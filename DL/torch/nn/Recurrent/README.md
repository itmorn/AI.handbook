# 循环神经网络（Recurrent）

RNN和RNNCell的区别
对于torch中的RNN相关类，有原始和原始Cell之分，其中RNN和RNNCell层的区别在于前者一次能够处理整个序列，而后者一次只处理序列中一个时间点的数据，前者封装更完备更易于使用，后者更具灵活性。 实际上RNN层的一种后端实现方式就是调用RNNCell来实现的。

1.循环神经网络(recurrent neural network)是时间上的展开,处理的是序列结构的信息,是有环图
2.递归神经网络(recursive neural network)是空间上的展开,处理的是树状结构的信息,是无环图

## 循环神经网络（RNN）

> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Recurrent/RNN.ipynb)  xxxxxxxx 

