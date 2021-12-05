---
layout: page
title: BTE4ElPh
description: 计算周期性体系中受电子声子（el-ph）耦合限制的电输运性质
img: assets/img/bte4elph.png
importance: 1
category: works
---

BTE4ElPh 使用玻尔兹曼输运方程（BTE）来计算周期性体系中受电子声子（el-ph）耦合限制的电输运性质。软件通过密度泛函理论方法，Wannier 插值算法和迭代方法不依赖任何经验参数精确求解 BTE，同时还提供弛豫时间近似（RTA）和动量弛豫时间近似（MRTA）求解。当前的功能包括电子传导率，迁移率，塞贝克系数和电子导热率的计算。除此之外，还可以获得一些有用的相关性质，包括 el-ph 散射率（电子寿命的倒数），平均自由程，声子-电子散射强度，Eliashberg 光谱函数及其在金属体系中的输运变量。

目前，BTE4ElPh 与含有 EPW 模块的 Quantum ESPRESSO（QE）软件包接口，源代码可以通过在 Linux 中运行 make 命令来被编译。如果编译成功，则会创建一个 BTE4ElPh 二进制文件。要运行 BTE4ElPh，首先需要一些在 QE 中执行计算得到的数据文件作为输入，然后需要一个 CONTROL 文件来调控求解 BTE 过程的参数。
