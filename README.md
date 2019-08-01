# 集合类

HashMap 原理

HashMap与HashTable的区别

ConcurrentHashMap原理

ArrayList原理

注：自己总结的集合类



# 数据库 

mysql数据库优化、索引、索引失效的情况 

数据库的行锁、表锁、死锁 

数据库索引的数据结构 B+Tree 

分库分区分表的实现

使用mycat分库如何知道你查询的是哪个数据库 



备注：完善MYSQL思维导图并记忆



# SSM

spring的了解、AOP（运用的场景：例如异常、权限控制、日志；且能说出一种场景的具体配置）、IOC 

spring的核心  

谈谈对Spring的认识，对DUBBO认识 原理！！！ 对SpringBoot认识 原理，SpringBoot常用注解，对SpringCloud框架理解（简历项目涉及哪个框架问哪个）！！！！非常重要！！！！！必问！！！

Spring有哪些核心组件，AOP(运用的场景：例如异常、权限控制、日志；且能说出一种场景的具体配置)和IOC， AOP的配置以及注解，IOC的注入(必问)！！！！

声明式事物的方式  

## 事务的传播性，说说你是怎么配置声明式事务的 非常重要！！！！ 



我需要发送一封邮件，在spring刚完成初始化，在把这个邮件发出去，说出你的办法

## springmvc工作流程



## Mybatis中的#{}和&的区别 防SQL注入非常 经常 常常 问！！！

```
#{}表示一个占位符号
${}表示拼接SQL串

name LIKE CONCAT('%',#{name},'%') 
```



注：在网上搜索答案



# 微服务

springcloud 

Docker的原理 

dubbo的原理   

zookeeper的原理  

dubbo在你的项目中做什么的  



注：迅速看视频+网上资料，整理

# 缓存

redis线程模式 

用了哪些缓存机制 

redis支持的数据类型  

ehcache的原理 

Redis的配置，redis客户端使用的是什么，REDIS怎么实现 +1台服务器 —1台服务器（选问）

Redis的集群是怎么配置的，具体的

熟悉REDIS，REDIS线程模式，REDIS集群数据同步，存储，持久化实现过程 

用过哪些缓存（REDIS,Ehcache,Memcache）,三者之间的区别 

redis的用法原理

redis集群 



注：看已经总结的redis够了

# 消息队列

用过哪些消息队列 

activemq在项目中的应用  

MQ项目中使用场景？你的理解？MQ如果收不到信息怎么处理？（非常重要）！！！！



注：看已经总结的mq消息队列，够了

# 多线程

CAS操作的具体过程 

CAS操作的具体过程（加分） 

熟悉高并发情况下怎么保证线程安全 



注：第二季面试总结

# 高并发

高并发处理方案

分布式锁



# 设计模式

工厂模式的种类 

手写一个单例模式（懒汉式） 

熟悉JAVA设计模式，单利模式，特别是高并发情况下怎么实现单利模式（重点） 

有没有看过关于设计模式的书籍  

# 数据结构

斐波那契 

```java
public void test(int i){
    if(i == 1|| i ==2){
        return 1;
    }else{
        return test(i-1)+test(i-2);
    }
}
```

注：数据结构视频过一下

# JVM

对于堆栈的了解



注：第二季面试总结

# 其他

## java1.8新特性 



## Sleep和wait方法的区别，各自具体的用法

<https://www.cnblogs.com/loren-Yang/p/7538482.html> 

## NGINX的配置，负载均衡的策略。

<https://www.cnblogs.com/1214804270hacker/p/9325150.html> 

## String底层equals方法原理 

<https://blog.csdn.net/yygangzi/article/details/70143111> 

## String,StringBulider,区别

<https://blog.csdn.net/u011702479/article/details/82262823> 

## 单点登录业务逻辑 

<https://www.cnblogs.com/itdragon/p/8094722.html> 

注：上网查找