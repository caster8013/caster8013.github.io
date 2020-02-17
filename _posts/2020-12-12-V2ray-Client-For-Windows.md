---
layout: post
title: "如何Windows系统安装v2ray？"
tags: [ v2ray , windows, chrome, 安装教程 ]
comments: true
---

> V2ray是一个代理软件，它代表本地同服务器端通信。只安装代理软件并不能实施蕃茄，其它程序（比如google chrome,IE,firefox,telegram等）借助代理软件才能实现蕃茄。这里需要被代理的软件是chrome浏览器。

### Step 1：安装chrome浏览器

下载chrome浏览器文件，安装之后运行。

### Step 2：安装swithyomega插件

1. 分别下载 [**swithyomega插件**][2] 和 [**插件配置文件**][3] 。

2. 浏览器依次打开"窗口"->"扩展程序"，右上角打开"开发模式"，把以`.crx`结尾的文件托入"扩展程序"窗口安装switchomega插件。

3. 如果插件安装成功，swithyomega会出现在"扩展程序"的列表中。依次选择"选项"->"导入/导出"->"从备份文件恢复"，从弹出窗口中选择以`.bak`结尾的配置文件导入。左边栏中，点击“保存(Apply changes)”。

4. 点击浏览器地址栏右边的swithyomega圆形按钮，选择“自动切换（Auto switch）”。

### Step 3：安装V2Ray客户端

请私信给我，会发给你v2ray客户端的下载链接。

下载之后解压，文件夹中有5个文件，已经包括新的配置参数。你会希望把文件夹移动到合适的地方，以后你会经常打开它。v2ray.exe打开之后，以命令行的形式运行，只要这个黑色窗口没有关闭，程序就在运行。wv2ray.exe以后台程序的形式运行，打开之后不会看到任何界面，在“任务管理器”的任务标签中可以找到它。两种方式，选择哪一种方式都可以。

此时，浏览器已经可以蕃茄。测试过程为，先打开百度，查看联网是否正常；再打开google，查看能否正常显示。

[2]:<http://w8.undervineyard.com/SwitchyOmega.crx>
[3]:<https://w8.undervineyard.com/OmegaOptions.20200217.bak>