# 2022最新Java面试题合集
包括 Java 集合、JVM、多线程、并发编程、设计模式、SpringBoot、SpringCloud、Java、MyBatis、ZooKeeper、Dubbo、Elasticsearch、Memcached、MongoDB、Redis、MySQL、RabbitMQ、Kafka、Linux、Netty、Tomcat、Python、HTML、CSS、Vue、React、JavaScript、Android 大数据、阿里巴巴等大厂面试题等、等技术栈！

![image](https://user-images.githubusercontent.com/28288225/156381520-170ef8d5-14b8-4ba9-b5cd-dd6192f65207.png)



## Java集合容器

1. 什么是集合
2. 集合的特点
3. 集合和数组的区别
4. 使用集合框架的好处
5. 常用的集合类有哪些？
6. List，Set，Map三者的区别？
7. 集合框架底层数据结构
8. 哪些集合类是线程安全的？
9. Java集合的快速失败机制 “fail-fast”？
10. 怎么确保一个集合不能被修改？

 ......

![image](https://user-images.githubusercontent.com/28288225/156195686-85479839-bae2-454b-94f1-e71f8c033cd1.png)



## Java多线程

1. 多线程有什么用？
2. 线程和进程的区别是什么？
3. Java 实现线程有哪几种方式？
4. 启动线程方法 start()和 run()有什么区别？
5. 怎么终止一个线程？如何优雅地终止线程？
6. 一个线程的生命周期有哪几种状态？它们之间如何流转的？
7. 线程中的 wait()和 sleep()方法有什么区别？
8. 多线程同步有哪几种方法？
9. 什么是死锁？如何避免死锁？
10. 多线程之间如何进行通信？

 ......

![image](https://user-images.githubusercontent.com/28288225/156366515-86263728-2ae8-4515-a67a-3bf65fa63a78.png)



## Java并发编程

1. 为什么要使用并发编程
2. 多线程应用场景
3. 并发编程有什么缺点
4. 并发编程三个必要因素是什么？
5. Java 程序中怎么保证多线程的运行安全？
6. 并行和并发有什么区别？
7. 什么是多线程
8. 多线程的好处
9. 多线程的劣势
10. 线程和进程区别 

 ......

![image](https://user-images.githubusercontent.com/28288225/156195977-1e5041f6-500a-487a-a1c5-467485a04db8.png)



## JVM虚拟机

1. 我们开发人员编写的Java代码是怎么让电脑认识的
2. 为什么说java是跨平台语言
3. Jdk和Jre和JVM的区别
4. 说一下 JVM由那些部分组成，运行流程是什么？
5. 说一下 JVM 运行时数据区
6. 详细的介绍下程序计数器？（重点理解）
7. 详细介绍下Java虚拟机栈?（重点理解）
8. 你能给我详细的介绍Java堆吗?（重点理解）
9. 能不能解释一下本地方法栈？
10. 能不能解释一下方法区（重点理解） 

 ......

![image](https://user-images.githubusercontent.com/28288225/156195843-9dbb021e-c545-4041-8032-ae726e106390.png)



## Tomcat

1. Tomcat的缺省端口是多少，怎么修改？
2. Tomcat 有哪几种Connector 运行模式(优化)？
3. Tomcat 有几种部署方式？
4. Tomcat容器是如何创建servlet类实例？用到了什么原理？
5. Tomcat 如何优化？
6. Tomcat 内存调优
7. Tomcat 垃圾回收策略调优
8. Tomcat 共享session处理
9. Tomcat 添加JMS远程监控
10. 专业点的分析工具有

 .....
 
 ![image](https://user-images.githubusercontent.com/28288225/156371973-2107ecc5-1e0a-492f-aa78-a80dce8b9777.png)

 

## MySQL

1. MySQL 中有哪几种锁？
2. MySQL 中有哪些不同的表格？
3. 简述在MySQL 数据库中 MyISAM 和InnoDB 的区别
4. MySQL 中InnoDB 支持的四种事务隔离级别名称
5. CHAR 和VARCHAR 的区别？
6. 主键和候选键有什么区别？
7. myisamchk 是用来做什么的？
8. 如果一个表有一列定义为TIMESTAMP，将发生什么？
9. 你怎么看到为表格定义的所有索引？
10. 列对比运算符是什么？

 ......

![image](https://user-images.githubusercontent.com/28288225/156369431-d6fc1001-04c2-4401-bb94-8219b6fe1133.png)



## Memcached

1. Memcached是什么，有什么作用？
2. Memcached服务分布式集群如何实现？
3. Memcached服务特点及工作原理是什么？
4. 简述Memcached内存管理机制原理？
5. Memcached是怎么工作的？
6. Memcached最大的优势是什么？
7. Memcached和MySQL的querycache相比，有什么优缺点？
8. memcached和服务器的local cache（比如PHP的APC、mmap文件等）相比，有什么优缺点？
9. memcached的cache机制是怎样的？
10. memcached如何实现冗余机制？

 ......
 
 ![image](https://user-images.githubusercontent.com/28288225/156371445-943789a9-a557-4184-b9ac-32b5a0886b2d.png)



## Redis

1. 什么是Redis？
2. Redis有哪些优缺点？
3. 使用redis有哪些好处？
4. 为什么要用 Redis / 为什么要用缓存
5. 为什么要用 Redis 而不用 map/guava 做缓存?
6. Redis为什么这么快
7. Redis有哪些数据类型
8. Redis的应用场景
9. Redis持久化
10. Redis 的持久化机制是什么？各自的优缺点？

 ......

![image](https://user-images.githubusercontent.com/28288225/156370431-9878cbb8-8cce-45bb-9af7-1ea3684d672f.png)



## elasticsearch
1. elasticsearch 了解多少，说说你们公司 es 的集群架构，索引数据大小，分片有多少，以及一些调优手段 
2. elasticsearch 的倒排索引是什么
3. elasticsearch 索引数据多了怎么办，如何调优，部署
4. elasticsearch 是如何实现 master 选举
5. 详细描述一下 Elasticsearch 索引文档的过程
6. 详细描述一下 Elasticsearch 搜索的过程？
7. Elasticsearch 在部署时，对 Linux 的设置有哪些优化方法
8. ucence 内部结构是什么？
9. Elasticsearch 是如何实现 Master 选举的？
10. Elasticsearch 中的节点（比如共 20 个），其中的10 个选了一个 master，另外 10 个选了另一个 master，怎么办？


 ......


![image](https://user-images.githubusercontent.com/28288225/156193359-35dd56c6-6e45-4e4b-86c3-0a11d20cb9f5.png)



## ZooKeeper

1. ZooKeeper 是什么？
2. ZooKeeper 提供了什么？
3. Zookeeper 文件系统
4. ZAB 协议？
5. 四种类型的数据节点 Znode
6. Zookeeper Watcher 机制 -- 数据变更通知
7. 客户端注册 Watcher 实现
8. 服务端处理 Watcher 实现
9. 客户端回调 Watcher
10. ACL 权限控制机制

 ......

![image](https://user-images.githubusercontent.com/28288225/156370937-966972e9-9e4d-43c9-beac-3923be600396.png)



## Dubbo
1. 为什么要用 Dubbo？
2. Dubbo 是什么？
3. Dubbo 的使用场景有哪些？
4. Dubbo 核心功能有哪些？
5. Dubbo 核心组件有哪些？
6. Dubbo 服务器注册与发现的流程？
7. Dubbo 的整体架构设计有哪些分层?
8. Dubbo Monitor 实现原理？
9. Dubbo 类似的分布式框架还有哪些？
10. Dubbo 和 Spring Cloud 有什么关系？

 ......

![image](https://user-images.githubusercontent.com/28288225/156194115-4af3991d-6ce5-45e2-86e1-8969c4503bf1.png)




## RocketMq

1. RocketMq 是什么
2. RocketMq 有什么功能
3. RoctetMq 架构
4. RocketMq 消息模型（专业术语）
5. 核心问题
  1. 顺序消息
  2. 消息过滤
  3. 消息去重
  4. 分布式事务消息
  5. 消息的可用性
  6. 刷盘实现
  7. 负载均衡

 ......
 
 ![image](https://user-images.githubusercontent.com/28288225/156373436-8eabadf2-cf11-4423-8d36-8da9d87b6ccb.png)

 
 
## Kafka

1. Kafka 架构
2. Kafka 基础概念
3. Kafka Rebalance (重平衡)
4. 日志索引
5. 高性能, 高吞吐
  1. 分区的原因
  2. 顺序写
  3. 批发送
  4. 数据压缩
  5. Page Cache & MMap
  6. Page Cache
  7. MMap (Memory Mapped Files, 内存映射文件)


 ......

![image](https://user-images.githubusercontent.com/28288225/156374041-5a238c04-75b5-4de2-b537-8c92ed097e85.png)




## RabbitMQ

1. 什么是MQ
2. MQ的优点
3. 解耦、异步、削峰是什么？
4. 消息队列有什么缺点
5. 你们公司生产环境用的是什么消息中间件？
6. Kafka、ActiveMQ、RabbitMQ、RocketMQ 有什么优缺点？
7. MQ 有哪些常见问题？如何解决这些问题？
8. 什么是 RabbitMQ？
9. Rabbitmq 的使用场景
10. RabbitMQ基本概念

 ......
 
![image](https://user-images.githubusercontent.com/28288225/156374538-d0d42a57-34e7-4ded-b6b8-ae84d216b148.png)



## Netty

1. Netty
2. I/O 模式
3. I/O 多路复用
  1. select
  2. poll
  3. epoll
4. Java 的 I/o
5. Netty 线程模型和 Reactor 模式
6. Echo服务
7. 源码剖析

 ......
 

 ![image](https://user-images.githubusercontent.com/28288225/156383064-d7eb4ae0-ef67-4b73-ac32-5adf36608492.png)

 


---

![qrcode_for_gh_7612c42dcad3_258](https://user-images.githubusercontent.com/28288225/156195397-8e97e523-a5e8-4327-8b35-cefc081e3ba8.jpg)

关注公众号，回复**面试题**获取
