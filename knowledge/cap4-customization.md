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
