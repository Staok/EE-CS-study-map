# EE-CS-study-map


基本的嵌入式学习路线：

[【目录贴】硕士实验室嵌入式学习路线参考清单 - 欢迎来到 瞰百Staok](https://staok.github.io/硕士实验室嵌入式学习路线参考清单/)

基本路线为（排序没那么严格）：c、mcu+汇编+hal库、电类专业基本课程、各类电路拓扑学习和设计、各类芯片使用、linux 系统使用+shell命令+应用编程（文件、各种实用系统API、进程线程以及通讯和同步机制、网络、IO并发等）+驱动编程（设备、驱动、设备树、中断、与应用层交互等的概念和编程）、各个方面的一些规范和实践经验总结，以及 可选的uboot、linux等的移植、buildroot学习、linux内核开发等，可选的FPGA大类（verilog/systemVerilog，IP核，仿真，SOPC，时序和时钟约束）

这个路线是我截止到硕士毕业的阶段性的总结，现在这个阶段的总结，即各种 CS 大类，即以下的内容。



------



以下是 CS 一些主干相关的：



个人对c++较全面的总结：

https://github.com/Staok/Cpp-Learning

还需要慢慢补充进去的内容：

```
c/c++ 环境搭建，个人最佳实践
win上：mingw+cmake+make+VSCode+clangd
两种：一种提供工程模板，一种快速从0搭建vscode工程（cmake quick start，vscode 快速配置task 和 lunch）
有待出一个这个模板，将以上所有用到的bin打包放一起，写上配置环境变量的步骤，配置clangd（安装clang，安装clangd插件，配置等）
设置vscode的推荐：设置trim，安装一些推荐插件（c/c++插件disable 掉 intel sense），保持最简
```

```
c++11，c++14，c++17 等 语言特性列出总结和学习
整理各种实用库，以及 win 和 linux 上的使用（win 上即 cmake+pkgconfig，linux 上即 buildroot+cmake+pkgconfig），即下面的“实用库 / 实现”里面的
数据结构与算法（主要是算法思路，比如使用动态规划的思路去设计算法程序）
c++最佳实践经验，现代c++编程
设计模式（如敏捷开发这一大课题（可看其百度百科），以及其下的各种方法，如TDD FDD等。其它还有任务状态设计模式，信号槽模式等等，适用于不同场景）
```



------



自己的 github star 精品库，均为日常持续补充



CS 学习 / C/C++ 进阶 / 系统

包含非常丰富，涵盖基础编程语言特性，数据结构与算法，开发模式，计算机组成原理、计算机系统、计算机网络/TCP-IP、编译原理 等等

[Your list / CS 学习 / C/C++ 进阶 / 系统 (github.com)](https://github.com/stars/Staok/lists/cs-学习-c-c-进阶-系统)



实用库 / 实现（总结很多非常实用，工程可用的，各种库）

[Your list / 实用库 / 实现 (github.com)](https://github.com/stars/Staok/lists/实用库-实现)



嵌入式项目 / 协议栈 / 库

[Your list / 嵌入式项目 / 协议栈 / 库 (github.com)](https://github.com/stars/Staok/lists/嵌入式项目-协议栈-库)



------



一些专项的、有意思的视频合集



Linux驱动开发学习分享

原生C++入门教程

FFmpeg基础

等等

https://space.bilibili.com/266979612/channel/series



现代C++项目实战

高性能并行编程与优化

https://space.bilibili.com/263032155/channel/series
