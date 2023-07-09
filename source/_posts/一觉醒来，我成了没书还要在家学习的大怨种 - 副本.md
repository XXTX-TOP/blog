---
title: [经验分享] 记录一下linux内核的编译
date: 2022-11-20 21:02:01
updated: 2022-11-20 21:02:01
tags: 
- 日记
- 生活
- 短篇
categories: 
- 经验分享
---
# 记录一下linux内核的编译
<https://www.kernel.org/>

## 首先去内核官方下内核包

#### 1、安装需要的软件包

sudo apt-get install git fakeroot build-essential ncurses-dev xz-utils libssl-dev bc flex libelf-dev bison

#### 2、拷贝启动目录到源代码目录

cp -v /boot/config-$(uname -r) .config

#### 3、配置命令启动配置界面

make menuconfig

#### 4、开始编译

make -j 10 （核心数量）

#### 5、安装模块

sudo make modules_install

#### 6、安装内核

sudo make install

#### 7、查看所有的内核

dpkg --get-selections | grep linux

#### 8、删除不需要的内核

sudo apt-get purge XXX

#### 9、更新引导

sudo update-grub