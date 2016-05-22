gRPC学习笔记
===========

> 注: 如果你看到的是github的源代码, 请点击 [这里](http://skyao.github.io/leaning-grpc/) 查看html静态内容.

# 介绍

gRPC是google最新发布(2015年2月底)的开源RPC框架, 声称是"一个高性能，开源，将移动和HTTP/2放在首位的通用的RPC框架.". 技术栈非常的新, 基于HTTP/2, netty4.1, proto3, 拥有非常丰富而实用的特性, 堪称新一代RPC框架的典范.

这份学习笔记记录google gRPC学习过程中的各种资料和信息，已经实际使用过程的心得, 另外针对性的翻译了部分特别有价值的英文资料。

> 注: **grpc目前已经进入beta阶段**, 最新版本0.14.0, API版本已经基本稳定，可以在正式产品中使用. 当然，期待正式版尽快发布!

# 实践

在2016年3月，我开始带领团队基于gPRC构建自己公司的RPC框架，基本技术选型是以gRPC + springboot + consul，希望构建一个性能良好，架构优雅，使用方便的微服务框架。

目前进展顺利，这个名为 `Dolphin` 的微服务框架，按照计划会在2016年底代码基本稳定时开源，敬请期待。

# 内容

* [gPRC 介绍](introduction/index.md)
    * [资料收集整理](introduction/information.md)
    * [Protocol Buffer 3](proto3/index.md)
* [gPRC文档](grpc/index.md)
    * [gRPC官方文档(中文版)](grpc/official_docs.md)
    * [gRPC动机和设计原则](grpc/motivation.md)
    * [源码导航](grpc/source_navigating.md)
* [Channel层](channel/index.md)
* [Stub层](stub/index.md)
* [客户端流程](client/index.md)
* [服务器端流程](server/index.md)
* [实战](action/index.md)
	* [集成Spring Boot](action/springboot/springboot.md)
	* [文档生成](action/documentation/index.md)

内容陆续添加中......

