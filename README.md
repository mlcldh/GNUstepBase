# GNUstepBase
[GNUstep](https://mlcldh.github.io/iOS/GNUstep)是GNU计划的项目之一，它将Cocoa的OC库重新开源实现了一遍。

官网源码地址：[http://www.gnustep.org/resources/downloads.php](http://www.gnustep.org/resources/downloads.php)

官网代码下载地址：http://ftpmain.gnustep.org/pub/gnustep/core/gnustep-base-1.28.0.tar.gz

GitHub代码地址：[https://github.com/gnustep/libs-base](https://github.com/gnustep/libs-base)

虽然GNUstep不是苹果官方源码，但还是具有一定的参考价值。

我们可以下载【GNUstep Base】，下载完成后打开目录Source-->Foundation 这里有许多Foundation的其它类，比如：NSArray，我们可以点击进去，查看到我们经常使用的方法及实现。

苹果[objc4](https://opensource.apple.com/tarballs/objc4/)公开的Foundation框架中只有NSObject的实现。假如我们想要查看NSString，NSArray，NSRunLoop，NSThread等Foundation这些类，是没有源码的。虽然通过汇编语言，一步步的跟踪也可以查看。但是汇编太过于晦涩难懂，所以这里推荐查看GNUstep里对Foundation的实现。


