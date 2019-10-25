# 20191023

#### 孟钰鑫

- 海洋科学与人工智能的交叉
  - 物理海洋的模型与人工智能相关模型的结合
- 海洋数据来源
  - 观察数据（真实数据）：较少，价值高
  - 数值模式（模拟数据）：数量可观，可信度低
  - 数值同化（根据真实数据校正过的模拟数据）：目前常用
- Attention机制和多任务学习应用于温度校正

#### 王益国

- 项目前期数据处理的基本方法。
- 时间序列异常值检测方法。
- 为什么要读在职博士？
- [参考：The Ultimate Guide to Data Cleaning](https://towardsdatascience.com/the-ultimate-guide-to-data-cleaning-3969843991d4)

#### 修士勇

- 项目情况
  - LSTM用于气温和盐度预测，时间跨度不一样的问题。
  - 异常值处理的问题
  - 封装了代码

- 论文

  - **Attention** **Is All You Need** 
    - Transformaer结构

  ![2019-10-24_08h36_37.png](http://pz38o5vs6.bkt.clouddn.com/2019-10-24_08h36_37.png)

  ![2019-10-24_08h36_50.png](http://pz38o5vs6.bkt.clouddn.com/2019-10-24_08h36_50.png)

  - Stand-Alone Self-Attentionin Vision Models
  - - ![2019-10-24_08h37_12.png](http://pz38o5vs6.bkt.clouddn.com/2019-10-24_08h37_12.png)
  - **Local Relational Networks for Image Recognition**
    - ![2019-10-24_08h37_17.png](http://pz38o5vs6.bkt.clouddn.com/2019-10-24_08h37_17.png)

<img src="http://pz38o5vs6.bkt.clouddn.com/2019-10-24_08h37_21.png" alt="2019-10-24_08h37_21.png" style="zoom:67%;" />

#### 伊俊杰

- 项目前期数据分析的情况
- 学习的情况
  - 聚类算法
  - pytorch
  - 深度学习课程
  - 论文

#### 王展梁

- 项目中时间序列方法

  - 传统的方法
    - ARMA
    - ARIMA
  - 基于深度学习的时间序列方法
    - RNN
    - LSTM
    - GRU

- 研究问题

  - 线性约束下矩阵秩最小化问题

    - 本身是一个线性等式约束的非凸优化问题
    - NP Hard 问题
    - 图像复原是低秩矩阵秩最小化问题的一种特例。
    - 由局部信息计算总体信息中最优化的一个。

  - 解决方案：寻求秩函数的合理替代而得到近似问题，通过求解替代问题
    寻找原问题的近似解。

    - Fazel 等人提出用核范数来近似矩阵的秩函数。

      - 这是一个凸优化问题。
      - 恢复能力相对较差

      ![2019-10-24_08h46_05.png](http://pz38o5vs6.bkt.clouddn.com/2019-10-24_08h46_05.png)

      

      

      ![2019-10-24_08h45_59.png](http://pz38o5vs6.bkt.clouddn.com/2019-10-24_08h45_59.png)

- 一些想法

#### 本周遗留问题

- 项目中叶绿素异常值检测问题。
- 修士勇论文2,3中细节问题
  - 论文2，Stand-Alone Self-Attentionin Vision Models
    - 怎么用的注意力机制
    - ”红绿蓝“是什么意思？为什么是”红绿蓝“？
  - 论文3，**Local Relational Networks for Image Recognition**
    - 更深入的层面？
    - 为什么这么做？

#### 其他

- 时间：
  - 隔周周二晚上开项目小组学习会
- 要求：
  - 每人至少讲一篇有关Lstm，convLstm，Lstm其他的一些变种，多任务学习、图网络、时空预测的论文。
  - 修士勇可多讲下代码分析，王展梁每次给我们讲一个和深度学习相关的数学点。

#### 补充资源

- [一文读懂「Attention is All You Need」| 附代码实现](https://mp.weixin.qq.com/s?__biz=MzIwMTc4ODE0Mw==&mid=2247486960&idx=1&sn=1b4b9d7ec7a9f40fa8a9df6b6f53bbfb&chksm=96e9d270a19e5b668875392da1d1aaa28ffd0af17d44f7ee81c2754c78cc35edf2e35be2c6a1&scene=21#wechat_redirect)
- [奇异值分解(SVD)原理与在降维中的应用](https://www.cnblogs.com/pinard/p/6251584.html)
- [一文让你通俗理解奇异值分解](https://mp.weixin.qq.com/s?__biz=MzA5ODUxOTA5Mg==&mid=2652567516&idx=1&sn=7239d6d651fe77e996402c191fa68ad2&chksm=8b7e0687bc098f919deb57b6113339467bd1abe42cb53f7db5909a90d6d4cb22291bc983c903&mpshare=1&scene=1&srcid=0628va3WXVV53n8IsWAdmu5O#rd)