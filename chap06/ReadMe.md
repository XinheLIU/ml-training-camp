## Chapter 05



打比赛
很多比赛核心是data leakage
data leakage detection看加密
强加密 加随机数 与训练没法用
imbalanced sample 手调
盗用代码 model stacking 平均
测试集乱猜 代替validation set的问题

k fold其实是数据太少的问题
k fold 抽样问题 分层抽样 地域 年龄 数据质量 渠道 
和项目经理 客户交流

测试集 销售会用POC甩锅 POC验证好 不要耍赖
实际工作中一定要在验证场景多方沟通

数据分析被优化 非核心 非研发 luxury etc

msri 机构
宛然老师学习资料


平安科技 坚信金科 蚂蚁金服 贷款违约
业务对建模指导非常少
实习生干死专家


可解释 从异常解释角度说 并非从模型说
研究字节跳动内部职级 架构体系
AI内参 数据科学


鲁棒性？看一些文章
和部署 新数据等都有关系 etc

消费者数据 男性32是个坎

决策树 医疗模型
树的可解释行 feature importance不可解释

gbdt 论文
提升

xgboost和论文


https://github.com/rwbfd/ml-training-camp


paper 复县 非常非常重要
代码不复杂
分布式部署
error checking step by step

英文写作和学数学的优势 英文论文元和信息源



likelihood is not probability

- HMM model
    - Baum Welch
- Bayes
    - Variational autoencoder



x-1

endogenity_econometrics

variational autoencoder 原文



[sympy](https://www.sympy.org/en/index.html) 



library

translate mathematcis to code

- testing every step : set checks/debug checkings at every step
  - have test set/numbers
  -  for code testing
  - check distributions
  - check overflows and underflow
    - loops and predications
  - check gradients
    - finite difference check

jax
https://jax.readthedocs.io/en/latest/notebooks/quickstart.html


reference 
andrew ang machine learning yarning


scipy, fortran 77 vs matlab (scientific computingIde)

Identification Issues **
http://www.doc88.com/p-9179650579913.html

multicollinearity how to handle ????

- chapter 2 cython situation

think

one-hot encoding in logistic regression
  - dependends on $w^T X + b$ whether it has b intercept
  - multicollinearity \sum x_i = 1


Bugs in Scipy (****) 

  gram-schmit implementation