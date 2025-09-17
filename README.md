# 👋 你好，我是方文涛

> **Java后端开发工程师** | **华中农业大学硕士在读** | **专注高并发与性能优化**

[![GitHub followers](https://img.shields.io/github/followers/Veloma0602?style=social)](https://github.com/Veloma0602)
[![GitHub stars](https://img.shields.io/github/stars/Veloma0602?style=social)](https://github.com/Veloma0602)
[![Email](https://img.shields.io/badge/Email-veloma0602%40163.com-red)](mailto:veloma0602@163.com)

---

## 🚀 关于我

- 🎓 **华中农业大学（211工程）** 电子信息-计算机应用技术 硕士在读（2023-2026）
- 💼 现任 **Momenta** Java后端开发实习生
- 🔭 专注于 **高并发系统设计**、**微服务架构** 和 **AI应用开发**
- 🌱 持续学习 **Flink源码**、**Spring生态系统** 和 **云原生技术**
- 💡 对 **分布式系统**、**性能优化** 和 **ASPICE合规** 有丰富实践经验
- 🏆 获得学业甲等奖学金（2023-2024）、学业乙等奖学金（2024-2025）

---

## 💼 核心技术栈

### 🔥 后端核心
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=for-the-badge&logo=mybatis&logoColor=white)

### 🗄️ 数据存储
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Caffeine](https://img.shields.io/badge/Caffeine-FF6B6B?style=for-the-badge&logo=caffeine&logoColor=white)

### 🔄 中间件
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Nacos](https://img.shields.io/badge/Nacos-00A9CE?style=for-the-badge&logo=alibaba-cloud&logoColor=white)
![Apache Flink](https://img.shields.io/badge/Apache_Flink-E6526F?style=for-the-badge&logo=apache-flink&logoColor=white)

### 🤖 AI技术
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF9500?style=for-the-badge&logo=openai&logoColor=white)

---



## 🏆 精选项目

### 🤖 [AI健身助手智能体](https://github.com/Veloma0602/ai-fitness-assistant)
**技术栈**: Spring Boot3, Spring AI, RAG, Tool Calling, MCP, ReAct
- **核心亮点**: 基于ReAct模式的自主规划AI智能体
- **功能特性**: 多轮对话、记忆持久化、RAG知识库检索、工具调用
- **技术创新**:
    - 自主实现基于文件系统的ChatMemory + Kryo序列化
    - 对接阿里云百炼知识库，实现云端文档检索
    - 支持通义、Ollama等多种大模型灵活切换

### 🚀 [客户项目导入准出SPA统一平台](https://github.com/Veloma0602/spa-platform)
**技术栈**: Spring Boot, RabbitMQ, Redis, AOP, 策略模式
- **业务价值**: 替代Jama工具，年节省成本40万/项目
- **技术亮点**:
    - 飞书事件回调 + AOP切面实现操作拦截，拦截无效操作300+次
    - 分布式任务管理系统重构，采用策略模式解耦多平台对接
    - RabbitMQ + 死信队列异步处理，系统可用性提升至99.5%

### ⚡ [船舶通信管理综合系统](https://github.com/Veloma0602/ship-communication-system)
**技术栈**: Spring Boot, ThreadPoolExecutor, Redis, RabbitMQ, Neo4j, gRPC
- **高并发设备管理**:
    - ThreadPoolExecutor + CompletableFuture异步批处理，QPS提升至5000+，TP99<100ms
    - Redis分布式锁保障设备状态更新零冲突
    - "缓冲队列+批量提交"机制，250次IO合并为8次批量操作，数据库压力降低40%
- **性能优化实践**:
    - Redis+Caffeine二级缓存，复杂查询响应降低80%
    - 覆盖索引+延迟加载，百万级数据分页查询<200ms
    - CASE WHEN批量更新优化，关键接口TP99从1.2s优化至180ms
- **分布式事务与一致性**:
    - RabbitMQ死信队列实现24小时超时回滚，本地消息表保障最终一致性
    - 事件驱动异步处理+生产者确认，补货通知100%可达
    - READ COMMITTED+乐观锁优化，库存扣减TPS达1200+/s
- **智能规划算法集成**:
    - GA算法+Neo4j存储3万+历史方案，初始种群质量提升30%
    - gRPC集成Python深度学习服务，性能比REST提升40%
    - 布隆过滤器防穿透，知识图谱缓存命中率提升至70%

### 🏫 [狮山云仓校园服务中台系统](https://github.com/Veloma0602/campus-service-platform)
**技术栈**: Spring Boot, MySQL, MyBatis, Redis, RabbitMQ, Caffeine, Nginx
- **项目概述**: 综合校园社区服务平台，集商户发布优惠、用户打卡探店、学生美食外卖为一体
- **核心功能模块**:
    - 用户登录认证、下单购物、优惠券限购秒杀
    - 笔记发布点赞、签到打卡、商户管理
- **技术亮点**:
    - **负载均衡**: Nginx反向代理实现负载均衡，保护后端服务
    - **会话管理**: Redis黑名单防恶意调用，多服务器Session共享
    - **三种下单场景**: 乐观锁、分布式锁、缓存预热+MQ分别处理普通/限购/秒杀
    - **异步优化**: 线程池异步创建订单，控制并发量和吞吐量
    - **社交功能**: ZSet实现点赞排行，Set管理关注关系，BitMap记录签到
- **架构设计**:
    - 服务层：接口调用和业务逻辑
    - 异步任务层：流量削峰和定时任务
    - 数据层：Caffeine+Redis+MySQL三层存储体系

---

## 💡 技术深度

### 🔧 Java核心技术
- **并发编程**: 深入理解ThreadPoolExecutor、CompletableFuture、ConcurrentHashMap、CAS、AQS等
- **JVM调优**: 熟悉内存结构、垃圾回收机制、GC底层算法，有实际调优经验
- **源码研究**: 阅读过ArrayList、HashMap、**Flink部分源码**等核心组件
- **框架原理**: 深入理解Spring IOC、AOP、SpringBoot自动配置机制

### 🚀 分布式系统
- **微服务架构**: Spring Cloud Alibaba技术栈，Nacos注册中心实践
- **消息中间件**: RabbitMQ死信队列、ACK确认、生产者确认机制
- **缓存设计**: Redis + Caffeine二级缓存，分布式锁，布隆过滤器防穿透
- **性能优化**: 覆盖索引、慢SQL分析、CASE WHEN批量更新、乐观锁并发控制

### 🏗️ 架构设计
- **高并发处理**: 缓冲队列+批量提交，流量削峰，异步处理
- **数据一致性**: 分布式事务、本地消息表、最终一致性保障
- **算法集成**: gRPC服务调用、ProtocolBuffers序列化、GA遗传算法
- **图数据库**: Neo4j存储与查询，知识图谱应用

### 🤖 AI应用开发
- **核心概念**: 掌握RAG、Tool Calling、MCP、CoT、ReAct、A2A等
- **实战经验**: 独立开发拥有自主规划能力的AI智能体
- **技术栈**: Spring AI、LangChain4j框架深度应用

---

## 📈 工作经历亮点

### 🏢 Momenta（北京初速度科技有限公司）- Java后端开发实习生
**2025.7 - 至今**

**核心成就:**
- 🎯 **飞书机器人批量消息工具**: 发送时间从2小时优化至10分钟，错误率从8%降至0.5%，年节省人工200+人天
- 🔍 **ASPICE合规平台**: 实现需求-设计-代码-测试全链路追溯，年节省成本40万/项目
- ⚡ **分布式任务管理**: 系统可用性提升至99.5%，解决第三方平台崩溃导致的服务阻塞

### 🚢 中国船舶集团有限公司第七二二研究所 - 后端开发实习生
**2024.3 - 2024.9**

**核心成就:**
- 🚀 **高并发系统**: QPS提升至5000+，支持设备状态零冲突更新，TP99响应<100ms
- 🎯 **性能优化**: 关键接口TP99从1.2s优化至180ms，复杂查询响应降低80%
- 🔒 **分布式事务**: RabbitMQ+本地消息表保障最终一致性，库存扣减TPS达1200+/s
- 🧠 **算法集成**: gRPC集成深度学习服务，性能比REST提升40%，GA算法种群质量提升30%

---


## 🎯 2025年目标

- [ ] 深入研究Flink流计算引擎源码与实践
- [ ] 掌握Kubernetes云原生部署与运维
- [ ] 参与更多开源项目贡献
- [ ] 学习并应用更多AI技术与框架

---

## 🏆 荣誉成就

- 🥇 **华中农业大学学业甲等奖学金**（2023-2024）
- 🥈 **华中农业大学学业乙等奖学金**（2024-2025）
- 🌟 **成都大学英才奖学金**（2020-2021）
- 📜 **CET-4英语四级证书**

---

## 🤝 联系方式

[![Email](https://img.shields.io/badge/Email-veloma0602%40163.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:veloma0602@163.com)
[![GitHub](https://img.shields.io/badge/GitHub-Veloma0602-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Veloma0602)

---

<div align="center">

**💻 "用技术创造价值，以代码改变世界"**

*专注Java后端开发 | 热爱技术分享 | 追求极致性能*

![Profile Views](https://komarev.com/ghpvc/?username=Veloma0602&color=brightgreen&style=flat-square&label=访问量)

</div>