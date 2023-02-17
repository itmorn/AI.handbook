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