---
layout: page
title: Program Analysis
---

## 程序分析

内容主要整理自南京大学计算机学院《软件分析》课程，主讲老师为李樾、谭添。

程序分析主要包括静态分析、动态分析；静态分析就是在程序尚未被执行时对程序进行分析，动态分析则是通过收集程序动态运行时的信息对程序进行分析。

## 静态分析

程序静态分析（Program Static Analysis）是指在不运行代码的方式下，通过词法分析、语法分析、控制流、数据流分析等技术对程序代码进行扫描，验证代码是否满足规范性、安全性、可靠性、可维护性等指标的一种代码分析技术。

### 常用手段
* 词法分析
* 语法分析
* 语义分析
* 抽象语法树分析
* 控制流分析
* 数据流分析
* 污点分析
* 无效代码分析

## 动态分析
包括黑盒测试、白盒测试两种方式。

### 黑盒测试
黑盒测试，它是通过测试来检测每个功能是否都能正常使用。在测试中，把程序看作一个不能打开的黑盒子，在完全不考虑程序内部结构和内部特性的情况下，在程序接口进行测试，它只检查程序功能是否按照需求规格说明书的规定正常使用，程序是否能适当地接收输入数据而产生正确的输出信息。黑盒测试着眼于程序外部结构，不考虑内部逻辑结构，主要针对软件界面和软件功能进行测试。

### 白盒测试
白盒测试又称结构测试、透明盒测试、逻辑驱动测试或基于代码的测试。白盒测试是一种测试用例设计方法，盒子指的是被测试的软件，白盒指的是盒子是可视的，即清楚盒子内部的东西以及里面是如何运作的。"白盒"法全面了解程序内部逻辑结构、对所有逻辑路径进行测试。