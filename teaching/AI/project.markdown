---
layout: post
title: 人工智能课程项目---Pacman
---


### 项目介绍

该项目的基础是一个开源的项目，其用Scala实现了Pacman游戏，你可以用一种特定的简单的语言命令pacman的行为。
项目的要求是这样：
	1. 用现有的特定语言制定pacman的智能行为
	2. 分析代码，定义能够为pacman提升智能的新的行为语言指令
	3. 实现比现有更为复杂的人工智能算法

### 安装步骤

1. 下载并解压[项目源代码(my-Pacman.zip)](my-Pacman.zip)
2. 下载并安装Scala [SBT](http://www.scala-sbt.org/download.html)编译运行工具
3. 下载并解压(基于Eclipse的)[Scala-IDE（开发工具）](http://scala-ide.org/download/sdk.html)
4. 打开Windows PowerShell,并键入在步骤1里解压的项目目录，键入

		> ./activator
		
		（这一步可能需等待库的下载，所下载库都被放入目录：你的用户名/.ivy目录里）
		
5. 然后键入compile 或 run 命令运行Pacman程序
6. 在当前命令行里可以键入eclipse命令，建立eclipse可导入的项目
7. 运行步骤3里下载并解压的Scala-IDE，并导入my-Pacman项目，进行编辑，运行时再重复步骤4和5即可。
