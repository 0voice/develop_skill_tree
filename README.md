<h1>2021年最新整理，名企校招各大岗位的技能树，含技术细节，Java，C/C++，前端，运维，测试，运营岗位。持续更新中...</h1>

-----------

### 一、软件岗位技能树
* [C++技能树](https://github.com/0voice/develop_skill_tree/blob/main/common_skills_tree/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BB%84%E6%88%90.md#计算机组成剖析)
* [](https://github.com/0voice/develop_skill_tree/tree/main/c++_skill_tree)
* [GoLong技能树](https://github.com/0voice/develop_skill_tree/tree/main/golang_skill_tree)（正在抓紧更新中）
* [Java技能树](https://github.com/0voice/develop_skill_tree/tree/main/java_skill_tree)
* [大数据技能树](https://github.com/0voice/develop_skill_tree/tree/main/bigdata_skill_tree)
* [Python技能树](https://github.com/0voice/develop_skill_tree/tree/main/python_skill_tree)
* [iOS技能树](https://github.com/0voice/develop_skill_tree/tree/main/ios_skill_tree)
* [Android技能树](https://github.com/0voice/develop_skill_tree/tree/main/android_skill_tree)
* [前端技树](https://github.com/0voice/develop_skill_tree/tree/main/javascript_skill_tree)
* [PHP技能树](https://github.com/0voice/develop_skill_tree/tree/main/php_skill_tree)
* [Python全栈自动化测试技能树](https://github.com/0voice/develop_skill_tree/tree/main/python_automatic_test_skill_tree)
* [运维岗技能树](https://github.com/0voice/develop_skill_tree/tree/main/operation_skill_tree)
* [C#技能树](https://github.com/0voice/develop_skill_tree/tree/main/c%23_skill_tree)
* [鸿蒙技能树](https://github.com/0voice/develop_skill_tree/tree/main/harmonyos_still_tree)

<br/>

## C++技能树
### 1 精进基石专栏
#### 1.1 数据结构与算法
##### 1.1.1 面试必聊的排序与KMP
##### 1.1.2 随处可见的红黑树
##### 1.1.3 磁盘存储链式的B树与B+树
##### 1.1.4 海量数据去重的Hash与布隆过滤器，bitmap
##### 1.1.5 图论算法，dijkstra，dfs，bfs，动态规划
#### 1.2 设计模式
##### 1.2.1 创建型设计模式
##### 1.2.2 单例模式
##### 1.2.3 行为型设计模式
#### 1.3 工程管理
##### 1.3.1 手写: Makefile/cmake/configure
##### 1.3.2 操作:git/svn与持续集成
##### 1.3.3 linux系统运行时参数命令
### 2 高性能网络设计专栏
#### 2.1 网络编程
##### 2.1.1 项目:网络io与select，poll, epoll
##### 2.1.2 项目: reactor的原理与实现
##### 2.1.3 项目: http/https服务器的实现
##### 2.1.4 项目: websocket协议与服务器实现
#### 2.2 网络原理
##### 2.2.1 项目:服务器百万并发实现
##### 2.2.2 redis， memcached，nginx网络组件
##### 2.2.3 posix API与网络协议栈
##### 2.2.4 udp的可靠传输，QUIc，KCP
#### 2.3 自研框架:协程框架实现NtyCo
##### 2.3.1 协程的设计原理与切换汇编实现
##### 2.3.2 协程的调度器实现与性能测试
#### 2.4 自研框架:用户态协议栈NtyTCP
##### 2.4.1 tcp/ip设计
##### 2.4.2 tcp/ip定时器与滑动窗口的实现
##### 2.4.3 Epoll的实现
### 3 基础组件实现专栏
#### 3.1 池式组件
##### 3.1.1 手写线程池与性能分析
##### 3.1.2 ringbuffer与内存池实现
##### 3.1.3 异步请求池 http/mysql/redis/dns
##### 3.1.4 mysql/redis连接池的实现
##### 3.2 高性能组件
##### 3.2.1 原子操作CAS与锁实现原理实现
##### 3.2.2 消息队列与无锁实现
##### 3.2.3 定时器方案红黑树时间轮最小堆
##### 3.2.4 try/ catch组件的实现
#### 3.3 开源组件
##### 3.3.1 libevent/libev框架实战的那些坑
##### 3.3.2 异步日志方案log4cpp
##### 3.3.3 应用层协议设计ProtoBuf/Thrift
##### 3.3.4 Openssl对称加密与非对称加密
##### 3.3.5 Json数据解析/Xml解析器和工具包
##### 3.3.6 字符编码Unicode原理及编程实践
### 4 中间件开发专栏
#### 4.1 MySQL
##### 4.1.1 MySQLSQL语句，索引，视图，存储过程，触发器
##### 4.1.2 MySQL索引原理以及SQL优化
##### 4.1.3 MySQL事务原理分析
##### 4.1.4 MySQL缓存策略
##### 4.1.5 MySQL集群方案与Replication原理
#### 4.2 Redis
##### 4.2.1 Redis 相关命令详解及其原理
##### 4.2.2 Redis协议与异步方式
##### 4.2.3 存储原理与数据模型
##### 4.2.4 主从同步与对象模型
##### 4.2.5 集群方案主从复制/哨兵/集群与持久化
#### 4.3 Nginx
##### 4.3.1 Nginx反向代理与系统参数配置conf原理
##### 4.3.2 进程间通信与Slab共享机制
##### 4.3.3 广告内容推送Nginx过滤模块的实现
##### 4.3.4 访问频率统计Nginx handler模块的实现
##### 4.3.5 Nginx http状态机流程
#### 4.4 MongoDB
##### 4.4.1 接口编程与文档操作
##### 4.4.2 集群方案与持久化备份
### 5 开源框架
#### 5.1 Skynet
##### 5.1.1 Skynet设计原理
##### 5.1.2 skynet网络层封装以及lua/c接口编程
##### 5.1.3 skynet重要组件以及手撕游戏项目
#### 5.2 ZeroMQ
##### 5.2.1 消息队列与ZeroMQ的应用
##### 5.2.2 ZeroMQ源码分析:消息模型的实现
##### 5.2.3 ZeroMQ源码分析:网络机制与性能分析
#### 5.3 DPDK
##### 5.3.1 DPDK环境与testpmd/l3fwd/skeleton
##### 5.3.2 DPDK的用户态协议栈实现
##### 5.3.3 千万级流量并发的DNS处理
##### 5.3.4 高性能数据处理框架 VPP
##### 5.3.5 DPDK的虚拟交换机框架 OvS
### 6 Linux内核源码专栏
#### 6.1 进程原理
##### 6.1.1 进程原理与运行分析
##### 6.1.2 全方位剖析调度机制
##### 6.1.3 锁与进程间通信
#### 6.2 内存管理
##### 6.2.1 内存原理与内存杂乱繁多的细节
##### 6.2.2 物理内存与虚拟内存管理
##### 6.2.3 虚拟内存及API调用
#### 6.3 文件系统
##### 6.3.1 虚拟文件系统
##### 6.3.2 无持久存储的文件系统
##### 6.3.3 磁盘文件系统
##### 6.3.4 用户态文件系统fuse
#### 6.4 设备驱动
##### 6.4.1 实现进程间通信组件
##### 6.4.2 块设备运行原理
##### 6.4.3 虚拟网络适配器的实现
### 7 性能分析专栏
##### 7.1 性能工具
##### 7.2 调试库
##### 7.3 内核跟踪与火焰图分析
### 8 分布式架构专栏
#### 8.1 架构实战
##### 8.1.1 腾讯微服务RPC框架Tars
##### 8.1.2 容器化Docker与容器编排
##### 8.1.3 容器化管理 k8s与核心组件
#### 8.2 架构原理
##### 8.2.1 分布式注册服务中心etcd
##### 8.2.2 内核级支持的分布式存储Ceph
##### 8.2.3 快播核心技术揭秘P2P框架的实现
### 9 架构原理
#### 9.1 互联网并发云盘
##### 9.1.1 fastdfs架构分析和配置
##### 9.1.2 fastdfs存储原理
##### 9.1.3 分布式fastdfs存储集群部署
##### 9.1.4 高负载nginx/fastcgi
##### 9.1.5 文件传输和接口设计
##### 9.1.6 产品上云公网发布/测试用例
#### 9.2 微服务即时通讯
##### 9.2.1 IM即时通讯项目框架分析和部署
##### 9.2.2 IM消息服务器/文件传输服务器
##### 9.2.3 消息服务器/路由服务器
##### 9.2.4 数据库代理服务器设计
##### 9.2.5 文件服务器和docker部署
##### 9.2.6 产品上云公网发布/公网测试上线
<br/>
<br/>

## GoLang后台云原生
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
