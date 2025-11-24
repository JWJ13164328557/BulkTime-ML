BulkTime-ML：时间序列 bulk RNA-seq 多模型机器学习整合流程

本流程 (BulkTime-ML) 是一个 端到端（end-to-end） 的 bulk RNA-seq 时间序列分析框架，特别面向如下任务：

预测干旱天数 / 时间进程等连续变量（regression）

从高维转录组中稳定识别关键特征基因（feature selection）

结合 11 种机器学习模型比较性能

提取多模型共识基因（consensus genes）

使用 Spearman 显式统计检验 & ρ 敏感性分析选择稳健时间相关基因

用 GAM（spline）识别非线性时间动态基因

包含 LOPO（Leave-One-Day-Out）验证、Nested-CV 嵌套交叉验证、PC1 轨迹可视化等

本脚本包含数据预处理、建模、显著性分析与可视化的完整代码
