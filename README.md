# EE-CS-study-map

本人的学习规划目录，用于记录



## Misc

计算机、数字世界的一些通识

[criwits/missing-web: 你缺失的那门计算机课（网页版）| Your Missing Semester of Using Computer (Web Version) (github.com)](https://github.com/criwits/missing-web)。



计算机教育中缺失的一课

[为什么大学c语言课不顺便教一下Linux，Makefile，git，gdb等配套工具链呢? - 知乎 (zhihu.com)](https://www.zhihu.com/question/576758408/answer/2830758012)。

[计算机教育中缺失的一课 · the missing semester of your cs education (missing-semester-cn.github.io)](https://missing-semester-cn.github.io/)。

> 1/13: 课程概览与 shell
> 1/14: Shell 工具和脚本
> 1/15: 编辑器 (Vim)
> 1/16: 数据整理
> 1/21: 命令行环境
> 1/22: 版本控制(Git)
> 1/23: 调试及性能分析
> 1/27: 元编程
> 1/28: 安全和密码学
> 1/29: 大杂烩
> 1/30: 提问&回答



心理学、哲学上的 程序员 的学习分析

[你认为哪些领域的知识对程序员来说特别重要？ - 知乎 (zhihu.com)](https://www.zhihu.com/question/5392270023/answer/46161501985)。



## 入门阶段 - 目录

在本科毕业将近时，和实验室同届的大牛总结过嵌入式、计算机的学习路径清单：
[【目录贴】总览软硬件规范化的意义和内容 - 欢迎来到 瞰百Staok](https://staok.github.io/总览软硬件规范化的意义和内容/#学习路径)。



在硕士（2020 - 2023）毕业将近时，个人总结过硕士几年的学习路径文章：
[【目录贴】硕士实验室嵌入式学习路线参考清单 - 欢迎来到 瞰百Staok](https://staok.github.io/硕士实验室嵌入式学习路线参考清单/)。


基本的嵌入式学习路线：

基本路线为（排序没那么严格）：

- c、数据结构与算法、设计模式、C++（各版本特性）
- mcu+汇编+hal库、电类专业基本课程、各类电路拓扑学习和设计、各类芯片使用
- linux 系统使用+shell命令+应用编程（文件、各种实用系统API、进程线程以及通讯和同步机制、网络、IO并发等）+ 驱动编程（设备、驱动、设备树、中断、与应用层交互等的概念和编程）
- 各维度工具链熟练使用和搭建，git、vim，gcc、make、cmake、dgb/dgb-server，
- 各个方面的一些规范和实践经验总结
- 以及 可选的uboot、linux等的移植、buildroot学习、linux内核开发等，可选的FPGA大类（verilog/systemVerilog，IP核，仿真，SOPC，时序和时钟约束）

这个路线是我截止到硕士毕业的阶段性的总结。

具体的路线网上有很多，路线可参考的就有：

- [Linux嵌入式所有知识点-思维导图-【一口君吐血奉献】 (qq.com)](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247497822&idx=1&sn=1e2aed9294f95ae43b1ad057c2262980&chksm=f96b8aaace1c03bc2c9b0c3a94c023062f15e9ccdea20cd76fd38967b8f2eaad4dfd28e1ca3d&scene=21#wechat_redirect)。
- [嵌入式驱动工程师学习路线【建议收藏】 (qq.com)](https://mp.weixin.qq.com/s?__biz=MzUxMjEyNDgyNw==&mid=2247496985&idx=1&sn=c3d5e8406ff328be92d3ef4814108cd0&chksm=f96b87edce1c0efb6f60a6a0088c714087e4a908db1938c44251cdd5175462160e26d50baf24&scene=21#wechat_redirect)。
- [phodal/eks: 嵌入式知识总汇 Embedded Knowledge Structure (github.com)](https://github.com/phodal/eks)，偏硬件。
- [Staok/ARM-Linux-Study: ARM Linux 的学习历程。包括应用、驱动、设备树，GCC, Make, CMake, Bash, Vim, Git 等等大集合内容。文章遵守 CC BY NC SA 4.0 协议。 (github.com)](https://github.com/Staok/ARM-Linux-Study/tree/main) 里面的 `嵌入式开发学习路线(知识点)梳理`，`成为嵌入式高手的技能清单和升级线路图`。
- .etc

现在这个阶段的总结，即各种 CS 大类，即以下的内容。

------



## 精进阶段 - 目录

主干仓库目录，一些支线仓库在此就不列了。



本人总结的一些 CS 相关的仓库

- C & MCU 编写规范

  [Staok/coding-style-and-more: C 编写规范和其他。永远地不定期更新。CC-BY-NC-SA 4.0。 (github.com)](https://github.com/Staok/coding-style-and-more)。

- C++学习总结备查（C++语言特性、实用库）

  [Staok/Cpp-Learning: C++学习总结备查 (github.com)](https://github.com/Staok/Cpp-Learning)。

- C-C++ 模板工程（cmake）



- C-C++-数据结构与算法简述和CS综合
- C-C++-设计模式综合



嵌入式 Linux 相关的仓库

- Linux：ARM-Linux-Study

  [Staok/ARM-Linux-Study: ARM Linux 的学习历程。包括应用、驱动、设备树，GCC, Make, CMake, Bash, Vim, Git 等等大集合内容。文章遵守 CC BY NC SA 4.0 协议。 (github.com)](https://github.com/Staok/ARM-Linux-Study)。

- 待补充新篇章（见下面 `补充` 一节）



硬件相关：

- 硬件：SCH & PCB 设计规范和 AD 的使用

  [Staok/thoughs-about-hardware-design: 介绍和罗列关于硬件设计所需要考虑的各个方面。纯个人经验总结，非科班念经。永远地不定期更新。CC-BY-NC-SA 4.0。 (github.com)](https://github.com/Staok/thoughs-about-hardware-design)。

- FPGA：HDL & FPGA 学习和规范

  [Staok/HDL-FPGA-study-and-norms: HDL & FPGA 学习和规范。CC-BY-NC-SA 4.0。 (github.com)](https://github.com/Staok/HDL-FPGA-study-and-norms)。



还需要慢慢补充进去的内容：



```
c++11，c++14，c++17 等 语言特性列出总结和学习
整理各种实用库，以及 win 和 linux 上的使用（win 上即 cmake+pkgconfig，linux 上即 buildroot+cmake+pkgconfig），即下面的“实用库 / 实现”里面的
数据结构与算法（主要是算法思路，比如使用动态规划的思路去设计算法程序）
c++最佳实践经验，现代c++编程
设计模式（如敏捷开发这一大课题（可看其百度百科），以及其下的各种方法，如TDD FDD等。其它还有任务状态设计模式，信号槽模式等等，适用于不同场景）
```



------



## 精选 github 仓库 - 目录

自己的 github star 精品库，均为日常持续补充



### 目录



CS / C/C++ / 系统 / 综合

涵盖基础编程语言特性，数据结构与算法，开发模式，计算机组成原理、计算机系统、计算机网络/TCP-IP、编译原理 等等。很多精品。

[Your list / CS / C/C++ / 系统 / 综合 (github.com)](https://github.com/stars/Staok/lists/cs-c-c-系统-综合)。



嵌入式 / 全栈 / 综合贴

嵌入式综合、linux综合、github rank、全栈学习综合贴等等。很多精品。

[Your list / 嵌入式 / 全栈 / 综合贴 (github.com)](https://github.com/stars/Staok/lists/嵌入式-全栈-综合贴)。



实用库 / EE-CS

总结很多非常实用，工程可用的，各种库，用于 EE 和 CS 的。

[Your list / 实用库 / EE-CS (github.com)](https://github.com/stars/Staok/lists/实用库-ee-cs)。



嵌入式项目 / 协议栈 / 库

聚焦嵌入式项目，嵌入式专用的库。

[Your list / 嵌入式项目 / 协议栈 / 库 (github.com)](https://github.com/stars/Staok/lists/嵌入式项目-协议栈-库)。



### 聚焦



#### 在上面的仓库中的



##### 可以快速刷着看的

- 简明教程 [C++ Beginner's Guide for Python/Java/... Programmers | hacking C++ (hackingcpp.com)](https://hackingcpp.com/cpp/beginners_guide.html#intro)

  这个推荐刷完

- **对于 C 语言特性的精品汇总**
  
  - [Knowledge-Notes/2 - C语言笔记 at master · wuxiaolie/Knowledge-Notes (github.com)](https://github.com/wuxiaolie/Knowledge-Notes/tree/master/2 - C语言笔记)。
  - [embedded/01_C at master · kuraxii/embedded (github.com)](https://github.com/kuraxii/embedded/tree/master/01_C)。
  - [lh233/C-knowledge: 关于C语言的基础知识 (github.com)](https://github.com/lh233/C-knowledge)。



- **对于 C++ 语言特性的精品汇总**

  - [Knowledge-Notes/2 - C++笔记 at master · wuxiaolie/Knowledge-Notes (github.com)](https://github.com/wuxiaolie/Knowledge-Notes/tree/master/2 - C%2B%2B笔记)。
  - [embedded/02_CPP at master · kuraxii/embedded (github.com)](https://github.com/kuraxii/embedded/tree/master/02_CPP)。
  - [EmbeddedSystem/Language at master · SummerGift/EmbeddedSystem (github.com)](https://github.com/SummerGift/EmbeddedSystem/tree/master/Language)。

  

  - [chengxumiaodaren/cpp-learning (github.com)](https://github.com/chengxumiaodaren/cpp-learning)。
- [C++11/14/17/20/23新特性，哪些是必须掌握的，哪些基本用得不多？ - 知乎 (zhihu.com)](https://www.zhihu.com/question/474664436/answer/3612037757)。



##### 可以慢慢看的

- CS学习综合贴

  [imarvinle/CSGuide: 🔥 计算机学习路线，包括科班、非科班、Web、全栈、C++、Java、System等 (github.com)](https://github.com/imarvinle/CSGuide)。

  - [计算机学习路线大全（2024版） | 编程指北 (csguide.cn)](https://csguide.cn/roadmap/)。
  - [C/C++后台开发面试重点知识 | 编程指北 (csguide.cn)](https://csguide.cn/cpp/)。

- 设计模式 [EmbeddedSystem/DesignPattern at master · SummerGift/EmbeddedSystem (github.com)](https://github.com/SummerGift/EmbeddedSystem/tree/master/DesignPattern)。

- 嵌入式项目、库 [zhengnianli/EmbedSummary: 精品嵌入式资源汇总 (github.com)](https://github.com/zhengnianli/EmbedSummary)。

- 计算机网络 [kuraxii/Computer-Network-Notes (github.com)](https://github.com/kuraxii/Computer-Network-Notes)。

- [Admol/SystemDesign: 系统设计面试：内幕指南（System Design Interview: An Insider’s Guide） (github.com)](https://github.com/Admol/SystemDesign)。



##### C++ 相关慢慢看的

- **C 精品仓库**

  - [jobbole/awesome-c-cn: C 资源大全中文版，包括了：构建系统、编译器、数据库、加密、初中高的教程/指南、书籍、库等。 (github.com)](https://github.com/jobbole/awesome-c-cn)。

- **C++ 精品仓库**

  下面这些 C++ 笔记仓库可牛了（这些仓库均已离线到 `C++学习相关Github仓库收集` 文件夹下！）

  - [chengxumiaodaren/cpp-learning (github.com)](https://github.com/chengxumiaodaren/cpp-learning)。好内容非常多。
  - [linux-cpp-tutorial: 基于Linux的C++ 教程合集， 包括C++基础， C++服务器， C++专题 - Gitee.com](https://gitee.com/andy-upp/linux-cpp-tutorial/tree/master)。
  - [czs108/Cpp-Primer-5th-Notes-CN: 📚 《C++ Primer中文版（第5版）》笔记 (github.com)](https://github.com/czs108/Cpp-Primer-5th-Notes-CN)。
  - [demon90s/CppStudy: My study notes for c/cpp language (github.com)](https://github.com/demon90s/CppStudy)。
  - [Light-City/CPlusPlusThings: C++那些事 (github.com)](https://github.com/Light-City/CPlusPlusThings)。
  - [0voice/introduce_c-cpp_manual: 一个收集C/C++新手学习的入门项目，整理收纳开发者开源的小项目、工具、框架、游戏等，视频，书籍，面试题/算法题，技术文章。 (github.com)](https://github.com/0voice/introduce_c-cpp_manual)。
  - [0voice/cpp_new_features: 2021年最新整理， C++ 学习资料，含C++ 11 / 14 / 17 / 20 / 23 新特性、入门教程、推荐书籍、优质文章、学习笔记、教学视频等 (github.com)](https://github.com/0voice/cpp_new_features)。
  - [FunctionDou/STL: STL源码分析 (github.com)](https://github.com/FunctionDou/STL)。
  
  **C++ 精品专项**
  
  - [Mq-b/ModernCpp-ConcurrentProgramming-Tutorial: 现代C++并发编程教程 (github.com)](https://github.com/Mq-b/ModernCpp-ConcurrentProgramming-Tutorial)。
  - [parallel101/course: 高性能并行编程与优化 - 课件 (github.com)](https://github.com/parallel101/course)。
  
  
  
  - [Mq-b/Modern-Cpp-templates-tutorial: 现代C++模板教程 (github.com)](https://github.com/Mq-b/Modern-Cpp-templates-tutorial)。
  - [wuye9036/CppTemplateTutorial: 中文的C++ Template的教学指南。与知名书籍C++ Templates不同，该系列教程将C++ Templates作为一门图灵完备的语言来讲授，以求帮助读者对Meta-Programming融会贯通。(正在施工中) (github.com)](https://github.com/wuye9036/CppTemplateTutorial)。



##### linux 相关慢慢看的

- [SuperTao/LinuxDriver: 总结Linux驱动写法，编写关于字符设备，platform，锁，中断等example。 (github.com)](https://github.com/SuperTao/LinuxDriver)。
- [CTTCassie/Linux: Linux下的系统编程&网络编程&shell脚本&gtest (github.com)](https://github.com/CTTCassie/Linux)。



- [hust-open-atom-club/linux-insides-zh: Linux 内核揭秘 (github.com)](https://github.com/hust-open-atom-club/linux-insides-zh)。
- [0voice/linux_kernel_wiki: linux内核学习资料：200+经典内核文章，100+内核论文，50+内核项目，500+内核面试题，80+内核视频 (github.com)](https://github.com/0voice/linux_kernel_wiki)。



#### 不在上面仓库中的

一些专项的、有意思的视频、文章合集



Linux驱动开发学习分享

原生C++入门教程

FFmpeg基础

等等

https://space.bilibili.com/266979612/channel/series



现代C++项目实战

高性能并行编程与优化

https://space.bilibili.com/263032155/channel/series



- 编译原理 / Compiler Principles：[《编译原理》总集篇](https://www.criwits.top/page/20221116140525-w0au45l)

- 操作系统 / Operating System：[《操作系统》总集篇](https://www.criwits.top/page/20230701100249-1fm004l)

- 密码学基础 / Cryptology：[《密码学基础》总集篇](https://www.criwits.top/page/20230701100315-osil36j)

- 计算机网络 / Computer Network：[《计算机网络》总集篇](https://www.criwits.top/page/20230701100327-0xryipa)

------



## 补充

积累到一定程度，会专门开仓库的领域，或者补充到上面自己仓库的一些资料。



### buildroot

- buildroot 官方手册
- 正点原子翻译的
- [buildroot编译框架_Once-Day的博客-CSDN博客](https://blog.csdn.net/once_day/category_12515863.html)。
- tips，查看所有配置项，可以选择 deconfig 之后，查看 生成的 config 文件 里面的所有项
- 按照纸上记录的 过程，上手验证一遍，记下主要步骤就行。



### linux 各方面

- 总结到了 linux 仓库，可以新开比如 3.1 这种分支文章来记录

  - 韦东山的 v2.0 文档看到了截止到 23年中的，基本看完，可以再快速过一遍。


  - 正点原子的 linux 文档，分应用和驱动，有一些和韦东山文档里的有所补充，个人认为可以快速过一过，新开 md 文档，把都有什么机制列一列（目录形式的），看懂了大概怎么用查清楚写上过程就行，这种都是要具体用时现查就行。


- linux 内核配置，移植，各个东西都从哪里找，uboot也一样。

- github 各种仓库。

- ARM

  - [#从0学arm (qq.com)](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1614665559315382276#wechat_redirect)

- 驱动 & 内核

  - [从开机到第一行linux内核代码执行之间的全部过程 (qq.com)](https://mp.weixin.qq.com/s/uPQ_EM1q2CzZUelvu1q28A)

  

  - [#Linux驱动 (qq.com)](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1502410824114569216#wechat_redirect)
  - [#linux (qq.com)](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1507350615537025026#wechat_redirect)

- 网络

  - [#网络 (qq.com)](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUxMjEyNDgyNw==&action=getalbum&album_id=1598710257097179137#wechat_redirect)

    







