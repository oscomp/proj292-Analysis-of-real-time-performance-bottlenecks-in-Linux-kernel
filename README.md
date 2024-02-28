# proj292-Analysis-of-real-time-performance-bottlenecks-in-Linux-kernel
Linux内核实时性能瓶颈分析（在stress-ng压力测试条件下）

## 项目描述

在实时计算领域，Linux内核的性能表现尤为关键。尽管Linux提供了PREEMPT_RT补丁等增强实时性的手段，但在极端负载条件下，如使用stress-ng工具进行压力测试时，内核的实时性能瓶颈仍然显现。本项目旨在深入分析Linux内核在应对stress-ng压力测试时的实时性能瓶颈，识别关键的延迟源，并提出有效的优化措施。

## 预期目标

- 利用stress-ng工具对Linux内核进行压力测试，模拟高负载环境下的实时性能场景。
- 在压力测试条件下，利用ftrace等工具分析Linux内核遇到的实时性能瓶颈和延迟源。
- 提出并实现优化策略，以改善Linux内核在stress-ng测试条件下的实时性能表现。
- 通过对比优化前后的性能数据，验证所提出优化措施的有效性。


## 特征

- 专注于在高负载条件下分析和优化Linux内核的实时性能。
- 要求参赛者具备Linux内核知识和性能分析技能。
- 鼓励采用创新的方法和技术来识别和解决性能问题。
- 优化成果应贡献给开源社区，采用GPL-3.0 License。


## 已有参考资料

- stress-ng官方文档和使用指南
- Linux PREEMPT_RT补丁和相关实时性能优化文档
- Linux性能分析工具，如Ftrace、Perf和BPF工具
- 《高性能Linux内核调优》和其他Linux性能优化相关书籍

## 赛题分类

- 内核完善

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

- 高等

## License

GPL-3.0 License

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

- 姓名：刘冬华
- 单位：国科环宇
- email：[donghua.liu@ucas.com.cn](mailto:donghua.liu@ucas.com.cn)
