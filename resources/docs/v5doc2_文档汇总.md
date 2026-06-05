# Seeyon V5 Doc2 文档汇总

- 来源：https://open.seeyoncloud.com/v5doc2/
- 提取文档数：77
- 说明：从 VuePress 静态站点 JS 中的原始 Markdown content 字段提取整理。

## 目录

1. [快速开始](#快速开始) — `/quickStart/`
2. [Hello World](#hello-world) — `/quickStart/helloworld.html`
3. [Nice Code](#nice-code) — `/quickStart/nicecode.html`
4. [前端文档](#前端文档) — `/166/`
5. [JSP动态脚本链入](#jsp动态脚本链入) — `/166/338/339.html`
6. [项目](#项目) — `/166/575/578/580.html`
7. [1.公用组件的抽离](#1公用组件的抽离) — `/166/575/578/581/`
8. [Vuex和provide、inject在项目中使用取舍](#vuex和provideinject在项目中使用取舍) — `/166/575/578/581/582.html`
9. [1.组件名、重要方法的名称备注的规则](#1组件名重要方法的名称备注的规则) — `/166/575/578/581/583.html`
10. [概述](#概述) — `/166/575/578/584.html`
11. [前言](#前言) — `/166/575/578/585.html`
12. [IE11、10中使用promise中的finally报错](#ie1110中使用promise中的finally报错) — `/166/575/578/591.html`
13. [npm run build时提示error -4048报错](#npm-run-build时提示error--4048报错) — `/166/575/578/593.html`
14. [组件封装原则](#组件封装原则) — `/166/575/578/596.html`
15. [Vue项目在IE10中包语法错位](#vue项目在ie10中包语法错位) — `/166/575/578/597.html`
16. [Vue项目在IE10浏览器环境下页面加载空白](#vue项目在ie10浏览器环境下页面加载空白) — `/166/575/578/598.html`
17. [1. 真实案例](#1-真实案例) — `/166/575/578/926.html`
18. [1、corejs相关的错误，如下图](#1corejs相关的错误如下图) — `/166/575/589/927.html`
19. [引入变化](#引入变化) — `/166/575/606/607.html`
20. [常规使用](#常规使用) — `/166/575/606/611.html`
21. [关于fiber切换新引入方案](#关于fiber切换新引入方案) — `/166/575/606/618.html`
22. [ICP备案](#icp备案) — `/1073/`
23. [APP备案引导手册](#app备案引导手册) — `/1073/1112.html`
24. [V5产品文档](#v5产品文档) — `/1073/1112.html`
25. [流版签](#流版签) — `/1136/`
26. [金格控件自检步骤](#金格控件自检步骤) — `/1136/1137.html`
27. [控件下载](#控件下载) — `/1136/1138.html`
28. [金格常见问题索引](#金格常见问题索引) — `/1136/1822.html`
29. [OfiiceTrans在线预览问题索引](#ofiicetrans在线预览问题索引) — `/1136/1846.html`
30. [插件适配的各浏览器情况](#插件适配的各浏览器情况) — `/1136/1847.html`
31. [永中wo（在线编辑）问题索引](#永中wo在线编辑问题索引) — `/1136/1857.html`
32. [点聚全文签批问题索引](#点聚全文签批问题索引) — `/1136/1893.html`
33. [永中dcs（在线预览）问题索引](#永中dcs在线预览问题索引) — `/1136/1932.html`
34. [国标Office自检步骤](#国标office自检步骤) — `/1136/1933.html`
35. [金山中台（金山weboffice）问题索引](#金山中台金山weboffice问题索引) — `/1136/1967.html`
36. [数科问题索引](#数科问题索引) — `/1136/2050.html`
37. [文档通问题索引](#文档通问题索引) — `/1136/2051.html`
38. [公文](#公文) — `/1142/`
39. [公文交换](#公文交换) — `/1142/1193/1194.html`
40. [公文元素](#公文元素) — `/1142/1193/1195.html`
41. [公文开关](#公文开关) — `/1142/1193/1196.html`
42. [公文预归档](#公文预归档) — `/1142/1193/1197.html`
43. [发文拟文/收文登记/签发拟文](#发文拟文收文登记签发拟文) — `/1142/1193/1198.html`
44. [外部单位](#外部单位) — `/1142/1193/1199.html`
45. [套红模板管理](#套红模板管理) — `/1142/1193/1200.html`
46. [快速发文（公文交换）](#快速发文公文交换) — `/1142/1193/1201.html`
47. [文单管理](#文单管理) — `/1142/1193/1202/`
48. [文单格式配置](#文单格式配置) — `/1142/1193/1202/1203.html`
49. [文号管理](#文号管理) — `/1142/1193/1204.html`
50. [机构组](#机构组) — `/1142/1193/1205.html`
51. [模板管理](#模板管理) — `/1142/1193/1206.html`
52. [电子印章](#电子印章) — `/1142/1193/1207.html`
53. [节点权限管理](#节点权限管理) — `/1142/1193/1208.html`
54. [节点动作](#节点动作) — `/1142/1193/1209.html`
55. [公文升级](#公文升级) — `/1142/1210.html`
56. [对外接口](#对外接口) — `/1142/1211.html`
57. [公文问题索引](#公文问题索引) — `/1142/1881.html`
58. [引导](#引导) — `/1142/2052.html`
59. [致信](#致信) — `/1146/`
60. [致信IM消息传输逻辑图](#致信im消息传输逻辑图) — `/1146/1308.html`
61. [浏览器](#浏览器) — `/1870/`
62. [背景](#背景) — `/1870/1871.html`
63. [云联中心](#云联中心) — `/1895/`
64. [云联常见问题](#云联常见问题) — `/1895/1896.html`
65. [电子邮件](#电子邮件) — `/1909/`
66. [电子邮件常见问题列表](#电子邮件常见问题列表) — `/1909/1912.html`
67. [组织模型](#组织模型) — `/1915/`
68. [组织模型问题索引](#组织模型问题索引) — `/1915/1916.html`
69. [CAP3表单](#cap3表单) — `/1923/`
70. [CAP3表单问题索引](#cap3表单问题索引) — `/1923/1922.html`
71. [文化建设](#文化建设) — `/1928/`
72. [文化建设常见问题FAQ清单](#文化建设常见问题faq清单) — `/1928/1929.html`
73. [文档中心](#文档中心) — `/1930/`
74. [文档中心常见问题](#文档中心常见问题) — `/1930/1931.html`
75. [智能合同](#智能合同) — `/2794/`
76. [智能合同产品文档清单](#智能合同产品文档清单) — `/2794/2796.html`
77. [智能合同管理_业务逻辑说明](#智能合同管理业务逻辑说明) — `/2794/2802.html`

---

## 1. 快速开始

> 原始路径：`/quickStart/`  
> 相对路径：`quickStart/README.md`  
> JS Chunk：`app.7a5cbccd.js`

## 快速开始

欢迎来到快速开始页面

## 2. Hello World

> 原始路径：`/quickStart/helloworld.html`  
> 相对路径：`quickStart/helloworld.md`  
> JS Chunk：`app.7a5cbccd.js`

## Hello World

北京欢迎您！

## 3. Nice Code

> 原始路径：`/quickStart/nicecode.html`  
> 相对路径：`quickStart/nicecode.md`  
> JS Chunk：`app.7a5cbccd.js`

## Nice Code

这是一段优秀的代码！

## 4. 前端文档

> 原始路径：`/166/`  
> 相对路径：`166/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称   URL
前端知识库   前端知识库
扩展接口    扩展接口

分享链接分享链接

## 5. JSP动态脚本链入

> 原始路径：`/166/338/339.html`  
> 相对路径：`166/338/339.md`  
> JS Chunk：`app.7a5cbccd.js`

## JSP动态脚本链入


## 场景

常用于JSP页面的客户化开发，不修改标准产品前端页面，按照规范将javascript文件放置在对应位置，标准产品JSP页面也能加载到客户化开发的javascript文件。


## 开发示例

下面的过程，我们以新建协同为例，不修改系统的jsp或js文件，通过一个动态引入的js文件，达到替换系统的协同发送按钮的目的。


## 确定页面的ModelAndView

可以访问对应页面，请求中加入ctp_dump_modelAndView参数确定ModelAndView的名称

http://127.0.0.1/seeyon/collaboration/collaboration.do?method=newColl&rescode=F01_newColl&ctp_dump_modelAndView=true


查看Response的Header，ModelAndView.name即为View的名称。

HTTP/1.1 200 OK
Server: Apache-Coyote/1.1
ModelAndView.name: apps/collaboration/newCollaboration
Pragma: No-cache
Cache-Control: no-store
Expires: Thu, 01 Jan 1970 00:00:00 GMT
Content-Type: text/html;charset=UTF-8
Content-Language: zh-CN
Vary: Accept-Encoding


推荐使用Fiddler工具。

至此，我们确定新建协同页面的ModelAndView为apps/collaboration/newCollaboration。


## 建立自定义的JavaScript文件

1、在webapps/seeyon的extend/js目录下，建立与ModelAndView名称相同的子目录（请注意大小写），如

apps/collaboration/newCollaboration


2、创建任意名称的js文件，如

webapps/seeyon/extend/js/apps/collaboration/newCollaboration/replaceButton.js


编写控制逻辑：利用IE的开发人员工具或直接查看源代码，我们可以确定新建协同的发送按钮Id为sendId，因此，我们这样编写replaceButton.js

// 在原有的按钮后面添加我们自己定义的发送按钮
$('#sendId').after('<input id="btnCustomSend" type="button" value="发送"/>');
// 隐藏原发送按钮
$('#sendId').hide();


3、新建的js文件在重启后生效。


## 常见问题

一、我在V8.0SP2及更早的版本，通过动态脚本注入到新建协同页面能生效，但升级到V8.2之后却不生效了？

-- 老版本新建协同JSP动态脚本注入地址
extend\js\apps\collaboration\newCollaboration


原因：新版本新建协同页面不是apps\collaboration\newCollaboration.jsp了，新版本采用pageDesign模板设计器的模式支持多套新建协同页面，JSP地址换成了如下三个页面：

-- V8.1以上新建协同JSP动态脚本注入地址
pageDesigner\template\tpflowNew\0\newCollaboration
pageDesigner\template\tpflowNew\1\newCollaboration
pageDesigner\template\tpflowNew\2\newCollaboration



## 代码实现原理

注：以下只是标准产品实现原理演示，客开无需自行封装。

后端：com.seeyon.ctp.common.web.ExtendJavascriptInteceptor#postHandle，将EXTEND_JS传递给前端：

String parentPath = SystemEnvironment.getApplicationFolder() + "/extend/js/";
String path = parentPath + viewName.replace("raw:", "");
File directory = new File(parentPath);
File file = new File(path);
if (FileUtil.inDirectory(file, directory)) {
    list = this.getListFiles(path, "js", false);
    int size = list.size();
    List<String> l = new ArrayList<String>(size);
    for (String js : list) {
        l.add("extend/js/" + viewName + "/" + js);
    }
    list = l;
}
view.addObject("EXTEND_JS", list);


前端：标准产品的common_footer.jsp公共jsp文件中，实现了解析扩展的url路径，追加到页面中：

<c:if test="${fn:length(EXTEND_JS)>0}">
    <c:forEach var="js" items="${EXTEND_JS}">
        <script type="text/javascript" src="${staticPath}/${js}${ctp:resSuffix()}"></script>
    </c:forEach>
</c:if>


编撰人：chenlin、het


快速跳转



 * JSP动态脚本链入
   * 场景
   * 开发示例
     * 确定页面的ModelAndView
     * 建立自定义的JavaScript文件
   * 常见问题
   * 代码实现原理



分享链接分享链接

## 6. 项目

> 原始路径：`/166/575/578/580.html`  
> 相对路径：`166/575/578/580.md`  
> JS Chunk：`app.7a5cbccd.js`

## 项目

访问地址：点我访问


## 介绍

该网站是本人自主搭建的在线运行组件库，其中有在线运行的功能，平时偶尔也会上去测试一些小demo，感觉还算是有点用在这里分享给大家。


## 使用文档

其实基础使用的话上网站去随便点点就可以清楚了，然后这里有篇文章是专门介绍过使用的，使用文章


## 功能作用

网站不仅仅是在线预览，同时还可以进行选择喜欢的组件后发布自己的组件库在项目中使用


## 组件介绍

现阶段组件有意义的主要有三个：

 * 3d地图组件，利用threejs和贴图达到3d地图的一定操作
 * canvas线条动画，封装了一个点击后可以交互的数据流动的动画
 * 图片处理工具：截取、旋转（支持gif）关键知识：ArrayBuffur

其余组件大多数为一些样式类的，比如：利用preserve-3d的3d css盒子，利用伪类的check选择动画等


## 结尾

其实该网站也可以算公司内部组件交流的地方，有什么好组件也可以直接拿下来用，或者有想法也可以直接在上面写组件。

编撰人：yinyanting、admin




快速跳转



 * 项目
 * 介绍
 * 使用文档
 * 功能作用
 * 组件介绍
 * 结尾



分享链接分享链接

## 7. 1.公用组件的抽离

> 原始路径：`/166/575/578/581/`  
> 相对路径：`166/575/578/581/README.md`  
> JS Chunk：`app.7a5cbccd.js`

## 1.公用组件的抽离

公用组件的封装分为两类，其一是布局样式公用组件的封装，其二是业务组件的封装。公用组件的封装可以提高整体研发团队的开发效率，避免后续改动带来的更多的工作量，尽量将后续工作控制在一定时间范围内。

公用组件的抽离是组件开发思维的核心基本的思想，不仅仅是将组件化开发停留在嵌套组件上，而是从项目整体出发设计公用组件，为项目研发技术团队提供真正可复用能力，为协同开发提供开发基础，最大化技术团队的研发开发效率。


## 1.1 布局样式组件封装

布局样式组件封装：只关注项目中布局样式上共性点，将具有公共样式的布局提取出来。

项目案例：



类似上图中的布局样式在多个页签中出现时，可将其作为公共布局样式的组件封装起来，让布局样式和业务代码解耦，促使研发人员将更多的精力和时间用在业务代码。


## 1.2 业务组件封装

业务组件封装：项目里在功能、交互、样式中有完全相同或相似度在90%以上的页面。

项目案例：



对于在项目上多个页面中会出现相同的页面和功能时我们可以使用将其封装为一个业务组件，提高研发团队的开发效率。


## 1.3 布局样式组件和业务组件的区别

 * 关注点：布局组件更关注布局样式的改变，业务组件更多的关注功能
 * 可引用：布局组件可以被业务组件引用，单业务组一定不会被布局组件引用
 * 范围性：布局组件范围相对业务组件会更小，更底层，业务组件的范围会比布局组件更上层
   编撰人：yinyanting、admin


快速跳转



 * 1.公用组件的抽离
   * 1.1 布局样式组件封装
   * 1.2 业务组件封装
   * 1.3 布局样式组件和业务组件的区别



分享链接分享链接

## 8. Vuex和provide、inject在项目中使用取舍

> 原始路径：`/166/575/578/581/582.html`  
> 相对路径：`166/575/578/581/582.md`  
> JS Chunk：`app.7a5cbccd.js`

## Vuex和provide、inject在项目中使用取舍


## 1.1 vuex全局管理的不二选择

这里使用vuex官网的一句话描述：它采用集中式存储管理应用的所有组件的状态，并以相应的规则保证状态以一种可预测的方式发生变化。

通过官网简介我们提取一下主要关键点，集中式、管理组件状态、可预测的方式

作为SPA前端开发框架，Vue父子组件之间的传值通信使用Props、多个组件之间的计算属性、方法公用一个属性时，vuex是推荐采用的一种状态管理中心。

通过中心管理状态让数据在不同组件之间更有利于管理，数据流向、数据改变、数据计算都形成统一的管理，项目中状态管理相对其他方式来说更清晰。


## 1.2 provide、inject多层嵌套组件通信必备

 * provide：Object | () => Object
 * inject：Array | { [key: string]: string | Symbol | Object }

对于多个嵌套较深的组件来说一层一层通过Props和事$emit传值是一件极其痛苦的事情。

provide和inject数据变更不是响应式的，响应式的数据需要return一个一个响应式的数据。


## 1.3 项目中关于vuex和provide、inject的取舍

 * 关注点: vuex的关注点从整个项目出发，不关注组件之间的嵌套关系，对项目中全局的状态做廷统一管理，provied和inject更关注基础组件之间的传值通信。
 * 响应式：vuex的state，getter都是响应式数据，provide提供的数据可以是响应式也可以不是响应式。
 * 可预测：vuex中mutation负责更改state，通过提交mutation的事件可预测性知晓数据的变化，provide中的数据变更不易被预测，绑定的数据如果是响应式数据，数组，对象的变化不会被监听到。
 * 命名空间：vuex中支持module模式，各个module之间可使用命名空间保持数据隔离，provide中不提供命名空间。
   编撰人：yinyanting、admin


快速跳转



 * Vuex和provide、inject在项目中使用取舍
   * 1.1 vuex全局管理的不二选择
   * 1.2 provide、inject多层嵌套组件通信必备
   * 1.3 项目中关于vuex和provide、inject的取舍



分享链接分享链接

## 9. 1.组件名、重要方法的名称备注的规则

> 原始路径：`/166/575/578/581/583.html`  
> 相对路径：`166/575/578/581/583.md`  
> JS Chunk：`app.7a5cbccd.js`

## 1.组件名、重要方法的名称备注的规则

 * 未规范命名

统一命名后的

组件命名规范：模块 + 实体

事件的名称方式：通过$emit（）的事件已toXXXXX命名，eg: $emit(toEmit, data) 组件内的事件命名：onXXXX eg: onEmit

通过统一事件命名的方式，快速定位事件的流转。


## 2.提高函数使用，避免使用全局变量

 * 尽量避免使用全局变量，使用函数返回数据的方式，减少全局变量带来的维护变量困难

onCheckAllChildrenNode(treeData, status) {
      let depList = []
      function addDept(treeData, status) {
        for (let i = 0; i < treeData.length; i++) {
          if (treeData[i].type === 'Department') {
            treeData[i]['excludeChildDepartment'] = status
            depList.push(treeData[i])
          }
          if (treeData[i].children.length > 0) {
            addDept(treeData[i].children)
          }
        }
      }
      addDept(treeData, status)
      return depList
    },



## 3.多层组件事件使用方法

组件之间事件传递超过三层组件时，可以使用provide方法暴露组件内的方法

// app.vue
provde(){
 return {
  app: ()=> this
 }
     },
    methods: {
 onPanel(data) {
  // 对data做一些处理
 }
     }

one.vue


 methods: {
 onSwitch(data) {
  // 在子组件中触发父组件的方法
  this.app().onPanel(data)
 }
    }


编撰人：yinyanting、admin


快速跳转



 * 1.组件名、重要方法的名称备注的规则
 * 2.提高函数使用，避免使用全局变量
 * 3.多层组件事件使用方法



分享链接分享链接

## 10. 概述

> 原始路径：`/166/575/578/584.html`  
> 相对路径：`166/575/578/584.md`  
> JS Chunk：`app.7a5cbccd.js`

## 概述

首先问大家个问题：

目前在前端开发中需要处理一些异步操作的时候，使用Promise的时候你是否觉得是一种理所当然的习惯性操作呢？ 我们来看下 Promise 出现的时间列表： ES2015 规范新增 Promise ES2018 规范新增 Promise.finally ES2020 规范新增 Promise.allSettled ES2021 规范新增 Promise.any 也就是说在此之前是没有Promise这个东东的，那么没有Promise的时候我们又是怎么处理异步呢？ 方法一：callback 大法 弊端： 1、回调地狱 2、调试链长可读性差

    function getDataByCallback(onSuccess, onError) {

        setTimeout(() => {

            onSuccess && onSuccess(11);

        }, 1000);

        setTimeout(() => {

            onError && onError(22);

        }, 2000);

    }


    getDataByCallback(function onSuccess(result) {

        ~/~/ TODO

        console.log('onSuccess: ', result);

    }, function onError(error) {

        ~/~/ TODO

        console.log('onError: ', error);

    });


方法二：eventbus 大法

弊端：

1、代码跟踪调试麻烦；

2、效率低

    //简易的发布订阅实现

    var eventbus = {

        events: {},

        on(key, handler) {

            if (typeof key !== 'string' || typeof handler !== 'function') {

                throw Error('入参错误');

            }

            this.events[key] = this.events[key] || [];

            this.events[key].push(handler);

        },

        trigger(key, params) {

            var handlerList = this.events[key];

            if (handlerList) {

                for (let i = 0, len = handlerList.length; i < len; i++) {

                    handlerList[i](params);

                }

            }

        }

    }


    var HANDLE_KEYS = {

        GET_DATA: 'getData'

    };


    eventbus.on(HANDLE_KEYS.GET_DATA, function(result) {

        console.log('结果：', result);

    });


    console.log('开始：');

    setTimeout(() => {

        eventbus.trigger(HANDLE_KEYS.GET_DATA, 123);

    }, 2000);



方法三：事件触发类 依托交互、循环检查等等

弊端：

1、业务场景限制

2、效率稳定性不一

因此针对以上问题，以及现阶段前端的快速的发展进程，Promise的出现就很好理解了，当然也不仅仅只是Promise。只是本次我们主要讲Promise的基础和业务中总结的一些使用技巧


## 基础

Promise 英文意思为承诺，大家都知道。那么针对承诺，我们直观的关注点应该就是:

1、为什么事做的承诺

2、当前的承诺状态

3、什么时候兑现承诺

4、兑现承诺做什么，成功了怎么做？失败了怎么做？

针对这种事物的基本逻辑，Promise也将其做了相应的实现，这些大家可能也是基本都了解。

以[[Promise A+>>https://promisesaplus.com/#]]规范为例：

1、为什么事做的承诺（业务主体） executor

2、状态 Pending（等待态）、Fulfilled（成功态）、Rejected（拒绝态）

3、什么时候兑现承诺（执行回调）， executor~-~-> resolve, reject

4、兑现承诺做什么(收集回调).then(onResolve, onReject) .catch(onReject) .finally(all)


## 知识点解析

1、executor 为同步执行，因此在业务开发中使用时，应该对具体的异步方法，是进行直接调用还是提供一个handler，这个需要优先考虑，如下两个场景

    const promiseFactory = value => {

        return new Promise((resolve, reject) => {

            console.log('开始执行 ', item);

            setTimeout(() => {

                resolve(item);

            }, Math.random() * 2000);

        }).then(res => {

            console.log('执行结束', res);

            return res;

        });

    }

    // 这里其实在构建promiseList的时候，每一个executor就已经在执行了

    const executAll = (list) => {

        Promise.all(list);

    }

    const valueList = [1, 2, 3];

    const promiseList = valueList.map(promiseFactory);

    executAll(promiseList);


    // 因此可以将每个Promise异步业务进行handler化封装，后续调用时才执行

    const executAll = (list) => {

        Promise.all(list.map(func => func(~)~)~);

    }

    const valueList = [1, 2, 3];

    const promiseList = valueList.map(value => () => promiseFactory(value));

    executAll(promiseList);


    OR


    const executAll = (list) => {

        const promiseList = list.map(promiseFactory);

        Promise.all(list.map(func => func(~)~)~);

    }

    const valueList = [1, 2, 3];

    executAll(valueList);




## 2、.then()， .catch()， .finally()用法以及注意项

Promise的then(onFulfilled, onRejected)方法主要收集Fulfilled和rejected状态下具体操作 注意事项： 1、promise.then()在调用是才会执行task.Enqueue方法将其放入microtask中 2、onRejected方法只能监听,reject触发和executor方法中抛出的错误，无法监听同级onFulfilled中出现的错误，但是可以监听上级的onFulffiled的错误，如：

    new Promise((resolve, reject) => {

        resolve(11)

       // reject(111)

    }).then(res => {

        console.log('then', res)

        dd

    }, err => {

        console.log('catch',err)

    }).then(() => {


    }, err => {

        debugger

    });


3、返回值问题，分为两种：

（1）、返回值非promise对象，那么会自动转换为Fulfilled状态，并且触发后续注册的onFulfiled回调

（2）、返回值为promise，会触发PromiseResolveThenableJob，分为两步生成一个job microtask，然后转接一个microtask到后面类似于then(onFulfilled)返回一个非promise的值类型

    Promise.resolve()

        .then(() => {

            console.log('promise0')

            return Promise.resolve();

        }).then(() => {

            console.log('sdfs')

        })


    Promise.resolve()

    .then(() => { console.log('promise1') })

    .then(() => { console.log('promise2') })

    .then(() => { console.log('promise3') })

    .then(() => { console.log('promise4') })

    .then(() => { console.log('promise5') })



Promise的catch(onCatch)，onCatch方法会捕获executor中的和之前的then，catch中的所有错误

Promise的finally(onCompleted)，onCompleted回到Fulfilled和Rejected状态都会执行且不会接收数据

3、resolve, reject ，Promise.resolve Promise.reject用法以及注意项

resolve, reject为new Promise(executor)中executor的两个方法参数，类似事件的trigger 主要动作为修改状态、执行相应的回调。特殊情况为resolve参数为promise的情况会触发PromiseResolveThenableJob处理模式，会导致后续then收集的回调延后连个microtask执行，应为会生成一个job 和 同步结果的microtask。具体例子如后面的Promise.resolve讲解

Promise.resolve() 直接返回一个Fulfilled状态的promise实例，其中可接受4种类型参数：

1、参数为promise实例

    const promise1 = new Promise((resolve, reject) => {

        resolve(1);

    });

    const promise2 = Promise.resolve(promise1);

    console.log(promise1 === promise2); ~/~/ true


2、参数为thenable，带有then方法额对象，Promise.resolve() 方法会将这个对象转为Promise对象，然后就立即执行thenable对象的then()方法

3、参数为一个原始值或者不带参数，那么Promise.resolve()返回一个新的状态为Fulfilledd的promise对象 针对resolve参数传递Promise对象，从而从而走A+规范PromiseResolveThenableJob的问题。特殊例子如下：

    new Promise(resolve => {
        let resolvedPromise = Promise.resolve()
        resolve(resolvedPromise)
    }).then(() => {
        console.log('resolvePromise resolved')
    })
    Promise.resolve()
    .then(() => { console.log('promise1') })
    .then(() => { console.log('promise2') })
    .then(() => { console.log('promise3') })
   //但是平时业务使用中，我们不太会去关注两个无关联性的promise的回调执行顺序。
   // Promise.reject方法执行得到一个Rejected状态的Promise对象
    const rejectedPromise = Promise.reject();



## 业务场景中的特殊用例


## 1、业务权限转接

场景： 1、转接、封装其他的异步操作，最常见的需求 2、替换、缓存、传递resolve，reject操作方法，从而达到控制异步操作响应、转移操作能力的目的

    const checkOptions = (options = {}) => {

        return new Promise((resolve, reject) => {

            setTimeout(() => {

                if (options.ok) resolve(options.ok);

                else reject('错误');

            }, 1000);

        });

    }


    const getData = (options) => {

        return new Promise((resolve, reject) => {

            setTimeout(() => {

                resolve('成功')

            }, 1000);

        })

    }


    const getDataHandler = (options = {}) => {

        return checkOptions(options).then(getData)

    }


    getDataHandler({ ok: false }).then(res => {

        console.log(res)

    }).catch(err => {

        console.log('error', err);

    });




## 2、promise列表，队列执行

场景：针对需要顺序执行的业务动作，其中包括promis function。如：有关联先后循序的连续型异步业务操作

    /*

    ~* promise批量串行处理

    *

    ~* @param {array} [arr=[]]

    ~* @param {function} onItemFinish 单项回调函数

    ~* @param {boolean} [isFinishWhenError=false] 为false不会因为单项错误中断串行执行，单项的rejected不抛出，直接放入fulfilled中捕获

    ~* @returns {promise}

    */

    const promiseQueue = (arr = [], onItemFinish, isFinishWhenError = false) => {

        const list = [].concat(arr);

        const isType = hand => Object.prototype.toString.call(hand);

        if(isType(list) !== '[object Array]') throw new TypeError('arr must is a array');


        const isFunction = (func) => isType(func) === '[object Function]';

        const isPromise = (func) => isType(func) === '[object Promise]';

        return list.reduce((nextPromise, currentPromise, index) => {

            return nextPromise.then(result => {

                if (!isPromise(currentPromise) && !isFunction(currentPromise)) throw new TypeError('item must is a function or a promiseFunction');if (!isPromise(currentPromise) && !isFunction(currentPromise)) throw new TypeError('item must is a function or a promiseFunction');


                if(isFunction(currentPromise)) {

                    currentPromise = currentPromise();

                }


                if (isPromise(currentPromise)) {

                    return currentPromise.then((res) => {

                        result.push(res);

                        return result;

                    }).catch(err => {

                        result.push(err);

                        return isFinishWhenError ? Promise.reject(result) : result;

                    });

                } else {

                    result.push(currentPromise);

                    return Promise.resolve(result);

                }

            }).then(function(result) {

                onItemFinish && onItemFinish(result.slice(-1)[0], index);

                return result;

            }).catch(function(result) {

                onItemFinish && onItemFinish(result.slice(-1)[0], index);

                return Promise.reject(result);

            });

        }, Promise.resolve([]));

    };


    let promises = [1, 2, 3, 4, 5, 6].map((item, index) => {

        return () => new Promise((resolve, reject) => {

            console.log('发送请求', item)

            setTimeout(() => {

                ~/~/ if(item !== 3) resolve(item)

                ~/~/ else reject('222');

                resolve(item)

            }, Math.random() * 100);

        });

    });


    const itemCallback = (res) => {

        console.log('请求响应', res);

    }

    promiseQueue(promises, itemCallback, false).then(res => {

        console.log('==', res);

    });




## 3、前置请求，缓存后续队列

1、前置请求场景，如：站点配置、权限校验等等，需要等待某个异步操作完成以后才能执行后续请求，但是又不能限制业务，要做到业务无感知，可并发使用的情况

2、单个业务场景，如：上传文档操作，需要先项服务端申请token然后才能执行上传、转发等待多个并行异步操作

    /*

    * @Author: daipeng7

    * @Date: 2021-12-29 10:26:48

    * @LastEditTime: 2021-12-29 14:13:39

    * @LastEditors: daipeng7

    * @Description: Promise 缓存使用场景demo代码

    * 1、前置请求场景，如：站点配置、权限校验等等，需要等待某个异步操作完成以后才能执行后续请求，但是又不能限制业务，要做到业务无感知，可并发使用的情况

    * 2、单个业务场景，如：上传文档操作，需要先项服务端申请token然后才能执行上传、转发等待多个并行异步操作

    */

    const isType = hand => Object.prototype.toString.call(hand);

    const isFunction = (func) => isType(func) === '[object Function]';

    const isPromise = (func) => isType(func) === '[object Promise]';


    class CacheRequest {

        constructor() {

            this.cacheList  = [];
            this.cache = false;
        }
        invok(func) {
            // 缓存
            if (this.cache) return this._setCache(func);
            // 非缓存
            if (!isFunction(func) && !isPromise(func)) return Promise.resolve(func);
            if (isFunction(func)) func = func();
            if (isPromise(func)) return func;
            else return Promise.resolve(func);
        }
        // 设置缓存，提供了一个对外等待的wrap Promise对象，并且将resolve和reject闭包的方式存入了缓存，等待缓存被执行的时候再来响应调用方
        _setCache(func) {
            console.log('==收集缓存==');
            let handler;
            // 缓存执行handler,最好不要直接缓存func
            if (isFunction(func)) handler = func;
            else if (isPromise(func)) handler = () => handler;
            else handler = () => Promise.resolve(handler);
           const wrapPromise = new Promise((resolve, reject) => {
                this.cacheList.push(() => {
                   return handler().then(resolve).catch(reject);
                });
            });
            return wrapPromise;
        }
        // 执行cache
        invokCache() {
            if (this.cacheList.length && !this.cache) {
                console.log('开始执行缓存');
                const invokList = [ ...this.cacheList ];
                this.cacheList = [];
               invokList.forEach(this.invok.bind(this));
            }
        }
    }
    const request = new CacheRequest();
    // 对外调用方法
    const requestHandler = (fun, prev = false) => {

        const _promise = request.invok(fun).then(res => {

            request.cache = false;

            request.invokCache();

            return res;
        });

        if (prev) request.cache = prev;
        return _promise;
    }
    // 测试数据
    const configRequest = () => {

        return new Promise((resolve, reject) => {

            console.log('执行config');

            setTimeout(() => {

                resolve('config');

            }, 1000);

        }).then(res => {

            console.log('响应config', res);

            return res;

        });

    }
    const asyncList = [1,2,3,4].map(item => {

        return () => new Promise((resolve, reject) => {

            console.log('执行后续异步操作', item);

            setTimeout(() => {

                resolve(item);

            }, Math.random() * 2000);

        }).then(res => {

            console.log('响应后续异步操作', res);

            return res;

        });

    });
    // 并发调用

    requestHandler(configRequest, true);

    asyncList.forEach(requestHandler);



## 总结

Promise使用中的关注点是针对业务封装、转接、执行控制。这三点灵活的组合可以很好的解决业务中可能需要交互、定时器等辅助实现带来的不稳定问题，同时对于代码的可读性也会变得更高。

编撰人：yinyanting、admin




快速跳转



 * 概述
 * 基础
   * 知识点解析
   * 2、.then()， .catch()， .finally()用法以及注意项
   * 业务场景中的特殊用例
     * 1、业务权限转接
     * 2、promise列表，队列执行
     * 3、前置请求，缓存后续队列
 * 总结



分享链接分享链接

## 11. 前言

> 原始路径：`/166/575/578/585.html`  
> 相对路径：`166/575/578/585.md`  
> JS Chunk：`app.7a5cbccd.js`

## 前言

> 俗话说的好：不喜欢折腾造轮子的工程师不是一个合格的工程师。今天就带来最新的小工具轮子，之前的vue组件平台服务器快要到期了，并且也要进入二次开发了，所以暂时可能要无法访问了（应该3月中旬后），现在还没有玩过的大佬可以去看看哦。 点我！

> 今天带来的不仅仅是一个实用的小工具，同时也是一个对于项目规范化开发流程的一个模式，具体是什么模式后面来进行说明。首要目的是：项目开发过程出问题几率减少，这就需要我们对开发以及后续的流程进行规范化的管理，同时也让我们工程师用的舒心。


## 项目工程化

项目工程化，不仅仅在于我们写的代码的可扩展性、可维护性，它更主要的目的是在于如何使我们整个开发流程的高效率、稳定。

> 工程化解决的问题是，如何提高编码、测试、维护阶段的生产效率。

所以作为一个好的工程师我们怎么能没有一个好的工程化概念呢？

到这里大家可以回想一下现在所做项目的整体流程是否清楚，如果清楚可以试想一下以下问题：

 * 新功能开发或bug修复完成后，测试是否能第一时间知道进行测试
 * 测试的代码是否已经是你修改的了，代码是否部署到测试环境
 * 测试完成后合并上线，临时功能紧急下线能否准确进行代码回滚
 * 每次提交是否能准确知道到底提交了什么内容
 * 你的代码是否经常被同事给冲突掉，导致问题出现

这些问题都是我在实际开发中遇到的，那么在工程化概念中咋们的开发、测试流程就会显得没有规范，就很难受。这一难受我就想怎么改，然后就进行思考如何优化这些不规范的东西。（大量文字预警）


## 项目迭代流程

> 这是本人基于现有公司的理解、认识所进行的总结分析得出的流程。



上面的图片解析如下：

 * 通过自动化创建分支，且可以强制限定一个bug或一个需求对应一个分支，减少bug之间的关联（防止一次提交多个bug+多个需求，对于代码回滚来说是噩梦）
 * 开发人员对于提交信息规范化，也可以减少git和任务仓库关联工作量
 * 进行mr请求更便捷，通过命令行即可
 * 通过打tag触发自动化更新，同时也可以自动化生成发版日志让测试进行测试（这里需要说明一下在任务发布的时候其实就已经有了，但是实际操作中经常出现延期和提前的问题，导致开发不能随意完结任务，需要等待发版后再把自己的任务转到测试头上，这样开发可以在提交后直接完成任务进入待验证区，测试通过发版日志选择性的测试）
 * 如果出现某个功能不需要上或者bug修改出错时进行代码回滚可以通过任务信息关联的git提交记录来确认提交内容，同时由于进行了一个分支对应一个bug或需求可以大大减少任务之间的代码相互影响

当然了这么多文字的流程规范，虽然还是不能适合每个项目的开发，但整体来说我觉得应该算是一个标准项目的迭代过程。

> 如果你的工程不适合的话，可以直接了解一下这个下面的工具是否有用。


## 抛砖引“玉”

经过如上的分析我们可以得到一个开发-测试的循环流程，既然开头就说了造了一个轮子，就先来看一下轮子的功能吧，放一个工程md文档的片段。

> 注：现阶段轮子支持的维度是jira + gitlab这一套工作流程。（当然了可以自主修改）

// 自动化commit流程
'lzgit lz / lzgit l'

// 自动获取jira、commit信息
'lzgit commit / lzgit c'

// 修改脚手架基础配置信息
'lzgit config / lzgit cf'

// 提交mr请求
'lzgit mr / lzgit m'

// 自动化push推送
'lzgit push / lzgit p'

// 修改整体配置
'lzgit config / lzgit cf'

// 创建新的开发分支
'lzgit branch / lzgit b'


如果看了以上命令有所不理解的可以专门看下面的关键指令的详细执行流程就可以了解具体功能实现了。


## lzgit commit

本指令会代替以前我们的整体commit流程，这个指令进行了如下运行


## lzgit mr

本指令会自动在gitlab上进行mr请求的发布，运行操作如下


## lzgit branch

本指令会自动创建开发分支，由此指令创建的分支，在提交信息时可以不用进行填写选择


## lzgit lz

本指令是完成开发时的全流程集合，会自动化进行commit、push、mr请求操作


## lzgit push

本指令就是简单的对分支先行进行了pull后再push的操作


## lzgit config

本指令是对一些程序的配置进行修改，较为简单可以尝试一下就明白了


## lzgit

上文其实已经说了这么多关于lzgit的使用和一些流程了，那么这个lzgit到底是什么东西怎么用的呢？就是需要在这说明的了。

总结以下关键几点：

 * 基于node环境
 * 使用ts编写
 * 可以得出使用npm进行包管理
 * 代码托管在gitee上

当然了，虽然我是个前端做出来的东西是基于nodejs的，但是使用不受限制呀，环境安装个nodejs就行了，然后就可以进行使用了。


## 安装命令

> npm install -g lazy-git-cli


## 工具简介

一个辅助进行Git提交、Jira关联、Mr合并请求提交、发版日志生成以及开发分支管理工具，只需要进行简单的配置后生成项目专用的文件配置（如不用分支管理则不用进行配置）

现阶段使用的为大多数公司管理流程：GitLab + Jira , 只要你的公司或项目是利用这个进行敏捷开发的都可以使用该工具


## 工具小结

> 如果真的你认真读到这里了会发现有一个关键的东西工具没有完成，自动化生成发版日志

通过上面的工程化流程介绍可以看出测试是通过发版日志和jira完成列表来进行bug的测试和回归，这样双面确认可以保证我们做完了jira测试可以明确知道哪个jira已经发版了可以开始测试，而哪些没有发版暂时无法测试，保证效率而不会出现测试打回来开发明明已经修改了的jira，只是因为没有部署测试环境。

> 在这简单说明一下，这个轮子暂时局限性比较大，如果真的有人开始使用了我就会把接口进行完善，进行多端的适配，所以暂时功能没有完全完成（其实就是懒）。

> 如果你想用工具的话，麻烦在底部评论一个“小老弟，快去完成xxx”，如：“小老弟，快去完成发版日志生成”

本人：

> 本文主要在于梳理流程和介绍工具，如果想知道整体开发技术，也在评论告诉我哦，立马就出下一篇文章


## 最后

那就在最后的最后把一些地址发布出来供各位大佬审批：

 * npm: https://www.npmjs.com/package/lazy-git-cli
 * gitee: https://gitee.com/beon/lazy-git
 * 安装命令强调一遍： npm install -g lazy-git-cli



编撰人：yinyanting




快速跳转



 * 前言
 * 项目工程化
 * 项目迭代流程
 * 抛砖引“玉”
   * lzgit commit
   * lzgit mr
   * lzgit branch
   * lzgit lz
   * lzgit push
   * lzgit config
 * lzgit
   * 安装命令
   * 工具简介
 * 工具小结
 * 最后



分享链接分享链接

## 12. IE11、10中使用promise中的finally报错

> 原始路径：`/166/575/578/591.html`  
> 相对路径：`166/575/578/591.md`  
> JS Chunk：`app.7a5cbccd.js`

## IE11、10中使用promise中的finally报错

问题描述：在Vue项目中使用promise中使用finally销毁promise实例，发现在IE中会报找不到finally方法。

解决办法

//第一步：安装promise.prototype.finally依赖包
npm i promise.prototype.finally -S

//第二步：在使用promise的js文件中调用shim方法，此时在自动给promise实例添加finally方法

require('promise.prototype.finally').shim()



编撰人：yinyanting、liuyc、admin


快速跳转



 * IE11、10中使用promise中的finally报错



分享链接分享链接

## 13. npm run build时提示error -4048报错

> 原始路径：`/166/575/578/593.html`  
> 相对路径：`166/575/578/593.md`  
> JS Chunk：`app.7a5cbccd.js`

## npm run build时提示error -4048报错



解决方法：先删除使用 rimraf node_modules，在npm install


## npm run build时提示vue-clie-serve报错信息



解决方法：先删除使用 rimraf node_modules，在npm install

编撰人：yinyanting、liuyc、admin




快速跳转



 * npm run build时提示error -4048报错
 * npm run build时提示vue-clie-serve报错信息



分享链接分享链接

## 14. 组件封装原则

> 原始路径：`/166/575/578/596.html`  
> 相对路径：`166/575/578/596.md`  
> JS Chunk：`app.7a5cbccd.js`

## 组件封装原则

一切组件封装的原则都不能脱离为提高编码效率而服务的根本前提。


## 组件封装原则

基础组件：业务基础组件一定遵循单一性编程原则，是项目中会用到基础组件，比如button组件，它的使用场景会遍布到整个项目中。

公共业务组件：公共业务组件一定和业务有强相关性，组件内部的处理逻辑是根据业务场景的不同需要调整，在使用过程中范围比基础组件要小。

公共布局组件：公共布局组件只关注布局样式的展现，其内部的更关注样式布局的处理，在使用过程中会被很多页面引用作为基本布局框架。


## 业务组件分装原则

高内聚低耦合：高内聚是指组件在项目中封装时要考虑的第一原则，业务组件的封装时一定是项目中有3处以上的位置有相同的页面交互，

业务逻辑。组件内部的会对页面交互做处理，会对业务逻辑做处理。其可以被多次复用，提高研发效率。

编撰人：yinyanting、liuyc、admin




快速跳转



 * 组件封装原则
   * 组件封装原则
   * 业务组件分装原则



分享链接分享链接

## 15. Vue项目在IE10中包语法错位

> 原始路径：`/166/575/578/597.html`  
> 相对路径：`166/575/578/597.md`  
> JS Chunk：`app.7a5cbccd.js`

## Vue项目在IE10中包语法错位

问题描述：在解决问题1时，vue项目在IE10会报语法错误，导致项目加载失败。



解决办法：在transpileDependencies加入报错的模块，包括node_modules中的模块

//在vue.config.js配置
module.exports = {
 productionSourceMap: false,
   // node_modules依赖项es6语法未转换问题
   transpileDependencies: [
      'vue-virtual-scroller'
 ]
}


编撰人：yinyanting、liuyc、admin


快速跳转



 * Vue项目在IE10中包语法错位



分享链接分享链接

## 16. Vue项目在IE10浏览器环境下页面加载空白

> 原始路径：`/166/575/578/598.html`  
> 相对路径：`166/575/578/598.md`  
> JS Chunk：`app.7a5cbccd.js`

## Vue项目在IE10浏览器环境下页面加载空白

问题描述：基于Vue@2+版本的项目在IE10打开后浏览器没报错，页面展示空白 解決方法：

//第一步：安装@babel/polfill 
npm i @babel/polfill --save-dev
//或者 npm i @babel/polfill -D

//第二步：在项目的主入口文件中main.js引入babel
import '@babel/polyfill';

//第三步：配置在babel.config.js
module.exports = {
 presets: [
  [
   '@vue/app',
   {
    useBuiltIns: 'entry'
   }
  ]
 ],
};


编撰人：yinyanting、liuyc、admin


快速跳转



 * Vue项目在IE10浏览器环境下页面加载空白



分享链接分享链接

## 17. 1. 真实案例

> 原始路径：`/166/575/578/926.html`  
> 相对路径：`166/575/578/926.md`  
> JS Chunk：`app.7a5cbccd.js`

## 1. 真实案例




## 1.1 关键字

运行缓慢、切换页面、系统卡顿


## 1.2 初步分析

如果你有类似的处理经验，那么会很容易猜到可能是因为存在着内存泄漏，且大概率为未手动清除定时器，最终造成内存溢出，导致了整个页面崩溃、js 主线程一直被长时间占用


## 1.3 具体分析

但大多数时候，我们一开始并不知道问题可能的主要原因。不过根据关键字以及问题描述，我们可以大概推测出，这应该是一个性能优化相关的问题

关于性能各方面的情况，我们可以借助浏览器自带的功能进行查看


## 1.3.1 操作步骤

打开开发者工具（F12） 切换至 Performance 工具 勾选 Memory 选项 点击左上角第一个黑色小圆点，进行录制 对页面进行正常的操作 点击 stop 停止按钮 录制完成，生成 profile 性能报告 分析性能报告


## 1.3.2 操作动画




## 1.4 性能排查


## 1.4.1 内存走势分析

确定是否存在内存泄漏

## 1.4.1.1 具体操作

页面正常操作，5秒之后，切换到别的页面，不做操作，停留5秒，最后停止录制

## 1.4.1.2 异常情况



可以看到，内存的下限是在不断的升高，这里大概率发生了内存泄漏

## 1.4.1.3 正常情况



当内存不再被使用时，会被 GC 回收，不会发生内存泄漏


## 1.4.2 内存泄漏点分析

确定存在内存泄漏后，进一步定位泄漏的源头

## 1.4.2.1 操作步骤

打开开发者工具（F12） 切换至 Memory 工具 点击左上角第一个黑色小圆点，记录下当前的堆内存快照（heap snapshot） 在页面上进行操作，特别是可能发生内存泄漏的操作 重复执行几遍步骤3、4，直至结束 找到顶栏的 All objects, 切换至 Objects allocated between snapshots 1 and 2（也可以选择其他的） 切换后，能看到两个快照之间新生成的对象。选择其中一项点开，看看它的 retaining tree 里面保留了哪些对象没有被释放

## 1.4.2.2 关键词解释

Shallow size：这是对象自身占用内存的大小。通常只有数组和字符串的 Shallow Size 比较大 Retain size：这是将对象本身连同其无法从 GC 根到达的相关对象一起删除后释放的内存大小。因此，如果Shallow Size = Retained Size，说明基本没怎么泄漏。而如果 Shallow Size < Retained Size，就需要多加注意了 closure：函数闭包持有的内存引用 array, string, number, regex：包含着一系列对象，这些对象的属性上有对应类型变量的引用 compiled code：V8引擎为了加快运行速度，会对代码进行一次编译，指与编译后的代码相关联的内存 Detached HTMLDivElement：代码里对指定类型 Dom 节点的引用

## 1.4.2.3 操作动画



## 1.4.2.4 原因分析



类似于 setInterval 的源码实现：

function setInterval (fn, time) {


let timer;   function interval () {      fn();      timer = setTimeout(interval, time);    }    setTimeout(interval, time);   return timer; } 可以看出这里是一个动画定时器的场景，但并未在组件卸载时，手动清除定时器，导致定时器中的函数一直在执行，直到刷新或者关闭页面才会停止。这是一个很常见的内存泄漏场景


## 2. 内存溢出

当内存泄漏严重到超过一定阈值时，就会造成内存溢出，从而导致程序崩溃


## 2.1 V8引擎的内存限制

默认情况下，V8引擎在 64 位系统下最多只能使用约 1.4GB 的内存，在 32 位系统下最多只能使用约 0.7GB 的内存。具体视浏览器的版本而定

所以在V8引擎中，对内存的使用并不是无限制的。内存泄漏、内存溢出也必然会导致性能问题

不过，在 node 端，V8引擎允许我们可手动地调整内存限制大小，但是需要在初始化时进行配置


## 2.2 内存限制原因

V8引擎的设计之初，只是作为浏览器端 JavaScript 的执行环境。在浏览器端其实很少会遇到使用大量内存的场景，因此也就没有必要将最大内存设置得过高 垃圾回收机制：垃圾回收本身是一件非常耗时的操作。假设V8的堆内存为1.5G，那么做一次小的垃圾回收需要50ms以上（这已经是一个 long task 了），而做一次非增量式回收甚至需要1s以上，可见其耗时之久。因此如果内存使用过高，那么必然会导致垃圾回收的过程缓慢 JS 单线程机制：垃圾回收的过程会阻碍主线程逻辑的执行，导致浏览器一直处于等待的状态，同时会失去对用户的响应，影响到应用程序的性能，直到垃圾回收结束后才会再次执行 JS 逻辑 基于以上几点，V8引擎为了减少对应用程序的性能造成的影响，采用了一种比较粗暴的手段，那就是直接限制堆内存的大小

所以当程序在申请内存时，系统已经不能再分配出足够的内存空间供其使用，这时就会抛出内存溢出的错误


## 3. 垃圾回收

栈内存：随着执行上下文在执行环境栈中被弹出，其中所定义和使用的变量也会随之被释放，垃圾回收很容易实现 堆内存：V8的垃圾回收策略主要是基于分代式垃圾回收机制，其根据对象的存活时间进行不同的分代，然后对不同的分代采用不同的垃圾回收算法 3.1 V8的堆内存结构 新生代（new_space）：大多数的对象刚开始都会被分配在这里，这个区域相对较小但是垃圾回收特别频繁。该区域被分为两半，一半用来分配内存，另一半用于在垃圾回收时将需要保留的对象复制过来 老生代（old_space）：新生代中的对象在存活一段时间后，就会被转移到老生代中。相对于新生代，老生代的垃圾回收频率较低。老生代又分为老生代指针区和老生代数据区，前者包含大多数可能存在指向其他对象的指针的对象，后者只保存原始数据对象 大对象区（large_object_space）：存放体积超越其他区域大小的对象。每个对象都会有自己的内存，垃圾回收不会移动大对象区 代码区（code_space）：代码对象，会被分配在这里，唯一拥有执行权限的内存区域 map 区（map_space）：存放 Cell 和 Map ，每个区域都是存放相同大小的元素，结构简单 垃圾回收主要发生在新生代和老生代


## 3.2 新生代垃圾回收

新生代主要用于存放存活时间较短的对象。由两个 semispace（半空间）构成的，内存最大值在64位系统上为32MB，在32位系统上为16MB


## 3.2.1 垃圾回收算法

新生代的垃圾回收过程主要采用了 Scavenge 算法，是一种典型的牺牲空间换取时间的算法

在具体实现中，主要采用了 Cheney 算法，它将新生代一分为二，即 semispace（半空间），其中处于激活状态的区域为 From 空间，未激活的区域为 To 空间。这两个空间，始终只有一个处于使用状态，另一个处于闲置状态

程序中声明的对象首先会被分配到 From 空间，当进行垃圾回收时，如果 From 空间中尚有存活对象，则会被复制到 To 空间进行保存，非存活的对象会被自动回收。当 From 空间中的所有非存活对象被清除之后，From 空间和 To 空间完成一次角色互换：From 空间会变为新的 To 空间，原来的 To 空间则会变成新的 From 空间


## 3.2.2 垃圾回收过程

基于以上算法，流程图如下：

假设在 From 空间中分配了三个对象 A、B、C

第一次垃圾回收时，对象 A 已经没有其他引用，则表示可以对其进行回收；对象 B、C 依旧处于活跃状态，因此会被复制到 To 空间中进行保存

清除 From 空间中的所有非存活对象

From 空间和 To 空间完成一次角色互换

在 From 空间中分配了一个新的对象 D

第二次垃圾回收时，对象 D 已经没有其他引用，则表示可以对其进行回收；对象 B、C 依旧处于活跃状态，再次被复制到 To 空间中进行保存

再次清除 From 空间中的所有非存活对象

From 空间和 To 空间继续完成一次角色互换

通过以上的流程图，可以很清楚地看到，Scavenge 算法主要就是将存活对象在 From 空间和 To 空间之间进行复制，同时完成两个空间的角色互换

因此该算法的缺点也比较明显，就是浪费了一半的内存用于复制


## 3.3 对象晋升


## 3.3.1 晋升概念

对象从新生代转移到老生代的过程


## 3.3.2 晋升条件

对象是否经历过一次 Scavenge 算法：通过检查该对象的内存地址来进行判断 To 空间的内存占比是否已经超过 25%：原因是因为 To 空间在经历过一次 Scavenge 算法后，会和 From 空间完成角色互换，变为了 From 空间，后续的内存分配都是在 From 空间中进行的。如果内存使用过高甚至溢出，则会影响后续对象的分配。因此超过此限制之后对象会直接晋升


## 3.3.3 晋升流程




## 3.4 老生代垃圾回收

在老生代中，因为管理着大量的存活对象，如果依旧使用 Scavenge 算法的话，很明显会浪费一半的内存，因此 Scavenge 算法不适合老生代


## 3.4.1 垃圾回收算法

在早前有一种算法叫做引用计数，该算法的原理比较简单，就是计算对象的引用次数。当引用次数为0时，则该对象就会被视为垃圾并被回收。但如果对象之间存在循环引用，则无法被回收，导致内存泄漏

截至2012年所有的现代浏览器均放弃了这种算法，转而采用新的 Mark-Sweep（标记清除）和 Mark-Compact（标记整理）算法等

## 3.4.1.1 标记清除

分为了标记和清除两个阶段。在标记阶段，会遍历堆中所有的对象，然后标记活着的对象；在清除阶段，会将非存活的对象进行清除

根列表：

全局对象 函数的参数和局部变量 当前嵌套调用链上的其他函数的参数和变量

## 3.4.1.1.1 具体步骤

垃圾回收器会在内部构建一个根列表 然后，从所有根节点出发，遍历其可以访问到的子节点，并将其标记为活动的。根节点不能到达的地方即为非活动的，将会被视为垃圾 最后，垃圾回收器将会释放所有非活动的内存块，并将其归还给操作系统

## 3.4.1.1.2 演示动画

 1. 



 2. 



 3. 



## 3.4.1.2 标记整理

## 3.4.1.2.1 内存碎片化

因为非存活的对象的内存地址可能不是连续的，所以在标记清除之后，内存空间可能会出现不连续的状态，这就是内存碎片化

它会导致如果后面需要分配一个大的对象，虽然有很多空闲内存，但是是不连续的，不足以分配的情况下，就会提前触发垃圾回收，而这次垃圾回收其实是没有必要的

## 3.4.1.2.2 整理过程

将活动的对象往堆内存的一端进行移动，移动完成后再清理掉边界外的全部内存。流程图如下：

假设在老生代中有 A、B、C、D 四个对象

在标记阶段，将对象 A 和对象 C 标记为活动的

在整理阶段，将活动的对象往堆内存的一端进行移动

在清除阶段，将活动对象左侧的内存全部回收

## 3.4.1.3 增量标记

一般来说，老生代会保存大量存活的对象，如果在标记阶段将整个堆内存遍历一遍，这将是一个耗时的过程，同时也会阻塞主线程的执行，这势必会导致性能问题

因此，为了减少垃圾回收带来的停顿时间，V8引擎引入了 Incremental-Marking（增量标记）的算法

即将原本需要一次性遍历堆内存的操作改为增量标记的方式：先标记堆内存中的一部分对象，然后暂停，将执行权重新交给 JS 主线程，待主线程任务执行完毕后，再从原来暂停标记的地方继续标记，直到标记完整个堆内存。这个算法其实有点像 React 框架中的 Fiber 架构

## 3.4.1.4 其他算法

V8引擎后续又引入了 Lazy-Sweeping（延迟清理）和 Incremental-Compaction（增量整理），让清理和整理的过程也变成增量式的

同时，为了充分利用多核 CPU 的性能，也将引入并行标记和并行清理，进一步地减少垃圾回收对主线程的影响，为应用提升更多的性能


## 4. 内存泄漏场景（重点）

在我们写代码的过程中，很多时候都不太需要关注内存泄漏，因为浏览器和大部分的前端框架在底层已经帮我们处理了常见的内存泄漏问题

虽然V8引擎的垃圾回收机制能回收绝大部分的垃圾内存，但是如果是因为代码疏忽，这样还是存在回收不了的情况

所以我们需要了解一些常见的内存泄漏场景，遇到内存泄漏问题时可以先自查一遍常见场景，能解决日常开发中遇到的大多数内存泄漏问题


## 4.1 意外的全局变量

创建的变量无形地挂载到 window 全局对象上


## 4.1.1 示例

在全局作用域中以 var 声明的方式创建一个变量 var a = 1; // 等价于 window.a = 1 在函数作用域中不以任何声明的方式创建一个变量 function fn() {    a = 1; // 等价于 window.a = 1 } this 指向，一种比较隐蔽的方式 function fn() {   this.a = 1; } fn(); // 此时 this 指向 window，等价于 window.a = 1


## 4.1.2 解决方案

全局变量使用完毕后可以将其设置为 null 从而触发垃圾回收


## 4.2 定时器

常见的定时器 setTimeout、setInterval、setImmediate、requestAnimationFrame、requestIdleCallback，在使用结束后（如组件卸载、离开页面时），务必手动清除定时器


## 4.3 事件监听器

监听器回调函数中的内存都是没法回收的（浏览器会认为这是必须的内存，不是垃圾内存）

Performance 里，监听器数量会持续上升


## 4.3.1 解决方案

当组件卸载、离开页面时，务必手动移除事件监听器

注意：

// 存在内存泄漏的代码

mounted() {


window.addEventListener('resize', debounce(this.fn, 100)); },

beforeDestroy() {


window.removeEventListener('resize', debounce(this.fn, 100)); } 乍一看好像没问题，但其实每次调用 debounce(this.fn, 100)时，都会返回一个新的函数，导致 addEventListener 和 removeEventListener 方法中传入的回调函数已经不是同一个回调函数，事件监听器没有被正确地移除，存在内存泄漏

// 改进后的代码

mounted() {


this.debounceFn = debounce(this.fn, 100);   window.addEventListener('resize', this.debounceFn); },

beforeDestroy() {


window.removeEventListener('resize', this.debounceFn); }


## 4.4 闭包

闭包和作用域链有关


## 4.4.1 核心概念

自由变量：在函数中使用的，但既不是函数的参数，也不是函数的局部变量的变量

闭包是指创建它的上下文已经销毁，但它仍然存在（比如函数从父函数中返回），并且在代码中使用了自由变量的函数

所以由于存在变量引用，导致变量无法回收，会一直存在于执行环境栈，造成内存泄漏


## 4.4.2 示例

function fn () {


const local = 1;   return function () {      console.log(local);    } } const func = fn(); func(); // 如果不调用返回的函数，就会造成内存泄漏


## 4.4.3 解决方案

调用返回的函数，执行结束后，该函数的执行上下文会被弹出执行环境栈，随之引用的变量也会被释放


## 4.5 DOM 引用

页面上的 DOM 都是占用内存的


## 4.5.1 示例

const button = document.getElementById('button');

document.body.removeChild(button); // 或者 document.body.removeChild(document.getElementById('button'));

button = null; // 如果不再手动置为 null，就会造成内存泄漏


将 DOM 对象赋值给一个变量后（内存指向是一样的），虽然在页面上移除了该元素，但内存指向换为了赋予的变量，内存占用还是存在的，造成内存泄漏


## 4.5.2 解决方案

将变量再手动置为 null


## 4.6 弱引用


## 4.6.1 概念

垃圾回收的过程中，不会将键名对该对象的引用考虑进去，只要所引用的对象没有其他引用了，垃圾回收器就会释放该对象所占用的内存


## 4.6.2 示例

// 存在内存泄漏的代码

const map = new Map();
const obj = { value: 1 };

map.set(obj, 1);

obj = null; // 虽然 obj 手动置为了 null，但是 map 的一个健值引用着该对象，内存还是占用的，造成内存泄漏

// 改进后的代码

const map = new Map();
const obj = { value: 1 };

map.set(obj, 1);

map.delete(obj);
obj = null;

// 更便捷的方式

const map = new WeakMap();
const obj = { value: 1 };

map.set(obj, 1); // 内存回收不会考虑到这个引用是否存在

obj = null;



## 4.6.3 解决方案

在 ES6 中新增了两个有效的数据结构 WeakMap 和 WeakSet，就是专门为了解决内存泄漏问题而诞生的。其表示弱引用，它的键名所引用的对象均是弱引用

这也就意味着，我们不需要关心其中键名对其他对象的引用，也不需要手动地清除引用

注意：但也不能乱用，因为二者的键名只能为对象


## 4.7 console

因为打印后的对象需要支持在控制台上查看，所以传递给 console 方法的对象是不能被垃圾回收的


## 4.7.1 解决方案

避免在生产环境用 console 打印对象

编撰人：liuyc


快速跳转



 * 1. 真实案例
   * 1.1 关键字
   * 1.2 初步分析
   * 1.3 具体分析
     * 1.3.1 操作步骤
     * 1.3.2 操作动画
   * 1.4 性能排查
     * 1.4.1 内存走势分析
       * 1.4.1.1 具体操作
       * 1.4.1.2 异常情况
       * 1.4.1.3 正常情况
     * 1.4.2 内存泄漏点分析
       * 1.4.2.1 操作步骤
       * 1.4.2.2 关键词解释
       * 1.4.2.3 操作动画
       * 1.4.2.4 原因分析
 * 2. 内存溢出
   * 2.1 V8引擎的内存限制
   * 2.2 内存限制原因
 * 3. 垃圾回收
   * 3.2 新生代垃圾回收
     * 3.2.1 垃圾回收算法
     * 3.2.2 垃圾回收过程
   * 3.3 对象晋升
     * 3.3.1 晋升概念
     * 3.3.2 晋升条件
     * 3.3.3 晋升流程
   * 3.4 老生代垃圾回收
     * 3.4.1 垃圾回收算法
       * 3.4.1.1 标记清除
         * 3.4.1.1.1 具体步骤
         * 3.4.1.1.2 演示动画
       * 3.4.1.2 标记整理
         * 3.4.1.2.1 内存碎片化
         * 3.4.1.2.2 整理过程
       * 3.4.1.3 增量标记
       * 3.4.1.4 其他算法
 * 4. 内存泄漏场景（重点）
   * 4.1 意外的全局变量
     * 4.1.1 示例
     * 4.1.2 解决方案
   * 4.2 定时器
   * 4.3 事件监听器
     * 4.3.1 解决方案
   * 4.4 闭包
     * 4.4.1 核心概念
     * 4.4.2 示例
     * 4.4.3 解决方案
   * 4.5 DOM 引用
     * 4.5.1 示例
     * 4.5.2 解决方案
   * 4.6 弱引用
     * 4.6.1 概念
     * 4.6.2 示例
     * 4.6.3 解决方案
   * 4.7 console
     * 4.7.1 解决方案



分享链接分享链接

## 18. 1、corejs相关的错误，如下图

> 原始路径：`/166/575/589/927.html`  
> 相对路径：`166/575/589/927.md`  
> JS Chunk：`app.7a5cbccd.js`

## 1、corejs相关的错误，如下图



解决办法： 1、删除cap-front、以及子级所有的node_modules： rm -rf node_modules/ rm -rf */node_modules/ 2、在父级重新安装：yarn install --ignore-engines


## 2、cap-front 外层yarn install 报错，如下图



解决方案： 切换node版本为12.19.0 然后执行yarn install --ignore-engines


## 3、FATAL ERROR: CALL_AND_RETRY_LAST Allocation failed - JavaScript heap out of memory

解析：node内存不足

解决：运行setx NODE_OPTIONS --max_old_space_size=10240后关闭cmd再重新打开


## 4、错误：rror loading PostCSS config: Loading PostCSS Plugin failed: Unknown browser query> 1%

解析：browserlist相关，暂未查询到具体原因

解决：删除.browserslistrc中的内容后正常。


## 5、错误：vue-style-loader!css-loader?{"minimize":false,"sourceMap":false}!.

解析：sass找不到

解决：cd到node_module中，运行npm rebuild node-sass，再cd回工程中，运行npm update。


## 6、错误：These dependencies were not found:

*core-js/modules/es.array.concat.js in ./node_modules/cache-loader/dist/cjs.js??ref--12-0

解析：core-js组件异常

解决：删除node-moduls中的core-js、core-js-compat、core-util-js。然后cd到工程中npm i core-js --save


## 7错误：编译form-mobile时报错 m_unflow

解析：新版本oa，依赖yarn

解决：cap-front目录 执行npm i -g yarn 再执行yarn install --ignore-engines


## 8错误：Error occurred while trying to proxy request

解析：跨域错误

解决：配置proxy，增加secure: false 以及 https:true




## 9、错误：启动成功后，页面访问404

解析：访问源ip不通过。

解决：配置proxy，增加changeOrigin:true



编撰人：liuyc




快速跳转



 * 1、corejs相关的错误，如下图
 * 2、cap-front 外层yarn install 报错，如下图
 * 3、FATAL ERROR: CALLANDRETRY_LAST Allocation failed - JavaScript heap out of memory
 * 4、错误：rror loading PostCSS config: Loading PostCSS Plugin failed: Unknown browser query > 1%
 * 5、错误：vue-style-loader!css-loader?{"minimize":false,"sourceMap":false}!.
 * 6、错误：These dependencies were not found:
 * 7错误：编译form-mobile时报错 m_unflow
 * 8错误：Error occurred while trying to proxy request
 * 9、错误：启动成功后，页面访问404



分享链接分享链接

## 19. 引入变化

> 原始路径：`/166/575/606/607.html`  
> 相对路径：`166/575/606/607.md`  
> JS Chunk：`app.7a5cbccd.js`

## 引入变化

#引入由于自带的vue、vuex所以要在webpack中进行配置排除

在vuecli3中

configureWebpack: {
  externals: {
   'vue': 'window.Vue',
   'fiber': 'window.Fiber'
  }
 }


在webpack中
  externals: {
   'vue': 'window.Vue',
   'fiber': 'window.Fiber'
  }



##使用方式

#import Vue from 'vue'
import * as Fiber from 'fiber'##

Vue.use(Fiber, {
     icon: ['v5', 'cap']
})



其中icon为图标库引入，v5为基础图标库，cap为cap图标库，请按需使用

自带国际化

由于基础组件内部的国际化和i18n不相关联，且原基础上没有暴露出api可以修改，所以在app最外层都需要进行套壳处理，ant官网利用该组件类似原理，然后国际化不需要引入内置了，所以local参数为string，可选值有  zh_CN、zh_TW、en三种，可直接绑定headerjs中的_locale值

使用代码如下所示

// 在组建的template中
<a-config-provider locale="zh_CN">
    <App ></App>
</a-config-provider>

// 利用render函数的jsx
render: () => (
<a-config-provider locale="zh_CN">
    <App ></App>
</a-config-provider>
)

// 或者利用render函数直接渲染
render: (h) => {
  return h('a-config-provider', {
    props: {
      locale: window._locale
    }
  }, [h(App)])
} 


编撰人：yinyanting、admin


快速跳转



 * 引入变化



分享链接分享链接

## 20. 常规使用

> 原始路径：`/166/575/606/611.html`  
> 相对路径：`166/575/606/611.md`  
> JS Chunk：`app.7a5cbccd.js`

## 常规使用

使用ctpui2.0、ctpui3.0、ctpui4.0的页面可以使用这种方式调用选人组件

$.selectPeople({
    // 选人参数
    type:'selectPeople',
    panels:'Department,Post,Team,Node,BusinessDepartment',
    selectType:'Member,Node',
    maxSize:1,
    minSize:1,
    params : {
        // 已选数据回填
        value: "Member|12121,Department|2313",
        text:"树琦、信创中心"
    },
    callback:function(ret){
     // 选人确定回调
    }
})


使用完整示例代码

 {{code language="html"}}<%--
 Author shuqi
 Rev
 Date: 2022-03-09 22:46
 
 Copyright (C) 2022 Seeyon, Inc. All rights reserved.
 
 This software is the proprietary information of Seeyon, Inc.
 Use is subject to license terms.
 @company seeyon.com
 @since V5 V8.1SP1
 @author shuqi
--%>
<%@ page contentType="text/html;charset=UTF-8" language="java" %>
<!DOCTYPE html>
<html>
<head>
<%@include file="/WEB-INF/jsp/common/common_header.jsp" %>
 <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
 <meta name="renderer" content="webkit|ie-comp|ie-stand">
 <title>ctpui 选人测试代码</title>
</head>
<body>
</body>
<%@include file="/WEB-INF/jsp/common/common_footer.jsp" %>
<script>
$(function(){
 $.selectPeople({
 type:'selectPeople',//固定
 panels:'Department,Post,Team,Role',//定义显示的页签
 selectType:'Member,Department',//定义可以选择那些类型的数据
 params : {
 // 已选数据回填
 value: "Member|12121,Department|2313",
 text:"树琦、信创中心"
 },
 callback:function(ret){
 // 选人确定回调
 console.log(ret.text);//"树琦、信创中心"
 console.log(ret.value);//"Member|12121,Department|2313"
 }
 })
});
</script>
</html>


1.0.1 Comp组件调用

这种使用方式和上一种是一样，只是页面渲染、事件绑定有ctpui自动完成。同样如果你愿意也可以动态生成 input框，设置好属性并使用$("jQuerySelector").compThis();

简单示例如下:

<input
 type="text" 
 class="comp" //固定
 comp="type:'selectPeople',panels:'Department,Post,Team,Role',selectType:'Member,Department'" // 传入选人参
数
/>


动态组件示例：

$(function(){
 var $input = $("<input type='text' id='selectorgDemo1'/>");
 $input.addClass("comp");
 
 $input.attr("comp","type:'selectPeople',panels:'Department,Post,Team,Role',selectType:'Member,Department'");
 $("body").append($input);
 $input.compThis();
});



完整的页面示例：

<%--
 Author shuqi
 Rev
 Date: 2022-03-09 22:46
 
 Copyright (C) 2022 Seeyon, Inc. All rights reserved.
 
 This software is the proprietary information of Seeyon, Inc.
 Use is subject to license terms.
 @company seeyon.com
 @since V5 V8.1SP1
 @author shuqi
--%>
<%@ page contentType="text/html;charset=UTF-8" language="java" %>
<!DOCTYPE html>
<html>
<head>
 <%@include file="/WEB-INF/jsp/common/common_header.jsp" %>
 <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
 <meta name="renderer" content="webkit|ie-comp|ie-stand">
 <title>ctpui 选人测试代码</title>
</head>
<body>
<input
 type="text"
 class="comp"
 comp="type:'selectPeople',panels:'Department,Post,Team,Role',selectType:'Member,Department'"
/>
</body>
<%@include file="/WEB-INF/jsp/common/common_footer.jsp" %>
<script>
$(function(){
 var $input = $("<input type='text' id='selectorgDemo1'/>");
 $input.addClass("comp");
 
$input.attr("comp","type:'selectPeople',panels:'Department,Post,Team,Role',selectType:'Member,Department'");
 $("body").append($input);
 $input.compThis();
});
</script>
</html>


1.0.1 V3x框架使用

如果你的页面使用的是v3x老框架，同样也可以使用选人。PS:v3x属于过时的老页面，建议尽快改完新框架 1、引入v3x命名空间

<%@ taglib uri="http://v3x.seeyon.com/taglib/core" prefix="v3x"%>


2、申明选人组件 提供的参数不全，可以通过扩展参数的方式设置。

<v3x:selectPeople
 id="manager"
 showMe="true"
 panels="Department,Post,Level,Team"
 selectType="Department,Post,Level,Team"
 memberId=""
 departmentId=""
 postId=""
 levelId=""
 maxSize="1"
 minSize="1"
 selectNode4EdocWorkflow=""
 showAllAccount=""
 include=""
 originalElements="Member|123"
 jsFunction="setBulPeopleFields(elements,'managerUserIds','managerUserNames')"
 maxSize="50"
></v3x:selectPeople>



3、扩展参数

如果需要设置全部参数，可以添加全局变量： 参数名_组件Id = xxx_ 如 var onlyLoginAccount_manager=true

//支持的扩展参数
['accountId', 'departmentId', 'memberId', 'postId', 'levelId', 'elements', 'showOriginalElement', 
'excludeElements', 'isNeedCheckLevelScope', 'onlyLoginAccount', 'showAccountShortname', 
'showConcurrentMember', 'hiddenPostOfDepartment', 'hiddenRoleOfDepartment', 'hiddenMetadataOfDepartment', 
'onlyCurrentDepartment', 'showDeptPanelOfOutworker', 'unallowedSelectEmptyGroup', 'showTeamType', 
'hiddenOtherMemberOfTeam', 'hiddenAccountIds', 'isCanSelectGroupAccount', 'showAllOuterDepartment', 
'hiddenRootAccount', 'hiddenGroupLevel', 'showDepartmentsOfTree', 'showDepartmentsNoChildrenOfTree', 
'hiddenSaveAsTeam', 'hiddenMultipleRadio', 'showAdminTypes', 'includeElements', 'extParameters', 
'showSecondMember', 'isAllowContainsChildDept', 'isCheckInclusionRelations', 'showRecent', 
'notShowAccountRole']
//示例
var onlyLoginAccount_manager=true;



1.0.1 Vue场景使用

vue要使用选人需要引入： ${contextpath}/common/js/selectOrgSdk.js

selectOrgSdk.showSelectOrg({
 panels: 'Department,JoinOrganization',
 selectType: 'Member',
 minSize: 0,
 onlyLoginAccount: true,
 targetWindow: getA8Top(),
 params: {
 value: _selectRoleIds
 },
 callback: function(ret) {
 // 选人确定回调
 console.log(ret.text);//"树琦、信创中心"
 console.log(ret.value);//"Member|12121,Department|2313"
 }
});



1.0.1 Vjoin使用

$.SeeyonSelectPeople({
 panels: 'Department,JoinOrganization',
 selectType: 'Member',
 minSize: 0,
 onlyLoginAccount: true,
 targetWindow: getA8Top(),
 params: {
 value: _selectRoleIds
 },
 callback: function(ret) {
 $(thisDom).val(ret.text);
 $(thisDom).parent().children(":first").val(ret.value);
 }
});



 2. 选人界面参数



编撰人：yinyanting、admin




快速跳转



 * 常规使用



分享链接分享链接

## 21. 关于fiber切换新引入方案

> 原始路径：`/166/575/606/618.html`  
> 相对路径：`166/575/606/618.md`  
> JS Chunk：`app.7a5cbccd.js`

## 关于fiber切换新引入方案

引入前说明：

新方案会自动引入国际化以及fiber的文件，需要自行引入headerJs，默认自动导入会导入到headerJs后面

新引入方案需要修改的步骤如下

1、新引入.npmrc文件[[attach:.npmrc||target="_blank"]]，放入项目根目录下(注意：下载下来有可能没有带点，名字是 .npmrc缺少的需要自己添加)。

2、安装依赖npm i ~-~-save-dev @fiber/i18n-webpack-plugin (需要注意，请查看版本，如有bate后缀请勿使用)

3、第三步是正式引入，有两种方案，webpack中添加plugins，为上诉所安装依赖，可参考如下代码

方案1：自动注入

const I18nWebpackPlugin = require('@fiber/i18n-webpack-plugin');

module.exports = {
  plugins: [
    new I18nWebpackPlugin()
  ]
}


方案2：手动注入，利用模板编译

const I18nWebpackPlugin = require('@fiber/i18n-webpack-plugin');

module.exports = {
  plugins: [
    new I18nWebpackPlugin({
      inject: false
    })
  ]
}


<html>
<head>
<script src="../../../headerJs"></script>
<%= htmlWebpackPlugin.options.fiber %>
</head>
</html>


最后做完后，请添加proxy为static路径的代理

'/static': {//匹配所有以 ‘/seeyon’开头的请求路径
      target: 'http://a82m.seeyoncd.com/', //代理目标的基础路径
      changeOrigin: true,
      headers: {
        Cookie: 'JSESSIONID='
      }
    }


做完如上操作后，会自动帮助引入：国际化、fiber。

特别说明！！！！！！！！

由于采用的html-webpack-plugin作为底层依赖，所以对于原有的引入依赖或许会造成影响，所以在这里提供了一个新api参数：addTags，具体参数可以查看typing.d.ts的类型说明文件，在依赖的同路径下，在这里提供一个示例

const I18nWebpackPlugin = require('@fiber/i18n-webpack-plugin');

module.exports = {
  plugins: [
    new I18nWebpackPlugin({
      addTags: [{
        tagName: 'script',
        innerHTML: '',
        attributes: {
          type: 'text/javascript',
          charset: 'utf-8',
          src: '/seeyon/rest/cap4/form/headerJs'
        }
      }]
    })
  ]
}


该示例就会再添加一个headerjs引入，当然顺序置于上面所列引入的最后

编撰人：yinyanting、admin




快速跳转



 * 关于fiber切换新引入方案



分享链接分享链接

## 22. ICP备案

> 原始路径：`/1073/`  
> 相对路径：`1073/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称       URL
APP备案引导手册   APP备案引导手册

分享链接分享链接

## 23. APP备案引导手册

> 原始路径：`/1073/1112.html`  
> 相对路径：`1073/1112.md`  
> JS Chunk：`app.7a5cbccd.js`

## APP备案引导手册


## 背景

应工信部文件《工业和信息化部关于开展移动互联网应用程序备案工作的通知》，要求所有涉及互联网的APP进行备案合规认证，不备案无法上架APP应用市场。基于此要求，不少客户在咨询备案事宜，此手册能解决大部分的备案疑惑。


## 解决方案

这里的备案主要指APP的ICP备案。


## 标准产品M3客户

如果客户使用标准产品M3，地区监管机构需要客户提供ICP备案证明，则直接提供致远公司针对标准产品M3申请的ICP备案号即可。

标准M3备案号              查验网址
京ICP备05042718号-18A   https://beian.miit.gov.cn/#/Integrated/recordQuery


## 定制APP客户

针对M3进行过VPN二次封装、沙箱包装、修改图标等所有操作都等同于非标准M3，无法使用致远的ICP备案信息，需要客户联系定制的技术人员获取APP信息进行备案。

完整的ICP备案过程参考文档： https://support.seeyon.com/cbo_cptjxx.html?id=1740665180259356674

编撰人：het




快速跳转



 * APP备案引导手册
   * 背景
   * 解决方案
     * 标准产品M3客户
     * 定制APP客户



分享链接分享链接

## 24. V5产品文档

> 原始路径：`/1073/1112.html`  
> 相对路径：`1073/1112.md`  
> JS Chunk：`app.7a5cbccd.js`

## APP备案引导手册


## 背景

应工信部文件《工业和信息化部关于开展移动互联网应用程序备案工作的通知》，要求所有涉及互联网的APP进行备案合规认证，不备案无法上架APP应用市场。基于此要求，不少客户在咨询备案事宜，此手册能解决大部分的备案疑惑。


## 解决方案

这里的备案主要指APP的ICP备案。


## 标准产品M3客户

如果客户使用标准产品M3，地区监管机构需要客户提供ICP备案证明，则直接提供致远公司针对标准产品M3申请的ICP备案号即可。

标准M3备案号              查验网址
京ICP备05042718号-18A   https://beian.miit.gov.cn/#/Integrated/recordQuery


## 定制APP客户

针对M3进行过VPN二次封装、沙箱包装、修改图标等所有操作都等同于非标准M3，无法使用致远的ICP备案信息，需要客户联系定制的技术人员获取APP信息进行备案。

完整的ICP备案过程参考文档： https://support.seeyon.com/cbo_cptjxx.html?id=1740665180259356674

编撰人：het




快速跳转



 * APP备案引导手册
   * 背景
   * 解决方案
     * 标准产品M3客户
     * 定制APP客户



分享链接分享链接

## 25. 流版签

> 原始路径：`/1136/`  
> 相对路径：`1136/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称                   URL
控件下载                    控件下载
金格控件自检步骤                金格控件自检步骤
国标Office自检步骤            国标Office自检步骤
插件适配的各浏览器情况             插件适配的各浏览器情况
金格常见问题索引                金格常见问题索引
OfiiceTrans在线预览问题索引     OfiiceTrans在线预览问题索引
永中wo（在线编辑）问题索引          永中wo（在线编辑）问题索引
点聚全文签批问题索引              点聚全文签批问题索引
永中dcs（在线预览）问题索引         永中dcs（在线预览）问题索引
金山中台（金山weboffice）问题索引   金山中台（金山weboffice）问题索引
数科问题索引                  数科问题索引
文档通问题索引                 文档通问题索引

分享链接分享链接

## 26. 金格控件自检步骤

> 原始路径：`/1136/1137.html`  
> 相对路径：`1136/1137.md`  
> JS Chunk：`app.7a5cbccd.js`

## 金格控件自检步骤


## 背景&需求

客户在使用金格控件时，会遇到无法唤起、提交转圈、反复提示安装、等其他异常问题。

由于控件与客户操作系统紧密联系，需要根据客户终端做确认自查，以下情况均影响金控使用：

1、金格控件版本不是最新或未正常安装； 2、浏览器不符合要求； 3、wps/office编辑软件版本兼容问题； 4、客户端浏览器设置问题； 5、客户端其他软件影响（例如加密软件和其他安全软件）； 等等 （只是简单举例，具体排查方法请看下方的自检步骤）


## 自检步骤


## 1.iweboffice2015与iwebpdf2018插件最新版链接

金格控件最新下载地址（待补充链接） 下载推荐配套使用的wps安装包 下载推荐配套使用的office安装包


## 2.浏览器兼容规则

首先：不支持任何浏览器的兼容模式！

OA 7.0sp3以上（若没有打适配kg107补丁或不是8.1sp210修复包以上，则无法支持谷歌、edge107以上版本）



OA 7.0sp3以下：仅支持ie浏览器


## 3.确保客户使用的编辑软件符合使用要求（不支持的编辑软件客户环境不允许安装，有些office仅是安装也会影响控件。

有问题的客户终端务必仅安装一个支持的编辑软件（比如安装了微软Office，就不要安装WPS，反之亦然）。




## 4.使用金格修复工具与致远修复工具

下载致远修复工具 下载金格修复工具

4.1 金格修复工具检测步骤：

①查看系统信息是否有错误，若有错误则点进查看详情查看具体错误原因和推荐解决方案。



②点击修复按钮后，点击一键修复



③再点击检测office安装正确性



正常情况会显示ole调用测试，若没有显示或一直卡住，则是编辑软件异常了，需要重装或安装推荐的版本。



③如图四个选项会在客户桌面生成金格修改过的浏览器快捷方式，用此快捷方式打开浏览器会大大降低控件的不稳定性，推荐给客户使用。



4.2 致远修复工具检测步骤：（此工具单点登录无法检测officeservlet请求，直接点击一键检测即可） 编辑 ①填写协同地址和账号密码后点击一键检测



②工具会自动检测当前控件版本是否为最新版，并且下载最新版安装，修复或安装即可。






## 5.查看金格控件安装是否成功

安装金格iweboffice2015后在C:\Program Files (x86)下会生成一个名为tgMiddlewareApp的文件夹

以上问题，请确认清楚，并提供截图附到bug单中。若使用不支持的环境，请不要上报bug。

编撰人：daixxyf、liuyc、huangym、het


快速跳转



 * 金格控件自检步骤
   * 背景&需求
   * 自检步骤
     * 1.iweboffice2015与iwebpdf2018插件最新版链接
     * 2.浏览器兼容规则
     * 3.确保客户使用的编辑软件符合使用要求（不支持的编辑软件客户环境不允许安装，有些office仅是安装也会影响控件。
     * 4.使用金格修复工具与致远修复工具
     * 5.查看金格控件安装是否成功



分享链接分享链接

## 27. 控件下载

> 原始路径：`/1136/1138.html`  
> 相对路径：`1136/1138.md`  
> JS Chunk：`app.7a5cbccd.js`

## 控件下载


## 客户端控件

iweboffice2015（7.0sp1以上适用）

v12.9.0.1092（客户端）

iwebpdf2018（OA7.1sp1以上适用）

v9.0.2258.1843（客户端）

iweboffice信创中间件

v3.1.0.186（客户端）


## 服务器端控件补丁（S1补丁）

iweboffice2015 (注意：打这个包之前需要打s1工具的补丁包或者将s1更新到3.4.1版本（二选一）

v12.9.0.1092（8.0以上的都可用）

iwebpdf2018（7.1sp1以下不支持iwebpdf2018控件）

v9.0.2258.1843（OA7.1sp1以上适用）

编撰人：daixxyf、liuyc、het




快速跳转



 * 控件下载
   * 客户端控件
   * 服务器端控件补丁（S1补丁）



分享链接分享链接

## 28. 金格常见问题索引

> 原始路径：`/1136/1822.html`  
> 相对路径：`1136/1822.md`  
> JS Chunk：`app.7a5cbccd.js`

## 金格常见问题索引


## 【网络问题】

FAQ名称                                            问题现象描述
【流版签】【金格控件】公文正文套红无响应；公文套红正文内容空白；公文套红提示“文件打开失败”   


## 【金格控件弹窗（报错）】

FAQ名称                                                            问题现象描述
【流版签】【金格】office控件版本需要更新                                          
【流版签】【金格】使用金格控件打开正文，提示：http返回码=12029或http返回码=12157               
【流版签】【金格】使用金格控件时，提示：文件打开失败，控件开始尝试自行修复，然后进行重试。如仍未解决，请打开日志工具查看日志   
【流版签】【金格】使用金格控件时，提示：安装控件或选择启动wps                                 
【流版签】【金格】使用金格控件保存正文时，提示：保存正文失败，请检查日志！                            
【流版签】【盖章】使用金格控件盖图片章时，提示：没有盖章，仍然提示：正文已盖章....                      


## 【金格控件显示问题】

FAQ名称                                     问题现象描述
【流版签】【金格】金格控件空白，单独自动打开了一个office或wps展示正文   
【流版签】【金格】金格控件打开后，没有工具栏                    


## 【文件格式问题】

FAQ名称                      问题现象描述
【流版签】【金格】PDF正文文字乱码或部分空白    
【流版签】【金格】个别word文档突然乱码或空白   
【流版签】【金格】套红后文档格式变化或不符合预期   
【流版签】【金格】正文在流转过程中错版，格式异常   无


## 【点聚问题】

FAQ名称                                         问题现象描述
【流版签】【点聚】M3进行点聚全文签批时，提示：本用户没有授权，没法签批，请联系管理员   
【流版签】【点聚】点聚专业签章、点聚全文签批提示：签批服务器链接失效，请联系管理员     


## 【其他问题】

FAQ名称
【流版签】【金格】谷歌、edge107以上点击正文没反应
【流版签】【金格】金格控件之前使用非支持版本正常，突然不正常了
【流版签】【金格】想用某某加密软件能否适配
【流版签】【图片章】转pdf后印章模糊，有锯齿痕迹
【流版签】【金格】金格签章盖章后前台看到的是红章，但从附件下载的是黑章
【流版签】【wps】WPS365在OA中集成使用方法

编撰人：liuyc、luoyy、huangym、het


快速跳转



 * 金格常见问题索引
   * 【网络问题】
   * 【金格控件弹窗（报错）】
   * 【金格控件显示问题】
   * 【文件格式问题】
   * 【点聚问题】
   * 【其他问题】



分享链接分享链接

## 29. OfiiceTrans在线预览问题索引

> 原始路径：`/1136/1846.html`  
> 相对路径：`1136/1846.md`  
> JS Chunk：`app.7a5cbccd.js`

## OfiiceTrans在线预览问题索引


## OA配置问题、用户操作问题

FAQ名称                                       问题现象描述
【流版签】【在线预览】升级后，查看公文正文不使用在线预览                
【流版签】【在线预览】OA各版本能使用的在线预览产品清单                
【在线预览】查看部分文件时不使用在线预览而是用控件进行查看               
【在线预览】移动端采用黑色主题，看不到在线预览的内容                  
【流版签】【officetrans转换】转换服务已启动但无法调用转换服务查看文件    
移动端M3查看正文预览显示net::ERR_BLOCKED_BY_RESPONSE   net::ERR_BLOCKED_BY_RESPONSE
【流版签】【officetrans转换】在线预览没有水印                
【流版签】第3方页面无法查看。显示灰色，拒接了我们的链接请求、             


## 需求问题

此类问题已有结论属于需求问题，如果需要修改，请走项目化支持

FAQ名称                                       问题现象描述
【流版签】【在线预览】各业务模块对在线预览的适配情况                  
【流版签】【在线预览】升级后CAP4附件控件预览PDF文件功能发生变化         
【流版签】【officetrans转换】附件中的PDF,没有打印按钮。         
【流版签】【officetrans转换】安卓移动端无法在线预览文件，PC端正常转换   
【流版签】office转换，一直显示转换中--路径问题                 


## 第三方配置问题

解决以下问题需要修改Aspose转换服务的相关参数

FAQ名称                                                  问题现象描述
【流版签】【officetrans转换】不能获取Office文件转换服务、转换不成功             
【流版签】【在线预览】Aspose在线预览提示Evaluation Only. Created with   
Aspose.Words
【在线预览】在线预览正文有黑色边框                                      
【流版签】M3查看发票pdf文字显示方框                                   
【流版签】【在线预览】查看文档内容，字体发生变化                               
【流版签】office转换后，图片有些不显示                                 
【流版签】【永中在线预览】所有文件一直显示“正在转换，请稍等...”                     
【流版签】永中预览 360浏览器提示当前浏览器版本不支持pdf在线预览”                   


## 第三方缺陷

以下问题属于Aspose产品的缺陷，致远无法解决。

FAQ名称                                 问题现象描述
【在线预览】在线预览提示“内存不足，无法打开此页面”            
【在线预览】在线预览提示：“文件转换失败，原因：文件无法识别”       
【流版签】【在线预览】Excel表格大写人民币一栏显示异常         
【流版签】【在线预览】文档的水印比其他地方的水印更小更浅          
【流版签】【转换服务】某个word或excel文件不能在线预览       
officetran转换的pdf公告，页面显示斜杠             
【流版签】【officetrans】aspose转换慢，很久才转换成功   


## 常见咨询问题

编撰人：luoyy、chelq


快速跳转



 * OfiiceTrans在线预览问题索引
   * OA配置问题、用户操作问题
   * 需求问题
   * 第三方配置问题
   * 第三方缺陷
   * 常见咨询问题



分享链接分享链接

## 30. 插件适配的各浏览器情况

> 原始路径：`/1136/1847.html`  
> 相对路径：`1136/1847.md`  
> JS Chunk：`app.7a5cbccd.js`

## 插件适配的各浏览器情况



编撰人：huangym、luoyy




快速跳转



 * 插件适配的各浏览器情况



分享链接分享链接

## 31. 永中wo（在线编辑）问题索引

> 原始路径：`/1136/1857.html`  
> 相对路径：`1136/1857.md`  
> JS Chunk：`app.7a5cbccd.js`

## 永中wo（在线编辑）问题索引


## 永中wo（在线编辑）配置问题

FAQ名称                                问题现象描述
【流版签】【永中wo（在线编辑）】个别正文打开报错，提示文件打开失败   


## 永中wo（在线编辑）第三方问题

FAQ名称                                问题现象描述
【流版签】【永中wo（在线编辑）】消息提醒提示永中文档在线编辑已到期   


## 永中wo（在线编辑）常见咨询问题

FAQ链接
【流版签】【永中wo（在线编辑）】【永中dcs（在线预览）】永中版本适配情况
【流版签】【永中wo（在线编辑）】【永中dcs（在线预览）】永中服务端支持哪些操作系统
【流版签】【永中wo（在线编辑）】永中是否支持盖章
【流版签】【永中wo（在线编辑）】使用永中在线编辑，正文类型选择PDF，还是会调用的控件

编撰人：luoyy


快速跳转



 * 永中wo（在线编辑）问题索引
   * 永中wo（在线编辑）配置问题
   * 永中wo（在线编辑）第三方问题
   * 永中wo（在线编辑）常见咨询问题



分享链接分享链接

## 32. 点聚全文签批问题索引

> 原始路径：`/1136/1893.html`  
> 相对路径：`1136/1893.md`  
> JS Chunk：`app.7a5cbccd.js`

## 点聚全文签批问题索引


## 第三方配置问题

FAQ名称                                                  问题现象描述
【流版签】【点聚全文签批】点聚专业签章、签批提示【签批服务器链接失效，请联系管理员】             
【流版签】【点聚全文单签批】移动端进行全文签批时提示【移动办公：本用户没有授权，没法签批，请联系管理员】   
【流版签】【点聚全文单签批】M3手写签批报错“查找用户出错”                         


## 常见咨询问题

FAQ名称
【流版签】【点聚全文单签批】全文签批单操作手册
【流版签】【点聚全文单签批】移动端对全文签批的适配情况
【无纸化会议】点聚为何换成数科

编撰人：luoyy


快速跳转



 * 点聚全文签批问题索引
   * 第三方配置问题
   * 常见咨询问题



分享链接分享链接

## 33. 永中dcs（在线预览）问题索引

> 原始路径：`/1136/1932.html`  
> 相对路径：`1136/1932.md`  
> JS Chunk：`app.7a5cbccd.js`

## 永中dcs（在线预览）问题索引


## 永中dcs（在线预览）第三方问题

FAQ名称                                   问题现象描述
【流版签】【永中dcs（在线预览）】永中预览 移动端预览只显示前几页的内容   


## 永中dcs（在线预览）常见咨询问题

FAQ链接
【流版签】【永中wo（在线编辑）】【永中dcs（在线预览）】永中版本适配情况
【流版签】【永中wo（在线编辑）】【永中dcs（在线预览）】永中服务端支持哪些操作系统
【流版签】【永中dcs（在线预览）】永中在线预览支持压缩包预览吗
【流版签】【永中dcs（在线预览）】永中文档在线预览支持OFD格式吗

编撰人：luoyy


快速跳转



 * 永中dcs（在线预览）问题索引
   * 永中dcs（在线预览）第三方问题
   * 永中dcs（在线预览）常见咨询问题



分享链接分享链接

## 34. 国标Office自检步骤

> 原始路径：`/1136/1933.html`  
> 相对路径：`1136/1933.md`  
> JS Chunk：`app.7a5cbccd.js`

## 国标Office自检步骤


## 第一步：自查版本

1、起始支持版本：V8.0SP2 2、购买检测：购买致远“国标Office”插件（请将加密狗信息附至BUG评论区） 3、版本检测：客户端安装WPS 2019专业版（请将wps版本信息附至BUG评论区） 致远测试通过版本（推荐使用）：windows版本要求11.8.2.10321/11.8.2.11972/11.8.2.11718/11.8.2.11965（请检查客户环境是否为该版本号，如果不为该版本，则更换版本） 致远测试通过版本（推荐使用）：信创版本要求11.8.2.10251/11.8.2.10953/11.8.2.11929（请检查客户环境是否为该版本号，如果不为该版本，则更换版本） 并且告知供应商：内置JSAPI插件 大于以上要求版本的WPS未全面测试（可能存在各种未知问题），低于该版本必然存在BUG！！！ 若客户使用非致远推荐版本，可以用一台客户电脑安装推荐版本后尝试，目的是为了确定是否为版本导致的问题。若更换版本后正常，则为wps自身的问题，请联系wps厂商


## 第二步：判断是否启用国标Office（WPS加载项）去控件配置

系统管理员登录后台，通过系统参数配置可看见混网开关，则可以使用加载项模式


## 第三步：判断本地wps启动服务是否启动

## windows环境启动服务失败

第一步：检测WPS版本以及安装环境 当前是否是WPS专业版，并且让销售内置了JSAPI插件？ 当前是否是前面要求匹配的小版本号？低于或高于小版本号均可能存在未知问题！ 第二步：检测publish文件 1）文件地址栏输入：%AppData%回车,进入如下地址，看看加载项的配置路径文件，如果有其他的xml（主要是jsplugins.xml），则删掉，只保留publish.xml。

2）打开publish.xml，只保留自己访问OA的ip地址的配置，有其他的，则全部删掉。 3）打开注册表编辑器，查看路径"计算机\HKEY_CLASSES_ROOT\ksoWPSCloudSvr\shell\open\command" 查看数据路径是否为wps的安装路径，若不是，手动修改。路径：\Kingsoft\WPS Office\ksolaunch.exe" /qingbangong "%1 到对应的安装路径查看是否有该文件

第三步：检测WPS端口 1）是否有开启网络代理，并代理了http:127.0.0.1，如果有，则取消代理 2）在浏览器地址栏中访问http://127.0.0.1:58890/version (http://127.0.0.1:58890/version) 接口，（如果端口通了，则会返回1.0.0或者1.0.1，则跳至第4步）

3）如果无法访问，则清除浏览器缓存

(火狐浏览器较特殊，勾选为总是询问)

4）在浏览器地址栏输入：ksoWPSCloudSvr://start=RelayHttpServer 弹出需要唤起本地应用的窗口后，点击“确定”（不同浏览器弹框样式可能不同）

5）再次访问http://127.0.0.1:58890/version (http://127.0.0.1:58890/version) 接口，若端口通了，还不能正常使用，请跳转 第四步 第四步： 端口有启动还是打不开 1）杀死进程，再通过WPS加载项尝试打开 打开cmd：

在命令行中依次输入，每输入一行，按一次回车： taskkill /f /t /im wps.exe

taskkill /f /t /im wpspdf.exe

taskkill /f /t /im wpp.exe

taskkill /f /t /im et.exe

taskkill /f /t /im weboffice.exe 杀死进程后，WPS加载项调起时还是请求错误，卸载重装。

## 信创环境启动服务失败

第一步：检测WPS版本以及安装环境 当前是否是WPS专业版，并且让销售内置了JSAPI插件？ 当前是否是前面要求匹配的小版本号？低于或高于小版本号均可能存在未知问题！

第二步：检测publish文件 1）文件地址栏输入：~/.local/share/Kingsoft/wps/jsaddons回车,进入如下地址，看看加载项的配置路径文件，如果有其他的xml（主要是jsplugins.xml），则删掉，只保留publish

2）打开publish.xml，只保留自己访问OA的ip地址的配置，有其他的，则全部删掉。 第三步：检测WPS端口 1）是否有开启网络代理，并代理了http:127.0.0.1，如果有，则取消代理 2）在浏览器地址栏中访问http://127.0.0.1:58890/version (http://127.0.0.1:58890/version) 接口，（如果端口通了，则会返回1.0.0或者1.0.1，则跳至第4步）

3）如果无法访问，则清除浏览器缓存

(火狐浏览器较特殊，勾选为总是询问)

4）在浏览器地址栏输入：ksoWPSCloudSvr://start=RelayHttpServer 弹出需要唤起本地应用的窗口后，点击“确定”（不同浏览器弹框样式可能不同）

5）再次访问http://127.0.0.1:58890/version (http://127.0.0.1:58890/version) 接口，（如果端口通了，则会返回1.0.0或者1.0.1）如果不好使，则向下排查。 若端口通了，还不能正常使用，请跳转 第四步

第四步： 端口有启动还是打不开 1）杀死进程，再通过WPS加载项尝试打开 ①打开终端输入： quickstartoffice restart 按回车执行



②UOS（信创）终端执行 (每输入一行，按一次回车)： cd/opt/apps/cn.wps.wps-office-pro/files/bin ./quickstartoffice restart




## 第四步：WPS客户端环境出现问题，有哪些文件权限需要排查

【缺图、缺现象场景】 需要保证oem.ini文件有读写的权限，本地的jsaddons文件夹也必须要有读写的权限 1：Windows系统 检查oem.ini文件：安装路径 \WPSOfflce\一串数字（版本号）\office6\cfgs\，建议修改cfgs目录的权限



示例：鼠标右键点击电脑左下角win图标,点击windowsPowerShell(管理员)（A）



找到自己需要改变权限的目录，cd进入目录，执行命令：cacls cfgs /t /p everyone:F



2：linux系统 检查oem.ini文件： 普通linux机器 /opt/kingsoft/wps-office/office6/cfgs

UOS /opt/apps/cn.wps.wps-office-pro/files/kingsoft/wps-office/office6/cfgs/ 示例：sudo chmod -R 777 /opt/kingsoft/wps-office/office6/cfgs



3.开启WPS调试模式 打开oem.ini文件在【Support】下，增加配置JsApiShowWebDebugger=true



4.国产机修改了oem.ini文件之后，需要重启WPS，方式如下： Linux（信创） 终端执行 quickstartoffice restart

UOS（信创） 终端执行 cd/opt/apps/cn.wps.wps-office-pro/files/bin ./quickstartoffice restart

以上问题，请确认清楚，并提供截图附到bug单中。若使用不支持的环境，请不要上报bug。

编撰人：huangym


快速跳转



 * 国标Office自检步骤
   * 第一步：自查版本
   * 第二步：判断是否启用国标Office（WPS加载项）去控件配置
   * 第三步：判断本地wps启动服务是否启动
     * windows环境启动服务失败
     * 信创环境启动服务失败
   * 第四步：WPS客户端环境出现问题，有哪些文件权限需要排查



分享链接分享链接

## 35. 金山中台（金山weboffice）问题索引

> 原始路径：`/1136/1967.html`  
> 相对路径：`1136/1967.md`  
> JS Chunk：`app.7a5cbccd.js`

## 金山中台（金山weboffice）问题索引


## 金山跑版问题

以下问题虽然表现各异，但是本质上都是跑版问题。 跑版问题分两类：1是因为缺字体导致，补全字体即可。2是金山产品缺陷，需要金山进行修复。

FAQ名称                                  问题现象描述
【金山中台】金山（weboffice）文件预览、编辑 内容异常        无
【流版签】【金山weboffice】weboffice在线预览样式不一致   
【流版签】【金山weboffice】word转PDF之后字体变成斜体     
【金山weboffice】金山中台显示痕迹记录不完整             
【金山weboffice】打印正文时正文和本身页码不符            
【流版签】【金山中台】在线编辑的脚注显示为方框，应该显示为数字        
【流版签】【金山weboffice】套红后正文页边距会发生变化        无


## 已知的金山缺陷

FAQ名称                               问题现象描述
【金山weboffice】金山中台预览，ie浏览器查看正文显示空白   
【流版签】【金山weboffice】金山中台偶发40003       


## 配置问题

FAQ名称                                                       问题现象描述
【流版签】【金山weboffice】weboffice报错 Could not create URI object   
【流版签】【金山weboffice】金山中台已经部署好了，前端编辑正文提示：code：40100001         
【流版签】【金山weboffice】金山在线预览pdf附件报错：参数错误 code:40000             
【流版签】【金山weboffice】表单转文档控件，再次转文档时，文档中带入的控件内容不会覆盖，会新增         
【金山weboffice】公文盖章后提交后，后续节点查看正文看不到印章                         
【金山中台】金山weboffice（中台）套红后红头不显示、只显示正文内容，再次套红提示已套红             
【流版签】【金山weboffice】金山weboffice套红失败                           
【流版签】【金山中台】文件转换失败，原因:配置错误，无法查看，请联系系统管理员                     
【流版签】【金山中台】突然无法正常使用，有报错10101008、InvalidArgument             
【流版签】【金山weboffice】金山中台查看正文或者附件报错result csrf error           
【m3】【金山预览】移动端正文没有用金山预览查看，用第三方的程序，pc正常                       
【流版签】【金山中台】在线预览和编辑报错，code:50001、code:20022                  
部署金山中台，添加host的时候，提示需要输入密码                                   


## 无效问题

FAQ名称                                                   问题现象描述
【流版签】【金山weboffice】套红模版正文书签添加在文字上，公文模板应用绑定绑定模板正文的文字不显示   
【流版签】【金山weboffice】金山编辑提示code:40100001                   
【套红】修改正文再次套红，勾选“保留一个红头”，套红后的正文是修改前的正文                   
【流版签】【金山中台】公文编辑界面关闭后内容会自动保存                             无


## 升级变动

FAQ名称                                             问题现象描述
【流版签】【金山weboffice】升级V9.0SP1后金山在线编辑与预览不可用，老版本没问题   


## 需求问题

FAQ名称                                                        问题现象描述
【流版签】【金山weboffice】表单转文档的内容使用金山weboffice无法带入表格，使用金山WPS加载项正常   
【流版签】【金山中台】weboffice套红的时候有一个日期字段套红不上                         无
【流版签】【金山weboffice】在线编辑cap3表单附件没有保存生效                         无


## 金山中台（金山weboffice）常见咨询问题

FAQ链接
【金山中台】WebOffice在线预览、编辑支持的浏览器版本
【流版签】【金山weboffice】OA是否有现成的接口实现金山中台可以回调推送授权到期提醒
【流版签】【officetrans转换】启动了officetrans后，附件还是用金山文档中台打开
【在线预览】部署金山在线预览服务，文件不能进行在线预览，不显示放大镜
【流版签】【金山中台】金山文档中台：1、金山文档中台页边距无法按照客户实际要求进行固定


## 金山中台老公文

FAQ链接
【金山中台】【老公文】上了中台后，24年的公文正文打开，22年的正文点击原文件还是用插件打开

编撰人：chelq、luoyy


快速跳转



 * 金山中台（金山weboffice）问题索引
   * 金山跑版问题
   * 已知的金山缺陷
   * 配置问题
   * 无效问题
   * 升级变动
   * 需求问题
   * 金山中台（金山weboffice）常见咨询问题
   * 金山中台老公文



分享链接分享链接

## 36. 数科问题索引

> 原始路径：`/1136/2050.html`  
> 相对路径：`1136/2050.md`  
> JS Chunk：`app.7a5cbccd.js`

## 数科问题索引


## 跑版问题

预览内容和实际文档内容不一致就属于跑版

FAQ名称                                问题现象描述
【流版签】【数科预览】数科预览跑版                    暂无
【流版签】【数科】word转版式之后，文件页数变化或页脚格式发生变化   暂无


## 设计缺陷

FAQ名称                       问题现象描述
【流版签】【文档通】【数科】内网或外网无法同时使用   暂无


## 授权异常

FAQ名称                                                        问题现象描述
【流版签】【数科预览】页面空白                                              暂无
【流版签】【数科预览】使用数科预览，打开公文详情，转圈等待动画一直存在                          
【流版签】【数科】转PDF提示“不支持转PDF版式”，“不支持转OFD版式”；转公告选择PDF版式、OFD版式没反应   
【流版签】【数科】PC端套红后一直等待、转圈                                       
【流版签】【数科】移动端执行套红操作，提示“套红失败”                                  
【流版签】【数科预览】“文件未找到”                                           
【流版签】【数科预览】数科预览页面出现“未授权”                                     


## 配置问题

FAQ名称                       问题现象描述
【流版签】【数科签章】不支持文单签章          
【流版签】【数科预览】URL不可用           
【流版签】【数科】所有文件预览均提示“连接已重置”   
【流版签】【数科预览】无法预览Excel文件      暂无


## 数据异常

FAQ名称                      问题现象描述
【流版签】【数科】查看部分正文提示“已重置连接”   
【流版签】【数科】图片章被文本段落遮挡        


## 兼容性问题

FAQ名称                   问题现象描述
【流版签】查看正文提示“不支持当前浏览器”   


## 第三方服务异常

FAQ名称                              问题现象描述
【流版签】【数科预览】预览内容空白                  
【流版签】【数科】数科预览报错 Unsupported:data   

编撰人：luoyy


快速跳转



 * 数科问题索引
   * 跑版问题
   * 设计缺陷
   * 授权异常
   * 配置问题
   * 数据异常
   * 兼容性问题
   * 第三方服务异常



分享链接分享链接

## 37. 文档通问题索引

> 原始路径：`/1136/2051.html`  
> 相对路径：`1136/2051.md`  
> JS Chunk：`app.7a5cbccd.js`

## 文档通问题索引


## 跑版问题

文档内容异常、样式异常均属于跑版现象。

FAQ名称                问题现象描述
【流版签】【文档通】在线编辑内容跑版   暂无


## 设计缺陷

FAQ名称                       问题现象描述
【流版签】【文档通】【数科】内网或外网无法同时使用   暂无


## 配置问题

FAQ名称                        问题现象描述
【流版签】【文档通】下载失败；这份文件无法保存。     
【流版签】【文档通】文档通服务health校验失败    
【流版签】【文档通】“文件打开失败，文档通配置异常”   
【流版签】【文档通】文档通打印预览内容显示乱码      


## 第三分产品缺陷

FAQ名称                                        问题现象描述
【流版签】【文档通】修改正文后提交，后续预览看不到修改的内容               暂无
【流版签】【文档通】正文盖章之后，后续的打印和预览都不显示印章，但是下载的文件里有。   暂无
【流版签】【文档通】“该文件版本已经改变了。该页面将被重新加载”             
【流版签】【文档通】在线编辑选择字体时，提示“您要保存的字体在当前设备上不可用”     
【流版签】【文档通】在线编码时选不到某个字体                       暂无
【流版签】【文档通】下载Excel正文，一直在转圈、等待                 
【流版签】【文档通】复制粘贴到文档中的部分图片无法显示                  
【文档通】公文正文里面的嵌套附件无法打开                         


## 兼容性问题

FAQ名称                        问题现象描述
【流版签】使用IE浏览器查看流版签配置页面，页面空白   

编撰人：luoyy


快速跳转



 * 文档通问题索引
   * 跑版问题
   * 设计缺陷
   * 配置问题
   * 第三分产品缺陷
   * 兼容性问题



分享链接分享链接

## 38. 公文

> 原始路径：`/1142/`  
> 相对路径：`1142/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称         URL
业务基础          业务基础
公文升级          公文升级
对外接口          对外接口
公文问题索引        公文问题索引
泛公文业务问题清单引导   泛公文业务问题清单引导

分享链接分享链接

## 39. 公文交换

> 原始路径：`/1142/1193/1194.html`  
> 相对路径：`1142/1193/1194.md`  
> JS Chunk：`app.7a5cbccd.js`

## 公文交换


## 概述

公文交换，不同单位或部门之间、上下级单位之间的公文传输，即发文流程转换为收文流程的过程。


## 说明

公文交换需要操作的人员具有公文收发文员角色才可进行交换操作





需要通过发文流程进行分送、然后通过签收单进行签收及分办后流转到下级单位的收文流程 发文流程的节点权限中配置分送操作



发文拟文时，配置流程节点为含有分送操作的节点权限





文单中的主送单位即对应的公文元素是send_to（还有其他公文元素也支持，copy_to,report_to）时 添加单位i数据，可进行公文交换



填写完成表单后即可发送进行公文交换 从分送节点对应的待办人那里打开刚发的文，进行分送操作



对应的主送单位的收文员会收到签收的待办



进行签收操作即可 然后继续进行分办操作



点击分办后会弹出新窗口（新窗口需要浏览器有弹出窗口的权限）进行收文登记操作



发送后，到这里就是完成了公文交换了

编撰人：lichaoj




快速跳转



 * 公文交换
   * 概述
   * 说明



分享链接分享链接

## 40. 公文元素

> 原始路径：`/1142/1193/1195.html`  
> 相对路径：`1142/1193/1195.md`  
> JS Chunk：`app.7a5cbccd.js`

## 公文元素


## 概述

公文元素：是映射到数据库字段的数据库，每个公文元素是唯一的。

目前共有公文元素 222个，但是只开放出了 184个。非系统元素可以修改名称。



编撰人：lichaoj




快速跳转



 * 公文元素
   * 概述



分享链接分享链接

## 41. 公文开关

> 原始路径：`/1142/1193/1196.html`  
> 相对路径：`1142/1193/1196.md`  
> JS Chunk：`app.7a5cbccd.js`

## 公文开关


## 概述

公文开关用来控制各种业务场景的展示及功能操作，目前只有如下图这些开关



编撰人：lichaoj




快速跳转



 * 公文开关
   * 概述



分享链接分享链接

## 42. 公文预归档

> 原始路径：`/1142/1193/1197.html`  
> 相对路径：`1142/1193/1197.md`  
> JS Chunk：`app.7a5cbccd.js`

## 公文预归档

公文预归档逻辑如下： 1、老公文，流程没结束，预归档目录也会生成文号，因每次提交时都会去更新归档信息 2、新公文，如果拟稿的时候生成文号，则预归档目录会生成文号，否则需要流程结束后才能在预归档目录中生成文号，中间流转过程不会更新归档数据

编撰人：lichaoj




快速跳转



 * 公文预归档



分享链接分享链接

## 43. 发文拟文/收文登记/签发拟文

> 原始路径：`/1142/1193/1198.html`  
> 相对路径：`1142/1193/1198.md`  
> JS Chunk：`app.7a5cbccd.js`

## 发文拟文/收文登记/签发拟文


## 概述

这里即为公文的新建入口了


## 说明

菜单一般在： 公文管理->发文拟文/收文登记/签发拟文 发文拟文：发送发文一类的公文数据 收文登记：发送收文一类的公文数据 签报拟文：发送签报一类的公文数据



以发文为例：



1、调用模板 可以使用 模板管理里面授权当前用户的模板来使用

2、正文类型可使用 标准正文、word、xls、wps、pdf、ofd这些类型的文件作为公文的正文

3、可编辑自己需要的流程进行流转，若调用模板的话是统一使用模板的流程进行流转不可编辑流程

4、可以选择自己需要的发文单

5、当前公文的一些基础设置

6、可上传附件和关联文档

7、发文文号可使用授权了的文号（文号管理）

编撰人：lichaoj




快速跳转



 * 发文拟文/收文登记/签发拟文
   * 概述
   * 说明



分享链接分享链接

## 44. 外部单位

> 原始路径：`/1142/1193/1199.html`  
> 相对路径：`1142/1193/1199.md`  
> JS Chunk：`app.7a5cbccd.js`

## 外部单位


## 概述

外部单位：是公文这边特有的一个单位表现形式不和系统的组织机构产生关系。仅用于公文流转时的外部单位的显示。

注意：外部单位不参与公文交换



新建后填写名称提交即可

编撰人：lichaoj




快速跳转



 * 外部单位
   * 概述



分享链接分享链接

## 45. 套红模板管理

> 原始路径：`/1142/1193/1200.html`  
> 相对路径：`1142/1193/1200.md`  
> JS Chunk：`app.7a5cbccd.js`

## 套红模板管理


## 说明

套红模板分为 正文套红和文单套红

 * 正文套红是用于给word正文进行套红的
 * 文单套红是用于给文单进行套红的



套红模板的原理是，通过在模板文件中配置书签，然后正文控件会使用word的插入书签数据的功能进行插入数据。


## 配置

配置路径：公文管理-> 公文应用设置-> 套红模板

按需要的类型新建模板



1、选模板分类

2、上传模板文件

3、填写模板信息（需要授权后才可被调用到）

4、确定提交



编撰人：lichaoj




快速跳转



 * 套红模板管理
   * 说明
   * 配置



分享链接分享链接

## 46. 快速发文（公文交换）

> 原始路径：`/1142/1193/1201.html`  
> 相对路径：`1142/1193/1201.md`  
> JS Chunk：`app.7a5cbccd.js`

## 快速发文（公文交换）


## 概述

快速发文是发起的是一种公文交换流程。他所在的发文是没有流程的，会直接到签收流程去。 签收流程：是将发文流程转换为收文流程的一个过渡流程，常常使用签收单来做。涉及签收、分办的节点权限。



编撰人：lichaoj




快速跳转



 * 快速发文（公文交换）
   * 概述



分享链接分享链接

## 47. 文单管理

> 原始路径：`/1142/1193/1202/`  
> 相对路径：`1142/1193/1202/README.md`  
> JS Chunk：`app.7a5cbccd.js`

## 文单管理


## 说明

文单是发送公文必不可少的基础内容，是基于infopath制作的格式模板，如下图：



文单类型分为** 发文单、收文单、签报单、签收单 **四类

发文单可以直接在 发文拟文时调用

收文单可以直接在 收文登记时调用

签报单可以直接在 签报拟文时调用

签收单不可主动调用，需要在公文交换流程中自动被调用，（目前签收单只能收到发文单中得标题区附件和附言区得附件）


## 如何配置

角色：公文管理员

配置路径：公文管理 -> 公文应用设置 -> 发文单/收文单/签报单



角色：单位管理员

配置路径：公文管理 -> 公文应用设置 -> 发文单/收文单/签报单/签收单(只有在单位管理时才可见)




## 新建文单

上传制作好的infopath文件，后缀为.xsn



然后会自动跳转到文单编辑页面



1、编辑文单名称 2、修改文单分类 3、编辑录入类型 4、编辑映射字段 5、编辑文单格式设置 6、编辑文单套红设置（见：套红模板）

下一步：



编辑完成后（到这一步可以直接完成文单配置，公文发文时就可以使用起这个文单），这里我们先下一步：



节点权限绑定操作这个是我们设计流程过程中非常常用的，配置这个节点权限在文单中是否能修改文单内的内容，正文是否能够显示。

下一步：



查询设置和统计设置还有触发设置是比较高级的用法，暂时不用管。

下一步到应用绑定：

应用即是用来新建模板的地方，可以配置固定的流程供授权人员调用，而不用在新建时再进行流程配置了。





1、模板名称

2、授权哪些用户可用

3、正文类型 无（拟文时可选正文类型）、标准正文、word、xls、wps、pdf、ofd

4、word正文类型时，可选择套红模板（套红模板）

5、文号绑定（文号管理）

6、流程超期设置

7、流程节点合并处理策略

8、流程制作见下图



9、设置流程预归档到文档中心去，设置文档中心目录

a、升级前，流程没结束，预归档目录也会生成文号 b、升级后如果拟稿的时候生成文号，则预归档目录会生成文号，否则需要流程结束后才能在预归档目录中生成文号

10、配置流程可编辑操作

在第10步完成后，点击右上方的保存



保存后跳转到之前的列表页上面;



点完成后会提示 是否直接发布文单? (“确定”表示保存后直接发布，“取消”表示保存为草稿)

点确定后新建文单就结束了。

编撰人：lichaoj




快速跳转



 * 文单管理
   * 说明
   * 如何配置
   * 新建文单



分享链接分享链接

## 48. 文单格式配置

> 原始路径：`/1142/1193/1202/1203.html`  
> 相对路径：`1142/1193/1202/1203.md`  
> JS Chunk：`app.7a5cbccd.js`

## 文单格式配置


## 说明

用于流程流转过程中，文单中的意见格式设置

包含：意见显示签名还是普通显示、部门显示、单位显示、日期显示、附件及关联文档显示、意见顺序





编撰人：lichaoj


快速跳转



 * 文单格式配置
   * 说明



分享链接分享链接

## 49. 文号管理

> 原始路径：`/1142/1193/1204.html`  
> 相对路径：`1142/1193/1204.md`  
> JS Chunk：`app.7a5cbccd.js`

## 文号管理


## 说明

文号，是公文中使用非常频繁的一个功能，是可以自动增加的格式流水号。通常由三部分组成 **机构代字 + 年号 + 流水号 ** 例如：发文字号〔2021〕1号



文号分为：小流水号，大流水号

小流水号：一个机构代字用自己的一个流水号 ，若开启占号和其他流水号不会冲突

大流水号：多个机构代字可以用同一个流水号，若开启占号和其他流水号会冲突


## 配置

配置路径：公文管理->公文应用设置->文号管理

新建：可新建三种分类 发文文号、内部文号、签收编号



1、点击新建

2、编辑机构代字 是同一个分类下唯一

3、流水号设置方式：大流水、小流水

4、可以设置流水号最大值和最小值及当前值

5、授权文号给那些人使用

6、选择文号分类 公文文号、内部文号、签收编号

7、确定提交，新建完成


## 文号规则

用于控制流程流转过程中的文号的状态

发文文号：



内部文号：



签收编号：




## 文号结构图



编撰人：lichaoj




快速跳转



 * 文号管理
   * 说明
   * 配置
   * 文号规则
   * 文号结构图



分享链接分享链接

## 50. 机构组

> 原始路径：`/1142/1193/1205.html`  
> 相对路径：`1142/1193/1205.md`  
> JS Chunk：`app.7a5cbccd.js`

## 机构组


## 概述

结构组：可以将系统中组织机构的中的部门重新分组，方便发送公文时选择。



新建后，填写名称及分配部门即可。

编撰人：lichaoj




快速跳转



 * 机构组
   * 概述



分享链接分享链接

## 51. 模板管理

> 原始路径：`/1142/1193/1206.html`  
> 相对路径：`1142/1193/1206.md`  
> JS Chunk：`app.7a5cbccd.js`

## 模板管理


## 说明

模板管理：可以在这里看到所有文单应用绑定中配置的模板，按照模板分类进行分类

模板分类主要有三大类：发文模板、收文模板、签报模板

三大类模板下可新建子类型的分类



可在这个管理界面

1、授权模板给某人使用

2、同时还可设置联合发文的流程

3、管理模板分类

编撰人：lichaoj




快速跳转



 * 模板管理
   * 说明



分享链接分享链接

## 52. 电子印章

> 原始路径：`/1142/1193/1207.html`  
> 相对路径：`1142/1193/1207.md`  
> JS Chunk：`app.7a5cbccd.js`

## 电子印章


## 概述

电子印章：用于配置签名印章数据

签名：使用在公文意见中。

印章：使用在正文的盖章中为图片章。

一个用户可配置一个签名


## 配置

配置路径： 单位管理员登陆后， 基础功能设置 -> 电子印章管理



编撰人：lichaoj




快速跳转



 * 电子印章
   * 概述
   * 配置



分享链接分享链接

## 53. 节点权限管理

> 原始路径：`/1142/1193/1208.html`  
> 相对路径：`1142/1193/1208.md`  
> JS Chunk：`app.7a5cbccd.js`

## 节点权限管理


## 说明

节点权限是含有操作权限的一个配置可操作功能的权限信息配置。公文流程上每个节点都有自己的一个权限信息。

公文节点权限分为四类：发文、收文、签报、交换



默认节点权限




## 配置

配置路径：公文管理->公文应用设置->节点权限



1、可新建自定义的节点权限

2、每个分类可设置一个默认的节点权限

编撰人：lichaoj




快速跳转



 * 节点权限管理
   * 说明
   * 配置



分享链接分享链接

## 54. 节点动作

> 原始路径：`/1142/1193/1209.html`  
> 相对路径：`1142/1193/1209.md`  
> JS Chunk：`app.7a5cbccd.js`

## 节点动作


## 说明

提供给节点权限用的可进行的动作。

可进行新建编辑操作





1、节点动作名称

2、可设置节点动作的态度

3、可设置节点动作要做的流程操作

4、可设置流程提交操作

使用时是直接在节点权限页面进行使用的



编撰人：lichaoj




快速跳转



 * 节点动作
   * 说明



分享链接分享链接

## 55. 公文升级

> 原始路径：`/1142/1210.html`  
> 相对路径：`1142/1210.md`  
> JS Chunk：`app.7a5cbccd.js`

## 公文升级


## 说明





第二种升级方案的手动方案：

在公文升级前做如下操作：

在正式环境的数据库中查询以下sql 以oracle为例： select form.name '表单名称', form.id '表单id', u.name '所属单位名称' , u.id '单位id' , '分区路径/' || to_char(file.CREATE_DATE,'yyyy') || '/' || to_char(file.CREATE_DATE, 'mm') || '/' || to_char(file.CREATE_DATE, 'dd') || '/' || to_char(file.id) '文件物理路径' from edoc_form form, ctp_file file , org_unit u where form.FILE_ID = file.id and form.DOMAIN_ID = u.id ;

 * 然后在正式环境中找到 文件物理路径下的所有文件，将找到的所有文件 放到 升级环境 的base/upload/edocupgradefiles/目录下， 该目录下全是具体文件，没有文件夹

 * 文件全部找到并放到 edocupgradefiles文件夹后，再进行公文升级

系统默认得文单文件 默认存在 2007/11/30 路径下 ，如果找不到 会去oa得目录下找默认文件



编撰人：lichaoj




快速跳转



 * 公文升级
   * 说明



分享链接分享链接

## 56. 对外接口

> 原始路径：`/1142/1211.html`  
> 相对路径：`1142/1211.md`  
> JS Chunk：`app.7a5cbccd.js`

## 对外接口


## 流程列表删除接口

提供监听流程在列表上删除的监听事件，来扩展处理在列表上删除时的逻辑

com.seeyon.apps.edoc.event.EdocDelEvent

调用方式：

只需要方法上注册@EdocDelEvent即可接收到事件数据

@EdocDelEvent
public void event(Object event){
    ......
}



## 流程发起接口

提供监听流程发起的监听事件，来扩展处理发起时的逻辑

com.seeyon.apps.edoc.event.EdocStartEvent

调用方式：

只需要方法上注册@EdocStartEvent 即可接收到事件数据

@EdocStartEvent
public void event(Object event){
    ......
}



## 流程取回接口

提供监听流程取回的监听事件，来扩展处理取回时的逻辑

com.seeyon.apps.edoc.event.EdocTakeBackEvent

调用方式：

只需要方法上注册@EdocTakeBackEvent即可接收到事件数据

@EdocTakeBackEvent
public void event(Object event){
    ......
}



## 流程回退接口

提供监听流程回退的监听事件，来扩展处理回退时的逻辑

com.seeyon.apps.edoc.event.EdocStepBackEvent

调用方式：

只需要方法上注册@EdocStepBackEvent即可接收到事件数据

@EdocStepBackEvent
public void event(Object event){
    ......
}



## 流程处理接口

提供监听流程处理的监听事件，来扩展处理处理时的逻辑

com.seeyon.apps.edoc.event.EdocProcessEvent

调用方式：

只需要方法上注册@EdocProcessEvent即可接收到事件数据

@EdocProcessEvent
public void event(Object event){
    ......
}



## 流程待办事项接收事件改变接口

提供监听流程待办事项接收时间改变的监听事件，来扩展处理待办事项接收时间改变时的逻辑

com.seeyon.apps.edoc.event.EdocReceivetimeChangeEvent

调用方式：

只需要方法上注册@EdocReceivetimeChangeEvent即可接收到事件数据

@EdocReceivetimeChangeEvent
public void event(Object event){
    ......
}



## 流程意见新增接口

提供监听流程处理新增了意见的监听事件，来扩展处理新增了意见时的逻辑

com.seeyon.apps.edoc.event.EdocAddCommentEvent

调用方式：

只需要方法上注册@EdocAddCommentEvent即可接收到事件数据

@EdocAddCommentEvent
public void event(Object event){
    ......
}



## 流程指定回退接口

提供监听流程指定回退的监听事件，来扩展处理指定回退时的逻辑

com.seeyon.apps.edoc.event.EdocAppointStepBackEvent

调用方式：

只需要方法上注册@EdocAppointStepBackEvent即可接收到事件数据

@EdocAppointStepBackEvent
public void event(Object event){
    ......
}



## 流程撤销接口

提供监听流程撤销的监听事件，来扩展处理撤销时的逻辑

com.seeyon.apps.edoc.event.EdocCancelEvent

调用方式：

只需要方法上注册@EdocCancelEvent即可接收到事件数据

@EdocCancelEvent
public void event(Object event){
    ......
}



## 流程新增跟踪人员接口

提供监听流程处理新增了跟踪人员的监听事件，来扩展处理新增了跟踪人员时的逻辑

com.seeyon.apps.edoc.event.EdocAddTrackMemberEvent

调用方式：

只需要方法上注册@EdocAddTrackMemberEvent即可接收到事件数据

@EdocAddTrackMemberEvent
public void event(Object event){
    ......
}



## 流程生成待办接口

提供监听流程处理产生待办数据的监听事件，来扩展处理产生待办时的逻辑

com.seeyon.apps.edoc.event.EdocAffairsAssignedEvent

调用方式：

只需要方法上注册@EdocAffairsAssignedEvent即可接收到事件数据

@EdocAffairsAssignedEvent
public void event(Object event){
    ......
}



## 流程移交接口

提供监听流程移交的监听事件，来扩展处理移交时的逻辑

com.seeyon.apps.edoc.event.EdocTransferEvent

调用方式：

只需要方法上注册@EdocTransferEvent即可接收到事件数据

@EdocTransferEvent
public void event(Object event){
    ......
}



## 流程终止接口

提供监听流程终止的监听事件，来扩展处理终止时的逻辑

com.seeyon.apps.edoc.event.EdocStopEvent

调用方式：

只需要方法上注册@EdocStopEvent即可接收到事件数据

@EdocStopEvent
public void event(Object event){
    ......
}



## 流程结束接口

提供监听流程结束的监听事件，来扩展处理结束时的逻辑

com.seeyon.apps.edoc.event.EdocFinishEvent

调用方式：

只需要方法上注册@EdocFinishEvent即可接收到事件数据

@EdocFinishEvent
public void event(Object event){
    ......
}



## 流程自动跳过接口

提供监听流程自动跳过的监听事件，来扩展处理自动跳过时的逻辑

com.seeyon.apps.edoc.event.EdocAutoSkipEvent

调用方式：

只需要方法上注册@EdocAutoSkipEvent即可接收到事件数据

@EdocAutoSkipEvent
public void event(Object event){
    ......
}



## 流程节点超期接口

提供监听流程节点超期的监听事件，来扩展处理节点超期时的逻辑

com.seeyon.apps.edoc.event.EdocNodeOverdueEvent

调用方式：

只需要方法上注册@EdocNodeOverdueEvent即可接收到事件数据

@EdocNodeOverdueEvent
public void event(Object event){
    ......
}


编撰人：lichaoj


快速跳转



 * 对外接口
   * 流程列表删除接口
   * 流程发起接口
   * 流程取回接口
   * 流程回退接口
   * 流程处理接口
   * 流程待办事项接收事件改变接口
   * 流程意见新增接口
   * 流程指定回退接口
   * 流程撤销接口
   * 流程新增跟踪人员接口
   * 流程生成待办接口
   * 流程移交接口
   * 流程终止接口
   * 流程结束接口
   * 流程自动跳过接口
   * 流程节点超期接口



分享链接分享链接

## 57. 公文问题索引

> 原始路径：`/1142/1881.html`  
> 相对路径：`1142/1881.md`  
> JS Chunk：`app.7a5cbccd.js`

## 公文问题索引


## 无效问题

FAQ名称                                         现象截图   一句话结论
【公文管理】“多人同时编辑”已开启，但依然提示：用户xx开始对此流程进行提交处理操作           此类格式的提示信息来自于流程锁，“多人同时编辑”配置属于表单锁。二者是不同的东西，没有关系。
【公文管理】附件控件取消下载权限后pdf文件就不能查看了                         Aspose转换服务不支持预览cap3附件控件中的pdf文件。查看pdf文件只能通过浏览器预览，而浏览器预览依赖于下载功能。所以取消掉附件控件的下载权限后，就无法查看表单控件中的pdf文件。
【公文管理】信创客户端上传PDF提示“您上传的正文类型系统不支持，请重新上传!”             国产信创环境暂不支持PDF文件，版式只支持OFD格式.。
【公文管理】公文的当前待办人显示不全                                   “当前待办人”有显示长度限制，并不会显示出全部的当前待办人。
【公文管理】流程复活提示“最后一个节点基本操作存在交换类型操作，不允许复活”               能够在OA上看到的节点权限都是新公文的节点权限。已分送的老公文不支持流程复活。
【公文管理】在拟文界面上传OFD正文成功，但是预览不了，发送后在流程中可以预览       暂无     发文拟文的时候正文不支持在线预览
【公文管理】公文查询-文单查询查不到老公文的数据                      暂无     文单查询只能查到基于cap3开发的新公文，查不到老公文
【公文管理】流程模板的“合并处理”已去掉，但是公文还是会合并处理              暂无     合并处理并不是一个全局配置
【公文管理】发文单有“PDF正文”页签，但是签收单没有“PDF正文”页签          暂无     公文交换时，如果发文单既有流式文件也有版式文件，那么触发的签收单上只会携带版式文件，不会携带流式文件
【公文管理】【协同工作】流程督办监控中点击“已超期”，查不到超期流程            暂无     流程督办监控中的【已超期】指的是节点的处理期限已超期，不是流程期限已超期。
【公文管理】打包下载功能下载得到的附件不全                         暂无     使用打包下载功能下载附件时，只能下载标题区和表单上的附件，不能下载评论区附件。
【公文管理】通过关联文档穿透查看公文时，有些按钮多了（或者少了）                     关联文档穿透时继承的节点权限不一致
【公文管理】添加快捷-协同应用-公文管理菜单中没有发文拟文                        快捷菜单中的发文拟文需要公文管理(封装)下的发文拟文才行。
【公文管理】线下占用/文号预留某个文号提示“文号已被使用或占用”，但是查不到被占用记录          在新建公文页面查看断号表中是否有目标文号。如果存在目标数据，则提示信息属于正常的业务表现。
【公文管理】收发统计穿透查看的公文待办人不是该部门/单位的人                       当前待办人不是这个部门/单位的人是可能的、合理的。
【公文管理】创建大流水文号时会立刻自动占用一批文号                     暂无     创建大流水文号时就是会把当前年其他机构代字已使用、预留的大流水号立刻强制占用。
【公文管理】首次上传正文时，会提示：重新上传正文，原正文内容将会丢失                   公文流程模板是可以预先绑定正文的，因此使用流程模板总是会出现该提示，告知用户上传正文会覆盖原有正文内容，提醒用户检查是否误操作。
【公文管理】公文签收单分办后，签收单中的附件带入收文单标题下了               暂无     签收单如果有附件则会将当前附件放在收文单的流程里面当作附件数据
【公文管理】公文单对应字段给了编辑权限还是不能编辑                            绑定的映射字段filesm，是上传附件后回填附件名称到该字段的，不是用来手动编辑的
【公文管理】某人的公文处理意见是图片                                   “文单签批”功能会将输入的或手写的文本转成一个图片，作为公文处理意见进行存储。


## 环境问题

FAQ名称                                          现象截图   一句话结论
【公文管理】公文待办里的意见框一闪而过                            暂无     公文开关中“意见填写位置”配置的是“文单”。在客户端浏览器响应比较慢的情况下就会出现这种现象。
【公文管理】提交、发送公文很慢，查询登记簿、公文管理很慢                   暂无     请先使用环境检测工具检查数据库是否缺索引，如果已使用工具确认不缺索引，再上报BUG处理。
【公文管理】公文待办提交报错“从前端获取数据失败，请重试！”                        如果在服务器上操作不回显问题，但是在其他客户端操作能回显问题，则说明是网络设备将参数过滤掉了。
【公文管理】使用Oracle数据库，机构代字为空的文号保存不成功               暂无     让用户不要使用空的机构代字。或者去除"EDOC_MARK_CATEGORY"表"CATEGORY_NAME"列的非空约束。
【公文管理】拟文、登记页面空白                                       此类问题常见于数据库同步、合版后。按方案修复数据。
【公文管理】Oracle环境无法修改文号定义                                修改数据库，去除"EDOC_MARK_CATEGORY"表"CATEGORY_NAME"列的非空约束；或者不要使用机构代字为空白内容的文号
【公文管理】公文提交/发送后，页面无法自动关闭。手动关闭页面后，公文已经提交/发送出去了   暂无     升级浏览器或打补丁兼容


## 错误配置、误操作引起的问题

FAQ名称                                                             现象截图   一句话结论
【公文管理】公文菜单中看不到某个公文数据或某个按钮                                                8.2版本新增了一个可配置的“公文管理(封装)”菜单，该菜单允许用户自行配置各页签下可查看的数据类型。
【公文管理】发文单交换详情页不能穿透查看签收单                                                  穿透由两个方面的参数控制：1、人员信息；当前人员需要具有【单位公文送文员】或【部门公文送文员】角色，或者是分送节点的处理人（代理人）2、系统配置；需要在seeyonConfig-【插件参数设置】中开启govdoc.chuantouchakan1和govdoc.chuantouchakan2
【公文管理】【协同工作】发送无响应                                                        尝试切换为标准正文，然后重试发送功能是否正常。
【协同工作】【公文管理】栏目中不显示特定数据，但是在菜单列表中能看到                                暂无     检查栏目是否有某种配置可以过滤数据。
【公文管理】公文文号被没有授权的其他单位使用                                                   用户自己手写的文号，不是系统带出的
【公文管理】使用“正文转公告”功能，得到的公告是word格式的，而不是PDF格式的                                公文正文既有word正文又有PDF正文情况下，如果用户需要公告是PDF正文，“正文转公告”时就需要勾选PDF
【公文管理】执行分送操作时提示“手写单位不能交换”                                                手工录入只会给控件填写显示值，不会填写组织id值。使用手工录入的数据执行分送动作，会因为无法获取到部门信息而导致交换业务异常
【公文管理】公文分送后，所选单位/部门未收到签收单                                         暂无     除非运维人员对公文业务非常熟悉，否则不建议删改预置签收文单和预置流程图。
【公文管理】调用模板提示：无调用模板权限，请联系公文管理员                                            拟文节点权限未配置【调用模板】动作
【公文管理】在公文列表中看到的标题和公文表单页看到的标题不同                                           模版没有配置动态刷新；参考方案修复数据
【公文管理】发文登记簿列表上部分公文没有签发日期                                                 公文单没有配置签发日期的公文元素；参考方案修复数据
【公文管理】公文文号丢失                                                      暂无     不要重复绑定公文元素
【公文管理】编辑待发公文提示没有发文拟文（或收文登记）权限                                            校验这个人是否有发文拟文菜单和发文拟文角色（或收文登记菜单、收文登记角色）
【公文管理】PC端能够显示表单附件，但移动端附件页签不显示                                            如果公文启用了移动端视图，且移动端视图未出现附件控件，则业务逻辑认为移动端无权限查看附件控件内容，所以无法在移动端附件页签中显示表单上的附件。
【公文管理】有大附件的签收单，分办时会等待很长时间，一直显示空白页                                        服务器在执行分办操作时，会复制签收单中附件的物理文件。附件越大，这一过程的耗时也就越长。
【公文管理】公文登记簿查不到数据或数据少了                                                    如果当前用户具有当前单位的“单位公文收文员”、“单位公文发文员”角色，则可查询出当前单位发起的所有发文、收文。否则，计算当前用户在当前单位具有哪些部门的“部门公文收文员”、“部门公文发文员”角色，仅查询出这些部门发起的发文、收文。如果不具有任何部门的收发文员角色，则查不到数据。
【公文管理】在待发事项栏目中无法编辑和发送公文，操作提示：你没有公文发起权                                    检查对应人员是否有 发文拟文人员 或 快速发文人员 角色
【公文管理】致信分享的公文无法查看，点击则提示无权限                                               对应节点没有配置转发动作，导致分享的公文，权限校验不通过
【公文管理】公文查询-条件查询-很多收文流程登记人不是收文发起人                                         收文单有配置create_person映射字段的配置，生成数据时，登记人就取这个字段的值。如果没有，再取公文的发起人
【公文管理】调用公文模板编辑文号，不显示断号按钮                                                 是否显示断号按钮是通过后台配置的，根据单位隔离
【公文管理】选不到某个公文文号                                                          1.文号需要授权给使用人员或部门或单位的，当前用户可能没有使用该文号的权限。2.公文流程模板可以绑定文号。如果该公文流程模板有绑定文号，则调用此流程模板时只能选择绑定的文号；
【公文管理】升级后，对已办公文执行归档操作，提示“公文xxx不允许归档！”                                    需确认处理的是新公文还是老公文，新、老公文是互相独立的两套节点权限。
【公文管理】提交后公文处理意见不会回填到文单上                                                  只有公文处理意见类型的控件才会回填意见
【公文管理】节点权限有“提交”动作，但是待办里不显示“提交”按钮                                         有“分送”动作的情况下会显示【分送】按钮，而不是【提交】按钮
【公文管理】公文移动端视图切线显示英文View1                                                 
【公文管理】未配置的公文表单，请联系后台单位管理员进入“公文管理-文单设置-发文单/收文/签报单/签报单”菜单下进行初始配置！          如果当前单位不存在可用的表单就会出现提示
【公文管理】提交一次会产生两条意见                                                        请检查公文文单上是否配置了“拟办意见”控件。
【公文管理】【分保插件】上传附件提示“请先设置文件密级，再上传附件”                                       确定开启了分保差距，检查公文单中是否设置有【文件密级】控件；上传附件之前是否正确填写了密级。
【公文管理】单位管理员使用流程督办监控搜不到某条公文                                        暂无     可登录集团管理员账号使用流程督办监控进行查询；删除掉具体的模板，查询条件只勾选笼统的【模板流程】
【公文管理】公文的节点权限分配了“归档”动作，但是没有收藏的按钮                                         流程属性中取消了归档权限
公文菜单给了权限，但是门户前台还是看不到该菜单                                                  实际上公文有两个菜单：【公文管理】和【公文管理（封装）】，门户设置的菜单和角色赋予权限的菜单不是同一个，就会出现这种现象。
自定义菜单或磁贴配置了某个菜单，但是首页还是看不到                                                公文管理有两个独立的菜单，一个叫【公文管理】，一个叫【公文管理（封装）】。他们下辖的子菜单在磁贴、自定义菜单配置中是混在一起的，且名称也是一样的，默认情况下无法区分。
【公文管理】“文号定义”的查询的规则                                                暂无     如果当前单位是某文号所属单位，或者当前用户有某文号的调用授权且当前单位是人员主单位。则当前用户能在【公文应用设置】-【文号定义】中查到这个文号。
【公文管理】在M3上打开公文会自动跳转到空白页面，PC端不会                                           检查该节点的节点权限，“默认显示”处是否勾选的是“全文签批单”。
【公文管理】文单中修改公文标题后，公文标题未发生变化                                               检查是否正确配置了动态标题。
【公文管理】公文套红印发日期没法依据书签更新到正文中                                        暂无     客户当前有多个公文视图，印发日期在第二个视图里面，能套红的视图又不存在印发日期字段所以不能套红
【公文管理】公文交换中找不到待签收的公文                                              暂无     交换类型的节点权限均未设置签收节点动作，会导致查询不出签收单。
【公文管理】收文查询中连续穿透标题关联公文后，穿透到某个收文中没有打印按钮                             暂无     关联文档为文档中心的文件时，需确保对应文件共享设置


## 需求问题

FAQ名称                                        现象截图   一句话结论
【公文管理】分办、签收、分送节点无法预览正文                              8.2SP1及以上版本，可以在公文开关中配置“公文交换时是否支持在线预览”；更低的版本升级解决或客开解决。
【公文管理】有附件的公文点击“分办”按钮后，页面无反应，要等很久才能弹出新建公文页面   暂无     建议先将大附件上传到文档中心，然后在公文中使用“关联文档”关联到这个附件。从而避免分办操作时复制附件物理文件。


## 高频编码问题

FAQ名称                                              现象截图   一句话结论
【公文管理】公文列表或公文登记簿不显示文号，但是公文表单上有文号                          8.1SP2、8.2、8.2SP1版本打补丁修复编码问题，参考方案修复数据
【公文管理】公文处理意见排序设置为人员排序号，处理意见排序不对                    暂无     8.0SP2~8.1版本无法解决。8.1SP1及以上版本，可上报BUG。
【公文管理】升级后查看历史公文会报错 For input string: “xxxx_yyyy”          9.0SP1版本打补丁修复编码问题
M3查看公文正文的时候，会把意见区滑上去                               暂无     8.0SP2~8.1SP1版本打补丁修复编码问题
【公文管理】【组织模型】主送/抄送单位非当前单位部门，公文单中不显示对应单位简称                  开启新选人组件
【公文管理】打包下载功能得到的文单内容空白或提示下载失败                       暂无     暂无


## 异常数据导致的问题

FAQ名称                                         现象截图   一句话结论
【公文管理】升级到9.0SP1版本后，紧急程度枚举的国际化资源显示不对                  执行sql，然后重启oa。
【公文管理】公文新建页面“预归档到”是灰的，无法选择                           如果没有配置预归档路径，正常情况下应该显示“无”。由于预归档路径非空，所以公文新建页面“预归档”功能被禁用。
【公文管理】收文管理-已办-没有按照时间排序                               数据库中历史旧数据没有完成时间数据，而SQL默认null的数据排序在前导致
【公文管理】有的文号可以重复发起 ，而有的会提示“发文字号已被占用，请重新选择”             根据方案清理异常数据
【公文管理】流程模板中设置正文类型为无，但是调用模板的时候正文类型还是灰色的，不可切换          模板数据异常，实际上是绑定了正文类型的，但是设计态显示的是“无”。重新配置正文类型，然后保存模板，可修复数据。
【公文管理】中间节点提交待办提示：发文字号已被占用                            检查占号配置是否合理，文号是否被其他文占用。手动释放目标文号或指定回退到相关节点，修改对应文号再提交
【公文管理】待办列表中点击公文提示“移动端不支持查看或处理”                       移动端对老公文没有支持，无法查看或处理
【公文管理】表单上紧急程度枚举值紧急，待办里显示平急                           设计变动导致，历史枚举值的显示名称是“紧急”，而不是标准的“平急”。使用sql修复数据
【公文管理】授权的套红模板选不到                                     重新上传正文套红模板
【公文管理】签收单没有签收、分办按钮                                   此类问题常见于客开产生的异常签收单，公文交换数据是通过“发文单-分送”、“收文单-转办”产生的，未经过分送和转办业务产生的签收单不会存在公文交换数据，也就没有签收、分办按钮。


## 常见咨询问题

FAQ名称
【公文管理】公文处理意见排序规则说明
【公文管理】升级公文后，自定义公文元素opinion系列字段全部丢失
【公文管理】分送时调用的签收单是哪一个
【公文管理】通过公文查询穿透查看公文，判断能否下载正文的规则是什么
【公文管理】公文查询中发文模版和收文模版需要修改名称，如何修改？
【公文管理】”输入文号大于当前文号+1000，请确认是否误操作“这个提示如何关闭
【公文管理】正文空白、丢失、损坏排查步骤


## 数据修复方案

FAQ名称
【公文管理】数据修复-将表单域的数据同步到公文扩展元素中
【公文管理】数据修复-同步表单数据到公文预置元素
【公文管理】数据修复-给公文文单补充人员处理意见
【公文管理】数据修复-调整公文处理意见的排序效果
【公文管理】数据修复-删除异常待办
【公文管理】数据修复-给公文处理意见补齐人员的签名
【公文管理】数据修复-升级后调用公文模板提示“文单字段名称存在重复，请修复文单后使用”
【公文管理】数据修复-SIGNET_DOCUMENT表清理重复数据
数据操作：人为失误撤销公文流程强制改为结束（恢复公文）
数据操作：删除协同或公文顶部区域的附件
数据操作：清理测试环境全部的公文数据
数据操作：公文文号修改方法
数据操作：公文附件替换方法
数据操作：公文正文替换方案
【公文管理】数据修复-删除公文督办数据
【公文管理】处理老公文进行分发提示“该类型下没有找到公文单，请到管理界面建立公文单”
【公文管理】数据修复-补充公文单主送、抄送的真实值
公文意见维护方案


## 升级过程相关问题

FAQ名称
【公文管理】升级公文交换数据报错2
【公文管理】老客户升级后，第一次启动OA进行公文升级非常慢
【公文管理】升级程序报错“Can't call commit when autocommit=true”
【公文管理】公文升级很慢，提示“文单物理文件不存在”
【公文管理】升级后紧急程度枚举由“普通”变成“无”

编撰人：luoyy


快速跳转



 * 公文问题索引
   * 无效问题
   * 环境问题
   * 错误配置、误操作引起的问题
   * 需求问题
   * 高频编码问题
   * 异常数据导致的问题
   * 常见咨询问题
   * 数据修复方案
   * 升级过程相关问题



分享链接分享链接

## 58. 引导

> 原始路径：`/1142/2052.html`  
> 相对路径：`1142/2052.md`  
> JS Chunk：`app.7a5cbccd.js`

## 引导

此页面用于帮助用户、区域及研发人员快速识别并查找对应模块的问题清单。 公文业务由3个主要模块组成：CAP3表单、公文、流版签。当前页的引导内容能够帮助您对公文业务有个整体的理解。 如果您只是想查找某个具体问题，但是由于不清楚公文业务的边界，不知道应该查找某个模块，可根据如下特征进行大致的问题归类。然后跳转到对应模块的问题索引页，查询常见问题清单。


## 一、CAP3表单

CAP3表单负责定义文单、视图、计算公式以及运行时文单数据的存储、展示。 通过如下链接跳转到CAP3表单问题索引

CAP3表单问题索引 https://open.seeyoncloud.com/v5doc2/1923/1922.html

**特征分类：【公文应用设置】-【X文单】**内的内容属于CAP3表单； 公文详情页上，表单页签下的内容，除公文处理意见和多单位多部门控件以外，都属于CAP3表单； 文单打印功能属于CAP3表单；


## 二、流版签

V5系统没有能力修改文件的内容，所有针对文档内容的展示、修改功能都是借助第三方产品的能力实现的。操作流式文件、版式文件、签章数据的功能模块统称为流版签。

正文中的内容属于流版签模块。 在线编辑和在线预览属于流版签模块。 套红、盖章功能属于流版签模块。

V5系统在发展过程中适配过许多第三方产品，因此这一块的分类比较繁杂，需要读者确认您所使用的是哪种第三方产品。如果您不了解各类流版签产品，可根据下文的内容进行简单区分。


## 二、1.金格控件

通过如下链接跳转到金格控件问题索引 金格常见问题索引 https://open.seeyoncloud.com/v5doc2/1136/1822.html

如果V5系统使用的是金格控件，且流版签模块的功能异常，需要先进行环境自检，确认金格控件是否正常安装、运行。金格控件自检步骤见链接： 金格控件自检步骤 https://open.seeyoncloud.com/v5doc2/1136/1137.html 特征分类： 以下页面属于金格控件，**金格控件在9.0及以后的版本已经弃用。**金格控件只能以编辑页面和只读编辑页面打开文档。


## 二、2.OfficeTrans转换(Aspose)

OfficeTrans转换是致远基于第三方产品Aspose开发的一个简易在线预览服务，它只有一个能力就是将流式、版式文件转换成一个Html页面，使得V5系统可以预览文件内容。 通过如下链接跳转到OfficeTrans转换问题索引 OfiiceTrans在线预览问题索引 https://open.seeyoncloud.com/v5doc2/1136/1846.html

特征分类： 以下页面属于OfficeTrans转换：


## 二、3.金山中台

通过如下链接跳转到金山中台问题索引 金山中台（金山weboffice）问题索引 https://open.seeyoncloud.com/v5doc2/1136/1967.html

特征分类： 以下页面属于金山中台，金山中台的编辑和预览是两个单独的子服务。


## 二、4.WPS加载项(国标Office)

如果V5系统使用的是WPS加载项，且流版签模块的功能异常，需要先进行环境自检，确认WPS加载项是否正常安装、运行。WPS加载项自检步骤见链接： 国标Office自检步骤 https://open.seeyoncloud.com/v5doc2/1136/1933.html

特征分类： 以下页面属于WPS加载项，WPS加载项在9.0及以后的版本已经弃用。


## 二、5.数科

通过如下链接跳转到数科问题索引 数科问题索引 https://open.seeyoncloud.com/v5doc2/1136/2050.html

9.0SP1版本开始启用文档通+数科的流版签组合，数科用于预览、盖章、转版操作。


## 二、6.文档通

通过如下链接跳转到文档通问题索引 文档通问题索引 https://open.seeyoncloud.com/v5doc2/1136/2051.html

特征分类： 以下页面属于文档通，9.0SP1版本开始启用文档通+数科的流版签组合，文档通用于在线编辑功能。


## 二、7.永中在线编辑、在线预览

通过如下链接跳转到永中在线编辑问题索引 永中wo（在线编辑）问题索引 https://open.seeyoncloud.com/v5doc2/1136/1857.html

通过如下链接跳转到永中在线预览问题索引 永中dcs（在线预览）问题索引 https://open.seeyoncloud.com/v5doc2/1136/1932.html

永中的产品只在8.2和8.2SP1两个版本中使用，已弃用。


## 三、公文

除公文详情页“流程”页签下的内容，以及上文提到的内容，其他的功能都可归类为公文模块。通过如下链接跳转到公文模块问题索引 公文问题索引 https://open.seeyoncloud.com/v5doc2/1142/1881.html

编撰人：luoyy


快速跳转



 * 引导
   * 一、CAP3表单
   * 二、流版签
     * 二、1.金格控件
     * 二、2.OfficeTrans转换(Aspose)
     * 二、3.金山中台
     * 二、4.WPS加载项(国标Office)
     * 二、5.数科
     * 二、6.文档通
     * 二、7.永中在线编辑、在线预览
   * 三、公文



分享链接分享链接

## 59. 致信

> 原始路径：`/1146/`  
> 相对路径：`1146/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称         URL
致信IM消息传输逻辑图   致信IM消息传输逻辑图

分享链接分享链接

## 60. 致信IM消息传输逻辑图

> 原始路径：`/1146/1308.html`  
> 相对路径：`1146/1308.md`  
> JS Chunk：`app.7a5cbccd.js`

## 致信IM消息传输逻辑图


## 背景

致信作为致远V5产品IM通信工具，提供统一的企业办公业务通讯工具，支持统一的业务通讯，高效的实时通信，以人为中心的工作沟通，稳健的系统运行以及安全的通讯链路。

致信支持多端、多系统使用：

 * PC客户端支持Windows、Mac、Linux、信创端运行（部分客户端因系统差异需要定制打包客户端）
 * 移动端支持iOS、安卓，在M3 APP中运行

> 不支持在微协同、钉钉、飞书等第三方APP下运行

对于安全要求较高的客户，不允许办公聊天和文件传输使用微信、钉钉、飞书，针对此类场景，我们推荐客户使用致信，以获得安全可靠的数据管理。

本章针对致信发送和接收消息、文件场景，提供完整的数据传输流向说明，以供用户部署、安全审计参考。

致信消息体分两类：消息和附件，这两类消息体的文件传输逻辑和存储不同。

 * 消息传输：主要是聊天文字内容，这类数据加密存储于致信服务器上
 * 文件传输：主要是文件、图片内容，这类数据加密存储于OA附件目录下


## 消息传输逻辑

消息数据加密存储于致信服务器上，故消息的通信均围绕致信服务器展开，致信的公有云和私有化对数据传输、网络要求不同，故本文分两个小节分别介绍。

致信基于融云实现了消息的一体化安全稳定管理。


## 致信公有云-消息传输逻辑

使用致信公有云客户，意味着致信的消息加密存储于致信公有云服务器。对于存在内外网隔离的客户，需要保证：

 * 客户内网能够访问到致信公有云，保障内网致信发送的消息能传递到致信公有云
 * 反之致信公有云能通过客户网络防火墙，访问到客户内网客户端，保障内网致信客户能收到消息

详细配置见《致信安装维护手册》- 致信公有云内外网解决方案章节。

致信公有云消息传输和数据管理安全简介：

 * 端到端的加密传输：消息从客户端发送时已经加密，整个网络发送传输过程是加密的
 * 数据存储于致信公有云云端，采用租户模式实现逻辑隔离，消息采用二进制加密存储
 * 支持HTTPS安全传输协议
 * 支持WSS，实现安全的WebSocket通信

> 更详细的安全说明可联系总部提供《融云IM与音视频产品安全说明》文档。

致信公有云优缺点：

 * 优点：易部署、易配置、价格低
 * 缺点：消息数据存储于云端，不适合安全要求较高的客户




## 致信私有云-消息传输逻辑

使用致信私有云客户，意味着致信的消息加密存储于客户内网。对于存在内外网隔离的客户，需要保证：

 * 外网客户端消息能推送到致信内网服务器，保持内外网消息端口互通
 * 如需要M3收到离线消息，还需要保障致信内网服务器能出访所有手机厂商的离线消息服务网站

详细配置见《致信安装维护手册》- 致信私有化安装配置全章节内容。

致信私有云消息传输和数据管理安全与公有云相同（细节参考“致信公有云-消息传输逻辑”中关于安全的描述），并且由于数据存储于内网私有化服务器，从物理层面又极大地提高了数据安全性。

> 更详细的安全说明可联系总部提供《融云IM与音视频产品安全说明》文档。

致信私有云优缺点：

 * 优点：消息数据存储于内网，最大化的数据安全性，适合安全要求较高的客户
 * 缺点：硬件成本、实施运维成本均高于公有云




## 附件上传下载逻辑（公有云和私有云相同）

致信聊天窗口中的附件文件（含图片）上传后存储于OA协同服务器附件区，这块与致信消息（存储于致信服务器）不同。故只要保证客户端与OA服务器内外网联通，即可保证附件的上传和下载。再简单点说，致信的附件上传和下载均走的标准接口，与OA系统内其它页面上传下载无异。

故致信附件安全规则为：

 * 附件上传采用html的from-data方式，文件内容存放于body，如果担心传输过程被篡改，可使用HTTPS协议传输
 * 附件上传到OA服务器，存储于OA服务器附件磁盘上，默认进行了加密，加密方案采用系统管理员安全存储相关配置




## 致信与OA技术实现逻辑图

以下为技术实现场景：




## 总结

致信消息存储于致信服务器，是客户端与致信服务器 端到端的传输，默认不存在中间缓冲服务器存储。但如果私有化部署客户要使用M3离线消息，则一定会向手机厂商的离线消息服务器中转数据，此时就需要客户取舍是否启用离线消息。

附件存储于OA协同服务器，是客户端与致信服务器 端到端的传输，不存在中间缓冲服务器存储。

编撰人：het




快速跳转



 * 致信IM消息传输逻辑图
   * 背景
   * 消息传输逻辑
     * 致信公有云-消息传输逻辑
     * 致信私有云-消息传输逻辑
   * 附件上传下载逻辑（公有云和私有云相同）
   * 致信与OA技术实现逻辑图
   * 总结



分享链接分享链接

## 61. 浏览器

> 原始路径：`/1870/`  
> 相对路径：`1870/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称              URL
Chrome浏览器扩展插件黑名单   Chrome浏览器扩展插件黑名单

分享链接分享链接

## 62. 背景

> 原始路径：`/1870/1871.html`  
> 相对路径：`1870/1871.md`  
> JS Chunk：`app.7a5cbccd.js`

## 背景

用户在浏览器上安装了某些劫持性的浏览器扩展插件，导致在使用OA产品过程中某些功能的代码、请求信息等被劫持，影响用户使用，因此此文将历史用到的浏览器扩展插件进行列举，欢迎大家补充。


## 表现特征

功能性方面表现特征众多，宏观规律表现常见为特定电脑特定浏览器无法使用，但其他电脑上或者其他浏览使用OA功能正常。


## 扩展插件黑名单

序号   插件名称                                          插件截图   影响功能                                                     影响级别   OA图例
1    Katalon Recorder (Selenium tests generator)          门户空间报错空白                                                 P0     
2    篡改猴                                                  OA系统重点击保存无反应                                             P0     -
3    AIX智能下载器                                             点击保存时出现报错：<div class="mpa-sc mpa-plugin-image-gatherer   P0     
                                                          mpa-new mpa
4    密码生成工具                                               门户空间显示空白                                                 P0     -

编撰人：luxxcd


快速跳转



 * 背景
 * 表现特征
 * 扩展插件黑名单



分享链接分享链接

## 63. 云联中心

> 原始路径：`/1895/`  
> 相对路径：`1895/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称    URL
云联常见问题   云联常见问题
平台/框架    平台/框架

分享链接分享链接

## 64. 云联常见问题

> 原始路径：`/1895/1896.html`  
> 相对路径：`1895/1896.md`  
> JS Chunk：`app.7a5cbccd.js`

## 云联常见问题


## 1、云联常见问题环境检查清单


## 2、云联常见问题列表

序号   问题描述                                      问题截图
1    【云联证书】V7.1系列及以前版本云联证书的安装                  
2    【云联中心】系统管理员云联中心云联校验提示不通过的情况               
3    【云联中心】CAP4应用包属性面板中提示许可单位与当前系统绑定的云联企业不一致   
4    【云联】更新安装云联证书后显示旧企业名称问题                    
5                                              

编撰人：luxxcd


快速跳转



 * 云联常见问题
   * 1、云联常见问题环境检查清单
   * 2、云联常见问题列表



分享链接分享链接

## 65. 电子邮件

> 原始路径：`/1909/`  
> 相对路径：`1909/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称        URL
电子邮件常见问题列表   电子邮件常见问题列表

分享链接分享链接

## 66. 电子邮件常见问题列表

> 原始路径：`/1909/1912.html`  
> 相对路径：`1909/1912.md`  
> JS Chunk：`app.7a5cbccd.js`

## 电子邮件常见问题列表

序号   问题描述                                                                                                                     问题截图
1    【电子邮件】收不到邮件提醒                                                                                                            
2    [【电子邮件】系统邮箱配置参数无误，但测试发送邮件即报错"发送失败，请确认您设置的邮箱支持SMTP服务"](https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+NzY2   
     "【电子邮件】系统邮箱配置参数无误，但测试发送邮件即报错"发送失败，请确认您设置的邮箱支持SMTP服务"")
3    【电子邮件】邮件链接穿透失败，提示链接失效、链接过期、或者显示404                                                                                       
4    【电子邮件】邮件发送常见异常报错与处理方案对照                                                                                                  
5    【电子邮件】邮箱密码存储方式                                                                                                           
6    【电子邮件】写邮件--内部员工添加，选择不到任何人                                                                                                

编撰人：lijingyf、chenm、liuyc


快速跳转



 * 电子邮件常见问题列表



分享链接分享链接

## 67. 组织模型

> 原始路径：`/1915/`  
> 相对路径：`1915/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单          URL
组织模型常见问题列表   组织模型常见问题列表

编撰人：hufei、admin、lichaoj、luoyy


快速跳转







分享链接分享链接

## 68. 组织模型问题索引

> 原始路径：`/1915/1916.html`  
> 相对路径：`1915/1916.md`  
> JS Chunk：`app.7a5cbccd.js`

## 组织模型问题索引


## 选人控件问题

问题描述                            问题截图   总结
【组织模型】开启新选人组件模式                        老选人控件功能异常时，建议尝试开启新选人组件（注意新选人不支持ie10以下版本的浏览器）
【组织模型】选人面板搜索部门名称搜不到内容                  截图勾选了【查全集团】，在这种情况下只能搜索人员，不能搜部门。
【组织模型】选人面板搜索名称时能查到其他人           暂无     这里是做的分词搜索,包含所有单字的名字都算作命中，不是只搜索出名称全匹配的人员。
【组织模型】在选人面板选择人员后“最近”页签里没显示该人员   暂无     只有从选人页面中选择人员并确定后,选人列表的人员才会出现在“最近”页签中


## 升级问题

问题描述                  问题截图   总结
【组织模型】组织rest接口提示401   暂无     为了安全考虑,安全补丁对部分接口做了限制,下面是被限制的接口以及对应需要的角色权限.


## 无效问题

问题描述                                  问题截图   总结
【组织模型】8.0以上版本选人、通讯录的人员排序说明                   暂无
【组织模型】通讯录或选人界面展示的人员排序和组织架构内设置的排序不一致   暂无     如果设置了部门人员排序或岗位人员排序，那么通讯录和选人面板两处，在点击部门、岗位的时候，展示的人员优先按部门人员排序或岗位人员排序的顺序展示，而不是按组织人员信息中的人员排序展示。
【组织模型】OA账号自动停用                               OA有一个账号多少天未登录系统会自动停用的功能，如不需要，关闭即可
【组织模型】修改某个人员排序号后，其他人员的排序号也会变更         暂无     人员修改时排序号默认是插入处理方式,此时如有相同的排序号,则大于此排序号的人排序号都会被自动加1
【组织模型】人员有副岗的情况下，通讯录岗位显示问题             暂无     人员有副岗的情况下，通讯录显示的岗位优先展示点击部门所在的岗位。


## 需求问题

问题描述                                 问题截图   总结
【组织模型】兼职时选人面板看不到编外人员页签               暂无     选人面板不支持切换单位后再选择编外人员
【组织模型】单位设置访问权限后不生效                   暂无     每个单位设置的权限只对自己单位生效,不会对子单位生效
【组织模型】选人定制页面看不到创建自定义选人组件             暂无     单位管理员创建的自定义选人均只能在对应创建的模块处修改
【组织模型】离职员工再次入职，触发更新报错“请先启用人员再更新数据”   暂无     CAP4触发不支持处理停用的人员


## 配置问题与常见误操作

问题描述                                 问题截图   总结
【组织模型】新建人员账号提示用户名重复，没找到重复的           暂无     检查离职人员、停用账户、未分配人员、编外人员
【组织模型】单位停用提示：单位存在未停用部门，操作失败          暂无     单位下存在未删除的人员、部门、岗位、组、职务级别、子单位都无法成功删除单位，需要先将单位下的这些数据停用后才可正常停用单位
【门户】某个用户的角色未授权菜单，但是他仍然能看到此菜单                点击【查看角色】，弹出的列表内容中显示的是该账号完整的角色信息。对照完整角色信息检查菜单授权。
【组织模型】调整人员职务或部门会导致人员角色变化                    检查是否将角色授权分配给了职务、部门
V-JOIN 微信连接设置保存失败                           请按文档要求配置
如何修改vjoin服务号按钮名称                     暂无     1.修改后没有将名称更新到微信.2.名称过长,微信对按钮名称长度有限制,超过5会失败.3.更新后微信会有延迟.
【组织模型】设置人员信息字段不在通讯录中显示               暂无     单位管理员-组织模型管理-通讯录设置-显示字段设置
【组织模型】添加一个部门，但是在部门下新建人员选不到想要的岗位             单位管理员-组织模型管理-组织机构管理-部门管理修改对应部门找到部门岗位，添加想要的岗位保存即可
【组织模型】部门名称设置的后面没有小地球，不能设置多语言                系统管理员-系统设置-系统模块管理开启数据国际化重启
向上访问级别范围修改不生效                        暂无     单位和集团的名称一致导致保存不生效.
【组织模型】单位中添加的自定义单位角色，在表单授权的选人面板中选不到   暂无     单位创建的自定义单位角色不支持，就是选不到。集团创建的角色才支持选择在选人页面展示。
【组织模型】选人面板选中部门，下属人员显示不完整             暂无     选人面板选中部门只会展示该部门下属的有效人员，无效人员会被过滤掉。


## 数据异常

问题描述                             问题截图   总结
【组织模型】导入工资提示人员未找到                暂无     可能原因如下:1.对模板列有过改动;2.填写的部门、编号等数据和OA内数据不一致;3.模板含有OA无法识别的空格.
【组织模型】人员信息没有新建等按钮                       检查使用到的枚举项名称,将特殊字符去掉即可恢复正常.
【组织模型】选岗位提示有超过职务级别访问范围的人员，不能选择   暂无     预置数据不支持此场景，可定制化修改


## 环境问题

问题描述                    问题截图   总结
【组织模型】新选人中无法搜索部门,人员名称          可能是该文件夹缺少新建/修改文件的权限导致


## 数据修复

问题描述                        问题截图   总结
【组织模型】导入人员有多个相同的部门名称，怎么区分          暂无


## 咨询问题及操作教程

问题描述                             问题截图   总结
【组织模型】调整选人界面中某个部门的人员显示顺序                单位管理员组织模型管理-人员信息管理-人员排序管理
【组织模型】调整兼职人员排序                          暂无
【组织模型】审计管理员audit-admin登录密码如何重置          暂无
【组织模型】怎么给用户多个单位的单位管理员权限                 暂无
【组织模型】工资条中的字段存储在哪里                      暂无
【组织模型】离职后重新入职的账号应该如何启用                  暂无
【组织模型】单位、部门、岗位、人员档案上新增自定义字段             暂无
【组织模型】节点封装加签-自定义选择的组件名称是怎么创建的           开启新选人组件，进入应用管理中心-基础数据-选人定制页签
【组织模型】如何批量修改人员信息                 暂无     如果需要修改的信息是相同的，那么可以使用高级批量修改；否则，采用Excel导入导出
【组织模型】查看组织信息修改日志                        登录系统管理员-系统日志-应用日志，操作模块选择组织信息管理
【组织模型】一个账号如何管理多个单位                      暂无
【组织模型】怎么使用系统中的工资管理               暂无     登录单位管理员-组织模型管理-角色授权管理-角色授权-选择工资管理员-分配人员
【组织模型】如何实现自动创建人员账号               暂无     通过表单触发实现自动创建人员账号
【组织模型】组的所属范围和公开范围有什么区别                  “公开范围”内的成员能查看到并使用该组，如果不设置“公开范围”默认全单位可见。
【组织模型】主数据怎么设置为流程里面的分支条件          暂无     增加一个下拉控件，数据关联表单里面的部门可以选择到，然后再用该下拉控件做分支条件


## 客开常见错误

编撰人：hufei、luoyy


快速跳转



 * 组织模型问题索引
   * 选人控件问题
   * 升级问题
   * 无效问题
   * 需求问题
   * 配置问题与常见误操作
   * 数据异常
   * 环境问题
   * 数据修复
   * 咨询问题及操作教程
   * 客开常见错误



分享链接分享链接

## 69. CAP3表单

> 原始路径：`/1923/`  
> 相对路径：`1923/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称        URL
CAP3表单问题索引   CAP3表单问题索引

分享链接分享链接

## 70. CAP3表单问题索引

> 原始路径：`/1923/1922.html`  
> 相对路径：`1923/1922.md`  
> JS Chunk：`app.7a5cbccd.js`

## CAP3表单问题索引


## 无效问题

FAQ名称              现象截图   一句话结论
【公文管理】发文单点击枚举没反应          如果要修改绑定的枚举值，需要先取消已经绑定的映射字段才行


## 配置问题

FAQ名称                                现象截图   一句话结论
【表单应用】【CAP3】多行文字不换行显示                       可能是infopath设置问题，请参照解决方案里的步骤进行确认和修复
【CAP3】文单字体大小不一致                             需检查下xsn文件对应字段字体大小是否正确设置
【CAP3】【公文管理】待办提交之后，计算公式得到的数据从表单上消失          配置了计算公式的表单域需要加上视图的编辑权限，并绑定到流程中的某个节点权限上，这样计算公式结果才能入库保存。
【CAP3】【公文管理】表单初始值提交后消失                      配置了初始值的表单域需要加上视图的编辑权限，并绑定到流程中的某个节点权限上，这样初始值才能入库保存。


## 异常数据

FAQ名称                  现象截图                               一句话结论
【CAP3】发起流程后表单的字段数据丢失   调用CAP3的模板发起流程后，待办中查看表单发现某个字段数据为空   1个域在某个视图中出现了多次，或者是主表、重复表对应域放在了错误的视图位置


## 设计变更

FAQ名称                                  现象截图   一句话结论
【CAP3】/rest/form/getformdata接口无法正常调用          此接口存在安全缺陷，因此在高版本中需要使用信道来调用，不允许直接使用token进行调用。


## 数据修复

FAQ名称
更新表单管理，cap3表单及公文的所属人所属单位
数据操作：删除CAP3表单数据
【CAP3】数据操作：已经产生数据，录入类型不能修改，否则会丢失数据


## 常见咨询问题及对应方案

FAQ名称
【表单】如何查询CAP3表单回写失败记录
CAP3菜单配置到CAP4
数据库解析CAP3XML中的表名称
cap3流程表单添加触发条件

编撰人：luoyy


快速跳转



 * CAP3表单问题索引
   * 无效问题
   * 配置问题
   * 异常数据
   * 设计变更
   * 数据修复
   * 常见咨询问题及对应方案



分享链接分享链接

## 71. 文化建设

> 原始路径：`/1928/`  
> 相对路径：`1928/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称      URL
文化建设常见问题   文化建设常见问题

分享链接分享链接

## 72. 文化建设常见问题FAQ清单

> 原始路径：`/1928/1929.html`  
> 相对路径：`1928/1929.md`  
> JS Chunk：`app.7a5cbccd.js`

## 文化建设常见问题FAQ清单


## 【文化建设常见功能】

模块分类    FAQ名称                                                      问题现象描述
新闻或公告   【文化建设新闻公告】新闻公告添加、取消置顶后，在某些地方查看没有生效                         新闻或公告设置置顶后，在指定位置查看却没有生效
新闻或公告   【文化建设】部分含有图片的新闻公告，图片无法正常显示                                 新闻或公告插入图片后，发布时能够正常查看，但是发布后再穿透查看图片无法正常显示
新闻或公告   【文化建设】新闻公告发布后，登录前门户不显示                                     新闻或公告发布后但是无法在登录前门户看到该数据
新闻或公告   【文化建设】文化建设进入新闻、公告菜单后，不能直接展示列表内容或有缺失，需要再点击单位新闻、公告按钮才显示      从文化建设菜单进入新闻或公告首页，显示不出列表数据或数据有缺失
新闻或公告   【文化建设】标准正文图片下载显示的尺寸分辨率与上传时不一致                              含有图片的新闻或公告上传的图片分辨率和尺寸与下载下来同一张图片分辨率、尺寸不一致
新闻或公告   【文化建设】可以统计某个月的发布的新闻的点击量等情况吗                                新闻或公告的点击量可以进行统计吗？在哪个位置统计？（注意FAQ中截图示意是使用的新闻，公告也是类似的操作）
新闻或公告   【文化建设】发布新闻、公告可以走审批流程吗？有，请配过程                               新闻或公告怎么配置流程审批
新闻或公告   【文化建设】新闻公告配置的审批流程，在审批过程中，能否修改新闻公告的标题或正文内容？                 通过流程审批发布的新闻或公告，想要修改正文内容或这标题应该怎么操作？
新闻或公告   【文化建设】新闻公告能否去统计公告中每个部门发送了多少文章的数量，统计完之后能否放到空间栏目以图表的形式去展示？   新闻或公告发布的数据可否从部门维度去统计数据，功能在哪个位置，应该怎么操作
新闻或公告   【文化建设】打印内容显示不全，有遮挡、空白等                                     新闻或公告点击打印，打印的内容不遮盖或者有空白应该怎么解决
新闻或公告   【文化建设】查看新闻的时候不想要水印要怎么设置（链接待公示，暂未公布）?                       新闻或公告不想显示水印应该如何配置
公告      【文化建设】公告发起以后到期了,想更改一下到期时间可以吗？                              公告的公示日期（过期日期）到了，可以修改公示日期吗？怎么修改？
公告      【文化建设】公告提示：该流程为应用审批流程，不支持直接发布，是否继续提交?                      公告发布时提示：“该流程为应用审批流程，不支持直接发布，是否继续提交？”
公告      【文化建设】公告的发布人员显示的是审核人员                                      公告发布后，发布人员位置却显示的是公告板块的审核员是何原因
公告      【文化建设】公告是否有字数限制                                            公告内容是否有字数限制，如果有，那限制是多少？
公告      【文化建设】二级单位发公告可以选择三级单位吗，在哪里看                                二级单位发布的公告，三级单位能看吗？在哪个位置可以查看？
调查      【文化建设】调查模板可以授权给其他人使用吗？                                     怎么保存调查模板，保存的调查模板可以授权给别人使用吗？
享空间     【文化建设】随意秀上传的相片可以删除吗？                                       享空间（随意秀）中发布的数怎么删除
讨论      【文化建设】发帖求助功能如何指定人员回复及禁止回复                                  发布的讨论能否设置禁止回复，或者禁止指定人回复

##【文化建设常见数据操作】

| 模块分类 | FAQ名称 | 问题现象描述 | | :------------: | :------------: | | 公告 | 【文化建设】8.1sp1版本以下升级到8.1sp1以上版本后，部分公告打开查看乱码，或查看原文档乱码 | 低版本升级到8.1sp1以上版本后以前的公文转公告数据查看出现乱码无法正常打开，经排查是数据问题，需要进行数据修复 | | 新闻或公告 | 【文化建设】数据操作：修改数据库将单位新闻公告改成集团的新闻公告 | 新闻公告从单位板块迁移到集团板块 |

编撰人：wanjl




快速跳转



 * 文化建设常见问题FAQ清单
   * 【文化建设常见功能】



分享链接分享链接

## 73. 文档中心

> 原始路径：`/1930/`  
> 相对路径：`1930/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称      URL
文档中心常见问题   文档中心常见问题

分享链接分享链接

## 74. 文档中心常见问题

> 原始路径：`/1930/1931.html`  
> 相对路径：`1930/1931.md`  
> JS Chunk：`app.7a5cbccd.js`

## 文档中心常见问题

##【文档中心常见配置问题】

分类              FAQ名称                                                       现象及描述
权限问题 （高频）       【文档中心权限】文档中心可以搜索出某个文档，点击提示：您无权限打开此文档                        文档中心打开某个文件提示：“您无权限打开此文档！”
权限问题            【文档中心权限】文档中心共享设置有某个单位或部门，但是目标单位或部门新增人员确没有对应文档的权限            文档中心某个文件共享设置有某个单位或部门，但是目标单位或部门新增人员却没有对应文件的权限
权限问题            【文档中心】文档中心里面的文件夹，怎么授权给指定的人或者部门里的人来查看、编辑、修改这个文件夹内的文档         文档中心文件或文件夹怎么给不同人员、组织授予不同的权限，每个权限的权限范围包括哪些？
功能配置**（高频）**    【文档中心排序】文档中心排序设置不生效，设置高级排序之后，文件列表排序还是乱序                     文档排序设置后却不生效
功能配置**（高频） **   【文档中心】文档中心上传文档，发布博客、删除之前上传的文档、单位管理员点开存储空间管理等报错              文档中心上传文档，发布博客、删除之前上传的文档、单位管理员点开存储空间管理等操作，页面出现报错有报错：org.springframework.dao.DataIntegrityViolationException，应该如何解决
功能配置**（高频） **   【文档中心下载】文档中心批量下载有时候点了没反应，有时候没有批量下载的按钮                       文档中心批量下载有时候点了没反应，有时候没有批量下载的按钮，导致该问题有多种原因，FAQ中详细分析
功能配置            【文档中心】需要授予什么权限才能进行文档中心的文档排序？                                什么角色权限，才能对文档中心的数据进行排序操作
功能配置            【文档中心】文件创建人是xxx，但是实际不是他上传的文档                                文档中心有来源不明确的数据，需要排查来源
功能配置            【文档中心】配置了多个内容类型，编辑了其中一个文档属性后，其他自定义文档属性就丢失了                  文档中心配置了多个内容类型，编辑了其中一个内容类型的文档属性（假设是：内容）后，然后切换到另一个内容类型，编辑保存一下其他自定义文档属性（假设是文号）。然后上页面查看，之前那个保存的那个文档属性的内容就丢失了
功能配置            【文档中心】文档中心中公文档案显示列设置了“归档状态”，“归档时间”但是前台看不到                   文档中心设置了显示列“归档状态”，前台却不显示的原因分析
功能配置            【文档中心】文档中心“发送到”被功能置灰                                        文档中心“发送到”无法正常使用
功能配置            【文档中心】公文归档到文档中心，需要文档中心增加一列显示公文文号                            文档中心归档的公文应该怎么设置显示公文文号
功能配置            【文档中心】文档中心上传excel编辑按钮为灰色                                    【FAQ链接待审核公示】文档中心上传的excel编辑按钮是灰色
功能配置            【文档中心】不想收到新增文档的消息怎么关闭？                                      【FAQ链接待审核公示】文档中心怎么关闭新闻修改文档等的消息提醒
功能配置            【文档中心】文档中心阅读信息在哪导出？                                         文档中心文档的阅读、下载日志等，怎么查询导出，怎么使用此功能？
功能配置            【文档中心】知识门户中的我的学习区、单位学习区、集团学习区的数据从哪里来的？                      栏目空间中个人几种学习区栏目的数据是从哪里来的？
功能配置            【文档中心】文档中心上传文档，发布博客、删除之前上传的文档、单位管理员点开存储空间管理等报错              文档中心上传文档，发布博客、删除之前上传的文档、单位管理员点开存储空间管理等操作，页面出现报错有报错：org.springframework.dao.DataIntegrityViolationException，应该如何解决
功能配置            【文档中心阅读】文档中心pdf格式的文档在上传替换过后阅读数量被清空，但文档日志里面依然存在修改之前的查看文档记录   pdf，图片等信息版式文件（无法编辑的文档）重新上传替换后，阅读数量会被清空，分析原因
已解决编码问题 （高频）    【文档中心】空间栏目中的文档中心栏目显示数据和文档中心文件显示顺序不一致                        空间栏目中的文档中心栏目显示数据和文档中心文件显示顺序不一致
数据库操作           【文档中心】文档中心数据被删除之后能否恢复，删除时物理文件是否同步删除                         文档中心数据删除后怎么恢复，如何查找文档中心对应的物理文件数据
数据库操作           数据操作：【文档中心】如何查找文档中心文件的树形结构，以及文件对应的物理文件                      如何去数据库获取文档中心的树形结构（层级关系），现总结获取方法步骤
数据库操作           【文档中心】人员已离职，升级后文档中心的共享显示了离职人员对文件夹的全部权限                      处理文档中心授权的历史坏数据
数据库操作           【文档中心】数据操作：用户误删除文档库中的某个文档夹，需要进行还原数据                         用户误删除文档库中的某个文档夹，如何进行数据还原

编撰人：wanjl


快速跳转



 * 文档中心常见问题



分享链接分享链接

## 75. 智能合同

> 原始路径：`/2794/`  
> 相对路径：`2794/README.md`  
> JS Chunk：`app.7a5cbccd.js`

子菜单名称    URL
模块业务逻辑   模块业务逻辑
产品文档清单   产品文档清单

分享链接分享链接

## 76. 智能合同产品文档清单

> 原始路径：`/2794/2796.html`  
> 相对路径：`2794/2796.md`  
> JS Chunk：`app.7a5cbccd.js`

## 智能合同产品文档清单

智能合同产品的可下载资料包涵盖了从理解、部署到使用的全流程文档，具体包含：指导系统环境搭建与配置的产品安装部署手册、帮助实施团队落地的实施指南、指导终端用户操作的用户手册、用于演示汇报的产品介绍PPT，以及清晰罗列所有核心能力的功能清单，提供了全面的产品支撑，助您从零到一快速掌握产品。


## 产品资料清单

如需查看或下载，请点击[查看详情]。

资料名称     资料说明                                      操作
实施指南     面向项目实施人员，涵盖部署规划、系统集成、配置要点及上线检查清单，助力快速落地   查看详情
用户操作手册   面向终端使用者，以步骤图解形式详解各功能模块的操作流程与常见问题处理        查看详情
产品介绍     浓缩产品定位、核心价值、典型场景与竞争优势                     查看详情
功能清单     结构化列出全部功能模块、子功能项及对应版本支持情况                 查看详情
安装部署手册   面向运维与系统工程师，提供软硬件环境要求、安装包说明、分步部署指令及验证方法    查看详情

编撰人：wdxue


快速跳转



 * 智能合同产品文档清单
   * 产品资料清单



分享链接分享链接

## 77. 智能合同管理_业务逻辑说明

> 原始路径：`/2794/2802.html`  
> 相对路径：`2794/2802.md`  
> JS Chunk：`app.7a5cbccd.js`

## 智能合同管理_业务逻辑说明

智能合同管理平台以“AI重塑合同应用场景，应用融合管理价值”为定位，为中/大型企业、集团型企业、央国企、实业集团、细分行业龙头等提供全方位、智能化、灵活高效的智能合同管理平台。 智能合同管理覆盖合同管理全生命周期的电子化、智能化应用，实现从签订前准备、合同起草、合同审批、合同签章、合同归档、合同履约等全流程管控。






## 子模块业务逻辑清单

业务模块   业务说明                                                                            业务逻辑
合同类别   按业务属性、管控要求自定义合同类别并进行管理，实现合同管理口径统一。                                              查看详情
我方单位   管理我方签约主体，包含主体基本信息、联系信息、银行账户以及印章信息等。                                             查看详情
相对方    集中管理合同相对方信息，包含基本信息、联系人、银行账户、签约记录等信息，具备将相对方加入黑名单、解除黑名单在内的相对方黑名单管理能力。             查看详情
规章制度   管理企业内部的规章制度，包含制度新建、修订、废止等。                                                      查看详情
合同模板   管理合同模板，供发起合同审批时快速调用，包含模板的新增、编辑、修订、发布、废止、授权、表单字段标注等能力。                           查看详情
合同预审   提前起草合同，由合同预审组成员协作预审，预审通过后文件可在发起合同审批时快速调用。                                       查看详情
合同审批   统一合同发起入口，根据不同的业务场景支持通过合同模板、预审文本、自拟三种方式发起合同审批。灵活设置各类审批流程，对不同组织、不同类别的合同审批单进行审批。   查看详情
合同缔约   对合同审批通过后生成的缔约任务进行管理。发起合同用印申请或者作废操作                                              查看详情
合同用印   对待用印任务发起实体签或电子签用印申请，通过后记录合同双方盖章文件。                                              查看详情
合同台账   全景、全量、全要素展示合同台账信息，包含基本信息、合同文件、履约纪律、审批记录、借阅记录等。                                  查看详情
合同归档   支持合同电子档案归档和实体档案归档，归档信息灵活配置，归档后可动态更新档案信息。                                        查看详情
合同变更   针对签约主体、合同标的、合同金额、合同条款等内容进行变更。                                                   查看详情
合同解除   选择履约中合同发起解除审批，解除类型包含终止、解除、撤销。                                                   查看详情
合同结项   对合同履约情况进行最终核查，确认合同约定的权利义务是否全部履行完毕。                                              查看详情
合同借阅   发起借阅申请查阅未经办合同，借阅后可归还合同。                                                         查看详情
合同履约   查看合同的履约事项，包含收款事项、付款事项、交付事项，并对履约事项的执行情况进行维护。                                     查看详情

编撰人：wdxue


快速跳转



 * 智能合同管理_业务逻辑说明
   * 子模块业务逻辑清单



分享链接分享链接
