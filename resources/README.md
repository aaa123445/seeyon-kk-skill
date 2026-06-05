# resources/docs

This directory contains the Markdown documentation corpus used by `seeyon-kk-skill`.

Codex should search this directory directly instead of relying on machine-local paths.

## Corpus files

| Site | Summary | Index |
|---|---|---|
| v5devCTP | `docs/v5devCTP_文档汇总.md` | `docs/v5devCTP_文档目录.md` |
| seeyonapi | `docs/seeyonapi_文档汇总.md` | `docs/seeyonapi_文档目录.md` |
| v5devCAP | `docs/v5devCAP_文档汇总.md` | `docs/v5devCAP_文档目录.md` |
| v5devUIComp | `docs/v5devUIComp_文档汇总.md` | `docs/v5devUIComp_文档目录.md` |
| cmpdev | `docs/cmpdev_文档汇总.md` | `docs/cmpdev_文档目录.md` |
| v5devCMP | `docs/v5devCMP_文档汇总.md` | `docs/v5devCMP_文档目录.md` |
| v5devCIP | `docs/v5devCIP_文档汇总.md` | `docs/v5devCIP_文档目录.md` |
| v5doc | `docs/v5doc_文档汇总.md` | `docs/v5doc_文档目录.md` |
| v5doc2 | `docs/v5doc2_文档汇总.md` | `docs/v5doc2_文档目录.md` |

## Search examples

```bash
DOCS=resources/docs
rg -n "流程集成|统一待办|事项服务|Event事件" "$DOCS/seeyonapi_文档汇总.md" "$DOCS/v5devCAP_文档汇总.md" "$DOCS/v5devCIP_文档汇总.md"
rg -n "CAP4|自定义控件|表单运行态|按钮" "$DOCS/v5devCAP_文档汇总.md"
rg -n "CIP集成平台|单点登录|组织同步|待办集成|事件绑定" "$DOCS/v5devCIP_文档汇总.md"
```
