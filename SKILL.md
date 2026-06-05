---
name: seeyon-kk-skill
description: Use when implementing Seeyon/致远/协同/CAP/CIP/CMP/OpenAPI/UIComp requirements with Codex. Classifies vague business requests such as “流程集成” into the right Seeyon documentation domain, implementation path, and verification checklist.
version: 1.0.0
author: Hermes Agent
license: MIT
metadata:
  hermes:
    tags: [seeyon, 致远, 协同, CAP, CIP, CMP, OpenAPI, Codex, integration]
    related_skills: [codex]
---

# Seeyon KK Skill

## Overview

Use this skill as Codex's routing brain for Seeyon/致远 work. The user may give a short business request like:

- “流程集成”
- “接入统一待办”
- “做 CAP 表单按钮”
- “第三方系统单点登录到协同”
- “微协同集成到企业微信/飞书”
- “前端做一个表格/弹窗/选择器”

Codex must not jump straight into coding from memory. It should first classify the request into a Seeyon domain, locate the relevant docs, inspect the current project, then implement with the matching platform conventions.

The detailed extracted document indexes live in:

- `references/seeyon-topic-routing-index.md` — compact topic-to-doc map for fast routing.
- `references/seeyon-doc-full-index.md` — full extracted document title/path/file index.

The source Markdown documentation is included in this repository under:

```text
resources/docs/
```

Codex should treat `resources/docs/` as the local documentation corpus. Do not rely on machine-specific paths such as `/root/.hermes/cache/documents`.

Important bundles:

```text
resources/docs/v5devCTP_文档汇总.md
resources/docs/seeyonapi_文档汇总.md
resources/docs/v5devCAP_文档汇总.md
resources/docs/v5devUIComp_文档汇总.md
resources/docs/cmpdev_文档汇总.md
resources/docs/v5devCMP_文档汇总.md
resources/docs/v5devCIP_文档汇总.md
resources/docs/v5doc_文档汇总.md
resources/docs/v5doc2_文档汇总.md
```

## When to Use

Use this skill when the task mentions any of:

- 致远、Seeyon、A8、A8-N、V5、协同、OA
- CAP、CAP3、CAP4、表单、业务包、无流程、有流程、运行态
- CIP、集成平台、第三方应用、单点登录、组织同步、待办集成、事件绑定
- CMP、M3、微协同、移动端、H5、企业微信、飞书审批、钉钉
- REST、OpenAPI、SeeyonAPI、三方互信、统一待办接口、事项服务
- UIComp、Button、Grid、Table、Tree、Dialog、Input、Select、Calendar
- 文档中心、智能合同、签章、套红、正文、Office/PDF
- 部署、升级、运维、宕机、CPU、内存、日志、系统监控

Do not use this skill for generic Java/Vue coding that has no Seeyon integration or platform dependency.

## Codex Operating Rule

When using Codex, pass a self-contained instruction like:

```text
You are implementing a Seeyon/致远 requirement. Load and follow the seeyon-kk-skill. First classify the user's request into one of the Seeyon domains, then search references/seeyon-topic-routing-index.md and the relevant extracted Markdown bundle under resources/docs/. Do not invent Seeyon APIs. Inspect the repo, identify its Seeyon version/module conventions, implement, and verify.

User requirement: <需求原文>
```

Codex must output or commit:

1. Requirement classification.
2. Docs consulted.
3. Implementation plan.
4. Code/config changes.
5. Verification evidence.
6. Remaining assumptions or required customer parameters.

## Domain Router

### 1. “流程集成 / 流程审批 / 发起流程 / 表单流程”

Route to:

- `seeyonapi` for REST/OpenAPI and form-flow APIs.
- `v5devCAP` for CAP form runtime, custom buttons, form plugin hooks, form frontend/backend APIs.
- `v5devCIP` when integration platform,待办集成,事件绑定,第三方应用接入 are involved.
- `v5devCTP` when server-side collaboration plugin/custom development is involved.

Start with these docs:

```text
seeyonapi: 表单流程集成 — /728/734.html
seeyonapi: 事项服务 — /728/748.html
seeyonapi: 统一待办接口 — /728/1820.html
seeyonapi: Event事件使用说明 — /1960/
v5devCAP: 发起表单(Html正文)流程 — /94/355/359/457/459.html
v5devCAP: 表单插件接口 — /94/355/359/399/405/407/
v5devCAP: 钩子相关接口 — /94/355/359/399/405/407/409.html
v5devCAP: 表单操作相关接口 — /94/355/359/399/405/407/410.html
v5devCAP: 表单运行态插件机制 — /94/355/359/399/405/412.html
v5devCIP: CIP集成平台-待办集成 — /250/256.html
v5devCIP: CIP集成平台-事件绑定 — /250/260.html
```

Implementation decision tree:

1. If requirement is “third-party system calls Seeyon to create/start/query workflow”, use `seeyonapi` first.
2. If requirement is “CAP form page/runtime behavior/button/hook”, use `v5devCAP` first.
3. If requirement is “external todo/event/data integration through platform config”, use `v5devCIP` first.
4. If requirement is “custom server plugin/listener/menu/portal in A8/V5”, use `v5devCTP` first.

Ask or infer these parameters before coding:

- Seeyon version: V8.2, V9.0, V9.0 NEXT, etc.
- Form type: CAP3/CAP4, 有流程/无流程, HTML 正文 or CAP form.
- Direction: third-party → Seeyon, Seeyon → third-party, or bidirectional.
- Auth: REST token, 三方互信, SSO/CAS, CIP app credentials.
- Identifiers: templateCode, formId, moduleId, affairId, memberId/loginName, org/account.
- Callback/event timing: before submit, after submit, node arrival, finish, cancel, revoke.

### 2. “接口集成 / REST / OpenAPI / 三方互信 / 统一待办”

Route to `seeyonapi`; combine with `v5devCIP` if the request says 集成平台/CIP.

Start docs:

```text
seeyonapi: 调用Rest接口 — /781/
seeyonapi: Rest三方互信接口(Since V8.2SP1) — /843/
seeyonapi: Rest三方互信(Since V9.0 NEXT) — /1956/
seeyonapi: 开放接口 — /728/
seeyonapi: 统一待办接口 — /728/1820.html
seeyonapi: CAP4表单应用接口 — /728/750.html
seeyonapi: Event事件使用说明 — /1960/
```

Implementation checklist:

1. Locate existing API client/auth wrapper in repo.
2. Identify base URL/context path and auth mode.
3. Implement typed request/response DTOs or adapters.
4. Add retry/timeouts/logging but never log secrets/tokens.
5. Add integration-test stubs or mock fixtures if no live Seeyon env is available.

### 3. “CIP集成 / 第三方应用 / 单点登录 / 组织同步 / 待办集成 / 事件绑定”

Route to `v5devCIP` first.

Start docs:

```text
v5devCIP: CIP集成平台-第三方应用功能说明 — /250/251.html
v5devCIP: CIP集成平台-待办集成 — /250/256.html
v5devCIP: CIP集成平台-事件绑定 — /250/260.html
v5devCIP: CIP集成平台-应用接入-应用菜单绑定 — /250/261.html
v5devCIP: CIP集成平台-用户绑定操作 — /250/252/253.html
v5devCIP: CIP集成平台-用户绑定 开发说明 — /250/252/254.html
v5devCIP: CIP集成平台-组织同步-接口同步 — /935/959.html
v5devCIP: 统一认证 — /936/
v5devCIP: CIP集成平台-统一认证-CAS认证设置说明 — /936/949/249.html
```

Implementation checklist:

1. Determine whether the solution is configuration-only in CIP or requires code/plugin.
2. Identify app registration, menu binding, user binding, org sync, todo sync, and event binding needs.
3. Produce config mapping tables: external user/org/app IDs ↔ Seeyon IDs.
4. For SSO, document assertion/token fields, redirect URLs, logout behavior, and clock skew.
5. Verify with a minimal end-to-end scenario: login/menu/todo/event callback.

### 4. “CAP表单 / 自定义控件 / 表单按钮 / 表单运行态 / 页面设计器”

Route to `v5devCAP`; use `v5devUIComp` for UI widgets.

Start docs:

```text
v5devCAP: cap4自定义控件-PC端 — /94/355/359/373/376.html
v5devCAP: CAP4自定义控件后端规范 — /94/355/359/373/377.html
v5devCAP: CAP4自定义控件 - 移动端 — /94/355/359/373/378.html
v5devCAP: CAP4表单前端接口 - 移动端 — /94/355/359/373/379.html
v5devCAP: CAP4无流程表单应用绑定自定义按钮开发文档 — /94/355/359/390/391.html
v5devCAP: 表单运行态插件机制 — /94/355/359/399/405/412.html
v5devCAP: cap3 表单运行态接口 — /94/470/475.html
v5devUIComp: Form 表单 — /components3.0/form/form.html
v5devUIComp: Input 表单专用-输入框 — /components3.0/form/input.html
```

Implementation checklist:

1. Determine CAP3 vs CAP4 and PC vs mobile.
2. Identify whether change is frontend component, backend spec, runtime hook, or form operation API.
3. Preserve platform lifecycle hooks; do not bypass form runtime state.
4. For custom controls, separate render, value binding, validation, and submit serialization.
5. Test create/edit/detail/submit paths, not only initial render.

### 5. “服务端插件 / 菜单栏目 / Portal / 监听器 / V5定制开发”

Route to `v5devCTP` and sometimes `v5devCAP`.

Start docs:

```text
v5devCTP: 插件化开发
v5devCTP: 如何定制开发
v5devCTP: 安装协同系统
v5devCTP: 开发环境搭建
v5devCTP: 代码版本管理
v5devCAP: 门户开发及栏目挂载 — /94/355/359/395/396.html
v5devCAP: 栏目开发及流程说明 — /94/355/359/395/397.html
v5devCAP: 插件使用步骤 — /94/355/359/399/405/406.html
seeyonapi: 菜单服务管理 — /728/745.html
```

Implementation checklist:

1. Inspect project packaging: plugin module, classpath, Spring config, extension XML, resource paths.
2. Match existing naming and deployment conventions.
3. Keep server customizations isolated; avoid modifying core platform files when plugin extension point exists.
4. Add logging and fail-safe behavior because platform plugins affect OA startup.
5. Provide deployment/restart steps.

### 6. “移动 / CMP / M3 / 微协同 / 企业微信 / 飞书 / 钉钉 / H5”

Route to `cmpdev` and `v5devCMP`.

Start docs:

```text
cmpdev: 前言 / 开发规范 / CMP核心知识
cmpdev: 微协同集成到第三方APP — H5inApp
cmpdev: 微协同集成到第三方H5 — wechatInH5
cmpdev: API — /api
v5devCMP: CMP API文档 — /93/550.html
v5devCMP: 移动H5应用开发 — /1271/1274.html
v5devCMP: 企业微信/飞书/钉钉相关集成与常见问题
```

Implementation checklist:

1. Determine runtime: M3 app, 微协同, third-party H5, 企业微信/飞书/钉钉 container.
2. Identify JS bridge/API availability and permission model.
3. Handle platform differences: Android/iOS/PC browser/debug container.
4. Provide debug path: vConsole, PC simulation, Android/iOS debug docs.

### 7. “前端组件 / UIComp / Button / Table / Dialog / Tree / Select”

Route to `v5devUIComp`.

Start docs:

```text
v5devUIComp: Button 按钮
v5devUIComp: Toolbar 区域
v5devUIComp: Grid 列表
v5devUIComp: Table 表格
v5devUIComp: Tree 树
v5devUIComp: Dialog 弹出框
v5devUIComp: Message / Notification / Alert
v5devUIComp: Input / Select / Calendar / Checkbox / Radio
```

Implementation checklist:

1. Determine UIComp V3.0 vs V4.0 and current frontend framework usage.
2. Reuse existing platform components/styles rather than adding unrelated UI libraries.
3. Implement examples matching doc patterns: object render vs comp render when applicable.
4. Test disabled/read-only/validation/event callback states.

### 8. “部署 / 升级 / 运维 / 故障排查 / 性能问题”

Route to `v5doc`.

Start docs:

```text
v5doc: 各版本部署手册
v5doc: 系统监控分析
v5doc: 通用宕机排查步骤
v5doc: 服务器CPU使用率高
v5doc: 服务器内存使用率高
v5doc: 协同Java进程CPU一直占用不释放
```

Implementation checklist:

1. Identify version, OS, database, middleware, deployment topology.
2. Collect logs, thread dumps, heap/GC, CPU/memory/disk/network facts before changing config.
3. Separate product config fix vs environment fix vs code fix.
4. Produce rollback steps for any config change.

### 9. “文档中心 / 智能合同 / 签章 / 正文 / Office/PDF”

Route to `v5doc2` and sometimes `v5devCIP`/`v5doc`.

Start docs:

```text
v5doc2: 文档中心
v5doc2: 文档中心常见问题
v5doc2: 智能合同
v5doc2: 智能合同产品文档清单
v5doc2: 智能合同管理_业务逻辑说明
v5devCIP: 签章平台相关集成插件文档
```

Implementation checklist:

1. Determine whether requirement is document storage, preview, edit, contract lifecycle, seal/signature, or integration.
2. Check file format handling and permission model.
3. Preserve business-facing document abstractions; do not expose implementation internals unless required.

## Fast Search Commands for Codex

When inside a repo or shell with extracted docs available:

```bash
DOCS=resources/docs
rg -n "流程集成|统一待办|事项服务|Event事件" "$DOCS/seeyonapi_文档汇总.md" "$DOCS/v5devCAP_文档汇总.md" "$DOCS/v5devCIP_文档汇总.md"
rg -n "三方互信|Rest|token|认证" "$DOCS/seeyonapi_文档汇总.md"
rg -n "CAP4|自定义控件|表单运行态|按钮" "$DOCS/v5devCAP_文档汇总.md"
rg -n "CIP集成平台|单点登录|组织同步|待办集成|事件绑定" "$DOCS/v5devCIP_文档汇总.md"
rg -n "微协同|M3|H5|企业微信|飞书|钉钉" "$DOCS/cmpdev_文档汇总.md" "$DOCS/v5devCMP_文档汇总.md"
rg -n "Button|Table|Dialog|Select|Tree|Grid" "$DOCS/v5devUIComp_文档汇总.md"
```

If `rg` is not available, use `grep -R` or inspect `references/seeyon-topic-routing-index.md` first.

## Codex Response Template

For every Seeyon task, Codex should structure the response like:

```text
## 需求识别
- 需求类型：<流程集成/API/CIP/CAP/CMP/UI/运维/...>
- 涉及平台：<CTP/seeyonapi/CAP/CIP/CMP/UIComp/...>
- 需要确认：<版本/认证/模板编号/人员组织映射/...>

## 文档依据
- <doc title> — <site/path>
- <doc title> — <site/path>

## 实施方案
1. <step>
2. <step>
3. <step>

## 修改内容
- <files/configs>

## 验证
- <tests/checks/manual scenario>

## 风险与假设
- <risk>
```

## Example: User Says “流程集成”

Classify as workflow/form integration. Do not assume it is only one API.

Decision path:

1. If the requirement says third-party system must create/start Seeyon workflows, search `seeyonapi: 表单流程集成` and `v5devCAP: 发起表单(Html正文)流程`.
2. If the requirement says unified todo or external todo sync, search `seeyonapi: 统一待办接口` and `v5devCIP: 待办集成`.
3. If the requirement says callbacks/events before/after workflow actions, search `Event事件使用说明`, `v5devCAP: 事件API支持`, `v5devCAP: 钩子相关接口`, and `v5devCIP: 事件绑定`.
4. If the requirement is inside a CAP form page, search `CAP4表单应用接口`, `表单运行态插件机制`, and custom button docs.

Minimum questions if missing:

```text
1. 是第三方系统发起协同流程，还是协同流程回调第三方？
2. 是 CAP3/CAP4 表单、HTML 正文流程，还是普通协同事项？
3. 当前协同版本是多少？是否使用三方互信/REST token/CIP？
4. 是否涉及统一待办、组织人员同步、事件回调？
```

If repo has enough config to infer these, Codex should infer and state assumptions instead of asking.

## Common Pitfalls

1. **Treating “流程集成” as a single API.** It can mean start workflow, sync todo, bind event, CAP runtime hook, or CIP integration.
2. **Mixing CAP3 and CAP4.** Always identify form generation/runtime version.
3. **Ignoring version differences.** REST 三方互信 differs across V8.2SP1 and V9.0 NEXT docs.
4. **Hardcoding user/org IDs.** Use mapping/config and document source of truth.
5. **Bypassing CIP when the customer expects platform configuration.** Some integrations should be configured in CIP, not custom-coded.
6. **Adding generic frontend libraries where UIComp exists.** Prefer Seeyon UI components and existing styles.
7. **Inventing Seeyon APIs.** Search the extracted docs first; cite the title/path used.
8. **Only testing the happy path.** Workflow/CAP tasks must test create, edit, submit, callback, cancel/revoke where relevant.

## Verification Checklist

- [ ] Requirement classified into a Seeyon domain.
- [ ] Relevant docs searched in `references/seeyon-topic-routing-index.md` or extracted bundles.
- [ ] Seeyon version/auth/form type/integration direction identified or listed as assumptions.
- [ ] Current repo conventions inspected before coding.
- [ ] Code/config changes are isolated to the intended module.
- [ ] No credentials/tokens logged.
- [ ] Tests or manual verification scenario provided.
- [ ] Deployment/rollback notes included when plugin/config changes affect platform startup.
