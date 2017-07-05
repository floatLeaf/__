
# IOT
> Internet of Things

- [pix2code](https://github.com/tonybeltramelli/pix2code)
- [js iot - Evothings Studio](https://evothings.com/)


# Math

> 一个国家的教学水平，整体反应在教材的水平上；一个大学的教学水平，也反应在教材水平上。全国除顶尖985学校之外，其余学校的数学水平都很不理想，绝大多数学校的数学课程都是直接从苏联数学继承过来的。
> 
> 看完美国教材只有一个感受：真正好的教育是将复杂的东西简化，强化基础概念和实际应用，弱化具体计算和逻辑证明，最终让普通学生也可掌握相对深奥的理论知识，并迅速转入实际应用。国内的教育正好相反：强化具体计算和逻辑证明，却弱化了基础概念和实际应用，最终生产了许多解题高手，但他们完全不懂这些数学“有什么用？”。
> 
> [知乎](https://www.zhihu.com/question/24066773/answer/80124451)

《微积分》是学习《概率统计》和《线性代数》的必备条件。初学者，请一定按照“微积分---概率论---线性代数”的流程来学习，因为“求导/求积”的运算是后期概率运算的基础。

[三角函数](https://zh.wikipedia.org/wiki/%E4%B8%89%E8%A7%92%E5%87%BD%E6%95%B0)

# 机器学习

学习过程与推理过程是紧密相连的，学习中使用的推理方法称为学习策略。学习策略主要分为三大类型：搜索型策略（如状态空间法、A*算法、BP 算法）、构造型策略（如多层反馈神经网络的 FP 学习和综合算法）、规划型策略（如支持向量机）。依据这三大学习策略，又可细分为几种基本学习方法，分别是机械学习（记忆学习、只是最简单记录）、传授学习（指导式或指点学习）、演绎学习（演绎推理）、归纳学习（又分为实例学习、观察与发现学习）和类比学习。人类学习往往同时使用多种策略。

学习类型主要包括四种：监督学习（也称为监督训练或有教师学习，神经网络和决策树最常采用监督学习作为训练的技术）、无监督学习（类似于聚类）、半监督学习（利用标注样本和未标注样本进行训练和分类）、强化学习（使用学习激励函数，如棋类游戏通过强化学习一遍遍玩、最后会变得超越人类棋手）。

增强学习，比如小孩跑的时候摔倒、觉得疼，他下次会调整跑的姿势、注意不摔倒。

机器学习算法：人工神经网络、决策树、高斯过程、线性判别分析、K 近邻算法、支持向量机、最大期望（EM）算法、贝叶斯网络、马尔可夫随机域、流形机器学习、增强学习、多实例学习、ranking 学习、数据流学习、主成分分析（PCA）、独立成分分析（ICA）、聚类分析、覆盖算法、集成学习、马尔可夫链-蒙特卡罗方法。


# 资料

- [全世界最简单的机器学习入门指南](https://zhuanlan.zhihu.com/p/24339995)
- 计算机视觉：李飞飞 [TED: How we teach computers to understand pictures](https://www.youtube.com/watch?v=40riCqvRoMs) / [ImageNet](http://image-net.org/) / [斯坦福 vision lab](http://vision.stanford.edu/)

[机器学习-入门](http://www.cnblogs.com/subconscious/p/4107357.html?spm=0.0.0.0.U5h3qC)、
[AI-Programmer](https://github.com/primaryobjects/AI-Programmer)、
[Would-AI-be-able-to-write-code](https://www.quora.com/Would-AI-be-able-to-write-code)、
[Intelligent code-completion? Is there AI to write code by learning?](http://stackoverflow.com/questions/710843/intelligent-code-completion-is-there-ai-to-write-code-by-learning)

[brain](https://github.com/harthur/brain)、
[convnetjs](https://github.com/karpathy/convnetjs)、
[synaptic](https://github.com/cazala/synaptic)、
[Pure Javascript OCR](https://github.com/naptha/tesseract.js)

[如何让机器学习得更快——深度学习并行训练算法浅析](http://www.infoq.com/cn/presentations/how-to-make-the-machine-learn-faster)

https://github.com/superscriptjs/superscript


# 《数据挖掘导论》
> 范明 范宏建 译  
> 2016-11-02

数据类型：定量的「区间（日历日期、温度）、比率（质量、长度、计数）」或定性的「标称（邮编、雇员ID、性别）、序数（矿石硬度、街道号码）」。定性和定量之间的差别，是数据值之间是否有比值和联系。

数据集可以看做「数据对象」的集合，数据对象也叫记录、点、向量、模式、事件、案例、样本、观测或实体。数据对象用一组刻画对象基本特性（如物体质量或事件发生时间）的「属性」描述，属性也叫做变量、特性、字段、特征或维。

数据集的一般特性：维度、稀疏性、分辨率。

-------

数据质量：

数据挖掘要：对数据质量问题检测和纠正（数据清理），使用可以容忍低质量数据的算法。

测量和收集方面的数据质量问题：测量误差问题有噪声、伪像、偏倚、精度和准确率。数据质量问题：离群点、遗漏、不一致的值、重复数据、数据时效性和相关性。

完全消除噪声是困难的，所以关注「鲁棒算法」即在噪声干扰下也能产生可以接受的结果。

理想情况下，数据集附有描述数据的文档，文档的质量好坏决定它是支持还是干扰其后的分析。

-------

数据预处理：

技术：聚集、抽样、维规约、特征子集选择、特征创建、离散化和二元化、变量变换。

数据预处理的一个重要动机就是减少维度，称为「维规约」(降维)。随着数据维度增加，数据在它所占据的空间中越来越稀疏，这意味着没有足够的数据对象来创建模型。

维规约的一些最常见方法是使用线性代数技术，将数据由高维空间投影到低纬空间，例如主成分分析（PCA）、奇异值分解（SVD）技术。

-------

根据数据联系分析数据：

相似性和相异性的度量。两个对象之间的邻近度是两个对象对应属性之间的邻近度函数。这包括相关和欧几里得距离度量，以及 Jaccard 和余弦相似性度量。


```
{poor, fair, ok, good, wonderful} 产品质量
```

