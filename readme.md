# “观云识天”-机器图像算法赛道-天气识别


## 实验概述

训练所用方法：  
- 数据增强(放缩、随机大小裁剪、翻转)，Auto_augment，随机擦除（RandomErasing）
- 学习率：RAdam，Lookahead
- 半精度训练（APEX）
- Random Image Cropping And Patching（RICAP）
- 模型：采用EfficientB3


其他：
- 数据分析（EDA，不平衡过采样）

## 结果

训练集：验证集=9：1，验证集0.85左右。

