# CMP移动平台文档 文档汇总

- 来源：https://open.seeyoncloud.com/cmpdev/
- 提取文档数：133
- 说明：该站点为 Vite/Vue 应用，正文 Markdown 通过运行时从 `iframePhone/md/fingerPost/{path}.md` 加载；本文件直接拉取这些 Markdown 源文件整理。

## 目录

1. [前言](#前言) — `preface`
2. [开发规范](#开发规范) — `standard`
3. [应用模块对照表](#应用模块对照表) — `appMap`
4. [CMP构建流程](#cmp构建流程) — `grunt`
5. [S3编译工具的使用](#s3编译工具的使用) — `S3release`
6. [CMP核心知识](#cmp核心知识) — `corePrinciple`
7. [各APP平台的userAgent](#各app平台的useragent) — `userAgent`
8. [重要更新](#重要更新) — `importantUpdate`
9. [输出打包](#输出打包) — `outputPackage`
10. [iOS端M3-WEB容器拦截问题](#ios端m3-web容器拦截问题) — `iosIntercept`
11. [CMP文件优化业务适配说明](#cmp文件优化业务适配说明) — `cmpMerge`
12. [原生导航设置](#原生导航设置) — `/component/native/nativeHeader`
13. [设备信息](#设备信息) — `/component/native/devices`
14. [电话短信](#电话短信) — `/component/native/tel`
15. [相机](#相机) — `/component/native/camera`
16. [邮件](#邮件) — `/component/native/mail`
17. [录音和播放录音](#录音和播放录音) — `/component/native/audio`
18. [二维码扫描](#二维码扫描) — `/component/native/barcode`
19. [网络状态](#网络状态) — `/component/native/network`
20. [打开第三方应用](#打开第三方应用) — `/component/native/openThridApp`
21. [webview操作](#webview操作) — `/component/native/webview`
22. [分享组件](#分享组件) — `/component/native/share`
23. [关联文档](#关联文档) — `/component/v5/accDoc`
24. [选人组件](#选人组件) — `/component/v5/selectOrg`
25. [选人组件](#选人组件) — `/component/v5/selectOrgV80`
26. [流程图](#流程图) — `/component/v5/treeView`
27. [表单签章](#表单签章) — `/component/v5/formSignature`
28. [V5类的附件上传下载套件](#v5类的附件上传下载套件) — `/component/v5/fileUpload`
29. [金格正文组件](#金格正文组件) — `/component/v5/content`
30. [button 按钮](#button-按钮) — `/component/module/button`
31. [actionSheet](#actionsheet) — `/component/module/actionSheet`
32. [Nav 页签](#nav-页签) — `/component/module/nav`
33. [navComp 页签](#navcomp-页签) — `/component/module/navComp`
34. [upload 上传套件](#upload-上传套件) — `/component/module/upload`
35. [voice 语音](#voice-语音) — `/component/module/voice`
36. [pagePlaceholder 骨架屏](#pageplaceholder-骨架屏) — `/component/module/pagePlaceholder`
37. [apishare 分享](#apishare-分享) — `/component/module/apishare`
38. [errorView 错误面板](#errorview-错误面板) — `/component/module/errorView`
39. [enum](#enum) — `/component/module/enum`
40. [appList 应用列表](#applist-应用列表) — `/component/module/appList`
41. [businessList 业务列表](#businesslist-业务列表) — `/component/module/businessList`
42. [bbsList 讨论列表](#bbslist-讨论列表) — `/component/module/bbsList`
43. [docList 文档列表](#doclist-文档列表) — `/component/module/docList`
44. [commentList 回复列表](#commentlist-回复列表) — `/component/module/commentList`
45. [memberList 人员列表](#memberlist-人员列表) — `/component/module/memberList`
46. [newsList 新闻列表](#newslist-新闻列表) — `/component/module/newsList`
47. [selectList 选择列表](#selectlist-选择列表) — `/component/module/selectList`
48. [selectionList 多选列表](#selectionlist-多选列表) — `/component/module/selectionList`
49. [showList](#showlist) — `/component/module/showList`
50. [functionList](#functionlist) — `/component/module/functionList`
51. [drawer抽屉组件](#drawer抽屉组件) — `/component/module/drawer`
52. [filterSearch 过滤搜索组件](#filtersearch-过滤搜索组件) — `/component/module/filterSearch`
53. [Button 按钮](#button-按钮) — `/component/ui/UIbutton`
54. [Badge 数字角标](#badge-数字角标) — `/component/ui/badge`
55. [Header布局](#header布局) — `/component/ui/header`
56. [Footer 底部导航栏](#footer-底部导航栏) — `/component/ui/footer`
57. [Checked 复选单选框](#checked-复选单选框) — `/component/ui/checked`
58. [Input 输入框](#input-输入框) — `/component/ui/input`
59. [Switch 开关](#switch-开关) — `/component/ui/switch`
60. [Progress 进度条](#progress-进度条) — `/component/ui/progress`
61. [Loading 加载状态](#loading-加载状态) — `/component/ui/loading`
62. [9Grid 9宫格](#9grid-9宫格) — `/component/ui/9grid`
63. [Nav 页签](#nav-页签) — `/component/ui/UInav`
64. [Drawer 全屏抽屉](#drawer-全屏抽屉) — `/component/ui/uidrawer`
65. [ListUi 列表UI](#listui-列表ui) — `/component/ui/listUi`
66. [Alert 弹出框](#alert-弹出框) — `/component/ui/alert`
67. [GroupSearch 组合搜索](#groupsearch-组合搜索) — `/component/ui/groupSearch`
68. [DateCalender日历组件](#datecalender日历组件) — `/component/ui/dateCalender`
69. [DatePicker 日期选择组件](#datepicker-日期选择组件) — `/component/ui/datePicker`
70. [Watermark 水印](#watermark-水印) — `/component/ui/watermark`
71. [ListView 滚动列表](#listview-滚动列表) — `/component/ui/listView`
72. [ScrollBox 正文滚动](#scrollbox-正文滚动) — `/component/ui/scrollBox`
73. [TableList table列表滚动](#tablelist-table列表滚动) — `/component/ui/tableList`
74. [Zoom  缩放组件](#zoom--缩放组件) — `/component/ui/zoom`
75. [Sortable 拖拽排序](#sortable-拖拽排序) — `/component/ui/sortable`
76. [LargePicture 正文大图查看](#largepicture-正文大图查看) — `/component/ui/largePicture`
77. [Calender 日历时间选择](#calender-日历时间选择) — `/component/ui/dtPickerCalender`
78. [slider 轮播图](#slider-轮播图) — `/component/ui/slider`
79. [H5调试准备](#h5调试准备) — `/inspect/inspect`
80. [熟悉调试面板](#熟悉调试面板) — `/inspect/inspect/inspect`
81. [手机开启调试模式](#手机开启调试模式) — `/inspect/inspect/phoneOpendebug`
82. [Edge浏览器inspect](#edge浏览器inspect) — `/inspect/inspect/edgeInspect`
83. [M3APP调试-安卓端](#m3app调试-安卓端) — `/inspect/m3debugAndroid`
84. [获取调试版本M3](#获取调试版本m3) — `/inspect/m3debugAndroid/debugm3`
85. [模拟器调试](#模拟器调试) — `/inspect/m3debugAndroid/simulatorDebug`
86. [真机调试](#真机调试) — `/inspect/m3debugAndroid/realDebug`
87. [M3日志抓取](#m3日志抓取) — `/inspect/m3debugAndroid/m3Log`
88. [M3APP调试-IOS端](#m3app调试-ios端) — `/inspect/m3debugIOS`
89. [模拟器调试](#模拟器调试) — `/inspect/m3debugIOS/m3debugIOS`
90. [M3APP调试-鸿蒙Next端](#m3app调试-鸿蒙next端) — `/inspect/m3debugharmony`
91. [真机调试(windows版)](#真机调试windows版) — `/inspect/m3debugharmony/m3debugharmony`
92. [微协同调试-PC端](#微协同调试-pc端) — `/inspect/wechatPC`
93. [微协同模拟调试](#微协同模拟调试) — `/inspect/wechatPC/simulationDebug`
94. [微协同调试-安卓端](#微协同调试-安卓端) — `/inspect/wechatIntegration`
95. [微信](#微信) — `/inspect/wechatIntegration/wechat`
96. [企业微信](#企业微信) — `/inspect/wechatIntegration/weCom`
97. [钉钉/welink/飞书](#钉钉welink飞书) — `/inspect/wechatIntegration/dingding`
98. [微协同调试-IOS端](#微协同调试-ios端) — `/inspect/wechatIOS`
99. [模拟器调试](#模拟器调试) — `/inspect/wechatIOS/wechatIOSsimulator`
100. [数据请求抓包调试](#数据请求抓包调试) — `/inspect/request`
101. [PC端Fiddler抓包](#pc端fiddler抓包) — `/inspect/request/fiddler`
102. [Stream抓包IOS端](#stream抓包ios端) — `/inspect/request/stream`
103. [httpCanary抓包安卓端](#httpcanary抓包安卓端) — `/inspect/request/httpCanary`
104. [后台CTP.log日志](#后台ctplog日志) — `/inspect/request/ctplog`
105. [M3开启vconsole](#m3开启vconsole) — `/inspect/request/m3vconsole`
106. [微协同开启vconsole](#微协同开启vconsole) — `/inspect/wechatIntegration/wechatVconsole`
107. [M3集成第三方H5页面](#m3集成第三方h5页面) — `m3inH5`
108. [概述](#概述) — `/third/m3inH5/m3inH5`
109. [常见问题](#常见问题) — `/third/m3inH5/m3inH5Problem`
110. [OA9.0以上版本IOS集成问题](#oa90以上版本ios集成问题) — `/third/m3inH5/m3inH5Problem2`
111. [微协同集成到第三方APP](#微协同集成到第三方app) — `H5inApp`
112. [概述](#概述) — `/third/H5inApp/H5inApp`
113. [常见问题](#常见问题) — `/third/H5inApp/H5inAppProblem`
114. [微协同集成到第三方H5](#微协同集成到第三方h5) — `wechatInH5`
115. [概述](#概述) — `/third/wechatInH5/wechatInH5`
116. [常见问题](#常见问题) — `/third/wechatInH5/wechatInH5Problem`
117. [指南](#指南) — `/fingerpost`
118. [指南](#指南) — `fingerpost`
119. [组件](#组件) — `/component`
120. [基础类](#基础类) — `basic`
121. [布局](#布局) — `/component/basic/layout`
122. [字体](#字体) — `/component/basic/font`
123. [颜色主题](#颜色主题) — `/component/basic/color`
124. [Icon图标](#icon图标) — `/component/basic/icon`
125. [附件图标](#附件图标) — `/component/basic/fileIcon`
126. [UI组件](#ui组件) — `ui`
127. [模块组件](#模块组件) — `module`
128. [业务组件](#业务组件) — `v5`
129. [原生组件](#原生组件) — `native`
130. [API](#api) — `/api`
131. [第三方集成](#第三方集成) — `/third`
132. [调试](#调试) — `/inspect`
133. [资源](#资源) — `/sources`

---

## 1. 前言

> 路由：`preface`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/preface.md

## 一、简述

本文主要带大家简单的了解 CMP 平台的整体架构，以方便了解整个 CMP 平台 H5 应用的基本原理与规范。

## 二、CMP 基础架构

**CMP 架构是基于移动原生与 H5 混合模式开发。整体总共分为4个部分：**

![1659495699175.png](./iframePhone/assets/img/CMP.png)

### 核心层

核心层主要是对 Android、iOS、Harmony(鸿蒙) 系统的基础能力进行规范统一的抽象封装如：网络请求、本地文件读写等。也是移动端运行环境的基础。M3 APP 的原生应用部分的开发也是基于此层开发。
特殊扩展知识：
1、Harmony OS 就是 Android OS 魔改的系统吗，或者说 Harmony OS 就是基于 Android OS 开发的系统，比如：小米的 MIUI，华为的 EMUI 系统？
答案肯定不是，Harmony OS 完全与 Android OS 没任何关系，是华为完全独立研发的一套全新的系统。
2、为什么能兼容 Android OS 的应用？
其实主要原因在于 Harmony 与 Android 都是基于 Linux 系统内核进行构建的上层应用系统。而上层应用程序最终也是允许在 Linux 系统之上的。比如：PC Linux 系统 RedHat OS、Cent OS 以及国产化的系统如：麒麟、统信UOS、深度等，都是基于 Linux 内核研发的上层应用系统。

### 移动平台 CMP 层
主要通过原生程序结合 H5 混合方式开发对上层提供统一的基础 API，并且在移动平台层将第三方集成和跨平台的能力进行了封装，并且提供了统一的标准与开发规范。保证了上层“应用层”开发过程中以及后续程序运行中可以无需过多的关注平台与环境问题，而更多的关注业务的问题。
Cordova 是一套开源移动开发框架，隶属于 Apache 开源项目，通过它，开发者可以用标准WEB技术：HTML5、CSS3、JavaScript，来开发跨平台 App。
Cordova 也是我们 CMP 平台 H5 与原生程序间相互调用通讯的中间件。
Cordova 目前支持的平台有：Android、Blackberry 10、iOS、OS X、Ubuntu、Windows、WP8。

### 应用层
基于 CMP 平台提供的标准规范与 API 开发出的各场景可独立运行的应用模块。通过 CMP 的规范完成开发，并使用 S3 工具编译构建后生成 M3 APP 可运行的 ZIP 与微协同可运行的 HTML 静态资源。因此能做到一次编写构建，多端运行。

### 客户端
此层分两部分。
**第一部分**：M3 APP（V5-A8\A6\G6 移动办公/移动政务/政务督办APP），由致远自己研发的可运行与 Android、iOS、Harmony 系统的独立 APP。M3 中所运行的应用全部基于 H5 完成开发。并通过 S3 工具编译生成可运行与 M3 中的 ZIP 包。
**第二部分**：微协同。通过 H5 方式提供可集成到第三方系统的致远移动办公系统，目前标准已支持集成到微信、企业微信、钉钉、飞书和 Welink APP 中。
**特别说明**：微协同第三方集成，标准产品有提供集成到第三方 APP 中的能力，但是实际集成中可能还是会存在部分少量的开发或适配，目前还是主要通过客开方式主导完成。
* _CMP 作为移动基础平台提供移动开发所需组件，业务应用按照 CMP 平台规范，开发出前端 HTML、JS 等文件，再通过 S3 工具编译后，输出生成可以运行的M3 ZIP 包和微协同静态 HTML 资源；_
* _M3 ZIP 包运行在 M3 客户端上，微协同静态资源运行在微信、企业微信、钉钉、飞书、Welink 等第三方办公 APP 平台_
* _总结：一次编码，一次编译，多端运行_

## 三、移动 CMP 平台简介
CMP 全称 Collaboration Mobile Platform 协同移动平台(也有理解为 Core Mobile Plaform 核心移动平台)。CMP 作为移动基础平台，提供移动开发与运行的基础规范以及基础组件。
CMP 也是跨平台前端框架。基于 CMP 平台开发的协同应用，均可以运行在 M3 APP、微信微协同、企业微信微协同、钉钉、飞书、Welink或第三方 APP 中。同时 CMP 平台也提供了第三方 H5 应用集成到 M3 APP 中的能力。按照 CMP 提供的 H5 标准集成规范，集成的 H5 APP 均可以正常运行在 M3 APP 中。
同时，CMP 平台也提供了很多基础 API，如：拍照、文件、定位、相册等本地原生功能 API，缓存、路由、类加载、AJAX等前端基础能力，并且还提供了丰富的 UI 组件。

## 四、应用开发简介
H5 应用开发请参阅：【移动端H5应用基础开发】
Android / iOS 原生应用开发请参阅：【M3原生应用开发】
第三方 H5 集成请参阅：【H5应用集成】

## 2. 开发规范

> 路由：`standard`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/standard.md

## 一、开发规范

> 开发人员需遵照开发规范执行

#### 1、基本原则
* 由于jquery在移动端的开发存在性能问题，页面不允许导入jquery库，如果已经习惯了jquery开发的，可以导入zepto库进行代替；
* 样式需进行兼容处理；
* UE交互保持一致性、UI风格保持一致性、代码风格保持一致性；
* 谨慎引入第三方前端库，引入时需要充分考虑性能、稳定性、可维护性和技能要求。

#### 2、页面开发规范
* 页面使用UTF-8编码
* 页面首屏数据量大小在1M以内，多余的部分需要使用异步导入的方式；
* 禁止ajax同步请求；
* 尽可能减少 div 嵌套；
* 样式代码不能使用CSS表达式；
* dom选择尽量使用ID选择；
* 所有的标签名必须小写；
* 所有的标签属性名必须小写；
* z-index的最高使用层级为49；
* 不要随意的使用position定位；
* link标签写在head标签内；
* script标签写在body标签结尾处；
* 国际化资源以中文简体资源为首选资源；
* 业务逻辑入口需放在cmp.ready回调里，如：cmp.ready(function(){业务逻辑})：

```html
http://cmp/v1.0.0/js/cordova/__CMPSHELL_PLATFORM__/cordova.js
http://cmp/v1.0.0/js/cordova/cordova-plugins.js
```
* 必须导入cmp平台的js，导入文件规则：

```html
//======== 代码运行在M3  app上
 <link href="http://cmp/v/css/cmp.css" rel="stylesheet" type="text/css" />
 <script  src="http://cmp/v/js/cmp-i18n.js"></script>
 <script  src="http://cmp/v/js/cmp.js"></script>
 //=======代码运行在微信、钉钉等或者第三方app以url的方式接入oa的H5页面时
 <link href="/seeyon/m3/cmp/css/cmp.css" rel="stylesheet" type="text/css" />
 <script  src="/seeyon/m3/cmp/js/cmp-i18n.js"></script>
 <script  src="/seeyon/m3/cmp/js/cmp.js"></script>
```

* 页面采用自适应屏幕宽度设置：

```html
<meta name="viewport" content="width=device-width, initial-scale=1,maximum-scale=1,user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
```

#### 3、代码结构
* html文件放到html文件夹；
* css文件放到css文件夹；
* js文件放到js文件夹；
* 图片文件放到img文件夹；
* 国际化资源文件放到i18n文件夹。

#### 4、命名
* camel命名风格

## 二、项目结构规范
```javascript
project
      |----html                                  <!--html文件夹-->
            -- index.html
      |----js                                    <!--js文件夹-->
           -- index.js
      |----css                                   <!--css文件夹-->
           -- index.css
      |----img                                   <!--图片文件夹-->
      |----i18n                                  <!--国际化文件夹-->
           -- project_en.js
           -- project_zh_CN.js
           -- project_zh_TW.js
      |----s3scriptjspdata                       <!--S3编译文件夹-->
           -- project_m3_commandata.data
           -- project_wechat_commandata.data
           -- project_dingding_commandata.data
      -- manifest.json                            <!--模块配置文件-->
      -- newModule_m_api.s3js                     <!--模块消息穿透、门户待办穿透api设置文件-->
```

## 三、cmp.ready里面应该做什么
首先要知道在运行cmp.ready时内部做了什么东西：
```javascript
function CMPReady() {
        var _this = this;
        _ready.setDeviceClass();
        this.CMPISReady = $.platform.CMPShell ? false : true;
        this.handles = [];
        //M3中的cordova ready
        try {
            !window.parent.CMPREADYMARK && _ready.deviceReadyListener();
        } catch (error) {
            console.log(error);
        }
        //文档ready
        _ready.documentReadyTask();
        //第三方sdk
        _ready.loadJSSDKTask();
        //调试JS任务
        _ready.loadDebugJsTask();
        //除debugJS任务外，其余任务完成后的操作
        pool.free(function() {
            //CMPREADYMARK这个变量业务层在用，没搞懂为啥要开放这个
            window.CMPREADYMARK = _this.CMPISReady = true;
            _ready.setTheme();
            _ready.releaseHandles(_this);
        });
    }
```
可以看见里面做了加载设备类名、加载第三方SDK、加载主题、等一系列操作，所以只能在cmp.ready里面才能做很多操作，比如注册返回事件cmp.backbutton、比如ready里面获取body元素上的类名等，其实归根结底就是类似jquery的ready，在完成一系列加载之后，才能在ready里面使用api或者一些方法等等。

## 四、js、css在cmp平台下导入的顺序规范以及微协同和M3上导入的差异性

> M3平台文件路径

CSS导入参考：
```html
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no" />
    <meta name="format-detection" content="telephone=no,email=no" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="apple-touch-fullscreen" content="yes" />
    <meta http-equiv="Content-Security-Policy" />
    <meta name="author" content="Clyne" />
    <title></title>
    <meta name = "cmp-screen-orientation" content = "all">
    <!--cmp样式-->
    <link rel="stylesheet" href="http://cmp/v/css/cmp.css" />
    <link rel="stylesheet" href="http://cmp/v/css/cmp-sliders.css" />
    <!--基础样式-->
    <link rel="stylesheet" href="http://commons.m3.cmp/v/css/base.css" />
    <!--图标样式-->
    <link rel="stylesheet" href="http://commons.m3.cmp/v/fonts/iconfont.css" />
    <!--业务样式-->
    <link rel="stylesheet"  href="http://application.m3.cmp/v/css/app_application.css" />
</head>
```

JS导入参考:

```html
<!-- 基础模块 -->
<script src="http://cmp/v/js/cmp-i18n.js"></script>
<script src="http://cmp/v/js/cordova/__CMPSHELL_PLATFORM__/cordova.js"></script>
<script src="http://cmp/v/js/cordova/cordova-plugins.js"></script>
<script src="http://cmp/v/js/cmp.js"></script>
<!-- cmp组件(按需引入) -->
<script src="http://cmp/v/js/cmp-asyncLoad.js"></script>
<script src="http://cmp/v/js/cmp-webviewListener.js"></script>
<!-- 针对M3应用的公共文件(V5应用可忽略) -->
<script src="http://commons.m3.cmp/v/js/m3-path.s3js"></script>
<script src="http://commons.m3.cmp/v/lib/seajs-2.2.1.js"></script>
<script src="http://commons.m3.cmp/v/config.js"></script>
<!-- 自己业务的模块入口文件 -->
<script async src="http://application.m3.cmp/v/js/sea-app-workbench.js"></script>
</body><!--！！！js的导入必须到body页签的结尾处！！！-->
```

> 微协同平台路径

CSS导入参考：
```html
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no" />
    <meta name="format-detection" content="telephone=no,email=no" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="apple-touch-fullscreen" content="yes" />
    <meta http-equiv="Content-Security-Policy" />
    <meta name="author" content="Clyne" />
    <title></title>
    <meta name = "cmp-screen-orientation" content = "all">
    <!--cmp样式-->
    <link rel="stylesheet" href="/seeyon/m3/cmp/css/cmp.css" />
    <link rel="stylesheet" href="/seeyon/m3/cmp/css/cmp-sliders.css" />
    <!--业务样式-->
    <link rel="stylesheet"  href="/seeyon/m3/apps/v5/bulletin/css/bulletinIndex.css" />
</head>
```
JS导入参考:

```html
<!-- 基础模块 -->
<script src="/seeyon/m3/cmp/js/cmp-i18n.js"></script>
<script src="/seeyon/m3/cmp/js/cmp.js"></script>
<!-- cmp组件(按需引入) -->
<script src="/seeyon/m3/cmp/js/cmp-asyncLoad.js"></script>
<script src="/seeyon/m3/cmp/js/cmp-webviewListener.js"></script>
<!-- 自己业务的模块入口文件 -->
<script async src="/seeyon/m3/apps/v5/bulletin/js/bulletinIndex.js"></script>
</body><!--！！！js的导入必须到body页签的结尾处！！！-->
```

**注：导入的顺序需要严格按照规范执行，不然会有报错和找不到方法或者变量的情况。**

## 五、国际化资源使用properties开发以及在页面中导入的规范

#### 1、文件命名:应用模块名+下横线+通用语言标识

![language](./iframePhone/assets/img/standard/language.png)

#### 2、国际化资源，必须以fI18nData JS对象进行扩展
```js
<script>
if(typeof fI18nData == "undefined"){
     fI18nData  = {};
}
fI18nData["mobileWork.label.back"] = "返回";
fI18nData["mobileWork.label.submit"] = "提交";
</script>
```
#### 3、国际化资源调用使用规则
```html
<html>
    <div><i18n key="mobileWork.label.back"></i18n></div> <!-- 使用国际化标签，key为国际化字符串 -->
</html>
<script>
    var backStr = cmp.i18n("mobileWork.label.back"); //返回国际化字符串"返回";
</script>
```
#### 4、国际化资源版本差异
|        版本        |                     国际化代码开发规范                     |
|---|---|
| 7.1以下的版本（不包含7.1） |             开发源码按照第1点的规范直接用js文件写国际化资源             |
| 7.1及以上的版本（包含7.1） | 1、源码使用properties文件进行开发  
2、需使用S3工具编辑后生成如第1点中的js文件 |

## 六、ajax调用规范
```javascript
cmp.ajax({
             url:cmp.seeyonbasepath + "/rest/.....",  //seeyon的rest接口，cmp.seeyonbasepath是seeyon服务器路径，兼容M3和微协同
             type:"GET",
             headers:{   //请求headers，异步seeyon的rest接口设置如下headers字段
                   'Accept' : 'application/json; charset=utf-8',
                   'Accept-Language' : cmp.language,
                   'Content-Type': 'application/json; charset=utf-8',
                   'token' : cmp.token,//微协同请求必带上token
                   'option.n_a_s' : '1'
             },
             success:function(result){
                   //请求成功的业务逻辑
             },
             error:function(error){
                 if(cmp.errorHandle(error) == false){  //请求错误时，先使用cmp的错误处理组件，如果cmp的错误处理组件为false，说明cmp组件处理不了这个错误，需要业务自己处理（cmp处理的错误包括被迫下线、网络断开、session失效、更新密码等）
                     cmp.notification.alert("请求数据失败")
                 }
             }
       });
```

## 七、应用包之间穿透API设计规范

#### 1、文件命名：应用模块名+下划线+api.s3js（文件命名必须和manifest.json中的entry下的jsapi字段保持一致）

![s3jsname](./iframePhone/assets/img/standard/s3jsname.png)

#### 2、穿透函数命名规范（openApp对应manifest.json的entry里的openAppMethod的值）

![manifest](./iframePhone/assets/img/standard/manifest.png)

#### 3、穿透函数开发例子(已在初始化应用包里自带)

```javascript
var mobileWorkApi = (function(){  //api定义的名字和manifest中的openAppMethod字段相对应
    var mobileWorkApi = function(){
        this.basePath = "${data:dependencies.mobilework}";//编辑本模块的路径
    }
    mobileWorkApi.prototype.openApp = function(type,backUrl,option,obj) {
        if(!option) {
            return false;
        }
        var params = {};
        var penetrateUrl = "";//数据穿透页面地址
        if(type=="message") {   //如果数据来自消息
            params.from = "message";
        }
        if("todo" == type){  //如果数据来自待办
            params.from = "todo";
        }
        var params.dataId = option.id;
        var params.xxId = option.xxId;
        if(option.dataType == "chooseCustomer"){//如果数据类型是打开选择客户页面
             penetrateUrl = this.basePath + "/html/chooseCustomer.html";
        }else if(option.dataType == "register"){//如果数据是打开外勤签到记录页面
             penetrateUrl = this.basePath + "/html/register.html";
        }
        cmp.href.next(penetrateUrl,params);
    }
    return new mobileWorkApi();
```

## 八、UE样式规范

```html
<!-- 以W3C标准的页面布局为例 -->
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no" />
    <meta name="format-detection" content="telephone=no,email=no" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="apple-touch-fullscreen" content="yes" />
    <meta http-equiv="Content-Security-Policy" />
    <meta name="author" content="Clyne" />
    <title></title>
    <meta name = "cmp-screen-orientation" content = "all">
    <!--cmp样式-->
    <link rel="stylesheet" href="http://cmp/v/css/cmp.css" />
    <link rel="stylesheet" href="http://cmp/v/css/cmp-sliders.css" />
    <!--基础样式-->
    <link rel="stylesheet" href="http://commons.m3.cmp/v/css/base.css" />
    <!--图标样式-->
    <link rel="stylesheet" href="http://commons.m3.cmp/v/fonts/iconfont.css" />
    <!--业务样式-->
    <link rel="stylesheet"  href="http://application.m3.cmp/v/css/app_application.css" />
    <style>
       .red{color:red;}
    </style>
</head>
<body>
<header class="cmp-bar cmp-bar-nav cmp-flex-header">
    <div class="cmp-header-left">
        <span class="cmp-icon see-icon-v5-common-arrow-back"></span>
    </div>
    <div class="cmp-title">
        <span>header布局</span>
    </div>
    <div class="cmp-header-right cmp-flex2">
        <span class="cmp-icon see-icon-add-round"></span>
        <span class="cmp-icon see-icon-add-round"></span>
    </div>
</header>
<div class="cmp-content">
  //主容器
</div>
<footer class="cmp-bar cmp-bar-footer">底部按钮</footer>
<script src="/seeyon/m3/cmp/js/cmp-i18n.js"></script>
<script src="/seeyon/m3/cmp/js/cmp.js"></script>
<!-- cmp组件(按需引入) -->
<script src="/seeyon/m3/cmp/js/cmp-asyncLoad.js"></script>
<script src="/seeyon/m3/cmp/js/cmp-webviewListener.js"></script>
<!-- 自己业务的模块入口文件 -->
<script async src="/seeyon/m3/apps/v5/bulletin/js/bulletinIndex.js"></script>
</body>
</html>
```

## 3. 应用模块对照表

> 路由：`appMap`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/appMap.md

## 一、M3/微协同模块对照表

**获取应用包地址**(V9.0版本及以上)可以使用代码:
```js
cmp.apps[模块][包名].path; //无需判断M3还是微协同，使用CMP平台定义全局方法获取包地址。
```
注：<code>该方法只使用标准产品内开发的应用包。特殊表单模块或者部分特殊应用包/第三方应用包无法获取</code>
```js
示例：
cmp.apps.m3.my.path //输出my包路径
或者
cmp.apps.v5.collaboration.path //输出collaboration包路径
```

### 1、微协同全部首页入口(可用PC访问这些页面进行模拟移动端调试)

|   应用名称    |                路径                |  源码路径    |
|   ---------   | ---------------------------------- | --------------- |
|   全部应用   |     /seeyon/H5/wechat/html/allApps.html     |  【apps-weixin】工程下\src\main\webapp\H5\wechat\html\allApps.html |
|     待办     |     /seeyon/m3/apps/m3/todo/layout/todo-list.html     | 【mplus-front】工程下\src\apps\m3\todo\layout\todo-list.html |
|   个人中心   |     /seeyon/H5/wechat/html/userCenter.html     |【apps-weixin】工程下\src\main\webapp\H5\wechat\html\userCenter.html |
|   信息门户   |   /seeyon/m3/apps/v5/portal/html/portalIndex.html | 【mplus-front】工程下\src\apps\v5\portal\html\portalIndex.html |

### 2、M3默认全部首页入口

|   应用名称    |                路径                |  源码路径    |
|   ---------   | ---------------------------------- | --------------- |
|   消息   |  \seeyon\m3files\m3\message.zip\layout\message-all.html |  【mplus-front】工程下\src\apps\m3\message\layout\message-all.html |
|     待办     | \seeyon\m3files\m3\todo.zip\layout\todo-list.html   | 【mplus-front】工程下\src\apps\m3\todo\layout\todo-list.html |
|   工作门户   | \seeyon\m3files\v5\65.zip\layout\portalIndex.html   | 【mplus-front】工程下\src\apps\v5\portal\html\portalIndex.html |
|   通讯录   |  \seeyon\m3files\m3\search.zip\layout\address-index.html | 【mplus-front】工程下\src\apps\m3\search\layout\address-index.html |
|   我   |  \seeyon\m3files\m3\my.zip\layout\my-index.html | 【mplus-front】工程下\src\apps\m3\my\layout\my-index.html |

### 3、V5应用对照表

| appId |   包名   |  应用名称 |M3路径    |    微协同路径  | 微协同应用入口路径   |
| ----- | ----- |  ----- | ----- | ----- | -----  |
|   1   | 1.zip  |   协同   | \seeyon\m3files\v5\1.zip  |  \seeyon\m3\apps\v5\collaboration  |    {ip}/seeyon/m3/apps/v5/collaboration/html/colAffairs.html    |
|   2   | 2.zip  |   表单   | \seeyon\m3files\v5\2.zip  |      \seeyon\m3\apps\v5\form       |                                无                                |
|   3   | 3.zip  |  文档中心  | \seeyon\m3files\v5\3.zip  |       \seeyon\m3\apps\v5\doc       |          {ip}/seeyon/m3/apps/v5/doc/html/docIndex.html          |
|   4   | 4.zip  |   公文   | \seeyon\m3files\v5\4.zip  |      \seeyon\m3\apps\v5\edoc       |         {ip}/seeyon/m3/apps/v5/edoc/html/edocList.html          |
|   6   | 6.zip  |   会议   | \seeyon\m3files\v5\6.zip  |     \seeyon\m3\apps\v5\meeting     |  {ip}/seeyon/m3/apps/v5/meeting/html/meeting_list_pending.html  |
|   7   | 7.zip  |   公告   | \seeyon\m3files\v5\7.zip  |    \seeyon\m3\apps\v5\bulletin     |       {ip}/seeyon/m3/apps/v5/bulletin/html/bulIndex.html        |
|   8   | 8.zip  |   新闻   | \seeyon\m3files\v5\8.zip  |      \seeyon\m3\apps\v5\news       |         {ip}/seeyon/m3/apps/v5/news/html/newsIndex.html         |
|   9   | 9.zip  |   讨论   | \seeyon\m3files\v5\9.zip  |       \seeyon\m3\apps\v5\bbs       |          {ip}/seeyon/m3/apps/v5/bbs/html/bbsIndex.html          |
|  10   | 10.zip |   调查   | \seeyon\m3files\v5\10.zip |     \seeyon\m3\apps\v5\inquiry     |      {ip}/seeyon/m3/apps/v5/inquiry/html/inquiryIndex.html      |
|  11   | 11.zip |  时间安排  | \seeyon\m3files\v5\11.zip |    \seeyon\m3\apps\v5\calendar     |      {ip}/seeyon/m3/apps/v5/calendar/html/timeArrange.html      |
|  17   | 17.zip |  工资条   | \seeyon\m3files\v5\17.zip |       \seeyon\m3\apps\v5\hr        |          {ip}/seeyon/m3/apps/v5/hr/html/hrSalary.html           |
|  26   | 26.zip |  综合办公  | \seeyon\m3files\v5\26.zip |     \seeyon\m3\apps\v5\office      |                                无                                |
|  30   | 30.zip |  工作任务  | \seeyon\m3files\v5\30.zip |   \seeyon\m3\apps\v5\taskmanage    |     {ip}/seeyon/m3/apps/v5/taskmanager/html/task_index.html     |
|  36   | 36.zip |   签到   | \seeyon\m3files\v5\36.zip |   \seeyon\m3\apps\v5\attendance    |   {ip}/seeyon/m3/apps/v5/attendance/html/attendanceIndex.html   |
|  40   | 40.zip |  享空间   | \seeyon\m3files\v5\40.zip |      \seeyon\m3\apps\v5\show       |         {ip}/seeyon/m3/apps/v5/show/html/showIndex.html         |
|  42   | 42.zip |  行为绩效  | \seeyon\m3files\v5\42.zip |    \seeyon\m3\apps\v5\footprint    |    {ip}/seeyon/m3/apps/v5/footprint/html/footPrintIndex.html    |
|  43   | 43.zip | 业务生成器  | \seeyon\m3files\v5\43.zip |       \seeyon\m3\apps\v5\biz       |          {ip}/seeyon/m3/apps/v5/biz/html/default.html           |
|  44   | 44.zip | v5应用通用 | \seeyon\m3files\v5\44.zip |     \seeyon\m3\apps\v5\commons     |                                无                                |
|  45   | 45.zip |  工作流   | \seeyon\m3files\v5\45.zip |    \seeyon\m3\apps\v5\workflow     |                                无                                |
|  47   | 47.zip | 无流程表单  | \seeyon\m3files\v5\47.zip |   \seeyon\m3\apps\v5\unflowform    |                                无                                |
|  48   | 48.zip |  查询统计  | \seeyon\m3files\v5\48.zip | \seeyon\m3\apps\v5\formqueryreport |     {ip}/seeyon/m3/apps/v5/formqueryreport/html/index.html      |
|  51   | 51.zip |  Dee   | \seeyon\m3files\v5\51.zip |       \seeyon\m3\apps\v5\dee       |                                无                                |
|  60   | 60.zip |  我的收藏  | \seeyon\m3files\v5\60.zip |  \seeyon\m3\apps\v5\mycollection   | {ip}/seeyon/m3/apps/v5/mycollection/html/mycollectionIndex.html |
|  61   | 61.zip |   致信   | \seeyon\m3files\v5\61.zip |       \seeyon\m3\apps\v5\uc        |           {ip}/seeyon/m3/apps/v5/uc/html/ucIndex.html           |
|  62   | 62.zip |  通讯录   | \seeyon\m3files\v5\62.zip |   \seeyon\m3\apps\v5\addressbook   |  {ip}/seeyon/m3/apps/v5/addressbook/html/addressbookIndex.html  |
|  63   | 63.zip |  报表分析  | \seeyon\m3files\v5\63.zip |  \seeyon\m3\apps\v5\seeyonreport   |       {ip}/seeyon/m3/apps/v5/seeyonreport/html/index.html       |
|  65   | 65.zip |   门户   | \seeyon\m3files\v5\65.zip |     \seeyon\m3\apps\v5\portal      |       {ip}/seeyon/m3/apps/v5/portal/html/portalIndex.html       |
|  66   | 66.zip |   流程表单   | \seeyon\m3files\v5\66.zip |     无      |       无

### 4、M3应用对照表

| appId |       包名        |   应用名称    |                M3路径                |           微协同路径   |
| ----- | --------------- | --------- | ---------------------------------- | -------------------------- 
|  49   |     cmp.zip     |   cmp平台   |     \seeyon\m3files\m3\cmp.zip     |       \seeyon\m3\cmp       |
|  52   | application.zip | 应用中心/门户应用 | \seeyon\m3files\m3\application.zip |   \seeyon\m3\application   |
|  53   |   commons.zip   |  commons  |   \seeyon\m3files\m3\commons.zip   |     \seeyon\m3\commons     |
|  55   |   message.zip   |   应用消息    |   \seeyon\m3files\m3\message.zip   |           无微协同版本           |
|  56   |     my.zip      |   个人信息    |     \seeyon\m3files\m3\my.zip      | \seeyon\m3\my(只有部分页面支持微协同) |
|  57   |   search.zip    |    通讯录    |   \seeyon\m3files\m3\search.zip    |     \seeyon\m3\search/layout/address-index.html      |
|  58   |    todo.zip     |    待办     |    \seeyon\m3files\m3\todo.zip     |      \seeyon\m3\todo\layout\todo-list.html       |


## 二、M3各版本新增应用

### 1、V7.0新增【全文检索】【报表中心】

| appId |       包名       | 应用名称 |               存放路径                |                    微协同应用入口路径                    |
| ----- | -------------- | ---- | --------------------------------- | ----------------------------------------------- |
|  59   | fullsearch.zip | 全文检索 | \seeyon\m3files\m3\fullsearch.zip | \seeyon\m3\v5\fullsearch\layout\all-search.html |
|  70   |  vreport.zip   | 报表中心 |  \seeyon\m3files\m3\vreport.zip   |      \seeyon\m3\v5\vreport\html\index.html      |

### 2、V7.0SP3新增【小致】

| appId |    包名     |   应用名称   |             M3路径             | 微协同应用入口路径 |
| ----- | --------- | -------- | ---------------------------- | --------- |
|  79   | xiaoz.zip | 小致(智能问答) | \seeyon\m3files\m3\xiaoz.zip |     无     |

### 3、 V7.1SP1新增【一键体检】

| appId |     包名      | 应用名称 |              M3路径              | 微协同应用入口路径 |
| ----- | ----------- | ---- | ------------------------------ | --------- |
|  90   | inspect.zip | 一键体检 | \seeyon\m3files\m3\inspect.zip |     无     |

### 4、 V8.0新增【文件管理】【领导行程】

| appId |        包名        | 应用名称 |                M3路径                 |                         微协同路径                          |
| ----- | ---------------- | ---- | ----------------------------------- | ------------------------------------------------------ |
|  93   |  filemanage.zip  | 文件管理 |  \seeyon\m3files\m3\filemanage.zip  |                           无                            |
|  94   | leaderagenda.zip | 领导行程 | \seeyon\m3files\m3\leaderagenda.zip | \seeyon\m3\v5\leaderagenda\html\leaderagendaIndex.html |


### 5、 V8.1SP1新增【智能票夹】【高级会议】【领导日程】

| appId |        包名        | 应用名称 |                M3路径                 |微协同路径|
| ----- | ---------------- | ---- | ----------------------------------- | ------------------------------------------------------ |
|  106   |  106.zip  | 智能票夹 |  \seeyon\m3files\v5\106.zip  |无|
|  105   |  105.zip  | 高级会议 |  \seeyon\m3files\v5\105.zip  |无|
|  111   |  111.zip  | 领导日程 |  \seeyon\m3files\v5\111.zip  |无|

## 三、应用包，包ID命名规则

在我们M3运行平台下，所有本地资源都是以应用包(压缩包)的形式存在，比如协同是一个1.zip压缩包，会议是一个6.zip压缩包，针对这个数字命名的压缩包，在我们开发平台有一个强制性的规则和规范，以下是命名规则：

- 标准应用包命名区间为：1 - 99 ，就是制作的标准应用包为99.zip等，目前已占用了一大部分，可以看上面的应用对照表。
- 集成应用包命名区间为：1000 - 2000 
- 文件夹包命名需要驼峰命名法，首字母小写

原因：

由于之前出现过几次H5应用包appid冲突的问题，M3现在对H5应用包的appId做了管控，新开发的应用包，凡是需要走运维构建的，都需要发 M3appid申请流程，由M3提供appid，否则不会构建。只影响标准H5应用包，cap与cip无影响。

![2131245.png](./iframePhone/assets/img/appId.jpg)

## 4. CMP构建流程

> 路由：`grunt`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/grunt.md

## CMP构建流程

构建流程说明图：![1659495699175.png](./iframePhone/assets/img/cmp-grunt.png)

### V9.0版本开始构建流程

无需解压模块依赖包node_modules，直接使用npm install安装依赖即可。
```js
cd cmp-front目录
然后执行：npm install

执行构建：npm run build

构建完成会生成release目录，该目录放入S3编译工具，进行M3或者微协同的编译打包。

```

## 5. S3编译工具的使用

> 路由：`S3release`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/S3release.md

## 一、工具的作用

移动端H5的代码原则上是一套源代码，通过S3工具编辑后，能生成多端运行的代码。本质就是通过此工具将html、s3js、css三种后缀文件中的类似 ${data:dependencies.cmp} 这种格式的静态资源路径进行一个替换，如：

![1.png](./iframePhone/assets/img/s3release/1.png)

**PS**：如果不通过此工具构建，相关的html、js、css是无法用程序运行的

## 二、支持的构建标签

| 序号  |                    标签                     |                                说明                                |
| --- | ----------------------------------------- | ---------------------------------------------------------------- |
|  1  |         ${data:dependencies.cmp}          |                        常见的标签，对应单个应用模块的路径                         |
|  2  |    <s3:import type="css"></s3:import>     |  对于一些有共性的页面元素，可以抽取成组件模板，编辑的时候会将此标签对应的模型进行替换，相当于PC端JSP页面的include  |
|  3  | <s3:data name='CollDatas.headerScript' /> | 同上，只是共性的模型更聚焦，比如此处就是协同模块的头部script标签的统一导入，因为在协同模块的每一个页面都会有这样的模板元素 |
|  4  |           ${data:buildversion}            |             对js、css等静态资源添加后缀，用于版本控制，更重要的是清除浏览器静态资源缓存             |

## 三、工具的获取

1、下载：点击此链接下载工具[S3编译工具下载](./iframePhone/assets/img/s3release/S3Script.zip)

2、安装：将文件解压到任何目录都可以使用

**PS**：有点不太友好的是此工具不支持苹果操作系统

## 四、工具的使用

### 1、认识工具的组成结构

![2.png](./iframePhone/assets/img/s3release/2.png)

【java】：该工具由java语言开发，相关的功能使用由jar在此文件夹中，开发者无需关注此文件夹
【publishcmd】：应用构建脚本集合，所有的H5应用微协同版本和M3应用zip包版本的脚本集合，根据配置信息启动工具构建不同的静态文件版本
【publishoutput】：构建完成后的可运行文件的输出目录,此目录构建出来的文件是可以直接运行的
【workspace】：项目源码的开发路径，此文件夹的路径，开发者最好按照此文件夹结构将开发项目源码导入进去，这样减少其他的学习成本
【文档】：此工具的一些说明性文档，开发者可以不用过多关注
【batchbuild.cmd】：批量构建脚本，通过配置可以将多个模块进行构建，可以同时构建出zip包和微协同模式的运行代码，一般用于某个开发者同时涉及多个应用模块的开发，**开发者关注此文件**
### 2、batchbuild 批量构建脚本

![3.png](./iframePhone/assets/img/s3release/3.png)

### 3、publishcmd 文件夹

**此文件夹已经将**62个标准应用的微信同模式和M3应用包模式的脚本进行了预置，后续如果开发者有新增模块，只需在对应的应用模块组里添加cmd文件即可，再在batchbuild中添加模块名称进行构建即可

## 五、规范
为减少工具学习成本，开发者最好按照文件夹结构来做工程源码文件夹结构和输出路径文件夹结构配置，这样只需按照规范来，就可以简简单单地完成源码开发、构建输出、代码调试查看的流程

## 6. CMP核心知识

> 路由：`corePrinciple`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/corePrinciple.md

#### 1、CMP路由机制

一般说到路由主要是微协同模式，M3是APP自带的多<code>webview</code>模式，路由为APP控制。

在微协同模式下，首次进入到OA微协同页面，会初始化一个本地缓存<code>CMPRouter</code>数据，是一个数组格式，首次进入页面会将当前页面push进去，并且存储,在每次跳转页面和返回页面的时候，都是统一改变该数据来实现路由。

而监听路由，是使用的浏览器标准事件<code>popstate</code>来监听浏览器路由变化，页面跳转时通过<code>pushState</code>来注入浏览器跳转状态，同时存储<code>CMPRouter</code>数据。当点击APP返回按钮，或手势返回时，正常情况下浏览器会触发<code>popstate</code>事件，然后走我们内部注册的返回逻辑，达到返回的效果。

但有些第三方APP集成了微协同后无法触发，大概率原因是APP壳的<code>webview</code>没有正常触发<code>popstate</code>事件导致，参考第三方集成里面的方式去解决。

为何要使用这种方式进行路由控制？

- 解决页面与页面之间参数问题。
- 解决当微协同集成到第三方应用，比如钉钉，企微等时，返回到首页时，再返回需要调用当前平台API的关闭方法，去关闭整个微协同页面。
- OA内统一管理，可以通过公共的方法，去实现返回几层页面等等。

示例代码：
```js
cmp.href.next(url); //CMPRouter执行push操作，并存储
cmp.href.back(); //CMPRouter执行pop操作，并存储
```
*  返回到首页时，back方法内部判断是首页，执行closePage方法，关闭整个webview。

#### 2、CMP的backbutton详解和用法

简介说明：
CMP的backbutton组件，主要控制H5页面的返回按钮，点击返回按钮时，会触发一个事件，由业务方处理。

在当前页面加载完成时，会有一个全局堆栈数组，一开始是[]空的。需要在页面加载完成后，调用<code>cmp.backbutton.push(cmp.href.back);</code>
去加入事件堆栈，才能执行返回操作。一般解决问题是：编辑页面的时候，触发了返回事件，需要弹出提示是否返回的弹框。当点击了确定，则执行返回操作。返回操作里面需要执行<code>cmp.backbutton.pop();</code>

示例代码：
```js
cmp.ready(function(){
    cmp.backbutton();
    cmp.backbutton.push(function(){
        //可以写当前业务要返回时的逻辑
        cmp.href.back();
    })
})
```
说明：当一个页面加载完成之后，需要在cmp.ready里面使用：<code>cmp.backbutton();</code> //初始化监听
使用：<code>cmp.backbutton.push(cmp.href.back);</code>初始化默认的返回方法。cmp.href.back方法里面已经自带<code>cmp.backbutton.pop()</code>,所以只push一次是无需再调用<code>cmp.backbutton.pop();</code>

打印堆栈信息：
```js
cmp.backbutton.stack //输出 [function,function] 当前堆栈内的回调函数
```

#### 3、CMP背景蒙层组件逻辑

简介说明：
CMP的zIndex组件，主要控制H5页面弹出类的元素，进行背景蒙层的层级控制。比如一个<code>alert</code>组件，弹出时，底部有个黑色背景。

假设我们不控制层级的话，以协同模块处理详情时的【更多】按钮来作为示例，可以选择更多数据的一个弹出层，这个弹出层里面可以调用cmp的弹出组件(假设是alert)。那么将会出现2种混乱情况的问题：

* <font size="1">点击协同详情页面上面的"更多"按钮，打开这个自定义弹出层，再次点击里面的cmp的弹出层alert，此时如果自定义层级随便写了一个z-index:30，或者1000。那么cmp的弹出层就不会展示出来，会被自定义弹出层给遮挡或者被遮挡。</font>
* <font size="1">或者这个自定义弹出层是由cmp的actionsheet弹出层打开的，如果层级没有规范，将会出现遮挡自定义弹出层的问题。</font>

<font size="4" color="red">zIndex初始化值为50，组件取值范围为>50，业务不使用cmp.zIndex时的取值范围为<50。</font>

大概示例：
![z-index流程图.png](./iframePhone/assets/img/fingerPost/z-index流程图.png)

#### 4、M3和微协同区别

1、页面加载方式不同
* M3APP是原生壳的web加载H5页面，属于混合模式，微协同则是纯H5，用于集成到企业微信，微信，钉钉等平台使用。

2、页面跳转方式不同
* 在页面跳转的时候，M3均是新开页面，意味着返回后，原来的页面还存在不会执行刷新，无加载时间，可以继续操作页面。
* 而微协同是单页面跳转，每次跳转页面后返回，都是将原来的页面刷新，需要等待时间。

3、一些特性不同
* 在M3里面可以使用原生APP自带的能力，比如M3可以使用致信消息，进行即时交流，扫码办事、离线通讯录等。

4、OA加载的包地址不同
* M3加载的资源包均是zip压缩格式，路径为：<code>/webapps/seeyon/m3files/</code>里面。
* 而微协同的资源均是目录文件格式，路径为：<code>/webapps/seeyon/m3/</code>里面。

## 7. 各APP平台的userAgent

> 路由：`userAgent`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/userAgent.md

### 一、微协同集成的APP类

以下信息中的 \<Version\>, \<NetworkType\>, \<Language\>, \<Device\>, \<BuildID\>, \<WeChatVersion\>, \<PrivateDeploymentVersion\> 等占位符代表具体的版本号、网络类型、语言、设备型号、构建ID等信息，这些在不同设备和版本上会有所不同。

##### 1、微信
Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build/<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36 MicroMessenger<Version> NetType<NetworkType> Language<Language>
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS X_X like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 MicroMessenger<Version> NetType<NetworkType> Language<Language>
```
##### 2、钉钉
Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36 DingTalk<Version> com.alibaba.android.rimet<Version>
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS X_X like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 AliApp(DingTalk<Version>) com.laiwang.DingTalk<Version>
```
##### 3、企业微信
Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36 wxwork<Version> MicroMessenger<WeChatVersion> NetType<NetworkType> Language<Language>
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS X_X like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 wxwork<Version> MicroMessenger<WeChatVersion> NetType<NetworkType> Language<Language>
```
##### 4、企业微信(私有部署)
Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36 wxworklocal<Version> MicroMessenger<WeChatVersion> NetType<NetworkType> Language<Language> wxwork_priv<PrivateDeploymentVersion>
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS X_X like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 wxworklocal<Version> MicroMessenger<WeChatVersion> NetType<NetworkType> Language<Language> wxwork_priv<PrivateDeploymentVersion>
```
##### 5、企业微信(政务)
Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36 wxworkgov<Version> MicroMessenger<WeChatVersion> NetType<NetworkType> Language<Language>
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS X_X like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 wxworkgov<Version> MicroMessenger<WeChatVersion> NetType<NetworkType> Language<Language>
```
##### 6、飞书
Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36 Lark<Version>
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS X_X like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 Lark<Version>
```
##### 7、welink
Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36 welink<Version>
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS X_X like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 welink<Version>
```
### 二、M3使用的APP类

Android:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36/seeyonCordova ANDROID (cmpTheme:white) (cmpLanguage:zh_CN) TencentMTA/1
```
AndroidPad:
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36/seeyonCordova ANDROIDPAD (cmpTheme:white) (cmpLanguage:zh_CN) TencentMTA/1
```
IOS:
```js
Mozilla/5.0 (iPhone; CPU iPhone OS 17_5_1 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 seeyonCordova Device/iPhoneX (cmpStasHt:47.000000) (cmpLanguage:zh_CN) (cmpTheme:white)
```
IOS Pad:
```js
Mozilla/5.0 (iPad; CPU OS 17_4 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E148 seeyonCordova Device/iPhoneX (cmpStasHt:24.000000) (cmpLanguage:zh_CN) (cmpTheme:white)
```
鸿蒙(非Next版本):
```js
Mozilla/5.0 (Linux; Android X.X; <Device> Build<BuildID>; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/XX.0.0.0 Mobile Safari/537.36/seeyonCordova (cmpTheme:white) (cmpLanguage:zh_CN) HarmonyOs
```
鸿蒙 Next版本:
```js
Mozilla/5.0 (Tablet; OpenHarmony X.X) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/XX.0.0.0 Safari/537.36  ArkWeb/4.1.6.1 Mobile WebOffice/1.0 (M3Harmony/Android CMP 1.0)
```

## 8. 重要更新

> 路由：`importantUpdate`  
> 版本：`!!!`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/importantUpdate.md

### M3移动办公APP网络协议更换说明

<span style="color:red;font-size:16px;">
OA版本V9.0及以上的版本，M3的IOS端APP移动办公不再支持通过http://、https://协议加载本地资源文件(本地资源就是APP程序内的已存在资源,比如已下载好的业务包:cmp.zip/1.zip等/webapps/seeyon/m3files目录内的)。
</span>


- 苹果系统在web容器获取本地资源文件，不允许通过拦截http、https等标准协议的方式去加载本地资源文件。在OA 9.0及以上版本，并且M3客户端APP iOS端版本需 <code>>=4.6.3</code> 版本，只能支持使用自定义协议cmp://方式加载本地资源文件。

http协议下的iOS端对cmp://协议生效，Android端对http://和https://、cmp://均生效：

|   协议    |              Android                  |  IOS    |
|   ---------   | ---------------------------------- | --------------- |
|   http://   |     支持     |  不支持 |
|     https://     |     支持     | 不支持 |
|   cmp://   |     支持     | 支持 |


<h3>IOS引入资源协议差异(Android无协议限制)：</h3>

<table>
  <tr>
    <th>引入方式</th>
    <th>当前OA网络协议</th>
    <th >OA版本</th>
    <th>加载方式</th>
    <th>要求</th>
    <th>问题</th>
  </tr>
  <tr>
    <td rowspan="4">M3 APP内资源</td>
    <td rowspan="2">http</td>
    <td><9.0</td>
    <td>http://  比如：http://cmp/v/js/cmp-i18n.js</td>
    <td>在M3 APP中打开页面</td>
    <td rowspan="3">如果三方页面和M3的web容器有冲突，则不能使用该方式。具体原因： https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+NTQ5</td>
  </tr>
  <tr>
    <td>>=9.0</td>
    <td>cmp:// 比如：cmp://cmp/v/js/cmp-i18n.js</td>
    <td>M3 APP版本>4.4.2</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="2">https</td>
    <td><9.0</td>
    <td>https://  比如：https://cmp/v/js/cmp-i18n.js</td>
    <td>版本无限制</td>
  </tr>
  <tr>
    <td>>=9.0</td>
    <td>不支持</td>
    <td>版本无限制</td>
    <td>在https下加载非https资源时，会报安全协议不允许的问题，假如使用cmp://或者使用http去加载资源，都会报错。所以只有使用https://oa.com/seeyon/m3/cmp/js/cmp-i18n.js这样来加载服务器资源。</td>
  </tr>

  <tr>
    <td>OA服务器资源</td>
    <td>http/https</td>
    <td>不限</td>
    <td>http/https://oa.com/seeyon/m3/cmp/js/cmp-i18n.js</td>
    <td>文件资源跟随OA版本</td>
    <td></td>
  </tr>
</table>


<span style="color:red;font-size:15px;">
该文档中所有示例均是http://，请特别注意OA版本是否等于9.0及以上时，在IOS端加载的资源时会有所差异。
</span>

## 9. 输出打包

> 路由：`outputPackage`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/outputPackage.md

## 移动端出包

> **主要说明开发人员解决客户移动端的bug后，向客户出补丁包的路径规范以及需要注意的细节问题。**



#### 1、简介说明

> 主要区分：微协同一般为OA嵌入到包括
>
> - 微信
> - 企业微信
> - 钉钉/welink/飞书
> - 第三方应用APP
>
> 等等。直接使用M3移动办公就是M3应用。具体详细区别见[CMP核心知识第4点](/#/fingerpost/fingerpost/corePrinciple)



#### 2、微协同处理bug出包

> **补丁包路径** ：seeyon\m3\\...   此路径为微协同出包路径。一般单文件出包直接放cmp目录下，seeyon\m3\\apps\\...一般直接放对应出包的完整文件夹。
>  - &#x1F4C2; seeyon
>    - &#x1F4C2; m3
>      - &#x1F4C2; cmp
>        - &#x1F4C2; js
>      - &#x1F4C2; apps
>        - &#x1F4C2; m3
>        - &#x1F4C2; v5

**注意：** 微协同只需出包对应路径下的**单个js/html/css文件**，客户打补丁后会相应覆盖旧文件

> **主要出包部署路径**：Seeyon\A8\ApacheJetspeed\webapps\seeyon\m3 
>
> - &#x1F4C2; Seeyon
>   - &#x1F4C2; A8
>     - &#x1F4C2;ApacheJetspeed
>       - &#x1F4C2; webapps
>         -  &#x1F4C2;seeyon
>            -  &#x1F4C2;m3
>                -  ...



#### 3、M3处理bug出包

**预处理**：M3出包需要对修改文件对应项目所在**文件夹的所有内容**做[**S3script**处理](/#/fingerpost/fingerpost/S3release)（处理静态资源路径问题）处理后的结果均为zip压缩包。结果中微协同对应数字命名.zip，M3对应文件夹名.zip。

> **补丁包路径** ： seeyon\m3files\m3 
>
> - &#x1F4C2; seeyon
>   -  &#x1F4C2; m3files
>       - &#x1F4C2; v5
>           -  ...
>       - &#x1F4C2; m3
>           -  ...

**注意：**M3需出包对应路径下的**整个文件夹**，S3script处理后均为**压缩包**形式。

> **出包部署路径**：Seeyon\A8\ApacheJetspeed\webapps\seeyon\m3files\
>
> - &#x1F4C2; Seeyon
>   -  &#x1F4C2; A8
>      - &#x1F4C2;ApacheJetspeed
>        - &#x1F4C2; webapps
>            -  &#x1F4C2;seeyon
>               -  &#x1F4C2;m3files
>                  - &#x1F4C2;m3
>                  - &#x1F4C2;v5

#### 4、全量出包

>全量出包指的是出包**对应版本**所有**build ID**的补丁包

**注意：** 在线全量出包的结果就是pak包。补丁包在线制作地址：<http://service.seeyon.com:3366/bpo/>

## 10. iOS端M3-WEB容器拦截问题

> 路由：`iosIntercept`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/iosIntercept.md

## iOS端M3-WEB容器拦截问题

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/iosIntercept.md）

## 11. CMP文件优化业务适配说明

> 路由：`cmpMerge`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/cmpMerge.md

## CMP 文件优化业务适配方案

### 方案步骤

#### 1. CMP文件资源合并

合并后的文件列表及体积对比：

| 原文件列表 | 合并后文件 | 体积 | gzip体积 |
|------------|------------|----------|--------------|
| cmp-asyncLoad.js, cmp-description.js | cmp.js | 297KB | 88.9KB |
| cmp-scrollBox.js, cmp-sortable.js, cmp-watermark.js, cmp-watermark2.js, cmp-zoom.js, cmp-v5.js, cmp-cache-control.js, cmp-head2base64.js, cmp-footerAuto.js | cmp-util.js | 59KB | 20.4KB |
| cmp-dtPicker.js, cmp-dtPicker-calender.js, cmp-picker.js, cmp-popover.js, cmp-popPicker.js, cmp-dateCalender.js, cmp-headerFixed.js, cmp-search.js, cmp-groupSearch.js, cmp-sliders.js, cmp-switch.js, cmp-tabBar.js, cmp-tabChange.js, cmp-fullPage.js | cmp-ui.js | 136KB | 36.6KB |
| cmp-audio.js, cmp-barcode.js, cmp-chat.js, cmp-contentEdit.js, cmp-gestureLock.js, cmp-handWriteSignature.js, cmp-offlineContacts.js, cmp-push.js, cmp-server.js, cmp-shell.js, cmp-telmail.js, cmp-webviewListener.js, cmp-lbs.js, cmp-speechRobot.js | cmp-native.js | 36KB | 9.3KB |
| cmp-listView.js, cmp-listViewSmooth.js, cmp-accDoc.js, cmp-emoji.js, cmp-flowV5.js, cmp-imgCache.js, cmp-indexedList.js, cmp-qrcode.min.js, cmp-quick-select-people.js, remogeo.js, cmp-app.js | cmp-business.js | 334KB | 92.4KB |
| 所有css资源（除cmp-selectOrg.css, cmp-accDoc.css, cmp-handwriting.css, cmp-lbsMapUi.css）均合并为cmp.css | cmp.css | 349KB | 77.4KB |
| 所有国际化资源 | cmp-i18n_en.js, cmp-i18n_zh_CN.js, cmp-i18n_zh_TW.js | 27KB | 7.1KB |

#### 2. 待办列表首页资源引入更改

![todoMergeDemo.png](./iframePhone/assets/img/fingerPost/todoMergeDemo.png)

#### 3. 动态资源文件更改引入

使用`cmp.require`方法动态加载资源：

```javascript
/**
 * 动态加载资源
 * @param {array|string} params 需要导入的参数，支持导入数组、字符串、模块名
 * @param {function} callback 回调函数，资源全部加载完成后触发回调
 */
cmp.require(params, callback);

// 示例
cmp.require(['/seeyon/m3/cmp/js/cmp-ui.js', '/seeyon/m3/cmp/css/cmp-picker.css']);
cmp.require('ui-actionSheet', function() {
    // actionSheet组件导入成功
});
cmp.require(['ui-actionSheet','ui-nav'], function() {
    // actionSheet和ui-nav组件导入成功
});
```

原cmp.asyncLoad.js和cmp.asyncLoad.css方法任然保留。

## 12. 原生导航设置

> 路由：`/component/native/nativeHeader`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/nativeHeader.md

## 原生导航设置

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/nativeHeader.md）

## 13. 设备信息

> 路由：`/component/native/devices`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/devices.md

## 设备信息

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/devices.md）

## 14. 电话短信

> 路由：`/component/native/tel`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/tel.md

## 电话短信

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/tel.md）

## 15. 相机

> 路由：`/component/native/camera`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/camera.md

## 相机

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/camera.md）

## 16. 邮件

> 路由：`/component/native/mail`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/mail.md

## 邮件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/mail.md）

## 17. 录音和播放录音

> 路由：`/component/native/audio`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/audio.md

## 录音和播放录音

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/audio.md）

## 18. 二维码扫描

> 路由：`/component/native/barcode`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/barcode.md

## 二维码扫描

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/barcode.md）

## 19. 网络状态

> 路由：`/component/native/network`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/network.md

## 网络状态

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/network.md）

## 20. 打开第三方应用

> 路由：`/component/native/openThridApp`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/openThridApp.md

## 打开第三方应用

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/openThridApp.md）

## 21. webview操作

> 路由：`/component/native/webview`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/webview.md

## webview操作

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/webview.md）

## 22. 分享组件

> 路由：`/component/native/share`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/share.md

## 分享组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/native/share.md）

## 23. 关联文档

> 路由：`/component/v5/accDoc`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/accDoc.md

## 关联文档

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/accDoc.md）

## 24. 选人组件

> 路由：`/component/v5/selectOrg`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/selectOrg.md

## 选人组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/selectOrg.md）

## 25. 选人组件

> 路由：`/component/v5/selectOrgV80`  
> 版本：`V8.0`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/selectOrgV80.md

## 选人组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/selectOrgV80.md）

## 26. 流程图

> 路由：`/component/v5/treeView`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/treeView.md

## 流程图

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/treeView.md）

## 27. 表单签章

> 路由：`/component/v5/formSignature`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/formSignature.md

## 表单签章

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/formSignature.md）

## 28. V5类的附件上传下载套件

> 路由：`/component/v5/fileUpload`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/fileUpload.md

## V5类的附件上传下载套件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/fileUpload.md）

## 29. 金格正文组件

> 路由：`/component/v5/content`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/content.md

## 金格正文组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/v5/content.md）

## 30. button 按钮

> 路由：`/component/module/button`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/button.md

## button 按钮

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/button.md）

## 31. actionSheet

> 路由：`/component/module/actionSheet`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/actionSheet.md

## actionSheet

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/actionSheet.md）

## 32. Nav 页签

> 路由：`/component/module/nav`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/nav.md

## Nav 页签

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/nav.md）

## 33. navComp 页签

> 路由：`/component/module/navComp`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/navComp.md

## navComp 页签

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/navComp.md）

## 34. upload 上传套件

> 路由：`/component/module/upload`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/upload.md

## upload 上传套件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/upload.md）

## 35. voice 语音

> 路由：`/component/module/voice`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/voice.md

## voice 语音

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/voice.md）

## 36. pagePlaceholder 骨架屏

> 路由：`/component/module/pagePlaceholder`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/pagePlaceholder.md

## pagePlaceholder 骨架屏

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/pagePlaceholder.md）

## 37. apishare 分享

> 路由：`/component/module/apishare`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/apishare.md

## apishare 分享

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/apishare.md）

## 38. errorView 错误面板

> 路由：`/component/module/errorView`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/errorView.md

## errorView 错误面板

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/errorView.md）

## 39. enum

> 路由：`/component/module/enum`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/enum.md

## enum

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/enum.md）

## 40. appList 应用列表

> 路由：`/component/module/appList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/appList.md

## appList 应用列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/appList.md）

## 41. businessList 业务列表

> 路由：`/component/module/businessList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/businessList.md

## businessList 业务列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/businessList.md）

## 42. bbsList 讨论列表

> 路由：`/component/module/bbsList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/bbsList.md

## bbsList 讨论列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/bbsList.md）

## 43. docList 文档列表

> 路由：`/component/module/docList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/docList.md

## docList 文档列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/docList.md）

## 44. commentList 回复列表

> 路由：`/component/module/commentList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/commentList.md

## commentList 回复列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/commentList.md）

## 45. memberList 人员列表

> 路由：`/component/module/memberList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/memberList.md

## memberList 人员列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/memberList.md）

## 46. newsList 新闻列表

> 路由：`/component/module/newsList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/newsList.md

## newsList 新闻列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/newsList.md）

## 47. selectList 选择列表

> 路由：`/component/module/selectList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/selectList.md

## selectList 选择列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/selectList.md）

## 48. selectionList 多选列表

> 路由：`/component/module/selectionList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/selectionList.md

## selectionList 多选列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/selectionList.md）

## 49. showList

> 路由：`/component/module/showList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/showList.md

## showList

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/showList.md）

## 50. functionList

> 路由：`/component/module/functionList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/functionList.md

## functionList

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/functionList.md）

## 51. drawer抽屉组件

> 路由：`/component/module/drawer`  
> 版本：`V9.0`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/drawer.md

## drawer抽屉组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/drawer.md）

## 52. filterSearch 过滤搜索组件

> 路由：`/component/module/filterSearch`  
> 版本：`V9.0`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/filterSearch.md

## filterSearch 过滤搜索组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/module/filterSearch.md）

## 53. Button 按钮

> 路由：`/component/ui/UIbutton`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/UIbutton.md

## Button 按钮

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/UIbutton.md）

## 54. Badge 数字角标

> 路由：`/component/ui/badge`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/badge.md

## Badge 数字角标

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/badge.md）

## 55. Header布局

> 路由：`/component/ui/header`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/header.md

## Header布局

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/header.md）

## 56. Footer 底部导航栏

> 路由：`/component/ui/footer`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/footer.md

## Footer 底部导航栏

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/footer.md）

## 57. Checked 复选单选框

> 路由：`/component/ui/checked`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/checked.md

## Checked 复选单选框

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/checked.md）

## 58. Input 输入框

> 路由：`/component/ui/input`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/input.md

## Input 输入框

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/input.md）

## 59. Switch 开关

> 路由：`/component/ui/switch`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/switch.md

## Switch 开关

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/switch.md）

## 60. Progress 进度条

> 路由：`/component/ui/progress`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/progress.md

## Progress 进度条

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/progress.md）

## 61. Loading 加载状态

> 路由：`/component/ui/loading`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/loading.md

## Loading 加载状态

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/loading.md）

## 62. 9Grid 9宫格

> 路由：`/component/ui/9grid`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/9grid.md

## 9Grid 9宫格

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/9grid.md）

## 63. Nav 页签

> 路由：`/component/ui/UInav`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/UInav.md

## Nav 页签

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/UInav.md）

## 64. Drawer 全屏抽屉

> 路由：`/component/ui/uidrawer`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/uidrawer.md

## Drawer 全屏抽屉

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/uidrawer.md）

## 65. ListUi 列表UI

> 路由：`/component/ui/listUi`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/listUi.md

## ListUi 列表UI

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/listUi.md）

## 66. Alert 弹出框

> 路由：`/component/ui/alert`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/alert.md

## Alert 弹出框

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/alert.md）

## 67. GroupSearch 组合搜索

> 路由：`/component/ui/groupSearch`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/groupSearch.md

## GroupSearch 组合搜索

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/groupSearch.md）

## 68. DateCalender日历组件

> 路由：`/component/ui/dateCalender`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/dateCalender.md

## DateCalender日历组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/dateCalender.md）

## 69. DatePicker 日期选择组件

> 路由：`/component/ui/datePicker`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/datePicker.md

## DatePicker 日期选择组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/datePicker.md）

## 70. Watermark 水印

> 路由：`/component/ui/watermark`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/watermark.md

## Watermark 水印

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/watermark.md）

## 71. ListView 滚动列表

> 路由：`/component/ui/listView`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/listView.md

## ListView 滚动列表

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/listView.md）

## 72. ScrollBox 正文滚动

> 路由：`/component/ui/scrollBox`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/scrollBox.md

## ScrollBox 正文滚动

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/scrollBox.md）

## 73. TableList table列表滚动

> 路由：`/component/ui/tableList`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/tableList.md

## TableList table列表滚动

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/tableList.md）

## 74. Zoom  缩放组件

> 路由：`/component/ui/zoom`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/zoom.md

## Zoom  缩放组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/zoom.md）

## 75. Sortable 拖拽排序

> 路由：`/component/ui/sortable`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/sortable.md

## Sortable 拖拽排序

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/sortable.md）

## 76. LargePicture 正文大图查看

> 路由：`/component/ui/largePicture`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/largePicture.md

## LargePicture 正文大图查看

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/largePicture.md）

## 77. Calender 日历时间选择

> 路由：`/component/ui/dtPickerCalender`  
> 版本：`V7.1SP1`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/dtPickerCalender.md

## Calender 日历时间选择

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/dtPickerCalender.md）

## 78. slider 轮播图

> 路由：`/component/ui/slider`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/slider.md

## slider 轮播图

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/ui/slider.md）

## 79. H5调试准备

> 路由：`/inspect/inspect`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect.md

## H5调试准备

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect.md）

## 80. 熟悉调试面板

> 路由：`/inspect/inspect/inspect`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect/inspect.md

## 熟悉调试面板

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect/inspect.md）

## 81. 手机开启调试模式

> 路由：`/inspect/inspect/phoneOpendebug`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect/phoneOpendebug.md

## 手机开启调试模式

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect/phoneOpendebug.md）

## 82. Edge浏览器inspect

> 路由：`/inspect/inspect/edgeInspect`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect/edgeInspect.md

## Edge浏览器inspect

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/inspect/edgeInspect.md）

## 83. M3APP调试-安卓端

> 路由：`/inspect/m3debugAndroid`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid.md

## M3APP调试-安卓端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid.md）

## 84. 获取调试版本M3

> 路由：`/inspect/m3debugAndroid/debugm3`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/debugm3.md

## 获取调试版本M3

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/debugm3.md）

## 85. 模拟器调试

> 路由：`/inspect/m3debugAndroid/simulatorDebug`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/simulatorDebug.md

## 模拟器调试

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/simulatorDebug.md）

## 86. 真机调试

> 路由：`/inspect/m3debugAndroid/realDebug`  
> 版本：`推荐`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/realDebug.md

## 真机调试

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/realDebug.md）

## 87. M3日志抓取

> 路由：`/inspect/m3debugAndroid/m3Log`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/m3Log.md

## M3日志抓取

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugAndroid/m3Log.md）

## 88. M3APP调试-IOS端

> 路由：`/inspect/m3debugIOS`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugIOS.md

## M3APP调试-IOS端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugIOS.md）

## 89. 模拟器调试

> 路由：`/inspect/m3debugIOS/m3debugIOS`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugIOS/m3debugIOS.md

## 模拟器调试

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugIOS/m3debugIOS.md）

## 90. M3APP调试-鸿蒙Next端

> 路由：`/inspect/m3debugharmony`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugharmony.md

## M3APP调试-鸿蒙Next端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugharmony.md）

## 91. 真机调试(windows版)

> 路由：`/inspect/m3debugharmony/m3debugharmony`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugharmony/m3debugharmony.md

## 真机调试(windows版)

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/m3debugharmony/m3debugharmony.md）

## 92. 微协同调试-PC端

> 路由：`/inspect/wechatPC`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatPC.md

## 微协同调试-PC端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatPC.md）

## 93. 微协同模拟调试

> 路由：`/inspect/wechatPC/simulationDebug`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatPC/simulationDebug.md

## 微协同模拟调试

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatPC/simulationDebug.md）

## 94. 微协同调试-安卓端

> 路由：`/inspect/wechatIntegration`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration.md

## 微协同调试-安卓端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration.md）

## 95. 微信

> 路由：`/inspect/wechatIntegration/wechat`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/wechat.md

## 微信

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/wechat.md）

## 96. 企业微信

> 路由：`/inspect/wechatIntegration/weCom`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/weCom.md

## 企业微信

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/weCom.md）

## 97. 钉钉/welink/飞书

> 路由：`/inspect/wechatIntegration/dingding`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/dingding.md

## 钉钉/welink/飞书

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/dingding.md）

## 98. 微协同调试-IOS端

> 路由：`/inspect/wechatIOS`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIOS.md

## 微协同调试-IOS端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIOS.md）

## 99. 模拟器调试

> 路由：`/inspect/wechatIOS/wechatIOSsimulator`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIOS/wechatIOSsimulator.md

## 模拟器调试

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIOS/wechatIOSsimulator.md）

## 100. 数据请求抓包调试

> 路由：`/inspect/request`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request.md

## 数据请求抓包调试

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request.md）

## 101. PC端Fiddler抓包

> 路由：`/inspect/request/fiddler`  
> 版本：`推荐`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/fiddler.md

## PC端Fiddler抓包

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/fiddler.md）

## 102. Stream抓包IOS端

> 路由：`/inspect/request/stream`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/stream.md

## Stream抓包IOS端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/stream.md）

## 103. httpCanary抓包安卓端

> 路由：`/inspect/request/httpCanary`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/httpCanary.md

## httpCanary抓包安卓端

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/httpCanary.md）

## 104. 后台CTP.log日志

> 路由：`/inspect/request/ctplog`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/ctplog.md

## 后台CTP.log日志

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/ctplog.md）

## 105. M3开启vconsole

> 路由：`/inspect/request/m3vconsole`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/m3vconsole.md

## M3开启vconsole

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/request/m3vconsole.md）

## 106. 微协同开启vconsole

> 路由：`/inspect/wechatIntegration/wechatVconsole`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/wechatVconsole.md

## 微协同开启vconsole

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect/wechatIntegration/wechatVconsole.md）

## 107. M3集成第三方H5页面

> 路由：`m3inH5`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/m3inH5.md

## M3集成第三方H5页面

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/m3inH5.md）

## 108. 概述

> 路由：`/third/m3inH5/m3inH5`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/m3inH5/m3inH5.md

## 概述

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/m3inH5/m3inH5.md）

## 109. 常见问题

> 路由：`/third/m3inH5/m3inH5Problem`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/m3inH5/m3inH5Problem.md

## 常见问题

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/m3inH5/m3inH5Problem.md）

## 110. OA9.0以上版本IOS集成问题

> 路由：`/third/m3inH5/m3inH5Problem2`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/m3inH5/m3inH5Problem2.md

## OA9.0以上版本IOS集成问题

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/m3inH5/m3inH5Problem2.md）

## 111. 微协同集成到第三方APP

> 路由：`H5inApp`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/H5inApp.md

## 微协同集成到第三方APP

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/H5inApp.md）

## 112. 概述

> 路由：`/third/H5inApp/H5inApp`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/H5inApp/H5inApp.md

## 概述

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/H5inApp/H5inApp.md）

## 113. 常见问题

> 路由：`/third/H5inApp/H5inAppProblem`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/H5inApp/H5inAppProblem.md

## 常见问题

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/H5inApp/H5inAppProblem.md）

## 114. 微协同集成到第三方H5

> 路由：`wechatInH5`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/wechatInH5.md

## 微协同集成到第三方H5

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/wechatInH5.md）

## 115. 概述

> 路由：`/third/wechatInH5/wechatInH5`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/wechatInH5/wechatInH5.md

## 概述

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/wechatInH5/wechatInH5.md）

## 116. 常见问题

> 路由：`/third/wechatInH5/wechatInH5Problem`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/wechatInH5/wechatInH5Problem.md

## 常见问题

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third/wechatInH5/wechatInH5Problem.md）

## 117. 指南

> 路由：`/fingerpost`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//fingerpost.md

## 指南

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//fingerpost.md）

## 118. 指南

> 路由：`fingerpost`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/fingerpost.md

## 指南

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/fingerpost.md）

## 119. 组件

> 路由：`/component`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component.md

## 组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component.md）

## 120. 基础类

> 路由：`basic`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/basic.md

## 基础类

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/basic.md）

## 121. 布局

> 路由：`/component/basic/layout`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/layout.md

## 布局

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/layout.md）

## 122. 字体

> 路由：`/component/basic/font`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/font.md

## 字体

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/font.md）

## 123. 颜色主题

> 路由：`/component/basic/color`  
> 版本：`V8.0`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/color.md

## 颜色主题

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/color.md）

## 124. Icon图标

> 路由：`/component/basic/icon`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/icon.md

## Icon图标

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/icon.md）

## 125. 附件图标

> 路由：`/component/basic/fileIcon`  
> 版本：`V7.0`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/fileIcon.md

## 附件图标

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//component/basic/fileIcon.md）

## 126. UI组件

> 路由：`ui`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/ui.md

## UI组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/ui.md）

## 127. 模块组件

> 路由：`module`  
> 版本：`V8.0+`  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/module.md

## 模块组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/module.md）

## 128. 业务组件

> 路由：`v5`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/v5.md

## 业务组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/v5.md）

## 129. 原生组件

> 路由：`native`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/native.md

## 原生组件

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost/native.md）

## 130. API

> 路由：`/api`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//api.md

## API

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//api.md）

## 131. 第三方集成

> 路由：`/third`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third.md

## 第三方集成

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//third.md）

## 132. 调试

> 路由：`/inspect`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect.md

## 调试

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//inspect.md）

## 133. 资源

> 路由：`/sources`  
> 版本：``  
> Markdown URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//sources.md

## 资源

（未能获取 Markdown：HTTP 404，URL：https://open.seeyoncloud.com/cmpdev/iframePhone/md/fingerPost//sources.md）
