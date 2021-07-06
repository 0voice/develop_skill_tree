<h1>2021年最新整理，名企校招(含技术细节)鸿蒙岗位。持续更新中...</h1>

-----------

## 1 华为鸿蒙系统

### 1.1 HarmonyOS

#### 1.1.1 HarmonyOS基础

* HarmonyOS介绍与系统架构
* 开发环境搭建:DevEco Studio与DevEco Device Tool
* 应用配置与资源文件
* XML布局与加载
* 创建第二个页面与跳转

### 1.2 HarmonyOS APP开发

#### 1.2.1 Ability

##### 1.2.1.1 Page Ability(Activity)

* Page与AbilitySlice(Activity与Fragment)
* Page与AbilitySlice生命周期
* AbilitySlice路由与导航(切换Fragment)使用Intent完成页面跳转
* 使用IAbilitycontinuation实现Page跨设备迁移

##### 1.2.1.2 Service Ability(Service)

* 服务的创建与生命周期
* 前台服务与后台服务
* 启动本地服务与启动远程设备服务
* Service通信

##### 1.2.1.3 Data Ability(content Provider)

* 鸿蒙App的数据持久化
* 使用UserDataAbility创建数据提供方
* 鸿蒙数据管理
  * 事务、数据库加密
  * 关系型数据库
  * 对象映射关系型数据库
  * 轻量级偏好数据库
  * 分布式数据服务
  * 分布式文件服务
  * 融合搜索与数据存储管理
* 使用DataAbilityHelper与数据提供方通信
* Ability Form ( AppWidget )

##### 1.2.1.4 UI

* 组件与布局
  * UI组件类型
  * 使用代码创建布局
  * 使用XMIL创建布局
* 常用组件与布局
  * Text、Button与Image
  * 线性布局DirectionalLayout
  * 相对布局DependentLayout
* 动画
  * 数值动画、属性动画与动画集合
* 多模输入

##### 1.2.1.5 CES公共事件服务

* 系统公共事件与自定义公共事件(广播)
* 带权、有序与粘性公共事件
* 通知栏功能NotificationHelper
* 通知点击效果IntentAgent

##### 1.2.1.6 剪切板

* 跨应用数据传递

##### 1.2.1.7 线程与进程

* TaskDispatcher任务分发器
  * 全局并发任务分发器GlobalTaskDispatcher
  * 并发任务分发器ParallelTaskDispatcher
  * 串行任务分发器SerialTaskDispatcher
  * 专有任务分发器SpecTaskDispatcher、UITaskDispatcher与MainTaskDispatcher
* 线程通信EventHandler机制
  * EventHandler机制

### 1.3 HormonyOS多媒体开发

#### 1.3.1 音视频开发

* 音视频编解码
* 图像编解码与位图操作
* 相机CameraKit与声音AudioCapturer
* 视频编解码、播放、录制与提取
* 音频播放采集、音量管理与短音（音效）播放

#### 1.3.2 网络与近场通信

* NFC控制
* 传统蓝牙与BLE低能耗
* 无线局域网WLAN与P2P点对点通信
* 网络管理
  * socket通信
  * 流量统计与Http缓存
  * 音频呼叫与视频呼叫
* 电话服务
  * 短信服务

#### 1.3.3 设备管理

* 传感器
  * 运动类传感器∶计步器传感器、陀螺仪传感器等
  * 环境类传感器∶环境温度传感器、湿度传感器等
  * 方向类传感器∶屏幕旋转传感器、方向传感器等
  * 光线类传感器∶环境光传感器、RGB颜色传感器等
  * 健康类与其他∶心率传感器按压检测传感器等
* LED灯与振动器
* 位置服务
  * 定位
  * 地理编码转化


