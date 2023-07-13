# 赛博协会逆向实验

## Work 1  dynamic

### work 简介

**本题所给的程序是PE文件，但是这个文件并不是由常见的C编译器编译而来的exe，你需要探索出这个文件是由什么语言所编写的.**

### 目标：

**1.找出编写该文件的语言，并且得到对应语言下的伪代码.**

**2.在寻找程序中一段关键代码时，你会发现这部分代码所在的模块被加密了，请你给出解密的方法.**

**3.找到程序中的flag**

### 拓展

**1.了解什么是“壳”，“壳”对程序有什么作用https://upx.github.io/**

**2.[extremecoders-re/pyinstxtractor: PyInstaller Extractor (github.com)](https://github.com/extremecoders-re/pyinstxtractor)**

## Work 2 Weird

### work 简介

**本题所给的程序是一个由gcc编译生成的elf文件，为此你可以了解一下elf和exe的区别.**

### 目标：

**1.找出在main函数之前运行的函数（可以忽略start)，并且思考如何让函数在main函数之前运行（提示:不同的操作系统和编译器由不同的方法）.**

**2.给出first()和second()函数运行的顺序，并且说明理由.**

**3.找到程序中的flag，并且思考如何快速的得到此flag**

### 拓展

**1.了解C语言中独特的数据结构——栈**

**2.了解一个文本文件(.c)到一个可执行文件(.exe)之间经历了什么**

