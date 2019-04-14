岗位：计算机视觉算法岗

关于题目：凭记忆整理；

关于侵权：如果侵犯公司隐私，请告知删除；

关于个人：跨专业菜鸟一枚，只是给大家提供一些参考。

### 1.搜狗杭州cv岗

结果：需要六个月实习，去不了

全程50分钟，无传统算法题。

根据记忆，大概有如下一些问题。

##### 1.介绍一下前一段实习

简单介绍了一下目标检测的实习经历

##### 2.目标检测two-stage模型

RCNN-->SPPNet-->Fast RCNN-->Faster RCNN-->RFCN-->DCN-->DCNv2

其中重点问了selective search和RPN，另外每个的创新点需要讲一下。

##### 3.目标检测one-stage模型

YOLO系列、SSD、RefineDet
yolo和ssd区别

##### 4.resnet和densenet及其区别

##### 5.Inception系列的演化

##### 6.BN的原理和实现细节，其中均值和标准差的计算，以及训练和测试时分别怎么用

##### 7. [Focal loss](https://blog.csdn.net/u014380165/article/details/77019084)

##### 8.小目标检测用什么方法
##### 9.mobilenet

##### 10.项目和比赛的某些细节
##### 11.coco冠军方案
---------------------

### 2.头条AI lab
开始以为头条就一个nlp类型的公司，拿来练手了，也是心大，第一天投，第二天就面试了，就刷了个位数的题，手撕代码虽然很简单，结果依然很惨。自然是一周内凉凉，后来又被另一个组捞，但是二面后告知对方不想做非检测方向，就结束了。

#### 一面（1小时）

##### 1.算法：x的n次方（x任意，n自然数）

##### 2.算法：链表排序

##### 3.目标检测sota模型

##### 4.多标签不平衡怎么处理
##### 5.改善nms
iou-guided-nms:iounet
soft-nms

##### 6.改善rpn

##### 7.rfbnet
Receptive Field Block
模拟人类视觉的感受野加强网络的特征提取能力，在结构上RFB借鉴了Inception的思想，主要是在Inception的基础上加入了dilated卷积层（dilated convolution），从而有效增大了感受野（receptive field）

##### 8.coco冠军方案
#### 二面（1小时）
##### 1.介绍实习
##### 2.目标检测模型发展
##### 3.深度可分离卷积
##### 4.focal loss
##### 5.Densenet，有没有改进模型
##### 6.多标签/多任务不平衡怎么处理
##### 7.two-stage为什么效果更好
##### 8.算法：螺旋打印二维数组
### 3.平安科技

结果：offer，后来导师不让日常实习，说想去提前一个月联系。

##### 1.相同层数，densenet和resnet哪个好，为什么densenet更好

##### 2.激活函数

##### 3.损失函数

##### 4.数字图像处理，各种滤波

##### 5.focal loss

##### 6.深度可分离卷积

##### 7.k折交叉验证

##### 8.模型融合，adaboost

### 4.第四范式

结果：一面写两道算法题，面试官说写的不错，但是我问面试官怎么看待第四范式毁约应届生，可能因为这个没给二面机会吧，不过我当时心情不怎么好，这样问确实有点不太妥，毕竟跟面试官也没什么关系。

```
第一题：按照字母顺序删除指定数目的字母
case：
input：
abcdabcd 4
output：
cdcd

第二题：给定数字n，输出循环三角形
case：
input
5
output：
1
2 12
3 13 11
4 14 15 10
5 6  7  8  9
```
### 5.海康威视

通知offer的时候已经知道导师不同意日常实习，就直接拒了。

一面电面，二面现场上机，有点迷。

#### 一面
##### 1.自我介绍
##### 2.人脸属性SOTA模型
##### 3.实验室科研项目
##### 4.天池比赛
##### 5.kaggle比赛
##### 6.为什么选择densenet
##### 7.kaggle比赛阈值
##### 8.实习内容
##### 9.refinedet和rfcn-dcn
##### 10.二叉树的深度
##### 11.排序，快排、堆排序
##### 12.深拷贝和浅拷贝
#### 二面

##### 1.算法：爬楼梯

##### 2.算法：连续子数组的最大和

##### 3.算法：最长不重复子串

##### 4.C++：继承与多态

##### 5.C++：指针与引用的区别

##### 6.数组和链表

### 6.商汤科技

research offer，导师不同意日常实习，已转暑期直通终面。

强推一下商汤，面试官和hr都超级nice。

#### 一面/二面
##### 1.自我介绍
##### 2.实验室项目
##### 3.mask rcnn
roialign
##### 4.refinedet
##### 5.rfcn-dcn
##### 6.分类loss函数
##### 7.传统机器学习
logistic回归
svm
boosting
bagging

##### 8.数据预处理
##### 9.处理不平衡的方法
##### 10.ssd和yolo对比
##### 11.retinanet
##### 12.算法：二叉树路径和为给定值
##### 13.算法：一个数组，其他数出现两次，另一个出现一次，找出；
改进：另两个出现一次
##### 14.算法：链表中倒数第k个结点
##### 15.概率：圆上任意三个点组成的三角形，包含圆心的概率
##### 16.gan
##### 17.分布式，多卡使用
##### 18.什么框架
dataloader，dataset，sampler关系
##### 19.创新的想法
##### 20.天池比赛的思路
##### 21.实习内容
### 7.旷视一面/二面/三面

hr加了微信，三面后第二天还微信问了一堆，然后说综合评估，然后就没有然后了，感觉略坑，都这样了，挂了发个邮件也好，这方面头条就做的很好。

##### 1.说一下nms

##### 2.人脸和身体一起检测，怎么处理

##### 3.目前目标检测存在的问题，以及你的解决思路

##### 4.人脸检测

##### 5.算法：逆序对

##### 6.概率：x，y，z都是（0，1）均匀分布，x+y+z<1的概率

### 8.滴滴一面
主要看下是不是对分类、检测、分割是不是都比较熟悉，可能是需要全栈做项目吧。

感觉我也没兴趣，对方也没兴趣，不知道什么状态。

### 9.微软小冰

二面后两周左右问了说没挂，综合评估，感觉应该是已经挂了。

不过微软的面试官真的很nice。

#### 一面
##### 1.人脸属性的任务，方法

##### 2.天池

##### 3.kaggle

##### 4.目标检测

##### 5.n个文件（海量文件），查找和排序，二分查找时间复杂度

归并排序，二分查找
#### 二面
##### 1.算法：一个数组里面是股票值，求什么时候购买和卖出，收益最大。

一个数记录最大差，一个记录最小元素，遍历一次即可
##### 2.算法：最长连续公共子串

dp
##### 3.知道哪些cv任务

分类/检测/分割
##### 4.卷积/池化/全连接层/BN等组件

IN/GN等
##### 5.激活函数

##### 6.优化器

##### 7.mAP的概念

### 10.阿里云

offer

#### 一面/二面
##### 1.多任务和多标签

##### 2.传统机器学习，svm，boosting，bagging，随机森林

bagging和随机森林的区别
##### 3.属性任务不平衡

##### 4.目标检测存在的问题

小目标，怎么解决
遮挡，怎么解决

#### 三面
##### 1.属性任务实际应用

##### 2.目标检测实际应用

##### 3.属性任务创新之处

##### 4.天池创新

##### 5.目标检测精度

##### 6.属性任务提升思路

#### 四面
##### 1.深度神经网络和深度学习区别

##### 2.深度学习为什么比机器学习好

##### 3.各种排序算法，快排时间复杂度，时间复杂度推导，

时间复杂度O(n)的排序算法
##### 4.detection两阶段阈值，有什么好方法

##### 5.目标检测有什么改进

##### 6.目标检测实习调参

#### HR面
##### 1.自我介绍

##### 2.实习

##### 3.个人规划

##### 4.希望做研究还是工程

##### 5.有没有和人发生争执

##### 6.遇到的困难

##### 7.给你项目怎么规划

##### 8.有没有论文


### 11.腾讯一面
被cdg广告部门锁简历，贼气，系统拒面了，依然打电话，问了强化学习，Qlearning什么的，说编程能力强，不懂广告可以去学，自我感觉编程能力不好，而且在跟同学去吃饭的路上，拒了。

### 12.Intel北京研究院
这个是日常实习，告诉面试官只能暑期，他坚持面一下。

也是超级nice的面试官，感觉好像外企面试官都很好，当然国内一些公司比如商汤阿里的部分面试官也很好。

讨论很有深度，也很舒服，感觉双方都比较满意。

说如果暑期找实习可以提前一个月联系。

##### 1.介绍自己的科研和实习经历

##### 2.实习用的模型

具体达到的recall和precision
##### 3.weighted sample和focal loss

##### 4.人脸属性sota模型

##### 5.天池模型改进的解释

##### 6.解决不平衡的思路

##### 7.train，val，test

过拟合，怎么调参
##### 8.如果训练集不平衡，测试集平衡，直接训练和过采样欠采样处理，哪个更好

##### 9.softmax

##### 10.F1score是$\alpha$=1，那么$\alpha$什么时候取其他值