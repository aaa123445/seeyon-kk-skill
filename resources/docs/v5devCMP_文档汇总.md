# Seeyon V5 Dev CMP 文档汇总

- 来源：https://open.seeyoncloud.com/v5devCMP/
- 提取文档数：73
- 说明：从 VuePress 静态站点 JS 中的原始 Markdown content 字段提取整理。

## 目录

1. [快速开始](#快速开始) — `/quickStart/`
2. [Hello World](#hello-world) — `/quickStart/helloworld.html`
3. [Nice Code](#nice-code) — `/quickStart/nicecode.html`
4. [CMP移动平台](#cmp移动平台) — `/93/`
5. [CMP移动端前端组件库](#cmp移动端前端组件库) — `/93/168.html`
6. [CMP API文档](#cmp-api文档) — `/93/550.html`
7. [移动端H5如何开发](#移动端h5如何开发) — `/93/551/552.html`
8. [移动端H5开发规范](#移动端h5开发规范) — `/93/551/553.html`
9. [CMP组件调用方式](#cmp组件调用方式) — `/93/551/554.html`
10. [H5应用模块对照](#h5应用模块对照) — `/93/551/555.html`
11. [S3编辑工具的使用](#s3编辑工具的使用) — `/93/551/556.html`
12. [CMP移动H5浏览器调试面板](#cmp移动h5浏览器调试面板) — `/93/551/557/558.html`
13. [CMP移动H5浏览器调试微协同](#cmp移动h5浏览器调试微协同) — `/93/551/557/559.html`
14. [CMP移动Android手机调试](#cmp移动android手机调试) — `/93/551/557/560.html`
15. [一、概述](#一概述) — `/93/551/557/561.html`
16. [CMP移动H5其他调试技巧](#cmp移动h5其他调试技巧) — `/93/551/557/562.html`
17. [M3原生应用开发](#m3原生应用开发) — `/93/563/`
18. [M3客开离线消息推送切换本地服务](#m3客开离线消息推送切换本地服务) — `/93/563/564.html`
19. [M3客户端唤起第三方平台](#m3客户端唤起第三方平台) — `/93/563/565.html`
20. [CMP移动离线消息支持说明](#cmp移动离线消息支持说明) — `/93/563/567.html`
21. [苹果开发相关-账号、证书、上架](#苹果开发相关-账号证书上架) — `/93/563/1219.html`
22. [iOS苹果APP开发入门](#ios苹果app开发入门) — `/93/563/1220.html`
23. [H5应用集成方案](#h5应用集成方案) — `/93/568.html`
24. [CMP移动端客开常见问题](#cmp移动端客开常见问题) — `/93/569.html`
25. [CMP小程序集成方案](#cmp小程序集成方案) — `/93/912.html`
26. [CMP移动平台概述](#cmp移动平台概述) — `/93/1118.html`
27. [概述](#概述) — `/1267/`
28. [移动平台](#移动平台) — `/1267/`
29. [常见客户问题](#常见客户问题) — `/1268/`
30. [M3常见问题](#m3常见问题) — `/1268/1316.html`
31. [微协同私有化部署常见问题](#微协同私有化部署常见问题) — `/1268/1317/1097.html`
32. [微协同客户问题自检和上报要求](#微协同客户问题自检和上报要求) — `/1268/1317/1106.html`
33. [企业微信集成微协同常见问题排查文档](#企业微信集成微协同常见问题排查文档) — `/1268/1317/1108.html`
34. [微协同常见问题排查](#微协同常见问题排查) — `/1268/1317/1109.html`
35. [同步机制和常见问题](#同步机制和常见问题) — `/1268/1317/1110.html`
36. [M3](#m3) — `/1269/`
37. [Android 开发技术要求](#android-开发技术要求) — `/1269/1275/1277.html`
38. [Android开发规范](#android开发规范) — `/1269/1275/1278.html`
39. [步骤 1: 安装Java Development Kit (JDK)](#步骤-1-安装java-development-kit-jdk) — `/1269/1275/1304.html`
40. [移动办公M3隐私保护协议](#移动办公m3隐私保护协议) — `/1269/1289/1307.html`
41. [应用权限说明](#应用权限说明) — `/1269/1289/1309.html`
42. [第三方SDK列表](#第三方sdk列表) — `/1269/1289/1310.html`
43. [APP加固](#app加固) — `/1269/1289/1311.html`
44. [网络安全的要求和解决方案](#网络安全的要求和解决方案) — `/1269/1289/1312.html`
45. [源码申请详细步骤](#源码申请详细步骤) — `/1269/1290/1291.html`
46. [软著申请的方法及所需资料证明和详细步骤](#软著申请的方法及所需资料证明和详细步骤) — `/1269/1290/1293.html`
47. [APP备案流程](#app备案流程) — `/1269/1290/1294.html`
48. [iOS APP发布上架详细流程和操作步骤](#ios-app发布上架详细流程和操作步骤) — `/1269/1290/1296/1821.html`
49. [M3云定制功能及注意事项](#m3云定制功能及注意事项) — `/1269/1305/`
50. [云打包：iOS证书制作](#云打包ios证书制作) — `/1269/1305/1943.html`
51. [云打包：安卓签名证书制作和公钥查看](#云打包安卓签名证书制作和公钥查看) — `/1269/1305/2549.html`
52. [M3 人脸识别服务第三方应用接入开发文档](#m3-人脸识别服务第三方应用接入开发文档) — `/1269/1315.html`
53. [移动分离部署服务 — 安装部署文档](#移动分离部署服务--安装部署文档) — `/1269/1826.html`
54. [微协同](#微协同) — `/1270/`
55. [微协同私有化部署手册-Windows版](#微协同私有化部署手册-windows版) — `/1270/1298/1331/1095.html`
56. [微协同私有化部署手册-Linux版](#微协同私有化部署手册-linux版) — `/1270/1298/1331/1096.html`
57. [微协同私有化部署-同步配置](#微协同私有化部署-同步配置) — `/1270/1298/1331/1098.html`
58. [（项目化）企业微信直连](#项目化企业微信直连) — `/1270/1298/1331/1959.html`
59. [微信服务号集成微协同](#微信服务号集成微协同) — `/1270/1298/1332/1103.html`
60. [微协同-私有化安装包升级](#微协同-私有化安装包升级) — `/1270/1298/1343.html`
61. [信创环境私有化集成部署手册](#信创环境私有化集成部署手册) — `/1270/1298/1350.html`
62. [致远微协同-企业微信集成配置](#致远微协同-企业微信集成配置) — `/1270/1325/1326/1094.html`
63. [企业微信接口许可购买及账号激活操作说明](#企业微信接口许可购买及账号激活操作说明) — `/1270/1325/1326/1266.html`
64. [致远微协同-钉钉集成配置](#致远微协同-钉钉集成配置) — `/1270/1325/1327/1099.html`
65. [致远微协同 - 飞书集成配置](#致远微协同---飞书集成配置) — `/1270/1325/1328/1100.html`
66. [致远微协同 - 飞书审批集成配置](#致远微协同---飞书审批集成配置) — `/1270/1325/1328/1101.html`
67. [致远微协同 - WELINK集成配置](#致远微协同---welink集成配置) — `/1270/1325/1329/1104.html`
68. [致远微协同-微信小程序集成配置](#致远微协同-微信小程序集成配置) — `/1270/1325/1330/1102.html`
69. [微协同问题上报建议](#微协同问题上报建议) — `/1270/1340.html`
70. [微协同常见问题FAQ清单](#微协同常见问题faq清单) — `/1270/1353.html`
71. [移动H5应用开发](#移动h5应用开发) — `/1271/`
72. [技术要求](#技术要求) — `/1271/1273.html`
73. [开发文档](#开发文档) — `/1271/1274.html`

---

## 1. 快速开始

> 原始路径：`/quickStart/`  
> 相对路径：`quickStart/README.md`  
> JS Chunk：`app.844f671c.js`

## 快速开始

欢迎来到快速开始页面

## 2. Hello World

> 原始路径：`/quickStart/helloworld.html`  
> 相对路径：`quickStart/helloworld.md`  
> JS Chunk：`app.844f671c.js`

## Hello World

北京欢迎您！

## 3. Nice Code

> 原始路径：`/quickStart/nicecode.html`  
> 相对路径：`quickStart/nicecode.md`  
> JS Chunk：`app.844f671c.js`

## Nice Code

这是一段优秀的代码！

## 4. CMP移动平台

> 原始路径：`/93/`  
> 相对路径：`93/README.md`  
> JS Chunk：`app.844f671c.js`

子菜单名称         URL
概述            概述
小程序集成方案       小程序集成方案
移动端H5应用基础开发   移动端H5应用基础开发
M3原生应用开发      M3原生应用开发
H5应用集成        H5应用集成
CMP组件库        CMP组件库
CMP API文档     CMP API文档
常见问题          常见问题

分享链接分享链接

## 5. CMP移动端前端组件库

> 原始路径：`/93/168.html`  
> 相对路径：`93/168.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动端前端组件库

CMP前端组件资源和组件库列表：

组件库        内容        链接
CMP前端组件库   含统一的图标库   链接
UI视觉组件控件   控件        链接
语音组件1.0    语音组件      链接
语音组件2.0    语音组件      链接

编撰人：admin、het


快速跳转



 * CMP移动端前端组件库



分享链接分享链接

## 6. CMP API文档

> 原始路径：`/93/550.html`  
> 相对路径：`93/550.md`  
> JS Chunk：`app.844f671c.js`

## CMP API文档

CMP API文档列表：

组件库                 内容      链接
CMP V7.1SP1 API文档   API文档   链接
CMP V8.0 API文档      API文档   链接

编撰人：admin、het


快速跳转



 * CMP API文档



分享链接分享链接

## 7. 移动端H5如何开发

> 原始路径：`/93/551/552.html`  
> 相对路径：`93/551/552.md`  
> JS Chunk：`app.844f671c.js`

## 移动端H5如何开发


## 一、开发流程图




## 二、开发目录构成




## 三、manifest配置说明




## 四、热部署/检查zip包


## 1.热部署


## 2.检查zip包


## 五、初始开发目录包下载

访问CMP移动平台资源中心 https://open.seeyoncloud.com/cmpdev/#/sources 下载 [mobileWork初始包]

编撰人：admin、het、puwb、lichaoj




快速跳转



 * 移动端H5如何开发
   * 一、开发流程图
   * 二、开发目录构成
   * 三、manifest配置说明
   * 四、热部署/检查zip包
     * 1.热部署
     * 2.检查zip包
   * 五、初始开发目录包下载



分享链接分享链接

## 8. 移动端H5开发规范

> 原始路径：`/93/551/553.html`  
> 相对路径：`93/551/553.md`  
> JS Chunk：`app.844f671c.js`

## 移动端H5开发规范

> 开发人员需遵照开发规范执行


## 1、基本原则

 * 由于jquery在移动端的开发存在性能问题，页面不允许导入jquery库，如果已经习惯了jquery开发的，可以导入zepto库进行代替；
 * 样式需进行兼容处理；
 * UE交互保持一致性、UI风格保持一致性、代码风格保持一致性；
 * 谨慎引入第三方前端库，引入时需要充分考虑性能、稳定性、可维护性和技能要求。


## 2、页面开发规范

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

http://cmp/v1.0.0/js/cordova/__CMPSHELL_PLATFORM__/cordova.js
http://cmp/v1.0.0/js/cordova/cordova-plugins.js


 * 必须导入cmp平台的js，导入文件规则：

//======== 代码运行在M3  app上
 <link href="http://cmp/v/css/cmp.css" rel="stylesheet" type="text/css" />
 <script  src="http://cmp/v/js/cmp-i18n.js"></script>
 <script  src="http://cmp/v/js/cmp.js"></script>
 //=======代码运行在微信、钉钉等或者第三方app以url的方式接入oa的H5页面时
 <link href="/seeyon/m3/cmp/css/cmp.css" rel="stylesheet" type="text/css" />
 <script  src="/seeyon/m3/cmp/js/cmp-i18n.js"></script>
 <script  src="/seeyon/m3/cmp/js/cmp.js"></script>


 * 页面采用自适应屏幕宽度设置：

<meta name="viewport" content="width=device-width, initial-scale=1,maximum-scale=1,user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">



## 3、代码结构

 * html文件放到html文件夹；
 * css文件放到css文件夹；
 * js文件放到js文件夹；
 * 图片文件放到img文件夹；
 * 国际化资源文件放到i18n文件夹。


## 4、命名

 * camel命名风格


## 二、项目结构规范

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



## 三、cmp.ready里面应该做什么

首先要知道在运行cmp.ready时内部做了什么东西：

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


可以看见里面做了加载设备类名、加载第三方SDK、加载主题、等一系列操作，所以只能在cmp.ready里面才能做很多操作，比如注册返回事件cmp.backbutton、比如ready里面获取body元素上的类名等，其实归根结底就是类似jquery的ready，在完成一系列加载之后，才能在ready里面使用api或者一些方法等等。


## 四、js、css在cmp平台下导入的顺序规范以及微协同和M3上导入的差异性

> M3平台文件路径

CSS导入参考：

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


JS导入参考:

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


> 微协同平台路径

CSS导入参考：

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


JS导入参考:

<!-- 基础模块 -->
<script src="/seeyon/m3/cmp/js/cmp-i18n.js"></script>
<script src="/seeyon/m3/cmp/js/cmp.js"></script>
<!-- cmp组件(按需引入) -->
<script src="/seeyon/m3/cmp/js/cmp-asyncLoad.js"></script>
<script src="/seeyon/m3/cmp/js/cmp-webviewListener.js"></script>
<!-- 自己业务的模块入口文件 -->
<script async src="/seeyon/m3/apps/v5/bulletin/js/bulletinIndex.js"></script>
</body><!--！！！js的导入必须到body页签的结尾处！！！-->


注：导入的顺序需要严格按照规范执行，不然会有报错和找不到方法或者变量的情况。


## 五、国际化资源使用properties开发以及在页面中导入的规范


## 1、文件命名:应用模块名+下横线+通用语言标识




## 2、国际化资源，必须以fI18nData JS对象进行扩展

<script>
if(typeof fI18nData == "undefined"){
     fI18nData  = {};
}
fI18nData["mobileWork.label.back"] = "返回";
fI18nData["mobileWork.label.submit"] = "提交";
</script>



## 3、国际化资源调用使用规则

<html>
    <div><i18n key="mobileWork.label.back"></i18n></div> <!-- 使用国际化标签，key为国际化字符串 -->
</html>
<script>
    var backStr = cmp.i18n("mobileWork.label.back"); //返回国际化字符串"返回";
</script>



## 4、国际化资源版本差异

版本                         国际化代码开发规范
7.1以下的版本（不包含7.1）           开发源码按照第1点的规范直接用js文件写国际化资源
7.1及以上的版本（包含7.1）           1、源码使用properties文件进行开发
2、需使用S3工具编辑后生成如第1点中的js文件   


## 六、ajax调用规范

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



## 七、应用包之间穿透API设计规范


## 1、文件命名：应用模块名+下划线+api.s3js（文件命名必须和manifest.json中的entry下的jsapi字段保持一致）




## 2、穿透函数命名规范（openApp对应manifest.json的entry里的openAppMethod的值）




## 3、穿透函数开发例子(已在初始化应用包里自带)

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



## 七、UE样式规范

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


编撰人：admin、het


快速跳转



 * 移动端H5开发规范
   * 1、基本原则
   * 2、页面开发规范
   * 3、代码结构
   * 4、命名
   * 二、项目结构规范
   * 三、cmp.ready里面应该做什么
   * 四、js、css在cmp平台下导入的顺序规范以及微协同和M3上导入的差异性
   * 五、国际化资源使用properties开发以及在页面中导入的规范
     * 1、文件命名:应用模块名+下横线+通用语言标识
     * 2、国际化资源，必须以fI18nData JS对象进行扩展
     * 3、国际化资源调用使用规则
     * 4、国际化资源版本差异
   * 六、ajax调用规范
   * 七、应用包之间穿透API设计规范
     * 1、文件命名：应用模块名+下划线+api.s3js（文件命名必须和manifest.json中的entry下的jsapi字段保持一致）
     * 2、穿透函数命名规范（openApp对应manifest.json的entry里的openAppMethod的值）
     * 3、穿透函数开发例子(已在初始化应用包里自带)
   * 七、UE样式规范



分享链接分享链接

## 9. CMP组件调用方式

> 原始路径：`/93/551/554.html`  
> 相对路径：`93/551/554.md`  
> JS Chunk：`app.844f671c.js`

## CMP组件调用方式


## 一、API网站说明

 * V6.X版本的API文档地址：http://open.seeyon.com/seeyon/cmp/doc/modules/Audio.html 和 http://open.seeyon.com/seeyon/cmp2.0/doc/modules/Audio.html
 * V7.X版本的API文档地址：http://open.seeyon.com/seeyon/cmp2.0/v7.1sp1-doc/index.html
 * V8.X版本的API文档地址：http://open.seeyon.com/seeyon/cmp2.0/v8.0-doc/index.html
 * 将要持续维护的永久文档地址：http://open.seeyon.com/seeyon/cmp2.0/cmpdemo/index.html


## 二、API如何查询




## 三、常用API的使用

1、附件查看

cmp.att.read({
    path:cmp.seeyonbasepath + "/rest/attachment/file/232323232",//文件的服务器地址
    filename:"文件名.doc",//附件名称
    edit:false,  //是否可以进行修改编辑
    //officeTransformEnable为enable的时候 v字段为必填字段
    v: 'CTP附件对象中的防盗链v值',
    extData:{
         fileId: '232323232',
         lastModified: '123',
         origin: 'xxx'
    },
    success:function(ret){
        console.log(ret)
    },
    error:function(error){
        //do something
    }
});


2、调用相机

cmp.camera.getPictures('#inputBtn-selector1', {
    success: function(ret) {
        // var ret = {
        //     files: [{
        //         fileSize: '49609',
        //         filepath: 'xxxxx.png',
        //         type: 'jpg',
        //         index: 0
        //     }],
        //     success: true
        // }
        console.log('拍照获取图片成功', ret);
    },

    error: function(e) {
        console.log('拍照获取图片异常', e);
    }
});


3、原生导航栏的扩展

cmp.header.customCMPHeader({
    type: 'tabStyle',
    leftConfig: [{
        backgroundColor: '#ff0000',
        activeBackgroundColor: '#00ff00',
        text: '1',
        textColor: '#000000',
        activeText: '11',
        activeTextColor: '#ff0000'
    },{
        backgroundColor: '#ff0000',
        activeBackgroundColor: '#00ff00',
        text: '2',
        textColor: '#000000',
        activeText: '22',
        activeTextColor: '#ff0000'
    }],
    leftBtnCallback: function(index) {console.log('---left---' + index)},
    rightConfig: [{
        type: 'image',
        imageUrl: 'http://commons.m3.cmp/v/imgs/default.png'
    },{
        type: 'image',
        imageUrl: 'http://commons.m3.cmp/v/imgs/default.png'
    }],
    rightBtnCallback: function(index) {console.log('---right---' + index)},
    initActiveLeftIndex: 1,
    isInitActionCb: false
});


编撰人：admin、het


快速跳转



 * CMP组件调用方式
   * 一、API网站说明
   * 二、API如何查询
   * 三、常用API的使用



分享链接分享链接

## 10. H5应用模块对照

> 原始路径：`/93/551/555.html`  
> 相对路径：`93/551/555.md`  
> JS Chunk：`app.844f671c.js`

## H5应用模块对照


## 一、M3/微协同模块对照表

1、V5应用对照表

APPID   包名       应用名称     M3路径                        微协同路径                                微协同应用入口路径
1       1.zip    协同       \seeyon\m3files\v5\1.zip    \seeyon\m3\apps\v5\collaboration     {ip}/seeyon/m3/apps/v5/collaboration/html/colAffairs.html
2       2.zip    表单       \seeyon\m3files\v5\2.zip    \seeyon\m3\apps\v5\form              无
3       3.zip    文档中心     \seeyon\m3files\v5\3.zip    \seeyon\m3\apps\v5\doc               {ip}/seeyon/m3/apps/v5/doc/html/docIndex.html
4       4.zip    公文       \seeyon\m3files\v5\4.zip    \seeyon\m3\apps\v5\edoc              {ip}/seeyon/m3/apps/v5/edoc/html/edocList.html
6       6.zip    会议       \seeyon\m3files\v5\6.zip    \seeyon\m3\apps\v5\meeting           {ip}/seeyon/m3/apps/v5/meeting/html/meeting_list_pending.html
7       7.zip    公告       \seeyon\m3files\v5\7.zip    \seeyon\m3\apps\v5\bulletin          {ip}/seeyon/m3/apps/v5/bulletin/html/bulIndex.html
8       8.zip    新闻       \seeyon\m3files\v5\8.zip    \seeyon\m3\apps\v5\news              {ip}/seeyon/m3/apps/v5/news/html/newsIndex.html
9       9.zip    讨论       \seeyon\m3files\v5\9.zip    \seeyon\m3\apps\v5\bbs               {ip}/seeyon/m3/apps/v5/bbs/html/bbsIndex.html
10      10.zip   调查       \seeyon\m3files\v5\10.zip   \seeyon\m3\apps\v5\inquiry           {ip}/seeyon/m3/apps/v5/inquiry/html/inquiryIndex.html
11      11.zip   时间安排     \seeyon\m3files\v5\11.zip   \seeyon\m3\apps\v5\calendar          {ip}/seeyon/m3/apps/v5/calendar/html/timeArrange.html
17      17.zip   工资条      \seeyon\m3files\v5\17.zip   \seeyon\m3\apps\v5\hr                {ip}/seeyon/m3/apps/v5/hr/html/hrSalary.html
26      26.zip   综合办公     \seeyon\m3files\v5\26.zip   \seeyon\m3\apps\v5\office            无
30      30.zip   工作任务     \seeyon\m3files\v5\30.zip   \seeyon\m3\apps\v5\taskmanage        {ip}/seeyon/m3/apps/v5/taskmanager/html/task_index.html
36      36.zip   签到       \seeyon\m3files\v5\36.zip   \seeyon\m3\apps\v5\attendance        {ip}/seeyon/m3/apps/v5/attendance/html/attendanceIndex.html
40      40.zip   享空间      \seeyon\m3files\v5\40.zip   \seeyon\m3\apps\v5\show              {ip}/seeyon/m3/apps/v5/show/html/showIndex.html
42      42.zip   行为绩效     \seeyon\m3files\v5\42.zip   \seeyon\m3\apps\v5\footprint         {ip}/seeyon/m3/apps/v5/footprint/html/footPrintIndex.html
43      43.zip   业务生成器    \seeyon\m3files\v5\43.zip   \seeyon\m3\apps\v5\biz               {ip}/seeyon/m3/apps/v5/biz/html/default.html
44      44.zip   v5应用通用   \seeyon\m3files\v5\44.zip   \seeyon\m3\apps\v5\commons           无
45      45.zip   工作流      \seeyon\m3files\v5\45.zip   \seeyon\m3\apps\v5\workflow          无
47      47.zip   无流程表单    \seeyon\m3files\v5\47.zip   \seeyon\m3\apps\v5\unflowform        无
48      48.zip   查询统计     \seeyon\m3files\v5\48.zip   \seeyon\m3\apps\v5\formqueryreport   {ip}/seeyon/m3/apps/v5/formqueryreport/html/index.html
51      51.zip   Dee      \seeyon\m3files\v5\51.zip   \seeyon\m3\apps\v5\dee               无
60      60.zip   我的收藏     \seeyon\m3files\v5\60.zip   \seeyon\m3\apps\v5\mycollection      {ip}/seeyon/m3/apps/v5/mycollection/html/mycollectionIndex.html
61      61.zip   致信       \seeyon\m3files\v5\61.zip   \seeyon\m3\apps\v5\uc                {ip}/seeyon/m3/apps/v5/uc/html/ucIndex.html
62      62.zip   通讯录      \seeyon\m3files\v5\62.zip   \seeyon\m3\apps\v5\addressbook       {ip}/seeyon/m3/apps/v5/addressbook/html/addressbookIndex.html
63      63.zip   报表分析     \seeyon\m3files\v5\63.zip   \seeyon\m3\apps\v5\seeyonreport      {ip}/seeyon/m3/apps/v5/seeyonreport/html/index.html
65      65.zip   门户       \seeyon\m3files\v5\65.zip   \seeyon\m3\apps\v5\portal            {ip}/seeyon/m3/apps/v5/portal/html/portalIndex.html

2、M3应用对照表

APPID   包名                应用名称        M3路径                                 微协同路径
49      cmp.zip           cmp平台       \seeyon\m3files\m3\cmp.zip           \seeyon\m3\cmp
52      application.zip   应用中心/门户应用   \seeyon\m3files\m3\application.zip   \seeyon\m3\application
53      commons.zip       commons     \seeyon\m3files\m3\commons.zip       \seeyon\m3\commons
55      message.zip       应用消息        \seeyon\m3files\m3\message.zip       无微协同版本
56      my.zip            个人信息        \seeyon\m3files\m3\my.zip            \seeyon\m3\my(只有部分页面支持微协同)
57      search.zip        通讯录         \seeyon\m3files\m3\search.zip        \seeyon\m3\search
58      todo.zip          待办          \seeyon\m3files\m3\todo.zip          \seeyon\m3\todo


## 二、M3各版本新增应用

1、V7.0新增【全文检索】【报表中心】

APPID   包名               应用名称   存放路径                                微协同应用入口路径
59      fullsearch.zip   全文检索   \seeyon\m3files\m3\fullsearch.zip   \seeyon\m3\v5\fullsearch\layout\all-search.html
70      vreport.zip      报表中心   \seeyon\m3files\m3\vreport.zip      \seeyon\m3\v5\vreport\html\index.html

2、V7.0SP3新增【小致】

APPID   包名          应用名称       M3路径                           微协同应用入口路径
79      xiaoz.zip   小致(智能问答)   \seeyon\m3files\m3\xiaoz.zip   无

3、 V7.1SP1新增【一键体检】

APPID   包名            应用名称   M3路径                             微协同应用入口路径
90      inspect.zip   一键体检   \seeyon\m3files\m3\inspect.zip   无

4、 V8.0新增【文件管理】【领导行程】

APPID   包名                 应用名称   M3路径                                  微协同路径
93      filemanage.zip     文件管理   \seeyon\m3files\m3\filemanage.zip     无
94      leaderagenda.zip   领导行程   \seeyon\m3files\m3\leaderagenda.zip   \seeyon\m3\v5\leaderagenda\html\leaderagendaIndex.html

编撰人：admin、het


快速跳转



 * H5应用模块对照
   * 一、M3/微协同模块对照表
   * 二、M3各版本新增应用



分享链接分享链接

## 11. S3编辑工具的使用

> 原始路径：`/93/551/556.html`  
> 相对路径：`93/551/556.md`  
> JS Chunk：`app.844f671c.js`

## S3编辑工具的使用


## 一、工具的作用

移动端H5的代码原则上是一套源代码，通过S3工具编辑后，能生成多端运行的代码。本质就是通过此工具将html、s3js、css三种后缀文件中的类似 ${data:dependencies.cmp} 这种格式的静态资源路径进行一个替换，如：



PS：如果不通过此工具构建，相关的html、js、css是无法用程序运行的


## 二、支持的构建标签

序号   标签                                          说明
1    ${data:dependencies.cmp}                    常见的标签，对应单个应用模块的路径
2    <s3:import type="css"></s3:import>          对于一些有共性的页面元素，可以抽取成组件模板，编辑的时候会将此标签对应的模型进行替换，相当于PC端JSP页面的include
3    <s3:data name='CollDatas.headerScript' />   同上，只是共性的模型更聚焦，比如此处就是协同模块的头部script标签的统一导入，因为在协同模块的每一个页面都会有这样的模板元素
4    ${data:buildversion}                        对js、css等静态资源添加后缀，用于版本控制，更重要的是清除浏览器静态资源缓存


## 三、工具的获取

1、下载：点击此链接下载工具[[S3工具下载链接|attach:S3Script.zip]] 2、安装：将文件解压到任何目录都可以使用 PS：有点不太友好的是此工具不支持苹果操作系统


## 四、工具的使用


## 1、认识工具的组成结构

【java】：该工具由java语言开发，相关的功能使用由jar在此文件夹中，开发者无需关注此文件夹 【publishcmd】：应用构建脚本集合，所有的H5应用微协同版本和M3应用zip包版本的脚本集合，根据配置信息启动工具构建不同的静态文件版本 【publishoutput】：构建完成后的可运行文件的输出目录,此目录构建出来的文件是可以直接运行的 【workspace】：项目源码的开发路径，此文件夹的路径，开发者最好按照此文件夹结构将开发项目源码导入进去，这样减少其他的学习成本 【文档】：此工具的一些说明性文档，开发者可以不用过多关注 【batchbuild.cmd】：批量构建脚本，通过配置可以将多个模块进行构建，可以同时构建出zip包和微协同模式的运行代码，一般用于某个开发者同时涉及多个应用模块的开发，开发者关注此文件


## 2、batchbuild 批量构建脚本




## 3、publishcmd 文件夹

此文件夹已经将62个标准应用的微信同模式和M3应用包模式的脚本进行了预置，后续如果开发者有新增模块，只需在对应的应用模块组里添加cmd文件即可，再在batchbuild中添加模块名称进行构建即可


## 五、规范

为减少工具学习成本，开发者最好按照文件夹结构来做工程源码文件夹结构和输出路径文件夹结构配置，这样只需按照规范来，就可以简简单单地完成源码开发、构建输出、代码调试查看的流程

编撰人：admin、het




快速跳转



 * S3编辑工具的使用
   * 一、工具的作用
   * 二、支持的构建标签
   * 三、工具的获取
   * 四、工具的使用
     * 1、认识工具的组成结构
     * 2、batchbuild 批量构建脚本
     * 3、publishcmd 文件夹
   * 五、规范



分享链接分享链接

## 12. CMP移动H5浏览器调试面板

> 原始路径：`/93/551/557/558.html`  
> 相对路径：`93/551/557/558.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动H5浏览器调试面板

说明：移动端的开发并没有想象中那么困难，只要用好浏览器提供的调试工具面板一样可以轻轻松松完成H5页面的调试； PS：首先你至少会F5进入调试面板，推荐使用edge浏览器和chrome浏览器


## 一、【Element】/【元素】面板，调试样式的利器




## 1、作用

用于调试页面样式，可以直接在调试面板上增删改dom元素，通过其他额外的工具进行配合使用达到能修改样式，改变dom，输入预想值，达到调试样式的目的


## 2、相辅相成的主要功能点

## 1) 在某个dom上鼠标右键弹出选项卡

里面有丰富的编辑dom的功能，除了右键弹出，还可以鼠标双击元素，直接编辑dom元素，比如将div标签修改成span标签的动作



几个常用功能 【添加属性】：给dom元素添加新的属性 【编辑为HTML】：可以直接编辑html字符串 【删除元素】：删除一些dom元素 【中断于】：当调试js代码可以设置页面元素的属性或者样式改变能断点js的代码

## 2）在右边【样式】选项卡中实时编辑样式




## 二、【source】/【源】所有页面的js、css、html、font代码的查看面板，代码逻辑调试全靠它


## 1、作用

主要用于JS代码的调试，当然也可以调试html，通过几大操作方式能快速定位程序问题点



该面板分为左、中、右三个部分，左边是用于展示页面加载的资源列表，中间是代码调试区域，右边是对代码调试的监控区域 ！！！其中代码调试区域在调试的过程中可以对代码进行动态修改，修改完成后，直接Ctrl+S保存，代码立即生效 以下几个重要的常用功能进行说明 **【代码优化显示按钮】：**当我们遇到代码是压缩混淆后的，点击此按钮可以将代码展示成格式化形式，代码会呈现没个行数，便于开发者调试，而不是看到一堆压缩的代码无法调试 **【左侧行数栏】：**点击后可以将断点打上，程序跑到这个位置程序中断 **【调试步骤按钮组】：**就是单步、步进、步推的调试方式的按钮组合，相关的快捷按钮，将鼠标悬浮在上面即可被告知 **【断点记录表】：**记录你在代码调试区域所有打断点的地方，便于开发者能快速查询到断点位置，当刷新页面后，双击断点记录表中的某一条即可直达代码所在位置 **【程序调用堆栈记录表】：**记录某个线程下程序的调用路径，双击某个记录可以快速定位到程序代码处，并且能打印出该代码处的变量值，通常调试程序调用链路一层一层往上找问题时需要用到


## 2、高阶用法

1）通过【Open file】弹出的搜索框，能快速查询出相关文件



2）通过【覆盖】选项卡可以将调试区域中修改后的代码进行修改保存，页面刷新或者下次进来的时候不用重新去修改代码，浏览器直接加载你之前修改过的代码，相当于是前面在调试区域修改代码后还能进行保存




## 三、【network】/【网络】查看页面网络资源请求


## 1、概览

可以抓住页面的网络请求，知道网页有什么请求，哪些资源请求时间长，哪些资源来自于哪里，甚至可以通过对网络请求的抓包能调试代码，知道页面的所有逻辑，所以这个面板也是非常重要的面板



该面板分为上下两个区域，上面主要是对网络资源的额外操作和网络状态的模拟 【筛选器】：对下面资源列表的过滤，可以筛选出开发者想要的资源 【保留日志】：即使页面刷新或者跳转页面，前面的请求记录会继续保留，方便开发者查看过往的网络请求记录 【禁用缓存】：为避免页面有js、css缓存问题而导致修改了js、css不生效的情况，一般调试的时候最好把此项勾选 【无限制】：主要用于模拟网络状态，可以设置无限制、3G等 【网络资源筛选】：对资源类型进行过滤，如Fetch/XHR就是页面Ajax请求类型 【资源列表】：所有资源的列表，可以通过筛选器进行文件名过滤，点击某个资源可以看见此资源的详细信息，包括请求头、响应头和返回值


## 2、点击资源列表查看资源详细信息！！非常重要！！



【标头】：能查看请求完成后的信息，包括响应状态码，响应头信息，请求头信息，请求参数等 【预览】：用于查看响应值，如果是json数据，会自动转换成json对象 【响应】：未格式化的响应数据查看 【发起程序】：可以查看此请求的程序调用堆栈链路，方便调试代码定位到代码 【计时】：可以查看请求从发起到数据返回用了多少时间


## 四、【application】/【应用程序】面板查看网页缓存

帮助你了解网页上到底还存了什么肉眼看不见得东西


## 1、概述



【本地存储】：就是localStorage储存，里面储存的数据通常情况下是永久的，但是某些手机APP（比如微信）会自动清除，导致其不能永久存储 【会话存储】：即sessionStorage，用于临时存储数据，一般只在一个会话中生效，一旦浏览器关闭，则里面存储的值会自动清除 【IndexDB】：如同数据库，可以永久储存数据 【Cookie】：存储Cookie信息，浏览器在发送请求的时候会自动带上，我们可以通过此参数知道请求人的身份


## 五、【search】/【搜索】面版

相当于你的页面全文检索


## 1、概览



在输入框中输入需要搜索的内容，可以快速的搜索出和搜索关键字相关的所有资源文件，包括JS、CSS、HTML等资源文件


## 六、【console】/【控制台】面板

页面的出现所有日志信息和对变量进行修改的都可以在这里操作


## 1、概栏



编撰人：admin、het




快速跳转



 * CMP移动H5浏览器调试面板
   * 一、【Element】/【元素】面板，调试样式的利器
     * 1、作用
     * 2、相辅相成的主要功能点
       * 1) 在某个dom上鼠标右键弹出选项卡
       * 2）在右边【样式】选项卡中实时编辑样式
   * 二、【source】/【源】所有页面的js、css、html、font代码的查看面板，代码逻辑调试全靠它
     * 1、作用
     * 2、高阶用法
   * 三、【network】/【网络】查看页面网络资源请求
     * 1、概览
     * 2、点击资源列表查看资源详细信息！！非常重要！！
   * 四、【application】/【应用程序】面板查看网页缓存
     * 1、概述
   * 五、【search】/【搜索】面版
     * 1、概览
   * 六、【console】/【控制台】面板
     * 1、概栏



分享链接分享链接

## 13. CMP移动H5浏览器调试微协同

> 原始路径：`/93/551/557/559.html`  
> 相对路径：`93/551/557/559.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动H5浏览器调试微协同


## 一、概述

为了能快速进行代码开发而不受手机设备条件限制，我们可以通过浏览器调试微协同的模式对H5页面进行快速调试，通过此方式调试基本能达到和手机端效果的90%，所以建议在应用开发过程中，非必要使用手机调试的情况下尽量使用浏览器调试微协同的模式，简单、快捷、高效


## 二、调试要求

1、熟悉每个应用模块的入口页面，可以参考第前面[[0204|doc:technology.categoryOfTechnology.t_m3.移动端基础开发培训演示.0204 H5应用模块对照.WebHome]]章节微协同的入口页面地址 2、熟悉上一章节对浏览器调试面板作用


## 三、调试流程


## 1、使用edge、chrome浏览器登录一个PC的账号




## 2、在改浏览器新开一个页签，并输入H5应用模块入口页面地址




## 3、通过检测此页面，开启页面调试模式，当修改代码后，刷新页面即可

编撰人：admin、het


快速跳转



 * CMP移动H5浏览器调试微协同
   * 一、概述
   * 二、调试要求
   * 三、调试流程
     * 1、使用edge、chrome浏览器登录一个PC的账号
     * 2、在改浏览器新开一个页签，并输入H5应用模块入口页面地址
     * 3、通过检测此页面，开启页面调试模式，当修改代码后，刷新页面即可



分享链接分享链接

## 14. CMP移动Android手机调试

> 原始路径：`/93/551/557/560.html`  
> 相对路径：`93/551/557/560.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动Android手机调试


## 一、概述

Android手机的调试是非常重要的一个调试手段，通过真实手机的调试能解决APP上特有的功能调试，所以移动的开发，Android手机的调试也是必备技能之一；


## 二、调试场景

1、需要调试APP原生功能和H5进行交互的情况，看看原生功能给H5页面返回了什么数据，常见的原生功能包括相册选图片、拍照、定位、扫一扫等； 2、用户PC端是内网但是移动端是外网的情况，开发无法通过微协同模式来调试，只有通过手机能访问外网的特性来调试用户环境； 3、有些特殊问题微协同模式不复现，手机端复现的情况，这种也需要直接使用手机来调试；


## 三、工具准备

1、一台Android手机+能连电脑的数据线； 2、edge浏览器； 3、M3 Android客户端调试版本；


## 四、调试流程




## 1、将你的Android手机开启成开发者模式

## 1）华为手机（Android和鸿蒙系统一样）

进入【设置】---【关于手机】----连续数次点击【版本号】选项，直至提示你“你正处在开发者模式”（如果你的手机设置了密码，会提示你先输入密码） 返回到【设置】主页面-----进入到【系统和更新】----【开发者选项】----找到【USB调试】将此开关开启，这样就让你的手机处于开发者模式了

PS：如果你开启USB调试开关，但是退出【开发人员选项】后再进入，USB调试开关自动关闭，此时你需要将【“仅充电”模式下允许ADB调试】的开关打开即可。



## 2）小米手机

首先点击进入小米手机的“设置”程序。



然后点击进入“我的设备”设置选项



再点击进入“全部参数”页面



这时连续点击ＭＩＵＩ版本号7次。



直到手机屏幕提示已经处于开发者模式即可停止点击。



当手机处于开发者模式后，就可以进入开发者设置选项。接下来点击进入“更多设置”选项



接着点击进入“开发者选项”。



最后就可以根据实际需要，在“开发者选项”设置页面来进一步对手机设置。




## 2、申请M3 Android客户端调试版本

## 1）发《代码申请表单》流程，向M3移动团队申请调试版本APP进行安装




## 3、手机连电脑进行调试

## 1）通过数据线将手机连接到电脑

此过程略

## 2）使用edge浏览器检测手机H5页面

在浏览器地址栏上输入 edge://inspect 后回车



编撰人：admin、het


快速跳转



 * CMP移动Android手机调试
   * 一、概述
   * 二、调试场景
   * 三、工具准备
   * 四、调试流程
     * 1、将你的Android手机开启成开发者模式
       * 1）华为手机（Android和鸿蒙系统一样）
       * 2）小米手机
     * 2、申请M3 Android客户端调试版本
       * 1）发《代码申请表单》流程，向M3移动团队申请调试版本APP进行安装
     * 3、手机连电脑进行调试
       * 1）通过数据线将手机连接到电脑
       * 2）使用edge浏览器检测手机H5页面



分享链接分享链接

## 15. 一、概述

> 原始路径：`/93/551/557/561.html`  
> 相对路径：`93/551/557/561.md`  
> JS Chunk：`app.844f671c.js`

## 一、概述

iOS的调试H5页面，存在一定的技术门槛，需要保证充分的准备工具才能调试


## 二、准备工具

1、Mac电脑本 2、在Mac上安装Xcode12及以上版本 3、Safari浏览器 4、M3 iOS客户端源码 5、iOS开发者账号 6、数据线


## 三、视频教程

编撰人：admin


快速跳转



 * 一、概述
 * 二、准备工具
 * 三、视频教程



分享链接分享链接

## 16. CMP移动H5其他调试技巧

> 原始路径：`/93/551/557/562.html`  
> 相对路径：`93/551/557/562.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动H5其他调试技巧


## 一、Fiddle调试


## 1、作用

通过此工具可以进行网络数据包抓取、代码替换、网络断点等常用操作，能通过网络层面协助分析问题


## 2、适合场景

1）对请求数据需要进行分析的场景 2）使用微协同模式PC端调试时，将修改后的代码通过本地替换，快速验证用户生成环境效果而不影响用户生产环境使用 3）手机抓网络请求数据包分析数据流转的场景


## 3、使用步骤

## 1）电脑开启fiddler软件，并设置监听端口号

【Tools】----【Fiddler Options...】----【HTTPS】设置https相关设置---【Connections】设置端口和远程网络请求抓取

## 【Tools】开启设置



## 【HTTPS】设置https类型的请求



## 设置https证书信任，这样就可以抓https的请求包了



## 设置代理的监听端口号和勾选远程数据抓取开启



## 2）使用fiddle替换线上代码



## 3）手机设置Fiddle代理



## 4）视频教程


## 二、微信客户端调试H5代码


## 1、通过微信聊天窗口

http://debugx5.qq.com，开启微信客户端对H5页面的调试




## 2、视频教程


## 三、通过后台日志排查前端错误


## 1、概述

从8.0SP2LTS版本和8.1版本开始，M3移动开发增加了前端错误日志推送到后台ctp.log日志中进行记录，便于当客户的手机端出现前端问题而没有明显错误信息提示到前端，或者用户报错的时间无法得知时，开发者可以通过后台日志记录快速定位问题原因


## 2、原理

CMP平台对页面的错误事件做了全局监听（及使用window.onerror），当错误信息被捕获后，会发生一个错误日志信息到后台，后台将错误信息记录到ctp.log日志文件中


## 3、日志获取路径

A8安装目录/ApacheJetspeed/logs_sy/ctp.log


## 4、日志分析



编撰人：admin、het




快速跳转



 * CMP移动H5其他调试技巧
   * 一、Fiddle调试
     * 1、作用
     * 2、适合场景
     * 3、使用步骤
       * 1）电脑开启fiddler软件，并设置监听端口号
         * 【Tools】开启设置
         * 【HTTPS】设置https类型的请求
         * 设置https证书信任，这样就可以抓https的请求包了
         * 设置代理的监听端口号和勾选远程数据抓取开启
       * 2）使用fiddle替换线上代码
       * 3）手机设置Fiddle代理
       * 4）视频教程
   * 二、微信客户端调试H5代码
     * 1、通过微信聊天窗口
     * 2、视频教程
   * 三、通过后台日志排查前端错误
     * 1、概述
     * 2、原理
     * 3、日志获取路径
     * 4、日志分析



分享链接分享链接

## 17. M3原生应用开发

> 原始路径：`/93/563/`  
> 相对路径：`93/563/README.md`  
> JS Chunk：`app.844f671c.js`

## M3原生应用开发


## 一、简述

为规范管理与提高 APP 的质量，需严格按照规范进行开发。


## 二、版本说明

标准产品 M3 APP 只有一个版本，官网最新的版本。因此，无论客户服务端 A8 是 6.1系列、7.x 系列还是最新的 8.x 系列 M3 官网最新客户全部兼容。也就是说 M3 官网最新的客户端始终是向下兼容所有已发布的 A8(A6, G6) 版本。

> 注：M3 首次发布于 V5-A8(A6) V6.1 版本


## 三、源码获取

 1. 由区域发起【代码申请表】申请 Android 或 iOS 源码。
 2. 通过 ctp-studio SVN 获取最新版本的 Android 或 iOS 源码。（不建议使用低版本）
 3. 如客户需要做 VPN 二次封装，需要提供未加固版本的 Android 或 iOS 客户端也需要发起【代码申请表】或者相关的研发支持流程。
 4. 如果是致远研发体系内的同事需要源码，可以通过发起【svn-git权限管理单】流程申请移动端对应模块的源码。
 5. M3 源码始终只提供当前最新的版本，不提供以前老版本源码。

> 注意：1、任何以自由流程、微信、QQ、邮件或致信等方式申请源码，一律不提供。因特殊情况无法发起【代码申请表】、【svn-git权限管理单】或无法通过 ctp-studio SVN 获取源码的情况，需由研发相关领导确认并同意后才可以提供源码。2、VPN 二次封装也属于二次开发。


## 四、开发环境搭建


## 1. Android 开发环境搭建

> 推荐使用 Android Studio 4.1.x 以上版本（以下文档已 Android Studio 4.1.2 为例）。最新版本 Android Studio 下载地址：https://developer.android.google.cn/studio/

## 第一步：Android Studio 安装：

> 略...

## 第二步：安装开发所需版本的 Android SDK:

启动 Android Studio ，点击 SDK Manager 安装需要的 Android SDK。点击【File】【Settings】【Appearance & Behavior】【System Settings】【Android SDK】在【SDK Platforms】选项卡中勾选 API Level 16、21、23、26、28 点击 【Apply】等等安装完成。如下图：



> 注意：API Level 会随着后续 M3 产品的版本更新会有变动。如最新的代码出现 Android SDK 版本问题导致编译或构建报错时，可以根据相关的报错信息添加对应的的 SDK 版本即可解决问题。

## 第三步：导入工程

点击【File】【Open...】选择对应的 M3 Android 工程根目录。一般 Android Studio 能自动识别 Android 工程，选择 M3 工程时也有对应的 Android 图标提示。如下图：



正确导入后 Android Studio 会自动进行首次工程编译，编译成功后在工程目录结构中可以看到以下结构。如下图：



## 第四步：首次构建

> 略...


## 2. iOS 开发环境搭建

## 第一步：下载安装 XCode

打开苹果应用市场 App Store 在搜索栏里输入 XCode 一般出现的第一个搜索结果便是最新版本的 XCode 版本。直接点击【获取】【安装】根据提示完成安装即可。如下图：



> 注意：根据苹果官方规定，最新版本 M3 iOS 客户端必须使用 XCode 12 及以上版本开发。

## 第二步：导入工程

启动 XCode 进入欢迎页面。点击【Open a project or file】选择 M3 工程文件，点击【Open】。如下图：




## 五、客开规范及常见问题


## 1、如何界定 APP 是客开版本

从严格意义上来讲，凡是非 M3 官网 https://m3.seeyon.com 以及应用市场上致远发布的 APP 版本，且对 APP 做了任何修改的版本均属于客开版本。其中也包含最小化的修改，如：VPN封装、替换 M3 图标、修改 APP 名称，以及任何二次打包后的 APP 等，均属于客开版本。


## 2、官方版本发布渠道

目前 M3 标准产品官方发布渠道一共有 5 个，分别如下： Android ：

 1. M3 官方网站 https://m3.seeyon.com
 2. 华为应用市场
 3. 小米应用市场
 4. VIVO 应用市场 iOS: 苹果 App Store

> 注意：除以上渠道下载的 APP 是标准官方版本，其他渠道下载的均不属于标准产品。


## 3、客开版本必须要修改包名

因 Android 和 iOS 程序在系统中运行是已包名作为唯一的标识以及进程名称等。如果包名相同，在安装过程中会将已有的程序覆盖替换，甚至无法直接安装。且客开的 APP 如果与标准产品的包名相同，会导致客开的 APP 无法上传市场，无法正确注册和使用第三方的服务。 如：客开版本需要注册小米的推送服务，在小米官方进行注册的时候，需要填写 APP 的包名，因标准产品已经注册了对应的包名，如果这时在使用标准产品的包名进行注册是无法通过注册的。如果使用与 M3 不同的包名注册，那么 M3 是无法正常使用新注册的服务。


## 4、客开版本签名

首先，我们自己的官方标准的应用包签名证书是绝不对外提供的。因为对外提供我们自己的证书存在诸多风险。首先，证书本身有作为身份认证的作用。并且，对外提供证书可能导致证书被封，特别是苹果 iOS 证书。苹果对此有较强的管控，一旦发现证书在多个 APP 下使用会直接封掉对应的证书。因此导致所有使用该证书的应用将无法使用或强制下架。其次，我们有集成一些第三方的服务，部分第三方的服务申请是提供了 APP 证书，一旦标准产品的证书对外提供可能导致我们自己申请的服务无法正常使用。最终影响标准产品用户的使用。


## 5、客开 APP 离线消息推送配置

> 注意：任何客开的版本，标准产品的离线消息推送服务均不能直接使用。因此，原生程序中对应推送消息服务的 KEY （证书）配置需要进行修改。

修改推送配置主要是在 Android 端。在工程目录中打开 M3 Module 下的 build.gradle 配置文件，找到 defaultConfig 配置模块，修改对应的配置即可。如下图：



目前 M3 离线消息推送 Android 端主要只支持华为和小米，因此主要修改华为和小米的配置即可。


## 6、M3 客开离线消息推送切换本地服务配置

【请参阅：M3客开离线消息推送切换本地服务配置】


## 7、客开 APP 升级更新

因客开版本的特殊性，大部分客开的版本会一直停留在已发布的标准产品某个版本上。这就导致了后续因设备系统升级、服务更新（包括第三方）、标准产品本身 BUG 的修复等问题因无法快速处理客户问题。比如：某些 Android 系统设备出现 APP 崩溃问题。iOS 14/15 兼容问题等。因标准产品是定期检查更新和适配已存在的问题，并定期发布最新已修复的版本。而客开版本因不升级或更新导致问题一直存在或无法修复。因此建议客开的版本随时或定期关注 M3 最新的版本发布，并做好升级合并的相关工作。以确保 APP 能实时解决当前已存在的问题。


## 8、苹果开发者账号申请

参考文档


## 9、海外用户申请 Google 地图 appKey 流程

参考文档


## 10、APP 安全加固

因 APP 安全问题，标准产品在发布前会对 APP 做进行二次加固处理（第三方加固）。建议客开版本的 APP 在开发完成发布前也对 APP 进行二次加固。保证 APP 使用过程中的用户数据安全。

编撰人：admin、het、lichaoj




快速跳转



 * M3原生应用开发
   * 一、简述
   * 二、版本说明
   * 三、源码获取
   * 四、开发环境搭建
     * 1. Android 开发环境搭建
       * 第一步：Android Studio 安装：
       * 第二步：安装开发所需版本的 Android SDK:
       * 第三步：导入工程
       * 第四步：首次构建
     * 2. iOS 开发环境搭建
       * 第一步：下载安装 XCode
       * 第二步：导入工程
   * 五、客开规范及常见问题
     * 1、如何界定 APP 是客开版本
     * 2、官方版本发布渠道
     * 3、客开版本必须要修改包名
     * 4、客开版本签名
     * 5、客开 APP 离线消息推送配置
     * 6、M3 客开离线消息推送切换本地服务配置
     * 7、客开 APP 升级更新
     * 8、苹果开发者账号申请
     * 9、海外用户申请 Google 地图 appKey 流程
     * 10、APP 安全加固



分享链接分享链接

## 18. M3客开离线消息推送切换本地服务

> 原始路径：`/93/563/564.html`  
> 相对路径：`93/563/564.md`  
> JS Chunk：`app.844f671c.js`

## M3客开离线消息推送切换本地服务


## M3离线消息服务

V8.0 及以上版本 M3 离线消息服务切换本地推送 - 配置说明文档


## 第一步：修改推送证书配置

路径在V5-A8(A6)安装目录 ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin\m3 中 pluginProperties.xml 配置文件，修改 appChannelCertificate 配置中，小米、华为和苹果的配置。如下图：



> 注意：8.0版本开始已经去掉百度的服务了，因此无百度服务的配置项，也不能继续使用百度服务。VIVO 和 OPPO 请忽略，目前不支持

> 特别说明：苹果服务的配置，file 是苹果的p12 证书文件存放路径（注意是完整路径不能是相对路径，只能是本地文件不能是网络路径），密码是 p12 证书文件的密码， production 参数是 1 和 2 ，1 是开发模式；2是生产模式。


## 第二步：修改推送服务切换本地服务

路径在V5-A8(A6)安装目录 ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin\m3 中 pluginProperties.xml 配置文件，修改 cloudServer -> pushServer -> openCloudPushService 配置，设置成 false 。如下图：



> 特别说明：8.0SP1 版开始可以直接在 SeeyonConfig 配置工具中进行配置。如下图：



> 注意：1、切换成本地推送服务后，统一使用本地的服务，且标准产品的推送默认将失效。因此，如果客户单独只客开了 Android 或者 iOS ，那么另外一个平台（Android 或 iOS）的标准产品将无法收到消息，必须通过客开走本地服务才能收到消息。2、如果客户不使用苹果，那么需要注释掉苹果服务的相关代码，否则会报错。相关代码如下图：




## 第三步：修改小米推送服务的渠道ID

在 apps-m3 模块中 MiPush.java 类中找到对应的 send 方法中修改即可。如下图：



> 注意：1、渠道ID（channel_id）需在小米平台进行申请，具体请参考小米官方文档。2、apps-m3 模块是 OA 主服务中的一个模块，如无相关源码需单独申请源码。如不修改此处是无法收到消息的。
> 
> 编撰人：admin、het


快速跳转



 * M3客开离线消息推送切换本地服务
   * M3离线消息服务
     * 第一步：修改推送证书配置
     * 第二步：修改推送服务切换本地服务
     * 第三步：修改小米推送服务的渠道ID



分享链接分享链接

## 19. M3客户端唤起第三方平台

> 原始路径：`/93/563/565.html`  
> 相对路径：`93/563/565.md`  
> JS Chunk：`app.844f671c.js`

## M3客户端唤起第三方平台


## 简介

该文档主要用于说明M3被第三方平台唤起的命令以及参数传递完成服务端三方登录实现。 三方应用打开M3定义的打开 APP URL 为 seeyon://m3 , 调用者可以根据自己的业务逻辑完成登录认证，M3 定义有标准穿透参数，如果三方平台按照 M3 定义的标准参数唤起，M3 客户端将会对参数处理，按照下文（参数说明）进行一些特殊范式的登录（如：用户名/密码方式），如果按照其余的格式传递，M3将不会对参数处理，会直接封装后发送给后台登录认证接口。


## 一、参数说明


## 1.1 M3标准格式参数

scheme:按照 URL 方式跳转 URL 固定为 <seeyon://m3>，带参数的跳转方式：<seeyon://m3?loginParams=XXXXXXX>

loginParams:调用登录方法所需要的参数为 JSON 格式

> 注意: loginParams 参数的值必须经过 URL Encoder 的方式转码

参数说明：

参数名         说明                                                                      是否必填
name        用户名                                                                     否
password    密码                                                                      否
ticket      单点登录 ticket （一般为第三方系统做单点登录认证的 Ticket）                                   否
serverUrl   M3                                                                      否
            服务器地址（例：http://192.168.10.236:8085）如果指定了该参数，会登录到指定的M3服务器；如果不指定该参数，登录到
            M3 当前设置的服务器。
ext         扩展参数                                                                    否

例:

{
    "name": "test1",
    "password": "tpassword",
    "ticket": "xxxxticket",
    "serverUrl": "http://192.168.10.236:8085",
    "ext":"扩张参数"
}


如果传递了 name 和 password，M3 将使用 name 为登录名称，password 为密码，进行标准功能的登录。 如果传递了 ticket，M3 将按照 A8 标准的三方认证类 SSOTicketLoginAuthentication.java 类进行单点登录。 如果不传，M3 客户端将会把整过 loginParams 以参数的形式传递给M3的登录接口，需要开发者按照 A8 登录集成功能进行集成（见示例：三、服务器单点登录参考示例）。


## 1.2 调用者自定义格式

scheme:按照 URL 方式跳转 URL 固定为 <seeyon://m3>，可选参数：serverUrl（参数说明见“M3标准格式参数”） 带参数的跳转方式：<seeyon://m3?key1=XXXXXXX&key2=XXXX&key3=XXXX> M3将把所有的参数封装为一个 JSON 对象，以 Key 为 loginParams 传递给后台登录接口。


## 二、M3定义的参数唤醒举例


## 2.1 Android

本地程序调用方式

方式一：

String params = "{" +
    "\"name\": \"test1\"," +
    "\"password\": \"tpassword\"," + 
    "\"serverUrl\": \"http://192.168.10.236:8085\"," +
    "\"ticket\": \"xxxxticket\"," + 
    "\"ext\": \"扩张参数\"" + 
"}";
params =URLEncoder.encode(params,"utf-8");
String url = "seeyon://m3?loginParams="+params; 
Intent in = new Intent(Intent.ACTION_VIEW, Uri.parse(url));
in.addFlags(Intent.FLAG_ACTIVITY_CLEAR_TASK|Intent.FLAG_ACTIVITY_NEW_TASK);
startActivity(in);


方式二：

String params = "{" + 
    "\"name\": \"test1\"," + 
    "\"password\": \"tpassword\"," +
    "\"serverUrl\": \"http://192.168.10.236:8085\"," + 
    "\"ticket\": \"xxxxticket\"," + 
    "\"ext\": \"扩张参数\"" + 
"}"; 

Intent in = new Intent();
in.setComponent(new ComponentName("com.seeyon.cmp", "com.seeyon.cmp.ui.LoadActivity"));
in.putExtra("loginParams", params);
in.addFlags(Intent.FLAG_ACTIVITY_CLEAR_TASK|Intent.FLAG_ACTIVITY_NEW_TASK);
startActivity(in);


网页程序调用方式

var params = "{" + 
    "\"name\": \"test1\"," + 
    "\"password\": \"tpassword\"," +
    "\"serverUrl\": \"http://192.168.10.236:8085\"," + 
    "\"ticket\": \"xxxxticket\"," + 
    "\"ext\": \"扩张参数\"" + 
"}"; 
params =URLEncoder.encode(params,"utf-8");


<a href="seeyon://m3?loginParams={params}">打开M3</a>



## 2.2 iOS

iOS跳转URL: <seeyonM3Phone://m3?loginParams=xx>

调用方式

// 拼接带参数的 URL 字符串
NSString *urlStr = @"seeyonm3phone://m3?loginParams={ \"name\": \"zlcs1\", \"password\": \"123456\", \"ticket\": \"ticket\", \"serverUrl\": \" http://192.168.10.236:8085\", \"ext\":\"extent\" }";  
// 将 URL 字符串进行转码，并创建 URL 对象
NSURL *url = [NSURL URLWithString:[urlStr stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]];
// 调用 sharedApplicaton openURL 方法通过 URL 唤起 M3
[[UIApplication sharedApplication] openURL:url];



## 三、服务端单点登录参考示例

M3 登录集成完全遵循 V5 登录验证逻辑可参见开放平台【登录集成（http://open.seeyon.com/book/ctp/ji-cheng-chang-jing/deng-lu-ji-cheng.html）】 这里的示例是自己实现登录认证的方式，如果采取了传递 userName/password 或者是 ticket 方式，A8 已经默认实现，请按照标准范式使用。 例：实现A8三方认证接口类 CustomLoginAuthentication.java 取出跳转命令传递的参数 loginParams 参数完成登录认证。



编撰人：admin、het




快速跳转



 * M3客户端唤起第三方平台
   * 简介
   * 一、参数说明
     * 1.1 M3标准格式参数
     * 1.2 调用者自定义格式
   * 二、M3定义的参数唤醒举例
     * 2.1 Android
     * 2.2 iOS
   * 三、服务端单点登录参考示例



分享链接分享链接

## 20. CMP移动离线消息支持说明

> 原始路径：`/93/563/567.html`  
> 相对路径：`93/563/567.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动离线消息支持说明


## 一、已接入服务

目前标准产品已接入平台有：华为官方服务、小米官方服务、苹果官方服务


## 二、支持设备

设备厂商   型号                           系统版本
苹果     iPhone（全型号）                  iOS 8及以上版本
苹果     iPad （全型号）                   iOS 8及以上版本
华为     全型号                          参考官方文档
小米     全型号                          参考官方文档
其他     均由小米提供服务，相关型号和系统版本参考小米官方文档   参考官方文档


## 三、消息提醒方式

目前标准产品，华为、小米和苹果设备的离线消息推送均采用的是通知栏消息（也就是系统级消息，也就是非透传类消息）。因此，消息的提醒方式全由设备系统自行管理和控制（部分设备在系统设置中有相应的用户设置）。APP 中未对消息提醒做单独控制，也无相关的功能。

透传消息和通知栏消息相关文档参考如下：

小米：https://dev.mi.com/console/doc/detail?pId=1292#_1_4

华为：https://developer.huawei.com/consumer/cn/doc/development/HMSCore-Guides/faq-0000001050042183

苹果：iOS 系统没有透传消息和通知栏消息的区分，只有一种系统消息

其他设备：无任何控制


## 四、其它 Android 设备的离线消息

首先，离线消息推送服务 Android 系统的官方服务是 Google 提供的 GMS (Google Mobile Service) 服务，但是国内对 Google 的限制，导致目前无法正常使用 Google 的相关服务，所以也无法使用 Android 系统官方的离线消息推送服务。

因此，国内的移动设备厂商为了解决此问题，部分厂商均有单独提供并推出自己的相关服务，比如：华为、小米等。

由于海外厂商的设备绝大部分都是直接使用的 Google 官方的 GMS 服务，但因上述原因，目前标准产品并未接入 GMS 服务。为了能解决离线消息的问题，目前我们对于非华为和小米的 Android 设备，均统一使用小米的服务代替。

比如：三星设备，三星设备默认就是使用的 GMS 服务。因上述原因，目前三星设备改用的是小米的服务提供离线消息推送。

由于，小米服务在非小米的设备上运行属于第三方服务，大部分设备厂商的系统为了优化自身系统性能等原因而禁用掉第三方的服务，因导致无法正常收到消息（其中就包括三星）。也因如此，目前无法保证非小米和华为的设备能正常收到离线消息。


## 五、角标

角标的显示目前均是由设备系统自行管理，相关服务只调用第三方提供的 API 通知了系统去显示角标，而是否显示、如何显示等问题，程序中不做任何控制，因系统行为也无法控制。


## 六、消息到达率与消息延迟

目前消息到达率均主要由第三方服务决定，根据实际测试分析：华为设备到达率在 85% 以上，小米设备到达率在 85% 以上，苹果设备到达率 95% 以上

由于用户量、服务器负载、网络、业务高峰等因素影响，消息正常延迟在 15 分钟以内，极限延迟不超过 30 分钟、平均延迟 30 秒


## 七、海外用户

目前标准产品只能保证国内用户的离线消息推送服务的正常使用，海外用户由于受到相关的政策和第三方服务的限制目前暂时无法保证一定可以收到消息。


## 八、附:

关于其他应用如：微信、QQ等在各个设备上能正常收到消息的问题说明：

经过技术分析与相关资料查询，如：腾讯、阿里等这类用户量上亿级厂商的应用，绝大部分的设备厂商均会单独适配或单独提供相关的服务，甚至有些厂商与此有直接的合作。因此，这类应用在绝大部分厂商的设备上基本都能正常收到离线消息。原因其实非常明确。像微信活跃用户达到12亿，且几乎是现在人手必备而不可缺少的通讯应用，外加上现在的移动支付等。设备厂商如果无法对微信这样的 APP 提供更好更全的服务，那么是一定会对设备厂商带来相应的影响。因为，用户可能会因为手机无法收到微信的消息而更换新的手机或其他厂商的手机，但是绝大部分不会因为无法收到微信消息，而换掉微信。

编撰人：admin、het




快速跳转



 * CMP移动离线消息支持说明
   * 一、已接入服务
   * 二、支持设备
   * 三、消息提醒方式
   * 四、其它 Android 设备的离线消息
   * 五、角标
   * 六、消息到达率与消息延迟
   * 七、海外用户
   * 八、附:



分享链接分享链接

## 21. 苹果开发相关-账号、证书、上架

> 原始路径：`/93/563/1219.html`  
> 相对路径：`93/563/1219.md`  
> JS Chunk：`app.844f671c.js`

## 苹果开发相关-账号、证书、上架


## 各类账号介绍【上架方式】

其中ABM账号不能用于开发者开发使用，只是用于管理分发APP下载。


## 一、申请开发者帐号

注册Apple ID：https://appleid.apple.com/account 账号管理操作文档：https://developer.apple.com/cn/help/account/ 开发者账号注册：https://developer.apple.com/cn/programs/enroll/ ABM苹果商务账号注册：https://business.apple.com/#enrollment 【Apple 商务管理使用手册：https://support.apple.com/zh-cn/guide/apple-business-manager/axm402206497/web】




## 二、开发者账号操作



## 1、创建开发证书【Certificates】

1）、development开发和distribution发布，用于哪些开发者账号和mac可以开发和发布app

2）、推送证书也在这里创建 https://developer.apple.com/cn/help/account/create-certificates/create-developer-id-certificates

## 2、标识符【Identifiers】(包名)

bundleId和App GroupId

https://developer.apple.com/cn/help/account/manage-identifiers/register-an-app-id

## 3、设备【Devices】

注册安装测试包的设备

https://developer.apple.com/cn/help/account/register-devices/register-a-single-device

## 4、描述文件【Profiles】

对应包名，创建开发或发布的描述文件

https://developer.apple.com/cn/help/account/manage-provisioning-profiles/create-a-development-provisioning-profile

## 5、开发或发布M3需要的证书和描述文件：

1)、开发或发布证书为.p12文件

2)、推送证书也是.p12文件用于后端或者三方推送平台

测试包需要开发证书（正式包需要发布证书）；三个Identifiers、以及对应的3个Profiles（需要区分开发和发布）；1个推送证书（后端推送服务）【参考包名：com.seeyon.m3.core(主工程)、com.seeyon.m3.callkit(组件)、com.seeyon.m3.share(组件)】


## 三、APP上架发布（Appstore Connect）

## 1、创建APP信息

上架appstore和ABM账号发布app的区别：



## 2、打包上传

创建好app信息版本号后，可以通过苹果官方app：Transporter上传包，也可以使用Xcode打包后上传。



Transporter软件上传





如果遇到包校验失败，解决对应问题后，需要移除再重新打包上传



## 3、提交审核

勾选好对应构建的包，就可以提交审核了。





编撰人：raosj、het




快速跳转



 * 苹果开发相关-账号、证书、上架
   * 各类账号介绍【上架方式】
   * 一、申请开发者帐号
   * 二、开发者账号操作
     * 1、创建开发证书【Certificates】
     * 2、标识符【Identifiers】(包名)
     * 3、设备【Devices】
     * 4、描述文件【Profiles】
     * 5、开发或发布M3需要的证书和描述文件：
   * 三、APP上架发布（Appstore Connect）
     * 1、创建APP信息
     * 2、打包上传
     * 3、提交审核



分享链接分享链接

## 22. iOS苹果APP开发入门

> 原始路径：`/93/563/1220.html`  
> 相对路径：`93/563/1220.md`  
> JS Chunk：`app.844f671c.js`

## iOS苹果APP开发入门


## 入门导图




## 一、准备工作

## 1、开发设备

 * Mac电脑：苹果的开发工具Xcode只能在Mac电脑上运行，因此你需要一台Mac电脑来进行iOS应用开发。
 * iOS设备：虽然可以使用模拟器进行应用程序测试，但最好还是拥有一台真实的iOS设备来进行真机测试，以确保应用在实际设备上的表现。
 * 数据线：用于连接iOS设备到Mac电脑，进行应用程序的安装和调试。建议原装数据线。
 * Apple ID：注册成为苹果开发者需要一个有效的Apple ID，用于访问开发者工具和资源，以及在App Store上发布应用程序。

## 2、下载安装Xcode

Xcode是苹果官方的集成开发环境，用于开发iOS和macOS应用程序。你可以从Mac App Store中免费下载安装。https://developer.apple.com/xcode/

## 3、注册成为苹果开发者

注册成为苹果开发者可以获得访问开发者工具和资源的权限，以及在App Store上发布应用程序的资格。你可以在苹果开发者官网注册：https://developer.apple.com/cn/programs/enroll/

## 4、账号、证书、上架

参考Seeyon开发文档：CMP移动平台->M3原生应用开发->苹果开发相关-账号、证书、上架


## 二、Swift编程语言：(或者使用Objective-C)

## 1、基础语法

Swift语言的基本语法规则，如变量、常量、函数、控制流等。

## 2、数据类型

Swift中的数据类型，包括整型、浮点型、字符串、数组、字典等。

## 3、面向对象编程

Swift中的面向对象编程概念，如类、结构体、协议、扩展等。 Swift官方文档：https://docs.swift.org/swift-book/documentation/the-swift-programming-language/ Objective-C官方文档：https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html


## 三、iOS开发基础

## 1、应用程序结构

iOS应用程序的基本结构，包括应用生命周期、应用委托、视图控制器等。 APP生命周期文档：https://developer.apple.com/documentation/uikit/app_and_environment/managing_your_app_s_life_cycle

## 2、界面设计

设计iOS应用的用户界面，包括使用Storyboard和XIB文件进行界面设计。需要掌握UIKit框架，即官方提供的UI API UIKit： https://developer.apple.com/documentation/uikit

## 3、用户交互

处理用户输入、响应事件以及实现界面交互逻辑。


## 四、UI设计

使用sdk api创建页面元素，以及按钮点击、文本输入等交互。

## 1、Interface Builder

使用Xcode中的Interface Builder进行界面设计，拖拽控件、设置属性等。

## 2、UI控件

常用的UI控件，如按钮、标签、文本框、表格视图等。

## 3、布局方式

Auto Layout约束、Stack View等布局方式，实现界面的自适应和响应式设计。 官方文档：https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/


## 五、数据存储

## 1、Core Data

使用Core Data框架进行数据的持久化存储和管理。CoreData官方文档：https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/CoreData/index.html

## 2、SQLite

在iOS应用中使用SQLite数据库进行数据存储操作。SQLite推荐三分库使用FMDB：https://github.com/ccgus/fmdb


## 六、网络通信

官方文档链接：https://developer.apple.com/documentation/foundation/url_loading_system


## 1、URLSession

使用URLSession进行网络请求和数据交互。https://developer.apple.com/documentation/foundation/urlsession


## 2、Alamofire

Alamofire 是一个流行的 Swift 网络库，用于简化 iOS 和 macOS 应用程序中的网络请求。https://github.com/Alamofire/Alamofire


## 七、调试与测试

## 1、Xcode调试工具

Xcode中的调试工具，如断点、调试器、日志等。

## 2、模拟器

使用Xcode中的模拟器进行应用程序的测试和调试。https://developer.apple.com/cn/documentation/xcode/running_your_app_in_the_simulator_or_on_a_device/


## 八、发布应用

官方文档：https://developer.apple.com/app-store-connect/

## 1、打包应用

使用Xcode将应用程序打包成.ipa文件。

## 2、提交App Store

将应用程序提交到App Store进行审核和发布。https://developer.apple.com/cn/documentation/xcode/preparing_your_app_for_distribution/

编撰人：raosj、het、lichaoj




快速跳转



 * iOS苹果APP开发入门
   * 入门导图
   * 一、准备工作
     * 1、开发设备
     * 2、下载安装Xcode
     * 3、注册成为苹果开发者
     * 4、账号、证书、上架
   * 二、Swift编程语言：(或者使用Objective-C)
     * 1、基础语法
     * 2、数据类型
     * 3、面向对象编程
   * 三、iOS开发基础
     * 1、应用程序结构
     * 2、界面设计
     * 3、用户交互
   * 四、UI设计
     * 1、Interface Builder
     * 2、UI控件
     * 3、布局方式
   * 五、数据存储
     * 1、Core Data
     * 2、SQLite
   * 六、网络通信
   * 1、URLSession
   * 2、Alamofire
   * 七、调试与测试
     * 1、Xcode调试工具
     * 2、模拟器
   * 八、发布应用
     * 1、打包应用
     * 2、提交App Store



分享链接分享链接

## 23. H5应用集成方案

> 原始路径：`/93/568.html`  
> 相对路径：`93/568.md`  
> JS Chunk：`app.844f671c.js`

## H5应用集成方案


## 一、M3集成第三方H5页面


## 1、概述

M3集成第三方H5页面，通常是通过CIP平台做的单点登录方式，通过两个系统的人员数据对接，做单点登录后，跳转到第三方H5应用页面；由于第三方页面运行在M3 原生APP中，第三方页面也可以通过导入CMP相关JS文件调起APP原生的一些功能，比如：拍照、定位、扫一扫等原生特色功能


## 2、集成中常预见的问题说明

## 1）第三方H5页面关闭M3的webview

问：从M3统一待办进入到第三方处理页面，处理完成后如何关闭webview？ 答：关闭webview的话必须要调用M3 app中的关闭webview的原生方法，那么在第三方的web 页面需要导入原生JS库和cmp.js，当处理完成的逻辑执行完成后调用cmp.href.closePage()具体如下：

第三方.html

<!--导入原生js库-->
<script  src="http://cmp/v1.0.0/js/cordova/__CMPSHELL_PLATFORM__/cordova.js"></script>
<script  src="http://cmp/v1.0.0/js/cordova/cordova-plugins.js"></script>
<!--导入cmp.js-->
<script  src="http://cmp/v/js/cmp-i18n.js"></script>
<script  src="http://cmp/v/js/cmp.js"></script>
<script>
    ...
    ...
    $("#处理按钮").bind("tap",function(){
    //处理提交的逻辑
		cmp.href.closePage();==================================>调用关闭webview的函数
        });
</script>


## 2）第三方页面刷新统一待办

问：从M3统一待办进入到第三方页面详细页面审批完成后，如何刷新待办列表 ？ 答：需要使用M3原生提供的刷新函数webviewListener进行刷新。

第三方.html

<!--导入原生js库-->
<script  src="http://cmp/v1.0.0/js/cordova/__CMPSHELL_PLATFORM__/cordova.js"></script>
<script  src="http://cmp/v1.0.0/js/cordova/cordova-plugins.js"></script>
<!--导入cmp.js-->
<script  src="http://cmp/v/js/cmp-i18n.js"></script>
<script  src="http://cmp/v/js/cmp.js"></script>
<script src="http://cmp/v/js/cmp-webviewListener.js"></script>
<script>
    ...
    ...
    $("#处理按钮").bind("tap",function(){
    //处理提交的逻辑
    //调用刷新统一待办列表逻辑
        cmp.webViewListener.fire({
              type: 'com.seeyon.m3.ListRefresh',
              data: {type: 'update'}
       });
    });
</script>



## 二、微协同H5页面被第三方APP集成


## 1、单点登录

一般情况下，第三方APP集成微协同一般是APP添加一个图标作为应用入口或者将协同系统的待办作为第三方APP统一待办，直接进入到详细页面，当然要进行详细页面，前提需要进行单点登录后才能进入微协同H5页面



 * 用户点击第三方APP上集成微协同的图标或者从第三方应用的统一待办发起登录申请
 * 第三方服务端需要提前喝OA系统对接人员数据，一般情况下出于安全设计考虑第三方服务端会生成一个临时加密ticket，此ticket和OA系统的登录名进行绑定关系
 * 第三方系统通过此ticket和OA系统进行多次握手认定后认为请求是有效的进行登录操作，然后将cookie返回给H5页面
 * H5再重定向到OA系统中的H5应用页面，完成整个单点登录过程


## 2、适配必要的第三方APP原生功能

## 1）概述

第三方App接入微协同，微协同标准应用有涉及到webview、文件等操作时，第三方App认为平台提供的接口解决办法不符合第三方App的要求，可进行第三方App接口的注册，对平台自身的代码无任何侵入（前提条件：第三方App必须具备Hybrid App能力，必须能提供JS调用原生接口的能力）

原则上如果注册了第三方App的原生接口，则调用第三方原生接口，否则会调用CMP平台认为比较合理的备用接口来实现和原生差不多的功能；可注册的接口包括：

 1. 关闭webview（第三方App想关闭webview此接口必须注册，无备用接口）；
 2. 附件下载（download）；
 3. 附件上传（upload）；
 4. 附件查看（read）；
 5. 选择附件（getFile）；
 6. 照相、选择相册（camera）；
 7. 获取定位位置（getPosition）

## 2）如何注册

 * 找到微协同服务器目录第三方平台接口注册文件【A8目录/webapps/seeyon/m3/cmp/extend/cmp-thirdPlatformPlugins.js】
 * 打开文件，进行接口函数注册



## 3）接口注册规范







## 4）视频教程


## 三、微协同H5页面被第三方APP集成（过时版本）

致远微协同标准集成只支持微信服务号、企业微信/微信企业号、钉钉。 随着企业的发展，很多企业都会考虑使用自己专属的APP平台，来塑造企业形象，实现统一移动办公。 致远微协同可以通过少量客开来实现在其它APP上使用，本文主要针对第三方APP如何集成微协同做介绍，主要分以下几个步骤：

 1. 组织机构同步（可选）
 2. 身份认证
 3. 访问协同H5页面
 4. 消息推送（可选）

依赖版本要求：V6.1SP2（含）以上，包含微协同插件。


## 1）组织机构同步

第三方APP都有人员唯一标识，需要和V5人员建议对应关系，一般有两种方式：

 * 通过组织机构同步实现自动绑定，V5组织架构也会一目了然的展现在第三方APP通讯录中
 * 员工自行手动绑定

详细手册请参考组织同步文档：

 * http://open.seeyon.com/book/ctp/ji-cheng-chang-jing/zu-zhi-mo-xing-tong-bu.html


## 2）身份认证

访问协同H5页面，必须有人员身份，并且占用PC并发，实现方式：

 * 通过Rest接口获取人员token

//Rest请求地址
协同地址 + "/seeyon/rest/token/" + restName + "/" + restPassword + "?loginName=" + loginName + "&memberId=" + memberId + "&userAgentFrom=weixin

参数：
    restName：Rest账号
    restPassword：Rest密码
    loginName：协同人员账号
    memberId：协同人员ID
返回值：
    {"bindingUser":{},"id":"93701378-c5e7-4d9b-9938-7b243baaff17"}，id为需要的token


详细手册请参考REST调用文档：

 * http://open.seeyon.com/book/ctp/restjie-kou/gai-shu.html


## 3）访问协同H5页面

默认访问微协同待办首页，可以自定义直接访问某应用首页

//访问H5页面
协同地址/seeyon/H5/collaboration/index.html?token=93701378-c5e7-4d9b-9938-7b243baaff17&html=&loginName=

参数：
    token：人员身份信息
    html：要访问的H5页面地址，传空默认进入微协同待办首页
    loginName：协同人员姓名，需URLEncoder.encode



## 4）消息推送

通过接口实现消息推送到第三方APP

通过实现MessagePipeline接口，实现消息推送
    消息链接：可参考WeixinMessagePipeline拼接
    消息穿透：同样需要人员身份信息token


详细手册请参考消息集成文档：

 * http://open.seeyon.com/book/ctp/ji-cheng-chang-jing/xiao-xi-ji-cheng.html


## 5）其它注意事项

 * 返回问题、关闭问题

在协同安装目录\webapps\seeyon\m3\cmp\js\cmp.js中
    _.platform.wechatOrDD，设为true
    _.href.closePage，实现第三方app关闭webview的方法


 * 文件下载问题、文件查看问题

重写cmp.att.download_third方法
重写cmp.att.read_third方法


详细手册请参考CMP文档：

 * http://open.seeyon.com/seeyon/cmp2.0/book/chapter-4/questions.html#disanfang


## 小程序集成方案

微信小程序是一种全新的连接用户与服务的方式，它可以在微信内被便捷地获取和传播，同时具有出色的使用体验。 我们通过微协同H5与小程序进行了快速集成，入口更快捷，体验更顺畅。 本文详细介绍小程序通过客开集成的方案，主要分以下几个步骤：


## 1）小程序注册

小程序注册登录地址：https://mp.weixin.qq.com

首先需要完成小程序的注册并且通过微信认证，每个邮箱仅能申请一个小程序，目前有2种方式：

 * 单独注册小程序，通过微信认证（提供企业资质信息，支付认证费用）
 * 【推荐使用】通过已认证公众号快速注册并认证小程序，可复用公众号资质（免认证）

注：小程序名称谨慎填写，因为小程序发布后，只能通过再次认证方式改名。


## 2）小程序配置

 1. 获取AppID和AppSecret
    
    在【设置-开发设置】开发者ID中获取
    
    

 2. 配置服务器域名和业务域名
    
    在【设置-开发设置】服务器域名/业务域名中配置，域名为协同服务器外网地址
    
    * 服务器域名/业务域名需经过ICP备案，且只支持https安全域名
    * 业务域名配置的时候需要校验，参考腾讯说明：请下载校验文件，并将文件放置在域名根目录下，例如wx.qq.com，并确保可以访问该文件。如配置中遇到问题，请查看具体指引
    
    


## 3. V5协同配置

 * 协同版本在V7.0SP2（含）以上
 * 协同有微协同插件
 * 部署《小程序插件》包
 * 在微协同基础配置中配置协同服务器地址
   * 协同服务器有外网地址，有经过ICP备案的域名，且只支持https安全协议




## 4. 小程序代码开发

 1. 下载小程序开发工具
    
    * https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html

 2. 获取代码
    
    * 申请V5微协同小程序集成代码
      * 下载代码
    * 解压代码，通过小程序开发工具导入代码，修改AppID
    
    

 3. 修改代码
    
    * 在config.js中修改相关配置信息
      
      hostPrefix：V5协同服务器域名
      
      appid：小程序AppID
      
      html：要跳转的H5地址，默认为空（微协同首页）
    
    

 4. 上传代码


## 5. 小程序代码审核

在【开发管理】中维护，将开发版本提交审核，也可选为体验版本先进行体验测试

 * 提交微信审核，可能需要测试账号才能通过审核




## 6. 小程序发布

在【开发管理】中维护，将审核通过版本正式发布使用




## 7. 小程序使用

公布小程序码，通过扫码使用，使用方式有两种：

 * 手机号一键登录，通过手机号免绑定，前提是微信绑定的手机号和协同账号的手机号一致
 * 协同账号登录，通过协同账号密码绑定



编撰人：admin、het、lichaoj




快速跳转



 * H5应用集成方案
   * 一、M3集成第三方H5页面
     * 1、概述
     * 2、集成中常预见的问题说明
       * 1）第三方H5页面关闭M3的webview
       * 2）第三方页面刷新统一待办
   * 二、微协同H5页面被第三方APP集成
     * 1、单点登录
     * 2、适配必要的第三方APP原生功能
       * 1）概述
       * 2）如何注册
       * 3）接口注册规范
       * 4）视频教程
   * 三、微协同H5页面被第三方APP集成（过时版本）
     * 1）组织机构同步
     * 2）身份认证
     * 3）访问协同H5页面
     * 4）消息推送
     * 5）其它注意事项
   * 小程序集成方案
     * 1）小程序注册
     * 2）小程序配置
   * 3. V5协同配置
   * 4. 小程序代码开发
   * 5. 小程序代码审核
   * 6. 小程序发布
   * 7. 小程序使用



分享链接分享链接

## 24. CMP移动端客开常见问题

> 原始路径：`/93/569.html`  
> 相对路径：`93/569.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动端客开常见问题


## 1、问题：Android手机点击左上角返回按钮，没有关闭或者没有返回到指定页面，页面顺序混乱



原因： 致远的移动端H5应用使用浏览器标准接口popstate来监听页面的返回事件，但是Android手机系统自10以来，提升了安全系数，如果用户在当前页面无任何手动主动操作行为（比如滑一下页面，点击一下按钮等动作），此时直接点击第三方APP原生的返回按钮，手机系统会认为不是用户的主动行为，不会响应popstate事件，导致H5应用对页面路由处理不了，所以就导致了页面返回混乱

解决方案： 需要用户的APP监听到原生的返回按钮事件，由于是集成的致远的移动端H5应用，当用户点击原生返回按钮的时候，原生返回事件代码被触发，此时原生APP调用H5兼容性事件**cmp.event.trigger("popstate",window)**即可处理H5应用的返回事件，保证页面返回路由正常

原生代码调用示例：

//前提：Android原生客户端要监听原生的返回按钮  
//第一步，设置调用H5页面js代码可行  
webView.getSettings().setJavaScriptEnabled(true);
//第二步：使用原生的方式调用js接口  
webview.loadUrl("javascript:try{cmp.event.trigger(\"popstate\",window)}catch(e){}"); //注意，一定要try catch避免代码出错报运行态错误信息


编撰人：admin、het


快速跳转



 * CMP移动端客开常见问题
   * 1、问题：Android手机点击左上角返回按钮，没有关闭或者没有返回到指定页面，页面顺序混乱



分享链接分享链接

## 25. CMP小程序集成方案

> 原始路径：`/93/912.html`  
> 相对路径：`93/912.md`  
> JS Chunk：`app.844f671c.js`

## CMP小程序集成方案

微信小程序是一种全新的连接用户与服务的方式，它可以在微信内被便捷地获取和传播，同时具有出色的使用体验。

我们通过微协同H5与小程序进行了快速集成，入口更快捷，体验更顺畅。 本文详细介绍小程序通过客开集成的方案，主要分以下几个步骤：




## 1. 小程序注册

小程序注册登录地址：https://mp.weixin.qq.com

首先需要完成小程序的注册并且通过微信认证，每个邮箱仅能申请一个小程序，目前有2种方式：

 * 单独注册小程序，通过微信认证（提供企业资质信息，支付认证费用）
 * 【推荐使用】通过已认证公众号快速注册并认证小程序，可复用公众号资质（免认证）

注：小程序名称谨慎填写，因为小程序发布后，只能通过再次认证方式改名。


## 2. 小程序配置

 1. 获取AppID和AppSecret
    
    在【设置-开发设置】开发者ID中获取
    
    

 2. 配置服务器域名和业务域名
    
    在【设置-开发设置】服务器域名/业务域名中配置，域名为协同服务器外网地址
    
    * 服务器域名/业务域名需经过ICP备案，且只支持https安全域名
    * 业务域名配置的时候需要校验，参考腾讯说明：请下载校验文件，并将文件放置在域名根目录下，例如wx.qq.com，并确保可以访问该文件。如配置中遇到问题，请查看具体指引
    
    


## 3. V5协同配置

 * 协同版本在V7.0SP2（含）以上
 * 协同有微协同插件
 * 部署《小程序插件》包
 * 在微协同基础配置中配置协同服务器地址
   * 协同服务器有外网地址，有经过ICP备案的域名，且只支持https安全协议




## 4. 小程序代码开发

 1. 下载小程序开发工具
    
    * https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html

 2. 获取代码
    
    * 申请V5微协同小程序集成代码
      * 下载代码
    * 解压代码，通过小程序开发工具导入代码，修改AppID
    
    

 3. 修改代码
    
    * 在config.js中修改相关配置信息
      
      hostPrefix：V5协同服务器域名
      
      appid：小程序AppID
      
      html：要跳转的H5地址，默认为空（微协同首页）
    
    

 4. 上传代码


## 5. 小程序代码审核

在【开发管理】中维护，将开发版本提交审核，也可选为体验版本先进行体验测试

 * 提交微信审核，可能需要测试账号才能通过审核




## 6. 小程序发布

在【开发管理】中维护，将审核通过版本正式发布使用




## 7. 小程序使用

公布小程序码，通过扫码使用，使用方式有两种：

 * 手机号一键登录，通过手机号免绑定，前提是微信绑定的手机号和协同账号的手机号一致
 * 协同账号登录，通过协同账号密码绑定



编撰人：lichaoj、het




快速跳转



 * CMP小程序集成方案
 * 1. 小程序注册
 * 2. 小程序配置
 * 3. V5协同配置
 * 4. 小程序代码开发
 * 5. 小程序代码审核
 * 6. 小程序发布
 * 7. 小程序使用



分享链接分享链接

## 26. CMP移动平台概述

> 原始路径：`/93/1118.html`  
> 相对路径：`93/1118.md`  
> JS Chunk：`app.844f671c.js`

## CMP移动平台概述

协同移动平台即Collaboration Mobile Platform，它是以协同为核心，移动技术为基础。为企业应用移动化，提供了从开发、调试、测试以及到部署、运行和管控的全生命周期的管理支撑。不仅提供快速集成企业现有的原生、H5移动应用的能力，还为企业应用定制化开发提供了支撑，真正的实现把企业应用放到一个移动平台上。


## 一、移动 CMP 平台简介

CMP 全称 Collaboration Mobile Platform 协同移动平台(也有理解为 Core Mobile Plaform 核心移动平台)。CMP 作为移动基础平台，提供移动开发与运行的基础规范以及基础组件。

CMP 也是跨平台前端框架。基于 CMP 平台开发的协同应用，均可以运行在 M3 APP、微信微协同、企业微信微协同、钉钉、飞书、Welink或第三方 APP 中。同时 CMP 平台也提供了第三方 H5 应用集成到 M3 APP 中的能力。按照 CMP 提供的 H5 标准集成规范，集成的 H5 APP 均可以正常运行在 M3 APP 中。

同时，CMP 平台也提供了很多基础 API，如：拍照、文件、定位、相册等本地原生功能 API，缓存、路由、类加载、AJAX等前端基础能力，并且还提供了丰富的 UI 组件。

> CMP API 文档请查阅：https://open.seeyoncloud.com/cmpdev


## 二、CMP 基础架构

CMP 架构是基于移动原生与 H5 混合模式开发。整体总共分为4个部分：




## 核心层

核心层主要是对 Android、iOS、Harmony(鸿蒙) 系统的基础能力进行规范统一的抽象封装如：网络请求、本地文件读写等。也是移动端运行环境的基础。M3 APP 的原生应用部分的开发也是基于此层开发。


## 移动平台 CMP 层

主要通过原生程序结合 H5 混合方式开发对上层提供统一的基础 API，并且在移动平台层将第三方集成和跨平台的能力进行了封装，并且提供了统一的标准与开发规范。保证了上层“应用层”开发过程中以及后续程序运行中可以无需过多的关注平台与环境问题，而更多的关注业务的问题。

Cordova 是一套开源移动开发框架，隶属于 Apache 开源项目，通过它，开发者可以用标准WEB技术：HTML5、CSS3、JavaScript，来开发跨平台 App。

Cordova 也是我们 CMP 平台 H5 与原生程序间相互调用通讯的中间件。

Cordova 目前支持的平台有：Android、Blackberry 10、iOS、OS X、Ubuntu、Windows、WP8。


## 应用层

基于 CMP 平台提供的标准规范与 API 开发出的各场景可独立运行的应用模块。通过 CMP 的规范完成开发，并使用 S3 工具编译构建后生成 M3 APP 可运行的 ZIP 与微协同可运行的 HTML 静态资源。因此能做到一次编写构建，多端运行。


## 客户端

此层分两部分：

第一部分：M3 APP（V5-A8\A6\G6 移动办公/移动政务/政务督办APP），由致远自己研发的可运行与 Android、iOS、Harmony 系统的独立 APP。M3 中所运行的应用全部基于 H5 完成开发。并通过 S3 工具编译生成可运行与 M3 中的 ZIP 包。

第二部分：微协同。通过 H5 方式提供可集成到第三方系统的致远移动办公系统，目前标准已支持集成到微信、企业微信、钉钉、飞书和 Welink APP 中。

> 特别说明：微协同第三方集成，标准产品有提供集成到第三方 APP 中的能力，但是实际集成中可能还是会存在部分少量的开发或适配，目前还是主要通过客开方式主导完成。

 * CMP 作为移动基础平台提供移动开发所需组件，业务应用按照 CMP 平台规范，开发出前端 HTML、JS 等文件，再通过 S3 工具编译后，输出生成可以运行的M3 ZIP 包和微协同静态 HTML 资源；
 * M3 ZIP 包运行在 M3 客户端上，微协同静态资源运行在微信、企业微信、钉钉、飞书、Welink 等第三方办公 APP 平台
 * 总结：一次编码，一次编译，多端运行


## 三、应用开发简介

H5 应用开发请参阅：【移动端H5应用基础开发】

Android / iOS 原生应用开发请参阅：【M3原生应用开发】

第三方 H5 集成请参阅：【H5应用集成】


## 四、平台特性

 1. 平台化 CMP平台为应用的集成提供了支撑，真正的把企业应用集成到一个移动平台。

 2. 定制性更强 使用H5语言，可以直接修改应用的代码，即可完成应用定制。

 3. 组件化 所有接口组件化，只需选择所需组件，即可组装出一个应用。

 4. 更简单
    
    * 开发简单：只需要一套代码，不需要分别对iOS、android系统进行开发；
    
    * 维护简单：降低开发、维护成本；
    
    * 使用简单：触手可用，不需要单独安装iOS、android应用；

 5. 更安全
    
    * 提供VPN私有网络环境运行的能力；
    
    * 标准的Https网络传输加密；
    
    * 应用白名单；
    
    * 安全的CMP运行环境，原生应用加固、代码混淆、运行环境安全检测；
    
    * 密码、手势、声纹、账号设备绑定的安全认证；
    
    * 本地数据加密存储；

 6. 自适应强 CMP平台使用Hybrid混合开发模式，采用国际通用标准的Html5语言开发规范，实现一次开发，多平台、多设备、多应用运行：

 * 多平台：可以运行在iOS、Android以及Windows Phone系统的设备；

 * 多设备：自适应布局，可以运行在不同尺寸的设备上，如iPad、iPhone设备。

 * 多应用：可以运行在M3、微信、钉钉以及支持Hybrid模式的应用上。

 7. 更新快 使用H5开发，可以实现快速更新，不需要重新安装iOS、Android应用，也不需要通过漫长的苹果审核周期，让用户无感知的使用新应用。
    编撰人：lichaoj、het、puwb


快速跳转



 * CMP移动平台概述
   * 一、移动 CMP 平台简介
   * 二、CMP 基础架构
     * 核心层
     * 移动平台 CMP 层
     * 应用层
     * 客户端
   * 三、应用开发简介
   * 四、平台特性



分享链接分享链接

## 27. 概述

> 原始路径：`/1267/`  
> 相对路径：`1267/README.md`  
> JS Chunk：`app.844f671c.js`

## 概述

协同移动平台即Collaboration Mobile Platform，它是以协同为核心，移动技术为基础。为企业应用移动化，提供了从开发、调试、测试以及到部署、运行和管控的全生命周期的管理支撑。不仅提供快速集成企业现有的原生、H5移动应用的能力，还为企业应用定制化开发提供了支撑，真正的实现把企业应用放到一个移动平台上。


## 一、移动 CMP 平台简介

CMP 全称 Collaboration Mobile Platform 协同移动平台(也有理解为 Core Mobile Plaform 核心移动平台)。CMP 作为移动基础平台，提供移动开发与运行的基础规范以及基础组件。

CMP 也是跨平台前端框架。基于 CMP 平台开发的协同应用，均可以运行在 M3 APP、微信微协同、企业微信微协同、钉钉、飞书、Welink或第三方 APP 中。同时 CMP 平台也提供了第三方 H5 应用集成到 M3 APP 中的能力。按照 CMP 提供的 H5 标准集成规范，集成的 H5 APP 均可以正常运行在 M3 APP 中。

同时，CMP 平台也提供了很多基础 API，如：拍照、文件、定位、相册等本地原生功能 API，缓存、路由、类加载、AJAX等前端基础能力，并且还提供了丰富的 UI 组件。

> CMP API 文档请查阅：https://open.seeyoncloud.com/cmpdev


## 二、CMP 基础架构

CMP 架构是基于移动原生与 H5 混合模式开发。整体总共分为4个部分：




## 核心层

核心层主要是对 Android、iOS、Harmony(鸿蒙) 系统的基础能力进行规范统一的抽象封装如：网络请求、本地文件读写等。也是移动端运行环境的基础。M3 APP 的原生应用部分的开发也是基于此层开发。


## 移动平台 CMP 层

主要通过原生程序结合 H5 混合方式开发对上层提供统一的基础 API，并且在移动平台层将第三方集成和跨平台的能力进行了封装，并且提供了统一的标准与开发规范。保证了上层“应用层”开发过程中以及后续程序运行中可以无需过多的关注平台与环境问题，而更多的关注业务的问题。

Cordova 是一套开源移动开发框架，隶属于 Apache 开源项目，通过它，开发者可以用标准WEB技术：HTML5、CSS3、JavaScript，来开发跨平台 App。

Cordova 也是我们 CMP 平台 H5 与原生程序间相互调用通讯的中间件。

Cordova 目前支持的平台有：Android、Blackberry 10、iOS、OS X、Ubuntu、Windows、WP8。


## 应用层

基于 CMP 平台提供的标准规范与 API 开发出的各场景可独立运行的应用模块。通过 CMP 的规范完成开发，并使用 S3 工具编译构建后生成 M3 APP 可运行的 ZIP 与微协同可运行的 HTML 静态资源。因此能做到一次编写构建，多端运行。


## 客户端

此层分两部分：

第一部分：M3 APP（V5-A8\A6\G6 移动办公/移动政务/政务督办APP），由致远自己研发的可运行与 Android、iOS、Harmony 系统的独立 APP。M3 中所运行的应用全部基于 H5 完成开发。并通过 S3 工具编译生成可运行与 M3 中的 ZIP 包。

第二部分：微协同。通过 H5 方式提供可集成到第三方系统的致远移动办公系统，目前标准已支持集成到微信、企业微信、钉钉、飞书和 Welink APP 中。

> 特别说明：微协同第三方集成，标准产品有提供集成到第三方 APP 中的能力，但是实际集成中可能还是会存在部分少量的开发或适配，目前还是主要通过客开方式主导完成。

 * CMP 作为移动基础平台提供移动开发所需组件，业务应用按照 CMP 平台规范，开发出前端 HTML、JS 等文件，再通过 S3 工具编译后，输出生成可以运行的M3 ZIP 包和微协同静态 HTML 资源；
 * M3 ZIP 包运行在 M3 客户端上，微协同静态资源运行在微信、企业微信、钉钉、飞书、Welink 等第三方办公 APP 平台
 * 总结：一次编码，一次编译，多端运行


## 三、应用开发简介

H5 应用开发请参阅：【移动端H5应用基础开发】

Android / iOS 原生应用开发请参阅：【M3原生应用开发】

第三方 H5 集成请参阅：【H5应用集成】


## 四、平台特性

 1. 平台化 CMP平台为应用的集成提供了支撑，真正的把企业应用集成到一个移动平台。

 2. 定制性更强 使用H5语言，可以直接修改应用的代码，即可完成应用定制。

 3. 组件化 所有接口组件化，只需选择所需组件，即可组装出一个应用。

 4. 更简单
    
    * 开发简单：只需要一套代码，不需要分别对iOS、android系统进行开发；
    
    * 维护简单：降低开发、维护成本；
    
    * 使用简单：触手可用，不需要单独安装iOS、android应用；

 5. 更安全
    
    * 提供VPN私有网络环境运行的能力；
    
    * 标准的Https网络传输加密；
    
    * 应用白名单；
    
    * 安全的CMP运行环境，原生应用加固、代码混淆、运行环境安全检测；
    
    * 密码、手势、声纹、账号设备绑定的安全认证；
    
    * 本地数据加密存储；

 6. 自适应强 CMP平台使用Hybrid混合开发模式，采用国际通用标准的Html5语言开发规范，实现一次开发，多平台、多设备、多应用运行：

 * 多平台：可以运行在iOS、Android以及Windows Phone系统的设备；

 * 多设备：自适应布局，可以运行在不同尺寸的设备上，如iPad、iPhone设备。

 * 多应用：可以运行在M3、微信、钉钉以及支持Hybrid模式的应用上。

 7. 更新快 使用H5开发，可以实现快速更新，不需要重新安装iOS、Android应用，也不需要通过漫长的苹果审核周期，让用户无感知的使用新应用。
    编撰人：puwb、admin


快速跳转



 * 概述
   * 一、移动 CMP 平台简介
   * 二、CMP 基础架构
     * 核心层
     * 移动平台 CMP 层
     * 应用层
     * 客户端
   * 三、应用开发简介
   * 四、平台特性



分享链接分享链接

## 28. 移动平台

> 原始路径：`/1267/`  
> 相对路径：`1267/README.md`  
> JS Chunk：`app.844f671c.js`

## 概述

协同移动平台即Collaboration Mobile Platform，它是以协同为核心，移动技术为基础。为企业应用移动化，提供了从开发、调试、测试以及到部署、运行和管控的全生命周期的管理支撑。不仅提供快速集成企业现有的原生、H5移动应用的能力，还为企业应用定制化开发提供了支撑，真正的实现把企业应用放到一个移动平台上。


## 一、移动 CMP 平台简介

CMP 全称 Collaboration Mobile Platform 协同移动平台(也有理解为 Core Mobile Plaform 核心移动平台)。CMP 作为移动基础平台，提供移动开发与运行的基础规范以及基础组件。

CMP 也是跨平台前端框架。基于 CMP 平台开发的协同应用，均可以运行在 M3 APP、微信微协同、企业微信微协同、钉钉、飞书、Welink或第三方 APP 中。同时 CMP 平台也提供了第三方 H5 应用集成到 M3 APP 中的能力。按照 CMP 提供的 H5 标准集成规范，集成的 H5 APP 均可以正常运行在 M3 APP 中。

同时，CMP 平台也提供了很多基础 API，如：拍照、文件、定位、相册等本地原生功能 API，缓存、路由、类加载、AJAX等前端基础能力，并且还提供了丰富的 UI 组件。

> CMP API 文档请查阅：https://open.seeyoncloud.com/cmpdev


## 二、CMP 基础架构

CMP 架构是基于移动原生与 H5 混合模式开发。整体总共分为4个部分：




## 核心层

核心层主要是对 Android、iOS、Harmony(鸿蒙) 系统的基础能力进行规范统一的抽象封装如：网络请求、本地文件读写等。也是移动端运行环境的基础。M3 APP 的原生应用部分的开发也是基于此层开发。


## 移动平台 CMP 层

主要通过原生程序结合 H5 混合方式开发对上层提供统一的基础 API，并且在移动平台层将第三方集成和跨平台的能力进行了封装，并且提供了统一的标准与开发规范。保证了上层“应用层”开发过程中以及后续程序运行中可以无需过多的关注平台与环境问题，而更多的关注业务的问题。

Cordova 是一套开源移动开发框架，隶属于 Apache 开源项目，通过它，开发者可以用标准WEB技术：HTML5、CSS3、JavaScript，来开发跨平台 App。

Cordova 也是我们 CMP 平台 H5 与原生程序间相互调用通讯的中间件。

Cordova 目前支持的平台有：Android、Blackberry 10、iOS、OS X、Ubuntu、Windows、WP8。


## 应用层

基于 CMP 平台提供的标准规范与 API 开发出的各场景可独立运行的应用模块。通过 CMP 的规范完成开发，并使用 S3 工具编译构建后生成 M3 APP 可运行的 ZIP 与微协同可运行的 HTML 静态资源。因此能做到一次编写构建，多端运行。


## 客户端

此层分两部分：

第一部分：M3 APP（V5-A8\A6\G6 移动办公/移动政务/政务督办APP），由致远自己研发的可运行与 Android、iOS、Harmony 系统的独立 APP。M3 中所运行的应用全部基于 H5 完成开发。并通过 S3 工具编译生成可运行与 M3 中的 ZIP 包。

第二部分：微协同。通过 H5 方式提供可集成到第三方系统的致远移动办公系统，目前标准已支持集成到微信、企业微信、钉钉、飞书和 Welink APP 中。

> 特别说明：微协同第三方集成，标准产品有提供集成到第三方 APP 中的能力，但是实际集成中可能还是会存在部分少量的开发或适配，目前还是主要通过客开方式主导完成。

 * CMP 作为移动基础平台提供移动开发所需组件，业务应用按照 CMP 平台规范，开发出前端 HTML、JS 等文件，再通过 S3 工具编译后，输出生成可以运行的M3 ZIP 包和微协同静态 HTML 资源；
 * M3 ZIP 包运行在 M3 客户端上，微协同静态资源运行在微信、企业微信、钉钉、飞书、Welink 等第三方办公 APP 平台
 * 总结：一次编码，一次编译，多端运行


## 三、应用开发简介

H5 应用开发请参阅：【移动端H5应用基础开发】

Android / iOS 原生应用开发请参阅：【M3原生应用开发】

第三方 H5 集成请参阅：【H5应用集成】


## 四、平台特性

 1. 平台化 CMP平台为应用的集成提供了支撑，真正的把企业应用集成到一个移动平台。

 2. 定制性更强 使用H5语言，可以直接修改应用的代码，即可完成应用定制。

 3. 组件化 所有接口组件化，只需选择所需组件，即可组装出一个应用。

 4. 更简单
    
    * 开发简单：只需要一套代码，不需要分别对iOS、android系统进行开发；
    
    * 维护简单：降低开发、维护成本；
    
    * 使用简单：触手可用，不需要单独安装iOS、android应用；

 5. 更安全
    
    * 提供VPN私有网络环境运行的能力；
    
    * 标准的Https网络传输加密；
    
    * 应用白名单；
    
    * 安全的CMP运行环境，原生应用加固、代码混淆、运行环境安全检测；
    
    * 密码、手势、声纹、账号设备绑定的安全认证；
    
    * 本地数据加密存储；

 6. 自适应强 CMP平台使用Hybrid混合开发模式，采用国际通用标准的Html5语言开发规范，实现一次开发，多平台、多设备、多应用运行：

 * 多平台：可以运行在iOS、Android以及Windows Phone系统的设备；

 * 多设备：自适应布局，可以运行在不同尺寸的设备上，如iPad、iPhone设备。

 * 多应用：可以运行在M3、微信、钉钉以及支持Hybrid模式的应用上。

 7. 更新快 使用H5开发，可以实现快速更新，不需要重新安装iOS、Android应用，也不需要通过漫长的苹果审核周期，让用户无感知的使用新应用。
    编撰人：puwb、admin


快速跳转



 * 概述
   * 一、移动 CMP 平台简介
   * 二、CMP 基础架构
     * 核心层
     * 移动平台 CMP 层
     * 应用层
     * 客户端
   * 三、应用开发简介
   * 四、平台特性



分享链接分享链接

## 29. 常见客户问题

> 原始路径：`/1268/`  
> 相对路径：`1268/README.md`  
> JS Chunk：`app.844f671c.js`

正在建设中…

编撰人：puwb、admin、daiky




快速跳转







分享链接分享链接

## 30. M3常见问题

> 原始路径：`/1268/1316.html`  
> 相对路径：`1268/1316.md`  
> JS Chunk：`app.844f671c.js`

## M3常见问题

问题：开发调试需要，如何获取M3的Debug版？

回复：M3开发Debug版下载地址改为：https://m3test.seeyon.com 扫码后选择开发测试版本链接。该网址可能涉及限制方案，如外部客户需要，请联系致远区域技术支持（通过VPN访问下载后提供）。

问题：客户等保需求，需要提供M3 APP安装包，包括IOS的ipa和Android的apk？

回复：Android的apk包从https://m3.seeyon.com 官网直接下载。

IOS的ipa包（客户可能没有下载通路）联系致远技术支持从ctp-studio仓库获取http://gitlab.kk.seeyon.com/release/m3apppack/-/tree/master/%E6%A0%87%E5%87%86%E6%9C%AA%E5%8A%A0%E5%9B%BA%E5%8C%85/IOS

问题：客户需要做APP的沙箱封装，需要提供M3未加固安装包？

回复：未加固的Android的apk包和IOS的ipa包，每次M3发版都会上传至CTP-studio，后续区域申请权限自取提供给客户：http://gitlab.kk.seeyon.com/release/m3apppack

编撰人：puwb、het




快速跳转



 * M3常见问题



分享链接分享链接

## 31. 微协同私有化部署常见问题

> 原始路径：`/1268/1317/1097.html`  
> 相对路径：`1268/1317/1097.md`  
> JS Chunk：`app.844f671c.js`

## 微协同私有化部署常见问题


## 企业微信从工作台可以进入微协同，但从聊天窗口进入时提示“redirect_uri需使用应用可信域名

在企业微信开放平台中点开自建应用-开发者接口-网页授权以及JS-SDK- 可信任域名配置上微协同服务器域名地址(如果有端口号，带端口号)


## 自建应用配置了首页地址，在企业微信工作台入口中可以正常穿透，通过微协同窗口消息列表底部菜单微协同穿透失败




## 企业微信可以正常穿透，但是无法收到消息

检查是否修改过域名，以及在微协同服务器检查wx_memeber表的coll_sit_url字段地址是否为配置好的OA服务器对外域名，若修改过域名，则通过该地址修改OA地址http://weixin.seeyon.com/sync/index(域名替换成独立部署微协同服务器地址)

微协同部署后无法收到消息，微协同服务器logs_wx/wx.log报警告日志,则修改nginx配置，不拦截header里面带下划线的参数 https://blog.csdn.net/loongshawn/article/details/78199977

编撰人：het、tanghu




快速跳转



 * 微协同私有化部署常见问题
   * 企业微信从工作台可以进入微协同，但从聊天窗口进入时提示“redirect_uri需使用应用可信域名
   * 自建应用配置了首页地址，在企业微信工作台入口中可以正常穿透，通过微协同窗口消息列表底部菜单微协同穿透失败
   * 企业微信可以正常穿透，但是无法收到消息



分享链接分享链接

## 32. 微协同客户问题自检和上报要求

> 原始路径：`/1268/1317/1106.html`  
> 相对路径：`1268/1317/1106.md`  
> JS Chunk：`app.844f671c.js`

## 微协同客户问题自检和上报要求

注：提前准备基本信息是问题上报人必备职责，让研发再去采集信息会造成大量的资源浪费，请遵守规则！上报微协同问题，请下载附件中的excel表，填写完整的内容，附加到BUG单中《微协同问题上报》

----------------------------------------


## 需提供的基础信息

问题                答案                                备注
微协同是否私有化部署                                          
OA是否集群                                              
OA对外域名                                              
问题是偶发还是必现                                           
复现问题的第三方平台        企业微信（企业号）、钉钉、welink、飞书、服务号（公众号）   
可供开发绑定的OA测试账号                                       
可供开发绑定的OA测试账号密码                                     


## 特定类型问题还需额外提供这些信息

## 【找不到该账号绑定的OA用户】



应用     应用信息     登录名        截图
企业微信   corpId   问题账号的登录名   没有登录名需提供报错截图
服务号    OA对外域名   问题账号的登录名   没有登录名需提供报错截图

## 【消息接收不到】

问题            答案   备注
该消息PC端能否接收到        
问题偶发还是必然复现         
是否更换了对外域名          如果更换了对外域名需要提供corpId、旧Url和新Url

## 【消息接收重复】

问题           答案   备注
OA是否有测试环境         
问题偶发还是必然复现        

编撰人：het、tanghu


快速跳转



 * 微协同客户问题自检和上报要求
   * 需提供的基础信息
   * 特定类型问题还需额外提供这些信息
     * 【找不到该账号绑定的OA用户】
     * 【消息接收不到】
     * 【消息接收重复】



分享链接分享链接

## 33. 企业微信集成微协同常见问题排查文档

> 原始路径：`/1268/1317/1108.html`  
> 相对路径：`1268/1317/1108.md`  
> JS Chunk：`app.844f671c.js`

## 企业微信集成微协同常见问题排查文档


## 一、网络问题

## 1、OA后台-微协同管理平台-微协同基础设置，环境校验失败

该配置主要是检查OA环境和微协同环境的互通性，使用微协同前，必须保证此项配置必须通过。微协同是在外网的环境，很多客户OA需要在内网中使用。有以下方法可提供排查： 1、OA环境必须要外网可以访问，可使用代理服务器实现； 2、网络防火墙有限制，可以配置微协同出口IP到白名单，微协同服务器出口ip:59.110.227.61； 3、OA服务器必须要能够访问微协同服务器； 4、如果是私有化部署微协同，该规则也适用，并且微协同也需要和外网互相访问； 5、私有化集成企业微信的话，不放开外网，可以将微协同和企业微信都私有化部署，所有都在内网中。

## 2、微协同基础设置校验成功，消息设置按钮已打开，消息接收不到

该问题可以先从OA的日志中排查： 1、先发送一条自由协同的消息； 2、查看OA服务ApacheJetspeed\logs_sy目录下的ctp.log文件； 3、通过模糊搜索“weixin”信息，查看日志文件中是否有对应的报错信息打印； 4、常见报错为“java.net.UnknownHostException:weixin.seeyon.com”； 5、在OA服务器上多次ping weixin.seeyon.com该域名，不同地区会返回不同ip地址，请以实时测试返回的ip地址为准； 6、配置host文件域名解析即可。

## 3、登录微协同提示“协同应用服务或网络异常!外网访问不到 ,请检查外网配置!”

该问题常见于1.1项，微协同基础配环境校验失败，如果环境校验成功的话，一般是绑定的时候信息填写有误（绑定只是建立企业微信和OA的人员关联关系，并非真实的登录），可以通过

## 4、登录微协同提示“微协同配置有误，请待管理员调整!”

该问题常见于OA域名解析后存在多个IP的情况，有些IP可以正常访问，有些IP不行。原因为客户网管会屏蔽某些IP的访问，如果遇到该情况，可以ping一下OA的域名，将返回的IP和客户网管确认下。

## 5、PC端登录微协同（8.1SP1版本及其以上才支持）提示“Oauth2 By Code 返回空”

该问题常见于PC端登录微协同后，还未打开默认浏览器时出现白屏（还未加载完），然后点击了刷新按钮。原因为点击应用后会通过企业微信进行oauth2认证，认证完毕后企业微信会返回一个code值（code5分钟失效，并且只能使用一次），如果点击了刷新，相当于使用第一次返回的code再次请求了，使用了两次 就会报这个错，因为微协同属于集成模块，很多东西和第三方集成，遇到该情况后，叉掉重新点击应用即可。低于8.1SP1版本不处理，版本都不支持打开。

## 6、登录微协同提示“绑定失败，您输入的协同访问地址有误!”

该问题常见于客户OA网络防火墙对微协同服务访问有限制，可参考1.1项，增加白名单或放开限制。此问题需要先由客户网管排查网络方面是否有什么限制策略。

## 7、登录微协同成功后提示“无法访问此网页!”

该问题常见于私有化部署微协同，OA环境只是放开了微协同的访问，但是没放开外网的访问。可以参考1.1项，放开外网访问策略。


## 二、配置问题

## 1、新安装微协同应用后消息接收不到

该问题常见于新安装微协同应用后，测试消息却接收不到的情况。由于OA默认设置协同在线时不发送集成APP通知，因此一般情况下为集成微协同的客户也不会在意此配置项，如果集成了微协同，可将该按钮打开。

## 2、微协同登陆提示“User not found”或“找不到该帐号绑定的OA用户”等相关信息

该问题常见于OA人员被删除后又新建，或者是离职后又入职的情况，原因为客户OA数据库中org_member表中存在重复的人员数据，但是id不同。而微协同数据库中所存的绑定关系中xt_user_id为已经未使用的账号信息。则当前人员的真实id和xt_user_id不匹配所导致的，一方面由于一些历史代码缺陷原因所造成，一方面为客户OA后台未开启监听同步按钮导致。后续操作，若OA人员有删除/停用操作时，如果没有开启监听同步按钮，则需要手动为该人员解绑微协同账号，避免出现该情况。目前的方式先上报bug进行处理，后续微协同代码优化直接处理。

## 3、pc端访问微协同提示NeedLess check login failed,AccessForbidden

该问题常见于OA版本为8.1SP2及其以上出现，为该版本的通用问题。若出现了该问题，可在官网上查到补丁包打上去，或者是打10月月度修复包处理。

## 4、客户修改OA访问地址（域名或IP地址）

该问题主要是OA修改了访问地址后，登录微协同会出现一系列的报错情况，如“协同应用服务或网络异常”等等网络方面的异常提示，目前的方式先上报bug进行处理，后续微协同提供页面，由客户自行修改。

## 5、用户修改OA访问地址（域名或IP地址），以前的消息无法穿透

该问题常见于客户修改了OA地址之后，以前的消息会出现无法穿透的情况。由于消息穿透的OA地址是固定写死实现的，因此会出现该问题，无需解决。

## 6、企业微信同步组织架构的人员同步失败提示：“获取Token失败”

该问题常见于同步组织架构时出现该提示信息，原因为客户企业微信未将通讯录授权给致远云平台。但是请注意，授权给致远云平台后，其他应用将无法获取到通讯录权限，如果客户有其他应用使用通讯录权限，则需要做取舍。授权方法为： 1、登陆企业微信后台，关闭通讯录接口同步。 2、授权给致远平台，通讯录授权：https://weixin.seeyon.com/account/indexaddress 3、可以参考FAQ文档：微协同无法免绑定

## 7、微协同提示：redirect_uri需使用应用可信域名

该问题常见于私有化部署微协同后出现该情况，需要保证以下几点： 1、微协同部署包-sysinfo.properties文件配置wx_url参数项的值为微协同对外地址； 2、企业微信后台可信任域名，已完成OAuth2.0网页授权功能的认证回调。该域名的配置地址为微协同对外地址； 3、OA后台-微协同管理平台-微协同基础设置微协同服务器地址为微协同对外地址。 4、微协同对外地址全部保持一致。 5、可以参考FAQ文档：企业微信集微协同提示：redirect_uri需使用应用可信域名

## 8、微协同打开后弹出提示空白框，没有任何文字或乱码描述

该问题常见于8.1SP2版本使用免绑定功能的客户，开启免绑定后登录微协同出现空白提示框，无任何描述信息。排查方法为： 1、先确定是否是首次安装微协同应用，如果是首次安装微协同应用，则先关闭免绑定，并且保证微协同基础配置确定后，能够设置成功；然后随便一位同事手工绑定微协同后，再开启免绑定功能。若非首次安装，则不用在意； 2、登录企业微信后台管理-管理工具-通讯录同步，查看通讯录是否授权给致远云平台，如果没有授权，则无法使用免绑定的功能； 3、可以参考FAQ文档：微协同无法免绑定

## 9、微协同解绑失效，PC端登录微协同提示“未认证通过”，企业微信可以正常穿透但是无法收到消息等等

该问题常见于nginx后出现该情况，可能还有其他情况，但是排查思路通用： 1、首先查看微协同数据库rest_account表，看Mark字段信息是否为空； 2、如果为空的话，一般情况下都是客户使用了nginx做代理； 3、需要修改下nginx的配置，增加不拦截header里面带下划线的参数的配置； 4、仅将underscores_in_headers on;配置信息加到http块中去即可； 5、可参考链接：https://blog.csdn.net/loongshawn/article/details/78199977

## 10、微协同绑定时提示“微协同绑定失败，内部协同版本过低”

该问题常见于微协同集成配置错误的情况，排查点如下： 1、微协同基础配置是否正确，网络校验能否通过； 2、人员绑定信息是否正确； 3、是否修改了OA地址；

编撰人：het、tanghu




快速跳转



 * 企业微信集成微协同常见问题排查文档
   * 一、网络问题
     * 1、OA后台-微协同管理平台-微协同基础设置，环境校验失败
     * 2、微协同基础设置校验成功，消息设置按钮已打开，消息接收不到
     * 3、登录微协同提示“协同应用服务或网络异常!外网访问不到 ,请检查外网配置!”
     * 4、登录微协同提示“微协同配置有误，请待管理员调整!”
     * 5、PC端登录微协同（8.1SP1版本及其以上才支持）提示“Oauth2 By Code 返回空”
     * 6、登录微协同提示“绑定失败，您输入的协同访问地址有误!”
     * 7、登录微协同成功后提示“无法访问此网页!”
   * 二、配置问题
     * 1、新安装微协同应用后消息接收不到
     * 2、微协同登陆提示“User not found”或“找不到该帐号绑定的OA用户”等相关信息
     * 3、pc端访问微协同提示NeedLess check login failed,AccessForbidden
     * 4、客户修改OA访问地址（域名或IP地址）
     * 5、用户修改OA访问地址（域名或IP地址），以前的消息无法穿透
     * 6、企业微信同步组织架构的人员同步失败提示：“获取Token失败”
     * 7、微协同提示：redirect_uri需使用应用可信域名
     * 8、微协同打开后弹出提示空白框，没有任何文字或乱码描述
     * 9、微协同解绑失效，PC端登录微协同提示“未认证通过”，企业微信可以正常穿透但是无法收到消息等等
     * 10、微协同绑定时提示“微协同绑定失败，内部协同版本过低”



分享链接分享链接

## 34. 微协同常见问题排查

> 原始路径：`/1268/1317/1109.html`  
> 相对路径：`1268/1317/1109.md`  
> JS Chunk：`app.844f671c.js`

## 微协同常见问题排查


## 消息问题


## 一、收不到消息

## 1.排查是否OA后台配置有问题造成接收不到消息

OA近期是否更改对外域名？

若更改对外域名请判断是否按照此修改OA对外域名文档进行修改

集团管理员是否关闭了PC端在线发送消息

具体配置见下图 v8.1-飞书消息-PC端在线发送消息 配置见下图

仅某类消息（非第三方消息）接收不到，或某单位、某员工收不到消息

此时分别检查集团、单位、个人的消息配置集团 集团配置位置如图 注意左下角配置项：集团消息配置是否能更改单位消息配置 单位配置位置如图 注意左下角配置项：是否允许个人单独进行消息配置 个人配置位置如图 这三个配置的优先级为：个人>单位>集团

## 2.排查是否OA端运维配置有问题造成接收不到消息

OA服务器位于内网，是否配置了反向代理？

配置了反向代理，检查http中是否配置允许带下划线的属性

近期是否因为护网行动等原因关闭服务器网络端口？

重点检查443端口、80端口

## 3.排查是否第三方应用后台配置有问题造成接收不到消息

检查钉钉|飞书应用的IP白名单配置

去掉IP白名单的填写

企业微信及公众号检查是否开启了消息免打扰




## 二、消息重复


## OA是否有测试环境？

若测试环境直接复制的正式环境数据库，停用测试环境的微协同


## 部分人员收到重复消息？

上报bug单，研发处理


## 同步问题


## 一、组织架构同步失败

## partyId不符合树形结构

上报bug单，有补丁包

## 已达企业人数上线

第三方组织架构人员扩容

## 其他问题

上报bug单，研发排查


## 二、组织监听同步失败

## 部门名称修改失败

不可修改最顶层名称

## 人员离职、停用、删除人员未同步到第三方

有同步失败日志记录的先排查失败记录，失败记录未明确记载或记录了原因但是不知道怎么处理的 上报bug单，研发排查

## OA后台修改人员信息未同步到第三方

手机号、邮箱在用户进入企业微信后不可再修改，此时请保持OA中手机号与邮箱与企业微信的一致，若不一致会导致其他信息修改同步也失效 有同步失败日志记录的先排查失败记录，失败记录未明确记载或记录了原因但是不知道怎么处理的 上报bug单，研发排查

## OA后台新增人员未同步到第三方

有同步失败日志记录的先排查失败记录 失败记录未明确记载或记录了原因但是不知道怎么处理的 上报bug单，研发排查


## 登录问题

> 企业微信绑定提示非法参数，请重新绑定

非法参数是企业微信那边没有识别到人员信息导致的，清理微信缓存或退出微信，重新登录

> 登录后会自动掉线

多为OA服务器缓存有问题,检查服务器内存、磁盘占用情况 上报bug单，研发排查

> 登陆后提示userId not found

企业微信 & 服务号 & welink & 公有云钉钉 截图上报bug单，研发处理 飞书 & 私有云钉钉 见链接

> 钉钉点击微协同应用提示：无权查看此页面

根据此链接内容重新检查配置，应用的IP白名单不要填写

> 钉钉点击微协同应用报错

根据此链接内容重新检查配置，应用的IP白名单不要填写


## 企业微信问题

> 企业微信绑定菜单后在微信的企业公众号中打开菜单后是聊天窗口，未正常穿透到OA

错误界面如下

调整对应配置：企业微信开放平台打开对应应用，应用主页选择修改，在修改界面勾选在微信插件中始终进入主页

> PC端企业微信底导航菜单穿透空白或者提示 “PC端暂不支持移动端的应用”

 1. 穿透空白的检查配置应用的连接是否正确。
 2. PC端暂不支持移动端的应用 的，8.1SP1 之前的版本不支持 PC端企业微信底导航穿透。
 3. 8.1SP1版本 PC端企业微信不支持 底导航设置 “全部应用PC” 菜单，如果设置了，可以出代码补丁包来屏蔽该菜单。

编撰人：het、tanghu


快速跳转



 * 微协同常见问题排查
   * 消息问题
     * 一、收不到消息
       * 1.排查是否OA后台配置有问题造成接收不到消息
       * 2.排查是否OA端运维配置有问题造成接收不到消息
       * 3.排查是否第三方应用后台配置有问题造成接收不到消息
   * 二、消息重复
     * OA是否有测试环境？
     * 部分人员收到重复消息？
   * 同步问题
     * 一、组织架构同步失败
       * partyId不符合树形结构
       * 已达企业人数上线
       * 其他问题
     * 二、组织监听同步失败
       * 部门名称修改失败
       * 人员离职、停用、删除人员未同步到第三方
       * OA后台修改人员信息未同步到第三方
       * OA后台新增人员未同步到第三方
   * 登录问题
   * 企业微信问题



分享链接分享链接

## 35. 同步机制和常见问题

> 原始路径：`/1268/1317/1110.html`  
> 相对路径：`1268/1317/1110.md`  
> JS Chunk：`app.844f671c.js`

## 同步机制和常见问题


## 同步机制


## 企业微信：

 1. 不是双向，只能从OA同步人员部门到企业微信，不能从企业微信同步人员部门到OA。
 2. 同步组织架构会将企业微信通讯录已有的组织架构删除并将人员全部挪动到临时部门后根据OA的组织架构在企业微信通讯录创建组织架构，人员企业微信使用的手机号必须与OA组织架构的手机号一致才会根据OA组织架构人员部门进行调整人员部门，最终的组织架构与OA保持一致
 3. 需要开启组织架构监听同步新增人员才会同步到企业微信通讯录，此逻辑成功的前提是需要进行组织架构同步（监听同步涉及到部门的增删改和人员的增删改操作）。
 4. 人员同步成功的前提条件，一是人员的手机号或者邮箱不能为空，二是人员所在部门是OA同步到企业微信的部门

## 备注：企业微信同步逻辑已经修改，待上线之后更新


## 钉钉/飞书：

 1. 不是双向，只能从OA同步人员部门到钉钉/飞书，不能从钉钉/飞书同步人员部门到OA。
 2. 同步组织架构不会删除钉钉/飞书原有的组织架构，会在钉钉/飞书原有的组织架构上新建没有的部门，人员已存在钉钉/飞书通讯录中则会将人员更新到OA对应的部门，必须人员在OA的手机号与钉钉/飞书使用的手机号保持一致。
 3. 需要开启组织架构监听同步新增人员才会同步到钉钉/飞书通讯录，此逻辑成功的前提是需要进行组织架构同步（监听同步涉及到部门的增删改和人员的增删改操作）。
 4. 人员同步成功的前提条件，一是人员的手机号或者邮箱不能为空，二是人员所在部门是OA同步到钉钉/飞书的部门。


## WeLink：

 1. 不是双向，只能从OA同步人员部门到welink，不能从welink同步人员部门到OA。
 2. 同步组织架构不会删除welink原有的组织架构，会在welink原有的组织架构上新建没有的部门，人员已存在welink通讯录中则不会将人员更新到对应的部门。
 3. 需要开启组织架构监听同步新增人员才会同步到welink通讯录，此逻辑成功的前提是需要进行组织架构同步（监听同步涉及到部门的增删改和人员的增删改操作）。
 4. 人员同步成功的前提条件，一是人员的手机号或者邮箱不能为空，二是人员所在部门是OA同步到welink书的部门。


## 常见问题

> Q: 使用致远微协同有什么条件？

A:

 1. 您的“致远协同办公系统”的产品版本为V5.1SP1（A8、A6、G6...）-2015年3月修复包及以上

 2. 您的“致远协同办公系统”的访问地址(IP)为公网地址

 3. 您已参照《使用配置说明》在“致远协同办公系统”中进行了配置

> Q: 使用致远微协同安全吗？

A:

 1. 致远公司的“致远微协同”服务，仅作为通道将您的消息、列表从您的“致远协同办公系统”传递到微信平台，不会进行留存。而详细内容页面，是直接访问您在本地部署“致远协同办公系统”的页面，所以是安全的

 2. 消息与列表的传递也会通过微信平台进行转发，并且当您使用企业号时，您的组织机构信息会在微信平台留存，不过微信已经在其服务协议中明确说明了对信息保护的原则和措施

 3. 所有的信息传输均采用了AES（高级加密标准）进行加密

> Q: 为什么我在绑定协同账号的时候总是提示失败？

A:

 1. 某些手机在输入用户名、密码的时候，会将第一个字母大写，这样会导致用户名密码校验失败
 2. 您可能没有参照《使用配置说明》，在“致远协同办公系统”的系统管理员中配置REST用户

> Q: 为什么我在绑定成功后，无法收到推送消息？

A:

 1. 为避免打扰，您的协同系统在PC端登录，将不会在微信中收到推送消息

 2. 请检查一下您的协同系统能否访问外网，如果不能访问外网则无法向微信推送消息

 3. 在您的协同系统配置（点击SeeyonConfig或者小地球）中是否配置了internet.site.url和weixin.enable这两个参数

 4. 您可能没有参照《使用配置说明》，在“致远协同办公系统”的配置工具中设置“消息推送链接”

 5. 服务号无法收到消息是因为文本消息是客服消息，必须和服务号对话才能收到消息

> Q: 如果我的协同办公系统在内网，考虑安全问题，不想直接开放外网地址，又想使用微协同怎么办？

A: 您可以使用“反向代理”的方案，在保证相对安全的基础上，来为您的协同系统提供外网访问地址。具体配置方法请下载《微协同反向代理配置文档》（注：此方案仅提供参考，为网络级方案，相关反向代理服务程序均为网络开源程序，与致远产品及服务无关）

> Q: 如果我的企业号不能全部同步V5的人员数据怎么办？

A: 未认证的企业号使用上限为200人，您可以通过认证企业号来提高微信企业号的使用上限。

> Q: 如果使用微协同总是弹出“继续访问”的提示怎么办？

A: 证明您的OA服务器外网地址是ip，ip会被微信认为有安全风险的，建议您将OA的外网地址改为域名。

> Q: 如果访问微协同时出现“非法参数，请重新绑定”的提示怎么办？

A: 由于企业微信/微信未识别到当前人员识别码，退出企业微信账号重新登录或者清除企业微信APP/微信缓存

> Q: 如果钉钉点击微协同提示无权查看此页面的提示怎么办？

A: 请检查钉钉应用的配置手机端地址是否填写错误以及应用权限是否开启

> Q: 如果企业微信不需要绑定就可以进入到OA的情况怎么处理？

A: 只要是OA同步人员到企业微信的就可以不需要进行绑定操作

> Q: 如果pc端消息点进去需要登录这是正常的吗？

A: 正常的，OA做了安全防护的

> Q: 如果在微协同基础配置检测时有错误怎么办？

A: 检查OA是否外网能够访问以及OA服务器防火墙做了那些限制

编撰人：het、tanghu




快速跳转



 * 同步机制和常见问题
   * 同步机制
     * 企业微信：
       * 备注：企业微信同步逻辑已经修改，待上线之后更新
     * 钉钉/飞书：
     * WeLink：
   * 常见问题



分享链接分享链接

## 36. M3

> 原始路径：`/1269/`  
> 相对路径：`1269/README.md`  
> JS Chunk：`app.844f671c.js`

正在建设中…

编撰人：puwb、admin




快速跳转







分享链接分享链接

## 37. Android 开发技术要求

> 原始路径：`/1269/1275/1277.html`  
> 相对路径：`1269/1275/1277.md`  
> JS Chunk：`app.844f671c.js`

## Android 开发技术要求


## 一、开发语言

 1. Java
    
    * 基础语法与面向对象编程：Android开发工程师需要熟练掌握Java的基础语法，包括变量、数据类型、运算符、控制流等。同时，他们还需要深入理解面向对象编程的概念，如类、对象、继承、封装和多态等，以便更好地设计和组织代码。
    
    * Android SDK与API：Java开发者需要熟悉Android SDK和API，能够利用这些工具进行应用的开发。他们应该了解Android的核心组件（如Activity、Service等）以及常用的API（如网络请求、文件操作等），并能够熟练地使用它们来实现业务需求。
    
    * 性能优化与内存管理：Android开发工程师需要具备Java性能优化和内存管理的知识。他们应该了解Java虚拟机（JVM）的工作原理，掌握垃圾回收机制，并能够通过代码优化来减少内存泄漏和提高应用性能。
    
    * 第三方库与框架：随着Android生态的发展，许多优秀的第三方库和框架应运而生。Android开发工程师需要了解并熟悉这些库和框架，如Retrofit、OkHttp、Glide等，以便更好地提高开发效率和软件质量。

 2. Kotlin
    
    * 简洁性与安全性：Kotlin语法简洁明了，减少了冗余代码，提高了代码的可读性和可维护性。同时，Kotlin提供了空安全特性，有效减少了空指针异常的风险。
    
    * 与Java的互操作性：Kotlin与Java具有良好的互操作性，这意味着Kotlin可以调用Java代码，反之亦然。这使得Kotlin能够充分利用现有的Java库和框架，同时也方便与其他Java开发者进行协作。
    
    * 函数式编程特性：Kotlin支持函数式编程，提供了高阶函数、Lambda表达式等特性，使得代码更加灵活和易于扩展。
    
    * Android官方支持：Google官方已经宣布Kotlin为Android开发的首选语言，并在Android Studio中提供了对Kotlin的全面支持。这意味着Kotlin具有稳定的生态和广阔的发展前景。


## 二、Android应用开发能力

 * 熟练掌握Android Studio等开发工具，并能高效地使用其进行应用的开发、调试和测试。

 * 深入理解Android四大组件（Activity、Service、BroadcastReceiver、ContentProvider）的生命周期和原理，能够灵活运用到实际开发中。

 * 精通Android UI/UX设计，包括布局、控件、动画等，能够创建出美观且用户友好的界面。

 * 熟悉Android网络通信机制，包括HTTP、Socket等，能够实现数据的传输和同步。


## 三、性能优化能力

 * 能够针对应用的性能瓶颈进行调优，包括内存管理、电量优化、网络优化等方面。

 * 熟悉Android的性能分析工具，如Systrace、Profiler等，能够定位并解决性能问题。

 * 了解Android多线程编程和并发控制，能够合理设计并发模型，提高应用的响应速度和稳定性。


## 四、系统架构设计能力

 * 能够根据业务需求设计出稳定、高效、可扩展的Android系统架构。

 * 深入理解Android系统的底层原理和实现机制，能够针对具体场景进行定制和优化。

 * 熟练掌握MVC、MVVM等设计模式，能够设计出易于维护和扩展的代码结构。


## 五、跨平台开发能力

 * 了解并掌握至少一种跨平台开发技术，如React Native、Flutter等，能够实现一次编写、多平台运行的应用开发。

 * 理解跨平台开发的原理和最佳实践，能够避免常见的性能和兼容性问题。


## 六、安全

 1. 数据加密与安全性
    
    * 加密技术：工程师需要了解并应用各种加密算法，如AES、RSA等，以保护敏感数据的传输和存储。此外，还应掌握密钥管理和安全存储的机制，确保加密密钥的安全性。
    
    * 安全协议：熟悉并正确使用HTTPS、SSL/TLS等安全协议，以确保网络通信的安全性。

 2. 权限管理与访问控制
    
    * 权限模型：深入理解Android的权限模型，确保应用只获取必要的权限，并正确处理和保护用户数据。
    
    * 运行时权限：熟悉Android 6.0及以上版本引入的运行时权限机制，能够在应用运行时动态地请求和管理权限，提高用户体验和安全性。

 3. 安全编码规范
    
    * 代码安全审计：掌握代码安全审计的方法和技巧，能够识别和修复潜在的安全漏洞，如SQL注入、跨站脚本攻击（XSS）等。
    
    * 安全编码实践：遵循安全编码的最佳实践，如输入验证、错误处理、日志记录等，减少应用被攻击的风险。

 4. 安全框架与组件
    
    * 安全框架：了解并应用业界认可的安全框架和组件，如OWASP（Open Web Application Security Project）提供的安全指南和工具，以增强应用的安全性。
    
    * 组件安全：确保使用的第三方库和组件是安全的，并关注其安全更新和漏洞修复情况。

 5. 应用安全测试与评估
    
    * 安全测试：掌握安全测试的方法和工具，如渗透测试、模糊测试等，能够对应用进行全面的安全评估。
    
    * 漏洞扫描：定期使用自动化工具进行漏洞扫描，及时发现并修复潜在的安全问题。

 6. 安全意识
    
    * 具备高度的安全意识和风险意识，能够识别和应对各种安全威胁。
      编撰人：puwb


快速跳转



 * Android 开发技术要求
   * 一、开发语言
   * 二、Android应用开发能力
   * 三、性能优化能力
   * 四、系统架构设计能力
   * 五、跨平台开发能力
   * 六、安全



分享链接分享链接

## 38. Android开发规范

> 原始路径：`/1269/1275/1278.html`  
> 相对路径：`1269/1275/1278.md`  
> JS Chunk：`app.844f671c.js`

## Android开发规范


## 一、编码风格与格式

 1. 命名规范：
    
    * 变量名、方法名、类名等应遵循Java的命名约定。局部变量和参数使用小驼峰命名法（lowerCamelCase）
      
      > 如：int myVariable。
    
    * 类名使用大驼峰命名法（UpperCamelCase），也称为Pascal命名法，
      
      > 如：public class MyClass。
    
    * 常量名应全部大写，并使用下划线分隔单词
      
      > 如：public static final int MAX_VALUE = 100;。
    
    * 对于资源ID，如layout中的id，应遵循一定的命名模式
      
      > 如：view缩写_模块名称_view的逻辑名称，例如：btn_login_submit。

 2. 代码格式：
    
    * 使用统一的缩进和空格规则。通常，每个缩进级别使用4个空格。
    * 避免一行代码过长，建议每行不超过80个字符。
    * 使用空行来提高代码的可读性。例如，在方法之间、逻辑段之间等使用空行。
    * 注释应清晰明了，说明代码的功能、参数、返回值以及可能的异常情况。

 3. 书写规范：
    
    * 编码方式统一使用UTF-8。
    * 花括号不要单独一行，应和前面的代码或语句在同一行，并用一个空格隔开。
    * 对于逻辑关键字（如if、else、for等）和运算符，与后面的语句或操作数之间应留一个空格。
    * 尽量避免一行声明多个变量，以提高代码的可读性。

 4. 异常处理
    
    * 所有 cache 处理，不允许直接使用 printStackTrace() 打印异常，只能使用日志管理工具 Log.e("TAG", "XXX") 方式打印异常（或自定义日志管理工具输出异常信息）


## 二、资源文件管理

 1. 资源目录结构：
    * res目录下应包含与界面和用户界面相关的所有文件。其中，drawable用于存放图片资源，layout用于存放布局文件，values用于存放各种资源的配置文件（如strings.xml）。
    * 图片资源文件应采用全小写的下划线命名法，如ic_launcher.png。
    * 值资源文件（如strings.xml）中的id命名也应采用全小写的下划线命名法。
 2. 资源引用：
    * 在代码中引用资源时，应使用R类中的静态常量，而不是直接引用资源文件的ID。
    * 避免使用硬编码的资源引用，而应使用@string/my_string、@drawable/my_image等形式。
      编撰人：puwb


快速跳转



 * Android开发规范
   * 一、编码风格与格式
   * 二、资源文件管理



分享链接分享链接

## 39. 步骤 1: 安装Java Development Kit (JDK)

> 原始路径：`/1269/1275/1304.html`  
> 相对路径：`1269/1275/1304.md`  
> JS Chunk：`app.844f671c.js`

## 步骤 1: 安装Java Development Kit (JDK)


## 1.1 下载JDK

Java Development Kit（JDK）是一种允许您编写和运行Java程序的工具集。首先，我们需要从Oracle官方网站下载JDK。您可以访问Oracle JDK下载页面。在该页面，您会看到一系列可供下载的JDK版本，选择适用于Windows的版本并点击下载。


## 1.2 安装JDK

安装JDK非常简单。双击您下载的安装文件，然后按照提示操作。通常情况下，您只需要点击“下一步”直到安装完成。安装完成后，您会收到一个安装成功的消息。


## 1.3 验证安装

为了确保JDK已成功安装，我们需要在命令行中执行一个简单的命令。打开命令提示符（按下Win + R，然后键入cmd并按Enter），在命令行中输入以下命令：

java -version


如果您看到了与您安装的JDK版本对应的信息，那么恭喜您，JDK安装成功！

【例如】：

C:\Users\admin> java -version
java version "1.8.0_201"
Java(TM) SE Runtime Environment (build 1.8.0_201-b09)
Java HotSpot(TM) 64-Bit Server VM (build 25.201-b09, mixed mode)



## 步骤 2: 安装Android Studio


## 2.1 下载Android Studio

Android Studio是Google官方推荐的用于Android应用开发的集成开发环境（IDE）。您可以从Android Studio下载页面下载适用于Windows的安装程序。


## 2.2 运行安装程序

安装Android Studio与安装其他软件一样简单。双击下载的安装程序，然后按照向导进行操作。您将被引导完成安装过程，直到安装完成为止。

> 备注：详细安装步骤请查看Google 官方教程：https://developer.android.com/studio/install, 也可以在互联网各大视频平台搜索”Android Studio 安装教程“进行详细学习


## 步骤 3: 配置Android SDK


## 3.1 启动Android Studio

安装完成后，启动Android Studio。您可能需要一些时间来初始化和设置。


## 3.2 打开SDK Manager

一旦Android Studio启动完毕，您将看到一个欢迎界面。在该界面上，选择 "Configure"（配置）选项，然后选择 "SDK Manager"。

> 注：截图仅供参考，Android Studio 版本不同所见界面会有一定区别，以实际安装版本为准。


## 3.3 安装所需的SDK版本

SDK Manager是一个管理Android开发工具的中心。在这里，您可以选择需要的Android版本和其他工具，然后点击底部的 "Apply" 按钮以开始下载和安装所选的SDK版本。安装完成后，您可以关闭SDK Manager。


## 步骤 4: 配置模拟器或连接设备


## 4.1 启动AVD Manager

在Android Studio中，点击顶部菜单栏中的 "Tools" -> "AVD Manager"。


## 4.2 创建虚拟设备

AVD Manager（Android Virtual Device Manager）是一个用于管理Android模拟器的工具。在AVD Manager中，点击 "Create Virtual Device" 按钮，然后按照向导选择设备类型、系统镜像等，并完成虚拟设备的创建。


## 4.3 连接物理设备

如果您有Android设备，您也可以通过USB连接到计算机。确保您的设备已启用开发人员选项，并在Android Studio中识别到它。


## 步骤 5: 创建新项目


## 5.1 启动Android Studio

如果尚未启动，请启动Android Studio。


## 5.2 创建新项目

在Android Studio中，点击顶部菜单栏中的 "File" -> "New" -> "New Project"。


## 5.3 填写项目信息

按照向导填写项目名称、包名等信息。如果您不确定某些选项的含义，您可以在右侧找到相应的帮助文档。


## 5.4 选择Activity模板

在 "Add an Activity" 阶段，选择一个适合您项目需求的Activity模板，然后点击 "Finish" 完成项目创建。

编撰人：puwb


快速跳转



 * 步骤 1: 安装Java Development Kit (JDK)
   * 1.1 下载JDK
   * 1.2 安装JDK
   * 1.3 验证安装
 * 步骤 2: 安装Android Studio
   * 2.1 下载Android Studio
   * 2.2 运行安装程序
 * 步骤 3: 配置Android SDK
   * 3.1 启动Android Studio
   * 3.2 打开SDK Manager
   * 3.3 安装所需的SDK版本
 * 步骤 4: 配置模拟器或连接设备
   * 4.1 启动AVD Manager
   * 4.2 创建虚拟设备
   * 4.3 连接物理设备
 * 步骤 5: 创建新项目
   * 5.1 启动Android Studio
   * 5.2 创建新项目
   * 5.3 填写项目信息
   * 5.4 选择Activity模板



分享链接分享链接

## 40. 移动办公M3隐私保护协议

> 原始路径：`/1269/1289/1307.html`  
> 相对路径：`1269/1289/1307.md`  
> JS Chunk：`app.844f671c.js`

## 移动办公M3隐私保护协议

隐私协议访问地址：https://m3.seeyon.com/privacy/cn/policy_ch.html

更新时间：2024年4月29日

> 注意：本隐私协议只适用 M3 标准产品，如果客户是客开后的M3，标准产品隐私协议将不再适用。客开后的APP需要客户重新编写客户自己的隐私协议。可参考标准产品的隐私协议进行编写，但不可以直接拷贝复制使用，否则带来任何问题和风险全部由客户自行承担。
> 
> 编撰人：puwb


快速跳转



 * 移动办公M3隐私保护协议



分享链接分享链接

## 41. 应用权限说明

> 原始路径：`/1269/1289/1309.html`  
> 相对路径：`1269/1289/1309.md`  
> JS Chunk：`app.844f671c.js`

## 应用权限说明

应用权限说明访问地址：https://m3.seeyon.com/privacy/cn/permissions_ch.html

更新时间：2024年4月29日

编撰人：puwb




快速跳转



 * 应用权限说明



分享链接分享链接

## 42. 第三方SDK列表

> 原始路径：`/1269/1289/1310.html`  
> 相对路径：`1269/1289/1310.md`  
> JS Chunk：`app.844f671c.js`

## 第三方SDK列表

查看集成的第三方SDK列表：https://m3.seeyon.com/privacy/cn/my-sdk-list_ch.html

更新时间：2024年4月29日

编撰人：puwb




快速跳转



 * 第三方SDK列表



分享链接分享链接

## 43. APP加固

> 原始路径：`/1269/1289/1311.html`  
> 相对路径：`1269/1289/1311.md`  
> JS Chunk：`app.844f671c.js`

## APP加固

> 本文只大致讲解 APP 加固的基本原理和推荐部分第三方加固厂商。致远官方不对外提供任何客开 APP 或第三方 APP 加固服务


## Android APP加固方案

Android APP加固的主要目的是通过一系列技术手段保护APP的代码逻辑和数据安全，防止被逆向分析、篡改、调试和数据泄漏。具体方案包括：

 1. 核心技术：
    
    * 防逆向：通过DEX加密、IVMP、源码混淆等技术对DEX和SO文件进行保护，防止被Apktool、IDA等逆向工具分析。
    * 防篡改：在加固时提取APP内文件的特征值，替换任意文件会导致应用无法运行，防止APP被反编译后植入恶意代码。
    * 防调试：使用多重加密技术防止代码注入，防止JAVA层/C层动态调试、代码注入和HOOK攻击。
    * 数据防泄漏：使用多种加密算法保护本地数据的安全，包括国际通用算法及自主研发的加密算法等。

 2. 主要功能：
    
    * 防逆向：DEX整体加密保护、DEX代码分离保护、DEX混合加密保护等。
    * 防篡改：DEX文件防篡改、SO库文件防篡改等。
    * 防调试：防动态调试、防内存代码注入等。
    * 数据防泄漏：防内存数据读取、防日志泄漏等。

 3. 第三方厂家：
    
    * 梆梆加固：提供Android应用的加固服务，包括DEX加密、资源文件保护等。
    * 360加固：另一家知名的Android加固服务提供商，具有相似的加固功能。
    * ipagurd加固：专注于Android应用的代码保护和反篡改技术。
    * 爱加密：另一家知名的Android加固服务提供商，具有相似的加固功能。
    
    > 当前移动办公M3 APP 标准产品就是采用的爱加密厂家进行的 APP 加固


## iOS APP加固方案

iOS APP加固的主要目标也是保护APP的代码逻辑和数据安全，防止被逆向分析、篡改和调试。具体方案包括：

 1. 保护原理：
    
    * 字符串混淆：对应用程序中使用的字符串进行加密，保证源码被逆向后不能看出字符串的直观含义。
    * 类名、方法名混淆：对应用程序的方法名和方法体进行混淆，降低源码可读性。
    * 程序结构混淆：对应用程序逻辑结构进行打乱混排，进一步降低源码可读性。
    * 反调试、反注入：采用主动保护策略防止调试和注入攻击。

 2. 第三方厂家：
    
    * VirboxProtector：基于虚拟机保护技术，提供iOS应用加固方案，无需启用Bitcode，无需替换Xcode编译器。
    * 其他专业加固公司：市面上还有其他一些专门提供iOS应用加固服务的公司，可以根据具体需求选择。

编撰人：puwb


快速跳转



 * APP加固
   * Android APP加固方案
   * iOS APP加固方案



分享链接分享链接

## 44. 网络安全的要求和解决方案

> 原始路径：`/1269/1289/1312.html`  
> 相对路径：`1269/1289/1312.md`  
> JS Chunk：`app.844f671c.js`

## 网络安全的要求和解决方案


## 一、网络安全要求

 1.  网络设备安全：
     * 选择品质可靠、具有完善安全防护机制的网络设备，如防火墙、入侵检测系统等。
 2.  安全网络拓扑结构：
     * 设计合理的网络拓扑结构，确保网络流量和数据传输的安全可控，减少风险暴露。
 3.  身份认证和访问控制：
     * 引入身份认证和访问控制机制，确保用户身份真实可信，只有经过授权的用户才能访问网络资源。
 4.  数据加密和传输安全：
     * 使用加密技术对敏感数据进行加密处理，确保数据传输过程中的安全性，防止数据泄漏和篡改。
 5.  强密码和账户管理：
     * 要求用户使用强密码，并加强账户管理，定期更换密码，禁止共享账户密码，减少密码被破解的风险。
 6.  安全协议和安全策略：
     * 制定和使用安全协议和安全策略，如使用HTTPS协议替代HTTP协议，限制外部连接，禁止安装未经授权的软件等。
 7.  实时监控和漏洞扫描：
     * 通过实时监控和漏洞扫描工具，及时发现和修补系统漏洞，防止黑客入侵和攻击。
 8.  员工教育和安全意识培养：
     * 提高员工对网络安全的认识和意识，定期进行培训，教育员工如何识别和防范网络安全威胁。
 9.  安全备份和恢复策略：
     * 定期备份关键数据，建立安全的数据备份和恢复策略，以防止数据丢失和被勒索软件攻击。
 10. 升级和修补系统漏洞：
     * 及时安装操作系统和应用程序的升级补丁，修复安全漏洞，提高系统的安全性。


## 二、网络安全解决方案

 1. 加密通信：
    * 采用HTTPS协议对所有网络请求进行加密传输，保护数据在传输过程中的安全。
 2. 使用安全的身份验证方法：
    * 如OAuth 2.0、JWT等，确保用户身份的真实性和访问权限的合法性。
 3. 应用安全加固：
    * 通过代码混淆、DEX加密等技术对APP进行加固，防止被逆向分析和篡改。
 4. 建立防火墙和安全监控体系：
    * 通过设置网络防火墙，防止非法访问和恶意攻击。同时建立安全监控体系，实时监测网络流量和异常行为。
 5. 实施安全审计和风险评估：
    * 定期对网络系统进行安全审计和风险评估，及时发现和修复潜在的安全隐患。
 6. 使用VPN等虚拟专用网络：
    * 对于需要远程访问敏感数据的场景，可以使用VPN等虚拟专用网络来确保数据传输的安全性。
 7. 强化账户安全管理：
    * 实施多因素认证、短信验证、密码复杂度要求等账户安全措施，减少账户被破解的风险。
 8. 建立应急响应机制：
    * 针对可能出现的网络安全事件，制定详细的应急响应计划，并定期组织演练和培训。

总结：网络安全的要求和解决方案需要从多个方面综合考虑，包括网络设备、网络拓扑结构、身份认证、数据加密、密码管理、安全协议、监控扫描、员工教育、备份恢复以及系统升级等多个方面。同时，需要根据具体的应用场景和业务需求，选择合适的网络安全解决方案来确保网络系统的安全稳定运行。

编撰人：puwb




快速跳转



 * 网络安全的要求和解决方案
   * 一、网络安全要求
   * 二、网络安全解决方案



分享链接分享链接

## 45. 源码申请详细步骤

> 原始路径：`/1269/1290/1291.html`  
> 相对路径：`1269/1290/1291.md`  
> JS Chunk：`app.844f671c.js`

## 源码申请详细步骤


## 背景&需求

源码申请用于客户定制化需求，需要申请源码


## 操作步骤


## 只申请源码，不由客开平台托管项目

## 第一步：发起《产品代码申请单》，填写相关信息即可：

该申请单可用于申请所有项目源码






## 由客开平台托管项目

## 第一步：《发起客户端代码推送申请》，填写相关信息即可：

该申请单可用于申请APP源码和APP未加固包，致信端代码以及微协同云服务代码 其他业务代码申请，见《产品代码申请单》申请





## 第二步： 客开托管平台 使用

1.登录后，点击右上角姓名，可以获取git账号密码



2.托管平台可以申请对应业务代码文件并进行修改

3.搜索具体的代码文件

3.构建发布

编撰人：puwb、zoujuan


快速跳转



 * 源码申请详细步骤
   * 背景&需求
   * 操作步骤
     * 只申请源码，不由客开平台托管项目
       * 第一步：发起《产品代码申请单》，填写相关信息即可：
     * 由客开平台托管项目
       * 第一步：《发起客户端代码推送申请》，填写相关信息即可：
       * 第二步： 客开托管平台 使用



分享链接分享链接

## 46. 软著申请的方法及所需资料证明和详细步骤

> 原始路径：`/1269/1290/1293.html`  
> 相对路径：`1269/1290/1293.md`  
> JS Chunk：`app.844f671c.js`

## 软著申请的方法及所需资料证明和详细步骤

> 软著需要以客户的名义自行申请，建议由客户的行政职责部门负责，致远不提供任何第三方软著申请服务。


## 一、资料证明

 1. 软件著作权登记申请表：这是申请软件著作权的基本表格，需要填写相关信息，如软件名称、版本号、开发完成时间、申请人信息等。
 2. 软件的鉴别材料：
    * 源程序：一般交存源程序和文档应提交前、后各连续30页，共60页，不足60页的，应当全部提交。每页不少于50行，最后一页应是开发程序的结束页。
    * 文档：文档应提交前、后各连续30页，不足60页的，应当全部提交。每页不少于30行，有图除外。
    * 例外交存：在特定情况下，可以选择其他例外交存方式，如源程序的前、后各连续的30页，其中的机密部分用黑色宽斜线覆盖等。
 3. 申请人身份证明和相关的证明文件：
    * 自然人、法人或其他组织的身份证明文件。
    * 如果涉及代理，需要提交代理人的身份证明文件及代理协议。
    * 如果软件是合作开发或委托开发，需要提交相应的合作开发合同或委托开发合同。
    * 如果软件涉及权利转移，如继承、转让等，需要提交相应的权利转移证明文件。


## 二、详细步骤

 1. 账号注册与实名认证：
    * 打开中国版权保护中心官网（https://www.ccopyright.com.cn/），注册账号。
    * 根据要求填写账户信息，并进行实名认证。实名认证需要提交身份证、公司营业执照等证明文件。
    * 实名认证通过后，即可登录系统。
 2. 填报提交：
    * 在系统中选择“计算机软件著作权相关登记”业务。
    * 填写软件著作权登记申请表，包括软件的基本信息、申请人信息等。
    * 上传软件的鉴别材料，包括源程序、文档等。
    * 上传相关的证明文件，如身份证明、合作开发合同等。
 3. 登记机构受理：
    * 中国版权保护中心在收到申请后，会进行初步审查，确认申请是否符合受理条件。
    * 如果申请符合受理条件，会向申请人发出受理通知书及缴费票据。
 4. 登记机构审查：
    * 在受理后，中国版权保护中心会对申请进行实质审查，包括软件的独创性、申请材料的完整性等。
    * 如果审查通过，会核发计算机软件著作权登记证。
 5. 取得登记证书：
    * 申请人持受理通知书原件到版权保护中心领取证书。
      编撰人：puwb、zoujuan


快速跳转



 * 软著申请的方法及所需资料证明和详细步骤
   * 一、资料证明
   * 二、详细步骤



分享链接分享链接

## 47. APP备案流程

> 原始路径：`/1269/1290/1294.html`  
> 相对路径：`1269/1290/1294.md`  
> JS Chunk：`app.844f671c.js`

## APP备案流程


## 背景

依据《互联网信息服务管理办法》(国务院令第292号)规定，电信主管部门对从事互联网信息服务的网站开展备案核准工作(即ICP备案)。根据工业和信息化部2023年7月21日发布的《工业和信息化部关于开展移动互联网应用程序备案工作的通知》与2023年8月8日发布的《《工业和信息化部关于开展移动互联网应用程序备案工作的通知》解读》，原则上要求所有APP、小程序、快应用在2023年9月1日之后需要完成ICP备案后方可进行上架。对于已上架的APP、小程序、快应用，需要在2024年3月31日之前完成ICP备案，否则会对其进行下架。


## 操作步骤


## 一、实名认证和准备APP相关资料

 1. 备案主体信息
    * 申办单位情况：单位名称，单位性质，证件类型，证件号码，详细地址
    * APP主体负责人基础情况：姓名、有效证件号码、有效证件起止日期、联系号码、应急联系电话、电子邮箱
    * ICP负责人基本情况：姓名、有效证件号码、有效证件起止日期、联系号码、应急联系电话、电子邮箱
 2. 应用运行平台：
    * 安卓：APP包名、公钥+MD5、域名
    * iOS：Bundle ID、公钥+MD5、域名
    * 其他，是否提供SDK服务，是否提供SDK，功能类型，服务商名称
 3. APP基础信息
    * APP名称，APP图标，APP备案/许可证号，前置审批项，前置审批号，前置审批文件，应用服务类型，APP服务类目，语种
 4. APP接入信息
    * APP接入信息
    * 接入服务器单位名称
    * 接入方式和服务器放置地
    * IP地址列表
 5. 其他
    * 接入信息App后台服务域名
    * 云服务器
    * 前置审批/专项审批
    * 补充材料：根据规则提供包括但不限于授权书、党建证明、居住证、情况说明、承诺书等
    * App负责人核验现场拍摄照片电子件
    * 互联网信息服务承诺书
    * App备案真实性核验单

开发者需要在应用商店或应用发布平台上进行应用信息登记，填写应用名称、应用版本号、应用描述、应用类型、所属类别、收费方式、开发机构、联系方式等信息。这些信息将会被展示在应用商店或应用发布平台上，供用户查看

## 二、前置审批材料

从事新闻、出版、教育、影视、宗教等APP互联网信息服务的主办者，在履行备案手续时，还应向其住所所在地省级通信管理局提交相关主管部门审核同意的文件。从事上述需须经有关主管部门审核同意的互联网信息服务的APP主办者，无论是否具有“经营性”，均应当提供业务对应的前置审批文件。

 1. 广播电影电视节目类，需提供《信息网络传播视听节目许可证》
 2. 出版类，需提供《互联网出版许可证》
 3. 药品和医疗器械类，需提供《互联网药品信息服务资格证书》或《互联网药品信息服务资格证书》
 4. 新闻类，需提供《互联网新闻信息服务许可证》
 5. 其他的还有诸如：金融类、游戏类、教育培训类、宗教类、文化类等见截图：

## 三、APP服务备案

 1. 云服务器 华为云备案网址：华为云备案_域名ICP备案服务_个人网站和企业网站备案服务-华为云 腾讯云备案网址：腾讯云备案_个人域名备案_网站备案_企业备案-腾讯云 阿里云备案网址：阿里云登录 - 欢迎登录阿里云，安全稳定的云计算服务平台 火山云（抖音）备案网址：备案中心-火山引擎 西部数码：ICP网站备案管理系统 v5.0

 2. 非云服务器 联系通信供应商，及固定IP提供商，他们有专有的备案网址： 电信自助备案系统：中国电信网站备案自助管理系统

## 四、备案流程

 1. 主办者申请：通过网络接入服务提供者、小程序平台、快应用平台的企业侧备案系统向主办者所在省级通信管理局提交申请。
 2. 材料核验：网络接入服务提供者、小程序平台、快应用平台对主办者提交的申请材料进行核验。
 3. 主办者确认：核验通过后，向主办者发送短信验证。主办者根据短信提示，登录https://beian.miit.gov.cn/ 进行确认。
 4. 材料审核：主办者确认后，省级通信管理局进行审核。
 5. 结果下发：审核通过后，通过短信、邮件将APP备案号告知主办者。主办者也可通过https://beian.miit.gov.cn/ 查看备案结果。
 6. 结果公示：工业和信息化部通过 https://beian.miit.gov.cn/ 对备案结果进行公示。

## 五、注意事项

 1. 凡是能够安装运行在不同操作系统平台的应用程序，包括Android、iOS等以及小程序、快应用等，都需要按照相关规定完成App备案。
 2. 网站备案号和App备案号是不同的，每个都是必须的。
 3. 如果App在不同平台上使用相同的名称，只需要备案一次，获得一个备案号。如果使用不同的名称，需要分别备案，将获得多个备案号。
 4. APP备案中填写的域名，表示APP启动运行时，连接后台服务器所使用的具体域名。

编撰人：puwb、zoujuan


快速跳转



 * APP备案流程
   * 背景
   * 操作步骤
     * 一、实名认证和准备APP相关资料
       * 二、前置审批材料
       * 三、APP服务备案
       * 四、备案流程
       * 五、注意事项



分享链接分享链接

## 48. iOS APP发布上架详细流程和操作步骤

> 原始路径：`/1269/1290/1296/1821.html`  
> 相对路径：`1269/1290/1296/1821.md`  
> JS Chunk：`app.844f671c.js`

## iOS APP发布上架详细流程和操作步骤


## 一、前期准备

 1. 注册苹果开发者账号：
    
    * 开发者需要在苹果官网上注册一个开发者账号，提供真实的个人或公司信息，并支付一定的注册费用（个人账号/公司开发者账号年费为99美金/年，企业账号年费为299美金/年）。
    * 账号申请需要一定的时间进行审核，审核通过后才能使用。

 2. 准备应用相关材料：
    
    * 应用名称、图标、描述、关键词等。
    * 应用截图和预览视频（如果需要）。
    * 应用定价和支付方式（如果应用是付费的）。


## 二、发布上架流程

 1. 创建App ID：
    
    * 登录苹果开发者账号，配置App bundle ID。
    * bundle ID的格式通常为com.company.AppName（包含两个点）。

 2. 创建证书请求文件（CSR文件）和发布证书 ：
    
    * 使用Mac的钥匙串访问工具创建CSR文件。
    * 在苹果开发者中心创建发布证书，并下载到本地，双击安装。

 3. 创建Provisioning Profiles配置文件（PP文件）：
    
    * 在苹果开发者中心创建配置文件，将证书和Bundle Identifier关联起来。

 4. 在iTunes Connect创建应用：
    
    * 登录iTunes Connect（现已整合到App Store Connect）。
    * 创建应用，填写应用的详细信息，包括主标题、副标题、描述、关键词等。

 5. 生成应用存档文件（IPA文件）：
    
    * 使用Xcode打包应用，生成IPA文件。

 6. 使用Xcode提交应用：
    
    * 在Xcode中选择“Product” -> “Archive”来创建一个应用存档。
    * 使用Xcode的Organizer工具将存档提交到App Store Connect。

 7. 配置应用的价格和付款方式：
    
    * 在App Store Connect中选择应用的价格（免费或付费），并配置支付方式。

 8. 提交应用进行审核：
    
    * 提交应用进行审核，等待苹果审核通过。

 9. 跟踪应用表现：
    
    * 一旦应用上架成功，可以使用App Store Connect跟踪应用的下载量、评价、收入等信息。


## 四、注意事项

 1. 遵守苹果的规定和法律法规：确保应用内容合法，不侵犯他人版权和知识产权。
 2. 优化界面设计和用户体验：确保应用界面简洁、清晰、易于使用。
 3. 确保应用的安全性和稳定性：进行充分的安全性测试和性能测试，确保应用无严重漏洞和错误。
    编撰人：puwb


快速跳转



 * iOS APP发布上架详细流程和操作步骤
   * 一、前期准备
   * 二、发布上架流程
   * 四、注意事项



分享链接分享链接

## 49. M3云定制功能及注意事项

> 原始路径：`/1269/1305/`  
> 相对路径：`1269/1305/README.md`  
> JS Chunk：`app.844f671c.js`

## M3云定制功能及注意事项


## 一、概述

M3云定制服务旨在为客户提供标准M3产品的个性化定制，包括更换APP图标、名称及预制后端服务器地址等功能，以满足客户在Android和IOS平台上的特定需求。

个性化意味着存在定制成本和风险约束，本文档旨在明确云定制服务的注意事项、处理步骤和方法，以确保服务的顺利进行，所有涉及云定制诉求的客户务必详细看完文档，再做是否定制的决策。

本文档适用场景：

 * 协同云-M3云定制：适用于需要对标准M3进行浅层二次封装（不用开发获取源码定制），以满足APP个性化需求的场景。

> 当前主要提供更换 APP 图标，修改 APP 名称，预制服务器地址等功能。


## 二、操作文档

在线和离线分别提供了一份M3云定制文档（二选一参考即可）：

 * 在线文档存放于协同云-帮助手册-基础操作指南-工作台-【M3云定制】

 * 离线文档存放于商务公布的安装程序/文档下载地址-客户版本-文档-操作手册-M3用户操作手册-“定制版本管理-云打包”章节




## 三、风险与注意事项

 1. 交付成本：M3云定制仅省去了代码开发工作量，实际获取证书、签名、注册定位key、注册离线消息、打包上架、安全过审都存在工作量，并且需要具备相关经验的人员操作，请参考本文做好成本的预估，不要仅仅只考虑云定制配置成本！
 2. 标准产品问题：云定制后的 APP 已非标准产品 APP ，如出现标准产品问题或安全审计问题，可能无法立刻解决，一般都要用最新版本APP做重新打包，需提前与客户沟通成本和时间风险。
 3. 权益使用：一个端一次权益，如同时封装 iOS 和 Android，需购买两次权益。权益自生效时间起一个月内有效，过期后将无法重新构建。
 4. 隐私协议：用户隐私协议需要客户自行编写，隐私协议具有法律效应，建议客户法务确认后发布。可以基于M3标准协议进行修改，单需要剔除所有与致远相关的信息。

> 注意：隐私协议是具有法律效益的文书，切忌直接拷贝致远的隐私协议。如客户基于致远隐私协议进行修改不可包含任何致远信息，否则客户可能会承担相关的法律责任。


## 四、能力要求


## Android APP定制要求



注：以下所有操作都是M3云定制的额外成本支出：

类型       操作人能力要求                         影响范围                                             参考文档
证书文件     具备计算机基础能力人员                     必做，如无证书无法做APP定制                                  M3操作手册-云打包
构建错误     具备Android APP编译构建错误日志分析能力       必做，如出现错误无法成功构建APP                                无参考，建议先做纯证书构建，再依次加入别的配置，错误时方便找原因
高德定位     具备计算机基础，自主去高德官网申请               不做会导致APP定位功能不可用                                  高德定位官网（手册中有地址）
Mob分享    具备计算机基础，自主去分享官网申请               不做会影响APP分享给QQ、微信、钉钉                              各自官网申请（手册中有地址）
乐播投屏     具备计算机基础，自主去乐播官网申请               不做会影响APP投屏到乐播                                    乐播分享官网（手册中有地址）
华为推送     具备申请华为推送证书经验，并且必须上架华为市场         不做影响华为手机收到离线消息                                   华为推送官网（手册中有地址）
小米推送     具备申请小米推送证书经验，并且必须上架小米市场         不做影响小米手机收到离线消息                                   小米推送官网（手册中有地址）
VIVO推送   具备申请VIVO推送证书经验，暂时无需上架市场         不做影响VIVO手机收到离线消息                                 VIVO推送官网（手册中有地址）
OPPO推送   具备申请OPPO推送证书经验，暂时无需上架市场         不做影响OPPO手机收到离线消息                                 OPPO推送官网（手册中有地址）
魅族推送     具备申请魅族推送证书经验，暂时无需上架市场           不做影响魅族手机收到离线消息                                   魅族推送官网（手册中有地址）
荣耀推送     具备申请荣耀推送证书经验，暂时无需上架市场           不做影响荣耀手机收到离线消息                                   荣耀推送官网（手册中有地址）
ICP备案    具备ICP备案经验                       2024年工信部新规，不做备案会影响APP分发                          APP备案参考文档
隐私协议     客户的法务参考M3标准协议做修改，涉及“致远”内容全部剔除   不能照抄M3隐私，完全复制极大概率审核无法通过                          工信部关于隐私政策的说明，以及M3隐私协议
APP上架    具备APP上架应用市场经验                   如无离线消息接收需求尽量建议内部分发，如果上架，涉及大量客户资质、审核等动作，成本和周期不低   各应用市场上架规范
安全漏洞     具备APP应用安全处理经验                   可能影响安全过审                                         无，参考安全扫描厂商的要求处置


## IOS APP定制要求



注：以下所有操作都是M3云定制的额外成本支出：

类型       能力要求                           影响范围                      参考文档
根证书文件    具备IOS开发能力人员+Mac电脑+客户已注册299证书   必做，如无根证书无法做APP定制          M3操作手册-云打包
构建错误分析   具备IOS APP编译构建错误日志分析能力          必做，如出现错误无法成功构建APP         无参考，建议先做纯证书构建，再依次加入别的配置，错误时方便找原因
高德定位     同Android                       不做会导致APP定位功能不可用           可复用Android申请的Key，无需重复申请
Mob分享    同Android                       不做会影响APP分享给QQ、微信、钉钉       可复用Android申请的Key，无需重复申请
乐播投屏     同Android                       不做会影响APP投屏到乐播             可复用Android申请的Key，无需重复申请
百度推送     可忽略                            可忽略，M3 IOS不用百度推送          可忽略
离线消息     具备计算机基础，需要将IOS根证书上传到融云，由融云推送   不做影响IOS接收离线消息             M3操作手册-云打包
ICP备案    同Android                       2024年工信部新规，不做备案会影响APP分发   与Android统一申请即可
隐私协议     同Android                       不做影响APP上架应用市场             与Android统一协议即可
APP上架    具备IOS APP上架应用市场经验                                        IOS应用市场上架规范
安全漏洞     具备APP应用安全处理经验                  可能影响安全过审                  无，参考安全扫描厂商的要求处置


## 五、云打包步骤与方法

1、需求分析：

 * 与客户沟通，明确定制需求，包括APP图标、名称、服务器地址等。
 * 评估需求实现的可行性，并提供初步解决方案。

> 此步骤非常关键，如果客户后续有其他的客开需求，那么不建议使用云定制。并且云定制不支持云定制已提供的功能外的其他定制化开发需求。

2、环境准备：

 * 根据定制平台（Android或IOS）准备相应的开发环境和工具。
 * 准备必要的证书文件和资源文件。

3、定制开发：

 * 按照客户需求进行APP图标、名称的更换。
 * 根据需要预制后端服务器地址。
 * 如需使用第三方服务（如推送、定位、分享等），进行必要的配置和集成。

4、测试验证：

 * 在开发环境中进行功能测试，确保定制功能正常运行。
 * 如有必要，进行多机型、多系统版本的兼容性测试。

5、打包发布：

 * 打包生成APK或IPA文件。
 * 如需上架应用商店，按照平台要求准备相关资料并提交审核。

6、APP加固

 * 从云定制下载的APP未进行加固，需要自行进行加壳处理
 * Android和iOS都需要进行加固（加壳）处理，参考软件-爱加密

7、后期维护：

 * 提供必要的后期技术支持和维护服务。
 * 如遇标准产品问题，及时与客户沟通并寻求解决方案。


## 常见问题


## 问题：云端构建失败，如何排查？

解决方案： 如果看不懂日志，则一步一步操作来排查构建失败原因。

第一步：仅上传证书文件，然后进行编译，如果失败则说明证书有问题，请找专业人员注册证书；

第二步：如果证书没问题，再加入定位Key，然后进行编译，如果失败则说明定位Key有问题；

后续步骤，依葫芦画瓢，一个一个加，排查具体编译失败的问题点！




## 问题：APP上架应用市场失败，如何排查？

解决方案： 根据应用市场的错误信息，自行网上搜索解决方案消除问题，或联系有上架经验的人员协助上架。

编撰人：puwb、het


快速跳转



 * M3云定制功能及注意事项
   * 一、概述
   * 二、操作文档
   * 三、风险与注意事项
   * 四、能力要求
     * Android APP定制要求
     * IOS APP定制要求
   * 五、云打包步骤与方法
   * 常见问题
     * 问题：云端构建失败，如何排查？
     * 问题：APP上架应用市场失败，如何排查？



分享链接分享链接

## 50. 云打包：iOS证书制作

> 原始路径：`/1269/1305/1943.html`  
> 相对路径：`1269/1305/1943.md`  
> JS Chunk：`app.844f671c.js`

## 云打包：iOS证书制作


## 文档目的

本文档旨在指导iOS开发人员如何生成CSR文件、.p12证书，以及创建主App ID、子App ID、Group ID、主描述文件和子描述文件。这些步骤是iOS应用开发和分发过程中必不可少的环节。


## 基本要求

 * Mac电脑：用于生成CSR文件和操作证书
 * 苹果开发者账号：用于在苹果开发者中心创建证书和描述文件,如果没有则需要注册申请 https://developer.apple.com/
 * 适合人群：具备Mac电脑使用基础的IT技能人员，推荐：iOS APP开发人员


## 操作步骤


## 第1步：生成CSR文件（证书签名请求文件）

 1. 打开钥匙串访问：
    
    * 在Mac电脑上，打开“钥匙串访问”应用。

 2. 生成CSR文件：
    
    * 选择菜单栏中的“证书助理”>“从证书颁发机构请求证书”。
    * 在弹出的窗口中，输入注册苹果开发者账号时使用的电子邮件地址和常用名称（通常是你的名字或公司名称）。
    * 选择“存储到磁盘”，然后点击“继续”。
    * 保存CSR文件到本地，方便后续使用。


## 第2步：创建iOS开发证书

 1. 登录苹果开发者中心：
    
    * 打开浏览器，访问苹果开发者中心。
    * 点击右上角的“Account”并使用你的Apple ID登录。

 2. 进入“Certificates, Identifiers & Profiles”部分：
    
    * 在左侧菜单中，选择“Certificates”。

 3. 创建新证书：
    
    * 点击页面右上角的“+”按钮创建新的证书。
    * 选择证书类型（例如“iOS Development”或“iOS Distribution”）并点击“Continue”。
    * 按照页面提示，上传之前生成的CSR文件，然后点击“Continue”。
    * 生成并下载证书（.cer文件）。




## 第3步：安装.cer文件并导出.p12文件

 1. 安装.cer文件：
    
    * 双击下载的.cer文件，将其安装到“钥匙串访问”中。

 2. 导出.p12文件：
    
    * 在“钥匙串访问”中，找到刚刚安装的证书。
    * 右键点击证书，选择“导出”。
    * 在导出窗口中，选择“个人信息交换（.p12）”格式。
    * 设置密码（请记住这个密码，后续会用到），然后保存.p12文件。


## 第4步：创建主App ID

 1. 返回苹果开发者中心：
    
    * 在左侧菜单中，选择“Identifiers”。

 2. 创建新的App ID：
    
    * 点击页面右上角的“+”按钮创建新的标识符。



 * 在“Register a New Identifier”页面，选择“App IDs”并点击“Continue”。



 * 在“App ID Description”部分，输入描述和Bundle ID（格式：com.yourdomain.appname），然后点击“Continue”。



 * 确认信息后，点击“Register”完成主App ID的创建。


## 第5步：创建子App ID

 1. 重复创建主App ID的步骤：
    * 使用与主App ID相同的格式输入描述和Bundle ID（例如：com.yourdomain.appname.child）。
    * 完成子App ID的创建。


## 第6步：创建Group ID

 1. 返回“Certificates, Identifiers & Profiles”部分：
    
    * 在左侧菜单中，选择“Identifiers”。

 2. 创建新的Group ID：
    
    * 点击页面右上角的“+”按钮创建新的标识符。
    * 在“Register a New Identifier”页面，选择“App Groups”并点击“Continue”。



 * 输入Group ID的描述和标识符（格式：group.yourdomain.appname），然后点击“Continue”。



 * 确认信息后，点击“Register”完成Group ID的创建。


## 第7步：关联Group ID

 1. 返回“Identifiers”部分：
    
    * 选择之前创建的主App ID。

 2. 关联Group ID：
    
    * 在App ID详情页面，点击“Edit”。
    * 在“Capabilities”部分，启用“App Groups”。
    * 选择之前创建的Group ID，然后点击“Save”。



 3. 重复步骤：
    * 将子App ID与Group ID关联。


## 第8步：创建主描述文件

 1. 返回“Certificates, Identifiers & Profiles”部分：
    
    * 在左侧菜单中，选择“Profiles”。

 2. 创建新的描述文件：
    
    * 点击页面右上角的“+”按钮创建新的描述文件。



 * 在“Select a profile type”页面，选择适合的描述文件类型（例如“App Store”）并点击“Continue”。
 * 选择主App ID和相关的证书，然后点击“Continue”。



 * 输入描述文件的名称，然后点击“Generate”生成描述文件。
 * 下载生成的主描述文件。


## 第9步：创建子描述文件

 1. 重复创建主描述文件的步骤：
    * 选择子App ID和相关的证书。
    * 命名并生成子描述文件。
    * 下载生成的子描述文件。

----------------------------------------


## 注意事项

 * 如果需要多个子描述文件，重复上面创建子AppID，关联GroupID，创建子描述文件的步骤即可
 * CSR文件：CSR文件是由私钥生成的，包含公钥和相关信息。
 * P12文件：P12文件是由.cer证书和私钥导出的，包含公钥和私钥。
 * 安全：P12文件包含私钥，是非常重要的文件，请妥善保管，不要泄露。
 * 描述文件：描述文件用于定义应用的权限和配置，确保在开发和分发过程中正确使用。

完成上述步骤后，你将获得一个.p12文件和多个描述文件，它们是iOS应用开发和分发过程中必不可少的。如果在操作过程中遇到任何问题，请参考苹果官方文档或联系苹果开发者支持。

编撰人：het、guojl


快速跳转



 * 云打包：iOS证书制作
   * 文档目的
   * 基本要求
   * 操作步骤
     * 第1步：生成CSR文件（证书签名请求文件）
     * 第2步：创建iOS开发证书
     * 第3步：安装.cer文件并导出.p12文件
     * 第4步：创建主App ID
     * 第5步：创建子App ID
     * 第6步：创建Group ID
     * 第7步：关联Group ID
     * 第8步：创建主描述文件
     * 第9步：创建子描述文件
   * 注意事项



分享链接分享链接

## 51. 云打包：安卓签名证书制作和公钥查看

> 原始路径：`/1269/1305/2549.html`  
> 相对路径：`1269/1305/2549.md`  
> JS Chunk：`app.844f671c.js`

## 云打包：安卓签名证书制作和公钥查看


## 一 生成签名证书

1、安装JDK，并配置好环境变量

2、使用如下命令生成签名证书 keytool -genkey -alias testalias -keyalg RSA -keysize 2048 -validity 36500 -keystore test.keystore

testalias 是证书别名，可修改为自己想设置的字符，建议使用英文字母和数字 test.keystore 是证书文件名称，可修改为自己想设置的文件名称，也可以指定完整文件路径 36500 是证书的有效期，表示 100 年有效期，单位天，建议时间设置长一点，避免证书过期


## 二 查看签名证书

1、安装JDK，并配置好环境变量

2、使用如下命令查看

keytool -list -v -keystore test.keystore

其中MD5码值也在其中，如下图：


## 三 查看公钥信息

1、百度搜索安装jadx-gui工具。

2、用jadx-gui工具反编译构建好安卓apk包，其中的模数就是公钥：

注意：不需要源码，只需要安卓的apk安装包即可！！！

编撰人：zouykk


快速跳转



 * 云打包：安卓签名证书制作和公钥查看
   * 一 生成签名证书
   * 二 查看签名证书
   * 三 查看公钥信息



分享链接分享链接

## 52. M3 人脸识别服务第三方应用接入开发文档

> 原始路径：`/1269/1315.html`  
> 相对路径：`1269/1315.md`  
> JS Chunk：`app.844f671c.js`

## M3 人脸识别服务第三方应用接入开发文档


## 一、引言

为提升数据准确和安全性，增强人事考勤管理能力、流程审批管理能力和 M3 Android 客户端 APP 安全，A8 V9.0 版本新增人脸识别能力。

适用于考勤签到、流程审批、支付等需要二次身份验证场景。


## 二、接入前提条件

> 注意：人脸识别当前只支持注意：人脸识别当前只支持 M3 ，不支持微协同


## 1、服务准备

 * * 安装部署旷视人脸服务，并创建自建应用
   
   > 获取旷视服务安装包与授权需要联系旷视官方商务或运维技术人员。
   > 
   > 参考文档：【旷视人脸识别（FaseID企业版）私有化服务安装部署文档】

 * * 申请 A8 服务加密狗，需要人脸识别插件

 * * 安装部署 A8 服务，并完成人脸服务相关配置

 * * 仅支持 A8 V9.0 及以上版本。M3 客户端 4.6.0 及以上版本。


## 2、技术准备

 * 前端开发工程师

 * 熟悉致远 CMP 平台
   
   > CMP 平台参考文档：https://open.seeyoncloud.com/cmpdev


## 三、接入流程概述




## 四、技术接入指南


## 1、OA PC 人脸识别接口

 * API： window.faceEECheck(success, error)

 * 资源依赖文件引入
   
   <scrpit src="${path}/apps_res/faceId/js/faceIdQrCode.js" />
   
   
   > ${path} 在 OA 后端 JSP 文件中作为 el 参数。如前后端分离可以将 ${path} 改为 seeyon 或其他（根据实际情况）。

 * 参数说明
   
   参数名称      类型         说明
   success   function   成功回调函数
   error     function   失败回调函数

 * 调用示例
   
   window.faceEECheck(function(data) {
       // 这里实现人脸识别成功回调
   }, function(error) {
       // 这里实现人脸识别失败回调
   })
   

 * 成功回调参数说明
   
   参数名称                      类型       说明
   qrCodeData                Object   
   qrCodeData.grImageurl     String   人脸识别认证二维码地址。（一般业务不需要）
   qrCodeData.bizInfoToken   String   识别结果查询码
   qrCodeData.bizNo          String   业务码

 * 失败回调参数说明
   
   无返回参数


## 2、移动H5应用调用人脸识别接口

 * API： cmp.sdk.faceEECheck(attendance, success, error)

 * 资源依赖文件引入
   
   <scrpit src="cmp://cmp/v/js/cmp-i18n.js" />
   <scrpit src="cmp://cmp/v/js/cordova/__CMPSHELL_PLATFORM__/cordova.js" />
   <scrpit src="cmp://cmp/v/js/cordova/cordova-plugins.js" />
   <scrpit src="cmp://cmp/v/js/cmp.js" />
   

 * 参数说明
   
   参数名称         类型         说明
   attendance   boolean    是否是考勤模块调用，默认 false。非 OA 标准产品考勤业务都需要传入 false
   success      function   成功回调函数
   error        function   失败回调函数

 * 调用示例
   
   cmp.sdk.faceEECheck(false, function(data) {
       // 这里实现人脸识别成功回调
   }, function(error) {
       // 这里实现人脸识别失败回调
   })
   

 * 成功回调参数说明
   
   参数名称       类型       说明
   code       int      返回码：200 成功，其他均失败
   type       String   认证状态
                       1：成功
                       2：人脸录入成功
   qrCodeId   String   二维码ID
   bit        String   结果查询码（bizInfoToken ）
   message    String   返回消息

 * 失败回调参数说明
   
   参数名称   类型       说明
   type   String   -1：用户主动注销
                   500：其他异常


## 3、服务端人脸识别 API

服务端 API 依赖 apps-api 模块：com.seeyon.apps.faceId.api.FaceIdApi 类

 * 判断指定人员是否拥有人脸识别授权
   
   当后端业务需要判断人员是否拥有人脸授权可调用此接口。当指定人员没有人脸识别授权或服务没有人脸插件和人脸识别服务不可用时，返回 false。反之返回true。
   
   boolean hasFaceIdAuth(long memberId);
   
   
   > 备注：此接口同时会验证人脸插件是否可用，人脸服务是否可用。
   
   * 接口参数
     
     参数名称       类型     是否必须   说明
     memberId   long   是      人员ID，OA 系统组织架构中的人员的ID
   
   * 返回数据
     
     参数名称   类型        默认值     说明
     是否授权   boolean   false   是否授权：true 已授权，false 未授权
   
   * 示例
     
     import com.seeyon.apps.faceId.api.FaceIdApi;
     
     public class BusinessDemo {
         // 获取人脸识别 API 的实现。注意：调用 faceIdApi 的方法时建议对 faceIdApi 对象做非空判断
     	private FaceIdApi faceIdApi = (FaceIdApi) AppContext.getBean("faceIdApi");
         
         public void testDemo() {
             // ... 业务实现
             boolean has = faceIdApi.hasFaceIdAuth(-54122145481136741347L); // 判断人员是否有人脸识别授权
             if (has) {
                 // ... 业务实现
             } else {
                 // ... 业务实现
             }
             // ... 业务实现
         }
     }
     

 * 判断是否有人脸插件
   
   当业务模块需要根据是否有人脸插件处理逻辑时，可以通过此接口判断服务是否拥有人脸插件。
   
   boolean hasFaceIdPlugin();
   
   
   * 接口参数
     
     无
   
   * 返回数据
     
     参数名称    类型        默认值     说明
     是否有插件   boolean   false   是否有插件：true 有插件，false 无插件或插件不可用
   
   * 示例
     
     import com.seeyon.apps.faceId.api.FaceIdApi;
     
     public class BusinessDemo {
         // 获取人脸识别 API 的实现。注意：调用 faceIdApi 的方法时建议对 faceIdApi 对象做非空判断
     	private FaceIdApi faceIdApi = (FaceIdApi) AppContext.getBean("faceIdApi");
         
         public void testDemo() {
             // ... 业务实现
             boolean has = faceIdApi.hasFaceIdPlugin(); // 判断是否有插件
             if (has) {
                 // ... 业务实现
             } else {
                 // ... 业务实现
             }
             // ... 业务实现
         }
     }
     

 * 人脸是否可用
   
   当业务模块需要根据是否有人脸插件切人脸服务是否可用处理逻辑时，可以调用此接口判断。
   
   boolean faceIdEnable();
   
   
   > 备注：此接口同时会验证人脸插件是否可用。
   
   * 接口参数
     
     无
   
   * 返回数据
     
     参数名称    类型        默认值     说明
     是否有插件   boolean   false   是否授权：true 有插件，false 无插件或插件不可用
   
   * 示例
     
     import com.seeyon.apps.faceId.api.FaceIdApi;
     
     public class BusinessDemo {
         // 获取人脸识别 API 的实现。注意：调用 faceIdApi 的方法时建议对 faceIdApi 对象做非空判断
     	private FaceIdApi faceIdApi = (FaceIdApi) AppContext.getBean("faceIdApi");
         
         public void testDemo() {
             // ... 业务实现
             boolean has = faceIdApi.faceIdEnable();
             // ... 业务实现
         }
     }
     

 * 检查识别结果
   
   当业务场景中，用户完成人脸识别后，服务端应对验证结果进行二次校验。此时可根据前端接口返回的参数传入后端接口中。在后端接口调用此接口进行二次校验人脸识别结果。
   
   Map<String, Object> checkRecognitionResult (String bizNo, String bizInfoToken);
   
   
   * 接口参数
     
     参数名称           类型       是否必须   说明
     bizNo          String   是      业务编码
     bizInfoToken   String   是      业务查询码
   
   * 返回数据
     
     参数名称     类型       默认值      说明
     bizNo    String            业务编码
     status   String   failed   结果状态：
                                created：认证请求已创建未开始
                                erifying：认证中
                                success：认证成功
                                failed：认证失败
                                cancelled：认证被取消中止
                                timeout：认证流程超时
   
   * 示例
     
     import com.seeyon.apps.faceId.api.FaceIdApi;
     
     public class BusinessDemo {
         // 获取人脸识别 API 的实现。注意：调用 faceIdApi 的方法时建议对 faceIdApi 对象做非空判断
     	private FaceIdApi faceIdApi = (FaceIdApi) AppContext.getBean("faceIdApi");
         
         public void testDemo() {
             // ... 业务实现
             Map<String, Object> result = faceIdApi.checkRecognitionResult("Pcn12SA", "jEf92Lsn172");
             String status = String.valueOf(result.get("status"));
             String bizNo = String.valueOf(result.get("bizNo"));
             if ("success".equals(status)) {
                 // ... 业务实现
             } else {
                 // ... 业务实现
             }
             // ... 业务实现
         }
     }
     

 * 业务模块人脸服务是否可用
   
   判断人脸识别业务模块是否可用及用户是否购买相关只插件，仅适用标准产品 M3 Android 唤醒、标准产品人脸识别考勤签到、标准产品人脸识别流程审批。第三方接入或其他场景此接口无用，无需调用此接口判断。
   
   boolean faceIdByBusinessPluginEnable(String businessPluginName)
   
   
   * 接口参数
     
     参数名称                 类型       是否必须   说明
     businessPluginName   String   是      业务模块ID：
                                          faceId_m3_awakening：M3 唤醒
                                          faceId_clock：人脸识别考勤签到
                                          faceId_approve：人脸识别流程审批
   
   * 返回数据
     
     参数名称     类型        默认值     说明
     模块是否可用   boolean   false   true：可用；false：不可用
   
   * 示例
     
     import com.seeyon.apps.faceId.api.FaceIdApi;
     
     public class BusinessDemo {
         // 获取人脸识别 API 的实现。注意：调用 faceIdApi 的方法时建议对 faceIdApi 对象做非空判断
     	private FaceIdApi faceIdApi = (FaceIdApi) AppContext.getBean("faceIdApi");
         
         public void testDemo() {
             // ...
             boolean has = faceIdApi.hasFaceIdAuth(-54122145481136741347L);
             // ...
         }
     }
     

编撰人：puwb


快速跳转



 * M3 人脸识别服务第三方应用接入开发文档
   * 一、引言
   * 二、接入前提条件
     * 1、服务准备
     * 2、技术准备
   * 三、接入流程概述
   * 四、技术接入指南
     * 1、OA PC 人脸识别接口
     * 2、移动H5应用调用人脸识别接口
     * 3、服务端人脸识别 API



分享链接分享链接

## 53. 移动分离部署服务 — 安装部署文档

> 原始路径：`/1269/1826.html`  
> 相对路径：`1269/1826.md`  
> JS Chunk：`app.844f671c.js`

## 移动分离部署服务 — 安装部署文档


## 一、简述

移动分离部署服务是为了解决客户需要将移动端 M3 或微协同进行服务单独分离部署需求而提供的独立服务。

移动分离部署服务总共有两个部分组成：

1、主服务 Seeyon-Mobile-Gateway 服务，此服务提供访问代理和请求转发服务。

2、静态服务 Seeyon-Static-Resource 服务，此服务提供静态资源部署和访问服务，静态资源服务 是可选服务，如客户有静态资源分离部署需求可使用此服务，如果不需要静态资源分离部署可以不使用此服务。此服务不可独立运行，需依赖主服务。

> 注意：

> 1、静态服务目前只支持部署微协同的 H5 静态资源，具体部署方式参考步骤 【五、部署静态资源】。

> 2、微协同使用分离部署后，只能通过微信、企业微信、钉钉、飞书等移动端访问，PC端是不支持访问的。因为分离部署会拦截PC端的 .do 请求。


## 二、网络拓扑图说明



访问示意图：




## 三、安装包说明

从商务公布的安装程序下载地址，下载与版本相匹配的安装包，安装包名为“SeeyonMobileCloud.zip”：



SeeyonMobileCloud.zip 是整个工程的安装包。直接解压到指定目录即可。解压后的目录中包含主服务 Seeyon-Mobile-Gateway 服务与静态服务 Seeyon-Static-Resource 服务两个文件夹。静态服务 Seeyon-Static-Resource 服务是可选服务，根据用户的需求选择是否需要部署。

解压后目录结构如下：



> 注意：不可手动修改 init-config.json 初始化配置文件


## 四、安装部署


## Linux环境调优

如部署环境为Linux或信创服务器，在进行安装部署前，先按照如下配置优化Linux相关系统参数：

修改Linux最大进程数最大文件打开数：

通过 vim /etc/security/limits.conf 命令编辑此文件添加以下内容

## open files  (-n)
* soft nofile 65535
* hard nofile 65535
## max user processes  (-u)
* soft nproc 65535
* hard nproc 65535

## 设置当前会话中立刻生效
ulimit -n 65535  # 设置最大打开文件数量
ulimit -u 65535  # 设置最大进程数


以上配置完成后，执行 ulimit -a 命令检查open files和max user processes是否都变成65535


## 安装前重要提醒

提醒：切记安装部署目录中请勿使用空格和中文字符


## 1、主服务安装部署

a. 直接解压 SeeyonMobileCloud.zip 压缩包到指定目录，或将 SeeyonMobileCloud.zip 压缩包中的 Seeyon-Mobile-Gateway 文件夹及文件夹中的所有文件解压到任意目录即可。

b. 将 JAVA 运行环境 JDK 拷贝到与 Seeyon-Mobile-Gateway 文件夹同级目录

> 注意：请使用 JDK 1.8 及以上版本，最低版本不能低于 JDK 1.8，推荐使用 JDK 1.8 版本。并且 Windows 与 Linux 系统需要区分 JDK ，32位系统与64位系统也需要区分JDK，请勿混用！

如下所示：



JDK 获取方法：

1.可以将 A8 安装目录下的 jdk 目录完整拷贝，一般在 A8 安装目录与 ApacheJetspeed 目录同级。（推荐，无需额外配置）



2.可以通过 JDK 官网下载获取。JDK 官网下载地址：https://www.oracle.com/hk/java/technologies/javase-downloads.html （不推荐容易配置错误）

c. 运行 Seeyon-Mobile-Gateway/config 目录下的 Config 配置脚本，启动配置工具。（Windows 环境请运行 .cmd 文件；Linux 环境请运行 .sh 文件）

d. 按照提示完成配置即可。

> 注意：Linux 运行 .sh 脚本需要将 .sh 脚本文件授权可运行权限。详细服务配置请参考【六、服务配置】


## 2、静态服务安装部署（可选服务）

静态服务是可选服务，主要提供静态资源分离部署的能力。如：微协同的 H5 静态资源其中包括：Html, JS, CSS, 图片等资源文件。根据客户自身需求进行部署。

静态服务可独立部署（指：可以与主服务分别部署在不同的服务器上），但不可独立运行，需要与主服务配合使用（指：主服务未部署或未启动状态下，只部署了静态服务是不可以单独直接使用的）。

a. 直接解压** SeeyonMobileCloud.zip** 压缩包到指定目录，或将 SeeyonMobileCloud.zip 压缩包中的 Seeyon-Static-Resource 文件夹及文件夹中的所有文件解压到任意目录即可。

b. 将 JAVA 运行环境 JDK 拷贝到与 Seeyon-Static-Resource 文件夹同级目录 如下所示：



JDK 获取方法：

1.可以将 A8 安装目录下的 jdk 目录完整拷贝，一般在 A8 安装目录与 ApacheJetspeed 目录同级。（推荐，无需额外配置）



2.可以通过 JDK 官网下载获取。JDK 官网下载地址：https://www.oracle.com/hk/java/technologies/javase-downloads.html （不推荐容易配置错误）

c. 运行 Seeyon-Static-Resource/config 目录下的 Config 配置脚本，启动配置工具。（Windows 环 境请运行 .cmd 文件；Linux 环境请运行 .sh 文件）

d. 按照提示完成配置即可。

> 说明：

> 1、Linux 运行 .sh 脚本需要将 .sh 脚本文件授权可运行权限。部署静态资源请参考【五、部署静态资源】；详细服务配置请参考【六、服务配置】；

> 2、首次配置会自动进行初始化，配置完成保存后初始化生效；

> 3、初始化生效后 init-config.json 文件将自动删除，并生成新的 config 加密文件，config 加密文件不可手动修改，不可删除；

> 4、不可手动修改 init-config.json 文件，否则可能导致初始化失败或无法正常保存配置；

> 5、config 加密文件只在当前服务器 OS 系统中生效，拷贝到其他环境或从其他环境拷贝到当前环境是无法读取的。如需要迁移服务器请在新服务器中重新安装部署。


## 五、部署静态资源

> 注意：只有微协同静态资源分离部署的时候才需要使用静态资源服务，也只有使用微协同的用户对微协同有分离部署需求的才需要使用静态资源服务，且静态资源服务目前只支持部署微协同静态资源。

1.确认静态服务 Seeyon-Static-Resours 服务的 html 目录下是否有 seeyon 目录，如果没有请新建 seeyon 目录

2.进入 A8(A6,G6) 安装目录 \ApacheJetspeed\webapps\seeyon 目录

目录结构参考如下：



3.将 H5 目录以及目录中的所有文件拷贝到静态服务 Seeyon-Static-Resours 服务的 html 下的 seeyon 目录中。

4.将 m3 目录以及目录中的所有文件拷贝到静态服务 Seeyon-Static-Resours 服务的 html 下的 seeyon 目录中。

5.将 skin 目录以及目录中的所有文件拷贝到静态服务 Seeyon-Static-Resours 服务的 html 下的 seeyon 目录中。

6.将 apps_res 目录以及目录中的所有文件拷贝到静态服务 Seeyon-Static-Resours 服务的 html 下 的 seeyon 目录中。

7.将 common 目录以及目录中的所有文件拷贝到静态服务 Seeyon-Static-Resours 服务的 html 下的 seeyon 目录中。

目录结构参考如下：




## 六、服务配置

分别运行主服务 Seeyon-Mobile-Gateway 和静态服务 Seeyon-Static-Resource 的 config 目录下的 Config.cmd（Windows） 或 Config.sh（Linux） 脚本启动配置工具

> 注意：Linux 运行 .sh 脚本需要将 .sh 脚本文件授权可运行权限。

1.设置分离服务主服务端口：

端口范围只能为 0 至 65535 的整数，建议使用 8000 以上的端口。8000 以下的端口多为系统保留端口和其他服务端口。并且保证设置的端口未被占用或其他服务使用。



2.设置 A8(A6, G6) 服务地址：

地址格式必须为：http(s)😕/{IP地址或域名}:{端口}，如：http://127.0.0.1:80 或 http://test.a8.co m:80。端口必须填写。并且请确保分离服务能正常访问 A8(A6, G6) 服务的地址。如果 A8(A6, G6) 服务与分离服务在同一个内网环境，建议使用内网的访问 IP 地址或域名，可以提高服务性能。如 果 A8(A6, G6) 服务是集群部署，请配置集群服务的地址和端口。

> 注意：除 V5-A8(A6, G6) 服务集群部署需要的集群服务器外，分离服务于 A8 服务之间不建议再使用其他任何网络代理相关或类似的服务，如使用可能造成网络环境过于复杂不利于维护。

3.设置静态服务地址：

静态服务是可选服务，如果用户没有静态服务分离部署需求，此处可以不用配置。配置静态服务需要确保服务已正确部署，且分离服务主服务可以正确访问到静态服务。

配置地址格式必须为：http(s)😕/{IP地址或域名}:{端口}，如：http://127.0.0.1:808 或 http://statice.service.com:808。端口必须填写。



4.设置分离服务静态服务端口：

端口范围只能为 0 至 65535 的整数，建议使用 8000 以上的端口。8000 以下的端口多为系统保留端口和其他服务端口。并且保证设置的端口未被占用或其他服务使用。



5.保存

点击【保存】按钮保存配置即可。

> 保存后需要重启服务新的配置才生效。


## 七、服务启动

完成以上配置后，运行 startup.cmd（Windows） 或 startup.sh（Linux） 脚本启动服务即可。主服务于静态服务启动不区分先后顺序。A8(A6, G6) 服务未启动前也可以先启动分离服务。但使用时需要确定 A8(A6, G6) 服务已正常启动。

> 注意：Linux 运行 .sh 脚本需要将 .sh 脚本文件授权可运行权限。


## 八、分离服务集群

移动分离服务本身支持集群。不区分主从节点。按照以上方式完成节点部署后，可通过 Nginx ，Apache，F5 等相关集群服务进行集群。

> 无特殊集群配置，相关服务配置参考集群服务提供方相关文档即可。


## 九、启用 HTTPS 连接

当前版本移动分离服务本身暂时不支持启用 HTTPS，如用户需要使用 HTTPS 访问分离服务，可以通过在移动分离服务前再部署一个 Web 服务并配置启用 HTTPS 的方式。通过 HTTPS 访问前置 Web 服务再到移动分离服务，完成 HTTPS 连接的启用。如：Nginx，Apache 等


## 附1：M3 使用 Nginx 分离部署

标准 S1 工具支持，参考 S1 相关文档

编撰人：tanghu、het




快速跳转



 * 移动分离部署服务 — 安装部署文档
   * 一、简述
   * 二、网络拓扑图说明
   * 三、安装包说明
   * 四、安装部署
     * Linux环境调优
     * 安装前重要提醒
     * 1、主服务安装部署
     * 2、静态服务安装部署（可选服务）
   * 五、部署静态资源
   * 六、服务配置
   * 七、服务启动
   * 八、分离服务集群
   * 九、启用 HTTPS 连接
   * 附1：M3 使用 Nginx 分离部署



分享链接分享链接

## 54. 微协同

> 原始路径：`/1270/`  
> 相对路径：`1270/README.md`  
> JS Chunk：`app.844f671c.js`

子菜单名称             URL
1. 微协同基础配置介绍      1. 微协同基础配置介绍
2. 私有化部署配置操作手册    2. 私有化部署配置操作手册
3. 集成配置操作手册       3. 集成配置操作手册
4. 微协同问题上报建议      4. 微协同问题上报建议
5. 微协同常见问题FAQ清单   5. 微协同常见问题FAQ清单

分享链接分享链接

## 55. 微协同私有化部署手册-Windows版

> 原始路径：`/1270/1298/1331/1095.html`  
> 相对路径：`1270/1298/1331/1095.md`  
> JS Chunk：`app.844f671c.js`

## 微协同私有化部署手册-Windows版


## 一、前置条件

私有化部署，需要满足如下条件：


## 1、网络条件

 1. 协同系统的访问地址是公网地址，可以是IP也可以是域名，域名的话最好是备案过的（避免企业微信校验为非法域名，禁止访问），OA在内网的客户可以使用反向代理，分离部署方案。
 2. 微协同服务和OA服务需要能够互相访问到。
 3. 微协同服务器地址必须为域名（企业微信配置可信域名使用到，私有化企业微信无限制），并且为公网地址。
 4. 微协同基础配置这里的校验是，OA和微协同服务能够互相访问到，双方互相访问成功后，OA会将rest账号密码推送至微协同服务（rest账号密码的作用就是获取访问OA的token，即是访问权限）。
 5. 用户通过企业微信APP/PC客户端访问微协同的时候，微协同先到企业微信中认证；再通过rest信息获取token到OA中认证，认证完毕后跳转至待办列表，后续的事项处理均是在OA中完成。
 6. OA同步组织架构、发送消息、配置菜单到企业微信的时候，会先将OA的数据推送至微协同，微协同在同步至企业微信。
 7. OA版本必须高于或等于8.0SP2版本才支持私有化部署。




## 2、其他条件

 1. 文件夹的层级目录不能有中文名称
 2. 微协同私有化部署仅和服务号（即是公众号）、企业微信、welink相关
 3. 微协同服务使用的数据库为MySQL，私有化部署包中数据库连接的jar包版本为5.1.38，如果客户使用更高版本的MySQL，请下载对应兼容版本的数据库连接jar包，然后放到该目录下：wx-core-service\webapps\ROOT\WEB-INF\lib。如下图所示（如果忽略此步骤，微协同将无法启动！！！）。
 4. 建议使用MySQL5.6或MySQL5.7版本，如果使用高版本的MySQL8.x可能会导致数据库超时断开连接而无法自动连接的异常，引发业务上的各种报错。



5.微协同域名以及OA访问地址如果是通过nginx配置的，那么请在nginx-conf配置文件中，将underscores_in_headers on配置信息加到http块中去即可。可参考链接：https://blog.csdn.net/loongshawn/article/details/78199977 （如果忽略此步骤，微协同将无法收到消息！！！ 配置完毕后请在微协同基础配置处重新点击确定保存通过）

http {
    include       mime.types;
    default_type  application/octet-stream;

    #log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
    #                  '$status $body_bytes_sent "$http_referer" '
    #                  '"$http_user_agent" "$http_x_forwarded_for"';

    #access_log  logs/access.log  main;

    sendfile        on;
    #tcp_nopush     on;
    underscores_in_headers on; //增加此配置即可
    #keepalive_timeout  0;
    keepalive_timeout  65;



## 3、网络条件说明

请参考文档链接：

【微协同集成-网络配置】网络配置的必要条件说明 https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+NjI3


## 二、部署微协同服务


## 1、修改部署包目录文件

1、解压wx-private-deployment-package.zip文件，解压后应为这样



2、老的部署包解压后为这样



3、修改完毕后，保证jdk与wx-core-service这两个文件夹在同一层级




## 2、修改微协同服务启动端口

1、更改位于wx-core-service\conf目录下的server.xml



2、如果微协同服务地址为https的话，需要增加以下配置（增加配置后需要重启对应服务）

（如果忽略此步骤，微协同将无法正常配置成功！！！）

首先在nginx的nginx.conf中加入:

proxy_set_header X-Forwarded-Proto $scheme;


然后到\wx-core-service\conf目录下修改server.xml文件，添加：

注意：所加内容必须是放到Host标签下的第一个位置，如下图所示

    <Valve className="org.apache.catalina.valves.RemoteIpValve"
    remoteIpHeader="X-forwarded-For"
    protocolHeader="X-Forwarded-Proto"
    ProtocolHeaderHttpsValue="https"
    httpsServerPort="xxx"/> //当微协同地址的对应端口非443的时候，请加上此配置，并配置上对应的端口





## 3、环境配置（现在无需增加该配置，默认已经增加）

1.保证jdk与微协同包在同一目录下



2.wx-core-service/conf/server.xml 中ROOT目录配置



该目录下的server.xml，添加上。添加后应为下图配置




## 4、数据库（已有安装mysql，则新建数据库即可，必须是MySQL）

建议使用MySQL5.6或MySQL5.7版本，如果使用高版本的MySQL8.x可能会导致数据库超时断开连接而无法自动连接的异常，引发业务上的各种报错。

1.安装mysql，新建数据库名为wxt,字符集UTF-8，然后在客户端执行wx-private-deployment-package\sql-init\mysql路径下的seeyonwx.sql文件进行数据库初始化。



2.使用高版本的MySQL8.x的客户，需要将wx-core-service\webapps\ROOT\WEB-INF\lib该目录下的mysql-connector-java-8.0.20.jar注意替换为数据库对应的版本，参考前置条件中1.2.3。


## 5、修改hibernate.properties配置文件

1、文件中数据库配置，如下图：

\wx-core-service\webapps\ROOT\WEB-INF\classes\config\spring\hibernate.properties 或 \wx-core-service\webapps\ROOT\WEB-INF\classes\hibernate.properties





2、修改配置文件中的数据库账号密码、数据库连接地址、数据库名称、数据库连接url信息

useSSL=false&serverTimezone=Asia/Shanghai&

如果MySQL的版本是小于6的，配置文件中的信息需要做如下修改



如果MySQL的版本是大于6的，配置文件中的信息需要做如下修改：




## 6、修改sysinfo.properties配置文件

\wx-core-service\webapps\ROOT\WEB-INF\classes\sysinfo.properties

qyapi_url ：企业微信地址，若企业微信私有部署，写私有部署企业微信地址
wx_url ：微协同服务外网域名地址（切记要增加 http://或https://  若有端口号并且端口不等于80或443，则带上端口号，若等于80或443 则不带。例如：https://weixin.seeyon.com）
qyAdmin：设置登录名（后续登录微协同管理后台使用）
qyPassword：设置密码（后续登录微协同管理后台使用）





## 7、启动微协同服务

\wx-core-service\bin中，点击startup.bat启动



访问对应端口得到这个页面即表示启动正常




## 三、企业微信配置


## 1、创建自建应用



可见范围设置为全员


## 2、微协同数据库执行sql

1、首先，将下列的所有参数都获取到 【企业名称】、【CorpID】获取地方如下图



【应用AgentId】、【应用Secret】获取如下图



【OA对外地址】、【OA对外端口】获取如下图



【通讯录secret】获取如下图



若点开通讯录同步发现已托管给第三方，先点击取消同步



2、根据上述图例中的参数组装初始化SQL语句（需要注意的是，引号内的内容不要留有空格）

不想同步组织架构的客户可以不用填写 通讯录Secret信息，将其置为空即可。

INSERT INTO `WX_ACCOUNT` (`ID`, `WTYPE`, `APPSECRET`, `ACCOUNTNAME`, `XT_IP`, `XT_PORT`, `QY_TOKEN`,`AES_KEY`, `CORP_ID`, `AGENTID`, `QYSECRET`, `TEMPLATEID`)
VALUES ('zl8a83838d5aad2a0c01', 'wechat', '通讯录Secret', '企业名称', 'OA对外地址', 'OA对外端口号', 'caSzlxoMHvW5EOus8Q', 'zld2lGX7Xyd2KpDxo3540dRrUKrbMhgvwezlWNMm8XY', 'CorpID', '应用AgentId', '应用Secret', '1');


示例：

INSERT INTO `WX_ACCOUNT` (`ID`, `WTYPE`, `APPSECRET`, `ACCOUNTNAME`, `XT_IP`, `XT_PORT`, `QY_TOKEN`,`AES_KEY`, `CORP_ID`, `AGENTID`, `QYSECRET`, `TEMPLATEID`)
VALUES ('zl8a83838d5aad2a0c01', 'wechat', 'CUn2ql6WKJXFti0h_Ft7C7oCmtrWa-gd0n8XUnTQG2g', 'Leverage咨询公司', 'http://yanfa9.seeyon.com', '80', 'caSzlxoMHvW5EOus8Q', 'zld2lGX7Xyd2KpDxo3540dRrUKrbMhgvwezlWNMm8XY', 'ww5af1eeb8db0efb26', '1000025', 'LglgfvFynOgUUG61tlXBS7cLhpaLLp8t7gW-0cRtdGg', '1');



## 3、配置可信域名和可信IP

1、点开自建应用



2、**设置可信域名，如果微协同的对外域名带有端口号，这里可信域名要带上端口号，如果是443/80端口的话不要带上，若不是80或443则需要带上端口。请先点击【申请校验域名】，然后操作下一步，下载文件。**待下一步操作完毕后，域名校验则会通过。



3、将下载的txt认证文件放到 \wx-core-service\webapps\ROOT目录下



4、配置微协同服务的出口IP




## 四、管理端后台配置


## 1、微协同管理后台配置

https://weixin.seeyon.com/admin/loginIndex（域名替换成独立部署微协同服务器地址）

如下图：

用户名（sysinfo.properties设置的参数qyAdmin） 密码（sysinfo.properties设置的参数qyPassword）



点击创建菜单，输入执行SQL中的ID值（应为zl8a83838d5aad2a0c01），点击指定企业号菜单按钮



如果创建菜单的时候如果有“60020”的报错，需要参考3.3步骤，将提示的报错IP配置到企业微信后台-应用管理-企业可信IP处。




## 2、OA管理后台配置

登录集团管理员账号，点击【微协同管理平台】菜单，进入微协同基础设置页面，然后选择私有化部署，并填写对应微协同私有化地址，点击并校验通过



注意：协同服务器地址和微协同服务器地址必须都携带协议头和端口，端口后面不能携带任何斜杠和其他路由信息


## 3、设置应用主页

1、进入企业微信后台【应用管理】找到微协同所属的自建应用，在【自定义菜单】项中点击【已启用】



2、跳转页面如下所示，然后点击下图中红框标记处内容



3、跳转页面如下所示，然后再复制下图中红框标记处内容



4、进入企业微信后台【应用管理】找到微协同所属的自建应用，点击【应用主页】根据弹框页面提示将上一步复制的地址粘贴到该处




## 五、组织同步配置

私有化部署微协同后，若客户需要进行组织同步（同步是单向的，只能从OA->企业微信）。请先阅读微协同私有化部署-同步配置手册，进行相应的同步前配置，如果没有配置直接同步则一定会出问题。


## 六、消息配置

登录OA后台，按照下图所示进行配置即可



编撰人：het、tanghu、lichaoj


快速跳转



 * 微协同私有化部署手册-Windows版
   * 一、前置条件
     * 1、网络条件
     * 2、其他条件
     * 3、网络条件说明
   * 二、部署微协同服务
     * 1、修改部署包目录文件
     * 2、修改微协同服务启动端口
     * 3、环境配置（现在无需增加该配置，默认已经增加）
     * 4、数据库（已有安装mysql，则新建数据库即可，必须是MySQL）
     * 5、修改hibernate.properties配置文件
     * 6、修改sysinfo.properties配置文件
     * 7、启动微协同服务
   * 三、企业微信配置
     * 1、创建自建应用
     * 2、微协同数据库执行sql
     * 3、配置可信域名和可信IP
   * 四、管理端后台配置
     * 1、微协同管理后台配置
     * 2、OA管理后台配置
     * 3、设置应用主页
   * 五、组织同步配置
   * 六、消息配置



分享链接分享链接

## 56. 微协同私有化部署手册-Linux版

> 原始路径：`/1270/1298/1331/1096.html`  
> 相对路径：`1270/1298/1331/1096.md`  
> JS Chunk：`app.844f671c.js`

## 微协同私有化部署手册-Linux版


## 一、前置条件

私有化部署，需要满足如下条件：


## 1、网络条件

 1. 协同系统的访问地址是公网地址，可以是IP也可以是域名，域名的话最好是备案过的（避免企业微信校验为非法域名，禁止访问），OA在内网的客户可以使用反向代理，分离部署方案。
 2. 微协同服务和OA服务需要能够互相访问到。
 3. 微协同服务器地址必须为域名（企业微信配置可信域名使用到，私有化企业微信无限制），并且为公网地址。
 4. 微协同基础配置这里的校验是，OA和微协同服务能够互相访问到，双方互相访问成功后，OA会将rest账号密码推送至微协同服务（rest账号密码的作用就是获取访问OA的token，即是访问权限）。
 5. 用户通过企业微信APP/PC客户端访问微协同的时候，微协同先到企业微信中认证；再通过rest信息获取token到OA中认证，认证完毕后跳转至待办列表，后续的事项处理均是在OA中完成。
 6. OA同步组织架构、发送消息、配置菜单到企业微信的时候，会先将OA的数据推送至微协同，微协同在同步至企业微信。
 7. OA版本必须高于或等于8.0SP2版本才支持私有化部署。




## 2、其他条件

 1. 文件夹的层级目录不能有中文名称
 2. 微协同私有化部署仅和服务号（即是公众号）、企业微信、welink相关
 3. 微协同服务使用的数据库为MySQL，私有化部署包中数据库连接的jar包版本为5.1.38，如果客户使用更高版本的MySQL，请下载对应兼容版本的数据库连接jar包，然后放到该目录下：wx-core-service\webapps\ROOT\WEB-INF\lib。如下图所示（（如果忽略此步骤，微协同将无法启动！！！））。
 4. 建议使用MySQL5.6或MySQL5.7版本，如果使用高版本的MySQL8.x可能会导致数据库超时断开连接而无法自动连接的异常，引发业务上的各种报错。



5.**微协同访问地址以及OA访问地址如果是通过nginx配置的，那么请在nginx-conf配置文件中，将underscores_in_headers on配置信息加到http块中去即可。**可参考链接：https://blog.csdn.net/loongshawn/article/details/78199977

（如果忽略此步骤，微协同将无法收到消息！！！ 配置完毕后请在微协同基础配置处重新点击确定保存通过）

http {
    include       mime.types;
    default_type  application/octet-stream;

    #log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
    #                  '$status $body_bytes_sent "$http_referer" '
    #                  '"$http_user_agent" "$http_x_forwarded_for"';

    #access_log  logs/access.log  main;

    sendfile        on;
    #tcp_nopush     on;
    underscores_in_headers on; //增加此配置即可
    #keepalive_timeout  0;
    keepalive_timeout  65;



## 3、网络条件说明

请参考文档链接：

【微协同集成-网络配置】网络配置的必要条件说明 https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+NjI3


## 二、部署微协同服务


## 1、修改部署包目录文件

解压wx-private-deployment-package.zip文件，解压后应为这样



修改部署包目录文件名后如下展示




## 2、设置文件权限

将wx-core-service文件夹所有文件修改权限， 执行chmod -R 777 wx-core-service




## 3、修改微协同服务启动端口

更改位于\wx-core-service\conf目录下的server.xml



如果微协同服务地址为https的话，需要增加以下配置（增加配置后需要重启对应服务）

（如果忽略此步骤，微协同将无法配置成功！！！）

首先在nginx的nginx.conf中加入:

proxy_set_header X-Forwarded-Proto $scheme;


然后到\wx-core-service\conf目录下修改server.xml文件，添加：

注意：所加内容必须是放到Host标签下的第一个位置，如下图所示

    <Valve className="org.apache.catalina.valves.RemoteIpValve"
    remoteIpHeader="X-forwarded-For"
    protocolHeader="X-Forwarded-Proto"
    ProtocolHeaderHttpsValue="https"
    httpsServerPort="xxx"/> //当微协同地址的对应端口非443的时候，请加上此配置，并配置上对应的端口





## 4、数据库（已有安装mysql，则新建数据库即可，必须是MySQL）

建议使用MySQL5.6或MySQL5.7版本，如果使用高版本的MySQL8.x可能会导致数据库超时断开连接而无法自动连接的异常，引发业务上的各种报错。

jdk环境为当前Linux系统的JAVA_HOME

安装mysql，新建数据库名为wxt,字符集UTF-8，然后在客户端执行wx-private-deployment-package\sql-init\mysql路径下的seeyonwx.sql文件进行数据库初始化。

## 备注：

linux环境在/etc/my.cnf中的[mysqld]后添加添加如下配置，表名不区分大小写： lower_case_table_names=1


## 5、修改hibernate.properties配置文件

\wx-core-service\webapps\ROOT\WEB-INF\classes\config\spring\hibernate.properties 或 \wx-core-service\webapps\ROOT\WEB-INF\classes\hibernate.properties 文件中数据库配置，如下图：



如果MySQL的版本是小于6的，配置文件中的信息需要做如下修改：

useSSL=false&



如果MySQL的版本是大于6的，配置文件中的信息需要做如下修改：

useSSL=false&serverTimezone=Asia/Shanghai&




## 6、修改sysinfo.properties配置文件

\wx-core-service\webapps\ROOT\WEB-INF\classes\sysinfo.properties

qyapi_url ：企业微信地址，若企业微信私有部署，写私有部署企业微信地址
wx_url ：微协同服务外网域名地址（切记要增加 http://或https://  若有端口号并且端口不等于80或443，则带上端口号，若等于80或443 则不带。例如：https://weixin.seeyon.com）
qyAdmin：设置登录名（后续登录微协同管理后台使用）
qyPassword：设置密码（后续登录微协同管理后台使用）





## 7、启动微协同服务

\wx-core-service\bin中，运行./startup.sh启动



## 注：启动过程中出现此类报错提示找不到文件，请在wx-core-service下新建一个logs文件夹，执行命令mkdir logs



访问对应端口得到这个页面即表示启动正常




## 三、企业微信配置


## 1、创建自建应用



可见范围设置为全员


## 2、微协同数据库执行sql

1、首先，将下列的所有参数都获取到 【企业名称】、【CorpID】获取地方如下图



【应用AgentId】、【应用Secret】获取如下图



【OA对外地址】、【OA对外端口】获取如下图



【通讯录secret】获取如下图



若点开通讯录同步发现已托管给第三方，先点击取消同步



2、根据上述图例中的参数组装初始化SQL语句（需要注意的是，引号内的内容不要留有空格）

不想同步组织架构的客户可以不用填写 “通讯录Secret”，将其置为空即可（即是直接填写NULL，不需要引号）。

INSERT INTO `WX_ACCOUNT` (`ID`, `WTYPE`, `APPSECRET`, `ACCOUNTNAME`, `XT_IP`, `XT_PORT`, `QY_TOKEN`,`AES_KEY`, `CORP_ID`, `AGENTID`, `QYSECRET`, `TEMPLATEID`)
VALUES ('zl8a83838d5aad2a0c01', 'wechat', '通讯录Secret', '企业名称', 'OA对外地址', 'OA对外端口号', 'caSzlxoMHvW5EOus8Q', 'zld2lGX7Xyd2KpDxo3540dRrUKrbMhgvwezlWNMm8XY', 'CorpID', '应用AgentId', '应用Secret', '1');


示例：

INSERT INTO `WX_ACCOUNT` (`ID`, `WTYPE`, `APPSECRET`, `ACCOUNTNAME`, `XT_IP`, `XT_PORT`, `QY_TOKEN`,`AES_KEY`, `CORP_ID`, `AGENTID`, `QYSECRET`, `TEMPLATEID`)
VALUES ('zl8a83838d5aad2a0c01', 'wechat', 'CUn2ql6WKJXFti0h_Ft7C7oCmtrWa-gd0n8XUnTQG2g', 'Leverage咨询公司', 'http://yanfa9.seeyon.com', '80', 'caSzlxoMHvW5EOus8Q', 'zld2lGX7Xyd2KpDxo3540dRrUKrbMhgvwezlWNMm8XY', 'ww5af1eeb8db0efb26', '1000025', 'LglgfvFynOgUUG61tlXBS7cLhpaLLp8t7gW-0cRtdGg', '1');



## 3、配置可信域名和可信IP

1、点开自建应用



2、设置可信域名，如果微协同的对外域名带有端口号，这里可信域名要带上端口号，如果是443/80端口的话不要带上，若不是则需要带上。请先点击【申请校验域名】，然后操作下一步，下载文件。待下一步操作完毕后，域名校验则会通过。



3、将下载的txt认证文件放到 \wx-core-service\webapps\ROOT目录下



4、配置微协同服务的出口IP




## 四、管理端后台配置


## 1、微协同管理后台配置

https://weixin.seeyon.com/admin/loginIndex（域名替换成独立部署微协同服务器地址）

如下图：

用户名（sysinfo.properties设置的参数qyAdmin） 密码（sysinfo.properties设置的参数qyPassword）



点击创建菜单，输入执行SQL中的ID值（应为zl8a83838d5aad2a0c01），点击指定企业号菜单按钮



如果创建菜单的时候如果有“60020”的报错，需要参考3.3步骤，将提示的报错IP配置到企业微信后台-应用管理-企业可信IP处。




## 2、OA管理后台配置

登录集团管理员账号，点击【微协同管理平台】菜单，进入微协同基础设置页面，然后选择私有化部署，并填写对应微协同私有化地址，点击并校验通过



注意：协同服务器地址和微协同服务器地址必须都携带协议头和端口，端口后面不能携带任何斜杠和其他路由信息


## 3、设置应用主页

1、进入企业微信后台【应用管理】找到微协同所属的自建应用，在【自定义菜单】项中点击【已启用】



2、跳转页面如下所示，然后点击下图中红框标记处内容



3、跳转页面如下所示，然后再复制下图中红框标记处内容



4、进入企业微信后台【应用管理】找到微协同所属的自建应用，点击【应用主页】根据弹框页面提示将上一步复制的地址粘贴到该处




## 五、组织同步配置

私有化部署微协同后，若客户需要进行组织同步（同步是单向的，只能从OA->企业微信）。请先阅读微协同私有化部署-同步配置手册，进行相应的同步前配置，如果没有配置直接同步则一定会出问题。


## 六、消息配置

登录OA后台，按照下图所示进行配置即可



编撰人：het、tanghu、lichaoj


快速跳转



 * 微协同私有化部署手册-Linux版
   * 一、前置条件
     * 1、网络条件
     * 2、其他条件
     * 3、网络条件说明
   * 二、部署微协同服务
     * 1、修改部署包目录文件
     * 2、设置文件权限
     * 3、修改微协同服务启动端口
     * 4、数据库（已有安装mysql，则新建数据库即可，必须是MySQL）
       * 备注：
     * 5、修改hibernate.properties配置文件
     * 6、修改sysinfo.properties配置文件
     * 7、启动微协同服务
       * 注：启动过程中出现此类报错提示找不到文件，请在wx-core-service下新建一个logs文件夹，执行命令mkdir logs
   * 三、企业微信配置
     * 1、创建自建应用
     * 2、微协同数据库执行sql
     * 3、配置可信域名和可信IP
   * 四、管理端后台配置
     * 1、微协同管理后台配置
     * 2、OA管理后台配置
     * 3、设置应用主页
   * 五、组织同步配置
   * 六、消息配置



分享链接分享链接

## 57. 微协同私有化部署-同步配置

> 原始路径：`/1270/1298/1331/1098.html`  
> 相对路径：`1270/1298/1331/1098.md`  
> JS Chunk：`app.844f671c.js`

## 微协同私有化部署-同步配置

前提：私有化集成企业微信，需要将OA的组织架构同步到企业微信才需要配置，不需要同步可不必关注。


## 1、同步说明

由于企业微信方更改，导致微协同同步功能受到一定影响，因此微协同需要重新适配企业微信同步功能。那么当客户需要私有化部署微协同，并且需要同步功能的话。请运维同事在网盘上下载最新的私有化部署包（私有化部署包会在A8安装包中），即是A8安装包的build id必须是大于230531的，最好是只要有私有化部署就下载最新的安装包。因为微协同部署包兼容所有OA版本。用最新的总不会错。 如果是已经部署过了的客户，需要同步的话，就需要重新下载最新安装包，再次部署。




## 2、企业微信通讯录配置

1.登录企业微信后台（企业微信超级管理员扫码登录） 2.点击管理工具-通讯录同步



1.企业可通过接口或授权第三方服务商 这两种方式进行同步 2.如果客户通讯录同步方式为“第三方应用”，请取消同步。只有微协同公有云集成才会使用该方式 3.如果没有开启同步的话，请点击“开启接口同步”





1.开启接口同步后点击Secret右边的“查看”，然后保存该值，后续配置会使用到 2.企业可信IP的配置，是在应用管理下-客户私有化微协同的应用中-企业可信IP中所配置的（微协同私有化部署文档有说明），请配置微协同服务器的出口IP






## 3、企业微信应用配置

进入企业微信后台，找到微协同对应的自建应用，设置应用可见范围



选择企业微信组织架构的根部门即可




## 4、微协同数据库配置

根据私有化部署文档中的3.2项（微协同数据库执行sql），将刚刚保存的Secret值填入sql语句中。执行完毕后可以查看数据库wx_account表，表中APPSECRET的值就是Secret值。




## 5、企业微信后台配置

1.点击我的企业-通讯录管理-修改 2.添加自定义信息-名称填写“登录名”







1.点击通讯录-随意点击一个人员，可以看见成员详情中多了一个“登录名”的信息 2.同步前，需要将企业微信中现有人员的“登录名”全部配置上，并保证OA中的人员的登录名和企业微信中人员登录名一致（如果不一致，那么同步将有问题，因为人员信息对应不上），手机号也要一一对应上，不然也会有问题。





1.一个一个的配置比较麻烦，用户可以导出企业微信的通讯录和OA的通讯录，然后将登录名信息填写到企业微信通讯录中 2.然后在执行文件导入





1.所有操作执行完毕后，就可以开始同步了 2.登录OA后台-微协同管理平台-企业微信集成-组织机构同步



编撰人：het、tanghu


快速跳转



 * 微协同私有化部署-同步配置
   * 1、同步说明
   * 2、企业微信通讯录配置
   * 3、企业微信应用配置
   * 4、微协同数据库配置
   * 5、企业微信后台配置



分享链接分享链接

## 58. （项目化）企业微信直连

> 原始路径：`/1270/1298/1331/1959.html`  
> 相对路径：`1270/1298/1331/1959.md`  
> JS Chunk：`app.844f671c.js`

## （项目化）企业微信直连


## 一、前置条件

私有化部署，需要满足如下条件：


## 0、满足项目化支持条件

本场景实际是去“微协同私有化服务部署”的能力，将微协同私有化服务的能力全部合并到OA主系统中。

本场景支持：免绑定登录，消息推送

本场景不支持：手动绑定登录，人员同步

本场景涉及项目化定制开发额外投入成本，工作量10人天。


## 1、网络条件

 1. 协同系统的访问地址是公网地址，必须是域名，并且是备案过的（避免企业微信校验为非法域名，禁止访问），OA在内网的客户可以使用反向代理，分离部署方案。
 2. （不用手动创建rest账号） 微协同基础配置保存的时候，OA会将rest账号密码保存至oa数据库（rest账号密码的作用就是获取访问OA的token，即是访问权限）。
 3. qyapi.weixin.qq.com企业微信的接口地址，需要能在oa服务器访问到。


## 2、其他条件

 1. 微协同和微协同-私有化两个插件都需要安装

 2. 文件夹的层级目录不能有中文名称

 3. 微协同域名如果是通过nginx配置的，那么请在nginx-conf配置文件中，将underscores_in_headers on配置信息加到http块中去即可。可参考链接：https://blog.csdn.net/loongshawn/article/details/78199977

http {
    include       mime.types;
    default_type  application/octet-stream;

    #log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
    #                  '$status $body_bytes_sent "$http_referer" '
    #                  '"$http_user_agent" "$http_x_forwarded_for"';

    #access_log  logs/access.log  main;

    sendfile        on;
    #tcp_nopush     on;
    underscores_in_headers on; //增加此配置即可
    #keepalive_timeout  0;
    keepalive_timeout  65;


nginx配置 https://open.seeyoncloud.com/v5doc/142/1190/1957.html 在上面配置中还需在part.conf加入以下配置

location ~ /seeyon/wechat/content.do {
            proxy_pass http://seeyon_v5_cluster;
            proxy_set_header Host $host:$server_port;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
            proxy_redirect     off;
            proxy_connect_timeout 300;
            proxy_read_timeout 300;
            proxy_send_timeout 300;
        }

location ~ /seeyon/wechat/menu.do {
            proxy_pass http://seeyon_v5_cluster;
            proxy_set_header Host $host:$server_port;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
            proxy_redirect     off;
            proxy_connect_timeout 300;
            proxy_read_timeout 300;
            proxy_send_timeout 300;
        }

location ~ /seeyon/wechat/pcapp.do {
            proxy_pass http://seeyon_v5_cluster;
            proxy_set_header Host $host:$server_port;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
            proxy_redirect     off;
            proxy_connect_timeout 300;
            proxy_read_timeout 300;
            proxy_send_timeout 300;
        }


注意：如果oa的域名包含上下文，例如：http://oa.xxx.com/xxxx/seeyon 需要nginx添加配置，修改cookie_path，避免调用rest请求的时候不自动携带session

location /xxxx {
   proxy_pass http://backend_server;
   
   # 重写 Set-Cookie 路径
   proxy_cookie_path /seeyon /xxxx;
}



## 二、部署企业微信直连插件补丁


## 1、打上补丁


## 三、管理端后台配置


## 1、OA管理后台配置

登录集团管理员账号，点击【微协同管理平台】菜单，进入微协同基础设置页面，然后填写OA域名地址，点击并校验通过



注意：协同服务器地址必须携带协议头和端口，端口后面不能携带任何斜杠和其他路由信息


## 2、配置免绑定登录



如果使用工号进行免绑定，需要看下下面链接如何企业微信新增工号 https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+MjI1Mw==


## 四、企业微信配置


## 1、创建自建应用



可见范围设置为全员


## 2、oa数据库执行sql

1、首先，将下列的所有参数都获取到 【企业名称】、【CorpID】获取地方如下图



【应用AgentId】、【应用Secret】获取如下图



2、根据上述图例中的参数组装初始化SQL语句（需要注意的是，引号内的内容不要留有空格）

INSERT INTO wechat_account (ID,ACCOUNT_NAME,ACCOUNT_TYPE,CORP_ID,CORP_SECRET,AGENT_ID,CREATE_TIME,UPDATE_TIME,XT_ACCOUNT_ID,EXT_ATTR_1,EXT_ATTR_2,EXT_ATTR_3,EXT_ATTR_4,EXT_ATTR_5,EXT_ATTR_6,EXT_ATTR_7,EXT_ATTR_8,EXT_ATTR_9) VALUES (-1106654060436373475,'企业名称','wechat','CorpID','应用Secret','应用AgentId','2024-08-12 15:30:53.0','2024-08-12 15:30:53.0','协同单位id',NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL);


示例：

INSERT INTO wechat_account (ID,ACCOUNT_NAME,ACCOUNT_TYPE,CORP_ID,CORP_SECRET,AGENT_ID,CREATE_TIME,UPDATE_TIME,XT_ACCOUNT_ID,EXT_ATTR_1,EXT_ATTR_2,EXT_ATTR_3,EXT_ATTR_4,EXT_ATTR_5,EXT_ATTR_6,EXT_ATTR_7,EXT_ATTR_8,EXT_ATTR_9) VALUES (-1106654060436373475,'大海企业','wechat','ww23fb96004ea7ba94','rMlruSYL5Ma18JGHy3UEqpGcrduZUQRfoAicl2Y37qc','1000004','2024-08-12 15:30:53.0','2024-08-12 15:30:53.0','6543897130257368270',NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL,NULL);



## 3、配置菜单

1、主页菜单地址获取 替换{协议头}、{corpid}、{oa域名}、{oa端口}、{上一步插入sql的id}（注意是id，不是XT_ACCOUNT_ID）、{应用的agentid}，括号也一起替换 PS: oa域名不要协议头和端口 PS：http时，{协议头}替换成http，https时，{协议头}替换成https

https://open.weixin.qq.com/connect/oauth2/authorize?appid={corpid}&redirect_uri={协议头}%3A%2F%2F{oa域名}%3A{oa端口}%2Fseeyon%2Fwechat%2Fmenu.do%3Fmethod%3DgetMenu%26accountid%3D{上一步插入sql的id}&response_type=code&scope=snsapi_privateinfo&state=123&agentid={应用的agentid}#wechat_redirect


如果是443端口或者80端口，用下面链接替换

https://open.weixin.qq.com/connect/oauth2/authorize?appid={corpid}&redirect_uri={协议头}%3A%2F%2F{oa域名}%2Fseeyon%2Fwechat%2Fmenu.do%3Fmethod%3DgetMenu%26accountid%3D{上一步插入sql的id}&response_type=code&scope=snsapi_privateinfo&state=123&agentid={应用的agentid}#wechat_redirect


2、跳转链接获取 输入企业corpid点击生成应用url，复制地址

3、点击自定义菜单



4、新增两个菜单，一个主页，一个待办工作 5、填写名称和地址 地址就用1、2步的地址



6、配置完成两个菜单




## 4、配置可信域名和可信IP

1、点开自建应用



2、**设置可信域名，填写OA域名，要带上端口号，如果是443/80端口的话不带上端口。请先点击【申请校验域名】，然后操作下一步，下载文件。**待下一步操作完毕后，域名校验则会通过。 配置的目的是企业微信跳转自建应用的时候，跳转地址必须是这里配置的域名才能跳转。



3、将下载的txt认证文件放到 \ApacheJetspeed\webapps\ROOT目录下 这一步目的是企业微信验证域名的时候，会请求域名根目录下的txt文件来验证域名所属



4、配置oa服务的IP(内网地址外网地址都配上)

配置的目的是，oa调用企业微信接口获取数据的时候，调用方必须是配置里的ip才能成功调用。




## 5、设置应用主页

1、进入企业微信后台【应用管理】找到微协同所属的自建应用，点击【应用主页】根据弹框页面提示将地址粘贴到该处 （第三步配置菜单的第一步获取的主页地址）




## 五、消息配置

登录OA后台，按照下图所示进行配置即可




## 错误及解决方案

1、报错：”企业微信认证失败，请稍后再试“



解决：访问qyapi.weixin.qq.com不通，需要开通

2、基础设置保存报错weixin.label.noPlgin



解决：安装微协同-私有化插件

3、报错“JSONObject["open _userid"] not found”



解决，查看日志，获取ip，配置可信ip

4、报错“OA凭证异常，请检查微协同基础配置是否通过”



解决：基础配置重新报错一下，等2分钟后再试一下

5、移动端正常跳转，pc跳转在默认浏览器打开的时候卡住



原因：企业微信配置的可信域名是443/80端口的，跳转链接的时候自动去掉了端口号，导致跳转链接和配置的可信域名不一致，报错不是可信域名 解决：企业微信可信域名在端口号为443/80的时候不配置端口号

6、主页不想跳转allApps，想跳转自定义的菜单

解决：不设置主页地址

编撰人：zhangzuh、het、admin


快速跳转



 * （项目化）企业微信直连
   * 一、前置条件
     * 0、满足项目化支持条件
     * 1、网络条件
     * 2、其他条件
   * 二、部署企业微信直连插件补丁
     * 1、打上补丁
   * 三、管理端后台配置
     * 1、OA管理后台配置
     * 2、配置免绑定登录
   * 四、企业微信配置
     * 1、创建自建应用
     * 2、oa数据库执行sql
     * 3、配置菜单
     * 4、配置可信域名和可信IP
     * 5、设置应用主页
   * 五、消息配置
   * 错误及解决方案



分享链接分享链接

## 59. 微信服务号集成微协同

> 原始路径：`/1270/1298/1332/1103.html`  
> 相对路径：`1270/1298/1332/1103.md`  
> JS Chunk：`app.844f671c.js`

## 微信服务号集成微协同


## 1.1 前置条件

满足使用条件才可以进行私有化微信功服务号部署。

 1. 请确认协同系统可以与微协同系统网络互相联通，否则无法进行配置。
 2. 请确认微协同系统可以访问微信服务号，否则无法推送消息。
 3. 层级目录不能有中文名称。
 4. 协同系统的访问地址是公网地址，必须是备案的域名，OA在内网的客户可以使用反向代理，分离部署方案。
 5. 微协同服务器地址必须为备案的域名，端口为80或者443，且必须是公网地址。后续再配置该地址的时候，只需要配置域名即可，无需配置端口。（例如地址为：https://weixin.seeyon.com:443，那么只需要配置https://weixin.seeyon.com。无需配置端口。仅仅是微协同地址的配置，OA地址依然是正常配置需要携带端口）
 6. OA版本必须高于或等于8.0SP2版本才支持私有化部署。
 7. 私有化部署微协同仅支持服务号集成，不支持订阅号集成。
 8. 确认用户是什么类型服务，下面表示服务号。



 9. 微协同访问地址以及OA访问地址如果是通过nginx配置的，那么请在nginx-conf配置文件中，将underscores_in_headers on配置信息加到http块中去即可。 可参考链接：https://blog.csdn.net/loongshawn/article/details/78199977

（如果忽略此步骤，微协同将无法收到消息！！！ 配置完毕后请在微协同基础配置处重新点击确定保存通过）




## 1.1.1 网络条件说明

请参考文档链接：

【微协同集成-网络配置】网络配置的必要条件说明 https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+NjI3


## 1.2 部署微服务


## 1.2.1 微协同文件

解压wx-core-service.zip文件:




## 1.2.2 改名jdk和wx-core-service 文件夹名称

修改完毕后，保证jdk与wx-core-service这两个文件夹在同一层级



## 1.2.2.1 Linux环境

若为Linux环境，修改下wx-core-service文件夹所有文件权限， 执行chmod -R 777 wx-core-service




## 1.2.3 微服务端口配置

端口配置如需更改，修改\wx-core-service\conf目录下的server.xml。具体步骤如下：





如果微协同服务地址为https的话，需要增加以下配置（增加配置后需要重启对应服务）

（如果忽略此步骤，微协同将无法配置成功！！！）

首先在nginx的nginx.conf中加入:

proxy_set_header X-Forwarded-Proto $scheme;



然后到\wx-core-service\conf目录下修改server.xml文件，添加：

   <Valve className="org.apache.catalina.valves.RemoteIpValve"
    remoteIpHeader="X-forwarded-For"
    protocolHeader="X-Forwarded-Proto"
    ProtocolHeaderHttpsValue="https"
    httpsServerPort="xxx"/>


注意：所加内容必须是放到Host标签下的第一个位置，如下图所示




## 1.2.4 数据库配置

安装mysql，新建数据库wxt,字符集UTF-8，客户端执行seeyonwx.sql进行数据库初始化。

注意：

1.linux环境在/etc/my.cnf中的[mysqld]后添加添加如下配置，表名不区分大小写：

lower_case_table_names=1


2.微协同服务使用的数据库为MySQL，私有化部署包中数据库连接的jar包版本为5.1.38，如果客户使用更高版本的MySQL，请下载对应兼容版本的数据库连接jar包。wx-core-service\webapps\ROOT\WEB-INF\lib该目录下的mysql-connector-java-8.0.20.jar注意替换为数据库对应的版本。如下图所示，需要下载高版本的jar替换低版本的。




## 1.2.5 修改hibernate.properties

wx-core-service\webapps\ROOT\WEB INF\classes\hibernate.properties 文件中数据库配置，如下图：



如果MySQL的版本是小于6的，配置文件中的信息需要做如下修改：

useSSL=false&



如果MySQL的版本是大于6的，配置文件中的信息需要做如下修改：

useSSL=false&serverTimezone=Asia/Shanghai&




## 1.2.6 修改sysinfo.properties

\wx-core-service\webapps\ROOT\WEB-INF\classes\sysinfo.properties

qyapi_url ：企业微信地址，若企业微信私有部署，写私有部署企业微信地址。 wx_url ：微协同服务外网域名地址（切记要增加协议 http://或https:// 鉴于服务号的地址的端口只能是80或443，因此不需要配置端口。例如：https://weixin.seeyon.com，无端口配置 qyAdmin：设置登录名（后续登录微协同管理后台使用）。 qyPassword：设置密码（后续登录微协同管理后台使用。

注意：服务号配置参考：1.3.1 服务号开发信息配置到sysinfo




## 1.2.7 启动服务

\wx-core-service\bin中，点击startup.bat启动：



访问对应端口得到这个页面即表示启动正常：




## 1.3 微信服务号后端配置


## 1.3.1 微协同安装程序webapps\ROOT\WEB-INF\classes此路径下的sysinfo.properties文件配置微信公众号的appid和appsecret相应信息

下图中ip白名单配置微协同服务器的出口IP地址，并将appid和appsecret配置到sysinfo.properties文件中




## 1.3.2 微信公众号，配置功能设置以及安全域名

根据微信公众号的要求配置业务域名、JS接口安全域名、网页授权域名（此处注意域名和sysinfo.properties文件中的wx_url一致，但这里只写域名，不需要协议和端口）注意的是微协同服务是必须是80或者是https对应的443端口



1、业务域名：将微协同服务的地址填上后保存即可 2、JS接口安全域名：将微协同服务的地址填上后保存，并将该txt文件下载下来，放在微协同服务器微协同安装目录下webapps\ROOT下，然后启动微协同服务，然后关闭当前页



3、网页授权域名：将微协同服务的地址填上后保存




## 1.4 配置微信公众号菜单

微信公众号已有菜单：在原来的菜单上创建一个菜单，选择跳转网页：

https://open.weixin.qq.com/connect/oauth2/authorize?appid=APPID&redirect_uri=https://微协同地址/menuController/getMenu?accountid=&response_type=code&scope=snsapi_base&state=123#wechat_redirect

APPID：微信公众号的APPID

微协同地址: 微协同服务的地址





微信公众号没有菜单：微协同的后台管理中创建，也可以根据有菜单的情况创建




## 1.5 消息模板配置

1、公众号设置-账号详情-服务类目处，先添加"商业服务-企业管理"类目



2、如果没有开通模板消息，需要先开通，一般1-2天就可以了







3、在模板消息-类模板库中搜索“OA”模板名称，找到"OA系统流程审批通知"标题，进入详情进行配置。注意模板详情中的关键词展示顺序，一定要如图所示，不能多也不能少。





4、配置sysinfo.properties文件，将模板ID配置到mp_message_template_id参数项中,mp_message_template_title参数项配置oa_approval即可。保存后重启微协同服务即可生效。






## 1.6 配置OA后台

1、协同服务器地址为OA外网地址，请注意格式，端口后面不要携带 “/” 斜杠这些东西。默认端口为80或443的时候也需要填写上。

2、微协同服务器地址为微协同访问外网地址，请注意格式，端口后面不要携带 “/” 斜杠这些东西。默认端口为80或443的时候不需要填写上。（此处的地址与和sysinfo.properties文件中的wx_url一致，也和公众号后台配置的网页授权等地址一致，一模一样。）



编撰人：het、tanghu




快速跳转



 * 微信服务号集成微协同
   * 1.1 前置条件
     * 1.1.1 网络条件说明
   * 1.2 部署微服务
     * 1.2.1 微协同文件
     * 1.2.2 改名jdk和wx-core-service 文件夹名称
       * 1.2.2.1 Linux环境
     * 1.2.3 微服务端口配置
     * 1.2.4 数据库配置
     * 1.2.5 修改hibernate.properties
     * 1.2.6 修改sysinfo.properties
     * 1.2.7 启动服务
   * 1.3 微信服务号后端配置
     * 1.3.1 微协同安装程序webapps\ROOT\WEB-INF\classes此路径下的sysinfo.properties文件配置微信公众号的appid和appsecret相应信息
     * 1.3.2 微信公众号，配置功能设置以及安全域名
   * 1.4 配置微信公众号菜单
   * 1.5 消息模板配置
   * 1.6 配置OA后台



分享链接分享链接

## 60. 微协同-私有化安装包升级

> 原始路径：`/1270/1298/1343.html`  
> 相对路径：`1270/1298/1343.md`  
> JS Chunk：`app.844f671c.js`

## 微协同-私有化安装包升级


## 背景

微协同作为一个独立于OA的云服务，会经常性发版更新。不依赖于OA版本，但是会兼容所有的OA版本。**当有客户私有化部署微协同后，有升级OA版本的需求，那么此时，微协同私有化安装包也需要升级。**下述内容为升级微协同安装包的操作步骤。


## 操作步骤&解决方案


## 第一步 下载最新安装包

获取最新的微协同私有化安装包（根据包名的时间节点获取）。

链接: https://pan.baidu.com/s/17z6FQTOpRd4Wl2XMgKo7Mg

提取码: q5h9


## 第二步 拷贝最新安装包文件夹

备份客户当前微协同服务器wx-core-service整个文件夹，生成备份文件。

根据客户部署微协同的操作环境，获取最新安装包的wx-core-service文件夹（Linux或Win）。然后拷贝到客户现有微协同服务器对应的目录下，拷贝完毕后注意修改文件夹名称为“wx-core-service”。

新包目录展示



按照客户操作系统类型，拷贝对应文件夹



注意修改文件夹名称




## 第三步 信创环境更新（非信创请忽略）

参考信创环境私有化部署文档，先打上补丁包。




## 第四步 修改配置文件

1、修改wx-core-service\conf路径下的server.xml文件，参考旧包中的对应文件内容（修改服务启动端口、https相关配置。请仔细对比新旧文件的差异，理应至少包含旧文件内容。）。 信创环境无需配置server.xml文件。



注意事项：如果微协同地址是https，请参考微协同私有化手册的配置。



2、修改wx-core-service\webapps\ROOT\WEB-INF\classes路径下的sysinfo.properties文件，参考旧包中的对应文件内容（wx_url等信息。请仔细对比新旧文件的差异，理应至少包含旧文件内容。）。



3、修改wx-core-service\webapps\ROOT\WEB-INF\classes路径下的hibernate.properties文件，参考旧包中的文件内容（修改数据库连接配置。请仔细对比新旧文件的差异。）。



注意事项：1、如果mysql版本是高于6，请参考微协同私有化手册的配置。



注意事项：2、如果信创环境，请参考信创环境私有化部署文档。



4、如果客户数据库MySQL的版本是高版本（高于5.7），请删除wx-core-service\webapps\ROOT\WEB-INF\lib路径下的mysql-connector-java-5.1.38-bin.jar文件，然后将备份文件夹对应路径的mysql-connector-java开头的jar包复制到相应路径下。 信创环境无需配置。



5、旧包中wx-core-service\webapps\ROOT路径下应该有一个.txt文件，此文件是部署手册中在企业微信后台生成的然后放到该路径下的，因此需要将旧包中的该文件复制到对应路径下。




## 第五步 执行SQL文件（信创环境私有化部署微协同则忽略该步骤）

执行新包中wx-private-deployment-package\sql-update\mysql路径下的wxt-sql-update.sql文件。

注意：如果执行时有报错，请查看客户微协同数据库中是否已经存在了SQL文件中的表和字段，如果存在可不执行。




## 第六步 客开

如果微协同服务有客开，请联系客体侧同事申请微协同源码。参考私有化安装包的名称，源码对应分支与安装包名称中的时间一致，目前最新是20250610。


## 第七步 重启微协同服务

重启微协同服务，使用微协同看是否正常


## 备注

如果客户需要将OA的组织架构同步到企业微信，必须要先进行配置，参考文档如下：https://open.seeyoncloud.com/v5devCMP/1270/1298/1331/1098.html

编撰人：tanghu、het




快速跳转



 * 微协同-私有化安装包升级
   * 背景
   * 操作步骤&解决方案
     * 第一步 下载最新安装包
     * 第二步 拷贝最新安装包文件夹
     * 第三步 信创环境更新（非信创请忽略）
     * 第四步 修改配置文件
     * 第五步 执行SQL文件（信创环境私有化部署微协同则忽略该步骤）
     * 第六步 客开
     * 第七步 重启微协同服务
     * 备注



分享链接分享链接

## 61. 信创环境私有化集成部署手册

> 原始路径：`/1270/1298/1350.html`  
> 相对路径：`1270/1298/1350.md`  
> JS Chunk：`app.844f671c.js`

## 信创环境私有化集成部署手册


## 一、微协同支持的信创环境

         支持范围
OA产品版本   高于8.1SP2版本
中间件      东方通7.0.x、金蝶V9~V10、宝兰德V952~V955
数据库      达梦8、人大金仓V8 R3 R6、华为GaussDB、PG、海量vastbase


## 二、参考文档

微协同私有化部署集成信创环境，请先了解以下文档，以便后续步骤的配置。

描述                       链接
致远协同管理软件信创环境部署手册         https://open.seeyoncloud.com/#/faq/vuepressFile/v1/share?url=Z2ptZkplPjMxMjk=
宝兰德BES中间件（v952及v955版本）   https://open.seeyoncloud.com/#/faq/vuepressFile/v1/share?url=Z2ptZkplPjMxMjU=
微协同私有化部署手册               https://open.seeyoncloud.com/#/faq/vuepressFile/v1/share?url=Z2ptZkplPjIxOjc=


## 三、部署前置条件

 1. 协同系统的访问地址是公网地址，可以是IP也可以是域名，域名的话最好是备案过的（避免企业微信校验为非法域名，禁止访问），OA在内网的客户可以使用反向代理，移动分离部署方案。
 2. 微协同服务和OA服务需要能够互相访问到。
 3. 微协同服务器地址必须为域名（企业微信配置可信域名使用到，私有化企业微信无限制），并且为公网地址。
 4. 微协同域名如果是通过nginx配置的，那么请在nginx-conf配置文件中，将underscores_in_headers on配置信息加到http块中去即可。可参考链接：https://blog.csdn.net/loongshawn/article/details/781999771. （如果忽略此步骤，微协同将无法收到消息！！！）

http {
    include       mime.types;
    default_type  application/octet-stream;

    #log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
    #                  '$status $body_bytes_sent "$http_referer" '
    #                  '"$http_user_agent" "$http_x_forwarded_for"';

    #access_log  logs/access.log  main;

    sendfile        on;
    #tcp_nopush     on;
    underscores_in_headers on; //增加此配置即可
    #keepalive_timeout  0;
    keepalive_timeout  65;





## 四、安装数据库


## 4.1、达梦数据库安装配置（DM8版本）

可参考文档：致远协同管理软件信创环境部署手册-达梦安装配置，如下截图所示。



注意事项：在初始化数据库的时候，一定不要勾选“字符串比较大小写敏感”




## 4.2、人大金仓数据库安装配置（KingbaseES_V008R006C008B0014版本）

可参考文档：致远协同管理软件信创环境部署手册-人大金仓安装配置，如下截图所示。



> 注意事项： 默认字符集编码为：UTF8 默认数据库兼容模式为：MySQL 默认大小写敏感为：否




## 4.3、华为高斯数据库安装配置（项目化支持，建议使用B兼容模式）


## 4.4、PG数据库安装配置

可参考文档：Postgresql数据库安装参考手册，如下截图所示。




## 4.5、海量数据库安装配置

可参考文档：海量数据库项目化部署升级手册，如下截图所示。




## 4.6、执行数据库初始化语句

当数据库安装配置完毕后，在客户端执行wx-private-deployment-package\sql-init\dm路径下的seeyonwx.sql文件进行数据库初始化。不同的数据库，按照目录文件夹的名称选取文件执行。下图以达梦数据库为例。




## 五、部署微协同服务


## 5.1、修改部署包目录文件

1、解压wx-private-deployment-package.zip文件，解压后应为这样



2、修改完毕后，保证jdk与wx-core-service这两个文件夹在同一层级




## 5.2、打补丁包

微协同标准产品只适配于MySQL数据库，由于不同数据库之间无法兼容语法等原因。因此客户私有化信创部署时候，针对不同的数据库按照目录名称打上补丁包即可。




## 5.3、修改hibernate.properties配置文件

进入\wx-core-service\webapps\ROOT\WEB-INF\classes\hibernate.properties目录，修改hibernate.properties配置文件



## 5.3.1、达梦数据库配置

修改配置文件中达梦数据库的账户和口令，以及访问地址端口



## 5.3.2、人大金仓数据库配置

修改配置文件中人大金仓数据库的账号密码，以及访问地址端口和数据库名



## 5.3.3、华为高斯数据库配置

修改配置文件中华为高斯数据库的账号密码，以及访问地址端口和数据库名



## 5.3.4、PG数据库配置

修改配置文件中PG数据库的账号密码，以及访问地址端口和数据库名



## 5.3.5、海量数据库配置

修改配置文件中海量数据库的账号密码，以及访问地址端口和数据库名




## 5.4、修改sysinfo.properties配置文件

进入\wx-core-service\webapps\ROOT\WEB-INF\classes\sysinfo.properties目录，修改sysinfo.properties配置文件

qyapi_url ：企业微信地址，若企业微信私有部署，写私有部署企业微信地址
wx_url ：微协同服务外网域名地址（切记要增加 http://，若有端口号，要带上端口号）
qyAdmin：设置登录名（后续登录微协同管理后台使用）
qyPassword：设置密码（后续登录微协同管理后台使用）





## 5.5、部署应用

微协同应用目录为：wx-private-deployment-package\wx-core-service\wx-core-service\webapps\ROOT，根据下述中间件的配置文档，部署微协同服务的ROOT目录后，即可启动服务。



## 5.5.1、东方通部署应用

可参考文档：致远协同管理软件信创环境部署手册-东方通部署应用，如下截图所示。



## 5.5.2、金蝶部署应用

可参考文档：致远协同管理软件信创环境部署手册-金蝶部署应用，如下截图所示。



## 5.5.3、金蝶V10部署应用

可参考文档：致远协同管理软件信创环境部署手册-金蝶V10部署应用，如下截图所示。



## 5.5.4、宝兰德部署应用

可参考文档：致远协同管理软件信创环境部署手册-宝兰德部署应用，如下截图所示。




## 5.6、启动服务，访问地址

访问对应地址和端口得到这个页面即表示启动正常




## 六、企业微信配置


## 6.1、创建自建应用



可见范围设置为全员


## 6.2、微协同数据库执行应用初始化SQL

1、首先，将下述的所有参数都获取到，后续执行SQL会用到。 【企业名称】、【CorpID】获取地方如下图



【应用AgentId】、【应用Secret】获取如下图



【OA对外地址】、【OA对外端口】获取如下图



【通讯录secret】获取如下图



若点开通讯录同步发现已托管给第三方（如下页面所示），先点击取消同步，然后点击开启API接口同步



2、根据上述图例中的参数组装初始化SQL语句（需要注意的是，引号内的内容不要留有空格）

不想同步组织架构的客户可以不用填写 通讯录Secret信息，将其置为空即可。

下述SQL示例为达梦数据库，客户可根据wx-private-deployment-package\sql-init路径下的文件夹名，获取accountInsert.sql文件进行初始化。

INSERT INTO WX_ACCOUNT (ID, WTYPE, APPSECRET, ACCOUNTNAME, XT_IP, XT_PORT, QY_TOKEN, AES_KEY, CORP_ID, AGENTID, QYSECRET, TEMPLATEID)
VALUES ('zl8a83838d5aad2a0c01', 'wechat', '通讯录Secret', '企业名称', 'OA对外地址', 'OA对外端口号', 'caSzlxoMHvW5EOus8Q', 'zld2lGX7Xyd2KpDxo3540dRrUKrbMhgvwezlWNMm8XY', 'CorpID', '应用AgentId', '应用Secret', '1');


示例：

INSERT INTO WX_ACCOUNT (ID, WTYPE, APPSECRET, ACCOUNTNAME, XT_IP, XT_PORT, QY_TOKEN, AES_KEY, CORP_ID, AGENTID, QYSECRET, TEMPLATEID)
VALUES ('zl8a83838d5aad2a0c01', 'wechat', 'CUn2ql6WKJXFti0h_Ft7C7oCmtrWa-gd0n8XUnTQG2g', 'Leverage咨询公司', 'http://yanfa9.seeyon.com', '80', 'caSzlxoMHvW5EOus8Q', 'zld2lGX7Xyd2KpDxo3540dRrUKrbMhgvwezlWNMm8XY', 'ww5af1eeb8db0efb26', '1000025', 'LglgfvFynOgUUG61tlXBS7cLhpaLLp8t7gW-0cRtdGg', '1');



## 6.3、配置可信域名和可信IP

1、点开自建应用



2、设置可信域名，如果微协同的对外域名带有端口号，这里可信域名要带上端口号，如果是443/80端口的话也要带上。请先点击【申请校验域名】，然后操作下一步，下载文件。待下一步操作完毕后，域名校验则会通过。



3、将下载的txt认证文件放到 \wx-core-service\webapps\ROOT目录下



4、配置微协同服务的出口IP




## 七、管理端后台配置


## 7.1、微协同管理后台配置

https://weixin.seeyon.com/admin/loginIndex（请将域名替换为私有化微协同服务器的访问地址）

如下图：

用户名（sysinfo.properties设置的参数qyAdmin） 密码（sysinfo.properties设置的参数qyPassword）



点击创建菜单，输入执行SQL中的ID值（应为zl8a83838d5aad2a0c01），点击指定企业号菜单按钮



如果创建菜单的时候如果有“60020”的报错，需要参考6.3步骤，将提示的报错IP配置到企业微信后台-应用管理-企业可信IP处。




## 7.2、OA管理后台配置

登录集团管理员账号，点击【微协同管理平台】菜单，进入微协同基础设置页面，然后选择私有化部署，并填写对应微协同私有化地址，点击并校验通过



注意：协同服务器地址和微协同服务器地址必须都携带协议头和端口，端口后面不能携带任何斜杠和其他路由信息


## 7.3、设置应用主页

1、进入企业微信后台【应用管理】找到微协同所属的自建应用，在【自定义菜单】项中点击【已启用】



2、跳转页面如下所示，然后点击下图中红框标记处内容



3、跳转页面如下所示，然后再复制下图中红框标记处内容



4、进入企业微信后台【应用管理】找到微协同所属的自建应用，点击【应用主页】根据弹框页面提示将上一步复制的地址粘贴到该处




## 八、组织同步配置

私有化部署微协同后，若客户需要进行组织同步（同步是单向的，只能从OA->企业微信）。请先阅读微协同私有化部署-同步配置手册，进行相应的同步前配置，如果没有配置直接同步则一定会出问题。


## 九、消息配置

登录OA后台，按照下图所示进行配置即可




## 十、附录

获取最新的微协同私有化安装包。

链接: https://pan.baidu.com/s/1NSZymVeaikJ0Nxv5Ugys-A 提取码: qazw

编撰人：tanghu、het




快速跳转



 * 信创环境私有化集成部署手册
   * 一、微协同支持的信创环境
   * 二、参考文档
   * 三、部署前置条件
   * 四、安装数据库
     * 4.1、达梦数据库安装配置（DM8版本）
     * 4.2、人大金仓数据库安装配置（KingbaseES_V008R006C008B0014版本）
     * 4.3、华为高斯数据库安装配置（项目化支持，建议使用B兼容模式）
     * 4.4、PG数据库安装配置
     * 4.5、海量数据库安装配置
     * 4.6、执行数据库初始化语句
   * 五、部署微协同服务
     * 5.1、修改部署包目录文件
     * 5.2、打补丁包
     * 5.3、修改hibernate.properties配置文件
       * 5.3.1、达梦数据库配置
       * 5.3.2、人大金仓数据库配置
       * 5.3.3、华为高斯数据库配置
       * 5.3.4、PG数据库配置
       * 5.3.5、海量数据库配置
     * 5.4、修改sysinfo.properties配置文件
     * 5.5、部署应用
       * 5.5.1、东方通部署应用
       * 5.5.2、金蝶部署应用
       * 5.5.3、金蝶V10部署应用
       * 5.5.4、宝兰德部署应用
     * 5.6、启动服务，访问地址
   * 六、企业微信配置
     * 6.1、创建自建应用
     * 6.2、微协同数据库执行应用初始化SQL
     * 6.3、配置可信域名和可信IP
   * 七、管理端后台配置
     * 7.1、微协同管理后台配置
     * 7.2、OA管理后台配置
     * 7.3、设置应用主页
   * 八、组织同步配置
   * 九、消息配置
   * 十、附录



分享链接分享链接

## 62. 致远微协同-企业微信集成配置

> 原始路径：`/1270/1325/1326/1094.html`  
> 相对路径：`1270/1325/1326/1094.md`  
> JS Chunk：`app.844f671c.js`

## 致远微协同-企业微信集成配置


## 一、使用条件

 1. 您已申请了属于您企业自己的“企业号”或“企业微信”，并且已经通过“认证”
 2. 确认协同产品的版本为V5.1SP1-11月修复包及以上
 3. 确认协同系统的访问地址是公网地址，必须是备案过的域名，（企业微信/微信安全策略强制要求）
 4. 确认协同系统可以访问外网，否则无法推送消息
 5. 企业微信用户需要下载新的企业微信app，如想在微信中使用原来的企业号，企业微信管理员可以在企业号后台开启微信插件，关注微信插件即可
 6. OA后台微协同基础配置确认需要成功


## 二、执行第三方应用绑定操作

请登录集团管理员，点击菜单【微协同管理平台】【企业微信集成】【集成配置】进入配置页面，点击【开始安装并授权】按钮





使用已经绑定的企业微信管理员扫描二维码，在手机上进行授权登录

**注意：**如果是一个OA集成多个企业微信的话，按文档下述内容完成一个企业微信集成配置之后，请在企业微信后台点击退出登录，然后关闭浏览器页面。接着重新按照第二步骤开始另一个企业微信集成的配置。




## 关于腾讯企业号升级到企业微信的说明

腾讯将企业号于2020年6月强制升级成了企业微信，现在都是使用的企业微信。因此集成企业微信配置有部分页面和企业号不一致，但是原理雷同。

管理员扫码之后会跳转到应用授权界面，企业号客户和企业微信客户看到的界面分别为图一和图二

图一：



图二：



企业号勾选微协同，并点击下一步，如图一所示 企业微信可直接点击同意即可（可设置应用的可见范围，见下一步），如图二所示

图一：企业号用户界面



图二：企业微信用户界面：



企业号/企业微信均点击设置按钮，即可设置微协同应用的可见范围，全公司可见，则只点击最顶层目录即可。企业号客户和企业微信客户看到的界面分别为图一和图二。

图一：企业号用户界面



图二：企业微信用户界面：



配置完毕后点击授权安装/同意以上授权并添加。企业号客户和企业微信客户看到的界面分别为图一和图二。

图一：企业号用户界面



图二：企业微信用户界面：



点击“同意以上授权并添加”，系统提示成功后，会跳转到如下界面 如果用户需要同步OA的组织架构到企业微信，那么必须安装通讯录套件，如果不需要同步可不用安装。



此步骤用来授权通讯录管理套件来管理通讯录，不授权次套件您将无法使用为协同的同步功能。点击“绑定通讯录管理套件”之后您将进入如下界面:

企业号用户界面如下图：



企业微信客户如下图：



点击“授权管理通讯录”，系统提示成功后，会跳转到如下界面。（该页面无需任何操作，关闭即可。后续组织架构同步在OA后台中操作）



后续组织架构同步在OA后台微协同管理平台-企业微信集成-组织架构同步来操作。 1、CorpID的值填入企业微信id 2、同步集团的指定单位（用户可根据实际情况选择，选择否：即是OA的组织机构全部增量同步到企微中；选择是：即是弹出选人组件供用户选择单位同步。）（如果是一套OA集成多个企微，那么此处应该选择是，然后根据第一步填入的企微id，选择指定单位分别同步到不同的企业微信中。） 3、点击同步组织模型，待进度反馈完毕后则同步成功。




## 三、返回企业微信查看配置是否成功

此时返回您的企业号、企业微信管理页面，点击“通讯录”菜单，如果刚刚您同步了，此时您会看到OA中的组织模型已经在企业号/企业微信通讯录中建立了。点击企业号/企业微信中的“应用管理”菜单，此时您会在“第三方”中看到一个叫做“微协同”的应用，点击进入



进入此应用后，做如下操作 点击最上方的“修改”按钮，可以修改您的这个应用的描述和logo（根据您的需要修改，此步非必须）



如果授权了通讯录同步，查看下同步方式是否是第三方应用，服务商为致远云平台






## 四、协同配置

1、V7.0SP3以下协同版本，后台配置如下所示：

系统管理员，信息集成配置-微协同设置（A8）或功能应用设置-微协同设置（A6）。输入协同服务器地址，点击确认接口。（需要确保协同地址外网可以访问）



2、V7.0SP3及以上协同版本，后台配置如下所示： 集团/单位管理员，微协同管理平台-基础设置-微协同基础设置。输入协同服务器地址，点击确认接口。（需要确保协同地址外网可以访问）



3、SeeyonConfig配置： 运行SeeyonConfig配置工具（conf\SeeyonConfig.cmd） 在“系统参数设置”页签中，为internet.site.url项目配置您的协同公网访问地址



在“插件参数设置”页签中，将weixin.enable设置成1（V6.1SP2版本需要配置）



完成设置后需要重启协同系统


## 五、关注与使用

进入企业号，将“管理工具”中的“成员加入”里面的二维码通知给企业员工让其扫描关注，或者在这个页面下方开启“通过企业名称查找加入”，让企业员工在微信中搜索关注



请确认您之前已经完成了通讯录同步操作。员工关注后，“企业小助手”将会提示并引导其进行权限验证，验证通过后，即可看见“微协同”服务并开始使用。验证方式有三种：

 1. 一、如果员工“个人信息”中的手机号与微信绑定的企业号一致，即关注后可自动绑定，直接使用即可
 2. 二、输入“个人信息”中的手机号，手机会收到一个验证码短信，回复给“企业小助手”即可绑定成功
 3. 三、输入“个人信息”中的邮箱，邮箱会收到一个验证码邮件，回复给“企业小助手”即可绑定成功

注：有的员工可能在协同协同中既没有邮箱、也没有手机号信息，此时将无法授权绑定，要求其在协同系统中添加信息后，会自动同步到微信通讯录，再使用其邮箱或手机验证即可


## 六、快捷应用配置


## 1、企业微信后台新创建一个自建应用，填写对应信息




## 2、OA企业微信集成——>工作台设置——>pc端应用——>填写信息（8.0SP2和8.1版本适用）




## 3、OA企业微信集成——>工作台设置——>pc端应用——>填写信息（非8.0SP2和8.1版本适用）




## 4、复制OA生成的pc应用主页地址到企业微信自建应用中——>配置自建应用的网页授权及JS-SDK（地址是OA地址加端口）




## 七、版本功能确认

8.0版本之前,企业微信不支持PC端底导航打开,不支持pc应用内消息穿透; 8.0-8.1版本.企业微信不支持PC端底导航打开,支持pc应用内消息穿透; 8.1SP1版本及以后,企业微信支持PC端底导航打开和pc应用内消息穿透。

编撰人：het、tanghu、puwb


快速跳转



 * 致远微协同-企业微信集成配置
   * 一、使用条件
   * 二、执行第三方应用绑定操作
     * 关于腾讯企业号升级到企业微信的说明
   * 三、返回企业微信查看配置是否成功
   * 四、协同配置
   * 五、关注与使用
   * 六、快捷应用配置
     * 1、企业微信后台新创建一个自建应用，填写对应信息
     * 2、OA企业微信集成——>工作台设置——>pc端应用——>填写信息（8.0SP2和8.1版本适用）
     * 3、OA企业微信集成——>工作台设置——>pc端应用——>填写信息（非8.0SP2和8.1版本适用）
     * 4、复制OA生成的pc应用主页地址到企业微信自建应用中——>配置自建应用的网页授权及JS-SDK（地址是OA地址加端口）
   * 七、版本功能确认



分享链接分享链接

## 63. 企业微信接口许可购买及账号激活操作说明

> 原始路径：`/1270/1325/1326/1266.html`  
> 相对路径：`1270/1325/1326/1266.md`  
> JS Chunk：`app.844f671c.js`

## 企业微信接口许可购买及账号激活操作说明


## 一、企业微信接口许可购买


## （一）订单发起

客户/渠道经理按照直销、分销客户分别发起“直销销售订单”、“分销销售订单”续约企业微信平台接口调用许可，订单信息如下图：



注：必须在致远互联下单购买企业微信平台接口许可。


## （二）涉及业务流程（直销分销客户流程一致，例举直销流程）

## 1、直销销售订单：商务“生产专员”节点处理提交后自动触发“企业微信平台订货单”流程。



## 2、企业微信平台订货单流程

（1）自动触发至订单发起人待办事项中，提交流程时需要提供客户企业微信Corp ID，查询方法如下：

登录“企业微信管理员”账号，点击“我的企业”—企业信息中查看对应的企业ID：



（2）订货单流程节点说明：



“SH商务审核员”节点：处理后会自动将订单信息同步至企业微信后台。 “徐晓丽”节点：创建企业微信订单的付款码。 “出纳对公（王叶琴）”节点：即为财务付款，节点处理后客户企业微信接口许可数生效。


## 二、账号激活


## （一）操作流程图说明



注意： 1、用户OA系统中已经安装部署企业微信微协同应用。 2、必须是用户企业微信管理员才能进行操作。 3、用户需要提前通过致远商务下单购买企微账号激活数。 4、购买企业微信接口许可数的订单可在管理企业微信账号—订单列表中查看，包含下单时间、购买数量以及截至时间等信息。




## （二）登录账号管理平台方法

## 1、7.x及其以上版本OA用户

（1）管理员登录集团管理员后，进入企业微信集成的**【集成配置】界面并点击【开始安装和授权】**按钮，如下图：



（2）在弹出界面，点击**【管理企业微信账号】**，如下图：



（3）在弹出的二维码，使用企业微信的扫码进入（企业微信超级管理员）：



## 2、7.x以下版本用户

（1）浏览器中输入微协同官网地址：https://weixin.seeyon.com

（2）点击企业号的**【开始绑定】**，如下图：



（3）进入到操作页面，点击**【管理企业微信账号】**按钮：



（4）在弹出的二维码，使用企业微信的扫码进入（注：登录的账号必须是企业微信超级管理员）：




## （三）账号激活操作说明

## 1、选择账号激活操作



## 2、导入激活

（1）企业微信管理员先到企业微信后台将导出通讯录（导出企业微信整个组织架构），也可以选择具体的部门导出。



（2）点击“导入激活”按钮，在弹出页面中上传文件，将导出的通讯录文件导入到账号管理平台（下载下来的文件模板不能更改，只能是删减人员行数）





## 3、自动激活账号：分不自动激活、全部自动激活账号、按组织自动激活账号



（1）不自动激活账号，则采用选择账号激活、导入激活操作。 （2）全部自动激活不需要同步组织架构 。 （3）按照组织自动激活需要同步OA系统组织架构。

其中按组织自动激活具体操作方法如下：

1）企业微信必须将通讯录授权给致远云平台





2）OA至少需要进行一次手动同步，方便后续OA新增人员能自动同步到企业微信，并自动激活账号。



3）OA需要开启监听组织变化，开启后OA新增人员才能自动同步到企业微信，并自动激活。




## 三、常见问题说明


## 1、接口调用许可

接口调用许可即是拥有调用企业微信接口的权限，企业微信将此权限和企业微信中人员相绑定，如果没有接口调用权限，那么用户在使用微协同应用时会提示“应用无法使用”。（注：客户购买多少个接口调用许可，只需参考企业微信通讯录人数，大概有多少人需要使用微协同，即购买多少） 人员和权限的绑定，就是通过账号激活操作来完成的。那么就可以理解为接口调用许可就是激活码。只有激活了的人员，才有权限使用微协同应用。 接口调用许可是将企业微信人员激活，激活后人员就有权限使用微协同应用，跟OA没有任何关系。 未激活的人员有如下表象：消息收不到、企业微信工作台点击应用提示“应用无法使用”，组织架构同步不会受影响(企业微信文档中未有此限制说明)。


## 2、应用可见范围





（1）通讯录范围不用设置，设置了的取消其配置即可。 （2）应用可见范围，即是在企业微信工作台是否有权限展示该应用，在应用可见范围内展示，不再则不展示。人员账号激活，与该范围紧密相关。 不需要使用微协同的人员，请不要设置其应用范围可见，避免后续激活操作中激活失误需要释放等等问题。

应用可见范围可以设置部门、成员或者标签。相关配置有如下场景：

1、企业微信全员使用微协同，那么应用可见范围设置为企业微信根部门即可。此时人员激活就建议客户设置为全部自动激活，开启全部自动激活后，企业成员使用应用时、推送消息时将自动激活许可，人员离职的时候激活码将自动释放。前提是客户购买的接口许可数要大于等于企业微信通讯录人员数。





2、企业微信部分成员使用微协同，那么应用可见范围客户就按需配置即可。客户可以配置部分部门的成员使用、特定的人员使用、不同部门下的部分人员（标签中的人员在企业微信内，可以属于不同的部门，方便客户人员较多但部分人员使用的场景）。此时人员激活就建议客户通过列表选择激活或者是导入激活。




## 3、激活码释放

激活码释放目前的方法有两个。一是将人员移出应用可见范围；二是企业微信将该人员做离职处理，激活码就会释放。如果开启了监听同步，在OA端做离职处理也是可以的，OA人员离职也会触发企业微信人员离职（注：企业微信人员离职的话，聊天记录、群等等都会消失）。

（1）**开启自动激活后，企业微信成员离职或者是移出应用可见范围，那么激活码第二天凌晨就能更新其状态；**如果没开自动激活，那么就需要通过继承的方式来释放激活码。 开启自动激活的客户，无需关注账号列表人员激活的情况，离职自动释放了，新入职使用时又自动激活。 注意：上述方案必须是在开启自动激活的前提下，才会生效。未开启自动激活无法释放激活码



（2）非自动激活时，激活码释放的各个场景说明：

a、企业微信管理员操作人员离职，账号列表中“企业微信账号”数量减一，可激活数量加一，列表展示激活状态还是已激活状态。如果是OA操作人员离职同步到企业微信，那么列表搜索不到该用户；如果只是企业微信操作人员离职，那么列表依然能搜索到该用户。 b、企业微信管理员操作人员移出应用可见范围，账号列表中“企业微信账号”数量减一，可激活数量加一，列表展示激活状态还是已激活状态，列表依然能搜索到该用户。 客户疑惑点在于，数量已经加一了，但是列表搜索状态还是已经激活的状态（目前现状如下，后期可能会优化）。原因是未开启自动激活，离职或者是移出应用可见范围后，人员A和激活码的真实绑定状态没有改变，账号列表只是先把数量给释放出来了，后续新入职人员B，将B激活的时候，就会使用人员A的激活码来激活人员B（B继承A的激活码）。成功激活后，B变为已激活，A变为未激活。




## 4、账号列表

企业微信账号：应用可见范围的人数； 企微账号：企业微信人员账号（通讯录-人员头像右边）； 已经绑定过了微协同的人员才会展示名称、部门、手机号、协同账号（OA登录名）； 通讯录授权给了致远云平台的企业微信，未绑定微协同，名称这列会展示人员的姓名； 要准确搜索的话，可以使用企微账号来搜索。





编撰人：tanghu、het




快速跳转



 * 企业微信接口许可购买及账号激活操作说明
   * 一、企业微信接口许可购买
     * （一）订单发起
     * （二）涉及业务流程（直销分销客户流程一致，例举直销流程）
       * 1、直销销售订单：商务“生产专员”节点处理提交后自动触发“企业微信平台订货单”流程。
       * 2、企业微信平台订货单流程
   * 二、账号激活
     * （一）操作流程图说明
     * （二）登录账号管理平台方法
       * 1、7.x及其以上版本OA用户
       * 2、7.x以下版本用户
     * （三）账号激活操作说明
       * 1、选择账号激活操作
       * 2、导入激活
       * 3、自动激活账号：分不自动激活、全部自动激活账号、按组织自动激活账号
   * 三、常见问题说明
     * 1、接口调用许可
     * 2、应用可见范围
     * 3、激活码释放
     * 4、账号列表



分享链接分享链接

## 64. 致远微协同-钉钉集成配置

> 原始路径：`/1270/1325/1327/1099.html`  
> 相对路径：`1270/1325/1327/1099.md`  
> JS Chunk：`app.844f671c.js`

## 致远微协同-钉钉集成配置


## 一、使用条件

 1. 请确认协同产品的版本为V6.1SP2及以上（A6、A8、G6均支持）。
 2. 请确认协同系统的访问地址（IP）是公网地址。
 3. 请确认协同系统可以访问外网，否则无法推送消息。
 4. 已申请开通企业钉钉并通过认证（未认证的钉钉无法使用组织同步功能）。
 5. OA服务器需能访问到钉钉的API接口地址“oapi.dingtalk.com”、“api.dingtalk.com”，如果无法访问到，需要配置DNS域名解析。为保证配置后能够正常使用微协同，请务必在OA服务器上ping通上述两个地址，并且配置下DNS解析。必须要保证OA能够访问这两个地址。


## 二、钉钉后台配置


## 1、登录【钉钉开放平台】

访问地址：https://open.dingtalk.com， 然后点击开发者后台，通过钉钉管理员扫码登录




## 2、获取CorpId

另外点击资源管理可以看到，付费 API 调用量的相关信息。根据钉钉政策，普通版钉钉集成微协同后，每月只有1W条消息可以收到，只有升级钉钉版本才能收到更多的消息。因此出现钉钉收不到消息的时候可以到此处排查。




## 3、创建自建应用并获取应用凭证相关信息AgentId、AppKey、AppSecret




## 4、配置接口权限

接口权限的配置必须按照下述说明进行配置，如果有不一样的地方，会出问题会出问题会出问题










## 5、应用发布

发布并设置可使用范围，只有在范围内的人员才可以在钉钉的工作台中看到当前应用（默认在未分组应用中）




## 三、【协同OA】配置


## 1、V6.1SP2

登录系统管理员，在《信息集成配置》-《微协同平台》（A8）或《功能应用设置》-《微协同平台》（A6），按页面中说明依次完成以下步骤：

 1. 微协同基础设置
 2. 微协同连接设置（如果打过最新月度包，则可选）
 3. 钉钉集成配置
 4. 钉钉组织机构同步（可选）




## 2、V7.X-V8.0

A8集团版：登录集团管理员，在《微协同管理平台》， A8企业版：登录单位管理员，在《微协同管理平台》， A6：登录系统管理员，在《微协同管理平台》， 按页面中说明依次完成以下步骤：

 1. 微协同基础设置
 2. 微协同连接设置（如果打过最新月度包，则可选）
 3. 钉钉集成配置
 4. 钉钉组织机构同步（可选）




## 3、V8.0及其以上

1、填充相关参数后，点击确定按钮，提示成功后即可，如果不成功，可以先排查OA地址外网是否可以访问；如有内网环境与外网环境映射，请确保OA能够访问微协同（可以OA服务器通过curl -I https://weixin.seeyon.com看是否成功，如果是unknownhost，则在OA服务器上多次ping weixin.seeyon.com该域名，不同地区会返回不同ip地址，请以实时测试返回的ip地址为准，配置host文件）；还需要确保微协同环境能够访问OA环境，请在OA访问策略配置白名单（微协同服务器出口ip:59.110.227.61）。




## 四、OA后台配置


## 1、进入OA后台钉钉集成——>集成配置,新建绑定，把对应的信息填充好后点击提交按钮，检测通过后会自动回填"钉钉开发管理"的配置信息

注： 1、目前钉钉集成都使用AppKey和AppSecret的模式 2、只有OA版本满足8.1SP1及其以上，才会生成应用首页和PC端首页地址



3、8.2版本及其以上支持钉钉待办集成，开启该配置即可

注意：受钉钉待办API限制，钉钉待办集成仅支持集成一个钉钉，当集成配置多个钉钉时，无法推送待办。




## 2、回到钉钉后台回填数据，配置完成后重新发布应用，即可完成集成配置

注： 1、无需在开发管理处配置服务器出口IP 2、8.1SP1版本以下钉钉集成配置应用首页地址为：OAURL/seeyon/wechat/dingding.do?method=newIndex&corpId=CorpID，其中OAURL为OA协同服务器地址，CorpID为刚刚获取的CorpID值。




## 五、使用微协同

集成配置完毕后，用户需要打开钉钉APP，找到对应的钉钉应用。点击此应用（首次点击时会跳转到绑定的页面），此时用户输入OA的登录名和密码完成绑定。 绑定完成后再次点击应用即可成功登录微协同并使用。


## 六、OA后台工作台配置（快捷应用配置，直接穿透到具体的应用详情页）


## 1、OA后台钉钉配置——>工作台设置——>输入钉钉企业corpId——>生成url——>将对应地址复制到钉钉自建应用（V8.1SP1之后）

注：此功能的作用是配置快捷应用跳转，直接穿透到应用页面，无需再登录到微协同进行操作。只需要按照上述文档在钉钉后台创建一个H5微应用，然后在开发管理处配置下图中所生成的地址即可



编撰人：het、tanghu


快速跳转



 * 致远微协同-钉钉集成配置
   * 一、使用条件
   * 二、钉钉后台配置
     * 1、登录【钉钉开放平台】
     * 2、获取CorpId
     * 3、创建自建应用并获取应用凭证相关信息AgentId、AppKey、AppSecret
     * 4、配置接口权限
     * 5、应用发布
   * 三、【协同OA】配置
     * 1、V6.1SP2
     * 2、V7.X-V8.0
     * 3、V8.0及其以上
   * 四、OA后台配置
     * 1、进入OA后台钉钉集成——>集成配置,新建绑定，把对应的信息填充好后点击提交按钮，检测通过后会自动回填"钉钉开发管理"的配置信息
     * 2、回到钉钉后台回填数据，配置完成后重新发布应用，即可完成集成配置
   * 五、使用微协同
   * 六、OA后台工作台配置（快捷应用配置，直接穿透到具体的应用详情页）
     * 1、OA后台钉钉配置——>工作台设置——>输入钉钉企业corpId——>生成url——>将对应地址复制到钉钉自建应用（V8.1SP1之后）



分享链接分享链接

## 65. 致远微协同 - 飞书集成配置

> 原始路径：`/1270/1325/1328/1100.html`  
> 相对路径：`1270/1325/1328/1100.md`  
> JS Chunk：`app.844f671c.js`

## 致远微协同 - 飞书集成配置


## 一、使用条件

1、用户需要先注册飞书(根据OA系统登记的手机号):https://ep8jgutfa0.feishu.cn/create/

2、下载PC端飞书:https://www.feishu.cn/download

3、若只是测试环境配置，请客户申请一个测试OA环境以及测试飞书企业进行配置。切记不能使用生产飞书企业，不然后续会产生一系列业务问题。


## 二、OA后台微协同基础配置和致飞基础设置

1、填充相关参数后，点击确定按钮，提示成功后即可，如果不成功，可以先排查OA地址外网是否可以访问；如有内网环境与外网环境映射，请确保OA能够访问微协同（可以OA服务器通过curl -I https://weixin.seeyon.com看是否成功，如果是unknownhost，则在OA服务器上多次ping weixin.seeyon.com该域名，不同地区会返回不同ip地址，请以实时测试返回的ip地址为准，配置host文件）；还需要确保微协同环境能够访问OA环境，请在OA访问策略配置白名单（微协同服务器出口ip:59.110.227.61）。

2、填充相关参数后，点击确定按钮，提示成功后即可。 注意事项：8.1SP2版本以前有致飞插件，页面如下。8.1SP2版本及其以后，将致飞插件合并到了微协同插件，因此只要微协同基础配置通过即可。



3、微协同基础配置那通过，说明微协同跟oa服务网络已互通。但是若是oa要跟飞书集成，oa服务器还必须能访问到https://open.feishu.cn 地址。

4、oa访问飞书api地址报连接超时异常，可能是无法解析飞书的域名。客户网管可以对 https://www.feishu.cn、https://open.feishu.cn 这两个域名做下dns解析，并且让oa服务能访问到这个两个地址。为保证配置后能够正常使用微协同，请务必在OA服务器上ping通上述两个地址，并且配置下DNS解析。必须要保证OA能够访问这两个地址。


## 三、获取企业编码(CorpId)

1、登录PC端飞书，左上角人员头像——>管理后台———>首页(右侧的"企业信息"板块里面的"企业编号")

2、或者是登录飞书管理后台-点击左侧“企业设置”菜单-再点击“企业信息”菜单




## 四、飞书后台创建应用（优先创建 "致远协同" ）

进入"飞书管理后台"——>工作台——>应用管理——>右侧页面创建应用。

然后点击创建企业自建应用




## 五、获取应用AppId、AppSecret(后续会在OA后台的集成配置里面使用)

点击第四步所创建的致远协同应用，复制应用凭证下的App ID和App Secret。




## 六、进入OA的后台飞书集成——>集成配置——>新建绑定，把对应的信息填充好后点击提交按钮，检测通过后会自动回填"飞书主页配置"的配置信息



只有配置“致远协同”应用，并且通过致远协同应用绑定微协同后，才会收到消息，配置其他的应用或通过其他应用无法收到消息。



##七、回填飞书后台应用相关地址 飞书开放平台有所升级，需要用户自行添加应用能力。请添加网页应用和机器人即可

配置移动和PC应用主页地址




## 八、启动机器人




## 九、安全设置

点击开放平台左侧菜单“安全设置”---->配置重定向URL



点击开放平台左侧菜单“安全设置”---->配置H5可信域名




## 十、权限管理

权限的配置必须按照下述说明进行配置，如果有不一样的地方，会出问题会出问题会出问题。



组织架构授权会提示配置数据范围（选择全部）



下述截图红色框中的权限都必须要开启







授权完毕后不会立马生效，需要应用发布后才会生效。当应用发布后确认此处应该有以下业务模块的授权。




## 十一、版本管理与发布

发布并设置可使用范围(必须"所有员工")




## 十二、管理员审核发布的应用

应用发布后，待管理员审核完毕即可完成集成配置。



集成配置完毕后，用户需要打开飞书APP，找到对应的飞书应用。点击此应用（首次点击时会跳转到绑定的页面），此时用户输入OA的登录名和密码完成绑定。 绑定完成后再次点击应用即可成功登录微协同并使用。

移动端登录微协同后跳转至全部应用页面 PC端点击应用展示页面如下



##十三、常见配置问题说明


## 1、移动端页面修改：目前飞书集成配置默认跳转页面为全部应用，且页面下没有底导航展示。

要想有底导航展示的话，请修改飞书开发平台-网页应用-移动端主页地址




## 2、如果客户方需要使用审批集成，那么请先同步下组织架构，然后在配置审批。

即是在集成配置完成之后，在下方页面选择“致远协同”进行组织架构同步




## 3、很多用户在配置完集成后，又需要删除并重新配置。这时候就会出现各种各样的问题，例如删除失败、删除后重新创建发现使用不了、收不到消息等等问题。

如果需要删除的话，请按照以下步骤一步一步的操作，顺序不能乱。 1.删除集成配置

2.进入飞书管理后台-工作台-应用管理-已安装应用下搜索需要删除的应用-将应用停用。 停用后在进入飞书开发平台-找到该应用删除即可

3.进入OA数据库，找到如下几张表，将数据全部删除即可，删除后需要重启下OA，因为有数据缓存。 wechat_user和wechat_department表数据全部删除

4.数据删除完毕后即可开始重新配置

编撰人：het、tanghu、zhuling




快速跳转



 * 致远微协同 - 飞书集成配置
   * 一、使用条件
   * 二、OA后台微协同基础配置和致飞基础设置
   * 三、获取企业编码(CorpId)
   * 四、飞书后台创建应用（优先创建 "致远协同" ）
   * 五、获取应用AppId、AppSecret(后续会在OA后台的集成配置里面使用)
   * 六、进入OA的后台飞书集成——>集成配置——>新建绑定，把对应的信息填充好后点击提交按钮，检测通过后会自动回填"飞书主页配置"的配置信息
   * 八、启动机器人
   * 九、安全设置
   * 十、权限管理
   * 十一、版本管理与发布
   * 十二、管理员审核发布的应用
     * 1、移动端页面修改：目前飞书集成配置默认跳转页面为全部应用，且页面下没有底导航展示。
     * 2、如果客户方需要使用审批集成，那么请先同步下组织架构，然后在配置审批。
     * 3、很多用户在配置完集成后，又需要删除并重新配置。这时候就会出现各种各样的问题，例如删除失败、删除后重新创建发现使用不了、收不到消息等等问题。



分享链接分享链接

## 66. 致远微协同 - 飞书审批集成配置

> 原始路径：`/1270/1325/1328/1101.html`  
> 相对路径：`1270/1325/1328/1101.md`  
> JS Chunk：`app.844f671c.js`

## 致远微协同 - 飞书审批集成配置


## 一、使用条件

1、用户需要先注册飞书(根据OA系统登记的手机号):https://ep8jgutfa0.feishu.cn/create/

2、下载PC端飞书:https://www.feishu.cn/download

3、配置审批前，请先完成集成配置，然后在配置审批

4、如果需要使用审批分组，需要进行组织架构同步才能配置审批分组

5、审批集成配置需要在飞书开放平台中另外新建一个应用，不能和集成配置使用同一个应用


## 二、OA后台微协同基础配置和致飞基础设置

1、填充相关参数后，点击确定按钮，提示成功后即可，如果不成功，可以先排查OA地址外网是否可以访问；如有内网环境与外网环境映射，请确保OA能够访问微协同（可以OA服务器通过curl -I https://weixin.seeyon.com看是否成功，如果是unknownhost，则在OA服务器上多次ping weixin.seeyon.com该域名，不同地区会返回不同ip地址，请以实时测试返回的ip地址为准，配置host文件）；还需要确保微协同环境能够访问OA环境，请在OA访问策略配置白名单（微协同服务器出口ip:59.110.227.61）。

2、填充相关参数后，点击确定按钮，提示成功后即可。 注意事项：8.1SP2版本以前有致飞插件，页面如下。8.1SP2版本及其以后，将致飞插件合并到了微协同插件，因此只要微协同基础配置通过即可。




## 三、获取企业编码(CorpId)

1、登录PC端飞书，左上角人员头像——>管理后台———>首页(右侧的"企业信息"板块里面的"企业编号")

2、或者是登录飞书管理后台-点击左侧“企业设置”菜单-再点击“企业信息”菜单




## 四、飞书后台创建应用（创建 "审批" ）

进入"飞书管理后台"——>工作台——>应用管理——>右侧页面创建应用。

然后点击创建企业自建应用




## 五、获取应用AppId、AppSecret(后续会在OA后台的审批集成配置里面使用)

点击第四步所创建的审批应用，复制应用凭证下的App ID和App Secret。




## 六、进入OA的后台飞书集成——>审批中心配置——>新建绑定，把对应的信息填充好后点击提交按钮，检测通过后会自动回填"飞书主页配置"的配置信息




## 七、添加机器人

飞书开放平台有所升级，需要用户自行添加应用能力。审批应用只需要添加机器人即可




## 八、安全设置

点击开放平台左侧菜单“安全设置”---->配置重定向URL




## 九、权限管理

权限的配置必须按照下述说明进行配置，如果有不一样的地方，会出问题会出问题会出问题。



组织架构授权会提示配置数据范围（选择全部）



下述截图红色框中的权限都必须要开启







授权完毕后不会立马生效，需要应用发布后才会生效。当应用发布后确认此处应该有以下业务模块的授权。




## 十、版本管理与发布

发布并设置可使用范围(必须"所有员工")




## 十一、管理员审核发布的应用




## 致远微协同 - 飞书审批分组配置


## 一、创建分组之前需要先同步组织架构




## 二、进入OA的后台飞书集成——>审批中心配置——>分组配置

输入分组名称后，点击编辑，即可选择相关应用

选择相关应用后，数据就会回填至分组配置页面中

点击确定，提示保存成功后。数据将会保存至飞书审批中

登录飞书客户端-点击审批应用-再点击发起申请菜单。即可看到OA后台刚刚所配置的相关应用

点击OA审批下的应用将会打开电脑系统默认浏览器--展示应用页面（下图为点击新建事项后跳转的页面）




## 三、消息和审批测试

消息测试前请先修改配置

OA触发流程后，消息和审批将会推送至飞书中（前提是人员必须要通过集成配置应用绑定微协同或者是同步过组织架构）




## 四、常见配置问题说明

## 1、集团版OA可以同步整个组织架构，也可以同步部分单位。创建分组后，在飞书客户端-审批-发起申请中。只有同步过去的单位下的人员才能看到，未同步过去的单位下的人员看不到



## 2、集团管理员可以允许单位管理员自建飞书审批应用。

允许后，登录单位管理员账号如下页面所示。审批配置与上面同理，只有在分组的时候可以看到分组类型只有单位和团队分组。 单位管理员配置的审批分组只有当前单位下的人员能看到。



## 3、很多用户在配置完审批后，又需要删除并重新配置。这时候就会出现各种各样的问题，例如删除失败、删除后重新创建发现使用不了、收不到消息和审批等等问题。

如果需要删除的话，请按照以下步骤一步一步的操作，顺序不能乱。 1.分组状态勾选为停用，然后在删除分组

2.删除审批配置

3.进入飞书管理后台-工作台-应用管理-已安装应用下搜索需要删除的应用-将应用停用。 停用后在进入飞书开发平台-找到该应用删除即可

4.如果顺序乱了，或则是操作过程中出现了问题。则采用以下手段：飞书后台操作不变；OA后台无需操作，直接进入OA数据库，找到如下几张表，将数据全部删除即可，删除后登录OA后台发现数据已经都没有了，删除后建议重启下OA，因为有数据缓存。

5.数据删除完毕后即可开始重新配置

编撰人：het、tanghu




快速跳转



 * 致远微协同 - 飞书审批集成配置
   * 一、使用条件
   * 二、OA后台微协同基础配置和致飞基础设置
   * 三、获取企业编码(CorpId)
   * 四、飞书后台创建应用（创建 "审批" ）
   * 五、获取应用AppId、AppSecret(后续会在OA后台的审批集成配置里面使用)
   * 六、进入OA的后台飞书集成——>审批中心配置——>新建绑定，把对应的信息填充好后点击提交按钮，检测通过后会自动回填"飞书主页配置"的配置信息
   * 七、添加机器人
   * 八、安全设置
   * 九、权限管理
   * 十、版本管理与发布
   * 十一、管理员审核发布的应用
   * 致远微协同 - 飞书审批分组配置
     * 一、创建分组之前需要先同步组织架构
     * 二、进入OA的后台飞书集成——>审批中心配置——>分组配置
     * 三、消息和审批测试
     * 四、常见配置问题说明
       * 1、集团版OA可以同步整个组织架构，也可以同步部分单位。创建分组后，在飞书客户端-审批-发起申请中。只有同步过去的单位下的人员才能看到，未同步过去的单位下的人员看不到
       * 2、集团管理员可以允许单位管理员自建飞书审批应用。
       * 3、很多用户在配置完审批后，又需要删除并重新配置。这时候就会出现各种各样的问题，例如删除失败、删除后重新创建发现使用不了、收不到消息和审批等等问题。



分享链接分享链接

## 67. 致远微协同 - WELINK集成配置

> 原始路径：`/1270/1325/1329/1104.html`  
> 相对路径：`1270/1325/1329/1104.md`  
> JS Chunk：`app.844f671c.js`

## 致远微协同 - WELINK集成配置


## 一、使用条件

 1. 请确认协同产品的版本为V8.0及以上（A6、A8均支持）。
 2. 请确认协同系统的访问地址（IP）是公网地址。
 3. 请确认协同系统可以访问外网，否则无法推送消息。
 4. 已申请开通企业WeLink。


## 二、【WeLink管理后台】配置


## 1、创建应用：业务应用-应用管理-自建应用-到开发平台创建




## 2、自建应用








## 3、配置WeLink

配置Welink首页地址







手机端连接填写: https://weixin.seeyon.com/weLink/index?corpId=企业ID

如果客户是私有化部署微协同，请将“https://weixin.seeyon.com”修改为客户私有化微协同的地址

企业ID/租户ID获取位置为：



设置接口权限





上截图全部申请授权 发布版本







审核版本








## 三、【协同】配置

A8集团版：登录集团管理员，在《微协同管理平台》， A8企业版：登录单位管理员，在《微协同管理平台》， A6：登录系统管理员，在《微协同管理平台》， 按页面中说明依次完成以下步骤：

 1. 微协同基础设置
 2. WeLink集成配置



点击开始绑定

如果客户是私有化部署微协同，请将下图中的地址“https://weixin.seeyon.com”修改为客户私有化微协同的地址



企业id获取位置：



Client_id与Client_Secret获取位置



如果客户有需要将OA的组织架构同步到welink，公有云客户使用地址“https://weixin.seeyon.com/sync/indexWeLink”， 如果是私有化部署微协同，请将地址“https://weixin.seeyon.com”修改为客户私有化微协同的地址



编撰人：het、tanghu


快速跳转



 * 致远微协同 - WELINK集成配置
   * 一、使用条件
   * 二、【WeLink管理后台】配置
     * 1、创建应用：业务应用-应用管理-自建应用-到开发平台创建
     * 2、自建应用
     * 3、配置WeLink
   * 三、【协同】配置



分享链接分享链接

## 68. 致远微协同-微信小程序集成配置

> 原始路径：`/1270/1325/1330/1102.html`  
> 相对路径：`1270/1325/1330/1102.md`  
> JS Chunk：`app.844f671c.js`

## 致远微协同-微信小程序集成配置


## 1、简介

微信小程序是一种全新的连接用户与服务的方式，它可以在微信内被便捷地获取和传播，同时具有出色的使用体验。

我们通过微协同H5与小程序进行了快速集成，入口更快捷，体验更顺畅。 本文详细介绍小程序通过客开集成的方案，主要分以下几个步骤：




## 2、小程序注册

小程序注册登录地址：https://mp.weixin.qq.com

首先需要完成小程序的注册并且通过微信认证，每个邮箱仅能申请一个小程序，目前有2种方式：

 * 单独注册小程序，通过微信认证（提供企业资质信息，支付认证费用）

 * 【推荐使用】通过已认证公众号快速注册并认证小程序，可复用公众号资质（免认证）

注：小程序名称谨慎填写，因为小程序发布后，只能通过再次认证方式名。


## 3、小程序配置

1.获取AppID和AppSecret

> 在【设置-开发设置】开发者ID中获取

2.配置服务器域名和业务域名

> 在【设置-开发设置】服务器域名/业务域名中配置，域名为协同服务器外网地址

 * 服务器域名/业务域名需经过ICP备案，且只支持https安全域名

 * 业务域名配置的时候需要校验，参考腾讯说明：请下载校验文件，并将文件放置在域名根目录下，例如wx.qq.com，并确保可以访问该文件。如配置中遇到问题，请查看具体指引

> 


## 4、V5协同配置

 * 协同版本在V7.0SP2（含）以上

 * 协同有微协同插件

 * 部署《小程序插件》包

 * 在微协同基础配置中配置协同服务器地址
   
   * 协同服务器有外网地址，有经过ICP备案的域名，且只支持https安全协议




## 5、小程序代码开发

 1. 下载小程序开发工具
    
    *   https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html
      

 2. 获取代码
    
    * 申请V5微协同小程序集成代码
      
      * [下载代码]
    
    * 解压代码，通过小程序开发工具导入代码，修改AppID

> 

3.修改代码

> 在config.js中修改相关配置信息
> 
> hostPrefix：V5协同服务器域名
> 
> appid：小程序AppID
> 
> html：要跳转的H5地址，默认为空（微协同首页）



如果遇到以下情况



请将以下内容配置到app.json中

"permission": {
    "scope.userLocation": {
      "desc": "你的位置信息将用于进行考勤签到" 
    }
  },
 "requiredPrivateInfos":["getLocation"]




4.上传代码


## 6、开通获取当前地理位置，速度接口权限

从2022.4.18日起，小程序版本的发布审核需要配置获取位置接口权限，不然审核会失败。



1.首先进入小程序获取当前地理位置接口，找到申请开通项，找到符合当前小程序的类目。小程序获取当前地理位置接口地址为：https://developers.weixin.qq.com/miniprogram/dev/api/location/wx.getLocation.html



2.进入小程序后台管理新增类目，类目包含当前地理位置接口申请开通项的内容。如果当前小程序的类目已经有了当前地理位置接口申请开通项的内容，则可不用再次添加了。







3.去开通获取当前地理位置、速度接口权限





4.接口权限申请过后方可发布小程序版本

注：申请原因可以多写一点，可以介绍小程序的功能点等等，最后突出需要获取地理位置信息的原因(比如说员工打卡需要获取地理位置)。写少了会申请不过。辅助图片可以截图小程序的操作页面。


## 7、小程序代码审核

在【开发管理】中维护，将开发版本提交审核，也可选为体验版本先进行体验测试

 * 提交微信审核，可能需要测试账号才能通过审核




## 8、小程序发布

在【开发管理】中维护，将审核通过版本正式发布使用




## 9、小程序使用

公布小程序码，通过扫码使用，使用方式有两种：

 * 手机号一键登录，通过手机号免绑定，前提是微信绑定的手机号和协同账号的手机号一致

 * 协同账号登录，通过协同账号密码绑定




## 10、常见问题

如果小程序在微信开发者工具上调试是正常的，但是发布上线后手机使用却提示“协同服务无响应，点击确定退出小程序”。可以通过体验版测试，在vconsole中看是否有如下报错。如果有的话，那就是域名证书连不完整造成的，请更新证书链即可。



解决方案：

 1. 通过 https://myssl.com/ 检测证书状态，该网站有缓存，如果有更换过证书记得手动点刷新报告
 2. 如果是证书链不完整，参照指引 https://blog.myssl.com/faq-miss-ca-certificate/ 解决即可
 3. 参考链接https://blog.csdn.net/qq_40881695/article/details/125107653

编撰人：het、tanghu


快速跳转



 * 致远微协同-微信小程序集成配置
   * 1、简介
   * 2、小程序注册
   * 3、小程序配置
   * 4、V5协同配置
   * 5、小程序代码开发
   * 6、开通获取当前地理位置，速度接口权限
   * 7、小程序代码审核
   * 8、小程序发布
   * 9、小程序使用
   * 10、常见问题



分享链接分享链接

## 69. 微协同问题上报建议

> 原始路径：`/1270/1340.html`  
> 相对路径：`1270/1340.md`  
> JS Chunk：`app.844f671c.js`

## 微协同问题上报建议

> 上报微协同问题的时候，建议提供如下信息，以便研发快速分析处理问题。

1、登录OA后台-选择【集团管理员】权限-点击【微协同管理平台】菜单-点击【微协同基础设置】，提供如下配置截图：



2、登录OA后台-选择【集团管理员】权限-点击【微协同管理平台】菜单-点击【微协同基础设置】，提供如下检查检查结果截图：



3、如果是企业微信集成微协同，采用公有云模式，提供如下截图中的企业ID：



4、如果是私有化部署微协同，建议提供下微协同的相关日志，相关路径为\wx-core-service\logs_wx目录下所有内容：



5、如果是消息接收不到问题，可提供OA PC端对应时间点消息的截图：



编撰人：tanghu、het


快速跳转



 * 微协同问题上报建议



分享链接分享链接

## 70. 微协同常见问题FAQ清单

> 原始路径：`/1270/1353.html`  
> 相对路径：`1270/1353.md`  
> JS Chunk：`app.844f671c.js`

## 微协同常见问题FAQ清单


## 【企业微信集成】

模块分类   FAQ名称                                                   问题现象描述
组织同步   【微协同集成企业微信-组织同步】通讯录同步方式非第三方应用                           同步组织架构时或者是免绑定时报错企业微信通讯录同步方式非第三方应用，请联系微协同管理员授权。（私有化不支持免绑定）
组织同步   【微协同集成企业微信-组织同步】OA人员离职后企业微信没有删除                         OA流程触发人员离职、或者是手动处理离职人员后，OA中已经不存在了但是企业微信那边人员还在。检查配置监听组织变化已是开启状态。
组织同步   【微协同集成企业微信-组织同步】修改手机号未同步到企业微信                           OA中修改人员手机号后未同步到企业微信中
组织同步   【微协同集成企业微信-组织同步】人员同步报错不合法的部门列表                          OA新增/修改人员信息后，发现人员没有同步到企业微信。查看同步失败日志发现报错“不合法的部门列表”
组织同步   【微协同集成企业微信-组织同步】OA组织架构同步到企微后部门层级错误                      OA的跟部门变成了企业微信的一级部门，企微部门层级多了一层
消息     【微协同集成企业微信】微协同收不到消息提醒                                   微协同收不到消息提醒，特指企业微信
消息     【微协同集成企业微信、钉钉、飞书-消息】无故收到消息                              OA中流程已经结束，并且PC端浏览器中OA也无收到协同提醒，但是微协同中仍有超期提醒，泛指微协同集成
账号激活   【微协同集成企业微信-账号激活】接口调用许可已到期，应用无法使用                        人员无法使用微协同或者是重新续费了接口许可，接口许可到期之后需要重新激活
账号激活   【微协同集成企业微信-账号激活】人员离职或移除应用可见范围后，列表依然展示人员数据并且状态依然是已激活状态   账号列表展示数据问题，还有人员激活状态展示理解问题
账号激活   【微协同集成企业微信-账号激活】激活人员后有效期没变化，并且会生成重复账号                   人员激活后激活时间没有变化，并且还多出了一条数据
账号激活   【微协同集成企业微信-账号激活】企微导出通讯录人员激活状态和企微管理列表状态不一致               导出企业微信通讯录中有一个激活状态，理解为接口许可的激活，其实两者无关系
账号激活   【微协同集成企业微信-账号激活】企微管理列表中无法搜索到人员                          账号列表人员不好搜索，不好定位，展示数据是加密的
私有化    【微协同集成企业微信-私有化】找不到对应的企业信息                               私有化部署微协同、更改了OA地址
私有化    【微协同集成企业微信-私有化】Linux环境下ps -ef grep wx查询进程有多个            linux环境私有化部署微协同，使用shutdown命令停止服务后，发现进程还在
私有化    【微协同集成企业微信-私有化】redirect_uri需使用应用可信域名                    私有化部署微协同，配置地址的问题
其他     【微协同集成企业微信-修改OA地址】微协同配置有误，请待管理员调整                       公有云微协同，修改了OA地址
其他     【微协同集成-网络配置】网络配置的必要条件说明                                 微协同集成的网络条件说明，必须要满足网络条件才行
其他     【微协同集成企业微信】登录微协同慢                                       主要是企业微信集成登录微协同慢
其他     【微协同集成-企微/钉钉/飞书/公众号】签到无法定位                              泛指微协同集成，无法定位
其他     【微协同集成-企微/钉钉/飞书】PC端打开后提示被迫下线                            浏览器登录了OA，通过微协同又在另外的浏览器打开了OA
其他     【微协同集成-企微/钉钉/飞书/WeLink】登录微协同后页面空白                       登录微协同页面空白，一般是OA打了补丁包，缓存问题，需要清理缓存
其他     【微协同集成-企微/钉钉/飞书】流程上传图片提示：图片上传异常                         表单或协调上传图片的时候报错上传异常，PC端应该也会有问题
其他     【微协同集成企业微信】打开OA待办消息，会提示“该应用已在默认浏览器打开”                   企业微信集成PC端打开OA会有此弹框页面提示
其他     【微协同集成-企微/钉钉/飞书】国外登录微协同速度慢                              登录微协同缓慢，增加fiddler抓包教程
其他     【微协同集成-飞书/钉钉/企业微信】人员信息里会同步的字段                           微协同同步的时候需要同步那些字段说明


## 【钉钉集成】

模块分类   FAQ名称                        问题现象描述
消息     【微协同集成钉钉-消息】你无权限查看该页面        消息穿透的时候，提示无权限查看该页面
消息     【微协同集成钉钉】钉钉上收不到消息            钉钉收不到工作通知
其他     【微协同集成钉钉】钉钉穿透待办，审批后页面不自动关闭   PC端钉钉登录微协同处理完毕后页面不会自动关闭，提示”操作成功，请关闭此页面“，这是标准产品设计如此的


## 【飞书集成】

模块分类   FAQ名称                                 问题现象描述
消息     【微协同集成-飞书/钉钉/企微】PC端点击消息提示”链接无效“       泛指微协同，不限于飞书或者是其他，关注报错现象是链接无效或者是直接跳转到OA的登录页面了
消息     【微协同集成飞书】飞书上收不到消息                     飞书收不到工作通知
其他     【微协同集成飞书】审批中心打开待办PC端出现一个空白页面，需要手动关闭   PC端飞书登录微协同处理完毕后页面不会自动关闭，提示”操作成功，请关闭此页面“，这是标准产品设计如此的
其他     【微协同集成飞书】移动端打开微协同提示：被迫下线              一般是首次集成飞书配置后提示被迫下线
其他     【微协同集成飞书】飞书审批待办中展示数据不全                审批集成只适配了协同、表单、公文。其他的不会推送到审批，会推送消息


## 【公众号集成】

模块分类   FAQ名称                    问题现象描述
其他     【微协同集成公众号】登录微协同后立马闪退     公有云集成，使用”致远微协同“公众号登录微协同闪退，主要是OA地址是纯IP
其他     【微协同集成公众号】PC端打开后提示被迫下线   微协同公众号不支持PC端微信去操作，任何OA版本都不支持
其他     【微协同集成公众号】消息接收不到         微协同公众号收不到消息

编撰人：tanghu、het


快速跳转



 * 微协同常见问题FAQ清单
   * 【企业微信集成】
   * 【钉钉集成】
   * 【飞书集成】
   * 【公众号集成】



分享链接分享链接

## 71. 移动H5应用开发

> 原始路径：`/1271/`  
> 相对路径：`1271/README.md`  
> JS Chunk：`app.844f671c.js`

正在建设中…

编撰人：puwb、admin




快速跳转







分享链接分享链接

## 72. 技术要求

> 原始路径：`/1271/1273.html`  
> 相对路径：`1271/1273.md`  
> JS Chunk：`app.844f671c.js`

## 技术要求


## 1. HTML、CSS、JavaScript等前端基础技术：

 * HTML：熟练掌握HTML5的语义化标签，理解HTML文档结构和页面布局，具备编写高效、可维护HTML代码的能力。

 * CSS：精通CSS3的各种选择器、布局和动画效果，能够编写可复用、可维护的CSS代码，了解CSS的预处理器和后处理器，如Sass或Less。

 * JavaScript：熟练掌握JavaScript的核心语法、DOM操作、事件处理、异步编程等，了解ES6+的新特性，并能编写高性能、可维护的JavaScript代码。


## 2. 前端性能优化

 * 代码优化：使用代码分割、懒加载等技术减少首屏加载时间，避免不必要的渲染和重绘。

 * 资源加载优化：利用缓存、压缩、合并等技术优化资源的加载速度。

 * 渲染优化：使用CSS3动画代替JavaScript动画，避免阻塞渲染线程；使用requestAnimationFrame进行高效的动画渲染。


## 3. 前端工程化、模块化开发

 * 熟练使用Webpack、Rollup等构建工具，能够配置和优化构建流程。

 * 熟悉ES6的模块化规范，了解CommonJS和AMD等其他模块化规范。

 * 能够使用Babel等转译工具将ES6+代码转换为兼容旧浏览器的代码。


## 4. 跨平台开发能力

 * 了解不同设备和浏览器的兼容性差异，能够编写兼容多平台的代码。

 * 接触过Hybrid App开发，了解WebView与原生代码的交互方式。

 * 能够使用响应式设计和适配技术，使Web应用在不同设备上都能良好地显示和运行。


## 5. 服务端开发基础

 * 了解HTTP协议的基本原理和请求流程，能够处理常见的HTTP请求和响应。

 * 熟悉Nginx等Web服务器的配置和部署，了解反向代理、负载均衡等概念。

 * 能够与后端开发人员协同工作，理解前后端的数据交互方式和接口规范。


## 6. 前端安全

 * 了解常见的Web安全漏洞和攻击方式，如XSS、CSRF等。

 * 能够采取相应的安全措施，如输入验证、内容安全策略（CSP）等，确保应用的安全性。


## 7. 主流前端框架

> 已下为举例说明，请根据实际项目情况请选择合理的前端框架

 * React：熟悉React的生命周期、组件化开发、状态管理（如Redux）等，能够使用React Hooks进行函数式组件的开发，并了解React Native用于移动应用的开发。

 * Vue.js：掌握Vue.js的响应式原理、组件通信、指令和插槽等，能够使用Vue Router和Vuex进行路由管理和状态管理。

 * Angular：了解Angular的模块系统、依赖注入、组件和服务等，能够使用Angular CLI进行项目的构建和部署。

编撰人：puwb


快速跳转



 * 技术要求
   * 1. HTML、CSS、JavaScript等前端基础技术：
   * 2. 前端性能优化
   * 3. 前端工程化、模块化开发
   * 4. 跨平台开发能力
   * 5. 服务端开发基础
   * 6. 前端安全
   * 7. 主流前端框架



分享链接分享链接

## 73. 开发文档

> 原始路径：`/1271/1274.html`  
> 相对路径：`1271/1274.md`  
> JS Chunk：`app.844f671c.js`

## 开发文档

H5详细开发文档请参考：https://open.seeyoncloud.com/cmpdev/

更新时间：2024年4月29日

编撰人：puwb




快速跳转



 * 开发文档



分享链接分享链接
