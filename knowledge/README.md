# Seeyon / 致远文档整理知识库总览

本目录是对 `resources/docs/` 原始抽取文档、`resources/images/` 图片、`resources/image-ocr.md` OCR 结果重新整理后的 Codex 友好知识库。不要让 Codex 只啃原始抽取数据；应先看本目录，再按需回查原始文档。

## 资源分层

- `knowledge/`：整理后的专题知识，优先阅读。
- `resources/docs/`：在线文档抽取原文，作为证据和细节回查。
- `resources/images/`：在线文档中的图片资源。
- `resources/image-ocr.md`：图片 OCR 原始文本。
- `resources/image-index.json`：图片来源、章节、下载状态、OCR 文件映射。
- `references/seeyon-topic-routing-index.md`：主题路由索引。
- `references/seeyon-doc-full-index.md`：完整文档标题/路径索引。
- `references/seeyon-index.json`：机器可读索引。

## 需求路由表

| 用户说法/需求 | 优先看 | 典型实现路线 | 必须核验 |
|---|---|---|---|
| 流程集成、发起流程、表单流程、Html 正文流程 | `workflow-integration.md` + `api-auth-and-rest.md` | REST 获取 token → `/seeyon/rest/bpm/process/start` → templateCode/data/attachments | 模板编号、字段名、CAP3/CAP4数据结构、token/三方互信 |
| 待办集成、统一待办、第三方待办 | `workflow-integration.md` + `cip-integration.md` | OA 内监听 `ExtIntegrationExtendEvent` 或 CIP 第三方待办推送/读取 | app/registerCode、taskId、PC/H5 URL、状态同步、人员映射 |
| 事件绑定、人员/组织变化触发第三方 | `cip-integration.md` + `workflow-integration.md` | CIP 内置事件绑定 URL/接口，或 OA Event `@ListenEvent` | 事件参数、触发条件、接口参数映射、幂等 |
| 组织同步、用户同步 | `cip-integration.md` | CIP 接口同步，绑定集团/单位/部门/岗位/职务/人员/任职/兼职模型 | 最少部门+人员接口、主岗唯一、树形部门、增量时间戳 |
| CAP4 自定义控件、控件后端、控件前端 | `cap4-customization.md` | 插件/component 包结构 → Java 类继承/实现指定抽象类 → PC/移动资源 → pluginCfg/spring/i18n | 类名以现场 SDK 为准、重启/扫描、资源路径、唯一 key |
| CAP4 自定义按钮、无流程表单按钮 | `cap4-customization.md` | 后端继承 `CommonBtn`，前端放 `customCtrlResources`，配置 component/plugin | 按钮类、入口方法、权限/绑定配置 |
| 表单运行态插件、白名单插件 | `cap4-customization.md` | `/seeyon/common/capextend/...` 放资源 → initFormPlugins 重扫 → pluginScripts 加载 | page/v/client/moduleId 参数、白名单表 |
| 移动端 H5、M3、微协同、CMP 页面 | `cmp-mobile-h5.md` | CMP 目录结构 + cmp.ready + cmp.href/backbutton + 平台 JS/CSS | 不引 jQuery、依赖顺序、缓存版本、i18n、性能 |
| UI 控件、Grid/Table/Dialog/Input/Button | `ui-components.md` | 使用平台 UI 组件 class/plugin 初始化 | `${path}`、managerName/method、targetWindow、comp 属性 |
| 系统卡顿、CPU高、内存高、宕机 | `ops-troubleshooting.md` | 系统监控 → OS top/free → JVM/GC/thread dump/heap dump → 日志 | G1GC、老年代、连接池、进程存活、hprof/hs_err |
| 文档中心、智能合同、签章 | `document-contract.md` | 先判定文档服务/签章平台/CIP 接入边界 | 版本、接口能力、业务口径，避免臆造 |

## Codex 工作流

1. 先根据用户短需求在上表选专题。
2. 阅读对应 `knowledge/*.md` 的“实现路线”和“核验清单”。
3. 用 `references/*index*` 找原始文档位置；必要时用 `grep -R` 在 `resources/docs/` 中回查原文。
4. 若涉及图片中的流程/目录/配置，查 `knowledge/image-derived-insights.md` 和 `resources/image-ocr.md`。
5. 只把原始文档作为依据，不要把抽取乱码/低质量 OCR 直接当最终答案；最终要整理成业务可执行方案。

## 重要边界

- 文档中出现的 Java 类名/接口名，如 `FormFieldCustomCtrl`、`CommonBtn`、`ExtIntegrationExtendEvent` 等，可作为已抽取文档依据；但现场 SDK 版本可能差异，真正编码前必须在客户现场 SDK/源码包中二次确认 import 包名和方法签名。
- A6 产品线不支持 Rest 远程调用；定制开发通常需要 A8/V5 产品线。
- V8.2SP1+、V9.0 NEXT+ 安全策略变化会影响 REST token/三方互信/IP 校验。
