# 这是研究生毕设的第二种轴承寿命预测算法研究内容

## 需要解决的问题

1. 判断数据是健康还是开始故障
   * 深度学习检测异常值？
   * 特征提取应采用无监督学习——无监督学习的不确定性怎么限制？
2. 如何确保提取的特征具
3. 备想要的信息？以方便rnn进行回归预测
   * rnn可采用注意力机制，将注意力较低的那部分特征认为是没能提取出有用信息？感觉还是不合适
   * rnn根据预测结果反求输入数据的理想值？
