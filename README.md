# Racket 软件简介

Racket 是一种 Lisp 方言(“方言”，地域方言和社会方言，本文指“数字域‘方言’”)。

Racket 源自 PLT Scheme(古典的专家型语言)，同时又是 Lisp 语言的一个分支(俗称“Lisp 方言”)。它适用于从脚本(Script)到应用程序(App)开发的任务执行工具，包括图形用户界面、Web服务器等。支持编译器的虚拟机，创建独立的可执行程序的工具，Racket Web 服务器，具有丰富而全面的功能库，既适用于初学者，也是专家编程者所爱。

Racket 可通过创建大量的语法系统来支持和创建新的编程语言，包括 Typed Scheme、ACL2、 FrTime、Lazy Scheme 和 ProfessorJ 等 。

作为编程语言的通用测试平台，Racket 软件包主要工具包括：

* racket——系统核心部分，主要包括编译器、解释器和运行库程序，它是 cmd 下的命令行程序；

* DrRacket——原为DrScheme，是一个基于 Racket 的开源、跨平台系统的IDE集成编程环境，DrRacket 则是 Window s窗口程序，更适用于初学者的 GUI 图形化用户编程界面；

* raco——基于字符界面的命令行执行工具，用于执行 Racket 命令集，如安装系统组件功能包，创建函数库等。

Racket 的特点是具有全面而丰富的库，可用于实现 xml、web-server、web-framework、multiple-threads、pattern match、latex、slides、posix、GUI等，其实用性不亚于另一种 Lisp 方言 Common Lisp。另外，其与众不同的特点在于 macro和continuation，并引入了 syntax object 和 compilable macro 的概念。

# 简说人工智能界经典语言 LISP 的几个主要特点：

1．计算用的是符号表达式而不是数；

2．具有表处理能力，即用链表形式表示所有的数据；

3．控制结构基于函数的复合，以形成更复杂的函数；

4．用递归作为描述问题和过程的方法；

5．用 LISP 语言书写的获取返回值函数(EVAL)既可作为 LISP 语言的解释程序，又可以作为语言本身的形式定义；

6．程序本身也同所有其他数据一样用表结构形式表示。

实践已经证明：LISP 的这些特点是解决人工智能核心问题的关键。它和后来由英国伦敦大学的青年学生柯瓦提出、由法国马赛大学的考尔麦劳厄(Alain Colmerauer)所领导的研究小组于1973年首先实现的逻辑式语言 PROLOG 并称为人工智能的两大语言，都对人工智能的发展起了十分深远的影响。

=====================================================================



[Racket](https://racket-lang.org/) is a general-purpose programming
language and an ecosystem for language-oriented programming.

This repository holds the source code for the core of Racket plus some
related packages. The rest of the Racket distribution source code is
in other repositories, mostly under [the Racket GitHub
organization](https://github.com/racket).

Quick Start
-----------

Pre-built versions of Racket for a variety of operating systems and
architectures, as well as convenient source distributions are
available at

  [https://download.racket-lang.org](https://download.racket-lang.org)

Racket comes with extensive documentation, including several tutorials.
You can read all of this documentation, as well as documentation for
third-party packages at

  [https://docs.racket-lang.org](https://docs.racket-lang.org)

Building from Source
--------------------

For information on building Racket from this repository, see the
[Build Guide](build.md).

Contributing
------------

Contribute to Racket by [submitting a pull request](https://github.com/racket/racket), joining the
[development mailing list](https://lists.racket-lang.org), or visiting
the [IRC](https://botbot.me/freenode/racket/) or [Slack](https://racket-slack.herokuapp.com/) channels.

By making a contribution, you are agreeing that your contribution is
licensed under the LGPLv3, Apache 2.0, and MIT licenses. Those
licenses are available in this repository in the files
racket/src/LICENSE-LGPL.txt, racket/src/LICENSE-APACHE.txt, and
racket/src/LICENSE-MIT.txt.

See the [Racket Build Guide](build.md) for more guidance on
contributing.

The [Friendly Environment Policy](https://racket-lang.org/friendly.html) contains guidelines on expected behavior within the Racket community.

License
-------

Racket is free software; see [LICENSE](LICENSE) for more details.
