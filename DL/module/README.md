# 卷积（Convolution）
## 卷积（Conv）
常规使用场景为下采样，即对张量局部特征进行汇总计算。    
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/Conv.ipynb)

## 转置卷积（ConvTranspose）
常规使用场景为上采样，即对张量局部特征进行插值计算。     
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/ConvTranspose.ipynb)

## 拆分（Unfold）
从batched input tensor中提取滑动局部块，即对一个大的张量拆分成一叠小张量，并以列的方式进行输出。   
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/Unford.ipynb)

## 折叠（Fold）
Unfold是负责拆分的，Fold与之相反，是负责折叠的，即将一叠小张量合并为一个大张量。用户可以自己指定合并方式，小张量重叠的位置会相加。    
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Convolution/Ford.ipynb)




# 池化（Pooling）
## 最大值池化（MaxPool）
使用最大值进行池化  
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Pooling/MaxPool.ipynb)

## 最大值反向池化（MaxUnpool）
将最大值池化的结果逆向  
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Pooling/MaxUnpool.ipynb)

## 平均值池化（AvgPool）
使用平均值进行池化  
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Pooling/AvgPool.ipynb)

## 分数最大值池化（FractionalMaxPool）
用户可以指定一个分数，该算子在执行最大值池化的同时，使得输出的尺寸 = 输入尺寸 * 分数  
[![](/imgs/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/module/Pooling/FractionalMaxPool.ipynb)