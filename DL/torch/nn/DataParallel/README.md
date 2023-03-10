# 数据并行（DataParallel）
## 分布式数据并行(DistributedDataParallel)
[![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/DL/torch/nn/DataParallel/DistributedDataParallel.ipynb)
torch.nn.parallel.DistributedDataParallel是PyTorch中的一个模块，用于支持分布式训练。它通过在多个GPU或计算机上并行处理模型的不同部分来加速训练过程。

当使用DistributedDataParallel时，模型被复制到每个GPU或计算机上。在每个计算设备上，模型使用相同的初始参数进行训练。在每个步骤之后，梯度被收集并在所有设备之间同步。然后，模型的参数被更新，并且训练进入下一步骤。这种并行训练的过程被称为数据并行。

DistributedDataParallel还可以与分布式后端一起使用，例如TorchDistributed或NCCL，以进一步加速分布式训练。分布式后端可以提供优化的通信方案，从而更快地收集和同步梯度。

总之，torch.nn.parallel.DistributedDataParallel是一种强大的工具，可用于在多个GPU或计算机上高效地训练大型神经网络。


