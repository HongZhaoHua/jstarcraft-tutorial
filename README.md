# JStarCraft Framework

****

一套涵盖核心编程,人工智能,数字图像处理,自然语言处理,推荐与搜索,云服务领域的Java框架.

****

## JStarCraft Core

目标是提供一个通用的Java核心编程框架,作为搭建其它框架或者项目的基础.

让相关领域的研发人员能够专注高层设计而不用关注底层实现.

涵盖了缓存,存储,编解码,资源,脚本,监控,通讯,事件,事务9个方面.

[https://github.com/HongZhaoHua/jstarcraft-core](https://github.com/HongZhaoHua/jstarcraft-core)

| 日期 | 变更记录 |
| :----: | :----: |
| 2020.04.16 | common模块script包:<br/>支持5种脚本语言(Groovy/JS/Lua/Python/Ruby) |
| 2019.05.01 | common模块selection包:<br/>支持4种查询表达式(CSS/JSONPath/RegExp/XPath)<br/>支持5种查询内容(JSON/HTML/Swing/Text/XML) |
| 2019.05.08 | transaction模块:<br/>支持7种分布式锁(Cassandra/ElasticSearch/Hazelcast/Hibernate/Mongo/Redis/ZooKeeper) |
| 2019.05.11 | common模块instant包:<br/>支持5种日期时间表达式(阳历/阴历/伊斯兰历/节气/间隔) |
| 2019.06.03 | event模块:<br/>支持2种事件模式(Queue/Topic)<br/>兼容9种消息传递协议/组件(AMQP/JMS/Memory/MQTT/RabbitMQ/Redis/RocketMQ/STOMP/Vert.x) |
| 2019.06.11 | event模块:<br/>支持2种事件模式(Queue/Topic)<br/>兼容10种消息传递协议/组件(AMQP/JMS/Kafka/Memory/MQTT/RabbitMQ/Redis/RocketMQ/STOMP/Vert.x) |
| 2019.06.30 | storage模块:<br/>支持1种键值数据库(Berkeley DB)<br/>支持3种文档数据库(Elasticsearch/Lucene/Mongo DB)<br/>支持2种关系数据库(Hibernate/MyBatis)<br/>支持1种图数据库(Neo4j) |

****

## JStarCraft Cloud

目标是提供一个通用的中间件抽象层,作为微服务项目的基础.

使得研发人员能够在各种实现层(配置中心/注册中心/任务调度/网关/云服务)之间无缝切换.

涵盖了配置管理,注册管理,灰度隔离,链路追踪,任务调度,网关和云服务7个方面

[https://github.com/HongZhaoHua/jstarcraft-cloud](https://github.com/HongZhaoHua/jstarcraft-cloud)

****

## JStarCraft AI

目标是提供一个完整的Java机器学习框架,作为人工智能在学术界与工业界的桥梁.

让相关领域的研发人员能够在各种软硬件环境/数据结构/算法/模型之间无缝切换.

涵盖了从**数据处理**到**模型的训练与评估**各个环节,支持硬件加速和并行计算,是最快最全的Java机器学习库.

[https://github.com/HongZhaoHua/jstarcraft-ai](https://github.com/HongZhaoHua/jstarcraft-ai)

| 日期 | 变更记录 |
| :----: | :----: |
| 2020.05.14 | math模块structure包:<br/>支持10种向量结构 |
| 2020.05.14 | math模块algorithm包:<br/>支持5种文本局部敏感哈希 |
| 2020.05.20 | math模块algorithm包:<br/>支持TF-IDF与BM25 |
| 2020.06.09 | math模块algorithm包:<br/>支持20种核技巧 |
| 2020.06.09 | math模块algorithm包:<br/>支持核距离与核相似度 |
| 2020.07.07 | math模块algorithm包:<br/>支持微积分导数 |

****

## JStarCraft DIP

专注于解决数字图像处理领域的几个核心问题:**图像转换,图像相似度,目标定位,目标检测,图像分割,图像聚类和图像分类**.

为相关领域的研发人员提供完整的通用设计与参考实现.

涵盖了多种数字图像处理,计算机视觉,计算机图形算法.

[https://github.com/HongZhaoHua/jstarcraft-dip](https://github.com/HongZhaoHua/jstarcraft-dip)

| 日期 | 变更记录 |
| :----: | :----: |
| 2020.05.30 | 支持4种图像局部敏感哈希 |
| 2020.06.05 | 支持9种图像局部敏感哈希 |

****

## JStarCraft NLP

专注于解决自然语言处理领域的几个核心问题:**词法分析,句法分析,语义分析,语种检测,信息抽取,文本聚类和文本分类**.

为相关领域的研发人员提供完整的通用设计与参考实现.

涵盖了多种自然语言处理算法,适配了多个自然语言处理框架.

兼容**Lucene/Solr/ElasticSearch**插件.

[https://github.com/HongZhaoHua/jstarcraft-nlp](https://github.com/HongZhaoHua/jstarcraft-nlp)

| 日期 | 变更记录 |
| :----: | :----: |
| 2020.04.11 | extraction模块detection包:<br/>支持406种语言的语种检测 |

****

## JStarCraft RNS

专注于解决推荐领域与搜索领域的两个核心问题:**排序预测(Ranking)和评分预测(Rating)**.

为相关领域的研发人员提供完整的通用设计与参考实现.

涵盖了70多种排序预测与评分预测算法,是最快最全的Java推荐与搜索引擎.

[https://github.com/HongZhaoHua/jstarcraft-rns](https://github.com/HongZhaoHua/jstarcraft-rns)

| 日期 | 变更记录 |
| :----: | :----: |
|  |  |

****

## JStarCraft Example

基于JStarCraft RNS引擎,Spring Boot框架和公共数据集搭建的千人千面演示项目. 

系统会根据用户的行为记录,自动调整用户的推荐内容和搜索内容.使用者可以通过该项目了解**推荐系统**与**搜索系统**的运作流程. 

涵盖了个性化推荐与个性化搜索2个部分.

[https://github.com/HongZhaoHua/jstarcraft-example](https://github.com/HongZhaoHua/jstarcraft-example)

| 日期 | 变更记录 |
| :----: | :----: |
|  |  |

****