---
layout: post
title: "怎样在MacOS上安装V2ray客户端？"
tags: [ v2ray , mac OS X, 安装教程 ]
comments: true
---

> 在苹果系统上，既可以选择`Chrome+v2ray`组合，也可以选择`safari+v2ray`组合。前者需要安装google chrome浏览器（还有swithyomega插件和配置文件）,参考[这里][1]。后者safari浏览器是系统自带，v2ray客户端可以接管系统代理，所以只需要安装v2ray即可。

> 另外提醒，macOS版的SSR与macOS版的v2ray都通过SOCKS5协议与浏览器通信，同样的本地代理端口会因为端口冲突让两个软件都不能工作。建议只运行v2ray一个软件。

### 一、安装V2ray客户端

点击[这里][2],下载解压之后安装。

从启动程序中找到V2RayX，打开程序。桌面最上方标题栏中出现钻石形状的程序图标，说明v2ray已运行。

### 二、填入配置参数

在无墙计划群，或者私信给我以下内容，我会把配置参数发给你。

```
macos+config
```


依次点击图标，选择"Configure..."，填入参数。

### 三、选择v2ray运行模式

点击程序图标，选中`start v2ray`。

再次点击程序图标，选中`V2Ray Rules`。

如果一切顺利，此时浏览器已经可以番茄。测试方法为，先打开百度，查看网络是否正常；再打开google，查看页面是否正常加载。如果遇到意外，请拍照发在群里，或私信给我。

### v2ray客户端安装结束！

<!-- [1]:<https://undervineyard.tk/2018/02/01/V2ray-Client-For-Windows.html> -->
[1]:<{{ site.baseurl }}{% post_url 2018-2-1-V2ray-Client-For-Windows %}>
[2]:<http://w8.undervineyard.com/V2RayX-v0.9.1-MacOS.zip>