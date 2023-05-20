### C/C++初学者练习题库

### MENU

- [TO-DO LIST](#to-do-list)
- + [BACKGROUND](#background)
- + [TUTORIAL](#tutorial)
- [HOW TO USE](#how-to-use)

### HOW TO USE

#### BACKGROUND

制作的一套`C/C++`程序题库，其目的是为了帮助熟悉掌握`C/C++`基础知识。程序自带检验和错误反馈功能，并有积分激励机制，假设你只配置了`Dev-C++`开发环境，题库的设计以在`Dev-C++`开发环境上使用方便为目的。使用效果不错，可以分享给一些想学`C/C++`的朋友或同学，都觉得的确对于`C/C++`初学者有一定的帮助。

这套程序题库有点类似于`Online Judge`，只不过它是在`Dev-C++`本机环境中使用（其实也可以在其他开发环境例如`visual studio`、`code::blocks`、`小熊猫C++`中使用，但是没有`Dev-C++`那么方便）。但与`Online Judge`的设计思想完全不同，`Online Judge`大多是黑盒测试，并不会给使用者过多的反馈，代码粘贴到网页中执行也缺乏本机环境的编辑调试能力，它是为算法竞赛而设计；但这套程序题库的设计思想是教会`C/C++`初学者基础知识，所以题库设计难度循序渐进，起到对初学者逐步建立起程序思维的作用，直接在开发环境中编辑和调试代码，有助于初学者对开发环境的熟悉掌握， 并且在程序执行结果不对的时候给予充足的提示信息以帮助初学者纠正错误。

虽然题库的使用非常简单，但每次还是少不了要教人一遍用法，为方便日后有人再问起，我写个使用教程。

#### TUTORIAL

1. 安装`Dev-C++`开发环境
  + [`Dev-C++`下载链接]()
2. 下载题库并解压（先解压，别直接在压缩包中使用）
  + [题库下载链接]()
3. 解压目录下的每个`A0**.cpp或B0**.cpp`源文件是独立的一道题，启动`Dev-C++`开发环境，拖拽其中一个文件到`Dev-C++`开发环境的窗口界面，或者在`Dev-C++`中直接打开
  ![1](https://www.foxzzz.com/cpp-quiz/1.png)
  
  ![7](http://61.186.173.89:2019/2023/05/20/55bec3eb189a0.png)
  
  ![8](http://61.186.173.89:2019/2023/05/20/bd918a524f937.png)
4. 根据题目要求，补充代码并编译运行
  ![2](https://www.foxzzz.com/cpp-quiz/2.png)
5. 程序测试给出的反馈
  ![3](https://www.foxzzz.com/cpp-quiz/3.png)
6. 如果全部测试通过，可按下回车查看总得分
  ![4](https://www.foxzzz.com/cpp-quiz/4.png)
7. 如果发生部分测试未通过，可按下回车查看错误提示
  ![5](https://www.foxzzz.com/cpp-quiz/5.png)
8. 可以另开一个程序写，也可以把`#define JUDGE_MODE`和`#include "./judge/A001.h"`用`ctrl+/`注释掉，等提交代码进行批改时再`ctrl+/`取消住宿。建议把`#include <iostream>`改成`#include <bits/stdc++.h>`
  ![6](http://61.186.173.89:2019/2023/05/20/fdec9e60b78b6.png)
  
> ***详情可以访问 https://www.foxzzz.com/cpp-quiz/***

### TO-DO LIST

- [X] 撰写README.md
- [ ]添加所有题目的题解
- [ ]在线ide
