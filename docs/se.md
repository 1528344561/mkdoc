# Software Engineering

## 软件的概念

软件是在计算机系统的支持下，完成特定功能与性能的程序、数据和相关文档 (并不只是简单的一系列语句)

## 程序的质量

程序的外在质量:流畅 速度 简易 美观 可靠

程序的内在质量:理解 结构 修改 重用 维护

### 程序质量的保证方法

遵循编码规范

采用程序设计方法

进行代码重用

采用结对编程

### 程序质量的分析方法

人工审查方法

自动化分析方法

程序测试方法

## 软件需求

### 何为软件需求?

软件本身:用于解决问题所表现的功能和性能等方面的要求

利益方对软件的功能,质量,运行环境,交付进度等方面的要求

软件需求刻画了软件系统能做什么（What to do），应表现出怎样的行为，需满足哪些方面的条件和约束等要求

### 软件需求包含哪些形式类别?

功能性

质量方面 外部质量 内部质量

约束性 (成本 进度 技术选型 遵循标准)

### 软件需求的质量要求

价值 正确 完整 可行 一致 追踪 验证 无二义

## 软件的生命周期

软件从提出开发开始到最终灭亡所经历的时期

阶段:需求分析，软件设计，编码，测试，运行，维护

## 软件工程

### 什么是软件工程

将系统的、规范的、可量化的方法应用于软件的开发、运行和维护的过程；以及上述方法的研究

系统化：提供完整和全面的解决方法，包括目标、原则、过程模型、开发活动、开发方法和技术等

规范化：支持各类软件系统的开发，包括语言标准、质量标准、编程标准、方法标准、能力极其改进标准等

可量化：工作量、成本、进度、质量等要素可以量化

三要素:过程 方法学 工具

### 软件工程的目标

在成本、进度等约束下，指导软件开发和运维，开发出满足用户要求的足够好软件

## 测试等价类

### 等价分类法

输入条件若是范围或一个值

划分三个等价类:在这个范围内(若是值,就做一个集合),大于这个范围,小于这个范围

输入条件是一个集合:划分成在集合和不在集合内

### 边界值分析法

输入条件是一范围(a,b):a,b以及紧挨a,b左右的值应作为测试用例

输入条件为一组数:选择这组数最大者和最小者，次大和次小者作为测试用例
