<h1>2021年最新整理，名企校招(含技术细节)Python自动化测试岗位。持续更新中...</h1>

-----------
### 1 数据结构与算法

#### 1.1 常用数据结构与算法

* 算法复杂性分析
* 线性表、链表数据结构详解
* 队列、栈结数据结构详解
* 基础排序算法详解
* 数论&枚举&递归&分治&回溯思想详解
* 贪心算法与动态规划
* 快排与归并排序详解
* 二分搜索、哈希表详解
* 并查集算法详解
* 树，基本概念，二叉树(遍历)，红黑树详解
* B树，Trie树，赫夫曼树，堆树详解
* 图论、深度优先遍历、广度优先遍历详解
* 最小生成树、最短路径详解
* 布隆过滤器与位图详解

### 2 Java基础

#### 2.1 Java基础知识

* Java语言的特点
* 面向对象与面向过程对比
* Java平台的三个版本J2EE、J2SE、J2ME
* JDK、JRE、JVM之间的区别于关系
* Java环境变量
* javac命令和java命令
* 字节码，采用字节码的好处
* import java和javax的区别
* Java和C++的区别
* Java数据类型
* Java访问修饰符
* 字符型常量和字符串常量的区别
* 面向对象编程三大特性:封装、继承、多态
* 接口和抽象类的区别
* 重载和重写的区别
* java对象
* java引用

#### 2.2 Java异常

*  Java异常处理
*  Runtime Exception与Error

#### 2.2 Java反射

*  java反射概念
*  java反射(Reflection)的底层实现原理
*  创建反射实例
*  反射中,Class.forName和classloader的区别
* 序列化与反序列化

#### 2.3 java拷贝

* 浅拷贝与深拷贝
* 拷贝的几种方法

#### 2.4 多线程与并发

* 进程与线程
* 并发与并行
* Thread和Runnable

#### 2.5 Java容器及底层实现

* Collection
* Set
* SortedSet
* HashSet
* TreeSet
* Iterator
* ListIterator
* List
* Vector
* Stack
* ArrayList
* LinkedList
* Map
* SortedMap
* TreeMap
* HashMap
* Hashtable

### 3 性能调优专题

#### 3.1 Jvm性能调优

##### 3.1.1 JVM类加载机制详解

* 从JDK源码(C++)级别深度剖析类加载全过程
* 启动类、扩展类、应用程序类加载器源码深度剖析
* 类加载双亲委派机制及如何打破详解
* 手写自定义类加载器
* Tomcat类加载机制源码剖析

##### 3.1.2 JVM内存模型

* 堆内存分代机制及对象生命周期详解
* 线程栈及栈帧内部结构详解
* 方法区(元空间)及常量池详解(深入到Hotspot底层C++级别解析)
* 程序计数器详解
* 本地方法栈详解

##### 3.1.3 类字节码文件深度剖析

* 数据类型
  * 无符号数
  * 表
* 组成
  * 0~3字节：魔数：文件类型
  * 4~7字节：jdk本号
  * 常量池
    * 字面量：常量字符串、final常量值
    * 符号引用
      * 类和接口的fully Qualified Name
      * 字段的方法和描述符
      * 方法的名称和描述符
  * u2访问标志：类/接口、public、final、abstract
  * 继承关系
    * u2类索引：类的全限定名
    * u2父索引：父类的全限定名
    * nu2+1接口索引：实现接口的全新定名
  * 字段表集合：描述接口、变量
    * u2访问标志
    * u2 name_index
    * u2 descriptor_index
    * u2 attributes_count
    * u2 attributes
  * 方法表集合：描述方法
  * 属性表集合
    * code属性
    * exception属性
    * LineNumberTable属性
    * LocalVariableTable属性
    * sourceFile属性
    * constantvalue属性：通知虚拟机自动为静态变量赋值
    * innerClass属性
    * Deprecated和Synthetic属性
    * stackMapTable属性
    * Signature属性：记录泛型信息
    * BootstrapMethod属性

##### 3.1.4 垃圾收集机制详解

* 垃圾收集算法详解
  * 标记清除算法详解
  * 复制算法详解
  * 标记整理算法详解
  * 分代垃圾收集算法详解
* 复制垃圾收集机制详解
  * 垃圾收集三色标记算法详解
  * 对象漏标解决方案增量更新与原始快照(SATB)详解
  * 读写内存屏障实现原理剖析(深入到Hotspot底层C++级别解析)
  * 记忆集(Remember Set)与卡表(Cardtable)详解
  * ZGC底层颜色指针详解

##### 3.1.5 十种垃圾收集器详解

* Serial垃圾收集器详解
* ParNew垃圾收集器详解
* Parallel垃圾收集器详解
* CMS垃圾收集器详解
* G1垃圾收集器详解(深入到Hotspot底层C++级别解析)
* ZGC垃圾收集器详解
* Epsilon与Shenandoah垃圾收集器详解

##### 3.1.6 JVM调优工具详解

* JDK自带Jstat、Jinfo、Jmap、Jhat及Jstack调优命令详解
* Jvisualvm、Jconsole调优工具详解
* 阿里巴巴JVM调优工具Arthas详解

##### 3.1.7 GC日志详细分析

* GCEasy日志分析工具使用
* GCViewer日志分析工具使用

##### 3.1.8 JVM调优实战

* 日均百万交易系统JVM堆栈大小设置策略与调优
* 亿级流量电商系统堆内年轻代与老年代垃圾回收参数设置与调优
* 高并发系统如何基于G1垃圾回收器优化性能
* 每秒10万并发的秒杀系统为什么会频繁发生GC
* 电商大促活动时，严重Full GC导致系统直接卡死的优化实战
* 线上生产系统OOM监控及定位与解决

#### 3.2 Mysql性能调优

##### 3.2.1 SQL执行原理详解

* 连接器详解
* 分析器详解
* 优化器详解
* 执行器详解
* Innodb的Buffer Pool机制详解
* Redo重做日志、Undo回滚日志与Binlog详解

##### 3.2.2 索引底层剖析

* 数据结构角度
  * B+树索引
    * 索引查找步骤
    * 索引选择
    * 联合索引
  * Hash索引
  * FULL TEXT索引
* 物理存储角度
  * 聚簇索引
  * 非聚簇索引
* 逻辑角度
  * 主键索引
  * 唯一索引
  * 单列索引
  * 多列索引
* 索引使用角度
  * 覆盖索引
  * 索引下推

##### 3.2.3 执行计划与SQL优化

* explain工具深度使用
* 阿里巴巴索引优化最佳实践

##### 3.2.4 Mysql锁机制与事务隔离级别详解

* Mysql锁
  * 性能
    * 乐观锁
    * 悲观锁
  * 操作
    * 读锁
    * 写锁
  * 粒度
    * 表锁
    * 行锁
  * 其它
    * 间隙锁
    * 临键锁
  * 死锁以及优化解决
* 事务隔离级别
  * 读未提交
  * 读已提交
  * 可重复读
  * 串行化
* MVCC多版本并发控制机制详解
  * Undo版本链
  * 事务一致性视图ReadView
  * 实现
    * Read Committed级别实现原理
    * Repeated Read级别实现原理

#### 3.3 Tomcat调优

##### 3.3.1 整体认知Tomcat项目架构

* 理解Tomat启动流程
* 理解对Http请求解析与处理流程
* 核心组件认知
  * wrapper
  * context
  * host
  * engine
  * container
* Tomcat 8 与Tomcat7 对比

##### 3.3.2 生产环境配置

* Tomcat server.xml 配置详解 
* Tomcat集群与会话复制方案实现
* Tomcat虚拟主机配置

##### 3.3.3 掌握Tomcat线程模型背后原理

* Tomcat 支持四种线程模型介绍 
* 通过压测演示Nio与 Bio模型的区别
* Tomcat Bio实现源码解读
* Tomcat Nio 实现源码解读
* Tomcat connector 并发参数解读

#### 3.4 Nginx调优

##### 3.4.1 Nginx快速掌握

* 核心模块
* 标准Http模块
* 可选Http模块
* 第三方模块
* nginx 事件驱动模型及特性

##### 3.4.2 熟练掌握Nginx核心配置

* 基本配置
* 虚拟主机配置
* upstream
* location
* 静态目录配置

##### 3.4.3 掌握Nginx负载算法配置

* 轮循+权重
* ip hash
* url hash
* least_conn
* least_time

### 4 并发编程专题

#### 4.1 操作系统内核原理

* 进程管理详解
* 内存管理详解
* 文件系统详解
* IO输入输出系统详解
* 进程间通信机制详解
* 网络通信原理剖析

#### 4.2 阻塞队列

* ArrayBlockingQueue 数组有界队列详解
* ConcurrentLinkedQueue 链表无界队列详解
* PriorityBlockingQueue 优先级排序无界队列详解
* DelayQueue 延时无界队列详解
* SynchronousQueue详解
* LinkedBlockingDeque详解

#### 4.3 java内存模型

##### 4.3.1 线程通信机制

* 内存共享
* 消息传递

##### 4.3.2 内存模型

* 重排序
* 顺序一致性
* happens-before
* as-if-serial
* 双重检查锁
* final内存语义

##### 4.3.3 synchronized

* 锁对象
  * 普通同步方法，锁是当前实例对象
  * 静态同步方法，锁是当前类的class对象
  * 同步方法块，锁是括号里面的对象
* 实现机制
  * Java对象头
  * monitor
* 锁优化
  * 轻量级锁
  * 重量级锁
  * 锁消除
  * 锁粗化
  * 偏向锁
* 使用方式
  * 普通同步方法，锁是当前实例对象
  * 静态同步方法，锁是当前类的class对象
  * 同步方法块，锁是括号里面的对象

##### 4.3.4 volatile

* 原子性
* 可见性
* 禁止重排序
* 实现机制

#### 4.4 线程池

##### 4.4.1 Executors

* newCachedThreadPool
* newFixedThreadPool
* newScheduledThreadPool
* newSingleThreadExecutor

##### 4.4.2 ThreadPoolExecutor

* 构造参数含义
* 任务提交
* 任务执行
* 线程池调优
* 线程池监控
* 底层原理实现

##### 4.4.3 ScheduledThreadPoolExecutor

* 构造参数含义
* 底层原理实现
* 日常开发注意问题

##### 4.4.4 Future

* 异步计算
* FutureTask
* 内部基于AQS实现

##### 4.4.5 线程间通信

* 内存共享
* 线程之间共享程序的公共状态,通过读和写内存中的公共状态进行隐式通信
* 线程之间必须通过发送消息来现实进行通信

#### 4.5 并发集合

* ConcurrentHashMap原理、源码、实战详解
* ConcurrentLinkedQueue原理、源码、实战详解
* ConcurrentSkipListMap原理、源码、实战详解
* ConcurrentSkipListSet原理、源码、实战详解
* ArrayList、LinkedList与CopyOnWriteArrayList详解
* HashMap与ConcurrentHashMap源码剖析
* Set与CopyOnWriteArraySet详解

#### 4.6 原子操作

##### 4.6.1 基本类型

* AtomicInteger:原子更新整形类型
* AtomicLong:原子更新长整型类型
* AtomicBoolean:原子更新boolean类型

##### 4.6.2 数组

* AtomicIntegerArray:原子更新整形数组里的元素
* AtomicLongArray:原子更新长整型数组里的元素
* AtomicReferenceArray:原子更新引用类似数组里的元素

##### 4.6.3 引用类型

* AomicRefernce:原子更新引用类型
* AtomicReferenceFieldUpdater:原子更新引用类型里的字段
* AtomicMarkableReference:原子更新带有标记为的引用类型

##### 4.6.4 字段类型

* AtomicIntegerFieldUpdater:原子更新整形的字段的更新器
* AtomicLongFieldUpdater:原子更新长整型字段的更新器
* AtomicStampedReference:原子更新电邮版本号的引用类型

### 5 框架源码专题

#### 5.1 应用框架Spring

##### 5.1.1 Spring IOC源码剖析

* 整体认知spring 体系结构
* 理解Spring IOC 容器设计原理
* 掌握Bean生命周期
 * 初始化InitializingBean/@PostConstruct
 * Bean的后置处理器BeanPostProcessor源码分析
 * 销毁DisposableBean/@PreDestroy
* Spring Context 装载过程源码分析
 * BeanFactoryPostProcessor源码分析
 * BeanDefinitionRegistryPostProcessor源码分析
* Spring IOC 循环依赖问题源码深度剖析
* Factorybean与Beanfactory区别

##### 5.1.2 Spring Aop源码剖析

* 掌握Spring AOP 编程概念
* AOP注解编程
 * @EnableAspectJAutoProxy
 * @Before/@After/@AfterReturning/@AfterThrowing/@Around
 * @Pointcut
* 基于Spring AOP 实现应用插件机制
* Spring AOP源码分析
 * ProxyFactory源码解析
 * AOP代理源码解析
 * 拦截器链与织入源码解析
* Spring事务控制与底层源码分析
 * @EnableTransactionManagement源码剖析
 * @Transactional源码剖析

##### 5.1.3 Spring MVC源码剖析

* 理解MVC设计思想
* 从DispatchServlet 出发讲述MVC体系结构组成
* 基于示例展开DispatchServlet 核心类结构
* MVC初始化及执行流程源码深度解析
* RequestMaping源码实现解析
* 熟悉MVC组件体系
 * 映射器原理实现
 * 执行适配器原理实现
 * 视图解析器原理实现
 * 异常捕捉器原理实现

##### 5.1.4 Spring注解式开发

* @Bean/@ComponentScan/@Configuration/@Conditional
* @Component/@Service@/Controller/@Repository
* @Lazy/@Scope/@Import/@Value/@Profile
* @Autowired/@Resources/@Inject

##### 5.1.5 Spring 5新特性

* 新特性详解
* 响应式编程模型
* 函数式风格的ApplicationContext
* Kotlin表达式的支持
* SpringWebFlux模块讲解

##### 5.1.6 Spring Security原理与源码剖析

* 快速入门与高级应用
* 核心安全过滤器源码剖析
* 会话管理源码剖析
* 命名空间配置源码剖析
* 授权体系结构源码剖析
* Outh1.0与Outh2.0协议详解

##### 5.1.7 Spring Webflux详解

* Webflux快速入门
* 响应式编程实战
* JDK响应式流编程实战
* Reactive Stream 响应式流详解
* Webflux服务端开发详解
* Webflux客户端声明式rest client框架开发讲解

#### 5.2 ORM框架MyBatis

##### 5.2.1 MyBatis快速掌握

* MyBatis、Hibernate及传统JDBC对比
* Mybatis全局参数详解
* 详解configuration 、properties、 settings、 typeAliases、 mapper
* 掌握xml和annotations和Criteria差异

##### 5.2.2 Mybatis源码分析

* 整体认识mybatis源码结构
* Mybatis核心应用配置与原理解析
* Spring与MyBatis集成源码剖析
* Configuration、Mapper、SqlSession、Executor源码解析

##### 5.2.3 Mybatis徒手实现

* 熟悉MyBatis内部运行机制
* 熟悉MyBatis初始化过程
* 源码debug一行行详细讲解
* MyBatis二级缓存应用
* 手写实现一套mybatis框架

### 6 分布式框架专题

#### 6.1 分布式消息中间件

##### 6.1.1 Rabbitmq

* RabbitMq概述与集群高可用环境搭建
* RabbitMq工作模式深度详解
* RabbitMq路由机制与镜像机制
* RabbitMq消息防丢失与削峰限流
* 死信队列与延时队列详解
* 消息防重复消费与消息积压快速处理
* RabbitMq与Spring、Springboot整合

##### 6.1.2 RocketMq

* 解密RocketMq集群部署与快速入门
* 深入分析RocketMq模块划分与集群原理讲解
* 详解普通消息、顺序消息、事务消息、定时消息
* 深入RocketMq Broker、Consumer、Producer源码剖析
* 详解RocketMq监控与运维
* 企业实战RocketMq消息中间件API架构开发

##### 6.1.3 Kafka

* Kafka发展介绍与对比
* Kafka集群搭建与使用
* Kafka副本机制与选举原理详解
* Kafka架构设计原理分析
* 基于Kafka的大规模日志系统实现原理分析
* 亿级流量生产系统Kafka性能优化最佳实践

#### 6.2 分布式储存中间件

##### 6.2.1 Redis

* Redis核心数据结构剖析
* Redis在微博，微信及电商场景典型应用实践
* Redis持久化机制与安全机制详解
* Redis主从及哨兵架构详解
* Redis Cluster集群架构实战及原理剖析
* 集群数据分片算法及动态水平扩容详解
* Jedis、Redisson客户端源码剖析
* Redis高并发分布式锁实战
* Redis缓存穿透，缓存失效，缓存雪崩实战解析
* Redis布隆过滤器实现
* Redis缓存设计与性能优化

##### 6.2.2 MongoDB

* MongoDB基础概念数据库、集合、索引及文档详解
* MongoDB高可用集群搭建实战
* MongoDB性能优化最佳实践

##### 6.2.3 FastDFS

* FastDFS应用背景和原理介绍
* FastDFS文件存储项目实战
* FastDFS分布式部署实战

##### 6.2.4 Elasticsearch

* ElasticSearch快速入门实战与底层原理剖析
* DSL高级语法与高可用架构实战
* ElasticSearch集群架构原理与源码剖析
* ElasticSearch数据建模与性能调优
* ELK、FileBeat企业级架构与面试剖析
* 亿级流量电商系统搜索实战

#### 6.3 分布式框架

##### 6.3.1 Zookeeper

* Zookeeper快速入门
* Zookeeper多节点集群部署实战
* Zookeeper典型应用场景实战
 * 服务注册与订阅
 * 分布式配置中心
 * 分布式锁
* Zookeeper中znode、watcher、ACL、客户端API详解
* Zookeeper客户端服务端源码剖析
* Zookeeper集群leader选举源码剖析
* Zookeeper集群ZAB协议源码剖析
* Zookeeper迁移、扩容、监控详解

##### 6.3.2 Dubbo

* Dubbo框架介绍与手写模拟Dubbo
* Dubbo的基本应用与高级应用
* Spring与Dubbo整合原理与源码分析
* Dubbo的可扩展机制SPI源码解析
* Dubbo容错机制与高扩展性分析
* Dubbo RPC协议底层原理与实现
* Dubbo服务导出源码解析
* Dubbo服务引入源码解析
* Dubbo服务调用源码解析
* Dubbo负载均衡源码解析

##### 6.3.3 ShardingSphere

* 数据读写分离及分库分表场景详解
* 常见数据分片算法hash、list、range、tag详解
* 常见数据库中间件Mycat和ShardingSphere对比
* 解密Sharding-jdbc核心概念与快速开始
* 深入Sharding-jdbc特性详解与模块划分
* 实战订单交易中orders和ordersItem分库分表开发
* 深入Sharding-jdbc源码之sql解析、sql路由、sql改写、sql执行、结果合并

##### 6.3.4 Netty

* 网络与IO模型基础进阶
 * HTTP请求与响应格式详解
 * HTTP重定向与转发详解
 * Cookie机制详解
 * HTTP缓存控制与代理服务详解
 * HTTPS 与 SSL/TLS详解
 * 对称加密与非对称加密、数字签名与证书详解
 * 七层网络协议详解
 * ТСР协议与流量控制详解
 * TCP协议可靠性是如何保障的
 * Socket与文件描述符详解
 * Socket与Tcp协议、Http协议的关系
 * Socket底层实现原理详解 
* BIO、NIO及AIO线程模型详解
* Netty线程模型及源码剖析
* 高性能序列化协议protobuf及源码分析
* 粘包拆包现象及解决方案、编解码器源码分析
* Netty心跳机制源码剖析
* 直接内存与Netty零拷贝详解
* Netty之Http协议开发应用实战（仿斗鱼弹幕系统实现）
* Netty之WebSocket协议开发应用实战（贪吃蛇多人联机网游实现）

#### 6.4 微服务系列专题

##### 6.4.1 微服务架构变迁史

* 淘宝电商微服务架构变迁史
* 京东电商微服务架构变迁史

##### 6.4.2 Spring Boot详解及源码剖析

* Spring boot 快速开始及核心配置详解
* Spring boot 部署方式及热部署详解
* Web开发模板引擎Thymeleaf及Freemarker详解
* Spring Boot集成Mybatis，Redis，RabbitMq等三方框架
* Spring Boot启动过程源码分析
* Spring Boot自动装配源码分析

##### 6.4.3 Spring Cloud Alibaba详解及源码剖析

###### 6.4.3.1 Nacos 注册中心详解及源码分析

* 服务注册与发现详解及源码剖析
* 服务心跳与下线详解及源码剖析
* 服务健康检查详解及源码剖析
* Nacos集群架构实战及源码剖析
* Nacos集群节点间服务数据同步详解及源码剖析
* Nacos集群架构CAP原理详解
  * AP架构详解
  * CP架构详解
    * 集群脑裂问题及解决方案
* Nacos源码高并发设计精髓
  * 防止读写并发冲突CopyOnWrite设计思想
  * 异步任务及内存队列有效提升系统并发
  * 异步批量同步集群节点数据有效提升系统性能
* 阿里云超大规模微服务注册中心设计架构详解

###### 6.4.3.2 Nacos 配置中心实战及源码分析

* Nacos配置中心架构剖析
* Nacos配置中心使用详解
  * 多环境切换及配置共享
    * 支持profile粒度的配置
    * 支持自定义 namespace 的配置
    * 支持自定义 Group 的配置
    * 支持自定义扩展的 DataId 配置
  * 运行时配置动态刷新及服务热加载
  * 高可用分布式配置中心实战
* Nacos Config Client源码分析
  * Client端从配置中心获取配置源码分析
  * Client动态感知配置中心配置变更源码分析
  * Spring整合Nacos实现配置更新源码分析
* Nacos Config Server源码分析
  * 服务端是配置推送源码分析
  * 配置持久化源码分析
  * 集群架构下其他节点同步配置数据源码分析

###### 6.4.3.3 LoadBalancer 客户端负载均衡器实战

* LoadBalancer替换Ribbon配置
* RestTemplate整合LoadBalancer
* WebClient整合LoadBalancer

###### 6.4.3.4 Ribbon 客户端负载均衡详解及源码分析

* Ribbon服务发现及客户端缓存源码剖析
* Ribbon客户端负载均衡源码剖析
  * 轮询策略
  * 随机策略
  * 最小并发策略
  * 响应时间加权策略
  * 重试策略
  * 权重策略
* 自定义扩展Ribbon客户端负载均衡算法
* Ribbon框架源码设计缺陷及优化

###### 6.4.3.5 Feign 声明式服务调用详解及源码分析

* Fegin的设计架构剖析
* Fegin自定义相关配置使用详解
  * 日志配置
  * 契约配置
  * 拦截器配置，自定义拦截器
  * 超时时间配置
  * 客户端组件Apache HttpClient & OkHttp配置
  * GZIP 压缩配置
  * 编码器解码器配置
  * 如何实现Feign到Dubbo的无缝迁移
* Feign 方法参数拼接Http请求源码剖析
* Feign 整合Ribbon源码剖析
* Spring整合Fegin源码剖析

###### 6.4.3.6 Sentinel 限流降级熔断详解及底层源码分析

* 限流源码剖析
  * 限流类型详解及源码剖析
    * QPS限流源码剖析
    * 线程数限流源码剖析
  * 限流模式详解及源码剖析
  * 限流效果详解及源码剖析
    * 请求快速失败
    * 请求预热
    * 请求排队
  * 限流算法详解及源码剖析
    * 计数器限流
    * 滑动时间窗口限流源码剖析
    * 令牌桶限流源码剖析
    * 漏桶限流源码剖析
* 熔断降级源码剖析
  * 服务断路器设计思想及源码剖析
    * 接口平均响应时间超时熔断源码剖析
    * 接口异常比例过高熔断源码剖析
    * 接口异常数过多熔断源码剖析
  * 服务降级注解自动化配置源码剖析
* 热点限流规则源码剖析
  * 秒杀场景指定热点参数限流实现
* 系统负载限流源码剖析
  * 系统级负载Load限流
  * 系统级平均响应时间限流
  * 系统级线程数限流
  * 系统级QPS限流
  * 系统CPU使用率限流
  * 系统黑白名单授权规则限流
* Sentinel网关限流源码剖析
* Sentinel规则持久化实战及其源码分析
  * 原始模式下规则推送的源码分析
  * Sentinel规则持久化扩展点分析
  * Sentinel控制台改造
  * 拉模式实现及其源码分析
    * 动态规则扩展之读写数据源的实现
    * 客户端拉模式规则持久化实战
    * 拉模式改造之整合Spring Cloud
* 推模式实现及其源码分析
  * 基于Nacos配置中心控制台推送规则实战
  * 基于Nacos控制台的推模式持久化源码分析
  * Sentinel控制台改造
  * 基于Sentinel控制台推送规则实战
  * Sentinel推模式整合Spring Cloud
* Spring整合Sentinel源码剖析

###### 6.4.3.7 Seata 微服务分布式事务详解及源码分析

* Seata AT,XA,TCC,Saga区别
* Seata AT模式多数据源，微服务下使用详解
* Seata全局事务注册源码剖析
* Seata分支事务客户端注册源码剖析
* Seata分支事务客户端全局锁冲突自旋设计原理剖析
* Seata分支事务服务端全局锁设计源码剖析
* Seata全局事务提交源码剖析
* Seata全局事务回滚源码剖析
* Seata分支事务第二阶段异步提交源码剖析
* Seata分支事务第二阶段生成反向Sql执行回滚源码剖析
* Spring整合Seata源码剖析

###### 6.4.3.8 Gateway 统一网关详解及源码剖析

* Gateway核心概念和工作原理分析
* Gateway使用详解
  * RoutePredicateFactories路由断言工厂配置
  * RoutePredicateFactories路由断言工厂配置
  * GlobalFilters全局过滤器配置
  * Gateway Cors跨域配置
  * Gateway整合Sentinel限流实战
  * Gateway网关高可用部署
* Gateway扩展
  * 服务动态路由
  * 服务统一限流熔断
  * 服务统一缓存
  * 服务统一授权认证
  * 服务统一性能监控
  * 服务统一灰度发布
* Gateway源码剖析
  * WebFlux核心请求流程分析
  * Gateway整合WebFlux源码分析
  * GateWay路由匹配核心源码分析
  * GateWay请求过滤器链源码分析
  * 整合Ribbon核心源码分析
  * 请求转发到下游微服务源码分析

###### 6.4.3.9 Skywalking链路追踪组件实战

* Skywalking整体架构剖析
* Skywalking使用详解
  * Skywalking OAP&UI服务搭建
  * 告警通知配置
  * 基于mysql/elasticsearch跟踪数据持久化
  * @Trace自定义链路追踪
  * Skywalking集成日志框架
  * Skywalking集群部署
* 进阶扩展：Java Agent实战

###### 6.4.3.10 Spring Security OAuth2微服务安全实战

* 微服务API安全机制详解
* 微服务安全之Oauth2协议详解
  * Oauth2介绍&常用场景分析
  * Oauth2设计思路详解
  * 客户端四种授权模式详解
* 微服务安全之传统Session的认证与授权
* 微服务安全之Token机制的认证与授权
* JWT安全认证方案详解
* 微服务接入网关实现SSO

##### 6.4.4 Spring Cloud Netflix详解及源码剖析

* Eureka服务注册与发现详解及源码分析
* Ribbon 客户端负载均衡详解及源码分析
* Fegin 声明式服务调用详解及源码分析
* Hystrix实现服务限流，降级，熔断详解及源码分析
* Hystrix实现自定义接口降级,监控数据及监控数据聚合
* Zuul统一网关详解，服务路由，过滤器使用及源码分析
* 分布式配置中心Config详解
* 分布式链路跟踪Sleuth详解

### 7 项目实战专题

#### 7.1 亿级流量微服务电商中台

##### 7.1.1 电商核心中台架构整体设计

* 淘宝电商后端架构变迁史
* 京东电商后端架构变迁史
* 阿里小前台大中台架构详解
  * 业务中台
  * 技术中台
  * 数据中台
* 领域驱动模型DDD设计
  * DDD基本概念介绍
  * DDD分层架构与微服务之间的关系
  * DDD与中台架构的关系
  * DDD小范围落地实战

##### 7.1.2 基于Spring Cloud微服务架构拆分

* 会员服务
  * 详解电商平台会员模块介绍、配置详解
  * 详解电商平台会员业务与技术实现
  * 解密电商平台SSO单点跨域详解
  * 解密电商平台会员数据库分库分表
* 商品服务
  * 详解电商平台商品模块介绍、配置详解
  * 详解电商平台商品模块业务与技术实现
  * 解密电商平台商品详细页静态化与缓存
* 订单服务
  * 详解电商平台订单模块介绍、配置详解
  * 详解电商平台订单业务与技术实现
  * 解密订单分布式事务、幂等性、重复消费问题
  * 秒杀库存分布式锁实战
* 支付服务
  * 支付宝支付功能实战
  * 微信支付功能实战
  * 商家对账功能详解
* 营销服务
  * 优惠券功能设计与实现
  * 满减优惠活动设计与实现
  * 团购优惠活动设计与实现
* 后台服务
  * 电商管理后台模块详解
  * 后台系统权限、资源、账号、角色关系及技术实现

##### 7.1.3 电商平台技术解决方案

##### 7.1.3.1 分布式解决方案

* 分布式锁
  * Mysql实现
  * Redis实现
  * Zookeeper实现
* 分布式事务
  * 基于2PC/3PC实现
    * Atomic框架
  * 基于消息队列实现
    * Rabbitmq
    * Rocketmq
  * 基于蚂蚁金服TCC方案实现
    * Tcc-transaction框架
    * Bytetcc框架
  * 基于阿里巴巴Seata方案实现
* 分布式调度中心
  * Quartz框架
  * xxl-job框架
  * TBSchedule框架
* 分布式配置中心
  * 阿里巴巴Nacos框架
  * Spring Cloud Config
  * Apollo框架
* 分布式全局序列号
  * 雪花算法详解与不足详解
  * 基于Redis自研分布式主键ID详解
* 分布式Session
  * Spring Session&JWT实现
* 海量数据分库分表
  * 基于ShardingSphere实战订单分库分表
  * 基于Redis自研分布式主键ID详解
  * 永不扩容的订单表方案实战
* 商品搜索
  * 基于Elasticsearch实战商品搜索
  * 多分类、多品牌、多属性、多规格等分词搜索实战

##### 7.1.3.2 高并发秒杀系统实现

* Redis与JVM多级缓存架构
  * 亿级流量商品详情页Openresty多级缓存架构方案实战
  * 缓存穿透、缓存失效、缓存雪崩及热点缓存重建优化及实战
* 消息中间件流量削峰与异步处理
* 限流策略实现
  * Nginx限流
  * 计数器 
  * 滑动时间窗口 
  * 令牌桶、漏桶算法 
  * Sentinel/Hystrix限流
* 全链路电商压测
  * 基于电商正向流程全链路压测实战
  * 基于逆向流程全链路压测实战
* 性能调优实战
  * 高并发场景JVM GC调优实战
  * 高并发场景Mysql调优实战
  * 高并发场景Tomcat调优实战
  * 高并发场景Nginx调优实战
* 性能监控
  * 监控系统Prometheus使用详解
  * 监控报警系统Grafana图表配置及异常报警
  * Prometheus+Grafana 监控电商系统各项性能指标
* 秒杀商品详细页多级缓存架构实战
  * 基于静态化CDN加速方案详解
  * 基于Redis本地cache方案详解
  * 基于OpenResty lua脚本缓存方案详解
* 秒杀交易全链路架构实战
  * 秒杀下单系统安全防刷策略实现
  * 大促下单高峰服务降级实现详解
  * 订单场景分布式事务实战

##### 7.1.3.3 集群上云

* 虚拟容器技术详解
  * 虚拟服务之Docker
    * Docker的镜像，仓库，容器详解
    * 快速开始搭建Docker环境
    * DockerFile使用详解
    * DockerCompose集成式应用组合
    * Docker服务编排实现
  * Kubernetes容器管理
    * Kubernetes介绍与快速开始
    * Kubernetes对象&Master组件&Node节点详解
    * Kubernetes生产集群环境搭建与使用
  * 电商中台项目云服务部署
    * 项目整体Docker容器化部署
    * 项目整体Kubernetes集群部署
  * 秒杀系统项目云服务部署
    * 项目整体Docker容器化部署
    * 项目整体Kubernetes集群部署

#### 8.2 BAT内部自研分布式调用链中间件

* 分布示调用链简介与发展史
* 调用链平台概要设计
* Javassist、字节码插桩、JavaAGENT
* 埋点采集
  * 采集点为：Dubbo、Jdbc Driver、Spring
  * 采集点为：Tomcat、Http、Redis
* Classloader深入加载机制
* 深入分析调用链中Threadlocal、Threadpool应用
* 分布式环境部署与问题排查

#### 8.3 秒杀系统实现

#### 8.4 拼团系统实现

### 9 互联网工具专题

#### 9.1 Git

* 整体认知GIT体系结构
* Git客户端与服务端快速搭建
* Git的核心命令详解
* Git企业应用最佳实践

#### 9.2 Maven

* Maven生命周期详解
* Maven插件体系详解
* Maven核心命令详解
* Maven的pom配置体系详解
* Nexus私服搭建实战

#### 9.3 Jenkins

* 整体认知Jenkins体系结构
* Jenkins如何做持续集成
* Jenkins搭建及使用详解
* Jenkins插件体系详解

#### 9.4 Linux

* Linux原理、启动、整体架构讲解
* Linux运维常用命令实战
* Linux用户与权限讲解
* Shell脚本编程实战

#### 9.5 虚拟容器

##### 9.5.1 Docker

* Docker的镜像，仓库，容器详解
* 快速开始搭建Docker环境
* DockerFile使用详解
* DockerCompose集成式应用组合
* Docker服务编排实现

##### 9.5.2 Kubernetes

* Kubernetes介绍与快速开始
* Kubernetes对象&Master组件&Node节点详解
* Kubernetes生产集群环境搭建与使用

### 10 区块链技术

### 10.1 区块链技术基础

* 项目架构与技术点讲解
* 区块链原理整体介绍

##### 10.2.1 区块链整体结构设计与实现

* 共识机制
* 工作量证明原理
* 挖矿算法

##### 10.2.2 密码学

* 对称加密
* 哈希(hash)加密
* 非对称加密
* 数字签名

##### 10.2.3 比特币钱包的设计与实现

* 钱包结构
* 钱包转账
* 钱包余额

##### 10.2.3 比特币交易的设计与实现

* 比特币交易UTXO
* 比特币余额

##### 10.2.4 P2P去中心化网络设计与实现

* 区块链P2P网络
* 网络节点发现
* 网络节点通讯
* 区块广播
* 交易广播

### 11 源码中的优秀设计模式

#### 11.1 设计原则

* 开闭、单一职责及里氏替换原则
* 依赖倒置、接口隔离、合成复用原则
* 迪米特法则

#### 11.2 创建型模式

* 工厂方法、抽象工厂及单例模式
* 建造者与原型模式

#### 11.3 结构型模式

* 适配器、装饰器及代理模式
* 外观、桥接、组合及享元模式

#### 11.4 行为型模式

* 模板方法、策略及观察者模式
* 迭代器、责任链、命令及中介者模式
* 备忘录、状态、访问者及解释器模式

#### 11.5 设计模式对比及应用场景

* 线程池的单例模式实现
* 电商优惠促销策略模式实现
* AOP底层代理模式实现
* RedisTemplate、JdbcTemplate模板模式实现
* Zookeeper监听器观察者模式实现
* 微服务网关鉴权责任链模式实现
* 多级缓存架构装饰器模式实现
