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
