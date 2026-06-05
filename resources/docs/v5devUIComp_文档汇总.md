# Seeyon V5 Dev UIComp 文档汇总

- 来源：https://open.seeyoncloud.com/v5devUIComp/
- 提取文档数：72
- 说明：该站点未提供完整 Markdown search content；本文件从 VuePress 页面清单和异步页面 render chunk 中抽取文本、图片等内容整理。

## 目录

1. [更新记录](#更新记录) — `/`
2. [Button 按钮](#button-按钮) — `/components3.0/basic/button.html`
3. [表单专用-button](#表单专用-button) — `/components3.0/basic/capbutton.html`
4. [Toolbar 区域](#toolbar-区域) — `/components3.0/basic/toolbar.html`
5. [EditorTable 可编辑table](#editortable-可编辑table) — `/components3.0/data/editorTable.html`
6. [Grid 列表](#grid-列表) — `/components3.0/data/grid.html`
7. [OverPage 翻页](#overpage-翻页) — `/components3.0/data/overPage.html`
8. [Scheduler 日程视图](#scheduler-日程视图) — `/components3.0/data/scheduler.html`
9. [Table 表格](#table-表格) — `/components3.0/data/table.html`
10. [Tree 树](#tree-树) — `/components3.0/data/tree.html`
11. [Calender 时间控件](#calender-时间控件) — `/components3.0/form/calender.html`
12. [Checkbox 复选](#checkbox-复选) — `/components3.0/form/checkbox.html`
13. [Form 表单](#form-表单) — `/components3.0/form/form.html`
14. [Input 表单专用-输入框](#input-表单专用-输入框) — `/components3.0/form/input.html`
15. [Link 链接](#link-链接) — `/components3.0/form/link.html`
16. [Radio 单选](#radio-单选) — `/components3.0/form/radio.html`
17. [SearchBox 查询组件](#searchbox-查询组件) — `/components3.0/form/searchBox.html`
18. [upload 上传组件](#upload-上传组件) — `/components3.0/form/upload.html`
19. [Fieldset 分组框](#fieldset-分组框) — `/components3.0/layout/fieldset.html`
20. [Layout 拖拽布局](#layout-拖拽布局) — `/components3.0/layout/layoutDrag.html`
21. [StaticLayout 静态布局](#staticlayout-静态布局) — `/components3.0/layout/staticLayout.html`
22. [Tab 页签](#tab-页签) — `/components3.0/layout/tab.html`
23. [Breadcrumb 面包屑](#breadcrumb-面包屑) — `/components3.0/navigation/breadcrumb.html`
24. [返回顶部按钮](#返回顶部按钮) — `/components3.0/navigation/gototop.html`
25. [MenuSimple 简易菜单](#menusimple-简易菜单) — `/components3.0/navigation/menuSimple.html`
26. [ProgressBar 进度条](#progressbar-进度条) — `/components3.0/navigation/progressBar.html`
27. [StepTab 向导菜单](#steptab-向导菜单) — `/components3.0/navigation/stepTab.html`
28. [Dialog 弹出框](#dialog-弹出框) — `/components3.0/notice/dialog.html`
29. [Message 消息提示](#message-消息提示) — `/components3.0/notice/message.html`
30. [MessageBox 提示窗口](#messagebox-提示窗口) — `/components3.0/notice/messageBox.html`
31. [tooltip 气球状提示](#tooltip-气球状提示) — `/components3.0/notice/tooltip.html`
32. [打印](#打印) — `/components3.0/other/print.html`
33. [seeyon v4.0 组件](#seeyon-v40-组件) — `/components3.0/seeyon.html`
34. [seeyon v3.0 组件](#seeyon-v30-组件) — `/components3.0/seeyon3.0.html`
35. [Color 色彩](#color-色彩) — `/components4.0/basic/color.html`
36. [Typography 字体](#typography-字体) — `/components4.0/basic/typography.html`
37. [Badge 标记](#badge-标记) — `/components4.0/data/badge.html`
38. [Progress 进度条](#progress-进度条) — `/components4.0/data/progress.html`
39. [Table 表格](#table-表格) — `/components4.0/data/table.html`
40. [Tag 标签](#tag-标签) — `/components4.0/data/tag.html`
41. [TreeGrid 树形列表](#treegrid-树形列表) — `/components4.0/data/treeGrid.html`
42. [Attachment 全屏拖拽上传组件](#attachment-全屏拖拽上传组件) — `/components4.0/form/attachment.html`
43. [Calendar 日历](#calendar-日历) — `/components4.0/form/calendar.html`
44. [Calendar 时间段选择](#calendar-时间段选择) — `/components4.0/form/calendarRange.html`
45. [Cascader 级联选择器](#cascader-级联选择器) — `/components4.0/form/cascader.html`
46. [Checkbox 多选框](#checkbox-多选框) — `/components4.0/form/checkbox.html`
47. [Input 输入框](#input-输入框) — `/components4.0/form/input.html`
48. [InputNumber 输入框](#inputnumber-输入框) — `/components4.0/form/inputNumber.html`
49. [Calendar 月份段选择](#calendar-月份段选择) — `/components4.0/form/monthRange.html`
50. [Radio 单选框](#radio-单选框) — `/components4.0/form/radio.html`
51. [Rate 评分](#rate-评分) — `/components4.0/form/rate.html`
52. [Select 选择器](#select-选择器) — `/components4.0/form/select.html`
53. [Slider 滑块](#slider-滑块) — `/components4.0/form/slider.html`
54. [Switch 开关](#switch-开关) — `/components4.0/form/switch.html`
55. [TextArea 输入框](#textarea-输入框) — `/components4.0/form/textArea.html`
56. [TimePicker 时间选择器](#timepicker-时间选择器) — `/components4.0/form/timePicker.html`
57. [Breadcrumb 面包屑](#breadcrumb-面包屑) — `/components4.0/navigation/breadcrumb.html`
58. [Dropdown 下拉菜单](#dropdown-下拉菜单) — `/components4.0/navigation/dropdown.html`
59. [NavMenu 导航菜单](#navmenu-导航菜单) — `/components4.0/navigation/navMenu.html`
60. [Steps 步骤条](#steps-步骤条) — `/components4.0/navigation/steps.html`
61. [Tabs 标签页](#tabs-标签页) — `/components4.0/navigation/tabs.html`
62. [Alert 警告提示](#alert-警告提示) — `/components4.0/notice/alert.html`
63. [Loading 加载](#loading-加载) — `/components4.0/notice/loading.html`
64. [Message 消息提示](#message-消息提示) — `/components4.0/notice/message.html`
65. [Notification 通知](#notification-通知) — `/components4.0/notice/notification.html`
66. [Card 卡片组件](#card-卡片组件) — `/components4.0/other/card.html`
67. [Collapse 折叠面板](#collapse-折叠面板) — `/components4.0/other/collapse.html`
68. [Divider 分割线](#divider-分割线) — `/components4.0/other/divider.html`
69. [Nestable 可拖拽树形结构](#nestable-可拖拽树形结构) — `/components4.0/other/nestable.html`
70. [Popover 弹出框](#popover-弹出框) — `/components4.0/other/popover.html`
71. [Tooltip 文字提示](#tooltip-文字提示) — `/components4.0/other/tooltip.html`
72. [9.0 发布修改记录](#90-发布修改记录) — `/changeLogs/v90.html`

---

## 1. 更新记录

> 原始路径：`/`  
> 相对路径：`Readme.md`  
> 页面 key：`v-2b813548`  
> JS Chunk：`47.0ad51e35.js`

## 更新记录

## 2. Button 按钮

> 原始路径：`/components3.0/basic/button.html`  
> 相对路径：`components3.0/basic/button.md`  
> 页面 key：`v-a4e8eb4e`  
> JS Chunk：`49.ad629636.js`

Button 按钮

普通按钮

不带图标

默认按钮

蓝色按钮

灰色按钮

按钮禁用

带图标

默认按钮

蓝色按钮

灰色按钮

禁用

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

tab1_body

"

>

不带图标

<

br

/>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

默认按钮

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_emphasize

"

>

蓝色按钮

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

灰色按钮

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_disable

"

>

按钮禁用

</

a

>

<

br

/>

<

br

/>

带图标

<

br

/>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_icon

"

>

<

em

class

=

"

xicon xicon-affix

"

>

</

em

>

默认按钮

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_icon common_button_emphasize

"

>

<

em

class

=

"

xicon xicon-affix

"

>

</

em

>

蓝色按钮

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_icon common_button_gray

"

>

<

em

class

=

"

xicon xicon-affix

"

>

</

em

>

灰色按钮

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_disable

"

>

<

em

class

=

"

xicon xicon-affix

"

>

</

em

>

禁用

</

a

>

<

br

/>

<

br

/>

</

div

>

</

div

>

</

div

>

扩展

确定

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<!-- 3px圆角 -->

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_emphasize radius3px

"

>

确定

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_emphasize_tint radius3px

"

>

确定

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray radius3px

"

>

确定

</

a

>

<

br

/>

<

br

/>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_primary_border radius3px

"

>

确定

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius3px

"

>

确定

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_black_bg radius3px

"

>

确定

</

a

>

<

br

/>

<

br

/>

<!-- 圆形：标准尺寸 -->

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50

"

>

<

i

class

=

"

xicon xicon-search

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 color_primary

"

>

<

i

class

=

"

xicon xicon-editor

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 color_success

"

>

<

i

class

=

"

xicon xicon-confirm

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 color_secondary_text

"

>

<

i

class

=

"

xicon xicon-pc

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 color_warning

"

>

<

i

class

=

"

xicon xicon-star

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 color_error

"

>

<

i

class

=

"

xicon xicon-delete

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

<

br

/>

<

br

/>

<!-- 圆形：小尺寸 -->

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 small

"

>

<

i

class

=

"

xicon xicon-search

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 small color_primary

"

>

<

i

class

=

"

xicon xicon-editor

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 small color_success

"

>

<

i

class

=

"

xicon xicon-confirm

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 small color_secondary_text

"

>

<

i

class

=

"

xicon xicon-pc

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 small color_warning

"

>

<

i

class

=

"

xicon xicon-star

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius50 small color_error

"

>

<

i

class

=

"

xicon xicon-delete

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

<

br

/>

<

br

/>

<!-- 方形：标准尺寸 xicon图标库-->

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon

"

>

<

i

class

=

"

xicon xicon-search

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon color_primary

"

>

<

i

class

=

"

xicon xicon-editor

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon color_success

"

>

<

i

class

=

"

xicon xicon-confirm

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon color_secondary_text

"

>

<

i

class

=

"

xicon xicon-pc

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon color_warning

"

>

<

i

class

=

"

xicon xicon-star

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon color_error

"

>

<

i

class

=

"

xicon xicon-delete

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

<

br

/>

<

br

/>

<!-- 方形：小尺寸 -->

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon small

"

>

<

i

class

=

"

xicon xicon-search

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon small color_primary

"

>

<

i

class

=

"

xicon xicon-editor

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon small color_success

"

>

<

i

class

=

"

xicon xicon-confirm

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon small color_secondary_text

"

>

<

i

class

=

"

xicon xicon-pc

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon small color_warning

"

>

<

i

class

=

"

xicon xicon-star

"

>

</

i

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button squareIcon small color_error

"

>

<

i

class

=

"

xicon xicon-delete

"

style

=

"

color

:

#ffffff

"

>

</

i

>

</

a

>

</

div

>

</

div

>

交互细则

1、一般情况下，按钮位置在整体录入区的下方，单独成行，居右显示

2、按钮为可用状态时，鼠标放到按钮上时，背景色发生改变；

3、按钮上要加TIPS功能，即对“按钮”的功能进行简易的说明：说明文字要简洁易懂

4、期望用户操作的按钮高亮展示

5、按钮不可用时为反显形式（置灰）

6、按钮文字应易懂，用词准确，摒弃没楞两可的字眼，要与同一界面上的其他按钮易于区分

7、同一功能或任务的元素集中放置，减少用户鼠标移动的距离，就近操作

8、按钮要支持键盘自动浏览按钮功能，即按Tab键的自动切换功能，支持Enter、ESC键盘操作

9、根据文字大小自适应，文字最多8个字，超出部分使用“…”表示，英文以当前按钮长度做截取，超出部分“…”

按钮位置

1、页面中包含“确定”“取消”按钮时，“确定”在左，“取消”在右显示，确定高亮

2、页面中包含“确定”“XX”“取消”按钮时，三个按钮的位置依次：确定、XX、取消

## 3. 表单专用-button

> 原始路径：`/components3.0/basic/capbutton.html`  
> 相对路径：`components3.0/basic/capbutton.md`  
> 页面 key：`v-1cf2e6da`  
> JS Chunk：`50.326c45a0.js`

表单专用-button

表单设置类按钮

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

plus_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

minus_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

multiply_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

divide_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

gt_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

lt_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

brackl_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

brackr_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

equal_16

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

gt_eq_16 w32

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

lt_eq_16 w32

"

>

</

span

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

<

span

class

=

"

brack_angle_16 w32

"

>

</

span

>

</

a

>

date

and

or

date

not

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

date

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

and

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

or

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

date

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn

"

>

not

</

a

>

extend

包含

不包含

重复表平均

重复表合计

日期差

日期时间差

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn w89

"

>

extend

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn w89

"

>

包含

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn w89

"

>

不包含

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn w89

"

>

重复表平均

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn w89

"

>

重复表合计

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn w89

"

>

日期差

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

form_btn w89

"

>

日期时间差

</

a

>

## 4. Toolbar 区域

> 原始路径：`/components3.0/basic/toolbar.html`  
> 相对路径：`components3.0/basic/toolbar.md`  
> 页面 key：`v-7debdab3`  
> JS Chunk：`51.23a2d328.js`

Toolbar 区域

基本使用

function getValue() {
var index = $("#select")[0].selectedIndex;
alert($("#select")[0][index].innerHTML);
}
$(function () {
var tt = $("#toolbar2").toolbar({
size: "L",
toolbar: [{
id: "transmit",
name: "转发",
className: "ico16", //设置图标 如果是设置字体图标的话 则不用className 而是采用img 细节查看【其他说明】tab页
click: function () {
alert("转发");
},
subMenu: [{
id: 'collaboration',
name: "协同",
click: function () {
alert("协同");
}
}, {
id: 'email',
name: "邮件",
click: function () {
alert("邮件");
}
}, {
id: 'event',
name: "事件",
click: function () {
alert("事件");
}
}]
}, {
id: "delete",
name: "删除",
className: "ico16 del_16",
selected: true
}, {
id: "refresh",
name: "刷新",
className: "ico16 refresh_16"
}, {
id: "select",
type: "select",
value: "-1",
text: "重要程度",
onchange: getValue,
items: [{
text: '普通',
value: '0'
}, {
text: '重要',
value: '1'
}, {
text: '非常重要',
value: '2'
}]
}, {
id: "workflow",
type: "checkbox",
text: "同一流程只显示最后一条",
value: "1",
checked: true,
click: function () {
alert("同一流程只显示最后一条")
}
}]
});
tt.hideBtn('event');
//动态添加按钮
tt.addMenu({
id: "delete2",
name: "删除2",
className: "ico16 del_16"
});
});

<

div

id

=

"

toolbar2

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

function

getValue

(

)

{

var

index

=

$

(

"#select"

)

[

0

]

.

selectedIndex

;

alert

(

$

(

"#select"

)

[

0

]

[

index

]

.

innerHTML

)

;

}

$

(

function

(

)

{

var

tt

=

$

(

"#toolbar2"

)

.

toolbar

(

{

size

:

"L"

,

toolbar

:

[

{

id

:

"transmit"

,

name

:

"转发"

,

className

:

"ico16"

,

//设置图标 如果是设置字体图标的话 则不用className 而是采用img 细节查看【其他说明】tab页

click

:

function

(

)

{

alert

(

"转发"

)

;

}

,

subMenu

:

[

{

id

:

'collaboration'

,

name

:

"协同"

,

click

:

function

(

)

{

alert

(

"协同"

)

;

}

,

{

id

:

'email'

,

name

:

"邮件"

,

click

:

function

(

)

{

alert

(

"邮件"

)

;

}

,

{

id

:

'event'

,

name

:

"事件"

,

click

:

function

(

)

{

alert

(

"事件"

)

;

}

]

}

,

{

id

:

"delete"

,

name

:

"删除"

,

className

:

"ico16 del_16"

,

selected

:

true

}

,

{

id

:

"refresh"

,

name

:

"刷新"

,

className

:

"ico16 refresh_16"

}

,

{

id

:

"select"

,

type

:

"select"

,

value

:

"-1"

,

text

:

"重要程度"

,

onchange

:

getValue

,

items

:

[

{

text

:

'普通'

,

value

:

'0'

}

,

{

text

:

'重要'

,

value

:

'1'

}

,

{

text

:

'非常重要'

,

value

:

'2'

}

]

}

,

{

id

:

"workflow"

,

type

:

"checkbox"

,

text

:

"同一流程只显示最后一条"

,

value

:

"1"

,

checked

:

true

,

click

:

function

(

)

{

alert

(

"同一流程只显示最后一条"

)

}

]

}

)

;

tt

.

hideBtn

(

'event'

)

;

//动态添加按钮

tt

.

addMenu

(

{

id

:

"delete2"

,

name

:

"删除2"

,

className

:

"ico16 del_16"

}

)

;

}

)

;

</

script

>

属性

类型

备注

描述

size

string

9.0 新增

toolbar高度，默认值是“M”，可选[“L”、“M”]

leftGap

number

9.0 新增

toolbar左侧间距

multiRow

bool

9.0 新增

默认为false,toolbar默认是单行形式，设置为true表示多行模式

isPager

bool

(9.0已经废弃)

默认为true，控制toolbar是否显示分页

searchHtml

搜索区域DOM

(9.0已经废弃)

默认为true，控制toolbar是否显示分页

toolbar中按钮参数 例

id

name

名称

click

点击事件

className

样式名称[按钮图标--从通用class中查询]

subMenu

下拉菜单

id

下拉子菜单id

name

下拉子菜单名称

click

下拉子菜单点击事件

toolbar中添加select

type

type默认值不写，还可以定义为select和checkbox

string

text

string

默认select的值

value

string

默认select的value

disable

boolean

设置select置灰

onchange

function

select的onchange方法

items

数组

select的option选项

className:"hidden"

设置class:hidden时隐藏select

方法

描述

selected()

设置某一个toolbar按钮高亮显示用 toolbar.selected(id)

unselected()

1、设置某一个toolbar按钮不高亮显示: toolbar.unselected(id)
2、unselected(),不添加参数，所有按钮取消高亮显示

disabled()

设置某一个toolbar按钮不可用 toolbar.disabled(id)

enabled()

设置某一个toolbar可用 toolbar.enabled(id)

disabledAll()

所有toolbar按钮不可用 toolbar.disabledAll()

enabledAll()

所有toolbar按钮可用 toolbar.enabledAll()

hideBtn(id)

toolbar隐藏按钮[参数为按钮id]: toolbar.hideBtn(id)

showBtn(id)

toolbar显示按钮[参数为按钮id] toolbar.showBtn()

更多参数

参数

类型

描述

showSeparate

boolean

设置toolbar是否显示分隔线，默认显示。

(6.0以后默认不显示)

## 5. EditorTable 可编辑table

> 原始路径：`/components3.0/data/editorTable.html`  
> 相对路径：`components3.0/data/editorTable.md`  
> 页面 key：`v-3a492072`  
> JS Chunk：`52.7e341889.js`

EditorTable 可编辑table

使用说明

第一步：需要在界面上引入相应的js文件和css文件。

![](https://open.seeyoncloud.com/v5devUIComp/${path}/common/js/ui/seeEditorTable/js/seeyon.ui.editorTable.min.js${ctp:resSuffix()})

<

link

rel

=

"

stylesheet

"

type

=

"

text/css

"

href

=

"

${path}/common/js/ui/seeEditorTable/css/seeEditorTable.css${ctp:resSuffix()}

"

/>

<

script

src

=

"

${path}/common/js/ui/seeEditorTable/js/seeyon.ui.editorTable.min.js${ctp:resSuffix()}

"

>

</

script

>

第二步： 在界面上定义一个div

<

div

id

=

"

formulaTable

"

>

</

div

>

第三步：渲染对象

var gridObj = $('#listSent').ajaxEditorGrid({
colModel: [
{
display: "标题",//标题
name: 'subject',
sortable : true,
validator:'NotEmpty',
defVal:'无标题',
width: 'big',
validatorMsg:'标题不能为空'
}, {
display: "发起时间",//发起时间
name: 'startDate',
sortable : true,
type:'date',
width: 'medium',
validatorMsg:'发送时间长度为10位'
},{
display: "当前处理人",//当前处理人
name: 'currentNodesInfo',
sortable : true,
validator:function(a){
return a.length<=10;
},
width: 'medium'
},{
display:"流程期限",//流程期限
name: 'processDeadLineName',
sortable : true,
type:'ed',
width: 'medium'
}, {
display:"跟踪状态",//跟踪状态
name: 'isTrack',
type:'ed',
sortable : true,
width: 'small'
}, {
display:"流程日志",// $.i18n("processLog.list.title.label")
name: 'processId',
type:'ed',
width: 'small'
}],
containerId:"mainPage",
height: 250,
autoload:false,
gridType:'autoGrid',
showTableToggleBtn: true,
managerName : "colManager",
managerMethod : "getSentList"
});

<

div

id

=

"

listSent

"

>

</

div

>

<

script

>

var

gridObj

=

$

(

'#listSent'

)

.

ajaxEditorGrid

(

{

colModel

:

[

{

display

:

"标题"

,

//标题

name

:

'subject'

,

sortable

:

true

,

validator

:

'NotEmpty'

,

defVal

:

'无标题'

,

width

:

'big'

,

validatorMsg

:

'标题不能为空'

}

,

{

display

:

"发起时间"

,

//发起时间

name

:

'startDate'

,

sortable

:

true

,

type

:

'date'

,

width

:

'medium'

,

validatorMsg

:

'发送时间长度为10位'

}

,

{

display

:

"当前处理人"

,

//当前处理人

name

:

'currentNodesInfo'

,

sortable

:

true

,

validator

:

function

(

a

)

{

return

a

.

length

<=

10

;

}

,

width

:

'medium'

}

,

{

display

:

"流程期限"

,

//流程期限

name

:

'processDeadLineName'

,

sortable

:

true

,

type

:

'ed'

,

width

:

'medium'

}

,

{

display

:

"跟踪状态"

,

//跟踪状态

name

:

'isTrack'

,

type

:

'ed'

,

sortable

:

true

,

width

:

'small'

}

,

{

display

:

"流程日志"

,

// $.i18n("processLog.list.title.label")

name

:

'processId'

,

type

:

'ed'

,

width

:

'small'

}

]

,

containerId

:

"mainPage"

,

height

:

250

,

autoload

:

false

,

gridType

:

'autoGrid'

,

showTableToggleBtn

:

true

,

managerName

:

"colManager"

,

managerMethod

:

"getSentList"

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

colModel

表格列定义

Array

自定义

----------

display

显示的列名称

string

自定义

----------

name

对应的后台字段名字

string

自定义

----------

type

编辑类型的定义

string

data10、ed、ro等

ed

----------

sortable

是否可以排序

boolean

true/false

true

----------

defVal

新增时候，默认值

string

自定义

----------

width

列宽

string/number

自定义/small/big/medium

----------

validator

校验函数,存在系统默认校验和用户自定义校验2种方式

string/function

自定义

----------

validatorMsg

校验提醒消息

string

自定义

height

表格的高度

Number

自定义

containerId

出现滚动条的容器id，如果是body出现滚动条则不需要设置

String

自定义

parentId

指定父元素ID，来适应其宽高

String

自定义

gridType

是否启动自动计算列宽

autoGrid/grid

autoGrid

managerName

后台Manager的名称（必须提供该参数）

String必须提供

自定义

managerMethod

后台对应Manager的方法名（必须提供该参数）

String必须提供

自定义

autoload

设置了managerName、managerMethod后，是否默认加载数据

string

自定义

idField

记录的关键字字段名称

String

自定义

id

onSuccess

成功后执行的函数

function

自定义

高度设置提醒：设置了parentId 可以不设置height，但如果parentId里面存在工具栏或者其他组件，

则建议设置height，可以写成
$("#center").height()-60的形式

gridObj=$("#formulaTable").ajaxEditorGrid({
....
idField:'id',
height: $("#center").height()-60,
....
});

<

div

class

=

"

layout_center over_hidden

"

layout

=

"

border:false

"

id

=

"

center

"

>

<

table

id

=

"

formulaTable

"

class

=

"

flexme3

"

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

>

</

table

>

</

div

>

gridObj=$("#formulaTable").ajaxEditorGrid({
....
idField:'id',
height: $("#center").height()-60,
....
});

编辑类型设置：目前只支持下面这些的编辑类型。

colModel中的type定义类型

type

编辑类型

补充说明

ch

CheckBox类型

ra

Radiobox类型

txt

textArea类型

date

日期10位类型【yyyy-MM-dd】

ed

普通input类型

price

金额类型

ro

只读类型

combo

下拉列类型

请参考列子

showDialog

请参考列子

date编辑类型

{
display: $.i18n("common.date.sendtime.label"),//发起时间
name: 'selSysCoding',
sortable : true,
type: 'date',
validator:function(a){
return a.length===10;
},

系统默认的日期格式是%Y-%m-%d
如果需要修改日期的显示格式可以通过监听onDateShow事件来实现

gridObj.attachEvent("onDateShow", function(dateCtl,rId,cInd,gridObj){
if(cInd===1){
gridObj.setDateFormat('%Y-%m-%d %H:%i');
}
return true;
})

{
display: $.i18n("common.date.sendtime.label"),//发起时间
name: 'selSysCoding',
sortable : true,
type: 'date',
validator:function(a){
return a.length===10;
},

系统默认的日期格式是%Y-%m-%d
如果需要修改日期的显示格式可以通过监听onDateShow事件来实现

gridObj.attachEvent("onDateShow", function(dateCtl,rId,cInd,gridObj){
if(cInd===1){
gridObj.setDateFormat('%Y-%m-%d %H:%i');
}
return true;
})

combo编辑类型

{display : "${ctp:i18n('common.datatype.label')}",name : 'dataType',width : 'small',sortable : true, type: 'combo'
,validator:'NotEmpty'
,validatorMsg:"${ctp:i18n('ctp.formulas.error.required')}"
,cellFun:function(comboObj){
comboObj.readonly(true);
comboObj.addOption([
{value: "1", text: "${ctp:i18n('common.text.label')}"},
{value: "2", text: "${ctp:i18n('ctp.formulas.dataType.numberic')}"},
{value: "3", text: "${ctp:i18n('common.date.time.label')}"},
{value: "4", text: "${ctp:i18n('ctp.formulas.dataType.bool')}"},
{value: "18", text: "${ctp:i18n('common.date.label')}"}
]);
}
}

{display : "${ctp:i18n('common.datatype.label')}",name : 'dataType',width : 'small',sortable : true, type: 'combo'
,validator:'NotEmpty'
,validatorMsg:"${ctp:i18n('ctp.formulas.error.required')}"
,cellFun:function(comboObj){
comboObj.readonly(true);
comboObj.addOption([
{value: "1", text: "${ctp:i18n('common.text.label')}"},
{value: "2", text: "${ctp:i18n('ctp.formulas.dataType.numberic')}"},
{value: "3", text: "${ctp:i18n('common.date.time.label')}"},
{value: "4", text: "${ctp:i18n('ctp.formulas.dataType.bool')}"},
{value: "18", text: "${ctp:i18n('common.date.label')}"}
]);
}
}

showDialog编辑类型

{
display: $.i18n("common.date.sendtime.label"),//发起时间
name: 'selUser',
sortable : true,
type: 'showDialog',
cellFun:function(editorObj,cellObj){
//这里可以定义选人弹框操作
createProcessXml(editorObj,cellObj
,"collaboration", getCtpTop(), window, $.ctx.CurrentUser.id, $.ctx.CurrentUser.name,
$.ctx.CurrentUser.loginAccountName, "collaboration", $.ctx.CurrentUser.loginAccount,
$.i18n('collaboration.newColl.collaboration'), null, null,
true, "", getNormalData("process_info")); //协同
});
}
},

//业务自行定义的方法
function createProcessXmlCallBack(editor,cellObj,tWindow, res, appName, returnValueWindow, currentUserId, currentUserName, currentUserAccountName,
defaultPolicyId, flowPermAccountId, defaultPolicyName){
if(res && res.obj && res.obj.length>0 && res.obj[0].length>0){
console.log(res.obj);
var nodeIds = [], personArray = res.obj[0];var nameLabels=[];
for (var i=0, len=personArray.length; i

";");
}

editor.grid.editStop();

}

其实就是用到下面2个核心方法：

//表示为单元格设置值
cellObj.value=nameLabels.join(";");
//停止编辑，即可完成单元格的输入
editor.grid.editStop();

{
display: $.i18n("common.date.sendtime.label"),//发起时间
name: 'selUser',
sortable : true,
type: 'showDialog',
cellFun:function(editorObj,cellObj){
//这里可以定义选人弹框操作
createProcessXml(editorObj,cellObj
,"collaboration", getCtpTop(), window, $.ctx.CurrentUser.id, $.ctx.CurrentUser.name,
$.ctx.CurrentUser.loginAccountName, "collaboration", $.ctx.CurrentUser.loginAccount,
$.i18n('collaboration.newColl.collaboration'), null, null,
true, "", getNormalData("process_info")); //协同
});
}
},

//业务自行定义的方法
function createProcessXmlCallBack(editor,cellObj,tWindow, res, appName, returnValueWindow, currentUserId, currentUserName, currentUserAccountName,
defaultPolicyId, flowPermAccountId, defaultPolicyName){
if(res && res.obj && res.obj.length>0 && res.obj[0].length>0){
console.log(res.obj);
var nodeIds = [], personArray = res.obj[0];var nameLabels=[];
for (var i=0, len=personArray.length; i<len; i++) {
var person = personArray[i];
nameLabels.push(person.name);
}
cellObj.value=nameLabels.join(";");
}

editor.grid.editStop();

}

其实就是用到下面2个核心方法：

//表示为单元格设置值
cellObj.value=nameLabels.join(";");
//停止编辑，即可完成单元格的输入
editor.grid.editStop();

校验设置：目前系统支持4中类型的校验，系统内置校验3种，还有就是用户自定义校验。

colModel中的validator定义

validator

类型

补充说明

notEmpty

校验是否为空

email

校验邮箱

number

校验数字类型

fun

自己定义校验函数

请参考列子

自己定义校验函数

{
display : "${ctp:i18n('ctp.formulas.description')}",
name : 'description',
width : 'medium',
sortable : false,
//自己定义校验函数
validator:function(a){
return a.length<=255;
},
//自己定义校验消息
validatorMsg:"${ctp:i18n_1('ctp.formulas.error.maxLength',255)}"
},

{
display : "${ctp:i18n('ctp.formulas.description')}",
name : 'description',
width : 'medium',
sortable : false,
//自己定义校验函数
validator:function(a){
return a.length<=255;
},
//自己定义校验消息
validatorMsg:"${ctp:i18n_1('ctp.formulas.error.maxLength',255)}"
},

方法列表

方法名

说明

参数 1

参数 2

例子

ajaxgridLoad

请求后台数据

params[请求参数]

o.type = 'Account';

gridObj.ajaxgridLoad(o);

setCellDisabled

设置某个单元格不可以编辑

id[行id]

cInd[列序号]

gridObj.setCellDisabled(id,0);

setRowNotEditor

设置某行不可以编辑

gridObj.setRowNotEditor(rowData.id);

addNewRow

新增一行数据

Array[行数据]

gridObj.addNewRow(seeyonCom.uid(),gridObj.getDefCellValues());

validate

手动触发列数据校验

eventName[方法名]

if(!gridObj.validate()){

return ;

}

getChangeSubmitData

获取发生过变更的数据

var content=gridObj.getChangeSubmitData();

getAllData

获取当前编辑表格所有单元格数据

var content=gridObj.getAllData();

setColumnHidden

根据列序号对列进行隐藏显示

表示第一列进行隐藏 var content=gridObj.setColumnHidden(0,true);

cells

根据行id和列序号获取单元格对象

var cellObj=gridObj.cells(rowId,1);获取第一单元格值

cellObj.setValue("ddd")为第一个单元格设置值

cellObj.getValue() 从第一个单元格获取值

event事件列表

eventName

方法作用

参数 1

参数2

例子

onCellChanged

单元格发生变化

rId [行id]

cInd[列序号]

nValue[变化后的单元格值]

gridObj.attachEvent("onCellChanged", function(rId,cInd,nValue){....})

onDateShow

弹出日期控件

dateCtl [日期对象]

rId[行id]

cInd[列序号]

gridObj.attachEvent("onDateShow", function(dateCtl,rId,cInd,gridObj){.....})

## 6. Grid 列表

> 原始路径：`/components3.0/data/grid.html`  
> 相对路径：`components3.0/data/grid.md`  
> 页面 key：`v-b5b2e15a`  
> JS Chunk：`24.17c55d5f.js`

Grid 列表

代码示例

// 列表简单初始化
var t = $("#mytable").ajaxgrid({
click : function(data,rowIndex, colIndex){},//单击事件
dblclick : function(data,rowIndex, colIndex){},//双击事件
render : rend,//function rend(txt,rowData, rowIndex, colIndex,colObj)
//自定义渲染器，
//可以对单元格显示数据和样式进行加工展现，据对象，
//txt为表身渲染单元格文本，rowData为渲染当前行数,rowIndex为当前行，colIndex为当前列,
//colObj为表头对象的width，name，display，align以及sortType等等
colModel : [ {
display : 'id',
name : 'orgid',
width : '40',
sortable : false,
align : 'center',
type : 'checkbox'
},
{
display : '组织名称',
name : 'orgname',
width : '180',
sortable : true,
align : 'left'
},
{
display : '组织名称2',
name : 'orgname2',
width : '180',
sortable : true,
align : 'left'
},
{
display : '父组织ID',
name : 'parentid',
width : '180',
sortable : true,
align : 'left',
codecfg : "codeId:'test_code'"//定义框架自动枚举转换规则，具体请参考“枚举组件”部分说明
} ],
width : 800,
height : 200,
managerName : "testPagingManager",
managerMethod : "testPaging"
});
function rend(txt,rowData, rowIndex, colIndex,colObj) {
if (c == 0)
return '<input type="checkbox" value="'+txt+'">';
else
return txt;
}

<

table

id

=

"

mytable

"

widht

=

"

100%

"

>

</

table

>

<

script

type

=

"

text/javascript

"

>

// 列表简单初始化

var

t

=

$

(

"#mytable"

)

.

ajaxgrid

(

{

click

:

function

(

data

,

rowIndex

,

colIndex

)

{

}

,

//单击事件

dblclick

:

function

(

data

,

rowIndex

,

colIndex

)

{

}

,

//双击事件

render

:

rend

,

//function rend(txt,rowData, rowIndex, colIndex,colObj)

//自定义渲染器，

//可以对单元格显示数据和样式进行加工展现，据对象，

//txt为表身渲染单元格文本，rowData为渲染当前行数,rowIndex为当前行，colIndex为当前列,

//colObj为表头对象的width，name，display，align以及sortType等等

colModel

:

[

{

display

:

'id'

,

name

:

'orgid'

,

width

:

'40'

,

sortable

:

false

,

align

:

'center'

,

type

:

'checkbox'

}

,

{

display

:

'组织名称'

,

name

:

'orgname'

,

width

:

'180'

,

sortable

:

true

,

align

:

'left'

}

,

{

display

:

'组织名称2'

,

name

:

'orgname2'

,

width

:

'180'

,

sortable

:

true

,

align

:

'left'

}

,

{

display

:

'父组织ID'

,

name

:

'parentid'

,

width

:

'180'

,

sortable

:

true

,

align

:

'left'

,

codecfg

:

"codeId:'test_code'"

//定义框架自动枚举转换规则，具体请参考“枚举组件”部分说明

}

]

,

width

:

800

,

height

:

200

,

managerName

:

"testPagingManager"

,

managerMethod

:

"testPaging"

}

)

;

function

rend

(

txt

,

rowData

,

rowIndex

,

colIndex

,

colObj

)

{

if

(

c

==

0

)

return

'<input type="checkbox" value="'

+

txt

+

'">'

;

else

return

txt

;

}

</

script

>

【grid 使用数据库进行排序】

// 设置dbOrderBy为true即可，点击升序、降序的时候会在原有参数的基础上传递 sortField: p.sortname,sortOrder: p.sortorder 到后台
var t2 = $("#mytable2").ajaxgrid({
click : function(){},//单击事件
dblclick : function(){},//双击事件
showToggleBtn:true,
render : rend,//function rend(txt,rowData, rowIndex, colIndex,colObj)
//自定义渲染器，
//可以对单元格显示数据和样式进行加工展现，据对象，
//txt为表身渲染单元格文本，rowData为渲染当前行数,rowIndex为当前行，colIndex为当前列,
//colObj为表头对象的width，name，display，align以及sortType等等
colModel : [ {
display : 'id',
name : 'orgid',
width : '40',
sortable : false,
align : 'center',
type : 'checkbox'
},
{
display : '组织名称',
name : 'orgname',
width : '180',
sortable : true,
align : 'left'
},
{
display : '组织名称2',
name : 'orgname2',
width : '180',
sortable : true,
align : 'left'
},
{
display : '父组织ID',
name : 'parentid',
width : '180',
sortable : true,
align : 'left',
codecfg : "codeId:'test_code'"//定义框架自动枚举转换规则，具体请参考“枚举组件”部分说明
} ],
width : 800,
dbOrderBy:true,
height : 200,
managerName : "testPagingManager",
managerMethod : "testPaging"
});

<

table

id

=

"

mytable2

"

>

</

table

>

<

script

type

=

"

text/javascript

"

>

// 设置dbOrderBy为true即可，点击升序、降序的时候会在原有参数的基础上传递 sortField: p.sortname,sortOrder: p.sortorder 到后台

var

t2

=

$

(

"#mytable2"

)

.

ajaxgrid

(

{

click

:

function

(

)

{

}

,

//单击事件

dblclick

:

function

(

)

{

}

,

//双击事件

showToggleBtn

:

true

,

render

:

rend

,

//function rend(txt,rowData, rowIndex, colIndex,colObj)

//自定义渲染器，

//可以对单元格显示数据和样式进行加工展现，据对象，

//txt为表身渲染单元格文本，rowData为渲染当前行数,rowIndex为当前行，colIndex为当前列,

//colObj为表头对象的width，name，display，align以及sortType等等

colModel

:

[

{

display

:

'id'

,

name

:

'orgid'

,

width

:

'40'

,

sortable

:

false

,

align

:

'center'

,

type

:

'checkbox'

}

,

{

display

:

'组织名称'

,

name

:

'orgname'

,

width

:

'180'

,

sortable

:

true

,

align

:

'left'

}

,

{

display

:

'组织名称2'

,

name

:

'orgname2'

,

width

:

'180'

,

sortable

:

true

,

align

:

'left'

}

,

{

display

:

'父组织ID'

,

name

:

'parentid'

,

width

:

'180'

,

sortable

:

true

,

align

:

'left'

,

codecfg

:

"codeId:'test_code'"

//定义框架自动枚举转换规则，具体请参考“枚举组件”部分说明

}

]

,

width

:

800

,

dbOrderBy

:

true

,

height

:

200

,

managerName

:

"testPagingManager"

,

managerMethod

:

"testPaging"

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

colModel

表格列定义

Array

自定义

----------

display

显示的列名称

string

自定义

----------

name

对应的后台字段名字

string

自定义

----------

sortType

排序类型

string

data、number、string

默认按照文本排序

----------

sortable

是否可以排序

boolean

true/false

true

----------

width

列宽

string/number

自定义（100或者15%）/small/big/medium

----------

align

内容显示的位置

string

left/center/right

left

----------

type

显示类型

string

checkbox、radio、空

空

height

高度[px]，默认200px

Number

自定义

dbOrderBy

设置是否需要数据库排序 （8.0新增功能）

boolean

true/false

false

click

单击事件返回值

:row(行json对象),

colIndex(所在列index值),

rowIndex(所在行index值)

Function(data,rowIndex, colIndex)

dbclick

双击事件返回值

:row(行json对象),

colIndex(所在列index值),

rowIndex(所在行index值)

Function(data,rowIndex, colIndex)

parentId

指定父元素ID，来适应其宽高

String

自定义

width

宽度值[px],默认auto表示根据每列的宽度自动计算

number

自定义

resizable

是否可伸缩

boolean

true/false

false

usepager

是否分页[false]

boolean

true/false

false

rpMaxSize

每页显示条数最大值[200]

number

自定义

onChangeSort

当改变排序时执行的函数，

当该属性设置时，组件不再使用自己的查询机制。

boolean

true/false

false

onCurrentPageSort

是否只对当前页的数据进行排序，

当设置为true时，只对当前页的数据进行排序。

boolean

true/false

false

onSuccess

成功后执行的函数

Function

slideToggleBtn

上下伸缩按钮是否显示

boolean

true/false

false

slideToggleUpHandle

自定义列表上箭头事件

Function

slideToggleDownHandle

自定义列表下箭头事件

Function

resizeGridUpDown

动态设置分割条位置 grid.grid.resizeGridUpDown('up')

String

up/middle/down

up

customId

个性化存储id ，默认值为$.ctx._currentPathId,

自定义的化在默认值后添加后缀

,例如customId : $.ctx.

currentPathId

+"${xxx.ff}";

string

自定义

showToggleBtn

显示/隐藏表头下拉箭头

boolean

true/false

true

noTotal

不显示：总条数、当前在第几页、

最后一条按钮（7.1新增功能）

boolean

true/false

false

customize

是否启用个性化存储

boolean

true/false

true

方法列表

方法名

说明

参数 1

参数 2

例子

ajaxgridLoad

请求后台数据

params[请求参数]

o.type = 'Account';

$("#gridObj").ajaxgridLoad(o);

callBackTotle

设置totle条数回调函数 类似:render

gridObj.p.callBackTotle=function(total){}

grid

获取grid对象

gridObj.grid;

destroyGrid

通过gridObj.destroyGrid来销毁当前表格对象，

用户界面上表格销毁，重新渲染

gridObj.grid.destroyGrid();

getSelectRows

获取选中行数组，例如[{"id": 10001, ... },{"id": 10001, ... }]

gridObj.grid.getSelectRows();

p

获取grid所有参数

gridObj.p

## 7. OverPage 翻页

> 原始路径：`/components3.0/data/overPage.html`  
> 相对路径：`components3.0/data/overPage.md`  
> 页面 key：`v-d30b8f1a`  
> JS Chunk：`53.b0d06012.js`

OverPage 翻页

当数据太多(或者数据项列表太长)一页显示不下时，将数据项列表拆分进一系列的页中。提供“上一页”和“下一页”的链接让用户可以访问被分页的数据，同时提供“第一页”和“最后一页”的链接。

基本使用

每页显示

条/共6条

第

页

go

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

div

class

=

"

common_over_page

"

>

每页显示

<

input

type

=

"

text

"

class

=

"

common_over_page_txtbox

"

>

<

span

class

=

"

margin_r_20

"

>

条/共6条

</

span

>

<

a

href

=

"

javascript:;

"

class

=

"

common_over_page_btn pFirst

"

title

=

"

首页

"

>

<

em

class

=

"

pageFirst

"

>

</

em

>

</

a

>

<

a

href

=

"

javascript:;

"

class

=

"

common_over_page_btn pPrev

"

title

=

"

上一页

"

>

<

em

class

=

"

pagePrev

"

>

</

em

>

</

a

>

<

span

class

=

"

margin_l_10

"

>

第

</

span

>

<

input

type

=

"

text

"

class

=

"

common_over_page_txtbox

"

>

页

<

a

href

=

"

javascript:;

"

class

=

"

common_over_page_btn pNext

"

title

=

"

下一页

"

>

<

em

class

=

"

pageNext

"

>

</

em

>

</

a

>

<

a

href

=

"

javascript:;

"

class

=

"

common_over_page_btn pLast

"

title

=

"

尾页

"

>

<

em

class

=

"

pageLast

"

>

</

em

>

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

grid_go

"

class

=

"

common_button common_over_page_go margin_lr_10

"

>

go

</

a

>

</

div

>

</

div

>

</

div

>

简要说明

当数据太多(或者数据项列表太长)一页显示不下时，将数据项列表拆分进一系列的页中。提供“上一页”和“下一页”的链接让用户可以访问被分页的数据，
同时提供“第一页”和“最后一页”的链接。

交互细则

1、翻页控件在列表右下方，与列表控件居右对齐

2、允许用户自定义设置每页显示行数

3、允许用户切换页码

4、支持键盘Enter键做页码切换确认

## 8. Scheduler 日程视图

> 原始路径：`/components3.0/data/scheduler.html`  
> 相对路径：`components3.0/data/scheduler.md`  
> 页面 key：`v-8feb4eda`  
> JS Chunk：`54.67195ed4.js`

Scheduler 日程视图

新建会议

新建计划

新建任务

新建事件

■

会议

■

计划

■

任务

■

事件

■

到期协同

■

到期公文

全天/跨日:

init()
function init() {
scheduler.config.multi_day = true;//日视图、周视图允许显示全天、跨天日程
scheduler.config.xml_date = "%Y-%m-%d %H:%i";//数据时间格式
scheduler.config.dblclick_create = false;//禁止双击创建
scheduler.config.drag_create = false;//禁止拖拽创建
scheduler.config.drag_resize = false;//日视图、周视图禁拖拽改变时间
scheduler.config.drag_move = false;//月视图禁止拖拽改变时间
scheduler.config.hour_size_px = 84;//时间高度
scheduler.config.scroll_hour = "03.00";//定位初始时间
scheduler.config.clickMenu = [{
name: "新建会xxxxxxxxxxx议",
isShow:false,
handle: function () {
//debugger;
alert(scheduler.config.currentDateTime);
}
}, {
isShow:true,
name: "新建计划",
handle: function () {
alert(scheduler.config.currentDateTime);
}
}];//单击是否有菜单on
//scheduler.config.tabClick = test;
//scheduler.config.prevClick = test;
//scheduler.config.nextClick = test;



scheduler.xy.bar_height = 30;//全天、跨天日程之前的间隔
scheduler.maxLength = 8;//全天、跨天日程最多显示的条数
scheduler.xy.nav_height = 40;//导航高度


scheduler.attachEvent("onClick", function (id) {
var event = this.getEvent(id);
var eventType = event.type;

alert(eventType)
});
scheduler.attachEvent("onDblClick", function () {
return false;
});

//portal使用参数
// scheduler.isPortal = true;//是否在portal显示
scheduler.config.goToPage = goToPage;
// scheduler.isPortal_scheduler = true;//如果是日程事件，则不显示日期切换
scheduler.dayEvent = [];//单日事件

scheduler.getId = function (id) { //单击事件，参数为事件id
var event = this.getEvent(id);
var eventType = event.type;

alert(eventType)
}
function goToPage(date) {
alert(date)
// window.open("http://www.baidu.com");
}
//portal使用参数 end

scheduler.config.xml_date = "%Y-%m-%d %H:%i";

scheduler.init('scheduler_here', new Date(), "week");//初始化显示当天日期+周视图
//初始化数据,数据格式为json
scheduler.parse([{
id: '6896764909577916408',
type: 'collaboration',
start_date: '2012-12-24 10:30',
end_date: '2012-12-26 11:00',
text: '协同1',
ico: "work_time_set_16",
content: "<span class='ico16'></span>+sfsdfsdsfsdswewew"
}, {
id: '6896764909577916418',
type: 'collaboration',
start_date: '2012-12-24 10:30',
end_date: '2012-12-24 11:00',
text: '任务2'
}, {
"id": "2825558033677960100",
"type": "plan",
"content": "dddddddddddddddddd<span class=\"ico16 xls_16\"></span>",
"subject": "dddddddddddddddddd",
"endDate": "2012-12-30 23:59",
"title": "计划",
start_date: '2012-12-24 10:30',
end_date: '2012-12-24 11:00'
}, {
id: '6896764909577916448',
type: 'task',
start_date: '2012-12-13 00:00',
end_date: '2012-12-14 23:59',
text: '任务3'
}
, {
id: '6896764909577916428',
type: 'task',
start_date: '2012-11-13 00:00',
end_date: '2012-11-21 23:59',
text: '任务3'
}, {
id: '6896764909577916438',
type: 'plan',
start_date: '2012-12-14 00:00',
end_date: '2012-12-14 23:59',
text: '计划4'
, set_disable: true
}, {
id: '2078061340905455728',
type: 'event',
start_date: '2012-11-13 00:00',
end_date: '2012-11-22 23:59',
text: '事件5'
}, {
id: '2078061340905455738',
type: 'event',
start_date: '2012-11-13 00:00',
end_date: '2012-11-22 23:59',
text: '事件6'
}, {
id: '2078061340905455748',
type: 'event',
start_date: '2012-11-13 00:00',
end_date: '2012-11-22 23:59',
text: '事件7'
}, {
id: '2078061340905455758',
type: 'task',
start_date: '2012-11-13 00:00',
end_date: '2012-11-22 23:59',
text: '任务8',
ico: "milestone right"
}, {
id: '2078061340905455768',
type: 'event',
start_date: '2012-11-13 00:00',
end_date: '2012-11-22 23:59',
text: '事件9'
}, {
id: '2078061340905455778',
type: 'event',
start_date: '2012-11-13 00:00',
end_date: '2012-11-22 23:59',
text: '事件10'
}, {
id: '-5722754109640979663',
type: 'doc',
eventId: '-8165958465554986075',
eventCreateUserId: '684019058616189893',
eventReceiveMemberId: '',
eventPeriodicalId: 'null',
eventBeginDate: '2012-11-22',
start_date: '2012-12-25 11:00',
end_date: '2012-12-25 11:00',
text: '公文11',
ico: 'work_time_set_16'
}, {
id: '-7346394655019678232',
type: 'meeting',
eventId: '6836291771407417598',
eventCreateUserId: '684019058616189893',
eventReceiveMemberId: '',
eventPeriodicalId: 'null',
eventBeginDate: '2012-11-22',
start_date: '2012-11-22 11:00',
end_date: '2012-11-22 11:30',
text: '会议12'
}, {
id: '-4031401379237048532',
type: 'plan',
eventId: '3259770405833755198',
eventCreateUserId: '684019058616189893',
eventReceiveMemberId: '',
eventPeriodicalId: 'null',
eventBeginDate: '2012-11-23',
start_date: '2012-11-23 11:30',
end_date: '2012-11-23 12:00',
text: '计划13'
}, {
id: '-4031401379237048542',
type: 'task',
eventId: '3259770405833755198',
eventCreateUserId: '684019058616189893',
eventReceiveMemberId: '',
eventPeriodicalId: 'null',
eventBeginDate: '2012-11-23',
start_date: '2012-12-23 11:30',
end_date: '2012-12-23 12:00',
text: '任务14',
ico: 'milestone right',
set_disable: true
}, {
id: '-4031401379237048552',
type: 'task',
eventId: '3259770405833755198',
eventCreateUserId: '684019058616189893',
eventReceiveMemberId: '',
eventPeriodicalId: 'null',

start_date: '2011-12-19 11:30',
end_date: '2012-12-23 11:00',
text: '任务15',
ico: 'milestone right'
}], "json");

$("#itemize").bind({
mouseover: function () {
$("#itemize_content").removeClass("hidden");
},
mouseout: function () {
$("#itemize_content").addClass("hidden");
}
})
}
function test(type, nextDate){
alert(nextDate)
}
$(function() {
$("#dhx_cal_common_tabs li div").click(function () {
$("#dhx_cal_common_tabs li").removeClass("current");
$(this).parents("li").addClass("current");
});
$('#meeting11111').hide()
})

<

div

id

=

"

scheduler_here

"

class

=

"

dhx_cal_container

"

style

=

'

width

:

100%

;

height

:

100%

;

'

>

<

div

class

=

"

dhx_cal_navline

"

>

<

div

id

=

"

top_left

"

>

<

a

id

=

"

newMeeting

"

class

=

"

common_button

"

href

=

"

javascript:void(0)

"

>

新建会议

</

a

>

<

a

id

=

"

newPlan

"

class

=

"

common_button

"

href

=

"

javascript:void(0)

"

>

新建计划

</

a

>

<

a

id

=

"

newTask

"

class

=

"

common_button

"

href

=

"

javascript:void(0)

"

>

新建任务

</

a

>

<

a

id

=

"

newEvent

"

class

=

"

common_button

"

href

=

"

javascript:void(0)

"

>

新建事件

</

a

>

</

div

>

<!--
<div class="dhx_cal_today_button" id="dhx_cal_today_button">
</div>
-->

<

div

class

=

"

dhx_cal_date

"

id

=

"

dhx_cal_date

"

style

=

"

position

:

absolute

;

z-index

:

2

;

top

:

0

;

left

:

400px

;

margin-top

:

15px

;

"

>

<

div

class

=

"

dhx_cal_prev_button

"

id

=

"

dhx_cal_prev_button

"

>

&nbsp;

</

div

>

<

div

class

=

"

dhx_cal_date

"

id

=

"

dhx_cal_date

"

style

=

"

>

</

div

>

<

div

class

=

"

dhx_cal_next_button

"

id

=

"

dhx_cal_next_button

"

>

&nbsp;

</

div

>

</

div

>

<

span

id

=

"

top_right

"

>

<!--<div class="dhx_cal_tab" name="day_tab" id="day_tab" style="right:204px;"></div>
<div class="dhx_cal_tab" name="week_tab" id="week_tab" style="right:140px;"></div>
<div class="dhx_cal_tab" name="month_tab" id="month_tab" style="right:76px;"></div>-->

<

div

id

=

"

dhx_cal_common_tabs

"

class

=

"

common_tabs clearfix

"

style

=

"

position

:

absolute

;

top

:

12px

;

right

:

75px

;

"

>

<

ul

class

=

"

left

"

>

<

li

class

=

"

left

"

>

<

a

hidefocus

=

"

true

"

href

=

"

javascript:void(0)

"

class

=

"

border_b left

"

style

=

"

padding

:

0

;

"

>

<

div

class

=

"

dhx_cal_tab

"

name

=

"

day_tab

"

id

=

"

day_tab

"

style

=

"

text-align

:

center

;

position

:

initial

;

top

:

initial

;

white-space

:

initial

;

padding

:

0 10px

;

position

:

static

;

"

>

</

div

>

</

a

>

</

li

>

<

li

class

=

"

left current

"

>

<

a

hidefocus

=

"

true

"

href

=

"

javascript:void(0)

"

class

=

"

border_b

"

style

=

"

padding

:

0

;

"

>

<

div

class

=

"

dhx_cal_tab

"

name

=

"

week_tab

"

id

=

"

week_tab

"

style

=

"

text-align

:

center

;

position

:

initial

;

top

:

initial

;

white-space

:

initial

;

padding

:

0 10px

;

position

:

static

;

"

>

</

div

>

</

a

>

</

li

>

<

li

class

=

"

left

"

>

<

a

hidefocus

=

"

true

"

href

=

"

javascript:void(0)

"

class

=

"

border_b last_tab

"

style

=

"

padding

:

0

;

"

>

<

div

class

=

"

dhx_cal_tab

"

name

=

"

month_tab

"

id

=

"

month_tab

"

style

=

"

text-align

:

center

;

position

:

initial

;

top

:

initial

;

white-space

:

initial

;

padding

:

0 10px

;

position

:

static

;

"

>

</

div

>

</

a

>

</

li

>

</

ul

>

</

div

>

<

div

href

=

"

class

=

"

common_drop_list dhx_cal_type

"

name

=

"

more_tab

"

id

=

"

more_tab

"

>

<

span

class

=

"

ico16 arrow_1_b

"

id

=

"

itemize

"

>

</

span

>

<

div

class

=

"

common_drop_list_content common_drop_list_content_action hidden dhx_cal_content

"

id

=

"

itemize_content

"

>

<

a

href

=

"

javascript:void(0)

"

value

=

"

0

"

>

<

span

class

=

"

dhx_cal_type_color cal_meeting

"

>

■

</

span

>

会议

</

a

>

<

a

href

=

"

javascript:void(0)

"

value

=

"

1

"

>

<

span

class

=

"

dhx_cal_type_color cal_plan

"

>

■

</

span

>

计划

</

a

>

<

a

href

=

"

javascript:void(0)

"

value

=

"

2

"

>

<

span

class

=

"

dhx_cal_type_color cal_task

"

>

■

</

span

>

任务

</

a

>

<

a

href

=

"

javascript:void(0)

"

value

=

"

3

"

>

<

span

class

=

"

dhx_cal_type_color cal_event

"

>

■

</

span

>

事件

</

a

>

<

a

href

=

"

javascript:void(0)

"

value

=

"

2

"

>

<

span

class

=

"

dhx_cal_type_color cal_col

"

>

■

</

span

>

到期协同

</

a

>

<

a

href

=

"

javascript:void(0)

"

value

=

"

3

"

>

<

span

class

=

"

dhx_cal_type_color cal_doc

"

>

■

</

span

>

到期公文

</

a

>

</

div

>

</

div

>

</

span

>

</

div

>

<

div

class

=

"

dhx_cal_header

"

>

</

div

>

<

div

class

=

"

dhx_cal_data

"

>

</

div

>

</

div

>

<

div

id

=

"

showEvent

"

class

=

"

border_all hidden h100b

"

>

<

p

class

=

"

hidden padding_5 font_bold

"

id

=

"

all_DayTitle

"

>

全天/跨日:

</

p

>

<

ul

id

=

"

allday_event

"

class

=

"

padding_5

"

>

</

ul

>

<

ul

class

=

"

border_t_dashed margin_t_5 padding_5

"

id

=

"

oneday_event

"

>

</

ul

>

</

div

>

<

script

>

init

(

)

function

init

(

)

{

scheduler

.

config

.

multi_day

=

true

;

//日视图、周视图允许显示全天、跨天日程

scheduler

.

config

.

xml_date

=

"%Y-%m-%d %H:%i"

;

//数据时间格式

scheduler

.

config

.

dblclick_create

=

false

;

//禁止双击创建

scheduler

.

config

.

drag_create

=

false

;

//禁止拖拽创建

scheduler

.

config

.

drag_resize

=

false

;

//日视图、周视图禁拖拽改变时间

scheduler

.

config

.

drag_move

=

false

;

//月视图禁止拖拽改变时间

scheduler

.

config

.

hour_size_px

=

84

;

//时间高度

scheduler

.

config

.

scroll_hour

=

"03.00"

;

//定位初始时间

scheduler

.

config

.

clickMenu

=

[

{

name

:

"新建会xxxxxxxxxxx议"

,

isShow

:

false

,

handle

:

function

(

)

{

//debugger;

alert

(

scheduler

.

config

.

currentDateTime

)

;

}

,

{

isShow

:

true

,

name

:

"新建计划"

,

handle

:

function

(

)

{

alert

(

scheduler

.

config

.

currentDateTime

)

;

}

]

;

//单击是否有菜单on

//scheduler.config.tabClick = test;

//scheduler.config.prevClick = test;

//scheduler.config.nextClick = test;

scheduler

.

xy

.

bar_height

=

30

;

//全天、跨天日程之前的间隔

scheduler

.

maxLength

=

8

;

//全天、跨天日程最多显示的条数

scheduler

.

xy

.

nav_height

=

40

;

//导航高度

scheduler

.

attachEvent

(

"onClick"

,

function

(

id

)

{

var

event

=

this

.

getEvent

(

id

)

;

var

eventType

=

event

.

type

;

alert

(

eventType

)

}

)

;

scheduler

.

attachEvent

(

"onDblClick"

,

function

(

)

{

return

false

;

}

)

;

//portal使用参数

// scheduler.isPortal = true;//是否在portal显示

scheduler

.

config

.

goToPage

=

goToPage

;

// scheduler.isPortal_scheduler = true;//如果是日程事件，则不显示日期切换

scheduler

.

dayEvent

=

[

]

;

//单日事件

scheduler

.

getId

=

function

(

id

)

{

//单击事件，参数为事件id

var

event

=

this

.

getEvent

(

id

)

;

var

eventType

=

event

.

type

;

alert

(

eventType

)

}

function

goToPage

(

date

)

{

alert

(

date

)

// window.open("http://www.baidu.com");

}

//portal使用参数 end

scheduler

.

config

.

xml_date

=

"%Y-%m-%d %H:%i"

;

scheduler

.

init

(

'scheduler_here'

,

new

Date

(

)

,

"week"

)

;

//初始化显示当天日期+周视图

//初始化数据,数据格式为json

scheduler

.

parse

(

[

{

id

:

'6896764909577916408'

,

type

:

'collaboration'

,

start_date

:

'2012-12-24 10:30'

,

end_date

:

'2012-12-26 11:00'

,

text

:

'协同1'

,

ico

:

"work_time_set_16"

,

content

:

"<span class='ico16'></span>+sfsdfsdsfsdswewew"

}

,

{

id

:

'6896764909577916418'

,

type

:

'collaboration'

,

start_date

:

'2012-12-24 10:30'

,

end_date

:

'2012-12-24 11:00'

,

text

:

'任务2'

}

,

{

"id"

:

"2825558033677960100"

,

"type"

:

"plan"

,

"content"

:

"dddddddddddddddddd<span class=\"ico16 xls_16\"></span>"

,

"subject"

:

"dddddddddddddddddd"

,

"endDate"

:

"2012-12-30 23:59"

,

"title"

:

"计划"

,

start_date

:

'2012-12-24 10:30'

,

end_date

:

'2012-12-24 11:00'

}

,

{

id

:

'6896764909577916448'

,

type

:

'task'

,

start_date

:

'2012-12-13 00:00'

,

end_date

:

'2012-12-14 23:59'

,

text

:

'任务3'

}

,

{

id

:

'6896764909577916428'

,

type

:

'task'

,

start_date

:

'2012-11-13 00:00'

,

end_date

:

'2012-11-21 23:59'

,

text

:

'任务3'

}

,

{

id

:

'6896764909577916438'

,

type

:

'plan'

,

start_date

:

'2012-12-14 00:00'

,

end_date

:

'2012-12-14 23:59'

,

text

:

'计划4'

,

set_disable

:

true

}

,

{

id

:

'2078061340905455728'

,

type

:

'event'

,

start_date

:

'2012-11-13 00:00'

,

end_date

:

'2012-11-22 23:59'

,

text

:

'事件5'

}

,

{

id

:

'2078061340905455738'

,

type

:

'event'

,

start_date

:

'2012-11-13 00:00'

,

end_date

:

'2012-11-22 23:59'

,

text

:

'事件6'

}

,

{

id

:

'2078061340905455748'

,

type

:

'event'

,

start_date

:

'2012-11-13 00:00'

,

end_date

:

'2012-11-22 23:59'

,

text

:

'事件7'

}

,

{

id

:

'2078061340905455758'

,

type

:

'task'

,

start_date

:

'2012-11-13 00:00'

,

end_date

:

'2012-11-22 23:59'

,

text

:

'任务8'

,

ico

:

"milestone right"

}

,

{

id

:

'2078061340905455768'

,

type

:

'event'

,

start_date

:

'2012-11-13 00:00'

,

end_date

:

'2012-11-22 23:59'

,

text

:

'事件9'

}

,

{

id

:

'2078061340905455778'

,

type

:

'event'

,

start_date

:

'2012-11-13 00:00'

,

end_date

:

'2012-11-22 23:59'

,

text

:

'事件10'

}

,

{

id

:

'-5722754109640979663'

,

type

:

'doc'

,

eventId

:

'-8165958465554986075'

,

eventCreateUserId

:

'684019058616189893'

,

eventReceiveMemberId

:

''

,

eventPeriodicalId

:

'null'

,

eventBeginDate

:

'2012-11-22'

,

start_date

:

'2012-12-25 11:00'

,

end_date

:

'2012-12-25 11:00'

,

text

:

'公文11'

,

ico

:

'work_time_set_16'

}

,

{

id

:

'-7346394655019678232'

,

type

:

'meeting'

,

eventId

:

'6836291771407417598'

,

eventCreateUserId

:

'684019058616189893'

,

eventReceiveMemberId

:

''

,

eventPeriodicalId

:

'null'

,

eventBeginDate

:

'2012-11-22'

,

start_date

:

'2012-11-22 11:00'

,

end_date

:

'2012-11-22 11:30'

,

text

:

'会议12'

}

,

{

id

:

'-4031401379237048532'

,

type

:

'plan'

,

eventId

:

'3259770405833755198'

,

eventCreateUserId

:

'684019058616189893'

,

eventReceiveMemberId

:

''

,

eventPeriodicalId

:

'null'

,

eventBeginDate

:

'2012-11-23'

,

start_date

:

'2012-11-23 11:30'

,

end_date

:

'2012-11-23 12:00'

,

text

:

'计划13'

}

,

{

id

:

'-4031401379237048542'

,

type

:

'task'

,

eventId

:

'3259770405833755198'

,

eventCreateUserId

:

'684019058616189893'

,

eventReceiveMemberId

:

''

,

eventPeriodicalId

:

'null'

,

eventBeginDate

:

'2012-11-23'

,

start_date

:

'2012-12-23 11:30'

,

end_date

:

'2012-12-23 12:00'

,

text

:

'任务14'

,

ico

:

'milestone right'

,

set_disable

:

true

}

,

{

id

:

'-4031401379237048552'

,

type

:

'task'

,

eventId

:

'3259770405833755198'

,

eventCreateUserId

:

'684019058616189893'

,

eventReceiveMemberId

:

''

,

eventPeriodicalId

:

'null'

,

start_date

:

'2011-12-19 11:30'

,

end_date

:

'2012-12-23 11:00'

,

text

:

'任务15'

,

ico

:

'milestone right'

}

]

,

"json"

)

;

$

(

"#itemize"

)

.

bind

(

{

mouseover

:

function

(

)

{

$

(

"#itemize_content"

)

.

removeClass

(

"hidden"

)

;

}

,

mouseout

:

function

(

)

{

$

(

"#itemize_content"

)

.

addClass

(

"hidden"

)

;

}

)

}

function

test

(

type

,

nextDate

)

{

alert

(

nextDate

)

}

$

(

function

(

)

{

$

(

"#dhx_cal_common_tabs li div"

)

.

click

(

function

(

)

{

$

(

"#dhx_cal_common_tabs li"

)

.

removeClass

(

"current"

)

;

$

(

this

)

.

parents

(

"li"

)

.

addClass

(

"current"

)

;

}

)

;

$

(

'#meeting11111'

)

.

hide

(

)

}

)

</

script

>

## 9. Table 表格

> 原始路径：`/components3.0/data/table.html`  
> 相对路径：`components3.0/data/table.md`  
> 页面 key：`v-3991dca6`  
> JS Chunk：`55.313a65b5.js`

Table 表格

基础表格

1

2

3

1

2

3

表格是由最简单的行、列、单元格构成的，根据浏览的目的和希望突出的信息不同，行、列、单元格都可以通过一些变化进行强调，这是将信息通过表格传达出去的最为根本的使用方式。

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

table

width

=

"

100%

"

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

class

=

"

only_table

"

>

<

thead

>

<

tr

>

<

th

>

1

</

th

>

<

th

>

2

</

th

>

<

th

>

3

</

th

>

</

tr

>

</

thead

>

<

tbody

>

<

tr

class

=

"

erow

"

>

<

td

>

1

</

td

>

<

td

>

2

</

td

>

<

td

>

3

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

</

div

>

固定表格

固定表头

2

3

start

2

3

end

2

3

end

2

3

end

2

3

end

2

3

end

2

3

end

2

3

end

2

3

<

div

class

=

"

list_content relative

"

style

=

"

height

:

100px

;

"

>

<

div

class

=

"

table_head relative

"

>

<!--表头-->

<

table

width

=

"

100%

"

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

class

=

"

only_table edit_table

"

>

<

tbody

>

<

tr

>

<

th

width

=

"

10%

"

>

固定表头

</

th

>

<

th

width

=

"

10%

"

>

2

</

th

>

<

th

width

=

"

10%

"

>

3

</

th

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

<

div

class

=

"

table_body absolute

"

>

<!--表身-->

<

table

width

=

"

100%

"

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

class

=

"

only_table edit_table

"

>

<

tbody

>

<

tr

>

<

td

>

start

</

td

>

<

td

>

2

</

td

>

<

td

>

3

</

td

>

</

tr

>

<

tr

>

<

td

width

=

"

10%

"

>

end

</

td

>

<

td

width

=

"

10%

"

>

2

</

td

>

<

td

width

=

"

10%

"

>

3

</

td

>

</

tr

>

<

tr

>

<

td

width

=

"

10%

"

>

end

</

td

>

<

td

width

=

"

10%

"

>

2

</

td

>

<

td

width

=

"

10%

"

>

3

</

td

>

</

tr

>

<

tr

>

<

td

width

=

"

10%

"

>

end

</

td

>

<

td

width

=

"

10%

"

>

2

</

td

>

<

td

width

=

"

10%

"

>

3

</

td

>

</

tr

>

<

tr

>

<

td

width

=

"

10%

"

>

end

</

td

>

<

td

width

=

"

10%

"

>

2

</

td

>

<

td

width

=

"

10%

"

>

3

</

td

>

</

tr

>

<

tr

>

<

td

width

=

"

10%

"

>

end

</

td

>

<

td

width

=

"

10%

"

>

2

</

td

>

<

td

width

=

"

10%

"

>

3

</

td

>

</

tr

>

<

tr

>

<

td

width

=

"

10%

"

>

end

</

td

>

<

td

width

=

"

10%

"

>

2

</

td

>

<

td

width

=

"

10%

"

>

3

</

td

>

</

tr

>

<

tr

>

<

td

width

=

"

10%

"

>

end

</

td

>

<

td

width

=

"

10%

"

>

2

</

td

>

<

td

width

=

"

10%

"

>

3

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

</

div

>

简要说明：

1、表格是一种组织整理数据的手段，主要承载数据的归纳、展示与对比的功能

2、表格由最简单的行、列、单元格构成的，根据浏览的目的和希望突出的信息不同，行、列、单元格都可以通过一些变化进行强调，这是将信息通过表格传达出去的
最为根本的使用方式

3、V5的表格分为两种：

A、静态表格：只做数据的静态展现，无法做数据穿透、不能进行列宽大小调整，排序，拖动列，过滤，搜索，分组，分页等功能

B、动态表格：数据可穿透，能进行列宽大小调整，排序，拖动列，过滤，搜索，分组，分页等功能，可以通过单选或多选的方式，查看并操作一个数据对象集合

交互细则：

1、所有文本居左对齐

2、默认显示20行信息，用户可以通过翻页控件设置条数，

下一次进入以用户设置条数为准？

## 10. Tree 树

> 原始路径：`/components3.0/data/tree.html`  
> 相对路径：`components3.0/data/tree.md`  
> 页面 key：`v-696ab35a`  
> JS Chunk：`56.6cad5405.js`

Tree 树

用于通过单选或多选方式查看和操作以层级方式组织的一组对象。

tree示例一[简单的tree]

var setting1 = {
callback: {
onClick: onClick1 //回调函数 onClick
}
}
var zNodes1 = [{
name: "根节点 - 展开-隐藏checkbox",
open: true,
children: [{
name: "父节点11 - 折叠",
iconSkin:'treeAccount',
children: [{
name: "叶子节点11",
iconSkin:'treeAccount',
children:[{
name: "叶子节点113",
iconSkin:'account'
}]
}, {
name: "叶子节点112",
iconSkin:'flow'
}, {
name: "叶子节点113",
iconSkin:'department'
}, {
name: "叶子节点114",
iconSkin:'department'
}]
}, {
name: "父节点12 - 折叠",
iconSkin:'treeDepartment',
children: [{
name: "叶子节点121"
}, {
name: "叶子节点122"
}, {
name: "叶子节点123"
}, {
name: "叶子节点124"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeMyKnowledge',
children:[{
name: "叶子节点121"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeAccountFile',
children:[{
name: "叶子节点121"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeGroupFile',
children:[{
name: "叶子节点121"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeProjectFile',
children:[{
name: "叶子节点121"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeEdocFile',
children:[{
name: "叶子节点121"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeCustomAccountFile',
children:[{
name: "叶子节点121"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeCustomGroupFile',
children:[{
name: "叶子节点121"
}]
}, {
name: "父节点13 - 没有子节点",
iconSkin:'treeCustomFile',
children:[{
name: "叶子节点121"
}]
}]
}];
function onClick1(e, treeId, treeNode) { //单击节点展开子节点
var zTree = $.fn.zTree.getZTreeObj("tree");
zTree.expandNode(treeNode);
}

$(document).ready(function () {
$.fn.zTree.init($("#tree"), setting1, zNodes1);//zTree 初始化方法，创建 zTree 必须使用此方法
});

<

ul

id

=

"

tree

"

class

=

"

treeDemo_0 ztree

"

>

</

ul

>

<

script

>

var

setting1

=

{

callback

:

{

onClick

:

onClick1

//回调函数 onClick

}

var

zNodes1

=

[

{

name

:

"根节点 - 展开-隐藏checkbox"

,

open

:

true

,

children

:

[

{

name

:

"父节点11 - 折叠"

,

iconSkin

:

'treeAccount'

,

children

:

[

{

name

:

"叶子节点11"

,

iconSkin

:

'treeAccount'

,

children

:

[

{

name

:

"叶子节点113"

,

iconSkin

:

'account'

}

]

}

,

{

name

:

"叶子节点112"

,

iconSkin

:

'flow'

}

,

{

name

:

"叶子节点113"

,

iconSkin

:

'department'

}

,

{

name

:

"叶子节点114"

,

iconSkin

:

'department'

}

]

}

,

{

name

:

"父节点12 - 折叠"

,

iconSkin

:

'treeDepartment'

,

children

:

[

{

name

:

"叶子节点121"

}

,

{

name

:

"叶子节点122"

}

,

{

name

:

"叶子节点123"

}

,

{

name

:

"叶子节点124"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeMyKnowledge'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeAccountFile'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeGroupFile'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeProjectFile'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeEdocFile'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeCustomAccountFile'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeCustomGroupFile'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

iconSkin

:

'treeCustomFile'

,

children

:

[

{

name

:

"叶子节点121"

}

]

}

]

}

]

;

function

onClick1

(

e

,

treeId

,

treeNode

)

{

//单击节点展开子节点

var

zTree

=

$

.

fn

.

zTree

.

getZTreeObj

(

"tree"

)

;

zTree

.

expandNode

(

treeNode

)

;

}

$

(

document

)

.

ready

(

function

(

)

{

$

.

fn

.

zTree

.

init

(

$

(

"#tree"

)

,

setting1

,

zNodes1

)

;

//zTree 初始化方法，创建 zTree 必须使用此方法

}

)

;

</

script

>

tree示例二[添加checkbox的tree]

var setting2 = {
check: {
enable: true, //设置 zTree 的节点上显示 checkbox/radio
chkStyle: "checkbox",//勾选框类型为checkbox
chkboxType: {
"Y": "ps",
"N": "ps"
}//勾选 checkbox 对于父子相互关联
},
callback: {
onClick: onClick2
}
}
var zNodes2 = [{
name: "根节点 - 展开-隐藏checkbox",
open: true,
children: [{
name: "父节点11 - 折叠",
children: [{
name: "叶子节点111--disabled"
}, {
name: "叶子节点112"
}, {
name: "叶子节点113"
}, {
name: "叶子节点114"
}]
}, {
name: "父节点12 - 折叠",
children: [{
name: "叶子节点121"
}, {
name: "叶子节点122"
}, {
name: "叶子节点123"
}, {
name: "叶子节点124"
}]
}, {
name: "父节点13 - 没有子节点",
isParent: true
}]
}];
function onClick2(e, treeId, treeNode) {
var zTree = $.fn.zTree.getZTreeObj("tree2");
zTree.expandNode(treeNode);
}

$(document).ready(function () {
$.fn.zTree.init($("#tree2"), setting2, zNodes2);
});

<

div

class

=

"

zTreeDemoBackground

"

>

<

ul

id

=

"

tree2

"

class

=

"

treeDemo_0 ztree

"

>

</

ul

>

</

div

>

<

script

>

var

setting2

=

{

check

:

{

enable

:

true

,

//设置 zTree 的节点上显示 checkbox/radio

chkStyle

:

"checkbox"

,

//勾选框类型为checkbox

chkboxType

:

{

"Y"

:

"ps"

,

"N"

:

"ps"

}

//勾选 checkbox 对于父子相互关联

}

,

callback

:

{

onClick

:

onClick2

}

var

zNodes2

=

[

{

name

:

"根节点 - 展开-隐藏checkbox"

,

open

:

true

,

children

:

[

{

name

:

"父节点11 - 折叠"

,

children

:

[

{

name

:

"叶子节点111--disabled"

}

,

{

name

:

"叶子节点112"

}

,

{

name

:

"叶子节点113"

}

,

{

name

:

"叶子节点114"

}

]

}

,

{

name

:

"父节点12 - 折叠"

,

children

:

[

{

name

:

"叶子节点121"

}

,

{

name

:

"叶子节点122"

}

,

{

name

:

"叶子节点123"

}

,

{

name

:

"叶子节点124"

}

]

}

,

{

name

:

"父节点13 - 没有子节点"

,

isParent

:

true

}

]

}

]

;

function

onClick2

(

e

,

treeId

,

treeNode

)

{

var

zTree

=

$

.

fn

.

zTree

.

getZTreeObj

(

"tree2"

)

;

zTree

.

expandNode

(

treeNode

)

;

}

$

(

document

)

.

ready

(

function

(

)

{

$

.

fn

.

zTree

.

init

(

$

(

"#tree2"

)

,

setting2

,

zNodes2

)

;

}

)

;

</

script

>

tree示例三[拖动接点]

var setting3 = {
edit: {
enable: true,
showRemoveBtn: false,
showRenameBtn: false
},
data: {
simpleData: {
enable: true
}
},
callback: {
beforeDrag: beforeDrag3,
beforeDrop: beforeDrop3
}
};

var zNodes3 = [
{ id: 1, pId: 0, name: "随意拖拽 1", open: true },
{ id: 11, pId: 1, name: "随意拖拽 1-1" },
{ id: 12, pId: 1, name: "随意拖拽 1-2", open: true },
{ id: 121, pId: 12, name: "随意拖拽 1-2-1" },
{ id: 122, pId: 12, name: "随意拖拽 1-2-2" },
{ id: 123, pId: 12, name: "随意拖拽 1-2-3" },
{ id: 13, pId: 1, name: "禁止拖拽 1-3", open: true, drag: false },
{ id: 131, pId: 13, name: "禁止拖拽 1-3-1", drag: false },
{ id: 132, pId: 13, name: "禁止拖拽 1-3-2", drag: false },
{ id: 133, pId: 13, name: "随意拖拽 1-3-3" },
{ id: 2, pId: 0, name: "随意拖拽 2", open: true },
{ id: 21, pId: 2, name: "随意拖拽 2-1" },
{ id: 22, pId: 2, name: "禁止拖拽到我身上 2-2", open: true, drop: false },
{ id: 221, pId: 22, name: "随意拖拽 2-2-1" },
{ id: 222, pId: 22, name: "随意拖拽 2-2-2" },
{ id: 223, pId: 22, name: "随意拖拽 2-2-3" },
{ id: 23, pId: 2, name: "随意拖拽 2-3" }
];

function beforeDrag3(treeId, treeNodes) {
for (var i = 0, l = treeNodes.length; i < l; i++) {
if (treeNodes[i].drag === false) {
return false;
}
}
return true;
}
function beforeDrop3(treeId, treeNodes, targetNode, moveType) {
return targetNode ? targetNode.drop !== false : true;
}

function setCheck3() {
// var zTree = $.fn.zTree.getZTreeObj("treeDemo3"),
// isCopy = $("#copy").attr("checked"),
// isMove = $("#move").attr("checked"),
// prev = $("#prev").attr("checked"),
// inner = $("#inner").attr("checked"),
// next = $("#next").attr("checked");
// zTree.setting.edit.drag.isCopy = isCopy;
// zTree.setting.edit.drag.isMove = isMove;
// showCode3(1, ['setting.edit.drag.isCopy = ' + isCopy, 'setting.edit.drag.isMove = ' + isMove]);
//
// zTree.setting.edit.drag.prev = prev;
// zTree.setting.edit.drag.inner = inner;
// zTree.setting.edit.drag.next = next;
// showCode3(2, ['setting.edit.drag.prev = ' + prev, 'setting.edit.drag.inner = ' + inner, 'setting.edit.drag.next = ' + next]);
}
function showCode3(id, str) {
var code = $("#code" + id);
code.empty();
for (var i = 0, l = str.length; i < l; i++) {
code.append("<li>" + str[i] + "</li>");
}
}

$(document).ready(function () {
$.fn.zTree.init($("#treeDemo3"), setting3, zNodes3);
setCheck3();
$("#copy").bind("change", setCheck3);
$("#move").bind("change", setCheck3);
$("#prev").bind("change", setCheck3);
$("#inner").bind("change", setCheck3);
$("#next").bind("change", setCheck3);
});

<

ul

id

=

"

treeDemo3

"

class

=

"

ztree

"

>

</

ul

>

<

script

type

=

"

text/javascript

"

>

var

setting3

=

{

edit

:

{

enable

:

true

,

showRemoveBtn

:

false

,

showRenameBtn

:

false

}

,

data

:

{

simpleData

:

{

enable

:

true

}

,

callback

:

{

beforeDrag

:

beforeDrag3

,

beforeDrop

:

beforeDrop3

}

;

var

zNodes3

=

[

{

id

:

1

,

pId

:

0

,

name

:

"随意拖拽 1"

,

open

:

true

}

,

{

id

:

11

,

pId

:

1

,

name

:

"随意拖拽 1-1"

}

,

{

id

:

12

,

pId

:

1

,

name

:

"随意拖拽 1-2"

,

open

:

true

}

,

{

id

:

121

,

pId

:

12

,

name

:

"随意拖拽 1-2-1"

}

,

{

id

:

122

,

pId

:

12

,

name

:

"随意拖拽 1-2-2"

}

,

{

id

:

123

,

pId

:

12

,

name

:

"随意拖拽 1-2-3"

}

,

{

id

:

13

,

pId

:

1

,

name

:

"禁止拖拽 1-3"

,

open

:

true

,

drag

:

false

}

,

{

id

:

131

,

pId

:

13

,

name

:

"禁止拖拽 1-3-1"

,

drag

:

false

}

,

{

id

:

132

,

pId

:

13

,

name

:

"禁止拖拽 1-3-2"

,

drag

:

false

}

,

{

id

:

133

,

pId

:

13

,

name

:

"随意拖拽 1-3-3"

}

,

{

id

:

2

,

pId

:

0

,

name

:

"随意拖拽 2"

,

open

:

true

}

,

{

id

:

21

,

pId

:

2

,

name

:

"随意拖拽 2-1"

}

,

{

id

:

22

,

pId

:

2

,

name

:

"禁止拖拽到我身上 2-2"

,

open

:

true

,

drop

:

false

}

,

{

id

:

221

,

pId

:

22

,

name

:

"随意拖拽 2-2-1"

}

,

{

id

:

222

,

pId

:

22

,

name

:

"随意拖拽 2-2-2"

}

,

{

id

:

223

,

pId

:

22

,

name

:

"随意拖拽 2-2-3"

}

,

{

id

:

23

,

pId

:

2

,

name

:

"随意拖拽 2-3"

}

]

;

function

beforeDrag3

(

treeId

,

treeNodes

)

{

for

(

var

i

=

0

,

l

=

treeNodes

.

length

;

i

<

l

;

i

++

)

{

if

(

treeNodes

[

i

]

.

drag

===

false

)

{

return

false

;

}

return

true

;

}

function

beforeDrop3

(

treeId

,

treeNodes

,

targetNode

,

moveType

)

{

return

targetNode

?

targetNode

.

drop

!==

false

:

true

;

}

function

setCheck3

(

)

{

// var zTree = $.fn.zTree.getZTreeObj("treeDemo3"),

// isCopy = $("#copy").attr("checked"),

// isMove = $("#move").attr("checked"),

// prev = $("#prev").attr("checked"),

// inner = $("#inner").attr("checked"),

// next = $("#next").attr("checked");

// zTree.setting.edit.drag.isCopy = isCopy;

// zTree.setting.edit.drag.isMove = isMove;

// showCode3(1, ['setting.edit.drag.isCopy = ' + isCopy, 'setting.edit.drag.isMove = ' + isMove]);

//

// zTree.setting.edit.drag.prev = prev;

// zTree.setting.edit.drag.inner = inner;

// zTree.setting.edit.drag.next = next;

// showCode3(2, ['setting.edit.drag.prev = ' + prev, 'setting.edit.drag.inner = ' + inner, 'setting.edit.drag.next = ' + next]);

}

function

showCode3

(

id

,

str

)

{

var

code

=

$

(

"#code"

+

id

)

;

code

.

empty

(

)

;

for

(

var

i

=

0

,

l

=

str

.

length

;

i

<

l

;

i

++

)

{

code

.

append

(

"<li>"

+

str

[

i

]

+

"</li>"

)

;

}

$

(

document

)

.

ready

(

function

(

)

{

$

.

fn

.

zTree

.

init

(

$

(

"#treeDemo3"

)

,

setting3

,

zNodes3

)

;

setCheck3

(

)

;

$

(

"#copy"

)

.

bind

(

"change"

,

setCheck3

)

;

$

(

"#move"

)

.

bind

(

"change"

,

setCheck3

)

;

$

(

"#prev"

)

.

bind

(

"change"

,

setCheck3

)

;

$

(

"#inner"

)

.

bind

(

"change"

,

setCheck3

)

;

$

(

"#next"

)

.

bind

(

"change"

,

setCheck3

)

;

}

)

;

</

script

>

tree示例四[可编辑tree]

var setting4 = {
edit: {
enable: true
},
data: {
simpleData: {
enable: true
}
},
callback: {
beforeDrag: beforeDrag4
}
};

var zNodes4 = [
{ id: 1, pId: 0, name: "父节点 1", open: true },
{ id: 11, pId: 1, name: "叶子节点 1-1" },
{ id: 12, pId: 1, name: "叶子节点 1-2是否上的法师打法师打发哒是否是法师打发生大幅是是" },
{ id: 13, pId: 1, name: "叶子节点 1-3" },
{ id: 2, pId: 0, name: "父节点 2", open: true },
{ id: 21, pId: 2, name: "叶子节点 2-1" },
{ id: 22, pId: 2, name: "叶子节点 2-2" },
{ id: 23, pId: 2, name: "叶子节点 2-3" },
{ id: 3, pId: 0, name: "父节点 3", open: true },
{ id: 31, pId: 3, name: "叶子节点 3-1" },
{ id: 32, pId: 3, name: "叶子节点 3-2" },
{ id: 33, pId: 3, name: "叶子节点 3-3" }
];

function beforeDrag4(treeId, treeNodes) {
return false;
}

function setEdit4() {
// var zTree = $.fn.zTree.getZTreeObj("treeDemo4"),
// remove = $("#remove").attr("checked"),
// rename = $("#rename").attr("checked"),
// removeTitle = $.trim($("#removeTitle").get(0).value),
// renameTitle = $.trim($("#renameTitle").get(0).value);
// zTree.setting.edit.showRemoveBtn = remove;
// zTree.setting.edit.showRenameBtn = rename;
// zTree.setting.edit.removeTitle = removeTitle;
// zTree.setting.edit.renameTitle = renameTitle;
// showCode4(['setting.edit.showRemoveBtn = ' + remove, 'setting.edit.showRenameBtn = ' + rename,
// 'setting.edit.removeTitle = "' + removeTitle +'"', 'setting.edit.renameTitle = "' + renameTitle + '"']);
}
function showCode4(str) {
var code = $("#code");
code.empty();
for (var i = 0, l = str.length; i < l; i++) {
code.append("<li>" + str[i] + "</li>");
}
}
$(document).ready(function () {
$.fn.zTree.init($("#treeDemo4"), setting4, zNodes4);
setEdit4();
$("#remove").bind("change", setEdit4);
$("#rename").bind("change", setEdit4);
$("#removeTitle").bind("propertychange", setEdit4)
.bind("input", setEdit4);
$("#renameTitle").bind("propertychange", setEdit4)
.bind("input", setEdit4);
});

<

ul

id

=

"

treeDemo4

"

class

=

"

ztree

"

>

</

ul

>

<

script

type

=

"

text/javascript

"

>

var

setting4

=

{

edit

:

{

enable

:

true

}

,

data

:

{

simpleData

:

{

enable

:

true

}

,

callback

:

{

beforeDrag

:

beforeDrag4

}

;

var

zNodes4

=

[

{

id

:

1

,

pId

:

0

,

name

:

"父节点 1"

,

open

:

true

}

,

{

id

:

11

,

pId

:

1

,

name

:

"叶子节点 1-1"

}

,

{

id

:

12

,

pId

:

1

,

name

:

"叶子节点 1-2是否上的法师打法师打发哒是否是法师打发生大幅是是"

}

,

{

id

:

13

,

pId

:

1

,

name

:

"叶子节点 1-3"

}

,

{

id

:

2

,

pId

:

0

,

name

:

"父节点 2"

,

open

:

true

}

,

{

id

:

21

,

pId

:

2

,

name

:

"叶子节点 2-1"

}

,

{

id

:

22

,

pId

:

2

,

name

:

"叶子节点 2-2"

}

,

{

id

:

23

,

pId

:

2

,

name

:

"叶子节点 2-3"

}

,

{

id

:

3

,

pId

:

0

,

name

:

"父节点 3"

,

open

:

true

}

,

{

id

:

31

,

pId

:

3

,

name

:

"叶子节点 3-1"

}

,

{

id

:

32

,

pId

:

3

,

name

:

"叶子节点 3-2"

}

,

{

id

:

33

,

pId

:

3

,

name

:

"叶子节点 3-3"

}

]

;

function

beforeDrag4

(

treeId

,

treeNodes

)

{

return

false

;

}

function

setEdit4

(

)

{

// var zTree = $.fn.zTree.getZTreeObj("treeDemo4"),

// remove = $("#remove").attr("checked"),

// rename = $("#rename").attr("checked"),

// removeTitle = $.trim($("#removeTitle").get(0).value),

// renameTitle = $.trim($("#renameTitle").get(0).value);

// zTree.setting.edit.showRemoveBtn = remove;

// zTree.setting.edit.showRenameBtn = rename;

// zTree.setting.edit.removeTitle = removeTitle;

// zTree.setting.edit.renameTitle = renameTitle;

// showCode4(['setting.edit.showRemoveBtn = ' + remove, 'setting.edit.showRenameBtn = ' + rename,

// 'setting.edit.removeTitle = "' + removeTitle +'"', 'setting.edit.renameTitle = "' + renameTitle + '"']);

}

function

showCode4

(

str

)

{

var

code

=

$

(

"#code"

)

;

code

.

empty

(

)

;

for

(

var

i

=

0

,

l

=

str

.

length

;

i

<

l

;

i

++

)

{

code

.

append

(

"<li>"

+

str

[

i

]

+

"</li>"

)

;

}

$

(

document

)

.

ready

(

function

(

)

{

$

.

fn

.

zTree

.

init

(

$

(

"#treeDemo4"

)

,

setting4

,

zNodes4

)

;

setEdit4

(

)

;

$

(

"#remove"

)

.

bind

(

"change"

,

setEdit4

)

;

$

(

"#rename"

)

.

bind

(

"change"

,

setEdit4

)

;

$

(

"#removeTitle"

)

.

bind

(

"propertychange"

,

setEdit4

)

.

bind

(

"input"

,

setEdit4

)

;

$

(

"#renameTitle"

)

.

bind

(

"propertychange"

,

setEdit4

)

.

bind

(

"input"

,

setEdit4

)

;

}

)

;

</

script

>

tree示例五[两列tree--]

var setting5 = {
edit: {
enable: true,
showRemoveBtn: false,
showRenameBtn: false
},
data: {
simpleData: {
enable: true
}
},
callback: {
beforeDrag: beforeDrag5,
beforeDrop: beforeDrop5
}
};

var zNodes5 = [
{ id: 1, pId: 0, name: "父节点 1", open: true },
{ id: 11, pId: 1, name: "叶子节点 1-1" },
{ id: 12, pId: 1, name: "叶子节点 1-2" },
{ id: 13, pId: 1, name: "叶子节点 1-3" },
{ id: 2, pId: 0, name: "父节点 2", open: true },
{ id: 21, pId: 2, name: "叶子节点 2-1" },
{ id: 22, pId: 2, name: "叶子节点 2-2" },
{ id: 23, pId: 2, name: "叶子节点 2-3" },
{ id: 3, pId: 0, name: "父节点 3", open: true },
{ id: 31, pId: 3, name: "叶子节点 3-1" },
{ id: 32, pId: 3, name: "叶子节点 3-2" },
{ id: 33, pId: 3, name: "叶子节点 3-3" }
];

function beforeDrag5(treeId, treeNodes) {
for (var i = 0, l = treeNodes.length; i < l; i++) {
if (treeNodes[i].drag === false) {
return false;
}
}
return true;
}
function beforeDrop5(treeId, treeNodes, targetNode, moveType) {
return targetNode ? targetNode.drop !== false : true;
}

$(document).ready(function () {
$.fn.zTree.init($("#treeDemo51"), setting5, zNodes5);
$.fn.zTree.init($("#treeDemo52"), setting5);

});

<

table

>

<

tbody

>

<

tr

>

<

td

width

=

"

200

"

>

<

ul

id

=

"

treeDemo51

"

class

=

"

ztree border_all

"

style

=

"

height

:

300px

;

"

>

</

ul

>

</

td

>

<

td

width

=

"

200

"

>

<

ul

id

=

"

treeDemo52

"

class

=

"

ztree border_all

"

style

=

"

height

:

300px

;

"

>

</

ul

>

</

td

>

</

tr

>

</

tbody

>

</

table

>

<

script

type

=

"

text/javascript

"

>

var

setting5

=

{

edit

:

{

enable

:

true

,

showRemoveBtn

:

false

,

showRenameBtn

:

false

}

,

data

:

{

simpleData

:

{

enable

:

true

}

,

callback

:

{

beforeDrag

:

beforeDrag5

,

beforeDrop

:

beforeDrop5

}

;

var

zNodes5

=

[

{

id

:

1

,

pId

:

0

,

name

:

"父节点 1"

,

open

:

true

}

,

{

id

:

11

,

pId

:

1

,

name

:

"叶子节点 1-1"

}

,

{

id

:

12

,

pId

:

1

,

name

:

"叶子节点 1-2"

}

,

{

id

:

13

,

pId

:

1

,

name

:

"叶子节点 1-3"

}

,

{

id

:

2

,

pId

:

0

,

name

:

"父节点 2"

,

open

:

true

}

,

{

id

:

21

,

pId

:

2

,

name

:

"叶子节点 2-1"

}

,

{

id

:

22

,

pId

:

2

,

name

:

"叶子节点 2-2"

}

,

{

id

:

23

,

pId

:

2

,

name

:

"叶子节点 2-3"

}

,

{

id

:

3

,

pId

:

0

,

name

:

"父节点 3"

,

open

:

true

}

,

{

id

:

31

,

pId

:

3

,

name

:

"叶子节点 3-1"

}

,

{

id

:

32

,

pId

:

3

,

name

:

"叶子节点 3-2"

}

,

{

id

:

33

,

pId

:

3

,

name

:

"叶子节点 3-3"

}

]

;

function

beforeDrag5

(

treeId

,

treeNodes

)

{

for

(

var

i

=

0

,

l

=

treeNodes

.

length

;

i

<

l

;

i

++

)

{

if

(

treeNodes

[

i

]

.

drag

===

false

)

{

return

false

;

}

return

true

;

}

function

beforeDrop5

(

treeId

,

treeNodes

,

targetNode

,

moveType

)

{

return

targetNode

?

targetNode

.

drop

!==

false

:

true

;

}

$

(

document

)

.

ready

(

function

(

)

{

$

.

fn

.

zTree

.

init

(

$

(

"#treeDemo51"

)

,

setting5

,

zNodes5

)

;

$

.

fn

.

zTree

.

init

(

$

(

"#treeDemo52"

)

,

setting5

)

;

}

)

;

</

script

>

tree示例六[自定义tree--进度条]

var IDMark_Switch = "_switch",
IDMark_Icon = "_ico",
IDMark_Span = "_span",
IDMark_Input = "_input",
IDMark_Check = "_check",
IDMark_Edit = "_edit",
IDMark_Remove = "_remove",
IDMark_Ul = "_ul",
IDMark_A = "_a";

var setting6 = {
view: {
addDiyDom: addDiyDom
}
};

var zNodes6 = [
{
id: 1, name: "hover事件显示控件", open: true,
children: [
{ id: 11, name: "按钮1" },
{ id: 12, name: "按钮2" },
{ id: 13, name: "下拉框" },
{ id: 141, name: "文本1" },
{ id: 142, name: "文本2" },
{ id: 15, name: "超链接" }

]
},
{
id: 2, name: "始终显示控件", open: true,
children: [
{ id: 21, name: "按钮1" },
{ id: 22, name: "按钮2" },
{ id: 23, name: "下拉框" },
{ id: 24, name: "文本" },
{ id: 25, name: "超链接" }
]
}
];


function addDiyDom(treeId, treeNode) {
if (treeNode.parentNode && treeNode.parentNode.id != 2) return;
var aObj = $("#" + treeNode.tId + IDMark_A);
if (treeNode.id == 21) {
var editStr = "<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>";
aObj.append(editStr);
} else if (treeNode.id == 22) {
var editStr = "<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>";
aObj.after(editStr);
} else if (treeNode.id == 23) {
var editStr = "<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>";
aObj.after(editStr);
} else if (treeNode.id == 24) {
var editStr = "<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>";
aObj.after(editStr);
} else if (treeNode.id == 25) {
var editStr = "<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>";
aObj.after(editStr);
}
}

$(document).ready(function () {
$.fn.zTree.init($("#treeDemo6"), setting6, zNodes6);
});
//-->

<

ul

id

=

"

treeDemo6

"

class

=

"

ztree

"

>

</

ul

>

<

script

type

=

"

text/javascript

"

>

var

IDMark_Switch

=

"_switch"

,

IDMark_Icon

=

"_ico"

,

IDMark_Span

=

"_span"

,

IDMark_Input

=

"_input"

,

IDMark_Check

=

"_check"

,

IDMark_Edit

=

"_edit"

,

IDMark_Remove

=

"_remove"

,

IDMark_Ul

=

"_ul"

,

IDMark_A

=

"_a"

;

var

setting6

=

{

view

:

{

addDiyDom

:

addDiyDom

}

;

var

zNodes6

=

[

{

id

:

1

,

name

:

"hover事件显示控件"

,

open

:

true

,

children

:

[

{

id

:

11

,

name

:

"按钮1"

}

,

{

id

:

12

,

name

:

"按钮2"

}

,

{

id

:

13

,

name

:

"下拉框"

}

,

{

id

:

141

,

name

:

"文本1"

}

,

{

id

:

142

,

name

:

"文本2"

}

,

{

id

:

15

,

name

:

"超链接"

}

]

}

,

{

id

:

2

,

name

:

"始终显示控件"

,

open

:

true

,

children

:

[

{

id

:

21

,

name

:

"按钮1"

}

,

{

id

:

22

,

name

:

"按钮2"

}

,

{

id

:

23

,

name

:

"下拉框"

}

,

{

id

:

24

,

name

:

"文本"

}

,

{

id

:

25

,

name

:

"超链接"

}

]

}

]

;

function

addDiyDom

(

treeId

,

treeNode

)

{

if

(

treeNode

.

parentNode

&&

treeNode

.

parentNode

.

id

!=

2

)

return

;

var

aObj

=

$

(

"#"

+

treeNode

.

tId

+

IDMark_A

)

;

if

(

treeNode

.

id

==

21

)

{

var

editStr

=

"<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>"

;

aObj

.

append

(

editStr

)

;

}

else

if

(

treeNode

.

id

==

22

)

{

var

editStr

=

"<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>"

;

aObj

.

after

(

editStr

)

;

}

else

if

(

treeNode

.

id

==

23

)

{

var

editStr

=

"<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>"

;

aObj

.

after

(

editStr

)

;

}

else

if

(

treeNode

.

id

==

24

)

{

var

editStr

=

"<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>"

;

aObj

.

after

(

editStr

)

;

}

else

if

(

treeNode

.

id

==

25

)

{

var

editStr

=

"<span style='display: inline-block;background:#ccc;width:200px;height:12px;'></span><span>30%</span>"

;

aObj

.

after

(

editStr

)

;

}

$

(

document

)

.

ready

(

function

(

)

{

$

.

fn

.

zTree

.

init

(

$

(

"#treeDemo6"

)

,

setting6

,

zNodes6

)

;

}

)

;

//-->

</

script

>

tree示例七[自定义tree--右键菜单]

var setting7 = {
view: {
dblClickExpand: false
},
check: {
enable: true
},
callback: {
onRightClick: OnRightClick
}
};

var zNodes7 = [
{
id: 1, name: "无右键菜单 1", open: true, noR: true,
iconSkin:"treeDepartment",
children: [
{ id: 11, name: "节点 1-1", noR: true },
{ id: 12, name: "节点 1-2", noR: true }

]
},
{
id: 2, name: "右键操作 2", open: true,
iconSkin:"treeMyKnowledge",
children: [
{ id: 21, name: "节点 2-1" },
{ id: 22, name: "节点 2-2" },
{ id: 23, name: "节点 2-3" },
{ id: 24, name: "节点 2-4" }
]
},
{
id: 3, name: "右键操作 3", open: true,
iconSkin:"treeAccount",
children: [
{ id: 31, name: "节点 3-1" },
{ id: 32, name: "节点 3-2" },
{ id: 33, name: "节点 3-3" },
{ id: 34, name: "节点 3-4" }
]
}
];

function OnRightClick(event, treeId, treeNode) {
if (!treeNode && event.target.tagName.toLowerCase() != "button" && $(event.target).parents("a").length == 0) {
zTree.cancelSelectedNode();
var distance = getElementDistance(event.srcElement, event.currentTarget);
showRMenu("root", distance.left, distance.top);
} else if (treeNode && !treeNode.noR) {
zTree.selectNode(treeNode);
var distance = getElementDistance(event.srcElement, event.currentTarget);
showRMenu("node", distance.left, distance.top);
}
}

function getElementDistance(element, parentDom) {
const rect1 = element.getBoundingClientRect();
const rect2 = parentDom.getBoundingClientRect();
return {
top: rect1.top - rect2.top + 20,
left: rect1.left - rect2.left + 20
};
}

function showRMenu(type, x, y) {
$("#rMenu ul").show();
if (type == "root") {
$("#m_del").hide();
$("#m_check").hide();
$("#m_unCheck").hide();
} else {
$("#m_del").show();
$("#m_check").show();
$("#m_unCheck").show();
}

rMenu.css({ "top": y + "px", "left": x + "px", "visibility": "visible" });

$("body").bind("mousedown", onBodyMouseDown);
}
function hideRMenu() {
if (rMenu) rMenu.css({ "visibility": "hidden" });
$("body").unbind("mousedown", onBodyMouseDown);
}
function onBodyMouseDown(event) {
if (!(event.target.id == "rMenu" || $(event.target).parents("#rMenu").length > 0)) {
rMenu.css({ "visibility": "hidden" });
}
}
var addCount = 1;
function addTreeNode() {
hideRMenu();
zTree.addNodes(zTree.getSelectedNodes()[0], [{ name: "增加" + (addCount++), checked: zTree.getSelectedNodes()[0].checked }]);
}
function removeTreeNode() {
hideRMenu();
var nodes = zTree.getSelectedNodes();
if (nodes && nodes.length > 0) {
if (nodes[0].children && nodes[0].children.length > 0) {
var msg = "要删除的节点是父节点，如果删除将连同子节点一起删掉。\n\n请确认！";
if (confirm(msg) == true) {
zTree.removeNode(nodes[0]);
}
} else {
zTree.removeNode(nodes[0]);
}
}
}
function checkTreeNode(checked) {
var nodes = zTree.getSelectedNodes();
if (nodes && nodes.length > 0) {
zTree.checkNode(nodes[0], checked, true);
}
hideRMenu();
}
function resetTree() {
hideRMenu();
$.fn.zTree.init($("#treeDemo7"), setting7, zNodes7);
}

var zTree, rMenu;
$(document).ready(function () {
$.fn.zTree.init($("#treeDemo7"), setting7, zNodes7);
zTree = $.fn.zTree.getZTreeObj("treeDemo7");
rMenu = $("#rMenu");
});

div#rMenu {
position: absolute;
visibility: hidden;
top: 0;
background-color: #555;
text-align: left;
padding: 2px;
}

div#rMenu ul li {
margin: 1px 0;
padding: 0 5px;
cursor: pointer;
list-style: none outside none;
background-color: #DFDFDF;
}
.treeBox {
position: relative;
}

增加节点

删除节点

Check节点

unCheck节点

恢复zTree

<

script

type

=

"

text/javascript

"

>

var

setting7

=

{

view

:

{

dblClickExpand

:

false

}

,

check

:

{

enable

:

true

}

,

callback

:

{

onRightClick

:

OnRightClick

}

;

var

zNodes7

=

[

{

id

:

1

,

name

:

"无右键菜单 1"

,

open

:

true

,

noR

:

true

,

iconSkin

:

"treeDepartment"

,

children

:

[

{

id

:

11

,

name

:

"节点 1-1"

,

noR

:

true

}

,

{

id

:

12

,

name

:

"节点 1-2"

,

noR

:

true

}

]

}

,

{

id

:

2

,

name

:

"右键操作 2"

,

open

:

true

,

iconSkin

:

"treeMyKnowledge"

,

children

:

[

{

id

:

21

,

name

:

"节点 2-1"

}

,

{

id

:

22

,

name

:

"节点 2-2"

}

,

{

id

:

23

,

name

:

"节点 2-3"

}

,

{

id

:

24

,

name

:

"节点 2-4"

}

]

}

,

{

id

:

3

,

name

:

"右键操作 3"

,

open

:

true

,

iconSkin

:

"treeAccount"

,

children

:

[

{

id

:

31

,

name

:

"节点 3-1"

}

,

{

id

:

32

,

name

:

"节点 3-2"

}

,

{

id

:

33

,

name

:

"节点 3-3"

}

,

{

id

:

34

,

name

:

"节点 3-4"

}

]

}

]

;

function

OnRightClick

(

event

,

treeId

,

treeNode

)

{

if

(

!

treeNode

&&

event

.

target

.

tagName

.

toLowerCase

(

)

!=

"button"

&&

$

(

event

.

target

)

.

parents

(

"a"

)

.

length

==

0

)

{

zTree

.

cancelSelectedNode

(

)

;

var

distance

=

getElementDistance

(

event

.

srcElement

,

event

.

currentTarget

)

;

showRMenu

(

"root"

,

distance

.

left

,

distance

.

top

)

;

}

else

if

(

treeNode

&&

!

treeNode

.

noR

)

{

zTree

.

selectNode

(

treeNode

)

;

var

distance

=

getElementDistance

(

event

.

srcElement

,

event

.

currentTarget

)

;

showRMenu

(

"node"

,

distance

.

left

,

distance

.

top

)

;

}

function

getElementDistance

(

element

,

parentDom

)

{

const

rect1

=

element

.

getBoundingClientRect

(

)

;

const

rect2

=

parentDom

.

getBoundingClientRect

(

)

;

return

{

top

:

rect1

.

top

-

rect2

.

top

+

20

,

left

:

rect1

.

left

-

rect2

.

left

+

20

}

;

}

function

showRMenu

(

type

,

x

,

y

)

{

$

(

"#rMenu ul"

)

.

show

(

)

;

if

(

type

==

"root"

)

{

$

(

"#m_del"

)

.

hide

(

)

;

$

(

"#m_check"

)

.

hide

(

)

;

$

(

"#m_unCheck"

)

.

hide

(

)

;

}

else

{

$

(

"#m_del"

)

.

show

(

)

;

$

(

"#m_check"

)

.

show

(

)

;

$

(

"#m_unCheck"

)

.

show

(

)

;

}

rMenu

.

css

(

{

"top"

:

y

+

"px"

,

"left"

:

x

+

"px"

,

"visibility"

:

"visible"

}

)

;

$

(

"body"

)

.

bind

(

"mousedown"

,

onBodyMouseDown

)

;

}

function

hideRMenu

(

)

{

if

(

rMenu

)

rMenu

.

css

(

{

"visibility"

:

"hidden"

}

)

;

$

(

"body"

)

.

unbind

(

"mousedown"

,

onBodyMouseDown

)

;

}

function

onBodyMouseDown

(

event

)

{

if

(

!

(

event

.

target

.

id

==

"rMenu"

||

$

(

event

.

target

)

.

parents

(

"#rMenu"

)

.

length

>

0

)

{

rMenu

.

css

(

{

"visibility"

:

"hidden"

}

)

;

}

var

addCount

=

1

;

function

addTreeNode

(

)

{

hideRMenu

(

)

;

zTree

.

addNodes

(

zTree

.

getSelectedNodes

(

)

[

0

]

,

[

{

name

:

"增加"

+

(

addCount

++

)

,

checked

:

zTree

.

getSelectedNodes

(

)

[

0

]

.

checked

}

]

)

;

}

function

removeTreeNode

(

)

{

hideRMenu

(

)

;

var

nodes

=

zTree

.

getSelectedNodes

(

)

;

if

(

nodes

&&

nodes

.

length

>

0

)

{

if

(

nodes

[

0

]

.

children

&&

nodes

[

0

]

.

children

.

length

>

0

)

{

var

msg

=

"要删除的节点是父节点，如果删除将连同子节点一起删掉。\n\n请确认！"

;

if

(

confirm

(

msg

)

==

true

)

{

zTree

.

removeNode

(

nodes

[

0

]

)

;

}

else

{

zTree

.

removeNode

(

nodes

[

0

]

)

;

}

function

checkTreeNode

(

checked

)

{

var

nodes

=

zTree

.

getSelectedNodes

(

)

;

if

(

nodes

&&

nodes

.

length

>

0

)

{

zTree

.

checkNode

(

nodes

[

0

]

,

checked

,

true

)

;

}

hideRMenu

(

)

;

}

function

resetTree

(

)

{

hideRMenu

(

)

;

$

.

fn

.

zTree

.

init

(

$

(

"#treeDemo7"

)

,

setting7

,

zNodes7

)

;

}

var

zTree

,

rMenu

;

$

(

document

)

.

ready

(

function

(

)

{

$

.

fn

.

zTree

.

init

(

$

(

"#treeDemo7"

)

,

setting7

,

zNodes7

)

;

zTree

=

$

.

fn

.

zTree

.

getZTreeObj

(

"treeDemo7"

)

;

rMenu

=

$

(

"#rMenu"

)

;

}

)

;

</

script

>

<

style

type

=

"

text/css

"

>

div#rMenu

{

position

:

absolute

;

visibility

:

hidden

;

top

:

0

;

background-color

:

#555

;

text-align

:

left

;

padding

:

2px

;

}

div#rMenu ul li

{

margin

:

1px 0

;

padding

:

0 5px

;

cursor

:

pointer

;

list-style

:

none outside none

;

background-color

:

#DFDFDF

;

}

.treeBox

{

position

:

relative

;

}

</

style

>

<

div

class

=

"

treeBox

"

>

<

ul

id

=

"

treeDemo7

"

class

=

"

ztree

"

>

</

ul

>

<

div

id

=

"

rMenu

"

>

<

ul

>

<

li

id

=

"

m_add

"

onclick

=

"

addTreeNode

(

)

;

"

>

增加节点

</

li

>

<

li

id

=

"

m_del

"

onclick

=

"

removeTreeNode

(

)

;

"

>

删除节点

</

li

>

<

li

id

=

"

m_check

"

onclick

=

"

checkTreeNode

(

true

)

;

"

>

Check节点

</

li

>

<

li

id

=

"

m_unCheck

"

onclick

=

"

checkTreeNode

(

false

)

;

"

>

unCheck节点

</

li

>

<

li

id

=

"

m_reset

"

onclick

=

"

resetTree

(

)

;

"

>

恢复zTree

</

li

>

</

ul

>

</

div

>

</

div

>

## 11. Calender 时间控件

> 原始路径：`/components3.0/form/calender.html`  
> 相对路径：`components3.0/form/calender.md`  
> 页面 key：`v-1569ffda`  
> JS Chunk：`25.3d8a1c07.js`

Calender 时间控件

可选择不同的时间节点，用于设置时间点及时间段。

基本使用

通过comp渲染组件

单个时间段

function callback(){
alert("事件更新后回调时间");
}

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'calendar',ifFormat:'%Y-%m-%d %H:%M',showsTime:true,cache:false,isClear:true,clearBlank:false,onUpdate:callback,isMini:true

"

/>

<

script

>

function

callback

(

)

{

alert

(

"事件更新后回调时间"

)

;

}

</

script

>

组合时间

开始时间:

结束时间：

$(function(){
var date = new Date();
var fromDate = date.print("%Y-%m-%d %H:%M");
toDate = date.getTime() + 1800000;//结束时间：默认显示当前时间加30分钟
$("#fromdate1").val(fromDate);//开始时间：默认显示当前时间
$("#todate1").val(new Date(toDate).print("%Y-%m-%d %H:%M"));
})
function bdCallback(obj){
var beginDate = $("#fromdate1").attr("value");//初始时间 string
var endDate = $("#todate1").attr("value");//结束时间 string
var p = obj.params;
var format = p.ifFormat;//日期格式
var now = new Date().print(format);//当前时间
var formDate = obj.date;//开始时间对象
var update = obj.dateClicked || p.electric;
if (update && p.singleClick && obj.dateClicked){//判断日历是否关闭
if(beginDate > now && beginDate != endDate){ //如果开始时间大于当前时间且不等于结束时间
var toDate=formDate.getTime() + 1800000//借宿时间加30分钟
$("#todate1").val(new Date(toDate).print(format))
}
}
}
function checkto1(obj){
var endDate = $("#todate1").attr("value");//结束时间 string
var p = obj.params;
var format = p.ifFormat;//日期格式
var now = new Date().print(format);//当前时间
var toDate = initDate(endDate);//结束时间对象
var update = obj.dateClicked || p.electric;
if (update && p.singleClick && obj.dateClicked){//判断日历是否关闭
if(endDate < now){ //如果结束时间小于开始时间
var formDate = toDate.getTime() - 1800000//开始时间减30分钟
$("#fromdate1").val(new Date(formDate).print(format))
}
}
}

开始时间:

<

input

id

=

"

fromdate1

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'calendar',dateString:'2012-12-16 17:59',onUpdate:bdCallback,ifFormat:'%Y-%m-%d %H:%M',showsTime:true,cache:false,isMini: true

"

/>

结束时间：

<

input

id

=

"

todate1

"

type

=

"

text

"

value

=

"

2012-12-16 17:59

"

class

=

"

comp

"

comp

=

"

type:'calendar',onUpdate:checkto1,ifFormat:'%Y-%m-%d %H:%M',showsTime:true,cache:false,isMini: true

"

/>

<

script

type

=

"

text/javascript

"

>

$

(

function

(

)

{

var

date

=

new

Date

(

)

;

var

fromDate

=

date

.

print

(

"%Y-%m-%d %H:%M"

)

;

toDate

=

date

.

getTime

(

)

+

1800000

;

//结束时间：默认显示当前时间加30分钟

$

(

"#fromdate1"

)

.

val

(

fromDate

)

;

//开始时间：默认显示当前时间

$

(

"#todate1"

)

.

val

(

new

Date

(

toDate

)

.

print

(

"%Y-%m-%d %H:%M"

)

;

}

)

function

bdCallback

(

obj

)

{

var

beginDate

=

$

(

"#fromdate1"

)

.

attr

(

"value"

)

;

//初始时间 string

var

endDate

=

$

(

"#todate1"

)

.

attr

(

"value"

)

;

//结束时间 string

var

p

=

obj

.

params

;

var

format

=

p

.

ifFormat

;

//日期格式

var

now

=

new

Date

(

)

.

print

(

format

)

;

//当前时间

var

formDate

=

obj

.

date

;

//开始时间对象

var

update

=

obj

.

dateClicked

||

p

.

electric

;

if

(

update

&&

p

.

singleClick

&&

obj

.

dateClicked

)

{

//判断日历是否关闭

if

(

beginDate

>

now

&&

beginDate

!=

endDate

)

{

//如果开始时间大于当前时间且不等于结束时间

var

toDate

=

formDate

.

getTime

(

)

+

1800000

//借宿时间加30分钟

$

(

"#todate1"

)

.

val

(

new

Date

(

toDate

)

.

print

(

format

)

}

function

checkto1

(

obj

)

{

var

endDate

=

$

(

"#todate1"

)

.

attr

(

"value"

)

;

//结束时间 string

var

p

=

obj

.

params

;

var

format

=

p

.

ifFormat

;

//日期格式

var

now

=

new

Date

(

)

.

print

(

format

)

;

//当前时间

var

toDate

=

initDate

(

endDate

)

;

//结束时间对象

var

update

=

obj

.

dateClicked

||

p

.

electric

;

if

(

update

&&

p

.

singleClick

&&

obj

.

dateClicked

)

{

//判断日历是否关闭

if

(

endDate

<

now

)

{

//如果结束时间小于开始时间

var

formDate

=

toDate

.

getTime

(

)

-

1800000

//开始时间减30分钟

$

(

"#fromdate1"

)

.

val

(

new

Date

(

formDate

)

.

print

(

format

)

}

</

script

>

通过js渲染组件

时间控件

function renderDom(id){
var callback = function(){

}
$.calendar({
displayArea: id,
returnValue: true,
date: new Date(),
onUpdate: callback,
autoShow: true,
ifFormat: "%Y-%m-%d %H:%M",
daFormat: "%Y-%m-%d %H:%M",
showsTime: true,
isClear: false,
isMini: true
});
}

<

a

id

=

"

calendar1

"

href

=

"

javascript:renderDom('calendar1')

"

>

时间控件

</

a

>

<

script

type

=

"

text/javascript

"

>

function

renderDom

(

id

)

{

var

callback

=

function

(

)

{

}

$

.

calendar

(

{

displayArea

:

id

,

returnValue

:

true

,

date

:

new

Date

(

)

,

onUpdate

:

callback

,

autoShow

:

true

,

ifFormat

:

"%Y-%m-%d %H:%M"

,

daFormat

:

"%Y-%m-%d %H:%M"

,

showsTime

:

true

,

isClear

:

false

,

isMini

:

true

}

)

;

}

</

script

>

属性

类型

描述

displayArea

string

要绑定日期控件的ID

ifFormat

string

日期选择结果的格式

showsTime

boolean

是否显示时间选择

autoShow

boolean

是否直接显示时间日历

dateString

string

控件打开显示的默认日期

position

[]

显示的相对位置[10,10]

onUpdate

function

选择日期后执行的方法

isMini

boolean

是否调用迷你的选择日期组件（适用于iframe里面）

## 12. Checkbox 复选

> 原始路径：`/components3.0/form/checkbox.html`  
> 相对路径：`components3.0/form/checkbox.md`  
> 页面 key：`v-62910d33`  
> JS Chunk：`57.3e6329dd.js`

Checkbox 复选

用于在两个或两个以上有清晰差别的选项中进行选择。复选框的标签是对选中状态的描述，而清除状态的含义必须与选中状态明确相反。因此，复选框应当仅用于切换选项的开关状态，或者是选择

基本使用

横排checkbox

选项1

选项2

选项3

选项4

选项6

选项7

<

div

class

=

"

common_checkbox_box clearfix

"

>

<

label

for

=

"

Checkbox1

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox1

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项1

</

label

>

<

label

for

=

"

Checkbox2

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox2

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项2

</

label

>

<

label

for

=

"

Checkbox3

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox3

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项3

</

label

>

<

label

for

=

"

Checkbox4

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox4

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项4

</

label

>

</

div

>

<

div

class

=

"

common_checkbox_box clearfix

"

>

<

label

for

=

"

radio6

"

class

=

"

skin-checkbox margin_r_10 disabled_color

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

radio6

"

name

=

"

option

"

disabled

=

"

true

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项6

</

label

>

<

label

for

=

"

radio7

"

class

=

"

skin-checkbox margin_r_10 disabled_color

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

radio7

"

name

=

"

option

"

disabled

=

"

true

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项7

</

label

>

</

div

>

竖排checkbox

选项1

选项2

选项3

选项4

<

div

class

=

"

common_checkbox_box clearfix

"

>

<

label

for

=

"

Checkbox5

"

class

=

"

skin-checkbox margin_t_5 hand display_block

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox5

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项1

</

label

>

<

label

for

=

"

Checkbox6

"

class

=

"

skin-checkbox margin_t_5 hand display_block

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox6

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项2

</

label

>

<

label

for

=

"

Checkbox7

"

class

=

"

skin-checkbox margin_t_5 hand display_block

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox7

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项3

</

label

>

<

label

for

=

"

Checkbox8

"

class

=

"

skin-checkbox margin_t_5 hand display_block

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

Checkbox8

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项4

</

label

>

</

div

>

横排checkbox 居中显示

选项1

选项2

选项3

选项4

<

div

class

=

"

common_checkbox_box clearfix align_center

"

>

<

label

for

=

"

radio14

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

radio14

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项1

</

label

>

<

label

for

=

"

radio15

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

radio15

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项2

</

label

>

<

label

for

=

"

radio16

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

radio16

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项3

</

label

>

<

label

for

=

"

radio17

"

class

=

"

skin-checkbox margin_r_10 hand

"

>

<

input

type

=

"

checkbox

"

value

=

"

0

"

id

=

"

radio17

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项4

</

label

>

</

div

>

其他说明

实现右对齐

右对齐只需要把中对齐中“align_center”改为“align_right”即可

## 13. Form 表单

> 原始路径：`/components3.0/form/form.html`  
> 相对路径：`components3.0/form/form.md`  
> 页面 key：`v-439845d3`  
> JS Chunk：`58.c0f9d172.js`

Form 表单

用于显示、输入或编辑文本或数值。

基本使用

标题:

人员编号:

aaaaaaaaaaaaa

备注:

确定

取消

<

div

class

=

"

form_area

"

>

<

div

class

=

"

one_row

"

>

<

table

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

>

<

tbody

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

标题:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

text18

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

人员编号:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

text19

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

人员编号:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_selectbox_wrap

"

>

<

select

>

<

option

>

aaaaaaaaaaaaa

</

option

>

</

select

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

备注:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox clearfix

"

>

<

textarea

cols

=

"

30

"

rows

=

"

7

"

class

=

"

w100b

"

>

</

textarea

>

</

div

>

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

<

div

class

=

"

align_center

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_emphasize

"

>

确定

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

取消

</

a

>

</

div

>

</

div

>

标题:

人员编号:

aaaaaaaaaaaaa

备注:

标题:

人员编号:

aaaaaaaaaaaaa

备注:

确定

取消

<

div

class

=

"

form_area

"

>

<

div

class

=

"

form_area_content

"

>

<

div

class

=

"

one_row

"

>

<

table

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

>

<

tbody

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

标题:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

text14

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

人员编号:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

text15

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

人员编号:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_selectbox_wrap

"

>

<

select

>

<

option

>

aaaaaaaaaaaaa

</

option

>

</

select

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

备注:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox clearfix

"

>

<

textarea

cols

=

"

30

"

rows

=

"

7

"

class

=

"

w100b

"

>

</

textarea

>

</

div

>

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

<

div

class

=

"

one_row

"

>

<

table

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

>

<

tbody

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10 common_txtbox_dis

"

for

=

"

text

"

>

标题:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox_wrap common_txtbox_wrap_dis

"

>

<

input

type

=

"

text

"

id

=

"

text16

"

disabled

=

"

true

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10 common_txtbox_dis

"

for

=

"

text

"

>

人员编号:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox_wrap common_txtbox_wrap_dis

"

>

<

input

type

=

"

text

"

id

=

"

text17

"

disabled

=

"

true

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

人员编号:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_selectbox_wrap

"

>

<

select

>

<

option

>

aaaaaaaaaaaaa

</

option

>

</

select

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10 common_txtbox_dis

"

for

=

"

text

"

>

备注:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox clearfix

"

>

<

textarea

cols

=

"

30

"

rows

=

"

7

"

disabled

=

"

true

"

class

=

"

padding_5 common_txtbox_wrap_dis w100b

"

>

</

textarea

>

</

div

>

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

</

div

>

<

div

class

=

"

align_center clear

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_emphasize

"

>

确定

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

取消

</

a

>

</

div

>

</

div

>

表单验证

用户名:

真实姓名:

移动电话:

办公电话:

出生日期:

提交

清空

function formSubmit() {
$("#tableForm").validate();
}

function myBtn() {
$("#tableForm").clearform();
}

<

div

class

=

"

form_area align_center

"

>

<

form

id

=

"

tableForm

"

action

=

"

list.htm

"

class

=

"

align_center

"

>

<

table

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

width

=

"

500

"

align

=

"

center

"

>

<

tbody

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

用户名:

</

label

>

</

th

>

<

td

width

=

"

100%

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

id

=

"

name

"

type

=

"

text

"

class

=

"

validate

"

validate

=

"

{type:'string',name:'姓名',notNull:true,minLength:4,maxLength:20,character:'-!@#$%^

&amp;

*()_+'}

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_5

"

for

=

"

text

"

>

真实姓名:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

id

=

"

truename

"

type

=

"

text

"

name

=

"

truename

"

class

=

"

validate

"

validate

=

"

fieldName:'真实姓名',notNullWithoutTrim:true

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_5

"

for

=

"

text

"

>

移动电话:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

id

=

"

phone

"

type

=

"

text

"

name

=

"

telephone

"

class

=

"

validate

"

validate

=

"

name:'移动电话',type:'telephone'

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_5

"

for

=

"

text

"

>

办公电话:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

id

=

"

officenumber

"

type

=

"

text

"

name

=

"

officeNumber

"

class

=

"

validate

"

validate

=

"

name:'办公电话', type:'number', dotNumber:2, integerDigits:4, notNull:true

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_10

"

for

=

"

text

"

>

出生日期:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

id

=

"

mycal2

"

type

=

"

text

"

class

=

"

comp validate

"

comp

=

"

type:'calendar',ifFormat:'%Y-%m-%d %H:%M',showsTime:true

"

validate

=

"

name:'出生日期',notNull:true,type:'5'

"

>

</

div

>

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

form

>

</

div

>

<

div

class

=

"

margin_t_10 align_center

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_emphasize

"

id

=

"

tableSubmit

"

onclick

=

"

formSubmit

(

)

;

"

>

提交

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

id

=

"

myBtn

"

onclick

=

"

myBtn

(

)

;

"

>

清空

</

a

>

</

div

>

<

script

type

=

"

text/javascript

"

>

function

formSubmit

(

)

{

$

(

"#tableForm"

)

.

validate

(

)

;

}

function

myBtn

(

)

{

$

(

"#tableForm"

)

.

clearform

(

)

;

}

</

script

>

用户名:

密码:

个人号码:

办公号码:

提交

清空

function formSubmit1() {
$("#tableForm1").validate();
}

function myBtn1() {
$("#tableForm1").clearform();
}

<

div

class

=

"

form_area align_center

"

>

<

form

id

=

"

tableForm1

"

action

=

"

list.htm

"

class

=

"

align_center

"

>

<

table

border

=

"

0

"

cellspacing

=

"

0

"

cellpadding

=

"

0

"

width

=

"

500

"

align

=

"

center

"

>

<

tbody

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_5

"

for

=

"

text

"

>

用户名:

</

label

>

</

th

>

<

td

width

=

"

50%

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

id

=

"

name

"

type

=

"

text

"

name

=

"

username

"

class

=

"

validate

"

validate

=

"

type:'string',name:'姓名',notNull:true,minLength:4,maxLength:20,character:'-!@#$%^

&amp;

*()_+'

"

>

</

div

>

</

td

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_5 margin_l_10

"

for

=

"

text

"

>

密码:

</

label

>

</

th

>

<

td

width

=

"

50%

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

password

"

name

=

"

password

"

class

=

"

validate

"

validate

=

"

fieldName:'密码',notNullWithoutTrim:true

"

>

</

div

>

</

td

>

</

tr

>

<

tr

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_5

"

for

=

"

text

"

>

个人号码:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

name

=

"

email

"

class

=

"

validate

"

validate

=

"

type:'email',name:'电子邮件'

"

>

</

div

>

</

td

>

<

th

nowrap

=

"

nowrap

"

>

<

label

class

=

"

margin_r_5

"

for

=

"

text

"

>

&nbsp;

办公号码:

</

label

>

</

th

>

<

td

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

name

=

"

telephone

"

class

=

"

validate

"

validate

=

"

name:'电话号码',type:'telephone'

"

>

</

div

>

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

form

>

</

div

>

<

div

class

=

"

align_center margin_t_10

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

id

=

"

tableSubmit

"

onclick

=

"

formSubmit1

(

)

;

"

>

提交

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

id

=

"

myBtn1

"

onclick

=

"

myBtn1

(

)

;

"

>

清空

</

a

>

</

div

>

<

script

type

=

"

text/javascript

"

>

function

formSubmit1

(

)

{

$

(

"#tableForm1"

)

.

validate

(

)

;

}

function

myBtn1

(

)

{

$

(

"#tableForm1"

)

.

clearform

(

)

;

}

</

script

>

## 14. Input 表单专用-输入框

> 原始路径：`/components3.0/form/input.html`  
> 相对路径：`components3.0/form/input.md`  
> 页面 key：`v-ac68a1fe`  
> JS Chunk：`59.e59a3caa.js`

Input 表单专用-输入框

用于显示、输入或编辑文本或数值。

选择关联表单

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

input

type

=

"

text

"

name

=

"

name

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'correlation_form',fun:'testFunction',title:'选择关联表单'

"

>

</

div

>

</

div

>

插入附件

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

input

type

=

"

text

"

name

=

"

name

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'affix',fun:'testFunction',title:'插入附件'

"

>

</

div

>

</

div

>

关联文档

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

input

type

=

"

text

"

name

=

"

name

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'associated_document',fun:'testFunction',title:'关联文档'

"

>

</

div

>

</

div

>

插入图片

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

input

type

=

"

text

"

name

=

"

name

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'insert_pic',fun:'testFunction',title:'插入图片'

"

>

</

div

>

</

div

>

选择关联项目

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

input

type

=

"

text

"

name

=

"

name

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'correlation_project',fun:'testFunction',title:'选择关联项目'

"

>

</

div

>

</

div

>

选择数据交换任务

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

input

type

=

"

text

"

name

=

"

name

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'data_task',fun:'testFunction',title:'选择数据交换任务'

"

>

</

div

>

</

div

>

查询控件交换引擎任务

<

div

class

=

"

code_area

"

>

<

div

class

=

"

example_box

"

>

<

input

type

=

"

text

"

name

=

"

name

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'search',fun:'testFunction',title:'查询控件交换引擎任务'

"

>

</

div

>

</

div

>

## 15. Link 链接

> 原始路径：`/components3.0/form/link.html`  
> 相对路径：`components3.0/form/link.md`  
> 页面 key：`v-51bd00da`  
> JS Chunk：`60.6bfd8656.js`

Link 链接

用于导航至其他页面、窗口或帮助主题，也可用于显示定义、启动命令或设置选项。链接可能是文本或图像，通常用已访问或未访问的系统链接颜色来显示，表明它是可以被单击的。

基本使用

更多

<!--链接示例-->

<

a

href

=

"

javascript:;

"

>

更多

</

a

>

<!-- 链接示例-disable -->

<

a

href

=

"

javascript:;

"

class

=

"

disabled_color

"

>

更多

</

a

>

## 16. Radio 单选

> 原始路径：`/components3.0/form/radio.html`  
> 相对路径：`components3.0/form/radio.md`  
> 页面 key：`v-4ca9375f`  
> JS Chunk：`61.0454ea4f.js`

Radio 单选

基本使用

横排radio

选项1

选项2

选项3

选项4

选项5

选项6

<

div

class

=

"

common_radio_box clearfix

"

>

<

label

for

=

"

radio1

"

class

=

"

skin-radio margin_r_10 hand

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio1

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项1

</

label

>

<

label

for

=

"

radio2

"

class

=

"

skin-radio margin_r_10 hand

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio2

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项2

</

label

>

<

label

for

=

"

radio3

"

class

=

"

skin-radio margin_r_10 hand

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio3

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项3

</

label

>

</

div

>

<

div

class

=

"

common_radio_box clearfix

"

>

<

label

for

=

"

radio4

"

class

=

"

skin-radio margin_r_10 disabled_color

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio4

"

name

=

"

option

"

disabled

=

"

true

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项4

</

label

>

<

label

for

=

"

radio5

"

class

=

"

skin-radio margin_r_10 disabled_color

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio5

"

name

=

"

option

"

disabled

=

"

true

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项5

</

label

>

<

label

for

=

"

radio6

"

class

=

"

skin-radio margin_r_10 disabled_color

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio6

"

name

=

"

option

"

disabled

=

"

true

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项6

</

label

>

</

div

>

<

br

/>

竖排radio

选项1

选项2

选项3

选项4

<

div

class

=

"

common_radio_box clearfix

"

>

<

label

for

=

"

radio7

"

class

=

"

skin-radio margin_t_5 hand display_block

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio7

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项1

</

label

>

<

label

for

=

"

radio8

"

class

=

"

skin-radio margin_t_5 hand display_block

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio8

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项2

</

label

>

<

label

for

=

"

radio9

"

class

=

"

skin-radio margin_t_5 hand display_block

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio9

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项3

</

label

>

<

label

for

=

"

radio10

"

class

=

"

skin-radio margin_t_5 hand display_block

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio10

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项4

</

label

>

</

div

>

横排radio 居中显示

选项1

选项2

选项3

选项4

<

div

class

=

"

common_radio_box clearfix align_center

"

>

<

label

for

=

"

radio11

"

class

=

"

skin-radio margin_r_10 hand

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio11

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项1

</

label

>

<

label

for

=

"

radio12

"

class

=

"

skin-radio margin_r_10 hand

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio12

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项2

</

label

>

<

label

for

=

"

radio13

"

class

=

"

skin-radio margin_r_10 hand

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio13

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项3

</

label

>

<

label

for

=

"

radio14

"

class

=

"

skin-radio margin_r_10 hand

"

>

<

input

type

=

"

radio

"

value

=

"

0

"

id

=

"

radio14

"

name

=

"

option

"

class

=

"

radio_com

"

>

<

label

style

=

"

float

:

left

;

margin-top

:

-2px

"

>

<

i

>

</

i

>

</

label

>

选项4

</

label

>

</

div

>

其他说明

实现右对齐

右对齐只需要把中对齐中“align_center”改为“align_right”即可

中对齐与右对齐radio

最后一个不用margin_r_10

## 17. SearchBox 查询组件

> 原始路径：`/components3.0/form/searchBox.html`  
> 相对路径：`components3.0/form/searchBox.md`  
> 页面 key：`v-759a154f`  
> JS Chunk：`62.79dd908d.js`

SearchBox 查询组件

1、基本使用

<

div

class

=

"

example_box clearfix

"

>

<

ul

class

=

"

common_search

"

>

<

li

id

=

"

inputBorder

"

class

=

"

common_search_input

"

>

<

input

class

=

"

search_input

"

type

=

"

text

"

>

</

li

>

<

li

>

<

a

class

=

"

common_button search_buttonHand

"

href

=

"

javascript:void(0)

"

>

<

em

>

</

em

>

</

a

>

</

li

>

</

ul

>

</

div

>

2、查询组件---页面无元素渲染方式

普通的输入框

var searchobj = $("#searchBox").searchCondition({
size:'L',
top: 10,
left: 500,
searchHandler: function () {

},
conditions: [{
id: 'title',
name: 'title',
type: 'input',
text: $.i18n("mt.list.column.mt_name"),
value: 'title'
},{
id: 'createUser',
name: 'createUser',
type: 'input',
text: $.i18n("common.sender.label"),
value: 'createUser'
},{
id: 'createDepartment',
name: 'createDepartment',
type: 'input',
text: $.i18n("common.fend.department.label"),
value: 'createDepartment'
},{
id: 'date',
name: 'date',
type: 'datemulti',
text: $.i18n("mt.label.meetingtime"),
value: 'date',
dateTime: true
},{
id: 'summary',
name: 'summary',
type: 'select',
text: $.i18n("mt.meetingrecord"),
value: 'summary',
items: [{
text: $.i18n("meeting.new.summary"),
value: '1'
}, {
text: $.i18n("mt.meeting.summary.show"),
value: '2'
}]
},{
id: 'meetingNature',
name: 'meetingNature',
type: 'select',
text: $.i18n("meeting.report.table.meeting.meetingtype"),
value: 'meetingNature',
items: [{
text: $.i18n("meeting.report.enum.meetingtype.normal"),
value: '1'
}, {
text: $.i18n("common.vidoe.meeting.label"),
value: '2'
}]
},{
id: 'category',
name: 'category',
type: 'select',
text: $.i18n("meeting.report.table.meeting.meetingcategory"),
value: 'category',
items: [{
text: $.i18n("meeting.report.enum.meetingcategory.single"),
value: '0'
}, {
text: $.i18n("mt.mtMeeting.type.periodic.meeting"),
value: '1'
}]
},{
id: 'meetingType',
name: 'meetingType',
type: 'input',
text: $.i18n("mt.mtMeeting.meetingCategory"),
value: 'meetingType'
}]
});

<

div

style

=

"

display

:

flex

"

>

<

div

style

=

"

margin-right

:

10px

"

>

普通的输入框

</

div

>

<

div

id

=

"

searchBox

"

>

</

div

>

</

div

>

<

script

>

var

searchobj

=

$

(

"#searchBox"

)

.

searchCondition

(

{

size

:

'L'

,

top

:

10

,

left

:

500

,

searchHandler

:

function

(

)

{

}

,

conditions

:

[

{

id

:

'title'

,

name

:

'title'

,

type

:

'input'

,

text

:

$

.

i18n

(

"mt.list.column.mt_name"

)

,

value

:

'title'

}

,

{

id

:

'createUser'

,

name

:

'createUser'

,

type

:

'input'

,

text

:

$

.

i18n

(

"common.sender.label"

)

,

value

:

'createUser'

}

,

{

id

:

'createDepartment'

,

name

:

'createDepartment'

,

type

:

'input'

,

text

:

$

.

i18n

(

"common.fend.department.label"

)

,

value

:

'createDepartment'

}

,

{

id

:

'date'

,

name

:

'date'

,

type

:

'datemulti'

,

text

:

$

.

i18n

(

"mt.label.meetingtime"

)

,

value

:

'date'

,

dateTime

:

true

}

,

{

id

:

'summary'

,

name

:

'summary'

,

type

:

'select'

,

text

:

$

.

i18n

(

"mt.meetingrecord"

)

,

value

:

'summary'

,

items

:

[

{

text

:

$

.

i18n

(

"meeting.new.summary"

)

,

value

:

'1'

}

,

{

text

:

$

.

i18n

(

"mt.meeting.summary.show"

)

,

value

:

'2'

}

]

}

,

{

id

:

'meetingNature'

,

name

:

'meetingNature'

,

type

:

'select'

,

text

:

$

.

i18n

(

"meeting.report.table.meeting.meetingtype"

)

,

value

:

'meetingNature'

,

items

:

[

{

text

:

$

.

i18n

(

"meeting.report.enum.meetingtype.normal"

)

,

value

:

'1'

}

,

{

text

:

$

.

i18n

(

"common.vidoe.meeting.label"

)

,

value

:

'2'

}

]

}

,

{

id

:

'category'

,

name

:

'category'

,

type

:

'select'

,

text

:

$

.

i18n

(

"meeting.report.table.meeting.meetingcategory"

)

,

value

:

'category'

,

items

:

[

{

text

:

$

.

i18n

(

"meeting.report.enum.meetingcategory.single"

)

,

value

:

'0'

}

,

{

text

:

$

.

i18n

(

"mt.mtMeeting.type.periodic.meeting"

)

,

value

:

'1'

}

]

}

,

{

id

:

'meetingType'

,

name

:

'meetingType'

,

type

:

'input'

,

text

:

$

.

i18n

(

"mt.mtMeeting.meetingCategory"

)

,

value

:

'meetingType'

}

]

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

size

搜索框的大小（9.0 新增）

String

L,M

M

top

离界面顶部的距离

number

自定义

0

right

离界面右边的距离

number

自定义

0

left

离界面的左边的距离

number

自定义

0

searchHandler

点击查询按钮触发的函数

function

自定义

onchange

条件变化时的回调函数

function

自定义

conditions

查询输入条件数组

Array

自定义

[]

conditions的参数

id【字段id】

Array

自定义

Json

name

String

自定义

type 【查询输入类型】

datemulti/select/selectPeople/input/custom/customPanel

input

text【字段名称】

String

自定义

validate【输入框不验证特殊】

String

自定义

value

String

自定义

maxLength

String

自定义

ifFormat【日期格式】

String

自定义

%Y-%m-%d %H:%M

conditionOptions【是否需要查询模式】

boolean

false/true

false

方法列表

方法名

说明

参数 1

参数 2

例子

searchobj.g.getReturnValue

获取查询返回的相应信息,

需要searchObj.g来调用

searchObj.g.getReturnValue();

返回格式

{ 'type': '类型', 'condition': '查询条件', 'value': '查询值',conditionVal:'查询模式'}

searchobj.g.destroySearch

销毁当前组件,比如界面上需要删除当前组件重新渲染就需要通过这个方法进行销毁

searchobj.g.hideItem

隐藏select下拉项 参数1：选项的id 参数2：是否初始化为默认项

searchobj.g.showItem

显示select下拉项，参数为：选项的id

searchobj.g.setCondition

设置条件默认值

searchobj.g.setCondition('datetime', '2012-10-25 17:49', '2012-10-25 17:49');

searchobj.g.clearCondition

清空条件值

## 18. upload 上传组件

> 原始路径：`/components3.0/form/upload.html`  
> 相对路径：`components3.0/form/upload.md`  
> 页面 key：`v-056fc673`  
> JS Chunk：`63.122bbfa5.js`

upload 上传组件

上传

图片上传的附件.jpg

图片.jpg

<

div

class

=

"

file_box

"

>

<

div

class

=

"

file_unload clearfix

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_icon file_click

"

>

<

em

class

=

"

ico16 affix_16

"

>

</

em

>

上传

<

input

style

=

"

border

:

1px #f00 solid

"

type

=

"

file

"

>

</

a

>

</

div

>

<

ul

class

=

"

file_select padding_10 border_all clearfix

"

>

<

li

>

<

span

title

=

"

图片上传的附件.jpg

"

>

图片上传的附件.jpg

</

span

>

<

em

class

=

"

ico16 affix_del_16

"

>

</

em

>

</

li

>

<

li

class

=

"

margin_l_10

"

>

<

span

title

=

"

图片

"

>

图片.jpg

</

span

>

<

em

class

=

"

ico16 affix_del_16

"

>

</

em

>

</

li

>

</

ul

>

</

div

>

## 19. Fieldset 分组框

> 原始路径：`/components3.0/layout/fieldset.html`  
> 相对路径：`components3.0/layout/fieldset.md`  
> 页面 key：`v-1666095a`  
> JS Chunk：`64.e83bbf0c.js`

Fieldset 分组框

是围绕在一组相关控件周围的带标签的矩形边框。它提供了一种通过视觉展示控件关系的方法。

基本使用

分组框

<

fieldset

>

<

legend

>

分组框

</

legend

>

</

fieldset

>

简要说明

界面上将相关数据分类的一种方式，一般用于信息较杂，有一定相关性时的信息聚合或分类

交互细则

1、每个分组框的顶部边缘处都有一个内置的标题，通常描述了框的内容

2、对齐方式：采用左对齐方式

3、读取方式：采用先左—中—右读取方式

4、分组框不出现滚动条

## 20. Layout 拖拽布局

> 原始路径：`/components3.0/layout/layoutDrag.html`  
> 相对路径：`components3.0/layout/layoutDrag.md`  
> 页面 key：`v-1438bd53`  
> JS Chunk：`65.3d1e59f9.js`

Layout 拖拽布局

基本使用

上边区域

右边区域

中间区域

左边区域

下边区域

var layout;
$(document).ready(function () {
layout = $('#layout').layout();
});

<

div

style

=

"

height

:

380px

;

"

>

<

div

id

=

'

layout

'

class

=

"

comp

"

comp

=

"

type:'layout'

"

>

<

div

class

=

"

layout_north

"

layout

=

"

height:100,maxHeight:100,minHeight:30

"

>

<!--code区域-->

上边区域

</

div

>

<

div

class

=

"

layout_east

"

layout

=

"

width:200,minWidth:50,maxWidth:200

"

>

<!--code区域-->

右边区域

</

div

>

<

div

class

=

"

layout_center

"

layout

=

"

border:false

"

>

<!--code区域-->

中间区域

</

div

>

<

div

class

=

"

layout_west

"

layout

=

"

width:200,minWidth:50,sprit:false,maxWidth:300

"

>

<!--code区域-->

左边区域

</

div

>

<

div

class

=

"

layout_south

"

layout

=

"

height:50,maxHeight:300,minHeight:30

"

>

<!--code区域-->

下边区域

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

layout

;

$

(

document

)

.

ready

(

function

(

)

{

layout

=

$

(

'#layout'

)

.

layout

(

)

;

}

)

;

</

script

>

说明

1.设置div的class为comp组件，同时设置comp属性type为layout，框架会自动将其作布局处理

2.class必须为layout_north的布局div，用layout属性进行宽高设置和最大、最小宽度/高度设置

3.class必须为layout_east的布局div，用layout属性进行宽高设置和最大、最小宽度/高度设置

4.class必须为layout_center的布局div，用layout属性进行宽高设置和最大、最小宽度/高度设置，内部还可进行布局嵌套定义

5.class必须为layout_west的布局div，用layout属性进行宽高设置和最大、最小宽度/高度设置

6.class必须为layout_south的布局div，用layout属性进行宽高设置和最大、最小宽度/高度设置

通过var layout = $("#layout").layout()函数获取Layout对象，用于动态调整布局宽度、高度，如layout.setEast(300);

属性

类型

描述

sprit

boolean

是否显示中间拖动条

border

boolean

是否显示边线

spiretBar

json

//上边区域
spiretBar: {
show: true,
handlerB: function () {
layout.setNorth(98);
},
handlerT: function () {
layout.setNorth(0);
}
}


//下边区域
spiretBar: {
show: true,
handlerB: function () {
layout.setSouth(0);
},
handlerT: function () {
layout.setSouth(48);
}
}

//右边区域
spiretBar: {
show: true,
handlerL: function () {
layout.setEast(198);
},
handlerR: function () {
layout.setEast(0);
}
}


//左边区域
spiretBar: {
show: true,
handlerL: function () {
layout.setWest(0);
},
handlerR: function () {
layout.setWest(198);
}
}

方法

名称

描述

setNorth(int)

//设置,北边区域高度:
//var layout = $("#layout").layout();
layout.setNorth(40);

setSouth(int)

//设置,南边区域高度:
//var layout = $("#layout").layout();
layout.setSouth(40);

setWest(int)

//设置,西边区域宽度:
//var layout = $("#layout").layout();
layout.setWest(40);

setEast(int)

//设置，右边区域宽度:
//var layout = $("#layout").layout();
layout.setEast(40);

setNorthSp(bool);

//设置，上边区域中间拖动条:
//var layout = $("#layout").layout();
layout.setNorthSp(false);

setSouthSp(bool);

//设置，下边区域中间拖动条:
//var layout = $("#layout").layout();
layout.setSouthSp(false);

setWestSp(bool);

//设置，左边区域中间拖动条:
//var layout = $("#layout").layout();
layout.setWestSp(false);

setEastSp(bool);

//设置，右边区域中间拖动条:
//var layout = $("#layout").layout();
layout.setEastSp(false);

## 21. StaticLayout 静态布局

> 原始路径：`/components3.0/layout/staticLayout.html`  
> 相对路径：`components3.0/layout/staticLayout.md`  
> 页面 key：`v-51f8545a`  
> JS Chunk：`66.968b1942.js`

StaticLayout 静态布局

修改“头部”的高度：需要修改 .stadic_head_height 中的

height:30px

和 .stadic_body_top_bottom 中的

top:30px

。

修改“尾部”的高度：需要修改 .stadic_footer_height 中的

height:30px

和 .stadic_body_top_bottom 中的

bottom:30px

。

修改“左部”的宽度：需要修改 .stadic_right .stadic_content 中的

margin-left:270px

和 .stadic_left 中的

width:265px

。

“中间区域”宽度为自适应。

基本使用

上下

我在上边区域

我在下边区域

Tip:

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

3. style标签中的30px，为上部区域高度

<

div

class

=

"

stadic_layout

"

style

=

"

height

:

140px

;

"

>

<

div

class

=

"

stadic_layout_head stadic_head_height

"

>

我在上边区域

</

div

>

<

div

class

=

"

stadic_layout_body stadic_body_top_bottom border_t

"

style

=

"

bottom

:

0px

;

"

>

我在下边区域

<

br

/>

<

br

/>

<

span

class

=

"

color_red

"

>

Tip:

<

br

/>

<

span

class

=

"

font_bold

"

>

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

</

span

>

<

br

/>

<

span

class

=

"

font_bold

"

>

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

</

span

>

<

br

/>

3. style标签中的30px，为上部区域高度

</

span

>

</

div

>

</

div

>

上中下

我在上边区域

我在中间边区域

Tip:

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

3. style标签中的30px，为上部区域高度

4. style标签中的20px，为下部区域高度

我在下边区域

<

div

class

=

"

stadic_layout

"

style

=

"

height

:

140px

;

"

>

<

div

class

=

"

stadic_layout_head stadic_head_height

"

>

我在上边区域

</

div

>

<

div

class

=

"

stadic_layout_body stadic_body_top_bottom border_tb

"

>

我在中间边区域

<

br

/>

<

span

class

=

"

color_red

"

>

Tip:

<

br

/>

<

span

class

=

"

font_bold

"

>

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

</

span

>

<

br

/>

<

span

class

=

"

font_bold

"

>

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

</

span

>

<

br

/>

3. style标签中的30px，为上部区域高度

<

br

/>

4. style标签中的20px，为下部区域高度

</

span

>

<

br

/>

</

div

>

<

div

class

=

"

stadic_layout_footer stadic_footer_height

"

>

我在下边区域

</

div

>

</

div

>

左右

我在中间区域

Tip:

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

3. style标签中的270px、265px，为左部区域高度

我在左边区域

.stadic_right {
float: right;
width: 100%;
height: 100%;
position: absolute;
z-index: 100;
overflow: auto;
}

.stadic_right .stadic_content {
margin-left: 270px;
height: 100%;
}

.stadic_left {
width: 265px;
float: left;
position: absolute;
height: 100%;
z-index: 300;
}

<

div

class

=

"

stadic_layout

"

style

=

"

height

:

140px

;

"

>

<

div

class

=

"

stadic_right

"

>

<

div

class

=

"

stadic_content

"

>

我在中间区域

<

br

/>

<

span

class

=

"

color_red

"

>

Tip:

<

br

/>

<

span

class

=

"

font_bold

"

>

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

</

span

>

<

br

/>

<

span

class

=

"

font_bold

"

>

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

</

span

>

<

br

/>

3. style标签中的270px、265px，为左部区域高度

<

br

/>

</

span

>

</

div

>

</

div

>

<

div

class

=

"

stadic_left border_r

"

>

我在左边区域

</

div

>

</

div

>

<

style

>

.stadic_right

{

float

:

right

;

width

:

100%

;

height

:

100%

;

position

:

absolute

;

z-index

:

100

;

overflow

:

auto

;

}

.stadic_right .stadic_content

{

margin-left

:

270px

;

height

:

100%

;

}

.stadic_left

{

width

:

265px

;

float

:

left

;

position

:

absolute

;

height

:

100%

;

z-index

:

300

;

}

</

style

>

上下左右

我在上边区域

我在中间区域

Tip:

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

3. style标签中的270px、265px，为左部区域高度

4. style标签中的30px，为上部区域高度

5. style标签中的20px，为下部区域高度

我在左边区域

我在下边区域

.stadic_head_height {
height: 30px;
}

.stadic_body_top_bottom {
bottom: 30px;
top: 30px;
}

.stadic_footer_height {
height: 30px;
}

.stadic_right {
float: right;
width: 100%;
height: 100%;
position: absolute;
z-index: 100;
}

.stadic_right .stadic_content {
overflow: auto;
margin-left: 270px;
height: 100%;
}

.stadic_left {
float: left;
width: 265px;
height: 100%;
position: absolute;
z-index: 300;
}

<

div

class

=

"

stadic_layout

"

style

=

"

height

:

140px

;

"

>

<

div

class

=

"

stadic_layout_head stadic_head_height border_b

"

>

我在上边区域

</

div

>

<

div

class

=

"

stadic_layout_body stadic_body_top_bottom clearfix border_b

"

>

<

div

class

=

"

stadic_right

"

>

<

div

class

=

"

stadic_content

"

>

我在中间区域

<

br

/>

<

span

class

=

"

color_red

"

>

Tip:

<

br

/>

<

span

class

=

"

font_bold

"

>

1. 禁止在“code区域”外添加元素，否则会导致页面显示错位！！！

</

span

>

<

br

/>

<

span

class

=

"

font_bold

"

>

2. 注意添加，html和body元素上的class，和style标签的内容，否则会导致出现多余滚动条！！！

</

span

>

<

br

/>

3. style标签中的270px、265px，为左部区域高度

<

br

/>

4. style标签中的30px，为上部区域高度

<

br

/>

5. style标签中的20px，为下部区域高度

</

span

>

</

div

>

</

div

>

<

div

class

=

"

stadic_left border_r

"

>

我在左边区域

</

div

>

</

div

>

<

div

class

=

"

stadic_layout_footer stadic_footer_height

"

>

我在下边区域

</

div

>

</

div

>

<

style

>

.stadic_head_height

{

height

:

30px

;

}

.stadic_body_top_bottom

{

bottom

:

30px

;

top

:

30px

;

}

.stadic_footer_height

{

height

:

30px

;

}

.stadic_right

{

float

:

right

;

width

:

100%

;

height

:

100%

;

position

:

absolute

;

z-index

:

100

;

}

.stadic_right .stadic_content

{

overflow

:

auto

;

margin-left

:

270px

;

height

:

100%

;

}

.stadic_left

{

float

:

left

;

width

:

265px

;

height

:

100%

;

position

:

absolute

;

z-index

:

300

;

}

</

style

>

其他说明

只能在

所在的div内添加内容

其他位置添加内容，会导致页面变形。

一般都直接应用在<body>里面

<body>中不再添加其他内容，否则会导致页面变形。

## 22. Tab 页签

> 原始路径：`/components3.0/layout/tab.html`  
> 相对路径：`components3.0/layout/tab.md`  
> 页面 key：`v-606406df`  
> JS Chunk：`67.fd484d86.js`

Tab 页签

基本使用

div1

div2

div3

div4

1

2

3

4

<

div

id

=

"

tabs2

"

class

=

"

comp

"

comp

=

"

type:'tab',width:600,height:200

"

>

<

div

id

=

"

tabs2_head

"

class

=

"

common_tabs size_L clearfix

"

>

<

ul

class

=

"

left

"

>

<

li

class

=

"

current

"

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab1_div

"

>

<

span

>

div1

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab2_div

"

>

<

span

>

div2

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab3_div

"

>

<

span

>

div3

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab4_div

"

>

<

span

>

div4

</

span

>

</

a

>

</

li

>

</

ul

>

</

div

>

<

div

id

=

"

tabs2_body

"

class

=

"

common_tabs_body

"

>

<

div

id

=

"

tab1_div

"

>

1

</

div

>

<

div

id

=

"

tab2_div

"

class

=

"

hidden

"

>

2

</

div

>

<

div

id

=

"

tab3_div

"

class

=

"

hidden

"

>

3

</

div

>

<

div

id

=

"

tab4_div

"

class

=

"

hidden

"

>

4

</

div

>

</

div

>

</

div

>

历史版本(已废弃)

div1

div2

div3

div4

1

2

3

4

<

div

id

=

"

tabs22

"

class

=

"

comp

"

comp

=

"

type:'tab',width:600,height:200

"

>

<

div

id

=

"

tabs22_head

"

class

=

"

common_tabs clearfix

"

>

<

ul

class

=

"

left

"

>

<

li

class

=

"

current

"

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab21_div

"

>

<

span

>

div1

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab22_div

"

>

<

span

>

div2

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab23_div

"

>

<

span

>

div3

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab24_div

"

>

<

span

>

div4

</

span

>

</

a

>

</

li

>

</

ul

>

</

div

>

<

div

id

=

"

tabs22_body

"

class

=

"

common_tabs_body

"

>

<

div

id

=

"

tab21_div

"

>

1

</

div

>

<

div

id

=

"

tab22_div

"

class

=

"

hidden

"

>

2

</

div

>

<

div

id

=

"

tab23_div

"

class

=

"

hidden

"

>

3

</

div

>

<

div

id

=

"

tab24_div

"

class

=

"

hidden

"

>

4

</

div

>

</

div

>

</

div

>

属性

类型

描述

id

string

必须

width

number

宽度

height

number

高度

parentId

string

获取设置tab的宽高

showTabIndex

number

设置第index的tab为默认显示

refreashTab

boolean

是否刷新iframe

tabsEquallyWidth

boolean

页签平分显示

方法

描述

disabled(id)

禁用某个页签

enable(id)

可用某个页签

setCurrent(id)

设置某个页签可用

setMouseOver(id)

设置鼠标滑过触发选中效果

setClick(id)

设置鼠标点击触发选中效果

resetSize()

重新整体宽高

## 23. Breadcrumb 面包屑

> 原始路径：`/components3.0/navigation/breadcrumb.html`  
> 相对路径：`components3.0/navigation/breadcrumb.md`  
> 页面 key：`v-9e54899a`  
> JS Chunk：`68.ad1d1705.js`

Breadcrumb 面包屑

反映当前页面在软件层次结构中的位置，显示所有父级页面的链接，向上追溯到主页面为止， 帮助用户轻松浏览软件层次结构。

基本使用

当前位置:

文档中心

-

业务培训

当前位置:

文档中心

-

业务培训

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

common_crumbs

"

>

<

span

class

=

"

margin_r_10

"

>

当前位置:

</

span

>

<

a

href

=

"

javascript:;

"

>

文档中心

</

a

>

<

span

class

=

"

common_crumbs_next margin_lr_5

"

>

-

</

span

>

<

a

href

=

"

javascript:;

"

class

=

"

last

"

>

业务培训

</

a

>

</

div

>

<

div

class

=

"

common_crumbs_disable

"

>

<

span

class

=

"

margin_r_10

"

>

当前位置:

</

span

>

<

a

href

=

"

javascript:;

"

>

文档中心

</

a

>

<

span

class

=

"

margin_lr_5

"

>

-

</

span

>

<

a

href

=

"

javascript:;

"

>

业务培训

</

a

>

</

div

>

</

div

>

简要说明

1、反映当前页面在软件层次结构中的位置，显示所有父级页面的链接，向上追溯到主页面为止， 帮助用户轻松浏览软件层次结构。

2、主要用于二级页面，方便跳转到之前的页面

3、总体上是作为主导航的补充

交互细则

1、面包屑每个文本链接都是指向一个页面，每个文本均可点击链接到相关页面（产品未做到），文本最后一项（当前用户位置）是可显示也可不显示的，且不可点击。因为当用户已经处于这个页面时，就没有理由给面包屑导航中的当前页面加上跳转链接。

2、面包屑文字前均有图标

3、使用分隔符：使用大于号“>”来作为链接与链接之间的分隔符

4、面包屑设计占地不能太大，不能用花哨的字体或明亮的颜色，分散用户注意力

新老框架的区别

新框架:<div class="comp" comp="type:'breadcrumb',code:资源code"></div>;

老框架:<script>showCtpLocation(code,{html:拼接的字符串}); </script>;

## 24. 返回顶部按钮

> 原始路径：`/components3.0/navigation/gototop.html`  
> 相对路径：`components3.0/navigation/gototop.md`  
> 页面 key：`v-17f63751`  
> JS Chunk：`45.6df20ca2.js`

返回顶部按钮

基本使用

GoTo_Top({ showHeight: 100, top: 500, left: 200, sTitle:"回到顶部" });

<

script

>

GoTo_Top

(

{

showHeight

:

100

,

top

:

500

,

left

:

200

,

sTitle

:

"回到顶部"

}

)

;

</

script

>

属性

类型

描述

obj

jquery对象

出现滚动条的jquery对象[默认：$(window)]

btnClass

string

按钮的class名称[默认："GoTo_Top"]

showHeight

number

滚动大于多少后，出现出现按钮[默认：obj的高度]

marginLeft

number

按钮相对左边的距离[默认：798]

sTitle

string

显示按钮的提示信息

nGoToHeight

number

指定回到哪个位置（默认是顶部）

## 25. MenuSimple 简易菜单

> 原始路径：`/components3.0/navigation/menuSimple.html`  
> 相对路径：`components3.0/navigation/menuSimple.md`  
> 页面 key：`v-3d38d2f3`  
> JS Chunk：`69.d646e733.js`

MenuSimple 简易菜单

基本使用

示例1

$

.

menuSimple

(

{

left

:

20

,

top

:

20

,

mRow

:

true

,

//换行

data

:

[

{

name

:

"示例1示例1示例1示例1示例1示例1示例1示例1"

,

customAttr

:

"qq='nodePerm'"

,

className

:

"toback_16"

,

disabled

:

true

,

handle

:

function

(

json

)

{

alert

(

json

.

name

)

;

}

,

{

type

:

"line"

////显示分割线

}

,

{

name

:

"示例1"

,

handle

:

function

(

json

)

{

alert

(

json

.

name

)

;

}

]

}

)

;

示例2

菜单

$(function () {
$("#qqq2").menuSimple({
data: [{
name: "示例2",
customAttr: "class='nodePerm'",
className: "toback_16",
handle: function (json) {
alert(json.id);
}
}, {
type: "line"
}, {
name: "示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2",
handle: function (json) {
alert(json.id);
}
}, {
name: "示例2",
handle: function (json) {
alert(json.obj);
}
}]
});
// $("#qqq2").trigger("click");
});

<

a

id

=

"

qqq2

"

title

=

"

示例2

"

>

菜单

</

a

>

<

script

type

=

"

text/javascript

"

>

$

(

function

(

)

{

$

(

"#qqq2"

)

.

menuSimple

(

{

data

:

[

{

name

:

"示例2"

,

customAttr

:

"class='nodePerm'"

,

className

:

"toback_16"

,

handle

:

function

(

json

)

{

alert

(

json

.

id

)

;

}

,

{

type

:

"line"

}

,

{

name

:

"示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2示例2"

,

handle

:

function

(

json

)

{

alert

(

json

.

id

)

;

}

,

{

name

:

"示例2"

,

handle

:

function

(

json

)

{

alert

(

json

.

obj

)

;

}

]

}

)

;

// $("#qqq2").trigger("click");

}

)

;

</

script

>

属性

类型

描述

id

string

event

string,jquery事件

默认['click']

data

[{
id:"ID",
className:"文字前面16*16图标class",
name:"显示的文本"，
disabled:true,/*禁用*/
handle: function (json) {
alert(json.obj); /*选项的jquery对象*/
alert(json.id); /*选项的id*/
alert(json.name); /*选项的文本*/
}},{
type: "line" /*添加分割线*/

}]

数据

width

number

默认[150]

top

number

绝对定位-上，仅"示例1"使用

left

number

绝对定位-左，仅"示例1"使用

offsetTop

number

绝对定位-相对上调整上，仅"示例2"使用

offsetLeft

number

绝对定位-相对左调整左，仅"示例2"使用

mRow

bool

默认[false],每个选项的内容是否多行显示

direction

string

绑定对象

BL

BR

默认['BL']，下左对其菜单的对其位置

## 26. ProgressBar 进度条

> 原始路径：`/components3.0/navigation/progressBar.html`  
> 相对路径：`components3.0/navigation/progressBar.md`  
> 页面 key：`v-e4a102ae`  
> JS Chunk：`70.7b9e8ae1.js`

ProgressBar 进度条

用于查看长时间操作的进度, 为需要 2 秒甚至更长时间的操作提供某种类型的进度反馈信息，可显示大致的完成百分比，也可以显示操作正在进行中。

基本使用

旋转进度条

$(document).ready(function(){
$('#proce').click(function(){
var proce = $.progressBar();
});
});

<

a

id

=

"

proce

"

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

旋转进度条

</

a

>

<

script

type

=

"

text/javascript

"

>

$

(

document

)

.

ready

(

function

(

)

{

$

(

'#proce'

)

.

click

(

function

(

)

{

var

proce

=

$

.

progressBar

(

)

;

}

)

;

}

)

;

</

script

>

有提示信息

$(document).ready(function(){
$('#proce_text').click(function(){
var proce = $.progressBar({
text: "正在更新RSS信息...."
});
});
});

<

a

id

=

"

proce_text

"

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

有提示信息

</

a

>

<

script

type

=

"

text/javascript

"

>

$

(

document

)

.

ready

(

function

(

)

{

$

(

'#proce_text'

)

.

click

(

function

(

)

{

var

proce

=

$

.

progressBar

(

{

text

:

"正在更新RSS信息...."

}

)

;

}

)

;

}

)

;

</

script

>

说明

A8

平台调用：

//显示遮罩

showMask

(

)

//隐藏遮罩

hideMask

(

)

// 关闭进度条方法

proce

.

close

(

)

;

:::

## 27. StepTab 向导菜单

> 原始路径：`/components3.0/navigation/stepTab.html`  
> 相对路径：`components3.0/navigation/stepTab.md`  
> 页面 key：`v-16ef3b63`  
> JS Chunk：`71.69486bc5.js`

StepTab 向导菜单

基本使用

第一步

基础操作

操作设置

查询统计设置

应用绑定

触发设置

<

div

class

=

"

step_menu

"

>

<

ul

>

<

li

class

=

"

first_step current

"

>

<

b

>

</

b

>

<

span

>

基础操作

</

span

>

</

li

>

<

li

>

<

b

>

</

b

>

<

span

>

操作设置

</

span

>

</

li

>

<

li

>

<

b

>

</

b

>

<

span

>

查询统计设置

</

span

>

</

li

>

<

li

>

<

b

>

</

b

>

<

span

>

应用绑定

</

span

>

</

li

>

<

li

class

=

"

last_step

"

>

<

span

>

触发设置

</

span

>

</

li

>

</

ul

>

</

div

>

中间步骤

基础操作

操作设置

查询统计设置

应用绑定

触发设置

<

div

class

=

"

step_menu

"

>

<

ul

>

<

li

class

=

"

first_step step_complate

"

>

<

b

>

</

b

>

<

span

>

基础操作

</

span

>

</

li

>

<

li

class

=

"

step_complate_last

"

>

<

b

>

</

b

>

<

span

>

操作设置

</

span

>

</

li

>

<

li

class

=

"

current

"

>

<

b

>

</

b

>

<

span

>

查询统计设置

</

span

>

</

li

>

<

li

>

<

b

>

</

b

>

<

span

>

应用绑定

</

span

>

</

li

>

<

li

class

=

"

last_step

"

>

<

span

>

触发设置

</

span

>

</

li

>

</

ul

>

</

div

>

最后一步

基础操作

操作设置

查询统计设置

应用绑定

触发设置

<

div

class

=

"

step_menu

"

>

<

ul

>

<

li

class

=

"

first_step step_complate

"

>

<

b

>

</

b

>

<

span

>

基础操作

</

span

>

</

li

>

<

li

class

=

"

step_complate

"

>

<

b

>

</

b

>

<

span

>

操作设置

</

span

>

</

li

>

<

li

class

=

"

step_complate

"

>

<

b

>

</

b

>

<

span

>

查询统计设置

</

span

>

</

li

>

<

li

class

=

"

step_complate_last

"

>

<

b

>

</

b

>

<

span

>

应用绑定

</

span

>

</

li

>

<

li

class

=

"

last_step current

"

>

<

span

>

触发设置

</

span

>

</

li

>

</

ul

>

</

div

>

完成后选择步骤

基础操作

操作设置

查询统计设置

应用绑定

触发设置

<

div

class

=

"

step_menu

"

>

<

ul

>

<

li

class

=

"

first_step step_complate

"

>

<

b

>

</

b

>

<

span

>

基础操作

</

span

>

</

li

>

<

li

class

=

"

step_complate_last

"

>

<

b

>

</

b

>

<

span

>

操作设置

</

span

>

</

li

>

<

li

class

=

"

current

"

>

<

b

>

</

b

>

<

span

>

查询统计设置

</

span

>

</

li

>

<

li

class

=

"

step_complate

"

>

<

b

>

</

b

>

<

span

>

应用绑定

</

span

>

</

li

>

<

li

class

=

"

last_step step_complate

"

>

<

span

>

触发设置

</

span

>

</

li

>

</

ul

>

</

div

>

## 28. Dialog 弹出框

> 原始路径：`/components3.0/notice/dialog.html`  
> 相对路径：`components3.0/notice/dialog.md`  
> 页面 key：`v-f89a215a`  
> JS Chunk：`72.ab2b70cd.js`

Dialog 弹出框

基本使用

html

html1

function showMessageBox0() {
var dialog = $.dialog({
targetWindow:window.parent,
id: 'html',
htmlId: 'htmlId',
height:100,
title: 'html',
bottomHTML:"<label for='Checkbox1' class='margin_r_10 hand'>"+
"<input type='checkbox' value='0' id='Checkbox1' name='option' class='radio_com'>选项1"+
"</label>",
overflow:'hidden',
buttons: [{
//id: 'ok',
text: "button1",
handler: function () {
//dialog.enabledBtn('cancel');
dialog.close({isFormItem:true});
}
}, {
//id: 'cancel',
//disabled: true,
//hide:true,
text: "button2",
handler: function () {
//dialog.disabledBtn('ok');
dialog.close();
}
}]
});
dialog.setTitle('弹窗框的自定义标题html');
}
function showMessageBox1() {
var dialog = $.dialog({
targetWindow:window.parent,
id: 'html1',
htmlId: 'htmlId1',
height:100,
title: 'html',
bottomHTML:"<label for='Checkbox1' class='margin_r_10 hand'>"+
"<input type='checkbox' value='0' id='Checkbox1' name='option' class='radio_com'>选项1"+
"</label>",
overflow:'hidden',
buttons: [{
//id: 'ok',
text: "button1",
handler: function () {
//dialog.enabledBtn('cancel');
dialog.close({isFormItem:true});
}
}, {
//id: 'cancel',
//disabled: true,
//hide:true,
text: "button2",
handler: function () {
//dialog.disabledBtn('ok');
dialog.close();
}
}]
});
dialog.setTitle('弹窗框的自定义标题html1');
dialog.endLoading()
}

<

a

href

=

"

javascript:showMessageBox0()

"

class

=

"

common_button common_button_gray

"

>

html

</

a

>

<

a

href

=

"

javascript:showMessageBox1()

"

class

=

"

common_button common_button_gray

"

>

html1

</

a

>

<

script

type

=

"

text/javascript

"

>

function

showMessageBox0

(

)

{

var

dialog

=

$

.

dialog

(

{

targetWindow

:

window

.

parent

,

id

:

'html'

,

htmlId

:

'htmlId'

,

height

:

100

,

title

:

'html'

,

bottomHTML

:

"<label for='Checkbox1' class='margin_r_10 hand'>"

+

"<input type='checkbox' value='0' id='Checkbox1' name='option' class='radio_com'>选项1"

+

"</label>"

,

overflow

:

'hidden'

,

buttons

:

[

{

//id: 'ok',

text

:

"button1"

,

handler

:

function

(

)

{

//dialog.enabledBtn('cancel');

dialog

.

close

(

{

isFormItem

:

true

}

)

;

}

,

{

//id: 'cancel',

//disabled: true,

//hide:true,

text

:

"button2"

,

handler

:

function

(

)

{

//dialog.disabledBtn('ok');

dialog

.

close

(

)

;

}

]

}

)

;

dialog

.

setTitle

(

'弹窗框的自定义标题html'

)

;

}

function

showMessageBox1

(

)

{

var

dialog

=

$

.

dialog

(

{

targetWindow

:

window

.

parent

,

id

:

'html1'

,

htmlId

:

'htmlId1'

,

height

:

100

,

title

:

'html'

,

bottomHTML

:

"<label for='Checkbox1' class='margin_r_10 hand'>"

+

"<input type='checkbox' value='0' id='Checkbox1' name='option' class='radio_com'>选项1"

+

"</label>"

,

overflow

:

'hidden'

,

buttons

:

[

{

//id: 'ok',

text

:

"button1"

,

handler

:

function

(

)

{

//dialog.enabledBtn('cancel');

dialog

.

close

(

{

isFormItem

:

true

}

)

;

}

,

{

//id: 'cancel',

//disabled: true,

//hide:true,

text

:

"button2"

,

handler

:

function

(

)

{

//dialog.disabledBtn('ok');

dialog

.

close

(

)

;

}

]

}

)

;

dialog

.

setTitle

(

'弹窗框的自定义标题html1'

)

;

dialog

.

endLoading

(

)

}

</

script

>

打开url

function showMessageBox1() {
dialog = $.dialog({
id: 'url',
url: 'message.html',
width: 3000,
height: 600,
title: 'url',
checkMax:true,
transParams:{
name:"陈宁宁"
},
closeParam:{
'show':true,
autoClose:false,
handler:function(){
//var d = dialog.getClose();
alert('关闭弹窗')
}
},
buttons: [
{
text: "button1",
handler: function () {
dialog.startLoading()
}
},
{
text: "button2",
handler: function () {
dialog.endLoading()
}
}
]
});
}

<

a

href

=

"

javascript:showMessageBox1()

"

class

=

"

common_button common_button_gray

"

>

打开url

</

a

>

<

script

type

=

"

text/javascript

"

>

function

showMessageBox1

(

)

{

dialog

=

$

.

dialog

(

{

id

:

'url'

,

url

:

'message.html'

,

width

:

3000

,

height

:

600

,

title

:

'url'

,

checkMax

:

true

,

transParams

:

{

name

:

"陈宁宁"

}

,

closeParam

:

{

'show'

:

true

,

autoClose

:

false

,

handler

:

function

(

)

{

//var d = dialog.getClose();

alert

(

'关闭弹窗'

)

}

,

buttons

:

[

{

text

:

"button1"

,

handler

:

function

(

)

{

dialog

.

startLoading

(

)

}

,

{

text

:

"button2"

,

handler

:

function

(

)

{

dialog

.

endLoading

(

)

}

]

}

)

;

}

</

script

>

属性

类型

描述

title

窗口名称

html

内容显示传入的html代码

url

内容显示iframe，src为传入的ur

width

内容区宽度

height

内容区高度

buttons

数组:按钮及事件

buttons:[{

text: "确认",

isEmphasize: true, //蓝色按钮

handler: function(){ alert('handler') }

},{

text: "取消",

handler: function(){ alert('handler') }

}]

isDrag

是否允许拖拽

type

是'dialog'还是'panel',默认为'dialog'

htmlId

显示改id内的内容

targetWindow

跨iframe显示[window.parent]注：window必须存在

closeParam

关闭按钮参数[show：是否显示关闭按钮,参数true or false],

[handler:点击关闭后调用的方法],默认值:{'show':true,handler:function(){}}

transParams

当url不为空时即弹出窗口中加载的是另外的窗口时，可以通过transParams传参数到弹出窗口中，在子页面中通过window.parentDialogObj[id]获取窗口对象，然后调用getTransParams()来获取传过来的参数

checkMax

检查弹出窗口是否超过浏览器可视区域

notcopyreturnvalue

是否不对returnvalue进行深拷贝，默认值：false，即默认会进行深拷贝

方法

描述

close()

关闭窗口:dialog.close();

getReturnValue()

获取iframe页面中OK()方法返回值:dialog.getReturnValue();

disabledBtn('按钮id')

设置按钮不可用:dialog.disabledBtn('按钮id')

var dialog = $.dialog({
id: 'html',
htmlId: 'htmlId',
title: 'html',
buttons: [{
id: 'ok',
text: "button1",
handler: function () {
//dialog.enabledBtn('cancel');
dialog.close();
}
}, {
id: 'cancel',
//disabled: true,//按钮默认是否可用
//hide:true,//按钮默认是否可见
text: "button2",
handler: function () {
//dialog.disabledBtn('ok');
dialog.close();
}
}]
});

enabledBtn('按钮id')

设置按钮可用dialog.enabledBtn('按钮id')

hideBtn('按钮id')

设置按钮不可见:dialog.hideBtn('按钮id')

showBtn('按钮id')

设置按钮可见dialog.showBtn('按钮id')

reSize(json)

设置dialog的大小dialog.reSize({width:300,height:300})

getMin(json)

调用嵌入页面中MIN()方法:dialog.getMin(json);

getMax(json)

调用嵌入页面中MAX()方法:dialog.getMax(json);

getClose(json)

调用嵌入页面中CLOSE()方法:dialog.getClose(json);

getWidth()

获取内容区域宽度:dialog.getWidth();

getHeight()

获取内容区域高度:dialog.getHeight();

reloadUrl(url)

重新设置url,如果不传参,为声明dialog的url参数:dialog.reloadUrl("http://www.qq.com");

setTitle(title)

重新设置title

window.parentDialogObj[id]

子页面获取dialog对象

getTransParams()

子页面获取dialog参数【window.parentDialogObj[id].getTransParams()】

startLoading()

显示遮罩

endLoading()

隐藏遮罩

其他说明

弹框确定的时候会调用dialog.getReturnValue();来获取窗口的返回信息

buttons

:

[

{

text

:

"button1"

,

handler

:

function

(

)

{

dialog

.

startLoading

(

)

var

oooooooooo

=

dialog

.

getReturnValue

(

)

;

//这里就可以获取到{rows:"false"};

}

]

// dialog.getReturnValue() 中获取的值其实是窗口界面里面OK函数的返回值

// 需要在iframe界面定义

function

OK

(

)

{

return

{

rows

:

"false"

}

;

}

:::

## 29. Message 消息提示

> 原始路径：`/components3.0/notice/message.html`  
> 相对路径：`components3.0/notice/message.md`  
> 页面 key：`v-2bb8829f`  
> JS Chunk：`26.27ae3fd8.js`

Message 消息提示

确定

确定 + 取消

是 + 否 + 取消

是 + 否

重试 + 取消

确定 + 详细

自定义

function showMessageBox(flag) {
if (flag == 0) {
$.messageBox({
'type': 0,
'msg': 'this is msg content!',
ok_fn: function () { alert('确定后执行，自定义方法test()!'); }
});
} else if (flag == 1) {
$.messageBox({
'type': 1,
'msg': 'this is msg content!',
ok_fn: function () { alert('确定后执行，自定义方法test()!'); }
});
} else if (flag == 2) {
$.messageBox({
'type': 2,
'msg': 'this is msg content!',
ok_fn: function () { alert('确定后执行，自定义方法test()!'); }
});
} else if (flag == 3) {
$.messageBox({
'type': 3,
'msg': 'this is msg content!',
ok_fn: function () { alert('确定后执行，自定义方法test()!'); }
});
} else if (flag == 4) {
$.messageBox({
'type': 4,
'msg': 'this is msg content!',
ok_fn: function () { alert('确定后执行，自定义方法test()!'); }
});
} else if (flag == 5) {
$.messageBox({
'type': 5,
'msg': 'this is msg content!',
imgType: 4,
ok_fn: function () { alert('确定后执行，自定义方法test()!'); }
});
} else if (flag == 100) {
$.messageBox({
'type': 100,
'msg': 'this is msg content!',
buttons: [{
id:'btn1',
text: "button1",
handler: function () { alert('handler') }
}, {
id:'btn2',
text: "button2",
handler: function () { alert('handler') }
}]
});
}
}

<

a

href

=

"

javascript:showMessageBox(0)

"

class

=

"

common_button common_button_gray

"

>

确定

</

a

>

<

a

href

=

"

javascript:showMessageBox(1)

"

class

=

"

common_button common_button_gray

"

>

确定 + 取消

</

a

>

<

a

href

=

"

javascript:showMessageBox(2)

"

class

=

"

common_button common_button_gray

"

>

是 + 否 + 取消

</

a

>

<

a

href

=

"

javascript:showMessageBox(3)

"

class

=

"

common_button common_button_gray

"

>

是 + 否

</

a

>

<

a

href

=

"

javascript:showMessageBox(4)

"

class

=

"

common_button common_button_gray

"

>

重试 + 取消

</

a

>

<

a

href

=

"

javascript:showMessageBox(5)

"

class

=

"

common_button common_button_gray

"

>

确定 + 详细

</

a

>

<

a

href

=

"

javascript:showMessageBox(100)

"

class

=

"

common_button common_button_gray

"

>

自定义

</

a

>

<

script

type

=

"

text/javascript

"

>

function

showMessageBox

(

flag

)

{

if

(

flag

==

0

)

{

$

.

messageBox

(

{

'type'

:

0

,

'msg'

:

'this is msg content!'

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法test()!'

)

;

}

)

;

}

else

if

(

flag

==

1

)

{

$

.

messageBox

(

{

'type'

:

1

,

'msg'

:

'this is msg content!'

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法test()!'

)

;

}

)

;

}

else

if

(

flag

==

2

)

{

$

.

messageBox

(

{

'type'

:

2

,

'msg'

:

'this is msg content!'

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法test()!'

)

;

}

)

;

}

else

if

(

flag

==

3

)

{

$

.

messageBox

(

{

'type'

:

3

,

'msg'

:

'this is msg content!'

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法test()!'

)

;

}

)

;

}

else

if

(

flag

==

4

)

{

$

.

messageBox

(

{

'type'

:

4

,

'msg'

:

'this is msg content!'

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法test()!'

)

;

}

)

;

}

else

if

(

flag

==

5

)

{

$

.

messageBox

(

{

'type'

:

5

,

'msg'

:

'this is msg content!'

,

imgType

:

4

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法test()!'

)

;

}

)

;

}

else

if

(

flag

==

100

)

{

$

.

messageBox

(

{

'type'

:

100

,

'msg'

:

'this is msg content!'

,

buttons

:

[

{

id

:

'btn1'

,

text

:

"button1"

,

handler

:

function

(

)

{

alert

(

'handler'

)

}

,

{

id

:

'btn2'

,

text

:

"button2"

,

handler

:

function

(

)

{

alert

(

'handler'

)

}

]

}

)

;

}

</

script

>

## 30. MessageBox 提示窗口

> 原始路径：`/components3.0/notice/messageBox.html`  
> 相对路径：`components3.0/notice/messageBox.md`  
> 页面 key：`v-39c2fc53`  
> JS Chunk：`73.32e4fdae.js`

MessageBox 提示窗口

基本使用

alert

info

error

confirm

自定义

$(document).ready(function(){
$('#alert').click(function(){
var alertObj = $.alert("这个是alert窗口!");
});
$('#infor').click(function(){
var infor = $.infor("这个是提示信息!");
});
$('#error').click(function(){
var error = $.error("这个是错误对话框!");
});
$('#confirm').click(function(){
var confirm = $.confirm({
width:400,
bottomHTML:'<span style="line-height:30px; color:#fff;"><label for="Checkbox5" class="margin_t_5 hand"><input type="checkbox" value="0" id="Checkbox5" name="option" class="radio_com">选项1</label><span class="color_blue hand" title="啊啊啊啊啊啊啊啊啊啊啊a啊啊">[说明]</span></span>',
'msg': '点击按钮后执行某个方法!',
ok_fn: function () { alert('确定后执行，自定义方法!'); },
cancel_fn:function(){alert('取消后执行，自定义方法!');}
});
});
$('#random').click(function(){
var random = $.messageBox({
'type': 100,
'msg': 'this is msg content!',
buttons: [{
text: "button1",
handler: function () { alert('handler') }
}, {
text: "button2",
handler: function () { alert('handler') }
}]
});
});
});

<

a

id

=

"

alert

"

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

alert

</

a

>

<

a

id

=

"

infor

"

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

info

</

a

>

<

a

id

=

"

error

"

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

error

</

a

>

<

a

id

=

"

confirm

"

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

confirm

</

a

>

<

a

id

=

"

random

"

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_gray

"

>

自定义

</

a

>

<

script

>

$

(

document

)

.

ready

(

function

(

)

{

$

(

'#alert'

)

.

click

(

function

(

)

{

var

alertObj

=

$

.

alert

(

"这个是alert窗口!"

)

;

}

)

;

$

(

'#infor'

)

.

click

(

function

(

)

{

var

infor

=

$

.

infor

(

"这个是提示信息!"

)

;

}

)

;

$

(

'#error'

)

.

click

(

function

(

)

{

var

error

=

$

.

error

(

"这个是错误对话框!"

)

;

}

)

;

$

(

'#confirm'

)

.

click

(

function

(

)

{

var

confirm

=

$

.

confirm

(

{

width

:

400

,

bottomHTML

:

'<span style="line-height:30px; color:#fff;"><label for="Checkbox5" class="margin_t_5 hand"><input type="checkbox" value="0" id="Checkbox5" name="option" class="radio_com">选项1</label><span class="color_blue hand" title="啊啊啊啊啊啊啊啊啊啊啊a啊啊">[说明]</span></span>'

,

'msg'

:

'点击按钮后执行某个方法!'

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法!'

)

;

}

,

cancel_fn

:

function

(

)

{

alert

(

'取消后执行，自定义方法!'

)

;

}

)

;

}

)

;

$

(

'#random'

)

.

click

(

function

(

)

{

var

random

=

$

.

messageBox

(

{

'type'

:

100

,

'msg'

:

'this is msg content!'

,

buttons

:

[

{

text

:

"button1"

,

handler

:

function

(

)

{

alert

(

'handler'

)

}

,

{

text

:

"button2"

,

handler

:

function

(

)

{

alert

(

'handler'

)

}

]

}

)

;

}

)

;

}

)

;

</

script

>

使用规范

红色叉子

是错误 、警告（只看警告结果，不可选择操作的）

黄色叹号

警告（结果用户可选择）、询问（需要强调的）

蓝色问号

询问（一般的询问，不需要很强调的）

绿色对勾

正确操作的反馈

属性

类型

描述

type

消息窗口类型

type值(类型)

Button

返回值

0

确定

ok

1

确定 + 取消

ok + cancel

2

是 + 否 + 取消

yes + no + cancel

3

是 + 否

yes + no

4

重试 + 取消

retry + cancel

5

确定 + 详细

ok + detail

100

自定义按钮及事件

title

消息窗口名称

imgType

消息窗口图片类型(0:成功)--(1:操作失败)--(2:警告)--(3:询问)

msg

y提示信息内容

ok_fn

点击确定后执行的函数

cancel_fn

点击取消后执行的函数

yes_fn

点击是后执行的函数

no_fn

点击否后执行的函数

retry_fn

点击重试后执行的函数

detail_fn

点击详情后执行的函数

close_fn

点击右上角 X 调用的方法

buttons

自定义按钮及事件

isFrountEvent

点击按钮后是否先执行自定义事件[默认先关闭窗口再执行自定义事件]

escapeHTML

Boolean

对传入的内容是否进行html转义，默认为false

方法

描述

close()

关闭窗口

var

win

=

new

MxtMsgBox

(

{

'type'

:

0

,

'msg'

:

'this is msg content!'

,

ok_fn

:

function

(

)

{

alert

(

'确定后执行，自定义方法test()!'

)

;

}

)

;

win

.

close

(

)

;

:::

## 31. tooltip 气球状提示

> 原始路径：`/components3.0/notice/tooltip.html`  
> 相对路径：`components3.0/notice/tooltip.md`  
> 页面 key：`v-109d0da7`  
> JS Chunk：`74.da363abf.js`

tooltip 气球状提示

鼠标触发提示

tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。

我要显示1

我要显示2

$(function () {
$("#testID").tooltip({
id: '1111111',
htmlID: 'tooltip_html'//内容优先级顺序[ htmlID、msg、tooltip属性]
});
})

<

a

id

=

"

testID

"

tooltip

=

"

tooltip

"

href

=

"

style

=

"

cursor

:

default

;

display

:

block

;

width

:

600px

;

"

>

tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。tooltip测试，靠左或靠右显示。

</

a

>

<

div

class

=

"

hidden

"

>

<

div

id

=

"

tooltip_html

"

>

<

ul

>

<

li

id

=

"

testtttt

"

>

我要显示1

</

li

>

<

li

>

我要显示2

</

li

>

</

ul

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

$

(

function

(

)

{

$

(

"#testID"

)

.

tooltip

(

{

id

:

'1111111'

,

htmlID

:

'tooltip_html'

//内容优先级顺序[ htmlID、msg、tooltip属性]

}

)

;

}

)

</

script

>

指定位置提示

指定位置显示.

关闭按钮,class为tooltip_close

知道了

$(function () {
$.tooltip({
id: '22222111',
width: 300,
openAuto: true,
event: false,
openPoint: [50, 100],
htmlID: 'tooltip_html2',
direction: "BL"
});
})

<

html

>

<

body

style

=

"

position

:

relative

;

height

:

300px

;

"

>

<

div

class

=

"

hidden

"

>

<

div

id

=

"

tooltip_html2

"

>

指定位置显示.

<

br

/>

关闭按钮,class为tooltip_close

<

br

/>

<

p

class

=

"

align_right

"

>

<

a

class

=

"

tooltip_close font_size12

"

href

=

"

javascript:void(0)

"

>

知道了

</

a

>

</

p

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

$

(

function

(

)

{

$

.

tooltip

(

{

id

:

'22222111'

,

width

:

300

,

openAuto

:

true

,

event

:

false

,

openPoint

:

[

50

,

100

]

,

htmlID

:

'tooltip_html2'

,

direction

:

"BL"

}

)

;

}

)

</

script

>

</

body

>

</

html

>

## 32. 打印

> 原始路径：`/components3.0/other/print.html`  
> 相对路径：`components3.0/other/print.md`  
> 页面 key：`v-7d2c219a`  
> JS Chunk：`75.f587b91a.js`

打印

function printColl(){
var printSubject = "标题";
var printsub = "printsub";
printsub = "<center><hr style='height:1px' class='Noprint'&lgt;</hr><span style='font-size:24px;line-height:24px;'>"+printsub.escapeHTML()+"</span></center>";
var printSubFrag = new PrintFragment(printSubject, printsub);

var printSenderInfo = "发起人信息";
var printSender = "printSender";
printSender = "<center><span style='font-size:12px;line-height:16px;'>" + printSender + "</span></center>";
var printSenderFrag = new PrintFragment(printSenderInfo, printSender);

var printColBody= "正文";
var colBody = $('#col-contentText').html();
var colBodyFrag = new PrintFragment(printColBody, colBody);

var cssList = new ArrayList();
cssList.add("/apps_res/collaboration/css/collaboration.css")

var pl = new ArrayList();
pl.add(printSubFrag);
pl.add(printSenderFrag);
pl.add(colBodyFrag);

printList(pl,cssList);
}

<

a

id

=

"

print

"

class

=

"

common_button common_button_gray

"

>

打印

</

a

>

<

script

>

function

printColl

(

)

{

var

printSubject

=

"标题"

;

var

printsub

=

"printsub"

;

printsub

=

"<center><hr style='height:1px' class='Noprint'&lgt;</hr><span style='font-size:24px;line-height:24px;'>"

+

printsub

.

escapeHTML

(

)

+

"</span></center>"

;

var

printSubFrag

=

new

PrintFragment

(

printSubject

,

printsub

)

;

var

printSenderInfo

=

"发起人信息"

;

var

printSender

=

"printSender"

;

printSender

=

"<center><span style='font-size:12px;line-height:16px;'>"

+

printSender

+

"</span></center>"

;

var

printSenderFrag

=

new

PrintFragment

(

printSenderInfo

,

printSender

)

;

var

printColBody

=

"正文"

;

var

colBody

=

$

(

'#col-contentText'

)

.

html

(

)

;

var

colBodyFrag

=

new

PrintFragment

(

printColBody

,

colBody

)

;

var

cssList

=

new

ArrayList

(

)

;

cssList

.

add

(

"/apps_res/collaboration/css/collaboration.css"

)

var

pl

=

new

ArrayList

(

)

;

pl

.

add

(

printSubFrag

)

;

pl

.

add

(

printSenderFrag

)

;

pl

.

add

(

colBodyFrag

)

;

printList

(

pl

,

cssList

)

;

}

</

script

>

## 33. seeyon v4.0 组件

> 原始路径：`/components3.0/seeyon.html`  
> 相对路径：`components3.0/seeyon.md`  
> 页面 key：`v-b7367896`  
> JS Chunk：`76.ce16883d.js`

seeyon v4.0 组件

常用的操作按钮。

基础用法

基础的按钮用法。

选项1

选项2

选项3

选项4

选项5

为

<button>

添加

el-button

样式设置按钮，添加不同的额外样式设置不同的表现。

<

span

class

=

"

ctpUiRadio

"

>

<

input

type

=

"

radio

"

value

=

"

1

"

id

=

"

Radio11

"

name

=

"

option1

"

>

<

label

for

=

"

Radio11

"

class

=

"

>

<

i

>

</

i

>

选项1

</

label

>

</

span

>

<

span

class

=

"

ctpUiRadio

"

>

<

input

type

=

"

radio

"

value

=

"

2

"

id

=

"

Radio12

"

name

=

"

option1

"

>

<

label

for

=

"

Radio12

"

class

=

"

>

<

i

>

</

i

>

选项2

</

label

>

</

span

>

<

span

class

=

"

ctpUiRadio

"

>

<

input

type

=

"

radio

"

value

=

"

3

"

id

=

"

Radio13

"

name

=

"

option1

"

>

<

label

for

=

"

Radio13

"

class

=

"

>

<

i

>

</

i

>

选项3

</

label

>

</

span

>

<

span

class

=

"

ctpUiRadio

"

>

<

input

type

=

"

radio

"

value

=

"

4

"

id

=

"

Radio14

"

name

=

"

option1

"

disabled

checked

>

<

label

for

=

"

Radio14

"

class

=

"

>

<

i

>

</

i

>

选项4

</

label

>

</

span

>

<

span

class

=

"

ctpUiRadio

"

>

<

input

type

=

"

radio

"

value

=

"

5

"

id

=

"

Radio15

"

name

=

"

option1

"

disabled

>

<

label

for

=

"

Radio15

"

class

=

"

>

<

i

>

</

i

>

选项5

</

label

>

</

span

>

## 34. seeyon v3.0 组件

> 原始路径：`/components3.0/seeyon3.0.html`  
> 相对路径：`components3.0/seeyon3.0.md`  
> 页面 key：`v-37fd7a73`  
> JS Chunk：`77.c3c5a48d.js`

seeyon v3.0 组件

常用的操作按钮。

基础用法

基础的按钮用法。

function getValue(){
var index=$("#select")[0].selectedIndex;
alert($("#select")[0][index].innerHTML);
}

$().ready(function(){
var tt = $("#toolbar").toolbar({
//searchHtml:"search",
//showSeparate:false,
toolbar: [{

id: "transmit",
name: "转发",
className: "ico16",//设置图标
click:function(){
alert("转发");
},
subMenu: [{
id:'sssssssssss',
name: "协同",
click: function(){
alert(111);
}
}, {
id:'dfdfdfd1',
name: "邮件",
click: function(){
alert(222);
}
}, {
id:'dfdfdfd2',
name: "邮件",
click: function(){
alert(222);
}
}, {
id:'dfdfdfd3',
name: "邮件",
click: function(){
alert(222);
}
}, {
id:'dfdfdfd4',
name: "邮件",
click: function(){
alert(222);
}
}]
}, {
id: "delete",
name: "删除",
className: "ico16 del_16",
selected:true
}, {
id: "refresh",
name: "刷新",
className: "ico16 refresh_16"
},{
id: "select",
type: "select",
value:"-1",
text:"重要程度",
//className:"hidden",
onchange:getValue,
// disabled:true,
items: [{
text: '普通',
value: '0'
}, {
text: '重要',
value: '1'
}, {
text: '非常重要',
value: '2'
}]

// className: "ico16 del_16",
},{
id: "checkb2222ox",
type: "checkbox",
text:"同一流程只显示最后一条",
value:"1",
checked:true,
click:function(){
alert(21111122)
}
}]
});
tt.hideBtn('sssssssssss');
tt.hideBtn('dfdfdfd1');
tt.hideBtn('dfdfdfd2');
//动态添加按钮
tt.addMenu({
id: "deldddddete",
name: "删dddd除",
className: "ico16 del_16"
});
//tt.disabled("transmit");
//tt.showBtn('sssssssssss');
});

为

<button>

添加

el-button

样式设置按钮，添加不同的额外样式设置不同的表现。

<

div

id

=

"

toolbar

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

function

getValue

(

)

{

var

index

=

$

(

"#select"

)

[

0

]

.

selectedIndex

;

alert

(

$

(

"#select"

)

[

0

]

[

index

]

.

innerHTML

)

;

}

$

(

)

.

ready

(

function

(

)

{

var

tt

=

$

(

"#toolbar"

)

.

toolbar

(

{

//searchHtml:"search",

//showSeparate:false,

toolbar

:

[

{

id

:

"transmit"

,

name

:

"转发"

,

className

:

"ico16"

,

//设置图标

click

:

function

(

)

{

alert

(

"转发"

)

;

}

,

subMenu

:

[

{

id

:

'sssssssssss'

,

name

:

"协同"

,

click

:

function

(

)

{

alert

(

111

)

;

}

,

{

id

:

'dfdfdfd1'

,

name

:

"邮件"

,

click

:

function

(

)

{

alert

(

222

)

;

}

,

{

id

:

'dfdfdfd2'

,

name

:

"邮件"

,

click

:

function

(

)

{

alert

(

222

)

;

}

,

{

id

:

'dfdfdfd3'

,

name

:

"邮件"

,

click

:

function

(

)

{

alert

(

222

)

;

}

,

{

id

:

'dfdfdfd4'

,

name

:

"邮件"

,

click

:

function

(

)

{

alert

(

222

)

;

}

]

}

,

{

id

:

"delete"

,

name

:

"删除"

,

className

:

"ico16 del_16"

,

selected

:

true

}

,

{

id

:

"refresh"

,

name

:

"刷新"

,

className

:

"ico16 refresh_16"

}

,

{

id

:

"select"

,

type

:

"select"

,

value

:

"-1"

,

text

:

"重要程度"

,

//className:"hidden",

onchange

:

getValue

,

// disabled:true,

items

:

[

{

text

:

'普通'

,

value

:

'0'

}

,

{

text

:

'重要'

,

value

:

'1'

}

,

{

text

:

'非常重要'

,

value

:

'2'

}

]

// className: "ico16 del_16",

}

,

{

id

:

"checkb2222ox"

,

type

:

"checkbox"

,

text

:

"同一流程只显示最后一条"

,

value

:

"1"

,

checked

:

true

,

click

:

function

(

)

{

alert

(

21111122

)

}

]

}

)

;

tt

.

hideBtn

(

'sssssssssss'

)

;

tt

.

hideBtn

(

'dfdfdfd1'

)

;

tt

.

hideBtn

(

'dfdfdfd2'

)

;

//动态添加按钮

tt

.

addMenu

(

{

id

:

"deldddddete"

,

name

:

"删dddd除"

,

className

:

"ico16 del_16"

}

)

;

//tt.disabled("transmit");

//tt.showBtn('sssssssssss');

}

)

;

</

script

>

基础用法

基础的按钮用法。

div1

div2

div3

div4

1

2

3

4

为

<button>

添加

el-button

样式设置按钮，添加不同的额外样式设置不同的表现。

<

div

class

=

"

code_area

"

>

<

div

id

=

"

tabs21

"

class

=

"

comp

"

comp

=

"

type:'tab',width:600,height:100

"

comptype

=

"

tab

"

>

<

div

id

=

"

tabs21_head

"

class

=

"

common_tabs clearfix

"

>

<

ul

class

=

"

left

"

>

<

li

class

=

"

current

"

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab11_div

"

>

<

span

>

div1

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab21_div

"

>

<

span

>

div2

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab31_div

"

>

<

span

>

div3

</

span

>

</

a

>

</

li

>

<

li

>

<

a

href

=

"

javascript:void(0)

"

tgt

=

"

tab41_div

"

>

<

span

>

div4

</

span

>

</

a

>

</

li

>

</

ul

>

</

div

>

<

div

id

=

"

tabs21_body

"

class

=

"

common_tabs_body

"

>

<

div

id

=

"

tab11_div

"

>

1

</

div

>

<

div

id

=

"

tab21_div

"

class

=

"

hidden

"

>

2

</

div

>

<

div

id

=

"

tab31_div

"

class

=

"

hidden

"

>

3

</

div

>

<

div

id

=

"

tab41_div

"

class

=

"

hidden

"

>

4

</

div

>

</

div

>

</

div

>

</

div

>

## 35. Color 色彩

> 原始路径：`/components4.0/basic/color.html`  
> 相对路径：`components4.0/basic/color.md`  
> 页面 key：`v-8d1701da`  
> JS Chunk：`27.ce7599ec.js`

Color 色彩

推荐使用以下调色板的颜色作为设计和开发规范，以保证页面和组件之间的视觉一致。

主色

使用较为安全的蓝色作为主色调

Primary

#1F85EC

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_primary

"

title

=

"

#1F85EC

"

>

<

p

>

Primary

</

p

>

<

p

>

#1F85EC

</

p

>

</

div

>

<

div

class

=

"

list-s

"

>

<

div

class

=

"

item color_primary

"

title

=

"

#1F85EC

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha90

"

title

=

"

rgba(31, 133, 236, 0.9)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha80

"

title

=

"

rgba(31, 133, 236, 0.8)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha70

"

title

=

"

rgba(31, 133, 236, 0.7)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha60

"

title

=

"

rgba(31, 133, 236, 0.6)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha50

"

title

=

"

rgba(31, 133, 236, 0.5)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha40

"

title

=

"

rgba(31, 133, 236, 0.4)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha30

"

title

=

"

rgba(31, 133, 236, 0.3)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha20

"

title

=

"

rgba(31, 133, 236, 0.2)

"

>

</

div

>

<

div

class

=

"

item color_primary_alpha10

"

title

=

"

rgba(31, 133, 236, 0.1)

"

>

</

div

>

</

div

>

</

div

>

辅助色

辅助色是具有代表性的颜色，常用于信息提示，比如成功、警告和失败。

Info

#1F85EC

Success

#67C13A

Warning

#E8A849

Error

#F56C6C

<

div

class

=

"

list-b

"

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_info

"

title

=

"

#1F85EC

"

>

<

p

>

Info

</

p

>

<

p

>

#1F85EC

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_success

"

title

=

"

#67C13A

"

>

<

p

>

Success

</

p

>

<

p

>

#67C13A

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_warning

"

title

=

"

#E8A849

"

>

<

p

>

Warning

</

p

>

<

p

>

#E8A849

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_error

"

title

=

"

#F56C6C

"

>

<

p

>

Error

</

p

>

<

p

>

#F56C6C

</

p

>

</

div

>

</

div

>

</

div

>

中性色

中性色常用于文本、背景、边框、阴影等，可以体现出页面的层次结构。

主要文字

#000000

常规文字

#333333

次要文字

#999999

占位文字

#909399

基础白色

#FFFFFF

选择器描边颜色

#E4E7ED

输入框描边颜色

#DCDFE6

禁用的输入框内部颜色

#F5F7FA

较深的颜色块

#C0C4CC

<

div

class

=

"

list-b

"

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_main_text

"

title

=

"

#000000

"

>

<

p

>

主要文字

</

p

>

<

p

>

#000000

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_regular_text

"

title

=

"

#333333

"

>

<

p

>

常规文字

</

p

>

<

p

>

#333333

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_secondary_text

"

title

=

"

#999999

"

>

<

p

>

次要文字

</

p

>

<

p

>

#999999

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_placeholder_text

"

title

=

"

#909399

"

>

<

p

>

占位文字

</

p

>

<

p

>

#909399

</

p

>

</

div

>

</

div

>

</

div

>

<

div

class

=

"

list-b

"

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_basic_white

"

title

=

"

#FFFFFF

"

>

<

p

>

基础白色

</

p

>

<

p

>

#FFFFFF

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_select_border

"

title

=

"

#E4E7ED

"

>

<

p

>

选择器描边颜色

</

p

>

<

p

>

#E4E7ED

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_input_border

"

title

=

"

#DCDFE6

"

>

<

p

>

输入框描边颜色

</

p

>

<

p

>

#DCDFE6

</

p

>

</

div

>

</

div

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_disable_bg

"

title

=

"

#F5F7FA

"

>

<

p

>

禁用的输入框内部颜色

</

p

>

<

p

>

#F5F7FA

</

p

>

</

div

>

</

div

>

</

div

>

<

div

class

=

"

list-b

"

>

<

div

class

=

"

listOut

"

>

<

div

class

=

"

list color_dark_block

"

title

=

"

#C0C4CC

"

>

<

p

>

较深的颜色块

</

p

>

<

p

>

#C0C4CC

</

p

>

</

div

>

</

div

>

</

div

>

## 36. Typography 字体

> 原始路径：`/components4.0/basic/typography.html`  
> 相对路径：`components4.0/basic/typography.md`  
> 页面 key：`v-018f29be`  
> JS Chunk：`46.985ccc7f.js`

Typography 字体

我们对字体进行统一规范，力求在各个操作系统下都有最佳展示效果。

字体

font-family:Arial, "Ping Fang SC", "Microsoft YaHei", Helvetica, sans-serif, "SimSun"

字号

样式

字号

(字体大小的1.4倍取偶数)

标准字

20px

28px

标准字

18px

26px

标准字

16px

22px

标准字

14px

20px

标准字

12px

16px

## 37. Badge 标记

> 原始路径：`/components4.0/data/badge.html`  
> 相对路径：`components4.0/data/badge.md`  
> 页面 key：`v-622ef476`  
> JS Chunk：`78.6c735667.js`

Badge 标记

出现在按钮、图标旁的数字或状态标记。

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#id").attrObj("_CtpUiComBadge");方式来获取对象

基础用法

展示新消息数量。

按钮

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiBadge

"

comp

=

"

type:'badge',value:999

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

按钮

</

a

>

</

div

>

</

div

>

</

div

>

最大值

可自定义最大值。

按钮

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiBadge

"

comp

=

"

type:'badge',value:999,max:99

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

按钮

</

a

>

</

div

>

</

div

>

</

div

>

自定义内容

可以显示数字以外的文本内容。

按钮

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiBadge margin_r_10

"

comp

=

"

type:'badge',value:'new'

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

按钮

</

a

>

</

div

>

<

div

class

=

"

comp ctpUiBadge

"

comp

=

"

type:'badge',value:'hot'

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

按钮

</

a

>

</

div

>

</

div

>

</

div

>

小红点

以红点的形式标注需要关注的内容。

按钮

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiBadge margin_r_10

"

comp

=

"

type:'badge',isDot:true

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button radius3px

"

>

按钮

</

a

>

</

div

>

<

div

class

=

"

comp ctpUiBadge margin_r_10

"

comp

=

"

type:'badge',isDot:true

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button common_button_emphasize radius3px

"

>

按钮

</

a

>

</

div

>

</

div

>

</

div

>

参数列表

参数

说明

类型

可选值

默认值

value

显示值

string, number

—

max

最大值，超过最大值会显示 '{max}+'，要求 value 是 Number 类型

number

—

isDot

小圆点

boolean

—

false

bgColor

背景色

string

合法颜色值即可

#F56C6C

textColor

文字颜色

string

合法颜色值即可

#FFFFFF

## 38. Progress 进度条

> 原始路径：`/components4.0/data/progress.html`  
> 相对路径：`components4.0/data/progress.md`  
> 页面 key：`v-750bf1d3`  
> JS Chunk：`28.b3c08fcb.js`

Progress 进度条

采用对象方式渲染

设置为55%

加5%

减5%

var testData1 = {
percent: 100,
text: "满了"
}
var test1 = new CtpUiProgress(document.getElementById("demoDiv1"), testData1);

var testData2 = {
percent: 50,
status: "success"
}
var test2 = new CtpUiProgress(document.getElementById("demoDiv2"), testData2);

var testData3 = {
percent: 60,
status: "warning"
}
var test3 = new CtpUiProgress(document.getElementById("demoDiv3"), testData3);

var testData4 = {
percent: 20,
status: "exception",
icon: "sy-delete-x"
}
var test4 = new CtpUiProgress(document.getElementById("demoDiv4"), testData4);

var testData5 = {
percent: 33,
height: 20,
textInside: true,
innerColor: "#ff0000",
outerColor: "#B200FF"
}
var test5 = new CtpUiProgress(document.getElementById("demoDiv5"), testData5);

$("#setPercent4Test5").on("click",function(){
test5.setPercent(55);
});

$("#increase4Test5").on("click",function(){
test5.increase(5);
});

$("#decrease4Test5").on("click",function(){
test5.decrease(5);
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demoDiv1

"

>

</

div

>

<

div

id

=

"

demoDiv2

"

>

</

div

>

<

div

id

=

"

demoDiv3

"

>

</

div

>

<

div

id

=

"

demoDiv4

"

>

</

div

>

<

br

/>

<

br

/>

<

div

id

=

"

demoDiv5

"

>

</

div

>

<

br

/>

<

div

>

<

a

id

=

"

setPercent4Test5

"

href

=

"

#### "

class

=

"

common_button

"

>

设置为55%

</

a

>

<

a

id

=

"

increase4Test5

"

href

=

"

#### "

class

=

"

common_button

"

>

加5%

</

a

>

<

a

id

=

"

decrease4Test5

"

href

=

"

#### "

class

=

"

common_button

"

>

减5%

</

a

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData1

=

{

percent

:

100

,

text

:

"满了"

}

var

test1

=

new

CtpUiProgress

(

document

.

getElementById

(

"demoDiv1"

)

,

testData1

)

;

var

testData2

=

{

percent

:

50

,

status

:

"success"

}

var

test2

=

new

CtpUiProgress

(

document

.

getElementById

(

"demoDiv2"

)

,

testData2

)

;

var

testData3

=

{

percent

:

60

,

status

:

"warning"

}

var

test3

=

new

CtpUiProgress

(

document

.

getElementById

(

"demoDiv3"

)

,

testData3

)

;

var

testData4

=

{

percent

:

20

,

status

:

"exception"

,

icon

:

"sy-delete-x"

}

var

test4

=

new

CtpUiProgress

(

document

.

getElementById

(

"demoDiv4"

)

,

testData4

)

;

var

testData5

=

{

percent

:

33

,

height

:

20

,

textInside

:

true

,

innerColor

:

"#ff0000"

,

outerColor

:

"#B200FF"

}

var

test5

=

new

CtpUiProgress

(

document

.

getElementById

(

"demoDiv5"

)

,

testData5

)

;

$

(

"#setPercent4Test5"

)

.

on

(

"click"

,

function

(

)

{

test5

.

setPercent

(

55

)

;

}

)

;

$

(

"#increase4Test5"

)

.

on

(

"click"

,

function

(

)

{

test5

.

increase

(

5

)

;

}

)

;

$

(

"#decrease4Test5"

)

.

on

(

"click"

,

function

(

)

{

test5

.

decrease

(

5

)

;

}

)

;

</

script

>

采用comp方式渲染

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

ctpUiProgress1

"

class

=

"

comp

"

comp

=

"

type:'CtpUiProgress',options:{percent:30}

"

>

</

div

>

</

div

>

</

div

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

-

options

percent

百分比（必填）

number

-

status

进度条当前状态（选填）

string("default"/success"/"exception"/"warning")

"default"

textInside

进度条显示文字内置在进度条内（选填）

boolean

false

text

文本（选填）

string

-

icon

图标的class（选填）

string

-

innerColor

内框的颜色（选填，会覆盖status状态的默认颜色）

string(HEX值，从"#000000"至"#ffffff")

-

outerColor

外框的颜色（选填，会覆盖status状态的默认颜色）

string(HEX值，从"#000000"至"#ffffff")

-

height

高度（选填）

number(像素)

6

方法列表

方法

说明

参数

setPercent

设置百分比

number(>=0 且<=100)

increase

增加百分比

number(>=0 且<=100)

decrease

减少百分比

number(>=0 且<=100)

destory

销毁元素

-

## 39. Table 表格

> 原始路径：`/components4.0/data/table.html`  
> 相对路径：`components4.0/data/table.md`  
> 页面 key：`v-265b99af`  
> JS Chunk：`29.f0bb0c4e.js`

Table 表格

基础用法

基础的表格展示用法。

任务开始时间

任务结束时间

任务名称

所属项目组

负责人

2019-01-01

2019-01-31

UE设计

UE

李洪泽

2019-01-01

2019-01-31

UE设计

UE

李洪泽

2019-01-01

2019-01-31

UE设计

UE

李洪泽

2019-01-01

2019-01-31

UE设计

UE

李洪泽

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

table

class

=

"

ctpUiTable

"

>

<

thead

>

<

tr

>

<

th

>

任务开始时间

</

th

>

<

th

>

任务结束时间

</

th

>

<

th

>

任务名称

</

th

>

<

th

>

所属项目组

</

th

>

<

th

>

负责人

</

th

>

</

tr

>

</

thead

>

<

tbody

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

</

div

>

任务开始时间

任务结束时间

任务名称

所属项目组

负责人

2019-01-01

2019-01-31

UE设计

UE

李洪泽

2019-01-01

2019-01-31

UE设计

UE

李洪泽

2019-01-01

2019-01-31

UE设计

UE

李洪泽

2019-01-01

2019-01-31

UE设计

UE

李洪泽

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

table

class

=

"

ctpUiTable

"

width

=

"

100%

"

>

<

thead

>

<

tr

>

<

th

>

任务开始时间

</

th

>

<

th

>

任务结束时间

</

th

>

<

th

>

任务名称

</

th

>

<

th

>

所属项目组

</

th

>

<

th

>

负责人

</

th

>

</

tr

>

</

thead

>

<

tbody

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

<

tr

>

<

td

>

2019-01-01

</

td

>

<

td

>

2019-01-31

</

td

>

<

td

>

UE设计

</

td

>

<

td

>

UE

</

td

>

<

td

>

李洪泽

</

td

>

</

tr

>

</

tbody

>

</

table

>

</

div

>

</

div

>

## 40. Tag 标签

> 原始路径：`/components4.0/data/tag.html`  
> 相对路径：`components4.0/data/tag.md`  
> 页面 key：`v-5c07dad2`  
> JS Chunk：`79.26817b22.js`

Tag 标签

用于标记和选择。

基础样式

<

div

id

=

"

cantDel

"

class

=

"

comp

"

comp

=

"

type:'tag',closable:false,click:'clickFn'

"

tagsdata

=

"

[{label:'标签一'},{label:'标签二',type:'success'},{label:'标签三',type:'info'},{label:'标签四',type:'warning'},{label:'标签五',type:'danger'}]

"

>

</

div

>

带删除按钮的标签

<

div

id

=

"

canDel

"

class

=

"

comp

"

comp

=

"

type:'tag',closable:true,click:'clickFn'

"

tagsdata

=

"

[{label:'标签一'},{label:'标签二',type:'success'},{label:'标签三',type:'info'},{label:'标签四',type:'warning'},{label:'标签五',type:'danger'}]

"

>

</

div

>

动态编辑标签

<

div

id

=

"

canDelandAdd

"

class

=

"

comp

"

comp

=

"

type:'tag',dynamicTags:true,closable:true,close:'closeFn'

"

tagsdata

=

"

[{'label':'标签一'},{'label':'标签二'},{'label':'标签三'}]

"

>

</

div

>

不同尺寸

1、默认尺寸

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

normal

"

class

=

"

comp

"

comp

=

"

type:'tag',closable:false,click:'clickFn'

"

tagsdata

=

"

[{'label':'标签一'},{'label':'标签二'},{'label':'标签三'},{'label':'标签四'},{'label':'标签五'}]

"

>

</

div

>

</

div

>

</

div

>

2、较小尺寸

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

small

"

class

=

"

comp

"

comp

=

"

type:'tag',size:'small',closable:false,click:'clickFn'

"

tagsdata

=

"

[{'label':'标签一'},{'label':'标签二'},{'label':'标签三'},{'label':'标签四'},{'label':'标签五'}]

"

>

</

div

>

</

div

>

</

div

>

3、小尺寸

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

mini

"

class

=

"

comp

"

comp

=

"

type:'tag',size:'mini',closable:false,click:'clickFn'

"

tagsdata

=

"

[{'label':'标签一'},{'label':'标签二'},{'label':'标签三'},{'label':'标签四'},{'label':'标签五'}]

"

>

</

div

>

</

div

>

</

div

>

不同主题

Tag 组件提供了三个不同的主题：dark、 plain和 light（默认light可不传）

<

div

id

=

"

effectDark

"

class

=

"

comp

"

comp

=

"

type:'tag',effect:'dark',closable:false,click:'clickFn'

"

tagsdata

=

"

[{label:'标签一'},{label:'标签二',type:'success'},{label:'标签三',type:'info'},{label:'标签四',type:'warning'},{label:'标签五',type:'danger'}]

"

>

</

div

>

<

br

>

<

div

id

=

"

effectPlain

"

class

=

"

comp

"

comp

=

"

type:'tag',effect:'plain',closable:false,click:'clickFn'

"

tagsdata

=

"

[{label:'标签一'},{label:'标签二',type:'success'},{label:'标签三',type:'info'},{label:'标签四',type:'warning'},{label:'标签五',type:'danger'}]

"

>

</

div

>

渲染方式

1、通过comp方式渲染

通过comp的方式的渲染, click和close仅支持传入字符串，且指向本窗口的全局函数

<

div

id

=

"

tagsObj_comp

"

class

=

"

comp

"

comp

=

"

type:'tag',closable:true,click:'clickFn'

"

tagsdata

=

"

[{label:'标签一'},{label:'标签二'},{label:'标签三'}]

"

>

</

div

>

2、通过对象渲染

通过new的方式的渲染, click和close除开支持传入字符串的全局函数，还支持function

var tagsObj_new = new CtpUiComTag($("#tagsObj_new").get(0),{
closable:true,
click:"clickFn",
close:function(_obj){
alert("this is a close function，你删除了【"+ _obj.parentNode.innerText +"】");
},
tagsdata:[{'label':'标签一'},{'label':'标签二'},{'label':'标签三'}]
});

<

div

id

=

"

tagsObj_new

"

>

</

div

>

<

script

>

var

tagsObj_new

=

new

CtpUiComTag

(

$

(

"#tagsObj_new"

)

.

get

(

0

)

,

{

closable

:

true

,

click

:

"clickFn"

,

close

:

function

(

_obj

)

{

alert

(

"this is a close function，你删除了【"

+

_obj

.

parentNode

.

innerText

+

"】"

)

;

}

,

tagsdata

:

[

{

'label'

:

'标签一'

}

,

{

'label'

:

'标签二'

}

,

{

'label'

:

'标签三'

}

]

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

size

-

尺寸

string

small / mini

—

closable

-

是否可关闭

boolean

true

false

dynamicTags

-

动态编辑

boolean

true

false

effect

-

主题

string

dark / plain / light

light

tagsdata

label

标签文字

string

—

type

类型

string

success/info/warning/danger

—

事件列表

事件名称

说明

类型

click

点击 Tag 时触发的事件

string / function(仅限new方式下有效)

close

关闭 Tag 时触发的事件

string / function(仅限new方式下有效)

## 41. TreeGrid 树形列表

> 原始路径：`/components4.0/data/treeGrid.html`  
> 相对路径：`components4.0/data/treeGrid.md`  
> 页面 key：`v-1d3abe9a`  
> JS Chunk：`80.a74eca11.js`

TreeGrid 树形列表

var testData = {
column: {
"Name": "版本名称",
"BuildId": "构建版本",
"ReleaseData": "发布日期"
},
"children": [
{
"Name": "V6.0",
"BuildId": "-",
"ReleaseData": "2016-06-30",
"children": [
{
"Name": "V6.0SP1",
"BuildId": "-",
"ReleaseData": "2016-09-30"
}
]
},
{
"Name": "V6.1",
"BuildId": "-",
"ReleaseData": "2017-05-30",
"children": [
{
"Name": "V6.1SP1",
"BuildId": "-",
"ReleaseData": "2017-08-15"
},
{
"Name": "V6.1SP2",
"BuildId": "B171110.77.CTP76869",
"ReleaseData": "2017-10-30"
}
]
},
{
"Name": "V7.0",
"BuildId": "B180601.6756.CTP105743",
"ReleaseData": "2018-04-30",
"expanded": false,
"children": [
{
"Name": "V7.0SP1",
"BuildId": "B180814.7024.CTP112688",
"ReleaseData": "2018-07-30"
},
{
"Name": "V7.0SP2",
"BuildId": "-",
"ReleaseData": "-",
"children": [
{
"Name": "V7.0SP2 10月版",
"BuildId": "B181008,7183.CTP117098",
"ReleaseData": "2018-10-08"
},
{
"Name": "V7.0SP2 11月版",
"BuildId": "B181101.7183.CTP117098",
"ReleaseData": "2018-11-01"
}
]
},
{
"Name": "V7.0SP3",
"BuildId": "B190701.9923.CTP145985",
"ReleaseData": "2018-11-30",
}
]
},
{
"Name": "V7.1",
"BuildId": "-",
"ReleaseData": "-",
"expanded": false,
"children": [
{
"Name": "V7.1 430版",
"BuildId": "B190505.9923.CTP145985",
"ReleaseData": "2019-04-30"
},
{
"Name": "V7.1 530版",
"BuildId": "B190701.9923.CTP145985",
"ReleaseData": "2019-05-30"
},
{
"Name": "V7.1SP1",
"BuildId": "-",
"ReleaseData": "-",
"children": [
{
"Name": "V7.1SP1 830版",
"BuildId": "B190902.682.CTP160958",
"ReleaseData": "2019-09-02"
},
{
"Name": "V7.1SP1 930版",
"BuildId": "B191010.91.CTP164920",
"ReleaseData": "2019-09-10"
}
]
}
]
}
]
}
var tese1 = new CtpUiTreeGrid("#demo1", testData);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo1

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData

=

{

column

:

{

"Name"

:

"版本名称"

,

"BuildId"

:

"构建版本"

,

"ReleaseData"

:

"发布日期"

}

,

"children"

:

[

{

"Name"

:

"V6.0"

,

"BuildId"

:

"-"

,

"ReleaseData"

:

"2016-06-30"

,

"children"

:

[

{

"Name"

:

"V6.0SP1"

,

"BuildId"

:

"-"

,

"ReleaseData"

:

"2016-09-30"

}

]

}

,

{

"Name"

:

"V6.1"

,

"BuildId"

:

"-"

,

"ReleaseData"

:

"2017-05-30"

,

"children"

:

[

{

"Name"

:

"V6.1SP1"

,

"BuildId"

:

"-"

,

"ReleaseData"

:

"2017-08-15"

}

,

{

"Name"

:

"V6.1SP2"

,

"BuildId"

:

"B171110.77.CTP76869"

,

"ReleaseData"

:

"2017-10-30"

}

]

}

,

{

"Name"

:

"V7.0"

,

"BuildId"

:

"B180601.6756.CTP105743"

,

"ReleaseData"

:

"2018-04-30"

,

"expanded"

:

false

,

"children"

:

[

{

"Name"

:

"V7.0SP1"

,

"BuildId"

:

"B180814.7024.CTP112688"

,

"ReleaseData"

:

"2018-07-30"

}

,

{

"Name"

:

"V7.0SP2"

,

"BuildId"

:

"-"

,

"ReleaseData"

:

"-"

,

"children"

:

[

{

"Name"

:

"V7.0SP2 10月版"

,

"BuildId"

:

"B181008,7183.CTP117098"

,

"ReleaseData"

:

"2018-10-08"

}

,

{

"Name"

:

"V7.0SP2 11月版"

,

"BuildId"

:

"B181101.7183.CTP117098"

,

"ReleaseData"

:

"2018-11-01"

}

]

}

,

{

"Name"

:

"V7.0SP3"

,

"BuildId"

:

"B190701.9923.CTP145985"

,

"ReleaseData"

:

"2018-11-30"

,

}

]

}

,

{

"Name"

:

"V7.1"

,

"BuildId"

:

"-"

,

"ReleaseData"

:

"-"

,

"expanded"

:

false

,

"children"

:

[

{

"Name"

:

"V7.1 430版"

,

"BuildId"

:

"B190505.9923.CTP145985"

,

"ReleaseData"

:

"2019-04-30"

}

,

{

"Name"

:

"V7.1 530版"

,

"BuildId"

:

"B190701.9923.CTP145985"

,

"ReleaseData"

:

"2019-05-30"

}

,

{

"Name"

:

"V7.1SP1"

,

"BuildId"

:

"-"

,

"ReleaseData"

:

"-"

,

"children"

:

[

{

"Name"

:

"V7.1SP1 830版"

,

"BuildId"

:

"B190902.682.CTP160958"

,

"ReleaseData"

:

"2019-09-02"

}

,

{

"Name"

:

"V7.1SP1 930版"

,

"BuildId"

:

"B191010.91.CTP164920"

,

"ReleaseData"

:

"2019-09-10"

}

]

}

]

}

]

}

var

tese1

=

new

CtpUiTreeGrid

(

"#demo1"

,

testData

)

;

</

script

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

options

checkbox

是否显示复选按钮（选填）

Boolean

true

column

需要显示的列的key，和children中的key相对应

由String组成的Array

children(数组类型，由多个Object组成)

expanded

子级数据是否展开的（选填）

Boolean

true

自定义key

单元格的数据，key和column中的值相对应（必填）

string

方法列表

方法

说明

参数

destory

销毁元素

-

## 42. Attachment 全屏拖拽上传组件

> 原始路径：`/components4.0/form/attachment.html`  
> 相对路径：`components4.0/form/attachment.md`  
> 页面 key：`v-7229c713`  
> JS Chunk：`81.0876aca1.js`

Attachment 全屏拖拽上传组件

普通全屏拖拽上传组件

一个页面只能有一个这个组件 多个事件会冲突

new CtpUiUploadFullScreenDrag(document.getElementById("upload"),{
dragDomWidth:'83.33333333%',
dragDomLeft:'16.66666667%',
maxSize: 10,
fileExtensions: 'zip'
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

upload

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiUploadFullScreenDrag

(

document

.

getElementById

(

"upload"

)

,

{

dragDomWidth

:

'83.33333333%'

,

dragDomLeft

:

'16.66666667%'

,

maxSize

:

10

,

fileExtensions

:

'zip'

}

)

;

</

script

>

与toolbar 组件的特殊生成

var toolbar = $("#toolbar").toolbar({
toolbar: [/*{
id: "insertAttachment",
name: "点击上次",
click:function(){
// addEditAttachment();
},
initToolBtnCallBack:function(){
var dom = document.getElementById("insertAttachment_a");
if(dom){
dom.innerHTML = '';
new CtpUiUploadFullScreenDrag(dom,{
isDrag:false,
isShowMaxSize:false,
width:'70px',
text:"上传新文件",
callMethod:function(){

},
uploadFullScreenDragStyle:'text-align: left;height:26px;line-height:26px;'
})
}

}
},*/{
id: "quoteMyDocument",
name: "子菜单有上传",
showCallBack:function(){
if(window.operate_edit_ctpUIFull){
window.operate_edit_ctpUIFull.destory();
}
window.operate_edit_ctpUIFull = new CtpUiUploadFullScreenDrag(document.getElementById('quoteMyDocument_subMenu_a').parentNode,{
isDrag:false,
isShowMaxSize:false,
width:'50px',
text:'上传组件',
callMethod:function(){

},
poi:'xsn1',
filesNum:1,
className:'order_menuitem',
fileExtensions:'xsn',
isNotAddAttr:true,
beforeCallbackFucAsyn:function(fuc1,fuc2){
setTimeout(function() {
if(true){
fuc1();
}else{
fuc2();
}
}, 1000)
},
UFSDiconStyle:'display:none;',
uploadFullScreenDragStyle:'text-align: left;height:16px;line-height:16px;'
});
document.getElementById('quoteMyDocument_subMenu_a').style.display='none';
},
subMenu:[
{
name:'aaa_aaa',
click:function(){

},
id:'quoteMyDocument_subMenu'
}
]
}]
});

<

div

id

=

"

toolbar

"

>

</

div

>

<

script

>

var

toolbar

=

$

(

"#toolbar"

)

.

toolbar

(

{

toolbar

:

[

/*{
id: "insertAttachment",
name: "点击上次",
click:function(){
// addEditAttachment();
},
initToolBtnCallBack:function(){
var dom = document.getElementById("insertAttachment_a");
if(dom){
dom.innerHTML = '';
new CtpUiUploadFullScreenDrag(dom,{
isDrag:false,
isShowMaxSize:false,
width:'70px',
text:"上传新文件",
callMethod:function(){

},
uploadFullScreenDragStyle:'text-align: left;height:26px;line-height:26px;'
})
}

}
},*/

{

id

:

"quoteMyDocument"

,

name

:

"子菜单有上传"

,

showCallBack

:

function

(

)

{

if

(

window

.

operate_edit_ctpUIFull

)

{

window

.

operate_edit_ctpUIFull

.

destory

(

)

;

}

window

.

operate_edit_ctpUIFull

=

new

CtpUiUploadFullScreenDrag

(

document

.

getElementById

(

'quoteMyDocument_subMenu_a'

)

.

parentNode

,

{

isDrag

:

false

,

isShowMaxSize

:

false

,

width

:

'50px'

,

text

:

'上传组件'

,

callMethod

:

function

(

)

{

}

,

poi

:

'xsn1'

,

filesNum

:

1

,

className

:

'order_menuitem'

,

fileExtensions

:

'xsn'

,

isNotAddAttr

:

true

,

beforeCallbackFucAsyn

:

function

(

fuc1

,

fuc2

)

{

setTimeout

(

function

(

)

{

if

(

true

)

{

fuc1

(

)

;

}

else

{

fuc2

(

)

;

}

,

1000

)

}

,

UFSDiconStyle

:

'display:none;'

,

uploadFullScreenDragStyle

:

'text-align: left;height:16px;line-height:16px;'

}

)

;

document

.

getElementById

(

'quoteMyDocument_subMenu_a'

)

.

style

.

display

=

'none'

;

}

,

subMenu

:

[

{

name

:

'aaa_aaa'

,

click

:

function

(

)

{

}

,

id

:

'quoteMyDocument_subMenu'

}

]

}

]

}

)

;

</

script

>

采用comp方式渲染

普通全屏拖拽上传组件

<

div

id

=

"

upload1

"

class

=

"

sliderBGstyle comp

"

comp

=

"

type:'CtpUiUploadFullScreenDrag',disabled:true,maxSize: 10, fileExtensions: 'zip'

"

>

</

div

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

-

options

参数配置

Object

width

宽度(带单位)

String

150px

id

String

disabled

是否已禁用

Boolean

false

dragDomWidth

拖拽确认框的宽度

Stirng

100%

dragDomTop

拖拽确认框的Top

Stirng

不填写默认上下居中

dragDomBottom

拖拽确认框的Bottom

Stirng

不填写默认上下居中 不能与dragDomTop一起使用

dragDomLeft

拖拽确认框的Left

Stirng

0px

dragDomRight

拖拽确认框的Right

Stirng

auto

maxSize

最大上传文件一共大小（M）

Number

100

_ctxPath

根路径

String

/seeyon

extensions

扩展名

String

isEncrypt

是否加密

String

false

fileType

文件类型

String

0

isShowMaxSize

是否显示最大上传大小

boolean

true

isDrag

是否支持拖动上传

boolean

true

poi

对应附件展示ID同老组件

String

Att

uploadFullScreenDragStyle

最外层样式

String

UFSDcontentStyle

文字样式

String

text

自定义文字

String

上传附件

UFSDiconStyle

图标样式

String

beforeCallbackFuc

上传之前回调 返回true 继续下去 返回false 终止上传

Function

beforeCallbackFucAsyn

上传之前异步回调 自带2个参数fuc1 fuc2 运行这个fuc1代表继续上传 运行fuc2代表终止上传

Function

callMethod

老的回调方式附件创建完成后callMethod

Function

isNotAddAttr

是否不执行 添加附件操作 insertAttachmentPoi/insertAttachment

boolean

false

isInsertAttachment

是否采用insertAttachment 上传附件

boolean

false 默认采用insertAttachmentPoi

filesNum

一次上传文件个数 不传就是不限制

Number

默认不限制

fileExtensions

上传文件类型限制 不传就是不限制 多个,分隔

String

默认不限制

firstSave

是否后端默认存储

boolean

false

callbackFuc

上传成功的回调 自带文件信息

Function

方法列表

方法名

说明

参数

destory

销毁控件

## 43. Calendar 日历

> 原始路径：`/components4.0/form/calendar.html`  
> 相对路径：`components4.0/form/calendar.md`  
> 页面 key：`v-9fafe69a`  
> JS Chunk：`30.bfa4b47c.js`

Calendar 日历

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiCalendarObj");方式来获取对象

【采用comp方式渲染】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiCalendarObj',containerId:'mainPage',ifFormat:'%Y-%M-%d %H:%m',hasIcon:true,showsTime:false

"

/>

</

div

>

</

div

>

</

div

>

【采用input对象方式渲染】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

type

=

"

text

"

id

=

"

calendar

"

autocomplete

=

"

off

"

class

=

"

validate comp

"

name

=

"

address

"

placeholder

=

"

请选择日期

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:50

"

/>

</

div

>

</

div

>

</

div

>

【采用div对象方式渲染,直接展示在页面上】

var calendarObject2 = new CtpUiCalendarObj("calendarHere",null,{});
calendarObject2.show();

<

div

class

=

"

clearfix

"

>

<

div

id

=

"

calendarHere

"

style

=

"

position

:

relative

;

height

:

250px

;

margin-top

:

20px

;

"

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

calendarObject2

=

new

CtpUiCalendarObj

(

"calendarHere"

,

null

,

{

}

)

;

calendarObject2

.

show

(

)

;

</

script

>

【采用comp方式渲染,选择年】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiCalendarObj',hasIcon:true,containerId:'mainPage',pattern:'year'

"

/>

</

div

>

</

div

>

</

div

>

【采用对象方式渲染,选择年】

由input渲染

var calendarObject = new CtpUiCalendarObj(["yearCtl"],null,{hasIcon:true,pattern:'year'});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

yearCtl

"

type

=

"

text

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

calendarObject

=

new

CtpUiCalendarObj

(

[

"yearCtl"

]

,

null

,

{

hasIcon

:

true

,

pattern

:

'year'

}

)

;

</

script

>

【采用comp方式渲染,选择月】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiCalendarObj',containerId:'mainPage',hasIcon:true,pattern:'month'

"

/>

</

div

>

</

div

>

</

div

>

【采用对象方式渲染,选择月】

由input渲染

var calendarObject = new CtpUiCalendarObj(["monthCtl"],null,{hasIcon:true,pattern:'month'});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

monthCtl

"

type

=

"

text

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

calendarObject

=

new

CtpUiCalendarObj

(

[

"monthCtl"

]

,

null

,

{

hasIcon

:

true

,

pattern

:

'month'

}

)

;

</

script

>

CtpUiCalendarObj 日历参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiCalendarObj

pattern

展示类型

string

date/year/month

date

ifFormat

日期格式

string

%Y-%m-%d %H:%i

twoInput

是否生成2个输入框

boolean

false/true

false

方法列表

方法名

说明

参数 1

参数 2

hide

隐藏日历

show

显示日历

setDate

设置日期

date对象

initDate

初始化日期方法

date对象

setErrorState

设置错误提醒信息

错误内容，例子 mycalObj.setErrorState("错误发生了");

clearErrorState

清空错误提示信息

setDisabled

设置日历不可以操作

例子 mycalObj.setDisabled(true);

attachEvent

注册方法

eventName[方法名]

fun[回调函数]

detachEvent

销毁方法

eventName[方法名]

destory

销毁组件

var calendarObject = new CtpUiCalendarObj(["calendar"],null,{hasIcon:true});
//设置日期的方式
calendarObject.setDate(new Date(2011,5,8));
calendarObject.setDate("2011-06-08"); // 如果采用字符串的话 相应初始化的时候设置了ifFormat 为"%Y-%M-%d"

<

script

type

=

"

text/javascript

"

>

var

calendarObject

=

new

CtpUiCalendarObj

(

[

"calendar"

]

,

null

,

{

hasIcon

:

true

}

)

;

//设置日期的方式

calendarObject

.

setDate

(

new

Date

(

2011

,

5

,

8

)

;

calendarObject

.

setDate

(

"2011-06-08"

)

;

// 如果采用字符串的话 相应初始化的时候设置了ifFormat 为"%Y-%M-%d"

</

script

>

event事件列表

eventName

参数 1

参数2

onClick

date

onBeforeChange

date

onChange

date

state

var calendarObject = new CtpUiCalendarObj(["calendar"],null,{hasIcon:true});
//设置日期的方式
calendarObject.attachEvent("onChange",function(date, state){
alert("数据变化成 "+date)
})


calendarObject.attachEvent("onBeforeChange",function(date){
alert("修改前的值 "+date)
})

calendarObject.attachEvent("onClick",function(date){
alert("点击选中的值 "+date)
})

<

script

type

=

"

text/javascript

"

>

var

calendarObject

=

new

CtpUiCalendarObj

(

[

"calendar"

]

,

null

,

{

hasIcon

:

true

}

)

;

//设置日期的方式

calendarObject

.

attachEvent

(

"onChange"

,

function

(

date

,

state

)

{

alert

(

"数据变化成 "

+

date

)

}

)

calendarObject

.

attachEvent

(

"onBeforeChange"

,

function

(

date

)

{

alert

(

"修改前的值 "

+

date

)

}

)

calendarObject

.

attachEvent

(

"onClick"

,

function

(

date

)

{

alert

(

"点击选中的值 "

+

date

)

}

)

</

script

>

## 44. Calendar 时间段选择

> 原始路径：`/components4.0/form/calendarRange.html`  
> 相对路径：`components4.0/form/calendarRange.md`  
> 页面 key：`v-ba1be3ce`  
> JS Chunk：`31.2c6d8f3f.js`

Calendar 时间段选择

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。

【采用comp方式渲染,选择时间段，2个输入框】

doubleDateDiv

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

doubleDateDiv

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiDateRange',containerId:'mainPage',twoInput:true,hasIcon:true,pattern:'dateRange'

"

/>

</

div

>

</

div

>

</

div

>

【采用comp方式渲染,选择时间段，单个输入框】

doubleDateDiv

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

doubleDateDiv

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiDateRange',containerId:'mainPage',hasIcon:true,pattern:'dateRange'

"

/>

</

div

>

</

div

>

</

div

>

【采用comp方式渲染,选择时间段，2个输入框,带时分选择】

doubleDateDiv

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

doubleDateDiv

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiDateRange',containerId:'mainPage',ifFormat:'%Y-%m-%d %H:%i',twoInput:true,hasIcon:true,pattern:'dateRange'

"

/>

</

div

>

</

div

>

</

div

>

【采用对象方式渲染,选择时间段】

doubleDateDiv

var doubleDateDiv = new CtpUiDateRange("doubleDateDiv", {twoInput: true, hasIcon: true, type: "date"});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

label

"

>

doubleDateDiv

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

250px

"

>

<

input

type

=

"

text

"

autocomplete

=

"

off

"

id

=

"

doubleDateDiv

"

name

=

"

name_text

"

value

=

"

class

=

"

validate msHideClear

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

doubleDateDiv

=

new

CtpUiDateRange

(

"doubleDateDiv"

,

{

twoInput

:

true

,

hasIcon

:

true

,

type

:

"date"

}

)

;

</

script

>

CtpUiDateRange 日历参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiDateRange

pattern

展示类型

string

date/year/month

date

ifFormat

日期格式

string

%Y-%m-%d %H:%i

传入了时分的时候才可以选择时、分钟没有传默认不显示

%Y-%m-%d

twoInput

是否生成2个输入框

boolean

false/true

false

方法列表

方法名

说明

参数 1

参数 2

setDateValues

设置开始、结束时间

doubleDateDiv.setDateValues({startDate:'2019-11-28 10:30',endDate:'2019-12-28 10:30'});

getDateValues

获取开始、结束时间

doubleDateDiv.getDateValues();返回格式为：{startDate:'2019-11-28 10:30',endDate:'2019-12-28 10:30'}

getStartDate

获取开始时间

getEndDate

获取结束时间

setErrorState

设置错误提醒信息

错误内容，例子 mycalObj.setErrorState("错误发生了");

clearErrorState

清空错误提示信息

setDisabled

设置日历不可以操作

例子 mycalObj.setDisabled(true);

attachEvent

注册方法

eventName[方法名]

fun[回调函数]

detachEvent

销毁方法

eventName[方法名]

destory

销毁组件

var calendarObject = new CtpUiDateRange(["calendar"],null,{hasIcon:true});
//设置日期的方式
calendarObject.setDate(new Date(2011,5,8));
calendarObject.setDate("2011-06-08"); // 如果采用字符串的话 相应初始化的时候设置了ifFormat 为"%Y-%M-%d"

<

script

type

=

"

text/javascript

"

>

var

calendarObject

=

new

CtpUiDateRange

(

[

"calendar"

]

,

null

,

{

hasIcon

:

true

}

)

;

//设置日期的方式

calendarObject

.

setDate

(

new

Date

(

2011

,

5

,

8

)

;

calendarObject

.

setDate

(

"2011-06-08"

)

;

// 如果采用字符串的话 相应初始化的时候设置了ifFormat 为"%Y-%M-%d"

</

script

>

event事件列表

eventName

参数 1

参数2

onClick

date

onBeforeChange

date

onChange

date

state

var calendarObject = new CtpUiDateRange(["calendar"],null,{hasIcon:true});
//设置日期的方式
calendarObject.attachEvent("onChange",function(date, state){
alert("数据变化成 "+date)
})


calendarObject.attachEvent("onBeforeChange",function(date){
alert("修改前的值 "+date)
})

calendarObject.attachEvent("onClick",function(date){
alert("点击选中的值 "+date)
})

<

script

type

=

"

text/javascript

"

>

var

calendarObject

=

new

CtpUiDateRange

(

[

"calendar"

]

,

null

,

{

hasIcon

:

true

}

)

;

//设置日期的方式

calendarObject

.

attachEvent

(

"onChange"

,

function

(

date

,

state

)

{

alert

(

"数据变化成 "

+

date

)

}

)

calendarObject

.

attachEvent

(

"onBeforeChange"

,

function

(

date

)

{

alert

(

"修改前的值 "

+

date

)

}

)

calendarObject

.

attachEvent

(

"onClick"

,

function

(

date

)

{

alert

(

"点击选中的值 "

+

date

)

}

)

</

script

>

## 45. Cascader 级联选择器

> 原始路径：`/components4.0/form/cascader.html`  
> 相对路径：`components4.0/form/cascader.md`  
> 页面 key：`v-593eacb3`  
> JS Chunk：`32.138b3869.js`

Cascader 级联选择器

1、基础用法--采用input+comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_comSelect");方式来获取对象

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

name_text41

"

name

=

"

name_text1

"

value

=

"

Beijing

"

class

=

"

comp

"

comp

=

"

type:'CtpUiCascadeSelect',containerId:'mainPage',options:[{value: 'Beijing',label: '北京',children:[
{value: 'zhinan',label: '指南'},
{value: 'zhinan1',label: '指南1',children:[
{value: 'zhinan111',label: '指南111'},
{value: 'zhinan1222',label: '指南1222'}
]}
]}
,{value: 'Beijing2',label: '北京2'},{value: 'Beijing3',label: '北京3',children:[{value: 'zhinan11',label: '指南11'},{value: 'zhinan122',label: '指南122'}]}]

"

>

</

div

>

</

div

>

</

div

>

基础用法--采用input+对象方式渲染

采用input+对象

var ctpUiComSelect = new CtpUiCascadeSelect($("#name_text411").get(0), {
containerId: "mainPage",
options: [{
value: 'Beijing', label: '北京', children: [
{value: 'zhinan', label: '指南'},
{
value: 'zhinan1', label: '指南1', children: [
{value: 'zhinan111', label: '指南111'},
{value: 'zhinan1222', label: '指南1222'}
]
}
]
}
, {value: 'Beijing2', label: '北京2'}
, {
value: 'Beijing3', label: '北京3', children: [
{value: 'zhinan11', label: '指南11'},
{value: 'zhinan122', label: '指南122'}
]
}]
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

采用input+对象

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

name_text411

"

name

=

"

name_text411

"

value

=

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

ctpUiComSelect

=

new

CtpUiCascadeSelect

(

$

(

"#name_text411"

)

.

get

(

0

)

,

{

containerId

:

"mainPage"

,

options

:

[

{

value

:

'Beijing'

,

label

:

'北京'

,

children

:

[

{

value

:

'zhinan'

,

label

:

'指南'

}

,

{

value

:

'zhinan1'

,

label

:

'指南1'

,

children

:

[

{

value

:

'zhinan111'

,

label

:

'指南111'

}

,

{

value

:

'zhinan1222'

,

label

:

'指南1222'

}

]

}

]

}

,

{

value

:

'Beijing2'

,

label

:

'北京2'

}

,

{

value

:

'Beijing3'

,

label

:

'北京3'

,

children

:

[

{

value

:

'zhinan11'

,

label

:

'指南11'

}

,

{

value

:

'zhinan122'

,

label

:

'指南122'

}

]

}

]

}

)

;

</

script

>

基础用法--radio 选择任意一级选项

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

name_text412

"

name

=

"

name_text412

"

value

=

"

Beijing

"

class

=

"

comp

"

comp

=

"

type:'CtpUiCascadeSelect',containerId:'mainPage',radio:true,options:[{value: 'Beijing',label: '北京',children:[
{value: 'zhinan',label: '指南'},
{value: 'zhinan1',label: '指南1',children:[
{value: 'zhinan111',label: '指南111'},
{value: 'zhinan1222',label: '指南1222'}
]}
]}
,{value: 'Beijing2',label: '北京2'},{value: 'Beijing3',label: '北京3',children:[{value: 'zhinan11',label: '指南11'},{value: 'zhinan122',label: '指南122'}]}]

"

>

</

div

>

</

div

>

</

div

>

基础用法--checkbox 级联多选

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

name_text4122

"

name

=

"

name_text4122

"

value

=

"

Beijing

"

class

=

"

comp

"

comp

=

"

type:'CtpUiCascadeSelect',containerId:'mainPage',multiple:true,options:[{value: 'Beijing',label: '北京',children:[
{value: 'zhinan',label: '指南'},
{value: 'zhinan1',label: '指南1',children:[
{value: 'zhinan111',label: '指南111'},
{value: 'zhinan1222',label: '指南1222'}
]}
]}
,{value: 'Beijing2',label: '北京2'}
,{value: 'Beijing3',label: '北京3',children:[
{value: 'zhinan11',label: '指南11'},
{value: 'zhinan122',label: '指南122'}
]}]

"

>

</

div

>

</

div

>

</

div

>

参数列表

参数

--------

说明

类型

可选值

默认值

type

--------

控件类型

string

CtpUiCascadeSelect

options

--------

下拉值集

Array

自定义

[itemJson]

----------

value

下拉项对应的值

string

自定义

----------

children

下拉子项

itemJson

自定义

----------

label

下拉项显示的label

string

自定义

disabled

--------

是否可以编辑

boolean

false/true

false

radio

--------

是否可以单选任意项

boolean

false/true

false

multiple

--------

是否可以多选

boolean

false/true

false

containerId

--------

出现滚动条的容器，如果是body出现滚动条则不需要该参数

string

自定义

方法列表

方法名

说明

参数 1

参数 2

getSelValue

获取选中的值

getSelText

获取选中的Text值

attachEvent

注册方法

eventName[方法名]

fun[回调函数]

detachEvent

销毁方法

eventName[方法名]

事件调用例子

dropdown.attachEvent("click", function(value, text){

// your code here

return true;

});

event事件列表

eventName

参数 1

参数2

click

value [选项的value]

text[选项的text]

afterInit

## 46. Checkbox 多选框

> 原始路径：`/components4.0/form/checkbox.html`  
> 相对路径：`components4.0/form/checkbox.md`  
> 页面 key：`v-76517953`  
> JS Chunk：`33.20f7deb7.js`

Checkbox 多选框

一组备选项中进行多选。

基础样式

选项1

选项2

选项3

选项4（disabled）

选项5（disabled）

扩展选项

扩展选项（disabled）

<

span

class

=

"

skin-checkbox

"

>

<

input

type

=

"

checkbox

"

value

=

"

1

"

id

=

"

Checkbox11

"

name

=

"

option1

"

checked

>

<

label

for

=

"

Checkbox11

"

class

=

"

>

<

i

>

</

i

>

</

label

>

选项1

</

span

>

<

span

class

=

"

skin-checkbox

"

>

<

input

type

=

"

checkbox

"

value

=

"

2

"

id

=

"

Checkbox12

"

name

=

"

option1

"

>

<

label

for

=

"

Checkbox12

"

class

=

"

>

<

i

>

</

i

>

</

label

>

选项2

</

span

>

<

span

class

=

"

skin-checkbox

"

>

<

input

type

=

"

checkbox

"

value

=

"

3

"

id

=

"

Checkbox13

"

name

=

"

option1

"

>

<

label

for

=

"

Checkbox13

"

class

=

"

>

<

i

>

</

i

>

</

label

>

选项3

</

span

>

<

span

class

=

"

skin-checkbox

"

>

<

input

type

=

"

checkbox

"

value

=

"

4

"

id

=

"

Checkbox14

"

name

=

"

option1

"

disabled

checked

>

<

label

for

=

"

Checkbox14

"

class

=

"

>

<

i

>

</

i

>

</

label

>

选项4（disabled）

</

span

>

<

span

class

=

"

skin-checkbox

"

>

<

input

type

=

"

checkbox

"

value

=

"

5

"

id

=

"

Checkbox15

"

name

=

"

option1

"

disabled

>

<

label

for

=

"

Checkbox15

"

class

=

"

>

<

i

>

</

i

>

</

label

>

选项5（disabled）

</

span

>

<

span

class

=

"

skin-checkbox isIndeterminate

"

>

<

input

type

=

"

checkbox

"

value

=

"

6

"

id

=

"

Checkbox16

"

name

=

"

option1

"

>

<

label

for

=

"

Checkbox16

"

class

=

"

>

<

i

>

</

i

>

</

label

>

扩展选项

</

span

>

<

span

class

=

"

skin-checkbox isIndeterminate

"

>

<

input

type

=

"

checkbox

"

value

=

"

7

"

id

=

"

Checkbox17

"

name

=

"

option1

"

disabled

>

<

label

for

=

"

Checkbox17

"

class

=

"

>

<

i

>

</

i

>

</

label

>

扩展选项（disabled）

</

span

>

扩展样式

① 按钮样式

按钮样式的复选组合。

采用对象方式渲染

//按钮式复选：对象方式渲染
var testData1 = {
styleType: "button",
name: "N1",
item: [{
id: "R1",
label: "选项1",
value: "V1",
checked: true,
disabled: false,
className: "",
style: "",
clickFun: function() {
$.alert("我是点击后触发的自定义事件");
}
},{
id: "R2",
label: "选项2",
value: "V2"
},{
id: "R3",
label: "选项3",
value: "V3",
checked: true
},{
id: "R4",
label: "选项4",
value: "V4"
},{
id: "R5",
label: "选项5",
value: "V5",
checked: true
},{
id: "R6",
label: "选项6",
value: "V6"
}]
};
var test1 = new CtpUicomCheckbox("#btnCheck-demoDiv1",testData1);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnCheck-demoDiv1

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//按钮式复选：对象方式渲染

var

testData1

=

{

styleType

:

"button"

,

name

:

"N1"

,

item

:

[

{

id

:

"R1"

,

label

:

"选项1"

,

value

:

"V1"

,

checked

:

true

,

disabled

:

false

,

className

:

""

,

style

:

""

,

clickFun

:

function

(

)

{

$

.

alert

(

"我是点击后触发的自定义事件"

)

;

}

,

{

id

:

"R2"

,

label

:

"选项2"

,

value

:

"V2"

}

,

{

id

:

"R3"

,

label

:

"选项3"

,

value

:

"V3"

,

checked

:

true

}

,

{

id

:

"R4"

,

label

:

"选项4"

,

value

:

"V4"

}

,

{

id

:

"R5"

,

label

:

"选项5"

,

value

:

"V5"

,

checked

:

true

}

,

{

id

:

"R6"

,

label

:

"选项6"

,

value

:

"V6"

}

]

}

;

var

test1

=

new

CtpUicomCheckbox

(

"#btnCheck-demoDiv1"

,

testData1

)

;

</

script

>

采用comp的方式渲染

选项1

选项2

选项3

选项4

选项5

选项6

<

div

id

=

"

checkboxCompDemo3

"

class

=

"

comp

"

comp

=

"

type:'CtpUiCheckbox',styleType:'button'

"

>

<

ul

class

=

"

ctpUiCheckbox_button

"

>

<

li

>

<

span

class

=

"

checkSquare

"

>

</

span

>

<

input

type

=

"

checkbox

"

name

=

"

N3

"

id

=

"

R5

"

value

=

"

V5

"

checked

=

"

/>

<

label

>

选项1

</

label

>

</

li

>

<

li

>

<

span

class

=

"

checkSquare

"

>

</

span

>

<

input

type

=

"

checkbox

"

name

=

"

N3

"

id

=

"

R6

"

value

=

"

V6

"

/>

<

label

>

选项2

</

label

>

</

li

>

<

li

>

<

span

class

=

"

checkSquare

"

>

</

span

>

<

input

type

=

"

checkbox

"

name

=

"

N3

"

id

=

"

R7

"

value

=

"

V7

"

checked

=

"

/>

<

label

>

选项3

</

label

>

</

li

>

<

li

>

<

span

class

=

"

checkSquare

"

>

</

span

>

<

input

type

=

"

checkbox

"

name

=

"

N3

"

id

=

"

R8

"

value

=

"

V8

"

/>

<

label

>

选项4

</

label

>

</

li

>

<

li

>

<

span

class

=

"

checkSquare

"

>

</

span

>

<

input

type

=

"

checkbox

"

name

=

"

N3

"

id

=

"

R9

"

value

=

"

V9

"

/>

<

label

>

选项5

</

label

>

</

li

>

<

li

>

<

span

class

=

"

checkSquare

"

>

</

span

>

<

input

type

=

"

checkbox

"

name

=

"

N3

"

id

=

"

R10

"

value

=

"

V10

"

disabled

=

"

disabled

"

/>

<

label

>

选项6

</

label

>

</

li

>

</

ul

>

</

div

>

② 小图片样式

小图片样式的复选组合。

//小图片
var testData3 = {
styleType: "smallImg",
name: "T3",
item: [{
id: "T31",
label: "图片1",
value: "V31",
img: "http://open.seeyon.com/seeyonui/images/1.jpg"
},{
id: "T32",
label: "图片2",
value: "V32",
img: "http://open.seeyon.com/seeyonui/images/2.jpg"
},{
id: "T33",
label: "图片3",
value: "V33",
img: "http://open.seeyon.com/seeyonui/images/3.jpg",
checked: true,
disabled: true
},{
id: "T34",
label: "图片4",
value: "V34",
img: "http://open.seeyon.com/seeyonui/images/4.jpg",
disabled: true
}]
}
var test3 = new CtpUicomCheckbox("#btnCheck-demoDiv3",testData3);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnCheck-demoDiv3

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//小图片

var

testData3

=

{

styleType

:

"smallImg"

,

name

:

"T3"

,

item

:

[

{

id

:

"T31"

,

label

:

"图片1"

,

value

:

"V31"

,

img

:

"http://open.seeyon.com/seeyonui/images/1.jpg"

}

,

{

id

:

"T32"

,

label

:

"图片2"

,

value

:

"V32"

,

img

:

"http://open.seeyon.com/seeyonui/images/2.jpg"

}

,

{

id

:

"T33"

,

label

:

"图片3"

,

value

:

"V33"

,

img

:

"http://open.seeyon.com/seeyonui/images/3.jpg"

,

checked

:

true

,

disabled

:

true

}

,

{

id

:

"T34"

,

label

:

"图片4"

,

value

:

"V34"

,

img

:

"http://open.seeyon.com/seeyonui/images/4.jpg"

,

disabled

:

true

}

]

}

var

test3

=

new

CtpUicomCheckbox

(

"#btnCheck-demoDiv3"

,

testData3

)

;

</

script

>

③ 图文列表样式

图文列表样式的复选组合。

//图文列表
var testData5 = {
styleType: "imageText",
name: "T5",
item: [{
id: "T51",
label: "图片1",
value: "V51",
img: "http://open.seeyon.com/seeyonui/images/1.jpg",
text: "北京致远互联软件股份有限公司（简称：致远互联）成立于2002年3月，专注于为组织级客户提供协同管理软件、解决方案和云服务，是集协同研究、软件研发、市场营销、渠道销售、支持服务于一体的协同管理全案服务商。",
checked: true
},{
id: "T52",
label: "图片2",
value: "V52",
img: "http://open.seeyon.com/seeyonui/images/2.jpg",
text: "作为中国协同管理软件及云服务领先厂商，致远互联17年一直专注在协同管理软件领域。多年来，致远互联秉承“以人为中心”的协同管理理念，形成了从私有云到公有云、从互联网到移动互联网、从产品到定制及增值服务、从工作协同到业务协同、从组织内协同到组织间协同再到社会化协同的完整产品线及解决方案。",
checked: false
},{
id: "T53",
label: "图片3",
value: "V53",
img: "http://open.seeyon.com/seeyonui/images/3.jpg",
text: "历经17年的发展，致远互联已先后走过单纯标准化产品化经营的V1.0阶段、协同解决方案和协同业务定制的V2.0阶段，现在，致远互联迈入了协同运营平台化发展的V3.0阶段，坚定助力企业“数字化升级”。",
checked: true
},{
id: "T54",
label: "图片4",
value: "V54",
img: "http://open.seeyon.com/seeyonui/images/4.jpg",
text: "每天，都有数万家政府机构及企业级用户、数百万个终端用户使用致远协同管理软件产品与服务。致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。",
checked: true,
disabled: true
},{
id: "T55",
label: "图片5",
value: "V55",
img: "http://open.seeyon.com/seeyonui/images/5.jpg",
text: "致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。",
checked: false,
disabled: true
}]
}
var test5 = new CtpUicomCheckbox("#btnCheck-demoDiv5",testData5);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnCheck-demoDiv5

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//图文列表

var

testData5

=

{

styleType

:

"imageText"

,

name

:

"T5"

,

item

:

[

{

id

:

"T51"

,

label

:

"图片1"

,

value

:

"V51"

,

img

:

"http://open.seeyon.com/seeyonui/images/1.jpg"

,

text

:

"北京致远互联软件股份有限公司（简称：致远互联）成立于2002年3月，专注于为组织级客户提供协同管理软件、解决方案和云服务，是集协同研究、软件研发、市场营销、渠道销售、支持服务于一体的协同管理全案服务商。"

,

checked

:

true

}

,

{

id

:

"T52"

,

label

:

"图片2"

,

value

:

"V52"

,

img

:

"http://open.seeyon.com/seeyonui/images/2.jpg"

,

text

:

"作为中国协同管理软件及云服务领先厂商，致远互联17年一直专注在协同管理软件领域。多年来，致远互联秉承“以人为中心”的协同管理理念，形成了从私有云到公有云、从互联网到移动互联网、从产品到定制及增值服务、从工作协同到业务协同、从组织内协同到组织间协同再到社会化协同的完整产品线及解决方案。"

,

checked

:

false

}

,

{

id

:

"T53"

,

label

:

"图片3"

,

value

:

"V53"

,

img

:

"http://open.seeyon.com/seeyonui/images/3.jpg"

,

text

:

"历经17年的发展，致远互联已先后走过单纯标准化产品化经营的V1.0阶段、协同解决方案和协同业务定制的V2.0阶段，现在，致远互联迈入了协同运营平台化发展的V3.0阶段，坚定助力企业“数字化升级”。"

,

checked

:

true

}

,

{

id

:

"T54"

,

label

:

"图片4"

,

value

:

"V54"

,

img

:

"http://open.seeyon.com/seeyonui/images/4.jpg"

,

text

:

"每天，都有数万家政府机构及企业级用户、数百万个终端用户使用致远协同管理软件产品与服务。致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。"

,

checked

:

true

,

disabled

:

true

}

,

{

id

:

"T55"

,

label

:

"图片5"

,

value

:

"V55"

,

img

:

"http://open.seeyon.com/seeyonui/images/5.jpg"

,

text

:

"致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。"

,

checked

:

false

,

disabled

:

true

}

]

}

var

test5

=

new

CtpUicomCheckbox

(

"#btnCheck-demoDiv5"

,

testData5

)

;

</

script

>

调用方式

var xxx = new CtpUicomCheckbox(elObj, options);

参数列表：

参数

说明

类型

默认值

elObj

-

被渲染的dom(必填项)

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

-

options（类型：object）(必填项)

styleType

按钮样式："button"

小图片样式："smallImg"

图文列表样式："imageText"

(选填项)

string

"button"

name

-

当前checkbox编组的name值,用于form提交

boolean / string / number

-

item（类型：array）

由1-N个object组成

每个object下的内容包含右侧这些内容

id

为checkbox指定一个id，用于dom查找等功能

值必须唯一（选填）

string

-

label

文字（选填）

boolean / string / number

-

value

value值（选填）

boolean / string / number

-

checked

是否选中（选填）

boolean

false

disabled

是否禁用（选填）

boolean

false

className

支持传入扩展class（选填）

string

-

style

支持传入扩展style（选填）

string

-

clickFun

自定义事件（选填）

function(以对象方式渲染时)

string(以comp方式渲染时)

-

img

图片的地址（仅小图片、图文列表时必填，否则 选填）

string

-

text

文本内容 （仅图文列表时必填，否则 选填）

string

-

方法列表（以对象方式渲染时可用）

方法

说明

参数

参数说明

参数类型

checked

设置某个checkbox为选中状态

index

设置为选中状态的checkbox的序号(必填项)

number，从0开始

checkedAll

设置所有checkbox为选中状态

unchecked

取消某个checkbox为选中状态

index

设置为选中状态的checkbox的序号(必填项)

number，从0开始

uncheckedAll

取消所有checkbox的选中状态

enabled

启用某个checkbox

index

设置为选中状态的checkbox的序号(必填项)

number，从0开始

enabledAll

启用所有checkbox

disabled

禁用某个checkbox

index

设置为选中状态的checkbox的序号(必填项)

number，从0开始

disabledAll

禁用所有checkbox

getAllCheckedValue

获取所有为选中状态的值

destory

销毁元素

-

以对象方式渲染时的方法调用示例，请点击下方的“显示代码”查看

var test = new CtpUicomCheckbox("#demoDiv", testData1);
test.checked(0); //将第一个checkbox设置为选中状态
test.checkedAll(); //将所有checkbox设置为选中状态
test.unchecked(0); //取消第一个checkbox的选中状态
test.uncheckedAll(); //取消所有checkbox的选中状态
test.enabled(0); //启用第一个checkbox
test.enabledAll(); //启用所有checkbox
test.disabled(0); //禁用第一个checkbox
test.disabledAll(); //禁用所有checkbox
test.getAllCheckedValue(); //获取所有为选中状态的值

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

style

=

"

font-size

:

16px

;

color

:

red

;

text-align

:

center

;

"

>

以对象方式渲染时的方法调用示例，请点击下方的“显示代码”查看

<

i

class

=

"

syIcon sy-arrow-crude-down

"

>

</

i

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

test

=

new

CtpUicomCheckbox

(

"#demoDiv"

,

testData1

)

;

test

.

checked

(

0

)

;

//将第一个checkbox设置为选中状态

test

.

checkedAll

(

)

;

//将所有checkbox设置为选中状态

test

.

unchecked

(

0

)

;

//取消第一个checkbox的选中状态

test

.

uncheckedAll

(

)

;

//取消所有checkbox的选中状态

test

.

enabled

(

0

)

;

//启用第一个checkbox

test

.

enabledAll

(

)

;

//启用所有checkbox

test

.

disabled

(

0

)

;

//禁用第一个checkbox

test

.

disabledAll

(

)

;

//禁用所有checkbox

test

.

getAllCheckedValue

(

)

;

//获取所有为选中状态的值

</

script

>

方法列表（以comp方式渲染时可用）

方法

说明

参数

参数说明

参数类型

checked

设置某个checkbox为选中状态

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

checkedAll

设置所有checkbox为选中状态

elObj

请见页末"elObj"的说明

String或dom对象

unchecked

取消某个checkbox为选中状态

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

uncheckedAll

取消所有checkbox的选中状态

elObj

请见页末"elObj"的说明

String或dom对象

enabled

启用某个checkbox

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

enabledAll

启用所有checkbox

elObj

请见页末"elObj"的说明

String或dom对象

disabled

禁用某个checkbox

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

disabledAll

禁用所有checkbox

elObj

请见页末"elObj"的说明

String或dom对象

getAllCheckedValue

获取dom下所有ctpUiCheckbox为选中状态的值

elObj

请见页末"elObj"的说明

String或dom对象

destory

销毁元素

-

以对象方式渲染时的方法调用示例，请点击下方的“显示代码”查看

CtpUiCheckbox.checked("#demoDiv",0); //将第一个checkbox设置为选中状态，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.checkedAll("#demoDiv"); //将所有checkbox设置为选中状态，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.unchecked("#demoDiv",0); //取消第一个checkbox的选中状态，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.uncheckedAll("#demoDiv"); //取消所有checkbox的选中状态，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.enabled("#demoDiv",0); //启用第一个checkbox，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.enabledAll("#demoDiv"); //启用所有checkbox，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.disabled("#demoDiv",0); //禁用第一个checkbox，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.disabledAll("#demoDiv"); //禁用所有checkbox，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.getAllCheckedValue("#demoDiv"); //获取dom下所有ctpUiCheckbox为选中状态的值

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

style

=

"

font-size

:

16px

;

color

:

red

;

text-align

:

center

;

"

>

以对象方式渲染时的方法调用示例，请点击下方的“显示代码”查看

<

i

class

=

"

syIcon sy-arrow-crude-down

"

>

</

i

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

CtpUiCheckbox

.

checked

(

"#demoDiv"

,

0

)

;

//将第一个checkbox设置为选中状态，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

checkedAll

(

"#demoDiv"

)

;

//将所有checkbox设置为选中状态，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

unchecked

(

"#demoDiv"

,

0

)

;

//取消第一个checkbox的选中状态，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

uncheckedAll

(

"#demoDiv"

)

;

//取消所有checkbox的选中状态，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

enabled

(

"#demoDiv"

,

0

)

;

//启用第一个checkbox，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

enabledAll

(

"#demoDiv"

)

;

//启用所有checkbox，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

disabled

(

"#demoDiv"

,

0

)

;

//禁用第一个checkbox，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

disabledAll

(

"#demoDiv"

)

;

//禁用所有checkbox，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

getAllCheckedValue

(

"#demoDiv"

)

;

//获取dom下所有ctpUiCheckbox为选中状态的值

</

script

>

elObj

:

被渲染的dom(必填项)
可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

## 47. Input 输入框

> 原始路径：`/components4.0/form/input.html`  
> 相对路径：`components4.0/form/input.md`  
> 页面 key：`v-261f91fa`  
> JS Chunk：`34.9c6949bf.js`

Input 输入框

1、普通的输入框

普通的输入框，原生组件，只是通过样式美观输入框

普通输入框

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

普通输入框

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

address

"

autocomplete

=

"

off

"

class

=

"

validate comp

"

name

=

"

address

"

placeholder

=

"

请输入值

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:50

"

/>

</

div

>

</

div

>

</

div

>

不可以编辑的输入框

原生组件，只是通过样式美观输入框

普通输入框

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

普通输入框

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

disabled

=

"

disabled

"

>

<

input

type

=

"

text

"

id

=

"

address

"

autocomplete

=

"

off

"

name

=

"

address2

"

placeholder

=

"

请输入值

"

class

=

"

validate comp

"

disabled

=

"

disabled

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:50

"

/>

</

div

>

</

div

>

</

div

>

2、带长度输入提醒的输入框---采用comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置

带长度输入框

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

带长度输入框

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

addressInput

"

autocomplete

=

"

off

"

placeholder

=

"

请输入值

"

name

=

"

addressInput

"

comp

=

"

type:'CtpUiComInput',maxLength:10

"

class

=

"

validate comp

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:10

"

/>

</

div

>

</

div

>

</

div

>

带长度输入提醒的输入框---采用对象渲染

普通输入框

var inputObj = new CtpUiComInput($("#inputObj").get(0), {maxLength: 20})

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

普通输入框

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

name

=

"

inputObj2

"

autocomplete

=

"

off

"

placeholder

=

"

请输入值

"

id

=

"

inputObj

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

inputObj

=

new

CtpUiComInput

(

$

(

"#inputObj"

)

.

get

(

0

)

,

{

maxLength

:

20

}

)

</

script

>

错误信息提醒---采用对象渲染

错误信息提醒

var inputObj = new CtpUiComInput($("#inputObj3").get(0), {});
inputObj.setErrorState("输入不能为空");
//清空错误状态 inputObj.clearErrorState();

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

错误信息提醒

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

name

=

"

inputObj3

"

autocomplete

=

"

off

"

placeholder

=

"

请输入值

"

id

=

"

inputObj3

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

inputObj

=

new

CtpUiComInput

(

$

(

"#inputObj3"

)

.

get

(

0

)

,

{

}

)

;

inputObj

.

setErrorState

(

"输入不能为空"

)

;

//清空错误状态 inputObj.clearErrorState();

</

script

>

成功信息提醒---采用对象渲染

成功信息提醒

var inputObj = new CtpUiComInput($("#inputObj4").get(0),{});
inputObj.setSuccessState();
//清空成功状态 inputObj.clearSuccessState();

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

成功信息提醒

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

name

=

"

inputObj4

"

autocomplete

=

"

off

"

placeholder

=

"

请输入值

"

id

=

"

inputObj4

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

inputObj

=

new

CtpUiComInput

(

$

(

"#inputObj4"

)

.

get

(

0

)

,

{

}

)

;

inputObj

.

setSuccessState

(

)

;

//清空成功状态 inputObj.clearSuccessState();

</

script

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiComInput

maxLength

长度提醒值

number

---

0

disabled

不可以编辑

boolean

false/true

false

方法列表

方法名

说明

参数

setErrorState

设置为错误状态

msg-错误提醒消息

setSuccessState

设置为成功状态

msg-成功提醒消息

clearErrorState

清空错误状态

--

clearSuccessState

清空成功状态

--

3、带前缀按钮的输入框---采用comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置

前缀按钮

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

前缀按钮

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

preBtnInput

"

name

=

"

preBtnInput

"

placeholder

=

"

请输入值

"

comp

=

"

type:'CtpUiPreBtnInput',pattern:'btn',btnLabel:'http://'

"

class

=

"

validate comp

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:50

"

/>

</

div

>

</

div

>

</

div

>

带前缀按钮的输入框---采用对象渲染

前缀按钮

var inputObj3 = new CtpUiPreBtnInput($("#preBtnInput3").get(0), {pattern: 'btn', btnLabel: '前缀'});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

前缀按钮

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

placeholder

=

"

请输入值

"

type

=

"

text

"

name

=

"

preBtnInput3

"

id

=

"

preBtnInput3

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

inputObj3

=

new

CtpUiPreBtnInput

(

$

(

"#preBtnInput3"

)

.

get

(

0

)

,

{

pattern

:

'btn'

,

btnLabel

:

'前缀'

}

)

;

</

script

>

带前缀图标的输入框---采用comp方式渲染

前缀按钮

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

前缀按钮

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

addressT

"

placeholder

=

"

请输入值

"

name

=

'

addressT

'

comp

=

"

type:'CtpUiPreBtnInput',pattern:'icon'

"

class

=

"

validate comp

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:50

"

/>

</

div

>

</

div

>

</

div

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiPreBtnInput

pattern

模式

string

btn 或者 icon

btn

iconClass

如果是icon模式需要设置字体图的class

string

syIcon sy-todoevent

btnLabel

如果是btn模式需要设置按钮的label

String

---

空

btnClick

点击按钮执行事件

string

---

空

4、带后缀按钮的输入框---采用comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置

pattern设置为btn

后缀按钮

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

后缀按钮

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

placeholder

=

"

请输入值

"

id

=

"

suffixBtnInput

"

comp

=

"

type:'CtpUiSuffixBtnInput',pattern:'btn',btnLabel:'https://'

"

class

=

"

validate comp

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:50

"

/>

</

div

>

</

div

>

</

div

>

带后缀简易按钮的输入框---采用comp方式渲染

pattern设置为simple

后缀按钮-简易

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

后缀按钮-简易

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

suffixBtnInputSimple

"

placeholder

=

"

请输入值

"

comp

=

"

type:'CtpUiSuffixBtnInput',pattern:'simple',btnLabel:'Forgot?'

"

class

=

"

validate comp

"

validate

=

"

type:'string',name:'${ctp:i18n('org.account_form.address.label')}',maxLength:50

"

/>

</

div

>

</

div

>

</

div

>

带后缀按钮的输入框---采用对象渲染

后缀按钮

var SuffixBtnInput3 = new CtpUiSuffixBtnInput($("#suffixBtnInput3").get(0), {pattern: 'btn', btnLabel: '后缀'});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

后缀按钮

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

placeholder

=

"

请输入值

"

type

=

"

text

"

name

=

"

suffixBtnInput3

"

id

=

"

suffixBtnInput3

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

SuffixBtnInput3

=

new

CtpUiSuffixBtnInput

(

$

(

"#suffixBtnInput3"

)

.

get

(

0

)

,

{

pattern

:

'btn'

,

btnLabel

:

'后缀'

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiSuffixBtnInput

pattern

模式

string

btn 或者 simple

btn

btnLabel

如果是btn模式需要设置按钮的label

String

---

空

btnClick

点击按钮执行事件

string

---

空

## 48. InputNumber 输入框

> 原始路径：`/components4.0/form/inputNumber.html`  
> 相对路径：`components4.0/form/inputNumber.md`  
> 页面 key：`v-32eb4cb1`  
> JS Chunk：`35.bb361626.js`

InputNumber 输入框

数字输入框----采用comp方式渲染

数字输入框--左右方式

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

数字输入框--左右方式

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

CtpUiNumberInput

"

comp

=

"

type:'CtpUiNumberInput',pattern:'leftRight'

"

class

=

"

comp validate

"

/>

</

div

>

</

div

>

</

div

>

数字输入框----采用comp方式渲染

数字输入框---上下方式

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

数字输入框---上下方式

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

CtpUiNumberInput

"

comp

=

"

type:'CtpUiNumberInput',pattern:'upDown'

"

class

=

"

comp validate

"

/>

</

div

>

</

div

>

</

div

>

数字输入框----采用手动方式渲染

数字输入框---上下方式

var preBtnObj=new CtpUiNumberInput($("#numberAdd").get(0),{pattern:'leftRight',min:-10,max:10});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

数字输入框---上下方式

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

numberAdd

"

class

=

"

validate

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

preBtnObj

=

new

CtpUiNumberInput

(

$

(

"#numberAdd"

)

.

get

(

0

)

,

{

pattern

:

'leftRight'

,

min

:

-

10

,

max

:

10

}

)

;

</

script

>

数字输入框----采用手动方式渲染

数字输入框---上下方式

var preBtnObj=new CtpUiNumberInput($("#number").get(0),{pattern:'upDown',min:-10,max:10});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

数字输入框---上下方式

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

number

"

class

=

"

validate

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

preBtnObj

=

new

CtpUiNumberInput

(

$

(

"#number"

)

.

get

(

0

)

,

{

pattern

:

'upDown'

,

min

:

-

10

,

max

:

10

}

)

;

</

script

>

参数列表

参数

说明

类型

默认值

type

控件类型

string

CtpUiNumberInput

min

最小值

Number

0

max

最大值

Number

9999999

step

步长

Number

1

pattern

展示方式

String

leftRight 或者 upDown

方法列表

方法名

说明

参数 1

参数 2

destory

销毁组件

## 49. Calendar 月份段选择

> 原始路径：`/components4.0/form/monthRange.html`  
> 相对路径：`components4.0/form/monthRange.md`  
> 页面 key：`v-627337d3`  
> JS Chunk：`82.066af11d.js`

Calendar 月份段选择

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiMonthRange");方式来获取对象

【采用comp方式渲染,选择月份段】

月份段comp

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

月份段comp

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiMonthRange',twoInput:true,startDate:'2019-02',endDate:'2020-11',containerId:'mainPage',hasIcon:true,pattern:'dateRange'

"

/>

</

div

>

</

div

>

</

div

>

【采用对象方式渲染,选择月份段】

月份段

var doubleDateDiv = new CtpUiMonthRange("ctpUiMonthRangeId", {hasIcon: true, type: "date", twoInput: true});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

月份段

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

250px

"

>

<

input

type

=

"

text

"

autocomplete

=

"

off

"

id

=

"

ctpUiMonthRangeId

"

name

=

"

name_text

"

value

=

"

class

=

"

validate msHideClear

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

doubleDateDiv

=

new

CtpUiMonthRange

(

"ctpUiMonthRangeId"

,

{

hasIcon

:

true

,

type

:

"date"

,

twoInput

:

true

}

)

;

</

script

>

CtpUiCalendarObj 日历参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiMonthRange

startDate

开始月份

string

-

当前月份

endDate

结束月份

string

-

twoInput

是否生成2个输入框

boolean

false/true

false

方法列表

方法名

说明

参数 1

参数 2

attachEvent

注册方法

eventName[方法名]

fun[回调函数]

detachEvent

销毁方法

eventName[方法名]

destory

销毁组件

setErrorState

设置错误提醒信息

错误内容，例子 mycalObj.setErrorState("错误发生了");

clearErrorState

清空错误提示信息

setDisabled

设置日历不可以操作

例子 mycalObj.setDisabled(true);

var calendarObject = new CtpUiCalendarObj(["calendar"],null,{hasIcon:true});
//设置日期的方式
calendarObject.setDate(new Date(2011,5,8));
calendarObject.setDate("2011-06-08"); // 如果采用字符串的话 相应初始化的时候设置了ifFormat 为"%Y-%M-%d"

<

script

type

=

"

text/javascript

"

>

var

calendarObject

=

new

CtpUiCalendarObj

(

[

"calendar"

]

,

null

,

{

hasIcon

:

true

}

)

;

//设置日期的方式

calendarObject

.

setDate

(

new

Date

(

2011

,

5

,

8

)

;

calendarObject

.

setDate

(

"2011-06-08"

)

;

// 如果采用字符串的话 相应初始化的时候设置了ifFormat 为"%Y-%M-%d"

</

script

>

event事件列表

eventName

参数 1

参数2

onClick

date

## 50. Radio 单选框

> 原始路径：`/components4.0/form/radio.html`  
> 相对路径：`components4.0/form/radio.md`  
> 页面 key：`v-e064813e`  
> JS Chunk：`36.8791ea9f.js`

Radio 单选框

在一组备选项中进行单选，由于选项默认可见，不宜过多，若选项过多，建议使用 Select 选择器。

基础样式

选项1

选项2

选项3

选项4

选项5

<

span

class

=

"

skin-radio margin_r_20

"

>

<

input

type

=

"

radio

"

value

=

"

1

"

id

=

"

Radio11

"

name

=

"

option1

"

>

<

label

for

=

"

Radio11

"

>

<

i

>

</

i

>

</

label

>

选项1

</

span

>

<

span

class

=

"

skin-radio margin_r_20

"

>

<

input

type

=

"

radio

"

value

=

"

2

"

id

=

"

Radio12

"

name

=

"

option1

"

>

<

label

for

=

"

Radio12

"

>

<

i

>

</

i

>

</

label

>

选项2

</

span

>

<

span

class

=

"

skin-radio margin_r_20

"

>

<

input

type

=

"

radio

"

value

=

"

3

"

id

=

"

Radio13

"

name

=

"

option1

"

>

<

label

for

=

"

Radio13

"

>

<

i

>

</

i

>

</

label

>

选项3

</

span

>

<

span

class

=

"

skin-radio margin_r_20

"

>

<

input

type

=

"

radio

"

value

=

"

4

"

id

=

"

Radio14

"

name

=

"

option1

"

disabled

checked

>

<

label

for

=

"

Radio14

"

>

<

i

>

</

i

>

</

label

>

选项4

</

span

>

<

span

class

=

"

skin-radio margin_r_20

"

>

<

input

type

=

"

radio

"

value

=

"

5

"

id

=

"

Radio15

"

name

=

"

option1

"

disabled

>

<

label

for

=

"

Radio15

"

>

<

i

>

</

i

>

</

label

>

选项5

</

span

>

扩展样式

① 按钮样式

按钮样式的单选组合。

采用对象方式渲染

var testData1 = {
styleType: "button",
name: "N1",
item: [{
id: "R1",
label: "选中的",
value: "V1",
checked: true,
disabled: false
},{
id: "R2",
label: "未选中的",
value: "V2",
checked: false,
disabled: false,
clickFun: function() {
$.alert("我是点击后触发的自定义事件");
}
}]
};
var testData2 = {
styleType: "button",
name: "N2",
item: [{
id: "R3",
label: "禁用的：已选中",
value: "V3",
checked: true,
disabled: true
},{
id: "R4",
label: "禁用的：未选中",
value: "V4",
checked: false,
disabled: true
}]
};
var test1 = new CtpUicomRadio("#btnRadio-demoDiv1",testData1);
var test2 = new CtpUicomRadio("#btnRadio-demoDiv2",testData2);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnRadio-demoDiv1

"

>

</

div

>

<

br

/>

<

div

id

=

"

btnRadio-demoDiv2

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData1

=

{

styleType

:

"button"

,

name

:

"N1"

,

item

:

[

{

id

:

"R1"

,

label

:

"选中的"

,

value

:

"V1"

,

checked

:

true

,

disabled

:

false

}

,

{

id

:

"R2"

,

label

:

"未选中的"

,

value

:

"V2"

,

checked

:

false

,

disabled

:

false

,

clickFun

:

function

(

)

{

$

.

alert

(

"我是点击后触发的自定义事件"

)

;

}

]

}

;

var

testData2

=

{

styleType

:

"button"

,

name

:

"N2"

,

item

:

[

{

id

:

"R3"

,

label

:

"禁用的：已选中"

,

value

:

"V3"

,

checked

:

true

,

disabled

:

true

}

,

{

id

:

"R4"

,

label

:

"禁用的：未选中"

,

value

:

"V4"

,

checked

:

false

,

disabled

:

true

}

]

}

;

var

test1

=

new

CtpUicomRadio

(

"#btnRadio-demoDiv1"

,

testData1

)

;

var

test2

=

new

CtpUicomRadio

(

"#btnRadio-demoDiv2"

,

testData2

)

;

</

script

>

采用comp的方式渲染

选中的

未选中的

禁用的：已选中

禁用的：未选中

<

div

id

=

"

btnRadioCompDemo3

"

class

=

"

comp

"

comp

=

"

type:'CtpUiRadio',styleType:'button'

"

>

<

ul

class

=

"

ctpUiRadio_button

"

>

<

li

>

<

span

class

=

"

checkCir

"

>

</

span

>

<

input

type

=

"

radio

"

name

=

"

N3

"

id

=

"

R5

"

value

=

"

V1

"

checked

=

"

/>

<

label

for

=

"

R5

"

>

选中的

</

label

>

</

li

>

<

li

>

<

span

class

=

"

checkCir

"

>

</

span

>

<

input

type

=

"

radio

"

name

=

"

N3

"

id

=

"

R6

"

value

=

"

V2

"

/>

<

label

for

=

"

R6

"

>

未选中的

</

label

>

</

li

>

</

ul

>

</

div

>

<

br

/>

<

div

id

=

"

btnRadioCompDemo4

"

class

=

"

comp

"

comp

=

"

type:'CtpUiRadio',styleType:'button'

"

>

<

ul

class

=

"

ctpUiRadio_button

"

>

<

li

>

<

span

class

=

"

checkCir

"

>

</

span

>

<

input

type

=

"

radio

"

name

=

"

N33

"

id

=

"

R7

"

value

=

"

V3

"

checked

=

"

disabled

=

"

disabled

"

/>

<

label

for

=

"

R7

"

>

禁用的：已选中

</

label

>

</

li

>

<

li

>

<

span

class

=

"

checkCir

"

>

</

span

>

<

input

type

=

"

radio

"

name

=

"

N33

"

id

=

"

R8

"

value

=

"

V4

"

disabled

=

"

disabled

"

/>

<

label

for

=

"

R8

"

>

禁用的：未选中

</

label

>

</

li

>

</

ul

>

</

div

>

② 小图片样式

小图片样式的单选组合。

//小图片
var testData3 = {
styleType: "smallImg",
name: "T3",
item: [{
id: "T31",
label: "图片1",
value: "V31",
img: "http://open.seeyon.com/seeyonui/images/1.jpg",
checked: false,
disabled: false
},{
id: "T32",
label: "图片2",
value: "V32",
img: "http://open.seeyon.com/seeyonui/images/2.jpg",
checked: false,
disabled: false
},{
id: "T33",
label: "图片3",
value: "V33",
img: "http://open.seeyon.com/seeyonui/images/3.jpg",
checked: true,
disabled: true
},{
id: "T34",
label: "图片4",
value: "V34",
img: "http://open.seeyon.com/seeyonui/images/4.jpg",
checked: false,
disabled: true
}]
}
var test3 = new CtpUicomRadio("#btnRadio-demoDiv3",testData3);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnRadio-demoDiv3

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//小图片

var

testData3

=

{

styleType

:

"smallImg"

,

name

:

"T3"

,

item

:

[

{

id

:

"T31"

,

label

:

"图片1"

,

value

:

"V31"

,

img

:

"http://open.seeyon.com/seeyonui/images/1.jpg"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T32"

,

label

:

"图片2"

,

value

:

"V32"

,

img

:

"http://open.seeyon.com/seeyonui/images/2.jpg"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T33"

,

label

:

"图片3"

,

value

:

"V33"

,

img

:

"http://open.seeyon.com/seeyonui/images/3.jpg"

,

checked

:

true

,

disabled

:

true

}

,

{

id

:

"T34"

,

label

:

"图片4"

,

value

:

"V34"

,

img

:

"http://open.seeyon.com/seeyonui/images/4.jpg"

,

checked

:

false

,

disabled

:

true

}

]

}

var

test3

=

new

CtpUicomRadio

(

"#btnRadio-demoDiv3"

,

testData3

)

;

</

script

>

③ 大图片样式

大图片样式的单选组合：图片强制拉伸显示

//大图片
var testData4 = {
styleType: "bigImg",
name: "T4",
item: [{
id: "T41",
label: "图片2",
value: "V41",
img: "http://open.seeyon.com/seeyonui/images/2.jpg",
checked: false,
disabled: false
},{
id: "T42",
label: "图片3",
value: "V42",
img: "http://open.seeyon.com/seeyonui/images/3.jpg",
checked: false,
disabled: false
},{
id: "T43",
label: "图片4",
value: "V43",
img: "http://open.seeyon.com/seeyonui/images/4.jpg",
checked: true,
disabled: true
},{
id: "T44",
label: "图片5",
value: "V44",
img: "http://open.seeyon.com/seeyonui/images/5.jpg",
checked: false,
disabled: true
}]
}
var test4 = new CtpUicomRadio("#btnRadio-demoDiv4",testData4);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnRadio-demoDiv4

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//大图片

var

testData4

=

{

styleType

:

"bigImg"

,

name

:

"T4"

,

item

:

[

{

id

:

"T41"

,

label

:

"图片2"

,

value

:

"V41"

,

img

:

"http://open.seeyon.com/seeyonui/images/2.jpg"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T42"

,

label

:

"图片3"

,

value

:

"V42"

,

img

:

"http://open.seeyon.com/seeyonui/images/3.jpg"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T43"

,

label

:

"图片4"

,

value

:

"V43"

,

img

:

"http://open.seeyon.com/seeyonui/images/4.jpg"

,

checked

:

true

,

disabled

:

true

}

,

{

id

:

"T44"

,

label

:

"图片5"

,

value

:

"V44"

,

img

:

"http://open.seeyon.com/seeyonui/images/5.jpg"

,

checked

:

false

,

disabled

:

true

}

]

}

var

test4

=

new

CtpUicomRadio

(

"#btnRadio-demoDiv4"

,

testData4

)

;

</

script

>

大图片样式的单选组合：支持图片居中，自定义背景色。

//大图片
var testData41 = {
styleType: "bigImg",
name: "T41",
item: [{
id: "T411",
label: "图片2",
value: "V411",
img: "http://open.seeyon.com/seeyonui/images/2.jpg",
checked: false,
disabled: false,
autoSize: true,
imgBgc: "#000"
},{
id: "T421",
label: "图片3",
value: "V421",
img: "http://open.seeyon.com/seeyonui/images/3.jpg",
checked: false,
disabled: false,
autoSize: true,
imgBgc: "#f00"
},{
id: "T431",
label: "图片41",
value: "V431",
img: "http://open.seeyon.com/seeyonui/images/4.jpg",
checked: true,
disabled: true,
autoSize: true,
imgBgc: "#000"
},{
id: "T441",
label: "图片51",
value: "V441",
img: "http://open.seeyon.com/seeyonui/images/5.jpg",
checked: false,
disabled: true,
autoSize: true,
imgBgc: "#000"
}]
}
var test41 = new CtpUicomRadio("#btnRadio-demoDiv41",testData41);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnRadio-demoDiv41

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//大图片

var

testData41

=

{

styleType

:

"bigImg"

,

name

:

"T41"

,

item

:

[

{

id

:

"T411"

,

label

:

"图片2"

,

value

:

"V411"

,

img

:

"http://open.seeyon.com/seeyonui/images/2.jpg"

,

checked

:

false

,

disabled

:

false

,

autoSize

:

true

,

imgBgc

:

"#000"

}

,

{

id

:

"T421"

,

label

:

"图片3"

,

value

:

"V421"

,

img

:

"http://open.seeyon.com/seeyonui/images/3.jpg"

,

checked

:

false

,

disabled

:

false

,

autoSize

:

true

,

imgBgc

:

"#f00"

}

,

{

id

:

"T431"

,

label

:

"图片41"

,

value

:

"V431"

,

img

:

"http://open.seeyon.com/seeyonui/images/4.jpg"

,

checked

:

true

,

disabled

:

true

,

autoSize

:

true

,

imgBgc

:

"#000"

}

,

{

id

:

"T441"

,

label

:

"图片51"

,

value

:

"V441"

,

img

:

"http://open.seeyon.com/seeyonui/images/5.jpg"

,

checked

:

false

,

disabled

:

true

,

autoSize

:

true

,

imgBgc

:

"#000"

}

]

}

var

test41

=

new

CtpUicomRadio

(

"#btnRadio-demoDiv41"

,

testData41

)

;

</

script

>

④ 图文列表样式

图文列表样式的单选组合。

//图文列表
var testData5 = {
styleType: "imageText",
name: "T5",
item: [{
id: "T51",
label: "图片1",
value: "V51",
img: "http://open.seeyon.com/seeyonui/images/1.jpg",
text: "北京致远互联软件股份有限公司（简称：致远互联）成立于2002年3月，专注于为组织级客户提供协同管理软件、解决方案和云服务，是集协同研究、软件研发、市场营销、渠道销售、支持服务于一体的协同管理全案服务商。",
checked: false,
disabled: false
},{
id: "T52",
label: "图片2",
value: "V52",
img: "http://open.seeyon.com/seeyonui/images/2.jpg",
text: "作为中国协同管理软件及云服务领先厂商，致远互联17年一直专注在协同管理软件领域。多年来，致远互联秉承“以人为中心”的协同管理理念，形成了从私有云到公有云、从互联网到移动互联网、从产品到定制及增值服务、从工作协同到业务协同、从组织内协同到组织间协同再到社会化协同的完整产品线及解决方案。",
checked: false,
disabled: false
},{
id: "T53",
label: "图片3",
value: "V53",
img: "http://open.seeyon.com/seeyonui/images/3.jpg",
text: "历经17年的发展，致远互联已先后走过单纯标准化产品化经营的V1.0阶段、协同解决方案和协同业务定制的V2.0阶段，现在，致远互联迈入了协同运营平台化发展的V3.0阶段，坚定助力企业“数字化升级”。",
checked: false,
disabled: false
},{
id: "T54",
label: "图片4",
value: "V54",
img: "http://open.seeyon.com/seeyonui/images/4.jpg",
text: "每天，都有数万家政府机构及企业级用户、数百万个终端用户使用致远协同管理软件产品与服务。致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。",
checked: true,
disabled: true
},{
id: "T55",
label: "图片5",
value: "V55",
img: "http://open.seeyon.com/seeyonui/images/5.jpg",
text: "致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。",
checked: false,
disabled: true
}]
}
var test5 = new CtpUicomRadio("#btnRadio-demoDiv5",testData5);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnRadio-demoDiv5

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//图文列表

var

testData5

=

{

styleType

:

"imageText"

,

name

:

"T5"

,

item

:

[

{

id

:

"T51"

,

label

:

"图片1"

,

value

:

"V51"

,

img

:

"http://open.seeyon.com/seeyonui/images/1.jpg"

,

text

:

"北京致远互联软件股份有限公司（简称：致远互联）成立于2002年3月，专注于为组织级客户提供协同管理软件、解决方案和云服务，是集协同研究、软件研发、市场营销、渠道销售、支持服务于一体的协同管理全案服务商。"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T52"

,

label

:

"图片2"

,

value

:

"V52"

,

img

:

"http://open.seeyon.com/seeyonui/images/2.jpg"

,

text

:

"作为中国协同管理软件及云服务领先厂商，致远互联17年一直专注在协同管理软件领域。多年来，致远互联秉承“以人为中心”的协同管理理念，形成了从私有云到公有云、从互联网到移动互联网、从产品到定制及增值服务、从工作协同到业务协同、从组织内协同到组织间协同再到社会化协同的完整产品线及解决方案。"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T53"

,

label

:

"图片3"

,

value

:

"V53"

,

img

:

"http://open.seeyon.com/seeyonui/images/3.jpg"

,

text

:

"历经17年的发展，致远互联已先后走过单纯标准化产品化经营的V1.0阶段、协同解决方案和协同业务定制的V2.0阶段，现在，致远互联迈入了协同运营平台化发展的V3.0阶段，坚定助力企业“数字化升级”。"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T54"

,

label

:

"图片4"

,

value

:

"V54"

,

img

:

"http://open.seeyon.com/seeyonui/images/4.jpg"

,

text

:

"每天，都有数万家政府机构及企业级用户、数百万个终端用户使用致远协同管理软件产品与服务。致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。"

,

checked

:

true

,

disabled

:

true

}

,

{

id

:

"T55"

,

label

:

"图片5"

,

value

:

"V55"

,

img

:

"http://open.seeyon.com/seeyonui/images/5.jpg"

,

text

:

"致远协同，已成为贵州省政府、中粮集团、联想控股、招商银行、滴滴出行、奇虎360、湖南卫视等世界500强、中国500强及各领域优秀企业的共同选择。"

,

checked

:

false

,

disabled

:

true

}

]

}

var

test5

=

new

CtpUicomRadio

(

"#btnRadio-demoDiv5"

,

testData5

)

;

</

script

>

⑤ 页签样式

页签样式的单选组合。

//页签样式
var testData6 = {
styleType: "tabs",
name: "T6",
item: [{
id: "T61",
label: "北京",
value: "V61",
checked: true,
disabled: false
},{
id: "T62",
label: "上海",
value: "V62",
checked: false,
disabled: false
},{
id: "T63",
label: "广州",
value: "V63",
checked: false,
disabled: true
},{
id: "T64",
label: "深圳",
value: "V64",
checked: false,
disabled: true
}]
}
var test6 = new CtpUicomRadio("#btnRadio-demoDiv6",testData6);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

btnRadio-demoDiv6

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//页签样式

var

testData6

=

{

styleType

:

"tabs"

,

name

:

"T6"

,

item

:

[

{

id

:

"T61"

,

label

:

"北京"

,

value

:

"V61"

,

checked

:

true

,

disabled

:

false

}

,

{

id

:

"T62"

,

label

:

"上海"

,

value

:

"V62"

,

checked

:

false

,

disabled

:

false

}

,

{

id

:

"T63"

,

label

:

"广州"

,

value

:

"V63"

,

checked

:

false

,

disabled

:

true

}

,

{

id

:

"T64"

,

label

:

"深圳"

,

value

:

"V64"

,

checked

:

false

,

disabled

:

true

}

]

}

var

test6

=

new

CtpUicomRadio

(

"#btnRadio-demoDiv6"

,

testData6

)

;

</

script

>

调用方式

var xxx = new CtpUicomRadio(elObj, options);

参数列表：

参数

说明

类型

默认值

elObj

-

被渲染的dom(必填项)

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

-

options（类型：object）(必填项)

styleType

按钮样式："button"

小图片样式："smallImg"

大图片样式："bigImg"

图文列表样式："imageText"

页签样式："tabs"

（选填项）

string

"button"

name

-

当前radio编组的name值,用于form提交

boolean / string / number

-

item（类型：array）

由1-N个object组成

每个object下的内容包含右侧这些内容

id

为radio指定一个id，用于dom查找等功能

值必须唯一

（选填）

string

-

label

文字（选填）

boolean / string / number

-

value

value值（选填）

boolean / string / number

-

checked

是否选中，每组radio组只允许一个为true（选填）

boolean

false

disabled

是否禁用（选填）

boolean

false

className

支持传入扩展class（选填）

string

-

style

支持传入扩展style（选填）

string

-

clickFun

自定义事件（选填）

function(以对象方式渲染时)

string(以comp方式渲染时)

-

img

图片的地址（仅小图片、大图片、图文列表时必填，否则 选填）

string

-

imgWidth

图片的宽度（仅大图片时选填）

number

-

imgHeight

图片的高度（仅大图片时选填）

number

-

imgAutoSize

图片尺寸是否自动（仅大图片时选填）

number

-

imgBgc

图片区的背景颜色（仅imgAutoSize为true时有效）

number

-

text

文本内容（仅图文列表时必填，否则 选填）

string

-

方法列表（以对象方式渲染时可用）

方法

说明

参数

参数说明

参数类型

checked

设置某个radio为选中状态

index

设置为选中状态的radio的序号(必填项)

number，从0开始

unchecked

取消某个radio为选中状态

index

设置为选中状态的radio的序号(必填项)

number，从0开始

uncheckedAll

取消所有radio的选中状态

enabled

启用某个radio

index

设置为选中状态的radio的序号(必填项)

number，从0开始

enabledAll

启用所有radio

disabled

禁用某个radio

index

设置为选中状态的radio的序号(必填项)

number，从0开始

disabledAll

禁用所有radio

destory

销毁元素

-

以对象方式渲染时的方法调用示例，请点击下方的“显示代码”查看

var test = new CtpUicomRadio("#demoDiv", testData1);
test.checked(0); //将第一个radio设置为选中状态
test.unchecked(0); //取消第一个radio的选中状态
test.uncheckedAll(); //取消所有radio的选中状态
test.enabled(0); //启用第一个radio
test.enabledAll(); //启用所有radio
test.disabled(0); //禁用第一个radio
test.disabledAll(); //禁用所有radio

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

style

=

"

font-size

:

16px

;

color

:

red

;

text-align

:

center

;

"

>

以对象方式渲染时的方法调用示例，请点击下方的“显示代码”查看

<

i

class

=

"

syIcon sy-arrow-crude-down

"

>

</

i

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

test

=

new

CtpUicomRadio

(

"#demoDiv"

,

testData1

)

;

test

.

checked

(

0

)

;

//将第一个radio设置为选中状态

test

.

unchecked

(

0

)

;

//取消第一个radio的选中状态

test

.

uncheckedAll

(

)

;

//取消所有radio的选中状态

test

.

enabled

(

0

)

;

//启用第一个radio

test

.

enabledAll

(

)

;

//启用所有radio

test

.

disabled

(

0

)

;

//禁用第一个radio

test

.

disabledAll

(

)

;

//禁用所有radio

</

script

>

方法列表（以comp方式渲染时可用）

方法

说明

参数

参数说明

参数类型

checked

设置某个radio为选中状态

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

unchecked

取消某个radio为选中状态

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

uncheckedAll

取消所有radio的选中状态

elObj

请见页末"elObj"的说明

String或dom对象

enabled

启用某个radio

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

enabledAll

启用所有radio

elObj

请见页末"elObj"的说明

String或dom对象

disabled

禁用某个radio

elObj, index

elObj:请见页末"elObj"的说明

index:设置为选中状态的checkbox的序号(必填项)

index: number，从0开始

disabledAll

禁用所有radio

elObj

请见页末"elObj"的说明

String或dom对象

destory

销毁元素

-

以comp方式渲染时的方法调用示例，请点击下方的“显示代码”查看

CtpUiCheckbox.checked("#demoDiv",0); //将第一个radio设置为选中状态，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.unchecked("#demoDiv",0); //取消第一个radio的选中状态，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.uncheckedAll("#demoDiv"); //取消所有radio的选中状态，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.enabled("#demoDiv",0); //启用第一个radio，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.enabledAll("#demoDiv"); //启用所有radio，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.disabled("#demoDiv",0); //禁用第一个radio，生效的元素为document.querySelector("#demoDiv")
CtpUiCheckbox.disabledAll("#demoDiv"); //禁用所有radio，生效的元素为document.querySelector("#demoDiv")

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

style

=

"

font-size

:

16px

;

color

:

red

;

text-align

:

center

;

"

>

以comp方式渲染时的方法调用示例，请点击下方的“显示代码”查看

<

i

class

=

"

syIcon sy-arrow-crude-down

"

>

</

i

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

CtpUiCheckbox

.

checked

(

"#demoDiv"

,

0

)

;

//将第一个radio设置为选中状态，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

unchecked

(

"#demoDiv"

,

0

)

;

//取消第一个radio的选中状态，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

uncheckedAll

(

"#demoDiv"

)

;

//取消所有radio的选中状态，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

enabled

(

"#demoDiv"

,

0

)

;

//启用第一个radio，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

enabledAll

(

"#demoDiv"

)

;

//启用所有radio，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

disabled

(

"#demoDiv"

,

0

)

;

//禁用第一个radio，生效的元素为document.querySelector("#demoDiv")

CtpUiCheckbox

.

disabledAll

(

"#demoDiv"

)

;

//禁用所有radio，生效的元素为document.querySelector("#demoDiv")

</

script

>

elObj

:

被渲染的dom(必填项)
可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

## 51. Rate 评分

> 原始路径：`/components4.0/form/rate.html`  
> 相对路径：`components4.0/form/rate.md`  
> 页面 key：`v-bb19a81a`  
> JS Chunk：`83.13c7c4b8.js`

Rate 评分

普通评分

new CtpUiRateMark(document.getElementById("rate"),{
value:3
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

rate

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiRateMark

(

document

.

getElementById

(

"rate"

)

,

{

value

:

3

}

)

;

</

script

>

禁用评分

new CtpUiRateMark(document.getElementById("rate1"),{
width:'300px',
value:3.5,
disabled:true
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

rate1

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiRateMark

(

document

.

getElementById

(

"rate1"

)

,

{

width

:

'300px'

,

value

:

3.5

,

disabled

:

true

}

)

;

</

script

>

显示分数评分

new CtpUiRateMark(document.getElementById("rate2"),{
width:'300px',
height:'50px',
value:3.5,
isShowLabel:true
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

rate2

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiRateMark

(

document

.

getElementById

(

"rate2"

)

,

{

width

:

'300px'

,

height

:

'50px'

,

value

:

3.5

,

isShowLabel

:

true

}

)

;

</

script

>

修改图标评分

new CtpUiRateMark(document.getElementById("rate3"),{
width:'300px',
height:'50px',
value:3.5,
isShowLabel:true,
fullIcon:'sy-praise-fill',
emptyIcon:'sy-praise'
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

rate3

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiRateMark

(

document

.

getElementById

(

"rate3"

)

,

{

width

:

'300px'

,

height

:

'50px'

,

value

:

3.5

,

isShowLabel

:

true

,

fullIcon

:

'sy-praise-fill'

,

emptyIcon

:

'sy-praise'

}

)

;

</

script

>

自定义分数评分

new CtpUiRateMark(document.getElementById("rate4"),{
width:'300px',
height:'50px',
value:3.5,
isShowLabel:true,
fullIcon:'sy-praise-fill',
emptyIcon:'sy-praise',
labelFunc:function(value){
var labelObj={
'0':'极差',
'0.5':'极差',
'1':'极差',
'1.5':'失望',
'2':'失望',
'2.5':'一般',
'3':'一般',
'3.5':'一般',
'4':'满意',
'4.5':'满意',
'5':'惊喜',
};
return labelObj[value]
}
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

rate4

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiRateMark

(

document

.

getElementById

(

"rate4"

)

,

{

width

:

'300px'

,

height

:

'50px'

,

value

:

3.5

,

isShowLabel

:

true

,

fullIcon

:

'sy-praise-fill'

,

emptyIcon

:

'sy-praise'

,

labelFunc

:

function

(

value

)

{

var

labelObj

=

{

'0'

:

'极差'

,

'0.5'

:

'极差'

,

'1'

:

'极差'

,

'1.5'

:

'失望'

,

'2'

:

'失望'

,

'2.5'

:

'一般'

,

'3'

:

'一般'

,

'3.5'

:

'一般'

,

'4'

:

'满意'

,

'4.5'

:

'满意'

,

'5'

:

'惊喜'

,

}

;

return

labelObj

[

value

]

}

)

;

</

script

>

采用comp方式渲染

自定义分数评分

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

rate5

"

class

=

"

comp

"

comp

=

"

type:'CtpUiRateMark',width:'300px',
height:'50px',
value:3.5,
isShowLabel:true,
fullIcon:'sy-praise-fill',
emptyIcon:'sy-praise',
labelFunc:function(value){
var labelObj={
'0':'极差',
'0.5':'极差',
'1':'极差',
'1.5':'失望',
'2':'失望',
'2.5':'一般',
'3':'一般',
'3.5':'一般',
'4':'满意',
'4.5':'满意',
'5':'惊喜',
};
return labelObj[value]
}

"

>

</

div

>

</

div

>

</

div

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

-

options

width

宽度(带单位)

String

200px

height

高度(带单位)

String

20px

id

String

value

当前值

Number

50

disabled

是否已禁用

Boolean

false

className

传入class

String

isShowLabel

是否显示label

Boolean

false

labelFunc

label渲染function 返回字符串 自带参数为value的值

Function

function(value:number){ return value + "分" }

labelWidth

label宽度(带单位)

String

30px

emptyIcon

自定义空心图标

String

sy-collect

fullIcon

自定义填充的图标

String

sy-collect-fill

callbackFuc

改变值后的回调方法 自带参数为value的值

Function

方法列表

方法名

说明

参数

destory

销毁控件

setDisabled

设置是否已禁用

true/false

setValue

设置当前值

number

## 52. Select 选择器

> 原始路径：`/components4.0/form/select.html`  
> 相对路径：`components4.0/form/select.md`  
> 页面 key：`v-0ba4461a`  
> JS Chunk：`37.19aeeb52.js`

Select 选择器

1、基础用法--采用select+comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiComSelect");方式来获取对象

由select渲染

dd

dd1

dd2

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由select渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

select

class

=

"

comp comp_select

"

comp

=

"

type:'CtpUiComSelect',search:true,containerId:'mainPage'

"

id

=

"

selOne

"

>

<

option

value

=

"

dd

"

>

dd

</

option

>

<

option

value

=

"

dd1

"

>

dd1

</

option

>

<

option

value

=

"

dd2

"

>

dd2

</

option

>

</

select

>

</

div

>

</

div

>

</

div

>

基础用法--采用select+对象方式渲染

由select渲染

dd

dd1

dd2

var ctpUiComSelect = new CtpUiComSelect($("#sel_two").get(0), {containerId: "mainPage"});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由select渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

select

class

=

"

comp_select

"

id

=

"

sel_two

"

>

<

option

value

=

"

dd

"

>

dd

</

option

>

<

option

value

=

"

dd1

"

>

dd1

</

option

>

<

option

value

=

"

dd2

"

>

dd2

</

option

>

</

select

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

ctpUiComSelect

=

new

CtpUiComSelect

(

$

(

"#sel_two"

)

.

get

(

0

)

,

{

containerId

:

"mainPage"

}

)

;

</

script

>

2、基础用法--采用inputt+comp方式渲染

普通的输入框

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

selTwo

"

name

=

"

selTwo

"

value

=

"

class

=

"

comp

"

comp

=

"

type:'CtpUiComSelect',containerId:'mainPage',options:[{value: 'Beijing',label: '北京'},{value: 'Beijing2',label: '北京2'}]

"

>

</

div

>

</

div

>

</

div

>

基础用法--采用input+对象方式渲染

由input渲染

var ctpUiComSelect = new CtpUiComSelect($("#name_text4").get(0), {
containerId: "mainPage",
options: [{"value": "null", "label": "无"},
{"value": "165256020278735481", "label": "千 (数据/1000) "},
{"value": "165256020278755483", "label": "十亿 (数据/1000000000) "},
{"value": "165256020278745482", "label": "百万 (数据/1000000) "},
{"value": "5419287588972873226", "label": "ddddddddddddd"},
{"value": "-375487052438878328", "label": "sssssssssssssssss<a href=''>dd</a>"},
{"value": "-3933095685980860961", "label": "集团单位 (数据/11111) "}
]
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

name_text4

"

name

=

"

name_text

"

value

=

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

ctpUiComSelect

=

new

CtpUiComSelect

(

$

(

"#name_text4"

)

.

get

(

0

)

,

{

containerId

:

"mainPage"

,

options

:

[

{

"value"

:

"null"

,

"label"

:

"无"

}

,

{

"value"

:

"165256020278735481"

,

"label"

:

"千 (数据/1000) "

}

,

{

"value"

:

"165256020278755483"

,

"label"

:

"十亿 (数据/1000000000) "

}

,

{

"value"

:

"165256020278745482"

,

"label"

:

"百万 (数据/1000000) "

}

,

{

"value"

:

"5419287588972873226"

,

"label"

:

"ddddddddddddd"

}

,

{

"value"

:

"-375487052438878328"

,

"label"

:

"sssssssssssssssss<a href=''>dd</a>"

}

,

{

"value"

:

"-3933095685980860961"

,

"label"

:

"集团单位 (数据/11111) "

}

]

}

)

;

</

script

>

3、disabled下拉

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiComSelect");方式来获取对象

disabled下拉

dd

dd1

dd2

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

disabled下拉

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

select

class

=

"

comp comp_select

"

comp

=

"

type:'CtpUiComSelect',search:true,disabled:true

"

id

=

"

selOne2

"

>

<

option

value

=

"

dd

"

>

dd

</

option

>

<

option

value

=

"

dd1

"

>

dd1

</

option

>

<

option

value

=

"

dd2

"

>

dd2

</

option

>

</

select

>

</

div

>

</

div

>

</

div

>

<!--
<div>
如果是input 可以设置input为disabled
<input type="text" id="selTwo" name="selTwo" value="" disabled="disabled"
class="comp"
comp="type:'CtpUiComSelect',containerId:'mainPage',options:[{value: 'Beijing',label: '北京'},{value: 'Beijing2',label: '北京2'}]">

如果是对象渲染 则设置参数disabled为true
var ctpUiComSelect = new CtpUiComSelect($("#name_text4").get(0), {
containerId: "mainPage",
disabled:true,
options: [
{ value: 'Beijing', label: '北京' },
{ value: 'Beijing2', label: '北京2'}
]
</div>
-->

4、group下拉--采用input+对象方式渲染

由input渲染

var options = [{
label: '热门城市',
options: [{
value: 'Shanghai',
label: '上海'
}, {
value: 'Beijing',
label: '北京'
}]
}, {
label: '城市名',
options: [{
value: 'Chengdu',
label: '成都'
}, {
value: 'Shenzhen',
label: '深圳'
}, {
value: 'Guangzhou',
label: '广州'
}, {
value: 'Dalian',
label: '大连'
}]
}]
var ctpUiComSelect = new CtpUiComGroupSelect($("#selGroup").get(0), {
containerId: "mainPage",
options: options
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

selGroup

"

name

=

"

selGroup

"

value

=

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

options

=

[

{

label

:

'热门城市'

,

options

:

[

{

value

:

'Shanghai'

,

label

:

'上海'

}

,

{

value

:

'Beijing'

,

label

:

'北京'

}

]

}

,

{

label

:

'城市名'

,

options

:

[

{

value

:

'Chengdu'

,

label

:

'成都'

}

,

{

value

:

'Shenzhen'

,

label

:

'深圳'

}

,

{

value

:

'Guangzhou'

,

label

:

'广州'

}

,

{

value

:

'Dalian'

,

label

:

'大连'

}

]

}

]

var

ctpUiComSelect

=

new

CtpUiComGroupSelect

(

$

(

"#selGroup"

)

.

get

(

0

)

,

{

containerId

:

"mainPage"

,

options

:

options

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

type

---------

控件类型

string

CtpUiComSelect

options

--------

下拉值集

Array

自定义

[]

----------

value

下拉项对应的值

string

自定义

----------

label

下拉项显示的label

string

自定义

disabled

--------

是否可以编辑

boolean

false/true

false

search

--------

是否可以过滤查询

boolean

false/true

false

width

--------

如果没有指定width，则采用select或者input的宽度作为下拉的宽度,如果设置了宽度，则以设置的宽度为准

number

containerId

--------

出现滚动条的容器，如果是body出现滚动条则不需要该参数

string

自定义

方法列表

方法名

说明

参数

getSelValue

获取选中的值

getSelText

获取选中的Text值

Select 多选选择器

CtpUiMultiSelect继承于CtpUiComSelect，select的方法和参数都适用于CtpUiMultiSelect

1、多选下拉选择器--采用input+comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiMultiSelect");方式来获取对象

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

input

type

=

"

text

"

id

=

"

name_text41444

"

name

=

"

name_text41444

"

value

=

"

Beijing;Beijing2

"

class

=

"

comp

"

comp

=

"

type:'CtpUiMultiSelect',containerId:'mainPage',options:[{value: 'Beijing',label: '北京'},{value: 'Beijing2',label: '北京2'},{value: 'Beijing3',label: '北京3'},{value: 'Beijing4',label: '北京4'}]

"

>

</

div

>

</

div

>

</

div

>

2、多选下拉选择器--采用select+comp方式渲染

由select渲染

dd

dd1

dd2

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由select渲染

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox_wrap

"

>

<

select

class

=

"

comp comp_select

"

comp

=

"

type:'CtpUiMultiSelect',search:true,containerId:'mainPage'

"

id

=

"

selMulti

"

>

<

option

value

=

"

dd

"

>

dd

</

option

>

<

option

value

=

"

dd1

"

selected

=

"

selected

"

>

dd1

</

option

>

<

option

value

=

"

dd2

"

>

dd2

</

option

>

</

select

>

</

div

>

</

div

>

</

div

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiMultiSelect

options

下拉值集

Array

自定义

[]

----------

value

下拉项对应的值

string

自定义

----------

label

下拉项显示的label

string

自定义

disabled

是否可以编辑

boolean

false/true

false

search

是否可以过滤查询

boolean

false/true

false

containerId

出现滚动条的容器，如果是body出现滚动条则不需要该参数

string

自定义

mouseover

通过鼠标移入移出来实现下拉的显示隐藏

boolean

false/true

false

方法列表

方法名

说明

参数 1

参数 2

attachEvent

注册方法

eventName[方法名]

fun[回调函数]

detachEvent

销毁方法

eventName[方法名]

setValue

设置下拉的值

value[下拉对应的value]

setValueByIndex

根据options的index设置下拉值

index[下拉序号]

setEnabled

设置为可以编辑

setDisabled

设置为不可以编辑

getOptionSize

获取选项的数量

getSelText

获取选中的Text值

getSelValue

获取选中的值

clearAll

清空所有值

addOption

添加选项

value

label

//清空以前的数据
$("#clearData").click(function(){
mulselOBj.clearAll();
})
//新增数据
$("#addData").click(function(){
mulselOBj.addOption(2,3);
})

//清空以前的数据
$("#clearData").click(function(){
mulselOBj.clearAll();
})
//新增数据
$("#addData").click(function(){
mulselOBj.addOption(2,3);
})

事件调用例子

dropdown.attachEvent("click", function(value, text){

// your code here

return true;

});

mulselOBj.attachEvent('onChange',function(val,text){

alert(mulselOBj.getSelValue())

})

event事件列表

eventName

参数 1

参数2

click

value [选项的value]

text[选项的text]

removeItem【多选下拉才有，移除选项】

value [选项的value]

text[选项的text]

onChange

afterInit

## 53. Slider 滑块

> 原始路径：`/components4.0/form/slider.html`  
> 相对路径：`components4.0/form/slider.md`  
> 页面 key：`v-4c184ad3`  
> JS Chunk：`84.fe1360f7.js`

Slider 滑块

普通滑块

new CtpUiSliderBlock(document.getElementById("slider"),{
width:'300px',
height:'50px',
min:0,
max:100,
value:30
});

<

div

id

=

"

slider

"

>

</

div

>

<

script

>

new

CtpUiSliderBlock

(

document

.

getElementById

(

"slider"

)

,

{

width

:

'300px'

,

height

:

'50px'

,

min

:

0

,

max

:

100

,

value

:

30

}

)

;

</

script

>

禁用滑块

new CtpUiSliderBlock(document.getElementById("slider1"),{
width:'300px',
height:'50px',
min:0,
max:100,
value:30,
disabled:true
});

<

div

id

=

"

slider1

"

>

</

div

>

<

script

>

new

CtpUiSliderBlock

(

document

.

getElementById

(

"slider1"

)

,

{

width

:

'300px'

,

height

:

'50px'

,

min

:

0

,

max

:

100

,

value

:

30

,

disabled

:

true

}

)

;

</

script

>

定制滑块tips

new CtpUiSliderBlock(document.getElementById("slider2"),{
width:'300px',
height:'50px',
min:100,
max:1000,
value:600,
tipsWidth:100,
tipsHTMLfuc:function(num){
return "测试："+num
}
});

<

div

id

=

"

slider2

"

>

</

div

>

<

script

>

new

CtpUiSliderBlock

(

document

.

getElementById

(

"slider2"

)

,

{

width

:

'300px'

,

height

:

'50px'

,

min

:

100

,

max

:

1000

,

value

:

600

,

tipsWidth

:

100

,

tipsHTMLfuc

:

function

(

num

)

{

return

"测试："

+

num

}

)

;

</

script

>

采用comp方式渲染

定制滑块tips

<

div

id

=

"

slider3

"

class

=

"

sliderBGstyle comp

"

comp

=

"

type:'CtpUiSliderBlock',width:'300px',height:'50px',min:100,max:1000,value:600,tipsWidth:100,tipsHTMLfuc:function(num){return '测试：'+num}

"

>

</

div

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

-

options

width

宽度(带单位)

String

200px

height

高度(带单位)

String

20px

tipsWidth

tips宽度（不带单位）

Number

32

tipsHTMLfuc

tips渲染function 返回字符串 自带参数为value的值

Function

id

String

min

最小值

Number

0

max

最大值

Number

100

value

当前值

Number

50

disabled

是否已禁用

Boolean

false

className

传入class

String

slierBlockCover

已使用样式

Style

slierBlockBg

未使用样式

Style

slierBlockCenter

滑块样式

Style

slierBlockCoverDisabled

已使用样式（禁用）

Style

slierBlockBgDisabled

未使用样式（禁用）

Style

slierBlockCenterDisabled

未使用样式

滑块样式 （禁用）

callbackFuc

改变值后的回调方法 自带参数为value的值

Function

方法列表

方法名

说明

参数

destory

销毁控件

setDisabled

设置是否已禁用

true/false

setValue

设置当前值

number

## 54. Switch 开关

> 原始路径：`/components4.0/form/switch.html`  
> 相对路径：`components4.0/form/switch.md`  
> 页面 key：`v-81f01c1a`  
> JS Chunk：`85.1ff4e0d6.js`

Switch 开关

表示两种相互对立的状态间的切换，多用于触发「开/关」。

采用对象方式渲染

基本用法

var testData1 = {
name: "T1",
activeValue: 1,
inactiveValue: 0
};
var test1 = new CtpUiSwitch(document.getElementById("ctpSwitch-demo1"), testData1);

<

div

id

=

"

ctpSwitch-demo1

"

class

=

"

ctpSwitch

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData1

=

{

name

:

"T1"

,

activeValue

:

1

,

inactiveValue

:

0

}

;

var

test1

=

new

CtpUiSwitch

(

document

.

getElementById

(

"ctpSwitch-demo1"

)

,

testData1

)

;

</

script

>

禁用

var testData2 = {
name: "T2",
on: false,
disabled: true,
activeValue: "on",
inactiveValue: "off"
};
var test2 = new CtpUiSwitch(document.getElementById("ctpSwitch-demo2"), testData2);

<

div

id

=

"

ctpSwitch-demo2

"

class

=

"

ctpSwitch

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData2

=

{

name

:

"T2"

,

on

:

false

,

disabled

:

true

,

activeValue

:

"on"

,

inactiveValue

:

"off"

}

;

var

test2

=

new

CtpUiSwitch

(

document

.

getElementById

(

"ctpSwitch-demo2"

)

,

testData2

)

;

</

script

>

文字描述、自定义颜色和宽度

var testData3 = {
name: "T3",
on: true,
width: 100,
activeText: "打开了",
inactiveText: "关闭了",
activeValue: 1,
inactiveValue: 0,
activeColor: "#ff0000",
inactiveColor: "#000000"
};
var test3 = new CtpUiSwitch(document.getElementById("ctpSwitch-demo3"), testData3);

<

div

id

=

"

ctpSwitch-demo3

"

class

=

"

ctpSwitch

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData3

=

{

name

:

"T3"

,

on

:

true

,

width

:

100

,

activeText

:

"打开了"

,

inactiveText

:

"关闭了"

,

activeValue

:

1

,

inactiveValue

:

0

,

activeColor

:

"#ff0000"

,

inactiveColor

:

"#000000"

}

;

var

test3

=

new

CtpUiSwitch

(

document

.

getElementById

(

"ctpSwitch-demo3"

)

,

testData3

)

;

</

script

>

支持一些方法：toggleStatus、on、off、enabled、disabled

切换状态

打开

关闭

enabled

disabled

var testData4 = {
name: "T4"
};
var test4 = new CtpUiSwitch(document.getElementById("ctpSwitch-demo4"), testData4);
window.toggleStatusDemo4 = function () {
test4.toggleStatus();
}
window.onDemo4 = function () {
test4.on();
}
window.offDemo4 = function () {
test4.off();
}
window.enabledDemo4 = function () {
test4.enabled();
}
window.disabledDemo4 = function () {
test4.disabled();
}

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

ctpSwitch-demo4

"

class

=

"

ctpSwitch

"

>

</

div

>

<

br

/>

<

a

href

=

"

javascript:window.toggleStatusDemo4()

"

class

=

"

common_button

"

>

切换状态

</

a

>

<

a

href

=

"

javascript:window.onDemo4()

"

class

=

"

common_button

"

>

打开

</

a

>

<

a

href

=

"

javascript:window.offDemo4()

"

class

=

"

common_button

"

>

关闭

</

a

>

<

a

href

=

"

javascript:window.enabledDemo4()

"

class

=

"

common_button

"

>

enabled

</

a

>

<

a

href

=

"

javascript:window.disabledDemo4()

"

class

=

"

common_button

"

>

disabled

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData4

=

{

name

:

"T4"

}

;

var

test4

=

new

CtpUiSwitch

(

document

.

getElementById

(

"ctpSwitch-demo4"

)

,

testData4

)

;

window

.

toggleStatusDemo4

=

function

(

)

{

test4

.

toggleStatus

(

)

;

}

window

.

onDemo4

=

function

(

)

{

test4

.

on

(

)

;

}

window

.

offDemo4

=

function

(

)

{

test4

.

off

(

)

;

}

window

.

enabledDemo4

=

function

(

)

{

test4

.

enabled

(

)

;

}

window

.

disabledDemo4

=

function

(

)

{

test4

.

disabled

(

)

;

}

</

script

>

采用comp方式渲染

基本用法

<

div

class

=

"

content

"

>

<

div

id

=

"

ctpSwitch1

"

class

=

"

comp

"

comp

=

"

type:'CtpUiSwitch',data:{name:'T11'}

"

>

</

div

>

</

div

>

禁用

<

div

class

=

"

content

"

>

<

div

id

=

"

ctpSwitch2

"

class

=

"

comp

"

comp

=

"

type:'CtpUiSwitch',data:{name:'T12',on:false,disabled:true}

"

>

</

div

>

</

div

>

文字描述、自定义颜色

<

div

class

=

"

content

"

>

<

div

id

=

"

ctpSwitch3

"

class

=

"

comp

"

comp

=

"

type:'CtpUiSwitch',data:{name:'T13',on:true,activeText:'ON',inactiveText:'OFF',activeColor:'#B200FF'}

"

>

</

div

>

</

div

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入

document.querySelector以获取到对应 DOM 节点

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

-

options

name

switch 对应的 name 属性(name值可用于form提交，选填项)

string

-

on

是否为打开状态（选填项）

boolean

true

disabled

是否禁用（选填项）

boolean

false

width

switch 的宽度（像素）（选填项）

number(最小值：30)

40

activeText

switch 打开时的描述文字（选填项）

string

-

inactiveText

switch 关闭时的描述文字（选填项）

string

-

activeValue

switch 打开时的值（选填项）

boolean / string / number

true

inactiveValue

switch 关闭时的值（选填项）

boolean / string / number

false

activeColor

switch 打开时的背景色（选填项）

string(HEX值，从"#000000"至"#ffffff")

-

inactiveColor

switch 关闭时的背景色（选填项）

string(HEX值，从"#000000"至"#ffffff")

-

方法列表(以对象方式渲染时)

方法

说明

参数

enabled

启用switch

-

disabled

禁用switch

-

toggleStatus

切换打开/关闭状态

-

on

设置switch为打开状态

-

off

设置switch为关闭状态

-

destory

销毁元素

-

## 55. TextArea 输入框

> 原始路径：`/components4.0/form/textArea.html`  
> 相对路径：`components4.0/form/textArea.md`  
> 页面 key：`v-4750e033`  
> JS Chunk：`38.3ade5a4b.js`

TextArea 输入框

1、普通的textArea输入框

普通的输入框

textarea

<

div

class

=

"

form_area clearfix

"

>

<

div

class

=

"

label

"

>

textarea

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox clearfix

"

>

<

textarea

rows

=

"

5

"

class

=

"

validate word_break_all

"

id

=

"

description2

"

validate

=

"

type:'string',name:'描述',notNull:false,maxLength:1000

"

style

=

"

width

:

450px

"

>

</

textarea

>

</

div

>

</

div

>

</

div

>

不可以编辑的输入框

普通输入框

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

普通输入框

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox clearfix

"

>

<

textarea

rows

=

"

5

"

class

=

"

validate word_break_all

"

disabled

=

"

disabled

"

id

=

"

description1

"

validate

=

"

type:'string',name:'描述',notNull:false,maxLength:1000

"

style

=

"

width

:

450px

"

>

</

textarea

>

</

div

>

</

div

>

</

div

>

2、带长度输入提醒的输入框---采用comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置

普通输入框

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

普通输入框

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox clearfix

"

>

<

textarea

rows

=

"

5

"

class

=

"

comp

"

comp

=

"

type:'CtpUiComTextArea',maxLength:50

"

id

=

"

description

"

validate

=

"

type:'string',name:'描述',notNull:false,maxLength:1000

"

style

=

"

width

:

450px

"

>

</

textarea

>

</

div

>

</

div

>

</

div

>

带长度输入提醒的输入框---采用对象方式渲染

普通输入框

var obj = new CtpUiComTextArea($("#textAreaObj").get(0),{maxLength:50});
obj.setErrorState("最多输入50个字符")

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

普通输入框

</

div

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

common_txtbox clearfix

"

>

<

textarea

rows

=

"

5

"

id

=

"

textAreaObj

"

validate

=

"

type:'string',name:'描述',notNull:false,maxLength:1000

"

style

=

"

width

:

450px

"

>

</

textarea

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

obj

=

new

CtpUiComTextArea

(

$

(

"#textAreaObj"

)

.

get

(

0

)

,

{

maxLength

:

50

}

)

;

obj

.

setErrorState

(

"最多输入50个字符"

)

</

script

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

textArea

maxLength

长度提醒值

number

自定义

0

## 56. TimePicker 时间选择器

> 原始路径：`/components4.0/form/timePicker.html`  
> 相对路径：`components4.0/form/timePicker.md`  
> 页面 key：`v-12013413`  
> JS Chunk：`86.70b0bfb4.js`

TimePicker 时间选择器

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiTimeSelect");方式来获取对象

【采用comp方式渲染】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiTimeSelect',containerId:'mainPage',format:'HH:mm:ss',pattern:'time'

"

/>

</

div

>

</

div

>

</

div

>

【采用input对象方式渲染】

时间选择

var ctpUiComSelect = new CtpUiTimeSelect($("#name_text5").get(0), {
pattern: 'time',
containerId: "mainPage",
format: 'HH:mm:ss'
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

时间选择

</

div

>

<

div

class

=

"

content

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

200px

;

float

:

left

"

>

<

input

type

=

"

text

"

id

=

"

name_text5

"

name

=

"

name_text1

"

value

=

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

ctpUiComSelect

=

new

CtpUiTimeSelect

(

$

(

"#name_text5"

)

.

get

(

0

)

,

{

pattern

:

'time'

,

containerId

:

"mainPage"

,

format

:

'HH:mm:ss'

}

)

;

</

script

>

【采用comp方式渲染,选择HH:mm 格式】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiTimeSelect',containerId:'mainPage',format:'HH:mm',pattern:'time'

"

/>

</

div

>

</

div

>

</

div

>

【采用对象方式渲染,选择 HH:mm 格式】

timeSelect

var ctpUiComSelect = new CtpUiTimeSelect($("#dateTime2").get(0), {
pattern: 'time',
containerId: "mainPage",
format: 'HH:mm'
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

timeSelect

</

div

>

<

div

class

=

"

content

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

200px

;

float

:

left

"

>

<

input

type

=

"

text

"

id

=

"

dateTime2

"

name

=

"

dateTime2

"

value

=

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

ctpUiComSelect

=

new

CtpUiTimeSelect

(

$

(

"#dateTime2"

)

.

get

(

0

)

,

{

pattern

:

'time'

,

containerId

:

"mainPage"

,

format

:

'HH:mm'

}

)

;

</

script

>

【采用comp方式渲染,选择时间段】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiTimeSelect',containerId:'mainPage',format:'HH:mm:ss',pattern:'timerange'

"

/>

</

div

>

</

div

>

</

div

>

【采用对象方式渲染,选择时间段 】

timeSelect

var ctpUiComSelect = new CtpUiTimeSelect($("#timerange").get(0), {
pattern: 'time',
containerId: "mainPage",
format: 'HH:mm'
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

timeSelect

</

div

>

<

div

class

=

"

content

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

200px

;

float

:

left

"

>

<

input

type

=

"

text

"

id

=

"

timerange

"

name

=

"

timerange

"

value

=

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

ctpUiComSelect

=

new

CtpUiTimeSelect

(

$

(

"#timerange"

)

.

get

(

0

)

,

{

pattern

:

'time'

,

containerId

:

"mainPage"

,

format

:

'HH:mm'

}

)

;

</

script

>

【采用comp方式渲染,选择时间段 HH:mm 格式】

由input渲染

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

由input渲染

</

div

>

<

div

class

=

"

go_content

"

style

=

"

width

:

310px

;

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

300px

;

"

>

<

input

id

=

"

mycal

"

type

=

"

text

"

class

=

"

comp

"

comp

=

"

type:'CtpUiTimeSelect',containerId:'mainPage',format:'HH:mm',pattern:'timerange'

"

/>

</

div

>

</

div

>

</

div

>

【采用对象方式渲染,选择时间段 HH:mm 格式】

timeSelect

var ctpUiComSelect = new CtpUiTimeSelect($("#timerange2").get(0), {
pattern: 'timerange',
containerId: "mainPage",
format: 'HH:mm'
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

label

"

>

timeSelect

</

div

>

<

div

class

=

"

content

"

>

<

div

class

=

"

common_txtbox_wrap

"

style

=

"

width

:

200px

;

float

:

left

"

>

<

input

type

=

"

text

"

id

=

"

timerange2

"

name

=

"

timerange2

"

value

=

"

04:05:05 - 05:02:01

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

ctpUiComSelect

=

new

CtpUiTimeSelect

(

$

(

"#timerange2"

)

.

get

(

0

)

,

{

pattern

:

'timerange'

,

containerId

:

"mainPage"

,

format

:

'HH:mm'

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiTimeSelect

options

参数

JSON

自定义

null

----------

format

时间的格式

string

HH:mm:ss/HH:mm

----------

pattern

显示类型

string

time/timerange

----------

containerId

出现滚动条的容器，如果是document.body出现滚动 则不需要进行设置

string

自定义

----------

placement

显示下拉区域

string

bottom,top

组件计算后决定显示位置

----------

beforeShow

显示隐藏下拉菜单前的回调方法

function

方法列表

方法名

说明

参数 1

参数 2

attachEvent

注册方法

eventName[方法名]

fun[回调函数]

detachEvent

销毁方法

eventName[方法名]

destory

销毁组件

getActiveItem

获取当前选中的item

type['min','hour','second']

num值

event事件列表

eventName

参数 1

参数2

onClick

date

onBeforeChange

date

onChange

date

state

## 57. Breadcrumb 面包屑

> 原始路径：`/components4.0/navigation/breadcrumb.html`  
> 相对路径：`components4.0/navigation/breadcrumb.md`  
> 页面 key：`v-ba58135a`  
> JS Chunk：`87.d923723f.js`

Breadcrumb 面包屑

首页

/

活动管理

/

活动列表

/

活动详情

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

breadcrumb

"

id

=

"

breadcrumb

"

style

=

"

display

:

block

;

"

>

<

span

class

=

"

nowLocation_content

"

>

<

a

style

=

"

cursor

:

default

"

>

首页

</

a

>

/

<

a

class

=

"

hand

"

onclick

=

"

javascript

:

void

(

0

)

"

>

活动管理

</

a

>

/

<

a

class

=

"

hand

"

onclick

=

"

javascript

:

void

(

0

)

"

>

活动列表

</

a

>

/

<

span

>

活动详情

</

span

>

</

span

>

</

div

>

</

div

>

</

div

>

属V5已有功能，暂无说明文档

## 58. Dropdown 下拉菜单

> 原始路径：`/components4.0/navigation/dropdown.html`  
> 相对路径：`components4.0/navigation/dropdown.md`  
> 页面 key：`v-4dbe3fd3`  
> JS Chunk：`88.52828b19.js`

Dropdown 下拉菜单

1、基础用法--comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiDropdown");方式来获取对象

下拉菜单

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

div

class

=

"

content

"

style

=

"

margin-bottom

:

100px

;

"

>

<

div

class

=

"

comp

"

comp

=

"

type:'CtpUiDropdown',align:'center',options:[{value: 'Beijing',label: '北京'},{value: 'Beijing1',label: '北京1'}]

"

style

=

"

width

:

80px

;

"

>

下拉菜单

</

div

>

</

div

>

</

div

>

</

div

>

</

div

>

2、基础用法--下拉菜单,存在不可以点击

下拉菜单

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

div

class

=

"

content

"

style

=

"

margin-bottom

:

100px

;

"

>

<

div

class

=

"

comp

"

comp

=

"

type:'CtpUiDropdown',options:[{value: 'Beijing',label: '北京',disabled:true},{value: 'Beijing1',label: '北京1'}]

"

style

=

"

padding

:

0 10px

;

width

:

80px

;

border-radius

:

12px

;

border

:

1px solid #dfdfdf

;

"

>

下拉菜单

</

div

>

</

div

>

</

div

>

</

div

>

</

div

>

3、基础用法--下拉菜单,存在图标

下拉菜单,存在图标

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

content

"

style

=

"

margin-bottom

:

100px

;

"

>

<

div

class

=

"

comp

"

comp

=

"

type:'CtpUiDropdown',align:'left',options:[{value: 'Beijing',label: '北京',icon:'syIcon sy-forwarding',iconColor:'#f00'},
{value: 'Beijing1',label: '北京1',icon:'syIcon sy-forwarding',iconColor:'#fF0'}]

"

style

=

"

width

:

130px

;

"

>

下拉菜单,存在图标

</

div

>

</

div

>

</

div

>

</

div

>

4、基础用法--下拉菜单,指定容器的宽度

下拉菜单,指定容器的宽度

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

style

=

"

margin-bottom

:

100px

;

"

>

<

div

class

=

"

comp

"

comp

=

"

type:'CtpUiDropdown',search:true,width:350,align:'left',options:[{value: 'Beijing',label: '北京',icon:'syIcon sy-forwarding',iconColor:'#f00'},
{type:'split'},
{value: 'Beijing1',label: '北京1',icon:'syIcon sy-forwarding',iconColor:'#fF0'}]

"

style

=

"

width

:

180px

;

"

>

下拉菜单,指定容器的宽度

</

div

>

</

div

>

</

div

>

5、基础用法--下拉菜单,从右边显示

下拉菜单,从右边显示

<

div

class

=

"

content

"

style

=

"

margin-bottom

:

100px

;

"

>

<

div

class

=

"

comp

"

comp

=

"

type:'CtpUiDropdown',width:350,align:'right',options:[{value: 'Beijing',label: '北京',icon:'syIcon sy-forwarding',iconColor:'#f00'},
{type:'split'},
{value: 'Beijing1',label: '北京1',icon:'syIcon sy-forwarding',iconColor:'#fF0'}]

"

style

=

"

width

:

130px

;

"

>

下拉菜单,从右边显示

</

div

>

</

div

>

6、基础用法--下拉菜单,采用对象渲染

下拉菜单

new CtpUiDropdown($("#dropMenuCtl").get(0),{width:130,options:[{value: 'Beijing',label: '北京',icon:'syIcon sy-forwarding',iconColor:'#f00'},
{type:'split'},
{value: 'Beijing1',label: '北京1',icon:'syIcon sy-forwarding',iconColor:'#fF0'}]});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

div

class

=

"

content

"

style

=

"

margin-bottom

:

100px

;

"

>

<

div

id

=

"

dropMenuCtl

"

style

=

"

padding

:

0 10px

;

width

:

80px

;

border-radius

:

12px

;

border

:

1px solid #dfdfdf

;

"

>

下拉菜单

</

div

>

</

div

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

new

CtpUiDropdown

(

$

(

"#dropMenuCtl"

)

.

get

(

0

)

,

{

width

:

130

,

options

:

[

{

value

:

'Beijing'

,

label

:

'北京'

,

icon

:

'syIcon sy-forwarding'

,

iconColor

:

'#f00'

}

,

{

type

:

'split'

}

,

{

value

:

'Beijing1'

,

label

:

'北京1'

,

icon

:

'syIcon sy-forwarding'

,

iconColor

:

'#fF0'

}

]

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiDropdown

options

下拉值集

Array

自定义

[]

----------

value

下拉项对应的值

string

自定义

----------

label

下拉项显示的label

string

自定义

----------

icon

字体图标

string

自定义

----------

iconColor

字体图标颜色

string

自定义

----------

disabled

下拉项是否disabled

boolean

true/false

false

----------

type

下拉项的类型 【item】表示普通项，【split】表示元素之间的分割线

string

item/split

item

----------

fun

选择数据的回调函数

function

自定义

align

下拉项的文字显示位置

string

left/center

left

radio

是否可以单选任意项

boolean

false/true

false

width

容器的宽度【如果定义了宽度，则取定义的宽度，

如果没有定义宽度，则取渲染元素的自身宽度作为下拉容器的宽度】

number

自定义

渲染元素的自身宽度

search

是否支持筛选

boolean

false/true

false

方法列表

方法名

说明

参数 1

参数 2

attachEvent

注册方法

eventName[方法名]

fun[回调函数]

detachEvent

销毁方法

eventName[方法名]

事件调用例子

dropdown.attachEvent("click", function(value, text){

// your code here

return true;

});

event事件列表

eventName

参数 1

参数2

click

value [选项的value]

text[选项的text]

afterInit

## 59. NavMenu 导航菜单

> 原始路径：`/components4.0/navigation/navMenu.html`  
> 相对路径：`components4.0/navigation/navMenu.md`  
> 页面 key：`v-306d1833`  
> JS Chunk：`89.4d87493d.js`

NavMenu 导航菜单

提供导航功能的菜单。

上边：子菜单通过hover触发

var testData1 = {
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test1 = new CtpUiNavMenu("#demo1", testData1);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo1

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData1

=

{

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test1

=

new

CtpUiNavMenu

(

"#demo1"

,

testData1

)

;

</

script

>

上边（暗黑皮肤）：子菜单通过hover触发

var testData2 = {
themes: "dark",
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test2 = new CtpUiNavMenu("#demo2", testData2);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo2

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData2

=

{

themes

:

"dark"

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test2

=

new

CtpUiNavMenu

(

"#demo2"

,

testData2

)

;

</

script

>

左侧：子菜单通过hover触发

var testData3 = {
themes: "dark",
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test3 = new CtpUiNavMenu("#demo3", testData3);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo3

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData3

=

{

themes

:

"dark"

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test3

=

new

CtpUiNavMenu

(

"#demo3"

,

testData3

)

;

</

script

>

左侧（暗黑皮肤）：子菜单通过hover触发

var testData4 = {
themes: "dark",
position: "left",
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test4 = new CtpUiNavMenu("#demo4", testData4);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo4

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData4

=

{

themes

:

"dark"

,

position

:

"left"

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test4

=

new

CtpUiNavMenu

(

"#demo4"

,

testData4

)

;

</

script

>

左侧：子菜单通过click触发

var testData5 = {
triggerMode: "click",
position: "left",
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test5 = new CtpUiNavMenu("#demo5", testData5);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo5

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData5

=

{

triggerMode

:

"click"

,

position

:

"left"

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test5

=

new

CtpUiNavMenu

(

"#demo5"

,

testData5

)

;

</

script

>

左侧（暗黑皮肤）：子菜单通过click触发

var testData6 = {
themes: "dark",
triggerMode: "click",
position: "left",
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test6 = new CtpUiNavMenu("#demo6", testData6);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo6

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData6

=

{

themes

:

"dark"

,

triggerMode

:

"click"

,

position

:

"left"

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test6

=

new

CtpUiNavMenu

(

"#demo6"

,

testData6

)

;

</

script

>

上边（暗黑皮肤）：指定高度(100px)和宽度(800px)

var testData7 = {
width: 800,
height: 100,
themes: "dark",
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test7 = new CtpUiNavMenu("#demo7", testData7);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo7

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData7

=

{

width

:

800

,

height

:

100

,

themes

:

"dark"

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test7

=

new

CtpUiNavMenu

(

"#demo7"

,

testData7

)

;

</

script

>

左侧（暗黑皮肤）：指定高度(500px)和宽度(500px)

var testData8 = {
width: 500,
height: 500,
position: "left",
themes: "dark",
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test8 = new CtpUiNavMenu("#demo8", testData8);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo8

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData8

=

{

width

:

500

,

height

:

500

,

position

:

"left"

,

themes

:

"dark"

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test8

=

new

CtpUiNavMenu

(

"#demo8"

,

testData8

)

;

</

script

>

左侧（暗黑皮肤）：默认为折叠状态

var testData9 = {
position: "left",
themes: "dark",
stretch: false,
items: [{
icon: "sy-PC",
id: "nav1",
name: "菜单一",
url : null,
items: [{
icon: "sy-notification",
id: "nav1_1",
name: "二级菜单一-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1",
name: "三级菜单一-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1",
name: "四级菜单一-1-1-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "五级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "六级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "七级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "八级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "九级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main",
items: [{
icon: "sy-notification",
id: "nav1_1_1_1_1",
name: "十级菜单一-1-1-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "十级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "十级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "九级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "九级菜单-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "八级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "八级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "七级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "七级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "六级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "六级菜单一-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_1_2",
name: "五级菜单一-1-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_1_3",
name: "五级菜单一1-1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_1_2",
name: "四级菜单一-1-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_1_3",
name: "四级菜单一1-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_1_2",
name: "三级菜单一-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_1_3",
name: "三级菜单一-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav1_2",
name: "二级菜单一-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_3",
name: "二级菜单一-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_4",
name: "二级菜单一-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav1_5",
name: "二级菜单一-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-newmeeting",
id: "nav2",
name: "菜单二",
url : null,
clickFun: function () {
$.alert("我支持自定义事件");
}
},{
icon: "sy-msg",
id: "nav3",
name: "菜单三",
url : null,
items: [{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav3_1",
name: "五级菜单三-1",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-html",
id: "nav4",
name: "菜单四",
url : null
},{
icon: "sy-process",
id: "nav5",
name: "菜单五",
url : null
},{
icon: "sy-print",
id: "nav6",
name: "菜单六",
url : null
},{
icon: "sy-toback",
id: "nav7",
name: "菜单七",
url : null
},{
icon: "sy-flow",
id: "nav8",
name: "菜单八",
url : null
},{
icon: "sy-signa",
id: "nav9",
name: "菜单九",
url : null
},{
icon: "sy-release",
id: "nav10",
name: "菜单十",
url : null
},{
icon: "sy-PC",
id: "nav11",
name: "菜单十一",
url : null
},{
icon: "sy-PC",
id: "nav12",
name: "菜单十二",
url : null
},{
icon: "sy-PC",
id: "nav13",
name: "菜单十三",
url : null
},{
icon: "sy-PC",
id: "nav14",
name: "菜单十四",
url : null
},{
icon: "sy-PC",
id: "nav15",
name: "菜单十五",
url : null
},{
icon: "sy-PC",
id: "nav16",
name: "菜单十六",
url : null,
items: [{
icon: "sy-notification",
id: "nav16_1",
name: "二级菜单十六-1",
url: null,
items: [{
icon: "sy-notification",
id: "nav16_1_1",
name: "二级菜单十六-1_1",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_2",
name: "二级菜单十六-1-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_1_3",
name: "二级菜单十六-1-3",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-notification",
id: "nav16_2",
name: "二级菜单十六-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_3",
name: "二级菜单十六-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_4",
name: "二级菜单十六-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav16_5",
name: "二级菜单十六-5",
url: "http:///www.baidu.com",
target: "main"
}]
},{
icon: "sy-PC",
id: "nav17",
name: "菜单十七",
url : null
},{
icon: "sy-PC",
id: "nav18",
name: "菜单十八",
url : null
},{
icon: "sy-PC",
id: "nav19",
name: "菜单十九",
url : null
},{
icon: "sy-PC",
id: "nav20",
name: "菜单二十",
url : null,
items: [{
icon: "sy-notification",
id: "nav20_1",
name: "二级菜单二十-1",
url: null
},{
icon: "sy-notification",
id: "nav20_2",
name: "二级菜单二十-2",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_3",
name: "二级菜单二十-3",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_4",
name: "二级菜单二十-4",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_5",
name: "二级菜单二十-5",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_6",
name: "二级菜单二十-6",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_7",
name: "二级菜单二十-7",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_8",
name: "二级菜单二十-8",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_9",
name: "二级菜单二十-9",
url: "http:///www.baidu.com",
target: "main"
},{
icon: "sy-notification",
id: "nav20_10",
name: "二级菜单二十-10",
url: "http:///www.baidu.com",
target: "main"
}]
}]
}
var test9 = new CtpUiNavMenu("#demo9", testData9);

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo9

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData9

=

{

position

:

"left"

,

themes

:

"dark"

,

stretch

:

false

,

items

:

[

{

icon

:

"sy-PC"

,

id

:

"nav1"

,

name

:

"菜单一"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1"

,

name

:

"二级菜单一-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1"

,

name

:

"三级菜单一-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1"

,

name

:

"四级菜单一-1-1-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"五级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"六级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"七级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"八级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"九级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_1"

,

name

:

"十级菜单一-1-1-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"十级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"十级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"九级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"九级菜单-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"八级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"八级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"七级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"七级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"六级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"六级菜单一-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_2"

,

name

:

"五级菜单一-1-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_1_3"

,

name

:

"五级菜单一1-1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_2"

,

name

:

"四级菜单一-1-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_1_3"

,

name

:

"四级菜单一1-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_2"

,

name

:

"三级菜单一-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_1_3"

,

name

:

"三级菜单一-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_2"

,

name

:

"二级菜单一-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_3"

,

name

:

"二级菜单一-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_4"

,

name

:

"二级菜单一-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav1_5"

,

name

:

"二级菜单一-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-newmeeting"

,

id

:

"nav2"

,

name

:

"菜单二"

,

url

:

null

,

clickFun

:

function

(

)

{

$

.

alert

(

"我支持自定义事件"

)

;

}

,

{

icon

:

"sy-msg"

,

id

:

"nav3"

,

name

:

"菜单三"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav3_1"

,

name

:

"五级菜单三-1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-html"

,

id

:

"nav4"

,

name

:

"菜单四"

,

url

:

null

}

,

{

icon

:

"sy-process"

,

id

:

"nav5"

,

name

:

"菜单五"

,

url

:

null

}

,

{

icon

:

"sy-print"

,

id

:

"nav6"

,

name

:

"菜单六"

,

url

:

null

}

,

{

icon

:

"sy-toback"

,

id

:

"nav7"

,

name

:

"菜单七"

,

url

:

null

}

,

{

icon

:

"sy-flow"

,

id

:

"nav8"

,

name

:

"菜单八"

,

url

:

null

}

,

{

icon

:

"sy-signa"

,

id

:

"nav9"

,

name

:

"菜单九"

,

url

:

null

}

,

{

icon

:

"sy-release"

,

id

:

"nav10"

,

name

:

"菜单十"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav11"

,

name

:

"菜单十一"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav12"

,

name

:

"菜单十二"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav13"

,

name

:

"菜单十三"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav14"

,

name

:

"菜单十四"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav15"

,

name

:

"菜单十五"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav16"

,

name

:

"菜单十六"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1"

,

name

:

"二级菜单十六-1"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav16_1_1"

,

name

:

"二级菜单十六-1_1"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_2"

,

name

:

"二级菜单十六-1-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_1_3"

,

name

:

"二级菜单十六-1-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_2"

,

name

:

"二级菜单十六-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_3"

,

name

:

"二级菜单十六-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_4"

,

name

:

"二级菜单十六-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav16_5"

,

name

:

"二级菜单十六-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

,

{

icon

:

"sy-PC"

,

id

:

"nav17"

,

name

:

"菜单十七"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav18"

,

name

:

"菜单十八"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav19"

,

name

:

"菜单十九"

,

url

:

null

}

,

{

icon

:

"sy-PC"

,

id

:

"nav20"

,

name

:

"菜单二十"

,

url

:

null

,

items

:

[

{

icon

:

"sy-notification"

,

id

:

"nav20_1"

,

name

:

"二级菜单二十-1"

,

url

:

null

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_2"

,

name

:

"二级菜单二十-2"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_3"

,

name

:

"二级菜单二十-3"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_4"

,

name

:

"二级菜单二十-4"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_5"

,

name

:

"二级菜单二十-5"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_6"

,

name

:

"二级菜单二十-6"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_7"

,

name

:

"二级菜单二十-7"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_8"

,

name

:

"二级菜单二十-8"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_9"

,

name

:

"二级菜单二十-9"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

,

{

icon

:

"sy-notification"

,

id

:

"nav20_10"

,

name

:

"二级菜单二十-10"

,

url

:

"http:///www.baidu.com"

,

target

:

"main"

}

]

}

]

}

var

test9

=

new

CtpUiNavMenu

(

"#demo9"

,

testData9

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

elObj

-

被渲染的dom(必填)

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入

document.querySelector以获取到对应 DOM 节点

-

options（类型：object）(必填项)

position

菜单的位置：上边/左侧（选填）

string

"top"

"left"

"top"

themes

-

皮肤风格：明亮/暗黑（选填）

string

"light"

"dark"

"light"

width

-

菜单的宽度（选填）

string / number

支持格式：

1、"100%"

2、100（组件会自动转换为100px）

position为"top"时：100%

position为"left"时：240px

height

-

菜单的高度（选填）

string / number

支持格式：

1、"100%"

2、100（组件会自动转换为100px）

position为"top"时：50px

position为"left"时：100%

triggerMode

-

子级菜单的展现方式（选填）

hover: 鼠标移入时显示子菜单

click: 鼠标点击时显示子菜单

string

"hover"

"click"

"hover"

stretch

-

是否处于展开状态（选填）

Boolean

true

false

true

item（类型：array）,由1-N个object组件

每个object下的内容包含右侧这些

id

当前菜单的id(选填)

string/number

icon

当前菜单的图标（选填）

string

name

当前菜单的文字（必填）

string

url

当前菜单的链接（选填）

function

target

打开当前链接的iframe的id或name（如果url有值时必填，否则选填）

string

clickFun

当前菜单的自定义事件（选填）

function

current

当前菜单是否处于高亮状态（选填）

Boolean

true

false

方法列表(以对象方式渲染时)

方法

说明

参数

stretchOn

展开菜单（仅左侧菜单支持）

-

stretchOff

收起菜单（仅左侧菜单支持）

-

destory

销毁元素

-

本区域用于展示菜单点击后切换iframe链接的效果，请点击菜单进行体验。

![](https://open.seeyoncloud.com/v5devUIComp/about:blank)

## 60. Steps 步骤条

> 原始路径：`/components4.0/navigation/steps.html`  
> 相对路径：`components4.0/navigation/steps.md`  
> 页面 key：`v-60049cae`  
> JS Chunk：`90.efa8ff12.js`

Steps 步骤条

采用对象方式渲染

//样式1
var testData1_1 = {
styleType: 1,
active: 3,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test1_1 = new CtpUiStep("#demo1-1",testData1_1);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo1-1

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式1

var

testData1_1

=

{

styleType

:

1

,

active

:

3

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test1_1

=

new

CtpUiStep

(

"#demo1-1"

,

testData1_1

)

;

</

script

>

//样式1：极简模式
var testData1_2 = {
styleType: 1,
active: 3,
simple: true,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test1_2 = new CtpUiStep("#demo1-2",testData1_2);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo1-2

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式1：极简模式

var

testData1_2

=

{

styleType

:

1

,

active

:

3

,

simple

:

true

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test1_2

=

new

CtpUiStep

(

"#demo1-2"

,

testData1_2

)

;

</

script

>

//样式2
var testData2_1 = {
styleType: 2,
active: 3,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test2_1 = new CtpUiStep("#demo2-1",testData2_1);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo2-1

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式2

var

testData2_1

=

{

styleType

:

2

,

active

:

3

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test2_1

=

new

CtpUiStep

(

"#demo2-1"

,

testData2_1

)

;

</

script

>

//样式2：极简模式
var testData2_2 = {
styleType: 2,
active: 3,
simple: true,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test2_2 = new CtpUiStep("#demo2-2",testData2_2);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo2-2

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式2：极简模式

var

testData2_2

=

{

styleType

:

2

,

active

:

3

,

simple

:

true

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test2_2

=

new

CtpUiStep

(

"#demo2-2"

,

testData2_2

)

;

</

script

>

//样式3
var testData3_1 = {
styleType: 3,
active: 3,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test3_1 = new CtpUiStep("#demo3-1",testData3_1);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo3-1

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式3

var

testData3_1

=

{

styleType

:

3

,

active

:

3

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test3_1

=

new

CtpUiStep

(

"#demo3-1"

,

testData3_1

)

;

</

script

>

//样式3：极简模式
var testData3_2 = {
styleType: 3,
active: 3,
simple: true,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test3_2 = new CtpUiStep("#demo3-2",testData3_2);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo3-2

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式3：极简模式

var

testData3_2

=

{

styleType

:

3

,

active

:

3

,

simple

:

true

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test3_2

=

new

CtpUiStep

(

"#demo3-2"

,

testData3_2

)

;

</

script

>

//样式4：仅支持极简模式
var testData4 = {
styleType: 4,
active: 3,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test4 = new CtpUiStep("#demo4",testData4);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo4

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式4：仅支持极简模式

var

testData4

=

{

styleType

:

4

,

active

:

3

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test4

=

new

CtpUiStep

(

"#demo4"

,

testData4

)

;

</

script

>

//样式5：仅支持极简模式
var testData5 = {
styleType: 5,
active: 3,
items: [
{
label: "步骤 1",
desc: "这里是步骤1 的描述信息",
icon: "sy-modify",
clickFun: function() {
$.alert('这是步骤1的自定义事件');
}
},
{
label: "步骤 2",
desc: "这里是步骤2 的描述信息"
},{
label: "步骤 3",
desc: "200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"
},{
label: "步骤 4",
desc: "这里是步骤4 的描述信息"
},{
label: "步骤 5",
desc: "这里是步骤5 的描述信息"
}
]
}
var test5 = new CtpUiStep("#demo5",testData5);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo5

"

>

</

div

>

</

div

>

</

div

>

<

script

>

//样式5：仅支持极简模式

var

testData5

=

{

styleType

:

5

,

active

:

3

,

items

:

[

{

label

:

"步骤 1"

,

desc

:

"这里是步骤1 的描述信息"

,

icon

:

"sy-modify"

,

clickFun

:

function

(

)

{

$

.

alert

(

'这是步骤1的自定义事件'

)

;

}

,

{

label

:

"步骤 2"

,

desc

:

"这里是步骤2 的描述信息"

}

,

{

label

:

"步骤 3"

,

desc

:

"200多万年来，人类始终被一个终极难题困扰：今天吃什么？明天吃什么？？后天吃什么？？？ 然而，正是在解决这个问题的过程中，人类技术得以进步、生活品质得以提高、精神文明得以丰富。"

}

,

{

label

:

"步骤 4"

,

desc

:

"这里是步骤4 的描述信息"

}

,

{

label

:

"步骤 5"

,

desc

:

"这里是步骤5 的描述信息"

}

]

}

var

test5

=

new

CtpUiStep

(

"#demo5"

,

testData5

)

;

</

script

>

采用comp方式渲染

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp

"

comp

=

"

type:'CtpUiStep',options:{styleType:1,active:3}

"

>

<

div

step-label

=

"

万里长征第1步

"

step-desc

=

"

这里是万里长征第1步 的描述信息

"

step-icon

=

"

sy-modify

"

step-clickFun

=

"

javascript:$.alert('这是万里长征第1步的自定义事件')

"

>

</

div

>

<

div

step-label

=

"

万里长征第2步

"

step-desc

=

"

这里是万里长征第2步 的描述信息

"

>

</

div

>

<

div

step-label

=

"

万里长征第3步

"

step-desc

=

"

这里是万里长征第3步 的描述信息

"

>

</

div

>

<

div

step-label

=

"

万里长征第4步

"

step-desc

=

"

这里是万里长征第4步 的描述信息

"

>

</

div

>

<

div

step-label

=

"

万里长征第5步

"

step-desc

=

"

这里是万里长征第5步 的描述信息，测试一下字数非常非常多的效果呢。

"

>

</

div

>

</

div

>

</

div

>

</

div

>

参数列表

参数

说明

类型

默认值

elObj

-

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入

document.querySelector以获取到对应 DOM 节点

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

（必填项）

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

-

options（类型：object）(必填项)

styleType

1、2、3、4、5

number

1

simple

-

是否为极简样式，极简样式不显示描述性文字（选填）

boolean

false

active

-

当前步骤的序号，序号从1开始(选填项)

number

1

item（类型：array）,由1-N个object组件，每个object下的内容包含右侧这些

label

当前步骤的标题(必填)

string

-

desc

当前步骤的描述文字（选填）

string

-

icon

当前步骤的图标（选填）

string

-

clickFun

当前步骤的自定义事件（选填）

function

-

color

当前步骤的文字和图标颜色（选填）

string(HEX值，从"#000000"至"#ffffff")

-

方法列表(以对象方式渲染时)

方法

说明

参数

destory

销毁元素

-

## 61. Tabs 标签页

> 原始路径：`/components4.0/navigation/tabs.html`  
> 相对路径：`components4.0/navigation/tabs.md`  
> 页面 key：`v-7edf649a`  
> JS Chunk：`91.8f40da75.js`

Tabs 标签页

export default {
data() {
return {}
},
methods: {},
mounted() {
<!--beforebegin--><div class="language- extra-class"><!--afterbegin--><pre><code> }
}
</code></pre>
<!--beforeend--></div><!--afterend-->

.ctpUiTabsBody {
padding: 20px;
}
.ctpUiTabs.size_XL .ctpUiTabsHeader>ul li {
height: 100%;
text-overflow: ellipsis;
white-space: nowrap;
}

## Tabs 标签页

采用对象方式渲染

基础样式

新增1个页签

删除第2个

disabled第2个

enabled第2个

var testData1 = {
size: "s",
styleType: 1,
items: [{
label: "选项卡1",
icon: "sy-internationalization-resources",
number: 123,
id: "tabs1"
},{
label: "选项卡2",
icon: "sy-word-to-pdf",
number: 99,
id: "tabs2",
clickFun: function(){
alert("我是选项卡2，支持传入自定义函数");
}
},{
label: "选项卡3",
icon: "sy-video-meeting",
number: 0,
disabled: true
},{
label: "选项卡4"
},{
label: "选项卡5"
},{
label: "选项卡6",
current: true
}]
};
var test1 = new CtpUiTabs(document.getElementById("demoDiv1"), testData1);

//新增
var add4Demo1 = function(){
test1.add({
item: {
label: "我是新来的",
id: "newId",
icon: "sy-PC"
}
});
}
//删除
var remove4Demo1 = function(){
test1.remove(1);
}
//disabled
var disabled4Demo1 = function(){
test1.disabled(1);
}
//enabled
var enabled4Demo1 = function(){
test1.enabled(1);
}

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demoDiv1

"

>

</

div

>

<

br

/>

<

a

href

=

"

javascript:window.add4Demo1()

"

class

=

"

common_button

"

title

=

"

新增1个页签

"

>

新增1个页签

</

a

>

<

a

href

=

"

javascript:window.remove4Demo1()

"

class

=

"

common_button

"

title

=

"

删除第2个

"

>

删除第2个

</

a

>

<

a

href

=

"

javascript:window.disabled4Demo1()

"

class

=

"

common_button

"

title

=

"

disabled第2个

"

>

disabled第2个

</

a

>

<

a

href

=

"

javascript:window.enabled4Demo1()

"

class

=

"

common_button

"

title

=

"

enabled第2个

"

>

enabled第2个

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData1

=

{

size

:

"s"

,

styleType

:

1

,

items

:

[

{

label

:

"选项卡1"

,

icon

:

"sy-internationalization-resources"

,

number

:

123

,

id

:

"tabs1"

}

,

{

label

:

"选项卡2"

,

icon

:

"sy-word-to-pdf"

,

number

:

99

,

id

:

"tabs2"

,

clickFun

:

function

(

)

{

alert

(

"我是选项卡2，支持传入自定义函数"

)

;

}

,

{

label

:

"选项卡3"

,

icon

:

"sy-video-meeting"

,

number

:

0

,

disabled

:

true

}

,

{

label

:

"选项卡4"

}

,

{

label

:

"选项卡5"

}

,

{

label

:

"选项卡6"

,

current

:

true

}

]

}

;

var

test1

=

new

CtpUiTabs

(

document

.

getElementById

(

"demoDiv1"

)

,

testData1

)

;

//新增

var

add4Demo1

=

function

(

)

{

test1

.

add

(

{

item

:

{

label

:

"我是新来的"

,

id

:

"newId"

,

icon

:

"sy-PC"

}

)

;

}

//删除

var

remove4Demo1

=

function

(

)

{

test1

.

remove

(

1

)

;

}

//disabled

var

disabled4Demo1

=

function

(

)

{

test1

.

disabled

(

1

)

;

}

//enabled

var

enabled4Demo1

=

function

(

)

{

test1

.

enabled

(

1

)

;

}

</

script

>

采用dom+comp方式渲染

基础样式

尺寸S

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

选项卡6

选项卡7

选项卡8

选项卡9

选项卡10

名字很长的选项卡11

选项卡12

选项卡13

选项卡14

选项卡15

选项卡16

选项卡17

选项卡18

选项卡19

选项卡20

选项卡21

选项卡22

选项卡23

选项卡24

选项卡25

选项卡26

选项卡27

选项卡28

选项卡29

选项卡30

我是内容区

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:1,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

class

=

"

current

"

>

选项卡5

</

li

>

<

li

>

选项卡6

</

li

>

<

li

class

=

"

disabled

"

>

选项卡7

</

li

>

<

li

>

选项卡8

</

li

>

<

li

>

选项卡9

</

li

>

<

li

>

选项卡10

</

li

>

<

li

>

名字很长的选项卡11

</

li

>

<

li

>

选项卡12

</

li

>

<

li

>

选项卡13

</

li

>

<

li

>

选项卡14

</

li

>

<

li

>

选项卡15

</

li

>

<

li

>

选项卡16

</

li

>

<

li

>

选项卡17

</

li

>

<

li

>

选项卡18

</

li

>

<

li

>

选项卡19

</

li

>

<

li

>

选项卡20

</

li

>

<

li

>

选项卡21

</

li

>

<

li

>

选项卡22

</

li

>

<

li

>

选项卡23

</

li

>

<

li

>

选项卡24

</

li

>

<

li

class

=

"

disabled

"

>

选项卡25

</

li

>

<

li

>

选项卡26

</

li

>

<

li

>

选项卡27

</

li

>

<

li

>

选项卡28

</

li

>

<

li

>

选项卡29

</

li

>

<

li

>

选项卡30

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

尺寸M

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{size:'M'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸L

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{size:'L'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸XL

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{size:'XL'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡样式-带边框的

尺寸S

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:2,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸M

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:2,size:'M'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸L

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:2,size:'L'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸XL

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:2,size:'XL'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡样式-带背景的

尺寸S

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:3,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸M

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:3,size:'M'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸L

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:3,size:'L'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸XL

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:3,size:'XL'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡样式-带边框和背景的

尺寸S

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸M

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'M'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸L

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'L'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

尺寸XL

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'XL'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

选项卡1

</

li

>

<

li

>

选项卡2

</

li

>

<

li

>

选项卡3

</

li

>

<

li

>

选项卡4

</

li

>

<

li

>

选项卡5

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

扩展：

纯图标

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:1,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:2,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:3,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

<

li

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

图标+文字

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:1,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:2,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:3,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡1

选项卡2

选项卡3

选项卡4

选项卡5

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

图标+文字+数字

选项卡1

999

选项卡2

123

选项卡3

0

选项卡4

888

选项卡5

666

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:1,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

<

div

class

=

"

tabsNumber

"

>

999

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

<

div

class

=

"

tabsNumber

"

>

123

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

<

div

class

=

"

tabsNumber

"

>

0

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

<

div

class

=

"

tabsNumber

"

>

888

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

<

div

class

=

"

tabsNumber

"

>

666

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡1

999

选项卡2

123

选项卡3

0

选项卡4

888

选项卡5

666

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:2,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

<

div

class

=

"

tabsNumber

"

>

999

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

<

div

class

=

"

tabsNumber

"

>

123

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

<

div

class

=

"

tabsNumber

"

>

0

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

<

div

class

=

"

tabsNumber

"

>

888

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

<

div

class

=

"

tabsNumber

"

>

666

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡1

999

选项卡2

123

选项卡3

0

选项卡4

888

选项卡5

666

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:3,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

<

div

class

=

"

tabsNumber

"

>

999

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

<

div

class

=

"

tabsNumber

"

>

123

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

<

div

class

=

"

tabsNumber

"

>

0

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

<

div

class

=

"

tabsNumber

"

>

888

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

<

div

class

=

"

tabsNumber

"

>

666

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡1

999

选项卡2

123

选项卡3

0

选项卡4

888

选项卡5

666

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'S'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

<

div

class

=

"

tabsNumber

"

>

999

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

<

div

class

=

"

tabsNumber

"

>

123

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

<

div

class

=

"

tabsNumber

"

>

0

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

<

div

class

=

"

tabsNumber

"

>

888

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

<

div

class

=

"

tabsNumber

"

>

666

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

选项卡1

999

选项卡2

123

选项卡3

0

选项卡4

888

选项卡5

666

我是内容区

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiTabs comp

"

comp

=

"

type:'CtpUiTabs',options:{styleType:4,size:'XL'}

"

>

<

div

class

=

"

ctpUiTabsHeader

"

>

<

ul

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡1

</

div

>

<

div

class

=

"

tabsNumber

"

>

999

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡2

</

div

>

<

div

class

=

"

tabsNumber

"

>

123

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡3

</

div

>

<

div

class

=

"

tabsNumber

"

>

0

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡4

</

div

>

<

div

class

=

"

tabsNumber

"

>

888

</

div

>

</

li

>

<

li

>

<

div

class

=

"

tabsIcon

"

>

<

i

class

=

"

syIcon sy-PC

"

>

</

i

>

</

div

>

<

div

class

=

"

tabsLabel

"

>

选项卡5

</

div

>

<

div

class

=

"

tabsNumber

"

>

666

</

div

>

</

li

>

</

ul

>

</

div

>

<

div

class

=

"

ctpUiTabsBody

"

>

我是内容区

</

div

>

</

div

>

</

div

>

</

div

>

参数列表（以comp方式渲染时）

参数

说明

类型

是否必填

默认值

size

tabs标签页的尺寸（选填项）

string

否

"M"

styleType

tabs标签页的样式：

1、Tabs 标签页

2、带边框的选项卡样式

3、带背景的选项卡样式

4、带边框和背景的选项卡样式

（选填项）

string

否

1

adaptationWidth

是否以tabs父元素宽度为基准，将宽度均分给每个页签

Boolean

否

false

参数列表（以对象方式渲染时）

参数

说明

类型

是否必填

默认值

size

tabs标签页的尺寸（选填项）

string

否

"M"

styleType

tabs标签页的样式：

1、Tabs 标签页

2、带边框的选项卡样式

3、带背景的选项卡样式

4、带边框和背景的选项卡样式

（选填项）

string

否

1

adaptationWidth

是否以tabs父元素宽度为基准，将宽度均分给每个页签

Boolean

否

false

items

--

array,由多个object组成

是

-

items下的object格式：

key

value

类型

是否必填

默认值

label

标签的文字

String

否

-

icon

标签的图标class

String

否

-

current

是否为高亮选中状态

Boolean

否

false

disabled

是否为disabled状态

Boolean

否

false

number

标签的角标数字

String

否

-

clickFun

标签的事件

function

否

-

方法列表(仅支持以对象方式渲染时)

方法

说明

参数

demo

setCurrent

选中某个页签

序号，从0开始

add

添加一个页签

index: 从0开始，在第index个页签后面插入，如果未传，默认插至末尾

item：页签的内容，属性参照上面(items下的object格式)

xxx.add({

index:1,

item:{

label:"我是新来的",

icon:"xxIcon"

}

})

remove

删除一个页签

序号，从0开始，如果未传，删除末尾的页签

xxx.remove(0)

enabled

enabled一个页签

序号，从0开始

xxx.enabled(0)

disabled

disabled一个页签

序号，从0开始

xxx.disabled(0)

destory

销毁元素

-

补充

对于comp方式渲染时需要重新渲染，请使用如下方式：

new CtpUiTabs(document.querySelector("#xxx"));

document.querySelector("#xxx")既是您想重新渲染的元素。

## 62. Alert 警告提示

> 原始路径：`/components4.0/notice/alert.html`  
> 相对路径：`components4.0/notice/alert.md`  
> 页面 key：`v-3cd4b137`  
> JS Chunk：`39.dc2991a8.js`

Alert 警告提示

用于页面中展示重要的提示信息。

采用对象方式渲染

基础用法

页面中的非浮层元素，不会自动消失。

var testData1 = {
title: "成功提示的文案",
type: "success"
}
var test1 = new CtpUiAlert(document.getElementById("demoDiv1"), testData1);

var testData2 = {
title: "消息提示的文案",
type: "info"
}
var test2 = new CtpUiAlert(document.getElementById("demoDiv2"), testData2);

var testData3 = {
title: "警告提示的文案",
type: "warning"
}
var test3 = new CtpUiAlert(document.getElementById("demoDiv3"), testData3);

var testData4 = {
title: "错误提示的文案",
type: "error"
}
var test4 = new CtpUiAlert(document.getElementById("demoDiv4"), testData4);

var testData5 = {
title: "说明提示的文案",
type: "explain"
}
var test5 = new CtpUiAlert(document.getElementById("demoDiv5"), testData5);

<

div

id

=

"

demoDiv1

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv2

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv3

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv4

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv5

"

class

=

"

demoBlock

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData1

=

{

title

:

"成功提示的文案"

,

type

:

"success"

}

var

test1

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv1"

)

,

testData1

)

;

var

testData2

=

{

title

:

"消息提示的文案"

,

type

:

"info"

}

var

test2

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv2"

)

,

testData2

)

;

var

testData3

=

{

title

:

"警告提示的文案"

,

type

:

"warning"

}

var

test3

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv3"

)

,

testData3

)

;

var

testData4

=

{

title

:

"错误提示的文案"

,

type

:

"error"

}

var

test4

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv4"

)

,

testData4

)

;

var

testData5

=

{

title

:

"说明提示的文案"

,

type

:

"explain"

}

var

test5

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv5"

)

,

testData5

)

;

</

script

>

带有 icon

表示某种状态时提升可读性。

var testData11 = {
title: "成功提示的文案",
type: "success",
showIcon: true
}
var test11 = new CtpUiAlert(document.getElementById("demoDiv11"), testData11);

var testData12 = {
title: "消息提示的文案",
type: "info",
showIcon: true
}
var test12 = new CtpUiAlert(document.getElementById("demoDiv12"), testData12);

var testData13 = {
title: "警告提示的文案",
type: "warning",
showIcon: true
}
var test13 = new CtpUiAlert(document.getElementById("demoDiv13"), testData13);

var testData14 = {
title: "错误提示的文案",
type: "error",
showIcon: true
}
var test14 = new CtpUiAlert(document.getElementById("demoDiv14"), testData14);

var testData15 = {
title: "说明提示的文案",
type: "explain",
showIcon: true
}
var test15 = new CtpUiAlert(document.getElementById("demoDiv15"), testData15);

<

div

id

=

"

demoDiv11

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv12

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv13

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv14

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv15

"

class

=

"

demoBlock

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData11

=

{

title

:

"成功提示的文案"

,

type

:

"success"

,

showIcon

:

true

}

var

test11

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv11"

)

,

testData11

)

;

var

testData12

=

{

title

:

"消息提示的文案"

,

type

:

"info"

,

showIcon

:

true

}

var

test12

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv12"

)

,

testData12

)

;

var

testData13

=

{

title

:

"警告提示的文案"

,

type

:

"warning"

,

showIcon

:

true

}

var

test13

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv13"

)

,

testData13

)

;

var

testData14

=

{

title

:

"错误提示的文案"

,

type

:

"error"

,

showIcon

:

true

}

var

test14

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv14"

)

,

testData14

)

;

var

testData15

=

{

title

:

"说明提示的文案"

,

type

:

"explain"

,

showIcon

:

true

}

var

test15

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv15"

)

,

testData15

)

;

</

script

>

文案居中

使用 center 属性让文案水平居中

var testData21 = {
title: "成功提示的文案",
type: "success",
showIcon: true,
center: true
}
var test21 = new CtpUiAlert(document.getElementById("demoDiv21"), testData21);

var testData22 = {
title: "消息提示的文案",
type: "info",
showIcon: true,
center: true
}
var test22 = new CtpUiAlert(document.getElementById("demoDiv22"), testData22);

var testData23 = {
title: "警告提示的文案",
type: "warning",
showIcon: true,
center: true
}
var test23 = new CtpUiAlert(document.getElementById("demoDiv23"), testData23);

var testData24 = {
title: "错误提示的文案",
type: "error",
showIcon: true,
center: true
}
var test24 = new CtpUiAlert(document.getElementById("demoDiv24"), testData24);

var testData25 = {
title: "说明提示的文案",
type: "explain",
showIcon: true,
center: true
}
var test25 = new CtpUiAlert(document.getElementById("demoDiv25"), testData25);

<

div

id

=

"

demoDiv21

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv22

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv23

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv24

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv25

"

class

=

"

demoBlock

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData21

=

{

title

:

"成功提示的文案"

,

type

:

"success"

,

showIcon

:

true

,

center

:

true

}

var

test21

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv21"

)

,

testData21

)

;

var

testData22

=

{

title

:

"消息提示的文案"

,

type

:

"info"

,

showIcon

:

true

,

center

:

true

}

var

test22

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv22"

)

,

testData22

)

;

var

testData23

=

{

title

:

"警告提示的文案"

,

type

:

"warning"

,

showIcon

:

true

,

center

:

true

}

var

test23

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv23"

)

,

testData23

)

;

var

testData24

=

{

title

:

"错误提示的文案"

,

type

:

"error"

,

showIcon

:

true

,

center

:

true

}

var

test24

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv24"

)

,

testData24

)

;

var

testData25

=

{

title

:

"说明提示的文案"

,

type

:

"explain"

,

showIcon

:

true

,

center

:

true

}

var

test25

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv25"

)

,

testData25

)

;

</

script

>

带有 icon 和辅助性文案介绍

包含标题和内容，解释更详细的警告。

// 带有 icon 和辅助性文案介绍
var testData31 = {
title: "成功提示的文案",
type: "success",
showIcon: true,
description: "我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"
}
var test31 = new CtpUiAlert(document.getElementById("demoDiv31"), testData31);

var testData32 = {
title: "消息提示的文案",
type: "info",
showIcon: true,
description: "我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"
}
var test32 = new CtpUiAlert(document.getElementById("demoDiv32"), testData32);

var testData33 = {
title: "警告提示的文案",
type: "warning",
showIcon: true,
description: "我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"
}
var test33 = new CtpUiAlert(document.getElementById("demoDiv33"), testData33);

var testData34 = {
title: "错误提示的文案",
type: "error",
showIcon: true,
description: "我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"
}
var test34 = new CtpUiAlert(document.getElementById("demoDiv34"), testData34);

var testData35 = {
title: "说明提示的文案",
type: "explain",
showIcon: true,
description: "我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"
}
var test35 = new CtpUiAlert(document.getElementById("demoDiv35"), testData35);

<

div

id

=

"

demoDiv31

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv32

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv33

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv34

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv35

"

class

=

"

demoBlock

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

// 带有 icon 和辅助性文案介绍

var

testData31

=

{

title

:

"成功提示的文案"

,

type

:

"success"

,

showIcon

:

true

,

description

:

"我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"

}

var

test31

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv31"

)

,

testData31

)

;

var

testData32

=

{

title

:

"消息提示的文案"

,

type

:

"info"

,

showIcon

:

true

,

description

:

"我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"

}

var

test32

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv32"

)

,

testData32

)

;

var

testData33

=

{

title

:

"警告提示的文案"

,

type

:

"warning"

,

showIcon

:

true

,

description

:

"我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"

}

var

test33

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv33"

)

,

testData33

)

;

var

testData34

=

{

title

:

"错误提示的文案"

,

type

:

"error"

,

showIcon

:

true

,

description

:

"我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"

}

var

test34

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv34"

)

,

testData34

)

;

var

testData35

=

{

title

:

"说明提示的文案"

,

type

:

"explain"

,

showIcon

:

true

,

description

:

"我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说，我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。"

}

var

test35

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv35"

)

,

testData35

)

;

</

script

>

自定义按钮

自定义关闭按钮为文案或其他符号。

//自定义关闭按钮
var testData41 = {
title: "成功提示的文案",
type: "success",
customClose: {
type: "text",
text: "我知道了"
}
}
var test41 = new CtpUiAlert(document.getElementById("demoDiv41"), testData41);

var testData42 = {
title: "消息提示的文案",
type: "error",
customClose: {
type: "button",
text: "已阅"
}
}
var test42 = new CtpUiAlert(document.getElementById("demoDiv42"), testData42);

<

div

id

=

"

demoDiv41

"

class

=

"

demoBlock

"

>

</

div

>

<

div

id

=

"

demoDiv42

"

class

=

"

demoBlock

"

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//自定义关闭按钮

var

testData41

=

{

title

:

"成功提示的文案"

,

type

:

"success"

,

customClose

:

{

type

:

"text"

,

text

:

"我知道了"

}

var

test41

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv41"

)

,

testData41

)

;

var

testData42

=

{

title

:

"消息提示的文案"

,

type

:

"error"

,

customClose

:

{

type

:

"button"

,

text

:

"已阅"

}

var

test42

=

new

CtpUiAlert

(

document

.

getElementById

(

"demoDiv42"

)

,

testData42

)

;

</

script

>

采用comp方式渲染

<

div

id

=

"

ctpUiAlert1

"

class

=

"

comp

"

comp

=

"

type:'CtpUiAlert',options:{title:'成功提示的文案',type:'success',clickFun:'alert(\'关闭之前我还想干点什么\')'}

"

>

</

div

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

-

options

title

标题（必填）

string

-

type

主题/类型（选填）

string("success"/"info"/"warning"/"error"/"explain")

"info"

targetWindow

本组件被渲染至哪一层window（选填）

window对象

组件被调用的window(当前window)

如果需要弹至顶层window，建议使用getCtpTop()

description

辅助性文案（选填）

string

-

customClass

自定义class（选填）

string

-

closable

是否可关闭（选填）

boolean

true

center

文案是否居中（选填）

boolean

false

textWrap

文字是否换行

boolean

false

closeText

关闭按钮自定义文本（选填）

string

-

showIcon

是否显示图标（选填）

boolean

false

customClose

自定义的关闭按钮（选填）

类型为一个object

type

自定义关闭按钮的类型：text、button

string

-

text

自定义关闭按钮的文字内容

string

-

方法列表

方法

说明

参数

destory

销毁元素

-

## 63. Loading 加载

> 原始路径：`/components4.0/notice/loading.html`  
> 相对路径：`components4.0/notice/loading.md`  
> 页面 key：`v-ac699612`  
> JS Chunk：`40.eef90760.js`

Loading 加载

(不支持IE8，IE8仅支持旧的progressBar组件)
加载数据时显示动效。

样式1

(自定义了文字和背景色)

开始loading

结束loading

//开启loading组件
var demo1 = Object.create(null);
window.openLoading1 = function() {
if(document.querySelector("#demoDiv1").querySelector(".ctpUiLoading")) {
$.alert("本区域中已存在loading组件了，请先关闭它");
return;
}
demo1 = $.progressBar({
styleType: 1,
target: "#demoDiv1",
text: "加载中，请稍等，亲",
background: "#B200FF"
});
}
window.openLoading1();
window.closeLoading1 = function() {
if(!document.querySelector("#demoDiv1").querySelector(".ctpUiLoading")) {
$.alert("本区域中不存在loading组件，请先开启它");
return;
}
demo1.close();
}
//关闭loading组件
// demo1.close();

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:window.openLoading1()

"

class

=

"

common_button

"

>

开始loading

</

a

>

<

a

href

=

"

javascript:window.closeLoading1()

"

class

=

"

common_button

"

>

结束loading

</

a

>

<

div

id

=

"

demoDiv1

"

class

=

"

loadingDemoBlock

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//开启loading组件

var

demo1

=

Object

.

create

(

null

)

;

window

.

openLoading1

=

function

(

)

{

if

(

document

.

querySelector

(

"#demoDiv1"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中已存在loading组件了，请先关闭它"

)

;

return

;

}

demo1

=

$

.

progressBar

(

{

styleType

:

1

,

target

:

"#demoDiv1"

,

text

:

"加载中，请稍等，亲"

,

background

:

"#B200FF"

}

)

;

}

window

.

openLoading1

(

)

;

window

.

closeLoading1

=

function

(

)

{

if

(

!

document

.

querySelector

(

"#demoDiv1"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中不存在loading组件，请先开启它"

)

;

return

;

}

demo1

.

close

(

)

;

}

//关闭loading组件

// demo1.close();

</

script

>

样式2

开始loading

结束loading

var demo2 = Object.create(null);
window.openLoading2 = function() {
if(document.querySelector("#demoDiv2").querySelector(".ctpUiLoading")) {
$.alert("本区域中已存在loading组件了，请先关闭它");
return;
}
demo2 = $.progressBar({
styleType: 2,
target: "#demoDiv2"
});
}
window.openLoading2();
window.closeLoading2 = function() {
if(!document.querySelector("#demoDiv2").querySelector(".ctpUiLoading")) {
$.alert("本区域中不存在loading组件，请先开启它");
return;
}
demo2.close();
}

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:window.openLoading2()

"

class

=

"

common_button

"

>

开始loading

</

a

>

<

a

href

=

"

javascript:window.closeLoading2()

"

class

=

"

common_button

"

>

结束loading

</

a

>

<

div

id

=

"

demoDiv2

"

class

=

"

loadingDemoBlock

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

demo2

=

Object

.

create

(

null

)

;

window

.

openLoading2

=

function

(

)

{

if

(

document

.

querySelector

(

"#demoDiv2"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中已存在loading组件了，请先关闭它"

)

;

return

;

}

demo2

=

$

.

progressBar

(

{

styleType

:

2

,

target

:

"#demoDiv2"

}

)

;

}

window

.

openLoading2

(

)

;

window

.

closeLoading2

=

function

(

)

{

if

(

!

document

.

querySelector

(

"#demoDiv2"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中不存在loading组件，请先开启它"

)

;

return

;

}

demo2

.

close

(

)

;

}

</

script

>

样式3

开始loading

结束loading

var demo3 = Object.create(null);
window.openLoading3 = function() {
if(document.querySelector("#demoDiv3").querySelector(".ctpUiLoading")) {
$.alert("本区域中已存在loading组件了，请先关闭它");
return;
}
demo3 = $.progressBar({
styleType: 3,
target: "#demoDiv3"
});
}
window.openLoading3();
window.closeLoading3 = function() {
if(!document.querySelector("#demoDiv3").querySelector(".ctpUiLoading")) {
$.alert("本区域中不存在loading组件，请先开启它");
return;
}
demo3.close();
}

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:window.openLoading3()

"

class

=

"

common_button

"

>

开始loading

</

a

>

<

a

href

=

"

javascript:window.closeLoading3()

"

class

=

"

common_button

"

>

结束loading

</

a

>

<

div

id

=

"

demoDiv3

"

class

=

"

loadingDemoBlock

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

demo3

=

Object

.

create

(

null

)

;

window

.

openLoading3

=

function

(

)

{

if

(

document

.

querySelector

(

"#demoDiv3"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中已存在loading组件了，请先关闭它"

)

;

return

;

}

demo3

=

$

.

progressBar

(

{

styleType

:

3

,

target

:

"#demoDiv3"

}

)

;

}

window

.

openLoading3

(

)

;

window

.

closeLoading3

=

function

(

)

{

if

(

!

document

.

querySelector

(

"#demoDiv3"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中不存在loading组件，请先开启它"

)

;

return

;

}

demo3

.

close

(

)

;

}

</

script

>

样式4

开始loading

结束loading

var demo4 = Object.create(null);
window.openLoading4 = function() {
if(document.querySelector("#demoDiv4").querySelector(".ctpUiLoading")) {
$.alert("本区域中已存在loading组件了，请先关闭它");
return;
}
demo4 = $.progressBar({
styleType: 4,
target: "#demoDiv4"
});
}
window.openLoading4();
window.closeLoading4 = function() {
if(!document.querySelector("#demoDiv4").querySelector(".ctpUiLoading")) {
$.alert("本区域中不存在loading组件，请先开启它");
return;
}
demo4.close();
}

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:window.openLoading4()

"

class

=

"

common_button

"

>

开始loading

</

a

>

<

a

href

=

"

javascript:window.closeLoading4()

"

class

=

"

common_button

"

>

结束loading

</

a

>

<

div

id

=

"

demoDiv4

"

class

=

"

loadingDemoBlock

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

demo4

=

Object

.

create

(

null

)

;

window

.

openLoading4

=

function

(

)

{

if

(

document

.

querySelector

(

"#demoDiv4"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中已存在loading组件了，请先关闭它"

)

;

return

;

}

demo4

=

$

.

progressBar

(

{

styleType

:

4

,

target

:

"#demoDiv4"

}

)

;

}

window

.

openLoading4

(

)

;

window

.

closeLoading4

=

function

(

)

{

if

(

!

document

.

querySelector

(

"#demoDiv4"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中不存在loading组件，请先开启它"

)

;

return

;

}

demo4

.

close

(

)

;

}

</

script

>

样式5

开始loading

结束loading

var demo5 = Object.create(null);
window.openLoading5 = function() {
if(document.querySelector("#demoDiv5").querySelector(".ctpUiLoading")) {
$.alert("本区域中已存在loading组件了，请先关闭它");
return;
}
demo5 = $.progressBar({
styleType: 5,
target: "#demoDiv5"
});
}
window.openLoading5();
window.closeLoading5 = function() {
if(!document.querySelector("#demoDiv5").querySelector(".ctpUiLoading")) {
$.alert("本区域中不存在loading组件，请先开启它");
return;
}
demo5.close();
}

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:window.openLoading5()

"

class

=

"

common_button

"

>

开始loading

</

a

>

<

a

href

=

"

javascript:window.closeLoading5()

"

class

=

"

common_button

"

>

结束loading

</

a

>

<

div

id

=

"

demoDiv5

"

class

=

"

loadingDemoBlock

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

demo5

=

Object

.

create

(

null

)

;

window

.

openLoading5

=

function

(

)

{

if

(

document

.

querySelector

(

"#demoDiv5"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中已存在loading组件了，请先关闭它"

)

;

return

;

}

demo5

=

$

.

progressBar

(

{

styleType

:

5

,

target

:

"#demoDiv5"

}

)

;

}

window

.

openLoading5

(

)

;

window

.

closeLoading5

=

function

(

)

{

if

(

!

document

.

querySelector

(

"#demoDiv5"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中不存在loading组件，请先开启它"

)

;

return

;

}

demo5

.

close

(

)

;

}

</

script

>

样式6

开始loading

结束loading

var demo6 = Object.create(null);
window.openLoading6 = function() {
if(document.querySelector("#demoDiv6").querySelector(".ctpUiLoading")) {
$.alert("本区域中已存在loading组件了，请先关闭它");
return;
}
demo6 = $.progressBar({
styleType: 6,
target: "#demoDiv6"
});
}
window.openLoading6();
window.closeLoading6 = function() {
if(!document.querySelector("#demoDiv6").querySelector(".ctpUiLoading")) {
$.alert("本区域中不存在loading组件，请先开启它");
return;
}
demo6.close();
}

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:window.openLoading6()

"

class

=

"

common_button

"

>

开始loading

</

a

>

<

a

href

=

"

javascript:window.closeLoading6()

"

class

=

"

common_button

"

>

结束loading

</

a

>

<

div

id

=

"

demoDiv6

"

class

=

"

loadingDemoBlock

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

demo6

=

Object

.

create

(

null

)

;

window

.

openLoading6

=

function

(

)

{

if

(

document

.

querySelector

(

"#demoDiv6"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中已存在loading组件了，请先关闭它"

)

;

return

;

}

demo6

=

$

.

progressBar

(

{

styleType

:

6

,

target

:

"#demoDiv6"

}

)

;

}

window

.

openLoading6

(

)

;

window

.

closeLoading6

=

function

(

)

{

if

(

!

document

.

querySelector

(

"#demoDiv6"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中不存在loading组件，请先开启它"

)

;

return

;

}

demo6

.

close

(

)

;

}

</

script

>

样式7

开始loading

结束loading

var demo7 = Object.create(null);
window.openLoading7 = function() {
if(document.querySelector("#demoDiv7").querySelector(".ctpUiLoading")) {
$.alert("本区域中已存在loading组件了，请先关闭它");
return;
}
demo7 = $.progressBar({
styleType: 7,
target: "#demoDiv7"
});
}
window.openLoading7();
window.closeLoading7 = function() {
if(!document.querySelector("#demoDiv7").querySelector(".ctpUiLoading")) {
$.alert("本区域中不存在loading组件，请先开启它");
return;
}
demo7.close();
}

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:window.openLoading7()

"

class

=

"

common_button

"

>

开始loading

</

a

>

<

a

href

=

"

javascript:window.closeLoading7()

"

class

=

"

common_button

"

>

结束loading

</

a

>

<

div

id

=

"

demoDiv7

"

class

=

"

loadingDemoBlock

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

demo7

=

Object

.

create

(

null

)

;

window

.

openLoading7

=

function

(

)

{

if

(

document

.

querySelector

(

"#demoDiv7"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中已存在loading组件了，请先关闭它"

)

;

return

;

}

demo7

=

$

.

progressBar

(

{

styleType

:

7

,

target

:

"#demoDiv7"

}

)

;

}

window

.

openLoading7

(

)

;

window

.

closeLoading7

=

function

(

)

{

if

(

!

document

.

querySelector

(

"#demoDiv7"

)

.

querySelector

(

".ctpUiLoading"

)

{

$

.

alert

(

"本区域中不存在loading组件，请先开启它"

)

;

return

;

}

demo7

.

close

(

)

;

}

</

script

>

参数列表

参数

说明

类型

默认值

styleType

样式(1-7) （选填）

number

1

target

Loading 需要覆盖的 DOM 节点(必须支持postion为relative或的absolute节点)。

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点（选填）

-

getCtpTop()

text

显示在加载图标下方的加载文案（选填）

string

-

background

遮罩层的背景色（选填）

string

rgba(0,0,0,0.25)

方法列表

方法

说明

参数

close

关闭loading层，并销毁元素

-

## 64. Message 消息提示

> 原始路径：`/components4.0/notice/message.html`  
> 相对路径：`components4.0/notice/message.md`  
> 页面 key：`v-c1831dbe`  
> JS Chunk：`92.e8f81138.js`

Message 消息提示

常用于主动操作后的反馈提示。与 Notification 的区别是后者更多用于系统级通知的被动提醒。。

采用对象方式渲染

基础用法

从顶部出现，3 秒后自动消失。

成功的提示

消息的提示

警告的提示

错误的提示

说明的提示

//成功提示的文案
$("#button1").on("click", function () {
var test1 = new CtpUiMessage({
title: "成功提示的文案",
type: "success"
});
});
//消息提示的文案
$("#button2").on("click", function () {
var test2 = new CtpUiMessage({
title: "消息提示的文案",
type: "info"
});
});
//警告提示的文案
$("#button3").on("click", function () {
var test3 = new CtpUiMessage({
title: "警告提示的文案",
type: "warning"
});
});
//错误提示的文案
$("#button4").on("click", function () {
var test4 = new CtpUiMessage({
title: "错误提示的文案",
type: "error"
});
});
//说明提示的文字
$("#button5").on("click", function () {
var test5 = new CtpUiMessage({
title: "说明提示的文字",
type: "explain"
});
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button1

"

class

=

"

common_button

"

>

成功的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button2

"

class

=

"

common_button

"

>

消息的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button3

"

class

=

"

common_button

"

>

警告的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button4

"

class

=

"

common_button

"

>

错误的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button5

"

class

=

"

common_button

"

>

说明的提示

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//成功提示的文案

$

(

"#button1"

)

.

on

(

"click"

,

function

(

)

{

var

test1

=

new

CtpUiMessage

(

{

title

:

"成功提示的文案"

,

type

:

"success"

}

)

;

}

)

;

//消息提示的文案

$

(

"#button2"

)

.

on

(

"click"

,

function

(

)

{

var

test2

=

new

CtpUiMessage

(

{

title

:

"消息提示的文案"

,

type

:

"info"

}

)

;

}

)

;

//警告提示的文案

$

(

"#button3"

)

.

on

(

"click"

,

function

(

)

{

var

test3

=

new

CtpUiMessage

(

{

title

:

"警告提示的文案"

,

type

:

"warning"

}

)

;

}

)

;

//错误提示的文案

$

(

"#button4"

)

.

on

(

"click"

,

function

(

)

{

var

test4

=

new

CtpUiMessage

(

{

title

:

"错误提示的文案"

,

type

:

"error"

}

)

;

}

)

;

//说明提示的文字

$

(

"#button5"

)

.

on

(

"click"

,

function

(

)

{

var

test5

=

new

CtpUiMessage

(

{

title

:

"说明提示的文字"

,

type

:

"explain"

}

)

;

}

)

;

</

script

>

可关闭

可以添加关闭按钮。。

成功的提示

消息的提示

警告的提示

错误的提示

说明的提示

//成功提示的文案
$("#button11").on("click", function(){
var test11 = new CtpUiMessage({
title: "成功提示的文案",
type: "success",
showClose: true,
customClose: {
type: "button",
text: "我知道了"
},
onCloseFun: function() {
alert("我是点击关闭按钮后触发的自定义函数");
}
});
});
//消息提示的文案
$("#button12").on("click", function(){
var test12 = new CtpUiMessage({
title: "消息提示的文案",
type: "info",
showClose: true
});
});
//警告提示的文案
$("#button13").on("click", function(){
var test13 = new CtpUiMessage({
title: "警告提示的文案",
type: "warning",
showClose: true
});
});
//错误提示的文案
$("#button14").on("click", function(){
var test14 = new CtpUiMessage({
title: "错误提示的文案",
type: "error",
showClose: true
});
});
//说明提示的文字
$("#button15").on("click", function(){
var test15 = new CtpUiMessage({
title: "说明提示的文字",
type: "explain",
showClose: true
});
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button11

"

class

=

"

common_button

"

>

成功的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button12

"

class

=

"

common_button

"

>

消息的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button13

"

class

=

"

common_button

"

>

警告的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button14

"

class

=

"

common_button

"

>

错误的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button15

"

class

=

"

common_button

"

>

说明的提示

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//成功提示的文案

$

(

"#button11"

)

.

on

(

"click"

,

function

(

)

{

var

test11

=

new

CtpUiMessage

(

{

title

:

"成功提示的文案"

,

type

:

"success"

,

showClose

:

true

,

customClose

:

{

type

:

"button"

,

text

:

"我知道了"

}

,

onCloseFun

:

function

(

)

{

alert

(

"我是点击关闭按钮后触发的自定义函数"

)

;

}

)

;

}

)

;

//消息提示的文案

$

(

"#button12"

)

.

on

(

"click"

,

function

(

)

{

var

test12

=

new

CtpUiMessage

(

{

title

:

"消息提示的文案"

,

type

:

"info"

,

showClose

:

true

}

)

;

}

)

;

//警告提示的文案

$

(

"#button13"

)

.

on

(

"click"

,

function

(

)

{

var

test13

=

new

CtpUiMessage

(

{

title

:

"警告提示的文案"

,

type

:

"warning"

,

showClose

:

true

}

)

;

}

)

;

//错误提示的文案

$

(

"#button14"

)

.

on

(

"click"

,

function

(

)

{

var

test14

=

new

CtpUiMessage

(

{

title

:

"错误提示的文案"

,

type

:

"error"

,

showClose

:

true

}

)

;

}

)

;

//说明提示的文字

$

(

"#button15"

)

.

on

(

"click"

,

function

(

)

{

var

test15

=

new

CtpUiMessage

(

{

title

:

"说明提示的文字"

,

type

:

"explain"

,

showClose

:

true

}

)

;

}

)

;

</

script

>

文字居中

使用 center 属性让文字水平居中

成功的提示

消息的提示

警告的提示

错误的提示

说明的提示

//成功提示的文案
$("#button21").on("click", function(){
var test21 = new CtpUiMessage({
title: "成功提示的文案",
type: "success",
center: true
});
});
//消息提示的文案
$("#button22").on("click", function(){
var test22 = new CtpUiMessage({
title: "消息提示的文案",
type: "info",
center: true
});
});
//警告提示的文案
$("#button23").on("click", function(){
var test23 = new CtpUiMessage({
title: "警告提示的文案",
type: "warning",
center: true
});
});
//错误提示的文案
$("#button24").on("click", function(){
var test24 = new CtpUiMessage({
title: "错误提示的文案",
type: "error",
center: true
});
});
//说明提示的文字
$("#button25").on("click", function(){
var test25 = new CtpUiMessage({
title: "说明提示的文字",
type: "explain",
center: true
});
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button21

"

class

=

"

common_button

"

>

成功的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button22

"

class

=

"

common_button

"

>

消息的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button23

"

class

=

"

common_button

"

>

警告的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button24

"

class

=

"

common_button

"

>

错误的提示

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

button25

"

class

=

"

common_button

"

>

说明的提示

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//成功提示的文案

$

(

"#button21"

)

.

on

(

"click"

,

function

(

)

{

var

test21

=

new

CtpUiMessage

(

{

title

:

"成功提示的文案"

,

type

:

"success"

,

center

:

true

}

)

;

}

)

;

//消息提示的文案

$

(

"#button22"

)

.

on

(

"click"

,

function

(

)

{

var

test22

=

new

CtpUiMessage

(

{

title

:

"消息提示的文案"

,

type

:

"info"

,

center

:

true

}

)

;

}

)

;

//警告提示的文案

$

(

"#button23"

)

.

on

(

"click"

,

function

(

)

{

var

test23

=

new

CtpUiMessage

(

{

title

:

"警告提示的文案"

,

type

:

"warning"

,

center

:

true

}

)

;

}

)

;

//错误提示的文案

$

(

"#button24"

)

.

on

(

"click"

,

function

(

)

{

var

test24

=

new

CtpUiMessage

(

{

title

:

"错误提示的文案"

,

type

:

"error"

,

center

:

true

}

)

;

}

)

;

//说明提示的文字

$

(

"#button25"

)

.

on

(

"click"

,

function

(

)

{

var

test25

=

new

CtpUiMessage

(

{

title

:

"说明提示的文字"

,

type

:

"explain"

,

center

:

true

}

)

;

}

)

;

</

script

>

采用对象方式渲染

此种调用的场景不如“采用对象方式渲染”多，因为message常出现于执行某个操作之后的触发，comp组件都是在页面加载后直接渲染，仅适用于一些特殊页面。

comp方式调用时，会在页面加载时自动渲染,请看页面顶部的触发效果

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp

"

comp

=

"

type:'CtpUiMessage',options:{title:'我是通过comp方式触发的message提示信息',type:'success'}

"

>

comp方式调用时，会在页面加载时自动渲染,请看页面顶部的触发效果

</

div

>

</

div

>

</

div

>

参数列表

参数

说明

类型

默认值

options

title

标题（必填）

string

-

type

主题/类型（选填）

string("success"/"info"/"warning"/"error"/"explain")

"info"

targetWindow

本组件被渲染至哪一层window（选填）

window对象

组件被调用的window(当前window)

如果需要弹至顶层window，建议使用getCtpTop()

customClass

自定义class（选填）

string

-

showClose

是否显示关闭按钮（选填）

boolean

false

center

文案是否居中（选填）

boolean

false

textWrap

文字是否换行

boolean

false

closeText

关闭按钮自定义文本（选填）

string

-

duration

显示时间, 毫秒。设为 0 则不会自动关闭（选填）

number

3000

onCloseFun

点击关闭按钮时触发的回调函数（选填）

function

-

offsetTop

距离窗口顶部的偏移量(px)（选填）

number

20

customClose

自定义的关闭按钮（选填）

类型为一个object

type

自定义关闭按钮的类型：text、button

string

-

text

自定义关闭按钮的文字内容

string

-

方法列表

方法

说明

参数

destory

销毁元素

-

## 65. Notification 通知

> 原始路径：`/components4.0/notice/notification.html`  
> 相对路径：`components4.0/notice/notification.md`  
> 页面 key：`v-5b447bda`  
> JS Chunk：`19.256478f0.js`

Notification 通知

悬浮出现在页面角落，显示全局的通知提醒消息。

关闭所有通知

基础用法

新通知

$("#newNotificationBase").click(function(event) {
window.CtpUiComNotification0 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
position:"topRight",//topRight/topLeft/bottomRight/bottomLeft
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){
console.log("这是onClick callback的提示消息");
}
});
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotificationBase

"

class

=

"

common_button

"

>

新通知

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

$

(

"#newNotificationBase"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification0

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

position

:

"topRight"

,

//topRight/topLeft/bottomRight/bottomLeft

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

console

.

log

(

"这是onClick callback的提示消息"

)

;

}

)

;

}

)

;

</

script

>

自定义弹出位置

可以让 Notification 从屏幕四角中的任意一角弹出

使用position属性定义 Notification 的弹出位置，支持四个选项：topRight、topLeft、bottomRight、bottomLeft，默认为topRight。

左上角

顶部中间

右上角

右侧中间

右下角

底部中间

左下角

左侧中间

正中间

$("#newNotification1").click(function(event) {
window.CtpUiComNotification1 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"topLeft",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});
$("#newNotification2").click(function(event) {
window.CtpUiComNotification2 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"topCenter",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotification3").click(function(event) {
window.CtpUiComNotification3 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"topRight",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotification4").click(function(event) {
window.CtpUiComNotification4 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"rightCenter",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotification5").click(function(event) {
window.CtpUiComNotification5 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"bottomRight",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotification6").click(function(event) {
window.CtpUiComNotification6 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"bottomCenter",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotification7").click(function(event) {
window.CtpUiComNotification7 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"bottomLeft",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotification8").click(function(event) {
window.CtpUiComNotification8 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"leftCenter",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotification9").click(function(event) {
window.CtpUiComNotification9 = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条通知的内容文字，随意啊啦啦啦啦',
showClose:true,
position:"centerCenter",//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification1

"

class

=

"

common_button

"

>

左上角

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification2

"

class

=

"

common_button margin_l_10

"

>

顶部中间

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification3

"

class

=

"

common_button margin_l_10

"

>

右上角

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification4

"

class

=

"

common_button margin_l_10

"

>

右侧中间

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification5

"

class

=

"

common_button margin_l_10

"

>

右下角

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification6

"

class

=

"

common_button margin_l_10

"

>

底部中间

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification7

"

class

=

"

common_button margin_l_10

"

>

左下角

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification8

"

class

=

"

common_button margin_l_10

"

>

左侧中间

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotification9

"

class

=

"

common_button margin_l_10

"

>

正中间

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

$

(

"#newNotification1"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification1

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"topLeft"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification2"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification2

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"topCenter"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification3"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification3

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"topRight"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification4"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification4

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"rightCenter"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification5"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification5

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"bottomRight"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification6"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification6

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"bottomCenter"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification7"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification7

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"bottomLeft"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification8"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification8

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"leftCenter"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotification9"

)

.

click

(

function

(

event

)

{

window

.

CtpUiComNotification9

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条通知的内容文字，随意啊啦啦啦啦'

,

showClose

:

true

,

position

:

"centerCenter"

,

//topLeft/topCenter/topRight/rightCenter/bottomRight/bottomCenter/bottomLeft/leftCenter

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

</

script

>

主题样式

带有 icon，常用来显示「成功、警告、消息、错误」类的系统消息

成功

警告

消息

错误

$("#newNotificationType1").click(function(event) {
window.newNotificationType1 = CtpUiComNotificationWarp({
title:'提示框4',
message:'我是一条success的提示的内容文字',
showClose:true,
type:"success",//success/warning/info/error
// iconClass:"sy-internationalization-resources",//success/warning/info/error
position:"topRight",//topRight/topLeft/bottomRight/bottomLeft
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotificationType2").click(function(event) {
window.newNotificationType2 = CtpUiComNotificationWarp({
title:'提示框4',
message:'我是一条warning的提示的内容文字',
showClose:true,
type:"warning",//success/warning/info/error
position:"topRight",//topRight/topLeft/bottomRight/bottomLeft
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotificationType3").click(function(event) {
window.newNotificationType3 = CtpUiComNotificationWarp({
title:'提示框4',
message:'我是一条info的提示的内容文字',
showClose:true,
type:"info",//success/warning/info/error
position:"topRight",//topRight/topLeft/bottomRight/bottomLeft
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

$("#newNotificationType4").click(function(event) {
window.newNotificationType4 = CtpUiComNotificationWarp({
title:'提示框4',
message:'我是一条error的提示的内容文字',
showClose:true,
type:"error",//success/warning/info/error
position:"topRight",//topRight/topLeft/bottomRight/bottomLeft
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotificationType1

"

class

=

"

common_button

"

>

成功

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotificationType2

"

class

=

"

common_button margin_l_10

"

>

警告

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotificationType3

"

class

=

"

common_button margin_l_10

"

>

消息

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotificationType4

"

class

=

"

common_button margin_l_10

"

>

错误

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

$

(

"#newNotificationType1"

)

.

click

(

function

(

event

)

{

window

.

newNotificationType1

=

CtpUiComNotificationWarp

(

{

title

:

'提示框4'

,

message

:

'我是一条success的提示的内容文字'

,

showClose

:

true

,

type

:

"success"

,

//success/warning/info/error

// iconClass:"sy-internationalization-resources",//success/warning/info/error

position

:

"topRight"

,

//topRight/topLeft/bottomRight/bottomLeft

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotificationType2"

)

.

click

(

function

(

event

)

{

window

.

newNotificationType2

=

CtpUiComNotificationWarp

(

{

title

:

'提示框4'

,

message

:

'我是一条warning的提示的内容文字'

,

showClose

:

true

,

type

:

"warning"

,

//success/warning/info/error

position

:

"topRight"

,

//topRight/topLeft/bottomRight/bottomLeft

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotificationType3"

)

.

click

(

function

(

event

)

{

window

.

newNotificationType3

=

CtpUiComNotificationWarp

(

{

title

:

'提示框4'

,

message

:

'我是一条info的提示的内容文字'

,

showClose

:

true

,

type

:

"info"

,

//success/warning/info/error

position

:

"topRight"

,

//topRight/topLeft/bottomRight/bottomLeft

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

$

(

"#newNotificationType4"

)

.

click

(

function

(

event

)

{

window

.

newNotificationType4

=

CtpUiComNotificationWarp

(

{

title

:

'提示框4'

,

message

:

'我是一条error的提示的内容文字'

,

showClose

:

true

,

type

:

"error"

,

//success/warning/info/error

position

:

"topRight"

,

//topRight/topLeft/bottomRight/bottomLeft

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

</

script

>

自动关闭

可以设置自动关闭的时间(毫秒)，duration设置为0的话代表不关闭，亦可以不传。

自动关闭

$("#newNotificationAutoClose").click(function(event) {
window.newNotificationAutoClose = CtpUiComNotificationWarp({
title:'提示框',
message:'我是一条提示的内容文字',
showClose:false,
type:"success",//success/warning/info/error
position:"topRight",//topRight/topLeft/bottomRight/bottomLeft
duration:4000,
onClose:function(){
console.log("这是onClose callback的通知消息");
},
onClick:function(){

}
});
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotificationAutoClose

"

class

=

"

common_button

"

>

自动关闭

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

$

(

"#newNotificationAutoClose"

)

.

click

(

function

(

event

)

{

window

.

newNotificationAutoClose

=

CtpUiComNotificationWarp

(

{

title

:

'提示框'

,

message

:

'我是一条提示的内容文字'

,

showClose

:

false

,

type

:

"success"

,

//success/warning/info/error

position

:

"topRight"

,

//topRight/topLeft/bottomRight/bottomLeft

duration

:

4000

,

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的通知消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

</

script

>

隐藏关闭按钮

可以不显示关闭按钮

隐藏关闭按钮

$("#newNotificationHideClose").click(function(event) {
window.newNotificationHideClose = CtpUiComNotificationWarp({
title:'提示框4',
message:'我是一条success的提示的内容文字',
showClose:false,
type:"success",//success/warning/info/error
// iconClass:"sy-internationalization-resources",//success/warning/info/error
position:"topRight",//topRight/topLeft/bottomRight/bottomLeft
onClose:function(){
console.log("这是onClose callback的提示消息");
},
onClick:function(){

}
});
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

newNotificationHideClose

"

class

=

"

common_button

"

>

隐藏关闭按钮

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

$

(

"#newNotificationHideClose"

)

.

click

(

function

(

event

)

{

window

.

newNotificationHideClose

=

CtpUiComNotificationWarp

(

{

title

:

'提示框4'

,

message

:

'我是一条success的提示的内容文字'

,

showClose

:

false

,

type

:

"success"

,

//success/warning/info/error

// iconClass:"sy-internationalization-resources",//success/warning/info/error

position

:

"topRight"

,

//topRight/topLeft/bottomRight/bottomLeft

onClose

:

function

(

)

{

console

.

log

(

"这是onClose callback的提示消息"

)

;

}

,

onClick

:

function

(

)

{

}

)

;

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

title

标题

string

—

message

说明文字

string

—

type

主题样式

string

success/warning/info/error

—

iconClass

自定义图标的类名,未传入的话将根据type决定

string

—

duration

显示时间, 毫秒。设为 0 则不会自动关闭

number

—

position

自定义弹出位置

string

topLeft / topCenter / topRight / rightCenter / bottomRight / bottomCenter / bottomLeft / leftCenter

topRight

showClose

是否显示关闭按钮

boolean

—

true

onClose

关闭时的回调函数

function

—

onClick

点击通知时的回调函数

function

—

方法列表

方法

说明

参数

close

关闭当前Notification

-

closeGroup

关闭一组Notification

position，具体的值请参照参数列表中的position

closeAll

关闭所有Notification

-

## 66. Card 卡片组件

> 原始路径：`/components4.0/other/card.html`  
> 相对路径：`components4.0/other/card.md`  
> 页面 key：`v-3d930b23`  
> JS Chunk：`93.d40ad62b.js`

Card 卡片组件

普通卡片带头部

new CtpUiCardContainer(document.getElementById("card"),{
showHeader:true
});

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

card

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiCardContainer

(

document

.

getElementById

(

"card"

)

,

{

showHeader

:

true

}

)

;

</

script

>

定制头部和正文卡片

new CtpUiCardContainer(document.getElementById("card1"),{
showHeader:true,
headerHtml: '<span>回忆绵绵</span> ' +
'<a href="javascript:forward()" class="common_button common_button_emphasize" style="float:right;margin-top:10px;">' +
'开启新篇章' +
'</a>',
bodyHtml: '<div id="test" style="margin-top:20px;"></div>' +
'<p>人的一生</p>' +
'<p>相识、相知</p>' +
'<p>再到相恋</p>' +
'<p>最后却不能相守</p>' +
'<p>热闹只是一时之欢</p>' +
'<p>孤独才是人生常态</p>',
callbackFuc:function(){
new CtpUiSliderBlock(document.getElementById("test"),{});
},
headerStyle:'background-color:#e1e1e1;',
shadow:'hover'
});
function forward(){
alert("有遗憾才是人生，还是要坚守本心，珍惜当下，向前看不一定成功，但也不会失败")
}

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

card1

"

>

</

div

>

</

div

>

</

div

>

<

script

>

new

CtpUiCardContainer

(

document

.

getElementById

(

"card1"

)

,

{

showHeader

:

true

,

headerHtml

:

'<span>回忆绵绵</span> '

+

'<a href="javascript:forward()" class="common_button common_button_emphasize" style="float:right;margin-top:10px;">'

+

'开启新篇章'

+

'</a>'

,

bodyHtml

:

'<div id="test" style="margin-top:20px;"></div>'

+

'<p>人的一生</p>'

+

'<p>相识、相知</p>'

+

'<p>再到相恋</p>'

+

'<p>最后却不能相守</p>'

+

'<p>热闹只是一时之欢</p>'

+

'<p>孤独才是人生常态</p>'

,

callbackFuc

:

function

(

)

{

new

CtpUiSliderBlock

(

document

.

getElementById

(

"test"

)

,

{

}

)

;

}

,

headerStyle

:

'background-color:#e1e1e1;'

,

shadow

:

'hover'

}

)

;

function

forward

(

)

{

alert

(

"有遗憾才是人生，还是要坚守本心，珍惜当下，向前看不一定成功，但也不会失败"

)

}

</

script

>

参数列表

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

-

options

width

宽度(带单位)

String

300px

height

高度(带单位)

String

300px

id

String

showHeader

是否显示头部

Boolean

false

headerHtml

头部自定义内容

String

headerStyle

头部自定义样式

String

bodyHtml

正文自定义内容

String

bodyStyle

正文自定义样式

String

shadow

阴影显示时机 always / hover / never

String

always

showHeader

是否显示头部

Boolean

false

showBorder

是否显示边框

Boolean

true

callbackFuc

上传成功的回调 自带文件信息

Function

方法列表

方法名

说明

参数

destory

销毁控件

## 67. Collapse 折叠面板

> 原始路径：`/components4.0/other/collapse.html`  
> 相对路径：`components4.0/other/collapse.md`  
> 页面 key：`v-1f40a429`  
> JS Chunk：`41.40872d50.js`

Collapse 折叠面板

通过折叠面板收纳内容区域

采用对象方式渲染

基础用法

可同时展开多个面板，面板之间不影响

简洁样式

//基础用法
//简洁样式
var testData1 = {
style: "simple",
accordion: false,
active: 0,
items: [{
title: "A8+协同管理软件",
content: "<div style='color:#efae38'>适用于集团、中大型组织的协同办公产品</div>"
},{
title: "A6+协同管理软件",
content: "适用于中小型组织的协同办公产品"
},{
title: "数据交换引擎",
content: "适用于异构系统间数据交换的管理平台"
},{
title: "信息交换中心",
content: "实现跨组织信息化协作的办公平台"
}]
}
var test1 = new CtpUiCollapse("#demo1", testData1);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo1

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//基础用法

//简洁样式

var

testData1

=

{

style

:

"simple"

,

accordion

:

false

,

active

:

0

,

items

:

[

{

title

:

"A8+协同管理软件"

,

content

:

"<div style='color:#efae38'>适用于集团、中大型组织的协同办公产品</div>"

}

,

{

title

:

"A6+协同管理软件"

,

content

:

"适用于中小型组织的协同办公产品"

}

,

{

title

:

"数据交换引擎"

,

content

:

"适用于异构系统间数据交换的管理平台"

}

,

{

title

:

"信息交换中心"

,

content

:

"实现跨组织信息化协作的办公平台"

}

]

}

var

test1

=

new

CtpUiCollapse

(

"#demo1"

,

testData1

)

;

</

script

>

卡片样式

//基础用法
//卡片样式
var testData2 = {
style: "card",
accordion: false,
active: 0,
items: [{
title: "简单",
content: "目标清晰 行动敏捷 平等透明 大道至简"
},{
title: "友爱",
content: "敬天爱人 换位思考 利他思维 上善若水"
},{
title: "务实",
content: "脚踏实地 拒绝浮夸 每天进步一点点 让问题到我为止"
},{
title: "创新",
content: "自以为非 鼓励试错 持续学习 跨界融合"
}]
}
var test2 = new CtpUiCollapse("#demo2", testData2);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo2

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//基础用法

//卡片样式

var

testData2

=

{

style

:

"card"

,

accordion

:

false

,

active

:

0

,

items

:

[

{

title

:

"简单"

,

content

:

"目标清晰 行动敏捷 平等透明 大道至简"

}

,

{

title

:

"友爱"

,

content

:

"敬天爱人 换位思考 利他思维 上善若水"

}

,

{

title

:

"务实"

,

content

:

"脚踏实地 拒绝浮夸 每天进步一点点 让问题到我为止"

}

,

{

title

:

"创新"

,

content

:

"自以为非 鼓励试错 持续学习 跨界融合"

}

]

}

var

test2

=

new

CtpUiCollapse

(

"#demo2"

,

testData2

)

;

</

script

>

手风琴效果

每次只能展开一个面板

简洁样式

//手风琴效果
//简洁样式
var testData3 = {
style: "simple",
accordion: true,
active: 0,
items: [{
title: "A8+协同管理软件",
content: "适用于集团、中大型组织的协同办公产品"
},{
title: "A6+协同管理软件",
content: "适用于中小型组织的协同办公产品"
},{
title: "数据交换引擎",
content: "适用于异构系统间数据交换的管理平台"
},{
title: "信息交换中心",
content: "实现跨组织信息化协作的办公平台"
}]
}
var test3 = new CtpUiCollapse("#demo3", testData3);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo3

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//手风琴效果

//简洁样式

var

testData3

=

{

style

:

"simple"

,

accordion

:

true

,

active

:

0

,

items

:

[

{

title

:

"A8+协同管理软件"

,

content

:

"适用于集团、中大型组织的协同办公产品"

}

,

{

title

:

"A6+协同管理软件"

,

content

:

"适用于中小型组织的协同办公产品"

}

,

{

title

:

"数据交换引擎"

,

content

:

"适用于异构系统间数据交换的管理平台"

}

,

{

title

:

"信息交换中心"

,

content

:

"实现跨组织信息化协作的办公平台"

}

]

}

var

test3

=

new

CtpUiCollapse

(

"#demo3"

,

testData3

)

;

</

script

>

卡片样式

//手风琴效果
//卡片样式
var testData4 = {
style: "card",
accordion: true,
active: 0,
items: [{
title: "简单",
content: "目标清晰 行动敏捷 平等透明 大道至简"
},{
title: "友爱",
content: "敬天爱人 换位思考 利他思维 上善若水"
},{
title: "务实",
content: "脚踏实地 拒绝浮夸 每天进步一点点 让问题到我为止"
},{
title: "创新",
content: "自以为非 鼓励试错 持续学习 跨界融合"
}]
}
var test4 = new CtpUiCollapse("#demo4", testData4);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

demo4

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//手风琴效果

//卡片样式

var

testData4

=

{

style

:

"card"

,

accordion

:

true

,

active

:

0

,

items

:

[

{

title

:

"简单"

,

content

:

"目标清晰 行动敏捷 平等透明 大道至简"

}

,

{

title

:

"友爱"

,

content

:

"敬天爱人 换位思考 利他思维 上善若水"

}

,

{

title

:

"务实"

,

content

:

"脚踏实地 拒绝浮夸 每天进步一点点 让问题到我为止"

}

,

{

title

:

"创新"

,

content

:

"自以为非 鼓励试错 持续学习 跨界融合"

}

]

}

var

test4

=

new

CtpUiCollapse

(

"#demo4"

,

testData4

)

;

</

script

>

采用comp方式渲染

基础用法

可同时展开多个面板，面板之间不影响

简洁样式

歌曲歌词

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

歌曲鉴赏

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

歌曲MV

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

社会影响

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiCollapse

"

comp

=

"

type:'CtpUiCollapse',options:{style:'simple',accordion:false,active:0}

"

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲歌词

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

</

p

>

<

p

>

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

</

p

>

<

p

>

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

</

p

>

<

p

>

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

</

p

>

<

p

>

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

</

p

>

<

p

>

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲鉴赏

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

</

p

>

<

p

>

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

</

p

>

<

p

>

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲MV

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

社会影响

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

</

p

>

</

div

>

</

div

>

</

div

>

</

div

>

</

div

>

卡片样式

歌曲歌词

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

歌曲鉴赏

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

歌曲MV

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

社会影响

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiCollapse

"

comp

=

"

type:'CtpUiCollapse',options:{style:'card',accordion:false,active:0}

"

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲歌词

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

</

p

>

<

p

>

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

</

p

>

<

p

>

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

</

p

>

<

p

>

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

</

p

>

<

p

>

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

</

p

>

<

p

>

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲鉴赏

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

</

p

>

<

p

>

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

</

p

>

<

p

>

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲MV

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

社会影响

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

</

p

>

</

div

>

</

div

>

</

div

>

</

div

>

</

div

>

手风琴效果

每次只能展开一个面板

简洁样式

歌曲歌词

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

歌曲鉴赏

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

歌曲MV

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

社会影响

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiCollapse

"

comp

=

"

type:'CtpUiCollapse',options:{style:'simple',accordion:true,active:0}

"

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲歌词

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

</

p

>

<

p

>

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

</

p

>

<

p

>

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

</

p

>

<

p

>

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

</

p

>

<

p

>

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

</

p

>

<

p

>

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲鉴赏

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

</

p

>

<

p

>

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

</

p

>

<

p

>

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲MV

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

社会影响

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

</

p

>

</

div

>

</

div

>

</

div

>

</

div

>

</

div

>

卡片样式

歌曲歌词

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

歌曲鉴赏

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

歌曲MV

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

社会影响

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

comp ctpUiCollapse

"

comp

=

"

type:'CtpUiCollapse',options:{style:'card',accordion:true,active:0}

"

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲歌词

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

我和我的祖国，一刻也不能分割，无论我走到哪里，都流出一首赞歌

</

p

>

<

p

>

我歌唱每一座高山，我歌唱每一条河，袅袅炊烟 小小村落，路上一道辙

</

p

>

<

p

>

我最亲爱的祖国，我永远紧依着你的心窝，你用你那母亲的脉搏，和我诉说

</

p

>

<

p

>

我的祖国和我，像海和浪花一朵，浪是那海的赤子，海是那浪的依托

</

p

>

<

p

>

每当大海在微笑，我就是笑的旋涡，我分担着海的忧愁，分享海的欢乐

</

p

>

<

p

>

我最亲爱的祖国，你是大海永不干涸，永远给我碧浪清波，心中的歌

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲鉴赏

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

《我和我的祖国》作品采用了抒情和激情相结合的笔调，将优美动人的旋律与朴实真挚的歌词巧妙结合，表达了人们对伟大祖国的衷心依恋和真诚歌颂。

</

p

>

<

p

>

该曲歌词以第一人称的手法诉说了“我和祖国”息息相连、一刻也不能分离的心情，作者将“我”和“祖国”比喻为孩子和母亲，又将“祖国”和“我”比喻为大海和浪花，这两个具象而生动的比喻，准确又动情，表达了个人和祖国之间，亘古不变的情感。秦咏诚在力求获得准确、生动的音乐形象的同时，十分懂得生活中的语言节奏与音乐中旋律节奏结合的规律，在使听众听得清、听得懂的基础上，保持了应有的线条美和律动美，从而创造了楚楚动人的音乐形象和丝丝入扣的情感表达。

</

p

>

<

p

>

《我和我的祖国》生动形象地表现了每个人和生他养他的祖国的血肉联系，在词曲结合上“恰到好处”，是一首具有永久魅力、深受人们喜爱的抒情歌曲。

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

歌曲MV

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2018年12月26日，中央广播电视总台制作的《我和我的祖国》主题MV发布，MV中不见华丽的艺术舞台，不见专业的歌唱演员，但一个个真实的现实生活场景。镜头前的这些面孔，来自于中国的四面八方、各行各业。他们是人民解放军仪仗队、消防官兵、中国国家女子排球队、港珠澳大桥岛遂工程建设者、路桥水电站建设者、塞罕坝机械林场职工、中国南极考察队、量子科学潘建伟团队、航天科技大军的代表、走在扶贫路上的基层干部

</

p

>

</

div

>

</

div

>

<

div

class

=

"

collapsItem

"

>

<

div

class

=

"

collapsTitle

"

>

社会影响

</

div

>

<

div

class

=

"

collapsContent

"

>

<

p

>

2019年2月3日至2月10日，中央电视台新闻频道推出“快闪系列活动——新春唱响《我和我的祖国》”系列节目，同时每天在央视《新闻联播》播出。该曲先后在北京首都国际机场、深圳北站、三沙、厦门鼓浪屿、成都宽窄巷、武汉黄鹤楼、广东乳源新时代文明实践中心、长沙橘子洲头唱响，单期节目平均全网总阅读量达五、六亿 [9] 。随后，《我和我的祖国》快闪活动在全国各地唱响

</

p

>

</

div

>

</

div

>

</

div

>

</

div

>

</

div

>

参数列表：

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

options

style

简单样式/卡片样式 （选填）：

"simple"/"card"

String

"simple"

accordion

是否开启手风琴效果（选填）

boolean

false

active

处于展开状态的面板的序号，从0开始（选填）

number / array

说明：当开启手风琴效果时，仅支持number

-

position

箭头图标的位置（选填）:

"left"/"right"

string

简洁样式时："right"

卡片样式时："left"

items(数组类型，由多个Object组成，每个Object包含title和content)

title

当前面板的标题（必填）

string

-

content

当前面板的内容（必填）

string

-

方法列表

方法

说明

参数

destory

销毁元素

-

## 68. Divider 分割线

> 原始路径：`/components4.0/other/divider.html`  
> 相对路径：`components4.0/other/divider.md`  
> 页面 key：`v-144856d3`  
> JS Chunk：`94.8ebfe22b.js`

Divider 分割线

区隔内容的分割线。

对不同章节的文本段落进行分割。

对行内文字/链接进行分割，例如表格的操作列。

基础用法

对不同章节的文本段落进行分割。

我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说。

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

p

>

我和我的祖国一刻也不能分割，无论我走到哪里都流出一首赞歌，我歌唱每一座高山我歌唱每一条河，袅袅炊烟小小村落路上一道辙，你用你那母亲的脉搏和我诉说。

</

p

>

<

div

class

=

"

ctpUiDivider

"

>

</

div

>

<

p

>

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

</

p

>

</

div

>

</

div

>

设置文案

可以在分割线上自定义文案内容。

左侧

我和我的祖国

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiDivider

"

>

<

div

class

=

"

dividerText left

"

>

我和我的祖国

</

div

>

</

div

>

<

p

>

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

</

p

>

</

div

>

</

div

>

右侧

我和我的祖国

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiDivider

"

>

<

div

class

=

"

dividerText right

"

>

我和我的祖国

</

div

>

</

div

>

<

p

>

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

</

p

>

</

div

>

</

div

>

中间

(不支持IE6、7、8)

我和我的祖国

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

ctpUiDivider

"

>

<

div

class

=

"

dividerText center

"

>

我和我的祖国

</

div

>

</

div

>

<

p

>

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

</

p

>

</

div

>

</

div

>

包裹住的分组

我和我的祖国

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

<

div

class

=

"

clearfix

"

>

<

div

class

=

"

content

"

>

<

fieldset

class

=

"

ctpUiDivider

"

>

<

legend

>

我和我的祖国

</

legend

>

<

p

>

我的祖国和我像海和浪花一朵，浪是海的赤子海是那浪的依托，每当大海在微笑我就是笑的旋涡，我分担着海的忧愁分享海的欢乐，永远给我碧浪清波心中的歌。

</

p

>

</

fieldset

>

</

div

>

</

div

>

## 69. Nestable 可拖拽树形结构

> 原始路径：`/components4.0/other/nestable.html`  
> 相对路径：`components4.0/other/nestable.md`  
> 页面 key：`v-2a506342`  
> JS Chunk：`42.32bd9e05.js`

Nestable 可拖拽树形结构

常用于拖拽排序、层级调整等功能

基础用法

var testData1 = {
group: 1,
items: [{
id: 1,
label: "Item 1"
},
{
id: 2,
label: "Item 2",
children:[{
id: 3,
label: "Item 3"
},
{
id: 4,
label: "Item 4"
},
{
id: 5,
label: "Item 5",
children:[{
id: 6,
label: "Item 6"
},
{
id: 7,
label: "Item 7",
children: [{
id: 8,
label: "Item 8"
}]
}]
},
{
id: 9,
label: "Item 9"
},
{
id: 10,
label: "Item 10"
}]
},
{
id: 11,
label: "Item 11"
},
{
id: 12,
label: "Item 12"
}],
dragEndFun: function() {
$("#jsonDiv1").text(window.JSON.stringify(test1.serialize())); //我是拖拽完成后的回调事件
}
};

var test1 = new CtpUiNestable($("#nestable-demo1"), testData1);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

nestable-demo1

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData1

=

{

group

:

1

,

items

:

[

{

id

:

1

,

label

:

"Item 1"

}

,

{

id

:

2

,

label

:

"Item 2"

,

children

:

[

{

id

:

3

,

label

:

"Item 3"

}

,

{

id

:

4

,

label

:

"Item 4"

}

,

{

id

:

5

,

label

:

"Item 5"

,

children

:

[

{

id

:

6

,

label

:

"Item 6"

}

,

{

id

:

7

,

label

:

"Item 7"

,

children

:

[

{

id

:

8

,

label

:

"Item 8"

}

]

}

]

}

,

{

id

:

9

,

label

:

"Item 9"

}

,

{

id

:

10

,

label

:

"Item 10"

}

]

}

,

{

id

:

11

,

label

:

"Item 11"

}

,

{

id

:

12

,

label

:

"Item 12"

}

]

,

dragEndFun

:

function

(

)

{

$

(

"#jsonDiv1"

)

.

text

(

window

.

JSON

.

stringify

(

test1

.

serialize

(

)

;

//我是拖拽完成后的回调事件

}

;

var

test1

=

new

CtpUiNestable

(

$

(

"#nestable-demo1"

)

,

testData1

)

;

</

script

>

结果：

请拖动后看效果

不允许跨层级拖动

var testData2 = {
group: 2,
crossLev: false, //不允许跨层级拖动
items: [{
id: 1,
label: "Item 1"
},
{
id: 2,
label: "Item 2",
children:[{
id: 3,
label: "Item 3"
},
{
id: 4,
label: "Item 4"
},
{
id: 5,
label: "Item 5"
}]
},
{
id: 6,
label: "Item 6",
children:[{
id: 7,
label: "Item 7"
},
{
id: 8,
label: "Item 8"
},
{
id: 9,
label: "Item 9"
}]
},
{
id: 10,
label: "Item 10",
children:[{
id: 11,
label: "Item 11"
},
{
id: 12,
label: "Item 12"
}]
}],
dragEndFun: function() {
$("#jsonDiv2").text(window.JSON.stringify(test2.serialize())); //我是拖拽完成后的回调事件
}
};

var test2 = new CtpUiNestable($("#nestable-demo2"), testData2);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

nestable-demo2

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData2

=

{

group

:

2

,

crossLev

:

false

,

//不允许跨层级拖动

items

:

[

{

id

:

1

,

label

:

"Item 1"

}

,

{

id

:

2

,

label

:

"Item 2"

,

children

:

[

{

id

:

3

,

label

:

"Item 3"

}

,

{

id

:

4

,

label

:

"Item 4"

}

,

{

id

:

5

,

label

:

"Item 5"

}

]

}

,

{

id

:

6

,

label

:

"Item 6"

,

children

:

[

{

id

:

7

,

label

:

"Item 7"

}

,

{

id

:

8

,

label

:

"Item 8"

}

,

{

id

:

9

,

label

:

"Item 9"

}

]

}

,

{

id

:

10

,

label

:

"Item 10"

,

children

:

[

{

id

:

11

,

label

:

"Item 11"

}

,

{

id

:

12

,

label

:

"Item 12"

}

]

}

]

,

dragEndFun

:

function

(

)

{

$

(

"#jsonDiv2"

)

.

text

(

window

.

JSON

.

stringify

(

test2

.

serialize

(

)

;

//我是拖拽完成后的回调事件

}

;

var

test2

=

new

CtpUiNestable

(

$

(

"#nestable-demo2"

)

,

testData2

)

;

</

script

>

结果：

请拖动后看效果

多个Nestable之间拖动

我是左侧的div

我是右侧的div

var testData3 = {
group: 3,
items: [{
id: 1,
label: "Item 1"
},
{
id: 2,
label: "Item 2",
children:[{
id: 3,
label: "Item 3"
},
{
id: 4,
label: "Item 4"
},
{
id: 5,
label: "Item 5"
}]
},
{
id: 6,
label: "Item 6",
children:[{
id: 7,
label: "Item 7"
},
{
id: 8,
label: "Item 8"
},
{
id: 9,
label: "Item 9"
}]
},
{
id: 10,
label: "Item 10",
children:[{
id: 11,
label: "Item 11"
},
{
id: 12,
label: "Item 12"
}]
}],
dragEndFun: function() {
$("#jsonDiv3").text(window.JSON.stringify(test3.serialize())); //我是拖拽完成后的回调事件
$("#jsonDiv4").text(window.JSON.stringify(test4.serialize())); //我是拖拽完成后的回调事件
}
};
var testData4 = JSON.parse(JSON.stringify(testData3)); //深拷贝一份拿来用，偷个懒

var test3 = new CtpUiNestable($("#nestable-demo3"), testData3);
var test4 = new CtpUiNestable($("#nestable-demo4"), testData4);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

nestable-demo3

"

>

我是左侧的div

</

div

>

<

div

id

=

"

nestable-demo4

"

>

我是右侧的div

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData3

=

{

group

:

3

,

items

:

[

{

id

:

1

,

label

:

"Item 1"

}

,

{

id

:

2

,

label

:

"Item 2"

,

children

:

[

{

id

:

3

,

label

:

"Item 3"

}

,

{

id

:

4

,

label

:

"Item 4"

}

,

{

id

:

5

,

label

:

"Item 5"

}

]

}

,

{

id

:

6

,

label

:

"Item 6"

,

children

:

[

{

id

:

7

,

label

:

"Item 7"

}

,

{

id

:

8

,

label

:

"Item 8"

}

,

{

id

:

9

,

label

:

"Item 9"

}

]

}

,

{

id

:

10

,

label

:

"Item 10"

,

children

:

[

{

id

:

11

,

label

:

"Item 11"

}

,

{

id

:

12

,

label

:

"Item 12"

}

]

}

]

,

dragEndFun

:

function

(

)

{

$

(

"#jsonDiv3"

)

.

text

(

window

.

JSON

.

stringify

(

test3

.

serialize

(

)

;

//我是拖拽完成后的回调事件

$

(

"#jsonDiv4"

)

.

text

(

window

.

JSON

.

stringify

(

test4

.

serialize

(

)

;

//我是拖拽完成后的回调事件

}

;

var

testData4

=

JSON

.

parse

(

JSON

.

stringify

(

testData3

)

;

//深拷贝一份拿来用，偷个懒

var

test3

=

new

CtpUiNestable

(

$

(

"#nestable-demo3"

)

,

testData3

)

;

var

test4

=

new

CtpUiNestable

(

$

(

"#nestable-demo4"

)

,

testData4

)

;

</

script

>

左侧的结果：

请拖动后看效果

右侧的结果：

请拖动后看效果

查看状态，允许给item绑定点击事件，但不允许拖动，可编辑item的内容，通过点击item上的“拖动”按钮切换至可拖动状态（适合展示数据，并一键切换至拖动状态）

var testData5 = {
group: 5,
view: true,
edit: true,
crossLev: false,
items: [{
id: 1,
label: "Item 1",
children: [{
id: 2,
label: "Item 2",
clickFun: function() {
$.infor("我是绑定的点击事件，想干啥就干啥，尽情嗨！（2）");
},
deleteFun: function() {
$.infor("我是点击了“删除”按钮触发的回调事件）");
},
editOkFun: function() {
$.infor("我是完成编辑后触发的回调事件");
}
},{
id: 3,
label: "Item 3",
clickFun: function() {
$.infor("我是绑定的点击事件，想干啥就干啥，尽情嗨！（3）");
},
deleteFun: function() {
$.infor("我是点击了“删除”按钮触发的回调事件）");
},
editOkFun: function() {
$.infor("我是完成编辑后触发的回调事件");
}
}],
}],
dragEndFun: function() { //我们是拖拽完成后的回调事件
$("#jsonDiv5").text(window.JSON.stringify(test5.serialize()));
$.infor("我是拖拽后的Fun事件");
},
view2editFun: function() { //我们是从查看状态切换至拖动状态后，点击‘确定’按钮后的回调函数事件
$("#jsonDiv5").text(window.JSON.stringify(test5.serialize()));
$.infor("我是从查看状态切换至拖动状态后，点击‘确定’按钮后的回调函数。");
}
};

var test5 = new CtpUiNestable($("#nestable-demo5"), testData5);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

nestable-demo5

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData5

=

{

group

:

5

,

view

:

true

,

edit

:

true

,

crossLev

:

false

,

items

:

[

{

id

:

1

,

label

:

"Item 1"

,

children

:

[

{

id

:

2

,

label

:

"Item 2"

,

clickFun

:

function

(

)

{

$

.

infor

(

"我是绑定的点击事件，想干啥就干啥，尽情嗨！（2）"

)

;

}

,

deleteFun

:

function

(

)

{

$

.

infor

(

"我是点击了“删除”按钮触发的回调事件）"

)

;

}

,

editOkFun

:

function

(

)

{

$

.

infor

(

"我是完成编辑后触发的回调事件"

)

;

}

,

{

id

:

3

,

label

:

"Item 3"

,

clickFun

:

function

(

)

{

$

.

infor

(

"我是绑定的点击事件，想干啥就干啥，尽情嗨！（3）"

)

;

}

,

deleteFun

:

function

(

)

{

$

.

infor

(

"我是点击了“删除”按钮触发的回调事件）"

)

;

}

,

editOkFun

:

function

(

)

{

$

.

infor

(

"我是完成编辑后触发的回调事件"

)

;

}

]

,

}

]

,

dragEndFun

:

function

(

)

{

//我们是拖拽完成后的回调事件

$

(

"#jsonDiv5"

)

.

text

(

window

.

JSON

.

stringify

(

test5

.

serialize

(

)

;

$

.

infor

(

"我是拖拽后的Fun事件"

)

;

}

,

view2editFun

:

function

(

)

{

//我们是从查看状态切换至拖动状态后，点击‘确定’按钮后的回调函数事件

$

(

"#jsonDiv5"

)

.

text

(

window

.

JSON

.

stringify

(

test5

.

serialize

(

)

;

$

.

infor

(

"我是从查看状态切换至拖动状态后，点击‘确定’按钮后的回调函数。"

)

;

}

;

var

test5

=

new

CtpUiNestable

(

$

(

"#nestable-demo5"

)

,

testData5

)

;

</

script

>

结果：

请拖动后看效果

纯查看状态，不允许编辑和拖动，允许给item绑定点击事件（适合展示数据）

var testData6 = {
group: 5,
view: true,
edit: false,
items: [{
id: 1,
label: "Item 1",
children: [{
id: 2,
label: "Item 2",
clickFun: function() {
$.infor("我是绑定的点击事件，想干啥就干啥，尽情嗨！（2）");
}
},{
id: 3,
label: "Item 3",
clickFun: function() {
$.infor("我是绑定的点击事件，想干啥就干啥，尽情嗨！（3）");
}
}],
}]
};

var test6 = new CtpUiNestable($("#nestable-demo6"), testData6);

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

id

=

"

nestable-demo6

"

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

testData6

=

{

group

:

5

,

view

:

true

,

edit

:

false

,

items

:

[

{

id

:

1

,

label

:

"Item 1"

,

children

:

[

{

id

:

2

,

label

:

"Item 2"

,

clickFun

:

function

(

)

{

$

.

infor

(

"我是绑定的点击事件，想干啥就干啥，尽情嗨！（2）"

)

;

}

,

{

id

:

3

,

label

:

"Item 3"

,

clickFun

:

function

(

)

{

$

.

infor

(

"我是绑定的点击事件，想干啥就干啥，尽情嗨！（3）"

)

;

}

]

,

}

]

}

;

var

test6

=

new

CtpUiNestable

(

$

(

"#nestable-demo6"

)

,

testData6

)

;

</

script

>

参数列表：

参数

说明

类型

默认值

elObj

被渲染的元素DOM（必填）

可传入一个 DOM 对象或字符串；

若传入字符串，则会将其作为参数传入 document.querySelector以获取到对应 DOM 节点

options

group

用于区分CtpNestable分组的编号

说明：本参数主要针对页面中有多个CtpNestable时

如果多个CtpNestable的group值相同，则它们的内容可以互拖

如果不需多CtpNestable内容互拖，请配置不同的group值

（选填）

crossLev

是否允许跨层级拖动（选填）

boolean

true

maxDepth

允许拖动的最大层级（选填）

number

5

view

是否处于查看状态，此状态下不可拖动，可通过"拖动"按钮一键切换至拖动态（选填）

boolean

false

edit

是否可编辑，仅view为true时有效（选填）

boolean

false

dragEndFun

拖动后的回调函数（选填）

纯查看状态下无效

function

items

(数组类型，由多个Object组成，

每个Object包含id、label等)

id

items的id（必填）

string/boolean/number

label

items的标签/名称（必填）

string

editOkFun

编辑完item后点击“确定”按钮后的回调事件（选填）

function

deleteFun

点击了item上的“删除”按钮后的回调事件（选填）

function

方法列表

方法

说明

参数

serialize

返回序列化的json数据

-

collapseAll

折叠所有子级

-

expandAll

展开所有子级

-

destory

销毁元素

-

## 70. Popover 弹出框

> 原始路径：`/components4.0/other/popover.html`  
> 相对路径：`components4.0/other/popover.md`  
> 页面 key：`v-6fb84f5a`  
> JS Chunk：`95.7bd47e7a.js`

Popover 弹出框

1、基础用法--标准内容，comp方式渲染

comp渲染，必须申明class为comp 然后在comp里面添加相应的参数配置。
如果是comp方式渲染的对象，通过 $("#input_obj").attrObj("_CtpUiPopover");方式来获取对象

hover 激活

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

hover 激活

</

span

>

</

button

>

</

div

>

hover 激活左上

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'leftTop',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

hover 激活左上

</

span

>

</

button

>

</

div

>

hover 激活右上

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'rightTop',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

hover 激活右上

</

span

>

</

button

>

</

div

>

hover 激活右下

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'bottomRight',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

hover 激活右下

</

span

>

</

button

>

</

div

>

hover 激活左下

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'bottomLeft',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

hover 激活左下

</

span

>

</

button

>

</

div

>

2、基础用法--自定义内容，comp方式渲染

自定义的显示内容的容器class需要设置成el-popover-div,里面的内容由大家自行编写

hover 激活

gridData: [{
date: '2016-05-02',
name: '王小虎',
address: '上海市普陀区金沙江路 1518 弄'
}

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',popoverId:'popover',placement:'right',width:200

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

"

>

<

span

>

hover 激活

</

span

>

</

button

>

<

div

class

=

"

el-popover-div

"

id

=

"

popover

"

style

=

"

padding

:

10px

;

"

>

gridData: [{
date: '2016-05-02',
name: '王小虎',
address: '上海市普陀区金沙江路 1518 弄'
}

</

div

>

</

div

>

3、基础用法--显示方向，comp方式渲染

right 激活

bottom 激活

left 激活

top 激活

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

go_content

"

>

<

div

class

=

"

row_record clearfix

"

style

=

"

font-size

:

13px

;

"

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'right',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

right 激活

</

span

>

</

button

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'bottom',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

bottom 激活

</

span

>

</

button

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'left',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

left 激活

</

span

>

</

button

>

<

button

type

=

"

button

"

class

=

"

comp el-button el-button--default el-popover__reference

"

comp

=

"

type:'CtpUiPopover',placement:'top',title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

;

margin-left

:

30px

;

"

>

<

span

>

top 激活

</

span

>

</

button

>

</

div

>

</

div

>

</

div

>

3、采用对象方式渲染

hover 激活

var inputObj3 = new CtpUiPopover($("#popoverBtn").get(0),{title:'标题',width:'200',content:'这是一段内容,这是一段内容,这是一段内容,这是一段内容'});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

go_content

"

>

<

button

type

=

"

button

"

id

=

"

popoverBtn

"

class

=

"

el-button el-button--default

"

style

=

"

padding

:

3px 20px

;

border-radius

:

4px

;

border

:

1px solid #dfdfdf

"

>

<

span

>

hover 激活

</

span

>

</

button

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

var

inputObj3

=

new

CtpUiPopover

(

$

(

"#popoverBtn"

)

.

get

(

0

)

,

{

title

:

'标题'

,

width

:

'200'

,

content

:

'这是一段内容,这是一段内容,这是一段内容,这是一段内容'

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

type

控件类型

string

CtpUiPopover

title

标题

string

自定义

content

提示内容

string

自定义

width

显示区域的宽度

number

80

height

如果传递了高度，则下拉区域的高度以用户定义的高度为准，不传的话，则最大高度为275px;

number

placement

显示位置

string

left/right/bottom/top

bottom

popoverId

自定义提示区域的内容的id

string

自定义

方法列表

方法名

说明

参数 1

参数 2

destory

销毁组件

## 71. Tooltip 文字提示

> 原始路径：`/components4.0/other/tooltip.html`  
> 相对路径：`components4.0/other/tooltip.md`  
> 页面 key：`v-05452c13`  
> JS Chunk：`43.043d35ea.js`

Tooltip 文字提示

代码示例

常用于展示鼠标 hover 时的提示信息

基础用法

在这里我们提供 12 种不同方向的展示方式，可以通过以下完整示例来理解，选择你要的效果。

上左

上边

上右

左上

左边

左下

右上

右边

右下

下左

下边

下右

//上边
new CtpUiTooltip($(".common_button")[0],{
placement:"topStart",
content:"1这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[1],{
placement:"topCenter",
content:"2这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[2],{
placement:"topEnd",
content:"3这是一段提示文字"
});

//左边
new CtpUiTooltip($(".common_button")[3],{
placement:"leftStart",
content:"4这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[4],{
placement:"leftCenter",
content:"5这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[5],{
placement:"leftEnd",
content:"6这是一段提示文字"
});

//右边
new CtpUiTooltip($(".common_button")[6],{
placement:"rightStart",
content:"7这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[7],{
placement:"rightCenter",
content:"8这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[8],{
placement:"rightEnd",
content:"9这是一段提示文字"
});

//下边
new CtpUiTooltip($(".common_button")[9],{
placement:"bottomStart",
content:"10这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[10],{
placement:"bottomCenter",
content:"11这是一段提示文字"
});

new CtpUiTooltip($(".common_button")[11],{
placement:"bottomEnd",
content:"12这是一段提示文字"
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

tooltip_demobox

"

>

<

div

class

=

"

top

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

上左

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

上边

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

上右

</

a

>

</

div

>

<

div

class

=

"

left

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

左上

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

左边

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

左下

</

a

>

</

div

>

<

div

class

=

"

right

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

右上

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

右边

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

右下

</

a

>

</

div

>

<

div

class

=

"

bottom

"

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

下左

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

下边

</

a

>

<

a

href

=

"

javascript:void(0)

"

class

=

"

common_button

"

>

下右

</

a

>

</

div

>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

//上边

new

CtpUiTooltip

(

$

(

".common_button"

)

[

0

]

,

{

placement

:

"topStart"

,

content

:

"1这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

1

]

,

{

placement

:

"topCenter"

,

content

:

"2这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

2

]

,

{

placement

:

"topEnd"

,

content

:

"3这是一段提示文字"

}

)

;

//左边

new

CtpUiTooltip

(

$

(

".common_button"

)

[

3

]

,

{

placement

:

"leftStart"

,

content

:

"4这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

4

]

,

{

placement

:

"leftCenter"

,

content

:

"5这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

5

]

,

{

placement

:

"leftEnd"

,

content

:

"6这是一段提示文字"

}

)

;

//右边

new

CtpUiTooltip

(

$

(

".common_button"

)

[

6

]

,

{

placement

:

"rightStart"

,

content

:

"7这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

7

]

,

{

placement

:

"rightCenter"

,

content

:

"8这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

8

]

,

{

placement

:

"rightEnd"

,

content

:

"9这是一段提示文字"

}

)

;

//下边

new

CtpUiTooltip

(

$

(

".common_button"

)

[

9

]

,

{

placement

:

"bottomStart"

,

content

:

"10这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

10

]

,

{

placement

:

"bottomCenter"

,

content

:

"11这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

".common_button"

)

[

11

]

,

{

placement

:

"bottomEnd"

,

content

:

"12这是一段提示文字"

}

)

;

</

script

>

主题

Tooltip 组件提供了两个不同的主题：dark和light。

深色主题

浅色主题

new CtpUiTooltip($("#effect1")[0],{
effect:"dark",
placement:"bottomCenter",
content:"这是一段提示文字"
});

new CtpUiTooltip($("#effect2")[0],{
effect:"light",
placement:"bottomCenter",
content:"这是一段提示文字"
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

effect1

"

class

=

"

common_button margin_l_10

"

>

深色主题

</

a

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

effect2

"

class

=

"

common_button margin_l_10

"

>

浅色主题

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

new

CtpUiTooltip

(

$

(

"#effect1"

)

[

0

]

,

{

effect

:

"dark"

,

placement

:

"bottomCenter"

,

content

:

"这是一段提示文字"

}

)

;

new

CtpUiTooltip

(

$

(

"#effect2"

)

[

0

]

,

{

effect

:

"light"

,

placement

:

"bottomCenter"

,

content

:

"这是一段提示文字"

}

)

;

</

script

>

更多内容

展示多行文本或者是设置文本内容的格式

多行内容

new CtpUiTooltip($("#multipleRows")[0],{
effect:"dark",
placement:"topCenter",
isMultipleRows:true,
content:"第一行文字文字<br>第二行文字"
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

a

href

=

"

javascript:void(0)

"

id

=

"

multipleRows

"

class

=

"

common_button margin_l_10

"

>

多行内容

</

a

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

new

CtpUiTooltip

(

$

(

"#multipleRows"

)

[

0

]

,

{

effect

:

"dark"

,

placement

:

"topCenter"

,

isMultipleRows

:

true

,

content

:

"第一行文字文字<br>第二行文字"

}

)

;

</

script

>

渲染方式

1、通过comp方式渲染

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

common_txtbox_wrap comp

"

comp

=

"

type:'CtpUiTooltip',content:'只能输入数字哦！',placement:'rightCenter'

"

style

=

"

width

:

200px

;

"

>

<

input

type

=

"

text

"

placeholder

=

"

请输入电话号码

"

/>

</

div

>

</

div

>

</

div

>

2、通过对象渲染

new CtpUiTooltip($("#tagsObj_new")[0],{
placement:"rightCenter",
content:"文字文字文字文字"
});

<

div

class

=

"

row_record clearfix

"

>

<

div

class

=

"

content

"

>

<

div

class

=

"

common_txtbox_wrap

"

id

=

"

tagsObj_new

"

style

=

"

width

:

200px

;

"

>

<

input

type

=

"

text

"

placeholder

=

"

请输入电话号码

"

/>

</

div

>

</

div

>

</

div

>

<

script

type

=

"

text/javascript

"

>

new

CtpUiTooltip

(

$

(

"#tagsObj_new"

)

[

0

]

,

{

placement

:

"rightCenter"

,

content

:

"文字文字文字文字"

}

)

;

</

script

>

参数列表

参数

说明

类型

可选值

默认值

effect

默认提供的主题

string

dark/light

dark

content

显示的内容，过滤所有的html标签(

isMultipleRows为true的时候仅保留<br>

)

string

—

placement

Tooltip 的出现位置

string

topCenter/topStart/topEnd

bottomCenter/bottomStart/bottomEnd

leftCenter/leftStart/leftEnd

rightCenter/rightStart/rightEnd

topCenter

isMultipleRows

是否多行（

多行需自行传入<br>实现换行

）

Boolean

—

false

width

最大宽度，超过自动换行，否则到达窗口边缘再换行

number

-

'auto'

## 72. 9.0 发布修改记录

> 原始路径：`/changeLogs/v90.html`  
> 相对路径：`changeLogs/v90.md`  
> 页面 key：`v-1a28bab6`  
> JS Chunk：`48.33115c64.js`

## 9.0 发布修改记录
