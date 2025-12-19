---
title: 关于编译出现缺少Arm Compiler 5编译链的解决方法
published: 2025-12-19
pinned: true
description: 关于编译出现缺少AC5编译链的解决方法。
tags: [嵌入式, C51, STM32]
category: 嵌入式
licenseName: "CC BY-SA 4.0"
author: CaspianCKY
draft: false
date: 2025-12-19
image: "./image/cover.jpg"
pubDate: 2025-12-19
---

- [1. 现象](#1-现象)
- [2. 原因](#2-原因)
- [3. 解决方法](#3-解决方法)

## 1. 现象

在编译过程中，出现缺少编译链的错误提示，如:`Default Compiler Version 5‘ which is not available`导致编译失败。

## 2. 原因

此链接中官方提到Arm Compiler 5编译链已结束支持，**MDKv5.37及以上**版本不再提供AC5编译链。
[https://developer.arm.com/documentation/ka005073/latest/](https://developer.arm.com/documentation/ka005073/latest/)
![结束支持](./image/image1.png)

## 3. 解决方法

我的另一篇博客中，有详细介绍如何安装AC5编译链。
[关于新版MDK缺少ArmCompiler5（AC5）编译链的问题](https://caspiancky.de5.net/posts/keil5-安装教程/#八关于新版mdk缺少arm-compiler5ac5编译链的问题)
