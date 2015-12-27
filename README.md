# Fast-and-General-Data-Processing-on-Large-Clusters
本文为`Matei Alexandru Zaharia`博士毕业论文的翻译，该论文探讨了spark中rdd、shark、d-stream的实现原理、架构以及其优缺点,论文为：[An Architecture for Fast and General Data Processing on Large Clusters](https://www.google.com.hk/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwiK3ona7uvJAhXl2aYKHR_4AGAQFggaMAA&url=%68%74%74%70%3a%2f%2f%77%77%77%2e%65%65%63%73%2e%62%65%72%6b%65%6c%65%79%2e%65%64%75%2f%50%75%62%73%2f%54%65%63%68%52%70%74%73%2f%32%30%31%34%2f%45%45%43%53%2d%32%30%31%34%2d%31%32%2e%70%64%66&usg=AFQjCNHv-NLuhL_H1jA7wyPxl24FROakzw)

论文目录如下：

* [综述](introduction/readme.md)
  * [专业系统的缺点](introduction/problems-with-specialized-systems.md)
  * [弹性分布式数据集（RDD）](introduction/rdds.md)
  * [RDD上实现的模型](introduction/models-implemented-on-rdds.md)
  * [结论](introduction/summary-of-results.md)
* [弹性分布式数据集](rdd/introduction.md)
  * [介绍](rdd/introduction.md)
  * [rdd抽象](rdd/rdd-abstraction.md)
  * [spark接口](rdd/spark-programming-interface.md)
  * [rdd表示](rdd/representing-rdds.md)
  * [实现](rdd/implementation.md)
  * [评价](rdd/evaluation.md)
  * [讨论](rdd/discussion.md)
* [建立在rdd上的模型](models-built-over-rdds/introduction.md)
  * [介绍](models-built-over-rdds/introduction.md)
  * [实现其它基于rdd的模型的技术](models-built-over-rdds/techniques-for-implementing-other-models-on-rdds.md)
  * [rdd上的sql（已经过时）](models-built-over-rdds/sql-on-rdds.md)
  * [实现](models-built-over-rdds/implementation.md)
  * [性能](models-built-over-rdds/performance.md)
  * [联合复杂分析和sql](models-built-over-rdds/combining-sql-with-complex-analytics.md)
* [离散化数据流](discretized-streams/introduction.md)
  * [介绍](discretized-streams/introduction.md)
  * [目标和背景](discretized-streams/goals-and-background.md)
  * [离散化数据流(D-Streams)](discretized-streams/discretized-streams.md)
  * [系统架构](discretized-streams/system-architecture.md)
  * [错误恢复](discretized-streams/fault-and-straggler-recovery.md)
  * [评价](discretized-streams/evaluation.md)
* [rdd概论](generality-of-rdds/introduction.md)
  * [介绍](generality-of-rdds/introduction.md)
  * [表达视角](generality-of-rdds/expressiveness-perspective.md)
  * [系统视角](generality-of-rdds/systems-perspective.md)
  * [限制和扩展](generality-of-rdds/limitations-and-extensions.md)
* [总结](conclusion/lessons-learned.md)
