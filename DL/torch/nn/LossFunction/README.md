# 损失函数（LossFunction）
## 二元交叉熵损失(BCELoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/BCELoss.ipynb)
BCELoss 的全称为二元交叉熵损失函数（Binary Cross Entropy Loss），是用于二分类问题中的常用损失函数之一。

## 带logits的二元交叉熵损失(BCEWithLogitsLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/BCEWithLogitsLoss.ipynb)
这种损失将Sigmoid层和BCELoss结合在一个类中。

## 余弦嵌入损失(CosineEmbeddingLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/CosineEmbeddingLoss.ipynb)
CosineEmbeddingLoss将输入的两个向量及它们的标签作为输入，并计算它们之间的余弦相似度。如果它们的标签相同，则目标是最小化它们之间的距离，否则目标是最大化它们之间的距离。

## 交叉熵损失(CrossEntropyLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/CrossEntropyLoss.ipynb)
计算input logits和目标之间的交叉熵损失。

## CTC损失(CTCLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/CTCLoss.ipynb)
CTCLoss将输入的预测标签和真实标签作为输入，并计算它们之间的CTC损失。CTC损失是一种无需对齐的损失函数，它允许模型根据输入序列的内容自动对齐标签。具体来说，它在计算损失时考虑了所有可能的对齐路径，而不仅仅是一一对应的路径。

## 合页嵌入损失(HingeEmbeddingLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/HingeEmbeddingLoss.ipynb)
评价两个向量的相似度，标签y=1是，表示应该相似，y=-1时表示应该疏远。x表示距离，如果y=1，距离越大损失越大；如果y=-1，距离越小损失越大。

## Huber损失(HuberLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/HuberLoss.ipynb)
L1Loss和L2Loss的结合，可以避免L2下梯度过大的问题，也解决了L1下梯度剧变的问题。

## KL散度损失(KLDivLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/KLDivLoss.ipynb)
在机器学习中，P往往用来表示样本的真实分布，Q用来表示模型所预测的分布，那么KL散度就可以计算两个分布的差异，也就是Loss值。

## 绝对误差损失(L1Loss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/L1Loss.ipynb)
用于测量输入x和目标y中每个元素之间的平均绝对误差(MAE)

## 带间隔的排名损失(MarginRankingLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/MarginRankingLoss.ipynb)
Margin Ranking Loss通常用于排序任务，特别是在训练学习排名（Learning to Rank）模型时

## 平均误差损失(MSELoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/MSELoss.ipynb)
测量输入x和目标y中每个元素之间的均方误差(L2范数的平方)。


## 带间隔的多分类多标签损失(MultiLabelMarginLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/MultiLabelMarginLoss.ipynb)

## 带间隔的多分类损失(MultiMarginLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/MultiMarginLoss.ipynb)

## 负对数似然损失(NLLLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/NLLLoss.ipynb)

## 平滑L1损失(SmoothL1Loss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/SmoothL1Loss.ipynb)
SmoothL1Loss 的中文全称为平滑 L1 损失函数，也称为 Huber 损失函数的平滑版本。该损失函数通常用于回归问题中，可以在一定程度上减少离群点的影响。

## 软边际损失(SoftMarginLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/SoftMarginLoss.ipynb) 
创建一个标准，优化输入张量x和目标张量y(包含1或-1)之间的两类分类任务。


## 三元组间隔损失(TripletMarginLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/TripletMarginLoss.ipynb)
三元组损失. 由 a, p 和 n构成(anchor, positive 和 negative). 让a和p更近，a和n更远。典型应用场景：人脸识别


## 带举例的三元组间隔损失(TripletMarginWithDistanceLoss)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/LossFunction/TripletMarginWithDistanceLoss.ipynb)
和TripletMarginLoss相比，可以自定义计算距离的公式





