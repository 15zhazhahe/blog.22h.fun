# bigo 三轮面试面经

5.19 bigo面试，岗位C++后台开发(广州)，面了一上午，总共三轮技术面，然后就没然后了，听天由命。。。

比较重要的点是笔试要认真的做，因为面试的问题基本上是针对你笔试的点一个一个问的。自己笔试做的有点粗糙，由于自己当天有事，差不多40分钟左右就交了，然后后面编程题bug有点多，然后由于基础薄弱前面选择题做的也不好，自己也没有太在意笔试，后面回去也没有好好总结，就编程题回顾了一下貌似错的挺多的......收到面试还是挺幸运的。

部分题目还是有些遗忘，不过大致知识点就是这样了。

## 第一轮面试

一开始照例自己我介绍，然后就开始根据项目(简易聊天室)问一些知识点

+ 网络编程TCP服务器构建的步骤（就是socket那一套步骤）
+ TCP与UDP的区别
+ TCP如何实现可靠交付
+ TCP四次挥手的过程
+ 析构函数为虚函数的作用
+ 有问常用什么编程环境(IDE(Code::blocks，Clion)什么的，vim熟悉吗)
+ 数据库索引的实现原理，B树和B+树的应用场景
+ hash冲突的解决方法
+ 算法题：给一个vector< float > p，p[i]表示下表为i的概率为多少，现在实现一个select函数返回一个索引i，进行若干次调用以后，使得返回所有的索引分布尽可能近似趋近事先给定的概率

## 第二轮面试

+ 栈和堆的区别（内存方面的）
+ 算法题：有一个记录日志(很多条)，每条访问记录都有一个ip地址，现在问你访问频率最高（出现次数最多的）的20个ip
+ 大端和小端模式，如何查看自己的电脑时大端还是小端
+ 逻辑地址和物理地址的关系，由具体什么进行转换(地址加法器)
+ 线程和进程的区别
+ 链接是什么作用，整个程序到可执行代码经历了什么
+ 有很多个2毛硬币，3毛硬币，5毛硬币，现在问你组成x毛的硬币的方案数，写出dp递推式就可以了
+ 给出入栈序列，求出栈方案数（卡特兰数）
+ 你觉得操作系统对你写代码有什么帮助吗
+ 给出入栈序列和出栈序列，判断是否合法
+ 怎样理解hash
+ 给一串英文语句，让你对语句进行翻转(this is a word -> word a is this)，第一次做法由对每个单词进行翻转，然后整体翻转(复杂度要求没满足)，然后就说如果是vector< string >就好做了，那么就转换成这样子(手写代码)

## 第三轮面试

基本上对着错题一题一题问怎么想的，还有一些写的不确定的题目

+ 数组里有一个数字出现次数超过一半，让你找出来这个数是什么。(笔试题目，代码写的有bug，让自己找bug)
+ 二分查一个有序数组的值。（笔试题目，代码写的有bug，让自己找bug）
+ TCP三次握手时的几种状态，以及过程中的一些细节(seq包序号什么之类的)
+ 数据库事物锁相关知识(没了解，直接略过了)
+ 八个球其中有一个最轻，其他质量一样，问最少需要称几次（2）
+ 九个球其中有一个最轻，其他质量一样，问最少需要称几次（2）


---

真的对每一轮环节都不能泄气，不然一定会在后面埋下大坑，就像这次我的笔试，以为水过去就好了，写完以后也没有仔细总结，导致面试的时候有点没准备的太好。

最后一面结束的时候扯了些没用的，不过说到底还是自己实力不够，只有最后一面有问问题，其他两面都没机会问问题，其实挺想知道面试评价的，想多积累一点经验的，不过硬伤还是基础太薄弱了，前两年精力大部分花在ACM上，结果ACM成绩不是特别理想，然后专业课基本都是最后冲刺才勉强过去的，还是很多不足，最近需要看的东西有很多。

第三面面试官评价说有一定代码能力，但是计算机网络基础比较薄弱（自认为计算机基础都比较薄弱。。。），感觉如果从应试的角度来看，了解这个公司的部分业务，可能能获得一定技术的侧重点，然后多准备一点。不过最后还是需要自己实力够硬，加油，近期好好恶补一下，自己一定能拿下暑假实习的。