<h1>2021年最新整理，名企校招各大岗位的技能树，含技术细节，Java，C/C++，前端，运维，测试，运营岗位。持续更新中...</h1>

-----------

### 一、软件岗位技能树
* [Linux C/C++后台开发](#anchor_point_1)
* [GoLang后台云原生](#anchor_point_2)
* [Java后台开发](#anchor_point_3)
* [Python架构师](#anchor_point_4)
* [大数据技能树](https://github.com/0voice/develop_skill_tree/tree/main/bigdata_skill_tree)（正在抓紧更新中）
* [iOS技能树](https://github.com/0voice/develop_skill_tree/tree/main/ios_skill_tree)
* [Android技能树](https://github.com/0voice/develop_skill_tree/tree/main/android_skill_tree)
* [前端技树](https://github.com/0voice/develop_skill_tree/tree/main/javascript_skill_tree)
* [PHP技能树](https://github.com/0voice/develop_skill_tree/tree/main/php_skill_tree)
* [Python全栈自动化测试技能树](https://github.com/0voice/develop_skill_tree/tree/main/python_automatic_test_skill_tree)
* [运维岗技能树](https://github.com/0voice/develop_skill_tree/tree/main/operation_skill_tree)
* [C#技能树](https://github.com/0voice/develop_skill_tree/tree/main/c%23_skill_tree)
* [鸿蒙技能树](https://github.com/0voice/develop_skill_tree/tree/main/harmonyos_still_tree)

<br/>
<br/>

<h2 id="anchor_point_1">Linux C/C++后台开发</h2>

### 1 精进基石专栏

#### 1.1 数据结构与算法

##### 1.1.1 面试必聊的排序与KMP

* 插入排序
* 插入排序
* 快速排序
* 希尔排序
* 桶排序
* 基数排序
* 归并排序
* 字符串匹配KMP算法

##### 1.1.2 随处可见的红黑树

* 红黑树的应用场景进程调度cfs
* 内存管理红黑树的数学证明与推导
* 手撕红黑树的左旋与右旋
* 红黑树添加的实现与添加三种情况的证明
* 红黑树删除的实现与删除四种情况的证明
* 红黑树的线程安全的做法
* 分析红黑树工程实用的特点

##### 1.1.3 磁盘存储链式的B树与B+树

* 磁盘结构分析与数据存储原理
* 多叉树的运用以及B树的定义
* 证明B树插入的两种分裂
* B树删除的前后借位与节点合并
* 手撕B树的插入，删除，遍历，查找
* B+树的定义与实现
* B+树叶子节点的前后指针
* B+树的应用场景与实用特点
* B+树的线程安全做法

##### 1.1.4 海量数据去重的Hash与布隆过滤器，bitmap

* hash的原理与hash函数的实现
* hash的应用场景
* 分布式hash的实现原理
* 海量数据去重布隆过滤器
* 布隆过滤的数学推导与证明

##### 1.1.5 图论算法，dijkstra，dfs，bfs，动态规划

* 图的构建与需求应用场景
* dijkstra的实现
* 经典动态规划问题

#### 1.2 设计模式

##### 1.2.1 创建型设计模式

* 单例模式
* 工厂方法模式
* 抽象工厂模式
* 原型模式

##### 1.2.2 单例模式

* 适配器模式
* 代理模式
* 桥接模式
* 组合模式

##### 1.2.3 行为型设计模式

* 策略模式
* 观察者模式
* 责任链模式
* 状态模式

#### 1.3 工程管理

##### 1.3.1 手写: Makefile/cmake/configure

* Makefile的规则与make的工作原理
* 单文件编译与多文件编译
* Makefile的参数传递
* 多目录文件夹递归编译与嵌套执行make
* Makefile的通配符，伪目标，文件搜索
* Makefile的操作函数与特殊语法
* configure生成makefile的原则
* cmake的写法

##### 1.3.2 操作:git/svn与持续集成

* git的工作流程
* 创建操作与基本操作
* 分支管理，查看提交历史
* git服务器搭建

##### 1.3.3 linux系统运行时参数命令

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

### 2 高性能网络设计专栏

#### 2.1 网络编程

##### 2.1.1 项目:网络io与select，poll, epoll

* socket与文件描述符的关联
* sigio的异步通知
* 多路复用select/poll
* 手撕epoll单线程，多线程，多进程的多种写法
* 代码实现LT/ET的区别

##### 2.1.2 项目: reactor的原理与实现

* reactor针对业务实现的优点
* epoll封装send_cb/recv_cb/accept_cb
* reactor多核实现
* 跨平台(select/epoll/kqueue)的封装reactor

##### 2.1.3 项目: http/https服务器的实现

* reactor sendbuffer与recvbuffer封装http协议
* http协议格式
* http2.0与http3.0
* 有限状态机fsm解析http
* https的工作流程
* https证书配置

##### 2.1.4 项目: websocket协议与服务器实现

* reactor sendbuffer与recvbuffer封装websocket协议
* websocket握手流程
* websocket协议头封装
* tcp分包与粘包的解决方案
* websocket数据流的编解码

#### 2.2 网络原理

##### 2.2.1 项目:服务器百万并发实现

* 同步处理与异步处理的数据差异
* 网络io线程池异步处理
* ulimit的fd的百万级别支持
* sysctl.conf的rmem与wmem的调优
* conntrack的原理分析

##### 2.2.2 redis， memcached，nginx网络组件

* redis单线程reactor的实现
* memcached的多线程master-worker的reactor实现
* nginx的多进程reactor的实现
* 多进程reactor的坑点，惊群，共享内存

##### 2.2.3 posix API与网络协议栈

* connect，,listen,accept与三次握手
* listen参数backlog
* syn泛洪的解决方案
* close与四次挥手
* 11个状态迁移
* 大量close_wait与time_wait的原因与解决方案
* tcp keepalive与应用层心跳包
* 拥塞控制与滑动窗口

##### 2.2.4 udp的可靠传输，QUIc，KCP

* udp的优缺点
* udp高并发的设计方案
* qq早期为什么选择udp作为通信协议
* udp可靠传输原理
* quic协议的设计原理
* quic的开源方案quiche
* kcp的设计方案与算法原理

#### 2.3 自研框架:协程框架实现NtyCo

##### 2.3.1 协程的设计原理与切换汇编实现

* 协程存在的3个原因
* 同步与异步性能，服务端异步处理，客户端异步请求
* 协程原语 switch, resume, yield,
* 一协程切换的三种实现方式，setjmp/longjmp，ucontext，汇编实现
* 汇编实现寄存器讲解
* 协程初始启动eip寄存器设置
* 协程栈空间定义，独立栈与共享栈的做法
* 协程结构体定义

##### 2.3.2 协程的调度器实现与性能测试

* 调度器的定义分析
* 超时集合，就绪队列，io等待集合的实现
* 协程调度的执行流程
* 协程接口实现，异步流程实现
* hook钩子的实现
* 协程实现mysql请求
* 协程多核方案分析
* 协程性能测试

#### 2.4 自研框架:用户态协议栈NtyTCP

##### 2.4.1 tcp/ip设计

* 用户态协议栈的存在场景与实现原理
* netmap开源框架
* eth协议，ip协议，udp协议实现
* arp协议实现
* icmp协议实现

##### 2.4.2 tcp/ip定时器与滑动窗口的实现

* tcp协议头实现
* tcp控制块的实现滑动窗口的实现
* 重传定时器，坚持定时器，time_wait定时器，keepalive定时器

##### 2.4.3 Epoll的实现

* epoll数据结构封装与线程安全实现
* 协议栈fd就绪回调实现
* epoll接口实现
* LT/ET的实现

### 3 基础组件实现专栏

#### 3.1 池式组件

##### 3.1.1 手写线程池与性能分析

* 线程池的异步处理使用场景
* 线程池的组成任务队列执行队列
* 任务回调与条件等待
* 线程池的动态防缩
* 扩展:nginx线程池实现对比分析

##### 3.1.2 ringbuffer与内存池实现

* 内存池的应用场景与性能分析
* 内存小块分配与管理
* 手写内存池，结构体封装与API实现
* 避免内存泄漏的两种万能方法
* 定位内存泄漏的3种工具
* 扩展:nginx内存池实现

##### 3.1.3 异步请求池 http/mysql/redis/dns

* 异步请求处理流程
* King式四元组，create, comm it, callback,destory
* 异步请求框架封装
* 应用协议redis/dns/http请求封装

##### 3.1.4 mysql/redis连接池的实现

* 连接池性能的影响的2个因素，tcp连接和mysql认证
* 连接请求归还策略
* 连接超时未归还策略
* 链接断开重连策略
* 连接数量最优策略

#### 3.2 高性能组件

##### 3.2.1 原子操作CAS与锁实现原理实现

* 互斥锁的使用场景与原理
* 自旋锁的性能分析
* 原子操作的汇编实现

##### 3.2.2 消息队列与无锁实现

* 有锁无锁队列性能
* 内存屏障Barrier
* 数组无锁队列设计实现
* 链表无锁队列设计实现

##### 3.2.3 定时器方案红黑树时间轮最小堆

* 定时器的使用场景
* 定时器的红黑树存储
* 时间轮的实现
* 最小堆的实现
* 分布式定时器的实现

##### 3.2.4 try/ catch组件的实现

* setjmp/longjmp
* try/catch宏定义实现
* try/catch嵌套
* try/catch线程安全
* 线程私有数据pthread_key

#### 3.3 开源组件

##### 3.3.1 libevent/libev框架实战的那些坑

* 服务端reactor事件封装
* libevent接口分析event_base_new,event_add，event_del,event_base_loop
* memcached网络模块分析
* libev的主要数据结构EV_WATCH，EV_WATCH_LIST
* libevent与libev性能对比

##### 3.3.2 异步日志方案log4cpp

* 日志库性能瓶颈分析
* 异步日志库设计与实现
* 批量写入与双缓存冲机制
* 奔溃后的日志找回

##### 3.3.3 应用层协议设计ProtoBuf/Thrift

* lM，云平台,nginx，http， redis协议设计
* 如何保证消息完整性
* 手撕protobuf IM通信协议
* protobuf序列化与反序列化
* protobuf编码原理

###### 3.3.4 Openssl对称加密与非对称加密

* 对称加密与非对称加密
* hash的数据结构与使用
* 内存分配与管理
* 抽象l0 BI0的具体实现
* base64编码的原理
* RSA的使用场景与数学证明
* https证书操作与原理分析

##### 3.3.5 Json数据解析/Xml解析器和工具包

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

### 4 中间件开发专栏

#### 4.1 MySQL

##### 4.1.1 MySQLSQL语句，索引，视图，存储过程，触发器

* MySQL体系结构，SQL执行流程
* SQL CURD与高级查询
* 视图，触发器，存储过程MySQL权限管理

##### 4.1.2 MySQL索引原理以及SQL优化

* 索引，约束以及之间的区别
* B+树，聚集索引和辅助索引
* 最左匹配原则以及覆盖索引
* 索引失效以及索引优化原则
* EXPLAIN执行计划以及优化选择过程分析

##### 4.1.3 MySQL事务原理分析

* 事务的ACID特性
* MySQL并发问题脏读，不可重复读，幻读
* 事务隔离级别
* 锁的类型，锁算法实现以及锁操作对象
* S锁 X锁 IS锁 IX锁
* 记录锁，间隙锁，next-key lock
* 插入意向锁，自增锁
* MVCC原理剖析

##### 4.1.4 MySQL缓存策略

* 读写分离，连接池的场景以及其局限
* 缓存策略问题分析
* 缓存策略强一致性解决方案
* 缓存策略最终一致性解决方案
* 2种mysql缓存同步方案从数据库与触发器+udf
* 缓存同步开源方案 go-mysql-transfer
* 缓存同步开源方案canal原理分析
* 3种缓存故障，缓存击穿，缓存穿透，缓存雪崩

##### 4.1.5 MySQL集群方案与Replication原理

* 分库分表:水平分库，垂直分库，水平分表，垂直分表
* MySQL官方三种集群方案replication，Fabric，Cluster
* 三个开源集群方案MMM，MHA，Galera Cluster

#### 4.2 Redis

##### 4.2.1 Redis 相关命令详解及其原理

* string, set,zset，list，hash
* 分布式锁的实现
* lua脚本解决ACID原子性
* Redis事务的ACID性质分析

##### 4.2.2 Redis协议与异步方式

* Redis协议解析
* 特殊协议操作订阅发布
* 手撕异步red is协议

##### 4.2.3 存储原理与数据模型

* string的三种编码方式int, raw, embstr
* 双向链表的list实现
* 字典的实现，hash函数
* 解决键冲突与rehash
* 跳表的实现与数据论证
* 整数集合实现
* 压缩列表原理证明

##### 4.2.4 主从同步与对象模型

* 对象的类型与编码字符串对象
* 列表对象哈希对象集合对象有序集合
* 类型检测与命令多态内存回收
* 对象共享对象空转时长

##### 4.2.5 集群方案主从复制/哨兵/集群与持久化

* redis的3种集群方式主从复制，sentinel, cluster
* 4种持久化方案
* 大厂的那些分布式缓存方案

#### 4.3 Nginx

##### 4.3.1 Nginx反向代理与系统参数配置conf原理

* Nginx静态文件的配置
* Nginx动态接口代理配置
* Nginx对Mqtt协议转发
* Nginx对Rtmp推拉流
* Openresty对Redis缓存数据代理

##### 4.3.2 进程间通信与Slab共享机制

* shmem的三种实现方式
* 原子操作
* nginx channel
* 信号
* 信号量
* 文件锁，互斥锁
* slab共享内存
* 如何解决"惊群"问题
* 如何实现负载均衡

##### 4.3.3 广告内容推送Nginx过滤模块的实现

* Nginx Filter模块运行原理
* 过滤链表的顺序
* 模块开发数据结构ngx_str_t,ngx_list_t,ngx_buf_t,ngx_chain_t
* error日志的用法
* ngx_comond_t的讲解
* ngx_http_module_t的执行流程

##### 4.3.4 访问频率统计Nginx handler模块的实现

* Nginx Handler模块运行原理
* ngx_module_t/ngx_http_module_t的讲解
* ngx_http_top_body_filter/ngx_http_top_header_filter的原理
* ngx_rbtree_t的使用方法
* ngx_rbtree自定义添加方法
* 模块性能测试

##### 4.3.5 Nginx http状态机流程

* Nginx的核心数据结构ngx_cycle_t,ngx_event_moule_t
* http请求的11个处理阶段
* http包体处理
* http响应发送
* Nginx Upstream机制的设计与实现

#### 4.4 MongoDB

##### 4.4.1 接口编程与文档操作

* 接口编程与文档操作
* 文档/集合/聚合函数操作
* 五种索引做法单字段索引，复合索引，TTL索引，全文索引,hash索引
* GridFS存储大文件
* WiredTiger存储引擎wiredTiger的事务journal日志

##### 4.4.2 集群方案与持久化备份

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

### 5 开源框架

#### 5.1 Skynet

##### 5.1.1 Skynet设计原理

* 多核并发编程-多线程，多进程，csp模型，actor模型
* actor模型实现-lua服务和c服务
* 消息队列实现
* actor消息调度

##### 5.1.2 skynet网络层封装以及lua/c接口编程

* skynet reactor网络模型封装
* socket/socketchannel封装
* 手撕高性能c服务
* lua编程以及lua/c接口编程

#### 5.1.3 skynet重要组件以及手撕游戏项目

* 基础接口skynet.send, skynet.call , skynet.response
* 广播组件multicastd
* 数据共享组件sharedatad datasheet
* 手撕万人同时在线游戏

#### 5.2 ZeroMQ

##### 5.2.1 消息队列与ZeroMQ的应用

* REQ/REP模型原理分析
* PUB/SUB模型原理分析
* PUSH/PULL模型原理分析
* Router/Dealer模型原理分析

##### 5.2.2 ZeroMQ源码分析:消息模型的实现

* 消息模型
* 消息传递模式
* 一消息分帧
* 一中间层代理
* 消息丢失处理
* 
##### 5.2.3 ZeroMQ源码分析:网络机制与性能分析

* 零拷贝技术
* 消息高水位标记
* 无锁队列
* 可靠性设计

#### 5.3 DPDK

##### 5.3.1 DPDK环境与testpmd/l3fwd/skeleton

* DPDK环境参数讲解
* 多队列网卡的工作原理
* CPU亲和性
* Burst数据包的优缺点
* DPDK轮询模式异步中断，轮询模式，混合中断轮询模式
* virtio与vhost

##### 5.3.2 DPDK的用户态协议栈实现

* 内核网络接口KNI的实现原理
* 接收线程/发送线程/KNI线程
* 内存数据结构rte_mbuf，rte_mempool
* 端口数据结构rte_kni， rte_kni_conf, rte_kni_ops,rte_eth_conf
* 协议数据结构rte_ether_hdrrte_ipv4_hdr，rte_udp_hdr
* 数据处理接口
* rte_eth_rx_burst,rte_kni_tx_burst,rte_pktmbuf_mtod

##### 5.3.3 千万级流量并发的DNS处理

* udp协议包处理
* dns协议实现
* 配置文件解析
* 数据结构rte_ring
* trex数据包性能测试

##### 5.3.4 高性能数据处理框架 VPP

* vpp使用vmxnet3
* DPDK ACL实现数据过滤
* vpp web应用
* vpp基础库VPPInfra
* 高速查找路由表，CAM表

##### 5.3.5 DPDK的虚拟交换机框架 OvS

* 0vS三大组件ovs-vswitchd，ovsdb-server，openvswitch.ko
* 0vS报文处理机制
* 0vS 4种数据路径
* VXLAN数据协议

### 6 Linux内核源码专栏

#### 6.1 进程原理

##### 6.1.1 进程原理与运行分析

* task_struct结构数据
* 进程的生命周期
* 进程优先级
* 进程状态迁移
* 写时复制

##### 6.1.2 全方位剖析调度机制

* 调度器stop/rt/deadline/cfs/idle
* 调度策略SCHED_RR/SCHED_FIFO
* smp多核调度

##### 6.1.3 锁与进程间通信

* 自旋锁的实现
* 互斥锁的实现
* 大内核锁BKL-Big Kernel Lock
* 消息队列
* 共享内存

#### 6.2 内存管理

#### 6.2.1 内存原理与内存杂乱繁多的细节

* uma与numa的内存结构
* tlb的工作原理
* mm_struct结构体
* 页表与缺页异常
* 高速缓存

##### 6.2.2 物理内存与虚拟内存管理

* 分配器原理
* slab/slub/slob分配器
* 不连续页原理
* 内存映射
* 伙伴算法

##### 6.2.3 虚拟内存及API调用

* 进程内存映射
* 进程堆栈管理
* 用户空间与内核空间
* 系统调用kmalloc/vmalloc

#### 6.3 文件系统

##### 6.3.1 虚拟文件系统

* 通用文件模型
* VFS结构
* 文件操作系统调用
* file/inode原理

##### 6.3.2 无持久存储的文件系统

* 文件系统数据结构
* 管理/proc数据项
* 系统控制机制
* sysfs数据结构
* 挂载文件系统
* 文件目录操作
* sysfs增加数据

##### 6.3.3 磁盘文件系统

* Ext2文件系统
* Ext3文件系统
* Ext4文件系统

#### 6.3.4 用户态文件系统fuse

* fuse使用场景fuse原理
* fuse实现
* 用户态文件接口实现

### 6.4 设备驱动

#### 6.4.1 实现进程间通信组件

* file_operation原理
* 系统调用的流程
* ioctl流程
* 请求中断

#### 6.4.2 块设备运行原理

* 资源管理
* I/0调度
* BI0结构原理
* PCI总线原理

##### 6.4.3 虚拟网络适配器的实现

* 网络结构体 net_device/net_device_ops
* sk_buff原理
* 网卡数据中断
* 网卡mmap

### 7 性能分析专栏

##### 7.1 性能工具

* 高性能代码构建系统 tundra
* Http压测工具 WRK
* 网站压测工具 webbench

##### 7.2 调试库

* 内存调试性能分析工具 Valgrind
* 谷歌C++测试框架 GoogleTest
* 内存分配跟踪库 MemTrack

##### 7.3 内核跟踪与火焰图分析

* 内核探测SystemTap
* 火焰图分析与生成

### 8 分布式架构专栏

#### 8.1 架构实战

##### 8.1.1 腾讯微服务RPC框架Tars

* Tars微服务应用场景
* RPC协议的序列化与反序列化
* 路由管理Registry
* 服务发布管理 Patch
* 分布式MySQL与分布式Cache
* 服务发现与服务治理解决方案

##### 8.1.2 容器化Docker与容器编排

* Docker镜像管理
* 镜像元数据管理与存储驱动
* 网络管理与GRE实现跨网络通信
* Docker容器安全解决方案SElinux
* Dockerfile的容器构建
* 编排三剑客Fig/Compose/Swarm
* 编排小神器Fleet
* Flynn体系架构与实现原理

##### 8.1.3 容器化管理 k8s与核心组件

* k8s使用场景
* k8s核心组件APIServer，scheduler，controller manager,kubelet，kube-proxy
* 网络核心原理单pod单ip,pod和网络容器
* 用户认证与namespace设计

#### 8.2 架构原理

##### 8.2.1 分布式注册服务中心etcd

* etcd的应用场景与功能分析
* 强一致性raft算法原理
* etcd的分布式锁实现
* 单机部署与集群部署

##### 8.2.2 内核级支持的分布式存储Ceph

* ceph的集群部署
* monitor与OSD
* ceph 5个核心组件
* ceph集群监控
* ceph性能调调优与benchmark

##### 8.2.3 快播核心技术揭秘P2P框架的实现

* 网关NAT表分析
* NAT类型，完全锥型NAT，对称NAT，端口限制锥形NAT，IP限制锥型NAT
* 代码逻辑实现NAT类型检测
* 网络穿透的原理
* 网络穿透的3种情况

### 9 架构原理

#### 9。1 互联网并发云盘

##### 9.1.1 fastdfs架构分析和配置

* fastdfs架构分析
* 快速配置fastdfs
* 上传文件逻辑分析
* 下载文件逻辑分析

##### 9.1.2 fastdfs存储原理

* tracker, storage分析
* 存储机制
* 支持断点续传
* 相同文件内容只保存一份

##### 9.1.2 分布式fastdfs存储集群部署

* 同步机制
* 线性扩容
* 如何实现高可用
* 负载均衡

##### 9.1.3 高负载nginx/fastcgi

* fastdfs-nginx-module模块分析
* fastcgi请求与响应
* nginx与fastcgi如何通信
* nginx-fastcgi-fastdfs如何实现上传下载

##### 9.1.4 文件传输和接口设计

* 云盘接口设计
* 云盘数据库设计
* 云盘文件上传，下载功能实现
* 云盘源码业务流程实现

##### 9.1.5 产品上云公网发布/测试用例

* 使用云服务器的各种坑分析
* fiddler监控http请求,postman模拟请求
* wrk测试接口吞吐量
* jmeter压力测试

#### 9.2 微服务即时通讯

##### 9.2.1 IM即时通讯项目框架分析和部署

* 接入层、逻辑层、持久层架构划分
* 消息实时性分析
* 即时通讯数据库设计
* 单聊、群聊消息原理
* 群成员管理
* 未读消息原理
* 池化技术的使用
* 快速配置IM项目

##### 9.2.2 IM消息服务器/文件传输服务器

* protobuf通信协议设计
* 数据库分表设计
* reactor百方并发模型
* login_server负载均衡
* 登录请求响应模型

##### 9.2.3 消息服务器/路由服务器

* 请求登陆逻辑
* 最近联系会话逻辑
* 查询用户在线主题
* 未读消息机制
* 单聊消息推拉机制
* 群聊消息推拉机制
* 路由转发机制

##### 9.2.4 数据库代理服务器设计

* main函数主流程
* 响应流程
* redis缓存
* 消息计数（单聊和群聊)
* 未读消息机制
* 群成员管理
* 单聊群聊

##### 9.2.5 文件服务器和docker部署

* 在线文件传输机制分析
* 离线文件传输机制分析
* etcd微服务注册与发现
* docker制作与部署

##### 9.2.6 产品上云公网发布/公网测试上线

* 单元测试案例
* testbench如何设计
* IM项目性能压测
* 定制私有功能
* 云服务器部署

<br/>
<br/>


<h2 id="anchor_point_2">GoLang后台云原生</h2>

<br/>


### 1 语法精讲

#### 1.1 语法基础

* 错误处理
* 包定义以及导入
* 结构体定义
* 反射原理
* 闭包
* 值传递,引用传递,defer函数

#### 1.2 并发编程

* goroutine
* 锁(读写锁，互斥锁，原子操作)
* 通道channel
* runtime包解析
* Context使用原则

#### 1.3 网络编程
* tcp编程
* udp编程
* http的实现
* websocket
      
#### 1.4 第三方测试框架

* goconvey
* gostub
* gomock
* monkey
      
#### 1.5 源码分析

* GC实现
* 调度器源码
* 定时器实现
* map与切片
      
### 2 中间件

#### 2.1 MySQL
			
* golang的CRUD
* jmorion/sqlx包
* 连接池的实现
* 异步mysql
      
#### 2.2 Gin

* RESTful API
* URL查询参数
* query接收数组和 Map
* 表单参数
* 上传文件
* 分组路由route以及中间件授权
* json、struct、xml、yaml、protobuf渲染

#### 2.3 Redis

* go-redis
* get/set/zset操作
* redis连接池
* 分布式锁
      
#### 2.4 MongoDB
			
* mongo-driver
* BSON解析
* CRUD操作
* 文档管理
* 连接池的实现
      
#### 2.5 Kafka
			
* saram包
* 同步与异步模式
* zstd压缩算法
* 横向扩展
* go实现生产消费者
* 原理分析-topic和partition
* 原理分析-消息分发策略
* 分区副本机制
      
#### 2.6 etcd
			
* etcd原理与实现
* 分布式锁的实现
* etcd操作
* 服务发现与注册
      
#### 2.7 ElasticSearch
			
* es服务器实例
* go-elasticsearch包
* node与cluster
* Index与Document
* 检测与配置
      
#### 2.8 gRPC
			
* protoc-gen-go开发包
* .proto文件编写
* gRPC Service Stub
* rpc接口设计
* 通信模式-客户端流、服务器端流、双向流模式
* 拦截器
* 多路复用
* 负载均衡
* 安全认证
      
### 3 源码分析

#### 3.1 Go标准库源码分析
			
* 编译和调试源码
* 协程实现原理
* Channel实现原理
* GC实现原理
      
#### 3.2 Gin HTTP框架源码分析
			
* 原生HTTP库源码分析
* gin路由设计
* gin中间件设计
* gin engine实现
* gin context实现
      
### 4 项目实战

#### 4.1 游戏后端

* leaf框架
* 网关模块
* 协议模块
* 日志模块
* 网络模块
      
#### 4.2 流媒体web后端
			
* Restful接口设计
* scheduler设计
* apidefs结构体定义
* mysql建库建表
* 项目上云 腾讯云COS
      
#### 4.3 小程序后端
			
* 公众号开发流程
* 微信消息接收与解析
* 公众号验证URL+Token
* 内网环境接口测试
* 后端程序测试脚本
      
#### 4.4 goadmin后台权限管理系统
			
* RESTful API 设计
* Gin框架精讲
* JWT 认证
* 支持 Swagger 文档(基于swaggo)
* GORM对象关系映射
* 基于Casbin的 RBAC 访问控制模型
      
#### 4.5 goim千万级高并发推送服务
			
* 支持单个、多个、广播消息推送
* 心跳检测（应用心跳和tcp、keepalive、http log pulling）
* 接入层支持多协议（websocket，tcp，http）
* 可拓扑的架构（job、logic模块可动态无限扩展）
* 基于Kafka做异步消息推送
* 注册发现服务
* 消息协议设计（基于protobuf）
* goim推送服务架构分析
* grpc客户端服务端编程
      
#### 4.6 腾讯云大数据

* 腾讯云大数据套件TBDS
* 云数据仓库PostgreSQL
* 弹性MapReduce
* WeData数据开发平台
      
### 5 云原生

#### 5.1 微服务

* go-micro原理
* rpc的讲解
* 服务间的同步机制
* json/protobuf
      
#### 5.2 DevOps

* 项目管理 CODING-PM
* 测试管理 CODING-TM
* 制品库  CODING-AR
* 代码托管 CODING-CR
      
#### 5.3 持续部署

* spinnake的实现
* webhook外部对接
* 蓝绿发布/金丝雀发布
* SCF云函数
* 快速回滚
      
#### 5.4 容器化

* Docker化部署
* k8s集群
* CVM云服务器
* TKE容器服务

<br/>
<br/>


<h2 id="anchor_point_3">Java后台开发</h2>

<br/>

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

<br/>
<br/>

<h2 id="anchor_point_4">Python架构师</h2>
<br/>

### 1 Python基础

#### 1.1 Python入门

* 基本数据类型
* 序列
* 运算
* 缩进和选择
* 循环
* 函数
* 面向对象及扩展

#### 1.2 Python进阶

* 词典
* 文本文件的输入输出 
* 模块 
* 函数的参数传递 
* 循环设计 
* 循环对象 
* 函数对象 
* 错误处理 

#### 1.3 Python高级语法和底层实现

* 特殊方法与多范式
* 上下文管理器
* 对象的属性
* 闭包
* 装饰器
* 内存管理
      
#### 1.4 Python标准库

* 正则表达式 (re包)
* 时间与日期 (time, datetime包)
* 路径与文件 (os.path包, glob包)
* 文件管理 (部分os包，shutil包)
* 存储对象 (pickle包，cPickle包)
* 子进程 (subprocess包)
* 信号 (signal包)
* 多线程与同步 (threading包)
* 进程信息 (部分os包)
* 多进程初步 (multiprocessing包)
* 多进程探索 (multiprocessing包)
* 数学与随机数 (math包，random包)
* 循环器 (itertools)
* 数据库 (sqlite3)
      
### 2 web进阶-Flask框架

#### 2.1 路由及视图
			
F1ask相关配置参数
视图常用逻辑
异常捕获
请求勾子
状态保持
上下文
      
#### 2.2 模板

* Jinja2模板的使用
* 过滤器
* 控制代码块
* 模板代码复用
* 特有变量和函数
* Flask_WTF表单
* CSRF

#### 2.3 数据库

##### 2.3.1 Mysql数据库

* 增删改查

##### 2.3.2 redis数据库

* 数据类型
* 增、删、改、查

##### 2.3.3 F1ask-SQLALchemy配置
##### 2.3.4 数据库的基础操作
##### 2.3.5 管理系统
* 定义模型
* 数据库表创建
* 数据显示
* 表单验证
* 删除数据
##### 2.3.6 多对多演练
##### 2.3.7 数据库迁移信号机制

#### 2.4 蓝图
			
* 模块化
* B1ueprint初识蓝图
* 运行机制
* 蓝图url前缀
* 注册静态路由
* 设置模板目录
      
### 3 web架构―Django框架

#### 3.1 Django框架基本使用
			
* Web应用机制和术语
* Django起源
* Django初体验
* Django工程创建
* 子应用创建
* 创建视图

#### 3.2 深入模型
			
* redis数据库
	* 数据类型
	* 增﹑删、改﹑查
* 配置关系型数据库MysQL
* 利用Django后台管理模型
* 使用ORM完成模型的CRUD操作
* 模型定义与字段使用实践

#### 3.3 静态资源和Ajax请求
			
* 加载静态资源
* Ajax请求
* Cookie
* Session

#### 3.4 表单的应用
			
* 注册登录功能

#### 3.5 中间件的应用
			
* 实现登录验证
* Django中间件概述
* 自定义中问件

#### 3.6 前后端分离开发入门
			
* 返回JSON格式的数据
* 使用Vue.js渲染页面

#### 3.7 RESTfu1架构和DRF
			
* RESTful设计方法
* DRF安装与配置
* Serializer序列化器
* 模型类序列化器
* 视图集ViewSet

#### 3.8 Django Channe1s和Ce1ery示例
#### 3.9 提高页面加载速度优化图像

* 使用Sor1在服务器端动态调整图像大小
* 使用Srcset和Sizes响应执行

#### 3.10 提高页面加载速度优化图像

* 使用Kubernetes使Django应用变得可扩展并具有弹性
* 传统的基于虚拟机cVM的部署存在有些问题
* 谷歌容器引擎应用上实例
* 预备步骤
* 创建及发布Docker容器
* 部署这些容器到Kubernetes集群

#### 3.11 异步任务和定时任务
#### 3.12 单元测试
#### 3.13 日志文件

### 4 Web网页开发

#### 4.1 项目准备

* 开发流程
* 需求分析
* 项目架构
* 工程创建
* 项目配置

#### 4.2 用户部分
			
* 图片验证码
* 短信验证码
* 跨域cORS
* JWT登录
* 用户中心
* 邮箱与验证
* 收货地址
   
#### 4.3 商品部分
			
* 数据表的设计
* FastDFS
* Docker容器
* 分布式文件系统
* 富文本编辑器
* 添加测试数据
* 定时任务页面
* 静态化商品详情
* 商品列表页
* 商品搜索
* 用户访问历史

#### 4.4 购物车部分

* 购物车数据库的设计
* 购物车增加
* 购物车查询
* 购物车修改
* 购物车删除
* 购物车全选
* 登录合并购物车
      
#### 4.5 订单部分
			
* 订单数据库设计
* 订单结算
* 保存订单
* 下单成功
      
#### 4.6 支付宝支付

* 接入支付宝
* 发起支付
* 保存支付结果

#### 4.7 Xadmin
#### 4.8 用户权限控制
#### 4.9 数据库读写分离
#### 4.10 项目部署
      
### 5 爬虫框架

#### 5.1 网络爬虫和相关工具

##### 5.1.1 网络爬虫

* 爬虫的应用领域
* 合法性和背景调研
	* 爬虫合法性探讨
	* Robots.txt文件

##### 5.1.2 相关工具

* HTTP协议
* 谷歌浏览器内置的开发者工具
* POSTMAN
* 命令行HTTP客户端

##### 5.1.3 相关工具

* 处理相对链接
* 设置代理服务
* 限制下载速度
* 避免爬虫陷阱
* SSL相关问题

#### 5.2 数据采集和解析

##### 5.2.1 HTML页面分析
##### 5.2.2 使用requests获取页面
##### 5.2.3 四种采集方式

* 正则
* PyQuery
* Beautiful
* lxml

##### 5.2.4 获取知乎发现上的问题链接

#### 5.3 缓存知乎发现上的链接和页面代码

#### 5.4 并发下载

* 多线程和多进程回顾
* 分布式进程
* 协程和异步I/0
* 多线程爬取随机网页所有页面

#### 5.5 解析动态内容

* Javascript逆向工程
* 使用Se1enium
* 爬虫逆向解析 - js解析动态内容

#### 5.6 表单交互和验证码处理

##### 5.6.1 提交表单

* 手动提交
* 自动提交

##### 5.6.2 验证码处理

* 光学字符识别

#### 5.7 常见反爬策略及应对方案

* 构造合理的HTTP请求头
* 检查网站生成的Cookie
* 抓取动态内容
* 限制爬取的速度
* 处理表单中的隐藏域
* 处理表单中的验证码
* 绕开"陷阱"
* 隐藏身份

#### 5.8 scrapy爬虫框架

* 数据处理流程
* 安装和使用Scrapy
* XPath语法
* 在Chrome浏览器中查看元素XPath语法

#### 5.9 scrapy爬虫框架高级应用

* Spider的用法
* 中间件的应用
	* 下载中间件
	* 蜘蛛中间件
	* scrapy对接Se1enium
	* scrapy部署到Docker

#### 5.10 Scrapy爬虫框架分布式实现

* Scrapy分布式实现
* Scrapyd分布式部署

### 6 Python架构师

#### 6.1 自动化运维

##### 6.1.1 shell基础

* shell快速入门
* shell执行方式
* shell脚本
* shell开发规范
* shell变量
	* 本地变量
	* 全局变量
	* 内置变量

##### 6.1.2 shell进阶

* 验证方式
	* 用户密码验证
	*基于秘钥等验证
* 条件表达式
* 计算机表达式
* 常见符号
* 常见命令

##### 6.1.3 shell流程控制

* if语句
	* 单分支
	* 双分支
	* 多分支
* 函数
	* 函数的定义
	* 函数参数的规则

##### 6.1.4 环境部署

* 基础目录环境
* 主机网络环境
* 方案定制
* 虚拟环境分析
* 软件安装
* 环境部署
* nginx
	* nginx基本操作
	* nginx代理项目配置

##### 6.1.5 代码发布

* 代码发布应用场景
* 代码发布方式

##### 6.1.6 手工代码发布

* 方案分析
* 方案实施

##### 6.1.7 脚本代码发布

* 固定变化
* 固定函数
* 远程执行
* 脚本框架
* 脚本参数
* 安全脚本发布

#### 6.2 数据分析

##### 6.2.1 数据分析基础

* 为什么要使用Python进行数据分析
* 重要的Python库
* IPython和Jupyter
* SciPy
* scikit-1earn
* statsmode1s
* 安装和设置

#### 6.2.2 NumPy基础

##### 6.2.2 数组和矢量计算

* NumPy简介
* NumPy的ndarray:一种多维数组对象
* 创建ndarray
* ndarray的数据类型
* NumPy数组的运算
* 基本的索引和切片
* 布尔型索引
* 数组转置和轴对换
* 通用函数:快速的元素级数组函数
* 利用数组进行数据处理
* 将条件逻辑表述为数组运算
* 数学和统计方法
* 示例:随机漫步

#### 6.3 Pandas入门

* pandas的数据结构介绍
	* Series
	* DataFrame
* 索引对象
* 丢弃指定轴上的项
* 索引、选取和过滤
* 用loc和iloc进行选取
* 算术运算和数据对齐
* 在算术方法中填充值
* DataFrame和Series之间的运算
* 函数应用和映射
* 汇总和计算描述统计

#### 6.4 数据加载、存储与文本格式

* 读写文本格式的数据
* 逐块读取文本文件
* 将数据写出到文本格式
* 处理分隔符格式
* JSON数据
* XML和HTML: Web信息收集
* 利用lxml.objectify解析XML
* 二进制数据格式
* Web APIs交互

#### 6.5 数据清洗和准备

* 处理缺失数据
* 滤除缺失数据
* 填充缺失数据
* 数据转换
* 利用函数或映射进行数据转换
* 检测和过滤异常值

#### 6.6 绘图与可视化

##### 6.6.1 matplotlib API入门

* Figure和Subp1ot
* 调整subplot周围的间距
* 设置标题、轴标签、刻度以及刻度标签
* 注解以及在Subplot上绘图
* 使用pandas和seaborn绘图

##### 6.6.2 Python建模

* pandas与模型代码的接口
* 用Patsy创建模型描述
* 用Patsy公式进行数据转换
* 分类数据和Patsy
* 估计线性模型
* 估计时间序列过程
* scikit-learn

##### 6.6.3 数据分析

* 数据准备
* 数据清洗
* 数据提取
* 用pandas对时区进行计数
* MovieLens 1M数据集
* 计算评分分歧
* 1880-2010年间全美婴儿姓名统计分析

### 7 分布式架构

#### 7.1 Celery - 快速入门

* Task Queue
* celery安装
* Broker
* Applic ation
* 项目中使用Celery
* 调用任务
* Designing Work-F1ows
* Roriodic Tasks

#### 7.2 Periodic Tasks

* Introduction
* Time Zones
* Entries
	* Availab1e Fie1ds
* Crontab schedules
* Solar schedules
* Starting the Schedu1er
	* Using custom schedu1er c1asses

#### 7.3 Docker

* Docker-swarm集群部署
* Docker集群伸缩
* Docker-swarm集群相关操作
* Docker私有仓库搭建
* Docker-swarm集群特性

#### 7.4 Nginx

* Nginx-nginx原理
* Python的web服务构建
* Nginx-web服务器
* IO复用
* epoll模型
* Nginx-进程
	* 常用模块
	* 配置语法
	* 常用模块的使用
* Nginx缓存代理
	* 负载均衡
	* 缓存优化
	* 缓存清除
	* 动态伸缩负载
* Nginx-1ua脚本

### 8 AI研发

#### 8.1 机器学习

##### 8.1.1 机器学习概述

* 什么是机器学习
* 机器学习的用途

##### 8.1.2 特征工程

* 特征工程介绍
* 特征提取
	* 特征提取API
	* 字典特征提取
	* 文本特征提取
	* jieba分词处理
* Tf-idf文本特征提取
* 特征预处理
	* 归一化
	* 标准化
* 特征选择
	* 降维
	* 过滤式
	* 相关系数
* 主成分分析

##### 8.1.3 分类算法

* 数据集介绍与划分
* skleam转换器和估计器
* k-近邻算法
	* K-近邻算法原理讲解
	* 应用场景和注意事项
* 模型选择与调优
	* 交叉验证
	* Facebook签到位置预测K值调优
* 朴素贝叶斯算法
	* 什么是朴素贝叶斯分类方法
* 决策树
* 集成学习方法之随机森林

##### 8.1.4 回归与聚类算法

* 线性回归
	* 线性回归原理
	* 线性回归介绍
* 欠拟合与过拟合
	* 什么是过拟合与欠拟合
* 线性回归-岭回归
	* 带有L2正则化的线性回归-岭回归
* 逻辑回归与二分类
	* 逻辑回归的应用场景
	* 逻辑回归的原理
* 无监督学习K-means算法
	* 什么是无监督学习
	* 无监督学习包含算法
	* K-means原理
	* K-means聚类步骤

#### 8.2 深度学习

##### 8.2.1 深度学习介绍

* 深度学习与机器学习的区别
* 深度学习的应用场景

##### 8.2.2 TensorF1ow框架

* TF数据流图
	* TensorFlow实现一个加法运算
	* TensorF1ow结构分析
* 会话
	* 会话的run()
* 张量
	* 张量的类型
	* 张量的阶
	* 创建张量的指令
	* 张量的数学运算

* 变量OP
	* 变量OP的方法
	* 命名空间与共享变量
* 高级API
	* tf.app
	* tf.image
	* tf.gfile
	* tf.summary
	* tf.train
* 线性回归

##### 8.2.3 神经网络

* 文件读取流程
* 图片数据
	* 图像基本知识
	* 图片三要素
	* 图片特征值处理
* 二进制数据
	* CIFAR10二进制数据集介绍
	* CIFAR10二进制数据读取
* TFRecords
	* 什么是TFRecords文件
	* Example结构解析J
* 神经网络基础
	* 感知机
	* playground使用
	* layground简单两类分类结果
	* 多个神经元效果演示
* 神经网络原理
	* softmax回归
	* 交叉嫡损失
* Mnist手写数字识别

##### 8.2.4 卷积神经网络

* 卷积神经网络简介
* 卷积神经网络原理
* CNNMnist手写数字
* 网络结构与优化
* 验证码图片识别


<br/>
<br/>
<br/>
<br/>
<br/>

### 二、通用计算机基础

##### 2.1 计算机组成

* [计算机组成剖析](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#计算机组成剖析)
* [冯·诺依曼计算机结构](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#冯·诺依曼计算机结构)
* [计算机执行指令的工作过程](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#计算机执行指令的工作过程)
* [指令系统分析](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#指令系统分析)
* [高级语言、汇编语言和机器语言之间的关系](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#高级语言、汇编语言和机器语言之间的关系)
* [计算机算术和逻辑运算方法及其实现](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#计算机算术和逻辑运算方法及其实现)
* [微处理器和CPU](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#微处理器和CPU)
* [存储系统](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#存储系统)
* [输入输出系统的基本原理和关键技术](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#输入输出系统的基本原理和关键技术)
	
##### 2.2 计算机网络

* [网络层次划分](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#网络层次划分)
* [OSI七层网络模型](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#OSI七层网络模型)
* [子网掩码及网络划分](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#子网掩码及网络划分)
* [ARP/RARP协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#ARP/RARP协议)
* [路由选择协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#路由选择协议)
* [TCP/IP协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#TCP/IP协议)
* [UDP协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#UDP协议)
* [DNS协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#DNS协议)
* [NAT协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#NAT协议)
* [DHCP协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#DHCP协议)
* [HTTP协议](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C.md#HTTP协议)

##### 2.3 数据结构

* [队列](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#队列)
* [集合](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#集合)
* [链表、数组](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#链表数组)
* [字典、关联数组](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#字典关联数组)
* [栈](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#栈)
* [树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#树)
  * [二叉树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#二叉树)
  * [完全二叉树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#完全二叉树)
  * [平衡二叉树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#平衡二叉树)
  * [二叉查找树（BST）](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#二叉查找树bst)
  * [红黑树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#红黑树)
  * [B，B+，B*树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#b-bb树)
  * [LSM 树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#lsm-树)
* [BitSet](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84.md#bitset)

##### 2.4 常用算法

* [排序、查找算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#排序查找算法)
  * [选择排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#选择排序)
  * [冒泡排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#冒泡排序)
  * [插入排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#插入排序)
  * [快速排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#快速排序)
  * [归并排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#归并排序)
  * [希尔排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#希尔排序)
  * [堆排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#堆排序)
  * [计数排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#计数排序)
  * [桶排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#桶排序)
  * [基数排序](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#基数排序)
  * [二分查找](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#二分查找)
  * [Java 中的排序工具](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#java-中的排序工具)
* [布隆过滤器](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#布隆过滤器)
* [字符串比较](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#字符串比较)
  * [KMP 算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#kmp-算法)
* [深度优先、广度优先](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#深度优先广度优先)
* [贪心算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#贪心算法)
* [回溯算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#回溯算法)
* [剪枝算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#剪枝算法)
* [动态规划](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#动态规划)
* [朴素贝叶斯](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#朴素贝叶斯)
* [推荐算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#推荐算法)
* [最小生成树算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#最小生成树算法)
* [最短路径算法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95.md#最短路径算法)

##### 2.5 设计模式

* [创建型模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#创建型模式)
	* [单例模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#创建型模式)
	* [原型模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#创建型模式)
	* [工厂模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#创建型模式)
	* [抽象工厂模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#创建型模式)
	* [建造者模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#创建型模式)
* [结构型模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
	* [代理模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
	* [适配器模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
	* [桥接模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
	* [装饰模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
	* [外观模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
	* [享元模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
	* [组合模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#结构型模式)
* [行为型模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [模板方法模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [策略模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [命令模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [职责链模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [状态模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [观察者模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [中介者模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [迭代器模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [访问者模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [备忘录模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
	* [解释器模式](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#行为型模式)
* [实际应用案例](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#实际应用案例)
	* [23种设计模式实际应用案例](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md#23种设计模式实际应用案例)

##### 2.6 网络安全

* [网络安全常识](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#网络安全常识)
* [web安全前后端基础](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#web安全前后端基础)
* [信息的扫描与嗅探](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#信息的扫描与嗅探)
* [病毒知识入门](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#病毒知识入门)
* [密码攻击的原理和方法](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#密码攻击的原理和方法)
* [网络代理与追踪技术](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#网络代理与追踪技术)
* [后门技术](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#后门技术)
* [网站攻防](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#网站攻防)
* [端口扫描工具](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8.md#端口扫描工具)

##### 2.7 版本管理工具

* [Git](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%89%88%E6%9C%AC%E7%AE%A1%E7%90%86%E5%B7%A5%E5%85%B7.md#Git)
* [SVN](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E7%89%88%E6%9C%AC%E7%AE%A1%E7%90%86%E5%B7%A5%E5%85%B7.md#SVN)

<br/>
<br/>
<br/>
<br/>

<!-- 

<h3 id="22">金主爸爸信息</h3> 

---
零声教育推出9.9元，校招特训营：内容包含岗位投递渠道，技术方向选择（Java，c++，前端，算法，运维，测试，嵌入式），简历书写规范，面试准备事宜，企业选择，薪资谈判。<br/>
点击 [秋招春招提前批大厂面试指导 简历梳理 offer选择 技术方向指导课程](https://ke.qq.com/course/3582758?flowToken=1037495)

另外每天8点还有技术直播分享，分享内容：Linux，Nginx，ZeroMQ，MySQL，Redis，fastdfs，MongoDB，ZK，流媒体，CDN，P2P，K8S，Docker，TCP/IP，协程，DPDK。<br/>
扫码联系小姐姐，获得直播链接。<br/>
![barcode](https://www.0voice.com/uiwebsite/img/barcode/cz.jpg)

-->

<!--
<h3 id="22">金主爸爸信息</h3> 

---
#### 零声教育，专注于c/c++Linux后台服务器开发架构技术提升。<br>
[分享Linux，Nginx，ZeroMQ，MySQL，Redis，fastdfs，MongoDB，ZK，流媒体，CDN，P2P，K8S，Docker，TCP/IP，协程，DPDK等技术内容，立即学习。](https://ke.qq.com/course/417774?flowToken=1037127)

福利资料获取：
#### 1、十份大厂面经视频分享

  ① 秋招如何斩获字节&快手offer<br>
  
  ② 小厂到腾讯60Woffer的逆袭<br>
  
  ③ 如何一次跳槽涨薪12W<br>
  
  ④ 清华毕业生跨专业如何拿到美团&字节offer<br>
  
  ⑤ 普通二本应届生的B站之路<br>
  
  ⑥ 非科班毕业如何进京东，拿到28W岗位offer<br>
  
  ⑦ 外包裸辞6个月，成功入职金山实现薪资翻倍<br>
  
  ⑧ 三年社招如何能够拿到35K&360offer<br>
  
  ⑨ 毕业半年，离职挑战华为offer<br>
  
  ⑩ 30天突击学习，拿下高薪offer涨薪10W
  
#### 2、对标腾讯T9职级技术要求的后台开发学习图谱

![大纲部分图.png](https://img11.360buyimg.com/ddimg/jfs/t1/37229/14/15620/149708/60e6a78eE5241eec1/d0f0c9d9aa1e4d99.png)

#### 扫码联系橙子，免费领取干货资料【备注：GitHub技能树】<br>
![barcode](https://www.0voice.com/uiwebsite/img/barcode/cz.jpg)
-->

<br/>
<br/>
<br/>
<br/>
<br/>

<h2>🤝 鸣谢</h2>

##### 为了让我们的repo内容更加的丰富，更加的专业。欢迎大家贡献patch，希望大家在issue里面出谋划策，我们期待你的加入。

<a href="https://github.com/wangbojing">
    <img src="https://avatars.githubusercontent.com/u/18027560?v=4" width="40px">
</a> 

<a href="https://github.com/ls-Brynn">
    <img src="https://avatars.githubusercontent.com/u/87458342?v=4" width="40px">
</a> 

## 联系专栏

#### 零声教育，专注于c/c++Linux后台服务器开发架构技术学习提升。<br>
每天晚上8点【免费技术直播】：[分享Linux，Nginx，ZeroMQ，MySQL，Redis，fastdfs，MongoDB，ZK，流媒体，CDN，P2P，K8S，Docker，TCP/IP，协程，DPDK等技术内容，立即学习。](https://ke.qq.com/course/417774?flowToken=1037127)

#### 关注微信公众号【后台服务架构师】——【联系我们】，获取本repo最全PDF学习文档！

<img width="65%" height="65%" src="https://user-images.githubusercontent.com/87457873/130796999-03af3f54-3719-47b4-8e41-2e762ab1c68b.png"/>
