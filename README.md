# [设计模式面试](https://github.com/stevenli91748/Design-Patterns/blob/master/Interview/README.md)


# 设计模式（Design-Patterns）


<a href="https://ibb.co/wYxztkD"><img src="https://i.ibb.co/YbqLgCv/image.jpg" alt="image" border="0"></a>
目录
----

[重学Java设计模式---基于互联网真实案例编写的Java设计模式](https://bugstack.cn/itstack/itstack-demo-design.html '以解决方案为核心，从实际开发业务中抽离出交易、营销、规则引擎、中间件、框架源码等22个真实场景，对设计模式进行全面、彻底的分析。帮助读者灵活地使用各种设计模式')|
---|

[精尽设计模式学习指南](http://svip.iocoder.cn/Design-Pattern/tutorials/)|[云设计模式: 面向云应用程序的规范性体系结构指南](https://blog.csdn.net/DERRANTCM/article/details/104219350)|[Github 排名第三的设计模式项目](https://github.com/iluwatar/java-design-patterns)|
---|---|---|

[设计模式的六大原则](https://www.runoob.com/design-pattern/design-pattern-intro.html)|
---|


[领域驱动设计架构DDD](https://github.com/stevenli91748/Design-Patterns/blob/master/%E9%A2%86%E5%9F%9F%E9%A9%B1%E5%8A%A8%E8%AE%BE%E8%AE%A1%E6%9E%B6%E6%9E%84DDD/README.md)|
---|


[软件架构设计模式(Architectural Pattern)不同于设计模式(Design Pattern)](https://github.com/stevenli91748/Software-Architecture-Design/blob/master/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F/README.md)|[十种软件架构设计模式(Architectural Pattern)](https://www.cnblogs.com/IcanFixIt/p/7518146.html)|
---|---|


[设计模式分三种类型：结构型、创建型和行为型，这三者类型其实对应着一个系统的三个阶段：设计阶段、创建阶段和运行阶段](https://www.jdon.com/46774)|
---|

[设计模式---接口设计原则之分离原则详解](https://www.jianshu.com/p/fe1e778b4f52)|
---|

[类与数据结构的比较！每个优秀的软件设计师和架构师都需要牢记的问题](https://www.jdon.com/52533)|
---|


# 1.  23种传统设计模式

**GOF设计模式分三种类型：结构型、创建型和行为型，这三者类型其实对应着一个系统的三个阶段：设计阶段、创建阶段和运行阶段**

## 1.1.  创建型模式---这些设计模式提供了一种在创建对象的同时隐藏创建逻辑的方式，而不是使用NEW运算符直接实例化对象，这使的程序在判断针对某个给定实例需要创建哪些对象时更加灵活.创建型模式指出系统起初如何被创建,对应系统创建阶段
 * 简单工厂模式(Simple Factory)---常用模式
 * 工厂模式(Factory)---常用模式
 * 抽象工厂模式(Abstract Factory)---常用模式
 * 单例模式(Singleton)---常用模式
 * 建造者模式(Builder)---常用模式
 * 原型模式(Prototype)

## 1.2.  结构模式---这些设计模式关注类和对象的组合，组合接口和定义组合对象获得新功能的方式 ,结构型模式指出如何设计出系统的结构 ,对应系统设计阶段
 * 桥接模式(Bridge)---常用模式
 * 组合模式(Composite)
 * 适配器模式(Adapter)
 * 装饰模式(Decorator)---常用模式
 * 代理模式(Proxy)---常用模式
 * 外观模式(Facade)---常用模式
 * 享元模式(Flyweight) 
 *     
## 1.3.  行为型模式---这些设计模式特别关注对象之间的通信，行为型模式是针对系统创建后进入自我运行阶段，对应系统运行阶段

### 1.3.1  父类与子类

 * 策略模式(Strategy)---常用模式
 * 模版方法模式(Template)---常用模式
      
### 1.3.2.   两个类之间

 * 观察者模式(Observer)---常用模式
 * 迭代模式(lterator)
 * 责任模式(chain of responsiblity)
 * 命令模式(Command)---常用模式
                
### 1.3.3.  类的状态

 * 备忘录模式(Memento)
 * 状态模式(State)
 * 空对象模式(Null Object)
     
### 1.3.4.  通过中间类

 * 访问者模式(Visitor)
 * 中介者模式(Mediator)
 * 解释器模式(Interpreter)
    
# 2.  J2EE模式


 * 依赖注入与CDI
 * 异步模式
 * MVC 模式（MVC Pattern）
 * 业务代表模式（Business Delegate Pattern）
 * 组合实体模式（Composite Entity Pattern）
 * 数据访问对象模式（Data Access Object Pattern）
 * 前端控制器模式（Front Controller Pattern）
 * 拦截过滤器模式（Intercepting Filter Pattern）
 * 服务定位器模式（Service Locator Pattern）
 * 传输对象模式（Transfer Object Pattern）
 
 ## 2.1.  JAVA EE 中的其他模式
  
  * WebSockets 模式
  * 面向消息的中间件模式
  * 微服务架构模式
 

# 3.  多线程设计模式

*  3.1.  Single Threaded Execution 模式
*  3.2.  Immutable 模式
*  3.3.  Guarded Suspension 模式
*  3.4.  Balking 模式
*  3.5.  Producer-Consumer 模式
*  3.6.  Read-Write lock 模式
*  3.7.  Thread-Per-Message 模式
*  3.8.  Worker Thread 模式
*  3.9.  Future 模式
*  3.10. Two-Phase Termination 模式
*  3.11. Thread-Specific Storage 模式
*  3.12. Active Object 模式

# 视频

* [尚硅谷-图解Java设计模式](https://www.bilibili.com/video/av58042929?from=search&seid=8766917260672308065)
* [Java设计模式 同时采用  Debug方式+内存分析 讲解抽象程度高的设计模式的视频  在f:/软件架构设计/视频/    ]
* [design patterns in java](https://www.youtube.com/watch?v=3_PUDwN01BQ&list=PLgzDdh90-m_S6ABC43AJ-q4t1LsYxdPAn)

# 有用的参考
* [23种设计模式全解析](https://blog.csdn.net/longyulu/article/details/9159589)
* [设计模式之单例模式实践](https://mp.weixin.qq.com/s/iOvBuv2yFb8Jyw_6WRWpsA)
* [设计模式之静态代理模式实战](https://mp.weixin.qq.com/s/bXeP_9MfztebxEJaH_pDww)
* [设计模式之动态代理模式实战](https://mp.weixin.qq.com/s/DURtDQVKgHXOprM5Lr1QXA)
* [详解 Java 中的三种代理模式](https://mp.weixin.qq.com/s/nBmbNP2mR7ei-lDsuOxjWg)
* [详解设计模式在Spring中的应用](https://blog.csdn.net/Y0Q2T57s/article/details/87899161)
* [涵盖了七个面向对象设计原则和24个设计模式](https://quanke.gitbooks.io/design-pattern-java/content/)
* [设计模式内容聚合---非常强大](https://mp.weixin.qq.com/s?__biz=MzI4Njc5NjM1NQ==&mid=2247488811&idx=4&sn=ec20f59a5b67a59d98d221bd20d78448&chksm=ebd62a07dca1a31188dafea0e6984b4883fa972a32ff31da2df6f52fcc73b56c6c9454751d73&scene=21)
* [Java 后端面试题 - 设计模式篇](https://hacpai.com/article/1583476977456)

