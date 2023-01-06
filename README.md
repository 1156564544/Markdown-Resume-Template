 <center>
     <h1>张米志鹏的个人简历</h1>
 </center>

## 个人信息 

* 性 别：男 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; 年 龄：22  
* 手 机：15307387999 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; 邮 箱：1156564544@sjtu.edu.cn   

## 教育经历
  
* 上海交通大学&emsp;&emsp;&emsp;&emsp;&emsp;2021.9~2024.3 &emsp;&emsp;&emsp;&emsp;计算机技术专业-硕士
* 上海交通大学&emsp;&emsp;&emsp;&emsp;&emsp;2017.9~2021.7&emsp;&emsp;&emsp;&emsp; 计算机科学与技术专业-本科  

## 专业技能

* 熟练使用 Go，了解 C、C++、Python 等编程语言
* 掌握基础数据结构和算法、操作系统、网络、数据库的基本原理
* 掌握分布式系统容灾与恢复、一致性协议的基本原理
* 熟悉开源存储组件GFS、leveldb的原理与设计，了解leveldb源码

## 项目经历

1. MIT-6.824-Project &emsp;&emsp;&emsp;&emsp; 项目地址：[https://github.com/1156564544/MIT6.824-projects ](https://github.com/1156564544/MIT6.824-projects)
    * 基于go实现一个MapReduce框架，来处理单词计数问题；基于go实现Raft强一致性协议；基于实现的Raft协议实现分布式键值存储

2. CS-15-445-Project &emsp;&emsp;&emsp;&emsp; 项目地址：[https://github.com/1156564544/bustub ](https://github.com/1156564544/bustub)  
    * 实现一个DBMS的内存池管理模块；基于实现的内存池管理模块实现一个可扩展哈希索引（Extendible Hash Index）；实现DBMS中的查询处理模块

3. 分布式对象存储原型系统 &emsp;&emsp;&emsp; 项目地址：[https://github.com/1156564544/oss ](https://github.com/1156564544/oss) 
    * 基于go实现的一个高并发的对象存储原型系统，包括：分布式数据存储、分布式接口服务、基于redis实现的消息队列广播心跳、基于elasticSearch实现的元数据管理、对上传的对象基于SHA256验证哈希值、基于RS纠删码实现的数据冗余与即时恢复、断点上传与下载、基于gzip算法进行数据压缩、用户鉴权与权限管理及一个简易的客户端
    
4. Linux下基于c++实现的web服务器 &emsp;&emsp;&emsp; 项目地址：[https://github.com/1156564544/webServer ](https://github.com/1156564544/webServer)
    * 主要技术栈：线程池+非阻塞socket+epoll多路复用+并发事件处理+状态机解析http请求+信号捕捉处理+管道通信

## 实习经历
1. 阿里云-盘古分布式存储-繁忙节点场景下的纠删码快速降级读和恢复 &emsp;&emsp;&emsp; 时间：2022.9~2022.12
    * 盘古现有的基于纠删码的恢复方案基本忽略了高负载场景下繁忙节点相比其他节点的性能表现的差异，并且没有考虑节点上的负载波动和负载差异。为了解决这一问题，我们设计一种调度策略综合考虑节点之间的负载差异以及节点上的实时负载变化，自适应的动态分配恢复任务并且实现负载均衡的恢复调度方案
    * 我们实现了一个原型系统来模拟盘古目前的恢复策略和我们新提出的恢复策略，实验表明我们的方法在200个节点时相比盘古现有的方法可以提高大概两倍的吞吐量
