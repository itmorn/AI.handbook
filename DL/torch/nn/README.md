# 卷积（Convolution）
## 卷积（Conv）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/Conv.ipynb)  常规使用场景为下采样，即对张量局部特征进行汇总计算。    

## 转置卷积（ConvTranspose）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/ConvTranspose.ipynb)  常规使用场景为上采样，即对张量局部特征进行插值计算。    

## 拆分（Unfold）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/Unford.ipynb) 从batched input tensor中提取滑动局部块，即对一个大的张量拆分成一叠小张量，并以列的方式进行输出。   

## 折叠（Fold）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/Ford.ipynb) Unfold是负责拆分的，Fold与之相反，是负责折叠的，即将一叠小张量合并为一个大张量。用户可以自己指定合并方式，小张量重叠的位置会相加。   





# 池化（Pooling）
## 最大值池化（MaxPool）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Pooling/MaxPool.ipynb) 使用最大值进行池化  

## 最大值反向池化（MaxUnpool）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Pooling/MaxUnpool.ipynb) 将最大值池化的结果逆向  

## 平均值池化（AvgPool）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Pooling/AvgPool.ipynb) 使用平均值进行池化  

## 分数最大值池化（FractionalMaxPool）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Pooling/FractionalMaxPool.ipynb) 用户可以指定一个分数，该算子在执行最大值池化的同时，使得输出的尺寸 = 输入尺寸 * 分数  

## 幂平均池化（FractionalMaxPool）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Pooling/LPPool.ipynb) 和平均池化类似，区别在于加和之前先对每个元素取p次方，再求和，最后再开p次根号  

## 自适应最大值池化（AdaptiveMaxPool）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Pooling/AdaptiveMaxPool.ipynb) 对由多个输入平面组成的输入信号上应用二维自适应最大池化。用户只需要指定一个输出尺寸，该算子会自动采用池化策略。  

## 自适应平均值池化（AdaptiveAvgPool）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Pooling/AdaptiveAvgPool.ipynb) 对由多个输入平面组成的输入信号上应用二维自适应平均池化。用户只需要指定一个输出尺寸，该算子会自动采用池化策略。  





# 填充（Padding）
## 镜像填充（ReflectionPad）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Padding/ReflectionPad.ipynb) 使用输入边界的镜像来填充输入张量。

## 重复填充（ReplicationPad）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Padding/ReplicationPad.ipynb) 使用距离卷积核最近的元素填充输入张量。

## 零填充（ZeroPad）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Padding/ZeroPad.ipynb) 使用0填充输入张量。

## 常量填充（ConstantPad）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Padding/ConstantPad.ipynb) 使用常量填充输入张量。



# 激活函数（Activations）
## element-wise汇总
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Activations/element-wise.ipynb) 


## vector-wise汇总
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Activations/vector-wise.ipynb)


# 规范化（Normalization）
Norm对比:
<p align="center">
<img src="./Normalization/imgs/4类Norm对比.png"
    width="2000" /></p>

## 批量归一化（BatchNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/BatchNorm.ipynb)  NCHW 在NHW维度上求均值和方差

## 层归一化（LayerNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/LayerNorm.ipynb)  NCHW 在CHW维度上求均值和方差

## 实例归一化（InstanceNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/InstanceNorm.ipynb)  NCHW 在HW维度上求均值和方差

## 组归一化（GroupNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/GroupNorm.ipynb)  层归一化和实例归一化的折中，即，将输入的通道分组，在组内执行层归一化，而实例归一化是在分组数=通道数时候的特例。




# 循环神经网络（Recurrent）
1. 循环神经网络(recurrent neural network)是时间上的展开,处理的是序列结构的信息,是有环图
2. 递归神经网络(recursive neural network)是空间上的展开,处理的是树状结构的信息,是无环图

## 循环神经网络单元（RNNCell）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Recurrent/RNNCell.ipynb)  

## 循环神经网络（RNN）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Recurrent/RNN.ipynb)  

## LSTM网络单元（LSTMCell）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Recurrent/LSTMCell.ipynb)  

## LSTM神经网络（LSTM）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Recurrent/LSTM.ipynb)  

## GRU网络单元（GRUCell）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Recurrent/GRUCell.ipynb)  

## GRU神经网络（GRU）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Recurrent/GRU.ipynb)  




# 线性网络（Linear）
## 线性层/全连接层（Linear）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Linear/Linear.ipynb)

## 双线性层（Bilinear）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Linear/Bilinear.ipynb)



# 循环神经网络（Dropout）
## 丢弃法（Dropout）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Dropout/Dropout.ipynb)



# 稀疏网络（Sparse）
## 嵌入（Embedding）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Sparse/Embedding.ipynb)

## 嵌入并汇总（EmbeddingBag）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Sparse/EmbeddingBag.ipynb)



# 距离公式（DistanceFunction）
## 余弦相似度（CosineSimilarity）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/DistanceFunction/CosineSimilarity.ipynb)

## Pairwise距离（PairwiseDistance）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/DistanceFunction/PairwiseDistance.ipynb)





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





