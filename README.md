# seeyon-kk-skill

Codex/Hermes skill for Seeyon/致远 requirements. It helps an agent classify short business requests such as “流程集成” into the right Seeyon domain, documentation entry, implementation path, and verification checklist.

## What it covers

- Seeyon/致远 A8/A8-N/V5/协同
- seeyonapi REST/OpenAPI/三方互信/统一待办/事项服务
- CAP/CAP3/CAP4 表单、运行态、自定义控件、按钮、插件
- CIP 集成平台、第三方应用、单点登录、组织同步、待办集成、事件绑定
- CMP/M3/微协同/H5/企业微信/飞书/钉钉
- UIComp V3/V4 组件库
- v5doc/v5doc2 部署运维、文档中心、智能合同等

## Files

```text
SKILL.md
references/
  seeyon-topic-routing-index.md   # compact topic routing index
  seeyon-doc-full-index.md        # full extracted title/path index
  seeyon-index.json               # structured index for automation/RAG
resources/docs/
  v5devCTP_文档汇总.md
  v5devCTP_文档目录.md
  seeyonapi_文档汇总.md
  seeyonapi_文档目录.md
  v5devCAP_文档汇总.md
  v5devCAP_文档目录.md
  v5devUIComp_文档汇总.md
  v5devUIComp_文档目录.md
  cmpdev_文档汇总.md
  cmpdev_文档目录.md
  v5devCMP_文档汇总.md
  v5devCMP_文档目录.md
  v5devCIP_文档汇总.md
  v5devCIP_文档目录.md
  v5doc_文档汇总.md
  v5doc_文档目录.md
  v5doc2_文档汇总.md
  v5doc2_文档目录.md
```

## Usage with Codex

Example prompt:

```text
你是 Codex，请加载并遵循 seeyon-kk-skill。

用户需求：
流程集成

请先识别这是致远哪个领域的需求，然后查询 seeyon-kk-skill references 中的路由索引和相关抽取文档，不要凭空编造致远 API。最后给出实现方案、需要确认的参数、代码修改点和验证方式。
```

## Install into Hermes local skills

```bash
mkdir -p ~/.hermes/skills/seeyon-kk-skill
cp SKILL.md ~/.hermes/skills/seeyon-kk-skill/SKILL.md
cp -r references ~/.hermes/skills/seeyon-kk-skill/
cp -r resources ~/.hermes/skills/seeyon-kk-skill/
```

Then start a new Hermes session so the skill loader can pick it up.

## Source corpus

This skill was condensed from extracted documentation indexes for:

- https://open.seeyoncloud.com/v5devCTP/
- https://open.seeyoncloud.com/seeyonapi/
- https://open.seeyoncloud.com/v5devCAP/
- https://open.seeyoncloud.com/v5devUIComp/
- https://open.seeyoncloud.com/cmpdev/
- https://open.seeyoncloud.com/v5devCMP/
- https://open.seeyoncloud.com/v5devCIP/
- https://open.seeyoncloud.com/v5doc/
- https://open.seeyoncloud.com/v5doc2/
