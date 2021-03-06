# Daily Schedule for OS Tutorial Summer of Code 2020

## TOC

*七月*

| Mon                  | Tues                 | Wed                  | Thur                 | Fri                  | Sat                  | Sun                  |
|----------------------|----------------------|----------------------|----------------------|----------------------|----------------------|----------------------|
|                      |                      | 1 <br> ([D1](#day-1-202071))   | 2 <br> ([D2](#day-2-202072))                  | 3 <br> ([D3](#3))                    | 4 <br> ([D4](#4))                    | 5 <br> ([D5](#5))                    |
| 6 <br> ([D6](#6))                   | 7 <br> ([D7](#7))                   | 8 <br> ([D8](#8))                    | 9 <br> ([D9](#9))| 10 <br> ([D10](#10))  | 11  | 12  |
| 13  | 14  | 15  | 16  | 17  | 18  | 19  |
| 20  | 21  | 22  | 23  | 24  | 25  | 26  |
| 27 | 28 | 29  | 30 |                      |                      |                      |

------

## Day 1 2020/7/1

### 事件1：OS Tutorial Summer of Code 2020

前天就在github上面看到了活动信息，然后立马就投了简历和报名表；正好一直以来就对系统相关的信息很感兴趣，也很早就看到了rcore这样一个项目，暑假也没啥别的事情，这样的好机会当然不能错过啦。（就是今天傍晚才收到回复...所以今天算第一天吧）

相关的计算机原理知识大致都了解过一遍，但没有什么很好的实践；学校教的是MIPS体系结构，rust大名如雷贯耳，但也未曾上手。大概还是有挺多东西要学的。

对于课程的计划时间表，也许有点希望尝试一下把这几个部分进行一定的交叉（？），从了解rust语法和RISC-V的原理开始，结合rcore labs相关的源代码阅读和一定的rust实践工作交叉进行...

### 事件2：rust beginner

今天大部分时间还是花在了mit的6.828上面（继续之前的学习），晚上才算是真正开始（入坑）rust。

主要参考资料：[Rust 程序设计语言](https://kaisery.github.io/trpl-zh-cn/)

- 安装并配置环境；换到国内源
- Hello, World!
- 简单的猜猜看游戏

参考今日文档记录：[Day1_rust_beginner.md](daily_documents/Day1_rust_beginner.md)

顺带瞻仰了一下rcore的设计论文，晚上去了一家还不错的日料店（吃到了河豚锅、海胆刺身还有很不错的土瓶烧！）

>rust看起来真好玩

### 问题

- `waiting for file lock on package cache lock` 折腾了一会，虽然解决了问题但并不很清楚其发生的原因；
- 大概了解了一下rust的设计理念，但语法还需要更深入地学习；

### 预期计划

- 睡个好觉，明天继续看rust基本知识；
- 简单了解一下 RISC-V 体系结构；
- 翻翻rCore的论文和tutorial，大概了解一下lab是要做什么怎么做的；

## Day 2 2020/7/2

### 事件1：rust PL again

主要参考资料：[Rust 程序设计语言](https://kaisery.github.io/trpl-zh-cn/)

继续阅读Rust 程序设计语言，梳理相关语法；

- 常见编程概念
- 所有权
- 结构体
- 枚举、方法匹配
- 使用包和crate
- 集合
- 错误处理
- 泛型、trait 和生命周期

笔记：[Day2_rust_next.md](daily_documents/Day2_rust_next.md)

编程：小练习题：

[Small exercises to get you used to reading and writing Rust code!](exercises/rustlings/readme.md)

- quiz 1-4
- variables
- if
- function
- primitive_types
- structs
- strings
- enums
- tests
- modules
- macros
- move_semantics

>晚上去吃了甲鱼生蚝火锅x

### 事件2：阅读rCore的一些参考资料

参考资料：

[Rust语言操作系统的设计与实现,王润基本科毕设论文,2019](https://github.com/rcore-os/zCore/wiki/files/wrj-thesis.pdf)

[PPT: 尝试用RUST写教学操作系统, 2018](https://s4plus.ustc.edu.cn/_upload/article/files/57/c6/a2ce9bd84b2ab411967842a1334d/27730908-ef69-4827-98a7-8e387875b39b.pdf)

- 大致了解了一下rCore的基本架构和设计实现思路；
- 大致了解了一下rust设计操作系统的相关语言特性和能力；

笔记：[Day2_rCore.md](daily_documents/Day2_rCore.md)

### 遗留的一些问题

- 不知道现在rCore相比于2019年的这篇文章，具体做了哪些演进呢
- 对于rust的一些语法特性并没有特别清晰熟练，还需要更多的阅读和练习
- 部分笔记还没有整理

### 预期计划

- 好好睡觉，明天继续深入rust（应该可以完成 Small exercises 的部分，并看完 PL，再考虑下一步计划
- 简单了解一下 RISC-V 体系结构；
- 尝试编译一下rCore，简单翻翻源代码长啥子样

## Day 3 2020/7/3