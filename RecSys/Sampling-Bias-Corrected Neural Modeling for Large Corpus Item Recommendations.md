# Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations

## 论文信息
- **标题**: Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations
- **文件路径**: /home/runner/work/Papers/Papers/RecSys/Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations.pdf

## 主要内容

### 摘要

本文针对大规模语料库物品推荐中的采样偏差问题，提出了采样偏差校正的神经网络建模方法。主要解决双塔模型中批内负采样的训练纠偏问题。

### 主要贡献

1. 分析了双塔模型中批内负采样导致的采样偏差问题
2. 提出了采样偏差校正的神经网络建模方法
3. 在大规模推荐系统中验证了方法的有效性

### 方法/技术

- **双塔召回模型**: 用户塔和物品塔分别编码用户和物品特征
- **批内负采样**: 利用同一批次内的其他样本作为负样本
- **偏差校正**: 通过理论分析和算法设计校正采样偏差
- **温度参数**: 温度系数对性能的影响很大，需要仔细调优

### 实验结果

实验表明温度参数对性能有显著影响，说明在应用归一化时需要仔细调整该参数。偏差校正方法能够有效提升模型在大规模语料库上的推荐性能。

### 结论

采样偏差是大规模推荐系统中的重要问题，通过适当的偏差校正方法可以显著提升双塔模型的推荐效果。

### 个人笔记

- 批内负采样是双塔模型训练的常用技巧，但会引入采样偏差
- 温度参数的调优在对比学习中至关重要
- 这类纠偏方法对工业级推荐系统具有重要意义


