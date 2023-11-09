## AI 概述

<img src="C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220614110002270.png" alt="image-20220614110002270" style="zoom:50%;" />

DP: 数据+算力

## 深度学习

1. 图像识别：将语义概念类似的图像归为一类

   - 困难和挑战：语义鸿沟（底层视觉特性 和 高层语义概念 之间的鸿沟）。

     - 相似的视觉特性，不同的语义概念：

       <img src="C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220614110937378.png" alt="image-20220614110937378" style="zoom: 67%;" />

     - 不相似的视觉特征，相同的语义概念：

       <img src="C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220614111150738.png" alt="image-20220614111150738" style="zoom:67%;" />	

   - 解决方法：

     - 传统方法：用全局的视觉底层特征统计量表示图像

       <img src="C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220614111547195.png" alt="image-20220614111547195" style="zoom:67%;" />

       - 问题：全局特征丢失图像细节

         <img src="C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220614111656276.png" alt="image-20220614111656276" style="zoom:50%;" />

       - **人工提取特征**（纹理、大小等） + 根据特征分类（分类器）-- 费时费力

     - 深度学习：学习特征，而不是人工提取

       - 通过训练数据得到一个 *f* () 函数用于分类

         <img src="C:\Users\16690\AppData\Roaming\Typora\typora-user-images\image-20220614121553627.png" alt="image-20220614121553627" style="zoom:67%;" />

       - 如何得到一个好的 *f*(x) 是关键。

       - 这个 *f* () 是我们人为设计的模型、网络等

       - 一般过程：

         - 模型：全连接神经网络、卷积神经网络、循环神经网络
         - 策略：模型选择、损失函数选择
         - 算法：学习参数、优化算法、反向传播算法

## 编程语言

Python - AI







## PaddleHub

摒弃前期设计模型的过程，直接使用。

不用花费大量精力从头开始训练。

**模型即软件**，一键下载

**迁移学习**，自动调参

**端到端部署**





## 迁移学习

有一个A任务的模型；

B任务和A任务类似（比如都是图像分类）；

用B任务的小数据在A任务的模型上进行一个微调；

得到一个新的B任务的模型。



## 深度学习流程：

明确需求-数据优化-模型选取-调参训练-预测部署