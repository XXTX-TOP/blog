---
title: [经验分享] Linux内核6.4.0-rc4分享【测试版内核，慎重更新！】
date: 2022-11-20 21:02:01
updated: 2022-11-20 21:02:01
tags: 
- 日记
- 生活
- 短篇
categories: 
- 经验分享
---
# Linux内核6.4.0-rc4分享【测试版内核，慎重更新！】 

目前在UOS专业版上使用6.4.0-rc4内核，因为笔记本是12代intel，所以UOS自带的内核不支持，随即分享出来。

在其他机器提前编译好6.4.0-rc4内核。

安装内核的过程是在安装系统后（此时无法正常进入系统，）通过grub界面进入live，然后chroot后获取已安装系统的root权限并设置密码，然后重启进入tty2，进入root账户，插入U盘并进行挂载，然后安装编译好的内核即可。

------

内核分享（**测试版内核，慎重更新！**）：

链接: <https://pan.baidu.com/s/1aVeuHWYu2MiiTC71p3_-eQ?pwd=7g39> 提取码: 7g39
--来自百度网盘超级会员v5的分享

![截图_deepin-terminal_20230601002454.png](https://storage.deepin.org/thread/20230602182523507_%E6%88%AA%E5%9B%BE_deepin-terminal_20230601002454.png)

![截图_选择区域_20230601063626.png](https://storage.deepin.org/thread/202306021826397451_%E6%88%AA%E5%9B%BE_%E9%80%89%E6%8B%A9%E5%8C%BA%E5%9F%9F_20230601063626.png)