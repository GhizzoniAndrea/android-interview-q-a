### 前言
> 梳理一下面试过程的知识点，为了以后可以更直观地回忆

### 面试前准备
- [扫清Android面试障碍](http://www.bingjie.me/2016/05/12/%E6%89%AB%E6%B8%85%E9%9D%A2%E8%AF%95%E5%89%8D%E7%9A%84%E5%87%86%E5%A4%87.html)

- [一个五年Android 开发者百度、阿里、聚美、映客的面试心经](https://www.diycode.cc/topics/165)

- [HR面试小总结--不定期更新](http://www.jianshu.com/p/6ba84767c5d3)

- [面试前准备](http://lastdays.cn/2016/05/17/ex/)

- [回答阿里社招面试如何准备，顺便谈谈对于Java程序猿学习当中各个阶段的建议](http://www.cnblogs.com/zuoxiaolong/p/life51.html)

- [开发者面试指南](http://www.jianshu.com/p/47d71eaeeccb)

- [面试时，问哪些问题能试出一个 Android 应用开发者真正的水平？](https://www.zhihu.com/question/19765032)

### 简历
- [80% 以上简历都是不合格的](http://b.codekk.com/detail/Trinea/%E4%B8%80%E5%A4%A7%E5%8D%8A%E4%BB%A5%E4%B8%8A%E7%AE%80%E5%8E%86%E9%83%BD%E6%98%AF%E4%B8%8D%E5%90%88%E6%A0%BC%E7%9A%84)

### 腾讯
- synchronize用法
- volatile用法
- 动态权限适配方案，权限组的概念
- 网络请求缓存处理，okhttp如何处理网络缓存的
- 图片加载库相关，bitmap如何处理大图，如一张30M的大图，如何预防OOM
- 进程保活
- ListView图片加载错乱的原理和解决方案
- https相关，如何验证证书的合法性，https中哪里用了对称加密，哪里用了非对称加密，对加密算法（如RSA）等是否有了解

### 阿里巴巴
- LRUCache原理
- 图片加载原理
- 模块化实现（好处，原因）
- JVM
- 视频加密传输
- 统计启动时长,标准
- 如何保持应用的稳定性
- ThreadLocal 原理
- 谈谈classloader
- 动态布局
- 热修复,插件化
- HashMap源码,SpareArray原理
- 性能优化,怎么保证应用启动不卡顿
- 怎么去除重复代码
- SP是进程同步的吗?有什么方法做到同步
- 介绍下SurfView
- HashMap实现原理，ConcurrentHashMap 的实现原理
- BroadcastReceiver，LocalBroadcastReceiver 区别
- Bundle 机制
- Handler 机制
- android 事件传递机制
- 线程间操作List
- App启动流程，从点击桌面开始
- 动态加载
- 类加载器
- OSGI
- Https请求慢的解决办法，DNS，携带数据，直接访问IP
- GC回收策略
- 画出 Android 的大体架构图
- 描述清点击 Android Studio 的 build 按钮后发生了什么
- 大体说清一个应用程序安装到手机上时发生了什么；
- 对 Dalvik、ART 虚拟机有基本的了解；
- Android 上的 Inter-Process-Communication 跨进程通信时如何工作的；
- App 是如何沙箱化，为什么要这么做；
- 权限管理系统（底层的权限是如何进行 grant 的）；
- 进程和 Application 的生命周期；
- 系统启动流程 Zygote进程 –> SystemServer进程 –> 各种系统服务 –> 应用进程
- RecycleView ListView 的区别,性能

### 滴滴
- MVP
- 广播（动态注册和静态注册区别，有序广播和标准广播）
- Service生命周期
- Handler实现机制（很多细节需要关注：如线程如何建立和退出消息循环等等）
- 多线程（关于AsyncTask缺陷引发的思考）
- 数据库数据迁移问题
- 设计模式相关（例如Android中哪里使用了观察者模式，单例模式相关）
- 微信的聊天数据在本地都是加密处理的（防止root了被破解），设计一个类似的本地数据存储系统
- x个苹果，一天只能吃一个、两个、或者三个，问多少天可以吃完
- Android相关你最擅长哪一块
- TCP与UDP区别与应用（三次握手和四次挥手）涉及到部分细节（如client如何确定自己发送的消息被server收到） HTTP相关 提到过Websocket 问了WebSocket相关以及与socket的区别
- 是否熟悉Android jni开发，jni如何调用java层代码
- 进程间通信的方式
- java注解
- 计算一个view的嵌套层级
- 项目组件化的理解
- 基于自身工作经验和计算机相关知识，给出 移动端地图局部加载 瓦片大小的像素大小估值
- 多线程断点续传原理
- Android系统为什么会设计ContentProvider，进程共享和线程安全问题
- jvm相关
- Android相关优化（如内存优化、网络优化、布局优化、电量优化、业务优化）
- EventBus实现原理

### 美团
- 线程挂起，休眠，释放资源相关，唤醒，线程同步，数据传递，问了很多线程的问题，问了20分钟大概
- static synchronized 方法的多线程访问和作用，同一个类里面两个synchronized方法，两个线程同时访问的问题
- 内部类和静态内部类和匿名内部类，以及项目中的应用
- 泛型是什么以及在项目中的应用
- handler发消息给子线程，looper怎么启动
- down、move、up事件的传递
- activity栈
- 封装view的时候怎么知道view的大小
- intent-filter
- arraylist和linkedlist的区别，以及应用场景
- 怎么启动service，service和activity怎么进行数据交互
- 下拉状态栏是不是影响activity的生命周期，如果在onStop的时候做了网络请求，onResume的时候怎么恢复
- view渲染

### 知乎
- 快排时间复杂度是怎么算出来的
- HashMap的结构
- 如何取桶下标
- hashcode是什么
- 与运算是什么

### 其他
- Java集合框架
- IO流
- Android事件分发
- 自定义View绘制机制和加载过程
- RxJava
- 如何选择图片加载框架
- ListView的优化方式
- Activity的启动模式
- Activity缓存方法
- 如何保证Service不被杀死
- TCP的连接过程、为什么需要心跳
- 推送的原理

### 知识储备
- [图解集合1：ArrayList](http://www.cnblogs.com/xrq730/p/4989451.html)

- [图解集合2：LinkedList](http://www.cnblogs.com/xrq730/p/5005347.html)

- [图解集合3：CopyOnWriteArrayList](http://www.cnblogs.com/xrq730/p/5020760.html)

- [图解集合4：HashMap](http://www.cnblogs.com/xrq730/p/5030920.html)

- [图解集合5：不正确地使用HashMap引发死循环及元素丢失](http://www.cnblogs.com/xrq730/p/5037299.html)

- [图解集合6：LinkedHashMap](http://www.cnblogs.com/xrq730/p/5052323.html)

- [6.1 （番外）深入源码理解HashMap、LinkedHashMap，DiskLruCache](http://www.jianshu.com/p/b0793fbd1322)

- [Java集合框架分析-HashMap](http://www.jianshu.com/p/76f5a3d12c28)

- [线性表（ArrayList 和 LinkedList源码分析）](http://www.jianshu.com/p/185b3d44a023)

- [HashMap深度剖析](https://zhuanlan.zhihu.com/p/27607844)

- [Java集合框架分析-Iterator](http://www.jianshu.com/p/57cbf9602ab1)

- [Java容器类源码-ArrayList的最全的源码分析](http://www.jianshu.com/p/2d0d77457043)

- [Java集合框架分析-ArrayList](http://www.jianshu.com/p/36730a42d51b)

- [图解集合7：红黑树概念、红黑树的插入及旋转操作详细解读](http://www.cnblogs.com/xrq730/p/6867924.html)

- [图解集合8：红黑树的移除节点操作](http://www.cnblogs.com/xrq730/p/6882018.html)

- [由 HashMap 引申出的技术深度讨论](https://mp.weixin.qq.com/s?__biz=MzIwNzU5NTQ1Mg==&mid=2247483699&idx=1&sn=fa5d59ec80474b971d37ee8fa5783354&chksm=970eb3e0a0793af6510fe1455b71ac6e0fca2b663b32b132042177fa59de3077ec4774c26f10&scene=0&key=ff6b7666d477ff273543d64cd3fc09962e6780c432c686293d2d43b8bf4f920fcb9fb17064eb32531d0e0f24dc5aa0c50d1bd91c0d6ad906e4bfa4e9af82c1dd56e2b51baa7be9d67d666d40484bf6b5&ascene=0&uin=NjkzMTg2NDA%3D&devicetype=iMac+MacBookPro11%2C2+OSX+OSX+10.12.5+build(16F73)&version=12020810&nettype=WIFI&fontScale=100&pass_ticket=ebineaMbB8BVIeUpnUZjBm8%2BZice%2Bhba5IDsVDpufNY%3D)

- [Android WebView —— Java 与 JavaScript 交互总结](https://juejin.im/post/5840270a128fe1005894e6ec)

- [彻底理解 Android Binder 通信架构](https://www.diycode.cc/topics/384)

- [彻底理解Android Binder通信架构](http://gityuan.com/2016/09/04/binder-start-service/)

- [startActivity启动过程分析](http://gityuan.com/2016/03/12/start-activity/)

- [史上最全 Android 面试资料集合](http://www.jianshu.com/p/d1efe2f31b6d)

- [这里有一份面经，请查收](http://blog.jobbole.com/103105/)

- [TCP 的连接和释放](https://juejin.im/entry/57763b7aa633bd00570baf23)

- [Service 要点全解析](https://juejin.im/entry/576a25e12e958a00699cb1ad)

- [Android面试重点难点](https://juejin.im/entry/57466b5e71cfe40068cd862a)

- [扫清Android面试障碍](https://juejin.im/entry/574682be2e958a002dbbec9a)

- [面试前的准备](http://lastdays.cn/2016/05/17/ex/)

- [Java中的几个HashMap/ConcurrentHashMap实现分析](http://www.importnew.com/19685.html)

- [Wireshark 基本介绍和学习 TCP 三次握手](http://www.codeceo.com/article/wireshark-and-tcp-3-hand.html#0-tsina-1-30953-397232819ff9a47a7b7e80a40613cfe1)

- [排序算法总结](https://segmentfault.com/a/1190000004994003)

- [如何设计实现一个LRU Cache？](http://www.importnew.com/18758.html)

- [快速了解 Android 重要机制－收藏必备](https://juejin.im/entry/56f0e148816dfa005181ab22)

- [查找算法之顺序、二分、二叉搜索树、红黑树 详细比较总结](https://juejin.im/entry/56eecbb6128fe100513d1a20)

- [就是要你懂Java中volatile关键字实现原理](http://www.cnblogs.com/xrq730/p/7048693.html)

- [理解 Java 中的弱引用](https://juejin.im/entry/5674e77800b0023c617f0484)

- [程序员必须知道的 10 大基础实用算法及其讲解](https://juejin.im/entry/56d823f9d342d30054803735)

- [面试中的 10 大排序算法总结](http://www.codeceo.com/article/10-sort-algorithm-interview.html)

- [40个Java多线程问题总结](http://www.importnew.com/18459.html)

- [我的Android面试经验总结](http://android.jobbole.com/82565/)

- [Java集合框架](http://www.importnew.com/19853.html)

- [Android 内存泄漏解决方案](https://juejin.im/entry/5762b1d7816dfa00544680a0)

- [Picasso源码揭秘](https://segmentfault.com/a/1190000005759947)

- [Android 中的 Service：Binder，Messenger，AIDL](https://juejin.im/entry/575697872e958a0068cdf056)

- [Android性能优化](https://mp.weixin.qq.com/s?__biz=MzIxNDE1NjQ2Mw==&mid=2649872276&idx=1&sn=baaa38109e103653c712f6e9a54cf647#rd)

- [这可能是目前最详细的安卓task, launchMode, intent flag测试分析与总结了](https://blog.piasy.com/2016/03/19/Android-Task-And-Back-Stack)

- [Android 内存泄漏案例和解析](http://drakeet.me/android-leaks/)

- [面试总结](http://www.importnew.com/22637.html)

- [双重检查锁定与延迟初始化](http://www.infoq.com/cn/articles/double-checked-locking-with-delay-initialization)

- [Java集合框架中隐藏的设计套路](http://blog.csdn.net/sdkfjksf/article/details/54380659)

- [Android Binder 机制原理（史上最强理解，没有之一）](https://juejin.im/entry/589537b82f301e006904eb3e)

- [Android WebView详解，常见漏洞详解和安全源码](https://juejin.im/post/58a037df86b599006b3fade4)

- [深入剖析 Android中的 ArrayMap](http://droidyue.com/blog/2017/02/12/dive-into-arraymap-in-android/index.html)

- [重新认识java（九） ---- 内部类](http://blog.csdn.net/qq_31655965/article/details/54988623)

- [【死磕Java并发】—–深入分析synchronized的实现原理](http://cmsblogs.com/?p=2071)

- [【死磕Java并发】—–深入分析volatile的实现原理](http://cmsblogs.com/?p=2092)

- [Android消息机制学习笔记](https://zhuanlan.zhihu.com/p/25222485)

- [Activity 与 Window、PhoneWindow、DecorView 之间的关系简述](http://gudong.name/2017/05/08/activity-windown-decorview.html)

- [5分钟完全理解Android Handler](https://android-notes.github.io/2016/12/03/5%E5%88%86%E9%92%9F%E5%AE%8C%E5%85%A8%E7%90%86%E8%A7%A3android-handler/)

- [Android事件传递三部曲：本地广播LocalBroadcastManager](https://shaohui.me/2017/01/21/android-message-3-localBroadcast/)

- [关于 Android 应用多进程的整理](http://droidyue.com/blog/2017/01/15/android-multiple-processes-summary/index.html)

- [［译］Android Activity 和 Fragment 状态保存与恢复的最佳实践](https://juejin.im/post/5860b20b1b69e6006cdf5c8e)

- [Android：这是一份很详细的Socket使用攻略](http://www.jianshu.com/p/089fb79e308b)

- [Android：深入四大组件系列](http://liuwangshu.cn/tags/Android%E6%B7%B1%E5%85%A5%E5%9B%9B%E5%A4%A7%E7%BB%84%E4%BB%B6/)

- [Android深入理解Context（一）Context关联类和Application Context创建过程](https://juejin.im/post/5930db500ce4630057f2b28b)

- [Activity全方位了解，总有你不知道的一面](http://lruheng.com/2017/02/22/Activity%E5%85%A8%E6%96%B9%E4%BD%8D%E4%BA%86%E8%A7%A3%EF%BC%8C%E6%80%BB%E6%9C%89%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84%E4%B8%80%E9%9D%A2/)

- [面试算法实践与国外大厂习题指南](https://zhuanlan.zhihu.com/p/25719965)

- [从框架层分析如何启动未注册的 Activity](https://zhuanlan.zhihu.com/p/26455221)

- [15个顶级Java多线程面试题及回答](http://ifeve.com/15-java-faq/)

- [Java面试中遇到的一些经典算法题目](http://pengcqu.iteye.com/blog/504628)

- [Android面试重点难点](http://blog.csdn.net/codeemperor/article/details/51004189)

- [一道面试题比较synchronized和读写锁](http://www.importnew.com/20865.html)

- [Android 面试要点](https://mp.weixin.qq.com/s?__biz=MzAxMTI4MTkwNQ==&mid=2650820648&idx=1&sn=cb9ee924f2ded3358dd6c256803cc687&scene=0#wechat_redirect)

- [2016年未，腾讯，百度，华为，搜狗和滴滴面试题汇总](https://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247484286&idx=1&sn=e5843fb79d8a36ab063699b5fb9a0711&chksm=eae1f62cdd967f3a576396f8402581326b835b8327ed5f20f23896fcd22c2115e77863b4115b#rd)

- [Android 面试资料集锦](http://jingbin.me/2017/02/20/Android%20%E9%9D%A2%E8%AF%95%E8%B5%84%E6%96%99%E9%9B%86%E9%94%A6/)

- [面试题思考：try 代码块中含 return 语句时，代码执行顺序](https://juejin.im/post/5901cefa44d90400690cd3d4)

- [阿里面试题锦集](http://www.jianshu.com/p/cf5092fa2694)

- [这些Android面试题你一定需要](https://mp.weixin.qq.com/s?__biz=MzI0MjE3OTYwMg==&mid=2649548612&idx=1&sn=8e46b6dd47bd8577a5f7098aa0889098&chksm=f1180c39c66f852fd955a29a9cb4ffa9dc4d528cab524059bcabaf37954fa3f04bc52c41dae8&scene=21#wechat_redirect)

- [Android 开发工程师面试指南](https://www.diycode.cc/wiki/androidinterview)

- [一线互联网公司面试简单分析](http://www.jackway.cn/2016/12/07/interview-1/)

- [面试中所遇到的那些坑](http://www.jianshu.com/p/aa8f47ea2a8a)

- [17年2月面试经验](https://guolei1130.github.io/2017/02/16/17%E5%B9%B42%E6%9C%88%E9%9D%A2%E8%AF%95%E7%BB%8F%E9%AA%8C/)

- [快速了解Android重要机制](http://www.jianshu.com/p/5f6d79323923)

- [RecyclerView技术栈](http://www.jianshu.com/p/16712681731e)

- [安卓开发中遇到的重难点解析，也包括平常的读书笔记和知识点整理](https://github.com/ZhaoKaiQiang/AndroidDifficultAnalysis/)

- [【凯子哥带你学Framework】Activity启动过程全解析](http://blog.csdn.net/zhaokaiqiang1992/article/details/49428287)

- [Android Activity 启动模式的功能验证](http://www.codeceo.com/article/android-activity-start-service.html)

- [基础与细节](https://segmentfault.com/a/1190000008720237)

- [问题与答案](http://blog.csdn.net/dd864140130/article/details/55833087)

- [Java线程面试题 Top 50](http://www.importnew.com/12773.html)

- [Android 工程师面试题](http://www.codeceo.com/article/android-interview-question.html)

- [不错的博客 排序二叉树和红黑树](http://blog.csdn.net/jackfrued/article/details/10129649)

- [面试感悟----一名3年工作经验的程序员应该具备的技能](http://www.cnblogs.com/xrq730/p/5260294.html)

- [2016Android某公司面试题](https://yuweiguocn.github.io/interview-2016-big-company/)

- [程序员面试之必考题（二）：HTTP的基本原理](http://www.jianshu.com/p/9eeb56a6afb9)

- [2016年魅族Android面试题（试答(上)）](http://www.jianshu.com/p/cd9f97853f54)

- [2016年魅族Android面试题（试答(下)）](http://www.jianshu.com/p/596778ae116b)

- [Android面试题-软键盘适配](http://www.jianshu.com/p/640bac6f58ab)

- [Android阿里面试题锦集](http://www.jianshu.com/p/cf5092fa2694)

- [Android老司机面试经历](http://www.jianshu.com/p/b524e83d15fe)

- [Android面试题集](http://blog.csdn.net/dd864140130/article/details/57408502)

- [Android面试题大集结](http://blog.csdn.net/wdong_love_cl/article/details/51489187)

- [Android面试遇到的问题(1)](http://blog.csdn.net/hmh0512/article/details/55095325)

- [面试题第一波](http://www.easydone.cn/2015/11/25/)

- [最新Android面试题整理 + 各个巨头公司面试题](http://www.apkbus.com/blog-88452-52994.html)

- [一些常见的Android面试基础题做下总结，看看你能做出多少道](https://my.oschina.net/gavinjin/blog/41806)

- [Android面试题收藏](http://www.jianshu.com/p/ddc859a6efe4)

- [Android常见面试题与回答](http://www.myexception.cn/android/1910329.html)

- [Andorid-15k+的面试题](http://blog.csdn.net/cym492224103/article/details/38417927)

- [你知道Thread线程是如何运作的吗？](https://mp.weixin.qq.com/s?__biz=MzIwMzYwMTk1NA==&mid=2247484614&idx=1&sn=5580b6d316846deb1153b4aefdedddb4&chksm=96cda58ba1ba2c9d23838a5f1e4446fd00cb8f2b3db65287fb673d1abed9b473a65e2aaf6c20#rd)

- [Android之View的诞生之谜](https://mp.weixin.qq.com/s?__biz=MzIwMzYwMTk1NA==&mid=2247484804&idx=1&sn=87a6bfaa9823570c1a850cab3a403c00&chksm=96cda4c9a1ba2ddf61d216717bac8bf8d49b590e54b6952d168046a3adf42076404955ec8624&mpshare=1&scene=23&srcid=0606OcoUp1cu0Y0t9ol77cRO#rd)

- [Android View绘制源码分析--Measure](http://rkhcy.github.io/2017/05/24/View%E7%9A%84%E7%BB%98%E5%88%B6-Measure/)

- [浅谈RxJava中的线程管理](http://zjutkz.net/2017/04/26/%E6%B5%85%E8%B0%88RxJava%E4%B8%AD%E7%9A%84%E7%BA%BF%E7%A8%8B%E7%AE%A1%E7%90%86/)

- [深入理解ServiceManager](https://pqpo.me/2017/04/26/learn-servicemanager/)

- [Java 里如何实现线程间通信？](http://wingjay.com/2017/04/09/Java%E9%87%8C%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0%E7%BA%BF%E7%A8%8B%E9%97%B4%E9%80%9A%E4%BF%A1%EF%BC%9F/)

- [深入理解MessageQueue](https://pqpo.me/2017/05/03/learn-messagequeue/)

- [Android性能优化（十）之App瘦身攻略](https://mp.weixin.qq.com/s?__biz=MzI3OTU3OTQ1Mw==&mid=2247483785&idx=1&sn=81fb5a5f57dd119e9b61477db1f5d2a5&chksm=eb44dfdbdc3356cd140a01d4b36df683798442347709eed031ec25daf73d82869474f84e69e2&mpshare=1&scene=23&srcid=05240yGaBTSiJEEcEEzWRpyO#rd)

- [Android性能优化（十一）之正确的异步姿势](https://mp.weixin.qq.com/s?__biz=MzI3OTU3OTQ1Mw==&mid=2247483791&idx=1&sn=a0062d053cc86ebe2c8d8b34fcc3b985&chksm=eb44dfdddc3356cba30b56921577b4d5a63c28d589277634406e688b658e4eaeca01db2bed0c&mpshare=1&scene=23&srcid=0607Zswt0KY7vLEUnpGGGJpb#rd)

- [关于Java并发编程的总结和思考](http://blog.csdn.net/jackfrued/article/details/44499227)

- [一年Android工作经验，一举拿下百度、网易、美团、小米、快手等Offer面经](https://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247485000&idx=1&sn=2d74c597c62c9c4229f79cce9587b6bf&chksm=eae1f31add967a0cddf98dd3bbf529b50420bbf7a9cb6b238e6e6fe993c8bd8ba5cca728e0da#rd)

- [Android客户端面试题集锦](http://www.cnblogs.com/jasonkent27/p/4856209.html)

- [写给小白的android基础面试笔试题（一）](http://www.jianshu.com/p/8650b3878722)

- [写给小白的android基础面试笔试题（二）](http://www.jianshu.com/p/6c38d96f396d)

- [写给小白的android基础面试笔试题（三）](http://www.jianshu.com/p/5573206112d2)

- [2017年小米春招内推面试面经](http://www.jianshu.com/p/d627c900af10)

- [Android launchMode](http://www.jianshu.com/p/72735608cd01)

- [常见面试题算法](http://www.jianshu.com/p/a477589fc4ff)

- [Android Handler的使用方式和注意事项](http://www.jianshu.com/p/e02d68da29b6)

- [Android后台杀死系列之二：ActivityManagerService与App现场恢复机制](http://www.jianshu.com/p/e3612a9b1af3)

- [2017年4月x团面试总结](http://www.jianshu.com/p/ab4d0c6e9481)

- [2016腾讯软件开发面试题(不定项选择题【1-12】)](http://www.jianshu.com/p/dc859753a035)

- [超详细的生命周期图-你能回答全吗](http://www.jianshu.com/p/d586c3406cfb)

- [很全面的算法和数据结构知识（含代码实现）](http://blog.jobbole.com/110835/)

- [教你如何迅速秒杀掉：99%的海量数据处理面试题](http://blog.csdn.net/v_july_v/article/details/7382693)

- [ViewRoot，DecorView，MeasureSpec和View的工作原理](http://blog.csdn.net/l664675249/article/details/50774617)

- [Android中View的事件分发机制](http://blog.csdn.net/l664675249/article/details/50738102)

- [Android中View的滑动冲突](http://blog.csdn.net/l664675249/article/details/50766523)

- [Java 之 volatile 详解](https://juejin.im/post/5956222cf265da6c483cccf1)

- [十个不可忽视的Java基础知识](http://www.jianshu.com/p/dfb0ca0b510d)

- [图解 Android 事件分发机制](http://www.jianshu.com/p/e99b5e8bd67b)

- [Android中Application类的全面总结](http://www.jianshu.com/p/8cf17551da65)

- [更简单的非递归遍历二叉树的方法](http://www.jianshu.com/p/49c8cfd07410)

- [Android自定义View总结](http://www.jianshu.com/p/cb98b15c89dc)

- [3分钟看懂Activity启动流程](http://www.jianshu.com/p/9ecea420eb52)

- [你真的理解AccessibilityService吗](http://www.jianshu.com/p/4cd8c109cdfb)

- [《Android开发艺术探索》——View事件体系](http://www.jianshu.com/p/efcf275a7e00)

- [记一次Android 面试](https://mp.weixin.qq.com/s?__biz=MzIxMTg5NjQyMA==&mid=2247483738&idx=1&sn=accca765d0129d90bc2b14bb3f71adad&chksm=974f1051a038994710d893724cb0db5040cf510250f57e377a036dc9606f65401490b7248b22#rd)

### 提问
- [面试时如何像公司提问？](http://www.mayflyask.org/question/252)

- [面试决定你的不仅仅是技术，而是它](https://mp.weixin.qq.com/s?__biz=MjM5NDkxMTgyNw==&mid=400620337&idx=1&sn=1fa995c1af190cb21479256807aaedb8#wechat_redirect)

### 网站
- [wingjay](http://wingjay.com/)

- [pqpo](https://pqpo.me/)

- [reezy](http://reezy.me/)

- [sparkyuan](http://sparkyuan.me/)

- [yuqirong](http://yuqirong.me/)

- [yydcdut](http://yydcdut.com/)

#### 总结
##### 共同点：
> - 对基础性、原理性的东西比较重视
> - 具体问题的解决能力、项目的架构能力

#### 不同点：
> - 公司不同、产品业务线不同，所以涉及的技术重点和方向不同

#### 思考
> - 有些东西你不仅要懂，而且要能够很好地表达出来，能够让面试官认可你的理解，例如Handler机制，这个是面试必问之题有些晦涩的点，或许它只活在面试当中，实际工作当中你压根不会用到它，但是你要知道它是什么东西

###### 注：持续更新，资源都来自互联网，若有侵权，请联系我删除，整理得有点混乱，多谢包涵。
