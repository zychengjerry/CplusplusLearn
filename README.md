# Cplusplus Learn
Learning C++

## Introduction

**编译器**

计算机只能理解一种语言，而这种语言由一组由 1 和 0 组成的指令组成。这种计算机语言被恰当地称为机器语言。

对计算机的一条指令可能如下所示：

    00000	10011110

允许用户输入两个数字、将两个数字相加并显示总数的特定计算机的机器语言程序可能包括以下机器代码指令：

    00000	10011110
    00001	11110100
    00010	10011110
    00011	11010100
    00100	10111111
    00101	00000000

您可以想象，仅使用 1 和 0 直接用机器语言对计算机进行编程非常繁琐且容易出错。为了使编程更容易，已经开发了高级语言。高级程序还使程序员更容易检查和理解彼此的程序。

这是用 C++ 编写的代码的一部分，用于实现完全相同的目的：

    int a, b, sum;

    cin >> a;
    cin >> b;

    sum = a + b;
    cout << sum << endl;

因为计算机只能理解机器语言，而人类希望用高级语言编写高级语言，所以必须在某些时候将高级语言重新编写（翻译）成机器语言。这是通过内置在各种编程应用程序中的称为编译器、解释器或汇编器的特殊程序来完成的。

C++被设计成一种编译型语言，也就是说它一般被翻译成系统可以直接理解的机器语言，使得生成的程序非常高效。为此，需要一组工具，称为开发工具链，其核心是编译器及其链接器。


**控制台程序**

控制台程序是使用文本与用户和环境进行通信的程序，例如将文本打印到屏幕或从键盘读取输入。

控制台程序易于交互，并且通常具有在所有平台上相同的可预测行为。它们也很容易实现，因此对于学习编程语言的基础知识非常有用：这些教程中的示例都是控制台程序。

编译控制台程序的方式取决于您使用的特定工具。

初学者编译 C++ 程序的最简单方法是使用集成开发环境 (IDE)。IDE 通常集成多个开发工具，包括文本编辑器和直接从中编译程序的工具。


## 下载 / 安装

MinGW就是windows下gcc的版本
https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/

