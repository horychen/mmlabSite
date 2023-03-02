---
title: Python Basics
date: '2023-03-02'
type: book
weight: 20
---

<!--more-->

{{< icon name="clock" pack="fas" >}} 1-2 hours

## I. Prerequisite

1. Download and install [Anaconda 3](https://www.anaconda.com/) before class.
    - Anaconda 3 is a Python distribution which will be the compiler for our Python codes;
    - We are going to use it to create virtual environment to ensure everybody in this class is on the same page;
    - The version does not matter if we use virtual environment. I installed *Anaconda3-2022.10-Windows-x86_64.exe* for my Windows machine.
2. Download and install [Visual studio code](https://code.visualstudio.com/download) before class.
    - VS code is a popular editor for programming
    - We will use its super-cool jupyter 
    - Alternative editor: [sublime text 4](https://www.sublimetext.com/download)

## II. Oueline

1. Numerical simulation essentials
    - Euler method (ode1)
    - Runge Kutta method (ode4)
    - Learn concept of a variable step size solver
    - Solve for some example systems
2. Numba accelerated simulation
3. Separation between simulation framework and motor dynamics

<!-- 数值积分1阶4阶
可视化洛伦兹系统
numba加速
框架和电机模型分开
 -->




## III. Learn Python in one video by Derek Banas
{{< youtube N4mEzFDjqtA >}}















## IV. Quiz

{{< spoiler text="What is the difference between lists and tuples?" >}}
Lists

- Lists are mutable - they can be changed
- Slower than tuples
- Syntax: `a_list = [1, 2.0, 'Hello world']`

Tuples

- Tuples are immutable - they can't be changed
- Tuples are faster than lists 
- Syntax: `a_tuple = (1, 2.0, 'Hello world')`
{{< /spoiler >}}

{{< spoiler text="Is Python case-sensitive?" >}}
Yes
{{< /spoiler >}}
