# UI 组件整理（V5 UIComp）

## 使用边界

本文件整理常用 PC UI 组件的初始化方式。原始抽取文档存在 HTML 被拆成逐 token 的情况，Codex 应优先按这里的模式生成代码，再回查 `resources/docs/v5devUIComp_文档汇总.md`。

## Button

常见 class：

```html
<a href="javascript:void(0)" class="common_button">默认按钮</a>
<a href="javascript:void(0)" class="common_button common_button_emphasize">蓝色按钮</a>
<a href="javascript:void(0)" class="common_button common_button_gray">灰色按钮</a>
<a href="javascript:void(0)" class="common_button common_button_disable">按钮禁用</a>
<a href="javascript:void(0)" class="common_button common_button_icon">
  <em class="xicon xicon-affix"></em>带图标
</a>
```

## Grid 列表

初始化：

```js
var grid = $("#mytable").ajaxgrid({
  click: function (data, rowIndex, colIndex) {},
  dblclick: function (data, rowIndex, colIndex) {},
  render: function (txt, rowData, rowIndex, colIndex, colObj) {
    return txt;
  },
  colModel: [
    { display: 'id', name: 'orgid', width: '40', sortable: false, align: 'center', type: 'checkbox' },
    { display: '组织名称', name: 'orgname', width: '180', sortable: true, align: 'left' },
    { display: '父组织ID', name: 'parentid', width: '180', sortable: true, align: 'left', codecfg: "codeId:'test_code'" }
  ],
  width: 800,
  height: 200,
  managerName: "testPagingManager",
  managerMethod: "testPaging"
});
```

HTML：

```html
<table id="mytable" width="100%"></table>
```

## EditorTable 可编辑表格

依赖：

```jsp
<link rel="stylesheet" type="text/css" href="${path}/common/js/ui/seeEditorTable/css/seeEditorTable.css${ctp:resSuffix()}" />
<script src="${path}/common/js/ui/seeEditorTable/js/seeyon.ui.editorTable.min.js${ctp:resSuffix()}"></script>
```

初始化：

```js
var gridObj = $('#listSent').ajaxEditorGrid({
  colModel: [
    { display: "标题", name: 'subject', sortable: true, validator: 'NotEmpty', defVal: '无标题', width: 'big', validatorMsg: '标题不能为空' },
    { display: "发起时间", name: 'startDate', sortable: true, type: 'date', width: 'medium' },
    { display: "当前处理人", name: 'currentNodesInfo', sortable: true, validator: function (a) { return a.length <= 10; }, width: 'medium' }
  ],
  containerId: "mainPage",
  height: 250,
  autoload: false,
  gridType: 'autoGrid',
  showTableToggleBtn: true,
  managerName: "colManager",
  managerMethod: "getSentList"
});
```

## Dialog 弹窗

```js
function showMessageBox() {
  var dialog = $.dialog({
    targetWindow: window.parent,
    id: 'html',
    htmlId: 'htmlId',
    height: 100,
    title: 'html',
    bottomHTML: "<label class='margin_r_10 hand'><input type='checkbox' value='0' name='option' class='radio_com'>选项1</label>",
    overflow: 'hidden',
    buttons: [{
      text: "确定",
      handler: function () {
        dialog.close({ isFormItem: true });
      }
    }, {
      text: "取消",
      handler: function () {
        dialog.close();
      }
    }]
  });
  dialog.setTitle('弹窗框的自定义标题');
}
```

## Input 表单专用输入框

通过 `comp` 属性声明选择器类型和回调：

```html
<input type="text" name="name" class="comp" comp="type:'correlation_form',fun:'testFunction',title:'选择关联表单'">
<input type="text" name="name" class="comp" comp="type:'affix',fun:'testFunction',title:'插入附件'">
<input type="text" name="name" class="comp" comp="type:'associated_document',fun:'testFunction',title:'关联文档'">
<input type="text" name="name" class="comp" comp="type:'insert_pic',fun:'testFunction',title:'插入图片'">
```

## 核验清单

- [ ] 页面已引入对应 UI 组件 JS/CSS。
- [ ] `${path}`、`${ctp:resSuffix()}` 等平台变量没有被硬编码替换。
- [ ] `managerName` / `managerMethod` 后端存在。
- [ ] Dialog 的 `targetWindow` 在 iframe/父窗口场景正确。
- [ ] Grid render 函数做了 XSS/HTML 转义策略。
