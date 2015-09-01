# Fresco 

Fresco is a powerful system for displaying images in Android applications.

Fresco takes care of image loading and display, so you don't have to. It will load images from the network, local storage, or local resources, and display a placeholder until the image has arrived. It has two levels of cache; one in memory and another in internal storage.

In Android 4.x and lower, Fresco puts images in a special region of Android memory. This lets your application run faster - and suffer the dreaded `OutOfMemoryError` much less often.

Fresco also supports:

* streaming of progressive JPEGs
* display of animated GIFs and WebPs
* extensive customization of image loading and display
* and much more!

Find out more at our [website](http://frescolib.org/index.html).

## Requirements

Fresco can be included in any Android application. 

Fresco supports Android 2.3 (Gingerbread) and later. 

## Using Fresco in your application

If you are building with Gradle, simply add the following line to the `dependencies` section of your `build.gradle` file:

```groovy
compile 'com.facebook.fresco:fresco:0.7.0+'
```

For full details, visit the documentation on our web site, available in English, Chinese, and Korean:

<a href="http://frescolib.org/docs/index.html"><img src="http://frescolib.org/static/GetStarted-en.png" width="150" height="42"/></a>

<a href="http://fresco-cn.org/docs/index.html"><img src="http://frescolib.org/static/GetStarted-zh.png" width="104" height="42"/></a>

<a href="http://fresco.recrack.com/docs/index.html"><img src="http://frescolib.org/static/GetStarted-ko.png" width="104" height="42"/></a>

## Join the Fresco community

Please use our [issues page](https://github.com/facebook/fresco/issues) to let us know of any problems.

For pull requests, please see the [CONTRIBUTING](https://github.com/facebook/fresco/blob/master/CONTRIBUTING.md) file for information on how to help out. See our [documentation](http://frescolib.org/docs/building-from-source.html) for information how to build from source.


## License
Fresco is [BSD-licensed](https://github.com/facebook/fresco/blob/master/LICENSE). We also provide an additional [patent grant](https://github.com/facebook/fresco/blob/master/PATENTS).




<--------------------------------------------------------------------------------------------------
Fresco 是一个强大的图片加载组件。

Fresco 中设计有一个叫做 image pipeline 的模块。它负责从网络，从本地文件系统，本地资源加载图片。为了最大限度节省空间和CPU时间，它含有3级缓存设计（2级内存，1级文件）。

Fresco 中设计有一个叫做 Drawees 模块，方便地显示loading图，当图片不再显示在屏幕上时，及时地释放内存和空间占用。

Fresco 支持 Android2.3(API level 9) 及其以上系统。
