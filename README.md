# 更新
2023年1月1日 完成前言部分
<details open>
<summary><font color="blue">详情</font></summary>
2022年12月30日 新建仓库
</details>


# 前言
在该小节中，我将带领读者快速总览一下**人工智能、机器学习和深度学习的关系**，帮助读者建立对**人工智能知识架构**的整体把握，并引出本仓库的定位以及对知识的组织形式。
<details open>
<summary><font color="blue">详情</font></summary>
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
</details>

# 知识的组织方式
在该小结中，我们介绍本仓库对知识的组织方式。我们尽可能选择一条多数人走过的学习之路，同时会对这期间遇到的知识进行**系统地组织和提炼**，以帮助读者高效、清晰地学习。  

本仓库有两种组织方式，分别为技术主题和业务主题，如下：

<p align="center">
<a href ="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0.drawio#R7VjbcpswEP0aHpMBhO3k0df0oZl06mbyLGADqoVEhTB2vr4SiJsvcZ02zWSSTB7Ys9qVtGf3DNhC02RzI3Aa3%2FIQqOXa4cZCM8t1Hc91Lf1vh9sKuaqBSJCwguwWWJInMJE1mpMQMoNVkOScSpL2wYAzBoHsYVgIXvSXPXIa9oAUR7AHLANM99EHEsq4vsWoxb8AieJ6Z2d4XXl8HKwiwXNm9mOcQeVJcJ3G3DGLcciLDoTmFpoKzmX1lGymQHVZ%2BxVbHPE2RxbA5J8E2NcX%2FvTO5w%2FJfbx8uthcDZOvF%2BaCa0xzU4pl7ivgB09JYM4tt3WZiphIWKY40HahWsFCk1gmVFmOeizrAHo7W1lYBIboQWlSEjFlBOq4IBSwBiGJomBsHAkJQ73RJJOCrxoedGKcS55VubSZqRMQFinLU5YUAAtFeIU4Brnl6xZgUMxDRXh9k9HEcoe%2Fcl35CTSOBrLQuONnksjtd6BYEs7mB1a709bIJBZyrDvySLqqQQ7GAgtfGJlBlOgu6Abq0eosCXKxVtT0Vlijmd52k%2BKyfZ0y7W5TmT7TbMGmA5kmuwGegBRbtcR4PdvM%2Fra2UWUXncnyKijuDJU7NPNsZjlqMrdNrR5MX5%2FR41d7Pb7X2NDpjmOE98hFs5KODmkNUpOhCmq3hT9RXpU5Anl6UPVBnyVBlOde93XtUElN6DdOdOPU5CG0Q97A66fIeC4CMFE7xDTHOMTVfQbizv%2Bp1du1KfaBHtEbStiqcsVSav0f613cRVEUlz4mYX4Z8KSE3FPMO17npqZVXiJnzpvJmf0pZ2fK2SNnsq6MZ%2Bwpp1yUnCNb%2FS0WZymdfu2gFKcZhM%2BOnokZILs3Qmho7%2BnfyP4n%2BqfMzlidIYnO4B1oYiU1pzXxpHY63v8RT2%2Fg9MVzN8W7Es%2FOS%2BqneH4Q8VTfdSCxT5vqrkAGsSnl6ymme92fm1qeuorpvq1iNnf9EIpZf7O%2BvmLuvG7W39V%2FrZjKbD%2Btq%2BXtTxdo%2Fhs%3D">
<img src="imgs/Technical_topics.drawio.svg"
    title="点击进入思维导图"
    width="80%" />
</a></p>

<hr>

<p align="center">
<a href ="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0.drawio#R7VjbcpswEP0aHpMBhO3k0df0oZl06mbyLGADqoVEhTB2vr4SiJsvcZ02zWSSTB7Ys9qVtGf3DNhC02RzI3Aa3%2FIQqOXa4cZCM8t1Hc91Lf1vh9sKuaqBSJCwguwWWJInMJE1mpMQMoNVkOScSpL2wYAzBoHsYVgIXvSXPXIa9oAUR7AHLANM99EHEsq4vsWoxb8AieJ6Z2d4XXl8HKwiwXNm9mOcQeVJcJ3G3DGLcciLDoTmFpoKzmX1lGymQHVZ%2BxVbHPE2RxbA5J8E2NcX%2FvTO5w%2FJfbx8uthcDZOvF%2BaCa0xzU4pl7ivgB09JYM4tt3WZiphIWKY40HahWsFCk1gmVFmOeizrAHo7W1lYBIboQWlSEjFlBOq4IBSwBiGJomBsHAkJQ73RJJOCrxoedGKcS55VubSZqRMQFinLU5YUAAtFeIU4Brnl6xZgUMxDRXh9k9HEcoe%2Fcl35CTSOBrLQuONnksjtd6BYEs7mB1a709bIJBZyrDvySLqqQQ7GAgtfGJlBlOgu6Abq0eosCXKxVtT0Vlijmd52k%2BKyfZ0y7W5TmT7TbMGmA5kmuwGegBRbtcR4PdvM%2Fra2UWUXncnyKijuDJU7NPNsZjlqMrdNrR5MX5%2FR41d7Pb7X2NDpjmOE98hFs5KODmkNUpOhCmq3hT9RXpU5Anl6UPVBnyVBlOde93XtUElN6DdOdOPU5CG0Q97A66fIeC4CMFE7xDTHOMTVfQbizv%2Bp1du1KfaBHtEbStiqcsVSav0f613cRVEUlz4mYX4Z8KSE3FPMO17npqZVXiJnzpvJmf0pZ2fK2SNnsq6MZ%2Bwpp1yUnCNb%2FS0WZymdfu2gFKcZhM%2BOnokZILs3Qmho7%2BnfyP4n%2BqfMzlidIYnO4B1oYiU1pzXxpHY63v8RT2%2Fg9MVzN8W7Es%2FOS%2BqneH4Q8VTfdSCxT5vqrkAGsSnl6ymme92fm1qeuorpvq1iNnf9EIpZf7O%2BvmLuvG7W39V%2FrZjKbD%2Btq%2BXtTxdo%2Fhs%3D">
<img src="imgs/Business_topics.drawio.svg"
    title="点击进入思维导图"
    width="80%" /></a></p>


采用这种组织方式的理由是——**对面试和工作都实用**。解释如下：  
> 一般来说，公司在设置招聘岗位时有两种方式：
> 1. 按**技术**描述岗位。比如：算法工程师、人工智能工程师、机器学习工程师、深度学习工程师、强化学习工程师、运筹优化工程师等。
> 2. 按**业务**描述岗位。比如：图像算法工程师、自然语言处理工程师、语音处理工程师、广告算法工程师、推荐算法工程师、风控算法工程师、数据挖掘工程师等。 
>  
> 虽然有以上两种方式，但是我们要清楚**技术是为业务服务的，某一项技术可能服务于多种业务**，比如说**强化学习**这门技术，可以单独拎出来讲一个技术专题，也可以结合具体业务（比如推荐和风控）讲一下具体的应用。所以，我最终决定将知识的组织方式分为两条线:
> 1. **技术线**：这条线上我们更加专注于系统性地讲解某一项技术，比如强化学习，我们就会讲解里面的一些基础的算法，优化方法、应用场景等。简言之，就是**重某一项技术系统的理论体系，轻具体的业务实践**。  
> 2. **业务线**：这条线上我们更加专注于如何提升业务指标(比如推荐算法中的点击率)，那么就会涉及到很多种技术(比如强化学习)如何合理地在该业务上进行实践的问题。简言之，就是**重具体的业务实践，轻某一项技术系统的理论体系**。   


# 如何使用本仓库
本仓库是一个AI学习手册，知识点繁多，覆盖领域广泛。因此，我们**针对不同的读者，给出一些使用建议**。
<details open>
<summary><font color="blue">详情</font></summary>

如果你是**AI初学者**。
> 可以优先学习技术主题中**机器学习**和**深度学习**的内容，来了解一些基本方法论，并学习一些经典的机器学习算法。然后根据自己的兴趣爱好选择一个主攻的业务领域，比如计算机视觉进行专项的学习。

如果你是**AI工程师**。
> 可以通过该仓库丰富自己的知识结构，也可以直接引用其中的代码提升开发效率。


</details>

# 参考资料
国内比较流行的AI资料有周志华老师的[《机器学习》](https://item.jd.com/12762673.html)、李航老师的[《统计学习方法》](https://item.jd.com/12522197.html)、Andrew Ng的[Coursera课程](https://www.coursera.org/instructor/andrewng)，还有一些知名的开源库，比如：[sklearn](https://scikit-learn.org/)、[pytorch](https://pytorch.org/)等。
温州大学黄海广老师的[《机器学习》](https://www.icourse163.org/course/WZU-1464096179)，该老师的[GitHub](https://github.com/fengdu78/WZU-machine-learning-course)中也囊括了很多优秀的代码示例。

接下来，我们就按照前文所说的知识组织方式一起走进AI的知识海洋吧！

# 技术主题
## 机器学习
### 机器学习基础

|            | 年份 | 介绍                 | colab | bilibili | youtube | 论文 |
| ---------- | ---- | -------------------- | ----- | -------- | ------- | ---- |
| 数据归一化 | 1980 | 对输入数据的处理方法 |       |          |         |      |
| EM算法     | 1980 |                      |       |          |         |      |
</br>

### 机器学习算法

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |
</br>

# 计算机视觉

## 计算机视觉基础

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |
</br>

## 图像分类

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |
</br>

## 目标检测

| 模型                                                                 | 年份 | 适用问题     | 模型类型 | colab                                                                                                                                                                                      | bilibili | youtube | 论文                                                               |
| -------------------------------------------------------------------- | ---- | ------------ | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | ------- | ------------------------------------------------------------------ |
| [感知机(perceptron)](./machine_learning/perceptron/models/README.md) | 1980 | 二分类       | 判别模型 | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itmorn/AI.handbook/blob/main/machine_learning/perceptron/models/perceptron.ipynb) |          |         | [paper](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0042519) |
| k近邻                                                                | 1993 | 多分类、回归 | 判别模型 |                                                                                                                                                                                            |          |         |                                                                    |
</br>
