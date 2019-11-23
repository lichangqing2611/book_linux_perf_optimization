&emsp;&emsp;我通过阅读各种相关书籍，从操作系统原理、到 Linux内核，再到硬件驱动程序等等。  
&emsp;&emsp;把观察到的性能问题跟系统原理关联起来，特别是把系统从应用程序、库函数、系统调用、再到内核和硬件等不同的层级贯穿起来。  
&emsp;&emsp;**性能优化**是个系统工程，总是牵一发而动全身，它涉及了从程序设计、编程语言，再到系统、存储、网络等各种底层基础设施的方方面面。每一个组件都有可能出问题，而且很有可能多个组件同时出问题。  
&emsp;&emsp;讲解 Linux 性能的基本指标、工具，以及相应的观测、分析和调优方法。包括 CPU 性能、磁盘 I/O 性能、内存性能以及网络性能。  
&emsp;&emsp;  
&emsp;&emsp;系统性能问题，只要你理解了应用程序和系统的少数几个基本原理，再进行大量的实战练习，建立起整体性能的全局观。  
&emsp;&emsp;**性能指标**：“高并发”和“响应快”是从应用负载的视角来考察性能，直接影响了产品终端的用户体验。也正对应着性能优化的两个核心指标——“吞吐”和“延时”。  
&emsp;&emsp;随着应用负载的增加，系统资源的使用也会升高，甚至达到极限。而**性能问题的本质**，就是系统资源已经达到瓶颈，但请求的处理却还不够快，无法支撑更多的请求。性能分析，其实就是找出应用或系统的瓶颈，并设法去避免或者缓解它们，从而更高效地利用系统资源处理更多的请求。  
&emsp;&emsp;**性能分析六个步骤**：  
&emsp;&emsp;（1）选择指标评估应用程序和系统的性能；  
&emsp;&emsp;（2）为应用程序和系统设置性能目标；   
&emsp;&emsp;（3）进行性能基准测试；   
&emsp;&emsp;（4）性能分析定位瓶颈；  
&emsp;&emsp;（5）优化系统和应用程序；  
&emsp;&emsp;（6）性能监控和告警。    
&emsp;&emsp;**建立整体系统性能的全局观**：理解最基本的几个系统知识原理； 掌握必要的性能工具；通过实际的场景演练，贯穿不同的组件。  
&emsp;&emsp;  
&emsp;&emsp; **真正的大神网站：http://www.brendangregg.com/ 以及大神之作《性能之巅：洞悉系统、企业与云计算》**  

&emsp;&emsp;**Brendan Gregg的性能工具图谱**  
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181215212309948.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FjY3oxMjM0NTY=,size_16,color_FFFFFF,t_70)
&emsp;&emsp;工具只是解决问题的手段，关键是真正理解系统背后的原理。  
&emsp;&emsp;  
&emsp;&emsp;**Linux性能优化全解图**  
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181215213245357.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FjY3oxMjM0NTY=,size_16,color_FFFFFF,t_70)
