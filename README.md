# 更新日志
2023年1月1日 完成前言部分
<details close>
2022年12月30日 新建仓库
</details></br>


# 前言
在该小节中，我将带领读者快速总览一下**人工智能、机器学习和深度学习的关系**，帮助读者建立对**人工智能知识架构**的整体把握。
<details close>
<p align="center">
    <img src="./imgs/difference_between_ai__machine_learning_and_deep_learning2.png"
         title="https://blogs.nvidia.com/blog/2016/07/29/whats-difference-artificial-intelligence-machine-learning-deep-learning-ai/"
         width="70%" />
</p>

<p align="center">
    <img src="./imgs/difference_between_ai__machine_learning_and_deep_learning.png"
         title="https://www.designnews.com/electronics-test/4-reasons-use-artificial-intelligence-your-next-embedded-design"
         width="70%" />
</p>
</br>   

**人工智能**：所有让计算机去模仿人类行为的技术，让机器具备人类的智慧。(Human Intelligence Exhibited by Machines)  
>回到1956年夏天的会议上，那些人工智能先驱的梦想是建造复杂的机器，由新兴的计算机实现，拥有与人类智能相同的特征。这就是我们所认为的“通用人工智能”(General AI)的概念——拥有我们所有感官(甚至更多)、所有理性，并像我们一样思考的神奇机器。  
你已经在电影中无数次看到这些机器，比如终结者。通用人工智能机器一直出现在电影和科幻小说中是有原因的，因为我们做不到，至少现在不行。   
我们所能做的就是“狭义人工智能”(Narrow AI)。这些技术能够像人类一样完成特定的任务，甚至比人类做得更好，比如下围棋(AlphaGo)。  
PS：[北京通用人工智能研究院](https://baike.baidu.com/item/%E5%8C%97%E4%BA%AC%E9%80%9A%E7%94%A8%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%A0%94%E7%A9%B6%E9%99%A2/55726794?fr=aladdin)(2020年成立)在研究具有自主的感知、认知、决策、学习、执行和社会协作能力，符合人类情感、伦理与道德观念的通用智能体。

</br>      

**机器学习**：机器学习是实现人工智能的一种方法。(An Approach to Achieve Artificial Intelligence)  
>它不需要人类显示地(explicitly)编程去告诉计算机如何去做，而是使用大量的数据和算法进行训练，使其能够学习如何执行任务。

</br>   

**深度学习**：深度学习是实现机器学习的一门技术。(A Technique for Implementing Machine Learning)  
> 从最早简单的[感知机](https://en.wikipedia.org/wiki/Perceptron)(perceptron,1958)，到[多层感知机](https://en.wikipedia.org/wiki/Multilayer_perceptron)(Multilayer Perceptron,1961)，再到[LeNet](https://en.wikipedia.org/wiki/LeNet)(1998)，最后到[AlexNet](https://en.wikipedia.org/wiki/AlexNet)(2012)，研究者发现，随着网络层数的增加，模型的效果可以得到十分显著的提升（AlexNet在ImageNet竞赛中将错误率降到了15.3%，远低于第二名的26.2%）。  
从此，这种网络层数非常深的模型得到了越来越多研究者的青睐，时至今日(2022.12)AlexNet的引用量已经达到了12w。  
之所以叫**深度**(deep)，主要由于研究者在设计网络模型的过程中，使用了很多的神经网络层(Neural network layer)以取得更佳的效果，我们把这种使用了很多网络层堆叠来构建、训练网络的机器学习技术称为**深度学习**。  

</br>
下面再展示一张比较流行的韦恩图，也许能进一步帮助你建立更清晰的知识层级：
<p align="center">
    <img src="./imgs/Relationship_between_artificial_intelligence_machine_learning_neural_network_and_deep_learning.jpg"
         title="https://twitter.com/DataScienceDojo/status/1557140164861902856"
         width="70%"/>
</p>
机器学习是一个范围宽阔、内容繁多、应用广泛的领域，并不存在(至少现在不存在)一个统一的理论体系涵盖所有内容[李航]。比如在上图中:

> Artificial intelligence下的Natural language processing(**自然语言处理**,NLP)就是一个抽象程度很高的任务，其子任务可以包括**自然语言理解**(Natural Language Understanding)和**自然语言推理**(Natural Language Inference)等。  
> Machine learning中的Linear regression又是一个具体的算法。  
> Deep learning中的CNN又是一类技术的统称。  

这个问题对很多AI学习、从业者造成了困扰，但我们必须面对这个现实。

那么本仓库中，该如何对这个纷繁的大知识树进行组织梳理呢？不同的人群又该如何使用本仓库呢？
</details></br>

# 知识的组织方式
在该小结中，我们介绍本仓库对知识的组织方式。我们尽可能选择一条多数人走过的学习之路，同时会对这期间遇到的知识进行**系统地组织和提炼**，以帮助读者高效、清晰地学习。

<details close>
由于AI领域不存在统一的理论体系，当我们听到别人说到某个专业名词时，能知道其表达的含义就足够了。

其实参考大部分AI从业者的学习路径就是一个不错的选择。俗话说，世界上本没有路，走的人多了也便成了路。这样，无论是在面试中、还是和同学同事交流中都不会引起太大的歧义。

国内比较流行的AI资料有[《机器学习》(周志华著)](https://item.jd.com/12762673.html)、[《统计学习方法》(李航著)](https://item.jd.com/12522197.html)、[Andrew Ng的Coursera课程](https://www.coursera.org/instructor/andrewng)，还有一些知名的开源库，比如：[sklearn](https://scikit-learn.org/)、[pytorch](https://pytorch.org/)等。

这些资料不仅是算法面试的重点，也是循序渐进走进AI世界的阶梯。本仓库会的基础部分会用大量篇幅覆盖这些内容。因此，我们建立的知识体系也旨在能够帮助学习者梳理清这些知识即可。  


本仓库包括以下几个大的模块：
**机器学习**、**计算机视觉**、**自然语言处理**等，下面我们具体展开来谈：

**机器学习(Machine Learning)**
> 在面试的过程中，面试官提到**机器学习**或者**传统机器学习**往往指的是形如逻辑回归、决策树和支持向量机等具体的算法(也可称为模型)。因此，在这一部分中，我们就主要讲解这些面试常见的算法。该部分还会细分为两个部分：
> - **机器学习基础**
>   > 主要讲解一些机器学习的基础概念、方法论和技巧等。
> - **机器学习算法**
>   > 主要讲解具体的算法，比如LR、KNN和决策树等  
>
> PS：面试过程中，无论你是从事AI的哪个领域，比如数据挖掘、计算机视觉和自然语言处理等，这些基础内容都属于高频考题。


**计算机视觉(Computer Vision)**
> 计算机视觉是一个抽象层级较高的任务(task)，其对标的岗位是**CV类工程师**。从业务/任务角度又包括很多子任务，比如图像分类、目标检测等。该部分，我们会细分为1+N个部分。其中，“1”表示的是计算机视觉基础；N表示计算机视觉的多个子任务所涉及到的算法。具体为：
> - **计算机视觉基础**  
>   > 主要讲解一些计算机视觉的基础概念、方法论和技巧等。
> - **图像分类(Image Classification)**
>   > 主要讲解一些图像分类算法，比如LeNet、AlexNet和ResNet等。
> - **目标检测(Object Detection)**
>   > 主要讲解一些目标检测算法，比如YOLO、SSD和RCNN等。

</details></br>

# 如何使用本仓库
本仓库是一个AI学习手册，知识点繁多，覆盖领域广泛。因此，我们**针对不同的读者，给出一些使用建议**。
<details close>

如果你是**AI初学者**。
> 可以优先学习**机器学习**部分的内容来了解一些基本方法论，并学习一些经典的机器学习算法。然后根据自己的兴趣爱好选择一个主攻的领域，比如计算机视觉或自然语言处理进行专项的学习。

如果你是**AI工程师**。
> 可以通过该仓库丰富自己的知识结构，也可以直接引用其中的代码提升开发效率。

接下来，我们就按照前文所说的知识组织方式一起走进AI的知识海洋吧！
</details></br>

# 机器学习

## 机器学习基础
<details close>

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |


|            | 年份 | 介绍                 | colab | bilibili | youtube | 论文 |
| ---------- | ---- | -------------------- | ----- | -------- | ------- | ---- |
| 数据归一化 | 1980 | 对输入数据的处理方法 |       |          |         |      |
| EM算法     | 1980 |                      |       |          |         |      |

</details></br>

## 机器学习算法
<details close>

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |


|            | 年份 | 介绍                 | colab | bilibili | youtube | 论文 |
| ---------- | ---- | -------------------- | ----- | -------- | ------- | ---- |
| 数据归一化 | 1980 | 对输入数据的处理方法 |       |          |         |      |
| EM算法     | 1980 |                      |       |          |         |      |

</details></br>

# 计算机视觉

## 计算机视觉基础
<details close>

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |


|            | 年份 | 介绍                 | colab | bilibili | youtube | 论文 |
| ---------- | ---- | -------------------- | ----- | -------- | ------- | ---- |
| 数据归一化 | 1980 | 对输入数据的处理方法 |       |          |         |      |
| EM算法     | 1980 |                      |       |          |         |      |

</details></br>

## 图像分类
<details close>

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |


|            | 年份 | 介绍                 | colab | bilibili | youtube | 论文 |
| ---------- | ---- | -------------------- | ----- | -------- | ------- | ---- |
| 数据归一化 | 1980 | 对输入数据的处理方法 |       |          |         |      |
| EM算法     | 1980 |                      |       |          |         |      |

</details></br>

## 目标检测
<details close>

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |


|            | 年份 | 介绍                 | colab | bilibili | youtube | 论文 |
| ---------- | ---- | -------------------- | ----- | -------- | ------- | ---- |
| 数据归一化 | 1980 | 对输入数据的处理方法 |       |          |         |      |
| EM算法     | 1980 |                      |       |          |         |      |

</details></br>
