# 视觉处理层（Vision）
## 像素混洗层(PixelShuffle)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Vision/PixelShuffle.ipynb)
PixelShuffle是PyTorch中的一种视觉层，它可以将一个高通道、低分辨率的输入张量转换成一个低通道、高分辨率的输出张量，从而可以用于超分辨率图像重建等任务。

## 像素拆分层(PixelUnshuffle)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Vision/PixelShuffle.ipynb)
是PixelShuffle的逆向操作。可以将一个低通道、高分辨率的输入张量转换成一个高通道、低分辨率的输出张量。PixelUnshuffle的作用类似于图像降采样，通常用于图像压缩等任务。

## 上采样层(Upsample)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Vision/Upsample.ipynb)
在PyTorch中，Upsample层支持多种插值方法，包括最近邻插值、双线性插值和三次插值等。可以使用不同的插值方法来平衡速度和精度的需求。

## 最近邻上采样层(UpsamplingNearest2d)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Vision/Upsample.ipynb)

## 插值上采样层(UpsamplingBilinear2d)
> [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/Vision/Upsample.ipynb)

