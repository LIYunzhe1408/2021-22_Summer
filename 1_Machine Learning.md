## 分类问题

1. 决策树 decision tree

2. 贝叶斯分类 Bayes classification

3. 支持向量机 support vector machine。有监督学习方法

   尝试寻找一个最优决策边界，使所有点到分界面的距离最大。

   - 非线性
   - 所需样本少，仅需边界的支持向量

   ![image-20220622103929445](C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220622103929445.png)

4. 逻辑回归 将回归值映射到离散类别

   e.g. 二项逻辑回归：

   ![image-20220622111218850](C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220622111218850.png)

   其中的线性回归用简单的例如：y = w1 * x1 + w2 * x2 + ...

   对于得到的回归值用sigmoid函数，二项时如下：

   ![image-20220622111333933](C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220622111333933.png)

   

## 回归问题

1. 线性回归：先选拟合函数的形式，再选损失函数（量化预测值和真实值的误差），再用算法拟合（最小二乘、梯度下降）
2. 岭回归：解决过拟合
3. Lasso回归：解决过拟合



## 聚类问题

1. K-means：分类
2. 高斯混合模型：分布。EM算法
3. 密度聚类
4. 层次聚类



## 生成问题

1. 隐马尔可夫模型：中文分词，词性标注、天气预测。
2. LDA主题模型



## 评价指标

1. 召回率：地震预测（高）、嫌疑人预测（低）
2. 宏平均&维平均：大选投票
3. 平均方差