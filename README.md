# PyTorch-Learning

#### **PyTorch: [维基百科](https://zh.wikipedia.org/wiki/PyTorch)**  

PyTorch是一个开源的Python机器学习库，基于Torch，底层由C++实现，应用于人工智能领域，如自然语言处理。它主要由Facebook的人工智能研究团队开发，并且被用于Uber的概率编程软件Pyro。
PyTorch主要有两大特征：
  * 类似于NumPy的张量计算，可使用GPU加速；
  * 基于带自动微分系统的深度神经网络。  
PyTorch包括torch.nn、torch.optim等子模块。

#### **Pytorch常用工具包**  
  * torch ：类似 NumPy 的张量库，强 GPU 支持 ；   
  * torch.autograd ：基于 tape 的自动区别库，支持 torch 之中的所有可区分张量运行；   
  * torch.nn ：为最大化灵活性未涉及、与 autograd 深度整合的神经网络库；   
  * torch.optim：与 torch.nn 一起使用的优化包，包含 SGD、RMSProp、LBFGS、Adam 等标准优化方式；
  * torch.multiprocessing： python 多进程并发，进程之间 torch Tensors 的内存共享；   
  * torch.utils：数据载入器。具有训练器和其他便利功能；   
  * torch.legacy(.nn/.optim) ：处于向后兼容性考虑，从 Torch 移植来的 legacy 代码；
  
#### **PyTorch官方API文档**
[https://pytorch.org/docs/stable/torch.html](https://pytorch.org/docs/stable/torch.html)  
(讲真，官方文档属实有点辣鸡)


代码参考：[动手学深度学习（pyTorch版）](https://www.bookstack.cn/read/Dive-into-DL-PyTorch/933bc36e0c35f00b.md)

和原书一样，内容大体可以分为3个部分：

1. 第一部分（第1章至第3章）涵盖预备工作和基础知识。
    1. 第1章介绍深度学习的背景。
    2. 第2章提供动手学深度学习所需要的预备知识。
    3. 第3章包括深度学习最基础的概念和技术，如多层感知机和模型正则化。如果读者时间有限，并且只想了解深度学习最基础的概念和技术，那么只需阅读第一部分。
2. 第二部分（第4章至第6章）关注现代深度学习技术。
    1. 第4章描述深度学习计算的各个重要组成部分，并为实现后续更复杂的模型打下基础。
    2. 第5章解释近年来令深度学习在计算机视觉领域大获成功的卷积神经网络。
    3. 第6章阐述近年来常用于处理序列数据的循环神经网络。阅读第二部分有助于掌握现代深度学习技术。
3. 第三部分（第7章至第10章）讨论计算性能和应用。
    1. 第7章评价各种用来训练深度学习模型的优化算法。
    2. 第8章检验影响深度学习计算性能的几个重要因素。
    3. 第9章和第10章分别列举深度学习在计算机视觉和自然语言处理中的重要应用。这部分内容读者可根据兴趣选择阅读。
    
 
 reference：
 
 [https://pytorch.org/resources/](https://pytorch.org/resources/)  -> [https://pytorch.org/tutorials/](https://pytorch.org/tutorials/)

