机器学习概述：


机器学习基本步骤：
1. 获取数据（获取、清洗、存储（hdfs、Hbase。。。））
2. 数据拆分训练集合测试集
3. 用特征向量训练算法
4. 在测试集上评估算法
5. 算法迭代与改进
6. 实际应用
7. 获取更多数据
8. 。。。



算法评估标准：
1. 准确率
2. 速度
3. 规模


常用算法：
（1）. 监督学习（样本有类别标记）
	1. 分类（目标概念为已知类别）
		a. KNN（Nearest Neighbors Classification）（k-最邻近）
		b. DT（Decision Tree）（决策树）
		c. SVM（Support Vectors Machine）（支持向量机）
		d. NN（Neural network）（神经网络）
		e. NB（Naive Bayes）（朴素贝叶斯）
	2. 回归（目标概念为连续值）
		a. LR（Linear regression）（线性回归）
		b. NLR（Non-Linear regression）（非线性回归）
（2）. 无监督学习（样本无类别标记）
	K-Means算法（一种聚类算法）




KNN：
1. 用未知和已知进行比对
2. 选择参数K
3. 根据投票法则归类
