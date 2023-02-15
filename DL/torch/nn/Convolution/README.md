# 卷积（Convolution）
## 卷积（Conv）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/Conv.ipynb)  常规使用场景为下采样，即对张量局部特征进行汇总计算。    

## 转置卷积（ConvTranspose）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/ConvTranspose.ipynb)  常规使用场景为上采样，即对张量局部特征进行插值计算。    

## 拆分（Unfold）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/Unford.ipynb) 从batched input tensor中提取滑动局部块，即对一个大的张量拆分成一叠小张量，并以列的方式进行输出。   

## 折叠（Fold）
> [![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Convolution/Ford.ipynb) Unfold是负责拆分的，Fold与之相反，是负责折叠的，即将一叠小张量合并为一个大张量。用户可以自己指定合并方式，小张量重叠的位置会相加。   
