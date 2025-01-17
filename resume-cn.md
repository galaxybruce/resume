# 张小龙

## android架构师

- 联系电话: 13739188962
- 电子邮箱: [282347554@qq.com](282347554@qq.com)
- GitHub主页: [https://github.com/galaxybruce](https://github.com/galaxybruce)


## 自我描述
我是一名安卓应用软件工程师，具有十几年的安卓应用开发经验和10年的带队经验。在过往的工作中，我不仅积累了丰富的实战经验，还锻炼了快速学习新技术和高效解决复杂问题的能力：
* 擅长总结项目中常用的逻辑并封装成工具类。
* 对三方库进行二次封装，方便后期维护和替换。
* 经常和团队成员探讨技术方案以及分享技术成果。
* 喜欢阅读github上的比较流行的开源项目。
* 不断尝试新技术以及优秀的解决方案（通过开发一个通用的app框架并在上面不断验证技术和流程）。
* 不断优化开发流程、开发规范、开发效率，并且有比较好的落地经验。
* 丰富的带队经验和团队协作经验。


## 工作经验
### 一、**Android高级研发经理** -南京元数科技有限公司

*2023/03 - 至今*

负责 Android 端的 架构设计、基础组件研发、性能优化、重点业务开发以及团队管理等工作：
1. app和pos端的架构设计
2. 三方订单自动接单打印小票以及语音播报开发
3. 价签打印开发
4. 移动收银系统开发
5. 安卓POS系统研发
6. 安卓自助收银系统研发
7. 团队的日常业务开发进度管理和人员协调以及技术方案设计

### 二、**Android高级研发经理** -江苏联童科技有限公司

*2018/12 - 2023/03*

负责 Android 端的 架构设计、基础组件研发、性能优化、重点业务开发以及团队管理等工作。
1. app的架构设计
2. 盘点业务开发
3. 直播业务开发
4. 团队的日常业务开发进度管理和人员协调以及技术方案设计

### 三、**Android研发经理** -[孩子王儿童用品股份有限公司](https://www.haiziwang.com/)

*2015/09 - 2018/12*

主要负责 Android 端的 架构设计、基础组件研发、性能优化、重点业务开发以及团队管理等工作，主要内容如下：
#### 技术建设

* **App架构设计**。应用的是行业内比较流行的MVVM架构(DataBinding + LiveData + Lifecycle + Retrofit + Kotlin)。

* **生成代码插件**。一键生成基于MVVM架构的代码模板文件，并自动建立文件间的关联，可以直接运行。也就是开发一个页面，只要输入页面业务名称就会自动生成一些列文件（activity/fragment/dialog、layout、viewmode、request)，极大提高团队研发效率，同时保证了代码的规范。

* **内存优化**。使用Profiler、MAT等工具持续对app进行内存监控、优化。保证了app运行时的流畅度。

* **启动速度优化**。通过对启动时的任务分类，并研发具有依赖关系的任务启动框架大大提高了app启动速度，并且后续持续增加功能也不会明显影响启动速度。

* **基础组件研发**。为提高团队研发效率，不断提供可复用的基础组件。如相册库、文件路径统一管理、封装了具备下拉刷新分页能力的RecyclerView（空视图、错误视图、下拉刷新、上拉加载封装在一个View中，使其能在activity、fragment、dialog中灵活使用而不需要各种基类）、彻底优雅的解决startActivityForResult调用繁琐的问题等

* **三方库封装**。方便更高效使用三方库、提高三方库升级的便利性。如图片加载glide库二次封装、腾讯云上传下载二次封装、下拉刷新上拉加载组件二次封装等，Rxjava封装三方库等

* **APP渐进式组件化方案**。对工程进行组件化方案改造后，模块间完全解耦，并且能很好的互相通信，甚至能灵活选择哪些module进行打包。组件化提高了团队相互协作、并行开发的效率，特别是能够快速适应不同复杂业务的并行开发。

* **约束代码边界的pin工程方案**。自研的gradle插件，一种约束业务代码边界的高效方式，比module颗粒更小，编译速度更快。

* **业务库多平台复用**。多平台复用的能力为公司很多业务在多个app上运营提供了很好的支持。

* **git代码仓库**。带领团队从svn切换到git。gitlab代码库维护、git-flow流程规范制定以及分享。

* **代码规范制定并负责落实**。经过多年的经验积累，我在约束团队代码规范方面做了很多努力，并取得了很好的效果，总结起来经历了5个阶段：制定规范->文档落实->代码框架层约束->开发插件生成代码模板。最终把规范落实到插件上，让团队所有人写的代码如同一个人写的一样，新成员也很容易融入团队。

* **新技术探索和落实**。如flutter、kotlin、jetpack在项目中落实。

* **MVVM架构落实**。推动团队从MVP架构切换到MVVM模式，activity和fragment基类同时兼容MVP和MVVM模式，保证团队无缝切换。基于Jetpack的MVVM架构，对提高开发效率、避免空指针的、处理事件分发、生命周期管理等收益很大。

* **Android项目编译速度优化**。通过自研的插件[AndroidPionner](https://github.com/galaxybruce/AndroidPionner) ，大大提高了编译速度。从原来运行8分钟左右，降到30秒左右。

* **flutter混编现有的项目**。用dart写的脚本，能够批量把flutter以及flutter依赖的三方插件上传到maven远程仓库，保证混编项目灵活切换对flutter源码依赖以及maven依赖。保证了flutter对现有项目的透明度，不影响其他成员对flutter的依赖。

* **用docker搭建maven仓库**。搭建maven仓库，才可以让工程化建设成为可能。

* **Android云控**。基于Appium开发的android群控，实现微信养号、社群运营等功能。
  
* **无障碍编程**。利用系统无障碍实现自动化脚本任务，比如用来做自动化测试任务、批量执行某音赚钱任务。
* **uniapp** 在已有的项目中集成uniapp小程序sdk并进行简单的小程序开发。
  
#### 特色业务
* **订单打印** 蓝牙打印机、一体机等订单打印业务，支持手动打印以及商家接单后自动连续打印。
* **IM客服** 基于socket长连接的客服IM App端的研发，支持C端用户和B端商家的实时在线通信功能。
* **商家进销存ERP系统开发** 比如盘点、调拨、拣货|复核、采购验收、采购退货、储位管理等app侧功能研发
* **直播** 基于七牛的app侧直播功能研发、包括直播、连麦功能。
* **智慧大屏** 商家门店的大屏应用开发
* **社区模块** 负责孩子王app社区模块的开发，包括发帖、在线相册、专家问答等功能。

#### 团队管理
* **需求评审**。参与团队需求评审、根据组员能力水平、特长等分配业务需求。
* **研发前期** 对复杂业务组织技术方案评审，选择合适的技术方案落地。
* **研发后期** 组织团队进行code review、组织交叉测试。
* **线上bug** 定期组织团队对线上bug进行复盘，总结经验并落实到框架层 或者 规范上。
* **业务覆盖** 需求不忙的时候，组织组员互相熟悉对方业务、代码并输出文档。
* **人员离职** 离职有专门的交接文档，包括业务名称、交接人、产品负责人、测试负责人、正在做的需求tapd、代码地址以及分支介绍、上线日期、拉入对应的群、备注说明。

### 四、**高级Android开发工程师** -[诚迈科技](https://www.archermind.com/)

*2010/07 - 2015/09*

在「Android 对外业务事业部」主要从事android平台的智能手机应用程序开发。在这个公司从刚开始接触Android到核心工程师再到项目经理的角色转变，主要内容如下：

* 华为即时聊天IM工具Hotalk开发。
* 华为应用市场App开发。
* 华为DBank音乐app项目android手机客户端开发。

### 五、**Java开发工程师** -[联创科技（南京）有限公司](http://www.lianchuang.com/)

*2008/07 - 2010/06*

web应用程序研发，所用技术：java，struts，spring，ibatis，birt，oracle，weblogic，unix。

## 技能专长

以下都是我平时用过或熟悉的编程语言、框架、软件及工具。

### 我的开源项目
- [AndroidTouchStone](https://github.com/galaxybruce/AndroidTouchStone) - 应用了android最新特性的一个成熟的app壳子项目。
- [GAndroidCodeTemplateForAS](https://github.com/galaxybruce/GAndroidCodeTemplateForAS) - 配合[AndroidTouchStone](https://github.com/galaxybruce/AndroidTouchStone) 项目的代码生成插件。
- [AndroidPionner](https://github.com/galaxybruce/AndroidPionner) - android项目编译插件（批量上传maven、module支持多平台、pin工程编译）。
- [Anchors](https://github.com/galaxybruce/Anchors) - fork开源项目改造的app启动任务框架。

### 擅长的编程语言

- [Java](https://www.java.com)
- [Kotlin](http://kotlinlang.org)
- [Python](https://www.python.org)
- [Shell](http://www.linuxshell.it)
- [JavaScript](https://www.javascript.com)
- [HTML](https://www.w3.org/html)
- [Dart](https://dart.cn/)
- [Groovy](http://www.groovy-lang.org/learn.html)

### 擅长的框架

- [Jetpack](https://developer.android.google.cn/jetpack)
- [RxJava](https://reactivex.io/)
- [RxAndroid](https://github.com/ReactiveX/RxAndroid)
- [EventBus](https://github.com/greenrobot/EventBus)
- [Retrofit](https://github.com/square/retrofit)
- [Gson](https://github.com/google/gson)
- [Glide](https://github.com/bumptech/glide)
- [ARouter](https://github.com/alibaba/ARouter)
- [Flutter-Boost](https://github.com/alibaba/flutter_boost)
- [fish-redux](https://github.com/alibaba/fish-redux)
- [Vue](https://cn.vuejs.org/)


### 经常使用的工具
- [Adobe Photoshop](http://www.adobe.com/cn/products/cs6/photoshop.html)
- [Alfred 3](https://www.alfredapp.com)
- [Android Studio](https://developer.android.com/studio/index.html?hl=zh-cn)
- [vsCode](https://code.visualstudio.com/)
- [Git](https://git-scm.com)
- [IntelliJ IDEA](https://www.jetbrains.com/idea)
- [IntelliJ IDEA CE](https://www.jetbrains.com/idea)
- [iTerm](https://www.iterm2.com)
- [on-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- [Postman](https://www.getpostman.com)
- [PyCharm](https://www.jetbrains.com/pycharm)
- [Navicat-Premium](http://www.navicat.com.cn/products/navicat-premium)
- [Source Tree](https://www.sourcetreeapp.com)
- [Charles](https://www.charlesproxy.com/)
- [MWeb](https://zh.mweb.im/)
- [印象笔记](https://www.yinxiang.com/)
- [Plant-UML](https://plantuml.com/zh/)
- [Jenkins](https://www.jenkins.io/)
- [幕布（思维导图工具）](https://mubu.com/home)

## 教育经历

*2004 - 2008* [安徽工业大学](https://www.ahut.edu.cn/) 计算机科学与技术 本科


## 个人荣誉

* 3 次 **二等校奖学金**。
* 党员


## 兴趣爱好

喜爱踢球。
