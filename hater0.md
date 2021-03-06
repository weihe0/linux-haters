Linux——比UNIX更强的病毒
======================================
1991年，赫尔辛基大学的一位大学生，给386型微机创造了一款类似UNIX的操作系统。当时的他可能没想到，他出于好玩而创造的这款操作系统，会成为各种UNIX系统中传染性最强的变种。这位大学生叫Linus，而他创造的系统就叫Linux。

Linux系统的前身UNIX系统，就是一种计算机病毒。病毒的第一个特点是个体微小，UNIX刚诞生时就体积就很小，也没有多少功能。病毒的第二个特点就是适应性强，UNIX系统很容易移植到各种各样的计算机上。病毒的第三个特点就是消耗宿主，UNIX依靠宿主主机的资源存活，如果没有系统管理员的悉心呵护，UNIX系统会很快崩溃。病毒的第四个特点就是快速变异，UNIX系统传播开来以后，一些公司与学校出现了UNIX的变种，他们互不兼容。病毒的特性，UNIX系统全都有。

UNIX这种病毒是在AT&T公司的实验室培养出来的。当时，汤普森与里奇两人想在实验室的一台PDP-7计算机上制作一款叫做“星际旅行”的游戏。为了制作这款游戏，首先要给PDP-7计算机开发操作系统。于是他们为PDP-7编写了操作系统内核、汇编器与文件系统，取名为UNIX。换句话说，当初创造UNIX并不是为了做一个通用的操作系统，而是为了玩星际旅行而已。他们并没有意识到，他们创造的UNIX系统是一种计算机病毒。他们非但没有阻止UNIX的传染，反而将它主动分享给同事，实际上就把UNIX给放了，整个实验室的计算机都感染了UNIX。

由于UNIX是汤普森和里奇的业余项目，AT&T的管理层没把它当回事，当外界有研究者找他们要源代码时，他们就把UNIX的源代码给放出去了。先是哥伦比亚大学的研究者找里奇要了一份UNIX源代码。几年后UNIX系统传染了各大院校，它们都有UNIX源代码了。大学生都必须在UNIX系统上学习计算机科学。伯克利大学甚至在AT&T的UNIX源代码基础上推出了自己的UNIX系统，名为BSD。BSD是除AT&的原版UNIX外传播得最广的UNIX变种，对UNIX世界的影响非常深。BSD上的许多命令、工具与子程序后来都成为了UNIX系统的标准配置。像DEC，IBM，Sun还有惠普等计算机厂商也嗅到了商机，纷纷销售UNIX工作站。它们之所以都能做出UNIX工作站，不是因为UNIX的功能有多么强大，而是它体积小巧、功能简单以及由此而来的便于移植。当然，这些厂商在移植UNIX的过程中都出现了变异，IBM的UNIX叫AIX，Sun的UNIX叫Solaris，惠普的UNIX叫HP-UX。当时濒于破产的苹果公司为了挽回颓势，也把自家的Mac系统改造为UNIX的一种变体。

虽然UNIX源代码早就在各大院校和公司传开了，但可笑的是，这些开发UNIX变体的公司与院校，都把自己的UNIX系统视为专有软件。把已经传开的UNIX源代码据为己有，当然是一件很滑稽的事。一群计算机高手打算戳穿他们的滑稽行为，就发起了名为GNU的自由软件运动。所谓自由软件，就是可以自由地运行、复制、发布、研究和改进的软件。为了确保软件的自由，他们发布的源代码都使用了GPL许可证。GPL许可证给了用户运行、研究和修改软件的自由，但用户必须以GPL许可证发布修改后的源代码，这样整个自由软件社群都能共享改进成果。由于UNIX体积小巧又容易移植，他们重写了UNIX系统的绝大部分组件，包括编译器、链接器、文本编辑器等等。但他们在研发操作系统内核上遇到了挫折，这就给今后的Linux以可乘之机。
