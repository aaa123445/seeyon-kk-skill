# CAP4 自定义控件 / 插件 / 按钮整理

## 自定义控件定位

CAP4 自定义控件是寄生在表单上的第三方组件：

- 表单负责生成 DOM 容器、提供基础数据和交互 API。
- 控件自己加载 CSS/JS、渲染、处理内部事件，可回填标准控件或保存自己的数据。
- 控件可以有 PC 端、移动端、后端 Java 部分。

## 后端规范要点

文档明确提到：

- CAP4 自定义控件后端类实现/继承：`com.seeyon.cap4.form.bean.fieldCtrl.FormFieldCustomCtrl`。
- CAP4 无流程表单应用自定义按钮后端类继承：`com.seeyon.cap4.form.bean.button.CommonBtn`。

注意：这些类名来自在线文档抽取，真正开发前必须在现场 SDK/源码包确认 import、抽象方法、版本差异。

## 自定义控件包结构

典型目录：

```text
seeyon/
├─ apps_res/
│  └─ cap/
│     └─ customCtrlResources/
│        └─ <controlResource>/
│           ├─ html/
│           ├─ js/
│           ├─ css/
│           └─ images/
├─ m3files/
│  └─ v5/
│     └─ <mobile-resource>.zip
└─ WEB-INF/
   ├─ cfgHome/
   │  └─ plugin|component/
   │     └─ <pluginName>/
   │        ├─ pluginCfg.xml
   │        ├─ i18n/
   │        │  ├─ *_zh_CN.properties
   │        │  ├─ *_zh_TW.properties
   │        │  └─ *_en.properties
   │        └─ spring/
   │           └─ spring-*-manager.xml
   ├─ classes/
   │  └─ com/seeyon/cap4/form/bean/fieldCtrl/<Control>.class
   ├─ jsp/
   └─ lib/
```

固定目录不要随意改名：`seeyon`、`apps_res`、`WEB-INF`、`cfgHome` 等是平台识别路径。

## 让设计器出现控件

1. 按目录结构组织项目。
2. 创建 Java 类，实现/继承平台抽象类。
3. 返回唯一控件 key；可用平台 UUID 工具生成。
4. 配置 plugin/component、spring、i18n。
5. 放置 PC 前端资源和 M3 移动资源包。
6. 部署到 V5 环境；商城下载包通常在重启后解压部署生效。

设计器左侧不显示时，先查后端发现链路，不要先调运行态 JS：

- 优先按 `WEB-INF/cfgHome/component/<componentId>/pluginCfg.xml` + `spring/spring-*-manager.xml` 组织表单编辑器控件；`pluginCfg.xml` 的 `<id>`、目录名、`init()` 里的 `setPluginId(...)` 保持一致。
- 在 Spring XML 中显式注册 `FormFieldCustomCtrl` 子类：`<bean id="..." class="..."/>`。仅靠 `@Component` 或业务 plugin 的 component-scan 可能不足以被设计器发现。
- 覆盖无参 `canUse()` 并返回 `true`；如果现场 SDK 默认 `canUse()` 依赖 `AppContext.hasPlugin("cap4") && isValid()`，未显式覆盖可能被过滤。
- 字段内按钮型自定义控件仍然继承 `FormFieldCustomCtrl`，不是无流程列表按钮的 `CommonBtn`。如果控件是按钮类，覆盖 `isButton()` 返回 `true`，并在 `init()` 中调用 `setButtonType(Enums.ButtonType.CustomBtn)`；当前 SDK 的 `toJsonObject()` 会在按钮类控件上读取 `getButtonType()` 写入 `btnType`。
- `getPCInjectionInfo()` / `getMBInjectionInfo()` 影响运行态资源加载；设计器是否出现主要取决于后端 bean、`canUse()`、plugin/component 配置和实际部署产物。
- 不要用旧包验证。确认部署到 OA 的产物里真实包含后端 class、component XML 和 `apps_res/cap/customCtrlResources/<ctrl>/` 资源；本地旧 `target/*.jar` 不含新增控件时，线上部署它必然不显示。

服务器快速核验示例：

```bash
OA_HOME=/data/Seeyon/V5/ApacheJetspeed/webapps/seeyon
find "$OA_HOME" \( \
  -path '*/WEB-INF/classes/com/seeyon/**/<Ctrl>.class' -o \
  -path '*/WEB-INF/cfgHome/component/<componentId>/pluginCfg.xml' -o \
  -path '*/WEB-INF/cfgHome/component/<componentId>/spring/spring-*-manager.xml' -o \
  -path '*/apps_res/cap/customCtrlResources/<ctrl>/js/*' \
\) -print
```

重启后再查日志中自定义控件 `init()` 日志；没有 init 日志时，优先排查 classpath、Spring XML、component 目录和部署包是否生效。

## PC 前端规范

建议结构：

```text
./
├─ js/
├─ css/
├─ icon/
└─ index.html
```

入口规则：

- 前端生成唯一标识，挂到全局命名空间。
- 控件代码中的 `this` 指向 `window[唯一标识]`。
- 必须有初始化入口方法，并配置到控件配置文档中。
- 建议闭包开发，避免污染全局。

入口方法参数一般是 Object，核心字段：

- `adaptation`：平台提供的 API 集合，用于与表单页面通信。
- `url_prefix`：资源 URL 前缀，用于加载 CSS/JS。
- `privateId`：当前控件在表单页面上的唯一标识。
- `getData`：当前控件初始数据。

`getData` 常见内容：附件信息、attrs、权限 auth（edit/hide）、ctrlType（自定义控件为 `suiCustomControl`）、customFieldInfo、display、enums、extra 等。

## 运行态 JS 未加载排查

CAP4 表单运行态会根据字段定义里的 `customFieldInfo` 下载自定义控件主 JS。Network 中完全没有对应 `runtime.js` 请求时，先查字段定义中的 `customFieldInfo.path/jsUri/nameSpace/version`，不要先调试运行态 JS 代码。

`FormFieldCustomCtrl#getPCInjectionInfo()` 里的 `jsUri` 保持平台示例的静态相对路径，不要拼 `?v=时间戳` 这类 query 参数。部分 CAP4 运行态会把 `jsUri` 当资源逻辑路径处理，`js/runtime.js?v=...` 可能导致主 JS 不下载。

推荐写法：

```java
@Override
public String getPCInjectionInfo() {
    return "{path:'apps_res/cap/customCtrlResources/<ctrl>/',jsUri:'js/runtime.js',initMethod:'init',nameSpace:'field_" + this.getKey() + "'}";
}
```

需要破缓存时，优先重新部署资源、清浏览器缓存、重启/重扫资源，或使用文件名版本化；不要在 `jsUri` 上追加 query。

带 `-` 的 UUID/key 本身不是运行态加载失败原因。CAP4 2.0 示例也允许 `csdk.component.register('myWidget-12345678', ...)` 这类标识；如同时暴露到 `window`，使用 `window[nameSpace]` 访问，避免点号访问带横线的属性。

## 表单运行态插件机制

资源路径：

```text
PC:   /seeyon/common/capextend
微协同: /seeyon/m3/apps/v5/capextend
M3:   /seeyon/m3files/v5/88.zip
```

历史版本注意：7.1SP1 930 前表单插件路径为 `/seeyon/common/cap4/extend`。

页面类型：

- `form`：表单。
- `query`：查询列表。
- `unflow`：无流程列表。
- `todo`：待办列表。

插件示例路径：

```text
/seeyon/common/capextend/cap4/form/utils/pluginA/index.js
/seeyon/m3/apps/v5/capextend/cap4/form/utils/pluginA/index.js
http://capextend.v5.cmp/v/cap4/utils/pluginA/index.js
```

白名单插件：

- 与普通插件目录同级，如 `.../form/whiteList/`。
- 默认不加载，需要在设计器高级配置中设置。
- 白名单表：`cap_form_plugin_whitelist`。

重扫资源：

```text
GET /seeyon/rest/cap4/form/initFormPlugins
```

插件脚本加载：

```text
/seeyon/rest/cap4/form/pluginScripts?page=form&v=cap4&client=pc&moduleId=...&moduleType=1
/seeyon/rest/cap4/form/pluginScripts?page=unflow&v=cap4&client=pc&bussId=...&appId=...&formId=...
```

## 自定义按钮

CAP4 无流程表单应用绑定自定义按钮自 V7.1 起支持。开发模式与自定义控件类似，也是 plugin/component。

后端：

```java
public class NewFormDataBtn extends CommonBtn {
    // 按现场 SDK 重写必要方法
}
```

前端资源通常放在 `apps_res/cap/customCtrlResources/<buttonResources>/`，后端配置放 `WEB-INF/cfgHome/component/<componentName>/`。

## 表单插件 API 调用注意

- CSDK 调用有回调的 API 时，必须等上一个接口返回再调下一个。
- 循环调用 `addRecord` 不合理；多条新增应优先使用 `addRecords`。
- 多次 `addRecord` / `deleteRecord` 要串行等待回调。

## 核验清单

- [ ] 现场 SDK 中确认 `FormFieldCustomCtrl` / `CommonBtn` 包名和抽象方法。
- [ ] 控件 key 唯一且稳定。
- [ ] PC、微协同、M3 资源路径都覆盖。
- [ ] pluginCfg、spring bean、i18n 文件齐全。
- [ ] 修改资源后执行重扫或按版本要求重启。
- [ ] 白名单插件已配置设计器高级配置和表。
- [ ] 移动端 88.zip 目录结构与微协同路径一致。
