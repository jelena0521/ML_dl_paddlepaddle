# REC_dl_paddlepaddle
Based on deeplearning, the framework is paddlepaddle

思路：
1、将用户特征如年龄、性别、职业等进行embedding
2、将物品特征如名字、类别、年限等进行embedding
3、通过全连接、相似度等前向传播计算得到pre
4、和label比较，进行反向传播，优化loss，跟新梯度
5、保留模型和参数
