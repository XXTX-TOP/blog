---
title: [经验分享] 利用github actions自动编译内核
date: 2022-11-20 21:02:01
updated: 2022-11-20 21:02:01
tags: 
- 日记
- 生活
- 短篇
categories: 
- 经验分享
- 内核
---
# 利用github actions自动编译内核 

[XXTX-TOP/Linux-kernel_deb_builder (github.com)](https://github.com/XXTX-TOP/Linux-kernel_deb_builder)

这个是我在：[debuggerx01/kernel_deb_builder](https://github.com/debuggerx01/kernel_deb_builder) 的基础上进行修改得来的，可以自助编译Linux内核。

![image.png](https://storage.deepin.org/thread/202306032341516551_image.png)

省去了拿自己的电脑慢慢编译的过程，同时可以及时的发布新的内核deb包，我觉得还不错，分享一下。具体的实现看项目的README.md

需要其他版本的内核只需要修改下载处的数字和config即可。