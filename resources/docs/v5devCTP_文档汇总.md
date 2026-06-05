# Seeyon V5 Dev CTP 开放平台文档汇总

- 来源：https://open.seeyoncloud.com/v5devCTP/
- 提取文档数：171
- 说明：本文档从 VuePress 静态站点搜索索引中的原始 Markdown content 字段提取整理。

## 目录

1. [快速开始](#快速开始) — `/quickStart/`
2. [Hello World](#hello-world) — `/quickStart/helloworld.html`
3. [Nice Code](#nice-code) — `/quickStart/nicecode.html`
4. [快速开始](#快速开始) — `/38/`
5. [关于本站](#关于本站) — `/38/42.html`
6. [插件化开发](#插件化开发) — `/38/47.html`
7. [如何定制开发](#如何定制开发) — `/38/48.html`
8. [安装协同系统](#安装协同系统) — `/38/50.html`
9. [开发环境搭建](#开发环境搭建) — `/38/51.html`
10. [代码版本管理](#代码版本管理) — `/38/56.html`
11. [开发规范](#开发规范) — `/38/57.html`
12. [PC查找前端JSP位置方法](#pc查找前端jsp位置方法) — `/38/63/1128.html`
13. [快速查找前端源码位置](#快速查找前端源码位置) — `/38/63/1129.html`
14. [通过页面追溯Controller和JSP](#通过页面追溯controller和jsp) — `/38/63/1130.html`
15. [通过页面抓取后端请求](#通过页面抓取后端请求) — `/38/63/1131.html`
16. [致信端如何找到代码位置](#致信端如何找到代码位置) — `/38/63/1132.html`
17. [页面某个地方操作无反应问题排查](#页面某个地方操作无反应问题排查) — `/38/63/1212.html`
18. [遇到窗口关闭，难以调试怎么办](#遇到窗口关闭难以调试怎么办) — `/38/63/1213.html`
19. [Log日志分析经验](#log日志分析经验) — `/38/63/1214.html`
20. [某个操作很慢，问题排查方法](#某个操作很慢问题排查方法) — `/38/63/1215.html`
21. [使用Jvm分析工具](#使用jvm分析工具) — `/38/63/1216.html`
22. [手动抓取ThreadDump](#手动抓取threaddump) — `/38/63/2259.html`
23. [OA系统监控详解](#oa系统监控详解) — `/38/63/2263.html`
24. [平台开发组件库(简版)](#平台开发组件库简版) — `/38/67.html`
25. [安全开发规范](#安全开发规范) — `/38/95.html`
26. [数据字典](#数据字典) — `/38/146.html`
27. [CTP技术平台](#ctp技术平台) — `/39/`
28. [DAO数据层开发](#dao数据层开发) — `/39/74.html`
29. [缓存组件](#缓存组件) — `/39/75.html`
30. [国际化多语言](#国际化多语言) — `/39/77.html`
31. [定时任务](#定时任务) — `/39/78.html`
32. [日期和多时区](#日期和多时区) — `/39/79.html`
33. [EVENT事件监听](#event事件监听) — `/39/80.html`
34. [HTTP304缓存](#http304缓存) — `/39/81.html`
35. [加密解密](#加密解密) — `/39/82.html`
36. [LOG日志](#log日志) — `/39/83.html`
37. [产品区隔组件](#产品区隔组件) — `/39/84.html`
38. [安全访问控制](#安全访问控制) — `/39/86.html`
39. [应用配置器参数](#应用配置器参数) — `/39/87.html`
40. [APPS-API模块化解耦开发](#apps-api模块化解耦开发) — `/39/160.html`
41. [动态接口](#动态接口) — `/39/161.html`
42. [应用锁](#应用锁) — `/39/164.html`
43. [SpringBean注入规范](#springbean注入规范) — `/39/528.html`
44. [系统后台菜单管理](#系统后台菜单管理) — `/39/725.html`
45. [系统消息组件](#系统消息组件) — `/39/755.html`
46. [EMail邮箱[电子邮件]组件](#email邮箱电子邮件组件) — `/39/756.html`
47. [PhantomJs打印组件](#phantomjs打印组件) — `/39/759.html`
48. [1. 后端组件](#1-后端组件) — `/39/772.html`
49. [REST接口代码规范](#rest接口代码规范) — `/39/783.html`
50. [门户](#门户) — `/39/790/`
51. [内嵌页面跨域报错](#内嵌页面跨域报错) — `/39/790/1159/1160.html`
52. [收到消息无法正常刷新栏目](#收到消息无法正常刷新栏目) — `/39/790/1159/1161.html`
53. [登录页面设置视频无法自动播放](#登录页面设置视频无法自动播放) — `/39/790/1159/1162.html`
54. [常见栏目刷新方法](#常见栏目刷新方法) — `/39/790/1163/1164.html`
55. [基于代码的定制](#基于代码的定制) — `/39/790/1165/`
56. [01 注册门户模板信息](#01-注册门户模板信息) — `/39/790/1165/1166.html`
57. [02 注册整体皮肤](#02-注册整体皮肤) — `/39/790/1165/1167.html`
58. [03 注册门户模板与整体皮肤的绑定关系](#03-注册门户模板与整体皮肤的绑定关系) — `/39/790/1165/1168.html`
59. [04 注册门户皮肤](#04-注册门户皮肤) — `/39/790/1165/1169.html`
60. [05 注册门户布局](#05-注册门户布局) — `/39/790/1165/1170.html`
61. [06 新建门户模板图片资源存放位置](#06-新建门户模板图片资源存放位置) — `/39/790/1165/1171.html`
62. [07 注册门户元素](#07-注册门户元素) — `/39/790/1165/1172.html`
63. [08 开发和注册栏目](#08-开发和注册栏目) — `/39/790/1165/1173.html`
64. [09 开发和注册依赖的第三方JS文件](#09-开发和注册依赖的第三方js文件) — `/39/790/1165/1174.html`
65. [10 注册门户模板热点](#10-注册门户模板热点) — `/39/790/1165/1175.html`
66. [a_门户模板定制](#a门户模板定制) — `/39/790/1176/1177.html`
67. [b_栏目布局定制](#b栏目布局定制) — `/39/790/1176/1178.html`
68. [c_栏目外框定制](#c栏目外框定制) — `/39/790/1176/1179.html`
69. [Groovy语法](#groovy语法) — `/39/797.html`
70. [系统登录组件](#系统登录组件) — `/39/925.html`
71. [概述](#概述) — `/39/1119.html`
72. [单点登录(SSO)](#单点登录sso) — `/39/1858.html`
73. [免登录认证请求](#免登录认证请求) — `/39/2441.html`
74. [appLog应用审计日志组件](#applog应用审计日志组件) — `/39/2534.html`
75. [对象存储扩展适配](#对象存储扩展适配) — `/39/2747.html`
76. [技术解决方案](#技术解决方案) — `/40/`
77. [组织机构解决方案](#组织机构解决方案) — `/40/89/`
78. [管理员菜单维护](#管理员菜单维护) — `/40/89/90.html`
79. [流程图详解](#流程图详解) — `/40/202/203/204.html`
80. [流程中各状态值](#流程中各状态值) — `/40/202/203/205.html`
81. [流程事件与节点事件](#流程事件与节点事件) — `/40/202/203/206.html`
82. [超级节点基础信息](#超级节点基础信息) — `/40/202/203/207.html`
83. [业务关系和简单场景](#业务关系和简单场景) — `/40/202/203/227.html`
84. [获取客户流程图的方式](#获取客户流程图的方式) — `/40/202/210/211.html`
85. [分支满足人员匹配到了还是弹框](#分支满足人员匹配到了还是弹框) — `/40/202/213/214.html`
86. [修复流程图数据及相关协同、表单数据等](#修复流程图数据及相关协同表单数据等) — `/40/202/788/789.html`
87. [查询性能问题解决方案](#查询性能问题解决方案) — `/40/299/1117.html`
88. [公文升级问题](#公文升级问题) — `/40/310/311.html`
89. [公文概念和数据结构](#公文概念和数据结构) — `/40/310/1000.html`
90. [SDK+web service方式集成](#sdkweb-service方式集成) — `/40/752/924.html`
91. [当前已登录了一个用户，同一窗口中不能登录多个用户](#当前已登录了一个用户同一窗口中不能登录多个用户) — `/40/752/1001.html`
92. [实现PC登录页扫描登录功能如何实现](#实现pc登录页扫描登录功能如何实现) — `/40/752/1008.html`
93. [登录验证码清晰度调整](#登录验证码清晰度调整) — `/40/752/1905.html`
94. [Android端M3升级TargetSDK Version 30的修改点和修改方法](#android端m3升级targetsdk-version-30的修改点和修改方法) — `/40/1002/1004.html`
95. [iOS M3常见安全问题处理方案](#ios-m3常见安全问题处理方案) — `/40/1002/1006.html`
96. [移动端协同修改正文实现多人在线编辑](#移动端协同修改正文实现多人在线编辑) — `/40/1002/1127.html`
97. [M3唤起三方APP或被唤起开发方案](#m3唤起三方app或被唤起开发方案) — `/40/1002/1218.html`
98. [【M3】正文预览“下载查看”按钮屏蔽](#m3正文预览下载查看按钮屏蔽) — `/40/1002/1950.html`
99. [不参加会议不要在领导行程中展示](#不参加会议不要在领导行程中展示) — `/40/1070/1071.html`
100. [统一待办降版本适配手册](#统一待办降版本适配手册) — `/40/1092.html`
101. [适配第三方数据库解决方案](#适配第三方数据库解决方案) — `/40/1113/1114.html`
102. [致信开发教程](#致信开发教程) — `/40/1115/1116.html`
103. [致信后端开发文档](#致信后端开发文档) — `/40/1115/1181.html`
104. [致信客开常见问题](#致信客开常见问题) — `/40/1115/1182.html`
105. [致信客开开发环境说明](#致信客开开发环境说明) — `/40/1115/1183.html`
106. [致信客户端国产化构建打包手册](#致信客户端国产化构建打包手册) — `/40/1115/1868.html`
107. [致信常见问题解决方案](#致信常见问题解决方案) — `/40/1115/1872.html`
108. [【致信】常见问题](#致信常见问题) — `/40/1115/1894.html`
109. [云联证书安装检查清单及问题处理方案](#云联证书安装检查清单及问题处理方案) — `/40/1346/1347.html`
110. [webservice wsdl代码生成位置](#webservice-wsdl代码生成位置) — `/40/1939/1940.html`
111. [新版本选择模板页面调整需求](#新版本选择模板页面调整需求) — `/40/1948/1949.html`
112. [CIP组织机构同步-接口模式](#cip组织机构同步-接口模式) — `/40/2203/2204.html`
113. [三方中间件适配点](#三方中间件适配点) — `/40/2232/2233.html`
114. [概述](#概述) — `/40/2380/2381.html`
115. [组织同步](#组织同步) — `/40/2380/2382.html`
116. [单点登录](#单点登录) — `/40/2380/2411.html`
117. [事项同步](#事项同步) — `/40/2380/2416.html`
118. [事项同步](#事项同步) — `/40/2380/2525.html`
119. [前端技术](#前端技术) — `/1842/`
120. [技术平台](#技术平台) — `/1842/167.html`
121. [JSP前端UI组件库](#jsp前端ui组件库) — `/1842/167.html`
122. [ES6转ES5工具使用教程](#es6转es5工具使用教程) — `/1842/169.html`
123. [JSP前端开发规范](#jsp前端开发规范) — `/1842/170.html`
124. [1、相关函数](#1相关函数) — `/1842/576/577.html`
125. [背景](#背景) — `/1842/576/622.html`
126. [seeyonUi 组件](#seeyonui-组件) — `/1842/576/905.html`
127. [文化建设](#文化建设) — `/1842/576/906.html`
128. [1、报表中心](#1报表中心) — `/1842/576/907.html`
129. [一、业务介绍](#一业务介绍) — `/1842/576/908.html`
130. [工程代码说明](#工程代码说明) — `/1842/576/909.html`
131. [1 表单设计态](#1-表单设计态) — `/1842/576/911.html`
132. [应用管理中心jsp页面](#应用管理中心jsp页面) — `/1842/576/915.html`
133. [1.代码位置](#1代码位置) — `/1842/576/919.html`
134. [自定义控件清单](#自定义控件清单) — `/1842/576/920.html`
135. [业务空间设置](#业务空间设置) — `/1842/576/921.html`
136. [1、工程相关](#1工程相关) — `/1842/576/923.html`
137. [AJAX组件](#ajax组件) — `/1842/773/73.html`
138. [数据国际化](#数据国际化) — `/1842/773/85.html`
139. [选人组件](#选人组件) — `/1842/773/88.html`
140. [前端JSP动态脚本链入](#前端jsp动态脚本链入) — `/1842/773/159.html`
141. [水印组件](#水印组件) — `/1842/773/1856.html`
142. [JSP Form校验提交组件](#jsp-form校验提交组件) — `/1842/773/1873.html`
143. [JSP附件组件](#jsp附件组件) — `/1842/773/1874.html`
144. [JSP关联文档组件](#jsp关联文档组件) — `/1842/773/1875.html`
145. [图片预览组件](#图片预览组件) — `/1842/773/1876.html`
146. [前端快速开始](#前端快速开始) — `/1842/1843.html`
147. [金格外部中间件JSAPI实现逻辑](#金格外部中间件jsapi实现逻辑) — `/1842/1851/970.html`
148. [金山中台预览增加SDK以实现打印旋转等功能](#金山中台预览增加sdk以实现打印旋转等功能) — `/1842/1851/971.html`
149. [金山WPS客户端JSAPI加载项集成文档](#金山wps客户端jsapi加载项集成文档) — `/1842/1851/1852.html`
150. [金山文档中台内外网映射适配方案](#金山文档中台内外网映射适配方案) — `/1842/1851/1966.html`
151. [文档通在线编辑技术说明文档](#文档通在线编辑技术说明文档) — `/1842/1851/1996.html`
152. [数科预览及水印技术说明文档](#数科预览及水印技术说明文档) — `/1842/1851/1997.html`
153. [数科套红技术说明文档](#数科套红技术说明文档) — `/1842/1851/1998.html`
154. [流版签（OfficeSDK）技术说明文档](#流版签officesdk技术说明文档) — `/1842/1851/1999.html`
155. [数科H5签章技术说明文档](#数科h5签章技术说明文档) — `/1842/1851/2000.html`
156. [数科版式正文盖章技术说明文档](#数科版式正文盖章技术说明文档) — `/1842/1851/2001.html`
157. [金山中台适配OfficeSDK技术说明文档](#金山中台适配officesdk技术说明文档) — `/1842/1851/2045.html`
158. [金山文档中台非/open开头地址适配](#金山文档中台非open开头地址适配) — `/1842/1851/2249.html`
159. [金山文档中台急速预览适配](#金山文档中台急速预览适配) — `/1842/1851/2265.html`
160. [金山文档中台集成运行逻辑图](#金山文档中台集成运行逻辑图) — `/1842/1851/2372.html`
161. [数科在线预览缩放比例自定义调整](#数科在线预览缩放比例自定义调整) — `/1842/1851/2722.html`
162. [协同新建修改和详情页面前后端分离动态接入组件](#协同新建修改和详情页面前后端分离动态接入组件) — `/1842/1878/1879.html`
163. [协同待办列表按钮扩展机制](#协同待办列表按钮扩展机制) — `/1842/1878/2002.html`
164. [页面设计器三方业务拓展](#页面设计器三方业务拓展) — `/1842/1878/2655.html`
165. [Vue工程本地调试及定位](#vue工程本地调试及定位) — `/1842/1947.html`
166. [CoMi智能体技术文档](#comi智能体技术文档) — `/2764/`
167. [调用CoMi已发布的Agent API](#调用comi已发布的agent-api) — `/2764/2765.html`
168. [调用已发布的CoMi工作流API](#调用已发布的comi工作流api) — `/2764/2767.html`
169. [CoMi小章鱼图标替换说明](#comi小章鱼图标替换说明) — `/2764/2799.html`
170. [AICard 结构化数据配置指南](#aicard-结构化数据配置指南) — `/2764/2807.html`
171. [CoMi CAP数据万能助手教程](#comi-cap数据万能助手教程) — `/2764/2808.html`

---

## 1. 快速开始

> 原始路径：`/quickStart/`  
> 相对路径：`quickStart/README.md`

## 快速开始

欢迎来到快速开始页面

## 2. Hello World

> 原始路径：`/quickStart/helloworld.html`  
> 相对路径：`quickStart/helloworld.md`

## Hello World

北京欢迎您！

## 3. Nice Code

> 原始路径：`/quickStart/nicecode.html`  
> 相对路径：`quickStart/nicecode.md`

## Nice Code

这是一段优秀的代码！

## 4. 快速开始

> 原始路径：`/38/`  
> 相对路径：`38/README.md`

子菜单名称         URL
关于本站          关于本站
安装协同系统        安装协同系统
搭建开发环境        搭建开发环境
代码管理Git&SVN   代码管理Git&SVN
插件化开发         插件化开发
安全开发规范        安全开发规范
平台开发组件库       平台开发组件库
如何定制开发        如何定制开发
问题调试分析方法      问题调试分析方法
关于数据字典        关于数据字典
开发规范          开发规范

分享链接分享链接

## 5. 关于本站

> 原始路径：`/38/42.html`  
> 相对路径：`38/42.md`

## 关于本站


## 演进历史

自2015年起，致远推出了open.seeyon.com开放平台，打造了第一代技术生态社区。open.seeyon建立了统一的技术文档出口，为客开、伙伴、第三方提供了开放的技术资源，是每一位技术接入用户必访站点。

时光荏苒，随着致远V5产品版本的不断迭代，open.seeyon技术平台（各种原因）没有跟上版本的脚步，技术文档大多还停留在V7.x版本。



考虑到未来扩展性和可维护性，我们决定采用新一代技术方案构建开放平台，于是open.seeyoncloud.com致远开放平台V2.0诞生！

open.seeyoncloud不再只是提供面向开发技术的文档，也推出了FAQ、产品文档等导航解决产品功能运维层面的问题，力图大家能通过平台快速自助解决问题。




## 关于开发文档

开发文档和SeeyonAPI是面向技术的文档库，在原来open.seeyon已有知识基础上完善了新版本的特性。


## 访问地址

菜单          地址
开发文档        https://open.seeyoncloud.com/v5devCTP/
SeeyonAPI   https://open.seeyoncloud.com/seeyonapi/


## 支持版本

本站暂时面向致远V5平台推出的产品线客户，包含并不仅限于如下产品版本：

 * A8+企业版/集团版、A8-N单组织/多组织版，如V8.0SP2LTS、V8.1、V8.2及未来更多版本
 * G6单组织/多组织版、G6-N单组织/多组织版，如V8.1、V8.2及未来更多版本
 * 督查督办V8.1、V8.2及未来更多版本


## 面向群体

致远软件V5开放平台网站-开发文档，主要面向技术人员的内容管理平台，服务于在致远平台建设的开发人员。

服务对象      服务内容
开发人员      开发文档、接口信息、解决方案。
内外部所有用户   了解致远V5平台。


## 关于V5平台

V5平台由协同技术平台（Collaboration Technology Platform）、协同应用平台（Collaboration Application Platform）、协同移动平台（Collaboration Mobile Platform）、协同集成平台（Collaboration Integration Platform）四大支撑平台组成。



协同技术平台（CTP）主要面向开发人员，提供开发框架、规范、组件和全生命周期的开发流程管理。CTP基于协同管理软件领域15年技术沉淀，高度抽象出协同应用五大核心业务引擎：组织权限、工作流、表单、门户及报表引擎。五大引擎基于B/S的MVC开发框架，并在此基础上封装、组合，形成致远协同服务用于应用开发的高度复用、抽象灵活的技术平台。同时，CTP平台提供安全与插件机制，通过远程服务调用与本地（API）接口相结合的方式，为致远研发内部、合作伙伴及客户提供策略配置、二次开发等多种方式以满足快速构建及扩展协同应用的各类需求。

协同应用平台（CAP）主要面向企业业务人员，通过配置工具搭建业务应用。以“人”为中心，“组织行为管理”为关键，“结构化信息”处理为重点，是内外打通、移动互联的大协同时代协同管理软件应用的结晶。基于智能表单引擎衍生的业务生成器，支持零编码方式搭建业务系统，便于应对需求变更进行重构，解决组织不同发展时期对协同软件的不同要求，为组织的不断发展壮大提供持续高效的协同服务。

协同移动平台（CMP）主要面向移动开发人员，提供移动开发框架基础支撑。以协同为核心，移动技术为骨架，支持致远旗下所有产品移动化的技术和应用平台。CMP平台同时提供应用集成解决方案，通过配置化的方式集成其他移动业务应用；提供移动应用开发的基础引擎和定制化接口，为二次开发提供标准化的扩展机制；提供统一的移动化办公桌面，有效提升企业工作效率。

协同集成平台（CIP）提供标准套件、接口和工具进行异构系统集成。提供企业应用集成整体方案及底层支持，标准化支持与NC、EAS、SAP、U8等ERP的HR、财务和供应链模块进行人员、页面、数据和流程的集成，与滴滴、携程整合提供一体化商旅出行解决方案，打破数据孤岛、信息孤岛和应用孤岛；基于开放性的平台架构，并提供DEE数据交换引擎简化异构系统之间的数据交换。




## 能力一览

V5开发文档内容管理平台提供了从入门到熟练的一整套文档解决方案，立志于让新人快速入手，让老人更加熟练解决问题。开放文档将持续提供如下能力输出：

一、新手入门：

 * 环境搭建
 * 开发示例
 * 代码版本管理、开发规范、安全规范
 * 定制开发引导
 * 问题调试方法、代码溯源方法、日志分析方法

二、进阶：平台组件

 * 代码结构、MVC框架、异常框架、日志
 * 数据层组件、Event事件监听、缓存组件、定时任务、平台锁组件、
 * 加密解密组件、多时区组件、多语言组件、选人组件、消息组件、电子邮箱组件

三、进阶：移动定制开发

 * 基于H5的页面开发
 * 三方集成常见问题及解决方案
 * M3原生开发

四、进阶：CIP集成

 * CIP集成接口
 * CAS认证
 * DEE集成
 * 集成组件：用户绑定、消息集成、待办集成、单点登录等

五、进阶：CAP应用表单开发

 * CAP3自定义控件开发
 * CAP4：前端后端环境搭建和编译、自定义控件开发、自定义按钮开发、门户空间开发、前端模板化开发

六、进阶：前端文档

 * 各业务模块前端代码位置总结
 * ES6转ES5工具
 * 前端技术经验

七、技术解决方案（持续完善）

 * 持续贡献各模块定制开发问题解决方案

八、SeeyonAPI

 * 对外开放的Rest APi、Event、动态接口API文档、核心工程Java Doc文档


## 技术要求

如果需要基于V5平台进行应用开发，开发人员需要掌握的相关技能如下：

## 后端服务开发

 * Java语言编程（JDK1.8）

 * JavaEE（Servlet、Filter等）

 * Spring、Spring MVC

 * XML和JSON

 * Restful

 * 熟悉致远CTP平台技术

## 后端数据层开发

 * JDBC原理和编程方法

 * Hiberante原理与编程方法

 * 数据库的配置和使用：Postgresql、MySQL、Oracle、SQL Server等

## 前端界面开发（JSP）

 * JavaSrcipt基本用法

 * CSS的使用

 * JSP/JSTL/EL

 * JQuery

 * Ajax

 * SeeyonUI框架代码

## 前端界面开发（Html）

 * JavaSrcipt基本用法

 * CSS的使用

 * HTML结构、Html5特性

 * VueJs

 * Ajax

## 移动应用开发（Html5）

 * JavaSrcipt基本用法

 * CSS的使用

 * HTML结构、Html5特性

 * 熟悉致远CMP平台API


## 问题反馈

如果在使用过程中有发现内容缺失、错误，欢迎通过页面右下角的“问题反馈”按钮反馈，我们收到信息后会尽快处理。




## 版权申明

本站版权归北京致远互联软件股份有限公司所有，摘编、转载或链接请注明出处，严禁一切取本站文档销售、商用行为。

对于不遵守此声明或者其他违法使用本站内容者，公司依法保留追究权。

编撰人：admin、het、lichaoj




快速跳转



 * 关于本站
   * 演进历史
   * 关于开发文档
     * 访问地址
     * 支持版本
     * 面向群体
     * 关于V5平台
     * 能力一览
     * 技术要求
       * 后端服务开发
       * 后端数据层开发
       * 前端界面开发（JSP）
       * 前端界面开发（Html）
       * 移动应用开发（Html5）
   * 问题反馈
   * 版权申明



分享链接分享链接

## 6. 插件化开发

> 原始路径：`/38/47.html`  
> 相对路径：`38/47.md`

## 插件化开发

V5基于三层模型架构运转，V5又是基于插件化开发模式以达到按模块松耦合、可插拔。

插件化开发是平台的基本能力，无论是标准产品还是二次开发，都应该基于插件化开发框架范畴进行技术完善，所以这是V5产品开发基础中的基础！

关键字：二次开发代码示例、客开代码示例、插件开发代码示例。


## 基础架构




## 开发准备


## 字符集

为了实现国际化编程，全局要求使用UTF-8的字符集编码，包括：

 * 数据库：参考安装维护手册配置字符集
 * 文件：java、properties、jsp、js、css、html等等使用UTF-8
 * servlet：response.setContentType(“text/html; charset=UTF-8”);
 * JSP头部标记UTF-8引用：<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>


## 代码结构

完整的项目结构大概如下

src
    com
        seeyon
            apps(ctp)                                        #1
                sample
                    controller
                        SampleController.java                #2
                    manager
                        SampleManager.java                   #3
                        SampleManagerImpl.java               #4
                    dao
                        SampleDao.java                       #5
                        SampleDaoImpl.java                   #6
                    po
                        SamplePO.java                        #7
                        SamplePO.hbm.xml                     #8
webapps
    WEB-INF
        cfgHome
            i18n
                SampleResource_en.properties                 #9
                SampleResource_zh_CN.properties
                SampleResource_zh_TW.properties
            spring
                spring-sample-controller.xml                 #10
                spring-sample-manager.xml                    #11
                spring-sample-dao.xml                        #12


编号   说明
1    应用使用apps，CTP平台使用ctp如com.seeyon.apps.news和com.seeyon.ctp.form
2    MVC
     Controller（如果模块不大，Controller、Manager和Dao都可以放到上级package中，但PO必须放在po
     package中）
3    MVC Manager接口
4    MVC Manager实现
5    MVC DAO接口
6    MVC DAO实现
7    PO
8    PO Hibernate映射文件
9    Java国际化资源文件
10   Controller的Spring配置文件
11   Manager的Srping配置文件
12   Dao的Spring配置文件


## 完整开发示例

V5平台提供“插件式”开发模式：一个业务功能模块就是一个插件，该业务功能模块下的所有代码在各自插件下维护，Spring Bean也交由该插件管理，如果插件停用、删除则该业务功能完全下线。

在本地协同服务ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin目录下能看到很多子文件夹，每一个文件夹就是一个插件，比如协同collaboration、公文edoc、表单应用cap4。

一个插件模块的开发步骤包含：

 1. 定义插件
 2. 创建spring beans文件
 3. 创建对应的hbm文件
 4. 编写XXXController、XXXManager、XXXDao XXXVO、XXXPO
 5. 编写前端页面


## 定义插件

在ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin目录下新建新的插件文件夹，一个标准的目录结构如下所示：



插件定义：插件的信息定义在/src/main/webapp/WEB-INF/cfgHome/plugin/demo/pluginCfg.xml

<?xml version="1.0" encoding="UTF-8"?>
<plugin>
 <!-- id最重要：保证全系统唯一 -->
 <id>demo</id>
 <!-- name仅仅是在ctp.log日志中输出 -->
 <name>开发实例</name>
 <!-- 数字自定义，最好不超过5位数，太大启动会报错 -->
 <category>50505</category>
</plugin>


其它spring/spring-demo-*.xml初期可以保持为空，等后续创建对应Java类之后再使用。

i18n下面的文件是国际化文件，初期同样可以保持为空，等需要国际化开发再使用。

将以上plugin/demo文件夹拷贝到本地协同服务ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin之后，启动系统完成后，查看ApacheJetspeed\logs_sy\ctp.log日志能够看到如下信息：

[localhost-startStop-1]  INFO: PluginSystemInit: - Load Plugin : 50505, demo, 开发实例



## 三层功能开发

## Controller层

基于Spring MVC开发，后端提供Controller负责数据转发，定义Controller方法需要继承平台的BaseController

> Controller的职责：只负责页面转发、参数传递、数据返回，不参与业务计算，所有业务计算和数据抽取均调用Manager层。

package com.seeyon.apps.demo.controller;

import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;
import org.springframework.web.servlet.ModelAndView;
import com.seeyon.ctp.common.controller.BaseController;

public class DemoController extends BaseController{
 /**
  * index方法是：URL不传任何method，默认访问的方法
  */
 @Override
 public ModelAndView index(HttpServletRequest request, HttpServletResponse response) throws Exception {
  return new ModelAndView("apps/demo/index");
 }
}


新建的Controller需要在Spring中注册，使用XML的形式注册到：/src/main/webapp/WEB-INF/cfgHome/plugin/demo/spring/spring-demo-controller.xml

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
<!-- 注意是name不是id -->
 <bean name="/demo.do" class="com.seeyon.apps.demo.controller.DemoController"></bean>
</beans>


下一步是编写跳转页面，Controller中ModelAndView("apps/demo/index")意味着页面需要放置在：/WEB-INF/jsp/apps/demo/index.jsp

<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html class="over_hidden h100b">
<head>
 <%@include file="/WEB-INF/jsp/common/common_header.jsp"%>
 <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta name="renderer" content="webkit">
 <title>${ctp:i18n("文件标题国际化key") }</title>
 <link rel="stylesheet" href="${path}/apps_res/{module}/css/xxx.css${ctp:resSuffix()}">
</head>
<body class="over_hidden h100b">
 这里是index.jsp页面
</body>
<%@include file="/WEB-INF/jsp/common/common_footer.jsp"%>
<script type="text/javascript" src="${path }/apps_res/{module}/js/xxx.js${ctp:resSuffix()}"></script>
</html>


如果以上开发编译完成，部署到V5平台下之后，可以通过如下链接访问到：

http://[host]:[port]/seeyon/demo.do?method=index

如果你是本地默认端口则可以访问：http://localhost/seeyon/demo.do?method=index

## Manager层

Manager是业务层，负责代码逻辑运算、解析、转换、涉及业务逻辑实现全部在此层完成。

首先要定义Manager接口：

public interface DemoManager {
  public void saveDemo(Map<String,Object> params) throws BusinessException;
}


然后编写实现类：

public class DemoManagerImpl implements DemoManager {
  @Override
  public void saveDemo(Map<String, Object> params) throws BusinessException {
    //代码实现块
  }
}


新建的Manager需要在Spring中注册，使用XML的形式注册到：/src/main/webapp/WEB-INF/cfgHome/plugin/demo/spring/srping-demo-manager.xml

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
 <bean id="demoManager" class="com.seeyon.apps.demo.manager.DemoManagerImpl"></bean>
</beans>


Manager被Controller所调用，我们可以在Controller中通过Inject注解注入Manager，随后就可以调用业务层的方法了。

public class DemoController extends BaseController{
// 通过Inject注入Manager
 @Inject
 private DemoManager demoManager;

 @Override
 public ModelAndView index(HttpServletRequest request, HttpServletResponse response) throws Exception {
  // 调用Manager方法，伪代码
  demoManager.saveDemo(params);
  return new ModelAndView("apps/demo/index");
 }
}


## DAO层

DAO层用于数据访问，直接对数据库进行操作，SQL全部在DAO层维护。

首先要定义Dao接口

public interface DemoDao {
  public List find();
}


然后编写实现类：

public class DemoDaoImpl implements DemoDao {
 public List find() {
  String sql = "select id from demo order by id";
  // CTP平台基于JDBC的工具类
  JDBCAgent jdbc = new JDBCAgent(false,false);
  try {
   // SQL查询方法
   return jdbc.findNamedSql(sql);
  } catch (BusinessException e) {
   return null;
  } finally {
   // 使用完毕后关闭连接，不关闭会造成连接池泄露
   jdbc.close();
  }
 }
}


新建的Dao需要在Spring中注册，使用XML的形式注册：/src/main/webapp/WEB-INF/cfgHome/plugin/demo/spring/srping-demo-dao.xml

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
 <bean id="demoDao" class="com.seeyon.apps.demo.dao.DemoDaoImpl"></bean>
</beans>


以上是DAO的最基本用法。V5平台基于数据库持久层引入了Hibernate框架，我们可以介入Hibernate相关API特性进行快速开发，同样也可以基于HQL进行数据库兼容编写。

更多更详细的DAO层API使用案例参考本站[DAO数据层开发]文档。


## 三层开发总结

综上，整个请求调用链路是：前端请求调用=>Controller=>Controller注入Manager+调用Manager接口获取数据并返回=>Manager注入DAO+调用Dao接口实现数据业务操作=>Dao直连数据库进行CRUD操作。

Controller、Manager、Dao三层开发各司其职，只有做好正确的切分才能保障代码的健壮性。

以上仅仅是最传统的三层模型开发，而随着技术的演进，V5平台基于这三层还衍生出了多种架构模式，如Restful、Ajax、Api等，万变不离其宗，只要三层结构封装够健壮，都可以顺利桥接。


## JSP开发准备

V5平台是单体应用架构，后端采用MVC框架，前端可以使用JSP或Html方案开发。

如果需要短平快的形式开发，可以采用JSP的开发模型，V5平台提供了完整的JSP开发配套前端组件，可以使用Seeyon UI+JQuery+AJAX进行页面操作，早期的应用均采用这种开发模式。

如果前端技能比较强，可以基于VUE+Html纯前后端分离的开发模式开发，V5部分应用正是采用这种开发模式。

V5平台推荐的一个标准的JSP页面应该是如下的结构：

<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html class="over_hidden h100b">
<head>
 <%@include file="/WEB-INF/jsp/common/common_header.jsp"%>
 <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta name="renderer" content="webkit">
 <title>${ctp:i18n("文件标题") }</title>
 <link rel="stylesheet" href="${path}/apps_res/{module}/css/xxx.css${ctp:resSuffix()}">
</head>
<body class="over_hidden h100b">
 这里是index.jsp页面
</body>
<%@include file="/WEB-INF/jsp/common/common_footer.jsp"%>
<script type="text/javascript" src="${path }/apps_res/{module}/js/xxx.js${ctp:resSuffix()}"></script>
</html>


common_header.jsp是平台统一封装的各种CSS以及JSP常用的JSTL和自封Taglib。

common_footer.jsp是平台统一封装的各种Javascript、js变量。

如果当前页面有比较特殊的css样式控制，可以自己编写独立的css文件，通过link rel="stylesheet" href引入。

不推荐大篇幅的Javascript在JSP中直接编写，我们推荐编写独立的.js文件，通过script type="text/javascript" src引入。

不推荐在JSP中嵌入EL表达式，甚至JSTL表达式，我们推荐使用Javascript+AJAX的形式进行页面的布局、渲染（或者就把JSP当前一个Html来开发）。


## JSP开发演示

下面是一个增、删、查的常规页面，本章基于此页面做代码演示。



第一步：使用SeeyonUI的static layout进行上下布局，上部分是操作按钮，下部分是table表格：

<!-- CSS静态上下布局，更多布局参考SeeyonUI组件库文档 -->
<style>
.stadic_head_height {
 height: 40px;
}

.stadic_body_top_bottom {
 bottom: 0px;
 top: 40px;
}
</style>
</head>
<body class="over_hidden h100b">
 <div class="stadic_layout">
  <div class="stadic_layout_head stadic_head_height">
   <div id="toolbar"></div>
  </div>
  <div class="stadic_layout_body stadic_body_top_bottom"
   id="layout_bottom">
   <table id="mytable" style="display: none"></table>
  </div>
 </div>
</body>


第二步：通过Javascript调用SeeyonUI API将上部分“添加”和“删除”按钮渲染出来：

/**
 * 这段代码可以独立js文件维护，也可以放在JSP script代码块中维护
 * toolbar学习资料：http://open.seeyon.com/seeyonui/V2.0/components/index.html#___toolbar
 */
var DemoIndex = {};
DemoIndex.initToolbar = function() {
 var tt = $("#toolbar").toolbar({
    toolbar : [{
       id : "add",
       name : $.i18n('common.button.add.label'),
       className : "ico16 add_16",
       click : DemoIndex.openDemoDialog
      }, {
       id : "delete",
       name : $.i18n('common.button.delete.label'),
       className : "ico16 del_16",
       click : DemoIndex.deleteDemo
      }]
   });
}


以上只是定义了初始化操作按钮的方法initToolbar，接着我们通过JQuery的ready事件，在初次进入页面时执行渲染即可实现按钮的显示：

<script type="text/javascript">
 $().ready(function() {
  DemoIndex.initToolbar();
 });
</script>


第三步：同理，通过Javascript调用SeeyonUI API将下部分列表渲染出来，由于SeeyonUI ajaxGrid涉及数据获取，还需要编写后端代码，本章就不做全部代码，只做伪代码演示：

var DemoIndex = {};

// 工具按钮参考文档：http://open.seeyon.com/seeyonui/V2.0/components/index.html#___toolbar
DemoIndex.initToolbar = function() {}

// 列表渲染参考文档：http://open.seeyon.com/seeyonui/V2.0/components/index.html#___grid
DemoIndex.initGrid = function() {}


基于以上方式，一个简单的前后端页面即开发完成。


## 示例源码下载

我将这个简单的示例源码提交到Gitee，你可以从Gitee获取了完整的开发示例：https://gitee.com/qqbless/seeyon_v5_demo


## 插件化深度应用


## 插件主动停止

假设我的插件需要依赖一些基础配置，只有这些配置生效才能使用本插件，则可以继承平台PluginInitializer接口实现isAllowStartup方法：

package com.seeyon.apps.fk;

public class FKPluginDefintion implements PluginInitializer {
    @Override
    public boolean isAllowStartup(PluginDefinition arg0, Logger arg1) {
    	boolean flag = "on".equals(arg0.getPluginProperty("fk.enable"));
        return flag;
    }
}


以上完成后，需要在插件配置文件下注册initializer：\WEB-INF\cfgHome\plugin\插件名\pluginCfg.xml

<?xml version="1.0" encoding="UTF-8"?>
<plugin>
	<id>自定义</id>
	<name>自定义</name>
	<category>自定义</category>
	<!-- 自定义PluginInitializer的实现类 -->
	<initializer>com.seeyon.apps.fk.FKPluginDefintion</initializer>
</plugin>


最终效果：启动OA过程中，如果插件PluginInitializer判断isAllowStartup返回为false，则会主动停用插件，提示信息类似于：

插件[222, fk, 分库插件]的initializer[com.seeyon.apps.fk.FKPluginDefintion]禁止了此插件的启动.



## 插件初始化Initializer

假设我的插件需要从数据库初始化加载缓存，以方便后续使用，则我们需要在插件类实例化完成后，执行初始化操作。

平台绝对禁用使用Spring的init来初始化缓存：

<!-- Bad code 绝对禁止使用init-method -->
<bean name="" class="" init-method="init" ></bean>


插件化开发标准解决方案是：继承SystemInitializer并实现initialize方法，initialize方法的执行时机时：系统所有Spring初始化完成之后，由根据平台默认任务编排依次执行继承了SystemInitializer的initialize方法。

public class DemoInitializerl extends AbstractSystemInitializer {

    // 重写AbstractSystemInitializer下的initialize方法，
    @Override
    public void initialize() {
        // 此时所有Bean已经初始化完成，可以放心调用所有Bean
        TODO
    }

}



## 插件与插件解耦

由于V5平台不是云原生应用，未实现模块与模块之间微服务化，故原则上插件与插件的代码可以相互调用，但这种混乱调用会造成严重耦合性。

针对此问题，平台基于Maven做基础，要求每个插件一个Project，每个Project一份Maven，通过Maven来控制依赖：不允许插件A直接调用插件B，只能通过中间工程apps-api做中间桥梁连接，这样的代码管理就实现了插件间解耦。

相关规范和编写方法见【APPS-API解耦开发】


## 插件是否可用判断

假设插件A涉及插件B的代码调用，则要先判断插件B是否启用。如果插件B未启用，则它的所有类均未被实例化，调用就会异常。

平台提供了AppContext#hasPlugin方法用于判断插件是否启用：

if(AppContext.hasPlugin("插件B")){
	插件BAPI.xxx();
}


编撰人：admin、het


快速跳转



 * 插件化开发
   * 基础架构
   * 开发准备
     * 字符集
     * 代码结构
   * 完整开发示例
     * 定义插件
     * 三层功能开发
       * Controller层
       * Manager层
       * DAO层
     * 三层开发总结
     * JSP开发准备
     * JSP开发演示
   * 示例源码下载
   * 插件化深度应用
     * 插件主动停止
     * 插件初始化Initializer
     * 插件与插件解耦
     * 插件是否可用判断



分享链接分享链接

## 7. 如何定制开发

> 原始路径：`/38/48.html`  
> 相对路径：`38/48.md`

## 如何定制开发


## 前言

用户总会有个性化需求和集成类需求，面对A8、G6版本客户，我们提供了定制开发的机制。

我们提供了ctp-studio平台进行定制开发代码托管，防止代码丢失。同时该平台有成千上万项目成果，我们也有限地提供了重复方案共享。

原则上，我们均要求尽量接口化开发，不要侵入源码。直接修改标准产品源码是项目交付最快捷的方案，但其引发的后续维护问题：比如标准产品团队处理客户BUG时修改了客开文件，就涉及代码合并。

本章末尾【开发文档资料】提供了相关资料链接供不熟悉定制开发的技术参阅。


## 怎么做定制开发？


## 确认开发方案

平台提供了多种开发方案，用来应对不同场景开发的：

接口方案              适合场景                                        特点                     面向人群
CIP集成平台           第三方系统登录认证、数据同步                              开箱即用、低代码、零代码           运维实施
插件化开发             致远V5系统内增加新功能、无侵入源码二次开发                      解耦、模块化、可升级、V5容器下共同运行   技术开发
Restful API       第三方系统远程调用致远V5、前后端分离开发                       轻量、无侵入、快速开发、跨平台跨语言     技术开发
WebService SOAP   第三方系统远程调用致远V5                               跨平台跨语言、偏重              技术开发
Event Listener    利用插件化开发为基础，在同一容器范围内监听致远V5应用事件，去做用户需要的事情     解耦、可拆卸、可升级、V5容器下共同运行   技术开发
动态接口              （当遇到需要修改源码的场景时）通过埋点接口或Bean替换的形式达到不修改源码的目标   源码无侵入、可升级、V5容器下共同运行    技术开发
ctp-studio源码修改    以上都无法满足需求，需要修改标准产品源码文件时，可通过平台申请对应文件修改编译打包   侵入源码                   技术开发

1）CIP集成平台--开箱即用的低代码集成平台，CIP是致远V5的标准产品能力，利用可视化配置的形式实现与第三方系统的认证和信息交互，运维实施通过配置就可以完成异构系统的集成。

2）插件化开发，插件化开发是致远V5平台提供的弹性扩展架构能力，如客户期望做一个标准产品没有的功能，完全可以通过插件化开发无侵入完成；若客户期望在标准产品基础上扩展额外的功能，同样可以基于插件化+其它的接口化开发完成，插件化开发是一切开发的本源，是基本技能。

> 插件化开发文档详见"快速开始">"插件化开发"章节

3）Restful远程Http调用，Restful API是通用技术标准，通过Http远程调用V5服务，彻底做到无源码侵入、服务分离的能力。我们总计开放了几百个Rest API接口，如组织机构的增删改查均可通过Rest远程调用解决（Rest接口文档全部存放于Open Api菜单中）。

> Restful文档详见SeeyonAPi菜单

4）Webservice SOAP集成（已过时），这是多年前的异构系统通信方案，此技术采用了XML、多通信协议、WSDL方案，开发调用非常臃肿，已被现在的Rest Api和轻量级RPC框架替代，目前平台继续保留原来开放的SOAP接口，但不再扩充。新的开发请使用REST接口。

5）Event事件监听，采用类似Observable+Observer模式，其作用是监听标准产品指定动作，然后进行二次开发实现自己的需求。 如与第三方的组织机构同步，可监听标准产品组织机构的增删改Event事件，然后将事件信息推送给第三方进行数据同步。 以及监听人员处理协同、回退协同事件，以此来通知第三方刷新待办数据。

> Event事件监听文档详见"CTP技术平台">"Event事件监听"章节

6）动态接口，动态接口是V8.0SP2 LTS版本开始推出的一种致远技术标准，其存在的目的是解决前面“插件化开发”、“Rest API”、“Event事件监听”、“APPS API”无法解决的问题。比如客开需要在某个标准产品源码块中间插入一段代码以实现客户需求，过去只能通过修改源码解决。而动态接口出现以后，则是由研发在需要修改源码的位置增加一个“动态接口”埋点，客开则只需要继承该动态接口，即可无侵入源码实现客户需求。

> 动态接口文档详见"CTP技术平台">"动态接口"章节

7）修改源码，如果接口化开发无法满足，我们也允许修改源码，从ctp-studio申请源码文件修改并提交，方便做版本管理。

> 如何确认修改哪个源码文件，这个需要一定基础，文档详见“快速开始” > “问题调试分析方法”


## 按场景推荐

## 场景一：第三方主动与OA通信

如第三方系统要与标准产品进行数据增、删、改、查操作（如人员的新增、修改）。

优先使用Rest API，通过远程Rest调用。这种调用方式，二次开发可以自行搭建一个微服务项目，使用HttpClient远程调用，做到完全解耦、轻量级开发。

如果标准产品的Rest接口不够，可以通过运维支持工单向研发申请开放接口以满足需求。

如果研发一时半会开不出来，二次开发也可以自己上：通过平台的插件开发规范，新建独立的客开插件，自己编写Rest接口服务，独立插件可以引用标准产品范围内的类方法，同时也能做到对标准产品源码无侵入。

## 场景二：OA主动与第三方通信

如果OA产生的数据变化，需要同步到第三方系统。比如组织机构变化需要与第三方同步，或者统一待办集成，OA侧待办数据变化需要推送到第三方更新待办。

这种情况可以优先考虑CIP集成平台、OCIP、DEE等一系列低代码组件是否能满足需求。

如果以上不能满足需求，则必然要在标准产品中进行代码开发--监听数据变化+推送数据到第三方。我们推荐的方案依然是：新建独立的客开插件！利用平台的Event Listener监听数据变化，然后将变化数据通过某种通道推送给第三方。

优先引用标准产品的Event API。如果标准产品的Event接口不够，可以通过运维支持工单向研发申请开放接口以满足需求。

如果没有对应Event触发接口，还可以采用动态接口开发的模式，从Open API中查看是否有匹配的动态接口，在标准产品需要触发动作的地方增加动态接口埋点或者采用Bean替换直接接管标准产品对应类的方法。

## 场景三：在OA中增加新页面新功能

如果客户需要在OA中增加新的页面功能。这种场景的实现方案非常简单：通过平台的插件开发规范，新建独立的客开插件，开发独立功能即可。可以做到完全无侵入。

## 场景四：改造OA现有功能

如果客户需要改造标准产品页面功能，则涉及到与标准产品源码交互，尽量采用无侵入源码方式开发。

其开发思路是：利用Event、动态接口能力+独立的客开插件化开发规则进行无侵入开发，动态接口有专门的文档明确给出了开发思路。

最后不得已，可以申请源码来修改。


## 技术要求

为了使用V5平台进行应用开发，开发人员必须掌握以下相应的技能：


## 后端服务开发

 * Java语言编程（JDK1.8）

 * JavaEE（Servlet、Filter等）

 * Spring、Spring MVC

 * XML和JSON

 * Restful

 * 熟悉致远CTP平台技术


## 后端数据层开发

 * JDBC原理和编程方法

 * Hiberante原理与编程方法

 * 数据库的配置和使用：Postgresql、MySQL、Oracle、SQL Server等


## 前端界面开发（JSP）

 * JavaSrcipt基本用法

 * CSS的使用

 * JSP/JSTL/EL

 * JQuery

 * Ajax

 * SeeyonUI框架代码


## 前端界面开发（Html）

 * JavaSrcipt基本用法

 * CSS的使用

 * HTML结构、Html5特性

 * VueJs

 * Ajax


## 移动应用开发（Html5）

 * JavaSrcipt基本用法

 * CSS的使用

 * HTML结构、Html5特性

 * 熟悉致远CMP平台API




## 开发文档资料

编号   开发类型                                          文档资料
0    开发准备、环境搭建                                     本站>快速开始：安装协同系统、搭建开发环境、代码管理、插件化开发，依次看完
1    培训视频文档（很丰富）                                   链接：https://pan.baidu.com/s/1bPzZad2VEnDBuDetUytXMg 提取码：tpje
2    问题分析排查、源码文件搜索                                 本站>快速开始>常见调试分析方法
3    安全类开发规范（与OA相关）                                本站>快速开始>安全开发规范
4    平台组件类：系统框架、数据库操作、日期/缓存/国际化/消息/AJAX等各种组件       本站>开发文档>CTP技术平台
5    移动端开发：M3 H5/微协同H5标准产品开发或集成三方开发，第三方APP集成H5开发   技术文档>移动开发文档 https://open.seeyoncloud.com/cmpdev/
6    前端开发：Vue、CSS、常见前端规范                           本站>开发文档>前端文档
7    表单业务开发：自定义控件、表单内页面操作                          本站>开发文档>CAP应用平台
8    致信客户端开发                                       1、致信平台https://zhixin.seeyon.com/doc ；2、编号1培训视频
9    部分客开场景的解决方案                                   本站>开发文档>技术解决方案
10   集成类解决方案                                       1、培训视频；2、ctp-studio复用别的项目方案；3、技术文档>集成平台
11   第三方调用本系统Rest接口                                技术文档>SeeyonAPI

编撰人：admin、het


快速跳转



 * 如何定制开发
   * 前言
   * 怎么做定制开发？
     * 确认开发方案
     * 按场景推荐
       * 场景一：第三方主动与OA通信
       * 场景二：OA主动与第三方通信
       * 场景三：在OA中增加新页面新功能
       * 场景四：改造OA现有功能
   * 技术要求
     * 后端服务开发
     * 后端数据层开发
     * 前端界面开发（JSP）
     * 前端界面开发（Html）
     * 移动应用开发（Html5）
   * 开发文档资料



分享链接分享链接

## 8. 安装协同系统

> 原始路径：`/38/50.html`  
> 相对路径：`38/50.md`

## 安装协同系统

作为开发人员，安装一个本地的协同环境，随时方便本地测试、调试是必须的。

致远提供了完整的安装手册文档和安装程序，另外启动本地协同环境需要获得授权Lic，以上三件套均可以联系致远的客户经理获取。

安装程序和文档取自致远商务公布的统一下载地址，安装部署手册名叫《致远 协同管理软件 XX版本 产品安装维护手册.docx》。


## Windows环境安装步骤


## 操作总览

安装一个本地环境整体步骤如下：

 1. 安装本地数据库，推荐MySQL5.7
 2. 下载并运行安装程序，按照引导安装服务到本地
 3. 配置参数，放入Lic授权文件，启动系统


## 安装MySQL5.7

前提是您本地没有安装MySQL，如果您本地安装过MySQL，我们建议您重新安装，因为V5服务对MySQL数据库配置有要求，比如UTF8编码集、lower_case_table_names忽略大小写等配置。如果使用你原本的MySQL数据库，在安装过程中可能遇到各种莫名问题。

> 操作参考：https://www.cnblogs.com/jyiqing/p/6924062.html

1）下载绿色免安装zip版本

2）将MySQL5.7解压到指定目录，如D:\Develop\mysql-5.7.12-winx64

3）解压后的MySQL目录下默认没有data文件夹，也不要去创建data文件夹！

4）在MySQL目录下增加一个my.ini文件，my.ini文件内容包含如下代码片段（注意basedir和datadir由你自己存放目录决定，尤其是注意datadir是数据存放地址，并且先不要创建这个文件夹，这个文件夹由MySQL自动生成）

[mysqld]

port = 3306

basedir=D:\Develop\mysql-5.7.12-winx64

datadir=D:\Develop\mysql-5.7.12-winx64\data

max_connections=200

character-set-server=utf8

default-storage-engine=INNODB

sql_mode=NO_ENGINE_SUBSTITUTION,STRICT_TRANS_TABLES

lower_case_table_names=1

[mysql]

default-character-set=utf8


5）以管理员身份运行cmd命令

6）在cmd命令窗口执行脚本，跳转到mysql的bin目录下

>d:
>cd cd D:\Develop\mysql-5.7.12-winx64\bin


7）完成上一步之后，在cmd命令窗口运行命令安装mysql

>mysqld –install


8）完成上一步之后，在cmd命令窗口执行初始化命令（我是执行的mysqld --initialize-insecure）

>mysqld --initialize-insecure --user=mysql --explicit_defaults_for_timestamp


9）完成上一步之后，在cmd命令窗口启动mysql服务

>net start mysql


10）完成上一步之后，在cmd命令窗口登录mysql（输入如下命令后回车会提示输入密码，默认密码为空，直接回车即可）

>mysql –u root –p


11）完成上一步之后，在cmd命令窗口修改数据库密码

## 先定位到mysql数据库，敲击回车
>use mysql;
## 再执行更新密码，回车
>update user set authentication_string=PASSWORD("seeyon123456") where user="root";
## 再更新权限，回车
>flush privileges;
## 最后退出mysql，重新登录就要求输入密码了
>quit;


12）安装完成后，MySQL会默认注册到服务中自启动，如果没有自启动就需要自己去设置开启：搜索“服务”，找到MySQL启动

13）为了方便mysql命令执行，可以将mysql的bin注册到环境变量PATH中，随后您就可以通过cmd命令行在任何地方运行mysql（操作方法可百度）

14）关于数据库连接工具，请使用正轨途径授权的工具或免费工具：

开源免费的可视化工具 dbeaver Community Edition



更多数据库调优见关联文档：https://open.seeyoncloud.com/v5doc/142/1184/144.html


## 安装V5服务

1）前期准备

 * 首先保证本地电脑有足够内存资源，需占用内存4G
 * 提前准备好加密狗License授权文件
 * 提前准备好安装程序SeeyonInstall（一般从致远客户经理初获取下载链接）
 * 提前下载好安装维护手册，以便随时查阅问题（一般从致远客户经理初获取下载链接）

2）确认安装的版本

安装程序是一个SeeyonInstall文件夹，文件夹里面的内容大概如下图所示，其中A6-1指A6+产品，A8-1指A8+企业版，A8-2指A8+集团版，你需要根据需求安装对应版本。同时你申请的加密狗License也会对应产品版本，加密文件和安装的版本不匹配也无法启动。

高版本开始，会检查服务器环境是否满足要求，有可能安装时会因为CPU核心数不足、虚拟内存不足不让安装。如果是本地个人使用，可以通过调整配置跳过限制，调整限制的配置文件路径SeeyonInstall\inst\check.yml，如何修改不做赘述，都是搞技术的，相信你看得懂。

数据库校验不通过，配置调整方法：https://open.seeyoncloud.com/v5doc/142/1184/144.html

3）上一步完成之后，开始按照引导进行一步一步的安装操作

缺省安装地址最好改一下，默认在C:\Seeyon\A8下，建议改为D:\Seeyon\A8，非系统盘毛病少些，后续操作均使用D:\Seeyon\A8目录做演示。

数据库设置：类型MySQL，数据库名自定义如v5，服务器地址localhost，端口3306，用户名root，口令是前面安装数据库设置的密码，如seeyon123456

> 注：MySQL无需提前连接到数据库去创建database，如果你所输入的数据库名不存在，安装程序会自动去创建

初次安装完成需要设置管理员密码，需要设置复杂一点，比如Seeyon123456

最终你的V5安装之后的文件存放在D:\Seeyon\A8，现在你需要在此目录下进行一些操作才能启动使用。

4）修改应用配置器

安装完成后，运行D:\Seeyon\A8\ApacheJetspeed\conf\SeeyonConfig.cmd这个文件，来完成协同服务的端口、JVM配置，以及检查数据库连接/调整连接池大小等操作。

> JVM配置最小4G，再小很容易启动不了！



5）准备加密狗License授权文件

默认安装的服务没有授权文件，无法启动。

受官方认可的加密狗获取方式只有一条通道--由致远客户经理提请，向致远商务申请的标准Licence！

从致远商务申请，有效的加密授权有五种：

 * 通卡：这是一个USB硬件狗，插到电脑上就可以用，最大登录限制是5并发，默认拥有所有插件的使用权限（但无Office控件权限）。需要向商务申请，并且交付押金。
 * 正式硬加密狗：这也是一个USB硬件狗，里面有正式用户的授权，没有使用期限，插到服务器上就可以用。其功效跟下面正式软加密一模一样，唯一区别是它是一个USB Key，现在这种狗使用量较少，大多数用户采用正式软加密。
 * 正式软加密：这是一个加密文件，里面有正式用户的授权，没有使用期限，将文件拷贝到客户服务器上激活后即可使用。我们的正式用户大多采用此方式。
 * 试用软加密：这是一个加密文件，功能跟正式软加密一样，只是里面有使用期限限制（一般3个月左右），过期之后无法启动服务。
 * Seeyonconfig共享加密：机制是多个测试环境可以共享主服务的加密授权，只是最大登录限制是5并发，详情见下面“共享加密”章节说明。

> 至于通过别的渠道获取的.js、.jar类型的所谓的“通狗”都不是正规加密授权（有的只是研发内部专用授权），致远也不受理这类授权环境的支持工单。

6）放置软加密文件

正式硬加密狗、正式软加密、试用软加密在申请下来之后都需要联网激活，激活工具在安装程序SeeyonInstall下面的updateDog文件夹里。



注册完成之后，将生成的软加密文件放置在本地协同服务器A8\base\license目录下。

7）启动本地服务

运行A8\ApacheJetspeed\bin\startup.bat进行启动，启动需要一定时间(大约5~10分钟），当出现“startup.Catalina.start Server startup in xxxxxx ms”字样则表示启动成功。如果你很长一段时间都没反应，可能是跟快速编辑模式有关，尝试取消快速编辑模式，再重新启动startup.bat。





8）浏览器访问V5系统，确认是否可以使用

启动本地环境完成之后，本机使用浏览器访问：http://localhost/seeyon ,进入登录页则表示启动成功。



9）登录系统，进行组织机构初始化

关于默认登录帐号，不同版本有不同的情况：

 * （大约）V7.1SP3之前的系列版本，安装完成之后，默认预制了group-admin和system帐号，默认密码是123456
 * （大约）V8.0~V8.0SP2系列版本，在安装过程中就会让你输入集团管理group-admin和系统管理员system的密码（这一切都为了安全考虑）
 * V8.1版本开始，又有了新的预制变化：系统废弃了group-admin和system帐号，改为了一号多权（三员角色化模式），初始安装的时候只需要设置一个初始化管理员帐号即可

> 三员角色化：即公司的IT人员有自己的个人帐号，可以让自己的个人帐号绑定集团管理员和系统管理员，随后只需使用一个个人帐号即可快速切换到不同平台去做管理。

如果你按照前面规则安装V5服务，并且在安装过程中已经输入了对应帐号密码，则可以执行登录操作。首先使用集团管理员帐号，依次建岗位、职务级别、单位名称、单位管理员帐号。再登录自己创建的单位管理员帐号，进行本单位的部门、人员录入。


## 卸载操作

卸载协同的命令工具在：A8\Uninstall_A8\uninstall.bat，Windows下需要以管理员身份运行，并且注册表信息需要存在。如果你手动删除过注册表，则直接删除整个协同目录即可。

删除过程中如果遇无法卸载提示，则需要先卸载S1服务。S1服务在\A8\S1目录下找到nssm_uninstall.bat、uninstall_s1_agent_link.bat这类带unistall的执行文件，以管理员身份运行并执行卸载。如果运行无反应，则考虑直接将整个S1文件夹删除掉。


## 安装多版本

默认情况下，一台电脑只能安装一个版本，执行安装过程中会先读取注册表信息，如果注册表存在版本信息，安装程序会自动进入升级或修复安装，不会创建多版本。

注册表位置在：cmd命令->regedit->打开注册表->计算机\HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\SEEYON\A8

如果你想要安装多版本，则可以删除上面注册表的信息，随后就可以多版本共存了！

如果打不开注册表，可以用命令的形式删除，首先以管理员身份启动cmd窗口，然后在cmd中执行reg delete HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\SEEYON /f也可以删除

编撰人：admin、het




快速跳转



 * 安装协同系统
   * Windows环境安装步骤
     * 操作总览
     * 安装MySQL5.7
     * 安装V5服务
   * 卸载操作
   * 安装多版本



分享链接分享链接

## 9. 开发环境搭建

> 原始路径：`/38/51.html`  
> 相对路径：`38/51.md`

## 开发环境搭建

本篇的开发环境特指Java开发环境，后端环境需要依赖Jar包才能调用到需要的类。我们的开发环境搭建，通常就两种：一种是基于Maven的环境，一种是无Maven环境。


## 有Maven搭建环境（主推）

致远标准产品Jar包均使用内部Maven仓库管理，基于Maven搭建环境是最高效的方案。

对于二次开发用户，我们要求使用致远CTP Studio代码托管平台开发，此平台具备完整的环境搭建能力。


## 基于CTP-Studio搭建

> CTP-Studio是致远面向合约客户的定制开发代码托管平台，如客户与致远签订了客开合约，则致远会负责在平台开通托管项目。为了保障安全性，代码托管平台由内网管理，外网访问需要通过致远开通VPN权限。

致远提供了ctp-studio平台供一线进行客户化开发，ctp-studio完成了源码分权控制、帐号统一管理、Maven化、代码统一管理的能力。

标准客开请统一按照致远客开总部关于CTP Studio的要求进行相关源码申请、帐号开通、环境搭建。


## 基于Gitlab搭建

内部研发采用Gitlab私服平台进行代码管理，结合Maven仓库完成快速搭建。

## 配置Gitlab

1、首先需要安装 Git GUI，Git各平台安装包下载地址为：http://git-scm.com/downloads

2、Git GUI安装完成之后，通过鼠标右键运行Git Bash Here，分别执行以下两句命令：

git config --global user.name "你的真实姓名" 
git config --global user.email "你的邮箱地址"


3、下面是获取本机的SSH Key，将其配置到gitlab代码管理平台上，配置之后，本地连接gitlab平台就无需再输入帐号密码了。以下操作也使用Git Bash命令窗口完成。

4、首先确定本机是否生成过sshkey：在C:\Users\Administrator目录下确认是否有.ssh文件夹，打开这个.ssh目录会看到id_rsa和id_rsa.pub。

5、如果未生成.ssh则执行生成公钥和私钥的命令ssh-keygen -t rsa并按回车3下（为什么按三下，是因为有提示你是否需要设置密码，如果设置了则每次使用Git都会用到密码，一般都是直接不写为空，直接回车就好了）。

ssh-keygen -t rsa


6、使用Git Bash执行查看公钥的命令

cat ~/.ssh/id_rsa.pub




7、将这段公钥复制粘贴到gitlab中：Settings->SSH Keys里面（公钥以ssh-rsa开头，末尾去掉回车）



## 拉取Gitlab工程

1、访问Gitlab，找到有权限的工程， 选择“克隆”>>“使用 SSH 克隆”，拷贝该工程的SSH地址：



2、回到本机，自己准备一个放置代码的目录，在目录下同样通过Git Bash命令窗口执行git clone命令将代码拉取到本地：

## 当前链接仅仅是示例，具体URL请自己提取
git clone git@gitlab.seeyon.com:cdp/apps-task.git




3、完成git clone之后，能在本机代码目录下见到clone下来的工程目录



常见问题： 部分gitlab服务禁用了SSH相关端口，无法通过SSH克隆仓库，则改成HTTP克隆+手动输入gitlab帐号密码也是可行的：



克隆命令是相似的，只是会要求输入gitlab的帐号密码做认证：

## 当前链接仅仅是示例，具体URL请自己提取
git clone http://gitlab.seeyon.com/ctp/apps-task.git


## 使用Eclipse搭建环境

下面使用Eclipse搭建开发环境，本示例是通过Eclipse的Git插件直接将Gitlab私库代码拉取到工作目录。

1、首先是配置Maven仓库文件，在Windows->Preferences->搜索maven->User Settings中自定义配置前面新建的这个settings.xml。

注意：这里的settings.xml不是随便找的，一定是与项目Maven私库相关联的配置文件，这个文件一般内部相互流传。

2、Eclipse选择File->Import->Git->Projects from Git(with smart import)->Clone URI->仅输入URI即可->选择自己想要Clone的分支到本地->设置本地仓库位置->下载即可。

> 采用smart import能保证Eclipse自动识别工程类型，比如看到pom.xml则自动转换为maven目录结构







3、以上操作完成后，Maven插件理论会自动下载当前工程所需的jar包。

如果Maven未执行拉取，则通过选中pom.xml>鼠标右键Maven>Update Maven Project点击确定刷新工程依赖。

## IntelliJ IDEA搭建环境

下面使用IDEA工具搭建开发环境。

1、首先是配置Maven仓库文件，通过File>Settings>搜索Maven，找到配置user setting的文件，保存即可。

注意：这里的settings.xml不是随便找的，一定是与项目Maven私库相关联的配置文件，这个文件一般内部相互流传。



2、如果是新建的projects空间，先设置当前空间的JDK版本，通过FIle>Project Structure>Project Settings>project设置Project SDK为“jdk1.8”；设置project language level为8。

3、导入Gitlab工程：在上一步Project Structure界面选择Modules>选择Import Module，找到刚才git clone下来的工程目录，以Maven的形式导入。



4、初次搭建开发环境，需要等待一段时间，以上操作完成后，IDEA会自动拉取该工程所依赖的所有jar文件。

如果没有自动拉取依赖包，则可以选中pom.xml文件，鼠标右键>Maven>Reload Project来加载依赖包。

5、上一步完成之后，尝试Build编译一下本地工程：Build导航菜单>执行Build Module “工程”操作。最终编译结果生成在：你本地的Gitlab工程目录\target\classes下面。

6、V5工程非常多，如果你有多个工程权限，可以在一个IDEA Projects空间中导入多个工程。操作方式重复3、4、5步即可。




## 无Maven搭建环境（不推荐）

在早期版本，没有经过Maven控制，或者当前环境非常特殊，拿不到Maven仓库配置，故只能采用无Maven方式搭建环境。这类场景下，搭建开发环境的思路则是：直接依赖jar包完成。

无论哪种IDE开发工具，首先需要安装一套完整的OA服务，可以自己本地安装，也可以从正式服务器获取。搭建环境时需要从OA服务中依赖必要的jar包。




## Eclipse环境搭建（无Maven）

以下示例为基于Eclipse开发工具搭建环境：

1）通过Eclipse创建一个空的Dynamic Web Project，Runtime运行时环境需要依赖Tomcat和JDK：

Tomcat不用自备，第一步安装好的V5服务就是一个标准的Tomcat，选择本地安装好的V5服务Apachejeetspeed文件夹即可。

JDK是根据不同Tomcat版本做选择：比如Tomcat6对应JDK6，而本例Tomcat8.5则是JDK8，JDK开发自备。



2）一个Dynamic Web Project基本配置如下：



3）下一步，对工程添加Jar包依赖：

首先Tomcat中间件和JDK的依赖已经在创建Dynamic工程的时候引入。

下一步是引入V5需要的所有Jar，这些Jar位于OA服务A8\ApacheJetspeed\webapps\seeyon\WEB-INF\lib文件夹下，使用Add Extenrnal JARs的方式引入该目录下全部jar包。



4）尝试是否能引用到OA相关API：如下图所示，可以建一个Java类，尝试引用com.seeyon下面V5的API，如果下图所示引入成功，则说明环境搭建完成。




## IntelliJ IDEA环境搭建（无Maven）

以下示例为基于IDEA开发工具搭建环境，本次演示条件是“有一个源码工程，但没有Maven”的场景，看下如何搭建。

1）假设只有一个apps-task工程，但我没有该工程所依赖的Maven环境，也download不到相关依赖包。



2）基于以上背景，我们还是要首先安装与这个工程相匹配的OA服务环境，我们需要依赖这个OA服务下的jar包文件，安装过程在这里略过。

3）如果IDEA是新建的projects空间，先设置当前空间的JDK版本，通过FIle>Project Structure>Project Settings>project设置Project SDK为“jdk1.8”；设置project language level为8。

同时通过File>Setting>Java Compiler设置确保项目是JDK8编译。

4）在上一步Project Structure界面选择Modules>选择Import Module，找到刚才git clone下来的工程目录，同样以Maven的形式导入。

虽然无法成功连接Maven私库，但这样做的目的是让工程在IDEA中以Maven约定的结构展现。



5）为了确保编译成功，通过FIle>Project Structure>Modules选中当前项目，在右侧选择Dependencies引入Jar报依赖，需要分别引入Tomcat和安装好的OA下的WEB-INF\lib所有jar。



6）最后Build工程，如果发现还有编译报错就确认自己哪里弄错了。如果是test目录下的单元测试编译不通过，建议删除单元测试模块代码，像TestCaseBase的依赖只有Maven私库才有。


## 扩展资料


## Eclipse重要插件

## decompiler反编译

 * Eclipse Marketplace搜索decompiler，安装enhanced class decompiler
 * 重启后Preferences中搜索File Associations可查看反编译设置，设置.class without source文件defualt以decompiler插件启动

## FileSync文件同步

 * Eclipse Marketplace搜索搜索file sync，安装FileSync
 * 使用场景：将Eclipse中的project代码同步到本地OA服务器对应目录下



## ResourceBundle Editor国际化插件

 * Eclipse Marketplace搜索i18n，安装ResourceBundle Editor
 * 使用场景：同级目录下同名不同语种的国际化properties可以一同编辑修改自动排序




## IntelliJ IDEA推荐插件

插件搜索和安装方法：IDEA > File > Settings > Plugins

## 通义灵码

通义灵码，一款基于通义大模型的智能编码辅助工具，提供行级/函数级实时续写、自然语言生成代码、单元测试生成、代码注释生成、代码解释、研发智能问答、异常报错排查等能力，并针对阿里云 SDK/API 的使用场景调优，为开发者带来高效、流畅的编码体验。

安装方式：Marketplace应用市场搜索“tongyi”，找到TONGYI Lingma，安装即可。



编撰人：admin、het


快速跳转



 * 开发环境搭建
   * 有Maven搭建环境（主推）
     * 基于CTP-Studio搭建
     * 基于Gitlab搭建
       * 配置Gitlab
       * 拉取Gitlab工程
       * 使用Eclipse搭建环境
       * IntelliJ IDEA搭建环境
   * 无Maven搭建环境（不推荐）
     * Eclipse环境搭建（无Maven）
     * IntelliJ IDEA环境搭建（无Maven）
   * 扩展资料
     * Eclipse重要插件
       * decompiler反编译
       * FileSync文件同步
       * ResourceBundle Editor国际化插件
     * IntelliJ IDEA推荐插件
       * 通义灵码



分享链接分享链接

## 10. 代码版本管理

> 原始路径：`/38/56.html`  
> 相对路径：`38/56.md`

## 代码版本管理


## Git版本管理（主流）


## 总述

git 是一种版本控制系统，是一个命令，是一种工具。

git是分布式版本控制系统，市面上有github、gitee、gitlab，它们的区别可以参考文章：https://blog.csdn.net/weixin_45664402/article/details/117061418


## Git使用经验

## 使用准备

使用Git首先需要在本机安装Git Client，网上搜索“Git下载”即可获得地址：https://git-scm.com/downloads

这是一个命令行工具，安装之后通过鼠标右键找到Git Bash Here即可快速打开命令行窗口，除了可以执行git本身命令外，还可以在Windows系统下执行Linux的一些命令。

除此之外，也可以下载TortoiseGit可视化工具，这个工具类似TortoiseSVN，一定程度上可以让SVN用户快速过渡。

Git GUI安装完成之后，通过鼠标右键运行Git Bash Here，分别执行以下两句命令，这个非常关键，务必设置真实姓名，您在Gitlab上面的提交记录都是跟这个有关：

git config --global user.name "你的真实姓名" 
git config --global user.email "你的邮箱地址"


## 使用SSH Keys

从远端Git代码仓库克隆代码、更新代码、推送代码都需要帐号密码权限，每次重复输入很麻烦，SSH Keys提供了一种机制无需输入帐号密码也能完成所有远端Git代码仓库交互操作。

建议使用Git时都在远端仓库配置上SSH Keys。具体配置方法可以见另一篇文档“搭建开发环境”篇，或者自行从网上查询。


## Gitlab常用操作

## 获取项目权限

Gitlab中的owner和maintainer具有项目授权的权利，通过Gitlab在线系统-对应工程-成员菜单进行授权。



## 角色权限级别

在授权过程中，整个Gitlab有如下的角色，授权人可以根据申请人的身份级别给予对应权限。

一般开发人员给予developer可读可写的权限，如果你想让人协助代管此工程，则可以给予maintainer权限。

角色名          权限
guest        project中的wiki文档查看
reporter     只读：只能clone、查看项目代码，无法提交代码到远端仓库
developer    读写：在无保护分支中正常读写代码，在受保护分支可发起合并请求由更高角色审批通过后合并代码
maintainer   管理员：可读写代码、可管理当前项目及授权maintainer、developer、reporter、guest权限
Owner        超管：可读写代码、可管理当前项目及授权maintainer、developer、reporter、guest权限

## Clone代码

将代码从远程仓库clone到本地，通过命令行完成clone操作（示例摘抄自Gitee帮助中心）：

$ git clone https://gitee.com/用户个性地址/HelloGitee.git #将远程仓库克隆到本地


## 提交代码

通过命令行将代码推送到远程仓库示例如下：

$ git add . #将当前目录所有文件添加到git暂存区
$ git commit -m "my first commit" #提交并备注提交信息
$ git push origin master #将本地提交推送到远程仓库


不同开发工具IDE同样提供了快速推送代码的操作，通常推送代码需要如下操作：

1、新增文件，需要将文件执行Add操作，推荐设置新增文件自动Add

2、修改代码之后，先执行commit File操作，添加提交备注，执行commit操作（不允许使用commit and push）

3、接下来先执行pull操作，确认下远程仓库代码是否存在冲突，冲突之后则进行代码合并

4、以上完成之后执行push操作，将代码最终推送到远程仓库



## Merge Request

在个人项目，我们通常都是用push的形式将代码合并到远程仓库。而在大型项目中，为了保证代码的编写质量，往往需要进行代码Review，而Git的Merge Request特性就是用于解决代码Review问题的。

场景演示：我现在需要修改一个问题，将修复代码合并到dev分支，通过Merge Request的操作步骤为：

1、通过访问gitlab在线系统或自己的IDE创建一个新分支，分支名自定义如dev-merge，选择分支复制自dev。

2、开发将dev-merge分支checkout到本地，然后在该分支上修改代码。

3、随后开发通过commit+push操作将代码推送到远程的dev-merge分支上。

4、开发通过gitlab在线系统找到dev-merge分支能看到刚才自己提交的代码记录，检查代码无误后，通过“创建合并请求”按钮发起Merge Request，合并目标选择dev，并填写相关备注。

5、Merge Request发起之后，开发通知工程管理员合并代码。

6、工程管理员可以通过gitlab在线系统右上角“合并请求”图标快速找到Merge Request，在线看到代码差异，在线Review，如果通过则一键合并，如果不通过则关闭本次Request，一键合并之后代码自动合并到dev分支。

网上有很多图文操作，可以自行学习：https://blog.csdn.net/qq_38875300/article/details/105050562

## 分支A全量合并到分支B

分支A有20条代码提交记录，并且来自不同开发，此时项目组要求将分支A的所有代码记录合并到分支B以保证两个分支的代码保持一致。

下面使用IntelliJ IDEA演示如何快速完成合并：

[分支A]的代码合并到[分支B]

1、checkout[分支B]，保证本地项目所在分支为[分支B]

2、在右下角选择分支列表，找到远程分支[origin/分支A]，点击箭头符号，选择“Merge selected into current”，意思是将[origin/分支A]的合并到[分支B]

3、如果没有冲突，执行上一步操作后会自动merge成功，如果有冲突会弹出比对窗口，此时需要开发手动选择使用哪个分支的代码

4、上一步merge等同于自动commit，最后对[分支A]执行push操作即可将变更推送到远程仓库

## 挑选部分提交记录合并到分支B

分支A有20条代码提交记录，此时项目组要求只将分支A中某几条记录合并到分支B，可以使用cherry-pick完成。

下面使用IntelliJ IDEA演示如何cherry-pick部分提交记录：

[分支A]的一部分代码cherry-pick到[分支B]

1、checkout[分支B]，保证本地项目所在分支为[分支B]

2、在底部工具栏“Git”中找到所有的分支列表，再找到当前工程的远程[origin/分支A]分支，鼠标左键单击之后，在右侧能看到该分支的所有提交记录

3、在上一步基础上，选择你要合并的提交记录，再用鼠标右键选择“Cherry-pick”即可，此步操作等于将远程[分支A]指定记录commit到本地[分支B]

4、最后对[分支A]执行push操作即可将变更推送到远程仓库

## 回滚commit记录

对于已经commit提交的代码记录，如果想反悔不提交的话，不同场景下有不同方式，IntelliJ IDEA提供了Undo Commit，Revert Commit，Drop Commit三种操作，对应使用效果见：https://blog.csdn.net/qq_33637730/article/details/123256813


## SVN版本管理（非主流）


## 总述

SVN是subversion的缩写，是一个开放源代码的版本控制系统，通过采用分支管理系统的高效管理，简而言之就是用于多个人共同开发同一个项目，实现共享资源，实现最终集中式的管理。

SVN在过去是一种主流的版本管理工具，现在Git是主流的版本管理工具。


## SVN使用经验

## 使用准备

使用SVN首先需要在本机安装TortoiseSVN，这是一个可视化工具，可以进行SVN下载、上传、还原等全部操作。

开发工具则需要安装SVN相关插件，有SVN插件后可以在开发工具中直接上传下载代码。


## 常用操作



## 下载项目

SVN每个分支都是一个URL，在管理员授予相关读取权限后即可下载。

在安装好TortoiseSVN的基础上，通过鼠标右键，选择“SVN Checkout”，输入对应工程分支的路径，再输入自己的帐号密码即可下载。

## 更新文件

如果SVN仓库有内容变更，本地需要进行更新。

在安装好TortoiseSVN的基础上，找到本地对应SVN目录，通过鼠标右键，选择“SVN Update”即可完成更新

## 提交文件

本地文件修改之后，需要提交到SVN仓库。

在安装好TortoiseSVN的基础上，找到本地对应SVN目录，鼠标右键，选择“SVN Commit”，添加提交备注后确定。

## 还原本地记录

本地修改的文件还未提交到中央仓库，此时需要废弃本地的修改文件，可使用revert操作。

在安装好TortoiseSVN的基础上，鼠标右键>TortoiseSVN>Revert会弹出变更的问题，手动选择需要还原的操作即可。

## Clean文件锁

如果提交冲突、提交时网络中断、update更新网络中断，很容易出现文件lock问题，此时无法提交、无法更新代码，需要使用clean操作清理lock文件。

在安装好TortoiseSVN的基础上，鼠标右键>TortoiseSVN>选择Cleanup操作即可。

## 查看提交记录

在安装好TortoiseSVN的基础上，鼠标右键>TortoiseSVN>Show log可以弹出提交记录。

在log记录列表中，选择两个提交鼠标右键>Compare reversions能看到两个文件的差异。

## 预览目录

如果想预览指定路径下有哪些文件，可以不用checkout文件，使用Repo-browser也能完成。

先准备好自己有权限的SVN URL，在安装好TortoiseSVN的基础上，鼠标右键>TortoiseSVN>选择Repo-browser即可预览该URL下的所有文件。

## 导出无SVN记录的文件

如果将整个文件夹拷贝到别的位置，此文件夹也会卸载SVN记录，为了保证复制到别处的文件夹是干净的文件，需要使用Export导出操作。

在安装好TortoiseSVN的基础上，鼠标右键>TortoiseSVN>选择Export to>最后选择目标文件夹，即可将SVN文件导出到别的目录并且不卸载SVN记录。

编撰人：admin、het


快速跳转



 * 代码版本管理
   * Git版本管理（主流）
     * 总述
     * Git使用经验
       * 使用准备
       * 使用SSH Keys
     * Gitlab常用操作
       * 获取项目权限
       * 角色权限级别
       * Clone代码
       * 提交代码
       * Merge Request
       * 分支A全量合并到分支B
       * 挑选部分提交记录合并到分支B
       * 回滚commit记录
   * SVN版本管理（非主流）
     * 总述
     * SVN使用经验
       * 使用准备
     * 常用操作
       * 下载项目
       * 更新文件
       * 提交文件
       * 还原本地记录
       * Clean文件锁
       * 查看提交记录
       * 预览目录
       * 导出无SVN记录的文件



分享链接分享链接

## 11. 开发规范

> 原始路径：`/38/57.html`  
> 相对路径：`38/57.md`

## 开发规范


## Java编码规范


## 命名规范

Package命名 [NAMING.PKG-2]

描述：

Package名必须为小写字母或数字，且必须以字母开头；

平台产品中要求包名为com.seeyon.ctp.xxx或com.seeyon.apps.xxx

xxx为应用名如collaboration、edoc ...

示例：

// CTP平台表单模块
package com.seeyon.ctp.form;

// 会议应用
package com.seeyon.apps.meeting;


Class命名 [NAMING.NCL-2]

描述：

Class名首字母必须大写，如果是某个Interface的实现，要求命名采用Interface + Impl

示例：

public interface CollaborationManager{};
public class CollaborationManagerImpl implements CollaborationManager{
}


Interface命名 [NAMING.NITF-2]

描述：

Interface命名首字母必须大写

示例：

public interface CollaborationManager{
}


Exception Class命名 [NAMING.NE-2]

描述：

Exception class命名必须以Exception结尾

示例：

public class NEFormatException extends Exception{
}


Unit Test Class命名 [NAMING.NE-2]

描述：

Unit test class命名必须以Test结尾

示例：

public class FooTest extends TestCase{
}


Enum type命名 [NAMING.NENUM-2]

描述：

Enum type命名首字母必须大写

示例：

private enum Grade { 
    A, B, C, D, F 
};


Methods命名 [NAMING.NMP-2]

描述：

Method命名首字母必须小写

示例：

public class NMFixed {
    void method () {  // FIXED
    }
}


Local variables命名 [NAMING.NLV-2]

描述：

Local variable命名首字母必须小写

示例：

private int example = 0;


常量命名 [NAMING.USF-2]

描述：

所有用 ”final”、”static” 修饰的变量命名要求全大写

示例：

public static final int SIZE = 10;
private static final Logger LOGGER;


类名禁止使用java内置类名 [NAMING.DJLO-2]

描述：

类名禁止使用java内置类名

错误示例：

public class Integer{
}


标示符禁止使用java关键字 [NAMING.DJLO-2]

描述：

标示符禁止使用java关键字

错误示例：

private String enum;
private int assert;


禁止使用sun预留包名 [NAMING.RPKG-2]

描述：

禁止使用sun预留包名

错误示例：

package java.rules.naming;


禁止仅通过大小写区分变量 [NAMING.UUVN-4]

描述：

禁止仅通过大小写区分变量

错误示例：

int foo = 9;
int Foo = 9;



## 注释规范

java文件头注释 [FORMAT.MCH-2]

描述：

所有java文件需要在文件头添加如下注释段：

/**
 * $Author$
 * $Rev$
 * $Date::                     $:
 *
 * Copyright (C) 2012 Seeyon, Inc. All rights reserved.
 *
 * This software is the proprietary information of Seeyon, Inc.
 * Use is subject to license terms.
 */
package xx.xx.xx;
import xx.xx;


java类注释 [JAVADOC.PJDC-2]

描述：

所有java类需按以下格式添加类注释：

/**
 * <p>Title: 应用模块名称</p>
 * <p>Description: 代码描述</p>
 * <p>Copyright: Copyright (c) 2012</p>
 * <p>Company: seeyon.com</p>
 */
public final class MyClass


方法注释 [JAVADOC.PJDM-2]

描述：

所有方法需按以下格式添加方法注释，继承的方法可以使用’@see’、’ @inheritDoc’ tag：

/**
  * Executes a mapped SQL SELECT statement that returns data to populate
  * a number of result objects within a certain range.
  *
  * @param id The name of the statement to execute.
  * @param skip The number of results to ignore.
  * @param max The maximum number of results to return.
  * @return A List of result objects.
  * @throws java.sql.SQLException If an error occurs.
  */

  List queryForList(String id, int skip, int max) throws SQLException;


相关校验点：

> [JAVADOC.DPMT-2]** 避免无用的javadoc tag
> 
> [JAVADOC.MDJT-2]** 注释内容要有意义
> 
> [JAVADOC.PARAM-2]** 每个param都要有'@param' tag
> 
> [JAVADOC.MRDC-2]** 有返回值的方法必须使用'@return' tag
> 
> [JAVADOC.THROW-2]** 有异常抛出的方法必须使用'@throws' 或 '@exception' tag
> 
> [JAVADOC.VMCR-2]** 无返回值的方法不要有'@return' tag
> 
> [JAVADOC.BT-4]** 不允许使用javadoc中未定义的'@' tag


## 格式规范

代码长度限制 [FORMAT.LL-2]

描述：

每行代码长度不能超过120个字符

每个声明占用一个代码行 [FORMAT.OSPL-2]

描述：

每个声明占用一行代码

错误示例：

int i = a + b; return i;


正确示例：

int i = a + b;
return i;


使用括号分隔复杂表达式 [FORMAT.APAREN-3]

描述：

使用括号分隔复杂表达式提高代码可读性

错误示例：

if (i >= j && i >= 0)


正确示例：

if ((i >= j) && (i >= 0))


**避免过于复杂的判断表达式

if ( workTimeSpecials.size() > 0 && !workTimeSpecials.get(0).getIsRest().equals("0")) 
    || workTimeSpecials.size() == 0 && !isWorkDay) {
        return;
}


遇到这样的表达式，请使用Extract Local Variable提取为意义明确的变量。

** 代码缩进使用空格代替tab [FORMAT.DUT-3]**

描述：

代码缩进使用空格代替tab保证代码在非windows系统环境下的可读性

数组声明格式 [FORMAT.IAD-3]

描述：

数组声明[]放在type后面而不是变量后面

错误示例：

private String str1[]**, str2[]**, str3[]**;


正确示例：

private String []** str1, str2, str3;


**正确使用equals

错误示例：

str.equals("0");


正确示例：

"0".equals(str); // 规避str为null时的空指针异常


避免不必要的小括号 [FORMAT.UP-3]

描述：

避免不必要的小括号

错误示例：

i = (i + 2);


与文件同名的类应放在所有类声明的最前面 [FORMAT.FCN-4]

描述：

如果一个文件中定义了多个类，那么与文件同名的类作为主类应放在代码的最前面

声明中修饰符的使用应遵循正确顺序 [FORMAT.MO-4]

描述：

声明中修饰符的使用应遵循以下顺序：

> annotations
> 
> public/protected/private
> 
> abstract
> 
> static
> 
> final
> 
> transient
> 
> volatile
> 
> synchronized
> 
> native
> 
> strictfp


## Java代码开发规范

1、禁止程序中使用 Systemc.gc();


## 前端UE编码规范


## 基本原则

 1. 兼容性
    
    兼容多浏览器 （（尽量兼容）IE10以上、Firefox、Chrome、Safari、Edge、信创浏览器）
    
    但暂不考虑跨设备的兼容，只对iPad作一定的兼容性改进。

 2. 一致性
    
    UE交互保持一致性
    
    UI风格保持一致性
    
    代码风格保持一致性

 3. 易测性
    
    应用组件开发时必须考虑易测性，为自动化测试提供方便 。

 4. 适度先进性
    
    谨慎引入第三方前端库，引入时需要充分考虑性能、稳定性、可维护性和技能要求。


## 页面开发规范

代码结构

jsp文件放到各Project的WebContent/WEB-INF/jsp/apps/{module}下。

如

Example 3.1.

f1_collaboation/WebContent/WEB-INF/jsp/apps/collaboration/listPending.jsp。

命名

camel命名风格

页面结构

禁止在页面中

 1. 定义css样式。
 2. 在style属性中直接书写样式。
 3. 引入除本页面同名js之外的任何js文件。（Portal如需引入第三方js，需要评审）
 4. 使用@page import引入Java类。

HTML书写规范

 1. HTML 标签必须成对使用，base br col hr img input meta link除外。
 2. HTML里的注释：<%-- 被注释的内容 --%>。
 3. 所有的标签名必须小写。
 4. 所有的标签属性名必须小写。
 5. 所有的标签属性值都必须用双引号包起来。
 6. 书写 HTML 代码的时候代码缩进。
 7. 表现与结构完全分离，代码中不涉及任何的表现元素，如style、font、bgColor、border等。
 8. 尽可能减少 div 嵌套。
 9. 给图片加上alt标签。

规范的书写示例如下：

<html>
    <head>
    </head>
    <body>
        <div id="panel"  class="panel">
        </div>
    </body>
</html>


JSTL & EL

限制使用，只能使用循环、el、少用if。

原有的taglib逐步进行迁移

只允许使用JSTL core、JSTL fmt 和JSTL functions 的部分tag，不允许使用JSTL sql和JSTL XML。

允许使用的tag列表

 1. c:out
 2. c:url
 3. c:forEach & c:if
 4. fmt:message


## Javascript开发规范

文件

JavaScript 程序应独立保存在后缀名为 .js 的文件中。

原则上，JavaScript 代码不应该被包含在 HTML 文件中。在 HTML 中的JavaScript代码会明显增加文件大小，而且也不能对其进行缓存和压缩。

模块的公开js，放到common/js/apps/{module}下，名称为模块名称，如common/js/apps/collaboration/collaboration_pub.js；发布时将被合并到主js文件。

页面js放到WebContent/apps/{module}下，建立与jsp同名的js文件，如WebContent/apps/collaboration/listPending.js。

命名

命名总的原则为：骆驼、自然语言、英文

 1. 名称只能包含下面的字符：26个大小写字符 (A .. Z， a .. z), 数字(0 .. 9)，和 下划线 (_)。不允许使用中文或特殊字符。首字母下划线只能用于私有方法和全局变量。

 2. 变量名称必须为小写字母，请使用英文名词，如department ;。对象的属性或方法名采用小驼峰式(lower camel-case)，如”init”, “bindEvent”, “updatePosition”：

 3. 类的命名使用骆驼命名规则，例如：Account, EventHandler

 4. 常量必须在对象（类）或者枚举变量的前部声明。枚举变量的命名必须要有实际的意义，并且其成员 必须 使用骆驼命名规则或使用大写：

 5. 不允许使用单词简写 。私有变量名用下划线开头。如：”_current”, “_defaultConfig”

 6. 不能使用大写名称作为变量名。常量名全部大写，单词间用下划线分隔。如：”CSS_BTN_CLOSE”, “TXT_LOADING”

 7. 方法和函数名应该以动词开始如getName()，返回bool类型的函数应该以is开始，例如isEnable()；不必担心长度，因为后期发布时会压缩。
    
    除了构造方法可以使用大写，首字母必须小写。

行长度

避免每行超过 120 个字符。当一条语句一行写不下时，请考虑折行。

缩进

缩进的单位为四个空格，避免使用 Tab 键来缩进。

注释

使用jsdoc语法书写注释。例如：

/**
 * 取得指定key的国际化资源。
 * @param {String} key 资源的key。
 * @return {String} 国际化资源文本。
 */
CTP.prototype.getMessage = function(key){
    ...
}


代码风格

遵循C++风格，参照下面的示例：

/**
 * 取得指定key的国际化资源。
 * @param {String} key 资源的key。
 * @return {String} 国际化资源文本。
 */
CTP.prototype.getMessage = function( key ){
    try{
        var msg= eval( '' + key );
        if( msg && arguments.length > 1 ){
        for( var i = 0; i < arguments.length - 1; i++ ) {
                var regEx = eval('messageRegEx_' + i);
                var repMe = '' + arguments[i + 1];
                if( repMe.indexOf( '$_' ) !== -1 ){
                    repMe = repMe.replace('$_', '$$_');
                }
                msg = msg.replace( regEx, repMe );
            }
        }
        return msg;
    }
    catch(e){
    }
    return "";
}



## 缓存规范


## 前端缓存的类型

版本

避免升级后受缓存的旧版本文件影响。 使用：${ctp:resSuffix()} 例如：all-min.js?V=V5_6_2015-04-29 所有的js和css引用都需要加。

启动

每一次重启后缓存失效。比如启动时生成的静态化国际化文件和Ajax存根。 目前没有提供Taglib，可使用：<%=com.seeyon.ctp.common.SystemEnvironment.getServerStartTime()%> 例如：ajaxStub.js?v=1430293037148

登录

用户每一次登录后缓存失效，比如菜单、插件等个性化缓存。 使用：${ CurrentUser !=null ? CurrentUser.etagRandom : 0} 例如：main.do?method=headerjs&login=-2043353591

不缓存

动态请求，为避免浏览器缓存，url加随机数。 如：ajax.do?method=ajaxAction&managerName=sectionManager&rnd=1277

ETAG

HTTP的机制，一般使用时间戳作为ETAG的依据。 如果是转发文件，可以用文件的最后更新时间。 比如我们正文中的图片，Ajax的存根。可以使用WebUtil的checkEtag和writeEtag来实现。

有效期

response.setDateHeader("Expires", xxx);


## H5编码规范


## 基本原则

 1. 由于jquery在移动端的开发存在性能问题，页面不允许导入jquery库；
 2. 样式需进行兼容处理；
 3. UE交互保持一致性、UI风格保持一致性、代码风格保持一致性；
 4. 谨慎引入第三方前端库，引入时需要充分考虑性能、稳定性、可维护性和技能要求。


## 页面开发规范

 1.  页面使用UTF-8编码
 2.  页面首屏数据量大小在1M以内，多余的部分需要使用异步导入的方式；
 3.  禁止ajax同步请求；
 4.  尽可能减少 div 嵌套；
 5.  样式代码不能使用CSS表达式；
 6.  dom选择尽量使用ID选择；
 7.  所有的标签名必须小写；
 8.  所有的标签属性名必须小写；
 9.  z-index的最高使用层级为49；
 10. 不要随意的使用position定位；
 11. link标签写在head标签内；
 12. script标签写在body标签结尾处；
 13. 国际化资源以中文简体资源为首选资源；
 14. 业务逻辑入口需放在cmp.ready回调里；
 15. 页面采用自适应屏幕宽度设置。

Example

<meta name="viewport" content="width=device-width, initial-scale=1,maximum-scale=1,user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">



## 代码结构

 1. html文件放到html文件夹；
 2. css文件放到css文件夹；
 3. js文件放到js文件夹；
 4. 图片文件放到img文件夹；
 5. 国际化资源文件放到i18n文件夹。


## 命名

 * camel命名风格


## 项目结构规范

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



## VUE前端开发规范


## 统一开发工具

 * node.js: 只支持lts版本，当前脚手架只支持v12.22.12+ || v14.21.2+
 * 代码编辑器IDE: 统一使用vscode最新版本，尽量定期根据提示升级
 * vscode插件: 在vscode插件商店搜索vue-extpack并安装

为保持编译、构建环境一致；代码风格一致；编码规范执行，务必安装上述工具。 由于工具可能未完全某些场景，暂不做强制检查，后续目录中的规范将强制执行，否则无法提交代码。


## Code Review检查点

代码Review着重检查的点，同时也是如何写出更容易维护代码的参考




## 对外开放的API必须经过评审

对外提供的API（如表单/无流程列表/自定义控件等）必须经过评审，评估接口规范、必要性、兼容性、各平台统一，禁止私自添加开放接口


## 工程规范: webapps/static目录

 * *.html不能放在static目录，必须放在seeyon中对应应用目录中
 * static中只能放静态资源(js/css/fonts/image/json等)，不能放jsp/html
 * static已经明确定义1级子目录结构，不允许修改1级目录结构
 * 标准产品应用目录统一放在static/app/下，各应用内目录结构不做强制要求
 * 标准扩展及三方扩展统一放在static/extend/下，
 * 目录命名应当遵守通用命名规范(包括第三方)
 * 新工程申请/三方产品集成时必须填写构建产物目录通过审核

static目录定义如下:

static
  - base 基础模块(如基础组件库、加密模块、错误收集、页面通信等)
  - app 各应用自己的资源(示例如下，尽量将统一模块放入统一目录)
    - collaboration
    - cap4
    - cap3
    - meeting
    - ...
    - conferrence
  - extend 扩展目录(标准扩展及第三方)
    - ia
    - leximisc
    - ...
    - ocip
    - 其它
  - WEB-INF tomcat配置文件(不能修改)



## vue规范: 如何在Vue中正确使用JSX?

vue中使用JSX语法需要安装转换依赖@vue/babel-preset-jsx @vue/babel-helper-vue-jsx-merge-props

 * 新脚手架已经集成这些配置，可直接使用@devpack/qakit/config/babel
 * 历史工程确认是否安装了上述必须依赖

vue中使用JSX只支持一些特定的写法，否则可能出现h is not defined错误，或者需要手动传递h方法，推荐以下用法由babel插件自行注入`h``

## vue组件里render方法

export default {
  render() {
    // babel插件会自动生成如下代码
    // var h = this.$createElement;
    // return h('a-button');
    return <a-button>...</a-button>
  }
}


## vue组件methods里定义的方法

 * renderXxx不能命名为_render
 * _render为vue原型内部方法，可能引发异常

export default {
  methods: {
    renderXxx() {
      // babel插件会自动生成如下代码
      // var h = this.$createElement;
      // return h('a-button');
      return <a-button>...</a-button>
    }
  }
}


## VNode方式，必须显示指定形参h，常用于Fiber组件库

const renderBar = (h) => {
  // babel插件会自动生成如下代码
  // var h = arguments[0];
  // return h('a-button');
  return <a-button>...</a-button>
}


## 通过call/apply/bind改变this, 未完全理解babel转换原理及this指向慎用

 * 将renders定义在工具函数集中管理
 * 调用时需要清楚this指向

const renders = {
  renderFoo() {
    // babel插件会自动生成如下代码
    // var h = this.$createElement;
    // return h('a-button');
    return <a-button>...</a-button>
  },
  renderBar() {
    return <a-button>...</a-button> 
  }
}
// 调用方式1，挂载为当前实例方法
export default {
  methods: {
    ...renders
  }
}
// 调用方式2，通过call/apply/bind指定this，这种方法适合公用且独立维护的render实现
export default {
  render() {
    // 注意这里必须传递当前组件的this
    return renders.renderFoo.call(this, arg1, ..., argsN);
  }
}



## 开源软件引入和漏洞自查规范

开源软件需要注意协议和本身安全漏洞，在合规范围内使用。


## 开源协议

 1. BSD许可证： 介绍： BSD许可证是一种开放源代码许可证，鼓励代码共享。它允许用户在满足一些基本条件的前提下自由地使用、修改和分发软件。 特点： 宽松的许可证，允许在商业和闭源项目中使用、修改和分发代码，无需公开源代码。 商业使用限制： 基本上没有商业使用限制，非常灵活。 使用注意事项：无

扩展说明：Apache/BSD/MIT许可证都是相对宽松的开源协议： MIT许可证是一种宽松的开源软件许可证，允许在商业和私人项目中免费使用、修改和分发软件，只需在软件中包含原版权声明和许可证文本。

 2. Mozilla公共许可证（MPL）: 介绍： MPL是一种结合了GPL和MIT许可证特性的混合许可证。它允许在商业和私人项目中使用、修改和分发软件。 特点： 允许在商业项目中使用、修改和分发代码，但修改后的代码必须以MPL或类似的协议发布。 商业使用限制： 需要将修改后的代码以开源形式发布。 使用注意事项：使用时不做修改

 3. Eclipse公共许可证（EPL）: 介绍： EPL是为Eclipse开发的开源项目设计的许可证。它允许用户自由使用、修改和分发软件，同时要求修改后的代码必须以EPL或类似许可证开放源代码。 特点： 适用于Eclipse开源项目，允许在商业项目中使用、修改和分发代码。 商业使用限制： 商业产品需要将修改后的代码以开源形式发布。 使用注意事项：使用时不做修改

 4. GNU宽通用公共许可证（LGPL）: 介绍： LGPL是GNU通用公共许可证的一个变种，允许开发者将LGPL授权的代码与非自由软件一起使用。 特点： 允许将LGPL授权的代码链接到非自由软件中，但修改后的LGPL代码必须以LGPL或者GPL发布。 商业使用限制： 商业产品需要满足LGPL的要求，确保修改后的代码以开源形式发布。 使用注意事项：动态链接使用（比如：Hibernate，glibc）

 5. GNU通用公共许可证（GPL）: 介绍： GPL是最知名的开源软件许可证之一，要求任何使用、修改和分发GPL软件的人必须以相同的许可证将其修改后的版本公开发布。 特点： 强调整个产品的开源性，要求任何使用GPL组件的商业产品都必须以GPL发布。 商业使用限制： 商业产品需要将包含的GPL组件以GPL发布。 使用注意事项：进程隔离、独立于产品进程使用

 6. GNU通用公共许可证增补条款（AGPL）: 介绍： AGPL是GPL的一个扩展版本，适用于在网络上提供软件服务的情况。 特点： 要求使用、修改和分发AGPL软件的人必须以AGPL发布，包括商业产品。 商业使用限制： 商业产品需要满足AGPL的要求，包括以开源形式提供源代码。 使用注意事项：进程隔离、独立于产品进程使用（比如：Berkeley DB）

 7. 服务器端公共许可证（SSPL）: 介绍： SSPL是一种相对较新的开源许可证，专为云服务和大数据应用设计。 特点： 要求在使用SSPL软件的基础上构建的云服务必须将整个服务的源代码开放。 商业使用限制： 商业产品需要满足SSPL的要求，包括以开源形式提供整个服务的源代码。 使用注意事项：避免商用（比如：mongodb、redis） 所有开源软件在做版本选择时，尽量选择成熟稳定、较新的版本，不要选择有已知高危漏洞的开源组件版本。


## 漏洞自查

已知漏洞自查方式：通过搜索引擎搜索“组件名称 CVE”关键字，查看搜索结果是否有组件的官方披露漏洞网址，确认所选版本是否有漏洞披露。（实在无法判断，可将名称、版本号、开源jar包发给安全部门通过我们的自建系统进行查询）


## 安全编码规范

详细安全解决方案参考开放平台>快速开始>安全开发规范


## 典型安全漏洞

漏洞            备注                                                                                                                         措施
脚本注入（SQL注入）   攻击者利用                                                                                                                      杜绝静态SQL，使用PreparedStatement
              SQL注入漏洞，可以获取数据库中的多种信息（如管理员后台密码），从而脱取数据库中内容（脱库）。在特别情况下还可以修改数据库内容或者插入内容到数据库，如果数据库权限分配存在问题，或者数据库本身存在缺陷，那么攻击者可以通过SQL注入漏洞直接获取
              bshell 或者服务器系统权限。
XSS攻击         通过漏洞页面在浏览器上执行 js， 从而进行一系列的操作。常见的攻击方式主要是利用 XSS                                                                              前端传入的参数输出前要进行处理
              盗取用户身份，进一步获取权限，甚至利用高级攻击技巧直接攻击企业内网 。
任意文件上传        文件上传攻击被利用于上传可执行文件、脚本到服务器上，进而进一步导致服务器沦陷。                                                                                    不允许应用自己实现上传，统一使用系统组件，特殊需求需报备。
路径遍历          客户端指定上传文件名，攻击者利用相对路径将文件上传到上下文目录中。                                                                                          1、不允许前端传递文件名；2、前端传递的参数如果带文件名，需校验File是否在指定的目录下。
任意文件下载        任意文件读取漏洞能够读取服务器上任意的脚本代码、服务及系统的配置文件等敏感信息，造成企业代码与数据的泄漏，威胁主机安全。                                                               不允许前端指定要下载的文件位置
越权访问/敏感信息泄漏   获取其他用户的数据，修改其他用户的信息，乃至直接获取管理员权限从而可以对整个网站的数据进行操作。                                                                           角色控制
弱口令/暴力破解      获取员工权限，拿到网站管理或内部系统权限，对进一步渗透打下基础，甚至可能直接获取系统权限。                                                                              不使用弱口令


## 安全规范

 * 单点登录的ticket绝对不允许使用登录名，不允许使用永久有效的ticket，同一用户每次生成的ticket必须不一样
 * 不要给黑客留可以不登录就根据字典暴力破解密码的口。
 * 缺省不允许使用弱口令。
 * 不允许按前端传递的人员Id进行响应，必须根据当前登录用户筛选数据。
 * URL中不允许传递用户名或密码等敏感信息，必须放到Body里用POST方式提交。
 * 敏感信息不落地，密码仅用于验证环节，不允许在内存中缓存或为了方便在Cookie或Session中存储。不允许应用在数据库、文件中存储平台或系统其它应用的密码。
 * 关于敏感信息，存储一定要加密，传输尽可能保障安全，必须使用POST提交，敏感信息不允许出现在URL中，不要在日志中输出客户的信息。
 * 必须登录才允许上传文件。
 * 最终用户上传的文件不允许进入上下文目录，不允许上传jsp文件（上传的html文件要对script进行trim）。
 * 不要为了方便就开一个口可以下载任何一个文件。
 * 管理功能必须加角色控制注解，限定角色访问。
 * Servlet和不在WEB-INF中的jsp必须报备，无需登录即可访问的入口必须控制住不进行上传、反序列化等危险操作。


## 限制无需登录的请求（before V7.1SP1）

对于无需登录即可访问的url，比如登录，可以加@NeedlessCheckLogin注解

public class MainController{
    @NeedlessCheckLogin
    public ModelAndView login(HttpServletRequest request, HttpServletResponse response) throws Exception {

    }
}


注意，上面的注解仅在7.1SP1之前可用，7.1SP1以后将匿名请求控制收归平台统一管理，原则上不允许应用随意新增无需登录的请求。


## 文件越权控制：加V

我们的很多功能对链接做了权限控制，同一个URL，不同的登录用户也不能下载。以doc插件为例，在插件的配置文件（pluginProperties.xml）中增加security.digesturl

<?xml version="1.0" encoding="utf-8"?>
<ctpConfig>
    <doc>
        <security>
            <!-- 需要做URL digest的URL注册，空格分隔1为uri地址，2为method（没有可以省略），3为digest参数名 -->
            <digesturl>/doc.do rightNew resId,frType,docLibId,docLibType,isShareAndBorrowRoot,all,edit,add,readonly,browse,list,parentCommentEnabled,parentRecommendEnable,parentVersionEnabled,flag</digesturl>
            <digesturl>/doc.do docPropertyIframe resId,docResId,frType,docLibId,docLibType,isShareAndBorrowRoot,all,edit,add,create,readonly,browse,read,list,parentCommentEnabled,parentRecommendEnable</digesturl>
            <digesturl>/doc.do docProperty _resId,docResId,frType,docLibId,docLibType,isShareAndBorrowRoot,_all,_edit,_add,_create,_readonly,_browse,_read,_list,propEditValue,_parentCommentEnabled,isPerBorrow</digesturl>
            <digesturl>/doc.do knowledgeBrowse docResId,entranceType,openFrom,docVersionId</digesturl>
        </security>
    </doc>
</ctpConfig>


处理后的链接会多出一个v参数，只有当前登录用户才能够正常访问。


## 统一权限控制

7.1SP1以后对所有的Servlet、Spring controller、Ajax、jsp、Rest、SOAP请求做了统一的权限控制。应用自行添加的JSP文件，不会被解释执行。在运行期内修改已存在的JSP文件，也会被判别为非法篡改，禁止执行。


## 数据库规范


## 数据结构设计规范

基本原则

 * 遵循第三范式，适度冗余提升性能，并保证数据的一致性。
 * 符合命名规范（ 注意关键字 、长度限制）。
 * 使用正确的数据类型、合适的长度。
 * 新建的表对于频繁查询的字段需要建立索引。

命名规范

 * 表的命名：模块（缩写）+表含义，例：平台模块的表前缀为ctp_，协同模块的表前缀为col_，表单模块的表前缀为cap_。
 * 表名与字段名使用下划线区分单词，以增加可读性。在HBM文件与POJO中则去除下划线， 第一个单词的首字母小写，其后单词的首字母大写。
 * 表中相同概念的字段，应该使用相同的名字、相同的类型、相同的值域，HBM映射文件与POJO类尽量保持一致的命名。例：”创建时间“在数据库中字段名为create_time，类型为datetime；在HBM映射文件与POJO类中属性名为createTime，类型为java.util.Date。
 * 索引命名：唯一，IDX_表缩写_索引字段缩写
 * 表主键：id在数据库中为bigint类型，在POJO中为long类型，通过UUID算法生成。
 * 表外键：被引用表缩写_id。
 * 注意关键字
 * 长度限制（表名、字段名、索引名长度统一不能超过25，预留PK_前缀等）

控制单表字段长度

单表所有VARCHAR类型的字段长度加起来，乘以4，不能超过65535。此问题对MySQL、SQLServer有影响，Oracle不受此影响。

优化策略：以MySQL为例，尽量少用VARCHAR大字段，比如VARCHAR(1000)、VARCHAR(2000)，改为LONGTEXT。

常用数据类型

下表中是我们经常用到的一些字段的类型与值域，请大家在设计数据库之前先查询一下这张表看看类似的字段是如何定义类型与值域的。

MYSQL      ORACLE      SQLSERVER   POSTGRESQL     DM             KINGBASE       OSCAR          GBASE          HBM文件       POJO类型              场景
BIGINT     INTEGER     BIGINT      INT8           BIGINT         INT8           BIGINT         BIGINT         long        java.lang.Long      主键
DATE       DATE        DATETIME    TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   timestamp   java.util.Date      日期
DATETIME   DATE        DATETIME    TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   timestamp   java.util.Date      日期时间
DECIMAL    NUMBER      NUMERIC     NUMERIC        NUMBER         NUMERIC        NUMBER         NUMBER         double      java.lang.Double    小数
INT        INTEGER     INT         INT4           INT            INT4           INTEGER        INT            integer     java.lang.Integer   整数
LONGBLOB   BLOB        IMAGE       BYTEA          BLOB           BYTEA          BLOB           BLOB           string      java.lang.String    二进制对象
LONGTEXT   CLOB        NTEXT       TEXT           CLOB           TEXT           CLOB           CLOB           string      java.lang.String    大文本
SMALLINT   NUMBER(4)   SMALLINT    INT2           SMALLINT       INT2           SMALLINT       SMALLINT       integer     java.lang.Integer   数字枚举
VARCHAR    VARCHAR2    NVARCHAR    VARCHAR        VARCHAR        VARCHAR        VARCHAR        VARCHAR        string      java.lang.String    文本

常用字段定义规范

字段名                中文名     类型（MYSQL）       描述
Id                 主键id    bigint(20)      
subject            标题      varchar(255)    长度统一定义为255，js前段校验为80
content            正文      longtext        大文本
description        描述      varchar(2000)   长度统一定义为2000，js前段校验为500
create_member_id   创建人id   bigint(20)      人员表id
update_member_id   修改人id   bigint(20)      人员表id
create_time        创建时间    datetime        yyyy-MM-dd HH:mm:ss
update_time        修改时间    datetime        yyyy-MM-dd HH:mm:ss

禁止

 * 禁止三表以上联查，容易导致性能问题。
 * 数据存储不要使用XML，避免序列化和反序列化性能问题。如果必须存储复合数据，建议使用JSON。
 * 数据类型不要使用BLOB，非结构化数据请使用文件存储。
 * 禁止循环SQL操作
 * 禁止大字段查询
 * 禁止不分页查询


## 数据结构变更规范

**修改字段类型：**原则上不允许修改，除非必须修改且数据库允许修改且已产生数据不影响的前提下，建议增加新字段兼容

**修改字段长度：**允许修改，原则只能加长，不可缩短

**修改字段名称：**建议不修改，一般用于支持新数据库时因为使用了关键字必须修改

**调整索引：**根据查询条件，优化索引，提升查询效率，注意索引长度限制


## 代码版本管理


## 代码提交规范

原则：只提交代码文件和产品所需的资源文件，其余文件一律不允许提交！


## 禁止提交的文件

 1. 禁止提交以.开始的任何文件和目录 如：
    
    * IDE生成的目录 .idea目录 .eclipse目录
    
    * 版本管理系统本地配置信息 .svn目录 .git目录
    
    * 项目管理工具（maven、gradle）的临时目录 .gradle目录 .mvn目录
    
    * eclipse配置信息 .classpath文件 .project文件 .settings文件

 2. 禁止提交和本地工程信息相关的任何文件 如：
    
    * 项目配置信息文件 project.iml文件 project.proj文件

 3. 编译产生的文件 如：
    
    * java编译产生的目录 build目录 target目录 out目录

 4. 打包工具产生的依赖目录 如：
    
    * nodejs的依赖目录 node_modules目录

 5. 动态生成的文件 如：
    
    * webpack构建生成的静态文件 static/js/app.39c23dbe587ebf1cebed.js

 6. DEMO文件、文档 如：
    
    * 开源工具使用到的示例（请上传到项目文档SVN） DEMO目录 README文件

 7. 其他所有非工程构建、编译、测试所需要的文件


## 提交信息

 1. 每次提交必须填写大于8个字符的提交信息
 2. 提交信息内容必须能表明本次提交的内容，禁止无意义的提交信息。

编撰人：admin、het、lichaoj


快速跳转



 * 开发规范
   * Java编码规范
     * 命名规范
     * 注释规范
     * 格式规范
     * Java代码开发规范
   * 前端UE编码规范
     * 基本原则
     * 页面开发规范
     * Javascript开发规范
   * 缓存规范
     * 前端缓存的类型
   * H5编码规范
     * 基本原则
     * 页面开发规范
     * 代码结构
     * 命名
     * 项目结构规范
   * VUE前端开发规范
     * 统一开发工具
     * Code Review检查点
     * 对外开放的API必须经过评审
     * 工程规范: webapps/static目录
     * vue规范: 如何在Vue中正确使用JSX?
       * vue组件里render方法
       * vue组件methods里定义的方法
       * VNode方式，必须显示指定形参h，常用于Fiber组件库
       * 通过call/apply/bind改变this, 未完全理解babel转换原理及this指向慎用
   * 开源软件引入和漏洞自查规范
     * 开源协议
     * 漏洞自查
   * 安全编码规范
     * 典型安全漏洞
     * 安全规范
     * 限制无需登录的请求（before V7.1SP1）
     * 文件越权控制：加V
     * 统一权限控制
   * 数据库规范
     * 数据结构设计规范
     * 数据结构变更规范
   * 代码版本管理
     * 代码提交规范
     * 禁止提交的文件
     * 提交信息



分享链接分享链接

## 12. PC查找前端JSP位置方法

> 原始路径：`/38/63/1128.html`  
> 相对路径：`38/63/1128.md`

## PC查找前端JSP位置方法


## 适合人群

技术开发


## 场景

在没有源码的前提下，我能看到前端某个页面，如果此页面是JSP，我想知道此页面的具体JSP位置。


## 解决方案

如下示例，已知红框区域是一个独立JSP，我想知道这个JSP的具体位置。



1）鼠标停留在红框区域任何位置，然后鼠标右键选择“查看框架源代码”：



2）此时在浏览器新页签能显示一个以“view-source:”开头的链接，拷贝完整链接，然后去掉“view-source:”，保留后面的完整URL，并且在URL最后追加一段参数“&ctp_dump_modelAndView=true”

view-source:http://ip/seeyon/taskmanage/taskinfo.do?method=taskList&pageType=task&listType=Personal

去掉view-source:保留后面的完整URL，并且追加一段参数“&ctp_dump_modelAndView=true”
http://ip/seeyon/taskmanage/taskinfo.do?method=taskList&pageType=task&listType=Personal&ctp_dump_modelAndView=true


3）浏览器新页签打开F12调试窗口，浏览器中输入上一步的地址。

通过F12调试窗口找到当前.do请求，在Response响应头中，能看到“ModelAndView.name”属性，其值apps/taskmanage/tasklist/taskList就是完整的JSP页面路径。

> apps上一层目录是seeyon/WEB-INF/。



编撰人：het




快速跳转



 * PC查找前端JSP位置方法
   * 适合人群
   * 场景
   * 解决方案



分享链接分享链接

## 13. 快速查找前端源码位置

> 原始路径：`/38/63/1129.html`  
> 相对路径：`38/63/1129.md`

## 快速查找前端源码位置


## 适合人群

技术开发


## 场景

在有源码的前提下，我想查找某个页面某个按钮/文字元素的代码位置。

注：如果你使用了ctp-studio，则可以根据关键字快速搜索到源码。


## 解决方案

通过浏览器开发者模式查找关键字来溯源，PC和移动端Html5均可以采用此方案搜索定位源码。

在上一步案例基础上扩展：用户希望我将新建协同页面-更多设置按钮改个图标，此时我需要以最快速度找到“更多设置”定义在页面什么位置（找到源代码位置）。



还是推荐使用Chrome、新Edge等高版本浏览器，鼠标移动到“更多设置”这个链接上，然后鼠标右键->选择最底部的“检查”按钮。



通过“检查”按钮，我们能够看到浏览器解析到了“更多设置”这个页面的HTML DOM元素代码。此时，开发人员要“根据经验”去找关键字，找与更多设置相关的一些关键字，找到他们，然后在开发者工具中搜索他们的位置。

如下图所示，id="show_more"和这两段代码都是比较唯一的关键字，开发可以根据这两者其一搜索代码位置。



最后，我们依然使用Eclipse做演示，输入关键字搜索*.jsp页面，最后定位源代码如下↓



> 小结：通过浏览器的“查看源代码”和“检查”特性能很快找到页面指定的元素位置，这是开发人员必备技能！

编撰人：het


快速跳转



 * 快速查找前端源码位置
   * 适合人群
   * 场景
   * 解决方案



分享链接分享链接

## 14. 通过页面追溯Controller和JSP

> 原始路径：`/38/63/1130.html`  
> 相对路径：`38/63/1130.md`

## 通过页面追溯Controller和JSP


## 适合人群

技术开发


## 场景

当前页面是一个.do请求，这个是标准的springmvc代码，我想知道这个页面对应的controller和jsp在哪里。

以下图为例，我想知道新建协同-更多设置页面的后端源码位置，可以按照下面的操作分析。




## 解决方案

1）使用Chrome、新Edge浏览器打开更多设置页面，图片红框中任何区域>鼠标右键>选择“查看源代码”。



2）通过选择“查看页面源代码”，我们能够在浏览器顶部窗口看到请求的URL，重点关注：collaboration/collaboration.do?method=newColl这个URL：



注意“xxx.do?method=yy”是一个典型的Spring MVC URL请求，这个URL对应Java后台的一个Controller的方法。下一步是要使用开发工具全局搜索这个Controller类在哪儿。

以Eclipse为例，首先搜索关键字“collaboration/collaboration.do”，匹配“*.xml”格式的文件类型，目的是找到这个.do请求是注册在哪个spring.xml中。

> 注：前提是开发人员需要有相关模块的源代码，或者你可以精准搜索本地安装的OA服务器目录：ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome下面的文件



如果你有相关模块源代码的话，最后能找到如下spring-*.xml格式的配置文件，看到这个请求注册的Controller类路径为：com.seeyon.apps.collaboration.controller.CollaborationController。



下一步是找到CollaborationController.java这个java类，并根据“method=newColl”找到newColl方法。

下一步我们要关注的是CollaborationController.java类的newColl方法最终路由到哪个JSP页面：你可以通过代码ModelAndView中配置的信息找到最终JSP（这是Spring MVC常识），如下代码可以看到请求被重定向到了**/seeyon/WEB-INF/jsp/apps/collaboration/newCollaboration.jsp**页面，注意标粗体+下划线的路径是Spring MVC默认规则。



最后根据ModelAndView信息，找到JSP源码位置如下：



同样，使用IntelliJ IDEA开发工具Ctrl+Shift+F也能很快搜索到对应代码，这里就不演示了。

编撰人：het




快速跳转



 * 通过页面追溯Controller和JSP
   * 适合人群
   * 场景
   * 解决方案



分享链接分享链接

## 15. 通过页面抓取后端请求

> 原始路径：`/38/63/1131.html`  
> 相对路径：`38/63/1131.md`

## 通过页面抓取后端请求


## 适合人群

技术开发


## 场景

我想知道某个前端页面的数据是通过几个后端请求返回回来的，想了解前端发送请求传了哪些参数？

V5产品的后端请求主要有.do类型的Controller请求、Ajax请求、Rest请求，Controller请求在本文同级目录有分析方法，本文只介绍Ajax请求和Rest请求。


## 一、Ajax请求解决方案

PC浏览器和移动H5页面均可使用此方案分析排查。

以下图任务详情为例：我想要知道任务标题、描述、时间、回复等数据是通过什么请求返回给页面的。



第一步：浏览器F12开启调试模式，切换到网络NetWork页签，同时先清理干净此前产生的网络请求：



第二步：重新打开一下任务详情卡片，此时会重新加载一遍任务数据，F12调试模式网络NetWork就能抓取到所有请求信息。

可以看到网络NetWork页签下面的请求信息刷新了，这就是本次打开产生的所有向服务器发送的请求：




## 第三步：分析Ajax请求

点击第一个ajax.do，这个是典型的V5 Ajax请求，选择负载Payload页签：

managerName对应后端服务器Ajax对象实例，managerMethod对应对象实例中的方法，arguments表示传递了什么参数：



继续保持在第一个ajax.do，切换到响应Response页签，这里表示从服务器向前端返回了什么数据信息：



问题：我已经知道这个Ajax请求了，那么如何找到后端源码呢？

通过负载Payload页签如下两个页签就能找到源码：

managerName: taskAjaxManager
managerMethod: validateViewTaskInfo


首先全局搜索*.xml文件中包含taskAjaxManager关键字的文件，如下可以发现源码就是com.seeyon.apps.taskmanage.manager.TaskAjaxManagerImpl.java



然后找到TaskAjaxManagerImpl.java源码，再搜索managerMethod中的“validateViewTaskInfo”方法，此方法就是对应Ajax源码：



> 扩展阅读：Ajax后端代码开发实现，参考本站>开发文档>CTP技术平台>AJAX组件


## 第四步：分析别的AJAX请求

点击第二个ajax.do，通过负载和响应就能初步清楚这个Ajax是获取任务核心数据的：



点击三个ajax.do，通过负载和响应就能初步清楚这个Ajax是获取任务回复数据的：




## 二、Rest请求解决方案

一般移动端H5页面都使用Rest请求来获取服务器数据，我们可以通过浏览器模式H5的页面效果。

> 移动端H5详细的调试文档可参考学习： https://open.seeyoncloud.com/cmpdev/

如下图所示：查看我的-已超期的列表数据，我们期望分析这个数据来自哪个Rest后端请求。



第一步：浏览器F12开启调试模式，切换到网络NetWork页签，同时先清理干净此前产生的网络请求，操作与前面Ajax示例一模一样。

第二步：点击页面上的已超期按钮，此时会重新加载一遍数据，F12调试模式网络NetWork就能抓取到所有请求信息。




## 第三步：分析Rest请求

调试模式下，在网络NetWork里面能看到两个请求，点击任意一个请求，通过“标头”页签能看到当前请求的URL是：/seeyon/rest/tasks/



通过“负载”页签，能看到请求传递的参数：



问题：我已经知道这个Rest请求了，那么如何找到后端源码呢？

这里的关键就是“标头”页签里面的请求URL：/seeyon/rest/tasks/，我们取rest后面的内容，全局搜索*Resource.java，来确认代码位置，如下图就知道TasksResource.java是源码文件：



> 为什么搜索*Resource.java就能知道是Rest后台文件：因为这是V5产品约定好的规范，详细Rest接口可参考本站>Seeyon API>Rest接口相关文档

以下是获取列表的具体的方法：




## 第四步：分析别的Rest请求

参考第三步操作，我们分析另一个请求的URL是seeyon/rest/tasks/count，代码位置同样位于TasksResource.java，而具体方法则是找Path注解=count的方法：



同样，通过负载能看到Rest请求参数，通过预览或响应能看到返回的结果：




## 三、其它情况

其它情况：如果调试窗口设置为XHR未找到任何请求，则可能不是AJAX、Rest，此时可以切换为ALL（全部）检查下是否是.do之类的请求。



编撰人：het


快速跳转



 * 通过页面抓取后端请求
   * 适合人群
   * 场景
   * 一、Ajax请求解决方案
     * 第三步：分析Ajax请求
     * 第四步：分析别的AJAX请求
   * 二、Rest请求解决方案
     * 第三步：分析Rest请求
     * 第四步：分析别的Rest请求
   * 三、其它情况



分享链接分享链接

## 16. 致信端如何找到代码位置

> 原始路径：`/38/63/1132.html`  
> 相对路径：`38/63/1132.md`

## 致信端如何找到代码位置


## 适合人群

技术开发


## 场景

致信客户端出现BUG，或需要针对某个页面做小的改动，我们需要客户端代码文件位置。


## 解决方案

致信客户端实际也是一个内置浏览器，故可以通过浏览器开发者模式调试问题。

按示例举例，比如我想调试致信客户端里面“快速会议”的功能，想知道代码位置：



操作方法：致信客户端打开“快速会议”页面，然后通过键盘按组合键：ctrl+alt+shift+i，就能打开致信的开发者模式窗口：



开发者模式窗口有很多功能，有前端技术经验的就可以继续分析了，比如：

1、通过查看html元素信息，找到关键字，再从致信源码中找对应文件 2、或者通过Console、NetWork分析相关问题 3、通过Sources源码分析源码文件

编撰人：het




快速跳转



 * 致信端如何找到代码位置
   * 适合人群
   * 场景
   * 解决方案



分享链接分享链接

## 17. 页面某个地方操作无反应问题排查

> 原始路径：`/38/63/1212.html`  
> 相对路径：`38/63/1212.md`

## 页面某个地方操作无反应问题排查


## 场景

用户发现某个页面的某个按钮操作无反应，应该如何分析问题原因？


## 案例操作

如下图所示，点击修改按钮无反应：



但凡出现页面“点击无反应”、“一直处于加载中”、“点击报错”，都先通过浏览器F12开发者工具检查前端异常。

使用Chrome、新Edege等浏览器回显问题，快捷键F12打开调试窗口，查看Console（控制台）页签是否有异常：

可以看到通过控制台能看到有Javascript异常堆栈，此时可以点击“templateManagementCenter.js:468” 看到具体报错点（源代码位置）。



最后定位报错点如下图所示，看起来是创建的ajax对象没有找到指定方法，后续就是分析原因（由于分析此问题需要掌握V5 Ajax知识，故此章节不赘述）。



注：如果第一次点击链接无法打开详细代码页面，你可能需要考虑在打开F12窗口的前提下，刷新下当前浏览器页面，这种问题一般出现在JSP中，JSP需要在开发调试窗口打开状态下重新加载。

如果你排查发现浏览器Console控制台没有报错，则需要通过F12调试工具抓取当前请求状态，看此请求访问后端是不是出现挂起问题，后端挂起就需要抓取ThreadDump检查服务器请求。

编撰人：het




快速跳转



 * 页面某个地方操作无反应问题排查
   * 场景
   * 案例操作



分享链接分享链接

## 18. 遇到窗口关闭，难以调试怎么办

> 原始路径：`/38/63/1213.html`  
> 相对路径：`38/63/1213.md`

## 遇到窗口关闭，难以调试怎么办


## 问题

我们有些弹出窗口点击提交按钮之后会自动关闭，随之而来的F12调试窗口也会被关闭掉，这个问题可以通过F12设置阻止关闭来解决。


## 解决方案

如下图所示，点击提交按钮，页面就关闭了。



同样打开F12调试窗口，切换到“源码”页签，在右侧事件监听器中，对窗口的windows.close打上勾，意思就是触发这个动作时会进入断点。



随后进行提交操作时窗口就不会关闭，反而会进入断点。



PS：F12源代码页签中提供了非常多的事件监听断点，比如onload等，大家可以根据不同场景加上断点进行调试。

编撰人：het




快速跳转



 * 遇到窗口关闭，难以调试怎么办
   * 问题
   * 解决方案



分享链接分享链接

## 19. Log日志分析经验

> 原始路径：`/38/63/1214.html`  
> 相对路径：`38/63/1214.md`

## Log日志分析经验

健全的日志信息建立在开发良好的日志编写习惯上，关于开发编写Log日志注意事项详见本站“CTP技术平台>LOG日志”篇。


## 1、日志结构

以默认安装的（基于Tomcat中间件）的本地OA服务为例，OA的日志存放于如下两个路径下：ApacheJetspeed\logs和ApacheJetspeed\logs_sy




## 2、运维如何快速提取日志

使用S1工具，找到发生异常的日期，对日志进行打包处理，操作方式详见S1用户操作手册：




## 3、技术人员如何获取正确的日志

如果异常刚刚才发生，则直接按照修改日期降序排列，找到最新日志取分析。



如果异常是此前一段时间的，则需要根据日志文件的“修改日期”找跟那段时间接近的日志。


## 2.1、logs目录

ApacheJetspeed\logs目录下的日志是Tomcat中间件日志，主要存放系统启动日志和JSP/Servlet运行时异常。

这个目录下有两个非常关键的日志：catalina.log和localhost.log，这两个日志默认都按照日期自增存放。

## 2.1.1、logs目录catalina日志

catalina-年-月-日.log存放系统启动日志，如果系统启动报错，优先看这个日志的文件信息。启动之初，会有整个Tomcat、JDK、JVM、系统环境变量的配置信息，可以快速通过日志分析当前系统环境情况。



> 如果更换为weblogic、was、金蝶、东方通等中间件，则需要按各自中间件特性取对应的日志文件（建议参考安装部署手册提取）

## 2.1.2、logs目录localhost日志

localhost日志存放的是Servlet、JSP级别异常，我们常见的页面红字异常都是存放在此处。


## 2.2、logs_sy目录

logs_sy目录下的日志非常丰富，都是V5的代码日志，功能及异常和日志追踪均通过logs_sy目录记录存储。

## 2.2.1、logs_sy日志存储规则

logs_sy下日志分为“当前运行时日志”和“历史记录日志”。

“当前运行时日志”就是存放于logs_sy根目录下，全部是.log文件，这些日志记录着当前正在运行的状态，按照修改日期降序排列，能看到最近什么日志文件有更新。



“历史记录日志”是通过文件夹存放，一天一个文件夹，按照日期存放。“当前运行时”的日志存储超过10M，就会被放入“历史记录日志”中。比如ctp.log存储满10M时，会被命名为ctp.log.2021-08-18.1.log放入2021-08-18文件夹（跟随当天日期存放）。



V8.2开始：如果重复的异常日志，会存储到error.log中，所以还需要取error.log文件。


## 4、根据关键字搜索日志的方法

场景：若客户上报了一个BUG：页面出现红字异常。没有提供报错的具体时分秒，只是知道是在某一天。

此时可以有多种方式追踪问题：

第一种，让客户重新试一下看是否报错，如果报错就取立刻报错时间点的日志分析。

第二种，由客户提供报错当天的全部日志，通常除了CAP、组织机构外，常规的错误日志都在ctp.log下，可以提取ctp.log下所有日志。



首先，确保自己已经安装了Notepad++软件，然后全选Log日志，鼠标右键>Edit with Notepad++



随后，在打开的Notepad++页面，输入红字异常关键字>选择查找所有打开文件>最后就能匹配到所有相关关键字。




## 5、日志级别动态调整

登录系统管理员账号，系统维护-系统调试设置-运行态改变日志级别



客户环境调试完成后记得重置默认日志级别，避免产生日志过多


## 6、系统LOG日志配置修改

OA系统全部LOG日志配置存储于\webapps\seeyon\WEB-INF\cfgHome\base目录下。主要修改log4j2_sys_running.xml和log4j2_sys_starting.xml两个文件的LOG配置，starting表示启动时打印的日志，running表示系统运行期打印的日志。

比如com.seeyon.ctp.event的日志级别默认是info，现在想修改为warn，则找到该日志配置，将level="info"改成level="warn"即可。

		<!-- 事件通知日志-->
		<AsyncLogger level="warn" additivity="false" name="com.seeyon.ctp.event">
			<AppenderRef ref="event"/>
			<AppenderRef ref="error"/>
		</AsyncLogger>




编撰人：het




快速跳转



 * Log日志分析经验
   * 1、日志结构
   * 2、运维如何快速提取日志
   * 3、技术人员如何获取正确的日志
     * 2.1、logs目录
       * 2.1.1、logs目录catalina日志
       * 2.1.2、logs目录localhost日志
     * 2.2、logs_sy目录
       * 2.2.1、logs_sy日志存储规则
   * 4、根据关键字搜索日志的方法
   * 5、日志级别动态调整
   * 6、系统LOG日志配置修改



分享链接分享链接

## 20. 某个操作很慢，问题排查方法

> 原始路径：`/38/63/1215.html`  
> 相对路径：`38/63/1215.md`

## 某个操作很慢，问题排查方法


## 适用场景

在如下场景下，都是某个操作很慢的情况，可以按照本文方式做排查：

 * 某一个功能很慢：比如提交处理协同要10秒，又或者打开会议已开列表页面要8秒，又或者翻页要等待10秒
 * 某一个功能操作后无反应，比如申请会议室页面，点击确定按钮后一直停在那不成功，可能要几十秒才反应过来

基于以上场景，可以说明当前系统某一个请求出现了问题，可能是数据库，可能是BLOCK锁，此时最好的解决方法是进行线程dump，分析当前时间区间对应请求到底在干什么。


## 技能要求

下面操作涉及一定的技术基础，需要有一定技术的运维或Java开发人员操作和分析。Java Thread dump分析是Java开发人员必备技能。


## 工作要求

如项目上遇到了缓慢问题，必须按照此文档，由对应技能要求的人员重现问题，抓取多份Thread Dump，先自行分析原因，如未分析出结果再提取这几份Thread Dump由专业的技术分析。


## 分析方法

V5系统内置了线程dump的工具，并且使用体验上做了极大优化，开发人员能够最快速度分析问题源头。如果出现某个功能响应慢，优先用V5系统内部的线程dump进行分析！


## 案例一：分析请求缓慢问题

问题示例：V5功能-国际化资源导出时很慢，需要1分多钟



1）通过系统管理员帐号登录，访问系统监控，点击thread dump就能拉出当前时间Jvm中运行的所有线程堆栈。



2）找到出性能问题的功能点，重新重现下性能问题。比如上面国际化资源模块，点击导出，通过浏览器F12工具会发现导出操作一直在Pending等待结果。

3）上面性能问题出现了，说明后台线程一直在运行再回到步骤1），系统监控页面点击页面下方的“Thread Dump”，弹出新页面，可以显示当前时刻的线程堆栈。



4）点击一次Thread Dump不够，最好是每隔几秒去点击一次，点击多次去找共同点，比如下图就是导出了7次，可以看到从第4次开始，一直都卡在doSheetContent这个方法，代码位置在Line 354行。



5）从线程堆栈可以看出，在执行20多秒之后，当前线程都在doSheetContent Line 354行这个代码位置：



6）随后查看源代码，可以看到Line354指向一个dataRecord.getRow()方法，再往下探getRow方法有toArray操作，而且是放在for循环内，类似于SQL循环了，肯定有性能问题。修复方法就是把dataRecord.getRow()放在for循环外层，执行一次即可。





案例总结：先登录system下的系统监控页面，随后复现性能慢的点，通过系统监控的thread dump每隔几秒跟踪下当前执行线程，定位执行慢的代码。这就是性能问题的固定分析套路。


## 案例二：某个操作卡住无反应问题

问题示例：用户新建会议时，如果选择了“会议地点”，点击发送后一直卡在“正在发送”界面，并且关闭浏览器会议新建不成功。



问题分析：只有发送会议这一个操作会出现此问题，则说明是保存会议这个动作出现了事故，解决方案依然是通过系统管理员的thread dump分析当前保存会议的线程在干什么。

操作方式见“案例一：分析请求缓慢问题”中的模式：

 * 首先复现问题并且保持现场，在出问题的环境重新操作一遍复现问题，保障发送会议一直处于“正在发送”阶段
 * 然后换个浏览器用系统管理员帐号登录系统后台，找到“系统监控”，访问系统监控下面的thread dump，可以每隔几秒钟打开一个thread dump
 * 分析thread dump内容，找到问题原因







总结以上分析结果：

1.有大量BLOCKED请求，都是MeetingRoomManagerImpl.applyRooms上面，说明会议保存请求存在死锁

2.通过thread dump全局搜索发现锁的源头都是owned by H-108，此时就要分析H-108为何没执行完

3.通过分析发现H-108Running了2天都没结束，再分析线程堆栈可以看到问题出在数据库查询，大概率是查询该条数据时出现死锁导致

解决动作：

如果要临时紧急处理，则重启OA服务即可解决。

如果要深挖问题根本原因，则要分析H-108那个数据库查询为何会死锁，这个要DBA连上数据库，结合锁检查SQL寻找问题源头---说不定H-108也不是问题根本，它只是受害者。

如果要保障代码健壮性，还应该检查MeetingRoomManagerImpl.applyRooms源代码，分析是不是代码中的锁粒度太大？是否可以缩小锁的范围，不要挂起那么多线程。

编撰人：het




快速跳转



 * 某个操作很慢，问题排查方法
   * 适用场景
   * 技能要求
   * 工作要求
   * 分析方法
     * 案例一：分析请求缓慢问题
     * 案例二：某个操作卡住无反应问题



分享链接分享链接

## 21. 使用Jvm分析工具

> 原始路径：`/38/63/1216.html`  
> 相对路径：`38/63/1216.md`

## 使用Jvm分析工具

如下场景下，需要对系统进行堆内存dump分析：

 * 系统使用过程中突然出现大面积瘫痪无法使用

如果系统出现大面积瘫痪，可能是内存溢出导致，此时就需要进行堆dump，然后使用MAT工具分析问题堆。


## windows导出线程、堆

上面的场景前提是有系统管理员帐号并且能成功登录查看到线程Thread Dump。如果没有帐号的话，还可以使用jdk自带的一些工具来查看、分析导出线程堆栈。

1）进入协同安装目录jdk\bin，双击启动jvisualvm.exe



2）选择要查看的java进程。

选择左侧的一个java进程，点击查看，在右侧可看到java进程在哪个目录下，由此可判断所选择的java进程对应什么服务。



3）导出线程dump。

在左侧列表中找到对应的java进程，点击右侧”线程dump”按钮，即可导出线程dump。若要导出协同dump，请在左侧选择对应的tomcat；若要导出office转换服务dump，请在左侧选择com.seeyon.v3x.rmi.server.Server。



4）保存线程dump文件。



5）保存堆dump。

点击”堆Dump”按钮后，左侧列表中可以看到生成了heapdump节点，选中生成的heapdump节点，右击选择另存为。

----------------------------------------


## Linux导出线程、堆


## jstack导出线程堆栈

用法： jdk的bin目录路径下执行：

jstack -l 2073 >./example.dump


2073代表进程id（查java进程 ps -ef | grep java）

./example.dump代表将线程堆栈导出到哪个路径中的哪个文件中，文件名可以自定义。


## jmap导出内存

用法： jdk的bin目录路径下执行：

jmap -dump:format=b,file=./example.hprof 2073


2073代表进程id（查java进程 ps -ef | grep java）

example.hprof代表将内存堆导出到哪个路径中的哪个文件中，文件名可以自定义。

分析hprof内存堆文件：使用mat工具，前提是分析内存的电脑内存要足够大，否则无法解析hprof

编撰人：het


快速跳转



 * 使用Jvm分析工具
   * windows导出线程、堆
   * Linux导出线程、堆
     * jstack导出线程堆栈
     * jmap导出内存



分享链接分享链接

## 22. 手动抓取ThreadDump

> 原始路径：`/38/63/2259.html`  
> 相对路径：`38/63/2259.md`

## 手动抓取ThreadDump

> ThreadDump主要用于分析后端功能慢的原因

 * 使用2个浏览器（或者无痕模式），一个登录系统管理员账号，另一个用来登录后复现问题

注意： 如果OA是集群部署，那么复现问题账号和系统管理员账号必须保证是登录到同一个后端OA节点

 * 系统管理员账号，切换至后台-系统维护-系统监控，点击底部 threadDump，打开3~5个标签页







 * 另一个浏览器登录复现问题账号，进入到问题复现页面(建议可以打开F12)，点击功能复现问题

 * 在问题复现期间（页面转圈、加载过程），慢请求还未返回响应之前；立刻到另一个浏览器，依次刷新之前打开的几个threadDump标签页（注意必须是在请求结束之前完成刷新）

 * 将加载过程刷新的threadDump页面，按刷新顺序标序并保存为文本文件，同时还可以把复现问题的浏览器中F12抓到的慢请求url一并记录保存

编撰人：wangyxyf


快速跳转



 * 手动抓取ThreadDump



分享链接分享链接

## 23. OA系统监控详解

> 原始路径：`/38/63/2263.html`  
> 相对路径：`38/63/2263.md`

## OA系统监控详解

> 位置：登录OA系统管理员后台-系统维护-系统监控


## JVM介绍



版本

JVM Version: OpenJDK 64-Bit Server VM (1.8.0_372, 25.372-b07, mixed mode)



在 Java 虚拟机（JVM）中，内存分为堆（Heap）和非堆（Non-Heap）两大部分


## 堆

堆内存（Heap Memory）是用于存储所有对象实例和数组的内存区域；是 Java 应用程序的主要内存区域之一，负责动态分配内存以支持对象的生命周期

-Xms: 初始堆内存 -Xmx：最大堆内存



堆内存通常分为以下几个区域，以支持不同阶段的对象生命周期管理：

## 新生代（Young Generation）：

 * Eden 区：新创建的对象首先分配在 Eden 区。
 * Survivor 区：Eden 区中的对象经过垃圾回收后，如果仍然存活，则移至 Survivor 区。

年轻对象在新生代中快速分配和回收，垃圾回收频率较高。

## 老年代（Old Generation）：

长时间存活的对象会从新生代晋升到老年代。 老年代用于存储生命周期较长的对象，垃圾回收频率较低，但回收过程更耗时。

重点关注老年代使用率



正常情况下应保持在80%以下，同时没有持续增涨不回收的现象

## 永久代（PermGen）/元空间（Metaspace）：

从 Java 8 开始，类元数据存储在元空间（Metaspace），不再属于堆的一部分。


## 非堆

非堆内存用于存储 JVM 自身的类结构和方法，而不是应用程序的对象数据，以下是非堆内存中的几个关键区域

 * Code Cache

当 Java 方法被调用时，JIT 编译器会将字节码编译为本地机器代码，并存储在 Code Cache 中，以提高执行效率。 Code Cache 的大小可以影响应用程序的性能，特别是在需要频繁编译代码的情况下。 可以通过 JVM 参数 -XX:ReservedCodeCacheSize 来调整 Code Cache 的最大大小。

 * Metaspace

从本地内存中分配空间，默认情况下是动态扩展的，受限于可用的系统内存。 可以通过 -XX:MetaspaceSize 和 -XX:MaxMetaspaceSize 参数来设置初始和最大 Metaspace 大小。 增加 Metaspace 的大小可以减少类加载和卸载的频率，从而提高性能。

 * Compressed Class Space

Compressed Class Space 是 Metaspace 中的一个子区域，用于存储类指针的压缩版本。 在 64 位 JVM 中，使用压缩类指针可以减少指针的大小，从而节省内存。 Compressed Class Space 的大小是在 Metaspace 的总大小内计算的，可以通过 -XX:CompressedClassSpaceSize 参数设置


## GC（垃圾回收）

在 Java 虚拟机（JVM）中，垃圾回收（Garbage Collection, GC）是自动管理内存的关键机制。GC 的主要目标是识别和清理不再使用的对象，以释放内存空间。JVM 中的垃圾回收通常分为年轻代（Young Generation）和老年代（Old Generation）两部分

老年代 GC 通常在老年代内存空间不足时触发。当对象在年轻代经过多次垃圾回收后仍然存活，会被晋升到老年代。随着时间的推移，老年代可能会被填满，从而触发老年代 GC，这可能会导致应用程序暂停（Stop-the-World），注意观察老年代gc的时间和次数。

Full GC 是一种更全面的垃圾回收过程，通常在以下情况下触发：

 * 老年代空间不足，且无法通过老年代 GC 释放足够的空间。
 * 显式调用 System.gc()（尽管不建议依赖此方法）。
 * Metaspace 或者其他内存区域不足。
 * CMS（Concurrent Mark-Sweep）GC 的失败。

过程： Full GC 会对整个堆内存（包括年轻代和老年代）进行回收。可能还会涉及其他内存区域，如 Metaspace（Java 8 及以上）




## 运行模式

运行模式必须是：product




## 连接池&线程池


## 连接池

观察数据库连接池的活动连接，可大致判断数据库是否有性能问题 注意最大连接应大于峰值连接数，否则会出现连接池耗尽异常，影响正常业务



如果存在大量活动连接堆积，没有及时回收且持续上涨；但活动线程数远低于数据库连接池的活动连接，那么可能存在连接泄露的现象


## 线程池



编撰人：wangyxyf




快速跳转



 * OA系统监控详解
   * JVM介绍
     * 堆
       * 新生代（Young Generation）：
       * 老年代（Old Generation）：
       * 永久代（PermGen）/元空间（Metaspace）：
     * 非堆
   * GC（垃圾回收）
   * 运行模式
   * 连接池&线程池
     * 连接池
     * 线程池



分享链接分享链接

## 24. 平台开发组件库(简版)

> 原始路径：`/38/67.html`  
> 相对路径：`38/67.md`

## 平台开发组件库(简版)

本文介绍V5平台丰富的组件库，建议收藏，在不同应用场景下可以使用平台现有组件开发。


## 环境及编译

完整本地开发环境搭建，详见【开发文档>快速开始>搭建开发环境】章节。

后台开发工具推荐IntelliJ IDEA，其次推荐Spring tools suite、Eclipse for J2EE。

V5最新版本工程使用JDK8，允许并推荐使用JDK8特性（Lambda、Stream等）来提升开发效率、缩减代码量。

> V5 V6.1及更早期版本可能需要使用JDK6来编译，具体情况请找熟悉老版本的指导人了解。


## 包引用规范

 * 禁止对JDK自带的sun包的调用：从JDK 1.7开始，Oracle未将以sun开头的类包加载到JVM启动加载的类包中

// Bad code
import sun.misc.BASE64Encoder;


 * 禁止使用Lombok，虽然能让JavaBean足够优雅，但强制要求所有IDE安装Lombok插件，并且DEBUG调用链很麻烦，同时对不熟悉Lombok的开发会有很大困惑，解释代价高。

 * 日志使用Apache Commons logging，所有的Log实例必须由CtpLogFactory创建。完整开发注意事项，详见【开发文档>CTP技术平台>LOG日志】章节。

 * 要求尽量使用com.seeyon.ctp下的平台接口开发，不推荐使用com.seeyon.v3x下的类。

// Not recommended
com.seeyon.v3x.xxx
// Good code
com.seeyon.ctp.xxx


 * 禁止[import *]偷懒式引入大量不必要的包，请显性引用需要的具体类，注意随手清理未被使用的import。

// Bad code
import java.util.*;
// Good code
import java.util.List;
import java.util.Map;


 * 推荐使用Apache common、Google guava等主流开源核心库，能让你在String、集合、并发、缓存等方面代码更加优雅简便。

// Instead of "new ArrayList()"
List<String> list = com.google.common.collect.Lists.newArrayList();
list.add("");
// Instead of "list != null && list.size() > 0"
boolean isNotEmpty = org.apache.commons.collections4.CollectionUtils.isNotEmpty(list);
// Cache of LRU
CacheBuilder.newBuilder().maximumSize(100);



## CTP平台Util工具类

完整平台工具类API，详见【开发文档>Open API>Java Doc】。

本节全部介绍CTP平台Util工具类，主要来自于com.seeyon.ctp.util。

> 如果你有代码权限，建议开发从ctp-core/src/com/seeyon/ctp/util和seeyon-util/src/com/seeyon/ctp/util两个地方逐个阅读每个工具类，半天时间就能熟悉所有工具类。

 * BeanUtils类对象操作工具，提供将一个Bean对象的属性值复制到另一个Bean对象的能力，也提供copy复制Bean对象能力。

TimeViewInfo v = BeanUtils.clone(viewInfo);
// 将summary中的值同步到hisColSummary中，拷贝共同属性的值
public void save(ColSummary summary) throws BusinessException {
    HisColSummary hisColSummary = new HisColSummary();
    BeanUtils.convert(hisColSummary, summary);
    ......
}


 * 禁止使用SimpleDateFormat转换日期，要求使用com.seeyon.ctp.util.Datetimes来实现日期对象管理，尤其是涉及国际化时区更要用这个工具类。

// Bad code
new SimpleDateFormat().format(date)
// Good code
Date firstTime = Datetimes.getTodayFirstTime();
Date curDate = Datetimes.parse(beginDate, Datetimes.datetimeStyle);
String deadline = Datetimes.format(deadlineDate, Datetimes.datetimeStyle);


 * ParamUtil获取页面form提交Map数据，提供getString、getInt等工具类快速从Map中获取指定key的值

Map<String ,Object> params = (Map<String, Object>) ParamUtil.getJsonParams();
String name = ParamUtil.getString(params, "name", true);
String memo = ParamUtil.getString(params, "memo");


 * Base64工具类用于转码、解码操作，基于RFC 2045协议

> 注意Base64只是一种二进制的编码方式，常用于网络图片、文件流数据传输，千万不要用来当做加密算法使用。

String encodeStr = Base64.encodeString(str);
String decodeStr = Base64.decode2String(str);


 * FileUtil文件封装工具类，用于获取文件编码、快速复制、创建、删除文件及文件夹操作。

"utf-8".equalsIgnoreCase(FileUtil.detectEncoding(string : full path));
FileUtil.copyFile(File : source,File : newTarget)


 * HttpClientUtil包装了远程调用网络地址的方法，支持get/post两种方式。一定一定一定要设定超时时间，（若未设置）当出现远程地址不通时会出现大量请求挂起从而导致系统拥塞。

> 如需GET、POST、PUT、DELETE这些更全面的HTTP请求工具，推荐使用org.springframework.web.client.RestTemplate

// 3000是超时时间
 HttpClientUtil h = new HttpClientUtil(3000);
 try {
  h.open("http://news.sina.com.cn", "get");
  int status = h.send();
  h.getResponseBodyAsString("GBK");
 }
 catch (IOException e) {
  logger.error(e.getLocalizedMessage(),e);;
 }
 finally {
  h.close();
 }
 
 HttpClientUtil h = new HttpClientUtil(5000);
 try {
  h.open("http://oa.com/something.do", "post");
  h.addParameter("name", "ta");
  h.addParameter("password", "123456");
  h.setRequestHeader("Cookie", "Language=zh_CN;UserAgent=PC");
  int status = h.send();
  h.getResponseBodyAsString("GBK");
 }
 catch (IOException e) {
  logger.error(e.getLocalizedMessage(),e);;
 }
 finally {
  h.close();
 }


 * HttpSessionUtil.getSessionId(HttpServletRequest)可以方便取出当前用户的SESSIONID

 * IOUtility通用IO流文件操作工具类，提供了流的复制下载、迁移、转字符串、转Byte等操作

private void download(HttpServletResponse response,File toFile) throws Exception{
        InputStream fis =new FileInputStream(toFile);
        // 取得文件名。
        String filename = toFile.getName();
        response.reset();
        // 设置response的Header
        response.addHeader("content-disposition","attachment; filename=" +  filename);
        response.addHeader("Content-Length", "" + toFile.length());
        response.setContentType("application/octet-stream");
        // 以流的形式下载文件。
        IOUtility.copy(fis, response.getOutputStream());
}


 * LightWeightEncoder轻量级转码工具类，在Base64做了一个转码结果位移操作，简单说就是把字符串A简单混淆成字符串B。非加密算法，请勿用于加密场景。

// 混淆
String encStr = LightWeightEncoder.encodeString(str)
// 解除混淆
String decStr = LightWeightEncoder.decodeString(str)


 * ObjectToXMLUtil提供Java对象转换为XML字符的工具方法，基于dom4j实现。XML转换为Java对象请务必调用XXEUtil.safeParseText实现XML外部实体注入(XML External Entity)的防护，再用Dom4j的Document解析实现。

> 不要使用Xsteam组件，老版本爆出存在远程代码执行漏洞，安全要求高的公司会审计不允许使用Xsteam。

// object to xml
String xml = ObjectToXMLUtil.objectToXML(Object);
// xml to object,务必使用XXEUtil.safeParseText
Document document = XXEUtil.safeParseText(xmlData); 
Element rootElement = document.getRootElement();


 * PropertiesUtil封装了java.util.Properties的常用操作，能够将指定.properties文件转换为Properties对象，以及修改保存.properties文件内容。
 * ReqUtil用于快速提取HttpRequest中的值

public ModelAndView mvc(HttpServletRequest request, HttpServletResponse response) throws Exception {
    String name  = ReqUtil.getString(request, "name", ""defaultValue"");
    // Instead of : Long.valueOf(request.getParameter("id"));
    Long id = ReqUtil.getLong(request, "id");
    ......
}


 * RespUtil提供了sendJsonResponse方法，用于直接向页面输出一个text/json格式的数据流

public static void sendJsonResponse(HttpServletResponse response, Object jsonObj) throws IOException {
        String json = JSONUtil.toJSONString(jsonObj);
        response.setContentType("text/json; charset=utf-8");
        response.setHeader("Cache-Control", "no-cache");
        PrintWriter pw = null;
        try {
            pw = response.getWriter();
            pw.write(json);


 * ServerDetector用于判断当前应用服务器（中间件）型号，比如判断是否为Tomcat、Weblogic、WebSphere、国产东方通、国产金蝶等

/**
     * 判断当前产品是否运行在国产化环境。
     */
    public static boolean isDomestic() {
     return ServerDetector.isApusic() || ServerDetector.isTongWeb() || JDBCAgent.isDMRuntime() || JDBCAgent.isKingBaseesRunTime();
    }


 * Strings工具类提供字符串的常用操作
 * UUIDLong.longUUID()常用于生成一个不重复的数据库主键ID
 * XXEUtil为XML解析相关的实体增加XXE防护的工具类，XML外部实体注入(XML External Entity)是一种注入XML中的攻击方式，我们在将XML解析为Java对象时需要做相关防护，所以XXEUtil.safeParseText(XML)是标配写法。

// Good code
org.dom4j.Document document = XXEUtil.safeParseText(XML);
// Bad code
org.dom4j.Document document = (new SAXReader()).read(path);


 * ZipUtil文件的压缩和解压工具类


## CTP实用辅助类

 * com.seeyon.ctp.common.SystemEnvironment系统环境相关工具类，极其常用，比如你想判断当前环境是否为集群、当前服务器的base目录地址、附件目录地址都可以从这里获取到。用于获取当前服务器的base目录、seeyon上下文目录，临时文件temp目录、日志文件目录、共享附件目录、用户配置的外网地址、当前中间件类型、本次服务器启动时间、单机还是集群模式、获取停用插件列表、直接停止服务、是否为国产化环境（中间件和数据库判断）、Redis是否开启、是否为生产环境。
 * com.seeyon.ctp.common.AppContext系统级上下文工具类，万能类，极其常用：

// 获取到当前登录的人员信息，常广泛用于
和Manager中。PS：实际我们推荐只在Controller、Rest中使用，而Manager和Dao则是在方法上以参数的形式将User传入。
User user = AppContext.getCurrentUser();

// 下面这个方法是对ThreadLocal的包装，此方法常用于在同一个线程栈+调用链很长的类与类共享参数所用。
// 比如：前端发送一个请求到后端，常规的调用链是：前端Form->后端拦截器->Controller->Manager->Dao，那么在Dao层希望获取到当前登录的用户以便SQL只获取当前登录用户的数据。而当前登录用户信息在拦截端能够获取到，那么拦截器就可以通过putThreadContext将用户信息写入，随后Dao层通过getThreadContext就能拿到拦截器传入的信息。
// 拦截器端：将当前用户信息写入到ThreadLocal
AppContext.putThreadContext("CURRENT_USER",User);
// Dao层：由于Dao与拦截器在同一个Thread里面，所以就能获取到拦截器传入的信息
User user = AppContext.getThreadContext("CURRENT_USER");
// 当然，拦截器发现自己写入的线程已经无需使用时，则要主动做下销毁动作，防止不必要的资源开销。
AppContext.removeThreadContext("CURRENT_USER");

// 不推荐使用：获取本次请求的Request或Response对象，本身ServeltRequest和response只能存在于C层，请勿在Manger甚至Dao层滥用。允许在Rest接口中使用。
AppContext.getRawRequest();
AppContext.getRawResponse();

// hasPlugin用于判断指定插件是否存在，常用于没有指定插件时屏蔽相关代码逻辑操作
boolean hasCAP = AppContext.hasPlugin("cap4");
// 伪代码示例：保存一条数据后，需要通知全文检索更新索引。开发需要调用全文检索API，但如果系统没有全文检索插件，API会是Null，如果不做防护就会报空指针异常，此时我们就可以使用hasPlugin做下防护。
if(AppContext.hasPlugin("index")){
    // 只有index插件时，indexApi才会被Spring初始化，也不会出现Null对象
    indexApi.buildIndex(colId,Enum.COLL);
}

// hasResourceCode用于判断当前登录用户是否有指定菜单资源权限
// 我们系统有非常多的菜单资源，每个菜单资源都有一个名称以及唯一表示resourceCode，后台可以配置什么人员可以使用什么菜单，不是所有人都有所有菜单权限。那么在应用中，某些特殊操作要求做判断时，你可能就会用到这个判断。
if(!AppContext.hasResourceCode("F01_newColl")){
    // 提示当前用户没有 新建协同操作权限
}

// 普通用户的resoueceCode从哪里查询：select m.NAME as '菜单国际化key',m.EXT7 as '菜单中文名',m.RESOURCE_CODE as 'resourceCode',m.RESOURCE_NAVURL as '菜单跳转URL' from priv_menu m
system.menuname.BBS 讨论 F114_bbs /bbs.do?method=listBoard
doc.video.square 视频广场 F04_docVideoSquare /doc.do?method=docIndex&openLibType=6

// V8.1开始，管理员的resourceCode从哪里查询：/seeyon/WEB-INF/cfgHome/metadata/entRoleStd或govRoleStd两个文件夹的XML，示例如下（如下XML属性code就是resourceCode）：
<menu code="org_tree" sort="1" name="common.org.chart" desc="组织架构图" icon="icon-company" target="mainfrm" plugin="" url="/organization/account.do?method=showTree&amp;from=orgModelManager" ></menu>
<menu code="org_account_setting" sort="2" name="menu.group.orgaAccount.setting" desc="单位管理" icon="icon-company" target="mainfrm" plugin="" url="/organization/account.do?method=viewAccount" ></menu>


 * com.seeyon.ctp.common.constants.ApplicationCategoryEnum系统内所有标准产品模块枚举值，此对象经常用来做应用的分类。另外还有个类似的类：com.seeyon.ctp.common.ModuleType。
 * com.seeyon.ctp.common.flag.SysFlag不同产品线功能切割枚举，这个类的作用很抽象，对于客开无用，对于标准产品研发人员有很大作用。

举例说明：V8.1 CTP平台下发布A6+、A8+企业版、A8+集团版、A8-N企业版、A8-N集团版等5个版本，现在新产品开发了一个“双因子认证”的功能，由于此功能在集团客户才使用，为避免给企业版客户带来解释成本，产品经理要求：“双因子认证”功能只针对A8+和A8-N集团版开放。恰好双因子认证不是一个收费插件，技术上是一个通用组件，为了屏蔽此功能，则可以使用SysFlag的特性。

public enum SysFlag {
    // 登记一条枚举，false表示不开通双因子认证能力
    doublefactorEnable(false, false, true, false, true),
    ......

    SysFlag(Object a6Flag, Object a8enterpriseFlag, Object a8groupFlag, Object a8NenterpriseFlag, Object a8NgroupFlag) {
        ......
    }
}

- com.seeyon.ctp.common.constants.ProductEditionEnum，CTP平台下集成的所有版本枚举信息，A6+、A8+、A8-N都各有枚举注册在其中。不推荐调用此枚举类，如果应用上希望某个功能在A6+不显示，在A8+显示，请使用上一个SysFlag特性。

- com.seeyon.ctp.common.constants.SystemProperties系统级配置集合，Seeyonconfig应用配置器下的配置和/seeyon/WEB-INF/cfgHome/plugin/插件/pluginProperties.xml中注册的信息都会放入SystemProperties。


String prodcutId = SystemProperties.getInstance().getProperty("system.ProductId")

// 调用点，通过直接调用枚举就能知道当前系统是否支持该功能
if(SysFlag.doublefactorEnable.getFlag() == true){
    // 显示双因子认证功能
}



## CTP业务工具类

 * 国际化：后台使用ResourceUtil.getString("xxx")调用；前端JSP使用${ctp:i18n('xxx')}调用；前端js在引用国际化资源库之后，使用$.i18n("xxx")调用。

> 如果前端Javascript需要调用到指定国际化key，需要在cfgHome/plugin/插件/i18n下维护一个export_to_js.xml文件，开发可以参考别的插件的编写方法。

更多国际化开发内容详见【开发文档>CTP技术平台>国际化】章节！

 * 用户操作日志：用户的重要操作需要写入到平台的操作日志中，注意不是log.info这种写入文本日志，而是使用AppLogManager接口写入到数据库中统一管理。

@Inject
private AppLogManager appLogManager;
appLogManager.insertLog(...);


 * 二维码：平台提供了简易的二维码组件

com.seeyon.ctp.common.barCode.manager.BarCodeManager barCodeManager;
// 保存二维码，二维码会以附件的形式存储到附件目录中
barCodeManager.saveBarCode(...);
// 从附件目录中取出指定二维码文件
barCodeManager.getBarCodeFile(...);


 * 临时异步线程：众所周知，Java提供了new Thread().start()这种很简易开启异步线程的方法，但为了保障平台线程安全可靠，我们要求开发不要主动调用start()方法，而是交给平台线程池来启动。

// Bad code
Thread newT = new xxxThread();
newT.start();

// Good code getDefaultThreadPool()是默认的线程池，常规操作用这个就够了
Thread newT = new xxxThread();
ExecutorServiceFactory.getDefaultThreadPool().submit(newT);

// Good code
ExecutorServiceFactory.getDefaultThreadPool().submit(new Runnable(){...});

// 初始化一个固定数量的线程池，"DemoWorker-" + AppContext.getCurrentTenantId()是这个线程池的标识
ExecutorServiceFactory.setThreadNum("DemoWorker-" + AppContext.getCurrentTenantId(), 1, 10);
ExecutorServiceFactory.getFixedThreadPool("DemoWorker-" + AppContext.getCurrentTenantId()).submit(thread);

// 初始化一个动态扩张的线程池，类似于数据库连接池的概念，默认初始化一个最小值，随后根据写入的线程数量弹性自增
ExecutorServiceFactory.setThreadNum("WF_AutoSkipRunnable_Pool", 30, 50);
ExecutorServiceFactory.setqueueSize("WF_AutoSkipRunnable_Pool",10000);
ExecutorService asynEventExecutors = ExecutorServiceFactory.getCachedThreadPool("WF_AutoSkipRunnable_Pool");
for(){
    asynEventExecutors.execute(thread);
}


 * 常驻异步任务处理：AsynchronousBatchTask，有些动作需要我们开一个常驻后台任务一直运行，比如消息处理器，就要一直留存一个独立线程，有消息过来就处理，没有就做个短休眠。

AsynchronousBatchTask的功能特性是：需要通过Spring Bean管理；通过.addTask(...)方法写入预执行数据到队列中；默认8秒执行一次批量任务，可以重写getIntervalTime()方法来设置默认执行时间，单位S秒；重点是重写doBatch()方法，这个方法用于做数据的批量处理。

> 在线程堆栈中带"AsynchronousBatchTask"标识的都是常驻异步任务。

// 一个典型的示例
public class TimeViewWorker extends AsynchronousBatchTask<TimeViewEventBean>{
    @Override
    public void doBatch(List<TimeViewEventBean> data){
        // 批量处理消费方，这个自己实现批处理操作
     try {
      timeViewManager.saveTimeViewEventBO(data);
     }catch (BusinessException e) {
      log.error("", e);
     }
    }
}

// 生产方
AppContext.getBean("timeViewWorker").addTask(data);


 * 系统消息：PC右下角的消息盒子、致信消息、移动端的消息均使用UserMessageManager调用发送。消息组件有些潜规则：如果PC在线，移动端就收不到消息。

@Inject
private UserMessageManager userMessageManager;
// 发送系统消息
userMessageManager.sendSystemMessage(...);
// 更新指定消息状态为已读，场景常见于用户收到某个数据消息但一直没打开，过了一段时间这条数据被自动处理了，为了保证最佳体验可以考虑更新状态
userMessageManager.updateSystemMessageStateByUserAndReference(...);


 * 系统全局开关：SystemConfig，这个对象保留的是<key,value>格式，value只有enable和disable两个选项，非0即1。这个变量存储了各种必要的配置，比如是否开启验证码，是否附件加密，是否开启密码强度控制等。

数据来自两个地方：

 1. select * from ctp_config where CONFIG_CATEGORY = 'system_switch'
 2. /seeyon/WEB-INF/cfgHome/spring/spring-config-manager.xml中关于systemConfig的defaultValue默认配置

// 调用方式如下IConfigPublicKey中有所有开关的配置
@Inject
private SystemConfig systemConfig;
boolean canReMove = SystemConfig.ENABLE.equals(systemConfig.get(IConfigPublicKey.CAN_DEL_PENDING));


 * 动态配置管理：configManager，这个对象保留的是<key,value>格式，key有自己自定义，value是字符串并且由自己自定义。本对象的作用是在数据库中提供一个快速存储动态配置参数的地方。你可以把configManager当作一个数据表级别的Properties文件来看。

简单点说，我现在要做一个数据初始化操作，只希望系统安装好第一次启动时才执行这个逻辑。那么，我肯定需要在某个地方存储一下是否执行过初始化的标记，如果是以前，你可能需要自己建张表维护这条数据，非常浪费表空间，那么configManager提供了非常方便的读写操作，减少了多余表的维护。

> configManager的表数据存储于select * from ctp_config，大家的少量动态配置数据都可以放入这里面

@Inject
praivate ConfigManager configManager;
init(){
        ConfigItem config = configManager.getConfigItem("dataInit", "enable");
     if(config != null) {
      String enable = config.getConfigValue();
      if("true".equals(enable)) {
       // 未初始化，下面执行初始化操作
       ......

       // 初始化完成后，使用addConfigItem更新状态为已经初始化完成
       configManager.addConfigItem("dataInit", "enable","false");
      }
     }
}


 * 系统枚举组件：没什么好说的，系统内枚举管理使用这个组件，可以open.seeon了解如何使用。

// 注意枚举组件beanname=enumManagerNew
private EnumManager enumManagerNew;


 * Excel解析和下载：FileToExcelManager，将数据导出成Excel或CSV是很常见的动作，平台提供了FileToExcelManager.save这种比较简便实用的导出接口。

@Inject
private FileToExcelManager fileToExcelManager;
......
HttpServletResponse response = ...
try {
    DataRecord dataRecord = new DataRecord();
    dataRecord = getDataRecord(...);
    // 将Excel导出
    fileToExcelManager.save(response, dataRecord.getTitle(), dataRecord);
} catch (Exception e) {
    logger.error(e.getLocalizedMessage(),e);
}

//读取第一个sheet的Excel值
fileToExcelManager.readExcel(file);


 * 平台级异常：BusinessException是CTP平台通用异常，Controller、Manager、Dao中定义异常都默认使用此类，CTP平台级异常路径：com.seeyon.ctp.common.exceptions

public class DemoController extends BaseController {

    public ModelAndView demoUrl(HttpServletRequest httpRequest, HttpServletResponse httpResponse) throws BusinessException{
        ......
    }

}


 * 附件组件：AttachmentManager，各功能应用对附件的上传和下载归Attachment模块管，附件组件与平台前端标签一起合并使用，可实现连贯的上传、保存、展现操作。使用附件组件上传的数据，在ctp_attachment表中存储有记录数据。

// 前端JSP，定义附件组件按钮示例
<div id="attFileDomain" class="comp" comp="type:'fileupload',attachmentTrId:'Att',applicationCategory:'6',checkSubReference:false,canFavourite:false,canDeleteOriginalAtts:true,originalAttsNeedClone:true,callMethod:'uploadAttachment',delCallMethod:'uploadAttachment',takeOver:false,noMaxheight:true" attsdata='${attListJSON}'></div>

// 保存附件，支持多种传参形式，建议阅读注释文档，选择准确的调用方式
attachmentManager.create(......);
// 删除数据库中附件数据，但附件文件未做物理删除
attachmentManager.deleteByReference(,);
// 删除数据库中附件数据，同时附件文件也做物理删除
attachmentManager.removeByReference(,);
// 获取附件信息
List<Attachment> atts = attachmentManager.getByReference(,);


 * 上传下载组件：
 * 关联文档：

<div id="attachmentTR" style="display:none;"></div>
<div class="comp" comp="type:'assdoc',applicationCategory:'30',canDeleteOriginalAtts:true,attachmentTrId:'position1', modids:'1,3,6'" attsdata='${attachmentJSON}'></div>


 * java.net.URLEncoder.encode和java.net.URLDecoder.decode常用于对URL中带中文的字符进行编码和解码，防止出现乱码问题
 * 日志处理统一使用Apache Common Log，LOG引用严格按照如下代码示例执行，日志记录有讲究，请务必理解下面的写法深意。

private static Log LOGGER = CtpLogFactory.getLog(XXXManager.class);

// 记录DEBUG级别日志标准写法LOGGER.isDebugEnabled()打头，想想这样写的好处
if(LOGGER.isDebugEnabled()) {
    LOGGER.debug("The value "+value+" is "+data);
}

try {
    ......
} catch(Exception e) {
    // catch代码只能有两种处理方式：第一种就是向上抛出异常；第二种就是LOG.error(string,throwable);
    // Bad code 直接拼接exception堆栈是错误的写法，这样会导致LOG日志异常信息不明确
    LOGGER.error("全文检索删除会议失败" + e);
    // Good code 下面是标准的异常处理写法
    LOGGER.error("全文检索删除会议失败", e);
}



## 数据库、Hibernate持久层、SQL规范

 * 数据库不要使用触发器、视图、存储过程，这将给标准客户安装部署升级带来实施复杂度。
 * 数据库表一般要求默认一个ID主键（bigint类型UUID，非自增），不允许建立外键。
 * 持久层使用Hibernate，尽量少用Hibernate的一些开箱即用的特性，这些简便的特性在小项目很方便，但在大项目将带来灾难性的问题。
 * Hibernate hbm mapping配置不要有one-to-many这类外键关系。
 * DBAgent是HSQL包装类，JDBCAgent是JDBC SQL包装类，开发无需自己获取Connection，使用这两个包装好的Agent可以对数据库进行增删改查操作。这两个Agent只允许在Dao层使用，不允许在Manager甚至Controller使用。

// Good code
public class OrgDaoImpl implements OrgDao {
    public xxx() {
        List r1 = DBAgent.find(hql,params,flipinfo);
        int r2 = DBAgent.count(hql);
        DBAgent.saveAll(List<Po>);
        DBAgent.get(id);
        DBAgent.delete(x);
    }
}
// Bad code
public class OrgManagerImpl implements OrgManager {
    public xxx() {
        DBAgent.find(hql,params,flipinfo);
    }
}


 * 关于JDBCAgent，开发一定一定一定要注意手动close连接，否则错误的编写方法会导致连接池泄漏。而DBAgent则交由Spring事务管理，无需显性close连接。

自7.1SP1版本，推荐使用JDBCAgent(boolean b1, boolean b2)来创建JDBC连接：

 1. b1为true表示使用原始的数据库Connection构造JDBCAgent;为false则使用Spring管理的数据库连接，推荐默认false
 2. b2为true表示使用完毕之后无需手动close，由平台代理autoClose；为false表示JDBCAgent使用完毕之后手动close，一般close操作放在finally中，推荐默认false

// new JDBCAgent(false则使用Spring管理的数据库连接, false表示显性close连接)
JDBCAgent jdbc = new JDBCAgent(false, false); // 等同于new JDBCAgent();
try {
 jdbc.xxxxx
} catch (Exception e) {
 logger.error("", e);
} finally {
        // 关键代码：new JDBCAgent(false, false)之后务必显性jdbc.close连接，否则会出现连接池泄漏
 jdbc.close();
}


 * 不要使用DBAgent.merge和DBAgent.saveOrUpdate（Hibernate智能代理：不存在的数据执行insert，存在的数据执行update），如果你有一部分数据要保存一部分要更新，则分别调用save和update方法。
 * 批量写入数据使用DBAgent的savePatchAll和updateAll

> 根据注释，DBAgent.savePatchAll比saveAll性能更好

// Bad code
for(obj){
    DBAgent.save(obj);
}
// Good code
DBAgent.savePatchAll(list<obj>);


 * Manager是业务层，方法命名受事务管理，具体的事务隔离级别详见：/seeyon/WEB-INF/cfgHome/spring/spring-default.xml
 * 慎重使用"From xxxPO"这种简易HQL，不仅存在潜在性能问题，同时当你对查询出来的结果进行set操作时，会自动触发Hibernate的update潜规则。

List<CtpAffair> affair = DBAgent.find("From CtpAffair");
for(affair){
    affair.getTitle(); // 数据库title=张三
    // 巨坑：执行set操作后，set的值将会自动更新到数据库
    affair.setTitle("李四"); // 数据库title=李四
}


 * SQL in超过1000时，在Oracle等数据库上会报错，查询效率也会指数级降低。在必须使用in(超过1000条数据)时，推荐每次分成999条、分多次SQL查询，最后汇总。

List<Long> ids // ids.size() > 1000
List<List<Long>> pages = Lists.partition(ids, 999);
for (List<Long> idList: pages) {
    // idList.size() == 999
    // 伪代码，仅供参考
    DBAgent.find("select id from demo where id in (?)",idList);
}


 * SQL注入是一种危害性极大的安全漏洞，注入源来自开发将SQL条件进行字符串拼接。防止SQL注入的方法：要求所有SQL需要使用预编译的形式开发，条件变量采用占位符的形式写入。

public find(String name){
    // Bad code 存在SQL注入
    DBAgent.find("select id from demo where name = '" + name+"'");
    // Good code 其中name使用":name"或"?"预编译占位符的形式，能防护SQL注入
    DBAgent.find("select id from demo where name = :name",name);
}


 * SQL语句中的Like同样存在SQL注入风险，需要使用平台的SQLWildcardUtil.escape()方法对模糊查询条件进行特殊字符过滤，这样能防护SQL注入

String hql = "select id from demo where name like :name";
// Bad code
params.put("name", "%" + name + "%");
// Good code
params.put("name", "%" + SQLWildcardUtil.escape(name) + "%");
DBAgent.find(hql,params);


 * 如无必要，少用数据库自带的特殊函数，因为我们要兼容多款数据库，尽快使用通用SQL编写代码。如果不同数据库确实有差异，需要针对不同库写不同的SQL代码。
 * 判断当前是什么数据库，使用JDBCAgent下面的包装类，提供了多种方式。

方案一：推荐，使用JDBCAgent.isXXXRuntime()方法
是否为SQLServer数据库：{com.seeyon.ctp.util.JDBCAgent.isSQLServerRuntime()}
是否为Oracle数据库：{com.seeyon.ctp.util.JDBCAgent.isOracleRuntime()}
是否为MySQL数据库：{com.seeyon.ctp.util.JDBCAgent.isMySQLRuntime()}
是否为PostgreSQL数据库：{com.seeyon.ctp.util.JDBCAgent.isPostgreSQLRuntime()}
是否为达梦数据库：{com.seeyon.ctp.util.JDBCAgent.isDMRuntime()}

// 方案二
String dbType = JDBCAgent.getDBType();
if ("microsoft sql server".equals(dbType )){
    ......
}

// 方案三：getDatabaseType()和getDBType()的关系是：getDBType() = getDatabaseType().toLowerCase()
String dbType = JDBCAgent.getDatabaseType();

// 方案四：获取方言
Dialect dialect = JDBCAgent.getDialect();
if (dialect instanceof MySQLDialect) {
    ......
}


 * SQL性能调优：**禁止在for中循环调用SQL，这个是最最最常见的性能问题。**不要偷懒：因为Dao没有提供批量方法就逐个调用，请务必编写批量获取数据的接口。

// Bad code
for(id){
    list.add(DBAgent.get(id));
}
// Good code ： 多次SQL查询改为一次SQL查询
list = DBAgent.find("select xx from demo where id in (:ids)");

// Bad code 如果别人的API没有提供批量操作，请一定要通知别人提供批量操作的接口，不要用下面的方式写代码
for(xxx){
    demoApi.update(obj);
}
// Good code 编写批量操作数据的接口
demoApi.getBath(list<obj>);


 * SQL性能调优：禁止使用HQL "From xxPO Where xxx" 或 SQL "SELECT * FROM xxx"这类全量SQL查询命令，请按需查询指定列结果。尤其是字段过多、LOB大字段多、数据量大的表，查询全列性能很差。

// Bad code
DBAgent.find("From CtpAffair Where ...");
// Good code
List<Map> result = DBAgent.find("SELECT new Map(c.id as id,c.name as name) From CtpAffair c Where ...");


 * SQL性能调优：判断某条数据在Database中是否存在请用count。

String hql = "select id from demo where title = ?";
// Bad code ：通过find把结果集查询出来，再通过list.size判断数据是否存在，这种方法及其不省电
List result = DBAgent.find(hql);
if(result.size() > 0){
    return true;
}else{
    return false;
}

// Good code ， 类似于： select count(id) from Demo ，通过查询结果返回影响行数。
int result = DBAgent.count(hql);
if(result > 0){
    return true;
}else{
    return false;
}


 * SQL性能调优：建表之初就需要预估表数据量，对频繁查询排序的字段增加相应索引，尽量创建多字段组合索引，少创建单一索引，组合索引也能让单字段生效。

> 影响SQL查询效率的点：SQL条件字段、排序字段，需要针对查询条件字段和排序字段进行索引建立

// 使用explain用来分析SQL性能是基本功，开发必备技能
explain select id from demo where yyy;


 * SQL性能调优：多表关联代码尽量少用HQL（表关联灵活性不够），推荐使用SQL能提升效率，并且有更大的调整空间。

// Not recommended
Select x from CtpAffair ca,ColSummary cs where ca.objectId = cs.id and xxx
// Recommended
Select x from ctp_affair ca left join col_summary cs on cs.id = ca.object_id where xxx


 * SQL性能调优：少使用is not null、is null、<>、or这类匹配条件，这类语句会导致SQL无法走索引

// Bad code：带or不走索引，会导致SQL整体效率低
select id from demo where age > 20 or age < 10;
// Good code：使用union能保证两条SQL都走索引，效率很高
(select id from demo where age > 20) union (select id from demo where age < 10);


 * SQL性能调优：不要让列字段默认值为NULL，如果是空值也推荐尽量赋一个默认值，这样SQL查询效率是提升的。

> 如果对带有Null的字段进行SQL排序，某些数据库下空值会排在前面，代码还不好修改

// Bad code
demo.setAge(null); // 不推荐默认赋空值
DBAgent.save(demo);
select id from demo where age is null;
// Good code
demo.setAge(-1); // 推荐默认赋一个值
DBAgent.save(demo);
select id from demo where age = -1;


 * SQL性能调优：一条SQL不要关联超过3张表，在每张表有都一定数据量的情况下，表关联后查询效率很低。减少多余表关联的方法：放弃一定的范式规则，在表中增加冗余字段。

// 如果下面这条SQL查询效率很低时，可以想办法在demo表中冗余存储ddemo.object字段
select d.title from demo d left join ddemo dd xxx where dd.object = yyy;
// Good code ： 适当冗余存储关联表数据，采用单表查询会明显提升SQL效率
select d.title from demo d where d.ddemoObject = yyy;


 * SQL性能调优：在表数据量足够大的时候，使用一条SQL表联查还不如分成两条SQL查询。

// 假设下面两张表的数据都很大，那么这条SQL在高并发下平均执行时间可能很长，但又无法增加冗余字段解决时，可以分两条SQL查询
select d.id from demo d left join ddemo dd on d.id = dd.dId where dd.object = yyy;

// 分两条SQL反而能让性能提升
List<Long> ids = DBAgent.find("Select dd.id from ddemo dd where dd.object = yyy");
DBAgent.find("Select d.id from demo d where d.ddId in (:ids)",ids);


 * SQL性能调优：SQL查询务必要做分页，CTP的持久层分页对象是FlipInfo。


## Spring Bean、类加载顺序、初始化要求

 * CTP使用Spring来管理Bean对象，默认使用XML配置进行Bean注入，配置文件存放于各插件下：/src/main/webapp/WEB-INF/cfgHome/plugin/插件名称/spring
 * Controller、Manager、Dao都交给Spring管理，允许set方法注入或@Inject注解注入。严禁在成员变量中使用AppContext.getBean()强制注入，严禁在构造函数中强制注入。

public class DemoController extends BaseController {
    // Bad code 不允许这种注入方法，此法会导致demoManager无法按照Spring默认编排的顺序初始化，而造成循环依赖，初始化失败！
    private DemoManager demoManager = (DemoManager)AppContext.getBean("demoManager");
    
    public DemoController(){
        // Bad code，交由Spring管理的Bean尽量不要重写构造函数
        demoManager = (DemoManager)AppContext.getBean("demoManager");
    }

    // Good code 标准的对象注入方式
    private FileManager fileManager;
    public void setFileManager(FileManager fileManager) {
        this.fileManager = fileManager;
    }
    
    // Good code 注解的形式注入，无需Set方法
    @Inject
    protected SpaceApi spaceApi;


 * 注入要求：Controller允许注入Manager，Manager允许注入Dao。严禁Controller注入Dao，或反向注入！
 * Rest类未受Spring管理，也不要注册到Spring XML中管理，所有继承了BaseResource的Rest接口类允许通过AppContext.getBean申明式加载Spring Bean对象。

// 以下写法是被允许的
public class DemoResources extends BaseResource{
  private static final Log LOGGER = CtpLogFactory.getLog(DemoResources.class);
  private WorkflowApiManager wapi = (WorkflowApiManager)AppContext.getBean("wapi");
  private AffairManager affairManager = (AffairManager) AppContext.getBean("affairManager");


 * 禁止在Spring XML中使用init-method，此时所有Bean尚未初始化完成，init-method中如果调用了别的Bean会出现调用失败等问题。

<!-- Bad code 绝对禁止使用init-method -->
<bean name="" class="" init-method="init" ></bean>


 * 有开发场景需要在启动系统过程中做一些初始化操作，比如定时任务初始化，请统一使用SystemInitializer机制，详见open.seeyon。

public class DemoManagerImpl extends AbstractSystemInitializer implements DemoManager {
    // 经典开头：养成记录日志的好习惯
    private Log LOGGER = CtpLogFactory.getLog(DemoManagerImpl.class);
    // 使用注解标准注入Bean
    @Inject
    private OrgManager orgManager;
    @Inject
    private IndexApi indexApi;
    
    // 重写AbstractSystemInitializer下的initialize方法，该方法的执行时间是：系统所有Spring初始化完成之后，根据平台默认任务编排依次执行继承了SystemInitializer的initialize方法
    @Override
    public void initialize() {
        // 此时所有Bean已经初始化完成，可以放心调用所有Bean
        orgManager.xxx
    }


 * 一些操作Bean的实用API都在AppContext中。

// 根据Spring管理的Bean名称获取Bean实例（带bean缓存以优化性能），非singleton的bean不适用
AppContext.getBean(beanName); 
// 根据Spring管理的Bean名称获取Bean实例，不走性能优化缓存，适用于非singleton的bean获取
AppContext.getBeanWithoutCache(beanName);

/* 根据Spring管理的Bean类型获取Bean实例Map，key为bean id或name，value为Bean实例  
*  前面SystemInitializer就是使用此场景，CTP通过getBeanOfType(SystemInitializer.class)找到所有注册了这个Initializer的对象，再for循环执行每个对象的initialize方法   */
Map<String, SystemInitializer> all = AppContext.getBeansOfType(SystemInitializer.class);
for(all){
  systemInitializer.initialize();
}



## 关于循环依赖

因为代理后对初始化的影响，bean之间循环依赖可能会导致FactoryBean is not fully initialized yet异常

需要手动对循环依赖的bean进行处理

比如

OrgDirectManager 依赖 RoleManager 依赖 OrgDirectManager

// 修改OrgDirectManager，不注入，去掉setRoleManager方法，使用Inject注解
    @Inject
    protected RoleManager roleManager;


OrgDirectManager 依赖 SpaceApi 依赖 SpaceManager 依赖 OrgDirectManager

// 修改OrgDirectManager，不注入， 去掉setSpaceApi，使用Inject注解
    import com.seeyon.ctp.util.annotation.Inject;
    @Inject
    protected SpaceApi     spaceApi;


OrgDirectManager 依赖 OrgManager 依赖 OrgDirectManager

// 修改OrgDirectManager，不注入， 去掉setOrgManager，使用Inject注解
    import com.seeyon.ctp.util.annotation.Inject;
    @Inject
    protected OrgManager       orgManager;



## 安全

更多安全开发内容详见【开发文档>快速开始>安全篇】章节！


## 前端

 * 我们的产品需要兼容IE、Chrome、Edge、360、国产化浏览器等各种浏览器，请尽量使用ES5的语法开发，避免高级语法在IE低版本浏览器无法使用。
 * 平台提供启动OA服务时自动压缩js的能力，只需通过XML配置，代码位置在:/ctp-common/src/main/webapp/common/compressconfig/compressconfig.xml，我们常见的all-min.js就在这个里面配置。

<!-- 压缩js示例 -->
<js>
    <inputfile><![CDATA[/messageLinkConstants.js]]></inputfile>
    <inputfile><![CDATA[/main/common/js/jquery-ui.draggable-min.js]]></inputfile>
    <inputfile><![CDATA[/common/js/ui/seeyon.ui.common-debug.js]]></inputfile>
    <inputfile><![CDATA[/common/js/ui/seeyon.ui.dialog-debug.js]]></inputfile>
    <inputfile><![CDATA[/common/js/ui/seeyon.ui.progress-debug.js]]></inputfile>
    <inputfile><![CDATA[/common/SelectPeople/js/orgDataCenter.js]]></inputfile>
    <outputfile isObscure="false"><![CDATA[/portal/portal-min.js]]></outputfile>
</js>


 * 所有js、css、html等静态文件尾部都需要带时间戳，防止浏览器缓存导致前端错误。

原理：主流浏览器在拉取xxx.js、xxx.css静态文件后默认会缓存文件，以减少刷新页面时重复向服务器下载静态文件的麻烦。但如果开发人员修改了js等静态文件，如果没有机制告知浏览器则无法重新下载新的js文件。

解决方法：在引用静态文件的所有地方都加一个后缀时间戳，每次修改了静态文件后，都更新这个时间戳，浏览器就会认为是新文件，随后执行下载更新。

> 如果你遇到修改客户服务器上的js文件不生效的话，可以尝试修改下引用这个js文件的html、jsp时间戳就能解决问题。

// .jsp中使用{ctp:resSuffix()}标签
<script type="text/javascript" charset="UTF-8" src="${path}/xxx.js${ctp:resSuffix()}"></script>
<link rel="stylesheet" type="text/css" href="${path}/xxx.css${ctp:resSuffix()}"/>

// .html中使用?V=STATIC_SUFFIX，这个"V=STATIC_SUFFIX"在CI构建时会被转换为一个字符串变量。如果是客开则注意自己按照生产态的格式写死字符串变量即可。
<!-- 开发态 -->
<link rel="stylesheet" href="/STATIC_PATH/common/all-min.css?V=STATIC_SUFFIX"/>
<!-- CI构建后，生产态 -->
<link rel="stylesheet" href="/seeyon/common/all-min.css?V=V8_1_20210525210000"/>


 * 开发前端页面时需要引用平台级变量，比如上下文、国际化等变量值，我们针对JSP和HTML提供了相应的解决方案：JSP中引用common_header.jsp和common_footer.jsp实现；Html中引用

// .jsp中
<%@ include file="/WEB-INF/jsp/common/common_header.jsp"%>
<body>
....
<%@ include file="/WEB-INF/jsp/common/common_footer.jsp"%>
<script ...>
</body>

// .html中引入如下请求地址
<head>


编撰人：admin、het


快速跳转



 * 平台开发组件库(简版)
   * 环境及编译
   * 包引用规范
   * CTP平台Util工具类
   * CTP实用辅助类
   * CTP业务工具类
   * 数据库、Hibernate持久层、SQL规范
   * Spring Bean、类加载顺序、初始化要求
     * 关于循环依赖
   * 安全
   * 前端



分享链接分享链接

## 25. 安全开发规范

> 原始路径：`/38/95.html`  
> 相对路径：`38/95.md`

## 安全开发规范


## Web安全漏洞和防御

以下列举了Web系统常见的安全漏洞，并非简单从网上摘抄片段，而是结合V5标准产品实际情况给出了具体解决方案。比如SQL注入、XXE、XSS、CSRF都是开发V5代码过程中常见的漏洞BUG，所有开发务必熟读并灵活运用。

而失效的身份认证和失效的访问控制则是无形中的安全问题，极易产生0Day高危，同样需要开发扎实的功底和敏锐的安全开发嗅觉。


## 一、SQL注入

SQL注入就是指Web应用程序对用户输入的数据的合法性没有进行判断，前端传入后端的参数使攻击者可控的，并且参数中带有数据库查询，攻击者可以通过构造不同的SQL语句来实现对数据库的任意操作。

SQL注入漏洞产生需要以下两个条件:

 * 参数是用户可控的:前端传给后端的参数内容是用户可以控制的
 * 参数带入数据库查询:传入的参数可以带入数据库中查询

## 攻击方法

String taskId = request.getParameter("taskId");
// Dangerous code
String sql = "SELECT ID,SUBJECT from task_info where ID="+taskId;
List result = executeSQL(sql);


以上代码是最常见的SQL注入案例，从代码写法上能看出：我们从客户端获得了一个taskId参数，然后将此参数作为条件放入SQL执行数据库查询。

攻击者可以自己组装客户端的请求参数，比如将taskID的值修改为：taskID=123 or id is not null，最终会执行如下SQL，显而易见：此时后台被SQL注入攻击了，此时攻击者能拿到该表的全部数据。

// 带有攻击的SQL，SQL注入：
SELECT ID,SUBJECT from task_info where ID = 123 or id is not null


## 防御方法

防护SQL注入非常简单，通俗说：所有SQL、HQL中Where条件查询都使用?、:param占位符的形式编写，不要直接使用 "column="+param这种SQL硬拼接方式。使用Mytabis 框架时，用#{}代替${}进行参数化查询。

专业说法就是：使用预编译SQL执行查询。

String taskId = request.getParameter("taskId");
// safer code
String sql = "SELECT ID,SUBJECT from task_info where ID= :id";
Map<String, Object> params = new HashMap<>();
params.put("id", Long.valueOf(taskId));


扩展：标准产品提供了SQL注入的检测手段：通过系统管理员>系统监控>底部按钮HQL Dump>打开链接即可看到当前系统是否存在SQL注入。


## 二、失效的身份认证

失效的身份认证，也叫冒充他人身份，常见场景为非法获得他人帐号权限，从而可以利用他人帐号身份进行非法操作。

危害:这些漏洞可能导致部分甚至全部账户遭受攻击，一旦攻击成功，攻击者就能执行合法的任何操作。

## 攻击和防御方法

攻击方式有很多，这里列举几个常见的：

1）弱口令

攻击方法：比如给所有系统用户默认密码123456，攻击者就可以猜到用户名的前提下，直接输入123456访问用户帐号。

防御方法：通过配置或修改代码增强密码强度，不允许用户设置密码为弱口令

2）内置固定帐号

攻击方法：系统为了简化管理员工作量，在安装系统时内置了固定的管理员帐号，如果管理员给帐号设置成弱口令，攻击者则可以很容易登录系统。

标准产品集成帆软8、9时遇到过帆软的固定管理员漏洞：如果首次访问帆软后台系统，需要设置管理员密码。这样导致，万一有用户没用过帆软后台系统，而攻击者成了首次访问者，攻击者就可以录入自己的密码登录，进行攻击。

防御方法：1、管理员密码在安装程序安装过程中设置，永远不内置固定帐号；2）用户密码不允许首次访问时设置，而必须在创建帐号时由用户录入与之绑定的高强度密码；3）每套系统的密钥随机生成并存放在安全的位置。

3）找回密码机制太弱

攻击方法：如果找回密码的认证机制太过简单，比如只需要输入帐号+手机号，不用获取手机验证码就可以找回的话，会导致攻击者在知道用户基本隐私信息下通过找回密码让帐号强制易主。

防御方法：增强找回密码验证机制，通过手机号获取短信验证码找回，通过邮箱确认链接找回。

4）极简的单点登录认证

单点登录是一种特殊的认证方式，通常通过URL中携带一个ticket参数，此参数与系统中的某个帐号身份对应，当系统单点登录认证通过后就会给予对应帐号相同的权限。单点登录这个ticket需要双方系统通过编码进行约定，如果ticket过于简单就容易被攻击者仿照模拟接管权限。

攻击方法：某些集成开发为了省事将ticket设置为用户的帐号，或者对帐号进行简单编码就当作ticket，这种方式都是错误的编码认证方式。

// Dangerous code
URL?ticket=system
// Dangerous code
URL?ticket=base64('system')


上面这种单点登录的ticket都是不安全的认证策略，攻击者只要猜到用户帐号就可以模拟相同的URL访问系统。

防御方法：产生和管理ticket的源头代码一定要强大且安全：保障ticket随机、带时效性！比如给对应帐号生成UUID的ticket，并且用户退出时自动销毁ticket或只允许ticket有xx分钟有效期。

/**下面是一段相对规范的SSO认证示例，本例是用户登录OA的前提下访问第三方系统前，由OA给第三方系统颁发证书的代码**/
String loginName = AppContext.currentUserLoginName();
// 从SSO认证中心查询当前登录人的ticket是否已经存在
TicketInfo ticketInfo = SSOTicketManager.getInstance().getTicketInfoList(loginName,"biinside");
if(ticketInfo == null){
    // 如果不存ticket，则自己注册一个ticket，推荐ticket是随机数
    String newTicket = String.valueOf(UUIDLong.absLongUUID());
    SSOTicketManager.getInstance().newTicketInfoList(newTicket, loginName, "biinside");
    // 与第三方通信，将当前ticket传输过去认证
	String sso = preUrl + "/api/Portal/A8SSO/?ticket="+newTicket;
}



## 三、敏感数据泄露

近年来，敏感数据泄露已经成为了一最常见、最具影响力的攻击，不久前就爆出过Facebook泄露了用户的大量信息，以及12306也多次泄露用户的信息。现在信息泄露已经成为了owasp top 10中的漏洞，可想而知敏感信息泄露现在已经成为十分严重的问题。

## 攻击方法

攻击者不是直接攻击密码，而是在传输过程中或从客户端窃取密钥、发起中间人攻击，或从服务器端窃取明文数据，还有可能由于管理员的安全性不高，使用弱密码，被攻击者暴力破解，进入到数据库拿到敏感信息。

## 防御方法

 * 不要在错误页面中泄露敏感信息，如系统详细信息、会话标识符、用户账号信息、系统物理路径、数据库路径、SQL 语句等，正确配置错误回显界面。
 * 建议删除 JavaScript 的注释代码，避免注释代码中存在遗留的测试账号信息、敏感接口地址、以及第三方服务的 access_key 等敏感信息造成泄露。
 * 避免在前端代码中存放敏感信息，如硬编码加密秘钥、Hidden 字段存放管理员账号密码等。
 * 禁止使用GET 方法传递敏感参数（会话标识、身份证号等），因为GET方法会将数据显示在URL中，传输过程中所有的代理及缓存服务器都可以直接获取用户数据。或者在传输过程中经过脱敏处理。为所有敏感信息采用加密传输，并且确保加密协议为安全版本。
 * 不要在日志中保存敏感信息，如会话ID、用户账号信息等。
 * 密码类数据信息必须采用SHA-256、SM3、MD5+Salt 的方式进行存储。
 * 需要逆向的敏感信息（如身份证号、银行卡号等）在存储时建议使用高强度的加密算法（如 AES-128、SM4）进行保护。
 * 禁止带有敏感数据的 Web 页面缓存。

开发层面能做的事情为：

1）对敏感数据进行加密存放，比如用户的手机号、邮箱、地址存储到数据库均采用AES-128、SM4这类可逆加密；对于用户的密码则采用SHA-256、SM3摘要算法；对于附件采用SHA-256、SM3进行签名认证。平台提供了完整的加解密API方案，详见CTP技术平台>加密解密相关内容。

//fileManager加密及验证签名示例
//致远V8.1之后提供了多种加密算法选择（国际标准SHA-256和AES-128、国标标准SM3和SM4、外接加密机），具体选用什么通过系统管理员配置完成
if (Strings.equals(Boolean.TRUE.toString(), isEncrypt)) {
    //获取加密coder工厂，工厂类会根据系统管理员配置选择对应算法
    EncryptCoderFactory coderFactory = EncryptCoderFactory.getInstance();
    //传入加密操作ENCRYPT_ATTACHMENT(文件)
    EncryptCoder encryptCoder = coderFactory.getByEncryptActionEnum(EncryptActionEnum.ENCRYPT_ATTACHMENT);
    //调用encrypt方法加密数据
    fileBytes = encryptCoder.encrypt(fileBytes);
    //签名依赖系统配置
    if (EncryptCoderFactory.enableSignature()) {
        //生成签名信息
        EncryptCoder signatureCoder = coderFactory.getByEncryptActionEnum(EncryptActionEnum.SIGNATURE_DATA);
        signature = signatureCoder.signature(fileBytes);
    }
}


对于特殊需求场景，你也可以直接通过枚举选择对应加密算法加密：

// 使用系统内置SM3加密，其它加密算法参考EncryptAlgorithmEnum枚举即可，起始于V8.1版本
EncryptAlgorithmEnum.SYS_SM3.getEncryptCoder().encrypt(data);


2）不要将数据SQL错误返回给前端，虽然看上去给开发省了很多排查问题的时间，但实际这是严重的安全漏洞，近期已经有多家客户上报客户BUG：

public void result(HttpServletRequest request,HttpServletResponse response) throws IOException {
  try {
   taskManager.countChildTaskInfo(taskId);
  } catch (BusinessException e) {
   // Bad code：不要把SQL异常输出到前端，正确的做法是log.error("",e)记录异常到日志文件中
   response.getWriter().write("出现SQL异常，SQL为："+e.getLocalizedMessage());
  }
 }


3）页面注释问题：Javascript注释、HTML注释在前端都可以通过“查看源代码”被发现，而JSP页面的JSP注释不会显示在前端页面。我们允许添加注释，但请务必保障注释不要泄露重要信息！

<body>
<!-- 这段HTML注释会被调试源代码扫描出来 -->
<%-- 这段JSP注释，页面调试时不会被扫描出来 --%>
<input name="">
</body>


4）严禁将敏感信息输出在Log日志：

// Bad Code：严禁将用户机密信息输出到日志
log.info("当前用户密码:"+AppContext.getCurrentUser().getPassword());
log.info("当前用户手机号:"+xxx.getPhone());
log.info("当前用户邮箱:"+xxx.getEmail());


5）严禁将所有信息输出在控制台：

try {
	insertLog4Account(user, user.getLoginAccount(), actionId, params);
} catch (Exception e) {
	// Bad Code:异常会被输出在控制台，并且无法追踪是什么类输出的
	e.printStackTrace();
	// Bad Code:这样的写法同样会将日志输出在控制台，这是不允许的
	System.out.println(e);
	// Nice Code:将日志放入log4j管理是正确的处理方式
	log.error("", e);
}


7）敏感信息放到header、body中，并以HTTPS形式发送Request，以提升URL安全性。


## 四、XML外部实体(XXE)

XXE(XML External Entity)指的是XML外部实体注入，XML用于标识电子文件使其具有结构性的标识语言，可以用来标记数据、定义数据类型，是一种允许用户对自己的标记语言进行定义的源语言。XML文档结构包括XML声名、DTD文档类型定义、文档元素。

## 攻击方法

如果攻击者可以上传XML文档或者在XML文档中添加恶意内容，通过易受攻击的代码、依赖项或集成，他们就能够攻击含有缺陷的XML处理器。XXE缺陷可用于提取数据、执行远程服务器请求、扫描内部系统、执行拒绝服务攻击和其他攻击。

## 防御方法

1）尽可能使用简单的数据格式（如JSON）替代XML，避免对敏感数据进行序列化。

2）过滤用户提交的XML数据，防止出现非法内容。平台提供了标准的工具类实现XXE防护，我们要求所有XML解析均使用XXEUtil进行一次解析，默认推荐使用Dom4j作为XML的解析器：

String xmlStr = xmlParam;
// 正确的解析XML写法
org.dom4j.Document doc=com.seeyon.ctp.util.XXEUtil.safeParseText(xmlStr);
org.dom4j.Element root=doc.getRootElement();


> 注意平台禁止使用XStream框架进行XML与POJO互转，XStream曾爆出多处高危漏洞。


## 五、失效的访问控制

失效的访问控制，也叫越权，指的是在未对通过身份验证的用户，实施恰当的访问控制。攻击者可以利用这一漏洞，访问未经授权的功能或数据。比如，访问其他用户的账户、查看敏感文件、修改其他用户的数据，更改访问权限等等，都属于失效的访问控制造成的后果。

## 攻击和防御方法

1）最常见的是水平越权和垂直越权。比如URL?method=saveUser这个URL请求原本设计只有管理员能使用，但开发人员忘记对这个URL进行权限校验，普通用户则可以复制这个URL，模拟对应参数进行操作。

平台提供了CheckRoleAccess注解、编码级权限控制、DigestURL等方案来进行权限控制，开发过程中需要根据不同场景实现对应权限控制。更多信息详见CTP技术平台>安全访问控制相关内容。

/**
  *  协同模版首页访问页面：通过注解控制权限
  */
 @CheckRoleAccess(resourceCode = "F01_colltemplate",roleTypes = { Role_NAME.TtempletManager})
 public ModelAndView indexFrame(HttpServletRequest request,HttpServletResponse response) throws Exception {
     request.setAttribute("isAccountAdmin", collaborationTemplateManager.isAccountAdmin());
  return new ModelAndView("common/template/indexFrame");
 }


2）免登录URL：通常管理系统都需要登录之后才能使用，带登录身份才能保障系统安全，但某些页面决定了无需登录也可以请求，比如登录、找回密码，这些请求就是免登录URL。

首先，所有免登录URL都是有风险的，因为服务一旦部署到互联网，免登录URL就有可能受到第三方攻击，所以平台要求所有二次开发以及新功能都不允许新增免登录URL。

3）路径遍历攻击是极其危险的攻击方式：攻击者通过URL./ …/这种路径遍历方式进行攻击，等于原本访问的是A目录，通过路径遍历攻击者能访问A的上一层别的目录。

场景一：“省事”的MVC跳板。

下面是一个Controller，开发提供了一个万能方法：前端传入页面名称，后端通过此跳板自动重定向到对应页面。

public class DoEverythingController extends BaseController {
    public ModelAndView toAnyWhere(HttpServletRequest httpRequest, HttpServletResponse httpResponse){
        String jspName = httpRequest.getParameter("jspName");
        ModelAndView mav = new ModelAndView("apps/jsp/task/"+jspName);
        return mav;
    }
}


看起来，开发的实现很美好，像如下的请求都能被重定向到正确的位置：

doEverythingController.do?mehotd=toAnyWhere&jspName=page1=>apps/jsp/task/page1.jsp
doEverythingController.do?mehotd=toAnyWhere&jspName=page2=>apps/jsp/task/page2.jsp
doEverythingController.do?mehotd=toAnyWhere&jspName=page3=>apps/jsp/task/page3.jsp


但开发是否想过如果有人不按常规出牌会怎么样？下面这种请求就出现了“失效的访问控制”，攻击者通过此请求访问到了别的目录JSP！

doEverythingController.do?mehotd=toAnyWhere&jspName=../system/monitor=>apps/jsp/system/monitor.jsp


解决方法是：建立白名单，只有列表中的页面才允许访问：

public class DoEverythingController extends BaseController {

    String[] whiteList = new String[]{"page1","page2","page3"};

    public ModelAndView toAnyWhere(HttpServletRequest httpRequest, HttpServletResponse httpResponse){
        String jspName = httpRequest.getParameter("jspName");
        if(!ArrayUtils.contains(whiteList,jspName)){
            return null;
        }
        ModelAndView mav = new ModelAndView("apps/jsp/task/"+jspName);
        return mav;
    }
}


场景二：任意文件下载。

如下代码是一个文件下载的实现，开发人员的初衷是：前端传给我文件名，我再根据文件名去下载特定目录下的指定文件。

public class DownloadController extends BaseController {

    public ModelAndView download(HttpServletRequest httpRequest, HttpServletResponse httpResponse){
        String fileName = httpRequest.getParameter("fileName");
        String parentFile = SystemEnvironment.getBaseFolder() + File.separator + "upload";
        File targetFile = new File(parentFile + File.separator + fileName);
        return downloadFile(targetFile);
    }

}


看起来，开发的实现很美好，像如下的请求都能按预期正常下载：

downloadController.do?method=download&fileName=zhixin.exe=>对应base/upload/zhixin.exe
downloadController.do?method=download&fileName=office/iweboffice.zip=>对应base/upload/office/iweboffice.zip


但开发是否想过如果有人不按常规出牌会怎么样？下面这种请求就出现了“失效的访问控制”，攻击者通过此请求能下载任意目录的文件！

任意文件下载是高危漏洞，攻击者如入无人之境，可以遍历下载服务器所有资料。

downloadController.do?method=download&fileName=../conf/datasourceCtp.properties=>对应base/conf/datasourceCtp.properties
downloadController.do?method=download&fileName=~/xxx=>Linux系统对应root或home根目录下的文件


解决方法为两种：

 * 第一种：判断下载文件路径是否在指定父目录下
 * 第二种：禁用前端动态传入文件名的下载方式，该为根据文件ID下载

public class DownloadController extends BaseController {

    public ModelAndView download(HttpServletRequest httpRequest, HttpServletResponse httpResponse){
        String fileName = httpRequest.getParameter("fileName");
        String parentFile = SystemEnvironment.getBaseFolder() + File.separator + "upload";
        File targetFile = new File(parentFile + File.separator + fileName);
        // 第一种：核心判断
        if(!FileUtil.inDirectory(targetFile, new File(parentFile))) {
            // 如果targetFile绝对路径不在parentFile父目录下则不允许下载
            return null;
        }
        return downloadFile(targetFile);
    }
    
}


public class DownloadController extends BaseController {
    public ModelAndView download(HttpServletRequest httpRequest, HttpServletResponse httpResponse){
        // 第二种：不信任前端的文件名，用UUID的fileID替代，从数据库查找映射文件
        String fileId = httpRequest.getParameter("fileId");
        String parentFile = SystemEnvironment.getBaseFolder() + File.separator + "upload";
        File targetFile = findFileById(fileId);
        return downloadFile(targetFile);
    }
}



## 六、安全配置错误

安全配置错误是最常见的安全问题，这通常是由于不安全的默认配置、不完整的临时配置、开源云 存储、错误的HTTP 标头配置以及包含敏感信息的详细错误信息所造成的。因此，我们不仅需要对所 有的操作系统、框架、库和应用程序进行安全配置，而且必须及时修补和升级它们。

通常，攻击者能够通过未修复的漏洞、访问默认账户、不再使用的页面、未受保护的文件和目录等来取得对系统的未授权的访问或了解。

## 攻击方法

安全配置错误可以发生在一个应用程序堆栈的任何层 面，包括网络服务、平台、Web服务器、应用服务器、数据库、框架、自定义代码和预安装的虚拟机、容器 和存储。自动扫描器可用于检测错误的安全配置、默认帐户的使用或配置、不必要的服务、遗留选项等。

比如，客户所使用的服务器操作系统有高危漏洞并且对外暴露了大量端口号，攻击者可以利用指定端口利用操作系统高危漏洞接管服务器，随后进行非法行动。

同样，系统中使用的一些框架被爆有高危漏洞（如Log4j漏洞、Struts漏洞），客户未及时修复，攻击者可以利用这些框架进行攻击。

## 防御方法

防御方法大多与开发过程代码无关，更多是系统级、架构级、运维级的安全升级处理方案：

 * 保证所有组件都是最新版本，并具有适当的安全配置，包括删除不需要的配置和文件夹，关闭或屏蔽不必要的端口，更改默认口令。如 fastjson、jackson 升级至最新安全版本。
 * 对应用系统所在服务器，所使用的框架和第三方库进行安全配置。如 Spring BootActuator 配置不当导致的高危漏洞，Tomcat AJP 文件包含漏洞等。
 * 验证应用程序资源是否被托管，例如 javascript 库、css 样式表、Web 字体由应用程序托管，而不是依赖于 CDN 或外部提供者。
 * 删除 web 目录下存在敏感信息的备份文件、测试文件、临时文件、旧版本文件等。
 * 产品不能运行在开发和 Debug 模式。
 * 当前在用的操作系统没有已知的漏洞。
 * 禁止启动不用的服务，例如，FTP、Telnet、SMTP 等。
 * 启动应用程序的系统用户必须是专用的、没有系统级别特权的用户和组。
 * 在部署之前，删除没有用的功能和测试代码。


## 七、跨站脚本攻击（XSS）

xss攻击全称为跨站脚本攻击，当应用程序的新网页中包含不受信任的、未经恰当验证或转义的数据时，或者使用可以创建HTML或JavaScript 的浏览器API 更新现有的网页时，就会出现XSS 缺陷。XSS 让攻击者能够在受害者的浏览器中执行脚本，并劫持用户会话、破坏网站或将用户重定向到恶意站点。

危害：攻击者在受害者浏览器中执行脚本以劫持用户会话，插入恶意内容，重定向用户，使用恶意软件劫持用户浏览器等。

种类：存储型，反射型，DOM型

如何防范：

 * 验证输入：产品层面控制文本框的特殊字符比如<>这种字符禁止输入
 * 编码输出（用来确保输入的字符被视为数据，而不是作为html被浏览器所解析）

## 防御方法

1）JSP中少用或者不用EL表达式，这样能极大减少XSS攻击。比如URL中的参数变量，不要使用EL表达式来获取，而是通过javascript解析参数变量：

<script text="text/javascript">
  // 格式如下的请求不要用EL表达式获取参数 xx.do?method=xx&id=xx&name=xx&other=xx
  var id = "${param.id}";  // Bad Code 可能存在反射型注入
  var name = "{param.name}"; // Bad Code 可能存在反射型注入

  var queryParams = getQueryParams(); // Nice Code物理解析参数，防止XSS攻击
  var id = queryParams.id;
  var name = queryParams.name;
</script>
<script text="text/javascript">
/**
 * 获取url后边的参数实现原理 注：此方法平台已经封装好，业务组调用即可
 * @returns
 */
function getQueryParams(){
 var search = location.search;
    var param = {};
    if (search.length > 0) {
        var strs = search.split("?")[1].split("&");
        for (var i = 0; i < strs.length; i++) {
         var con = strs[i].split("=");
            param[con[0]] = decodeURIComponent(con[1]);
        }
    }
 return param;
}
</script>


后端MVC框架Controller层只做路径跳转，ModelAndView中不携带任何参数。

// 推荐：Controller只做路由跳转，在前端JSP页面通过AJAX获取数据能极大避免XSS攻击
public ModelAndView agendaList(HttpServletRequest httpRequest, HttpServletResponse httpResponse){
	ModelAndView modelAndView = new ModelAndView("apps/leaderagenda/agendaList");
	return modelAndView;
}
// 不推荐：mav携带Object给前端
public ModelAndView agendaList(HttpServletRequest httpRequest, HttpServletResponse httpResponse){
	ModelAndView modelAndView = new ModelAndView("apps/leaderagenda/agendaList");
	// 不推荐携带参数变量
	modelAndView.addObject("userName",AppContext.currentUserName());
	modelAndView.addObject("accountName",AppContext.currentAccountName());
	return modelAndView;
}


<!-- 接上面代码示例，如果前端JSP通过EL表达式接受ModelAndView参数，恰巧userName有特殊字符就会造成存储型XSS攻击 -->
<input type="text" value = "${userName}">
<input type="text" value = "${accountName}";


2）历史代码，若JSP的script标签块内已经有EL表达式且存在XSS攻击，则需要使用平台的${ctp:escapeJavascript(x)}标签进行转换：

<!-- JSP脚本区域使用ctp:escapeJavascript，如果是老代码，还没有ctp标签，需要使用v3x:escapeJavascript实现 -->
<script  type="text/javascript">
var _resourceCode = "${ctp:escapeJavascript(param._resourceCode)}";
</script>


历史代码，若JSP中html dom value attribute元素存在EL表达式且存在XSS攻击，需要使用${fn:escapeXml(x)}进行转换：

<!-- dom中需要使用fn:escapeXml -->
<input type="hidden" id="app" name="app" value="${fn:escapeXml(param.app)}">


历史代码，若JSP中DOM标签块内存在EL表达式且存在XSS攻击，需要使用${ctp:toHTML(x)}进行转换：

<!-- 如果是老代码，还没有ctp标签，则需要改为${v3x:toHtml(x)} -->
<tr>
<td>${ctp:toHTML(param._resourceCode)}</td>
</tr>
<!-- 如下c:out标签等同上面的写法 -->
<tr>
<td><c:out value="${username}" escapeXml="true"></c:out></td>
</tr>


3）如无必要不要在后端代码进行转换：这些数据在后端本身是无害的，只是在前端渲染才有害，而且渲染在script区、dom属性值区、dom内容区的XSS防护方法是不同的，后端一个参数被用在多处则无法面面俱到。同时如果这个后端代码只是被用着远程接口调用，通过escape会将本应正确的数据转换错误，这是不合理的。

如果当前代码耦合过于严重，无法在前端处理，则后端转换是最后的策略，后端转换也需要根据实际情况判定到底是基于Javascript转换还是html转换：

org.springframework.web.util.JavaScriptUtils.javaScriptEscape(xssStr);
org.springframework.web.util.HtmlUtils.htmlEscape(xssStr);


4）不要将后端异常抛出到前台页面，如果前端没有做好防护，极易引发XSS攻击。

如下是真实攻击案例：攻击者拦截了我们的URL请求，原本memberID参数应该是一个标准数字类型，但是攻击者将其篡改为XSS攻击脚本，最后异常被返回到前端页面，前端未及时防护导致XSS攻击生效。

// request URL: xxx?memberId=<scirpt>alert(1)</scirpt>
try {
 Long memberId = Long.valueOf(request.getParameter("memberId"));
} catch (Exception e) {
 // 前端将输出：For input string: "For input string: "<scirpt>alert(1)</scirpt>""
 response.getWriter().write(e.getLocalizedMessage()); // Bad code
 response.getWriter().write("数据解析出现异常！"); // Nice code
 logger.error("",e); // Nice code
}


5）对于Html纯前端或去EL表达式的JSP前端代码发生XSS几率会小很多，但也不是没有。

在编码过程，养成良好的习惯，保障纯前端渲染的过程：

 1. 浏览器先加载一个静态 HTML，此 HTML 中不包含任何跟业务相关的数据。
 2. 然后浏览器执行 HTML 中的 JavaScript。
 3. JavaScript 通过 Ajax 加载业务数据，调用 DOM API 更新到页面上。

在纯前端渲染中，我们会明确的告诉浏览器：下面要设置的内容是文本（.innerText），还是属性（.setAttribute），还是样式（.style）等等。浏览器不会被轻易的被欺骗，执行预期外的代码了。

但纯前端渲染还需注意避免 DOM 型 XSS 漏洞（例如 onload 事件和 href 中的 javascript:xxx 等，请参考下文”预防 DOM 型 XSS 攻击“部分）。在很多内部、管理系统中，采用纯前端渲染是非常合适的。

DOM 型 XSS 攻击，实际上就是网站前端 JavaScript 代码本身不够严谨，把不可信的数据当作代码执行了。

在使用 .innerHTML、.outerHTML、document.write() 时要特别小心，不要把不可信的数据作为 HTML 插到页面上，而应尽量使用 .textContent、.setAttribute() 等。

如果用 Vue/React 技术栈，并且不使用 v-html/dangerouslySetInnerHTML 功能，就在前端 render 阶段避免 innerHTML、outerHTML 的 XSS 隐患。

DOM 中的内联事件监听器，如 location、onclick、onerror、onload、onmouseover 等，<a> 标签的 href 属性，JavaScript 的 eval()、setTimeout()、setInterval() 等，都能把字符串作为代码运行。如果不可信的数据拼接到字符串中传递给这些 API，很容易产生安全隐患，请务必避免。

> 作者：美团技术团队 链接：https://www.jianshu.com/p/2d9da4490ae1 来源：简书 著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。


## 八、使用含有已知漏洞的组件

组件（例如：库、框架和其他软件模块）拥有和应用程序相同的权限。如果应用程序中含有已知漏洞的组件被攻击者利用，可能会造成严重的数据丢失或服务器接管。同时，使用含有已知漏洞的组件的应用程序和API可能会破坏应用程序防御、造成各种攻击并产生严重影响。

## 防御方法

1.识别正在使用的组件和版本，包括所有的依赖

2.更新组件或引用的库文件到最新

3.建立安全策略来管理组件的使用

对于标准产品，开发规范中有明令禁止使用的组件库：XStream和Fastjson（两个框架历史上出现过多次高危漏洞，使用这类框架容易被白帽子盯上），（为避免不必要的麻烦）取而代之的是XXEUti+Dom4j和平台的JSONUtil。


## 九、不足的日志记录和监控

这个和等保有一定的关系，不足的日志记录和监控，以及事件响应缺失或无效的集成，使攻击者能够进一步攻击系统、保持持续性或转向更多系统，以及篡改、提取或销毁数据。大多数缺陷研究显示，缺陷被检测出的时间超过200天，且通常通过外部检测方检测，而不是通过内部流程或监控检测。

## 防御方法

这类问题的防护更多是基于国家等保分保标准进行相应的产品合规性开发，标准产品尽量按照三级标准进行了相应的日志记录，具体见标准产品发布文档--安全合规专题。


## 十、不安全的反序列化

不安全的反序列化会导致远程代码执行。即使反序列化缺陷不会导致远程代码执行，攻击者也可以利用它们来执行攻击，包括：重播攻击、注入攻击和特权升级攻击。

序列化就是将对象转换成字节流,可以更方便的将数据保存到本地文件

反序列化就是将字节流还原成对象，Java中提供了两个接口来支持序列化,ObjectIutputStream()和ObjectOutputStream()

序列化相对安全,问题出在反序列化的过程

原理：攻击者通过构造恶意的参数,使数据在在反序列化后生成特殊的对象类型,从而执行恶意代码。问题的根源在于,反序列化时没有对生成的对象类型做限制

防御：反序列化漏洞的防御主要以白名单为主,限制对象的类型,从而减小影响。


## 十一、跨站请求伪造CSRF

CSRF（Cross-site request forgery），中文名称跨站请求伪造，也被称为：one click attack/session riding，缩写为：CSRF/XSRF。

你这可以这么理解CSRF攻击：攻击者盗用了你的身份，以你的名义发送恶意请求。CSRF能够做的事情包括：以你名义发送邮件，发消息，盗取你的账号，甚至于购买商品，虚拟货币转账等等，从而造成个人隐私泄露以及财产安全问题。

CSRF利用的是同一浏览器保留用户状态的特性，在主系统保持登录状态的前提下，使用同一浏览器从危险网站点击链接执行主系统的请求，最终形成CSRF跨站请求伪造。

## 攻击方法

通俗说，同一浏览器有保持会话的能力，我们在日常工作中应该体会到了：

1、先正常访问协同系统，正常输入帐号密码登录到系统个人空间

2、打开一个待办协同，复制一下浏览器上待办协同的URL地址

3、关闭当前待办协同的窗口，不关闭个人空间主浏览器，再新建一个标签页（Ctrl+T）打开一个空白页，输入第2步复制的待办协同URL地址回车

4、按照第3步操作之后，你会发现一个空白页签，输入协同内的地址也能正常打开页面

CSRF就是基于上面浏览器原理实现的攻击，攻击场景为：

1、原本客户有一个正常的办公主系统，网站地址为：xxx.seeyon.com，首先受害者正常登录此地址进入系统。

2、在这个正常的办公系统有一个URL是用于给系统内人员点赞，点赞高的将会获得公司的奖励，链接地址为，xxx.seeyon.com/xxx/likes，正常登录办公主系统即可给人员点赞。

3、别有用心之人如果想无声无息获得高赞，可以利用CSRF漏洞：攻击者可以开发另一个危险的网站，比如aaa.com，该网站首页有一个按钮名叫“点击我获得1万元”，而这个按钮的链接实际是：xxx.seeyon.com/xxx/likes

4、攻击者只要利用受害者先保持主系统在线，然后引导受害者在同一浏览器访问危险网站aaa.com去点击“点击我获得1万元”按钮即可立刻获得主系统的点赞。

## 防御方法

防护CSRF的攻击就是要让想办法让“危险网站”直接请求主系统URL失效。

V5标准产品提供了在URL后添加CSRFTOKEN的方案来防护CSRF攻击，每次登录之后，用户的CSRFTOKEN都不一样，这样就能防护住危险网站的攻击（危险网站不可能随意获取到当前登录用户的CSRFTOKEN）。

<%-- JSP页面，URL后面添加${ctp:csrfSuffix()}做标记 --%>
<form action="${path}/meetingResource.do?method=execAdd${ctp:csrfSuffix()}">
</form>


// javascript在URL最后追加CsrfGuard.getUrlSurffix()
var v3x = new V3X();
function openColInfo(obj) {
 var url = _ctxPath + "/coll.do?method=summary&type=" + obj + "&id=123" + CsrfGuard.getUrlSurffix();
 v3x.openWindow({
  url : url,
  workSpace : 'yes',
  FullScrean : 'yes',
  dialogType : 'open',
  closePrevious : "no"
 });
}


AJAX请求，增加beforeSend: CsrfGuard.beforeAjaxSend，例如：

$.ajax({
    type: "POST",
    beforeSend: CsrfGuard.beforeAjaxSend, 
    url: encodeURI("/seeyon/organization/orgIndexController.do?method=saveRecentData4OrgIndex&rData=" + _value)
});

 $('#attchmentForm').ajaxSubmit({
    url : genericURL + "?method=updateAttachment&edocSummaryId="+summaryId+"&affairId="+affair_id,
    type : 'POST',
    beforeSend: CsrfGuard.beforeAjaxSend, 
    success : function(data) {
    }
});


Java后台生成URL时也可以在URL后面追加CSRF标记：

// 返回"&CSRFTOKEN={currentTokenValue}"
com.seeyon.ctp.common.taglibs.functions.Functions.csrfSuffix()


由于CSRF攻击方式复杂、并且一般请求无害，只有涉及到金额、利益相关的行为才需要重视，所以CSRF漏洞监测常用于金融行业。CSRF毕竟要多一层拦截器进行鉴权，性能肯定比不带CSRFTOKEN好，所以我们默认只对核心应用进行CSRF控制。如有特殊URL需要进行控制，需要在下面配置文件中注册。

V5平台的CSRFTOKEN方案基于Owasp封装，WEB-INF/classes/Owasp.CsrfGuard.overlay.properties中配置了需要CSRF控制的URL：

org.owasp.csrfguard.protected.C1    =   ajax.do
org.owasp.csrfguard.protected.C2    =   content/content.do
org.owasp.csrfguard.protected.C3    =   collaboration/collaboration.do?method=saveDraft
## 忽略若干代码 ......


CSRF的拦截器位于：com.seeyon.ctp.common.web.filter.CTPCsrfGuardFilter，过滤器进行了相关防护。


## 十二、服务端请求伪造（SSRF）

SSRF(Server-Side Request Forgery:服务器端请求伪造)，形成的原因大都是由于服务端提供了从其他服务器应用获取数据的功能,但又没有对目标地址做严格过滤与限制，导致攻击者可以传入任意的地址来让后端服务器对其发起请求,并返回对该目标地址请求的数据。ssrf是利用存在缺陷的web应用作为代理攻击远程和本地的服务器。

## 攻击方法

服务端提供了从其他服务器应用获取数据的功能且没有对目标地址做过滤与限制，比如从指定URL地址获取网页文本内容，加载指定地址的图片，下载等等。

数据流：攻击者->服务器->目标地址

从服务端获取外部资源的请求，如果该请求参数可控则有可能造成SSRF攻击。比如请求其他服务器的资源测试连接功能，如果没对ip、端口、响应信息做处理则就会出现SSRF攻击，还包括可控的数据库连接测试、加载其他网站图片等等。

通过SSRF漏洞，可能造成的影响包括但不限于：端口信息探测、内网Web应用指纹识别、读取本地文件、攻击内网web应用、攻击运行在内网或本地的应用程序。

## 防御方法

SSRF的防御更多可以从防火墙、网关等层面进行运维级隔离，与代码开发关系相对较小：

1、限制内网IP

2、限制请求高危端口，如：20,21,22,53,80,139,443,445,1433,1521,3306,3389,5432,6379,7001,8080-8090

3、禁用不需要的协议，如：file:///,gopher://,ftpftp://

4、统一回显，过滤详细报错信息

编撰人：admin、het


快速跳转



 * 安全开发规范
   * Web安全漏洞和防御
     * 一、SQL注入
       * 攻击方法
       * 防御方法
     * 二、失效的身份认证
       * 攻击和防御方法
     * 三、敏感数据泄露
       * 攻击方法
       * 防御方法
     * 四、XML外部实体(XXE)
       * 攻击方法
       * 防御方法
     * 五、失效的访问控制
       * 攻击和防御方法
     * 六、安全配置错误
       * 攻击方法
       * 防御方法
     * 七、跨站脚本攻击（XSS）
       * 防御方法
     * 八、使用含有已知漏洞的组件
       * 防御方法
     * 九、不足的日志记录和监控
       * 防御方法
     * 十、不安全的反序列化
     * 十一、跨站请求伪造CSRF
       * 攻击方法
       * 防御方法
     * 十二、服务端请求伪造（SSRF）
       * 攻击方法
       * 防御方法



分享链接分享链接

## 26. 数据字典

> 原始路径：`/38/146.html`  
> 相对路径：`38/146.md`

## 数据字典

1、如果需要通过SQL对数据库增删改操作：我们不建议您直接对数据库进行操作，实体之间的关系非常复杂，请通过接口调用。

2、如果客开需要向标准产品表中新增字段：我们不建议您直接在表中新增字段，而是应该另外加一张非标准产品的表维护。

3、如果需要查看表字段注释：出于相关政策，请客户经理联系公司商务申请数据字典，研发无法提供数据字典。

编撰人：het




快速跳转



 * 数据字典



分享链接分享链接

## 27. CTP技术平台

> 原始路径：`/39/`  
> 相对路径：`39/README.md`

子菜单名称             URL
概述                概述
后端组件              后端组件
DAO数据层开发          DAO数据层开发
SpringBean注入规则    SpringBean注入规则
Event事件监听开发       Event事件监听开发
APP-API解耦开发       APP-API解耦开发
动态接口              动态接口
缓存组件              缓存组件
国际化               国际化
定时任务              定时任务
日期和多时区            日期和多时区
HTTP304缓存         HTTP304缓存
加密解密              加密解密
LOG日志             LOG日志
产品区隔组件            产品区隔组件
安全访问控制            安全访问控制
应用配置器参数组件         应用配置器参数组件
应用锁组件             应用锁组件
系统后台菜单开发          系统后台菜单开发
系统消息组件            系统消息组件
EMail邮箱[电子邮件]组件   EMail邮箱[电子邮件]组件
PhantomJs打印组件     PhantomJs打印组件
系统登录组件            系统登录组件
Groovy语法          Groovy语法
门户组件              门户组件
单点登录(SSO)         单点登录(SSO)
编写Rest代码          编写Rest代码
免登录认证请求           免登录认证请求
appLog应用审计日志组件    appLog应用审计日志组件
对象存储扩展适配          对象存储扩展适配

分享链接分享链接

## 28. DAO数据层开发

> 原始路径：`/39/74.html`  
> 相对路径：`39/74.md`

## DAO数据层开发


## 数据层开发示例

数据层用于与数据库进行CRUD交互，本节按照一个开发示例进行演示数据层的开发模式。


## 第一步：建表

建表规范见本页面后续章节，以MySQL为例：

 * 必须定义主键，统一命名为ID，BIGINT类型，默认通过Java的UUID生成
 * 创建人、创建单位默认都指向对应表的主键，所以数据类型也是BIGINT
 * 文本内容默认使用VARCHAR，根据应用场景定义字符长度
 * 未知长度（允许用户输入大量文本）可以使用LONGTEXT，但注意SQL性能
 * 日期时间使用DATETIME，日期使用DATE
 * 数据状态（删除、未删除）一般对应0和1，使用SMALLINT即可

/*==============================================================*/
/* Table: SHOWBAR_INFO  DBType:MySQL                            */
/*==============================================================*/
CREATE TABLE SHOWBAR_INFO
(
   ID                   BIGINT NOT NULL,
   CREATE_USER_ID       BIGINT,
   ACCOUNT_ID           BIGINT,
   CREATE_TIME          DATETIME,
   UPDATE_USER_ID       BIGINT,
   UPDATE_TIME          DATETIME,
   CREATE_FROM          SMALLINT,
   STATUS               SMALLINT,
   SHOWBAR_NAME         VARCHAR(255),
   START_DATE           DATETIME,
   END_DATE             DATETIME,
   ADDRESS              VARCHAR(255),
   SUMMARY              VARCHAR(1024),
   SETTOP_TIME          DATETIME,
   VIEW_NUM             INT,
   LIKE_NUM             INT,
   IMG_NUM              INT,
   COMMENT_NUM          INT,
   COVER_PICTURE        BIGINT,
   ORDER_NUM            INT,
   LAST_IMAGE_ID        BIGINT,
   ORDER_TIME           DATETIME,
   PRIMARY KEY (ID)
);



## 第二步：新增索引

开发需要预估表的未来数据量：如果未来会超过5万条，则要提前考虑建立规范、有效的数据库索引。

由于本案例表数据不大，CREATE_USER_ID字段经常被当做SQL条件，对该字段则建立简单的索引即可

CREATE INDEX IDX_SHOW_MYCREATED ON SHOWBAR_INFO(CREATE_USER_ID);



## 第三步：定义hbm

平台使用Hibernate框架与数据库进行交互，需要定义hbm文件和与数据库字段相对应的POJO对象。代码位置如下：

com
	seeyon
		apps
			show
				po
					ShowbarInfo.java
					ShowbarInfo.hbm.xml




在com.seeyon.apps.show.po package下新增ShowbarInfo.hbm.xml文件，该文件以XML的格式定义数据库表字段与Java POJO的关系：

> 注意：只允许使用Hibernate最传统的字段映射特性，不要使用one-to-many这类多表关联特性！

<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE hibernate-mapping PUBLIC "-//Hibernate/Hibernate Mapping DTD 3.0//EN"
"http://hibernate.sourceforge.net/hibernate-mapping-3.0.dtd">

<hibernate-mapping>
    <class name="com.seeyon.apps.show.po.ShowbarInfo" table="showbar_info">
        <id name="id" type="java.lang.Long">
            <column name="ID" />
            <generator class="assigned" ></generator>
        </id>
        <property name="createUserId" type="java.lang.Long">
            <column name="CREATE_USER_ID" >
                <comment>秀吧创建人ID</comment>
            </column>
        </property>
        <property name="accountId" type="java.lang.Long">
            <column name="ACCOUNT_ID" >
                <comment>所属单位ID</comment>
            </column>
        </property>
        <property name="createTime" type="java.util.Date">
            <column name="CREATE_TIME" length="19" >
                <comment>创建时间</comment>
            </column>
        </property>
        <property name="updateUserId" type="java.lang.Long">
            <column name="UPDATE_USER_ID">
                <comment>最近修改人ID</comment>
            </column>
        </property>
        <property name="updateTime" type="java.util.Date">
            <column name="UPDATE_TIME" length="19">
                <comment>最近修改时间</comment>
            </column>
        </property>
        <property name="createFrom" type="java.lang.Integer">
            <column name="CREATE_FROM" >
                <comment>创建自（PC、M1）</comment>
            </column>
        </property>
        <property name="status" type="java.lang.Integer">
            <column name="STATUS" >
                <comment>状态标识：0删除，1正常，2系统预制秀</comment>
            </column>
        </property>
        <property name="showbarName" type="java.lang.String">
            <column name="SHOWBAR_NAME" >
                <comment>秀吧名称</comment>
            </column>
        </property>
        <property name="startDate" type="java.util.Date">
            <column name="START_DATE" length="10">
                <comment>秀吧开始时间</comment>
            </column>
        </property>
        <property name="endDate" type="java.util.Date">
            <column name="END_DATE" length="10">
                <comment>秀吧结束时间</comment>
            </column>
        </property>
        <property name="address" type="java.lang.String">
            <column name="ADDRESS">
                <comment>秀吧活动地址</comment>
            </column>
        </property>
        <property name="summary" type="java.lang.String">
            <column name="SUMMARY" length="1000">
                <comment>秀吧简介</comment>
            </column>
        </property>
        <property name="settopTime" type="java.util.Date">
            <column name="SETTOP_TIME" length="19">
                <comment>置顶时间（未置顶则为空）</comment>
            </column>
        </property>
        <property name="viewNum" type="java.lang.Integer">
            <column name="VIEW_NUM" >
                <comment>浏览次数</comment>
            </column>
        </property>
        <property name="likeNum" type="java.lang.Integer">
            <column name="LIKE_NUM" >
                <comment>点赞次数</comment>
            </column>
        </property>
        <property name="imgNum" type="java.lang.Integer">
            <column name="IMG_NUM" >
                <comment>照片总数</comment>
            </column>
        </property>
        <property name="commentNum" type="java.lang.Integer">
            <column name="COMMENT_NUM" >
                <comment>评论总数</comment>
            </column>
        </property>
        <property name="coverPicture" type="java.lang.Long">
            <column name="COVER_PICTURE" >
                <comment>封面图片ID(对应show_imgae表)</comment>
            </column>
        </property>
        <property name="orderNum" type="java.lang.Integer">
            <column name="ORDER_NUM">
                <comment>排序号</comment>
            </column>
        </property>
        <property name="lastImageId" type="java.lang.Long">
            <column name="LAST_IMAGE_ID">
                <comment>主题最新图片ID</comment>
            </column>
        </property>
        <property name="orderTime" type="java.util.Date">
            <column name="order_time" length="19" >
                <comment>主题排序时间</comment>
            </column>
        </property>
    </class>
</hibernate-mapping>


在上一步完成基础上，在同级package下新建对应POJO，继承平台的BasePO，代码如下：

public class ShowbarInfo extends BasePO{
 private static final long serialVersionUID = 2180154441235743764L;

 private Long   createUserId; //秀吧创建人ID
 private Long   accountId;  //所属单位ID
 private Date   createTime; //创建时间
 private Long   updateUserId; //最近修改人ID
 private Date   updateTime; //最近修改时间
 private Integer   createFrom; //创建自（PC、M1）
 /**
  * 0删除 状态去掉，直接物理删除
  */
 private Integer   status;  //状态标识：0删除，1正常，2系统预制秀
 private String   showbarName; //秀吧名称
 private Date   startDate;  //秀吧开始时间
 private Date   endDate;  //秀吧结束时间
 private String   address;  //秀吧活动地址
 private String   summary;  //秀吧简介
 private Date   settopTime = ShowConstants.DEFAULT_TIME; //置顶时间（未置顶则为空）
 private Integer   viewNum;  //浏览次数
 private Integer   likeNum;  //点赞次数
 private Integer   imgNum;  //照片总数
 private Integer   commentNum; //评论总数
 private Long   coverPicture; //封面图片ID(对应show_imgae表)
 private Integer   orderNum;  //序号
 private Long   lastImageId; //主题最新图片ID
 
 private Date   orderTime;  //秀吧排序时间  V5 V7.0SP1添加

 // Constructors

 /** default constructor */
 public ShowbarInfo() {
 }

getter...

setter...
}



## 第四步：DAO层接口和实现



DAO层就是建立数据库互通的代码层，代码CRUD均要求在DAO层完成，我们遵守Spring IOC容器规范，定义接口+实现的Dao层模型进行代码维护！

public interface ShowbarInfoDao {
 /**
  * <p>Description: 创建一个秀吧</p>
  * 
  * @param showbarInfo 秀吧PO
  * @throws BusinessException
  */
 public void save(ShowbarInfo showbarInfo) throws BusinessException;

 /**
  * <p>Description:更新秀吧 </p>
  * 
  * @param showbarInfoId 秀吧PO
  * @throws BusinessException
  */
 public void update(ShowbarInfo showbarInfo) throws BusinessException;

 /**
  * <b>获取秀吧操作数据</b><br>
  *
  * @param dataIds 秀吧的Id
  * @return
  * @throws BusinessException
  */
 @SuppressWarnings("rawtypes")
 public List<Map> findShowbarNums(Long[] dataIds) throws BusinessException;
}


平台提供了DBAgent和JDBCAgent的封装进行数据库操作：

 * DBAgent对应的是Hibernate标准API那一套，基于PO实体进行增删改，基于HQL进行数据查询
 * JDBCAgent对应的是Java JDBC那一套，基于JDBC SQL进行增删改查

一般简单的CUD，我们都使用DBAgent（即Hibernate）那一套实现，Hibernate在多数据库兼容上做到了尽量的简单、易用。

而一般复杂查询，尤其是多表联查，我们要求尽量使用JDBCAgent，即传统的SQL开发。在高并发下，SQL效率比HQL要高！

public class ShowbarInfoDaoImpl implements ShowbarInfoDao {

 @Override
 public void save(ShowbarInfo showbarInfo) throws BusinessException {
  DBAgent.save(showbarInfo);
 }

 @Override
 public void update(ShowbarInfo showbarInfo) throws BusinessException {
  DBAgent.update(showbarInfo);
 }

 @SuppressWarnings({ "unchecked", "rawtypes" })
 @Override
 public List<Map> findShowbarNums(Long[] dataIds) throws BusinessException {
  StringBuilder hql = new StringBuilder();
  hql.append("SELECT New Map(");
  hql.append("id as id,");
  hql.append(" viewNum  as viewNum,");
  hql.append(" likeNum  as likeNum,");
  hql.append(" imgNum   as imgNum,");
  hql.append(" commentNum  as commentNum ");
  hql.append(") FROM ");
  hql.append(ShowbarInfo.class.getCanonicalName());
  hql.append(" WHERE id in (:ids)");

  Map<String, Object> param = new HashMap<String, Object>();
  param.put("ids", dataIds);

  return DBAgent.find(hql.toString(), param);
 }
}



## 第五步：注册DAO到Spring容器

按照插件化开发规则，找到自己的插件目录，将Dao注入到spring中，示例如：src\main\webapp\WEB-INF\cfgHome\plugin\show\spring\spring-show-dao.xml

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
 <bean id="showbarInfoDao" class="com.seeyon.apps.show.dao.ShowbarInfoDaoImpl"></bean>
</beans>



## 第六步：Manager层调用

最后Dao被Manager调用，示例如下：

> 注：Dao不要被Controller调用，我们的三层依赖链是：Controller->Manager->Dao

public class ShowbarInfoManagerImpl implements ShowbarInfoManager {
 private static Log logger = CtpLogFactory.getLog(ShowbarInfoManagerImpl.class);
 private ShowbarInfoDao showbarInfoDao;

 @Override
 public void save(ShowbarInfo showbarInfo) throws BusinessException {
  // 伪代码示例：这里展示的是Manager一个方法可以调用多个Dao的方法
  // 并且如果这个manager的方法受事务管理，则如下任务Dao的增删改出现异常就会全部被回滚
  showbarInfoDao.findShowbarNums(xxx);
  showbarInfoDao.getById(xxx);
  showbarInfoDao.save(showbarInfo);
  // 伪代码示例：manager中的方法还可以嵌套调用别的manager方法
  this.update(showbarInfo);
 }
}


以上就是完整的数据库持久层开发示例，如有不清楚的地方，开发过程中，可以参考标准产品的代码。


## 数据层工具类详解


## 分页对象FlipInfo

在调用数据库封装方法前，先介绍平台提供的分页对象，这个在数据库操作中非常常见。

在开发过程中，我们可能会看到如下的代码写法，这里的FlipInfo是一个分页对象，用于告诉平台取第几页数据，并且还可以根据参数配置来确定是否执行一次count(*)求和操作，并且将结果集放入到FlipInfo的data属性中，一个对象多个能力：

public FlipInfo findResult(Map<String, Object> params) {
   FlipInfo flipInfo = new FlipInfo();
   // 无需执行count(*)返回求和数据
   flipInfo.setNeedTotal(false);
   // 一次取10条数据
   flipInfo.setSize(10);
   // 取结果中的第二页数据：即忽略前10条数据，取11~20的数据
   flipInfo.setPage(2);
   DBAgent.find("select new Org(id,title) from Org where orgname like :orgname order by id", params, flipInfo);
   return flipInfo;
  }


下面是FlipInfo分页对象的关键属性：

public class FlipInfo implements Serializable {
    private List data;   //查询结果集会放入此对象中
    private int page = 1; //分页参数：取第几页数据
    private int size = 20;//分页参数：一次取多少条数据
    private boolean needTotal = true;//求和参数，默认true，表示默认会先执行count(*)求出结果集总数，再执行select分页查询需要的结果集
    private int total = 0;//跟needTotal同生
}


最佳实践：如果你只需要分页查询出结果数据，则一定要设置flipInfo.setNeedTotal(false);这样能减少一条count(*)的SQL。

FlipInfo跟前端的Gird组件绑定较深，前端Gird表格组件的整个翻页逻辑与之一一对应，实用性很高。


## 数据操作DBAgent

DBAgent是CTP平台封装的基于Hibernate的数据库操作工具类，DBAgent功能接近于org.hibernate.Session，可以进行save、delete、update、query。DBAgent包装了具有V5特性的能力，更方便我们应用开发。

## 常用API

单条数据增删改查接口：

DBAgent.save(myPO);  //新增保存PO实体对象
DBAgent.delete(myPO); //删除PO实体对象（myPO中的主键ID不能为空）
DBAgent.update(myPO);//更新PO实体对象
DBAgent.get(MyPO.class,id);//获取单条数据：根据主键ID查询PO实体对象

/**不推荐接口调用**/
@Deprecated
DBAgent.saveOrUpdate(myPO); //从数据库判断数据是否存在，存在则更新，不存则新增，此方法不推荐，开发过程一定要分清楚：新增就调用新增方法、更新就调用更新方法
DBAgent.merge(myPO);// 同saveOrUpdate


批量数据增、删、改接口：

DBAgent.saveAllForceFlush(pos);//批量新增插入PO对象数据，每1000条自动提交到数据库
DBAgent.saveAll(pos, true);//作用同saveAllForceFlush
DBAgent.deleteAll(pos);//批量删除PO对象数据
DBAgent.updateAll(pos);//批量修改PO对象数据

/**不推荐接口调用**/
DBAgent.saveAll(pos);//批量新增插入PO对象数据，与saveAllForceFlush的差异是：只有所有数据写入到缓冲区才提交，此法数据量成千上万时易引发性能问题


另外，如果需要根据某些特定条件进行批量更新或删除操作，同样推荐通过HQL进行数据批量更新、删除，此法类似于SQL的删除和更新，效率也很高：

DBAgent.bulkUpdate("delete from Org where orgid>? and orgid<?", 200L, new Long(210));
DBAgent.bulkUpdate("update from Org set orgname=? where orgid>? and orgid<?", "测试", 210L, new Long(220));


单表查询语句，根据特定条件查询结果集可以使用Hibernate的HQL，DBAgent同样封装了相关接口。

/**单表查询推荐使用HQL语法，并且select结果要明确，不要直接select * from查询全部**/
//根据传入的HQL进行查询操作，如果返回数据量过大不允许使用
List result = DBAgent.find("select id,title from Org");
//根据传入的HQL和命名参数进行查询操作，如果返回数据量过大不允许使用
List<Map> result = DBAgent.find("select new Map(o.id as id,o.title as title) from Org o where o.orgname like :orgname", params);
//根据传入的HQL和命名参数进行翻页查询操作，需要构造FlipInfo翻页信息类
List<Org> result = DBAgent.find("select new Org(id,title) from Org where orgname like :orgname", params, flipInfo);

// 平台提供了获取结果集总数的接口，如下HQL会被平台解析转换为count语句
int count = DBAgent.count("select id,title from Org");
int count = DBAgent.count("select new Map(o.id as id) from Org o where o.orgname like :orgname", params);
// 平台同时也提供了判断是存在结果数据的接口，如下HQL会被平台解析只获取1条结果集，如果数据>=1则表示存在
boolean isExist = DBAgent.exists("select id,title from Org");
boolean isExist = DBAgent.exists("select new Map(o.id as id) from Org o where o.orgname like :orgname", params);


关于HQL中参数传递的最佳实践： 使用:var的占位符形式进行参数传递，通过Map将变量放入参数对象中即可。

/**
*本例子几乎包含了所有场景的参数传递：包括如何使用LIKE传参，如何向IN中传参，如何进行日期比较等
**/
public void find(String name, Long memberId, Date startTime, List<Long> dataId, FlipInfo flipInfo) throws BusinessException {
  String hql = "select new map(id,name,startTime) from Org where memberId = :memberId and startTime > :startTime and dataId in (:dataId) and name like :name";
  Map<String,Object> params = new HashMap<>();
  params.put("name","%" + SQLWildcardUtil.escape(name) + "%"); //注意：调用SQLWildcardUtil.escape过滤危险字符，防止SQL攻击
   params.put("memberId",memberId); // Long类型就传入Long对象
   params.put("startTime",startTime); // 日期类型就传入Date对象
   params.put("dataId",dataId); // SQL IN就传输List或Array
   DBAgent.find(hql,params,flipInfo);
}


内存分页： 此接口默认不推荐，在“情非得已”的时候使用！

原则上，我们要求通过HQL、SQL查询的数据就要进行分页，即一次只能查出xx条数据，这样才能保障性能！但是如果应用上不满足一条SQL解决问题，需要查询一批结果集进行内存运算之后再分页，则可以在最后一步调用如下方法进行分页。

DBAgent.memoryPaging(dataList, flipInfo);


## 禁忌操作

1）不推荐使用"select * from table"和"from table"的操作，要求按需获取数据！

2）多表关联不要使用HQL，需要改用SQL以保障性能

/**
1）不推荐HQL写法：
下面写法是Hibernate“引以为傲”的特性，但是这样编写会将表字段全部查询出来，如果大表会出现严重性能问题，我们需要遵循“需要什么结果就查询什么数据原则”，不要动不动就查询全部结果集
同时此法还有一个持久化缓存的问题，用此法会导致开发遇到很多不可控的坑，后面会介绍！
**/
List<Org> result = DBAgent.find("from Org");
List<Org> result = DBAgent.find("from Org where orgname like :orgname", params);
/**2）不推荐使用Hibernate完成多表关联，多表关联请使用SQL以提升性能**/
DBAgent.find("from Org o,User u where o.userId=u.id");
/**
3）同样不推荐使用Hibernate的如下封装特性，只要返回整个对象的都不再推荐
**/
//根据queryName进行查询操作，如果返回数据量过大不允许使用
DBAgent.findByNamedQuery(queryName);
//根据queryName和命名参数进行查询操作，如果返回数据量过大不允许使用
DBAgent.findByNamedQuery(queryName, params);
//根据queryName和命名参数进行翻页查询操作，需要构造FlipInfo翻页信息类
DBAgent.findByNamedQuery(queryName, params, flipInfo);
//根据queryName和ValueBean进行查询操作，Bean中的属性名将作为HQL中的命名参数，如果返回数据量过大不允许使用
DBAgent.findByNamedQueryAndValueBean(queryName, valueBean);
//根据queryName和ValueBean进行翻页查询操作，Bean中的属性名将作为HQL中的命名参数，需要构造FlipInfo翻页信息类
DBAgent.findByNamedQueryAndValueBean(queryName, valueBean, flipInfo);


3）巨坑：通过"from table"或DBAnget.get()获取的对象不要进行set操作，此举会导致Hibernate自动执行update更新：

public List<Org> find(Map params){
  String hql = "from Org where xxx";
  List<Org> result = DBAgent.find(hql,params);
   for (Org org: result) {
   // Bad code：执行from table的hql结果集会被Hibernate缓存，如果使用set导致属性变化，Hibernate会隐式执行update更新数据库
   org.setName("newName");
  org.setStartTime(new Date());
   // 上面代码会导致Hibernate隐式执行：update Org set name='newName',startTime=new date()
   }
  return result;
 }


public Org get(Long id){
  Org org = DBAgent.get(id,Org.class);
   // Bad code：使用get获取的结果会被Hibernate缓存，如果使用set导致属性变化，Hibernate会隐式执行update更新数据库
   org.setName("newName");
  org.setStartTime(new Date());
   // 上面代码会导致Hibernate隐式执行：update Org set name='newName',startTime=new date()
   return org;
 }


4）判断是否存在结果数据不允许使用DBAgent.find(hql).size()的形式，要求使用DBAgent.exists(hql)方法：

public boolean isExsist(){
  // Bad code：判断数据是否存在不应该通过查询出结果集结果再通过size()大小去判断
  return DBAgent.find("select id from Org").size() > 0 ? true : false;
  // Nice code：使用平台封装的exists方法是最高效的写法，此法是取第1页第1条数据出来，极大提升性能
  return DBAgent.exists("select id from Org");
 }



## 原生SQL-JDBCAgent

前面DBAgent是CTP平台封装，提供给开发利用Hibernate能力执行数据库操作的工具类。

而如果开发需要使用标准的JDBC SQL开发则需要另一个工具类：JDBCAgent是CTP平台封装，提供给开发执行SQL使用的工具类。

一个规范的JDBCAgent写法示例如下，设计创建JDBCAgent、调用Agent方法、关闭JDBCAgent这几步操作：

// 创建JDBCAgent
        JDBCAgent agent = new JDBCAgent();
        try {
            // 调用相关JDBC接口执行SQL
            agent.execute("update org_table set title = xxx");
        } catch (Exception e) {
            // 处理异常
            logger.error("",e);
        } finally {
            // 必做：关闭JDBCAgent连接
            agent.close();
        }


## 常用API

创建JDBCAgent实例： 前面示例可以看到通过new JDBCAgent来创建对象实例。

自V7.1SP1开始，平台提供了多种构造函数创建JDBCAgent实例不同构造函数代表不同意思。

/**
     * 使用Spring管理的数据库连接构造JDBCAgent
     * --------------------------------------------------------------
     * @deprecated 自7.1SP1版本，推荐使用以下方法：
     * @see #JDBCAgent(boolean, boolean)
     * --------------------------------------------------------------
     */
    @Deprecated
    public JDBCAgent() {
        this(false);
    }

    /**
     * 传入true时将使用原始的数据库连接构造JDBCAgent，false则使用Spring管理的数据库连接
     * @param useNative 是否使用原始的数据库连接构造JDBCAgent
     * --------------------------------------------------------------
     * @deprecated 自7.1SP1版本，推荐使用以下方法：
     * @see #JDBCAgent(boolean, boolean)
     * --------------------------------------------------------------
     */
    @Deprecated
    public JDBCAgent(boolean useNative) {
        this(useNative, false);
    }

    /**
     * 获取JDBCAgent实例
     * @param useNative 传入true时将使用原始的数据库连接构造JDBCAgent，false则使用Spring管理的数据库连接
     * @param autoClose 传入true则由平台托管关闭连接，传入false则必须由开发通过.close()显性关闭连接
     */
    public JDBCAgent(boolean useNative, boolean autoClose)


对于不熟悉CTP特性的开发，推荐如下两种写法，必然不会有问题：

// 推荐第一种：创建JDBCAgent
        JDBCAgent agent = new JDBCAgent();
        try {
            // 调用相关JDBC接口执行SQL
            agent.execute("update org_table set title = xxx");
        } catch (Exception e) {
            // 处理异常
            logger.error("",e);
        } finally {
            // 必做：关闭JDBCAgent连接，不关闭会造成连接池泄漏
            agent.close();
        }

        // 推荐第二种：创建JDBCAgent(false:默认使用Spring的连接，false:由开发显性调用.close()关闭连接)
        JDBCAgent agent1 = new JDBCAgent(false,false);
        try {
            // 调用相关JDBC接口执行SQL
            agent1.execute("update org_table set title = xxx");
        } catch (Exception e) {
            // 处理异常
            logger.error("",e);
        } finally {
            // 必做：关闭JDBCAgent连接，不关闭会造成连接池泄漏
            agent1.close();
        }


调用JDBCAgent常用方法：

> 特别注意：jdbcAgent.resultSetToList()和jdbcAgent.findByPaging()最终返回的结果集参数key都是小写，那是底层做了转换！而如果jdbcAgent.resultSetToList(false)则会返回你设置的参数格式，但这个有坑：Oracle、达梦默认返回的是强制全部大写，所以不建议使用jdbcAgent.resultSetToList(false)。

// 直接执行SQL
            int resultCount = jdbcAgent.execute("update org_table set title = xxx");
            // 带参数调用SQL
            jdbcAgent.execute("update org_table set title =? and data_id=?",Arrays.asList(new Object[]{title,dataId}));
            // 类Hibernate HQL传参写法，带参数调用SQL
            Map<String, Object> params = new HashMap<>();
            params.put("title",title);
            jdbcAgent.executeNamedSql("update org_table set title = :title",params);

            // 执行查询语句SQL：需要做两步，第一步execute()，第二步resultSetToList或resultSetToMap返回结果集
            jdbcAgent.execute("select id,title from org_table where title =?",title);
            List<Map<String,Object>> listResult = jdbcAgent.resultSetToList();

            // 执行查询语句SQL：需要做两步，第一步execute()，第二步resultSetToList或resultSetToMap返回结果集
            jdbcAgent.execute("select id,title from org_table where title =?",title);
            Map<String,Object> mapResult = jdbcAgent.resultSetToMap();

            // 下方式执行SQL查询即可一次返回结果
            Map<String, Object> params1 = new HashMap<>();
            params1.put("title",title);
            FlipInfo resultFlipInfo = jdbcAgent.findNameByPaging("select id,title from org_table where title = :title",params1,flipInfo);
            FlipInfo resultFlipInfo1 = jdbcAgent.findByPaging("select id,title from org_table where title = ?",Arrays.asList(new Object[]{title}),flipInfo);


JDBCAgent同样提供了的批量增删改方法：

/**
     * 批量执行SQL
     * @param params [{'标题',123456},{'标题2',78901},{'标题3',98777}]
     */
    public void batch(List<Object[]> params){
        JDBCAgent jdbcAgent = null;
        try {
            jdbcAgent = new JDBCAgent();
            jdbcAgent.batch1Prepare("update org_table set title = ? where id = ?");
            jdbcAgent.batch2Add(params);
            jdbcAgent.batch3Execute();
        } catch (Exception e) {
            logger.error("",e);
        } finally {
            jdbcAgent.close();
        }
    }


## 禁忌操作

JDBCAgent的禁忌相对DBAgent少很多，主要注意三个点：

// 1）一定一定一定要关闭连接，不执行如下close很容易引起客户环境连接池泄漏
jdbcAgent.close();

// 2）参数严禁直接拼接在SQL后面，需要以参数变量传入防止SQL注入：
String sql = "select id,title from org_table where id="+id;// Bad code:SQL注入
String sql = "select id,title from org_table where id= ?";// Nice code

// 3）不要使用select *查询全部结果集，务必按需查找结果集
String sql = "select * from org_table where id= ?";// Bad code
String sql = "select id,title from org_table where id= ?";// Nice code



## 扩展阅读


## JDBCAgent和DBAgent使用场景

## DBAgent使用场景

对数据执行新增、修改、删除操作，我们推荐使用DBAgent即Hibernate封装的能力来完成：save、saveAllForceFlush等方法能很好完成数据的写入。

如果你担心性能，也可以通过HQL进行批量修改、删除：delete from Org where id in (:ids);

对于单表的查询，我们同样推荐使用DBAgent进行操作，但注意查看[DBAgent禁忌规则]，良好的编码习惯才能保证系统稳定运行。

## JDBCAgent使用场景

如果涉及多表关联查询，我们一概推荐使用JDBC SQL来完成，经过多个有效场景验证，多表关联的JDBC SQL比Hibernate HQL性能要强几倍甚至几十倍！


## AbstractHibernateDao

这是早期平台提供的：纯Hibernate Entity DAO基类，不带扩展的分页函数。通过泛型，子类无需扩展任何函数即拥有完整的CRUD操作。

继承AbstractHibernateDao之后，Dao层实现无需使用DBAgent，可以直接调用预埋的CRUD方法使用。

建议：如无必要，没必要使用此方案，推荐使用常规的JDBCAgent、DBAgent。

public class ShowDaoImpl extends AbstractHibernateDao<ShowbarInfo> implements ShowDao {

 @Inject
 private OrgManager orgManager;

 @Override
 public int countNewsShowbarList(User user, Map<String, Object> filter) throws BusinessException {
  NamedQueryCondition condition = this.getNewsShowbarList(user, filter);
  return super.count(condition.getNamedQuery(), "showbarInfo.id", true, condition.getParam());
 }
 @Override
 @SuppressWarnings("unchecked")
 public List<ShowbarInfo> findNewsShowbarList(int start, int size, User user, Map<String, Object> filter) throws BusinessException {
  NamedQueryCondition condition = this.getNewsShowbarList(user, filter);
  return super.find(condition.getNamedQuery(), start, size, condition.getParam());
 }
}



## CTP平台事务管理机制

1）事务中，有些数据库对表的DDL会默认提交，如oracle，所以在一个事务中的操作，最好能区分开。

2）目前一个“空”事务中，使用DBAgent来对对象进行修改后，由于hibernate判断本次操作在事务中，所以暂缓刷新到数据库，而再使用DBAgent的find命令，由于判断当前事务为空事务，所以不会触发刷新到数据库，而是直接查询数据库，从而查询为空。

对于这种情况，一种方法是在修改或者新增的时候，手动调用dbagent的commit操作；二种方法是使用dbagent直接对对象的get操作。

V5平台要求使用全系统统一命名方法控制事务，即DAO层方法是下面开头则会被相应事务传播机制所控制：

有事务的方法命名(REQUIRED)

    save*
    insert*
    delete*
    update*
    trans*
    test*
    import*
    add*
    create*


无事务的方法命名(SUPPORTS)

    is*
    check*
    find*
    get*
	select*
    list*
    query*
    on*
    copy*


随着时间的迁移，平台的事务管理也在变化，当前版本的详细控制可参考配置文件：/WEB-INF/cfgHome/spring/spring-default.xml


## 使用注解控制事务

7.0以上版本支持注解配置事务，主要用于性能优化，消除不必要的事务，注解和XML同时配置则注解优先。

@Transactional(propagation = Propagation.SUPPORTS, rollbackFor = com.seeyon.ctp.common.exceptions.BusinessException.class)
    @Override
    public void updateETagDate(String category, String key) {

    }



## 数据库规范

不同数据库字段映射关系：

MYSQL      ORACLE      SQLSERVER   POSTGRESQL     DM             KINGBASE       OSCAR          GBASE          HBM文件       POJO类型              场景
BIGINT     INTEGER     BIGINT      INT8           BIGINT         INT8           BIGINT         BIGINT         long        java.lang.Long      主键
DATE       DATE        DATETIME    TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   timestamp   java.util.Date      日期
DATETIME   DATE        DATETIME    TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   TIMESTAMP(0)   timestamp   java.util.Date      日期时间
DECIMAL    NUMBER      NUMERIC     NUMERIC        NUMBER         NUMERIC        NUMBER         NUMBER         double      java.lang.Double    小数
INT        INTEGER     INT         INT4           INT            INT4           INTEGER        INT            integer     java.lang.Integer   整数
LONGBLOB   BLOB        IMAGE       BYTEA          BLOB           BYTEA          BLOB           BLOB           string      java.lang.String    二进制对象，原则不允许
LONGTEXT   CLOB        NTEXT       TEXT           CLOB           TEXT           CLOB           CLOB           string      java.lang.String    大文本
SMALLINT   NUMBER(4)   SMALLINT    INT2           SMALLINT       INT2           SMALLINT       SMALLINT       integer     java.lang.Integer   数字枚举
VARCHAR    VARCHAR2    NVARCHAR    VARCHAR        VARCHAR        VARCHAR        VARCHAR        VARCHAR        string      java.lang.String    文本

其它数据库规范，详见开放平台>快速开始>开发规范>数据库部分。

编撰人：het、lichaoj、admin




快速跳转



 * DAO数据层开发
   * 数据层开发示例
     * 第一步：建表
     * 第二步：新增索引
     * 第三步：定义hbm
     * 第四步：DAO层接口和实现
     * 第五步：注册DAO到Spring容器
     * 第六步：Manager层调用
   * 数据层工具类详解
     * 分页对象FlipInfo
     * 数据操作DBAgent
       * 常用API
       * 禁忌操作
     * 原生SQL-JDBCAgent
       * 常用API
       * 禁忌操作
   * 扩展阅读
     * JDBCAgent和DBAgent使用场景
       * DBAgent使用场景
       * JDBCAgent使用场景
     * AbstractHibernateDao
     * CTP平台事务管理机制
     * 使用注解控制事务
   * 数据库规范



分享链接分享链接

## 29. 缓存组件

> 原始路径：`/39/75.html`  
> 相对路径：`39/75.md`

## 缓存组件


## 什么时候使用？

 1. 缓解数据库压力，提升响应速率。
 2. 节点之间数据同步，内存共享。

平台封装了统一的缓存API组件，单机和集群下由平台统一控制使用对应的缓存实现，真正做到一处开发多处使用的能力。 单机默认采用内存缓存，集群采用集中式Redis缓存。


## 如何使用？

// 第一步，创建缓存群组：PrivilegeCacheImpl.class 为缓存的组名称
private CacheAccessable factory = CacheFactory.getInstance(PrivilegeCacheImpl.class);
// 第二步，创建缓存：menuMap 为缓存名称，在同一个组内缓存名称不能相同
private AdvancedCacheMap<Long, PrivMenuBO, Long> menuMap = factory.createAdvancedMap("menuMap", new PrivMenuL2CacheMapLoader(), true, 500);
// 第三步，使用缓存
获取数据: menuMap.get(1231)
写入数据：menuMap.put(123,Obj)
删除数据：menuMap.remove(123)



## 使用哪种类型？

平台提供了多种缓存模型，开发可以根据实际场景采用对应的缓存方案。


## CacheMap

键值对数据缓存，提供类似于java.util.Map的功能，支持常用的get,put,remove等方法。

/**举例：创建CacheMap**/
CacheMap<String, RestUser> restuserCache =  factory.createMap("restuser",new RestUserMapLoader());
/**Rest用户加载*/
public class RestUserMapLoader implements MapDataLoader<String, RestUser>{

  @Override
  public RestUser load(String key) {
    Map<String, RestUser> loadLocal = loadBatch(Arrays.asList(key));
    if(loadLocal != null)
      return loadLocal.get(key);
    return null;
  }

  @Override
  public Map<String, RestUser> loadBatch(Collection<String> keys) {
    Map<String, RestUser> map = null;
    if(keys.size() > 0) {
      RestUserDao restUserDao = (RestUserDao) AppContext.getBean("restUserDao");
      List<RestUser> restUsers = restUserDao.findListUserByNames(new ArrayList<String>(keys));
      map  = convertToMap(restUsers);
    }
    return map;
  }

}



## AdvancedCacheMap

CacheMap的高级实现，除了CacheMap的功能之外，还支持批量数据获取、懒加载、本地模式、索引等。

/**举例：枚举缓存**/
AdvancedCacheMap<Long, CtpEnumItem, EnumItemIndex> advanceCtpEnumItemCache =
      factory.createAdvancedMap("ctpEnumItemCache", new EnumItemCacheMapLoader());
/**枚举缓存加载及丢失补偿**/  
public class EnumItemCacheMapLoader implements L2CacheMapLoader_Long<Long,CtpEnumItem, HashMap> {

  @Override
  public Map loadIndexData() {

   //如果需要使用index功能需要实现该接口，同时设置下方的hasIndex返回true

  }

  @Override
  public CtpEnumItem loadDataFromDB(Long id) {

//单个数据加载

  }

  @Override
  public boolean hasIndex() {
    return false;
  }

  @Override
  public int getL2CacheSize() {

    //设置本地LRU缓存的大小，如果在接口中不覆盖，默认大小为1000
      return 200000;
    }

  /**
   * 按照key集合从数据库中批量加载数据
   * @param ids
   * @return
   */
  @Override
  public Map loadDatasFromDB(Long... ids){

//批量获取

  }

  /**
   * 从数据库中批量加载数据
   *
   * @return
   */
  @Override
  public Map loadAllDatasFromDB() {

  }

}



## IndexCacheMap

主要的方法同CacheMap，但是加入了索引存储机制，主要用于关系缓存。

/**举例：登录token和用户Id的关系缓存**/
IndexCacheMap<String, Long>   cacheThirdUser = factory.createIndexMap("cacheThirdUser", new MemberTransformationLoader());
/**按需加载*/
public class MemberTransformationLoader implements L2IndexCacheMapLoader_String<String,Long> {

  private ThirdpartyUserMapperDao thirdpartyUserMapperDao;

  @Override
  public Map<String, Long> loadIndexData() {
    Map<String, Long> userMap = new HashMap<String, Long>();

    List<ThirdpartyUserMapper> mapperUserList = getMapperDao().getAllUserMapper();
    for (ThirdpartyUserMapper thirdpartyUserMapper : mapperUserList) {
      //TODO
    }
    return userMap;
  }
}



## CacheObject

单一对象缓存，提供get，set两个方法。

/**举例：集群配置缓存**/
CacheObject<Properties> cache = factory.createObject("masterProperties",null);



## CacheSet

Set缓存，管理集合类的缓存，提供类似java.util.Set的功能。

/**举例：用户访问Token缓存**/
CacheSet<String> UserIdOfCanAccessMobile = cacheFactory.createSet("UserIdOfCanAccessMobile");



## Redis缓存组件原理

以AdvanceCacheMap实现为例，讲解缓存组件写入和读取的主要流程及原理。


## 缓存读取【get方法】



读取缓存数据步骤

①　初始化

②　检查NoCheck机制，在Nocheck中包含了无效Key检查，处理逻辑：AutoRefresh重新加载Index，从AutoRefresh HashMap中获取需要更新的Key；非AutoRefresh检查本地Key的标记位。使用了Index不要设置短时间Nocheck

③　在NoCheck时间内，直接查询本地缓存返回数据

④　查询Redis标记位

⑤　标记为和缓存不一致，获取Redis中缓存数据

⑥　标记位和本地一致，数据没发生变化，直接取本地缓存中数据返回

⑦　Redis中读取到数据，更新本地缓存，返回数据

⑧　Redis中读取不到数据，从数据库加载数据


## 缓存写入【put方法】



写入缓存数据

①　所有的修改操作基本都走这个逻辑，包括put、remove、update等。

②　如果标记为AutoRefresh，放入数据和Flag的同时，放入Flag刷新标记位，刷新数据2分钟有效，各节点需要在2分钟之内，去拉取Flag并同步数据到本地。

③　其他缓存，直接放入数据和Flag。

④　放入本地缓存，并设置needCheck为true，下次获取时，强制做数据对比。

⑤　清除本地Index，如果实现了Index。


## 常见场景


## 全量缓存

为了提供缓存命中率，很多数据量不大，但访问频率很高的数据可以采用全量缓存，全量缓存的数据在系统启动初始化时，从数据库中全量加载并缓存在Redis中，后续的操作通过后台的自动刷新机制同步到集群中的其他节点。

// autoRefresh设置为true
createAdvancedMap(String cacheName, L2CacheMapLoader_Inner dataLoader, boolean autoRefresh, int noCheckTime);



## 按需加载

启动时，系统不会加载全量的缓存数据，当需要读取数据时才通过接口从数据库中读取数据放入缓存中，使用按需加载时修改自己节点的数据不会通过自动刷新机制同步到集群中的其他节点，但是可以通过调用get方法主动对比flag标记位完成数据同步。

// autoRefresh设置为false
createAdvancedMap(String cacheName, L2CacheMapLoader_Inner dataLoader, boolean autoRefresh, int noCheckTime);



## 数据更新

 1. 更新数据时，推荐更新完数据库之后，删除Redis缓存中的数据，在下一次加载数据时，如果缓存中没有，会调用数据加载接口从新从数据库加载。尽量不要更新完数据库之后，直接调用put方法往Redis中写入数据。
 2. 在涉及高频访问时，尽量以数据库数据为基准来做业务判断，比如验证人员登录密码。


## 数据同步

目前缓存组件除了用于加速数据访问速度外，还有一个重要的功能是实现各节点之间数据同步，目前缓存中主要的数据同步机制包含以下两种：

 1. flag比对，数据在写入时会变更flag标记位，当本地数据的标记位和Redis中不一致时，组件会同步Redis中数据到本地，数据查询主要查询本地缓存中的数据。（主要机制，主动）
 2. 自动刷新机制，组件会在后台以一定的频率批量刷新Redis中的数据到本地缓存，完成各节点之前的数据同步。（次要机制，被动）


## 高频访问

由于在业务开发中存在循环调用的情况，每次调用即时从Redis中读取数据依旧性能表现不佳，这时可用通过缓存组件中的nocheck机制，在一定时间范围内直接动本地读取数据，减少对Redis访问的频率。 调用方式：

// autoRefresh设置为true
// noCheckTime设置时间范围
createAdvancedMap(String cacheName, L2CacheMapLoader_Inner dataLoader, boolean autoRefresh, int noCheckTime);


这种使用方式依靠自动刷新机制完成各节点之间的数据同步，由于自动刷新机制有一定延迟，且是被动机制，所以在一些低延迟，高数据一致性场景可能会存在一些问题，应该尽量避免使用。如果必须使用可以调用AdvanceCacheMap.get(key,false)穿透到Redis中读取数据。


## 不推荐的使用方式


## 不满足事务提交

在关系数据库中能保证事务的一致性，但是在Redis并不擅长处理事务的问题，如果在长事务中使用redis缓存相关的操作，需要考虑缓存场景的适应性，以及是否可以通过额外的补偿来解决事务的问题。

推荐方式：

 1. 注册spring事务TransactionSynchronizationManager.registerSynchronization在数据库更新完成后再执行redis操作。
 2. 在同时操作数据库和缓存时，应该先操作数据库，在操作缓存，同时也可以考虑幂等操作，在数据库事务回滚后是否对Redis中已写入的数据有影响。


## 无补偿模型

现在的缓存组件属于读穿透模型，当数据丢失时，缓存组件可以根据提供的数据加载接口自动补偿丢失的数据，但是一些业务中并没有配置数据加载接口，将会导致缓存数据丢失后不能被找回的情况。在使用缓存组件时尽量都配置数据加载接口，对于一些数据不能通过数据补偿的，需要考虑其他补偿机制，如：幂等，重建，忽略等方式，来满足业务功能。


## index缓存使用不当

IndexMap实现的本身是为实现动态数据加载，但是这个实现要求缓存组件需要知道所有的index(key/主键)，并且所有的写操作，更新操作都会触发更新index，所以如果在业务场景中大量使用更新操作，将会导致大量的index重新加载请求，从而带来性能问题。

两种代码编写方式为使用index：

 1. AdvanceCacheMap的数据加载接口中hasIndex()方法返回True。
 2. 调用createIndexMap，创建了IndexCacheMap。


## LRU设置不当

当前提供的几种缓存组件都带有本地缓存（JVM)缓存，本地缓存的大小可以通过LRU算法来设置，默认1000，当本地缓存数量超过设定的值后就会被淘汰出本地缓存，如果缓存中的数据量比较大，且访问频率很高，将会导致大量的数据被频繁的淘汰，导致大量的访问请求直接让问Redis，影响性能。

 @Override
  public int getL2CacheSize() {
      return 200;
  }



## 不推荐的方法

在缓存组件中提供了keySet，values等方法，这写方法对于本地的JVM缓存是没有问题的，但是对于分布式缓存，对于大数据场景，在缓存中只是加载的一部分热点数据，调用keyset，values，contains都会带来性能问题，或者这些方法返回的数据本身就是不可用的，在实际应用中应该谨慎使用。

AdvancedCacheMap<Long,User,Byte> userCache= = cacheAccessable.createAdvancedMap("userCache", userCacheLoader, true, 2000);

//为什么不推荐使用?

public boolean contains(Long updateValue) { return userCache.contains(updateValue); }

//为什么不推荐使用?

public void method(){

for(Long key:userCache.keySet()){ }

}



## 复杂缓存对象

缓存数据在传输时，需要序列化为字符串，缓存对象尽量使用POJO对象，使用简单的Bean对象，不要讲复杂的，特别是树结构、循环依赖结构的对象放入缓存中，将会带来大量的序列化和网络开销。


## 其他


## 直接操作Redis

有些场景可能现有封装的组件并不能满足我们的要求，可以直接操作Redis

RedisOpt<String, String, String> opt = RedisOptFactory.getStringInstance();
opt.get(key)
opt.set(key)
opt.hget(key,item)
opt.hset(key,item,value)
。。。。


但是在项目中不推荐直接操作Redis，原因如下： 1.无法进行统一管理，通过现有的监控工具查看缓存使用情况。 2.需要直行处理序列化。 3.缓存组件除了支持Redis还支持单机模式无需Redis的情况，需要自行实现兼容。


## OA集成Redis底层接入位置

OA是使用Jedis组件连接Redis服务，代码初始启动连接Redis的地方在：\ctp-core\src\main\java\com\seeyon\ctp\component\cache\redis\RedisHandler.java

初始入口：initialize()

initialize()通过读取配置文件判断走单机Redis还是三主三从Redis

单机Redis连接走initSingle()

三主三从Redis连接走initCluster()




## 常见问题

Redis缓存问题排查思路包括： 1.查看logs_sy/cache.log,logs_sy/performance.log,logs_sy/ctp.log日志文件中是否存在与Redis相关的报错 2.进入系统控制台查看缓存数据是否一致









3.检查Redis运行情况

集群缓存配置

单节点登录
$redis-cli -h host -p port -a password -c
查看运行情况
>  info

集群
$redis-cli -h host -p port -a password -c
查看集群状态

> cluster nodes
登录到主节点，执行info命令查看状态


编撰人：het、admin


快速跳转



 * 缓存组件
   * 什么时候使用？
   * 如何使用？
   * 使用哪种类型？
     * CacheMap
     * AdvancedCacheMap
     * IndexCacheMap
     * CacheObject
     * CacheSet
   * Redis缓存组件原理
     * 缓存读取【get方法】
     * 缓存写入【put方法】
   * 常见场景
     * 全量缓存
     * 按需加载
     * 数据更新
     * 数据同步
     * 高频访问
   * 不推荐的使用方式
     * 不满足事务提交
     * 无补偿模型
     * index缓存使用不当
     * LRU设置不当
     * 不推荐的方法
     * 复杂缓存对象
   * 其他
     * 直接操作Redis
   * OA集成Redis底层接入位置
   * 常见问题



分享链接分享链接

## 30. 国际化多语言

> 原始路径：`/39/77.html`  
> 相对路径：`39/77.md`

## 国际化多语言

在学习本章前，建议先了解一下什么叫国际化、多语言。

平台针对PC、移动端均提供了多语言的开发框架能力。

多语言的基础条件是词条，词条是一个key-value组合，格式如：common.button.ok.label = OK.实际应用中，开发只需要在显示端引用词条key，系统则会根据语种环境自动显示对应语言。


## PC端国际化


## 定义国际化词条

国际化依然要遵守插件化开发规则，插件国际化配置文件位于“cfgHome/plugin/插件id/i18n”目录下，按照JDK国际化文件的配置规则命名。

注意：词条key必须以插件id开始。 默认插件国际化资源配置只能在Java端使用，前端javascript无法使用，如果要开放给前端，可以在插件的i18n文件夹根下创建名为“export_to_js.xml”注册js可以使用的词条key。

PC端标准国际化文件结构：

WEB-INF
    cfgHome
        plugin
            taskmanage
                i18n
                    taskmanage_en.properties
                    taskmanage_zh_CN.properties
                    taskmanage_zh_TW.properties
                    export_to_js.xml


PC端国际化文件编写规范： properties中的资源必须经过编码，不允许出现中文、日文、法文等字符，而必须是ASCII码。 注意：词条key必须以插件id开始。

## taskmanage_zh_CN.properties
taskmanage.create.label    = \u521B\u5EFA
taskmanage.create.label1   = \u521B\u5EFA{0}
taskmanage.create.label2   = {0}\u521B\u5EFA{1}

## taskmanage_zh_TW.properties
taskmanage.create.label    = \u5275\u5EFA
taskmanage.create.label1   = \u5275\u5EFA{0}
taskmanage.create.label2   = {0}\u5275\u5EFA{1}

## taskmanage_en.properties
taskmanage.create.label    = Create
taskmanage.create.label1   = Create {0}
taskmanage.create.label2   = {0} Create {1}



## Java调用国际化

Java端使用平台的ResourceUtil工具类获取国际化内容。

String value = ResourceUtil.getString("taskmanage.create.label");
//一个占位符
String value1 = ResourceUtil.getString("taskmanage.create.label1", "admin");
//两个占位符
String value2 = ResourceUtil.getString("taskmanage.create.label2", "上帝", "人");



## 前端调用国际化

JSP前端调用方式：

<%-- 引入common_header --%>
<%@ include file="/WEB-INF/jsp/common/common_header.jsp"%>
<tr>
    <td>ctp:i18n函数</td>
    <td>${ctp:i18n('common.button.add.label')}</td>
</tr>
<tr>
    <td>ctp:i18n_1函数，一个参数，变量参数</td>
    <td>${ctp:i18n_1('common.charactor.limit.label',path)}</td>
</tr>
<tr>
    <td>ctp:i18n_1函数，一个参数，数值参数</td>
    <td>${ctp:i18n_1('common.charactor.limit.label',10)}</td>
</tr>
<tr>
    <td>ctp:i18n_1函数，一个参数，字符串参数</td>
    <td>${ctp:i18n_1('common.charactor.limit.label','测试')}</td>
</tr>
<tr>
    <td>ctp:i18n_2函数，两个参数</td>
    <td>${ctp:i18n_2('common.charactor.limit.label','测试',3)}</td>
</tr>
<tr>
    <td>ctp:i18n_3函数，三个参数</td>
    <td>${ctp:i18n_3('common.charactor.limit.label','测试',3,3)}</td>
</tr>
<tr>
    <td>ctp:i18n_4函数，四个参数</td>
    <td>${ctp:i18n_4('common.charactor.limit.label','测试',3,3,3)}</td>
</tr>
<tr>
    <td>ctp:i18n_5函数，五个参数</td>
    <td>${ctp:i18n_5('common.charactor.limit.label','测试',3,3,3,3)}</td>
</tr>


Javascript中调用国际化：

在javascript文件中默认情况下无法获取国际化词条。 如果要获取国际化词条则需要在/cfgHome/plugin/插件ID/i18n目录下新增export_to_js.xml文件，然后在文件里注册需要被js引用的国际化key。

<?xml version="1.0" encoding="utf-8"?>
<export>
 <resKey>taskmanage.create.label</resKey>
 <resKey>taskmanage.create.label1</resKey>
 <resKey>taskmanage.create.label2</resKey>
</export>


在完成export_to_js.xml的前提下，前端JSP引入common_footer.jsp文件，再通过平台封装好的函数调用国际化内容，示例如下：

前端javascript中：
<%-- 注意在JSP中引入common_footer --%>
<%@ include file="/WEB-INF/jsp/common/common_footer.jsp"%>
<script type="text/javascript">
 var value = $.i18n('taskmanage.create.label');
 var value1 = $.i18n('taskmanage.create.label1','参数1');
 var value2 = $.i18n('taskmanage.create.label2','参数1','参数2');
</script>



## 移动端国际化


## 定义国际化词条

移动端与PC端的国际化词条是分别开发维护的，主要原因是PC国际化词条太过庞大，移动端词条按需使用，需要本地化存储。

mplus-front
    src
        apps
            v5
                taskmanage
                    i18n
                        taskmanage_en.properties
                        taskmanage_en.properties
                        taskmanage_zh_TW.properties


代码存放于移动端工程，各模块下，如：mplus-front\src\apps\v5\addressbook\i18n\Addressbook_en.properties

移动端开发态的国际化是properties文件，而开发在生产部署之后看到的国际化是js格式，这里编译工程做了一个简化操作：

 * 开发态（源码态）下properties文件更利于国际化维护

 * 运行态（生产系统上），html只能引用javascript，所以每次编译都基于properties文件同步一份javascript文件

 * 本地开发如何做到properties转javascript？可以参考M3培训手册中的工具s3js来实现编码从开发态向运行态的转换


## HTML调用国际化

<!-- 默认引入zh_CN的国际化，以加速页面响应效率 -->
<script src="${data:dependencies.attendance}/i18n/attendance_zh_CN.js${data:buildversion}"></script>
<script src="${data:dependencies.commons}/i18n/Commons_zh_CN.js${data:buildversion}"></script>
<script src="${data:dependencies.cmp}/js/cmp-i18n.js${data:buildversion}"></script>
<script>
<!-- 异步调用i18n组件，地址指向本模块的i18n文件夹，这一步组件会自动判断国际化环境加载对应文件 -->
cmp.i18n.init("${data:dependencies.attendance}/i18n/","attendance",function(){
//初始化本页面titile国际化标准写法
document.title = cmp.i18n("Attendance.label.atWork");
});
</script>


<!-- 前端html标签调用国际化方法，使用<i18n>自定义标签来实现：-->
<div ><span><i18n key="Attendance.label.records"></i18n></span></div>

<!-- 前端javascript调用国际化方法：-->
<script type="text/javascript">
//普通写法
var i18n = cmp.i18n("Attendance.label.attendance");
//带占位符的写法
var i18n1 = cmp.i18n("Attendance.label.authAttendTimes","123");
</script>



## 特殊产品线国际化（国际化后缀）

事情来源于政务G6，政务G6与A8的功能相差不大，共用一套代码，但是产品需求有调整：A8的协同应用就叫“协同”，G6的协同应用叫“事务”。

问题来了：这些命名都是通过国际化文件维护，一山不容二虎，G6产品线需要修改标准产品的国际化内容才能达成产品需求。

基于以上原因，平台提供了一套不同产品线维护相同国际化的机制：政务G6产品线只要在原有国际化后面追加一个.GOV的国际化key就优先走政务国际化。

menu.tools.about     = 關於
menu.tools.about.GOV = 關於G6



## 实现原理

G6是一个新产品线，我们在产品线定义文件中规定了".GOV"后缀的信息，如下代码所示：

public enum ProductEditionEnum {
// ...
    entgroup        (2, "A8V5-2", "edition.entgroup.product", ""), // A8+企业集团版
    government      (3, "G6V5-1", "edition.government.product", ".GOV"), // 政务版
    governmentgroup (4, "G6V5-2", "edition.governmentgroup.product", ".GOV") // 政务多组织版
}


在实际运行中，我们的国际化获取显示值的代码实际执行如下：

1）先通过key+国际化后缀获取当前产品线下是否有特殊国际化

2）没有则寻找key的原始国际化内容

// 使用版本特定后缀的国际化KEY
        String i18nSuffixUpperCase = ProductEditionEnum.getCurrentProductEditionEnum().getI18nSuffix();
        // 使用版本特定后缀的国际化KEY
        String suffixKey = key + i18nSuffixUpperCase;
        String message = ResourceLoader.getResources(locale, suffixKey);
        // 如果没有取到，就使用默认的KEY
        if (Strings.isNotBlank(i18nSuffixUpperCase) && (message == null || "".equals(message.trim()))) {
            message = ResourceLoader.getResources(locale, key);
        }



## 开发注意事项

1）国际化key命名原则：插件名.功能点1.功能点*.动作

## 不推荐（单字母严重不推荐）
detaili18n = Detail
## 不推荐（首字母不是所属模块）
deeSection.name = DeeSection
## 推荐（首字母对应插件名，至少两个点以上）
dee.synchron.detail.label = Detail


2）关于拼接国际化key避开如下拼接方式 有时候我们会写一些与后台枚举变量对应的国际化，如下所示通过1，2，3区分不同的枚举：

attendance.clock.levels.level1 = low
attendance.clock.levels.level2 = medium
attendance.clock.levels.level3 = senior
// 调用的时候采用变量的方式拼接，如下所示
public void getLevel(int num){
 ResourceUtil.getString("attendance.clock.levels.level"+num);
}


这种拼接的方式我们是推荐的，但请尽量把变量放国际化最后一个，不要像下面这样：

attendance.level1.label = low
attendance.level2.label = medium
attendance.level3.label = senior
// 不推荐，不推荐
public void getLevel(int num){
 ResourceUtil.getString("attendance.level"+num+".label");
}
// 首先上面这种写法是没问题的，但是不推荐，因为我们有一个工具会检测未使用的国际化key
// 像上面这种，工具会认为以"attendance.level"开头的国际化都在被使用，很多未使用的国际化key会被忽略了！
attendance.level.xxx
attendance.level.yyy
attendance.level.zzz


3）properties文件注释使用#，不要出现下面这种注释：

//------------------------\u4E8C\u7EF4\u7801-----------------


4）预置（初始化）的数据要考虑国际化，推荐创建properties，初始化SQL使用国际化key

INSERT INTO MEETING_ROOM_TYPE (ID,NAME,PARENT_ID,SORT) VALUES(-1,'meeting.room.type.unclassified',0,0);


5）规避重复的国际化值定义 高频率出现、重复的翻译（如确定，取消等等等等），必须取平台Common中的国际化key

 * 相同的国际化翻译共用一个key，不要重复定义，节约空间
 * 废弃的国际化key一定要及时删除，一定要及时删除，节约空间

6）所有新功能在开发版本期内必须完成国际化，不要说下版本支持，不做就不能发版！

7）所有英语翻译首字母必须大写

8）英文下单词需要空格

9）单个单词不要截断换行

//以下显示是错误的
i have a dr
eam.
//以下显示是正确的
i have a 
dream.


10）引导类文字，如菜单名称一定要显示全（即使是换行显示也行），不能出...

11）鼠标移动到文字上方时需要有完整名称的tips提示

12）标题类字段不要局限于20个字，尽量提高到250字或更大，因为海外的一些英文信息非常长！

13）不要只使用中文的图片，至少让UE提供中英两套图片

14）一些紧凑布局要提出质疑：英文国际化下是否会显示混乱

15）日期时间不要用Java自带的DateFormat，必须使用平台的Datetimes工具类处理，平台工具类对时区进行了专业处理的

编撰人：het、admin




快速跳转



 * 国际化多语言
   * PC端国际化
     * 定义国际化词条
     * Java调用国际化
     * 前端调用国际化
   * 移动端国际化
     * 定义国际化词条
     * HTML调用国际化
   * 特殊产品线国际化（国际化后缀）
     * 实现原理
   * 开发注意事项



分享链接分享链接

## 31. 定时任务

> 原始路径：`/39/78.html`  
> 相对路径：`39/78.md`

## 定时任务

平台提供了两种定时任务机制：

 * 基于Timer的普通单机定时任务
 * 基于Quartz的持久化支持集群定时任务

我们支持集群多服务器部署，开发过程中一定要思考定时任务的应用范围！


## Quartz

Quartz是平台基于第三方框架封装的定时任务，此定时任务的特点是：两台服务器集群下，只会有一台服务器执行，即一个OA系统下只有一个节点执行定时任务，以防止任务重复执行。

核心类com.seeyon.ctp.common.quartz.QuartzHolder


## 基本原理

定时任务采用异步处理模式，在生成定时任务的时候需要指定：任务处理器Bean + 参数。 任务处理器Bean是解释执行特定任务的JavaBean，通过参数来描述业务特征。


## 开发案例

定义一个QuartzJob类，实现com.seeyon.ctp.common.quartz.QuartzJob接口

class ABCQuartz implement QuartzJob{
    public void execute(Map<String, String> parameters){
        Long id = parameters.get("id");
        // TODO
    }
}


按照插件化开发规范，将QuartzJob注册到Spring容器中spring-xx.xx.xml：

<bean name="abcQuartz" class="package.ABCQuartz" >



## 注册任务

开发QuartzJob之后，需要注册这个Job的执行时间、循环周期、以及每次触发时传递的参数。

// 将如下代码放在希望触发定时任务的地方
Map<String, String> parameters = new HashMap<String, String>();
parameters.put("id", String.valueOf(id));
if(!QuartzHolder.hasQuartzJob("jobName"){
    QuartzHolder.newQuartzJob("jobName", new Date(109, 1, 1), "abcQuartz", parameters);
}



## 常用API

QuartzHolder其它接口

/**  
 * 检测任务是否存在  
 *  
 * @param name 任务名称  
 * @return  
 */  
public static boolean hasQuartzJob(String name);  
/**  
 * 删除任务  
 *  
 * @param name 任务名称  
 * @return  
 */  
public static boolean deleteQuartzJob(String name);

	/**
	 * 只运行一次，默认分组
	 * @param jobName 任务名称，要求每一个任务唯一
	 * @param runTime 触发运行的时间点
	 * @param jobBeanId 任务执行类的BeanId, implement QuartzJob接口
	 * @param parameters
	 * @return
	 * @throws MutiQuartzJobNameException 
	 */
	public static boolean newQuartzJob(String jobName, Date runTime,
			String jobBeanId, Map<String, String> parameters) throws MutiQuartzJobNameException, NoSuchQuartzJobBeanException {
		return newQuartzJob(jobName, runTime, 0, 0, jobBeanId, parameters);
	}

	/**
	 * 创建每天的定时任务，时间以beginTime为准
	 * @param groupName 可以为<code>null</code>
	 * @param jobName
	 * @param beginTime
	 * @param jobBeanId 任务执行类的BeanId, implement QuartzJob接口
	 * @param parameters
	 * @return
	 */
	public static boolean newQuartzJobPerDay(String groupName, String jobName, Date beginTime, String jobBeanId, Map<String, String> parameters) throws MutiQuartzJobNameException, NoSuchQuartzJobBeanException{
		return newQuartzJobPerDay(groupName, jobName, beginTime,null, jobBeanId, parameters);
	}




## Timer

Timer利用Java自带特性进行封装，Timer只能在当前机器运行，即如果是两台服务器集群环境，两台服务器都会执行各自的Timer任务：

// 其中sampleTask是一个Runnable
TimerHolder.newTimer(sampleTask, 60 * 60 * 1000);


平台封装了TimerHolder用于定时任务创建，常见API如下：


	/**
	 * 创建定时任务，从现在开始，周期性运行无限次
	 * @param task 任务
	 * @param period 运行周期，必须大于0，毫秒
	 * @return
	 */
	public static boolean newTimer(Runnable task, long period) {
		timer.schedule(new TimerTaskProxy(task, true), new Date(), period);
		return true;
	}

	/**
	 * 创建定时任务，延迟一段时间后再开始，周期性运行无限次
	 * @param task 任务
	 * @param delay 延迟时间，必须大于0，毫秒
	 * @param period 运行周期，必须大于0，毫秒
	 * @return
	 */
	public static boolean newTimer(Runnable task, long delay, long period) {
		timer.schedule(new TimerTaskProxy(task, true), delay, period);
		return true;
	}

	/**
	 * 创建定时任务，在指定时间点运行一次
	 * @param task 任务
	 * @param runTime 运行时间点
	 * @return
	 */
	public static boolean newTimer(Runnable task, Date runTime) {
		timer.schedule(new TimerTaskProxy(task, true), runTime);
		return true;
	}



## 扩展：QuartzJob表达式

QuartzJob拥有灵活的表达式，如果标准的API无法满足需求，完全可以使用cron表达式来完成定时任务的创建。

一个cron表达式有至少6个（也可能7个）有空格分隔的时间元素。

按顺序依次为

秒（0~59）

分钟（0~59）

小时（0~23）

天（月）（0~31，但是你需要考虑你月的天数）

月（0~11）

天（星期）（1~7 1=SUN 或 SUN，MON，TUE，WED，THU，FRI，SAT）

7.年份（1970－2099） 其中每个元素可以是一个值(如6),一个连续区间(9-12),一个间隔时间(8-18/4)(/表示每隔4小时),一个列表(1,3,5),通配符。由于"月份中的日期"和"星期中的日期"这两个元素互斥的,必须要对其中一个设置?.

0 0 10,14,16 ? 每天上午10点，下午2点，4点

0 0/30 9-17 ? 朝九晚五工作时间内每半小时

0 0 12 ? * WED 表示每个星期三中午12点

"0 0 12 ?" 每天中午12点触发

"0 15 10 ? " 每天上午10:15触发

"0 15 10 ?" 每天上午10:15触发

"0 15 10 ? *" 每天上午10:15触发

"0 15 10 ? 2005" 2005年的每天上午10:15触发

"0 14 * ?" 在每天下午2点到下午2:59期间的每1分钟触发

"0 0/5 14 ?" 在每天下午2点到下午2:55期间的每5分钟触发

"0 0/5 14,18 ?" 在每天下午2点到2:55期间和下午6点到6:55期间的每5分钟触发

"0 0-5 14 ?" 在每天下午2点到下午2:05期间的每1分钟触发

"0 10,44 14 ? 3 WED" 每年三月的星期三的下午2:10和2:44触发

"0 15 10 ? * MON-FRI" 周一至周五的上午10:15触发

"0 15 10 15 * ?" 每月15日上午10:15触发

"0 15 10 L * ?" 每月最后一日的上午10:15触发

"0 15 10 ? * 6L" 每月的最后一个星期五上午10:15触发

"0 15 10 ? * 6L 2002-2005" 2002年至2005年的每月的最后一个星期五上午10:15触发

"0 15 10 ? * 6#3" 每月的第三个星期五上午10:15触发

有些子表达式能包含一些范围或列表

例如：子表达式（天（星期））可以为 “MON-FRI”，“MON，WED，FRI”，“MON-WED,SAT”

“*”字符代表所有可能的值

因此，“”在子表达式（月）里表示每个月的含义，“”在子表达式（天（星期））表示星期的每一天

“/”字符用来指定数值的增量

例如：在子表达式（分钟）里的“0/15”表示从第0分钟开始，每15分钟

在子表达式（分钟）里的“3/20”表示从第3分钟开始，每20分钟（它和“3，23，43”）的含义一样

“？”字符仅被用于天（月）和天（星期）两个子表达式，表示不指定值

当2个子表达式其中之一被指定了值以后，为了避免冲突，需要将另一个子表达式的值设为“？”

“L” 字符仅被用于天（月）和天（星期）两个子表达式，它是单词“last”的缩写

但是它在两个子表达式里的含义是不同的。

在天（月）子表达式中，“L”表示一个月的最后一天

在天（星期）自表达式中，“L”表示一个星期的最后一天，也就是SAT

如果在“L”前有具体的内容，它就具有其他的含义了

例如：“6L”表示这个月的倒数第６天，“ＦＲＩＬ”表示这个月的最一个星期五

注意：在使用“L”参数时，不要指定列表或范围，因为这会导致问题

单位         范围                   表达式
秒          0-59                 , - * /
分          0-59                 , - * /
小时         0-23                 , - * /
日期         1-31                 , - * ? / L W C
月份         1-12 或者 JAN-DEC      , - * /
星期         1-7 或者 SUN-SAT       , - * ? / L C #
年（可选）      留空, 1970-2099        , - * /

编撰人：het、admin


快速跳转



 * 定时任务
   * Quartz
     * 基本原理
     * 开发案例
     * 注册任务
     * 常用API
   * Timer
   * 扩展：QuartzJob表达式



分享链接分享链接

## 32. 日期和多时区

> 原始路径：`/39/79.html`  
> 相对路径：`39/79.md`

## 日期和多时区

协同服务器机房在中国，而全球各地都有用户，需要连到中国服务器办公，这里就存在“时区”的影响：

 * 北京时间（UTC+8：2021-8-5 21:01:25）
 * 伦敦时间（UTC/GMT：2021-8-5 13:01:25）
 * 美国时间（UTC-5：2021-8-5 08:01:25）

不同地区的时间不一致，那么就提出一个问题：如果英国用户在2021-8-5 13:01:25发出的协同，我中国用户和美国用户打开协同应该看到的发起时间是什么时候？

显然，答案应该是看到的发起时间跟着自己地区的时间走，否则数据就会混乱。

那么如何实现不同地区发出、查看的数据能跟着自己本地的时区时间走呢？这里就涉及到“多时区”的概念。


## 时区案例

前面说了时区的概念，那么落实到具体场景：我们所谓的时区在PC电脑里是如何体现的呢？

实际我们个人电脑关于时区的体现就在我们PC日历上面，如下图所示是标准的北京时间：



而如果你处于伦敦、纽约、东京等不同地域，你可以手动调整日期显示格式到对应时区，或者选择自动设置时区：



切换时区后，你所在PC电脑上看到的日期就是对应时区的当前时间，这个不用赘述了。


## 技术如何实现

回到前面的问题，如果我一套V5协同管理系统要在不同国家地区使用，那么我如何保障一名伦敦时间用户发送的会议邀请（UTC/GMT：2021-8-5 13:01:25），在北京时区用户（UTC+8：2021-8-5 21:01:25）和美国用户（UTC-5：2021-8-5 08:01:25）打开会议时，看到的会议时间是北京、美国用户各自本地的时间？

这里就涉及一套统一的时区管理原则，开发人员在编写多时区代码的时候，一定要认真理解这个原理。

1）V5协同服务器和数据库要在同一时区下维护，所有地区的时间最终会转换为服务器的时区时间统一管理。

2）不同时区提交保存日期数据原则：对应时区的PC端传输自己时区的日期时间字符串到服务器，服务器将日期字符串通过日期转换函数+时区转换为统一的服务器日期对象，存储到数据库。

3）不同时区查看日期数据原理：对应时区的PC端向服务器发送获取日期数据的请求，服务器从数据取出日期对象，在服务器端通过日期转换函数+时区转换，将服务器时区的日期对象转换为客户端时区的日期字符串返回。




## 前提准备

多时区是一个独立的商务插件，需要向商务申请购买，更新加密狗Lic。

购买之后，还需要通过登录系统管理员->模块管理->开启“多时区”->重启一次服务器才生效。


## 标准API

1、平台的com.seeyon.ctp.util.Datetimes工具类是专门用于做日期（含时区）转换的，平台的com.seeyon.ctp.util.DateUtil也能实现相同功能，但我更推荐Datetimes（更全面）。

2、调用API就分下面几种场景：

// 字符串带时区转Date  
Date date = Datetimes.parse(dateStr, pattern)  
// 字符串不带时区转Date  
Date date = Datetimes.parseNoTimeZone(dateStr, pattern)  
// Date带时区转字符串  
String str = Datetimes.format(date, pattern)  
// Date不带时区转字符串  
String str = Datetimes.formatNoTimeZone(date, pattern)


> 注：任何时候，日期的格式化都不允许使用SimpleDateFormat，要求全部使用平台的Datetimes实现！

Datetimes格式化常量：

public static final String datetimeStyle = "yyyy-MM-dd HH:mm:ss";

public static final String datetimeStyleNoSeparator = "yyyyMMddHHmmss";

public static final String dateStyle = "yyyy-MM-dd";

public static final String dateStyleWithoutYear = "MM-dd";

public static final String datetimeStartWithMonthStyle = "MM-dd HH:mm";

public static final String datetimeWithoutSecondStyle = "yyyy-MM-dd HH:mm";

public static final String datetimeAllStyle = "yyyy-MM-dd HH:mm:ss.S";

private static final String datetimeCSTStyle = "EEE MMM dd HH:mm:ss Z yyyy";

public static final String RFC822_PATTERN = "EEE', 'dd' 'MMM' 'yyyy' 'HH:mm:ss' 'Z";



## 时区编写示例


## 客户端到服务器

客户端来自不同地区，不同地区都有发协同等操作，那么同一时刻，不同时区发起的协同日期如何控制？

这里采用的是“服务器统一时间”的机制，即无论什么地区同一时刻发起的协同，发送到服务器之后通过时区工具类转换，必然会转为当前服务器的日期，这样就保证所有地区的数据存储日期一致。

从客户端传到服务器，需要使用Datetimes.parse将客户端的日期字符串转换为服务器的Date日期对象，没有直接的客户端String字符串转服务器String字符串的接口。

<!-- 前端日期数据 -->
<form>
 <input name="startTime" type="text" value="2021-08-21 11:50:30"/>
</form>


// =======后端代码=======  
// 获取客户端的日期字符串  
String timeStr = request.getParameter("startTime");  
// 通过pase方法将客户端的字符串日期转换为服务端的Date对象  
Date startTime = Datetimes.parse(timeStr, Datetimes.datetimeStyle);  
// 转换为服务器日期Date后，将对象存入数据库  
sqlDao.save(startTime);



## 服务器到客户端

客户端来自不同地区，不同地区查看同一个协同，协同里面的发起时间要与不同时区对应，这种日期如何控制？

同样，如果你基于场景一“服务器统一时间”的规则进行开发，那么此时协同的发起时间是存入服务器数据库的。不同时区客户端向服务器发送请求获取协同的发起日期，实际是将服务器数据库中Date对象转换为客户端字符串日期的一个过程。

从服务器返回给客户端，需要使用Datetimes.format方法将服务器的Date日期对象转换为客户端的日期时间String字符串，切忌不要直接把Date日期对象返回给客户端！

// ======后端代码========
// 获取当前默认时间
Date beginDate = setHalfMinite();
Date endDate = Datetimes.addMinute(beginDate, 30);
// Bad code:如下参数如果需要返回给前端，绝对绝对不要使用Date对象传输，你服务器的日期跟客户端的日期很可能对不上
// result.put("beginTime",beginDate); // Bad code
// result.put("endTime",endDate); // Bad code
// 正确的实现如下：一定要通过Datetimes.format将日期Date对象转换为字符串输出给前端
result.put("beginTime",Datetimes.format(beginDate, Datetimes.datetimeStyle));
result.put("endTime",Datetimes.format(endDate, Datetimes.datetimeStyle));


<!-- 前端日期数据 -->
<form>
 <input name="beginTime" type="text" value="${beginTime}"/>
 <input name="endTime" type="text" value="${endTime}"/>
</form>


> 再次提醒：从后端服务器向前端传输日期数据时，请务必使用字符串传输，不要使用Date对象传输！


## 无需时区场景

那么，我们有的应用却是无需进行时区转换，客户端到服务器端传输保存都使用相同日期，则可以使用如下代码实现：

// 字符串不带时区转Date  
Date date = Datetimes.parseNoTimeZone(dateStr, pattern)  
// Date不带时区转字符串  
String str = Datetimes.formatNoTimeZone(date, pattern)



## 时区实现原理

下面是时区的实现原理，方便后续集成接入使用。特别提醒：如果要做第三方登录到V5协同的开发，并且客户在全球办公，需要按照实现原理自行封装多时区能力。

以标准PC登录为例：

1、默认登录页（/seeyon/main/login/default/login.jsp）包装了时区的input参数，可自行查看login.jsp源代码。

其实现作用是：在点登录按钮的时候，通过Javascript调用获取客户端的时区值，将参数放到id="timezone"这个input元素中，通过form提交的形式将时区参数提交到服务器后端。

<form method="post" action="${path}/main.do?method=login" id="login_form" name="loginform" onsubmit="checkPwdStrength();">
  <input id="timezone" type="hidden" name="login.timezone" value=""/>
  ....
</form>
<script type="text/javascript">
    function loginSubmit(){//登录操作
      var timeZoneId = getTimeZoneId();
      $("#timezone").val(timeZoneId);
    }

    function getTimeZoneId(){
     //获取客户端时区
     var d = new Date();
     var timezoneOffset = 0 - d.getTimezoneOffset();
     var gmtHours = (timezoneOffset/60).toString();
     //8  -8:30  8:45
     var gmtHoursArr = gmtHours.split(".");
     var h = gmtHoursArr[0];
     if(h>=0){
      h = "+"+h;
     }
     var m = "00";
     if(gmtHoursArr.length>1){
      m = Number("0."+gmtHoursArr[1]) * 60;
     }
     return  "GMT"+h+":"+m;
    }
</script>


2、服务器登录会调用loginControl.transDoLogin(request, session, response)这个接口，在加密狗中会从request中取到timezone，再将其放入User全局变量中。

transDoLogin(HttpServletRequest request){
  // V8.X已经将此段代码放入加密代码中
  User user = AppContext.getCurrentUser();
  user.setTimeZone(TimeZone.getDefault());
  String timeZone = request.getParameter("timeZone");
  if(Strings.isNotBlank(timeZone)){
    TimeZone tz = TimeZone.getTimeZone(timeZone);
      if(null!=tz && TimeZoneUtil.isEnable()){
        user.setTimeZone(tz);
      }
   }
}


3、Datetimes调用时区转换的实现原理，其实就是判断isTimeZoneEnable()==true（对应前面插件和开关，把时区打开），则调用getCustomerTimeZone()获取当前时区的方法。

public static Date parse(String dateStr, TimeZone timeZone, String pattern){
  /** 加入时区  */
  if(null == timeZone){
   if(isTimeZoneEnable()){
    timeZone = getCustomerTimeZone();
   }else{
    timeZone = TimeZone.getDefault();
   }
  }
}


4、层层往下，getCustomerTimeZone获取自定义时区，实际就是从当前登录人员的getTimeZone()封装中获取的值。

private static TimeZone getCustomerTimeZone() {  
    //时区转换以所在客户端时区为准（默认）,  
    int transTimezoneType = TRANSTIMEZONE_BY_CUSTSET;  
    if(transTimezoneType==TRANSTIMEZONE_BY_PRIVSET){  
     return getTimeZoneByPrivSet();  
    }  
    return getTimeZoneByCustSet();  
   }   

   public static TimeZone getTimeZoneByCustSet(){  
    if(null != AppContext.getCurrentUser() && isEnable()){  
     return AppContext.getCurrentUser().getTimeZone();  
    }
    return TimeZone.getDefault();  
    }


总结：如果涉及第三方登录到V5系统，并且要做时区集成的话，就要保障：

1）调用Login登录的时候，将本地时区通过?timezone=xxx传到后端

2）后端统一登录逻辑通过request.getParameter("timeZone");获取到时区变量，将其封装到User对象中

3）登录之后，User对象中一直保存有时区参数，并且保存在服务器端会话中，后续操作别的功能都不需要再传时区变量。


## 追加内容

[年-月-日 时:分:秒] 这种显示日期格式在国内是通用显示标准，但在美国、英国等国家的日期显示一般是“月/日/年”的形式。

而我们的代码又清一色使用“yyyy-MM-dd HH:mm”这种固定的日期格式，会导致国外不适用。这个是目前已知的问题，因为国外需求量极少，所以此问题未放入优先处理范围内。

如果有国外类似需求的用户，我们有二次开发建议方案：

1）基于国际化多语言的形式维护不同语言的日期显示格式 2）不使用Datetimes工具类（改用com.seeyon.ctp.report.engine.util.DateFormatUtil），或重写Datetimes工具类

代码实现原理是：通过国际化方案，给不同登录的国际化语言配置不同的日期显示格式：

## datetimes_zh_CN
datetimes.format.yyyyMMddHHmmss = yyyy-MM-dd HH:mm:ss
## datetimes_zh_TW
datetimes.format.yyyyMMddHHmmss = yyyy-MM-dd HH:mm:ss
## datetimes_en
datetimes.format.yyyyMMddHHmmss = MM/dd/yyyy HH:mm:ss


代码上依然调用工具类的format、parse方法：

public static String format(Date date, FormatType formatType) {
 return format(date, formatType, null);
}


而底层实现则是根据当前登录人员所选择的登录显示语言去找对应的日期国际化显示格式：

public static String format(Date date, FormatType formatType, TimeZone timeZone, Locale... locale) {
  if (formatType == null || date == null) {
   return "";
  }
  Locale toLocale;
  if (locale != null && locale.length > 0) {
   toLocale = locale[0];
  } else {
   toLocale = AppContext.getLocale();
  }
  return formatters.get(formatType).format(date, toLocale, timeZone, formatType);
 }


此问题的开发工作量不止在后端，前端的日期组件也需要修改，所以二次开发的时候务必要评估全面。

编撰人：het、admin




快速跳转



 * 日期和多时区
   * 时区案例
   * 技术如何实现
   * 前提准备
   * 标准API
   * 时区编写示例
     * 客户端到服务器
     * 服务器到客户端
     * 无需时区场景
   * 时区实现原理
   * 追加内容



分享链接分享链接

## 33. EVENT事件监听

> 原始路径：`/39/80.html`  
> 相对路径：`39/80.md`

## EVENT事件监听

场景：开发需要做一个第三方组织机构同步集成功能，当系统内出现人员、部门、单位新增、修改、删除的时候，开发需要将这些信息同步给第三方，让第三方同步新增、修改、删除对应组织机构数据。

传统的做法是找到新增、删除、修改的源代码，在后面追加同步的代码，这种方式会侵入源码，耦合性极高。

CTP平台基于此问题，提供了一套事件分发和监听机制：组织机构开发在新增、修改、删除的代码位置封装推送一个Event对象，第三方集成只需监听这个Event对象，去实现数据同步即可。这种思路能降低代码耦合，提升可维护性。


## 实现原理

采用类似Observable+Observer模式，使用java.util.EventObject技术，并进行了简化开发。方案特点：注解驱动、无需注册监听、无需定义事件类型、异步分发、易扩展。




## 定义Event

下面以人员新增事件为例做Event事件开发演示。

标准产品侧，要触发事件则要先定义Event事件实例对象，实例如下，“人员新增”事件中存放了新增的人员对象V3xOrgMember：

public class AddMemberEvent extends Event {
	private static final long serialVersionUID = -5719181273255663176L;
	private V3xOrgMember member;
	private boolean isBatch = false;;

	public V3xOrgMember getMember() {
		return member;
	}
	public void setMember(V3xOrgMember member) {
		this.member = member;
	}
	public AddMemberEvent(Object source) {
		super(source);
	}
    public boolean isBatch() {
        return isBatch;
    }
    public void setBatch(boolean isBatch) {
        this.isBatch = isBatch;
    }
}



## 发布Event

标准产品侧，当执行人员新增逻辑的时候，就需要封装AddMemberEvent对象并通过fireEvent将事件发布出去：

    public void addMembers(List<V3xOrgMember> members) throws BusinessException {
        for (V3xOrgMember v3xOrgMember : members) {
            try {
                // 实例化Event对象
                AddMemberEvent event = new AddMemberEvent(this);
                // 传入必要的参数
                event.setMember(v3xOrgMember);
                // 分发Event事件，此步动作发送之后，外部即可监听
                EventDispatcher.fireEvent(event);
            } catch (Exception e) {
                log.error("AddMemberEvent error:"+v3xOrgMember.getName(),e);
            }
        }
    }


发布时机&发布类型：

## 立即触发事件，出现异常也不抛出，只记录日志
EventDispatcher#fireEvent

## 立即触发事件，出现异常时会抛出异常，供发出者捕获
EventDispatcher#fireEventWithException

## 事务提交成功后才触发，事务回滚则不触发
EventDispatcher#fireEventAfterCommit



## 监听Event

“定义Event”和“发布Event”是标准产品侧实现的代码，只要完成了事件的发布，标准产品侧就不需要再做别的事情。

下面就是需求方的任务，需求方需要在自己的业务类中（或者单独新增一个Listener）来监听Event事件，示例如下：

public class WeixinOrganizationListener {

    private DingdingManager dingdingManager;

    private FeishuManager feishuManager;

    public void setDingdingManager(DingdingManager dingdingManager) {
        this.dingdingManager = dingdingManager;
    }

    public void setFeishuManager(FeishuManager feishuManager) {
        this.feishuManager = feishuManager;
    }

    @ListenEvent(event = AddMemberEvent.class, async = true)
    public void addMember(AddMemberEvent event) {
        V3xOrgMember member = event.getMember();
        WeixinUtil.syncMember(member, "add");
        dingdingManager.syncMemberDing(member, "add");
        feishuManager.syncMember(member, "add");
    }

    @ListenEvent(event = UpdateMemberEvent.class, async = true)
    public void updateMember(UpdateMemberEvent event) {
        V3xOrgMember member = event.getMember();
        WeixinUtil.syncMember(member, "update");
        if (member.isValid()) {
            dingdingManager.syncMemberDing(member, "update");
            feishuManager.syncMember(member, "update");
        } else {
            dingdingManager.syncMemberDing(member, "del");
            feishuManager.syncMember(member, "del");
        }
    }
}


用于事件监听的类需要通过插件化开发的方式注册到Spring容器中：

<bean id="weixinOrganizationListener" class="com.seeyon.apps.weixin.listener.WeixinOrganizationListener" />


关于注解@ListenEvent：其定义信息如下：

@Documented
@Retention(RetentionPolicy.RUNTIME)
@Target({ ElementType.METHOD/*, ElementType.TYPE */})
@Inherited
public @interface ListenEvent {
 /**
  * 监听的事件类型。
  * 
  * @return 监听的事件类型。
  */
 Class event();
 /**
  * 执行模式，同步或异步。为true时异步（asynchronous）执行，为false时同步（synchronization）执行。缺省为false。
  * @return 执行模式。
  */
 boolean async() default false;
 /**
  * 事件触发模式，如不指定，则立刻触发。
  * <color>不推荐使用：如果需要立即执行，请将async=false</color>
  * @return 事件触发模式。
  */
 @Deprecated
 EventTriggerMode mode() default EventTriggerMode.immediately;
 /**
  * <description>顺序(越小越在前面)</description>
  *
  * @return
  * @author: ouyp
  * @since: Seeyon V7.1
  * @date: 2019年1月10日 下午4:15:25
  */
 int order() default 0;
}


> 如无特殊需要，我们一概建议异步执行监听：设置async参数为true！


## 产品标准Event接口

详见SeeyonAPI Event事件部分：https://open.seeyoncloud.com/seeyonapi/8.2/event/


## 常见问题

1）Listener获取不到AppContext.currentUser()

用户掉线或离线状态、或者你当前是异步线程执行。

编撰人：het、admin




快速跳转



 * EVENT事件监听
   * 实现原理
   * 定义Event
   * 发布Event
   * 监听Event
   * 产品标准Event接口
   * 常见问题



分享链接分享链接

## 34. HTTP304缓存

> 原始路径：`/39/81.html`  
> 相对路径：`39/81.md`

## HTTP304缓存

本文Etag的简介和作用大量摘抄自知乎：ETag简介与作用

ETag是URL的tag，用来标示URL对象是否改变。这样可以应用于客户端的缓存：服务器产生ETag，并在HTTP响应头中将其传送到客户端，服务器用它来判断页面是否被修改过，如果未修改返回304，无需传输整个对象。

页面渲染速度大头取决于：静态文件下载速度和动态请求返回速度。通过Fiddler或浏览器F12开发者工具能够看到每个页面的加载情况。

对于css、静态图片、js文件这类请求文件，第一次访问页面之后都会被浏览器缓存以提升二次访问效率。

对于后台请求，默认不会缓存，而有的后端数据经常几小时、几天都无变化，如果被高频访问，就白白浪费服务器资源。Etag就是用来解决这类长期无数据更新的后台请求的，使用Etag机制之后即使访问后台也不返回数据，数据都从浏览器缓存处获取。




## ETag的作用

HTTP1.1用ETag来判断请求的文件是否被修改，主要为了解决Last-Modified无法解决的一些问题

1、一些文件也许会周期性的更改，但是他的内容并不改变(仅仅改变的修改时间)，这个时候并不希望客户端认为这个文件被修改了重新GET;

2、某些文件修改非常频繁，1秒内修改了N次，If-Modified-Since能检查到的粒度是秒级的，这种修改无法判断

3、某些服务器不能精确的得到文件的最后修改时间；

为此，HTTP1.1引入了ETag。但标准并没有规定ETag的内容是什么或者说要怎么实现，唯一规定的是ETag需要放在双引号内。ETag由服务器端生成，客户端通过If-Match或者说If-None-Match这个条件判断请求来验证资源是否修改。我们常见的是使用If-None-Match。


## Etag缓存示例

请求一个后台数据的流程如下：

第一次请求：

1）客户端发起HTTP get请求一个文件

2）服务器处理请求，返回文件内容和一堆Header，当然包括ETag(例如"1ec5-502264e2ae4c0")(假设服务器支持ETag生成和已经开启了ETag).状态码200，如下图所示



第二次请求：

1）客户端发起HTTP GET请求一个文件，这个时候客户端同时发送一个If-None-Match头，这个头的内容就是我们第一次请求时服务器返回的ETag：1ec5-502264e2ae4c0

2）服务器判断发送过来的ETag和计算出来的ETag是匹配的，不返回200，返回304，让客户端继续使用本地缓存。

> 返回200是：服务器返回结果数据+返回HTTP200状态码返回304是：服务器返回空的结果数据+返回HTTP304状态码，浏览器识别到304之后从浏览器本地缓存提取上次的数据使用




## 入门实现案例

Etag缓存所有代码只需要在后端Controller层完成，平台提供了WebUtil.checkEtag和WebUtil.writeETag的封装来简化开发难度。

下面是最简单的Etag实现方式：

 /***
   * 模拟场景：此方法用于返回当前登录用户指定月份的薪资，我们知道薪资发放入库之后一般都不会变化了。
   * 所以如果当前用户调用过指定月份的薪资数据之后，我们就可以打一个Etag标记，后续就不会再发送请求。
   */
  int year = ReqUtil.getInt(request, "year");
  int month = ReqUtil.getInt(request, "month");
  User user = AppContext.getCurrentUser();
  // 假设每个月薪资
  String eTag = String.format("B-%d-%d-%d", user.getId(),year,month);
  
  try {
   // 校验request的If-None-Match是否与服务器生成的一致，如果一致则说明此前已经请求过，直接返回null。
   // PS:WebUtil.checkEtag方法内会自动返回HTTP304
   if(WebUtil.checkEtag(request, response, eTag)){
    return null;
   }
  } catch (IOException e) {
   logger.error("",e);
  }
  
  List result = dataManager.find(user,year,month);
  
  if(CollectionUtils.isNotEmpty(result)){
   // 如果有指定月份的薪资数据，则向浏览器写入当前的ETag，下次浏览器再将ETag带回来做对比
   // 最后一个参数是Etag有效期，默认定缓存30天
   WebUtil.writeETag(request, response, eTag, 1000L * 60 * 60 * 12 * 30);   
  }
  
  return result;



## 增强实现案例

上面是最简单的Etag实现方式，上面的Etag前提是：某人指定年月的薪资100%确认并且永远不会更改了，我们就可以基于“人员ID-年-月”来做Etag标记。而现实场景，我们很多数据可能出现二次更新的情况，比如第一次录入薪资错误了，次月又重新更新了数据。如果我们用上面那种Etag就会导致，数据一直是录入错误的薪资，即使更新了数据库，前端也看不到正确数据。

基于以上问题，平台封装了ETagCacheManager组件来统一管理ETag时间戳，ETagCacheManager的方法只有三个，非常简单实用。

public interface ETagCacheManager {

    /**
     * 根据分类和key获取最后修改时间戳
     * 
     * @param category 分类标识<br>
     *          如：SECTION,记录栏目属性发生变化<br>
     *          如：BUL_TYPE,记录公告板块下数据发生变化<br>
     *          如：BUL_USER,记录用户阅读情况发生变化<br>
     * @param key
     *      如：entityId,栏目ID<br>
     *      如：typeId,公告板块ID<br>
     *      如：userId,人员ID<br>
     * @return
     */
    public Long getETagDate(String category, String key);

    /**
     * 根据分类和key更新时间戳
     * 
     * @param category 分类标识<br>
     *          如：SECTION,记录栏目属性发生变化<br>
     *          如：BUL_TYPE,记录公告板块下数据发生变化<br>
     *          如：BUL_USER,记录用户阅读情况发生变化<br>
     * @param key
     *      如：entityId,栏目ID<br>
     *      如：typeId,公告板块ID<br>
     *      如：userId,人员ID<br>
     */
    public void updateETagDate(String category, String key);

    /**
     * 根据分类清除所有时间戳（如大变动，需要清除整个分类下时间戳）
     * 
     * @param category 分类标识
     */
    public void clearCategoryETagDate(String category);

}


基于上面场景，我们的实现可以修改为：

  int year = ReqUtil.getInt(request, "year");
  int month = ReqUtil.getInt(request, "month");
  User user = AppContext.getCurrentUser();
  // 假设每个月薪资
  String eTagKey = String.format("B-%d-%d-%d", user.getId(),year,month);
  
  ETagCacheManager eTagCacheManager = (ETagCacheManager) AppContext.getBean("eTagCacheManager");
  Long eTag = eTagCacheManager.getETagDate(ApplicationCategoryEnum.hr.name(), eTagKey);
  
  try {
   // 校验request的If-None-Match是否与服务器生成的一致，如果一致则说明此前已经请求过，直接返回null。
   // PS:WebUtil.checkEtag方法内会自动返回HTTP304
   if(eTag != null && WebUtil.checkEtag(request, response, String.valueOf(eTag))){
    return null;
   }
  } catch (IOException e) {
   logger.error("",e);
  }
  
  List result = dataManager.find(user,year,month);
  
  if(CollectionUtils.isNotEmpty(result)){
   eTagCacheManager.updateETagDate(ApplicationCategoryEnum.hr.name(), eTagKey);
   eTag = eTagCacheManager.getETagDate(ApplicationCategoryEnum.hr.name(), eTagKey);
   // 如果有指定月份的薪资数据，则向浏览器写入当前的ETag，下次浏览器再将ETag带回来做对比
   // 最后一个参数是Etag有效期，默认定缓存30天
   WebUtil.writeETag(request, response, String.valueOf(eTag), 1000L * 60 * 60 * 12 * 30);   
  }
  
  return result;


另外，要注意，在薪资进行修改的业务类中，也需要更新ETag时间戳，这样才能保证我们的数据是最新的：

 public void updateSalary() {
  dataManager.updateSalary(user.getId(),year,month,data);
  String eTagKey = String.format("B-%d-%d-%d", user.getId(),year,month);
  ETagCacheManager eTagCacheManager = (ETagCacheManager) AppContext.getBean("eTagCacheManager");
  Long eTag = eTagCacheManager.getETagDate(ApplicationCategoryEnum.hr.name(), eTagKey);
  if(eTag != null) {
   //
   eTagCacheManager.updateETagDate(ApplicationCategoryEnum.hr.name(), eTagKey);
  }
 }



## 常用案例-栏目

一个空间下有多个栏目，每个栏目都要请求不同的业务数据，如果配置的栏目过多，页面渲染速度就会降低。基于此问题，门户在Section中封装了getLastModify方法来做Etag被标记。

下面是一个典型是栏目示例：

各业务Setion需要重写getLastModify方法，组装自己的ETag格式，空间栏目组件会优先调用getLastModify看下是否与浏览器ETag一致，如果一致则不调用业务的查询数据方法，而是直接返回304。

如果业务数据发生变化，则栏目数据要更新，各业务可以通过eTagCacheManager.updateETagDate来更新ETag时间戳。下面这个业务代码利用了Spring切面能力来更新ETag，也是一个无侵入的好方法。

public class RelevanceProjectSetion extends BaseSectionImpl {
 private static final Log logger = CtpLogFactory.getLog(RelevanceProjectSetion.class);
    
 private ETagCacheManager eTagCacheManager;

 public void seteTagCacheManager(ETagCacheManager eTagCacheManager) {
  this.eTagCacheManager = eTagCacheManager;
 }
 
    @Override
 public Long getLastModify(Map<String, String> preference) {
  return eTagCacheManager.getETagDate(ProjectContants.PROJECT_SECTION_ETAG,ProjectContants.PROJECT_SECTION_ETAG);
 }
    
    /**
     * 利用平台的AOP切面监听如下方法，只要以下任何方法被执行，则触发projectChangeEvent方法
     */
    @After({
     "/project/project.do.orderProject",
     "/project/project.do.saveProject",
     "/project/project.do.setPhase",
     "/project/project.do.updateProject",
     "/project/project.do.doImport",
     "/project/project.do.saveProjectType",
     "/project/project.do.updateProjectType",
     "projectConfigManager.updateProjectOrder",
     "projectConfigManager.deleteProject",
     "projectAjaxManager.saveProjectMark",
     "projectAjaxManager.deleteMarkProjectById",
     "projectAjaxManager.updataProjectByField",
     "projectAjaxManager.saveCustomViewType"
    })
    public void projectChangeEvent(){
     // 当项目出现增、删、改，则说明数据发生变化，需要进行Etag时间戳更新
     eTagCacheManager.updateETagDate(ProjectContants.PROJECT_SECTION_ETAG,ProjectContants.PROJECT_SECTION_ETAG);
    }
}


编撰人：het、admin


快速跳转



 * HTTP304缓存
   * ETag的作用
   * Etag缓存示例
   * 入门实现案例
   * 增强实现案例
   * 常用案例-栏目



分享链接分享链接

## 35. 加密解密

> 原始路径：`/39/82.html`  
> 相对路径：`39/82.md`

## 加密解密

本文档对V8.1及更高版本有效，自V8.1版本开始，平台对加解密进行了升级，以下是对新算法的说明！


## 修订记录

修订内容                                修订时间
完善传输加密章节内容（内部关联单号JSFW-2024-02672）   2024年12月


## 功能简介

标准产品主要做了3次大的算法升级（或新增）：

 * 第一次升级：V8.1针对数据存储加解密算法进行了升级，由旧的国际算法升级为“新国际算法”、“国密算法”、“加密机算法”三选一，以满足不用客户需求。
 * 第二次升级：V8.1SP1针对部分隐私数据增加了加密传输算法，以满足基本的加密传输合规性
 * 第三次升级：V9.0SP1针对OA管理的用户名密码，在pc、移动、微协同等多端新增了登录密码加密传输Hash算法，以满足基本的登录加密传输合规性


## Ⅰ数据保护范围（since V8.1）

第一次升级：V8.1数据存储加解密升级，废弃了老旧的SHA-1、DES算法，升级为更安全的新算法。

除此之外，还扩展了数据存储加密领域，让更多关键数据支持加密存储，主要完成以下变化：

算法|业务              密码|数据签名   附件        日志        用户隐私信息    正文
旧国际算法（8.0SP2及更早）   SHA-1     DES       无         无         无
新国际算法（8.1以后三选一）    SHA-256   AES-128   AES-128   AES-128   AES-128
内置国密算法（8.1以后三选一）   SM3       SM4       SM4       SM4       SM4
加密机算法（8.1以后三选一）    三未信安SM3   三未信安SM4   三未信安SM4   三未信安SM4   三未信安SM4
中度加密算法（适用所有版本）               异或算法                          

注：加密机算法依赖三方密码机设备，需采购对应型号密码机集成才能生效，详细见对应版本的发版文档-安装维护手册-外接国密加密机（三未信安）配置手册。

数据保护即指定敏感数据加密存储到数据库。敏感数据在写入和读取时存在加解密操作，故加密数据比不加密数据更耗时，请根据安全保密级别按需开启加密控制。

数据保护范围内容有：密码、附件、正文、隐私信息（用户身份证号、办公电话、手机电话、电子邮箱等文本）、应用日志、数据完整性校验、工资。

随着产品持续发展，用户需求的变化，数据保护范围也会相应变化扩大，不同版本支持的范围可能存在差异性。数据保护范围全部可配置，通过系统管理员角色查看和配置加密范围：安全管理>数据保护>数据加密做个性化配置！

注意：当系统管理员通过后台修改了全局的密码存储加密算法（例如，从国际算法切换为国密算法）后， 历史已产生的加密数据不会自动切换为新加密方式 ，而是保持原样，只有历史数据被修改时，才会更新为新加密方式。

 * 用户密码加密：只有当用户主动修改密码或首次登录时被系统强制要求重置密码时，系统才会使用新的算法来加密并存储新密码。
 * 数据存储加密：对于用户隐私信息（如身份证、手机号）等数据的存储加密方式变更，其规则类似。已存在的、用旧算法加密的数据仍保持原状。只有在这些数据被新建或修改时，系统才会按照当前配置的新算法进行加密后重新存储。
 * 这样的设计确保了系统在提升安全性的同时，保持对历史数据的兼容和平滑过渡。



----------------------------------------

关于表单数据加密，标准产品无法做存储加密，主要原因是表单字段存在多样化，全面加密后，即时加密和即使解密能力都会遇到巨大瓶颈，系统体验就是加载慢、卡，故不适合做大面积加密。如有需求，可报成本，走项目化开发支持。


## Ⅱ加密传输（since V8.1SP1）

第二次升级：V8.1SP1针对部分隐私数据增加了加密传输算法，以满足基本的加密传输合规性。

应用价值：在等保/分保/密评合规要求中，需要保障重要业务数据、个人敏感信息存储、传输的机密性和完整性要求，标准产品提供了加密传输的功能和接口能力。

功能特性：传输机密性，传输（从前端浏览器、M3、等传到后台）要加密传输，传输完整性：验签。

依赖插件：分保插件。

标准化支持内容：人员信息敏感字段(办公电话、手机号码、电子邮件)，在传输过程中数据通过加密传输，防止被拦截破解。

功能开关位置：通过系统管理员角色访问：安全管理>数据保护>加密传输。传输默认关闭。



传输加解密的运行逻辑图如下，关键逻辑为：

 * 客户端在发送关键数据时，先从服务器获取国密SM2公钥（该算法专用于快速生成密钥）
 * 客户端再使用SM2颁发的公钥结合客户端SDK进行加密，将加密后的密文传输到服务器
 * 服务器同步解密获得正确的数据，再处理后续业务逻辑



全过程涉及加、解、完整性校验等多个操作，详细流程图如下：




## Ⅲ登录密码加密传输算法增强（since V9.0SP1）

第三次升级：V9.0SP1针对登录时用户密码增加了加密传输算法，以满足基本的登录密码加密传输合规性。

应用价值：采用hash不可逆算法，在OA进程内和数据库内不可反解用户密码，保证了用户密码最高安全性。

算法简述：

 * 核心加密算法：SM3+SHA256 组合哈希（hash_login）：客户端侧对密码执行SM3 国密哈希算法 + SHA256 国际哈希算法的组合哈希运算（该组合过程简称为 hash_login），利用 SM3 的国密级安全特性与 SHA256 的高抗碰撞性形成算法互补，输出固定长度哈希值替代明文密码传输，结合动态种子加盐后，实现 “密码 + 专属一次性盐值” 的组合哈希，大幅提升暴力破解难度。
 * 动态加盐机制：一次性专属种子防重放 / 彩虹表攻击：在进行上面加密关键步骤会进行加盐以进一步提升破解难度，盐值由前后端协同提供一次性种子实现，种子为加密盐值核心载体，使用后立即清空废弃，防止重放复用。
 * 多端种子隔离：实现了PC浏览器、移动端（M3）、微协同、致信等多端传输加密，且各端一次性种子隔离，彻底防止A端种子到B端冒用问题。

出于加密算法安全，密码加密传输仅提供以上说明。


## 扩展阅读：关于国密

本次主要是引入国密算法（中华人民共和国自主知识产权的数字密码学算法），简介如下：

国密即国家密码局认定的国产密码算法。主要有SM1，SM2，SM3，SM4。密钥长度和分组长度均为128位。

 * SM1 为对称加密。其加密强度与AES相当。该算法不公开，调用该算法时，需要通过加密芯片的接口进行调用。
 * SM2为非对称加密，基于ECC。该算法已公开。由于该算法基于ECC，故其签名速度与秘钥生成速度都快于RSA。ECC 256位（SM2采用的就是ECC 256位的一种）安全强度比RSA 2048位高，但运算速度快于RSA。
 * SM3 消息摘要。可以用MD5作为对比理解。该算法已公开。校验结果为256位。类似算法还有SHA。
 * SM4 无线局域网标准的分组数据算法。对称加密，密钥长度和分组长度均为128位。

由于SM1、SM4加解密的分组大小为128bit，故对消息进行加解密时，若消息长度过长，需要进行分组，要消息长度不足，则要进行填充。


## 技术使用说明


## 部分算法示意图

## 摘要算法示意图

默认采用SM3，常用于密码存储。



## 对称加解密算法示意图

密钥长度32位，采用ecb模式加密，默认使用SM4，常用于日志、正文、隐私信息存储（查看时解密）。




## Ⅰ加解密接口

业务需求是通过系统配置可以自由的切换加密算法。为了达到高内聚的效果，我们将通过开关切换算法的逻辑添加到平台内。业务只需要通过工厂方法获取算法接口的实现即可。

平台只提供加密/解密/加签/验签能力，其中凭证ID即为加签操作返回的签文，主要支持对称加密算法（如：SM4）和哈希算法（如：SHA-1\SM3）前者是可逆操作如：加密用户身份信息、文件等，后者不可逆如：用户密码、凭证校验。

> 如果你不知道加密、解密、加签、验签，建议先学习相关概念再往下看。

EncryptCoder具体方法如下:

方法名称             传入参数                          返回参数                说明
encrypt          byte[]                        byte[]              文件的加密方法，传入文件的byte数组返回加密后的byte数组，byte[]可用通过InputStream().getBytes()获取
encrypt          String                        String              字符串类型的加密方法，传入字符串明文，返回加密后的字符串密文
encrypt          Double data：待加密数字             Double              浮点树的加密方法采用混淆算法，传入待加密的浮点数data和参与混肴的数字盐往往是用户的id
                 long seed：参与混肴的数字盐
decrypt          byte[] ciphertext：带解密的密文数组    byte[]：解密后的明文字节数组   文件类型的解密方法，传入加密文件的字节数组，返回解密后文件的字节数组
decrypt          String ciphertext：待解密的密文字符串   String：解密后的明文串      字符串类型的解密方法，传入加密的字符串，返回解密后的明文字符串
decrypt          Double data：待解密数字             Double：解密后的数字       数字类型的解密方法，参数带解密的数字，混肴的数字盐以及保留的小数位，返回解密后的数字
                 long seed：参与混肴的数字盐
                 int decimal：保留的小数位
signature        byte[] data：待加签的文件字节数组        String：加签的签文        文件类型的加签方法，传入文件的字节数组吗，返回前文字符串(凭证Id)，长度稳定为44个字符
signature        String data：签名的字符串            String：加签的签文        字符串类型的加签方法，传入待签名字符串以及签名的盐（此参数保证同样的字符处理后的签文不一致），返回签文
                 String seed：参与签名算法的盐，非必需
signatureCheck   byte[] data：验签数据              boolean：true-验证成功   文件类型验签方法，传入做签名的文件字节数组和签文，返回验证结果
                 String signature：签文           false-验证失败
signatureCheck   String data：签名的字符串            boolean：true-验证成功   字符串类型验签方法，传入做签名的字符串和签文，返回验证结果
                 String seed：参与签名算法的盐，非必需      false-验证失败
                 String signature：签文

EncryptCoder接口源码：

public interface EncryptCoder {
	/**
	 * 加密文件类型的二进制数据
	 *
	 * @param data 待加密明文
	 * @return 加密后密文
	 */
	byte[] encrypt(byte[] data) throws CoderException;


	/**
	 * 加密字符串
	 *
	 * @param data 待加密明文
	 *             具体的加密操作：正文/附件/日志等
	 * @return
	 */
	String encrypt(String data) throws CoderException;

	/**
	 * 加密小数
	 *
	 * @param data 待加密数字
	 * @param seed 参与混肴的盐，通常是用户id
	 * @return
	 * @throws CoderException
	 */
	Double encrypt(Double data, long seed) throws CoderException;


	/**
	 * 解密数据 文件
	 *
	 * @param ciphertext 密文
	 * @return 解密后明文
	 */
	byte[] decrypt(byte[] ciphertext) throws CoderException;

	/**
	 * 解密数字
	 *
	 * @param ciphertext 待解密数字
	 * @param seed       参与混肴的盐，通常是用户id
	 * @param decimal    保留的有效小数位
	 * @return
	 * @throws CoderException
	 */
	Double decrypt(Double ciphertext, long seed, int decimal) throws CoderException;

	/**
	 * 解密数据 字符串
	 *
	 * @param ciphertext 密文
	 * @return 解密后的明文串
	 */
	String decrypt(String ciphertext) throws CoderException;


	/**
	 * 文件类型加签
	 *
	 * @param data 待签名的原始数据
	 * @return 签名字符串
	 */
	String signature(byte[] data) throws CoderException;

	/**
	 * 文件验签
	 *
	 * @param data
	 * @param signature
	 * @return
	 */
	boolean signatureCheck(byte[] data, String signature) throws CoderException;

	/**
	 * 字符串签名
	 *
	 * @param data 签名数据
	 * @param seed 盐 保证同样字符串签名后的密文不一样之前是用户的用户登录名加密
	 * @return
	 */
	String signature(String data, String seed) throws CoderException;

	/**
	 * @param data       待签名数据
	 * @param signature 签名后的密文
	 * @param seed       盐 保证同样字符串签名后的密文不一样
	 * @return
	 */
	boolean signatureCheck(String data, String signature, String seed) throws CoderException;
}


目前提供的EncryptActionEnum如下：

	/**
	 * 加密密码
	 */
	ENCRYPT_PWD(EncryptActionVO::getUserPassword),

	/**
	 * 加密附件
	 */
	ENCRYPT_ATTACHMENT(EncryptActionVO::getAttachment),

	/**
	 * 加密正文
	 */
	ENCRYPT_TEXT(EncryptActionVO::getText),

	/**
	 * 加密隐私信息：用户身份证号、办公电话、手机电话、电子邮箱等文本
	 */
	ENCRYPT_SECRECY(EncryptActionVO::getSecrecy),

	/**
	 * 加密应用日志
	 */
	ENCRYPT_APP_LOG(EncryptActionVO::getAppLog),

	/**
	 * 加密数据完整性校验
	 */
	SIGNATURE_DATA(EncryptActionVO::getSignatureData),

	/**
	 * 加密工资：数字
	 */
	ENCRYPT_SALARY(EncryptActionVO::getSalary),


## 加密、加签示例

加密加签时候通过 encryptCoderFactory.getByEncryptActionEnum获取到EncryptCoder。其中每个配置项都与EncryptActionEnum的枚举存在唯一对应关系，因此在做加密/加签操作时候需要传入EncryptActionEnum，平台会去读数据加密配置返回合适的EncryptCoder，如果设置为不加密会返回EncryptCoderEmptyImpl即do nothing(传入什么参数就返回什么参数)。

/**可逆加密身份证号码示例**/
EncryptCoderFactory encryptCoderFactory = EncryptCoderFactory.getInstance();
//身份证属于隐私信息对应ENCRYPT_SECRECY
EncryptCoder encryptCoder = encryptCoderFactory.getByEncryptActionEnum(EncryptActionEnum.ENCRYPT_SECRECY);
//调用encrypt方法加密身份证信息
String encrypt = encryptCoder.encrypt("5132118518445451851");


/**不可逆对用户密码生成签名示例**/
EncryptCoderFactory encryptCoderFactory = EncryptCoderFactory.getInstance();
//用户密码对应操作枚举ENCRYPT_PWD
EncryptCoder encryptCoder = encryptCoderFactory.getByEncryptActionEnum(EncryptActionEnum.ENCRYPT_PWD);
//调用signature方法加密用户密码，加盐是为了保证即使输入一样的密码加密出来的密文也是不一致的
String encrypt = encryptCoder.signature("Seeyon999","username");


/**不可逆对文件生成摘要签名，用于对文件进行防窜改验证**/
//将文件转字节数组
byte[] fileBytes = IOUtility.toByteArray(new FileInputStream(file));
EncryptCoderFactory encryptCoderFactory = EncryptCoderFactory.getInstance();
//无论什么类型，只要是加签操作对应枚举为SIGNATURE_DATA
EncryptCoder encryptCoder = encryptCoderFactory.getByEncryptActionEnum(EncryptActionEnum.SIGNATURE_DATA);
//调用signature生成文件摘要
String encrypt = encryptCoder.signature(fileBytes);


## 解密、验签示例

由于平台加密算法是可配置的，支持不同加密算法的切换(国际通用算法->国密算法->加密机算法)，因此在解密/验签操作时候获取EncryptCoder的过程会略有不同。

解密时候通过encryptCoderFactory.getByEncryptActionEnum.getByCipher获取EncryptCoder。

/**可逆解密身份证号码示例，与前面加密配套使用**/
EncryptCoderFactory encryptCoderFactory = EncryptCoderFactory.getInstance();
//通过密文解析到做加密时候的算法实现
EncryptCoder decryptCoder = encryptCoderFactory.getByCipher(encrypt);
//解密数据
String decrypt = decryptCoder.decrypt(encrypt);


如果是验签操作同样是通过encryptCoderFactory.getByEncryptActionEnum.getByCipher获取EncryptCoder。

/**对用户密码验签示例，与签名密码加密配套使用**/
EncryptCoderFactory encryptCoderFactory = EncryptCoderFactory.getInstance();
//通过密文解析到做加签时候的算法实现
EncryptCoder decryptCoder = encryptCoderFactory.getByCipher(signature);
//验签数据，true为通过，false为不通过
boolean result = decryptCoder.signatureCheck("Seeyon999",signature,"username");


/**对文件进行验签示例，用于验证文件是否被窜改**/
EncryptCoderFactory encryptCoderFactory = EncryptCoderFactory.getInstance();
//通过密文解析到做加签时候的算法实现
EncryptCoder decryptCoder = encryptCoderFactory.getByCipher(signature);
//验签数据，true为通过，false为不通过
boolean result = decryptCoder.signatureCheck(fileBytes,signature);



## Ⅰ加解密算法实现原理

目前的算法实现按照分类来说有：

 * 摘要算法：用于用户密码加密、生成数字签名（凭证id）；只可加密不可解密，它所谓的“解密”过程叫“验签”，即将加密后的内容“签文”与需要验证的数据拿去生成的数字签名做对比，如果两者内容一致着验签正确。
 * 对称加密算法：用于用户隐私信息、文件、日志等需要解密出明文的操作。加密/解密过程需要引入一把密钥，加密和解密都需要使用这把密钥才能成功进行。也就是看起来加密和机密过程密钥是一致的成为对称加密。这种加密方式适合只有一方系统内部信息的加密，不适合多个系统传输数据加密解密，因为密钥在传递和多个系统中存储增加丢失几率，对两边系统都产生安全风险。

## 摘要类算法实现方式

摘要算法采用了java自带的MessageDigest，只需要传入算法名称和算法发提供者获取实例，签名代码如下：

	@Override
	public String signature(byte[] data) throws CoderException {
		try {
            //算法名称为SM3，算法供应商provider=SwxaJCE(三位信安)，不传递第二个参数（provider）则使用jdk内置的算法
			MessageDigest messageDigest = MessageDigest.getInstance("SM3", "SwxaJCE");
            //加密数据
			messageDigest.update(data);
            //拿到加密结果
			byte[] output = messageDigest.digest();
            //获取该算法的标识内容
			byte[] headerMark = getHeaderMark();
            //将标识添加到签文头部返回最终结果
			return Base64.getEncoder().encodeToString(mergeBytes(headerMark, output));
		} catch (Exception e) {
			LOG.error(e);
			throw new CoderException("use MessageDigest signature failed!");
		}
	}


摘要类算法需要实现getHeaderMark、signature、signatureCheck几个方法即可。实例SHA-256算法实现如下：

public class EncryptCoderSha256 extends AbstractEncryptCoder {

	/**
	 * 日志
	 */
	private static final Log LOG = CtpLogFactory.getLog(EncryptCoderSha256.class);

	/**
	 * 算法名称
	 */
	private static final String ALGORITHM = "SHA-256";

	@Override
	byte[] getHeaderMark() {
		return str2Bytes(EncryptAlgorithmEnum.SYS_SHA256.getValue());
	}

	@Override
	public String signature(byte[] data) throws CoderException {
		try {
			MessageDigest digest = MessageDigest.getInstance(ALGORITHM);
			digest.update(data);
			byte[] output = digest.digest();
			return Base64.getEncoder().encodeToString(mergeBytes(getHeaderMark(), output));
		} catch (Exception e) {
			LOG.error(e);
			throw new CoderException(String.format("use MessageDigest[%s] signature failed!", ALGORITHM));
		}
	}

	@Override
	public boolean signatureCheck(byte[] data, String signature) throws CoderException {
		String current = signature(data);
		return Objects.equal(signature, current);
	}

	@Override
	public String signature(String data, String seed) throws CoderException {
		try {
			MessageDigest messageDigest = MessageDigest.getInstance(ALGORITHM);
			//seed不为空则将seed加入到摘要算法中
			if (Strings.isNotBlank(seed)) {
				byte[] seedBytes = messageDigest.digest(str2Bytes(seed));
				messageDigest.update(seedBytes);
			}
			byte[] output = messageDigest.digest(str2Bytes(data));
			return Base64.getEncoder().encodeToString(mergeBytes(getHeaderMark(), output));
		} catch (Exception e) {
			LOG.error(e);
			throw new CoderException(String.format("use MessageDigest[%s] signature failed!", ALGORITHM));
		}
	}

	@Override
	public boolean signatureCheck(String data, String signature, String seed) throws CoderException {
		String current = signature(data, seed);
		return Objects.equal(signature, current);
	}
}


指的注意的是，加签密码时候需要额外传入第二个参数seed，这是为了保证每位用户加签出来的密码都是独一无二的避免被暴力破解，因为密码的安全是系统安全的基础，即使别人得到的密码的密文也无法轻松破解出密码原文。

## 对称类算法实现方式

对称类算法主要用到Cipher通过通过其getInstance方法获取到算法，第一个参数为算法名称，第二参数如果传入则为算法的提供应商如SwxaJCE，计算过程通过doFinal或者update都可以，区别是doFinal是一次性运算、update则是批量多次运算每次都会返回运算的结果。由于需要密钥，因此在构造方法中需要指的密钥的初始化方式和密钥的获取方式。初始化方式是为了系统首次使用该算法时候生成并保该密钥，这样能保证每个OA客户端的每把密钥都是独一无二的。这类算法实现需要实现的方法有：getHeaderMark、encrypt、decrypt 。示例代码如下（AES-128实现）

public class EncryptCoderAESImpl extends AbstractEncryptCoder {

	/**
	 * 日志类
	 */
	private static final Log LOGGER = CtpLogFactory.getLog(EncryptCoderAESImpl.class);


	/**
	 * 算法名称
	 */
	private static final String ALGORITHM = "AES/ECB/PKCS5padding";

	/**
	 * 密钥号
	 */
	private static final String KEY_ID = "**";

	/**
	 * 系统内置的AES算法 加密专用
	 */
	private static Cipher AES_CIPHER_ENCODE;

	/**
	 * 系统内置的AES算法 解密专用
	 */
	private static Cipher AES_CIPHER_DECODE;


	@Override
	public byte[] getHeaderMark() {
		return str2Bytes(EncryptAlgorithmEnum.SYS_AES.getValue());
	}

	@Override
	public byte[] encrypt(byte[] data) throws CoderException {
		try {
			byte[] encode = AES_CIPHER_ENCODE.doFinal(data);
			return mergeBytes(getHeaderMark(), encode);
		} catch (Exception e) {
			LOGGER.error(e);
			throw new CoderException("AES encrypt string failed");
		}

	}

	@Override
	public String encrypt(String data) throws CoderException {
		try {
			byte[] encrypt = encrypt(str2Bytes(data));
			return Base64.getEncoder().encodeToString(encrypt);
		} catch (Exception e) {
			LOGGER.error(e);
			throw new CoderException("AES encrypt string failed");
		}
	}

	@Override
	public String decrypt(String ciphertext) throws CoderException {
		try {
			byte[] decode = Base64.getDecoder().decode(ciphertext);
			decode = removeHeader(decode);
			byte[] doFinal = AES_CIPHER_DECODE.doFinal(decode);
			return bytes2Str(doFinal);
		} catch (Exception e) {
			LOGGER.error(e);
			throw new CoderException("AES decrypt string failed");
		}
	}

	@Override
	public byte[] decrypt(byte[] ciphertext) throws CoderException {
		try {
			//去掉头
			ciphertext = removeHeader(ciphertext);
			//解密
			return AES_CIPHER_DECODE.doFinal(ciphertext);
		} catch (Exception e) {
			LOGGER.error(e);
			throw new CoderException("AES decrypt string failed");
		}
	}


	public String generateKey() throws CoderException {
		try {
			//生成key
			Security.addProvider(new BouncyCastleProvider());
			//生成key
			KeyGenerator keyGenerator=KeyGenerator.getInstance("AES", "BC");
			//AES>=128
			keyGenerator.init(128);
			SecretKey secretKey = keyGenerator.generateKey();
			byte[] key = secretKey.getEncoded();
			return Base64.getEncoder().encodeToString(key);
		} catch (Exception e) {
			LOGGER.error("init AES key-128 failed", e);
			throw new CoderException("init AES key-128 failed");
		}
	}


	/**
	 * 初始化内置的des算法
	 */
	public EncryptCoderAESImpl() throws CoderException {
		try {
			String secretKey = getSecretKey(KEY_ID, this::generateKey);
			//加密
			AES_CIPHER_ENCODE = Cipher.getInstance(ALGORITHM);
			byte[] keyBates = Base64.getDecoder().decode(secretKey);
			SecretKeySpec keySpec = new SecretKeySpec(keyBates, "AES");
			AES_CIPHER_ENCODE.init(Cipher.ENCRYPT_MODE, keySpec);
			//解密
			AES_CIPHER_DECODE = Cipher.getInstance(ALGORITHM);
			AES_CIPHER_DECODE.init(Cipher.DECRYPT_MODE, keySpec);
		} catch (Exception e) {
			LOGGER.error("init AES algorithm failed", e);
			throw new CoderException("init AES algorithm failed");
		}
	}
}



可以看到加密的cipher类和解密的cipher类是分开的，这是因为执行加密和解密cipher的执行模式是不一样的，为了保证线程安全以及性能将加密和解密的cipher分开。同事指定了生成key的方式，如果获取key(getSecretKey(KEY_ID, this::generateKey);)失败则会生成一把key并保存到数据库中。


## 其它代码


## SM2生成密钥代码




## Ⅰ登录密码传输加密hash算法使用

## 开关切换

开关默认为false，使用老的des加密。当切换为true后，重启oa，登录时候用户密码在登录客户端使用的是hash算法加密后，发送到OA后端。

## 明文密码传输场景支持

标准OA是禁止用户密码明文登录。但是考虑到老客户在有些场景（如工具测试）已经在使用明文密码传输。所以提供了配置开关，可以支持用户密码明文传输后登录 当选择为true，则打开开关，支持客户通过密码明文登录，同时需要客户在请求url参数中带上useClearPassword=1。 如如下 pc登录接口明文登录

对称类算法主要用到Cipher通过通过其getInstance方法获取到算法，第一个参数为算法名称，第二参数如果传入则为算法的提供应商如SwxaJCE，计算过程通过doFinal或者update都可以，区别是doFinal是一次性运算、update则是批量多次运算每次都会返回运算的结果。由于需要密钥，因此在构造方法中需要指的密钥的初始化方式和密钥的获取方式。初始化方式是为了系统首次使用该算法时候生成并保该密钥，这样能保证每个OA客户端的每把密钥都是独一无二的。这类算法实现需要实现的方法有：getHeaderMark、encrypt、decrypt 。示例代码如下（AES-128实现）


## 扩展阅读&常见问题

问题：我已经知道密码的加密算法，是否可以使用网上对应加密算法的破解工具来破解加密内容？

回复：公网工具无法破解。加密、解密、验签等操作均需要读产品中的代码，或调用产品中相关加解密代码才能实现。在进行加解密时，我们追加了一些影响因子，比如用户密码加密做了加盐操作，你得知道我们的盐是啥。

----------------------------------------

以下是研发过程中总结的笔记，方便后续开发接入新算法时参考。

Q1:如何兼容老数据？

将所有老算法通过抽取、提炼出`EncryptCoder`实现中，并配置相关算法枚举到`AlgorithmEnum`中，让老数据也能走新设计下的解密流程：将密文传入`EncryptCoderFactory`，通过解析密文开头标识在`AlgorithmEnum`中匹配到算法实现完成解密


Q2:如何解决多业务数据的加密，并保证一定的扩展性？

业务数据是否加密以及具体的加密算法是通过系统配置中度加密存储来控制的，也就是业务的加密算法的开关以及加密算法具体实现的联动是动态的，因此这部分内容是保存在数据库中的，而为了满足拓展性达需要设计成“动”、“静”分明的效果。

`动`是指的加密存储的配置项、每个加密业务操作的具体实现算法、以及扩展新加密业务的方式是变化的，这部分代码尽量设计成配置式。通过`actionEnum`绑定加密业务操作类型，通过`actionEnum`的枚举属性完成加密存储配置值的映射，以及每个业务加密操作的算法名称映射，最终实现业务通过`actionEnum`->获取算法开关配置&拿到算法名称id->通过`AlgorithmEnum`拿到算法实现。拓展新的业务数据加密操作时候只需要新增一个`actionEnum`以及对应新增`actionEnum`的算法映射配置到数据库即可完成拓展。

`静`是指的面向业务的核心代码是通用始终不变的，即`encryptFactory`工厂类的代码始终不会因为业务功能的拓展而被迫发生改变。因为`encryptFactory`的任意一行代码的修改都会影响所有适配的数据加密的业务，进而规避各种风险的产生。


Q3:如何一种业务数据采用不同加密算法的切换，具备一定的算法扩展性？

业务数据的加密算法切换以及开关控制是通过系统配置中度加密存储来配置的，业务在加密的时候只需要传入`actionEnum`，由平台去查询`actionEnum`对应映射的加密存储配置的算法以及开关的状态，如果加密操作选项为关闭状态则返回内置的`EmptyCoderImpl`这个算法实现中在加密/解密时候执行空操作，对于业务消费方是无感的。业务不需要写判断逻辑是控制数据是否需要加密由平台统一控制。解密时候`encryptFactory`会通过解析密文的头部数据反向查找匹配该信息的算法实现，这样就能保证算法切换后仍然能够成功的机密出来，因为加密密文中存储了算法信息。

因为采用动静分明的设计，扩展新算法时只需要实现`EncryptCoder`接口，并将算法实现添加到`AlgorithmEnum`，最后将替换掉数据库中`actionEnum`对应的算法映射关系数据即可。下次加密时候，通过`actionEnum`找到算法名称id，并在`AlgorithmEnum`中匹配到新的算法实现


Q4:如何支持大于一个加密厂商接入，并具备一定的新厂商接入扩展性？

加入加密的过程从编码层面看只是将算法替换为对于厂商的过程，使用的`java`类仍旧是`javax.crypto.*`下的类。因此本质上来说与扩展新的`jdk`自带国际算法是同样的过程，因此只需实现加密机厂商的算法实现并配置到`AlgorithmEnum`和系统配置文件中即可。
加密机的适配过程往往需要：
1.引入厂商扩展的jar到`jre/ext/lib`下
2.修改相关配置文件让`jdk`加载到扩展算法
3.配置厂商提供的配置文件将加密机的`ip`和密码保证连接的安全，因此能保证一定的扩展性


Q5:如何实现加密机厂商连接模拟测试

由于加密厂商的`sdk`并不会提供测试连接的`api`，并且配置的`ip`也是在`jdk`目录配置的，能`ping`通不一定能连接。因此在连接测试中编写了一段加密代码能成功执行则说明能执行成功并且在设定了线程超时时间，指定时间内未能执行完毕则视为连接失败


编撰人：het、zhuhui、admin


快速跳转



 * 加密解密
   * 修订记录
   * 功能简介
     * Ⅰ数据保护范围（since V8.1）
     * Ⅱ加密传输（since V8.1SP1）
     * Ⅲ登录密码加密传输算法增强（since V9.0SP1）
     * 扩展阅读：关于国密
   * 技术使用说明
     * 部分算法示意图
       * 摘要算法示意图
       * 对称加解密算法示意图
     * Ⅰ加解密接口
       * 加密、加签示例
       * 解密、验签示例
     * Ⅰ加解密算法实现原理
       * 摘要类算法实现方式
       * 对称类算法实现方式
   * 其它代码
     * SM2生成密钥代码
     * Ⅰ登录密码传输加密hash算法使用
       * 开关切换
       * 明文密码传输场景支持
   * 扩展阅读&常见问题



分享链接分享链接

## 36. LOG日志

> 原始路径：`/39/83.html`  
> 相对路径：`39/83.md`

## LOG日志


## 日志级别

日志记录器(Logger)是日志处理的核心组件，V5采用标准的log4j日志记录标准。log4j具有5种正常级别(Level)。

1. static Level DEBUG : DEBUG Level指出细粒度信息事件对调试应用程序是非常有帮助的,一般认为比较重要的方法执行需要详细查看运行情况的则开启debug。

2. static Level INFO INFO level表明消息在粗粒度级别上突出强调应用程序的运行过程，只需要了解该方法是否运行的可以使用INFO

3. static Level WARN WARN level表明会出现潜在错误的情形。

4. static Level ERROR ERROR level指出虽然发生错误事件，但仍然不影响系统的继续运行。一般异常处理等情况都需要ERROR

5. static Level FATAL FATAL level指出每个严重的错误事件将会导致应用程序的退出。

> ———————————————— 版权声明：遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。 原文链接：https://blog.csdn.net/m0_37179470/article/details/81238012


## 开发示例

记录Log日志前提，需要在当前类下注册Log全局变量，LOG日志记录代码如下：

public class ShowManagerImpl implements ShowManager {
    // 1、初始化logger
	private static final Log logger = CtpLogFactory.getLog(ShowManagerImpl.class);

	@Override
	public void deleteShowbarById(Long showbarInfoId) throws BusinessException, NotExistedException, NotAuthorizationException {
		ShowbarInfo showbarInfo = getShowbarByIdWithAuth(showbarInfoId);
		if (showbarInfo == null) {
            // 2、使用warn级别记录日志
			logger.warn("无权限或未找到对应主题:" + showbarInfoId);
			throw new NotExistedException();
		}
		if (hasShowbarAuth(ShowBarAuth.Delete, showbarInfo,isShowbarAdmin(AppContext.currentUserId(),showbarInfo.getAccountId()))) {
			int total = showbarAuthManager.deleteAll(showbarInfo.getId());
            // 3、使用info级别记录日志
			logger.info(String.format("%s完成%s条数据的批量删除！",showbarInfoId,total));
			try {
				eTagCacheManager.updateETagDate(ShowConstants.SHOWPOST_CHANGE_ETAG, ShowConstants.SHOWPOST_CHANGE_ETAG);
			} catch (Exception e) {
                // 4、使用error级别记录日志
				logger.error("更新Etag异常！",e);
			}
		} else {
			if(logger.isDebugEnabled()){
                // 5、使用debug级别记录日志
                logger.debug(AppContext.currentUserName() + "没有删除当前主题的权限:" + showbarInfoId);
			}
			throw new NotAuthorizationException();
		}
	}
}



## 反模式

下面这种Logger的定义将对开发人员带来灾难性后果：找不到源代码位置！

public class ReqUtil {
	// Bad code！！！
  	private static final org.apache.commons.logging.Log logger  = CtpLogFactory.getLog(Constants.class); 
}


上面代码的问题在于.getLog(Constants.class)：当前类是ReqUtil，但是注册的LOG指向了Constants.class，将会导致Log记录日志的时候显示代码位置在Constants下，导致开发人员花费大量时间分析问题：

## Log 本来是ReqUtil抛出的，但是被记录在Constants下
19:54:56 [localhost-startStop-1] ERROR: Constants: - org.quartz.ObjectAlreadyExistsException



## LOG配置文件

log4j通过XML配置管理各模块日志粒度。

产品源码下，日志配置文件存放于：

/ctp-common/src/main/webapp/WEB-INF/cfgHome/base/log4j2_sys_starting.xml
/ctp-common/src/main/webapp/WEB-INF/cfgHome/base/log4j2_sys_running.xml
/ctp-common/src/main/webapp/WEB-INF/cfgHome/base/log4j2-properties.xml


生产系统下，日志存放于：

/seeyon/WEB-INF/cfgHome/base/log4j2_sys_starting.xml  -- 启动过程中日志
/seeyon/WEB-INF/cfgHome/base/log4j2_sys_running.xml   -- 启动后，运行过程中日志
/seeyon/WEB-INF/cfgHome/base/log4j2-properties.xml    -- Log日志全局配置



## 如何看懂日志配置？

如下图所示，只要日志名称为org.hibernate.SQL或org.hibernate.SQL.xxx都受此配置管控，此配置要求error级别才记录日志，并且日志存放位置是sql.log、error.log：

基于此规范就可以自行调整日志级别。




## 动态更新日志级别

线上系统如果需要调整日志输出级别，不用停服，可以使用系统管理员登录->系统监控->底部操作按钮->运行态改变日志级别。

如下图login默认是INFO，如果想输出DEBUG的login日志，则选中该行的DEBUG立刻生效。

运行态改动日志级别有效时间：如果系统不停服，随后日志都会以调整后的级别输出。系统重启之后，日志级别会被还原为初始状态。






## 最佳实践


## DEBUG日志

debug日志通常用于做数据跟踪使用，默认生产系统下debug日志不会被开启，需要调试跟踪的时候可以自行动态开启，通过日志观察代码数据走向。在编写代码的时候，记录尽量多的debug日志将有利于分析生产系统上的问题。

注意记录debug日志外层需要包装if(logger.isDebugEnabled())判断，什么原因自己想想。

if("zh".equals(lang)) {
 // 思考题：为何推荐在外层进行一次log.isDebugEnabled()判断？
 if(logger.isDebugEnabled()) {       
  logger.debug("zh lang：" + lang);
 }
 String country = locale.getCountry();
 if(Strings.isNotBlank(country)) {
  country = country.toLowerCase();
 }
 // 兼容华为平板 zh_HANS-CN
 if(country.endsWith("cn")) {
  loc = Locale.SIMPLIFIED_CHINESE;
  if(logger.isDebugEnabled()) {       
   logger.debug("SIMPLIFIED_CHINESE lang：" + country);
  }
 }else if(country.endsWith("tw")){
  loc = Locale.TRADITIONAL_CHINESE;
  if(logger.isDebugEnabled()) {       
   logger.debug("TRADITIONAL_CHINESE lang：" + country);
  }
 }
}



## INFO日志

info日志是比较常用的日志记录类型，如果你有些关键跟踪数据需要放入日志文件中就可以使用.info方法。比如方法执行耗时、一些日志动作记录等等。

long startTime = System.currentTimeMillis();
logger.info("Initializer [" + beanName + "] start:");
consoleLogger.info("Initializer [" + beanName + "] start:");
try {
    initializers.get(beanName).initialize();
} catch (Exception e) {
    logger.error(e.getMessage(), e);
}
long l = System.currentTimeMillis() - startTime;
if (initializers.get(beanName) instanceof AbstractSystemInitializer) {
    AbstractSystemInitializer aci = (AbstractSystemInitializer) initializers.get(beanName);
    logger.info(beanName + "," + aci.getSortOrder() + "," + l);
} else {
    logger.info(beanName + ",-," + l);
}

logger.info("Initializer [" + beanName + "] 耗时：" + l + " MS");



## WARN日志

warn级别的日志主要是提醒可能存在潜在问题。

if(!file.exists()){
  log.warn(path + " 分区不存在，请检查分区配置并确定对应磁盘位置有效！");
}



## ERROR日志

异常catch处理都推荐使用.error记录异常，而且一定是使用logger.error("",Throwable)的方法。

  try {
   
  } catch (Exception e) {
   // 注意error传两个参数
   logger.error("", e);
  }



## 反模式


## catch块未做处理

try {
	StringBuilder newMsg = new StringBuilder();
	Map<String, String> mapMsg = JSONUtil.parseJSONString(m, Map.class);
	mapMsg.forEach((key, value) -> {newMsg.append(value);});
	m = newMsg.toString();
} catch (BusinessException e) {
	// Bad Code 空代码
}


catch块未做处理会导致：异常被吞掉，增加问题的排查难度。正确的写法是：

try {
	
} catch (BusinessException e) {
	// 正确写法
	logger.error("",e);
}



## 滥用printStackTrace()

try {
	map = privilegeMenuManager.getByMember(user.getId(),user.getLoginAccount());
} catch (BusinessException e) {
	// Bad Code 错误的写法
	e.printStackTrace();
}


使用printStackTrace()会导致：日志仅仅输出到控制台而不会写入到LOG日志文件，当服务器重启后，控制台信息不会被保留，日志丢失！ 正确的写法是：

try {
	
} catch (BusinessException e) {
	// 正确写法
	logger.error("",e);
}



## 用错log.error(e)

try {
	
} catch (BusinessException e) {
	// Bad Code 错误写法
	logger.error(e);
}


log.error(e)会导致：仅会将报错的异常类型打印出来，报错详细堆栈不会被输出。问题如下：

## 日志中仅有报错的类型 java.lang.NumberFormatException，但是没有详细堆栈，无法定位具体的报错信息点，排查问题困难。
11:00:41 [584907570157383680 - 10.6.3.71] [H-95] ERROR: CtripRestDataManagerImpl: - For input string: "" [code : 1182292592]
java.lang.NumberFormatException: For input string: ""
11:00:42 [584907570157383680 - 10.6.3.71] [H-95]  INFO: ColManagerImpl: - xxxx


正确的写法是logger.error("",e)用带两个参数的API：

try {
	
} catch (BusinessException e) {
	// 正确写法
	logger.error("",e);
}



## 严禁记录敏感数据

红线：千万不要把用户名、密码等敏感信息写入到日志文件中，这是禁忌！！！

// Bad Code 严禁向LOG文件写入敏感数据
logger.info("帐号:"+user.getLoginName()+",密码:"+user.getPassword()+",联系电话："+user.getPhone());



## V8.1以上日志调整说明

1、为什么要对日志进行改造？

 * 减少冗余日志的输出，为日志瘦身
 * 减轻磁盘IO的负载

2、改造了哪些方面?

 * 限制了日志Message的长度：当超过1024个字节，就会被截断。

 * 限制了异常堆栈日志的输出次数：同一个方法的同一个位置抛出了同一个异常栈，堆栈信息一天只会打印一次。

 * 所有的堆栈信息都会额外打印到error.log文件中：error.log和其它日志文件一样，每天都会滚动生成；error.log的最大容量是500M，超过了也会发生滚动。

3、如何找到堆栈日志信息？

 * 每一个error级别的日志后面的生成一个code码，通这个code码在error.log里边查找，就可找到相应的堆栈信息。

4、由于输出的Message被截断了，我想看到全部的message该怎么办？

 * 修改seeyon\WEB-INF\cfgHome\base\log4j2-appenders.xml配置

	<!-- 比如 -->
    <CtpRollingFile name="ctp" fileName="${rootPath}/ctp.log"
                 filePattern="${rootPath}/${fileDate}/ctp.log.${fileDate}.%i.log">
        <Policies>
            <OnStartupTriggeringPolicy/>
            <SizeBasedTriggeringPolicy size="${fileSize}"/>
            <TimeBasedTriggeringPolicy/>
        </Policies>
        <PatternLayout charset="UTF-8" pattern="${patternLayout}"/>
        <DefaultRolloverStrategy max="${rollMax}" fileIndex="max"/>
    </CtpRollingFile>
    <!-- 修改为 -->
    <RollingFile name="ctp" fileName="${rootPath}/ctp.log"
                 filePattern="${rootPath}/${fileDate}/ctp.log.${fileDate}.%i.log">
        <Policies>
            <OnStartupTriggeringPolicy/>
            <SizeBasedTriggeringPolicy size="${fileSize}"/>
            <TimeBasedTriggeringPolicy/>
        </Policies>
        <PatternLayout charset="UTF-8" pattern="${patternLayout}"/>
        <DefaultRolloverStrategy max="${rollMax}" fileIndex="max"/>
    </RollingFile>


编撰人：het、admin


快速跳转



 * LOG日志
   * 日志级别
   * 开发示例
   * 反模式
   * LOG配置文件
     * 如何看懂日志配置？
   * 动态更新日志级别
   * 最佳实践
     * DEBUG日志
     * INFO日志
     * WARN日志
     * ERROR日志
   * 反模式
     * catch块未做处理
     * 滥用printStackTrace()
     * 用错log.error(e)
     * 严禁记录敏感数据
   * V8.1以上日志调整说明



分享链接分享链接

## 37. 产品区隔组件

> 原始路径：`/39/84.html`  
> 相对路径：`39/84.md`

## 产品区隔组件


## 开场问题

V8.1版本有A6+、A8+、A8-N、G6+、G6-N、G6-SU这么多产品线，其中A8+还有企业版和集团版之分，A8-N/G6+/G6-N/G6-SU还有同义的单组织和多组织之分。

这里提出两个开场问题：

 1. 这么多产品线，我们在代码中是如何版本管理的？
 2. 这么多产品线，肯定有功能的区隔（比如A6+和A8+都有致信功能，产品设计上要求致信在不同产品线上显示不同的图标，这个应该如何实现才利于维护？）

基于上面两个问题，V5提供了ProductEditionEnum和SysFlag的实现来解决问题。


## 版本定义文件ProductEditionEnum

com.seeyon.ctp.common.constants.ProductEditionEnum是版本定义文件，基本代码实现如下：

public enum ProductEditionEnum {
    a6              (0, "A6V5-1", "edition.a6.product", ""), // A6+版
    enterprise      (1, "A8V5-1", "edition.enterprise.product", ""), // A8+企业版
    entgroup        (2, "A8V5-2", "edition.entgroup.product", ""), // A8+企业集团版
    government      (3, "G6V5-1", "edition.government.product", ".GOV"), // 政务版
    governmentgroup (4, "G6V5-2", "edition.governmentgroup.product", ".GOV"), // 政务多组织版
    a8n1            (14, "A8NV5-1", "edition.a8n1.product", ""), // A8-N企业版
    a8n2            (15, "A8NV5-2", "edition.a8n2.product", ""), // A8-N企业集团版
    g6n1            (16, "G6NV5-1", "edition.g6n1.product", ".GOV"), // G6-N单组织版
    g6n2            (17, "G6NV5-2", "edition.g6n2.product", ".GOV"),// G6-N多组织版
 g6su1           (18, "G6SUV5-1", "edition.governmentsupervision.product", ".GOV"), // G6-督查督办单组织版
 g6su2           (19, "G6SUV5-2", "edition.governmentsupervisiongroup.product", ".GOV") // G6-督查督办多组织版
    ;
......
}


我们可以通过ProductEditionEnum.getCurrentProductEditionEnum()方法获取到当前正在使用的协同产品线：

int productId = ProductEditionEnum.getCurrentProductEditionEnum().key;


那么，你可能还有个问题：系统是怎么知道我当前正在使用的产品线的？

我们对产品线进行了多重描述：产品线定义文件+产品描述文件+数据库标记+加密狗文件。以后在开发分析问题的时候，可以通过如下方式去了解客户产品线

> 产品线定义文件存放于：ApacheJetspeed\webapps\seeyon\common\js\ui\publicinfomenu.js

> 产品描述文件存放于：ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\base\productFeature.xml


## 功能区隔组件SysFlag

那么回到开场问题：比如A6+和A8+都有致信功能，产品设计上要求致信在不同产品线上显示不同的图标，这个应该如何实现才利于维护？

那么，我们开发可能会考虑基于currentProductEdition就能用来做功能区隔：

int currentProductId= ProductEditionEnum.getCurrentProductEditionEnum().getKey();
if(currentProductId == ProductEditionEnum.a6.getKey()) {

}else {

}


可以明确的是：上面这段代码在当前版本是有效的。但是如果下个版本又出现了b6+、c6+的产品线，同样需要做屏蔽怎么办？

如果我们代码中有几十上百处都这样来处理，那么下个版本就要修改几十上百处的代码，对代码的可维护性太差！

基于可维护的问题，平台提供了SysFlag工具类。


## SysFlag的用法

倒过来介绍，先介绍如果在SysFlag中定义了必要的方法之后，我们会怎么改写上面的代码：

boolean ucEnabled = (boolean) SysFlag.ucEnableButton.getFlag();


上面这一句简单代码即可实现enable功能，SysFlag.ucEnableButton的实现代码如下：

public enum SysFlag {

    /***************************************************************************
     * 开发人员定义的代码在这里 参数顺序依次是：A6-s-V5, A6-V5, A8企业版标志、A8企业集团版、政务版标志、政务多组织版、UFIDA-NC套件版标志、cwork
     */
    sys_isGroupVer(false, false, false, true, false, true, true, false), //是否为多组织版本
    sys_isEnterpriseVer(false, false, true, false, false, false, false, false), //是否为企业版本
    sys_isGovVer(false, false, false, false, true, true, false, false), //是否为政务版本（含政务版和政务多组织版）
    sys_isA6Ver(true, true, false, false, false, false, false, false), //是否为A6
    sys_isG6S(false, false, false, false, false, false, false, false), //是否为G6-s
    ucEnableButton(false, false, true, true, true, true, true, true), // 致信屏蔽A6+特性
}


上面代码的释义：枚举下面每个参数代表一个产品线，第二个参数代表A6+，第三个代表A8企业版，第四个代表A8集团版，通过不同参数true、false控制就能来确定什么产品线支持什么功能。

综上，如果要基于产品线屏蔽某个功能特性，开发只需要在SysFlag下面新增一个枚举，针对对应产品线设置标识语句即可。

当然，如果需要不同产品线使用不同的图标，还可以直接在SysFlag中定义图标文件名，在代码中直接调用即可：

IconSuffix("abouta6.png", "abouta81.png", "abouta82.png", "default.png", "default.png", "default.png", "default.png", "default.png")



## SysFlag的实现原理

SysFlag的实现原理很简单：就是初始化的时候就内置了当前产品线，随后在调用SysFlag枚举的时候已经能定位到对应枚举变量了，代码如下：

public enum SysFlag {

    /***************************************************************************
     * 开发人员定义的代码在这里 参数顺序依次是：A6-s-V5, A6-V5, A8企业版标志、A8企业集团版、政务版标志、政务多组织版、UFIDA-NC套件版标志、cwork
     */

    ucEnableButton(false, false, true, true, true, true, true, true), // 致信屏蔽A6+特性

    ;

    private Map<ProductEditionEnum, Object> flags = new EnumMap<ProductEditionEnum, Object>(ProductEditionEnum.class);

    SysFlag(Object a6sFlag, Object a6Flag, Object enterpriseFlag, Object entgroupFlag, Object governmentFlag, Object governmentgroupFlag, Object ufidancFlag, Object cworkFlag) {
        flags.put(ProductEditionEnum.a6s, a6sFlag);
        flags.put(ProductEditionEnum.a6, a6Flag);
        flags.put(ProductEditionEnum.a6p, a6Flag);
        flags.put(ProductEditionEnum.enterprise, enterpriseFlag);
        flags.put(ProductEditionEnum.a8n1, enterpriseFlag);
        flags.put(ProductEditionEnum.entgroup, entgroupFlag);
        flags.put(ProductEditionEnum.a8n2, entgroupFlag);
        flags.put(ProductEditionEnum.government, governmentFlag);
        flags.put(ProductEditionEnum.governmentgroup, governmentgroupFlag);
        flags.put(ProductEditionEnum.ufidanc, ufidancFlag);
        flags.put(ProductEditionEnum.cwork, cworkFlag);
        flags.put(ProductEditionEnum.g6n1, governmentFlag);
        flags.put(ProductEditionEnum.g6n2, governmentgroupFlag);
        flags.put(ProductEditionEnum.g6su1, governmentFlag);
        flags.put(ProductEditionEnum.g6su2, governmentgroupFlag);
    }

    /**
     * 取得标志，自动识别版本
     * 
     * @return 对应版本的标志
     */
    public Object getFlag() {
        return flags.get(currentProductEdition);
    }

    //产品版本.
    private static ProductEditionEnum currentProductEdition = null;

    static{
        currentProductEdition = ProductEditionEnum.getCurrentProductEditionEnum();
    }

}


编撰人：het、admin


快速跳转



 * 产品区隔组件
   * 开场问题
   * 版本定义文件ProductEditionEnum
   * 功能区隔组件SysFlag
     * SysFlag的用法
     * SysFlag的实现原理



分享链接分享链接

## 38. 安全访问控制

> 原始路径：`/39/86.html`  
> 相对路径：`39/86.md`

## 安全访问控制


## 基于DigestURL摘要算法控制


## 使用示例

第一步：明确哪个后端MVC请求需要被Digest，比如下面这个方法：

public class CollaborationController extends BaseController {
    public ModelAndView statisticSearch(HttpServletRequest request,
            HttpServletResponse response) throws Exception {
    	ModelAndView mav = new ModelAndView("apps/collaboration/colStatisticSearch");
		String userId = request.getParameter("user_id");
		// TODO
		}
}


第二步：通过插件化开发，在插件配置pluginCfg.xml同级目录新增一个pluginProperties.xml文件，目录格式如下：

WEB-INF
	cfgHome
		plugin
			collaboration
				pluginCfg.xml
				pluginProperties.xml


第三步：pluginProperties.xml中定义的内容如下

> 按照注释的描述可以大概理解到collaboration.do的statisticSearch方法中的user_id参数需要被digest，用于权限校验。

<?xml version="1.0" encoding="utf-8"?>
<ctpConfig>
	<collaboration>
		<security>
            <!-- 需要做URL digest的URL注册，空格分隔1为uri地址，2为method（没有可以省略），3为digest参数名 -->
			<digesturl>/collaboration/collaboration.do statisticSearch user_id</digesturl>
        </security>
	</collaboration>
</ctpConfig>


第四步（最关键步骤）：所有调用collaboration.do?method=statisticSearch的地方都要在这个URl中包装一个v参数，示例代码如下：

String url = "/collaboration/collaboration.do?method=statisticSearch&user_id=" + userId + "&v=" + SecurityHelper.func_digest(userId);



## 实现原理

参考代码SpringControllerAuthenticator.checkDigestParam

编撰人：het、admin


快速跳转



 * 安全访问控制
   * 基于DigestURL摘要算法控制
     * 使用示例
     * 实现原理



分享链接分享链接

## 39. 应用配置器参数

> 原始路径：`/39/87.html`  
> 相对路径：`39/87.md`

## 应用配置器参数


## 功能简介

通过OA服务器ApacheJetspeed\conf\SeeyonConfig.cmd运行可执行文件后，可以唤起应用配置器。在“插件参数设置”页签设置必要的参数后，重启系统后参数生效。

应用配置器的插件参数设置是一个统一配置入口，作为二次开发也可以自己开发我们的参数，以达到参数集中配置的效果。




## 开发步骤

第一步：按照插件化开发模式进行开发。

第二步：在插件配置目录下新增一个pluginProperties.xml文件，文件路径在：\WEB-INF\cfgHome\plugin\demo\pluginProperties.xml

<?xml version="1.0" encoding="utf-8"?>
<ctpConfig>
    <demo>
		<!-- 字符串格式 -->
		<loginname mark="{VE}" desc="Demo帐号"></loginname>
		<!-- 密码格式 -->
		<pwd mark="{password} {VE}" desc="Demo密码"></pwd>
		<!-- 数字格式 -->
		<port mark="{int} {VE}" desc="Demo端口">8088</port>
		<!-- 布尔格式 -->
		<enable mark="{boolean} {VE}" desc="是否启用,true表示启用;false表示不启用;默认false">false</enable>
		<!-- 下拉选择格式 -->
		<running mark="{option,1,2,3,4,5} {VE}" desc="Demo线程数">1</running>
	</demo>
</ctpConfig>


第三步：随后访问ApacheJetspeed\conf\SeeyonConfig.cmd就可以立刻看到刚才的配置：



第四步：重启OA，重启OA，重启OA才生效

第五步：在Java后台，通过如下API可以调用到配置：

// 这些配置来自于\WEB-INF\cfgHome\plugin\demo\pluginProperties.xml,这些配置可以通过ApacheJetspeed\conf\SeeyonConfig.cmd应用配置器修改
String loginname = SystemProperties.getInstance().getProperty("demo.loginname");
String pwd = SystemProperties.getInstance().getProperty("demo.pwd");



## 其它使用场景

在完成应用配置器参数配置和注册之后，可以在OA的Spring Bean注册文件中引用应用配置器参数，具体引用方法如下：

在spring-xxx-xx.xml文件中注册对应的Bean实例，其中Bean中的全局变量可以通过${xxx}的形式引用来自应用配置器的参数值。

	<bean id="loginDemoManager" class="com.seeyon.apps.login.LoginDemoManagerImpl">
		<property name="loginname" value="${demo.loginname}" />
		<property name="pwd" value="${demo.pwd}" />
	</bean>


具体使用参数的代码如下：

public class LoginDemoManagerImpl{

	private String loginname;	// 此全局变量在spring中已经引用应用配置器参数达到了自动注册变量的效果
	private String pwd;			// 此全局变量在spring中已经引用应用配置器参数达到了自动注册变量的效果

	public void test(){
		log.info(loginname);
		log.info(pwd);
	}

}


编撰人：het、admin


快速跳转



 * 应用配置器参数
   * 功能简介
   * 开发步骤
   * 其它使用场景



分享链接分享链接

## 40. APPS-API模块化解耦开发

> 原始路径：`/39/160.html`  
> 相对路径：`39/160.md`

## APPS-API模块化解耦开发


## 背景

V5产品由几十个工程组成，使用Maven做依赖管理，在Maven框架内工程间做到逻辑解耦：

 * 应用组（apps工程）之间无法直接调用，防止代码污染
 * 应用组（apps工程）之间通过apps-api桥接：接口定义在apps-api，用于应用组之间调用
 * 工作流通过ctp-workflow-api对外开放接口，实现解耦
 * 表单应用通过cap-api对外开放接口，实现解耦
 * apps-common是应用组件工程，存放水印这类应用公共组件
 * ctp-common提供平台基础组件，如国际化、上传下载组件
 * ctp-organization提供组件机构的支持
 * ctp-core提供平台核心开发框架支撑

我们工程间做到解耦，工程之间只能依靠接口的形式进行调用，而且有依赖顺序。

核心层级：平台核心层 → 公共组件层 → 应用接口层 → 业务应用层（自上而下依赖，严格遵循单向依赖规则）

┌─────────────────────────────────────────────────────────────────────────┐
│                           业务应用层（apps级插件）                        │
│  （90%开发聚焦层，基于接口调用下层能力，相互调用通过apps-api桥接）         │
│  ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐  │
│  │apps-bbs   │ │apps-task  │ │apps-demo  │ │apps-edoc  │ │其他apps-*│  │
│  │（论坛）   │ │（任务）   │ │（示例）   │ │ （公文）│ │业务插件（如协同）  │  │
│  └───────────┘ └───────────┘ └───────────┘ └───────────┘ └───────────┘  │
│          ▲▲▲                  相互调用依赖 → 【apps-api】                 │
└───────────┼─────────────────────────────────────────────────────────────┘
            │
┌───────────▼─────────────────────────────────────────────────────────────┐
│                           应用接口层（桥接解耦层）                        │
│  ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐  │
│  │apps-api   │ │cap-api    │ │ctp-workflow-api││其他业务接口││Org相关接口│  │
│  │（应用桥接）│ │（表单桥接）│ │（工作流桥接） ││工程      ││（组织架构）│  │
│  └───────────┘ └───────────┘ └───────────┘ └───────────┘ └───────────┘  │
│          ▲▲▲                        接口定义层，仅对外暴露能力            │
└───────────┼─────────────────────────────────────────────────────────────┘
            │
┌───────────▼─────────────────────────────────────────────────────────────┐
│                           公共组件层（通用能力层）                        │
│  ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐  │
│  │apps-common│ │ctp-common │ │cap-core  │ │ctp-org    │ │其他公共工程│  │
│  │（应用公共）│ │（平台公共）│ │（表单核心）│ │（组织架构）│ │          │  │
│  └───────────┘ └───────────┘ └───────────┘ └───────────┘ └───────────┘  │
│          ▲▲▲        提供通用工具/能力，全上层工程可直接依赖调用          │
└───────────┼─────────────────────────────────────────────────────────────┘
            │
┌───────────▼─────────────────────────────────────────────────────────────┐
│                           平台核心层（基础框架层）                        │
│  ┌───────────────────────────────────────────────────────────────────┐  │
│  │                          ctp-core                                  │  │
│  │（平台核心开发框架：Spring IOC、依赖注入、Bean容器、核心规范）        │  │
│  └───────────────────────────────────────────────────────────────────┘  │
│          ▲▲▲                架构底层支撑，所有上层工程的基础            │
└─────────────────────────────────────────────────────────────────────────┘



## 解耦调用示例

前面说我们工程间做到解耦，工程之间只能依靠接口的形式进行调用，而且有依赖顺序。我们所谓的接口调用一般是基于Spring IOC的形式进行注入调用。

下面以一个APP应用模块为例，介绍APP调用不同模块的接口示例。


## 什么是应用级插件化开发

我们90%的开发都是apps级应用插件开发，什么是“apps级应用插件”？我们的apps-bbs、apps-task、apps-collaboration、apps-edoc等等都是通过标准的插件化开发出来的功能应用，标准产品中apps-开头的都是“apps级应用插件”，这些工程的职责就是开发功能应用，属于最上层应用封装，可以调用ctp-平台的代码，也可以apps之间相互调用，但调用需要基于Maven规则进行apps-api接口调用。

如下是标准产品apps-bbs的pom.xml配置，其中parent artifactId=apps-root决定了它的依赖关系。

<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">

    <parent>
        <groupId>com.seeyon</groupId>
        <artifactId>apps-root</artifactId>
        <version>standard-V8.0SP2LTS-feature_202205M-SNAPSHOT</version>
    </parent>

    <modelVersion>4.0.0</modelVersion>

    <artifactId>apps-bbs</artifactId>
    <version>${apps.version}</version>

</project>


我们的客户化开发也应该遵守此规则进行插件开发。

如下示例展示了“apps级应用插件”可以调用哪些工程模块，开发过程中需要按照下面规范进行代码维护。


## 调用平台级工程



平台级工程主要是ctp-core、ctp-common、apps-common这几个工程的核心库，一般插件化开发的应用模块可以直接引用，示例如下：

package com.seeyon.apps.demo.manager;

import java.util.Map;

import com.seeyon.ctp.common.AppContext;
import com.seeyon.ctp.common.appLog.manager.AppLogManager;
import com.seeyon.ctp.common.exceptions.BusinessException;
import com.seeyon.ctp.common.filemanager.manager.FileManager;
import com.seeyon.ctp.common.usermessage.UserMessageManager;
import com.seeyon.ctp.util.annotation.Inject;

/**
*注意：DemoManagerImpl一定要在Spring Bean容器中注册
*<bean id="demoManager" class="com.seeyon.apps.demo.manager.DemoManagerImpl"></bean>
**/
public class DemoManagerImpl implements DemoManager {
 
 @Inject
 private AppLogManager appLogManager;
 @Inject
 private FileManager fileManager;
 @Inject
 private UserMessageManager userMessageManager;
 
 @Override
 public void saveDemo(Map<String, Object> params) throws BusinessException {
  // 上传组件
  fileManager.update(file);
  // 审计日志组件
  appLogManager.insertLog(AppContext.getCurrentUser(), 123, "");
  // 发送消息组件
  userMessageManager.sendSystemMessage(arg0, arg1, arg2, arg3, arg4);
 }
 
}



## 调用组织机构接口示例



组织机构是核心中的核心，获取人员、部门、单位、岗位、职务等信息都需要通过组织机构接口来完成，应用组调用组织机构接口的方式也很简单，一般有两种方案二选一：引入OrgManager Bean的形式，或直接调用OrgHelper的形式。

public class DemoManagerImpl implements DemoManager {
 
 @Inject
 private OrgManager orgManager;
 
 @Override
 public void saveDemo(Map<String, Object> params) throws BusinessException {
  // 方案一：注入orgManager的形式，能调用组织机构全部的接口
  V3xOrgMember member = orgManager.getMemberById(arg0);
  // 方案二：不注入Bean，直接使用OrgHelper来调用组织机构接口
  member = OrgHelper.getMember(arg0);
 }
 
}



## 调用CAP表单应用接口示例



表单也是V5里面非常核心的业务，表单无处不在，表单也分CAP3、CAP4（这块内容请自行学习），接口也做了区分。表单的接口公布在cap-api这个工程，下面是表单比较常见的调用示例。

public class DemoManagerImpl implements DemoManager {
 @Inject
 private FormApi4Cap3 formApi4Cap3;
 @Inject
 private FormApi4Cap4 formApi4Cap4;
 
 @Override
 public void saveDemo(Map<String, Object> params) throws BusinessException {
  com.seeyon.cap4.form.bean.FormBean formBean4 = formApi4Cap4.getForm(var1);
  com.seeyon.ctp.form.bean.FormBean formBean3 = formApi4Cap3.getForm(var2);
 }
 
}



## 调用协同插件应用接口示例



协同模块归属于apps应用组，是经常被调用的模块，apps应用组之间的代码是无法被直接调用，我们通过apps-api作为桥接器实现各模块之间的物理调用。

实现原理很简单：apps-api定义Interface接口，apps-collaboration等具体应用组实现Interface，来达到解耦效果。

/**apps-api工程**/
package com.seeyon.apps.collaboration.api;

import com.seeyon.apps.collaboration.po.ColSummary;
import com.seeyon.ctp.common.exceptions.BusinessException;


public interface CollaborationApi {
 /**
  * 根据id获取协同对象
     *
     * 正常:<br>
     *     1、传入正确的协同id，能获取到协同的实体<br>
     *
  * @param id 协同id
  * @return ColSummary对象
  * @throws BusinessException
  */
 public ColSummary getColSummary(Long id) throws BusinessException;
}


/**apps-collaboration工程**/
package com.seeyon.apps.collaboration.api;

import org.apache.commons.logging.Log;

import com.seeyon.apps.collaboration.manager.ColManager;
import com.seeyon.apps.collaboration.po.ColSummary;
import com.seeyon.ctp.common.exceptions.BusinessException;
import com.seeyon.ctp.common.log.CtpLogFactory;
import com.seeyon.ctp.util.annotation.Inject;

public class CollaborationApiImpl implements CollaborationApi{
    private static final Log LOG = CtpLogFactory.getLog(CollaborationApiImpl.class);
    
    @Inject
    private ColManager colManager;

 @Override
 public ColSummary getColSummary(Long id) throws BusinessException {
  ColSummary colSummary = colManager.getColSummaryById(id);
  if (null != colSummary) {
   try {
    ColSummary clone = (ColSummary) colSummary.clone();
    clone.setId(colSummary.getId());
    clone.setAudited(colSummary.isAudited());
    return clone;
   } catch (CloneNotSupportedException e) {
    LOG.error("", e);
   }
  }
  return null;
 }

}


/**apps-demo应用组调用**/
package com.seeyon.apps.demo.manager;

import java.util.Map;

import com.seeyon.apps.collaboration.api.CollaborationApi;
import com.seeyon.ctp.common.exceptions.BusinessException;
import com.seeyon.ctp.util.annotation.Inject;

public class DemoManagerImpl implements DemoManager {
 
 @Inject
 @PluginQualifier(pluginName= "collaboration") //这个注解的目的是：在没有collaboration插件的时候，防止注入报错
 private CollaborationApi collaborationApi;
 
 @Override
 public void saveDemo(Map<String, Object> params) throws BusinessException {
  ColSummary summary = collaborationApi.getColSummary(arg0);
 }
 
}


编撰人：het


快速跳转



 * APPS-API模块化解耦开发
   * 背景
   * 解耦调用示例
     * 什么是应用级插件化开发
     * 调用平台级工程
     * 调用组织机构接口示例
     * 调用CAP表单应用接口示例
     * 调用协同插件应用接口示例



分享链接分享链接

## 41. 动态接口

> 原始路径：`/39/161.html`  
> 相对路径：`39/161.md`

## 动态接口


## 后端Bean替换机制和示例


## 支持场景

Bean替换是最通用的无侵入源码进行二次开发的能力，Java后台Controller、Manager、Dao任何一层都支持Bean替换。

Bean替换简单说就是自己新增一个类，extends标准产品的Controller、Manager、Dao任何一个实现类，Override重写标准产品父类的方法，这样最终代码逻辑就会走二次开发自己新增的类里面去。

Bean替换的支持场景就非常多：

1、客户需要修改某个前端JSP页面的显示效果，客开为了保证不动标准产品JSP源码，可以采用Bean替换后端的Controller，将原计划ModelAndView重定向到标准产品JSP页面的方法重写，重定向到客开的JSP页面。

2、客户需要调整前端某个页面的列表显示内容，此列表的数据是通过Dao层SQL查询出来的。客开为了保证不动标准产品Dao源码，可以采用Bean替换后端的Dao实现类，重写原本获取数据的SQL方法，改为客户期望的规则输出到前端。

3、同样客开发现标准产品的Manager类某个方法不符合客户需求，需要全面重写，则可以采用Bean替换对应Manager实现类，Override重写标准产品方法即可。


## 实现步骤

1、按照插件化开发规则，新增一个独立客开插件工程

2、新插件工程下新建一个实现类，extends自己想要替换的任何一个Controller、Manager、Dao

3、然后通过Override重写父类中的方法，实现客户化开发需要的逻辑

4、最后将新建的实现类注册到spring容器中，随后系统运行时将跳过父类直接调用Bean替换的实现类。

5、将新的客开插件打包发布到标准产品，重启OA


## 开发示例

场景描述： 客户需要大改某个前端页面的交互逻辑，经过客开分析发现客开的前端页面是个capRunningLog.jsp，通过springmvc跳转，代码如下。

public class CapLogController extends BaseController {

    @Override
    public ModelAndView index(HttpServletRequest request, HttpServletResponse response) throws Exception {
        ModelAndView mav = new ModelAndView("cap4/monitor/capRunningLog");

        List<Enums.CapLogType> capLogTypeList = Enums.CapLogType.getLogTypeListByOwnerType();
        mav.addObject("capLogType", JSONUtil.toJSONString(capLogTypeMapList));

        return mav;
    }

}


<!-- cap4日志Bean XML注册信息 -->
<bean name="/cap4/capLog.do" class="com.seeyon.cap4.form.modules.log.CapLogController"/>


由于页面改动太大，等同于重新编写一个页面，故可以采用替代capRunningLog.jsp的方案来开发，实现逻辑是：

 * 基于capRunningLog.jsp复制一个新的jsp文件名为：kkcapRunningLog.jsp（名称可以自己定义，存放目录也可以自己定义）
 * 在kkcapRunningLog.jsp里面修改代码，实现客户的前端交互逻辑
 * 采用Bean替换方式继承CapLogController并重写index方法，将ModelAndView由标准产品的capRunningLog修改为客开的kkcapRunningLog

1）第一步复制并编写kkcapRunningLog.jsp页面这里略过

2）客开按照插件化开发规则，新增或复用一个与标准产品无关的客开插件，在插件化开发框架下完成如下代码实现：

 1. 新增一个客开类KKCapLogController.java（类名可以自定义），此类extends标准产品的CapLogController.java
 2. 在客开类的顶部增加@Replace注解，beanName一定是标准产品CapLogController在XML中注册的名字
 3. 在客开类中，通过@Override注解重写index方法，再将里面的跳转路径改为客开自己的JSP

@Replace(beanName = "/cap4/capLog.do")
public class KKCapLogController extends CapLogController{
    @Override
    public ModelAndView index(HttpServletRequest request, HttpServletResponse response) throws Exception {
        ModelAndView mav = super.index(request, response);
        mav.setViewName("cap4/monitor/kkcapRunningLog");
        return mav;
    }
}


下面的写法等同上面的写法，但上面的写法更优：彻底保留了标准产品的源码，如果标准产品修复了代码，上面的写法就天然承接了标准产品的修改。

@Replace(beanName = "/cap4/capLog.do")
public class KKCapLogController extends CapLogController {
    @Override
    public ModelAndView index(HttpServletRequest request, HttpServletResponse response) throws Exception {
        ModelAndView mav = new ModelAndView("cap4/monitor/kkcapRunningLog");
        List<Enums.CapLogType> capLogTypeList = Enums.CapLogType.getLogTypeListByOwnerType();
        mav.addObject("capLogType", JSONUtil.toJSONString(capLogTypeMapList));
        return mav;
    }
}


3）最后将KKCapLogController.java注册到客开插件Spring XML中：

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
	<!-- 客开Bean替换的XML注册信息，这里的name没什么特别意义，只要保证唯一性即可 -->
	<bean name="/cap4/kkcapLog.do" class="com.seeyon.客开插件路径.KKCapLogController"/>
</beans>


4）最后将文件编译，将KKCapLogController.class、客开插件配置、kkcapRunningLog.jsp部署到服务器测试。

5）完成以上操作之后，用户使用过程中，在请求/cap4/capLog.do?method=index这个URL的时候就不会再走标准产品代码，而是走客开的KKCapLogController.index方法。


## 后端动态接口开发和调用


## 支持场景

面对Controller、Manager、Dao、Resource（Rest类）任何一层，客开期望在标准产品方法中某个位置插入一段自己的实现逻辑，不涉及大改，均可以通过后端动态接口开发适配。

非常适合做动态接口的场景是：客户从低版本升级到V8.1或更高版本，此时涉及客开代码合并，为了防止以后无休止的客开源码合并工作量，可以通过动态接口进行快速转型开发。


## 实现步骤

1、客开先按照侵入源码的方式进行二次开发，自测确认客开有效性，如果有效则开始确认动态接口开发有效性

2、在上一步基础上，去开放平台Open API目录-动态接口章节，搜索是否有现成的动态接口，如果有则直接复用开发

3、如果开放平台Open API中没有现成动态接口，则可以：发起动态接口支持流程，由研发新增动态接口并提交到ctp-studio，随后客开调用新动态接口开发


## 开发示例

场景描述： 按照客户需求，需要在标准产品ColManagerImpl.findsSummaryComments里面增加一段二次开发代码，以满足客户的需求。

传统的实现方式如下所示，我们会直接修改标准产品源码，插入一段客开实现，这种方式短平快，能解决用户问题。

但随之而来的是后期维护成本：ColManagerImpl是协同模块核心类，研发会修改此类进行新功能开发和BUG修复，而客户每次升级、打补丁包都需要客开确认代码是否冲突，无形增加了N倍后期维护成本。

为了解决以上问题，我们可以通过动态接口埋点的形式无侵入源码开发！

public class ColManagerImpl implements ColManager{

    @Override
    public Map<String, Object> findsSummaryComments(Map<String, String> params) throws BusinessException {
        // ......此处省略若干行标准产品源码

        // xxx客户 过滤意见内容 start
        try {
            String depart = params.get("departId");
            String isOk = params.get("isOk");
            if (depart != null) {
                Long departId = Long.parseLong(depart.substring(depart.indexOf('|') + 1));
                ZgyzManager zgyzManager = (ZgyzManager) AppContext.getBean("zgyzManager");
                zgyzManager.filterComment(commentList, departId, "true".equals(isOk));
                if(commentList != null) {
                    allCommentCount.put(0, commentList.size());
                }
            }
        } catch (Exception e) {
            LOG.error("***意见过滤异常：", e);
        }
        // xxx客户 过滤意见内容 end
        
        // ......此处省略若干行标准产品源码
    }
    
}


## 研发侧-动态接口埋点

基于以上代码，首先需要在客开位置进行动态接口“埋点”，这个是研发的工作，资深客开工程师也可以主动开发动态接口，然后将源码提交给研发。

首先一个大原则：按照解耦思想，apps-xxx模块的动态接口全部要在apps-api下定义，表单应用在cap-api定义，工作流在ctp-workflow-api。

1）首先要确认开通接口的模块是否已经有动态接口基础定义，比如协同模块，在apps-api下能找到如下基础定义，则这一步就不用新开了。

如果所属的模块没有，则需要参考如下代码去实现。比如bbs没有，则新增一个BBSDynamicInterface extends DynamicInterface，重写getModuleDes()=BBS讨论模块动态接口，重写getModuleName()='bbs'。

// since注解表示代码初始化版本
@Since("8.1")
public interface ColDynamicInterface extends DynamicInterface {
    @Override
    default String getModuleDes() {
        return "协同动态接口";
    }

    @Override
    default String getModuleName() {
        return "collaboration";
    }
}


2）然后再在apps-api下定义一个interface接口，extends第一步的ColDynamicInterface。当然，如果ColManagerImpl有多处埋点，多个接口可以共用一个ColManagerImplDynamicApi。

@Since("8.1")
public interface ColManagerImplDynamicApi extends ColDynamicInterface {
    // 本次新开埋点
    @Since("8.1SP1")
    default void findsSummaryCommentsOfFilterComment(ColSummaryCommentBO colSummaryCommentBO){
    }
    
    // 历史埋点
    @Since("8.1")
    default void removeColExtendInfo(ColSummaryBean bean) {
    };
    
    // 历史埋点
    @Since("8.1")
    default void putColExtendInfo(ColExtendInfoBean bean) {
    };
}


新开埋点需要传入一个对象ColSummaryCommentBO，实现如下：

public class ColSummaryCommentBO implements Serializable {
    Map<String, String> params;
    List commentList;
    Map<Integer, Integer> allCommentCount;
	// ......此处省略getter、setter
}


注意：我们所有动态接口都要求以对象的形式传递参数，面向对象开发对后期接口扩展维护有极大增益。

default关键字是JDK8新特性，开发必学！

3）以上完成之后，在ColManagerImpl标准产品客开修改代码位置进行动态接口埋点：

public class ColManagerImpl implements ColManager{

	/**如下代码片段是标准产品开通动态接口埋点必备代码start**/
    @Inject
    private DynamicContext dynamicContext;
    private ColManagerImplDynamicApi colManagerImplDynamicApi = null;
    @PostConstruct
    public void init() {
        colManagerImplDynamicApi = dynamicContext.getBean(ColManagerImplDynamicApi.class);
    }
    /**如下代码片段是标准产品开通动态接口埋点必备代码end**/
    
    @Override
    public Map<String, Object> findsSummaryComments(Map<String, String> params) throws BusinessException {
        // ......此处省略若干行标准产品源码

        // xxx客户 动态接口埋点 start
        if(colManagerImplDynamicApi != null){ // colManagerImplDynamicApi != null是必写代码，否则NullPointerException必现
            ColSummaryCommentBO colSummaryCommentBO = new ColSummaryCommentBO();
            colSummaryCommentBO.setCommentList(commentList);
            colSummaryCommentBO.setAllCommentCount(allCommentCount);
            colSummaryCommentBO.setParams(params);
            colManagerImplDynamicApi.findsSummaryCommentsOfFilterComment(colSummaryCommentBO);
        }
        // xxx客户 动态接口埋点 end
        
        // ......此处省略若干行标准产品源码
    }
    
}


4）以上完成之后，将代码提交到标准产品，后续版本客开就可以复用。同时将修改的源码提交到客开对应的ctp-studio工程中，客开即可复用，进行接口化调用。

## 客开侧-动态接口调用

在研发已经提供了对应动态接口埋点基础上，客开即可进行动态接口的接入，按此方式接入即可无侵入标准产品源码，也无需担心升级高版本、月度修复包代码合并成本。

1）客开按照插件化开发规则，新增或复用一个与标准产品无关的客开插件，在插件化开发框架下新增一个类继承ColManagerImplDynamicApi接口：

/**客开代码*/
public class ColManagerImplDynamicApiImpl implements ColManagerImplDynamicApi {
    // 养成记录Log日志的习惯
	private static final Log LOG = CtpLogFactory.getLog(ColManagerImplDynamicApiImpl.class);
}


2）重写研发的动态接口findsSummaryCommentsOfFilterComment方法，这里面埋入客开的代码：

public class ColManagerImplDynamicApiImpl implements ColManagerImplDynamicApi {
    private static final Log LOG = CtpLogFactory.getLog(ColManagerImplDynamicApiImpl.class);

    @Override
    public void findsSummaryCommentsOfFilterComment(ColSummaryCommentBO colSummaryCommentBO) {
        if(LOG.isDebugEnabled()){
            LOG.debug("进入动态接口findsSummaryCommentsOfFilterComment...");
        }
        Map<String,String> params = colSummaryCommentBO.getParams();
        List commentList = colSummaryCommentBO.getCommentList();
        Map allCommentCount = colSummaryCommentBO.getAllCommentCount();
        try {
            String depart = params.get("departId");
            String isOk = params.get("isOk");
            if (depart != null) {
                Long departId = Long.parseLong(depart.substring(depart.indexOf('|') + 1));
                ZgyzManager zgyzManager = (ZgyzManager) AppContext.getBean("zgyzManager");
                zgyzManager.filterComment(commentList, departId, "true".equals(isOk));
                if(commentList != null) {
                    allCommentCount.put(0, commentList.size());
                }
            }
        } catch (Exception e) {
            LOG.error("***意见过滤异常：", e);
        }
    }
}


3）将ColManagerImplDynamicApiImpl.java注册到客开插件Spring XML中：

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
	<!-- 客开Bean替换的XML注册信息，这里的name没什么特别意义，只要保证唯一性即可 -->
	<bean id="colManagerImplDynamicApiImpl" class="com.seeyon.客开插件路径.ColManagerImplDynamicApiImpl"/>
</beans>


4）最后将文件编译、部署到服务器测试。


## 前端JSP动态脚本链入


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



## 前端动态接口开发和调用


## 支持场景

前端接口主要适用于JS文件中一些标准产品已有的方法逻辑的修改，以及替换一些方法的实现逻辑；前端动态接口实现了第三方JS文件的加载机制以及通用的事件生命周期，从而降低客开后期升级成本。

前端接口的支持场景：

1、要在列表界面新增展示字段

2、修改按钮点击事件逻辑，或者在事件逻辑中新增校验


## 实现步骤

1、客开先按照侵入源码的方式进行二次开发，自测客开有效性，如果有效则开始确认动态接口开发有效性

2、在上一步基础上，去开放平台Open API目录-动态接口章节，搜索是否有现成的动态接口，如果有则直接复用开发

3、如果开放平台Open API中没有现成动态接口，则可以：发起动态接口支持流程，由研发新增动态接口并提交到ctp-studio，随后客开调用新动态接口开发


## 开发示例

场景描述：阅读、知会、传阅节点用户点开后直接变已办，不需要点击提交

传统的实现方式如下所示，我们会直接在标准产品源码对应的JS中增加逻辑，这样虽然可以解决用户问题，但是在之后版本升级时会造成代码冲突，大大的增加了后期维护成本

为了解决以上问题，我们可以通过JS中埋点的形式实现无源码侵入开发！

function _onloadFunc() {
  //省略标准产品代码。。。
  
//客开      加   屏蔽知会、阅读、传阅   节点意见处理框
	 if(nodePolicyName == '知会' || nodePolicyName == '阅读' || nodePolicyName == '传阅'){
	var sideBtn = document.getElementById('sideBtn');	
	sideBtn.click();
	var east = document.getElementById('east');	
	east.style.display= "none"; 
	callBackendMethod("noSubmissionManager", "noSubmission", affairId,"collaboration",null);
	 //客开      加   屏蔽知会、阅读、传阅   节点意见处理框
} 	
}


以上在修改在标准产品方法中新增了逻辑，会导致升级产品时再一次迁移代码，如果升级产品对应地方代码有变动，升级产品耗费会大大增加，我们可以在新增代码位置埋点，将新增代码拿出来放在一个单独的JS里，用来实现埋的动态接口

实现逻辑是：

1）、在调用对应方法的JSP或者HTML里引入

<script src="/seeyon/common/cap-dynamic-front/load.js"></script>


2）、将实现接口的JS文件放入/seeyon/common/cap-dynamic-front/js 下，执行上级目录的dev-app.exe，重新编辑load.js,重新生成的load.js会将客开js中的url放入map，在请求的时候就能加载的客开的JS

## 研发侧-动态接口埋点

JS动态接口埋点：

//界面加载完后执行onload方法
function _onloadFunc(){
    //省略标准产品代码。。。
    customManage.methodEmit('apps-Col-doSubmitAfterLoad',{nodePolicyName:nodePolicyName});
}


apps-Col-doSubmitAfterLoad为研发埋点提供方法名，研发可根据具体需求自定义，nodePolicyName为客开需要用到的参数。

在summary.jsp以及其他引用了summary.js中引入load.js：

    <script type="text/javascript" src="${path}/common/cap-dynamic-front/load.js${ctp:resSuffix()}"></script>


## 客开侧-动态接口实现

客开实现代码：

customManage.load({
  match: {
      url: ['/collaboration/collaboration.do?method=summary'],
  },
  unmatch: {
      url: ''
  },
  cssLoadPath: [],
  // 加载顺序
  order: 99
});
/**
 * DOM加载完毕后的处理，加入模板3页面元素
 */
customManage.methodHook('apps-Col-doSubmitAfterLoad',function () {
    var nodePolicyName = this.nodePolicyName;
    	 if(nodePolicyName == '知会' || nodePolicyName == '阅读' || nodePolicyName == '传阅'){
	var sideBtn = document.getElementById('sideBtn');	
	sideBtn.click();
	var east = document.getElementById('east');	
	east.style.display= "none"; 
	callBackendMethod("noSubmissionManager", "noSubmission", affairId,"collaboration",null);
	 //客开      加   屏蔽知会、阅读、传阅   节点意见处理框
} 	
  }
});


match.url 用来指定需要加载该js的页面url，可以根据IE开发者工具查看

cssLoadPath 加载该js的同时，将会加载该css文件

order指定加载顺序，js加载优先级

## 客开JS文件存放生效

1、放入标准产品ApacheJetspeed/webapps/seeyon/common/cap-dynamic-front/js目录下

2、运行ApacheJetspeed/webapps/seeyon/common/cap-dynamic-front/dev-app.exe文件，提示新生成load.js文件后成功，服务器环境不可运行dev-app.exe文件的，可把cap-dynamic-front文件夹到处，执行dev-app.exe后替换服务器load.js文件

3、不需要考虑引入客开自己创建的js文件，运行dev-app.exe程序后，自己生成的js会被加载到load.js中，埋点时引入了load.js，可以直接加载到客开的js文件

编撰人：het、admin、chenghu


快速跳转



 * 动态接口
   * 后端Bean替换机制和示例
     * 支持场景
     * 实现步骤
     * 开发示例
   * 后端动态接口开发和调用
     * 支持场景
     * 实现步骤
     * 开发示例
       * 研发侧-动态接口埋点
       * 客开侧-动态接口调用
   * 前端JSP动态脚本链入
     * 场景
     * 开发示例
       * 确定页面的ModelAndView
       * 建立自定义的JavaScript文件
     * 代码实现原理
   * 前端动态接口开发和调用
     * 支持场景
     * 实现步骤
     * 开发示例
       * 研发侧-动态接口埋点
       * 客开侧-动态接口实现
       * 客开JS文件存放生效



分享链接分享链接

## 42. 应用锁

> 原始路径：`/39/164.html`  
> 相对路径：`39/164.md`

## 应用锁

应用锁组件用于控制并发修改，比如协同流程并发修改和公文正文并发编辑控制。

为应用提供统一的独占锁，管理用户、资源、操作三者之间的关系。 只控制锁的状态（加锁、解锁、锁失效、锁判断），不实际对资源进行锁定，资源和操作的锁定由应用自己管理。

为同时适应单机和集群环境，提升性能，提供内存锁和数据库锁两种模式。 单机环境使用内存保存锁；集群环境使用数据库保存锁。


## 功能特性

功能一： 锁定资源 特定用户锁定资源，解锁或锁失效之前其他用户不允许访问资源。 锁定资源后指定资源只允许加锁者独占使用。

功能二： 锁定资源的操作 特定用户锁定资源的操作，解锁或锁失效之前其他用户不允许进行资源的操作。

功能三： 解锁 解除资源的所有锁或解除资源特定操作的锁。

功能四： 锁判断 判断指定用户是否可以访问资源或资源的操作。 这里会有一定歧义：对资源加锁是锁定了资源的所有操作，还是操作为空本身就是一种操作。 在这里不做处理，由应用自己解释。如果有特定的解释，请不要使用组件提供的锁判断方法，取得资源的所有锁后自己判断。

功能五： 锁过期 提供了锁过期的策略，缺省过期时间设置为8小时，以后可以进行扩展。

功能六： 锁失效 以下三种情况会导致锁失效，失效的锁将被系统自动清理。

 * 锁过期；
 * 加锁人不在线；
 * 加锁人虽然在线，但加锁以后登出过（加锁时间<登录时间）。


## 使用示例

1）应用如果要使用锁组件，确定模块编号以后，在Spring配置文件中定义一个新的bean，如下所示

<bean id="formLock" parent="lockManager">
	<property name="module" value="formLock"/>
</bean>


2）然后在自己的class中引用定义的bean即可。

<bean id="formManager" class="com.seeyon.v3x.form.FormManagerImpl">
	<property name="formLock" ref="formLock"/>
</bean>


3）业务代码层面是：“判断是否锁占用”、“加锁”、“解锁”结合使用来保证锁的有效性。

   public class FormManagerImpl {
       private long owner;
       private LockManager formLock;
       private long resourceId;
       private int action = -1;

       public long getFormLock() {
           return formLock;
       }

       public void setFormLock(LockManager formLock) {
           this.formLock = formLock;
       }

       /**占用锁*/
       public long lock(long memberId,long formId) {
           formLock.lock(memberId,formId);
       }
       
       /**判断是否正在占用锁*/
       public boolean isLock(long memberId,long formId){
           return formLock.check(memberId,formId);
       }
       
       /**解除锁占用*/
       public void unlock(long formId){
           formLock.unlock(formId);
       }
       
   }



## 最佳实践

场景1：控制编辑工作流流程业务并发操作

// 请求1：打开编辑流程页面时
long resourceId;
long userId = AppContext.currentUserId();
boolean result = lockManager.check(userId,resourceId);

if(result){
    // 可操作
    result = lockManager.lock(userId, resourceId);
}

if(!result){
    // 不可操作或加锁失败
    // 提示前端用户
}

//-------------------------------------------------------------//
// 请求2：关闭编辑流程页面时，调用解锁
lockManager.unlock(resourceId);


场景2：控制集群环境的用户并发操作

long resourceId;
long userId = AppContext.currentUserId();
boolean result = lockManager.check(userId,resourceId);

// 可操作
if(result){
    result = lockManager.lock(userId, resourceId);
}

if(!result){
    // 不可操作或加锁失败
    // 提示前端用户重试，也可以采取3的方式等待一段时间重试，但考虑用户体验，时间不宜过长
}else{
    try{
        doSomething();
    } catch (Exception e) {
        // ...
    }finally {
        // 完成业务操作后解锁
        lockManager.unlock(resourceId);
    }  
}


场景3：控制集群环境的后台并发操作

long resourceId;
long userId = AppContext.currentUserId();
boolean result = checkAndLock(userId,resourceId);
if(!result){
    // 不可操作或加锁失败
    // 等待重试 如果能确保不会死锁，也可以while(true)
    for (int i = 0; i < 20; i++) {
        if(!checkAndLock(userId,resourceId)){
           Thread.sleep(1000);
        }
    }
}
if(result){
    try{
        doSomething();
    } catch (Exception e) {
        // ...
    }finally {
        // 完成业务操作后解锁
        lockManager.unlock(resourceId);
    }  
}else{
    // 无法获取锁，抛出异常
}

private boolean checkAndLock(long userId,long resourceId){
    boolean result = lockManager.check(userId,resourceId);
    // 可操作
    if(result){
        result = lockManager.lock(userId, resourceId);
    }
    return result;
}



## 无效场景案例

锁存在所属人的属性，而且对应所属人的在线状态也有很严格的要求，因此对于后台定时任务此类无法获取到当前登录人员的情况下，使用这套锁逻辑无效。 例如所属人传递的是协同发起人，对于同一个协同的两个用户场景，执行到此逻辑的情况下，如果协同发起人处于离线状态，那么第一次运行到判断逻辑，会校验未锁定，然后加锁。第二次运行到判断逻辑，会校验锁属于自己（实际情况是其他人锁的），继续执行代码逻辑。最终导致出现重入现象。

编撰人：het、lichaoj、admin




快速跳转



 * 应用锁
   * 功能特性
   * 使用示例
   * 最佳实践
   * 无效场景案例



分享链接分享链接

## 43. SpringBean注入规范

> 原始路径：`/39/528.html`  
> 相对路径：`39/528.md`

## SpringBean注入规范

V5平台基于Spring框架进行Java后台对象管理，三层模型中的Manager和Dao均要求注册到Spring容器中，采用依赖注入的形式实例化调用。

Spring Bean的注册和引用有很多种方法，但V5有对应规范，我们希望用规范的写法来完成开发，避免出现未知问题。


## 引用已有Bean实例


## 最推荐使用代码

如果你正在开发新功能，此时需要获取组织机构的一些数据，则必然会用到组织机构的核心接口OrgManager。

一个规范的引用Bean方法为：

// 特别注意：DemoManagerImpl一定也要是一个Spring Bean对象，此实例需要交给Spring容器管理
public class DemoManagerImpl implements DemoManager {

	// 第一步：引用OrgManager接口
	private OrgManager orgManager;
	// 第二步：编写set方法，Spring会将实例对象自动注入，详见Spring官方文档
	public void setOrgManager(OrgManager orgManager) {
		this.orgManager = orgManager;
	}
		
	@Override
	public void saveDemo(Map<String, Object> params) throws BusinessException {
		// 第三步：使用orgManager已经实例化的对象
		V3xOrgMember member = orgManager.getMemberById((Long) params.get("memberId"));
		......
	}
}



## 谨慎推荐使用代码

在查阅V5现有代码的时候，大家可能会看到@Inject注解，这个注解引用之后，似乎没有编写set方法也能注入对象。

Inject注解是Ctp依赖注入注解。有别于JSR 330，目前只支持Field注入。

使用@Inject注解之后，就可以省略set方法了，如下代码一般也是有效的：

public class DemoManagerImpl implements DemoManager {

	// 第一步：引用OrgManager接口并引入@Inject注解
	@Inject
	private OrgManager orgManager;
		
	@Override
	public void saveDemo(Map<String, Object> params) throws BusinessException {
		// 第二步：使用orgManager已经实例化的对象
		V3xOrgMember member = orgManager.getMemberById((Long) params.get("memberId"));
		......
	}
}


注意：为什么要谨慎推荐使用？ 因为这个注解默认会强制实例化对象，如果Bean对象不存在会抛出异常，致使系统无法启动。

什么时候Bean对象会不存在呢？我们产品是插件化开发，如果客户没买插件，则对应插件下的Bean都不会实例化。比如你引入了任务Bean，但是客户没购买任务插件，使用@Inject注解后会导致无法启动：

public class DemoManagerImpl implements DemoManager {
	
	// 警告：如果task任务插件不存在会导致Bean注入失败并且抛出异常无法启动
	@Inject
	private TaskmanageApi taskmanageApi;
		
	@Override
	public void saveDemo(Map<String, Object> params) throws BusinessException {
		if(taskmanageApi != null){
			TaskInfoBO taskInfoBO = taskmanageApi.getTaskInfo((Long) params.get("taskId"));
		}
		.....
	}
}


针对以上问题，标准产品提供了一个解决方案：追加@PluginQualifier注解，标识这个Bean来自哪个插件，如果带这个注解后，就不会抛出异常了。

如下代码才是最规范的编写方式：

public class DemoManagerImpl implements DemoManager {
	
	// PluginQualifier注解用于标识此Bean属于哪个插件
	@Inject
	@PluginQualifier(pluginName = "taskmanage")
	private TaskmanageApi taskmanageApi;
		
	@Override
	public void saveDemo(Map<String, Object> params) throws BusinessException {
		if(taskmanageApi != null){
			TaskInfoBO taskInfoBO = taskmanageApi.getTaskInfo((Long) params.get("taskId"));
		}
		.....
	}
}



## 没有办法时才使用的方法

需要注意，使用前面两种依赖注入需要要求实现类需要交给Spring容器管理。而我们的Utils工具类一般不会交给Spring，恰恰在Utils中需要使用一些Bena对象时就无法通过依赖注入的形式获取，需要换一种方式获取。

V5平台的AppContext.getBean提供了在方法引用中引用Spring Bean示例的机会：

public class DemoUtils {

    private static Log logger = CtpLogFactory.getLog(DemoUtils.class);

    public static String getMemberName(Long memberId){
        // 通过AppContext.getBean强行获取Bean实例
        OrgManager orgManager = (OrgManager) AppContext.getBean("orgManager");
        try {
            V3xOrgMember member = orgManager.getMemberById(memberId);
            if(member != null){
                return member.getName();
            }
        } catch (BusinessException e) {
            logger.error("",e);
        };
        return "";
    }

}


> 需要注意AppContext是V5平台封装的API，这是推荐使用的。而Spring本身的ApplicationContext对象虽然也可以获取Bean，但这是不允许使用的，尽量使用V5平台封装，方便后续遇到问题统一调整。


## 绝对禁止编写的代码示例

上一节说到AppContext.getBean可以应急使用，但需要注意此代码绝对不要出现在成员变量后面，如下所示代码是绝对错误，绝对错误，绝对错误！这样会导致Spring初始化的混乱，甚至引发启动异常！

public class DemoManagerImpl implements DemoManager {

	// Bad Code:绝对禁止的代码写法
	private OrgManager orgManager = (OrgManager) AppContext.getBean("orgManager");
		
	@Override
	public void saveDemo(Map<String, Object> params) throws BusinessException {
		V3xOrgMember member = orgManager.getMemberById((Long) params.get("memberId"));
		......
	}
}


有人说“我看到过有些地方这样写是没问题的”，是的，目前唯一允许在成员变量中引入AppContext.getBean的地方是我们的后台Rest接口类：

/**Rest接口中直接引用是被允许的，因为他未交给Spring管理，Spring初始化完成之后才初始化Rest接口类，所以不受影响**/
@Path("meeting")
@Consumes({ MediaType.APPLICATION_JSON, MediaType.APPLICATION_XML })
@Produces(MediaType.APPLICATION_JSON)
@Api(module = ApiModuleEnum.meeting, type = ApiTypeEnum.REST, value = "会议",subModelName = "会议")
public class MeetingResource extends BaseResource {
    private static final Log   LOGGER             = LogFactory.getLog(MeetingResource.class);
    private MtMeetingManager   mtMeetingManager   = (MtMeetingManager) AppContext.getBean("mtMeetingManager");
    private MeetingManager     meetingManager   = (MeetingManager) AppContext.getBean("meetingManager");
    private MeetingM3Manager     meetingM3Manager   = (MeetingM3Manager) AppContext.getBean("meetingM3Manager");
    private MeetingRoomM3Manager meetingRoomM3Manager   = (MeetingRoomM3Manager) AppContext.getBean("meetingRoomM3Manager");
    .....
}



## 如何编写注册一个新的Bean

如果你需要编写一个新的实现类，并将其注册到Spring中，方便自己使用或被别人调用，则按照如下步骤完成即可。

大前提依然是以插件化开发规范进行开发。

首先，定义一个Java接口:

package com.seeyon.apps.demo.manager;
public interface DemoManager {
	public void saveDemo(Map<String,Object> params) throws BusinessException;
}


然后，编写接口的实现类：

package com.seeyon.apps.demo.manager;

public class DemoManagerImpl implements DemoManager {
	@Inject
	private DemoDao demoDao;
		
	@Override
	public void saveDemo(Map<String, Object> params) throws BusinessException {
		Demo demo = new Demo();
		ParamUtil.mapToBean(params, demo, true);
		demo.setIdIfNew();
		demo.setCreateMember(AppContext.currentUserId());
		demo.setCreateTime(new Date());
		demo.setDeleteFlag(Constants4Demo.deleteFlag.ENABLE.ordinal());
		demoDao.save(demo);
	}
}


最后将对象通过XML配置的形式注册到Spring容器中，XML存放于各自插件下：

<!-- 插件化开发，XML注册位置 \seeyon\WEB-INF\cfgHome\plugin\demo\spring\srping-demo-manager.xml -->
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
	<bean id="demoManager" class="com.seeyon.apps.demo.manager.DemoManagerImpl"/>
</beans>


最后调用方注册对应Bena即可使用：

public class DemoController extends BaseController{

	private DemoManager demoManager;
    
    public void setDemoManager(DemoManager demoManager) {
		this.demoManager = demoManager;
	}
}



## 红线、禁忌

1）被Spring管理的对象中，依赖注入对象绝对禁止使用AppContext.getBean来完成！

public class DemoManagerImpl implements DemoManager {

	// Bad Code:绝对禁止的代码写法
	private OrgManager orgManager = (OrgManager) AppContext.getBean("orgManager");
	
	@Override
	public void saveDemo(Map<String, Object> params) throws BusinessException {
		V3xOrgMember member = orgManager.getMemberById((Long) params.get("memberId"));
		......
	}
}


2）不要在Spring容器初始化前、初始化中就进行Bean的使用

public class DemoManagerImpl implements DemoManager {
	@Inject
	private DemoDao demoDao;

	DemoManagerImpl(){
		// 不要在构造方法中使用Bean对象
		demoDao.findDemoList();
	}
	
	static {
		// 不要在static代码块中使用Bean对象
		demoDao.findDemoList();
	}
    
    private void init() {
		// 不要在init-method中使用Bean对象
		demoDao.findDemoList();
	}
}


Spring XML中的init-method属性是不推荐使用的，很多人期望在初始化对象时同时进行缓存初始化，这种写法是极其危险的，我们有标准的初始化接口，在后面介绍。

<beans default-autowire="byName">
	<!-- init-method是不允许被使用的 -->
	<bean init-method="init" id="demoManager" class="com.seeyon.apps.demo.manager.DemoManagerImpl" />
</beans>


Spring XML中的init-method的统一替代方案如下：

平台提供了一个标准组件：可以在Spring容器初始化完成之后，进行缓存等数据初始化，标准的写法如下：

有开发场景需要在启动系统过程中做一些初始化操作，比如定时任务初始化，请统一使用SystemInitializer机制。

public class DemoManagerImpl extends AbstractSystemInitializer implements DemoManager {
    // 经典开头：养成记录日志的好习惯
    private Log LOGGER = CtpLogFactory.getLog(DemoManagerImpl.class);
    // 使用注解标准注入Bean
    @Inject
    private OrgManager orgManager;
    @Inject
    private IndexApi indexApi;
    // 重写AbstractSystemInitializer下的initialize方法，该方法的执行时间是：系统所有Spring初始化完成之后，根据平台默认任务编排依次执行继承了SystemInitializer的initialize方法
    @Override
    public void initialize() {
        // 此时所有Bean已经初始化完成，可以放心调用所有Bean
        orgManager.xxx
    }


编撰人：het、lichaoj


快速跳转



 * SpringBean注入规范
   * 引用已有Bean实例
     * 最推荐使用代码
     * 谨慎推荐使用代码
     * 没有办法时才使用的方法
     * 绝对禁止编写的代码示例
   * 如何编写注册一个新的Bean
   * 红线、禁忌



分享链接分享链接

## 44. 系统后台菜单管理

> 原始路径：`/39/725.html`  
> 相对路径：`39/725.md`

## 系统后台菜单管理


## 1、后台管理员菜单配置位置



如上图所示管理员菜单有两套（entRoleStd和govRoleStd） entRoleStd：标准模式（SystemAdmin系统管理员，GroupAdmin集团管理员，AccountAdministrator单位管理员、AuditAdmin审计管理员） govRoleStd：三员模式(GroupSystemAdmin系统级-系统管理员，GroupSecretAdmin系统级-安全管理员、GroupAuditAdmin系统级-审计管理员、UnitSystemAdmin单位级-系统管理员，UnitSecretAdmin单位级-安全管理员、UnitAuditAdmin单位级-审计管理员)


## 2、不同版本加载的配置文件


## A6单位管理员

标准模式下：menu-AccountAdministrator-A6.xml
三员模式下：menu-UnitSystemAdmin-A6.xml


----------------------------------------


## A8企业版单位管理员

标准模式下：menu-AccountAdministrator-Enterprise.xml
三员模式下：menu-UnitSecretAdmin-Enterprise.xml、menu-UnitSystemAdmin-Enterprise.xml


----------------------------------------


## A8集团版

标准模式下：menu-SystemAdmin.xml、menu-GroupAdmin.xml、menu-AccountAdministrator.xml、menu-AuditAdmin.xml
三员模式下：menu-GroupSystemAdmin.xml、menu-GroupSecretAdmin.xml、menu-GroupAuditAdmin.xml、menu-UnitSystemAdmin.xml、menu-UnitSecretAdmin.xml、menu-UnitAuditAdmin.xml


----------------------------------------

在后台新增菜单时需要确认两个点 一、菜单适配哪些版本 二、菜单需要放在哪个管理员下 注意授权相关的在三员模式下尽量放在安全管理员下

编撰人：admin、hufei




快速跳转



 * 系统后台菜单管理
   * 1、后台管理员菜单配置位置
   * 2、不同版本加载的配置文件
   * A6单位管理员
   * A8企业版单位管理员
   * A8集团版



分享链接分享链接

## 45. 系统消息组件

> 原始路径：`/39/755.html`  
> 相对路径：`39/755.md`

## 系统消息组件

本文讲解V5系统中发送消息相关的内容，本文你能知道：

 * 如何调用接口发送消息
 * 如何新增消息类型
 * 如何自定义新的消息


## 快速开始：开发示例

我们以一个发送系统消息的Java后端代码为例，想要发送消息，只需要： 1）注入UserMessageManager实体Bean对象 2）调用UserMessageManager接口的sendXXX方法


## 特别注意！

此方式发送消息，只能在pc端进行显示或pc右下角消息盒子弹出。并不会推送到移动端！ 若需要推送消息到移动端，建议使用cip消息集成： https://open.seeyon.com/book/ctp/ji-cheng-chang-jing/xiao-xi-ji-cheng.html

private UserMessageManager userMessageManager;
public void setUserMessageManager(UserMessageManager userMessageManager){
    this.userMessageManager = userMessageManager;
}

public void sendMessage(){
	MessageContent msgContent = new MessageContent("消息内容");
	Long sendUserId = AppContext.currentUserId();
	List<MessageReceiver> msgReceivers = xxx;
    userMessageManager.sendSystemMessage(msgContent, ApplicationCategoryEnum.taskManage, sendUserId, msgReceivers);
}



## UserMessageManager使用说明

UserMessageManager有几种接口形式：


## 接口类型

/**
  * 发送系统消息，发送给单个接收者
  * @param content  消息体 
  * @param messageCategroy 消息所属应用分类 在com.seeyon.ctp.common.constants.ApplicationCategoryEnum中定义 
  * @param senderId  发送者ID 
  * @param receiver  接收者 
  * @param messageFilterArgs  消息转移的参数，与对应的UserMessageFilter对应 
  * @see com.seeyon.ctp.common.constants.ApplicationCategoryEnum 
  * @throws MessageException 
  */ 
void sendSystemMessage(MessageContent content, 
    ApplicationCategoryEnum messageCategroy, long senderId, 
    MessageReceiver receiver, Object... messageFilterArgs) throws MessageException; 

/** 
  * 发送系统消息，发送给多个接收者
  * @param content  消息体 
  * @param messageCategroy 
  *                       消息所属应用分类 
  *                     在com.seeyon.ctp.common.constants.ApplicationCategoryEnum中定义 
  * @param senderId  发送者ID 
  * @param receivers  接收者 
  * @param messageFilterArgs  消息转移的参数，与对应的UserMessageFilter对应 
  * @see com.seeyon.ctp.common.constants.ApplicationCategoryEnum 
  * @throws MessageException 
  */ 
  void sendSystemMessage(MessageContent content, 
    ApplicationCategoryEnum messageCategroy, long senderId, 
    Collection  receivers,  Object...  messageFilterArgs)  throws 
        MessageException; 

/** 
  * 发送系统消息，使用指定的时间发送给多个接收者
  * @param content   消息体 
  * @param messageCategroy 
  *                       消息所属应用分类 
  *                       在com.seeyon.ctp.common.constants.ApplicationCategoryEnum中定义 
  *                       如果是插件，需要在插件定义文件中配置applicationCategory属性 
  * @param senderId  发送者ID 
  * @param creationDate  发送时间 
  * @param receivers  接收者 
  * @param messageFilterArgs  消息转移的参数，与对应的UserMessageFilter对应 
  * @see com.seeyon.ctp.common.constants.ApplicationCategoryEnum 
  * @throws MessageException 
  */ 
void sendSystemMessage(MessageContent content, int messageCategroy, 
    long senderId, Date creationDate, 
    Collection receivers, Object... messageFilterArgs) 
    throws MessageException;



## 注意事项

 * 如果MessageContent相同，接收者为多人的情况下，禁止通过for-each 方式调用sendSystemMessage方法发送消息 ；而应该使用多接收者的接口。
 * 如果MessageContent的Subject是动态的，比如：处理协同的状态，通过消息定义来解决。


## 参数说明

## MessageContent构造消息体

MessageContent 消息体，主要封装国际化key以及参数。国际化内容放在各插件的中的国际化文件中，不需要在消息组件中的国际化文件中增加。

几种构造方法说明： 方式一： new MessageContent(String key, Object... param) 方式二：MessageContent.get(String key, Object... param) 方式三：new MessageContent() .add(String key, Object... params)

例如：

MessageContent messageContent = new MessageContent() 
      .add("col.send", subject, sender.getName()) 
      .add("col.agent") 
      .setBody(bodyContent, bodyType, bodyCreateDate);


设置正文，主要用于email的正文:MessageContent.setBody(String bodyContent, String bodyType, Date bodyCreateDate) 设置重要程度：1普通，2重要，3非常重 要:MessageContent.setImportantLevel(Integer)

## MessageReceiver 消息接收者

MessageReceiver 消息接收者，主要封装关联主体对象id、接收人Id、链接类型及链接参数

几种构造方法说明：

 * 每个接收者的链接地址都不一样，通过for-each单个构造 MessageReceiver MessageReceiver.get(Long referenceId, long receiverId, String linkType, String... linkParam)
 * 一个接收者，但没有连接 MessageReceiver MessageReceiver.get(Long referenceId, long receiverId)
 * 多个接收者，一样的链接 List get(Long referenceId, List receiverIds, String linkType, String... linkParam)
 * 多个接收者,都没有链接 List get(Long referenceId, List receiverIds)


## 消息通道(第三方系统接收平台消息)

当第三方系统（sms，email，rtx，gke）需要接收协同平台消息时，可以使用消息展现通道。

只需实现一个消息接口， 系统就可以把外部的应用集成进来，在集成端可以接收系统 的所有消息，如在线消息，协同，会议，计划等，在系统启动前和用户个人设置中均可以配置。


## 消息通道开发步骤

接口名称：interface MessagePipeline 需要开发继承此接口进行相关代码实现。

/**RTXMessagePipeline是开发示例，项目上可以根据场景自行命名class类名**/
public class RTXMessagePipeline implements MessagePipeline


接口必须实现的方法如下：

方法定义                               返回值       备注
getName()                          String    消息展现通道的系统标示，注意不要重复，有数字字母 下划线构成，如：pc,sms,email,rtx,gke
                                             getShowName() string 消息展现通道的显示名称 isAvailability() boolean
                                             该通道是否可用，可以控制是否需要消息展现
isAllowSetting(User currentUser)   String    是否允许用户在“个人设置-消息提示设置”中进行配 置； 如：短信提示，需要后台管理员授权，并且设置了个人
                                             的手机号码，人员是当前登录者，允许配置返回 null， 否则返回提示信息（注意国际化）
getAllowSettingCategory()          List      得到哪些应用类别可以配置(参考 ApplicationCategoryEnum), 如果采用系统默认， 请直接返回
                                             null 如果不允许配置请参考 isAllowSetting(User currentUser)
invoke(Message[] messages)         void      在此方法中处理消息，把消息集成到外系统 getSortId() int 排序号，从 0 开始
isDefaultSend()                    boolean   默认是否发送，如果为 false，则个人需要在“个人设 置-消息提示设置”中进行配置
isShowSetting()                    boolean   如果 isDefaultSend 设置为false,则个人需要设置为true

在完成接口的实现后，将实现类注册到系统

<bean id="rtxMessagePipeline" class="com.seeyon.v3x.plugin.rtx.message.RTXMessagePipeline"/>


系统启动时查看ctp.log等系统日志文件，能看到如下加载信息，则代表pc、email和rtx三个消息通道实现加载成功。

[main] INFO MessagePipelineManagerImpl:68 - 加载消息展现通道：[pc, email, rtx]



## 消息通道代码示例

新建消息通道类，继承并实现MessagePipeline接口，编写接口下的方法实现：

public class RTXMessagePipeline implements MessagePipeline {
    // 处理消息
    public void invoke(Message[] messages) {
        for (Message message: messages) {
            try {
                String remoteURL = message.getRemoteURL();
                String userName = message.getReceiverMember().getLoginName();
                RTXNotifyValueBean value = new RTXNotifyValueBean();
                String content = message.getContent();
                value.title = message.getSenderMember().getName();
                // ...
                rtxSendNotifyManager.sendNotify(value);
            } catch (Throwable e) {
                log.error("", e);
            }
        }
    }
    // 该通道是否可用
    public boolean isAvailability() {
        return SystemEnvironment.hasPlugin("rtx");
    }
    // 消息展现通道的系统标示
    public String getName() {
        return "rtx";
    }
    // 默认是否发送
    public boolean isDefaultSend() {
        return false;
    }
    // 排序号
    public int getSortId() {
        return 6;
    }
}


注：标准产品对不同端不同场景均建立了Pipeline实现类，项目开发过程中可以参考进行定制开发。



编撰人：het、zhuling


快速跳转



 * 系统消息组件
   * 快速开始：开发示例
   * 特别注意！
   * UserMessageManager使用说明
     * 接口类型
     * 注意事项
     * 参数说明
       * MessageContent构造消息体
       * MessageReceiver 消息接收者
   * 消息通道(第三方系统接收平台消息)
     * 消息通道开发步骤
     * 消息通道代码示例



分享链接分享链接

## 46. EMail邮箱[电子邮件]组件

> 原始路径：`/39/756.html`  
> 相对路径：`39/756.md`

## EMail邮箱[电子邮件]组件

系统内置有发送邮件相关接口，可以复用。


## 核心接口WebmailApi

代码及注释如下：

/**
 * 电子邮件接口
 */
public interface WebmailApi {

    /**
     * 判断人员是否有默认邮箱
     *
     * 正常:<br>
     *     1、传入正确的人员id（人员有默认邮箱），返回true<br>
     *     2、传入正确的人员id（人员没有默认邮箱），返回false<br>
     *
     * @param memberId 人员id
     * @return
     * @throws BusinessException
     */
    public boolean hasDefaultMbc(Long memberId) throws BusinessException;

    /**
     * 获取人员邮件所占空间大小
     *
     * 正常:<br>
     *     1、传入正确的人员id，返回邮件所占空间大小<br>
     *
     * @param memberId 人员id
     * @return
     */
    public long getMailSpaceSize(Long memberId) throws BusinessException;

    /**
     * 转发邮件
     *
     * 正常:<br>
     *     1、传入正确的协同id、标题、正文内容、附件列表，返回邮件实体<br>
     *     2、传入正确的计划id、标题、正文内容、附件列表为空，返回邮件实体<br>
     *     3、传入正确的文档id、标题、正文内容为空、附件列表为空，返回邮件实体<br>
     * 异常:<br>
     *     4、所有参数传入null，抛异常<br>
     *
     * @param referenceId 源id，如：协同id/文档id
     * @param subject 标题
     * @param body 正文内容
     * @param attachments 附件列表
     * @return
     */
    public ModelAndView forwardMail(Long referenceId, String subject, String body, List<Attachment> attachments);

}



## 调用示例

public class ColManagerImpl implements ColManager {
	private WebmailApi webmailApi;
	public void setWebmailApi(WebmailApi webmailApi) {
		this.webmailApi = webmailApi;
	}

	/**
     * 协同转发邮件
     * @param params
     * @return
     * @throws BusinessException
     */
    public ModelAndView getforwordMail(Map params) throws BusinessException {
        User user = AppContext.getCurrentUser();
        try {
			// 判断人员是否有默认邮箱，无邮箱则重定向到错误页面
            boolean hasDefaultMbc = webmailApi.hasDefaultMbc(user.getId());
            if(!hasDefaultMbc){
                ModelAndView mav = new ModelAndView("webmail/error");
                mav.addObject("errorMsg", "2");
                mav.addObject("errorUrls", "?method=list&jsp=set");
                return mav;
            }
        } catch (Exception e1) {
            LOG.error("调用邮件接口判断当前用户是否有邮箱设置：", e1);
        }
		Long summaryId; // 源id，如：协同id/文档id
		String subject; //标题
		String bodyContent; // 正文内容
		List<Attachment> attachments; // 附件列表
		// 调用转发动作
		ModelAndView mv = webmailApi.forwardMail(summaryId, subject, bodyContent, attachments);
        return mv;
	}

}


编撰人：het


快速跳转



 * EMail邮箱[电子邮件]组件
   * 核心接口WebmailApi
   * 调用示例



分享链接分享链接

## 47. PhantomJs打印组件

> 原始路径：`/39/759.html`  
> 相对路径：`39/759.md`

## PhantomJs打印组件


## 版本说明

此组件仅适用于协同OA V9.0及更早期版本，并且不适用于信创环境，信创环境下PhantomJs组件无法正常运行！


## 功能介绍

由于PhantomJS使用了一个真实的布局和渲染引擎-WebKit，因此它可以对一个网页进行截屏。因为PhantomJS可以在web页面上捕捉任何东西，所以它不仅可以用来转换带有CSS的HTML内容，还可以用来转换SVG、图像和画布元素。本功能采用了phantomjs网页截屏功能实现对加载的网页进行截屏，开发只需要编写需要打印的页面，将页面的访问地址传入封装好的方法，此功能即可对应答页面进行截屏生成base64字符串的图片或者pdf文件。


## 实现思路

通过java后台封装phantomjs能够识别的命令字符串，将参数封装到命令中，通过java后台执行命令字符串，实现对网页的截图功能


## 适配范围

此功能实现了对公文、协同、CAP3这三个业务的表单、附言、意见区域的打印，开发可以根据参数来控制要打印的区域。


## 涉及工程

涉及到的工程apps-collaboration、apps-edoc、ctp-common


## 调用说明

网页转PDF可调用ctp-common工程中的ScreenShotManager接口的htmlToPdf方法，此方法包含两个参数说明如下：

1)、url：需要打印的页面地址，开发可自己定义要打印的页面地址

公文、CAP3地址如下：
/govdoc/govdoc.do?method=showPrintForm&openFrom=listDone&affairId=xxxx&isShowComment=false&isReplyContent=false

协同地址为如下：
/collaboration/collaboration.do?method=showPrintForm&openFrom=listDone&affairId=xxxx&isShowComment=false&isReplyContent=false


url中参数说明：

----------------------------------------

isShowComment 是否显示意见区域 非必填

isReplyContent 是否显示附言信息 非必填

affairId 个人事项ID 必填

openFrom 打开类型 必填

----------------------------------------

2)、paramObj：ScreenShotParam对象，包含如下属性

----------------------------------------

sessionParams session参数

height 截屏高度

width 截屏宽度

filePath 文件存储地址，默认存储地址为base/temporary文件夹下面

renderType 渲染类型，转pdf无需设置，会强制设置为pdf类型

extParams 扩展参数，可设置转pdf的纸张格式、缩放比例等

----------------------------------------

网页转图片可调用ctp-common工程中的ScreenShotManager接口的htmlToFile方法，此方法包含的参数同htmlToPdf方法。

示例如下：



phantomjs 是 一个基于 webkit 内核的无头浏览器，提供了 javascript API接口，可以通过 js 直接与 webkit内核交互，因此我们实现了一个js文件与浏览器进行交互，此文件为ctp-common工程中的screenShot.js，java后台生成的命令与screenShot.js进行交互，screenShot.js获取后台传递的参数可以设置打印的相关参数。加载页面也可以通过collPhantom()函数与screenShot.js进行交互，从而控制截屏的效果。

screenShot.js可以获取java后台封装的命令行参数供页面截屏使用，关键方法说明如下：

page.open(）此方法为页面打开的时候调用，可以设置pdf文件的的格式、缩放率、图片的渲染方式等。

page.onCallback()此函数页面调用callPhantom(obj)的时候触发，用语页面与phantomjs工具进行交互，此方法可用语动态控制截屏页面的大小，页面加载完成后返回页面对高度和宽度。

page.onCallback = function(data) {
	//来自应用页面的回调，如果页面需要返回高宽则传入参数即可
	if(data.height && data.width){
		page.viewportSize = {
			height : data.height,
			width : data.width
		};
	}
	flagData = data;
}
page.open(params.url, function(status){
	if (status !== "success") {
		console.info("PHANTOMJS_ERROR: Unable to open " + params.url);
		phantom.exit();
	}
	var start = Date.now(), timeout = 10 * 1000;
	var interval =  setInterval(function(){
		//应用页面回调后执行
		if (Date.now() - start > timeout || flagData) {
			clearInterval(interval);
			if(params.renderType == "pdf"){
				page.settings.userAgent = 'Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko) Chrome/33.0.1750.117 phantomJs Safari/537.36';
				//如果非也参数部位空就设置分页参数，如果为空默认未A4、纵向、边距0.8cm
				if(params.paperSize){
					page.paperSize =params.paperSize;
				}else{
					page.paperSize = { format: 'A4', orientation: 'portrait', margin: '0.8cm' };
				}
				//如果缩放率参数不为空就设置缩放率参数，否则默认不缩放
				if(params.zoomFactor){
					page.zoomFactor = params.zoomFactor;
				}else{
					page.zoomFactor=1;
				}
				console.info(page.render(params.filePath));
			}else{
				console.info(page.renderBase64('PNG'));				
			}
			phantom.exit();
		}
	}, 1000);
});



## 常见问题

 1. 转换的pdf无法分页的时候，需要设置一下网页<body>标签的高度，确保body高度和可见内容一致。

 2. 转换的pdf内容未在正中的时候，需要设置一下网页<body>标签的宽度，确保body的宽度不小于pdf内容区域的最小宽度。

 3. 转换的pdf出现内容不全，原因是phantomjs接收到的宽度、高度和页面渲染的不一致，需要确保在页面渲染完成后再调用window.callPhantom({width:width,height:height})方法想phantomjs传递高度和宽度。

 4. 在异步线程中调用表单转pdf会出现seeionid无法获取的问题，解决方案：通过后台管理员在REST用户管理模块创建一个REST用户，当出现无法获取到seeionid的时候可通过这个rest用户获取到一个固定用户的seeionid。

编撰人：ranjunfeng、het、ranjf、admin、lichaoj


快速跳转



 * PhantomJs打印组件
   * 版本说明
   * 功能介绍
   * 实现思路
   * 适配范围
   * 涉及工程
   * 调用说明
   * 常见问题



分享链接分享链接

## 48. 1. 后端组件

> 原始路径：`/39/772.html`  
> 相对路径：`39/772.md`

## 1. 后端组件


## 1.1. 当前用户

框架提供多种方式获取当前登录用户相关信息com.seeyon.ctp.common.authenticate.domain.User

获取当前用户信息的几种方式：

 1. 后台获取当前用户信息的API为AppContext.getCurrentUser()。
 2. JSP中可以用EL表达式${CurrentUser.xxx}。
 3. Javascript中可以用$.ctx.CurrentUser.xxx(目前只开放id，name、loginAccount和loginAccountName)获取。

为避免应用自行创建User对象设置到当前用户，请统一使用UserUtil的build方法创建，setCurrentUser方法设置。

如果是系统中存在的人员，使用UserUtil.build构建， 使用UserUtil.setCurrentUser设置为当前用户

    String loginName;
    User user = new User();
    V3xOrgMember m = orgManager.getMemberByLoginName(loginName);
    user.setLoginAccount(m.getOrgAccountId());
    user.setId(m.getId());
    user.setLocale(LocaleContext.getAllLocales().get(0));
                   AppContext.putThreadContext(com.seeyon.ctp.common.GlobalNames.SESSION_CONTEXT_USERINFO_KEY, user);


改为

    User user = UserUtil.build(loginName,"",null);
    if(user!=null) {
        UserUtil.setCurrentUser(user);
    }


如果是系统中不存在的虚拟用户，如超级节点，使用 UserUtil.buildVirtualUser构建 如

    User user = new User();
    user.setName("SuperNodeUser");
    AppContext.putThreadContext(com.seeyon.ctp.common.GlobalNames.SESSION_CONTEXT_USERINFO_KEY, user);


改为

    User user = UserUtil.buildVirtualUser(1l,"SuperNodeUser");
    UserUtil.setCurrentUser(user);



## 1.2. 产品线相关判断

 * 获取当前产品线信息获取当前产品线信息
   
   com.seeyon.ctp.common.constants.ProductEditionEnum.getCurrentProductEditionEnum()
   
   
   请参考

 * 获取当前版本信息
   
   com.seeyon.ctp.common.constants.ProductVersionEnum.getCurrentVersion()
   
   
   请参考

 * 是否集团版
   
   (Boolean) com.seeyon.ctp.common.flag.SysFlag.sys_isGroupVer.getFlag()
   
   
   请
   
   参考

 * 获取浏览器差异标识，如当前浏览器是否运行管理员登录

(Boolean) com.seeyon.ctp.common.flag.BrowserFlag.A8Allow4Admin(request)


请参考


## 1.3. 国际化 i18n

CTP对国际化组件进行全新的设计，所有的国际化资源文件集中存放在cfgHome/i18n下，可以按照模块划分子文件夹存放，框架会在启动时自动加载全部资源文件，并形成总体的key->value映射，这种模式下要求各模块的key命名要严格按照规范进行定义，不允许出现重复，否则将会相互覆盖。系统Locale定义的配置存在于

WEB-INF/cfgHome/base/systemProperties.xml中的locales属性：

        <!-- 系统提供的语言种类 用逗号分隔 -->
        <locales>zh_CN,en,zh_TW</locales>


前端的调用方式如下：

<tr>
    <td>ctp:i18n函数</td>
    <td>${ctp:i18n('common.button.add.label')}</td>
</tr>
<tr>
    <td>ctp:i18n_1函数，一个参数，变量参数</td>
    <td>${ctp:i18n_1('common.charactor.limit.label',path)}</td>
</tr>
<tr>
    <td>ctp:i18n_1函数，一个参数，数值参数</td>
    <td>${ctp:i18n_1('common.charactor.limit.label',10)}</td>
</tr>
<tr>
    <td>ctp:i18n_1函数，一个参数，字符串参数</td>
    <td>${ctp:i18n_1('common.charactor.limit.label','测试')}</td>
</tr>
<tr>
    <td>ctp:i18n_2函数，两个参数</td>
    <td>${ctp:i18n_2('common.charactor.limit.label','测试',3)}</td>
</tr>
<tr>
    <td>ctp:i18n_3函数，三个参数</td>
    <td>${ctp:i18n_3('common.charactor.limit.label','测试',3,3)}</td>
</tr>
<tr>
    <td>ctp:i18n_4函数，四个参数</td>
    <td>${ctp:i18n_4('common.charactor.limit.label','测试',3,3,3)}</td>
</tr>
<tr>
    <td>ctp:i18n_5函数，五个参数</td>
    <td>${ctp:i18n_5('common.charactor.limit.label','测试',3,3,3,3)}</td>
</tr>


后端的调用方式如下：

ResourceUtil.getString("common.button.add.label");
ResourceUtil.getString("common.charactor.limit.label", 12);
ResourceUtil.getString("common.date.times", 2, 15);
ResourceUtil.getString("common.date.times", 2, 15, 3);
ResourceUtil.getString("common.date.times", 2, 15, 3, 4);
ResourceUtil.getString("common.date.times", 2, 15, 3, 4, 5);


此外，框架还提供了两种前端Javascript国际化调用支持，第一种是系统默认将把“.js”结尾的资源key生成到前端国际化资源中，通过$.i18n函数获取，同时支持动态

参数，如下例：

alert($.i18n('my.resource.js'));
alert($.i18n('my.resource.js','参数1','参数2'));


第二种是在i18n文件夹根下配置export_to_js.xml文件，用于指定哪些后台国际化资源要开放给前端Javascript引用，该文件内容例子如下：

<?xml version="1.0" encoding="utf-8"?>
<export>
    <resKey>common.button.cancel.label</resKey>
    <resKey>common.button.close.label</resKey>
    <resKey>common.button.ok.label</resKey>
</export>



## 1.3.1. 增加语种

以日语为例，平台采用标准的java i18n方式进行国际化，并进行了简化

国际化资源文件的位置：

1、webapps/seeyon/WEB-INF/cfgHome/i18n

2、webapps/seeyon/WEB-INF/cfgHome/plugin/*/i18n

3、webapps/seeyon/common/js/i18n

4、webapps/seeyon/WEB-INF/lib/v3x-all.jar的各个resources/i18n 下(6.0以上版本不存在v3x-all.jar可省略此步骤)

都是标准的java的properties文件，在相应的位置提供同名的_jp.properties文件即可。

此外，还有前端的js国际化资源需要修改，位置在webapps/seeyon/apps_res/*/i18n下，增加一个对应的ja.js文件。

最后，还需要修改webapps/seeyon/WEB-INF/cfgHome/base/systemProperties.xml，

增加ja语种

<!-- 系统提供的语言种类 用逗号分隔，首选语言放在第一位 -->

<locales>zh_CN,en,zh_TW,ja</locales>


如果是针对单个客户交付的项目，6.1SP1以后版本可以省略这一步，直接配置系统参数中的ctp.locales即可。

系统语言选择预置了德语、法语、日语、韩语、俄语的国际化



如果增加的语种超出了系统预置的范围，还需要修改webapps/seeyon/WEB-INF/cfgHome/i18n/common/下所有的LocaleSelectorResources_*.properties文件，增加对应的语种，并为新增的语种增加一个文件。


## 1.3.2. 时区

国际化必须支持时区，否则是不完整的，未了很好的处理时区信息，我们要求必须使用com.seeyon.ctp.util.Datetimes的parseXXX进行日期解析，切忌自己定义DateFormat；同理，必须使用formatXXX进行日期输出。


## 1.4. 配置管理

配置管理提供三种模式：系统配置、配置管理组件、系统开关组件

比较项    系统配置                          配置管理组件                                系统开关组件
定位     系统级的配置，只要配置系统运行环境、IT环境等基础数据   业务级的配置                                在配置管理组件上进行封装
方式     配置方式单一，采用key-value方式          配置灵活，采用category-item-value-extValue   采用key-value(defaultValue)方式
管理模式   由专业人员直接修改文件                   通过各应用自己的界面修改                          通过统一的界面修改


## 1.4.1. 系统配置

标准产品为了适应各种环境、需求特性采用了参数化方式。CTP提供的参数方式继承、兼容老A8方式。

对如下几方面提供了参数化：

 * 系统全局

 * 插件级

参数使用过程包括如下几步：

 1. 定义参数文件
 2. 配置参数
 3. 获取参数

## 定义参数文件

CTP使用xml格式的参数文件。关键特性如下：

 * 分为用户配置项和产品配置项
   
   * 用户配置项：指允许用户通过配置工具进行配置。

 * 产品配置项：指不允许用户配置，不能通过配置工具修改的配置项。

 * 支持层次划分，为了方便对配置项进行分类，例如按模块。类似老A8的 common.size效果。

 * 系统全局与各插件分开配置
   
   * 系统全局配置文件为:base/systemProperties.xml

 * 插件配置分散在个插件中，参见插件规范

## 用户配置项

用户配置项的标识，在元素中增加了 mark属性的配置项，表示此项为用户配置项。

例如：

<temporary>
    <!-- 系统临时目录 SystemEnvironment.getSystemTempFolder() -->
    <folder mark="userconfig" desc="系统临时目录 SystemEnvironment.getSystemTempFolder()">${ctp.base.folder}/temporary</folder>
</temporary>


对于用户配置项，可以进一步定义该数据项的类型及其他约束，此部分沿用老A8方式。

此定义放在mark属性的值中，例如：mark="{int}"

 * 约束必须用{}括起来

 * {int}：表示该配置只能输入整形值

 * {int,1,10}：表示该配置只能输入整形值，且值域是1到10

 * {boolean}：表示该配置是true, false值

 * {option,5,10,15}：表示该配置只能在5、10、15这三个值域中选择

 * {password} ： 对 配 置 值 进 行 加 密 ， 在 代 码 中 使 用com.seeyon.ctp.tools.util.PwdEncoder.decode(String）

 * {VE}和{VP}只在集群启用时生效。

 * 标记了{VE}的配置项，集群所有节点的值必须一致

 * 标记了{VP}的配置项，集群各节点配置的目录必须是相同的目录（物理上）。

## 层次划分

层次特性示例：

<officeTrans>
        <rmi>
            <!-- M Office转换服务的IP地址 -->
            <host>127.0.0.1</host>
            <!-- M{int} Office转换服务的端口 -->
            <port>1097</port>
        </rmi>
        <cache>
            <!-- M Office转换文件目录，存放Office文件的HTML缓存 -->
            <folder>${A8.base.folder}/officetrans</folder>
        </cache>
        <!-- M{int} {VE} Office转换文件最多天数（默认60），超出的文件将被清理以节省空间 -->
        <retainDay>60</retainDay>
        <file>
            <!-- M{int} {VE} 允许转换的Office文件的大小：单位是byte，缺省只转换5M以下的文件 -->
            <maxSize>5242880</maxSize>
        </file>
    </officeTrans>


## 配置参数

通过配置工具对用户配置项进行配置，配置保存在base/conf中。

## 获取参数

在程序中获取参数值调用统一的接口SystemProperties.getInstance().getProperty(key);

key为参数的完整路径，例如："product.build.date"


## 1.4.2. 配置管理组件

完成系统公共的管理配置，与组织模型、权限系统和各业务模块的专有配置一起构成整个系统的完整配置，各个业务应用模块也可以使用此模块来进行配置管理。 接口：ConfigManager configManager

package com.seeyon.ctp.common.config.manager;
public interface ConfigManager {
    //增加一个配置项
    ConfigItem addConfigItem(String configCategory, String configItem,
                            String configValue);

    ConfigItem addConfigItem(String configCategory, String configItem,

                            String configValue, String configDesp, String configType);

    //删除一个配置类别
    void deleteByConfigCategory(String configCategory);

    //删除一个配置项
    void deleteConfigItem(String configCategory, String configItem);

    //更新一个配置项
    void updateConfigItem(ConfigItem config);

    //列举配置项
    List listAllConfigByCategory(String configCategory);

    //获得一个配置项
    ConfigItem getConfigItem(String configCategory, String configItem);
}



## 1.5. JSON解析

JSON解析请统一使用平台提供的JSONUtil，为保证一致性，请勿使用直接使用fastjson、org.json、net.sf.json或jackson。

  // JSON解析
  String s ="{1:{\"first\":1,\"second\":2,\"third\":3}}"; 
    Map o = JSONUtil.parseJSONString(s, Map.class); // 无序
    Type type = new com.seeyon.ctp.util.TypeReference<Map<Integer,LinkedHashMap<String,Integer>>>(){}.getType();
    Map o1 = JSONUtil.parseJSONString(s, type); // 有序

  // JSON转换
  Pojo bean;
  String json = JSONUtil.toJSONString(bean);


如果使用了上述的其他解析器，请按下表进行调整。

调用                                            替代方法                       示例（修改前）                                  示例（替代）
net.sf.json.JSONXxx.fromXxx                   JSONUtil.parseJSONString   JSONArray.fromObject(str);               JSONUtil.parseJSONString(str);
net.sf.json.JSONXxx.toXxx                     JSONUtil.toJSONString      new JSONArray().toString()               JSONUtil.toJSONString(bean);
org.json.JSONObject                           HashMap                    JSONObject data = new JSONObject();      Map data = new HashMap()
org.json.JSONObject                           JSONUtil.parseJSONString   JSONObject data = new JSONObject(str);   Map data = JSONUtil.parseJSONString(str,Map.class);
org.json.JSONArray                            ArrayList                  JSONArray arr = new JSONArray(str);      List arr = JSONUtil.parseJSONString(str,List.class);
org.json.JSONXxx                              JSONUtil.toJSONString      new JSONXxx().toString()                 JSONUtil.toJSONString(bean);
com.alibaba.fastjson.JSONObject               HashMap                    JSONObject data = new JSONObject();      Map data = new HashMap()
com.alibaba.fastjson.JSONArray                ArrayList                  JSONArray arr = new JSONArray(str);      List arr = JSONUtil.parseJSONString(str,List.class);
com.fasterxml.jackson.databind.ObjectMapper   JSONUtil.parseJSONString   mapper.readValue(str);                   JSONUtil.parseJSONString(str)
com.fasterxml.jackson.databind.ObjectMapper   JSONUtil.toJSONString      mapper.writeValue(bean);                 JSONUtil.toJSONString(bean);


## 1.6. 脚本引擎支持（Groovy）

脚本引擎可用于

 1. 表单的公式（表达式）计算
 2. 流程分支条件运算
 3. 字符串宏替换

它最基本的功能是表达式计算，比如x+y，x=1，y=2

x+y是脚本

String script = "x+y";


而x=1，y=2则是对应的上下文，表现为

Map<String, Object> context = new HashMap<String, Object>();
context.put("x", 1);
context.put("y", 2);


通过下面的调用即可得到结果3

import com.seeyon.ctp.common.script.ScriptEvaluator;
...
Integer result = (Integer) ScriptEvaluator.getInstance().eval(script, context);



## 1.6.1. 表达式计算

// 预置函数库
String functions = "def 加(a,b){a+b}\n def 减 = {x,y-> x-y}\n";
// 运算上下文
Map<String, Object> context = new HashMap<String, Object>();
context.put("x", 1);
context.put("y", 2);
context.put("str", "string");
import com.seeyon.ctp.common.script.ScriptEvaluator;
...
ScriptEvaluator evaluator = ScriptEvaluator.getInstance();
try {
    assertEquals(evaluator.eval("x+y", context), 3);

    assertEquals(evaluator.eval("str.length()", context), 6);
    assertEquals(evaluator.eval(functions + "加 x,y", context), 3);
    assertEquals(evaluator.eval(functions + "减(x,y)", context), -1);
} catch (ScriptException e) {
    fail(e.getLocalizedMessage());
}



## 1.6.2. 字符串宏替换

import com.seeyon.ctp.common.script.ScriptEvaluator;
...
assertEquals(evaluator.evalString("x+$y", context), "x+2"); // 把$y替换为上下文中指定的值2
assertEquals(evaluator.evalString("$x+${y}", context), "1+2");//$y也可写为${y}



## 1.6.3. 基本函数库

为了实现预置公式，简化调用，我们可以像上面那样用Groovy的闭包或函数实现基本函数库，与表达式字符串一起调用eval

// 预置函数库
String functions = "def 加(a,b){a+b}\n def 减 = {x,y-> x-y}\n";

ScriptEvaluator.getInstance().eval(functions + "加 x,y", context);


但是，如果预置的函数库很大，无论是定义还是调用都会很麻烦。

我们可以用一种更优雅更自然的方式

 1. 首先，实现一个基础函数库类，这个类可以用groovy实现，也可以用java实现，但它的所有要被脚本调用的方法都必须是static的
    
    比如CommonFunctions.groovy
    
    package com.seeyon.ctp.common.script
    import com.seeyon.ctp.common.AppContext
    public class CommonFunctions {
        /**
         * 可以用Java method实现。
         */
        public static int add(int x,int y){
            return x+y;
        }
        /**
         * 也可以用Groovy function实现（支持中文）。
         */
        def static 加(a,b){
            a+b
        }
        /**
         * 还可以用Groovy closure实现。
         */
        def static 减 = { x,y->
            x-y
        }
        /**
         * 可以为Java methdo包一个壳，简化调用。
         */
        def currentUserName(){
            AppContext.currentUserName()
        }
    }
    

 2. 然后，可以在Java中作如下调用
    
    evaluator.eval("import static com.seeyon.ctp.common.script.CommonFunctions.*;" + "减(x,y)", context)
    evaluator.eval("import static com.seeyon.ctp.common.script.CommonFunctions.*;" + "currentUserName()", context)
    

 3. 表单和工作流等模块可以继承CommonFunctions扩展自己的特殊函数
    
    package com.seeyon.ctp.common.script
    public class FormFunctions extends CommonFunctions{
    
    }
    
    
    然后，在调用时import
    
    evaluator.eval("import static com.seeyon.ctp.common.script.FormFunctions.*;" + "减(x,y)", context)
    

对于复杂的复合对象，建议在脚本中直接调用Java的系统上下文对象获取，比如

def userName = com.seeyon.ctp.common.AppContext.currentUserName()


同理，表单和工作流也可以封装供脚本调用的上下文对象，如FormContext、WorkFlowContext。


## 1.7. 公式组件(Since:V6.1)

公式 = 常量| 变量 | 函数 | 表达式

统一的函数、变量和表达式引擎，管理员和关键用户可以在流程分支匹配、表单计算等场景进行调用。

本组件目前只实现PC配置调用，暂不考虑移动端调用。

公式有三种形态：

公式类型                            管理者    特征                  示例
变量                              管理员    无参 作为上下文注入 运行时可改变   x = 1 BASECURRENCY = "人民币"
表达式或Groovy函数                    管理员    有参数 解释执行 运行时可改变     X = a+b
后台Java注解实现的函数 （支持国际化和参数返回值定制）   二次开发   无参\                 有参数 编译执行 运行期不可改变

公式名称不支持中文（为避免冲突，只接受至少一个大写字母和数字下划线的组合），但显示名称可为中文。

公式名称全局唯一，不可重名。

您可以登录单位管理员定义公式



公式可以更复杂，调用后台的Java方法



这样，就可以直接在配置流程的自定义函数中直接选择



目前因为工作流分支限制只列出返回值为布尔型的公式，需要在公式中组织好变量和表达式，返回布尔值。

例如我们在标准产品预置公式中的示例

1、定义了一个变量CEO_APPROVED_AMOUNT，总经理审批额度

2、定义了一个函数REQUIRE_CEO_APPROVED，需要总经理审批

param > getVar("CEO_APPROVED_AMOUNT")


3、这样，工作流分支里就可以使用这个函数了。以后如果要调整，修改CEO_APPROVED_AMOUNT变量的值即可。

公式组件在关联系统中的应用(Since:V7.0)：

可以在关联系统的URL和参数预设值中使用公式，比如

http://mail.seeyon.com?username=${getVar("USER_LOGINNAME")}&rnd=${RAND()}


${getVar("USER_LOGINNAME")} 调用了公式中的变量USER_LOGINNAME，直接传递当前登录名。

${RAND()}则生成一个随机数。

利用好这个特性，可以不需要开发就实现一些简单的单点登录场景。


## 1.8. 事件


## 1.8.1. 应用场景

底层组件（或一个模块）发生动作，需要让上层应用（或其它模块）做出响应动作。

比如：组织模型创建单位，上层公文需要给这个新单位创建一套预置公文元素、公告需要预置一套板块等等。


## 1.8.2. 技术背景

采用类似Observable+Observer模式，使用java.util.EventObject技术，并进行了简化开发。

方案特点：注解驱动、无需注册监听、无需定义事件类型、异步分发、易扩展。




## 1.8.3. 开发步骤

 1. 定义事件 (Event) 封装事件的上下文，隐含事件类型信息，一个事件对象唯一标识一类事件，不允许重用，同时也在事件触发者和事件处理者之间传递数据。必须继承com.seeyon.ctp.event.Event。

 2. 事件触发
    
    在事件发生的源头，发出事件通知。 com.seeyon.ctp.event.EventDispatcher.fireEvent(Event)

 3. 事件监听（注解驱动）
    
    其它任意模块都可以监听上述事件，只需要在方法上面什么@listenEvent(event=XXXEvent.class)，方法参数即为Event对象。 监听类必须定义为spring bean


## 1.8.4. 事件命名规范

事件对象都放到模块的event包下，如com.seeyon.apps.collaboration.event

模块名称+操作+Event，如：

// 流程发起事件 CollaborationStartEvent

// 流程结束事件 CollaborationFinishEvent

// 流程处理事件 CollaborationProcessEvent

// 流程回退事件 CollaborationStepBackEvent

// 流程撤销事件 CollaborationCancelEvent


## 1.8.5. 示例

 * 第一步：定义事件，并定义好所需要的数据

   public class CollaborationStartEvent extends Event {
        private static final long serialVersionUID = -8411990532000425368L;
        public CollaborationStartEvent(Object source) {
                  super(source);
        }

        private Long summaryId;
        private String from;

        //getter
        //setter
}


 * 第二步：在协同发起代码中触发事件

   public class CollaborationController extends BaseController{  
       public ModelAndView send(HttpServletRequest request,  
                                HttpServletResponse response) throws Exception{  
           …….  
          //协同发起事件通知  
           CollaborationStartEvent event = new CollaborationStartEvent(this);  
           event.setSummaryId(colSummary.getId());  
           event.setFrom("pc");  
           EventDispatcher.fireEvent(event);  
           ……  
       }  
   }


 * 第三步：其它监听事件
   
   public FormEventListener{
       @listenEvent(event= CollaborationStartEvent.class)
       public void onCollaborationStart(CollaborationStartEvent event){
           //event.getSummartId()
       }
   }
   
   
   <bean id="" class="com.seeyon.apps.form.FormEventListener">
       ……
   </bean>
   

监听模式：

// 异步监听，异步方式执行监听代码，出现异常不影响业务执行
@ListenEvent(event = CollaborationStartEvent.class,async=true)
// 事务成功时触发，如果事务提交出现异常，不会调用对应的代码。
@ListenEvent(event = CollaborationStartEvent.class,mode=EventTriggerMode.afterCommit)



## 1.9. After

After反向监听注解，指定Manager或Controller的特定方法执行以后，主动执行当前方法。 比如下面的例子中，SpaceManagerImpl.saveSpaceSort调用以后会执行当前的updateSpace方法。 支持Class的{CanonicalName}.{methodName}，也支持使用Spring的beanName替代CanonicalName， 如linkSystemManager.saveLinkSystem、main.do.main。 所有加了After注解的方法都可以登录系统管理员，在系统监控的EventDump中查看到。 注意：After只监听Controller以及Ajax直接调用的Manager。 如果是Controller里调用了Manager A，或者Ajax调用Manager B，B Manager再调用Manager A， 对于Manager A的After均不会触发。

    @After({"com.seeyon.ctp.portal.space.manager.SpaceManagerImpl.saveSpaceSort",
        "com.seeyon.apps.project.controller.ProjectController.saveProject",
        "/collTemplate/collTemplate.do.saveCollaborationTemplate",
        "linkSystemManager.saveLinkSystem"
        })
    public void updateSpace(){
    }


如果需要传递参数，需要按下面的格式声明（Since 7.0）

@After(value = {"com.seeyon.ctp.login.controller.MainController.index", "main.do.main",
            "sectionManager.doProjection" }, withParameters = true)



## 1.10. 对象缓存

总的原则，少用对象缓存，能不用则不用。


## 1.10.1. 缓存的界定

 1. 静态成员变量集合，在方法中有增删改操作； 只在系统初始化时加载，运行过程中不改变的可以不做缓存同步。
 2. Singleton的成员变量集合，有增删改操作；
 3. Singleton的成员变量，有修改值操作；
 4. 锁（如表单和协同的操作锁）； 使用数据库保存锁状态的可以不考虑同步。
 5. 自增变量。 如果在内存中维护自增值，就必须做集群的改造。高频访问的自增变量在集群模式下必须使用数据库仿照应用锁机制自行管理。
 6. 定时任务。 可以改用Quartz组件，它已经支持集群。

平台提供了两种同步机制来确保缓存的一致性：

缓存组件和通知同步。

缓存组件适用于小对象，它们在集群节点间进行完整传输，不会给网络造成太大负载。 通知同步适用于大数据量或需要频繁进行细粒度更新的场合，比如要从数据库完全重新加载整个缓存，如果使用缓存组件就太奢侈了，这时候，我们可以使用通知同步机制，发送一个通知给其它节点，让它们也进行一次缓存重载。 如果有内存占用较大需要缓存的对象，请不要直接使用缓存组件，可以使用通知同步，传递唯一标识对象的id，让别的节点根据id自行加载（也可使用缓存组件的DataLoader）。


## 1.10.2. 缓存组件

> 应用于V8.0之前版本. 自V8.0开始,使用新缓存组件

组件提供三种缓存数据结构

1、 CacheMap 与java.util.Map一致的数据结构,支持集群同步,对CacheMap的任何变更都会同步到集群的其他节点.

2、 CacheSet 类似CacheMap，替代java.util.Set

3、 CacheObject 缓存单一变量



详细调用请参照API文档，下面以CacheMap为例来说明缓存的使用。

    // 取得缓存管理工厂实例
    private CacheAccessable factory = CacheFactory.getInstance(MyClass.class);

    //创建缓存
    private CacheMap<String,String> cache = factory.createMap("first");
    //...
    //使用缓存
    cache.put("aKey",value);
    //...
    String value = cache.get("aKey");


缓存的创建方式类似Log4J，以当前类的class作为组名称隔离不同的缓存，createMap的参数定义了缓存的名称。 具体的调用则与Map完全一样。

DataLoader： 对于大对象，直接同步会导致较大的网络开销的，可以建立一个DataLoader，只传递Key，由接收方自行重载缓存。



/**
 * 缓存数据加载。为缓存的reload方法提供重新加载缓存的支持。缓存调用者需要自己实现此接口。
* @see AbstractMapDataLoader
 */
public interface DataLoader<K extends Serializable> {
    /**
     * 重新加载整个缓存。
     */
    void load();

    /**
     * 重新加载指定Key的缓存项。
     * 
     * @param key
     *            缓存的key。
     */
    void load(K key);
}


DataLoader开发示例

        cache.setDataLoader(new AbstractMapDataLoader<String, String>(cache) {
            @Override
            protected Map<Long, String> loadLocal() {
                Map<String, String> map = new HashMap<String, String>();
                //    从数据库中加载所有数据，组织为与缓存一致的结构

                ……
            return map;
            }
            @Override
            protected String loadLocal(String key) {
            //    从数据库中加载指定数据，返回
                final String value = dao.get(key);
                return value;
            }
        });


isSkipFillData（Since V7.0）：由于新的缓存组件（Geode）构建的缓存对象（如果是Global类型的）在集群环境下是自动同步的，只要加入集群中会自动从集群节点中同步相关缓存的数据，针对这种情况，增加该方法以便应用构造缓存对象时判断是否需要载入初始化数据，从而避免系统启动 （通常为从节点启动或者主节点重启）时重复加载数据造成浪费。

 if(!CacheFactory.isSkipFillData()){
     // 从数据库中加载组织模型缓存
 }


缓存的注意事项

 1. 控制缓存的大小，不要把一棵树放到缓存里，内存占用和同步代价都会很大。

 2. 控制缓存更新的频次，避免过大的东西流量影响系统稳定性。

 3. 还有一个著名的坑
    
    CacheMap<String,Map> cache;
    Map value = cache.get(key);
    value.put(xxx,xxx);
    cache.put(key,value);
    
    // 上面一切OK，下面就开始失控了
    value.put(xxx,xxx)；
    // end
    
    
    这样的代码会导致各节点的缓存不一致，因为你取出来的value已经脱离缓存组件的控制了，value.put修改操作修改了本地JVM的值，但远程节点未得到同步。
    
    // 正确的做法是value变更以后告知缓存组件
    cache.notifyUpdate(key);
    // 或者再进行一次put
    cache.put(key,value)；
    


## 1.10.3. 新缓存组件

> 自V8.0开始,使用新缓存组件.原有缓存组件作废

新缓存组件文档


## 1.11. 加解密

com.seeyon.ctp.common.encrypt.CoderFactory

/**
 * 加密深度
 *
 * @return 轻度加密：{@link ICoder#VERSON01}；
 * 深度加密：{@link ICoder#VERSON02}；
 * 不加密：<code>no</code>
 */

public String getEncryptVersion() ;



## 1.12. 应用锁

应用锁组件用于控制并发修改

比如协同流程并发修改和公文正文并发编辑控制。

为应用提供统一的独占锁，管理用户、资源、操作三者之间的关系。 只控制锁的状态（加锁、解锁、锁失效、锁判断），不实际对资源进行锁定，资源和操作的锁定由应用自己管理。

为同时适应单机和集群环境，提升性能，提供内存锁和数据库锁两种模式。 单机环境使用内存保存锁；集群环境使用数据库保存锁。


## 1.12.1. 名词解释

 模块：需要加锁的应用。如协同、公文、表单，可以自行指定一个字符串，如ColLock、FormLock作为标识。

 资源：被锁定对象。可以是协同、公文、表单，甚至是人员。

 操作：被锁定对象的行为。对于流程，可以是处理、加签减签等。


## 1.12.2. 功能

功能一： 锁定资源 特定用户锁定资源，解锁或锁失效之前其他用户不允许访问资源。 锁定资源后指定资源只允许加锁者独占使用。

功能二： 锁定资源的操作 特定用户锁定资源的操作，解锁或锁失效之前其他用户不允许进行资源的操作。

功能三： 解锁 解除资源的所有锁或解除资源特定操作的锁。

功能四： 锁判断 判断指定用户是否可以访问资源或资源的操作。 这里会有一定歧义：对资源加锁是锁定了资源的所有操作，还是操作为空本身就是一种操作。 在这里不做处理，由应用自己解释。如果有特定的解释，请不要使用组件提供的锁判断方法，取得资源的所有锁后自己判断。

功能五： 锁过期 提供了锁过期的策略，缺省过期时间设置为8小时，以后可以进行扩展。

功能六： 锁失效 以下三种情况会导致锁失效，失效的锁将被系统自动清理。

 锁过期；

 加锁人不在线；

 加锁人虽然在线，但加锁以后登出过（加锁时间<登录时间）。


## 1.12.3. 调用

 1. 应用如果要使用锁组件，确定模块编号以后，在Spring配置文件中定义一个新的bean，如下所示

   <bean id="formLock" parent="lockManager">
       <property name="module" value="formLock"/>
   </bean>


 1. 然后在自己的class中引用定义的bean即可。

   <bean id="formManager" class="com.seeyon.v3x.form.FormManagerImpl">
       <property name="formLock" ref="formLock"/>
   </bean>


 1. 加锁

   public class FormManagerImpl {
       private long owner;
       private LockManager formLock;
       private long resourceId;
       private int action = -1;


       public long getFormLock() {
           return formLock;
       }

       public void setFormLock(LockManager formLock) {
           this.formLock = formLock;
       }

       public long lock( long memberId,long formId) {
           formLock.lock(memberId,formId);
       }
   }


详细信息请参考相关API文档


## 1.12.4. 最佳实践

1、控制编辑工作流流程业务并发操作

// 请求1：打开编辑流程页面时
long resourceId;
long userId = AppContext.currentUserId();
boolean result = lockManager.check(userId,resourceId);

if(result){
    // 可操作
    result = lockManager.lock(userId, resourceId);
}

if(!result){
    // 不可操作或加锁失败
    // 提示前端用户
}

//-------------------------------------------------------------//
// 请求2：关闭编辑流程页面时，调用解锁
lockManager.unlock(resourceId);


2、控制集群环境的用户并发操作

long resourceId;
long userId = AppContext.currentUserId();
boolean result = lockManager.check(userId,resourceId);

// 可操作
if(result){
    result = lockManager.lock(userId, resourceId);
}

if(!result){
    // 不可操作或加锁失败
    // 提示前端用户重试，也可以采取3的方式等待一段时间重试，但考虑用户体验，时间不宜过长
}else{
    try{
        doSomething();
    } catch (Exception e) {
        // ...
    }finally {
        // 完成业务操作后解锁
        lockManager.unlock(resourceId);
    }  
}


3、控制集群环境的后台并发操作

long resourceId;
long userId = AppContext.currentUserId();
boolean result = checkAndLock(userId,resourceId);
if(!result){
    // 不可操作或加锁失败
    // 等待重试 如果能确保不会死锁，也可以while(true)
    for (int i = 0; i < 20; i++) {
        if(!checkAndLock(userId,resourceId)){
           Thread.sleep(1000);
        }
    }
}
if(result){
    try{
        doSomething();
    } catch (Exception e) {
        // ...
    }finally {
        // 完成业务操作后解锁
        lockManager.unlock(resourceId);
    }  
}else{
    // 无法获取锁，抛出异常
}

private boolean checkAndLock(long userId,long resourceId){
    boolean result = lockManager.check(userId,resourceId);
    // 可操作
    if(result){
        result = lockManager.lock(userId, resourceId);
    }
    return result;
}



## 1.13. 定时任务 Quartz

定时任务分为两种，一种是业务定时任务，另一种是系统定时任务

Table 定时任务分类

名称       使用范围       技术特征                               举例
业务定时任务   应用中的定时任务   定时任务将被持久化                          提前提醒，超期提醒
系统定时任务   异步的调度系统    定时任务将在系统启动初生成，shutdown是终止，不会被持久化   定时从移动网关取短信内容


## 1.13.1. 业务定时任务

 1. 核心类com.seeyon.ctp.common.quartz.QuartzHolder

 2. 基本原理
    
    定时任务采用异步处理模式，在生成定时任务的时候，需要指定：任务处理器Bean + 参数。 任务处理器Bean是解释执行特定任务的JavaBean，通过参数来描述业务特征

 3. 接口规范
    
    * 定义任务处理，实现com.seeyon.ctp.common.quartz.QuartzJob接口

     class ABCQuartz implement QuartzJob{

     public void execute(Map<String, String> parameters){

              Long id = parameters.get("id");

              ...

     }

     }

     <bean name="abcQuartz" class="package.ABCQuartz" >


 * 生成/注册任务
   
   调用接口/方法： com.seeyon.ctp.common.quartz.QuartzHolder
   
   Map<String, String> parameters = new HashMap<String, String>();
   
   parameters.put("id", String.valueOf(id));
   
   QuartzHolder.newQuartzJob("jobName", new Date(109, 1, 1), "abcQuartz", parameters);
   

 * 任务查找和删除
   
   /**
    * 检测任务是否存在
    * 
    * @param name 任务名称
    * @return
    */
   public static boolean hasQuartzJob(String name);
   /**
    * 删除任务
    * 
    * @param name 任务名称
    * @return
    */
   public static boolean deleteQuartzJob(String name);
   
   
   | | Caution | | ---------------------------------------- | ------- | | 特别注意 任务名称要求唯一，即每次调用newQuartzJob时，参数name都是不同的，即使jobBeanId是一致的。如：协同的提前提醒，jobBeanId是同一个，但每一个节点的name、parameters都不是一样的，也就是说这不属于同一个任务。目的：方便任务解除。 | |


## 1.13.2. 系统定时任务

 1. 核心类com.seeyon.ctp.common.timer.TimerHolder

 2. 定义任务处理器
    
    class SampleTask implements Runnable{
    
             public void run(){
    
                     ...
    
             }
    
    } 
    
    <bean name="sampleTask" class="package.SampleTask" >
    

 3. 生成/注册任务
    
    public void StartTask() {
    
             TimerHolder.newTimer(sampleTask, 60 * 60 * 1000);
    
    }
    


## 1.14. 文件（附件）管理JAVA 接口

此部分只描述JAVA程序可用的附件接口，不描述前端附件组件，附件组件的完整用法，请参考前端组件部分。

后端提供如下接口：

 1. 对输入流的下载。
 2. 对附件的删除。


## 1.14.1. 对输入流下载的接口

 1. FileUploadUtil.downLoadStream(……）

   FileUploadUtil工具类

     /**
        * 对输入流直接下载
        * 例如对需要导出的数据组织成输入流，对该流直接下载。
        * 在request中需要设置下面属性：filename （即 request.setAttribute("filename","某某数据")）
        * @param request
        * @param response
        * @param in
        * @return
        * @throws BusinessException
        */
    public static ModelAndView downLoadStream(HttpServletRequest request, HttpServletResponse response,InputStream in) throws BusinessException;



## 1.14.2. 删除附件的接口

 1. attachmentManager.removeByReference(……）
    
    attachmentManager.deleteById(……）

            /**
             * 按照主数据和次数据删除: 文件做物理删除 
             * @param reference
             * @param subReference
             */
            public void removeByReference(Long reference, Long subReference)
            throws BusinessException;


            /**
             * 按照附件Id删除，非物理删除
             * @param attachmentId
             */
            public void deleteById(long attachmentId);



## 1.15. 文件压缩/解压

支持ZIP格式文件的压缩和解压

import com.seeyon.ctp.util.ZipUtil;
// 压缩整个文件夹
ZipUtil.zip(new File("d:\\新建文件夹"), new File("c:\\新建文件夹.zip"), true);
// 压缩指定文件夹下所有文件
ZipUtil.zip(new File("d:\\新建文件夹"), new File("c:\\新建文件夹.zip"), false);
// 压缩一组文件
ZipUtil.zip(Collection<File>, new File("c:\\新建文件夹.zip"));
// 解压缩zip包
ZipUtil.unzip(File zipFile, File directory);



## 1.16. 消息接口


## 1.16.1. 发送消息接口

注入消息接口

 * userMessageManager

例如：

<bean class="com.seeyon.app.collaboration.manager.impl.ColManagerImpl"> 
<property name="userMessageManager" ref="UserMessageManager" /> 
</bean>


----------------------------------------

接口说明

几种接口形式：
/** 
  * 发送系统消息，发送给单个接收者
  * @param content  消息体 
  * @param messageCategroy 消息所属应用分类 在com.seeyon.ctp.common.constants.ApplicationCategoryEnum中定义 
  * @param senderId  发送者ID 
  * @param receiver  接收者 
  * @param messageFilterArgs  消息转移的参数，与对应的UserMessageFilter对应 
  * @see com.seeyon.ctp.common.constants.ApplicationCategoryEnum 
  * @throws MessageException 
  */ 
public void sendSystemMessage(MessageContent content, 
    ApplicationCategoryEnum messageCategroy, long senderId, 
    MessageReceiver receiver, Object... messageFilterArgs) throws MessageException; 

/** 
  * 发送系统消息，发送给多个接收者
  * @param content  消息体 
  * @param messageCategroy 
  *                       消息所属应用分类 
  *                     在com.seeyon.ctp.common.constants.ApplicationCategoryEnum中定义 
  * @param senderId  发送者ID 
  * @param receivers  接收者 
  * @param messageFilterArgs  消息转移的参数，与对应的UserMessageFilter对应 
  * @see com.seeyon.ctp.common.constants.ApplicationCategoryEnum 
  * @throws MessageException 
  */ 
public void sendSystemMessage(MessageContent content, 
    ApplicationCategoryEnum messageCategroy, long senderId, 
    Collection<MessageReceiver>  receivers,  Object...  messageFilterArgs)  throws 
MessageException; 

/** 
  * 发送系统消息，使用指定的时间发送给多个接收者
  * @param content   消息体 
  * @param messageCategroy 
  *                       消息所属应用分类 
  *                       在com.seeyon.ctp.common.constants.ApplicationCategoryEnum中定义 
  *                       如果是插件，需要在插件定义文件中配置applicationCategory属性 
  * @param senderId  发送者ID 
  * @param creationDate  发送时间 
  * @param receivers  接收者 
  * @param messageFilterArgs  消息转移的参数，与对应的UserMessageFilter对应 
  * @see com.seeyon.ctp.common.constants.ApplicationCategoryEnum 
  * @throws MessageException 
  */ 
public void sendSystemMessage(MessageContent content, int messageCategroy, 
    long senderId, Date creationDate, 
    Collection<MessageReceiver> receivers, Object... messageFilterArgs) 
    throws MessageException;


接口使用注意事项

 * 如果：MessageContent相同，接收者为多人的情况下，禁止通过forEach 方式调用sendSystemMessage方法发送消息 ；而应该使用多接受者的接口。

 * 如果MessageContent的Subject是动态的，比如：处理协同的状态，通过消息定义来解决。

接口参数说明：

MessageContent 构造消息体

MessageContent 消息体，主要封装国际化key以及参数。国际化内容放在各插件的中的国际化文件中，不需要在消息组件中的国际化文件中增加。

几种构造方法说明：

 * 方式一： new MessageContent(String key, Object... param)

 * 方式二：MessageContent.get(String key, Object... param)

 * 方式三：new MessageContent() .add(String key, Object... params）……
   
   例如：
   MessageContent messageContent = new MessageContent() 
     .add("col.send", subject, sender.getName()) 
   .add("col.agent") 
   .setBody(bodyContent, bodyType, bodyCreateDate);
   

设置正文，主要用于email的正文

 * MessageContent.setBody(String bodyContent, String bodyType, Date bodyCreateDate)

设置重要程度：1普通，2重要，3非常重 要

 * MessageContent.setImportantLevel(Integer)

MessageReceiver 消息接收者

MessageReceiver 消息接收者，主要封装关联主体对象id、接收人Id、链接类型及链接参数

几种构造方法说明：

 * 每个接收者的链接地址都不一样，通过ForEach单个构造
   
   MessageReceiver MessageReceiver.get(Long referenceId, long receiverId, String linkType, String... linkParam)

 * 一个接收者，但没有连接
   
   MessageReceiver MessageReceiver.get(Long referenceId, long receiverId)

 * 多个接收者，一样的链接
   
   List get(Long referenceId, List receiverIds, String linkType, String... linkParam)

 * 多个接收者,都没有链接
   
   List get(Long referenceId, List receiverIds)


## 1.17. 线程池(Since V8.0)

为控制资源使用，所有应用都必须使用平台提供到的线程池组件，由平台统一管理。


## 1.17.1. 基本用法

// 按应用（group）设置线程池任务队列最大长度
ExecutorServiceFactory.setqueueSize("app", Integer.MAX_VALUE);

// 按应用（group）设置线程池线程的最小、最大数量
public static void setThreadNum(group, minThreadNum, maxThreadNum)

// 获取可Cached线程池
ExecutorService asynEventExecutors = ExecutorServiceFactory.getCachedThreadPool("Event-Handle");

// 获取指定线程数量的线程池
ExecutorService executorService = ExecutorServiceFactory.getFixedThreadPool(String group);

// 获取定时执行的线程池
ScheduledExecutorService scheduledExecutorService = ExecutorServiceFactory.getScheduledThreadPool(String group);



## 1.17.2. 守护线程

将应用开启的守护线程进行改造，使用平台BackgroundExecutor执行器

 /**
     * 执行一个共享的后台线程
     * @param poolName 线程池名称
     * @param aWaitTime 等待时间
     * @param BackgroundRunnable runnable 任务执行器
     * @return 第一次创建线程池,返回 ExecutorService,以后返回null,
     */
BackgroundExecutor.executeBackgroundExecutor(poolName, aWaitTime, runnable)

/**
     * 执行一个共享的后台线程
     * @param poolName 线程池名称
     * @param inactiveWait 最小等待时间
     * @param lazyRun  长等待时间
     * @param RunnableEnd runnable
     * @return 第一次创建线程池,返回 ExecutorService,以后返回null,
     */
    BackgroundExecutor.executeBackgroundExecutorInActiveWait(poolName, inactiveWait, lazyRun, runnable){



## 1.17.3. 简单异步处理线程的共享

请参照下面的示例进行改造。

平台默认线程池

 ExecutorServiceFactory.getDefaultThreadPool().submit(runnable);


示例A：

原代码:

new Thread(new Runnable() {
    @Override
    public void run() {
    try {
        wfAnalysisAuthManager.updateLastestWfAuth(wfaParam.getUser(), wfaParam.getTemplateIds());
    } catch (BusinessException e) {
        logger.error("记录最新查询异常...",e);
    }
    }
}).start();


修改为：

ExecutorServiceFactory.getDefaultThreadPool().submit(new Runnable() {
    @Override
    public void run() {
    try {
        wfAnalysisAuthManager.updateLastestWfAuth(wfaParam.getUser(), wfaParam.getTemplateIds());
    } catch (BusinessException e) {
        logger.error("记录最新查询异常...",e);
    }
    }
});


示例B：

原代码：

class CreateShowbarPushMessageToUser extends Thread {
  @Override
  public void run() {
    //业务处理逻辑略
  }
}

new CreateShowbarPushMessageToUser().start(); //开启一个异步线程


修改为：

class CreateShowbarPushMessageToUser extends Thread {
  @Override
  public void run() {
    //业务处理逻辑略
  }
}

ExecutorServiceFactory.getDefaultThreadPool().submit(new CreateShowbarPushMessageToUser());



## 1.18. 全文检索


## 1.18.1. 环境准备

准备开发所需环境：

 * 加载lucene相关开源包，路径：WEB-INF/lib：
   
   lucene-*.jar
   

 * 加载全文检索组件：
   
   加载jar包，路径：WEB-INF/lib：
   
   seeyon-ctp-index.jar
   

加载插件，路径：

WEB-INF/cfgHome/plugin/index

WEB-INF/cfgHome/plugin/indexResume

加载页面，路径：

WEB-INF/jsp/index

WEB-INF/jsp/indexresume

apps_res/index


## 1.18.2. 开发准备

实现IndexEnable接口，开发人员可以参考原来各自模块关于全文检索的manager类，通过继承，可以少写很多。

 * IndexEnable接口的类介绍
   
   package com.seeyon.apps.index.manager;
   public interface IndexEnable {
     /**
      * 设置各应用的类别名称，参见{@link ApplicationCategoryEnum}
      * @return 各应用自身的key值
           */
             public Integer getAppEnumKey();
   
     /**
      * 根据ID获取索引信息
      * @param id 各应用的实体ID
      * @return
      * @throws BusinessException
           */
             public IndexInfo getIndexInfo(Long id)throws BusinessException;
   
     /**
      * 获取所有需要重建索引的实体数量
      * @param starDate 开始日期
      * @param endDate  结束日期
      * @return
      * @throws BusinessException
           */
              public Integer findIndexResumeCount(Date starDate, Date endDate)throws BusinessException;
   
     /**
      * 获取所有需要重建索引的实体ID集合
      * @param starDate
      * @param endDate
      * @param firstRow
      * @param pageSize
      * @return
      * @throws BusinessException
           */
             public List<Long> findIndexResumeIDList(Date starDate, Date endDate, Integer firstRow,Integer pageSize)throws BusinessException;
   
     /**
      * 获取实体的某些信息
      * @param entityId
      * @return Map的key说明：
      * IndexEnable.FOLDER_ID 所属文档夹ID
      * IndexEnable.SOURCE_ID 实体的源ID：协同、表单、公文为affairId  文档为sourceId
      * IndexEnable.SOURCE_PATH 所处位置路径
      * @throws BusinessException
           */
             public Map<String,Object> findSourceInfo(Long entityId)throws BusinessException;
           }
   

 * getAppEnumKey()：设置各应用的类别名称，比如：
   
    @Override
     public Integer getAppEnumKey() {
         return ApplicationCategoryEnum.doc.getKey();
     }
   

 * getIndexInfo(Long)：根据实体ID获取索引信息，这个方法可以参考原来各模块的实现，挪移过来就可

 * findIndexResumeCount(Date, Date)：根据开始、结束时间，查找此断时间内创建的实体熟练，语句如下：
   
   "select count(id)  from  table where  properties>=? and properties<=? "+other
   

参数说明

模块              TABLE                PROPERTIES   OTHER                  备注
collaboration   ColSummary           createDate   and bodyType<>'FORM'   -
form            ColSummary           createDate   and bodyType='FORM'    -
doc             DocResource          createTime   -                      -
plan            Plan                 createTime   -                      -
organization    OrgMember            createTime   -                      -
taskManage      TaskInfo             createTime   -                      -
meeting         MtMeeting            createDate   -                      -
bulletin        BulData              createDate   -                      -
news            NewsData             createDate   -                      -
calendar        CalEvent             createDate   -                      -
bbs             V3xBbsArticle        issueTime    -                      -
inquiry         InquirySurveybasic   sendDate     -                      -

 * findIndexResumeIDList(Date, Date, Integer,Integer)：分页查询时间段内的实体ID集合，语句如下：
   
   return (List<Long>) getHibernateTemplate().execute(
       new HibernateCallback() {
           public Object doInHibernate(Session session)throws HibernateException, SQLException {
               String member = "";
               if (base.equals(V3xOrgMember.class.getName())) {
                   member = "isDeleted ='0' and enabled='1' and ";
               }
               String hql = "select id from  base where properties>=? and properties<=? "+other+" order by properties desc";
               Query query = session.createQuery(hql);
               query.setParameter(0, starDate);
               query.setParameter(1, endDate);
               query.setFirstResult(fromIndex);
               query.setMaxResults(pageSize);
               return query.list();
           }
       });
   

 * findSourceInfo(Long): 获取实体的某些信息:
   
   文档：IndexEnable.FOLDER_ID：所属文档夹ID
   
   IndexEnable.SOURCE_ID：实体ID，sourceId
   
   IndexEnable.SOURCE_PATH：文档路径
   
   协同、表单、公文：IndexEnable.SOURCE_ID：代办事项ID，affairId
   
   其他模块无须实现。


## 1.18.3. 索引入库

本节介绍如何在开发中调用接口实现索引入库，以便检索。

## 全文检索接口说明：

  package com.seeyon.apps.index.manager;
  public interface IndexManager {

    /**
     * 新增索引信息
     * @param entityId  实体ID
     * @param appType  实体类别 参见{@link ApplicationCategoryEnum}
     * @throws BusinessException
     */
    public void add(Long entityId, Integer appType) throws BusinessException;

    /**
     * 新增索引信息
     * @param indexInfo  索引信息
     * @throws BusinessException
     */
    public void add(IndexInfo indexInfo)throws BusinessException;

    /**
     * 修改索引信息,使用先删后增策略
     * @param entityId  实体ID
     * @param appType  实体类别 参见{@link ApplicationCategoryEnum}
     * @throws BusinessException
     */
    public void update(Long entityId, Integer appType) throws BusinessException;

    /**
     * 修改索引信息,使用先删后增策略
     * @param indexInfo  索引信息
     * @throws BusinessException
     */
    public void update(IndexInfo indexInfo) throws BusinessException;

    /**
     * 修改索引信息 ,使用部分信息更新策略，无需获取应用的索引获取操作
     * @param entityId  实体ID
     * @param appType  实体类别 参见{@link ApplicationCategoryEnum}
     * @param param 需要修改的数据信息
     * @throws BusinessException
     * @deprecated 暂时不用
     */
    public void update(Long entityId, Integer appType, Map param) throws BusinessException;
    /**
     * 删除索引信息
     * @param entityId  实体ID
     * @param appType  实体类别 参见{@link ApplicationCategoryEnum}
     * @throws BusinessException
     */
    public void delete(Long entityId, Integer appType) throws BusinessException;

    /**
     * 单索引库查询
     * @param userInfoStr
     * @param keyMap
     * @param indexLib
     * @param startPoint
     * @return
     * @throws IndexException
     */
    public SearchResultWapper search(String userInfoStr, Map keyMap,
            ApplicationCategoryEnum indexLib, int startPoint)
            throws BusinessException;

    /**
     * 多库查询
     * @param userInfoStr 当前用户的所有组织ID
     * @param keyMap
     * @param indexLib 索引库标识集合数组
     * @param startPoint
     * @return
     * @throws IndexException
     */
    public SearchResultWapper search(String userInfoStr, Map keyMap,
            String[] indexLib, int startPoint)
            throws BusinessException;
            }


## 全文检索接口调用

 * 新增索引
   
   try {
             if (AppContext.hasPlugin("index")) {
                 indexManager.add(id, ApplicationCategoryEnum.doc.getKey());
             }
         } catch (Exception e) {
             logger.error("新增文档[id=" + id + "]全文检索信息时出现异常：", e);
         }
   

 * 修改索引
   
   try {
             if (AppContext.hasPlugin("index")) {
                 indexManager.update(id, ApplicationCategoryEnum.doc.getKey());
             }
         } catch (Exception e) {
             logger.error("更新文档[id=" + id + "]全文检索信息时出现异常：", e);
         }
   

 * 删除索引
   
   try {
             if (AppContext.hasPlugin("index")) {
                 indexManager.delete(drId, ApplicationCategoryEnum.doc.getKey());
             }
         } catch (Exception e) {
             logger.error("删除文档[id=" + id + "]全文检索信息时出现异常：", e);
         }
   

## 索引检索

菜单： 常用工具 -> 全文检索

地址： http://ip:port/context/index/indexController.do?method=searchAll

编撰人：lichaoj、het




快速跳转



 * 1. 后端组件
   * 1.1. 当前用户
   * 1.2. 产品线相关判断
   * 1.3. 国际化 i18n
     * 1.3.1. 增加语种
     * 1.3.2. 时区
   * 1.4. 配置管理
     * 1.4.1. 系统配置
       * 定义参数文件
         * 用户配置项
         * 层次划分
       * 配置参数
       * 获取参数
     * 1.4.2. 配置管理组件
   * 1.5. JSON解析
   * 1.6. 脚本引擎支持（Groovy）
     * 1.6.1. 表达式计算
     * 1.6.2. 字符串宏替换
     * 1.6.3. 基本函数库
   * 1.7. 公式组件(Since:V6.1)
   * 1.8. 事件
     * 1.8.1. 应用场景
     * 1.8.2. 技术背景
     * 1.8.3. 开发步骤
     * 1.8.4. 事件命名规范
     * 1.8.5. 示例
   * 1.9. After
   * 1.10. 对象缓存
     * 1.10.1. 缓存的界定
     * 1.10.2. 缓存组件
     * 1.10.3. 新缓存组件
   * 1.11. 加解密
   * 1.12. 应用锁
     * 1.12.1. 名词解释
     * 1.12.2. 功能
     * 1.12.3. 调用
     * 1.12.4. 最佳实践
   * 1.13. 定时任务 Quartz
     * 1.13.1. 业务定时任务
     * 1.13.2. 系统定时任务
   * 1.14. 文件（附件）管理JAVA 接口
     * 1.14.1. 对输入流下载的接口
     * 1.14.2. 删除附件的接口
   * 1.15. 文件压缩/解压
   * 1.16. 消息接口
     * 1.16.1. 发送消息接口
   * 1.17. 线程池(Since V8.0)
     * 1.17.1. 基本用法
     * 1.17.2. 守护线程
     * 1.17.3. 简单异步处理线程的共享
   * 1.18. 全文检索
     * 1.18.1. 环境准备
     * 1.18.2. 开发准备
     * 1.18.3. 索引入库
       * 全文检索接口说明：
       * 全文检索接口调用
       * 索引检索



分享链接分享链接

## 49. REST接口代码规范

> 原始路径：`/39/783.html`  
> 相对路径：`39/783.md`

## REST接口代码规范

北京致远互联软件股份有限公司 2017年03月


## 适用范围

本文适用致远V5产品线所有新增的REST接口，包括二次开发接口，已开放的除外。

本文主要用于有新增Rest接口诉求开发，本文涵盖了开发Rest过程中的全部规则。

本文技术适用于有Rest基础的开发，如果你还不知道什么叫Rest，请通过互联网视频学习，完成基础后再进行本文的阅读。


## REST开发规范


## 1. 原则

 * 所有的REST接口均基于JAX-RS规范进行开发， 应用代码里禁止出现对jersey的调用
 * 只允许使用GET和POST，严禁使用PUT和DELETE（某些安全软件将DELETE动作视为危险行为）
 * 已确定/已发布的接口禁止修改 请求方法/URL/参数名/返回值结构/内容 ，禁止删除 接口/参数/返回值中的属性

> 如有上述变更诉求，请新启用一个接口

> 允许新增参数，但该参数不能为必填，如必填需提供缺省值兼容旧的调用


## 2. 协议约定

 * 根据CRUD来设计接口，R(Retrieve)使用GET，CUD(create,update,delete)使用POST

 * 使用GET方法时， URL里不能包含动词

 * 使用POST方法时，使用create/add表示新增，update表示修改，remove表示删除（勿使用delete关键字，极易被安全软件拦截）

 * 仅需要传递id的CUD操作，使用body传递id

 * 正常情况下所有R(获取数据)操作都使用GET方法 ，查询内容参数使用QueryParams（仅允许在查询请求参数非常多的情况下，如参数数量大于5个，才可以使用post）

 * 缺省接受JSON格式的参数，输出JSON。

@Consumes("application/json")
@Produces("application/json")


 * 使用Jackson进行JSON处理，缺省将Date输出为长整型值。 URL带参数option.n_a_s=1时将数值输出为字符串(Number as String)，以避免在Javascript中解析长整型的精度问题。

 * 对象和方法命名语义需与内部保持一致，不允许自行创造。比如不要把Member叫做Person。


## 3. 代码规范

 * 代码使用com.seeyon.ctp.rest.resources包名 ，放置在各自模块的工程下自行管理。例如 com.seeyon.ctp.rest.resources.MemberResource
 * 所有资源均需继承BaseResource
 * 资源必须以名词命名，并且同时提供单数和复数两种形式的资源，路径首字母小写

资源名称      路径        CLASSNAME         备注
Member    member    MemberResource    单个人员
Members   members   MembersResource   人员列表
Affair    affair    AffairResource    单条事项
Affairs   affairs   AffairsResource   事项列表

 * 方法名称不允许改变，不允许重载
 * 使用POST进行remove操作
 * 文档必须完备，所有必填内容必须注明到javadoc中
 * 对外接口需要增加标注@RestInterfaceAnnotation


## 4. URL命名

根据RESTful的定义，我们知道，REST定义的URL描述的是资源

虽然我们没有使用PUT、DELETE，但是URL即资源的描述这个属性不会改变

需要特别注意：URL并不是动作的描述，因尽量避免使用增删改以外的动词。

 * URL传递unicode字符一定要encode
 * URL建议按照对象/功能/参数命名，例

  news/like
  news/replay/remove/{id} 或 news/replay/{id}/remove
  news/{id}/replays


 * get方法不需要再在URL使用get开始，如一个bbs模块的方法getConent，应命名为bbs/content/{id}，而不是bbs/getContent/{id}
 * @Path注解中的值，不能以/开始
 * URL遵从Java代码规范， 不允许使用缩写或拼音 ，规避以下JavaScript关键字

delete、in、enum、let、function、typeof、debugger、console、prototype


## 4.1. URL例

正确

GET tasks
GET bbs/{id}/replys
POST affair/remove
   BODY affairId:{id}
POST task/update     特殊：为兼容老代码允许使用task/update/{id}
   BODY taskId:{id},title:{title},...


错误

GET plan/getPlans          应为 GET plans
POST meeting/getOrderDate  应为 GET meeting/orderDate/{roomId}
   BODY roomId:{id}


禁止使用缩写

POST uc/modifypwd 错误命名

POST uc/password 正确命名


原则上一段URL只有一个单词，如一段URL里需要多个单词则需要按单词分割路径，原则上勿用驼峰命名

POST coll/transRepalValid     错误命名，原则上勿用驼峰命名
POST coll/transStepBackValid  错误命名，原则上勿用驼峰命名

POST collaboration/valid/repeal    正确命名
POST collaboration/valid/rollback  正确命名



## 5. 代码注释规范

## 5.1. 原则

 1. 使用标准格式的JAVADOC
 2. 必须包含接口说明，参数说明，返回值说明。格式必须易读，请编写时注意调整注释的格式
 3. JAVADOC应如实反映接口的功能。如有必要，可以在接口说明中增加场景
 4. JAVADOC中，参数需要列明其名称、是否必填、允许值范围以及必要的说明，如参数间有关联，需要备注
 5. 如参数为枚举/对象，必须将其使用的属性、值完全说明
 6. 返回值应注明返回数据中的数据结构以及要有必要的参数说明
 7. 应使用@since标明接口的启用版本
 8. 应使用@date标明接口编写的时间

## 5.2. 注释示例

/**
 * 保存秀吧信息
 * URL show/showbar
 * @since 6.0sp1
 * @date 2016-12-01
 * @param params 秀吧的参数
 * 
<pre>

 *    类型    名称            必填    备注
 *    Long    showbarId        Y    主题Id
 *    Long    coverPicture        N    封面Id
 *    String    showbarName        Y    主题名称
 *    String    summary            N    主题简介
 *    String    address            Y    主题发布地址
 *    String    startDate        Y    主题开始时间
 *    String    endDate            Y    主题结束时间
 *    String    showbarAuthScope    Y    授权范围类型
 *				{
 *				All                全部
 *            	All_extend_externalStaff    全部（外部人员除外）
 *            	Part                部分授权
 *            	All_group            全集团
 *				}
 *    String    showbarAuth        Y    授权范围字符串
</pre>

 * @return 返回对象com.seeyon.apps.show.po.ShowbarInfo
 * 
<pre>

 *     成功 {success:true,data:showBarData}
 *                 showBarData    来自于对象com.seeyon.apps.show.po.ShowbarInfo
 *                         {
 *                         "accountId"    所属单位ID,
 *                         "commentNum"    评论总数,
 *                         "coverPicture"    封面图片ID(对应show_imgae表),
 *                         "createFrom"    创建自：PC、M1,
 *                         "createTime"    创建时间,
 *                         "createUserId"    秀吧创建人ID,
 *                         "extraMap"    额外信息,
 *                         "id"    秀吧id,
 *                         "imgNum"    照片总数,
 *                         "likeNum"    点赞次数,
 *                         "new"    是否为新建,
 *                         "orderNum"    序号,
 *                         "settopTime"    置顶时间（未置顶则为空）,
 *                         "showbarName"    秀吧名称,
 *                         "status"    状态标识：0删除，1正常，2系统预制秀,
 *                         "viewNum"    浏览次数
 *                        }
 *    失败 {success:false,msg:errorMessage}
 *
</pre>

 * @throws BusinessException    出错信息
 */
@POST
@Path("showbar")
@Consumes({MediaType.APPLICATION_XML,MediaType.APPLICATION_JSON})
public Response saveShowbarInfo(Map<String,Object> params)throws BusinessException



## 6. Response返回值定义

## 6.1. 原则

平台统一定义格式，各应用只需要传入数据及消息信息

成功的请求

{
  code: 0,
  data: 返回数据,
  message: 'messges if exists'
}


失败的请求

{
  code: 1,
  message: 'error messges'
}


message定义

如果是要提示给最终用户的message，必须进行国际化

成功的请求

大家只需要关心data内的内容，如果有需要传递的消息，请设置msg参数（非必填，如传空，平台将不返回该字段）

失败的请求

message必须填写,且内容恰当

## 6.2. 返回值示例

必须return Response，而不是具体的POJO对象；不允许自己进行JSON的toString，直接调用success或者fail方法由框架进行JSON转换。

// 错误
public V3xOrgMember getMemberByLoginName(
        @QueryParam("loginName") String loginName) throws Exception {
    return getOrgManager().getMemberByLoginName(decode(loginName));
}

// 正确
public Response getMemberByLoginName(
        @QueryParam("loginName") String loginName) throws BusinessException {
	try{
		// 成功操作，返回对象数据
		return success(getOrgManager().getMemberByLoginName(decode(loginName)));
	}catch(Exception e){
		log.error("根据LoginName获取人员数据异常:"+loginName, e);
		// 失败操作，返回异常信息
		return fail("获取数据异常");
	}
}



## 7. Spring bean引用

因为所有的REST实现都不受Spring管理，所以对于Spring bean不能采取依赖注入方式，请按照下面的方式进行处理

public class MemberResource extends BaseResource {
    private OrgManager orgManager;
    public OrgManager getOrgManager() {
        if (orgManager == null) {
            orgManager = (OrgManager) AppContext.getBean("orgManager");
        }
        return orgManager;
    }

    @GET
    @Path("{id}")
    @Produces(MediaType.APPLICATION_JSON)
    @RestInterfaceAnnotation
    public Response get(@PathParam("id") long id) throws Exception {
        return ok(getOrgManager().getEntityById(getActualClass(), id));
    }
}



## 8. JSON输出过滤和扩展

## 8.1. JSON过滤

不输出实体的某些属性，比如

{
  "orgAccountId" : -7580270040522800906,
  "id" : -4133790465478605204,
  "name" : "自动1",
  "code" : "5",
  "createTime" : 1429064089000,
  "updateTime" : 1429064089000,
  "sortId" : 0,
  "isDeleted" : false,
  "enabled" : true,
  "status" : 1,
  "description" : "",
  "orgLevelId" : 8562916345585944089,
  "orgPostId" : -2379980414295520995,
  "orgDepartmentId" : -5380398112991065519,
  "password" : "123456" ,
  ......
}


不希望输出V3xOrgMember的password属性。

 * 侵入式修改，在需要过滤的域的get方法上加@JsonIgnore注解。

  public class V3xOrgMember
      @JsonIgnore
      public String getPassword() {
      }
  }


 * 非侵入式修改

  // 定义一个空的类，增加注解列出要过滤的class
  @JsonIgnoreProperties(value = { "v3xOrgPrincipal", "password" })
  public class MemberWriteFilter {
  }
  // 初始化时调用注册Mixin
  com.seeyon.ctp.rest.util.MapperFactory.getInstance().addMixInAnnotations(V3xOrgMember.class, MemberWriteFilter.class);


所有的V3xOrgMember转为JSON时将不输出过滤的属性列表

## 8.2. JSON扩展

需要在输出的Bean基础上增加属性时使用，比如输出V3xOrgMember时输出所在单位的名称orgAccountName

com.seeyon.ctp.rest.util.MapperFactory.getInstance().register(V3xOrgMember.class,new  BeanSerializerFactory.Builder() {   
    public Map addFields(Object bean) {
        Map<String,String> data = new HashMap<String,String>();
        V3xOrgMember member = (V3xOrgMember) bean;
        long orgAccountId = member.getOrgAccountId();
        data.put("orgAccountName",orgManager.getAccountById(orgAccountId).getName());
        data.put("orgDepartmentName",balabala);
        data.put("orgPostName",balabala);
        return data;
    }
});



## 9. 分页

统一使用pageSize和pageNo两个QueryParam控制分页

// CTP获取FlipInfo对象
getFlipInfo();
// V3X的迁移代码在方法实现首行进行设置
setPagination();



## 10. 国际化

编写Rest接口时无需特殊处理国际化内容，只是编写代码中如涉及到国际化提示语反馈需要使用CTP的标准国际化组件。

以下内容是：如有国际化远程调用需求用户，需要在调用前传递对应的语言，以确保获取准确的结果数据。

通过http header的Accept-Language控制国际化使用的语言

  Accept-Language:en_US


REST Client中提供方法设置语言

client.setLocale(Locale.SIMPLIFIED_CHINESE);


JSSDK中缺省以浏览器的语言进行国际化，取不到浏览器语言时使用zh_CN 如果需要强制指定，可以在最后一个参数中使用AcceptLanguage指定语言。

$s.Token.getToken('rest','123456','',{
    'AcceptLanguage':'zh_CN'
})



## 11. 当前用户

禁止通过前端传递member的id，比如取某某用户的待办。必须同时支持以下两种方式：

1.从Header和QueryParam中取ticket，通过ticket获取member的Id。

2.如果ticket为空，在Resource层取CurrentUser（禁止在Manager、Api、Dao层取）。 如果取不到CurrentUser，而且也没有传递ticket则抛出异常。

已经支持token绑定用户，绑定用户后任何地方的代码获取当前用户就不会是null了，有两种绑定方式：

1、获取Token时加?loginName=s1参数

POST http://127.0.0.1/seeyon/rest/token/?loginName=s1 HTTP/1.1
Accept: application/json
Host: 127.0.0.1
Content-Type: application/json
Content-Length: 39

{"userName":"rest","password":"123456"}


2、获取Token后单独调用 PUT /rest/token {"token":"xxx", "loginName":"xxx"} 进行绑定


## 12. 内容协商

对于实体返回，建议同时支持JSON和XML，在Resource的Class或方法加入如下声明

@GET
@Path("{userName}/{password}")
@Produces({MediaType.APPLICATION_JSON,MediaType.APPLICATION_XML})
public Response getToken(@PathParam("userName") String userName,
    @PathParam("password") String password,
    @QueryParam("loginName") String loginName,
    @QueryParam("userAgentFrom") String userAgentFrom) throws Exception {
    return ok(_getToken(userName, password,loginName,userAgentFrom));
}


ok方法会根据请求header的accept自动返回json或xml。

如果需要返回html和纯文本，可以新建一个方法，使用相同的Path

@GET
@Path("{userName}/{password}")
@Produces(MediaType.TEXT_PLAIN)
public Response getTokenString(@PathParam("userName") String userName,
    @PathParam("password") String password,
    @QueryParam("loginName") String loginName,
    @QueryParam("userAgentFrom") String userAgentFrom) throws Exception {
    UserToken token = _getToken(userName, password,loginName,userAgentFrom);
    return ok(token.getId());
}


例如请求：

GET http://127.0.0.1/seeyon/rest/token/rest/123456 HTTP/1.1
Accept: application/json
Host: 127.0.0.1


返回

{
  "bindingUser" : null,
  "id" : "a5ad648c-0a40-49b0-bedd-9fd7025313b5"
}


请求

GET http://127.0.0.1/seeyon/rest/token/rest/123456 HTTP/1.1
Accept: application/xml
Host: 127.0.0.1


返回

<UserToken><bindingUser/><id>55b69a17-b2be-4dfa-80ac-c3a211ec652d</id></UserToken>


请求

GET http://127.0.0.1/seeyon/rest/token/rest/123456 HTTP/1.1
Accept: text/plain
Host: 127.0.0.1


返回

d72640bd-48b0-46cd-87a1-ca9a449da185



## 代码示例


## 常见问题

获取token报错：java.lang.NoSuchMethodError: org.codehaus.stax2.XMLStreamWriter2.writeLong(J)V

此问题在个别客户环境发生，stax2-api.jar和wstx-asl.jar冲突导致。

原因：jackson-dataformat-xml.jar包的ToXmlGenerator类中使用了XMLStreamWriter2接口，但stax2-api.jar和wstx-asl.jar包都定义了XMLStreamWriter2接口。stax2-api.jar包中XMLStreamWriter2接口的实现类Stax2WriterAdapter中有writeLong方法。

解决方法：停止协同服务，将webapps\seeyon\WEB-INF\lib\wstx-asl.jar包剪切走备份，启动协同服务。

获取token返回值有时字符串，有时json格式

参考本文“内容协商”章节，需要在发送请求时在header中固定Accpet参数：

--application/json为json格式
--text/plain为字符串格式


没加token会报：被迫下线的错误



获取token的接口，rest账号密码不正确，会返回401无权限问题



rest用户未授权，会给出明确提示，需要在管理Rest帐号的地方配置权限



报500错误

可能是post方式下，内容格式或某数据的类型错误

编撰人：lichaoj、het、admin




快速跳转



 * REST接口代码规范
   * 适用范围
   * REST开发规范
     * 1. 原则
     * 2. 协议约定
     * 3. 代码规范
     * 4. URL命名
       * 4.1. URL例
     * 5. 代码注释规范
       * 5.1. 原则
       * 5.2. 注释示例
     * 6. Response返回值定义
       * 6.1. 原则
       * 6.2. 返回值示例
     * 7. Spring bean引用
     * 8. JSON输出过滤和扩展
       * 8.1. JSON过滤
       * 8.2. JSON扩展
     * 9. 分页
     * 10. 国际化
     * 11. 当前用户
     * 12. 内容协商
   * 代码示例
   * 常见问题



分享链接分享链接

## 50. 门户

> 原始路径：`/39/790/`  
> 相对路径：`39/790/README.md`

## 门户

适用版本：V7.0及其以上版本


## 关于门户的定制方式

门户支持三种定制模式：基于门户设计器界面的定制、基于门户模板导入导出的定制和基于代码开发的定制。

 * 基于门户界面的定制：这种定制方式，主要通过设计器界面对门户的相关属性进行修改，比如门户模板样式、皮肤样式、栏目外框样式等，这种定制方式无需重启服务即可生效。
 * 基于导入导出的定制：这种定制方式，主要通过将门户组成的所有资源导出一个ZIP包，用户可以用WINRAR工具解开这个ZIP包，可以对相关的门户资源进行修改，然后重新打一个ZIP包，再重新导入系统中形成一个新的门户模板，这种定制方式也无需重启服务即可生效。
 * 基于代码开发的定制：这种定制方式，主要是开发人员通过遵循门户规范，去开发实现门户的各个组成部分，从而开发出一套新的门户模板。这种定制方式需要重启服务才能生效。


## 本手册包含的内容

本手册主要以具体例子来对第二种【基于导入导出的定制】和第三种【基于代码开发的定制】定制方式进行详细说明，以指导开发人员进行门户的定制开发实战。但可能会顺带介绍一些门户规范和原理，但不会对这块进行专门的介绍。 同时本手册也对门户对外提供的其它API如何使用也进行了说明。


## 对阅读者的要求

本手册主要面向开发人员，你需要熟练掌握如下开发知识和技术：

 * HTML：超文本标记语言（英语：HyperText Markup Language，简称：HTML）是一种用于创建网页的标准标记语言。您可以使用 HTML 来建立自己的 WEB 站点，HTML 运行在浏览器上，由浏览器来解析。

 * CSS: 是一种用来表现HTML（标准通用标记语言的一个应用）或XML（标准通用标记语言的一个子集）等文件样式的计算机语言。CSS不仅可以静态地修饰网页，还可以配合各种脚本语言动态地对网页各元素进行格式化。CSS 能够对网页中元素位置的排版进行像素级精确控制，支持几乎所有的字体字号样式，拥有对网页对象和模型样式编辑的能力。

 * JAVASCRIPT：JavaScript是一种属于网络的脚本语言,已经被广泛用于Web应用开发,常用来为网页添加各式各样的动态功能,为用户提供更流畅美观的浏览效果。通常JavaScript脚本是通过嵌入在HTML中来实现自身的功能的。是一种解释性脚本语言（代码不进行预编译）。主要用来向HTML（标准通用标记语言下的一个应用）页面添加交互行为。

 * JSON：JSON 指的是 JavaScript 对象表示法（JavaScript Object Notation），是轻量级的文本数据交换格式。JSON 使用 Javascript语法来描述数据对象，但是 JSON 仍然独立于语言和平台。JSON 解析器和 JSON 库支持许多不同的编程语言。 目前非常多的动态（PHP，JSP，.NET）编程语言都支持JSON。

 * LAYTPL：laytpl 是 JavScript 模板引擎，在字符解析上有着比较出色的表现，laytpl 的模板可与数据分离，集中把逻辑处理放在 View 层，提升代码可维护性，尤其是针对大量模板渲染的情况。

 * XML：XML 指可扩展标记语言(eXtensible Markup Language)。 XML 被设计用来传输和存储数据。

 * AJAX：Ajax 即“Asynchronous Javascript And XML”（异步 JavaScript 和 XML），是指一种创建交互式网页应用的网页开发技术。

 * JAVA：Java 是由Sun Microsystems公司于1995年5月推出的高级程序设计语言。Java可运行于多个平台，如Windows, Mac OS，及其他多种UNIX版本的系统。

上面列出来的是一个比较全面的门户开发知识和技术要求，是进行第3种门户定制开发必须具备的，但如果您只是进行第2种门户定制开发，不涉及新增门户后台数据接口，则掌握了上面提到的：HTML、CSS、JAVASCRIPT、JSON、LAYTPL、XML、AJAX即可。


## 开始定制开发


## 基于导入导出的定制

我们可以用集团管理员或单位管理员登录系统，进入V-Portal配置平台，分别对下述内容进行导入导出定制。

门户模板定制 门户模板ZIP包介绍 进入【整体样式库】，选择“网站式信息门户”导出，如下图：









1、portal/images：该目录存放门户模板用到的所有图片文件；

2、portal\pagelayout\layout\layout02：该目录存放门户布局相关文件，其中layout02为门户布局代码。这个目录下会存放3个文件：layout02_b.html、layout02_b.css和layout02_b.js。layout02_b.html文件为门户布局html文件，layout02_b.css为门户布局样式文件，layout02_b.js为该门户特有的JavaScript脚本。后面会对门户布局的概念进行专门介绍，在这里记住门户布局由1个html文件、1个css文件和1个js文件组成即可。

对门户布局的解释

产品中自带了常见的门户布局，能够满足大部分需求，详细见《附录1：门户布局规范》。

开发建议：在定义门户布局时尽量使用产品自带的门户布局，在这个基础上在进行扩展，这样的好处是可以在门户设计器中对门户布局的各个区域的属性进行配置定义，例如门户布局中个区域的背景色和背景图片等。

通过门户布局规范可以知道，门户布局是指将门户页面划分为若干区域，如何划分门户区域，这个跟客户对门户的需求有关系，举个例子：比如客户希望单位LOGO和名称放在最上面靠左，退出按钮放在最右上角，菜单摆在单位LOGO和单位名称的下面，菜单内容下面为内容区。根据这个描述，我们可以将门户布局划分如下图所示：



门户布局html文件，只包含html内容，但在html的dom元素上会有致远门户自定义属性，以layout02_b.html为例，内容如下：



注意：主要是红色框中的内容：class=”seeyon-portal-header”标识门户头部区；class=” seeyon-portal-body”标识门户内容区；class=” seeyonElementGroup”标识门户元素分组，门户元素分组中可以包含多个门户元素；class=” seeyonElement”标识门户元素，门户元素中的id和data-tpl两个属性必须指定，其中id的值必须保证唯一性，data-tpl的值必须跟门户元素的文件名相同，门户元素包含哪些内容，后面马上会介绍到。

1、portal\pagelayout\element：该目录存放门户元素相关文件，每个门户元素包含3个文件：1个html文件、1个js文件、1个css文件。例如幻灯片元素tpl-slideVPortal.html、tpl-slideVPortal.js、tpl-slideVPortal.css。 门户元素的这三个文件要求必须以tpl-开头，除了后缀不通外，文件名称必须相同。 门户元素html文件需要符合laytpl前端模板引擎规范。例如tpl-slideVPortal.html内容如下：



注意：上面文件内容中

## 51. 内嵌页面跨域报错

> 原始路径：`/39/790/1159/1160.html`  
> 相对路径：`39/790/1159/1160.md`

## 内嵌页面跨域报错


## 背景介绍：

因客户需求，客开将门户页面 ehrtg.yintai-centre.com 使用iframe内嵌到客户的页面 portalt.yintai-centre.com 中。


## 报错信息：

Uncaught DOMException: Blocked a frame with origin "https://xxxxx.com" from accessing a cross-origin frame



注： IE的控制台上可能报“拒绝访问”


## 触发点：

发现门户中的iframe在使用 parent.vPortal 时会报错，只要是调用parent上的方法、属性等，都会报错。


## 排查步骤：

 1. 门户 ehrtg.xxx-centre.com 是使用iframe内嵌到客户网页 portalt.xxx-centre.com 中， 将门户页面使用浏览器直接打开，发现问题仍然存在。

 2. 因发生点位置是门户页面中的一个iframe， 在门户中使用iframe打开其它页面，然后在iframe中测试调用parent上的方法，发现内嵌的iframe，只要调用parent，就会触发跨域问题。

 3. 排查门户页面(top)的 document.domain 与 iframe中页面的 document.domain，发现前者为xxx-centre.com ，后者为 ehrtg.xxx-centre.com 。两者在二级域名有差异，怀疑问题点在这里，继续排查。



 4. 手动将门户页面(top)的 document.domain 设置成 ehrtg.xxx-centre.com 后， 在iframe中调用 parent.vPortal 不再报错，定位到问题点。

 5. 因当前地址栏中的地址为 htts://ehrtg.xxx-centre.com ， iframe中的地址为相对路径，且iframe的document.domain与地址栏中的域名一致，判断问题点在门户（top）的 document.domain。

 6. 排查门户的doc， 发现在head中，有对document.domain进行赋值。使用overrides进行覆盖测试， 将下图中的代码注释掉后， iframe能正常访问parent中的方法，问题排查完成。




## 总结：

如果各方面跨域相关配置完成，门户页面能正常渲染的情况下，发现门户内嵌iframe无法正常显示，一直报跨域问题， 优先排查门户页面是否更改了"document.domain"

编撰人：chuhc、het




快速跳转



 * 内嵌页面跨域报错
   * 背景介绍：
   * 报错信息：
   * 触发点：
   * 排查步骤：
   * 总结：



分享链接分享链接

## 52. 收到消息无法正常刷新栏目

> 原始路径：`/39/790/1159/1161.html`  
> 相对路径：`39/790/1159/1161.md`

## 收到消息无法正常刷新栏目


## 收到消息后刷新栏目的逻辑：

消息返回参数中，有一个key为”L” 变量， 该变量携带了相应的消息类别， 需要通过该消息类别map到对应的栏目sectionBeanId， 然后调用栏目刷新方法。


## 常见问题：

 1. 集成了第三方待办， L值为message.link.cip.message.url，对应的sectionBeanId为thirdPendingSection 。 页面上栏目的sectionBeanId 为pendingSection，所以无法刷新。
 2. 执行“撤回”操作，消息响应中不包含”L”参数，所以无法刷新。


## 代码位置：

压缩后存在于portal-min.js中，可查找sectionMappingLinkType



编撰人：chuhc、het




快速跳转



 * 收到消息无法正常刷新栏目
   * 收到消息后刷新栏目的逻辑：
   * 常见问题：
   * 代码位置：



分享链接分享链接

## 53. 登录页面设置视频无法自动播放

> 原始路径：`/39/790/1159/1162.html`  
> 相对路径：`39/790/1159/1162.md`

## 登录页面设置视频无法自动播放


## 问题原因：

浏览器机制限制， 非静音视频不能自动播放


## 说明：

登录页面使用videojs提供播放能力，增加配置 muted: true 使页面静音即可


## 视频播放问题常见排查步骤：

 1. 浏览器开启override
 2. 定位videojs对象创建页面
 3. 设置controls为true，显示控制台，排查页面加载时视频是否为暂停状态。
 4. 核对videojs官方文档，排查配置是否有误。
 5. 如果配置无误，仍然无法自动播放，需排查浏览器规则。
    编撰人：chuhc、het


快速跳转



 * 登录页面设置视频无法自动播放
   * 问题原因：
   * 说明：
   * 视频播放问题常见排查步骤：



分享链接分享链接

## 54. 常见栏目刷新方法

> 原始路径：`/39/790/1163/1164.html`  
> 相对路径：`39/790/1163/1164.md`

## 常见栏目刷新方法


## 门户栏目更新方法汇总


## 总的来说， 刷新门户的方法在各个地方可能都单独进行过封装， 但绝大部份，最后都会去调用renderTpl方法（有两处文件都有此方法，需要注意）。

排查时，可以将断点打在renderTpl，然后通过调用栈，分析父级调用逻辑。 下面为一些常见的栏目刷新方法


## 一. 刷新栏目内容

 1. 刷新栏目： renderEachPanel(pannelId)
 2. 刷新所有栏目： renderAllSection(spaceId)
 3. 监听消息，刷新栏目 ：文件onlinemessage.js 其中 function refreshSection(linkTypes) 方法负责刷新门户栏目。 收到消息后不刷新，可能跟linkTypes有关， 该参数依赖与消息中的”L”参数，如果返回值中没有此参数，将不会引起栏目的刷新。
 4. 根据sectionBeanId，刷新指定类型栏目： vPortal.sectionHandler.reload，常在协同处理完后，刷新门户对应栏目时遇到。


## 二. 刷新栏目页签后的数字

 1. updateCurrentPortletAllTotal
 2. renderTotalFromData
    编撰人：chuhc、het


快速跳转



 * 常见栏目刷新方法
   * 门户栏目更新方法汇总
   * * 一. 刷新栏目内容
     * 二. 刷新栏目页签后的数字



分享链接分享链接

## 55. 基于代码的定制

> 原始路径：`/39/790/1165/`  
> 相对路径：`39/790/1165/README.md`

## 基于代码的定制

----------------------------------------

门户模板由门户布局（含门户元素）、门户主皮肤样式、栏目外框样式、二级页面样式、图标样式、图表样式组成，下面会分别讲述，如何基于代码来定制相关内容。

关键标签说明：

名称              说明           来源
templateID      主题模板ID       portal_themes_pc.xml
tid             门户布局模板ID     portal_template_pc.xml
msid            门户主皮肤ID      portal_skins_pc.xml
Ssid            门户栏目外框样式ID   portal_skins_section.xml
Csid            二级页面组件样式ID   portal_skins_page.xml
Iconid          门户图标风格ID     
echartStyleid   门户图表样式ID     
ext10           整体皮肤的ID      portal_skin_set_pc.xml

基于代码开发新模板，需要在多个xml文件中对多种模板进行注册， 各配置文件的关系图参考下图所示（黄框中为示例代码）：



编撰人：chuhc


快速跳转



 * 基于代码的定制



分享链接分享链接

## 56. 01 注册门户模板信息

> 原始路径：`/39/790/1165/1166.html`  
> 相对路径：`39/790/1165/1166.md`

## 01 注册门户模板信息

----------------------------------------

要新增一套门户模板， 则需要先注册该套模板的基础信息。

在安装目录文件 /webapps/seeyon/portal/config/portal_themes/portal_themes_pc.xml 中注册PC门户模板，添加内容如下所示：

<PortalThemes><!-- 以下是需要添加的部份 -->
	<PortalTheme>
		<id>2000000001</id>
		<code>theme01</code>
		<name>portal.theme.name.1</name>
		<accountId>0</accountId>
		<sysinit>1</sysinit>
		<sort>1</sort>
		<previewImg>/portal/images/themes/theme_pc_01.png</previewImg>
		<isdelete>0</isdelete>
		<type>0</type>
		<category>1</category>
		<productId></productId>
	</PortalTheme>
<!-- 以上是需要添加的部份 -->
</PortalThemes>


 * PortalTheme 标签表示一个门户模板。
 * id 表示门户模板的唯一标识，PC的门户模板以20开头，移动的门户模板以21开头，登录前门户以22开头，大屏门户以23开头，必须全为数字，同时要确保唯一性。
 * code 标识门户模板的代码，建议英文字符+数字，确保唯一性。
 * name 标识门户模板的名称，不能含有特殊字符，使用国际化的的代码。
 * acountId 预制门户的单位ID，统一设置为0即可。
 * systeminit ：是否为预制，这里填写为1，标识为预制。
 * sort ：标识门户模板的显示顺序。
 * previewImg ：标识为门户模板的预览示意图。
 * isdelete ：标识是否删除，这里一般为0即可。
 * type ：标识门户模板类型：0标识为PC，1标识为移动；2标识为登录前，3标识为大屏

注意：如果是移动门户模板，则需要在文件portal*themes*mobile.xml中注册；如果是登录前门户，则需要在文件portal*themes*loginPre.xml中注册；如果是大屏门户，则需要在文件portal*themes*bigScreen.xml中注册

编撰人：chuhc




快速跳转



 * 01 注册门户模板信息



分享链接分享链接

## 57. 02 注册整体皮肤

> 原始路径：`/39/790/1165/1167.html`  
> 相对路径：`39/790/1165/1167.md`

## 02 注册整体皮肤

----------------------------------------

在安装目录文件 webapps/seeyon/portal/config/portal_skin_set/portal_skin_set_pc.xml 中注册PC门户的整体皮肤，添加内容如下所示：

<PortalSkinSets> <!-- 以下为需要添加的代码 -->
	<PortalSkinSet>
		<id>4000000001</id>
		<code>harmony</code>
		<name>和谐之美</name>
		<msid>3000000001</msid>
		<ssid>3400000001</ssid>
		<csid>3700000001</csid>
		<iconid>1</iconid>
		<echartStyleid>1</echartStyleid>
		<deft>1</deft>
		<sysinit>1</sysinit>
		<sort>1</sort>
		<imageOrColor>/portal/images/skins/skin_pc_01.png</imageOrColor>
		<type>0</type>
	</PortalSkinSet> <!-- 以上为需要添加的代码 -->
</PortalSkinSets>


 * PortalSkinSet 标签标识一套门户整体皮肤；
 * id 唯一标识整体皮肤；PC门户整体皮肤从40开始，移动门户整体皮肤从41开始，登录前门户整体皮肤从42开始，大屏门户整体皮肤从43开始；且必须是数字类型。
 * code 表示整体皮肤代码；
 * name 表示整体皮肤的名称，不能有特殊字符；
 * msid 表示门户主皮肤ID
 * ssid 表示门户栏目外框样式ID
 * csid 表示二级页面组件样式ID
 * iconid 表示门户图标风格ID
 * echartStyleid 表示门户图表样式ID
 * deft 表示是否为系统默认
 * sysinit 表示是否为系统预制
 * sort 表示整体皮肤排序
 * imageOrColor 表示整体皮肤的预览示意图；
 * type ：标识整体皮肤类型：0标识为PC，1标识为移动；2标识为登录前，3标识为大屏 注意：如果是移动门户模板，则需要在文件 portal_skin_set _mobile.xml 中注册；如果是登录前门户，则需要在文件 portal_skin_set_loginPre.xml 中注册；如果是大屏门户，则需要在文件 portal_skin_set_bigScreen.xml 中注册。
   编撰人：chuhc


快速跳转



 * 02 注册整体皮肤



分享链接分享链接

## 58. 03 注册门户模板与整体皮肤的绑定关系

> 原始路径：`/39/790/1165/1168.html`  
> 相对路径：`39/790/1165/1168.md`

## 03 注册门户模板与整体皮肤的绑定关系

----------------------------------------

在安装目录文件 webapps/seeyon/portal/config/portal_skin_choice/portal_skin_choice.xml 中注册门户模板与整体皮肤的绑定关系，添加内容如下所示：

<PortalSkinChoices> <!-- 以下是需要添加的部份 -->
	<PortalSkinChoice>
		<id>6977749752117152012</id>
		<templateId>2000000001</templateId>
		<entityType>group</entityType>
		<entityId>0</entityId>
		<currentAccountid>0</currentAccountid>
		<skinStyle>4000000001</skinStyle>
	</PortalSkinChoice> <!-- 以上是需要添加的部份 -->
</PortalSkinChoices>


 * PortalSkinChoice 标签标识门户模板绑定哪套整体皮肤；
 * id 是门户模板与整体皮肤绑定关系的唯一标识；
 * templateId 为门户模板ID；
 * entityType 为组织模型类型，这里默认为group；
 * entityId 为组织模型ID，这里默认为0；
 * currentAccountid 为当前单位ID，这里默认为0；
 * skinStyle 表示整体皮肤ID；
   编撰人：chuhc


快速跳转



 * 03 注册门户模板与整体皮肤的绑定关系



分享链接分享链接

## 59. 04 注册门户皮肤

> 原始路径：`/39/790/1165/1169.html`  
> 相对路径：`39/790/1165/1169.md`

## 04 注册门户皮肤

----------------------------------------

在安装目录文件 webapps/seeyon/portal/config/portal_skins/portal_skins_pc.xml 中注册PC门户的主框架皮肤，添加内容如下所示：

<PortalSkins> <!-- 以下是需要添加的部份 -->
	<PortalSkin>
		<id>3000000001</id>
		<code>skin01</code>
		<name>主框架皮肤01</name>
		<path>/portal/pagelayout/skin/01.css</path>
		<stype>0</stype>
		<image></image>
		<sysinit>1</sysinit>
		<sort>1</sort>
		<isdelete>0</isdelete>
		<accountId>0</accountId>
	</PortalSkin> <!-- 以上是需要添加的部份 -->
</PortalSkins>


 * PortalSkin 标签标识一个皮肤样式文件；

 * id 标识皮肤的唯一标识；PC门户主框架样式皮肤以30开头；PC门户栏目外框样式皮肤以34开头；PC门户二级页面样式皮肤以37开头；移动端门户皮肤以31开头；登录前门户皮肤以32开头；大屏皮肤以33开头；

 * code 标识皮肤的代码；

 * name 标识皮肤的名称；

 * path 标识皮肤css文件所在的路径，其中文件内容需要遵循CSS规范；

 * stype 标识皮肤类型：0为PC普通门户；1为移动门户；2为登录前门户；3为大屏门户；

 * image 标识皮肤预览图片；

 * sysinit 标识是否系统初始化；

 * sort 标识排序；

 * isdelete 标识是否删除；

 * accountId 标识单位ID，预制的默认都为0。
   
   注意： 如果为移动门户皮肤，则需要在portal_skins_mobile.xml文件中注册； 如果为大屏门户皮肤，则需要在portal_skins_bigScreen.xml文件中注册； 如果为登录前门户，则在portal_skins_loginPre.xml文件中注册； 如果为栏目外框皮肤，则在 portal_skins_section.xml文件中注册； 如果为二级页面组件皮肤，则在portal_skins_section.xml文件中注册。
   
   编撰人：chuhc
   
   


快速跳转



 * 04 注册门户皮肤



分享链接分享链接

## 60. 05 注册门户布局

> 原始路径：`/39/790/1165/1170.html`  
> 相对路径：`39/790/1165/1170.md`

## 05 注册门户布局

----------------------------------------

在安装目录webapps/seeyon/portal/pagelayout/layout 下新建一个门户布局目录layout_c001，然后在此目录下新建三个文件：layout_c001_a.html、layout_c001_a.css、layout_c001_a.js，

并根据需求开发对应内容。 在安装目录文件webapps/seeyon/portal/config/portal_template/portal_template_pc.xml中注册该门户布局，添加内容如下所示：

<PortalTemplates>
    <PortalTemplate>
        <id>1000000001</id>
        <name>模板04a</name>
        <path>/portal/pagelayout/layout/layout04/layout04_a.html</path>
        <thumbnail>/portal/pagelayout/layout/layout04/layout04_a.jpg</thumbnail>
        <preset>1</preset>
        <description>主框架layout04_a</description>
        <sort>1</sort>
        <cdefault>0</cdefault>
        <layout>layout04</layout>
        <layoutName>layout04</layoutName>
        <styleCode>layout04_a</styleCode>
        <cssPath>/portal/pagelayout/layout/layout04/layout04_a.css</cssPath>
        <jsPath>/portal/pagelayout/layout/layout04/layout04_a.js</jsPath>
        <type>0</type>
    </PortalTemplate>
</PortalTemplates>


编撰人：chuhc


快速跳转



 * 05 注册门户布局



分享链接分享链接

## 61. 06 新建门户模板图片资源存放位置

> 原始路径：`/39/790/1165/1171.html`  
> 相对路径：`39/790/1165/1171.md`

## 06 新建门户模板图片资源存放位置

----------------------------------------

在安装目录/webapps/seeyon/portal/pagelayout/layout/layout_c001 下新建一个图片资源目录images，

新开发的门户模板中用到的图片资源必须都放到这个目录下，例如html文件中使用的图片文件，

css文件中使用的图片文件，js文件中使用的图片文件，所有使用图片文件都必须使用全路径

引用 /seeyon/portal/pagelayout/layout/layout_c001/images/xxx.png ，图片资源支持gif、png和jpg三种格式。

编撰人：chuhc




快速跳转



 * 06 新建门户模板图片资源存放位置



分享链接分享链接

## 62. 07 注册门户元素

> 原始路径：`/39/790/1165/1172.html`  
> 相对路径：`39/790/1165/1172.md`

## 07 注册门户元素

----------------------------------------

在安装目录webapps/seeyon/portal/pagelayout/element/custom 下新建为每个门户元素新建三个文件：tpl-xxx.html、tpl-xxx.css、tpl-xxx.css。 在安装目录文件 webapps/seeyon/portal/config/portal_laytpl_template/elements.xml 中注册改门户模板，添加内容如下所示：

<?xml version="1.0" encoding="UTF-8"?>
<laytpls version="1.0" vendor="www.seeyon.com">
  <laytpl>
    <id><![CDATA[0]]></id>
    <code><![CDATA[tpl-demo]]></code>
    <name><![CDATA[示例元素]]></name>
    <htmlPath><![CDATA[/portal/pagelayout/element/tpl-demo.html]]></htmlPath>
    <jsPath><![CDATA[/portal/pagelayout/element/tpl-demo.js]]></jsPath>
    <cssPath><![CDATA[/portal/pagelayout/element/tpl-demo.css]]></cssPath>
  </laytpl>
</laytpls>


编撰人：chuhc


快速跳转



 * 07 注册门户元素



分享链接分享链接

## 63. 08 开发和注册栏目

> 原始路径：`/39/790/1165/1173.html`  
> 相对路径：`39/790/1165/1173.md`

## 08 开发和注册栏目

----------------------------------------

第一步：栏目模板开发 栏目模板是指栏目长的是什么样子，例如列表样子、棋盘样式、图片轮播样式等，一个栏目模板由4个文件组成：1个html文件、1个js文件、1个css文件和1个java文件，其中html文件必须遵循laytpl模板引擎语法，1个java文件必须实现com.seeyon.ctp.portal.section.templete. BaseSectionTemplete基类。 以目前系统中已有栏目模板横幅模板（bannerTemplete）为例，所包含的内容如下所示：

 * tpl-bannerTemplete.html
 * tpl-bannerTemplete.js
 * tpl-bannerTemplete.css
 * com.seeyon.ctp.portal.section.templete.BannerTemplete 在确定了栏目要显示哪些内容后，就可以按照上面的示例内容进行栏目模板的开发。 在安装目录文件webapps/seeyon/portal/config/portal_laytpl_template/sections.xml中注册该栏目模板，添加内容如下所示：

> 注：低版本portal_laytpl_template/sections.xml文件存放于ctp-portal工程，自V9.0SP1开始，文件存放于ctp-portal-xfront工程。

<?xml version="1.0" encoding="UTF-8"?>
<laytpls version="1.0" vendor="www.seeyon.com">
  <laytpl>
    <id><![CDATA[6288512492262214147]]></id>
    <code><![CDATA[tpl-bannerTemplete]]></code>
    <name><![CDATA[栏目模板-横幅]]></name>
    <htmlPath><![CDATA[/portal/sections/tpl/tpl-bannerTemplete.html]]></htmlPath>
    <jsPath><![CDATA[/portal/sections/tpl/tpl-bannerTemplete.js]]></jsPath>
    <cssPath><![CDATA[/portal/sections/tpl/tpl-bannerTemplete.css]]></cssPath>
  </laytpl>
</laytpls>


第二步：实现栏目后台java接口 PC和移动统一在同一个接口类com.seeyon.ctp.portal.section.BaseSection中定义，同时返回BaseSectionTemplete的栏目模板实例。具体定义如下：

 * PC接口

**public** **abstract** BaseSectionTemplete projection(Map<String, String> preference);


 * 移动接口

**public** **abstract** BaseSectionTemplete mProjection(Map<String, String> preference);


第三步：在spring.xml配置文件中注册栏目接口和配置栏目属性 以横幅栏目实现类BannerSection为例，在spring.xml配置文件中的配置信息如下图所示： 一、栏目可以配置的属性如下表所示： 1.一个栏目属性一般通过下面几个方面的信息进行描述清楚： 2.支持的栏目属性数据类型 支持的数据类型如下表所示：



 1. 一个具体栏目可以配置1到n个上述栏目属性。

注意：一个属性可以在PC端和移动端同时使用，也可以不同时使用，这个是通过在属性配置增加如下内容来配置区分：

 * defaultPC：表示PC端栏目属性；
 * m3mobile：表示移动端栏目属性；

二、栏目的分类和所属空间配置：



编撰人：chuhc、het




快速跳转



 * 08 开发和注册栏目



分享链接分享链接

## 64. 09 开发和注册依赖的第三方JS文件

> 原始路径：`/39/790/1165/1174.html`  
> 相对路径：`39/790/1165/1174.md`

## 09 开发和注册依赖的第三方JS文件

----------------------------------------

如果栏目有依赖的第三方js文件，则需要单独在配置文件中配置，配置文件所在位置为webapps/seeyon/portal/config/portal_section_jsfiles/pc.xml，内容如下图所示：

<?xml version="1.0" encoding="UTF-8"?>  
<sectionTpls-thirdJsFiles-mapping>  
  <sectionTpls>  
    <!-- 以下为指定栏目及其需要导入的第三方JS名称-->  
      <sectionTpl>  
        <tplId><![CDATA[unWorkFlowTemplete]]></tplId>  
        <thirdJsFileNames>  
          <jsFileName><![CDATA[jquery.slide.js]]></jsFileName>  
          <jsFileName><![CDATA[unflowQueryResultSection.js]]></jsFileName>  
        </thirdJsFileNames>  
      </sectionTpl>  
    <!-- 以上为指定栏目及其需要导入的第三方JS名称-->  
  </sectionTpls>  
  <thirdJsFiles>  
    <!-- 以下为指定导入的第三方JS名称及其路径和描述-->  
    <thirdJsFile>  
      <jsFileName><![CDATA[jquery.slide.js]]></jsFileName>  
      <jsFilePath><![CDATA[/portal/sections/component/jquery.slide.js]]></jsFilePath>  
      <jsFileDescript><![CDATA[jquery幻灯片插件]]></jsFileDescript>  
    </thirdJsFile>  
    <thirdJsFile>  
      <jsFileName><![CDATA[unflowQueryResultSection.js]]></jsFileName>  
      <jsFilePath><![CDATA[/common/form/common/unflowQueryResultSection.js]]></jsFilePath>  
      <jsFileDescript><![CDATA[无流程底表栏目]]></jsFileDescript>  
    </thirdJsFile>  
  </thirdJsFiles>  
    <!-- 以上为指定导入的第三方JS名称及其路径和描述-->  
</sectionTpls-thirdJsFiles-mapping>


 * thirdJsFiles标签声明一个第三方js文件，它包含jsFileName、jsFilePath 和 jsFileDescript；

 * sectionTpl 标签声明一个栏目模板依赖哪些第三方js文件，其中tplId为栏目模板标识；

 * thirdJsFileNames 标签中为所有用到的第三方js文件名称。
   
   注意：如果为移动端栏目一栏的第三方js文件则需要在 “webapps/seeyon/portal/config/portal_section_jsfiles/mobile.xml”中进行配置注册。
   
   编撰人：chuhc
   
   


快速跳转



 * 09 开发和注册依赖的第三方JS文件



分享链接分享链接

## 65. 10 注册门户模板热点

> 原始路径：`/39/790/1165/1175.html`  
> 相对路径：`39/790/1165/1175.md`

## 10 注册门户模板热点

----------------------------------------

以安装目录文件 webapps/seeyon /portal/config/portal_hotspot/portal_hotspot_theme_pc_01.xml 该文件为例进行说明，当我们新增了一个门户模板时，需要在webapps/seeyon /portal/config/portal_hotspot/目录下新增一个门户默认热点配置xml文件，文件的内容要跟portal_hotspot_theme_pc_01.xml一样，主要是把main要配置好，其它可以不配置，如下所示：

<?xml version=“1.0” encoding=“UTF-8”?>
<PortalHotspots>
    <PortalHotspot>
        <id>4285973905855824829</id>
        <templateid>2000000001</templateid>
        <name>hotspot.name.style.main</name>
        <hotspotkey>main</hotspotkey>
        <hotspotvalue>{“tid”:”1000000001”,”msid”:”3000000001”,”ssid”:”3400000001”,”csid”:”3700000001”,”iconid”:”1”,”echartStyleId”:”1”}</hotspotvalue>
        <module>1</module>
        <tiling>0</tiling>
        <entityId>0</entityId>
        <entityLevel>Group,Account,Member</entityLevel>
        <display>1</display>
        <ext4>0</ext4>
        <ext10>4000000001</ext10>
    </PortalHotspot>
</PortalHotspots>


 * PortalHotspot 标识一个热点数据；
 * id 为热点数据的唯一标识；
 * templateid 为门户模板ID；
 * name 为热点名称，一般为国际化资源key；
 * hotspotkey 为热点key，这里为main；
 * hotspotvalue 为热点值，这里为一个json字符串，tid为门户布局ID，msid为门户主框架皮肤ID，ssid为栏目外框皮肤ID；csid为门户二级页面组件皮肤ID，iconid为门户图标样式风格，echartStyleId为门户图表风格ID
 * ext10 为整体皮肤的ID
   编撰人：chuhc


快速跳转



 * 10 注册门户模板热点



分享链接分享链接

## 66. a_门户模板定制

> 原始路径：`/39/790/1176/1177.html`  
> 相对路径：`39/790/1176/1177.md`

## a_门户模板定制

我们可以用集团管理员或单位管理员登录系统，进入V-Portal配置平台，分别对下述内容进行导入导出定制。


## 门户模板ZIP包介绍

进入【整体样式库】，选择“网站式信息门户”导出，如下图：



导出的ZIP包目录结构如下图所示：



 1. portal/images：该目录存放门户模板用到的所有图片文件；
 2. portal/pagelayout/layout/layout02：该目录存放门户布局相关文件，其中layout02为门户布局代码。这个目录下会存放3个文件：layout02_b.html、layout02_b.css和layout02_b.js。layout02_b.html文件为门户布局html文件，layout02_b.css为门户布局样式文件，layout02_b.js为该门户特有的JavaScript脚本。后面会对门户布局的概念进行专门介绍，在这里记住门户布局由1个html文件、1个css文件和1个js文件组成即可。门户布局html文件，只包含html内容，但在html的dom元素上会有致远门户自定义属性，以layout02_b.html为例，内容如下：

注意：主要是红色框中的内容, 标识门户头部区class='seeyon-portal-header'；标识门户内容区:class='seeyon-portal-body'；标识门户元素分组:class='seeyonElementGroup'，门户元素分组中可以包含多个门户元素；标识门户元素:class='seeyonElement'，门户元素中的id和data-tpl两个属性必须指定，其中id的值必须保证唯一性，data-tpl的值必须跟门户元素的文件名相同，门户元素包含哪些内容，后面马上会介绍到

 1. portal/pagelayout/element：该目录存放门户元素相关文件，每个门户元素包含3个文件：1个html文件、1个js文件、1个css文件。例如幻灯片元素tpl-slideVPortal.html、tpl-slideVPortal.js、tpl-slideVPortal.css。 门户元素的这三个文件要求必须以tpl-开头，除了后缀不通外，文件名称必须相同。 门户元素html文件需要符合laytpl前端模板引擎规范。例如tpl-slideVPortal.html内容如下：
    
    注意：上面文件内容中 <script id="tpl-slideVPortal" type="text/html"> ，id必须跟文件名称保持一致

门户元素js文件，需要按照门户规范实现，以tpl-slideVPortal.js文件为例，内容如下图所示：

vPortalMainFrameElements.slideVPortal = {
   config: true, // 标识该门户元素是否可以在门户设计器中对元素属性进行设置：true标识可以， false标识不>可以
   getData: function() {
       // 此方法需要返回一个json格式的数据， 数据格式必须与tpl-slideVPortal.html中使用的数据结构匹>配，如果元素不需要在tpl中渲染， 可以**return** false或者不写getData。
  },
   afterInit: function(_domId) {
       // _domID为门户元素在门户中惟一dom标识
  },
   getProp: function (_dataJson){
       // 在门户设计器中可配置的属性
       // 此方法需要返回一个Json格式数据， 数据格式见《附录2：门户属性配置Json数据格式》
  },
   onPropChange: function(json, id, key, value){
       // 在门户设计器使用，在门户元素属性发生变化时，会调用此方法，但注意止方法不需要对数据进行持>久化
  },
   saveProp: function(){
     // 保存门户元素属性值， 注意此方法需要对数据进行持久化,例如保存到数据库中
  }
}


门户元素css文件，主要对门户元素的外观进行配置，需要按照CSS规范实现，且这些css样式只能在tpl-slideVPortal.html文件中用到，以tpl-slideVPortal.css文件为例，内容如下图所示：



 1. portal/pagelayout/skin：该目录存放门户模板样式CSS文件，这个文件内容遵循CSS标准。
 2. portal/sections/skin：该目录存放门户栏目外框样式CSS文件，这个文件内容遵循CSS标准。
 3. skin/dist/components：该目录存放二级页面样式CSS文件，这个文件内容遵循CSS标准。
 4. upload：该目录存放导出的门户模板中包含的图片文件。
 5. import.xml：该文件为导入内容元数据描述文件，内容如下：

<?xml version="1.0" encoding="UTF-8"?>

<portal version="1.0" vendor="www.seeyon.com" type="0">
    <theme>
        <name>门户模板名称: 网站式信息门户</name>
        <icon>门户模板图标: theme_pc_06.png</icon>
        <layout>
            ... 门户模板布局 ...
        </layout>
        <skinSet>
            <name>门户模板使用的整体皮肤名称: 曙光之晨</name>
            <icon>门户模板使用的整体皮肤图标: skin_pc_06.png</icon>
            <mainSkin>
                ... 门户模板使用的主样式风格 ...
            </mainSkin>
            <sectionSkin>
                ... 门户模板使用的栏目外框样式 ... 
            </sectionSkin>
            <componentSkin>
                ... 门户模板使用的二级页面组件样式 ...
            </componentSkin>
            <iconSkin>
                ... 门户模板使用的图标风格 ...
            </iconSkin>
            <echartStyle>
                ... 门户模板使用的图表风格 ...
            </echartStyle>
        </skinSet>
        <elements>
            ... 门户模板含有的元素集合 ...
        </elements>
        <hotspots>
            ... 门户模板热点数据 ...
        </hotspots>
    </theme>
</portal>


从上面的内容可以看出：

(1) portal根标签表示一个门户模板，这个标签下的标签表示门户模板的名称，注意门户名称不能含有特殊字符，标签表示门户模板的图标，它的值是一个图片文件名称，这个图片文件必须放到前面提到的portal/images目录下；为门户模板中CSS、JS和HTML文件中直接引用的图片资源文件路径。

(2) layout这个标签中定义门户模板使用的布局文件，这个标签包含的定义内容如下：

<layout>
     <code>layout02</code>
     <styleCode>layout02_b</styleCode>
     <icon>layout02_b.jpg</icon>
     <name>layout02</name>
   </layout>


 * 标签中的内容为门户模板布局唯一标识，这个值必须与ZIP包中的路径portal/pagelayout/layout/layout02中的layout02目录名称保持一致，注意这里layout02只是一个例子，也可以是其它英文标识。
 * 标签中的内容为门户布局特定样式标识，且也必须唯一，这个值必须与ZIP包中的路径portal/pagelayout/layout/layout02目录下的文件名称相同。
 * 标签中的内容为门户模板的示意图标，这个值是一个图片文件名称，，这个图片文件必须放到前面提到的portal/images目录下。
 * 标签中的内容为门户模板的名称，不能含有特殊字符，这里建议使用与标签中相同的值。

(3)：标签表示门户模板使用的整体皮肤，这个标签下的标签表示整体皮肤的名称，注意整体皮肤名称不能含有特殊字符，标签表示整体皮肤的示意图标，它的值是一个图片文件名称，这个图片文件必须放到前面提到的portal/images目录下。它由mainSkin、sectionSkin、componentSkin、iconSkin、echartStyle五部分内容组成。

 * mainSkin标签中的内容为整体皮肤的主皮肤内容，这个标签下的name标签表示主皮肤的名称，注意主皮肤名称不能含有特殊字符。这个标签下的code标签内容标识主皮肤样式文件，必须与ZIP压缩包中portal/pagelayout/skin下的CSS文件名称保持一致。（注意：系统预制的门户模板导出的ZIP包中，这个文件名称跟code可能会不一样，但如果我们想修改这个文件内容，并将这个文件导入，则这个文件名称必须跟code保持一致）
 * sectionSkin标签中的内容为整体皮肤的栏目外框样式内容，这个标签下的name标签表示栏目外框样式的名称，注意栏目外框样式名称不能含有特殊字符。这个标签下的code标签内容标识栏目外框样式文件，必须与ZIP压缩包中portal\sections\skin下的CSS文件名称保持一致。（注意：系统预制的门户模板导出的ZIP包中，这个文件名称跟code可能会不一样，但如果我们想修改这个文件内容，并将这个文件导入，则这个文件名称必须跟code保持一致）,icon标签表示整体皮肤的示意图标，它的值是一个图片文件名称，这个图片文件必须放到前面提到的portal/images目录下。
 * componentSkin标签中的内容为整体皮肤的栏目外框样式内容，这个标签下的name标签表示栏目外框样式的名称，注意栏目外框样式名称不能含有特殊字符。这个标签下的code标签内容标识栏目外框样式文件，必须与ZIP压缩包中portal\sections\skin下的CSS文件名称保持一致。（注意：系统预制的门户模板导出的ZIP包中，这个文件名称跟code可能会不一样，但如果我们想修改这个文件内容，并将这个文件导入，则这个文件名称必须跟code保持一致）
 * iconSkin标签中的内容为整体皮肤的图标风格，这个标签下的name标签表示图标风格的名称，注意图标风格名称不能含有特殊字符。这个标签下的code标签内容标识图标风格：0标识线性；1标识面型，目前系统只支持这两种类型的图标风格。（如果输入其他内容，则系统图标风格将出现问题）
 * echartStyle标签中的内容为整体皮肤的图表风格，这个标签下的name标签表示图表风格的名称。这个标签下的code标签内容标识图表风格。code和name的值要求有对应关系，系统只支持下表中的图表风格（如果输入其他内容，则系统图标风格将出现问题）



(4)elements标签表示门户模板中的门户元素集合，这个标签下包含一个或多个标签。每个标签有code和name两个字标签。code标签的值必须与ZIP压缩包中portal/pagelayout/element下的存在对应的三个文件：tpl-xxxx.html、tpl-xxxx.js、tpl-xxxx.css。

(5)hotspots：标签表示门户模板中的热点数据集合，这个标签下包含一个或多个标签。每个标签有key和value两个字标签。key标签的值标识某个热点，value是热点数据，热点数据的格式为JSON，JSON数据中含有的数据跟具体热点有关，这里不做详细说明。

> 最后附上一个完整的import.xml文件，如下图所示：



## 可以定制化的内容

 1. 修改门户模板的布局
 2. 修改门户模板的主皮肤
 3. 修改门户模板的栏目外框样式
 4. 修改门户模板的二级页面组件样式
 5. 修改门户模板的图标风格
 6. 修改门户模板的图表风格
 7. 新增门户元素
 8. 去掉门户元素，例如去掉幻灯片元素。

上面列出的可定制化内容，1、2、3、4主要是修改css文件内容或者是热点数据中的某个热点值来实现，这个比较简单，不做详细说明；5和6是指定一个风格即可，也比较简单。对于7这种情况来说稍微复杂点，但代码开发工作也并不大，关键是遵循我们前面介绍的内容进行扩展。

## 举个例子

下面以一个具体例子来说明：比如我们要把现有【网站式信息门户】门户模板的幻灯片元素替换为一个新元素，为了降低学习门槛，我们还是以helloworld作为入门例子，假设这个元素我们叫做helloworld，元素代码为tpl-helloworld，这个门户元素的展现效果为只输出一个文本hello world！

开发步骤：

第一步：解压导出的门户ZIP包； 第二步：在目录portal/pagelayout/element中新建门户元素的三个文件：tpl-helloworld.html、tpl-helloworld.js、tpl-helloworld.css。内容分别如下所示： tpl-helloworld.html文件的内容如下：

<script id="tpl-helloworld" type="text/html">    <div class="helloworld" onclick="vPortalMainFrameElements.helloworld.showMessage();" title="{{ d.name }}" >{{ d.name }} {{ d.age }}</div></script>


tpl-helloworld.js文件的内容如下：

vPortalMainFrameElements.helloworld = {
  config: true,

   //获取数据
   getData: function() {
     return  {
      name: 'Jully',
      age: '20'
    }
  },

   //初始化，元素如果有初始化的事件请写在这里面
   init: function(_elementId) {
     return;
  },

   //设计器中获取可设置属性
   getProp : function(_dataJson){
     window.parent.changeRightTitle("hello world 设置");
     return {};
  },

  showMessage: function () {
    alert("hello!")
  }
}


tpl-helloworld.css文件的内容如下：

.helloworld {
   color:red;
   text-align:center;
}


第三步：修改门户布局html文件layout02_b.html，将helloworld元素绑定到门户模板布局上，内容如下图红框中的内容：



第四步：修改门户布局文件名称，将layout02_b.html修改为layout02_001.html，将layout02_b.js修改为layout02_001.js，将layout02_b.css修改为layout02_001.css，修改后的文件如下图所示：



第五步：修改import.xml文件中的下述helloworld相关部分的内容：

<?xml version="1.0" encoding="UTF-8"?>
<portal version="1.0" vendor="www.seeyon.com" type="0">
  <theme>
    <name>helloworld门户</name>
    <icon>helloworld.jpg</icon>
    <layout>
      <code>layout02</code>
      <styleCode>layout02_001</styleCode>
      <icon>layout02_b.jpg</icon>
      <name>layout02</name>
    </layout>
<elements>
      <element>
        <code>tpl-wideLogo</code>
        <name>宽尺寸的单位logo元素</name>
      </element>
      <element>
        <code>tpl-concurrentAccount</code>
        <name>兼职单位元素</name>
      </element>
      <element>
        <code>tpl-topRightsystemOperation</code>
        <name>顶部系统操作按钮元素</name>
      </element>
      <element>
        <code>tpl-miniNav</code>
        <name>顶部极简版导航-包含门户、空间、菜单、第三方系统、项目空间等</name>
      </element>
      <element>
        <code>tpl-helloworld</code>
        <name>helloworld</name>
      </element>
      <element>
        <code>tpl-showNavSpaceMenu</code>
        <name>导航-空间下的菜单,当鼠标hover至空间时展现</name>
      </element>
      <element>
        <code>tpl-messageBottom</code>
        <name>底部弹出的消息盒子</name>
      </element>
......


注意：helloworld.jpg为我们自己找的一张图片，作为我们这个新的门户模板的示例图标，需要放到目录portal/images下。

第六步：重新打包成ZIP包，文件名称无特殊要求。假设我们的压缩包名称为“portal_template.zip”，双击打开后，显示应该如下图所示， 所有文件都是压缩包根目录下，否则会导入时会报错：



第七步：以集团管理员或单位管理员登录系统，将ZIP导入门户模板。

至此，门户模板定制完毕，效果如下





编撰人：chuhc、admin、het


快速跳转



 * a_门户模板定制
   * 门户模板ZIP包介绍
     * 可以定制化的内容
     * 举个例子



分享链接分享链接

## 67. b_栏目布局定制

> 原始路径：`/39/790/1176/1178.html`  
> 相对路径：`39/790/1176/1178.md`

## b_栏目布局定制


## 栏目布局ZIP包介绍

进入【栏目布局库】，选择“网站式信息门户”导出，如下图： 导出的ZIP包目录结构如下图所示：



 1. portal/decoration/layout/D1-M_T: 为栏目布局文件layout.html所在目录，其中D1-M_T为栏目布局唯一标识。栏目布局文件layout.html内容如下：

<div class="container">
    <div class="row">
            <div class="col-12 col">
                <div class=“fragment” id=“fragment_0_0” x=“0” y=“0” swidth=“12” celladd=“true” maxsection=“-1”>
                </div>
            </div>
        </div>
</div>


其中， class="row" 表示一行，class="col-12 col" 标识一列，col-12 标识这一列宽度比例（注意：一行的宽度分成12等份），如果用 col-12 则标识这一列占满了整行。class="fragment" 标识栏目片段集合，可以配置下表中的属性：

 1. portal/images：为栏目布局预览图标文件所在目录。
 2. import.xml：为栏目布局元数据描述文件，内容如下所示：

<portal version="1.0" vendor="www.seeyon.com" type="decoration">
            <decoration>
                <code>D1-M_T</code>
                <name>模板1</name>
                <icon>space_edit_layout_1.png</icon>
            </decoration>
        </portal>



## 可以定制化的内容

1.修改栏目布局示例图标； 2.修改栏目布局名称； 3.修改栏目布局标识； 4.修改栏目布局，比如调整栏目宽度比例，增加一行栏目等。


## 举个例子：

下面以一个具体的例子来说明如何对栏目布局进行修改。比如我们要做一个下图所示的布局：




## 开发步骤如下

开发步骤如下： 第一步：根据前面“栏目布局ZIP包介绍”，我们可以写出这个栏目布局的layout.html文件，如下所示：

<div class="container">  
    <div class="row">  
        <div class="col-12 col">  
            <div class="fragment" id="fragment_0_0" x="0" y="0" swidth="12" celladd="true" maxsection="-1"></div>  
        </div>  
    </div>  
    <div class="row">  
        <div class="col-3 col">  
            <div class="fragment" id="fragment_1_0" x="0" y="1" swidth="3" celladd="true" maxsection="-1"></div>  
        </div>  
        <div class="col-3 col">  
            <div class="fragment" id="fragment_1_1" x="1" y="1" swidth="3" celladd="true" maxsection="-1"></div>  
        </div>  
        <div class="col-3 col">  
            <div class="fragment" id="fragment_1_2" x="2" y="1" swidth="3" celladd="true" maxsection="-1"></div>  
        </div>  
        <div class="col-3 col">  
            <div class="fragment" id="fragment_1_3" x="3" y="1" swidth="3" celladd="true" maxsection="-1"></div>  
        </div>  
    </div>  
    <div class="row">  
        <div class="col-2 col">  
            <div class="fragment" id="fragment_2_0" x="0" y="2" swidth="2" celladd="true" maxsection="-1"></div>  
        </div>  
        <div class="col-4 col">  
            <div class="fragment" id="fragment_2_1" x="1" y="2" swidth="4" celladd="true" maxsection="-1"></div>  
        </div>  
        <div class="col-6 col">  
            <div class="fragment" id="fragment_2_2" x="2" y="2" swidth="6" celladd="true" maxsection="-1"></div>  
        </div>  
    </div>  
</div>


第二步：修改import.xml文件中的code和name，假设code我们命名为custom_001，name我们命名为自定义栏目布局01，icon修改为custom_001.png。修改后的内容如下所示：

<portal version="1.0" vendor="www.seeyon.com" type="decoration">  
  <decoration>  
    <code>custom_001</code>  
    <name>自定义栏目布局01</name>  
    <icon>custom_001.png</icon>  
  </decoration>  
</portal>


第三步：将ZIP包中路径portal/decoration/layout/D1-M_T修改为portal/decoration/layout/custom_001。 第四步：将custom_001.png图片放到ZIP包路径portal/images下。 第五步：将修改后的内容重新打一个ZIP包，然后重新导入系统即可。 导入系统后，可以对该布局进行编辑，可以查看定制的布局是否显示正确。

编撰人：chuhc、het




快速跳转



 * b_栏目布局定制
 * 栏目布局ZIP包介绍
   * 可以定制化的内容
   * 举个例子：
     * 开发步骤如下



分享链接分享链接

## 68. c_栏目外框定制

> 原始路径：`/39/790/1176/1179.html`  
> 相对路径：`39/790/1176/1179.md`

## c_栏目外框定制


## 栏目外框ZIP包介绍

进入【栏目外框库】，选择“栏目外框01”导出，获得门户模板ZIP包。然后解压如下图：



导出的ZIP包的目录结构如下图所示：



 1. portal/images/section_01.png：该图片为栏目外框的预览图片。
 2. portal/sections/skin/01.css：该文件为栏目外框的样式文件。
 3. portal/import.xml：该文件为栏目外框的元数据描述文件，内容如下图所示：



sectionSkin标签中的内容为栏目外框样式内容，这个标签下的name标签表示栏目外框样式的名称，注意栏目外框样式名称不能含有特殊字符。这个标签下的code标签内容标识栏目外框样式文件，

必须与ZIP压缩包中 portal/sections/skin下的CSS文件名称保持一致。（注意：系统预制的栏目外框模板导出的ZIP包中，这个文件名称跟code可能会不一样，但如果我们想修改这个文件内容，

并将这个文件导入，则这个文件名称必须跟code保持一致），icon标签表示栏目外框的示意图标，它的值是一个图片文件名称，这个图片文件必须放到前面提到的portal/images目录下。

栏目外框的热点数据如下表所示：




## 可以定制化的内容

 1. 修改栏目外框的code、name和icon
 2. 修改栏目外框的样式文件内容
 3. 修改栏目外框的热点数据


## 例子

例如我们要导入一个栏目外框模板，栏目外框带边框，边框颜色为蓝色，边框圆角为10，栏目内容背景色为黄色，栏目外框标识为custom_001，栏目外框名称为自定栏目外框001，

栏目外框示意图修改为custom_001.png，则需要做如下修改： 主要修改下图中import.xml文件中标黄部分的内容：

然后将上述内容达成压缩包，重新导入系统即可。

编撰人：chuhc、het




快速跳转



 * c_栏目外框定制
 * 栏目外框ZIP包介绍
   * 可以定制化的内容
   * 例子



分享链接分享链接

## 69. Groovy语法

> 原始路径：`/39/797.html`  
> 相对路径：`39/797.md`

## Groovy语法

对于Java开发人员来说，Groovy是很简单的。

因为如果你不懂Groovy，完全可以直接书写Java语句，它会被兼容。

对于非Java开发人员而言，Groovy比Java更简单。

让我们一步一步的来转化吧

你可以这样输出

// Java
System.out.println("Hello");

// Groovy
println "hello"


你可以这样定义Map和List

// Java
Map map = new HashMap();
// ... put
List list = new ArrayList();
// ... add

// Groovy
def map = ["1":"one","2":"two"]
def list = [1,2,3,4,5,6]


还有GString

def name = "user"
def age = 21
// Java
"姓名：" + name + ",年龄："+ age

// Groovy
"姓名:$name,年龄：$age"


for循环

// Java
for (int i = 0; i < 100; i++) {

}
// Groovy
for (i in 1..100){

}


参考链接：

语法风格指南(极客学院)

groovy语法(简书)

字符串操作

def s = '20170001'
println s[2..7] // 或者 s[2..-1]


将输出

170001


编撰人：lichaoj、het


快速跳转



 * Groovy语法



分享链接分享链接

## 70. 系统登录组件

> 原始路径：`/39/925.html`  
> 相对路径：`39/925.md`

## 系统登录组件


## 登录认证器

登录认证器是一种认证单元，一个认证策略就需要实现一套认证器。典型应用场景如下：AD/LDAP统一认证、双因素认证、CA认证实现、帐号密码认证。


## 默认认证器

平台提供了多元化的认证器，只要任意一个认证器认证通过，即可当作登录成功。系统缺省提供几个验证器：

验证器                                                            说明
com.seeyon.ctp.portal.sso.login.SSOTicketLoginAuthentication   单点登录认证
com.seeyon.ctp.login.auth.QrCodeLoginAuthentication            二维码登录
com.seeyon.v3x.plugin.ca.CALoginAuthentication                 使用CA认证
com.seeyon.ctp.login.IdentificationDogLoginAuthentication      使用身份验证狗认证
com.seeyon.apps.ldap.login.LDAPLoginAuthentication             使用LDAP认证
com.seeyon.ctp.login.auth.CASLoginAuthentication               CIP集成平台CAS认证
com.seeyon.ctp.login.auth.SMSLoginAuthentication               短信验证码认证
com.seeyon.ctp.login.auth.DefaultLoginAuthentication           使用协同用户系统认证


## 实现原理

每一套认证器均是集成AbstractLoginAuthentication，重写authenticate方法，并按如下注释说明来控制成功还是失败：

/**
     * 认证，策略是：
     *
     * <ol>
     *   <li>系统框架把登录界面发过来的<code>HttpServletRequest</code>完整的传递给认证实现类</li>
     *   <li>认证实现类完成自己的逻辑</li>
     *   <li>返回值约定
     *      <ol type="i">
     *        <li>当验证通过，需要给框架返回[用户名, 密码]，框架将直接跳转到首页</li>
     *        <li>当不验证通过，但要终止本次登录请求，直接throw new LoginAuthenticationException(),用户将跳转到登录页</li>
     *        <li>当不验证通过，返回null，框架将调用下一个认证类认证</li>
     *      </ol>
     *   </li>
     * </ol>
     * 
     * @return 认证通过: 返回[用户名, 密码]； 验证不通过返回null，框架将调用下一个认证类认证
     * @throws LoginAuthenticationException 用户将跳转到登录页
     */
    String[] authenticate(HttpServletRequest request, HttpServletResponse response)
            throws LoginAuthenticationException;



## 实现示例

要实现自己的登录认证，必须：

1、继承com.seeyon.ctp.login.AbstractLoginAuthentication，实现自己的登录验证类

package com.seeyon.apps.login;

import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

import com.seeyon.ctp.common.constants.Constants;
import com.seeyon.ctp.common.constants.LoginConstants;
import com.seeyon.ctp.login.AbstractLoginAuthentication;
import com.seeyon.ctp.login.LoginAuthenticationException;

public class CustomLoginAuthentication extends AbstractLoginAuthentication {
    @Override
    public String[] authenticate(HttpServletRequest request,
            HttpServletResponse response) throws LoginAuthenticationException {
        String username = request.getParameter(LoginConstants.USERNAME);// 用户名
        String password = request.getParameter(LoginConstants.PASSWORD);// 密码
        if (username == null || password == null) {
            return null;
        }
        //登录方式，判断是否移动应用登陆
        String userAgentFrom = request.getParameter(Constants.LOGIN_USERAGENT_FROM);
        boolean fromMobile = Constants.login_useragent_from.mobile.name().equals(userAgentFrom) || LoginUtil.isFromM1(userAgentFrom);

        if (check(username, password)) {
            return new String[] { username, password };
        }

        return null;
    }

    private boolean check(String username, String password) {
        // 登录认证逻辑，用户名和密码正确时返回true即可
        return false;
    }
}


2、将自定义认证器注册到Spring bean中：

<bean class="com.seeyon.apps.login.CustomLoginAuthentication"/>



## 登录认证拦截器

登录认证拦截器用于在认证前、认证后进行拦截、记录登录行为以及做前置、后置动作。

典型应用场景如下：登录认证前做IP访问控制、登录成功后记录到审计日志、计算登录前、后执行耗时。

登录认证拦截器使用Spring的Interceptor拦截器实现。


## 默认登录拦截器

系统缺省通过几个拦截器实现一些功能控制：

验证器                                                             说明
com.seeyon.ctp.login.interceptor.VerifyCodeLoginInterceptor     验证码拦截器，在preHandle对用户输入的验证码进行校验
com.seeyon.ctp.login.interceptor.LockLoginInterceptor           锁定用户拦截器
com.seeyon.ctp.login.interceptor.IpcontrolLoginInterceptor      IP控制拦截器
com.seeyon.ctp.login.interceptor.MutilBrowserLoginInterceptor   限制管理员只能使用PC，通过IE登录


## 实现原理

每一个拦截器均继承自AbstractLoginInterceptor，并根据使用场景重写“登录前preHandle”、“登录后afterComplete”、“登录失败afterFailure”的方法：

/**
     * 登录之前的操作

     * 
     * 此时AppContext.getCurrentUser()是null的
     * 
     * @param request
     * @param response
     * @return Error标示本次登录终止,返回到登录页；OK正常往下进行
     */
    public LoginResult preHandle(HttpServletRequest request, HttpServletResponse response);

    /**
     * 在登录验证成功后的操作

     * 此时AppContext.getCurrentUser()有值
     * @param request
     * @param response
     * @return Error标示本次登录终止,返回到登录页；OK正常往下进行
     */
    public LoginResult afterComplete(HttpServletRequest request, HttpServletResponse response);

    /**
     * 在登录验证失败后的操作
     * 
     * @param request
     * @param response
     * @return Error不管怎么样都会跳转到登录页面，最好别返回LoginResult.OK他也没有用
     */
    public LoginResult afterFailure(HttpServletRequest request, HttpServletResponse response);



## 实现示例

可以通过以下步骤实现登录拦截：

1、继承com.seeyon.ctp.login.AbstractLoginInterceptor，实现自己的登录拦截器类

package com.seeyon.apps.login;

import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

import com.seeyon.ctp.common.constants.LoginConstants;
import com.seeyon.ctp.login.AbstractLoginInterceptor;
import com.seeyon.ctp.login.LoginAuthenticationException;

public class CustomMutilBrowserLoginInterceptor extends com.seeyon.ctp.login.AbstractLoginInterceptor {
    public CustomMutilBrowserLoginInterceptor() {
    }
    //管理员只能通过IE、PC访问
    public LoginResult afterComplete(HttpServletRequest request,HttpServletResponse response) {
        User currentUser = CurrentUser.get();
        if(currentUser.isAdmin()) {
            Boolean A8Allow4Admin = (Boolean)(BrowserFlag.A8Allow4Admin.getFlag(request));

            //管理员只能从IE上登录
            if (Boolean.FALSE.equals(A8Allow4Admin)) {
                return LoginResult.ERROR_IPCONTROLIPAD;
            }

            //管理员不能从M1上登录
            if(currentUser.isFromM1() || Constants.login_useragent_from.mobile.name().equals(currentUser.getUserAgentFrom())){
                return LoginResult.ERROR_ForbiddenAdminLogin;
            }
        }

        return LoginResult.OK;
    }
}


2、注册Spring bean，将实现类在自己的Spring插件配置下注册：

<bean class="com.seeyon.apps.login.CustomMutilBrowserLoginInterceptor"/>



## 执行顺序调整

在大多数场景下，同一套产品只会有一个主要的LoginAuthentication生效，而LoginInterceptor对顺序不敏感，原则上不需要排序。

但如果要对LoginAuthentication和LoginInterceptor进行排序，可以在插件目录定义一个login.xml，如(WEB-INF\cfgHome\plugin\myplugin\login.xml)，并按如下配置示例进行属性配置：

<?xml version="1.0" encoding="UTF-8"?>
<login>
	<!-- 将CustomLoginInterceptor放到com.seeyon.ctp.login.interceptor.LockLoginInterceptor之前执行。 -->
    <bean class="com.seeyon.apps.login.CustomLoginInterceptor" before1="com.seeyon.ctp.login.interceptor.LockLoginInterceptor"/>
	<!-- 将CustomLoginAuthentication放到com.seeyon.v3x.plugin.ca.CALoginAuthentication之后执行。 -->
    <bean class="com.seeyon.apps.login.CustomLoginAuthentication" after2="com.seeyon.v3x.plugin.ca.CALoginAuthentication"/>
</login>


一旦定义了login.xml，对应的bean就无需在spring xml中注册。

编撰人：lichaoj、het




快速跳转



 * 系统登录组件
   * 登录认证器
     * 默认认证器
     * 实现原理
     * 实现示例
   * 登录认证拦截器
   * 默认登录拦截器
     * 实现原理
     * 实现示例
   * 执行顺序调整



分享链接分享链接

## 71. 概述

> 原始路径：`/39/1119.html`  
> 相对路径：`39/1119.md`

## 概述

CTP平台在语言方面基于Spring开发框架，遵循JavaEE的标准规范，主要采用JAVA语言设计开发，同时引入Groovy、Rest、Erlang、Html5、CSS3等多种技术；在架构方面采用MVC编程模式进行分层设计，满足标准定义、分散关注、松散耦合、逻辑复用的设计要求；在数据持久方面采用基于JDBC轻量级的对象封装的Hibernate框架实现数据对象关系映射，可应用于任何符合JDBC标准的数据访问场景，支持主流关系型数据库。

平台基于分层、组件化设计思路，同时采用分布式体系架构，具有高度的灵活性和扩展性，各业务模块支持插拔，可根据客户需求进行快速配置、灵活组合。

平台提供完备的开放接口和规范，基于数据交换引擎DEE和单点登录SSO，可与ERP、SCM和邮件系统等组织内部系统进行人员、页面、数据、流程和消息的多层次集成整合。

平台具备良好的兼容性，支持多种操作系统，支持多种关系型数据库，支持主流应用服务器，提供多语言和多时区支持，客户端支持多种浏览器，支持多种移动终端。并为各产品线提供规范化的全生命周期开发流程管理。

CTP平台采用分层、组件化设计，模块低耦合、高内聚，有效满足协同应用的快速开发及平台的高并发、高稳定要求。



平台提供了丰富的技术组件、应用组件和界面组件，为系统应用开发提供灵活、高效的基础支撑。平台具有完整的前后端组件支撑体系，为平台提供了统一的标准和便捷的调用模式，在提高扩展性的同时保障了系统的稳定性、一致性。



平台主要由组织权限引擎、工作流引擎、表单引擎、门户引擎、报表引擎五大核心引擎组成，涉及组织机构、访问权限、流程控制、业务定制、数据集成、数据展现六大方面，是致远协同系统的主体运行框架，在协同平台服务构建和运行中起到了坚实的基础支撑作用。


## 平台特性


## 一站式解决方案

致远协同产品系列是一套完整的组织协同管理解决方案，可面向政府/事业单位、企业和社区等不同类型的组织，提供企业A系列、政府G系列、移动M系列等多产品线，覆盖了各类企业、组织从超低端、低端、中端、高端，直到超高端等不同层。V5平台支撑着V5大家族产品的快速发展，让用户可以随着致远基于统一平台的产品发展而共同进步。同时，V5平台提供平滑的升级机制，让跨产品线的升级简单、顺畅，解决组织在不同发展时期对协同软件有不同要求的问题，大大降低组织的总拥有成本（TCO）。


## 业界技术先进性

V5平台是基于JavaEE标准开发的企业级协同管理应用。平台采用标准的Java EE开发体系，在事务管理、远程调用、安全防护等方面达到业界领先水平。

V5平台引入HTML5技术语言，其最大的优点在于它是一个公开的技术，意味着每一个浏览器或每一个平台都可以实现，使得V5平台具有良好设备、平台兼容性。

平台提供本地API、RESTWebService和JSSDK等多种类型接口满足不同场景的调用，引入REST技术。基于HTTP协议，具备轻量级、服务自解释、数据描述简单等优点，学习门槛低，有效降低了集成成本。

同时，V5平台在多项技术处于业界领先水平。独立的工作流引擎保证了系统流程的稳定、高效；企业搜索技术使信息的搜索覆盖到整个系统的结构化和非结构化信息，并且保证搜索的高效精准；外部数据交换使用XML技术保证了数据的完整描述和模块间数据交换的松耦合；移动技术使应用延展到移动设备并且与PC端拥有一致的用户体验；门户技术既有效地整合了内部的业务模块，又能够轻松集成异构系统的应用；Ajax技术提高了界面响应速度和用户体验等等，这些技术的自研、引入、优化均以“高内聚、松耦合”为架构的核心思想，经过十余年不断的努力付出和充分的调研、优化，完美和谐的集成在一起。


## 完善的安全体系

基于Internet和移动互联网技术，V5平台充分考虑了系统安全、信息安全、数据安全等方面的要求，支持多级多种安全管理，对PC和移动应用进行全方位的安全管控。参照国家信息系统安全等级保护的相关标准，通过数据库安全性、系统数据安全性、应用服务器安全性、传输安全性、统一身份认证、安全审计和客户端安全等措施保证系统安全，增强了系统的高安全性，为用户提供安全可靠的协同服务，主要体现下以下五个方面：

 * 统一身份认证：提供身份认证狗和短信验证码登录方式，支持密码的加密传输，提供CA认证接口等方案，验证用户身份。

 * 完善的鉴权体系：建立基于角色访问控制（RBAC）的鉴权体系，提供基于人员、单位、部门、组、角色、岗位、职务级别等多种角色的权限控制，系统可以针对以上属性进行灵活的权限设定，确保信息安全的可定义和可执行。

 * 数据存储安全：敏感数据加密存储（如密码、手机号、工资数据等），包括系统管理员、数据库管理员也无法获取；提供多种文件加密策略，采用密码加密传输等安全措施。

 * 数据传输安全：支持HTTPS安全传输，对用户输入数据进行转义等措施。

 * 行为审计安全：采用数字签名技术，记录审计日志等安全措施。

以上五种服务相辅相成，统一形成V5平台强大的安全体系，可有效地防止黑客攻击及数据泄露，保障系统数据的安全可靠。


## 高度的开放集成

数据孤岛、信息孤岛、应用孤岛等问题是企事业单位多年信息化建设后的后遗症，解决这些孤岛的关键就在于系统开放、数据共享。V5平台采用业内顶尖的开发技术，如：SSH框架、Groovy脚本引擎技术、REST技术等，遵从WFMC、JAX-WS、JAX-RS、JSR223等标准，可实现零代码搭建模块，易于平台业务功能的个性化建设与扩展。同时，平台开放了丰富的二次开发规范和接口，并提供开发工具，支持与异构系统等进行人员、页面、数据和流程等信息的全面集成，且提供高效的安全保障机制。致远开放平台网站open.seeyon.com提供一站式的开发者支持服务。


## 高性能和高稳定

V5平台采用一系列的基础组件和技术，有效保证了系统运行的稳定可靠。平台基于轻量级的Spring框架，采用标准的接口规范及SQL编制规范，利用索引、缓存、异步等技术保证了平台在海量数据、高并发环境下的运行性能。

 * 异步Ajax技术 通过异步JavaScript技术与栏目的有效结合，平台实现了客户端页面的局部刷新，减少了客户端与服务器交互的数据量，提高了系统的性能和稳定性，极大地改善了用户体验。

 * 高效数据缓存 数据库缓存：使用数据层的二级缓存，合理配置系统参数，有效地解决系统的性能问题。 页面缓存：在Portal中对访问过的页面进行缓存，缩短了二次请求的响应时间。 缓存组件：通用分布式缓存组件为应用提供统一的缓存管理机制。

 * 异步消息队列 通过异步消息技术，解决大并发问题，避免同时给全系统人员发消息时的信息堵塞和对服务器资源的高频占用，提高了系统的稳定性。


## 集群与微服务

系统支持集群和双机热备，支持平滑扩容，避免服务中断，通过负载均衡、会话复制、缓存同步等机制保证系统提供长期、可靠的服务，提高系统的可用性和可伸缩性。平台支持Apache（mod_jk）、nginx以及F5等各类软硬负载均衡，并提供了基于jgroups实现的分布式缓存。

平台广泛应用基于Spring boot实现的微服务架构，通过微服务剥离全文检索、文件下载和后台业务逻辑，避免单点故障引起整体宕机。平台还提供分库服务避免长期积累的海量数据影响系统性能，附件按日期分区存储便于增量备份和扩容。

编撰人：lichaoj




快速跳转



 * 概述
   * 平台特性
     * 一站式解决方案
     * 业界技术先进性
     * 完善的安全体系
     * 高度的开放集成
     * 高性能和高稳定
     * 集群与微服务



分享链接分享链接

## 72. 单点登录(SSO)

> 原始路径：`/39/1858.html`  
> 相对路径：`39/1858.md`

## 单点登录(SSO)


## 协同平台单点登录第三方系统


## 实现方式一：关联系统+扩展栏目

无需开发，使用关联系统管理登录信息，集成第三方系统页面。

适用于不需要验证码的Web应用，使用目标系统的用户名和密码模拟登录过程。

 * 配置关联系统
   
   * 以系统管理员system登录协同，使用“关联系统管理”建立一个新的关联系统。关联系统的url为被集成系统的登录链接，将登录需要的信息如用户名和密码定义为关联系统参数
     
     
   
   * 建立扩展栏目
     
     由第三方系统管理验证信息的栏目有两种：数据集成型栏目(SSOWebContentSection)和功能操作型栏目（SSOIframeSection）



 * 用户登录后，在个人空间中配置关联系统参数，填写集成系统的登录信息（用户名和密码）。 由关联系统维护被集成系统的用户名、密码以及Session
 * 说明：被集成系统的修改：登录不成功，需要在登录请求的response中增加header项：LoginError=***，否则平台无法判断是否成功登录
 * 从V7.0开始，关联系统的URL中可以调用公式，实现一些更复杂的单点登录，请参见公式组件。


## 实现方式二：Ticket

实现步骤：

 * 添加页签
   
   新建插件sso:按下面的定义，在协同的webapps\seeyon\WEB-INF\cfgHome\plugin\sso目录下新建一个XML文件pluginCfg.xml，例如：
   
   <?xml version="1.0" encoding="UTF-8"?>
   <plugin>
       <id>sso</id>
       <name>单点登录模块</name>
       <category>11001</category>
   </plugin>
   
   
   然后在协同的webapps\seeyon\WEB-INF\cfgHome\plugin\sso\spring目录下新建一个XML文件，如myspace.xml
   
   <?xml version="1.0" encoding="UTF-8"?>
   <!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
   <beans default-autowire="byName">
       <!-- id必须唯一 -->
       <bean id="sinaNewsSpace" class="com.seeyon.v3x.common.thirdparty.ThirdpartySpace" init-method="init">
           <!--注意如果OA的版本是V6.0及其以上，上面class修正为：com.seeyon.ctp.portal.sso.thirdpartyintegration.ThirdpartySpace -->
           <!-- id必须唯一或者不写后台自动生成，必须为数字 -->
           <property name="id" value="-2327812443752403806"/>
           <!-- 页签上显示的名称 -->
           <property name="name" value="Sina News"/>
           <!-- 插件id，必须存在，如果不存在，请按下面的步骤定义一个新的插件 -->
           <property name="pluginId" value="sso"/>
           <!-- 第三方系统登录地址，如果合并3、4步，可以省略 -->
           <property name="loginURL" value="http://xxx.xxx.xxx.xxx/ssologin.jsp"/>
           <!-- 点击页签要打开的第三方系统页面地址 -->
           <property name="pageURL" value="http://xxx.xxx.xxx.xxx/main.jsp"/>
           <!-- 打开方式，值为open时在新窗口打开，为workspace时在协同页面能打开 -->
           <property name="openType" value="open"/>
           <!-- 排序号 -->
           <property name="index" value="4"/>
       <!-- 授权 accessRoles与accessCheck选择其中一个即可-->  
       <property name="accessRoles"> 
         <list> 
           <value>GeneralStaff</value> 
         </list> 
       </property>  
      <!-- <property name="accessCheck" ref="accessCheck"/> -->  
     </bean>  
    <!-- <bean id="accessCheck" class="com.seeyon.ctp.ext.Tab.TestThirdpartyAccessCheck"></bean> -->  
   </beans>
   
   
   注意事项：集成的第三方系统，必须先在协同平台中定义插件

 * myspace.xml参数说明

名称                        备注
id                        唯一标示，这了在XML里必须设置为数字型
name                      名称
pluginId                  插件ID
loginURL                  在进入第三方指定页面前，先跳转到loginURL进行握手
                          第三方系统根据Ticket回调获取协同身份信息，进行单点登录，并注册Ticket和登录用户的映射，
                          平台带着Ticket跳转到第三方系统的"页面地址" （pageURL）
pageURL                   第三方指定到达的目的页面。
openType                  打开方式
accessRoles与accessCheck   OA用户对于第三方页签显示权限，详情请见页签集成。

 * 配置第三方系统，ThirdpartySpace：名称、登录地址、页面地址、打开方式【详情请见1.5.1. 页签集成】

 * 登录过程
   
   在协同中点击"空间页签"
   
   平台产生Ticket，并维护在内存中
   
   平台带着Ticket访问第三方系统的"登录地址"（loginURL）进行握手 第三方系统根据Ticket回调获取协同身份信息，进行单点登录，并注册Ticket和登录用户的映射， 平台带着Ticket跳转到第三方系统的"页面地址" （pageURL）

说明

第三方系统完全依赖和信任协同的身份验证，Ticket由协同平台发放

第三方系统使用与协同完全相同的登录名或者进行二次开发，自己维护协同登录名与第三方系统用户的映射表

如果当前用户已经登录第三方系统，将跳过② ③，直接到第4步，使用相同的Ticket

 * 认证ticket/获取身份信息的接口系统提供Servlet：http://a8:80/seeyon/thirdpartyController.do?ticket=**；平台将通过response header的LoginName返回登录名

 * 如果第三方回调后认为有异常，请在response header增加名称为SSOLogoutError的信息

 * 在上面myspace.xml中（loginURL）获取当前人员登录名例程如下：
   
   //获取ticket
   String ticketinfo=request.getParameter("ticket");
   //通过ticket/获取身份信息的接口获取登录信息
   String LoginNameUrl="http://127.0.0.1/seeyon/thirdpartyController.do?ticket="+ticketinfo;
   //通过HttpClientUtil发送请求
   HttpClientUtil u = new HttpClientUtil();
   //获取登录名
   String LoginName=u.getContent(LoginNameUrl).toString();
   

第三方系统退出时，要通知协同，地址是http://a8:80/seeyon/thirdparty.do?method=logoutNotify&ticket=**

根据情况可将 ③ ④步合并 （省略loginURL）


## 第三方系统单点登录协同平台

Ticket中请不要使用特殊字符和中文，平台不支持使用中文作为Ticket！

必须在配置工具的系统参数设置中配置协同平台的外网访问地址internet.site.url，否则，生成的url为空。

注意：【V6.1 ticket必须加密，不加密则无法正常登录】


## 应用场景

 1. 从第三方Portal打开协同
 2. 从第三方集成的协同栏目打开链接


## 关键步骤

下面描述了单点登录的典型开发关键步骤，细节可参阅后续章节

 1. 配置外网访问地址internet.site.url,如不配置，webService导出的数据的url为空



 1. 建立一个插件,作为单点登录配置和Class的容器。参见本地开发接口的插件化章节。

建立握手类，例如

public class MySSOLoginHandshake  extends SSOLoginHandshakeAbstract {
    // “ticket” 就是ticket取得的参数值
    public String handshake(String ticket) {
        if(ticket==null||ticket.equals("")) {
            return null;
        }
        HttpClient hc = new HttpClient();
        //对应下图（实现原理）中 步骤4：协同平台与第三方系统握手，根据ticket获取loginName
        loginName = hc.get("http://第三方系统/getLoginIdByTicket?ticket="+ticket);

        // 返回ticket对应的协同登录名
        return loginName;
    }
    public void logoutNotify(String ticket) {
        HttpClient hc = new HttpClient();
        //用户退出协同时，通知第三方系统。
        loginName = hc.get("http://第三方系统/logout?ticket="+ticket);
    }
}


 1. 建立握手类Spring配置文件

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
<bean id="samplesso" class="com.seeyon.ctp.portal.sso.SSOLoginContext">
    <property name="name" value="sample"/>
    <property name="forward" value="true"/>
    <property name="handshake">
        <!-- 使用自己的握手实现 -->
        <bean class="com.seeyon.apps.plugin.MySSOLoginHandshake" />
    </property>
</bean>
</beans>



## 实现原理

从第三方系统登录到协同，这种认证是完全信任第三方系统的，单点登录有两种效果：

 * 单点登录成功后直接打开协同主页面（缺省模式）。
 * 单点登录成功后并不打开协同主页面，平台维护ticket信息和登录用户信息，为以后请求服务作认证使用。

比如：请求获得协同待办事项列表服务。需要配置SSOLoginContext.xml中一个属性如下： 单点登录的前提是外部系统使用和协同一致的登录名或维护了两个系统的登录名映射，也就是说，外部系统必须知道它的当前用户在协同中的登录名。 请注意，为了安全，登录过程必须由第三方系统的服务器发出，不允许第三方系统客户端直接单点登录。 登录过程：



 1. 获取当前用户的ticket:
    
    用户登录外部平台，发出要访问协同平台的请求。

 2. 生成ticket:
    
    外部平台生成ticket，ticket不能为中文，也不能使用协同平台的登录名，最理想的ticket是类似sessionId的随机字符串。并在第三方系统服务器中，记录 ticket 和 ctp平台中的loginName的关联关系。

 3. 登录:外部平台带着ticket、from（握手bean的name，如下文中的gke）和UserAgentFrom跳转到协同平台
    
    UserAgentFrom是一个枚举代表着不同端的登录(默认值：pc)。
    
     UserAgentFrom枚举值如下：
    
         pc     //pc端
         phone    //移动端
         ucpc    //ucpc
         wechat    //微信端
    
     登录URL如下所示：
    
     /seeyon/login/sso?from=gke&ticket=ticket***&UserAgentFrom=pc
    

 4. handshark 握手请求:
    
    发起一个请求，从第三方系统中获取ticket对应的loginName。

 5. 返回ticket对应loginName:
    
    外部平台将ticket对应的协同登录名告知协同协同平台。如果没有获取到loginName，表示握手失败。

 6. SSOOK:
    
    平台执行其他相关操作，完成ticket与用户信息绑定的注册（并在内存中存储ticket和username映射）。在response header中增加SSOOK。

 7. 返回ticket

 8. 协同平台通过ticket参数，调用登录操作，完成用户登录
    
    示例:
         /seeyon/main.do?method=login&ticket=[ticket]&ssoFrom=gke&UserAgentFrom=pc
    

 9. 定时发送心跳,保证用户在线
    
    各个端的心跳接口如下:
    
     通用心跳接口(保持当前用户登录的端的心跳):/seeyon/getAJAXOnlineServlet?V=[随机数]
     致信端心跳接口:/seeyon/uc/rest.do?method=showUpdateSystemHistoryMessages&timestamp=[随机数]
     M3端心跳接口: /seeyon/rest/m3/message/classification
    

退出过程：

 * 用户退出协同时，会通过SSOLoginHandshakeInterface的logoutNotify()通知到第三方系统
 * 用户退出第三方系统时，访问协同平台的/seeyon/login/ssologout?from=&ticket=&userAgentFrom通知协同平台 !!!重要，为了安全，必须logout。

接口说明：

 * 外部平台需要有协同登录名的映射表或者使用相同的登录名
 * SSOLoginHandshakeInterface与from映射，需要配置或二次开发。
 * 配置：系统提供通用的com.seeyon.ctp.portal.sso.SSOLoginHandshakeServletImpl，配置url（外部系统中传入ticket返回协同登录名的页面地址）和logoutUrl即可。 二次开发：实现接口SSOLoginHandshakeAbstract，自己编写握手逻辑，比如下面的GKEA8SSOLoginImpl。
 * 平台的验证系统完全依赖和信任第三方系统（存在风险，因此，只在服务器之间握手至关重要）

配置文件说明：在插件的spring目录增加xml配置文件

SSOLoginContext.xml示例：

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
<bean id="gke" class="com.seeyon.ctp.portal.sso.SSOLoginContext">
    <property name="name" value="gke"/>
    <!-- 单点登录成功是否跳转到首页 -->
    <property name="forward" value="false"/>
    <!-- 握手配置 -->
    <property name="handshake">
        <!-- 使用系统实现的缺省握手类 -->
        <bean class="com.seeyon.ctp.portal.sso.SSOLoginHandshakeServletImpl">
            <!-- 第三方系统页面，传入ticket，返回协同登录名 -->
            <property name="url" value="http://第三方系统:8080/checkTicket"/>
            <!-- 第三方系统页面单点登录登出地址 -->
            <property name="logoutUrl" value="http://第三方系统:8080/ssologout"/>
        </bean>
    </property>
</bean>
</beans>


或

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
<bean id="gke" class="com.seeyon.ctp.portal.sso.SSOLoginContext">
    <property name="name" value="gke"/>
    <property name="handshake">
        <!-- 使用自己的握手实现 -->
        <bean class="com.seeyon.v3x.plugin.gke.sso.GKEA8SSOLoginImp" />
    </property>
</bean>
</beans>


二次开发需要实现SSOLoginHandshakeAbstract的handshake和logoutNotify方法

/**
* 通过握手获取平台的认证信息
* @param ticket 平台传过来的令牌信息
* @return 返回当前登录者的登录名
*/
public String handshake(String ticket);

/**
 * A8退出时通知外部平台
 * 
 * @param ticket 平台传过来的令牌信息
 */
public void logoutNotify(String ticket);


代码示例

从GKE登录到协同平台：

public class GKEA8SSOLoginImp  extends SSOLoginHandshakeAbstract {
    // “ticket” 就是ticket取得的参数值
    public String handshake(String ticket) {
        if(ticket==null||ticket.equals("")) {
            return null;
        }
        String userName="";
        // 这个是gke自己特定的ticket格式:{GID},{passport}
        String[] r=ticket.split(",");
        if(r==null||r.length!=2) {
            return null;
        }
        userName=this.checkPassport(r[0], r[1]);
        return userName;
    }
    public void logoutNotify(String ticket) {

    }

    private String checkPassport(String GID,String passPort) {
        StringBuffer sb = new StringBuffer();
        sb.append("<?xml version="1.0" encoding="UTF-8" ?>");
        sb.append("<request type="login" subtype="passport" msid="">");
        sb.append("<message>");
        sb.append("<user");
        sb.append(" GID=""+GID+""  gid=""  zoneid="">");
        sb.append("<passport>");
        sb.append(passPort);
        sb.append("</passport>");
        sb.append("</user>");
        sb.append("</message>");
        sb.append("</request>");  
        // 向GKE发出请求，取得协同登录名
        return getGKEResponse(postGKERequest(sb.toString()));
}



## 单点登录的URL包装

单点登录成功获取Ticket以后，要想使用ticket访问协同平台内部地址，必须对URL进行包装

String ticket = request.getParameter("ticket");
String url="collaboration/collaboration.do?method=summary&openFrom=listPending&affairId=-932843950278492";
TicketInfo ticketInfo = com.seeyon.ctp.portal.sso.SSOTicketBean.getTicketInfo(ticket);
if(ticketInfo != null) {
  response.sendRedirect(com.seeyon.ctp.portal.sso.SSOTicketBean.makeURLOfSSOTicket(ticket, url));
}



## 示例:单点登录+事项列表场景

 1. 通过单点登录接口的tourl参数，直接登录OA并且打开tourl对应OA地址页面。
    
    完整示例：
    
    OA中某待办协同地址：
    http://ip:端口/seeyon/collaboration/collaboration.do?method=summary&openFrom=listPending&affairId=-1036595126906172786
    对应单点登录URL：
    http://ip:端口/seeyon/login/sso?from=sample&ticket=lsm1&UserAgentFrom=pc&tourl=%2fseeyon%2fcollaboration%2fcollaboration.do%3Fmethod%3Dsummary%26openFrom%3DlistPending%26affairId%3D-1036595126906172786
    
    
    从上面的示例中可以看出tourl是OA中具体链接的【/seeyon/collaboration/collaboration.do?method=summary&openFrom=listPending&affairId=-1036595126906172786】部分做了转码。

 2. 通过事项接口获取列表URL后直接打开OA地址页面。
    
    看了上面的示例可能会有人问如何获取OA中具体协同的打开地址呢？
    
    现在OA平台接口有2种方式可以获取事项URL。
    
    第一种方式：SOAP接口的exportPendingList方法：获取待办事项列表。这个接口需要要单点登录成功以后才会导出事项 URL地址。
    
    第二种方式：REST接口中【门户集成】-【事项接口】（注意在V7.0版本，事项接口才可以导出URL地址），可以获取事项的URL地址。
    
    注意：通过以上两种方式获取到URL地址以后，必须要单点登录成功以后，才能再请求获取到的URL地址。而如果是通过tourl方式打开URL，则是单点登录与打开URL同时请求，不需要单独再做单点登录请求。

其他

部署说明：单点登录的开发建立的java文件放在com.seeyon.ctp.portal.sso包下

跳转到协同页面

将协同页面集成为第三方系统菜单项：

单点登录以后，如果要实现在第三方系统打开协同平台任意页面的功能，可以使用下面的跳转链接：

/seeyon/a8genius.do?method=window&url=xxx，

例如：

/seeyon/a8genius.do?method=window&url=calEvent.do%3Fmethod%3DhomeEntry


可以跳转到协同平台的日程计划页面/seeyon/calEvent.do?method= homeEntry 如果不进行跳转，协同平台页面可能找不到依赖的javascript脚本，导致脚本错误，无法使用。

编撰人：lichaoj




快速跳转



 * 单点登录(SSO)
   * 协同平台单点登录第三方系统
     * 实现方式一：关联系统+扩展栏目
     * 实现方式二：Ticket
   * 第三方系统单点登录协同平台
     * 应用场景
     * 关键步骤
     * 实现原理
     * 单点登录的URL包装
     * 示例:单点登录+事项列表场景



分享链接分享链接

## 73. 免登录认证请求

> 原始路径：`/39/2441.html`  
> 相对路径：`39/2441.md`

## 免登录认证请求


## 场景

为了确保系统安全，默认所有的后台请求都要求登录之后才能访问，如seeyon/ajax.do?method=ajaxAction，如未登录，直接访问请求会提示无权限或强制退出。

但某些特殊意义的请求需要确保无需登录，比如帐号密码登录认证请求就需要免登录认证。其它三方认证、握手的请求也往往要求不做登录认证。

产品针对不同版本提供了免登录的解决方案。

注意：能力越大责任越大，谁做的免登录认证，谁就需要对请求的安全性负责！


## V7.1SP1及更早版本免登录认证方案

V7.1SP1及更早版本，对于无需登录即可访问的url（比如登录），可以加@NeedlessCheckLogin注解：

public class MainController{
    @NeedlessCheckLogin
    public ModelAndView login(HttpServletRequest request, HttpServletResponse response) throws Exception {

    }
}


7.1SP1以后将匿名请求控制收归平台统一管理，原则上不允许应用随意新增无需登录的请求。


## V8.0~V8.2版本免登录认证方案

V8.0（包含）到V8.2（包含）之间的版本，需要通过修改 ctp-core\src\main\resources\needless_check_login.xml和needless_check_login_recheck.xml 的配置，配置格式：

<beans>
    <bean>
        <id>/sc.do</id>
        <name>com.seeyon.cap4.form.modules.smartCode.controller.SmartCodeController</name>
        <methods>
            <method>qr</method>
        </methods>
    </bean>
    <bean>
        <id>/media/media.do</id>
        <name>com.seeyon.ctp.common.media.controller.MediaController</name>
        <methods>
            <method>mediaShow</method>
        </methods>
    </bean>

	<!-- 不要删除原来默认的配置，仅在最后beans标签中追加客开需要的免登录接口 -->
	<bean>
        <id>对应springmvc的beanId</id>
        <name>对应springmvc的Controller</name>
        <methods>
            <method>对应Controller下的具体方法，用于限定只开通一个请求</method>
        </methods>
    </bean>
</beans>


代码位置：



最终生产环境打包位置参考“V8.2SP1及更高版本免登录认证方案”的截图。


## V8.2SP1及更高版本免登录认证方案

自V8.2SP1版本开始，为防止侵入标准产品源码，平台提供了扩展登录认证的能力：

客开只需要在各自 ctp-customize-xxx客开工程\src\main\resources\目录 新建needless_check_login_xxx.xml和needless_check_login_recheck_xxx.xml的文件名，其中_xxx名称自定义，最好是插件的英文名：

<beans>
	<!-- 在beans标签中追加客开需要的免登录接口 -->
	<bean>
        <id>对应springmvc的beanId</id>
        <name>对应springmvc的Controller</name>
        <methods>
            <method>对应Controller下的具体方法，用于限定只开通一个请求</method>
        </methods>
    </bean>
</beans>


代码示例：



最终生产环境打包位置：



编撰人：het




快速跳转



 * 免登录认证请求
   * 场景
   * V7.1SP1及更早版本免登录认证方案
   * V8.0~V8.2版本免登录认证方案
   * V8.2SP1及更高版本免登录认证方案



分享链接分享链接

## 74. appLog应用审计日志组件

> 原始路径：`/39/2534.html`  
> 相对路径：`39/2534.md`

## appLog应用审计日志组件


## 背景

标准产品后台管理员提供了“应用日志”模块，该模块记录了各应用的关键行为记录，可作为审计、防抵赖。

开发人员可参考本组件文档对应用日志进行新增、修改。




## 接口说明

接口路径： \ctp-core\src\main\java\com\seeyon\ctp\common\appLog\manager\AppLogManager.java

接口核心方法：

public interface AppLogManager{
    /**
     * 插入操作日志<br>
     * AppLogAction的枚举值对应一条国际化key，前缀统一采用"appLog.action."<br>
     * 如枚举Coll_New(101)，对应Key: "appLog.action.101" <br>
     * 同时增加操作类型简称，appLog.actionType.101 = 新建协同
     * 新增加枚举时需要增加对应的key，变参目由你的国际化key决定.
     * @param user 登录用户
     * @param action 操作类型枚举
     * @param params 操作描述国际化key对应的参数
     */
	@Deprecated
    public void insertLog(User user, AppLogAction appLogAction, String... params);

	/**
	* 传参参考insertLog(User user, AppLogAction appLogAction, String... params)
	* 唯一区别actionId对应AppLogAction.getKey()，适用于客开不侵入AppLogAction源码场景
	**/
    public void insertLog(User user, Integer actionId, String... params);

    /**
     * 批量插入操作日志<br>
     * AppLogAction的枚举值对应一条国际化key，前缀统一采用"appLog.action."<br>
     * 如枚举Coll_New(101)，对应Key: "appLog.action.101" <br>
     * 新增加枚举时需要增加对应的key，变参目由你的国际化key决定.
     * @param user 登录用户
     * @param action 操作类型枚举
     * @param labelsList 操作描述国际化key对应的参数list, List<String[]>根据自己情况构造
     */
    @Deprecated
    public void insertLogs(User user, AppLogAction appLogAction, List<String[]> labelsList);

	/**
	* 传参参考insertLogs(User user, AppLogAction appLogAction, List<String[]> labelsList)
	* 唯一区别actionId对应AppLogAction.getKey()，适用于客开不侵入AppLogAction源码场景
	**/
	public void insertLogs(User user, Integer actionId, List<String[]> labelsList);

	// ---------------- 忽略若干其它方法
}



## 组件接入方法


## AppLogAction注册枚举

AppLogAction并不是开发必须接入的元素，只是让大家理解应用日志的对应关系。

ctp-core\src\main\java\com\seeyon\ctp\common\appLog\AppLogAction.java 枚举类管理了所有审计日志动作，每个模块每个操作类型可在此注册。新版本被 apps-common\src\main\webapp\WEB-INF\cfgHome\i18n\applog\AppLogActions.txt 文件取代。

AppLogAction中的数字编号key是核心，新的开发场景可以不用在此枚举类注册，只需要遵守数字编号key唯一，在后续步骤做好注册即可。

数字编号key规范：

 * 每一个模块占用100个编号，比如协同100~199；公告500~599；组织机构800~899
 * 模块下的每个类型占用一个唯一编号，比如新建协同101，删除协同105

/**
 * 应用日志操作类型枚举
 */
@Deprecated
public enum AppLogAction {
	/**协同_新建协同*/
    Coll_New(101),
    /**协同_转发协同*/
    Coll_Transmit(102),
    /**协同_删除*/
	Coll_Delete(105),

	忽略若干代码......

	/**公告_新建公告 */
    Bulletin_New(501),
    /**公告_修改公告 */
    Bulletin_Modify(502),

	忽略若干代码......

	private int key;

    AppLogAction(int key) {
        this.key = key;
    }

    public int getKey() {
        return this.key;
    }
}



## 维护applog-xxx.properties国际化文件

应用审计日志国际化文件存放于 \apps-common\src\main\webapp\WEB-INF\cfgHome\i18n\applog目录下。 国际化文件正常会有：中文、繁体、英文一式三份，命名格式为applog-模块编号_多语言名称.properties。

以协同模块（占用100~199）为例，英文就是applog-100_en.properties，中文就是applog-100_zh_CN.properties，显示效果如下图：



同理，公告则存放于applog-500_xxx.properties文件中：



开发实际新增、修改维护应用日志就是这些文件，以下是applog-500_zh_CN.properties文件的示例代码：

appLog.action.501         = {0}新建了公告：《{1}》
appLog.action.502         = {0}修改了公告：《{1}》
appLog.action.503         = {0}发布了公告：《{1}》
appLog.actionType.501     = 新建公告
appLog.actionType.502     = 修改公告
appLog.actionType.503     = 发布公告


appLog.action.类型编号与appLog.actionType.类型编号是成对出现。

假如我们需要在公告模块新增一个应用审计类型叫“公告转发”，则需要搜索applog-500_zh_CN.properties文件中的所有数字编号，找一个不存在的编号将其定义成“公告转发”。比如公告501~550、560~599都被使用了，那么我们可以取551~559的其中一个数字做编号，比如数字552：

appLog.action.501         = {0}新建了公告：《{1}》
appLog.action.502         = {0}修改了公告：《{1}》
appLog.action.503         = {0}发布了公告：《{1}》
appLog.action.552         = {0}转发了公告：《{1}》
appLog.actionType.501     = 新建公告
appLog.actionType.502     = 修改公告
appLog.actionType.503     = 发布公告
appLog.actionType.552     = 转发公告



## 业务点调用接口写入日志

新的应用日志编号及日志国际化内容定义好之后，业务侧则调用接口执行日志写入即可：

public class BulDataManagerImpl implements BulDataManager {

	// 注入appLogManager接口
    private AppLogManager                appLogManager;

		public void setAppLogManager(AppLogManager appLogManager) {
		this.appLogManager = appLogManager;
	}

	public Result shareBul(Map<String, Object> param) throws BusinessException {
		....
		// 转发后调用写入应用日志的接口
		appLogManager.insertLog(user, 552, userName, bulData.getTitle());
		....
	}
}



## 结果检查

以上完成后，可以通过页面测试代码是否生效。也可以通过数据库查询ctp_app_log表检查应用日志是否生效。

编撰人：het




快速跳转



 * appLog应用审计日志组件
   * 背景
   * 接口说明
   * 组件接入方法
     * AppLogAction注册枚举
     * 维护applog-xxx.properties国际化文件
     * 业务点调用接口写入日志
     * 结果检查



分享链接分享链接

## 75. 对象存储扩展适配

> 原始路径：`/39/2747.html`  
> 相对路径：`39/2747.md`

## 对象存储扩展适配


## 前言

在协同中，产品的附件、动态资源文件都需要存储管理，产品默认提供了文件存储（共享存储）的方式，自V8.1SP2开始产品又提供了华为云OBS对象存储的标准支持（直接配置使用），但并未标准提供阿里OSS、亚马逊对象存储等其它厂商的对象存储（此类厂商均需要参考本文档做二次开发）。

但针对不同公司的对象存储可能有不同的需求，如使用不同的对象存储厂商、存储在云端或存储在自己的私有存储服务上，因此需要抽象对象存储的接口，让客户在使用时，仅通过实现对象存储的接口即可在协同应用中使用自己的存储服务。本手册提供V5产品对象存储接口文档，供项目上参考适配，以应对不同对象存储厂商二次开发适配。


## 关键工作量

V5对接对象存储定制开发代码适配工作量1周左右（开发+调试）。

如果是老客户的话还要考虑历史附件迁移，部分对象存储厂商有迁移工具（如杉岩）就不需要开发，只需要迁移实施工作量。

如果对象存储厂家没有迁移工具，就要客开写代码迁移，这块工作另算(1周或更多)。


## 三方对象存储集成实现方法


## 三方对象存储二次开发适配案例

如有三方对象存储二次开发适配诉求，可通过CTP-STUDIO平台检索相似修改接口，看别的项目如何接入实现。




## 1、实现RemoteFileHandler接口

接口名称：com.seeyon.ctp.common.file.remote.RemoteFileHandler

说明：对象存储的处理实现类，包含对象的存、改、查等。

不同版本接口方法可能存在变化，需要继承实现当前接口，具体继承实现方案可参考标准的 ctp-file/src/main/java/com/seeyon/ctp/common/file/HuaWeiObsHandler.java

接口方法详细说明：

/**
 * 三方文件存储操作
 * 主要上传，下载文件
 */
public interface RemoteFileHandler {
    /**
     * 获取文件元信息
     * @param fileName  对象存储key
     * @return 文件的元信息
     */
    CtpMetaData headFile(String fileName) throws IOException;

    /**
     * 下载文件为流
     * @param fileName 对象存储key
     * @return 返回文件流
     * @throws IOException
     */
    InputStream downLoadFile(String fileName) throws IOException;

    /**
     * 上传文件
     * @param fileName 保存的对象存储key
     * @param inputStream 上传的数据流
     * @throws IOException
     */
    void uploadFile(String fileName, InputStream inputStream) throws IOException;

    /**
     * 上传文件
     * @param fileName 保存的对象存储key
     * @param file 上传的文件对象
     * @throws IOException
     */
    void uploadFile(String fileName, File file) throws IOException;

    /**
     * 上传文件
     * @param fileName 保存的对象存储key
     * @param file 上传的文件对象
     * @param metaData 文件的元数据信息
     * @throws IOException
     */
    void uploadFile(String fileName, File file, CtpMetaData metaData) throws IOException;

    /**
     * 上传文件
     * @param fileName 保存的对象存储key
     * @param inputStream 上传的数据流
     * @param metaData 文件的元数据信息
     * @throws IOException
     */
    void uploadFile(String fileName, InputStream inputStream, CtpMetaData metaData) throws IOException;

    /**
     * 创建一个空文件
     * @param fileName 保存的对象存储key
     * @return 返回创建成功（true）,创建失败 false
     * @throws IOException
     */
    boolean createNewFile(String fileName) throws IOException;

    /**
     * 删除文件
     * @param fileName 删除的对象存储key
     * @return 返回删除成功（true）,删除失败 false
     * @throws IOException
     */
    boolean deleteFile(String fileName) throws IOException;

    /**
     * 创建文件目录
     * @param fileName 对象存储key
     * @return 返回创建成功（true）,创建失败 false
     * @throws IOException
     */
    boolean mkdir(String fileName) throws IOException;

    /**
     * 上传文件 （以file的绝对路径作为对象存储key ）
     * @param file 待上传的文件
     * @throws IOException
     */
    void uploadFile(File file) throws IOException;

    /**
     * 追加写文件
     * @param fileName 待追加写的对象存储key
     * @param inputStream 待追加写入的数据流
     * @throws IOException
     */
    void appendUploadFile(String fileName, InputStream inputStream) throws IOException;

    /**
     * 文件重名名
     * @param srcFile 原对象存储key
     * @param tarFile 修改后对象存储key
     * @return 返回修改成功（true）,修改失败 false
     * @throws IOException
     */
    boolean renameTo(String srcFile, String tarFile) throws IOException;

    /**
     * 获取文件的访问url
     * 此方法有安全风险，可跟进情况看是否需要实现
     * @param fileName
     * @return url方式访问的地址
     * @throws IOException
     */
    String getUrl(String fileName) throws IOException;

    /**
     * 列举出以fileName开头的所有文件（类似于文件操作中递归列举目录下所有文件）
     * @param fileName 对象存储key的前缀
     * @return 文件列表
     * @throws IOException
     */
    List<String> listAll(String fileName) throws IOException;

    /**
     * 列举前缀目录下的所有obs对象（等价文件操作中列举目录下文件）
     * @param fileDir obs对象的key的前缀
     * @param recursion  是否递归查找 ，true 表示递归查找，false不递归
     * @return 文件列表
     * @throws IOException
     */
    List<String> listDir(String fileDir, boolean recursion) throws IOException;

    /**
     * 更新文件的元信息
     * @param fileName 待更新的obs对象key
     * @param meta 更新的文件元信息
     * @return 返回修改成功（true）,修改失败 false
     * @throws IOException
     */
    boolean updateMeta(String fileName, Map<String, String> meta) throws IOException;

    /**
     * 更新文件的最后一次修改时间
     * @param fileName 待更新的obs对象key
     * @param newModify 更新的文件修改时间
     * @return 返回修改成功（true）,修改失败 false
     * @throws IOException
     */
    boolean updateLastModify(String fileName, long newModify) throws IOException;

    /**
     * 获取obs桶的整个容量（单位：byte）
     * @return 返回容量
     * @throws IOException
     */
    long getTotalSpace() throws IOException;

    /**
     * 获取obs桶的剩余可用容量 （单位：byte）
     * @return 返回容量
     * @throws IOException
     */
    long getUsableSpace() throws IOException;

    /**
     * 复制文件
     * @param srcFileName 待复制的原文件（对象存储key）
     * @param tarFileName 复制后的的目标文件（对象存储key）
     * @return 返回复制成功（true）,复制失败 false
     * @throws IOException
     */
    boolean copyFile(String srcFileName, String tarFileName) throws IOException;
}



## 2、实现HealthChecker接口

接口名称：com.seeyon.ctp.common.file.remote.HealthChecker

说明：服务启动时检查存储服务是否正常

需要继承实现当前接口，具体继承实现方案可参考标准的 ctp-file/src/main/java/com/seeyon/ctp/common/file/HuaWeiObsHealthChecker.java

方法详细说明：

public interface HealthChecker {

   /**
    * 心跳检查（OBS服务正常则无返回，否则抛出异常）
    * @return
    * @throws IOException
    */
   boolean health() throws IOException;
}



## 3、修改seeyon-ctp-file.jar中的META-INF

协同OA程序目录下，找到文件webapps\seeyon\WEB-INF\lib\seeyon-ctp-file.jar，使用压缩工具打开并分别修改如下两个文件的内容，将如下两个文件中的对象存储实现类改成前面客开实现的对象存储类：

 * \META-INF\services\com.seeyon.ctp.common.file.remote.HealthChecker
 * \META-INF\services\com.seeyon.ctp.common.file.remote.RemoteFileHandler




## 4、设置对象存储参数

参考对应版本部署手册-对象存储章节，打开SeeyonConfig，在OBS配置页开启远程对象存储（设置为ture），并填写OBS需要的Access Key、Security Key、Endpoint、桶名和配置路径等，随后启动验证功能，参考说明如下图：




## 文件存储数据迁移对象存储

发布对象存储程序后，新产生的数据会按对象存储形式保存，但原历史文件不会自动迁移。

如项目上有历史附件资源文件迁移对象存储的需求，需要联合对象存储厂商一起，针对产品的存储格式、存储风格，进行迁移规划，这个一般存在不少工作量，甚至迁移工具的开发（1周以上）。

研发有华为云对象存储的项目化迁移工具，有华为云迁移项目，可发起支持单从研发侧获取项目化迁移工具。

编撰人：het


快速跳转



 * 对象存储扩展适配
   * 前言
   * 关键工作量
   * 三方对象存储集成实现方法
     * 三方对象存储二次开发适配案例
     * 1、实现RemoteFileHandler接口
     * 2、实现HealthChecker接口
     * 3、修改seeyon-ctp-file.jar中的META-INF
     * 4、设置对象存储参数
   * 文件存储数据迁移对象存储



分享链接分享链接

## 76. 技术解决方案

> 原始路径：`/40/`  
> 相对路径：`40/README.md`

子菜单名称         URL
M3            M3
门户空间          门户空间
组织机构          组织机构
工作流           工作流
公文            公文
会议            会议
统一待办降版本适配手册   统一待办降版本适配手册
数据库           数据库
致信            致信
云联            云联
问题排查方法        问题排查方法
平台            平台
协同模板          协同模板
CIP应用平台       CIP应用平台
中间件           中间件
V5V8融合        V5V8融合

分享链接分享链接

## 77. 组织机构解决方案

> 原始路径：`/40/89/`  
> 相对路径：`40/89/README.md`

## 组织机构解决方案

编撰人：admin


快速跳转



 * 组织机构解决方案



分享链接分享链接

## 78. 管理员菜单维护

> 原始路径：`/40/89/90.html`  
> 相对路径：`40/89/90.md`

## 管理员菜单维护

V8.1开始，标准产品对组织机构做了调整：全面开启了三元分离和三员角色化，在代码层面会有很大调整，详见如下信息。


## 需要修改


## AppContext.isXxxxAdmin

将旧版本左侧的代码用右侧写法替代：

AppContext.isGroupAdmin()==> orgHelper.isLoginGroupAdminRole()
AppContext.isAdministrator()==> orgHelper.isLoginUnitAdminRole()
AppContext.isAuditAdmin()==> orgHelper.isLoginGroupAdminRole()
AppContext.isSystemAdmin()==> orgHelper.isLoginGroupAdminRole()



## User.isXxxAdmin

将旧版本左侧的代码用右侧写法替代：

r.isGroupAdmin() ==> orgHelper.isLoginGroupAdminRole()
r.isAdministrator()==> orgHelper.isLoginUnitAdminRole()
r.isAuditAdmin() ==> orgHelper.isLoginGroupAdminRole()
r.isSystemAdmin() ==> orgHelper.isLoginGroupAdminRole()



## orgManager.getXxxx

将旧版本左侧的代码用右侧写法替代：

getSystemAdmin() ==> findSystemAdmin()
getAuditAdmin() ==> findAuditAdmin()
getGroupAdmin() ==> findGroupAdmin()
getAdministrator() ==> findAdministrator()



## 角色化管理员适配示例

由于角色化，系统管理员的菜单从原来固定的角色，变为多种组合，以前通过角色判断的是否具有某个菜单资源的方式不再合适。所以一般建议改为使用资源code判断权限。适配需要修改的点：

1、菜单配置文件。

2、修改@CheckRoleAccess配置。

3、修改原有的集团管理员、单位管理员区分逻辑。

4、验证业务功能。


## 菜单配置文件

ctp-organization\src\main\webapp\WEB-INF\cfgHome\metadata
metadata                                        
├─ entRoleStd                                   
│  ├─ menu-AccountAdministrator-A6.xml   //A6:单位管理员（原admin1账号）             
│  ├─ menu-AccountAdministrator-A6C.xml       //A6C:单位管理员（原admin1账号）          
│  ├─ menu-AccountAdministrator-Enterprise.xml  //A8-1:单位管理员（原admin1账号）    
│  ├─ menu-AccountAdministrator.xml  //系统管理员（原system账号）               
│  ├─ menu-AuditAdmin.xml   //审计管理员（原audit-admin账号）                        
│  ├─ menu-GroupAdmin.xml  //集团管理员（原group-admin账号）                         
│  └─ menu-SystemAdmin.xml  //系统管理员（原system账号）            
├─ govRoleStd                                   
│  ├─ menu-GroupAuditAdmin.xml    //三员-系统级-审计管理员                  
│  ├─ menu-GroupSecretAdmin.xml    //三员-系统级-安全管理员                         
│  ├─ menu-GroupSystemAdmin.xml    //三员-系统级-系统管理员                        
│  ├─ menu-UnitAuditAdmin.xml      ///三员-单位-审计管理员             
│  ├─ menu-UnitSecretAdmin.xml     //三员-单位-安全管理员       
│  ├─ menu-UnitSystemAdmin-A6.xml   //A6:三员-单位-系统管理员
│  ├─ menu-UnitSystemAdmin-A6C.xml    //A6c:三员-单位-系统管理员     
│  ├─ menu-UnitSystemAdmin-Enterprise.xml      //A8-1：三员-单位-系统管理员
│  └─ menu-UnitSystemAdmin.xml    //A8-2:三员-单位-系统管理员   
├─ menu-SystemInitAdmin.xml     //初始化管理员



## 配置文件说明

菜单配置文件包含两个部分菜单部分、资源code部分。

1、菜单部分用于配置系统管理员菜单入口、命名、图标等信息

2、资源code部分用于配置当前对应的管理员，没有菜单入口但是又要访问的资源code.

<?xml version="1.0" encoding="UTF-8"?>
<GroupAdmin>
    <!-- 菜单配置 -->
    <menus>
      <menu code="org_workscope_setting" sort="9" name="system.menuname.AccessLevelConfig" desc="工作范围管理" icon="icon-gongzuofanweiguanli" target="mainfrm" plugin="" url="/organization/workscopeController.do?method=showWorkscopeframe" ></menu>
    </menus>
    <!--配置有权限的资源code-->
    <virtualCode>
        <code>system_back_admin</code>
    </virtualCode>
</GroupAdmin>


下边我以组织机构_工作范围管理_、_特殊账号管理_适配过程为例，来说明怎么适配角色化后权限控制。


## 工作范围管理

1、为菜单定义资源code，命名建议{模块}_{子模块}_{功能},如果org_workscope_setting表示组织机构工作范围管理

// 修改前
<menu code="" sort="9" name="system.menuname.AccessLevelConfig" desc="工作范围管理" icon="icon-gongzuofanweiguanli" target="mainfrm" plugin="" url="/organization/workscopeController.do?method=showWorkscopeframe" ></menu>

// 修改后
<menu code="org_workscope_setting" sort="9" name="system.menuname.AccessLevelConfig" desc="工作范围管理" icon="icon-gongzuofanweiguanli" target="mainfrm" plugin="" url="/organization/workscopeController.do?method=showWorkscopeframe" ></menu>


2、修改后端@CheckRoleAccess配置

// 修改前
@CheckRoleAccess(roleTypes={Role_NAME.GroupAdmin,Role_NAME.AccountAdministrator,Role_NAME.HrAdmin})
public class WorkscopeController extends BaseController {
}

//修改后,将角色判断去掉，添加:resourceCode = "org_workscope_setting"
@CheckRoleAccess(roleTypes={Role_NAME.HrAdmin},resourceCode = "org_workscope_setting")
public class WorkscopeController extends BaseController {
}



## 特殊账号管理

1、菜单code定义

// 修改前
<menu code="" sort="7" name="system.menuname.Guest.special.accountManagement" desc="特殊账号管理" icon="icon-teshuzhanghaoguanli" target="mainfrm" plugin="vPortalAdvanced" url="/organization/guestController.do?method=showGuestframe" ></menu>

// 修改后
<menu code="org_gust_setting" sort="7" name="system.menuname.Guest.special.accountManagement" desc="特殊账号管理" icon="icon-teshuzhanghaoguanli" target="mainfrm" plugin="vPortalAdvanced" url="/organization/guestController.do?method=showGuestframe" ></menu>


2、修改@CheckRoleAccess

// 修改前
@CheckRoleAccess(roleTypes={Role_NAME.GroupAdmin,Role_NAME.AccountAdministrator})
public class GuestController extends BaseController {
}

//修改后,将角色判断去掉，添加:resourceCode = "org_workscope_setting"
@CheckRoleAccess(resourceCode = "org_gust_setting")
public class GuestController extends BaseController {
}


3、集团管理员与单位管理员区隔适配

// 修改前
public ModelAndView showGuestframe(HttpServletRequest request, HttpServletResponse response) throws Exception {
        ModelAndView mav = new ModelAndView("apps/organization/guest/guestHome");
        User user = AppContext.getCurrentUser();
        boolean isGroupVer = (Boolean) (SysFlag.sys_isGroupVer.getFlag());
        mav.addObject("isGroupVer", isGroupVer);
        mav.addObject("isGroupAdmin", OrgHelper.isGroupAdmin());// 前端需要缺乏是集团管理员or  单位管理员
        mav.addObject("isAdministrator", OrgHelper.isAdministrator());// 前端需要缺乏是集团管理员or  单位管理员
        return mav;
}


// 修改后
public ModelAndView showGuestframe(HttpServletRequest request, HttpServletResponse response) throws Exception {
        ModelAndView mav = new ModelAndView("apps/organization/guest/guestHome");
        User user = AppContext.getCurrentUser();
        boolean isGroupVer = (Boolean) (SysFlag.sys_isGroupVer.getFlag());
        mav.addObject("isGroupVer", isGroupVer);
        mav.addObject("isLoginGroupAdminRole", OrgHelper.isLoginGroupAdminRole());// 改为判断当前用户是否为集团的管理角色
        mav.addObject("isLoginUnitAdminRole", OrgHelper.isLoginUnitAdminRole());// 改为判断当前用户是否为单位的管理角色
        return mav;
}



## 废弃的组织机构变量

安全起见，以下变量废弃：

/**
     * 系统管理员预置ID
     * @deprecated 角色角色化后，废弃不再使用
     */
    public static final Long SYSTEM_ADMIN_ID = -72730320***L;
    /**
     * 审计管理员预置ID
     * @deprecated 角色角色化后，废弃不再使用，8.1后可能删除
     */
    public static final Long AUDIT_ADMIN_ID = -44016066***L;
    /**
     * 集团管理员预置ID
     * @deprecated 角色角色化后，废弃不再使用，8.1后可能删除
     */
    public static final Long GROUP_ADMIN_ID = 5725175934***L;


编撰人：admin


快速跳转



 * 管理员菜单维护
   * 需要修改
     * AppContext.isXxxxAdmin
     * User.isXxxAdmin
     * orgManager.getXxxx
   * 角色化管理员适配示例
     * 菜单配置文件
     * 配置文件说明
     * 工作范围管理
     * 特殊账号管理
   * 废弃的组织机构变量



分享链接分享链接

## 79. 流程图详解

> 原始路径：`/40/202/203/204.html`  
> 相对路径：`40/202/203/204.md`

## 流程图详解

## 流程xml解析



## 节点分类解析



## 分支信息



## 流程数据表信息



## 基础方法



编撰人：chenxd、admin


快速跳转



 * 流程图详解
   * 流程xml解析
   * 节点分类解析
   * 分支信息
   * 流程数据表信息
   * 基础方法



分享链接分享链接

## 80. 流程中各状态值

> 原始路径：`/40/202/203/205.html`  
> 相对路径：`40/202/203/205.md`

## 流程中各状态值

## wf_case_run



## wf_process_running



## wf_workitem_run



## CaseLog（CaseContent）



## CaseContent字段控制节点图标状态



编撰人：chenxd、admin




快速跳转



 * 流程中各状态值
   * wfcaserun
   * wfprocessrunning
   * wfworkitemrun
   * CaseLog（CaseContent）
   * CaseContent字段控制节点图标状态



分享链接分享链接

## 81. 流程事件与节点事件

> 原始路径：`/40/202/203/206.html`  
> 相对路径：`40/202/203/206.md`

## 流程事件与节点事件

流程事件实现需要实现AbstractWorkflowEventInterface.java里面的接口，接口名及含义如下：

处理前：onBeforeFinishWorkitem
处理后：onFinishWorkitem
回退前：onBeforeStepBack
回退后：onStepBack
取回前：onBeforeTakeBack
取回后：onTakeBack
撤销前：onBeforeCancel
撤销后：onCancel
终止前：onBeforeStop
终止后：onStop
流程发起前：onBeforeStart
流程发起：onStart
流程结束前：onBeforeProcessFinished
流程结束：onProcessFinished


接口参数WorkflowEventData对象

流程事件设置：集团管理员登录在CIP业务流程集成里面绑定，绑定好对应事件后，绑定信息会存入WF_PROCESS_PROPERTY表，在调用流程发起的时候，会从WF_PROCESS_PROPERTY表找到对应的数据，拷贝一份和发起的流程绑定后再存入WF_PROCESS_PROPERTY表。

注意：常用的处理前事件是通过前端JS去调用的，拿到后端给的结果后再去调用处理后事件。处理前和处理后就不在同一个线程里面，如果处理的过程中出现问题，处理前事件是无法回滚的。可能还存在处理前事件执行过程中网络中断或者页面异常关闭的问题，导致流程没有往下流转但是处理前事件已经触发的问题。


编撰人：chenxd、admin


快速跳转



 * 流程事件与节点事件



分享链接分享链接

## 82. 超级节点基础信息

> 原始路径：`/40/202/203/207.html`  
> 相对路径：`40/202/203/207.md`

## 超级节点基础信息

数据表：

WF_SUPERNODE		超级节点信息表
WF_SUPERNODE_CONTROL	已发起流程中激活的超级节点信息（designated_member_id干预人Id）
WF_SUPERNODE_CONTROL_DETAIL	已发起流程中激活的超级节点的详细信息（包含超级节点的返回信息和return_code）


超级节点的实现：继承BaseSuperNodeAction父类，执行executeAction方法，返回对象SuperNodeResponse 里面的return_code码的几种状态：

FORWARD(1), // 向前
BACK(2), // 向后
HUMAN(3), // 转人工处理
WAIT(4), // 等待外部调用
STOP(5), // 终止流程
CANCEL(6); // 撤销流程


启动OA的时候，会去扫描实现了SuperNodeManager接口的实现类

具体的执行过程：A（普通节点）---B（超级节点）---C（普通节点）

A提交的时候，判断到B节点是超级节点，会走到SuperNodeDispatcher类中的onActivityReady方法，给超级设置干预人的		workitem和affair数据，并且将超级节点任务放到任务队列里面，这时候的workitem的perfomer字段和affair的memberId字段是一个随机的UUID，不是具体某个人的人员Id。只有超级节点在转干预人的时候才会将这两个字段替换成干预人的Id，替换后干预人的待办事项就有相应的待办数据。
超级节点的任务是新起了一个线程去执行，所以可能存在A节点还没完成，事务没有提交就开始执行超级节点任务的情况。这时候超级节点的相关信息都还没有入库，没有写到（WF_SUPERNODE_CONTROL）表，当检测到该情况时，超级节点任务会延时执行，到达一定时间还是获取不到任务，该超级节点的任务就会自动废弃。
获取到任务后，会去执行超级节点具体的逻辑，然后根据SuperNodeResponse对象里面的returnCode来决定流程的走向。


编撰人：chenxd、lichaoj、admin


快速跳转



 * 超级节点基础信息



分享链接分享链接

## 83. 业务关系和简单场景

> 原始路径：`/40/202/203/227.html`  
> 相对路径：`40/202/203/227.md`

## 业务关系和简单场景

## 流程是和业务组的关系

COL_SUMMARY表记录整个协同的数据，主要关注processId和caseId
CTP_AFFAIR事项表，每条协同数据，有多少人就有多少数据（正常情况下，除了撤销，回退等操作产生的数据），主要关注sub_object_id(WF_WORKITEM_RUN表的主键ID),activity_id(节点ID),processId以及caseId




## 简单的闭环流程（提交场景）



## 流程不满足的分支节点怎么屏蔽

分支条件解析满足的接口：ActionRunner.getConditionValue
分支条件计算：WorkflowFunctions.java
提交的时候日志信息：
14:45:30 [H-92]  INFO: ProcessEngineImpl: - chen,W_I:=2755396907718623273; W_N:=; 	W_C:={"matchRequestToken":"7373653295765867504","condition":[{"nodeId":"163274129988710","isDelete":"false"},{"nodeId":"163274129988711","isDelete":"true"}]}; W_M:=; readyObject:=null;NodeConditionChangeInfoMap:{}

重要信息："condition":[{"nodeId":"163274129988710","isDelete":"false"},	{"nodeId":"163274129988711","isDelete":"true"}]
isDelete等于true表示当前节点所在分支不满足条件

//将节点是否需要激活放入context
WorkflowUtil.putNodeConditionToContext(context, activity, "isDelete", isDelete)
//从context中取出该节点的状态
WorkflowApiUtil.getNodeConditionFromContext(context,activittty,"isDelete");

实际流转，将能流转到的节点和不能流转到的节点信息放入WF_CASE_RUN表的case_content字段的	wf_node_condition_change_key属性见下面的数据：
{
"datamap":{
    "appName":"collaboration",
    "wf_node_condition_change_key":{
        "16327412955304":{
            "isDelete":"false"
        },
        "163274129988710":{
            "isDelete":"false"
        },
        "163274129988711":{
            "isDelete":"true"
        },
        "16327412998866":{
            "isDelete":"false"
        },
        "16327412998867":{
            "isDelete":"false"
        }
    }
}
}

前端查看流程图的时候会从wf_case_run中取出节点信息，动态的设置节点的状态：BPMSeeyonPolicy.setIsDelete(String isDelete);

public Map<String, String> getConditionMapFromCase(BPMCase theCase, String nodeId) {
    Object result = theCase == null ? null : theCase.getData(WorkFlowConstants.WF_NODE_CONDITION_CHANGE_KEY);
    Map<String, String> nodeData = result == null ? null : ((Map<String, Map<String, String>>) result).get(nodeId);
    return nodeData == null ? new HashMap<>() : nodeData;
}




## 流程图添加删除节点

原理：BPMProcess已经封装好了节点和线之间的关系
添加节点:串行添加 在A节点后面添加B节点  s----A-b-----c---e
process.addChild(BNode); 向流程中添加节点
BPMTransition transition = new BPMTransition(ANode,BNode);//建立A节点和B节点之间的线
process.addLink(transition);//将线加入流程
BPMTransition aDowLink = ANode.getDownTransitions().get(0);//获取A节点原来的down线
BNode.addDownTransition(aDowLink);//B节点和down线建立联系
aDowLink.setFrom(BNode);//线和B节点建立联系

添加并行节点：split和join节点总是成对出现，需要建立两者之间的关系
创建split节点：BPMAndRouter split= new BPMAndRouter(splitId, "split");
创建join节点：BPMAndRouter join = new BPMAndRouter(joinId,"join");
split.setStartAnd(true);
join.setStartAnd(false);
split.setParallelismNodeId(relevancyId);
join.setParallelismNodeId(relevancyId);


编撰人：chenxd、admin


快速跳转



 * 业务关系和简单场景
   * 流程是和业务组的关系
   * 简单的闭环流程（提交场景）
   * 流程不满足的分支节点怎么屏蔽
   * 流程图添加删除节点



分享链接分享链接

## 84. 获取客户流程图的方式

> 原始路径：`/40/202/210/211.html`  
> 相对路径：`40/202/210/211.md`

## 获取客户流程图的方式

第一步： 找到打开流程图的请求/designer.do?method=showDiagram，右键Save all as HAR with content将整个数据保存到桌面 第二步： 打开chrome浏览器的审查元素，将第一步保存的后缀为.har的文件，拖动到自己本地的chrome浏览器里面，就可以看到客户那边这个 请求完整的参数以及返回值。 第三步： 拷贝该请求response里面的数据

第四步： 找到本地工程ctp-workflow\svg_workflow_designer\demo目录下的displayCommonCollProcess.js，将第三步的拷贝的数据放到displayCommonCollProcess.js里面 第五步： 在ctp-workflow\svg_workflow_designer目录下执行node server.js命令，会将客户那边取过来的流程图展示出来

编撰人：chenxd、admin


快速跳转



 * 获取客户流程图的方式



分享链接分享链接

## 85. 分支满足人员匹配到了还是弹框

> 原始路径：`/40/202/213/214.html`  
> 相对路径：`40/202/213/214.md`

## 分支满足人员匹配到了还是弹框

## 场景1：

节点是单人执行但是匹配出来的人员大于1个人，所以必须要选择一个


## 场景2：

节点是多人执行，前端要弹框让用户选择哪几个人执行


## 场景3：

勾选了允许从组织架构中选人的选项，如下图




## 场景4：

设置了分支可选数


## 场景5：

设置了非强制分支


编撰人：chenxd、admin


快速跳转



 * 分支满足人员匹配到了还是弹框
   * 场景1：
   * 场景2：
   * 场景3：
   * 场景4：
   * 场景5：



分享链接分享链接

## 86. 修复流程图数据及相关协同、表单数据等

> 原始路径：`/40/202/788/789.html`  
> 相对路径：`40/202/788/789.md`

## 修复流程图数据及相关协同、表单数据等


## 目标

 1. 流程标题
 2. 流程发起人
 3. 表单控件内容
 4. 意见区对应节点
 5. 已走完流程中发起节点


## 数据库表相关

【CTP_AFFAIR】 - FORM_APP_ID 表单id，当前表单中所有数据该值都一样，目标表单该id为 -4692955500345013816 【CTP_AFFAIR】 - PROCESS_ID 流程id = 【WF_PROCESS_RUNNING】表的id = 【WF_CASE_RUN】表的PROCESSID = 【CTP_PROCESS_LOG】表的PROCESS_ID = 【COL_SUMMARY】表的PROCESS_ID 【CTP_AFFAIR】 - STATE 流程状态：待办-3 已办-4 【CTP_AFFAIR】 - SUB_STATE 流程副状态：0-正常结束

【CTP_AFFAIR】流程节点相关 【WF_PROCESS_RUNNING】流程图相关 【WF_CASE_RUN】流程图相关 【CTP_PROCESS_LOG】流程日志相关 【COL_SUMMARY】 流程整体相关


## 获取关键关联数据

 1. 人员替换数据获取：人员【测试1】替换为人员【zz2】

-- 执行sql，自行更改人员名称
select ID,NAME from org_member where NAME in ('测试1','zz2')


 2. 确认对应的ID与人员名称

 3. 流程【流程Id-processId】、【表单记录id-formRecordId】获取： 打开需要修改的数据流程任一节点，获取url中的affairId【4667429481687958886】

-- 获取流程Id-processId&表单记录id-formRecordId
select PROCESS_ID, FORM_RECORDID from ctp_affair where id = 4667429481687958886;



## 具体修改步骤

 * 流程标题

-- 节点标题
select * from ctp_affair where process_id  = 4519538881911210689;
-- 总流程标题
select * from col_summary where process_id  = 4519538881911210689;


以上查询结果的SUBJECT均需修改

 * 流程发起人

-- 查找发起节点
-- process_id为【流程Id-processId】
select * from ctp_affair where process_id  = 4519538881911210689 and state = 2;


查询结果修改MEMBER_ID&SENDER_ID

-- 查找总流程
-- process_id为【流程Id-processId】
select * from col_summary where process_id  = 4519538881911210689;


查询结果修改START_MEMBER_ID

-- 查找表单记录
-- id为【表单记录id-formRecordId】
select * from formmain_0017 where id = 2172893486824571236;


查询结果修改START_MEMBER_ID

-- 查询流程日志发起人
-- process_id为【流程Id-processId】
select * from ctp_process_log where process_id = 4519538881911210689 and ACTIVITY_ID = -1;


查询结果修改ACTION_USER_ID

 * 表单控件内容 数据字典中查看到需修改表单控件对应的表名及字段名 id为【表单记录id-formRecordId】 表名为数据字典中对应表名 列名为数据字典中对应字段名称 select field0003 from formmain_0017 where id = 2172893486824571236; 修改查询结果中的内容

 * 意见区对应节点 页面开启F12，确认节点的affairId

select * from ctp_affair where id = -225551282638601123;


修改查询结果中的MEMBER_ID

 * 流程图已走完流程中发起节点

-- id为【流程Id-processId】
select * from wf_process_running where id = 4519538881911210689;


查询结果中，若PROCESS_XML不为空则直接更改PROCESS_XML 若PROCESS_XML为空则执行

-- processid为【流程Id-processId】
select * from wf_case_run where processid = 4519538881911210689;


查询结果中需修改CASE_CONTENT

编撰人：lichaoj


快速跳转



 * 修复流程图数据及相关协同、表单数据等
   * 目标
   * 数据库表相关
   * 获取关键关联数据
   * 具体修改步骤



分享链接分享链接

## 87. 查询性能问题解决方案

> 原始路径：`/40/299/1117.html`  
> 相对路径：`40/299/1117.md`

## 查询性能问题解决方案


## 方案之索引

1、对于ctp_affair表，参考高版本的索引创建，并确保所分析sql正确使用该索引。

2、没有固定方案，分析sql，合理建立索引。


## 方案之分步查询


## 原理

去除连表查询，使用单表查询策略，将多次单表查询的结果合并后返回。


## 适用场景

查询sql是多表关联，查询结果集需要展示多表字段内容，默认查询条件全部在一个表中，其他查询条件全部或者部分都在同一个表中。


## 改造方案

1、梳理sql，整理查询条件各字段属于哪个表关系清单，整理各展示字段属于哪个表关系清单。

2、将查询条件所在的表执行一次查询，将此表需要的字段先查出来，同时达到分页效果。

3、根据第2步结果，使用关联字段再去其他表中单独查询数据，最后将数据与第一次查询的结果集合并到一起后返回。由于已经分页，所以查询其他表的数据量相当少，耗时忽略不计。

4、判断接口传入的条件，如分步在多个表，依旧执行多表关联查询。


## 优缺点

优点：

 * 改造成本低、仅需处理dao层sql拼接逻辑。

 * 影响范围小，基于dao层处理，外部使用不受影响，对业务造成的影响小。

缺点：

 * 并非所有场景都适用，需要分析sql是否符合分步要求。
 * 不一定所有条件都支持分步要求，可能存在部分查询条件依旧需要走连表。


## 案例

某所ctp_affair表1.25亿数据，其中协同数据1.16亿，公文0.09亿，体现在协同待办、协同已办、公文待办、公文已办耗时较长。分析查询语句发现，使用ctp_affair表与col_summary或者edoc_summary表关联，大部分查询条件都在ctp_affair表，极少部分在summary表中。使用多账号多场景验证sql，连表查询平均耗时0.30秒，单表查询平均耗时0.03秒（oracle数据库，缓存无法完全清除，无法准确定位首次请求，体现不出几十秒的效果。数据均在存在缓存的情况下多次查询得出），速度提升10倍。改造后监控capability.log请求日志，客户早高峰使用期间，接口平均耗时由5秒降低至1秒。


## 方案之分库


## 原理

数据库均有一个阈值，此阈值根据数据库硬件条件、参数设置等变化。一旦数据量超过此阈值，查询效率将急剧下降。通过分库，将数据拆分到其他数据库，以减少数据角度提升查询性能。


## 适用场景

已经采用其他方式提升查询性能，随着数据增长，的确由于数据太多导致性能无法再提升。迁移的数据仅做查询使用，不继续处理。


## 改造方案（以协同转储分库为例）

1、创建分库

2、将已完结，且发起时间为两年前的协同数据迁移至分库，协同数据包含col_summary、ctp_affair及其他相关联的各表（根据表在业务中使用情况可以有所变化）

3、前台页面新增入口用于查询分库数据，查询条件根据实际情况做增减，如查询使用多表关联，需确保都在同一个数据库。否则可以考虑减少查询条件，或者增加表一起迁移至分库。

4、配置分库数据源，通过配置不同的bean，控制查询主库或是分库。

注：标准产品v6.1sp2及以上版本支持协同业务转储，插件控制


## 优缺点

优点：

 * 最后解决方案，从数据量角度，根本上解决问题。

缺点：

 * 改造成本大，预估不少于20人/天，业务代码几乎需要全场景适配，v6.1sp2版本以下额外涉及平台底层改造支撑。
 * 影响范围大，与业务展现相关所有场景均可能造成影响，如改造不完善，将导致部分功能无法正常展现数据。


## 案例

某局ctp_affair表8千万+采用分库策略，迁移4千万数据到分库后，在其他条件不变的情况下，查询速度由1分+降至20秒+

编撰人：lichaoj、admin




快速跳转



 * 查询性能问题解决方案
   * 方案之索引
   * 方案之分步查询
     * 原理
     * 适用场景
     * 改造方案
     * 优缺点
     * 案例
   * 方案之分库
     * 原理
     * 适用场景
     * 改造方案（以协同转储分库为例）
     * 优缺点
     * 案例



分享链接分享链接

## 88. 公文升级问题

> 原始路径：`/40/310/311.html`  
> 相对路径：`40/310/311.md`

## 公文升级问题


## 1、升级异常

## 排查方案：

1、 去升级日志all.log和ctp.log检查是否有报错。 2、 根据报错排查逻辑。

示例：BUG2020102720389 原因：all.log有异常日志，升级出错。 方案：根据代码情况修复。


## 2、升级后部分公文元素内容丢失

## 排查方案：

1、 查看ctp.log日志检查是否存在报错 2、 查看all.log日志检查是否存在报错

原因汇总： 示例：BUG2020092517439 原因：V5.1SP1升V5.6时，将edoc_summary表字段拆分部分到edoc_summary_extend表中，由于客开修改过原库中部分字段长度，且此长度超过标准产品对应字段长度，导致插入报错。 方案：客开行为导致，由客开处理。

编撰人：wxju


快速跳转



 * 公文升级问题
   * 1、升级异常
     * 排查方案：
   * 2、升级后部分公文元素内容丢失
     * 排查方案：



分享链接分享链接

## 89. 公文概念和数据结构

> 原始路径：`/40/310/1000.html`  
> 相对路径：`40/310/1000.md`

## 公文概念和数据结构


## 一、确认公文属于"cap3新公文"还是"老企业公文"

## 方式1

select govdoc_type from edoc_summary where id = ?

govdoc_type 字段不存在，或者等于 0，则是"老企业公文"，否则是"cap3新公文"

## 方式2

浏览器url中包含"govdoc.do"的是"cap3新公文"，否则是"老企业公文"


## 二、表间关系

## 说明

 * 描述公文常见表及关联关系、常见字段、常见状态介绍
 * 由于版本差异，字段会存在一定差异

## 公文主表 edoc_summary

## 说明

 * 公文主要内容存储表
 * 关系：edoc_summary.templete_id = ctp_template.id
 * 关系：edoc_summary.form_app_id = form_definition.id

## 字段

 * subject 流程标题

 * element_subject 公文元素标题
   
   特指在文单中显示的标题

 * state 流程状态
   
   0：运行中；2：撤销；3：正常结束

 * doc_mark 公文文号

 * serial_no 内部文号

 * send_to 主送单位

 * send_to_id 抄送单位ID
   
   与send_to对应出现，send_to存储单位名称，send_to_id存储类型及id，示例：Department|7659511175398779

 * copy_to 抄送单位

 * copy_to_id 抄送单位ID
   
   同send_to_id

 * templete_id 模板ID

 * org_department_id 部门ID

 * org_account_id 单位ID

 * current_nodes_info 当前待办人ID

 * edoc_type 公文类别
   
   0：发文；1：收文；2：签报

 * govdoc_type 公文类别（推荐使用）
   
   cap3新公文：1：发文；2：收文；3：签报；4：交换
   
   老企业公文：0

 * form_app_id 表单ID

 * form_recordid 表单动态表数据ID

 * newflow_type 流程类型
   
   0：主流程；1：子流程

 * body_type 正文类型
   
   10：HTML；41：OfficeWord；42：OfficeExcel；43：WpsWord；44：WpsExcel；45：PDF；46：OFD

## 公文主表扩展表 edoc_summary_extend

## 说明

 * 扩展存储公文元素对应字段

 * 关系：edoc_summary_extend.summary_id = edoc_summary.id，一条edoc_summary数据对应一条edoc_summary_extend数据

## 事项表 ctp_affair

## 说明

 * 流程中各事项数据
 * 关系：ctp_affair.object_id = edoc_summary.id，一条edoc_summary数据对应多条ctp_affair数据
 * 关系：ctp_affair.templete_id = ctp_template.id

## 字段

 * memberId 人员ID

 * sender_id 发起者ID

 * subject 流程标题

 * object_id 主体ID

 * state 状态
   
   1：待发；2：已发：3：待办；4：已办

 * sub_state 子状态
   
   0：正常；11：未读；12：已读

 * create_date 创建时间
   
   同一个流程对应的创建时间相同

 * receive_time 接收时间
   
   事项生成时间

 * complete_time 结束时间
   
   事项处理时间

 * body_type 正文类型
   
   同edoc_summary.body_type

 * node_policy 节点权限

 * activity_id 节点ID

 * form_app_id 表单ID

 * form_recordid 表单动态表数据ID

 * templete_id 模板ID

 * app 应用类型
   
   cap3新公文：4
   
   老企业公文（V7.1版本（包括）之后）：4
   
   老企业公文（V7.1版本（不包括）之前）：19：发文；20：收文；21：签报

 * sub_app 子应用类型
   
   cap3新公文：1：发文；2：收文；3：签报；4：交换
   
   老企业公文（V7.1版本（包括）之后）：19：发文；20：收文；21：签报

 * summary_state
   
   同edoc_summary.state

## 正文表 ctp_content_all

## 说明

 * cap3新公文存储使用
 * 关系：ctp_content_all.module_id = edoc_summary.id，一条edoc_summary对应2条或者3条ctp_content_all数据，做过wps转OFD或者word转pdf会生产3条数据，其他情况仅有2条
 * 关系：ctp_content_all.content = ctp_file.id

## 字段

 * module_type 模块类型
   
   4：公文业务数据；401：发文模板；402：收文模板；403：交换模板；404：签报模板

 * module_id 模块ID

 * content_type 正文类型
   
   10：HTML；20：表单正文；41：OfficeWord；42：OfficeExcel；43：WpsWord；44：WpsExcel；45：Pdf；46：Ofd

 * content 正文
   
   content_type是HTML正文，此字段存储HTML代码
   
   content_type是表单正文，此字段为空
   
   content_type是其他类型，此字段存储文件ID

## 正文表 edoc_body

## 说明

 * 老企业公文存储使用

 * 关系：edoc_body.edoc_id = edoc_summary.id 一条edoc_summary对应1条或者2条edoc_body数据，做过word转pdf会生产2条数据，其他情况仅有1条

 * 关系：edoc_body.content = ctp_file.id

## 字段

 * content_type 正文类型
   
   HTML；OfficeWord；OfficeExcel；WpsWord；WpsExcel；Pdf

 * content 正文
   
   content_type是HTML正文，此字段存储HTML代码
   
   content_type是其他类型，此字段存储文件ID

 * edoc_id 公文ID

## 意见表 ctp_comment_all

## 说明

 * cap3新公文存储使用
 * 关系：ctp_comment_all.module_id = edoc_summary.id，一条edoc_summary对应0条或多条ctp_comment_all数据
 * 关系：ctp_comment_all.affair_id = ctp_affair.id

## 字段

 * module_type 模块类型
   
   4：公文

 * module_id 模块ID

 * ctype 意见类型
   
   -1：附言；0：普通意见；1：回复意见

 * content 意见内容

 * affair_id 事项ID

 * create_id 创建人ID

 * create_date 创建时间

## 附件表 ctp_attachment

## 说明

 * 记录标题区、文单区、意见区附件以及关联文档
 * 关系：ctp_attachment.att_reference = edoc_summary.id

## 字段

 * att_reference 主体ID

 * sub_reference 子主体ID
   
   主体ID、子主体ID都对应edoc_summary.id，此数据属于标题区
   
   主体ID对应edoc_summary.id，子主体ID对应edoc_opinion.id，此数据属于文单区
   
   主体ID对应edoc_summary.id，子主题ID对应ctp_comment_all.id，此数据属于意见区

 * type 类型
   
   0：附件；2：关联文档

 * filename 名称
   
   附件名称或者关联文档流程标题

 * file_url 文件地址
   
   附件则对应ctp_file.id
   
   关联文档则对应其对象ID

 * mime_type 文件类别

 * attachment_size 附件大小
   
   单位：Byte

## 文件表 ctp_file

## 说明

 * 关系（cap3新公文正文）：ctp_file.id = ctp_content_all.content

 * 关系（老企业公文正文）：ctp_file.id = edoc_body.content

 * 关系（附件）：ctp_file.id = ctp_attachment.file_url

## 字段

 * filename 文件名称

 * mime_type 文件类型

 * file_size 文件大小
   
   单位：Byte

 * create_date 创建时间

 * update_date 更新时间
   
   cap3新公文正文、老企业公文：优先根据update_date在文件分区根据id找文件，找不到的情况下根据create_date查找
   
   附件：根据create_date在文件分区根据id找文件

## 意见表 edoc_opinion

## 说明

 * cap3新公文配置到文单中的公文处理意见会存储到此表，否则仅存储ctp_comment_all
 * 老企业公文意见都写入此表
 * 关系：edoc_opinion.edoc_id = edoc_summary.id
 * 关系：edoc_opinion.affair_id = ctp_affair.id

## 字段

 * edoc_id 公文ID

 * affair_id 事项ID

 * content 意见内容

 * policy 表单字段ID
   
   用于定位此意见显示在文单哪个意见框中

 * create_user_id 创建人ID

 * create_time 创建时间

 * node_id 节点ID

 * department_name 部门名称

 * account_name 单位名称

## 文号记录表 govdoc_mark_record

## 说明

 * 关系：govdoc_mark_record.summary_id = edoc_summary.id
 * 关系：govdoc_mark_record.mark_def_id = edoc_mark_definition.id

## 字段

 * summary_id 公文ID
 * mark_def_id 文号定义ID
 * markstr 文号字符串
 * word_no 机构代字
 * year_no 年份
 * mark_number 文号序号

## 文号使用表 edoc_mark

## 说明

 * 关系：edoc_mark.mark_definition_id = edoc_mark_definition.id
 * 关系：edoc_mark.edoc_id = edoc_summary.id

## 字段

 * mark_definition_id 文号定义ID

 * edoc_id 公文ID

 * doc_mark 文号字符串

 * doc_mark_no 文号序号

 * mark_type 文号类别
   
   0：公文文号；1：内部文号；2：签收编号

## 文号占用表 edoc_mark_history

## 说明

 * 关系：edoc_mark_history.mark_definition_id = edoc_mark_definition.id
 * 关系：edoc_mark_history.edoc_id = edoc_summary.id

## 字段

同edoc_mark

## 表单定义表 form_definition

## 说明

 * 关系：form_definition.id = edoc_summary.form_app_id

## 字段

 * field_info 字段属性信息
   
   Table标签name属性对应动态表明
   
   Field标签mappingField属性对应映射字段，正常情况下此属性不能重复
   
   Field标签name属性对应表单的字段
   
   
   
   

 * view_info 视图属性信息
   
   Form标签id属性对应视图ID
   
   Operation标签id属性对应操作ID
   
   视图信息可能存在多组
   
   

## 权限设置表 form_permission_config

## 说明

 * 文单定义中权限设置
   
   

 * 关系：form_permission_config.form_id = form_definition.id

## 字段

 * form_id 表单ID

 * config 初始化配置
   
   数据格式："节点ID":"视图ID.操作ID"
   
   节点ID对应ctp_node_permission.id
   
   视图ID、操作ID 见form_definition表介绍

 * show_content_config 修改后的配置
   
   同 config

## 文件分区表 ctp_partition

## 说明

 * 用于确认公文正文、附件存储位置

## 字段

 * path 文件路径

 * state 状态
   
   0：启用；1：停用

 * start_date 开始日期

 * end_date 结束日期


## 三、查找公文正文物理文件

## 查找文件分区

## 方式1

登录系统管理员，在系统分区管理列表中查看



## 方式2

使用sql直接查数据库

select path, state, start_date, end_date from ctp_partition;


## 查找文件

见ctp_file表介绍，确认用于定位的时间，根据文件分区开始日期与结束日期定位这个文件落在哪个路径，在路径中根据年月日定位文件夹，在文件夹中使用ctp_file.id搜索文件，与id完全匹配不带后缀的文件则是当前流程中显示的正文，带后缀的文件则是之前修改的备份文件

编撰人：admin


快速跳转



 * 公文概念和数据结构
   * 一、确认公文属于"cap3新公文"还是"老企业公文"
     * 方式1
     * 方式2
   * 二、表间关系
     * 说明
     * 公文主表 edoc_summary
       * 说明
       * 字段
     * 公文主表扩展表 edocsummaryextend
       * 说明
     * 事项表 ctp_affair
       * 说明
       * 字段
     * 正文表 ctpcontentall
       * 说明
       * 字段
     * 正文表 edoc_body
       * 说明
       * 字段
     * 意见表 ctpcommentall
       * 说明
       * 字段
     * 附件表 ctp_attachment
       * 说明
       * 字段
     * 文件表 ctp_file
       * 说明
       * 字段
     * 意见表 edoc_opinion
       * 说明
       * 字段
     * 文号记录表 govdocmarkrecord
       * 说明
       * 字段
     * 文号使用表 edoc_mark
       * 说明
       * 字段
     * 文号占用表 edocmarkhistory
       * 说明
       * 字段
     * 表单定义表 form_definition
       * 说明
       * 字段
     * 权限设置表 formpermissionconfig
       * 说明
       * 字段
     * 文件分区表 ctp_partition
       * 说明
       * 字段
   * 三、查找公文正文物理文件
     * 查找文件分区
       * 方式1
       * 方式2
     * 查找文件



分享链接分享链接

## 90. SDK+web service方式集成

> 原始路径：`/40/752/924.html`  
> 相对路径：`40/752/924.md`

## SDK+web service方式集成


## 确定栏目数据

栏目中的数据由首页应用来确定

需要提供的接口：

1、数据列表抽取接口，该接口用来获取栏目显示的数据；

2、数据总数统计接口，该接口用来显示栏目数据的总数（如果需求显示数据总数）。


## 栏目解析类开发

1.Package：com.seeyon.ctp.portal.section

2.解析类需要继承抽象类：com.seeyon.ctp.portal.section.BaseSectionImpl

3.Demo类示例

public class DemoSection extends BaseSectionImpl {

    @Override
    public String getId() {
        //栏目ID，必须与spring配置文件中的ID相同;如果是原栏目改造，请尽量保持与原栏目ID一致
        return "demoSection";
    }

    @Override
    public String getName(Map preference) {
        //栏目显示的名字，必须实现国际化，在栏目属性的“columnsName”中存储
        String name = preference.get("columnsName");
        if(Strings.isBlank(name)){
            return "demoSection";
        }else{
            return name;
        }
    }

    @Override
    public Integer getTotal(Map preference) {
        //栏目需要展现总数据条数时重写
        return null;
    }

    @Override
    public String getIcon() {
        // 栏目图标，暂不需要实现
        return null;
    }

    @Override
    public BaseSectionTemplete projection(Map preference) {
        //栏目解析主方法
        
        HtmlTemplete ht = new HtmlTemplete();
        StringBuilder html = new StringBuilder();
        html.append("
DemoSection");
        ht.setHeight("230");
        ht.setHtml(html.toString());
        ht.setModel(HtmlTemplete.ModelType.inner);
        ht.setShowBottomButton(true);
        ht.addBottomButton(BaseSectionTemplete.BOTTOM_BUTTON_LABEL_MORE, "javascript:alert('ok');");
        return ht;
    }
}



## 栏目解析类配置

1.编写好的栏目类需要在对应的插件Spring配置文件夹进行Spring注册配置。

2.约定栏目的Spring文件命名为spring-xxxx-section.xml xxxx为插件Id。

3.栏目属性对照表

属性名               值域                                                         描述
sectionType       common, //常用栏目 timeManagement, //时间管理 publicInformation,   栏目类型，空间选择栏目时栏目的分类由该属性决定
                  //公共信息 doc, //文档栏目 formbizconfigs, //表单栏目 forum, //扩展栏目
sectionCategory   plan                                                       栏目类型中的分类：常用、计划...
spaceTypes        Constants.SpaceType中枚举的类型                                  允许添加该栏目的空间类型
resourceBundle    示例：com.seeyon.v3x.main.resources.i18n.MainResources        国际化绑定来源，已废弃
properties        List                                                       栏目编辑属性

4.空间类型

/**
     * 空间类型，顺序不可改变
     */
    public static enum SpaceType {
        /**
         * 0 个性化个人空间
         */
        personal, //0
        
        /**
         * 部门空间
         */
        department, //1
        /**
         * 单位空间
         */
        corporation, //2
        /**
         * 集团空间
         */
        group, //3
        /**
         * 自定义团队空间
         */
        custom, //4
        
        //默认的空间
        /**
         * 默认个人空间
         */
        Default_personal, //5 
        //@Deprecated
        /**
         * 默认部门空间
         */
        Default_department, //6 
        
        @Deprecated
        Default_custom,  //7 
        /**
         * 第三方系统
         */
        thirdparty, //8 
        /**
         * 默认领导空间
         */
        default_leader,//9 
        /**
         * 个性化领导空间
         */
        leader,//10 
        /**
         * 关联系统
         */
        related_system,//11 
        /**
         * 关联项目
         */
        related_project,//12 
        /**
         * 自定义个人空间
         */
        Default_personal_custom,//13 
        /**
         * 默认外部人员空间
         */
        Default_out_personal,//14 
        /**
         * 个性化个人自定义空间
         */
        personal_custom,//15 
        /**
         * 个性化外部人员空间
         */
        outer,//16  
        /**
         * 自定义单位空间
         */
        public_custom,//17 
        /**
         * 自定义集团空间
         */
        public_custom_group,//18 
        //二级主页空间
        /**
         * 协同工作
         */
        cooperation_work,//19 协同工作
        /**
         * 目标管理
         */
        objective_manage,//20 目标管理
        /**
         * 公文管理
         */
        edoc_manage,//21 公文管理
        /**
         * 会议管理
         */
        meeting_manage,//22 会议管理
        /**
         * 协同驾驶舱
         */
        performance_analysis,//23 协同驾驶舱
        /**
         * 空间模板的默认空模板类型，不是空间类型，内部使用
         */
        template,//空间模板的默认空模板类型，不作为空间类型使用
        /**
         * 表单应用
         */
        form_application,//25 表单应用
        //end 
    }


5.Demo栏目配置示例

<bean id="demoSection" class="com.seeyon.ctp.portal.section.DemoSection" init-method="init">
    <property name="sectionType" value="common" />
    <property name="sortId" value="99" />
</bean>


6.栏目模板列表

模板类                                描述
CalendarFourColumnTemplete         日程事件的四列模板：标题 开始时间 结束时间 状态
ChessboardTemplete                 棋盘式 * 左边小图标(默认1616)+右边标题 * 上边大图标(默认3232)+下边标题 * 标题可以有浮动菜单
ChessMultiRowThreeColumnTemplete   棋盘式 、3列
HtmlTemplete                       直接输出HTML代码片断
MonthCalendarTemplate              月历式栏目
MoveMultiRowThreeColumnTemplete    多行3列滚动式
MultiIconCategoryItem              多行的，图标，分类，文本的展现形式
                                   * 图表是32px * 32px的，在左边，右边的上面是分类(Category),下面是若干个项
MultiRowFourColumnTemplete         多行3列模板，依次是：subject createDate createMemberName category
MultiRowThreeColumnTemplete        多行3列模板，依次是：subject createDate category
MultiRowVariableColumnTemplete     成倍行,不定列 模板 * 适用于　三或四列标准列表模板满足不了需要的情况下* 可以自定义列数、宽度、单元格样式、链接地址
MultiSubjectSummary                多行的，显示标题和摘要，常用新闻、公告
OneImageAndListTemplete            图片加列表模板 * 第一列为图片居左 右边为标题加摘要 * 下面为列表 * 列表内容为 * 标题 发起时间 所属板块 *
                                   列表参数可配置
OneItemUseTwoRowTemplete           两行展现一项 模板 * 适用于　如集团空间调查栏目 * 第１行　标题，另起一行　发布时间和类型
OnePictureTemplete                 图片滚动式
OneSummaryAndMultiList             显示模式：一条显示为“标题+时间+(类别)+摘要”，下面是若干行列表
PictureTemplete                    图片基础模板
PictureTitleAndBriefTemplete       标题加摘要的新闻模板

编撰人：lichaoj


快速跳转



 * SDK+web service方式集成
   * 确定栏目数据
   * 栏目解析类开发
   * 栏目解析类配置



分享链接分享链接

## 91. 当前已登录了一个用户，同一窗口中不能登录多个用户

> 原始路径：`/40/752/1001.html`  
> 相对路径：`40/752/1001.md`

## 当前已登录了一个用户，同一窗口中不能登录多个用户


## 需求

登录系统的用户不点击系统内的注销按钮，重新访问系统会提示：当前已登录了一个用户，同一窗口中不能登录多个用户。

用户期望当前还处于登录状态的用户，不要给出上方提示，而是自动进入个人首页。




## 解决方案

产品对登录页做了拦截导致的问题，访问【域名/seeyon/】、【域名/seeyon/main.do】、【域名/seeyon/main.do?method=index】都会有此提示。反而直接访问【域名/seeyon/main.do?method=main】就能进入个人空间。

基于此思路，可定制开发修改重定向代码：apps-common工程的com.seeyon.ctp.login.controller.MainController中的index方法，里面可以判断已经登录过，如果登录过就跳转到main.do?method=main即可。

编撰人：admin




快速跳转



 * 当前已登录了一个用户，同一窗口中不能登录多个用户
   * 需求
   * 解决方案



分享链接分享链接

## 92. 实现PC登录页扫描登录功能如何实现

> 原始路径：`/40/752/1008.html`  
> 相对路径：`40/752/1008.md`

## 实现PC登录页扫描登录功能如何实现


## 参照版本

V8.2SP1


## 需求

项目上需要复用PC登录页的“微信/M3扫码登录”功能，期望把二维码放在客户第三方系统页面展示，供大家扫描登录OA。需要知道这个二维码生成接口及实现。




## 标准实现分析

要进行定制开发，必须了解免登录的实现原理：


## 生成二维码

前端开发，通过F12查找二维码元素，看到这是一个canvas，基于html5渲染。这里看应该是前端js进行的渲染，可以找特征值id="qrcode1"，一般都是通过dom操作渲染。



全局搜索qrcode1关键字，可以找到渲染二维码的代码位置：



总结：渲染二维码逻辑为前端显示：

// 一、引入JQuery组件及jquery.qrcode.js（使用别的QR渲染组件也可以）
// 二、实现如下前端代码，随后Jquery("#qrcode1 .qrcode")这个Dom下就有二维码了
var date = new Date();
var dateNumber = date.getTime();

// 记住这个random，这是关键变量
var random="seeyon-" + Math.uuid() + "-" + dateNumber;
var qrcodeRandom = "https://weixin.seeyon.com/mobilehelp.jsp?random=" + random;
$("#random").val(random);

//canvas方式进行图片渲染
$("#qrcode1 .qrcode").empty();
$("#qrcode1 .qrcode").qrcode({
	render: isIE8?"table":"canvas", //canvas方式
	width: adjustWidth, //宽度
	height: adjustHeight, //高度
	text: utf16to8(qrcodeRandom) //任意内容
});

// 记住这行代码：每隔1秒向服务器确认是否免登录
setInterval("intervalLogin()", 1000);



## 扫码记录免登

M3或企业微信扫描二维码，能读取到二维码中的random信息，这个random是当前用户很重要的记录信息。

随后M3或企业微信调用OA的免登录接口，记录当前用户进行了免登录：

 * LoginResource#loginForWechat(random) 企业微信免登
 * LoginResource#loginForM3(random) M3免登


## PC自动登录

上一步是M3通知OA服务器：用户进行了免登，OA服务器记录了免登状态。但此时PC二维码界面是不知道用户免登的，需要有一个动作确认是否有免登状态，如果确认OK，则自动登录，这块实现逻辑就在前端的intervalLogin()方法里：

// 前面二维码渲染处进行了每隔1秒轮询判定是否免登的实现
setInterval("intervalLogin()", 1000);

//轮询请求，防止后台阻塞
function intervalLogin(){
	if(sendFlag){
		sendFlag = false;
		loginForWechat();
	}
}

// 真正的轮询方法
function loginForWechat(){
	// 从页面获取random信息
	var random = $("#random").val();
    $.ajax({
        async : true,
        type: "GET",
        url: _ctxPath+"/main.do?method=login4QrCode&random=" + random,  //这个请求的意思是判断当前是否进行了免登录操作，如果没有则返回loginError字符串，如果有则返免登录的人员loginName登录名
        dataType : 'text',
        success : function(data) {
            if(data != "loginError" || data == null){
				// 如果确认进行了免登录，则模拟登录按钮直接登录
                $("#login_username").val(data);
				// 这个执行的button上面的点击事件，实际触发的是onclick方法，具体可自行查看前端代码
                $("#login_button").click();
            } else {
                sendFlag = true;
            }
        },
        error : function(XMLHttpRequest, textStatus, errorThrown) {
            alert($.i18n('login.tip.failure'));
        }
    });
}


依据源码分析，在判定免登录成功后会执行$("#login_button").click();方法，根据方法溯源，可以看到调用链：

$("#login_button").click();
↓
loginButtonOnClickHandler()；
↓
doLoginSubmit()
↓
$("#submit_button").click();
↓
<form method="post" action="${path}/main.do?method=login" id="login_form" name="loginform">
	<input id="submit_button" type="submit" style="display: none" value="" />
</form>
↓
MainController#login();
↓
QrCodeLoginAuthentication#authenticate(); //免登录认证器



## 实现原理小结

基于以上分析，扫描的完整逻辑为：

1、在PC登录页渲染显示出免登录二维码

2、M3、企业微信APP扫描二维码后，在APP端远程调用OA服务器通知该用户进行了免登录

3、在PC登录页每隔1秒询问OA：用户是否进行了免登录。如果OA服务器返回免登录动作，则PC执行form提交操作登录。


## 第三方页面定制开发解决方案

1、复制一份seeyon\main\login\default\login.jsp登录页的实现源码，把所有能看到的元素全部隐藏起来，只渲染一个二维码，让人感觉这个页面就一个二维码：

 * 将背景色、背景图全部干掉
 * 将input、button等能看到的Dom元素全部隐藏起来，不要删除
 * 将form标签增加target=_blank属性，表示打开新窗口
 * 实现免登录二维码渲染操作，保障能看到二维码

-- 增加target="_blank"属性
<form method="post" action="${path}/main.do?method=login" id="login_form" name="loginform" target="_blank">
	<input id="submit_button" type="submit" style="display: none" value="" />
</form>


2、第三方页面Iframe的形式访问复制的那份JSP页面，此时第三方页面就只能看到二维码了

3、随后用M3或企业微信扫描二维码，按照原来的业务逻辑会执行submit提交操作，登录打开OA页面

注1：为什么要拷贝一份login.jsp而不是新建一个空白html页面，只引入二维码？

答：因为自动跳转使用了login.jsp里面的很多业务逻辑，包括dom的操作，当然如果你技术能力强，也可以自己实现免登录

编撰人：het




快速跳转



 * 实现PC登录页扫描登录功能如何实现
   * 参照版本
   * 需求
   * 标准实现分析
     * 生成二维码
     * 扫码记录免登
     * PC自动登录
     * 实现原理小结
   * 第三方页面定制开发解决方案



分享链接分享链接

## 93. 登录验证码清晰度调整

> 原始路径：`/40/752/1905.html`  
> 相对路径：`40/752/1905.md`

## 登录验证码清晰度调整


## 背景&需求

所有用户登录界面验证码显示太模糊，混淆太严重，期望调整到可以查看准确验证码信息：




## 解决方案

定制开发，修改验证码源码apps-common\src\main\java\com\seeyon\ctp\login\VerifyCodeImageServlet.java，调低干扰线的值：

	// 代码修改点：VerifyCodeImageServlet#drawInterfere
	private void drawInterfere(Graphics2D g,ThreadLocalRandom random,String type) {
		// 修改点start：干扰线个数，可以将count值调低，比如设置为 = 3
		int count=3;
		// 修改点end：干扰线个数，可以将count值调低，比如设置为 = 3
		
		其它若干代码......
	}


编撰人：het


快速跳转



 * 登录验证码清晰度调整
   * 背景&需求
   * 解决方案



分享链接分享链接

## 94. Android端M3升级TargetSDK Version 30的修改点和修改方法

> 原始路径：`/40/1002/1004.html`  
> 相对路径：`40/1002/1004.md`

## Android端M3升级TargetSDK Version 30的修改点和修改方法


## 影响

影响范围：影响所有对M3 Android端进行了定制开发并上架到小米、华为等应用商店的项目。

影响后果：如果未按要求进行SDK升级，将导致2024年1月定制开发的APP被小米、华为从应用商店下架。

所有IOS APP不受影响。

处理思路：修改APP的源码，将Android SDK升级到30或以上，同步修改升级后的影响点，确保升级后功能可用。


## 快速解决方案

Android SDK30适配代码已上架应用商城，完整代码已推送客开代码平台，有升级SDK需求的项目请通过标准流程从客开总部申请最新的源代码，参考修改记录做合并。

> M3 Android SDK30适配稳定版本：M3 4.5.9及更高版本


## 背景

接到华为和小米官方平台最新通知：因工信部要求和安全等相关问题，要求线上 APP 必须升级 Android 底层代码 Android Traget SDK Version 到 30 以上。并且华为要求必须在 2024年1月31日前完成，否则将下架 APP（后续其余平台可能也会跟进）。

依此规定，所有涉及上架到小米、华为应用商城的APP，都需要按照规范升级到Android Traget SDK Version 30或以上。致远M3 APP也同样需要遵守此规则，包括所有针对M3 Android进行了定制开发的项目（只影响上架应用商店的APP，不影响私有化）。


## 依据

工信部通知参见：关于侵害用户权益行为的APP（SDK）通报

华为应用商店通知如下：



小米应用商店通知如下：




## 修改点

如下是在M3 Android 4.5.5版本基础上整理的修改点，请参考进行升级：


## 0. 修改targetSdkVersion号码为30

如下图，在android studio中全局搜索，找到对应配置文件，将后面的号码改为30




## 1.外勤签到语音无法保存

问题原因： 1.录制音频保存文件的时候需要访问手机存储 2.targetsdk30后强制执行分区存储，所以老的调用方法不能直接运行，需要申请管理所有文件的权限才行

修改方法： M3\src\main\java\org\apache\cordova\media\AudioPlayer.java文件中添加申请管理全部文件的权限，具体如下



运行效果： 在加上以上代码之后，在android11及以上机器运行，点击录制签到语音的时候，就会跳转到设置页面，需要用户手动点击授权给m3对应权限，授权后返回m3，即可正常使用


## 2.活动推送分享图片保存文件失败

问题原因：

1.重要消息分享的时候会先保存一张图片文件到本地，再进行分享 2.targetsdk30后强制执行分区存储，所以老的调用方法不能直接运行，需要把文件保存地址改为应用内部地址才能正常保存

修改方法： M3\src\main\java\com\seeyon\cmp\ui\fragment\ImportantMsgFragment.kt文件中修改文件的保存位置为内部路径，代码如下



运行效果： 在加上以上代码之后，在android11及以上机器运行，点击分享重要消息，就不会报错了


## 3.wpspro打开文件无权限失败

问题原因： 1.wpspro打开文件的时候，会读取文件，再进行打开，该处也需要文件管理权限 2.targetsdk30后强制执行分区存储，所以老的调用方法不能直接运行，需要申请新的文件管理权限才能正常访问

修改方法： M3\src\main\java\com\seeyon\cmp\plugins\attachment\AttachmentPlugin.java文件中添加权限申请代码，代码如下



运行效果： 在加上以上代码之后，在android11及以上机器运行，使用wpspro打开文件，就不会报错了


## 4.聊天选文件发送的时候过滤掉了.word等文件

问题原因： 1.targetsdk30后强制执行分区存储，所以老的调用方法不能访问全部的手机文件，需要申请新的文件管理权限才能正常访问 修改方法： M3\src\main\java\com\seeyon\cmp\plugins\file\ui\FileSelectActivity.java文件中添加权限申请代码，代码如下



运行效果： 在加上以上代码之后，在android11及以上机器运行，聊天中选择手机文件，就包含了全部的文件


## 5.Kotlin语法错误

问题原因： 1.修改到targetsdk30后kotlin语法发生了变化，主要集中在变量的赋值和空判断方面

修改方法： 根据ide的提示进行语法修改即可，无需特殊处理，对于类似常量赋值的问题，可以使用对应的set方法进行处理，例如



运行效果： 在修改完成kotlin语法错误后，即可正常编译


## 6.鸿蒙3.0文件系统适配

问题原因： 1.修改到targetsdk30后由于鸿蒙3.0系统基于的是sdk29，会导致选择文件白屏等问题的出现

修改方法： 由于鸿蒙3对应的是sdk29，所以需要添加特殊的标记来实现对文件访问的向下兼容，具体代码如下： M3\src\main\AndroidManifest.xml



运行效果： 添加完该配置后，在鸿蒙3上就可以正常的访问文件系统了


## 7.致信语音需要点进聊天详情才会自动弹出

问题原因： 1.由于致信代码初始化的顺序问题，每次语音通话需要点进过具体聊天页面才能弹出对应页面

修改方法： 提前初始化致信代码，就可以在没有点进具体的对话的情况下弹出语音通话的界面，具体代码如下： M3\src\main\java\com\seeyon\cmp\manager\bg\CMPBackgroundRequestsManager.java



运行效果： 添加完该配置后，在使用m3的过程中有语音通话就能自动弹出对应页面了


## 8.Android8.0透明主题冲突

问题原因： 1.升级到targetsdk30之后原有的设置透明主题方式与旋转屏幕方法在Android8.0上有冲突会导致应用闪退

修改方法： 1.对于透明activity做了转换拦截



2.针对于强制需要横竖屏切换的页面，修改了透明属性

运行效果： 在Android8.0版本无闪退情况， 几个关键页面能正常横竖屏切换

修改完成后，透明主题与旋转屏幕在android8.0上不再会导致闪退的情况出现


## 9.融云聊天中点击位置，弹出页面无法定位

问题原因： 1.高德老的api在Android13设备无法正常返回 修改方法： 1.换用新的方式定位





运行效果：Android13设备正常定位成功， 后续逻辑正常

编撰人：het、admin


快速跳转



 * Android端M3升级TargetSDK Version 30的修改点和修改方法
   * 影响
   * 快速解决方案
   * 背景
   * 依据
   * 修改点
     * 0. 修改targetSdkVersion号码为30
     * 1.外勤签到语音无法保存
     * 2.活动推送分享图片保存文件失败
     * 3.wpspro打开文件无权限失败
     * 4.聊天选文件发送的时候过滤掉了.word等文件
     * 5.Kotlin语法错误
     * 6.鸿蒙3.0文件系统适配
     * 7.致信语音需要点进聊天详情才会自动弹出
     * 8.Android8.0透明主题冲突
     * 9.融云聊天中点击位置，弹出页面无法定位



分享链接分享链接

## 95. iOS M3常见安全问题处理方案

> 原始路径：`/40/1002/1006.html`  
> 相对路径：`40/1002/1006.md`

## iOS M3常见安全问题处理方案


## 适用人群

所有用户。

用户对M3进行了安全扫描，针对安全扫描后的对应问题应对处理方案做下陈述：


## 包含不仅限于下表内容

序列号   设备    安全问题                      安全风险问题描述                                                                                               风险等级   第三方评估详情   第三方修复建议                                                                                                             修复状态   研发回复                                                        影响版本
1     iOS   InnerHTML 的 XSS 攻击风险      该应用存在 InnerHTML 的 XSS 攻击风险                                                                             高      高         建议开发者使用函数封装                                                                                                         无需改动   检测到的仅为显示页面，不涉及操作和敏感信息                                       所有
2     iOS   是否存在注入攻击风险                在iOS越狱环境下，越狱插件通过DYLD_INSERT_LIBRARIES环境变量注入dylib动态库，从而执行恶意代码或插件，HOOK应用程序关键函数，打乱程序执行流程，危害程序信息安全。        高      高         建议客户端对dylib注入进行检测                                                                                                   无需改动   暂不支持，苹果系统安全性较高                                              所有
3     iOS   是否存在篡改和二次签名打包的风险          应用被篡改后二次打包不仅损害开发者的利益，而且也使APP用户遭受到不法应用的恶意侵害。                                                            高      高         建议开发者校验 embedded.mobileprovision 文件中的 teamID 是 否是应用的                                                                无需改动   线上app对二次签名有加固处理，改变包名不可使用                                    所有
                                                                                                                                                              teamID，或者判断 BundleID 是否被修改
4     iOS   反dylib注入                  在iOS越狱环境下，越狱插件通过DYLD_INSERT_LIBRARIES环境变量注入dylib动态库，从而执行恶意代码或插件，HOOK应用程序关键函数，打乱程序执行流程，危害程序信息安全。        高      高         建议客户端对dylib注入进行检测                                                                                                   无需改动   暂不支持，苹果系统安全性较高，可客开开发，也可提产品需求；                               所有
5     iOS   客户端未设置证书校验                客户端未设置证书校验                                                                                             中      中         建议客户端设置证书校验                                                                                                         无需改动   暂不支持，苹果系统安全性较高，可客开开发，也可提产品需求；                               所有
6     iOS   是否存在格式化字符串漏洞                                                                                                                     中      中         发现存在格式化字符串漏洞 fprintf fscanf printf sprintf sscanf vsprintf                                                          无需改动   使用到的函数是苹果官方支持的方式，无需去做封装处理                                   所有
7     iOS   是否存在创建可执行权限内存风险           通过 mprotect 函数，可以修改内存空间的读写属性，使内存空间 具备可读可写可执行权限。                                                        中      中         建议开发者不要使用 mprotect 函数修改内存空间读取权限。                                                                                    无需改动   检测到的mprotect函数，未使用来对内存空间读取权限                                所有
8     iOS   输入记录保护                    iOS中安装了键盘记录程序（可以在非越狱状态运行），则使用系统键盘输入的内容易被键盘记录程序记录，导致内容泄露                                                中      中         使用自定义软键盘。参考https://github.com/ibireme/YYKeyboardManager                                                                    需要客开添加                                                      所有
9     iOS   屏幕录像保护                    和输入记录类似，恶意程序可以对用户输入的敏感信息（主要是密码）进行窃听。                                                                   中      中         重写输入框避免字符变化。                                                                                                        无需改动   目前M3中密码框的录屏操作会被苹果自动屏蔽，也就是显示空白；另，M3可提示用户截屏操作，并上传截屏记录。        所有
10    iOS   软键盘随机化排布                  在使用自定义软键盘进行敏感信息输入的情况下，有可能被恶意软件进行屏幕点击位置劫持，获取对应的点击位置，得到其输入内容                                             中      中         每次调用键盘时候，需要对键盘进行随机化排布（通常是利用数组表示键排布，则需要对数组进行随机打乱）。                                                                          需要客开添加                                                      所有
11    iOS   在敏感数据输入时是否使用不安全的系统键盘      系统会启动输入法的自动更正提示，在用户输入过程中利用缓存的 输入记录来更正用户的输入，而这些输入记录都是明文存储在本地                                            中      中         在敏感数据输入时使用专业的安全键盘，可以有效防止输入敏感内 容时被监听。                                                                                       需要客开添加                                                      所有
                                      缓存文件中，可被导出查看；系统键盘可被录屏并进行输入还原。
12    iOS   代码混淆                      检测 iOS 应用的源代码是否经过混淆处理。                                                                                 中      中         1．使用静态检测引擎对 IPA                                                                                                     无需改动   一、苹果安全机制本就很高，逆向难度很大二、代码混淆会影响上架苹果审核                          所有
                                                                                                                                                              文件进行解压缩。2．对解压缩后的文件进行分析，提取相关函数信息3．检查函数名称是否被混淆为无意义的名称，发现存在未混淆的函数名。
13    iOS   弱哈希算法使用漏洞                 弱 HASH 算法指安全级别低的 HASH 算法，包括 SHA1 和 MD5。                                                                低      低         开发者自查应用开发中勿使用 CC_SHA1 的方式进行数据哈希，推荐使用 CC_SHA256 算法进行数据哈希操作                                                           无需改动   m3中使用到的hash目前主要为md5、sha1，针对此类使用，目前不会存在安全问题。版本目部分使用SM国密算法。   所有
14    iOS   越狱设备运行风险                  程序中使用弱 HASH 算法时，HASH 算法可能被黑客攻击导致                                                                       低      低         越狱指充分开放 iOS                                                                                                         无需改动   M3对app有越狱检测，并会弹框提醒                                          所有
                                                                                                                                                              系统的用户操作权限，将用户对系统的操作权限由越狱前的读提到读写，可以任意擦写系统任意区域的运行状态。
15    iOS   动态库文件信息是否可被读取             HASH 校验方法失效。HASH 校验方法失效可能造成客户端隐私数                                                                      低      低                                                                                                                             无需改动   检测到的库均为苹果系统库，本就支持调用                                         所有
16    iOS   是否存在日志数据泄露风险。             据泄露、文件被篡改、传输数据被获取等后果，导致用户敏感信息                                                                          低      低         调试信息函数 NSLog 和 printf 可能输出重要的调试信息，其中包含                                                                              无需改动   线上版本无日志输出，已屏蔽                                               所有
                                                                                                                                                              的信息可能导致用户信息泄露，泄露核心代码逻辑等，为发起攻击提供便利
17    iOS   是否使用 URL Schemes。         被窃取。                                                                                                   低      低         如果 URL Scheme 只是启动打开应用，没有传输信息或操作应用内的逻辑可以忽略本检测项。                                                                     无需改动   APP中使用到的地方是加参数打开对应的页面                                       所有
18    iOS   是否存在外部函数显式调用风险。           攻击者可以通过静态分析程序中的外部函数调用关系，获取和跟踪 程序逻辑，然后对外部函数调用进行 HOOK                                                    低      低         建议通过定义函数指针，并通过函数指针的方式调用函数，从而消 除函数间的调用关系。                                                                            无需改动   检测到的函数调用是苹果支持或者推荐的方式                                        所有
                                      拦截、篡改业务逻辑等
19    iOS   出口合规证明信息是否正确              上架需要勾选加密选项                                                                                             低      低                                                                                                                             无需改动   M3上架无需出口合规证明信息                                              所有
20    iOS   是否存在系统调用暴露风险。             iOS系统提供了大量的共享库供开发者使用应用程序使用了这些封装的库函数，编译后很容易通过反编译工具找到函数内的调用关系，攻击者可以通过分析函数的调用关系，来获取核心业务逻辑，对关键系统函数进行HOOK   低      低         建议开发者在代码中封装关键系统函数，不调用外部的系统函数。                                                                                       无需改动   检测到的函数调用是苹果支持或者推荐的方式                                        所有
                                      拦截，导致信息泄漏等
21    iOS   xml文件中是否存在敏感信息                                                                                                                   低      低                                                                                                                             无需改动   检测到的xml仅为错误显示页面中的key                                        所有
22    iOS   js文件中是否存在敏感信息                                                                                                                    低      低                                                                                                                             无需改动   检测到的仅为key，不包含敏感信息的值                                         所有
23    iOS   是否存在超大的自定义函数。             过于庞大的接口函数，不仅不便于维护，而且容易产生可被攻击者利用的安全漏洞，严重影响程序本身的安全。                                                      低      低         建议开发者避免编写超大函数                                                                                                       无需改动   存在，无需修改，对业务执行没有影响                                           所有
24    iOS   是否存在缓冲区溢出漏洞               缓冲区溢出指系统对接收的输入数据长度没有进行有效检测，向缓 冲区内填充数据超过了缓冲区本身的容量，导致数据溢出到被分配                                            低      低         建议开发者自查，使用苹果推荐的替代函数，如strlcpy、strlcat。iOS                                                                            无需改动   以上函数只存在与部分三方库文件，目前长期稳定使用，未发现问题                              所有
                                      空间之外的内存空间，使得溢出的数据覆盖了其他内存空间的数据。                                                                                          底层框架也会使用存在缓冲区溢出漏洞的API，请根据实际情况修复
25    iOS   中是否调用 malloc 方法                                                                                                                  低      低                                                                                                                             无需改动   malloc存在少量的使用，并对使用后及时释放                                     所有
26    iOS   是否存在 Web Storage 数据泄露风险                                                                                                          低      低                                                                                                                             无需改动   需要使用，存敏感数据会加密处理                                             所有
27    iOS   二进制程序保护                   编译好的可执行文件可以容易地被Hopper或者IDA这类软件反编译。在没有进行函数名和逻辑混淆的时候，则容易被反汇编得到关键逻辑进而进行破解                                 低      低         利用iOS ClassGuard可以进行类名混淆，利用LLVM-obfuscator进行相关的逻辑混淆                                                                 无需改动   苹果审核机制是不允许代码混淆的，如被发现有被拒风险。标准产品无需做代码混淆。                      所有
28    iOS   认证失败锁定                    测试账户在登陆时候多次输入密码错误或修改密码时候多次错误是否会导致账号被锁定。                                                                低      低         后台中，通过维护一张currentErrorMap（线性安全），使用用户名作为key，使用错误次数作为value；并且重写其add方法，检测其错误次数，如果错误次数达到阈值，则写入1到数据库中isLocked字段中，禁止登陆。   无需改动   pc管理端可以设置出现错误次数后锁定                                          所有
29    iOS   界面切换保护                    当用户在登录界面写入账号密码之后，若界面切换时候未能清除用户输入的密码，则可能导致手机丢失后被直接使用已输入的信息进行登录。                                         低      低         加入清除密码的相关代码                                                                                                         无需改动   需要客开添加；另，退到后台有界面模糊功能                                        所有
30    iOS   通信协议安全                    APP使用HTTP协议进行通信过程中可能会遭受中间人攻击，威胁数据安全。                                                                   低      低         使用HTTPS协议进行通信                                                                                                       无需改动   建议使用https传输数据                                               所有
31    iOS   手机网络环境切换后未进行风险提示          网络环境切换后，客户端未进行风险提示                                                                                     低      低         建议对网络切换进行风险提示                                                                                                       无需改动   暂不支持，苹果系统安全性较高，可客开开发，也可提产品需求；                               所有
32    iOS   键盘记录保护                    自定义软键盘的键位需要随机、无按键阴影，以防止攻击者通过记录屏幕触点或截图，进行键盘记录                                                           低      低         建议客户端使用自定义软键盘                                                                                                              需要客开添加                                                      所有

编撰人：admin


快速跳转



 * iOS M3常见安全问题处理方案
   * 适用人群
   * 包含不仅限于下表内容



分享链接分享链接

## 96. 移动端协同修改正文实现多人在线编辑

> 原始路径：`/40/1002/1127.html`  
> 相对路径：`40/1002/1127.md`

## 移动端协同修改正文实现多人在线编辑


## 需求

客户购买了金山文档中台服务，可以实现在线预览和在线编辑。而自由协同如果是Word正文，后续节点修改正文时（PC端）支持多人同时在线编辑。但是移动端不支持，期望移动端在修改正文时也能多人在线编辑。


## 问题原因

移动端点击修改正文的时候会对修改正文操作进行加锁，多人编辑的时候后续的请求判断当前请求被加了锁后就会弹出提示。


## 修改方案

移动端点击修改正文按钮的时候，移除加锁逻辑。修改的代码块见下图：



编撰人：het




快速跳转



 * 移动端协同修改正文实现多人在线编辑
   * 需求
   * 问题原因
   * 修改方案



分享链接分享链接

## 97. M3唤起三方APP或被唤起开发方案

> 原始路径：`/40/1002/1218.html`  
> 相对路径：`40/1002/1218.md`

## M3唤起三方APP或被唤起开发方案


## 需求

关于APP相互唤起的场景分两种，不同客户有不同的需求 第一种：M3 APP唤起第三方APP，如唤起xx银行APP 第二种：第三方APP唤起M3，如客户的统一办公APP点击某个按钮唤起M3

以上不同场景如果出现无法唤起问题，需要针对问题做开发调试、甚至添加代码定制开发。


## 开发方案


## 第一种：M3唤起三方APP

## Android修改点

Android客户端，只需要找到M3源码文件：org.apache.cordova.CordovaWebViewImpl#interceptPay针对如下图所示位置进行定制开发适配即可：

定制开发工程师，可以在此处打断点调试，确认三方APP的URL请求协议是什么，做下相应适配：



## IOS修改点

Xcode打开IOS M3源码:

 1. 左侧文件列表找到M3-Info.plist，在文件中找到key：Queried URL Schemes，展开查看是否包含第三方本地程序的url Schemes，如没有，则添加三方url Schemes即可：



 2. 左侧文件列表找到config.xml，在文件中找到keyallow-navigation下是否包含第三方url scheme，没有则参考格式添加即可：

<allow-navigation href="weixin:*" />




3）左侧文件列表搜索CMPBannerWebViewController+InterceptRequest.m，找到方法- (BOOL)customShouldOverrideLoadWithRequest:(NSURLRequest*)request navigationType:(WKNavigationType)navigationType

如果三方APP的url scheme比较特殊，不在代码适配范围内导致return YES了，则需要定制开发：添加判断如果是跳转的特定url scheme，则返回NO。

- (BOOL)customShouldOverrideLoadWithRequest:(NSURLRequest*)request navigationType:(WKNavigationType)navigationType
  {
    //原逻辑。。。
    //添加代码
    NSURL *url = request.URL;
    if([url.scheme isEqualToString:@"目标scheme"]) {
        BOOL bSucc = [[UIApplication sharedApplication] openURL:url];
        if (!bSucc) {
            // 可提示未安装目标应用
        }
        return NO;
    }
    //此处前面添加上述代码
    return YES;
  }




 4. 如果是最新版本（2024年1月发布）的IOS M3源码，则这一步不需要，如果是2023年获更早时期的代码，则需要做本步：

左侧文件列表搜索CMPCommonWebViewController.m,找到方法- (void)webView:(WKWebView *)webView decidePolicyForNavigationAction:(WKNavigationAction *)navigationAction decisionHandler:(void (^)(WKNavigationActionPolicy))decisionHandler 方法内查找是否有如下代码，没有则在最后的返回前面添加如下代码

- (void)webView:(WKWebView *)webView decidePolicyForNavigationAction:(WKNavigationAction *)navigationAction decisionHandler:(void (^)(WKNavigationActionPolicy))decisionHandler{
  //原逻辑。。。
  //添加代码
  if (![url.scheme.lowercaseString hasPrefix:@"http"]){//其他scheme
      if ([[UIApplication sharedApplication] canOpenURL:url]) {
          [[UIApplication sharedApplication] openURL:url options:@{} completionHandler:nil];
          decisionHandler(WKNavigationActionPolicyCancel);
          return;
      }
  }
  //此处前面添加上述代码
  decisionHandler(WKNavigationActionPolicyAllow)
  }





## 第二种：三方APP唤起M3

## Android修改点

## M3 URL Scheme信息

三方应用打开M3定义的打开app url为seeyon://m3, 调用者可以根据自己的业务逻辑完成登录认证，M3定义有标准穿透参数，如果三方平台按照M3定义的标准参数唤起，M3客户端将会对参数处理，按照下文（参数说明）进行一些特殊范式的登录（如：用户名/密码方式），如果按照其余的格式传递，M3将不会对参数处理，会直接封装后发送给后台登录认证接口。

Android的url scheme:按照url方式跳转url固定为 seeyon://m3， 带参数的跳转方式：seeyon://m3?loginParams=XXXXXXX

loginParams参数:调用登录方法所需要的参数为json格式(注意loginParams里面的值必须经过URLEncoder的方式转码)，例如：

{
	"name": "test1",
	"password": "tpassword",
	"ticket": "xxxxticket",
	"ext":"扩张参数"
}


如果传递了name和password，M3将使用name为登录名称，password为密码，进行标准功能的登录。 如果传递了ticket，M3将按照A8标准的三方认证类SSOTicketLoginAuthentication.java类进行单点登录。 如果不传，M3客户端将会把整过loginParams以参数的形式传递给M3的登录接口，需要开发者按照A8登录集成功能进行集成（见示例3,服务器单点登录参考示例）。

自定义格式场景：如果调用者需要自定义参数，url scheme可以带自定义参数的跳转方式：seeyon://m3?key1=XXXXXXX&key2=XXXX&key3=XXXX， M3会将把所有的参数封装为一个json对象，以key为loginParams传递给后台登录接口。

## 三方唤起M3示例

本地程序调用方式：

方式一：

String params=”{
    "name": "test1",
    "password": "tpassword",
    "ticket": "xxxxticket",
    "ext": "扩张参数"
}”;
params =URLEncoder.encode(params,"utf-8");
String url = "seeyon://m3?loginParams="+params; 
Intent in = new Intent(Intent.ACTION_VIEW, Uri.parse(url));
in.addFlags(Intent.FLAG_ACTIVITY_NEW_TASK);
startActivity(in);


方式二：

String params=”{
    "name": "test1",
    "password": "tpassword",
    "ticket": "xxxxticket",
    "ext": "扩张参数"
}”;
params =URLEncoder.encode(params,"utf-8");
Intent in=new Intent("com.seeyon.cmp");
in.putExtra("loginParams", params");
startActivity(in);


Web页面调用方式：

String params=”{
    "name": "test1",
    "password": "tpassword",
    "ticket": "xxxxticket",
    "ext": "扩张参数"
}”;
params =URLEncoder.encode(params,"utf-8");

<a href="seeyon://m3?loginParams="+params>打开M3</a>


如果依然无法唤起，确保M3 APP是最新版本。随后再基于最新版本M3源码中进行代码检查，找到AndroidManifest文件，确保参数 android:scheme="seeyon" 无误：



## IOS修改点

第三方APP客户端唤起M3，则需要在三方源码中添加唤起代码，代码格式如下：

NSString *urlStr = @"seeyonM3Phone://m3?loginParams={ \"name\": \"zlcs1\", \"password\": \"123456\", \"ticket\": \"ticket\", \"serverUrl\": \" http://192.168.10.236:8085\", \"ext\":\"extent\" }";
NSURL *url = [NSURL URLWithString:[urlStr stringByAddingPercentEscapesUsingEncoding:NSUTF8StringEncoding]];
[[UIApplication sharedApplication] openURL:url];


如果是三方Web页面唤起M3，则可以参考如下源码：

var params = "{" +
    "\"name\": \"test1\"," +
    "\"password\": \"tpassword\"," +
    "\"serverUrl\": \"http://192.168.10.236:8085\"," +
    "\"ticket\": \"xxxxticket\"," +
    "\"ext\": \"扩张参数\"" +
"}";
params =URLEncoder.encode(params,"utf-8");
<a href="seeyonM3Phone//m3?loginParams={params}">打开M3</a>


如果依然无法唤起，确保M3 APP是最新版本。随后再基于最新版本M3源码中进行部分修改：M3源码使用XCode打开，在左侧文件列表搜索M3-Info.plist，找到key：URL types，逐级展开查看是否包含URL Schemes为seeyonM3Phone的项，如没有，仿照添加。



编撰人：het、lichaoj


快速跳转



 * M3唤起三方APP或被唤起开发方案
   * 需求
   * 开发方案
     * 第一种：M3唤起三方APP
       * Android修改点
       * IOS修改点
     * 第二种：三方APP唤起M3
       * Android修改点
         * M3 URL Scheme信息
         * 三方唤起M3示例
       * IOS修改点



分享链接分享链接

## 98. 【M3】正文预览“下载查看”按钮屏蔽

> 原始路径：`/40/1002/1950.html`  
> 相对路径：`40/1002/1950.md`

## 【M3】正文预览“下载查看”按钮屏蔽


## 背景

1、如果节点权限的基础操作中配置了“正文保存”操作，那么移动端正文预览的界面就会出现“下载查看”按钮，如下图所示：



2、如果正文盖了图片章，通过移动端正文预览中“下载查看”按钮将正文下载下来，此文件通过第三方软件打开并对其进行修改，存在安全隐患。


## 问题原因

1、pc端下载文件的时候会对有章的文件进行处理，下载下来的文件不会被编辑； 2、移动端通过正文中的“下载查看”按钮下载的文件，由于第三方软件不受控制，可以对文件进行编辑。


## 解决方案

为了不影响PC端的节点权限，可以通过单独对移动端进行处理，通过屏蔽移动端“下载查看”按钮的方式对此问题进行限制，具体修改的方法如下： 修改mplus-front/src/apps/v5/edoc/js/details/summary-debug.js文件初始化正文的逻辑，屏蔽掉“下载查看”按钮，方法是将下图红框中的逻辑去掉



备注：此处也可以根据需求做M3特有的权限控制来屏蔽按钮

编撰人：ranjf、het




快速跳转



 * 【M3】正文预览“下载查看”按钮屏蔽
   * 背景
   * 问题原因
   * 解决方案



分享链接分享链接

## 99. 不参加会议不要在领导行程中展示

> 原始路径：`/40/1070/1071.html`  
> 相对路径：`40/1070/1071.md`

## 不参加会议不要在领导行程中展示


## 需求

标准产品有会议模块和领导行程模块的联动：当新建一个会议，与会人是领导时，在领导行程上面也会有一条记录，以方便大家看到领导的工作时间排期。

用户期望：领导在会议中选择了“不参加”，则表示不参会，此条会议记录需要从领导行程中去掉，以避免误解行程。

如下是一条待开的会议记录：



如下是目标管理-领导行程下面同步的会议记录（说明中有“会议同步数据”几个字）：




## 标准产品实现原理

标准产品在MeetingManagerImpl#publishMeetingAfterAffairs中实现了：新建会议后向领导行程推送数据的功能：

private Map<String, Object> buildLeaderAgendInfo(MtMeeting meeting) {
        Map<String, Object> params = new HashMap<>();
        params.put("moduleType", "meeting");
        params.put("moduleId", meeting.getId());
        params.put("title", meeting.getTitle());
        params.put("startTime", meeting.getBeginDate());
        params.put("endTime", meeting.getEndDate());
        params.put("agendaDesc", "会议同步数据");
        params.put("createUser", meeting.getCreateUser());
        return params;
    }



## 解决方案

需求：领导在会议中选择了“不参加”，则表示不参会，此条会议记录需要从领导行程中去掉。

解决方法： 1、编写Event事件监听器Listener，监听会议的回执处理事件 2、通过会议回执事件来判断处理人是否是领导，如果是领导则发起删除领导行程的操作

参考资料：

一、事件监听组件编写引导：https://open.seeyoncloud.com/v5dev/39/80.html

二、会议回执事件接口（来自SeeyonAPI）：https://open.seeyoncloud.com/seeyonapi/8.2/event/75/#%E4%BC%9A%E8%AE%AE%E5%9B%9E%E6%89%A7%E4%BA%8B%E4%BB%B6

三、判断是否是领导接口（Java）：com.seeyon.apps.leaderagenda.LeaderAgendaApi#isLeader(memberId)

四、删除领导行程代码参考：com.seeyon.apps.leaderagenda.manager.LeaderAgendaManagerImpl#deleteAgenda(agendaId)，需要自行参考代码实现删除领导会议行程的代码

五、领导行程数据库表：LEADER_AGENDA_INFO

编撰人：het




快速跳转



 * 不参加会议不要在领导行程中展示
   * 需求
   * 标准产品实现原理
   * 解决方案



分享链接分享链接

## 100. 统一待办降版本适配手册

> 原始路径：`/40/1092.html`  
> 相对路径：`40/1092.md`

## 统一待办降版本适配手册

说明：

1、以V7.1SP1 20190930基线代码为例。

2、示例代码版本较老，存储在SVN仓库，studio中建对应项目仅做代码存储，体现修改记录。

3、视频讲解位置 链接：https://pan.baidu.com/s/15u6nrN-OzKEin1HTeB6GYg 提取码：ms6g 【客开知识大纲3.0】-【研发知识转移2023】-【统一待办降版本适配手册】


## 支持原则和适配成本

V5V8融合由两部分代码构成，不同版本的集成成本不同：


## 第一部分代码：V5推送接口代码

 * 8.2SP1及后续版本，无客开成本，标准产品已经自带这部分代码，开箱即用

 * 8.1、8.1SP1、8.1SP2、8.2版本：需要预留3天客开及自测工作量，适配新闻、公告、调查等模块推送代码，适配方式：参考Ctp-Stuido“客开复用插件：V5V8融合”里面新闻、公告、调查的代码做适配，或者参考标准产品8.2SP1的对应模块代码做适配。

 * 8.0SP2及更早版本：需要预留6天客开及自测工作量，适配协同、公文、新闻、公告、调查等模块推送代码，适配方式：参考Ctp-Stuido“客开复用插件：V5V8融合”里面新闻、公告、调查的代码做适配

> 如何适配可参考本手册

> 如项目上无客开能力适配，直销项目走“项目开发作业申请单”（抵扣项目客开成本），分销项目走“技术服务支持申请单”（伙伴预支付结算成本费用后支持）


## 第二部分代码：监听V5接口并将消息推送到V8的代码

此代码不区分版本，所有版本通用。

1、短期：联系V8提供补丁包。

2、中期：V8会将适配代码迁移到ctp-studio，位置待定。后续别的项目有集成需求，直接通过ctp-studio申请代码自行合并即可。

> 如何适配可参考本手册视频培训部分

> 如项目上无客开能力适配，直销项目走“项目开发作业申请单”（抵扣项目客开成本），分销项目走“技术服务支持申请单”（伙伴预支付结算成本费用后支持）


## 获取studio代码

客户名称搜索"V5V8"，找到如图所示项目。



复制代码仓库地址，删除"/v5.git"，使用"http://gitlab.kk.seeyon.com/customize/KKCJZB202308210001"访问。



进入"V5V8融合for7.1"项目，选择v71sp1_hotfix_20190930_pending分支，README.md中简要说明此分支作用及代码版本基线





代码提交记录分为两类，分别为需要修改文件对应版本发版源码，以及针对源码的修改记录提交




## 交互逻辑

如图，分为两类，直接组装数据调用统一待办事件；以及通过工作流中转，在工作流结束事件中统一推送。




## 事件类介绍

1、事件类：ExtIntegrationExtendEvent

2、应用数据类：ExtSummary

包含事项变动列表、应用标题、发起人、发起时间等。

3、事项变动列表类：ExtAffair

包含事项所属人、事项状态、事项删除状态、PC跳转链接、移动跳转链接等。

4、工作流变动事项类：ExtIntegrationWorkflowBO


## 适配方式

1、参照代码提交记录，在对应版本适配代码

2、在触发ExtIntegrationExtendEvent事件的总入口处检查各项数据是否正确，建议参照相邻确认有此功能版本。确保相同的操作，调用事件次数相同、变动事项列表数量相同、变动事项中关键状态相同。


## FAQ

F：版本与示例版本不一致如何处理？

Q：参照示例中的修改记录找对应位置自行适配。

F：适配时发现部分代码在适配版本中找不到怎么办？

Q：不同版本功能不一定完全相同，有可能会少也有可能会多。如果适配版本都无此功能，自然无需适配。如果适配版本相比示例更多，参照适配方式验证数据方式，在具备此功能的高版本中查找代码修改点。

F：相同的功能，affair.state与affair.subState的值与示例版本不一致怎么办？

Q：根据实际效果而定，如果不影响可以不用考虑，要是影响了可以参考示例版本特殊处理。建议对推送事件中的对象做处理，不影响OA原有逻辑。

F：相同的位置加上了代码，但是运行到事件推送接口的数据量和状态与示例版本不一致怎么办？

Q：不同版本对于数据实际更新的处理不完全相同，分析代码另外找合适的位置适配，确保到事件接口处的数据正确。

编撰人：lichaoj、het




快速跳转



 * 统一待办降版本适配手册
   * 支持原则和适配成本
     * 第一部分代码：V5推送接口代码
     * 第二部分代码：监听V5接口并将消息推送到V8的代码
   * 获取studio代码
   * 交互逻辑
   * 事件类介绍
   * 适配方式
   * FAQ



分享链接分享链接

## 101. 适配第三方数据库解决方案

> 原始路径：`/40/1113/1114.html`  
> 相对路径：`40/1113/1114.md`

## 适配第三方数据库解决方案


## 适合人群

本文档适合后端开发人员阅读（包括有标准产品定制开发基础的客开人员）


## 前言

标准产品适配了很多数据库厂商，然而信创数据库厂商千千万，数据库类型层出不穷。不同客户总会选择一些非标的数据库，此时就需要评估是否进行代码适配。

首先，可以明确的是不是所有非标数据库都需要代码适配：

 * 第一类：不少信创数据库只是在主流数据库基础上做了微小包装，驱动、连接方式都是用原厂的，比如OceanBase for MySQL、TDSQL for MySQL内核都是MySQL，驱动也用的MySQL，这些就当作MySQL数据库去部署即可，无需任何二次开发；
 * 第二类：有的数据库则在开源数据库内核基础上做了一定的封装，比如瀚高、海量就是Postgresql的包装，但运行时可能存在一些关键字或转换报错，需要联系厂商执行一些SQL做转换适配，我们无需二次开发；
 * 第三类：有的数据库厂商则是做了深度包装或大的改动，比如GaussDB for OpenGauss，就是Postgresql内核，但连接URL、驱动名都是自己的，此时我们就需要做一定的代码适配；
 * 第四类：有的数据库可能是自己写的底层或做了巨大改动，SQL语法只是遵循某个主流数据库语法，但不全部遵循，比如南大通用，此类数据库需要与厂商首先确认使用哪一套通用数据库SQL语法，在遇到语法不匹配的时候，让厂商进行定制修改，此类数据库适配周期较长；
 * 第五类： 是否是分布式分片数据库， 如果数据库要做分片键，则产品不支持

按照1~4类数据库厂商类型，适配成本从小到大依次是：第一类<第二类<第三类<第四类。


## 如何判断新数据库是否需要代码适配？



我们先回顾一段Java JDBC入门代码：

String url = "jdbc:mysql://localhost:3306/mydb";
String user = "root";
String password = "password";

// 加载MySQL JDBC驱动
String driverName = "com.mysql.jdbc.Driver";
Class.forName(driverName);
Connection conn = DriverManager.getConnection(url, user, password);
DatabaseMetaData metaData = conn.getMetaData();

// databaseName = MySQL
String databaseName = metaData.getDatabaseProductName();


以上JDBC连接代码最重要的有几个变量url、driverName、databaseName，万变不离其宗：新数据库厂商，也围绕这几个变量来确认适配可行性！

联系数据库厂商，让厂商提供如下问题的答案：

1、数据库连接URL是什么？ 如果不是标准产品适配的这几家，则存在适配工作量。





2、数据库的JDBC驱动类名是什么？ 如果不是主流数据库厂商的驱动类名，则存在适配工作量。

com.mysql.jdbc.Driver
oracle.jdbc.driver.OracleDriver
org.postgresql.Driver
com.microsoft.sqlserver.jdbc.SQLServerDriver


3、通过JDBC连接数据库获取DatabaseMetaData.getDatabaseProductName()值是什么？ 如果不主流数据库厂商的名称，则存在适配工作量。

MySQL
Oracle
PostgreSQL
Microsoft SQL Server


4、当前数据库是基于哪一套主流库内核（Postgresql？MySQL？）做的二次封装？还是纯自研？ 厂商如果是基于主流数据库内核做的封装，则可以使用咱们标准产品对应的数据库ALL IN ONE执行脚本初始化，以及代码也可以适配这套标准。

5、厂商是纯自研的话，那么自研数据库兼容Postgresql、MySQL、SQLServer、Oracle哪一套主流库语法？ 比如厂商说完全兼容Oracle，则我们可以编写代码，让厂商库走Oracle逻辑。

6、检测指定表是否存在索引的SQL语句是否随主流库，还是自研系统表？ 如果系统表与主流库厂商一致则不存在开发，如果自研系统表，则需要调整代码。

比如：虚谷遵守Oracle数据库语法标准，但检测是否存在索引的表与Oracle不同：Oracle是USER_IND_COLUMNS，虚谷是USER_TABLES, USER_COLUMNS, USER_INDEXES，则需要调整代码。


## 代码修改点

以GaussDB for OpenGuass数据库为例，存在几个非标选项，则需要做代码定制开发：

 * 数据库URL是jdbc:opengauss://127.0.0.1:30100/xxx?currentschema=pams&batchMode=false&reWriteBatchedInserts=off&blobMode=on
 * 数据库驱动类名是com.huawei.opengauss.jdbc.Driver
 * 数据库databaseName是Postgresql
 * 数据库是基于Postgresql内核做的二次封装


## 数据库连接URL适配：修改ctp-giant-panda项目（V9.0已迁移到ctp-panda项目）

注意V9.0开始已迁移到ctp-panda项目，V9.0之后从ctp-panda项目中寻找源码。

GaussDB for OpenGuass数据库URL是jdbc:opengauss://127.0.0.1:30100/xxx?currentschema=pams&batchMode=false&reWriteBatchedInserts=off&blobMode=on，没有在标准产品清单中，故需要在产品中进行注册。

1、修改ctp-giant-panda工程的com/seeyon/ctp/giant/panda/database/url/ValidateContext.java文件，增加数据库新产品名称：

public class ValidateContext {

	忽略若干其它代码......

    public static final String ORACLE = "oracle";

    public static final String DM = "dm";

	// 第一个修改点：增加opengauss常量 start
    public static final String OPENGAUSS = "opengauss";
	// 第一个修改点：增加opengauss常量 end
	
	忽略若干其它代码......
	
	public static JdbcValidateResult connectValidate(String url, Properties info) {
        
		忽略若干其它代码......
		
        if (urlTypeMatches(sourcesUrl,MYSQL_JDBC_TYPE)) {
            jdbcUrlParamsValidate = new MysqlJdbcUrlParamsValidate(MYSQL_JDBC_TYPE);
        } else if (urlTypeMatches(sourcesUrl, PG_JDBC_TYPE)) {
            jdbcUrlParamsValidate = new PostgresqlJdbcUrlParamsValidate(PG_JDBC_TYPE);
        } else if (urlTypeMatches(sourcesUrl, GBASE)) {
            jdbcUrlParamsValidate = new JdbcUrlCommaParamsValidate(GBASE);
		// 第二个修改点：判断数据库连接URL中带opengauss关键字则走opengauss通路 start
		// 这里sourceUrl = jdbc:opengauss://127.0.0.1:30100/xxx?currentschema=pams&batchMode=false&reWriteBatchedInserts=off&blobMode=on
        } else if (urlTypeMatches(sourcesUrl, OPENGAUSS)) {
            jdbcUrlParamsValidate = new DefaultJdbcUrlParamsValidate(OPENGAUSS);
		// 第二个修改点：判断数据库连接URL中带opengauss关键字则走opengauss通路 end
        } else {
            throw new RuntimeException("不支持的数据库类型，Url:" + sourcesUrl);
        }
		
		忽略若干其它代码.......
	
	}


2、修改ctp-giant-panda工程的com/seeyon/ctp/giant/panda/database/url/jdbcParamsBlackWhiteList.properties文件，添加数据黑白名单，有对应key即可：

> 注：这里opengauss.white=中的opengauss对应的是ValidateContext.OPENGAUSS常量值

忽略若干配置......
kingbase8.white=clientEncoding,user,password
kingbase8.black=
## 修改点：增加两行opengauss的参数，等号后面的信息可以为空start
opengauss.white=
opengauss.black=
## 修改点：增加两行opengauss的参数，等号后面的信息可以为空end


注：如果ctp-giant-panda工程的com/seeyon/ctp/giant/panda/database/url目录下是vendorDriverUrlWhiteList.properties文件，也可以这样添加key：

忽略若干配置......
kingbase8=
oscar=
opengauss=



## 数据库驱动类名适配：修改ctp-jdbcproxydriver项目

GaussDB for OpenGuass数据库驱动类名是com.huawei.opengauss.jdbc.Driver，没有在标准产品清单中，故需要在产品中进行注册。

1、修改ctp-jdbcproxydriver工程com/seeyon/ctp/monitor/perf/jdbcmonitor/proxyobj/ProxyDriverList.properties文件添加驱动

忽略若干配置......
com.kingbase8.Driver=jdbc:kingbase8://127.0.0.1:54321/mydatabase
com.oscar.Driver=jdbc:oscar://127.0.0.1:2003/mydatabase
com.gbasedbt.jdbc.Driver=jdbc:gbasedbt-sqli://127.0.0.1:9088/gbasev5:GBASEDBTSERVER=mydatabase;SQLMODE=Oracle;DBDATE=Y4MD-;DB_LOCALE=zh_CN.57372;
## 修改点：增加GaussDB for OpenGuass数据库驱动类名 start
com.huawei.opengauss.jdbc.Driver=jdbc:opengauss://127.0.0.1:30100/mydatabase
## 修改点：增加GaussDB for OpenGuass数据库驱动类名 end


> 注：这个配置文件最重要的是要有com.huawei.opengauss.jdbc.Driver驱动类名，至于类名=等号后面的URL只是一个Demo，不用写客户真实地址

2、修改ctp-jdbcproxydriver工程src/main/resources/META-INF/services/java.sql.Driver连接池驱动代理类为如下固定参数：

> 注：V8.1SP1及之后的版本已经默认内置，如果发现代码中已经有此配置则无需修改本步

com.seeyon.ctp.monitor.perf.jdbcmonitor.proxyobj.JMProxyDriver



## 非标数据库databaseName适配：需要修改多处代码

## 数据库名称非标准，为什么要做多处修改？

这一段内容非常重要，请开发理解透彻，以便做好准确的适配！

如果通过JDBC连接，调用DatabaseMetaData.getDatabaseProductName()返回的数据库名称是非标准支持的库名，假设GaussDB返回的就是“GaussDB”，则意味着这个数据库是一个“黑户”，标准产品不知道这个数据库用什么Hibernate方言、也不知道用什么SQL语法兼容。

解决方案就是：让这个新数据库告知我们，他们遵守的是Oracle、SQLServer、Postgresql、MySQL主流数据库里面的哪一家SQL语法？只要遇到这个数据库时则执行主流数据库的代码逻辑。

## 非标数据库名适配点：修改ctp-core项目

假设：新数据库厂商的DatabaseMetaData.getDatabaseProductName() = GaussDB，并且厂商基于Postgresql内核做的改造，遵守PG数据库SQL语法。技术上我们需要识别到名为GaussDB数据库标识时，让其走Postgresql的代码逻辑，具体修改点如下：



1、修改ctp-core项目com/seeyon/ctp/util/JDBCAgent.java新增对应数据库的判断方法：

public final class JDBCAgent implements Closeable{

	public static boolean isPostgreSQLRuntime(){
		String dbType = getDBType();
		if(dbType == null){
			return false;
		}
        // 修改点：增加dbType.contains("GaussDB")判断，如果当前环境是GaussDB，则返回true，让其走PG代码逻辑 start
		return dbType.contains("postgresql") || dbType.contains("GaussDB");
        // 修改点：增加dbType.contains("GaussDB")判断，如果当前环境是GaussDB，则返回true，让其走PG代码逻辑 end
	}
	
	忽略若干其它代码......
	
}


2、修改ctp-core项目org/hibernate/dialect，在目录下新增一个方言类:

package org.hibernate.dialect;

/**新增一个方言类，继承PG方言**/
public class CTPGaussDBSQLDialect extends CTPPostgreSQLDialect{
	// 内部实现可以为空，除非新库Dialect具有特殊性，否则可以完全使用PGDialect特性
}




3、修改ctp-core项目org/hibernate/dialect/resolver/CTPDialectResolver.java文件，增加对应方言的实现：

public class CTPDialectResolver extends AbstractDialectResolver {

    private static final Logger log = LoggerFactory.getLogger(CTPDialectResolver.class);

    protected Dialect resolveDialectInternal(DatabaseMetaData metaData) throws SQLException {
        String databaseName = metaData.getDatabaseProductName();
        if(AppContext.getCache(GlobalNames.CACHE_DATABASE_NAME_KEY)==null) {
        	AppContext.putCache(GlobalNames.CACHE_DATABASE_NAME_KEY, databaseName);
            AppContext.putCache(GlobalNames.CACHE_DATABASE_NAME_LOWERCASE_KEY, databaseName.toLowerCase());
            initJdbcDriverBooleanConfig(databaseName);
        }

        if ("MySQL".equals(databaseName)) {
            return new CTPMySQLDialect();
        }

        // 修改代码：增加新数据库的方言注册信息 start
        if ("GaussDB".equals(databaseName)) {
            return new CTPGaussDBSQLDialect();
        }
        // 修改代码：增加新数据库的方言注册信息 end

        if ("PostgreSQL".equals(databaseName)) {
            return new CTPPostgreSQLDialect();
        }

		忽略若干其它代码......
}


> 注：如果你嫌麻烦，可以忽略修改点2，直接进行修改点3，让程序判断数据库为GaussDB时，走CTPPostgreSQLDialect方言。有第2步的好处是方便数据库做特殊定制。


## 系统表纯自研：查询表索引适配点

产品中涉及查询数据库的系统表，比如索引记录表，用于判断是否存在索引，虚谷遵守Oracle数据库语法标准，但检测是否存在索引的表与Oracle不同：Oracle是USER_IND_COLUMNS，虚谷是USER_TABLES, USER_COLUMNS, USER_INDEXES，则需要调整代码，适配虚谷。

代码位置cap-api\src\main\java\com\seeyon\ctp\form\bean\FormTableIndexBean#searchIndexSql

	/**
     * 检测动态表列是否存在索引的SQL语句
     */
    private String searchIndexSql(String tableName, String columnName) {
        if (ReportDBUtils.isOracleRuntime()) {//oracle数据库；
            String sql = null;
            if(ReportDBUtils.isXuGuRuntime()) {//可以判断请求URL带xugu关键字
                StringBuffer buffer = new StringBuffer();
                buffer.append("SELECT USER_INDEXES.INDEX_NAME, USER_TABLES.TABLE_NAME, USER_COLUMNS.COL_NAME FROM USER_TABLES, USER_COLUMNS, USER_INDEXES ");
                buffer.append("WHERE USER_TABLES.TABLE_ID = USER_COLUMNS.TABLE_ID  AND USER_TABLES.TABLE_ID = USER_INDEXES.TABLE_ID");
                buffer.append("and USER_TABLES.TABLE_NAME = Upper('" + tableName + "') ");
                buffer.append("AND USER_COLUMNS.COL_NAME= Upper('" + columnName + "') ");
                buffer.append("AND USER_INDEXES.INDEX_NAME IN (");
                buffer.append("  SELECT USER_INDEXES.INDEX_NAME FROM USER_INDEXES UI, USER_TABLES UT WHERE UI.TABLE_ID = UT.TABLE_ID");
                buffer.append("  AND UT.TABLE_NAME = Upper('" + tableName + "') GROUP BY UI.INDEX_NAME HAVING COUNT(*)=1");
                buffer.append(")");
                sql = buffer.toString();
            } else {
                //since 20200904 sqlserver 转达梦数据库后，索引的名称变了（如INDEX12258405396505042），已经不能通过以前的索引名称去判断 索引是否存在。应该是查询当前列是否存在 单列索引
                sql = "SELECT INDEX_NAME,TABLE_NAME,COLUMN_NAME  FROM USER_IND_COLUMNS WHERE TABLE_NAME = Upper('" + tableName + "')  AND COLUMN_NAME= Upper('" + columnName + "')" +
                        " AND INDEX_NAME IN " +
                        "(SELECT INDEX_NAME FROM SYS.USER_IND_COLUMNS uic WHERE uic.TABLE_NAME = Upper('" + tableName + "') GROUP BY INDEX_NAME HAVING COUNT(*)=1) ";
            }
            LOGGER.info("searchIndexSql:"+sql);

            return sql;
			
			忽略若干其它代码......
}



## 环境运维：将新数据库URL注册到OA系统中

以上完成后，除了编译打补丁到OA环境下，还需要在OA配置相关数据库信息：

如果是X86系统，默认Tomcat中间件，直接修改base下数据库连接base\conf\datasourceCtp.properties文件，确保存在如下信息：

> 信创下根据对应中间件做配置

ctpDataSource.driverClassName=com.huawei.opengauss.jdbc.Driver
ctpDataSource.url=jdbc:opengauss://127.0.0.1:30100/pamsdbsit?currentschema=pams&batchMode=false&reWriteBatchedInserts=off&blobMode=on
ctpDataSource.username=数据库帐号
ctpDataSource.password=数据库密码(建议通过SeeyonConfig随意选一个数据库设置密码后保存生成)


另外增加druid连接空闲检测和keepalive保活参数是必须的：修改base下数据库连接base\conf\datasourceCtp.properties文件：

## 连接空闲检测
ctpDataSource.druid.timeBetweenEvictionRunsMillis=60000
ctpDataSource.druid.validationQuery=select 1
ctpDataSource.druid.validationQueryTimeout=10
ctpDataSource.druid.testOnBorrow=true
## 从连接池重用一个空闲连接时，会根据连接的空闲时间决定是否执行 validationQuery 去判断连接的有效性
ctpDataSource.druid.testWhileIdle=true
## 获取连接时最大等待时间，单位毫秒，5分钟
ctpDataSource.druid.maxWait=300000
## 连接保持空闲而不被驱逐的最小时间  3分钟
ctpDataSource.druid.minEvictableIdleTimeMillis=180000
## 连接池中的minIdle数量以内的连接，空闲时间超过minEvictableIdleTimeMillis，则会执行keepAlive操作。
ctpDataSource.druid.keepAlive=true
## 查询超时时间 - 单位是秒 默认不限时，设置最大时间30分钟
ctpDataSource.druid.queryTimeout=1800


备注：ctpDataSource.druid.validationQuery不同数据库的探活SQL参考：

Oracle: select 1 from dual
Oscar（神州通用）: select 1
MySQL: select 1
Microsoft SqlServer: select 1
Postgresql select 1
DM	jdbc:dm	select 1
KingBase(人大金仓): select 1
GBase （南大通用）: select 1 from dual
openGuess高斯数据库:  select 1



## 非必须：修改ctp-log-elasticsearch项目

如何确认是否需要修改ctp-log-elasticsearch项目：参考前文JDBCAgent实现，如果是在JDBCAgent下新增了一个is新数据库Runtime方法则必然要修改ctp-log-elasticsearch项目，如果只是基于JDBCAgent#isPostgreSQLRuntime等现有方法做了修改，则不需要动ctp-log-elasticsearch项目。

1、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.jdbc.common.DatabaseType.java新增对应数据库类型：

public enum DatabaseType {
	// 修改代码：增加新数据库 start
	GAUSSDB {
		@Override
		public String getValue() {
			return "gaussdb";
		}
	},
	// 修改代码：增加新数据库 end
	ORACLE {
		@Override
		public String getValue() {
			return "oracle";
		}
	},
	忽略其它代码......
}


2、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.jdbc.sql.create包目录下，增加新数据库的实现：

/**新增实现类GaussDBCreateTableSqlBuilder**/
public class GaussDBCreateTableSqlBuilder extends AbstractCreateTableSqlBuilder {
	@Override
	protected DatabaseType getDatabaseType() {
		return DatabaseType.GAUSSDB;
	}
}


3、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.jdbc.sql.create.CreateTableSqlBuilders.java文件，增加新数据库的Builder注册接口：

public class CreateTableSqlBuilders {
	// 修改代码：增加GaussDB注册接口 start
	public static CreateTableSqlBuilder gaussdb() {
		return new GaussDBCreateTableSqlBuilder();
	}
	// 修改代码：增加GaussDB注册接口 end
	
	public static CreateTableSqlBuilder oracle() {
		return new OracleCreateTableSqlBuilder();
	}
	
	public static CreateTableSqlBuilder mysql() {
		return new MysqlCreateTableSqlBuilder();
	}
	忽略其它代码......
}


4、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.jdbc.sql.dialect包目录，增加新数据库的方言实现类：

> 由于前面假设了GaussDB走的PG内核，故我们可以extends PostgresDialect

package com.seeyon.ctp.log.jdbc.sql.dialect;

import com.seeyon.ctp.log.jdbc.sql.create.CreateTableSqlBuilders;
import java.util.List;

class GaussDBDialect extends PostgresDialect {

	@Override
	public List<String> ddlOf(String table) {
		// 重写ddlOf，让其实现走GaussDB自己的Builder
		return CreateTableSqlBuilders.gaussdb().build(table);
	}
}


5、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.jdbc.sql.dialect.SqlDialects.java，增加新数据库的调用方法：

public class SqlDialects {

	// 修改代码：增加新方言的调用方法 start
	public static SqlDialect gaussdb() {
		return new GaussDBDialect();
	}
	// 修改代码：增加新方言的调用方法 end
	
	public static SqlDialect oracle() {
		return new OracleDialect();
	}
	
	public static SqlDialect mysql() {
		return new MySQLDialect();
	}
	
	忽略其它代码......
}


6、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.jdbc.spi目录新增新数据库JDBCLogger的实现：

package com.seeyon.ctp.log.jdbc.spi;

/**由于我们假设GaussDB是PG内核，故可以extends PostgresLogger，否则需要extends AbstractJDBCLogger并参考其它代码编写内部实现**/
public class GaussDBLogger extends PostgresLogger {
	private static final Log log = LogFactory.getLog(GaussDBLogger.class);

	public GaussDBLogger(SqlSessionFactory sqlSessionFactory) {
		super(sqlSessionFactory);
	}

	@Override
	public SqlDialect getDialect() {
		return SqlDialects.gaussdb();
	}
}


7、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.LoggerBeanAutoConfiguration.java的

public class LoggerBeanAutoConfiguration {

	private Logger getOtherJDBCLogger() {
		SqlSessionFactory sessionFactory = SqlSessionFactorys.getSqlSessionFactory();
		// 修改代码：新数据库走新的Logger注册start
		if (JDBCAgent.新数据库())
			return new GaussDBLogger(sessionFactory);
		// 修改代码：新数据库走新的Logger注册end
		if (JDBCAgent.isDMRuntime())
			return new DMLogger(sessionFactory);
		if (JDBCAgent.isKingBaseesRunTime())
			return new KingBaseLogger(sessionFactory);
		忽略其它代码......
	}

	忽略其它代码......
}


8、修改ctp-log-elasticsearch项目com.seeyon.ctp.log.jdbc.sql.update包模块需要做对应的实现，如新增Builder，以及在MergedSqlBuilder.java中提供Builder的实现，以及在SqlDialect#dmlOfmerged实现中调用该builder：



9、修改webapp/WEB-INF/cfgHome/plugin/eslog/scripts 增加对应数据库的建表语句




## 非必须：仅链路追踪组件需要

这一批代码99.999%的客户都无需适配，仅用于有项目化适配链路追踪的客户需求加这些代码：

1、修改ctp-jdbcproxydriver工程com/seeyon/ctp/monitor/perf/jdbcmonitor/proxyobj/trace/analyzer下新增一个url的analyzer：



2、修改ctp-jdbcproxydriver工程DBType新增枚举



3、修改ctp-jdbcproxydriver工程DBMateInfo新增static里map设置



编撰人：zhangzuh、het、manmao




快速跳转



 * 适配第三方数据库解决方案
   * 适合人群
   * 前言
   * 如何判断新数据库是否需要代码适配？
   * 代码修改点
     * 数据库连接URL适配：修改ctp-giant-panda项目（V9.0已迁移到ctp-panda项目）
     * 数据库驱动类名适配：修改ctp-jdbcproxydriver项目
     * 非标数据库databaseName适配：需要修改多处代码
       * 数据库名称非标准，为什么要做多处修改？
       * 非标数据库名适配点：修改ctp-core项目
     * 系统表纯自研：查询表索引适配点
     * 环境运维：将新数据库URL注册到OA系统中
     * 非必须：修改ctp-log-elasticsearch项目
     * 非必须：仅链路追踪组件需要



分享链接分享链接

## 102. 致信开发教程

> 原始路径：`/40/1115/1116.html`  
> 相对路径：`40/1115/1116.md`

## 致信开发教程


## 1、开发准备环境

①　Node.js > 12 ②　Npm ③　可用的OA地址


## 2、致信开发调试

①　安装致信 首先安装致信桌面端应用程序。

修改致信服务器地址，填写完服务器地址后可点击【测试】验证服务器连接是否正常，注意这里不许填写http 或 https。

②　本地启动致信环境 致信代码所在工程zhixin-front，致信依赖包采用使用yarn管理，通过npm install --gloabl yarn 安装最新版的yarn。 安装结束后使用yarn dev启动致信程序

③　修改致信代理 找到致信安装的位置，进入zhixin\resources\app\src文件夹，打开main.js

修改致信代理地址

④　开启致信开发模式 完成以上3步后就可以开启致信开发模式了，退出致信重新登陆，登陆后使用ctrl+shift+alt+i打开控制台开发调试。

编撰人：gemin、het


快速跳转



 * 致信开发教程
   * 1、开发准备环境
   * 2、致信开发调试



分享链接分享链接

## 103. 致信后端开发文档

> 原始路径：`/40/1115/1181.html`  
> 相对路径：`40/1115/1181.md`

## 致信后端开发文档


## 一、搭建A8教程


## 1、从 git 上下载 A8 的环境代码

在同级目录将JDK 复制过来（交接文档中有），目录结构为：


## 2、连接数据库

## 2.1 首先通过svn 拿到最新的数据库ALL-IN-ONE 的SQL



## 2.2 打开Navicat ，新建连接，输入数据库的IP 、 端口 、 用户名 和密码



## 2.3 新建数据库a8_trunk ，选择UTF-8



## 2.4 右键数据库a8_trunk ，选择运行SQL 文件，将之前下载的ALL-IN-ONE 文件运行



## 2.5 执行完成后，点击关闭



## 2.6 打开A8\v5-resource\conf 的SeeyonConfig.cmd 文件



## 2.7 选择第二个页签（数据库连接），修改数据库相关参数，然后点击确定进行保存




## 3、配置致信环境

打开A8\v5-resource\bin 目录，将交接文档中的app.txt 复制到此目录


## 4、配置调试端口

打开A8\v5-resource\bin 目录的catalina.bat 文件，在图中文件增加一行调试信息


## 5、启动A8

运行A8\v5-resource\bin 目录的startup.bat 文件，启动A8


## 二、开发搭建教程


## 1、环境搭建

## 1.1 安装 JDK 1.8

教程网址：https://blog.csdn.net/lduzhenlin/article/details/105425719（注意记得要配置JAVA_HOME 和Path ，要不然IDEA不一定能识别。）

## 1.2 安装IDEA

直接去官网，下载社区版IDEA（免费版）

## 1.3 配置Maven

## 1.3.1 Maven安装

教程网址：https://www.runoob.com/maven/maven-setup.html

## 1.3.2 IDEA 配置 Maven

(1) 将交接文档中的settings-seeyon.xml 文件放到Maven 的conf 目录下。 (2) 打开IDEA 的File-Settings 菜单，修改Maven 相关配置

## 1.4 配置远程 Debug

## 1.4.1 点击 Add Configuration 这个按钮



## 1.4.2 点击+号，选择Remote



## 1.4.3 输入A8 的地址和调试端口，点击OK



## 1.4.4 最后点击此按钮开启调试，此时A8 必须是启动完成状态




## 2、源码使用

## 2.1 下载源码

8.0SP1 及以前版本从 svn 上下载代码，8.0SP2 及以后版本从 git 上下载代码

## 2.2 导入源码到工程

## 2.2.1 svn 方式

打开Idea ，新建一个 Empty Project ，通过svn 或者git 的方式（根据A8 版本自行选择）将代码导入到新建的目录中

## 2.2.2 git 方式

通过自带的命令行工具（推荐）或者界面化工具把代码下载到工程目录。打开IDEA，新建Module ，将代码导入工程中。


## 3、代码开发

## 3.1 Spring 规范

## 3.1.1 Spring 配置文件

在controller 、 manager 、 dao 层创建的时候，需要在对应的spring-zx-rong-Shape52 Shape53 Shape54 controller.xml 、 spring-zx-rong-manager.xml 、 spring-zx-rong-dao.xml 文件中新增定义。

## 3.1.1 Spring Bean使用

 * log--群操作日志数据库操作ZxAuthDao
 * ZxAuthDaoImpl--人员授权数据库操作
 * ZxBroadcastIssueBodyDao--老版本小广播代码--废弃
 * ZxBroadcastIssueBodyDaoImpl--老版本小广播代码--废弃
 * ZxBroadcastIssueDao--老版本小广播代码--废弃
 * ZxBroadcastIssueDaoImpl--老版本小广播代码--废弃
 * ZxBroadcastIssueScopeDao--老版本小广播代码--废弃
 * ZxBroadcastIssueScopeDaoImpl--老版本小广播代码--废弃
 * ZxBroadcastManagerDao--老版本小广播代码--废弃
 * ZxBroadcastManagerDaoImpl--老版本小广播代码--废弃
 * ZxBroadcastManagerGroupDao--老版本小广播代码--废弃
 * ZxBroadcastManagerGroupDaoImpl--老版本小广播代码--废弃
 * ZxBroadcastManagerScopeDao--老版本小广播代码--废弃
 * ZxBroadcastManagerScopeDaoImpl--老版本小广播代码--废弃
 * ZxConfigCacheImpl--致信相关配置缓存ZxConfigDao
 * ZxConfigDaoImpl--致信相关配置数据库操作
 * ZxGroupDao
 * ZxGroupDaoImpl--群组数据库操作ZxRongCache
 * ZxRongCacheImpl--致信相关缓存
 * ZxTokenDao
 * ZxTokenDaoImpl--token数据库操作enums--相关枚举
 * event--致信创建头像监听exception--致信自定义异常io--融云的sdk
 * job--定时任务
 * listener--人员离职、部门群变化等监听manager
 * auth--致信人员授权
 * chatmessage--合并聊天记录config--致信相关配置
 * doc--文档中心保存合并聊天记录extra--创建群组头像
 * file--致信文件操作groupauth--群文件权限job--定时任务
 * jrmf--红包littlebroadcast--小广播lock--分布式锁
 * log--群操作日志手机messagecard--消息卡片online--在线状态
 * org--多维组织shortmenu--磁贴
 * ticket--双击头像ticket管理
 * ctp
 * usermessage--业务消息获取videoauth--音视频
 * xiaoz--智能问答S2SRongManager
 * S2SRongManagerImpl--和融云sdk集成
 * UcOrgManager
 * UcOrgManagerImpl--致信组织架构（大部分已废弃） ZxGroupManager
 * ZxGroupManagerImpl--群组管理
 * ZxManager ZxManagerImpl--废弃ZxMsgSwitchManager
 * ZxMsgSwitchManagerImpl--system业务消息接收设置ZxPcMessagePipeline--消息通道（已废弃） ZxRestManager
 * ZxRestManagerImpl--部分组织架构获取ZxRobotManager ZxRobotManagerImpl--机器人消息ZxRongManager
 * ZxRongManagerImpl--token管理models--老版本的一些bean
 * po--数据库对象dangmessage--小广播对象groupauth--群文件权限对象log--群操作日志对象
 * ZxAuthUser--致信人员授权对象ZxBroadcastIssue--老版本小广播代码--废弃ZxBroadcastIssueBody--老版本小广播代码--废弃ZxBroadcastIssueScope--老版本小广播代码--废弃ZxBroadcastManager--老版本小广播代码--废弃
 * ZxBroadcastManagerGroup--老版本小广播代码--废弃ZxBroadcastManagerScope--老版本小广播代码--废弃ZxConfigItem--致信配置对象
 * ZxGroupInfo--群组对象ZxGroupMember--群成员对象ZxToken--token对象
 * service--一些老代码sso
 * ZxSSOLoginHandshakeImpl--双击头像打开A8的检验（重点）
 * utils--工具类vo--展示类
 * ZxInitializer--致信插件启动入口ZxPluginInitializer
 * UcResource--rest接口，主要是提供systemConfig UcRongResource--rest接口，给m3提供相关接口
 * s2s--老版本代码目录--废弃

## 3.1.2 SQL 提交流程

(1) 提交协同表单 (2) 所属工程组选apps-uc (3) 选择SQL 变更类型

 * 如果选择增加表，需要填写表名和相关字段，下面举例了新增表的格式 表名通过下划线来分割，如ZX_DES。其中主键定义为ID ，字段类型是BIGINT ，设置为主键。
 * 若字段是字符串类型，定义为VARCHAR(255)。
 * 若字段是日期类型，定义为DATETIME
 * 若字段是数字类型（比如定义状态值），定义为SMALLINT sql示例: (4) 提交flyway 在工程目录apps-uc 下的sql_files 文件夹下有mysql 、 oracle 、 postgresql 、 sqlserver 目录，需要在每个目录下都得新建一个SQL 文件，名字为Vx standard_V8.1_apps-uc.sql ，其中x 指的是版本号，如果这个目录下没有文件，定义x 为2；如果目录下已经有SQL 文件，则x 为当前SQL文件,不同SQL数据库 对应的SQL 都可以在上面协同单子里自动生成。

## 3.1.3 PO 类和 HBM 文件定义

(1) PO 类命名规范和表名映射，每个单词的首字母大写，如包含下划线，则取消下划线，把下划线右边的第一个字母大写。如表名为ZX_DES ，则类名为ZxDes (2) 字段映射：

 * BIGINT 类型对应Long 类型
 * VARCHAR 类型对应String 类型
 * DATETIME 类型对应java.sql.Timestamp
 * SMALLINT 类型对应Integer ZxDes 类声明（写在po 包里）：

//继承BasePo，可以不用声明主键，在BasePo中已经定义，并且提供生成主键的方法public class ZxDes extends BasePO {

//定义字段

/**

描述
*/

private String desName;

/**

创建日期
*/

private Timestamp createDate;

/**

状态
*/

private int desStatus;

//声明get/set方法

public String getDesName() { return desName;

}

public void setDesName(String desName) { this.desName = desName;

}

public Timestamp getCreateDate() { return createDate;

}

public void setCreateDate(Timestamp createDate) { this.createDate = createDate;

}

public int getDesStatus() { return desStatus;

}

public void setDesStatus(int desStatus) { this.desStatus = desStatus;

}

}


 * HBM 文件命名规范是PO类名.hbm.xml如类名为ZxDes ，则类名为ZxDes.hbm.xml

字段映射：

 1. Long 类型对应long 类型
 2. String 类型对应string 类型
 3. java.sql.Timestamp 类型对应timestamp
 4. Integer 类型对应integer ZxDes 类的HBM 文件声明（和ZxDes 类在同级目录）：

<class

name="com.seeyon.apps.zx.po.ZxDes" table="zx_des"

lazy="false"

<id

name="id" type="long" column="id" length="20"

<property

name="desName" type="string" column="des_name" length="255"

/>

<property

name="createDate" type="timestamp" column="create_date" length="19"

/>

<property

name="desStatus" type="integer" column="DES_STATUS"




## 3.1.4 DAO 定义

以消息免打扰数据操作为例，展示下如何使用

 1. 声明接口
 2. 生成实现类并且继承BaseHibernateDao ，其中t 代表数据库操作对象
 3. 利用BaseHibernateDao 的内置方法来简化开发常用方法：对于使用BaseHibernateDao 无法解决的需求，可以使用DbAgent 进行编写sql处理常用代码：

## 3.2 缓存使用规范

## 3.2.1 声明缓存变量

以缓存用户id和ticket为例:

 1. 首先在ZxRongCache类中定义下缓存的类型和名字，一般类型就是CacheMap<K,V>
 2. 在init方法中通过factory.createMap()的方式创建对象

缓存有全量加载缓存和按需加载缓存两种:

 1. 全量加载缓存需要在初始化的时候就把所有数据加载到缓存中使用factory.createMap("zxUserTicketCache", null);的方式来创建缓存
 2. 按需加载缓存不需要在初始化的时候把数据加载到缓存中，但是需要实现MapDataLoader这个类来做到自动从数据库加载的过程



## 3.2.2 缓存使用



## 3.2.3 跨模块调用

对于需要使用到非当前模块的功能（如组织架构、会议、文件等），需要根据不同模块使用下面两种方 案来调用。

 1. 公共模块：如组织架构、文件服务，这种模块在maven 中与apps-uc 进行了相互依赖，所以apps-uc 工程可以直接调用到此模块的类，如OrgManager 、 FileManager 、 AttachmentManager
 2. 独立模块：如会议、文档中心、小智，这种模块没有在Maven 中和apps-uc 进行依赖，所以需要调用公共的依赖模块apps-api 来相互调用。在你需要调用他们的接口的时候，可以使用如MeetingApi 、 DocAPi 、 XiaozQaApi 等接口来进行调用。如果你需要给他们提供接口调用，可以在ZxApi 和ZxApiImpl 中分别编写接口和实现类，供各个模块使用。

## 3.3 Controller 使用规范

以ZxRestController 为例，举例说明：

 1. Controller接口的前缀路径是 http(s)😕/ip:port/seeyon
 2. 因为在spring-zx-rong-controller.xml文件中，映射路径为/uc/rest.do，所以这个类的路径是 http(s)😕/ip:port/seeyon/uc/rest.do 比如要获取群组信息，使用groupInfo方法进行获取，这个方法的路径就是http(s)😕/ip:port/seeyon/uc/rest.do?method=groupInfo 参数读取方式 url 传参：如http(s)😕/ip:port/seeyon/uc/rest.do? body 传参：仅适合POST 请求

public ModelAndView createLittleBroadcast(HttpServletRequest request, HttpServletResponse response) {

Map<String, Object> result = Maps.newHashMap(); try {

Long currentMemberId = getCurrentMemberId();

//使用ZxUtils.getRequestBodyMap(request)的方式获取

Map<String, Object> condition = ZxUtils.getRequestBodyMap(request); String content = (String) condition.get("content");

String files = condition.get("files") == null ? "" : (String) condition.get("files");

String receiverMemberIds = (String) condition.get("receiverMemberIds");

zxLittleBroadcastManager.createLittleBroadcast(currentMemberId, content, files, receiverMemberIds);

result.put(ZxConstants.STATUS, ZxConstants.SUCCESSED);

} catch (Throwable e) { log.error(e.getMessage(), e);

result.put(ZxConstants.STATUS, ZxConstants.FAILED);

}

outResult(response, result); return null;

}


参数返回：调用outResult() 方法，将需要返回的数据填入

## 3.4 Rest 使用规范

以UcRongResource 为例，举例说明：

 1. rest 接口的前缀路径是http(s)😕/ip:port/seeyon/rest
 2. 在Resource 类上增加@Path 注解来声明这个类的路径，如uc/rong
 3. 在Resource 类上增加@Produces 注解来声明这个类的方法的返回值类型，如MediaType.APPLICATION_JSON 代表是json
 4. 在方法上增加@Path 注解来声明这个方法的路径，如getToken
 5. 在方法上增加@GET 或者@POST 注解来声明这个方法的请求类型最终url 就是http(s)😕/ip:port/seeyon/rest/uc/rong/getToken

@Path("uc/rong")
@Produces({ MediaType.APPLICATION_JSON })

public class UcRongResource extends BaseResource {

private static Log log = LogFactory.getLog(UcRongResource.class);

//获取对象的过程中，使用AppContext.getBean("beanName");的方式获取对象private ZxRongManager zxRongManager = (ZxRongManager)

AppContext.getBean("zxRongManager");

@Context HttpServletRequest req; @Context HttpServletResponse resp;

/**

@Description: 获取用户融云 token
@return Map[code:状态值,token:用户的融云token]
*/ @GET

@Path("getToken")

@Produces({ MediaType.APPLICATION_JSON }) public Response getRongToken() {

Map<String, Object> result = new HashMap<String, Object>();


参数获取方式：

 1. 路径参数:如http(s)😕/ip:port/seeyon/rest/uc/rong/groups/bymid/1234567
 2. url 传参：如http(s)😕/ip:port/seeyon/rest/uc/rong/upload/avatar?avatarType=1

//通过req.getParameter()的方式获取参数数据String avatarType =Optional.of(req.getParameter("avatarType")).get(); 
AvatarType avatarTypeEnum = AvatarType.valueOf(avatarType.toUpperCase());
Long groupId = -1L;
String groupIdStr = req.getParameter("groupId"); if (Strings.isNotBlank(groupIdStr)) {

groupId = Long.valueOf(groupIdStr);

}

CommonsMultipartResolver resolver = (CommonsMultipartResolver) Optional.of(AppContext.getBean("multipartResolver")).get();

HttpServletRequest req2 = resolver.resolveMultipart(req); V3XFile v3xFile = Optional.of(zxFileManager.uploadAvatar(req2,

avatarTypeEnum, groupId, user.getId())).get(); result.put("file", v3xFile);

result.put(ZxConstants.STATUS, ZxConstants.SUCCESSED);

} catch (Exception e) {

result.put(ZxConstants.STATUS, ZxConstants.FAILED);

}

return ok(result);

}


body 传参：仅适合POST 请求 参数返回：调用ok() 方法，将需要返回的数据填入


## 4、名词解释

 * Controller：控制层，一般只负责处理参数和返回参数，不负责业务逻辑Manager：业务层，处理业务逻辑
 * Dao：数据层，和数据库交互
 * PO：数据库表映射类，一张表对应一个实体PO类
 * VO：展示类，包装后返回给前端
 * BO：模块与模块之间调用传输的类


## 5、致信功能详解

## 5.1 致信登陆

客户端调用apps-common 包的MainController 类的login4Ucpc3() 方法进行身份校验（如用户名密码、AD域、二维码扫描、自动登录） login4Ucpc3() 方法内部调用ZxApi 的afterComplete() 方法获取用户的信息（如memberId 、 token 等数据，封装到response 中） 常见问题： 3401：超过致信授权最大数 3402：致信服务授权已过期！ 3404：未知错误 看日志（一般是token无效），检查appkey和appsecret是否有效，检查网络是否可以ping通 3405：人员未授权

## 5.2 致信双击头像打开 A8

客户端调用ZxRestController 类的getTicket() 方法，获取到ticket 打开浏览器，访问ZxSSOLoginHandshakeImpl 类的handshake() 方法进行校验

## 5.3 致信穿透业务消息

客户端拼接消息url ，将verification 参数拼接到后面（ verification 参数在调用登录接口的时候从返回值里获取） 打开浏览器，访问ZxRestController 类的commonPierce() 方法进行穿透 通过UcLoginSecurityManager 类校验verification 是否有效 解析参数enc ，转义成真实的跳转url 父页面跳转到pierce.jsp ，内部iframe 对真实url 进行跳转

## 5.4 致信请求通讯录

访问ZxRestController 类的() childAccounts() 方法获取所有的单位 访问ZxRestController 类的() firstDepts() 方法获取当前单位的第一级部门 访问ZxRestController 类的() subDeptInfo() 方法获取子部门（非一级部门）

## 5.5 群组操作

获取群组信息： ZxRestController 类的() groupInfo() 方法 修改群组信息： ZxRestController 类的() updateGroupInfo() 方法 群组加人： ZxRestController 类的() joinMember() 方法 群组减人： ZxRestController 类的() removeGroup() 方法 退出群组： ZxRestController 类的() quitGroup() 方法 解散群组： ZxRestController 类的() dismissGroup() 方法

## 5.6 读取加密狗信息

在ZxConfigManagerImpl 类的loadingZxInfo() 方法中读取了加密狗中的参数，并加载到缓存中； 通过 Class<?> c1 = MclclzUtil.ioiekc("com.seeyon.ctp.product.ProductInfo"); 来定义加密狗配置类 用 MclclzUtil.invoke(c1, "方法名"); 的方式获取数据，其中方法名需要加密狗开发人员告知

## 5.7 离职人员的退群等相关逻辑

在MemberTokenEventListener 类的listenEventUpdateMember() 方法和listenEventDeleteMember()， 方法中对人员的修改和删除进行了监听。当人员发生离职的情况时会触发UpdateMemberEvent；当人员被删除时会触发DeleteMemberEvent；在判断出人员发生离职时，调用ZxAuthManagerImpl 类的blockUser() 方法进行处理离职人员。

 1. 封禁用户：公有云封禁三个月（最多只能三个月），私有云永久
 2. 删除用户的token 数据
 3. 对在线用户进行强行踢掉的处理
 4. 删除群关系：查询这个人所有的群，进行踢出操作

## 5.8 机器人消息卡片逻辑

接收前端传的参数： title-标题 、 content-内容 、 noticeMemberId-@人id 、 talkType-接收对象（0:个人 1:群组） 、 talkId-接收对象id 、 pierceUrl-穿透url 在ZxRobotManagerImpl 类的sendRobotMsg() 方法中对参数进行封装，调用发送消息接口发送消息；在发送消息的时候要注意如果接收人是自己，那么isIncludeSender 要传 0 ，其他情况传 1 ，这个问题在代码中已经提取出通用方法

## 5.9 群组权限、文件收发控制逻辑

## 5.9.1 全局设置：

在单位管理员-致信管理-群文件权限管理 中可以对人员进行全局文件权限控制 在ZxGroupAuthManagerImpl 类的saveGroupAuthMsg() 方法中对人员的文件收发权限进行了设置， 设置后会在zx_groupauth 和zx_groupauth_group 表会进行保存，其中zx_groupauth 表记录每个人的权限， zx_groupauth_group 表记录分组；还会在ZxRongCacheImpl 类的zxGroupAuthCoarseCache 缓存变量中存储数据，提高查询速度

## 5.9.2 单个群组设置：

在uc_group_members 表中，每个群成员都有控制是否允许发送、接收文件的数据。在创建群组的时候，每个群成员会到zx_groupauth 表去查询这个人是否在全局设置过群文件权限，如果设置过就使用设置的权限，没有设置过就默认全部可以收发。在群组中也可以对每个群成员设置每个人权限，设置后不再受全局设置影响

## 5.10 第三方消息接收逻辑

对于第三方消息，之前的老版本是受系统管理员-致信管理-消息接收设置 影响，没有在此设置中的消息无法接收。新版本在判断消息类型是否接收时，对于不在系统预制消息类型中的消息进行放行，代码在ZxUserMessageManagerImpl类的filterMessage()方法中。

ZxConfigItem configItem = zxConfigCache.getZxConfigItem(ZxConstants.ZX_MESSAGE_SWITCH_ALLOW);
if (configItem != null) {
allowString = configItem.getConfigValue();
}
String[] allowArray =allowString.split(",");
Set allCache = Sets.newHashSet(); allCache.addAll(Arrays.asList(allowArray));
List result = Lists.newArrayList(); for (UserHistoryMessage userHistoryMessage : data) {
if (allCache.contains(userHistoryMessage.getMessageCategory().toString()) ||
!isBasicMessage(userHistoryMessage.getMessageCategory().toString()) || isNewAddMessage(userHistoryMessage.getMessageCategory())) {
result.add(userHistoryMessage);
}
}
return result;
}
/**
新增类型消息 不受消息接收设置 也不是nc消息 进行放行
@param messageCategory
@return
*/
private boolean isNewAddMessage(int messageCategory) {
if (ApplicationCategoryEnum.cap4Form.getKey() == messageCategory) { return true;}
return false;
}
/**
是否是基础消息（非nc）
@param messageCategory
@return
*/
private boolean isBasicMessage(String messageCategory) {
String[] messageCategorys = ZxConstants.totalAllowString.split(","); for (String category : messageCategorys) {
if (category.equals(messageCategory)){ return true;}
}
return false;
}


## 5.11 唤醒致信客户端、参数传递相关

各个组通过使用chat.js 文件中的 wakeZX(appCategory, appId, isForward, params) 方法对致信进行唤醒。 appCategory：应用组编号（ApplicationCategoryEnum） appId：主键id isForward：是否允许转发params：额外参数 比如在协同详情页面对致信进行唤醒并且转发卡片到群里，那么appCategory 是 1 ， appId 是此封协同的id ， isForward 是 1 代表允许转发， params 不传在方法对这些参数进行整合后发送给客户端，参数有以下：

 * memberid：人员id loginticket：自动登录的ticket currentUserLocale：国际化语言protocol：协议（http、https） host：IP
 * port：端口 contextPath：前缀，默认是seeyon，在协同云环境会变化成别的前缀productCode：组织码（协同云环境专属）
 * type：autoLogin代表自动登录，sendAppCard代表分享卡片到群里params：额外参数
 * ran：一个随机参数，浏览器打开url会在后面加/ 所以后面拼接个没用的参数防止客户端切割参数失败

## 5.12 应用中心模块调用逻辑

## 5.12.1 系统设置：

通过ZxShortMenuManagerImpl 类的getInitData() 方法设置预设应用组为快捷新建、协同办公、企业文化、我的工具 通过ZxShortMenuManagerImpl 类的saveShortMenuGroup() 方法新建应用组 通过门户的磁贴组件shortMenuContent.jsp 文件的openSelectMenu() 方法，将设置后的数据和当前应用组id 传给portal

## 5.12.2 所有磁贴：

通过ZxRestController 类的showShortMenuGroupContent() 方法获取磁贴数据 先获取所有应用组,遍历每个应用组，通过应用组id 向portalApi 的getSelectedPorletsZx() 方法请求每个组的所有磁贴，封装成VO 返回到前端

## 5.13 轻协作相关接口逻辑

在设置群面板后，调用ZxRestController 类的updateGroupInfo() 方法对群面板进行保存。参数格式：

## 5.13.1群任务：

获取群任务的计数： ZxRestController 类的getGroupTaskCount() 方法获取群任务： ZxRestController 类的getGroupTasks() 方法。

## 5.14 卡片消息实现逻辑：

 1. 在应用页面通过使用chat.js 文件中的 wakeZX(appCategory, appId, isForward, params)方法对致信进行唤醒客户端。具体详情见#5.11、唤醒致信客户端、参数传递相关。
 2. 客户端在选择需要发送的个人或群组后，调用ZxRestController 类的sendAppCard() 方法，进行发送卡片逻辑
 3. 在ZxMessageCardManagerImpl 类的sendAppCard() 方法中，通过messageCategory 拿到应用的ShareDataManager 的实现类
 4. 调用实现类的getZxMessageCard() 方法拿到ZxMessageCardBO 对象
 5. 致信创建卡片消息类，将ZxMessageCardBO 对象设置后，发送消息，客户端接收到消息后进行页面卡片展示。

附：在ctp-common 中定义了一个接口ShareDataManager ，各个应用组如果想支持卡片消息，需要实现这个ShareDataManager 接口，在内部的getZxMessageCard() 方法中定义消息卡片样式。

## 5.15 调用融云api向各端进行消息推送的逻辑：

首先定义一个自定义消息类，继承BaseMessage ，然后实现getType() 和toString() 方法，然后声 明id(消息id) 、 content(标题，离线推送会用) 、 user（接收人信息） 三个通用参数，最后定义自己的自定义类

 //继承BaseMessage
public class ZxRobotMessage extends BaseMessage {
 
/**
消息id
*/
private String id;

/**
标题
可能会走离线推送
*/
private String content;

/**
发送人信息
*/
private ZxMessageUser user;

/**
自定义内容
*/
private ZxRobotVO zxRobotVO;

//消息类型@Override
public String getType() { return "OA:OARobotMsg";}

//转换Json的方式@Override
public String toString() {
return GsonUtil.toJson(this, ZxRobotMessage.class);
}

//各种get/set方法 public String getId() {
return id;
}

public void setId(String id) { this.id = id;}

public String getContent() { return content }

public void setContent (String content) {
this.content = content
}

public ZxRobotVO getZxRobotVO () {
return zxRobotVO;
}

public void setZxRobotVO (ZxRobotVO zxRobotVO) {
this.zxRobotVO = zxRobotVO;
}

public ZxMessageUser getUser () {
return user;
}

public void setUser (ZxMessageUser user) {
this.user = user;
}

}


调用S2SRongManager的publishPrivate()方法和publishGroup()方法发送到个人、群组中

## 5.16 致信封装并穿透打开 A8 应用的两种方式

## 5.16.1 通过消息类型来封装、解析应用链接

代码位置： ZxUserMessageManagerImpl 类的getPcLinkUrlByApp() 方法

## 5.16.1.1 封装、穿透逻辑：

通过上述接口获取到加密的url ，例： http://{ip}/seeyon/uc/rest.do?rification=o8iJxsg 穿透后通过ZxRestController 类的pierce() 方法解析url ，把enc 解析

String linkType = encMap.get("L");
String path = encMap.get("P");
if (Strings.isNotBlank(linkType)) {
//去message-link.properties文件中找真实url
如/collaboration/collaboration.do?method=summary&openFrom=listDone&affairId=
{0}&contentAnchor={1}
link = UserMessageUtil.getMessageLinkType().get(linkType);
if (link == null) {
mv.addObject("ExceptionKey", "mail.read.alert.wuxiao"); return mv;
}
//填充url中的参数 如{0}、{1}
String[] linkParams = request.getParameterValues("P"); for (int i = 0; i < linkParams.length; i++) {
linkParams[i] = Strings.toHTML(linkParams[i]);
}
java.text.MessageFormat formatter = new java.text.MessageFormat(link); int formatsCount = formatter.getFormats().length;
if (linkParams != null) {
if (formatsCount > linkParams.length) { String[] params = new String[formatsCount]; for (int i = 0; i < params.length; i++) {
if (i < linkParams.length) { params[i] = linkParams[i];
} else {
params[i] = "";
}
}
link = formatter.format(params);
} else {
link = formatter.format(linkParams);
}
}
this.pierceVerify(mv, request, response, link, openFrom, linkType);
return mv;
}


## 5.16.1.2 通过消息类型去message-link.properties 配置文件中寻找具体url

解析后进行拼接后在ZxRestController 类的pierceVerify() 方法中进行封装到ModelAndView 跳转到pierce.jsp ，然后在iframe 中进行跳转

## 5.16.1.3 通过消息 url 来解析应用链接

代码位置： ZxUserMessageManagerImpl 类的getShortMenuUrl() 方法


## 三、客户常见问题以及解决方案


## 1、A8群成员与融云群成员不同步

产生原因： A8 在操作人员退群时( ZxGroupManagerImpl 类的transQuitGroup() 方法)，会同时修改A8数据库uc_group_members 表的数据和融云的群成员映射关系，分别是ZxGroupManagerImpl 类的quitLocalGroup() 和quitCloudGroup() 方法。老版本在操作的时候代码出现失误，把融云退群和发送消息绑定到了一个条件里，导致如果设置不发送 消息就会导致融云退群失败，但是A8退群成功，最终的现象就是在群里找不到这个人，但是可以发送和 接收消息。 老代码： 改造后： 解决方案： 可以参考新版本的ZxGroupManagerImpl 类的synGroup() 方法中的下面这一段，逻辑是分别获取群组中A8和融云的成员，进行对比以及修复


## 2、群成员异常退群

产生原因： 客户部署了多套A8 （数据库相互拷贝）且共用了一套Appkey 致信后台默认有定时任务ZxSynGroupJob ，每天凌晨二点进行同步（ ZxjobManagerImpl 类的startSynGroupJob() 方法负责开启），将本地和融云数据不一样的群组进行修复。当不同的A8环境操作同一个群组时，数据库因为进行了隔离所以不会有数据问题，但是因为共用一套融 云环境导致融云数据出现错乱，定时任务的时候会以最后一个完成定时任务的机器数据为准，就会出现 人员异常退群（现象是人还在群里，但是发不了消息） 解决方案： 任选其一：

 * 停掉其他A8 环境停掉致信
 * 替换Appkey


## 3、部门群问题

产生原因： 部门群需要根据人员的状态变化监听进行相应调整群里的成员，因为人员变化监听非常多（人员的新建、离职、调岗、增加兼职、更新兼职等），且准确率不高，之前 使用针对不同的人员变化进行特殊处理的方式很容易出BUG。 解决方案： 合并出一个刷新部门群的方法（ ZxGroupManagerImpl 类的synDepGroupMember() 方法），这个方法的逻辑是：

 1. 获取当前部门群的群成员
 2. 获取当前部门的最新人员组成
 3. 两者进行对比，多则退出，少则增加

只要触发人员的监听，就会调用这个方法进行刷新，保证了数据的准确性


## 4、穿透A8报错，提示无效用户名密码（username is not available）

产生原因： 老版本在通过双击头像打开A8的过程（ ZxSSOLoginHandshakeImpl 类的handshake() 方法）中，是通过用户名、密码的方式进行校验身份，这种方法在一些特殊环境会有问题，比如用户登录用的是AD 域 、 CA 等方式，导致客户端拿到的密码并不是真实的登录密码，还有用户名是中文的情况下有时也会导致用户名解析出问题，最终导致检验通不过，返回 username is not available 解决方案： 致信使用了一次性ticket 的方式来替代传统的A8用户名、密码 校验，解决了以上的问题步骤：

 1. 致信客户端在双击头像打开A8 前先向服务器请求一个一次性的tikcet ，在ZxRongCacheImpl 缓存类的zxUserTicketCache 和zxTicketUserCache 变量分别存储了ticket 和memberId 的映射关系，区别是一个是key 为memberId ， value 为ticket ，一个是key 为ticket ， value 为memberId
 2. 客户端拿到tikcet 后打开浏览器，访问ZxSSOLoginHandshakeImpl 类的handshake() 方法， 在方法里对ticket 进行校验，当通过ticket 可以拿到memberId 的时候，代表这个ticket 是有效的，将这个tikcet 从两个缓存中分别移除，保证ticket 只有一次性有效


## 5、后台自动授权人员功能异常

产生原因： 首先阐明下融云实际没有授权这个概念，只有对用户进行封禁和解封两个状态

 * 对于融云来说，当一个用户第一次请求token 的时候，就默认给他一个注册数（授权） 所以A8 在区分公有云和私有云的时候，其实是控制请求token来做的
 * 公有云在A8 启动的时候会给所有人请求token ，代表全部授权
 * 私有云在A8 启动的时候不会进行请求token ，只有当授权的时候才会对授权人进行请求token

私有云自动授权功能：

 1. 当用户登录致信的时候，会对用户的授权状态进行判断
 2. 当用户已经授权，则判断token 是否存在，存在直接返回token ，不存在向融云请求token 后返回
 3. 当用户未授权，则判断是否开启自动授权功能
 4. 如果开启了自动授权，则自动把他授权且向融云请求token并返回
 5. 如果没有开启自动授权则返回未授权

所以如果自动授权功能异常，问题大概是以下几点：

 1. 注册数满了，无法授权（包含A8 注册数满和融云注册数满）
 2. 向融云请求token 失败

解决方案：

 1. 检查注册数是否满了（包含A8 注册数满和融云注册数满）
 2. 在system 管理员致信管理-人员信息管理 菜单进行刷新token，然后查看 zx.log


## 6、A8启动异常或宕机，日志报出与致信相关的信息

## 6.1 生产环境：

因为致信初始化加载全程用try-catch 捕获，所以不会出现生产环境启动异常的问题

## 6.2 开发环境：

## 6.2.1 启动异常：

产生原因：

 * Spring 加载问题：比如你在Spring 配置文件中声明了bean的加载，但是实际并没有提交这个bean的源文件，就会导致启动异常
 * 数据库加载异常：比如你新增了个一张表，并且针对这个表编写了PO 类和HBM 文件，但是由于SQL 脚本没有提交，导致环境中没有这张表，那么在Hibernate 进行类和表映射的过程中就会导致报错
 * 本地代码和A8 部署环境对不上：比如你的开发代码是最新的，且在你的代码中引了别人的项目的 新类，但是你的A8 部署环境代码比较老，还没有这个新类，就会导致启动失败

解决方案：

 * 查看ctp.log
 * 保证代码和数据库SQL 一起提交
 * 保证开发环境和A8 部署环境代码一致

## 6.2.2 运行异常：

产生原因： 目前遇到过的是老版本因为每 30s 全量获取一次业务消息导致OOM ，主要原因是每次对全部消息进行去toJson 的时候消耗过大，导致了内存溢出 解决方案： 老版本解决方案是降低每次全量获取业务消息的条数，如固定每次只取 150 条，降低toJson 的压力新版本使用时间戳的方式增量获取最新消息


## 7、集团版A8如何能实现一次授权所有单位人员

使用system管理员的 致信管理-私有云设置 菜单的自动授权的功能可以做到间接性一次授权所有单位人员


## 四、Nginx 搭建


## 1、Nginx 安装

Nginx 及安装过程中需要的依赖程序的下载链接参考如下： Nginx，参考下载链接（建议下载stable version）：http://nginx.org/en/download.html nginx-sticky-module，参考下载链接：https://bitbucket.org/nginx-goodies/nginx-sticky-modul e-ng/downloads/ pcre，参考下载链接：https://ftp.pcre.org/pub/pcre/ 所有的安装程序位于/home/soft 下， nginx 的安装目录位于/home/nginx 下，依次执行以下命令进行nginx 的安装（命令中标红的安装包名称，以实际下载的为准）： 安装： 以实际下载的文件格式选择tar或zip解压 解压tar压缩包

tar –zxvf nginx-1.12.1.tar.gz tar –zxvf pcre-8.40.tar.gz


解压zip压缩包

unzip nginx-goodies-nginx-sticky-module-ng-08a395c66e42.zip
``` # 修改解压后文件夹名，便于后续安装
```shell
mv nginx1.12.1 nginx mv pcre-8.40 pcre


mv nginx-goodies-nginx-sticky-module-ng-08a395c66e42 nginx-sticky-module
``` # 赋权文件夹
```shell
chmod –R 777 nginx


进行nginx的configure ```shell cd nginx

注意以下configure命令为一行
```shell
./configure --prefix=/home/nginx --with-http_stub_status_module --with- http_ssl_module --with-http_realip_module --with-http_sub_module --with- http_flv_module --with-http_mp4_module --with-http_random_index_module --with- http_gzip_static_module --with-pcre=/home/soft/pcre --add- module=/home/soft/nginx-sticky-module


编译、安装 make make install


## 2、Nginx 配置



client_max_body_size 10240M;


gzip on;# 开启gzip


1KB以下不进行gzip

 gzip_min_length 1k;


设置gzip的buffer

gzip_buffers 4 16k;


设置gzip的等级，等级越高压缩比例越大，越消耗cpu gzip_comp_level 3; 设置gzip的压缩类型

gzip_types text/xml text/plain text/css text/javascript application/x- javascript application/javascript application/xml application/json;


ie6及以下版本浏览器不进行gzip gzip_disable "MSIE [1-6]."; 定义一个upstream，名称（seeyon_v5_cluster，可更改）、模式（必须为sticky）及其服务 集（server，192.168.0.1为服务ip，80为http端口，以实际情况进行修改）

upstream seeyon_v5_cluster{ sticky;
server 192.168.0.1:80 max_fails=5 fail_timeout=20s; server 192.168.0.2:80 max_fails=5 fail_timeout=20s;
}


定义一个server server {
设置监听端口
listen 80; # 设置server名称
server_name localhost; # 设置字符集
charset utf-8; # 设置location location / {
转发请求至seeyon_v5_cluster，该名称与upstream的名称一致
proxy_pass http://seeyon_v5_cluster; # 设置header的host包含host及port
proxy_set_header Host $host:$server_port; # 设置header的客户端ip为实际ip proxy_set_header X-Real-IP $remote_addr; # 设置header的协议为实际使用的协议
proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for; proxy_set_header X-Forwarded-Proto $scheme;
关闭redirect
proxy_redirect off;
设置超时时间
proxy_connect_timeout 300;
proxy_read_timeout 300;
proxy_send_timeout 300;
}



## 3、Nginx 启动

以nginx 安装在/home/nginx 下为例， nginx 的启动脚本为/home/nginx/sbin/nginx 。启动示例如下：


## 4、参数调优

参数优化需依据nginx的运行情况，及服务器负载情况进行调整。常见的优化参数有以下内容：

 * worker_processes：nginx的进程数，一般为cpu的倍数，可以为1倍
 * worker_rlimit_nofile：nginx的进程打开文件数，可以与ulimit –u的值一致
 * worker_connections：每个进程允许的最多连接数 keepalive_timeout：客户端超时时间，单位秒
 * client_max_body_size：客户端连接的最大请求实体，影响协同系统的上传附件大小，建议设置大 于或等于运行附件上传的最大值
 * access_log：请求日志，建议无需调试时关闭（off）

Nginx 可优化的参数还有很多，建议依据系统实际的运行需求，选择性优化


## 5、启用https配置

启用https 需要购买ca证书（放在/home/nginx/ssl 下），在购买了证书后，对nginx配置文件（nginx.conf ）的server 段进行以下调整：

编撰人：wangywyf、duxf、lichaoj




快速跳转



 * 致信后端开发文档
   * 一、搭建A8教程
     * 1、从 git 上下载 A8 的环境代码
     * 2、连接数据库
       * 2.1 首先通过svn 拿到最新的数据库ALL-IN-ONE 的SQL
       * 2.2 打开Navicat ，新建连接，输入数据库的IP 、 端口 、 用户名 和密码
       * 2.3 新建数据库a8_trunk ，选择UTF-8
       * 2.4 右键数据库a8_trunk ，选择运行SQL 文件，将之前下载的ALL-IN-ONE 文件运行
       * 2.5 执行完成后，点击关闭
       * 2.6 打开A8\v5-resource\conf 的SeeyonConfig.cmd 文件
       * 2.7 选择第二个页签（数据库连接），修改数据库相关参数，然后点击确定进行保存
     * 3、配置致信环境
     * 4、配置调试端口
     * 5、启动A8
   * 二、开发搭建教程
     * 1、环境搭建
       * 1.1 安装 JDK 1.8
       * 1.2 安装IDEA
       * 1.3 配置Maven
         * 1.3.1 Maven安装
         * 1.3.2 IDEA 配置 Maven
       * 1.4 配置远程 Debug
         * 1.4.1 点击 Add Configuration 这个按钮
         * 1.4.2 点击+号，选择Remote
         * 1.4.3 输入A8 的地址和调试端口，点击OK
         * 1.4.4 最后点击此按钮开启调试，此时A8 必须是启动完成状态
     * 2、源码使用
       * 2.1 下载源码
       * 2.2 导入源码到工程
         * 2.2.1 svn 方式
         * 2.2.2 git 方式
     * 3、代码开发
       * 3.1 Spring 规范
         * 3.1.1 Spring 配置文件
         * 3.1.1 Spring Bean使用
         * 3.1.2 SQL 提交流程
         * 3.1.3 PO 类和 HBM 文件定义
         * 3.1.4 DAO 定义
       * 3.2 缓存使用规范
         * 3.2.1 声明缓存变量
         * 3.2.2 缓存使用
         * 3.2.3 跨模块调用
       * 3.3 Controller 使用规范
       * 3.4 Rest 使用规范
     * 4、名词解释
     * 5、致信功能详解
       * 5.1 致信登陆
       * 5.2 致信双击头像打开 A8
       * 5.3 致信穿透业务消息
       * 5.4 致信请求通讯录
       * 5.5 群组操作
       * 5.6 读取加密狗信息
       * 5.7 离职人员的退群等相关逻辑
       * 5.8 机器人消息卡片逻辑
       * 5.9 群组权限、文件收发控制逻辑
       * 5.9.1 全局设置：
       * 5.9.2 单个群组设置：
       * 5.10 第三方消息接收逻辑
       * 5.11 唤醒致信客户端、参数传递相关
       * 5.12 应用中心模块调用逻辑
         * 5.12.1 系统设置：
         * 5.12.2 所有磁贴：
       * 5.13 轻协作相关接口逻辑
         * 5.13.1群任务：
       * 5.14 卡片消息实现逻辑：
       * 5.15 调用融云api向各端进行消息推送的逻辑：
       * 5.16 致信封装并穿透打开 A8 应用的两种方式
         * 5.16.1 通过消息类型来封装、解析应用链接
           * 5.16.1.1 封装、穿透逻辑：
           * 5.16.1.2 通过消息类型去message-link.properties 配置文件中寻找具体url
           * 5.16.1.3 通过消息 url 来解析应用链接
   * 三、客户常见问题以及解决方案
     * 1、A8群成员与融云群成员不同步
     * 2、群成员异常退群
     * 3、部门群问题
     * 4、穿透A8报错，提示无效用户名密码（username is not available）
     * 5、后台自动授权人员功能异常
     * 6、A8启动异常或宕机，日志报出与致信相关的信息
       * 6.1 生产环境：
       * 6.2 开发环境：
         * 6.2.1 启动异常：
         * 6.2.2 运行异常：
     * 7、集团版A8如何能实现一次授权所有单位人员
   * 四、Nginx 搭建
     * 1、Nginx 安装
     * 2、Nginx 配置
     * 3、Nginx 启动
     * 4、参数调优
     * 5、启用https配置



分享链接分享链接

## 104. 致信客开常见问题

> 原始路径：`/40/1115/1182.html`  
> 相对路径：`40/1115/1182.md`

## 致信客开常见问题

注：根目录是 源码的根目录或者致信安装位置的 resources/app 目录


## Q1. 如何更换客户端图标、名称以及窗口中的【致信】字样？


## 1). 客户端图标文件介绍

项目的 根目录/res 目录下，详细介绍如下：

 * app.icns：MacOS 应用图标(1024 * 1024)
 * app.ico：Windows 应用图标, 安装包图标(256 * 256)
 * app.png：Linux 应用图标，任务栏图标，启动页面背景图标(1024 * 1024)
 * bg.png: Mac 安装界面背景(600 * 400)
 * Windows_icon.png: Windows、Linux 托盘图标(64 * 64)
 * Windows_Remind_icon.png：Windows、Linux 托盘闪烁时图标(64 * 64)
 * remind_ZXlogo_normalTemplate@2x.png：Mac 托盘图标(64 * 64)
 * Mac_Remind_icon_white.png：Mac 托盘闪烁时图标(64 * 64)

备注：请分别替换掉上述图标文件，保持命名一样即可。 图标用法请参考https://www.electronjs.org/docs/latest/api/native-image


## 2). 修改客户端名称和图标（基于上方图标介绍）

 * Linux和国产化机器： 项目的 根目录/script/forge.config.js 文件里配置客户端打包信息，如下图：
 * MacOS 和 Windows： 项目的 根目录/src/local_config.json 文件里修改名称、版本号，如下图： 项目的 根目录/src/config.js 文件里修改图标（建议不修改），如下图：


## 3). 修改窗口中显示的【致信】

 * 项目的 根目录/src/locales 文件夹里， 如下文件，修改文件中致信： en.json zh-CN.json zh-TW.json
 * 项目的 根目录/src/modules/page_addr/i18n.js 文件。
 * 项目的 根目录/src/modules/page_addr/index.html 文件。


## Q2. 任务栏图标不显示或修改任务栏的图标？

项目的 项目根目录/src/main.js 找到创建窗口的方法，添加或修改图标，如下图：


## Q3. 修改窗口大小，位置等信息？

项目的 项目根目录/src/main.js 找到创建窗口的方法，参考文档https://www.electronjs.org/docs/latest/api/browser-window，如下图：


## Q4. 修改系统托盘菜单、图标、提示文字？

 * 系统托盘显示如图：
 * 系统托盘修改： 项目根目录/src/modules/tray/tray.set.js 设置托盘提示文字和图标，如下代码:
   
   

const Config = require('../../config.js');
const path = require('path');
const baseDir = path.join(__dirname, '../../../res');
let TrayImg = platform.darwin ? Config.MAC.TRAY : Config.WIN.TRAY; // 根目录/src/config.js 中配置
TrayImg = path.join(baseDir, TrayImg); // 托盘显示图标

let tray = {}
if (appTray) {
tray = appTray
} else {
tray = new Tray(TrayImg);
}

let trayMenu = Utils.getMenu(menus);
tray.on('click', () => {
openMainWindow()
});
tray.on('right-click', () => {
tray.popUpContextMenu(trayMenu)
});
tray.setImage(TrayImg); // 设置图标
tray.setToolTip(Config.MAIN_WINDOW.title); // 设置提示文字

- 登录前的菜单：
项目根目录/src/modules/tray/tray.main.js 设置托盘菜单、闪烁，如下代码:

```javascript
const Config = require('../../config.js');  
const setMenu = require('./tray.set.js')(electron);  
const path = require('path');  
const baseDir = path.join(__dirname, '../../../res');

const TrayImg =  path.join(baseDir, platform.darwin ? Config.MAC.TRAY : Config.WIN.TRAY); // 闪烁图标 根目录/src/config.js 中配置  
const TrayOffImg = path.join(baseDir, platform.darwin ? Config.MAC.TRAY_OFF : Config.WIN.TRAY_OFF); // 闪烁图标 根目录/src/config.js 中配置

const defaultMenus = () => { // 登录前的默认菜单  
    let locale = global.locale;  
    let template = [  
        {  
            label: locale.__('winTrayMenus.Open'), // 打开致信  
            click () {  
                openMainWindow() // 显示窗口  
            }  
        },  
        {  
            type: 'separator'  
        },  
        {  
            label: locale.__('winTrayMenus.Exit'), // 退出  
            click () {  
                app.quit(); // 退出程序  
            }  
        }  
    ];  
    return template;  
};

// 托盘闪烁操作  
const BlinkHandler = {  
    interval: null,  
    set: (enabled) => {  
        if (enabled) {  
            BlinkHandler.start();  
        } else {  
            BlinkHandler.stop();  
        }  
    },  
    start: () => {  
        BlinkHandler.stop();  
        let flag;  
        let iconFile = [ TrayImg, TrayOffImg ];  
        BlinkHandler.interval = setInterval(() => {  
            flag = !flag;  
            // 设置全局 tray 的 icon  
            if (BrowserWindow.tray && BrowserWindow.tray.setImage) {  
                BrowserWindow.tray.setImage(iconFile[ flag ? 1 : 0 ]);  
            }  
        }, 500);  
    },  
    stop: () => {  
        clearInterval(BlinkHandler.interval);  
        BlinkHandler.interval = null;  
        // 设置全局 tray 的 icon  
        if (BrowserWindow.tray) {  
            BrowserWindow.tray.setImage(TrayImg);  
        }  
    }  
};

ipcMain.on('tray-blink', (event, enabled) => {  
    BlinkHandler.set(enabled);  
});


 * 登录后托盘设置： 项目根目录/src/adapt-old.js 搜索 setTrayMenu 方法，设置登录后和锁定时的托盘菜单， 如下:

/**  
 * 设置托盘菜单  
 *  
 * @param {string} type 托盘菜单类型  
 *   
 * Tray 文档地址  
 * https://electronjs.org/docs/api/tray  
 *   
 * PS:执行下面的命令设置托盘菜单  
 *    ZX_CLIENT.setTrayMenu('login')  
 */  
function setTrayMenu(type) {  
  var Tray = ZxDesktop.require('Tray');  
  const locale = remote.getGlobal('locale');  
  var BrowserWindow = ZxDesktop.require('BrowserWindow');  
  var app = ZxDesktop.require('App');

  // 登录之前，和锁定的菜单  
  var loginMenus = [  
    {  
      label: locale.__('winTrayMenus.Open'), 打开致信  
      click: function () {  
        console.log(locale.__('winTrayMenus.Open'))  
        BrowserWindow.show();  
      }  
    },  
    {  
      type: 'separator'  
    },  
    {  
      label: locale.__('winTrayMenus.Exit'), // 退出  
      click: function () {  
        console.log(locale.__('winTrayMenus.Exit'))  
        app.quit();  
      }  
    }  
  ];

  // 登录之后的菜单  
  var loggedMenus = [  
    {  
      label: locale.__('winTrayMenus.Open'), // 打开致信  
      click: function () {  
        console.log(locale.__('winTrayMenus.Open'))  
        BrowserWindow.show();  
      }  
    },  
    {  
      label: locale.__('winTrayMenus.lock'), // 锁定  
      click: function () {  
        console.log(locale.__('winTrayMenus.lock'))  
        ipcRenderer.send('lock-screen');  
      }  
    },  
    {  
      type: 'separator'  
    },  
    {  
      label: locale.__('winTrayMenus.logout'), // 注销  
      click: function () {  
        console.log(locale.__('winTrayMenus.logout'))  
        ZX_CLIENT.setTrayMenu("login")  
        ipcRenderer.send('go-logout');  
      }  
    },  
    {  
      label: locale.__('winTrayMenus.Exit'), // 退出  
      click: function () {  
        console.log(locale.__('winTrayMenus.Exit'))  
        app.quit();  
      }  
    }  
  ];

  switch (type) {  
    case 'login': // 锁定  
      Tray.setMenu({menus: loginMenus});  
      break;

    case 'logged': // 登录后  
      Tray.setMenu({menus: loggedMenus});  
      setLoginAppMenus();  
      break;

    default:  
      break;  
  }  
}



## Q5. 启动致信客户端，配置IP页面，文字不显示 ？

删除 appdata/zhixin/uc.cfg 文件， APPDATA 路径：%APPDATA% Windows 中 $XDG_CONFIG_HOME or ~/.config Linux 中~/Library/Application macOS 中


## Q6. 使用ZX_CLIENT.getMAC()获取mac地址时会出现为null的情况 ？

 * 终端里 cd 到源码所在目录，执行 npm uninstall getmac ；
 * 然后 npm install getmac ， 安装新版本getmac 模块；
 * 修改 文件 \src\modules\system\system.render.js

const mac = require('getmac') // 修改成 ->  
const getMac = require('getmac').default;

// 注释或删除下面代码  
// mac.getMac(function(err, mac) {  
//     if (err) throw err  
//     macAddress = mac;  
// });

deviceId: {  
  get: () => {  
    return macAddress;  
  }  
}

// 修改成 ->  
deviceId: {  
  get: () => {  
    if (!macAddress) {  
      macAddress = getMac();  
    }  
    return macAddress;  
  }  
}


编撰人：wangywyf、duxf、lichaoj


快速跳转



 * 致信客开常见问题
   * Q1. 如何更换客户端图标、名称以及窗口中的【致信】字样？
     * 1). 客户端图标文件介绍
     * 2). 修改客户端名称和图标（基于上方图标介绍）
     * 3). 修改窗口中显示的【致信】
   * Q2. 任务栏图标不显示或修改任务栏的图标？
   * Q3. 修改窗口大小，位置等信息？
   * Q4. 修改系统托盘菜单、图标、提示文字？
   * Q5. 启动致信客户端，配置IP页面，文字不显示 ？
   * Q6. 使用ZX_CLIENT.getMAC()获取mac地址时会出现为null的情况 ？



分享链接分享链接

## 105. 致信客开开发环境说明

> 原始路径：`/40/1115/1183.html`  
> 相对路径：`40/1115/1183.md`

## 致信客开开发环境说明


## 一、致信客户端分两部分（VUE 和 ELectron）：

安装在电脑上的客户端壳，基于Electron开发，可以理解它是一个浏览器。 与操作系统交互的逻辑，都写在Electron项目中，比如数据库操作、文件读写、 截图、开机自动启动、窗口抖动，操作剪贴板之类的。 放在A8服务器上的web页面，基于VUE.js开发，可以理解成为一个网页页面。 致信客户端的用户界面，是一个网页，存放在协同服务器中。但必须由Electron项目中的浏 览器来加载这个页面，因为其中一部分操作数据库、本地文件等等方法，都必须调用Electron暴露的方法，否则报错。


## 二、致信客户端架构：




## 三、致信客户端启动的原理

 1. 用户打开致信客户端（实际为内嵌chrome浏览器的程序）
 2. 致信客户端加载协同服务器地址配置页面（本地安装目录中的一个html页面）
 3. 用户配置完成地址后，加载该地址服务器中的vue项目页面（协同服务器中的一个html页面）
 4. 加载完成，致信打开成功。（配置地址保存到本地，供下次直接加载）


## VUE项目

## 1. 开发环境

npm install
npm run dev(会启动一个本地服务：<ins><https://localhost:8888></ins>) npm run http(会启动一个本地服务：<ins><https://localhost:8888></ins>)




## 2.打包发布

npm run build(会生成一个名为dist2的文件夹)

Electron壳

开发环境搭建

 * 执行 npm install
 * 客户端依赖sqlite3，使用npm install安装会失败，按照下面<sqlite3安装>操作，安装sqlite3
 * 执行 npm run http (会启动程序并加载 http://localhost:8080 页面) 执行 npm run dev (会启动程序并加载 https://localhost:8888 页面)
 * sqlite3安装 -- mac版本 --

1、cd node_modules/sqlite3
2、删除node-modules
3、npm install
4、node-gyp conﬁgure --module_name=node_sqlite3 --module_path=../lib/binding/electron-v1.8-darwin-x64
5、node-gyp rebuild --target=1.8.7 --arch=x64 --target_platform=darwin --dist-url=https://atom.io/ download/electron/ --module_name=node_sqlite3 --module_path=../lib/binding/electron-v1.8- darwin-x64


-- windows 版本 -- 32

1、cd node_modules/sqlite3
2、删除node-modules
3、npm install
4、node- gyp conﬁgure --module_name=node_sqlite3 --module_path=../lib/binding/electron-v1.8-darwin- x86 5、node-gyp rebuild --target=1.8.7 --target_platform=win32 --dist-url=https://atom.io/downlo ad/electron/ --module_name=node_sqlite3 --module_path=../lib/binding/electron-v1.8-win32-ia32


-- windows 版本--64

1、cd node_modules/sqlite3
2、删除node-modules
3、npm install
4、node-gyp conﬁgure -- module_name=node_sqlite3 --module_path=../lib/binding/electron-v1.8-darwin-x64 5、node-gyp rebuild --target=1.8.7 --arch=x64 --target_platform=win64 --dist-url=https://atom.io/download/ele ctron/ --module_name=node_sqlite3 --module_path=../lib/binding/electron-v1.8-win32-x64
打包 -- OS X (需要在MAC的开发模式下打包)
（1）、npm run package:win
（2）、npm run installer:win


-- Windows7+ --

1、npm run package:win


## 一、使用inno setup打包安装包制作目录



 1. app：致信程序文件目录，需要更换致信程序内的图片文件在这个目录中
 2. assistant：致信相关辅助程序文件目录，无需关注
 3. output：安装包程序文件的生成目录，最终的zxsetup.exe生成在这里
 4. req：桌面图标和相关运行时文件目录，需要更换桌面图标需替换app.ico
 5. tmp：安装包所需的图片文件目录，无需关注
 6. dll.iss和zhixin.iss：安装包制作脚本文件

## 二、存放致信可执行程序

 1. 在本地或其它终端找到致信的安装目录，通常可通过桌面快捷方式快速定位，如图
 2. 将安装目录(如上图)中的所有文件夹和文件拷贝到安装包制作目录ZhiXinPackage\app下

## 三、替换图片文件

 1. 进入到app目录，找到resources\app\assets\img，替换需要更换的图片
 2. 进入到app目录，找到resources\app\res，替换需要更换的图片
 3. 进入req目录，替换app.ico来更换桌面快捷方式图标

## 四、生成安装包

 1. 打开Inno Setup5目录中的Compil32.exe
 2. 在Compil32.exe中打开zhixin.iss，也可直接将zhixin.iss拖拽到Compil32.exe窗口中
 3. 编译安装脚本
 4. 生成安装包文件
    编撰人：wangywyf、duxf、het


快速跳转



 * 致信客开开发环境说明
   * 一、致信客户端分两部分（VUE 和 ELectron）：
   * 二、致信客户端架构：
   * 三、致信客户端启动的原理
     * VUE项目
       * 1. 开发环境
       * 2.打包发布
       * 一、使用inno setup打包安装包制作目录
       * 二、存放致信可执行程序
       * 三、替换图片文件
       * 四、生成安装包



分享链接分享链接

## 106. 致信客户端国产化构建打包手册

> 原始路径：`/40/1115/1868.html`  
> 相对路径：`40/1115/1868.md`

## 致信客户端国产化构建打包手册


## 构建条件

## 需要在可以连接互联网的国产化设备上执行，最好不要有各类网络策略限制，易导致软件依赖库文件更新失败，影响后续操作的正常进行和构建打包的成功完成


## 操作步骤&解决方案


## 一、国产化系统更新软件库

## 1：执行：sudo apt-get upgrade

## 2：执行：sudo apt-get install g++

## 3：执行：sudo apt-get install git

## 4：执行：sudo apt-get install dpkg

## 5：执行：sudo apt-get install libgconf*


## 二、国产化系统中安装nodejs环境

## 鉴于国产化OS+CPU组合很多，避免nodejs安装包选择不对导致不可预知问题，建议使用源码编译安装

## 1、打开NodeJs下载官网到下载包路径：https://nodejs.org/dist/v11.15.0/

## 2、下载 node-v11.15.0.tar.gz

## 3、下载完毕后，本地解压源码包，执行：tar -cxvf node-v11.15.0.tar.gz -C ./

## 4、编译源码，执行：./configure

## 5、执行： make （注：此步操作时间较长，通常需要1.5 - 2小时左右）

## 6、执行：sudo make install

## 7、查看node版本：node -v，显示版本为11.15.0


## 三、设置编译依赖源

## npm 设置华为镜像

## 1、执行npm config set registry https://mirrors.huaweicloud.com/repository/npm/

## 2、执行npm config set electron_mirror https://mirrors.huaweicloud.com/electron/


## 四、构建致信客户端安装包

## 1、进入致信源码主目录

## 2、执行：npm install

## 3、执行：npm run make

## 4、在生成的out\ZhiXin\make\deb目录下，会有当前CPU架构对应的子目录，例如：arm架构会生成arm64目录，进入该目录可看到生成的deb文件，即为构建的安装包文件


## 五、构建安装包目录

## 1、在致信官网(http://zhixin.seeyon.com) 下载客户端安装包

## 2、将安装包解压，进入主目录，可以看到deb，install.sh，uninstall.sh，zhixin.desktop和安装说明等文件

## 3、将第四部分生成的安装包deb文件，替换当前目录中的同名deb文件


## 六、安装\卸载客户端

## 1、执行install.sh安装客户端

## 2、执行uninstall.sh卸载客户端

编撰人：duxf


快速跳转



 * 致信客户端国产化构建打包手册
   * 构建条件
     * 需要在可以连接互联网的国产化设备上执行，最好不要有各类网络策略限制，易导致软件依赖库文件更新失败，影响后续操作的正常进行和构建打包的成功完成
   * 操作步骤&解决方案
     * 一、国产化系统更新软件库
       * 1：执行：sudo apt-get upgrade
       * 2：执行：sudo apt-get install g++
       * 3：执行：sudo apt-get install git
       * 4：执行：sudo apt-get install dpkg
       * 5：执行：sudo apt-get install libgconf*
     * 二、国产化系统中安装nodejs环境
       * 鉴于国产化OS+CPU组合很多，避免nodejs安装包选择不对导致不可预知问题，建议使用源码编译安装
       * 1、打开NodeJs下载官网到下载包路径：https://nodejs.org/dist/v11.15.0/
       * 2、下载 node-v11.15.0.tar.gz
       * 3、下载完毕后，本地解压源码包，执行：tar -cxvf node-v11.15.0.tar.gz -C ./
       * 4、编译源码，执行：./configure
       * 5、执行： make （注：此步操作时间较长，通常需要1.5 - 2小时左右）
       * 6、执行：sudo make install
       * 7、查看node版本：node -v，显示版本为11.15.0
     * 三、设置编译依赖源
       * npm 设置华为镜像
       * 1、执行npm config set registry https://mirrors.huaweicloud.com/repository/npm/
       * 2、执行npm config set electron_mirror https://mirrors.huaweicloud.com/electron/
     * 四、构建致信客户端安装包
       * 1、进入致信源码主目录
       * 2、执行：npm install
       * 3、执行：npm run make
       * 4、在生成的out\ZhiXin\make\deb目录下，会有当前CPU架构对应的子目录，例如：arm架构会生成arm64目录，进入该目录可看到生成的deb文件，即为构建的安装包文件
     * 五、构建安装包目录
       * 1、在致信官网(http://zhixin.seeyon.com) 下载客户端安装包
       * 2、将安装包解压，进入主目录，可以看到deb，install.sh，uninstall.sh，zhixin.desktop和安装说明等文件
       * 3、将第四部分生成的安装包deb文件，替换当前目录中的同名deb文件
     * 六、安装\卸载客户端
       * 1、执行install.sh安装客户端
       * 2、执行uninstall.sh卸载客户端



分享链接分享链接

## 107. 致信常见问题解决方案

> 原始路径：`/40/1115/1872.html`  
> 相对路径：`40/1115/1872.md`

## 致信常见问题解决方案


## 一、单机环境部署失败

####注：单机环境部署建议使用新的环境，不能跟别的应用共用，会导致部署失败


## a)服务器环境基础环境要求

## 登录 ROOT 用户进行安装部署。

## 关闭防火墙。

## 命令：systemctl stop firewalld

## 命令：systemctl disable firewalld

## 关闭 SELINUX

## 命令：

## getenforce 是查看selinux状态命令;

## 如果 SELINUX=enforcing（或 SELINUX=permission ）则修改为 SELINUX=disabled

## 通过命令 vi /etc/selinux/config 来修改 SELINUX=disabled，

## 修改后重启操作系统，修改的配置才生效。

## 致信服务器支持的操作系统

## 操作系统类别 详细信息

## Linux CentOS 7.2-7.9_x64 版本

## Red Hat Enterprise Linux 7.2_-7.9_x64 版本

## Ubuntu18或20（server版）

## 查看版本命令：cat /etc/redhat-release




## b)服务器环境不是纯净环境，进行清理，重新部署

注：确保是新的机器，不保留服务器的任何数据

## 命令:

## systemctl stop supervisord

## systemctl stop mysql

## pkill fdfs

## for i in df -h | grep docker| awk '{print $6}' ;do umount $i;done

## rm -rf /usr/lib/systemd/system/mysql.service

## rm -rf /rcloud/*

## rm -rf /opt/*

## rm -rf /etc/my.cnf

## rm -rf /etc/supervisord.conf

## rm -rf /etc/systemd/system/supervisord.service

## sed -i 's/export.*//g' /root/.bashrc

## sed -i 's/.=.//g' /etc/sysctl.conf

## sed -i 's/.*655535//g' /etc/security/limits.conf

## systemctl daemon-reload

## 运行完成以后，需重启服务器，才可以重新部署。


## 二、pc端登录失败


## a)检查协同配置



## 确定部署方式、部署地址（致信内网）、端口配置是否正确，配置完成需重启oa服务


## b)检查system配置



## 确定【PC端访问私有云地址】配置地址为致信服务器内网地址或者公网地址（致信pc端仅内网访问不做配置也可以）


## c)确定人员授权致信是否成功

## 在system-致信管理-人员管理，确定刷新全部是否可以成功。

## 如果刷新失败请确定：

## 1.加密狗与私有云后台的appkey、appsecret是否一致

## 2.确定oa服务器请求致信服务器的8081端口是否开通


## d)使用致信检测工具进行检查（V9.0及以下OA版本）



## 确定致信服务器涉及相关端口是否开通、license授权绑定地址是否正确。

## 致信pc端登录需要客户端能请求到致信服务器8082、8085端口（默认端口，可根据现场情况修改）


## e)在私有云后台（致信服务器ip：8098）查看公网地址是否配置



## 确定该处配置致信服务器地址有客户内网、外网或者域名等地址


## 在登录界面按组合键：ctrl+alt+shift+i 发送研发支持申请单，附带图片




## 三、M3聊天消息无法接受或者发送出去为空


## a)检查协同配置



## 确定部署方式、部署地址（致信内网ip）、端口配置是否正确，配置完成需重启oa服务


## b)检查system配置



## 确定【M3端访问私有云地址】配置地址为致信服务器的内网地址或者公网地址（视M3客户端登录网络情况判断）


## c)确定人员授权致信是否成功

## 在system-致信管理-人员管理，确定刷新全部是否可以成功。

## 如果刷新失败请确定：

## 1.加密狗与私有云后台的appkey、appsecret是否一致

## 2.确定oa服务器请求致信服务器的8081端口是否开通


## d)在私有云后台（致信服务器ip：8098）查看公网地址是否配置



## 确定该处配置致信服务器地址有客户内网、外网或者域名等地址


## e)移动端访问网络要求

## 需要M3移动端所在网络能请求到致信服务器的8082、8043、8070端口（默认），tcp协议常用检测手段telnet


## 四、M3离线推送接收失败


## M3离线推送测试须知：

## 1.确认手机端是否打开了推送通知。

## 2.目前手机推送消息只支持华为/小米/IOS操作系统。

## 3.发送者手机系统不限，但接收者必须是华为/小米/IOS操作系统。

## 4.接收者必须杀死APP进程，然后发送者发送一般聊天信息。

## 5.测试时候不能多端登陆，PC端以及网页端需要退出。

## 6.客户是否能收到一般的聊天消息？


## 排查思路:


## a)私有云管理后台是否有做配置（登录致信服务器ip:8098）




## b)苹果手机收不到推送请检查推送方式是否证书是否过期




## c)致信服务器8070端口是否开通

## 示例：telnet IP 8070


## d)致信服务器出访第三方推送地址是否开通

## 示例：curl -X POST https://api.xmpush.xiaomi.com/v2/message/regid

## 正常返回：



## 致信服务器需要开通以下出访策略：

## 融云PUSH代理（仅苹果）443端口出访：https://push.cn.ronghub.com/api/v1/push

## 苹果PUSH：

## https://api.development.push.apple.com:443

## https://api.push.apple.com:443

## 2）小米PUSH：确保以下域名的 443 端口能够出访

## https://api.xmpush.xiaomi.com

## 3）华为PUSH：确保以下域名的 443 端口能够出访

## https://api.push.hicloud.com

## https://api.vmall.com

## https://login.vmall.com

## https://login.cloud.huawei.com

## https://push-api.cloud.huawei.com

## https://oauth-login.cloud.huawei.com

## 以上验证完成，提供以下信息发送研发支持申请单

## 发送者userid、接收者userid、发送时间、发送内容

## 注：userid获取方式

## 方法1. 在oa的system致信管理、人员管理

## 方法2. 连接OA数据库中，进入org_member表

## 命令：select * from org_member where name= '人员名称'


## 五、内网加外网登录相关配置

## 注：客户端在外网登录，需要把致信服务器的8082、8043、8085、8070端口映射到外网地址上面去


## a)需确定license授权信息是否有加上外网导航地址

## 可登录致信私有云后台首页查看。谷歌浏览器输入：致信IP地址:8098（账户admin，默认密码123456）



## 没有外网地址，请联系商务增加授权地址（测试授权除外）


## b)将外网地址添加到cmp地址中

## 优先级根据前面的顺序添加，端口默认第一条照抄。参考下面截图



## Android PUSH同上




## c)oa的system人员管理更新全部

## 如果刷新失败请确定：

## 1.加密狗与私有云后台的appkey、appsecret是否一致

## 2.确定oa服务器请求致信服务器的8081端口是否开通


## oa的system配置致信服务器外网地址

## PC需要在外网登录就配置pc端访问私有云地址

## M3移动端需要外网登录聊天就配置m3端访问私有云地址



## 注：如果客户PC端内网、外网都需要登录且使用不同的ip地址进行访问，确保以上操作完成后，在“pc端访问私有云地址”填写两个ip地址，使用英文逗号隔开，仅oa版本8.0以上才可以。（客户有域名的话建议内外网都使用客户域名进行访问）


## 六、授权讲解


## a)oa加密狗授权




## b)致信授权




## 七、更新致信服务授权变更

## License：控制导航域名、或导航地址（需提供服务部署地址IP或域名）。

## 识别码：控制最大注册用户数、试用时长（默认3个月，正式购买不涉及试用时长）。

## Appkey及appsecret：认证信息，需加密狗与致信底层服务使用一致

## 客户测试环境转生产环境，需要保留聊天历史记录，实施人员需注意商务提供的appkey是否与之前保持一致，确定授权无问题，依次更新licnese、更新识别码


## a)License更新（最新的致信底层服务版本可以在私有云后台首页直接更新license，更新完成后，重启服务即可）

## 操作人员须知致信私有云后台地址（谷歌浏览器打开致信服务器IP:8098， 操作人员须知admin账户的密码)

## 1、登录私有云管理后台：谷歌浏览器输入致信服务器IP地址:8098（账户admin密码123456）



## 2、点击图中的刷新按钮 -> 填入新申请的 License



## 3、重启rcx服务命令：supervisorctl restart all



## 4、查看地址是否已经更新



## 注：更新完成后需要在oa的system用户 致信管理->人员管理->更新全部


## b)识别码更新

## 操作人员须知致信后台地址（浏览器打开致信服务器IP:8098端口， 操作人员须知admin账户的密码）

## 1、打开浏览器输入致信服务器IP:8098端口， 点击管理后台



## 2、打开后台应用点击查看应用



## 3、点击设置进入APP，更新后可以查看是否更新【到期时间】



## 4、点击【续期】或者点击APP名称后面的【圆圈】刷新



## 5、输入商务提供的最新APP识别码即可



## 6、最后返回应用列表界面可查看是否更新成功（不需要重启服务）



编撰人：duxf


快速跳转



 * 致信常见问题解决方案
   * 一、单机环境部署失败
     * a)服务器环境基础环境要求
       * 登录 ROOT 用户进行安装部署。
       * 关闭防火墙。
       * 命令：systemctl stop firewalld
       * 命令：systemctl disable firewalld
       * 关闭 SELINUX
       * 命令：
       * getenforce 是查看selinux状态命令;
       * 如果 SELINUX=enforcing（或 SELINUX=permission ）则修改为 SELINUX=disabled
       * 通过命令 vi /etc/selinux/config 来修改 SELINUX=disabled，
       * 修改后重启操作系统，修改的配置才生效。
       * 致信服务器支持的操作系统
       * 操作系统类别 详细信息
       * Linux CentOS 7.2-7.9_x64 版本
       * Red Hat Enterprise Linux 7.2-7.9x64 版本
       * Ubuntu18或20（server版）
       * 查看版本命令：cat /etc/redhat-release
     * b)服务器环境不是纯净环境，进行清理，重新部署
       * 命令:
       * systemctl stop supervisord
       * systemctl stop mysql
       * pkill fdfs
       * for i in df -h | grep docker| awk '{print $6}' ;do umount $i;done
       * rm -rf /usr/lib/systemd/system/mysql.service
       * rm -rf /rcloud/*
       * rm -rf /opt/*
       * rm -rf /etc/my.cnf
       * rm -rf /etc/supervisord.conf
       * rm -rf /etc/systemd/system/supervisord.service
       * sed -i 's/export.*//g' /root/.bashrc
       * sed -i 's/.=.//g' /etc/sysctl.conf
       * sed -i 's/.*655535//g' /etc/security/limits.conf
       * systemctl daemon-reload
       * 运行完成以后，需重启服务器，才可以重新部署。
   * 二、pc端登录失败
     * a)检查协同配置
       * 确定部署方式、部署地址（致信内网）、端口配置是否正确，配置完成需重启oa服务
     * b)检查system配置
       * 确定【PC端访问私有云地址】配置地址为致信服务器内网地址或者公网地址（致信pc端仅内网访问不做配置也可以）
     * c)确定人员授权致信是否成功
       * 在system-致信管理-人员管理，确定刷新全部是否可以成功。
       * 如果刷新失败请确定：
       * 1.加密狗与私有云后台的appkey、appsecret是否一致
       * 2.确定oa服务器请求致信服务器的8081端口是否开通
     * d)使用致信检测工具进行检查（V9.0及以下OA版本）
       * 确定致信服务器涉及相关端口是否开通、license授权绑定地址是否正确。
       * 致信pc端登录需要客户端能请求到致信服务器8082、8085端口（默认端口，可根据现场情况修改）
     * e)在私有云后台（致信服务器ip：8098）查看公网地址是否配置
       * 确定该处配置致信服务器地址有客户内网、外网或者域名等地址
     * 在登录界面按组合键：ctrl+alt+shift+i 发送研发支持申请单，附带图片
   * 三、M3聊天消息无法接受或者发送出去为空
     * a)检查协同配置
       * 确定部署方式、部署地址（致信内网ip）、端口配置是否正确，配置完成需重启oa服务
     * b)检查system配置
       * 确定【M3端访问私有云地址】配置地址为致信服务器的内网地址或者公网地址（视M3客户端登录网络情况判断）
     * c)确定人员授权致信是否成功
       * 在system-致信管理-人员管理，确定刷新全部是否可以成功。
       * 如果刷新失败请确定：
       * 1.加密狗与私有云后台的appkey、appsecret是否一致
       * 2.确定oa服务器请求致信服务器的8081端口是否开通
     * d)在私有云后台（致信服务器ip：8098）查看公网地址是否配置
       * 确定该处配置致信服务器地址有客户内网、外网或者域名等地址
     * e)移动端访问网络要求
       * 需要M3移动端所在网络能请求到致信服务器的8082、8043、8070端口（默认），tcp协议常用检测手段telnet
   * 四、M3离线推送接收失败
     * M3离线推送测试须知：
       * 1.确认手机端是否打开了推送通知。
       * 2.目前手机推送消息只支持华为/小米/IOS操作系统。
       * 3.发送者手机系统不限，但接收者必须是华为/小米/IOS操作系统。
       * 4.接收者必须杀死APP进程，然后发送者发送一般聊天信息。
       * 5.测试时候不能多端登陆，PC端以及网页端需要退出。
       * 6.客户是否能收到一般的聊天消息？
     * 排查思路:
     * a)私有云管理后台是否有做配置（登录致信服务器ip:8098）
     * b)苹果手机收不到推送请检查推送方式是否证书是否过期
     * c)致信服务器8070端口是否开通
       * 示例：telnet IP 8070
     * d)致信服务器出访第三方推送地址是否开通
       * 示例：curl -X POST https://api.xmpush.xiaomi.com/v2/message/regid
       * 正常返回：
       * 致信服务器需要开通以下出访策略：
       * 融云PUSH代理（仅苹果）443端口出访：https://push.cn.ronghub.com/api/v1/push
       * 苹果PUSH：
       * https://api.development.push.apple.com:443
       * https://api.push.apple.com:443
       * 2）小米PUSH：确保以下域名的 443 端口能够出访
       * https://api.xmpush.xiaomi.com
       * 3）华为PUSH：确保以下域名的 443 端口能够出访
       * https://api.push.hicloud.com
       * https://api.vmall.com
       * https://login.vmall.com
       * https://login.cloud.huawei.com
       * https://push-api.cloud.huawei.com
       * https://oauth-login.cloud.huawei.com
       * 以上验证完成，提供以下信息发送研发支持申请单
       * 发送者userid、接收者userid、发送时间、发送内容
       * 注：userid获取方式
       * 方法1. 在oa的system致信管理、人员管理
       * 方法2. 连接OA数据库中，进入org_member表
       * 命令：select * from org_member where name= '人员名称'
   * 五、内网加外网登录相关配置
     * 注：客户端在外网登录，需要把致信服务器的8082、8043、8085、8070端口映射到外网地址上面去
     * a)需确定license授权信息是否有加上外网导航地址
       * 可登录致信私有云后台首页查看。谷歌浏览器输入：致信IP地址:8098（账户admin，默认密码123456）
       * 没有外网地址，请联系商务增加授权地址（测试授权除外）
     * b)将外网地址添加到cmp地址中
       * 优先级根据前面的顺序添加，端口默认第一条照抄。参考下面截图
       * Android PUSH同上
     * c)oa的system人员管理更新全部
       * 如果刷新失败请确定：
       * 1.加密狗与私有云后台的appkey、appsecret是否一致
       * 2.确定oa服务器请求致信服务器的8081端口是否开通
     * oa的system配置致信服务器外网地址
       * PC需要在外网登录就配置pc端访问私有云地址
       * M3移动端需要外网登录聊天就配置m3端访问私有云地址
       * 注：如果客户PC端内网、外网都需要登录且使用不同的ip地址进行访问，确保以上操作完成后，在“pc端访问私有云地址”填写两个ip地址，使用英文逗号隔开，仅oa版本8.0以上才可以。（客户有域名的话建议内外网都使用客户域名进行访问）
   * 六、授权讲解
     * a)oa加密狗授权
     * b)致信授权
   * 七、更新致信服务授权变更
     * License：控制导航域名、或导航地址（需提供服务部署地址IP或域名）。
     * 识别码：控制最大注册用户数、试用时长（默认3个月，正式购买不涉及试用时长）。
     * Appkey及appsecret：认证信息，需加密狗与致信底层服务使用一致
     * 客户测试环境转生产环境，需要保留聊天历史记录，实施人员需注意商务提供的appkey是否与之前保持一致，确定授权无问题，依次更新licnese、更新识别码
     * a)License更新（最新的致信底层服务版本可以在私有云后台首页直接更新license，更新完成后，重启服务即可）
       * 操作人员须知致信私有云后台地址（谷歌浏览器打开致信服务器IP:8098， 操作人员须知admin账户的密码)
         * 1、登录私有云管理后台：谷歌浏览器输入致信服务器IP地址:8098（账户admin密码123456）
         * 2、点击图中的刷新按钮 -> 填入新申请的 License
         * 3、重启rcx服务命令：supervisorctl restart all
         * 4、查看地址是否已经更新
         * 注：更新完成后需要在oa的system用户 致信管理->人员管理->更新全部
     * b)识别码更新
       * 操作人员须知致信后台地址（浏览器打开致信服务器IP:8098端口， 操作人员须知admin账户的密码）
         * 1、打开浏览器输入致信服务器IP:8098端口， 点击管理后台
         * 2、打开后台应用点击查看应用
         * 3、点击设置进入APP，更新后可以查看是否更新【到期时间】
         * 4、点击【续期】或者点击APP名称后面的【圆圈】刷新
         * 5、输入商务提供的最新APP识别码即可
         * 6、最后返回应用列表界面可查看是否更新成功（不需要重启服务）



分享链接分享链接

## 108. 【致信】常见问题

> 原始路径：`/40/1115/1894.html`  
> 相对路径：`40/1115/1894.md`

## 【致信】常见问题

模块分类    FAQ标题及地址
登录、消息   致信登录失败和消息收发不成功
登录      客户端登录报错：导航资源错误 30007
登录      致信登录不上，一直显示登录中
登录      致信登录提示：连接协同服务器失败
消息      致信PC端可以收发消息，但M3移动端不行
消息      在群组中发送消息，提示发送失败不在群组中
消息      公有云切换为私有云聊天记录还能否查看
文件      致信是否可以控制上传的文件大小
文件      如何搜索和删除致信上传的文件
白屏      信创环境致信登录显示白屏
搜索      搜索栏内搜索不到通讯录内的人员
加密      致信私有云的聊天记录在服务端和客户端是什么加密方式

编撰人：duxf、lichaoj


快速跳转



 * 【致信】常见问题



分享链接分享链接

## 109. 云联证书安装检查清单及问题处理方案

> 原始路径：`/40/1346/1347.html`  
> 相对路径：`40/1346/1347.md`

## 云联证书安装检查清单及问题处理方案


## 云联证书安装检查清单

OA环境无法安装云联证书，请务必按以下清单进行检查

检查项分类        检查内容                                                                                                    修正说明                                                  检查结果
开发模式检查       检查文件\ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\base\systemProperties.xml中runningMode配置项是否为product   如果runningMode不是product，请修改为product,然后重启OA服务           
开发狗检查        确认是否存在ApacheJetspeed\webapps\seeyon\common\js\ui\                                                       如果存在此文件，则删除后再重启OA服务                                   
             partaletindev.js 文件
证书狗号检查       安装之前确定云联证书是最新生成的，使用文本工具打开云联证书文件，查看文件中 DOGNOS                                                            如果不存在请重新生成云联证书，再次确认，如果还是不存在，说明此证书不属于此单位云联证书，需联系商务处理   
             的数字列表中是否存在OA中的狗号
JDK环境检查      登录OA的system账号系统监控页面，查看JVM信息，确定 JVM Version                                                              目前发现是openjdk 1.8.0_292版本，需要调整到OA版本自带JDK版本             
集群分区指向检查     集群环境下系统分区指向的磁盘路径，多个节点服务必须指向同一个磁盘                                                                        如果每个节点的系统分区不是指向同一个物理磁盘，则需要做磁盘共享或挂载                    
集群路径参数指向检查   集群环境下V8.0及以后版本在SeeyonConfig界面系统参数设置中的 ctp.public.folder                                                 如果每个节点的不是指向同一个物理磁盘，则需要做磁盘共享或挂载                        
             路径也需要指向同一个物理磁盘
磁盘权限检查       上述集群环境下或者单独文件服务器挂载的磁盘路径，请确保OA服务机可以正常访问到，如访问账号密码正确、拥有读写权限                                                请确保能够正常访问、读写正常                                        
系统时间同步检查     如果是集群环境，或者单独做了文件服务器，请检查集群环境下，各个服务节点的操作系统 时间是否同步                                                         V8.0以前版本各个时间差不能超过3秒钟。V8.0及后续版本时间保持高度同步                -


## 常见问题清单及处理方案


## 1 档案数据

此类问题具体原因比较多，其中云联企业ID不一致的占20%，更新云联证书后企业名称不一致的占10% ，此类问题需要项目经理联系协同云运维人员进行排查处理。

## 1.1 应用停止，查看属性提示：与当前系统绑定的云联企业不一致

一般常见于应用包是使用测试狗做的，后来有切换成正式狗，且两个狗对应的云联ID不一致导致。一般在cap.log存在一下记录：

{width="6.3in" height="1.9939796587926508in"}

解决方案：此种情况下需要联系致远项目经理走云联变更，见协同流程表单：《业务应用包授权变更申请》

## 1.2 更新云联证书后客户名称没有更新

解决方案见：附1

## 1.3 云联证书无法生成

使用企业管理员账号登录cloud.seeyon.com，在账号设置中云联企业证书无法生成：



产生原因：

> ① 老客户档案表伙伴编号填写错误，导致加密狗在多个单位了 ② 狗号过期 ③ 更换了加密狗 ④ 未签约伙伴 ⑤ 伙伴和客户单位拆分问题导致 ⑥ 需做云联更名处理

## 1.4 生成证书对应的单位id和狗号列表文件中的单位id不匹配导致

解决方案：协同云档案数据修复

## 1.5 许可单位未找到企业信息

在低版本(V7.1sp1及以前版本)存在数据兼容问题，应用包再没有绑定云联时做的，会提示许可单位未找到企业信息。

解决方案：先导出此应用包，然后更新安装即可。

## 1.6 重新生成云联证书提示：单位狗号列表不存在

> ① 一般是更换了单位之后，生成证书还在之前的单位账号下去生成，需要解绑当前单位更换为新单位。 ② 产品申请未同步，等待同步后，现在可以重新生成证书。

## 1.7 老客户档案狗号问题

老客户档案狗号不正确，老客户档案将不正确的狗号标记为已回退。


## 2 需更新云联证书

> 常见原因： ① OA服务更换了加密狗但未更新云联证书 ② 测试环境使用了最新云联证书但未更新正式环境 ③ 未绑定云联证书 ④ 更新云联证书后没有重启服务


## 3 网络调整

此类问题一般是云联相关插件服务无法使用，如域名无法解析(UnknowHostException：mplus.seeyon.com)，或者无法获取云联票据(get ticket error:java.lang.RuntimeException: com.seeyon.apps.mplus.a.k: q#a error:0x01 )等。

解决方案：在防火墙白名单中添加：cloud.seeyon.com chome.seeyon.com mplus.seeyon.com；确保服务器内部能够访问到这三个地址。 |


## 4 集群分区设置

常见原因：

> ① 调整系统分区，导致云联证书读取异常 ② 集群环境下挂载文件服务器配置异常 ③ 系统分区配置异常 ④ 共享文件访问失败 ⑤ 文件服务器没有读写权限，如在ctp.log下能够找到类似日志： java.io.FileNotFoundException: I:\base1\upload1\2007\01\01\work\lock.lck


## 5 开发模式或使用开发狗

常见于客户在测试环境安装云联证书，发现应用包等无法使用，一般是测试环境使用了开发者模式或者开发狗。

解决方案：

① 检查文件\ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\base\systemProperties.xml中runningMode配置项是否为product，如果runningMode不是product，请修改为product,然后重启OA服务 ② 确认是否存在ApacheJetspeed\webapps\seeyon\common\js\ui\partaletindev.js文件，如果存在此文件，则删除后再重启OA服务


## 6 客开或中间件

常见于使用了apache的commons-codec.jar高版本，导致相关算法被调整导致，或者重写了Base64等算法且类加载优先级较高，导致云联证书加密解密无法正常进行。


## 7 JDK环境

目前发现有些JDK存在算法不完整的情况，如：openjdk 1.8.0_292 、jdk_8u282 Caused by: java.security.UnrecoverableKeyException: Encrypt Private Key failed: unrecognized algorithm name: PBEWithSHA1AndDESede


## 附1： 关于安装云联证书后显示旧企业名称问题

如果企业修改了企业名称，在协同云已经将企业信息进行更新，导出的证书也是正确的，但是在OA绑定证书还查看证书信息的时候还是显示旧的企业名称。这是因为在绑定云联证书时读取的是云联企业信息，但是云联企业信息并没有做名称的更新导致的。目前用户可以手动去云联中心修改，然后重新绑定云联证书即可。

以后遇到此类问题，修改方法如下:


## 登录协同云 [https://cloud.seeyon.com]




## 点击云联中心到云联企业信息管理页面。

修改后然后保存即可。再去协同云个人中心，到账户设置页面，点击云联企业证书




## 然后点击重新生成证书并下载。




## 最后去OA重新绑定云联证书即可。

注：已经安装使用的应用包属性中的企业信息还是会显示原来的企业名称，但是不影响使用。如果要修改，建议导出应用包后，再更新一下即可。



编撰人：xiey


快速跳转



 * 云联证书安装检查清单及问题处理方案
   * 云联证书安装检查清单
   * 常见问题清单及处理方案
     * 1 档案数据
       * 1.1 应用停止，查看属性提示：与当前系统绑定的云联企业不一致
       * 1.2 更新云联证书后客户名称没有更新
       * 1.3 云联证书无法生成
       * 1.4 生成证书对应的单位id和狗号列表文件中的单位id不匹配导致
       * 1.5 许可单位未找到企业信息
       * 1.6 重新生成云联证书提示：单位狗号列表不存在
       * 1.7 老客户档案狗号问题
     * 2 需更新云联证书
     * 3 网络调整
     * 4 集群分区设置
     * 5 开发模式或使用开发狗
     * 6 客开或中间件
     * 7 JDK环境
   * 附1： 关于安装云联证书后显示旧企业名称问题
     * 登录协同云 [https://cloud.seeyon.com]
     * 点击云联中心到云联企业信息管理页面。
     * 然后点击重新生成证书并下载。
     * 最后去OA重新绑定云联证书即可。



分享链接分享链接

## 110. webservice wsdl代码生成位置

> 原始路径：`/40/1939/1940.html`  
> 相对路径：`40/1939/1940.md`

## webservice wsdl代码生成位置


## 需求

咱们产品webservice支持soap11和soap12两种，客户由于使用的接口配置工具，无法进行适配，需要将soap12进行屏蔽，涉及代码开发，需要了解生成wsdl的代码策略。




## 实现逻辑

第一次访问 http://localhost/seeyon/services/accountService?wsdl，会进入CtpAxis2Servlet#init中，对各个service做初始化。

在init初始化每个service中进入如下逻辑：



addService中会进入Utils中对三个endpoint做添加：rest、soap11、soap12。代码如下：

org.apache.axis2.deployment.util.Utils#addEndpointsToService(org.apache.axis2.description.AxisService, org.apache.axis2.engine.AxisConfiguration)





可以看到是通过disableREST、disableSOAP11、disableSOAP12来控制。

所以只要保证每个SpringWebService的参数中有对应的参数控制即可。

做法有两种：

1、com.seeyon.ctp.common.ws.CtpAxis2Servlet#populateCommonParameters中新增默认公共参数（本地验证过是可以屏蔽）



2、在\seeyon\WEB-INF\cfgHome\component\webservice\spring\wso2services.xml每个service中增加参数（本地未验证，不涉及改动代码，现场可以尝试下）。

编撰人：het


快速跳转



 * webservice wsdl代码生成位置
   * 需求
   * 实现逻辑



分享链接分享链接

## 111. 新版本选择模板页面调整需求

> 原始路径：`/40/1948/1949.html`  
> 相对路径：`40/1948/1949.md`

## 新版本选择模板页面调整需求


## 背景&需求

自V9.0开始，新建协同弹出的选择模板页面与旧版本效果不一样了，客户在使用过程中对新的模板页面交互有优化的需求（比如希望新模板每个卡片显示的文字更多），需要知道在哪里修改？






## 解决方案

源码所在位置：cap-front\pc_new_item\src\views\template.vue

参考源码对对应的DOM进行操作即可：



编撰人：het




快速跳转



 * 新版本选择模板页面调整需求
   * 背景&需求
   * 解决方案



分享链接分享链接

## 112. CIP组织机构同步-接口模式

> 原始路径：`/40/2203/2204.html`  
> 相对路径：`40/2203/2204.md`

## CIP组织机构同步-接口模式


## 介绍

 * 官方说明文档见 组织同步
 * 与中间库方式一致，均支持集团、单位、部门、岗位、职务、人员基本信息、人员任职信息、人员兼职信息




## 产品登记

 * {产品编码}自定义录入（建议具备一定含义）
 * {产品名称}自定义录入（建议具备一定含义）
 * {出品公司}自定义录入（建议具备一定含义）




## 应用注册

 * {应用名称}自定义录入（建议具备一定含义）
 * {登记产品编码}选择刚才登记的产品
 * {版本号}选择刚才登记产品的版本号
 * {版本说明}自定义录入（建议具备一定含义）
 * {应用说明}自定义录入（建议具备一定含义）
 * {应用服务商}自定义录入（建议具备一定含义）
 * {接入方式}根据实际情况选择，如需同时支持PC和移动端则选择"PC&移动URL接入应用"




## 创建第三方应用接口库


## 新建分类

 * 选择左侧树中层级，层级名称为"产品登记"中的{产品编码}与{版本号}拼接
 * 新建接口分类，{分类名称}自定义录入（建议具备一定含义）




## 新建接口

说明：新建接口中的动作根据需要多次创建，一般情况下集团、单位、部门是必须的

 * 选择创建的分类名称，点击新建接口



## 录入基本信息

 * {接口名称}自定义录入（建议具备一定含义）
 * {接口描述}自定义录入（建议具备一定含义）
 * {版权所有}自定义录入（建议具备一定含义）



## 录入语义定义

 * {接口访问协议}根据实际情况选择
 * {接口应用类型}根据实际情况选择
 * {接口服务地址}根据实际情况填写
 * {HTTP/Rest/Webservice 接口基础信息}根据实际情况选择



 * 参数设置，根据与接口提供方约定参数名称与类型，是否存在入参等信息。集团接口返回参数{数据类型}使用"JSON"，其他接口使用"JSONArray"，因为集团只会有一个，其他信息对于整个系统来说都应该是批量数据（根据实际情况自行调整）。



 * 数据类型为"JSON"或者"JSONArray"，需要进行格式设置，设置中的字段名称要求与接口字段命名一致




## 同步方案设置

 * {方案名称}自定义录入（建议具备一定含义）

 * {第三方应用}选择应用注册中的应用

 * {同步方式}选择"接口同步"

 * 点击"同步接口绑定"按钮



 * 展开{扩展信息匹配设置}支持将数据同步至主数据中





 * 按照实际情况配置各接口



 * 配置接口中各参数对应关系。注意：人员基本信息的主键字段与人员任职信息中的人员主键、基础信息主键，要求相同，否则人员基本信息无法同步过去（推测是一个BUG）




## 同步初始化

 * 新建初始化配置
 * {同步方案}选择同步方案设置操作中设置的方案
 * {协同组织}根据实际情况选择，需要同步整个集团的信息选择集团。需要同步某个单位的信息选择对应单位
 * {第三方应用组织}根据实际情况选择集团或者单位。此时将会调用集团接口、单位接口，如未出现数据，说明没有正确获取到接口中的集团和单位信息，可能是配置问题，也可能是接口中数据问题等
 * {同步范围}根据实际情况勾选/取消勾选




## 同步操作

 * 勾选同步操作，{同步方式}为手工同步时点击确定立刻触发同步动作。选择定时同步，根据设置定时触发同步操作



 * 同步进行中



 * 同步完成




## 同步日志

 * 查看同步结果




## 示例


## 接口定义

 * 集团



 * 单位



 * 部门



 * 岗位



 * 人员基本信息



 * 人员任职信息




## 接口绑定

 * 集团



 * 单位



 * 部门



 * 岗位





 * 人员基本信息





 * 人员任职信息






## 接口

    @GetMapping("/getGroup")
    public Map<String, Object> getGroup(){
        Map<String, Object> group1 = new HashMap<>();
        group1.put("id", "groupId_1");
        group1.put("name", "三方集团");
        group1.put("code", "group");
        return group1;
    }

    @GetMapping("/getAccount")
    public List<Map<String, Object>> getAccount(){
        List<Map<String, Object>> accountList = new ArrayList<>();
        Map<String, Object> account1 = new HashMap<>();
        account1.put("id", "accountId_1");
        account1.put("name", "单位1");
        account1.put("code", "account1");
        account1.put("groupId", "groupId_1");
        accountList.add(account1);

        Map<String, Object> account2 = new HashMap<>();
        account2.put("id", "accountId_2");
        account2.put("name", "单位2");
        account2.put("code", "account2");
        account2.put("groupId", "groupId_1");
        accountList.add(account2);

        return accountList;
    }

    @GetMapping("/getDepartment")
    public List<Map<String, Object>> getDepartment(){
        List<Map<String, Object>> departmentList = new ArrayList<>();
        Map<String, Object> department1 = new HashMap<>();
        department1.put("id", "depId_1");
        department1.put("name", "部门1");
        department1.put("code", "department1");
        department1.put("accountId", "accountId_1");
        departmentList.add(department1);

        Map<String, Object> department2 = new HashMap<>();
        department2.put("id", "depId_2");
        department2.put("name", "部门2");
        department2.put("code", "department2");
        department2.put("accountId", "accountId_1");
        departmentList.add(department2);

        return departmentList;
    }

    @GetMapping("/getPost")
    public List<Map<String, Object>> getPost(){
        List<Map<String, Object>> postList = new ArrayList<>();
        Map<String, Object> post1 = new HashMap<>();
        post1.put("id", "postId_1");
        post1.put("name", "岗位1");
        post1.put("code", "post1");
        post1.put("accountId", "accountId_1");
        postList.add(post1);

        Map<String, Object> post2 = new HashMap<>();
        post2.put("id", "postId_2");
        post2.put("name", "岗位2");
        post2.put("code", "post2");
        post2.put("accountId", "accountId_1");
        postList.add(post2);

        return postList;
    }

    @GetMapping("getMemberBase")
    public List<Map<String, Object>> getMemberBase(){
        List<Map<String, Object>> memberBaseList = new ArrayList<>();
        Map<String, Object> memberBase1 = new HashMap<>();
        memberBase1.put("id", "memberId_1");
        memberBase1.put("idNum", "12344111");
        memberBaseList.add(memberBase1);

        Map<String, Object> memberBase2 = new HashMap<>();
        memberBase2.put("id", "memberId_2");
        memberBase2.put("idNum", "45655111");
        memberBaseList.add(memberBase2);

        return memberBaseList;
    }

    @GetMapping("getMemberPost")
    public List<Map<String, Object>> getMemberPost(){
        List<Map<String, Object>> memberPostList = new ArrayList<>();
        Map<String, Object> memberPost1 = new HashMap<>();
        memberPost1.put("id", "memberId_1");
        memberPost1.put("name", "张三");
        memberPost1.put("code", "memebrCode1");
        memberPost1.put("depId", "depId_1");
        memberPost1.put("accountId", "accountId_1");
        memberPost1.put("postId", "postId_1");
        memberPostList.add(memberPost1);

        Map<String, Object> memberPost2 = new HashMap<>();
        memberPost2.put("id", "memberId_2");
        memberPost2.put("name", "李四");
        memberPost2.put("code", "memebrCode2");
        memberPost2.put("depId", "depId_1");
        memberPost2.put("accountId", "accountId_1");
        memberPost2.put("postId", "postId_1");
        memberPostList.add(memberPost2);

        return memberPostList;
    }


编撰人：lichaoj


快速跳转



 * CIP组织机构同步-接口模式
   * 介绍
   * 产品登记
   * 应用注册
   * 创建第三方应用接口库
     * 新建分类
     * 新建接口
       * 录入基本信息
       * 录入语义定义
   * 同步方案设置
   * 同步初始化
   * 同步操作
   * 同步日志
   * 示例
     * 接口定义
     * 接口绑定
     * 接口



分享链接分享链接

## 113. 三方中间件适配点

> 原始路径：`/40/2232/2233.html`  
> 相对路径：`40/2232/2233.md`

## 三方中间件适配点

本手册用于开发备案，解决东方通8版本中间件识别错误的问题，别的中间件也可以做类似参考。


## 获取中间件产品信息

产品代码位置：seeyon-util\src\main\java\com\seeyon\ctp\util\ServerDetector.java

该核心类用于判断当前是什么中间件，以便做对应的业务逻辑处理，以东方通为例，代码适配为：

    public static final String TONGWEB_CLASS =  
            "/com/tongweb/cdi/integration/weld/TongwebWeldContainer.class";

    // 东方通7.0.8、东方通8 版本特殊类名标识
    public static final String TONGWEB8_CLASS = "/com/tongweb/server/Container.class";
	
    public static boolean isTongWeb() {  
        ServerDetector sd = _instance;  
  
        if (sd._tongWeb == null) {  
            Class c = sd.getClass();  
  
            if (c.getResource(TONGWEB_CLASS) != null || c.getResource(TONGWEB8_CLASS) != null) {
                sd._tongWeb = Boolean.TRUE;  
            }  
            else {  
                sd._tongWeb = Boolean.FALSE;  
            }  
        }  
  
        return sd._tongWeb;  
    }


编撰人：het


快速跳转



 * 三方中间件适配点
   * 获取中间件产品信息



分享链接分享链接

## 114. 概述

> 原始路径：`/40/2380/2381.html`  
> 相对路径：`40/2380/2381.md`

## 概述


## 实现功能

 * V8通过主动拉取方式同步V5组织信息
 * V8作为门户单点登录至V5
 * V5系统推送事项至V8


## 同步代码

 * studio根据客户名称搜索"V5V8"，找到"客开复用插件：V5V8融合"



 * 得到项目目录"http://gitlab.kk.seeyon.com/customize/KKCJZB202308210001"并访访问



 * 访问gitlab，此部分均为V5系统代码

 * v5、V5V8融合*，均为V5业务部分改造，v5为全量，V5V8融合*为之前根据项目需求适配的部分。根据代码提交记录确认所需内容，如统一待办降版适配文档详见文档

 * apps-v8 为单点登录、监听实现等代码，基于V5平台能力客开的代码实现单点登录、将待办事项推送至V8等能力。（建议：即使仅使用其中一部分能力也全量适配至项目代码中，除非项目组有用足够实力的开发同事配合梳理仅需要的代码）注：低版本V5可能缺少部分监听，导致代码合并后报错，直接删除此部分监听的实现逻辑即可




## 配置技巧

 * Body参数在首层配置数组(对象)





编撰人：lichaoj


快速跳转



 * 概述
   * 实现功能
   * 同步代码
   * 配置技巧



分享链接分享链接

## 115. 组织同步

> 原始路径：`/40/2380/2382.html`  
> 相对路径：`40/2380/2382.md`

## 组织同步


## 说明

 * V8主动调用V5接口拉取组织信息，仅需配置V8系统


## 操作步骤


## 1、创建应用

 * 使用租户账号在后台管理中进入三方应用集成（也可能叫连接器），点击新建





 * 录入基础信息，请求地址需根据实际情况录入




## 2、配置接口

 * 新增一个分类用于存放组织同步所需接口，创建1个认证接口以及分别获取单位、部门、人员接口

（注：认证接口必须存在，由于获取token方式存在多种，如无特殊需求建议使用文档配置方式即可。文档中获取单位、部门、人员接口使用V5平台已提供的对外接口，内容比较全，相对的也比较多，可以根据实际情况考虑V5侧定制开发获取三类数据的接口。字段之间的映射也可根据实际情况调整，需与同步配置中各接口的配置匹配）



## 2.1、配置认证接口





## 2.2、配置获取单位信息接口



 * 要求结构必须一致，配置方式见配置技巧



## 2.3、配置获取部门信息接口



 * 要求结构必须一致，配置方式见配置技巧



## 2.4、配置获取人员信息接口



 * 要求结构必须一致，配置方式见配置技巧




## 3、配置安全认证



 * 使用V5平台创建的rest用户名与密码，创建文档链接



 * Token名称必须设置为"token"

 * Token值选择认证接口返回参数中的id字段

 * V5平台token有效时长大概23分钟，此处设置为20分钟




## 4、同步配置

## 4.1、同步参数配置



## 4.2、同步内容配置

 * 内部根节点根据项目实际情况选择，一般情况下应该是最顶层机构



 * 示例场景使用V5集团版，外部根节点为集团ID默认值"-1730833917365171641"，如V5是企业版使用"670869647114347"

 * 岗位和职级提前建好，使用默认值



 * 排除外部根节点配置的ID



## 4.2.1、机构

 * 组织id对应组织code，副组织id对应父组织code，由于使用的接口未提供这样的结构，仅提供当前单位id与上级单位id，因此将其作为组织code同步至V8，（可考虑自行开发接口）
 * 组织类型使用默认值"INSTITUTION"



 * status设置内容如图



## 4.2.2、部门

 * 请求参数映射页签中录入单位ID，由于此接口是根据单位ID获取部门，存在多个单位的情况下需要多次修改并同步数据。（可考虑自行开发接口）
 * 组织类型使用默认值"DEPARTMENT"





 * status设置内容如图



## 4.2.3、人员

 * 请求参数映射页签中录入单位ID，由于此接口是根据单位ID获取人员，存在多个单位的情况下需要多次修改并同步数据。（可考虑自行开发接口）
 * 人员类型使用默认值"MEMBER"







 * 人员编号默认值配置，配置名称与文档中完全一致的情况下可直接粘贴以下内容，否则根据图中含义自行配置

{
    "type": "__EXPRESS_TOKENS",
    "data": [
        {
            "controlData": null,
            "desc": "条件返回",
            "subOps": [
                [
                    {
                        "uid": "0269cdf3-83ff-42f5-8b49-4e4854c160fb",
                        "type": "FUNCTION",
                        "value": "isNotNull",
                        "desc": "不为空",
                        "subOps": [
                            [
                                {
                                    "uid": "68b5a046-a743-4a01-bb51-f68623df4984",
                                    "type": "VARIABLE",
                                    "value": "code",
                                    "desc": "参数变量.人员编号"
                                }
                            ]
                        ]
                    }
                ],
                [
                    {
                        "uid": "6f1e18e9-a07b-482c-8441-741e21832bfc",
                        "type": "VARIABLE",
                        "value": "code",
                        "desc": "参数变量.人员编号"
                    }
                ],
                [
                    {
                        "uid": "b5553077-7fc8-4cfb-8e41-32194b424659",
                        "type": "VARIABLE",
                        "value": "loginName",
                        "desc": "参数变量.登录名"
                    }
                ]
            ],
            "type": "FUNCTION",
            "uid": "de1ec0c5-aacb-45de-8464-b329954c3bc1",
            "value": "ifs",
            "g_l_index": "1"
        }
    ]
}




 * 性别设置



 * status设置内容如图



## 4.3、运行配置

 * 根据实际需求配置同步时机，示例使用手动同步




## 5、发布应用






## 6、同步



 * 检查日志



编撰人：lichaoj




快速跳转



 * 组织同步
   * 说明
   * 操作步骤
     * 1、创建应用
     * 2、配置接口
       * 2.1、配置认证接口
       * 2.2、配置获取单位信息接口
       * 2.3、配置获取部门信息接口
       * 2.4、配置获取人员信息接口
     * 3、配置安全认证
     * 4、同步配置
       * 4.1、同步参数配置
       * 4.2、同步内容配置
         * 4.2.1、机构
         * 4.2.2、部门
         * 4.2.3、人员
       * 4.3、运行配置
     * 5、发布应用
     * 6、同步



分享链接分享链接

## 116. 单点登录

> 原始路径：`/40/2380/2411.html`  
> 相对路径：`40/2380/2411.md`

## 单点登录


## 说明

 * V8系统作为门户单点至V5系统，单点基于手机号确定人员对应关系，需要提前同步组织信息


## 操作步骤


## V5部分

## 1、CIP应用集成配置

 * 产品登记



 * 应用注册



 * 应用接入，此处的应用编号需要注意，后续将使用





## 2、REST账号配置





## 3、补丁包

 * 同步apps-v8代码，见同步代码

 * 修改"\ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin\cip\spring\spring-v8-sso.xml"文件中"V8地址"部分，替换为实际的v8地址。例如：V8登录页面地址为"http://dev-xtcv8.seeyoncloud.com/login"，value值对应为"http://dev-xtcv8.seeyoncloud.com/service/cip-manager/plug/sso/callback"

 * 秘钥key建议使用示例即可，需要与免登配置中加密因子保持一致

<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xsi:schemaLocation="http://www.springframework.org/schema/beans
           http://www.springframework.org/schema/beans/spring-beans-3.0.xsd"
       default-autowire="byName">
    <bean id="v8sso" class="com.seeyon.ctp.portal.sso.SSOLoginContext">
        <property name="name" value="v8sso" />
        <property name="ticketName" value="ticket" />
        <property name="handshake">
           <bean class="com.seeyon.ctp.portal.sso.V8SSOLogin">
               <!-- V8地址-->
                <property name="url" value="http(s)://{ip}:{port}/service/cip-manager/plug/sso/callback"/>
                <!-- 秘钥key -->
                <property name="key" value="E6C63180C2806DD1F47B859DE501C15F"/>
           </bean>
        </property>
    </bean>
</beans>



## V8部分

## 1、创建应用

 * 见创建应用

## 2、菜单配置



## 3、免登配置

 * 应用编码见CIP应用集成配置

 * 单点登录地址，如OA登录页地址为"http://10.2.178.5:30318/seeyon/main.do"，则配置为"http://10.2.178.5:30318"

 * REST信息见REST账号配置

 * 加密因子见补丁包，xml配置中的"秘钥key"



## 4、角色授权

 * 按照如图操作配置角色与菜单关系，角色根据实际情况选择











## 5、发布应用

 * 见发布应用

## 6、功能验证

 * 确保用于验证的V8人员手机号与V5人员手机号匹配







编撰人：lichaoj




快速跳转



 * 单点登录
   * 说明
   * 操作步骤
     * V5部分
       * 1、CIP应用集成配置
       * 2、REST账号配置
       * 3、补丁包
     * V8部分
       * 1、创建应用
       * 2、菜单配置
       * 3、免登配置
       * 4、角色授权
       * 5、发布应用
       * 6、功能验证



分享链接分享链接

## 117. 事项同步

> 原始路径：`/40/2380/2416.html`  
> 相对路径：`40/2380/2416.md`

## 事项同步


## 说明

 * V5系统事项数据推送至V8系统
 * 支持协同、公文、会议、新闻、公告、调查


## 操作步骤


## V5部分

## 1、CIP应用集成配置

 * 见CIP应用集成配置

## 2、REST账号配置

 * 见REST账号配置

## 3、补丁包

 * 见补丁包

 * 除链接中的配置外，还需要如下配置

 * 修改"\ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin\cip\spring\spring-v8-cip.xml"文件，V8的openapi地址、V8的能力id、V8的openapi-key、V8的openapi-secret，4个属性的value值获取方式见接入应用配置、事项同步、API权限设置,以示例的情况配置出来的xml内容为

		<!-- V8的openapi地址 -->
		<property name="openApiUrl" value="http://dev-xtcv8-openapi.seeyoncloud.com"/>
		<!-- V8的能力id -->
		<property name="capabilityId" value="319418659649249470"/>
		<!-- V8的openapi-key -->
		<property name="appKey" value="acf7d1d7cba941d28dfc4c77949b5727"/>
		<!-- V8的openapi-secret -->
		<property name="secretKey" value="51d0ceac5da3402d8eb2a448192f3b9a" />


<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
	   xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	   xsi:schemaLocation="http://www.springframework.org/schema/beans
           http://www.springframework.org/schema/beans/spring-beans-3.0.xsd"
	   default-autowire="byName">
	
	<!-- V8  openApi -->
	<bean id="openApiClient" class="com.seeyon.cip.OpenApiClient">
		<!-- V8的openapi地址 -->
		<property name="openApiUrl" value="{openApiUrl}"/>
		<!-- V8的能力id -->
		<property name="capabilityId" value="{capabilityId}"/>
		<!-- V8的openapi-key -->
		<property name="appKey" value="{appKey}"/>
		<!-- V8的openapi-secret -->
		<property name="secretKey" value="{secretKey}"/>
		<!-- 消息过滤 应该就是 应用接入名称，用于双向集成过滤，单向集成请设置为空 -->
		<property name="msgFilterString" value="" />
	</bean>
	<bean id="v5BpmEventListener" class="com.seeyon.cip.V5BpmEventListener"></bean>
	<bean id="v8OtherEventListener" class="com.seeyon.cip.V8OtherEventListener"></bean>
	<bean id="v5OrgEventListener" class="com.seeyon.cip.V5OrgEventListener">
		<property name="orgSynStart" value="1"/>
		<property name="memberCodeMapper" value="code"/>
	</bean>
	<bean id="v5Message" class="com.seeyon.cip.V5Message"></bean>
	<bean id="retryRecordManager" class="com.seeyon.apps.retry.manager.RetryRecordManagerImpl">
		<!-- 推送V8定时补偿间隔（分钟），建议设置10,20,30 -->
		<property name="quartzMinute" value="30"/>
		<!-- 重试次数 -->
		<property name="retryCount" value="3"/>
	</bean>
	<bean id="retryRecordQuartz" class="com.seeyon.apps.retry.task.RetryRecordQuartz"></bean>
</beans>



## V8部分

## 1、创建组织映射

 * 按照如图方式创建人员映射





## 2、开放平台配置

 * 进入开放平台菜单



## 2.1、API管理配置



## 2.2、新建接入应用



## 2.3、接入应用配置

 * 查看接入应用详情



 * 在凭证与基础信息页签查看AppKey与AppSecret的值，用于配置spring-v8-cip.xml中的{appKey}和{secretKey}



## 2.4、API权限设置



 * 查看api接口地址，用于配置spring-v8-cip.xml中的{openApiUrl}





## 3、免登配置

 * 见免登配置

 * 在链接文档配置外，还需要如下配置



## 4、组织同步

 * 见组织同步

 * 在链接文档配置外，人员同步配置中需要增加如下配置



## 5、事项同步

 * 新建事项同步





 * 启用事项同步

 * 查看同步能力编码，用于配置spring-v8-cip.xml中的{capabilityId}



## 6、发布应用

 * 见发布应用

## 7、同步

 * 见同步

 * 检查用户映射



## 8、功能验证

 * V5系统给用户映射列表中的人员发送一条协同数据，V8系统登录可在待办事项快捷入口中看到推送数据，并可点击穿透打开







编撰人：lichaoj




快速跳转



 * 事项同步
   * 说明
   * 操作步骤
     * V5部分
       * 1、CIP应用集成配置
       * 2、REST账号配置
       * 3、补丁包
     * V8部分
       * 1、创建组织映射
       * 2、开放平台配置
         * 2.1、API管理配置
         * 2.2、新建接入应用
         * 2.3、接入应用配置
         * 2.4、API权限设置
       * 3、免登配置
       * 4、组织同步
       * 5、事项同步
       * 6、发布应用
       * 7、同步
       * 8、功能验证



分享链接分享链接

## 118. 事项同步

> 原始路径：`/40/2380/2525.html`  
> 相对路径：`40/2380/2525.md`

## 事项同步


## 说明

 * V5系统消息数据推送至V8系统


## 操作步骤


## V5部分

## 1、CIP应用集成配置

 * 见CIP应用集成配置

## 2、REST账号配置

 * 见REST账号配置

## 3、补丁包

 * 见补丁包

 * 除链接中的配置外，还需要如下配置

 * 修改"\ApacheJetspeed\webapps\seeyon\WEB-INF\cfgHome\plugin\cip\spring\spring-v8-cip.xml"文件，V8的openapi地址、V8的能力id、V8的openapi-key、V8的openapi-secret，4个属性的value值获取方式见接入应用配置、消息同步、API权限设置,以示例的情况配置出来的xml内容为

		<!-- V8的openapi地址 -->
		<property name="openApiUrl" value="http://dev-xtcv8-openapi.seeyoncloud.com"/>
		<!-- V8的能力id -->
		<property name="capabilityId" value="319418659649249470"/>
		<!-- V8的openapi-key -->
		<property name="appKey" value="acf7d1d7cba941d28dfc4c77949b5727"/>
		<!-- V8的openapi-secret -->
		<property name="secretKey" value="51d0ceac5da3402d8eb2a448192f3b9a" />


<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
	   xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	   xsi:schemaLocation="http://www.springframework.org/schema/beans
           http://www.springframework.org/schema/beans/spring-beans-3.0.xsd"
	   default-autowire="byName">
	
	<!-- V8  openApi -->
	<bean id="openApiClient" class="com.seeyon.cip.OpenApiClient">
		<!-- V8的openapi地址 -->
		<property name="openApiUrl" value="{openApiUrl}"/>
		<!-- V8的能力id -->
		<property name="capabilityId" value="{capabilityId}"/>
		<!-- V8的openapi-key -->
		<property name="appKey" value="{appKey}"/>
		<!-- V8的openapi-secret -->
		<property name="secretKey" value="{secretKey}"/>
		<!-- 消息过滤 应该就是 应用接入名称，用于双向集成过滤，单向集成请设置为空 -->
		<property name="msgFilterString" value="" />
	</bean>
	<bean id="v5BpmEventListener" class="com.seeyon.cip.V5BpmEventListener"></bean>
	<bean id="v8OtherEventListener" class="com.seeyon.cip.V8OtherEventListener"></bean>
	<bean id="v5OrgEventListener" class="com.seeyon.cip.V5OrgEventListener">
		<property name="orgSynStart" value="1"/>
		<property name="memberCodeMapper" value="code"/>
	</bean>
	<bean id="v5Message" class="com.seeyon.cip.V5Message"></bean>
	<bean id="retryRecordManager" class="com.seeyon.apps.retry.manager.RetryRecordManagerImpl">
		<!-- 推送V8定时补偿间隔（分钟），建议设置10,20,30 -->
		<property name="quartzMinute" value="30"/>
		<!-- 重试次数 -->
		<property name="retryCount" value="3"/>
	</bean>
	<bean id="retryRecordQuartz" class="com.seeyon.apps.retry.task.RetryRecordQuartz"></bean>
</beans>



## V8部分

## 1、创建组织映射

 * 按照如图方式创建人员映射





## 2、开放平台配置

 * 进入开放平台菜单



## 2.1、API管理配置



## 2.2、新建接入应用



## 2.3、接入应用配置

 * 查看接入应用详情



 * 在凭证与基础信息页签查看AppKey与AppSecret的值，用于配置spring-v8-cip.xml中的{appKey}和{secretKey}



## 2.4、API权限设置



 * 查看api接口地址，用于配置spring-v8-cip.xml中的{openApiUrl}





## 3、免登配置

 * 见免登配置

 * 在链接文档配置外，还需要如下配置



## 4、组织同步

 * 见组织同步

 * 在链接文档配置外，人员同步配置中需要增加如下配置



## 5、消息同步

 * 新建消息同步





 * 启用消息同步

 * 查看同步能力编码，用于配置spring-v8-cip.xml中的{capabilityId}



## 6、发布应用

 * 见发布应用

## 7、同步

 * 见同步

 * 检查用户映射



## 8、功能验证

 * V5系统给用户映射列表中的人员发送一条协同数据，V8系统登录可在我的消息中看到推送数据，并可点击穿透打开



编撰人：lichaoj


快速跳转



 * 事项同步
   * 说明
   * 操作步骤
     * V5部分
       * 1、CIP应用集成配置
       * 2、REST账号配置
       * 3、补丁包
     * V8部分
       * 1、创建组织映射
       * 2、开放平台配置
         * 2.1、API管理配置
         * 2.2、新建接入应用
         * 2.3、接入应用配置
         * 2.4、API权限设置
       * 3、免登配置
       * 4、组织同步
       * 5、消息同步
       * 6、发布应用
       * 7、同步
       * 8、功能验证



分享链接分享链接

## 119. 前端技术

> 原始路径：`/1842/`  
> 相对路径：`1842/README.md`

子菜单名称          URL
前端快速开始         前端快速开始
JSP前端开发规范      JSP前端开发规范
JSP UI组件       JSP UI组件
JSP 业务组件       JSP 业务组件
VUE前后端分离组件     VUE前后端分离组件
主要模块和前端代码位置    主要模块和前端代码位置
ES6转ES5注意事项    ES6转ES5注意事项
Vue工程本地调试及定位   Vue工程本地调试及定位
流版签组件和解决方案     流版签组件和解决方案

分享链接分享链接

## 120. 技术平台

> 原始路径：`/1842/167.html`  
> 相对路径：`1842/167.md`

## JSP前端UI组件库

SeeyonUI前端组件资源和组件库列表：

组件库            内容                           链接
SeeyonUI 2.0   面向JSP前端开发，含统一的图标库，支持与3.0混用   链接
SeeyonUI 3.0   面向JSP前端开发，含统一的图标库，支持与2.0混用   链接
SeeyonUI 4.0   面向JSP前端，适用于V8.0以上版本          链接

编撰人：admin、het


快速跳转



 * JSP前端UI组件库



分享链接分享链接

## 121. JSP前端UI组件库

> 原始路径：`/1842/167.html`  
> 相对路径：`1842/167.md`

## JSP前端UI组件库

SeeyonUI前端组件资源和组件库列表：

组件库            内容                           链接
SeeyonUI 2.0   面向JSP前端开发，含统一的图标库，支持与3.0混用   链接
SeeyonUI 3.0   面向JSP前端开发，含统一的图标库，支持与2.0混用   链接
SeeyonUI 4.0   面向JSP前端，适用于V8.0以上版本          链接

编撰人：admin、het


快速跳转



 * JSP前端UI组件库



分享链接分享链接

## 122. ES6转ES5工具使用教程

> 原始路径：`/1842/169.html`  
> 相对路径：`1842/169.md`

## ES6转ES5工具使用教程


## 一、背景

由于部分功能（如：weboffice）在开发过程中使用了es6语法，如：async/await、解构赋值（...）、let 等。但各浏览器对es6语法的支持差异较大，特别是在IE11及以下浏览器，直接使用含es6的语法的文件时，页面会出现空白，所以需要将相关文件通过“es6转es5工具”进行语法转换。


## 二、影响工程及版本

影响版本：V8.0SP2LTS及以上

影响工程：

工程名称                     模块中文名称
apps-bulletin            公告
apps-collaboration       协同
apps-common              通用组件
apps-doc                 文档中心
apps-edoc                公文
apps-meeting             会议
apps-news                新闻
apps-plan                计划
apps-vreport             报表
ctp-workflow-component   工作流
apps-aiedoc              智能公文


## 三、适合人群

以上受影响的工程，在给客户出前端js补丁包的时候，不允许直接出源码！需要通过编译服务自动进行ES5转换。

1、如果你是依托研发内部的CICD平台进行编码，则无需手动操作，只需等CICD（自动ES6转ES5）编译结果使用即可

2、如果你是依托ctp-studio客开管理平台进行代码管理，则一定要使用ctp-studio平台进行编译，编译后的文件自动做了ES6到ES5的转换

3、如果你没有平台，只有产品源码，则一定要用手动进行ES6转ES5，本文档适合这类人群


## 四、使用教程


## 环境前提

前提：本机需要安装Node.js，需要安装Node.js，需要安装Node.js（网上大把教程自行安装，无版本要求，但建议使用最新的版本）


## Windows使用教程

1、下载解压ES6转ES5工具 （es62es5-npm.zip），解压后文件目录结构如下图：



2、将需要转换的文件或者目录放置在default文件夹中的src文件夹下，如下图所示：（放置了一个baseOffice的js文件）

（注意：工具只会对js文件进行转换，非js文件不会做转换，部分忽略的特征文件及目录也不会做转换）



3、然后双击根目录下名为start的批处理文件，如下图所示：



4、双击后会弹出一个cmd控制台界面，执行es6转es5的操作，如下图所示：



5、cmd控制台执行完后会自动退出，转换后的文件名不变，并在default/src目录下为每个文件生成一个同名的map文件（注意：由于转换后原文件内容会被替换，如果需要保留原文件，请先拷贝原文件再执行转换）。如下图所示：



6、然后使用转换后的文件给客户出补丁包


## Mac使用教程

1、下载解压ES6转ES5工具（es62es5-npm.zip），解压后文件目录结构如下图：



2、将需要转换的文件或者目录放置在default文件夹中的src文件夹下，如下图所示：（放置了一个baseOffice的js文件）



3、然后在终端执行start.sh文件

cd 到 es62es5-npm 目录，然后使用 ls 命令，展示文件夹下的文件结构，其中含有start.sh文件。如下图：



然后执行start.sh文件，使用命令：./start.sh

若出现以下提示，说明缺少权限



先cd到es62es5-npm文件夹上层目录

然后执行命令：sudo chmod -R 777 es62es5-npm

输入电脑登录密码

再 cd 到 es62es5-npm 目录

然后执行命令：./start.sh

(命令过程如下图，以及界面的内容展示)



4、终端执行完后，转换后的文件名不变，并在default/src目录下为每个文件生成一个同名的map文件（注意：由于转换后原文件内容会被替换，如果需要保留原文件，请先拷贝原文件再执行转换）。如下图所示：



5、然后使用转换后的文件给客户出补丁包


## 五、忽略的特征文件及目录



编撰人：admin、het


快速跳转



 * ES6转ES5工具使用教程
   * 一、背景
   * 二、影响工程及版本
   * 三、适合人群
   * 四、使用教程
     * 环境前提
     * Windows使用教程
     * Mac使用教程
   * 五、忽略的特征文件及目录



分享链接分享链接

## 123. JSP前端开发规范

> 原始路径：`/1842/170.html`  
> 相对路径：`1842/170.md`

## JSP前端开发规范


## JSP文件规范

1、文件目录：jsp文件放到WEB-INF各插件目录下：

{projectName}/src/main/webapp/WEB-INF/jsp/[ctp|apps]/{module}/abcList.jsp


2、文件命名：遵循camel命名风格,尽量遵循Controller的方法名和jsp名称一致

//good addUser.jsp userList.jsp

//bad add_user.jsp userlist.jsp


3、禁止在JSP中写java代码，尽量把JSP当作纯html使用：

4、jsp页面注释使用：<%-- 被注释的内容 --%>

5、Javascript文件引用：js文件保持和jsp同名文件放在{projectName}/src/main/webapp/[apps_res|common]/{module}/abcList.js

> css文件同理

6、禁止在页面使用seeyon作为静态文件上下文，引用V5标准模板后，可以通过${path}来代替seeyon硬编码：

<!--good code-->
<link rel="stylesheet" href="${path}/apps_res/{module}/css/xxx.css${ctp:resSuffix()}">
<script type="text/javascript" src="${path }/apps_res/{module}/js/xxx.js${ctp:resSuffix()}"></script>

<!--bad code-->
<link rel="stylesheet" href="seeyon/apps_res/{module}/css/xxx.css${ctp:resSuffix()}">
<script type="text/javascript" src="seeyon/apps_res/{module}/js/xxx.js${ctp:resSuffix()}"></script>



## JSTL表达式

JSTL属于后端技术，底层是执行Java代码。

原则上，新jsp页面不允许使用JSTL全部标签，通过html+Javascript均能代替相关能力。

曾经使用过JSTL的JSP页面，也只允许使用JSTL core、JSTL fmt 和JSTL functions的部分tag，不允许使用JSTL sql和JSTL XML。

允许使用的tag列表

1. c:out
2. c:url
3. c:forEach & c:if
4. fmt:message



## CTP EL表达式

ctp EL表达式是V5平台按照jstl规范，自定义的el表达式，定义申明文件在WEB-INF/tld/ctp.tld文件中，用法都是以${ctp:xxx()}形式使用


## CTP EL常用表达式

不推荐使用涉及Java对象操作的CTP EL表达式，操作不符合前后端分离规范。

推荐使用静态化执行的CTP EL表达式，对前后端分离影响相对小一些。

表达式                  示例                                                   说明
i18n(_[1~5])         ${ctp:i18n("abc.bcd")} ${ctp:i18n("abc.bcd1",123)}   推荐，国际化
formatDate           ${ctp:formatDate(date)}                              不推荐，需要对java对象进行转换，yyyy-MM-dd
formatDateTime       ${ctp:formatDateTime(date)}                          不推荐，需要对java对象进行转换，yyyy-MM-dd HH:mm
toHTML               ${ctp:toHTML(string)}                                不推荐，需要对java对象进行转换，将字符串转换成HTML，将对\r \n < > & 空格进行转换
toHTMLAlt            ${ctp:toHTMLAlt(string)}                             不推荐，需要对java对象进行转换，将字符串转换成HTML,不包括 \n
toHTMLWithoutSpace   ${ctp:toHTMLWithoutSpace(string)}                    不推荐，需要对java对象进行转换，将字符串转换成HTML，将对\r \n < > & 空格不进行转换
showMemberName       ${ctp:showMemberName(memberId)}                      不推荐，需要对java对象进行转换，显示人员姓名
hasPlugin            ${ctp:hasPlugin(pluginName)}                         推荐，判断是否包含某个插件
resSuffix            ${ctp:resSuffix()}                                   推荐，静态资源时间戳后缀
csrfSuffix           ${ctp:csrfSuffix()}                                  推荐，CSRF请求后缀


## jsp全局变量（推荐使用）

变量名    示例        说明
path   ${path}   当前应用上下文


## 扩展：为什么不推荐使用EL？

不推荐新的JSP中使用原生EL表达式、JSTL表达式，不推荐原因有二：

 1. EL表达式是渲染页面时执行，极易引发反射型和存储型XSS
 2. 尽量少的EL表达式代码编写，利于后续JSP->html迁移，降低前后端分离代价
 3. 更清晰的职责，前端就是前端、后端就是后端，方便做职责分离，也更适合现在的开发模式

如果老代码，已经在JSP中使用EL表达式，建议参考安全篇，对EL表达式中的变量进行XSS防护。

针对不同场景，我们也有相应EL表达式的替换方案。

场景一：而编写js的<script>代码块嵌入了EL表达式，则是XSS攻击的源头。

<html>
<head>
</head>
<body>
</body>
<script type="text/javascript">
 function init(){
   // Bad Code ： 如下通过原生EL引入的id和title变量极易引发XSS攻击
   var id = ${id};
   var title = ${title};
   // Nice Code：改用Javascript直接获取URL中的变量
   var queryParams = getQueryParams();
   var id = queryParams.id;
   var title = queryParams.title;
 }

 /**
 * 获取url后边的参数实现原理 注：此方法平台已经封装好，业务组调用即可
 * @returns
 */
function getQueryParams(){
 var search = location.search;
    var param = {};
    if (search.length > 0) {
        var strs = search.split("?")[1].split("&");
        for (var i = 0; i < strs.length; i++) {
         var con = strs[i].split("=");
            param[con[0]] = decodeURIComponent(con[1]);
        }
    }
 return param;
}
</script>

<%-- Nice Code：推荐通过src的形式引入Javascript --%>
<script type="text/javascript" src="apps_res/{module}/js/xxx.js"></script>
</html>


场景二：JSP中的html标签，value值直接用EL表达式获取，也是XSS攻击源头。

<%-- Bad Code以下写法都不再推荐 --%>
<input type="text" value="${demo.title}">
<input type="hidden" value="${demo.name}">
<%-- 如果要对某些文本字段赋值，请使用AJAX的形式获取数据后，再通过Javascript对DOM赋值。 --%>



## V5标准JSP模板

如果编写一个新的JSP页面，我们推荐使用CTP标准的JSP模板，通过如下模板配置，能够使用CTP JSP前端组件的各种特性，并且保持浏览器最大兼容性。

    <%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
    <!DOCTYPE html>
    <html class="over_hidden h100b">
    <head>
     <%@include file="/WEB-INF/jsp/common/common_header.jsp"%>
     <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge" />
     <meta name="renderer" content="webkit">
     <title>${ctp:i18n("文件标题") }</title>
     <link rel="stylesheet" href="${path}/apps_res/{module}/css/xxx.css${ctp:resSuffix()}">
    </head>
    <body class="over_hidden h100b">

    </body>
    <%@include file="/WEB-INF/jsp/common/common_footer.jsp"%>
    <script type="text/javascript" src="${path }/apps_res/{module}/js/xxx.js${ctp:resSuffix()}"></script>
    </html>



## 关于common_header.jsp

common_header.jsp是V5基于JSP提供的标准模板，适合放在JSP页面<head>标签里，主要标准化内置了：${path}上下文变量、平台CSS样式。




## 关于common_footer.jsp

common_footer.jsp也是标准模板，适合放在JSP页面</body>标签后面，主要标准化内置了：Javascript可使用的V5公共变量、SeeyonUI组件库。




## EClipse和IDEA设置默认模板

开发人员可以在自己的IED开发工具中预置默认的JSP模板方便直接调用：






## SeeyonUI前端组件

V5提供了基于JSP的各种平台UI前端组件，前面标准JSP引入规范编写代码后即可使用这些UI组件做功能开发。

详细的组件引用方法参考站内>技术平台>前端技术>JSP前端组件库。




## js前端压缩组件

平台提供了启动压缩Javascript文件的能力，可以将一批js压缩成一个xx.min.js文件使用。

Javascript压缩清单：/ctp-common/src/main/webapp/common/compressconfig/compressconfig.xml

    <!-- 新建协同 -->
    <js>
        <inputfile><![CDATA[/common/js/orgIndex/jquery.tokeninput.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/js/newCollaboration.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/js/project_select.js]]></inputfile>
        <inputfile><![CDATA[/common/js/template/templateApi.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/js/dealNodeCommon.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/atwho/js/jquery.atwho.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/atwho/js/jquery.caret.js]]></inputfile>
        <outputfile isObscure="false"><![CDATA[/apps_res/collaboration/js/newCollaboration-all-min.js]]></outputfile>
    </js>
    <!-- 处理协同 -->
    <js>
        <inputfile><![CDATA[/apps_res/uc/rongcloud/chat.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/js/comment.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/js/componentPage.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/doc/js/knowledgeBrowseUtils.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/js/summary.js]]></inputfile>
        <inputfile><![CDATA[/common/waterMark/js/waterMark.js]]></inputfile>
        <inputfile><![CDATA[/common/isignaturehtml/artDialog/dialog-min.js]]></inputfile>
        <inputfile><![CDATA[/common/workflow/allocation/manualAllocation.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/atwho/js/jquery.atwho.js]]></inputfile>
        <inputfile><![CDATA[/apps_res/collaboration/atwho/js/jquery.caret.js]]></inputfile>
        <outputfile isObscure="false"><![CDATA[/apps_res/collaboration/js/summary-jsp-min.js]]></outputfile>
    </js>
    <!-- 正文编辑器 -->


Javascript压缩后端实现逻辑：/ctp-portal/src/main/java/com/seeyon/ctp/portal/util/SeeyonCompressorUtils.java

如何判断压缩成功？从ctp.log日志中能看到如下信息表示压缩成功。

INFO: SeeyonCompressorUtils: - 启动时开始压缩配置的js和css
......
INFO: SeeyonCompressorUtils: - 压缩配置的js和css结束


压缩成功后的效果，在对应文件目录能看到一个xxx.min.js文件

如何判断压缩失败？从ctp.log日志中看到“启动压缩js和css时出错”并且有异常堆栈则说明压缩失败！需要根据错误信息寻找对应代码行检查代码准确性。


## Javascript代码最佳实践

javascript模块化的第一条规则：一个模块不应该为全局名字空间添加多于一条的标记.通俗的讲：除了给全局命名空间定义一个模块的命名空间，其它的你一句代码都不要写

1、防止全局变量被覆盖

2、减少全局变量个数

//js文件名和命名空间名保持一致
//全局变量和函数保存在命名空间中
//Collaboration.js

var Collaboration;

if(!Collaboration) Collaboration = {};//第一级域名

Collaboration.xxx = xxx;//变量

Collaboration.函数名1=function(){  //函数

}

//---------------------------------------------------------------------------------------

//如果js文件名相同，则需要将不同的js放到不同的目录，则需要定义多级

var com;

if(!com) com={};//如果com不存在，则新生成一个

else if(typeof com!="object"){//如果已存在，但不是一个对象，则抛出一个异常

   throw new Error("com already exists and is not an object");
}

if(!com.util) com.util={};//如果com.util不存在则新生成一个

else if(typeof com.util!="object"){//如果com存在，但不是一个对象，则抛出一个异常

    throw new Error("com.util already exists and is not an object");
}

if(!com.util.Collaboration){//如果com.util.ModuleClass存在，则直接抛出异常

    throw new Error("com.util.Collaboration already exists");
}
com.util.Collaboration = {//在com.util.Collaboration不存在的情况下，我们才能正常使用在此命名空间下定义的代码

    函数1:function(){ 函数体;},

    函数2:function(){ 函数体;}

};


编撰人：het


快速跳转



 * JSP前端开发规范
   * JSP文件规范
   * JSTL表达式
   * CTP EL表达式
     * CTP EL常用表达式
     * jsp全局变量（推荐使用）
     * 扩展：为什么不推荐使用EL？
   * V5标准JSP模板
     * 关于common_header.jsp
     * 关于common_footer.jsp
     * EClipse和IDEA设置默认模板
   * SeeyonUI前端组件
   * js前端压缩组件
   * Javascript代码最佳实践



分享链接分享链接

## 124. 1、相关函数

> 原始路径：`/1842/576/577.html`  
> 相对路径：`1842/576/577.md`

## 1、相关函数

1、流程制作-增加节点：designerCallAddNodeItem

2、流程制作-替换节点：designerCallReplaceNode

3、流程制作-节点属性：designerCallSelectPolicy

4、老选人：panel.js=>selectOneMember -> selectOne -> add2List3


## 2、相关页面jsp

(1) 流程制作 1、流程制作-页面：workflowDesigner.jsp

2、流程制作-复制流程弹窗页面：WorkflowTemplateList4Clone.jsp

3、流程制作-单击节点-节点属性弹窗：setWorkflowNodeProperty.jsp

4、流程制作-单击节点-节点属性的策略说明(?按钮)：workflowPolicyExplain.jsp

5、流程制作-单击节点-节点属性的表单字段：dateFormField.jsp

6、流程制作-单击节点-节点属性的查看消息：messageRuleDetail.jsp

7、流程制作-单击节点-节点属性的消息设置：simpleRuleList.jsp

8、流程制作-单击节点-节点属性的审批规则设置：IntelligentAuditSuperNodeSetting.jsp

9、流程制作-单击节点-节点属性的节点匹配说明(?按钮)：workflowShowMatchScopeExplain.jsp

10、流程制作-单击节点-节点属性的合并处理设置说明(?按钮)：showMergeDealExplain.jsp

11、流程制作-单击节点-子流程节点设置：editSubProcessSetting.jsp

12、流程制作-单击节点-子流程节点设置-子流程制作人：workflowSelectSubProcessCreator.jsp

13、流程制作-单击节点-子流程节点设置-选择子流程：workflowSelectTemplate.jsp

14、流程制作-单击节点-触发新流程：workflowTriggerNewProcess.jsp

15、流程制作-单击节点-触发新流程-点击选择触发条件：workflowAutoBranchSetting.jsp

16、流程制作-单击节点-触发新流程-点击选择触发条件-下方自动条件页面：workflowOrgBranchSetting.jsp

17、流程制作-单击节点-触发新流程-点击选择触发条件-下方自动条件页面-单击条件列表选项：workflowOrgBranchSelectOrg.jsp

18、流程制作-单击节点-触发新流程-点击选择触发条件-下方表单条件页面：workflowFormBranchSetting.jsp

19、流程制作-单击节点-触发新流程-点击选择触发条件-下方表单条件页面-包含：workflowFormBranchIExcludeFunction.jsp

20、流程制作-单击节点-触发新流程-点击选择触发条件-下方表单条件页面-in：in_func.jsp

21、流程制作-单击节点-触发新流程-点击选择触发条件-下方表单条件页面-extend(单选)：formulaextend.jsp

22、流程制作-单击节点-触发新流程-点击选择触发条件-下方表单条件页面-extend(多选)：formulaextend_multi.jsp

23、流程制作-单击节点-触发新流程-点击选择触发条件-下方表单条件页面-明细表一行：workflowFormBranchExistSlave.jsp

24、流程制作-单击节点-触发新流程-点击选择触发条件-下方表单条件页面-自定义函数：workflowFormBranchExistSlave.jsp

25、流程仿真页面：simulationMain.jsp

26、流程仿真页面-用例列表：list.jsp

27、流程仿真页面-用例详情：newSimulation.jsp

28、流程仿真页面-报告详情：reportDetail.jsp

29、流程仿真页面-报告详情-单击节点查看节点属性：workflowShowNodeProperty.jsp

30、选择节点执行人页面：showWorkFlowMatchResultPage.jsp

31、选择节点执行人页面-查看原因页面：showCanotAutoSkipMsgPage.jsp

32、应用定制平台-运维中心-节点查询与替换：processTemplateSuperviseIndex.jsp

33、应用定制平台-运维中心-节点查询与替换-选择系统停用节点：wfEnabledPeople.jsp

34、应用定制平台-运维中心-节点查询与替换-选择表单：templateManagementCenter.jsp

35、应用定制平台-运维中心-节点查询与替换-选择模板：templateChooseM.jsp

36、应用定制平台-运维中心-节点查询与替换-批量修改流程：processTemp.jsp

37、应用定制平台-运维中心-节点查询与替换-批量修改执行模式：processTemplateSuperviseReplace.jsp

38、发起协同-调用模板-查看流程-流程预测：workflowPrediction.jsp

39、发起协同-调用模板-查看流程-查看超级节点属性：workflowShowSuperNodeProperty.jsp

编撰人：yinyanting、liuyc




快速跳转



 * 1、相关函数
 * 2、相关页面jsp



分享链接分享链接

## 125. 背景

> 原始路径：`/1842/576/622.html`  
> 相对路径：`1842/576/622.md`

## 背景

选人控件是单独项目工程，不与任何项目工程耦合，这是为了保持选人控件的相对独立，新选人控件是通过ctp-organization\src\main\webapp\common\js\selectOrgSdk-debug.js 中间SDK方式供业务调用，整个选人入口通过open方法调用。


## 设计模式

新选人组件基础框架使用vue@2.5.17， 采用vuex统一管理已选数据，整体交互采用左右联动模式，点击左侧复选框后右侧已选区会加入已勾选的内容，同时左侧内容要显示勾选，若对左侧取消勾选则右侧同时取消该条内容。


## 所属项目工程

项目工程： ctp-selectorg-front




## 主入口文件




## 所有的页签都放置在以下文档目录中：

ctp-organization-front\src\views\organization\common\selectOrg\tabs


## 布局组件放置在如下目录

ctp-organization-front\src\views\organization\common\selectOrg\components


## 右侧公共组件、滚动加载数据组件、切换单位组件右侧公共组件、滚动加载数据组件、切换单位组件

ctp-organization-front\src\components\scrollList\index.vue api：放置选人控件的接口

assets：静态icon-font的js缓存

css：静态公共css文件

directive：全局指令

filters：全局过滤方法

panels: 所有页签组件

store：全局状态管理中心

utils：全局公共方法

views：主入口js、主入口模板 基本左右布局组件：simpleLayout.vue

基本带上下移动按钮三栏布局组件：topBottomLayout.vue

树形结构组件： transforTree.vue

客开代理组件：customBox.vue 选人业务组件有右侧已选区choolist

选人平铺组件scrollList

选人图标组件：svgIcon

切换单位组件：teamSelect


## 特殊页签说明

如图：customListTab.vue和customTreeTab.vue是自定义选人配置后所需的页签组件。

特殊说明：自定义选人组件中的树使用的是baseBusinessTree.vue组件




## 选人控件与自定义选人控件区别

a：有无compCode，有是自定义选人控件，否则是标准选人控件

b：自定义选人不适配业务场景参数，标准选人控件会适配业务参数，业务会根据不同参数控制标准选人控件显示，但是自定义选人组件不会除了特定一个参数外不做其他更多业务场景的适配，它是根据配置态适配业务场景。

c：自定义选人基于标准选人控件，自定义选人控件是基于标准的选人控件数据产生，没有使用标准选人控件时就不能使用自定义选人功能。


## 项目启动方法：

npm run serve:org_common_selectOrgConfig


因为选人配置使用最新的fiber.js前端库，启动方式依赖Vue/cli 脚手架。


## 调试方法主要分三步调试方法主要分三步

第一步：配置server地址

配置文件在ctp-organization-front\config\devServer.js

第二步：启动项目

第三步：使用启动后的localhost地址调试

## 选人配置主入口文件：

ctp-organization-front\src\views\organization\selectOrgConfig\selectOrgConfigMain.js

## 选人主出口html:

ctp-organization-front\dist\seeyon\apps_res\organization\common\selectOrg.html

## 选人根节点组件：

ctp-organization-front\src\views\organization\common\selectOrgApp.vue

## 选人配置态中分为：

自定义选人组件、自定义选人范围两个部分，

## 自定义选人组件入口：

ctp-organization-front\src\views\organization\selectOrgConfig\pages\configInfo.vue

## 自定义选人范围入口：

ctp-organization-front\src\views\organization\selectOrgConfig\pages\scopeConfigInfo.vue

## 自定义选人组件在业务中使用位置：

公文管理-基础设置-选人定制 页面设计中心-页面管理-选人定制 应用定制平台-应用管理中心-基础数据-选人定制

编撰人：yinyanting、liuyc




快速跳转



 * 背景
 * 设计模式
 * 所属项目工程
 * 主入口文件
 * 所有的页签都放置在以下文档目录中：
 * 布局组件放置在如下目录
 * 右侧公共组件、滚动加载数据组件、切换单位组件右侧公共组件、滚动加载数据组件、切换单位组件
 * 特殊页签说明
 * 选人控件与自定义选人控件区别
 * 项目启动方法：
 * 调试方法主要分三步调试方法主要分三步
   * 选人配置主入口文件：
   * 选人主出口html:
   * 选人根节点组件：
   * 选人配置态中分为：
   * 自定义选人组件入口：
   * 自定义选人范围入口：
   * 自定义选人组件在业务中使用位置：



分享链接分享链接

## 126. seeyonUi 组件

> 原始路径：`/1842/576/905.html`  
> 相对路径：`1842/576/905.md`

## seeyonUi 组件

## 1.组件文档地址

https://open.seeyon.com/seeyonui/V4.0/

## 2.代码工程

ctp-ui

## 3. 代码结构

ctpUi dist --构建生成压缩后的代码 docCss --文档的一部分代码 docs --文档的一部分代码 src --开发代码 images js -- tsc 执行生成的js代码 scss ts --主要代码 common excludes lang ui --主要代码 ui_old Gruntfile.js -- grunt 构建执行文件 package -- 依赖文件 tsconfig.json -- typescript 配置文件 4. 构建命令

ctpUi目录层 在终端打开 执行tsc 将 ts代码 编译成js代码 编译成js代码 执行grunt default 只编译js部分的代码

      执行grunt  scss  只编译scss文件

       执行grunt all  编译全部内容



## 老组件 -1

## 1.文档地址

https://open.seeyon.com/seeyonui/V3.0

https://open.seeyon.com/seeyonui/V2.0

## 2. 代码结构

js

- calendar

- scheduler

- seeEditorTable

- searchBox-debug.js

- seeyon.ui.calendar-debug.js

- seeyon.ui.checkform-debug.js

- seeyon.ui.colorPanel-debug.js

- seeyon.ui.comLanguage-debug.js

- seeyon.ui.common-debug.js

- seeyon.ui.dialog-debug.js

- seeyon.ui.grid-debug.js

- seeyon.ui.jcrop-debug.js

- seeyon.ui.layout-debug.js

- seeyon.ui.menu-debug.js

- seeyon.ui.peopleCrad-debug.js

- seeyon.ui.print-debug.js

- seeyon.ui.print-iframe-debug.js

- seeyon.ui.progress-debug.js

- seeyon.ui.shortCutSet-debug.js

- seeyon.ui.tab-debug.js

- seeyon.ui.timeline-debug.js

- seeyon.ui.toolbar-debug.js

- seeyon.ui.tree-debug.js


编撰人：liuyc


快速跳转



 * seeyonUi 组件
   * 1.组件文档地址
   * 2.代码工程
   * 3. 代码结构
 * 老组件 -1
   * 1.文档地址
   * 2. 代码结构



分享链接分享链接

## 127. 文化建设

> 原始路径：`/1842/576/906.html`  
> 相对路径：`1842/576/906.md`

## 文化建设

## 一、业务介绍

业务入口：首页菜单-文化建设

新闻、公告、讨论、调查 都是通过单位管理员来分配权限的，它们的业务逻辑也都差不多，一般员工是一般只有查看、收藏权限，拿新闻模块为例，一般员工点进新闻模块，页面长这个样子：

登录单位管理员之后可以给指定用户分配发布和审核权限。如下图：

得到审核和发布权限之后，点进新闻版块儿，页面长这样：


## 二、工程代码

文化建设相关工程清单PC端：

 1. apps-bulletin  公告

 2. apps-news   新闻

 3. apps-inquiry   调查

 4. apps-bbs  讨论

这四个模块的工程结构和业务逻辑大差不差，基本上是以下结构：

## 移动端工程：

新闻：mplus-front/news 公告：mplus-front/bulletin 调查：mplus-front/inquiry 讨论：mplus-front/bbs

编撰人：liuyc




快速跳转



 * 文化建设
   * 一、业务介绍
 * 二、工程代码
   * 移动端工程：



分享链接分享链接

## 128. 1、报表中心

> 原始路径：`/1842/576/907.html`  
> 相对路径：`1842/576/907.md`

## 1、报表中心

## 1、业务介绍

报表分类：查询、单表统计、多表统计、静态报表，每种报表可以自定义数据源、标题、排序、穿透、数据字段等

查询报表 =》普通列表，显示数据字段如图一 统计报表 =》可以设置行表头、列表头作为统计项统计如图二



## 2、工程相关

报表设置页签，左侧和右侧设置，整体页面框架在report_design工程，内部查询、统计列表嵌入iframe

工程地址：http://gitlab.seeyon.com/cap/cap-front.git 报表整体框架页面路径: cap-front\report_design\src\views\reportDesign\reportList 查询工程: pc端: cap-front\pc_query 移动端: cap-front\m_query 统计工程: pc端: cap-front\pc_statistics_new 移动端: cap-front\m_statistics_new

## 3、开发调试

pc_query工程调试: 查看package.json需要启动哪种模板，执行命令，这里我启动npm run serve:0,代表启动query-0模板，启动后进入OA系统=>报表设置=>控制台查询当前iframe=>右键 Open in new tab新标签也打开如图三=>去掉浏览器url 中seeyon到?中间的字符如图三，刷新页面=>本地调试





report_design工程调试:

因为报表设置页面有很多弹框页面 之前都是使用的V5弹框 是一个一个页面组成的 不方便vue调试 这里最好使用 vue-remote-devtools 详见 Vue远程调试 vue-remote-devtools 的使用 - 简书 (jianshu.com)

全局安装 vue-remote-devtools 打开图中的注释 运行 vue-devtools 在调试完毕后，一定需要之前打开的注释再加上！！！


## 2、无流程

## 1、业务介绍

无流程指cap无流程表单里的一种样式列表，配置如下

## 2、工程相关

工程地址：http://gitlab.seeyon.com/cap/cap-front.git 无流程工程路径: pc端: cap-front\pc_unflow 移动端: cap-front\m_unflow

## 3、开发调试

## 1、模板开发

在代码工程cap-front中找到pc_unflow工程，在src目录下找到views，这里面就是系统中的所有无流程表单模板，这里面只有默认模板（unflow-0）会随项目打包自动更新内容，其他的模板都需要我们自己重新打包-> 更新测试商城 -> 提测 -> 走组件上新过程到正式商城。 安装依赖需要在cap-front下的 pc_unflow pkg_condition component_doc 文件夹下分别都安装依赖 首先我们开发的所有模板都是基于unflow-0项目来，所以我们开始复制一个文件夹unflow-0,这里注意无流程模板的文件夹都是以’unflow-‘开始的。 然后在复制的文件夹里修改我们的内容。这里注意：在index.vue文件中我们必须引入allMixins以及tableMixin，这两个文件是公共必须的文件。文件中的一些方法我们可以使用，同时我们也可以在我们文件重写，注意名称保持一致。 在images中的cover.png文件名字固定的，图片可以换，这个是展示在模板使用中的设置部分的背景图。 在config.json中内容是栏目开发中的内容。参考栏目开发中的配置项。 在package.json中添加我们对应的启动命令。（"serve:你的模板名称": "vue-cli-service serve --你的模板名称"） 在vue.config.js中添加我们新的模板对应的命令，将红框部分复制一份换成我们新模板对应的打包命令名称以及文件路径即可。 打包使用npm run lib然后选择对应的模板打包，然后在配置的地方导入模板即可





## 2.模板调试

首先启动我们项目npm run serve:你的模板名称 登录系统，找到一个无流程模板 f12打开调试面板。在element中找如图iframe，右键选择open in new tab。 在面板中看到如图页面，去掉红框的内容访问页面。这样我们就可以进行本地调试了。



## 3.模板使用

进入菜单 选择一个应用，进入应用 在上侧的菜单中选择门户设置 在弹框中点击默认模板PC 在pc Tab中就是模板，红色框就是无流程的两个模板，鼠标移入，点击使用就可以了







编撰人：liuyc




快速跳转



 * 1、报表中心
   * 1、业务介绍
   * 2、工程相关
   * 3、开发调试
 * 2、无流程
   * 1、业务介绍
   * 2、工程相关
   * 3、开发调试
     * 1、模板开发
     * 2.模板调试
     * 3.模板使用



分享链接分享链接

## 129. 一、业务介绍

> 原始路径：`/1842/576/908.html`  
> 相对路径：`1842/576/908.md`

## 一、业务介绍



知识社区主要是收录了各个体系的知识文档和视频文件，每个公司员工都可以进入查看学习，但是有的文档是有阅读权限的，如果想要获取浏览权限，需要联系对应的管理员去开通权限。查看文档管理信息：知识社区-文档管理库：




## 二、工程代码

git 工程地址

PC端：http://gitlab.seeyon.com/cwp/apps-doc

移动端：http://gitlab.seeyon.com/mplus/mplus-front/doc

目前，问题出现的集中点在 PC 端的 文档中心 这一块儿，对应到工程中的代码是 apps-doc/src/main/webapp/apps_res/doc/ 目录下的 js 文件以及 apps-doc/src/main/webapp/WEB-INF/jsp/appa/doc/ 目录下的 jsp 文件。



编撰人：liuyc




快速跳转



 * 一、业务介绍
 * 二、工程代码



分享链接分享链接

## 130. 工程代码说明

> 原始路径：`/1842/576/909.html`  
> 相对路径：`1842/576/909.md`

## 工程代码说明

1、代码库git地址：http://gitlab.seeyon.com/ctp/ctp-common.git 2、代码路径说明： /src/main/webapp/common/ckeditor。 /src/main/webapp/common/ckeditor413。


## 代码版本说明：

1、ie8使用ckeditor。 2、ie8以上及其他浏览器使用ckeditor413。 3、最新代码已合并ckeditor和ckeditor413，即在所有浏览器上都只存在一个版本ckeditor413。


## 核心代码说明

1、剪切板（复制/粘贴核心处理代码）： ckeditor-source.js line:12647：CKEDITOR.plugins.add(“clipboard”)处起始行。 重点关注：起line:12686止line:12735。正文数据粘贴过滤处理代码。 2、编辑器字体/字号添加： config.js。 在font和fomtfamily相关代码中添加。 3、图像上传/编辑插件： 代码：plugins/image/dialogs/image.js。 4、复制/粘贴插件： 5、代码：plugins/pastetools/filter/common.js。

编撰人：liuyc




快速跳转



 * 工程代码说明
 * 代码版本说明：
 * 核心代码说明



分享链接分享链接

## 131. 1 表单设计态

> 原始路径：`/1842/576/911.html`  
> 相对路径：`1842/576/911.md`

## 1 表单设计态

## 工程：

cap-front/form-design

## 表单设计：

form-design\src，启动命令是npm run dev ，打包命令npm run buildSeeyon

## 操作设置：

form-design\others\src\authDesign，启动命令是npm run devo ，打包命令npm run buildo

## 业务列表设置：

cap-core

## 运行调试：

（1）安装依赖(在form-design层级运行npm i）

（2）代理服务器

cap-front\form-design\bin\common-dev.js

target：代理目标地址

Cookie：将登录后的代理地址的Cookie复制替换

然后运行



运行后，将代理地址的设计器页面url index.html后的复制下来，放到运行本地工程的地址后就可以调试了

## 表单设计 （ip）/index.html?





## 操作设置 （ip）/authDesign.html?




## 2、表单运行态：

## 工程：

cap-front

## 项目文件：

cap-front/pc_form

## 调试方法

1、在cap-front/pc_form项目工程中使用 npm run dev 启动项目

2、在运行态把iframe中的地址copy一下，新开一个浏览器页签，使用localhost/[copy_url]

## 暴露给业务的方法

CAP4表单控件暴露给客开的js在 cap-front\pc_form\static\js\redirectApi.js

CAP4表单的状态可以通过setFieldData方法更改

## 明细表、明细表高级设置

明细表、明细表高级设置（表头有筛选项）是两套不同的代码实现逻辑

明细表入口文件： pc_form\src\components\drawTable\index.vue

明细表高级设置表入口文件：pc_form\src\components\drawListTable\index.vue

提示：运行态明细表、明细表高级设置【新增】【删除】【复制】是通过后端接口返回的数据做渲染

## CAP4控件-能否编辑

1、先看后端接口 form/createOrEdit 接口返回数据中对应的auth 是否有问题？ 2、后端的【auth】有问题，让后端处理，如果没有问题继续看第3点 3、查看标准代码控件对应的组件是否渲染有问题？cap4控件path：cap-front\pc_form\src\components\widgets 4、标准代码控件没有问题，定位暴露给客开的setFieldData方法是否被调用？一般情况下，标准组件没有修改控件的编辑的权限，99%的可能是客开通过setFieldData修改。

## CAP4控件-大写控件未更新修改方法

在8.1sp1之前的版本：

修改文件是 cap-front\pc_form\src\mixins\handlerData.js 文件中的backfillFormControlData 方法

  // 自定义控件数据回填
    backfillFormControlData(params, formmainName) {
        const { fillBackControlData } = this;
        const _self= this;
        let changeFields = {};
        // 阻止计算
        this.limitCalculate = true;
        // 处理回填的是Array还是Object
        if (Array.isArray(params)) {
            params.forEach((item, index) => {
                fillBackControlData(item, changeFields, formmainName);
            });
        } else if (Bridge.checkDataType(params, 'Object')) {
            fillBackControlData(params, changeFields, formmainName);
        }
        // 将这句话注释掉，就可以解决
        //if(Object.keys(changeFields).length > 0){ 
            // 全表计算
            setTimeout(() => {
                // 释放计算锁
                _self.limitCalculate = false;
                _self.allTableCalculate({}, 
                Object.keys(changeFields), formmainName);
            }, 10);
        //}
    },


## CAP4控件-自定义控件渲染异常修改方法

cap4中选人自定义控件的文件在： pc_form\src\mixins\loadControl.js

renderFormComponents 方法

问题：在form表单中使用中发现配置条件后表单控件出现渲染错误等问题，可以使用以下方法解决：

fieldCustomV2组件渲染时绑定key，同时给fieldCustomV1组件渲染时绑定key

 <fieldCustomV2
 key={data.Xkey}
 data={data}
 formmainName={formmainName}
 formdata= 
 {drawInitData.currentFormData}
 formDetails={getCurrentTableDateils}
 formSave={formSave}
 currentRight={currentRightId}
></fieldCustomV2>

 <fieldCustomV1
 key={data.Xkey}
 data={data}
 formmainName={formmainName}
 formdata={drawInitData.currentFormData}
 formDetails={getCurrentTableDateils}
 formSave={formSave}
 currentRight={currentRightId}
 onBackfillFormControlData={
 this.BackfillFormControlData
 }
 onBackfillFormAttachment={
 this.backfillFormAttachment
 }
 onBackfillFormUpdateData={
 this.backfillFormUpdateData
 }
 ></fieldCustomV1>


## cap4表单附件不能预览修改方法

cap4表单预览使用_previewType方法

cap-front\pc_form\src\mixins\utils\form-controlWork.js

// 查看控件业务关系
    _previewType(...args) {
        let [iType, type, params, index, attType] = args;
        if (attType === "img") {
            const datas = [];
            params.attachmentInfo.attachmentInfos.forEach((v, i) => {
                const t = v.filename.split(".");
                if (iType.indexOf(t[t.length - 1].toLowerCase()) >= 0) {
                    datas.push({
                        src: `${Config._ctxPath()}/fileUpload.do?method=showRTE&fileId=${v.fileUrl}&createDate=${v.createdate}&type=image&showType=big`,
                        originalsrc: `${Config._ctxPath()}/fileUpload.do?method=showRTE&fileId=${v.fileUrl}&createDate=${v.createdate}&type=image`
                    });
                    if (i === index) {
                        index = datas.length - 1;
                    }
                }
            });
            Config.currentWindow.$.touch({
                id: new Date().getTime(),
                datas,
                currentIndex: index || 0
            });
        } else if (attType === "pdf") { 
            const currentFile = params.attachmentInfo.attachmentInfos[index];
            // 不支持office在线转换,走以前的逻辑
            if(currentFile.isWpsOnlineEnable === '0'){
                let url = `${Config._ctxPath()}/fileDownload.do?method=doDownload4Office&type=Pdf&isOpenFile=true&fileId=${currentFile.fileUrl}&createDate=${currentFile.createdate}&filename=${encodeURIComponent(currentFile.filename)}&v=${currentFile.v}${Config.urlSurffix}`;
                Config.currentWindow.addattachDialog = null;
                Config.currentWindow.addattachDialog = Config.currentWindow.$.dialog({
                    title: $.i18n("officeTrans.view.label"),
                    transParams: { parentWin: window },
                    url,
                    width: 1280,
                    height: 800
                });
            }else{
                let url = `${Config._ctxPath()}/officeTrans.do?method=view&fileId=${currentFile.fileUrl}&createDate=${currentFile.createdate}&filename=${encodeURIComponent(currentFile.filename)}&v=${currentFile.v}${Config.urlSurffix}`;
                this.$refs.myFormIframe.src = url;
            }
        } else {
            const file = params.attachmentInfo.attachmentInfos[index];
            const viewUrl = `${Config._ctxPath()}/officeTrans.do?method=view&fileId=${file.fileUrl}&createDate=${file.createdate}&v=${file.v}&filename=${encodeURI(file.filename)}`;
            this.$refs.myFormIframe.src = viewUrl;
        }
    },


## 修改公共组件后打包流程

第一步：进入m_index先执行npm run buildSeeyon

第二步：进入pc_portal_space再执行 npm run buildSeeyon

编撰人：liuyc


快速跳转



 * 1 表单设计态
   * 工程：
   * 表单设计：
   * 操作设置：
   * 业务列表设置：
   * 运行调试：
   * 表单设计 （ip）/index.html?
   * 操作设置 （ip）/authDesign.html?
 * 2、表单运行态：
   * 工程：
   * 项目文件：
   * 调试方法
   * 暴露给业务的方法
   * 明细表、明细表高级设置
   * CAP4控件-能否编辑
   * CAP4控件-大写控件未更新修改方法
   * CAP4控件-自定义控件渲染异常修改方法
   * cap4表单附件不能预览修改方法
   * 修改公共组件后打包流程



分享链接分享链接

## 132. 应用管理中心jsp页面

> 原始路径：`/1842/576/915.html`  
> 相对路径：`1842/576/915.md`

## 应用管理中心jsp页面

/cap4\form\business\bizconfigApp\businessAppList.js.jsp 应用管理中心-应用中心-应用管理中心 应用管理中心-应用中心-基础数据 /cap4\form\business\bizconfigApp\businessAppList.jsp 应用管理中心-应用中心-应用管理中心 应用管理中心-应用中心-基础数据 /cap4\form\business\bizconfigApp\businessAppListMenusEvent.jsp 应用管理中心,基础数据事件实现(一个文件代码太多,所以分成2个文件) /cap4\form\business\bizconfigApp\businessFormList.js.jsp 应用管理中心-应用中心-表单管理 /cap4\form\business\bizconfigApp\businessFormList.jsp 应用管理中心-应用中心-表单管理 /cap4\form\business\bizconfigApp\businessFormRelation.js.jsp 应用管理中心-应用中心-表单管理-业务关系设置 /cap4\form\business\bizconfigApp\businessFormRelation.jsp 应用管理中心-应用中心-表单管理-业务关系设置 /cap4\form\business\bizconfigApp\businessFlowFormList.jsp 应用管理中心-应用中心-表单管理-业务关系设置-插入表单 /cap4\form\business\bizconfigApp\businessMenuList.js.jsp 应用管理中心-应用中心-综合业务菜单(现在废弃) /cap4\form\business\bizconfigApp\listMutiMenudata.jsp 应用管理中心-应用中心-综合业务菜单(现在废弃) /cap4\form\business\bizconfigApp\listMutiMenuDataTree.jsp 应用管理中心-应用中心-综合业务菜单(现在废弃) /cap4\form\business\bizconfigApp\newMutiMenu.js.jsp 应用管理中心-应用中心-综合业务菜单(现在废弃) /cap4\form\business\bizconfigApp\newMutiMenu.jsp 应用管理中心-应用中心-综合业务菜单(现在废弃)

\cap4\form\business\managementCenter\listBusinessLicenses.js.jsp 应用管理中心-应用安装-查看应用许可 \cap4\form\business\managementCenter\listBusinessLicenses.jsp 应用管理中心-应用安装-查看应用许可 \cap4\form\business\managementCenter\managementInstallApp.js.jsp 应用管理中心-应用安装 \cap4\form\business\managementCenter\managementInstallApp.jsp 应用管理中心-应用安装 \cap4\form\business\managementCenter\managementList.js.jsp 工作台(现在废弃) \cap4\form\business\managementCenter\managementList.jsp 工作台(现在废弃) \cap4\form\business\managementCenter\workbench.js.jsp 工作台 \cap4\form\business\managementCenter\workbench.jsp 工作台

\cap4\form\business\operationCenter\clearFormData.js.jsp 运维中心-数据清理工具-表单数据清理 \cap4\form\business\operationCenter\clearFormData.jsp 运维中心-数据清理工具-表单数据清理 \cap4\form\business\operationCenter\clearSpecifyData.js.jsp 运维中心-数据清理工具-指定数据清理 \cap4\form\business\operationCenter\clearSpecifyData.jsp 运维中心-数据清理工具-指定数据清理 \cap4\form\business\operationCenter\operationColEdit.js.jsp 运维中心-数据清理工具-字段类型修改 \cap4\form\business\operationCenter\operationColEdit.jsp 运维中心-数据清理工具-字段类型修改 \cap4\form\business\operationCenter\operationList.js.jsp 运维中心-主框架 \cap4\form\business\operationCenter\operationList.jsp 运维中心-主框架 \cap4\form\business\operationCenter\operationNav.jsp 运维中心-导航 \cap4\form\business\operationCenter\reportDataAuth.js.jsp 运维中心-报表数据授权 \cap4\form\business\operationCenter\reportDataAuth.jsp 运维中心-报表数据授权

\cap4\form\business\appLog.js.jsp 查看应用日志(不清楚现在是否在使用) \cap4\form\business\appLog.jsp 查看应用日志 \cap4\form\business\bizconfigAuth..jsp 应用管理中心-应用中心-应用包-权限设置 \cap4\form\business\bizconfigAuth.js.jsp 应用管理中心-应用中心-应用包-权限设置 \cap4\form\business\bizconfigBaseData.js.jsp 应用管理中心-应用中心-应用包-基础数据 \cap4\form\business\bizconfigBaseData.jsp 应用管理中心-应用中心-应用包-基础数据 \cap4\form\business\bizconfigList.js.jsp 应用管理中心-应用中心/应用包-外框 \cap4\form\business\bizconfigList.jsp 应用管理中心-应用中心/应用包-外框 \cap4\form\business\bizconfigMenu.js.jsp 应用管理中心-应用中心-应用包-菜单设置(!!!!!!!Devil) \cap4\form\business\bizconfigMenu.jsp 应用管理中心-应用中心-应用包-菜单设置(!!!!!!!Devil) \cap4\form\business\listbizdata.jsp 应用管理中心-应用中心-应用包-菜单设置-左侧的顶部导航(!!!!!!!Devil) \cap4\form\business\listbizdatatree.jsp 应用管理中心-应用中心-应用包-菜单设置-左侧的数据树结构(包含cap3的页面)(!!!!!!!Devil) \cap4\form\business\bizconfigNew.js.jsp 应用管理中心-应用中心-应用包-表单管理(!!!!!!!Devil) \cap4\form\business\bizconfigNew.jsp 应用管理中心-应用中心-应用包-表单管理(!!!!!!!Devil) \common\cap4\bizconfig\js\doc_setting\tree.js 应用管理中心-应用中心-应用包-表单管理-左侧表单树 \common\cap4\bizconfig\js\doc_setting\view_map.js 应用管理中心-应用中心-应用包-表单管理-业务关系图实现(!!!!!!!Devil) \cap4\form\business\bizconfigRelation.jsp 应用管理中心-应用中心-应用包-表单管理-业务关系设置 \cap4\form\business\bizconfigViewMap.js.jsp 应用管理中心-应用中心-应用包-业务关系图设置 \cap4\form\business\bizconfigSetPeopleBelong.js.jsp 应用管理中心-应用中心-应用包/表单-修改所属人

\common\cap4\bizconfig\js\bizCommon.js 公共js \common\cap4\bizconfig\js\bizconfigReleaseApp.js 应用管理中心-应用中心-应用包-应用发布功能

\common\cap4\bizconfig\scss 页面的css,编译到 \common\cap4\bizconfig\css中 \common\cap4\bizconfig\fonts 字体文件 \common\cap4\bizconfig\trip jquery tooltip插件

\common\cap4\bizconfig\js\bizconfigReleaseApp.html 应用管理中心-应用中心-应用包-应用发布弹窗 \common\cap4\bizconfig\js\businessInfo.html 应用管理中心-应用中心-应用包-应用属性/表单属性弹窗 \common\cap4\bizconfig\js\businessAppDialog.html 应用管理中心-应用中心-新建应用/新建基础数据包弹窗 \common\cap4\bizconfig\js\clearData.html 应用管理中心-应用中心-删除数据弹窗

## vue工程:

pc_flow_authorized 应用管理中心-应用中心-应用包-管理设置-表单流程授权 pc_app_config 应用管理中心-应用中心-配置授权应用包进去页面

编撰人：liuyc


快速跳转



 * 应用管理中心jsp页面
 * vue工程:



分享链接分享链接

## 133. 1.代码位置

> 原始路径：`/1842/576/919.html`  
> 相对路径：`1842/576/919.md`

## 1.代码位置

cap-front工程，form-mobile项目，项目说明参考项目中的README.md文件


## 2.电脑端调试

一般来说，移动端的问题，我们通过微协同就能解决。网页登录协同，然后将url中的'/seeyon/***'替换成'/seeyon/H5/wechat/html/allApps.html'


## 3.打包

依赖于pkg_condition，先要装pkg_condition项目中的依赖 执行./seeyonBuild.sh

编撰人：liuyc




快速跳转



 * 1.代码位置
 * 2.电脑端调试
 * 3.打包



分享链接分享链接

## 134. 自定义控件清单

> 原始路径：`/1842/576/920.html`  
> 相对路径：`1842/576/920.md`

## 自定义控件清单

电子发票 OCR识别 表单转文档 电子签章 查询统计 富文本 文档对比 企业征信 项目关联 标签打印（按钮） 查看表单（按钮） 新建表单（按钮）


## 工程及代码说明

自定义控件设置态和PC端运行态代码 8.0以上在GIT\cap-custom-control中, 8.0以下在SVN各个版本的分支下的cap-custom-ctrls，比如 http://10.3.4.218:6666/svn/cap_code/branches/V7.1SP1_Hotfix_202002M/cap-custom-ctrls

移动端运行态代码 8.0以上在git\mplus-front\src\apps\v5中 8.0以下在SVN各个版本的分支下，比如 http://10.3.4.218:6666/svn/mplus/h5/branches/V7.1SP1_Hotfix_202007M/src/apps/v5

控件         设置态和PC端运行态代码目录                移动端代码目录
电子发票       formEinvoiceCtrlResources     invoice
OCR识别      formOcrCtrlResources          ocrbtn
表单转文档      wordInjectionResources        Formwordinjectionctrl
电子签章       formHandWriteCtrlResources    formhandwritectrl
查询统计       formQueryBtnCtrlResources     querybtn
富文本        formRichTextCtrlResources     formrichtextctrl
文档对比       formDocCompareCtrlResources   \cap-front\m_cap4_pkg\packages\customCtrlResources\formDocCompareCtrlResources
企业征信       formEinvoiceCtrlResources     formCreditqueryCtrl
项目关联       projectRelatedResources       \cap-front\m_cap4_pkg\packages\customCtrlResources\projectRelatedResources
新建表单（按钮）   newFormDataBtnResources       cwidgetviewform
查看表单（按钮）   showFormDataBtnResources      cwidgetviewform
标签打印（按钮）   labelPrintBtnResources        无


## 使用操作说明

1.打开表单设计器-应用绑定，修改或新建应用绑定，添加一个“标签打印”自定义按钮

2.打开标签打印设置窗口，点击设置，在弹出的模板列表中依次点击查看，找到一个与要新增的模板相似的模板。

3.打开数据库中cap_print_template表，找到第二步的模板数据，复制并插入一行，修改插入行的ID，模板名称，保证与其他行不重复。

4.将第1步中的“标签打印”自定义按钮模板设置为新增的模板。配置字段映射，表单权限，菜单等。

5.打开表单数据行上的标签打印，查看打印预览效果。

6.将第三步插入的数据行中content列字段剪切，粘贴到json.cn格式化，然后拷贝到content列，方便修改。

7.按从上到下，从左到右依次修改标签的位置，宽高等。调整后刷新第5步的打印页面看效果。 注： 1."type":"staticText", 为左侧标签，"type":"line"为线，"type":"6678555354073746763",为二维码，其他则为文字。 2.name不可重复，主要用于字段映射。 3.模板大小不变的情况下外框的4个line不需要调整。如果要调整线的位置，可以将线的颜色修改为非黑色，以便快速找出要修改的线。 4.建议使用上图中的ping fang sc和microsoft yahei字体,否则会有打印不清晰问题。


## 自定义开发相关文档

cap4：https://opendoc.seeyoncloud.com/bin/view/technology/Application/t_cap4/CAP4%E5%BC%80%E5%8F%91%E6%96%87%E6%A1%A3/03%20cap4/3.1%20%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8E%A7%E4%BB%B6/

cap3：https://opendoc.seeyoncloud.com/bin/view/technology/Application/t_cap4/CAP4%E5%BC%80%E5%8F%91%E6%96%87%E6%A1%A3/04%20cap3/4.1%20%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8E%A7%E4%BB%B6/


## 树控件：

应用包中：树形组件设置页面对应工程：cap-front>pc_aloneFile下的tree.vue

编撰人：liuyc




快速跳转



 * 自定义控件清单
 * 工程及代码说明
 * 使用操作说明
 * 自定义开发相关文档
 * 树控件：



分享链接分享链接

## 135. 业务空间设置

> 原始路径：`/1842/576/921.html`  
> 相对路径：`1842/576/921.md`

## 业务空间设置

应用中的门户设置-业务空间中的栏目模板来源有两个地方：

1：cap-front/column_factory/packages

2：xtc-app-code-complete/


## 查看已有的模板

进入special-app-column/colum_factory

npm run serve


## 导入栏目开发

1：栏目开发步骤：找到对应模板

2：用命令复制模板，*** 切记不要手动复制 ***

例如: 要复制如下模板：

xtc-app-code-complete\special-app-custom\custom-columns\xtc-hr-column\column-hr-development-history-project

复制模板步骤：

（1）进入 special-app-column/colum_factory 文件夹

（2）安装依赖 npm i

（3）如果上一步有报错，执行 npm run upslot

（4）npm run create

3：添加栏目配置、修改栏目配置方法

找到栏目中的配置项映射的config.json


   /**

    * config.json配置描述，增加、修改、删除通过属性options配置

   */

  {

    "name": "指标-卡片式信息3（PC端）-",

    "helpInfo": "请修改输入业务场景相关的栏目名称以便展示",

    "platform": "1",

    "skipOutStyle": true,

    "height": 180,

    "minHeight": 180,

    "UUID": "daaa2630-55bc-11ed-8e08-e9327cce1d44",

    "options": [

        {

            "key": "1",

            "type": "number",

            "name": "栏目圆角",

            "value": "0",

            "rules": [{

                "pattern": "^(0|[1-9][0-9]?|100)$",

                "attributes": "g",

                "message": "*注: 圆角设置范围为：0 - 100"

            }],

            "rightSpan": "px"

        }

    ],

    "labels": [],

    "autoHeight": true,

    "elements": [

        {

            "name": "表格",

            "description": "",

            "dataFormat": "4",

            "dataVersion": "V1"

        }

    ],

    "v5Version" : ["8_0SP1_2020-06-11", "~"],

    "excludeV5Version" : [],

    "HYtag": "国资体系,房地产业,IT服务业,消费品,科研院所,能源化工,医药医疗,教育,制造业, 批发零售业,多元化集团,金融业,交通运输业,商务服务业,餐饮业,建筑业",

    "LYtag": "人力资源管理,行政管理"

}



4：引用配置，找栏目模板的vue文件

eg： column-hr-hr-person-card2-hksktitle.vue

   // 通过 this.cloptions 获取config.json中的options配置数据
   this.cloptions()




## 编译

进入special-app-custom/colum_factory

npm run lib

编译后在会在special-app-custom/xtc-cap-components生成一个结尾为clmn的模板

编撰人：liuyc




快速跳转



 * 业务空间设置
 * 查看已有的模板
 * 导入栏目开发
 * 编译



分享链接分享链接

## 136. 1、工程相关

> 原始路径：`/1842/576/923.html`  
> 相对路径：`1842/576/923.md`

## 1、工程相关

工程名字：ctp-portal

门户路径: ctp-portal\trunk\src\main\webapp\portal



登录页相关: ctp-portal\trunk\src\main\webapp\main\login

门户的jsp页面: ctp-portal\trunk\src\main\webapp\WEB-INF\jsp\ctp\portal




## 2、模板文件入口

## 注册门户模板



PC⻔户模板: /webapps/seeyon/portal/config/portal_themes/portal_themes_pc.xml 移动⻔户模板: /webapps/seeyon/portal/config/portal_themes/portal_themes_mobile.xml 登录前⻔户: /webapps/seeyon/portal/config/portal_themes/portal_themes_loginPre.xml ⼤屏⻔户: /webapps/seeyon/portal/config/portal_themes/portal_themes_bigScreen.xml

## 注册整体⽪肤

PC⻔户模板: /webapps/seeyon/portal/config/portal_skin_set/portal_skin_set_pc.xml 移动⻔户模板: /webapps/seeyon/portal/config/portal_skin_set/portal_skin_set _mobile.xml 登录前⻔户: /webapps/seeyon/portal/config/portal_skin_set/portal_skin_set_loginPre.xml ⼤屏⻔户: /webapps/seeyon/portal/config/portal_skin_set/portal_skin_set_bigScreen.xml

## 注册⻔户模板与整体⽪肤的绑定关系

PC⻔户模板: /webapps/seeyon/portal/config/portal_skin_choice/portal_skin_choice.xml

## 注册⻔户⽪肤

PC⻔户的主框架⽪肤: /webapps/seeyon/portal/config/portal_skins/portal_skins_pc.xml 移动⻔户皮肤: /webapps/seeyon/portal/config/portal_skins/portal_skins_mobile.xml 登录前⻔户皮肤: /webapps/seeyon/portal/config/portal_skins/portal_skins_loginPre.xml 栏⽬外框⽪肤: /webapps/seeyon/portal/config/portal_skins/portal_skins_section.xml ⼆级⻚⾯组件⽪肤: /webapps/seeyon/portal/config/portal_skins/portal_skins_section.xml ⼤屏⻔户皮肤: /webapps/seeyon/portal/config/portal_skins/portal_skins_bigScreen.xml

## 注册⻔户布局

PC⻔户布局: /webapps/seeyon/portal/config/portal_template/portal_template_pc.xml 移动⻔户布局: /webapps/seeyon/portal/config/portal_template/portal_template_mobile.xml 登录前⻔户布局: /webapps/seeyon/portal/config/portal_template/portal_template_loginPre.xml ⼤屏⻔户布局: /webapps/seeyon/portal/config/portal_template/portal_template_bigScreen.xml

## ⻔户模板图⽚资源

在/webapps/seeyon/portal/pagelayout/layout/layout_c001 下新建⼀个图⽚资源 ⽬录 images ，新开发的⻔户模板中⽤到的图⽚资源必须都放到这个⽬录下，例如html⽂件中使 ⽤的图⽚⽂件，css⽂件中使⽤的图⽚⽂件，js⽂件中使⽤的图⽚⽂件，所有使⽤图⽚⽂件都必须 使⽤全路径引⽤ /seeyon/portal/pagelayout/layout/ layout_c001/images/xxx.png ，图 ⽚资源⽀持gif、png和jpg三种格式。

## 注册⻔户元素

注册⻔户模 板: /webapps/seeyon/portal/config/portal_laytpl_template/elements.xml 注册⻔户模板: /webapps/seeyon/portal/config/portal_laytpl_template/elements_mobile.xml 在webapps/seeyon/portal/pagelayout/element/custom 下新建为每个⻔户元素新 建三个⽂件： tpl-xxx.html 、 tpl-xxx.css 、 tpl-xxx.css

## 开发和注册栏⽬

栏⽬模板是指栏⽬⻓的是什么样⼦，例如列表样⼦、棋盘样式、图⽚轮播样式等，⼀个栏⽬模板 由4个⽂件组成：1个html⽂件、1个js⽂件、1个css⽂件和1个java⽂件，其中html⽂件必须遵循 laytpl模板引擎语法，1个java⽂件必须实现com.seeyon.ctp.portal.section.templete. BaseSectionTemplete基类。 以⽬前系统中已有栏⽬模板横幅模板（bannerTemplete）为例，所包含的内容如下所示：

tpl-bannerTemplete.html tpl-bannerTemplete.js tpl-bannerTemplete.css com.seeyon.ctp.portal.section.templete.BannerTemplete 在确定了栏⽬要显示哪些内容后，就可以按照上⾯的示例内容进⾏栏⽬模板的开发。在webapps/seeyon/portal/config/portal_laytpl_template/sections.xml 中注册该栏⽬ 模板

## 开发和注册依赖的第三⽅JS⽂件

如果栏⽬有依赖的第三⽅js⽂件，则需要单独在配置⽂件中配置

PC注册依赖: /webapps/seeyon/portal/config/portal_section_jsfiles/pc.xml 移动注册依赖: /webapps/seeyon/portal/config/portal_section_jsfiles/mobile.xmll


## 3、登录前门户静态化

登录前门户的url地址是：xxx/sportal/entry/index.html 登录前门户开关：


## 4、其它说明

## 查看新增模板

以集团管理员登录系统，进⼊后台管理=》【V-Portal配置平台-》整体样式库】中可以看到 我们刚才开发好的⻔户模板，如下图所示：




## 5、移动端门户

http://ip:port/seeyon/m3/apps/v5/portal/html/portalIndex.html 手机端门户首页 http://ip:port/seeyon/m3/apps/v5/collaboration/html/colAffairs.html 手机端待办列表 http://localhost/seeyon/m3/apps/m3/todo/layout/todo-list.html 首页待办 /seeyon/H5/wechat/html/allApps.html 不掉线的首页

## M3更新应用包:

⻔户相关的应⽤包在 webapps/seeyon/m3files/v5/65.zip 中， 此包其实使⽤webapps/seeyon/m3/apps/v5/portal ⽬前打包⽣成 ，如果需要更新，有两种⽅案使其⽣效：

需要系统管理员登录后，进⾏⼿动热部署，重启服务 重启服务

## 微协同调试

pc登陆协同：http://xt.seeyon.com/ 修改url路径为: http://xt.seeyon.com/seeyon/m3/apps/v5/portal/html/portalIndex.html 打开控制台进入调试页面，设置为手机模式如图:





## M3调试

安卓调试 iOS 使用ios模拟器

编撰人：liuyc




快速跳转



 * 1、工程相关
 * 2、模板文件入口
   * 注册门户模板
   * 注册整体⽪肤
   * 注册⻔户模板与整体⽪肤的绑定关系
   * 注册⻔户⽪肤
   * 注册⻔户布局
   * ⻔户模板图⽚资源
   * 注册⻔户元素
   * 开发和注册栏⽬
   * 开发和注册依赖的第三⽅JS⽂件
 * 3、登录前门户静态化
 * 4、其它说明
   * 查看新增模板
 * 5、移动端门户
   * M3更新应用包:
   * 微协同调试
   * M3调试



分享链接分享链接

## 137. AJAX组件

> 原始路径：`/1842/773/73.html`  
> 相对路径：`1842/773/73.md`

## AJAX组件

平台封装了一套AJAX组件，这套组件可以直接调用Manager层的业务方法，使用较为方便。


## 标准AJAX组件（推荐）

要实现AJAX，需要做如下动作：

1）确定哪个Manager的哪个方法可以被前台AJAX调用，然后在对应方法头加上@AjaxAcces注解

2）前台JSP引入common_footer.jsp，再使用前端包装方法callBackendMethod执行AJAX请求

具体做法如下：

第一步：Java后台使用Ajaxaccess注解注册

找到后台需要注册AJAX的Manager接口，在其方法上增加AjaxAcces注解，代码如下：

package com.seeyon.apps.demo.manager;

import java.util.Map;
import com.seeyon.ctp.common.exceptions.BusinessException;
import com.seeyon.ctp.util.annotation.AjaxAccess;


public interface DemoManager {
 /**
  * 保存
  * @param params
  * @throws BusinessException
  */
 @AjaxAccess
 public void saveDemo(Map<String,Object> params) throws BusinessException;

}


第二步：前端执行AJAX调用

如果是JSP页面，可以在引入common_footer.jsp的前提下，调用callBackendMethod进行AJAX请求：

<%@include file="/WEB-INF/jsp/common/common_footer.jsp"%>
<script type="text/javascript">
var params = {};
params.id=xx;
params.name=yy;
params.title=zz;
/**
 * demoManager:对应Spring bean id
 * saveDemo:对应demoManager interface下的方法
 * params:对应saveDemo方法里面的参数
 */
callBackendMethod("demoManager","saveDemo",params,{
    success : function(ret){
        //这是异步的AJAX请求方法
        $.alert("保存成功！");
    },
    error : function(request, settings, e){
        $.error("异常："+e);
    }
});//end of callBackendMethod
</script>


默认callBackendMethod采用异步返回，如果开发需要阻塞等待结果返回，则可以采用同步的形式：

> 注意：一般都不推荐使用同步AJAX，编写代码时尽量使用异步模式

//同步AJAX格式，如下请求会等待AJAX执行结束之后再继续
var projectName=callBackendMethod("projectQueryManager","getProjectName",relateProjectId);


前端AJAX实现原理：参考jsonGateway-debug.js文件：

function callBackendMethod(managerName, methodName) {
  var url = (typeof(window._ctxPath) !== "undefined" ? window._ctxPath : v3x.baseURL)+'/ajax.do?method=ajaxAction&managerName=' + managerName;
  return ajaxCallFuncInner(url, methodName, Array.prototype.slice.call(arguments, 2));
}



## 早期ajaxStub[不推荐]

在老工程可能会看到如下的代码实现方式，这是采用ajaxStub.do存根的方案：

var demoAjax = new demoManager();
demoAjax.saveDemo(params,{
    success : function(ret){
        $.alert("保存成功！");
    },
    error : function(request, settings, e){
        $.error("异常："+e);
    }
});


其原理就是：启动OA的时候，后端会扫描所有带有Ajax注解信息的类和方法，然后将其封装成一个前端javascript可使用的ajaxStub.js文件，放在seeyon目录下。

只要引用了ajaxStub.js文件的页面，都可以用过new Manager().callMethod()这种对象调用的形式来开发，其实这就是一个AJAX JSSDK。

之所以不推荐使用是因为ajaxStub.js日渐庞大，页面引用要耗费资源时间，影响页面加载速度。

<script type="text/javascript" src="${path}/ajaxStub.js?v=<%=com.seeyon.ctp.common.SystemEnvironment.getLastNodeStartTime()%>"></script>


实现原理参见平台AjaxAuthenticator、AjaxAccessInterceptor、AjaxController、jsonGateway-debug.js。


## 远古getAjaxDataServlet（不推荐）

下面这是更早期的AJAX封装实现，现在已经全面不推荐了，如果看到历史代码可以知晓这个实现原理。

第一步：后台注册：/cfgHome/*-ajax.xml方法

在\src\main\webapp\WEB-INF\cfgHome\路径下，*-ajax.xml文件中，进行对应模块map属性的配置。

示例代码展示了对公文发文、后台格式、项目管理等模块的配置，如下所示：

<map>
        <!-- 公文发文支持手工输入单位 -->
        <entry key="ajaxEdocExchangeAccountManager" value="exchangeAccountManager" ></entry>
        <!-- 后台格式设置 -->
        <entry key="ajaxContentTemplateManager" value="contentTemplateManager" ></entry>
        <!-- 项目管理 -->
        <entry key="ajaxProjectManager" value="projectManager" ></entry>
        <entry key="ajaxHandWriteManager" value="handWriteManager" ></entry>
        <entry key="ajaxWpsAssistManager" value="wpsOfficeApi" ></entry>
        <!-- 会议室管理 -->
        <entry key="ajaxMeetingRoomManager" value="meetingRoomManager" ></entry>
        <!-- 综合办公管理 -->
        <entry key="ajaxOfficeCommonManager" value="officeCommonManager" ></entry>
        <!-- 办公用品管理 -->
        <entry key="ajaxStockManager" value="stockManager"></entry>
</map>


第二步：前端调用：callBackendMethod调用

与平台ajax.do的新方式相似，callBackendMethod也将managerName和methodName两个参数传到前端；与新方式不同的是，由于老版本的ajax通过采用Servlet方法，调用callBackendMethod传值时还需传递相应Servlet的SessionId。

以下代码为该方法调用实例代码，三个参数分别为managerName，methodName和SessinId。

callBackendMethod("loginUserManager","isLeave",getDogSessionId(),{
         success : function(result){
          if(result == "__LOGOUT"){
           alert($.i18n('loginUserState.unknown')+',原因:检测到用户已退出!');//loginUserState.unknown
           exitCurrentSystem();
          }
          else if(result.isLeave==true){
                 showAuthenticationDialog({'avatar':result.avatar});
             }else{
                 unlockAllScreen();
             }
             isDoubleCommit = false;
         },
         error : function(request, settings, e){
          $.alert($.i18n('login.label.lose.connection.desc'));
          isDoubleCommit = false;
         }
     });


实现原理：参考AjaxAuthenticator类。

编撰人：het、admin




快速跳转



 * AJAX组件
   * 标准AJAX组件（推荐）
   * ~~早期ajaxStub[不推荐]~~
   * ~~远古getAjaxDataServlet（不推荐）~~



分享链接分享链接

## 138. 数据国际化

> 原始路径：`/1842/773/85.html`  
> 相对路径：`1842/773/85.md`

## 数据国际化


## 1 数据国际化真实效果

以SeeyonA8+集团版为例，先用系统管理员账号登录系统，在系统设置-系统模块管理-模块启停用-国际化-数字国际化中打开数字国际化开关，如图所示：



再重启OA系统，登录集团管理员账号，在基础功能设置-枚举管理中查看相应枚举，点击修改按钮，点击枚举名称右边的小地球图标可进行国际化资源管理：



以公共枚举时区为例，管理人员可人工修改其对应的英文和繁体中文，以对接不同企业的需求。



数据国际化同样适用于枚举值的显示，如公共枚举处理结果的枚举值“同意”，企业管理人员也可以对其进行国际化管理。




## 2 开发步骤


## 2.1 单字段设置国际化组件

数据国际化组件基于jQuery，并按照ctp标准comp组件规范实现,如果需要使用，需要按照平台【JSP开发规范】引入相关文件。

## 2.1.1 页面DOM初始化

<input type="text" id="dataI18nID" name="dataI18nName"  value="8578565212478542153" class="comp"
comp="type:'dataI18n',i18nSwitch:'off',mode:1,category:'enum.name',categoryName:'枚举名称'"
validate="notNullWithoutTrim:true,notNull:true,maxLength:85"/>


## 2.1.2 jQuery插件初始化

// 应用场景二：业务js中动态拼接生成国际化input组件，在业务js中主动调用$.('#eleId').dataI18n({...})方法，即可渲染生成组件。
$.('#dataI18nID').dataI18n({
  type:'dataI18n',
  mode:1,
  category:'enum.name',
  i18nSwitch:'off',
  categoryName:'枚举名称'
}); // eleId为国际化组件id


## 2.1.3 标准comp方式渲染

var $i18nDom = $.('#dataI18nID');
$i18nDom.addClass("comp");
$i18nDom.value("8578565212478542153")
$i18nDom.attr("comp","type:'dataI18n',i18nSwitch:'off',mode:1,category:'enum.name',categoryName:'枚举名称'");
$i18nDom.attr("validate","notNullWithoutTrim:true,notNull:true,maxLength:85");
$i18nDom.compThis();


## 2.1.4 更新国际化key

// 业务代码可通过如下方法回填组件值。
$("#dataI18nID").setI18nVal("-3449671849168386491");// 传国际化表中的id
$("#dataI18nID").setI18nVal("国际化组件");// 传未国际化的值


说明 ：组件生效，需要在 系统模块管理-->模块启停 功能中开启“数据国际化”开关，此开关默认为关。


## 2.2 自定义国际化事件监听

由于组件内部会将原来DOM进行替换，所以不能使用jQuery的on/bind,事件绑定使用jquery的delegate(代理)方式绑定。

__queryData__作为数据存放的对象，有i18nTitle和title两种属性，queryData.i18nTitle用来存放应用中的国际化数据，queryData.title用来存放应用中的原始数据。相应事件触发的传值在如下代码中反映：

## 2.2.1 dataChange事件

dataChange事件用于组件内部通知应用数据已经改变,方便应用做数据处理。**若使用了国际化，则触发dataChange事件，将相应数据的国际化值(i18nValue)传入相应变量的国际化属性(i18nTitle)中；若未使用国际化，则没有i18nValue这一属性，i18nTitle和title都是原始值。 **注意如果你通过JQuery中的validate插件进行校验，但规则校验不通过，组件不会保存数据同样也不会触发dataChnage事件。

$("国际化dom父元素的选择器").delegate("#i18n_dmo","dataChange", function(event,data){
 if(data.isI18n){//使用了国际化
  __queryData__.i18nTitle = data.i18nValue;
  __queryData__.title = data.value;
 }else{//未使用国际化
  __queryData__.i18nTitle = data.value;
  __queryData__.title = data.value;
 }
})


返回数据说明：

//返回数据说明
{
  "domId": "scheduledstats_title",//dom的id
  "isI18n": true,// 是否使用国际化,不使用返回false，且没有i18nValue、allLanguageValue、currentLanguage属性
  "value": "3321074866139252525",//input的值，如果使用国际化则是国际化的id，否者是input的数据
  "i18nValue": "静态报表",// 使用国际化则返回当前语种国际化的文字
  "allLanguageValue": {//全部语言的数据
    "en": "English-静态报表",
    "zh_CN": "静态报表",
    "zh_TW": "繁體中文-静态报表"
  },
  "currentLanguage": "zh_CN"//当前语种的local
}


## 2.2.2 dataBackfill事件

dataBackfill事件用于组件内部通知应用数据已经完成国际数据的化的回填并初始化,方便应用做数据处理。事件触发传值方式和上述dataChange事件相同。

$("国际化dom父元素的选择器").delegate("#indexName","dataBackfill", function(event,data){
 if(data.isI18n){//使用了国际化
  __queryData__.i18nTitle = data.i18nValue;
  __queryData__.title = data.value;
 }else{//未使用国际化
  __queryData__.i18nTitle = data.value;
  __queryData__.title = data.value;
 }
})


返回数据说明：

//返回数据说明
{
  "domId": "scheduledstats_title",//dom的id
  "isI18n": true,// 是否使用国际化,不使用返回false，且没有i18nValue、allLanguageValue、currentLanguage属性
  "value": "3321074866139252525",//input的值，如果使用国际化则是国际化的id，否者是input的数据
  "i18nValue": "静态报表",// 使用国际化则返回当前语种国际化的文字
  "allLanguageValue": {//全部语言的数据
    "en": "English-静态报表",
    "zh_CN": "静态报表",
    "zh_TW": "繁體中文-静态报表"
  },
  "currentLanguage": "zh_CN"//当前语种的local
}



## 2.3 批量设置国际化组件

上面我们讲了单字段国际化组件的设置和开发，这里通过jsonData来批量设置国际化组件，jsonData的属性说明见下表。

通过onOk方法来处理返回数据，onOk方法的相应属性见下文中的表格。

组件调用示例：

var jsonData = '['+
  '{\"name\":\"field0001\",\"text\":\"姓名\",\"maxLength\":80,\"category\":\"cap4.formmain_0025.field0001\"},'+
  '{\"name\":\"field00011\",\"text\":\"姓名\",\"title\":\"曾用名\",\"maxLength\":80,\"category\":\"cap4.formmain_0025.field00011\"},'+
  '{\"name\":\"field0002\",\"text\":\"性别\",\"maxLength\":10,\"category\":\"cap4.formmain_0025.field0002\"},'+
  '{\"name\":\"field0003\",\"text\":\"学历\",\"category\":\"cap4.formmain_0025.field0003\"},'+
  '{\"key\":\"-477759458923426020\",\"name\":\"field0004\",\"text\":\"籍贯\",\"maxLength\":50,\"category\":\"cap4.formmain_0025.field0004\"}'+
  ']';

  $.showDataI18nDialog({'jsonData':jsonData,'onOk':onOk,fieldName:"字段名称",titleName:"标题名称",showFieldColumn:true,showTitleColumn:false,callbackCheckMethod:checkI18nData});

  function onOk(data){
   console.log(data);
   /*
      *   处理返回数据
   */
  }



## 3 数据国际化属性说明


## 3.1 input属性说明

属性                      必填   值                     说明
id                      否    自定义                   不写会自动生成
name                    否    自定义                   不写会自动生成
value                   否                          编辑或初始化场景下使用。直接把应用字段的原始值赋给value即可。
readonly                否                          input的readonly值决定组件是否可用
disable                 否                          input的disable值决定组件是否可用
class                   是    comp                  固定值
comp                    是                          详见comp属性说明
validate                否                          规则原组件规范一致。此validate值会影响业务表单与国际化弹出框中表单的校验。 业务表单校验说明：完全依赖业务代码。
                                                   国际化弹出框表单校验说明：1、是否进行表单校验，受comp属性中validateSwitch开关控制；2、表单校验依据此validate，空校验除外；3、组件会忽略业务中设置的空校验规则；组件自身重置空校验规则，默认语言与当前语言不能为空，其它语言可为空。
onblur                  否                          不建议使用，建议使用dataChange事件，blur事件存在调用先后顺序问题，组件内部无法确认组件优先被调用1.直接在input元素上添加事件
                                                   onblur="javascript:console.log('失去焦点！');"
                                                   2.js绑定时建议使用on绑定事件，可以让多次绑定的函数都执行$("#dataI18nID").on('blur',function
                                                   () {// 业务代码})
onclick等事件              否                          可自定义各类事件
data-i18n                    该值由组件回填（true/false）   标识此字段的值是否进行了国际化。组件渲染完或国际化弹出框点击确定按钮后更新此属性的值
data-allLanguageValue        该值由组件回填               所有语言的值，json格式的字符串，例：{"en":"english
                                                   Value","zh_CN":"中文","zh_TW":"繁體"}


## 3.2 comp属性说明

属性               必填   值          说明
type             是    dataI18n   固定值
model            是    1          暂时未用到，建议先设置为1。1表示使用弹出对话框单一录入模式
category         是               标识应用分类，命名规范为应用分类+模块标识+Input的名称，至少三级，以点分隔，不允许重复。如枚举管理-枚举名称，category为global.enum.name。（category为以后清理无引用数据的重要依据，请务必填写）
categoryName     否               编辑的字段名称，国际化页面提示使用。
i18nSwitch       否    on/off     是否国际化。暂时使用，是否保留待定。
validateSwitch   否    on/off     国际化弹出框中是否做校验。
checkI18nData    否    0/1        是否进行业务逻辑校验.
                                 如果设置了需要进行校验(checkI18nData:1),需要同时在页面上定义js方法：function
                                 callBackCheckI18nData(i18nData,callback,param)来进行业务逻辑校验，同时在校验成功后调用回调函数保存国际化数据。

checkI18nData国际化数据校验示例：

/**
*1.i18nData:设置的国际化数据，json格式，如 {"zh_CN":"1","en":"1","zh_TW":"","validate":true,"id":"8444155350495150826","category":"organization.account.name","currentLocale":"zh_CN"}
*2.callback:保存国际化数据的回调函数。
*3.param：保存国际化数据的回调函数参数。
*/
function callBackCheckI18nData(i18nData,callback,param){
    var id = $("#id").val();
    var action = id === '-1' ? 'add' : 'update';
    // 业务数据逻辑校验
    oManager.checkNameI18nData(i18nData,action, id,null,{
        success: function(msg) { 
     if(msg != ''){
  $.alert(msg);
     }else{
         // 逻辑校验成功，必须手动调用回调函数保存国际化数据
  callback(param);
     }
        }
      });
}



## 3.3 jsonData属性说明

属性             必填   值   说明
name           是        页面字段的唯一标识（表单控件的名称或者input框的id，自行设置）
text           是        字段名称
title          否        字段标题（text相同的情况下用于区分字段，缺省值为text。）
categoryName   是        类别（规则：应用组名称.业务名称.字段名称。（规则按具体要求处理，保证分类唯一，易懂）key:对应存储的国际化id。新增时为空，更新时必填。）
maxLength      否        字段最大长度（缺省为数据库最大长度500）
key            否        对应存储的国际化id,新增时为空，更新时必填。


## 3.4 非必要设置属性说明

属性                    必填   值            说明
fieldName             否                 自定义的字段名称
titleName             否                 自定义的标题名称
showFieldColumn       否    true/false   是否显示列（缺省显示）
showTitleColumn       否    true/false   是否显示列（缺省显示）
callbackCheckMethod   否                 保存数据前的回调校验函数

callbackCheckMethod 国际化数据校验示例

/**
*1.content:校验数据
*2.callbackSaveMethod:回调函数
*/
function checkI18nData(content,callbackSaveMethod){
    // 业务数据逻辑校验
    oManager.checkNameI18nData(content,{
        success: function(msg) { 
     if(msg != ''){
  $.alert(msg);
     }else{
         // 逻辑校验成功，必须手动调用回调函数保存国际化数据
  callbackSaveMethod();
     }
        }
      });
}



## 3.5 onOk方法说明

数据保存成功后的回调函数。 data数据格式：

[
{"name":"field0001,"text":"姓名","key":"8475457947599485074"},
{"name":"field0002,"text":"籍贯","key":"-790375975930503570"}
]


属性     说明
name   和传入的name一致，（表单控件的名称或者input框的id）。
text   返回编辑过的当前语种的名称。
key    国际化的id。


## 数据国际化（后端）


## 背景&需求

需要对系统某个地方的展示适配国际化，涉及到的后端开发

## 操作步骤&解决方案

下面以用户名称的国际化作为示例

前端已经实现了国际化的配置



## 第一步：

配置态适配：

1、后端需要在数据库表新增字段



2、并给对象新增字段i18nNameId



3、修改保存数据接口

在保存的时候，前端会传一个long类型的i18nNameId过来，入库存入数据库

4、修改查询接口，新增i18nNameId字段查询返回，方便前端根据id回填已配置的国际化值

## 第二步：

运行态适配：

1、修改展示接口，对从数据库的查询接口进行特殊处理，对原来的name字段进行单独重新赋值



重新设置，通过以下代码取国际化值

ResourceUtil.getString(i18nNameId);




返回的值会自动根据当前环境语言，来返回对应的值，适配完成

编撰人：het、zhangzuh、admin




快速跳转



 * 数据国际化
   * 1 数据国际化真实效果
   * 2 开发步骤
     * 2.1 单字段设置国际化组件
       * 2.1.1 页面DOM初始化
       * 2.1.2 jQuery插件初始化
       * 2.1.3 标准comp方式渲染
       * 2.1.4 更新国际化key
     * 2.2 自定义国际化事件监听
       * 2.2.1 dataChange事件
       * 2.2.2 dataBackfill事件
     * 2.3 批量设置国际化组件
   * 3 数据国际化属性说明
     * 3.1 input属性说明
     * 3.2 comp属性说明
     * 3.3 jsonData属性说明
     * 3.4 非必要设置属性说明
     * 3.5 onOk方法说明
   * 数据国际化（后端）
     * 背景&需求
       * 操作步骤&解决方案
         * 第一步：
         * 第二步：



分享链接分享链接

## 139. 选人组件

> 原始路径：`/1842/773/88.html`  
> 相对路径：`1842/773/88.md`

## 选人组件

关键字：JSP选人组件、JSP选人控件




## 使用示例

使用ctpui2.0、ctpui3.0、ctpui4.0的页面可以使用这种方式调用选人组件：

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


前端JSP使用完整示例代码：

<%--
  Author shuqi
  Rev
  Date: 2022-03-09 22:46
  
  Copyright (C) 2022 Seeyon, Inc. All rights reserved.
  
  This software is the proprietary information of Seeyon, Inc.
  Use is subject to license terms.
  @company  seeyon.com
  @since  V5 V8.1SP1
  @author       shuqi
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



## Comp组件

这种使用方式和上一种是一样，只是页面渲染、事件绑定有ctpui自动完成。同样如果你愿意也可以动态生成input框，设置好属性并使用$("jQuerySelector").compThis();

示例如下：

<input
 type="text" 
 class="comp" //固定
 comp="type:'selectPeople',panels:'Department,Post,Team,Role',selectType:'Member,Department'" // 传入选人参数
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
  @company  seeyon.com
  @since  V5 V8.1SP1
  @author       shuqi
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



## V3x框架使用

如果你的页面使用的是v3x老框架，同样也可以使用选人。PS:v3x属于过时的老页面，建议尽快改完新框架

1、引入v3x命名空间

<%@ taglib uri="http://v3x.seeyon.com/taglib/core" prefix="v3x"%>


2、申明选人组件

提供的参数不全，可以通过扩展参数的方式设置。

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

如果需要设置全部参数，可以添加全局变量：参数名_组件Id = xxx_如var onlyLoginAccount_manager=true

//支持的扩展参数
['accountId', 'departmentId', 'memberId', 'postId', 'levelId', 'elements', 'showOriginalElement', 'excludeElements', 'isNeedCheckLevelScope', 'onlyLoginAccount', 'showAccountShortname', 'showConcurrentMember', 'hiddenPostOfDepartment', 'hiddenRoleOfDepartment', 'hiddenMetadataOfDepartment', 'onlyCurrentDepartment', 'showDeptPanelOfOutworker', 'unallowedSelectEmptyGroup', 'showTeamType', 'hiddenOtherMemberOfTeam', 'hiddenAccountIds', 'isCanSelectGroupAccount', 'showAllOuterDepartment', 'hiddenRootAccount', 'hiddenGroupLevel', 'showDepartmentsOfTree', 'showDepartmentsNoChildrenOfTree', 'hiddenSaveAsTeam', 'hiddenMultipleRadio', 'showAdminTypes', 'includeElements', 'extParameters', 'showSecondMember', 'isAllowContainsChildDept', 'isCheckInclusionRelations', 'showRecent', 'notShowAccountRole']
//示例
var onlyLoginAccount_manager=true;



## Vue场景

vue要使用选人需要引入：${contextpath}/common/js/selectOrgSdk.js

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



## Vjoin使用

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



## 选人界面参数

参数                                          字段类型                                                     备注
panels                                      string                                                   控制选人界面panel,多个“,”分隔
selectType                                  string                                                   控制选人界面可选类型,多个“,”分隔
alwaysShowPanels                            string                                                   切换单位一直显示页签,多个“,”分隔
hiddenOnChanageAccountForOrgTeam            boolean                                                  切换单位隐藏机构组 ,默认true
hiddenOnChanageAccountForExchangeAccount    boolean                                                  切换单位隐藏公文交换,默认true
hiddenGroupLevel                            boolean                                                  不显示集团职务界别页签，参数控制不显示,默认值为false
showAccountPanel                            boolean                                                  是否显示单位页签，默认为true，
showDeptPanelOfOutworker                    boolean                                                  编外人员显示单位、岗位、职位级别、角色、主数据，默认为false
onlyShowChildrenAccount                     boolean                                                  是否只显示子单位，默认false都显示（切换单位和单位树 ）
showAllAccount                              boolean                                                  是否显示全部单位，默认false
showAccountIds                              string                                                   指定显示单位，多个以“,”分隔，默认null
hiddenAccountIds                            string                                                   指定显示单位，多个以“,”分隔，默认null[已废弃]
showRecent                                  boolean                                                  是否显示最近页签，默认为true
allowSeachGroup                             boolean                                                  是否允许全集团查询人员，缺省允许 true
onlyLoginAccount                            boolean                                                  是否只定位到指定的（accountId或者登陆单位）单位
accountId                                   long                                                     指定默认单位Id
departmentId                                long                                                     是否显示查询全集团的按钮
defaultUnitType                             String                                                   默认组织类型
showOriginalElement                         boolean                                                  是否回显原有数据，默认为true
hiddenSaveAsTeam                            boolean                                                  隐藏“另存为组”，默认为false
maxSize                                     int                                                      最大可选择,默认为1000
minSize                                     int                                                      最小可选择,默认为1
hiddenMetadataOfDepartment                  boolean                                                  是否隐藏部门下的人员属性
hiddenMemberOfDepartment                    boolean                                                  隐藏部门下的人员选择框
hiddenRoleOfDepartment                      boolean                                                  是否隐藏部门下的角色
hiddenPostOfDepartment                      boolean                                                  是否隐藏部门下的岗位
showTeamType                                "1,2,3"                                                  需要显示的组类型1-个人,2-系统,3-项目, 默认""，表示所有
showAdminTypes_${id}                        "SystemAdmin,AuditAdmin,GroupAdmin                       需要显示的管理员,如果不指定，表示显示所有
                                            ,AccountAdministrator,AccountAdministrator _-81232345"
notShowAccountRole                          boolean                                                  （相对角色，表单控件下） 不显示单位角色，默认按照集团管理员勾选‘选人界面’的设置来。默认false
notShowMetadataRole                         boolean                                                  （相对角色，表单控件下） 不显示主数据下的角色。默认false
extParameters                               string                                                   选人业务扩展参数。默认""
showRoleType                                string                                                   Account，Department 角色页签下显示什么类型的角色，默认显示所有，可以单独设置显示单位角色还是部门角色
orgMetadataTagTypes                         string                                                   主数据显示支持类型,默认"Account,Department,Post,Member"
showAccountShortname                        string                                                   是否只一直显示登录简称,默认auto
showConcurrentMember                        boolean                                                  是否显示兼职人员（只外单位）,默认true
showSecondMember                            boolean                                                  是否显示副岗人员（只外单位）,默认true
unallowedSelectEmptyGroup                   boolean                                                  不允许选择空的组、部门,默认false
isCanSelectGroupAccount                     boolean                                                  是否可以选择集团单位,默认true
alwaysShowBusiness                          boolean                                                  总是显示的多维组织的id
showDepartmentsOfTree                       string                                                   部门Id,部门树上可以显示的部门
showSearchFunction                          boolean                                                  组织机构选人界面定义的是否显示搜索功能
unallowedChangeBusinessAccount              boolean                                                  是否允许切换多维组织单位,默认为false
currentBusinessAccount                      string                                                   默认显示的多维组织单位id
SingleChoice                                boolean                                                  控制单位树、组织机构树是否为单选
showChild                                   boolean                                                  是否显示子树
excludeElementsBeyondMemberSize             string                                                   指定类型的元素，该元素下的人员超过指定大小后，不允许选择 默认为null,Department
showDepartmentsNoChildrenOfTree             string                                                   部门页签下，显示当前部门和父级部门
isNeedCheckLevelScope                       boolean                                                  是否需要进行职务级别校验,部门可见性校验由其决定
params                                      object                                                   上个页面回填的数据，如{value:"Member|122",text:"树琦"}
returnValueNeedType                         boolean                                                  返回值是否需要带类型，默认true，如果false则只返回Id，只用于单一选择
isConfirmExcludeSubDepartment               boolean                                                  默认值true，选择部门时，是否提示“是否包含子部门”，默认false即包含子部门
hiddenAddExternalAccount                    boolean                                                  显示增加外部单位连接，默认false
isAllowContainsChildDept                    boolean                                                  在部门面板选择部门时，是否允许同时选择父部门和子部门，默认为false，不允许
isCheckInclusionRelations                   boolean                                                  是否检查已选数据的包含关系，默认true
isNotShowNoMemberConfirm                    boolean                                                  是否不显示“xxx部门下无人，是否继续选择”的提示语，默认false，即显示
isNotCheckDuplicateData                     boolean                                                  是否不检查重复数据，默认false，即检查
returnMemberWithDept                        string                                                   true
isShowCheckboxIntree                        boolean                                                  是否展示的树，允许复选框勾选，缺省不允许 false.单位树不受此开关控制
memberWithDeptInfo                          string                                                   人员返回部门信息
isSelectUserDepartment                      boolean                                                  部门页签是否默认选中用户所在部门
disabledAccountSelectorForOrgTeam           boolean                                                  禁用机构组的单位选择
disabledAccountSelectorForExchangeAccount   boolean                                                  禁用外部单位的单位选择
preReturnValueFun                           string                                                   选择完后，点击确定时，需要进行回调该方法，参数为：传入所选对象的id
excludeElements                             list                                                     不在被选框中显示 默认为null
includeElements                             list                                                     Element[] 备选的数据范围
showAllOuterDepartment                      boolean                                                  是否显示所有的外部部门，默认false(按照自己的访问权限来)
showGroupRole                               boolean                                                  是个显示集团角色,默认为false @since 8.2


## 基础panel类型

CODE                    PANELTYPE                   名称          备注
OrgRecent               ORG_RECENT                  最近          
Account                 ORG_ACCOUNT                 单位          
OcipOrganization        OCIP_ORGANIZATION           OCIP        需要OCIP插件
Department              ORG_DEPARTMENT              部门          
BusinessAccount         ORG_BUSINESSACCOUNT         多维组织单位      需要多维组织插件
BusinessDepartment      ORG_BUSINESSDEPARTMENT      多维组织部门      需要多维组织插件
Team                    ORG_TEAM                    组           
OrgTeam                 EDOC_ORGTEAM                机构组         
Post                    ORG_POST                    岗位          
Level                   ORG_LEVEL                   职务级别        
Node                    ORG_NODE                    相对角色        
Outworker               ORG_OUTWORKER               编外人员        
FormField               FORM_FIELD                  表单字段        
OrgMetadataTag          ORG_METADATATAG             组织属性        
RelatePeople            ORG_RELATEPEOPLE            关联人员        
Role                    ORG_ROLE                    角色          
BusinessRole            ORG_BUSINESSROLE            多为组织角色      需要多维组织插件
Admin                   ORG_ADMIN                   管理员         
ExchangeAccount         EDOC_EXCHANGEACCOUNT        公文外部单位      
WFDynamicForm           WF_DYNAMICFORM              动态表流程       
WfSuperNode             WF_SUPER_NODE               超级节点        
Guest                   ORG_GUEST                   Guest账号     
AppProperty             APPLINK_APPPROPERTY         应用属性        
JoinOrganization        VJOIN_ORGANIZATION          Vjoin组织     需要vjoin插件
JoinAccount             VJOIN_ACCOUNT               Vjoin部门     需要vjoin插件
JoinPost                VJOIN_POST                  Vjoin岗位     需要vjoin插件
JoinAccountTag          VJOIN_ACCOUNTTAG            Vjoin组织属性   需要vjoin插件
GovRoleStdSystemAdmin   ORG_GovRoleStdSystemAdmin   系统管理员       
GovRoleStdSecretAdmin   ORG_GovRoleStdSecretAdmin   安全管理员       
GovRoleStdAuditAdmin    ORG_GovRoleStdAuditAdmin    审计管理员       
econtractForm           ECONTRACT_FORM              电子合同        
Unit                    ORG_UNIT                    组织机构：中石油    中石油添加
MemberMetadataTag       ORG_MEMBERMETADATATAG       人员主数据       


## 基础selectType类型

CODE                              名称          备注
Member                            人员          
Department                        部门          
Account                           单位          
Role                              角色          
Post                              岗位          
Department_Post                   部门岗         
Level                             职务级别        
Team                              组           
Admin                             管理员         
Guest                             特殊账号        
OrgMetadataTag                    组织属性        
Unit                              组织机构：中石油    
Node                              相对角色        
FormField                         表单字段        
JoinAccountTag                    vjoin组织扩展   
BusinessAccount                   多维组织        
BusinessDepartment                多维组织部门      
BusinessRole                      多维组织角色      
BusinessDepartment_BusinessRole   多维组织部门下角色   
ExchangeAccount                   外部单位        
OrgTeam                           机构组         
doc                               文档          
meeting                           会议          
meetingsummary                    会议纪要        
bulletin                          公告          
news                              新闻          
WF_SUPER_NODE                     流程超级节点      
WFDynamicForm                     审批路径表       
GovRoleStdSystemAdmin             系统管理员       
GovRoleStdSecretAdmin             安全管理员       
GovRoleStdAuditAdmin              审计管理员       
econtractForm                     电子合同        

编撰人：admin、het


快速跳转



 * 选人组件
   * 使用示例
   * Comp组件
   * V3x框架使用
   * Vue场景
   * Vjoin使用
   * 选人界面参数
   * 基础panel类型
   * 基础selectType类型



分享链接分享链接

## 140. 前端JSP动态脚本链入

> 原始路径：`/1842/773/159.html`  
> 相对路径：`1842/773/159.md`

## 前端JSP动态脚本链入


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


编撰人：het


快速跳转



 * 前端JSP动态脚本链入
   * 场景
   * 开发示例
     * 确定页面的ModelAndView
     * 建立自定义的JavaScript文件
   * 代码实现原理



分享链接分享链接

## 141. 水印组件

> 原始路径：`/1842/773/1856.html`  
> 相对路径：`1842/773/1856.md`

## 水印组件


## 什么是水印组件

水印是指在系统页面中添加的半透明标识或图案，用于防止内容被盗用或篡改，并标明版权信息或作者身份。

标准产品提供了通用的水印设置页面，允许设置哪些模块需要水印，详细配置位置：系统管理员-安全管理-数据保护-水印设置。

> 水印设置代码位置：\ctp-common\src\main\webapp\WEB-INF\jsp\common\waterMark\waterMarkSetting.jsp



如果项目上进行了新页面的开发，需要添加水印，可以参考本手册自行加上水印组件。


## PC添加水印

（1）在JSP页面中引入水印组件Javascript文件：<script src="${path}/common/waterMark/js/waterMark.js${ctp:resSuffix()}"></script>

（2）调用function addWaterMark(xxx)执行水印设置操作

    <%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
    <!DOCTYPE html>
    <html class="over_hidden h100b">
    <head>
     <%@include file="/WEB-INF/jsp/common/common_header.jsp"%>
     <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge" />
     <meta name="renderer" content="webkit">
     <title>${ctp:i18n("文件标题") }</title>
     <link rel="stylesheet" href="${path}/apps_res/{module}/css/xxx.css${ctp:resSuffix()}">
    </head>
    <body class="over_hidden h100b">

    </body>
    <%@include file="/WEB-INF/jsp/common/common_footer.jsp"%>
    <script src="${path}/common/waterMark/js/waterMark.js${ctp:resSuffix()}"></script>
	<script type="text/javascript">
		$(document).ready(function(){
			addWaterMark({"appType": "addressbook","isMobile":false,"imgInfo":true},function (result) {
				if(result.show && result.img){ // result.show = true表示开启了水印
					var watermarkImg = result.img;
					if(watermarkImg != ''){
						// 设置水印操作，其中$('body')可以根据需求来控制，比如只需要指定div区域则找到对应div dom设置即可
						$('body').css("background-image","url(\"" + watermarkImg +"\")");
					}
				}
			});
		});
	</script>
    </html>


addWaterMark相关参数注释如下：

/**
 * 水印生成方法
 * @param params            配置参数 格式如下
 * {
 *  "appType": "news",     必有，表示当前水印属于什么模块，该模块与后台水印设置对应，用来判断当前模块是否开启了水印，目前可选的值为 col form imail edoc report news bul addressbook doc salary zx officePreview paperless bbs print
 *  "isMobile":false,      选填，默认为false,与appType组合，取pc还是移动端的水印启停状态
 *  "imgInfo":true         选填，默认为true,是否生成base64的水印图片
 * }
 * @param callbackFun       回调方法，需要接收一个参数 接收数据 格式如下
 * {
 *      "show":false,       是否显示水印
 *      "print":false,      是否显示打印水印
 *      "img":"",           水印base64图片字符串,只有打印水印时，为空
 *      "printImg":"",      打印用水印base64图片字符串，方便区分用
 *      "info":""           额外信息 出错信息存于此
 *      "name" : true,      是否显示名称
 *      "acc" : true,       是否显示单位名称
 *      "time" : true,      是否显示时间
 * };
 * @param isSync            同步还是异步，默认异步
 */
function addWaterMark(params, callbackFun, isSync)



## 移动端添加水印

1、先在当前模块注册JSSDK，以获取水印配置信息：

getWaterMarkInfo : function(appType, isMobile, imgInfo, _params, options) {
	return SeeyonApi.Rest.get('waterMark/waterMarkInfo/' + appType + '/' + isMobile + "/" + imgInfo + "", _params, '', cmp.extend({}, options))
}


参照源码示例：\mplus-front\src\apps\v5\vreport\js\vreport-jssdk.js



2、H5页面引入cmp-watermark.js：<script type="text/javascript" src="${data:dependencies.cmp}/js/cmp-watermark.js${data:buildversion}"></script>

参照源码示例：\mplus-front\src\apps\v5\vreport\html\fileReportView.html



3、在H5页面底部或在js中执行水印渲染操作：

<!DOCTYPE html>
<html>
	<head>
		忽略若干代码
		<title></title>
		<style id="styleForWaterMark">
    	</style>
	</head>
	<body class="cmp-fullscreen cmp-p-bg">
		忽略若干代码
		<script type="text/javascript" src="${data:dependencies.cmp}/js/cmp-watermark.js${data:buildversion}"></script>
		<script type="text/javascript">
			cmp.ready(function(){
				// 执行水印渲染
				$s.Vreport.getWaterMarkInfo("report", true, false, null, { // 通过jssdk调用后端获取当前模块是否支持水印，返回水印信息
					success: function(rs){
						if (rs && rs.show) { // rs.show = true 表示支持水印
							var imgUrl = cmp.watermark(rs.mobileWaterMarkParams).toBase64URL();
							var tempStyle = "" +
									".waterMark::after {\n" +
									"    content:\"\";\n" +
									"    position: absolute;\n" +
									"    top: 0;\n" +
									"    left: 0;\n" +
									"    right: 0;\n" +
									"    bottom: 0;\n" +
									"    background-image: url(\""+ imgUrl +"\");\n" +
									"    background-size: 200px 100px;\n" +
									"    background-repeat: repeat;\n" +
									"    pointer-events: none;\n" +
									"}";
							var styleTag = document.getElementById("styleForWaterMark");
							styleTag.innerHTML = tempStyle;
							// 页面注入waterMark的css样式
							document.querySelector('.cmp-content').classList.add("waterMark");
						}
					}
				});
			});
		</script>
	</body>
</html>


参照源码示例：\mplus-front\src\apps\v5\vreport\js\fileReportView.js => $s.Vreport.getWaterMarkInfo

4、以上开发完成后无法直接使用，需要使用自动构建系统编译出结果，或使用S3JS工具编译出最终文件测试。

编撰人：het




快速跳转



 * 水印组件
   * 什么是水印组件
   * PC添加水印
   * 移动端添加水印



分享链接分享链接

## 142. JSP Form校验提交组件

> 原始路径：`/1842/773/1873.html`  
> 相对路径：`1842/773/1873.md`

## JSP Form校验提交组件


## 前言

JSP Form校验提交组件是基于JSP开发规范下衍生出的一套Form表单前后端交互组件，支持统一的表单页面布局、统一校验规范、统一提交和回填等相关能力。

使用本组件的前提是：当前页面是JSP并且按照致远JSP开发组件规范引入相关文件。


## 1、Form布局规范

在<form>标签外层包一层<div class="form_area">，使用此代码后，整个form便可以被V5的Seeyon UI相关API调用。

<div class="form_area align_center">
    <form id="tableForm" action="list.htm" class="align_center">
		<input id="name" type="text" class="validate" validate="{type:'string',name:'姓名',notNull:true,minLength:4,maxLength:20,character:'-!@#$'}">
	</form>
</div>


更详细的表单form代码示例，可参考Seeyon UI 3.0组件 - Form表单


## 2、Form校验

在text等可编辑元素增加class="validate" validate="xxx"参数，可使用平台标准的校验规则。

> 如要校验某种类型，要求input存在class为validate，并具备validate属性进行校验规则配置，validate属性值的格式要求是json对象定义字符串(不含大括号)。

例如：

<input id="username" name="username" type="text" class="validate" validate="type:'string',maxLength:20,minLength:6"/>


在Javascript中使用JQuery的扩展函数formobj、jsonSubmit或validate方法时，会执行校验过程，例如：

> 注：只要按照JSP开发规范，正确引入common_footer.jsp，则可以调用这三个方法。

// 该方法用于直接提交form：获取form中所有元素+执行元素validate校验+校验通过后自动提交form
$("#username").jsonSubmit();
// 该方法用于获取form中所有元素值，可获取到值后通过AJAX异步提交：获取form中所有元素+执行元素validate校验
var formObj = $("#username").formobj();
// 该方法仅用作校验Form元素准确性
var bool = $("#username").validate();



## validate校验属性字典

以下属性均运作于前面validate属性中，全部都是json字符串的属性。

主属性是验证某一个类型必须存在的属性，副属性可选，不是必须存在的属性。

目前一共可以验证13种类型，再加上最后一种给定自定义正则表达式的自定义验证类型。

类型                                    主属性和可选值                                               副属性和可选值（空白表示无）
1、非空                                  notNull:true或nullable:true                            
2、包含空格的非空                             notNullWithoutTrim:true                               
3、数字（小数）                              isNumber:true或type:number或type:1或type:2               max或maxValue（必须是数字，如果两个都给出，只使用前者）
                                                                                            min或minValue（必须是数字，如果两个都给出，只使用前者） integerDigits整数位-数（必须是数字）
                                                                                            decimalDigits或dotNumber小数位数（必须是数字，如果两个都给出，只使用前者）
4、数字（整形）                              isInteger:true                                        max或maxValue（必须是数字，如果两个都给出，只使用前者）
                                                                                            min或minValue（必须是数字，如果两个都给出，只使用前者）
5、电子邮件                                isEmail:true或type:email                               
6、字符串                                 isWord:true或type:string或type:8或type:9                 character:，将所有你认为是特殊字符的字符放进去，例如character:!@#$%^*()。
                                                                                            （如果特殊字符中存在中划线-的话，必须放在第一个）（如果特殊字符中存在脱字符^的话，必须不能放在第一个）
7、不允许为默认值                             isDeaultValue:true、deaultValue:一个给定的值                 
8、固定电话号码                              type:telephone                                        
9、手机号码                                type:mobilePhone                                      
10、日期类型（要求格式：yyyy-MM-dd）              type:3                                                
11、日期时间类型（要求格式：yyyy-MM-dd HH:mm:ss）   type:4                                                
12、最大长度                               maxLength:一个数字                                        
13、最小长度                               minLength:一个数字                                        
14、自定义正则表达式                           regExp:一个自定义的正则表达式，例如/[\d+]/                          
15、自定义校验函数                            主属性：func:一个自己定义的函数（必须是全局函数，可以是匿名函数）                   
                                      （该函数可以没有返回值（js中没有返回值的话默认为null），返回null或false表示校验未通过）
16、自定义错误提示                            主属性：errorMsg:一个字符串，例如:请输入数字！                          
17、js设置校验规则                           请看下方的MxtCheckMsg方法                                    -


## 3、Form值回填

场景：点击编辑时，打开编辑的JSP页面，并且回填值到编辑的JSP页面。

本组件适用于后端Controller已经准备好页面所需的值，在进入JSP页面时，通过EL表达式直接注入值到JSP页面。

自动form回填可以自动为表单元素设置值，而不再需要自己写那些繁琐的js。但事实证明，这种主动回填的代码极易引发XSS注入。并且违背前后端分离原则，不适合纯前端开发工作者！

> 注：只要按照JSP开发规范，正确引入common_header.jsp和common_footer.jsp，则可以调用form值回填组件

（1）编写前端代码：

如下示例，JSP里面有两个div（也可以是form），每个div都有几个输入框或checkbox或select 注意div的Id和每一个表单元素的Id。 在同一个容器里，每一个表单元素的Id必须唯一。

   <div id="area1">
       用户名：<input type="text" id="username"/>
       密码：<input type="text" id="userage"/>
       爱好：<input type="checkbox" id="aihao1" value="1"/>(1)<input type="checkbox" id="aihao2" value="2"/>(2)<input type="checkbox" id="aihao3" value="3"/>(3)
       性别：<input type="radio" id="sex1" value="1"/>(男)<input type="radio" id="sex2" value="2"/>(女)
       星级：<select id="qiuji">
           <option value="1">地球</option>
           <option value="2">月球</option>
           <option value="3">火星</option>
       </select>
       实力：<select id="shili" multiple="true">
           <option value="1">天</option>
           <option value="2">地</option>
           <option value="3">人</option>
       </select>
   </div>
   <div id="area22">
       用户名：<input type="text" id="username"/>
       密码：<input type="text" id="userage"/>
       爱好：<input type="checkbox" id="aihao1" value="1"/>(1)<input type="checkbox" id="aihao2" value="2"/>(2)<input type="checkbox" id="aihao3" value="3"/>(3)
       性别：<input type="radio" id="sex1" value="1"/>(男)<input type="radio" id="sex2" value="2"/>(女)
       星级：<select id="qiuji">
           <option value="1">地球</option>
           <option value="2">月球</option>
           <option value="3">火星</option>
       </select>
       实力：<select id="shili" multiple="true">
           <option value="1">天</option>
           <option value="2">地</option>
           <option value="3">人</option>
       </select>
   </div>


（2）编写后台代码：

如下示例，与前台两个div对应，这里有两个Map，分别对应前端的两个div容器。

每一个Map都必须要通过调用request对象的setAttribute方法，添加到request对象中。

调用setAttribute时，Map的key的值必须要以ff开头，后面紧跟前台对应的容器Id。

> 比如前端<div id="area1">，后端Map的key就等于ffarea1

向Map中put键值对时，key必须是容器中对应的表单元素的Id。

如果表单元素是多选（例如checkbox、select），多个值之间用逗号分隔开。

		/**以下代码片段存放于MVC中的Controller，在重定向JSP页面前执行：**
       Map<String, String> test = new HashMap<String, String>();
       test.put("username", "zho'ulj");
       test.put("userage", "16\"'");
       test.put("aihao2", "2");
       test.put("aihao3", "3");
       test.put("sex2", "2");
       test.put("qiuji", "2,3");
       test.put("shili", "1,2,3");
	   // 回填第一个div
       request.setAttribute("ffarea1", test);
       Map<String, String> test2 = new HashMap<String, String>();
       test2.put("username", "岳不群！");
       test2.put("userage", "16\"'");
       test2.put("aihao2", "2");
       test2.put("aihao3", "3");
       test2.put("sex2", "2");
       test2.put("qiuji", "2,3");
       test2.put("shili", "1,2,3");
	   // 回填第二个div
       request.setAttribute("ffarea22", test2);


（3）扩展用法：AJAX调用表单回填：

我们也可以在JSP页面通过AJAX调用获取后端对象，再使用JQueryDom..fillform(对象)的形式将值回填到表单元素中。这是推荐使用的一种回填方案。

	   // 以下是平台提供的AJAX写法，还不知道如何使用，可在`JSP前端业务组件>AJAX组件`中学习
       tBS.testAjaxMethod(param, {success:
              function(obj){
                 $("#myform").fillform(obj);
              }
           });



## 4、Form提交

本组件主要作为CTPJSP页面的form提交的标准方式，禁止使用普通的form提交。

使用该组件可以极大的简化前后台代码的提交和获取参数的方式。

使用限制：

 1. 除radio外，同一个容器（或分区）内表单元素（包括checkbox）不能有相同的name或id。
 2. select如果是多选的话，后台会转换成List类型的对象。 该组件通过jQuery插件的方式提供，调用jsonSubmit方法即可。

主要有四种提交方式（前台），四种获取参数的方式（后台）

普通提交（无分区、无分组）、分组提交（无分区）、分区提交（无分组）、分区分组式提交。

> 注：只要按照JSP开发规范，正确引入common_header.jsp和common_footer.jsp，则可以调用form提交组件


## Form普通提交方式

 * 前台调用jsonSubmit方法提交参数。
 * 后台调用ParamUtil.getJsonParams()获取参数。
 * getJsonParams方法返回一个Map类型的对象。
 * 其key是json对象的属性名，value是json对象的属性值
 * 如果json对象的属性值是一个数组的话，Map的value就是一个List。

(1)前台JSP页面：

   <form id="form1" name="form1" method="post" action="test.do?method=testJsonSubmit2">
       <table>
           <tbody>
               <tr><td colspan="2"><label>表单<font color="red">无分区无分组</font>提交</label></td></tr>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="pwd"/></td>
               </tr>
           </tbody>
       </table>
   </form>


(2)前台js代码：

	// 参数中的debug属性在正式开发的时候不需要给出，或者需要设置为false；
   $("#form1").jsonSubmit({debug:false});


(3)后台代码：

   Map params = ParamUtil.getJsonParams();
   params.get("username");
   params.get("pwd");



## Form分组提交方式

所谓的分组，其实就是一个容器内有多个name或id相同的输入框。 前台的提交方式与普通方式没有区别，都是调用jsonSubmit方法。 后台获取参数的方式有区别，使用ParamUtil.getJsonParamsGroup()方法。 getJsonParamsGroup方法返回的是一个List类型的对象。 List中的每一个元素都是一个Map。 该Map的内容与getJsonParams返回的Map内容相同。

（1）前台JSP

   <form id="form4" name="form4" method="post" action="test.do?method=testJsonSubmit4">
       <table>
           <tbody>
               <tr><td colspan="2"><label>表单<font color="red">无分区分组</font>提交</label></td></tr>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="pwd"/></td>
               </tr>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="pwd"/></td>
               </tr>
               <tr>
                   <td><input id="savebtn4" type="button" value="提交paramGroup"/></td>
                   <td></td>
               </tr>
           </tbody>
       </table>
   </form>


（2）前台js代码：

   // 参数中的debug属性在正式开发的时候不需要给出，或者需要设置为false；
   $("#form4").jsonSubmit({debug:false});


（3）后台代码：

   List groups1 =ParamUtil.getJsonParamsGroup();
   for(Object o : groups1){
       if(o instanceof Map){
           Map map = (Map)o;
           for(Object entryObj : map.entrySet()){
               if(entryObj instanceof Map.Entry){
                   Map.Entry entry = (Map.Entry)entryObj;
                   System.out.println(entry.getKey() + ":" + entry.getValue());
               }
           }
       }
   }



## Form分区提交方式

前台的提交方式有区别，方法名不变，都是jsonSubmit方法。 不过参数有改变，{domains:["domain31","domain32"],debug:false} 多了一个domains属性，其值必须是一个数组，数组中的每一个元素必须是要提交的多个容器的id。 后台获取参数的方式也不同了，使用ParamUtil.getJsonDomain("domain31")方法。 getJsonDomain方法的参数需要给出前台给出的容器Id。 如果有多个domain，必须调用多次getJsonDomain方法来获取到所有的domain。 getJsonDomain的返回值也是一个Map。 该Map的内容与getJsonParams返回的Map内容相同。

（1）前台JSP

   <form id="form3" name="form3" method="post" action="test.do?method=testJsonSubmit3">
       <table id="domain31">
           <tbody>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="pwd"/></td>
               </tr>
           </tbody>
       </table>
       <table id="domain32">
           <tbody>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="pwd"/></td>
               </tr>
               <tr>
                   <td><input id="savebtn3" type="button" value="提交domain"/></td>
                   <td></td>
               </tr>
           </tbody>
       </table>
   </form>


（2）前台js代码：

   /**
   参数中的debug属性在正式开发的时候不需要给出，或者需要设置为false；
   domains属性值必须是一个数组，数组中的每一个元素必须要要提交的多个容器的id。
   **
   $("#form4").jsonSubmit({domains:["domain31","domain32"],debug:false});


（3）后台代码：

   Map domain1 =ParamUtil.getJsonDomain("domain31");
   domain1.get("username");
   domain1.get("pwd");

   Map domain2 =ParamUtil.getJsonDomain("domain32");
   domain2.get("username");
   domain2.get("pwd");



## Form分区分组式提交

这种方式其实是前面两种方式的组合： 分区分组是提交，首先是分区是提交。 每个分区中，可能存在分组，也可能不存在分组。 前台的提交方式与分区式提交相同，都是jsonSubmit方法。 参数也相同，都是{domains:["domain31","domain32"],debug:false} 多了一个domains属性，其值必须是一个数组，数组中的每一个元素必须是要提交的多个容器的id。 对于存在分组的分区，后台获取参数的方式:List groups1 =ParamUtil.getJsonDomainGroup("domain51"); 参数就是前台分区的id，其返回值是一个List，其中的每一个元素是一个Map。 对于不存在分组的分区，后台获取参数的方式与分区式提交后台获取参数的方式相同。 都是Map domain2 = ParamUtil.getJsonDomain("domain52");

（1）前台JSP

   <form id="form5" name="form5" method="post" action="test.do?method=testJsonSubmit5">
       <table id="domain51">
           <tbody>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="passwork"/></td>
               </tr>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="passwork"/></td>
               </tr>

               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="passwork"/></td>
               </tr>
           </tbody>
       </table>
       <table id="domain52">
           <tbody>
               <tr>
                   <td><label>用户名</label></td>
                   <td><input type="text" name="username"/></td>
               </tr>
               <tr>
                   <td><label>密码</label></td>
                   <td><input type="password" name="passwork"/></td>
               </tr>
               <tr>
                   <td><input id="savebtn5" type="button" value="提交domainGroup2"/></td>
                   <td></td>
               </tr>
           </tbody>
       </table>
   </form>


（2）前台js代码：

   /**
   参数中的debug属性在正式开发的时候不需要给出，或者需要设置为false；
   domains属性值必须是一个数组，数组中的每一个元素必须要要提交的多个容器的id。
   **/
   $("#form4").jsonSubmit({domains:["domain51","domain52"],debug:false});


（3）后台代码：

   List groups1 = ParamUtil.getJsonDomainGroup("domain51");
   for(Object o : groups1){
       if(o instanceof Map){
           Map map = (Map)o;
           for(Object entryObj : map.entrySet()){
               if(entryObj instanceof Map.Entry){
                   Map.Entry entry = (Map.Entry)entryObj;
                   System.out.println(entry.getKey() + ":" + entry.getValue());
               }
           }
       }
   }
   Map domain2 = ParamUtil.getJsonDomain("domain52");
   for(Object entryObj : domain2.entrySet()){
       if(entryObj instanceof Map.Entry){
           Map.Entry entry = (Map.Entry)entryObj;
           System.out.println(entry.getKey() + ":" + entry.getValue());
       }
   }


如果需要获取页面中某个分区中的数据对象进行Ajax提交或其它处理，可以调用jquery插件的formobj方法，比如：

   var obj = $("mydomain").formobj();
   tBS.testAjaxSubmit(obj,{success:
      function(retObj){
         alert("success");
      }
   });


属性名            属性值与说明
domains        必须是一个数组，分区式提交时该参数必须给出，里面每一个元素都必须是其中一个分区的id。
debug          当该属性的值是true时，会在提交之前将生成的json字符串alert出来，以便调试。
beforeSubmit   该属性的值必须是一个函数，当该函数的返回值等于false时，不会提交该form。


## 关于jsonSubmit

jsonSubmit方法可以模拟异步提交方式，可使用callback参数指定回调函数实现，如：$("#mydiv").jsonSubmit({callback : function() { alert('回调函数'); }});


## Form表单数据清除

框架提供clearform函数用于清除某个区域内的表单输入域的值，代码例子如下：

<script>
$(document).ready(function() {
    $("#mybtn").click(function() {
	  // 本方法可清理form中的所有input元素值
      $("#mydomain").clearform();
    });
});
</script>
<input type="button" id="mybtn">
<div id="mydomain">
<input type="text"><input type="checkbox"><input type="radio"><textarea></textarea>
</div>



## Form表单控件批量禁用/启用

框架提供disable和enable函数用于批量禁用和启用某个区域的控件，代码例子如下：

<script>
  $(document).ready(function() {
    $("#mybtn").toggle(function() {
      $("#mycal1").disable();
      $("#testRegion").disable();
    }, function() {
      $("#mycal1").enable();
      $("#testRegion").enable();
    });
  });
</script>
<input type="button" id="mybtn" value="禁用/启用">
<div id="testRegion">
    <a href="javascript:void(0)" class="common_button common_button_gray">按钮1</a><a href="javascript:void(0)"
        class="common_button common_button_gray">按钮2</a> <input type="text" class="comp"
        comp="type:'calendar',ifFormat:'%m-%Y-%d'"> <input type="checkbox"><input type="radio">
</div>


编撰人：het


快速跳转



 * JSP Form校验提交组件
   * 前言
   * 1、Form布局规范
   * 2、Form校验
     * validate校验属性字典
   * 3、Form值回填
   * 4、Form提交
     * Form普通提交方式
     * Form分组提交方式
     * Form分区提交方式
     * Form分区分组式提交
     * 关于jsonSubmit
   * Form表单数据清除
   * Form表单控件批量禁用/启用



分享链接分享链接

## 143. JSP附件组件

> 原始路径：`/1842/773/1874.html`  
> 相对路径：`1842/773/1874.md`

## JSP附件组件


## 前言

附件上传下载组件，是在JSP开发规范基础上实现的前后端附件互通的模块组件，只要按照JSP开发规范，正确引入common_header.jsp、common_footer.jsp，则可以调用本组件。


## 应用范围

 * 协同、公文等模块附件区文件的渲染及上传操作。

 * 文档管理/知识管理应用的用户上载文件的管理


## 附件管理

附件组件的使用分为前端和后端，两部分配合使用才能实现完整的附件相关功能。在开发时需要分别编写JSP前端、Java后端代码。

 * 前端负责界面展现
 * 后端负责附件的保存、获取相关逻辑

附件上传分为下面几种方式：

 * 标准方式：即附件的显示、保存等功能不需要调用者关系，组件会完成所有功能。调用者只按要求调用几个接口即可。使用方法参考下面3.2.1

 * 扩展方式：即组件只完成部分功能，剩余功能需要调用者来处理。适用于上传、解析后不在使用该文件。即上传后对该文件直接解析处理，并不返回调用页，在调用者处理完后返回自己期望的页面。

 * 一页多个上传组件：即一个页面做多处需要上传文件，每处上传的属性和显示的位置不同。标准方式和扩展方式都支持。

 * js动态创建方式：上面三种都依赖与页面完整加载，对于页面不重新加载，而是通过js操作的需使用此方式。例如行为动态生成，每行都包含一个上传组件，需要通过js方法动态生成。


## 附件上传-标准方式

（1）编写前端代码：

1、声明一个附件上传组件；

2、在对应的菜单或者按钮上调用 insertAttachment() 方法

3、在自己的页面中submit form时必须使用分区方式提交。

<!-- 附件上传组件区域start -->
<div id="attachmentTR" style="display:none;">${ctp:i18n("common.attachment.label")}:(<span id="attachmentNumberDiv"></span>)</div>
<div class="comp" comp="type:'fileupload',applicationCategory:'1',canDeleteOriginalAtts:false,originalAttsNeedClone:false" attsdata='${attachmentsJSON}'>
<!-- 附件上传组件区域end -->

<!-- 定义触发按钮，点击触发附件上传start -->
<input type="button" onclick="insertAttachment()" value="上传附件">
<!-- 定义触发按钮，点击触发附件上传end -->


 * div id="attachmentTR"是显示附件数量区域，如果要显示附件数量，请在需要显示附件数量的位置放置。样式可以改，里面的id都不能修改。
 * comp属性值为：type:'fileupload'，表示附件组件。
 * 如果一个页面只有一个上传组件，则可以使用insertAttachment()执行上传,如果一个页面有多个上传组件则需要调用insertAttachmentPoi(attachmentTrId属性的值)方法，该方法需要和attachmentTrId属性配合使用。
 * insertAttachment()是平台内置方法，执行此函数则进行上传，不用开发自己封装函数。



上传附件组件comp支持如下属性：

属性                      说明                                                            实例
type                    指当前为上传文件组件，值为固定值                                              type:'fileupload
attsdata                指原有已上传的附件，需要把原有的附件显示出来。                                       
                        这个属性对应的值来自于Controller，从后端参考标准接口获取附件对象字符串，参考示例
applicationCategory     应用分类，统一在ApplicationCategoryEnum定义                             applicationCategory:'1'
canDeleteOriginalAtts   指能否删除原有的附件，如转发协同不能删除原有附件                                      canDeleteOriginalAtts:false
originalAttsNeedClone   是否需要复制原有附件，常用在模板调用                                            originalAttsNeedClone:false
extensions              允许上传的文件类型，用文件会后缀表示，多个类型用逗号分隔（,）                               extensions:'txt,jpg'
maxSize                 上传文件的大小限制，单位为字节                                               maxSize:10240000
isEncrypt               对上传的文件是否加密，true为加密；false为不加密                                  isEncrypt:false
quantity                最多上传文件个数，不使用该参数事默认是5                                          quantity:1
attachmentTrId          一页支持多个附件上传组件时使用，和insertAttachmentPoi('poi77')方法配合使用           attachmentTrId:poi77
                        在方法中传入该属性的值。
callMethod              在不改变使用过程的情况下，在上传附件后回调该方法。 此属性依赖takeOver属性，takeOver值为false     callMethod:'testCallBack' takeOver:false
                        注意！方法名必须用引号括起来作为字符串。具体返回值请参考扩展方式中的说明。
takeOver                是否接管附件上传（即弹出窗口关闭）之后的逻辑。                                       takeOver:false
                        该属性和callMethod配合使用，如果不使用回调方法，可以不使用该属性； 否则属性值应为false
showReplaceOrAppend     是否显示“追加”、“覆盖”radio。即，在上传页面中会提供如下元素， 业务模块根据下面元素确定相关逻辑。         showReplaceOrAppend:true
firstSave               是否先保存附件表信息，ture为先保存，false或者无该属性为后保存。                          firstSave:true
                        并且为ture时，回调方法得到的参数值为包含Attachment 的js 数组，否则为逗号(,)分隔的文件ID字符串。
                        这种情况下后端应该调用附件更新接口，目的是关联业务数据域附件数据。

（2）后端上传附件代码逻辑：

后端负责对附件信息的存储，其实如果前端JSP编写的是标准的附件组件，则后端附件存储是不需要业务组自己写代码。

在触发前端insertAttachment()执行上传附件操作时，附件组件就会自动自动调用后台的AttachmentManager#create接口来实现附件的上传，接口参数定义如下：

	/**
     * 该方法必须和 comp=type:'fileupload' 配合使用
     * @param category         所属应用分类
     * @param reference        主题Id，如协同的Id
     * @param subReference      二级主题Id，如协同的回复Id，如果当前是给协同上传附件，则该subReference 与 reference相同
     * @return 附件类型任意组合 如："012"、"12"、"01"、"02"; 其中 0-文件附件 1-图片 2-关联文 ,排列无序
     * @see com.seeyon.ctp.common.filemanager.Constants.ATTACHMENT_TYPE_FILE
     * @see com.seeyon.v3x.common.filemanager.Constants.isUploadLocaleFile(String)
     * @throws Exception
     */
    public String create(ApplicationCategoryEnum category, Long reference, Long subReference) throws Exception;




（3）attsdata后端返回已上传附件列表

前端编写代码comp组件中attsdata='${attachmentsJSON}用于进入JSP页面时，返回并显示已经上传过的附件列表，EL表达式${attachmentsJSON}数据来自于后端，此附件列表数据需要编写在MVC层的Controller层，在重定向到当前JSP页面前准备好数据。

        ModelAndView modelAndView = new ModelAndView("apps/file/inituploadfile");
        // attachmentManager#getAttListJSON(主数据Id)可以组装attsdata数据
        modelAndView.addObject("attachmentsJSON", attachmentManager.getAttListJSON(dataId));
        return modelAndView;



## 附件上传-扩展方式

扩展方式除了由平台完成附件的上传外，还支持前端自定义回调函数：在平台上传附件成功之后将结果返回给回调函数，方便业务组拿到数据做自己的后续逻辑开发。

如下场景：产品支持上传excel格式的通讯录，上传之后，业务组解析通讯录文件并转化为业务组需要的数据，最后持久化到数据库中。

基础以上场景，这个业务实际要进行两段操作：

 * 附件组件：上传通讯录文件

 * 附件组件上传成功后通知业务组回调函数

 * 业务组回调函数拿到上传文件信息，并调用业务组自己的后端接口：后端解析Excel文件，并转化为业务组数据持久化到数据库

 * 业务组后端接口：返回页面，告知用户成功或失败信息。

从上面过程看，从第三步开始与附件上传的标准过程不同，需要调用者来处理。

（1）编写前端代码：

首先，业务组需要在JSP页面准备好一个回调函数：

<script type="text/javascript">
//附件上传后回调方法
function testCallBack(file,d){
  // 业务组处理文件逻辑的动作
  var fileUrl = file.get(0).fileUrl;
  var fileId = file.get(0).id;
  sendAjax(fileUrl,fileId);
}
</script>


然后，参照标准模式，定义附件组建区域，唯一要增加的是：在附件组件comp属性增加callMethod:'testCallBack'参数。

其它附件组件相关comp属性均参照标准模式的属性列表

    <div class="comp" comp="type:'fileupload',callMethod:'testCallBack'">
    <input type="button" onclick="insertAttachment()" value="上传附件">


（2）编写后端代码：

后端存在两种情况：

 1. 不保存附件信息，即获取到上传文件后，获取到文件数据后该文件不再使用，不需要作为附件存储起来。
 2. 保存附件信息。

场景一：业务组不保存附件信息

通过fileManager#getFile可以得到刚上传的文件：

    public ModelAndView index(HttpServletRequest request, HttpServletResponse response) throws Exception {
        ModelAndView modelAndView = new ModelAndView("apps/file/selfupload");
		// 获取刚上传的文件对象
        File file = fileManager.getFile(Long.parseLong(request.getParameter("fileid"),new Date()));
        //对得到的文件进行处理
        modelAndView.addObject("filename", file.getName());
        modelAndView.addObject("filelength", file.length());
        return modelAndView;
    }


场景二：业务组自己保存附件信息

在后端业务操作中调用如下接口，用来关联附件也业务数据：

 /**
     * 根据文件标识新引用
     * @param fileUrl 文件标识
     * @param referenceId 业务id
     */
    public  void updateReference(Long fileUrl, Long referenceId);

    /**
     * 根据文件标识更新引用及子引用
     * @param fileUrl 文件标识
     * @param referenceId 业务主ID
     * @param subReference 业务子ID
     */
    public  void updateReferenceSubReference(Long fileUrl, Long referenceId, Long subReference);


1   与该业务ID相关的所有附件都在同一处显示，使用该接口更新。
2   与该业务ID相关的所有附件都在同多处显示，每处根据子ID进行区分，使用该接口更新。


## 附件上传-js动态创建方式

如果业务组不需要编写附件组件<div comp=fileupdate>相关代码，只需要用前端Javascript直接操作附件上传组件，则可以使用本方案。

通过调用js方法：dymcCreateFileUpload() 来实现。对于不需要的特性输入null即可。

/**
 * locationElementid, 位置id，放置上传组件的位置，比如div的id（"dyncid"）：<div id="dyncid"> </div>
 * applicationCategory, 应用模块id
 * extensions, 文件扩展名，逗号分隔的字符串
 * quantity, 最多上传的文件数
 * isEncrypt, 是否加密
 * callMethod, 回调方法名
 * attachmentTrId, 对赢得文件上传的id
 * firstSave，是否先保存附件表信息，默认false：后保存。
 * atts 附件数据
 * canDeleteOriginalAtts 是否可删除附件
 * takeOver 是否接管附件上传（即弹出窗口关闭）之后的逻辑。 该属性和callMethod配合使用，如果不使用回调方法，可以不使用该属性； 否则属性值应为false
 * maxSize 上传文件的大小限制，单位为字节
    */
    function dymcCreateFileUpload(locationElementid,applicationCategory,extensions,quantity,isEncrypt,callMethod, attachmentTrId,firstSave,canDeleteOriginalAtts,atts,takeOver,maxSize){


对于以上方式不能满足交互需要，可以使用下面接口灵活控制附件相关特性。

/**
 * 获取当前组件提交的附件数据。对于一页存在多个上传组件，每个组件所在区域单独处理附件时（即只处理本区域附件，其他区域附件不处理），
 * 使用该方法，可以把该组件上传的附件数据，存放到以组件ID为domainid的区域内。
 * inputDomainId 上传组件id
    */
    function saveAttachmentPart(inputDomainId ){


编撰人：het


快速跳转



 * JSP附件组件
   * 前言
   * 应用范围
   * 附件管理
     * 附件上传-标准方式
     * 附件上传-扩展方式
     * 附件上传-js动态创建方式



分享链接分享链接

## 144. JSP关联文档组件

> 原始路径：`/1842/773/1875.html`  
> 相对路径：`1842/773/1875.md`

## JSP关联文档组件


## 前言

JSP关联文档组件，是在JSP开发规范基础上实现的前后端附件互通的模块组件，只要按照JSP开发规范，正确引入common_header.jsp、common_footer.jsp，则可以调用本组件。

关联文档开发包括两种角色，调用者和内容开发者。调用者通过简单接口使用关联文档组件；内容开发者提供可关联的内容部分，需根据关联文档框架规范进行开发。


## 调用关联文档

关联文档调用分为下面几种方式：

 * 标准方式：即jsp页面中放入标签，通过加载jsp来生成相应内容。

 * js动态创建方式：对于页面不重新加载，而是通过js操作的需使用此方式。例如动态生成，每行都包含一个关联文档组件，需要通过js方法动态生成。


## 关联文档-标准方式

前端页面调用方法

调用过程包含下面两步：

<div class="div-float">关联文档：<span id="attachment2NumberDivposition1"></span></div> 
<div class="comp" comp="type:'assdoc',attachmentTrId:'position1', modids:'1'" attsdata='${ attachmentsJSON}'>
           <input type="button" onclick="quoteDocument('position1')" value="关联文档">


 * 关联文档数量的显示，id值的柜式为：固定部分（attachment2NumberDiv ）+组件位置部分（即 attachmentTrId 属性值），例如：id="attachment2NumberDivposition1"
 * 添加关联文档显示区，即在需要显示关联文档的地方添加 type:'assdoc' 的组件

属性               说明                                                          实例
type             指当前为关联文档组件，值为固定值                                            type:'assdoc'
attachmentTrId   如果一页包含多个关联文档，需要使用该属性指定当前组件的位置id                             attachmentTrId:'position1',
modids           应用id字符串为逗号（,）分隔，id值为全系统统一编号                                 modids:'1' 1 = Collaboration;2= Form;3 = Knowledge
                                                                             management ;4= Official document ;5 = Plan;6= Meeting;7=
                                                                             Bulletin;8 = News;9 = Discussion
attsdata         指原有的关联文档，如：业务模块的修改页面，或协同保存待发—新建等功能， 需要把原有的关联文档显示。           attsdata='${ attachmentsJSON}'
                 使用下面接口获取原有附件： /** 返回关联文档列表的json字符串*
                 为前端显示附件获取一个主题下的所有附件信息，包括二级主题， 如：协同的附件和协同回复的附件 / public
                 String getAttListJSON(Long reference);
callMethod       回调方法名。注意！方法名必须用引号括起来作为字符串。                                  callMethod:'testCallBack'
embedInput       需要在组件位置生成一个hidden input，id、name为 该属性值。不需要该input时不需要设置该属性。   embedInput:'field001'

打开关联文档窗口的接口，调用quoteDocument(poi) 打开关联文档窗口。

poi为组件的位置属性值

后端保存、获取

后端保存与获取和附件保存、获取方式相同。使用同一套接口可以一次保存附件和关联文档的数据，获取也是如此。即：如果当前提交既有附件又有关联文档，只需要调用一次保存接口。


## 关联文档-js动态创建方式

通过调用js方法：dymcCreateAssdoc()来实现。对于不需要的特性输入null即可。

/**
 * locationElementid, 位置id，放置关联组件的位置，比如div的id（"dyncid"）：<div id="dyncid"> </div>
 * attachmentTrId, 同一页多个关联组件的区分id
 * atts 关联文档数据
    */
    function dymcCreateAssdoc(locationElementid, attachmentTrId,modids,atts)



## 关联内容开发

主要包含下面步骤：

 1. 获取业务内容并展现
 2. 展现页面中要包含checkbox，并且checkbox的 onclick 响应事件中应调用接口：parent.quoteDocumentSelected(this, subject, ${applicationCategoryType.name}, id);同时需要提供一个js方法，用来取消选择。该方法名固定为deselectItem(fileUrl)，方法主要是根据传进来的业务id值来取消选择。例如：

   function deselectItem(fileUrl){
       $("input[value='"+fileUrl+"']").attr("checked", false);
   }


 1. 注册关联内容到关联文档框架，让框架自动识别该部分内容


## quoteDocumentSelected 接口说明

接口说明：

/**
 * checkbox回调方法
 * obj, checkbox对象 this
 * subject, 标题
 * documentType, 应用类型
 * url，关联内容的id
    */
    function quoteDocumentSelected(obj, subject, documentType, url)


例如：quoteDocumentSelected(this, subject, ${applicationCategoryType.name}, id)



## 注册关联内容到框架

关联内容的请求url、应用编号等注册，在模块（插件）的spring中配置如下bean

    <bean id="test1" class="com.seeyon.ctp.common.assdoc.AssdocDefinition">
        <property name="appId" value="1" />
        <property name="url" value="http://www.baidu.com" />
    </bean>


 * 定义class="com.seeyon.ctp.common.assdoc.AssdocDefinition" 的bean

 * 设置应用编号属性，name="appId"，value为如下的应用编号`

  1 = Collaboration

  2 = Form

  3 = Knowledge management

  4 = Official document

  5 = Plan

  6 = Meeting

  7 = Bulletin

  8 = News

  9 = Discussion


 * 设置该应用关联列表的url.
   编撰人：het


快速跳转



 * JSP关联文档组件
   * 前言
   * 调用关联文档
     * 关联文档-标准方式
     * 关联文档-js动态创建方式
   * 关联内容开发
     * quoteDocumentSelected 接口说明
     * 注册关联内容到框架



分享链接分享链接

## 145. 图片预览组件

> 原始路径：`/1842/773/1876.html`  
> 相对路径：`1842/773/1876.md`

## 图片预览组件

支持放大缩小、原图查看功能：

 1. 可以兼容到IE

 2. 支持左右按钮切换图片、ESC退出

 3. 支持滚轮缩放图片的大小

 4. 支持图片放大后拖拽

 5. 新增一个原图查看功能

可以直接将 DEMO下载请鼠标右键-链接地址另存为放在v5的seeyon目录运行。







编撰人：het




快速跳转



 * 图片预览组件



分享链接分享链接

## 146. 前端快速开始

> 原始路径：`/1842/1843.html`  
> 相对路径：`1842/1843.md`

## 前端快速开始

以下适合于需要进行V5产品功能学习和定制开发的前端技术人员，用于快速引导前端熟悉V5前端能力，知道什么场景用什么开发。


## 前提条件

你需要满足如下条件，方可继续阅读本文档：

（1）你已经有一个V5环境，可以正常登录并使用产品功能，已经初步了解V5产品模块分类和功能，如“协同”、“公文”、“CAP4”的概念。

> 如没有环境，请参考文档：本站>技术平台>快速开始>安装协同系统

（2）你具备前端开发技术能力，涉足JSP（JSTL/EL）、Javascript、JQuery、VueJs、CSS、Html5一个或多个领域开发，并具备在浏览器开发者模式下做调试分析的基本能力。

基于以上条件，下面将以问答的形式，来解决大家的疑惑，给大家一个较为全面的V5前端引导。


## 目录

问题                            快速定位
V5用什么前端技术框架？                  快速跳转
如何判断某个功能页面使用的什么前端技术？          快速跳转
如何根据功能页面快速找到前端源码位置？           快速跳转
是否有各功能模块前端入门文档？               快速跳转
如何快速掌握V5平台JSP前端技能？            快速跳转
如何快速掌握V5平台CAP4 VueJs前端开发技能？   快速跳转
如何快速掌握移动端H5前端技能？              快速跳转


## V5用什么前端技术框架？



V5是具有十多年底蕴的产品体系，每年都会发一个或多个版，不同时期采用的技术具有差异。

以下是基于版本，简述每个模块所使用的前端技术：

版本      协同            公文    表单CAP3   新闻等其它模块   表单CAP4   PC新模块   致信      移动端
V5.0+   JSP           JSP   JSP      JSP       未涉及      未涉及     未涉及     未涉及
V7.1+   JSP           JSP   JSP      JSP       VueJS    未涉及     VueJS   Html5
V8.1+   JSP + VueJS   JSP   JSP      JSP       VueJS    VueJS   VueJs   Html5

以下是对前端技术的名词解释：

名词      解释                                                         V5适配组件
JSP     基于Html+Java代码混合开发的技术，早期主流技术，适合全栈开发经验工程师                    JSTL/EL、JQuery、SeeyonUI2.0、SeeyonUI3.0、SeeyonUI4.0（推荐）
VueJS   基于HTML、CSS和JavaScript的一整套前端解决方案，现今主流技术，可实现前后端分离，适合纯前端工程师   Ant-Design
Html5   新的Html标准，手机端浏览器大多都支持，固移动端主Html5技术                          CMP-UI

总结：

 * 如果你要进行公文的定制开发，则需要接触JSP相关前端技能
 * 如果你需要进行CAP4定制开发，则需要接触Vue相关前端技能
 * 如果你要做移动端（任何模块）的开发，则基于Html5再配合V5的CMP-UI组件库即可开发


## 如何判断某个功能页面使用的什么前端技术？



问题：新人在调试某个功能页面时，不知道其使用的什么前端技术，导致无法根据源码继续分析问题，有什么办法能快速知道当前页面使用的什么前端技术吗？

解决方案：

如果是移动端或致信端，答案是明确的 - 大部分使用的Html前后端分离技术。

而PC则不一样，有的是JSP，有的是VueJs，肉眼看不出来，则需要参照如下方式分析：

（1）开发人员鼠标停留在页面指定区域，然后鼠标右键选择“查看框架源代码”：



（2）浏览器随后会打开新选项卡，此时仔细看浏览器地址：如果地址中存在.do，则表示使用的JSP前端技术：



（3）同样方式，通过“查看框架源代码”访问CAP4相关页面，可以看到地址中存在.html，则表示使用的VueJs技术：




## 如何根据功能页面快速找到前端源码位置？



问题：作为不熟悉功能的新人，在看到功能页面后，最难的是找到这个页面的源码位置。

解决方案：

首先，你需要参考上一个问题，判断当前页面是JSP还是Html。

如果是.html路径则非常简单： 以下图为例，html文件路径为xxx/seeyon/common/cap4/template/bizconfig/setForm/index.html，则对应V5服务器seeyon目录下的html文件，非常明确：



如果是.do路径（JSP技术），则需要参考站内>技术平台>快速开始>问题调试分析方法>PC查找前端JSP位置方法的文档进行操作即可找到JSP。

以上，找到html或jsp源码文件后，再基于源码读代码，则可以一步步分析处理问题。

另外，有的代码是在Javascript中，你想快速知道js的源码位置，还可以参考站内>技术平台>快速开始>问题调试分析方法>快速查找前端源码位置方式来查询。


## 是否有各功能模块前端入门文档？



我们整理了一部分文档，参考站内>技术平台>前端技术>主要模块和前端代码位置，


## 我是个新人，如何快速掌握V5平台JSP前端技能？



第一步，如果你是全栈，首先要了解V5平台JSP技术前后端统一化的代码结构，通过站内>技术平台>快速开始>插件化开发来熟悉代码目录（如果你是纯前端，则需要有一位后端配合，让后端掌握插件化开发内容）。

第二步，全栈或前端都需要学习V5平台的JSP前端开发基础知识，通过站内>技术平台>前端技术>JSP前端开发方案来掌握JSP的基础内容。

第三步，你需要掌握基于JSP的V5平台前端组件，通过站内>技术平台>前端技术>JSP前端组件库来学习，后续开发过程，你将与组件库为伴。

第四步，你需要读一些产品的源码，以熟悉一个增删改查完整功能是如何实现的，如何根据功能页面找到源码位置前面小节已经给了方法。

最后，就是尝试新建一个JSP去开发一个功能，在不知道某个组件如何开发时，可以参考标准产品功能去看代码实现。

> 由于JSP历史悠久，并且近期主流功能已经不使用JSP，某些资料不一定全面，在遇到问题的时候，尽量多参考相似功能页面如何实现。


## 我是个新人，如何快速掌握V5平台CAP4 VueJs前端开发技能？



第一步，CAP4使用VueJs即可，首先，你需要掌握Vue和ES2015，并能正确配置Node.js v6.x及以上版本。

第二步，可以参考站内>应用平台>表单应用CAP4的文档进行全面学习和开发实践。


## 我是个新人，如何快速掌握移动端H5前端技能？



第一，可以参考站内>移动平台>移动H5应用开发全目录学习。

第二，移动H5开发也提供了完整的开发文档，访问站内地址学习：https://open.seeyoncloud.com/cmpdev/

第三，可以查阅培训视频，通过视频循序渐进学习：客开知识大纲3.0/09 移动开发

> 培训视频链接：链接：https://pan.baidu.com/s/1bPzZad2VEnDBuDetUytXMg 提取码：tpje
> 
> 编撰人：het


快速跳转



 * 前端快速开始
   * 前提条件
   * 目录
   * V5用什么前端技术框架？
   * 如何判断某个功能页面使用的什么前端技术？
   * 如何根据功能页面快速找到前端源码位置？
   * 是否有各功能模块前端入门文档？
   * 我是个新人，如何快速掌握V5平台JSP前端技能？
   * 我是个新人，如何快速掌握V5平台CAP4 VueJs前端开发技能？
   * 我是个新人，如何快速掌握移动端H5前端技能？



分享链接分享链接

## 147. 金格外部中间件JSAPI实现逻辑

> 原始路径：`/1842/1851/970.html`  
> 相对路径：`1842/1851/970.md`

## 金格外部中间件JSAPI实现逻辑


## ⅠPDF实现逻辑


## 控件加载要求

页面加载的时候需要初始化一个id为officeEditorFrame的ifram标签，并且加载basePdf.js，basePdf.js需要和iframe在同一个页面

示例：

<iframe id="officeEditorFrame" name="officeEditorFrame" 
         frameborder="0" height="100%" width="100%" scrolling="no" marginheight="0" marginwidth="0"></iframe>
 <script src="./basePdf.js"></script>



## 代码加载顺序

basePdf.js>pdf_kinggrid_brower.js

basePdf.js中通过懒加载的方式引入对应插件所需要的js


## 加载流程




## 各文件的作用

1、pdf.html：控件挂载点

2、pdfBrowser.css：样式文件

3、basePdf.js：调用pdf控件的基础js，提供了业务方法的调用

4、pdf.js：用于postMessage通信，根据插件类型懒加载对应插件所需的js，并返回加载消息给basePdf.js

5、enum.js：不同控件需要的js枚举

6、utils.js：实现一些内部所需要的工具方法

7、pdf_kinggrid_browse.js：金格pdf控件jsapi原型对象js

8、pdf_invoke.js：金格pdf控件jsapi双向通信封装的方法

9、tgPdf.js：金格控件jsapi插件端执行的js


## 实现逻辑

1、方法入口为basePdf.js中的initPdf()方法

	/**
     * 初始化控件
     * @param {*} params 
     */
    initPdf: async function (params, callBack) {
        //老控件需求
        PdfUtils.setEditorFrameOptions(params);
        // callback执行顺序 1: parasm.callback 2:第二个参数callback
        const data = await this.showPdfDiv(params.fileType, params.isFullSize, params.callback, params);
        if (typeof callBack == 'function') {
            callBack(data);
        }
        return data;
    }


2、initPdf()调用basePdf.js文件的showPdfDiv()方法

1).判断插件类型，根据环境判断当前插件是否可用（jsapi支持谷歌内核107以上，不支持mac环境、windows环境火狐浏览器不支持）

2).判断是否立即加载控件

3).调用loadHtmlForPlugin()加载pdf.html页面，懒加载js（basePdf.js与pdf.html中的pdf.js通过postMessage进行通信）pdf.html加载完成后basePdf.js会通过postMessage与pdf.js进行通信

关键代码：

> basePdf.js

if (iframeDom.attachEvent) {
	iframeDom.attachEvent("onload", async () => {
		var targetWindow = iframeDom.contentWindow;
		await this.emitMessage(param, targetWindow);
		resolve(targetWindow.PDFOffice);
	})
} else {
	iframeDom.onload = async () => {
		var targetWindow = iframeDom.contentWindow;
		await this.emitMessage(param, targetWindow);
		resolve(targetWindow.PDFOffice);
	}
}


以上代码标识pdf.html页面加载完成后向pdf.js发送消息，pdf.js会监听postMessage发送过来的消息，然后左响应的js加载

> pdf.js

/**
 * 懒加载js文件
 * @returns 
 */
function lazyLoadJS(params, callback) {
    return new Promise((resolve, reject) => {
        const {
            pluginType,
            webRoot
        } = params;
        let urls = JsFilesEnums[pluginType];
        // 文件接口拼接
        urls = urls.map(item => {
            if (item.needWebRoot) {
                return webRoot + item.jsUrl;
            } else {
                return item.jsUrl;
            }
        })
        loadJS(urls, () => {
            if (typeof callback == 'function') {
                callback();
            }
            resolve(true);
        });
    });
}


> 这里的控件类型是“kingsoft_pdf_jsapi”，因此会加载enum.js文件中JsFilesEnums对象中kingsoft_pdf_ppapi对应的js文件

4).实例化PDFOffice对象

5).调用PDFOffice对象的initPdf()初始化控件（pdf_kinggrid_browser.js对应的initPdf方法）

6).调用basePdf.js中的doShowPdfDiv()打开PDF控件，加载文档

3、doShowPdfDiv()调用basePdf.js中的loadPdf()加载文件

1).在每个插件对应的js中检查控件是否可用

2).设置记录文件打开值isLoadPdfFile

3).调用插件对应的loadPdf()加载pdf正文（pdf_kinggrid_browser.js文件中的loadPdf()）

4、调用pdf_kinggrid_brower.js文件中的loadPdf()方法

1).获取令牌，设置令牌

2).验证控件是否可用

// 获取证书
const verification = KGPdfUtils.getVerification();
// 验证PDF控件是否可用
// 第一步检测金格中间件应用 第二步检测iwebpdf是否安装
if (!this.isOfficeAvailable() || !await this.checkOfficeStatus(params)) {
   this.dialog();
   this.isLoading = false;
   return false;
}


3).如果控件可用，会调用唤起App，然后打开文件

const res = await KGBrowserPdfUtils.StartApp(params);
if(res){
	data = await KGBrowserPdfUtils.openFile(params);   //data就代表文档是否打开成功，如果不用打开或不用保存，则返回true
	setIsLoadPdfFile(data);
}else{
	setIsLoadPdfFile(false);
}


备注：这里的打开文件并不是真的打开，是调用pdf_invoke.js的openFile方法是发送了一个消息给tgPdf.js执行tgPdf.js中的openFile方法,发送消息见pdf_invoke.js如下：

/**
 * 金格JSAPI统一发送消息的方法
 * @param { String } func 需要执行的方法名称
 * @param { Object } params 参数信息
 */
function _KgInvoke(func, params = {}) {
    const { reqType = 'post' } = params;
    // 金格sdk中获取的方法
    return new Promise(function (resolve, reject) {
        if(KgPdfApp) {
            KgPdfApp.invoke({
                method: func.method,
                reqType: reqType,
                params: params,
                success: function (data) {
                    resolve(data);
                },
                error: function (err) {
                    reject(err);
                }
            });
        } else {
            reject(false);
        }
    });
}


4).调用initOcxMenu()进行菜单初始化

/**
 * 初始化菜单
 */
PDFOffice.prototype.initOcxMenu = function () {
    var pdfFun = document.getElementById("WebPDF").iWebPDFFun;
    pdfFun.AppendTools("101", KGPdfUtils.getPdfLanguage("menu_57"), 7);
}


5).调用adjustMenu()调整菜单显示

/**
 * 调整菜单显示
 */
PDFOffice.prototype.adjustMenu = function () {
try {
        //修改正文
        var pdfObj = document.getElementById("WebPDF").iWebPDFFun;
        pdfObj.Zoom = 100;
        var menuStr = "";
        var _canOpen = true;
        var hideMenuStr = "";
        var signMenu = "";
        if (parent.editType == "0,0" || parent.editType == "4,0") { //查看只读文档状态，不能打开文档，保存文档
            menuStr = "menu_1,menu_10,menu_89,menu_90";
            hideMenuStr = "menu_118";
            _canOpen = false;
            signMenu = ",menu_102,menu_103";
            try {
                pdfObj.AllowMoveAnnot = false;
            } catch (e) {}
        } else if (parent.editType == "1,0") { // 新建文档状态，可以打开文档，保存文档
            _canOpen = true;
        }
        /*************************************隐藏菜单开始***********************************************/
        for (var i = 2; i < 118; i++) {
            if (_canOpen) {
                if (i == 8 || i == 10 || i == 12 || i == 57 || i == 88 || i == 89 || i == 91 || i == 92 || i == 93 || i == 94 || i == 95 || i == 96 || i == 102 || i == 103 || i == 104 || i == 105 || i == 106 || i == 107 || i == 108) {
                    continue;
                }
                if(menuStr == ""){
                    menuStr = menuStr + "menu_" + i;
                }else{
                    menuStr = menuStr + ",menu_" + i;
                }
            } else {
                if (i == 8 || i == 10 || i == 12 || i == 51 || i == 52 || i == 57 || i == 88 || i == 91 || i == 92 || i == 93 || i == 94 || i == 95 || i == 96 || i == 102 || i == 103 || i == 104 || i == 105 || i == 106 || i == 107 || i == 108) {
                    continue;
                }
                if(menuStr == ""){
                    menuStr = menuStr + "menu_" + i;
                }else{
                    menuStr = menuStr + ",menu_" + i;
                }
            }
        }
        /*************************************隐藏菜单结束***********************************************/
        //-----------------------------
        var canSaveLocal = parent.contentSaveLocal && parent.contentSaveLocal == "true";
        canSaveLocal = canSaveLocal || parent.officecanSaveLocal && parent.officecanSaveLocal == "true";
        canSaveLocal = canSaveLocal || parent.parent.officecanSaveLocal && parent.parent.officecanSaveLocal == "true";
        //如果是快速发文,默认有下载权限
        if (parent.parent && parent.parent.isQuickSend === "true") {
            canSaveLocal = true;
        }
        //要禁用的菜单 本地另存为按钮 只有在没权限保存的时候禁用
        if (!canSaveLocal) {
            menuStr = menuStr + ",menu_8";
        }
        menuStr += signMenu;
        //-----------------------------
        //打印
        menuStr = this.setToolsPrintState(menuStr);
        menuStr = KGPdfUtils.getPdfLanguage(menuStr).replace(/,/g, ";");
        hideMenuStr = this.setToolsPrintState(hideMenuStr);
        hideMenuStr = KGPdfUtils.getPdfLanguage(hideMenuStr).replace(/,/g, ";");
        pdfObj.EnableTools(menuStr, 0);
        pdfObj.EnableTools(hideMenuStr, 2);
        pdfObj.EnableTools(KGPdfUtils.getPdfLanguage("menu_51,menu_52").replace(/,/g, ";"), 1);
        //文字选择按钮,控制复制粘特
        this.isAuthorityToCopy(pdfObj);
    } catch (e) {
        window.console && console.log(e);
    }
}



## Ⅱ Word、WPS实现逻辑


## 控件加载要求

页面加载的时候需要初始化一个id为officeEditorFrame的ifram标签，并且加载baseOffice.js，baseOffice.js需要和iframe在同一个页面

示例：

<iframe id="officeEditorFrame" name="officeEditorFrame" 
         frameborder="0" height="100%" width="100%" scrolling="no" marginheight="0" marginwidth="0"></iframe>
 <script src="./baseOffice.js"></script>



## 各文件的作用

 1. officeBrowse.html:挂载点

 2. officeBrower.css：样式文件

 3. baseOffice.js：调用pdf控件的基础js，提供了业务方法的调用

 4. kinggirdBaseOffice.js：金格office控件jsapi原型对象js

 5. kinggirdInvoke.js：金格office控件jsapi双向通信封装的方法

 6. tgOffice.js：金格控件jsapi插件端执行的js


## 实现逻辑

1、方法入口为baseOffice.js中的initOffice()方法

initOffice: async function(params) {
	await this.buildOfficePlugin(params);
}


2、调用buildOfficePlugin()方法

1).获取webOffice在线编辑的类型

2).获取是否启用了webOffice配置

3).如果是wps类型需要判断webOffice是否可用

4).如果webOffice不可用，并且客户端混网，没有购买国标office插件，就走金格

5).如果是非混网，或者pdf被wps打开了

3、调用baseOffice.js的setKinggriddPlugin()方法设置参数

1)、获取谷歌内核版本，如果是高于107版本就使用金格jsapi

2)、实例化金格插件对象，设置相关参数

4、调用kinggridBaseOffice.js的loadOffice()方法加载office

1).判断插件是否可用

2).调用_loadKGBrowerHtml()设置正文挂载点

3).设置一下最新的参数

4).判断金格app是否安装,控件未加载成功后续逻辑不再执行

5).调用checkOfficeStatus()检查控件即当前状态

6).调用kinggridOffice.js的StartApp()方法，备注：kinggridOffice.js的startApp()并不是打开控件，而是调用kinggridinvoke.js的StartApp()方法打开控件

7).调用kinggridOffice.closeDocumentByAll()关闭金格控件,这个方法会调用kinggridinvoke.js的closeDocumentByAll()方法，向tgOffice.js发送关闭文档的指令。备注：tgOffice.js是在金格外部中间件的浏览器中加载，OA不能直接调用，所有交互都是采用消息发送。

8).判断是否立即加载，如果需要立即加载再次调用startApp打开控件

7、打开金格外部中间件

调用kinggridOffice.js的StartApp()方法即可打开控件

编撰人：ranjunfeng、het、ranjf




快速跳转



 * 金格外部中间件JSAPI实现逻辑
   * ⅠPDF实现逻辑
     * 控件加载要求
     * 代码加载顺序
     * 加载流程
     * 各文件的作用
     * 实现逻辑
   * Ⅱ Word、WPS实现逻辑
     * 控件加载要求
     * 各文件的作用
     * 实现逻辑



分享链接分享链接

## 148. 金山中台预览增加SDK以实现打印旋转等功能

> 原始路径：`/1842/1851/971.html`  
> 相对路径：`1842/1851/971.md`

## 金山中台预览增加SDK以实现打印旋转等功能


## 改造背景

目前金山文档中台在线预览是请求金山文档中台预览接口返回预览地址，直接在页面上进行显示，此方案无法初始化金山文档中台的SDK，使用金山的SDK进行功能扩展。 比如追加实现打印、旋转、禁止pdf图片下载等功能。

本文档提供适配方法：实现初始化金山中台SDK，以方便做功能扩展。


## 适用版本

适用于V9.0及更老版本

> V9.0SP1版本已经内置SDK


## 改造方案

预览文件的时候根据金山文档中台预览接口获取到预览地址， 通过WebOfficeSDK.config 方法在指定的挂载节点下创建一个文档应用，url参数为预览接口返回的地址，其他参数可以根据需求自定义，此时就可以调用文档应用对象的打印、旋转等方法。


## 适配版本

本次适配的中台版本为v6、v7，金山v5版本不适用。


## 可参考代码

Ctp-Studio 客开复用插件：金山中台在线预览支持打印旋转下载




## 涉及的工程

apps-api、apps-common、apps-office-plugins-front、apps-office-plugins、ctp-common、ctp-core


## 支持功能

1、公文、协同所有类型的正文在线预览支持打印、下载； 2、正文打印支持节点权限控制； 3、word、excel、ppt、pdf、ofd格式的附件线预览支持打印、下载； 4、pdf格式文件在线预览禁用图片下载； 5、pdf、ofd正文、附件支持左旋转、右旋转。


## 改动点


## apps-api

修改java类com.seeyon.apps.officePlugins.util.OfficeFileUtil.java

在pdfExts数组变量中加入“ofd”，原因是金山文档中台ofd格式文件预览调用的是pdf的接口，如下所示：




## apps-common

新增open-jssdk-v0.0.11.umd.js文件

此文件为金山文档中台官方提供的在线预览的sdk文件


## apps-office-plugins-front

修改BuildConfig.js文件

将金山在线预览需要编译的文件加入到entrys变量中，如下图所示：



新增webOfficePreview.html文件

webOfficePreview.html文件为挂载在线预览的页面，用于将在线预览的地址挂载到此页面元素中，页面渲染的时候需要加载open-jssdk-v0.0.11.umd.js和webOfficePreview.js文件，代码如下：

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="Cache-control" content="no-cache">
    <meta http-equiv="Cache" content="no-cache">
    <title>在线预览</title>
    <script src="./../../js/polyfill.min.js?V=STATIC_SUFFIX"></script>
    <script src="./../../js/V3X.js?V=STATIC_SUFFIX"></script>

    <script type="text/javascript">
        var v3x = new V3X();
    </script>
    <style type="text/css">
        body,
        html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: rgb(243, 243, 243);
        }

        .plugin-container {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
        }

        .container {
            width: 100%;
            height: 100%;
        }

        .content {
            position: absolute;
            width: 410px;
            height: 220px;
            top: calc(50% - 110px);
            left: calc(50% - 205px);
        }

        .item {
            text-align: center;
        }

        .item img {
            width: 360px;
            height: auto;
            margin: 0 auto;
        }

        .tips {
            font-size: 14px;
            color: #999999;
            font-family: Arial, "Ping Fang SC", "Microsoft YaHei", Helvetica, sans-serif, "SimSun"
        }

        .edit {
            font-size: 14px;
            color: #FFFFFF;
            background: #5087E5;
            border: none;
            border-radius: 5px;
            width: 120px;
            height: 35px;
            margin-top: 20px;
            outline: none;
        }

        .edit:hover {
            cursor: pointer;
            transform: scale(1.1);
        }

        .edit:active {
            border: none;
        }
        #officeToolbar{
            border-bottom:1px solid #e2e6ed;
        }
        .icons{
            vertical-align: middle;
            display: inline-block;
            background-repeat: no-repeat;
            background-size: 100% 100%;
            flex-shrink: 0;
            width:16px;
            height:16px;
        }
        .icons-rotate-left{
            background-image:url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNjk5MzM0MDYwNzQ5IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjIyNDY4IiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgd2lkdGg9IjIwMCIgaGVpZ2h0PSIyMDAiPjxwYXRoIGQ9Ik05MjQuOCAzMzcuNmMtMjIuNi01My40LTU0LjktMTAxLjMtOTYtMTQyLjRzLTg5LTczLjQtMTQyLjQtOTZDNjMxLjEgNzUuOSA1NzIuNSA2NCA1MTIgNjRTMzkyLjkgNzUuOSAzMzcuNiA5OS4yYy01My40IDIyLjYtMTAxLjMgNTQuOS0xNDIuNCA5Ni0yMi40IDIyLjQtNDIuMiA0Ni44LTU5LjIgNzMuMVYyMjhjMC0xOS44LTE2LjItMzYtMzYtMzZzLTM2IDE2LjItMzYgMzZ2Mjg4YzAgMTkuOCAxNi4yIDM2IDM2IDM2czM2LTE2LjIgMzYtMzZ2LTUwLjJjNC4yLTM0LjggMTMuMi02OC43IDI3LTEwMS4yIDE5LjEtNDUuMSA0Ni40LTg1LjYgODEuMi0xMjAuNEMyNzkgMjA5LjQgMzE5LjUgMTgyIDM2NC42IDE2M2M0Ni43LTE5LjcgOTYuMy0yOS44IDE0Ny40LTI5LjggNTEuMiAwIDEwMC44IDEwIDE0Ny40IDI5LjggNDUuMSAxOS4xIDg1LjYgNDYuNCAxMjAuNCA4MS4yQzgxNC42IDI3OSA4NDIgMzE5LjUgODYxIDM2NC42YzE5LjcgNDYuNyAyOS44IDk2LjMgMjkuOCAxNDcuNCAwIDUxLjItMTAgMTAwLjgtMjkuOCAxNDcuNC0xOS4xIDQ1LjEtNDYuNCA4NS42LTgxLjIgMTIwLjRDNzQ1IDgxNC42IDcwNC41IDg0MiA2NTkuNCA4NjFjLTQ2LjcgMTkuNy05Ni4zIDI5LjgtMTQ3LjQgMjkuOC02NC42IDAtMTI4LjQtMTYuNS0xODQuNC00Ny44LTU0LjQtMzAuNC0xMDAuOS03NC4xLTEzNC42LTEyNi42LTEwLjMtMTYuMS0zMS43LTIwLjgtNDcuOC0xMC40LTE2LjEgMTAuMy0yMC44IDMxLjctMTAuNCA0Ny44IDM5LjggNjIgOTQuOCAxMTMuNyAxNTkuMSAxNDkuNiA2Ni4yIDM3IDE0MS43IDU2LjYgMjE4LjEgNTYuNiA2MC41IDAgMTE5LjEtMTEuOSAxNzQuNC0zNS4yIDUzLjQtMjIuNiAxMDEuMy01NC45IDE0Mi40LTk2IDQxLjEtNDEuMSA3My40LTg5IDk2LTE0Mi40Qzk0OC4xIDYzMS4xIDk2MCA1NzIuNSA5NjAgNTEycy0xMS45LTExOS4xLTM1LjItMTc0LjR6IiBmaWxsPSIjMzMzMzMzIiBwLWlkPSIyMjQ2OSI+PC9wYXRoPjxwYXRoIGQ9Ik0yNzUuNCA1NzUuNWM5LjUtMi41IDE5LjEgMi45IDIyLjMgMTIuMiAzLjUgMTAuMiA5LjkgMTcuNyAxOS4xIDIyLjYgNy4xIDMuOSAxNS4xIDUuOCAyNCA1LjggMTYuNiAwIDMwLjgtNi45IDQyLjUtMjAuOCAxMS43LTEzLjggMjAtMzIuNyAyNC45LTc1LjEtNy43IDEyLjItMTcuMyAyMC44LTI4LjcgMjUuOC0xMS40IDUtMjMuNyA3LjQtMzYuOCA3LjQtMjYuNyAwLTQ3LjctOC4zLTYzLjMtMjQuOS0xNS41LTE2LjYtMjMuMy0zNy45LTIzLjMtNjQuMSAwLTI1LjEgNy43LTQ3LjEgMjMtNjYuMiAxNS4zLTE5IDM3LjktMjguNiA2Ny44LTI4LjYgNDAuMyAwIDY4LjEgMTguMSA4My40IDU0LjQgOC41IDE5LjkgMTIuNyA0NC45IDEyLjcgNzQuOSAwIDMzLjgtNS4xIDYzLjgtMTUuMyA4OS45LTE2LjkgNDMuNS00NS41IDY1LjItODUuOCA2NS4yLTI3IDAtNDcuNi03LjEtNjEuNi0yMS4yLTEwLTEwLjEtMTYuNC0yMi0xOS4zLTM1LjgtMi05LjYgNC0xOS4xIDEzLjUtMjEuNmwwLjkgMC4xeiBtMTAzLTc0LjRjOS40LTcuNSAxNC4xLTIwLjYgMTQuMS0zOS4zIDAtMTYuOC00LjItMjkuMy0xMi43LTM3LjVTMzYwLjYgNDEyIDM0Ny41IDQxMmMtMTQgMC0yNS4yIDQuNy0zMy40IDE0LjEtOC4yIDkuNC0xMi40IDIyLTEyLjQgMzcuNyAwIDE0LjkgMy42IDI2LjcgMTAuOSAzNS41IDcuMiA4LjggMTguOCAxMy4xIDM0LjYgMTMuMSAxMS40IDAgMjEuOC0zLjggMzEuMi0xMS4zek02NDYuNiA0MTQuNGMxMi40IDIyLjggMTguNSA1NCAxOC41IDkzLjcgMCAzNy42LTUuNiA2OC43LTE2LjggOTMuMy0xNi4yIDM1LjMtNDIuOCA1Mi45LTc5LjYgNTIuOS0zMy4yIDAtNTcuOS0xNC40LTc0LjItNDMuMy0xMy41LTI0LjEtMjAuMy01Ni40LTIwLjMtOTcgMC0zMS40IDQuMS01OC40IDEyLjItODAuOSAxNS4yLTQyIDQyLjctNjMgODIuNS02MyAzNS45IDAgNjEuOCAxNC44IDc3LjcgNDQuM3ogbS00MC4yIDE3My4zYzkuNC0xMy45IDE0LTM5LjkgMTQtNzggMC0yNy40LTMuNC01MC0xMC4xLTY3LjctNi44LTE3LjctMTkuOS0yNi42LTM5LjQtMjYuNi0xNy45IDAtMzEgOC40LTM5LjMgMjUuMi04LjMgMTYuOC0xMi40IDQxLjYtMTIuNCA3NC4zIDAgMjQuNiAyLjYgNDQuNCA3LjkgNTkuNCA4LjEgMjIuOCAyMiAzNC4zIDQxLjYgMzQuMyAxNS43IDAgMjguMy03IDM3LjctMjAuOXpNODAzLjMgMzg3LjJjMTEuMiAxMS4zIDE2LjggMjUgMTYuOCA0MS4yIDAgMTYuNy01LjggMzAuNy0xNy41IDQxLjhDNzkxIDQ4MS40IDc3Ny40IDQ4NyA3NjIgNDg3Yy0xNy4xIDAtMzEuMi01LjgtNDIuMS0xNy40LTEwLjktMTEuNi0xNi40LTI1LjEtMTYuNC00MC42IDAtMTYuNSA1LjgtMzAuNCAxNy4zLTQxLjcgMTEuNS0xMS4zIDI1LjMtMTcgNDEuMi0xNyAxNi4zIDAgMzAuMSA1LjcgNDEuMyAxNi45ek03MzkuNSA0NTFjNi4yIDYuMiAxMy43IDkuMyAyMi41IDkuMyA4LjQgMCAxNS44LTMuMSAyMi4xLTkuMyA2LjMtNi4yIDkuNC0xMy43IDkuNC0yMi42IDAtOC41LTMuMS0xNS45LTkuMy0yMi4xLTYuMi02LjItMTMuNi05LjMtMjIuMi05LjNzLTE2LjEgMy4xLTIyLjQgOS4zYy02LjMgNi4yLTkuNCAxMy43LTkuNCAyMi42LTAuMSA4LjQgMyAxNS44IDkuMyAyMi4xeiIgZmlsbD0iIzMzMzMzMyIgcC1pZD0iMjI0NzAiPjwvcGF0aD48L3N2Zz4=")
        }
        .icons-rotate-right{
            background-image:url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/PjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI+PHN2ZyB0PSIxNjk5MzM0NjY5NzI0IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjQwODA5IiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgd2lkdGg9IjIwMCIgaGVpZ2h0PSIyMDAiPjxwYXRoIGQ9Ik0xNDY0LjMgMjc5LjciIGZpbGw9IiMzMzMzMzMiIHAtaWQ9IjQwODEwIj48L3BhdGg+PHBhdGggZD0iTTUxMiA5NjBjLTYwLjUgMC0xMTkuMS0xMS45LTE3NC40LTM1LjItNTMuNC0yMi42LTEwMS4zLTU0LjktMTQyLjQtOTZzLTczLjQtODktOTYtMTQyLjRDNzUuOSA2MzEuMSA2NCA1NzIuNSA2NCA1MTJzMTEuOS0xMTkuMSAzNS4yLTE3NC40YzIyLjYtNTMuNCA1NC45LTEwMS4zIDk2LTE0Mi40czg5LTczLjQgMTQyLjQtOTZDMzkyLjkgNzUuOSA0NTEuNSA2NCA1MTIgNjRzMTE5LjEgMTEuOSAxNzQuNCAzNS4yYzUzLjQgMjIuNiAxMDEuMyA1NC45IDE0Mi40IDk2czczLjQgODkgOTYgMTQyLjRDOTQ4LjEgMzkyLjkgOTYwIDQ1MS41IDk2MCA1MTJjMCAxOS4xLTE1LjUgMzQuNi0zNC42IDM0LjZzLTM0LjYtMTUuNS0zNC42LTM0LjZjMC01MS4yLTEwLTEwMC44LTI5LjgtMTQ3LjQtMTkuMS00NS4xLTQ2LjQtODUuNi04MS4yLTEyMC40Qzc0NSAyMDkuNCA3MDQuNSAxODIgNjU5LjQgMTYzYy00Ni43LTE5LjctOTYuMy0yOS44LTE0Ny40LTI5LjgtNTEuMiAwLTEwMC44IDEwLTE0Ny40IDI5LjgtNDUuMSAxOS4xLTg1LjYgNDYuNC0xMjAuNCA4MS4yUzE4MiAzMTkuNSAxNjMgMzY0LjZjLTE5LjcgNDYuNy0yOS44IDk2LjMtMjkuOCAxNDcuNCAwIDUxLjIgMTAgMTAwLjggMjkuOCAxNDcuNCAxOS4xIDQ1LjEgNDYuNCA4NS42IDgxLjIgMTIwLjRDMjc5IDgxNC42IDMxOS41IDg0MiAzNjQuNiA4NjFjNDYuNyAxOS43IDk2LjMgMjkuOCAxNDcuNCAyOS44IDY0LjYgMCAxMjguNC0xNi41IDE4NC40LTQ3LjggNTQuNC0zMC40IDEwMC45LTc0LjEgMTM0LjYtMTI2LjYgMTAuMy0xNi4xIDMxLjctMjAuOCA0Ny44LTEwLjQgMTYuMSAxMC4zIDIwLjggMzEuNyAxMC40IDQ3LjgtMzkuOCA2Mi05NC44IDExMy43LTE1OS4xIDE0OS42LTY2LjIgMzctMTQxLjcgNTYuNi0yMTguMSA1Ni42eiIgZmlsbD0iIzMzMzMzMyIgcC1pZD0iNDA4MTEiPjwvcGF0aD48cGF0aCBkPSJNOTI0IDU1MmMtMTkuOCAwLTM2LTE2LjItMzYtMzZWMjI4YzAtMTkuOCAxNi4yLTM2IDM2LTM2czM2IDE2LjIgMzYgMzZ2Mjg4YzAgMTkuOC0xNi4yIDM2LTM2IDM2ek0yNzUuNCA1NzUuNWM5LjUtMi41IDE5LjEgMi45IDIyLjMgMTIuMiAzLjUgMTAuMiA5LjkgMTcuNyAxOS4xIDIyLjYgNy4xIDMuOSAxNS4xIDUuOCAyNCA1LjggMTYuNiAwIDMwLjgtNi45IDQyLjUtMjAuOCAxMS43LTEzLjggMjAtMzIuNyAyNC45LTc1LjEtNy43IDEyLjItMTcuMyAyMC44LTI4LjcgMjUuOC0xMS40IDUtMjMuNyA3LjQtMzYuOCA3LjQtMjYuNyAwLTQ3LjctOC4zLTYzLjMtMjQuOS0xNS41LTE2LjYtMjMuMy0zNy45LTIzLjMtNjQuMSAwLTI1LjEgNy43LTQ3LjEgMjMtNjYuMiAxNS4zLTE5IDM3LjktMjguNiA2Ny44LTI4LjYgNDAuMyAwIDY4LjEgMTguMSA4My40IDU0LjQgOC41IDE5LjkgMTIuNyA0NC45IDEyLjcgNzQuOSAwIDMzLjgtNS4xIDYzLjgtMTUuMyA4OS45LTE2LjkgNDMuNS00NS41IDY1LjItODUuOCA2NS4yLTI3IDAtNDcuNi03LjEtNjEuNi0yMS4yLTEwLTEwLjEtMTYuNC0yMi0xOS4zLTM1LjgtMi05LjYgNC0xOS4xIDEzLjUtMjEuNmwwLjkgMC4xeiBtMTAzLTc0LjRjOS40LTcuNSAxNC4xLTIwLjYgMTQuMS0zOS4zIDAtMTYuOC00LjItMjkuMy0xMi43LTM3LjVTMzYwLjYgNDEyIDM0Ny41IDQxMmMtMTQgMC0yNS4yIDQuNy0zMy40IDE0LjEtOC4yIDkuNC0xMi40IDIyLTEyLjQgMzcuNyAwIDE0LjkgMy42IDI2LjcgMTAuOSAzNS41IDcuMiA4LjggMTguOCAxMy4xIDM0LjYgMTMuMSAxMS40IDAgMjEuOC0zLjggMzEuMi0xMS4zek02NDYuNiA0MTQuNGMxMi40IDIyLjggMTguNSA1NCAxOC41IDkzLjcgMCAzNy42LTUuNiA2OC43LTE2LjggOTMuMy0xNi4yIDM1LjMtNDIuOCA1Mi45LTc5LjYgNTIuOS0zMy4yIDAtNTcuOS0xNC40LTc0LjItNDMuMy0xMy41LTI0LjEtMjAuMy01Ni40LTIwLjMtOTcgMC0zMS40IDQuMS01OC40IDEyLjItODAuOSAxNS4yLTQyIDQyLjctNjMgODIuNS02MyAzNS45IDAgNjEuOCAxNC44IDc3LjcgNDQuM3ogbS00MC4yIDE3My4zYzkuNC0xMy45IDE0LTM5LjkgMTQtNzggMC0yNy40LTMuNC01MC0xMC4xLTY3LjctNi44LTE3LjctMTkuOS0yNi42LTM5LjQtMjYuNi0xNy45IDAtMzEgOC40LTM5LjMgMjUuMi04LjMgMTYuOC0xMi40IDQxLjYtMTIuNCA3NC4zIDAgMjQuNiAyLjYgNDQuNCA3LjkgNTkuNCA4LjEgMjIuOCAyMiAzNC4zIDQxLjYgMzQuMyAxNS43IDAgMjguMy03IDM3LjctMjAuOXpNODAzLjMgMzg3LjJjMTEuMiAxMS4zIDE2LjggMjUgMTYuOCA0MS4yIDAgMTYuNy01LjggMzAuNy0xNy41IDQxLjhDNzkxIDQ4MS40IDc3Ny40IDQ4NyA3NjIgNDg3Yy0xNy4xIDAtMzEuMi01LjgtNDIuMS0xNy40LTEwLjktMTEuNi0xNi40LTI1LjEtMTYuNC00MC42IDAtMTYuNSA1LjgtMzAuNCAxNy4zLTQxLjcgMTEuNS0xMS4zIDI1LjMtMTcgNDEuMi0xNyAxNi4zIDAgMzAuMSA1LjcgNDEuMyAxNi45ek03MzkuNSA0NTFjNi4yIDYuMiAxMy43IDkuMyAyMi41IDkuMyA4LjQgMCAxNS44LTMuMSAyMi4xLTkuMyA2LjMtNi4yIDkuNC0xMy43IDkuNC0yMi42IDAtOC41LTMuMS0xNS45LTkuMy0yMi4xLTYuMi02LjItMTMuNi05LjMtMjIuMi05LjNzLTE2LjEgMy4xLTIyLjQgOS4zYy02LjMgNi4yLTkuNCAxMy43LTkuNCAyMi42LTAuMSA4LjQgMyAxNS44IDkuMyAyMi4xeiIgZmlsbD0iIzMzMzMzMyIgcC1pZD0iNDA4MTIiPjwvcGF0aD48L3N2Zz4=");
        }
        .icons-print{
            background-image:url("data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSIjM0Q0NzU3IiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0xMiA0aC0xVjJINXYySDRWMmExIDEgMCAwMTEtMWg2YTEgMSAwIDAxMSAxdjJ6bTAgNXY0YTEgMSAwIDAxLTEgMUg1YTEgMSAwIDAxLTEtMVY5aDF2NGg2VjloMXoiLz48cGF0aCBkPSJNMTIgMTJ2LTFoMlY1SDJ2NmgydjFIMmExIDEgMCAwMS0xLTFWNWExIDEgMCAwMTEtMWgxMmExIDEgMCAwMTEgMXY2YTEgMSAwIDAxLTEgMWgtMnoiLz48cGF0aCBkPSJNMyA4aDEwdjFIM3ptOC0yaDJ2MWgtMnoiLz48L2c+PC9zdmc+");
        }
        .icons-download{
            background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAYAAACqaXHeAAAAAXNSR0IArs4c6QAAA9dJREFUeF7tm01oE1EQx/+zKRQv6kkvCoJ6UC9exEOT+FFMInhqm6SFHgQVL0JFDyIIVr2ICJ68iIIgYj7EL5Rm14prNn4i9CCIiOBB8CAo+HEwxezIBltjPva9TZt0Y94e8+bNe/PbmXnDyyyhyx/qcvuhACgPkCAQig33EzjBjO0A1khMabfIF4B0ZpgFI3XBy+LCEAhGEuNEdNyL0gWVJRhWLh2V3YMrgNDO+HrY2lMAi2UV+kGOmfbLeoI7gGjyHICDfjDK6x6mtZ4lzyeufhPNcwUQjianGNg4o8TS08KQES3YqvGaUNXsDdZE9rVoPZEHcKWCTgLARNsKuZSpAAgIKA9wAxSKJlUIqBxQQUAlwQ46BtUpoI5BVQe0txAKxoa3wra3iiqvinHniK1Xh9T7vfxbwciMN9JfXQq3PQc4AIj5oQcAnkSZ+YQCoDzA/yHQspsjZn7k6xDwFNAtEF7wJNgCmzyp7HoAoR2JUWh0ZYZa249BT6+rRcLByPApIj7mqO9KAI7h4Wgyw0C87QDKlWCTj8zdnazq/v6R5dM9tsFEYzJ65+1KrNlKUPZNyQIoe0EkEbY1TetaAA4E54V0NQBZj/kvQ0DWeEdu3gB4WbRZ2XqJVsbN3dbrLAC1/1Sblp7e1izQzvMABaCmV0F5gAoBlQNUElSngDoG50BAFUJu8BaiQeJPa96QpadPVu+tTs9i3TogHEsO2ECgkEtnRc7hKw/4Y3wGwAZiHM0b6dOVBsgACEaSu4hwC0CACQkRBN8AqDR+1miiQ1Yu5fQqlh8RgL5IfIcG7TYIi/5ejrpD8A2ARi25DD5Q0DPnRQC2RIdDNvgOgKX/uD3xdSuXSTj3pPXCwTcAGhhY3jMR7c3nUpcaecCWWHKTzXwXoGVVRt4KFNfFTXP8V6Nc4CsArhAYozZ4bVXjtgnSxsClewCtqDLybqC4KG6al3923H1Aw3BgPlEDAFgJYPW/RnIuUOS4aWZ/dNQpIMj49WxxeoHXVw1M9pbsocnJ7FeR8b6/EGniWwWz+Gt66MWDm59ljPc9ALecUGsgF0rcO/jEuPJJ1ngZAM8AbJ5RuFCNkiJPIMazEtPg4/upj16MFwIIR5NnGTjsVakH+bdMtF/mZrdxYsRLDTSQN1IfPKw7K+qHT2a+E2F3Ppe+ITKgDoQpYnswb2Tfi+Y2VQd4i8FmtzA7b5+lpy+KtMxCYLwKkD1g6tl3ojlN1wEzE/tiI0GN7T0AnH+AV81lQfe5fMTSM2dE+h0IPQikTOPaG5GsaNy33wCJNj5f4wrAfJHsVD1d7wG/AbuI0V8xA0d0AAAAAElFTkSuQmCC")
        }
        .btn{
            line-height: 40px;
            margin-left: 3px;
            margin-right: 3px;
            padding:2px 5px 2px 5px;
            cursor:pointer;
        }
        .btn-text{
            font-size:12px;
        }
        .btn:hover{
            background:#c0c6cf;
        }
    </style>
</head>

</head>

<body>
<div style="text-align: center;height:40px;display: none" id="officeToolbar">
        <span onclick="topPrint()" id="print" class="btn">
            <i class="icons icons-print"></i>
            <span class="btn-text">打印</span>
        </span>
    <span id="left-rotate" onclick="topRotate(-90)" class="btn">
            <i class="icons icons-rotate-left"></i>
            <span class="btn-text">左旋转</span>
        </span>
    <span id="right-rotate" onclick="topRotate(90)" class="btn">
            <i class="icons icons-rotate-right"></i>
            <span class="btn-text">右旋转</span>
        </span>
    <span onclick="topDownload()" class="btn">
            <i class="icons icons-download"></i>
            <span class="btn-text">下载</span>
        </span>
</div>
<div id="pluginContainer" class="plugin-container">
    <div class="container" style="height: 100% ;width: 100%;">
        <div class="content" id="wpsPdfContent" style="display: none;">

        </div>

    </div>
</div>
<script type="text/javascript" src="./../../js/jquery-debug.js?V=STATIC_SUFFIX"></script>
<script type="text/javascript" src="./../js/open-jssdk-v0.0.11.umd.js?V=STATIC_SUFFIX"></script>
<script type="text/javascript" src="./../js/webOffice/webOfficePreview.js?V=STATIC_SUFFIX"></script>
</body>

</html>


新增webOfficePreview.js文件

webOfficePreivew.js文件为在线预览的核心文件，用于获取金山文档中台预览地址、挂载预览地址、打印、旋转等

var webOfficeObj={};
var fileId;
var fileName;
var fileType;
var ctxPath="";
var viewUrl="";
var userAgentForm="pc";
window.onload = function () {
    var queryParams = getQueryParams();
    var officeToolbar=$(document.getElementById("officeToolbar"));
    var pluginContainer=$(document.getElementById("pluginContainer"));
    fileId=queryParams.fileId;
    fileName=queryParams.fileName;
    viewUrl=queryParams.viewUrl;
    ctxPath=queryParams.ctxPath;
    userAgentForm=queryParams.userAgentForm;
    if(fileName.lastIndexOf(".")>0){
        fileName=fileName.substring(0,fileName.lastIndexOf("."))
    }
    fileType=queryParams.fileSuffix;

    officeToolbar.show();
    if(userAgentForm=="pc") {
        if (top.officecanPrint == "false" || top.isFromTraceFlag) {
            $(document.getElementById("print")).hide();
        }
        if (fileId != top.fileId && fileId != top.pdfFileId && fileId != top.ofdFileId) {
            $(document.getElementById("print")).show();
        }
    }else{
        $(document.getElementById("print")).hide();
    }
    $(pluginContainer).height($(pluginContainer).height()-51);
    if(typeof(fileType)!="undefined"&&(fileType!="pdf"&&fileType!="ofd")){
        $(document.getElementById("right-rotate")).hide();
        $(document.getElementById("left-rotate")).hide();
    }
    loadFile()
}
/**
 * 获取token信息
 * @returns
 */
function getToken() {
    var webRoot=window.location.origin + ctxPath;
    let xhrFun = getAjaxFunc();
    return new Promise(function(resolve,reject){
        xhrFun({
            url: webRoot + '/webOfficeTolen.do?tko=WebOffice&m=k',
            type: 'GET',
            success: function(msg, status, xhr) {
                const token = xhr.getResponseHeader('tolen');
                const maxRetryTimes = 1;
                let hasRetryTimes = 0;
                const rollTime = 60 * 1000;

                const dealFail = () => {
                    // 允许网络不稳定，重试
                    if(hasRetryTimes >= maxRetryTimes){
                        // TODO  提示
                        const res = confirm("正文保存数据心跳失败，请保存数据到本地，重新打开页面!");
                        if(res){
                            return false;
                        }
                    }
                    hasRetryTimes++;
                    console.debug("delay RetryTimes[" + hasRetryTimes + "]");
                    return true;
                }

                const doDelay = () => {
                    xhrFun({
                        url:webRoot + '/webOfficeTolen.do?tko=WebOffice&m=u&tolen=' + token,
                        headers: {
                            'tolen':token
                        },
                        success: function(msg,status,xhr) {
                            //val
                            var val = xhr.getResponseHeader('val');
                            if(val == "1"){
                                console.debug("delay ok!");
                                // reset
                                hasRetryTimes = 0;
                                setTimeout(doDelay, rollTime);
                            }else{
                                if(dealFail()){
                                    setTimeout(doDelay, rollTime);
                                }
                            }
                        },
                        error:function(XMLHttpRequest, textStatus, errorThrown){
                            if(dealFail()){
                                setTimeout(doDelay, rollTime);
                            }
                        }
                    })
                }
                setTimeout(doDelay, rollTime);
                resolve(token);
            },
            error: function() {
                resolve(false);
            }
        })
    })
}
// 获取ajax
function getAjaxFunc() {
    return $.ajax ? $.ajax : window.top.jQuery.ajax;
}

function loadFile(){
    return new Promise(async (reslve, reject) => {
        const tolen = await getToken();
        const url = viewUrl + "&v=" + new Date().getTime()
        const refreshToken = () => {
            // 获取 token 函数
            return Promise.resolve({
                token: tolen, // 必需：你需要设置的 toekn
                timeout: 10 * 60 * 1000, //  必需：token 超时时间，以 10 分钟示例
            });
        };
        // 清空节点
        let dom = document.querySelector("#wpsPdfContent");
        dom.innerHTML = "";
        dom.setAttribute("class", "");
        dom.setAttribute("style", "width: 100%; height: 100%");
        webOfficeObj = OpenSDK.config({
            url: url,
            refreshToken,
            mount: dom,
            pdfOptions:{
                isInSafeMode:false,
            }
        });
        // 	文档打开事件
        webOfficeObj.on('fileOpen', (data) => {
            console.log('文件打开:', data);
            reslve(data);
        });
        if(tolen) {
            webOfficeObj.setToken({token: tolen,timeout: 10 * 60 * 1000})
        }
        //如果执行wps.ready()后不再往下执行，极大可能是因为weboffice在线编辑文档不可见
        console.log("init:wps.ready() 开始 ....");
        await webOfficeObj.ready();
        let officeIframe=document.querySelector("#office-iframe");
        officeIframe.setAttribute("style", "width: 100%; height: 100%");
        console.log("init:初始 wps.ready() 已执行");

    })
}
var currentAngle=0;
window.topPrint = async function topPrint(){
    webOfficeObj.executeCommandBar('TabPrintPreview');
}
window.topRotate=function topRotate(angle){
    currentAngle=currentAngle+angle;
    if(currentAngle>=360){
        currentAngle=currentAngle-360;
    }else if(currentAngle<0){
        currentAngle=360+angle;
    }
    webOfficeObj.Application.ActivePDF.RotatePage(currentAngle);
}
window.topDownload=function topDownload(){
    if(webOfficeObj){
        let xhrFun = getAjaxFunc();
        var webRoot = window.location.origin + ctxPath
        xhrFun({
            url: webRoot + "/rest/webOffice/getSecuritySeed?recordId=" + fileId + "&originalFileId=", //获取加密种子地址
            type: 'GET',
            success: function success(msg) {
                if (msg.code == 0) { //获取加密种子成功
                    const v = msg.data;
                    var realFilename = fileName;
                    realFilename += "."+fileType;
                    realFilename = realFilename.replace(/[\r\n]/g, "");
                    var downlaodUrl = webRoot + "/fileDownload.do?method=download&fileId=" + fileId + "&v=" + v + "&filename=" + encodeURIat(realFilename);
                    var a = document.createElement("a");
                    a.href = downlaodUrl;
                    a.download = realFilename;
                    a.target = "downloadFileFrame";
                    $("body") ? $("body").append(a) : document.body.append(a); // 修复firefox中无法触发click
                    a.click();
                    $(a).remove();
                } else {//文件不能下载的时候的操作
                }
            },
            error: function (err) {
                Alert(err);
            }
        });

    }
}



## apps-office-plugins

1、com.seeyon.apps.officePlugins.enums.WebOfficeEnums.java

在TypeEnum枚举中增加OnlinePreviewForV6枚举，如图所示：



2、com.seeyon.apps.officePlugins.helper.WebOfficeURLHelper.java

1)、增加setHeadersForWps4方法

public HttpHeaders setHeadersForWps4(URI url,HttpHeaders headers){
        String path=url.getPath()+"?"+url.getQuery();
        if (path.startsWith("/open")) {
            path = path.replace("/open", "");
        }
        String sha256body="";
        //日期格式化
        DateFormat dateFormat = new SimpleDateFormat("EEE, dd MMM yyyy HH:mm:ss 'GMT'", Locale.US);
        dateFormat.setTimeZone(TimeZone.getTimeZone("GMT"));
        String date = dateFormat.format(new Date());
        String signature = null;
        try {
            signature = HMacUtil.HMACSHA256("WPS-4GET" +
                    path + "application/json" + date + sha256body, SystemGlobalConstant.WEBOFFICE_APPKEY);
        } catch (Exception e) {
            e.printStackTrace();
        }
        headers.add("Wps-Docs-Date",date);
        headers.add("Wps-Docs-Authorization", String.format("WPS-4 %s:%s", SystemGlobalConstant.WEBOFFICE_APPID, signature));
        return headers;
    }


2)、修改mapToWebOfficeUrlForPri方法

	/**
	 * weboffice为内网，map参数转为weboffice需要的url参数（代签名）
	 *
	 * @param params   需要组装的第3方参数
	 * @param typeEnum Url类型
	 * @return
	 * @throws BusinessException
	 */
	public String mapToWebOfficeUrlForPri(Map<String, Object> params, WebOfficeEnums.UrlTypeEnum typeEnum) throws BusinessException {
		if(MapUtils.isEmpty(params) && WebOfficeEnums.UrlTypeEnum.OnlineEdit.getKey().equals(typeEnum.getKey())){
			return null;
		}
		Boolean isPreview=false;
		//判断是否为预览
		if(params!=null&&params.get("viewMode")!=null&&params.get("viewMode").equals("view")) {
			isPreview=true;
		}
		String token = createAppToken(typeEnum);

		if(WebOfficeEnums.UrlTypeEnum.ContentFormat.getKey().equals(typeEnum.getKey())){
			return token;
		}
		String callBackUrl = SystemProperties.getInstance().getProperty("officeTrans.wps.callBackUrl");
		Boolean isV6=callBackUrl.contains("/webOffice/v6");
		UriComponentsBuilder builder;
		if(isV6&&isPreview) {
			builder = UriComponentsBuilder
					.fromHttpUrl(this.webOfficeUrl + WebOfficeEnums.UrlTypeEnum.OnlinePreviewForV6.getUrl().replace("{file_id}", MapUtils.getString(params, "fileId")));
		} else {
			// 设置token，生成weboffice认证后的url
			builder = UriComponentsBuilder
					.fromHttpUrl(this.webOfficeUrl + typeEnum.getUrl());
			builder.queryParam("app_token", token);
			builder.queryParam("file_id", MapUtils.getString(params, "fileId"));
		}
        String fileTypeCode= OfficeFileUtil.getFileTypeCode(MapUtils.getString(params, "fileType"));
        if(fileTypeCode!=null){
			// 在线编辑，需要增加type参数
			builder.queryParam("type", OfficeFileUtil.getFileTypeCode(MapUtils.getString(params, "fileType")));
		}
		params.forEach((k,v)->{
			if(v!=null){
				builder.queryParam(PARAM_PREFIX + k, MapUtils.getString(params, k, ""));
			}
		});
		URI urlResult = builder.build().toUri();
		HttpHeaders headers = new HttpHeaders();
		headers.setContentType(MediaType.APPLICATION_JSON);
        HttpEntity<String> requestEntity;
        if(isV6&&isPreview) {
            headers=setHeadersForWps4(urlResult,headers);
            requestEntity= new HttpEntity<>(null, headers);
            GetOnlinePreviewResponse previewResponse = restTemplate.exchange(urlResult, HttpMethod.GET, requestEntity, GetOnlinePreviewResponse.class).getBody();
            if(previewResponse.getCode().equals("200")){
                if(previewResponse.getData().containsKey("link")) {
                    return previewResponse.getData().get("link").toString().replace("wpsCachePreview","wpsPreview=1000000&simple");
                }
            }
        }
		requestEntity = new HttpEntity<>(null, headers);
		long t1 = System.currentTimeMillis();
		GetOnlineEditUrlResponse res;
		try {
			res = restTemplate.exchange(urlResult, HttpMethod.GET, requestEntity, GetOnlineEditUrlResponse.class).getBody();
		} catch (HttpClientErrorException e) {
			LOGGER.error("获取weboffice生成的URL出错:url="+urlResult.toString()+";"+e.getResponseBodyAsString(), e);
			throw new BusinessException(e.getResponseBodyAsString(),e);
		}
		LOGGER.info(MessageFormat.format("请求中台-2-：{0}，耗时{1}ms", this.webOfficeUrl+ typeEnum.getUrl(),System.currentTimeMillis()-t1));
		return res.getUrl();
	}


3、com.seeyon.apps.wpsassist.manager.WpsAssistOfficeApiImpl.java

添加如下代码：



4、新增java类com.seeyon.apps.weboffice.util.HMacUtil.java

package com.seeyon.apps.weboffice.util;

import javax.crypto.Mac;
import javax.crypto.spec.SecretKeySpec;
import java.security.MessageDigest;
import java.security.NoSuchAlgorithmException;

/**
 * @author ranjf
 * @description
 * @date 2023/9/26 15:50
 */
public class HMacUtil {
    public static String HMACSHA256(String data, String key) throws Exception {
        Mac sha256_HMAC = Mac.getInstance("HmacSHA256");
        SecretKeySpec secret_key = new SecretKeySpec(key.getBytes("UTF-8"),
                "HmacSHA256");
        sha256_HMAC.init(secret_key);
        byte[] array = sha256_HMAC.doFinal(data.getBytes("UTF-8"));
        StringBuilder sb = new StringBuilder();
        for (byte item : array) {
            sb.append(Integer.toHexString((item & 0xFF) | 0x100).substring(1,
                    3));
        }
        return sb.toString();
    }
    /**
     * 利用java原生的摘要实现SHA256加密
     * @param str 加密后的报文
     * @return
     */
    public static String getSHA256StrJava(byte[] str){
        MessageDigest messageDigest;
        String encodeStr = "";
        try {
            messageDigest = MessageDigest.getInstance("SHA-256");
            messageDigest.update(str);
            encodeStr = byte2Hex(messageDigest.digest());
        } catch (NoSuchAlgorithmException e) {
            e.printStackTrace();
        }
        return encodeStr;
    }
    /**
     * 将byte转为16进制
     * @param bytes
     * @return
     */
    private static String byte2Hex(byte[] bytes){
        StringBuffer stringBuffer = new StringBuffer();
        String temp = null;
        for (int i=0;i<bytes.length;i++){
            temp = Integer.toHexString(bytes[i] & 0xFF);
            if (temp.length()==1){
                //1得到一位的进行补0操作
                stringBuffer.append("0");
            }
            stringBuffer.append(temp);
        }
        return stringBuffer.toString();
    }
}


5、新增Java类：com.seeyon.apps.officePlugins.vo.middleground.GetOnlinePreviewResponse.java

package com.seeyon.apps.officePlugins.vo.middleground;

import com.fasterxml.jackson.annotation.JsonInclude;
import com.fasterxml.jackson.annotation.JsonProperty;

import java.util.Map;

/**
 * @author ranjf
 * @description
 * @date 2023/9/27 15:56
 */
@JsonInclude(JsonInclude.Include.NON_NULL)
public class GetOnlinePreviewResponse {
    @JsonProperty("data")
    private Map<String,Object> data;
    @JsonProperty("code")
    private String code;
    @JsonProperty("msg")
    private String msg;

    public Map<String, Object> getData() {
        return data;
    }

    public void setData(Map<String, Object> data) {
        this.data = data;
    }

    public String getCode() {
        return code;
    }

    public void setCode(String code) {
        this.code = code;
    }

    public String getMsg() {
        return msg;
    }

    public void setMsg(String msg) {
        this.msg = msg;
    }
}


6、修改java类：com.seeyon.apps.weboffice.manager.WpsWebOfficePreviewAdapter.java

1)、修改filter方法

修改前：



修改后：





最终代码如下：

	public boolean filter(HttpServletRequest request, HttpServletResponse response) throws Exception {
		// url中 包含文件名和其父级路径，如：-23634523412345123/-23634523412345123.html；-23634523412345123/file001.jpg
		String viewURL;
		String webOfficePreviewUrl= SystemEnvironment.getContextPath() +"/common/office/html/webOfficePreview.html";
		try {
			// 检查浏览器对于webOffice的兼容性
			checkBrowserCompatible(request);
			Object[] o = extractFileId(request.getRequestURI());
			String suffix = request.getParameter("fileSuffix");
			if(StringUtils.isNoneEmpty(suffix)){
				suffix=suffix.replace(".","");
			}
			long fileId = (Long) o[0];
            String fileName = request.getParameter("fileName");
            if(Strings.isBlank(fileName)){
                fileName=request.getParameter("dcs_titleName");
            }
            if(suffix==null){
                if(fileName!=null&&fileName.lastIndexOf(".")>-1){
                    suffix=fileName.substring(fileName.lastIndexOf(".")+1);
                }
            }
			viewURL = buildWpsPreviewUrl(request, String.valueOf(fileId),suffix);
			viewURL += "&_w_third_watermark=" + URLEncoder.encode(StringUtils.trimToEmpty(getWatermarkText(request)), "utf-8").replaceAll("\\+","%20");

			if (StringUtils.isNoneEmpty(fileName)){
				viewURL += "&_w_third_filename=" + URLEncoder.encode(fileName,"UTF-8");
			}

			if (StringUtils.isNoneEmpty(suffix)){
				viewURL += "&_w_third_suffix=" +suffix;
			}
			String fileCreateDate = request.getParameter("fileCreateDate");
			if (StringUtils.isNoneEmpty(fileCreateDate)){
				viewURL += "&_w_third_fileCreateDate=" + fileCreateDate;
			}

			//如果文件类型为空，并且不在支持的类型范围 走老的预览逻辑
			if(suffix!=null&& OfficeFileUtil.getFileTypeCode(suffix)!=null) {
				String userAgentForm=AppContext.getCurrentUser().getUserAgentFrom();
				String ctxPath=SystemEnvironment.getContextPath();
				webOfficePreviewUrl += "?ctxPath="+ctxPath+"&userAgentForm="+userAgentForm+"&fileId="+fileId+"&fileSuffix="+suffix+"&fileName="+URLEncoder.encode(fileName,StandardCharsets.UTF_8.toString())+"&viewUrl=" + URLEncoder.encode(viewURL, StandardCharsets.UTF_8.toString());
			}else {
				webOfficePreviewUrl=viewURL;
			}
			
		}catch (BrowserCompatibleException exception){
			LOG.error("BrowserCompatibleException",exception);
			return writeErrorMessageToBrower(response,9);
		}catch (Exception exception){
			LOG.error("",exception);
			return writeErrorMessageToBrower(response,8);
		}
		redirect(response,webOfficePreviewUrl);
		return false;
	}


2)、修改buildWpsPreviewUrl方法，添加如红框中的代码



7、修改Java类com.seeyon.apps.wpsassist.manager.WpsAssistOfficeApiImpl.java

SUPPORT_SUFFIX集合中添加MIMETypeSuffix.ofdMIMEType.getSuffix()



8、修改java类：com.seeyon.ctp.rest.resources.WebOfficeV6CallbackResource.java

1)、添加静态常量：REP_TOKEN

private static final String REP_TOKEN = "x-wps-weboffice-token";


2)、修改getFileInfo方法，修改点如图：

修改前：



修改后：






## ctp-common

1、com.seeyon.ctp.common.content.mainbody.handler.impl.AbstractOfficeMainbodyHandler.java

修改getContentHtml()方法，如下图：



2、com.seeyon.ctp.common.content.mainbody.handler.impl.OFDMainbodyHandler.java

修改getTransView()方法，如下图：



3、com.seeyon.ctp.common.taglibs.support.EditorSupport.java

修改showOfficeHtmlContent()方法，如下图所示：



**4、com.seeyon.ctp.common.taglibs.support.ShowContentSuppert.java **

修改showOfficeHtmlContent()方法，如下图所示：



com.seeyon.ctp.common.web.filter.WebOfficeAuthenticator.java

修改authenticate()方法，获取token的时候先从header获取，如果没有就从url中获取，获取token的代码改为如下所示：

String tolen = Strings.isBlank(request.getHeader(REP_TOKEN)) ? (Strings.isBlank(request.getParameter("_w_tolen"))?request.getParameter("_w_third_tolen"):request.getParameter("_w_tolen")) : request.getHeader(REP_TOKEN);



## ctp-core

修改java类：com.seeyon.ctp.common.office.trans.util.OfficeTransHelper.java

修改buildCacheUrl方法，修改点如图所示：



编撰人：ranjunfeng、het、ranjf


快速跳转



 * 金山中台预览增加SDK以实现打印旋转等功能
   * 改造背景
   * 适用版本
   * 改造方案
   * 适配版本
   * 可参考代码
   * 涉及的工程
   * 支持功能
   * 改动点
     * apps-api
     * apps-common
     * apps-office-plugins-front
     * apps-office-plugins
     * ctp-common
     * ctp-core



分享链接分享链接

## 149. 金山WPS客户端JSAPI加载项集成文档

> 原始路径：`/1842/1851/1852.html`  
> 相对路径：`1842/1851/1852.md`

## 金山WPS客户端JSAPI加载项集成文档


## 前言

使用WPS加载项无需安装额外控件，在线编辑是打开WPS的客户端，能保证内容1：1还原，并且还能打开微软的Office文件。


## 安装要求

推荐使用WPS2019专业版，版本号为v11.8.2.10255。Windows仅支持10255及其以上专业版。注意：最好使用10255版本，其他版本未过测试。你可以打开WPS，点击右上角设置图标，在关于WPS后面可以看到当前软件的版本号。



使用WPS加载项最重要一点是：保证本机已安装WPS专业版，并且对版本有严格要求，只有从金山供应商购买的WPS并且由供应商提供的WPS安装程序才能使用加载项。

所有个人从金山官网下载的WPS均不支持加载项。

详细要求配置可参考[关联文档](【流版签】【wps】WPS365在OA中集成使用方法 https://open.seeyoncloud.com/#/faq/faq/v1/share?url=Z2JySmU+Nzkz "关联文档")。


## 插件和配置

加载项支持的OA版本是8.0SP2及其以上版本，以系统管理员身份登录，点击设置进入"后台管理"：



进入后台管理后，选择点击"系统参数设置"：



进入系统参数设置后，找到"功能选项"，在"是否混合使用金格插件和WPS加载项"中选择"否"。如果这个选项是"是"，代表在相关的后续的操作中，会优先使用金格控件，但是如果金格控件不可用的话，就会使用WPS加载项，我们在这里选择"否"，来默认使用WPS加载项。（注意：该菜单受加密狗"国标插件"控制，没有插件则无法显示）



设置系统参数后，点击确定，退出并重新登录。


## 使用示例

正常登录系统，在"协同工作"，点击"新建事项"：



在"正文类型"中选择"Word正文"，并确定继续：






## 首次启动WPS服务场景

首次访问，或者重启电脑，均需要启动服务（用于唤醒wps进程）：



点击后，可能浏览器会弹出申请打开链接的弹窗（这是浏览器访问金山接口的安全机制控制），此时可勾选复选框后，单击红框中的按钮即可：



此时可能会弹出如下窗口，这时直接点击启动服务即可(根据电脑性能等影响，可能wps接口无法立即给出响应导致)，重新再启动，如果多次无法启动，则需要判断当前wps版本是否支持加载项：





然后点击重新加载，刷新页面：



然后重新选择在"正文类型"中选择"Word正文"，并确定继续，此时可以成功打开WPS服务。




## 已经启动WPS服务场景

此时点击"Word正文"，可以直接弹出WPS服务：





进入WPS文字后，点击右上角退出后，会回到浏览器界面，此时点击窗口中显示的打开正文，仍然可以重新进入：





最后就可以使用WPS加载项编辑内容了：




## 开启调试模式

开发或者分析问题时，可能需要开启调试模式。


## 调试模式：配置参数

【Windows环境】

进入安装目录，找到oem.ini文件，可能在WPS Office > 11.8.2.10255 > office6 > cfgs 目录下面：



然后【support】增加配置JsApiShowWebDebugger=true：

【信创环境】

卸载 :sudo dpkg -r xxx

安装：sudo dpkg -i xxx

1、授权：

sudo chmod -R 777 /opt/apps/cn.wps.wps-office-pro/files/

2、修改oem.ini：

uos环境：龙芯

cd /opt/apps/cn.wps.wps-office-pro/files/kingsoft/wps-office/office6/cfgs

linux：银河麒麟

cd /opt/kingsoft/wps-office/office6/cfgs

开始修改：

vim oem.ini

JsApiShowWebDebugger=true

3、重启：

cd /opt/apps/cn.wps.wps-office-pro/files/bin

国产机修改后重启：终端执行 quickstartoffice restart

备注：金山文档 https://www.kdocs.cn/l/cCVZwo3LW

查找publish.xml文件

windows: 我的电脑地址栏中输入：%appdata%\kingsoft\wps\jsaddons

linux: 我的电脑地址栏中输入：~/.local/share/Kingsoft/wps/jsaddons


## 调试模式：跟踪调试

WPS打开文档后，鼠标点到页签，按alt+F12：



按了之后会弹出类似浏览器控制台（该控制台主要可调试WPS内部触发的加载项逻辑，例如OA触发打开文件）



"任务窗格"的点击事件需要跟踪，把鼠标放在任务窗格，点ALT+F12



（该控制台主要可调试"任务窗格"点击后的逻辑，例如点击左侧的"保存"按钮）




## 代码实现

OA触发wps客户端执行业务代码的逻辑在wps.js中，通过调用_WpsInvoke方法来调用wps_sdk.js(金山提供的)来和wps客户端通讯。



wps加载项，有一个版本支持多进程方式，目前只给了中石油客开使用，没有提交标准版本。代码工程：http://gitlab.seeyon.com/ctp/apps-common/-/tree/require-wps-cnpc-develop

wps客户端的代码在apps-common工程，代码分别为表格和和文字的，代码逻辑是一模一样，只是表格的语法不一样，因此只要看了文字的功能，表格也就明白：




## 代码实现：打开文档

打开在线文档，oa浏览器触发wps客户端，在wps的func_oastarter.js文件的dispatcher()方法，这个方法是web页面调用WPS的方法入口：



而在这里面，定义了如何打开在线文档的方法，涉及到了位于wps.js文件里面的函数OnlineEditDoc()：



OA浏览器触发wps的最后代码位于wps.js，打开文档方法 OnlineEditDoc()：



该函数的主要功能实际上是修改参数以及调用_WpsInvoke()函数，参数的修改对象是一个全局WPS上下文类型，该对象指定了很多属性来表示WPS文件的各种状态：



OnlineEditDoc()修改了3个属性（业务中会根据他们来进行些控制，这个不是最主要的，分析时可全局搜索），分别是：

\"renderWpsFlag\" ：wps 渲染标记

\"wpsCloseFlag\"：wps打开文档标记

\"changeFlag\"：是否调用模板标记


OnlineEditDoc()根据业务情况和参数传值来修改这些属性的的值：



只要需要打开WPS，必然需要经过_WpsInvoke方法，这是调用wps客户端的最后一个业务方法：



改方法会调用wps_sdk.js(金山提供)的方法和wps客户端通讯，这个文件是金山给我们提供的，我们不做任何修改，如果需要修改，则和master反馈。


## 代码实现：消息通知

1、消息监听

消息通知有消息监听的形式，比如WPS文字监听函数，通过传入参数的信息，来设定文档的属性，实现一个信息的传递功能。例如WPS客户端对文档保存、修改、关闭等操作，需要告诉oa，则通过改消息机制来实现：





表格信息监听的方式如出一辙，也是通过传递的参数信息来判断和修改对象的属性值：



在后面，还对这两个监听方法实现了一个封装，并且为了实现加载上的一个同步，还设置了一个200ms的延迟时间（很多业务组加载js文件是异步的，会存在wps_sdk.js没有引入就开始初始代码而导致undefined错误）：



2、心跳机制

Wps客户端访问oa时，是wps的内置浏览器触发请求，因此存在另一个seesion，这个新的seesion在OA是没有登录的，会被拦截。因此需要一套安全机制。

wps和oa服务器通讯，目前我们使用的是类似一个心跳的机制，下边是它时序图：



当需要使用加载项时，OA页面会触发生成

3、保存文档

进入WPS，点击保存，触发点击事件：



跟踪代码，此时会调用方法OnAction()，最终相应的执行OnBtnSaveToServer()方法：



继续跟踪OnBtnSaveToServer()方法，进入func_tabcontrol.js文件的OnBtnSaveToServer()方法：



进入核心代码行uploadToServer()方法的调用，然后在这里奇怪的是，我进入该行代码的执行，但是显现的并不是我想看到的那个函数（可能是一些浏览器显示乱跳的问题，我们可以使用debugger来强制使用断点进入）：



进入后调用的是这一行，也就是调用btnShowDoc()函数的最末行，而不是uploadToServer()的第一行：



随后执行函数onAutoUploadSuccess()，执行完该函数过后，：



4、保存文档回调

保存文档回调的关键代码是对象WpsConstent的saveFileCallBack()方法：




## 代码实现：执行专业签章

文件wps.js

①判断是否有专业签章函数

fileId：文件Id

ClientType：客户端类型(wps或et)，若不传将被设置为wps

返回值为boolean



②函数_WpsInvoke

funcs：调用的函数名，JSON格式

OAAssistType：客户端类型，若不传将被设置为wps

调用wpsFunc去做判断，其中info的值为{"HasSpecialSignature":fileId...}

判断结果将传入回调函数的参数result



文件func_oastarter.js

①判断是否有金格专业签章

判断doc中sheet的每一项的shape的每一项，有三种情况均可确定有金格专业签章，满足任意一项均可return true。




## 代码实现：执行图片签章

①文件wps.js

传入funcs的函数名为"HasPicSignature"

与专业签章逻辑一致



②文件func_oastarter.js

判断doc中sheet的每一项的shape的每一项，提取出关键字用于判断是否为金格图片签章。


## 代码实现：文档是否已经打开

含义：OA主动发起请求到wps客户端（wps加载项）中请求文档是否处于打开状态。

1、OA主动发起请求

apps-common\src\main\webapp\common\office\js\wps.js



2、wps客户端接收

apps-common\src\main\webapp\common\wpsOfficeAssist\WpsOAAssist\js\common\func_oastarter.js



3、根据本地是否存在对应的文件id判断是否文档已经打开




## 代码实现：套红

含义：OA主动发起请求到wps客户端（wps加载项）中进行在线套红处理。

1、OA主动发起

apps-common\src\main\webapp\common\office\js\wps.js



2、wps客户端接收

apps-common\src\main\webapp\common\wpsOfficeAssist\WpsOAAssist\js\common\func_oastarter.js



3、wps客户端处理

apps-common\src\main\webapp\common\wpsOfficeAssist\WpsOAAssist\js\common\func_docProcess.js

先判断文档是否存在，后执行判断权限是否允许，执行套红操作。




## 代码实现：获取公文域或书签数量

含义：OA主动发起请求到wps客户端（wps加载项）中进行获取公文域或书签数量，参数为文件id。

1、OA主动发起

apps-common\src\main\webapp\common\office\js\wps.js



2、wps客户端接收处理

apps-common\src\main\webapp\common\wpsOfficeAssist\WpsOAAssist\js\common\func_oastarter.js



3、根据文件id处理文件




## 代码实现：获取书签名列表

含义：OA主动发起请求到wps客户端（wps加载项）中进行获取书签名。

1、OA发起

apps-common\src\main\webapp\common\office\js\wps.js



2、wps客户端接收

apps-common\src\main\webapp\common\wpsOfficeAssist\WpsOAAssist\js\common\func_oastarter.js



3、逻辑处理

apps-common\src\main\webapp\common\wpsOfficeAssist\WpsOAAssist\js\common\func_docProcess.js




## 代码实现：删除书签

含义：OA主动发起请求到wps客户端（wps加载项）中进行删除书签操作。

1、OA发起

apps-common\src\main\webapp\common\office\js\wps.js



2、wps客户端处理

apps-common\src\main\webapp\common\wpsOfficeAssist\WpsOAAssist\js\common\func_docProcess.js




## 代码实现：更新参数

更新权限等操作会调用该函数

①文件wps.js

paramObj：参数对象

直接调用_WpsInvoke函数

无需设置ClientType



需要设置ClientType



②文件func_oastarter.js

调用addParamsToDoc函数并刷新权限





文件func_docProcess.js

具体的合并两个params的操作




## 代码实现：激活文档

①文件wps.js



②文件func_docProcess.js




## 代码实现：强制wps保存

文件wps.js

调用_WpsInvoke




## 代码实现：国际化

①获取国际化信息

文件baseOffice.js



②从oa缓存中获取国际化信息

文件wps.js




## 代码实现：打印

含义：在打开的wps客户端的当前打开文档中调起打印页面设置框。进行文档的打印实现。

1、入口函数

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\taskpane.html



2、执行打印逻辑

a. 获取当前激活文档：wpsApp.ActiveDocument

b. 延时加载打印逻辑：wpsApp.CommandBars.ExecuteMso("FilePrint");

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\js\common.js




## 代码实现：WPS权限控制

含义：根据OA系统传递的数据进行任务窗格功能性的动态渲染与Ribbon按钮(wps上层默认功能按钮)是否可用，以及默认功能重写。

## 1、任务窗格

 1. 加载逻辑：通过从OA端获取参数，使用wps加载项提供的参数共享方式wps.PluginStorage.setItem()来初始化需要展示的任务窗格参数。wps.PluginStorage.getItem()获取任务窗格参数，在taskpane.html中渲染任务窗格。

 2. OA参数获取与初始化参数。

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\js\common.js

初始化菜单的参数：

params:OA参数



根据OA参数更新菜单权限：

params:OA参数



 3. 动态显示任务窗格

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\js\common.js

调起加载taskpane.html

{width="5.726388888888889in" height="1.5303280839895013in"}

渲染任务窗格：

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\taskpane.html

{width="5.726388888888889in" height="3.4402088801399824in"}

## 2、Ribbon按钮

 1. 加载逻辑：在ribbon.xml中定义出需要操作的功能权限，在初始化函数OnWPSWorkTabLoad中将需要操作的权限初始化以及挂载WPS的文档事件，比如：监听文档打开，监听文档关闭......。

a. idMso：控件名称，必须使用控件规定的名https://open.wps.cn/docs/office

b. getEnabled:是否生效。

c. onAction:自定义执行逻辑。

 2. 处理Ribbon按钮的是否可用

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\js\common\func_tabcontrol.js

{width="5.726388888888889in" height="4.164646762904637in"}

 3. 自定义菜单按钮的点击执行事件

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\js\common\func_tabcontrol.js




## 代码实现：花脸

含义：简单说对历史编辑做一个展示，并提供选择权限进行一个历史编辑版本的信息展示。

1、执行逻辑

在任务窗格有花脸功能的情况下，点击对应花脸按钮，执行打开弹框逻辑，获取花脸数据，展示在弹框区域中，以进度项方式展示，点击对应任务项，获取对应任务项数据，切换并渲染新页面。打开只读文件。最后关闭弹框，关闭花脸模式。

2、弹框逻辑

a. 入口函数

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\taskpane.html

花脸此处使用了vue.js的展示和执行函数方式。





3、展示花脸弹框信息

wpsOfficeAssist\wpsOfficeAssist\WpsOAAssist\taskpane.html

执行函数：listHualian

发起ajax请求，获取花脸信息。



4、点击花脸对应任务项功能

a. 执行函数：open

b. 参数：item 每一个花脸任务项信息。



渲染新的界面并切换：




## 代码实现：清稿

含义：对文档的历史编辑痕迹进行一个清楚，然后保存全新的文档到服务器中。

1、入口函数

WpsOAAssist\js\common\func_tabcontrol.js



2、清稿后需要保存到服务器中，并刷新花脸




## 代码实现：转OFD、转PDF

①文件baseOffice.js



②文件handWrite_n.js


## 常见Bug和解决

每次重启电脑都会提示启动服务

因为重启电脑，wps进程就会退出。下次使用必定会启动服务来唤起wps，这个我们已经找过金山技术，他们无法做到自动启动，据说是系统安全有限制，无法实现重启电脑来自动启动wps。

无法启动服务或者wps无法唤起

问题排查【WPS 问题排查https://www.kdocs.cn/l/srSD8XlpL】：

注意：请务必确认，当前WPS版本是专业版，window是10255，信创是10290。（大于该版本的未全面测试）

1：文件地址栏输入%AppData%回车,进入如下地址，看看加载项的配置路径文件



如果有其他的xml，则删掉，只保留publish.xml。

2：打开publish.xml，只保留自己访问OA的ip地址的配置，有其他的，则全部删掉。

信创环境publish.xml文件地址：

> linux： cd ~/.local/share/Kingsoft/wps/jsaddons



保存不成功

保存有延迟，上传文件到服务器需要时间，不要在保存的时候，立即关闭wps。

访问m3端失败

请访问：http://localhost/seeyon/H5/wechat/html/allApps.html 首页

 * fildder总是弹出黄框阻塞

可能是启动了信创vpn或其他vpn

信创vpn

打开服务，将这三个服务关闭后禁用。



编撰人：het




快速跳转



 * 金山WPS客户端JSAPI加载项集成文档
   * 前言
   * 安装要求
   * 插件和配置
   * 使用示例
     * 首次启动WPS服务场景
     * 已经启动WPS服务场景
   * 开启调试模式
     * 调试模式：配置参数
     * 调试模式：跟踪调试
   * 代码实现
     * 代码实现：打开文档
     * 代码实现：消息通知
     * 代码实现：执行专业签章
     * 代码实现：执行图片签章
     * 代码实现：文档是否已经打开
     * 代码实现：套红
     * 代码实现：获取公文域或书签数量
     * 代码实现：获取书签名列表
     * 代码实现：删除书签
     * 代码实现：更新参数
     * 代码实现：激活文档
     * 代码实现：强制wps保存
     * 代码实现：国际化
     * 代码实现：打印
     * 代码实现：WPS权限控制
       * 1、任务窗格
       * 2、Ribbon按钮
     * 代码实现：花脸
     * 代码实现：清稿
     * 代码实现：转OFD、转PDF
   * 常见Bug和解决



分享链接分享链接

## 150. 金山文档中台内外网映射适配方案

> 原始路径：`/1842/1851/1966.html`  
> 相对路径：`1842/1851/1966.md`

## 金山文档中台内外网映射适配方案

2024年8月


## 需求

标准产品集成金山文档中台，要求客户端能连接金山中台服务，并且OA也要与金山中台互通，以上互通配置都通过SeeyonConfig应用配置器完成。

目前存在一个问题：如果使用金山在线编辑，目前只有一个SeeyonConfig参数用于配置金山中台服务器的地址。这样会导致一个问题：

如下图所示，如果地址配置的是金山域名http://wps.yonghu.com，则客户端能连接金山中台，但是内网OA服务器连不上金山中台（客户内网不给开金山域名访问策略）；反之，如果配置的是金山内网IP，则客户端无法连接金山。

> 金山在线预览不存在此问题，在线预览有两个参数



修改方案如下图所示：SeeyonConfig配置金山地址的参数变成2个，一个配置外网客户端连接金山中台的地址，一个配置OA直连金山中台内网的地址。




## 方案原理

本次修改的原理是根据用户请求头信息中带入user-agent判断访问的终端类型，然后根据终端类型取获取对应配置中的外网地址，将金山中台返回的内网预览/编辑地址替换为外网地址，本次功能为金山文档中台在线编辑外网映射，在线预览目前产品已支持。


## 涉及工程

本次修改涉及到的工程ctp-common、apps-office-plugins


## 改动点

1.修改ctp-common中的systemProperties.xml配置，在ctp.offictTrans.wps中加入如下配置:

<m3EditDomain mark="{VE}" desc="M3应用的域名,该域名用于将金山编辑URL和M3保持同域"/>
<wechatEditDomain mark="{VE}" desc="微协同应用的域名,该域名用于将金山编辑URL和微协同保持同域"/>
<pcEditDomain mark="{VE}" desc="PC协同应用的域名,该域名用于将金山编辑URL和PC协同保持同域"/>


**2.修改apps-office-plugins中的WebOfficeUtil类，添加如下代码（此处代码主要是根据用户访问的终端信息获取配置的外网地址）： **

	/**
     * 替换 url 中的主机和端口
     */
    public static String replaceAddress(String dest, String orig) throws BusinessException {
        try {
            if (Strings.isBlank(dest)||Strings.isBlank(orig)) {
                log.error("替换url host 失败.dest 或 orig为空");
                return orig;
            }
            URL destUrl = new URL(dest);
            URL origUrl = new URL(orig);
            URL newUrl = new URL(destUrl.getProtocol(), destUrl.getHost(), destUrl.getPort(), origUrl.getFile());
            log.info("替换weboffice地址,替换前{" + orig + "}\n替换后{" + newUrl + "}");
            return newUrl.toString();
        } catch (MalformedURLException e) {
            throw new BusinessException(e);
        }
    }
	/**
     * 获取外网地址
     */
    public static String publicAddress(HttpServletRequest request) {
        String agent = request.getHeader("User-Agent-Client");
        User currentUser = AppContext.getCurrentUser();
        //获取各端配置
        String wechatEditDomain = SystemProperties.getInstance().getProperty("officeTrans.wps.wechatEditDomain");
        String pcEditDomain = SystemProperties.getInstance().getProperty("officeTrans.wps.pcEditDomain");
        String m3EditDomain = SystemProperties.getInstance().getProperty("officeTrans.wps.m3EditDomain");
        return getPublicAddress(agent, currentUser, wechatEditDomain, pcEditDomain, m3EditDomain);
    }
    private static final List<String> M3_AGENT = Arrays.asList(
            Constants.login_useragent_from.mobile.name(),
            Constants.login_useragent_from.iphone.name(),
            Constants.login_useragent_from.ipad.name(),
            Constants.login_useragent_from.androidpad.name(),
            Constants.login_useragent_from.androidphone.name()
    );
    /**
     * 判断是否是M3访问金山中台预览
     * @param agent			各端agent
     * @param currentUser	当前登录用户
     * @return
     */
    protected static boolean isM3(String agent, User currentUser) {
        if(M3_AGENT.contains(agent)) {
            return true;
        }
        if(currentUser != null && currentUser.isFromM1()) {
            return true;
        }
        return false;
    }
    /**
     * 判断是否是微协同访问金山中台预览
     * @param agent			各端agent
     * @param currentUser	当前登录用户
     * @return
     */
    protected static boolean isWx(String agent, User currentUser) {
        if(Constants.login_useragent_from.wechat.name().equals(agent)) {
            return true;
        }
        if(currentUser != null && Constants.login_useragent_from.wechat.name().equals(currentUser.getUserAgentFrom())) {
            return true;
        }
        return false;
    }
	/**
     * 根据用户的agent信息获取配置的外网地址
     * @param agent			各端agent
     * @param currentUser	当前登录用户
     * @param wechatDomain	微协同地址
     * @param pcDomain	pc同地址
     * @param m3Domain	m3同地址
     * @return
     */
    protected static String getPublicAddress(String agent, User currentUser, String wechatDomain, String pcDomain, String m3Domain) {
        String publicAddress=null;
        if(isM3(agent, currentUser) && Strings.isNotEmpty(m3Domain)) {
            publicAddress=m3Domain;
        } else if(isWx(agent, currentUser) && Strings.isNotEmpty(wechatDomain)) {
            publicAddress=wechatDomain;
        } else if(Strings.isNotEmpty(pcDomain)) {
            publicAddress=pcDomain;
        }

        return publicAddress;
    }


3.修改apps-office-plugins中的WebOfficeResource类的createWebOffice方法，返回结果之前替换一下内网地址,代码如下：

UrlInfoVO result = WebOfficeHelper.fillCreateBackVO(woVo);
final String publicAddress = WebOfficeUtil.publicAddress(req);
if (publicAddress != null) {
	result.setWebOfficeDomin(WebOfficeUtil.replaceAddress(publicAddress, result.getWebOfficeDomin()));
	result.setWpsUrl(WebOfficeUtil.replaceAddress(publicAddress, result.getWpsUrl()));
}
return this.success(result);


修改前代码：

修改后代码：


## 修改配置

方法1：修改seeyonConfig配置，将需要开放外网访问端的中台外网地址配置上，如下图所示：



方法2：修改base/config/systemCtp.properties文件，添加如下配置：

在线预览配置：

officeTrans.wps.m3Domain=m3在线预览（金山文档中台）外网地址
officeTrans.wps.wechatDomain=微协同在线预览（金山文档中台）外网地址
officeTrans.wps.pcDomain=pc在线预览（金山文档中台）外网地址


在线编辑配置：

officeTrans.wps.m3EditDomain=m3在线编辑（金山文档中台）外网地址
officeTrans.wps.wechatEditDomain=微协同在线编辑（金山文档中台）外网地址
officeTrans.wps.pcEditDomain=pc在线编辑（金山文档中台）外网地址


备注：此处配置根据要开放的端进行选择配置，地址为金山文档中台外网访问地址，只需要到填写到端口。如：https://10.3.4.85:80

编撰人：ranjf、het


快速跳转



 * 金山文档中台内外网映射适配方案
   * 需求
   * 方案原理
   * 涉及工程
   * 改动点
   * 修改配置



分享链接分享链接

## 151. 文档通在线编辑技术说明文档

> 原始路径：`/1842/1851/1996.html`  
> 相对路径：`1842/1851/1996.md`

## 文档通在线编辑技术说明文档


## 1.背景及综述

中标慧康文档通服务是一款去控件化、支持多人在线编辑的流式文档编辑器（支持标准格式的docx、xlsx、pptx） 本文档致力与阐述文档通服务接入OA的部分前端逻辑和全部后端逻辑，以及配置相关的常见问题。


## 2.文档通接入（前端）

注：本文档默认文档通服务以安装并按要求配置并启动。


## 2.1接入api.js

前端引入文档通api.js，并初始化nsoOffice前端组件, 在本期实现，其由wdtAdapter.js 静态加载实现


## 2.2 构建打开参数，维护nsoOffice对象

## 2.2.1 获取当前文档downloadUrl和callbackUrl



## 2.2.2 获取dockey



## 2.2.3 拼接params



## 2.3 获取token

请求地址：/rest/wdt_online/v1/get_jwt 
请求方式：POST
请求参数：@param params {payload : String}


请求接口获取文档通参数token, 并打开文档


## 3.文档通接入（后端）


## 3.1 token 生产

通过统一的加解密方式，生产token, 用于于文档通鉴权和后续的权限校验。token需要一个双方确定的密钥，在流版签配置中心后台配置。并在文档通服务配置。

同时需要确保与文档通服务配置保持一致。后台代码位置

com.seeyon.ctp.common.office.config.util.WdtJwtUtil





## 3.2 后台回调

文档通用于在文档变化、保存后会通过 前面的callbackUrl设置主动请求OA服务器以获取信息或者落地文档通服务器上的文件。


## 3.3 保存回调和dockey机制

由于文档通使用dockey作为文档的唯一标识，但同时这个dockey在触发了一个文档所有用户离开编辑界面一段时间后，会触发一个离线保存回调请求到OA服务器，此时需要OA服务器落地文件，并为当前文档生成一个新的dockey。旧的dockey将丢弃从用户打开该文档到触发离线保存期间的所有内容。 而对于OA而言，文档的唯一标识为ctp_file的主键fileId。为了配合文档通离线保存的机制，故本次对接中，dockey由fileId + "_" + update_date 拼接而成。

 1. 文档通在线文档在编辑过程中触发Ctrl+S 时，会主动触发保存回调到OA服务器，这个时候OA服务器应该从回调的请求中获取文档下载流下载并落地文件。
 2. OA可以通过nsoOffice对象通过saveFile2前端js方法强制文档通服务器触发保存回调请求。
 3. 当所有用户退出文档并一段时间后没有任何用户再打开该文档时，文档通将发起离线保存回调，并在回调请求返回后，更新该文档版本（如下图）



版本更新后，或者在版本更新期间重新对某fileId文件进行打开时，应该需要通过文档通提供的command请求的keystatus子请求去获取当前文档的保存情况，避免dockey更新不及时的问题。




## 4.文档通配置及检查清单


## 4.1 检查系统管理级菜单

在系统管理员后台管理界面-系统设置-流版签系统设置-在线编辑-文档通在线编辑中的三个配置（如图示） 检查三个配置：

 1. 文档通在线编辑服务器地址：文档通服务器的ip+port。保证配置正确无误，保证端口已放开。
 2. 文档通在线编辑密钥：保证与文档通部署时文档通服务配置的密钥完全一致。
 3. 文档通在线编辑回调地址：既OA的真实地址，保证端口放开。


## 4.2 检查网络连通性

检查完上述配置完全正确后，需要验证网络的连通。

 1. 保证文档通服务器能够ping通OA服务器，且端口放开
 2. 保证OA服务器能够ping通文档通服务器，且端口放开
 3. 保证用户OA客户端所在的网段，能够ping通OA/文档通服务器，且端口放开。

编撰人：liangyd、het


快速跳转



 * 文档通在线编辑技术说明文档
   * 1.背景及综述
   * 2.文档通接入（前端）
     * 2.1接入api.js
     * 2.2 构建打开参数，维护nsoOffice对象
       * 2.2.1 获取当前文档downloadUrl和callbackUrl
       * 2.2.2 获取dockey
       * 2.2.3 拼接params
       * 2.3 获取token
   * 3.文档通接入（后端）
     * 3.1 token 生产
     * 3.2 后台回调
     * 3.3 保存回调和dockey机制
   * 4.文档通配置及检查清单
     * 4.1 检查系统管理级菜单
     * 4.2 检查网络连通性



分享链接分享链接

## 152. 数科预览及水印技术说明文档

> 原始路径：`/1842/1851/1997.html`  
> 相对路径：`1842/1851/1997.md`

## 数科预览及水印技术说明文档


## 1. 业务逻辑说明


## 1.1 数科在线预览

数科在线预览时序图

主要用于各个模板对正文、附件的在线预览，效果如图




## 1.2 水印

水印为数科轻阅读服务的功能，OA集成

开启条件：

> 1.系统管理员账号->系统设置->流版签设置->在线预览->在线预览态（正文和附件）开关开启



> 2.系统管理员账号->安全管理->数据保护->水印设置->水印显示范围->office在线查看> 勾选



> 3.预览文件水印状态（非编辑文件）

效果如图：




## 2. 接口说明


## 2.1 在线预览

## 2.1.1 前端代码

定义了一个闭包对象，用来和数科对接。

PC端

apps-office-plugins-front 工程：

\\desktop-front\\src\\office\\js\\skLightRead\\skAdapter.js

移动端：

apps-office-plugins-front 工程
：\\mplus-front\\src\\webOffice\\skLightRead\\skAdapter.js


## 2.1.2 后端代码（PC/移动共用）

apps-office-plugins 工程

SuwellResource.java

## 2.1.2.1 获取数科预览URL

数科预览接口，前端请求该接口，返回预览URL链接，挂载到iframe中进行预览



## 2.1.2.2 获取数科轻阅读需要的参数配置接口（用于数科回调）

前端挂载请求数科预览URL后，数科会回调该接口，获取预览文件详细信息（下载地址、上传地址、权限、水印）



## 2.1.2.3 数科轻阅读向oa保存文件接口（用于数科回调）

在数科预览界面签批或盖章后，数科服务会调用该接口将新的文件保存到OA



## 2.1.3 使用方法

## 2.1.3.1 页面引用officeSDK

// 在需要使用的html页面引入officeSDK.js

<script type="text/javascript"> src="/seeyon/common/office/js/officeSDK.js">
</script>


## 2.1.3.2 初始化officeSDK

初始化officeSDK会加载skAdapter.js，这里js是通过后台的配置返回的，比如开启了预览态，fileType 为流式或者版式文件都会返回skAdapter.js；未开启预览态，流式文件会返回当前配置的编辑器js,版式文件则返回skAdapter.js

## 2.1.3.3 打开文件

打开文件目前有两种方式：

1、嵌入式打开

嵌入式打开需要在init的时候给domId设置挂载点的元素id，流版签插件将会作为子元素挂载在页面上

2、弹窗式打开

弹窗式打开需要在openfile的时候设置isDialog为true，流版签插件将会挂载在自己的弹窗中显示出来。如果需要弹出隐藏的方式需要设置isHide为true（嵌入式不支持隐藏式打开，需要业务自己控制挂载点的显示/隐藏）


## 2.2 水印

## 2.2.1 前端代码

水印为数科轻阅读功能，无前端代码

## 2.2.2 后端代码

水印为数科轻阅读功能，无后端代码

SuwellResource.java

## 2.2.3 使用方法

> 1.在提供给数科回调的接口 /rest/skResource/sk/file/info 里，会返回相关水印信息。获取水印的方法如下，返回为null则不显示水印



> 2.可以通过SkLightReadWatermark对象，调整水印样式



编撰人：qingsg、het、liangyd


快速跳转



 * 数科预览及水印技术说明文档
   * 1. 业务逻辑说明
     * 1.1 数科在线预览
     * 1.2 水印
   * 2. 接口说明
     * 2.1 在线预览
       * 2.1.1 前端代码
       * 2.1.2 后端代码（PC/移动共用）
         * 2.1.2.1 获取数科预览URL
         * 2.1.2.2 获取数科轻阅读需要的参数配置接口（用于数科回调）
         * 2.1.2.3 数科轻阅读向oa保存文件接口（用于数科回调）
       * 2.1.3 使用方法
         * 2.1.3.1 页面引用officeSDK
         * 2.1.3.2 初始化officeSDK
         * 2.1.3.3 打开文件
     * 2.2 水印
       * 2.2.1 前端代码
       * 2.2.2 后端代码
       * 2.2.3 使用方法



分享链接分享链接

## 153. 数科套红技术说明文档

> 原始路径：`/1842/1851/1998.html`  
> 相对路径：`1842/1851/1998.md`

## 数科套红技术说明文档


## 1.业务逻辑说明


## 1.1 快速发文正文套红

快速发文中正文套红代码逻辑如图所示：




## 1.2 待办正文套红

待办中正文套红逻辑如下图所示：




## 1.3 文单套红

文单套红代码逻辑如图所示：




## 2. 接口说明


## 2.1 使用方式

调用officeSDK.taohong(params,callback)方法进行套红，taohong方法是异步方法，如果需要确保套红完成后再做后续的逻辑，可采用一下两种方式： 方法1：

let result = await officeSDK.taohong(params);
if(result){
    // 后续处理逻辑
}


方法2：

officeSDK.taohong(params,function(err,result){
    if(!err){
        // err如果未false，表示套红成功，此处可以做后续处理
    }
})
// params：调用套红接口参数
// callback：回调函数，接收套红结果


备注：套红后是否打开文档是在各自插件对应的Adapter文件中控制，文件打开方式由params参数控制，可以在套红之前调用officeSDK.setOptions({})将参数设置进去，打开文件的时候会根据参数控制打开的方式


## 2.2 参数说明

## 1. 套红参数说明

参数                    参数类型      是否必填   说明
allBookMark           List      是      书签对象集合
templateType          String    是      模板类型（edoc：正文，script：表单）
fileType              String    是      文件类型（doc或者docx）
fileId                String    是      文件ID
refreshBookMarkText   Boolean   是      刷新数书签值，如果需要刷新书签，次参数传递true
templateUrl           String    否      模板ID
extParam              Map       否      扩展参数

## 2. 书签对象说明

参数         参数类型           是否必填   说明
bookmark   String         是      书签名称
type       String         是      书签类型（DOCUMENT \ IMAGE \TEXT）
text       String         否      文本内容
imgInfo    ImgInfo        否      图片对象，当type为IMAGE时，必填
fileInfo   DocumentInfo   否      文件对象，当type为DOCUMENT时，必填

## 3. 图片对象说明

参数            参数类型     是否必填   说明
imgId         String   是      图片ID
inputType     String   是      图片类型（image、handwrite、barcode）
createDate    String   否      创建时间
isSignatrue   String   是      是否签章

## 4. 文件对象说明

参数               参数类型     是否必填   说明
fileId           String   是      文件ID
fileType         String   是      正文类型
originalFileId   String   否      原正文ID
size             Long     否      文件大小

## 5.扩展参数说明

参数                        参数类型     是否必填   说明
useOriginContentTaohong   String   否      是否原正文套红
originContentId           String   否      原正文ID


## 3.套红功能

套红功能支持的插件为数科预览、金山文档中台、WPS加载项，在调用套红功能之前需要将当前插件切换为编辑模式，代码示例如下：

示例1：

await officeSDK.init({
    mode: OfficeSDK.ENUM_MODE_TYPE.EDIT
});


示例2：

await officeSDK.switchProvider({
    mode: OfficeSDK.ENUM_MODE_TYPE.EDIT
});



## 3.1 数科套红

## 1. 前端代码

同时存在多个可以套红的插件时会优先使用数科的套红功能，因此数科的前端套红方法被封装为OfficeSDK的一个工具方法：

OfficeSDK.utils = {
     taohong: function (params, callback) {
        .....
     }
}



PC代码位置：

apps-office-plugins-front\\desktop-front\\src\\office\\js\\OfficeSDK.js

移动端代码位置：

apps-office-plugins-front\\mplus-front\\src\\office\\js\\OfficeSDK.js


## 2. 后端代码

数科套红采用的是后端接口套红，接口信息如下：

请求方式：POST
请求地址：/rest/suWellTaoHong/taohong


接口入口如下：

@Path("/taohong")
@POST
@ApiOperation(name="套红",scenes = "PC端-套红")
public Response taohong(@RequestBody CommonTaoHongParam commonTaoHongParam){
    String configValue= OfficeConfigUtil.getConfigValue(OfficeConfigEnum.ONLINE_PREVIEW_TYPE);
    if(commonTaoHongParam == null){
        return this.fail("taoHongParams is null");
    }
    if(!("SUWELL").equals(configValue)){
        return this.fail("当前插件不支持套红");
    }
    try {
        DocumentInfo documentInfo = suWellTaoHongManager.taohong(commonTaoHongParam);
        return this.success(documentInfo);
    } catch (BusinessException e) {
        return this.fail(e.getMessage());
    }
}




## 3.2 文档通

由于文档同本身没有实现套红功能，套红逻辑采用的是数科的套红功能，因文档通的套红方法是通过调用OfficeSDK.utils.taohong(params,callback)方法进行套红的。

## 1. 前端代码

PC代码位置：apps-office-plugins-front\desktop-front\src\office\js\docWebOffice\wdtAdapter.js

DocWebOfficePlugin.prototype.taohong = function (params, callback) {
    var _self = this;
    return new Promise((resolve, reject) => {
        OfficeSDK.utils.taohong(params, async function (error, result) {
            if (error) {
                callback && callback(error, result);
                reject(error)
            } else {
                _self.openFile({ fileId: result.fileId }, function (error, result) {
                    callback && callback(error, result);
                    resolve(result)
                });
            }
        })
    })
}



移动端代码位置：

apps-office-plugins-front\mplus-front\src\webOffice\docWebOffice\wdtAdapter.js

DocWebOfficePlugin.prototype.taohong = function (params, callback) {
    var _self = this;
    return new Promise((resolve, reject) => {
        OfficeSDK.utils.taohong(params, function (error, result) {
            callback && callback(error,result);
            if (error) {
                reject(false)
            } else {
                resolve(result)
            }
        })
    })
}



## 3.金山文档中台

金山文档中台套红功能首先是调用后台套红接口进行套红，后台套红不支持的功能再经过前端进行套红。

备注：意见区域待图片使用前端套红

## 1. 前端代码

PC代码位置：

apps-office-plugins-front\desktop-front\src\office\js\kingSoftAdapter\kingSoftAdapter.js

KingSoftOfficePlugin.prototype.taohong = async function (params, callback) {
	var _self = this;
    return new Promise((resolve, reject) => {
		OfficeSDK.utils.taohong(params, async function (error, result) {
			if (error) {
				_self.webOfficeInstance.taohong(params, async (e, res) => {
					if (e) {
						callback && callback(e, res);
					} else {
						if (res) {
							// 后端套红成功，需要再执行前端套红
							// 服务端套红生成的文件需要比对是否替换fileId
							if (_self.params.fileId !== res.data.fileId) {
								_self.params.fileId = res.data.fileId;
							}
							// 服务端套红后需要刷新office，但是之前已经存在一个wps实例，会导致展示的内容为原wps内容而不是套红后的内容（这是wps本身缺陷），所以需保证wps实例为最新
							await _self.webOfficeInstance.wps.destroy();
							// 套红后需要是可以编辑状态
							_self.params.canEdit = true;
							_self.params.editType = "2,1";

							await _self.openFile();
							// 前端补套，由于服务端无法执行部分书签的套红（如：书签下同时包含图片和文字两种类型的值）
							// 如果是快速发文，不走前端套红的逻辑
							await _self.webOfficeInstance.frontTaohong(params.imgArray, params.allBookMark);
							var data = {
							  fileId: _self.params.fileId
							}
							callback && callback(null, data);
							resolve(data)
						} else {
							callback && callback(false, false);
							reject(false)
						}
					}
				});
			} else {
			  //刷新的时候调用强制刷新刷新内容
			  await _uploadWebofficeEditRefresh(result.fileId);
			  _self.openFile({fileId: result.fileId},function(error,result){
				callback && callback(error,result);
				resolve(result)
			  });
			}
		})
    })
}



PC端金山文档中台套红相关业务代码位置如下：

> apps-office-plugins-front\desktop-front\src\office\js\kingSoftAdapter\kingSoftWebOffice.js通过KingSoftAdapter.js对业务代码进行调用。

移动端代码位置：

apps-office-plugins-front\mplus-front\src\webOffice\kingsoft\kingSoftAdapter.js

KingSoftOfficePlugin.prototype.taohong = async function (params, callback) {
	var _self = this;
	return new Promise((resolve, reject) => {
		OfficeSDK.utils.taohong(params, function (error, result) {
			if (error) {
				_self.webOfficeInstance.taohong(params, async (e, res) => {
					callback && callback(e, res);
					resolve(res)
				});
			}else{
				callback && callback(error, result);
				resolve(result)
			}
		})
	})
}



移动端金山文档中台套红相关业务代码位置如下：

> apps-office-plugins-front\mplus-front\src\webOffice\kingSoftWebOffice.js通过KingSoftAdapter.js对业务代码进行调用。

## 2. 后台代码

金山文档中台后端套红代码接口信息如下：

请求方式：POST
请求地址：/rest/webOffice/format/taohong



金山文档中台代码位置：

> apps-office-plugins\src\main\java\com\seeyon\ctp\rest\resources\WebOfficeFormatResource.java

代码入口如下：

@Path("/taohong")
@POST
@ApiOperation(name = "套红", scenes = "套红")
public Object taohong(@RequestBody TaoHongParams taoHongParams) throws BusinessException {
	// 获取模板
	if(taoHongParams == null){
		return this.fail("taoHongParams is null");
	}
	try {
		DocumentInfo info = formatControlManager.taohong(taoHongParams);
		return this.success(info);
	}catch (Exception e){
		log.error("后端套红出错",e);
		return this.fail(e.getMessage());
	}
}



## 4. WPS加载项

## 1. 前端代码

WPS加载项套红采用的是再客户端进行套红，目前暂时不支持移动端套红

PC代码位置：

> apps-office-plugins-front\desktop-front\src\office\js\wpsAdapter\wpsAdapter.js

WpsAdapter.prototype.taohong = async function (params={}, callback){
	if(!await this.checkOpenState()){
		return false;
	}
	let allBM = {};
	params.allBookMark && params.allBookMark.forEach((item) => {
		if(item.type=='TEXT'){
			allBM[item.bookmark] = item.text;
		}else if(item.type === "IMAGE"){
			let imgInfo=item.imgInfo;
			if(typeof(imgInfo) !="undefined") {
				let imgValObj = {inputType: imgInfo.inputType};
				imgValObj["value"] = imgInfo.value;
				imgValObj["isSignatrue"] = "false";
				var imgVal = [["imgsign", imgValObj]];
				allBM[item.bookmark] = imgVal;
			}
		}else{
			if(item.bookmark.indexOf("FJ_正文")==0 || (params.extParam.category == "32" && item.type == "DOCUMENT")){
				let fileInfo=item.fileInfo;
				allBM[item.bookmark]={"FJContent":fileInfo.fileId,"fileName":fileInfo.fileName,"fileType":fileInfo.fileType};
			}else {
				allBM[item.bookmark] = item;
			}
		}
	});
	var wpsTaohongParam ={
		fileId:this.options.fileId,
		// 执行操作
		handleType: params.templateType=="edoc" ? HANDLE_TYPE.BodyInsertRed : HANDLE_TYPE.FormInsertRed,
		// 模版id
		templateUrl:params.templateUrl,
		redFileElement: allBM,
		//插入正文对应的元素
		bkInsertFile:'Content', //Content
		zhInsertFile:'正文', //正文
		editType: "1,0",
		istaohong:true
	}
	if (!WpsUtil.isEmptyObject(params.extParam)) {
		if (params.extParam["useOriginContentTaohong"] == true) {
			// 原正文套红
			wpsTaohongParam["useOriginContentTaohong"] = params.extParam["useOriginContentTaohong"];
			wpsTaohongParam["originContentId"] = params.extParam["originContentId"];
		} else {
			// 文单套红，可修改，但不能保存到oa，直接不清稿操作
			if(wpsTaohongParam.handleType==HANDLE_TYPE.FormInsertRed){
				wpsTaohongParam["wpsFileSaveToServer"] = params.extParam.wpsFileSaveToServer || '';
				wpsTaohongParam["isFromDocTaoHong"] = true;//是否来于文单套红
			}
		}
	}
	//信息报送-期刊套红
	try {
		if(params.extParam.category=="32") {
			wpsTaohongParam.category = "32";
			if (params.extParam.dataList && (params.extParam.dataList.length > 0|| Object.keys(params.extParam.dataList).length > 0)) {
				wpsTaohongParam.dataList = params.extParam.dataList;
			}
		}
	} catch(e) {}
	await this.active();
	await InsertRedHead(wpsTaohongParam);
	callback && callback(null,true);
	return true;
}


编撰人：qingsg、het、liangyd


快速跳转



 * 数科套红技术说明文档
   * 1.业务逻辑说明
     * 1.1 快速发文正文套红
     * 1.2 待办正文套红
     * 1.3 文单套红
   * 2. 接口说明
     * 2.1 使用方式
     * 2.2 参数说明
       * 1. 套红参数说明
       * 2. 书签对象说明
       * 3. 图片对象说明
       * 4. 文件对象说明
       * 5.扩展参数说明
   * 3.套红功能
     * 3.1 数科套红
       * 1. 前端代码
       * 2. 后端代码
     * 3.2 文档通
       * 1. 前端代码
       * 3.金山文档中台
         * 1. 前端代码
         * 2. 后台代码
       * 4. WPS加载项
         * 1. 前端代码



分享链接分享链接

## 154. 流版签（OfficeSDK）技术说明文档

> 原始路径：`/1842/1851/1999.html`  
> 相对路径：`1842/1851/1999.md`

## 流版签（OfficeSDK）技术说明文档


## 背景&作用

过去版本每集成一套流版签产品，就是同一个类中增加if...else写法，长此以往造成了流版签新产品极高的集成扩展成本。

V9.0SP1采用统一接口的方式，提供了一套标准API接口，项目上如有新的流版签产品（如永中wo/dcs、福昕轻阅读、联想中台等）需要集成，则参考API做集成即可，无需将代码耦合到产品核心库中。


## 适用版本

协同V9.0SP1及未来版本


## 名词解释：

 * 套红：将文单中的值组合成文本、图片插入到word文档中对应的书签位置。

 * 清稿：保存当前正文的一个备份文件，然后删除文档中的手写批注、修改的痕迹，并保存正文。

 * 花脸：清稿操作中保存的备份文件。


## 1.使用方式


## 1.1页面引入

// 在需要使用的html页面引入officeSDK.js
<script type="text/javascript" src="/seeyon/common/office/js/officeSDK.js"></script>


注意：如果是PC端，当前页面必需引入了jQuery的ajax请求，并且能通过$.ajax调用；如果是移动端，当前页面必需引入cmp平台库。


## 1.2初始化

var params = {
    fileId: "", // 文件id
    fileType: "", //文档类型
    editType: "", // 编辑权限 （编辑：’2,1’，只读：’0,0’ 或者 ’4,0’）
}

var officeSDK = new OfficeSDK(params);
var initParams = {
    domId:’’, //插件加载的目标 DOM 元素的 ID。
    fileType:’’,//文档类型'docx', 'doc', 'wps', 'xlsx', 'xls', 'et',         'ods', 'csv', 'pptx', 'ppt', 'dps', 'odp'
    mode:’VIEW’,//打开模式VIEW、EDIT、SIGN 三选一
}


ES5写法：

officeSDK.init(initParams, function(error, result){
  // TODO：初始化完后的回调
});


ES6写法（async/await）:

try { let ret = await officeSDK.init(initParams);
  // TODO:初始化成功
}catch(e) {
  // TODO:初始化失败
}



## 1.3打开文件

打开文件目前有两种方式：

1、嵌入式打开 嵌入式打开需要在init的时候给domId设置挂载点的元素id，流版签插件将会作为子元素挂载在页面上

2、弹窗式打开 弹窗式打开需要在openfile的时候设置isDialog为true，流版签插件将会挂载在自己的弹窗中显示出来。如果需要弹出隐藏的方式需要设置isHide为true（嵌入式不支持隐藏式打开，需要业务自己控制挂载点的显示/隐藏）

var openParams = {
    isDialog: true,//是否是弹窗打开
    isHide:true,//是否隐藏式打开(主要针对弹窗的打开方式)
    showDialogTitle:’正文’,//弹窗标题
    noTransFlag:false,//是否需要显示预览（客户端模式的三方插件需要，如：WPS客户端）true：不显示，false：显示
}
officeSDK.openFile(openParams, function(error, result){
  // TODO：打开文件后的回调
});



## 2.接口说明


## 2.1初始化参数说明

{
    /** 文件ID */
    fileId: "",
    /** 文件保存到本地时候的文件名字*/
    fileName: "",
    /** 创建时间 */
    createDate: "",
    /** 应用的URL，例如http://127.0.0.1/seeyon */
    webRoot: OfficeSDK.utils.getWebRoot(),
    /** 文档类型 .doc,.docx,.xls,.xlsx*/
    fileType: "",//文档类型
    contentId: "",
    editType: "",
    /** 系统配置的最大的文件上传大小 */
    officeOcxUploadMax: "",
    /** 当前的国际化语言环境 */
    currentLanguage: OfficeSDK.utils.currentLanguage(),
    /** 原始文件的创建时间，例如调用模板的时候，模板文件的创建时间*/
    originalCreateDate: "",
    /** 原始文件的文件ID，例如调用模板的时候，模板文件的文件的ID*/
    originalFileId: "",
    /** 是不是需要clone原始文件*/
    needCloneFile: "",
    /**当前用户ID */
    userId: "",
    canCopy: 1, // 是否能够复制
    /** 当前用户的name */
    currentUserName: "",
    /*代理人ID*/
    affairMemberId: "",
    /*代理人姓名*/
    affairMemberName: "",
    /** 文件大小 */
    officeFileRealSize: "",
    /** 是否可以修改正文*/
    canEditContent: OfficeSDK.utils.getCanEditContent(),
    /** 当前页面是那个页面*/
    currentPage: "",
    originalNeedClone: "",
    extendParams: {},
    mode: 'view',//view edit sign
    // 编辑器内转OFD按钮能否使用
    canTransOfd: undefined,
    // 编辑器内转PDF按钮能否使用
    canTransPdf: undefined,
    // 编辑器内下载按钮能够使用
    canDownload: undefined,
    // 编辑器内能上传按钮能使用
    canUpload: undefined,
    // 编辑器内打印按钮能够使用
    canPrint: undefined,
    /** 当前打开，修改保存Office文档是否保留痕迹。某些情况下可能不需要保留痕迹，例如协同公文的新建*/
    // 编辑器内的盖章按钮能够使用
    canSign: undefined,
    // 编辑器内的验章按钮能够使用,验证按钮默认不受控制
    canCheckSign: undefined,
    // 编辑器内的清稿按钮能够使用
    canClearTrail: undefined,
    // 痕迹按钮是否显示
    isShowTrailBtn: undefined,
    // 编辑正文时是否开启修订模式(保留修改痕迹)
    canRevise: undefined,
    // 关闭弹窗的回调函数
    dialogCloseCallback: null,
    // 添加对应的流程Id
    processId: (typeof (processId) != "undefined" ? processId : (typeof parent.processId != "undefined" ? parent.processId : parent.parent.processId)),
};



## 2.2 init

函数描述：初始化 SDK 插件函数

函数原型：function init (params = {}, callBack)

函数入参：

@param {Object} params - 初始化插件所需的参数对象，可以为空对象。
{
  @param {string} params.domId - 插件加载的目标 DOM 元素的 ID。
  @param {string} params.fileType - 文档类型 //'docx','doc','wps','xlsx','xls','et','ods','csv','pptx','ppt','dps','odp'。
  @param {string} params.mode - 模式 DOM  VIEW、EDIT、SIGN 三选一
}
@param {Function} callBack - 初始化完成后的回调函数，可选参数。


返回结果：返回promise对象

例：

officeSDK.init(initParams, function(error, result){
    if (error) {
        // 初始化失败
    } else {
        // 初始化成功
    }
});



说明：callBack返回两个值，第一个值返回error，第二个值result返回调用后台接口函数执行的结果。

如果返回的error不为null，表明初始化adapter失败，当前插件配置不支持当前的文件类型打开。如果为null，则有合适的adapter。result的返回值{code：0，msg：'',data：{}}，如果code=0表示初始化adapter是成功，如果code=-1表示初始化不成功，表示后台接口异常。


## 2.3 setOptions

函数描述：更改adapter实例的公共参数

函数原型：function setOptions (params = {}, callBack)

函数入参：

@param {object} params
@param {Function} callBack


返回结果：返回promise对象

例：

officeSDK.setOptions(openParams, function(error, result){
    if (error) {
        //设置失败
    } else {
        //设置成功
    }
});



## 2.4 openFile

函数描述：打开文件

函数原型：function openFile (params = {}, callBack)

函数入参：

@param {object} params
{
  @param {Boolean} isDialog 是否是弹窗打开
  @param {Boolean} isHide 是否隐藏式打开
  @param {String} showDialogTitle 弹窗标题
  @param {true} noTransFlag 是否需要显示预览（客户端模式的三方插件需要，如：WPS客户端）true：不显示，false：显示
}
@param {Function} callBack 打开文件后返回的回调函数


返回结果：返回promise对象

例：

officeSDK.openFile(openParams, function(error, result){
    if (error) {
        //打开文件失败
    } else {
        //打开文件成功
    }
});



## 2.5 destory

函数描述：销毁当前adapter中持有的三方实例（包括关闭文档,关闭弹窗）

函数原型：function destory(params = {}, callBack)

函数入参：

@param {object} params (目前无需该参数，传null即可)
@param {Function} callBack 打开文件后返回的回调函数


返回结果：返回promise对象

例：

officeSDK.destory(params, function(error, result){
    if (error) {
        //销毁弹窗失败
    } else {
        //销毁弹窗成功
    }
});




## 2.6 closeFile

函数描述：关闭文件

函数原型：function closeFile (params = {}, callBack)

函数入参：

@param {object} params

@param {Function} callBack 回调函数


返回结果：返回promise对象

例：

officeSDK.closeFile(openParams, function(error, result){
    if (error) {
        //关闭文件失败
    } else {
        //关闭文件成功
    }
});




## 2.7 saveFile

函数描述：保存文件

函数原型：function saveFile (params = {}, callBack)

函数入参：

@param {object} params{
  @param {string}  fileId        文件ID
  @param {boolean} isAsync       是否异步保存
  @param {boolean} noTransFlag   true //wps保存后不触发转换
  @param {boolean} isNotCloseDoc true //wps保存后不关闭文档
}

@param {Function} callBack 回调函数


返回结果：返回promise对象

例：

officeSDK.saveFile(openParams, function(error, result){
    if (error) {
        //保存文件失败
    } else {
        //保存文件成功
    }
});



## 2.8 taohong

函数描述：文档套红

函数原型：function taohong (params = {}, callBack)

函数入参：

@param {object} params{
  @param {Array} allBoomark //套红书签对象
  {
    @param {string} bookmark // 书签名称
    @param {string} type     // 值类型 ('TEXT': 文本，'IMAGE':图片，'DOCUMENT': 文件)
    @param {string} text     // 书签值
    @param {object} fileInfo // 文件信息（文件类型的书签使用）
    @param {object} imgInfo  // 图片信息（图片类型的书签使用）
  }
  @param {string} templateUrl  // 模板id
  @param {string} templateType // 套红类型（'edoc':正文套红-对当前正文进行套红，'script': 文单套红-加载模版文件进行套红）
  @param {Object} extParam     // 扩展参数
}
@param {Function} callBack 回调函数


返回结果：返回promise对象


## 2.9 isAvailable

函数描述：编辑器是否可用

函数原型：function isAvailable (params = {})

函数入参：

@param {object} params


返回结果：返回布尔对象true/false


## 2.10 isModified

// 文档是否被修改 isModified: function () { },


## 2.11 print

// 打印 print: function () {},


## 2.12 delAnnotations

// 删除文档批注 delAnnotations: function () { },


## 2.13 saveHuaLian

// 保存花脸 saveHuaLian: function () {},


## 2.14 clearTrail

// 清稿 clearTrail: function () {},


## 2.15 bookmarkHighlight

// 高亮、定位跳转到书签 bookmarkHighlight: function () {},


## 2.16 transform

// 流式文件转板式文件（PDF、OFD） transform: function () { },


## 2.17 getBookmarkList

// 获取书签列表 getBookmarkList: function () {},


## 2.18 delBookmarks

// 删除书签 delBookmarks: function () {},


## 2.19 contentLength

// 获取文档大小 contentLength: function () {},


## 2.20 contentLengthAndCreateDate

// 获取文档大小和创建日期 contentLengthAndCreateDate: function () {},


## 2.21 signature

// 签章 signature: function () {},


## 2.22 hasProfessionalSign

// 是否有专业签章 hasProfessionalSign: function () {},


## 2.23 countSignatures

// 获取签章数量 countSignatures: function () {},


## 2.24 download

// 下载正文 download: function () {},


## 2.25 analyzing

// 解析图片 analyzing: function () {},


## 2.26 isEmpty

// 判断正文是否为空 isEmpty: function (params, callback) { },


## 2.27 supportMultiEditing

// 是否支持多人编辑 supportMultiEditing: function () {},


## 2.28 batchSwap

//批量替换书签内容 batchSwap: function () {},


## 2.29 swapWithoutHighlight

//替换书签内容不高亮 swapWithoutHighlight: function () {},


## 2.30 batchDeleteBM

//删除指定书签 batchDeleteBM: function () {},


## 2.31 decryptSeal

// 印章置灰 decryptSeal: function () {},


## 2.32 isClientApp

// 是否为客户端。例如wps加载项 isClientApp: function () {},


## 2.33 isAllowSignature

// 是否有签章功能 isAllowSignature: function () {},


## 2.34 isAllowTransform

// 是否有转版功能 isAllowTransform: function () {},


## 2.35 hide

// 隐藏弹窗 hide: function () {}


## 3.枚举

//mode 的枚举类型 VIEW、EDIT、SIGN
OfficeSDK.ENUM_MODE_TYPE = {
    VIEW: 'VIEW', // 预览
    EDIT: 'EDIT',  // 编辑
    SIGN: 'SIGN'  // 签章
}




## 4、三方插件使用(TODO)



编撰人：qijl、het、liangyd


快速跳转



 * 流版签（OfficeSDK）技术说明文档
   * 背景&作用
   * 适用版本
   * 名词解释：
   * 1.使用方式
     * 1.1页面引入
     * 1.2初始化
     * 1.3打开文件
   * 2.接口说明
     * 2.1初始化参数说明
     * 2.2 init
     * 2.3 setOptions
     * 2.4 openFile
     * 2.5 destory
     * 2.6 closeFile
     * 2.7 saveFile
     * 2.8 taohong
     * 2.9 isAvailable
     * 2.10 isModified
     * 2.11 print
     * 2.12 delAnnotations
     * 2.13 saveHuaLian
     * 2.14 clearTrail
     * 2.15 bookmarkHighlight
     * 2.16 transform
     * 2.17 getBookmarkList
     * 2.18 delBookmarks
     * 2.19 contentLength
     * 2.20 contentLengthAndCreateDate
     * 2.21 signature
     * 2.22 hasProfessionalSign
     * 2.23 countSignatures
     * 2.24 download
     * 2.25 analyzing
     * 2.26 isEmpty
     * 2.27 supportMultiEditing
     * 2.28 batchSwap
     * 2.29 swapWithoutHighlight
     * 2.30 batchDeleteBM
     * 2.31 decryptSeal
     * 2.32 isClientApp
     * 2.33 isAllowSignature
     * 2.34 isAllowTransform
     * 2.35 hide
   * 3.枚举
   * 4、三方插件使用(TODO)



分享链接分享链接

## 155. 数科H5签章技术说明文档

> 原始路径：`/1842/1851/2000.html`  
> 相对路径：`1842/1851/2000.md`

## 数科H5签章技术说明文档


## 1.说明

H5签章主要用于自由协同标准正文、CAP4表单、CAP3表单、和公文文单中进行专业签章的盖章，效果如图。

以CAP4表单为例：




## 2.相关文档

数科对接文档： 【金山文档 | WPS云文档】 数科HTML5签章 https://kdocs.cn/l/cdNw87UPf30f提供了和数科对接的前后端接口信息。


## 3.对接交互




## 4.关键代码

文单签章代码原来在apps-common ，V9.0SP1迁移到apps-office-plugins-front工程。

前端代码工程：apps-office-plugins-front
后端代码工程：apps-office-plugins





## 4.1 前端代码

apps-office-plugins-front\desktop-front\src\isignaturehtml\js\isignaturehtml.js


改造前是用的金格控件，相关操作都是在这个js中，目前对接数科也是在这个js中。业务引入的js和调用方法不变。

## 4.1.1 数科H5插件

定义了一个闭包对象，用来和数科对接。数科的插件代码， **PC端：**可以在isignaturehtml.js文件内部，搜索“数科插件”，标记start 到end区间代码为数科代码（数科有修改则替换这一部分）。

**移动端:**对应mplus-front工程中m3iSignature-debug.js文件，其中数科插件代码为shuke-html-signature.js文件

## 4.1.2 定义方法

定义了一个方法为SuWellH5Signature

var SuWellH5Signature={
...
}
内部属性：
sealWebPlugins 数科H5插件对象，数科的方法都是通过这个对象来操作
options 定义的文单签章相关参数


## 4.1.3 初始签章

（1）业务进入页面需要加载印章。原有的金格业务不变增加数科新的逻辑。可参考已有逻辑

//数科签章初始化
    var suwellOptions = {
        documentId: documentId,
        menuDeleteSign: isShowDeleteSign(),
        data: null,
        domId: signaturePosition
    };
SuWellH5Signature.init(suwellOptions);

1、init方法先发送oa请求获取当前数据的印章信息。然后调用数科H5插件渲染印章


（2）初始数科H5插件和菜单权限。

var config = {
            sealDomId: this.options.domId,
            autoX: 0,//相对于定位元素偏移量
            autoY: 0,
            isMove: true,// 盖上之后是否默认支持拖动
            allMove: true,// 全局是否支持拖动
            isDeleteSeal: this.options.menuDeleteSign,//是否有删除按钮
            InterfaceManagement: "childPage",
            requestUrl: this.webRoot + "/rest",//定义oa请求地址前缀
            watchDeleteSeal: function (item, list) {
                _this.count = list.length;
            }
        };
this.sealWebPlugins.setMenuList(config);


（3）渲染已经存在的印章

1、调用oa接口： "/rest/elsh5sign/h5sign/selectSignList",获取盖章记录
2、调用数科H5插件渲染：this.sealWebPlugins.renderingSeal //渲染印章




## 4.1.4 盖章弹框

SuWellH5Signature.sign可以打开数科盖章弹框

SuWellH5Signature.sign({documentId:h5DocumentId,data:newdata});

在sign中调用数科的
this.sealWebPlugins.sealDialog({...})打开数科弹框，参数见数科文档。



## 4.2 后端代码

参照文档开头数科提供的接口文档 SuwellH5SignResource.java

## 4.2.1 中转数科请求

数科H5插件和数科签章服务对接中转接口。该接口是为数科H5插件中发起请求数科签章服务的请求，参数和返回值oa不做关注，只做转发处理。

接口 POST: /rest/elsh5sign/h5sign




## 4.2.2 获取签章记录

oa保存数科盖章的信息后，下次打开需要加载出印章信息。

接口 GET: /rest/elsh5sign/h5sign




## 4.2.3 增加盖章记录

oa保存数科盖章的信息后。

接口 POST: /rest/elsh5sign/addSign




编撰人：liangyd、het




快速跳转



 * 数科H5签章技术说明文档
   * 1.说明
   * 2.相关文档
   * 3.对接交互
   * 4.关键代码
     * 4.1 前端代码
       * 4.1.1 数科H5插件
       * 4.1.2 定义方法
       * 4.1.3 初始签章
       * 4.1.4 盖章弹框
     * 4.2 后端代码
       * 4.2.1 中转数科请求
       * 4.2.2 获取签章记录
       * 4.2.3 增加盖章记录



分享链接分享链接

## 156. 数科版式正文盖章技术说明文档

> 原始路径：`/1842/1851/2001.html`  
> 相对路径：`1842/1851/2001.md`

## 数科版式正文盖章技术说明文档


## 1.说明

数科版式文件盖章支持自由协同（PDF/OFD）、公文版式正文（PDF/OFD）,在数科轻阅读中打开盖专业签章


## 2.服务器配置

数科正文盖章只支持版式盖章（PDF、OFD） 系统管理员配置签章服务。


## 3.关键代码

数科正文盖章，其实是在数科轻阅读上增加的盖章。初始编辑器的逻辑和预览一样。

代码：apps-office-plugins-front\desktop-front\src\office\js\skLightRead\skAdapter.js


业务在调用正文盖章时，new OfficeSDK参数中设置mode=sign，和打开编辑正文逻辑类似。


## 3.1 业务调用openFile。更具参数判断是否弹框




## 3.2 开启数科按钮监听




## 3.3 根据mode=sign和参数，获取在线签章的数科阅读器地址

后端接口为：/rest/skResource/${type}/url //type："VIEW" 预览；"SIGN" 盖章




openFile(): 打开数科在线编辑




如果mode=sign,这里从后端获取到的轻阅读地址为系统管理员配置的数科签章配置信息。


## 4.开始盖章


## 4.1 初始成功后可以查看到轻阅读顶上出现“签章”按钮




## 4.2 点击盖章就可以盖章了。这些都是数科内部功能






## 5.数科制章、授权


## 5.1相关文档

【腾讯文档】数科制章、授权
https://docs.qq.com/doc/DQlNFd0FNdVRoZmlW



## 5.2 环境部署

即：数科部署的签章相关服务。部署由数科或者运维老师操作（例如电子制章，电子签章，初始的组织架构等）。 部署完成后。登录了系统管理员xtadmin可看到如图类似界面。



在部署好环境后，这里简单说下创建用户和制作印章，授权印章。


## 5.3 创建用户

登录系统管理员：http://｛ip:port｝/managementCenter/login xtadmin 密码 ip\port、账号、密码按实际的来。例如


## 5.3.1 登录后添加用户





注意：

 1. 用户ID，必须和oa的登录账号一样。例如oa登录账号是seeyon，那么这里用户ID也设置为seeyon
 2. 印章密码默认的123456，在正式使用前，一定要改下密码，否则文单盖章会提示用户修改密码。初始也可以设置其他密码，那么用户就可以直接用。


## 5.4 制作印章

切换登录:http://｛ip:port｝/managementCenter/portal 账号为初始创建的。


## 5.4.1 选择印章申请：




## 5.4.2 录入信息






## 5.4.3 信息录入完成后，确定，提交申请




## 5.5 制章系统-审批




## 5.5.1 审批通过




## 5.6 制章系统-授权

审批通过后再印章系统可以看到印章


## 5.6.1 授权给新用户




## 5.6.2 选择新用户授权




## 5.7 系统集团管理员授权

授权，需要插件：电子签章集成。授权数量受加密狗授权数量控制


## 5.7.1 加密狗授权

需要选择厂商（当前只有一家：数科），和盖章人数


## 5.7.2 OA系统内授权



编撰人：liangyd


快速跳转



 * 数科版式正文盖章技术说明文档
   * 1.说明
   * 2.服务器配置
   * 3.关键代码
     * 3.1 业务调用openFile。更具参数判断是否弹框
     * 3.2 开启数科按钮监听
     * 3.3 根据mode=sign和参数，获取在线签章的数科阅读器地址
   * 4.开始盖章
     * 4.1 初始成功后可以查看到轻阅读顶上出现“签章”按钮
     * 4.2 点击盖章就可以盖章了。这些都是数科内部功能
   * 5.数科制章、授权
     * 5.1相关文档
     * 5.2 环境部署
   * 5.3 创建用户
     * 5.3.1 登录后添加用户
   * 5.4 制作印章
     * 5.4.1 选择印章申请：
     * 5.4.2 录入信息
     * 5.4.3 信息录入完成后，确定，提交申请
   * 5.5 制章系统-审批
     * 5.5.1 审批通过
   * 5.6 制章系统-授权
     * 5.6.1 授权给新用户
     * 5.6.2 选择新用户授权
   * 5.7 系统集团管理员授权
     * 5.7.1 加密狗授权
     * 5.7.2 OA系统内授权



分享链接分享链接

## 157. 金山中台适配OfficeSDK技术说明文档

> 原始路径：`/1842/1851/2045.html`  
> 相对路径：`1842/1851/2045.md`

## 金山中台适配OfficeSDK技术说明文档


## 背景&需求

本文讲解V9.0SP1+版本，金山中台集成适配致远OfficeSDK的实现思路，以方便有金山中台二次开发需求的技术做参考。


## 依赖版本

V9.0SP1及未来版本


## 技术说明


## 标准适配代码位置

PC端集成代码位于：\apps-office-plugins-front\desktop-front\src\office\js\kingSoftAdapter目录下

kingsoftPreviewAdapter.js和kingSoftPreview.js是金山在线预览的适配源码

kingSoftAdapter.js和kingSoftWebOffice.js是金山在线编辑的适配源码


移动端H5集成代码位于：\apps-office-plugins-front\mplus-front\src\webOffice\kingsoft目录下

kingSoftAdapter.js是金山在线编辑移动端的适配源码

kingsoftPreviewAdapter.js是金山在线预览移动端的适配源码



## 二次适配思路

针对标准适配代码，修改里面的实现，以完成定制的诉求。

apps-office-plugins-front工程下允许使用ES6语法，基于Ctp-Studio编译部署。如果没有Ctp-studio平台，纯粹个人开发，则需要做ES6转ES5的转换，否则无法使用。

如果是新页面需要引入OfficeSDK代码，则按[流版签（OfficeSDK）技术说明文档]，引入officeSDK.js即可。不用引入kingSoftAdapter.js这类适配器的代码，具体使用什么适配器是officeSDK.js中根据后台配置动态装载。

// 在需要使用的html页面引入officeSDK.js
<script type="text/javascript" src="/seeyon/common/office/js/officeSDK.js"></script>



## 测试注意事项

特别说明：9.0SP1及以后版本，金山与OA对接的相关配置，已不再从Seeyonconfig上配置。配置调整到了 》OA系统管理员后台》系统设置》流版签设置》进行相关配置。





基于文档做好了配置之后，officeSDK.js就知道当前系统使用的金山中台，于是就会主动去装载金山的Adapter。


## 产品调用金山中台API一览

描述      金山中台V5                                   金山中台V6、V7
强制刷新    /om/weboffice/v1/file/:id/edit/refresh   /api/edit/v2/files/:id/refresh
多书签套用   /cps/v2/office/wrapheader                /api/cps/sync/v1/wrapheader
文件下载    /cps/v1/download/file/{0}                /api/cps/v1/download/{0}
格式转换    /cps/v2/office/convert                   /api/cps/sync/v1/convert
文档合并    /cps/v2/office/merge                     /api/cps/sync/v1/merge
查询任务    /cps/v1/task/query                       /cps/v1/task/query
内容操作    /cps/v2/office/operate                   /api/cps/sync/v1/content/operate
在线编辑    /weboffice/v1/url                        /api/edit/v1/files/{file_id}/link
在线预览    /preview/v1/url                          /api/preview/v1/files/{file_id}/link
回调接口    v1/3rd/file/info                         v1/3rd/file/info

编撰人：het


快速跳转



 * 金山中台适配OfficeSDK技术说明文档
   * 背景&需求
   * 依赖版本
   * 技术说明
     * 标准适配代码位置
     * 二次适配思路
     * 测试注意事项
   * 产品调用金山中台API一览



分享链接分享链接

## 158. 金山文档中台非/open开头地址适配

> 原始路径：`/1842/1851/2249.html`  
> 相对路径：`1842/1851/2249.md`

## 金山文档中台非/open开头地址适配


## 背景

OA对接金山文档中台的标准地址为http://ip:port/open, 当金山文档中台的对接地址为http://ip:port/xxx/open 这种格式的时候，预览文件的时候将会报“400 Bad Request”，通过查看日志会发现报如下错误：

获取weboffice生成的token出错:url=http://ip:port/wps/open/auth/v1/app/inscope/token?app_id=ROVYZTLZLHQQLDXU&scope=file_format_control,file_edit;{"result":40101,"msg":"wps2 signature invalid: extract appId err"}

备注：根据异常信息分析大致可以确定是签名的问题


## 问题原因

OA在访问金山文档中台接口的时候对请求的接口做了拦截，此拦截会对请求的地址做wps-3签名,签名的规则是将appKey + contentMd5 + url + contentType + date拼接的字符串做SHA-1加密，其中url中/open之前的内容不会参与加密，所以需要将金山文档中台地址中/open之前的地址过滤掉（包含/open）


## 解决方案

工程：apps-office-plugins

修改com.seeyon.apps.weboffice.config.WPS3AuthenticationInterceptor.java类的intercept()方法，如下图所示：



编撰人：ranjunfeng、ranjf


快速跳转



 * 金山文档中台非/open开头地址适配
   * 背景
   * 问题原因
   * 解决方案



分享链接分享链接

## 159. 金山文档中台急速预览适配

> 原始路径：`/1842/1851/2265.html`  
> 相对路径：`1842/1851/2265.md`

## 金山文档中台急速预览适配


## 背景

为满足政企客户对公文类文档快速打开、不跑版、性能开销低等诉求，金山文档中台推出了急速预览模式；目前标准产品支持的在线预览模式是高清预览。如果有适配金山文档中台急速预览的诉求可按照此文档进行适配


## 解决方案


## 8.1sp1

1、涉及工程

ctp-core

2、修改com.seeyon.ctp.common.office.trans.util.OfficeTransHelper.java类的buildWpsPreviewUrl()方法，改动点如下：

改动前：

改动后：


## 8.2sp1

1、涉及的工程 apps-office-plugins

2、修改com.seeyon.apps.weboffice.manager.WpsWebOfficePreviewAdapter.java类的buildWpsPreviewUrl()方法，改动点如下：

修改前： 修改后：


## 8.3

1、涉及的工程 apps-office-plugins 2、修改com.seeyon.apps.weboffice.manager.WpsWebOfficePreviewAdapter.java类的buildWpsPreviewUrl()方法，改动点如下：

修改前： 修改后：

3、修改com.seeyon.apps.officePlugins.helper.WebOfficeURLHelper.java类的mapToWebOfficeUrlForPri()方法，改动的代码如下：

修改前：

修改后：


## 9.0sp1

1、涉及的工程 apps-office-plugins

2、修改com.seeyon.ctp.rest.resources.kingsoft.KingsoftPreviewResource.java类的buildWpsPreviewUrl()方法，改动代码如下： 改动前：



3、修改com.seeyon.apps.officePlugins.helper.WebOfficeURLHelper.java类的mapToWebOfficeUrlForPri()方法，改动的代码如下：

修改前：

修改后：

改动后：

编撰人：ranjf


快速跳转



 * 金山文档中台急速预览适配
   * 背景
   * 解决方案
     * 8.1sp1
     * 8.2sp1
     * 8.3
     * 9.0sp1



分享链接分享链接

## 160. 金山文档中台集成运行逻辑图

> 原始路径：`/1842/1851/2372.html`  
> 相对路径：`1842/1851/2372.md`

## 金山文档中台集成运行逻辑图


## 背景

V5产品集成了金山WebOffice文档中台（金山在线编辑、在线预览服务），客户想知道集成的细节，期望有一个逻辑运行图做归档记录。


## 解决方案


## 集成部署架构图

协同集成金山文档中台的部署架构图如下，主要网络要求：

1、客户端需要即能访问协同OA，又能访问金山中台服务

2、协同OA服务与金山中台服务需要网络互通




## 预览和编辑渲染逻辑图

金山在线预览和在线编辑初始化、渲染显示文件的过程是一样的，涉及到的关键动作都在逻辑图中标注：




## 在线编辑保存逻辑图

金山在线编辑保存操作运行逻辑如下图所示：



编撰人：het




快速跳转



 * 金山文档中台集成运行逻辑图
   * 背景
   * 解决方案
     * 集成部署架构图
     * 预览和编辑渲染逻辑图
     * 在线编辑保存逻辑图



分享链接分享链接

## 161. 数科在线预览缩放比例自定义调整

> 原始路径：`/1842/1851/2722.html`  
> 相对路径：`1842/1851/2722.md`

## 数科在线预览缩放比例自定义调整


## 需求

需要自定义数科在线预览打开时的页面缩放比例的场景




## 操作步骤&解决方案

工程：apps-office-plugins-front

文件路径： desktop-front/src/office/js/skLightRead/skAdapter.js

修改位置：



接口文档：



编撰人：liangyd


快速跳转



 * 数科在线预览缩放比例自定义调整
   * 需求
   * 操作步骤&解决方案



分享链接分享链接

## 162. 协同新建修改和详情页面前后端分离动态接入组件

> 原始路径：`/1842/1878/1879.html`  
> 相对路径：`1842/1878/1879.md`

## 协同新建修改和详情页面前后端分离动态接入组件


## 适用版本

V9.0及以上


## 背景

自V9.0开始，PC协同新建、查看页面进行了前后端分离改造，页面已经基于VUE实现了html化，过去基于JSP的扩展模式已经不适用。

项目上期望在前后端分离的协同页面做无侵入的前端动态注入，需要重新按照新规范进行扩展实现，本文档介绍相关扩展方法。


## 适用范围

适用于V9.0以后版本的协同前后端分离页面，请求地址格式如下：




## 动态注入js/css资源

原有JSP的extend/js动态脚本链路机制仅仅支持js代码且一旦引入，所有的业务流程都会加载此js代码，若某个客开代码出现报错或者修改了共享的资源，会影响到全部协同页面的正常运行。

前后端分离页面引入了动态加载Javascript、css静态资源，按需可以保证后续持续扩展健康发展，避免出现资源冲突、保护非相干性业务的稳定运行。



首先创建资源负载类并继承抽象接口AbstractCollaborationPlugin，通过实现方法loadPluginResource(PluginResourceLocation locationParam);完成js/css的按需加载。

public interface CollaborationPlugin {
    /**
     * 加载资源文件
     * @param locationParam 对应页面参数{@link com.seeyon.ctp.plugins.resources.PluginResourceScope}
     */
    public List<PluginResource> loadPluginResource(PluginResourceLocation locationParam);
}


PluginResourceLocation对象属性介绍：

属性          类型                     解释
location    PluginResourceScopes   页面标记：COLL_PC_SEND - 协同发送页面；COLL_PC_DEAL - 协同处理页面
isM3        boolean                布尔类型，是否是移动端
affair      CtpAffair              待办对象
template    CtpTemplate            模版对象
extParams   Map<String,Object>     扩展字段，当key为：summary - ColSummary协同对象

PluginResource返回值对象，有两个实现类介绍：

 * JavascriptResource - js资源类型
 * CssResource - css资源类型

属性        类型                   解释
path      String               资源的类型要求字符串开始固定格式为{serverRoot}例如：{serverRoot}/extend/action/example.js，前端会统一将路径替换为真实服务器路径
getType   PluginResourceType   若是js资源则用PluginResourceType，css资源用CssResource


## 编写扩展js接收事件

如何编写js代码，保证上面新增的节点动作按钮被用户点击后，将事件传递到扩展js代码中呢？

按照约束，我们会把点击事件接收到后，通过事件分发出去，事件的code为扩展节点动作的wrapContent#customerAction的值。为了防止变量污染，页面逻辑请统一在立即执行函数表达式中执行。例如example.js：

(function () {

 	$.ctp.bind('fileDiff',function(params){
		//do something
    })

  })();


为了兼容原有的老功能，我们将一些重要的参数挂载到window上面：

    const {affair, template} = businessData;
    //协同id
    window.summaryId = affair.objectId;
    //事项的id
    window.affairId = affair.id;
    //节点权限，系统内置的就是标识代码，比如newCol\collaboration，自定义的为名称
    window.nodePolicy = affair.nodePolicy;
    //流程id
    window.processId = affair.processId;
    //cap4有流程表单的数据记录id
    window.fromRecordId = affair.formRecordid;
    //工作流的示例id
    window.wfCaseId = affair.caseId;
    //协同标题
    window.subject = affair.subject;
    //cap4有流程表单的id
    window.formAppId = affair.formAppId;
    //工作流节点id
    window.wfActivityId = affair.activityId
    //工作流流程图模版id
    window.templateWorkflowId = template.workflowId;
    // 0 ： 没有做修改, 1:修改了正文   2：修改了附件 3 ： 修改了正文和附件
    window.isEditAttOrContent = 0;
    //协同所使用的模版id
    window.templateId = template.id;



## 自定义节点动作按钮


## 目的

帮助客开完成协同页面的二次开发以及标准产品侧对页面实现按钮功能定制的需求。提供三方扩展节点动作的能力，节点动作与标准产品支持的动作能力相当，支持在流程基础设置>节点权限中用户根据个人需求完成动作到任意节点权限的配置；提供能力实现对不同流程动态加载、卸载节点动作的能力。


## 名词解释

> 节点动作：协同页面上的用户可点击的按钮，比如：查看附件、关联文档、提交、发送等

> 节点权限：在协同流程中不同节点打开协同页面展示的所使用的权限，比如：发起人新建页面节点权限为新建，处理人根据节点不同可以是：协同、审批、知会等权限


## 开发扩展主要步骤

 * 实现抽象接口AbstractCustomerClassOperationLoader完成节点动作注入到系统，实现节点动作的扩展。
 * 实现抽象接口AbstractCustomizePermissionOperationForPage实现对不同节点权限下对扩展节点动作动态加载、卸载扩展，实现节点动作的运行态控制。
 * 实现接口CollaborationPlugin完成协同页面加载js/css资源加载，实现用户节点动作点击触发后的响应。


## 实现方案介绍




## 具体执行步骤

## 扩展节点动作

在xml中注入节点动作扩展的bean，继承抽象类为AbstractCustomerClassOperationLoader，完成抽象方法getClassOperations()的实现逻辑。

CLASS定义                                补充内容
AbstractCustomerClassOperationLoader   完成List<CustomerClassOperation>
                                       getClassOperations()方法的实现，此方法为扩展的动作集合
CustomerClassOperation                 自定义的节点动作对象，需要指定id\name\icon信息，和wrapContent

示例代码：

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE beans PUBLIC "-//SPRING//DTD BEAN//EN" "http://www.springframework.org/dtd/spring-beans.dtd">
<beans default-autowire="byName">
	<bean id="fileDiffCustomerClassOperation" class="com.seeyon.ctp.common.permission.bo.CustomerClassOperation">
		<!--唯一标识id-->
		<constructor-arg value="-3939844178343801046"/>
		<!--国际化名称-->
		<constructor-arg value="permission.operation.intelliContract.docComparison"/>
		<!--显示图标样式-->
		<constructor-arg value="syIcon sy-meeting-summary|#1F85EC"/>
		<property name="wrapContent" >
			<value>
		<!--customerAction为节点动作的唯一标识，用于前端监听触发的点击事件，supportPermission为该动作支持绑定的节点权限，多个用逗号分隔-->		{"attitudeAction":"","processAction":"","submitAction":"","attitudeShowName":"","category":"4","customerAction":"fileDiff","supportPermission":"inform"}
			</value>
		</property>
		<property name="operationName" value="permission.operation.intelliContract.docComparison"/>
	</bean>

	<bean id="fileDiffHistoryCustomerClassOperation" class="com.seeyon.ctp.common.permission.bo.CustomerClassOperation">
		<!--唯一标识id-->
		<constructor-arg value="5757082696558594222"/>
		<!--国际化名称-->
		<constructor-arg value="permission.operation.intelliContract.docComparisonHistory"/>
		<!--显示图标样式-->
		<constructor-arg value="syIcon sy-view_log|#1F85EC"/>
		<property name="wrapContent" >
			<value>
				<!--customerAction为节点动作的唯一标识，用于前端监听触发的点击事件，supportPermission为该动作支持绑定的节点权限，多个用逗号分隔-->{"attitudeAction":"","processAction":"","submitAction":"","attitudeShowName":"","category":"4","customerAction":"fileDiffHistory","supportPermission":"newCol,inform"}
			</value>
		</property>
		<property name="operationName" value="permission.operation.intelliContract.docComparisonHistory"/>
	</bean>

	<bean id="colCustomerClassOperationLoader" class="com.seeyon.ctp.common.permission.FileDiffCustomerClassOperationLoaderImpl">
		<property name="customerClassOperations" >
			<list>
				<ref bean="fileDiffCustomerClassOperation"/>
				<ref bean="fileDiffHistoryCustomerClassOperation"/>
			</list>
		</property>
	</bean>
</beans>


FileDiffCustomerClassOperationLoaderImpl：

public class FileDiffCustomerClassOperationLoaderImpl extends AbstractCustomerClassOperationLoader {

    private List<CustomerClassOperation>  customerClassOperations;

    @Override
    public List<CustomerClassOperation> getClassOperations() {
        return customerClassOperations;
    }

    public void setCustomerClassOperations(List<CustomerClassOperation> customerClassOperations) {
        this.customerClassOperations = customerClassOperations;
    }
}


解释：

1、创建自定义节点动作扩展类FileDiffCustomerClassOperationLoaderImpl继承抽象接口AbstractCustomerClassOperationLoader，并通过实现方法getClassOperations()暴露需要注入的扩展动作信息，同时将扩展的节点动作放入集合customerClassOperations，添加setter方法用xml方式扩展节点动作具体内容。

2、创建xml的bean定义文件，通过<property name="customerClassOperations" >指定了节点动作数据来源，此处有两个fileDiffCustomerClassOperation和fileDiffHistoryCustomerClassOperation

3、创建节点动作的具体定义信息，比如在fileDiffCustomerClassOperation中<constructor-arg>构造器方式创建CustomerClassOperation对象，并设置了wrapContent内容，配置key说明见下表格：

标签                               作用                  解释
<constructor-arg>                构造器                 参数依次为id\name\icon样式
<property name="wrapContent" >   扩展属性对象              
wrapContent#category             category分类          0- 流程调整类
                                                     1- 应用类
                                                     2- 提交类
                                                     3- 意见回复类
                                                     4- 其他 （三方业务扩展分类为其他）
wrapContent#customerAction       customerAction      改动作的标识code，此code会作为事件名称，用户点击按钮后前端事件触发
wrapContent#supportPermission    supportPermission   支持的在那些特殊的节点权限上显示，默认支持处理的节点权限，比如协同、审批等。
                                                     特殊的节点权限指：
                                                     newCol- 新建页面节点权限
                                                     inform- 知会页面节点权限

## 控制节点动作

扩展节点动作是为了1.满足同节点权限下，节点动作在部分人处理时加载显示，部分人又不显示加载。2.用户免配置，根据业务情况去动态的加载节点动作。

首先创建自定义节点权限控制类集成抽象类AbstractCustomizePermissionOperationForPage，注入到spring-bean中，需要实现是三个方法：

/**
 * 用户扩展协同页面的节点动作相关
 * 支持1：扩展协同页面的节点动作动态按需动态添加（前提是：节点动作都存在于系统中）
 * 支持2：对协同页面的节点动作进行按需过滤功能 （前提是：节点动作都存在于系统中）
 */
public abstract class AbstractCustomizePermissionOperationForPage implements ICustomizePermissionOperationCheck {

	/**
     * 控制的节点动作id集合
     *
     * @return
    */
    public abstract List<Long> getPermissionActionIds();

	/**
	 * 按需过滤节点权限上绑定的节点动作
	 *
	 * @param permissionOperationIds 控制的节点动作id集合
	 * @param customizeContext       上下文对象
	 * @param type                   0-基础区域 1 -高级区域 2- 常用区域
	 * @return true 是可以显示， false为不能显示
	 */
	public abstract Map<Long, Boolean> permissionOperationFilter(List<Long> permissionOperationIds, CustomizeContext customizeContext, int type);


	/**
	 * 把节点动作扩展到协同节点权限上去
	 *
	 * @param customizeContext 上下文对象
	 * @param type             0-基础区域 1 -高级区域 2- 常用区域
	 * @return
	 */
	public abstract List<Long> extendPermissionOperation(CustomizeContext customizeContext, int type);


	@Data
	@Builder
	@AllArgsConstructor
	public static class CustomizeContext {
		private CtpAffair affair;
		private ColSummary summary;
		private CtpTemplate template;
		private Boolean isTemplate;

		/**
		 * 节点权限code
		 * <pre>
		 * newCol 新建
		 * collaboration 协同
		 * inform 知会
		 * </pre>
		 */
		private String permissionCode;

		/**
		 * 节点权限的id
		 */
		private Long permissionId;

		/**
		 * 来pc还是移动端
		 *
		 * @see Constants.login_sign
		 */
		private String userAgent;
	}
}


示例代码：

public class ExampleForCustomizeAction extends AbstractCustomizePermissionOperationForPage {
	
	@Inject(beanName = "colCustomerClassOperationLoader")
	private CustomerOperationLoader customerOperationLoader;
    
    /**
	 * 按需过滤节点权限上绑定的节点动作
	 *
	 * @param permissionOperationIds 控制的节点动作id集合
	 * @param customizeContext       上下文对象
	 * @param type                   0-基础区域 1 -高级区域 2- 常用区域
	 * @return true 是可以显示， false为不能显示
	 */
    @Override
	public Map<Long, Boolean> permissionOperationFilter(List<Long> permissionOperationIds, CustomizeContext customizeContext, int type) {
		//特定表单的，基础按钮才实现自己的节点动作
		Long formAppId = customizeContext.getAffair().getFormAppId();
		boolean support = type == 0 && Strings.equals(123456789L, formAppId);
		Map<Long, Boolean> collect = permissionOperationIds.stream().collect(Collectors.toMap(Function.identity(), id -> support, (o1, o2) -> o2));
		return collect;
	}
	
    /**
	 * 把节点动作扩展到协同节点权限上去
	 *
	 * @param customizeContext 上下文对象
	 * @param type             0-基础区域 1 -高级区域 2- 常用区域
	 * @return
	 */
	@Override
	public List<Long> extendPermissionOperation(CustomizeContext customizeContext, int type) {
		//如果是新建节点并且用户是pc端，则把节点动作加载新建页面上
		if (Strings.equals(customizeContext.getPermissionCode(), PermissionCodeEnum.newCol.getKey())
				&& Strings.equals(customizeContext.getUserAgent(), "pc")) {
			return getPermissionActionIds();
		}
		return null;
	}
	
      /**
     * 控制的节点动作id集合，只有自己的节点动作才能控制
     *
     * @return
     */
	@Override
	public List<Long> getPermissionActionIds() {
		List<AbstractCustomerOperation> operations = customerOperationLoader.getOperations();
		if(CollectionUtils.isEmpty(operations)) {
			return Collections.emptyList();
		}
		return operations.stream().map(AbstractCustomerOp=eration::getId).collect(Collectors.toList());
	}
}


以上逻辑即实现了：新建页面新增扩展节点动作，同时按照指定的表单控制是否显示节点动作。

编撰人：het、admin


快速跳转



 * 协同新建修改和详情页面前后端分离动态接入组件
   * 适用版本
   * 背景
   * 适用范围
   * 动态注入js/css资源
     * 编写扩展js接收事件
   * 自定义节点动作按钮
     * 目的
     * 名词解释
     * 开发扩展主要步骤
     * 实现方案介绍
     * 具体执行步骤
       * 扩展节点动作
       * 控制节点动作



分享链接分享链接

## 163. 协同待办列表按钮扩展机制

> 原始路径：`/1842/1878/2002.html`  
> 相对路径：`1842/1878/2002.md`

## 协同待办列表按钮扩展机制


## 适用版本

V9.0SP1 BuildID是2024年9月之后的版本


## 解决方案

> 目的：待办列表toolbar按钮提供二次开发能力
> 
> 步骤仅需两部：1.按需动态注入js 2.js逻辑注册按钮schema信息

 1. 按需加载js代码

首先创建资源负载类并继承抽象接口AbstractCollaborationPlugin，通过实现方法loadPluginResource(PluginResourceLocation locationParam);完成js/css的按需加载。 AbstractCollaborationPlugin:

public interface CollaborationPlugin {

    
    /**
     * 加载资源文件
     * 
     * @param locationParam 对应页面参数{@link com.seeyon.ctp.plugins.resources.PluginResourceScope}
     * 
     * 
     * @author : muj
     * 
     * @date : 2019年6月6日
     *
     * @since: A8-V5 7.1SP1
     */
    public List<PluginResource> loadPluginResource(PluginResourceLocation locationParam);
    
    
}


PluginResourceLocation对象属性介绍：

属性         类型                     解释
location   PluginResourceScopes   页面标记：
                                  COLL_PC_LIST_PENDING - 协同待办列表

PluginResource返回值对象，有两个实现类介绍： JavascriptResource - js资源类型 CssResource - css资源类型

属性        类型                   解释
path      String               资源的加载路径例如：/extend/action/example.js，前端会统一将路径替换为真实服务器路径，如/seeyon/extend/action/example.js
getType   PluginResourceType   若是js资源则用PluginResourceType，css资源用CssResource

 2. 按需加载js代码逻辑编写

通过调用挂载在window上的registerComp注册按钮信息，调用一次待办注册一个按钮，如下：

(function (){
  //注册组件  extend-pending-toolbar 扩展按钮
  window.registerComp('extend-pending-toolbar',{
    eventId:'handleExtend',
    icon:'vportal vp-videoconferencing',//使用的图标
    subject:'高拍仪/高扫仪',// 名称
    click:function (selectData){
      if(window.confirm('执行了客开方法')){
        alert("选择了"+selectData.length+"条数据")
      }
      
    },
  })
})();


参数说明：

属性             作用
registerComp   注册二次开发组件方法，第一个参数是注册组件id其中extend-pending-toolbar代表待办列表的toolbar扩展
               第二个参为注册是schema信息，指明按钮的具体名称、点击函数等
eventId        按钮的id,多次注册需要保证唯一性
icon           按钮图标（未实现）
subject        按钮的名称
click          按钮点击后回调执行方法，selectData为列表页面选择的数据列

编撰人：het


快速跳转



 * 协同待办列表按钮扩展机制
   * 适用版本
   * 解决方案



分享链接分享链接

## 164. 页面设计器三方业务拓展

> 原始路径：`/1842/1878/2655.html`  
> 相对路径：`1842/1878/2655.md`

## 页面设计器三方业务拓展

> 背景：此前的一堆前、后事件，容易出现多个客开竞争冲突（同时使用流程前事件，前面的接收，后面的拒绝），多个前端请求埋点无法保障事务回滚（拿不到表单最终计算触发后的最终态数据），简化和规范协同页面扩展机制，保障协同+工作流+表单同事务提交和回滚，简化按照不同业务区分出一堆业务模块的前、后事件的问题，解决此前单一上下文无法获取完整的协同-工作流-表单完整数据获取难题

用于扩展前置事件、后置事件、适用于 发送、处理、终止、存为模板、保持待发场景，全代码执行周期进行扩展

####版本要求 9.0以及以上版本，协同前端后端分离的PC新模板支持：精致新体验布局、经典新体验布局 ####事件机制说明 表单预提交

类型           ORDER   LISTENER阶段
发送           100     PreListener
处理           100     PreListener
终止/回退/指定回退   200     PreListener
存为模版         1       NormalListener
保存待发         100     PreListener

若需要获取到预提交数据需要让order返回值大于上面的对应值，比如在发送阶段获取预提交值，则需要order>100才能查询到预提交数据

提供扩展抽象类

类型           CLASSNAME                                
发送           CollaborationThirdPartySendListener      
处理           CollaborationThirdPartyDealListener      
终止/回退/指定回退   CollaborationThirdPartyOperateListener   

对象ThirdPartyListenerContext字段说明：

FIELD NAME           FIELD DESCRIPTION                  FIELD TYPE
thirdpartParamData   三方业务数据，由自己维护 data[*].key 匹配自己的业务   ThirdpartParamData
affairId             事项id                               Long
summaryId            协同id                               Long
formAppId            表单id                               Long
formRecordId         表单数据id                             Long
templateId           模版id                               Long
activityId           节点id                               Long
processId            流程id                               String
caseId               流程实例id                             Long
affairState          协同状态                               Integer
affairSubState       协同子状态                              Integer
nodePolicy           节点权限code                           String
workItemId           工作流的workItemId                     Long
submitCode           提交操作code                           String

对象ThirdPartyListenerContext字段说明：

FIELD NAME          FIELD DESCRIPTION                      FIELD TYPE
beforeEventBO       工作流执行提交前事件参数bean                       WorkflowBeforeEventBO (Deprecated)
data                三方数据                                   List
thirdPartyContext   三方传递的上下文，在hook#thirdPartyHandle 自行写入   Map<String, Object>

示例：

后端：

public class ExampleDealListener extends CollaborationThirdPartyDealListener implements PreListener<CollaborationFinishWorkItemEvent>   {

	@Override
	public int getOrder() {
		//表单预提交之后
		return 200;
	}

	@Override
	public ServiceResult doHandle(ThirdPartyListenerContext thirdPartyListenerContext) throws BusinessException {
		ThirdpartParamData thirdpartParamData = thirdPartyListenerContext.getThirdpartParamData();
		Object confirm = thirdpartParamData.getThirdPartyContext().get("weekBlock12345");
		if (confirm instanceof Map){
			Map<String, Boolean> stringObjectMap = (Map<String, Boolean>) confirm;
			if (stringObjectMap.getOrDefault("confirm",false)){
				return ServiceResult.ok();
			}
		}
		if (Objects.nonNull(thirdPartyListenerContext.getFormAppId())){
			return ServiceResult.fail(Collections.singletonMap("errorMsg","发送拦截不通过"));
		}
		return ServiceResult.ok();
	}
}


可以扩展的接口实现说明：

接口                       说明                                                     执行顺序
PreListener              前置接口，代表的是表单预提交；工作流预提交                                  0
NormalListener           业务数据提交接口，待办工作正式提交、协同正式提交、表单正式提交、此阶段后生成提交的数据，如生成了新的待办   1
PostListener             后置接口，代表是提交后，需要触发什么动作，比如全文检索、协同触发事件、互联互通等               2
FinalListener            最后执行的接口，用于释放锁、缓存等操作，此阶段始终会执行                           3
AfterPostAsyncListener   最后执行的异步监听，用于触发事务提交成功后的动作，比如新闻、公告审批                     4

前端：

//强阻塞
$.ctp.bind('thirdPartyHandle',(args)=>{
    alert(args.data.errorMsg)；
    args.error();
});
//弱阻塞，带确认
$.ctp.bind('thirdPartyHandle',(args)=>{
    console.log('12313',args)
    var confirmation = confirm(args.data.errorMsg);
    if(confirmation){
        args.thirdPartyContext['weekBlock12345']={
            confirm:true//后端发现此key匹配的true无需再校验
        }
    args.success(); 
    }else{
       args.error();  
    }
});


事件列表：

事件KEY                   事件类型
AddNode                 同步事件
moreSign                同步事件
RemoveNode              同步事件
Terminate               同步事件
Cancel                  同步事件
return                  同步事件
specifiesReturn         同步事件
specifiesReturnCreate   同步事件
Comment                 同步事件
ContinueSubmit          异步事件
beforeDealSubmit        异步事件
createMeeting           异步事件
relationDoc             异步事件
relationAttachment      异步事件
transform               异步事件
transfer                异步事件
favorite                异步事件
sign                    异步事件
doZCDB                  异步事件
beforSendColl           同步事件
summary-leavePage       异步事件
newColl-leavePage       异步事件
thirdPartyHandle        异步事件

设计器支持状态：

状态CODE                    作用                    规则
state.affairState         是否显示处理意见（新建自由协同不显示）   不显示：新建自由协同（新建、草稿都不显示，含协同模版）
state.showRelationData    是否显示相关数据（）            不显示：新建自由协同（不含协同模版）
state.showSiderbar        是否显示侧边栏               不显示：相关数据和处理意见都不显示时候
state.showFormRuleState   是否显示智能校验              显示：表单模版
state.showPredication     是否显示流程预测              显示：表单模版
state.showPostscript      是否显示附言                不显示：模版配置不能添加附言
state.siderActiveTab      右侧胶囊当前激活页签            有附言时候：key = 发起附言
                                                无附言时候：key = 处理意见
                                                有意见锚点：key = 处理意见
                                                新建模版：key = 相关数据
state.mainActiveTab       正文、流程激活页签             正文：修改正文
                                                流程：修改流程（加签会签）
                                                


## 移动端三方业务适配使用示例

## 事件注册

// 注册第一个检查：金额检查
cmp.funProxy.setter("beforeDealSubmit ", function(data, success, error) {
    console.log("正在检查金额...");
    if (data.amount > 0) {
        success(); // 检查通过，继续下一个
    } else {
        error();   // 检查失败，流程终止
    }
});

// 注册第二个检查：库存检查（模拟异步）
cmp.funProxy.setter("beforeDealSubmit", function(data, success, error) {
    console.log("正在检查库存...");
    // 假设 checkStock 是一个返回 Promise 的业务函数
    checkStock(data.orderId).then(function() {
        success(); // Promise resolve，执行成功回调
    }).catch(function() {
        error();   // Promise reject，执行失败回调
    });
});


## 注意事项

 * 必须手动调用回调: 在 setter 注册的函数中，必须显式调用 success() 或 error()，否则代理链会卡住，导致正常流程回调永远不会执行。

编撰人：ranpf、wup


快速跳转



 * 页面设计器三方业务拓展
 * 移动端三方业务适配使用示例
   * 事件注册
   * 注意事项



分享链接分享链接

## 165. Vue工程本地调试及定位

> 原始路径：`/1842/1947.html`  
> 相对路径：`1842/1947.md`

## Vue工程本地调试及定位


## cap-front目录下的工程介绍

以V8.1SP2_Release_20230116版本下的cap-front目录： 1.一共53个以上工程目录：以pc_开头的目录是PC端的工程，m_开头的工程的移动端工程用，只有pc_/m_开头的工程才能启动，非pc_/m_开头的工程都是工程调用的公共组件 2.依赖下载：可以在cap-front的根目录下打开lerna.json文件可以看到，可以使用lerna bootstrap命令下载当前所有的工程依赖，也可以单个执行某个工程下载依赖（npm install) 3. 常用工程启动：pc-form工程的启动要依赖pkg-cap4-pc-ui,component_doc,pkg_condition ，seeyon-ui-ant工程的依赖才能正常启动，pc_unflow工程也是需要依赖seeyon-ui-ant 4.一般工程名就是对应菜单的入口


## 本地环境搭建与开发调试


## pc_form工程本地启动及调试

1.前置条件:（V8.1_Release_20211213版本为例） 1.1 安装node,建议安装node14以下版本（https://nodejs.org/dist/）



1.2.在cap-front目录下找到对应的工程，依次先下载pkg_cap4_pc_ui,component_doc,pkg_condition ，seeyon-ui-ant工程的依赖，分别执行npm install命令，以截图为例：

















3.再下载pc_form工程的依赖（npm install)，详情可参考截图； 4.本地的后端环境启动; 5.再修改pc_form目录下后台代理ip(cap-front\pc_form\config\proxy.js)和前端端口修改（cap-front\pc_form\config\index.js),前提是本地环境是启动好了,再执行npm run dev/npm start命令启动


## 如何将一个新的vue工程关联到菜单上


## 前端开发文档梳理及开发常见问题

编撰人：yangyanh


快速跳转



 * Vue工程本地调试及定位
   * cap-front目录下的工程介绍
   * 本地环境搭建与开发调试
     * pc_form工程本地启动及调试
   * 如何将一个新的vue工程关联到菜单上
   * 前端开发文档梳理及开发常见问题



分享链接分享链接

## 166. CoMi智能体技术文档

> 原始路径：`/2764/`  
> 相对路径：`2764/README.md`

子菜单名称              URL
调用CoMi Agent API   调用CoMi Agent API
调用CoMi工作流API       调用CoMi工作流API
CoMi小章鱼图标替换说明      CoMi小章鱼图标替换说明
CoMi卡片机制教程         CoMi卡片机制教程
CoMi CAP数据万能助手教程   CoMi CAP数据万能助手教程

分享链接分享链接

## 167. 调用CoMi已发布的Agent API

> 原始路径：`/2764/2765.html`  
> 相对路径：`2764/2765.md`

## 调用CoMi已发布的Agent API


## 适用场景

在CoMiBuilder后台制作发布了Agent（不包含工作流），第三方支持通过程序调用Agent API的形式进行集成。




## 适配方法


## 1、前提准备

## 1-1、准备Apikey

协同OA系统管理员后台 → CoMiBuilder → 应用中心 → API服务 → Api Key → 创建API Key给第三方调用使用，默认可选择全部接口：



## 1-2、获取远程调用Agent服务编码

首先，确保计划调用的Agent已经设计完成并正式发布。

然后，通过协同OA系统管理员后台 → CoMiBuilder → 应用中心 → Agent页签 → 搜索到计划调用的Agent，获得“服务编码”：




## 2、执行远程调用

## 2-1、非流式调用Agent

非流式调用Agent请求地址： http(https)://Nginx地址/seeyon/ai-platform/ai-manager/agent/svc/call/rest
请求方式：POST
Content-Type：application/json
Request Header：api-key


请求参数：

参数              类型       含义                                              是否必填   
chatSessionId   string   每次会话的唯一标识，需要调用者生成，使用uuid即可。                     Y      
sessionId       Long     Ai-manager生成的会话，可不传，仅当需要记忆上下文时需要传。对应上一次调用comi   N      
                         agent的输出data.aiSessionId
input           String   用户的输入内容                                         Y      
agentCode       String   ComiBuilder侧已发布的agentCode，从comiBuilder侧查看       Y      

CURL请求示例：

curl -X POST \
  http://10.101.68.10/seeyon/ai-platform/ai-manager/agent/svc/call/rest \
  -H "Content-Type: application/json" \
  -H "api-key: sjoaOMDf1Ze5YJOZUaXwD8iS87bbBOXHBOR42aTY9DijGpCidS" \
  -d '{
    "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
    "sessionId": null,
    "input": "翻译成英文：好好学习天天向上",
    "agentCode": "tansfer"
  }'


CURL请求结果输出示例：

{
    "code": "0",
    "message": "success",
    "data": {
        "id": "4481045495456417230",
        "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
        "aiSessionId": "4698884980493336821",
        "aiSessionName": null,
        "callId": "8056787592516619398",
        "agentId": "-2161078899843117468",
        "agentCode": "tansfer",
        "agentType": null,
        "assistantId": "0",
        "assistantCode": "",
        "sessionType": 1,
        "input": null,
        "messageType": 1,
        "content": "[翻译后的内容]：Study hard and make progress every day.",
        "citationsJson": null,
        "citationList": [],
        "messageTime": 1768534203520,
        "runStepId": null,
        "stepType": "",
        "stepName": "",
        "stepInput": "",
        "runStepStatus": "",
        "stepTime": null,
        "startedAt": 1768534203520,
        "completedAt": null,
        "expiredAt": null,
        "cancelledAt": null,
        "failedAt": null,
        "totalTime": null,
        "errorMsgTag": null,
        "errorCode": null,
        "promptTokens": null,
        "completionTokens": null,
        "totalTokens": null,
        "finish": null,
        "createUserName": null,
        "modelCode": null,
        "createTime": 1768534203523,
        "updateTime": 1768534203523,
        "runningStatus": null,
        "sourceType": null,
        "runSteps": null,
        "hitKnowledgeRunSteps": null,
        "needMarkBlueRunSteps": null,
        "recordSaveStatus": true,
        "assistant": null,
        "needHistoryRecord": true,
        "isInterrupt": 0,
        "currentNodeType": null
    }
}


CURL执行命令效果图：



Java远程调用代码示例：

/***
* Maven基础依赖：spring-boot-starter、spring-web、jackson-databind、spring-boot-starter-test
**/
@SpringBootTest
class DemoApplicationTests {

    @Test
    void contextLoads() {

        // CoMi Agent API地址（非流式）
        String apiUrl = "http://10.101.68.10/seeyon/ai-platform/ai-manager/agent/svc/call/rest";
        // CoMi API Key
        String apiKey = "sjoaOMDf1Ze5YJOZUaXwD8iS87bbBOXHBOR42aTY9DijGpCidS";
        // CoMi Agent 之 翻译助手编码
        String agentCode = "tansfer";


        // POST请求消息体
        Map<String, Object> requestBodyMap = new HashMap<>();
        // 通过UUID创建每次对话的chatSessionId
        requestBodyMap.put("chatSessionId", UUID.randomUUID().toString().replace("-", ""));
        requestBodyMap.put("sessionId", null);
        // 用户提示词
        requestBodyMap.put("input", "翻译成英文：好好学习天天向上");
        requestBodyMap.put("agentCode", agentCode);

        // 创建 RestTemplate 实例
        RestTemplate restTemplate = new RestTemplate();

        // 设置请求头
        HttpHeaders headers = new HttpHeaders();
        headers.setContentType(MediaType.APPLICATION_JSON);
        headers.set("api-key", apiKey);

        // 创建 HttpEntity，直接使用 Map 对象
        HttpEntity<Map<String, Object>> entity = new HttpEntity<>(requestBodyMap, headers);

        try {
            // 添加JSON消息转换器
            MappingJackson2HttpMessageConverter jsonConverter = new MappingJackson2HttpMessageConverter();
            ObjectMapper objectMapper = new ObjectMapper();
            jsonConverter.setObjectMapper(objectMapper);
            restTemplate.getMessageConverters().add(jsonConverter);

            // 更改响应类型为Map
            ResponseEntity<Map> response = restTemplate.exchange(
                    apiUrl,
                    HttpMethod.POST,
                    entity,
                    Map.class  // 返回类型为Map
            );

            // 输出响应状态和结果
            System.out.println("Status Code: " + response.getStatusCode());
            System.out.println("Response Body: " + response.getBody());
			System.out.println("Agent返回内容：" + ((Map)(response.getBody().get("data"))).get("content") );

        } catch (Exception e) {
            System.err.println("Error occurred while calling the API: " + e.getMessage());
            e.printStackTrace();
        }

    }
}


## 2-2、流式调用

流式调用Agent请求地址： http(https)://Nginx地址/seeyon/ai-platform/ai-manager/agent/svc/call/stream
请求方式：POST
Content-Type：application/json
Request Header：api-key


请求参数：

参数              类型       含义                                              是否必填   
chatSessionId   string   每次会话的唯一标识，需要调用者生成，使用uuid即可。                     Y      
sessionId       Long     Ai-manager生成的会话，可不传。仅当需要记忆上下文时需要传。对应上一次调用comi   N      
                         agent的输出data.aiSessionId
input           String   用户的输入内容                                         Y      
agentCode       String   ComiBuilder侧已发布的agentCode，从comiBuilder侧查看       Y      

流式输出-CURL请求示例（标准SSE接口）：

curl -X POST \
  http://10.101.68.10/seeyon/ai-platform/ai-manager/agent/svc/call/stream \
  -H "Content-Type: application/json" \
  -H "api-key: sjoaOMDf1Ze5YJOZUaXwD8iS87bbBOXHBOR42aTY9DijGpCidS" \
  -d '{
    "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
    "sessionId": null,
    "input": "翻译成英文：好好学习天天向上",
    "agentCode": "tansfer"
  }'




流式输出-CURL请求返回数据（第一段）：

data: {
  "id": null,
  "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
  "aiSessionId": "-4449259218539558771",
  "aiSessionName": "翻译成英文：好好学习天天向上",
  "callId": "-6430567852231800020",
  "agentId": "-2161078899843117468",
  "agentCode": "tansfer",
  "agentType": null,
  "assistantId": null,
  "assistantCode": null,
  "sessionType": 1,
  "input": "翻译成英文：好好学习天天向上",
  "messageType": 1,
  "content": "",
  "citationsJson": "",
  "citationList": null,
  "messageTime": null,
  "runStepId": null,
  "stepType": "",
  "stepName": "",
  "stepInput": "",
  "runStepStatus": "",
  "stepTime": null,
  "startedAt": null,
  "completedAt": null,
  "expiredAt": null,
  "cancelledAt": null,
  "failedAt": null,
  "totalTime": null,
  "errorMsgTag": null,
  "errorCode": null,
  "promptTokens": null,
  "completionTokens": null,
  "totalTokens": null,
  "finish": 0,
  "createUserName": null,
  "modelCode": null,
  "createTime": null,
  "updateTime": null,
  "runningStatus": null,
  "sourceType": null,
  "runSteps": [],
  "hitKnowledgeRunSteps": null,
  "needMarkBlueRunSteps": null,
  "recordSaveStatus": true,
  "assistant": null,
  "needHistoryRecord": true,
  "isInterrupt": 0,
  "currentNodeType": null
}


流式输出-CURL请求返回数据（最后一段）：

data: {
  "id": null,
  "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
  "aiSessionId": "-4449259218539558771",
  "aiSessionName": "翻译成英文：好好学习天天向上",
  "callId": "-6430567852231800020",
  "agentId": "-2161078899843117468",
  "agentCode": null,
  "agentType": null,
  "assistantId": null,
  "assistantCode": null,
  "sessionType": null,
  "input": null,
  "messageType": 5,
  "content": "",
  "citationsJson": null,
  "citationList": [],
  "messageTime": null,
  "runStepId": null,
  "stepType": null,
  "stepName": null,
  "stepInput": null,
  "runStepStatus": "completed",
  "stepTime": null,
  "startedAt": 1768785609087,
  "completedAt": 1768785609466,
  "expiredAt": null,
  "cancelledAt": null,
  "failedAt": null,
  "totalTime": "379",
  "errorMsgTag": null,
  "errorCode": null,
  "promptTokens": 0,
  "completionTokens": 0,
  "totalTokens": 0,
  "finish": 1,
  "createUserName": "admin",
  "modelCode": "qwen3-awq-32b",
  "createTime": 1768785609063,
  "updateTime": 1768785609466,
  "runningStatus": 1,
  "sourceType": null,
  "runSteps": null,
  "hitKnowledgeRunSteps": null,
  "needMarkBlueRunSteps": null,
  "recordSaveStatus": true,
  "assistant": null,
  "needHistoryRecord": true,
  "isInterrupt": null,
  "currentNodeType": null
}



## 2-3、流式结果messageType类型说明

1、messageType的各种情况

1：结果非流式
2：步骤
5：结果流式
7：命中知识源


2、消息中finish =1 代表本次会话结束，可以关闭接受消息。finish = 0 代表会话正在进行中，需要持续接收消息。

编撰人：het




快速跳转



 * 调用CoMi已发布的Agent API
   * 适用场景
   * 适配方法
     * 1、前提准备
       * 1-1、准备Apikey
       * 1-2、获取远程调用Agent服务编码
     * 2、执行远程调用
       * 2-1、非流式调用Agent
       * 2-2、流式调用
     * 2-3、流式结果messageType类型说明



分享链接分享链接

## 168. 调用已发布的CoMi工作流API

> 原始路径：`/2764/2767.html`  
> 相对路径：`2764/2767.md`

## 调用已发布的CoMi工作流API


## 适用场景

在CoMiBuilder后台制作发布了工作流，第三方支持通过程序调用工作流API的形式进行集成。




## 适配方法


## 1、前提准备

## 1-1、准备Apikey

协同OA系统管理员后台 → CoMiBuilder → 应用中心 → API服务 → Api Key → 创建API Key给第三方调用使用，默认可选择全部接口：



## 1-2、获取远程调用工作流服务编码

首先，确保计划调用的工作流已经设计完成并正式发布。

然后，通过协同OA系统管理员后台 → CoMiBuilder → 应用中心 → 工作流页签 → 搜索到计划调用的工作流，获得“服务编码”：




## 2、执行远程调用


## 请求地址（流式输出）

由于工作流可能涉及多步、阻塞式操作，故请求采用stream流式数据输出（SSE标准）：

请求地址 http(https)://Nginx地址/seeyon/ai-platform/ai-manager/workflow/svc/call/stream
请求方式：POST
Content-Type：application/json
Request Header：api-key


如调用服务和comi的ai-manager服务在同一局域网下，可以用如下地址
http://ip:port/ai-manager/workflow/svc/call/stream


请求参数：

参数              类型       含义                                                                    是否必填   
chatSessionId   string   每次会话的唯一标识，需要调用者生成，使用uuid即可。                                           Y      
workflowCode    String   已发布的工作流的服务编码                                                          Y      
input           String   用户的输入内容                                                               Y      
citations       []       有文件上传时使用，需要使用comibuilder的文件上传接口之后的结果作为此值                                     
sessionId       Long     Ai-manager生成的会话，可不传，仅当需要记忆上下文时需要传。对应上一次调用comi工作流的输出data.aiSessionId   N      
varValueMap     Map      配置了变量的workflow只能通过通过服务方式调用，调用时需要通过该字段传入变量的真实值                         N      


## 调试示例

CURL测试工作流示例：

curl -X POST \
  http://10.101.68.10/seeyon/ai-platform/ai-manager/workflow/svc/call/stream \
  -H "Content-Type: application/json" \
  -H "api-key: sjoaOMDf1Ze5YJOZUaXwD8iS87bbBOXHBOR42aTY9DijGpCidS" \
  -d '{
    "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
    "workflowCode": "v5_workflow_form_approve",
    "citations": [],
    "sessionId": "",
    "varValueMap":{}
  }'




CURL返回结果（第一段）：

data: {
    "id": "-1441631494942929507",
    "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
    "aiSessionId": "7765413880767791954",
    "aiSessionName": "",
    "callId": "-891878663125250145",
    "agentId": "-315404879017523771",
    "agentCode": "v5_workflow_form_approve",
    "agentType": null,
    "assistantId": "-315404879017523771",
    "assistantCode": "v5_workflow_form_approve",
    "sessionType": 5,
    "input": null,
    "messageType": 2,
    "content": "",
    "citationsJson": null,
    "citationList": [

    ],
    "messageTime": 1768801854756,
    "runStepId": "-8939658967002168328",
    "stepType": "智能场景识别",
    "stepName": "智能场景识别",
    "stepInput": "",
    "runStepStatus": "completed",
    "stepTime": null,
    "startedAt": 1768801854592,
    "completedAt": 1768801854756,
    "expiredAt": null,
    "cancelledAt": null,
    "failedAt": null,
    "totalTime": "164",
    "errorMsgTag": null,
    "errorCode": null,
    "promptTokens": null,
    "completionTokens": null,
    "totalTokens": null,
    "finish": 0,
    "createUserName": null,
    "modelCode": null,
    "createTime": null,
    "updateTime": null,
    "runningStatus": null,
    "sourceType": 6,
    "runSteps": null,
    "hitKnowledgeRunSteps": null,
    "needMarkBlueRunSteps": null,
    "recordSaveStatus": true,
    "assistant": null,
    "needHistoryRecord": true,
    "isInterrupt": 0,
    "currentNodeType": null
}


CURL返回结果（最后一段）：

data: {
    "id": null,
    "chatSessionId": "0d8adcfd95794adf9aab7b8dc06b0d8d",
    "aiSessionId": "7765413880767791954",
    "aiSessionName": "",
    "callId": "-891878663125250145",
    "agentId": "-315404879017523771",
    "agentCode": null,
    "agentType": null,
    "assistantId": null,
    "assistantCode": null,
    "sessionType": 5,
    "input": null,
    "messageType": 5,
    "content": "",
    "citationsJson": null,
    "citationList": [

    ],
    "messageTime": null,
    "runStepId": null,
    "stepType": null,
    "stepName": null,
    "stepInput": null,
    "runStepStatus": "completed",
    "stepTime": null,
    "startedAt": 1768801854555,
    "completedAt": 1768801855499,
    "expiredAt": null,
    "cancelledAt": null,
    "failedAt": null,
    "totalTime": "944",
    "errorMsgTag": null,
    "errorCode": null,
    "promptTokens": 134,
    "completionTokens": 2,
    "totalTokens": 136,
    "finish": 1,
    "createUserName": "admin",
    "modelCode": null,
    "createTime": 1768801854537,
    "updateTime": 1768801855499,
    "runningStatus": 1,
    "sourceType": null,
    "runSteps": null,
    "hitKnowledgeRunSteps": null,
    "needMarkBlueRunSteps": null,
    "recordSaveStatus": true,
    "assistant": null,
    "needHistoryRecord": true,
    "isInterrupt": null,
    "currentNodeType": null
}



## 流式结果messageType类型说明

1、messageType的各种情况

1：结果非流式
2：步骤
5：结果流式
7：命中知识源


2、消息中finish =1 代表本次会话结束，可以关闭接受消息。finish = 0 代表会话正在进行中，需要持续接收消息。


## 返回异常

已知，如果传入错误的工作流编码，会提示如下错误码：

{"code":"1000","message":"工作流不存在","data":null}


已知，如果工作流未发布，会提示如下错误码：

{"code":"1000","message":"工作流未发布","data":null}


编撰人：het


快速跳转



 * 调用已发布的CoMi工作流API
   * 适用场景
   * 适配方法
     * 1、前提准备
       * 1-1、准备Apikey
       * 1-2、获取远程调用工作流服务编码
     * 2、执行远程调用
   * 请求地址（流式输出）
   * 调试示例
   * 流式结果messageType类型说明
   * 返回异常



分享链接分享链接

## 169. CoMi小章鱼图标替换说明

> 原始路径：`/2764/2799.html`  
> 相对路径：`2764/2799.md`

## CoMi小章鱼图标替换说明


## 问题现象

客户有自己企业文化的图片，想要替换COMI产品的章鱼LOGO图片。


## 解决方案

目前产品内暂无实施配置的方式统一修改comi图标，而目前V5系列产品中图标均为静态资源文件，直接找到对应的文件进行替换即可明细如下：


## COMI侧边栏、智能门户中包含小章鱼的图片



** 如上图中源码存放路径为：bap-assistant-portal/src/assets/imgs **


## V5系统门户、流程审批页面、CAP表单列表、报表等中包含小章鱼的图片



** 如上图中源码存放路径为：comi-biz/src/main/webapp/apps_res/aiAssistantEntry/img **


## 注意事项：

 * 版本差异可能图标略有不同，项目上可以根据自身情况，F12的方式查看具体图标文件名称，按照上述说明替换对应源码中图片；
 * bap-assistant-portal工程为VUE工程，替换源码中图片需要编译后再部署到环境；
   编撰人：shangguan


快速跳转



 * CoMi小章鱼图标替换说明
   * 问题现象
   * 解决方案
     * COMI侧边栏、智能门户中包含小章鱼的图片
     * V5系统门户、流程审批页面、CAP表单列表、报表等中包含小章鱼的图片
   * 注意事项：



分享链接分享链接

## 170. AICard 结构化数据配置指南

> 原始路径：`/2764/2807.html`  
> 相对路径：`2764/2807.md`

## AICard 结构化数据配置指南

本指南旨在指导如何通过规范的 JSON 结构配置 aicard 组件。


## 1. 核心数据结构概览 (JSON Tree)

&lt;aicard> (根节点)
----- data (业务数据层) 
      ├---- cardType (卡片类型标识)
      ├---- businessType (业务分类标识)
      └---- businessData (业务核心内容)
            ├---- title (标题)
            ├---- desc (描述信息)
            ├---- cm (颜色模式: card-solid / background-solid)
            ├---- ha (横向对齐: left/center/right)
            ├---- lm (布局模式: single/double)
            ├---- items (卡片内容列表)
            │     ├---- content (支持 Markdown/HTML 渲染：支持加粗、颜色、链接)
            │     └---- evts (交互事件: {type, content})
            └---- btns (底部按钮列表)
                  ├---- text (按钮显示文本)
                  ├---- type (操作类型)
                  └---- content (回填逻辑/业务属性)
&lt;/aicard>                  


----------------------------------------


## 2. 核心功能说明


## 2.1 Markdown 内容渲染

卡片 items 中的 content 字段支持 Markdown 语法。

 * 富文本演示： 可使用 **加粗**、[链接](url)、<span style="color: red;">红色文字</span> 等。
 * 适用场景： 审批结论高亮、复杂业务描述的排版。


## 2.2 字段回填优先级规则

在 evts 或按钮交互中，字段标识支持 field00x（系统自动编码）或 字段名称；匹配优先级为： field00x > 数据域字段名称。

----------------------------------------


## 3. 业务场景配置示例


## 3.1 卡片布局（基础样式）

演示不同背景模式及对齐方式。

 * 关键属性： cm (ColorMode), ha (HorizontalAlign)
 * 示例代码：

xml

<aicard>
{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'有背景颜色+居中',cm:'background-solid',ha:'center',lm:'double',items:[{content:'本周潜在风险',evts:{type:'formFieldScroll',content:'本周潜在风险'}},{content:'上周总结',evts:{type:'formFieldScroll',content:'上周总结'}}],btns:[]}}}}
</aicard>
<aicard>
{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'无背景颜色+左对齐',cm:'card-solid',ha:'left',lm:'single',items:[{content:'本周潜在风险',evts:{type:'formFieldScroll',content:'本周潜在风险'}},{content:'上周总结',evts:{type:'formFieldScroll',content:'上周总结'}}],btns:[]}}}}
</aicard>
<aicard>
{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'无背景颜色+右对齐',cm:'card-solid',ha:'right',lm:'single',items:[{content:'本周潜在风险',evts:{type:'formFieldScroll',content:'本周潜在风险'}},{content:'上周总结',evts:{type:'formFieldScroll',content:'上周总结'}}],btns:[]}}}}
</aicard>


> 

----------------------------------------


## 3.2 意见回填（意见交互）

用于审批场景，将态度值回填至意见区。

 * 关键属性： btns.type: 'opinion'，content: { comment: '...', attitude: 'agree/disagree' }
 * 示例代码：

xml

<aicard>
{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'办公报销审批',cm:'background-solid',lm:'single',items:[{content:'报销事由：差旅费'}, {content:'金额：5000元'}, {content:'附件：发票扫描件'}],btns:[{text:'同意报销',type:'opinion',content:{comment:'费用合理，予以批准',attitude:'agree'}}]}}}}
</aicard>


> 

----------------------------------------


## 3.3 表单回填（联动交互）

实现卡片内容触发页面表单区域自动跳转或内容回填。

 * 关键属性： btns.type: 'formFillback'，evts.type: 'formFieldScroll'
 * 示例代码：

示例代码：

<aicard>
{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'办公周计划回填',cm:'card-solid',lm:'single',items:[{content:'上周总结：本周完成项目A需求开发，进度正常。'}, {content:'上周问题分析：测试环境偶发延迟，已协调运维优化。'}, {content:'本周潜在风险：第三方接口可能延期，需提前沟通备选方案。'}],btns:[{text:'一键回填周计划',type:'formFillback',content:'上周总结,field0001,上周问题分析,field0002,本周潜在风险,field0003'}]}}}}
</aicard>


> 

----------------------------------------


## 3.4 消息发送（通知提醒）

用于系统通知，重点在于简练的标题与描述信息。

 * 关键属性： title (简洁明确), desc (背景信息)
 * 示例代码：

示例：

<aicard>
{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'订单确认消息',cm:'card-solid',lm:'single',items:[{content:'订单号：FY20260312001,商品：智能办公套装,金额：¥1,299.00'}],btns:[{text:'发送确认消息',type:'sendMessageToBot',content:'请确认订单FY20260312001，商品为智能办公套装，金额1299元。'}]}}}}
</aicard>


> 

----------------------------------------


## 3.5 表单滚动 (联动交互)

此场景通过 evts 触发，点击卡片项或全卡片时，页面自动滚动定位至对应字段位置。

 * 配置: 在 items 或 boxEvts 中设置 type: 'formFieldScroll'。
 * 优先级: 优先识别 field00x 编码，若无则匹配对应表单字段名称。

示例：

<aicard>{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'滚动分析卡片',cm:'background-solid',lm:'single',items:[{content:'本周潜在风险'}, {content:'上周问题分析'}],btns:[{text:'查看详情',type:'formFieldScroll',content:'本周潜在风险,上周问题分析'}]}}}}
</aicard>


> 


## 3.6. 附件预览滚动 (联动交互)

实现点击卡片内容即可定位并高亮原文附件。

 1. 前置步骤：先渲染一个 span 标签提供 fileId。
    
    <span tag="seeyon-action-tag"   data='{"type": "dispatchSdkAction","action": "openFile","content": {"value":[{"fileName":"BUG报告单.doc","fileType":"application/msword","fileUrl":"/seeyon/mv/comi/office/preview?method=index&fileId=3991411971557443721&isFromComi=true"}]}}'>查看附件内容</span> 
    
    
    注意：目的是为了提供一个附件预览容器，其中/seeyon/mv/comi/office/preview?method=index&fileId=3991411971557443721&isFromComi=true是固定支持了滚动机制的访问地址，提供window.comiOfficeReadonlySearchTextHighlight({text:keywords},callbackFn)搜索高亮并滚动。
    
    支持控件：文档通编辑、金山编辑 （采用编辑预览模式打开，原厂jsapi能力）
    
    支持文件类型：word/pdf (不支持图片滚动)

 2. 交互逻辑：点击卡片 items 时，通过 officeTextScroll 匹配 content 关键字，在移动端 Office 预览中同步滚动并高亮段落。

示例数据：

<span tag="seeyon-action-tag"   data='{"type": "dispatchSdkAction","action": "openFile","content": {"value":[{"fileName":"BUG报告单.doc","fileType":"application/msword","fileUrl":"/seeyon/mv/comi/office/preview?method=index&fileId=3991411971557443721&isFromComi=true"}]}}'>查看附件内容</span> 
<aicard>
{"code":"0","message":"","data":{"cardType":"9","businessType":"5","businessData":{"data":{"title":"BUG报告单填写规范总结","items":[{"content":"BUG回显步骤需明确登录角色用户，按顺序描述在特定模块的操作动作及数据，并附带结果描述或截图；同时需根据问题类型提供相应日志、出错公文单或表单模板。","evts":{"type":"officeTextScroll","content":"BUG回显步骤撰写要求"}},{"content":"涉及性能或平台问题时，必须补充服务器配置信息（CPU、内存、杀毒软件等）、并发数据、系统上线时间、远程访问权限、配置文件参数及进程性能截图等详细环境数据。","evts":{"type":"officeTextScroll","content":"第二部分 *涉及到性能问题、平台问题"}}]}}}}
</aicard>


> 


## 4. 常见问题 (FAQ)

 * Q: 多个字段如何同时跳转？
   * A: 使用半角逗号分隔即可，如 'field0001,field0012'。
 * Q: 如果没有标题和描述怎么办？
   * A: 直接在 businessData 对象中省略 title 和 desc 字段，卡片容器会自动收缩布局。


## 5. 参考提示词

 * 卡片布局&表单滚动&意见回填&表单回填&消息发送

## Role
你是一个智能卡片配置工程师。你的任务是根据用户的需求描述，生成符合前端协议标准的结构化数据。

## Core Rule
1. 所有输出必须包裹在 `&lt;aicard>{json}&lt;/aicard>` 标签中。
2. 每个输出对象必须包含 `code: '0'`, `cardType: '9'`, `businessType: '4'`。
3. 当用户输入凌乱、缺失参数或描述模糊时，请根据文档默认规则自动补全，确保 JSON 结构合法。
4. 若用户要求生成多个场景，请在同一回答中分段输出多个 `&lt;aicard>...&lt;/aicard>`。
5. content里面多字段分隔符统一使用英文逗号[,] 格式是：**字段1,字段2,字段3**, 绝对不要增加空格或者更改分割符

## Data Documentation (参数映射表)
### 关键布局参数：
- `cm` (ColorMode): `card-solid` (背景透明/卡片实色), `background-solid` (背景实色/卡片透明)
- `ha` (HorizontalAlign): `left` / `center` / `right`
- `lm` (LayoutMode): `single` (单列), `double` (双列)

### 核心业务场景与类型映射 (Type Mapping)：
- **`formFieldScroll` (滚动联动)**: 场景：点击卡片项或按钮，页面自动滚动定位到具体表单字段。
  - 参数 `content`: 字段 名称/id 列表，如 `field0001,field0002,合同名称`，字段里面不要加空格，比如： [AI 按钮 控件] 应该是[AI按钮控件] 。
- **`opinion` (意见回填)**: 场景：审批通过/驳回。 
  - `attitude` 可选：`agree` (同意), `disagree` (驳回), `haveRead` (已阅)。
- **`formFillback` (表单回填)**: 场景：自动将预设内容填入指定输入框。
- **`sendMessageToBot` (机器人交互)**: 场景：向业务助手发送咨询或报错信息。

## Examples
### 场景1：含有复杂滚动交互的驳回审批卡片
输入：生成一个审批驳回卡片，背景采用背景实色，包含3个滚动项，按钮显示“驳回意见”且态度为驳回。
输出：
&lt;aicard>{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'审批意见',cm:'background-solid',lm:'single',items:[{content:'驳回理由：折扣过低',evts:{type:'formFieldScroll',content:'field0001'}},{content:'审批记录',evts:{type:'formFieldScroll',content:'field0070'}},{content:'附件预览',evts:{type:'formFieldScroll',content:'field0016'}}],btns:[{text:'驳回意见',type:'opinion',content:{comment:'折扣不合规',attitude:'disagree'}}]}}}}&lt;/aicard>

### 场景2：多功能组合（回填+机器人）
输入：生成一个双列布局卡片，包含表单回填按钮和机器人发送按钮。
输出：
&lt;aicard>{'code':'0','message':'','data':{'cardType':'9','businessType':'4','businessData':{data:{title:'多功能操作盘',cm:'card-solid',ha:'center',lm:'double',items:[{content:'字段001修正'}],btns:[{text:'自动填充',type:'formFillback',content:'field0001'},{text:'咨询AI',type:'sendMessageToBot',content:'这个字段怎么填？'}]}}}}&lt;/aicard>

## Instruction
请根据用户接下来的要求，生成符合上述协议的 JSON 数据。


 * 附件滚动

## 角色
你是附件内容总结助手，能够先对用户首次输入的数据进行精准总结。

### 技能

仔细分析用户首次输入的数据，提取关键信息段落信息，用简洁、准确的语言进行总结。总结内容应涵盖数据的核心要点。最终按照特定格式的AICard来返回。

##输出格式：
- 使用例子里面指定格式的span作为首行
- 使用AICard格式作为段落,注意文字内换行请使用斜杠n斜杠r（\r\n）：
&lt;aicard>
{
  "code": "0",
  "message": "",
  "data": {
    "cardType": "9", //固定值
    "businessType": "5", //固定值
    "businessData": {
      "data": {
        "title": "{段落的标题}",
        "items": [
          {
            "content": "{总结的**段落1**}",
            "evts": {
              "type": "officeTextScroll", //固定文字
              "content": "{提取原始文字的一个关键词语，必须来自用户输入}" 
            }
          },
          {
            "content": "{总结的**段落2**}",
            "evts": {
              "type": "officeTextScroll", //固定文字
              "content": "{提取原始文字的一个关键词语，必须来自用户输入}}" 
            }
          }
        ]
      }
    }
  }
}
&lt;/aicard>
例：
&lt;span tag="seeyon-action-tag"   data='{"type": "dispatchSdkAction","action": "openFile","content": {"value":[{"fileName":"人工智能研究.doc","fileType":"application/msword","fileUrl":"/seeyon/mv/comi/office/preview?method=index&amp;fileId=3991411971557443721&amp;isFromComi=true"}]}}'>查看附件内容&lt;/span> 
{ "code": "0", "message": "", "data": { "cardType": "9", "businessType": "5", "businessData": { "data": { "title": "人工智能技术及其应用概述", "items": [ { "content": "人工智能是一种通过计算机模拟人类智能行为的技术，具备学习、推理和自我纠错等能力，并随着算力和数据的发展迅速进步。", "evts": { "type": "officeTextScroll", "content": "计算机系统模拟人类智能的技术" } }, { "content": "人工智能已在医疗、金融和制造等行业广泛应用，如医疗影像识别、金融风控与客服、以及制造业生产流程优化。", "evts": { "type": "officeTextScroll", "content": "AI可以辅助医生进行影像识别和疾病预测" } } ] } } } }


### 限制
- span内容不要做任何修改，原封不动显示
- 必须严格按照先总结首次数据，再结合总结回答后续问题的流程进行操作。
- 回答内容需基于用户首次输入的数据总结以及后续问题，不得引入无关信息。
- 总结部分要简洁明了，突出重点，避免冗长复杂的表述。
- 回答语言应通俗易懂，符合正常交流习惯。


编撰人：ranpf、het


快速跳转



 * AICard 结构化数据配置指南
   * 1. 核心数据结构概览 (JSON Tree)
   * 2. 核心功能说明
     * 2.1 Markdown 内容渲染
     * 2.2 字段回填优先级规则
   * 3. 业务场景配置示例
     * 3.1 卡片布局（基础样式）
     * 3.2 意见回填（意见交互）
     * 3.3 表单回填（联动交互）
     * 3.4 消息发送（通知提醒）
     * 3.5 表单滚动 (联动交互)
     * 3.6. 附件预览滚动 (联动交互)
   * 4. 常见问题 (FAQ)
   * 5. 参考提示词



分享链接分享链接

## 171. CoMi CAP数据万能助手教程

> 原始路径：`/2764/2808.html`  
> 相对路径：`2764/2808.md`

## CoMi CAP数据万能助手教程

> 用户agent配置场景需要关联底部数据查询分析的场景，本文提供一个自然语言描述需求的方式查询任意查询报表\无流程列表的数据，支持任意字段过滤和任意数据字段和长度范围的查询机制

## 效果

如："找出需求里面包含集团化财的客户和对应需求"


## 步骤

## 1. 将目标底部配置为无流程列表/报表

## 2. 进入目标列表，利用数据智能分析的能力发起任意对话，用于捕获列表参数

进入后台【集团管理员/单位管理员】/CoMiBuilder/应用/数据智能分析 找到刚才的对话 ** 进入页面日志/找到刚才的对话/详情/点击调用Agent 找到输入里面的变量 ** 注意保存好如图所示的变量：

{
  "mark": "page_832f7b3",
  "appServiceType": "cap4Unflow",
  "businessId": "-4651549148098379424",
  "subBusinessId": "-5626447884627064366",
  "showPopUp": false,
  "platformTag": "pc",
  "oaVersion": "V10_0SP1_260312_123013_16"
}


## 3. 进行agent调试验证

进入 智能体工作室/工作流/前往工作台/找到CAP数据万能助手 点击确认设计，进入页面后点击编译后，点击运行，将上一步的参数输入进去，验证查询效果，如图： 点击开始运行后详情里面查看效果

> 注意：如果无此agent可以自行导入下载附件

## 4. 集成到工作流的大模型节点

> 场景举例：辅助审批场景需要做相似信息推荐，通过当前表单的几个字段，查询类似业务的低表数据进行关联分析

实现思路：利用辅助审批或AI控件，把需要分析的业务字段通过工作流agent参数机制传递，底表数据通过CAP数据万能助手作为智能体节点进行提取，最后使用普通大模型节点分析底表数据进行推荐。 参考工作流：

参考下载 下载附件

编撰人：ranpf


快速跳转



 * CoMi CAP数据万能助手教程
   * 效果
   * 步骤
     * 1. 将目标底部配置为无流程列表/报表
     * 2. 进入目标列表，利用数据智能分析的能力发起任意对话，用于捕获列表参数
     * 3. 进行agent调试验证
     * 4. 集成到工作流的大模型节点



分享链接分享链接
