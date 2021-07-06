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

#### 1.3.3 linux系统运行时参数命令

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

#### 3.1.1 手写线程池与性能分析

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

## 5 开源框架

### 5.1 Skynet

#### 5.1.1 Skynet设计原理

* 多核并发编程-多线程，多进程，csp模型，actor模型
* actor模型实现-lua服务和c服务
* 消息队列实现
* actor消息调度

#### 5.1.2 skynet网络层封装以及lua/c接口编程

* skynet reactor网络模型封装
* socket/socketchannel封装
* 手撕高性能c服务
* lua编程以及lua/c接口编程

#### 5.1.3 skynet重要组件以及手撕游戏项目

* 基础接口skynet.send, skynet.call , skynet.response
* 广播组件multicastd
* 数据共享组件sharedatad datasheet
* 手撕万人同时在线游戏

### 5.2 ZeroMQ

#### 5.2.1 消息队列与ZeroMQ的应用

* REQ/REP模型原理分析
* PUB/SUB模型原理分析
* PUSH/PULL模型原理分析
* Router/Dealer模型原理分析

#### 5.2.2 ZeroMQ源码分析:消息模型的实现

* 消息模型
* 消息传递模式
* 一消息分帧
* 一中间层代理
* 消息丢失处理
* 
#### 5.2.3 ZeroMQ源码分析:网络机制与性能分析

* 零拷贝技术
* 消息高水位标记
* 无锁队列
* 可靠性设计

### 5.3 DPDK

#### 5.3.1 DPDK环境与testpmd/l3fwd/skeleton

* DPDK环境参数讲解
* 多队列网卡的工作原理
* CPU亲和性
* Burst数据包的优缺点
* DPDK轮询模式异步中断，轮询模式，混合中断轮询模式
* virtio与vhost

#### 5.3.2 DPDK的用户态协议栈实现

* 内核网络接口KNI的实现原理
* 接收线程/发送线程/KNI线程
* 内存数据结构rte_mbuf，rte_mempool
* 端口数据结构rte_kni， rte_kni_conf, rte_kni_ops,rte_eth_conf
* 协议数据结构rte_ether_hdrrte_ipv4_hdr，rte_udp_hdr
* 数据处理接口
* rte_eth_rx_burst,rte_kni_tx_burst,rte_pktmbuf_mtod

#### 5.3.3 千万级流量并发的DNS处理

* udp协议包处理
* dns协议实现
* 配置文件解析
* 数据结构rte_ring
* trex数据包性能测试

#### 5.3.4 高性能数据处理框架 VPP

* vpp使用vmxnet3
* DPDK ACL实现数据过滤
* vpp web应用
* vpp基础库VPPInfra
* 高速查找路由表，CAM表

#### 5.3.5 DPDK的虚拟交换机框架 OvS

* 0vS三大组件ovs-vswitchd，ovsdb-server，openvswitch.ko
* 0vS报文处理机制
* 0vS 4种数据路径
* VXLAN数据协议

## 6 Linux内核源码专栏

### 6.1 进程原理

#### 6.1.1 进程原理与运行分析

* task_struct结构数据
* 进程的生命周期
* 进程优先级
* 进程状态迁移
* 写时复制

#### 6.1.2 全方位剖析调度机制

* 调度器stop/rt/deadline/cfs/idle
* 调度策略SCHED_RR/SCHED_FIFO
* smp多核调度

#### 6.1.3 锁与进程间通信

* 自旋锁的实现
* 互斥锁的实现
* 大内核锁BKL-Big Kernel Lock
* 消息队列
* 共享内存

### 6.2 内存管理

#### 6.2.1 内存原理与内存杂乱繁多的细节

* uma与numa的内存结构
* tlb的工作原理
* mm_struct结构体
* 页表与缺页异常
* 高速缓存

#### 6.2.2 物理内存与虚拟内存管理

* 分配器原理
* slab/slub/slob分配器
* 不连续页原理
* 内存映射
* 伙伴算法

#### 6.2.3 虚拟内存及API调用

* 进程内存映射
* 进程堆栈管理
* 用户空间与内核空间
* 系统调用kmalloc/vmalloc

### 6.3 文件系统

#### 6.3.1 虚拟文件系统

* 通用文件模型
* VFS结构
* 文件操作系统调用
* file/inode原理

#### 6.3.2 无持久存储的文件系统

* 文件系统数据结构
* 管理/proc数据项
* 系统控制机制
* sysfs数据结构
* 挂载文件系统
* 文件目录操作
* sysfs增加数据

#### 6.3.3 磁盘文件系统

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

#### 6.4.3 虚拟网络适配器的实现

* 网络结构体 net_device/net_device_ops
* sk_buff原理
* 网卡数据中断
* 网卡mmap

## 7 性能分析专栏

#### 7.1 性能工具

* 高性能代码构建系统 tundra
* Http压测工具 WRK
* 网站压测工具 webbench

#### 7.2 调试库

* 内存调试性能分析工具 Valgrind
* 谷歌C++测试框架 GoogleTest
* 内存分配跟踪库 MemTrack

#### 7.3 内核跟踪与火焰图分析

* 内核探测SystemTap
* 火焰图分析与生成

## 8 分布式架构专栏

### 8.1 架构实战

#### 8.1.1 腾讯微服务RPC框架Tars

* Tars微服务应用场景
* RPC协议的序列化与反序列化
* 路由管理Registry
* 服务发布管理 Patch
* 分布式MySQL与分布式Cache
* 服务发现与服务治理解决方案

#### 8.1.2 容器化Docker与容器编排

* Docker镜像管理
* 镜像元数据管理与存储驱动
* 网络管理与GRE实现跨网络通信
* Docker容器安全解决方案SElinux
* Dockerfile的容器构建
* 编排三剑客Fig/Compose/Swarm
* 编排小神器Fleet
* Flynn体系架构与实现原理

#### 8.1.3 容器化管理 k8s与核心组件

* k8s使用场景
* k8s核心组件APIServer，scheduler，controller manager,kubelet，kube-proxy
* 网络核心原理单pod单ip,pod和网络容器
* 用户认证与namespace设计

### 8.2 架构原理

#### 8.2.1 分布式注册服务中心etcd

* etcd的应用场景与功能分析
* 强一致性raft算法原理
* etcd的分布式锁实现
* 单机部署与集群部署

#### 8.2.2 内核级支持的分布式存储Ceph

* ceph的集群部署
* monitor与OSD
* ceph 5个核心组件
* ceph集群监控
* ceph性能调调优与benchmark

#### 8.2.3 快播核心技术揭秘P2P框架的实现

* 网关NAT表分析
* NAT类型，完全锥型NAT，对称NAT，端口限制锥形NAT，IP限制锥型NAT
* 代码逻辑实现NAT类型检测
* 网络穿透的原理
* 网络穿透的3种情况

## 9 架构原理

### 9。1 互联网并发云盘

#### 9.1.1 fastdfs架构分析和配置

* fastdfs架构分析
* 快速配置fastdfs
* 上传文件逻辑分析
* 下载文件逻辑分析

#### 9.1.2 fastdfs存储原理

* tracker, storage分析
* 存储机制
* 支持断点续传
* 相同文件内容只保存一份

#### 9.1.2 分布式fastdfs存储集群部署

* 同步机制
* 线性扩容
* 如何实现高可用
* 负载均衡

#### 9.1.3 高负载nginx/fastcgi

* fastdfs-nginx-module模块分析
* fastcgi请求与响应
* nginx与fastcgi如何通信
* nginx-fastcgi-fastdfs如何实现上传下载

#### 9.1.4 文件传输和接口设计

* 云盘接口设计
* 云盘数据库设计
* 云盘文件上传，下载功能实现
* 云盘源码业务流程实现

#### 9.1.5 产品上云公网发布/测试用例

* 使用云服务器的各种坑分析
* fiddler监控http请求,postman模拟请求
* wrk测试接口吞吐量
* jmeter压力测试

### 9.2 微服务即时通讯

#### 9.2.1 IM即时通讯项目框架分析和部署

* 接入层、逻辑层、持久层架构划分
* 消息实时性分析
* 即时通讯数据库设计
* 单聊、群聊消息原理
* 群成员管理
* 未读消息原理
* 池化技术的使用
* 快速配置IM项目

#### 9.2.2 IM消息服务器/文件传输服务器

* protobuf通信协议设计
* 数据库分表设计
* reactor百方并发模型
* login_server负载均衡
* 登录请求响应模型

#### 9.2.3 消息服务器/路由服务器

* 请求登陆逻辑
* 最近联系会话逻辑
* 查询用户在线主题
* 未读消息机制
* 单聊消息推拉机制
* 群聊消息推拉机制
* 路由转发机制

#### 9.2.4 数据库代理服务器设计

* main函数主流程
* 响应流程
* redis缓存
* 消息计数（单聊和群聊)
* 未读消息机制
* 群成员管理
* 单聊群聊

#### 9.2.5 文件服务器和docker部署

* 在线文件传输机制分析
* 离线文件传输机制分析
* etcd微服务注册与发现
* docker制作与部署

#### 9.2.6 产品上云公网发布/公网测试上线

* 单元测试案例
* testbench如何设计
* IM项目性能压测
* 定制私有功能
* 云服务器部署



