 **邻域建模的输入：一是“功能” 二是“可扩展性”具体要求，邻域模型必须能支持在《软件需求规格说明书》中规定的“现在功能，还支持随着业务发展而出现的“未来功能”**，这两种功能就是驱动邻域建模的因素。
  
 **决定系统功能的可扩展性，决定了软件系统能力的范围，精髓是业务决定功能 功能决定模型，邻域建模和需求分析是同时进行的，他们互相参考**，

**邻域建模的输出是邻域模型，邻域模型是系统细化设计中邻域模型细化的输入**

**邻域建模的输入：一是“功能” 二是“可扩展性”具体要求，邻域模型必须能支持在《软件需求规格说明书》中规定的“现在功能，还支持随着业务发展而出现的“未来功能”**，这两种功能就是驱动邻域建模的因素。
  
**决定系统功能的可扩展性，决定了软件系统能力的范围，精髓是业务决定功能 功能决定模型，邻域建模和需求分析是同时进行的，他们互相参考**，
  
**邻域建模的输出是邻域模型，邻域模型是系统细化设计中邻域模型细化的输入**

在业务逻辑使用邻域模型模式组织时，需要定义专门的对象模型，**因此自然需要专门的数据訪问层来完成持久化工作，不能用关系型数据模型来建立数据訪问层，关系型数据模型只是简单地将数据传入持久化介质或
从中读取，不能解决复杂的应用程序必须要处理的将内存中的基于对象的数据模型转换成持久化层中的关系型数据模型，也就是说如果使用非邻域模型模式来设计业务逻辑就会把数据訪问层和业务层混在一起**，



# 邻域建模决定系统的可扩展性
<a href="https://ibb.co/6wvQfrc"><img src="https://i.ibb.co/NC1RHtg/2.png" alt="2" border="0"></a>



# 视频

* [DDD 领域驱动设计](https://www.youtube.com/watch?v=b3Au9Iw8mFU&list=PLvlChfJP2hjy_CL4ur3zLEoO_Ci_ZOuQb)
* [互联网大厂的未来架构之道DDD领域驱动设计实战---图灵课堂官方](https://www.youtube.com/watch?v=-If87fF1lwo&t=2104s)
* [DDD领域驱动设计实战图灵课堂官方诸葛老师](https://www.youtube.com/watch?v=gIGd0jOe--E)
# 在线书籍

* [邻域驱动设计---2020](https://weread.qq.com/web/reader/44f32bb071e1265344f0481)
* [复杂软件设计之道：邻域驱动设计全面解析与实战---DDD研究十年心得](https://weread.qq.com/web/reader/95932e2072052ac7959169d)
* [实现邻域驱动设计](https://weread.qq.com/web/reader/f5032ce071fd5a64f50b0f6)
* [深入实践DDD: 以DSL驱动复杂软件开发---2021](https://weread.qq.com/web/reader/3f232740723b60233f23504)
---


[解道： 领域驱动设计(DDD:Domain-Driven Design)](https://www.jdon.com/ddd.html)|[美团技术团队: 领域驱动设计在互联网业务开发中的实践](https://tech.meituan.com/2017/12/22/ddd-in-practice.html)|
---|---|

[DDD 模式从天书到实践](https://juejin.cn/post/6844904049377017869)|[京东平台研发——领域驱动设计（DDD）实践](https://www.jianshu.com/p/bee314f3a7d3)|[DDD分层架构的应用](https://www.jianshu.com/p/6bb57268b3c2)|
---|---|---|



# 案例

* [DDD专题案例一《初识领域驱动设计DDD落地》](https://bugstack.cn/itstack-demo-ddd/2019/10/15/DDD%E4%B8%93%E9%A2%98%E6%A1%88%E4%BE%8B%E4%B8%80-%E5%88%9D%E8%AF%86%E9%A2%86%E5%9F%9F%E9%A9%B1%E5%8A%A8%E8%AE%BE%E8%AE%A1DDD%E8%90%BD%E5%9C%B0.html)
* [DDD专题案例二《领域层决策规则树服务设计》](https://bugstack.cn/itstack-demo-ddd/2019/10/16/DDD%E4%B8%93%E9%A2%98%E6%A1%88%E4%BE%8B%E4%BA%8C-%E9%A2%86%E5%9F%9F%E5%B1%82%E5%86%B3%E7%AD%96%E8%A7%84%E5%88%99%E6%A0%91%E6%9C%8D%E5%8A%A1%E8%AE%BE%E8%AE%A1.html)
* [DDD专题案例三《领域驱动设计架构基于SpringCloud搭建微服务》](https://bugstack.cn/itstack-demo-ddd/2019/10/17/DDD%E4%B8%93%E9%A2%98%E6%A1%88%E4%BE%8B%E4%B8%89-%E9%A2%86%E5%9F%9F%E9%A9%B1%E5%8A%A8%E8%AE%BE%E8%AE%A1%E6%9E%B6%E6%9E%84%E5%9F%BA%E4%BA%8ESpringCloud%E6%90%AD%E5%BB%BA%E5%BE%AE%E6%9C%8D%E5%8A%A1.html)
* [DDD专题案例四---源代码](https://github.com/fuzhengwei/itstack-demo-ddd)
* [单体应用服务之SSM整合：Spring4 + SpringMvc + Mybatis---工程模型采用DDD四层架构](https://bugstack.cn/itstack-demo-frame/2019/12/22/%E6%9E%B6%E6%9E%84%E6%A1%86%E6%9E%B6%E6%90%AD%E5%BB%BA(%E4%B8%80)-%E5%8D%95%E4%BD%93%E5%BA%94%E7%94%A8%E6%9C%8D%E5%8A%A1%E4%B9%8BSSM%E6%95%B4%E5%90%88-Spring4-+-SpringMvc-+-Mybatis.html)
* [带头撸项目，《DDD + RPC 开发分布式架构，抽奖系统》](https://bugstack.cn/framework/2021/08/22/%E5%B8%A6%E5%A4%B4%E6%92%B8%E9%A1%B9%E7%9B%AE-DDD-+-RPC-%E5%BC%80%E5%8F%91%E5%88%86%E5%B8%83%E5%BC%8F%E6%9E%B6%E6%9E%84-%E6%8A%BD%E5%A5%96%E7%B3%BB%E7%BB%9F.html)
* [Spring Cloud与领域驱动实践](https://github.com/stevenli91748/JAVA-Architecture/blob/master/JAVA%20Framework/Spring%20Cloud/Spring%20Cloud%20%E4%B8%8E%20%E9%82%BB%E5%9F%9F%E9%A9%B1%E5%8A%A8%E5%AE%9E%E8%B7%B5/README.md)

#### 最全面微服务教程：SpringBoot + DDD + Apache Kafka实现最终一致性
  *  [最全面微服务教程：SpringBoot + DDD + Apache Kafka实现最终一致性(1) ](https://www.jdon.com/56424)
  *  [最全面微服务教程：SpringBoot + DDD + Apache Kafka实现最终一致性(1) 英文版](https://itnext.io/eventual-consistency-with-spring-for-apache-kafka-cfbbed450b5e)
  *  [最全面微服务教程: SpringBoot + DDD + Apache Kafka实现最终一致性(2)：在Kubernetes与Istio运维微服务](https://www.jdon.com/56429)
  *  [[最全面微服务教程: SpringBoot + DDD + Apache Kafka实现最终一致性(2)：在Kubernetes与Istio运维微服务 英文版](https://itnext.io/eventual-consistency-with-spring-for-apache-kafka-part-2-of-2-23bedd512ccf)


# 目录
* [领域驱动设计（DDD）](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k4e73277021a4e732ced3b55)---打破了分析和设计割裂的状态，并给出了领域模型的概念，抛弃了将分析与设计分开的做法，使用统一的模型来满足分析与设计的需求，使系统开发能够更加灵活、快速地响应需求的变化,领域建模的过程把分析阶段和设计阶段变成了单个循环阶段，把分析与设计紧密联系起来，使领域建模专家不再只关注需求概念的收集，也关注程序代码的设计与实现
* [领域模型的分层架构---领域驱动设计中的一些核心要素](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k6ea321b021d6ea9ab1ba605)
  * 基础设施层(底层)
    * 实体（Entity）
    * 聚合（Aggregate）：聚合是由聚合根（Root Entity）绑定在一起的对象的集合，是领域对象的显示分组，用来表达整体的概念（也可以是单一的领域对象）。它的作用是保持领域模型的行为和唯一性，同时作为一致性和事务性的边界。聚合根通过禁止外部对象对其成员的引用来保证在聚合内进行的更改是一致的，所以它的难点一般在对一致性的维护上：在聚合内实现强一致性，在聚合外实现最终一致性。在进行聚合设计时要遵循以下几个原则。◎ 遵循领域不变性。◎ 每个事务都只包含一个更新聚合，当在事务中有多个更新聚合时，就要通过领域事件对事务进行拆分，实现最终一致性。◎ 使用小聚合，避免把聚合当作领域对象的集合或容器，从而出现“巨大”的聚合根。◎ 不仅仅是HAS-A的关系，与面向对象（OO）思想中的聚合不是一个概念。领域驱动设计中的聚合首先要确定对象的行为和唯一性，由此可见聚合不是单纯的包含关系。◎ 领域对象的持久化和检索是通过聚合根来完成的。◎ 使用值对象，将聚合根内的其他领域对象优先设计成值对象。◎ 使用ID进行关联，而非对象引用。
    * 仓储（Repository）--- 仓储通过隐藏聚合持久化和检索的底层技术实现，从而达到与具体实现的解耦能力,比如当前使用的是Hibernate，而未来想改为MyBatis，这样的变动对于领域层来说是完全透明的
    * 服务（Service）---服务分为应用服务和领域服务，强调与其他对象的关系，只定义了可以为客户做什么
      * 应用服务
      * 领域服务 
  * 领域层---负责表达业务的概念，实现全部的业务逻辑并且通过各种校验手段保证业务的正确性，是核心部分。业务逻辑包括业务的流程、策略、规则、状态及完整性约束等，所以领域层是较“胖”的一层
    * 领域服务   
  * 应用层---应用层（Application Layer）：负责将展示层的请求转发到领域层，将领域层的执行结果返回给展示层，并根据业务对象调用相应的应用服务。它不包含业务逻辑，相对来说是较“薄”的一层。在该层除了可以定义应用服务，还可以进行安全认证、权限校验、持久化事务控制、调用外部系统或者向其他系统发送事件消息等。另外，应用层是展示层与领域层的桥梁，展示层使用视图模型进行界面展示，与应用层通过数据传输对象进行数据交互，从而达到展示层与领域对象解耦的目的
    * 应用服务 
  * 用户接口层（高层）
* [领域驱动设计中的核心内容是领域模型](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k341323f021e34173cb3824c)
  * 建模方法
    * 领域驱动（DDD）
    * [用例驱动（UDD）](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k341323f021e34173cb3824c)
    * [四色建模](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k341323f021e34173cb3824c)
    * CRC建模
    * CQRS建模
* 领域模型驱动设计实践
  * [ 领域模型实践](https://weread.qq.com/web/reader/71032d60719ad5af7104ca2k341323f021e34173cb3824c) 
  * [领域驱动设计](https://weread.qq.com/web/reader/d9e327a07188b377d9eb7dak70e32fb021170efdf2eca12)
  * [Spring Cloud 与 邻域驱动实践](https://github.com/stevenli91748/JAVA-Architecture/blob/master/JAVA%20Framework/Spring%20Cloud/Spring%20Cloud%20%E4%B8%8E%20%E9%82%BB%E5%9F%9F%E9%A9%B1%E5%8A%A8%E5%AE%9E%E8%B7%B5/README.md)

# 视频
* [DDD视频](https://search.bilibili.com/all?keyword=DDD%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1&from_source=web_search)

# 有用的参考

* [DDD中聚合、聚合根的含义以及作用](https://www.cnblogs.com/Courage129/p/14861100.html)
* [DDD中实体与值对象是干什么的](https://www.cnblogs.com/Courage129/p/14855483.html)
* [DDD中限界上下文与通用语言的作用](https://www.cnblogs.com/Courage129/p/14854367.html)
* [DDD划分领域、子域、核心域、支撑域的目的](https://www.cnblogs.com/Courage129/p/14853600.html)
* [DDD兴起的原因以及与微服务的关系](https://www.cnblogs.com/Courage129/p/14839544.html)
* [DDD与MVC的区别](https://segmentfault.com/q/1010000000440138)
* [可落地的DDD(1)-目标讨论](https://juejin.cn/post/6844903846712442888)
* [可落地的DDD的(2)-为什么说MVC工程架构已经过时](https://juejin.cn/post/6844903848327413773)
* [可落地的DDD(3)-如何利用DDD进行微服务的划分](https://juejin.cn/post/6844903857093345287)
* [可落地的DDD(4)-如何利用DDD进行微服务的划分(2)](https://juejin.cn/post/6844903858339069959)
* [可落地的DDD(5)-战术设计](https://juejin.cn/post/6844903873144946702)
* [DDD-CQRS能解什么问题](https://blog.csdn.net/FS1360472174/article/details/88542163)
* [DDD-CQRS的落地案例](https://juejin.cn/post/6844904062953996296)
* [为什么DDD是设计微服务的最佳实践](https://juejin.cn/post/6844903912802091021)
