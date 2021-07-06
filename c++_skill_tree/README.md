<h1>2021年最新整理，名企校招(含技术细节)Linux C/C++后台开发岗位。持续更新中...</h1>

-----------

## 1 精进基石专栏

### 1.1 数据结构与算法

#### 1.1.1 面试必聊的排序与KMP

* 插入排序
* 插入排序
* 快速排序
* 希尔排序
* 桶排序
* 基数排序
* 归并排序
* 字符串匹配KMP算法

#### 1.1.2 随处可见的红黑树

* 红黑树的应用场景进程调度cfs
* 内存管理红黑树的数学证明与推导
* 手撕红黑树的左旋与右旋
* 红黑树添加的实现与添加三种情况的证明
* 红黑树删除的实现与删除四种情况的证明
* 红黑树的线程安全的做法
* 分析红黑树工程实用的特点

#### 1.1.3 磁盘存储链式的B树与B+树

* 磁盘结构分析与数据存储原理
* 多叉树的运用以及B树的定义
* 证明B树插入的两种分裂
* B树删除的前后借位与节点合并
* 手撕B树的插入，删除，遍历，查找
* B+树的定义与实现
* B+树叶子节点的前后指针
* B+树的应用场景与实用特点
* B+树的线程安全做法

#### 1.1.4 海量数据去重的Hash与布隆过滤器，bitmap

* hash的原理与hash函数的实现
* hash的应用场景
* 分布式hash的实现原理
* 海量数据去重布隆过滤器
* 布隆过滤的数学推导与证明

#### 1.1.5 图论算法，dijkstra，dfs，bfs，动态规划

* 图的构建与需求应用场景
* dijkstra的实现
* 经典动态规划问题

### 1.2 设计模式

#### 1.2.1 创建型设计模式

* 单例模式
* 工厂方法模式
* 抽象工厂模式
* 原型模式

#### 1.2.2 单例模式

* 适配器模式
* 代理模式
* 桥接模式
* 组合模式

#### 1.2.3 行为型设计模式

* 策略模式
* 观察者模式
* 责任链模式
* 状态模式

### 1.3 工程管理

#### 1.3.1 手写: Makefile/cmake/configure

* Makefile的规则与make的工作原理
* 单文件编译与多文件编译
* Makefile的参数传递
* 多目录文件夹递归编译与嵌套执行make
* Makefile的通配符，伪目标，文件搜索
* Makefile的操作函数与特殊语法
* configure生成makefile的原则
* cmake的写法

#### 1.3.2 操作:git/svn与持续集成

* git的工作流程
* 创建操作与基本操作
* 分支管理，查看提交历史
* git服务器搭建

#### 1.3.2 linux系统运行时参数命令

* 进程间通信设施状态 ipcs
* Linux系统运行时长 uptime
* CPU平均负载和磁盘活动iostat
* 监控，收集和汇报系统活动sar
* 监控多处理器使用情况mpstat
* 监控进程的内存使用情况pmap
* 系统管理员调优和基准测量工具 nmon
* 密切关注Linux系统 glances
* 查看系统调用strace
* ftp服务器基本信息 ftptop
* IO监控iotop
* 电量消耗和电源管理powertop
* 监控mysql 的线程和性能 mytop
* 系统运行参数分析htop/top/atop
* Linux网络统计监控工具 netstat
* 显示和修改网络接口控制器ethtool
* 网络数据包分析利刃tcpdump
* 远程登陆服务的标准协议 telnet
* 获取实时网络统计信息 iptraf
* 显示主机上网络接口带宽使用情况iftop

## 2 高性能网络设计专栏

### 2.1 网络编程

#### 2.1.1 项目:网络io与select，poll, epoll

* socket与文件描述符的关联
* sigio的异步通知
* 多路复用select/poll
* 手撕epoll单线程，多线程，多进程的多种写法
* 代码实现LT/ET的区别

#### 2.1.2 项目: reactor的原理与实现

* reactor针对业务实现的优点
* epoll封装send_cb/recv_cb/accept_cb
* reactor多核实现
* 跨平台(select/epoll/kqueue)的封装reactor

#### 2.1.3 项目: http/https服务器的实现

* reactor sendbuffer与recvbuffer封装http协议
* http协议格式
* http2.0与http3.0
* 有限状态机fsm解析http
* https的工作流程
* https证书配置

#### 2.1.4 项目: websocket协议与服务器实现

* reactor sendbuffer与recvbuffer封装websocket协议
* websocket握手流程
* websocket协议头封装
* tcp分包与粘包的解决方案
* websocket数据流的编解码

### 2.2 网络原理

#### 2.2.1 项目:服务器百万并发实现

* 同步处理与异步处理的数据差异
* 网络io线程池异步处理
* ulimit的fd的百万级别支持
* sysctl.conf的rmem与wmem的调优
* conntrack的原理分析

#### 2.2.2 redis， memcached，nginx网络组件

* redis单线程reactor的实现
* memcached的多线程master-worker的reactor实现
* nginx的多进程reactor的实现
* 多进程reactor的坑点，惊群，共享内存

#### 2.2.3 posix API与网络协议栈

* connect，,listen,accept与三次握手
* listen参数backlog
* syn泛洪的解决方案
* close与四次挥手
* 11个状态迁移
* 大量close_wait与time_wait的原因与解决方案
* tcp keepalive与应用层心跳包
* 拥塞控制与滑动窗口

#### 2.2.4 udp的可靠传输，QUIc，KCP

* udp的优缺点
* udp高并发的设计方案
* qq早期为什么选择udp作为通信协议
* udp可靠传输原理
* quic协议的设计原理
* quic的开源方案quiche
* kcp的设计方案与算法原理

### 2.3 自研框架:协程框架实现NtyCo

#### 2.3.1 协程的设计原理与切换汇编实现

* 协程存在的3个原因
* 同步与异步性能，服务端异步处理，客户端异步请求
* 协程原语 switch, resume, yield,
* 一协程切换的三种实现方式，setjmp/longjmp，ucontext，汇编实现
* 汇编实现寄存器讲解
* 协程初始启动eip寄存器设置
* 协程栈空间定义，独立栈与共享栈的做法
* 协程结构体定义

#### 2.3.2 协程的调度器实现与性能测试

* 调度器的定义分析
* 超时集合，就绪队列，io等待集合的实现
* 协程调度的执行流程
* 协程接口实现，异步流程实现
* hook钩子的实现
* 协程实现mysql请求
* 协程多核方案分析
* 协程性能测试

### 2.4 自研框架:用户态协议栈NtyTCP

#### 2.4.1 tcp/ip设计

* 用户态协议栈的存在场景与实现原理
* netmap开源框架
* eth协议，ip协议，udp协议实现
* arp协议实现
* icmp协议实现

#### 2.4.2 tcp/ip定时器与滑动窗口的实现

* tcp协议头实现
* tcp控制块的实现滑动窗口的实现
* 重传定时器，坚持定时器，time_wait定时器，keepalive定时器

#### 2.4.3 Epoll的实现

* epoll数据结构封装与线程安全实现
* 协议栈fd就绪回调实现
* epoll接口实现
* LT/ET的实现

## 3 基础组件实现专栏

### 3.1 池式组件

### 3.1.1 手写线程池与性能分析

* 线程池的异步处理使用场景
* 线程池的组成任务队列执行队列
* 任务回调与条件等待
* 线程池的动态防缩
* 扩展:nginx线程池实现对比分析

#### 3.1.2 ringbuffer与内存池实现

* 内存池的应用场景与性能分析
* 内存小块分配与管理
* 手写内存池，结构体封装与API实现
* 避免内存泄漏的两种万能方法
* 定位内存泄漏的3种工具
* 扩展:nginx内存池实现

#### 3.1.3 异步请求池 http/mysql/redis/dns

* 异步请求处理流程
* King式四元组，create, comm it, callback,destory
* 异步请求框架封装
* 应用协议redis/dns/http请求封装

#### 3.1.4 mysql/redis连接池的实现

* 连接池性能的影响的2个因素，tcp连接和mysql认证
* 连接请求归还策略
* 连接超时未归还策略
* 链接断开重连策略
* 连接数量最优策略

#### 3.2 高性能组件

#### 3.2.1 原子操作CAS与锁实现原理实现

* 互斥锁的使用场景与原理
* 自旋锁的性能分析
* 原子操作的汇编实现

#### 3.2.2 消息队列与无锁实现

* 有锁无锁队列性能
* 内存屏障Barrier
* 数组无锁队列设计实现
* 链表无锁队列设计实现

#### 3.2.3 定时器方案红黑树时间轮最小堆

* 定时器的使用场景
* 定时器的红黑树存储
* 时间轮的实现
* 最小堆的实现
* 分布式定时器的实现

#### 3.2.4 try/ catch组件的实现

* setjmp/longjmp
* try/catch宏定义实现
* try/catch嵌套
* try/catch线程安全
* 线程私有数据pthread_key

### 3.3 开源组件

#### 3.3.1 libevent/libev框架实战的那些坑

* 服务端reactor事件封装
* libevent接口分析event_base_new,event_add，event_del,event_base_loop
* memcached网络模块分析
* libev的主要数据结构EV_WATCH，EV_WATCH_LIST
* libevent与libev性能对比

#### 3.3.2 异步日志方案log4cpp

* 日志库性能瓶颈分析
* 异步日志库设计与实现
* 批量写入与双缓存冲机制
* 奔溃后的日志找回

#### 3.3.3 应用层协议设计ProtoBuf/Thrift

* lM，云平台,nginx，http， redis协议设计
* 如何保证消息完整性
* 手撕protobuf IM通信协议
* protobuf序列化与反序列化
* protobuf编码原理

#### 3.3.4 Openssl对称加密与非对称加密

* 对称加密与非对称加密
* hash的数据结构与使用
* 内存分配与管理
* 抽象l0 BI0的具体实现
* base64编码的原理
* RSA的使用场景与数学证明
* https证书操作与原理分析

#### 3.3.5 Json数据解析/Xml解析器和工具包

* cjson,jsoncpp, repidjson接口应用
* json序列化和反序列化
* TinyXML2接口应用
* XML序列化和反序列化
* XML/json不同应用场景

#### 3.3.6 字符编码Unicode原理及编程实践

* 字符集与字符编码的关系
* UTF8/UTF16/UTF32具体区别
* mysql，redis，nginx使用中的字符集问题分析
* zlib数据压缩
* 手撕zlib压缩与解压
* nginx中的zlib实现原理

## 4 中间件开发专栏

### 4.1 MySQL

#### 4.1.1 MySQLSQL语句，索引，视图，存储过程，触发器

* MySQL体系结构，SQL执行流程
* SQL CURD与高级查询
* 视图，触发器，存储过程MySQL权限管理

#### 4.1.2 MySQL索引原理以及SQL优化

* 索引，约束以及之间的区别
* B+树，聚集索引和辅助索引
* 最左匹配原则以及覆盖索引
* 索引失效以及索引优化原则
* EXPLAIN执行计划以及优化选择过程分析

#### 4.1.3 MySQL事务原理分析

* 事务的ACID特性
* MySQL并发问题脏读，不可重复读，幻读
* 事务隔离级别
* 锁的类型，锁算法实现以及锁操作对象
* S锁 X锁 IS锁 IX锁
* 记录锁，间隙锁，next-key lock
* 插入意向锁，自增锁
* MVCC原理剖析

#### 4.1.4 MySQL缓存策略

* 读写分离，连接池的场景以及其局限
* 缓存策略问题分析
* 缓存策略强一致性解决方案
* 缓存策略最终一致性解决方案
* 2种mysql缓存同步方案从数据库与触发器+udf
* 缓存同步开源方案 go-mysql-transfer
* 缓存同步开源方案canal原理分析
* 3种缓存故障，缓存击穿，缓存穿透，缓存雪崩

#### 4.1.5 MySQL集群方案与Replication原理

* 分库分表:水平分库，垂直分库，水平分表，垂直分表
* MySQL官方三种集群方案replication，Fabric，Cluster
* 三个开源集群方案MMM，MHA，Galera Cluster

### 4.2 Redis

#### 4.2.1 Redis 相关命令详解及其原理

* string, set,zset，list，hash
* 分布式锁的实现
* lua脚本解决ACID原子性
* Redis事务的ACID性质分析

#### 4.2.2 Redis协议与异步方式

* Redis协议解析
* 特殊协议操作订阅发布
* 手撕异步red is协议

#### 4.2.3 存储原理与数据模型

* string的三种编码方式int, raw, embstr
* 双向链表的list实现
* 字典的实现，hash函数
* 解决键冲突与rehash
* 跳表的实现与数据论证
* 整数集合实现
* 压缩列表原理证明

#### 4.2.4 主从同步与对象模型

* 对象的类型与编码字符串对象
* 列表对象哈希对象集合对象有序集合
* 类型检测与命令多态内存回收
* 对象共享对象空转时长

#### 4.2.5 集群方案主从复制/哨兵/集群与持久化

* redis的3种集群方式主从复制，sentinel, cluster
* 4种持久化方案
* 大厂的那些分布式缓存方案

### 4.3 Nginx

#### 4.3.1 Nginx反向代理与系统参数配置conf原理

* Nginx静态文件的配置
* Nginx动态接口代理配置
* Nginx对Mqtt协议转发
* Nginx对Rtmp推拉流
* Openresty对Redis缓存数据代理

#### 4.3.2 进程间通信与Slab共享机制

* shmem的三种实现方式
* 原子操作
* nginx channel
* 信号
* 信号量
* 文件锁，互斥锁
* slab共享内存
* 如何解决"惊群"问题
* 如何实现负载均衡

#### 4.3.3 广告内容推送Nginx过滤模块的实现

* Nginx Filter模块运行原理
* 过滤链表的顺序
* 模块开发数据结构ngx_str_t,ngx_list_t,ngx_buf_t,ngx_chain_t
* error日志的用法
* ngx_comond_t的讲解
* ngx_http_module_t的执行流程

#### 4.3.4 访问频率统计Nginx handler模块的实现

* Nginx Handler模块运行原理
* ngx_module_t/ngx_http_module_t的讲解
* ngx_http_top_body_filter/ngx_http_top_header_filter的原理
* ngx_rbtree_t的使用方法
* ngx_rbtree自定义添加方法
* 模块性能测试

#### 4.3.5 Nginx http状态机流程

* Nginx的核心数据结构ngx_cycle_t,ngx_event_moule_t
* http请求的11个处理阶段
* http包体处理
* http响应发送
* Nginx Upstream机制的设计与实现

### 4.4 MongoDB

#### 4.4.1 接口编程与文档操作

* 接口编程与文档操作
* 文档/集合/聚合函数操作
* 五种索引做法单字段索引，复合索引，TTL索引，全文索引,hash索引
* GridFS存储大文件
* WiredTiger存储引擎wiredTiger的事务journal日志

#### 4.4.2 集群方案与持久化备份

* Master-Slave的三个服务Mongos/config/shard服务
* Replica Set读写策略
* Sharding的实现与原理
* 三种Mongodb性能优化策略时间同步，磁盘预读功能，内存管理
* 项目: MongoDB跨数据中心的数据复制平台
  * 抓取Oplog操作日志
  * 日志分离
  * 日志订阅
  * 数据路由
  * Cache同步


