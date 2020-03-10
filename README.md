# hw
-----
根据例程及自己的理解分别实现的感知机的原始形式，对偶形式，以及结合特征提取的对手写数字的二分类识别。  
##原始形式：
* 时间花费主要集中在训练过程中，对于数据的计算和验证以及参数的更新。
* 经过5000轮训练后精度可以达到97%左右。
## 对偶形式：
* 由于计算40000*40000的原始gram矩阵十分缓慢，在这里只是用的部分数据作为训练使用。
* 由于训练数据的原因精度大约在92%
## 特征提取：
* 通过了解一些特征提取的算法，实现了数据的降维，使得gram计算速度更快，在增加训练轮数的之后能达到99%。
