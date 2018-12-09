# Project: vagrant
 ## todo: vagrant 基础知识
 ## todo: vagrant 构建虚机
 ## todo: vagrant 创建集群


# Project: 算法
 ## 覃超: 数据结构与算法之美
 ## leetcode
 [leetcode](https://leetcode.com/problems/linked-list-cycle/)  
 ##
[csdn 算法博客](https://blog.csdn.net/MBuger/article/details/70259940)  
[各种语言的算法实现](https://rosettacode.org/wiki/Category:Elixir)  
[斐波那契数列算法及时间复杂度分析
](https://blog.csdn.net/ecjtu_yuweiwei/article/details/47282457)  
[以下计算斐波那契数列的函数时间复杂度为](https://www.nowcoder.com/questionTerminal/fd57dad14d224881a929d6739741fe50)  
[斐波那契数列数列的三种时间复杂度的实现方法
](https://blog.csdn.net/u012684062/article/details/76330075)  
[递归时间复杂度](https://www.cnblogs.com/youxin/p/3284089.html)  


# Project: 面试
[谈谈如何准备找工作](https://segmentfault.com/a/1190000011275849)  
[程序员价值最大化 - 如何在面试中脱颖而出](https://segmentfault.com/l/1500000010412102)  
[亚马逊资深面试官教你如何面试](https://segmentfault.com/l/1500000010991087)  
[系统设计面试指南-如何做好系统设计面试](https://segmentfault.com/l/1500000015156310)  
[算法面试指南-如何做好算法面试](https://segmentfault.com/l/1500000015156212)  

# Elixir&&Phoenix  
- [phoenix lessions](http://phoenix.thefirehoseproject.com/11.html)  

- [dave tomas elixir](https://www.youtube.com/watch?v=KQwEmdOH-GM)  

## awesome elixir phoenix
- [Advantages of Elixir vs Golang
](https://www.cogini.com/blog/advantages-of-elixir-vs-golang/)  
- [elixirnation](https://elixirnation.io/tools/obelisk-static-site-generator-for-elixir-like-jekyll)  
- [Coherence and ExAdmin - Devise and ActiveAdmin for Phoenix](http://www.akitaonrails.com/2016/12/06/coherence-and-exadmin-devise-and-activeadmin-for-phoenix)  
- [GENERATING HTML AND JSON SCAFFOLD WITH PHOENIX 1.3 (1.3.2) GENERATORS](https://www.kickinespresso.com/posts/generating-html-and-json-scaffold-with-phoenix-1-3-1-3-2-generorators)  
- [Getting Started With Phoenix: Building a Scaffolded CRUD App
](http://nithinbekal.com/posts/elixir-phoenix-crud-app/)  
- [一家it服务公司- 很有意思的是他们使用phoenix且有自己的blog](https://www.kickinespresso.com/#blog)  
- [小白elixir -作者废话连篇](https://joyofelixir.com/toc.html)  
- [荣锋亮的phoenix博客](https://www.cnblogs.com/rongfengliang/p/8873422.html)  
- [rong fengliang github](https://github.com/rongfengliang?tab=repositories)  
- [elixirchina](https://www.cnblogs.com/rongfengliang/p/8873422.html) 
- [使用elixir phoenix手撸rubychina](https://github.com/zven21/mipha)  
- [用 Elixir/Phoenix 撸了一个 RubyChina.
](https://www.v2ex.com/t/472072)  

# 准备 
- 职位: 架构师/资深研发/全栈工程师
- 行业: 金融/教育/医疗
- 面试点: 分布式/高并发/缓存/SQL/网关/容错/容灾/服务降级/监控/雪崩/DDD/负载/nginx/rabbit/es/kafka/redis/中台/大数据/低延迟/restful设计/系统设计/注册中心/配置中心/k8s/docker/devops/中台/设计模式/秒杀/重试/连接超时/静态分析/测试/TDD/多线程/异步io/非阻塞/分布式容错/分布式一致性/熔断/鲁棒性 稳定性/协议/网络协议/重连/弹性伸缩/集群哨兵/中台架构/分库分表设计与上线/jvm/GC/设计模式/io nio/安全/高性能/语言特性: 泛型, lambda 基础类库:集合 io/nio 网络 安全 并发

类加载过程: 加载 验证 链接 初始化
常见垃圾收集器: SeiralGC ParallelGC CMS G1 适用于什么样的工作负载

面试官的刨根问底法: 看面试人的对知识点的掌握程度

[ClassNotFoundException vs. NoClassDefFoundError](https://dzone.com/articles/java-classnotfoundexception-vs-noclassdeffounderro)  

ClassNotFoundException is an exception that occurs when you try to load a class at run time using Class.forName() or loadClass() methods and mentioned classes are not found in the classpath.

NoClassDefFoundError is an error that occurs when a particular class is present at compile time, but was missing at run time.

try-with-resources

throw early, catch late

反应变慢，吞吐下降，查看是否频繁的exception
异步编程中的promise future对异常的处理机制
业务功能模块分配id

四种引用 强、软、弱、幻想引用 对象的可达性与垃圾回收的影响
强引用Strong 普通对象引用 赋值null
软引用Soft  强引用的弱化 可以使得对象豁免垃圾回收 在内存敏感时的缓存，会保证内存可用，释放弱引用对象，保证不耗尽内存。
弱引用 Weak  如果对象存在就访问，不在就重新实例化，也同样是缓存实现的选择。  
幻想引用 或者虚引用  不能通过它访问对象,提供了确保对象被finalize后能做某些事情的机制. 可用来监控对象的创建和销毁

mysql的 connector-j 驱动在特定模式下(useCompression=true)的内存泄露问题,就需要我们理解怎么排查幻想对象的堆积问题。  





- 谦虚/自信/善于沟通
- 非特定语言
- n+1 / error / exception / 读写分离 主从
# company
[firehouse](http://blog.thefirehoseproject.com/posts/category/career-advice/)  


# design
- [秒杀系统优化方案之缓存、队列、锁设计思路](https://segmentfault.com/a/1190000008888926)  
- [演讲实录：使用 Go 开发秒杀系统的实践](http://blog.shurenyun.com/untitled-7/)    
- [基于可靠消息最终一致性分布式事务框架
](https://github.com/yu199195/myth)    
- [服务器压力测试工具设计](https://blog.csdn.net/MBuger/column/info/28555)  

10亿级订单系统分库分表设计思路！ https://juejin.im/entry/5ba59ef8e51d450e616015f7
分库分表后如何部署上线？ https://segmentfault.com/a/1190000016475827
MySQL分库分表单库分表和迁移数据(4th) https://cn.aliyun.com/jiaocheng/455029.html 


# prepare
- java核心技术36讲 重点复习
- java base && java cheatsheet 见java-cheatsheet.md
- java 最佳实践 如何写出优雅高效的代码 sf aws复习
- jvm
- concurrent collection
- spring factory ioc aop
- mysql 慢查询 分库分表
- 设计模式
- spring cloud 组件

直接看面试要点 


- ddd
- TDD
- 分布式 高并发设计
- 如何设计一个秒杀系统
- 如何设计缓存系统
- 高可用 高性能 高并发 伸缩 弹性 一致性
- nginx 代理
- redis设计
- mongo
