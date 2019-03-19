---
layout: post
title: "如何在Android系统上安装V2ray客户端？"
tags: [ v2ray , android, 安装教程 ]
comments: true
---

> Android系统内的V2ray客户端是一个叫作`v2rayNG`的App。它的配置参数不是填写几行字符，而是导入一个有很多参数的配置文件。

### 一、安装 v2rayNG

在手机浏览器中打开本页面，点击 [android-v2rayNG-v0.6.4-universal.apk][1]，下载安装文件。下载成功之后安装。

### 二、导入配置文件

#### **方法一：**同样在手机浏览器中打开本页面，复制下面的URL:

```
http://w8.undervineyard.com/v2ray-clientside-WS-TLS-Nginx.json
```

打开v2rayNG软件，点触右上角 `+` ，选择`从URL导入自定义配置`。

#### **方法二：**点击 [v2ray-clientside-WS-TLS-Nginx][2] ,下载配置文件。

打开 v2rayNG 软件，点触右上角`+`，选择`从本地导入自定义配置`。然后，选择上面下载的配置文件导入。

### 三、运行App

如果配置文件导入成功，主界面列表里会有新的列表项。选中新增加的列表项，点触右下小飞机形状的开关，运行App。

如果一切顺利，只要`v2rayNG`在运行，其它程序打开之后都可以蕃茄。如果你运行的程序（如微信、支付宝、网易云音乐、美团等国内App）不需要蕃茄，请关闭App，为我们的服务器节省流量。

### Android系统中v2ray客户端安装结束！


[1]:<https://w8.undervineyard.com/android-v2rayNG-v0.6.4-universal.apk>
[2]:<http://w8.undervineyard.com/v2ray-clientside-WS-TLS-Nginx>