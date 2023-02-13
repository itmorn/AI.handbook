# 目录

## 卷积（Conv）
常规使用场景为下采样，即对张量局部特征进行汇总计算。    
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/conv.ipynb)

## 转置卷积（ConvTranspose）
常规使用场景为上采样，即对张量局部特征进行插值计算。    
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/convTranspose.ipynb)

## 拆分（Unfold）
从batched input tensor中提取滑动局部块，即对一个大的张量拆分成一叠小张量，并以列的方式进行输出。   
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/unford.ipynb)

## 折叠（Fold）
Unfold是负责拆分的，Fold与之相反，是负责折叠的，即对一叠小张量汇总为一个大张量。    
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/ford.ipynb)
