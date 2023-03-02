---
title: C1. Python Basics
date: '2023-03-02'
type: book
weight: 20
---

<!--more-->

{{< icon name="clock" pack="fas" >}} 15 min

## C1.1. Prerequisite

1. Download and install [Anaconda 3](https://www.anaconda.com/) before class.
    - Anaconda 3 is a Python distribution which will be the compiler for our Python codes;
    - We are going to use it to create virtual environment to ensure everybody in this class is on the same page;
    - The version does not matter if we use virtual environment. I installed *Anaconda3-2022.10-Windows-x86_64.exe* for my Windows machine.
    - For Windows PCs, you can set up a virtual environment following these steps:
        - Open anaconda prompt, or alternatively, you can add anaconda to system path (the Windows environment variable).
            ```
            D:\Programs\anaconda3
            D:\Programs\anaconda3\Scripts
            D:\Programs\anaconda3\Library\bin
            ```
            After doing this, you can call python.exe and pip.exe in your command prompt (cmd.exe)
        - Create a virtual environment python 3.10 under the name "main":
            - `conda create -n main python=3.10`
            - Type `y` to confirm downloading the packages and wait.
        - Activate it
            - `conda activate main`
        - Now, if you run command `pip install`, the packages will be installed for this virtual environment
            - `pip install matplotlib pandas numba control dearpygui`
        - Open file explorer.exe at current directory
            - `explorer.exe .`
        - Create a file named `my_dearpygui_demo.py` and paste the following codes and save
            ```python
            import dearpygui.dearpygui as dpg
            import dearpygui.demo as demo
            dpg.create_context()
            dpg.create_viewport(title='Custom Title', width=600, height=600)
            demo.show_demo()
            dpg.setup_dearpygui()
            dpg.show_viewport()
            dpg.start_dearpygui()
            dpg.destroy_context()
            ```
        - Run python codes
            - `python my_dearpygui_demo.py`
            - Have fun!
    - You can check existing virtual environment by typing: `conda env list`
2. Download and install [Visual Studio Code](https://code.visualstudio.com/download) before class.
    - VS code is a popular editor for programming
    - We will use its super-cool jupyter 
    - Alternative editor: [sublime text 4](https://www.sublimetext.com/download)

## C1.2. Outline

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




## C1.3. Learn Python in one video by Derek Banas (need access to Youtube)
{{< youtube N4mEzFDjqtA >}}















## C1.4. Quiz

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
