:point_right: 此repo主要是为了整理机器学习面试相关知识点的有用链接
（注：目前不打算将一些基础算法的内容加入这个repo里，比如LR、SVM算法在《统计学习方法》里已经得到了很好的解释，面试时可能考到的手推公式在书里已经写的很好了，所以推荐直接看书即可。）

### 一、特征工程

#### （一）特征预处理
- [标准化、归一化、异常特征清洗、不平衡数据](https://www.cnblogs.com/pinard/p/9093890.html)
- [不平衡数据的处理方法](https://blog.csdn.net/zhang15953709913/article/details/84635540)

#### （二）特征表达
- [缺失值、特殊特征(eg.时间)、离散特征、连续特征](https://www.cnblogs.com/pinard/p/9061549.html)
- [连续特征离散化的好处](http://note.youdao.com/noteshare?id=024fa3dbabf4b5a07eb72c8021e60f62)
- [什么样的模型对缺失值更敏感？](https://blog.csdn.net/zhang15953709913/article/details/88717220)

#### （三）特征选择
- [过滤法、包装法、嵌入法](https://www.cnblogs.com/pinard/p/9032759.html) 
- [Kaggle中的代码实战](https://www.kaggle.com/willkoehrsen/introduction-to-feature-selection)

### 二、算法相关
#### （一）评价指标
- [PR曲线和F1 & ROC曲线和AUC](http://note.youdao.com/noteshare?id=13d31b4a7dc317b3d4abd18bf42a74df)

#### （二）正则项
- [正则化与数据先验分布的关系](http://note.youdao.com/noteshare?id=2851b97199bcdc174001d72b1bec0372)
- [L1在0点处不可导怎么办？](http://www.cnblogs.com/pinard/p/6018889.html)可采用坐标轴下降、最小角回归法

#### （三）损失函数
- [常见回归和分类损失函数比较
](http://note.youdao.com/noteshare?id=070ef1d6687a15dc2747cb094e005ea4)

#### （四）模型训练
- [经验误差与泛化误差、偏差与方差、欠拟合与过拟合、交叉验证](http://note.youdao.com/noteshare?id=b629383adb3b09eb31b754c337f690b5)

#### （五）机器学习算法
1. 线性回归、逻辑回归、SVM
  - [LR优缺点](https://github.com/wangyuGithub01/Machine_Learning_Notes/blob/master/pdf/lr_pros_and_cons.md)
  - [SVM、logistic regression、linear regression对比](https://github.com/wangyuGithub01/Machine_Learning_Notes/blob/master/pdf/compare_svm_lr.md)
  - [LR和最大熵模型的关系](https://blog.csdn.net/dp_BUPT/article/details/50568392)
  - [为什么LR要用对数似然，而不是平方损失？](https://blog.csdn.net/zhang15953709913/article/details/88717326)
2. 树模型
- [逻辑回归与决策树在分类上的区别](https://blog.csdn.net/zhang15953709913/article/details/84841988)
- [回归树、提升树、GBDT](https://www.jianshu.com/p/005a4e6ac775)
- [GBDT、XGBOOST、LightGBM讲解(强烈推荐看一下)](https://github.com/wangyuGithub01/Machine_Learning_Notes/blob/master/pdf/gbdt_wepon.pdf)
- [随机森林 GBDT  XGBOOST  LightGBM 比较](http://note.youdao.com/noteshare?id=65790e27fd5737155c31af2c05df8985)

3. 其他
- [各种机器学习算法的应用场景](https://www.zhihu.com/question/26726794)

#### （六）NLP相关
- [word2vec]()
- [fasttext](https://zhuanlan.zhihu.com/p/32965521)
- [Transformer](https://zhuanlan.zhihu.com/p/54356280)
- [Bert](https://fancyerii.github.io/2019/03/05/bert-prerequisites/) 零基础入门，prerequisites很全
- [Bert / Elmo](http://www.sohu.com/a/281795578_473283)
- [XLNet](https://zhuanlan.zhihu.com/p/70257427)
- [nlp中的词向量对比：word2vec/glove/fastText/elmo/GPT/bert](https://zhuanlan.zhihu.com/p/56382372)
- [NLP/AI面试全记录](https://zhuanlan.zhihu.com/p/57153934)

#### （七）CTR预估 & 推荐系统 相关
- [FM算法](https://zhuanlan.zhihu.com/p/37963267):讲的蛮细的
- [FM算法结合推荐系统的讲解](https://zhuanlan.zhihu.com/p/58160982)

#### （八）其他
- [判别模型 vs 生成模型](https://www.zhihu.com/question/20446337)
- [参数模型 vs 非参数模型](https://zhuanlan.zhihu.com/p/26012348)
- [参数估计 最大似然估计与贝叶斯估计](https://blog.csdn.net/bitcarmanlee/article/details/52201858)
- [梯度下降法、牛顿法和拟牛顿法](https://zhuanlan.zhihu.com/p/37524275)
- [最小二乘法 和 最大似然估计的对比联系](https://blog.csdn.net/zhang15953709913/article/details/88716699)
- [最大似然估计 和 EM](https://blog.csdn.net/zouxy09/article/details/8537620)
- [浅谈最优化问题的KKT条件](https://zhuanlan.zhihu.com/p/26514613)
- [交叉熵](https://colah.github.io/posts/2015-09-Visual-Information/)
- [KL散度](https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained)

### 三、其他
- [向量间距离度量方式](http://note.youdao.com/noteshare?id=ffba716f9f94f1cf3fac48fca300c198)

### 四、推荐书籍/笔记/代码实现
- [统计学习方法](https://github.com/wangyuGithub01/E-book/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95(%E6%9D%8E%E8%88%AA).pdf) (注意这个pdf是第一版，其中的勘误可在[这里](https://github.com/wangyuGithub01/E-book/blob/master/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95%EF%BC%88%E5%8B%98%E8%AF%AF%EF%BC%89.pdf)查看)（[代码实现及ppt](https://github.com/fengdu78/lihang-code)）
- [西瓜书的公式推导细节解析](https://datawhalechina.github.io/pumpkin-book/#/)
- [deeplearning.ai深度学习课程的中文笔记](https://github.com/fengdu78/deeplearning_ai_books)
- [机器学习训练秘籍 (Andrew NG)](https://github.com/AcceptedDoge/machine-learning-yearning-cn)
- [推荐系统实战](https://github.com/wangyuGithub01/E-book)

### 五、推荐专栏
- [刘建平Pinard](https://www.cnblogs.com/pinard/)：很多高质量文章
- [美团技术团队](https://tech.meituan.com/tags/%E7%AE%97%E6%B3%95.html)：美团的技术博客，新技术与实际应用相结合
- [华校专](http://huaxiaozhuan.com/)：基础算法讲解，多而全
- [王喆的机器学习专栏](https://zhuanlan.zhihu.com/wangzhenotes)：结合论文+工业界的应用，讲的很清晰 
- [北冥乘海生](https://zhuanlan.zhihu.com/c_78909596)：计算广告一书的作者
- [计算广告小觑](https://blog.csdn.net/breada/article/details/50572914)
- [深度学习前沿笔记](https://zhuanlan.zhihu.com/c_188941548)：NLP相关较多，预训练技术讲解的多

### 六、面试问题汇总
- [牛客网面经总结](https://www.nowcoder.com/discuss/165930)

### 七、其他面试常考
- [海量数据判重](https://www.nowcoder.com/discuss/153978)
- [常考智力题/逻辑题](https://github.com/wangyuGithub01/Machine_Learning_Resources/blob/master/pdf/IQ.md)
- [常考概率题](https://github.com/wangyuGithub01/Machine_Learning_Resources/blob/master/pdf/statistic.md)


