---
layout: post
title: "删除系统盘hiberfil.sys"
date: 2024-04-15 12:01:00 -0000
categories: windows10
---
“hiberfil.sys”是系统休眠文件，其大小和物理内存一样大，它可以删除掉，但却不能手动删除掉，只要在“控制面板”中打开“电源选项”，之后在电源管理对话框的“休眠”标签下，去掉“启用休眠”前的勾，重新启动计算机后，休眠文件就会自动删除。

在命令提示符中输入：powercfg -hibernate off 按回车（Enter键）执行命令即可关闭休眠功能。

如要再次开启休眠功能，可以在命令提示符中输入：powercfg -hibernate on 按回车（Enter键）执行命令即可打开休眠功能（无需重启电脑）。