# DMD_sector_rotation
Code covering DMD sector rotation strategy

# 时间序列中的动态模态分解
动态模态分解 (dynamic mode decomposition) 最早是被用来分析流体（例如水流）的动态过程，它可以把复杂的流动过程分解为低秩的时空特征 (low-rank spatiotemporal features)，这种方法的强大之处在于它不依赖于动态系统中的任何主方程。作为衍生，动态模态分解可以被用来分析多元时间序列 (multivariate time series)，进行短期未来状态预测。

动态模态分解是一种数据驱动的方法，其在描述一些动态过程时具有很多优势，包括：
动态模态分解不依赖于任何给定的动态系统表达式；
不同于奇异值分解，动态模态分解可以做短期状态预测，即模型本身具备预测能力。

本期文章为大家简要介绍该模型的原理。 https://mp.weixin.qq.com/s/rkiXjhO7KxmMli-4gieKdg
