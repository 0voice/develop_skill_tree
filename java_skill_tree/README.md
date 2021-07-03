<h1>2021年最新整理，名企校招(含技术细节)Java岗位。持续更新中...</h1>

-----------

* [Java基础](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Java基础)
	* [Java基础知识1](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Java基础知识1)
	* [容器](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#容器)
	* [多线程](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#多线程)
	* [反射](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#反射)
	* [对象拷贝](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#对象拷贝)
	* [Java Web模块](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#JavaWeb模块)
	* [异常模块](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#异常模块)
	* [网络模块](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#网络模块)
* [设计模式](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#设计模式)
	* [23种设计模式](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#23种设计模式)
* [框架](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#框架)
	* [Spring](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Spring)
	* [Hibernate](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Hibernate)
	* [Mybatis](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Mybatis)
* [数据库](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#数据库)
* [并发编程](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#并发编程)
	* [操作系统内核原理](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#操作系统内核原理)
	* [java内存模型](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#java内存模型)
	* [线程池](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#线程池)
	* [并发集合](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#并发集合)
	* [原子操作](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#原子操作)
	* [阻塞队列](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#阻塞队列)
* [分布式](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#分布式)
	* [分布式消息中间件](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#分布式消息中间件)
	* [分布式储存中间件](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#分布式储存中间件)
	* [分布式框架](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#分布式框架)
	* [分布式锁](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#分布式锁)
	* [分布式事务](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#分布式事务)
* [微服务](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#微服务)
	* [Spring Boot详解](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#SpringBoot详解)
	* [Spring Cloud Alibaba详解](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#SpringCloudAlibaba详解)
	* [Spring Cloud Netflix详解](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#SpringCloudNetflix详解)
* [后台优化](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#后台优化)
	* [Jvm性能调优](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Jvm性能调优)
	* [Mysql性能调优](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Mysql性能调优)
	* [Tomcat调优](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Tomcat调优)
	* [Nginx调优](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#Nginx调优)
* [项目实战](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#项目实战)
	* [秒杀系统实现](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#秒杀系统实现)
	* [亿级流量微服务电商中台](https://github.com/0voice/develop_skill_tree/edit/main/java_skill_tree/README.md#亿级流量微服务电商中台)


# Java基础

## Java基础知识1

### Java语言的特点
* 1.面向对象（封装，继承，多态）；
* 2.平台无关性（ Java 虚拟机实现平台无关性，一次编译，到处运行）；
* 3.简单易学（与C语言的面向过程相比，Java的面向对象更接近人的语言习惯）；
* 4.安全性，可靠性（Java中没有指针，程序员无法直接操作内存，而是把操作权限交给Java虚拟机，使程序不容易出现不容易出现内存泄漏和内存溢出问题。）；
* 5.支持多线程（ C++ 语言没有内置的多线程机制，因此必须调用操作系统的多线程功能来进行多线程程序设计，而 java的lang包提供一个Thread类本身就支持多线程）；
* 6.编译与解释并存（Java编译生成字节码文件，交给Java虚拟机解释）；

### 面向对象与面向过程对比
* <h6>1.面向过程</h6>
* 优点： 性能比面向对象高，因为类调用时需要实例化，开销比较大，比较消耗资源;比如单片机、嵌入式开发、Linux/Unix等一般采用面向过程开发，性能是最重要的因素。
* 缺点： 没有面向对象易维护、易复用、易扩展。
* <h6>2.面向对象</h6>
* 优点： 易维护、易复用、易扩展，由于面向对象有封装、继承、多态性的特性，可以设计出低耦合的系统，使系统更加灵活、更加易于维护。
* 缺点： 性能比面向过程低。

### Java平台的三个版本J2EE、J2SE、J2ME
* JavaSE：即Java标准版，主要用于开发和部署桌面、例如，Java应用程序开发平台Eclipse（常说的C\S架构）。
* JavaEE：即Java企业版，主要针对企业应用的开发。例如,电商网站（常说的B\S架构）。
* JavaME：即Java微型版，主要针对移动设备和嵌入式设备。例如，手机、PDA、电视机顶盒等等。
* 注：从JDK 5.0开始 J2EE 改名为 java EE，J2SE 改名为 java SE，J2ME 改名成 java ME。

### JDK、JRE、JVM之间的区别于关系
* <h6>1.三者之间的区别</h6>
* JDK：（Java Development Kit）即java的开发与运行环境，他除了包含完整的JRE之外，还包含了供开发者使用的工具包。
* JRE：（Java Runtime Environment）即Java运行环境，非开发者只需要安装 JRE来运行程序， 它包含java运行的所需的类库+JVM(java虚拟机)。
* JVM： (Java Virtual Machine) 即Java虚拟机， 当我们运行一个程序时，JVM 负责将字节码转换为特定机器代码，JVM 提供了内存管理/垃圾回收和安全机制等。这种独立于硬件和操作系统，正是 java 程序可以一次编写多处执行的原因。

* <h6>2.三者之间的关系</h6>
* 作为程序员，就必须安装JDK，因为其中包含Java开发工具包，同时也包含了JRE。
* 作为使用者，运行已经开发好的Java程序，只需要安装JRE。
* JVM和JRE的关系：JRE包含了JVM，JVM是运行Java程序的核心虚拟机，同时也包含了Java程序所需的环境支持
* 总结:JDK>JRE>JVM
* 	JDK （Java开发工具包）
*	JRE （Java运行环境)
*	JVM (Java虚拟机)

### Java环境变量
* <h6>1.环境变量的意义</h6>
* 	让java bin目录下的工具，可以在任意目录下运行，原理是将该工具所在目录告诉了系统，当使用该工具时，由系统帮我们去找指定的目录。
* <h6>2.JAVA_HOME</h6>
* 	它指向jdk的安装目录,引用%JAVA_HOME%即可,避免每次引用都输入很长的路径串，方便第三方软件引用约定好的JAVA_HOME变量，保证程序正常运行。
* <h6>3.Path环境变量</h6>
* 	设置Path环境变量之后就可以在任何目录下执行javac/java等工具命令了。 系统默认先去当前路径下找要执行的程序，如果没有，再去path中设置的路径下找。
* <h6>4.ClassPath</h6>
* 	如果指定了classpath，那么会在指定的目录下查找要运行的类文件（JDK1.5后不需要配置）

### javac命令和java命令
* java运行分两部分：一个是编译，一个是运行。
* javac：负责的是编译的部分，当执行javac时，会启动java的编译器程序。对指定扩展名的.java文件进行编译。编译后生成class文件。
* java：负责运行的部分.会启动jvm虚拟机，加载运行时所需的类库,并对class文件进行执行.
* 
### 什么是字节码，采用字节码的好处是什么。
* 首先我们来谈谈Java文件类型，一共有两种：
* 1. 扩展名为Java，Java的源文件，编译之前的纯文本文件，用来储存Java源代码。
* 2. 扩展名为class，Java 的类文件，编译之后的二进制文件，存储的是字节码
* 	也就是说编译后的.class文件存储就是字节码*。
* 	采用字节码的最大好处： 可以实现一次编译到处运行，也就是java的与平台无关性，它依靠不同平台的Java虚拟机将编译后的字节码解释成具体平台上的机器指令执行。

### import java和javax有什么区别
* 刚开始的时候 JavaAPI 所必需的包是 java 开头的包，javax 当时只是扩展 API 包来说使用。然而随着时间的推移，javax 逐渐的扩展成为 Java API 的组成部分。但是，将扩展从 javax 包移动到 java 包将是* 太麻烦了，最终会破坏一堆现有的代码。因此，最终决定 javax 包将成为标准API的一部分。
* 所以，实际上java和javax没有区别。这都是一个名字。

### Java和C++的区别
* 都是面向对象的语言，都支持封装、继承和多态
* Java 不提供指针来直接访问内存，程序内存更加安全
* Java 的类是单继承的，C++ 支持多重继承；虽然 Java 的类不可以多继承，但是接口可以多继承。
* Java 有自动内存管理机制，不需要程序员手动释放无用内存

### Java数据类型
* 基本数据类型
* 	整型、浮点型、字符型、布尔型
* 引用类型
* 	类、接口类型、数组类型、枚举类型、注解类型
* 区别
* 	基本数据类型 在被创建时，在栈上给其划分一块内存，将数值直接存储在栈上。
*	引用数据类型 在被创建时，首先要在栈上给其引用（句柄）分配一块内存，而对象的具体信息都存储在堆内存上，然后由栈上面的引用指向堆中对象的地址

### Java访问修饰符


### 字符型常量和字符串常量的区别

### 面向对象编程三大特性:封装、继承、多态

### 多态

### 接口和抽象类的区别是什么

### 接口的意义与抽象类的意义
### 重载和重写的区别
### 构造方法
### 成员变量与局部变量的区别有那些
### java对象
### java引用
#### java中四种引用
* 强引用，软引用，弱引用，虚引用。不同的引用类型主要体现在GC上:
* 强引用：如果一个对象具有强引用，它就不会被垃圾回收器回收。即使当前内存空间不足，JVM也不会回收它，而是抛出 OutOfMemoryError 错误，使程序异常终止。如果想中断强引用和某个对象之间的关联，可以显式地将引用赋值为null，这样一来的话，JVM在合适的时间就会回收该对象。
如obj.equels(new Object());
而这样 obj对象对后面new Object的一个强引用，只有当obj这个引用被释放之后，对象才会被释放
* 软引用（SoftReference）：在使用软引用时，如果内存的空间足够，软引用就能继续被使用，而不会被垃圾回收器回收，只有在内存不足时，软引用才会被垃圾回收器回收。
* 弱引用（WeakReference）：具有弱引用的对象拥有的生命周期更短暂。因为当 JVM 进行垃圾回收，一旦发现弱引用对象，无论当前内存空间是否充足，都会将弱引用回收。不过由于垃圾回收器是一个优先级较低的线程，所以并不一定能迅速发现弱引用对象。
* 虚引用（PhantomReference）：顾名思义，就是形同虚设，如果一个对象仅持有虚引用，那么它相当于没有引用，在任何时候都可能被垃圾回收器回收。
#### WeakReference与SoftReference的区别
* WeakReference 与 SoftReference 都有利于提高 GC 和 内存的效率，但是 WeakReference ，一旦失去最后一个强引用，就会被 GC 回收，而软引用虽然不能阻止被回收，但是可以延迟到 JVM 内存不足的时候。
#### 为什么要有不同的引用类型
* java不像C语言，我们可以控制内存的申请和释放，在Java中有时候我们需要适当的控制对象被回收的时机，因此就诞生了不同的引用类型，可以说不同的引用类型实则是对GC回收时机不可控的妥协。有以下几个使用场景可以充分的说明：

* 利用软引用和弱引用解决OOM问题：用一个HashMap来保存图片的路径和相应图片对象关联的软引用之间的映射关系，在内存不足时，JVM会自动回收这些缓存图片对象所占用的空间，从而有效地避免了OOM的问题.

* 通过软引用实现Java对象的高速缓存:比如我们创建了一Person的类，如果每次需要查询一个人的信息,哪怕是几秒中之前刚刚查询过的，都要重新构建一个实例，这将引起大量Person对象的消耗，并且由于这些对象的生命周期相对较短，会引起多次GC影响性能。此时，通过软引用和 HashMap 的结合可以构建高速缓存，提供性能。

### String 和 StringBuffer、StringBuilder
#### 可变性
* 简单的来说：String 类中使用 final 关键字字符数组保存字符串，private　final　char　value[]，所以 String 对象是不可变的。而StringBuilder 与 StringBuffer 都继承自 AbstractStringBuilder * 类，在 AbstractStringBuilder 中也是使用字符数组保存字符串char[]value 但是没有用 final 关键字修饰，所以这两种对象都是可变的
#### 线程安全性
* String 中的对象是不可变的，也就可以理解为常量，线程安全。AbstractStringBuilder 是 StringBuilder 与 StringBuffer 的公共父类，定义了一些字符串的基本操作，如 expandCapacity、append、
* insert、indexOf 等公共方法。StringBuffer 对方法加了同步锁或者对调用的方法加了同步锁，所以是线程安全的。StringBuilder 并没有对方法进行加同步锁，所以是非线程安全的。 　　
##### 性能
* 每次对 String 类型进行改变的时候，都会生成一个新的 String 对象，然后将指针指向新的 String 对象。StringBuffer 每次都会对 StringBuffer 对象本身进行操作，而不是生成新的对象并改变对象引用。相* 同情况下使用 StirngBuilder 相比使用 StringBuffer 仅能获得 10%~15% 左右的性能提升，但却要冒多线程不安全的风险。
* 对于三者使用的总结：

* 操作少量的数据 = String
* 单线程操作字符串缓冲区下操作大量数据 = StringBuilder
* 多线程操作字符串缓冲区下操作大量数据 = StringBuffer

### == 与 equals
* == : 它的作用是判断两个对象的地址是不是相等。即，判断两个对象是不是同一个对象。(基本数据类型“= =”比较的是值，引用数据类型 = = 比较的是内存地址).
* equals() : 它的作用也是判断两个对象是否相等。但它一般有两种使用情况：
* 情况1：类没有覆盖 equals() 方法。则通过 equals() 比较该类的两个对象时，等价于通过“==”比较这两个对象。
* 情况2：类覆盖了 equals() 方法。一般，我们都覆盖 equals() 方法来两个对象的内容相等；若它们的内容相等，则返回 true (即，认为这两个对象相等)。
* 说明：
* String 中的 equals 方法是被重写过的，因为 object 的 equals 方法是比较的对象的内存地址，而 String 的 equals 方法比较的是对象的值。
* 当创建 String 类型的对象时，虚拟机会在常量池中查找有没有已经存在的值和要创建的值相同的对象，如果有就把它赋给当前引用。如果没有就在常量池中重新创建一个 String 对象。

### hashCode 与 equals
* hashCode（）介绍
* hashCode() 的作用是获取哈希码，也称为散列码；它实际上是返回一个int整数。这个哈希码的作用是确定该对象在哈希表中的索引位置。hashCode() 定义在JDK的Object.java中，这就意味着Java中的任何类都包含有hashCode() 函数。
* 散列表存储的是键值对(key-value)，它的特点是：能根据“键”快速的检索出对应的“值”。这其中就利用到了散列码！（可以快速找到所需要的对象）。
* 为什么要有 hashCode
* 我们以“HashSet 如何检查重复”为例子来说明为什么要有 hashCode：
* 当你把对象加入 HashSet 时，HashSet 会先计算对象的 hashcode 值来判断对象加入的位置，同时也会与其他已经加入的对象的 hashcode 值作比较，如果没有相符的hashcode，HashSet会假设对象没有重复出现。但是如果发现有相同 hashcode 值的对象，这时会调用 equals（）方法来检查 hashcode 相等的对象是否真的相同。如果两者相同，HashSet 就不会让其加入操作成功。如果不同的话，就会重新散列到其他位置。（摘自我的Java启蒙书《Head fist java》第二版）。这样我们就大大减少了 equals 的次数，相应就大大提高了执行速度。
* hashCode（）与equals（）的相关规定
* 如果两个对象相等，则hashcode一定也是相同的。
* 两个对象相等,对两个对象分别调用equals方法都返回true。
* 两个对象有相同的hashcode值，它们也不一定是相等的。
* 因此，equals 方法被覆盖过，则 hashCode 方法也必须被覆盖，hashCode() 的默认行为是对堆上的对象产生独特值。如果没有重写 hashCode()，则该 class 的两个对象无论如何都不会相等。

### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别
### 重载和重写的区别

### Java访问修饰符

### Java访问修饰符

## 容器
* 
## 多线程
* 
## 反射
* 
## 对象拷贝
* 
## Java Web模块
* 
## 异常模块
* 
## 网络模块
* 
