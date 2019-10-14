# Spring-Cloud-Demo
Spring Cloud 基础组件学习库

## 一、微服务
在过去的几年间，“微服务架构”这几个字在技术圈内应该是最亮眼的。“微服务”其实是描述的一种软件设计和部署的方式。我们判断一个系统是否属于微服务架构，是根据系统中的服务是否是以服务套件的方式独立部署来判断的。

“微服务”这一概念最早出现于2012年，是出自于软件大师Martin Fowler的一篇文章《Microservices》，有兴趣可以点击链接去看看大师是怎么定义微服务的。

## 二、Spring Cloud 简介
Spring Cloud 作为微服务的实践， 为开发人员提供了快速构建分布式系统中的一些常见模式的工具链，其中包括 服务发现、配置管理、熔断器、API网关、服务总线、消息驱动、负载均衡、远程调用等常用的分布式解决方案组件。

Spring 是将我们日常开发中一些设计模式给组合在一起，使我们开发Web应用时能更加便捷，Spring Cloud 是将我们在分布式系统开发中用到一些常用的解决方案通过组件的方式组合在一起，以便我们能更快的、更好的来构建一个稳定、高效、容错的分布式应用。

## 三、Spring Cloud 组件
微服务体系结构的核心思想是构建多个独立的服务，由这些独立的服务来构成一个可靠且容错的分布式系统。在使用微服务来构建系统时，核心任务之一就是定义基础设施与应用的边界，合理切分复杂性，减少应用开发者需要面对的复杂性。Spring Cloud 作为一个微服务架构的解决方案，已经为我们切分出了一些构建分布式系统一些基础设施服务，我们通过采用这些已经经过社区实践的基础设施服务，能大大减少我们的工作量。下面我们就一些来学习如下Spring Cloud 的一些基础组件。

- Spring Cloud Eureka 服务注册于发现
 [Spring Cloud Eureka 服务治理（注册与发现）](http://gangb.info/?p=57)	
- Spring Cloud Config 配置中心
- Spring Cloud Ribbon 软负载
- Spring Cloud Feign 声明式服务间远程调用
- Spring Cloud Zuul Api网关 （2.x停止维护）
- Spring Cloud Gateway Api网关 （Zuul替代组件）
- Spring Cloud Hystrix 熔断器 （停止维护）
- Spring Cloud Bus 服务总线
- Spring Cloud Stream 消息驱动