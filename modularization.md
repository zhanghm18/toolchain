[[toc]]


# 要解决的问题


* 如何构建模块化程度高、易于维护的应用系统


# 解决方案


通过对世界的认知，形成不同的组织原则即抽象，用于简化并指导系统的实现。


# 解决方案案例


## 用户界面交互系统


### Reactive Programming - RxJS


RxJS 提供了针对异步事件的 Observable 接口，可以将其视为流的一种形式，通过订阅流，每个过程执行一系列操作和变换后形成新的流，
从而完成整个流程。


### Vue/React


Vue 和 React 都采用声明式语法，提供以组件（Component）为基础的前端框架，帮助组织复杂的交互式前端系统。


## OLTP


### 函数式编程


在业务建模面临的问题中，很大一部分涉及到对象的变化，传统的基于局部状态和赋值的编程模型无法提供简单、易于使用的抽象模型，
所以，基于流的编程模型将时间和对象视为整体抽象，也就是函数式编程。


#### Lisp Streams


#### Haskell


## OLAP


### 批处理系统


随着 IT 数据规模的增长，需要提供一种编程模型，用以构建海量数据的应用服务，Google 提出的 map/reduce 模型便是一种应用非常广泛的编程模型。


#### Hadoop


#### Spark


### 流处理系统


批处理系统的往往用在时效性要求不高的应用中，为了提供更加优质的数据服务，结合在线服务和离线数据分析服务特点的流处理系统应运而生，
其中比较具有代表性的有 Flink、Storm、Spark Streaming、Kafka Streaming。


#### Flink


