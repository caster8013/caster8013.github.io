---
layout: post
title: "怎样在Windows系统上安装v2ray客户端？"
tags: [ v2ray , windows, chrome, 安装教程 ]
comments: true
---

> V2ray是一个代理软件，它代表本地同服务器端通信。只安装代理软件并不能实施蕃茄，其它程序（比如google chrome,IE,firefox,telegram等）借助代理软件才能实现蕃茄。这里需要被代理的软件是chrome浏览器。我们选择chrome浏览器用来番茄，是因为它的插件扩展功能可以非常好地管理本地代理。为了避免安装完V2Ray之后，不知道如何蕃茄，以下会先介绍如何安装chrome，以及如何安装swithyomega插件、导入配置文件。如果你已经知道chrome蕃茄的原理，可以跳过前面部分，直接进入安装新客户端软件的部分。

### Step 1：安装chrome浏览器

下载chrome浏览器文件，安装之后运行。

### Step 2：安装swithyomega插件

1. 分别下载 [**swithyomega插件**][2] 和 [**插件配置文件**][3] 。

2. 浏览器中依次打开"窗口"->"扩展程序"，右上角打开"开发模式"，把以`.crx`结尾的文件托入"扩展程序"窗口中完成安装。

3. 如果插件安装成功，swithyomega会出现在"扩展程序"的列表中。依次选择"选项"->"导入/导出"->"从备份文件恢复"，从弹出窗口中选择以`.bak`结尾的配置文件导入。左边栏中，点击“保存(Apply changes)”。

4. 点击浏览器地址栏右边的swithyomega圆形按钮，选择“自动切换（Auto switch）”。

### Step 3：安装V2Ray客户端

- 如果你的系统是64位: [`V2RayW-windows-64.zip`][4]

解压下载的文件，点击运行文件夹中的`V2RayW.exe`。windows下方任务栏中会出现W形状的绿色图标，说明v2ray客户端已打开运行。

<hr>

- 32位系统: [`v2ray-v3.24-windows-32.zip`][5]

文件解压之后是一个文件夹，里面的文件已经配置好。把这个文件夹Copy到电脑里一个安全的地方，以后会经常运行。

下面的选项A和选项 B, 二选一即可 

1. 选项A: `v2ray`打开运行之后，会出现一个命令行界面，只要它不关闭，`v2ray`客户端就在运行。

2. 选项B: `wv2ray`打开运行之后，什么都看不到，因为它以后台程序的方式运行，可以在后台服务程序中找到`wv2ray`的进程。

<hr>
如果上面都没有问题，此时chrome浏览器已经可以蕃茄了。测试过程为，先打开百度，查看联网是否正常；再打开google，查看能否正常显示。

[1]:<http://w8.undervineyard.com/>
[2]:<http://w8.undervineyard.com/SwitchyOmega.crx>
[3]:<http://w8.undervineyard.com/OmegaOptions.2018.2.1.bak>
[4]:<https://w8.undervineyard.com/V2RayW-windows-64.zip>
[5]:<http://w8.undervineyard.com/v2ray-v3.24-windows-32.zip>