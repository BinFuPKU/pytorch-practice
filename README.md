# pytorch-practice

个人实现pytorch高级编程（环境：mac m1，python 3.9），包括基本知识、卷积神经网络、循环神经网络、生成对抗、模型部署和分布式训练（2022)。

1.张量：属性、高级使用方法（分布统计、函数）和计算，Dataset封装，动态修改学习速率 lr_scheduler.StepLR等。

2.传统机器学习模型：回归、分类模型。

3.神经网络：激活函数、过拟合。

4.卷积神经网络：卷积与反卷积、下采样与上采样、不同维度的池化、pad补全方法、图片读取、利用register_forward_hook钩子来可视化中间层。

5.循环神经网络：RNN、LSTM、GRU、文本处理。

6.生成对抗训练。

7.模型部署：onnx及其onnxruntime工具、Netron可视化ONNX格式的模型、torchscript（torch.jit.trace / torch.jit.script）、推理时间效果对比。

8.分布式训练：torch.nn.parallel下数据并行的DataParallel（单进程多线程） 和DistributedDataParallel（多进程）实现单机多卡训练。
