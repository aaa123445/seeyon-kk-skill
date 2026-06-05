# Seeyon V5 Dev CAP 文档汇总

- 来源：https://open.seeyoncloud.com/v5devCAP/
- 提取文档数：128
- 说明：从 VuePress 静态站点 JS 中的原始 Markdown content 字段提取整理。

## 目录

1. [快速开始](#快速开始) — `/quickStart/`
2. [Hello World](#hello-world) — `/quickStart/helloworld.html`
3. [Nice Code](#nice-code) — `/quickStart/nicecode.html`
4. [CAP应用平台](#cap应用平台) — `/94/`
5. [特别说明](#特别说明) — `/94/355/359/373/`
6. [自定义控件 render扩展](#自定义控件-render扩展) — `/94/355/359/373/374.html`
7. [自定义控件前端2.0开发概述](#自定义控件前端20开发概述) — `/94/355/359/373/375.html`
8. [cap4自定义控件-PC端](#cap4自定义控件-pc端) — `/94/355/359/373/376.html`
9. [CAP4自定义控件后端规范](#cap4自定义控件后端规范) — `/94/355/359/373/377.html`
10. [CAP4自定义控件 - 移动端](#cap4自定义控件---移动端) — `/94/355/359/373/378.html`
11. [CAP4表单前端接口 - 移动端](#cap4表单前端接口---移动端) — `/94/355/359/373/379.html`
12. [关于协同升级到V5 8.0版本之后，自定义控件适配的说明](#关于协同升级到v5-80版本之后自定义控件适配的说明) — `/94/355/359/373/380.html`
13. [全量接口](#全量接口) — `/94/355/359/373/701.html`
14. [自定义控件打包规范](#自定义控件打包规范) — `/94/355/359/373/702.html`
15. [自定义控件开发痛点问题](#自定义控件开发痛点问题) — `/94/355/359/373/703.html`
16. [自定义控件开发痛点问题](#自定义控件开发痛点问题) — `/94/355/359/373/704.html`
17. [8.2以上OA版本新增自定义控件V3版本支持首次安装热加载，不需要重启](#82以上oa版本新增自定义控件v3版本支持首次安装热加载不需要重启) — `/94/355/359/373/1349.html`
18. [什么是触发：](#什么是触发) — `/94/355/359/381/382.html`
19. [一、触发队列作用](#一触发队列作用) — `/94/355/359/381/383.html`
20. [介绍](#介绍) — `/94/355/359/390/`
21. [CAP4无流程表单应用绑定自定义按钮开发文档](#cap4无流程表单应用绑定自定义按钮开发文档) — `/94/355/359/390/391.html`
22. [自定义控件内容区插槽开发文档](#自定义控件内容区插槽开发文档) — `/94/355/359/390/392.html`
23. [自定义控件筛选条件开发文档](#自定义控件筛选条件开发文档) — `/94/355/359/390/393.html`
24. [门户开发及栏目挂载](#门户开发及栏目挂载) — `/94/355/359/395/396.html`
25. [栏目开发及流程说明](#栏目开发及流程说明) — `/94/355/359/395/397.html`
26. [无流程模板](#无流程模板) — `/94/355/359/398.html`
27. [概要](#概要) — `/94/355/359/399/`
28. [介绍](#介绍) — `/94/355/359/399/400/`
29. [表单能力配置使用](#表单能力配置使用) — `/94/355/359/399/400/401.html`
30. [设计器能力配置](#设计器能力配置) — `/94/355/359/399/400/402/`
31. [如何添加添加字体库？](#如何添加添加字体库) — `/94/355/359/399/400/402/1337.html`
32. [事件API支持](#事件api支持) — `/94/355/359/399/400/403.html`
33. [Demo示例](#demo示例) — `/94/355/359/399/400/404.html`
34. [介绍](#介绍) — `/94/355/359/399/405/`
35. [插件使用步骤](#插件使用步骤) — `/94/355/359/399/405/406.html`
36. [表单插件接口](#表单插件接口) — `/94/355/359/399/405/407/`
37. [事件接口](#事件接口) — `/94/355/359/399/405/407/408.html`
38. [钩子相关接口](#钩子相关接口) — `/94/355/359/399/405/407/409.html`
39. [表单操作相关接口](#表单操作相关接口) — `/94/355/359/399/405/407/410.html`
40. [Demo示例](#demo示例) — `/94/355/359/399/405/411.html`
41. [表单运行态插件机制](#表单运行态插件机制) — `/94/355/359/399/405/412.html`
42. [介绍](#介绍) — `/94/355/359/399/413.html`
43. [1、介绍](#1介绍) — `/94/355/359/399/414.html`
44. [客开通路及插件体系版本支持](#客开通路及插件体系版本支持) — `/94/355/359/399/415.html`
45. [组件库开发指南](#组件库开发指南) — `/94/355/359/416/417.html`
46. [GFM语法解读](#gfm语法解读) — `/94/355/359/416/418.html`
47. [table表格](#table表格) — `/94/355/359/416/420/421.html`
48. [通用分页 组件](#通用分页-组件) — `/94/355/359/416/420/422.html`
49. [通用title 组件](#通用title-组件) — `/94/355/359/416/420/423.html`
50. [统计排队组件](#统计排队组件) — `/94/355/359/416/420/424.html`
51. [code组件](#code组件) — `/94/355/359/416/420/425.html`
52. [条件筛选组件](#条件筛选组件) — `/94/355/359/416/420/426.html`
53. [批量导入组件](#批量导入组件) — `/94/355/359/416/420/427.html`
54. [上传组件](#上传组件) — `/94/355/359/416/420/428.html`
55. [批量更新组件](#批量更新组件) — `/94/355/359/416/420/429.html`
56. [批量刷新组件](#批量刷新组件) — `/94/355/359/416/420/430.html`
57. [组件cap4-button](#组件cap4-button) — `/94/355/359/416/431/432.html`
58. [组件名cap4-checkbox](#组件名cap4-checkbox) — `/94/355/359/416/431/433.html`
59. [组件名cap4-color](#组件名cap4-color) — `/94/355/359/416/431/434.html`
60. [组件名cap4-eg](#组件名cap4-eg) — `/94/355/359/416/431/435.html`
61. [组件名cap4-horizontal-list](#组件名cap4-horizontal-list) — `/94/355/359/416/431/436.html`
62. [组件名cap4-icon](#组件名cap4-icon) — `/94/355/359/416/431/437.html`
63. [组件名cap4-indicator](#组件名cap4-indicator) — `/94/355/359/416/431/438.html`
64. [组件名cap4-radio](#组件名cap4-radio) — `/94/355/359/416/431/439.html`
65. [组件名cap4-search](#组件名cap4-search) — `/94/355/359/416/431/440.html`
66. [组件cap4-select](#组件cap4-select) — `/94/355/359/416/431/441.html`
67. [组件名cap4-shuttle](#组件名cap4-shuttle) — `/94/355/359/416/431/442.html`
68. [组件名cap4-tap](#组件名cap4-tap) — `/94/355/359/416/431/443.html`
69. [组件cap4-text](#组件cap4-text) — `/94/355/359/416/431/444.html`
70. [组件名cap4-tree](#组件名cap4-tree) — `/94/355/359/416/431/445.html`
71. [组件名cap4-validate](#组件名cap4-validate) — `/94/355/359/416/431/446.html`
72. [cap4-menu 组件](#cap4-menu-组件) — `/94/355/359/416/431/447.html`
73. [Cap4Iframe组件](#cap4iframe组件) — `/94/355/359/416/431/448.html`
74. [toolbar组件](#toolbar组件) — `/94/355/359/416/431/449.html`
75. [统计饼图](#统计饼图) — `/94/355/359/416/450/451.html`
76. [统计echart组件包](#统计echart组件包) — `/94/355/359/416/450/452.html`
77. [font-class引用](#font-class引用) — `/94/355/359/416/453.html`
78. [开发指南](#开发指南) — `/94/355/359/454/`
79. [CAP4自定义触发开发说明文档](#cap4自定义触发开发说明文档) — `/94/355/359/454/455.html`
80. [更新表单数据缓存](#更新表单数据缓存) — `/94/355/359/457/458.html`
81. [发起表单(Html正文)流程](#发起表单html正文流程) — `/94/355/359/457/459.html`
82. [Vue实战培训](#vue实战培训) — `/94/355/359/465/467.html`
83. [Vue进阶培训](#vue进阶培训) — `/94/355/359/465/468.html`
84. [前端构建](#前端构建) — `/94/355/359/465/469.html`
85. [portal和业务空间](#portal和业务空间) — `/94/355/359/479/`
86. [0、开发流程示意图](#0开发流程示意图) — `/94/355/359/479/480.html`
87. [栏目前端说明](#栏目前端说明) — `/94/355/359/479/481/`
88. [快速开始](#快速开始) — `/94/355/359/479/481/482.html`
89. [门户空间配置文件](#门户空间配置文件) — `/94/355/359/479/481/483.html`
90. [栏目配置文件](#栏目配置文件) — `/94/355/359/479/481/484.html`
91. [PortalAPI](#portalapi) — `/94/355/359/479/481/485.html`
92. [PortalDataAPI](#portaldataapi) — `/94/355/359/479/481/486.html`
93. [PortalAjax](#portalajax) — `/94/355/359/479/481/487.html`
94. [PortalEventBus](#portaleventbus) — `/94/355/359/479/481/488.html`
95. [PortalM3Utils](#portalm3utils) — `/94/355/359/479/481/489.html`
96. [## 1、什么是指标？](#1什么是指标) — `/94/355/359/479/481/490/492.html`
97. [0、菜单栏目](#0菜单栏目) — `/94/355/359/479/481/490/494.html`
98. [1、什么是列表栏目？](#1什么是列表栏目) — `/94/355/359/479/481/490/495.html`
99. [1、统计](#1统计) — `/94/355/359/479/481/490/496.html`
100. [有很多场景无需数据源，只需要内置对象即可开发出对应功能模块。](#有很多场景无需数据源只需要内置对象即可开发出对应功能模块) — `/94/355/359/479/481/491/`
101. [1、功能说明](#1功能说明) — `/94/355/359/479/481/491/498.html`
102. [功能说明](#功能说明) — `/94/355/359/479/481/491/499.html`
103. [功能说明](#功能说明) — `/94/355/359/479/481/491/500.html`
104. [应用场景](#应用场景) — `/94/355/359/479/481/503/504.html`
105. [0、前言](#0前言) — `/94/355/359/479/481/505.html`
106. [数据源开发](#数据源开发) — `/94/355/359/479/506/508.html`
107. [数据格式](#数据格式) — `/94/355/359/479/506/509.html`
108. [1、进入业务空间](#1进入业务空间) — `/94/355/359/479/511/512.html`
109. [经过源码编译后的文件【xxxxx.clmn】才能导入。](#经过源码编译后的文件xxxxxclmn才能导入) — `/94/355/359/479/511/513.html`
110. [应用包导入导出接入](#应用包导入导出接入) — `/94/355/359/895.html`
111. [文档概要](#文档概要) — `/94/355/360.html`
112. [vue快速上手](#vue快速上手) — `/94/355/361/362/363.html`
113. [前端开发规范](#前端开发规范) — `/94/355/361/364/365/`
114. [总体原则](#总体原则) — `/94/355/361/364/365/366.html`
115. [HTML规范](#html规范) — `/94/355/361/364/365/367.html`
116. [html&css规范](#htmlcss规范) — `/94/355/361/364/365/368.html`
117. [vue编码规范](#vue编码规范) — `/94/355/361/364/365/369.html`
118. [Javascript规范](#javascript规范) — `/94/355/361/364/365/370.html`
119. [后端开发规范](#后端开发规范) — `/94/355/361/364/371.html`
120. [表单业务讲解](#表单业务讲解) — `/94/355/477/`
121. [数据魔方](#数据魔方) — `/94/355/477/519.html`
122. [WBS客户使用的常见问题集合](#wbs客户使用的常见问题集合) — `/94/355/766/1351.html`
123. [标签打印自定义模板操作说明](#标签打印自定义模板操作说明) — `/94/355/1937/1938.html`
124. [特别说明](#特别说明) — `/94/470/471/`
125. [cap3自定义控件](#cap3自定义控件) — `/94/470/471/473.html`
126. [cap3 表单运行态接口](#cap3-表单运行态接口) — `/94/470/475.html`
127. [标题（第一行必须是一号标题，并且唯一）](#标题第一行必须是一号标题并且唯一) — `/2133/`
128. [应用平台](#应用平台) — `/2133/2134/2214.html`

---

## 1. 快速开始

> 原始路径：`/quickStart/`  
> 相对路径：`quickStart/README.md`  
> JS Chunk：`app.371b709c.js`

## 快速开始

欢迎来到快速开始页面

## 2. Hello World

> 原始路径：`/quickStart/helloworld.html`  
> 相对路径：`quickStart/helloworld.md`  
> JS Chunk：`app.371b709c.js`

## Hello World

北京欢迎您！

## 3. Nice Code

> 原始路径：`/quickStart/nicecode.html`  
> 相对路径：`quickStart/nicecode.md`  
> JS Chunk：`app.371b709c.js`

## Nice Code

这是一段优秀的代码！

## 4. CAP应用平台

> 原始路径：`/94/`  
> 相对路径：`94/README.md`  
> JS Chunk：`app.371b709c.js`

子菜单名称        URL
1.表单应用CAP4   1.表单应用CAP4
2.表单应用CAP3   2.表单应用CAP3

分享链接分享链接

## 5. 特别说明

> 原始路径：`/94/355/359/373/`  
> 相对路径：`94/355/359/373/README.md`  
> JS Chunk：`app.371b709c.js`

## 特别说明

作为客开控制使用的场景，不能直接复制标准控件的outerHTML，如果有该实现需求，须将DOM的class名字修改，以保证class名称与官方控件不重名，避免产生样式冲突 .

编撰人：yinyanting、admin




快速跳转



 * 特别说明



分享链接分享链接

## 6. 自定义控件 render扩展

> 原始路径：`/94/355/359/373/374.html`  
> 相对路径：`94/355/359/373/374.md`  
> JS Chunk：`app.371b709c.js`

## 自定义控件 render扩展

以富文本2为列，自定义控件全局唯一key：[RichText88826600909]

注：所有的文件夹和命名，都需要根据key来做唯一隔离



配置文件位置

\seeyon\common\customConfig\RichText88826600909.config

{
  "key": "RichText88826600909",
  "name": "RichText88826600909",
  "path":{
  "pc":"apps_res/cap/customCtrlResources/RichText88826600909/js",
  "wap":"m3/apps/v5/RichText88826600909/js",
  "native":"http://sourceId.v5.cmp/v1.0.0/js"
 },
    "render": {
     "defRender": {
   "filter": "render2Filter.umd.min.js",
   "list": "formrichtext2ctrl.umd.min.js",
   "mfilter": "render2mFilter.umd.min.js",
   "mlist": "formrichtext2ctrlM.umd.min.js"
  },
  "render1": {
   "filter": "render2Filter.umd.min.js",
   "list": "formrichtext2ctrl.umd.min.js",
   "mfilter": "render2mFilter.umd.min.js",
   "mlist": "formrichtext2ctrlM.umd.min.js",
   "087C5688-8C95-49B9-2502-6727D6C3YY91": {
    "filter": "render1AFilter.js",
     "list": "render1AList.js"
   }
  }
 },
  "renderMapping": {
  "cap4query": "render1",
  "cap4report": "render1",
  "relationList": "render1",
  "cap4unflow": {
   "filter": "render2Filter.umd.min.js",
   "list": "formrichtext2ctrl.umd.min.js",
   "mfilter": "render2mFilter.umd.min.js",
   "mlist": "formrichtext2ctrlM.umd.min.js",
   "087C5688-8C95-49B9-2502-6727D6C35502": {
    "filter": "render2AFilter.js",
       "list": "render2AList.js"
   }
  },
  "cap4unflow2": "text"
 }
}



## filter和list 渲染DEMO

编撰人：yinyanting、admin、xuecx


快速跳转



 * 自定义控件 render扩展



分享链接分享链接

## 7. 自定义控件前端2.0开发概述

> 原始路径：`/94/355/359/373/375.html`  
> 相对路径：`94/355/359/373/375.md`  
> JS Chunk：`app.371b709c.js`

## 自定义控件前端2.0开发概述

本文档仅适用于协同版本为V8.0&CAP4.5及以上版本的CAP4表单.

V8.0&CAP4.5前版本的自定义控件前端没有提供统一规范，在实际开发过程基本上是自行发挥，"借鉴"已开发的工程，开发门槛较高，开发者不知如何下手，同时也暴露了一些比较低级的错误。针对这些问题，提出了自定义控件前端2.0规范，定义自定义控件前端的基本生命周期、事件、校验接口等。

自定义控件前端2.0确定了以下内容:

 * 注册自定义控件统一接口
 * 确定了自定义控件基类，明确了控件的生命周期、事件、API
 * 规范基于csdk开放API来操作自定义控件、表单及进行数据通信
 * 提供了Promise支持（csdk已经注入polyfill)，建议异步操作都使用Promise


## 1. 启用自定义控件2.0

自定义控件2.0在每个控件上增加了一个version属性，version设为'2.0'即代表启用自定义控件2.0版本。




## 2. 自定义控件2.0生命周期

自定义控件生命周期大致分为下载、安装、渲染、更新、销毁等过程。

 * 下载: 表单根据接口返回的控件定义信息customFieldInfo下载自定义控件的主js资源及国际化文件
 * 安装: 资源下载完毕后调用控件定义的安装脚本（install）处理控件的初始化、业务逻辑等
 * 渲染: 当表单渲染到该自定义控件时，自定义控件的渲染方法被调用
 * 更新: 当控件数据发生变化时，自定义控件的更新方法被调用
 * 销毁: 当控件被表单主动销毁时，自定义控件的销毁方法被调用

详见下图



## 3. 注册自定义控件

用csdk.component.register(uuid, factory)申明自定义控件

 * uuid: 自定义控件的唯一标识，建议使用单词+uuid实现，保证全局唯一及可读性
 * factory: 自定义控件的具体实现，返回结构参照下图

csdk.component.register('myWidget-12345678', function () {
  return {
    ....
  }
});


自定义控件的基本代码结构如下



## 4. 生命周期钩子及API详细说明

下面对自定义控件的生命周期方法详述。

## - type

申明自定义控件实现的类型，可选值raw和vue, 当前版本仅支持raw。

 * raw: 原生js实现
 * vue: vue组件实现

## - plugin.install(context)

自定义控件资源下载完毕后调用plugin.install(contxt)执行安装脚本，一些常见的业务场景：

 * 加载控件使用到的其他资源，如js、css、图片等
 * 按次、按量计费的控件，超量超次控件不可使用，在install期间校验
 * 从服务器读取控件的相关业务配置

参数/返回值说明:
@param {Object} context {package: '自定义控件控件包地址'}，可用于加载包内的资源
@return Promise | undefined | Any

 * install方法返回Promise，则表单会等待异步操作完成后才开始渲染自定义控件。
 * install方法返回undefined, 表示操作完成。
 * install方法返回其他值，表示在安装中遇到错误，无法继续渲染（比如付费服务的调用次数用完）。

示例:

// 没有异步，操作成功
plugin: {
  install: function (context) {
    // 异步操作返回Promise，示例检查接口调用次数是否用完
    return new Promise(function (resolve) {
      ajax('/xyz/validateApi', {
        success: function(res) {
          if (res.count <= 0) return; // 次数用完
          resolve();
        }
      })
    })  
    // 安装脚本出错
    try {
      a.b(); // 模拟报错
    } catch (ex) {
      return ex || 'unknow error';
    }
    // 返回undefined，表示没有异步操作且成功
    return;
  }
}


## - plugin.requiredAssert(fieldData)

控件必填校验逻辑，由开发者根据业务需要自行实现，默认校验字段的value是否有值

参数/返回值说明:
@param {Object} fieldData: 自定义控件对象
@return Boolean

## - plugin.fieldLengthAssert(fieldData)

控件长度校验，由开发者根据业务需要自行实现，默认校验通过

参数/返回值说明:
@param {Object} fieldData: 自定义控件对象
@return Boolean

## - plugin.validAssert(fieldData)

控件自定义场景校验，由开发者根据业务需要自行实现，默认校验通过

参数/返回值说明:
@param {Object} fieldData: 自定义控件对象
@return Boolean

## - implement.init(context, container)

控件初始化渲染，由开发者根据自身业务实现控件的渲染，事件绑定等，该方法必须实现

参数/返回值说明:
@param {Object} context 初始化渲染上下文参数
@param {HTMLElement} container 控件渲染的容器元素
@return Promise | Any 如果返回Promise, 则控件渲染完成事件会等待promise完成后触发

context参数说明

option: {
  uuid: '', // 由表单生成唯一标识，用于识别控件实例，进行数据通信
  scope: '', // 所在表单视图作用域，用于区分包含视图引用（视图嵌套）场景
  fieldId: '', // 控件的数据域id
  recordId: '', // 明细行数据id
  tableName: '', // 明细表名
  container: HTMLElement // 容器元素
}


示例:

init: function (context, container) {
  console.log('init ' + this.$data.display)
  var ctx = this;
  var el = document.createElement('div');
  el.style.cssText = 'padding: 10px 5px; color: white; background: gray';
  el.innerHTML = this.$t('cap.form.loading'); // 国际化
  setTimeout(function () {
    el.innerHTML = 'test ' + ctx.$data.value;
  }, 1000);
  container.appendChild(el);
  this.$el = el;
  // 绑定事件
  this.$on(this.$el, 'tap', function () {
    // 更新数据
    ctx.$set({
      value: 'event changed ' + Date.now()
    });
  });

  return new Promise(function (resolve) {
    // 模拟异步渲染
    setTimeout(function () {
      this.$el.innerHTML = 'async rendering';
      resolve();
    }, 1000);
  });
}


## - implement.update()

当控件数据发生变化时，会触发该方法，由开发者实现渲染更新

示例:

update: function () {
  this.$el.innerHTML = 'updated at ' + Date.now() + '\n,new value is: ' + this.$data.value;
}


## - implement.destroy()

在控件被销毁前调用，由开发实现需要清理的事件、数据等

示例:

destroy: function () {
  console.log('destroy ' + this.$data.display)
  this.$el = null;
}


## - implement.beforeSave()

在表单保存时调用，由开发者实现当前控件需要在保存前的业务处理

参数说明:
@return Promise | Any 如果返回Promise，则表单会等待异步操作完成继续提交

注1: 由于交互问题，移动端轻表单模式只支持调用主表中的自定义控件该方法
注2: 由于数据分页，只支持调用在页面渲染好的（即可见）控件的该方法
注3: 除非特殊需要，尽可能减少这种场景设计

示例:

beforeSave: function () {
  console.log('beforeSave ' + this.$data.display);
  return new Promise((resolve) => {
    // do sth cost 2 seconds
    setTimeout(resolve, 2000);
  });
}


## - implement.afterSave()

表单提交后调用该方法，由于保存后页面会关闭或者刷新，只建议实现同步调用

示例:

afterSave: function () {
  console.log('Saved');
}


## - $t(i18nKey, replacer)

获取国际化词条

fI18nData['cap.form.mywidget.chineseDate'] = '{0}年{1}月';
this.$t('cap.form.mywidget.chineseDate', ['2020', '4']);


## - $set(data)

更新当前控件数据

示例:

data = {
  value: 'value', // 控件的值
  display: 'showValue', // 控件的显示值
  auth: 'auth', // 控件的权限
  atts: Object, // 待定，尚未完全支持
  placeholder: 'placeHolder' // 输入框占位符
};

this.$set({
  value: 'newValue',
  display: 'newShowValue',
  auth: 'browse'
})


## - $on(el, type, listener) 和 $on(type, listener)

控件事件绑定，支持绑定dom事件和控件自定义事件，使用方式如下:

 * $on(el, type, listener) : 绑定dom事件
 * $on(type, listener) : 绑定控件自定义事件

调用this.$on绑定的事件，在控件销毁时，会被自动销毁，开发者无须关注

## - $emit(type, data)

控件触发自定义事件


## 5. 自定义控件事件

EVENT_RENDERED: 自定义控件渲染完，需开发者保证
EVENT_UPDATED: 自定义控件更新完成
EVENT_DESTROYED: 自定义控件销毁

示例:

csdk.event.on(csdk.component.EVENT_RENDERED, function(evt) {
  console.log('component rendered', evt);
});



## 6. 与表单、其他控件交互通信

与自定义控件1.0版本相比，2.0版本只在初始化提供必要参数，1.0版本中提供的一些其他数据不再传入。如需要获取表单数据、获取其他控件数据、更新表单、更新其他控件（包括自定义控件自身）、监听数据变化等请使用表单提供的csdk开发套件。csdk.开发套件提供了一套PC和移动一致的API及事件，可实现大部分代码重用。

csdk相关文档见:
csdk API接口
csdk 事件接口
csdk 钩子

End

编撰人：yinyanting




快速跳转



 * 自定义控件前端2.0开发概述
   * 1. 启用自定义控件2.0
   * 2. 自定义控件2.0生命周期
   * 3. 注册自定义控件
   * 4. 生命周期钩子及API详细说明
     * - type
     * - plugin.install(context)
     * - plugin.requiredAssert(fieldData)
     * - plugin.fieldLengthAssert(fieldData)
     * - plugin.validAssert(fieldData)
     * - implement.init(context, container)
     * - implement.update()
     * - implement.destroy()
     * - implement.beforeSave()
     * - implement.afterSave()
     * - $t(i18nKey, replacer)
     * - $set(data)
     * - $on(el, type, listener) 和 $on(type, listener)
     * - $emit(type, data)
   * 5. 自定义控件事件
   * 6. 与表单、其他控件交互通信



分享链接分享链接

## 8. cap4自定义控件-PC端

> 原始路径：`/94/355/359/373/376.html`  
> 相对路径：`94/355/359/373/376.md`  
> JS Chunk：`app.371b709c.js`

## cap4自定义控件-PC端

----------------------------------------

cap4表单自定义控件参考开发文档 （文档默认是v7.0sp1开始支持，新增内容会备注开始支持版本号，删除内容会备注顶用版本号）


## 自定义控件介绍

A. 自定义控件增加了表单的可扩展性。
 a. 比如使用者想在页面中增加一个需求功能，例如在表单中显示一个统计页面的板块。而这样的需求在表单常规使用中很少会遇见，或者表单没有这样的标准控件。就可以通过自定义控件实现。
B. 自定义控件和表单的关系
 a. 自定义控件是寄生在表单上的单独的组件。会自己去渲染，表单不提供渲染。也可以自己通过接口和后端交互数据，不走表单的流程。
 b. 表单会给自定义控件一定范围的基础数据支持。会提供表单和自定义控件之间的数据交互API



## 一.开发规范


## 1.1 自定义控件文档结构

自定义控件项目前端可按照如下目录结构组织资源(开发文档结构没有强制规范，这只是建议，只要开发中的路径关系理顺就行)。

./                开发文件夹
├─js                      js资源
├─css                     css资源
├─icon                    图标资源
├─index.html              html资源



## 1.2 自定义控件基础规范

A.生成一个唯一标识
 a 开发者需要在前端代码中生成一个属于当前开发自定义控件的唯一标识，用于挂载到全局实现自定义控件命名空间(开发者自己维护)
B.控件代码里面的所有this指向window[1唯一标识]
C.确保有初始化入口方法(并且要配置到配置文档去)
D.建议使用闭包进行开发



## 1.3 自定义控件存在生命周期

自定义控件由入口方法调用开始加载，表单页面关闭销毁。



## 二. 自定义控件实现和交互规范

A.表单绘制的时候会根据后端设计器的视图信息，会在对应的位置生成一个DOM容器，这个容器会附上一个ID（对表单中每一个位置的自定义控件都唯一）
B.会根据自定义控件信息去加载js文件，加载完成后调用配置的入口方法 (js文件路径和入口方法都来自于配置信息)
C.调用入口方法会传入一个Object参数（三.3.自定义控件初始传入的数据解析）
D.开发者需要在入口方法后顺序执行的过程中去加载自己的css，js，并且渲染当前控件
E.自定义控件内部的各种事件，操作区域，打开文件等等，都由自定义控件内部开发代码完成
F.自定义控件需要回填其他标准控件，或者保存自己的数据，可以根据API提供的功能就行回填



## 三. 3.自定义控件初始传入的数据解析


## 3.1 入口方法传入的参数是Object数据类型，里面有5个属性



(自定义控件入口方法参数)(3.1图)

数据解析：
A.adaptation : 这个里面有提供的api，方法集合，可实现和表单页面数据之间的通信.
B.url_prefix : 这个是url前缀，可用于开发者加载css文件和js文件的路径前缀.
C.privateId : 这个是当前控件的在表单页面的唯一标识，可用于挂载控件DOM，也是调用部分API操作的必传参数，用于操作获取对应的值。
D.getData : 获取当前控件初始的所有数据




(D图，当前控件数据信息)

a. attachmentInfo : 附件信息 （里面包含附件列表和基础附件信息）
 b. attrs : 视图里面的简单控件信息
 c. auth: 权限 (‘edit’ : 编辑，’hide’: 隐藏)
 d. ctrlType : 视图里面的控件状态（这个，自定义控件的是"suiCustomControl"）
 e. customFieldInfo ： 自定义控件的信息，里面包含pc，移动的js信息和入口方法信息，路径信息。
 f. digitNum : 小数位长度
 g. display : 控件名
 h. enums : 控件的枚举列表
 i. extra ：设计器给控件设置的样式信息
 j. fieldLength ：控件内字符的限制长度
 k. fieldType ：字段类型
 l. formType ： 控件所在的表的类型
 m. formatType ： 数据格式
 n. Formdata ： 整个表单的信息
  n-1. Alldata ：整个表单的所有数据包括视图信息和用户信息，主表数据，明细表数据，多视图信息
  n-2. content ：表单的基础信息，包括表单数据ID，表单权限Id等等
  n-3. formdata ： 表数据
  n-4. formmains : 主表数据
  n-5. formsons : 明细表数据
  n-6. model : 表单中明细表是页签还是平铺（undefined是平铺，暂时其他是页签）
 o. id ：字段名
 p. inputType ：控件类型（标准控件判断）
 q. isInCalculate ： 是否计算（1为计算）
 r. isInCondition ： 是否是条件字段
 s. isNotNull ： 必填校验（1为必填）
 t. isCustomFiled : 是否是自定义控件（1是）
 u. placeHolder ： 提示语言
 v. radioAlignType ： 
 w. relation : 关联信息（控件公用的基础信息）
 x. relationData : 当前控件的关联数据 
 y. showValue ： 显示值
 z. value : 计算值
 aa. type : 类型
 ab. valueId : 值
E. formMessage : 当前控件在表的位置信息
 a. tableCategory : 主表还是明细表(formmain = ‘主表’,formson = ’明细表’)
 b. tableName : 所在表的表名


/**
  * 示例：
  * 
  * */
 {
   tableCategory : '',
   tableName : ''
 }



## 四. Api (依赖于(三)传入的adaptation属性，具体回填格式和数据请看下面详解)

API方法名                    说明            参数                 参数格式                   参数说明                                             详细介绍
childrenGetData           获取当前控件的数据     privatedId         String                 当前控件的唯一标识ID                                      (A)
childrenSetData           更新保存当前控件的数据   data，privatedId    Object, String         messageObj是获取的控件数据对象（更新到你维护的最新值），privaredId:     (B)
                                                                                  当前控件的唯一标识ID（入口方法传入)
ObserverEvent             用于事件发布订阅      属性方法               Function               扩展的属性方法                                          (C)
backfillFormControlData   用于回填控件数据      data, privatedId   Object/Array, string   payload: 回填的数据， privatedId 当前控件的唯一标识ID（入口方法传入）   (D)
backfillFormAttachment    用于回填附件数据      data, privatedId   Object/Array, string   payload: 回填的数据， privatedId 当前控件的唯一标识ID（入口方法传入）   (E)
callTakeFormSave          调用表单预提交方法     data, privatedId   Object, string         data 调用方法的参数， privatedId 当前控件的唯一标识ID（入口方法传入）     (F)

(A). childrenGetData (privateId)


/**
   * 示例：
   * 说明：此接口是用于获取当前的控件的即时数据。
   * 参数：privateId->（String）唯一标识
   * */
  adaptation.childrenGetData(privateId);


(B). childrenSetData (data, privateId)


/**
   * 示例：
   * 说明：此接口用于把自定义控件操作当前控件的数据回填到表单维护的当前控件数据中，建议取得数据对象，你就维护此对象，回填的时候传入此数据。
   * 参数：data->(Object)当前控件的数据
   *    privateId->（String）唯一标识
   * */
  adaptation.childrenSetData (data, privateId);


(C). ObserverEvent


/**
   * 示例：
   * 说明：发布订阅方法，有多个属性方法
   * 属性方法：
   *    one (key,  fn) : 处理一次
   *    remove (key,  fn) : 删除注册事件
   *  listen (key , fn) : 组册事件
   *    trigger () : 触发事件，第一个传入key，后面的传入需要传递的数据
   * 参数：
   *  key->(String) 事件名
   *    fn->(Function) 回调方法，里面可能有参数，看事件的约定
   * */
  adaptation.ObserverEvent.one('key', function(params) {});
  adaptation.ObserverEvent.remove('key', function() {});
  adaptation.ObserverEvent.listen('key', function(params) {});
  adaptation.ObserverEvent.trigger('key', params);


(D). backfillFormControlData(data, privateId)


/**
   * 示例：
   * 说明：此接口是用于自定义控件回填表单其他控件数据
   * 参数：data -> (Object || Array) 组织的回填的数据
   *         Object格式 :
   *     {
   *       tableName : (表名),
   *       tableCategory : (表类型(formmain || formson)),
   *      updateData : {
   *         filedName(表单对应控件名) ：{} (回填控件的数据对象)
   *       },
   *       updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有)
   *     }
   *       Array格式：
   *     [
   *       {
   *         tableName : (表名),
   *         tableCategory : (表类型(formmain || formson)),
   *         updateData : {
   *           filedName(表单对应控件名) ：{} (回填控件的数据对象)
   *         },
   *         updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有)
   *       }
   *     ]
   *      privateId->（String）唯一标识
   * 注意：
   *  1.回填是根据后端控件值格式
   *  2.回填输的数据对象里面有三个值很特殊 ：从入口方法获取的前端控件对象里面三个属性名是showValue, value, valueId.对应的回填对象里面格属性名是showValue，showValue2, value (非常重要)
   *  3. 2里面获取的前端控件数据对象里面的属性名和回填控件的数据对象属性名 showValue = showValue, value = showValue2, valueId = value  （非常重要）
   * */
   adaptation.backfillFormControlData (data, privateId);


(E). backfillFormAttachment(data, privateId)


/**
   * 示例：
   * 说明：此接口用于回填表单里面控件的附件
   * 参数：data -> (Object || Array) 组织的回填附件数据
   *       Object格式：
   *         {
   *           tableName : (表名),
   *           tableCategory : (表类型),
   *           updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有),
   *           handlerMode : (操作类型值：添加add和删除delete),
   *           fieldName : (表单回填的对应控件名),
   *           addAttchmentData : [{}], // 回填控件的附件信息列表，附件信息对象需要经过后端对应的格式生成
   *           deleteAttachmentData ：[] // 回填控件附件列表中要删除的对应Id数组
   *         }
   *       Array格式：
   *         [
   *           {
   *             tableName : (表名),
   *             tableCategory : (表类型),
   *             updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有),
   *             handlerMode : (操作类型值：添加add和删除delete),
   *             fieldName : (表单回填的对应控件名),
   *             addAttchmentData : [{}], // 回填控件的附件信息列表，附件信息对象需要经过后端对应的格式生成
   *             deleteAttachmentData ：[] // 回填控件附件列表中要删除的对应Id数组
   *           }
   *         ]
   *      privateId->（String）唯一标识
   * 注意：
   *  1.handlerMode属性有两个值必填其一
   *  2.handlerMode属性为‘add’ => 只会去读取addAttchmentData属性列表，所以必填
   *  3.handlerMode属性为‘delete’ => 只会去读取deleteAttachmentData属性数组，所以必填
   * 
   * 
   * */
  adaptation.backfillFormAttachment (data, privateId);


F. callTakeFormSave(data, privateId)


/**
   * 示例
   * 说明：此接口用于自定义控件调用预提交
   * 参数：data -> (Object) 参数对象
   *      {
   *        type: 'save', // 必填，值固定
   *        isPrev: true, // 必填，值固定
   *        callback ：(数据格式为Function), // 回调方法，有一个参数，参数格式为Object
   *        successFn ：(数据格式为Function), // v7.0 sp2-1130版本支持，正确预提交回调方法
   *        errorFn ：(数据格式为Function), // v7.0 sp2-1130版本支持，预提交失败，或者错误回调方法
   *      }
   *      privateId->（String）唯一标识
   * 
   * 注意：
   *  1.数据格式按规则填写
   *  2.只是预提交表单数据
   *  3.只是只支持这些
   * 
   * */
  adaptation.callTakeFormSave (data, privateId);



## 五. 表单触发的事件（依赖于adaptation.ObserverEvent）

监听事件名          说明              参数     参数格式     参数说明              详细介绍
Event + 唯一标识   用于监听是否数据更新      data   Object   返回的是表单中当前控件最新数据   (A)
Save + 唯一标识    通知自定义控件表单要保存了   无      无        无                 (B)

(A). Event + 唯一标识：用于告诉对应的自定义控件表单里面当前的数据更新了


/**
   * 示例：
   * 说明： 于告诉对应的自定义控件表单里面当前的数据更新了
   * 事件名： 字符串 'Event' + 入口方法传入的唯一标识privateId
   * 参数：data => (Object) 
   *         当前控件的控件数据对象
   * 
   * */
  adaptation.ObserverEvent.listen('Event' + privateId, function(data) {
    // 执行你的操作
  });


(B). Save + 唯一标识：用于告诉对应的自定义控件要保存了        (v7.0 sp2版本支持)


/**
   * 示例：
   * 说明：用于告诉对应的自定义控件当前表单要保存了
   * 事件名：字符串 'Save' + 入口方法传入的唯一标识privateId
   * 参数： privateId => (String) 唯一标识
   *        data => (Object)
   * */
  adaptation.ObserverEvent.listen('Save' + privateId, function(privateId, data) {
    // 执行你的操作
  });



## 六. 前端开发示例

下面是一个前端自定义控件开发示例 (按钮自定义控件)


/**
  * 说明： 是一个按钮类自定义控件的示例
  * */
 (function(factory){
  var nameSpace = 'field_5902128098173592526';
  if(!window[nameSpace]){
   var Builder = factory();
   window[nameSpace] = {
    instance: {}
   };
   window[nameSpace].init = function (options) {
    window[nameSpace].instance[options.privateId] = new Builder(options);
   };
   window[nameSpace].isNotNull = function (obj) {
    return true;
   };
  }
 })(function(){
  /**
  * 构造函数
  * @param options
  * @constructor
  */
  function App(options) {
   var self = this;
   //初始化参数
   self.initParams(options);
   //初始化dom
   self.initDom();
   //事件
   self.events();
  }
  
  App.prototype = {
   initParams : function (options) {
    var self = this;
    self.adaptation = options.adaptation;
    self.privateId = options.privateId;
    self.messageObj = options.getData;
    self.preUrl = options.url_prefix;
   },
   initDom : function () {
    var self = this;
    dynamicLoading.css(self.preUrl + 'css/formQueryBtn.css');
    self.appendChildDom();
   },
   events : function () {
    var self = this;
    // 监听是否数据刷新
    self.adaptation.ObserverEvent.listen('Event' + self.privateId, function() {
     self.messageObj = self.adaptation.childrenGetData(self.privateId);
     self.appendChildDom();
    });
   },
   appendChildDom : function () {
    var self = this;
    var domStructure = '<section class="customButton_box_content">'+
     '<div class="customButton_class_box '+ self.privateId + '" title="' + self.messageObj.display.escapeHTML() + '">'+ self.messageObj.display.escapeHTML() +'</div>'+
     '</section>';
    document.querySelector('#' + self.privateId).innerHTML = domStructure;
    var jumpFun = function() {
     // 事件执行
    };
    document.querySelector('.' + self.privateId).removeEventListener('click',jumpFun);
    document.querySelector('.' + self.privateId).addEventListener('click',jumpFun);
    //渲染隐藏权限
    if (self.messageObj.auth === 'hide') {
     document.querySelector('#' + self.privateId).innerHTML = '<div class="cap4-text__browse" style="line-height: 1.8; color: rgb(0, 0, 0) !important;">***</div>';
    }
   },
   dealCdtMapping : function (opt) {
    $.ajax({
     url: '/seeyon/rest/cap4/formquerybtn/dealCdtMapping?formId=' + opt.formId + '&fieldName=' + opt.fieldName + '&formDataId=' + opt.formDataId + '&formSubDataId=' + opt.formSubDataId + '&designId=' + opt.designId,
     success: function (data) {
      if(opt.callback && typeof opt.callback === 'function')
       opt.callback.apply();
     },
     error: function (e) {
      if(e.message){
       top.$.error(e.message);
      }else{
       top.$.error('处理筛查条件出错...');
      }
     }
    });
   }
  };

  var dynamicLoading = {
   css: function(path) {
    if(!path || path.length === 0) {
     throw new Error('argument "path" is required !');
    }
    var head = document.getElementsByTagName('head')[0];
    var link = document.createElement('link');
    link.href = path;
    link.rel = 'stylesheet';
    link.type = 'text/css';
    head.appendChild(link);
   },
   js: function(path) {
    if(!path || path.length === 0) {
     throw new Error('argument "path" is required !');
    }
    var head = document.getElementsByTagName('head')[0];
    var script = document.createElement('script');
    script.src = path;
    script.type = 'text/javascript';
    head.appendChild(script);
   }
  }

  return App;
 });



## 七. 自定义控件调试环境和与表单的交互

1.协同开发环境.
2.我们会持续维护表单和自定义控件之间的交互api，如有特殊情况可以联系后讨论处理方案



## 八．常见的错误

1.this的指向问题
2.同一个表单里面可能具有多个相同的自定义控件
 1) 需要当前控件防污染处理
3.兼容
 1) 因为兼容IE（定义变量使用var （不建议let ， const）， 不建议ES5以上标准的js书写代码）
 2) 也可以是最终运行的代码是编译成ES5标准的（例如使用：babel-polyfill）
4.事件初始化
 1) 初始化方法调用后要对原有注册的方法进行销毁处理，并重新注册
5.数据陈旧
 1) 没有监听（五-A）的监听方法，去更新当前控件里面的数据
 2) 如果没有第一步，新操作的时候也没有去取新的数据
 3) 如果没有第一步，页面数据变化了自定义控件没有刷新渲染，出现了运行态和预期不一致


----------------------------------------

End

编撰人：yinyanting




快速跳转



 * cap4自定义控件-PC端
   * 自定义控件介绍
   * 一.开发规范
     * 1.1 自定义控件文档结构
     * 1.2 自定义控件基础规范
     * 1.3 自定义控件存在生命周期
   * 二. 自定义控件实现和交互规范
   * 三. 3.自定义控件初始传入的数据解析
     * 3.1 入口方法传入的参数是Object数据类型，里面有5个属性
   * 四. Api (依赖于(三)传入的adaptation属性，具体回填格式和数据请看下面详解)
   * 五. 表单触发的事件（依赖于adaptation.ObserverEvent）
   * 六. 前端开发示例
   * 七. 自定义控件调试环境和与表单的交互
   * 八．常见的错误



分享链接分享链接

## 9. CAP4自定义控件后端规范

> 原始路径：`/94/355/359/373/377.html`  
> 相对路径：`94/355/359/373/377.md`  
> JS Chunk：`app.371b709c.js`

## CAP4自定义控件后端规范


## 1、自定义控件定义

在CAP4表单中，除了致远提供的标准功能控件外，第三方开发可以通过自定义控件方案实现第三方的控件，这类控件我们统称自定义控件。


## 2、自定义控件设计方案


## 2.1 总体设计方案

自定义控件由第三方开发，开发好之后上传致远商城，V5客户的应用设计师登录V5之后，在CAP4表单制作页面左侧会有自定义控件管理页面，V5客户可以在扩展控件列表页面从商城下载第三方开发的控件到V5安装环境中进行使用，模式如下图：





备注：V5用户下载自定义控件只是将控件的包下载到了V5环境的共享目录中，在下次重启的时候才会将自定义控件包解压进行自动部署。所以自定义控件下载之后需要重启生效。

## 2.1.1 插件/component开发说明

第三方开发的自定义控件对于V5来说其实是一个插件或者component（plugin，致远内部开发自定义控件可以不用单独创建插件，相关配置可以放到控件相关功能的插件配置中），开发自定义控件将严格接受V5插件开发规范。 （更多V5插件开发请见http://open.seeyon.com/book/ctp/sdk/ctpbackendspec.html#插件化）

## 2.1.2 自定义控件项目目录结构说明

开发自定义控件第一步自然是创建项目，创建项目之后目录结构可以参照以下示例创建各目录，以下目录结构是一个自定义控件的示例（下载完整目录结构）。

─seeyon      固定目录不可修改
├─apps_res     固定目录不可修改
│  └─cap     固定目录不可修改
│  └─customCtrlResources   固定目录不可修改（存放PC端前端资源的目录）
│  └─testCtrlResource
│  │  test.png
│  │
│  ├─html
│  │  param1Setter.html
│  │  param2Setter.html
│  │
│  └─js
├─m3files     固定目录不可修改（存放M3移动端自定义资源包的目录）
│  └─v5      固定目录不可修改
│  3423424234234234234.zip
│
└─WEB-INF     固定目录不可修改
├─cfgHome     固定目录不可修改
│  └─plugin     固定目录不可修改
│  └─testCtrlPlugin
│  │  pluginCfg.xml
│  │
│  ├─i18n
│  │  export_to_js.xml
│  │  test_en.properties
│  │  test_zh_CN.properties
│  │  test_zh_TW.properties
│  │
│  └─spring
│    spring-test-manager.xml
│    spring-test-controller.xml
│
├─classes
│  └─com
│  └─seeyon
│  └─cap4
│  └─form
│  └─bean
│  └─fieldCtrl
│  TestCtrl.class
│
├─jsp     固定目录不可修改
└─lib     固定目录不可修改


## 2.1.3 如何让CAP4表单编辑器中出现你的自定义控件

 * 按照以上示例中的目录结构创建自定义控件项目工程
 * 创建一个java类文件，实现自定义控件抽象类com.seeyon.cap4.form.bean.fieldCtrl.FormFieldCustomCtrl
 * 实现或者重写FormFieldCustomCtrl中的接口，示例（电子发票控件实现类）：

`

private static final Log LOGGER = CtpLogFactory.getLog(FormEinvoiceCtrl.class);

/**
  * 返回自定义控件唯一的key，控件key可以使用平台www.seeyon.com.utils.UUIDUtil.getUUIDString()接口 生成一个uuid，将此Id作为控件的key
  * @return
  */
@Override
public String getKey() {
    return "4578843378267869145";
}

/**
  * 获取控件名称
  * @return
  */
@Override
public String getText() {
    return ResourceUtil.getString("com.cap.ctrl.einvoice.text");
}

/**
 * 定义此自定义控件是否支持批量刷新
 *
 * @return
 */
@Override
public boolean canBathUpdate() {
    return false;
}
/**
 * 此控件是否是附件类控件
 *
 * @return
 */
@Override
public boolean isAttachment() {
    return true;
}

/**
 * 新建的时候生成此自定义控件的值，此值会存放在对应动态表的对应字段上，一般情况下只有需要上传附件类的自定义控件才需要此接口。
 *
 * @param oldVal
 * @return
 */
@Override
public Object genVal(Object oldVal) {
    if (StringUtil.checkNull(String.valueOf(oldVal))) {
        return UUIDLong.longUUID();
    } else {
        return oldVal;
    }
}

@Override
public List<String[]> getListShowDefaultVal(Integer integer) {
    return null;
}

/**
 * 初始值生成接口
 */
@Override
public String[] getDefaultVal(String s) {
    return new String[0];
}

/**
 * 控件初始化接口，此接口在控件初始化的时候，会调用，主要用于定义控件所属插件id、在表单编辑器中的图标、表单编辑器中有哪些属性可以设置。
 * 使用举例：在接口中定义自定义控件在在表单编辑器中有哪些控件属性需要配置
 */
@Override
public void init() {
    this.setPluginId("formInvoiceBtn");//控件所属插件id
    this.setIcon("cap-icon-e-invoice");//控件在表单编辑器中的图标
    LOGGER.info("自定义控件" + this.getText() + "init执行开始");
    ParamDefinition eivoiceDef = new ParamDefinition();//控件属性设置定义对象
    eivoiceDef.setDialogUrl("apps_res/cap/customCtrlResources/formEinvoiceCtrlResources/html/EinvoiceSetting.html");//控件属性点击之后弹出的设置对话框的url
    eivoiceDef.setDisplay("com.cap.ctrl.einvoice.paramtext");//如果要做国际化 这个地方只能存key
    eivoiceDef.setName("mapping");//控件属性名
    eivoiceDef.setParamType(Enums.ParamType.button);//控件属性类型
    addDefinition(eivoiceDef);
    LOGGER.info("自定义控件" + this.getText() + "init执行结束，params.size:" + super.params.size());
}

/**
 * 定义PC端自定义控件运行态资源注入信息
 * path:文件夹路径
 * jsUri:定义PC端表单运行态加载第三方JavaScript的路径
 * cssUri：定义PC端表单运行态加载第三方CSS的路径
 * initMethod:定义PC端表单运行态第三方js入口方法名称
 * nameSpace：此自定义控件前端运行时的命名空间，可以参照一下写法来定义命名空间
 * @return
 */
@Override
public String getPCInjectionInfo() {
    return "{path:'apps_res/cap/customCtrlResources/formEinvoiceCtrlResources/',jsUri:'js/formEinvoicePcRuning.js',initMethod:'init',nameSpace:'field_" + this.getKey() + "'}";
}

/**
 * 获取移动端自定义控件运行态资源注入信息
 * path：'http://'+m3应用包mainifest.json中的urlSchemes的值+'v'+m3应用包mainifest.json中的version的值
 * weixinpath: 微信端打开的时候使用的m3/apps/v5/自定义控件移动端资源目录名称/,weixinpath配置的就是此自定义控件移动端资源目录名称
 * jsUri:移动端表单运行态加载第三方JavaScript的路径
 * initMethod:定义M3端表单运行态第三方js入口方法名称
 * * nameSpace:定义M3端表单运行态命名空间
 *
 * @return
 */
@Override
public String getMBInjectionInfo() {
    return "{path:'http://einvoice.v5.cmp/v1.0.0/',weixinpath:'invoice',jsUri:'js/formEinvoiceMbRuning.js',initMethod:'init',nameSpace:'field_"+this.getKey()+"'}";

}
/**
 * 定义控件对应数据库所需长度
 * 注意：一旦自定义控件长度定好，上线部署到OA环境中之后，
 * 此接口返回的长度不允许改变，因为上线之后如果有表单使用
 * 了此自定义控件，就会在数据库中创建字段长度为此指定长度
 * 的数据列。
 *
 * @return
 */
@Override
public String getFieldLength() {
    return "25";
}

/**
 * 是否支持套红，自定义控件默认false，如果支持需要重新接口返回true
 *
 * @return
 */
@Override
public boolean canInjectionWord() {
    return false;
}


## 2.1.4 如何让CAP4报表查询配置中出现你的自定义控件

 * 实现或者重写FormFieldCustomCtrl中的接口中的canShowInReport；
 * 实现或者重写FormFieldCustomCtrl中的接口中的convertCtrlValue；
 * 实现或者重写FormFieldCustomCtrl中的接口中的getRenderInfo4Run

@Override
public FormFieldCustomCtrlReportInfo canShowInReport() {
 FormFieldCustomCtrlReportInfo reportInfo = new FormFieldCustomCtrlReportInfo();
 reportInfo.setEnableQuery(true);
 reportInfo.setEnableDisplayField(true);
 reportInfo.setEnableSort(true);
 reportInfo.setEnableFilterField(true);
 return reportInfo;
}

@Override
public Object convertCtrlValue(FormFieldBean fieldBean, Object value) {
 return MapUtils.getString(JSONUtil.parseJSONString((String) value, Map.class), "projectName");
}

@Override
public FormFieldCustomCtrlRunInfo getRenderInfo4Run() {
 FormFieldCustomCtrlRunInfo runInfo = new FormFieldCustomCtrlRunInfo();
 // PC列表
 FormFieldCustomCtrlInjectInfo pcList = new FormFieldCustomCtrlInjectInfo();
 pcList.setPath("apps_res/cap/customCtrlResources/projectRelatedResources/");
 pcList.setNameSpace(getListNameSpace());
 pcList.setJsUri("js/projectRelatedPCList.umd.min.js");
 runInfo.setPcList(pcList);

 // PC普通筛选
 FormFieldCustomCtrlInjectInfo pcFilter = new FormFieldCustomCtrlInjectInfo();
 pcFilter.setPath("apps_res/cap/customCtrlResources/projectRelatedResources/");
 pcFilter.setNameSpace(getFilterNameSpace());
 pcFilter.setJsUri("js/projectRelatedPCFilter.umd.min.js");
 runInfo.setPcFilter(pcFilter);

 // 移动端列表
 FormFieldCustomCtrlInjectInfo mList = new FormFieldCustomCtrlInjectInfo();
 mList.setPath("http://customCtrlResources.v5.cmp/v1.0.0/");
 mList.setWeixinPath("customCtrlResources");
 mList.setNameSpace(getListNameSpace());
 mList.setJsUri("projectRelatedResources/js/projectRelatedMList.umd.min.js");
 runInfo.setMobileList(mList);

 // 移动端普通筛选
 FormFieldCustomCtrlInjectInfo mFilter = new FormFieldCustomCtrlInjectInfo();
 mFilter.setPath("http://customCtrlResources.v5.cmp/v1.0.0/");
 mFilter.setWeixinPath("customCtrlResources");
 mFilter.setNameSpace(getFilterNameSpace());
 mFilter.setJsUri("projectRelatedResources/js/projectRelatedMFilter.umd.min.js");
 runInfo.setMobileFilter(mFilter);

 return runInfo;
}

/**
 * 获取列表区作用域
 *
 * @return
 */
private String getListNameSpace() {
 return getNameSpace("List");
}

/**
 * 获取条件区作用域
 *
 * @return
 */
private String getFilterNameSpace() {
 return getNameSpace("Filter");
}

/**
 * 获取全局命名空间
 *
 * @param uniqueKey
 * @return
 */
protected String getNameSpace(String uniqueKey) {
 return StringUtils.uncapitalize(getClass().getSimpleName()) + uniqueKey + getKey();
}


## 2.1.5 在spring配置文件中配置自定义控件Java类

控件实现类创建好之后需要在spring配置文件中将此类配置一下，由spring管理此类，具体做法是在你的项目中创建如2.1.2中的spring目录和目录下的文件spring-xxx-manager.xml(xxx由第三方自己定义)，编辑此xml文件，按照spring规范定义此bean对象即可，例如电子发票控件的spring配置：

<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
   xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation="http://www.springframework.org/schema/beans http://www.springframework.org/schema/beans/spring-beans.xsd http://www.springframework.org/schema/aop http://www.springframework.org/schema/aop/spring-aop.xsd" default-autowire="byName">
<bean id="formInvoiceBtnCtrl" class="com.seeyon.cap4.form.bean.fieldCtrl.FormEinvoiceCtrl"></bean>
</beans>



## 2.2 自定义控件属性设置开发


## 2.2.1 定义自定义控件有哪些属性

自定义控件在表单编辑器中，需要由开发控件的人自己定义控件有哪些属性，属性由com.seeyon.cap4.form.bean.ParamDefinition进行描述，需要在自定义控件实现类的init方法中进行属性的定义和添加，属性设置分两种表现形式，此处着重描述按钮类型的属性怎么定义： 在自定义控件的init方法中new出一个ParamDefinition类型的对象，调用对象的setDialogUrl方法设置按钮点击之后弹出框的url（如果类型是按钮类的才需要），调用对象的setDisplay方法设置按钮显示的名称，调用setParamType设置属性类型（类型由枚举com.seeyon.cap4.form.util.Enums.ParamType进行描述，button：按钮类型，text文本框类型），最后调用addDefinition将new出来的对象添加到自定义控件属性列表中，示例代码：

ParamDefinition eivoiceDef = new ParamDefinition();
    eivoiceDef.setDialogUrl("apps_res/cap/customCtrlResources/formEinvoiceCtrlResources/html/EinvoiceSetting.html");
    eivoiceDef.setDisplay("com.cap.ctrl.einvoice.paramtext");//如果要做国际化 这个地方只能存key
    eivoiceDef.setName("mapping");
    eivoiceDef.setParamType(Enums.ParamType.button);
    addDefinition(eivoiceDef);



## 2.2.2 如何开发自定义控件属性设置页面

如果是弹出框类型的属性，需要开发弹出框所需的页面，在页面中定义一个名称为ok的js方法，此方法返回点击确定之后所需要保存的设置信息，在表单编辑器保存表单定义的时候，CAP会将自定义控件属性的定义信息保存到cap_form_definition表的field_info对应字段的customParam属性中，field_info是json格式。

function OK(){
    var mapping = [];
    var settings = $("#systemMappingArea").find(".biz_groupguanlian");
    var checkTag = true;
    for(var i=0;i<settings.length;i++){
        var setting = $(settings[i]);
        var temp = {};
        var einvoicefield = setting.find(".leftField").find("option:selected").attr("fieldtype");
        var fieldname = setting.find(".rightField").find("option:selected").attr("fieldname");
        if(einvoicefield===undefined||fieldname===undefined){
            top.$.alert("选项不能为空！");
            checkTag = false;
            break;
        }
        temp.source = einvoicefield;
        temp.target = fieldname;
        mapping.push(temp);
    }
    if(checkTag){
        var hasSame = false;
        var sameFieldName = "";
        //校验所选是否满足规则
        //先校验右侧同一个数据域是否出现多次
        for(var j=0;j<mapping.length;j++){
            var current1 = mapping[j];
            for(var k=0;k<mapping.length;k++){
                var current2 = mapping[k];
                if(current1.source!=current2.source && current1.target===current2.target){
                    hasSame = true;
                    sameFieldName = current1.target;
                    break;
                }
            }
            if(hasSame){
                break;
            }
        }
        //再校验左右是否类型匹配
        if(hasSame){
            checkTag = false;
            var sameField = getFieldInfoByCurrentField(initObj.currentfield.name,sameFieldName);
            top.$.alert(sameField.display+"[右侧数据域]出现多次!");
        }else{
            var errorMsg = "";
            var formId = initObj.formBaseInfo.formBaseInfo.formInfo.id;
            $.ajax({ url: "/seeyon/rest/cap4/formEinvoice/checkMapping",
                async:false,
                type: 'POST',
                dataType:'json',
                contentType : 'application/json;charset=UTF-8',
                data: JSON.stringify({"formId":formId,"datas":mapping}),
                success: function(data){
                    if(data.data.result=="true"){
                        checkTag = true;
                    }else{
                        checkTag = false;
                        errorMsg = data.data.errorMsg;
                    }
                }
            });
            if(!checkTag){
                top.$.alert(errorMsg);
            }
        }
    }
    return  {valid:checkTag,data:mapping};
}


表单保存之后数据库cap_form_definition中field_info字段截图：

![[custom-custom-serverside-4.98fdbe5.png|custom-custom-serverside-4.98fdbe5.png]]

 * 显示为一个按钮，点击之后是弹出框形式，如图：
 * ![[custom-custom-serverside-3.366f799.png|custom-custom-serverside-3.366f799.png]]
 * 显示为一个文本框


## 2.2.2 自定义控件前端运行态渲染开发

CAP4表单自定义控件前端渲染分为PC端和移动端（M3或者微协同统称移动端），CAP4平台会将您渲染自定义控件的js文件动态注入到页面中。您需要通过2.1.3中所描述的getPCInjectionInfo和getMBInjectionInfo接口来分别定义您自定义控件在PC和移动端渲染的js路径。表单在运行态调用的时候，会主动调用您js文件中的初始化方法，您需要在初始化方法中实现您自定义控件的渲染以及事件绑定等操作。如下为表单电子发票控件的PC端js文件代码：

(function (ctx,factory) {
    var nameSpace = 'field_4578843378267869145';
    if(!window[nameSpace]){
        var Builder = factory(ctx,nameSpace);
        window[nameSpace] = {
            instance: {}
        };
        window[nameSpace].init = function (options) {
            window[nameSpace].instance[options.privateId] = new Builder(options);
    };
    }
})(typeof $ === 'undefined' ? top.$ : $,function($,domain){

    function App(options) {
        var self = this;
        self.appendChildDom = function (adaptation, messageObj, privateId, getData) {
            self.customButton(adaptation, messageObj, privateId, getData);
        };
        self.customButton = function (adaptation, messageObj, privateId, getData) {

            if (adaptation) {
                self.adaptation = adaptation;
            }
            //----------创建DOM---------
            var domStructure = '';
            var box = document.querySelector('#' + privateId);
            if(!box) {
                console.warn('未找到控件dom');
                return;
            }
            if (getData.auth === 'browse') {
                domStructure = '<section class="cap4-images is-one "><div><div class="cap4-images__cnt" style="border:none;"><div class="cap4-images__items"><div class="cap4-images__holder"></div></div></div></div></section>';
            }else if (getData.auth === 'hide') {
                box.style.display="none";
                return;
            }else {
                domStructure = '<section class="cap4-images is-one "><div><div class="cap4-images__cnt"><div class="cap4-images__items"><div class="cap4-images__holder"></div></div><div class="cap4-images__picker upload ' + privateId + '"><div class="icon CAP cap-icon-e-invoice"></div></div></div></div></section>';
            };
            box.innerHTML = domStructure;
            if (self.getData.attachmentInfo.attachmentInfos && self.getData.attachmentInfo.attachmentInfos.length > 0) {
                var filename=encodeURIComponent(self.getData.attachmentInfo.attachmentInfos[0].filename);
                if (getData.auth === 'browse') {
                    box.querySelector(".cap4-images__items").innerHTML = '<div style="cap4-images__it"><a style="display: block;max-height: 20px;" target="myFormIframe" href="/seeyon/fileDownload.do?method=download&fileId=' + self.getData.attachmentInfo.attachmentInfos[0].fileUrl + '&v=' + self.getData.attachmentInfo.attachmentInfos[0].v + '&createDate=' + self.getData.attachmentInfo.attachmentInfos[0].createdate + '&filename=' +filename + '"title="' + filename + '">'+self.getData.attachmentInfo.attachmentInfos[0].filename + '</a></div>';
                } else {
                    box.querySelector(".cap4-images__items").innerHTML = '<div style="cap4-images__it"><a style="display: block;max-height: 20px;" target="myFormIframe" href="/seeyon/fileDownload.do?method=download&fileId=' + self.getData.attachmentInfo.attachmentInfos[0].fileUrl + '&v=' + self.getData.attachmentInfo.attachmentInfos[0].v + '&createDate=' + self.getData.attachmentInfo.attachmentInfos[0].createdate + '&filename=' +filename + '"title="' + filename + '">' +self.getData.attachmentInfo.attachmentInfos[0].filename + '</a><div class="cap4-images__close"><i class="icon CAP cap-icon-guanbi delete"></i></div></div>';
                }
                box.querySelector('.upload') && (box.querySelector('.upload').style.display = "none");
                if (box.querySelector('.delete')) {
                    box.querySelector('.delete').addEventListener('click', function () {
                        var field = box.querySelector(".cap4-images__items");
                        field.removeChild(field.childNodes[0]);
                        box.querySelector('.upload') && (box.querySelector('.upload').style.display = "");
                        self.aId = self.getData.attachmentInfo.attachmentInfos[0].id;
                        if (self.adaptation.backfillFormAttachment) {
                            var attachmentData = [
                                {
                                    tableName: self.formMessage.tableName,
                                    tableCategory: self.formMessage.tableCategory,
                                    updateRecordId: self.getData.recordId || '',
                                    handlerMode: 'delete',
                                    fieldName: self.getData.id,
                                    deleteAttchmentData: [self.aId]
                                }
                            ];
                            self.adaptation.backfillFormAttachment(JSON.parse(JSON.stringify(attachmentData)), privateId);
                }
                    });
                }
            }else{
                if (getData.auth === 'edit'){
                    box.querySelector(".cap4-images__cnt").style.background=(messageObj.isNotNull=='1'?'#fef0d0':'');
                }
            }
            if (document.querySelector('.' + privateId)) {
                document.querySelector('.' + privateId).addEventListener('click', function () {
                    if(self.messageObj.customFieldInfo.customParam==null){
                        top.$.alert("请联系应用设计师，在表单编辑器中设置电子发票控件的属性映射！");
                        return;
                    }
                    var opts = {
                        type: 0,
                        applicationCategory: 66,
                        maxSize: '',
                        isEncrypt: '',
                        popupTitleKey: '',
                        attachmentTrId: 'Att',
                        takeOver: 'false',
                        firstSave: 'true',
                        quantity: 1,
                        extensions: 'pdf'
                    };
                    //文件上传成功后
                    self.uploadFile(opts, function (fileurls, atts) {
                        if (atts && atts.length > 0) {
                            var att = atts;
                            att[0].refefence = self.getData.attachmentInfo.baseAttachmentInfo.reference;
                            att[0].subReference = self.getData.attachmentInfo.baseAttachmentInfo.subReference;
                            self.att = att;
                            box.querySelector(".cap4-images__items").innerHTML = '<div style="cap4-images__it"><a title="'+atts[0].filename+'" style="display: block;max-height: 20px;" target="myFormIframe" href="/seeyon/fileDownload.do?method=download&fileId='+self.att[0].fileUrl+'&v='+self.att[0].v+'&createDate='+self.att[0].createDate+'&filename='+encodeURIComponent(self.att[0].filename)+'">'+atts[0].filename+'</a><div class="cap4-images__close"><i class="icon CAP cap-icon-guanbi delete"></i></div></div>';
                            //icon botton
                            box.querySelector(".cap4-images__cnt").style.background='';
                            box.querySelector('.upload').style.display = "none";
                            self.aId = atts[0].id;
                            box.querySelector('.delete').addEventListener('click', function () {
                                var field = box.querySelector(".cap4-images__items");
                                field.removeChild(field.childNodes[0]);
                                box.querySelector('.upload').style.display = "";
                                box.querySelector(".cap4-images__cnt").style.background=(messageObj.isNotNull=='1'?'#fef0d0':'');
                                if (self.adaptation.backfillFormAttachment) {
                                    var attachmentData = [
                                        {
                                            tableName: self.formMessage.tableName,
                                            tableCategory: self.formMessage.tableCategory,
                                            updateRecordId: self.getData.recordId || '',
                                            handlerMode: 'delete',
                                            fieldName: self.getData.id,
                                            deleteAttchmentData: [self.aId]
                                        }
                                    ];
                                    //backfillFormAttachment（向数据库删除需要删除的内容）
                                    self.adaptation.backfillFormAttachment(JSON.parse(JSON.stringify(attachmentData)),privateId);
                                }
                            });
                            //rest
                            var content = self.messageObj.formdata.content;
                            var params = {
                                formId: content.contentTemplateId,
                                rightId: content.rightId,
                                fieldName: getData.id,
                                fileId: atts[0].fileUrl,
                                masterId: content.contentDataId,
                                subId: getData.recordId || '0'
                            };
                            var process = top.$.progressBar({
                                text: "解析中"
                            });
                            $.ajax({
                                type: 'get',
                                url: (_ctxPath ? _ctxPath : '/seeyon') + "/rest/cap4/formEinvoice/parseEinvoiceFileAndFillBack?" + self.parseParam(params),
                                dataType: 'json',
                                contentType: 'application/json',
                                beforeSend: function () {

                                },
                                success: function (res) {
                                    process.close();
                                    if (res.success || res.code == "0") {
                                        if (self.adaptation.backfillFormControlData) {
                                            var backfillData = [];
                                            var backfillItem = {
                                                tableName: self.formMessage.tableName,
                                                tableCategory: self.formMessage.tableCategory,
                                                updateData: {},
                                                updateRecordId: ''
                                            }
                                            if (self.countProperties(res.data) === 0) {
                                                return;
                                            } else {
                                                var key = [];
                                                for (var k in res.data) {
                                                    if (k.split('_').length > 1) {
                                                        key.push(k.split('_')[1]);
                                                    }
                                                }

                                                if (key.length == 0) {
                                                    backfillItem.updateData = res.data;
                                                    backfillData.push(backfillItem);
                                                } else {
                                                    if (self.removal(key).length === 1) {
                                                        if (self.countProperties(res.data) === key.length) {
                                                            backfillItem.updateData = res.data;
                                                            backfillItem.updateRecordId = key[0];
                                                            backfillData.push(backfillItem);
                                                        } else {
                                                            var mTable = {};
                                                            var sTable = {};
                                                            for (p in res.data) {
                                                                if (p.split('_').length === 2 && p.split('_')[1] === key[0]) {
                                                                    sTable[p] = res.data[p];
                                                                } else {
                                                                    mTable[p] = res.data[p];
                                                                }
                                                            }
                                                            backfillData.push({
                                                                updateData: mTable,
                                                                tableName: self.formMessage.tableName,
                                                                tableCategory: self.formMessage.tableCategory,
                                                            });
                                                            backfillData.push({
                                                                updateData: sTable,
                                                                tableName: self.formMessage.tableName,
                                                                tableCategory: self.formMessage.tableCategory,
                                                                updateRecordId: key[0]
                                                            });
                                                        }
                                                    } else {
                                                        var len = removal(key);

                                                        for (var i = 0; i <= len.length; i++) {
                                                            var tableData = {};
                                                            for (p in res.data) {
                                                                if (p.split('_').length === 2) {
                                                                    if (p.split('_')[1] === len[i]) {
                                                                        tableData[p] = res.data[p];
                                                                    }
                                                                } else {
                                                                    if (i === len.length) {
                                                                        tableData[p] = res.data[p];
                                                                    }
                                                                }
                                                            }
                                                            backfillData.push({
                                                                updateData: tableData,
                                                                tableName: self.formMessage.tableName,
                                                                tableCategory: self.formMessage.tableCategory,
                                                                updateRecordId: len[i] || ''
                                                            });
                                                        }
                                                    }
                                                }
                                            }
                                            if (backfillData && backfillData.length > 0) {
                                                for (var i = 0; i < backfillData.length; i++) {
                                                    for (var k in backfillData[i].updateData) {
                                                        if (k.split('_').length > 1) {
                                                            backfillData[i].updateData[k.split('_')[0]] = backfillData[i].updateData[k];
                                                            delete backfillData[i].updateData[k];
                                                        } else {
                                                            backfillData[i].updateData[k] = backfillData[i].updateData[k];
                                                        }
                                                    }
                                                }
                                            }
                                            //backfillFormControlData（回填电子发票相关联的其它控件的值）
                                            self.adaptation.backfillFormControlData(backfillData, privateId);
                                        }
                                        if (self.adaptation.backfillFormAttachment) {
                                            var attachmentData = [
                                                {
                                                    tableName: self.formMessage.tableName,
                                                    tableCategory: self.formMessage.tableCategory,
                                                    updateRecordId: self.getData.recordId || '',
                                                    handlerMode: 'add',
                                                    fieldName: self.getData.id,
                                                    addAttchmentData: self.att
                                                }
                                            ]
                                            //backfillFormAttachment（向数据库添加新建的内容）
                                            self.adaptation.backfillFormAttachment(JSON.parse(JSON.stringify(attachmentData)), privateId);
                                        }
                                    } else {
                                    }
                                },
                                complete: function () {
                                    process.close();
                                },
                                error:function (errorMsg) {
                                    var retObj = $.parseJSON(errorMsg.responseText);
                                    top.$.alert(retObj.message);
                                    process.close();
                                }
                            });
                        }

                    });
                });
            }
        }
        self.download = function () {

        }
        self.removal = function (arr) {
            var res = [];
            var json = {};
            for (var i = 0; i < arr.length; i++) {
                if (!json[arr[i]]) {
                    res.push(arr[i]);
                    json[arr[i]] = 1;
                }
            }
            return res;
        }

        self.countProperties = function (obj) {
            var count = 0;
            for (var property in obj) {
                if (Object.prototype.hasOwnProperty.call(obj, property)) {
                    count++;
                }
            }
            return count;
        }
        //定义上传文件接口
        self.uploadFile = function (options, callback) {
            self.parseParam = function (param, key) {
                var paramStr = "";
                if (param instanceof String || param instanceof Number || param instanceof Boolean) {
                    paramStr += "&" + key + "=" + encodeURIComponent(param);
                } else {
                    $.each(param, function (i) {
                        var k = key == null ? i : key + (param instanceof Array ? "[" + i + "]" : "." + i);
                        paramStr += '&' + self.parseParam(this, k);
                    });
                }
                return paramStr.substr(1);
            }

            options.CSRFTOKEN = top.CsrfGuard.getToken();
            var url = (_ctxPath ? _ctxPath : '/seeyon') + '/fileUpload.do?callMethod=_dinvoiceUploadFileCallback&' + self.parseParam(options);
            getCtpTop().addattachDialog = null;
            getCtpTop().addattachDialog = getCtpTop().$.dialog({
                title: $.i18n('fileupload.page.title'),
                transParams: {
                    parentWin: window
                },
                url: url,
                width: 400,
                height: 250
            });

            window._dinvoiceUploadFileCallback = function (att, repeat) {
                var atts = null;
                atts = att;

                if (atts && atts.instance.length) {
                    //处理一下返回的数据，拼接一下url，统一修改
                    atts.instance.forEach(function (item) {
                        var opts = {
                            createDate: item.createDate.split(' ')[0],
                            fileId: item.fileUrl
                        };
                        var url = (_ctxPath ? _ctxPath : '/seeyon') + '/fileUpload.do?method=showRTE&type=image&showType=big&' + self.parseParam(opts);
                        item.src = url; //增加src属性，写入url
                    });
                    callback(null, atts.instance);
                } else {
                    callback(null, []);
                }
            }
        }
        self.initParams(options);
    }

    App.prototype.initParams = function (res) {
        var self = this;
        var adaptation = res.adaptation;
        var url_prefix = res.url_prefix;
        var privateId = res.privateId;
        self.formMessage = res.formMessage;
        self.getData = res.getData;
        var dataObj = adaptation.childrenGetPrivateMessage(privateId);
        self.messageObj = adaptation.childrenGetData(privateId);
        self.appendChildDom(adaptation, self.messageObj, privateId, res.getData);

        // 监听是否数据刷新
        adaptation.ObserverEvent.listen('Event' + privateId, function () {
            //self.messageObj = adaptation.childrenGetData(privateId);
            //self.appendChildDom(adaptation, self.messageObj, privateId);
        });
    };
    return App;
});


![[custom-custom-serverside-5.542f425.png|custom-custom-serverside-5.542f425.png]]

更多运行态相关说明请见：自定义控件-前端


## 2.2.3 自定义控件在CAP4报表查询中有哪些属性

自定义控件在CAP4报表查询中，需要由开发控件的人自己定义控件有哪些属性，属性由com.seeyon.cap4.form.bean.fieldCtrl.FormFieldCustomCtrlReportInfo进行描述，需要在自定义控件实现类的canShowInReport方法中进行属性的定义和添加，具体属性设置如下表：

属性名                  说明
enableQuery          是否在查询中使用，如果为false的话不在查询中显示
enableDisplayField   是否支持数据字段设置
enableFormulaField   是否支持公式列
enableSort           是否支持排序设置
enableFilterField    是否支持筛选条件-普通条件

以关联项目自定义控件为例：

@Override
public FormFieldCustomCtrlReportInfo canShowInReport() {
 FormFieldCustomCtrlReportInfo reportInfo = new FormFieldCustomCtrlReportInfo();
 reportInfo.setEnableQuery(true);
 reportInfo.setEnableDisplayField(true);
 reportInfo.setEnableSort(true);
 reportInfo.setEnableFilterField(true);
 return reportInfo;
}


我们在查询配置中数据字段设置/筛选条件设置，就可以看到这个自定义控件[项目关联1]：

![[query_displayFields.png|query_displayFields.png]]

查询数据字段设置

![[query_filterFields.png|query_filterFields.png]]

查询筛选条件设置


## 2.2.4 自定义控件查询前端运行态渲染开发

## 2.2.4.1查询列表

对于如何将数据库字段中存放的类似{"projectName":"项目1","id":"-8312506844008854456"}这种格式的数据在查询列表中正常显示出来，有两种方案:

 * 覆写接口中的convertCtrlValue方法将字段值转换为显示值，查询前端默认会以文本的格式显示出来；
 * 覆写接口中的convertCtrlValue方法和getRenderInfo4Run方法，并开发自己的列表插槽，具体可参看自定义控件（插槽）

![[query_table.png|query_table.png]]

## 2.2.4.2 筛选条件

自定义控件条件支持的操作类型

操作类型       说明
Equal      等于
NotEqual   不等于
Like       字符串模糊匹配包含
NotLike    字符串模糊匹配不包含

对于筛选条件的开发示例可以具体参考自定义控件(筛选条件)

![[query_filter_1.png|query_filter_1.png]]

普通筛选条件

![[query_filter_2.png|query_filter_2.png]]

筛选条件参数格式

筛选后结果如下：

![[query_filter_3.png|query_filter_3.png]]

筛选结果


## 3、自定义控件DEMO下载（本demo以表单电子发票这个自定义控件为例)：

 * apps目录中是移动端相关文件源码,自定义控件移动端采用H5技术；
 * src中是server端以及pc设置态相关源码；
   编撰人：yinyanting、pengbin


快速跳转



 * CAP4自定义控件后端规范
   * 1、自定义控件定义
   * 2、自定义控件设计方案
     * 2.1 总体设计方案
       * 2.1.1 插件/component开发说明
       * 2.1.2 自定义控件项目目录结构说明
       * 2.1.3 如何让CAP4表单编辑器中出现你的自定义控件
       * 2.1.4 如何让CAP4报表查询配置中出现你的自定义控件
       * 2.1.5 在spring配置文件中配置自定义控件Java类
     * 2.2 自定义控件属性设置开发
     * 2.2.1 定义自定义控件有哪些属性
     * 2.2.2 如何开发自定义控件属性设置页面
     * 2.2.2 自定义控件前端运行态渲染开发
     * 2.2.3 自定义控件在CAP4报表查询中有哪些属性
     * 2.2.4 自定义控件查询前端运行态渲染开发
       * 2.2.4.1查询列表
       * 2.2.4.2 筛选条件
   * 3、自定义控件DEMO下载（本demo以表单电子发票这个自定义控件为例)：



分享链接分享链接

## 10. CAP4自定义控件 - 移动端

> 原始路径：`/94/355/359/373/378.html`  
> 相对路径：`94/355/359/373/378.md`  
> JS Chunk：`app.371b709c.js`

## CAP4自定义控件 - 移动端

----------------------------------------

CAP4移动端表单自定义控件基本开发文档

CAP4表单自定义控件开发源自于PC端自定义控件，为了尽量保持一致开发，CAP4移动端自定义控件开发规范与PC端自定义控件开发规范基本保持一致。


## 1. 开发规范


## 1.1. 自定义控件项目结构

自定义控件项目前端可按照如下目录结构组织资源（目录结构及命名非强制要求），可根据实际情况增删目录。

─my-widget                组件资源存放的目录名
├─js                      js资源
├─css                     css资源
├─icon                    图标资源
├─index.html              html资源



## 1.2. 自定义控件生命周期

自定义控件必须实现init及destroy接口，负责自定义控件的渲染及销毁

 * 自定义控件渲染

a. 表单渲染时调用自定义控件实现的init接口来渲染自定义控件
b. 调用init接口时主动表单会传递以下参数
c. 可以根据需要动态/按需加载控件所需的其他资源

myWidget.init({
  adaptation,       // 表单操作代理
  url_prefix,       // 控件资源目录存放位置，如1.1.中的my-widget
  privateId         // 控件的标识符
})


 * 自定义控件销毁

表单会在某些情况（如视图切换/保存新建/保存复制）下需要调用自定义控件的destroy接口销毁自定义控件

myWidget.destroy(privateId)



## 1.3. 自定义控件开发

 * 自定义控件命名空间

a. CAP4表单在渲染自定义控件时会使用定义的命名控件获取自定义控件接口，用于管理自定义控件生命周期。
b. 命名空间建议以"cap4_custom_widget_"作为前缀，后缀根据控件自身语义命名
c. 命名空间目前默认注册到window对象，请尽量按照建议做法避免命名冲突


示例:

var scopeName = "cap4_custom_widget_my_widget_name";
  var widgetImpl = {};
  window[scopeName] = widgetImpl;


 * 自定义控件渲染及事件交互

a. 组件必须实现init及destroy方法
b. init方法用于组件初始化（如组件渲染、事件绑定、更新渲染等）
c. destroy方法用于组件销毁（如解除事件绑定、释放内存）
d. 以上两个接口均由表单发起调用


示例:

var scopeName = "cap4_custom_widget_my_widget_name";
  var widgetImpl = {
    init: function(options) {
      // 自定义初始化/渲染/事件绑定
    },
    destroy: function(widgetId) {
      // 自定义控件销毁
    }
  };
  window[scopeName] = widgetImpl;


 * 获取自定义控件数据

通过init接口传入的adaptation.childrenGetData方法获取控件数据

var field = adaptation.childrenGetData(privateId)
field = {
  attachmentInfo ： 自定义控件附件信息，
  attrs ： 自定义控件属性样式，
  auth ： 控件权限 追加(add) 编辑(edit) 浏览(browse) 隐藏(hide),
  ctrlBorderStyle ：，
  ctrlTitleStyle： ，
  ctrlType ： 控件类型，
  customFieldInfo ： 自定义控件的自定义控件信息，
  display ： 控件名，
  enums ： 控件的枚举信息，
  fieldLength ： 字段长度，
  fieldType ： 字段类型，
  formType： 表单类型 （formmain ： 主表， formson ： 明细表），
  recordId: 明细表的行ID，
  id： 字段ID（这里是字段名），
  inputType: 控件类型，
  isInCalculate： 是否计算（‘1’： 计算， ‘0’： 不计算），
  isInCondition： ，
  isNotNull： 是否必填，
  placeHolder： 提示信息，
  relation： ‘关联信息’，
  relationData： {
    imgShow: 是否显示关联图标，
    viewThrough ："1"//是否可穿透
    toMasterDataId:"2222"//穿透的数据id  无流程指的是表单数据id  有流程就是summeryId
  },
  showValue： 显示数据信息，
  value：参与计算的值，
  valueId ：数据库存储值
  formdata ： { // 表单信息 （这之前都是当前控件信息）
      content ： 表单的基础信息（包括表单的权限Id, 表单Id的等），
      formmains ： 表单的主表数据，
      formsons ： 表单的明细表数据，
      model ： 明细表是页签模式还是平铺模式（平铺模式是default），
      allData ： 整个表单的所有数据
  }
}


 * 监听自定义控件数据变化

a. 表单计算等可能引起自定义控件数据
b. 使用init接口传入的ObserverEvent.listen方法监听自定义控件数据变化并根据情况作出更新

adaptation.ObserverEvent.listen('Event' + privateId, function(newField) {
  // 更新你的控件
})


 * 自定义控件回填/更新表单数据

方法                        说明         参数                      参数格式                     参数说明
backfillFormControlData   用于回填控件数据   (payload, privatedId)   (Object/Array, String)   payload: 回填的数据， privatedId 当前控件的唯一标识ID（入口方法传入）
backfillFormAttachment    用于回填附件数据   (payload, privatedId)   (Object/Array, String)   payload: 回填的数据， privatedId 当前控件的唯一标识ID（入口方法传入）

// 回填数据示例 - 数组
payload = [
  {
    tableName : String,
    tableCategory : String,
    updateData : {
      field0002 : {
        value : 'your value'
        ...
      },
      field0003 : {
        value : 'your value'
        ...
      }
    },
    updateRecordId : String
  }
]
// 回填数据示例 - 对象
payload = {
  tableName : String,
  tableCategory : String,
  updateData : {
    field0002 : {
      value : 'your value'
      ...
    },
    field0003 : {
      value : 'your value'
      ...
    }
  },
  updateRecordId : String
}


 * 自定义控件调用表单方法

可以通过adaptation.backCallApi(name, callback, payload)方法在需要时主动调用表单公开的方法。
name:       String        方法的名称
callback:   Function      方法调用完成之后的回调(可选)
payload:    Any           表单方法接受的参数，由对应的方法决定


支持的方法列表

名称        参数                                                         说明
presave   { needCheckRule: '0', needDataUnique: '0', needSn: '0' }   表单预提交, 将用户填写的表单数据写入后端缓存

调用示例

adaptation.backCallApi(
  'presave',
  function() {
    console.log('表单预提交成功');
  },
  { needSn: '1' }
)



## 2. 开发示例

下面以实现一个按钮点击弹出"Hello CAP4!"例子演示如何开发自定义控件


示例:

(function () {
  // >>> step1. 定义控件唯一标识（命名空间）
  var scopeName = "field_5902128098173592526";

  // >>> step2. 实现自定义控件渲染及交互逻辑
  var MyWidgetImpl = function (options) {
    this.customWidgetType = scopeName;
    this._create(options);
  };
  MyWidgetImpl.prototype = {
    constructor: MyWidgetImpl,
    _create: function (options) {
      this._options = options;
      this._widgetId = options.privateId;
      this._widgetProxy = options.adaptation;
      this._wrapper = document.getElementById(this._widgetId);
      this._field = this._widgetProxy.childrenGetData(this._widgetId);
      this._tunnelId = 'Event' + this._widgetId;
      if (!this._wrapper) return console.warn('没有找到组件渲染的容器');
      this.clicked = 0;
      this._update();
      console.log(this._widgetProxy);
    },
    _update: function (field) {
      if (field) this._field = field;
      this._destroy();
      this._buildRendering();
      this._postCreate();
    },
    _buildRendering: function () {
      var elemId = 'section-' + this._widgetId;
      var btnId = 'section-' + this._widgetId + '-btn';
      var tpl = '<section id="section-' + elemId + '">' +
        '<button id="' + btnId + '" style="display:block;border:1px solid blue;border-radius:5px;margin:8px 16px;padding:5px;line-height:24px;;text-align:center">' + this._field.display +
        'clicked ' + this.clicked + '次</button>' +
        '</section>';
      this._wrapper.innerHTML = tpl;
      this._el = this._wrapper.querySelector('#' + elemId);
      this._btnEl = this._wrapper.querySelector('#' + btnId);
    },
    _postCreate: function () {
      this._unbindTap = this._bind(this._btnEl, 'tap', this.onClick.bind(this));
      this._unbindUpdate = this._listen(this._tunnelId, this._update.bind(this));
    },
    _destroy: function () {
      this._unbindTap && this._unbindTap();
      this._unbindUpdate && this._unbindUpdate();
      this._el = this._btnEl = null;
    },
    _bind: function (el, evt, cb) {
      el.addEventListener(evt, cb, false);
      return function () {
        el.removeEventListener(evt, cb, false);
      }
    },
    _listen: function(evt, cb) {
      var hub = this._widgetProxy.ObserverEvent;
      hub.listen(evt, cb);
      return function() {
        hub.remove(evt, cb);
      }
    },
    onClick: function () {
      this.clicked += 1;
      this._btnEl.innerHTML = this._field.display +
        'clicked ' + this.clicked + '次';
      alert('Hello CAP4!');
      this._update();
    }
  };

  // >>> step3. 实现开发规范约定的init及destroy接口
  var myWidgets = {};
  // 组件初始化
  MyWidgetImpl.init = function (options) {
    var widget = new MyWidgetImpl(options);
    myWidgets[ widget._widgetId ] = widget;
  };
  // 组件销毁
  MyWidgetImpl.destroy = function (widgetId) {
    var widget = myWidgets[ widgetId ];
    if (widget) widget._destroy();
    delete myWidgets[ widgetId ];
  };

  // >>> step4. 注册组件实现到命名控件
  window[ scopeName ] = MyWidgetImpl;
})();


运行效果:



自定义控件开发示例


## 3. 注意事项

 * 自定义控件有动态加载资源时，要防护重复加载资源
 * 由于数据变化等引起自定义控件需要更新时，要做好事件清理解绑，防止重复绑定事件
 * 如果需要使用到cmp组件，请参考cmp组件文档
 * 未列出内容，待后续更新补充

----------------------------------------

End

编撰人：yinyanting




快速跳转



 * CAP4自定义控件 - 移动端
   * 1\. 开发规范
     * 1.1. 自定义控件项目结构
     * 1.2. 自定义控件生命周期
     * 1.3. 自定义控件开发
   * 2\. 开发示例
   * 3\. 注意事项



分享链接分享链接

## 11. CAP4表单前端接口 - 移动端

> 原始路径：`/94/355/359/373/379.html`  
> 相对路径：`94/355/359/373/379.md`  
> JS Chunk：`app.371b709c.js`

## CAP4表单前端接口 - 移动端

----------------------------------------

CAP4移动端表单前端接口文档

CAP4移动端表单前端接口文档适用于M3(app)、微协同等


## 1. 表单事件


## 1.1. cap_form_afterFormRender

在表单首次渲染完成时触发（只触发一次）


用法示例:

document.addEventListener('cap_form_afterFormRender', function(evt) {
  console.log(evt)
});


事件参数:



表单首次渲染完成


## 1.2. cap_form_afterFormUpdate

在表单任何内容（包括主表字段/明细表字段/明细行）变化导致表单渲染更新时均会触发


用法示例:

document.addEventListener('cap_form_afterFormUpdate', function(evt) {
  console.log(evt)
});


事件参数:

无


## 2. 表单API


## 2.1. XForm.getData()

获取整个表单数据


接口参数:

无

用法示例:

XForm.getData()


返回结果:

{
  metadata: Object, // metadata中含有表单id，权限id等信息
  formmains: Object, // 主表数据
  formsons: Object // 明细表数据
}




获取整个表单数据


## 2.2. XForm.getField(fieldName[，tableName, recordId])

获取某个字段（控件）信息


接口参数:

参数名         参数类型     是否必须   说明
fieldName   String   必须     字段名
tableName   String   可选     明细表名
recordId    String   可选     明细行记录id

用法示例:

XForm.getField(fieldName) // 获取主表字段
XForm.getField(fieldName，tableName, recordId) // 获取明细行字段


返回结果:

{
  metadata: Object,   // metadata中含有表单id，权限id等信息
  formmains: Object,  // 主表数据
  formsons: Object    // 明细表数据
}




获取某个字段（控件）信息


## 2.3. XForm.setField(fieldName, data[，tableName, recordId])

更新某个字段（控件）信息


接口参数:

参数名         参数类型     是否必须   说明
fieldName   String   必须     字段名
data        Object   必须     更新的数据
tableName   String   可选     明细表名
recordId    String   可选     明细行记录id

用法示例:

data = {
  display: '新的控件标题',
  showValue: '新的控件显示值'
}
XForm.setField(fieldName, data) // 更新主表字段
XForm.setField(fieldName，data, tableName, recordId) // 更新明细行字段


返回结果:

true    // 更新成功
false   // 更新失败



## 2.4. XForm.allowedProps

列出字段（控件）支持更新的属性列表



## 3. 注意事项

 * 目前仅提供部分表单事件，后续根据实际反馈开放
 * cap2的事件名为sui_form_afterFormRender
 * XForm是CAP4移动端暴露在全局的变量
 * 目前只支持XForm.allowedProps列表内属性被更新
 * 未列出内容，待后续更新补充

----------------------------------------

End

编撰人：yinyanting、admin




快速跳转



 * CAP4表单前端接口 - 移动端
   * 1\. 表单事件
     * 1.1. cap_form_afterFormRender
     * 1.2. cap_form_afterFormUpdate
   * 2\. 表单API
     * 2.1. XForm.getData()
     * 2.2. XForm.getField(fieldName\[，tableName, recordId\])
     * 2.3. XForm.setField(fieldName, data\[，tableName, recordId\])
     * 2.4. XForm.allowedProps
   * 3\. 注意事项



分享链接分享链接

## 12. 关于协同升级到V5 8.0版本之后，自定义控件适配的说明

> 原始路径：`/94/355/359/373/380.html`  
> 相对路径：`94/355/359/373/380.md`  
> JS Chunk：`app.371b709c.js`

## 关于协同升级到V5 8.0版本之后，自定义控件适配的说明

特别说明，本说明适用于场景：自定义控件基于V5 8.0以前版本开发的，并且需要在V5 8.0既以上版本使用的需要适配，如果是继续在V5 8.0版本以前使用，不需要进行这个适配。另外，如果是基于V5 8.0既以上版本开发的，则不需要适配。

应公司最新的战略需求，CAP4应用需要支持同一个应用重复安装多次，并能用原始包对这些已安装的包都能进行升级。所以在这期间CAP4对应用包的安装和导出（包括单表单导出和导入）进行了改造，重新设计了各元数据ID的编码映射机制，保证应用重复安装之后，可以平滑进行数据升级。

 * 为什么要适配：如果不进行处理，可能自定义控件上的数据定义就不是有效的内容，这样会影响运行时的数据。首先说下为什么需要自定义控件开发进行适配，原因是：新的编码映射机制设计了三张表，分别存放应用上的数据，表单上的数据，公共数据（包括枚举和常量等），如果不进行适配，原来的接口不知道该将数据映射落位到什么地方，也不知道该从那个地方获取其他模块已经重置的元数据ID。
 * 怎么判断是否需要适配：检查自己实现FormFieldCustomCtrl接口的所有自定义控件，是否重写了getJson4Export、importExtInfo、importInfoAfterBizImport这几个方法，并且检查这几个方法内，是否用到了BusinessDataBean中被标注为过时（@Deprecated）的方法，比如：genNewIdByOldId，getEnumMapOld2New，getRealId4Export，getRealId4Upgrade等方法。
 * 怎么改：将上述被标记过时的方法，替换为BusinessDataBean中新的接口，接口说明，见方法上的备注：

导出应用相关的接口    
    /**
     * <p>通过当前资源id，获取业务编码。</p>
     * <p>注：该方法仅用于获取应用id，表单id，枚举id对应的编码
     * 其他id编码请调用{@link #lookupBizKey(MappingField,Long,Long)}</p>
     * @param table 映射表分类
     * @param sourceId 资源id，应用id，表单id，枚举id
     * @return
     */
    public Long lookupBizKey(MappingTable table, Long sourceId)｛｝
        
    /**
     * <p>通过当前资源id，获取业务编码。需要传递</p>
     * <p>注：该方法仅用于公共数据，比如枚举和常量函数使用
     * 其他id编码请调用{@link #lookupBizKey(MappingField,Long,Long)}</p>
     * @param table 映射表分类
     * @param sourceId 资源id，应用id，表单id，枚举id
     * @param orgAccountId 枚举和常量的单位id，如果为集团公用的，没有单位id的，直接传null
     * @return
     */
    public Long lookupBizKey4CommonData(MappingTable table,Long sourceId,Long orgAccountId)｛｝
    
    /**
     * <p>通过当前二级数据id和资源id，获取对应业务编码。</p>
     * 其他id编码请调用{@link #lookupBizKey(MappingTable,Long)}</p>
     * @param field 字段分类枚举
     * @param sourceId 资源id，应用id，表单id，枚举id
     * @param dataId 二级数据id
     * @return
     */
    public Long lookupBizKey(MappingField field,Long sourceId,Long dataId){}


安装相关的接口
    /**
     * 只是获取编码id对应的资源Id，如果没有返回null
     * @param table 表分类
     * @param bizKey JSON中解析出来的资源Id
     * @return
     */
    public Long onlyGetRootId(MappingTable table,Long bizKey){}
    
    /**
     * 只获取编码id对应的当前数据id，没有返回null，不会生成新id返回
     * @param field 映射表字段分类
     * @param sourceId 资源id
     * @param bizKey 原二级数据id
     * @return
     */
    public Long onlyGetSubId(MappingField field,Long sourceId,Long bizKey){}


此处仅写了几个比较通用的接口，其他的接口请移步BusinessDataBean中查看。

编撰人：yinyanting




快速跳转



 * 关于协同升级到V5 8.0版本之后，自定义控件适配的说明



分享链接分享链接

## 13. 全量接口

> 原始路径：`/94/355/359/373/701.html`  
> 相对路径：`94/355/359/373/701.md`  
> JS Chunk：`app.371b709c.js`

## 全量接口

继承FormFieldCustomCtrl

    /**
     * 设置控件在表单编辑器的控件页签中的图标样式class或者图标图片路径
     * 1、可以指定为系统图标库中存在的图标的class；
     * 2、可以是contextpath下，一个固定的图片路径，比如/apps_res/cap/customCtrlResource/xxx/aa.png
     */
    public void setIcon(String icon) {
        this.icon = icon;
    } 
    /**
     * 控件类型名称
     */
    public abstract String getKey();

    /**
     * 控件显示名称
     */
    public abstract String getText();

    /**
     * 控件类别
     */
    public abstract InputTypeCategory getCategory();

    /**
     * 该控件能显示那种类型的数据，可能是多种，所以用数组表示
     */
    public abstract Enums.FieldType[] getFieldType(); 
    /**
     * 返回控件标准类型
     */
    public String mappingStandardCtrlType() {
        return FormFieldComEnum.TEXT.getKey();
    }   
    /**
     * 初始化，自定义控件使用，这个方法放到全局不合理，应该放到FormFieldCustomCtrl里面去
     */
    public abstract void init();

    /**
     * 控件是否可用
     */
    public abstract boolean canUse();
    /**
     * 自定义控件分是否按钮类，如果是按钮类，则重写此接口返回true
     */
    boolean isButton();

    /**
     * 运行态生成控件的值，比如电子发票等控件在运行的时候需要生成一个uuid
     */
    Object genVal(Object oldVal);
    /**
     * 根据表单类型判断控件是否可用
     */
    public abstract boolean canUse(Enums.FormType formType);

    /**
     * 此控件是否是附件类控件
     *
     * @return
     */
    public abstract boolean isAttachment();

    /**
     * 初始值生成接口
     */
    public abstract String[] getDefaultVal(String defaultValue);

    /**
     * 定义控件是否能参与明细表，默认支持，如果不支持重写此方法返回false
     */
    boolean canInSubTable();

    /**
     * 定义控件能否拖入table，默认支持，如果不支持重写此方法返回false
     */
    boolean canInTable();
    /**
     * 控件类别
     */
    public abstract InputTypeCategory getCategory();
/**
     * 获取PC端自定义控件运行态资源注入信息
     * jsUri:定义PC端表单运行态加载第三方JavaScript的路径
     * cssUri：定义PC端表单运行态加载第三方CSS的路径
     * initMethod:定义PC端表单运行态第三方js入口方法名称
     * 用于运行态
     * @return
     */
    public abstract String getPCInjectionInfo();

    /**
     * 获取移动端自定义控件运行态资源注入信息
     * path：'http://'+m3应用包mainifest.json中的urlSchemes的值+'v'+m3应用包mainifest.json中的version的值
     * path：'http://'+8.1sp1 以后固定sourceId+'v'+m3应用包mainifest.json中的version的值
     * weixinpath: 微信端打开的时候使用的m3/apps/v5/自定义控件移动端资源目录名称/,weixinpath配置的就是此自定义控件移动端资源目录名称
     * jsUri:移动端表单运行态加载第三方JavaScript的路径
     * initMethod:定义M3端表单运行态第三方js入口方法名称
     * * nameSpace:定义M3端表单运行态命名空间
     * 用于运行态
     * @return
     */
    public abstract String getMBInjectionInfo();
/**
     * 设置扩展属性
     */
    public void addExtAttr(String key, Object value) {
        this.extendMap.put(key, value);
    }
    /**
     * 是否能作为查询统计的输出项，默认不支持，如果当前控件需要在查询统计中输出，则需要重写此接口返回true
     *用于无流程查询区域和报表查询区域
     */
   
    default FormFieldCustomCtrlReportInfo canShowInReport() {
        FormFieldCustomCtrlReportInfo reportInfo = new FormFieldCustomCtrlReportInfo();
        reportInfo.setEnableQuery(true);
        reportInfo.setEnableDisplayField(true);
        reportInfo.setEnableSort(true);
        reportInfo.setEnableFilterField(true);
        return reportInfo;
    }

    /**
     * 返回用于列表展示的值,过时了，使用key.config 配置文件渲染
     *
     * @param val 控件原始的值
     * @return 控件用于列表展示的值
     */
    @Deprecated
    Object getValue4ListItem(Object val);

    /**
     * 返回参与关联/触发映射时候的拷贝值,默认原值拷贝
     *
     * @param val 控件原始的值
     * @return 控件参与映射的值,
     */
    Object getValue4FillBack(Object val);

    /**
     * 表单另存为的时候，如果控件需要单独实现另存的逻辑，需要重写此接口实现控件自身的另存逻辑
     */
    void otherSave(FormFieldBean fieldBean, FormBean formBean, FormSaveAsBean mapping);

    /**
     * 业务包导出的扩展接口，自定义控件用，有需要的重写该方法
     *
     * @param formBean         当前表单
     * @param formFieldBean    当前字段
     * @param businessDataBean 导出中间对象，如果有附件，可以放到对象中的unifie{}ExportAttachment中
     * @param resultMap        字段json
     */
    void getJson4Export(FormBean formBean, FormFieldBean formFieldBean, BusinessDataBean businessDataBean, Map<String, Object> resultMap){
       //控件额外信息导出
        String customParam = formFieldBean.getCustomParam().isEmpty()?"":formFieldBean.getCustomParam();
        resultMap.put(BusinessExportConstant.CUSTOMPARAM, customParam);
        //控件枚举信息导出
        List<Long> enumIdList=new ArrayList<>();
        //将需要导出的枚举Id放入此处即可
        resultMap.put(BusinessExportConstant.CUSTOM_CTRL_ENUMS,enumIdList);
    }

    /**
     * 导入的时候处理自定义控件的扩展信息，自行重写接口来实现逻辑
     *
     * @param formBean         当前表单
     * @param formFieldBean    当前字段
     * @param businessDataBean 导入中间对象
     * @param fieldInfo        字段信息
     */
    void importExtInfo(FormBean formBean, FormFieldBean formFieldBean, BusinessDataBean businessDataBean, Map<String, Object> fieldInfo);

    /**
     * 在业务导入完之后自定义控件的处理接口
     *
     * @param formBean         当前表单
     * @param formFieldBean    当前字段
     * @param businessDataBean 导入中间对象
     */
    void importInfoAfterBizImport(FormBean formBean, FormFieldBean formFieldBean, BusinessDataBean businessDataBean);

    /**
     * 数据保存时，自定义控件保存方法，默认空实现，如果有需要，在自身的控件实现类中重写此方法
     *
     * @param params 参数
     */
    void handleSaving(Map<String, Object> params) throws BusinessException;

    /**
     * 数据保存并复制时，自定义控件接口，如果自定义控件支持保存并复制功能，需要重写此接口
     */
    void saveAndCopy(Map<String, Object> params);

    /**
     * 后台刷新接口，如果自定义控件需要后台刷新自定义控件内容，需要重写此接口
     * 供批量刷新、批量修改、触发关系使用
     */
    void refresh(Map<String, Object> params) throws BusinessException;

    /**
     * 检查自定义控件能够参与报表设置的哪些点，未使用
     *
     * @return 报表设置点的枚举集合
     */
    List<String> checkReportEnable();

    /**
     * 自定义控件参与报表条件设置时候，支持的操作符
     * <p>操作符：Equals(=), NotEquals(<>, Greator(>), GreatorEquals(>=), Less(<), LessEquals(<=), Like(like), NotLike(not like), In(in), Include(like)</>)</p>
     *
     * @return 返回支持的操作符的字符串数组
     */
    String[] getSupportConSymbolInReport();

    /**
     * 控件参与查询的时候其值的转换处理
     *
     * @param fieldBean 自定义控件所在字段
     * @param value     传入的控件的值
     * @return object，便于后续扩展，接口重用
     */
    Object convertCtrlValue(FormFieldBean fieldBean, Object value);

    /**
     * 获取用于报表列表显示的渲染资源路径
     *
     * @return 渲染js文件的路径
     */
    FormFieldCustomCtrlRunInfo getRenderInfo4Run();

    /**
     * 是否下架，默认false
     * 当下架时，在表单编辑器控件管理页面不再显示
     * @return false--否，true--下架
     */
    boolean offline();

    /**
     *  1 过滤哪些控件可以出现在校验规则 公式里的过滤方法 false过滤，true不过滤
     */
    boolean canInCheckRuleCondition();

    /**
     * 参与校验规则提示内容设置接口   预留，后面公式设置界面改造时候用到
     */
    //boolean canInCheckRuleTips();

    /**
     * 参与字段计算公式结果设置接口   预留，后面公式设置界面改造时候用到
     */
    //boolean canInFormulaResult();

    /**
     * 1 过滤哪些控件可以出现在计算公式里的过滤方法 false过滤，true不过滤
     */
@Deprecated
    boolean canInFormulaCondition();

    /**
     * 1 过滤哪些控件可以出现在计算公式(高级)里的过滤方法 false过滤，true不过滤
     */
@Deprecated
    boolean canInHighFormulaCondition();

    /**
     * 无流程表单应用绑定，操作范围屏蔽
     */
@Deprecated
    boolean canInOperatingRange();

    /**
     *业务关系--触发关系-前置条件公式屏蔽
     */
@Deprecated
    boolean canInConditionTypeNoFunction();
    /**
     * 业务关系--关联关系--筛选条件过滤
     */
    boolean canInScreeningConditions();

    /**
     * 是否能参与计算
     */
    boolean canInCalc();

    /**
     * 参与函数extend设置接口
     */
    boolean canExtend();

    /**
     * 返回字段参与字符串公式的值
     */
    Object getFormulaValue4Varchar(FormFieldBean fieldBean, Object val) throws BusinessException;

    /**
     * 返回字段参与数字公式的值
     */
    Object getFormulaValue4Number(FormFieldBean fieldBean, Object val) throws BusinessException;

    /**
     * 返回字段参与日期、日期时间公式的值
     */
    Object getFormulaValue4Date(FormFieldBean fieldBean, Object val) throws BusinessException;

    /**
     * 返回字段参与条件的值
     */
    Object getFormulaValue4Condition(FormFieldBean fieldBean, Object val) throws BusinessException;
 /**
     * 能否批量修改(无流程应用绑定)接口，能否批量刷新也用此接口判断
     */
    boolean canBathUpdate();

    /**
     * 参与无流程应用绑定操作范围设置接口(此接口应该可以和参与条件设置接口通用)    预留，后面公式设置界面改造时候用到
     */
    boolean canInUnFlowBindOperationScope();

    /**
     * 参与流程列表(待办列表和综合业务列表)操作范围设置接口
     */
    boolean canInFlowBusinessOperationScope();

    /**
     * 能否参与excel导入导出
     * */
    boolean canInExcelExpOrImp();

    /**
     * 能否参与无流程列表显示项，或者排序设置
     * 排序设置是从列表显示项中来的，因此接口共用一个
     * */
    boolean canInDataList();
    /**
     * 设置操作权限时是否支持必填设置
     *
     * @return true--支持，false--不支持 默认true
     */
    boolean isSupportRequiredValue();

    /**
     * 校验字段值是否必填权限，并且值没有填写，默认实现只校验权限是否必填，需要控件自身重写逻辑实现，
     * 如果控件是必填，并且没有填写，返回true，否则，返回false。
     *
     * @param formDataMasterBean 表单数据
     * @param field              字段
     * @param authViewFieldBean  字段权限
     * @param val                字段值
     */
    boolean authNotNullAndValIsNull(FormDataMasterBean formDataMasterBean, FormFieldBean field, FormAuthViewFieldBean authViewFieldBean, Object val);

    /**
     * 能否设置初始值
     */
    boolean isSupportSetDefaultVal();

    /**
     * 获取初始值系统变量待选项列表接口
     */
    List<String[]> getListShowDefaultVal(Integer externalType);

    /**
     * 字段在初始值设置页面上显示的元素
     *
     * @param fieldBean 当前字段
     * @param formId    当前编辑表单ID
     */
    Map<String, Object> getAuthDefaultValueMap(FormFieldBean fieldBean, Long formId) throws BusinessException;
 /**
     * 是否参与二维码组成接口
     */
    boolean barcodeContent();

    /**
     * 是否支持套红
     */
    boolean canInjectionWord();

    /**
     * 获取套红值
     */
    String getTaoHongValue(FormDataMasterBean masterBean, FormFieldBean fieldBean, Map<String, Object> special) throws BusinessException;

    /**
     * 获取签章保护数据
     */
    String getProtectedValue(Object value);

    /**
     * 翻译控件值提供给标签打印使用
     */
    Object getLabelPrintVal(FormFieldBean fieldBean, FormDataMasterBean masterData) throws BusinessException;

    /**
     * 获取全文检索值
     *
     * @param params 传入参数
     *               key: formFieldBean:FormFieldBean类型
     *               reference：Long类型,附件的reference
     *               value：Object类型,控件值
     */
    String convertVal4Index(Map<String, Object> params) throws Exception;

    /**
     * 控件值在回退或者撤销到待发列表的时候，是否需要清空此类型控件的值，默认需要，如果不需要清空，请重写此接口返回false
     */
    boolean needClearWhenBackToStarter();

    /**
     * 回退或者撤销到待发的时候，实现控件值的清空接口
     *
     * @param formBean     表单定义bean
     * @param masterDataId 数据id
     * @param fieldBean    字段定义bean
     * @param fillBackMap  如果要清空此字段的值，直接在map中put以字段名称fieldxxxx为key以null为value即可，cap会自动将map中的值更新回数据库动态表
     * @param attachments  要删除的附件信息
     */
    void clearWhenBackToStarter(FormBean formBean, Long masterDataId, FormFieldBean fieldBean, Map<String, Object> fillBackMap, Map<String, Long> attachments) throws BusinessException;

  

    /**
     * 是否支持一键复制，默认支持
     * @return
     */
    default Boolean canAKeyToCopy(){
        return true;
    }
/**
     * 参与触发关系前置条件接口    预留，后面公式设置界面改造时候用到
     */
    //boolean canInTriggerPreCondition();

    /**
     * 参与触发关系映射接口
     */
    boolean canInTriggerFillBack();

    /**
     * 参与触发关系映射接口    预留，后面公式设置界面改造时候用到
     */
    //boolean canInTriggerRowCondition();

    /**
     * 参与触发消息内容设置接口    预留，后面公式设置界面改造时候用到
     */
    //boolean canInTriggerMsgContent();

    /**
     * 参与关联关系映射接口
     */
    boolean canInRelationFillBack();

    /**
     * 是否能作为cap4手工关联cap3的关联过滤条件，默认是false，如果控件能支持，重写此接口返回true
     */
    boolean canInCap3RelationCondition();

    /**
     * 业务关系设置的时候，能不能给这个字段设置穿透信息
     * @since V8.0
     * @author wangh
     * @return
     */
    boolean canThroughSet();
 /**
     * 参与流程标题设置接口    预留，后面公式设置界面改造时候用到
     */
    //boolean canInFlowSubjectSet();

    /**
     * 参与流程消息内容组装接口   预留，后面公式设置界面改造时候用到
     */
    //boolean canInFlowMsgContent();

    /**
     * 参与流程分支条件接口
     */
    boolean canInWorkFlowBranch();

    /**
     * 参与流程表单相关数据查询接口
     */
    boolean canInRelatedDataCondition();
 /**
     * 控件设置态控制参数（最大控件数） -2 表示前端使用原有方式；-1表示不控制，非负整数表示具体可拖动的控件数量；
     *
     * @return
     */
    default FieldViewCtl setFieldViewCtl() {
        FieldViewCtl fieldViewCtl = new FieldViewCtl();
        FieldViewCtl.ViewParam viewParam = new FieldViewCtl.ViewParam(true, true, true,
                true, true);
        FieldViewCtl.Client client = new FieldViewCtl.Client(true, true);
        fieldViewCtl.setCount(5);
        fieldViewCtl.setTargets(viewParam);
        fieldViewCtl.setClients(client);
        return fieldViewCtl;
    }
 /**
     * 根据字段的字段类型获取该字段值的字符串格式  重复表间关系计算的时候在调用
     *
     * @param value 值
     * @return 如果为空，返回空字符串
     */
    public String getDbValue(Object value) {
        if (value == null || Strings.isBlank(String.valueOf(value))) {
            return "";
        }
        return value.toString();
    }

    /**
     * 获取控件的显示值 此方法被FormFieldBean.getDisplayValue()方法调用，默认是个空方法
     *
     * @param returnArr 长度为3的数组，（以组织机构控件为例，0：id(数据库保存值)、1：显示名称字符串(组织机构的名字字符串，数字类型百分号或者千分位或者小数位格式之后的值)、2：Member|292929292929(数字参与计算值，非组织机构则为展示值)）
     * @param valueStr  字段值的字符串形态
     * @param needSub   多部门时，是否需要有包含子部门标识（场景：当设置多部门的初始值时，不包含子部门的值后面会添加|1标识，但是不处理就直接显示页面会多余，而且保存后值有问题。）
     * @param forExport 是否导出时调用
     */
    public void getDisplayValue4Ctrl(FormFieldBean fieldBean, Object[] returnArr, String valueStr, boolean needSub, boolean forExport) throws BusinessException {

    }

    /**
     * 自定义控件extend扩展计算公式页面url
     * @return 返回自定义控件自定义extend计算公式配置页面url，默认返回空
     */
    public String extendUrl() {
        return null;
    }

    /**
     * 前端控制视图显示的config.json信息，该信息需要开发自定义控件用户自己实现，并将js配置到config.json中，
     * 前端通到config.json中取对应的js用于渲染；
     * 如查询条件，列表，报表等
     *
     * {
     *   "key": "1745730351955790712",
     *   "name": "formrichtext2ctrl",
     *   "path": {
     *     "pc": "apps_res/cap/customCtrlResources/formRichText2CtrlResources/js",
     *     "wap": "m3/apps/v5/customCtrlResources/formrichtext2ctrl/js",
     *     "native": "http://customCtrlResources.v5.cmp/v1.0.0/js"
     *   },
     *   "render": {
     *     "defRender": {
     *       "filter": "defRenderFilter.js",
     *       "list": "defRenderList.js"
     *     },
     *     "render1": {
     *       "filter": "render1Filter.js",
     *       "list": "render1List.js",
     *       "087C5688-8C95-49B9-2502-6727D6C3YY91": {
     *         "filter": "render1Filter.js",
     *         "list": "render1List.js"
     *       }
     *     },
     *     "render2": {
     *       "filter": "render1Filter.js",
     *       "list": "render1List.js",
     *       "087C5688-8C95-49B9-2502-6727D6C3YY91": {
     *         "filter": "render1Filter.js",
     *         "list": "render1List.js"
     *       }
     *     }
     *   },
     *   "renderMapping": {
     *     "cap4query": "render1",
     *     "cap4unflow": {
     *       "filter": "render2Filter.js",
     *       "list": "render2List.js",
     *       "087C5688-8C95-49B9-2502-6727D6C35502": {
     *         "filter": "render3Filter.js",
     *         "list": "render3List.js"
     *       }
     *     }
     *   }
     * }
     * @return config.json 文件路径
     *
     */
    public String viewJsUrl(){
        return null;
    }
    /**
     * 校验公式
     *
     * @param functionStr 自定义公式字符串
     * @param elementList 结果字段
     * @param formBean    结果字段
     * @return
     */
    @Override
    public ValidateResult check(String functionStr, List<String> elementList, FormBean formBean) {
        return new ValidateResult(true, null, -1);
    }

    /**
     * 自定义公式运行，表单高级计算公式和普通计算公式
     *
     * @param formBean
     * @param condition
     * @param cacheMasterData
     * @return
     */
    @Override
    public Object run(FormBean formBean, String condition, FormDataMasterBean cacheMasterData) {
        return "111";
    }


   //8.2 新增加
   /**
     * 报表拼接sql，编写时1=1需要修改为 （xx表.xx字段=xx值）
     *
     * @param formBean
     * @param fields
     * @return
     */
    default String reportRun(FormBean formBean, List<String> fields) {
        return "(1=1)";
    }

    /**
     * 计算公式布尔值，工作流用
     * @param formBean
     * @param fieldValue
     * @param containsValue
     * @return
     */
    default Boolean booleanValueRun(FormBean formBean, Object fieldValue,Object containsValue) {
        return true;
    }



## 8.1sp1后新增接口

    /**
     * 是否支持一键复制，默认支持
     * @return
     */
    default Boolean canAKeyToCopy(){
        return true;
    }

    /**
     * 控件设置态控制参数（最大控件数） -2 表示前端使用原有方式；-1表示不控制，非负整数表示具体可拖动的控件数量；
     *
     * @return
     */
    default FieldViewCtl setFieldViewCtl() {
        FieldViewCtl fieldViewCtl = new FieldViewCtl();
        FieldViewCtl.ViewParam viewParam = new FieldViewCtl.ViewParam(true, true, true,
                true, true);
        FieldViewCtl.Client client = new FieldViewCtl.Client(true, true);
        fieldViewCtl.setCount(5);
        fieldViewCtl.setTargets(viewParam);
        fieldViewCtl.setClients(client);
        return fieldViewCtl;
    }   

	/**
     * 自定义控件extend扩展计算公式页面url
     * @return 返回自定义控件自定义extend计算公式配置页面url，默认返回空
     */
    public String extendUrl() {
        return null;
    }

    /**
     * 前端控制视图显示的config.json信息，该信息需要开发自定义控件用户自己实现，并将js配置到config.json中，
     * 前端通到config.json中取对应的js用于渲染；
     * 如查询条件，列表，报表等
     *
     * {
     *   "key": "1745730351955790712",
     *   "name": "formrichtext2ctrl",
     *   "path": {
     *     "pc": "apps_res/cap/customCtrlResources/formRichText2CtrlResources/js",
     *     "wap": "m3/apps/v5/customCtrlResources/formrichtext2ctrl/js",
     *     "native": "http://customCtrlResources.v5.cmp/v1.0.0/js"
     *   },
     *   "render": {
     *     "defRender": {
     *       "filter": "defRenderFilter.js",
     *       "list": "defRenderList.js"
     *     },
     *     "render1": {
     *       "filter": "render1Filter.js",
     *       "list": "render1List.js",
     *       "087C5688-8C95-49B9-2502-6727D6C3YY91": {
     *         "filter": "render1Filter.js",
     *         "list": "render1List.js"
     *       }
     *     },
     *     "render2": {
     *       "filter": "render1Filter.js",
     *       "list": "render1List.js",
     *       "087C5688-8C95-49B9-2502-6727D6C3YY91": {
     *         "filter": "render1Filter.js",
     *         "list": "render1List.js"
     *       }
     *     }
     *   },
     *   "renderMapping": {
     *     "cap4query": "render1",
     *     "cap4unflow": {
     *       "filter": "render2Filter.js",
     *       "list": "render2List.js",
     *       "087C5688-8C95-49B9-2502-6727D6C35502": {
     *         "filter": "render3Filter.js",
     *         "list": "render3List.js"
     *       }
     *     }
     *   }
     * }
     * @return config.json 文件路径
     *
     */
    public String viewJsUrl(){
        return null;
    }
    /**
     * 校验公式
     *
     * @param functionStr 自定义公式字符串
     * @param elementList 结果字段
     * @param formBean    结果字段
     * @return
     */
    @Override
    public ValidateResult check(String functionStr, List<String> elementList, FormBean formBean) {
        return new ValidateResult(true, null, -1);
    }

    /**
     * 自定义公式运行，表单高级计算公式和普通计算公式
     *
     * @param formBean
     * @param condition
     * @param cacheMasterData
     * @return
     */
    @Override
    public Object run(FormBean formBean, String condition, FormDataMasterBean cacheMasterData) {
        return "111";
    }


   //8.2 新增加
   /**
     * 报表拼接sql，编写时1=1需要修改为 （xx表.xx字段=xx值）
     *
     * @param formBean
     * @param fields
     * @return
     */
    default String reportRun(FormBean formBean, List<String> fields) {
        return "(1=1)";
    }

    /**
     * 计算公式布尔值，工作流用
     * @param formBean
     * @param fieldValue
     * @param containsValue
     * @return
     */
    default Boolean booleanValueRun(FormBean formBean, Object fieldValue,Object containsValue) {
        return true;
    }



## 公式


## 计算公式

实现方案：将计算公式的配置、校验、实现交由自定义控件实现；


## 报表计算公式

功能：实现sql where 条件拼接,后端实现非groove

公式： customFunction({表单名称.富文本21},=,'5705361015223765326')

结果：（formmain_1024.field0007='5705361015223765326'）

代码：


## 工作流计算公式

功能：布尔值计算

公式：customCtrlFunction('==',{富文本21}, '1','富文本1')

结果：布尔值

代码：


## 表单计算公式

功能：包含高级计算公式和普通计算公式

公式: customFunction (''富文本1'，'客户计算公式字符串')；

结果：布尔值和 其他

代码：

编撰人：xuecx




快速跳转



 * 全量接口
 * 8.1sp1后新增接口
 * 公式
   * 计算公式
   * 报表计算公式
   * 工作流计算公式
   * 表单计算公式



分享链接分享链接

## 14. 自定义控件打包规范

> 原始路径：`/94/355/359/373/702.html`  
> 相对路径：`94/355/359/373/702.md`  
> JS Chunk：`app.371b709c.js`

## 自定义控件打包规范


## V8.1SP1 以前自定义控件补丁包格式

如：自定义控件A.zip

zip包含文件仅有 control.properties，并且V5终端环境已更新自定义控件的补丁包。

V8.1SP1 以前版本开发文档参考：后端 · CAP开发文档 · 看云 (kancloud.cn)


## V8.1SP1 以及之后版本自定义控件补丁包格式以及规范


## 补丁包结构：




## 兼容低版本的补丁包结构（此结构在V8.1SP1以前、以及高版本均兼容此补丁包格式，但V8.1SP1以前需要终端自行按照原逻辑进行补丁包文件的安装部署,此包结构仅对补丁包维护可以共用一个zip文件。）：




## 制作升级包（新的补丁包结构）

V8.1SP1 依据自己开发的文件结构，根节点为seeyon目录



V8.1SP2 新增 V8.1SP2 变更点后端文件：class文件、spring.xml、国际化文件， 需要添加一层目录：custom+{key} key:来自于config.json 里定义的key值 目前自定义控件仅支持加载后端class文件、spring.xml文件（加载spring Bean）、国际化文件




## 制作config.json包描述

V8.1SP1

config.json需要在一行内写完，不能换行（云端需要）,建议使用在线json压缩

config.json

 * {
 * “sourceCode”: “82951704012123”, ## 资源编码，每次需要通过UUID生成一个唯一值
 * “cloudType”: 3, ## 资源类型，默认3 自定义控件
 * “sourceName”: “富文本2”, ## 资源名称
 * “description”: “自定义组件的第一个富文本组件”, ## 资源描述
 * “restart”: 1, ## 是否需要重启，如果有java文件，需要重启 0 不需要，1需要
 * “sourceVersion”: “V1.2.0”, ## 资源版本 格式类似V1.2.0
 * “supportVersion”: “V8.0SP1,V8.0SP2”, ## 支持版本
 * “developer”: “王鑫鑫”, ## 开发人员
 * “supportTerminal”: “PC,MOBIlE,All”, ## 支持终端
 * “createTime”: “2021-10-27 13:36:25”, ## 出厂时间，创建时间
 * “key”:”richText88826600909”, ## 控件key 和 控件代码中的key一致，需要唯一
 * “pluginId”:”formBankRichText2Ctrl”, ## 控件pluginId 和 控件代码中的pluginId一致，需要唯一
 * “controlType”: “text”, ## 目前只支持text 此字段需要和mappingStandardCtrlType 中的一致
 * “beanIds”:”userId,userDao” ## 8.2新加
 * }


## V8.1SP2新增

  config.json:
   1. `beanIds` 字段定义需要校验的bean ； 多个以 `英文` 逗号拼接
   2. `key` : `控件英文名称`; 例如： richText1648797608000 ，开发自行定义
   3. `supportVersion`：ALL 如果包含此值，则该控件支持所有所有平台版本



## 压缩为zip文件

手动压缩，文件名称和控件名称保持一致


编撰人：xuecx


快速跳转



 * 自定义控件打包规范
   * V8.1SP1 以前自定义控件补丁包格式
   * V8.1SP1 以及之后版本自定义控件补丁包格式以及规范
     * 补丁包结构：
     * 兼容低版本的补丁包结构（此结构在V8.1SP1以前、以及高版本均兼容此补丁包格式，但V8.1SP1以前需要终端自行按照原逻辑进行补丁包文件的安装部署,此包结构仅对补丁包维护可以共用一个zip文件。）：
     * 制作升级包（新的补丁包结构）
     * 制作config.json包描述
     * V8.1SP2新增
 * 压缩为zip文件



分享链接分享链接

## 15. 自定义控件开发痛点问题

> 原始路径：`/94/355/359/373/703.html`  
> 相对路径：`94/355/359/373/703.md`  
> JS Chunk：`app.371b709c.js`

## 自定义控件开发痛点问题

整个控件完全跑通，大约需要2人天的开发和联调工作，其中痛点问题如下

1、包命名不规范不能热加载；

2、default接口不实现，无法适配表单；

3、控件前后端渲染交付存在大量约定变量，如控件key，前端控件命名空间、约定的前端渲染config.json配置、移动端资源路径等；

4、控件做包安装过程复杂；


## 自定义控件代码生成器能为开发干啥

1、一键解决上述痛点问题，每个控件可节约开发2人天开发联调工作；

2、开发仅需要关注自己的业务逻辑，无需花费不必需要的时间干控件通路问题；

3、ctp_studio上一键生成代码并上传到ctp_studio平台；

4、标准上架控件可一键生成maven工程前后端代码，开发工具一键打包上架zip文件；


## 代码生成器地址

为了使打包，配置能更加简单，cap开发了一个控件生成工具，让开发人员只关注自己的代码逻辑；

http://10.2.5.180:8082/seeyon/index.html （内部地址，仅供内部人员使用）




## 使用


## 字段解释

控件名称 = 显示在表单中自定义控件处的名称

工程名称= 生成java代码的工程名称；

className = 控件或者按钮的核心类的类名

OA版本 = 当前OA依赖的版本，正常开发的自定义控件于OA版本无关，开发过程中如果有问题则需要做兼容；

控件描述=控件安装完成后在资源中心可以看见的一个描述；


## 控件打包安装

1、直接利用maven的install 命令,会生成output目录，目录内有一个seeyon目录就是控件补丁，config.json就是控件描述文件



2、手动选中seeyon文件夹和config.json 压缩为zip文件，如上图中的”文本.zip“问题；

3、资源中心安装



4、8.1sp1 需要重启，8.1sp2 同一个控件第一次不需要重启，第二次开始需要；

5、控件更新安装需要加大config.json的版本号siyrceVersion的值，修改完成后在打包或者打包了后在修改；



编撰人：xuecx、luxxcd、lichaoj




快速跳转



 * 自定义控件开发痛点问题
 * 自定义控件代码生成器能为开发干啥
 * 代码生成器地址
 * 使用
   * 字段解释
   * 控件打包安装



分享链接分享链接

## 16. 自定义控件开发痛点问题

> 原始路径：`/94/355/359/373/704.html`  
> 相对路径：`94/355/359/373/704.md`  
> JS Chunk：`app.371b709c.js`

## 自定义控件开发痛点问题

整个控件完全跑通，大约需要2人天的开发和联调工作，其中痛点问题如下

1、包命名不规范不能热加载；

2、default接口不实现，无法适配表单；

3、控件前后端渲染交付存在大量约定变量，如控件key，前端控件命名空间、约定的前端渲染config.json配置、移动端资源路径等；

4、控件做包安装过程复杂；


## 自定义控件代码生成器能为开发干啥

1、一键解决上述痛点问题，每个控件可节约开发2人天开发联调工作；

2、开发仅需要关注自己的业务逻辑，无需花费不必需要的时间干控件通路问题；

3、ctp_studio上一键生成代码并上传到ctp_studio平台；

4、标准上架控件可一键生成maven工程前后端代码，开发工具一键打包上架zip文件；


## 区域控件生成器（区域）

1、直接在ctp_studio上生成控件，程序会自动提交到提交到git中，开发人员只需要git pull下来即可得到生成的控件，开发人员自需要编写自己的业务逻辑即可，无需在关注控件文件、前后端路径调试、规范要求的一系列约束ID；



2、移动端固定写法sourceId

@Override
public String getMBInjectionInfo() {
    return "{path:'http://sourceId.v5.cmp/v/',weixinpath:'123/',jsUri:'js/AAmRunning.js',initMethod:'init',nameSpace:'field_" + this.getKey() + "'}";
}


3、不能用历史的打包方式打包，既是安装包中做了control.properties文件的方式，否则会导致移动端无法使用；

编撰人：xuecx




快速跳转



 * 自定义控件开发痛点问题
 * 自定义控件代码生成器能为开发干啥
 * 区域控件生成器（区域）



分享链接分享链接

## 17. 8.2以上OA版本新增自定义控件V3版本支持首次安装热加载，不需要重启

> 原始路径：`/94/355/359/373/1349.html`  
> 相对路径：`94/355/359/373/1349.md`  
> JS Chunk：`app.371b709c.js`

## 8.2以上OA版本新增自定义控件V3版本支持首次安装热加载，不需要重启


## 自定义控件V3版本的规范

## 一、控件包结构：

需要沿用按照8.1sp2 版本的控件包格式封装控件包 具体如何封装控件包可参考文档：https://open.seeyoncloud.com/v5devCAP/94/355/359/373/702.html

## 二、V3版本控件

## 1、config.json适配

控件包V3版本定义：config.json文件里需要新增字段 —— deployVersion:V3

####2、控件后端代码规范

## a、rest接口层

rest接口的类 需要在spring文件里定义

## b、后端代码获取bean的方式

不能用AppContext.getBean("")取bean ,要用@Inject注入 原因：不用AppContext.getBean("")是因为用的子容器加载的控件，AppContext.getBean("")只能获取原始容器中的bean 具体原因可咨询架构王林勇

####3、注意事项：仅支持加载后端class文件、spring.xml文件（加载spring Bean）、国际化文件 若控件包有jsp、后端jar包，则控件热加载会不生效

编撰人：hedan




快速跳转



 * 8.2以上OA版本新增自定义控件V3版本支持首次安装热加载，不需要重启
   * 自定义控件V3版本的规范
     * 一、控件包结构：
     * 二、V3版本控件
     * 1、config.json适配
     * a、rest接口层
     * b、后端代码获取bean的方式



分享链接分享链接

## 18. 什么是触发：

> 原始路径：`/94/355/359/381/382.html`  
> 相对路径：`94/355/359/381/382.md`  
> JS Chunk：`app.371b709c.js`

## 什么是触发：

触发定义： 在指定的操作发生之后，当满足一定的条件时，异步的去执行特定的动作或逻辑

我们可以通过触发的设置，来进一步认识触发的定义，触发设置见下图



如上图所示，我们看到的是一个常见的触发设置，

其效果即是流程结束的时候，如果流程表的字段"文本1"包含了“需要触发”，那么就已更新无流程1中的字段

所以触发其实就是某张表单什么时间什么情况下去干什么事情

编撰人：yinyanting、zhangzuh




快速跳转



 * 什么是触发：



分享链接分享链接

## 19. 一、触发队列作用

> 原始路径：`/94/355/359/381/383.html`  
> 相对路径：`94/355/359/381/383.md`  
> JS Chunk：`app.371b709c.js`

## 一、触发队列作用

在上一节触发的定义中，我们会看到一个关键字-“异步”，也就是说在例如流程结束之后，触发的执行是由其他线程异步执行，而不是当前流程结束的线程同步执行的

由此，诞生了触发队列，从而解决触发异步执行的问题


## 二、触发队列模型


## 1.生产者与消费着经典模型

基于“异步”这个关键字，我们看看触发队列是怎么架构的

触发队列的总体架构，其实就是基于多线程的经典模型，生产者与消费者模型进行架构的



上图为经典的生产者与消费者模型，多个生产者线程不停的产生任务，放入到任务缓冲区，然后由多个消费者线程，不停的从缓冲区取出任务进行消费，从而异步的实现多线程执行任务

而触发队列在这套模型之上，根据自身的业务需求进行架构


## 2.CAP触发队列整体模型

首先，我们看看cap触发队列的整体模型图



每当流程提交、无流程数据保存等操作产生之后（实际上就是调用doTrigger方法），都会产生一个事件，并将该事件放入到事件队列中进行解析，该事件会根据源表设置的触发定义，产生出多个任务（一个aciton一个任务），并放入到任务队列中去，然后再由多线将任务取出，执行具体的逻辑（即执行触发设置的动作action）

由此可见，我们触发队列的整体流程为 产生事件--->放入事件队列--->解析事件为任务--->放入任务队列--->取出任务并执行

具体流程图示例如下图

简单版本：一条流程结束后，触发异步执行简图



复杂版本：多条流程结束后，触发异步执行简图



综上  触发队列其实就是基于生产者与消费者模式之上的异步多线程模型

编撰人：yinyanting、zhangzuh




快速跳转



 * 一、触发队列作用
 * 二、触发队列模型
   * 1.生产者与消费着经典模型
   * 2.CAP触发队列整体模型



分享链接分享链接

## 20. 介绍

> 原始路径：`/94/355/359/390/`  
> 相对路径：`94/355/359/390/README.md`  
> JS Chunk：`app.371b709c.js`

## 介绍

//待补充


编撰人：yinyanting


快速跳转



 * 介绍



分享链接分享链接

## 21. CAP4无流程表单应用绑定自定义按钮开发文档

> 原始路径：`/94/355/359/390/391.html`  
> 相对路径：`94/355/359/390/391.md`  
> JS Chunk：`app.371b709c.js`

## CAP4无流程表单应用绑定自定义按钮开发文档

----------------------------------------


## 概要说明

自V7.1版本开始，CAP4无流程表单应用绑定设置可以支持自定义按钮（以下简称按钮），客开伙伴可以用此通路在CAP4无流程数据列表页面开发一些想要的功能。

总体来说，应用绑定自定义按钮开发模式和表单编辑器中的自定义控件类似，是以插件或者组件的形式融入产品，插件或者组件开发规范请见http://open.seeyon.com/book/ctp/sdk/ctpbackendspec.html#插件化


## 应用绑定自定义按钮代码目录结构说明

开发按钮第一步自然是创建项目，创建项目之后目录结构可以参照以下示例创建各目录（以下目录结构是一个自定义按钮的示例）：

 ─seeyon
..├─apps_res
..│..└─cap
..│......└─customCtrlResources
..│..........└─newFormDataBtnResources
..│..............├─css
..│..............│......setTargetFormInfo.css
..│..............│
..│..............├─html
..│..............│......setTargetFormInfo.html
..│..............│
..│..............├─images
..│..............│......dash-arrow.png
..│..............│
..│..............└─js
..│......................customBtn8714694276131171133.common.js
..│......................customBtn8714694276131171133.umd.js
..│......................customBtn8714694276131171133.umd.min.js
..│......................setTargetFormInfo.js
..│
..└─WEB-INF
......├─cfgHome
......│..└─component
......│......└─newFormDataBtn
......│..........│..pluginCfg.xml
......│..........│
......│..........├─i18n
......│..........│......newFormDataBtn_en.properties
......│..........│......newFormDataBtn_zh_CN.properties
......│..........│......newFormDataBtn_zh_TW.properties
......│..........│
......│..........└─spring
......│..................spring-newformdatabtn-manager.xml
......│
......├─classes
......│..└─com
......│......└─seeyon
......│..........└─cap4
......│..............└─form
......│..................└─bean
......│......................└─button
......│..............................NewFormDataBtn.class
......│
......└─jsp



## 后端开发说明

要实现一个自定义按钮，需要写一个java类继承com.seeyon.cap4.form.bean.button.CommonBtn，并且实现/重写其中的接口，例如：

package com.seeyon.cap4.form.bean.button;

import com.seeyon.cap4.form.bean.FormBean;
import com.seeyon.cap4.form.bean.FormSaveAsBean;
import com.seeyon.cap4.form.modules.importandexport.BusinessDataBean;
import com.seeyon.cap4.form.util.Enums;
import com.seeyon.ctp.common.i18n.ResourceUtil;
import com.seeyon.ctp.util.Strings;
import com.seeyon.ctp.util.json.JSONUtil;

import java.util.HashMap;
import java.util.Map;

/**
 * Created by weijh on 2018-12-26.
 * 应用绑定新建按钮实现类
 */
public class NewFormDataBtn extends CommonBtn {

@Override
public void init() {
    this.setPluginId("newFormDataBtn");//设置插件或者组件id，和pluginCfg.xml中的id一致
    this.setIcon("cap-icon-custom-button");

    BtnParamDefinition targetFormInfoParam = new BtnParamDefinition();
    targetFormInfoParam.setDialogUrl("apps_res/cap/customCtrlResources/newFormDataBtnResources/html/setTargetFormInfo.html");
    targetFormInfoParam.setDisplay("com.cap.btn.newFormDataBtn.param1.display");
    targetFormInfoParam.setName("targetFormInfo");
    targetFormInfoParam.setParamType(Enums.BtnParamType.button);
    targetFormInfoParam.setDialogWidth("640");
    targetFormInfoParam.setDialogHeight("415");

    addDefinition(targetFormInfoParam);
}

@Override
public String getKey() {
 return "8714694276131171133";//给按钮设置一个key，可以随便取，只是不要和已有按钮冲突
}

@Override
public String getNameSpace() {
 return "customBtn" + this.getKey();
}

@Override
public String getText() {
 return ResourceUtil.getString("com.cap.btn.newFormDataBtn.text");//设置按钮名称
}

/*
/**
 * 获取PC端自定义控件运行态资源注入信息
 * jsUri:定义PC端表单运行态加载第三方JavaScript的路径
 * cssUri：定义PC端表单运行态加载第三方CSS的路径
 * initMethod:定义PC端表单运行态第三方js入口方法名称
 *
 * @return
 */
@Override
public String getPCInjectionInfo() {
 return "{\"path\":\"apps_res/cap/customCtrlResources/newFormDataBtnResources/\",\"jsUri\":\"js/" + this.getNameSpace() + ".umd.min.js\",\"initMethod\":\"init\",\"nameSpace\":\"" + this.getNameSpace() + "\"}";
}

@Override
public String getMBInjectionInfo() {
 return null;
}

/**
 * 导出的扩展接口，应用绑定自定义按钮用，有需要的重写该方法
 *
 * @param formBean         当前表单
 * @param businessDataBean 导出中间对象，如果有附件，可以放到对象中的unifiedExportAttachment中
 * @param resultMap        按鈕json
 */
@SuppressWarnings("unchecked")
@Override
public void getJson4Export(FormBean formBean, String customParam, BusinessDataBean businessDataBean, Map<String, Object> resultMap) {
    if (Strings.isNotEmpty(customParam)) {
     Map<String, Object> customParamMap = (Map<String, Object>) JSONUtil.parseJSONString(customParam);
     if(customParamMap.size() > 0){
      resultMap.putAll(customParamMap);
      Map<String, Object> targetFormInfo = (Map<String, Object>) customParamMap.get("targetFormInfo");
      Map<String, Object> targetFormMap = (Map<String, Object>) targetFormInfo.get("targetForm");
      String formId = (String) targetFormMap.get("formId");
      targetFormMap.put("formId", businessDataBean.getRealId4Export(Long.valueOf(formId)).toString());
      String bindId = (String) targetFormMap.get("bindId");
      targetFormMap.put("bindId", businessDataBean.getRealId4Export(Long.valueOf(bindId)).toString());
     }
    }
}
/**
 * 在业务导入完之后，应用绑定自定义按钮的处理接口
 * @param formBean
 * @param customParam
 * @param businessDataBean
 * @param btnInfoMap
 */
@Override
public void importInfoAfterBizImport(FormBean formBean, String customParam, BusinessDataBean businessDataBean, Map<String, Object> btnInfoMap) {
    if (Strings.isNotEmpty(customParam)) {
     Map<String, Object> customParamMap = (Map<String, Object>) JSONUtil.parseJSONString(customParam);
     btnInfoMap.putAll(customParamMap);
     Map<String, Object> targetFormInfo = (Map<String, Object>) customParamMap.get("targetFormInfo");
     Map<String, Object> targetFormMap = (Map<String, Object>) targetFormInfo.get("targetForm");
     int targetType = Integer.parseInt(String.valueOf(targetFormMap.get("targetType")));
     if (targetType == 0) {
      //业务内表单新建
      String formId = (String) targetFormMap.get("formId");
      targetFormMap.put("formId", businessDataBean.getNewIdByOldId(Long.valueOf(formId)).toString());
      String bindId = (String) targetFormMap.get("bindId");
      targetFormMap.put("bindId", businessDataBean.getNewIdByOldId(Long.valueOf(bindId)).toString());
     } else {
      btnInfoMap.putAll(new HashMap<String, Object>());
     }
    } else {
     btnInfoMap.putAll(new HashMap<String, Object>());
    }
}

/**
 * 表单另存为应用绑定自定义按钮另存为接口，各个应用绑定自定义按钮需要处理自己的逻辑
 * @param formSaveAsBean
 * @param formBean
 * @param btnInfoMap
 */
public void otherSave(FormSaveAsBean formSaveAsBean, FormBean formBean, Map<String, Object> btnInfoMap){
    Long saveToBizId = formSaveAsBean.getSaveToBizId();
    Long oldBizId = formSaveAsBean.getOldBizId();
    //另存为选择为空说明是存为单表
    if(null == saveToBizId){
        //原来是应用中的表，清空
        if(null != oldBizId){
            btnInfoMap.put("customParam","");
        }
    }else{//存为应用中的表单
        if(null == oldBizId){//原来是单表
            btnInfoMap.put("customParam","");
        }else{//原来是应用中的表单
            if(!saveToBizId.equals(oldBizId)){//跨应用另存，清空
                btnInfoMap.put("customParam","");
            }
        }
    }

 }
}


编撰人：yinyanting


快速跳转



 * CAP4无流程表单应用绑定自定义按钮开发文档
   * 概要说明
   * 应用绑定自定义按钮代码目录结构说明
   * 后端开发说明



分享链接分享链接

## 22. 自定义控件内容区插槽开发文档

> 原始路径：`/94/355/359/390/392.html`  
> 相对路径：`94/355/359/390/392.md`  
> JS Chunk：`app.371b709c.js`

## 自定义控件内容区插槽开发文档

----------------------------------------


## 概要说明

自V8.0版本开始，支持自定义控件列表内容区插槽开发。


## 应用绑定自定义按钮代码目录结构说明

开发按钮第一步自然是创建项目，创建项目之后目录结构可以参照以下示例创建各目录：

 ─seeyon
..├─apps_res
..│..└─cap
..│......└─customCtrlResources
..│..........└─projectRelatedResources
..│..............├─css
..│..............│......setTargetFormInfo.css
..│..............│
..│..............├─images
..│..............│......dash-arrow.png
..│..............│
..│..............└─js
..│..............│......projectRelatedPCList.umd.min.js



## 代码实现

(function () {

 // 命名空间key， 
var privated = 'customBtn8714694276131171133'; 
var self = {}; // 默认父容器为div，可以自行修改父容器类型，父容器会通过init的参数el传入进来 
self.tag = 'div'; 
    /** * 初始化入口，必须实现 * 
    @param el // 父容器dom，自定义控件挂载到该dom上 * @param props { *      data：自定义按钮后端返回的配置参数 * } *
    @param context // 上下文。 */
    self.init = function (el, props, context) { console.log('渲染:', el, props) // 根据props.data 中给的数据 在el中渲染内容。

    };
    /**
     * 重置条件
     */
    self.reset = function () {
        console.log('清空条件!')
    };
    
    /**
     * 销毁组件，当组件被移除之前的时候会触发，非必须实现。
     * @param el // 父容器
     */
    self.beforeDestroy = function (el) {
        console.log("销毁："+privated,el);
    };
    window[privated] = self;

})();


编撰人：yinyanting


快速跳转



 * 自定义控件内容区插槽开发文档
   * 概要说明
   * 应用绑定自定义按钮代码目录结构说明
   * 代码实现



分享链接分享链接

## 23. 自定义控件筛选条件开发文档

> 原始路径：`/94/355/359/390/393.html`  
> 相对路径：`94/355/359/390/393.md`  
> JS Chunk：`app.371b709c.js`

## 自定义控件筛选条件开发文档

----------------------------------------


## 概要说明

自V8.0版本开始，支持自定义控件筛选条件开发。


## 应用绑定自定义按钮代码目录结构说明

开发按钮第一步自然是创建项目，创建项目之后目录结构可以参照以下示例创建各目录：

 ─seeyon
..├─apps_res
..│..└─cap
..│......└─customCtrlResources
..│..........└─projectRelatedResources
..│..............├─css
..│..............│......setTargetFormInfo.css
..│..............│
..│..............├─html
..│..............│......setTargetFormInfo.html
..│..............│
..│..............├─images
..│..............│......dash-arrow.png
..│..............│
..│..............└─js
..│..............│......projectRelatedPCFilter.umd.min.js



## 代码实现

(function () {
 // 命名空间key， var privated = 'customBtn8714694276131171133'; 
var self = {}; // 默认父容器为div，可以自行修改父容器类型，父容器会通过init的参数el传入进来 
self.tag = 'div'; 

/** * 初始化入口，必须实现 * @param el // 父容器dom，自定义控件挂载到该dom上 * @param props { *      data：自定义按钮后端返回的配置参数 * } * 
@param context // 上下文。 _/ 

self.init = function (el, props, context) { 

console.log('渲染:', el, props) // 发送条件，条件变化后，向父组件通知。 

context.$emit('change',condition); 
}; 
    /_* * 重置条件 */ 
    self.reset = function () { console.log('重置条件!') };
    /_* * 清空条件 */ 
    self.clean= function () { console.log('清空条件!') };

    /_* * 点击筛选条件 */ 
    self.getValue= function () { console.log('返回条件!') };
    /**
     * 销毁组件，当组件被移除之前的时候会触发，非必须实现。
     * @param el // 父容器
     */
    self.beforeDestroy = function (el) {
        console.log("销毁："+privated,el);
    };
    window[privated] = self;

})();


编撰人：yinyanting


快速跳转



 * 自定义控件筛选条件开发文档
   * 概要说明
   * 应用绑定自定义按钮代码目录结构说明
   * 代码实现



分享链接分享链接

## 24. 门户开发及栏目挂载

> 原始路径：`/94/355/359/395/396.html`  
> 相对路径：`94/355/359/395/396.md`  
> JS Chunk：`app.371b709c.js`

## 门户开发及栏目挂载

----------------------------------------


## 说明

> 由于现在设计上，门户能够配置任何功能进行展示，为了方便代码的维护和管理，对门户进行了功能块组件化分割。


## 概览

门户设计




## 新建门户

下面用LayoutTest门户举例，如何新建一个门户页面


## start

 * 1.下载工程工程脚手架，运行npm i安装依赖
 * 2.在layout/pages/下拷贝LayoutShangJi文件夹，重命名LayoutTest
 * 3.在layout/pages/main.js中修改import App from './pages/LayoutTest/home.vue'指向到自己的栏目工程，此main.js是本地启动的关键，只是测试用，真正打包的main.js在layout/pages/LayoutTest/下 注：任何需要打包的属性，一定得加入到layout/pages/LayoutTest/下的main.js中


## step1

门户中如果引用栏目组件，main.js中推荐加入以下设置

// 主题字段，如果白色背景或者单独定制门户，则不需要设置。
Vue.prototype.$themes = 'black';
// 注入基础栏目组件支持
import  Cap4ColumnBase  from '_columns/cap4-column-base';
Vue.use(Cap4ColumnBase);

// 远程挂载组件(可选，只有远程挂载才会使用)
import  Cap4ColumnComponent  from '_columns/cap4-column-component';
Vue.use(Cap4ColumnComponent);



## step2

门户的主要处理逻辑（layout/pages/LayoutTest/home.vue）需要引入_utils/mixin/layoutMixin

引入后在mounted中通过this.getConfig()获取本模板配置信息。

直接通过this.getColumn(index)分割配置信息，将栏目配置信息分发给各个栏目。

以下参数可以直接用this.xxx访问到，部分参数在调用this.getConfig()后才能获取。

参数           说明       类型       备注
config       模板配置文件   Object   无
columns      栏目配置列表   Array    无
bussId       业务包id    String   从url上获取
templateId   模板id     String   从url上获取


## step3 创建配置文件

创建配置文件必须得理解栏目、栏目元素两个概念，一个模板包含多个栏目，一个栏目包含多个栏目元素。



门户设计

配置文件示例：

{
  "columns": [ --------------------------------------------------------门户模板包含的栏目数组
    {
      "elements": [ ---------------------------------------------------栏目中包含的栏目元素数组
        {
          "name": "本月商机成交量",
          "dynamicKey": "02440231-5E99-4D15-8FAC-57A3CA03F07C",
          "type": 4 ---------------------------------------------------栏目元素类型，影响门户设置数据源配置范围。
        },
        {
          "name": "本月商机成交量",
          "dynamicKey": "02540231-5E99-4D15-8FAC-57A3CA03F07C",
          "type": 5 ---------------------------------------------------type5为快捷入口，不会再页面上有显示内容，只影响点击跳转
        }
      ],
      "name": "待完成工作任务",
      "state": "1", ---------------------------------------------------栏目状态，后端可操作此字段来修改栏目显示状态。
      "type": 4 -------------------------------------------------------栏目类型，影响门户设置栏目配置的栏目类型显示。
    },
    {
      "elements": [
        {
          "name": "待完成项目任务",
          "dynamicKey": "03440231-5E99-4D15-8FAC-57A3CA03F07C",
          "type": 4
        },
        {
          "name": "待完成项目任务",
          "dynamicKey": "03540231-5E99-4D15-8FAC-57A3CA03F07C",
          "type": 5
        }
      ],
      "name": "待完成项目任务",
      "state": "1",
      "type": 4
    }
  ],
  "name": "任务管理模板",
  "type": 1
}


## 模板配置文件结构

参数        说明              类型       可选值
columns   参照栏目配置：column   Array    无
name      模板名称【必须】        String   无
type      模板类型【必须】        Number   0:pc&移动

1:pc
2:移动 |

## 栏目配置结构column

参数         说明                 类型       可选值
elements   参照栏目元素配置：element   Array    无
name       栏目名称【必须】           String   无
state      栏目开关状态【必须】         Number   无
type       栏目类型【必须】           Number   0 default 未指定

1 queryResult 查询结果
2 caclResult 统计结果
3 flowList 流程列表
4 businessTarget 业务指标
5 shortCut 快捷方式
6 unflowList 无流程列表
7 noData 无须配置数据源
8 menuCollection 菜单合集 | | componentName | 动态挂载时需要指定此栏目挂载的组件名【可选】
配置了这个字段才能使用Cap4ColumnComponent动态挂载 | String | 无 | | componentUrl | 指定组件的url路径（可不用vue组件，如果是.html结尾会自动使用ifram加载）【可选】
| String | 无 |

## 栏目元素配置结构element

参数           说明            类型       可选值
name         栏目元素名称【必须】    String   无
dynamicKey   全局唯一key【必须】   String   无
type         栏目元素类型【必须】    Number   0 default 未指定

1 queryResult 查询结果
2 caclResult 统计结果
3 flowList 流程列表
4 businessTarget 业务指标
5 shortCut 快捷方式
6 unflowList 无流程列表
7 noData 无须配置数据源
8 menuCollection 菜单合集 | | page | 取得查询或者统计时候
可分页取得数据【可选】 | Object | {
page:1(从1开始，必须),
pageSize:50(默认50，可选)
} | | columnIndex | 返回第几列数据，如果大于总列数则返回最后一列【可选】 | Number | 无 | | maxColumnLength | 限制（统计查询）最大返回列【可选】 | Number | 无 | | completeCrossColumn | 限制（统计查询）最大返回列，可能产生不完整交叉项，
如果为true则舍弃不完整交叉组，返回可能小于最大返回列【可选】 | Boolean | 无 | | extend | 扩展字段【可选】 | Object | 无 |


## step4 上传商城

现在写的config文件没有栏目id跟栏目元素id。这两个id是经过后台处理后，由后台分配的，本地调试需要进行商城上传下载。
后台处理后的config文件，栏目和栏目元素被分配了id，这时候才能获取数据。

后台处理后config示例：

{
 "templateFolder": "2346017665022313537", --------------------------------------- 后端分配的模板id，此id一般在url上直接获取
 "columns": [{
  "columnId": "165012826161365089", -------------------------------------- 后端分配的栏目id
  "elements": [{
   "elementId": "1152844087841408814", ---------------------------- 后端分配的栏目元素id
   "name": "新建菜单合集",
   "dynamicKey": "01863984-0646-49C6-BD8F-780ACEE28521",
   "type": "8"
  }],
  "name": "新建菜单合集",
  "state": "1",
  "type": "8"
 }, {
  "columnId": "3115505023330371320",
  "elements": [{
   "elementId": "4257172996191834010",
   "name": "本月新增商机",
   "dynamicKey": "02440231-5E99-4D15-8FAC-57A3CA03F07C",
   "type": "4"
  }, {
   "elementId": "4088305993474785437",
   "name": "本月新增商机",
   "dynamicKey": "02540231-5E99-4D15-8FAC-57A3CA03F07C",
   "type": "5"
  }],
  "name": "本月新增商机",
  "state": "1",
  "type": "4"
 }, {
  "columnId": "2627389823276306095",
  "elements": [{
   "elementId": "7556469782579068978",
   "name": "本月新增客户",
   "dynamicKey": "03440231-5E99-4D15-8FAC-57A3CA03F07C",
   "type": "4"
  }, {
   "elementId": "2070180027328514266",
   "name": "本月新增客户",
   "dynamicKey": "03540231-5E99-4D15-8FAC-57A3CA03F07C",
   "type": "5"
  }],
  "name": "本月新增客户",
  "state": "1",
  "type": "4"
 }, {
  "columnId": "3735702750817242562",
  "elements": [{
   "elementId": "4357802298177374266",
   "name": "本月商机成交量",
   "dynamicKey": "04440231-5E99-4D15-8FAC-57A3CA03F07C",
   "type": "4"
  }, {
   "elementId": "-2211378874524548588",
   "name": "本月商机成交量",
   "dynamicKey": "04540231-5E99-4D15-8FAC-57A3CA03F07C",
   "type": "5"
  }],
  "name": "本月商机成交量",
  "state": "1",
  "type": "4"
 }, {
  "columnId": "-3940581403590308363",
  "elements": [{
   "elementId": "126384694740273687",
   "name": "本月成交金额",
   "dynamicKey": "054CDA7B-479D-4F9B-A21A-431C9D68F75B",
   "type": "4"
  }, {
   "elementId": "-2482746810529855644",
   "name": "本月成交金额",
   "dynamicKey": "055CDA7B-479D-4F9B-A21A-431C9D68F75B",
   "type": "5"
  }],
  "name": "本月成交金额",
  "state": "1",
  "type": "4"
 }, {
  "columnId": "-2923792911191421994",
  "elements": [{
   "elementId": "-9001353740858146132",
   "name": "客户来源分析",
   "dynamicKey": "06233BE8-89EF-4F6A-BD78-FEFD5BA37840",
   "type": "2"
  }, {
   "elementId": "8698323620921229485",
   "name": "更多",
   "dynamicKey": "0653D5B7-05BB-4BBD-B8CD-06B4ABC2508A",
   "type": "5"
  }],
  "name": "客户来源分析",
  "state": "1",
  "type": "2"
 }, {
  "columnId": "-5055874239504298447",
  "elements": [{
   "elementId": "-835606408726230998",
   "name": "本于销售业绩PK",
   "dynamicKey": "07233BE8-89EF-4F6A-BD78-FEFD5BA37840",
   "type": "2"
  }, {
   "elementId": "8798617162677897017",
   "name": "更多",
   "dynamicKey": "0753D5B7-05BB-4BBD-B8CD-06B4ABC2508A",
   "type": "5"
  }],
  "name": "本于销售业绩PK",
  "state": "1",
  "type": "2"
 }],
 "name": "商机管理模板",
 "type": "1",
 "templateId": "2346017665022313537"
}



## step4-1

执行npm run dist:layout,选择LayoutTest进行打包，打包后在dist_layout文件夹下找到LayoutTest.zip,用于上传商城

上传文档：更新商城主题包文档


## step4-2 本地调试

需要在本地启动v5后台，在门户设置中下载刚上传的主题包，配置权限。

通过预览获取config的路径和业务包id、模板id，获取到这些参数以后，配置本地env文件layout/env/env.js

最后通过npm dev:layout本地启动门户首页。


## step5 门户开发

参照示例门户、通过import引入标准栏目组件。

注：如果组件没有在工程下，需要远程加载，则使用Cap4ColumnComponent来代理加载，vue组件是.js结尾，支持.html结尾的组件

<Cap4ColumnComponent
    src="http://10.5.5.200:4000/static/wwc/cap4-pc-ui-eg/index.js" // 远程栏目组件挂载地址
    :templateId="templateId" // 挂载栏目组件的参数
    :bussId="bussId" // 挂载栏目组件的参数
    :column="getColumn(5)"> // 挂载栏目组件的参数
</Cap4ColumnComponent>



## step6 eg数据制作

在LayoutTest\config下有data.json,这个是门户的默认数据，当刚下载门户模板没有数据获取时候，由这个json文件填充。

data.json与config.json是一一对应的，参照config.json的dynamicKey对应创建data.json的数据。


## end 门户再次上传

引入栏目组件后的门户网站，再次上传商城，重新配置数据源。

编撰人：yinyanting、chenlin




快速跳转



 * 门户开发及栏目挂载
   * 说明
   * 概览
   * 新建门户
     * start
     * step1
     * step2
     * step3 创建配置文件
       * 模板配置文件结构
       * 栏目配置结构column
       * 栏目元素配置结构element
     * step4 上传商城
     * step4-1
     * step4-2 本地调试
     * step5 门户开发
     * step6 eg数据制作
     * end 门户再次上传



分享链接分享链接

## 25. 栏目开发及流程说明

> 原始路径：`/94/355/359/395/397.html`  
> 相对路径：`94/355/359/395/397.md`  
> JS Chunk：`app.371b709c.js`

## 栏目开发及流程说明

----------------------------------------


## 说明

栏目组件为特殊的业务组件，自身会根据栏目配置发送ajax请求。

## 依赖关系：

 * 所有栏目组件都依赖于cap4-column-base组件，此组件包含ajax底层请求方法，和v5环境变量。
 * 所有栏目组件都依赖于_utils/mixin/columnMixin，此组件包含了数据请求方法，和基本的数据注入。 注：_utils/mixin/columnMixin中包含有_utils/mixin/themesMixin，无需再次引入;

以上依赖已经预置到初始化栏目组件里。

## cap4-column-base组件提供支持

由门户开发人员注入，全局只需要一个，主要提供栏目的ajax请求支持。

注入后可在vue原型对象上访问到$httpClient对象。

$httpClient：

参数                          说明                     类型       备注
env                         v5外框的环境参数              Object   {_ctxPath,_ctxServer,CsrfGuard}
getUrlSurffix()             v5外框的跨域保护，返回String     String   
urls                        栏目相关url合集              Object   
axios                       pc-ajax请求用工具           Object   
setEnv(p)                   可在env中手动写入字段，或覆盖环境变量            p:Object对象
getDataByColumnIds(p1,p2)   取得栏目运行时数据,返回promise             p1:模板id p2:栏目元素id数组
getCurrentUserInfo()        取得用户信息,返回promise                
getConfig()                 取得配置文件,返回promise                

注：如果不使用$httpClient,可自行通过接口获取数据。

urls：的接口列表

//根据模板id获取运行时数据
    getDataByTemplateIdUrl:`${_ctxPath}/rest/cap4/template/getDataByTemplateId/`,
    //根据栏目id获取运行时数据
    getDataByColumnIdsUrl:`${_ctxPath}/rest/cap4/template/getDataByColumnIds/`,
    //根据栏目元素id获取运行时数据
    getDataByElementIdsUrl:`${_ctxPath}/rest/cap4/template/getDataByElementIds/`,
    // 根据真实参数获取运行时数据
    getDataByRealParams:`${_ctxPath}/rest/cap4/template/getDataByRealParams`,


推荐使用根据栏目元素id获取运行时数据，方便理解。

请求地址:/seeyon/rest/cap4/template/getDataByElementIds
请求类型:POST
请求参数：
 templateId:模板id
 elementIds:[123,123]
返回参数：
{
    "code": 1000,
    "data": {
        ...
    },
    "message": "the operation is success!!!"
}


## _utils/mixin/columnMixin提供支持

为了标准化栏目开发规范，所有栏目组件都必须混入_utils/mixin/columnMixin来提供以下特性。

props: 接受参数

参数           说明          类型       备注
column       栏目配置        Object   数据获取和栏目元素名称获取
templateId   模板id【必须】    String   模板id，用于数据获取
bussId       业务包id【必须】   String   主要用于穿透

data:*引入后可直接用this.xxx 进行访问到数据信息

参数       说明      类型       备注
datas    栏目配置    Array    栏目请求到数据后数据所存放的位置
keys     模板id    Array    从模板配置文件中解析出来的dynamicKey合集
themes   业务包id   String   门户开发人员所设置的皮肤样式字段，用于适配多皮肤栏目

methods:提供方法

 * getData (callback)，在栏目组件的mounted或者create中调用，调用后才能使用下面方法获取数据

*** callback【可选】：请求数据完成后的回调，非必须，利用双向绑定无需使用。

 * this.dk(index,key)次方法可以根据栏目的标记位置取到对应的数据。

*** index【必须】：配置文件中数据标记位置如下标记0,标记1

*** key【可选】：取得栏目元素数据中某个字段的值。

column：从config中切割下来的栏目配置，以下为dk标记位置

{
      "fileName":"yearStatis",
      "oldFileName":"yearStatis",
      "elements":[
           { -- 标记0
                "name":"本部门预算执行率",
                "dynamicKey":"E9640111-5E99-4D15-8FAC-57A3CA03F07C",
                "type":4
           },
           {-- 标记1
                 "name":"本部门预算执行率",
                 "dynamicKey":"E9640111-5E99-4D15-8FAC-57A3CA03F07C",
                 "type":5
           }
      ],
      "name":"本部门年度预算统计",
      "state":"1",
      "type":4
}



## 集成以上组件后，栏目开发代码如下

<template>
  <div class="cap4-column-card-container" :style="{cursor:dk(1,'isEg')=='1'?'default':'pointer'}" @click="goUrl(dk(1))">
    <cap4-pc-ui-eg
      style="position: absolute;top: 0px;left: 10px;z-index: 1"
      v-if="dk(0,'isEg')=='1'"
      :direction="1">
    </cap4-pc-ui-eg>
    <div class="cap4-column-card-left" :style="{backgroundColor:color}">
      <div class="inner" v-if="keys.length">
        <p class="value" :title="dk(0,'display')" >
          {{dk(0) | dataFormat}}&nbsp;
        </p>
        <p class="type" :title="dk(0,'name')" v-text="column.name"></p>
      </div>
    </div>
    <div class="cap4-column-card-right" :style="{backgroundColor:color}">
      <i class="CAP" :class="[icon]"></i>
    </div>
  </div>
</template>
<script>
    import columnMixin from '_utils/mixin/columnMixin';
    import dataFormatMixin from '_utils/mixin/dataFormatMixin';
    import Cap4PcUiEg from '_pc_ui/cap4-pc-ui-eg';
export default{
    name: 'Cap4ColumnCard',
    mixins : [columnMixin,dataFormatMixin],
    props: {
        color : {
            type : String,
            default : '#3FA8D8'
        },
        icon : {
            type : String,
            default : ''
        }
    },
    data () {
      return {
      }
    },
      mounted (){
          this.getData();
      },
      methods:{

      },
        components : {Cap4PcUiEg}
  }
</script>


编撰人：yinyanting


快速跳转



 * 栏目开发及流程说明
   * 说明
     * 依赖关系：
     * cap4-column-base组件提供支持
     * _utils/mixin/columnMixin提供支持
     * 集成以上组件后，栏目开发代码如下



分享链接分享链接

## 26. 无流程模板

> 原始路径：`/94/355/359/398.html`  
> 相对路径：`94/355/359/398.md`  
> JS Chunk：`app.371b709c.js`

## 无流程模板


## 1.模板开发

 * 在代码工程cap-front中找到pc_unflow工程，在src目录下找到views，这里面就是系统中的所有无流程表单模板，这里面只有默认模板（unflow-0）会随项目打包自动更新内容，其他的模板都需要我们自己重新打包-> 更新测试商城 -> 提测 -> 走组件上新过程到正式商城。
 * 首先我们开发的所有模板都是基于unflow-0项目来，所以我们开始复制一个文件夹unflow-0,这里注意无流程模板的文件夹都是以’unflow-‘开始的。
 * 然后在复制的文件夹里修改我们的内容。这里注意：在index.vue文件中我们必须引入allMixins以及tableMixin，这两个文件是公共必须的文件。文件中的一些方法我们可以使用，同时我们也可以在我们文件重写，注意名称保持一致。
 * 在images中的cover.png文件名字固定的，图片可以换，这个是展示在模板使用中的设置部分的背景图。
 * 在config.json中内容是栏目开发中的内容。参考栏目开发中的配置项。
 * 在package.json中添加我们对应的启动命令。（"serve:你的模板名称": "vue-cli-service serve --你的模板名称",）
 * 在vue.config.js中添加我们新的模板对应的命令，将红框部分复制一份换成我们新模板对应的打包命令名称以及文件路径即可。
 * 打包构建命令为npm run lib 然后勾选我们对应的模板即可。
 * 为了方便我们每次都不用手动去商城更新上传，我们可以在第一次上传后获取到模板id，然后在config -> shopConfig-dev.js 中添加我们新模板的配置信息，然后每次打包最后会有个询问是否上传到上传，选择是就可以了。


## 2.模板调试

 * 首先启动我们项目npm run serve:你的模板名称
 * 登录系统，找到一个无流程模板
 * f12打开调试面板。在element中找如图iframe，右键选择open in new tab。
 * 在面板中看到如图页面，去掉红框的内容访问页面。这样我们就可以进行本地调试了。


## 3.模板使用

 * 进入菜单
 * 
 * 选择一个应用，进入应用
 * 在上侧的菜单中选择门户设置
 * 
 * 在弹框中点击默认模板PC
 * 
 * 在pc Tab中就是模板，红色框就是无流程的两个模板，鼠标移入，点击使用就可以了


## 4.常见客户bug

页面出现使用时出现404 not found



原因和解决方式：

 * 原因1：可能是版本升级，导致客户对应的模板的版本未升级，模板还是使用的是以前的老的版本的模板；解决方式：重新在应用设置平台 -> 应用管理中心 ->  门户设置里 -> 页面设置,找到对应的的表单，在配置里重新使用模板
 * 原因2：在后台中使用模板的id为老旧的模板id，因此每次去使用下载的模板一直不正确； 解决方法：修改数据库中查询的id
 * 原因3：查看页面中http请求，发现存在请求404的问题，请求路径存在STATIC_PATH、STATIC_SUFFIX等字段时，是因为在页面打包构建时，路径上的变量未完全替换； 解决方法：1.手工替换为seeyon或者客户自己的路径 2.采用替换工具，执行替换，然后重启客户环境（关联客户bug号：BUG2021033138263）
   编撰人：yinyanting、xuecx


快速跳转



 * 无流程模板
   * 1.模板开发
   * 2.模板调试
   * 3.模板使用
   * 4.常见客户bug



分享链接分享链接

## 27. 概要

> 原始路径：`/94/355/359/399/`  
> 相对路径：`94/355/359/399/README.md`  
> JS Chunk：`app.371b709c.js`

## 概要

1、介绍CAP中支持客开的表单业务能力扩展机制，帮助理解和使用CAP中面向客开的设计器扩展配置、运行态插件机制及表单相关接口。
2、CAP客开插件是针对表单、查询列表、无流程列表、待办列表等应用制作满足实际应用需求的前端静态资源包，详细介绍见客开插件

编撰人：yinyanting




快速跳转



 * 概要



分享链接分享链接

## 28. 介绍

> 原始路径：`/94/355/359/399/400/`  
> 相对路径：`94/355/359/399/400/README.md`  
> JS Chunk：`app.371b709c.js`

## 介绍

表单设计器预置了针对一定范围内高频客开场景的能力配置，可灵活的配置表单各模块功能开关。


## 章节内容

1.具体使用步骤；

2.介绍基本的能力配置；

3.支持的事件API；

4.Demo示例

编撰人：yinyanting




快速跳转



 * 介绍
 * 章节内容



分享链接分享链接

## 29. 表单能力配置使用

> 原始路径：`/94/355/359/399/400/401.html`  
> 相对路径：`94/355/359/399/400/401.md`  
> JS Chunk：`app.371b709c.js`

## 表单能力配置使用

步骤如下

1.增加表单扩展脚本

表单设计器加载前会先请求扩展脚本，需在对应路径添加extend脚本

/seeyon/common/cap4/design/extend.js

2.定义表单配置对象

将formDesignerExtend配置对象挂载至window即可：

extend.js中配置

window.formDesignerExtend = {
    config: {  
        //添加需要的能力配置
    },  
    event: {  
        //添加需要的事件
    }  
};


3.实现需求对应的事件处理

如需求为表单设计器加载完成后请求后台某自动处理任务：

function autoTaskRequest() {
    $.ajax({
        url: "seeyon/autoTaskBusiness/customTask1",  
        type: "post",
        data: {param: 0},
        success: function(){}
    }); 
}
window.formDesignerExtend = {
    config: {  
        supportDesign: true  
    },  
    event: {  
        designerRendered: function() {
            autoTaskRequest(); 
        }  
    }  
};


编撰人：yinyanting


快速跳转



 * 表单能力配置使用



分享链接分享链接

## 30. 设计器能力配置

> 原始路径：`/94/355/359/399/400/402/`  
> 相对路径：`94/355/359/399/400/402/README.md`  
> JS Chunk：`app.371b709c.js`

## 设计器能力配置

如下图，按照设计器业务功能划分区域：



序号   区域      标注颜色   配置标识
0    -       -      baseCfg
1    工具栏     红色     toolbar
2    控制区     蓝色     ctrlArea
3    设计区     绿色     designArea
4    属性设置区   黄色     settingArea

> 能力配置示例：

//表单设计器能力配置示例
window.formDesignerExtend = {
    config: {
        //0-全局基础配置
        baseCfg: {
            supportDesign: true //是否支持设计器编辑
        },
        //1-工具栏
        toolbar: {
            supportCopy: true, //是否支持复制功能
            fontFamilyExtend: [   //字体扩展示例,每项格式为['字体英文名', '字体中文名']
                ['Microsoft YaHei', '微软雅黑'],
                ['Microsoft JhengHei', '微软正黑体']
            ],
            fontSizeExtend: [26,30] //字体大小扩展示例,单位为像素
        },
        //2-控制区
        ctrlArea: {
            //布局
            layout: {
                supportCustom: false, //是否支持自定义布局
            },
            //控件列表
            ctrlList: {
                supportCustomCtrl: true //是否支持自定义控件
            },
            //数据域
            dataSource: {
                supportQuickGenField: true //是否支持快速生成字段
            }
        },
        //3-设计区
        designArea: {
            maxViewsCount: 20, //单平台(PC/移动)最大视图个数
            maxSubTbCount: 15 //单个视图中明细表最大个数
        },
        //4-属性设置区
        settingArea: {
            //表单属性设置
            formSetting: {
                supportConditionFormat: false, //是否支持条件格式设置
                supportAnchorPoint: false //是否支持视图锚点设置
            },
            //控件属性设置
            ctrlSetting: {
                supportMasterTbName: false, //是否支持主表名设置
                relationObjCustom: false, //是否支持关联对象选项自定义
                supportColumnHide: false //是否支持列隐藏设置
            }
        }
    }
};


表单设计器加载前会先请求扩展脚本，默认请求路径 /seeyon/common/cap4/design/extend.js

extend.js中需要在window上挂载formDesignerExtend配置对象；

设计器全局环境有上述各区域对应的默认配置，读取和校验客开配置生效后，每项有效配置项会替换相应默认配置。CAP各版本支持的配置跟随产品迭代，具体版本支持的完整配置信息参见相应发版说明。


## 特别注意

自定义字体生效前提为当前操作系统已安装该字体，使用的浏览器支持该字体的渲染。

编撰人：yinyanting




快速跳转



 * 设计器能力配置
 * 特别注意



分享链接分享链接

## 31. 如何添加添加字体库？

> 原始路径：`/94/355/359/399/400/402/1337.html`  
> 相对路径：`94/355/359/399/400/402/1337.md`  
> JS Chunk：`app.371b709c.js`

## 如何添加添加字体库？


## 在设计器中没有需要的字体




## 示例

产品自带字体库不够用，根据客户需求增加字体库，比如：增加"和风"字体


## 实现步骤

1、准备好字体库，需要"svg"、"ttf"、"woff"格式的字体文件，如果客户要用到IE浏览器，还需要准备"eot"格式的字体文件； 推荐一个字体转换的网站：https://convertio.co/zh/font-converter/ 特别提醒：部分字体使用是有版权费

2、构建字体目录结构，字体存放路径以及结构如下图所示

 * 字体库扩展目录 /seeyon/common/capextend/cap4/form/utils/customfont（"customfont"文件加可以自己定义）

3、设计器扩展脚本入口，/seeyon/common/cap4/design/extend.js，引入扩展字体库文件index.js,示例如下

window.formDesignerExtend = {
    config: {
        baseCfg: {supportWhitePluginCfg: true, supportDesign: true},
        toolbar: {
            hasInit: false,
            fontFamilyExtend: [['HeFengShuDao', '和风']],
            get fontSizeExtend() {
                if (!this.hasInit) {
                    this.init();
                }
                return [];
            }
            , init: function () {
                //在表单设计器中引入新增字体样式文件
                var fontJS = document.querySelector("#formdesign-frame").contentDocument.createElement('script');
                fontJS.setAttribute('type', 'text/javascript');
                fontJS.setAttribute('async', 'false');
				//引入扩展字体库的index.js文件
                fontJS.setAttribute('src', '/seeyon/common/capextend/cap4/form/utils/customfont/index.js?V=V8_1SP2_230116_1705090');
                document.querySelector("#formdesign-frame").contentDocument.head.appendChild(fontJS);
            }
        }
    }

}


4、index.js代码

function importCss(){
    var url = _ctxPath + '/common/capextend/cap4/form/utils/customfont/customfont.css';
    var conference=document.createElement('link');
    conference.rel = 'stylesheet';
    conference.type = 'text/css';
    conference.href = url;
    document.head.appendChild(conference);
}

importCss();


5、customfont.css引入需要增加的字体库css

@font-face {
    font-family: 'HeFengShuDao';
    src:  url('HeFengShuDao.eot?9ieal7');
    src:  url('HeFengShuDao.eot?9ieal7#iefix') format('embedded-opentype'),
    url('HeFengShuDao.ttf?9ieal7') format('truetype'),
    url('HeFengShuDao.woff?9ieal7') format('woff'),
    url('HeFengShuDao.svg?9ieal7#HeFengShuDao.svg') format('svg');
    font-weight: normal;
    font-style: normal;
}


6、打包，重启

7、效果


## 扩展阅读

客户端安装字体可以参考：https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+NjQ3

编撰人：19912713320




快速跳转



 * 如何添加添加字体库？
   * 在设计器中没有需要的字体
   * 示例
   * 实现步骤
   * 扩展阅读



分享链接分享链接

## 32. 事件API支持

> 原始路径：`/94/355/359/399/400/403.html`  
> 相对路径：`94/355/359/399/400/403.md`  
> JS Chunk：`app.371b709c.js`

## 事件API支持

可以通过上述formDesignerExtend配置对象的event属性介入所需事件。

事件API                 事件描述             支持详情
designerRendered      表单设计器首次渲染完成后通知   v7.1SP1+ [CAP4]
designerTabSwitched   设计器标签页切换事件       v7.1SP1+ [CAP4]
viewTabSwitched       视图切换事件           v7.1SP1+ [CAP4]
viewTableSelected     当前视图表被选中事件       v7.1SP1+ [CAP4]
fieldSwitched         选中字段切换事件         v7.1SP1+ [CAP4]
beforeSaveForm        保存表单前触发          v7.1SP1+ [CAP4]

> 事件配置示例：

//表单设计器事件API
window.formDesignerExtend = {
    event: {
        /*
        * [1-1] 表单设计器首次渲染完成后通知
        * * arguments: Object
        * {
        *    formId: String //表单id
        *    formType: String //表单类型
        *    formBaseInfo: Object //表单基本信息
        * }
        * */
        designerRendered: function(data){
            //todo
        },

        /*
        * [1-2] 设计器标签页切换事件
        * arguments: Object
        * {
        *    fromPage: Number, //切换前页签 eg: 1-表单设计 2-操作设置 3-应用绑定
        *    toPage: Number //切换后页签
        * }
        * */
        designerTabSwitched: function(data){
            //todo
        },

        /*
        * [1-3] 视图切换事件
        * arguments: Object
        * {
        *     formId: String //表单id
        *     fromView: Object //跳转前视图信息 eg:
                  {
                      plat: "pc", 
                      name: "差旅费报销",
                      id: "7681958030234698266"
                   }
        *     toView: Object //跳转后视图信息
        * }
        * */
        viewTabSwitched: function(data) {
            //todo
        },

        /*
        * [1-4] 当前视图表被选中事件
        * arguments: Object
        * {
        *     formId: String //表单id
        *     currentViewId: String //当前视图id
        *     isMater: Boolean //是否为主表
        *     currentTable: Object //选中表信息
        * }
        * */
        viewTableSelected: function(data) {
            //todo
        },

        /*
        * [1-5] 选中字段切换事件
        * arguments: Object 字段信息
        * {
        *   "id": "7966030540684413408",
            "enumInfo": "6875661119798661104_false_0_",
            "display": "二级业务类型描述",
            "type": "select",
            "relation": {},
            "typeText": "下拉",
            "name": "field0052",
            "isCustomCtrl": false,
            "enumName": "主数据业务",
            "fieldType": "DECIMAL",
            "fieldLength": "20,0"
        * }
        * */
        fieldSwitched: function(data) {
            //todo
        },

        /*
        * [1-6] 保存表单前触发
        * arguments: Object
        * {
        *    formId: String //表单id
        *    formType: String //表单类型
        *    curPage: Number //当前页签 eg: 1-表单设计 2-操作设置
        * }
        * return: Boolean //false-不执行表单保存 true-继续原来的表单保存逻辑
        * */
        beforeSaveForm: function(data) {
            //todo
            return true;
        },
        
        /*
        * [2-1] 关联对象列表生成前触发
        * arguments:
        *   fieldInfo [Object] 字段信息
        *   allFieldMap [Object] 所有字段映射信息
        *
        * return:
        *   [Array] 一个字段可以关联的所有字段
        *
        *   eg:
        *   [
        *       { "value": "field0015", "text":"申请人[选人]" },
        *       { "value": "field0016", "text":"供职部门[选部门]" },
        *   ]
        *
        * [注]
        * 1、回调不能包含异步操作
        * 2、若返回值不为标准的字段信息数组，则回调不生效
        * */
        beforeRelationObjRender: function(fieldInfo, allFieldMap) {
            //todo
        }
    }
};


编撰人：yinyanting


快速跳转



 * 事件API支持



分享链接分享链接

## 33. Demo示例

> 原始路径：`/94/355/359/399/400/404.html`  
> 相对路径：`94/355/359/399/400/404.md`  
> JS Chunk：`app.371b709c.js`

## Demo示例


## demo-1 表单设计与流程管理分权


## 需求

表单管理员可以做表单设计、操作设置和应用绑定的切换，流程管理员被表单管理员授权制作流程，但不能设计表单，设计器界面对流程管理员来说需要做表单设计的相关屏蔽处理。


## 解决方法

流程管理员进入表单设计器首个页面时只能预览

window.formDesignerExtend = {
    config: {
        baseCfg: {
            supportDesign: false //是否支持设计器编辑
        }
    }
};


配合URL参数onlyEditWF(仅流程管理员有)解析


## 效果




## demo-2 带条件隐藏表格


## 需求

根据不同的条件隐藏相应的表格（主表区域、明细表）。


## 分析与解决

1.标准产品默认不支持条件格式设置，需要配置对应能力(supportConditionFormat)

2.设置条件后需要选取对应表格，默认不支持主表块的识别（主表区域的唯一名称），故还需要配置设置主表名的能力(supportMasterTbName)

window.formDesignerExtend = {
    config: {
        settingArea: {
            //表单属性设置
            formSetting: {
                supportConditionFormat: true //是否支持条件格式设置
            },
            //控件属性设置
            ctrlSetting: {
                supportMasterTbName: true //是否支持主表名设置
            }
        }
    },
    event: {
        onConditionFormatClick: onConditionFormatClick
    }
};


3.添加条件格式设置窗逻辑

function onConditionFormatClick(data) {
    var defId = data.formId;//表单ID
   var viewId = data.currentView.id;
   if(viewId ==  ""){
    $.alert("请先保存表单");
    return false;
   }
   var plat = data.currentView.plat;
   dialogCondSet = $.dialog({
    width:620,
    height:450,
    targetWindow:getCtpTop(),
    transParams: {
              transData: data,
              winObj : window
          },
    url:_ctxPath + "/ext/formCond.do?method=formConditionHidden&formId="+defId+"&hideType=table&viewId="+viewId+"&plat="+plat,
       title : "视图条件格式设置",
       buttons : [{
         text : $.i18n('common.button.ok.label'),
         id:"doOk",
         isEmphasize: true,
         handler : function() {
          var retValue = dialogCondSet.getReturnValue({"operationId":"doOk"});
          var cssObj = $("<i class='icon CAP cap-icon-duigou' style='color: rgb(126, 211, 33);'></i>");
          if(!$("#formdesign-frame").contents().find(".form-setting-button:eq(2)").find(".cap-icon-duigou").length > 0){
           $("#formdesign-frame").contents().find(".form-setting-button:eq(2)").append(cssObj);
          }
         }
       },{
          text : $.i18n('common.button.empty.label'),
          id:"deleteAndExit",
       isEmphasize: true,
          handler : function() {
           var retValue = dialogCondSet.getReturnValue({"operationId":"deleteAndExit"});
           $("#formdesign-frame").contents().find(".form-setting-button:eq(2)").find(".cap-icon-duigou").remove();
          }
        },{
         text : $.i18n('common.button.cancel.label'),
         handler : function() {
          dialogCondSet.close();
         }
       } ]
   });
}



## 效果




## demo-3 带条件隐藏明细表列


## 需求

根据不同的条件隐藏某个明细表的指定列。


## 分析与解决

1.默认不支持列隐藏设置，需要配置对应能力(supportColumnHide)

2.对于已设置列隐藏后的明细表，选中时需要标识是否已经设置过，即在表格选中事件(viewTableSelected)触发时更新其样式

window.formDesignerExtend = {
    config: {
        settingArea: {
            //控件属性设置
            ctrlSetting: {
                supportColumnHide: true //是否支持列隐藏设置
            }
        }
    },
    event: {
     viewTableSelected: viewTableSelectedFn
        onTableColumnHideClick: onTableColumnHideClick
    }
};


3.onTableColumnHideClick中实现列隐藏设置逻辑，viewTableSelectedFn中添加列隐藏按钮样式更新逻辑

function viewTableSelectedFn(data,obj){
    var cssObj = $("<i class='icon CAP cap-icon-duigou' style='color: rgb(126, 211, 33);'></i>");
    var formId = data.formId;
    var viewId ="";
    var platForm="";
    if(obj && "tabSwitch" == obj){
        viewId = data.toView.id;
        platForm = data.toView.plat;
    }else{
        viewId = data.currentView.id;
        platForm = data.currentView.plat;
    }
    //是否已经设置隐藏列
    callBackendMethod("capExtendManager","getCssSet",formId,viewId,platForm,"","",{
        success : function(returnList){
         var $btn = $("#formdesign-frame").contents().find(".form-setting-button:eq(2)");
            if(returnList.columnHidden == "true"){
                $btn.append(cssObj);
            }else if(returnList.columnHidden == "false"){
                $btn.find(".cap-icon-duigou").remove();
            }
        }
    });
}

function onTableColumnHideClick(data){
    var defId = data.formId;//表单ID
    var viewId = data.currentView.id;
    var detailTableName = data.currentTable.tableName;
    if(viewId ==  ""){
        $.alert("请先保存表单");
        return false;
    }
    var colArray = data.currentTable.cells;
    if(colArray.length > 0 && colArray[0].rowIndex == 1){
        $.alert("请先设置表头信息");
        return false;
    }
    var plat = data.currentView.plat;
    dialogCondSet = $.dialog({
        width:620,
        height:450,
        targetWindow:getCtpTop(),
        transParams: {
            transData: data,
            winObj : window
        },
        url:_ctxPath + "/ext/formCond.do?method=formConditionHidden&formId="+defId+"&hideType=column&" +
            "viewId="+viewId+"&plat="+plat+"&detailTableName="+detailTableName,
        title : "隐藏列设置",
        buttons : [{
            text : $.i18n('common.button.ok.label'),
            handler : function() {
                var retValue = dialogCondSet.getReturnValue({"operationId":"doOk"});
                var cssObj = $("<i class='icon CAP cap-icon-duigou' style='color: rgb(126, 211, 33);'></i>");
                if(!$("#formdesign-frame").contents().find(".ctrl-setting-button").find(".cap-icon-duigou").length > 0){
                    $("#formdesign-frame").contents().find(".ctrl-setting-button").append(cssObj);
                }
            }
        },{
            text : $.i18n('common.button.empty.label'),
            id:"deleteAndExit",
            isEmphasize: true,
            handler : function() {
                var retValue = dialogCondSet.getReturnValue({"operationId":"deleteAndExit"});
                $("#formdesign-frame").contents().find(".ctrl-setting-button").find(".cap-icon-duigou").remove();
            }
        },{
            text : $.i18n('common.button.cancel.label'),
            handler : function() {
                dialogCondSet.close();
            }
        } ]
    });
}



## 效果



编撰人：yinyanting、het


快速跳转



 * Demo示例
   * demo-1 表单设计与流程管理分权
     * 需求
     * 解决方法
     * 效果
   * demo-2 带条件隐藏表格
     * 需求
     * 分析与解决
     * 效果
   * demo-3 带条件隐藏明细表列
     * 需求
     * 分析与解决
     * 效果



分享链接分享链接

## 34. 介绍

> 原始路径：`/94/355/359/399/405/`  
> 相对路径：`94/355/359/399/405/README.md`  
> JS Chunk：`app.371b709c.js`

## 介绍

A.使用说明

针对一定范围内的高频应用场景，提供在运行态中制作插件包的方法步骤以及各类客开化接口，为客体的定制化开发提供支持。

B.版本支持
   7.1sp1+



## 章节内容

1.表单插件制作步骤；

2.表单插件接口分类详细说明；

3.具体的Demo示例；

4.插件扫描和加载机制（了解）

编撰人：yinyanting




快速跳转



 * 介绍
 * 章节内容



分享链接分享链接

## 35. 插件使用步骤

> 原始路径：`/94/355/359/399/405/406.html`  
> 相对路径：`94/355/359/399/405/406.md`  
> JS Chunk：`app.371b709c.js`

## 插件使用步骤

步骤如下

1.添加插件目录及资源

1）如制作一个cap4表单插件，则对应目录为

/seeyon/common/capextend/cap4/form/utils （多端应用及白名单插件目录详见2-4说明）

在该目录下添加pluginA（插件名）文件夹

2）在pluginA中添加脚本index.js和index.css

2.需求对应脚本实现

如需求为表单加载完成后请求后台某自动处理任务，index.js增加实现代码：

//客开脚本初始化
//do something
function autoTaskRequest() {
    $.ajax({
        url: "seeyon/autoTaskBusiness/customTask2",  
        type: "post",
        data: {param: 0},
        success: function(){}
    }); 
}
csdk.event.on('formRendered', function (data) {
    autoTaskRequest();
});


3.需求对应样式实现

如index.css中实现鼠标悬浮按钮上倾斜效果：

/*基础样式*/
.custom-button {
    color: #fff;
}
/*悬浮样式*/
.custom-button:hover {
    color: blue;
    -webkit-transform: rotate(5deg);
    transform: rotate(5deg);
}


编撰人：yinyanting


快速跳转



 * 插件使用步骤



分享链接分享链接

## 36. 表单插件接口

> 原始路径：`/94/355/359/399/405/407/`  
> 相对路径：`94/355/359/399/405/407/README.md`  
> JS Chunk：`app.371b709c.js`

## 表单插件接口

目前提供插件使用的接口分为三类：

1.事件接口；

2.钩子相关接口；

3.表单操作接口


## 特别注意

使用CSDK调用API时，对有回调的接口，必须等上一个接口返回才能调下一个。
例如，循环addRecord是不合理的操作，对于addRecord等需要操作多次的，正确的做法是调用addRecords，如果需要多次使用addRecord或deleteRecord时，则等上一个请求调用完成再调用下一个。

编撰人：yinyanting




快速跳转



 * 表单插件接口
 * 特别注意



分享链接分享链接

## 37. 事件接口

> 原始路径：`/94/355/359/399/405/407/408.html`  
> 相对路径：`94/355/359/399/405/407/408.md`  
> JS Chunk：`app.371b709c.js`

## 事件接口

表单生命周期中关键节点会对外触发事件，可通过csdk.event.on接口对特定事件进行监听，当事件被触发 时，会进入到使用者注册的回调中。 事件与钩子都允许注册多次。它们的区别在于，每个事件回调相互独立，事件参数彼此不影响，而钩子在处理函数中会有操作修改上下文数据context的场景，同一个钩子被注册多次时，会共享一份上下文数据。

事件名称            事件描述                                                               支持详情
formRendered    表单第一次渲染完成后通知                                                       v7.1SP1+ [CAP4、CAP3]
viewRendered    视图渲染完成的事件，在表单视图切换后都会触发此事件                                          v7.1SP1+ [CAP4]
fieldChanged    字段值发生变更后通知的事件                                                      v7.1SP1+ [CAP4、CAP3]
formUpdated     视图渲染发生更新后通知的事件，在字段值改变时、关联计算、明细行操作后都会触发此事件                          v7.1SP1+ [CAP4、CAP3]
recordUpdated   明细行渲染完成后通知的事件。此事件只在CAP4移动端轻表单新建或编辑明细行，打开明细行新webview时，明细行渲染完成时才触发   v7.1SP1+ [CAP4]
recordAdded     明细行添加完成                                                            v7.1SP1+ [CAP4]
recordCopied    明细行复制完成                                                            v7.1SP1+ [CAP4]
recordDeleted   明细行删除完成                                                            v7.1SP1+ [CAP4]

示例

function handler(e) {
    //do something
}  
var removeHandler = csdk.event.on('formRendered', handler); 
//移除事件  
removeHandler();


编撰人：yinyanting


快速跳转



 * 事件接口



分享链接分享链接

## 38. 钩子相关接口

> 原始路径：`/94/355/359/399/405/407/409.html`  
> 相对路径：`94/355/359/399/405/407/409.md`  
> JS Chunk：`app.371b709c.js`

## 钩子相关接口

在表单生命周期中，可通过注册钩子实现劫持表单流程，钩子中传入上下文数据，可在此时通过修改上下文数据从而 实现改变表单渲染样式。 同一个钩子被注册多次时，会共享一份上下文数据context，按照钩子注册的先后顺序调 用，由于context为对象引用，那么存在多处对context进行修改时，可能会有数据被覆盖的风险。

钩子名称                描述                                                                       支持详情
beforeFormRequest   用于请求表单数据前，通过劫持参数，修改参数从而实现请求到特定表单数据的能力。传入的上下文数据context为请求表单的参数            v7.1SP1+[不支持CAP3 PC端]
beforeFormRender    用于表单渲染前，通过修改表单viewContent数据，从而实现表单渲染样式发生改变的能力。传入的上下文数据context为表单视图描述数据   v7.1SP1+[不支持CAP3 PC端]

示例

function handler(context) {
//注意，此处context为传入的上下文数据，直接修改context可对视图渲染样式产生影响
//do something
}  
csdk.hook('beforeFormRender', handler);


编撰人：yinyanting


快速跳转



 * 钩子相关接口



分享链接分享链接

## 39. 表单操作相关接口

> 原始路径：`/94/355/359/399/405/407/410.html`  
> 相对路径：`94/355/359/399/405/407/410.md`  
> JS Chunk：`app.371b709c.js`

## 表单操作相关接口

csdk.core里面封装了对表单数据操作的各种常用接口

> 


## csdk.core.getFieldData

说明                                  参数                             返回值   支持详情
获取表单指定字段的数据，如果只主表只需要传入fieldId                                            
参数，如果是明细表，还需要传入tableName和recordId
[注]必须在表单事件、钩子内使用                    {fieldId,tableName,recordId}         

fieldId { string } 字段id，如field0001
tableName { string } 明细表名
recordId { string } 明细表行记录id | data { object } | v7.1SP1+ [CAP4、CAP3] |

示例

//获取主表字段为field0001的数据
var opts = {fieldId: 'field0001'};
var data = csdk.core.getFieldData(opts);
//获取明细表formson_0001，明细行记录号为987654321，并且字段为field0001的数据
opts = {
    fieldId: 'field0001', 
    tableName:'formson_0001', 
    recordId:'123456789'
  }; 
var data = csdk.core.getFieldData(opts);


> 


## csdk.core.getFormData

说明          参数   返回值               支持详情
获取整个表单的数据   空    data { object }   v7.1SP1+ [CAP4、CAP3]

示例

var data = csdk.core.getFormData();
//注意，此接口涉及到大量数据克隆，使用时千万不要高频次调用


> 


## csdk.core.getMetaData

说明                                           参数   返回值                   支持详情
获取表单，affairId，templateId，moduleId以及视图权限等信息   空    metaData { object }   v7.1SP1+ [CAP4、CAP3]

示例

var metaData = csdk.core.getMetaData();
//metaData格式如下
{
    rightId, //权限id
    moduleId, //有流程的时候为summaryId，无流程中为主数据Id，即contentDataId
    moduleType, //值为'1'，'42'等
    contentDataId, //表单主数据Id
    contentTemplateId, //表单定义信息id，后台form bean的id，即模板id
    moduleTemplateId, //应用绑定id
    //affairId属性只在有流程中存在
    affairId //个人待办Id
}


> 


## csdk.core.getSubmitData

说明                                        参数   返回值               支持详情
获取需要提交到后台的表单数据，此数据是经过瘦身的数据，key，value的格式   空    data { object }   v7.1SP1+ [CAP4、CAP3]

示例

var submitData = csdk.core.getSubmitData();


> 


## csdk.core.setFieldData

 * **参数：**csdk.core.setFieldData(data) data={fieldId, fieldData, tableName?, recordId?}或[{fieldId, fieldData, tableName?, recordId?}] @param data { object |Array } 需要设置的字段对象值，格式为数组或对象，如果传入的是数组，即同时对多个字段进行值的设置，如果传入的单个对象，即值设置一个字段的值 data.fieldId { string } 字段id，如field0001 data.fieldData { object } 设置的字段数据，对象格式，可以设置value、display、auth等属性，下述例子有说明 data.tableName { string } 明细表名，主表不需要传入此参数 data.recordId { string } 明细表行记录id，主表不需要传入此参数
 * **返回值：**undefined
 * **说明：**设置表单字段数据，可以是一个字段或者多个字段一起设置。fieldData仅支持的字段属性为“value”， “display”， “placeHolder”， “auth”， “atts”，详细说明参照下述示例
 * **支持版本：**v7.1SP1+    [CAP4、CAP3]
 * 示例：

var data = {
    fieldId: 'field0001',
    fieldData: {
      value: '2019-05-01', //数据值，存入数据库中的value值
      display: '2019年5月1日', //字段渲染在页面上的显示值，通常是经过format后的值
      placeHolder: '请选择日期', //input或其它控件输入提示语
      auth: 'browse', //字段权限，只能修改为browse(浏览)或hide(隐藏)，
      //如果被设置字段是必填且为空时，不能修改字段权限
      atts:[] //图片、文档、附件等附件类型字段的附件信息
    } 
};
//设置单个主表字段值
csdk.core.setFieldData(data);
//设置单个明细表字段值 
var data = {
      fieldId: 'field0010',
    tableName: 'formson_0001',
    recordId: '123456789',
    fieldData: {...}
};
var data = [ {
        fieldId: 'field0001',
        fieldData: {...}
    },
    {
        fieldId: 'field0010',
        tableName: 'formson_0001',
        recordId: '123456789',
        fieldData: {...}
} ];
//同时设置多个字段值 
csdk.core.setFieldData(data);


> 


## csdk.core.patchData

说明                                                                参数                              返回值         支持详情
根据后台接口返回的data数据，更新表单前端渲染视图，注意，此接口使用的数据一定是经过后台接口返回的格式，并且格式不能随意修改   data { object } 参照后台接口返回的数据格式   undefined   v7.1SP1+ [CAP4、CAP3]

示例

$.ajax({
    url,
    ...,
    success(res) {
      //这里通过后台接口拿到数据，直接将原始数据格式传入patchData   
      csdk.core.patchData(res.data);
  }
});
//后台接口返回的回填主表的数据格式 
{
	"code": 0,
	"data": {
		"code": "2000",
		"data": {
			"tableData": {
				"formmain_0039": {
					"update": {
						"field0008": {
							"showValue": "11",
							"showValue2": "11",
							"relationData": {
								"imgShow": "1",
								"viewThrough": "1",
								"toMasterDataId": "5349687614034585905"
							},
							"relationInfo": {
								"toFormType": "42",
								"fillInRow": "0",
								"buttonName": "插入文本1",
								"pcView": "2955061720904059008.-7526562575306899268",
								"relationShipId": "-4677381009382161664",
								"phoneView": "-3291413942012787928.-79988990681201604",
								"mainSelector": "field0008",
								"fieldInfo": "field0008",
								"mainSelectorDisplay": "文本1",
								"toVersion": "default_form"
							},
							"value": "11"
						}
					}
				}
			}
		},
		"message": "the operation is success!!!"
	},
	"message": ""
}

//后台接口返回的回填明细表的数据格式 
{
	"code": 0,
	"data": {
		"code": "2000",
		"data": {
			"tableData": {
				"formson_0064": {
					"update": {
						"-2826325192640280451": {
							"field0021": {
								"showValue": "11",
								"showValue2": "11",
								"value": "11"
							}
						}
					}
				}
			}
		},
		"message": "the operation is success!!!"
	},
	"message": ""
}



> 


## csdk.core.preSave

说明                                              参数                                                                             返回值         支持详情
预提交接口，调用此接口时，表单会向后台请求预提交数据接口，待后台响应完成后再通过回调通知使   callback { Function }                                                          undefined   v7.1SP1+ [CAP4、CAP3]
用者，无论是成功或失败都会进入回调                               调用预提交时传入的回调函数，无论成功与否都进入此回调，接收两个参数err和data，第一个参数err为null时表示成功，如果err不为null表示失败

示例

csdk.core.preSave(function(err, data){
    if (err) {
     //调用失败
     return; 
    }
  //调用成功
    //do something
});


> 


## csdk.core.getSelectedRecord

说明                               参数                           返回值                 支持详情
获取指定明细表当前选中行记录，如果没有选中的记录返回null   tableName { string } 明细表表名   record { object }   v7.1SP1+ [CAP4、CAP3]

示例

var tableName = 'formson_001'; 
//获取明细表formson_001当前选中行
var curRecord = csdk.core.getSelectedRecord(tableName);


> 


## csdk.core.deleteRecord

说明                                                                             参数                                          返回值   支持详情
删除目标明细表指定行记录，如果records为true表示删除所有行。此API涉及到后台接口调用，因此在调用过程中会弹出遮罩，调用完成进入回调后遮罩关闭   csdk.core.deleteRecord(options, callback)         

options={ tableName, records}
options { object } 第一个参数为options对象格式
tableName { string } 明细表表名
records { Array或Boolean } 待删除的明细行记录id集合，如果records为Boolean，并且为true，则表示删除所有行，否则为 Array，如['123456789']
callback { Function } 删除记录成功或失败的回调
callback接收参数:callback(err)
err { null 或 object}:错误信息 | undefined | v7.1SP1+ [CAP4、CAP3] |

示例

var tableName = 'formson_001';
//删除明细表formson_001所有行记录
csdk.core.deleteRecord({tableName: tableName, records: true}, function(err){
  if (err) { //删除失败
    return; 
  }
  //删除成功
  //do something
});
//删除明细表formson_001当前选中行
var curRecord = csdk.core.getSelectedRecord(tableName);
var curRecordId = curRecord ? (curRecord.id || curRecord.recordId): null;
csdk.core.deleteRecord({tableName: tableName, records: [curRecordId]}, function(err){
  if (err) { //删除失败
    return; 
  }
  //删除成功
  //do something
});


> 


## csdk.core.addRecord

说明                                                                                                                        参数        返回值   支持详情
添加一行空记录到目标明细表指定位置，如果posRecordId为null表示添加到明细表末尾，如果posRecordId有效，则添加到目标行的下一行位置。此API涉及到后台接口调用，因此在调用过程中会弹出遮罩，调用完成进入回调后遮罩关闭。   opts ：{         

tableName,
posRecoedId,
records: {}
}
callback(err,newRecord) err { null 或 object} 错误信息
newRecord {object } 返回新增的行记录，newRecord.id是后台接口分配的行id号 | undefined | v7.1SP1+ [CAP4、CAP3]
支持多行插入：v8.0+（或v7.1SP1 930+补丁包） |

示例

var tableName = 'formson_001'; //在明细表formson_001末尾添加一行空行
var opts = {
    tableName: tableName,
    posRecordId: null
};
csdk.core.addRecord(opts, function(err, newRecord){
    if (err) {
      //添加失败
      return; 
    }
//添加成功，取得新记录的id
var newRecordId = newRecord.id || newRecord.recordId;
  //do something
});
//添加一行空行到到明细表formson_001当前选中行后面
var curRecord = csdk.core.getSelectedRecord(tableName); 
var curRecordId = curRecord ? (curRecord.id || curRecord.recordId) : null;
opts = {
    tableName: tableName,
    posRecordId: curRecordId,
};
csdk.core.addRecord(opts, function(err, newRecord){
    if (err) {
      //添加失败
      return; 
    }
//添加成功，取得新记录的id
var newRecordId = newRecord.id || newRecord.recordId;
  //do something
});


> 


## csdk.core.copyRecord

说明                                                                                                                                                              参数                                        返回值   支持详情
复制一行记录到目标明细表指定位置，copyRecordId是被复制的行记录号，copyRecordId在记录中找不到或非法，则提示找不到被复制的行记录。posRecordId的作用同接口csdk.core.addRecord一致。此API涉及到后台接口调用，因此在调用过程中会弹出遮罩，调用完成进入回调后遮罩关闭。   csdk.core.copyRecord(options, callback)         

options={ tableName, copyRecordId, posRecordId}
options { object } 第一个参数为options对象格式
tableName { string } 明细表表名
copyRecordId { string } 被复制的行记录号
posRecordId { string 或 null } 新增的明细行插入的 位置，posRecordId为空，则插入到明细表末尾，否则插入到目标位置的下一行
callback { Function } 复制行记录成功或失败的回调 | undefined | v7.1SP1+ [CAP4、CAP3] |

示例

var tableName = 'formson_001';
var curRecord = csdk.core.getSelectedRecord(tableName);
var curRecordId = curRecord ? (curRecord.id || curRecord.recordId) : null;
var opts = {
    tableName: tableName,
    copyRecordId: curRecordId,
    posRecordId: null,
};
//拷贝明细表formson_001当前选中的行并添加到明细表末尾 
csdk.core.copyRecord(opts, function(err, newRecord){
if (err) { 
  //拷贝失败
  return; 
}
//拷贝成功，取得新记录的id
var newRecordId = newRecord.id || newRecord.recordId; 
  //do something
});
//拷贝明细表formson_001当前选中的行并添加到当前选中行后面 
opts = {
    tableName: tableName,
    copyRecordId: curRecordId,
    posRecordId: curRecordId,
};
csdk.core.copyRecord(opts, function(err, newRecord){
if (err) { 
  //拷贝失败
  return; 
}
//拷贝成功，取得新记录的id
var newRecordId = newRecord.id || newRecord.recordId;
  //do something
});


编撰人：yinyanting、lixianhong


快速跳转



 * 表单操作相关接口
   * csdk.core.getFieldData
   * csdk.core.getFormData
   * csdk.core.getMetaData
   * csdk.core.getSubmitData
   * csdk.core.setFieldData
   * csdk.core.patchData
   * csdk.core.preSave
   * csdk.core.getSelectedRecord
   * csdk.core.deleteRecord
   * csdk.core.addRecord
   * csdk.core.copyRecord



分享链接分享链接

## 40. Demo示例

> 原始路径：`/94/355/359/399/405/411.html`  
> 相对路径：`94/355/359/399/405/411.md`  
> JS Chunk：`app.371b709c.js`

## Demo示例


## demo-1 视图锚点（anchor）


## 需求

在表单视图上点击表格（主表区域、明细表）后跳转至对应位置。


## 分析与解决

1.添加anchor插件目录及资源

[注]7.1SP1 930版本前的表单插件路径为/seeyon/common/cap4/extend



2.脚本实现

//添加表单渲染完成和视图渲染完成事件
var removereadyAnchorFun = csdk.event.on("formRendered", readyAnchorFun);
var removeViewChangeAnchorFun  = csdk.event.on("viewRenderd", viewChangeAnchorFun);
function readyAnchorFun(){
 var metaData = csdk.core.getMetaData();
 var formId = metaData.contentTemplateId;
 var viewId = metaData.viewId;
 callBackendMethod("anchorPointSettingManager","findAnchorPointSettingbyViewIdFormId",formId,viewId,{
  success : function(returnList){
   if(window.parent.location.href.indexOf("summary") >= 0 ){
    summaryFlag = true;
   }
   anchorPointRender(returnList);
        },
        error : function(request, settings, e){
            $.alert(e);
        }
 });
}
function viewChangeAnchorFun(){
 if(summaryFlag){
  top.$(".anchor-point-wrap").remove();
  top.$(".anchor-point-wrap").remove();
 }else{
  $(".anchor-point-wrap").remove();
  $(".anchor-point-wrap").remove();
 }
 readyAnchorFun();
}
function anchorPointRender(tables) {
    if("array" !== $.type(tables) || !tables.length) {
        return;
    }
    var tplArray = ['<div class="anchor-point-wrap"><div class="ap-content"><div class="ap-content-top"></div>'];
    tables.forEach(function(item) {
        tplArray.push('<div class="ap-item" onclick="scrollAnchor(this)" data-id="' + item.fromTableName + '" title="' + item.anchorPointName + '">' + item.anchorPointName + '</div>');
    });
    tplArray.push('</div></div><div class="anchor-point-pos" title="锚点列表"></div>');
    if(summaryFlag){
     $(tplArray.join('')).appendTo(parent.$("body"));
     //处理锚点悬浮按钮位置
     var bottom =  parseInt(top.$("#goToReply").css("bottom"));
     var left =  parseInt(top.$("#goToReply").css("left"));
     top.$(".anchor-point-pos").css("bottom",bottom + 82);
     top.$(".anchor-point-pos").css("left",left);
     //处理锚点列表位置
     top.$(".anchor-point-wrap").css("bottom",bottom + 82 +38);
     top.$(".anchor-point-wrap").css("left",left);
     top.$(".anchor-point-wrap").css("right","auto");
     
    }else{
     $(tplArray.join('')).appendTo('body');
    }
}


3.样式实现

.anchor-point-wrap {
    position: fixed;
    border-top: 5px solid #1F85EC;
    bottom: 100px;
    right: 1px;
    box-shadow: 1px 1px 10px 1px rgba(0, 0, 0, 0.3);
    z-index:10;
    background-color: #fff
}
.anchor-point-wrap.hide {
    display: none;
}
.anchor-point-wrap .ap-content {
    min-width: 50px;
    max-width: 136px;
    padding: 20px 0 10px;
}
.ap-content-top {
    position: absolute;
    top: 1px;
    right: 0;
    width: 20px;
    height: 20px;
    cursor: pointer;
    background: url(images/custom-modal-min.png) no-repeat right center;
}
.ap-content .ap-item {
    height: 30px;
    line-height: 30px;
    padding: 0 10px;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
}
.ap-content .ap-item:hover {
    cursor: pointer;
    background-color: #D1E8FD;
}

.ap-content .selected-item {
    background-color: #D1E8FD;
}

.anchor-point-pos {
    position: fixed;
    width: 36px;
    height: 36px;
    bottom: 60px;
    right: 40px;
    cursor: pointer;
    z-index: 2;
    border-radius: 50%;
    background: url(images/custom-pos.png) no-repeat center center;
}
.anchor-point-pos:hover {
    background: url(images/custom-pos-hover.png) no-repeat center center;
}



## 效果




## demo-2 带条件隐藏明细表列


## 需求

根据不同的条件隐藏某个明细表的指定列。


## 分析与解决

1.添加插件目录及资源

同demo1，在utils目录下添加columnHidden目录;由于不需要额外的样式实现，故只需添加脚本index.js

2.脚本实现

var filedChangeArray; //参与设计态隐藏行或者列的条件字段数组
var readyFun = function () {
    var pageDataObj = csdk.core.getFormData().metaData;
    filedChangeArray = pageDataObj.extend.conditionHidden.condtionSet;
    var handlerFun = function (fieldArray) {
        for (var m = 0; m < fieldArray.length; m++) {
            var fieldObj = fieldArray[m];
            var fieldId = fieldObj.id;
            var isCaculate = fieldObj.isInCalculate;
            if (isCaculate == "1") {
                return; //只要含有计算字段  cap4会合并缓存 同事拿隐藏规则进行隐藏 不需要客开再次处理
            }
        }
        for (var m = 0; m < fieldArray.length; m++) {
            var fieldObj = fieldArray[m];
            var fieldId = fieldObj.id;
            var index = $.inArray(fieldId, filedChangeArray);
            if (index >= 0) {
                //1:合并缓存 2：ajax请求设计态该视图下设置的的数据
                var transData = csdk.core.getSubmitData();
                var transObj = new Object();
                var metaData = csdk.core.getMetaData();
                transObj.formId = metaData.contentTemplateId;
                transObj.viewId = metaData.viewId;
                transObj.formMasterId = metaData.contentDataId;
                transObj.rightId = metaData.rightId;
                transObj.platForm = "pc";
                var returnMap = callBackendMethod("capExtendManager", "executeHidden", transObj, transData);
                filedChangeArray = returnMap.condtionSet;
                var transObj = {
                    "hiddenResult": returnMap.hiddenResult
                }
                csdk.core.backfillTableAuth(transObj);
                break;
            }
        }
    };
    //字段值改变事件
    var removeFieldChangeFun = csdk.event.on("fieldChanged", handlerFun);
};

//渲染完成事件
var removeRederFun = csdk.event.on("formRendered", readyFun);
//切换视图事件
function viewChangeFun() {
    var pageDataObj = csdk.core.getFormData().metaData;
    filedChangeArray = pageDataObj.extend.conditionHidden.condtionSet;
}
var removeViewChangeFun = csdk.event.on("viewRenderd", viewChangeFun);


编撰人：yinyanting、het


快速跳转



 * Demo示例
   * demo-1 视图锚点（anchor）
     * 需求
     * 分析与解决
     * 效果
   * demo-2 带条件隐藏明细表列
     * 需求
     * 分析与解决



分享链接分享链接

## 41. 表单运行态插件机制

> 原始路径：`/94/355/359/399/405/412.html`  
> 相对路径：`94/355/359/399/405/412.md`  
> JS Chunk：`app.371b709c.js`

## 表单运行态插件机制

插件扫描与加载

A8系统启动时会扫描通用插件目录(utils)下脚本、样式等资源并加载。

客开插件资源放置路径

应用端   插件资源路径
PC    /seeyon/common/capextend
微协同   /seeyon/m3/apps/v5/capextend
M3    /seeyon/m3files/v5/88.zip

[注]7.1SP1 930版本前的表单插件路径为/seeyon/common/cap4/extend

目录结构 PC端插件目录结构如下图（微协同和M3的类似）



form、query、unflow、todo，分别表示表单、查询列表、无流程列表、待办列表

如表单插件命名为pluginA，则pluginA目录下添加的脚本和样式资源均会被加载

以请求pluginA插件index.js为例，多端请求路径如下

应用端        请求路径
cap4 PC    /seeyon/common/capextend/cap4/form/utils/pluginA/index.js
cap3 PC    /seeyon/common/capextend/cap3/form/utils/pluginA/index.js
cap4 微协同   /seeyon/m3/apps/v5/capextend/cap4/form/utils/pluginA/index.js
cap3 微协同   /seeyon/m3/apps/v5/capextend/cap3/form/utils/pluginA/index.js
cap4 M3端   http://capextend.v5.cmp/v/cap4/utils/pluginA/index.js
cap3 M3端   http://capextend.v5.cmp/v/form/utils/pluginA/index.js

在M3端，capextend构建出来为88.zip
客开需要将M3上的插件统一放置到88.zip中，目录结构跟微协同上路径一致        


白名单插件

1、白名单插件目录与普通插件目录同级。

如cap4普通插件对应目录/seeyon/common/capextend/cap4/form/utils/

则白名单插件目录为/seeyon/common/capextend/cap4/form/whiteList/

2、默认不会加载白名单插件相应资源，需要在设计器高级配置中设置。

白名单表：cap_form_plugin_whitelist

插件资源重新扫描

新制作完插件或者修改插件资源后需要系统重新扫描后才能生效，不通过重启服务的方式为 在已登录的浏览器访问地址 IP:端口/seeyon/rest/cap4/form/initFormPlugins

插件资源加载

1、调用插件加载时，请求路径为：

/seeyon/rest/cap4/form/pluginScripts

2、表单加载参数：（moduleId，moduleType） /seeyon/rest/cap4/form/pluginScripts?page=form&v=cap4&client=pc&moduleId=6902010891055746387&moduleType=1

3、其他加载参数：（bussId，appId，formId） /seeyon/rest/cap4/form/pluginScripts?page=unflow&v=cap4&client=pc&bussId=6902010891055746387&appId=8697407549015999331&formId=-4281519914682530682

page类型："form", "unflow", "query", "todo"

v版本："cap4", "cap3"

client："pc", "wx", "m3"

编撰人：yinyanting




快速跳转



 * 表单运行态插件机制



分享链接分享链接

## 42. 介绍

> 原始路径：`/94/355/359/399/413.html`  
> 相对路径：`94/355/359/399/413.md`  
> JS Chunk：`app.371b709c.js`

## 介绍

A.使用说明

此规范用于第三方对表单进行定制化开发满足标准开发未满足的需求

B.版本支持

文档默认是v7.0sp2开始支持，新增内容会备注开始支持版本号，删除内容会备注顶用版本号



## 提供的API载体（window.thirdPartyFormAPI）

该全局对象是第三方事件处理的载体，主要包括事件池和功能api两部分。


## 1 表单事件池操作

可用作注册事件和触发事件


属性              说明     参数
registerEvent   注册事件   key:事件名称，fn：回调函数
triggerEvent    触发事件   key:事件名称，params：回调参数

注：事件触发是做扩展用，第三方可在事件池中自定义事件并自己触发事件，但是表单内部提供的监听等不需要第三方去触发

 * 事件池注册示例：

// 注册事件
    window.thirdPartyFormAPI.registerEvent('key', function(params){
        // params 接收参数
    });

    // 触发事件
    window.thirdPartyFormAPI.triggerEvent('key', params);


## 1.1 表单中控件失去焦点后触发事件（afterFormFieldChange）

第三方开发要注册此方法


// 注册事件
    window.thirdPartyFormAPI.registerEvent('afterFormFieldChange', function(params){
    ...//params是当前失去焦点的控件的数据
    //如果需要获取主表或明细表数据可用功能api中的getFormData获取
    });

    // params 是一个对象（当前变化控件数据）




/**
   * 说明：这是获取的前端控件数据对象（Object），是具体每个字段的说明
   * 
   * */
  {
    attachmentInfo : 附件信息 （里面包含附件列表和基础附件信息）
    attrs : 视图里面的简单控件信息
    auth: 权限 (‘edit’ : 编辑，’hide’: 隐藏)
    ctrlType : 视图里面的控件状态（这个，自定义控件的是"suiCustomControl"）
    customFieldInfo ： 自定义控件的信息，里面包含pc，移动的js信息和入口方法信息，路径信息。
    digitNum : 小数位长度
    display : 控件名
    enums : 控件的枚举列表
    extra ：设计器给控件设置的样式信息
    fieldLength ：控件内字符的限制长度
    fieldType ：字段类型
    formType ： 控件所在的表的类型
    formatType ： 数据格式
    id ：字段名
    inputType ：控件类型（标准控件判断）
    isInCalculate ： 是否计算（1为计算）
    isInCondition ： 是否是条件字段
    isNotNull ： 必填校验（1为必填）
    isCustomFiled : 是否是自定义控件（1是自定义控件）
    placeHolder ： 提示语言
    radioAlignType ： 
    relation : 关联信息（控件公用的基础信息）
    relationData : 当前控件的关联数据 
    showValue ： 显示值
    value : 计算值
    type : 类型
    valueId : 值
  }


## 1.2 表单中控件双击后触发事件（formFieldDbclick）

第三方开发要注册此方法


// 注册事件
    window.thirdPartyFormAPI.registerEvent('formFieldDbclick', function(params){
    ...//params是当前失去焦点的控件的数据
    //如果需要获取主表或明细表数据可用功能api中的getFormData获取
    });


## 1.3 表单中控件右键后触发事件（formFieldContextmenu）

第三方开发要注册此方法


/**
     * 参数：params => (Object) 失去焦点的控件数据
     * */
    // 注册事件
    window.thirdPartyFormAPI.registerEvent('formFieldContextmenu', function(params){
    ...//params是当前失去焦点的控件的数据
    //如果需要获取主表或明细表数据可用功能api中的getFormData获取
    });


 * 注意：标准接口代码中不会去阻止浏览器右键默认事件，如果希望阻止浏览器右键默认弹出框可以用该接口返回参数中的event完成，如下

/**
     * 参数：params => (Object) 右键的控件数据
     * */
    window.thirdPartyFormAPI.registerEvent('formFieldContextmenu', function(params){
        if (params.event) {
            params.event.preventDefault();
        }
    });



## 2 表单提供的功能api

可以操作表单内部回填等功能，事件触发为同步。

属性                        说明            参数                   详细介绍
getFormData               获取表单数据        fn：回调函数(可不传，为可选参数)   2.1
backfillFormControlData   回填数据          data                 2.2
backfillFormAttachment    回填附件，图片       data                 2.3
changeFormFieldAuth       改变控件权限        params               2.4
getChooseFormsonRecord    获取页面内明细表选中行   无参数                  2.5
insertFormsonRecords      新增明细行         params               2.6
copyFormsonRecods         复制明细行         params               2.7
deleteFormsonRecods       删除明细行         params               2.8

## 2.1 getFormData(fn)

/**
   * 说明：获取当前表单的数据
   * 参数：result => (Object)
   *           {
   *              formData : {}， // 表单数据
   *              formmains ：{}， // 主表数据
   *              formsons : {} // 明细表数据
   *           }
   * 
   * */
  // 直接返回值
  window.thirdPartyFormAPI.getFormData();
  // 传入回调方法，值进入回调方法
  window.thirdPartyFormAPI.getFormData(function(result) {
    // result 是返回的数据
  });




## 2.2 backfillFormControlData(data)

/**
   * 示例：
   * 说明：此接口是用于自定义控件回填表单其他控件数据
   * 参数：data -> (Object || Array) 组织的回填的数据
   *         Object格式 :
   *     {
   *       tableName : (表名),
   *       tableCategory : (表类型(formmain || formson)),
   *      updateData : {
   *         filedName(表单对应控件名) ：{} (回填控件的数据对象)
   *       },
   *       updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有)
   *     }
   *       Array格式：
   *     [
   *       {
   *         tableName : (表名),
   *         tableCategory : (表类型(formmain || formson)),
   *         updateData : {
   *           filedName(表单对应控件名) ：{} (回填控件的数据对象)
   *         },
   *         updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有)
   *       }
   *     ]
   * 注意：
   *  1.回填是根据后端控件值格式
   *  2.回填输的数据对象里面有三个值很特殊 ：从入口方法获取的前端控件对象里面三个属性名是showValue, value, valueId.对应的回填对象里面格属性名是showValue，showValue2, value (非常重要)
   *  3. 2里面获取的前端控件数据对象里面的属性名和回填控件的数据对象属性名 showValue = showValue, value = showValue2, valueId = value  （非常重要）
   * */
   window.thirdPartyFormAPI.backfillFormControlData(data);


## 2.3 backfillFormAttachment(data)

/**
   * 示例：
   * 说明：此接口用于回填表单里面控件的附件
   * 参数：data -> (Object || Array) 组织的回填附件数据
   *       Object格式：
   *         {
   *           tableName : (表名),
   *           tableCategory : (表类型),
   *           updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有),
   *           handlerMode : (操作类型值：添加add和删除delete),
   *           fieldName : (表单回填的对应控件名),
   *           addAttchmentData : [{}], // 回填控件的附件信息列表，附件信息对象需要经过后端对应的格式生成
   *           deleteAttchmentData ：[] // 回填控件附件列表中要删除的对应Id数组
   *         }
   *       Array格式：
   *         [
   *           {
   *             tableName : (表名),
   *             tableCategory : (表类型),
   *             updateRecordId : (更新对应的数据行Id,主表控件没有，明细表控件有),
   *             handlerMode : (操作类型值：添加add和删除delete),
   *             fieldName : (表单回填的对应控件名),
   *             addAttchmentData : [{}], // 回填控件的附件信息列表，附件信息对象需要经过后端对应的格式生成
   *             deleteAttchmentData ：[] // 回填控件附件列表中要删除的对应Id数组
   *           }
   *         ]
   * 注意：
   *  1.handlerMode属性有两个值必填其一
   *  2.handlerMode属性为‘add’ => 只会去读取addAttchmentData属性列表，所以必填
   *  3.handlerMode属性为‘delete’ => 只会去读取deleteAttchmentData属性数组，所以必填
   * 
   * 
   * */
   window.thirdPartyFormAPI.backfillFormAttachment(data);


## 2.4 changeFormFieldAuth(params)

/**
   * 说明： 更新表单控件的权限
   * 参数：params => (Object)
   *    {
   *        formType : 'formmain', // 'formmain','formson'
   *        tableName : 'formmain_5614',
   *        fieldID : 'field0001',
   *        recordId : '', // 明细表用，主表传空
   *        auth : 'hide' // 'edit','browse','hide'
   *    }
   * 
   * */
  // 更新权限
  window.thirdPartyFormAPI.changeFormFieldAuth(params)


## 2.5 getChooseFormsonRecord(); （v7.0sp2 1130版本新增）

/**
   * 说明：获取明细表选中行
   * 返回结果 ： {
   *              (明细表front表名) ：(当前明细表选中行的索引)，
   *              (明细表表名) : {
   *                    index : (当前明细表选中行的索引),
   *                    recordId : (当前明细表选中行的recordId)
   *              },
   *              newChooseTableName : {} // 最近一次操作明细表选中行的信息对象
   *            }
   * 
   * */
  let indexObj = window.thirdPartyFormAPI.getChooseFormsonRecord();


## 2.6 insertFormsonRecords（params） （v7.0sp2 1130版本新增）

/**
   * 说明：js新增明细行
   * 参数： params => (Object)
   *          {
   *            tableName : (明细表表名), // 必填
   *            isFormRecords ：（是否在明细表中选中行后面插入）// true, false 两个值。 必填
   *            chooseRecords ： {  // 指定明细行后面插入
   *                tableName (修改的明细表表名) ：index (明细表索引行 Number类型)
   *            },
   *            callbackFn : (Function) 操作成功后回调
   *          }
   * 注意：
   *    isFormRecords 为true的时候chooseRecords就不生效
   * 
   * */
  window.thirdPartyFormAPI.insertFormsonRecords(params);


## 2.7 copyFormsonRecods（params） （v7.0sp2 1130版本新增）

/**
   * 说明：js复制明细行
   * 参数： params => (Object)
   *          {
   *            tableName : (明细表表名), // 必填
   *            isFormRecords ：（是否在明细表中选中行后面插入复制）// true, false 两个值。 必填
   *            chooseRecords ： {  // 指定明细行后面插入复制
   *                tableName (修改的明细表表名) ：index (明细表索引行 Number类型)
   *            },
   *            callbackFn : (Function) 操作成功后回调
   *          }
   * 注意：
   *    isFormRecords 为true的时候chooseRecords就不生效
   *    isFormRecords 为true 或者chooseRecords 其一必须满足
   * 
   * */
  window.thirdPartyFormAPI.copyFormsonRecods(params);


## 2.8 deleteFormsonRecods（params） （v7.0sp2 1130版本新增）

/**
   * 说明：js删除明细行
   * 参数： params => (Object)
   *          {
   *            tableName : (明细表表名), // 必填
   *            isFormRecords ：（是否在明细表中选中行删除）// true, false 两个值。 必填
   *            chooseRecords ： {  // 指定明细行删除
   *                tableName (修改的明细表表名) ：index (明细表索引行 Number类型)
   *            },
   *            callbackFn : (Function) 操作成功后回调
   *          }
   * 注意：
   *    isFormRecords 为true的时候chooseRecords就不生效
   *    isFormRecords 为true 或者chooseRecords 其一必须满足
   * 
   * */
  window.thirdPartyFormAPI.copyFormsonRecods(params);


编撰人：yinyanting、zhangzuh、lixianhong


快速跳转



 * 介绍
 * 提供的API载体（window.thirdPartyFormAPI）
   * 1 表单事件池操作
     * 1.1 表单中控件失去焦点后触发事件（afterFormFieldChange）
     * 1.2 表单中控件双击后触发事件（formFieldDbclick）
     * 1.3 表单中控件右键后触发事件（formFieldContextmenu）
   * 2 表单提供的功能api
     * 2.1 getFormData(fn)
     * 2.2 backfillFormControlData(data)
     * 2.3 backfillFormAttachment(data)
     * 2.4 changeFormFieldAuth(params)
     * 2.5 getChooseFormsonRecord(); （v7.0sp2 1130版本新增）
     * 2.6 insertFormsonRecords（params） （v7.0sp2 1130版本新增）
     * 2.7 copyFormsonRecods（params） （v7.0sp2 1130版本新增）
     * 2.8 deleteFormsonRecods（params） （v7.0sp2 1130版本新增）



分享链接分享链接

## 43. 1、介绍

> 原始路径：`/94/355/359/399/414.html`  
> 相对路径：`94/355/359/399/414.md`  
> JS Chunk：`app.371b709c.js`

## 1、介绍

白名单插件为运行态中可以自定义是否执行相应定制化功能的插件，目录需放置到whiteList目录下


## 2、支持版本

7.1sp1 930+



## 3、使用前置条件

移动端插件白名单放置目录



PC端插件白名单放置目录




## 4、设计态配置





PC端表单应用的白名单插件内容如下




## 5、白名单插件运行态效果

通过表单运行态打印信息可以推断只有名为Test99的白名单插件生效。



编撰人：yinyanting、lixianhong




快速跳转



 * 1、介绍
 * 2、支持版本
 * 3、使用前置条件
 * 4、设计态配置
 * 5、白名单插件运行态效果



分享链接分享链接

## 44. 客开通路及插件体系版本支持

> 原始路径：`/94/355/359/399/415.html`  
> 相对路径：`94/355/359/399/415.md`  
> JS Chunk：`app.371b709c.js`

## 客开通路及插件体系版本支持


## 7.1SP1 930

1、运行态插件分类，支持表单、查询列表、无流程列表、待办列表等，具体目录变动参见插件机制说明； 2、支持白名单插件配置；

编撰人：yinyanting




快速跳转



 * 客开通路及插件体系版本支持
   * 7.1SP1 930



分享链接分享链接

## 45. 组件库开发指南

> 原始路径：`/94/355/359/416/417.html`  
> 相对路径：`94/355/359/416/417.md`  
> JS Chunk：`app.371b709c.js`

## 组件库开发指南

----------------------------------------


## 背景介绍

为了能够减少维护代价，降低复杂业务逻辑开发门槛，我们新增加了各种功能性组件。让开发像搭积木，不需要再去深入理解业务细节，直接拼装即可使用。


## 说明

> 组件库分为三个pc-ui组件库、移动ui组件库、业务组件库、栏目组件库。

 * pc-ui组件库：只包含单纯的pc-ui显示类组件，通用性较强。
 * 移动ui组件库：只包含单纯的m-ui显示类组件，通用性较强。
 * 业务组件库：对某个业务块高度集成，使用者只需要关系入口跟出口即可，无需关心内部业务处理。
 * 栏目组件库：门户专用组件，自带请求逻辑，内部包含业务组件和ui组件，并且要集成皮肤控制。


## 开发前准备

> 正确配置Node.jsv6.x 或以上版本（推荐先安装nvm），svn最好添加dos命令版


## 命令合集

> 组件打包工程

 * npm run create新建组件，可选择构建哪个组件库的初始化工程，并且会生成初始化md文档，
 * npm run dist交互式打包命令合集，最后提交时候可用此命令交互式发布组件库，最后一个选项为全组件库更新。

注：以下命令已集成到上面两个命令中

 * npm run clean清除lib文件夹
 * npm run build:pkg分别打包packages下子项目，影响分布引用用户
 * npm run build:index分别打包总项目，影响全体引用用户（不推荐使用）
 * npm run build:theme编译公共样式（业务组件库暂时不用）
 * npm run build:utils编译公共js为es5
 * npm run build:cpAssets拷贝src下assets
 * npm run republish单纯发布工程，不编译直接发布

> 门户打包

 * npm build:frame框架编译（只用于开发）
 * npm build:layout门户编译（只用于开发）
 * npm dist:layout正式打包到商城
 * npm dev:layout运行layout

> API文档工程

 * npm run start本地启动API文档
 * npm run build编译API文档
 * npm run dll编译vendor
 * npm run linteslint代码整理
 * npm run unit运行单元测试


## 组件库开发流程


## 新建组件

运行npm run create按照交互命令创建标准初始组件。 组件名的命名规则在packages/config.js下配置。比如业务组件库必须为cap4-开头, 只有cap4-开头的文件夹才会被识别为组件、否则会被忽略。

注：在创建过程中会自动添加识别头，无需再次输入。比如创建组件cap4-test组件，只需输入test即可。

npm run create
组件名 test
------创建模板
packages\cap4-test\index.js
packages\cap4-test\src\cap4-test.vue
packages\cap4-test\src\css\cap4-test.css


创建模板后进入packages文件夹下的模板文件夹中开发。

注：选择不同的组件，生成的组件位置和打包后位置不同

 * pc-ui组件库：packages_pc_ui打包=>lib_pc_ui
 * 移动ui组件库：packages_m_ui打包=>lib_m_ui
 * 业务组件库：packages打包=>lib
 * 栏目组件库：packages_columns打包=>lib_columns


## 开发组件与测试

创建组件后，在examples\docs下创建组件的同名文档，并且在nav.config.json中填入路由

> 路由设置：desc 路由显示名称，name路由名称，path为路由地址

{
          "desc": "indexVUE 测试页面",
          "name": "index",
          "path": "/index"
        }


> 如果不想用md格式或者只是方便测试自己的组件，则在pages下创建自己的组件开发用vue,并且设置如下路由，增加了类型type，指向到pages

{
          "desc": "indexVUE 测试页面",
          "type":"pages",
          "name": "index",
          "path": "/index"
        },



## 编译组件

运行npm run dest按照交互命令编译组件库。

> 交互式逻辑如下

npm run dist
是否需要全工程构建？
是：全部工程构建，重新刷新整个组件的列表文件。
否：进入局部编译状态。

版本说明：如果有svn提交会发布到svn日志

是否重复上次工程构建？
是：读取本地缓存文件，执行上一次局部构建
否：进入局部构建选择页面

选择需要构建的包？[a]全选[space]选择/取消
（）cap4-pkg1
（）cap4-pkg2
（）cap4-pkg3

是否发布到资源库？
是：提交到npm内部资源库。
否：


局部构建是为了方便开发的时候快速编译，如果要发布到资源库里最好更新svn后再执行全编译。


## 业务组件组

用create创建的是标准业务组件，如果需要创建非标准的业务组件组，参照cap4-statistics-pc-ui组件。

业务组件组：如果几个组件是强关联的，要引入都一起引入，才推荐使用业务组件组。其他情况都使用标准业务组件模板。

业务组件组index结构：对外暴露install方法，此方法循环注入多个组件

import Cap4StatisticsMuiSelectGroup from './src/eap-phone-select-group.vue';
import Cap4StatisticsMuiPieTable from './src/eap-echart-table/eap-echart-table-pie.vue';
import Cap4StatisticsMuiLine from './src/eap-echart-table/eap-echart-table-line.vue';
import Cap4StatisticsMuiLineFilter from './src/eap-echart-table/eap-echart-table-line-filter.vue';
import Cap4StatisticsMuiLineHeader from './src/eap-echart-table/eap-echart-table-line-header.vue';
import Cap4StatisticsMuiLineTabs from './src/eap-echart-table/eap-echart-table-line-tabs.vue';

const components = [
  Cap4StatisticsMuiSelectGroup,
  Cap4StatisticsMuiPieTable,
  Cap4StatisticsMuiLine,
  Cap4StatisticsMuiLineFilter,
  Cap4StatisticsMuiLineHeader,
  Cap4StatisticsMuiLineTabs
];

for(let i=0;i<components.length;i++){
  let component = components[i];
  component.install = function (Vue) {
    Vue.component(component.name, component);
  };
}

const install = function(Vue) {
  if (install.installed) return;
  components.map(component => component.install(Vue))
}

export default  {
  install,
  Cap4StatisticsMuiSelectGroup,
  Cap4StatisticsMuiPieTable,
  Cap4StatisticsMuiLine,
  Cap4StatisticsMuiLineFilter,
  Cap4StatisticsMuiLineHeader,
  Cap4StatisticsMuiLineTabs
}



## 组件文档

使用npm run create命令创建的组件会自动生成文档，文档放置在各自的文件夹中。新建的文档不会被添加到导航栏上，如果文档已经完事，手动添加到各自的config文件下

 * pc-ui组件库：examples\docs_pc_ui=> 暂无
 * 移动ui组件库：examples\docs_m_ui=> 暂无
 * 业务组件库：examples\docs=> nav.config.json
 * 栏目组件库：examples\docs_column=> 暂无
   编撰人：yinyanting


快速跳转



 * 组件库开发指南
 * 背景介绍
   * 说明
   * 开发前准备
   * 命令合集
   * 组件库开发流程
     * 新建组件
     * 开发组件与测试
     * 编译组件
     * 业务组件组
     * 组件文档



分享链接分享链接

## 46. GFM语法解读

> 原始路径：`/94/355/359/416/418.html`  
> 相对路径：`94/355/359/416/418.md`  
> JS Chunk：`app.371b709c.js`

## GFM语法解读

----------------------------------------

大标题
====


在文本下面加上 等于号 = ，那么上方的文本就变成了大标题。等于号的个数无限制。

本组件库文档从中标题开始使用。

中标题
-------


在文本下面加上 下划线 - ，那么上方的文本就变成了中标题同样的下划线个数无限制。

除此之外，你也会发现大，中标题下面都有一条横线，没错这就是 = 和 - 的显示结果。

如果你只输入了等于号=，但其上方无文字，那么就只会显示一条直线。如果上方有了文字，但你又只想显示一条横线，而不想把上方的文字转义成大标题的话，那么你就要在等于号=和文字直接补一个空行。

补空行：是很常用的用法，当你不想上下两个不同的布局方式交错到一起的时候，就要在两种布局之间补一个空行。

## 一级标题
### 二级标题
#### 三级标题
##### 四级标题
###### 五级标题
####### 六级标题


> 注意井号#和标题名称要并排写作一行，显示效果：


## 一级标题


## 二级标题


## 三级标题

## 四级标题

## 五级标题

## 六级标题


## 普通文本

这是一段普通的文本，
直接回车不能换行，<br>
要使用\<br>


直接输入的文字就是普通文本。需要注意的是要换行的时候不能直接通过回车来换行，需要使用<br>(或者<br/>)。也就是html里面的标签。事实上，markdown支持一些html标签，你可以试试。当然如果你完全使用html来写的话，就丧失意义了，毕竟markdown并非专门做前端的，然而仅实现一般效果的话，它会比html写起来要简洁得多得多啦。

注意第三行的<br>前加了反斜杠 \ 。目的就是像其他语言那样实现转义，也就是 < 的转义。

此外，要显示一个超链接的话，就直接输入这个链接的URL就好了。显示出来会自动变成可链接的形式的。

补充： 联系两个回车也能达到换行的效果。也就是在文档中有个空行，表现为真正页面的换行。


## 插入代码片段

写法如下：(注意包围符合)




## 单行文本

使用两个Tab符实现单行文本。


## 部分文字的高亮

如果你想使一段话中部分文字高亮显示，来起到突出强调的作用，那么可以把它用包围起来。注意这不是单引号，而是Tab上方，数字1左边的按键（注意使用英文输入法）。

写法：

Thank `You` . Please `Call` Me `Coder`


效果： ThankYou. PleaseCallMeCoder


## 文字超链接

给一段文字加入超链接的格式是这样的要显示的文字。比如：

[我的博客](http://blog.csdn.net/xxxx)


显示效果：我的博客


## 插入符号


## 圆点符

* 昵称：CAP4项目组


要注意的是星号* 后面要有一个空格。否则显示为普通星号。上文的显示效果如图：

 * 昵称：CAP4项目组

此外还有二级圆点和三级圆点。就是多加一个Tab。


## 缩进

>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树


显示效果：

> 数据结构
> 
> > 树
> > 
> > > 二叉树
> > > 
> > > > 平衡二叉树
> > > > 
> > > > > 满二叉树
> > > 
> > > > 

> > > 
> > 
> > > > 

> > > 


## 插入图片

叹号! + 方括号[ ] + 括号( ) 其中叹号里是图片的URL。在方括号里可以加入一些 标识性的信息，比如

![](http://www.baidu.com/img/bdlogo.gif)
![baidu](http://www.baidu.com/img/bdlogo.gif)


这个方括号里的baidu并不会对图像显示造成任何改动，如果你想达到鼠标悬停显示提示信息，那么可以仿照前面介绍的文本中的方法，就是这样：

![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")



## 给图片加上超链接

[![baidu]](http://baidu.com)
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"


编撰人：yinyanting


快速跳转



 * GFM语法解读
 * 一级标题
   * 二级标题
     * 三级标题
       * 四级标题
         * 五级标题
           * 六级标题
   * 普通文本
   * 插入代码片段
   * 单行文本
   * 部分文字的高亮
   * 文字超链接
   * 插入符号
     * 圆点符
     * 缩进
   * 插入图片
     * 给图片加上超链接



分享链接分享链接

## 47. table表格

> 原始路径：`/94/355/359/416/420/421.html`  
> 相对路径：`94/355/359/416/420/421.md`  
> JS Chunk：`app.371b709c.js`

## table表格


## 概述

    Cap4EasyTable是一个可拓展的且内置各种操作与配置接口的table组件。支持宽高设置，序列号，选择框，
列宽可拖动，列拖拽，冻结列，操作列固定，hover颜色及点击颜色设置，水平border及垂直border显示，行
点击，列点击，自排序，列排序，数据可筛选等功能。并且可以支持大数据量显示模式（循环轮播原理）。


----------------------------------------


## 组件调用方法

import Cap4EasyTable from 'cap4-business/lib/cap4-easy-table/index.js';
 import 'cap4-business/lib/cap4-easy-table/css/cap4-easy-table.css';
 
 // 或者cli3脚手架直接引用源码（一般采用相对路径或工程内别名路径）
 import Cap4EasyTable from 'component_doc/packages/cap4-easy-table/index.js';



## 基础表格

/**/

export default {  
    data(){  
        return {  
            tableData: [],  
            msg: '',  
            columns: [],  
            tableConfig: {  
                localStorageKey: "localStorageKey_demo1",  
                bigDataModel: false,  
                columnWidthDrag: false,  
                columnPositionMove: false,  
                frozenOperationCol: false,  
                hasDropDown: false,  
                hasFrozenOeration: false,  
                titleClickChoose: false  
            }  
        }  
    },  
    mounted() {  
        window.setTimeout(() => {  
            this.tableData = [];  
            for (let i = 0; i < 10; i++) {  
                let num = i * 16;  
                this.tableData.push(  
                    {isLock:true, name:'赵伟',tel: ++num+'-'+ '156*****1987',  
                    '01':{showValue:'路飞',src:'http://open.seeyon.com/seeyon/img/group5.png'},  
                    date: {showValue: '2018-10-12',config:{backgroundColor:'green'}},  
                    tel3: 12312.56123,  
                    hobby: function (h) {  
                        return h('div', {  
                            style: ''  
                        }, '123');  
                    }, address:'上海市黄浦区金陵东路569号17楼'},  
                    {name:'李伟',tel: ++num+'-'+ '182*****1538',  
                    date: {showValue: '2018-10-11',config:{backgroundColor:'green'}},  
                    hobby:'钢琴、书法、唱歌',address:'上海市奉贤区南桥镇立新路12号2楼'},  
                    {isLock:true, name:'孙伟',tel: ++num+'-'+ '161*****0097',  
                    date: {showValue: '2018-10-01',config:{backgroundColor:'red'}},  
                    hobby:'钢琴、书法、唱歌',address:'上海市崇明县城桥镇八一路739号'},  
                    {name:'周伟',tel: ++num+'-'+ '197*****1123',hobby:'钢琴、书法、唱歌',address:'上海市青浦区青浦镇章浜路24号'},  
                    {name:'吴伟',tel: ++num+'-'+ '183*****6678',hobby:'钢琴、书法、唱歌',address:'上海市松江区乐都西路867-871号'},  
                );  
            }  
            this.columns = [];  
            for (let i = 0; i < 3; i++) {  
                const str = i === 0 ? '' : i;  
                this.columns.push(  
                    {field: 'name' + str, title: '123', isEdit: true, sortable: false, isFrozen: false, width:0,  
                        filterable: true  
                    },  
                    {field: 'tel' + str, title: '手机号码', sortable: true, filterable: true, searchable: true},  
                    {field: 'operation' + str, type: 'slot', title: '操作', width:100,  
                    },  
                    {field: '01' + str, title: '123123121313122123', type: 'img', columnAlign:'center', compute: true},  
                )  
            }  
        }, 0);  
    }  
};  


/**/


## 带选择框表格

支持单选或多选


{{Math.random()}}

/**/

export default {  
    data(){  
        return {  
            tableData: [],  
            filterData: [],  
            msg: '',  
            columns: [],  
            tableConfig: {  
                localStorageKey: "localStorageKey",  
                serialNumber: {  
                    show: true,  
                    textAlign: 'left'  
                },  
                selection: {  
                    show: true,  
                    isMultiple: true  
                },  
                lockable: true,  
                frozenOperationCol: true,  
                isVerticalResize: false,  
                showVerticalBorder: true,  
                defaultSort: true  
            },  
            pageData: {  
                maxPageSize: 999,  
                page: 1,  
                pageSize: 20,  
                total: 700,  
                noBoundary: true,  
                col: {  
                    isNumber: true,  
                    average: 6,  
                    number: 6,  
                    total: 6  
                }  
            },  
            // 示例用，显示触发事件  
            triggerFunctionArr: []  
        }  
    },  
    mounted() {  
        window.setTimeout(() => {  
            this.tableData = [];  
            for (let i = 0; i < 10; i++) {  
                let num = i * 16;  
                this.tableData.push(  
                    {isLock:true, name:'赵伟',tel: ++num+'-'+ '156*****1987',  
                    '01':{showValue:'路飞',src:'http://open.seeyon.com/seeyon/img/group5.png'},  
                    date: {showValue: '2018-10-12',config:{backgroundColor:'green'}},  
                    tel3: 12312.56123,  
                    hobby: function (h) {  
                        return h('div', {  
                            style: ''  
                        }, '123');  
                    }, address:'上海市黄浦区金陵东路569号17楼'},  
                    {name:'李伟',tel: ++num+'-'+ '182*****1538',  
                    date: {showValue: '2018-10-11',config:{backgroundColor:'green'}},  
                    hobby:'钢琴、书法、唱歌',address:'上海市奉贤区南桥镇立新路12号2楼'},  
                    {isLock:true, name:'孙伟',tel: ++num+'-'+ '161*****0097',  
                    date: {showValue: '2018-10-01',config:{backgroundColor:'red'}},  
                    hobby:'钢琴、书法、唱歌',address:'上海市崇明县城桥镇八一路739号'},  
                    {name:'周伟',tel: ++num+'-'+ '197*****1123',hobby:'钢琴、书法、唱歌',address:'上海市青浦区青浦镇章浜路24号'},  
                    {name:'吴伟',tel: ++num+'-'+ '183*****6678',hobby:'钢琴、书法、唱歌',address:'上海市松江区乐都西路867-871号'},  
                );  
            }  
            this.filterData = [];  
            this.columns = [];  
            for (let i = 0; i < 3; i++) {  
                const str = i === 0 ? '' : i;  
                this.columns.push(  
                    {field: 'name' + str, title: '123', isEdit: true, sortable: false, isFrozen: false, width:0,  
                        filterable: true  
                    },  
                    {field: 'tel' + str, title: '手机号码', sortable: true, filterable: true, searchable: true},  
                    {field: 'operation' + str, type: 'slot', title: '操作', width:100,  
                    },  
                    {field: '01' + str, title: '123123121313122123', type: 'img', columnAlign:'center', compute: true},  
                )  
            }  
        }, 0);  
    },  
    methods: {  
        // 列点击  
        titleClick(params) {  
            this.setTriggerFunction('列点击');  
        },  
        // 行点击  
        rowClick(params) {  
            this.setTriggerFunction('行点击');  
        },  
        // 行双击  
        rowDblclick(params) {  
            this.setTriggerFunction('行双击');  
        },  
        // 子组件回调  
        onSubComponent(params) {  
            this.setTriggerFunction('子组件');  
        },  
        // 单元格编辑回调  
        cellEditDone(params) {  
            this.setTriggerFunction('单元格');  
        },  
        // 全选  
        selectAll(params) {  
            this.setTriggerFunction('全选');  
        },  
        // 选择  
        selectChange(params) {  
            this.setTriggerFunction('选择');  
        },  
        // 排序  
        sortChange(params) {  
            this.setTriggerFunction('排序');  
        },  
        // render  
        renderSlot(slotProps) {  
            const colData = slotProps.data.data.colData;  
            const rowData = slotProps.data.data.rowData;  
            let type = colData.type;  
            return '<div>123</div>'  
        },  
        // 获取筛选数据  
        getFilterData(params) {  
            this.setTriggerFunction('筛选值');  
        },  
        // 筛选  
        filterTableContent(params) {  
            this.setTriggerFunction('筛选');  
        },  
        // 设置triggerFunction  
        setTriggerFunction(str) {  
            const key = Math.random() + str;  
            this.triggerFunctionArr.push({  
                key,  
                name: str,  
            });  
            if (this.triggerFunctionArr.length > 5) {  
                setTimeout(() => {  
                    this.triggerFunctionArr.shift();  
                });  
            }  
            setTimeout(() => {  
                let index = this.triggerFunctionArr.findIndex(item => item.key === key);  
                if (index > -1) {  
                    this.triggerFunctionArr.splice(index, 1);  
                }  
            }, 10000);  
        },  
    },  
    computed: {  
    },  
};  


/**/


## Attributes

参数                 说明                   类型         可选值   默认值
tableData          (必选)列表数据             Array      —     []
columns            (必选)列信息              Array      —     []
filterData         (可选)筛选信息             Array      —     []
width              (可选)宽度               Number     —     —
height             (可选)高度               Number     —     —
tableConfig        (可选)配置项，详细说明见下方      Object     —     {}
showLoading        (可选)是否展示加载态          Boolean    —     true
minWidth           (可选)最小列宽度            Boolean    —     63
titleRowHeight     (可选)行高               Function   —     40
isPrint            (可选)是否打印态            Boolean    —     false
printStorageInfo   (可选)打印态需要传递浏览器缓存信息   Object     —     {}
page               (可选)第几页              Number     —     1
pageSize           (可选)每页的条数            Number     —     50


## tableConfig

table配置项，用object传递减少直接传入参数


配置项                    说明                  类型        可选值          示例值
serialNumber           显示序号                Object    —            {show: true, textAlign: 'left'} (显示序列号，且居左显示)
selection              显示选择框               Object    —            {show: true,isMultiple: true} (显示选择框，且支持多选)
lockable               显示锁定列               Boolean   true/false   true
isHorizontalResize     水平自适应               Boolean   true/false   true
isVerticalResize       垂直自适应               Boolean   true/false   true
columnWidthDrag        列宽可拖动               Boolean   true/false   true
columnPositionMove     列位置可拖拽              Boolean   true/false   true
frozenOperationCol     右侧固定操作列             Boolean   true/false   true
localStorageKey        localStorage缓存key   String    —            'localStorageKey' (使用唯一值)
rowHoverColor          行hover颜色            Boolean   —            '#F5F5F5'
titleBgColor           列头背景色               Boolean   —            true
operationBgColor       固定操作列背景色            Boolean   —            true
titleHoverColor        列头hover颜色           Boolean   —            true
rowClickColor          行点击选中色              Boolean   —            true
showHorizontalBorder   显示水平border          Boolean   true/false   true
showVerticalBorder     显示垂直border          Boolean   true/false   true
defaultSort            自排序                 Boolean   true/false   true
titleRowHeight         行高                  Boolean   —            true
bigDataModel           大数据量模式              Boolean   true/false   true
hasDropDown            显示下拉框               Boolean   true/false   true
titleClickSort         列头点击排序              Boolean   true/false   true
titleClickChoose       列点击可选中              Boolean   true/false   true
rowClickUncheck        行重复点击取消选中           Boolean   true/false   true


## col配置项属性

配置项             说明      类型        可选值                                                                           示例值
filterable      可筛选     Boolean   true/false                                                                    true
searchable      筛选可搜索   Boolean   true/false                                                                    true
sortable        可排序     Boolean   true/false                                                                    true
isFrozen        被冻结     Boolean   true/false                                                                    true
width           初始列宽度   Number    -                                                                             100
field           key     String    -                                                                             'field01'
type            类型      String    'render'/'slot'/'normalText'/'normalObjText'(.v)/'normalObjectText(.value)'   'normalText'
componentName   以组件加载   String    -                                                                             -


## Event

事件名称                 说明          回调参数
titleClick           列点击触发       列信息
titleUnClick         列重复点击触发     —
rowClick             行点击触发       行信息
onSubComponent       子组件触发       —
cellEditDone         td编辑触发      —
selectAll            全选时触发       —
selectChange         选择项改变触发     —
sortChange           列排序触发       —
getFilterData        列筛选获取数据触发   —
filterTableContent   列筛选触发       —

编撰人：yinyanting


快速跳转



 * table表格
   * 概述
   * 组件调用方法
   * 基础表格
   * 带选择框表格
   * Attributes
   * tableConfig
   * col配置项属性
   * Event



分享链接分享链接

## 48. 通用分页 组件

> 原始路径：`/94/355/359/416/420/422.html`  
> 相对路径：`94/355/359/416/420/422.md`  
> JS Chunk：`app.371b709c.js`

## 通用分页 组件

----------------------------------------


## 引入

import Cap4BasePage from 'cap4-business/lib/cap4-base-page';
import 'cap4-business/lib/cap4-base-page/css/cap4-base-page.css';



## 用法

 * 引入分页组件来实现分页效果
 * 引入分页组件必须用有height的相对元素包裹起来
 * 图标依赖于 cap4字体库


## 示例

每页显示

条/共700条记录

共35页

第

页

GO

显示代码


## Attributes

参数     说明        类型       可选值   默认值
data   传入的data   Object   —     —


## data

参数            说明              类型        可选值          默认值
total         总数(必填)          Number    —            —
pageSize      每页显示的条数(必填)     Number    —            —
page          当前页数(必填)        Number    —            —
maxPageSize   每一页最大长度         Number    —            —
noBoundary    是否隐藏上方分界线(选填)   Boolean   true/false   false


## Event

事件名称        说明       回调参数
pageEvent   页数改变回调   {page, pageSize}

编撰人：yinyanting


快速跳转



 * 通用分页 组件
   * 引入
   * 用法
   * 示例
   * Attributes
   * data
   * Event



分享链接分享链接

## 49. 通用title 组件

> 原始路径：`/94/355/359/416/420/423.html`  
> 相对路径：`94/355/359/416/420/423.md`  
> JS Chunk：`app.371b709c.js`

## 通用title 组件

----------------------------------------


## 引入

import Cap4Title from 'cap4-business/lib/cap4-title';
import 'cap4-business/lib/cap4-title/css/cap4-title.css';



## 用法

 * 图标依赖于 cap4字体库


## 示例

测试批量无流程(20条)

转发打印导出Excel

显示代码


## Attributes

参数      说明          类型       可选值      默认值
name    title显示文本   String   —        —
count   条数          Number   —        —
type    类型          String   Number   (1:有打印导出, 2:没有打印导出)

编撰人：yinyanting


快速跳转



 * 通用title 组件
   * 引入
   * 用法
   * 示例
   * Attributes



分享链接分享链接

## 50. 统计排队组件

> 原始路径：`/94/355/359/416/420/424.html`  
> 相对路径：`94/355/359/416/420/424.md`  
> JS Chunk：`app.371b709c.js`

## 统计排队组件

----------------------------------------


## 引入

import Cap4StatisticsQueue from 'cap4-business/lib/cap4-statistics-queue';
import  'cap4-business/lib/cap4-statistics-queue/css/cap4-statistics-queue.css';



## 用法

cap4-statistics-queue排队组件,用于带有排队机制的接口。 接口返回类型如下：(必须有state字段，统计内容在字段result中)

注：新增了对旧有接口的支持，如果类型为普通的统计不带排队字段，直接返回传入的data

{
     "result" : {},
     "state" : {
         "code" : "101",
         "taskCount":"1000",
         "reqId" : "8330040413334832192"
      }
}


排序有三个状态

 * 100正常返回数据
 * 101队列中，可以取消
 * 102队列已满。


## 示例

## pc 101态样式

:注一旦状态变为100,表明已经取到数据,内部的作用域中变量slot.dataInfo里面会注入统计数据。

系统繁忙，当前报表请求排队中，
前面有1000个报表请求等待响应中！
点击取消，可撤销当前请求！
取消

显示代码

## 移动 101态样式

系统繁忙，当前报表请求排队中，
前面有1000个报表请求等待响应中！
点击取消，可撤销当前请求！
取消

显示代码

## pc 102态样式

系统繁忙，前面已有1000个报表请求等待响应中！
请稍候再试！
确定

显示代码

## 移动 102态样式

系统繁忙，前面已有1000个报表请求等待响应中！
请稍候再试！
确定

显示代码


## Attributes

参数         说明                              类型       可选值         默认值
data       由排队接口返回是数据，数据内部包含有【state】排序字段   Object   —           —
platform   平台                              Number   1：pc 2：手机   1


## Event

事件名称     说明                                                                       回调参数
loop     后台返回101                                                                  state
         排序状态，组件会进入循环状态，取到数据的三秒后再次回调loop方法（新增自动请求，但是必须依赖栏目垫片组件）
cancel   在101排序态下取消排序回调（注：如果为102队列已满，点击确定不再调用后台，所以不会触发此回调）（新增自动请求，但是必须依赖栏目垫片组件）   

编撰人：yinyanting


快速跳转



 * 统计排队组件
   * 引入
   * 用法
   * 示例
     * pc 101态样式
     * 移动 101态样式
     * pc 102态样式
     * 移动 102态样式
   * Attributes
   * Event



分享链接分享链接

## 51. code组件

> 原始路径：`/94/355/359/416/420/425.html`  
> 相对路径：`94/355/359/416/420/425.md`  
> JS Chunk：`app.371b709c.js`

## code组件

----------------------------------------


## 引入

import Cap4Code from 'cap4-business/lib/cap4-code';
import  'cap4-business/lib/cap4-code/css/cap4-code.css';



## 用法

cap4-codecode码显示组件，用于统一处理code显示。 1.code码提示优先于无数据。 2.现阶段只支持无流程列表。

三个状态展示

无数据样式展示

 * noDate暂无数据提示


## 示例

接口返回示例

{
        "code" : "1004",
        "message" : "this option not auth or not exist!",
        "isEg" : "0"
      }


## pc noDate状态



暂无数据

显示代码

## m noDate状态



暂无数据

显示代码

## pc code iconIndex == 1显示状态



系统错误！

显示代码

## pc code iconIndex='2'显示状态



暂无权限

显示代码

## pc code iconIndex='3'显示状态 ，只有在移动端有效。引用的v5样式、

暂无权限

显示代码


## Attributes

参数          说明                    类型        可选值         默认值
noData      没有数据                  Boolean   —           false
code        code码                 String                ''
msg         显示文字，如果不传入则显示默认提示文字   Number                默认提示文字 ：noData = false :系统错误！ 、 noData = true :暂无数据
platform    平台                    Number    1：pc 2：手机   1
iconIndex   显示图标                  Number    1：叹号 2：咖啡   1

编撰人：yinyanting


快速跳转



 * code组件
   * 引入
   * 用法
   * 示例
     * pc noDate状态
     * m noDate状态
     * pc code iconIndex == 1显示状态
     * pc code iconIndex='2'显示状态
     * pc code iconIndex='3'显示状态 ，只有在移动端有效。引用的v5样式、
   * Attributes



分享链接分享链接

## 52. 条件筛选组件

> 原始路径：`/94/355/359/416/420/426.html`  
> 相对路径：`94/355/359/416/420/426.md`  
> JS Chunk：`app.371b709c.js`

## 条件筛选组件

----------------------------------------

用于列表页面中条件的筛选。


## 基本用法

## 1.概述

条件筛选组件分为快速筛选和高级筛选两种，选择好需要筛选的条件，点击筛选即可进行筛选，点击重置可将刚才选择好的筛选条件清空，点击>>后，在快速筛选和高级筛选之间切换。

## 2.快速筛选和高级筛选

快速筛选和高级筛选可以进行7种类型的筛选字段,分别为文本,数字,单选框/下拉框,日期/日期时间,组织,图片枚举/图片下拉,复选框。 文本,数字之间在输入框输入对应的条件;单选框/下拉框,图片枚举/图片下拉，复选框通过点击输入框，在弹出的列表中选择;日期/日期时间，组织会调用相关的V5控件选择;其中图片枚举/图片下拉在快速筛选中为多选，高级筛选为单选。 高级筛选有选择括号、逻辑关系和集合关系的选项;快速筛选没有，是按照默认的选项传递到search事件。

<script>
   export default{
      data () {
       return {
           //示例：部分类型筛选字段
           filterFields:
               [
                   {
                       "enums":[],
                       "aliasTableName":"formmain_1913_0",
                       "defaultValue":{},
                       "display":"复选2复选2",
                       "name":"field3014",
                       "inputType":"checkbox",
                       "fieldType":"VARCHAR",
                       "tableName":"formmain_1913"
                   },
                   {
                       "enums" : [ ],
                       "aliasTableName" : "formmain_0016",
                       "defaultValue" : {
                       "showValue" : "开发",
                       "showValue2" : "开发",
                       "value" :{
                            "Member|261808748185796717,Member|4718179216211725653," +
                            "Member|-6452904596450358682,Member|3030772480077482176," +
                            "Member|6474707622226251493,Member|-2760468557162788733"
                        },
                        "display" : "选多人1",
                        "name" : "field0013",
                        "inputType" : "multimember",
                        "fieldType" : "VARCHAR",
                        "tableName" : "formmain_0016"
                   },
                   {
                        "aliasTableName": "formmain_0014_0",
                        "enumId": "0",
                        "inputType": "text",
                        "name": "field000111",
                        "fieldType": "DECIMAL",
                        "category": "cap4biz",
                        "properties": {},
                        "display": "数字2",
                        "tableName": "formmain_0014"
                   },
                   {
                        "enums" : [  {
                            "showValue" : "本日",
                            "enumValue" : "date_today",
                            "id" : "date_today"
                        },{
                            "showValue" : "本月",
                            "enumValue" : "date_thisMonth",
                            "id" : "date_thisMonth"
                        },{
                            "showValue" : "上月",
                            "enumValue" : "date_preMonth",
                            "id" : "date_preMonth"
                        },{
                            "showValue" : "本周",
                            "enumValue" : "date_thisWeek",
                            "id" : "date_thisWeek"
                        }, {
                            "showValue" : "本季度",
                            "enumValue" : "date_thisSeason",
                            "id" : "date_thisSeason"
                        },{
                            "showValue" : "本年",
                            "enumValue" : "date_thisyear",
                            "id" : "date_thisyear"
                        },{
                            "showValue" : "昨日",
                            "enumValue" : "date_yesterday",
                            "id" : "date_yesterday"
                        },{
                            "showValue" : "明日",
                            "enumValue" : "date_tomorrow",
                            "id" : "date_tomorrow"
                        },{
                            "showValue" : "下月",
                            "enumValue" : "date_nextMonth",
                            "id" : "date_nextMonth"
                        },{
                            "showValue" : "上周",
                            "enumValue" : "date_preWeek",
                            "id" : "date_preWeek"
                        },{
                            "showValue" : "下周",
                            "enumValue" : "date_nextWeek",
                            "id" : "date_nextWeek"
                        },{
                            "showValue" : "去年",
                            "enumValue" : "date_lastyear",
                            "id" : "date_lastyear"
                        }, {
                            "showValue" : "明年",
                            "enumValue" : "date_nextyear",
                            "id" : "date_nextyear"
                        } ,{
                            "showValue" : "上季度",
                            "enumValue" : "date_preSeason",
                            "id" : "date_preSeason"
                        }, {
                            "showValue" : "下季度",
                            "enumValue" : "date_nextSeason",
                            "id" : "date_nextSeason"
                        },{
                            "showValue" : "111dfssssss1111",
                            "enumValue" : "2018-03-16 10:54|2018-03-23 10:54",
                            "startTime" : "2018-03-16 10:54",
                            "id" : "2018-03-16 10:54|2018-03-23 10:54",
                            "endTime" : "2018-03-23 10:54"
                        } ],
                        "defaultValue":{
                            "showValue":"上季度",
                            "showValue2":"date_preSeason",
                            "value":"date_preSeason"
                        },
                        "aliasTableName": "formmain_0014_0",
                        "enumId": "0",
                        "inputType": "datetime",
                        "name": "field0007",
                        "fieldType": "TIMESTAMP",
                        "category": "cap4biz",
                        "properties": {},
                        "dateValue":{
                            "startDate":'',
                            "endDate":'',
                        },
                        "display": "日期1时间",
                        "tableName": "formmain_0014"
                   },
                   {
                        "aliasTableName": "formmain_0015_0",
                        "enumId": "0",
                        "inputType": "text",
                        "name": "field0205",
                        "fieldType": "VARCHAR",
                        "category": "cap4biz",
                        "properties": {},
                        "display": "文本2",
                        "defaultValue":{
                            "showValue":"手动默认值设置",
                            "showValue2":"手动默认值设置",
                            "value":"手动默认值设置"
                        },
                        "tableName": "formmain_0015"
                   },
               ]
           }
       }
   },
   methods: {
       getCalendar(params,callback,callback2){
           $.calendar({
               displayArea:params.id,
               returnValue: true,
               date:new Date(),
               autoShow:true,
               minuteStep:1,
               ifFormat:params.type==='date'?"%Y-%m-%d":"%Y-%m-%d %H:%M",
               daFormat:params.type==='date'?"%Y-%m-%d":"%Y-%m-%d %H:%M",
               showsTime:params.type==='date'?false:true,
               isClear:true,
               onUpdate:function (v) {
                   callback&&callback(v);
               },
               onClear:function () {
                   callback2&&callback2('');
               }
           });
       },
       getOrganize(params,callback){
           let panels;
           let selectType;
           let maxSize;
               switch (params.type) {
                   case 'member':
                       panels = 'Department,Team,Post,Outworker,Level';
                       selectType = 'Member';
                       maxSize = '1';
                       break;
                   case 'multimember':
                       panels = 'Department,Team,Post,Outworker,Level';
                       selectType = 'Member';
                       maxSize = '-1';
                       break;
                   case 'post':
                       panels = selectType = 'Post';
                       maxSize = '1';
                       break;
                   case 'multipost':
                       panels = selectType = 'Post';
                       maxSize = '-1';
                       break;
                   case 'department':
                       panels = selectType = 'Department';
                       maxSize = '1';
                       break;
                   case 'multidepartment':
                       panels = selectType = 'Department';
                       maxSize = '-1';
                       break;
                   case 'account':
                       panels = selectType = 'Account';
                       maxSize = '1';
                       break;
                   case 'multiaccount':
                       panels = selectType = 'Account';
                       maxSize = '-1';
                       break;
                   case 'level':
                       panels = selectType = 'Level';
                       maxSize = '1';
                       break;
                   case 'multilevel':
                       panels = selectType = 'Level';
                       maxSize = '-1';
                       break;
                   default:
                       break;
               }
               let filbackData = '';
               if (params.value) {
                   params.value.split(',').forEach(v => {
                       if (v) {
                           if (filbackData !== '') {
                               filbackData += ',';
                           }
                       filbackData += `${selectType}|${v.split('|')[0]}`;
                       }
                   });
               }
               console.log(filbackData);
                   window.top.$.selectPeople({
                       panels,
                       selectType,
                       maxSize,
                       minSize : 0,
                       isAllowContainsChildDept : true,
                       params : {
                           text : '请选择',
                           value : filbackData
                       },
                       callback : ret => {
                           const result = ret.obj;
                           let ids = '';
                           let value = '';
                           result.forEach(v => {
                           if (value !== '') {
                               value += ',';
                           }
                           value += `${v.id}|${v.name}`;
                           if (ids !== '') {
                               ids += ',';
                           }
                           ids += `${v.id}`;
                       });
                       params.value = value;
                       params.valueId = ids;
                       callback&&callback({
                           value:ret.value,
                           valueId:ids,
                           text:ret.text
                       });
                   }
               });
           },
           resetFun() {
               //doSth...
           },
           alert(str){
               window.top.$.error(str);
           },
           sizeChangeFun() {
               //doSth...
           },
           search(userConditions, strConditions) {
               //doSth...
           },
           switchFilter(){
               //doSth...
           },
       }
   }
</script>
<cap4-condition
    v-if="filterFields"
    :filterFields="filterFields"
    @search="search"
    @getCalendar="getCalendar"
    @reset="resetFun"
    @alert="alert"
    @sizeChange="sizeChangeFun"
    @getOrganize="getOrganize"
    @switchFilter="switchFilter"
>



## Attributes

参数             说明               类型      可选值   默认值
filterFields   必选参数，后端返回的筛选字段   array   —     [ ]


## Event

事件名称           说明                              回调参数
search         点击筛选按钮后将触发，返回筛选到的数据以便于向后端发送请求   userConditions(返回的向后端请求的筛选数据), strConditions(前端显示的筛选信息)
getCalendar    选择时间日期时调用V5日期组件                 params(传入的日期详细类型),callback(日期组件确定按钮的回调),clearCallback(日期组件清除按钮的回调)
reset          点击重置按钮后将触发                      —
alert          调用V5消息提示                        alertMsg(需要提示的内容)
sizeChange     当筛选组件的高度发生变化时调用                 —
getOrganize    选择组织后调用V5组织控件                   params(传入的组织详细类型),callback(组织控件确定按钮的回调)
switchFilter   点击快速筛选和高级筛选的切换按钮后触发             —

编撰人：yinyanting


快速跳转



 * 条件筛选组件
   * 基本用法
     * 1.概述
     * 2.快速筛选和高级筛选
   * Attributes
   * Event



分享链接分享链接

## 53. 批量导入组件

> 原始路径：`/94/355/359/416/420/427.html`  
> 相对路径：`94/355/359/416/420/427.md`  
> JS Chunk：`app.371b709c.js`

## 批量导入组件

----------------------------------------

用于批量导入


## 基本用法

通过v-if 来动态加载批量导入模块

<script>
  export default{
    data () {
        return {
          isShow: false,
          params: {
            appId:'', // your appId
            formId:'', // your formId
            bindAuthId: '' // your bindAuthId
          }
        }
    },
    methods: {
    }
  }
</script>

<div class=" demo-block">
  <a href="javascript:;" @click="isShow = true">批量导入</a>
  <cap4-bulk-import v-if="isShow" :params="params"></cap4-bulk-import>
</div>



## Attributes

参数       说明         类型       可选值                                           默认值
params   参数 (必填))   Object   —                                             —
path     网站path     string   /seeyon/common/cap4/template/base/cap4-bulk   


## params

参数           说明                类型       可选值   默认值
appId        appId (必填)        String   —     —
formId       formId (必填)       String   —     —
bindAuthId   bindAuthId (必填)   String   —     —


## Event

事件名称      说明     回调参数
success   成功回调   —
close     关闭回调   —

编撰人：yinyanting


快速跳转



 * 批量导入组件
   * 基本用法
   * Attributes
   * params
   * Event



分享链接分享链接

## 54. 上传组件

> 原始路径：`/94/355/359/416/420/428.html`  
> 相对路径：`94/355/359/416/420/428.md`  
> JS Chunk：`app.371b709c.js`

## 上传组件

----------------------------------------

用于Excel上传


## 基本用法



通过v-if 来动态加载Excel上传

<script>
  export default{
    data () {
        return {
          isShow: false,
          ctxPath: null,
          mineGetUrlSurffix: null
        }
    },
    methods: {
      uploadSuccess(data){
      }
    }
  }
</script>

<div class=" demo-block">
  <a href="javascript:;" @click="isShow = true">选择文件</a>
  <cap4-upload-excel 
    v-if="isShow" 
    :ctxPath="ctxPath"
    :mineGetUrlSurffix="mineGetUrlSurffix"
    @upload-success="uploadSuccess"
    @close="isShow = false"></cap4-upload-excel>
</div>



## Attributes

参数                      说明                  类型       可选值                                           默认值
ctxPath                 ctxPath(必填)         string   —                                             —
mineGetUrlSurffix(必填)   mineGetUrlSurffix   string   -                                             
path                    网站path              string   /seeyon/common/cap4/template/base/cap4-bulk   


## Event

事件名称             说明     回调参数
upload-success   成功回调   —
close            关闭回调   —

编撰人：yinyanting


快速跳转



 * 上传组件
   * 基本用法
   * Attributes
   * Event



分享链接分享链接

## 55. 批量更新组件

> 原始路径：`/94/355/359/416/420/429.html`  
> 相对路径：`94/355/359/416/420/429.md`  
> JS Chunk：`app.371b709c.js`

## 批量更新组件

----------------------------------------

用于批量更新


## 基本用法



通过v-if 来动态加载批量更新模块

<script>
  export default{
    data () {
        return {
          isShow: false,
          params: {
            appId:'', // your appId
            formId:'', // your formId
            bindAuthId: '', // your bindAuthId
            size: 10, // Data List 数据条数 必填
            lockNum: 2, //锁定条数 必填
            checkObjLen: 2, //选中条数 必填
            checkObj: [], //选中的数据 必填
          }
        }
    },
    methods: {
    }
  }
</script>

<div class=" demo-block">
  <a href="javascript:;" @click="isShow = true">批量修改</a>
  <cap4-bulk-update v-if="isShow" :params="params"></cap4-bulk-update>
</div>



## Attributes

参数       说明         类型       可选值                                           默认值
params   参数 (必填))   Object   —                                             —
path     网站path     string   /seeyon/common/cap4/template/base/cap4-bulk   —


## params

参数            说明                    类型       可选值   默认值
appId         appId (必填)            String   —     —
formId        formId (必填)           String   —     —
bindAuthId    bindAuthId (必填)       String   —     —
size          Data List 数据条数 (必填)   Number   —     —
lockNum       锁定条数 (必填)             Number   —     —
checkObjLen   选中条数 (必填)             Number   —     —
checkObj      选中的数据 (必填)            Array    —     —


## Event

事件名称      说明     回调参数
success   成功回调   —
close     关闭回调   —

编撰人：yinyanting、chenlin


快速跳转



 * 批量更新组件
   * 基本用法
   * Attributes
   * params
   * Event



分享链接分享链接

## 56. 批量刷新组件

> 原始路径：`/94/355/359/416/420/430.html`  
> 相对路径：`94/355/359/416/420/430.md`  
> JS Chunk：`app.371b709c.js`

## 批量刷新组件

----------------------------------------

用于批量刷新


## 基本用法



通过v-if 来动态加载批量刷新模块

<script>
  export default{
    data () {
        return {
          isShow: false,
          params: {
            appId:'', // your appId
            formId:'', // your formId
            bindAuthId: '', // your bindAuthId
            size: 10, // Data List 数据条数 必填
            lockNum: 2, //锁定条数 必填
            checkObjLen: 2, //选中条数 必填
            checkObj: [], //选中的数据 必填
            isDoTrigger: false, // 是否需要执行触发
            queryParamsData : null, // 筛选条件
          }
        }
    },
    methods: {
    }
  }
</script>

<div class=" demo-block">
  <a href="javascript:;" @click="isShow = true">批量刷新</a>
  <cap4-bulk-refresh v-if="isShow" :params="params"></cap4-bulk-refresh>
</div>



## Attributes

参数       说明         类型       可选值                                           默认值
params   参数 (必填))   Object   —                                             —
path     网站path     string   /seeyon/common/cap4/template/base/cap4-bulk   


## params

参数                说明                    类型        可选值   默认值
appId             appId (必填)            String    —     —
formId            formId (必填)           String    —     —
bindAuthId        bindAuthId (必填)       String    —     —
size              Data List 数据条数 (必填)   Number    —     —
lockNum           锁定条数 (必填)             Number    —     —
checkObjLen       选中条数 (必填)             Number    —     —
checkObj          选中的数据 (必填)            Array     —     —
isDoTrigger       是否需要执行触发 (必填)         Boolean   —     —
queryParamsData   筛选条件                  Object    —     —


## Event

事件名称      说明     回调参数
success   成功回调   —
close     关闭回调   —

编撰人：yinyanting


快速跳转



 * 批量刷新组件
   * 基本用法
   * Attributes
   * params
   * Event



分享链接分享链接

## 57. 组件cap4-button

> 原始路径：`/94/355/359/416/431/432.html`  
> 相对路径：`94/355/359/416/431/432.md`  
> JS Chunk：`app.371b709c.js`

## 组件cap4-button

----------------------------------------


## 引入

import cap4-button from 'cap4-pc-ui/lib/cap4-button';  
import 'cap4-pc-ui/lib/cap4-button/css/cap4-button.css';



## 用法

 * 图标依赖于 cap4字体库


## 示例

展示cap4-button组件

::: demo

<cap4-button></cap4-button>


:::


## Attributes

参数       说明         类型       可选值   默认值
params   参数 (必填))   Object   —     —


## Event

事件名称      说明     回调参数
success   成功回调   —
close     关闭回调   —

编撰人：yinyanting


快速跳转



 * 组件cap4-button
   * 引入
   * 用法
   * 示例
   * Attributes
   * Event



分享链接分享链接

## 58. 组件名cap4-checkbox

> 原始路径：`/94/355/359/416/431/433.html`  
> 相对路径：`94/355/359/416/431/433.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-checkbox

----------------------------------------


## 引入

import Cap4Checkbox from 'cap4-pc-ui/lib/cap4-checkbox';
import 'cap4-pc-ui/lib/cap4-checkbox/css/cap4-checkbox.css';



## 基本用法

展示cap4-checkbox组件

::: demo

<cap4-checkbox></cap4-checkbox>


:::


## Attributes

参数       说明         类型       可选值   默认值
params   参数 (必填))   Object   —     —


## Event

事件名称      说明     回调参数
success   成功回调   —
close     关闭回调   —

编撰人：yinyanting


快速跳转



 * 组件名cap4-checkbox
   * 引入
   * 基本用法
   * Attributes
   * Event



分享链接分享链接

## 59. 组件名cap4-color

> 原始路径：`/94/355/359/416/431/434.html`  
> 相对路径：`94/355/359/416/431/434.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-color

----------------------------------------


## 引入

import Cap4Color from 'cap4-pc-ui/lib/cap4-color';
import 'cap4-pc-ui/lib/cap4-color/css/cap4-color.css';



## 基础用法

/**/

export default {
data() {
return {
leftSpan: '请选择颜色',
color: '#999999'
};
}
};
/**/::: demo

<template>
    <div class="demo-block" style="position:relative;">
        <cap4-color v-model="color" :leftSpan="leftSpan"></cap4-color>
    </div>
</template>

<script>
export default {
    data() {
        return {
            leftSpan: '请选择颜色',
            color: '#999999'
        };
    }
};
</script>


:::


## Attributes

参数          说明          类型       可选值   默认值
value       颜色 (选填))    String   —     ''
leftSpan    左文本 (选填))   String   —     
rightSpan   右文本 (选填))   String   —     

编撰人：yinyanting


快速跳转



 * 组件名cap4-color
   * 引入
   * 基础用法
   * Attributes



分享链接分享链接

## 60. 组件名cap4-eg

> 原始路径：`/94/355/359/416/431/435.html`  
> 相对路径：`94/355/359/416/431/435.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-eg

----------------------------------------


## 引入

import Cap4Eg from 'cap4-pc-ui/lib/cap4-eg';
import 'cap4-pc-ui/lib/cap4-eg/css/cap4-eg.css';



## 基本用法

展示cap4-eg组件

::: demo

<cap4-eg></cap4-eg>


:::


## Attributes

参数       说明         类型       可选值   默认值
params   参数 (必填))   Object   —     —


## Event

事件名称      说明     回调参数
success   成功回调   —
close     关闭回调   —

编撰人：yinyanting


快速跳转



 * 组件名cap4-eg
   * 引入
   * 基本用法
   * Attributes
   * Event



分享链接分享链接

## 61. 组件名cap4-horizontal-list

> 原始路径：`/94/355/359/416/431/436.html`  
> 相对路径：`94/355/359/416/431/436.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-horizontal-list

----------------------------------------


## 引入

import Cap4HorizontalList from 'cap4-pc-ui/lib/cap4-horizontal-list';
import 'cap4-pc-ui/lib/cap4-horizontal-list/css/cap4-horizontal-list.css';



## 基础用法

    {{ list[slotProps.index].display }}

/**/

export default {  
data() {  
return {  
list: [    
                {    
                    value: 1,    
                    display: '北京'    
                },    
                {    
                    value: 2,    
                    display: '上海'    
                },    
                {    
                    value: 3,    
                    display: '广州'    
                },    
                {    
                    value: 4,    
                    display: '北京1'    
                },    
                {    
                    value: 5,    
                    display: '上海1'    
                },    
                {    
                    value: 6,    
                    display: '广州1'    
                }    
            ],  
};  
}  
};  
/**/::: demo


<template>
    <div class="demo-block">
        <cap4-horizontal-list :list="list">
        <template v-slot="slotProps">
            <li style="width:150px; height:80px; line-height:40px;">{{ list[slotProps.index].display }}</li>
        </template>
        </cap4-horizontal-list>
    </div>
</template>

<script>
export default {
    data() {
        return {
            list: [
                {
                    value: 1,
                    display: '北京'
                },
                {
                    value: 2,
                    display: '上海'
                },
                {
                    value: 3,
                    display: '广州'
                },
                {
                    value: 4,
                    display: '北京1'
                },
                {
                    value: 5,
                    display: '上海1'
                },
                {
                    value: 6,
                    display: '广州1'
                }
            ],
        };
    }
};
</script>


:::


## Attributes

参数     说明         类型      可选值   默认值
list   参数 (选填))   Array   —     —


## Slot

参数      说明              类型       可选值   默认值
index   序号 (数组中的第几项))   Number   —     —

编撰人：yinyanting、admin


快速跳转



 * 组件名cap4-horizontal-list
   * 引入
   * 基础用法
   * Attributes
   * Slot



分享链接分享链接

## 62. 组件名cap4-icon

> 原始路径：`/94/355/359/416/431/437.html`  
> 相对路径：`94/355/359/416/431/437.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-icon

----------------------------------------


## 引入

import Cap4Icon from 'cap4-pc-ui/lib/cap4-icon';
import 'cap4-pc-ui/lib/cap4-icon/css/cap4-icon.css';



## 基础用法

/**/

export default {
data() {
return {
leftSpan: '请选择图标',
icon: 'cap-icon-new-business-opportunity',
iconColor: '#67bfff',
bgColor: '#ebebeb'
};
},
methods: {
chooseIcon() {
alert('实现选图标');
}
}
};
/**/::: demo

<template>
    <div class="demo-block">
        <cap4-icon v-model="icon" :leftSpan="leftSpan" :iconColor="iconColor" :bgColor="bgColor" @chooseIcon="chooseIcon"></cap4-icon>
    </div>
</template>

<script>
export default {
    data() {
        return {
            leftSpan: '请选择图标',
            icon: 'cap-icon-new-business-opportunity',
            iconColor: '#67bfff',
            bgColor: '#ebebeb'
        };
    },
    methods: {
        chooseIcon() {
            alert('实现选图标');
        }
    }
};
</script>


:::


## Attributes

参数          说明            类型       可选值   默认值
value       图标 (必填))      String   —     ''
leftSpan    左文本 (选填))     String   —     
rightSpan   右文本 (选填))     String   —     
iconColor   图标色 (选填))     String   —     
iconClass   图标样式类 (选填))   String   —     
bgColor     图标背景色 (选填))   String   —     

编撰人：yinyanting


快速跳转



 * 组件名cap4-icon
   * 引入
   * 基础用法
   * Attributes



分享链接分享链接

## 63. 组件名cap4-indicator

> 原始路径：`/94/355/359/416/431/438.html`  
> 相对路径：`94/355/359/416/431/438.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-indicator

----------------------------------------


## 引入

import Cap4Indicator from 'cap4-pc-ui/lib/cap4-indicator';
import 'cap4-pc-ui/lib/cap4-indicator/css/cap4-indicator.css';



## 基础用法

/**/

export default {
data() {
return {
loading: true
};
}
};
/**/::: demo

<template>
    <div class="demo-block" style="position:relative; height:300px;">
        <cap4-indicator :loading="loading"></cap4-indicator>
    </div>
</template>

<script>
export default {
    data() {
        return {
            loading: true
        };
    }
};
</script>


:::


## Attributes

参数        说明             类型                 可选值   默认值
loading   是否加载中 (必填))    Boolean            —     
empty     是否无数据 (必填))    Boolean            —     
opacity   设置不透明度 (必填))   [String, Number]   —     

编撰人：yinyanting


快速跳转



 * 组件名cap4-indicator
   * 引入
   * 基础用法
   * Attributes



分享链接分享链接

## 64. 组件名cap4-radio

> 原始路径：`/94/355/359/416/431/439.html`  
> 相对路径：`94/355/359/416/431/439.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-radio

----------------------------------------


## 引入

import Cap4Radio from 'cap4-pc-ui/lib/cap4-radio';
import 'cap4-pc-ui/lib/cap4-radio/css/cap4-radio.css';



## 基础用法

/**/

export default {
data() {
return {
value: 1,
radioArr: [
{
value: 1,
display: '北京'
},
{
value: 2,
display: '上海'
},
{
value: 3,
display: '广州'
}
],
};
}
};
/**/::: demo

<div class="demo-block">
  <cap4-radio v-model="value" :radioArr="radioArr"></cap4-radio>
</div>

<script>
export default {
    data() {
        return {
            value: 1,
            radioArr: [
                {
                    value: 1,
                    display: '北京'
                },
                {
                    value: 2,
                    display: '上海'
                },
                {
                    value: 3,
                    display: '广州'
                }
            ],
        };
    }
};
</script>


:::


## Attributes

参数         说明            类型                          可选值   默认值
value      值 (必填))       [String, Number, Boolean]   —     —
radioArr   可选择数组 (必填))   Array                       —     —
disabled   不可选 (选填))     Boolean                     —     —

编撰人：yinyanting


快速跳转



 * 组件名cap4-radio
   * 引入
   * 基础用法
   * Attributes



分享链接分享链接

## 65. 组件名cap4-search

> 原始路径：`/94/355/359/416/431/440.html`  
> 相对路径：`94/355/359/416/431/440.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-search

----------------------------------------


## 引入

import Cap4Search from 'cap4-pc-ui/lib/cap4-search';
import 'cap4-pc-ui/lib/cap4-search/css/cap4-search.css';



## 基础用法

/**/

export default {
data() {
return {
float: 'none',
showSelect: true,
width: 300,
list: [
{
value: 1,
display: '北京'
},
{
value: 2,
display: '上海'
},
{
value: 3,
display: '广州'
}
],
};
},
methods: {
search(value) {
console.log('value', value);
}
}
};
/**/::: demo

<template>
    <div class="demo-block">
        <cap4-search :float="float" @search="search"></cap4-search>
    </div>
</template>

<script>
export default {
    data() {
        return {
            float: 'none',
        };
    },
    methods: {
        search(value) {
            console.log('value', value);
        }
    }
};
</script>


:::


## 带下拉

::: demo

<template>
    <div class="demo-block">
        <cap4-search :float="float" @search="search" :showSelect="showSelect" :list="list" :width="width"></cap4-search>
    </div>
</template>

<script>
export default {
    data() {
        return {
            float: 'none',
            showSelect: true,
            width: 300,
            list: [
                {
                    value: 1,
                    display: '北京'
                },
                {
                    value: 2,
                    display: '上海'
                },
                {
                    value: 3,
                    display: '广州'
                }
            ],
        };
    },
    methods: {
        search(value) {
            console.log('value', value);
        }
    }
};
</script>


:::


## Attributes

参数            说明         类型                 可选值   默认值
value         参数 (选填))   String             —     —
width         参数 (选填))   [String, Number]   —     200
height        参数 (选填))   [String, Number]   —     30
fontSize      参数 (选填))   [String, Number]   —     14
noBorder      参数 (选填))   Boolean            —     false
showSelect    参数 (选填))   Boolean            —     false
list          参数 (选填))   Array              —     —
placeholder   参数 (选填))   String             —     $i18n('cap.common.lbsMapUi.searchPlace')
float         参数 (选填))   String             —     'right'


## Event

事件名称     说明     回调参数
search   成功回调   str/obj

编撰人：yinyanting


快速跳转



 * 组件名cap4-search
   * 引入
   * 基础用法
   * 带下拉
   * Attributes
   * Event



分享链接分享链接

## 66. 组件cap4-select

> 原始路径：`/94/355/359/416/431/441.html`  
> 相对路径：`94/355/359/416/431/441.md`  
> JS Chunk：`app.371b709c.js`

## 组件cap4-select

----------------------------------------


## 引入

import Cap4PcUiSelect from 'cap4-pc-ui/lib/cap4-select';
import 'cap4-pc-ui/lib/cap4-select/css/cap4-select.css';



## 依赖

 * 图标依赖于 cap4字体库


## 基础用法

/**/

export default {
data() {
return {
selectValue: '',
leftSpan: '选择',
leftSpanWidth: 50,
list: [
{
value: 1,
display: '北京'
},
{
value: 2,
display: '上海'
},
{
value: 3,
display: '广州'
}
],
disable: true,
searchable: true
};
},
methods: {
selectChange(value, item) {
console.log('value', value);
console.log('item', item);
}
}
};
/**/::: demo

<template>
    <div class="demo-block">
        <cap4-select
            v-model="selectValue"
            :leftSpan="leftSpan"
            :leftSpanWidth="leftSpanWidth"
            :list="list"
            @change="selectChange"
        ></cap4-select>
    </div>
</template>

<script>
export default {
    data() {
        return {
            selectValue: '',
            leftSpan: '选择',
            leftSpanWidth: 50,
            list: [
                {
                    value: 1,
                    display: '北京'
                },
                {
                    value: 2,
                    display: '上海'
                },
                {
                    value: 3,
                    display: '广州'
                }
            ]
        };
    },
    methods: {
        selectChange(value, item) {
            console.log('value', value);
            console.log('item', item);
        }
    }
};
</script>


:::


## 禁用状态

::: demo

<template>
    <div class="demo-block">
        <cap4-select
            v-model="selectValue"
            :leftSpan="leftSpan"
            :leftSpanWidth="leftSpanWidth"
            :list="list"
            :disable="disable"
            @change="selectChange"
        ></cap4-select>
    </div>
</template>

<script>
export default {
    data() {
        return {
            selectValue: '',
            leftSpan: '选择',
            leftSpanWidth: 50,
            list: [
                {
                    value: 1,
                    display: '北京'
                },
                {
                    value: 2,
                    display: '上海'
                },
                {
                    value: 3,
                    display: '广州'
                }
            ],
            disable: true
        };
    },
    methods: {
        selectChange(value, item) {
            console.log('value', value);
            console.log('item', item);
        }
    }
};
</script>


:::


## 可搜索

::: demo

<template>
    <div class="demo-block">
        <cap4-select
            v-model="selectValue"
            :leftSpan="leftSpan"
            :leftSpanWidth="leftSpanWidth"
            :list="list"
            :searchable="searchable"
            @change="selectChange"
        ></cap4-select>
    </div>
</template>

<script>
export default {
    data() {
        return {
            selectValue: '',
            leftSpan: '选择',
            leftSpanWidth: 50,
            list: [
                {
                    value: 1,
                    display: '北京'
                },
                {
                    value: 2,
                    display: '上海'
                },
                {
                    value: 3,
                    display: '广州'
                }
            ],
            searchable: true
        };
    },
    methods: {
        selectChange(value, item) {
            console.log('value', value);
            console.log('item', item);
        }
    }
};
</script>


:::


## Attributes

参数              说明             类型                 可选值   默认值
value           值 (必填))        [String, Number]   —     —
list            可选项 (必填))      Array              —     —
leftSpan        左侧文本 (选填))     String             —     —
leftSpanWidth   左侧文本宽度 (选填))   [String, Number]   —     100
listHeight      下拉框高度 (选填))    [String, Number]   —     200
disable         不可选 (选填))      Boolean            —     false
inputWidth      输入宽度 (选填))     [String, Number]   —     200
position        位置 (选填))       String             —     —
normalSelect    浏览器样式 (选填))    Boolean            —     false
showBorder      是否显示边线 (选填))   Boolean            —     true
searchable      是否可搜索 (选填))    Boolean            —     false


## Event

事件名称     说明    回调参数
change   值改变   value, item

编撰人：yinyanting


快速跳转



 * 组件cap4-select
   * 引入
   * 依赖
   * 基础用法
   * 禁用状态
   * 可搜索
   * Attributes
   * Event



分享链接分享链接

## 67. 组件名cap4-shuttle

> 原始路径：`/94/355/359/416/431/442.html`  
> 相对路径：`94/355/359/416/431/442.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-shuttle

----------------------------------------


## 引入

import Cap4Shuttle from 'cap4-pc-ui/lib/cap4-shuttle';
import 'cap4-pc-ui/lib/cap4-shuttle/css/cap4-shuttle.css';



## 基础用法

/**/

export default {
data() {
return {
// 注意root虚拟节点不显示
treeData: {
name: 'root',
id: 'root',
level: 0,
type: 'ul',
show: true,
branch: true,
showChildren: true,
children: [{
id: '0',
name: '城市',
parentId: 'root',
type: 'ul',
level: 1,
show: true,
branch: true,
showChildren: true,
children: [{
id: '1',
level: 2,
name: '北京',
parentId: '0',
show: true,
branch: false
},
{
id: '2',
level: 2,
name: '上海',
parentId: '0',
show: true,
branch: false
},
{
id: '3',
level: 2,
name: '广州',
parentId: '0',
show: true,
branch: false
}]
}]
},
dataSource: []
};
},
methods: {
leftItemClick(item) {
console.log(item);
},
chooseItem(item) {
console.log(item);
}
}
};
/**/::: demo

<template>
    <div
        class="demo-block"
    >
        <cap4-shuttle
            :treeData="treeData"
            :dataSource="dataSource"
            @leftItemClick="leftItemClick"
            @chooseItem="chooseItem"
        ></cap4-shuttle>
    </div>
</template>

<script>
export default {
    data() {
        return {
            // 注意root虚拟节点不显示
            treeData: {
                name: 'root',
                id: 'root',
                level: 0,
                type: 'ul',
                show: true,
                branch: true,
                showChildren: true,
                children: [{
                    id: '0',
                    name: '城市',
                    parentId: 'root',
                    type: 'ul',
                    level: 1,
                    show: true,
                    branch: true,
                    showChildren: true,
                    children: [{
                        id: '1',
                        level: 2,
                        name: '北京',
                        parentId: '0',
                        show: true,
                        branch: false
                    },
                    {
                        id: '2',
                        level: 2,
                        name: '上海',
                        parentId: '0',
                        show: true,
                        branch: false
                    },
                    {
                        id: '3',
                        level: 2,
                        name: '广州',
                        parentId: '0',
                        show: true,
                        branch: false
                    }]
                }]
            },
            dataSource: []
        };
    },
    methods: {
        leftItemClick(item) {
            console.log(item);
        },
        chooseItem(item) {
            console.log(item);
        }
    }
};
</script>


:::


## Attributes

参数               说明             类型                 可选值   默认值
treeData         数据 (必填))       Object             —     ''
dataSource       选中项 (选填))      Array              —     
leftLabel        左文本 (选填))      String             —     
rightLabel       右文本 (选填))      String             —     
leftWidth        左侧树宽度 (选填))    [String, Number]   —     
leftLabelWidth   左侧文本宽度 (选填))   [String, Number]   —     
rightWidth       右侧树宽度 (选填))    [String, Number]   —     
contentHeight    高度 (选填))       [String, Number]   —     
showSearchLeft   左侧可搜索 (选填))    Boolean            —     


## Event

事件名称            说明   回调参数
leftItemClick   单击   item
chooseItem      双击   item

编撰人：yinyanting


快速跳转



 * 组件名cap4-shuttle
   * 引入
   * 基础用法
   * Attributes
   * Event



分享链接分享链接

## 68. 组件名cap4-tap

> 原始路径：`/94/355/359/416/431/443.html`  
> 相对路径：`94/355/359/416/431/443.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-tap

----------------------------------------


## 引入

import Cap4Tap from 'cap4-pc-ui/lib/cap4-tap';
import 'cap4-pc-ui/lib/cap4-tap/css/cap4-tap.css';



## 基础用法

/**/

export default {
data() {
return {
tabs: [
{
value: 1,
name: '北京'
},
{
value: 2,
name: '上海'
},
{
value: 3,
name: '广州'
}
],
activeTabIndex: 0
};
},
methods: {
changeTab(index) {
this.activeTabIndex = index;
console.log('index', index);
}
}
};
/**/::: demo

<template>
    <div class="demo-block">
        <cap4-tap :tabs="tabs" @changeTab="changeTab" :activeTabIndex="activeTabIndex"></cap4-tap>
    </div>
</template>

<script>
export default {
    data() {
        return {
            tabs: [
                {
                    value: 1,
                    name: '北京'
                },
                {
                    value: 2,
                    name: '上海'
                },
                {
                    value: 3,
                    name: '广州'
                }
            ],
            activeTabIndex: 0
        };
    },
    methods: {
        changeTab(index) {
            this.activeTabIndex = index;
            console.log('index', index);
        }
    }
};
</script>


:::


## Attributes

参数               说明                类型        可选值   默认值
tabs             数据 (选填))          String    —     —
activeTabIndex   选中项 (选填))         Number    —     0
padding          padding样式 (选填))   String    —     '5px 10px'
showPartition    是否显示竖线 (选填))      Boolean   —     true
showBorder       是否显示边线 (选填))      Boolean   —     false
showTriangle     是否显示三角 (选填))      Boolean   —     false
height           高度 (选填))          Number    —     —
fontSize         字体 (选填))          Number    —     14


## Event

事件名称        说明   回调参数
changeTab   切换   index

编撰人：yinyanting


快速跳转



 * 组件名cap4-tap
   * 引入
   * 基础用法
   * Attributes
   * Event



分享链接分享链接

## 69. 组件cap4-text

> 原始路径：`/94/355/359/416/431/444.html`  
> 相对路径：`94/355/359/416/431/444.md`  
> JS Chunk：`app.371b709c.js`

## 组件cap4-text

----------------------------------------


## 引入

import Cap4Text from 'cap4-pc-ui/lib/cap4-text';
import 'cap4-pc-ui/lib/cap4-text/css/cap4-text.css';



## 依赖

 * 图标依赖于 cap4字体库


## 基础用法

/**/

export default {
data() {
return {
value: '',
value1: '',
value2: '',
leftSpan: '文本',
leftSpan1: '气温',
leftSpanWidth: 50,
rightSpan: '℃',
disabled: true,
inputBgColor: '#f3f6fa',
type: 'number'
};
},
methods: {
validate(str, rules) {
if (str < -50 || str > 50 ) {
return '气温值应该在-50℃到50℃之间';
}
}
}
};
/**/::: demo

<template>
    <div class="demo-block">
        <cap4-text
            v-model="value"
            :leftSpan="leftSpan"
            :leftSpanWidth="leftSpanWidth"
        ></cap4-text>
    </div>
</template>

<script>
export default {
    data() {
        return {
            value: '',
            leftSpan: '选择',
            leftSpanWidth: 50
        };
    }
};
</script>


:::


## 不可输入状态

::: demo

<template>
    <div class="demo-block">
        <cap4-text
            v-model="value"
            :leftSpan="leftSpan"
            :leftSpanWidth="leftSpanWidth"
            :disabled="disabled"
            :inputBgColor="inputBgColor"
        ></cap4-text>
    </div>
</template>

<script>
export default {
    data() {
        return {
            value: '',
            leftSpan: '选择',
            leftSpanWidth: 50,
            disabled: true,
            inputBgColor: '#f3f6fa'
        };
    }
};
</script>


:::


## 带验证提示

::: demo

<template>
    <div class="demo-block">
        <cap4-text
            v-model="value"
            :leftSpan="leftSpan"
            :rightSpan="rightSpan"
            :leftSpanWidth="leftSpanWidth"
            :type="type"
            :validate="validate"
        ></cap4-text>
    </div>
</template>

<script>
export default {
    data() {
        return {
            value: '',
            leftSpan: '气温',
            leftSpanWidth: 50,
            rightSpan: '℃',
            type: 'number'
        };
    },
    methods: {
        validate(str, rules) {
            if (str < -50 ||   str > 50 ) {
                return '气温值应该在-50℃到50℃之间';
            }
        }
    }
};
</script>


:::


## Attributes

参数               说明              类型                 可选值   默认值
value            值 (必填))         [String, Number]   —     —
leftSpan         左侧文本 (选填))      String             —     —
leftSpanWidth    左侧文本宽度 (选填))    [String, Number]   —     100
rightSpan        右边侧文本 (选填))     String             —     —
rightSpanWidth   右侧文本宽度 (选填))    [String, Number]   —     100
width            文本框高度 (选填))     [String, Number]   —     200
height           文本框高度 (选填))     [String, Number]   —     30
disabled         不可输入状态 (选填))    Boolean            —     false
type             类型 (选填))        String             —     'text'
validate         验证 (选填))        Function           —     —
validateWidth    验证文本宽度 (选填))    [Number, String]   —     —
rules            规则 (选填))        Array              —     —
inputBgColor     文本框背景色 (选填))    String             —     —
hideLeftColon    隐藏左文本冒号 (选填))   Boolean            —     false

编撰人：yinyanting


快速跳转



 * 组件cap4-text
   * 引入
   * 依赖
   * 基础用法
   * 不可输入状态
   * 带验证提示
   * Attributes



分享链接分享链接

## 70. 组件名cap4-tree

> 原始路径：`/94/355/359/416/431/445.html`  
> 相对路径：`94/355/359/416/431/445.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-tree

----------------------------------------


## 引入

import Cap4Tree from 'cap4-pc-ui/lib/cap4-tree';
import 'cap4-pc-ui/lib/cap4-tree/css/cap4-tree.css';



## 基础用法

/**/

export default {
data() {
return {
// 注意root虚拟节点不显示
treeData: {
name: 'root',
id: 'root',
level: 0,
type: 'ul',
show: true,
branch: true,
showChildren: true,
children: [{
id: '0',
name: '城市',
parentId: 'root',
type: 'ul',
level: 1,
show: true,
branch: true,
showChildren: true,
children: [{
id: '1',
level: 2,
name: '北京',
parentId: '0',
show: true,
branch: false
},
{
id: '2',
level: 2,
name: '上海',
parentId: '0',
show: true,
branch: false
},
{
id: '3',
level: 2,
name: '广州',
parentId: '0',
show: true,
branch: false
}]
}]
},
activeItem: []
};
},
methods: {
childClick(item) {
this.activeItem = [item];
console.log(item);
},
childDbClick(item) {
this.activeItem = [item];
console.log(item);
},
listChoose(id, items) {
console.log(id, items);
}
}
};
/**/::: demo

<template>
    <div
        class="demo-block"
    >
        <cap4-tree
            :treeData="treeData"
            :activeItem="activeItem"
            @childClick="childClick"
            @childDbClick="childDbClick"
        ></cap4-tree>
    </div>
</template>

<script>
export default {
    data() {
        return {
            // 注意root虚拟节点不显示
            treeData: {
                name: 'root',
                id: 'root',
                level: 0,
                type: 'ul',
                show: true,
                branch: true,
                showChildren: true,
                children: [{
                    id: '0',
                    name: '城市',
                    parentId: 'root',
                    type: 'ul',
                    level: 1,
                    show: true,
                    branch: true,
                    showChildren: true,
                    children: [{
                        id: '1',
                        level: 2,
                        name: '北京',
                        parentId: '0',
                        show: true,
                        branch: false
                    },
                    {
                        id: '2',
                        level: 2,
                        name: '上海',
                        parentId: '0',
                        show: true,
                        branch: false
                    },
                    {
                        id: '3',
                        level: 2,
                        name: '广州',
                        parentId: '0',
                        show: true,
                        branch: false
                    }]
                }]
            },
            activeItem: []
        };
    },
    methods: {
        childClick(item) {
            this.activeItem = [item];
            console.log(item);
        },
        childDbClick(item) {
            this.activeItem = [item];
            console.log(item);
        },
        listChoose(id, items) {
            console.log(id, items);
        }
    }
};
</script>


:::


## Attributes

参数               说明              类型        可选值   默认值
treeData         数据 (必填))        Object    —     ''
activeItem       选中项 (选填))       Array     —     
showFull         全称 (选填))        Boolean   —     
showFolderIcon   显示文件夹图标 (选填))   Boolean   —     


## Event

事件名称           说明   回调参数
childClick     单击   item
childDbClick   双击   item
listChoose     多选   id, items

编撰人：yinyanting


快速跳转



 * 组件名cap4-tree
   * 引入
   * 基础用法
   * Attributes
   * Event



分享链接分享链接

## 71. 组件名cap4-validate

> 原始路径：`/94/355/359/416/431/446.html`  
> 相对路径：`94/355/359/416/431/446.md`  
> JS Chunk：`app.371b709c.js`

## 组件名cap4-validate

----------------------------------------


## 引入

import Cap4Validate from 'cap4-pc-ui/lib/cap4-validate';
import 'cap4-pc-ui/lib/cap4-validate/css/cap4-validate.css';



## 基础用法

/**/

export default {
data() {
return {
validateStr: '验证提示信息'
};
}
};
/**/::: demo

<template>
    <div class="demo-block">
        <cap4-validate :validateStr="validateStr"></cap4-validate>
    </div>
</template>

<script>
export default {
    data() {
        return {
            validateStr: '验证提示信息'
        };
    }
};
</script>


:::


## Attributes

参数            说明             类型       可选值   默认值
validateStr   验证提示信息 (必填))   String   —     

编撰人：yinyanting


快速跳转



 * 组件名cap4-validate
   * 引入
   * 基础用法
   * Attributes



分享链接分享链接

## 72. cap4-menu 组件

> 原始路径：`/94/355/359/416/431/447.html`  
> 相对路径：`94/355/359/416/431/447.md`  
> JS Chunk：`app.371b709c.js`

## cap4-menu 组件

----------------------------------------

用于自定义门户布局框架的菜单组件


## 基本用法

<script>
  export default{
    data () {
       return {
            "fold":false,
            "data" : {
                        "shortCut" : [ {
                            "menuList" : [{
                                "menuIcon" : "/fileUpload.do?method=showRTE&fileId=4674185107131156747&createDate=2018-5-2&type=image",
                                "appId" : "5346801070781844789",
                                "menuId" : "15252411841960",
                                "menuName" : "有流程",
                                "menuType" : "listCreate",
                                "isUseCustomTemplate" : "0"
                            } ],
                            "appId" : "4198771627843666672",
                            "menuId" : "6282397618325521949",
                            "menuName" : "快速新建",
                            "menuType" : "category"
                        } ],
                        "bussImg" : "vp-icon-severeSandStorm",
                        "categoryMenu" : [...],
                        "bussName" : "xms",
                        "flowList" : [ {
                            "appId" : "6014113484955537231,5346801070781844789",
                            "menuId" : "5492484774340732977",
                            "menuName" : "审批事项",
                            "menuType" : "flowList",
                            "isUseCustomTemplate" : "0"
                        } ]
                    }
       }
    },
    methods: {
        click(item){
            alert(`你点击了【${item.menuName}】`)
        }
    }
  }
</script>
<div style='width:800px;height:400px;position:relative;'>
<Cap4Menu
    :data='data'
    @click='click'
    :fold='fold'
    :ctxPath="'http://10.5.5.204:8088/seeyon/'">
</Cap4Menu>
<button @click='fold = !fold' style='position:absolute;top:0;left:154px;'>点击切换展示状态</button>
<button @click='fold = !fold' style='position:absolute;top:0;left:154px;'>点击切换展示状态</button>
</div>



## Attributes

参数        说明                                                                  类型        可选值   默认值
data      数据源，后端请求回来的数据，包括（flowList、shortCut、categoryMenu、bussName、bussImg）   Object    —     {}
ctxPath   用在图片请求时，需要传入的BaseUrl                                                string    —     ""
fold      是否折叠菜单                                                              Boolean   —     false


## Event

事件名称    说明         回调参数
click   点击菜单项时触发   当前点击项

编撰人：yinyanting


快速跳转



 * cap4-menu 组件
   * 基本用法
   * Attributes
   * Event



分享链接分享链接

## 73. Cap4Iframe组件

> 原始路径：`/94/355/359/416/431/448.html`  
> 相对路径：`94/355/359/416/431/448.md`  
> JS Chunk：`app.371b709c.js`

## Cap4Iframe组件

----------------------------------------

Cap4Iframe 组件


## 基本用法

 * 使用 加载资源，用法同以前html标签iframe;

<Cap4Iframe src='http://www.seeyon.com/' style='width:100%;height:700px'></Cap4Iframe>
<script>
    export default {

    };
</script>


编撰人：yinyanting


快速跳转



 * Cap4Iframe组件
   * 基本用法



分享链接分享链接

## 74. toolbar组件

> 原始路径：`/94/355/359/416/431/449.html`  
> 相对路径：`94/355/359/416/431/449.md`  
> JS Chunk：`app.371b709c.js`

## toolbar组件

----------------------------------------

tool bar 组件


## 基本用法

 * tool bar 组件
 * 图标依赖于iconfont字体库

<script>
  export default{
    data () {
        return {
          buttonListData: [
            {
              authName: '新建',
              operationType: 'create',
              datas: {
                authId: '3434965240233480124',
                viewId: '-5986396426325309878'
              }
            },
            {
              authName: '修改',
              operationType: 'update',
              datas: {
                authId: '-2974825467645112856',
                viewId: '-5986396426325309878'
              }
            },
            {
              authName: '批量刷新',
              operationType: 'batchFresh',
              datas: {
                isDoTrigger:"0"
              }
            },
            {
              authName: '批量修改',
              operationType: 'batchUpdate',
              datas: null
            },
          ]
        }
    },
    methods: {
      buttonEvent(){
        console.log(arguments)
      }
    }
  }
</script>

<div class=" demo-block">
  <cap4-tool-bar :buttonListData="buttonListData" @buttonEvent="buttonEvent"></cap4-tool-bar>
</div>



## Attributes

参数               说明               类型         可选值   默认值
buttonListData   button列表 (必填))   Array      —     —
buttonEvent      事件回调             Function   —     —


## buttonListData

参数              说明                 类型       可选值                                                                                                      默认值
authName        显示label            String   —                                                                                                        —
datas           传入的data            Object   —                                                                                                        —
operationType   button type (必填)   String   create/update/batchUpdate/batchFresh/delete/lock/unlock/importAndExport/query/statistics/print/viewLog   —


## Event

事件名称          说明       回调参数
buttonEvent   点击事件回调   callBackArr, viewBid, authBid, name


## buttonEvent回调args

参数            说明        类型       可选值   默认值
callBackArr   点击类型      Array    —     —
viewBid       viewId    Number   —     —
authBid       authId    Number   —     —
name          按钮label   String   —     —

编撰人：yinyanting


快速跳转



 * toolbar组件
   * 基本用法
   * Attributes
   * buttonListData
   * Event
   * buttonEvent回调args



分享链接分享链接

## 75. 统计饼图

> 原始路径：`/94/355/359/416/450/451.html`  
> 相对路径：`94/355/359/416/450/451.md`  
> JS Chunk：`app.371b709c.js`

## 统计饼图

----------------------------------------


## 引入

import { Cap4StatisticsPieGroup } from 'cap4-business/lib/cap4-statistics';
import  'cap4-business/lib/cap4-statistics/css/cap4-statistics.css';



## 示例



<script>
  import {data} from './egdata/statisticsData.js'
  export default{
    data () {
       return {
          itemStyle:{'margin-left': '50px'},
          selectGroup:'',
          dataInfo: data
       }
    },
    methods: {
       penetrationClick(item) {
            alert('穿透：'+JSON.stringify(item))
       }
    }
  }
</script>

<div class=" demo-block">
  <Cap4StatisticsPieGroup
    :size="250"
    :selectIndex="1"
    :selectGroup="selectGroup"
    :dataInfo="dataInfo"
  >
  </Cap4StatisticsPieGroup>
</div>



## Attributes

参数            说明            类型       可选值                       默认值
size          饼图的大小         string   —                         —
itemStyle     每个饼图单元的外框样式   Object   {'margin-left': '50px'}   —
selectGroup   交叉报表，选择交叉项    string   —                         —
selectIndex   选择饼图中的1个      Number   —                         —
dataInfo      统计数据          Object   —                         —


## Event

事件名称      说明                 回调参数
outData   抛出转换为echart类型的数据   useDataInfos

编撰人：yinyanting


快速跳转



 * 统计饼图
   * 引入
   * 示例
   * Attributes
   * Event



分享链接分享链接

## 76. 统计echart组件包

> 原始路径：`/94/355/359/416/450/452.html`  
> 相对路径：`94/355/359/416/450/452.md`  
> JS Chunk：`app.371b709c.js`

## 统计echart组件包

----------------------------------------

用于页面中展示重要的提示信息。


## 基本用法



线形图

<script>
  import {data} from './egdata/statisticsData.js'
  export default{
    data () {
       return {
          itemStyle:{'margin-left': '50px'},
          dataInfo: data
       }
    },
    methods: {
       penetrationClick(item) {
            alert('穿透：'+JSON.stringify(item))
       }
    }
  }
</script>
<div class="demo-block" style='height:300px'>
    <Cap4StatisticsLineFixed
      :mode="'bar'"
      :dataInfo="dataInfo">
    </Cap4StatisticsLineFixed>
</div>



## Attributes

参数            说明                       类型        可选值                          默认值
title         标题，必选参数。也可通过默认 slot 传入   string    —                            —
type          主题                       string    success/warning/info/error   info
description   辅助性文字                    string    —                            —
closable      是否可关闭                    boolean   —                            true
center        文字是否居中                   boolean   —                            true
close-text    关闭按钮自定义文本                string    —                            —
show-icon     是否显示图标                   boolean   —                            false


## Event

事件名称    说明              回调参数
close   关闭alert时触发的事件   —

编撰人：yinyanting


快速跳转



 * 统计echart组件包
   * 基本用法
   * Attributes
   * Event



分享链接分享链接

## 77. font-class引用

> 原始路径：`/94/355/359/416/453.html`  
> 相对路径：`94/355/359/416/453.md`  
> JS Chunk：`app.371b709c.js`

## font-class引用

font-class是unicode使用方式的一种变种，主要是解决unicode书写不直观，语意不明确的问题。

与unicode使用方式相比，具有如下特点：

 * 兼容性良好，支持ie8+，及所有现代浏览器。
 * 相比于unicode语意明确，书写更直观。可以很容易分辨这个icon是什么。
 * 因为使用class来定义图标，所以当要替换图标时，只需要修改class里面的unicode引用。
 * 不过因为本质上还是使用的字体，所以多色图标还是不支持的。

使用步骤如下：


## 第一步：引入项目下面生成的fontclass代码：

<link rel="stylesheet" type="text/css" href="./iconfont.css">



## 第二步：挑选相应图标并获取类名，应用于页面：

<i class="CAP cap-icon-xxx"></i>


> "CAP"是你项目下的font-family。可以通过编辑项目查看，默认是"iconfont"。
> 
> 编撰人：yinyanting


快速跳转



 * font-class引用
   * 第一步：引入项目下面生成的fontclass代码：
   * 第二步：挑选相应图标并获取类名，应用于页面：



分享链接分享链接

## 78. 开发指南

> 原始路径：`/94/355/359/454/`  
> 相对路径：`94/355/359/454/README.md`  
> JS Chunk：`app.371b709c.js`

## 开发指南

//待补充



## 分类

1、关联 2、触发

编撰人：yinyanting




快速跳转



 * 开发指南
 * 分类



分享链接分享链接

## 79. CAP4自定义触发开发说明文档

> 原始路径：`/94/355/359/454/455.html`  
> 相对路径：`94/355/359/454/455.md`  
> JS Chunk：`app.371b709c.js`

## CAP4自定义触发开发说明文档

一、概念

CAP4中，触发的概念进行了统一，将触发分为了表间触发(标准的触发设置，即原来的触发、联动、回写)和单表触发，原人员、会议、DEE等在CAP4中都是属于单表触发的分支。因此，自定义触发的设置入口放在单表触发设置中，具体入口：应用定制平台/设计中心/具体业务包/单表触发+号，如图：



其次，根据cap3的自定义触发的规则，分为了无设置界面自定义触发和有设置界面自定义触发。无设置界面自定义触发表示不需要有具体动作设置，仅有一个动作类型的选择，有设置界面自定义触发表示需要进行具体的动作设置，进行一些业务规则的前端设置。

二、自定义触发设置代码结果

─seeyon

├─xxx

│ └─FormTriggerCustomTest1DesignManagerjava

│ └─FormTriggerCustomTest2DesignManagerjava

└─WEB-INF

 ├─cfgHome


│ └─xxx

 │      └─spring

 │            spring-test-manager.xml


├─jsp

│ └─xxx

│ └─customerTriggerTest2.jsp

三、代码示例

1、设置态

FormTriggerCustomDesignManager 自定义触发设置抽象父类 FormTriggerCustomTest1DesignManager 无界面自定义触发示例 FormTriggerCustomTest2DesignManager 有界面自定义触发示例





其中，父类方法hasSettingPage和getActionSettingUrl配合使用，只有hasSettingPage为true时，其getActionSettingUrl方法返回的url才有效。hasSettingPage默认返回false。这两个方法根据需要进行重写。目前hasSettingPage方法暂时没有使用，仅做预留


注意，父类有个默认实现方法checkFieldInActionSet，此方法是去处理修改字段时校验此字段是否参与触发关系设置的。如果业务需要进行校验，重写的时候如果有参与设置，则返回值必须为FormTriggerBean.CheckResultEnum.customerAction.getKey()；没有参与，则返回值必须为FormTriggerBean.CheckResultEnum.none.getKey()，不能为其他值，否则修改表单字段后保存会报异常。

另外，如果是有界面自定义触发，则需要在xxxController中增加getActionSettingUrl中指定的页面跳转方法，同时增加对应的jsp，此jsp就是具体的自定义触发动作的设置界面。






无界面自定义触发设置效果：



有界面自定义触发设置效果：



2、运行态

FormTriggerCustomBaseAction 自定义触发运行抽象父类 FormTriggerCustomTest1Action 无界面自定义触发运行类 FormTriggerCustomTest2Action 有界面自定义触发运行类



子类实现父类抽象方法getId()、init()和execute(FormTriggerActionContext context)；视情况重写canUse()和预执行方法preExecute，preExecute返回false为预执行不通过，会转到执行队列末尾等待下次执行，返回true表示预执行通过。canUse方法目前暂未使用

在7.0sp3基础上进行客开，有细节的区分

FormTriggerBaseActionManager 触发运行公共抽象父类 FormTriggerCustomTest1Action 无界面自定义触发运行类 FormTriggerCustomTest2Action 有界面自定义触发运行类



子类不再需要实现父类init方法，仅需实现getId和execute方法即可。其余canUse和preExecute方法视业务需求重写，preExecute返回false为预执行不通过，会转到执行队列末尾等待下次执行，返回true表示预执行通过。canUse方法目前暂未使用

注：设置态的子类和运行态的子类java文件都必须在spring文件中进行注册，否则无法使用

编撰人：yinyanting、admin




快速跳转



 * CAP4自定义触发开发说明文档



分享链接分享链接

## 80. 更新表单数据缓存

> 原始路径：`/94/355/359/457/458.html`  
> 相对路径：`94/355/359/457/458.md`  
> JS Chunk：`app.371b709c.js`

## 更新表单数据缓存

 * 根据传入从参数，可以更新后端表单的数据缓存，在保存表单时会将缓存中的值存入数据库中持久化
 * 此接口需传入JSON数据格式


## 接口请求说明：

 * http请求方式：POST
   http://ip:port/seeyon/rest/cap4/form/api/updateCacheFormData
   例如：
   http://127.0.0.1/seeyon/rest/cap4/form/api/updateCacheFormData

参数                 是否必须   参数说明
formMasterDataId   是      主表数据ID
formId             是      表单ID
fieldName          是      需要更新的字段名
fromRecordId       否      重复表数据ID
formSonTableName   否      重复表名
mergeData          是      主从表的值（类型为Map，key为主从表的表名，value为所有字段值的Map，第二层Map的key为字段名，value为字段值）


## 返回说明：

请求结果：

参数        是否必须   参数说明
code      是      http请求code
data      是      请求返回数据JSON，参考下述data
message   是      提示信息

请求结果data：

参数        是否必须   参数说明
code      是      状态码
message   是      提示信息

编撰人：yinyanting


快速跳转



 * 更新表单数据缓存
   * 接口请求说明：
   * 返回说明：



分享链接分享链接

## 81. 发起表单(Html正文)流程

> 原始路径：`/94/355/359/457/459.html`  
> 相对路径：`94/355/359/457/459.md`  
> JS Chunk：`app.371b709c.js`

## 发起表单(Html正文)流程

文档链接.

可发起指定模板的Html正文流程或表单流程。


## 推荐使用接口(Since:V80sp1)

接口请求说明：

http请求方式：POST
http://ip:port/seeyon/rest/bpm/process/start


示例：

Map<String, Object> map = new HashMap<String, Object>();
  map.put("appName", "collaboration");
  
  Map<String, Object> data1 = new HashMap<String, Object>();
  data1.put("templateCode", "asss_001");
  data1.put("draft", "0");
  data1.put("attachments", new ArrayList<Long>() {{add(3128081619541315193l); add(-1686961755437117824l);}});
  data1.put("relateDoc", "col|-2871660587841141706,-1609894079662438907");
  data1.put("subject", "aaa1");

  Map<String, Object> data2 = new HashMap<String, Object>();
  data2.put("formmain_0018", new HashMap<String, Object>(){{put("申请人", "saa"); put("车牌号", "ddd");}});
  
  data1.put("data", data2);
  
  map.put("data", data1);
        Map result = client.post("bpm/process/start" ,map);


传入参数说明：

参数        是否必须   说明
appName   是      应用类型
data      是      data参数

data参数

参数                    是否必须   说明
templateCode          是      模板编号，参见表单正文流程模板编号
draft                 是      是否为待发：0:新建-发送；1:新建-保存待发
attachments           否      协同标题区附件，Long型List，值为附件的Id。Id是附件接口响应结果中fileUrl字段的值。
relateDoc             否      协同公文的id
subject               否      未设置取模板设置的标题
data                  否      表单data参数
useNewDataStructure   否      是否使用新的表单数据格式
doTrigger             否      是否执行触发

表单data参数

参数                 是否必须   说明
formmainxxx        是      表单字段数据，json格式：key字段显示名称，value字段值（如果是cap4的附件控件，则value为附件的相关信息）
formsonxx1         是      数组结构，参考主表
thirdAttachments   否      CAP4附件参数
changedFields      否      参与计算的字段

thirdAttachments参数说明

参数             是否必须   说明
subReference   是      对应的附件字段的value值
fileUrl        是      上传的附件ID
sort           是      附件排序

请求参数示例：

{
    "appName": "collaboration",
    "data": {
        "data": {
            "formmain_0177": {
                "文本1": "测试文本1-111",
                "上传附件1": "3091996204880318295",
                "图片下拉1": "-2767075386175501632"
            },
            "formson_0185": [
                {
                    "图片下拉2": "-2767075386175501632",
                    "上传附件2": "-6092561120937621142"
                }
            ],
            "thirdAttachments": [
                {
                    "subReference": "3091996204880318295",
                    "fileUrl": "432641077895385013",
                    "sort": 1
                },
                {
                    "subReference": "-6092561120937621142",
                    "fileUrl": "355134930180197101",
                    "sort": 1
                }
            ],
            "changedFields":{
                "formmain_0177":["选人1","文本1"],
                "formson_0185":["选人2"]
            }
        },
        "templateCode": "ABC1111",
        "draft": "0",
        "attachments": [
            123456,
            123457
        ],
        "relateDoc": "col|123,456;doc|321,654",
        "subject": ""，
        "useNewDataStructure": false,
        "doTrigger": true
    }
}



## 请求表单参数说明(@Since v8.0sp2)

masterTable的结构

参数              类型         是否必填   说明
name            String     是      数据库表名称
record          Object     是      记录的数据
changedFields   String[]   否      需要计算的字段

masterTable—record的结构

参数       类型         是否必填   说明
id       long       是      数据id
fields   Object[]   是      包含字段

masterTable—record—fields的结构

参数          类型       是否必填   说明
name        String   是      数据域名称
value       String   是      数据值（优先）
showValue   String   是      显示值

subTables的结构

参数              类型         是否必填   说明
name            String     是      数据库表名称
records         Object[]   是      包含的所有数据
changedFields   String[]   否      需要计算的字段

subTables—records的结构

参数       类型         是否必填   说明
id       long       是      数据id
fields   Object[]   是      包含字段

subTables—records—fields的结构

参数          类型       是否必填   说明
name        String   是      数据域名称
value       String   是      数据值（优先）
showValue   String   是      显示值

请求参数示例(@Since v8.0sp2)：

{
    "appName": "collaboration",
    "data": {
        "data": {
            "masterTable":{
                "name":"formmain_0019",
                "record":{
                    "id":123456789101,
                    "fields":[
                        {
                            "name":"field0001",
                            "value":"",
                            "showValue":"create"
                        },
                        {
                            "name":"field0002",
                            "value":"",
                            "showValue":"one"
                        }
                    ]
                },
                "changedFields": ["field0001","field0002"]
            },
            "subTables": [
                {
                    "name":"formson_0021",
                    "records": [
                        {
                            "id": 123456789101,
                            "fields": [
                                {
                                    "name":"field0005",
                                    "value":"",
                                    "showValue":"cap"
                                }
                            ]
                        }
                    ]，
                    "changedFields": ["field0005"]
                }
            ]
        },
        "templateCode": "SOAP01",
        "draft": "0",
        "subject": "又试1下"，
        "useNewDataStructure": true,
        "doTrigger": true
    }
}


返回数据：

{
  "code" : 0,
  "data" : {
    "workitems" : [ {
      "nodeName" : "节点姓名",
      "userLoginName" : "loginName",
      "id" : "6063271658185834554",
      "userName" : "用户姓名",
      "nodeId" : "15940211100644",
      "userId" : "5647565013925644425"
    } ],
    "app_bussiness_data" : "{\"affairId\":\"-7826004588359563757\",\"summaryId\":\"2076716881761815485\"}",
    "processId" : "5724125432261003059",
    "subject" : "aaa1",
    "errorMsg" : ""
  },
  "message" : ""
}


返回参数说明：

参数              说明
code            返回码
nodeName        节点名称
userLoginName   登录名
id              wf_workitem_run.id
userName        用户名
nodeId          节点ID（ctp_affair.activity_id）
userId          人员ID
affairId        事项ID
summaryId       协同ID
processId       流程ID（ctp_affair.process_id）
subject         标题


## 过时接口(V61update)

注意V6.1此接口支持直接传入JSON数据格式。

接口请求说明：

http请求方式：POST
http://ip:port/seeyon/rest/flow/{templateCode}
例如：
http://127.0.0.1/seeyon/rest/flow/A0001


参数说明：

发起表单流程所需要参数，可以参考文档【BPM集成】中的【public ServiceResponse launchFormCollaboration(String token, String senderLoginName, String templateCode, String subject, String data, Long[] attachments, String param) throws ServiceException;】；

参数                是否必须   说明
templateCode      是      模板编号，参见表单正文流程模板编号
token             是      为登录验证后获取的身份令牌
senderLoginName   是      发起者的登录名（登录协同的登录名）
subject           是      协同的标题
data              是      HTML正文流程为html内容;取得流程正文数据支持传入json格式数据
attachments       否      附件，Long型List，值为附件的Id。Id是附件接口响应结果中fileUrl字段的值。
param             否      为控制是否流程发送。0：缺省值，发送，进入下一节点的待办（如果需要选人则保存到待发）1：不发送，保存到待发。
transfertype      否      (V6.1增加)data格式，xml:表示data为XML格式；json：表示data为json格式
formContentAtt    否      (V6.1增加) 表单附件 组件传入ID参数
accountCode       否      (V6.1增加)发起人单位编码（用于发起人兼职多单位情况，用不同单位角色发起流程）

参数获取说明：

发起表单是多参数，建议组装为MAP传参。 token身份令牌：token在CTPRestClient中已经封装好的，如果要单独获取可如下方式：

private CTPRestClient client = null;
CTPServiceClientManager clientManager = CTPServiceClientManager.getInstance("http://127.0.0.1");
client = clientManager.getRestClient();
...
String token = client.get("token/" + userName + "/" + password, String.class,"text/plain");


senderLoginName发起者的登录名:发起者登录OA的登录名，如下：

String senderLoginName ="lsm";


templateCode模板编号：对应创建模板时填写的模板编号（即ctp_template表TEMPLETE_NUMBER字段）

String templateCode ="100";


subject协同的标题:发出表单模板对应的标题，如下：

String subject ="申请流程标题";


data表单数据：表单数据信息，REST接口提供了获取已经发送的表单流程XML新方法，请参考取得流程正文数据

注意在获取表单数据XML 需要转换成String

提供已发表单转String示例：

private CTPRestClient client = null;
...
String data = client.get("flow/data/-6074085048046957774", String.class);//-6074085048046957774为已发流程ID


V6.1表单流程正文数据支持JSON格式,示例如下：

string data ="{"field1":"主表数据1","field2":"主表数据2",sub:[{"field3":"从表数据3","field4":"从表数据4","field5":"从表数据5"},{"field6":"从表数据6"},{"field10":"从表数据10","field11":"从表数据11"}]}";


注意：这里sub代表从表数据，而field1等字段信息是对应【流程表单制作】-【基础设置】中控件的【名称】字段

表单流水号场景：

现在发起流程接口只支持【计算流水号】

1.新建流水号：创建流水号：表单应用-流水号管理；

2.模板设置流水号：表单应用-流程表单设置-流程表单制作-选择控件-计算公式设置-系统数据域中选择流水号

表单附件组件场景：

1.获取附件ID：通过上传接口获得【注意：如果2个表单附件控件都是同一个附件，也需要上传2次，获取不同的ID，而不能2个表单附件控件共用一个附件ID】

2.发起接口XML/json数据中设置附件ID;

3.需要formContentAtt重设置附件ID;

List<Long> formcontentatt=new ArrayList();//表单正文组件ID，这里需要注意，就算三个正文组件上传的同一个文件，这个文件也需要通过上传接口上传三次，而给予表单控件三个不同的附件ID，不能一个ID给多个表单组件
res.put("formContentAtt",formcontentatt);//表单附件组件


> CAP4表单附件组件场景更正（Since V8.0，仅支持CAP4表单）
> 
> 更正说明：由于原有结构不支持控件多个附件或者附件无法添加到表单中的场景，因此接口请求增加_formContentAtt_参数，参数为数组格式，说明如下：

参数名            说明
subReference   表单内字段value值，如“上传附件1”的value值
fileUrl        调用附件上传接口获取的附件ID
sort           附件排序

> > CAP4表单附件组件更正调用示例

{
    "data": {
        "文本1": "示例",
        "上传附件1": "8451540374587001174"
    },
    "subject": "示例",
    "senderLoginName": "seeyon",
    "transfertype": "json",
    "formContentAtt":[
        {
            "subReference":8451540374587001174,
            "fileUrl":-7390855572027915259,
            "sort":1
        },
        {
            "subReference":8451540374587001174,
            "fileUrl":-7390855572027915268,
            "sort":2
        }
    ]
}


{
"data": {
"文本1": "示例",
"上传附件1": "8451540374587001174"
},
"subject": "示例",
"senderLoginName": "seeyon",
"transfertype": "json",
"formContentAtt":[
{
"subReference":8451540374587001174,
"fileUrl":-7390855572027915259,
"sort":1
},
{
"subReference":8451540374587001174,
"fileUrl":-7390855572027915268,
"sort":2
}
]
}

param为控制流程发送.

String param="0";


表单流程通过REST POST创建示例：

private CTPRestClient client = null;
MAP info =new HashMap();//存放上述参数
String checkUrl ="flow/"+模板ID；
...
client.post(url, info, String.class);


发起HTML正文流程示例1：

Map data = new HashMap() {
            {
                put("senderLoginName", "s1");
                put("subject", "这个是用Map方式发的");
                put("data", "正文内容");
                put("attachments",new Long[] {-1l,-5199818657160149985l});
                put("formContentAtt",formcontentatt);//表单附件控件
            }
        };
        Long flowId1 = client.post("flow/H0001" ,data, Long.class);


发起HTML正文流程示例2：

Long flowId2 = client .post("flow/H0001",
                        "{"senderLoginName":"s1","subject":"这是用JSON发的","data":"HTML正文","attachments":[-1,1]}",
                        Long.class);


返回说明

正常情况下，返回创建成功以后对应的流程Id。

返回异常说明：

异常编码    异常说明
12005   无效的token，请再次验证
21011   单位名称不能为空或不存在
25001   职务级别不存在
25002   职务级别名称为空
25003   职务级别已存在
23023   部门名称为空
23024   父部门名称为空
23025   部门已存在
24001   岗位不存在
24002   岗位名称为空
24003   岗位已存在
22129   设置人员的所属部门出错
22011   人员登录名为空
50126   按登录名查找发起人出错
50121   表单不存在
50122   无表单权限
50123   无流程表单导入出错
50124   XML解析失败
50125   模板不存在
50126   无模板访问权限
50127   非表单正文内容
50128   不是无流程表单，请检查模板编号是否正确
50129   模板为非流程模板，请检查模板编号是否正确
31013   指定流程不存在
50130   此表单已经停用
50131   无输入字段
50132   日期格式错误
50133   没有主表记录错误

编撰人：yinyanting


快速跳转



 * 发起表单(Html正文)流程
   * 推荐使用接口(Since:V80sp1)
   * 请求表单参数说明(@Since v8.0sp2)
   * 过时接口(V61update)



分享链接分享链接

## 82. Vue实战培训

> 原始路径：`/94/355/359/465/467.html`  
> 相对路径：`94/355/359/465/467.md`  
> JS Chunk：`app.371b709c.js`

## Vue实战培训


## 1 培训简介


## 1.1 内容

本次培训是一次代码实战培训，首先在了解了Vue组件核心概念和通信方式之后，将以Vue工程实现具体客开需求的角度给 大家一个更加具体的实战学习。


## 1.2 目标

认真学完之后，大家将能够初步上手使用Vue工程及组件等开发客开需求。


## 2 Vue组件


## 2.1 Vue组件介绍

组件是可复用的 Vue 实例，且带有一个名字。所以它们与 new Vue 接收相同的选项，例如 data、computed、watch、 methods 以及生命周期钩子等。可以将组件进行任意次数的复用，一个组件的 data 选项必须是一个函数，因此每个实例 可以维护一份被返回对象的独立的拷贝。

::: demo

Vue.component('button-counter', {
    data: function () {
        return {
            count: 0
        }
    },
    template: '<button v-on:click="count++">You clicked me {{ count }} times.</button>'
})


:::

在线运行示例


## 2.2 vue组件三大核心概念



2.2.1 属性

自定义属性props：prop 定义了这个组件有哪些可配置的属性

inheritAttrs：默认情况下父作用域的不被认作 props 的特性绑定将会“回退”且作为普通的 HTML 特性应用在
              子组件的根元素上。可通过设置 inheritAttrs 为 false，这些默认行为将会被去掉。
              注意：这个选项不影响 class 和 style 绑定。

data与props：data 被称之为动态数据，在各自实例中，在任何情况下，我们都可以随意改变它的数据类型和数据
             结构，不会被任何环境所影响。props 被称之为静态数据，在各自实例中，一旦在初始化被定义好类
             型时，基于 Vue 是单向数据流，在数据传递时始终不能改变它的数据类型，而且不允许在子组件中
             直接操作 传递过来的props数据，而是需要通过别的手段，改变传递源中的数据。

单向数据流：props的数据都是通过父组件或者更高层级的组件数据或者字面量的方式进行传递的，不允许直接操作
            改变各自实例中的 props数据，而是需要通过别的手段，改变传递源中的数据。


2.2.2 事件 事件修饰符

2.2.3 插槽 普通插槽和作用域插槽


## 3 Vue组件间通信


## 3.1 通过 Prop 向子组件传递数据，子组件可以通过调用内建的 $emit 方法 并传入事件名称来触发一个事件

Prop 是你可以在组件上注册的一些自定义 attribute。当一个值传递给一个 prop attribute 的时候，它就变成了
那个组件实例的一个属性。


::: demo

Vue.component('button-counter1', {
    props: ['count'],
    template: '<button v-on:click="emitAdd">You clicked me {{ count }} times.</button>',
    methods: {
        emitAdd() {
            this.$emit('add');
        }
    }
})


:::


## 3.2 利用事件总线通知事件

这种方法通过一个空的Vue实例作为中央事件总线（事件中心），用它来触发事件和监听事件,巧妙而轻量地实现了任何
组件间的通信，包括父子、兄弟、跨级。


::: demo

var Event=new Vue();
    Event.$emit(事件名, 数据);
    Event.$on(事件名, data => {});


:::


## 3.3 $parent / $children与 ref

ref：如果在普通的 DOM 元素上使用，引用指向的就是 DOM 元素；如果用在子组件上，引用就指向组件实例
$parent / $children：访问父 / 子实例


其他还有vuex，provide/inject，$attrs/$listeners等方式。

概念了解之后，我们用实际项目来学习一下。

编撰人：yinyanting




快速跳转



 * Vue实战培训
   * 1 培训简介
     * 1.1 内容
     * 1.2 目标
   * 2 Vue组件
     * 2.1 Vue组件介绍
     * 2.2 vue组件三大核心概念
   * 3 Vue组件间通信
     * 3.1 通过 Prop 向子组件传递数据，子组件可以通过调用内建的 $emit 方法 并传入事件名称来触发一个事件
     * 3.2 利用事件总线通知事件
     * 3.3 $parent / $children与 ref



分享链接分享链接

## 83. Vue进阶培训

> 原始路径：`/94/355/359/465/468.html`  
> 相对路径：`94/355/359/465/468.md`  
> JS Chunk：`app.371b709c.js`

## Vue进阶培训


## 1 培训简介


## 1.1 内容

本次培训会介绍到一些Vue中更复杂一点的知识点，并且会以实际工程中的使用作为参考讲解。


## 1.2 目标

认真学完之后，大家将会对Vue中的进阶知识有所了解。


## 2 模板语法进阶


## 2.1 输入修饰符

.lazy 
在默认情况下，v-model 在每次 input 事件触发后将输入框的值与数据进行同步 (除了上述输入法组合文字时)。
你可以添加 lazy 修饰符，从而转变为使用 change 事件进行同步：

.number
如果想自动将用户的输入值转为数值类型，可以给 v-model 添加 number 修饰符。

.trim
如果要自动过滤用户输入的首尾空白字符，可以给 v-model 添加 trim 修饰符



## 2.2 混入

混入 (mixin) 提供了一种非常灵活的方式，来分发 Vue 组件中的可复用功能。一个混入对象可以包含任意组件选项。当组件使用混入对象时，所有混入对象的选项将被“混合”进入该组件本身的选项。

// 定义一个混入对象
var myMixin = {
  created: function () {
    this.hello()
  },
  methods: {
    hello: function () {
      console.log('hello from mixin!')
    }
  }
}

// 定义一个使用混入对象的组件
var Component = Vue.extend({
  mixins: [myMixin]
})

var component = new Component() // => "hello from mixin!"


一般都采用混入文件的方式来混入

注意 ① 数据对象在内部会进行递归合并，并在发生冲突时以组件数据优先。
     ② 生命周期函数混入文件优先。



## 2.3 自定义指令和自定义过滤器

2.3.1 自定义指令

当页面加载时，该元素将获得焦点，现在让我们用指令来实现这个功能：

全局自定义指令

Vue.directive('focus', {
        // 当被绑定的元素插入到 DOM 中时……
        inserted: function (el) {
            // 聚焦元素
            el.focus()
        }
    })


如果想注册局部指令，组件中也接受一个 directives 的选项：

directives: {
        focus: {
            // 指令的定义
            inserted: function (el) {
            el.focus()
            }
        }
    }


使用：

<input v-focus>


2.3.1 自定义过滤器

Vue允许自定义过滤器，可被用于一些常见的文本格式化。

全局定义过滤器：

Vue.filter('capitalize', function (value) {
        if (!value) return ''
        value = value.toString()
        return value.charAt(0).toUpperCase() + value.slice(1)
    })


如果想注册局部指令，组件中也接受一个 filters 的选项：

filters: {
        capitalize: function (value) {
            if (!value) return ''
            value = value.toString()
            return value.charAt(0).toUpperCase() + value.slice(1)
        }
    }


使用：

{{ message | capitalize }}



## 3 组件使用进阶


## 3.1 插槽

3.1.1 普通插槽

<slot></slot>


3.1.2 具名插槽

<slot name="container"></slot>

<template v-slot:container>
    <p>A paragraph for the main content.</p>
    <p>And another one.</p>
</template>


注：一般v-slot 只能添加在 <template> 上

3.1.3 作用域插槽

<slot v-bind:user="user"></slot>

<template v-slot:default="slotProps">
    {{ slotProps.user.firstName }}
</template>



## 3.2 动态组件

在不同组件之间进行动态切换

<component v-bind:is="currentTabComponent"></component>



## 3.3 异步组件

Vue 允许以一个工厂函数的方式定义你的组件，这个工厂函数会异步解析你的组件定义。Vue 只有在这个组件需要被渲染的时候才会触发该工厂函数，且会把结果缓存起来供未来重渲染。

Vue.component('async-example', function (resolve, reject) {
    setTimeout(function () {
        // 向 `resolve` 回调传递组件定义
        resolve({
        template: '<div>I am async!</div>'
        })
    }, 1000)
    })



## 4 API使用进阶


## 4.1 vm.$nextTick( [callback] )

将回调延迟到下次 DOM 更新循环之后执行。

new Vue({
        // ...
        methods: {
            // ...
            example: function () {
            // 修改数据
            this.message = 'changed'
            // DOM 还没有更新
            this.$nextTick(function () {
                // DOM 现在更新了
                // `this` 绑定到当前实例
                this.doSomethingElse()
            })
            }
        }
    })



## 4.2 vm.$refs

一个对象，持有注册过 ref 特性 的所有 DOM 元素和组件实例，用起来有点像id。

// 组件或dom元素上添加ref属性
    <base-input ref="usernameInput"></base-input>

    // js代码中用$refs获取
    this.$refs.usernameInput



## 4.3 vm.$set( target, propertyName/index, value )

向响应式对象中添加一个属性，并确保这个新属性同样是响应式的，且触发视图更新。

export default {
      data() {
            return {
                obj: {}
            }
      },
      mounted() {
        this.$set(this.obj, 'age', 10);
      }
  }



## 5 工具使用进阶


## 5.1 vue-router

可以简单了解一下，因为我们的业务需求所以大部分工程都是多页面应用。 Vue Router 是 Vue.js 官方的路由管理器。针对于SPA(single page application):单一页面应用程序，它在加载页面时，不会加载整个页面，而是只更新某个指定的容器中内容。单页面应用(SPA)的核心之一是:更新视图而不重新请求页面;vue-router在实现单页面前端路由时，提供了两种方式：Hash模式和History模式。

hash模式 通过 hash 来实现路由 history模式 通过HTML5中的pushState 和 replaceState来实现，需要后端配合


## 5.2 axios

Axios 是一个基于 promise 的 HTTP 库

执行 GET 请求

// 为给定 ID 的 user 创建请求
    axios.get('/user?ID=12345')
    .then(function (response) {
        console.log(response);
    })
    .catch(function (error) {
        console.log(error);
    });

    // 可选地，上面的请求可以这样做
    axios.get('/user', {
        params: {
        ID: 12345
        }
    })
    .then(function (response) {
        console.log(response);
    })
    .catch(function (error) {
        console.log(error);
    });


执行 POST 请求

axios.post('/user', {
        firstName: 'Fred',
        lastName: 'Flintstone'
    })
    .then(function (response) {
        console.log(response);
    })
    .catch(function (error) {
        console.log(error);
    });


执行多个并发请求

function getUserAccount() {
    return axios.get('/user/12345');
    }

    function getUserPermissions() {
    return axios.get('/user/12345/permissions');
    }

    axios.all([getUserAccount(), getUserPermissions()])
    .then(axios.spread(function (acct, perms) {
        // 两个请求现在都执行完成
    }));



## 6 另外还有vuex，jsx，vue-hooks等，大家可以接着探索。

编撰人：yinyanting


快速跳转



 * Vue进阶培训
   * 1 培训简介
     * 1.1 内容
     * 1.2 目标
   * 2 模板语法进阶
     * 2.1 输入修饰符
     * 2.2 混入
     * 2.3 自定义指令和自定义过滤器
   * 3 组件使用进阶
     * 3.1 插槽
     * 3.2 动态组件
     * 3.3 异步组件
   * 4 API使用进阶
     * 4.1 vm.$nextTick( [callback] )
     * 4.2 vm.$refs
     * 4.3 vm.$set( target, propertyName/index, value )
   * 5 工具使用进阶
     * 5.1 vue-router
     * 5.2 axios
   * 6 另外还有vuex，jsx，vue-hooks等，大家可以接着探索。



分享链接分享链接

## 84. 前端构建

> 原始路径：`/94/355/359/465/469.html`  
> 相对路径：`94/355/359/465/469.md`  
> JS Chunk：`app.371b709c.js`

## 前端构建


## 1 培训简介


## 1.1 内容

了解vue前端构建，如何生成生产环境下的前端代码（如何出包、生成自定义控件、自定义按钮的运行端等）。


## 1.2 目标

1.了解构建的功能，知道哪些东西能放入到构建中去做。

2.了解脚手架cli3的基础功能。

3.了解代理，能够本地前后端分离开发。


## 2 Webpack


## 2.1 Webpack基本概念

Webpack 本质上是一个打包工具，它会根据代码的内容解析模块依赖，帮助我们把多个模块的代码打包。下面是Webpack官网给的一个说明图。



如上图，webpack 会把项目中使用到的多个代码模块（可以是不同文件类型），打包构建成项目运行仅需要的几个静态文件（如.js、.css等）。


## 2.2 详细说明

Webpack 是一个前端资源加载和打包工具。所谓的模块就是在平时的前端开发中， 用到一些静态资源，如JavaScript、CSS、图片等文件，webpack就将这些静态资源文件称之为模块。 webpack支持AMD和CommonJS，以及其他的一些模块系统，并且兼容多种JS书写规范， 它能对静态资源进行统一的管理以及打包发布。

Webpack受到大多数前端开发者的喜爱，因为它能够编译打包CSS，做CSS预处理， 对JS的方言进行编译，打包图片，代码压缩，混淆等等。

与其他的构建工具相比，Webpack具有如下的一些优势：

**1.对 CommonJS 、 AMD 、UMD 、ES6 的语法做了兼容； *2.对 js、css、图片等资源文件都支持打包； 3.串联式模块加载器以及插件机制，让其具有更好的灵活性和扩展性，例如提供对 CoffeeScript、ES6的支持； 4.有独立的配置文件 webpack.config.js； *5.可以将代码切割成不同的 chunk，实现按需加载，降低了初始化时间； 6.支持 SourceUrls 和 SourceMaps，易于调试； *7.具有强大的 Plugin 接口，大多是内部插件，使用起来比较灵活; 8.webpack 使用异步 IO 并具有多级缓存。这使得 webpack 很快且在增量编译上更加快。

PS: 一、CommonJS是一种后端js规范，是nodeJs遵循的一种编写js模块的规范，（是由nodejs将其发扬光大的），同时也开启了js全栈的大门。

此处主要用于webpack配置。

1、定义模块 根据CommonJS规范，一个单独的文件就是一个模块。每一个模块都是一个单独的作用域，也就是说，在该模块内部定义的变量，无法被其他模块读取，除非定义为global对象的属性

2、模块输出： 模块只有一个出口，module.exports对象，我们需要把模块希望输出的内容放入该对象

3、加载模块： 加载模块使用require方法，该方法读取一个文件并执行，返回文件内部的module.exports对象

// foobar.js
//私有变量
var test = 123;
 
//公有方法
function foobar () {
 
    this.foo = function () {
        // do someing ...
    }
    this.bar = function () {
        //do someing ...
    }
}
 
//exports对象上的方法和变量是公有的
var foobar = new foobar();
exports.foobar = foobar;

// test.js
//require方法默认读取js文件，所以可以省略js后缀
var test = require('./boobar').foobar;
 
test.bar();


二、 AMD 全称Asynchronous Module Definition 由于不是JavaScript原生支持，使用AMD规范进行页面开发需要用到对应的库函数，也就是大名鼎鼎RequireJS，AMD是 RequireJS 在推广过程中对模块定义的规范化的产出

requireJS主要解决两个问题

1、多个js文件可能有依赖关系，被依赖的文件需要早于依赖它的文件加载到浏览器 2、js加载的时候浏览器会停止页面渲染，加载文件越多，页面失去响应时间越长

requireJS的例子

// 定义模块 myModule.js
define(['dependency'], function(){
    var name = 'Byron';
    function printName(){
        console.log(name);
    }
 
    return {
        printName: printName
    };
});
 
// 加载模块
require(['myModule'], function (my){
　 my.printName();
});


UMD：Universal Module Definition（通用模块规范）

由于CommonJS和AMD都十分流行，但似乎缺少一个统一的规范。于是，UMD(通用模块规范)出现了，它可以同时支持这两种风格。

虽然这个模式的写法比较难看，但是，它同时兼容了AMD和CommonJS，而且还支持老式的全局变量规范。

是由社区想出来的一种整合了CommonJS和AMD两个模块定义规范的方法

UMD = AMD + CommonJS

总结： 1.一切皆模块（核心） 正如js文件可以是一个“模块（module）”一样，其他的（如css、image或html）文件也可视作模 块。 因此，你可以require(‘myJSfile.js’)亦可以require(‘myCSSfile.css’)。 这意味着我们可以将事物（业务）分割成更小的易于管理的片段，从而达到重复利用等的目的。

2.按需加载（性能优化） 传统的模块打包工具（module bundlers）最终将所有的模块编译生成一个庞大的bundle.js文件。 但是在真实的app里边，“bundle.js”文件可能有10M到15M之大可能会导致应用一直处于加载中状态。 因此Webpack使用许多特性来分割代码然后生成多个“bundle”文件，而且异步加载部分代码以实现按需加载。

webpack 优化 https://www.jianshu.com/p/d2152789759d


## 2.3 简单入口配置

## 入口

每个应用程序都有自己的入口文件，而Webpack构建的项目的默认的入口文件就是“./src/main.js” 。

入口使用 entry 字段来进行配置，可以是个字符串或数组或者是对象；如果是数组，数组中的所有文件会打包生成一个filename文件；如果是对象，可以将不同的文件构建成不同的文件。例如：

## loader

webpack 中提供一种处理多种文件格式的机制，便是使用 loader。我们可以把 loader 理解为是一个转换器，负责把某种文件格式的内容转换成 webpack 可以支持打包的模块。

在webpack中JavaScript，CSS，LESS，TypeScript，JSX，CoffeeScript，图片等静态文件都是模块，不同模块的加载是通过模块加载器（webpack-loader）来统一管理的当我们需要使用不同的 loader 来解析处理不同类型的文件时，我们可以在 module.rules 字段下来配置相关的规则。例如使用 Babel 来处理 .js 文件。

## plugin

在 webpack 的构建流程中，plugin 用于处理更多其他的一些构建任务。可以这么理解，模块代码转换的工作由 loader 来处理，除此之外的其他任何工作都可以交由 plugin 来完成。

webpack提供了“丰富的组件”来满足我们不同的需求，当然也可以自行实现一个组件来满足特定的需求。在webpack中，可以通过 plugins 字段来添加新的 plugin 。

输出

module.exports = {
  entry: './src/index.js' 
}

// 使用数组来对多个文件进行打包
module.exports = {
  entry: {
    main: [
      './src/foo.js',
      './src/bar.js'
    ]
  },
  rules: [ // loader
    {
      test: /\.jsx?/, // 匹配文件路径的正则表达式，通常我们都是匹配文件类型后缀
      include: [
        path.resolve(__dirname, 'src') // 指定哪些路径下的文件需要经过 loader 处理
      ],
      use: 'babel-loader', // 指定使用的 loader
    },
  ],
  plugins: [
    new UglifyPlugin() //新的plugin
  ],
  // ...
  output: {
    path: path.resolve(__dirname, 'dist'),
    filename: 'bundle.js',
  },
}


注：中文官网路径 https://www.webpackjs.com/


## 3 vue 简化配置，cli3 脚手架

为了减少webpack的配置，cli3脚手架对webpack再次封装，简化了vue的webpack配置。

实际原理就是把复杂的webpack配置给出了一套完整的适用于vue工程的默认配置。

如果有修改，只需要进行微调即可。

1.工程目录

参考demo工程。

2.css支持配置.browserslistrc ···

> 1% last 7 versions not ie <= 8 last 10 Chrome versions last 5 Firefox versions Safari >= 6 ···

3.vue.config.js是一个可选的配置文件，cli3已经存在了默认配置，我们只需要通过vue.config.js来微调配置即可。

{
    productionSourceMap: false, // 如果你不需要生产环境的 source map，可以将其设置为 false 以加速生产环境构建
    assetsDir: "static", // dist下的静态资源目录
    publicPath: "./",
    configureWebpack: {
        plugins: [
            new DistInitPlugin()
        ],
        output: {
            filename: `static/js/[name].min.js?t=${version}`,
            chunkFilename: `static/js/[name].min.js?t=${version}`
        },
        resolve: {
            alias: alias
        }
    },
    outputDir: 'dist',
    devServer: devServer,
    pages: {
        index: 'src/main.js' // 入口
    }
}


## productionSourceMap

Type: boolean

Default: true

如果你不需要生产环境的 source map，可以将其设置为 false 以加速生产环境构建。

## publicPath

Type: string

Default: '/'

部署应用包时的基本 URL。Vue CLI 会假设你的应用是被部署在一个域名的根路径上，例如 https://www.my-app.com/。如果应用被部署在一个子路径上，你就需要用这个选项指定这个子路径。例如，如果你的应用被部署在 https://www.my-app.com/my-app/，则设置 publicPath 为 /my-app/。

这个值也可以被设置为空字符串 ('') 或是相对路径 ('./')，这样所有的资源都会被链接为相对路径，这样打出来的包可以被部署在任意路径，也可以用在类似 Cordova hybrid 应用的文件系统中。

## outputDir

Type: string

Default: 'dist'

当运行 vue-cli-service build 时生成的生产环境构建文件的目录。注意目标目录在构建之前会被清除 (构建时传入 --no-clean 可关闭该行为)。

## configureWebpack

配置输出细节、构建过程、等细节化调整。

## devServer.proxy

如果你的前端应用和后端 API 服务器没有运行在同一个主机上，你需要在开发环境下将 API 请求代理到 API 服务器。这个问题可以通过 vue.config.js 中的 devServer.proxy 选项来配置。

devServer.proxy 可以是一个指向开发环境 API 服务器的字符串

下面就是本地代理到服务器 const proxySite = 'http://192.168.225.70:88' // 主干 ··· { proxy: { '/seeyon': { target: proxySite, changeOrigin: false, pathRewrite: { '^/seeyon': '/seeyon' } } }, port: 8000 } ···

官网链接 https://cli.vuejs.org/zh/config/#vue-config-js


## 自定义命令

package.json 中的scripts，可以自己组合命名执行。


## vue-cli-service build

如何构建库

用法：vue-cli-service build [options] [entry|pattern]

选项： --dest 指定输出目录 (默认值：dist) --target app | lib | wc | wc-async (默认值：app) --name 库或 Web Components 模式下的名字 (默认值：package.json 中的 "name" 字段或入口文件名)

编撰人：yinyanting、chenlin




快速跳转



 * 前端构建
   * 1 培训简介
     * 1.1 内容
     * 1.2 目标
   * 2 Webpack
     * 2.1 Webpack基本概念
     * 2.2 详细说明
     * 2.3 简单入口配置
       * 入口
       * loader
       * plugin
   * 3 vue 简化配置，cli3 脚手架
     * productionSourceMap
     * publicPath
     * outputDir
     * configureWebpack
     * devServer.proxy
     * 自定义命令
     * vue-cli-service build



分享链接分享链接

## 85. portal和业务空间

> 原始路径：`/94/355/359/479/`  
> 相对路径：`94/355/359/479/README.md`  
> JS Chunk：`app.371b709c.js`

## portal和业务空间


## 一、什么是portal？

官方定义：Portal是一种Web应用，通常用来提供个性化、单点登录、聚集各个信息源的内容，并作为信息系统表现层的宿主。聚集是指将来自各个信息源的内容集成到一个Web页面里的活动。

百度解释：portal意门户，现多用于互联网的门户（入口）网站和企业应用系统的门户系统。

1）广义注解

这里是一个应用框架，它将各种应用系统、数据资源和互联网资源集成到一个信息管理平台之上，并以统一的用户界面提供给用户，使企业可以快速地建立企业对客户、企业对内部员工和企业对企业的信息通道, 使企业能够释放存储在企业内部和外部的各种信息。 它将各种应用系统、数据资源和互联网资源集成到一个信息管理平台之上，并以统一的用户界面提供给用户，使企业可以快速地建立企业对客户、企业对内部员工和企业对企业的信息通道, 使企业能够释放存储在企业内部和外部的各种信息。

2）狭义注解

所谓门户网站（入口网站），是指通向某类综合性互联网信息资源并提供有关信息服务的应用系统。门户网站最初提供搜索引擎和网络接入服务，后来由于市场竞争日益激烈，门户网站不得不快速地拓展各种新的业务类型，希望通过门类众多的业务来吸引和留驻互联网用户，以至于目前门户网站的业务包罗万象，成为网络世界的“百货商场”或“网络超市”。从现在的情况来看，门户网站主要提供新闻、搜索引擎、网络接入、聊天室、电子公告牌（BBS）、免费邮箱、影音资讯、电子商务、网络社区、网络游戏、免费网页空间，等等。在中国，典型的门户网站有新浪网、网易和搜狐网等；台湾的著名入口网站则是以雅虎奇摩（Yahoo-Kimo）、蕃薯藤（Yam）、网路家庭（PChome）等。

从定义中我们可知portal的三个特点：

a. Personalization （个性化）：用户可以自己定制自己所需要的页面；

b. Single sign on（单点登陆）：一处登陆，处处通行；

c. Content aggregation（内容聚合）：不同来源的信息整合到一个页面中 。


## 二、什么是业务空间？

业务空间是portal的侠义体现，通过提供布局设置，栏目配置，数据源配置等机制实现客户可以定制化页面的需求，现阶段实现了portal的两个点：

a. Personalization （个性化）：用户可以自己定制自己所需要的页面；

> 通过布局设置，栏目配置等实现.

b. Single sign on（单点登陆）：一处登陆，处处通行；

> 暂时无此业务需求，未实现.

c. Content aggregation（内容聚合）：不同来源的信息整合到一个页面中 。

> 通过数据源开发和配置可以集成当前系统和其他系统的信息.


## 三、业务空间渲染过程




## 四、业务空间与JSR-168

JSR-168是适合于portlet开发人员的Java API集合，JSR286是JSR168的增强版,对JSR168向后兼容。在JSR-168/JSR-268中将页面分为三个部分：1）Portal Server， 2） Portlet Container , 3) Portlet



1) Portal Server

一个Portal(门户网站)就是指一个Web-based的系统，通常都会提供个性化设置，单一登陆、以及由各种不同来源或者网站取得各式各样的信息，并且将这些信息放在网页之中组合而成的呈现平台，门户网站会由精巧的个性化设置去提供定制的网页，当不同等级的使用者来浏览该页面将获得不同的信息内容。


2) Portlet Container

Portlet Container 是提供portlets执行的环境，包含了很多porlets并管理他们的生命周期，他也会保存着portlets的喜好设置，一个portlet container接收到来自portal的请求后，接着将这个请求传递给存在container的portlet执行，portlet container没有义务去组合portlets产生的信息内容，这个工作必须由portal来处理，portal和portlet和portlet container可以放在一起视为一个系统的组件，或者分开为两个独立的组件。

3) Portlet

一个Portlet是以Java技术为基础的Web组件，由Portlet Container所管理，专门处理客户的request以及产生各种动态的信息内容。Portlets分为可拔插(pluggable)的客户界面组件，提供呈现层成为一个信息系统。

这些由portlet产生的内容称为片段（fragment），而片段是具有一些规则的Markup(HTML, XHTML, WML)，而且可以和其他的片段组合为一个复杂的文件。而Portlet中的内容正常来说是与其他Portlet的内容聚合而成为一个Portal网页。而Porttlet的生命周期是被Portlet Container所管理控制的。

客户端和portlets的互动是由portal通过典型的request/response方式实现，正常来说，客户回和portlets所产生的内容互动，举例来说，根据下一步的连接或者确认送出的form请求，结果portal将回接收到portlet的动作，将这个处理状态转向目标的portlet。这些portlet内容的产生可能会因为不同的使用者而有不同的变化，完全是根据客户对于这个portlet的设置。

## JSR-168参考实现

a) Spring Portlet MVC

b) juzuweb

以Spring Portlet MVC开发示例，以下摘自Spring Portlet MVC开发入门示例

----------------------------------------

Spring Portlet MVC和其Web MVC可以说是如出一辙,只是在Web MVC中处于核心的DispatcherServlet在Portlet MVC中换成了DispatcherPortlet,如下图描述了Portlet request是如何被处理的.关于Spring 的Web MVC,请参照 http://blog.csdn.net/kkdelta/article/details/7274708



DispatcherPortlet配置在portlet.xml文件中,它继承了Portlet标准中的GenericPortlet,所以它本质上是一个能够将Portlet Request dispatch到Spring框架中其它MVC组件的一个Portlet.配置如下:

<portlet>
 <portlet-name>helloWorld</portlet-name>
 <portlet-class>org.springframework.web.portlet.DispatcherPortlet</portlet-class>
 <supports>
  <mime-type>text/html</mime-type>
  <portlet-mode>view</portlet-mode>
 </supports>
 <resource-bundle>content.Language-ext</resource-bundle>
 <portlet-info>
  <title>Hello World</title>
 </portlet-info>
</portlet>


这里以Render Request处理为例,当DispatcherPortlet接收到Request的时候,它会根据handermapping的配置找到相应的Controler来处理请求.Controler处理完后返回一个ModelAndView,对于View的处理则和Web MVC类似了,这里不再做介绍.

<bean id="helloWorldController"
 class="chapter07.code.listing.HelloWorldController"></bean>

<bean id="portletModeHandlerMapping"
 class="org.springframework.web.portlet.handler.PortletModeHandlerMapping">
 <property name="portletModeMap">
  <map>
   <entry key="view">
    <ref bean="helloWorldController" ></ref>
   </entry>
  </map>
 </property>
</bean>
<bean id="viewResolver"
 class="org.springframework.web.servlet.view.InternalResourceViewResolver">
 <property name="viewClass"
  value="org.springframework.web.servlet.view.JstlView" ></property>
 <property name="prefix" value="/WEB-INF/jsp/" ></property>
 <property name="suffix" value=".jsp" ></property>
</bean>


public class HelloWorldController implements Controller { public void handleActionRequest(ActionRequest request, ActionResponse response) throws Exception { //-- do nothing the Hello World portlet doesn't receive //-- action requests. }
public ModelAndView handleRenderRequest(RenderRequest request, RenderResponse response) throws Exception { Map<String, Object> model = new HashMap<String, Object>(); model.put("helloWorldMessage", "Hello World"); return new ModelAndView("helloWorld", model); } } 本文的例子参照了Portlets in Action,完整代码可以从http://download.csdn.net/detail/kkdelta/4125924下载. 这个例子可以运行在Liferay的Portal server上,关于Portlet和LifeRay的介绍可以参考 http://blog.csdn.net/kkdelta/article/category/1082877

Spring的Controller提供了处理Render request和Action request的方法,对于处理Event和resource类型的request可以分别实现EventAwareController和ResourceAwareController.

同时通过注解的方式也可以mapping响应的request到具体的方法进行处理.Spring提供了@Controller,@RenderMapping和@ActionMapping等等.

----------------------------------------

## 业务空间是否符合JSR-168规范？

业务空间并不符合JSR-168规范。JSR-168是一个Portal在Java API参考，JSR-168的三个组件（Portal Server，Portlet Container , Portlet）我们并没有参考其API去做实现。


## 五、业务空间与V5空间

我们先看下jquery-ui-portal的截图



大家是否有发现如果仅仅从布局和功能上，jquery-ui-portal与我们的门户(V5门户和业务空间)大体一样。

## 5.1 V5门户是一个非常典型和完整的Portal实现

包含以下功能特点：

a. Personalization （个性化）：用户可以自己定制自己所需要的页面；

b. Single sign on（单点登陆）：一处登陆，处处通行；

c. Content aggregation（内容聚合）：不同来源的信息整合到一个页面中 ；

d. 消息通知。

## 5.2 V5门户开发栏目过程

V5门户采用针对业务场景制作一个栏目，所以V5门户采用开发栏目的方式，可以将各个系统的信息整合到V5门户页面上来，栏目开发包含以下内容：

a) 后端开发一个类BannerSection并继承BaseSectionImpl；

::: demo

public class BannerSection extends BaseSectionImpl {

 @Override
    public String getResolveFunction(Map<String, String> preference) {
        return BannerTemplete.RESOLVE_FUNCTION;
    }

    @Override
 public String getIcon() {
  return null;
 }

 @Override
 public String getId() {
  return "banner";
 }
 
 public boolean isNoHeaderSection() {
  return true;
 }
 
 @Override
 public String getBaseName() {
  return ResourceUtil.getString("space.section.banner");
 }
 @Override
 public String getBaseNameI18nKey(){
  return "space.section.banner";
 }

 @Override
 public String getName(Map<String, String> preference) {
  return ResourceUtil.getString("space.section.banner");
 }

 @Override
 public Integer getTotal(Map<String, String> preference) {
  return null;
 }

 @Override
 public BaseSectionTemplete projection(Map<String, String> preference) {
  BannerTemplete bannerHtml= this.getHTML(preference);
  return bannerHtml;
 }
 
 public BannerTemplete getHTML(Map<String, String> preference) {
  int columnsStyle = this.getSectionProperty(0, preference, "columnsStyle");
  String textAlign = "left";
  if(columnsStyle == 3){
      textAlign = "center";
  } else if(columnsStyle == 4){
      textAlign = "right";
  }
  int height = this.getSectionProperty(60, preference, "height");
  int fontSize = this.getSectionProperty(4, preference, "fontSize");
  int fontStyle = this.getSectionProperty(1, preference, "fontStyle");
  String fontColor = preference.get("fontColor");
  if(Strings.isBlank(fontColor)){
   fontColor= "0";
  }
  String backgroundColor = preference.get("backgroundColor");
  if(Strings.isBlank(backgroundColor)){
   backgroundColor= "";
  }
  if("0".endsWith(fontColor)){  
   fontColor= "#4c6498";
  }else if("1".endsWith(fontColor)){
   fontColor= "#ff0000";
  }else if("2".endsWith(fontColor)){
   fontColor= "#ff7c03";
  }else if("3".endsWith(fontColor)){
   fontColor= "#5c3d09";
  }else if("4".endsWith(fontColor)){
   fontColor= "#ffff00";
  }else if("5".endsWith(fontColor)){
   fontColor= "#00ff00";
  }else if("6".endsWith(fontColor)){
   fontColor= "#0000ff";
  }else if("7".endsWith(fontColor)){
   fontColor= "#ff00ff";
  }else if("8".endsWith(fontColor)){
   fontColor= "#6e6e6e";
  }else if("9".endsWith(fontColor)){
   fontColor= "#000000";
  }
  String backgroundRepeat = preference.get("backgroundTile");
  if(Strings.isBlank(backgroundRepeat)){
   backgroundRepeat = "inherit";
  }

  String slogan = preference.get("slogan");
  if (slogan==null) {
   if (ProductEditionUtil.isG6Verson(ProductEditionEnum.getCurrentProductEditionEnum().getKey() + "")) {
    slogan= ""; 
   }else{
    slogan = Constants.getSloganKey();
   }
  }
  slogan = Functions.toHTML(ResourceUtil.getString(slogan));

  String resSuff = Functions.resSuffix();
  String banner = preference.get("background");
  String defaultBanner = "/apps_res/v3xmain/images/banner/space_banner.gif";
//  String defaultBanner = "none";
  if (Strings.isBlank(banner)) {
   banner = defaultBanner;
  } else if (!defaultBanner.equals(banner)) {
   String[] banners = banner.split(",");
   if (banners.length > 0) {
    String bannerUrl= banners[0];
    if(Strings.isNotBlank(bannerUrl) && Strings.isDigits(bannerUrl)){
     banner = "/fileUpload.do?method=showRTE&fileId=" + banners[0] + "&type=image";
     resSuff = "";
    }else{
     banner = bannerUrl;
    }
   }
  }
  BannerTemplete bannerTemplete= new BannerTemplete();
  bannerTemplete.setBanner(banner);
  bannerTemplete.setSlogan(slogan);
  bannerTemplete.setBackgroundColor(backgroundColor);
  bannerTemplete.setBackgroundRepeat(backgroundRepeat);
  bannerTemplete.setFontColor(fontColor);
  bannerTemplete.setFontSize(fontSize+"");
  bannerTemplete.setFontStyle(fontStyle+"");
  bannerTemplete.setHeight(height+"");
  bannerTemplete.setTextAlign(textAlign);
  bannerTemplete.setResSuff(resSuff);
  bannerTemplete.setMarqueeStyle(columnsStyle+"");
  return bannerTemplete;
 }

 public String getHTML(String entityId, String ordinal, String spaceType, String ownerId, Long spaceId) {
  Map<String, String> preference = getPrefenerce(entityId, ordinal, spaceType, ownerId, null, null, null);
  return null;
 }

 private int getSectionProperty(int defaultValue, Map<String, String> preference, String property) {
  String value = preference.get(property);
  if (Strings.isNotBlank(value)) {
   return NumberUtils.toInt(value);
  }
  return defaultValue;
 }

    @Override
    public int getHeight(Map<String, String> preference) {
        String heightStr = preference.get(PropertyName.height.name());
        int height = 60;
        if (NumberUtils.isDigits(heightStr)) {
            height = Integer.parseInt(heightStr);
        }
        return height;
    }

}


:::

b) 在spring配置文件中加入BannerSection配置;

:::demo

<!-- 横幅 -->
    <bean id="banner" class="com.seeyon.ctp.portal.section.BannerSection">
        <property name="sectionType" value="common" ></property>
        <property name="sortId" value="1004" ></property>
        <property name="spaceTypes" value="personal,personal_custom,leader,outer,department,custom,corporation,public_custom,group,public_custom_group,cooperation_work,form_application,edoc_manage,objective_manage,meeting_manage,performance_analysis,related_project_space,big_screen,before_login,v_report" ></property>
        <property name="resourceBundle" value="com.seeyon.v3x.main.resources.i18n.MainResources" ></property>
        <property name="properties">
            <list>
                <bean class="com.seeyon.ctp.portal.section.SectionPropertyImpl">
                    <property name="reference">
                        <list>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="height" ></property>
                                <property name="subject" value="cannel.data.height" ></property>
                                <property name="valueType" value="2" ></property>
                                <property name="validate" value="isInteger" ></property>
                                <property name="validateValue" value="max=2000 min=10" ></property>
                                <property name="defaultValue" value="60" ></property>
                                <!-- 高度帮助图片 -->
                                <!--<property name="helpType" value="1" ></property> -->
                                <!--<property name="helpValue" value="help-height.png" ></property> -->
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="slogan" ></property>
                                <property name="subject" value="cannel.data.word" ></property>
                                <property name="valueType" value="2" ></property>
                                <property name="validate" value="maxLength" ></property>
                                <property name="validateValue" value="maxSize=600" ></property>
                                <property name="editSuffix" value="EditionSuffix" ></property>
                                <property name="defaultValue" value="space.label.slogan.default" ></property>
                                <property name="hiddenValue">
                                    <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                        <property name="name" value="slogan" ></property>
                                        <property name="editSuffix" value="EditionSuffix" ></property>
                                        <property name="defaultValue" value="space.label.slogan.default" ></property>
                                    </bean>
                                </property>
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="columnsStyle" ></property>
                                <property name="subject" value="cannel.wordstyle.label" ></property>
                                <property name="valueType" value="0" ></property>
                                <property name="defaultValue" value="0" ></property>
                                <property name="valueRanges">
                                    <list>
                                        <bean class=" com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="columnsStyle.0.label" ></property>
                                            <property name="value" value="0" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="columnsStyle.3.label" ></property>
                                            <property name="value" value="3" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="columnsStyle.4.label" ></property>
                                            <property name="value" value="4" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="columnsStyle.1.label" ></property>
                                            <property name="value" value="1" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="columnsStyle.2.label" ></property>
                                            <property name="value" value="2" ></property>
                                        </bean>
                                    </list>
                                </property>
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="fontSize" ></property>
                                <property name="subject" value="cannel.data.fontSize" ></property>
                                <property name="valueType" value="0" ></property>
                                <property name="defaultValue" value="2" ></property>
                                <property name="valueRanges">
                                    <list>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="fontSize.0.label" ></property>
                                            <property name="value" value="0" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="fontSize.1.label" ></property>
                                            <property name="value" value="1" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="fontSize.2.label" ></property>
                                            <property name="value" value="2" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="fontSize.3.label" ></property>
                                            <property name="value" value="3" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="fontSize.4.label" ></property>
                                            <property name="value" value="4" ></property>
                                        </bean>
                                    </list>
                                </property>
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="fontStyle" ></property>
                                <property name="subject" value="cannel.data.fontStyle" ></property>
                                <property name="valueType" value="0" ></property>
                                <property name="defaultValue" value="1" ></property>
                                <property name="valueRanges">
                                    <list>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="fontStyle.0.label" ></property>
                                            <property name="value" value="0" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="fontStyle.1.label" ></property>
                                            <property name="value" value="1" ></property>
                                        </bean>
                                    </list>
                                </property>
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="fontColor" ></property>
                                <property name="subject" value="cannel.data.fontColor" ></property>
                                <property name="valueType" value="11" ></property>
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="backgroundColor" ></property>
                                <property name="subject" value="cannel.data.backgroundColor" ></property>
                                <property name="valueType" value="11" ></property>
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="background" ></property>
                                <property name="subject" value="section.name.banner.background" ></property>
                                <property name="valueType" value="4" ></property>
                                <property name="defaultValue" value="/apps_res/v3xmain/images/banner/space_banner.gif" ></property>
                                <property name="hiddenValue">
                                    <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                        <property name="name" value="bannerFileName" ></property>
                                        <property name="defaultValue" value="/apps_res/v3xmain/images/banner/space_banner.gif" ></property>
                                    </bean>
                                </property>
                            </bean>
                            <bean class="com.seeyon.ctp.portal.section.SectionReferenceImpl">
                                <property name="name" value="backgroundTile" ></property>
                                <property name="subject" value="cannel.background.image.displayStyle" ></property>
                                <property name="valueType" value="5" ></property>
                                <property name="defaultValue" value="inherit" ></property>
                                <property name="valueRanges">
                                    <list>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="cannel.background.tile" ></property>
                                            <property name="readOnly" value="false" ></property>
                                            <property name="value" value="inherit" ></property>
                                        </bean>
                                        <bean class="com.seeyon.ctp.portal.section.SectionReferenceValueRangeImpl">
                                            <property name="subject" value="cannel.background.notile" ></property>
                                            <property name="readOnly" value="false" ></property>
                                            <property name="value" value="no-repeat" ></property>
                                        </bean>
                                    </list>
                                </property>
                            </bean>
                        </list>
                    </property>
                </bean>
            </list>
        </property>
    </bean>


:::

c) 开发栏目的前端部分：

i tpl-bannerTemplete.html：栏目前端模板文件；

ii tpl-bannerTemplete.js：栏目前端JS事件交互文件；

iii tpl-bannerTemplete.css：栏目前端样式文件；

## 5.3 V5门户优点

a）针对业务场景制作栏目，基本可以满足各种业务场景的信息集成需求；

b）基础栏目开发简单，一个Section后端类 + 一个前端模板文件(html/js)

## 5.4 V5门户缺点

a) V5针对业务场景制作栏目，对于前端显示模板的复用性不高，无法多个后端Section公用一套前端显示模板；

b) V5栏目机制上不满足一个Section后端类 + 多个前端模板文件；

c) V5的门户不可以随业务包导入导出；

d) V5的门户不可以通过商城增加栏目；

## 5.5 业务空间与V5门户比较

业务空间大多理念和使用来源于V5门户，然而业务空间与V5门户有着本质上的区别：

> 业务空间是开发数据源拓展可取数的范围，通过开发栏目拓展数据的展现方式；而V5是开发一个个前端+后端的栏目。

a) 业务空间前后端以规定的数据格式进行交互。a)前端栏目开发者面基于已确定好的数据格式开发栏目展现；b) 后端根据栏目取数参数获取数据；3)数据格式返回由平台统一指定。

b) 栏目的开发是不需要关注业务的，只需要知道数据格式及支持的操作（基于此业务空间的栏目开发可以脱离V5环境进行开发工作）；

c) 由于b)的存在，业务空间在业务场景适配上无法做到V5门户那么定制化的需求。

d) 业务空间的配置（布局，栏目，数据源配置等）可以随业务包导出；

e) 业务空间可以通过商城增加栏目；

编撰人：yinyanting、admin




快速跳转



 * portal和业务空间
   * 一、什么是portal？
   * 二、什么是业务空间？
   * 三、业务空间渲染过程
   * 四、业务空间与JSR-168
     * JSR-168参考实现
     * 业务空间是否符合JSR-168规范？
   * 五、业务空间与V5空间
     * 5.1 V5门户是一个非常典型和完整的Portal实现
     * 5.2 V5门户开发栏目过程
     * 5.3 V5门户优点
     * 5.4 V5门户缺点
     * 5.5 业务空间与V5门户比较



分享链接分享链接

## 86. 0、开发流程示意图

> 原始路径：`/94/355/359/479/480.html`  
> 相对路径：`94/355/359/479/480.md`  
> JS Chunk：`app.371b709c.js`

## 0、开发流程示意图




## ## 1、node版本：

10.24.1

下载地址：以往的版本 | Node.js (nodejs.org)


## 2、代码工程：（查看附件）

此工程是空间中栏目制作，主题制作的基础工程，无需依赖A8，可直接启动。

无依赖版本：[column_factory-无依赖.zip]

ps：需要自行在文件夹中运行npm i，重新安装依赖

如果安装报错，可尝试下载全量版本

全量版（包含依赖）：[column_factory.zip]

启动命令：npm run serve


## 3、单独栏目源码：

附件：column-menu-vertical.zip

使用方法：




## 4、工程启动后页面




## ## QA:

Q1：如果启动报错

A1：删除目录下node_modules，在目录中重新执行命令 npm i 安装依赖

Q2：如果执行npm i 报错

A2：检查node 版本是不是10.xx.xx的

编撰人：yinyanting




快速跳转



 * 0、开发流程示意图
 * 
 * 1、node版本：
 * 2、代码工程：（查看附件）
 * 3、单独栏目源码：
 * 4、工程启动后页面
 * 
 * QA:



分享链接分享链接

## 87. 栏目前端说明

> 原始路径：`/94/355/359/479/481/`  
> 相对路径：`94/355/359/479/481/README.md`  
> JS Chunk：`app.371b709c.js`

## 栏目前端说明

----------------------------------------


## 1.简介

1.提供了多种api处理，方便栏目扩展特殊功能。

2.栏目有一整套的更新机制，方便在线升级，并且支持栏目版本回退。

3.同一个门户支持栏目多版本。

4.支持后端数据源开发。

5.支持导入导出、门户离线交付。

6.降低客开要求，栏目开发者只需要关注栏目的渲染，并且只需要考虑正常获取数据的情况。

7.支持v5不同版本数据兼容。

8.[v8.1]门户支持多视图，允许门户自身配置多页面。


## 2.门户模型图



编撰人：yinyanting




快速跳转



 * 栏目前端说明
   * 1.简介
   * 2.门户模型图



分享链接分享链接

## 88. 快速开始

> 原始路径：`/94/355/359/479/481/482.html`  
> 相对路径：`94/355/359/479/481/482.md`  
> JS Chunk：`app.371b709c.js`

## 快速开始

业务空间开发栏目需要使用脚手架工程，工程在源码cap-front/column_factory下

node版本建议：10.24.xx

进入工程后先执行npm i 安装依赖


## 1.快速开发

## 特点

1.从源栏目copy一份出来，修改后可直接上线（涉及到配置，必须使用create命令来进行栏目copy）。

2.适用于大部分业务场景，覆盖现阶段所有数据类型。

3.上手成本低，无需深入理解整个门户运行机制。

## npm run create 命令使用

## step 1

在文档的已开发栏目中选取跟自身需求类似的栏目，在url中获能够看到栏目的文件夹名称，这里用column-menu-grid栏目来举例。



## step 2

在控制台中运行npm run create,运行命令之前，让工程处于关闭状态。 创建模式中选择第二种【指定】创建栏目



## step 3

选中我们看中的栏目，回车运行。



## step 4

输入栏目名称test1,通过copy程序生成了column-test1栏目,开发者就可以进入工程的packages/column-test1下对栏目进行开发。

## ps：copy程序会自动写入栏目的唯一认证uuid、css重命名、栏目重命名等必要信息，不要自己手动copy栏目，防止出现栏目冲突。



## step 5

启动工程npm run serve后，就会发现刚才新建的栏目已经挂载到已开发栏目下。


## 2.栏目打包

1.输入命令npm run lib,选中column-test1后回车，出现提示是否上传商城选择【是】，此处没有进行商城链接并不会真正上传到商城，但是会生成上传商城的附件shop/column-test1.clmn。

## 有了这个文件后就可以在商城上架栏目商品或者直接通过门户设置中的本地导入功能导入栏目。



编撰人：yinyanting




快速跳转



 * 快速开始
   * 1.快速开发
     * 特点
     * npm run create 命令使用
       * step 1
       * step 2
       * step 3
       * step 4
       * ps：copy程序会自动写入栏目的唯一认证uuid、css重命名、栏目重命名等必要信息，不要自己手动copy栏目，防止出现栏目冲突。
       * step 5
   * 2.栏目打包
     * 有了这个文件后就可以在商城上架栏目商品或者直接通过门户设置中的本地导入功能导入栏目。



分享链接分享链接

## 89. 门户空间配置文件

> 原始路径：`/94/355/359/479/481/483.html`  
> 相对路径：`94/355/359/479/481/483.md`  
> JS Chunk：`app.371b709c.js`

## 门户空间配置文件

----------------------------------------

门户模板的核心配置文件，栏目配置包含在config.layout下，

栏目开发者只需关心自己栏目挂载的位置，方便问题调试与查看自己栏目配置在总配置的什么地方。

其它情况无需查看此页。


## 配置文件总览

布局相关层级

> layout
> 
> > spaces -- 8.1之后，新增视图层
> 
> > layout-- 8.1之后，新增视图层,视图层内又循环嵌套整个config结构
> > 
> > > rows --行
> > > 
> > > > cols --列
> > > > 
> > > > > columnGroups --栏目组
> > > 
> > > > 

栏目相关层级 从商城的下载的栏目配置文件会挂载到columnGroups的columns数组下。

> columnGroups --栏目组
> 
> > columns --栏目
> > 
> > > elements --栏目元素

示意图：

配置文件具体详情

{
    "id": "4902333343970836725",        -- configId，跟url上configId相同，用于请求数据。
    "layoutId": "6915691805717513441",  // 布局id，用于定位已选布局。
    "themeId": "4902333343970836725",   // 主题id，用于加载主题css。
    "left": {                           // 左侧布局区域，用于放置菜单等边侧栏目。
    },
    "top": {},  // 顶部布局区域，用于放置菜单等顶部栏
    "right": {}, // 右侧区域，用于放置菜单等顶部栏
    "bottom": {},// 顶部布局区域，用于放置菜单等顶部栏
    "layout": { // 主视图区域
        "mode":["1"], // 1:打开了左侧，2：打开顶部边侧，两侧可以同时打开
        "spaces":[], // 8.1之后，整个config可能会放入到spaces中，制作多视图门户。
        "rows": [
            {
                "class": "layout-height-100", // 可以给行设置样式
                "cols":[
                    {
                        "class": "col-6",        // 必须要有[col-*]，用于控制栏目横向所占百分比，也可以加自己的样式。
                        "columnGroups": [{      // 栏目组
                            "headerHidden": "1", // 是否隐藏头
                            "columns": [         // 存储栏目单元的数组
                                {
                                    "id": "123456", // 栏目id
                                    "name": "栏目右上角", // 栏目名称
                                    "UUID": "UUID11111111",
                                    "options": [
                                        {"type": "text", name: "高级筛选1"}
                                    ],
                                    "elements": [
                                        {
                                            "id": "123456",
                                            "name": "栏目元素",
                                            "description": "", // 数据源描述信息【可有】
                                            "dataFormat": "", // 数据格式
                                            "dataVersion": "v1"
                                        },
                                        {
                                            "id": "123456",
                                            "name": "更多",
                                            "description": "", // 数据源描述信息【可有】
                                            "linkToColumnGroupRight": "1" , // 是否连接到栏目组右上角
                                            "dataFormat": "",
                                            "dataVersion": "v1"
                                        }
                                    ]
                                }
                            ]
                        }]
                    },
                    { // 列
                        "class": "col-6",
                        "columnGroups": []
                    }
                ]
            }
        ]
    }
}



## config对象属性

参数         说明     类型       可选值           备注
id         配置id   String   —             —
layoutId   模板id   String   —             —
themeId    类型     String   —             —
left       类型     Object   rows/column   边侧布局因为要单独放菜单，所以要支持单独栏目展示，也得支持布局rows。现阶段不支持边侧再布局，只支持单独栏目展示。
top        类型     Object   rows/column   同上
right      类型     Object   rows/column   同上
bottom     类型     Object   rows/column   同上
layout     类型     Object   rows          只支持布局方式，如果是单栏目，也要套用布局。


## 布局主要属性

参数             说明     类型       可选值   备注
rows           配置id   String   —     —
cols           模板id   String   —     —
columnGroups   栏目组    String   —     用于挂载栏目对象

编撰人：yinyanting


快速跳转



 * 门户空间配置文件
   * 配置文件总览
     * config对象属性
     * 布局主要属性



分享链接分享链接

## 90. 栏目配置文件

> 原始路径：`/94/355/359/479/481/484.html`  
> 相对路径：`94/355/359/479/481/484.md`  
> JS Chunk：`app.371b709c.js`

## 栏目配置文件

----------------------------------------

此处是栏目开发者重点关注文档、配置文件涵盖了栏目跟平台的链接定义、支持的数据源范围等。

详细需要参考 09 栏目类型 ，根据自身业务类型合理选择栏目。


## 1.栏目基本信息

栏目存放路径 packages/ 栏目的文件夹结构

├─src
│  ├─css         --栏目实现所依赖的css文件
│  ├─img         --栏目实现中所依赖的图片文件
│  └─column.vue  --栏目实现
├─config.json     --栏目配置文件.
├─mySection.png   --[v8.1]栏目封面，本地导入的时候也能看到封面图片。
└─index.js        --栏目组件vue入口文件。可以在组件注入vue之前，处理一些环境变量。



## 2.栏目配置文件

{
    "id": "4902333343974444",  // 【必须】栏目id
    "name": "栏目名称",         // 【必须】栏目名称
    "bgColor": "red"  // 【可选】可预制栏目背景色。
    "UUID": "UUID11213111111", // 【必须】栏目UUID，每个栏目都有一个自己的物理UUID，用于请求栏目物理文件。
    "height": 300, // 【必须】栏目高度，一般还是要写上，方便可设置栏目高度。ps：不写栏目不会报错，但是不能预占位。
    "fullPage": "1" // 【可选】'是否是全屏模式,'1':全屏模式 ''：根据height自定义高度',
    "minHeight": 20, // 【可选】如果不设置，默认为20，标识栏目最低高度。
    "maxHeight": 2000, //[V8.1SP1]【可选】如果不设置，默认为2000，标识栏目最大高度。
    "platform": 1,// 【必须】1：pc，2：移动 0：全部
    "heightReload": true,// 【可选】true：在编辑态高度变化时候，让平台销毁自己（重新挂载：主要为了解决echarts等canvas在栏目大小变化时无法重绘等问题、栏目开发者无需自己写监听，由平台统一处理）。 
    "forceReload": true,// 【可选】true：在编辑态高度变化时候，让平台销毁自己，重新挂载。
    "onResizeReload": true,// 【可选】true：编辑态跟运行态中，浏览器窗口变化，重新挂载自身栏目。
    "autoHeight": true, // 【可选】true：把height 转换为min-height。可做动态伸缩高度的栏目。
    "noBgColor": true, // 【可选】true：不允许设置背景色。
    "skipNoDataCheck": true, // 【可选】默认为：false：是否跳过默认的无数据检查 PS:如果设置为true，那么必须自己需要确认无数据场景栏目不能报错。
    "skipEgCheck": true, // 【可选】默认为：false：是否跳过默认的eg检查。PS:如果设置为true，那么必须自己判断是否是示例数据。示例数据不能参与真实数据的处理。
    "allowElementAuthCheck": true, // [V8.1SP1]【可选】true：允许对栏目元素单个做权限校验,元素如果无权限会在允许时自动移除。
    "options": [               // 【可选】用户自定义高级参数，用于接收设计者的选择值。
        {
            "type": "text",       // 类型:[text：文本]、[number：数字型]、[color：颜色]、[icon：图标选择]
            "name": "高级筛选1",  // 高级配置的
            "rules": [{  // 正则适配，用于过滤异常输入
                        "pattern": "^(0|[1-9][0-9]?|100)$",
                        "attributes": "g", //标识全局适配
                        "message": "*注: 圆角设置范围为：0 - 100"
                    }],
            "value": ""          // 用户录入的值会回填在value中
        }
    ],
    "elements": [             // 【可选】栏目元素，一般要有一个。但是可以没有，这样可开发纯样式栏目
        {
            "name": "栏目元素",  // 【必须】栏目名称
            "dataFormat": "1",  // 【必须】数据格式
            "dataVersion": "v1" // 【必须】数据格式版本
        },
        {
            "name": "统计",
            "description": {// 【可选（只有统计才支持条件按条件过滤）】数据源描述信息（此属性可过滤统计的统计列）
                "includeCalcType":"[sum][count][avg][max][min]",// 【可选】支持哪些数据类型
                "excludeCalcType":""// 【可选】不支持哪些数据类型
            },
            "dataFormat": "5",
            "dataVersion": "V1",
            "extensible":true, //[V8.1]【可选】元素可扩展，可以通过编辑态，动态增加元素
            "extensibleGroup": "1", //[V8.1SP1]【可选】组编号，相同的组元素，动态添加的时候一起添加，一起删除。
            "groupDelete":true, //[V8.1SP1]【可选】栏目权限校验的时候，如果没有权限，并且groupDelete==true,那么整个组的栏目都将被删除。
            "options":[],//[V8.1SP1]【可选】跟栏目的options一样，栏目能配置的元素都能配置
            "important": true, //  [V8.1SP1]【可选】true：重要的元素，如果此元素无权限，则整个栏目无权限。
            "doNotCheckAuth":true, //  [V8.1SP1]【可选】true：元素权限校验的时候，就算是无权限也禁止移除此元素。
            "condition":{  // 【可选（只有统计和查询才支持条件）】条件
                "pagination" : {      // 分页
                    "page" : 1,
                    "pageSize" : 50
                },
                "rowTypes" : ["normal"] //【可选】数组可写多个 *[normal:普通行],[subtotal：小计行],[total：合计行]，此属性可以过滤统计的部分行。
            }
        },
        {
            "name": "更多",
            "description": "",
            "linkToColumnGroupRight": "1" , // 是否连接到栏目组右上角,指定为1后，次栏目元素会被栏目组的右上角区域捕获，一般用于跳转
            "columnGroupRightIcon":'', // 可配置右上角图标
            "dataFormat": "1",
            "dataVersion": "v1"
        }
    ]
}


编撰人：yinyanting


快速跳转



 * 栏目配置文件
   * 1.栏目基本信息
   * 2.栏目配置文件



分享链接分享链接

## 91. PortalAPI

> 原始路径：`/94/355/359/479/481/485.html`  
> 相对路径：`94/355/359/479/481/485.md`  
> JS Chunk：`app.371b709c.js`

## PortalAPI

----------------------------------------


## 1.简介

门户中主要api

## window.PortalAPI.env

环境变量，能获取到url上的参数、移动端能获取到getParam中的参数。

ENV中的包含的主要参数   参数            说明       类型     示例   备注
configId       配置文件id        String   —      —    
bizId          业务包id         String   —      —    
platform       平台            String   —      —    
debug          debug模式是否打开   String   true   —    
spaceId        异常回调函数        String   —      —    

## window.PortalAPI.getElementData(bizId, configId, params, callback)

根据栏目元素获取单个元素的数据。

参数         说明       类型       示例                       备注
bizId      配置文件id   String   —                        —
configId   业务包id    String   —                        —
params     条件参数     Object   {id：栏目元素id,platform:1}   platform[1:pc][2:移动]
callback   回调       String   true                     —

## window.PortalAPI.getColumnData(bizId, configId, params, callback)

根据栏目元素获取单个元素的数据。

参数         说明       类型       示例                     备注
bizId      配置文件id   String   —                      —
configId   业务包id    String   —                      —
params     条件参数     Object   {id：栏目id,platform:1}   platform[1:pc][2:移动]
callback   回调       String   true                   —

## window.PortalAPI.getThemeAttribute(className, Attr, tag)

js获取皮肤中的

参数          说明            类型       示例   备注
className   皮肤中的class名称   String   —    —
Attr        业务包id         String   —    —
tag         业务包id         String   —    —

.cap-link {
  color: #BBBBBA;
}

.cap-link:hover {
  color: red;
}


var color1 = window.PortalAPI.getThemeAttribute('cap-link', 'color')
var color2 = window.PortalAPI.getThemeAttribute('cap-link', 'color', 'hover')

// color1:#BBBBBA
// color2:red


## window.PortalAPI.getColor20ByNum(num)

// 获取皮肤中20个颜色，num从1开始。

num如果超出20 则循环获取，比如num=21与num=1 是一样的值。

## window.PortalAPI.getSeeyonPath(platform)

pc 会获取到 '/seeyon'

移动返回的是：window.cmp.util.getSeeyonPath()

## window.PortalAPI.columnJumpContent(params)

// 查询列表跳转。

/** 获取内容url
 *   params: {
*       bizId,        // 业务包id
*       configId,     // 配置id
*       columnId,     // 栏目id
*       elementId,    // 元素id
*       platform,     // 类型，'1'为PC，'2'为移动
*       op,           // 操作
*       q,            // 描述
*   }
 **/


## window.PortalAPI.isPreview()

是否是预览态

## window.PortalAPI.isEdit()

是否是编辑态

## window.PortalAPI.menuJumpContent(params)

跳转穿透 params 为菜单或者快捷入口 后端返回的数据。

## window.PortalAPI.getUrlParams(name)

从url上获取参数。

## window.PortalAPI.getPlugin(name,callback)

现在只能获取echarts对象，使用这个方法可以无需在栏目中引入大型的插件对象，优化栏目的体积。

window.PortalAPI.getPlugin('echarts' ,function(echarts){
        // 返回echarts对象
});


编撰人：yinyanting


快速跳转



 * PortalAPI
   * 1.简介
     * window.PortalAPI.env
     * window.PortalAPI.getElementData(bizId, configId, params, callback)
     * window.PortalAPI.getColumnData(bizId, configId, params, callback)
     * window.PortalAPI.getThemeAttribute(className, Attr, tag)
     * window.PortalAPI.getColor20ByNum(num)
     * window.PortalAPI.getSeeyonPath(platform)
     * window.PortalAPI.columnJumpContent(params)
     * window.PortalAPI.isPreview()
     * window.PortalAPI.isEdit()
     * window.PortalAPI.menuJumpContent(params)
     * window.PortalAPI.getUrlParams(name)
     * window.PortalAPI.getPlugin(name,callback)



分享链接分享链接

## 92. PortalDataAPI

> 原始路径：`/94/355/359/479/481/486.html`  
> 相对路径：`94/355/359/479/481/486.md`  
> JS Chunk：`app.371b709c.js`

## PortalDataAPI

----------------------------------------


## 1.基础数据处理

基础数据处理已经集成到栏目的通用混入文件中，如果是用vue开发栏目，则可以直接只用this.访问。 比如

参数解释：

index:下标，key：object里的key

获取`栏目`config的各个属性
##### window.PortalDataAPI.cl(key)


获取`栏目`的options的配置属性
##### window.PortalDataAPI.cloptions(optionIndex, key)


获取`栏目元素`的config属性
##### window.PortalDataAPI.el(elIndex, key)


获取`栏目元素`option属性（8.1SP1废弃函数：不要再用）
##### window.PortalDataAPI.eloption(elIndex, key)


获取`栏目元素`options属性（8.1SP1新增：）

elIndex:【必须】元素下标

optionIndex：【必须】元素的option下标

optionKey：【可选】默认为 value

##### window.PortalDataAPI.eloptions(elIndex, optionIndex,optionKey)


获取`栏目元素`labels属性
##### window.PortalDataAPI.ellabel(labelIndex, key)


获取`栏目元素`扩展属性
##### window.PortalDataAPI.elextends(extIndex, key)


获取`栏目元素`的数据
##### window.PortalDataAPI.dk(index, key)



## 1.统计数据处理df

## window.PortalDataAPI.statistic.dataFactory(inputData,elementConfig)

接收到统计数据以后，把栏目元素与配置文件传入此方法中，会得到df对象，可以用此对象来简化统计数据的分割，获取，过滤等常用操作，减少统计的栏目开发难度。

## df.target

传入的统计接口返回的对象，实际就是inputData。

## df.hasParentField

是否是交叉统计

普通统计



交叉统计



## df.rowHeaders

统计的行表头

## df.colHeaders

统计的列表头

## df.getFields()

统计的所有表头

## df.getBaseData()

统计的数据，内部会由两层data嵌套，无特殊需求使用getSourceData来获取统计数据。

## df.getSourceData(params)

统计的源数据，可以过滤数据，过滤条件由params：{hiddenSubTotal:true,hiddenTotal:true}确认,可为空。

如果想获取统计正在的数据最好用getSourceData来

hiddenSubTotal = true; 过滤小计行

hiddenTotal = true; 过滤总计行

## df.getParentFieldByDeep(item,deep)

// 根据获取第几层表头

## df.getColTreeHeaders()

// 按照树形结构获取表头。

如果是交叉统计，返回的是两层树结构表头。

如果是普通统计，返回的是df.colHeaders

## df.getRowHerderList()

// 获取行表头列表



## df.getRowData(rowIndex)

// 获取第rowIndex行的数据。

## df.getCellData(rowIndex,col)

// 获取单元格的数据* 第rowIndex行，第col列。

## df.getColDataList(col)

// 第col列数据。

## df.getColDataListBySourceData(col)

// 第col列源数据。

## df.penetrate(currCol,rowData,colsItem)

// 统计穿透，可自动判断移动还是pc

## df.penetrateM(currCol,rowData,colsItem)

// 移动统计穿透

## df.penetratePc(currCol,rowData,colsItem)

// pc统计穿透


## df.utils

统计的一些辅助方法，现阶段只有以下两个，方便用于chart 数据转换。

## df.utils.dataToEchartDataByCol(inputData, df, choCol, tag, colorMode)

// 获取一列，转换为echarts数据格式。

## df.utils.echartDataSetPercent(list, total)

// 为echarts数据添加百分比计算。

编撰人：yinyanting




快速跳转



 * PortalDataAPI
   * 1.基础数据处理
   * 1.统计数据处理df
     * window.PortalDataAPI.statistic.dataFactory(inputData,elementConfig)
     * df.target
     * df.hasParentField
     * df.rowHeaders
     * df.colHeaders
     * df.getFields()
     * df.getBaseData()
     * df.getSourceData(params)
     * df.getParentFieldByDeep(item,deep)
     * df.getColTreeHeaders()
     * df.getRowHerderList()
     * df.getRowData(rowIndex)
     * df.getCellData(rowIndex,col)
     * df.getColDataList(col)
     * df.getColDataListBySourceData(col)
     * df.penetrate(currCol,rowData,colsItem)
     * df.penetrateM(currCol,rowData,colsItem)
     * df.penetratePc(currCol,rowData,colsItem)
   * df.utils
     * df.utils.dataToEchartDataByCol(inputData, df, choCol, tag, colorMode)
     * df.utils.echartDataSetPercent(list, total)



分享链接分享链接

## 93. PortalAjax

> 原始路径：`/94/355/359/479/481/487.html`  
> 相对路径：`94/355/359/479/481/487.md`  
> JS Chunk：`app.371b709c.js`

## PortalAjax

----------------------------------------


## 1.简介

轻量级ajax请求api

## window.PortalAjax.get(url, fn)

GET 请求    参数       说明         类型   可选值   备注
url       url      String     —    —     
fn        回调函数     Function   —    —     
errorFn   异常回调函数   Function   —    —     

示例：

var url = '/seeyon/rest/cap4/bizportal/data';
window.PortalAjax.get(url, function(data){
      // data 返回值
});


## window.PortalAjax.post(url,data, callback)

POST 请求    参数       说明         类型   可选值   备注
url        url      String     —    —     
callback   回调函数     Function   —    —     
errorFn    异常回调函数   Function   —    —     

示例：

var url = '/seeyon/rest/cap4/bizportal/data';
var params = {id:1};
window.PortalAjax.post(url,params, function(data){
      // data 返回值
});


编撰人：yinyanting


快速跳转



 * PortalAjax
   * 1.简介
     * window.PortalAjax.get(url, fn)
     * window.PortalAjax.post(url,data, callback)



分享链接分享链接

## 94. PortalEventBus

> 原始路径：`/94/355/359/479/481/488.html`  
> 相对路径：`94/355/359/479/481/488.md`  
> JS Chunk：`app.371b709c.js`

## PortalEventBus

----------------------------------------


## 1.简介

门户空间的EventBus，主要用于以下功能开发。

1.栏目之间的数据通信。

2.监听空间的事件。

## 门户的平台事件

名称                         说明                    返回值
portal-onResizeReload      门户的layout区域size发生变化   id：可能会返回栏目id
portal-columnGroupResize   栏目组发生了变化              groutKey：栏目组的key
portal-optionReload        option变更              可能会返回栏目id
portal-forceReload         皮肤变化，菜单位置变化           无

示例：

var fun = function(params) {
     // TODO:如果门户内部空间发生了变化，则执行...
 }
 // 监听空间事件
 window.PortalEventBus.$on('portal-onResizeReload', fun);


## window.PortalAjax.$on(eventName, fn)

监听事件        参数     说明         类型   可选值   备注
eventName   url    String     —    —     
fn          回调函数   Function   —    —     

示例：

var scrollFun = function(params) {
     ....
 }
 window.PortalEventBus.$on('my-event', scrollFun);


## window.PortalAjax.$off(eventName, fn)

关闭事件        参数         说明         类型   可选值   备注
eventName   url        String     —    —     
fn          监听时的函数对象   Function   —    —     

示例：

window.PortalEventBus.$off('my-event', scrollFun);


## window.PortalAjax.$emit(eventName, params)

触发事件        参数      说明       类型   可选值   备注
eventName   url     String   —    —     
params      发送的数据   Object   —    —     

示例：

window.PortalEventBus.$emit('my-event', params);


如果两个栏目需要通信：

1、先约定一个广播名称：比如[my-event-1]

2、发送方 发送方：栏目A 把参数通过对象发送出去

window.PortalEventBus.$emit('my-event-1', {p1:1,p2:2});


接收方：栏目B

window.PortalEventBus.$on('my-event-1', (params)=>{
   // params:{p1:1,p2:2}
   // TODO: 获取到参数后，执行栏目B操作
}
);


发送方与接受方式一对多关系，一个发送何以多个栏目同时接收,只要是广播名称相同都能接收。

接收方：栏目C

window.PortalEventBus.$on('my-event-1', (params)=>{
   // params:{p1:1,p2:2}
   // TODO: 获取到参数后，执行栏目C操作
}
);


编撰人：yinyanting


快速跳转



 * PortalEventBus
   * 1.简介
     * 门户的平台事件
     * window.PortalAjax.$on(eventName, fn)
     * window.PortalAjax.$off(eventName, fn)
     * window.PortalAjax.$emit(eventName, params)



分享链接分享链接

## 95. PortalM3Utils

> 原始路径：`/94/355/359/479/481/489.html`  
> 相对路径：`94/355/359/479/481/489.md`  
> JS Chunk：`app.371b709c.js`

## PortalM3Utils

----------------------------------------


## 1.简介

移动端跳转辅助工具，已经集成到PortalAPI.menuJumpContent，如果移动端m3不是对跳转有特殊要求，可不必查看此api

## window.PortalM3Utils.idLink

m3 id key对应表

ID   APINAME         名称
1    collaboration   协同应用
66   cap4            cap4表单
82   cap4report      cap4统计
83   cap4business    cap4业务包门户
84   cap4query       cap4查询
85   cap4unflow      cap4无流程列表
91   cap4todolist    cap4待办
8    news            新闻
7    bulletin        公告
9    bbs             讨论
10   inquiry         调查
40   show            大秀
3    doc             文档
70   vreport         报表中心

## window.PortalM3Utils.NativeURLS

m3 原生跳转路径

APINAME         BASEURL
collaboration   http://collaboration.v5.cmp/v1.0.0
cap4            http://cap4.v5.cmp/v1.0.0
cap4report      http://cap4report.v5.cmp/v1.0.0
cap4business    http://cap4business.v5.cmp/v1.0.0
cap4query       http://cap4query.v5.cmp/v1.0.0
cap4unflow      http://cap4unflow.v5.cmp/v1.0.0
cap4todolist    http://cap4todolist.v5.cmp/v1.0.0
news            http://news.v5.cmp/v1.0.0
bulletin        http://bulletin.v5.cmp/v1.0.0
bbs             http://bbs.v5.cmp/v1.0.0
inquiry         http://inquiry.v5.cmp/v1.0.0
show            http://show.v5.cmp/v1.0.0
doc             http://doc.v5.cmp/v1.0.0
vreport         http://vreport.v5.cmp/v1.0.0

## window.PortalM3Utils.WapURLS

m3 wap跳转路径

APINAME         BASEURL
collaboration   /seeyon/m3/apps/v5/collaboration
cap4            /seeyon/m3/apps/v5/cap4
cap4report      /seeyon/m3/apps/v5/cap4report
cap4business    /seeyon/m3/apps/v5/cap4business
cap4query       /seeyon/m3/apps/v5/cap4query
cap4unflow      /seeyon/m3/apps/v5/cap4unflow
cap4todolist    /seeyon/m3/apps/v5/cap4todolist
news            /seeyon/m3/apps/v5
bulletin        /seeyon/m3/apps/v5
bbs             /seeyon/m3/apps/v5
inquiry         /seeyon/m3/apps/v5
show            /seeyon/m3/apps/v5
doc             /seeyon/m3/apps/v5
vreport         /seeyon/m3/apps/v5/vreport

## window.PortalM3Utils.s3js

m3 s3js的名称

APINAME         NAME
collaboration   collaboration_m_api.s3js
cap4            cap4_m_api.s3js
cap4report      cap4report_m_api.s3js
cap4business    cap4business_m_api.s3js
cap4query       cap4query_m_api.s3js
cap4unflow      cap4unflow_m_api.s3js
cap4todolist    cap4todolist_m_api.s3js
news            news_m_api.s3js
bulletin        bulletin_m_api.s3js
bbs             bbs_m_api.s3js
inquiry         inquiry_m_api.s3js
show            show_m_api.s3js
doc             doc_m_api.s3js
vreport         vreport_m_api.s3js

## window.PortalM3Utils.getHost(apiName)

根据apiName 返回baseUrl，内部自动适配了原生m3 与微协同。

## window.PortalM3Utils.getApi(inputParams,fn)

根据穿透参数，返回api对象，对象从fn中传入

编撰人：yinyanting




快速跳转



 * PortalM3Utils
   * 1.简介
     * window.PortalM3Utils.idLink
     * window.PortalM3Utils.NativeURLS
     * window.PortalM3Utils.WapURLS
     * window.PortalM3Utils.s3js
     * window.PortalM3Utils.getHost(apiName)
     * window.PortalM3Utils.getApi(inputParams,fn)



分享链接分享链接

## 96. ## 1、什么是指标？

> 原始路径：`/94/355/359/479/481/490/492.html`  
> 相对路径：`94/355/359/479/481/490/492.md`  
> JS Chunk：`app.371b709c.js`

## ## 1、什么是指标？

指标就是报表指标，来自统计中的部分数据。


## 2、如何制作一个指标




## 3、开发一个指标栏目

我们可以把一个指标或多个指标开发为一个栏目，【column_factory】中有很多指标栏目可以参考，比较典型的是column-quota-card,下面我们就深度解析此栏目来方便我们开发一个新的栏目

栏目样式：



文件夹结构：



3-1、入口文件

webpack 打包用的入口文件，一般只是单纯的应用vue对象，不做其他处理。

如果需要再vue安装此组件的时候先处理逻辑，可以写入install中。

import ColumnQuotaCard from './src/column-quota-card.vue';

ColumnQuotaCard.install = function (Vue) {
  Vue.component(ColumnQuotaCard.name, ColumnQuotaCard);
};

export default ColumnQuotaCard;


3-2、示例数据

用于栏目在开发过程中或者未绑定数据源的时候做的临时数据，注意eg数据是个数组，数组的个数要跟config.elements的个数对应。

因为此指标点击要跳转穿透，所以我们定义了两个数据源

1、指标：dataFormat:1获取数据，

2、穿透：dataFormat:2获取跳转信息。

当然eg.json里面，数组第一个就是模拟获取指标数据。因为跳转信息无法模拟，所以写个{}空对象。这里必须一一对应。



3-3、配置文件

{
  "name": "卡片式指标",   // 栏目名称
  "platform": "0",       // 平台属性 0:全部 1：pc 2：移动
  "bgColor": "#57CAC7",  // 默认背景色
  "skipOutStyle": true,  // 跳过外部样式，让外部不再自动处理配置样式，全部交由自身控制
  "height": "110",       // 默认高度110px
  "minHeight": "60",     // 最小高度60px
  "UUID": "4f0d2930-81bf-11e9-99d2-3520e7f11666", // 自动生成，全局唯一id
  "options": [ // 3-3-1:高级属性配置
    ....
  ],
  "labels": [ //  3-3-2:栏目上所显示描述的文字
    {
      "key": "1",
      "name": "员工人数"
    }
  ],
  "elements": [ // 3-3-3:栏目元素
    {
      "name": "指标",
      "description": "",
      "dataFormat": "1",
      "dataVersion": "V1"
    },
    {
      "name": "穿透",
      "description": "",
      "dataFormat": "2",
      "dataVersion": "V1"
    }
  ]
}


3-3-1:高级属性配置、config.options 跟配置看板的映射关系，允许栏目开发者将部分权限交给用户，让其自己定义部分功能细节。





3-3-2:栏目上所显示描述的文字



3-3-3:栏目元素点位映射

hotPoint的个数跟栏目元素个数相关，序号从0开始。如果多个数据源要绑定到同一个dom上，那么用  /  线隔开



3-3-3:栏目元素的映射关系



3-3-4:穿透的映射关系



divClickJump 其实也是获取指标元素的数据，通过基础api:window.PortalAPI.menuJumpContent直接跳转。 一定要使用基础api跳转，否则容易造成升级后错误。

divClickJump(index) {
            const jump = this.columnData[this.el(index,'id')];
            jump.data = jump.data || {};
            jump.data.id = jump.data.id || this.el(index,'id');
            jump && window.PortalAPI.menuJumpContent(jump);
        }


编撰人：yinyanting


快速跳转



 * 
 * 1、什么是指标？
 * 2、如何制作一个指标
 * 3、开发一个指标栏目



分享链接分享链接

## 97. 0、菜单栏目

> 原始路径：`/94/355/359/479/481/490/494.html`  
> 相对路径：`94/355/359/479/481/490/494.md`  
> JS Chunk：`app.371b709c.js`

## 0、菜单栏目

菜单栏目需要支持应用菜单和综合业务菜单。pc端基本都支持，移动端会自动过滤不支持的类型。


## 1、什么是应用菜单，如何配置菜单？




## 2、什么是综合业务菜单？如何配置综合菜单？




## 3、菜单栏目解析

栏目【column-menu-vertical】提供了一个菜单栏目的范本，后续栏目开发可以此为基础做扩展，或者重新开发。



编撰人：yinyanting




快速跳转



 * 0、菜单栏目
 * 1、什么是应用菜单，如何配置菜单？
 * 2、什么是综合业务菜单？如何配置综合菜单？
 * 3、菜单栏目解析



分享链接分享链接

## 98. 1、什么是列表栏目？

> 原始路径：`/94/355/359/479/481/490/495.html`  
> 相对路径：`94/355/359/479/481/490/495.md`  
> JS Chunk：`app.371b709c.js`

## 1、什么是列表栏目？

现阶段，查询列表，无流程列表统称为列表栏目，他们的区别是无流程列表支持数据操作，查询列表支持关联查询。

列表栏目的难点，主要是针对特殊表单字段的特殊处理，比如图片枚举与自动以控件等处理。

代表栏目：【column-query-list】见附件[column-query-list.zip]


## 2、配置解析




## 3、最终样式



编撰人：yinyanting




快速跳转



 * 1、什么是列表栏目？
 * 2、配置解析
 * 3、最终样式



分享链接分享链接

## 99. 1、统计

> 原始路径：`/94/355/359/479/481/490/496.html`  
> 相对路径：`94/355/359/479/481/490/496.md`  
> JS Chunk：`app.371b709c.js`

## 1、统计

是比较复杂的栏目类型


## 具体参考栏目：【column-statistics-line】，已经在工程里面提供，可自行debug学习。

需要深入理解05 PortalDataAPI 的 df 使用规则

后续再补充此文档...

编撰人：yinyanting




快速跳转



 * 1、统计
 * 具体参考栏目：【column-statistics-line】，已经在工程里面提供，可自行debug学习。



分享链接分享链接

## 100. 有很多场景无需数据源，只需要内置对象即可开发出对应功能模块。

> 原始路径：`/94/355/359/479/481/491/`  
> 相对路径：`94/355/359/479/481/491/README.md`  
> JS Chunk：`app.371b709c.js`

## 有很多场景无需数据源，只需要内置对象即可开发出对应功能模块。

比如当前以下场景需要次功能

1、门户切换，当前所有授权门户直接跳转切换

2、[v8.1]空间视图的切换

3、[v8.1]自行管理菜单跳转的堆栈

4、图片栏目开发，横幅栏目开发

5、开发动态栏目，允许栏目被其它栏目注入栏目配置，达到变成其它栏目的目的

6、其它客开模块，如果跟标准数据源无关，可参考1，定义一个栏目，在vue中自行访问客开接口渲染，之后直接打包栏目上传即可。

具体查看栏目示例

编撰人：yinyanting




快速跳转



 * 有很多场景无需数据源，只需要内置对象即可开发出对应功能模块。



分享链接分享链接

## 101. 1、功能说明

> 原始路径：`/94/355/359/479/481/491/498.html`  
> 相对路径：`94/355/359/479/481/491/498.md`  
> JS Chunk：`app.371b709c.js`

## 1、功能说明




## 2、主要参考栏目

column-top-info，

实现方式：

通过【${this.columnApi.seeyonPath}/rest/cap4/bizportal/${bizId}/listAll/1】获取所有有权限的门户列表。再自行渲染到vue里面，不必绑定数据源。

编撰人：yinyanting




快速跳转



 * 1、功能说明
 * 2、主要参考栏目



分享链接分享链接

## 102. 功能说明

> 原始路径：`/94/355/359/479/481/491/499.html`  
> 相对路径：`94/355/359/479/481/491/499.md`  
> JS Chunk：`app.371b709c.js`

## 功能说明

8.1之后，空间支持多视图配置，并且允许空间在多个视图之间来回切换。



图中参考栏目：【column-base-views】

可以通过直接修改此栏目样式制作新的视图切换栏目。

视图的核心数据存储在全局vuex对象中，可自行获取渲染。

this.$store.state.spacesIndex:当前选中的是第几个视图

this.$store.getters.configSpaces:当前的视图列表

编撰人：yinyanting




快速跳转



 * 功能说明



分享链接分享链接

## 103. 功能说明

> 原始路径：`/94/355/359/479/481/491/500.html`  
> 相对路径：`94/355/359/479/481/491/500.md`  
> JS Chunk：`app.371b709c.js`

## 功能说明

8.1之后，空间会自动记录嵌入式菜单跳转的堆栈，方便栏目开发者做空间tags切换。

现阶段不支持tag页面缓存，也不会把弹出的菜单页面压入堆栈。



参考栏目【column-menu-tabs】【column-menu-tabs-style2】

核心数据存贮在全局$store对象中

this.$store.state.linkTabs：用户的菜单点击顺序队列

this.$store.state.linklinkHref:当前生效的链接地址，可用于判断当前点击的是哪个tag，方便选中着色。

this.$store.state.linkCount:当前点击的是队列中第几个tag。一般不用，最好使用linklinkHref判断当前点击。如果是相同的链接，可以同时生效。

编撰人：yinyanting




快速跳转



 * 功能说明



分享链接分享链接

## 104. 应用场景

> 原始路径：`/94/355/359/479/481/503/504.html`  
> 相对路径：`94/355/359/479/481/503/504.md`  
> JS Chunk：`app.371b709c.js`

## 应用场景

允许栏目开发者，定义某个元素是可扩展的。栏目开发者只需要开发一个样板栏目元素，后续具体要多少个，让使用者自行定义。



参考栏目：【column-quota-ring】

通过【extensible】属性，允许用户不断扩展栏目元素，达到动态增加元素的目的。

常见场景：栏目开发者定义一个指标，允许这个指标可扩展。那么用户就可以设置一排指标。达到了类似磁贴的效果。

同理，栏目开发者可以定义一个列表，用户可以扩展多个列表。等需求场景。

此栏目的功能是用户定义两个以上的指标，让指标自己成环状显示。



编撰人：yinyanting




快速跳转



 * 应用场景



分享链接分享链接

## 105. 0、前言

> 原始路径：`/94/355/359/479/481/505.html`  
> 相对路径：`94/355/359/479/481/505.md`  
> JS Chunk：`app.371b709c.js`

## 0、前言

主题的css是最后挂载，同样的css name 主题的优先级最大。


## 1、主题存放目录

除了标准的css修改外，还可以在theme.css 自己写其它css属性，强制覆盖当前属性。




## 2、修改完成后，可执行编译主题



构建完成后，可到工程目录【shop】下寻找【theme-def.zip】文件，此文件可以导入到空间中，覆盖现有主题文件。

03 如何导入本地主题

注意：特殊情况下，导入主题无法实时覆盖，可以右上角保存后，关闭编辑态再重新打开。

编撰人：yinyanting




快速跳转



 * 0、前言
 * 1、主题存放目录
 * 2、修改完成后，可执行编译主题



分享链接分享链接

## 106. 数据源开发

> 原始路径：`/94/355/359/479/506/508.html`  
> 相对路径：`94/355/359/479/506/508.md`  
> JS Chunk：`app.371b709c.js`

## 数据源开发


## 一、数据格式

暂时支持7种数据格式，其中“个人信息”可以不用配置数据源自动获取当前登陆人的信息，如下表：

数据格式   数据编码   数据版本   说明
指标     1      V1     统计值（max, min, sum, count）
快捷入口   2      V1     
菜单     3      V1     
列表     4      V1     
统计列表   5      V1     
个人信息   6      V1     暂时不支持数据源配置，自动获取当前登陆人信息
业务导图   7      V1     暂时不支持移动端


## 二、数据源类图




## 三、数据源主要API介绍

3.1 名词说明

名称     说明
数据源    可等同理解为java.sql.DataSource
数据集    可等同数据库表
数据结果   可等同理解为“select * from T where a=1”的查询结果

3.2 AbstractDataSourceProvider：数据源连接基础封装

方法                                                             说明
DataFormat dataFormat()                                        指定数据格式，具体参考DataFormat
String uuid()                                                  数据连接唯一码, 可以使用Online UUID Generator在线生成
DataSetList getDataSetList(ContextParam contextParam,          返回数据集的列表，用户可以以此进行数据源绑定
String[] versions)
isAllow(ContextParam contextParam, DataSetMetadata metadata,   判断用户是否有权限访问
Command command)
DataSetResult executeQuery(ContextParam contextParam,          获取查询结果
DataSetMetadata metadata, String[] versions, Command
command)

::: demo

/**
 * @Title: 数据源连接基础封装
 * @Description:
 * @Company: seeyon.com
 * @Team: Seeyon CAP4
 * @Date: 2019-06-03 13:36
 */
public abstract class AbstractDataSourceProvider implements InvokeHandler, SortOrderable {
    /**
     * 数据格式
     *
     * @return
     */
    public abstract DataFormat dataFormat();

    /**
     * 数据版本
     *
     * @return
     */
    public String[] versions() {
        return new String[]{BizPortalConstants.Version.V1.name()};
    }

    /**
     * 数据连接唯一码, 可以使用https://www.uuidgenerator.net/version1在线生成
     *
     * @return
     */
    public abstract String uuid();

    /**
     * 数据连接名称
     *
     * @return
     */
    public abstract String name();

    /**
     * 获取数据集列表
     *
     * @param contextParam
     * @param versions
     * @return
     * @throws BusinessException
     */
    public abstract DataSetList getDataSetList(ContextParam contextParam, String[] versions) throws BusinessException;

    /**
     * 判断是否有权限
     *
     * @param contextParam
     * @param metadata
     * @param command
     * @return
     * @throws BusinessException
     */
    public abstract boolean isAllow(ContextParam contextParam, DataSetMetadata metadata, Command command) throws BusinessException;

    /**
     * 获取数据实际id
     *
     * @param metadata
     * @param k
     * @return
     * @throws BusinessException
     */
    protected Long attrRealLong(Command command, DataSetMetadata metadata, String k) throws BusinessException {
        return metadata.attrLong(k);
    }
}


:::

3.3 DataSetList：数据集列表

暂时只支持树形结构返回，对应实现类DefaultDataSetList，在使用DefaultDataSetList的时候请确保叶子节点是可绑定的数据集，并设置上metadata属性.

::: demo

/**
 * @Title:默认数据集结果
 * @Description:
 * @Company: seeyon.com
 * @Team: Seeyon CAP4
 * @Date: 2019-06-03 14:26
 */
public class DefaultDataSetList implements DataSetList {
    /**
     * 节点列表
     */
    private List<Node> list = new ArrayList<Node>();

    public List<Node> getList() {
        return list;
    }

    /**
     * 添加节点
     *
     * @param node
     */
    public void addNode(Node node) {
        list.add(node);
    }

    /**
     * 创建根节点
     *
     * @param id
     * @param name
     * @return
     */
    public Node createBranchNode(String id, String name) {
        Node node = new Node();
        node.id = id;
        node.name = name;
        node.branch = true;
        node.parentId = "0";
        return node;
    }

    /**
     * 创建枝干节点
     *
     * @param id
     * @param name
     * @param parentId
     * @return
     */
    public Node createBranchNode(String id, String name, String parentId) {
        Node node = new Node();
        node.id = id;
        node.name = name;
        node.branch = true;
        node.parentId = parentId;
        return node;
    }

    /**
     * 创建叶子节点
     *
     * @param id
     * @param name
     * @param parentId
     * @return
     */
    public Node createLeafNode(String id, String name, String parentId) {
        Node node = new Node();
        node.id = id;
        node.name = name;
        node.fillName = name;
        node.fullName = name;
        node.branch = false;
        node.parentId = parentId;
        return node;
    }

    /**
     * 创建叶子节点
     *
     * @param id
     * @param name
     * @param parentId
     * @param dataSetMetadata
     * @return
     */
    public Node createLeafNode(String id, String name, String parentId, DataSetMetadata dataSetMetadata) {
        Node node = new Node();
        node.id = id;
        node.name = name;
        node.fillName = name;
        node.fullName = name;
        node.branch = false;
        node.parentId = parentId;
        node.metadata = dataSetMetadata;
        return node;
    }

    /**
     * 创建叶子节点
     *
     * @param id
     * @param name
     * @param parentId
     * @param dataSetMetadata
     * @return
     */
    public Node createLeafNode(String id, String name, String fullName, String parentId, DataSetMetadata dataSetMetadata) {
        Node node = new Node();
        node.id = id;
        node.name = name;
        node.fillName = name;
        node.fullName = fullName;
        node.branch = false;
        node.parentId = parentId;
        node.metadata = dataSetMetadata;
        return node;
    }

    /**
     * 创建叶子节点
     *
     * @param id
     * @param name
     * @param parentId
     * @param dataSetMetadata
     * @return
     */
    public Node createLeafNode(String id, String name, String fullName, String fillName, String parentId, DataSetMetadata dataSetMetadata) {
        Node node = new Node();
        node.id = id;
        node.name = name;
        node.fillName = fillName;
        node.fullName = fullName;
        node.branch = false;
        node.parentId = parentId;
        node.metadata = dataSetMetadata;
        return node;
    }

    /**
     * 判断是否有子节点
     *
     * @param id
     * @return
     */
    public boolean existChildren(String id) {
        for (Node node : list) {
            if (StringUtils.equals(id, node.parentId)) {
                return true;
            }
        }
        return false;
    }

    /**
     * 数据节点
     */
    public static class Node implements Serializable {
        /**
         * 节点Id
         */
        private String id;
        /**
         * 名称
         */
        private String name;
        /**
         * 回填名称
         */
        private String fillName;
        /**
         * 完整名称
         */
        private String fullName;
        /**
         * 上级节点
         */
        private String parentId;
        /**
         * 是否枝干节点
         */
        private boolean branch;
        /**
         * 元信息
         */
        private DataSetMetadata metadata;

        public String getId() {
            return id;
        }

        public void setId(String id) {
            this.id = id;
        }

        public String getName() {
            return name;
        }

        public void setName(String name) {
            this.name = name;
        }

        public String getFillName() {
            return fillName;
        }

        public void setFillName(String fillName) {
            this.fillName = fillName;
        }

        public String getFullName() {
            return fullName;
        }

        public void setFullName(String fullName) {
            this.fullName = fullName;
        }

        public String getParentId() {
            return parentId;
        }

        public void setParentId(String parentId) {
            this.parentId = parentId;
        }

        public boolean isBranch() {
            return branch;
        }

        public void setBranch(boolean branch) {
            this.branch = branch;
        }

        public DataSetMetadata getMetadata() {
            return metadata;
        }

        public void setMetadata(DataSetMetadata metadata) {
            this.metadata = metadata;
        }
    }
}


:::

3.4 DataSetMetadata：数据集元信息

这里记录的数据集的标志信息，确保根据里面内容能反向查询到这个节点，并可以根据里面的内容做查询等操作。

::: demo

/**
 * @Title: 数据集元信息
 * @Description:
 * @Company: seeyon.com
 * @Team: Seeyon CAP4
 * @Date: 2019-06-03 14:28
 */
public class DataSetMetadata implements Serializable {
    /**
     * 标志符
     * 请与所对应的DataSourceProvider#uuid()保持一致
     */
    private String uuid;
    /**
     * 数据集标志: 用于区分一个数据源中可以获得种数据集的时候判断
     */
    private String sign;
    /**
     * 属性
     */
    private Map<String, Object> attributes = new HashMap<String, Object>();

    public DataSetMetadata() {
    }

    public DataSetMetadata(String uuid) {
        this.uuid = uuid;
    }

    public DataSetMetadata(String uuid, String sign) {
        this.uuid = uuid;
        this.sign = sign;
    }

    /**
     * 设置属性
     *
     * @param att
     * @param val
     * @return
     */
    public DataSetMetadata attr(String att, Object val) {
        attributes.put(att, val);
        return this;
    }

    /**
     * 获取属性
     *
     * @param att
     * @return
     */
    public Object attr(String att) {
        return attributes.get(att);
    }

    /**
     * 获取属性
     *
     * @param att
     * @return
     */
    public Long attrLong(String att) {
        return MapUtils.getLong(attributes, att);
    }

    public Integer attrInt(String att) {
        return MapUtils.getInteger(attributes, att);
    }


    public String getUuid() {
        return uuid;
    }

    public void setUuid(String uuid) {
        this.uuid = uuid;
    }

    public String getSign() {
        return sign;
    }

    public void setSign(String sign) {
        this.sign = sign;
    }

    public Map<String, Object> getAttributes() {
        return attributes;
    }

    public void setAttributes(Map<String, Object> attributes) {
        this.attributes = attributes;
    }
}


:::

3.5 ContextParam：上下文参数封装

记录了当前用户，当前业务包Id，终端类型（PC还是移动端）信息。

3.6 Command：数据集操作命令

默认op=default，使用场景如下：a) 列表中查看详情；b) 列表中翻页；c) 数据返回和操作不满足客开场景，可以与栏目开发者“协商”好op值和参数格式，并在后端实现一个InvokeHander并注入到对应的数据源接口中即可。

invokeHandlerMap.put("default", new DefaultInvokeHandler());
invokeHandlerMap.put("viewDetail", new DefaultViewDetailInvokeHandler());


----------------------------------------


## 四、指标数据源开发

4.1 指标数据返回结果

::: demo

public class IndicatorDataSetResult implements DataSetResult {
    @Override
    public Integer getDataFormat() {
        return DataFormat.INDICATOR.getCode();
    }

    @Override
    public String getVersion() {
        return Version.V1.name();
    }

    /**
     * 原始值
     */
    private Object source;
    /**
     * 显示值
     */
    private Object value;
    /**
     * 字段类型
     * @see FieldType#getKey()
     */
    private String fieldType;

    public Object getSource() {
        return source;
    }

    public void setSource(Object realValue) {
        this.source = realValue;
    }

    public Object getValue() {
        return value;
    }

    public void setValue(Object value) {
        this.value = value;
    }

    public String getFieldType() {
        return fieldType;
    }

    public void setFieldType(String fieldType) {
        this.fieldType = fieldType;
    }
}


:::

4.2 指标数据源开发参考示例

::: demo

public class DefaultReportIndicatorDataSourceProvider extends DefaultDataSourceProvider {
    @Override
    public int getSortOrder() {
        return 0;
    }

    @Override
    public BizPortalConstants.DataFormat dataFormat() {
        return BizPortalConstants.DataFormat.INDICATOR;
    }

    @Override
    public String uuid() {
        return "ec18b5ba-2125-410c-89be-5429c53c5810";
    }

    @Override
    public String name() {
        return "应用报表指标";
    }
    
    
    @Override
    public DefaultDataSetList getDataSetList(ContextParam contextParam, DataSetMetadata dataSetMetadata, String[] versions) throws BusinessException {
        DefaultDataSetList dataSetList = new DefaultDataSetList();
        BizConfigBean configBean = bizPortalExternAdapterManager.getBizConfigBean(getMultiStepId(dataSetMetadata));
        Long bizId = configBean.getId();

        // 根节点
        DefaultDataSetList.Node rootNode = dataSetList.createBranchNode(bizId.toString(), name());
        dataSetList.addNode(rootNode);

        // 报表指标
        List<ReportIndex> list = bizPortalReportAdapterManager.findReportIndex(ApplicationCategoryEnum.cap4biz.name(), bizId.toString());
        if (CollectionUtils.isNotEmpty(list)) {
            Multimap<Long, ReportIndex> multimap = Multimaps.index(list, new Function<ReportIndex, Long>() {
                @Override
                public Long apply(ReportIndex input) {
                    return input.getReportDesignId();
                }
            });
            List<ReportDesignDefinition> reportConfigs = bizPortalReportAdapterManager.findReportDesignDefinition(Lists.newArrayList(multimap.keySet()));
            for (ReportDesignDefinition definition : reportConfigs) {
                DefaultDataSetList.Node configNode = dataSetList.createBranchNode(definition.getDesignId().toString(), definition.getTitle(), rootNode.getId());
                dataSetList.addNode(configNode);
                Function<String, String> fullNameFunction = getFullNameFunction(configBean, definition);
                for (ReportIndex ri : multimap.get(definition.getDesignId())) {
                    // 这个地方非常关键，请务必将下次查询所需要的参数都放进去
                    DataSetMetadata metadata = new DataSetMetadata(uuid())
                            .attr(BIZ_ID, bizId)
                            .attr("designId", definition.getDesignId())
                            .attr("indexId", ri.getId());
                    dataSetList.addNode(dataSetList.createLeafNode(getNodeId(ri.getId()), ri.getTitle(), fullNameFunction.apply(ri.getTitle()), configNode.getId(), metadata));
                }
            }
        }
        return dataSetList;
    }

    /**
     * 获取统计指标完整名
     *
     * @param bizConfigBean
     * @param designDefinition
     * @return
     */
    private Function<String, String> getFullNameFunction(final BizConfigBean bizConfigBean, final ReportDesignDefinition designDefinition) {
        return new Function<String, String>() {
            @Override
            public String apply(String input) {
                return bizConfigBean.getName() + "-" + designDefinition.getTitle() + "-" + input;
            }
        };
    }

    @Override
    public boolean isAllow(ContextParam contextParam, DataSetMetadata metadata, Command command) throws BusinessException {
        return bizPortalReportAdapterManager.checkAuth(attrRealLong(command, metadata,"designId"), contextParam.getUserId());
    }

    @Override
    public DataSetResult executeQuery(ContextParam contextParam, DataSetMetadata metadata, String[] versions, Command command) throws BusinessException {
        // 查询指标结果，这个地方请注意设置fieldType和source和value，有的时候指标的显示需要用原始值
        ReportIndexResult indexResult = bizPortalReportAdapterManager.getReportIndexResult(attrRealLong(command, metadata, "indexId"));
        if (indexResult != null) {
            IndicatorDataSetResult dataSetResult = new IndicatorDataSetResult();
            dataSetResult.setFieldType(indexResult.getOriginalField().getDbType());
            dataSetResult.setSource(indexResult.getRealValue());
            dataSetResult.setValue(indexResult.getDisplay());
            return dataSetResult;
        }
        return null;
    }

    // 如果要随业务包导出的化，请将所有会变的值全部以下面代码示例转换下
    @Override
    public DataSetMetadata beforeDataSetMetaBind(String dataId, DataSetMetadata metadata) throws BusinessException {
        Long bizId = getBizId(metadata);
        metadata.attr("designId", createBizPortalDataRelation(bizId, dataId, metadata.attrLong("designId")));
        metadata.attr("indexId", createBizPortalDataRelation(bizId, dataId, metadata.attrLong("indexId")));
        return metadata;
    }

    @Override
    protected String getId(Command command, DataSetMetadata metadata) throws BusinessException {
        return attrRealLong(command, metadata, "indexId").toString();
    }

    // fields
    private BizPortalReportAdapterManager bizPortalReportAdapterManager;

    // setters
    public void setBizPortalReportAdapterManager(BizPortalReportAdapterManager bizPortalReportAdapterManager) {
        this.bizPortalReportAdapterManager = bizPortalReportAdapterManager;
    }
}


:::


## 五、快捷入口数据源开发

5.1 快捷入口数据返回结果

快捷入口返回的数据结果在PC端和移动端是有区别的：1. PC端根据返回URL的直接跳转；2.移动端是优先基于CMP的openAppByApi进行跳转，参数格式为{appId: 应用包Id， openApi : 跳转方法, params: 跳转参数}， 如果不能使用openAppByApi跳转时，则采用URL直接跳转.

5.1.1 PC端返回格式

::: demo

public class LinkDataSetResult implements DataSetResult {
    @Override
    public Integer getDataFormat() {
        return DataFormat.LINK.getCode();
    }

    @Override
    public String getVersion() {
        return Version.V1.name();
    }

    public static LinkDataSetResult of(String href) {
        LinkDataSetResult that = new LinkDataSetResult();
        that.href = href;
        return that;
    }

    /**
     * 连接地址
     */
    private String href;

    public String getHref() {
        return href;
    }

    public void setHref(String href) {
        this.href = href;
    }
}


:::

5.1.2 移动端返回格式

:::demo

public class MobileLinkDataSetResult extends LinkDataSetResult {
 /**
  * 应用包Id
  */
 private String appId;
 /**
  * 跳转方法
  */
 private String openApi;
 /**
  * 跳转参数
  */
 private Map<String, ?> params;

 public static MobileLinkDataSetResult of(String appId, String openApi, Map<String, ?> params) {
  MobileLinkDataSetResult that = new MobileLinkDataSetResult();
  that.appId = appId;
  that.openApi = openApi;
  that.params = params;
  return that;
 }

 public String getAppId() {
  return appId;
 }

 public void setAppId(String appId) {
  this.appId = appId;
 }

 public String getOpenApi() {
  return openApi;
 }

 public void setOpenApi(String openApi) {
  this.openApi = openApi;
 }

 public Map<String, ?> getParams() {
  return params;
 }

 public void setParams(Map<String, ?> params) {
  this.params = params;
 }
}


:::

5.1.2 快捷入口数据源开发参考示例

其他部分与指标数据源开发基本一致，以下代码是查看业务空间的快捷入口示例。

:::demo

@Override
 public LinkDataSetResult viewBizPortalSpace(ContextParam contextParam, Long spaceId) throws BusinessException {
  LinkDataSetResult dataSetResult;
  if (isMobile(contextParam)) {
   CAPPortalSpace portalSpace = bizPortalSpaceManager.getCAPPortalSpace(spaceId);
   CAPPortalSpaceConfig spaceConfig = bizPortalSpaceManager.getBizPortalSpaceConfig(spaceId, BizPortalConstants.ConfigStatus.RUNNING);
   Map<String, Long> map = ImmutableMap.of("bizId", portalSpace.getBizId(), "spaceId", spaceId, "configId", spaceConfig.getId());
            // 注意点1：构建移动端openAppByApi的参数格式
   dataSetResult = MobileLinkDataSetResult.of(getAppId(ApplicationCategoryEnum.cap4Form), "openBizInfoBySpaceId", map);
  } else {
            // 注意点2：构建出URL格式
   dataSetResult = LinkDataSetResult.of(replaceURL(VIEW_BIZPORTAL_SPACE_PATTERN, ImmutableMap.of("spaceId", spaceId)));
  }
  return dataSetResult;
 }


:::


## 六、列表数据源开发

列表数据源开发与前面数据源格式相比要复杂些，他支持分页获取数据，支持查看详情（如果数据源支持的话）。故命令对象在就至少存在两个：1. default: 默认列表；2. viewDetail：查看单条记录详情。

6.1 op=default：默认列表数据返回格式

:::demo

public class ListDataSetResult implements DataSetResult {

    @Override
    public Integer getDataFormat() {
        return DataFormat.LIST.getCode();
    }

    @Override
    public String getVersion() {
        return Version.V1.name();
    }

    /**
     * 列表数据结果
     */
    private transient ListDataResult listDataResult;

    public static ListDataSetResult of(ListDataResult listDataResult) {
        ListDataSetResult that = new ListDataSetResult();
        that.listDataResult = listDataResult;
        return that;
    }

    public void setListDataResult(ListDataResult listDataResult) {
        this.listDataResult = listDataResult;
    }

    public List<ListField> getFields() {
        return listDataResult.getFields();
    }

    public List<ListRowData> getData() {
        return listDataResult.getData();
    }

    public int getPage() {
        return listDataResult.getPage();
    }

    public int getPages() {
        return listDataResult.getPages();
    }

    public int getSize() {
        return listDataResult.getSize();
    }

    public int getTotal() {
        return listDataResult.getTotal();
    }

    public Date getExecuteTime (){
        return listDataResult.getExecuteTime();
    }
}


:::

这里最主要的是初始化出listDataResult这个列表对象，列表对象包含了（字段列表，数据结果，页码，总页数，每页显示数量，总体数，执行时间）等信息。

:::demo

public class ListDataResult implements Serializable {
    /**
     * id
     */
    private String id;
    /**
     * 字段列表
     */
    private List<ListField> fields = new ArrayList<ListField>();
    /**
     * 数据结果
     */
    private List<ListRowData> data = new ArrayList<ListRowData>();
    /**
     * 页码
     */
    private int page;
    /**
     * 总页数
     */
    private int pages;
    /**
     * 每页数量
     */
    private int size;
    /**
     * 总数
     */
    private int total;
    /**
     * 执行时间
     */
    private Date executeTime;

    private volatile transient Map<String, String> indexCache;

    public void addListField(ListField listField) {
        fields.add(listField);
    }

    public ListRowData newListRowData() {
        ListRowData listRowData = new ListRowData();
        data.add(listRowData);
        return listRowData;
    }

    public void putListRowData(ListRowData listRowData) {
        data.add(listRowData);
    }

    /**
     * 放数据
     *
     * @param rowData
     * @param key
     * @param data
     */
    public void putListRowData(ListRowData rowData, String key, ListRowData.Data data) {
        initIndexCache();
        rowData.getData().put(indexCache.get(key), data);
    }

    /**
     * 获取数据行中字段数据
     *
     * @param rowData
     * @param listField
     * @return
     */
    public Data getData(ListRowData rowData, ListField listField) {
        initIndexCache();
        return rowData.getData().get(indexCache.get(listField.getKey()));
    }

    /**
     * 初始化key-index对象
     */
    private void initIndexCache() {
        if (indexCache != null) {
            return;
        }
        Map<String, String> map = Maps.newHashMapWithExpectedSize(fields.size());
        for (int i = 0; i < fields.size(); i ++) {
            map.put(fields.get(i).getKey(), String.valueOf(i));
        }
        indexCache = map;
    }

    public String getId() {
        return id;
    }

    public void setId(String id) {
        this.id = id;
    }

    public List<ListField> getFields() {
        return fields;
    }

    public void setFields(List<ListField> fields) {
        this.fields = fields;
    }

    public List<ListRowData> getData() {
        return data;
    }

    public void setData(List<ListRowData> data) {
        this.data = data;
    }

    public int getPage() {
        return page;
    }

    public void setPage(int page) {
        this.page = page;
    }

    public int getPages() {
        return pages;
    }

    public void setPages(int pages) {
        this.pages = pages;
    }

    public int getSize() {
        return size;
    }

    public void setSize(int size) {
        this.size = size;
    }

    public int getTotal() {
        return total;
    }

    public void setTotal(int total) {
        this.total = total;
    }

    public Date getExecuteTime() {
        return executeTime;
    }

    public void setExecuteTime(Date executeTime) {
        this.executeTime = executeTime;
    }
}
/**
 * @Title: 列表字段
 * @Description:
 * @Company: seeyon.com
 * @Team: Seeyon CAP4
 * @Date: 2019-06-11 14:31
 */

public class ListField implements Serializable {
    /**
     * 枚举ID
     */
    public static String ENUM_ID = "enumId";
    /**
     * 枚举层级
     */
    public static String ENUM_LEVEL = "enumLevel";
    /**
     * 是否末级枚举
     */
    public static String IS_FINAL_CHILD= "isFinalChild";

    /**
     * 字段键值
     */
    private String key;
    /**
     * 字段名称
     */
    private String name;
    /**
     * 控件类型
     * com.seeyon.ctp.form.bean.FormFieldComBean.FormFieldComEnum
     * com.seeyon.ctp.report.engine.api.ReportConstants.FieldComType
     */
    private String inputType;
    /**
     * 字段类型
     * com.seeyon.cap4.form.util.Enums.FieldType
     */
    private String fieldType;
    /**
     * 字段长度
     */
    private String length;
    /**
     * 小数位
     */
    private String digitNum = "0";
    /**
     * 其他属性
     */
    private Map<String, Object> attributes = new HashMap<String, Object>();
    /**
     * 支持操作类型
     * com.seeyon.ctp.report.bizportal.Action
     */
    private List<String> actions = new ArrayList<String>();
    /**
     * 报表字段
     */
    private transient DisplayField displayField;
    /**
     * 值对象
     */
    private ListRowData.Data data;

    public String getKey() {
        return key;
    }

    public void setKey(String key) {
        this.key = key;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getInputType() {
        return inputType;
    }

    public void setInputType(String inputType) {
        this.inputType = inputType;
    }

    public String getFieldType() {
        return fieldType;
    }

    public void setFieldType(String fieldType) {
        this.fieldType = fieldType;
    }

    public List<String> getActions() {
        return actions;
    }

    public void setActions(List<String> actions) {
        this.actions = actions;
    }

    public DisplayField getDisplayField() {
        return displayField;
    }

    public void setDisplayField(DisplayField displayField) {
        this.displayField = displayField;
    }

    public Data getData() {
        return data;
    }

    public void setData(Data data) {
        this.data = data;
    }
    public Long getEnumId() {
        return (Long) attributes.get(ENUM_ID);
    }

    public void setEnumId(Long enumId) {
        attr(ENUM_ID, enumId);
    }

    public Integer getEnumLevel() {
        return MapUtils.getInteger(attributes, ENUM_LEVEL);
    }

    public void setEnumLevel(Integer enumLevel) {
        attr(ENUM_LEVEL, enumLevel);
    }

    public Map<String, Object> getAttributes() {
        return attributes;
    }

    public void attr(String key, Object value) {
        this.attributes.put(key, value);
    }

    public void attr(Map<String, Object> map) {
        this.attributes.putAll(map);
    }

    public Boolean getFinalChild() {
        return (Boolean) attributes.get(IS_FINAL_CHILD);
    }

    public void setFinalChild(Boolean finalChild) {
        attr(IS_FINAL_CHILD, finalChild);
    }

    public String getLength() {
        return length;
    }

    public void setLength(String length) {
        this.length = length;
    }

    public String getDigitNum() {
        return digitNum;
    }

    public void setDigitNum(String digitNum) {
        this.digitNum = digitNum;
    }
}
/**
 * @Title: 列表行数据封装
 * @Description:
 * @Company: seeyon.com
 * @Team: Seeyon CAP4
 * @Date: 2019-06-11 14:38
 */
public class ListRowData implements Serializable {
    /**
     * 数据对象
     */
    private Map<String, Data> data = new HashMap<String, Data>();
    /**
     * 行标志符
     */
    private String identifier;
    /**
     * 行号
     */
    private int lineNo;
    /**
     * 支持操作类型
     */
    private List<String> actions = new ArrayList<String>();

    public Map<String, Data> getData() {
        return data;
    }

    public void setData(Map<String, Data> data) {
        this.data = data;
    }

    public String getIdentifier() {
        return identifier;
    }

    public void setIdentifier(String identifier) {
        this.identifier = identifier;
    }

    public List<String> getActions() {
        return actions;
    }

    public void setActions(List<String> actions) {
        this.actions = actions;
    }

    public int getLineNo() {
        return lineNo;
    }

    public void setLineNo(int lineNo) {
        this.lineNo = lineNo;
    }

    /**
     * 数据结果封装
     */
    public static class Data implements Serializable {
        /**
         * 原始值
         */
        private Object s;
        /**
         * 显示值
         */
        private Object v;

        public Data() {
        }

        public Data(Object value) {
            this.v = value;
        }

        public Data(Object sValue, Object value) {
            this.s = sValue;
            this.v = value;
        }

        public Object getS() {
            return s;
        }

        public Object getV() {
            return v;
        }
    }
}


:::

6.2 op=viewDetail：查看记录的详情信息

是否支持viewDetail不是必须的，由op=default列表中ListRowData#actions中是否包含“viewDetail”决定，如果某一行支持查看详情，则必须同时设置ListRowData#identifier属性（在获取查看详情链接的时候会带上identified来作为标志用户查看哪一行的详情）。查看详情的数据结果请求返回的是一个多快捷入口返回格式（有i与单一行可能是由多个信息主体关联而成），格式如下：

:::demo

/**
 * @Title: 多超链接返回结果
 * @Description: 针对查询和统计一条数据有多个返回链接
 * @Company: seeyon.com
 * @Team: ouyp Seeyon CAP4
 * @Date: 2019/8/28 20:29
 */
public class MultiLinkDataSetResult implements DataSetResult {

    @Override
    public Integer getDataFormat() {
        return BizPortalConstants.DataFormat.LINK.getCode();
    }

    @Override
    public String getVersion() {
        return BizPortalConstants.Version.V1.name();
    }

    public static MultiLinkDataSetResult of(LinkDataSetResult link) {
        MultiLinkDataSetResult that = new MultiLinkDataSetResult();
        that.links.add(create(link));
        return that;
    }

    public static MultiLinkDataSetResult of(String href) {
        return of(LinkDataSetResult.of(href));
    }

    public static WithLabelLinkDataSet create(LinkDataSetResult linkDataSetResult, String label) {
        WithLabelLinkDataSet withLabelLinkDataSet = new WithLabelLinkDataSet();
        BizPortalUtils.copyProperties(withLabelLinkDataSet, linkDataSetResult);
        withLabelLinkDataSet.label = label;
        return withLabelLinkDataSet;
    }

    public static WithLabelLinkDataSet create(LinkDataSetResult linkDataSetResult) {
        return create(linkDataSetResult, StringUtils.EMPTY);
    }

    /**
     * 超链接列表
     */
    private List<WithLabelLinkDataSet> links = Lists.newArrayList();

    public List<WithLabelLinkDataSet> getLinks() {
        return links;
    }

    public void setLinks(List<WithLabelLinkDataSet> links) {
        this.links = links;
    }

    public static class WithLabelLinkDataSet extends MobileLinkDataSetResult {
        private String label;

        public String getLabel() {
            return label;
        }

        public void setLabel(String label) {
            this.label = label;
        }
    }
}


:::

6.3 列表数据源开发参考示例

:::demo

/**
 * @Title: 数据源连接——列表
 * @Description: 应用报表
 * @Company: seeyon.com
 * @Team: Seeyon CAP4
 * @Date: 2019-06-06 10:25
 */
public class DefaultReportListDataSourceProvider extends DefaultDataSourceProvider implements InitializingBean {
    // fields
    private Map<String, InvokeHandler> invokeHandlerMap = Maps.newHashMap();
    private BizPortalReportAdapterManager bizPortalReportAdapterManager;

    //setter
    public void setInvokeHandlerMap(Map<String, InvokeHandler> invokeHandlerMap) {
        this.invokeHandlerMap = invokeHandlerMap;
    }

    public void setBizPortalReportAdapterManager(BizPortalReportAdapterManager bizPortalReportAdapterManager) {
        this.bizPortalReportAdapterManager = bizPortalReportAdapterManager;
    }

    @Override
    public void afterPropertiesSet() throws Exception {
        // 注意1： 注入标志产品支持的操作方式，如客开添加其他命令，可以在spring配置文件中设置invokeHandlerMap达到功能增强
        invokeHandlerMap.put("default", new DefaultInvokeHandler());
        invokeHandlerMap.put("viewDetail", new DefaultViewDetailInvokeHandler());
    }

    @Override
    public BizPortalConstants.DataFormat dataFormat() {
        return BizPortalConstants.DataFormat.LIST;
    }

    @Override
    public int getSortOrder() {
        return 1;
    }

    @Override
    public String uuid() {
        return "56abc264-6cd6-48a8-8967-96b1fd89f2d3";
    }

    @Override
    public String name() {
        return "应用报表";
    }

    @Override
    public DefaultDataSetList getDataSetList(ContextParam contextParam, DataSetMetadata dataSetMetadata, String[] versions) throws BusinessException {
        DefaultDataSetList dataSetList = new DefaultDataSetList();
        BizConfigBean configBean = bizPortalExternAdapterManager.getBizConfigBean(getMultiStepId(dataSetMetadata));
        Long bizId = configBean.getId();
        // 根节点
        DefaultDataSetList.Node rootNode = dataSetList.createBranchNode(bizId.toString(), name());
        dataSetList.addNode(rootNode);
        // 查询列表
        List<ReportDesignDefinition> reportConfigs = bizPortalReportAdapterManager.findReportDesignDefinition(ApplicationCategoryEnum.cap4biz.name(), bizId.toString(), DesignType.QUERY);
        if (CollectionUtils.isNotEmpty(reportConfigs)) {
            for (ReportDesignDefinition config : reportConfigs) {
                DefaultDataSetList.Node leafNode = dataSetList.createLeafNode(getNodeId(config.getDesignId()),
                        config.getTitle(),
                        configBean.getName() + "-" + config.getTitle(),
                        rootNode.getId(),
                        new DataSetMetadata(uuid()).attr(BIZ_ID, bizId).attr(BIZ_ID, bizId).attr("designId", config.getDesignId()));
                dataSetList.addNode(leafNode);
            }
        }
        return dataSetList;
    }

    @Override
    public boolean isAllow(ContextParam contextParam, DataSetMetadata metadata, Command command) throws BusinessException {
        return bizPortalReportAdapterManager.checkAuth(getDesignId(command, metadata), contextParam.getUserId());
    }

    @Override
    public DataSetResult executeQuery(ContextParam contextParam, DataSetMetadata metadata, String[] versions, Command command) throws BusinessException {
        return getInvokeHandler(command).executeQuery(contextParam, metadata, versions, command);
    }

    @Override
    public DataSetMetadata beforeDataSetMetaBind(String dataId, DataSetMetadata metadata) throws BusinessException {
        return metadata.attr("designId", createBizPortalDataRelation(getBizId(metadata), dataId, metadata.attrLong("designId")));
    }

    @Override
    protected String getId(Command command, DataSetMetadata metadata) throws BusinessException {
        return getDesignId(command, metadata).toString();
    }

    private Long getDesignId(Command command, DataSetMetadata metadata) throws BusinessException {
        return attrRealLong(command, metadata, "designId");
    }

    /**
     * 获取命令操作类
     * @param command
     * @return
     */
    private InvokeHandler getInvokeHandler(Command command) {
        return invokeHandlerMap.get(command.getOp());
    }

    /**
     * 默认命令处理类
     */
    private class DefaultInvokeHandler implements InvokeHandler {
        @Override
        public DataSetResult executeQuery(ContextParam contextParam, DataSetMetadata metadata, String[] versions, Command command) throws BusinessException {
            Long designId = getDesignId(command, metadata);

            FlipInfo fi = new FlipInfo();
            // 注意2：这里是带了分页信息的，列表数据源需要处理分页场景
            PaginationParam paginationParam = PaginationParam.of(command);
            fi.setPage(paginationParam.getPage());
            fi.setSize(paginationParam.getPageSize());
            fi.setNeedTotal(true);

            UserConditions userConditions = new UserConditions();
            ListDataResult list = bizPortalReportAdapterManager.findQueryDataResult(designId, userConditions, fi);

            return ListDataSetResult.of(list);
        }
    }

    /**
     * 查询穿透查看详情
     */
    private class DefaultViewDetailInvokeHandler implements ViewDetailInvokeHandler {
        @Override
        public MultiLinkDataSetResult executeQuery(ContextParam contextParam, DataSetMetadata metadata, String[] versions, Command command) throws BusinessException {
            Long designId = getDesignId(command, metadata);
            String extendParams = command.getAttributes().get("identifier").toString();
            return bizPortalReportAdapterManager.getQueryPenetrateInfo(contextParam, designId, extendParams);
        }
    }
}


:::

----------------------------------------


## 七、数据版本

由于暂时所以的数据格式都只有V1版本，但不排除后期对数据格式有版本升级，故平台建议数据源开发者

1.不要重写AbstractDataSourceProvider#versions方法；2. 返回的数据结果的versio均指定为Version.V1。

编撰人：yinyanting




快速跳转



 * 数据源开发
   * 一、数据格式
   * 二、数据源类图
   * 三、数据源主要API介绍
   * 四、指标数据源开发
   * 五、快捷入口数据源开发
   * 六、列表数据源开发
   * 七、数据版本



分享链接分享链接

## 107. 数据格式

> 原始路径：`/94/355/359/479/506/509.html`  
> 相对路径：`94/355/359/479/506/509.md`  
> JS Chunk：`app.371b709c.js`

## 数据格式


## 数据格式

数据格式   格式编码
指标     1
快捷入口   2
菜单     3
列表     4
统计列表   5
个人信息   6


## 数据版本

数据版本   版本编码
V1     V1


## 数据格式-指标

{
  "source": "8",
  "value": "8",
  "fieldType": "DECIMAL",
  "version": "V1",
  "dataFormat": "1"
}



## 数据格式-快捷入口

{
  "href": "/seeyon/report4Result.do?method=showResult&designType=QUERY&designId=-7748046540639024958",
  "version": "V1",
  "dataFormat": "2"
}



## 数据格式-菜单

{
  "id": "-1725826174662848879",
  "name": "业务空间",
  "imgSrc": "/fileUpload.do?method=showRTE&fileId=8225193822529209404&createDate=2019-8-5&type=image",
  "items": [
    {
      "id": "-3142428952920175746",
      "name": "业务首页",
      "icon": "cap-icon-Businessportal",
      "parentId": "-1725826174662848879",
      "target": "newWindow",
      "url": "/seeyon/cap4/businessTemplateController.do?method=businessIndex&bussId=-6115980305565398932"
    },
    {
      "id": "15603391934020",
      "name": "无流程表单-1",
      "imgSrc": "/fileUpload.do?method=showRTE&fileId=-3069999976959685492&createDate=2019-8-5&type=image",
      "parentId": "-1725826174662848879",
      "target": "newWindow",
      "url": "/seeyon/cap4/businessTemplateController.do?method=capUnflowList&srcFrom=bizconfig&businessId=-6115980305565398932&moduleId=-5447215666925712065&formId=3382674407659816373&type=baseInfo&tag=1564971106435"
    },
    {
      "id": "15608408734480",
      "name": "流程模板1",
      "icon": "cap-icon-human-resources",
      "parentId": "-1725826174662848879",
      "target": "newWindow",
      "url": "/seeyon/collaboration/collaboration.do?method=newColl&from=bizconfig&firstName=%E4%B8%9A%E5%8A%A1%E7%A9%BA%E9%97%B4&secondName=%E6%B5%81%E7%A8%8B%E6%A8%A1%E6%9D%BF1&menuId=-1725826174662848879&templateId=-211208903950905634"
    },
    {
      "id": "15647262660510",
      "name": "主从表枚举",
      "icon": "cap-icon-cost-management",
      "parentId": "-1725826174662848879",
      "target": "newWindow",
      "url": "/seeyon/cap4/businessTemplateController.do?method=capUnflowList&srcFrom=bizconfig&businessId=-6115980305565398932&moduleId=384385011724337873&formId=8869544524283333456&type=baseInfo&tag=1564971106435"
    },
    {
      "id": "15608408807318",
      "name": "二级菜单1",
      "icon": "cap-icon-administrative-management",
      "parentId": "-1725826174662848879",
      "target": "mainfrm",
      "url": "/seeyonnull"
    },
    {
      "id": "156084088582510",
      "name": "流程代办列表",
      "icon": "cap-icon-asset-management",
      "parentId": "15608408807318",
      "target": "mainfrm",
      "url": "/seeyon/cap4/businessTemplateController.do?method=capFlowListNew&srcFrom=bizconfig&businessId=-6115980305565398932&moduleId=-5898317688602278531&formId=414564057231344759"
    },
    {
      "id": "156084089821212",
      "name": "查询-1",
      "icon": "cap-icon-contract-management",
      "parentId": "15608408807318",
      "target": "mainfrm",
      "url": "/seeyon/report4Result.do?method=showResult&designType=QUERY&designId=-4861021556841823778&businessId=-6115980305565398932"
    }
  ],
  "version": "V1",
  "dataFormat": "3"
}



## 数据格式-列表

{
  "fields": [
    {
      "key": "formmain_0017_0_field0001",
      "name": "文本1",
      "inputType": "text",
      "fieldType": "VARCHAR",
      "length": "100",
      "digitNum": "0",
      "attributes": {
        "enumId": "0"
      },
      "actions": [
        "sort"
      ],
      "enumId": "0"
    },
    {
      "key": "formmain_0017_0_field0002",
      "name": "数字1",
      "inputType": "text",
      "fieldType": "DECIMAL",
      "length": "20",
      "digitNum": "0",
      "attributes": {
        "enumId": "0"
      },
      "actions": [
        "sort"
      ],
      "enumId": "0"
    },
    {
      "key": "formmain_0017_0_field0003",
      "name": "文本域1",
      "inputType": "textarea",
      "fieldType": "VARCHAR",
      "length": "255",
      "digitNum": "0",
      "attributes": {
        "enumId": "0"
      },
      "actions": [
        "sort"
      ],
      "enumId": "0"
    },
    {
      "key": "formmain_0017_0_id",
      "name": "主表ID_系统字段",
      "inputType": "text",
      "fieldType": "LONG",
      "digitNum": "0",
      "attributes": {},
      "actions": [
        "sort"
      ]
    },
    {
      "key": "formmain_0017_0_finishedflag",
      "name": "流程状态_系统字段",
      "inputType": "customenum",
      "fieldType": "INTEGER",
      "digitNum": "0",
      "attributes": {
        "formType": "1"
      },
      "actions": [
        "sort"
      ]
    },
    {
      "key": "formmain_0017_0_field0005",
      "name": "下拉1",
      "inputType": "select",
      "fieldType": "DECIMAL",
      "length": "20",
      "digitNum": "0",
      "attributes": {
        "enumId": "-6161890562859515306",
        "isFinalChild": false,
        "enumLevel": "0"
      },
      "actions": [
        "sort"
      ],
      "enumId": "-6161890562859515306",
      "enumLevel": "0",
      "finalChild": false
    }
  ],
  "size": "20",
  "data": [
    {
      "data": {
        "0": {},
        "1": {
          "s": "2",
          "v": "2"
        },
        "2": {
          "s": "3",
          "v": "3"
        },
        "3": {
          "s": "-8664099259836709757",
          "v": "-8664099259836709757"
        },
        "4": {
          "s": "0",
          "v": "未结束"
        },
        "5": {
          "s": "-3727256975531228803",
          "v": "重要"
        }
      },
      "identifier": "{\"formmain_0017_0_id\":\"-8664099259836709757\"}",
      "lineNo": "0",
      "actions": [
        "viewDetail"
      ]
    },
    {
      "data": {
        "0": {},
        "1": {
          "s": "1",
          "v": "1"
        },
        "2": {
          "s": "2",
          "v": "2"
        },
        "3": {
          "s": "-2776354056516908447",
          "v": "-2776354056516908447"
        },
        "4": {
          "s": "1",
          "v": "已结束"
        },
        "5": {}
      },
      "identifier": "{\"formmain_0017_0_id\":\"-2776354056516908447\"}",
      "lineNo": "1",
      "actions": [
        "viewDetail"
      ]
    },
    {
      "data": {
        "0": {},
        "1": {
          "s": "1",
          "v": "1"
        },
        "2": {
          "s": "1",
          "v": "1"
        },
        "3": {
          "s": "828532004649324104",
          "v": "828532004649324104"
        },
        "4": {
          "s": "0",
          "v": "未结束"
        },
        "5": {}
      },
      "identifier": "{\"formmain_0017_0_id\":\"828532004649324104\"}",
      "lineNo": "2",
      "actions": [
        "viewDetail"
      ]
    },
    {
      "data": {
        "0": {},
        "1": {
          "s": "1",
          "v": "1"
        },
        "2": {
          "s": "2",
          "v": "2"
        },
        "3": {
          "s": "7649403830094875642",
          "v": "7649403830094875642"
        },
        "4": {
          "s": "0",
          "v": "未结束"
        },
        "5": {}
      },
      "identifier": "{\"formmain_0017_0_id\":\"7649403830094875642\"}",
      "lineNo": "3",
      "actions": [
        "viewDetail"
      ]
    },
    {
      "data": {
        "0": {
          "s": "1",
          "v": "1"
        },
        "1": {
          "s": "1",
          "v": "1"
        },
        "2": {
          "s": "1",
          "v": "1"
        },
        "3": {
          "s": "7819421277139782857",
          "v": "7819421277139782857"
        },
        "4": {
          "s": "0",
          "v": "未结束"
        },
        "5": {
          "s": "-2557046271853379313",
          "v": "普通"
        }
      },
      "identifier": "{\"formmain_0017_0_id\":\"7819421277139782857\"}",
      "lineNo": "4",
      "actions": [
        "viewDetail"
      ]
    }
  ],
  "total": "5",
  "version": "V1",
  "page": "1",
  "dataFormat": "4",
  "pages": "1",
  "executeTime": "2019-08-14"
}



## 数据格式-统计列表

{
  "fields": [
    {
      "key": "formmain_0017_field0001",
      "name": "文本1",
      "inputType": "text",
      "fieldType": "VARCHAR",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "headerField": true,
      "columnMerge": false,
      "formulaField": false,
      "rowMerge": false
    },
    {
      "key": "formmain_0017_field0005",
      "name": "下拉1",
      "inputType": "select",
      "fieldType": "DECIMAL",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "headerField": true,
      "columnMerge": false,
      "formulaField": false,
      "rowMerge": false
    },
    {
      "key": "col_0_formmain_0017_field0003",
      "name": "文本域1",
      "inputType": "textarea",
      "fieldType": "VARCHAR",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "displayField": {
        "aliasTableName": "formmain_0017",
        "name": "field0003",
        "aliasDisplay": "文本域1",
        "digitNum": "0",
        "formatType": "",
        "exportDigitNum": "0",
        "exportFormatType": "",
        "penetrateEnable": false,
        "hideField": false,
        "calcType": "count"
      },
      "headerField": false,
      "columnMerge": false,
      "formulaField": false,
      "rowMerge": false,
      "calcType": "count",
      "parentField": {
        "key": "col_0",
        "name": "",
        "inputType": "DECIMAL",
        "fieldType": "select",
        "digitNum": "0",
        "attributes": {},
        "actions": [],
        "data": {}
      }
    },
    {
      "key": "col_0_formmain_0017_id",
      "name": "主表ID_系统字段",
      "inputType": "text",
      "fieldType": "LONG",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "displayField": {
        "aliasTableName": "formmain_0017",
        "name": "id",
        "aliasDisplay": "主表ID_系统字段",
        "digitNum": "0",
        "formatType": "",
        "exportDigitNum": "0",
        "exportFormatType": "",
        "penetrateEnable": false,
        "hideField": false,
        "calcType": "count"
      },
      "headerField": false,
      "columnMerge": false,
      "formulaField": false,
      "rowMerge": false,
      "calcType": "count",
      "parentField": {
        "key": "col_0",
        "name": "",
        "inputType": "DECIMAL",
        "fieldType": "select",
        "digitNum": "0",
        "attributes": {},
        "actions": [],
        "data": {}
      }
    },
    {
      "key": "col_1_formmain_0017_field0003",
      "name": "文本域1",
      "inputType": "textarea",
      "fieldType": "VARCHAR",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "displayField": {
        "aliasTableName": "formmain_0017",
        "name": "field0003",
        "aliasDisplay": "文本域1",
        "digitNum": "0",
        "formatType": "",
        "exportDigitNum": "0",
        "exportFormatType": "",
        "penetrateEnable": false,
        "hideField": false,
        "calcType": "count"
      },
      "headerField": false,
      "columnMerge": false,
      "formulaField": false,
      "rowMerge": false,
      "calcType": "count",
      "parentField": {
        "key": "col_1",
        "name": "三级枚举",
        "inputType": "DECIMAL",
        "fieldType": "select",
        "digitNum": "0",
        "attributes": {},
        "actions": [],
        "data": {
          "s": "4844510305374653145",
          "v": "三级枚举"
        }
      }
    },
    {
      "key": "col_1_formmain_0017_id",
      "name": "主表ID_系统字段",
      "inputType": "text",
      "fieldType": "LONG",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "displayField": {
        "aliasTableName": "formmain_0017",
        "name": "id",
        "aliasDisplay": "主表ID_系统字段",
        "digitNum": "0",
        "formatType": "",
        "exportDigitNum": "0",
        "exportFormatType": "",
        "penetrateEnable": false,
        "hideField": false,
        "calcType": "count"
      },
      "headerField": false,
      "columnMerge": false,
      "formulaField": false,
      "rowMerge": false,
      "calcType": "count",
      "parentField": {
        "key": "col_1",
        "name": "三级枚举",
        "inputType": "DECIMAL",
        "fieldType": "select",
        "digitNum": "0",
        "attributes": {},
        "actions": [],
        "data": {
          "s": "4844510305374653145",
          "v": "三级枚举"
        }
      }
    },
    {
      "key": "formmain_0017_field0003",
      "name": "文本域1",
      "inputType": "textarea",
      "fieldType": "VARCHAR",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "displayField": {
        "aliasTableName": "formmain_0017",
        "name": "field0003",
        "aliasDisplay": "文本域1",
        "digitNum": "0",
        "formatType": "",
        "exportDigitNum": "0",
        "exportFormatType": "",
        "penetrateEnable": false,
        "hideField": false,
        "calcType": "count"
      },
      "headerField": false,
      "columnMerge": true,
      "formulaField": false,
      "rowMerge": false,
      "calcType": "count",
      "parentField": {
        "key": "col_2",
        "name": "列汇总",
        "digitNum": "0",
        "attributes": {},
        "actions": [],
        "data": {
          "v": "列汇总"
        }
      }
    },
    {
      "key": "formmain_0017_id",
      "name": "主表ID_系统字段",
      "inputType": "text",
      "fieldType": "LONG",
      "digitNum": "0",
      "attributes": {},
      "actions": [],
      "displayField": {
        "aliasTableName": "formmain_0017",
        "name": "id",
        "aliasDisplay": "主表ID_系统字段",
        "digitNum": "0",
        "formatType": "",
        "exportDigitNum": "0",
        "exportFormatType": "",
        "penetrateEnable": false,
        "hideField": false,
        "calcType": "count"
      },
      "headerField": false,
      "columnMerge": true,
      "formulaField": false,
      "rowMerge": false,
      "calcType": "count",
      "parentField": {
        "key": "col_2",
        "name": "列汇总",
        "digitNum": "0",
        "attributes": {},
        "actions": [],
        "data": {
          "v": "列汇总"
        }
      }
    }
  ],
  "size": "0",
  "data": [
    {
      "data": {
        "0": {},
        "1": {},
        "2": {
          "s": "5",
          "v": "5"
        },
        "3": {
          "s": "5",
          "v": "5"
        },
        "4": {
          "s": "1",
          "v": "1"
        },
        "5": {
          "s": "1",
          "v": "1"
        },
        "6": {
          "s": "6",
          "v": "6"
        },
        "7": {
          "s": "6",
          "v": "6"
        }
      },
      "lineNo": "0",
      "actions": [],
      "subTotal": false,
      "total": false
    },
    {
      "data": {
        "0": {},
        "1": {
          "s": "-3727256975531228803",
          "v": "重要"
        },
        "2": {
          "s": "1",
          "v": "1"
        },
        "3": {
          "s": "1",
          "v": "1"
        },
        "4": {},
        "5": {},
        "6": {
          "s": "1",
          "v": "1"
        },
        "7": {
          "s": "1",
          "v": "1"
        }
      },
      "lineNo": "1",
      "actions": [],
      "subTotal": false,
      "total": false
    },
    {
      "data": {
        "0": {},
        "1": {
          "s": "-2557046271853379313",
          "v": "普通"
        },
        "2": {},
        "3": {},
        "4": {
          "s": "1",
          "v": "1"
        },
        "5": {
          "s": "1",
          "v": "1"
        },
        "6": {
          "s": "1",
          "v": "1"
        },
        "7": {
          "s": "1",
          "v": "1"
        }
      },
      "lineNo": "2",
      "actions": [],
      "subTotal": false,
      "total": false
    },
    {
      "data": {
        "0": {
          "s": "1",
          "v": "1"
        },
        "1": {
          "s": "-2557046271853379313",
          "v": "普通"
        },
        "2": {},
        "3": {},
        "4": {
          "s": "1",
          "v": "1"
        },
        "5": {
          "s": "1",
          "v": "1"
        },
        "6": {
          "s": "1",
          "v": "1"
        },
        "7": {
          "s": "1",
          "v": "1"
        }
      },
      "lineNo": "3",
      "actions": [],
      "subTotal": false,
      "total": false
    },
    {
      "data": {
        "0": {
          "v": "合计"
        },
        "1": {},
        "2": {
          "s": "6",
          "v": "6"
        },
        "3": {
          "s": "6",
          "v": "6"
        },
        "4": {
          "s": "3",
          "v": "3"
        },
        "5": {
          "s": "3",
          "v": "3"
        },
        "6": {
          "s": "9",
          "v": "9"
        },
        "7": {
          "s": "9",
          "v": "9"
        }
      },
      "lineNo": "4",
      "actions": [],
      "subTotal": false,
      "total": true
    }
  ],
  "version": "V1",
  "total": "0",
  "page": "0",
  "pages": "0",
  "dataFormat": "5"
}



## 数据格式-个人信息

{
  "values": {
    "652728791064661657": {
      "success": true,
      "data": {
        "memberId": "4362114081108477725",
        "memberName": "乔巴",
        "postId": "-4767074113794126247",
        "postName": "船医",
        "avatarUrl": "/seeyon/rest/orgMember/avatar/4362114081108477725",
        "version": "V1",
        "dataFormat": "6"
      }
    }
  }
}


编撰人：yinyanting


快速跳转



 * 数据格式
   * 数据格式
   * 数据版本
   * 数据格式-指标
   * 数据格式-快捷入口
   * 数据格式-菜单
   * 数据格式-列表
   * 数据格式-统计列表
   * 数据格式-个人信息



分享链接分享链接

## 108. 1、进入业务空间

> 原始路径：`/94/355/359/479/511/512.html`  
> 相对路径：`94/355/359/479/511/512.md`  
> JS Chunk：`app.371b709c.js`

## 1、进入业务空间




## 2、进入预览界面



示例：

获取的url

关键参数，必须要包含

【spaceId】空间id

【configId】配置id  ----》注意：修改门户保存后，此id会变，需要重新获取此id，放入到获取的url中。如果不更新此id，新配置的东西不会在旧url上生效。（8.2及8.2之后，可不传configId，默认获取最新配置，这样就不需要频繁更新configId）

【bizId】业务包id

【platform】平台：1：pc  2：移动

必须要删除的参数【preview】，这个参数会导致页面不让用户点击。

处理前url：

/seeyon/common/cap4/template/designPortalSpace/dist/m3WapIndex.html?spaceId=-840430830350414234&configId=3732216110446037924&bizId=8530267299944680466&platform=2&bussId=8530267299944680466&preview=true

处理后url：

/seeyon/common/cap4/template/designPortalSpace/dist/m3WapIndex.html?spaceId=-840430830350414234&configId=3732216110446037924&bizId=8530267299944680466&platform=2

此url可以用于单点进入业务包门户。

编撰人：yinyanting




快速跳转



 * 1、进入业务空间
 * 2、进入预览界面



分享链接分享链接

## 109. 经过源码编译后的文件【xxxxx.clmn】才能导入。

> 原始路径：`/94/355/359/479/511/513.html`  
> 相对路径：`94/355/359/479/511/513.md`  
> JS Chunk：`app.371b709c.js`

## 经过源码编译后的文件【xxxxx.clmn】才能导入。



编撰人：yinyanting




快速跳转



 * 经过源码编译后的文件【xxxxx.clmn】才能导入。



分享链接分享链接

## 110. 应用包导入导出接入

> 原始路径：`/94/355/359/895.html`  
> 相对路径：`94/355/359/895.md`  
> JS Chunk：`app.371b709c.js`

## 应用包导入导出接入


## 说明

应用包的导入导出是个泛指，还包含了其他的应用定制平台下的包的导入导出。列表如下：

类型    来源               是否支持更新
应用包   应用管理或者基础数据       是
表单    表单管理或者应用包里面的表单   否
聚合包   聚合应用管理           是

除了导入导出和更新外，应用包（仅限应用包）还支持一种特殊操作：合并导入。可以将一个不相干的应用包的部分或者全部数据导入当前选择的应用包，类似于应用包合并。


## 导入导出上下文

导入导出的上下文类是BusinessDataBean，定义在cap-api这个工程。主要的属性说明如下：

属性                      存在场景（*表示全部）   说明
bizConfigBean           应用包和聚合包导入导出   当前导入或导出的应用包
appUpgradeCacheBean     全部            需要入库的数据，包含了businessDateBean的大部分功能
upgradeSourceApp        应用包或聚合包更新     被更新的应用包
upgradeSourceFormMap    应用包或聚合包更新     被更新的表单列表
exportType              *             FORM为表单导入导出，APPLICATION为应用包导入导出
importFormType          表单导入          0:保留原类型；1：有流程；2：无流程
upgrade                 更新场景          true表示应用包更新
formBeanList            *             导入的表单列表
isMallApp               应用包场景         是否是商品包
rootMap                 *             最终要写入应用包的数据或者从应用包读取的数据
extensionMap            *             最终要写入应用包的扩展数据或者从应用包读取的扩展数据
hasBaseData             应用包或者聚合包导入    是否有基础数据
capAppSetupBizMapping   *             id映射表，后面专门解释


## 接口说明

要接入应用包导入导出，一般来说，从一下两个抽象类实现其中一个即可

类名                                    所在工程       说明
AbstractBusinessModuleExportManager   cap-api    应用包下级模块或者基础模块的数据导入导出，类似报表，关联触发等
AbstractBusinessFormExportManager     cap-core   表单下级模块的数据导入导出接口，类似明细表，应用绑定等

这里要注意选择合适的接口，两个类的方法参数会有细微区别


## 方法说明

公共参数说明

businessDataBean 是应用包导入导出的上下文，在导入导出的时候可以将自己的数据存在该上下文，然后再不同的阶段使用
FormBean 表单的对象类，只有AbstractBusinessFormExportManager类方法有该参数，表示当前正在处理的表单，所以需要注意的是这个表单数据不一定是完整的。
appUpgradeCacheBean：入库数据，在importdata方法执行的时候，将要入库的数据放在该类中，最后入库的时候使用


AbstractBusinessModuleExportManager方法说明

方法                       参数                                           说明
exportData               rootMap表单要写入包文件的数据，所以要导出的数据需要添加到该map         数据导出
importData               表示从应用包中读取的包原始数据，需要查询自己的数据并解析                 数据导入
exportEnums                                                           枚举导出，一些特殊场景会使用没有在表单绑定的枚举，这些枚举需要在这个方法统一处理，否则导入时候可能会丢失
compatibilityDetection   CompatibilityDetectionResultBean表示不兼容的属性集合   在应用包更新的时候，需要对部分特殊无法更新的数据检测，如果这些数据发生了变更，则阻断更新，并提示用户
upgradeDataCompare       UpgradeCompareResultBean发生更新的属性说明            应用包更新场景下，需要对更新的数据做出描述，在这个方法处理，并将结果放入参数中
redirectBusiness         businessRedirectDataBean                     当前模块使用了组织架构的数据的话，需要对组织架构数据进行重定向，这个方法就是用来获取当前模块中所有组织架构数据的
mergeRedirectData        redirectData表示客户重定向的组织架构数据                   客户重定向操作执行后会将组织架构的映射信息传入当前方法，开发就可以更新当前模块的组织架构信息
completeSetup            appUpgradeCacheBean                          数据入库
cancelSetup                                                           取消安装，模块需要清理下缓存以及临时数据

AbstractBusinessFormExportManager方法说明。表单数据在循环处理时，会调用以下方法

方法                       参数                                                   说明
exportData               formDataMap表示要导出的表单数据                                导出表单数据，开发在处理好要导出的数据后，放于formDataMap即可
importData               dataMap从应用包读取的表单数据                                   导入表单数据，开发将参数中的dataMap处理成要入库的数据，存放formbean中
compatibilityDetection   同应用包，newFormBean表示包里的表单，cacheFormBean表示id相同的被更新的表单   更新场景下兼容性检测，同应用包
upgradeDataCompare       同上                                                   更新场景下获取更新说明，同应用包
redirectForm             同应用包redirectBusiness                                 同应用包redirectBusiness
mergeRedirectData        同应用包                                                 同应用包
completeSetup            同应用包                                                 同应用包
cancelSetup              同应用包                                                 同应用包


## 常用的导包场景判断

方法                                              说明
businessDataBean instanceof MergeSetupContext   是否是业务包合并的场景
businessDataBean.isSetup()                      true为安装，false为导出
businessDataBean.isUpgrade()                    true是更新场景
businessDataBean.isFormSetup()                  true为表单导入


## 应用包重复安装

什么是业务包重复安装？

就是一个业务包可以在同一个V5里面多次导入，但是导出后还可以互相更新。

举个例子：我在a82环境创建了一个应用包“合同管理”，我把这个应用包导出成syz文件，然后再导入a82，就会生成一个新的应用包“合同管理”，我把新的合同管理

导出来成syz，去更新最开始创建的哪个应用包，是可以更新成功的。再次新建一个应用包“合同应用”，导出后更新之前的包会提示不是同一个应用包，无法更新。

所以就会存在一个问题，同一个应用包导入了两次，id肯定不能相同，但是id不相同的话又怎么互相更新呢？

当前的解决方案是id映射，第一个合同管理的id是 345，在导出的时候会产生一个映射id345，再次导入的时候会生成一个随机的uuid例如123，同事建立123到345的映射，在123导出的时候，会把id重新还原成345，这样更新的时候就能判断是一个应用包。

上面说的生成映射和还原映射的方法在businessDatabean中已经提供。

还原id的方法（导出时候用）

方法                                                             说明
lookupBizKey(MappingTable table, Long sourceId)                用作应用包，表单，枚举，常量这四种类型的数据id的还原，MappingTable对应这四种类型，sourceId为当前的业务id。
lookupBizKey(MappingField field, Long sourceId, Long dataId)   用做应用包，表单下的子级的数据还原数据id，MappingField具体数据可以参考这个，根据ownerTable数据判断sourceId传入什么参数，例如视图的id替换，使用如下方式：businessDataBean.lookupBizKey(BusinessEnums.MappingField.VIEW_ID_MAPPING,
                                                               formBean.getId(), viewId))

创建或者查询id的的方法（导入用）

方法                                                             说明
generateOrGetRootId(MappingTable table, Long bizKey)           根据包里面的id创建或者生成一个id，已经生成的就返回，没有的话就创建一个
generateOrGetSubId(MappingField field, Long sourceId, Long     根据包里面的id创建或者生成一个子级id。例如：
bizKey)                                                        businessDataBean.generateOrGetSubId(BusinessEnums.MappingField.VIEW_ID_MAPPING,
                                                               formId, viewId)
onlyGetRootId(MappingTable table, Long bizKey)                 查询已经生成的id，没有的话返回null
onlyGetSubId(MappingField field, Long sourceId, Long bizKey)   查询已经生成的子级id，没有的话返回null：例如：businessDataBean.onlyGetSubId(BusinessEnums.MappingField.VIEW_ID_MAPPING,
                                                               formId, viewId)

除此之外，还有一些特殊方法：

方法                                              说明
findEnumItemId                                  查询枚举id的映射id，导入用
circulateFindId(Long sourceId, Boolean setup)   获取传入id的映射id，setup控制导入还是导出，慎用

> 注意：我们在处理id的时候不只是处理自己的数据的id，自己数据引用数据的id也要同步处理，不然导入的时候可能会丢失数据。例如我要处理一个计算公式，计算公式使用了枚举，这个计算公式的id要替换，计算公式中的枚举id也要替换。


## 数据处理

有些数据需要用户处理后才能入库，目前导入导出对这部分的支持比较弱，需要业务方与前端自行沟通，增加接口处理客户返回的数据。导入导出能提供的能力如下：


## 返回数据到前端

com.seeyon.cap4.form.modules.importandexport.BusinessDataBean#getResultMap();
com.seeyon.cap4.form.modules.importandexport.AppUpgradeCacheBean#getResultMap();


通过上面的方式获取到Map后，将要展示的数据放在这个map中即可，注意放入的数据需要实现Serializable接口.

至于key，和前端同事商量一致即可。


## 获取应用安装上下文

客户处理完处理后，需要业务方自己添加接口处理客户的数据，这个时候是需要业务上下文的。可以通过如下方式获取：

Long bizConfigId = ParamUtil.getLong(params, "bizConfigId", 0L);
        final AppUpgradeCacheBean appUpgradeCacheBean = businessImportAndExportManager.getAppUpgradeCacheBean(bizConfigId.toString());


编撰人：suylyf


快速跳转



 * 应用包导入导出接入
   * 说明
   * 导入导出上下文
   * 接口说明
     * 方法说明
   * 常用的导包场景判断
   * 应用包重复安装
   * 数据处理
     * 返回数据到前端
     * 获取应用安装上下文



分享链接分享链接

## 111. 文档概要

> 原始路径：`/94/355/360.html`  
> 相对路径：`94/355/360.md`  
> JS Chunk：`app.371b709c.js`

## 文档概要

CAP开发文档涵盖了基础业务组件、统计组件、栏目组件、自定义控件、自定义按钮、前后端API及针对客开的设计器配置和运行态接口的使用细则，文档总体结构如下：

编撰人：yinyanting、admin、xuecx




快速跳转



 * 文档概要



分享链接分享链接

## 112. vue快速上手

> 原始路径：`/94/355/361/362/363.html`  
> 相对路径：`94/355/361/362/363.md`  
> JS Chunk：`app.371b709c.js`

## vue快速上手

----------------------------------------


## 使用前准备

> 在使用之前，推荐学习Vue和ES2015，并正确配置Node.jsv6.x 或以上版本

基于Vue.js2.x+ 版本开发，所以有必要了解以下基础知识：

 * Vue 组件
 * 单文件组件


## 标准开发

实际项目中，往往会使用webpack，rollup或者gulp的工作流，大多可以做到按需加载页面用到的组件，所以不推荐直接使用<script>标签全局引入的方式使用。


## 全局组件使用

可以在项目的入口文件中引入所有组件或所需组件

import Cap4Business from 'cap4-business' // 引入组件库
import '../node_modules/Cap4Business/lib/index.css' // 引入样式库

Vue.use(Cap4Business)



## 单个组件按需使用，解构方式（会导致打包过大，推荐使用单引用）

可以局部注册所需的组件，适用于与其他框架组合使用的场景

import { Cap4Button } from 'cap4-business'

export default {
  components: {
    Cap4Button
  }
}



## 单个组件按需使用，单引用

可以局部注册所需的组件，适用于与其他框架组合使用的场景

import Cap4StatisticsPcTable from 'cap4-business/lib/cap4-statistics-pc-table';
import  'cap4-business/lib/cap4-statistics-pc-table/css/cap4-statistics-pc-table.css';

export default{
    components : {Cap4StatisticsPcTable}
}


在模板中，用<cap4-button></cap4-button>自定义标签的方式使用组件

<template>
  <div>
    <cap4-button>这是一个按钮</cap4-button>
  </div>
</template>


编撰人：yinyanting


快速跳转



 * vue快速上手
   * 使用前准备
   * 标准开发
     * 全局组件使用
     * 单个组件按需使用，解构方式（会导致打包过大，推荐使用单引用）
     * 单个组件按需使用，单引用



分享链接分享链接

## 113. 前端开发规范

> 原始路径：`/94/355/361/364/365/`  
> 相对路径：`94/355/361/364/365/README.md`  
> JS Chunk：`app.371b709c.js`

## 前端开发规范

总体原则

HTML规范

HTML&css规范

vue编码规范

Javascript规范

编撰人：yinyanting




快速跳转



 * 前端开发规范



分享链接分享链接

## 114. 总体原则

> 原始路径：`/94/355/361/364/365/366.html`  
> 相对路径：`94/355/361/364/365/366.md`  
> JS Chunk：`app.371b709c.js`

## 总体原则

 1. As short as possible（如无必要，勿增注释）。尽量提高代码本身的清晰性、可读性。
 2. As long as necessary（如有必要，尽量详尽）。合理的注释、空行排版等，可以让代码更易阅读、更具美感。

总之，注释的目的是：提高代码的可读性，从而提高代码的可维护性。


## 哪些需要注释

 1. 某段代码的写法，需要注释说明原因时：

// Using loop is more efficient than `rest = slice.call(arguments, 1)`.
for (i = 1, len = arguments.length; i < len; i++) {
    rest[i - 1] = arguments[i];
}


 1. 添加上注释，能让代码结构更清晰时：

init: function(selector, context, rootjQuery) {
    var match, elem, ret, doc;

    // Handle $(""), $(null), or $(undefined)
    if ( !selector ) {
        ...
    }

    // Handle $(DOMElement)
    if ( selector.nodeType ) {
        ...
    }

    // The body element only exists once, optimize finding it
    if ( typeof selector === "string" ) {
        ...
     }
}


 1. 有借鉴第三方代码，需要说明时：

// Inspired by https://github.com/jquery/jquery/blob/master/src/core.js
function ready() {
    ...
}


 1. 当有值的判断或者选择，有不同的分支时：

// It need to do when the value of a  is one or two. 
if(a === 1 || a === 2) {
    ...
}



## 起始约定

每个源码文件的开头，保留为空：

define('lego',[],function() {
    // 源代码
});


注意点：

 1. 文件头不注明Author信息，通过README来提供author & contributors。（组件规则，业务代码需要注明方便查看）


## 注释书写规范

 1. 源码中的注释，推荐用英文。
 2. 含有中文时，标点符号用中文全角。
 3. 中英文夹杂时，英文与中文之间要用一个空格分开。
 4. 注释标识符与注释内容要用一个空格分开：// 注释 与 /* 注释 */。
 5. 单行注释用// 注释 与多行注视用 /* 注释 */区分开来，能够一行注视明白的不写过多注视


## JSDoc 注释

 * 不推荐 JSDoc 式注释，推荐 Backbone 风格的注释。
 * API 请通过 README 等文档表达清楚。
 * 不写 JSDoc 类文档，可以让开发者在写代码时更专注于写代码，在写文档时则更专注于写文档。让工作解耦，更专注。
   编撰人：yinyanting


快速跳转



 * 总体原则
 * 哪些需要注释
 * 起始约定
 * 注释书写规范
 * JSDoc 注释



分享链接分享链接

## 115. HTML规范

> 原始路径：`/94/355/361/364/365/367.html`  
> 相对路径：`94/355/361/364/365/367.md`  
> JS Chunk：`app.371b709c.js`

## HTML规范


## 强制缩进使用 4个空格


## 强制属性使用双引号


## 建议不在自动闭合标签后加/


## 强制doctype使用大写

<!DOCTYPE html>
<html>
    <head>
    </head>
</html>



## 强制除非有特殊需求,一律使用UTF8编码,书写方式约定为:

<head>
    <meta charset="UTF-8">
</head>



## 强制引入css/js时,一律不加type

<link rel="stylesheet" href="main.css">
<style>
/*...*/
</style>
<script>
//...
</script>



## 建议img加alt


## 建议link加title


## 建议统一顺序, 增加gzip的压缩比

<a href="javascript:void(0);" target="_blank" class="item" id="xxx" title="xxx">xxx</a>
<a href="javascript:void(0);" target="_blank" class="item" id="yyy" title="yyy">yyy</a>


编撰人：yinyanting


快速跳转



 * HTML规范
   * 强制缩进使用 4个空格
   * 强制属性使用双引号
   * 建议不在自动闭合标签后加/
   * 强制doctype使用大写
   * 强制除非有特殊需求,一律使用UTF8编码,书写方式约定为:
   * 强制引入css/js时,一律不加type
   * 建议img加alt
   * 建议link加title
   * 建议统一顺序, 增加gzip的压缩比



分享链接分享链接

## 116. html&css规范

> 原始路径：`/94/355/361/364/365/368.html`  
> 相对路径：`94/355/361/364/365/368.md`  
> JS Chunk：`app.371b709c.js`

## html&css规范

浏览器兼容ie8+，如要使用动画，则采用优雅降级处理ie8，9效果。


## html规范


## 基础

 * 使用html5文档申明
 * 尽量使用更加语义化的html5标签，参考：Sections and Outlines of an HTML5 Document，考虑到ie8不支持html5标签，可以引入html5.js
 * 若需支持响应式设计（pc+pad）,则需要为ie8引入respond.js
 * 一般按照从上至下、从左到右的视觉顺序书写HTML结构，但有时候为了便于搜索引擎抓取或布局考虑，我们也会不按照视觉顺序书写
 * HTML标签名、属性名必须全部采用小写，属性必须加引号，并且必须闭合，单标签也必须闭合，如：<input type=”text” />、<br />
 * 结构(html)，表现(css)，行为(js)相分离，避免直接将css或js写在标签结构里
 * 标签挂靠的class不要过多，最多别超过4个
 * 请不要在内联元素中嵌入块级元素，如span里面有div标签，a里面包裹h2等(h5 a元素可以嵌套块级元素)
 * ul/ol的直接子元素只能是li
 * 数据类内容，大胆的使用table
 * a元素提供title属性，img提供alt属性，如果img大小固定，请记得使用width和height属性（如<img src="" alt="" width="200" height="100" />）
 * 页面中不要使用&nbsp进行缩进，如需缩进，使用CSS的text-indent来控制，如text-indent:2em用于中文的缩进两个空格
 * js操作属性，请以data-为前缀
 * i标签用于图标


## 注释

采用类似标签闭合的写法，与HTML统一格式；注释文案两头空格 。 允许只有开始注释！

<!-- header -->
<div class="header">
    <div class="inner-center"></div>
</div>
<!-- /header -->



## 常用结构

## PC空白模板

<!doctype html>
<html>
<head>
 <meta charset="UTF-8">
 <meta name="renderer" content="webkit">
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta name="keywords" content="">
 <meta name="description" content="">
 <meta name="format-detection"content="telephone=no,email=no"/>
 <title>page title</title>
</head>
<body></body>
</html>


如果需要ie8支持html5标签或者响应式，请引入对应的js，如下面采用html注释对ie8引入html5标签支持和响应式支持

<!--[if lt IE 9]>
 <script src="js/html5-respond.js"></script>
<![endif]-->


## Mobile空白模板

<!doctype html>
<html>
<head>
 <meta charset="UTF-8">
 <meta name="keywords" content="">
 <meta name="description" content="">
 <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
 <meta content="yes" name="apple-mobile-web-app-capable"/>
  <meta content="black" name="apple-mobile-web-app-status-bar-style"/>
 <meta name="format-detection"content="telephone=no,email=no"/>
 <title>page title</title>
</head>
<body></body>
</html>


## 常规布局

一般来说header和footer可能有全屏背景，所以居中部分添加.inner-center，container我们可以设计成全屏或居中，而其余的全屏部分我们可以独立出来，与header，container等并列，如全屏的滚动图片

header.header>.inner-center^
[section.featured>.inner-center^]
div.container.clearfix>aside.aside-left+main.main.clearfix+aside.aside-right^^
footer.footer>.inner-center


## 区块

边栏区块，特殊化区块请使用.x-block或.aside-block--xxx

.aside-block>.block-hd>h3.block-tt+.block-bd


内容区块，特殊化区块请使用.x-block或.section-block--xxx

.section-block>.block-hd>h2.block-tt+.block-bd


## 等分

//两列等分
.col-half.clearfix>.col-block*2>(.block-hd>h2.block-tt)+.block-bd
//三列等分
.col-third.clearfix>.col-block*3>(.block-hd>h2.block-tt)+.block-bd
//四列等分
.col-quarter.clearfix>.col-block*4>(.block-hd>h2.block-tt)+.block-bd



## 常用html转义符

 * space空格(&nbsp;)
 * 1个汉字空格(&emsp;)
 * 小于号<(&lt;)
 * 大于号>(&gt;)
 * 连接号&(&amp;)
 * 双引号"(&quot;)
 * 单引号'(&apos;)
 * 版权©(&copy;)
 * 间隔符·(&middot)
 * 人民币￥(&yen;)


## scss/css


## 基础

 * scss/css文件开始添加编码：@charset "utf-8";
 * 简写模式，如：border:1px solid #ccc;
 * 请不要直接定义标签样式，如span{},div{}
 * 选择器如无特殊情况最多不要超过4层，请使用高效率选择器,可参阅：CSS选择器的优化
 * 多数值为0时可以省略单位（好像0deg要带单位，某个浏览器有bug，然后@keyframes的0%单位不可省略）
 * z-index一般以5为一个步长（如50,55,60），方便以后增加或修改
 * 如果是自己写前缀，请把所有前缀写在标准的前面(如-webkit-transition:0.3s;transition:0.3s;)，关于前缀情况，可参考can i use
 * 使用!important请小心，确认是否有必要
 * 使用clearfix或overflow或inline-block清除子元素的浮动，而不是空标签
 * 不使用影响到页面性能expression表达式与filter，opacity的filter兼容除外
 * 禁止使用.parent *{}选择器，即*{}选择器只能单独使用，绝对禁止在前面再加上父级元素
 * ie8只支持:first-child选择器，而不支持:last-child选择器，所以列表类的元素，可以使用:first-child对第一个元素进行特殊化处理，如需要对最后一个元素特殊化处理，则先考虑能否转成第一个元素，如果不能则对最后一个元素添加classlast
 * ie8只支持:before/after写法，不支持::before/after写法


## scss文件注意事项

 * 基础文件名以_为前缀，导入时可以省略_和后缀名.scss，默认不编译成css文件
 * 合理定义变量及使用@mixin
 * 选择器合理嵌套，最多嵌套不超过四层
 * 不要@extend .class，因为会产生冗余代码，如非得使用@extend，最好先定义一个%
 * 可以使用自动化工具生成各个浏览器前缀


## class命名

 * 小写英文，单词之间使用中划线（-）链接，如line-item
 * 列表类的class可采用.*-list>.*-item>.item-*,如ul.line-list>li.line-item>span.item-title
 * 特殊化某个类，采用两个中划线连接（--），如.line-list.line-list--arrow，基础类是.line-list右侧没有箭头，如需要右侧有箭头的可以追加类.line-list--arrow
 * 图标的class以.icon-为前缀，字体图标的class为.icon-font.i-name，另字体图标可参考字体图标规范


## 常用class关键词：

 * 布局类：header,footer,container,main,content,aside,page,section
 * 包裹类：wrap,inner
 * 区块类：region,block,box
 * 结构类：hd,bd,ft,top,bottom,left,right,middle,col,row,grid,span
 * 列表类：list,item,field
 * 主次类：primary,secondary,sub,minor
 * 大小类：s,m,l,xl
 * 状态类：active,current,checked,hover,fail,success,warn,error,on,off
 * 导航类：nav,prev,next,breadcrumb,forward,back,indicator,paging,first,last
 * 交互类：tips,alert,modal,pop,panel,tab,accordion,slide,scroll,overlay
 * 星级类：rate,star
 * 分割类：group,seperate,divider
 * 等分类：full,half,third,quarter
 * table类: table,tr,td,cell,row
 * 图片类：img,thumbnail,original,album,gallery
 * 语言类：cn,en
 * 其他语义类：btn,close,ok,cancel,switch; link,title,info,intro,more,icon; form,label,search,contact,phone,date,email,user; view,loading...


## 选择器权重

 * !important
 * 行内样式，指的是html文档中定义的style
 * ID选择器
 * 类，属性选择器和伪类选择器
 * 元素和伪元素


## 雪碧图

注意事项：

 * 单个图标之间必须保留空隙，空隙大小由容器大小及显示方式决定。这样做的好处是既考虑了“容错性”又提高了图片的可维护性。
 * 图标的排列方式排列方式分为以下几种：横向排列（容器宽度有限）、纵向排列（容器高度有限）、斜线排列（容器宽高不限），靠左排列（容器背景居左）、靠右排列（容器背景居右）、水平居中排列（容器背景水平居中）、垂直居中排列（容器背景垂直居中）。
 * 合并后图片大小不宜超过50K，建议大小在20K-50K之间。
 * 请保留雪碧图片的psd源文件，以方便后来的增删改，后来的所有的修改请在psd源文件中修改，然后再导出图片。

合并图片的一些原则（专题页面除外）：

 * 按照图片排列方式，把排列方式一样的图片进行合并，便于样式控制。
 * 按照模块或元件，把同属于一个模块或元件的图片进行合并，方便模块或元件的维护。以导航模块为例，整个导航栏的icon为一个雪碧图片，而不是和其他的混合在一起，方便后来的修改或扩展。
 * 按照图片大小，把大小一致或差不多的图片进行合并，可充分利用图片空间。
 * 按照图片色彩，把色彩一致或差不多的图片进行合并，保证合并后图片的色彩不过于丰富，可防止色彩失真。

最后请不要过度使用sprite背景图片，而是按照或页面，或模块，或元件的方式合并为雪碧图，更好的考虑到未来的修改或扩展。


## css注释

css块级注释及单行注释

/* -------------------------------------------------
 * 块级注释
 * -------------------------------------------------
*/ 

 /* 单行注释 */


scss块级注释及单行注释

// 块级注释
//----------------------------------------------------

// 单行注释


scss文件中的html结构注释法

- 以emmet书写方法为骨架
- ()表示特殊化追加的class，[]表示需要的属性，｛｝表示标签内的文本内容
- 单行判断采用单行注释法，以if开头
- 多行判断采用if,else,end if



## 给各大浏览器打hack

请以标准浏览器为准书写css代码，如遇兼容问题，先考虑换实现方法，在万不得已的情况下，采用hack解决

firefox

/* Firefox 3+ */
@-moz-document url-prefix() {}


chrome及safari

/* Chrome, Safari 3+ */
@media screen and (-webkit-min-device-pixel-ratio:0) {}


ie8-

.selector { property: value\9; }


filter不可使用该方法

**ie9+及其他高级浏览器 **

:root .selector {}


ie10+及其他高级浏览器

html[lang='\
en'] .selector 
{}


更多请查阅：hack速查英文版 / hack速查中文版


## 更多资料

 * css guideline
   编撰人：yinyanting


快速跳转



 * html&css规范
   * html规范
     * 基础
     * 注释
     * 常用结构
       * PC空白模板
       * Mobile空白模板
       * 常规布局
       * 区块
       * 等分
     * 常用html转义符
   * scss/css
     * 基础
     * scss文件注意事项
     * class命名
     * 常用class关键词：
     * 选择器权重
     * 雪碧图
     * css注释
     * 给各大浏览器打hack
   * 更多资料



分享链接分享链接

## 117. vue编码规范

> 原始路径：`/94/355/361/364/365/369.html`  
> 相对路径：`94/355/361/364/365/369.md`  
> JS Chunk：`app.371b709c.js`

## vue编码规范


## 目标

本规范提供了一种统一的编码规范来编写 Vue.js 代码。这使得代码具有如下的特性：

 * 其它开发者或是团队成员更容易阅读和理解。
 * IDE更容易理解代码，从而提供高亮、格式化等辅助功能
 * 更容易使用现有的工具
 * 更容易实现缓存以及代码包的分拆


## 准则

 * 基于模块开发
 * vue 组件命名
 * 组件表达式简单化
 * 组件 props 原子化
 * 验证组件的 props
 * 将 this 赋值给 component 变量
 * 组件结构化
 * 组件事件命名
 * 避免 this.$parent
 * 谨慎使用 this.$refs
 * 使用组件名作为样式作用域空间
 * 提供组件 API 文档
 * 提供组件 demo
 * 对组件文件进行代码校验
 * 只在需要时创建组件


## 基于模块开发

始终基于模块的方式来构建你的 app，每一个子模块只做一件事情。

Vue.js 的设计初衷就是帮助开发者更好的开发界面模块。一个模块是应用程序中独立的一个部分。


## How？

每一个 Vue 组件（等同于模块）首先必须专注于解决一个单一的问题，独立的、可复用的、微小的 和 可测试的。

如果你的组件做了太多的事或是变得臃肿，请将其拆分成更小的组件并保持单一的原则。一般来说，尽量保证每一个文件的代码行数不要超过 100 行。也请保证组件可独立的运行。比较好的做法是增加一个单独的 demo 示例。

↑ 回到目录


## Vue 组件命名

组件的命名需遵从以下原则：

 * 有意义的: 不过于具体，也不过于抽象
 * 简短: 2 到 3 个单词
 * 具有可读性: 以便于沟通交流

同时还需要注意：

 * 必须符合自定义元素规范: 使用连字符分隔单词，切勿使用保留字。
 * app- 前缀作为命名空间: 如果非常通用的话可使用一个单词来命名，这样可以方便于其它项目里复用。


## Why？

 * 组件是通过组件名来调用的。所以组件名必须简短、富有含义并且具有可读性。


## 如何做？

<!-- 推荐 -->
<app-header></app-header>
<user-list></user-list>
<range-slider></range-slider>

<!-- 避免 -->
<btn-group></btn-group> <!-- 虽然简短但是可读性差. 使用 `button-group` 替代 -->
<ui-slider></ui-slider> <!-- ui 前缀太过于宽泛，在这里意义不明确 -->
<slider></slider> <!-- 与自定义元素规范不兼容 -->


↑ 回到目录


## 组件表达式简单化

Vue.js 的表达式是 100% 的 Javascript 表达式。这使得其功能性很强大，但也带来潜在的复杂性。因此，你应该尽量保持表达式的简单化。


## Why？

 * 复杂的行内表达式难以阅读。
 * 行内表达式是不能够通用的，这可能会导致重复编码的问题。
 * IDE 基本上不能识别行内表达式语法，所以使用行内表达式 IDE 不能提供自动补全和语法校验功能。


## How？

如果你发现写了太多复杂并难以阅读的行内表达式，那么可以使用 method 或是 computed 属性来替代其功能。

<!-- 推荐 -->
<template>
  <h1>
    {{ `${year}-${month}` }}
  </h1>
</template>
<script type="text/javascript">
  export default {
    computed: {
      month() {
        return this.twoDigits((new Date()).getUTCMonth() + 1);
      },
      year() {
        return (new Date()).getUTCFullYear();
      }
    },
    methods: {
      twoDigits(num) {
        return ('0' + num).slice(-2);
      }
    },
  };
</script>

<!-- 避免 -->
<template>
  <h1>
    {{ `${(new Date()).getUTCFullYear()}-${('0' + ((new Date()).getUTCMonth()+1)).slice(-2)}` }}
  </h1>
</template>


↑ 回到目录


## 组件 props 原子化

虽然 Vue.js 支持传递复杂的 JavaScript 对象通过 props 属性，但是你应该尽可能的使用原始类型的数据。尽量只使用 JavaScript 原始类型（字符串、数字、布尔值）和函数。尽量避免复杂的对象。


## Why？

 * 使得组件 API 清晰直观。
 * 只使用原始类型和函数作为 props 使得组件的 API 更接近于 HTML(5) 原生元素。
 * 其它开发者更好的理解每一个 prop 的含义、作用。
 * 传递过于复杂的对象使得我们不能够清楚的知道哪些属性或方法被自定义组件使用，这使得代码难以重构和维护。


## How？

组件的每一个属性单独使用一个 props，并且使用函数或是原始类型的值。

<!-- 推荐 -->
<range-slider
  :values="[10, 20]"
  min="0"
  max="100"
  step="5"
  :on-slide="updateInputs"
  :on-end="updateResults">
</range-slider>

<!-- 避免 -->
<range-slider :config="complexConfigObject"></range-slider>


↑ 回到目录


## 验证组件的 props

在 Vue.js 中，组件的 props 即 API，一个稳定并可预测的 API 会使得你的组件更容易被其他开发者使用。

组件 props 通过自定义标签的属性来传递。属性的值可以是 Vue.js 字符串(:attr="value" 或 v-bind:attr="value")或是不传。你需要保证组件的 props 能应对不同的情况。


## Why？

验证组件 props 可以保证你的组件永远是可用的（防御性编程）。即使其他开发者并未按照你预想的方法使用时也不会出错。


## How？

 * 提供默认值。
 * 使用 type 属性校验类型。
 * 使用 props 之前先检查该 prop 是否存在。

<template>
  <input type="range" v-model="value" :max="max" :min="min">
</template>
<script type="text/javascript">
  export default {
    props: {
      max: {
        type: Number, // 这里添加了数字类型的校验
        default() { return 10; },
      },
      min: {
        type: Number,
        default() { return 0; },
      },
      value: {
        type: Number,
        default() { return 4; },
      },
    },
  };
</script>


↑ 回到目录


## 将 this 赋值给 component 变量

在 Vue.js 组件上下文中，this指向了组件实例。因此当你切换到了不同的上下文时，要确保 this 指向一个可用的 component 变量。

换句话说，如果你正在使用 ES6 的话，就不要再编写 var self = this; 这样的代码了，您可以安全地使用 Vue 组件。


## Why？

 * 使用 ES6，就不再需要将 this 保存到一个变量中了。
 * 一般来说，当你使用箭头函数时，会保留 this 的作用域。（译者注：箭头函数没有它自己的 this 值，箭头函数内的 this 值继承自外围作用域。）
 * 如果你没有使用 ES6，当然也就不会使用 箭头函数 啦，那你必须将 “this” 保存到到某个变量中。这是唯一的例外。


## How？

<script type="text/javascript">
export default {
  methods: {
    hello() {
      return 'hello';
    },
    printHello() {
      console.log(this.hello());
    },
  },
};
</script>

<!-- 避免 -->
<script type="text/javascript">
export default {
  methods: {
    hello() {
      return 'hello';
    },
    printHello() {
      const self = this; // 没有必要
      console.log(self.hello());
    },
  },
};
</script>


↑ 回到目录


## 组件结构化

按照一定的结构组织，使得组件便于理解。


## Why？

 * 导出一个清晰、组织有序的组件，使得代码易于阅读和理解。同时也便于标准化。
 * 按首字母排序 properties、data、computed、watches 和 methods 使得这些对象内的属性便于查找。
 * 合理组织，使得组件易于阅读。（name; extends; props, data 和 computed; components; watch 和 methods; lifecycle methods 等）。
 * 使用 name 属性。借助于 vue devtools 可以让你更方便的测试。
 * 合理的 CSS 结构，如 BEM 或 rscss - 详情？。
 * 使用单文件 .vue 文件格式来组件代码。


## How？

组件结构化

<template lang="html">
  <div class="Ranger__Wrapper">
    <!-- ... -->
  </div>
</template>

<script type="text/javascript">
  export default {
    // 不要忘记了 name 属性
    name: 'RangeSlider',
    // 组合其它组件
    extends: {},
    // 组件属性、变量
    props: {
      bar: {}, // 按字母顺序
      foo: {},
      fooBar: {},
    },
    // 变量
    data() {},
    computed: {},
    // 使用其它组件
    components: {},
    // 方法
    watch: {},
    methods: {},
    // 生命周期函数
    beforeCreate() {},
    mounted() {},
  };
</script>

<style scoped>
  .Ranger__Wrapper { /* ... */ }
</style>


↑ 回到目录


## 组件事件命名

Vue.js 提供的处理函数和表达式都是绑定在 ViewModel 上的，组件的每一个事件都应该按照一个好的命名规范来，这样可以避免不少的开发问题，具体可见如下 为什么。


## Why？

 * 开发者可以随意给事件命名，即使是原生事件的名字，这样会带来迷惑性。
 * 过于宽松的事件命名可能与 DOM 模板不兼容。


## How？

 * 事件名也使用连字符命名。
 * 一个事件的名字对应组件外的一组意义操作，如：upload-success、upload-error 以及 dropzone-upload-success、dropzone-upload-error （如果需要前缀的话）。
 * 事件命名应该以动词（如 client-api-load） 或是 形容词（如 drive-upload-success）结尾。（出处）

↑ 回到目录


## 避免 this.$parent

Vue.js 支持组件嵌套，并且子组件可访问父组件的上下文。访问组件之外的上下文违反了基于模块开发的第一原则。因此你应该尽量避免使用 this.$parent。


## Why？

 * 组件必须相互保持独立，Vue 组件也是。如果组件需要访问其父层的上下文就违反了该原则。
 * 如果一个组件需要访问其父组件的上下文，那么该组件将不能在其它上下文中复用。


## How？

 * 通过 props 将值传递给子组件。
 * 通过 props 传递回调函数给子组件来达到调用父组件方法的目的。
 * 通过在子组件触发事件来通知父组件。

↑ 回到目录


## 谨慎使用 this.$refs

Vue.js 支持通过 ref 属性来访问其它组件和 HTML 元素。并通过 this.$refs 可以得到组件或 HTML 元素的上下文。在大多数情况下，通过 this.$refs来访问其它组件的上下文是可以避免的。在使用的的时候你需要注意避免调用了不恰当的组件 API，所以应该尽量避免使用 this.$refs。


## Why？

 * 组件必须是保持独立的，如果一个组件的 API 不能够提供所需的功能，那么这个组件在设计、实现上是有问题的。
 * 组件的属性和事件必须足够的给大多数的组件使用。


## How？

 * 提供良好的组件 API。
 * 总是关注于组件本身的目的。
 * 拒绝定制代码。如果你在一个通用的组件内部编写特定需求的代码，那么代表这个组件的 API 不够通用，或者你可能需要一个新的组件来应对该需求。
 * 检查所有的 props 是否有缺失的，如果有提一个 issue 或是完善这个组件。
 * 检查所有的事件。子组件向父组件通信一般是通过事件来实现的，但是大多数的开发者更多的关注于 props 从忽视了这点。
 * Props向下传递，事件向上传递！。以此为目标升级你的组件，提供良好的 API 和 独立性。
 * 当遇到 props 和 events 难以实现的功能时，通过 this.$refs来实现。
 * 当需要操作 DOM 无法通过指令来做的时候可使用 this.$ref 而不是 JQuery、document.getElement*、document.queryElement。

<!-- 推荐，并未使用 this.$refs -->
<range :max="max"
  :min="min"
  @current-value="currentValue"
  :step="1"></range>


<!-- 使用 this.$refs 的适用情况-->
<modal ref="basicModal">
  <h4>Basic Modal</h4>
  <button class="primary" @click="$refs.basicModal.hide()">Close</button>
</modal>
<button @click="$refs.basicModal.open()">Open modal</button>

<!-- Modal component -->
<template>
  <div v-show="active">
    <!-- ... -->
  </div>
</template>

<script>
  export default {
    // ...
    data() {
      return {
        active: false,
      };
    },
    methods: {
      open() {
        this.active = true;
      },
      hide() {
        this.active = false;
      },
    },
    // ...
  };
</script>


<!-- 如果可通过 emited 来做则避免通过 this.$refs 直接访问 -->
<template>
  <range :max="max"
    :min="min"
    ref="range"
    :step="1"></range>
</template>

<script>
  export default {
    // ...
    methods: {
      getRangeCurrentValue() {
        return this.$refs.range.currentValue;
      },
    },
    // ...
  };
</script>


↑ 回到目录


## 使用组件名作为样式作用域空间

Vue.js 的组件是自定义元素，这非常适合用来作为样式的根作用域空间。可以将组件名作为 CSS 类的命名空间。


## Why？

 * 给样式加上作用域空间可以避免组件样式影响外部的样式。
 * 保持模块名、目录名、样式根作用域名一样，可以很好的将其关联起来，便于开发者理解。


## How？

使用组件名作为样式命名的前缀，可基于 BEM 或 OOCSS 范式。同时给 style 标签加上 scoped 属性。加上 scoped 属性编译后会给组件的 class 自动加上唯一的前缀从而避免样式的冲突。

<style scoped>
  /* 推荐 */
  .MyExample { }
  .MyExample li { }
  .MyExample__item { }

  /* 避免 */
  .My-Example { } /* 没有用组件名或模块名限制作用域, 不符合 BEM 规范 */
</style>


↑ 回到目录


## 提供组件 API 文档

使用 Vue.js 组件的过程中会创建 Vue 组件实例，这个实例是通过自定义属性配置的。为了便于其他开发者使用该组件，对于这些自定义属性即组件API应该在 README.md 文件中进行说明。


## Why？

 * 良好的文档可以让开发者比较容易的对组件有一个整体的认识，而不用去阅读组件的源码，也更方便开发者使用。
 * 组件配置属性即组件的 API，对于组件的用户来说他们更感兴趣的是 API 而不是实现原理。
 * 正式的文档会告诉开发者组件 API 变更以及向后的兼容性情况。
 * README.md 是标准的我们应该首先阅读的文档文件。代码托管网站（GitHub、Bitbucket、Gitlab 等）会默认在仓库中展示该文件作为仓库的介绍。


## How？

在模块目录中添加 README.md 文件：

range-slider/
├── range-slider.vue
├── range-slider.less
└── README.md


在 README 文件中说明模块的功能以及使用场景。对于 vue 组件来说，比较有用的描述是组件的自定义属性即 API 的描述介绍。


## Range slider


## 功能

range slider 组件可通过拖动的方式来设置一个给定范围内的数值。

该模块使用 noUiSlider 来实现跨浏览器和 touch 功能的支持。


## 如何使用

<range-slider> 支持如下的自定义属性：

ATTRIBUTE   TYPE                DESCRIPTION
min         Number              可拖动的最小值.
max         Number              可拖动的最大值.
values      Number[] optional   包含最大值和最小值的数组. 如. values="[10, 20]". Defaults to [opts.min,
                                opts.max].
step        Number optional     增加减小的数值单位，默认为 1.
on-slide    Function optional   用户拖动开始按钮或者结束按钮时的回调函数，函数接受 (values, HANDLE) 格式的参数。 如：
                                on-slide={ updateInputs }, component.updateInputs = (values,
                                HANDLE) => { const value = values[HANDLE]; }.
on-end      Function optional   当用户停止拖动时触发的回调函数，函数接受 (values, HANDLE) 格式的参数。

如需要自定义 slider 的样式可参考 noUiSlider 文档

↑ 回到目录


## 提供组件 demo

添加 index.html 文件作为组件的 demo 示例，并提供不同配置情况的效果，说明组件是如何使用的。


## Why？

 * demo 可以说明组件是独立可使用的。
 * demo 可以让开发者预览组件的功能效果。
 * demo 可以展示组件各种配置参数下的功能。

↑ 回到目录


## 对组件文件进行代码校验

代码校验可以保持代码的统一性以及追踪语法错误。.vue 文件可以通过使用 eslint-plugin-html插件来校验代码。你可以通过 vue-cli 来开始你的项目，vue-cli 默认会开启代码校验功能。


## Why？

 * 保证所有的开发者使用同样的编码规范。
 * 更早的感知到语法错误。


## How？

为了校验工具能够校验 *.vue文件，你需要将代码编写在 <script>标签中，并使组件表达式简单化，因为校验工具无法理解行内表达式，配置校验工具可以访问全局变量 vue 和组件的 props。

## ESLint

ESLint 需要通过 ESLint HTML 插件来抽取组件中的代码。

通过 .eslintrc 文件来配置 ESlint，这样 IDE 可以更好的理解校验配置项：

{
  "extends": "eslint:recommended",
  "plugins": ["html"],
  "env": {
    "browser": true
  },
  "globals": {
    "opts": true,
    "vue": true
  }
}


运行 ESLint

eslint src/**/*.vue


## JSHint

JSHint 可以解析 HTML（使用 --extra-ext命令参数）和抽取代码（使用 --extract=auto命令参数）。

通过 .jshintrc 文件来配置 ESlint，这样 IDE 可以更好的理解校验配置项。

{
  "browser": true,
  "predef": ["opts", "vue"]
}


运行 JSHint

jshint --config modules/.jshintrc --extra-ext=html --extract=auto modules/


注：JSHint 不接受 vue 扩展名的文件，只支持 html。


## 只在需要时创建组件


## Why？

Vue.js 是一个基于组件的框架。如果你不知道何时创建组件可能会导致以下问题：

 * 如果组件太大, 可能很难重用和维护;
 * 如果组件太小，你的项目就会（因为深层次的嵌套而）被淹没，也更难使组件间通信;


## How?

 * 始终记住为你的项目需求构建你的组件，但是你也应该尝试想到它们能够从中脱颖而出（独立于项目之外）。如果它们能够在你项目之外工作，就像一个库那样，就会使得它们更加健壮和一致。
 * 尽可能早地构建你的组件总是更好的，因为这样使得你可以在一个已经存在和稳定的组件上构建你的组件间通信（props & events）。


## 规则

 * 首先，尽可能早地尝试构建出诸如模态框、提示框、工具条、菜单、头部等这些明显的（通用型）组件。总之，你知道的这些组件以后一定会在当前页面或者是全局范围内需要。
 * 第二，在每一个新的开发项目中，对于一整个页面或者其中的一部分，在进行开发前先尝试思考一下。如果你认为它有一部分应该是一个组件，那么就创建它吧。
 * 最后，如果你不确定，那就不要。避免那些“以后可能会有用”的组件污染你的项目。它们可能会永远的只是（静静地）待在那里，这一点也不聪明。注意，一旦你意识到应该这么做，最好是就把它打破，以避免与项目的其他部分构成兼容性和复杂性。 ↑ 回到目录

----------------------------------------

官网规范参见

编撰人：yinyanting




快速跳转



 * vue编码规范
   * 目标
   * 准则
   * 基于模块开发
     * How？
   * Vue 组件命名
     * Why？
     * 如何做？
   * 组件表达式简单化
     * Why？
     * How？
     * 组件 props 原子化
     * Why？
     * How？
   * 验证组件的 props
     * Why？
     * How？
   * 将 this 赋值给 component 变量
     * Why？
     * How？
   * 组件结构化
     * Why？
     * How？
   * 组件事件命名
     * Why？
     * How？
   * 避免 this.$parent
     * Why？
     * How？
   * 谨慎使用 this.$refs
     * Why？
     * How？
   * 使用组件名作为样式作用域空间
     * Why？
     * How？
   * 提供组件 API 文档
   * Why？
     * How？
 * Range slider
   * 功能
   * 如何使用
   * 提供组件 demo
     * Why？
   * 对组件文件进行代码校验
     * Why？
     * How？
       * ESLint
       * JSHint
   * 只在需要时创建组件
     * Why？
     * How?
     * 规则



分享链接分享链接

## 118. Javascript规范

> 原始路径：`/94/355/361/364/365/370.html`  
> 相对路径：`94/355/361/364/365/370.md`  
> JS Chunk：`app.371b709c.js`

## Javascript规范


## 1.分号

## 强制语句必须都有分号结尾，除了for, function, if, switch, try, while


## 2. 缩进

## 强制 使用空格而非Tab来缩进, 一层缩进=4个空格


## 3. 命名

## 强制 常量使用大写字符, 下划线连接

var SECONDS_IN_A_MINUTE = 60;
obj.TEXT_WARNNING = '警告';


## 强制 标准变量: 驼峰

var myCount = 1;


## 强制 构造函数: 驼峰且大写第一个字母

function Point(x, y) {
    this.x = x;
    this.y = y;
}


## 建议 私有方法: 驼峰且加_前缀

function MyClass() {
    var _privateNum;
    this.getNum = function() {
        return _privateNum;
    };
}

// 虽然不建议这么写一个对象(建议用闭包来写)
// 但如果真这么写了, 请把意图上不想暴露的变量, 用_开头
var myCounter = {
    _count: 1,
    get: function() {
        return this._count;
    }
};


## 建议 对布尔型的变量, 命名时加is,has,can前缀

## 强制 不要使用让人糊涂的命名

var isNotError;
var isNotClosed;


## 强制 当出现以下字符时,统一拼写

var iOSVersion; //iOS
var AndroidVersion; //Android
var classID,teacherID,mID; //ID
var jumpURL; //URL
var normalHTML, isXML; //HTML
var HTTPHeader; //HTTP
//... 待补充


## 建议 字符串常量或字面量使用时, 使用单引号而非双引号

var str = '<span class="info">';
str += 'some infomation</span>';



## 4. 代码风格

## 强制 即使是单行,也需要加花括号

正确


//更建议换行写
if (isUndead) {
    grabFire();
}
//一定要一行,也必须这样
if (isUndead) { grabFire(); }


错误


if (isUndead) grabFire();


## 强制操作符前后要有空格分隔

//运算符
var a = 1 + 2;
var thaco = hit + adjustment - randomFactor;

//三元操作符
var num = val ? foo() : bar();
var fn = JSON.parse ? JSON.parse : function() {
    //...
};


## 强制对象属性的冒号前无空格,后跟一个空格

var myObject = {
    propA: 1
};


## 建议逗号位置: Last comma

建议 (last comma)

var foo = 1,
    bar = 2,
    baz = 3;

var obj = {
    foo: 1,
    bar: 2,
    baz: 3
};


不推荐 (first comma)

var foo = 1
  , bar = 2
  , baz = 3;

var obj = {
    foo: 1
  , bar: 2
  , baz: 3
};


## 注意一定不要多写逗号了

错误


var list = [
    {n: 1},
    {n: 2}, //<----- 会导致IE报错, GCC默认参数压缩也会报错
];


## 建议function的参数括号: 前后都加一个空格, 若非匿名函数, 则名字和括号之间不再需要空格

//匿名函数, function和括号间有空格, 括号和花括号间也有空格
var fn = function (param) {
    //...
}
//带名字的函数, function和括号间有空格, 但插入的名字和括号间就无需再加空格了
function foo() {
    return "bar";
}


## 建议条件判断括号: 前后都加一个空格

推荐


if (true) {
    //...
}

while (true) {
    //...
}

switch (v) {
    //...
}


不推荐


if(true) {
    //...
}

while(true) {
    //...
}

switch(v) {
    //...
}


## 建议括号紧挨两端处不要空格, 中间有逗号, 逗号后加空格

推荐


function fn(arg1, arg2) {
    //...
}
var fn = function (arg) {
    //...
}
if (true) {
    //...
} else {
    //...
}
var arr = [1, 2, 3];


不推荐


function fn( arg1, arg2 ) {
    //...
}
var fn = function ( arg ) {
    //...
}
if ( true ) {
    //...
}
else {
    //...
}
var arr = [ 1, 2, 3 ];


## 建议 if...else 写法

if (condition1) {
    doSomething1();
} else if (condition2) {
    doSomething2();
} else {
    doSomethingElse();
}


## 建议 switch...case 写法

switch (condition) {
    case "first":
        // code
        break;

    case "third":
        // code
        break;

    default:
        // code
        break;
}


switch (condition) {
    case "first":
    case "second": //上一行不用加fall though: 两个case紧挨, jshint不会报错
        // code
        break;

    case "third":
        // code
        /* falls through */
    case "fourth": //上一行必须加, 否则jshint会报错
        // code
        break;

    default:
        // code
        break;
}


## 强制函数参数过多时的排版: 两层缩进

正确


var localMonsterRumors = getLocalGossip(inkeeper,
        localInn, numberOfClerics, pintsOfAlePurchased,
        charismaAjustment);


错误


var localMonsterRumors = getLocalGossip(inkeeper,
                                          localInn,
                                          numberOfClerics,
                                          pintsOfAlePurchased,
                                          charismaAjustment);


## 建议采用临时变量来提高复杂判断或字符串拼接的可读性

错误


if ( (conditionAA && conditionAB) || (conditionBA && conditionBB) ){
    //...
}

var elem = document.getElementById('charClass-' + charClass +
      + '_combatStats-' + armorClass + '-' + toHitBonus);


正确


var conditionA = conditionAA && conditionAB;
var conditionB = conditionBA && conditionBB;
if (conditionA || conditionB) {
    //...
}

var strChar = 'charClass-' + charClass;
var strCombat = 'combatStatus-' + armorClass + '-' + toHitBonus;
var elem = document.getElementById(strChar + '_' + strCombat);


## 建议逻辑块 之间使用空行


## 5. 杂项

## 建议尽量使用标准方法而不是用非标准方法

例: 优先用string.charAt(3) 而不用 string[3]

## 强制不要修改内置对象的原型

主要是为了不污染原型从而对外部造成不好的影响 如Array.prototype,Object.prototype

## 强制避免 == != 的使用， 用严格比较条件 === !==


## for...in

## 建议对数组遍历时, 用下标的for循环而非for...in

## 注意使用for...in时要注意利用hasOwnProperty排除掉可能的原型污染干扰


## with,eval

## 强制如非特殊情况, 不允许使用with,eval


## 多行字符串

## 强制不要使用转义字符''的方式来写多行字符串

## 强制也不要使用function内注释再toString的hack来定义和使用多行字符串


## 保留字

## 强制对象的属性如果是保留字, 请务必使用引号定义,方括号引号引用

正确


var example = {
    "new": function () {}
};

var fn = example['new'];


错误


var example = {
    new: function () {}
};

var fn = example.new;



## 注释

## 单行注释优先

## 优先使用单行注释(即使是需要写多行), 除了以下情况

## 优先使用多行注释的情况

 * fileoverview / constructors
 * public method

## 多行注释

/**
 * this method is ...
 * @param {Object} ...
 * @return {Object} ...
 */



## //todo: 大块注释怎么写


## //todo: switch规避jshint的一种特殊情形

编撰人：yinyanting


快速跳转



 * Javascript规范
   * 1.分号
     * 强制语句必须都有分号结尾，除了for, function, if, switch, try, while
   * 2. 缩进
     * 强制 使用空格而非Tab来缩进, 一层缩进=4个空格
   * 3. 命名
     * 强制 常量使用大写字符, 下划线连接
     * 强制 标准变量: 驼峰
     * 强制 构造函数: 驼峰且大写第一个字母
     * 建议 私有方法: 驼峰且加_前缀
     * 建议 对布尔型的变量, 命名时加is,has,can前缀
     * 强制 不要使用让人糊涂的命名
     * 强制 当出现以下字符时,统一拼写
     * 建议 字符串常量或字面量使用时, 使用单引号而非双引号
   * 4. 代码风格
     * 强制 即使是单行,也需要加花括号
     * 强制操作符前后要有空格分隔
     * 强制对象属性的冒号前无空格,后跟一个空格
     * 建议逗号位置: Last comma
     * 注意一定不要多写逗号了
     * 建议function的参数括号: 前后都加一个空格, 若非匿名函数, 则名字和括号之间不再需要空格
     * 建议条件判断括号: 前后都加一个空格
     * 建议括号紧挨两端处不要空格, 中间有逗号, 逗号后加空格
     * 建议 if...else 写法
     * 建议 switch...case 写法
     * 强制函数参数过多时的排版: 两层缩进
     * 建议采用临时变量来提高复杂判断或字符串拼接的可读性
     * 建议逻辑块 之间使用空行
   * 5. 杂项
     * 建议尽量使用标准方法而不是用非标准方法
     * 强制不要修改内置对象的原型
     * 强制避免 == != 的使用， 用严格比较条件 === !==
     * for...in
       * 建议对数组遍历时, 用下标的for循环而非for...in
       * 注意使用for...in时要注意利用hasOwnProperty排除掉可能的原型污染干扰
     * with,eval
       * 强制如非特殊情况, 不允许使用with,eval
     * 多行字符串
       * 强制不要使用转义字符'\'的方式来写多行字符串
       * 强制也不要使用function内注释再toString的hack来定义和使用多行字符串
   * 保留字
     * 强制对象的属性如果是保留字, 请务必使用引号定义,方括号引号引用
   * 注释
     * 单行注释优先
     * 优先使用单行注释(即使是需要写多行), 除了以下情况
     * 优先使用多行注释的情况
     * 多行注释
   * //todo: 大块注释怎么写
   * //todo: switch规避jshint的一种特殊情形



分享链接分享链接

## 119. 后端开发规范

> 原始路径：`/94/355/361/364/371.html`  
> 相对路径：`94/355/361/364/371.md`  
> JS Chunk：`app.371b709c.js`

## 后端开发规范

//待补充



## Java开发规范


## 命名

**【规范】**类名使用UpperCamelCase风格，必须遵从驼峰形式，但以下情形例外： （ 领域模型的相关命名 ）DO / BO / DTO / VO 等。

正例： MarcoPolo / UserDO / XmlService / TcpUdpDeal / TaPromotion

反例： macroPolo / UserDo / XMLService / TCPUDPDeal / TAPromotion

**【规范】**方法名、参数名、成员变量、局部变量都统一使用lowerCamelCase风格，必须遵从驼峰形式。

正例： localValue / getHttpMessage() / inputUserId

**【规范】**常量命名全部大写，单词间用下划线隔开，力求语义表达完整清楚，不要嫌名字长。

**【规范】**抽象类命名使用 Abstract 或 Base 开头 ； 异常类命名使用 Exception 结尾 ； 测试类命名以它要测试的类的名称开始，以 Test 结尾。枚举类名建议带上 Enum 后缀，枚举成员名称需要全大写，单词间用下划线隔开。

**【规范】**POJO 类中布尔类型的变量，都不要加 is ，否则部分框架解析会引起序列化错误。

**【规范】**各层命名规约：

A) Service / DAO 层方法命名规约

1 ） 获取单个对象的方法用 get 做前缀。

2 ） 获取多个对象的方法用 list 做前缀（习惯：getXXXList）。

3 ） 获取统计值的方法用 count 做前缀。

4 ） 插入的方法用 save（ 推荐 ） 或 insert 做前缀。

5 ） 删除的方法用 remove（ 推荐 ） 或 delete 做前缀。

6 ） 修改的方法用 update 做前缀(或modify)。

B) 领域模型命名规约

1 ） 数据对象： xxxDO ， xxx 即为数据表名。

2 ） 数据传输对象： xxxDTO ， xxx 为业务领域相关的名称。

3 ） 展示对象： xxxVO ， xxx 一般为网页名称。

4 ） POJO 是 DO / DTO / BO / VO 的统称，禁止命名成 xxxPOJO 。


## 常量

**【规范】**不允许任何魔法值（ 即未经定义的常量 ） 直接出现在代码中。

反例： String key =” Id # taobao _”+ tradeId；

cache . put(key , value);


## 格式规约

**【风格】**单行太长需换行

**【风格】**方法体内的执行语句组、变量的定义语句组、不同的业务逻辑之间或者不同的语义之间插入一个空行。相同业务逻辑和语义之间不需要插入空行。


## OOP规约

**【效率】**避免通过一个类的对象引用访问此类的静态变量或静态方法，无谓增加编译器解析成本，直接用类名来访问即可。

**【规范】**所有的覆写方法，必须加@ Override 注解。

**【规范】**对外暴露的接口签名，原则上不允许修改方法签名，避免对接口调用方产生影响。接口过时必须加@Deprecated 注解，并清晰地说明采用的新接口或者新服务是什么。

**【规范】**Object 的 equals 方法容易抛空指针异常，应使用常量或确定有值的对象来调用equals。

正例： ” test ” .equals(object);

反例： object.equals( ” test ” );

**【规范】**所有的相同类型的包装类对象之间值的比较，全部使用 equals 方法比较。(注意空指针)

说明：对于 Integer var =?在-128 至 127 之间的赋值， Integer 对象是在IntegerCache . cache 产生，会复用已有对象，这个区间内的 Integer 值可以直接使用==进行判断，但是这个区间之外的所有数据，都会在堆上产生，并不会复用已有对象，这是一个大坑，推荐使用 equals 方法进行判断。

**【规范】**关于基本数据类型与包装数据类型的使用标准如下：

1 ） 所有的 POJO 类属性必须使用包装数据类型。

2 ） RPC 方法的返回值和参数必须使用包装数据类型。

3 ） 所有的局部变量【推荐】使用基本数据类型。

**【强制】**序列化类新增属性时，请不要修改 serialVersionUID 字段，避免反序列失败 ； 如果完全不兼容升级，避免反序列化混乱，那么请修改 serialVersionUID 值。

**【规范】**构造方法里面禁止加入任何业务逻辑，如果有初始化逻辑，请放在 init 方法中。

**【规范】**使用索引访问用 String 的 split 方法得到的数组时，需做最后一个分隔符后有无内容的检查，否则会有抛 IndexOutOfBoundsException 的风险。

说明：

String str = “a,b,c,,”;

String[] ary = str.split(“,”);

//预期大于 3，结果是 3

System.out.println(ary.length);

**【规范】**当一个类有多个构造方法，或者多个同名方法，这些方法应该按顺序放置在一起，便于阅读。

**【风格】**类内方法定义顺序依次是：公有方法或保护方法 > 私有方法 > getter / setter方法。

**【效率】**final 可提高程序响应效率，声明成 final 的情况：

1 ） 不需要重新赋值的变量，包括类属性、局部变量。

2 ） 对象参数前加 final ，表示不允许修改引用的指向。

3 ） 类方法确定不允许被重写。

4 ）例子：final boolean existed = (file.open(fileName, “w”) != null) && (…) || (…);


## 集合处理

**【强制】**关于 hashCode 和 equals 的处理，遵循如下规则：

1） 只要重写 equals ，就必须重写 hashCode 。

2） 因为 Set 存储的是不重复的对象，依据 hashCode 和 equals 进行判断，所以 Set 存储的对象必须重写这两个方法。

3） 如果自定义对象做为 Map 的键，那么必须重写 hashCode 和 equals 。

**【强制】**不要在 foreach 循环里进行元素的 remove / add 操作。 remove 元素请使用 Iterator方式，如果并发操作，需要对 Iterator 对象加锁。

反例：

List a = new ArrayList();

a.add(“1”);

a.add(“2”);

for (String temp : a) {

if(“1”.equals(temp)){

a.remove(temp);

}

}

说明：以上代码的执行结果肯定会出乎大家的意料，那么试一下把“1”换成“2”，会是同样的结果吗？(java.util.ConcurrentModificationException)

正例：

Iterator it = a.iterator();

while(it.hasNext()){

String temp = it.next();

if(删除元素的条件){

it.remove();

}

}

**【规范】**集合初始化时，尽量指定集合初始值大小。

说明： ArrayList 尽量使用 ArrayList(int initialCapacity) 初始化。

**【规范】**使用 entrySet 遍历 Map 类集合 KV，而不是 keySet 方式进行遍历。

说明:keySet 其实是遍历了 2 次，一次是转为 Iterator 对象，另一次是从 hashMap 中取出 key 所对应的 value。而 entrySet 只是遍历了一次就把 key 和 value 都放到了 entry 中，效 率更高。如果是 JDK8，使用 Map.foreach 方法。

Map map = new HashMap();

map.put(“1”, “@@”);

map.put(“2”, “##”);

/**

* JDK8推荐使用

*/

map.forEach((K, V) -> {

System.out.println(“Key : ” + K);

System.out.println(“Value : ” + V);

});

/**

* foreach推荐使用

*/

for (Map.Entry entry : map.entrySet()) {

System.out.println(“Key : ” + entry.getKey());

System.out.println(“Value : ” + entry.getValue());

}

/**

* 不推荐使用

*/

for (String key : map.keySet()) {

System.out.println(“Key : ” + key);

System.out.println(“Value : ” + map.get(key));

}

**【强制】**高度注意 Map 类集合 K/V 能不能存储 null 值的情况，如下表格:

集合类KeyValueSuper说明Hashtable不允许为 null不允许为 nullDictionary线程安全ConcurrentHashMap不允许为 null不允许为 nullAbstractMap分段锁技术TreeMap不允许为 null允许为 nullAbstractMap线程不安全HashMap允许为 null允许为 nullAbstractMap线程不安全


## 并发处理

**【规范】**获取单例对象需要保证线程安全，其中的方法也要保证线程安全。

说明:资源驱动类、工具类、单例工厂类都需要注意。

**【规范】**创建线程或线程池时请指定有意义的线程名称，方便出错时回溯。

正例:

public class TimerTaskThread extends Thread { public TimerTaskThread(){

super.setName(“TimerTaskThread”); … }

**【规范】**线程资源必须通过线程池提供，不允许在应用中自行显式创建线程。

说明:使用线程池的好处是减少在创建和销毁线程上所花的时间以及系统资源的开销，解决资 源不足的问题。如果不使用线程池，有可能造成系统创建大量同类线程而导致消耗完内存或者 “过度切换”的问题。

**【规范】**线程池不允许使用 Executors 去创建，而是通过 ThreadPoolExecutor 的方式，这样 的处理方式让写的同学更加明确线程池的运行规则，规避资源耗尽的风险。 说明:Executors 返回的线程池对象的弊端如下:

1)FixedThreadPool 和 SingleThreadPool:

允许的请求队列长度为 Integer.MAX_VALUE，可能会堆积大量的请求，从而导致 OOM。

2)CachedThreadPool 和 ScheduledThreadPool:

允许的创建线程数量为 Integer.MAX_VALUE，可能会创建大量的线程，从而导致 OOM。

**【效率】**高并发时，同步调用应该去考量锁的性能损耗。能用无锁数据结构，就不要用锁;能 锁区块，就不要锁整个方法体;能用对象锁，就不要用类锁。

**【强制】**对多个资源、数据库表、对象同时加锁时，需要保持一致的加锁顺序，否则可能会造 成死锁。

说明:线程一需要对表 A、B、C 依次全部加锁后才可以进行更新操作，那么线程二的加锁顺序 也必须是 A、B、C，否则可能出现死锁。

**【规范】**并发修改同一记录时，避免更新丢失，要么在应用层加锁，要么在缓存加锁，要么在 数据库层使用乐观锁，使用 version 作为更新依据。

说明:如果每次访问冲突概率小于 20%，推荐使用乐观锁，否则使用悲观锁。乐观锁的重试次 数不得小于 3 次。

**【规范】**多线程并行处理定时任务时，Timer运行多个 TimeTask 时，只要其中之一没有捕获 抛出的异常，其它任务便会自动终止运行，使用ScheduledExecutorService则没有这个问题。

**【规范】**HashMap 在容量不够进行 resize 时由于高并发可能出现死链，导致 CPU 飙升，在 开发过程中注意规避此风险。


## 控制语句

**【规范】**在一个 switch 块内，每个 case 要么通过 break/return 等来终止，要么注释说明程 序将继续执行到哪一个 case 为止;在一个 switch 块内，都必须包含一个 default 语句并且 放在最后，即使它什么代码也没有。

**【规范】**在 if/else/for/while/do 语句中必须使用大括号，即使只有一行代码，避免使用 下面的形式:if (condition) statements;

**【规范】**推荐尽量少用 else， if-else 的方式可以改写成:

if(condition){

…

return obj; }

// 接着写 else 的业务逻辑代码;

说明:如果非得使用if()…else if()…else…方式表达逻辑，【强制】请勿超过3层，

超过请使用状态设计模式 或者 卫语句。

卫语句示例：

public void today() {
    if (isBusy()) {
        System.out.println(“change time.”); 
        return;
    }
    if (isFree()) {
        System.out.println(“go to travel.”);
        return; 
    }
    System.out.println(“stay at home to learn Alibaba Java Coding Guidelines.”);
    return; 
}


**【规范】**除常用方法(如 getXxx/isXxx)等外，不要在条件判断中执行其它复杂的语句，将复 杂逻辑判断的结果赋值给一个有意义的布尔变量名，以提高可读性。

说明:很多 if 语句内的逻辑相当复杂，阅读者需要分析条件表达式的最终结果，才能明确什么 样的条件执行什么样的语句，那么，如果阅读者分析逻辑表达式错误呢?

正例:

//伪代码如下

boolean existed = (file.open(fileName, “w”) != null) && (…) || (…); if (existed) {

… }

反例:

if ((file.open(fileName, “w”) != null) && (…) || (…)) { …

}

**【规范】**方法中需要进行参数校验的场景:

 1. 调用频次低的方法。
 2. 执行时间开销很大的方法，参数校验时间几乎可以忽略不计，但如果因为参数错误导致

中间执行回退，或者错误，那得不偿失。

 1. 需要极高稳定性和可用性的方法。
 2. 对外提供的开放接口，不管是RPC/API/HTTP接口。
 3. 敏感权限入口。

**【规范】**方法中不需要参数校验的场景:

 1. 极有可能被循环调用的方法，不建议对参数进行校验。但在方法说明里必须注明外部参

数检查。

2)底层的方法调用频度都比较高，一般不校验。毕竟是像纯净水过滤的最后一道，参数错误不太可能到底层才会暴露问题。一般 DAO 层与 Service 层都在同一个应用中，部署在同一 台服务器中，所以 DAO 的参数校验，可以省略。

 1. 被声明成private只会被自己代码所调用的方法，如果能够确定调用方法的代码传入参 数已经做过检查或者肯定不会有问题，此时可以不校验参数。


## 注释规约

**【规范】**类、类属性、类方法的注释必须使用 Javadoc 规范，使用/**内容*/格式，不得使用 //xxx 方式。

**【规范】**所有的抽象方法(包括接口中的方法)必须要用 Javadoc 注释、除了返回值、参数、 异常说明外，还必须指出该方法做什么事情，实现什么功能。

说明:对子类的实现要求，或者调用注意事项，请一并说明。

**【风格】**方法内部单行注释，在被注释语句上方另起一行，使用//注释。方法内部多行注释使用/* */注释，注意与代码对齐。

**【规范】**所有的枚举类型字段必须要有注释，说明每个数据项的用途。

**【规范】**代码修改的同时，注释也要进行相应的修改，尤其是参数、返回值、异常、核心逻辑 等的修改。

**【规范】**注释掉的代码尽量要配合说明，而不是简单的注释掉。

说明:代码被注释掉有两种可能性:

1)后续会恢复此段代码逻辑。

2)永久不用。前者如果没 有备注信息，难以知晓注释动机。

后者建议直接删掉(代码仓库保存了历史代码)。

**【风格】**特殊注释标记，请注明标记人与标记时间。注意及时处理这些标记，通过标记扫描， 经常清理此类标记。线上故障有时候就是来源于这些标记处的代码。

1)待办事宜(TODO)😦 标记人，标记时间，[预计处理时间]) 表示需要实现，但目前还未实现的功能。这实际上是一个 Javadoc 的标签，目前的 Javadoc

还没有实现，但已经被广泛使用。只能应用于类，接口和方法(因为它是一个 Javadoc 标签)。

2)错误，不能工作(FIXME):(标记人，标记时间，[预计处理时间])

在注释中用 FIXME 标记某代码是错误的，而且不能工作，需要及时纠正的情况。


## 异常

**【规范】**异常不要用来做流程控制，条件控制，因为异常的处理效率比条件分支低。

**【规范】**对大段代码进行 try-catch，这是不负责任的表现。catch 时请分清稳定代码和非稳 定代码，稳定代码指的是无论如何不会出错的代码。对于非稳定代码的 catch 尽可能进行区分 异常类型，再做对应的异常处理。

**【规范】**捕获异常是为了处理它，不要捕获了却什么都不处理而抛弃之，如果不想处理它，请 将该异常抛给它的调用者。最外层的业务使用者，必须处理异常，将其转化为用户可以理解的 内容。

**【强制】**有 try 块放到了事务代码中，catch 异常后，如果需要回滚事务，一定要注意手动回 滚事务。

**【规范】**不能在 finally 块中使用 return，finally 块中的 return 返回后方法结束执行，不 会再执行 try 块中的 return 语句。

**【规范】**方法的返回值可以为 null，不强制返回空集合，或者空对象等，必须添加注释充分 说明什么情况下会返回 null 值。调用方需要进行 null 判断防止 NPE 问题。

**【规范】**防止 NPE，是程序员的基本修养，注意 NPE 产生的场景:

 1. 返回类型为包装数据类型，有可能是null，返回int值时注意判空。

反例:public int f(){ return Integer 对象}; 如果为 null，自动解箱抛 NPE。

 1. 数据库的查询结果可能为null。
 2. 集合里的元素即使isNotEmpty，取出的数据元素也可能为null。
 3. 远程调用返回对象，一律要求进行NPE判断。
 4. 对于Session中获取的数据，建议NPE检查，避免空指针。
 5. 级联调用obj.getA().getB().getC();一连串调用，易产生NPE。

**【规范】**在代码中使用“抛异常”还是“返回错误码”，对于公司外的 http/api 开放接口必须 使用“错误码”;而应用内部推荐异常抛出;跨应用间 RPC 调用优先考虑使用 Result 方式，封 装 isSuccess、“错误码”、“错误简短信息”。

说明:关于 RPC 方法返回方式使用 Result 方式的理由:

1)使用抛异常返回方式，调用方如果没有捕获到就会产生运行时错误。

2)如果不加栈信息，只是new自定义异常，加入自己的理解的error message，对于调用 端解决问题的帮助不会太多。如果加了栈信息，在频繁调用出错的情况下，数据序列化和传输 的性能损耗也是问题。

**【规范】**避免出现重复的代码(Don’t Repeat Yourself)，即DRY原则。


## 日志

**【规范】**应用中不可直接使用日志系统(Log4j、Logback)中的 API，而应依赖使用日志框架

SLF4J 中的 API，使用门面模式的日志框架，有利于维护和各个类的日志处理方式统一。

import org.slf4j.Logger;

import org.slf4j.LoggerFactory;

private static final Logger logger = LoggerFactory.getLogger(Abc.class);

**【规范】**日志文件推荐至少保存 15 天，因为有些异常具备以“周”为频次发生的特点。

**【规范】**应用中的扩展日志(如打点、临时监控、访问日志等)命名方式: appName_logType_logName.log。

logType:日志类型，推荐分类有 stats/desc/monitor/visit 等;

logName:日志描述。这种命名的好处:通过文件名就可知 道日志文件属于什么应用，什么类型，什么目的，也有利于归类查找。

正例:mppserver 应用中单独监控时区转换异常，如: mppserver_monitor_timeZoneConvert.log

说明:推荐对日志进行分类，错误日志和业务日志尽量分开存放，便于开发人员查看，也便于 通过日志对系统进行及时监控。

**【规范】**对 trace/debug/info 级别的日志输出，必须使用条件输出形式或者使用占位符的方式。

说明:logger.debug(“Processing trade with id: ” + id + ” symbol: ” + symbol); 如果日志级别是 warn，上述日志不会打印，但是会执行字符串拼接操作，如果 symbol 是对象， 会执行 toString()方法，浪费了系统资源，执行了上述操作，最终日志却没有打印。 正例:(条件)

if (logger.isDebugEnabled()) {

logger.debug(“Processing trade with id: ” + id + ” symbol: ” + symbol);

}

正例:(占位符)

logger.debug(“Processing trade with id: {} symbol : {} “, id, symbol);

* 避免重复打印日志，浪费磁盘空间，务必在 log4j.xml 中设置 additivity=false。

正例:

**【规范】**可以使用warn 日志级别来记录用户输入参数错误的情况，避免用户投诉时，无所适 从。注意日志输出的级别，error 级别只记录系统逻辑出错、异常等重要的错误信息。如非必 要，请不要在此场景打出 error 级别。

**【规范】**谨慎地记录日志。生产环境禁止输出 debug 日志;有选择地输出 info 日志;如果使 用 warn 来记录刚上线时的业务行为信息，一定要注意日志输出量的问题，避免把服务器磁盘 撑爆，并记得及时删除这些观察日志。

说明:大量地输出无效日志，不利于系统性能提升，也不利于快速定位错误点。记录日志时请

**思考:**这些日志真的有人看吗?看到这条日志你能做什么?能不能给问题排查带来好处?


## 其它

**【效率】**在使用正则表达式时，利用好其预编译功能，可以有效加快正则匹配速度。 说明:不要在方法体内定义:Pattern pattern = Pattern.compile(规则);

**【规范】**获取当前毫秒数 System.currentTimeMillis(); 而不是 new Date().getTime();

说明:如果想获取更加精确的纳秒级时间值，用 System.nanoTime()。在 JDK8 中，针对统计 时间等场景，推荐使用Instant类。

**【规范】**对于“明确停止使用的代码和配置”，如方法、变量、类、配置文件、动态配置属性等要坚决从程序中清理出去，避免造成过多垃圾。


## 单元测试

**【强制】**好的单元测试必须遵守 AIR 原则。

**说明:**单元测试在线上运行时，感觉像空气(AIR)一样并不存在，但在测试质量的保障上，却是非常关键的。好的单元测试宏观上来说，具有自动化、独立性、可重复执行的特点。
 A:Automatic(自动化)
 I:Independent(独立性)

 R:Repeatable(可重复)

【强制】单元测试应该是全自动执行的，并且非交互式的。测试框架通常是定期执行的，执行过程必须完全自动化才有意义。输出结果需要人工检查的测试不是一个好的单元测试。单元测 试中不准使用 System.out 来进行人肉验证，必须使用 assert 来验证。

**【强制】**保持单元测试的独立性。为了保证单元测试稳定可靠且便于维护，单元测试用例之间 决不能互相调用，也不能依赖执行的先后次序。
反例:method2 需要依赖 method1 的执行，将执行结果做为 method2 的输入。

**【强制】**对于单元测试，要保证测试粒度足够小，有助于精确定位问题。单测粒度至多是类级别，一般是方法级别。

**说明:**只有测试粒度小才能在出错时尽快定位到出错位置。单测不负责检查跨类或者跨系统的 交互逻辑，那是集成测试的领域。

【强制】****核心业务、核心应用、核心模块的增量代码确保单元测试通过。

**说明:**新增代码及时补充单元测试，如果新增代码影响了原有单元测试，请及时修正。

**【推荐】**单元测试的基本目标:语句覆盖率达到 70%;核心模块的语句覆盖率和分支覆盖率都 要达到 100%
说明:在工程规约的应用分层中提到的 DAO 层，Manager 层，可重用度高的 Service，都应该 进行单元测试。

【推荐】编写单元测试代码遵守 BCDE 原则，以保证被测试模块的交付质量。
 B:Border，边界值测试，包括循环边界、特殊取值、特殊时间点、数据顺序等。

C:Correct，正确的输入，并得到预期的结果。

 D:Design**，与设计文档相结合，来编写单元测试**。
 E:Error**，强制错误信息输入(如:非法数据、异常流程、非业务允许输入等)，并得 到预期的结果。**

**【推荐】**和数据库相关的单元测试，可以设定自动回滚机制，不给数据库造成脏数据。或者 对单元测试产生的数据有明确的前后缀标识。
正例:在 RDC 内部单元测试中，使用 RDC_UNIT_TEST_的前缀标识数据。

**【推荐】**在设计评审阶段，开发人员需要和测试人员一起确定单元测试范围，单元测试最好 覆盖所有测试用例(UC)。

**【推荐】**单元测试作为一种质量保障手段，不建议项目发布后补充单元测试用例，建议在项 目提测前完成单元测试。

**【参考】**不要对单元测试存在如下误解:
 那是测试同学干的事情。本文是开发手册，凡是本文内容都是与开发同学强相关的。

单元测试代码是多余的。汽车的整体功能与各单元部件的测试正常与否是强相关的。 

单元测试代码不需要维护。一年半载后，那么单元测试几乎处于废弃状态。
 单元测试与线上故障没有辩证关系。好的单元测试能够最大限度地规避线上故障。


## MySQL开发规范


## 建表规约

**【规范】**表达是与否概念的字段，必须使用 is_xxx 的方式命名，数据类型是 unsigned tinyint ( 1表示是，0表示否)，此规则同样适用于odps建表。 说明:任何字段如果为非负数，必须是 unsigned。

**【规范】**表名、字段名必须使用小写字母或数字;禁止出现数字开头，禁止两个下划线中间只 出现数字。数据库字段名的修改代价很大，因为无法进行预发布，所以字段名称需要慎重考虑。

正例:getter_admin，task_config，level3_name

反例:GetterAdmin，taskConfig，level_3_name

**【规范】**唯一索引名为 uk_字段名;普通索引名则为 idx_字段名。

**【规范】**小数类型为 decimal，禁止使用 float 和 double。

说明:float 和 double 在存储的时候，存在精度损失的问题，很可能在值的比较时，得到不 正确的结果。如果存储的数据范围超过 decimal 的范围，建议将数据拆成整数和小数分开存储。

**【规范】**如果存储的字符串长度几乎相等，使用 char 定长字符串类型。

**【效率】**varchar 是可变长字符串，不预先分配存储空间，长度不要超过 5000，如果存储长 度大于此值，定义字段类型为 text，独立出来一张表，用主键来对应，避免影响其它字段索 引效率。

**【规范】**表的命名最好是加上“业务名称_表的作用”。

正例:tiger_task / tiger_reader / mpp_config

**【规范】**库名与应用名称尽量一致。

**【规范】**如果修改字段含义或对字段表示的状态追加时，需要及时更新字段注释。

**【效率】**字段允许适当冗余，以提高性能，但是必须考虑数据同步的情况。冗余字段应遵循:

1)不是频繁修改的字段。

2)不是 varchar 超长字段，更不能是 text 字段。 正例:商品类目名称使用频率高，字段长度短，名称基本一成不变，可在相关联的表中冗余存 储类目名称，避免关联查询。

**【效率】**单表行数超过 500 万行或者单表容量超过 2GB，才推荐进行分库分表。说明:如果预计三年后的数据量根本达不到这个级别，请不要在创建表时就分库分表。

**【效率】**合适的字符存储长度，不但节约数据库表空间、节约索引存储，更重要的是提升检 索速度。

正例:人的年龄用 unsigned tinyint(表示范围 0-255，人的寿命不会超过 255 岁);海龟 就必须是 smallint，但如果是太阳的年龄，就必须是 int;如果是所有恒星的年龄都加起来， 那么就必须使用 bigint。


## 索引规约

**【效率】**业务上具有唯一特性的字段，即使是组合字段，也必须建成唯一索引。

说明:不要以为唯一索引影响了 insert 速度，这个速度损耗可以忽略，但提高查找速度是明 显的;另外，即使在应用层做了非常完善的校验和控制，只要没有唯一索引，根据墨菲定律， 必然有脏数据产生。

**【规范】**超过三个表禁止 join。需要 join 的字段，数据类型保持绝对一致;多表关联查询 时，保证被关联的字段需要有索引。

说明:即使双表 join 也要注意表索引、SQL 性能。

**【规范】**在 varchar 字段上建立索引时，必须指定索引长度，没必要对全字段建立索引，根据 实际文本区分度决定索引长度。

说明:索引的长度与区分度是一对矛盾体，一般对字符串类型数据，长度为 20 的索引，区分 度会高达 90%以上，可以使用 count(distinct left(列名, 索引长度))/count(*)的区分度 来确定。

**【规范】**页面搜索严禁左模糊或者全模糊，如果需要请走搜索引擎来解决。

说明:索引文件具有 B-Tree 的最左前缀匹配特性，如果左边的值未确定，那么无法使用此索 引。

**【规范】**如果有 order by 的场景，请注意利用索引的有序性。order by 最后的字段是组合 索引的一部分，并且放在索引组合顺序的最后，避免出现 file_sort 的情况，影响查询性能。

正例:where a=? and b=? order by c; 索引:a_b_c

反例:索引中有范围查找，那么索引有序性无法利用，如:WHERE a>10 ORDER BY b; 索引 a_b 无法排序。

**【效率】**利用覆盖索引来进行查询操作，来避免回表操作。

说明:如果一本书需要知道第 11 章是什么标题，会翻开第 11 章对应的那一页吗?目录浏览 一下就好，这个目录就是起到覆盖索引的作用。 正例:能够建立索引的种类:主键索引、唯一索引、普通索引，而覆盖索引是一种查询的一种 效果，用explain的结果，extra列会出现:using index。

**【效率】**利用延迟关联或者子查询优化超多分页场景。

说明:MySQL 并不是跳过 offset 行，而是取 offset+N 行，然后返回放弃前 offset 行，返回 N 行，那当 offset 特别大的时候，效率就非常的低下，要么控制返回的总页数，要么对超过 特定阈值的页数进行 SQL 改写。

正例:先快速定位需要获取的 id 段，然后再关联:（优化在可以少查表1的很多字段）

SELECT a.* FROM 表 1 a, (select id from 表 1 where 条件 LIMIT 100000,20 ) b where a.id=b.id

**【效率】**SQL 性能优化的目标:至少要达到 range 级别，要求是 ref 级别，如果可以是 consts 最好。

说明:

1)consts 单表中最多只有一个匹配行(主键或者唯一索引)，在优化阶段即可读取到数据。

2)ref 指的是使用普通的索引(normal index)。

3)range 对索引进行范围检索。

反例:explain 表的结果，type=index，索引物理文件全扫描，速度非常慢，这个 index 级 别比较 range 还低，与全表扫描是小巫见大巫。

**【规范】**建组合索引的时候，区分度最高的在最左边。

正例:如果 where a=? and b=? ，a 列的几乎接近于唯一值，那么只需要单建 idx_a 索引即 可。

说明:存在非等号和等号混合判断条件时，在建索引时，请把等号条件的列前置。如:where a>? and b=? 那么即使 a 的区分度更高，也必须把 b 放在索引的最前列。

**【说明】**创建索引时避免有如下极端误解:

1)误认为一个查询就需要建一个索引。

2)误认为索引会消耗空间、严重拖慢更新和新增速度。

3)误认为唯一索引一律需要在应用层通过“先查后插”方式解决。


## SQL规约

**【规范】**不要使用 count(列名)或 count(常量)来替代 count(*)，count(*)就是 SQL92 定义 的标准统计行数的语法，跟数据库无关，跟 NULL 和非 NULL 无关。

说明:count(*)会统计值为 NULL 的行，而 count(列名)不会统计此列为 NULL 值的行。

**【说明】**count(distinct col) 计算该列除 NULL 之外的不重复数量。注意 count(distinct col1, col2) 如果其中一列全为NULL，那么即使另一列有不同的值，也返回为0。

**【说明】**当某一列的值全是 NULL 时，count(col)的返回结果为 0，但 sum(col)的返回结果为 NULL，因此使用 sum()时需注意 NPE 问题。

正例:可以使用如下方式来避免sum的NPE问题:SELECT IF(ISNULL(SUM(g)),0,SUM(g)) FROM table;

**【说明】**使用 ISNULL()来判断是否为 NULL 值。注意:NULL 与任何值的直接比较都为 NULL。

说明:

 1. NULL<>NULL的返回结果是NULL，而不是false。
 2. NULL=NULL的返回结果是NULL，而不是true。
 3. NULL<>1的返回结果是NULL，而不是true。

**【规范】**不得使用外键与级联，一切外键概念必须在应用层解决。

说明:(概念解释)学生表中的 student_id 是主键，那么成绩表中的 student_id 则为外键。 如果更新学生表中的 student_id，同时触发成绩表中的 student_id 更新，则为级联更新。外键与级联更新适用于单机低并发，不适合分布式、高并发集群;级联更新是强阻塞，存在数 据库更新风暴的风险;外键影响数据库的插入速度。

**【规范】**数据订正时，删除和修改记录时，要先 select，避免出现误删除，确认无误才能执行更新语句。

**【效率】**in 操作能避免则避免，若实在避免不了，需要仔细评估 in 后边的集合元素数量，控制在 1000 个之内。（可以用用 EXISTS ，NOT EXISTS 或 JOIN代替）

**【规范】**如果有全球化需要，所有的字符存储与表示，均以 utf-8 编码，那么字符计数方法 注意:

说明:

SELECT LENGTH(“轻松工作”); 返回为12

SELECT CHARACTER_LENGTH(“轻松工作”); 返回为4 如果要使用表情，那么使用 utfmb4 来进行存储，注意它与 utf-8 编码的区别。

**【规范】**TRUNCATE TABLE 比 DELETE 速度快，且使用的系统和事务日志资源少，但 TRUNCATE无事务且不触发 trigger，有可能造成事故，故不建议在开发代码中使用此语句。

说明:TRUNCATE TABLE 在功能上与不带 WHERE 子句的 DELETE 语句相同。


## ORM规约

**【规范】**POJO 类的 boolean 属性不能加 is，而数据库字段必须加 is_，要求在 resultMap 中 进行字段与属性之间的映射。

说明:参见定义 POJO 类以及数据库字段定义规定，在 sql.xml 增加映射，是必须的。

**【安全】**配置XML文件时注意SQL注入问题。

**【规范】**不允许直接拿 HashMap 与 Hashtable 作为查询结果集的输出。

**【强制】**更新数据表记录时，必须同时更新记录对应的 gmt_modified 字段值为当前时间。

**【规范】**不要写一个大而全的数据更新接口，传入为 POJO 类，不管是不是自己的目标更新字 段，都进行 update table set c1=value1,c2=value2,c3=value3; 这是不对的。执行 SQL 时，尽量不要更新无改动的字段，一是易出错;二是效率低;三是 binlog 增加存储。

【规范】@Transactional 事务不要滥用。事务会影响数据库的 QPS，另外使用事务的地方需 要考虑各方面的回滚方案，包括缓存回滚、搜索引擎回滚、消息补偿、统计修正等。


## 工程规约



【说明】**图中默认上层依赖于下层，箭头关系表示可直接依赖，如:开放接口层可以依赖于Web 层，也可以直接依赖于 Service 层，依此类推。

 开放接口层:可直接封装 Service接口暴露成 RPC 接口;通过 Web 封装成 http 接口;网关控 制层等。

 终端显示层:各个端的模板渲染并执行显示层。当前主要是 velocity 渲染，JS 渲染，JSP 渲 染，移动端展示层等。

 Web 层:主要是对访问控制进行转发，各类基本参数校验，或者不复用的业务简单处理等。(Controller)

 Service 层:相对具体的业务逻辑服务层。

 Manager 层:通用业务处理层，它有如下特征:

1)对第三方平台封装的层，预处理返回结果及转化异常信息;

2)对Service层通用能力的下沉，如缓存方案、中间件通用处理;

3)与DAO层交互，对DAO的业务通用能力的封装。

 DAO 层:数据访问层，与底层 MySQL、Oracle、Hbase 进行数据交互。

 外部接口或第三方平台:包括其它部门 RPC 开放接口，基础平台，其它公司的 HTTP 接口。

【规范】(分层异常处理规约)在 DAO 层，产生的异常类型有很多，无法用细粒度的异常进 行catch，使用catch(Exception e)方式，并throw new DAOException(e)，**不需要打印日志，因为日志在 Manager/Service 层一定需要捕获并打到日志文件中去，如果同台服务器 再打日志，浪费性能和存储。**在 Service 层出现异常时，必须记录出错日志到磁盘，尽可能带 上参数信息，相当于保护案发现场。如果 Manager 层与 Service 同机部署，日志方式与 DAO 层处理一致，如果是单独部署，则采用与 Service 一致的处理方式。Web 层绝不应该继续往上抛异常，因为已经处于顶层，如果意识到这个异常将导致页面无法正常渲染，那么就应该直接跳转到友好错误页面，加上用户容易理解的错误提示信息。开放接口层要将异常处理成错误码 和错误信息方式返回。

**【规范】**分层领域模型规约:

 DO(Data Object):与数据库表结构一一对应，通过 DAO 层向上传输数据源对象。(Entity)

 DTO(Data Transfer Object):数据传输对象，Service 和 Manager 向外传输的对象。

 BO(Business Object):业务对象。可以由 Service 层输出的封装业务逻辑的对象。

 QUERY:数据查询对象，各层接收上层的查询请求。注:超过 2 个参数的查询封装，禁止 使用 Map 类来传输。

 VO(View Object):显示层对象，通常是 Web 向模板渲染引擎层传输的对象。


## 服务器规约

**【效率】**高并发服务器建议调小 TCP 协议的 time_wait 超时时间。

说明:操作系统默认 240 秒后，才会关闭处于 time_wait 状态的连接，在高并发访问下，服务器端会因为处于 time_wait 的连接数太多，可能无法建立新的连接，所以需要在服务器上 调小此等待值。

正例:在 linux 服务器上请通过变更/etc/sysctl.conf 文件去修改该缺省值(秒):

net.ipv4.tcp_fin_timeout = 30

**【效率】**调大服务器所支持的最大文件句柄数(File Descriptor，简写为fd)。

说明:主流操作系统的设计是将 TCP/UDP 连接采用与文件一样的方式去管理，即一个连接对 应于一个 fd。主流的 linux 服务器默认所支持最大 fd 数量为 1024，当并发连接数很大时很 容易因为 fd 不足而出现“open too many files”错误，导致新的连接无法建立。 建议将 linux 服务器所支持的最大句柄数调高数倍(与服务器的内存数量相关)。

**【规范】**给 JVM 设置-XX:+HeapDumpOnOutOfMemoryError 参数，让 JVM 碰到 OOM 场景时输出 dump 信息。

说明:OOM 的发生是有概率的，甚至有规律地相隔数月才出现一例，出现时的现场信息对查错 非常有价值。

**【规范】**服务器内部重定向使用 forward;外部重定向地址使用 URL 拼装工具类来生成，否则 会带来 URL 维护不一致的问题和潜在的安全风险。


## 安全规约

**【安全】**隶属于用户个人的页面或者功能必须进行权限控制校验。

说明:防止没有做水平权限校验就可随意访问、操作别人的数据，比如查看、修改别人的订单。

**【安全】**用户敏感数据禁止直接展示，必须对展示数据脱敏。

说明:查看个人手机号码会显示成:158****9119，隐藏中间 4 位，防止隐私泄露。

**【安全】**用户输入的 SQL 参数严格使用参数绑定或者 METADATA 字段值限定，防止 SQL 注入， 禁止字符串拼接 SQL 访问数据库。

**【安全】**用户请求传入的任何参数必须做有效性验证。

说明:忽略参数校验可能导致:

 page size 过大导致内存溢出

 恶意 order by 导致数据库慢查询

 任意重定向

 SQL 注入

 反序列化注入

 正则输入源串拒绝服务 ReDoS

说明:Java 代码用正则来验证客户端的输入，有些正则写法验证普通用户输入没有问题， 但是如果攻击人员使用的是特殊构造的字符串来验证，有可能导致死循环的效果。

**【安全】**禁止向 HTML 页面输出未经安全过滤或未正确转义的用户数据。

**【安全】**表单、AJAX 提交必须执行 CSRF 安全过滤。

说明:CSRF(Cross-site request forgery)跨站请求伪造是一类常见编程漏洞。对于存在 CSRF 漏洞的应用/网站，攻击者可以事先构造好 URL，只要受害者用户一访问，后台便在用户 不知情情况下对数据库中用户参数进行相应修改。

**【安全】**在使用平台资源，譬如短信、邮件、电话、下单、支付，必须实现正确的防重放限制， 如数量限制、疲劳度控制、验证码校验，避免被滥刷、资损。

说明:如注册时发送验证码到手机，如果没有限制次数和频率，那么可以利用此功能骚扰到其 它用户，并造成短信平台资源浪费。

**【安全】**发贴、评论、发送即时消息等用户生成内容的场景必须实现防刷、文本内容违禁词过 滤等风控策略。

编撰人：yinyanting、xuecx




快速跳转



 * 后端开发规范
   * Java开发规范
     * 命名
     * 常量
     * 格式规约
     * OOP规约
     * 集合处理
     * 并发处理
     * 控制语句
     * 注释规约
     * 异常
     * 日志
     * 其它
   * 单元测试
   * MySQL开发规范
     * 建表规约
     * 索引规约
     * SQL规约
     * ORM规约
   * 工程规约
   * 服务器规约
   * 安全规约



分享链接分享链接

## 120. 表单业务讲解

> 原始路径：`/94/355/477/`  
> 相对路径：`94/355/477/README.md`  
> JS Chunk：`app.371b709c.js`

## 表单业务讲解

编撰人：yinyanting


快速跳转



 * 表单业务讲解



分享链接分享链接

## 121. 数据魔方

> 原始路径：`/94/355/477/519.html`  
> 相对路径：`94/355/477/519.md`  
> JS Chunk：`app.371b709c.js`

## 数据魔方

数据魔方接入方式主要有以下2种：


## 1、实现com.seeyon.datamagic.engine.out.service.OutService接口


## （1）接口方法简要说明

方法名                     说明
getServiceInfo          获取接口选择页面标签
loadAllServices         加载所有支持的选择器列表左侧树列表
convert                 将选择后的树节点信息转换成魔方接口
provider                提供当前节点的实现类
generateMethodContent   代码块生成代码


## （2） 界面和功能入口




## (3)点击确定后会调用convert和provider方法进行接口定义生成。


## (4)目前通过此方法接入的功能列表如下:

| ---------- | -------------------------------------------------------- | | 名称 | 类名 | | 业务生成器/表单应用 | com.seeyon.cap4.magic.generator.cap3.CAP3FormJoinService | | CIP业务接口 | com.seeyon.apps.voucher.cap4.VoucherForCapMagicService | | 报表 | com.seeyon.cap4.magic.manager.impl.MagicReportOutService | | DEE数据交互接口 | com.seeyon.apps.dee.cap4.DeeForCapMagicService |


## 2、通过通用接口实现


## （1）应用应用设计师进入业务包-->管理设置-->接口管理




## (2) 集团管理员/单位管理员进入CIP集成平台-->集成资源库-->CAP应用接口




## (3)新建通用接口，必填以及关键信息如下

## (1) 填写接口名称

## (2) 调用授权，默认是公开，标识所有的业务包都能调用;也可以选择自定义指定某些业务包能够调用，



## (3)点击下一步新建方法，目前只支持关联/触发，注意事项如下

## (1) 关联 返回值必填

## (2) 触发 没有必填项

## (3) 无论是关联和触发，代码名称必须符合java的命名规范，并且不能使用java内置关键字

## (4) 关联和触发的传入参数关联条件不允许使用OA内置的函数名称，比如year,date等



## (4)设置好方法后点击下一步进入接口实现页面先点击下一步将接口定义信息保存入库 然后选中此接口并点击修改 再次进入接口实现。此时接口实现为空需要下载接口代码点击按钮下载接口代码，下载完成后解压后用idea或者eclipse打开



## (1) MagicProviderRegisterImpl 此结果在导入接口实现时由程序调用不能删除

## (2) 修改pom.xml中的版本号，默认是trunk-SNAPSHOT,需要修改为系统当前的版本

## (3) 进入类C372f1c191aaa516db58df5803508499f中编写对应的接口实现。

## (4) 代码编写完成后 执行maven 打包命令package



## (5) 在接口实现页面点击导入实现将打包后的zip文件上传到OA服务器此次接口实现会显示出导入的实现



## (6)确定后页面刷新 这时接口实现就是开发时提供的接口实现



自此 通路已经完成，可以通过表单的业务关系关联/触发选择到自己新建的接口(方法显示名称)后进行业务测试.如果实现类有问题可以修改后重新打包 将之前的实现类删掉 重新导入实现。目前 组织机构是通过此方式接入




## 推荐使用第二种方式


## 注意事项总结如下

** (1)  方法名称可以自定义，只需要满足java命名规范**

** (2)  方法参数名需要满足java命名规范，关联条件不能使用OA自带的函数名称 比如 year ，date**

** (3)  代码源码中有个关键文件  serviceConfig.json  这个文件不能修改，如果有调整必须通过OA接口定义界面调整，然后下载后直接用文件更新。 导入实现时会用此文件重新更新接口定义，因此需要保证OA中的接口定义和工程中的一致，否则会出现覆盖的情况。**

编撰人：yinyanting、het


快速跳转



 * 数据魔方
   * 1、实现com.seeyon.datamagic.engine.out.service.OutService接口
     * （1）接口方法简要说明
     * （2） 界面和功能入口
     * (3)点击确定后会调用convert和provider方法进行接口定义生成。
     * (4)目前通过此方法接入的功能列表如下:
   * 2、通过通用接口实现
     * （1）应用应用设计师进入业务包-->管理设置-->接口管理
     * (2) 集团管理员/单位管理员进入CIP集成平台-->集成资源库-->CAP应用接口
     * (3)新建通用接口，必填以及关键信息如下
       * (1) 填写接口名称
       * (2) 调用授权，默认是公开，标识所有的业务包都能调用;也可以选择自定义指定某些业务包能够调用，
       * (3)点击下一步新建方法，目前只支持关联/触发，注意事项如下
         * (1) 关联 返回值必填
         * (2) 触发 没有必填项
         * (3) 无论是关联和触发，代码名称必须符合java的命名规范，并且不能使用java内置关键字
         * (4) 关联和触发的传入参数关联条件不允许使用OA内置的函数名称，比如year,date等
       * (4)设置好方法后点击下一步进入接口实现页面先点击下一步将接口定义信息保存入库 然后选中此接口并点击修改 再次进入接口实现。此时接口实现为空需要下载接口代码点击按钮下载接口代码，下载完成后解压后用idea或者eclipse打开
         * (1) MagicProviderRegisterImpl 此结果在导入接口实现时由程序调用不能删除
         * (2) 修改pom.xml中的版本号，默认是trunk-SNAPSHOT,需要修改为系统当前的版本
         * (3) 进入类C372f1c191aaa516db58df5803508499f中编写对应的接口实现。
         * (4) 代码编写完成后 执行maven 打包命令package
         * (5) 在接口实现页面点击导入实现将打包后的zip文件上传到OA服务器此次接口实现会显示出导入的实现
         * (6)确定后页面刷新 这时接口实现就是开发时提供的接口实现
   * 推荐使用第二种方式
   * 注意事项总结如下



分享链接分享链接

## 122. WBS客户使用的常见问题集合

> 原始路径：`/94/355/766/1351.html`  
> 相对路径：`94/355/766/1351.md`  
> JS Chunk：`app.371b709c.js`

## WBS客户使用的常见问题集合


## 使用说明

**wbs新版本2.0：**项目任务管理控件：V31.0.0 及以上； 项目任务管理按钮： V30.0.0及以上。 **wbs环境：**协同云体验中心 — WBS任务管理应用和项目综合管理系统


## 常见问题

问题：新上市的9.0版本中的WBS功能，安装产品后在哪里开启使用？是否和之前一样，需要在协同云购买wbs应用包？

解答： a、客户环境安装过wbs控件： 1）若走的正式订单购买wbs应用获取到wbs控件的话，则目前需要走支持单，获取到最新版本的wbs控件。待商城订单有推送最新控件的功能后则不需要走支持单获取最新控件，商城订单推送最新控件的功能上线时间待定。 2）若是走的试用订单获取到wbs控件的话，则需要重新下试用订单获取最新的控件。 b、客户环境未安装过wbs应用包和控件： 需要在商城下试用单或者正式单。订单里有应用包和wbs控件和按钮

----------------------------------------

问题：WBS应用中某个任务延期了，会触发一张任务延期的表单，我们会修改时间，会出现一种情况，后续的任务可能就全部需要延后时间，后续的任务怎么修改？

解答：客户环境下载的应用包是23年6月下载的，当前客户环境的版本没有支持修改底表的计划时间。

支持甘特图的项目的计划时间会同时修改的功能，项目任务管理控件：V31.0.0 及以上； 项目任务管理按钮： V30.0.0及以上。后续的任务，延后时间也需要通过触发产生的表单后修改计划时间。

----------------------------------------

问题：设置了前置任务，子任务关联，前置任务延期了关联的子任务时间会不会自动变？

解答：设置了前置任务，子任务关联。 如果是在甘特图页面操作，修改前置任务的时间，关联的子任务时间会自动变更； 如果是触发产生的父任务延期的表单，修改任务时间，仅是修改当前任务的计划时间，关联子任务的时间不会自动变更。

----------------------------------------

问题：wbs任务导入不了提示：当前项目已有任务数据，不允许导入。能不能去掉这个提示？ 或是删除任务怎么设置批量删除？



解答：产品需求功能设计：当前项目已有任务数据，不允许导入。不能去掉；没有批量删除的功能，只有逐条删除的功能

----------------------------------------

问题：甘特图导入数据可以支持.project格式吗

解答：甘特图导入数据只支持xml格式导入，不支持.project格式导入。可与微软project相互导入，但需要从微软project可以导出xml格式，以.xml格式导入到甘特图。

----------------------------------------

问题：WBS中的计划工期中的工作日是如何设置的，是和OA系统的工作日同步的嘛，还是在什么地方其他设置，客户环境需要自定义设置日历。



解答：WBS计划工期中的工作日和OA系统的工作日不是同步的。用的是WBS里设置的日历，有内置标准的日历，若不满足客户的需求，可以在配置态创建自定义的日历，甘特图使用的时候就能用到自定义的日历。

配置态：【项目档案】— 【WBS分解】 — 【映射字段】：



甘特图 — 使用自定义的日历



----------------------------------------

问题：WBS打开默认关键路径是关闭状态，保存后就自动打开了



解答：老版本的wbs甘特图是在保存的时候，会有前端闪动开启了关键路径。但是重新刷新或者进入甘特图页面并没有开启关键路径。关键路径的开启这个功能，只是当前操作的开启，并没有记录，重新刷新或者进入甘特图默认都是关闭的。 客户环境低版本的环境，需要修改了前端代码，具体修改代码位置如图



----------------------------------------

问题：项目任务管理控件，之前配置的时候没有“保存为项目模板”，但是现在新配置的时候有这个选项，但客户不需要这个，目前又没法删除，需要确认这个字段是怎么配置和映射的？



解答：【保存为项目模板】是新功能，应用包需要用新的，目前应用包最新版未上架，若客户环境需要用，则需要WBS角色权限表单-需要新增【保存为项目模板】字段，复选类型。然后在角色权限勾选上【保存为项目模板】，则可以在甘特图页面使用【另存为模版】



----------------------------------------

问题：wbs项目管理，怎么查看项目的导入时间？

解答：甘特图页面没有查看任务导入的时间。只能通过将任务档案应用绑定列表显示字段添加：创建时间，在任务档案列表查看创建时间就是任务导入的时间。



----------------------------------------

问题：项目进度百分比可以同步到项目档案中显示么？

解答：任务进度完成百分比，是任务档案里的字段，代表的是当前某一个任务的进度完成百分比。没有项目进度百分比，项目档案里显示任务进度完成百分比不合理。

----------------------------------------

问题：是否可以按项目经理、项目负责人等角色设置不同的权限（查看、编辑、删除任务）？

解答：可以，在【角色权限】设置不同的角色，在【项目成员】添加为不同的人添加不同的角色。则可以实现

----------------------------------------

问题：WBS功能中的数据跟CAP4表单是否可以互联互通？

解答：wbs功能里操作的数据是基于cap4表单的表存储数据，具体哪些表单数据，需要看wbs项目管理应用包里表单配置。 应用包：WBS任务管理应用和项目综合管理系统

----------------------------------------

**问题：同一个项目，在底表中点击任务计划，导入模板是有选择的模版数据；但在流程表单中点击任务计划，点击导入模板没有可以选择的模板数据 **

解答：模版是归属于项目走的，不能跨项目的模版，别的项目使用。 导入模版—选择的模版是不区分入口，只跟项目相关。若同一个项目，两个入口存在获取到的模版不一样，是产品的bug。客户BUG2024052007506 已修复。

编撰人：hedan、het


快速跳转



 * WBS客户使用的常见问题集合
   * 使用说明
   * 常见问题



分享链接分享链接

## 123. 标签打印自定义模板操作说明

> 原始路径：`/94/355/1937/1938.html`  
> 相对路径：`94/355/1937/1938.md`  
> JS Chunk：`app.371b709c.js`

## 标签打印自定义模板操作说明


## 场景

系统内置了多套标签打印模板，都不满足用户需求，需要个性化调整属于自己的标签模板。

以下提供了自定义调整的方案。


## 适合人群

本方案需要懂JSON基础知识的技术人员或实施人员操作。


## 自定义模板操作方式

1、打开表单设计器-应用绑定，修改或新建应用绑定，添加一个"标签打印"自定义按钮



2、打开标签打印设置窗口，点击设置，在弹出的模板列表中依次点击查看，找到一个与要新增的模板相似的模板。

> 

3、打开数据库中cap_print_template表，找到第二步的模板数据，复制并插入一行，修改插入行的ID，模板名称，保证与其他行不重复。



4、将第1步中的"标签打印"自定义按钮模板设置为新增的模板。配置字段映射，表单权限，菜单等。



5、打开表单数据行上的标签打印，查看打印预览效果。



6、将第三步插入的数据行中content列字段剪切，粘贴到json.cn格式化，然后拷贝到content列，方便修改。



7、按从上到下，从左到右依次修改标签的位置，宽高等。调整后刷新第5步的打印页面看效果。



修改参数格式：

1、"type":"staticText"为左侧标签，"type":"line"为线，"type":"6678555354073746763"为二维码，其他则为文字。 2、name不可重复，主要用于字段映射。 3、模板大小不变的情况下外框的4个line不需要调整。如果要调整线的位置，可以将线的颜色修改为非黑色，以便快速找出要修改的线。 4、建议使用上图中的ping fang sc和microsoft yahei字体,否则会有打印不清晰问题。


## 其它问题

1、从8.2开始，如果出现不换行问题，可能是BUG，请上报BUG获取补丁包。

2、如果出现多行打印，部分浏览器表单预览正常，打印预览不换行，可能是BUG，请上报BUG。

3、如果想要打印的时候让标签在标签纸上居中，而不是靠近上方时，可以进行客开解决 可以修改index.html的代码，新增style的padding，调整top和bottom的合适间距大小，让其整体下移

编撰人：het、zhangzuh




快速跳转



 * 标签打印自定义模板操作说明
   * 场景
   * 适合人群
   * 自定义模板操作方式
   * 其它问题



分享链接分享链接

## 124. 特别说明

> 原始路径：`/94/470/471/`  
> 相对路径：`94/470/471/README.md`  
> JS Chunk：`app.371b709c.js`

## 特别说明

作为客开控制使用的场景。自定义控件基于V8.0sp2版本开发的，如果是基于V8.0sp2及以上版本开发的，则不需要适配。如果是基于在V8.0sp2版本以前使用，需要进行自定义控件适配。

编撰人：yinyanting




快速跳转



 * 特别说明



分享链接分享链接

## 125. cap3自定义控件

> 原始路径：`/94/470/471/473.html`  
> 相对路径：`94/470/471/473.md`  
> JS Chunk：`app.371b709c.js`

## cap3自定义控件

1、自定义控件事件注册

目录：移动工程/v5/form/js/components/suiCustom.js

示例：

  /**
 * demo自定义控件-附件，返回html
 * @param (html, inputAttrObj, options, auth)
 * @returns {string}
 */
 
api.buildAttaChmentDom = function(html, inputAttrObj, options, auth){
    //此处是渲染控件的dom
    
    //如果是relation或者relationform，则修改__state
    if (options.fieldInfo.inputType == 'relation' || options.fieldInfo.inputType == 'relationform') {
        options.model.__state = 'modified';
    }
    inputAttrObj['value'] = options.model.value;
    inputAttrObj['readonly'] = 'true';
    inputAttrObj['class'] += ' sui-hide';
    html += '<input ' + cmp.sui.attrBuilder(inputAttrObj) + '/>';
    html += '<div ' + cmp.sui.attrBuilder({class: 'sui-form-ctrl-value-display sui-form-ctrl-attachment', id: options.fieldInfo.name}) + '>';
    //attachment控件 --start
    options.model.attData = options.model.attData || [];
    var items = options.model.attData;

    if (items.length > 0) {
        html += '<div class="attachment-items">';
        items.forEach(function(item){
            item.remoteSource = !item.remoteSource ? (cmp.util.getSeeyonPath() + '/rest/attachment/file/' + item.fileUrl) : item.remoteSource;
            html += '   <div class="attachment-item">';
            html += '       <i class="attachment-icon ' + _FileExtensionFilter(item.extension) +  '"></i>';
            var dom = document.createElement('div');
            dom.classList.add('attachment-content');
            dom.classList.add('allow-click-attachment');
            dom.setAttribute('see-att-data', JSON.stringify(item));
            dom.innerHTML = item.filename;
            html += dom.outerHTML;
            if (auth == 'edit') {
                html += '    <i class="see-icon-v5-form-close-circle-fill"></i>';
            }
            html += '   </div>';
        });
    } else {
        html += '<div class="attachment-items items-empty">';
    }

    html += '</div>';//items-end
    if (auth == 'edit') {
        html += '<div class="attachment-add-item">' + (cmp.i18n('form.attachment.uploadLimit') || 'Please upload file which limited as 50MB') +
            '   <div class="icon-add">' +
            '           <i class="see-icon-v5-form-add"></i>' +
            '  </div>' +
            ' </div>';
    }

    html += '</div>';
    //attachment控件 --end
    html +='</div>';
    return html
}


2、自定义调用

目录：移动工程/v5/form/js/components/sui_utils.js

示例：

case 'customcontrol':
  if(options.model.customType&&options.model.customType!='text'){
      //自定义控件 -demo
      inputAttrObj['customType'] = options.model.customType;
      switch (inputAttrObj['customType']){
          case 'attachment':
              html += SuiCustom.buildAttaChmentDom (html, inputAttrObj, options, auth)
              break;
          default:
              break;
      }
  }else{
      inputAttrObj['value'] = options.model.value;
      inputAttrObj['readonly'] = 'true';
      inputAttrObj['class'] += ' sui-hide';
      html += '<input ' + $.sui.attrBuilder(inputAttrObj) + '/>';
      html += '<div ' + $.sui.attrBuilder({class: 'sui-form-ctrl-value-display sui-form-ctrl-static ' + (!options.model.value ? 'sui-form-placeholder' : ''), id: options.fieldInfo.name}) + '>' + (options.model.display || options.fieldInfo.desc || '').escapeHTML() + '</div>';
  }
  break;


编撰人：yinyanting


快速跳转



 * cap3自定义控件



分享链接分享链接

## 126. cap3 表单运行态接口

> 原始路径：`/94/470/475.html`  
> 相对路径：`94/470/475.md`  
> JS Chunk：`app.371b709c.js`

## cap3 表单运行态接口

//待补充


编撰人：yinyanting


快速跳转



 * cap3 表单运行态接口



分享链接分享链接

## 127. 标题（第一行必须是一号标题，并且唯一）

> 原始路径：`/2133/`  
> 相对路径：`2133/README.md`  
> JS Chunk：`app.371b709c.js`

## 标题（第一行必须是一号标题，并且唯一）

不用加toc标签：只要第一行是一号标题，系统会自动识别生成快速跳转链接


## 背景&需求（接着是二号标题）

不要为了美观，上来就4号####、5号#####标题，有些内容可以用加粗符号

功能示例贴图：直接CTRL+V到本文档光标位置

代码不允许贴图，代码直接贴代码片段：




所有文字、截图严禁出现客户公司名称、金额、网址、联系方式等一切隐私数据!

保存之后，会自动发送致信消息给管理员，可以致信催促管理员审核发布，否则不会更新到open.seeyoncloud.com。




## 操作步骤&解决方案


## 第一类方案

## 第一步：

## 第二步：

## 第三步：


## 第二类方案

编撰人：ouyp、admin


快速跳转



 * 标题（第一行必须是一号标题，并且唯一）
   * 背景&需求（接着是二号标题）
   * 操作步骤&解决方案
     * 第一类方案
       * 第一步：
       * 第二步：
       * 第三步：
     * 第二类方案



分享链接分享链接

## 128. 应用平台

> 原始路径：`/2133/2134/2214.html`  
> 相对路径：`2133/2134/2214.md`  
> JS Chunk：`app.371b709c.js`

编撰人：yangyiwen


快速跳转







分享链接分享链接
