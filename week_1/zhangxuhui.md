- 第一章

了解了一个helloword c程序的编码到运行，预处理->编译->汇编->链接，其中讲链接很有意思，所用的系统函数（printf）之类的都已经预编译过了，链接做的操作是将其与之合并。
这一章也提出了几个问题很吸引人继续读下去，
* switch 语句是否比一系列的if then else 高效的多？
* 一个函数调用的开销是多少？
* ...

操作系统的设计是对各系统的不同i/o设备进行抽象、对系统来说都是文件，通过总线进行通讯。

不同进程的切换过程是保存当前上下文，系统中断（system call），恢复下个进程上下文，这里有个疑问就是上下文的信息是保存在寄存器里吗，是怎么样一个保存和恢复的过程？信息会不会很大？

- 第二章

这一章还是主要复习时到在学校里学的基础知识，了解数据的存储格式是必要的，字节排序中大小端法很有意思，（故事也很有意思），这章收获颇多，难度也很大，准备抽时间再读一遍。
