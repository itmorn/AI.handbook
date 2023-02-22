# 规范化（Normalization）
Norm对比:
<p align="center">
<img src="./imgs/4类Norm对比.png"
    width="2000" /></p>

## 批量归一化（BatchNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/BatchNorm.ipynb)  NCHW 在NHW维度上求均值和方差

## 层归一化（LayerNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/LayerNorm.ipynb)  NCHW 在CHW维度上求均值和方差

## 实例归一化（InstanceNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/InstanceNorm.ipynb)  NCHW 在HW维度上求均值和方差

## 组归一化（GroupNorm）
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Normalization/GroupNorm.ipynb)  层归一化和实例归一化的折中，即，将输入的通道分组，在组内执行层归一化，而实例归一化是在分组数=通道数时候的特例。

