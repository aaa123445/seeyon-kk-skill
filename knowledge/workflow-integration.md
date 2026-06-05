# 流程 / 表单 / 待办集成整理

## 适用场景

- 第三方系统发起 OA 协同、表单流程或 Html 正文流程。
- OA 流程状态同步到第三方待办/已办。
- 第三方待办接入 OA/CIP。
- 监听 OA 事件后推送第三方。

## 发起表单或 Html 正文流程

推荐 REST：

```text
POST /seeyon/rest/bpm/process/start
```

基础调用链：

1. 调用 REST token 接口获得 token（见 `api-auth-and-rest.md`）。
2. 准备 `appName=collaboration`。
3. 准备 `data`：
   - `templateCode`：模板编号，决定发起哪条流程；必须从 OA 模板配置中取得，不能猜。
   - `draft`：`0` 新建并发送，`1` 保存待发。
   - `subject`：标题；不传时可能取模板标题。
   - `attachments`：标题区附件 ID 列表。
   - `relateDoc`：关联文档/公文 ID。
   - `data`：表单字段数据。
   - `useNewDataStructure`、`doTrigger`：按版本/需求启用。
4. CAP3 表单必须传入所有参与计算公式的字段，否则可能报错。
5. CAP4 附件控件、子表、变更字段等要按文档的数据结构传入。

示意结构：

```json
{
  "appName": "collaboration",
  "data": {
    "templateCode": "asss_001",
    "draft": "0",
    "subject": "流程标题",
    "data": {
      "formmain_0018": {
        "申请人": "张三",
        "车牌号": "京A00000"
      }
    }
  }
}
```

## 模板编号与 activityId

- Html 正文流程模板编号：单位管理员 → 功能应用设置 → 协同应用设置 → 新建 → 高级 → 模板编号。
- 表单正文流程模板编号：表单管理员 → 表单应用 → 流程表单制作 → 新建 → 应用绑定 → 模板编号。
- `activityId` 可在流程图页面用 F12 Elements 定位节点 DOM，`node_id` 即 activityId。

## 统一待办事件

V8.2 以上优先使用统一事件：

```java
@ListenEvent(event = ExtIntegrationExtendEvent.class, async = true)
public void onExtIntegrationEvent(ExtIntegrationExtendEvent event) throws BusinessException {
    ExtSummary extSummary = event.getExtSummary();
    // 将待办/已办/终止/撤销/回退等状态同步给第三方
}
```

要点：

- `ExtIntegrationExtendEvent` 比旧 `ExtIntegrationEvent` 覆盖更广，支持协同、公文、会议、新闻、公告、调查、讨论等模块。
- `ExtSummary` 包含标题、summaryId、流程状态、发起人、当前处理人、PC URL、移动 URL、模块编码等信息。
- 同步第三方时必须做幂等：同一事项同一状态重复推送不能产生重复待办。

## 普通 Event 监听

通用写法：

```java
public class BbsEventListener {
    @ListenEvent(event = BbsAddEvent.class, async = true)
    public void bbsAddEvent(BbsAddEvent event) {
        // 从 event 中取参数，实现定制逻辑
    }
}
```

Spring Bean：

```xml
<bean id="bbsEventListener" class="com.seeyon.xxx.BbsEventListener"/>
```

## 第三方待办接入 CIP/OA

典型接口：

```text
REST认证：/seeyon/rest/token/{username}/{password}
单条待办：/seeyon/rest/thirdpartyPending/receive
多条待办：/seeyon/rest/thirdpartyPending/receive/pendings
更新状态：/seeyon/rest/thirdpartyPending/updatePendingState
```

关键字段：

- `registerCode`：注册系统编码。
- `taskId`：第三方待办主键，必须稳定唯一。
- `title`、`senderName`、`creationDate`。
- `state`：`0` 待办，`1` 已办。
- `thirdSenderId`、`thirdReceiverId`。
- `url`：PC 穿透地址。
- `h5url`：H5 穿透地址。
- `noneBindingSender` / `noneBindingReceiver`：未绑定时可用登录名/人员编码/手机号/邮箱。

## 核验清单

- [ ] 确认产品版本：V8.2SP1/V9.0 NEXT 会影响三方互信和 token。
- [ ] 确认模板编号、字段显示名/字段编码、子表编码。
- [ ] 确认附件上传接口返回的 ID 与 `attachments` / `thirdAttachments.fileUrl` 对应。
- [ ] 确认 CAP3 公式字段是否完整传入。
- [ ] 确认待办同步方向：OA 推第三方、第三方推 OA、第三方由 OA 定时读取。
- [ ] 确认人员映射：OA memberId/loginName/code/mobile/email 与第三方用户 ID。
- [ ] 确认幂等键：流程 summaryId/affairId/taskId + state。
