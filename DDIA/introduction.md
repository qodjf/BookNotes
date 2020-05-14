# 数据密集型应用系统设计

分类：实用性

## 谈了些什么
本书旨在帮助大家更好地驾驭**处理数据** (computing) 和**存储数据** (storage) 相关技术。它不是针对某个特定软件的介绍手册，也不是纯理论的习题。

我们将对某些典型系统深入展开讨论，梳理其**核心算法**，探讨其**设计理念**和背后的**权衡之道**。在此过程中，尝试总结某些经验法则来重新审视系统架构。

## 想要解决的问题
* 如何构建具有扩展性、高性能、可靠性和高可用的系统
* 背后的设计理念
* 哪些技术和工具适用于哪些场景，如何最佳使用，有哪些坑，如何搭配

## 纲要
分为三大部分
#### 支撑数据密集型应用系统所需的若干基本原则
1. 目标：可靠性、可扩展性、可维护性。目标是什么以及如何达成目标。
2. 数据模型和查询语言：对比，讨论各自的适用场景
3. 存储引擎：数据库如何在磁盘上分布数据以快速查询
4. 数据编码：序列化，以及模式随时间的演化
#### 由单机转向分布式（扩展性）
5. 复制
6. 分区
7. 事务
8. 分布式系统的挑战
9. 分布式系统如何达成一致性和共识
#### 产生派生数据的系统（如何处理数据）
10. 批处理
11. 流式处理
12. 数据系统的未来展望