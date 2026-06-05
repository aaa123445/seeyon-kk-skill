# CMP / M3 / 微协同移动 H5 整理

## 技术定位

CMP/M3 是移动端 H5 + 原生容器能力体系。页面通过 CMP/Cordova/Native API 调用设备能力，也可作为微协同集成到第三方 App/H5。

图片资料中的架构层次：

- M3 APP / 手机端 / Web / 微信等入口。
- ZIP 包、HTML 资源层。
- CMP Core、Fetch、i18n、Seajs、HTML/JS/TS/CSS。
- WebView / Cordova / Native API / 第三方组件。
- Network、Native、Local、API 能力。
- Android / iOS / Harmony 等原生系统。

## 页面开发规范

- UTF-8 编码。
- 首屏数据量控制在 1M 以内，超出部分异步加载。
- 禁止同步 Ajax。
- 尽量减少 div 嵌套。
- DOM 选择尽量使用 ID。
- 标签名、属性名小写。
- z-index 最高层级建议不超过 49。
- link 放 head，script 放 body 结尾。
- 业务逻辑入口放 `cmp.ready`：

```js
cmp.ready(function () {
  // business logic
});
```

- 移动端不建议引入 jQuery；如习惯 jQuery 可用 zepto 替代。
- 谨慎引入第三方库，考虑性能、稳定性、维护成本。

## CMP 依赖引入

M3 App 中示例：

```html
<link href="http://cmp/v/css/cmp.css" rel="stylesheet" type="text/css" />
<script src="http://cmp/v/js/cmp-i18n.js"></script>
<script src="http://cmp/v/js/cmp.js"></script>
```

第三方 App / 微信 / 钉钉等 URL 接入 OA H5 页面示例：

```html
<link href="/seeyon/m3/cmp/css/cmp.css" rel="stylesheet" type="text/css" />
<script src="/seeyon/m3/cmp/js/cmp-i18n.js"></script>
<script src="/seeyon/m3/cmp/js/cmp.js"></script>
```

图片资料补充的 JSP/平台变量依赖：

```jsp
<script src="${data:dependencies.cmp}/js/cmp.js?${data:buildversion}"></script>
<script src="${data:dependencies.cip}/js/cip.js?${data:buildversion}"></script>
<script src="${data:dependencies.cmp}/js/cmp-util.js?${data:buildversion}"></script>
<script src="${data:dependencies.cmp}/js/cmp-native.js?${data:buildversion}"></script>
<script src="${data:dependencies.cmp}/js/cmp-business.js?${data:buildversion}"></script>
<script src="${data:dependencies.common}/js/m3-path.js?${data:buildversion}"></script>
```

原则：不要引用不存在的依赖；依赖顺序以平台页面为准；保留 `?${data:buildversion}` 解决缓存刷新。

## 项目结构

```text
project/
├─ html/
│  └─ index.html
├─ js/
│  └─ index.js
├─ css/
├─ img/
└─ i18n/
   ├─ module_zh_CN.js
   ├─ module_zh_TW.js
   └─ module_en.js
```

## 路由与返回

微协同模式使用本地缓存 `CMPRouter`，页面跳转用 `pushState`，返回监听 `popstate`。

常用：

```js
cmp.href.next(url);
cmp.href.back();
```

返回按钮：

```js
cmp.ready(function () {
  cmp.backbutton();
  cmp.backbutton.push(function () {
    cmp.href.back();
  });
});
```

如果第三方 App WebView 没有正常触发 `popstate`，返回逻辑会异常，需要按第三方集成方案处理。

## 构建流程

V9.0 开始构建：

```bash
cd cmp-front
npm install
npm run build
```

构建完成生成 `release` 目录，再放入 S3 编译工具进行 M3 或微协同编译打包。

图片资料补充：

- 工程通常有 `package.json`、`gulpfile.js`、`node_modules`、`src`、`config`、`public`。
- 没有 `node_modules` 时先 `npm install`。
- 旧工程可能用 gulp task。
- S3Script 目录可包含 `java/`、`publishcmd/`、`publishoutput/`、`workspace/`、`batchbuild/`。

## i18n

多语言文件示例：

```text
i18n/
├─ mobileWork_en.js
├─ mobileWork_zh_CN.js
└─ mobileWork_zh_TW.js
```

文案不要全部硬编码在页面中，至少可扩展为 i18n 文件。

## 核验清单

- [ ] `cmp.ready` 包裹业务入口。
- [ ] 不使用同步 Ajax。
- [ ] CMP/CIP/Common 依赖路径适配运行环境。
- [ ] 路由返回在 M3/微协同/第三方 App 中都测试。
- [ ] i18n 文件命名正确。
- [ ] 构建产物 `release` 或 zip 能被 S3/M3 工具识别。
- [ ] 不硬编码本机绝对路径。
