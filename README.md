# 总览人工智能、机器学习和深度学习
<div>
    <center>
    <img src="./imgs/difference_between_ai__machine_learning_and_deep_learning2.png"
         title="https://blogs.nvidia.com/blog/2016/07/29/whats-difference-artificial-intelligence-machine-learning-deep-learning-ai/"
         style="zoom:1"/>
    </center>
</div>
<div>
    <center>
    <img src="./imgs/difference_between_ai__machine_learning_and_deep_learning.png"
         title="https://www.designnews.com/electronics-test/4-reasons-use-artificial-intelligence-your-next-embedded-design"
         style="zoom:1"/>
    </center>
</div>

* **人工智能**：所有让计算机去模仿人类行为的技术，让机器具备人类的智慧。(Human Intelligence Exhibited by Machines)
>回到1956年夏天的会议上，那些人工智能先驱的梦想是建造复杂的机器，由新兴的计算机实现，拥有与人类智能相同的特征。这就是我们所认为的“通用人工智能”(General AI)的概念——拥有我们所有感官(甚至更多)、所有理性，并像我们一样思考的神奇机器。  
你已经在电影中无数次看到这些机器，比如终结者。通用人工智能机器一直出现在电影和科幻小说中是有原因的，因为我们做不到，至少现在不行。   
我们所能做的就是“狭义人工智能”(Narrow AI)。这些技术能够像人类一样完成特定的任务，甚至比人类做得更好，比如下围棋(AlphaGo)。  
PS：[北京通用人工智能研究院](https://baike.baidu.com/item/%E5%8C%97%E4%BA%AC%E9%80%9A%E7%94%A8%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%A0%94%E7%A9%B6%E9%99%A2/55726794?fr=aladdin)(2020年成立)在研究具有自主的感知、认知、决策、学习、执行和社会协作能力，符合人类情感、伦理与道德观念的通用智能体。


* **机器学习**：机器学习是实现人工智能的一种方法。(An Approach to Achieve Artificial Intelligence)
>它不需要人类显示地(explicitly)编程去告诉计算机如何去做，而是使用大量的数据和算法进行训练，使其能够学习如何执行任务。


* **深度学习**：深度学习是实现机器学习的一门技术。(A Technique for Implementing Machine Learning)
> 从最早简单的[感知机](https://en.wikipedia.org/wiki/Perceptron)(perceptron,1958)，到[多层感知机](https://en.wikipedia.org/wiki/Multilayer_perceptron)(Multilayer Perceptron,1961)，再到[LeNet](https://en.wikipedia.org/wiki/LeNet)(1998)，最后到[AlexNet](https://en.wikipedia.org/wiki/AlexNet)(2012)，研究者发现，随着网络层数的增加，模型的效果可以得到十分显著的提升（AlexNet在ImageNet竞赛中将错误率降到了15.3%，远低于第二名的26.2%）。  
从此，这种网络层数非常深的模型得到了越来越多研究者的青睐，时至今日(2022.12)AlexNet的引用量已经达到了12w。  
之所以叫**深度**(deep)，主要由于研究者在设计网络模型的过程中，使用了很多的神经网络层(Neural network layer)以取得更佳的效果，我们把这种使用了很多网络层堆叠来构建、训练网络的机器学习技术称为**深度学习**。  

</br>
下面再展示一张比较流行的韦恩图，也许能进一步帮助你建立更清晰的知识层级：
<div>
    <center>
    <img src="./imgs/Relationship_between_artificial_intelligence_machine_learning_neural_network_and_deep_learning.jpg"
         title="https://twitter.com/DataScienceDojo/status/1557140164861902856"
         style="zoom:1"/>
    </center>
</div>

# 本仓库的定位







## 机器学习(machine learning)

## 模型总览

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |

## 其他

|            | 年份 | 介绍                 | colab | bilibili | youtube | 论文 |
| ---------- | ---- | -------------------- | ----- | -------- | ------- | ---- |
| 数据归一化 | 1980 | 对输入数据的处理方法 |       |          |         |      |
| EM算法     | 1980 |                      |       |          |         |      |

# 计算机视觉(computer vision)

## 图像分类(image classification)

### 模型总览

### 其他

### 数据集

## 目标检测(object detection)

### 模型总览

### 其他

### 数据集

# 更新日志