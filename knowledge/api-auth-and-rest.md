# REST 认证 / 三方互信 / 接口调用整理

## 基础 REST 调用

推荐 POST 获取 token：

```text
POST /seeyon/rest/token/
Content-Type: application/json
Accept: application/json
```

请求体示意：

```json
{
  "userName": "restName",
  "password": "restPassword",
  "loginName": "loginName"
}
```

业务接口调用时将 token 放到 header：

```text
token: <token-id>
```

示例业务接口：

```text
GET /seeyon/rest/affair/pending/count
```

## 版本差异与安全策略

- A6 产品线不支持 Rest 远程调用；如需定制一般使用 A8/V5。
- V8.2SP1 起，部分重要接口因安全要求不能只用普通 REST token，必须使用三方互信。
- V9.0 NEXT 起，三方互信实现有调整；如果获取 token 出现 IP 异常/500，要检查三方互信 IP 绑定。
- V9.0SP1+ 如果 REST 账号勾选了“校验 IP”但没有配置绑定 IP，会导致无法正确获取 TOKEN。
- 文档示例中 token 失效时长以 V8.2SP1 20221013 为例约 23 分钟，现场以版本为准。

## 三方互信触发条件

常见现象：

- 升级到 V8.2SP1+ 后，原接口出现 401。
- 升级到 V9.0 NEXT+ 后，原三方互信改造因未配置 IP 绑定导致 token 获取 500。
- 接口被配置到三方互信配置文件。

配置文件位置示例：

```text
ApacheJetspeed/webapps/seeyon/WEB-INF/cfgHome/base/dataSynchronizationAccessInfo.properties
ApacheJetspeed/webapps/seeyon/WEB-INF/cfgHome/base/dataSynchronizationAccessInfo.txt
```

文档中列出的受控接口示例：

```text
form/getformdata/{summaryIdOrAffairId}
affairData/pending/code/{memberCode}
com.seeyon.ctp.rest.resources.V8TicketResources#checkTicket#java.lang.String
com.seeyon.ctp.rest.resources.V8TicketResources#getDomainIds#java.lang.String,java.lang.Long
com.seeyon.ctp.rest.resources.V8TicketResources#getPluginInfo#java.lang.String
com.seeyon.ctp.rest.resources.V8TicketResources#getSysVarList#java.lang.String
com.seeyon.ctp.rest.resources.V8TicketResources#getSysByName#java.lang.String,java.lang.String,java.lang.Long
com.seeyon.ctp.rest.resources.V8TicketResources#getMemberRoles#java.lang.String,java.lang.Long
```

## Codex 实现建议

实现 Seeyon REST client 时，不要只写“拿 token 调接口”的 happy path，应包含：

1. baseUrl 标准化：`https://host/seeyon/rest`。
2. token 获取：POST JSON，支持旧式 path token 作为兼容选项。
3. token 缓存与过期刷新。
4. 401 自动诊断：提示可能需要三方互信/IP 绑定。
5. header 注入：`token`、`Accept`、`Content-Type`。
6. HTTPS 证书策略：生产不跳过校验，测试可配置。
7. 日志脱敏：不打印 password/token。
8. 接口失败时输出 method/url/status/body 摘要。

## 核验清单

- [ ] 产品线不是 A6。
- [ ] REST 账号、密码、登录名正确。
- [ ] IP 校验/绑定配置正确。
- [ ] 目标接口是否在三方互信配置中。
- [ ] token 放 header 而不是 query，除非现场旧接口要求。
- [ ] token 过期后能刷新。
- [ ] 401/500 错误有明确诊断，不要静默重试。
