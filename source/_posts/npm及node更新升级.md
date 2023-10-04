---
title: npm及node更新升级
date: 2023-10-04 22:37:47
updated: 2023-10-04 22:37:47
tags: 编程
categories:
---

1. 查看 **npm** 当前版本 **npm** -v.
2. 清理 **npm** 缓存数据 **npm** cache clean --force.
3. 更新到最新版本 **npm** install -g **npm**.
4. 首先：查看当前**node** 版本：**node** –v.
5. 安装n 模块：**npm** install -g n.

安装最近的稳定版本

> n stable 

安装完成之后，用 node –v 查看，还是老版本，安装未生效。 

![1696430392231](C:\Users\XXTXT\Desktop\github\blog\source\_posts\npm及node更新升级.assets\1696430392231.png)

我用的是zsh，所以执行hash -r。