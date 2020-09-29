## 前言
下面的题目都是楼主在Android交流群大家在面试字节跳动时遇到的，如果大家有好的题目或者好的见解欢迎分享，楼主将长期维护此帖。
**参考解析**：郭霖、鸿洋、玉刚、极客时间、腾讯课堂...

**内容特点**：条理清晰，含图像化表示更加易懂。

**内容概要**：包括 Handler、Activity相关、Fragment、service、布局优化、AsyncTask相关
、Android 事件分发机制、 Binder、Android 高级必备 ：AMS,WMS,PMS、Glide、 Android 组件化与插件化等面试题和技术栈！


> 由于文章内容比较多，篇幅不允许，部分未展示内容以截图方式展示 。**如有需要获取完整的资料文档的朋友点击我的[GitHub](https://links.jianshu.com/go?to=https%3A%2F%2Fgithub.com%2FAndroid-Alvin%2FAndroid-P7%2Fblob%2Fmaster%2FAndroid%25E5%25BC%2580%25E5%258F%2591%25E8%25BF%2598%25E4%25B8%258D%25E4%25BC%259A%25E8%25BF%2599%25E4%25BA%259B%25EF%25BC%259F%25E5%25A6%2582%25E4%25BD%2595%25E9%259D%25A2%25E8%25AF%2595%25E6%258B%25BF%25E9%25AB%2598%25E8%2596%25AA%25EF%25BC%2581.md)免费获取。**

**接下来我们针对字节跳动Android中高级面试展开的完整面试题**
![](https://upload-images.jianshu.io/upload_images/23587538-eb7162ce9b26efaf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Handler 相关知识，面试必问！

常问的点：
Handler Looper Message 关系是什么？
Messagequeue 的数据结构是什么？为什么要用这个数据结构？
如何在子线程中创建 Handler?
Handler post 方法原理？
Android消息机制的原理及源码解析
Android Handler 消息机制
![Handler](https://upload-images.jianshu.io/upload_images/23587538-2a7f6c034f944337.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Activity 相关

启动模式以及使用场景?
onNewIntent()和onConfigurationChanged()
onSaveInstanceState()和onRestoreInstanceState()
Activity 到底是如何启动的
启动模式以及使用场景
onSaveInstanceState以及onRestoreInstanceState使用
onConfigurationChanged使用以及问题解决
Activity 启动流程解析
![Activity相关](https://upload-images.jianshu.io/upload_images/23587538-b607aef4db50cd37.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Fragment
Fragment 生命周期和 Activity 对比
Fragment 之间如何进行通信
Fragment的startActivityForResult
Fragment重叠问题
Fragment 初探
Fragment 重叠， 如何通信
Fragment生命周期
![Fragment相关](https://upload-images.jianshu.io/upload_images/23587538-1f83642719a5653d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Service 相关
进程保活
Service的运行线程（生命周期方法全部在主线程）
Service启动方式以及如何停止
ServiceConnection里面的回调方法运行在哪个线程？
startService 和 bingService区别
进程保活一般套路
关于进程保活你需要知道的一切
![Service 相关](https://upload-images.jianshu.io/upload_images/23587538-7ddb79cf9862d35e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android布局优化之ViewStub、include、merge
什么情况下使用 ViewStub、include、merge？
他们的原理是什么？
ViewStub、include、merge概念解析
Android布局优化之ViewStub、include、merge使用与源码分析
![Android布局优化](https://upload-images.jianshu.io/upload_images/23587538-d6f4ee78eb724cb1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## BroadcastReceiver 相关

注册方式，优先级
广播类型，区别
广播的使用场景，原理
Android广播动态静态注册
常见使用以及流程解析
广播源码解析
![ BroadcastReceiver相关](https://upload-images.jianshu.io/upload_images/23587538-3d3ca179d49e8501.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## AsyncTask相关

AsyncTask是串行还是并行执行？
AsyncTask随着安卓版本的变迁
AsyncTask完全解析
串行还是并行
![AsyncTask相关](https://upload-images.jianshu.io/upload_images/23587538-8a10b7c751ed2b9b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 事件分发机制
onTouch和onTouchEvent区别，调用顺序
dispatchTouchEvent， onTouchEvent， onInterceptTouchEvent 方法顺序以及使用场景
滑动冲突，如何解决
事件分发机制
事件分发解析
dispatchTouchEvent， onTouchEvent， onInterceptTouchEvent方法的使用场景解析
![](https://upload-images.jianshu.io/upload_images/23587538-3debb0333c542693.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android View 绘制流程

简述 View 绘制流程
onMeasure， onlayout， ondraw方法中需要注意的点
如何进行自定义 View
view 重绘机制

* Android LayoutInflater原理分析，带你一步步深入了解View(一)
* Android视图状态及重绘流程分析，带你一步步深入了解View(二)
* Android视图状态及重绘流程分析，带你一步步深入了解View(三)
* Android自定义View的实现方法，带你一步步深入了解View(四)
![Android View 绘制流程](https://upload-images.jianshu.io/upload_images/23587538-2d1ed33c05cfedc6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## Android Window、Activity、DecorView以及ViewRoot

Window、Activity、DecorView以及ViewRoot之间的关系
![Android Window](https://upload-images.jianshu.io/upload_images/23587538-40baaea08208b764.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 的核心 Binder 多进程 AIDL

常见的 IPC 机制以及使用场景
为什么安卓要用 binder 进行跨进程传输
多进程带来的问题

* AIDL 使用浅析
* binder 原理解析
* binder 最底层解析
* 多进程通信方式以及带来的问题
* 多进程通信方式对比
![Binder 相关](https://upload-images.jianshu.io/upload_images/23587538-991771fb8e448ec9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 高级必备 ：AMS,WMS,PMS

AMS,WMS,PMS 创建过程

* AMS,WMS,PMS全解析
* AMS启动流程
* WindowManagerService启动过程解析
* PMS 启动流程解析
![](https://upload-images.jianshu.io/upload_images/23587538-051584078344f7ab.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android ANR

为什么会发生 ANR？
如何定位 ANR？
如何避免 ANR？
什么是 ANR
如何避免以及分析方法
Android 性能优化之 ANR 详解
![Android ANR](https://upload-images.jianshu.io/upload_images/23587538-f7444b1843fcc861.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 内存相关

**注意：内存泄漏和内存溢出是 2 个概念**

什么情况下会内存泄漏？
如何防止内存泄漏？

* 内存泄漏和溢出的区别
* OOM 概念以及安卓内存管理机制
* 内存泄漏的可能性
* 防止内存泄漏的方法
![Android 内存相关](https://upload-images.jianshu.io/upload_images/23587538-9364fa7976091393.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 屏幕适配

屏幕适配相关名词解析
现在流行的屏幕适配方式

* 屏幕适配名词以及概念解析
* 今日头条技术适配方案
![Android 屏幕适配](https://upload-images.jianshu.io/upload_images/23587538-d4ca52adf9b16eca.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 缓存机制

LruCache使用极其原理

* Android缓存机制
* LruCache使用极其原理述
![Android 缓存机制](https://upload-images.jianshu.io/upload_images/23587538-053aee6fc1507ce1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 性能优化

如何进行 内存 cpu 耗电 的定位以及优化
性能优化经常使用的方法
如何避免 UI 卡顿

* 性能优化全解析，工具使用
* 性能优化最佳实践
* 知乎高赞文章
![ Android 性能优化](https://upload-images.jianshu.io/upload_images/23587538-177527762b84b15c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## Android MVC、MVP、MVVM

好几种我该选择哪个？优劣点

任玉刚的文章：设计模式选择
![Android MVC、MVP、MVVM](https://upload-images.jianshu.io/upload_images/23587538-008b356352212d46.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android Gradle 知识

这俩篇官方文章基础的够用了
[必须贴一下官方文档：配置构建](https://developer.android.com/studio/build?hl=zh-cn)
[Gradle 提示与诀窍](https://developer.android.com/studio/build/gradle-tips?hl=zh-cn)

Gradle插件 了解就好
Gradle 自定义插件方式
全面理解Gradle - 执行时序
* Gradle系列一
* Gradle系列二
* Gradle系列三
![Android Gradle 知识](https://upload-images.jianshu.io/upload_images/23587538-33700ce089536145.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## RxJava

使用过程，特点，原理解析
RxJava 名词以及如何使用
Rxjava 观察者模式原理解析
Rxjava订阅流程，线程切换，源码分析 系列
![ RxJava相关](https://upload-images.jianshu.io/upload_images/23587538-d9b14dde8f2f34dd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## OKHTTP 和 Retrofit

OKHTTP完整解析
Retrofit使用流程，机制详解
从 HTTP 到 Retrofit
Retrofit是如何工作的
![OKHTTP 和 Retrofit](https://upload-images.jianshu.io/upload_images/23587538-4692e07e1a1aedb1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 最流行图片加载库： Glide

**郭神系列 Glide 分析**
Android图片加载框架最全解析（一），Glide的基本用法
Android图片加载框架最全解析（二），从源码的角度理解Glide的执行流程
Android图片加载框架最全解析（三），深入探究Glide的缓存机制
Android图片加载框架最全解析（四），玩转Glide的回调与监听
Android图片加载框架最全解析（五），Glide强大的图片变换功能
Android图片加载框架最全解析（六），探究Glide的自定义模块功能
Android图片加载框架最全解析（七），实现带进度的Glide图片加载功能
Android图片加载框架最全解析（八），带你全面了解Glide 4的用法
![ Glide相关](https://upload-images.jianshu.io/upload_images/23587538-f4fdddcc22f144b6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Android 组件化与插件化

为什么要用组件化？
组件之间如何通信？
组件之间如何跳转？
Android 插件化和热修复知识梳理
为什么要用组件化
* Android彻底组件化方案实践
* Android彻底组件化demo发布
* Android彻底组件化-代码和资源隔离
* Android彻底组件化—UI跳转升级改造
* Android彻底组件化—如何使用Arouter

插件化框架历史
深入理解Android插件化技术
Android 插件化和热修复知识梳理

![Android 组件化与插件化](https://upload-images.jianshu.io/upload_images/23587538-bd6e69f53f5012b9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


网上高级工程师面试相关文章鱼龙混杂，要么一堆内容，要么内容质量太浅， 鉴于此我整理了上述安卓开发高级工程师面试题以及答案帮助大家顺利进阶为高级工程师，目前我就职于某大厂安卓高级工程师职位，在当下大环境下也想为安卓工程师出一份力，通过我的技术经验整理了面试经常问的题，答案部分会是一篇文章或者几篇文章，都是我认真看过并且觉得不错才整理出来，大家知道高级工程师不会像刚入门那样被问的问题一句话两句话就能表述清楚，所以我通过过滤好文章来帮助大家理解.

> 由于文章内容比较多，篇幅不允许，部分未展示内容以截图方式展示 。**如有需要获取完整的资料文档的朋友点击我的[GitHub](https://links.jianshu.com/go?to=https%3A%2F%2Fgithub.com%2FAndroid-Alvin%2FAndroid-P7%2Fblob%2Fmaster%2FAndroid%25E5%25BC%2580%25E5%258F%2591%25E8%25BF%2598%25E4%25B8%258D%25E4%25BC%259A%25E8%25BF%2599%25E4%25BA%259B%25EF%25BC%259F%25E5%25A6%2582%25E4%25BD%2595%25E9%259D%25A2%25E8%25AF%2595%25E6%258B%25BF%25E9%25AB%2598%25E8%2596%25AA%25EF%25BC%2581.md)免费获取。**
