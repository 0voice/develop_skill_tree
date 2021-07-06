<h1>2021年最新整理，名企校招(含技术细节)GoLang后台云原生岗位。持续更新中...</h1>

-----------

## 1 语法精讲

### 1.1 语法基础

* 错误处理
* 包定义以及导入
* 结构体定义
* 反射原理
* 闭包
* 值传递,引用传递,defer函数

### 1.2 并发编程

* goroutine
* 锁(读写锁，互斥锁，原子操作)
* 通道channel
* runtime包解析
* Context使用原则

### 1.3 网络编程
* tcp编程
* udp编程
* http的实现
* websocket
      
### 1.4 第三方测试框架

* goconvey
* gostub
* gomock
* monkey
      
### 1.5 源码分析

* GC实现
* 调度器源码
* 定时器实现
* map与切片
      
## 2 中间件

### 2.1 MySQL
			
* golang的CRUD
* jmorion/sqlx包
* 连接池的实现
* 异步mysql
      
### 2.2 Gin

* RESTful API
* URL查询参数
* query接收数组和 Map
* 表单参数
* 上传文件
* 分组路由route以及中间件授权
* json、struct、xml、yaml、protobuf渲染

### 2.3 Redis

* go-redis
* get/set/zset操作
* redis连接池
* 分布式锁
      
### 2.4 MongoDB
			
* mongo-driver
* BSON解析
* CRUD操作
* 文档管理
* 连接池的实现
      
### 2.5 Kafka
			
* saram包
* 同步与异步模式
* zstd压缩算法
* 横向扩展
* go实现生产消费者
* 原理分析-topic和partition
* 原理分析-消息分发策略
* 分区副本机制
      
### 2.6 etcd
			
* etcd原理与实现
* 分布式锁的实现
* etcd操作
* 服务发现与注册
      
### 2.7 ElasticSearch
			
* es服务器实例
* go-elasticsearch包
* node与cluster
* Index与Document
* 检测与配置
      
### 2.8 gRPC
			
* protoc-gen-go开发包
* .proto文件编写
* gRPC Service Stub
* rpc接口设计
* 通信模式-客户端流、服务器端流、双向流模式
* 拦截器
* 多路复用
* 负载均衡
* 安全认证
      
## 3 源码分析
### 3.1 Go标准库源码分析
			
* 编译和调试源码
* 协程实现原理
* Channel实现原理
* GC实现原理
      
### 3.2 Gin HTTP框架源码分析
			
* 原生HTTP库源码分析
* gin路由设计
* gin中间件设计
* gin engine实现
* gin context实现
      
## 4 项目实战
### 4.1 游戏后端

* leaf框架
* 网关模块
* 协议模块
* 日志模块
* 网络模块
      
### 4.2 流媒体web后端
			
* Restful接口设计
* scheduler设计
* apidefs结构体定义
* mysql建库建表
* 项目上云 腾讯云COS
      
### 4.3 小程序后端
			
* 公众号开发流程
* 微信消息接收与解析
* 公众号验证URL+Token
* 内网环境接口测试
* 后端程序测试脚本
      
### 4.4 goadmin后台权限管理系统
			
* RESTful API 设计
* Gin框架精讲
* JWT 认证
* 支持 Swagger 文档(基于swaggo)
* GORM对象关系映射
* 基于Casbin的 RBAC 访问控制模型
      
### 4.5 goim千万级高并发推送服务
			
* 支持单个、多个、广播消息推送
* 心跳检测（应用心跳和tcp、keepalive、http log pulling）
* 接入层支持多协议（websocket，tcp，http）
* 可拓扑的架构（job、logic模块可动态无限扩展）
* 基于Kafka做异步消息推送
* 注册发现服务
* 消息协议设计（基于protobuf）
* goim推送服务架构分析
* grpc客户端服务端编程
      
### 4.6 腾讯云大数据

* 腾讯云大数据套件TBDS
* 云数据仓库PostgreSQL
* 弹性MapReduce
* WeData数据开发平台
      
## 5 云原生

### 5.1 微服务

* go-micro原理
* rpc的讲解
* 服务间的同步机制
* json/protobuf
      
### 5.2 DevOps

* 项目管理 CODING-PM
* 测试管理 CODING-TM
* 制品库  CODING-AR
* 代码托管 CODING-CR
      
### 5.3 持续部署

* spinnake的实现
* webhook外部对接
* 蓝绿发布/金丝雀发布
* SCF云函数
* 快速回滚
      
### 5.4 容器化
* Docker化部署
* k8s集群
* CVM云服务器
* TKE容器服务
