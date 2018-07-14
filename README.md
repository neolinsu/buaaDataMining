# BUAA Data Mining Group

这里是BDMG小组的资源分享平台，包含工程代码、学习资料、数据集等。  
*注意：请不要将带有版权的资料直接上传，给出相应链接即可。*

## TODO
* 将组员加入到git项目中。
* 确定每周集中讨论时间。
* 组员选择第一周的学习方向。

## Week 0 
暑假期间的活动主要以理论学习与实践为主，第一周的主要任务是选择自己感兴趣的数据处理基础模型进行自主学习，并尝试动手实现运用该模型对数据进行分析。
### 环境配置
实践所用的语言以python为主。为了降低环境配置难度，建议选择anaconda(or miniconda)，并将anaconda的下载源换成国内的服务器后进行环境配置的工作。  
|Description|Link|
|---|---|  
| anaconda| [https://anaconda.org](https://anaconda.org)
| anaconda 更换源　|[https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/](https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/)
|anaconda 安装scikit-learn| [https://anaconda.org/anaconda/scikit-learn](https://anaconda.org/anaconda/scikit-learn)

### 基础模型选择
在搭建好学习环境后可以选择自己喜欢的基础模型进行深入探索，在阅读一定综述（两到三篇）后，理解模型的基本工作原理和适用范围后，复现在scikit-learn中给出的sample。完成上述工作后，准备一个8分钟左右的小展示，简要介绍所学模型的基本特点，并且演示自己复现的sample。
这里给出几类经典模型。
#### Support Vector Machines (SVM)
理论完备的经典分类模型。
|Description|Link|
|---|---|  
|simple guide|https://www.csie.ntu.edu.tw/~cjlin/papers/guide/guide.pdf|
||http://www.stanford.edu/~montanar/TEACHING/Stat319/papers/cover_nn.pdf|


[scikit-learn SVM](http://scikit-learn.org/stable/modules/svm.html)


#### Generalized Linear Models
经典线性模型。
|Description|Link|
|---|---|  
|classic paper|http://www.ixueshu.com/document/1563073819c1cc4c318947a18e7f9386.html|

[scikit-learn GLM](http://scikit-learn.org/stable/modules/linear_model.html)

#### Nearest Neighbors
邻聚模型。

|Description|Link|
|---|---|  
|Nearest neighbor pattern classification| http://www-isl.stanford.edu/people/cover/papers/transIT/0021cove.pdf|

[scikit-learn NN](http://scikit-learn.org/stable/modules/neighbors.html)


