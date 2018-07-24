# BUAA Data Mining Group

BDMG小组的资源分享平台，包含工程代码、学习资料、数据集等。  
*注意：请不要将带有版权的资料直接上传，给出相应链接即可。*

## TODO
* 将组员加入到git项目中。
* 更新数据预处理的学习资源。

## Week 1
上周末的展示十分精彩，这周将陆续上传展示的PPT。
本周的研究方向将产生较大的分支：跟着网课学习的同学将可以着手尝试ANN神经网络的工程实践；准备深入机器学习算法的同学可以选择某一机器学习模型进行深入探究。  
**推荐继续对自己感兴趣的问题进行深入探究**　基础理论十分重要。  
这里给出展示中遇到的具体问题：
1. 朴素贝叶斯算法中使用的“先验概率”指的是什么？
2. 为什么决策树的变量处理顺序不同将影响最后结果？如何影响？
3. K邻近方法计算量大，为了减小计算量设计了几种索引结构降低算法复杂度（如：KDTree, BallTree），这样的优化将对结果造成什么样的影响？为什么会造成这样的影响？
4. Q-learning的状态划分有什么限制？
5. 数据预处理有哪些方法？需要考虑数据源的种类，如：离散有限无序关系集合，离散有限有序关系集合，连续有限集合。需要考虑种类不同的数据源之间的协调统一方法，如：为何归一化方法可以为$(data-min)/(max-min)$ 或 $(data-mean)/(max-min)$ 。
   
建议在解决上述问题（特别是有关数据预处理的问题）后继续往前探索！

## Week 0 
暑假期间的活动主要以理论学习与实践为主，第一周的主要任务是选择自己感兴趣的数据处理基础模型进行自主学习，并尝试动手实现运用该模型对数据进行分析。
### 环境配置
实践过程主要使用python语言。为了降低环境配置难度，建议选择anaconda(or miniconda)，并将anaconda的下载源换成国内的服务器后进行环境配置的工作。  
  
|描述|链接|    
|---|---|  
| anaconda | [https://anaconda.org](https://anaconda.org) |  
| anaconda 更换源　| [https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/](https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/) |  
|anaconda 安装scikit-learn| [https://anaconda.org/anaconda/scikit-learn](https://anaconda.org/anaconda/scikit-learn) |  


### 基础模型选择
在搭建好学习环境后可以选择自己喜欢的基础模型进行深入探索。在阅读一定综述（两到三篇），理解模型的基本工作原理和适用范围之后，复现在scikit-learn中给出的[sample](http://scikit-learn.org/stable/auto_examples/index.html)。完成上述工作后，**准备一个8分钟左右的小展示**，简要介绍所学模型的基本特点，并且演示自己复现的[sample](http://scikit-learn.org/stable/auto_examples/index.html)。
这里给出几类经典模型。


#### Support Vector Machines (SVM)
理论完备的经典分类模型。

|描述|链接|
|---|---|  
|simple guide|https://www.csie.ntu.edu.tw/~cjlin/papers/guide/guide.pdf |


[scikit-learn SVM](http://scikit-learn.org/stable/modules/svm.html)


#### Generalized Linear Models
经典广义线性模型。  

|描述|链接|
|---|---|  
|classic paper|http://www.ixueshu.com/document/1563073819c1cc4c318947a18e7f9386.html|

[scikit-learn GLM](http://scikit-learn.org/stable/modules/linear_model.html)

#### Nearest Neighbors
邻聚模型。

|描述|链接|
|---|---|  
|Nearest neighbor pattern classification| http://www-isl.stanford.edu/people/cover/papers/transIT/0021cove.pdf|

[scikit-learn NN](http://scikit-learn.org/stable/modules/neighbors.html)


