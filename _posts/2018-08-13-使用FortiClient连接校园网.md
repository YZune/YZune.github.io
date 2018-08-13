---
layout:     post
title:      使用FortiClient连接校园网
subtitle:   WakeUp课程表中关于校园网连接的方法会跳转到这里
date:       2018-08-13
author:     YZune
header-img: img/post-bg-coffee.jpeg
catalog: true
tags:
    - 教程
---

# 前言

目前如果不连接苏大WiFi，WakeUp课程表只能借助这个App访问到学校的教务系统。但其实也有其他解决方案，在这里先感谢王子恒，他将帮我构建一个接口，实现不连苏大WiFi也能直接获取课表。相信这个功能将出现在下个更新版本。

# 下载FortiClient

Android上可以使用FortiClient连接至苏大校园网

下载地址1：[https://fir.im/SudaFortiClient](https://fir.im/SudaFortiClient)

下载地址2：[https://pan.baidu.com/s/1Kh4U3VLbhh7dakV-_jHMNQ](https://pan.baidu.com/s/1Kh4U3VLbhh7dakV-_jHMNQ)

下载好后安装

# 配置FortiClient

安装好后打开，会提示授予权限，授予后弹出新界面，按以下截图填写和选择。

![](https://ws3.sinaimg.cn/large/0069RVTdgy1fu7xy3wvcsj30u01hcwhn.jpg)

点击“创建”，跳转到新页面，需要手动修改的就两个地方，一个是**服务器**，一个是**用户名**。**服务器**填https://vpn.suda.edu.cn，注意输入的都是英文符号。**用户名**填**你的学号**。填好如下图所示，再提醒一遍，**用户名填的是你的学号！**

![](https://ws2.sinaimg.cn/large/0069RVTdgy1fu7y2ohtcvj30u01hc43g.jpg)

然后点左上角的返回，点击下方的“连接”按钮，会弹出窗口提示输入密码，密码应该是你登录苏大WiFi的密码，或者说是你统一身份认证的密码。登录成功后，*原来的登录按钮会变成断开按钮*。使用完毕后记得断开连接哦。