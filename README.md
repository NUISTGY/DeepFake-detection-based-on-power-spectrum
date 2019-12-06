# DFD-based-on-power-spectrum
复现：基于一维功率谱的Deepfake Detection

## 使用了三种分类器：SVM，LR，密集链接网络
在训练集验证集为40k张的情况下（8：2）：
 ```
    SVM acc达到96.6%
    LR  acc达到70%
    密集链接网络无法完成分类
 ```
 
 后续尝试对输入数据升维操作后发现LR准确率有所上升，小伙伴们可以自己加上一些预处理的相关操作训练试试。
