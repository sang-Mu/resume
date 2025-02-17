# 联系方式

* 手机：`********`
* Email：`*************`
* QQ/微信号：`**********************`

# 个人信息

* ****/男/2000
* 技术博客：https://jsdi.top
* Github：https://github.com/sang-Mu
* 期望职位：Java 后端实习生

# 技能清单

* 熟练掌握 Java 基础知识、多线程、集合等基础框架
* 对 JVM 原理有初步的理解，包括内存模型、垃圾回收机制以及类加载过程
* 熟悉关系型数据库，如 MySQL；掌握非关系型数据库，如 Redis，了解高并发下缓存穿透和缓存雪崩的解决方案
* 掌握基础数据结构与算法、计算机网络，了解 TCP/IP协议、HTTP/HTTPS协议等
* 掌握常见消息队列的使用，如RabbitMQ
* 熟练使用 Spring、SpringMVC 、SpringBoot 、Mybatis 、Mybatis-Plus 等主流开源框架
* 熟练使用 Git 、Maven 等常用开发工具
* 熟练使用 Linux，有 Linux 下的开发经验
* 了解前端的 HTML、CSS、JavaScript 以及 Vue

# 项目经验

### 基于SprintBoot-Vue的个人博客系统

- **项目简述：**学习后端开发以来第一个完整的项目，该项目分为三个子项目：博客前台、后台管理系统以及后端项目，实现的功能模块有：登录注销/文章管理/动态管理/标签管理/用户管理/UV、PV统计等。

- **项目地址：**https://github.com/sang-Mu/viturals-blog

- **项目预览：**[博客门户](https://jsdi.top)	[后台管理系统](https://jsdi.top/admin)

- **技术选型：**SpringBoot + Mybatis-Plus + MySQL + Redis + Shiro + JWT等

- **责任描述：**

  1. 登录模块的开发，前后端两次MD5加密算法保证账号密码的安全性

  2. 负责整个博客系统的数据库建模和基础业务功能开发，集成了Swagger方便接口调试以及Druid监控系统SQL慢查询等

  3. 使用Redis + 定时任务实现UV、PV的统计

  4. 把项目部署到云服务器，同时配置了HTTPS以及Nginx反向代理

- **项目收获：**该项目成功作为本人的个人博客上线，目前系统允许稳定，功能完善。此项目也让我对web开发有了进一步的认识，并非所有的系统都追求高性能，**可靠性、可维护性、编程工作量**等往往是更重要的考虑因素。总而言之，代码的实现要”优雅“。

### 高并发秒杀项目

- **项目简述：**基于SpringBoot的高并发电商秒杀项目，前后端分离，并进行了高并发优化和压力测试。实现的功能模块有：登录功能/商品列表/商品详情/库存预热/秒杀下单/订单详情等。
- **项目地址**：https://github.com/sang-Mu/springboot-vue-seckill

- **技术选型：**
  - 主流web框架：SpringBoot + Mybatis + MySQL + Vue + 其他
  - 缓存：Redis
  - 消息队列：RabbitMQ

- **项目难点：**
  1. 登录模块的开发，包括两次MD5加密算法保证数据安全以及使用Redis缓存登录验证码UUID，实现验证码模块功能
  
  2. MD5算法加密秒杀地址，隐藏下单URL，防止恶意用户刷单
  
  3. 使用 Redis 实现秒杀商品减库存，为了防止超卖现象的发生，使用 LUA 脚本来保证”减库存“操作的原子性
  
  4. 使用 Redis 判断用户是否重复消费。这里的实现借鉴了redis实现分布式锁的思想，使用`setnx`命令。redis中不存在某个key才能把订单放进消息队列，避免了重复消费
  
  5. 使用消息队列 RabbitMQ 来实现异步下单，削峰填谷，进一步提升系统并发能力
  
- **项目成果：**使用 Jmeter 对该系统进行压力测试，优化前后，秒杀下单请求的 QPS 从300+/sec 提升到了3000+/sec，提升了十倍不止。该项目也为自己带来了不少关于**系统设计、框架使用、缓存使用、代码解耦、性能优化**等的开发经验。

# 教育经历

- 2018.09 ~ 2022.06			****			计算机科学与技术			GPA：5% ~ 10% | CET-4

# 自我评价

本人心态好，抗压能力强，工作认真严谨。对新鲜事物充满好奇，对技术有强烈的兴趣和追求。平时喜欢逛社区，看书，运动等等。热爱技术，拥抱开源，想在程序员这一行业上走得更远。


# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。