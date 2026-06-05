# 图片资料整理结论（OCR + 视觉识别）

> 来源：`resources/images/` 中 16 张从在线文档下载的图片，OCR 原始结果见 `resources/image-ocr.md`，图片索引见 `resources/image-index.json`。OCR 对低分辨率截图/流程图会有误识别，本文件是结合 OCR 与视觉识别后的整理版。

## 总体结论

图片资料主要补充了三类知识：

1. **CMP/M3 移动端前端开发**：Node/npm/gulp 构建，CMP JS 依赖，i18n 多语言，移动端应用配置，H5 + Cordova/Native 架构。
2. **CIP/Seeyon 平台集成配置**：应用/菜单/入口配置，浏览器调试接口，后台管理页面配置，第三方业务系统入口集成。
3. **部署与运行环境**：Windows 构建目录，发布输出目录，批量构建脚本，DM 数据库连接配置，测试连接。

## 对 Codex 有用的落地规则

- 生成 CMP 页面时必须按平台方式引入依赖，常见包括 `cmp.js`、`cmp-i18n.js`、`cip.js`、`cmp-util.js`、`cmp-native.js`、`cmp-business.js`，并使用 `${data:dependencies.xxx}` / `?${data:buildversion}` 等平台变量，不要硬编码本机路径。
- CMP/M3 应用构建通常是 Node + npm + gulp/npm scripts：检查 `package.json`、安装 `node_modules`、执行 `npm run build` 或 gulp task、生成 `release`，再放入 S3 编译/打包工具生成 M3/微协同包。
- 移动 H5 项目建议结构：`html/`、`js/`、`css/`、`img/`、`i18n/`，多语言文件按 `模块名_zh_CN.js`、`模块名_en.js`、`模块名_zh_TW.js` 命名。
- 应用上线不只是代码：还要配置 app 编码、名称、版本、入口 URL、图标、权限范围、菜单绑定、移动端展示参数。
- 集成 CIP/Seeyon 时要处理 SSO/token/session/cookie、用户/组织映射、菜单入口、PC/H5 穿透 URL。
- 调试 CIP/Seeyon 页面优先用浏览器开发者工具 Network/Console/Elements 反查真实请求 URL、参数、响应 JSON、headers、Cookie/CSRF/token。
- 数据库/信创场景要关注达梦 DM：JDBC URL、驱动、方言、SQL 兼容性、连接池、测试连接。
- 百度 logo 示例图本身无技术价值，只可作为图片资源加载/GIF 支持示例，不能推导 Seeyon API。
