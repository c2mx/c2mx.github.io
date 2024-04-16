---
layout: post
title: Win10远程桌面出现身份验证错误
date: 2024-04-14 12:00:00
categories: windows10
---
Win10远程桌面连接Window Server时报错信息如下：

出现身份验证错误，要求的函数不正确，这可能是由于CredSSP加密Oracle修正。

解决方法：

运行 gpedit.msc

本地组策略：

计算机配置>管理模板>系统>凭据分配>加密Oracle修正

选择启用并选择易受攻击。