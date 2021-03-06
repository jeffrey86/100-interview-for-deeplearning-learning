# 百面深度学习-学习

## 卷积神经网络

- 简述卷积的基本操作，并分析其与全连接层的区别？
- 在卷积神经网络中，如何计算各层的感受野大小？
- 卷积层的输出尺寸、餐数量和计算量。
- 简述分组卷积及其应用场景。
- 简述空洞卷积的设计思路
- 简述转置卷积的主要思想以及应用场景。
- 可变性卷积旨在解决哪类问题？
- 批归一化是为了解决什么问题？它的参数有何意义？它在网络中一般放在什么位置？
- 用于分类任务的卷积神经网络最后几层一般是什么层？在最近几年有什么变化？
- 简述卷积神经网络近年在结构设计上的主要发展和变迁（从AlexNet到ResNet系列）。
- 卷积神经网络中的瓶颈结构和沙漏结构提出的初衷是什么？可以应用于哪些问题？

## 循环神经网络

- Dropout为什么可以缓解过拟合问题
- 描述循环神经网络的结构及参数更新方式。
- 如何使用卷积神经网络对序列数据建模？
- 循环神经网络为什么容易出现长期依赖问题？
- LSTM是如何实现长短期记忆功能的
- 再循环神经网络中如何使用Dropout？
- 如何用循环神经网络实现Seq2Seq映射？
- Seq2Seq框架在编码-解码过程中是否存在信息丢失？有哪些解决方案？
- GRU是如何用两个门控单元来控制时间序列的记忆及遗忘行为的？

## 图神经网络

- 什么是图谱和图傅里叶变换
- 以GCN为例，简述基于频谱域的图神经网络的发展。
- 以GAT、GraphSAGE为例，简述基于空间域的图神经网络的主要思想。
- 简述PinSage的模型设计和实现细节。
- 基于图神经网络的推理框架有何优势？
- 简述图神经网络的推理机制在其他领域中的应用。

## 生成模型

- 简单介绍RBM的训练过程。如何拓展普通的RBM以对图像数据进行建模？
- 简述VAE的基本思想，以及它是如何用变分推断方法进行训练的？
- 什么是最大均值差异？它是如何应用到生成式矩阵匹配网络中的？
- DBN与DBM有什么区别？
- VAE如何控制生成图像的类别？
- 如何修改VAE的损失函数，使得隐藏层的编码是相互解耦的？
- 自回归方法如何应用在生成模型上？
- 原始VAE存在哪些问题？有哪些改进方式？
- 如何将VAE与GAN进行结合？

## 生成对抗网络

- 简述IS和FID的原理。
- 有哪些问题是属于图像到图像翻译的范畴的？GAN是如何应用在其中的？
- 简述AE、VAE、GAN的联系？
- 简单介绍GAN模型结构的演进。
- 列举一些近几年针对GAN的训练过程或训练技巧的改进、
- GAN用于生成高质量、高分辨率图像时会有哪些难点？简述从SNGAN、SAGAN到BigGAN的发展过程。
- 简述CycleGAN的原理。
- 简单介绍GAN目标函数的演进。
- GAN为什么适用于半监督学习？生成数据在半监督学习中起到了什么作用？
- 原始GAN在理论上存在哪些问题？
- 原始GAN在实际应用中存在哪些问题？

## 强化学习

- 什么是强化学习？如何利用马尔科夫模型决策过程来描述强化学习？
- 举例说明时序列分强化学习和蒙特卡洛强化学习的区别。
- 强化学习中的有模型学习和免模型学习有什么区别？
- 基于策略迭代和基于价值迭代的强化学习方法有什么区别？
- 什么是Q-learning？
- 简述强化学习在人工智能领域中的一些应用场景。
- 什么是DQN？它与传统Q-learning有什么联系与区别？
- 简述Sarsa和Sarsa(λ)算法，并分析它们之间的联系与区别。

## 元学习

- 元学习适合哪些学习场景？可解决什么样的学习问题？
- 使用学习优化算法的方式处理元学习问题，与基于记忆的云学习模型有哪些区别？
- 学习公共初始点的方法与预训练的方法有什么不同？
- 元学习与有监督学习/强化学习具体有哪些区别？
- 给定一个传统的多分类数据集，如何构造一份适于元学习的K次N分类数据集？
- 如何用最近邻方法将一个普通的神经网络训练过程改造为元学习过程？
- 元学习中非参数方法相比参数方法有什么有点？
- 带读写操作的记忆模块（如神经图灵机）在元学习中可以起到什么样的作用？
- 基于初始点的元学习方法中的两次反向传播有什么不同？
- 试概括并举例当前元学习方法的主要思路。它们大致可以分为哪几类？
- 如何用微调训练的方法将一个普通的神经网络训练过程改造为元学习过程？
- 如何基于LSTM设计一个可学习的优化器？
- 基于初始点的元学习模型，用在强化学习中时与分类或回归任务有何不同？
- 从理论上简要分析一下元学习可以帮助少次学习的原因。
- 如何用度量学习和注意力机制来改造基于最近邻的元学习方法？
- 如何构造基于神经图灵机和循环神经网络的元学习模型？
- 如何设计基于LSTM优化器的元学习的目标函数和训练过程？
- 上述LSTM优化器如何克服参数规模过大的问题？
- 简单描述基于初始点的元学习方法。

## 自动化机器学习

- 自动化机器学习要解决什么问题？有哪些主要的研究方向？
- 简述神经网络架构搜索的应用场景和大致工作流程。
- 简单介绍神经网络架构搜索中有哪些主要的研究方向。
- 模型和超参数有哪些自动化调优方法？它们各自有什么特点？
- 贝叶斯优化中的获取函数是什么？起到什么作用？请介绍常用的获取函数。
- 什么是一次架构搜素？它有什么优势和劣势？
- 简述贝叶斯优化中用高斯过程回归计算目标函数后验分布的方法。高斯过程回归可以用于哪种类型或者层次型模型配置参数的优化吗？
- 简述可微架构搜索的主要原理。

## 计算机视觉

- 简述物体检测领域中的单步模型和两步模型的性能差异及其原因。
- 有哪些措施可以增强对于小物体的检测效果？
- 简述图像分割中经常用到的编码器-解码器网络结构的设计理念。列举2~3个基于编码器-解码器结构的图像分割算法。
- 简单介绍基于候选框和基于像素分割的文本检测算法，并分析它们的优劣。
- 列举1~2个基于深度学习的端对端文本检测和识别算法。
- 在2D人体姿态识别中，自底向上方法与自顶向下方法有什么区别？
- 简单介绍两步模型R-CNN、SPPNet、Fast R-CNN、Faster R-CNN的发展过程。
- 简单介绍单步模型YOLO、YOLOv2、YOLO9000、YOLOv3、YOLOv4和YOLOv5的发展过程。
- DeepLab系列模型中每一代的创新是什么？是为了解决什么问题？
- 图像标注任务评测指标有哪些？简述它们各自的评测重点和存在的不足。
- 如何通过单幅图像进行3D人体姿态识别？

## 自然语言处理

- 神经机器翻译模型经历了哪些主要的结构变化？分别解决了哪些问题？
- 常见的词嵌入模型有哪些？它们有什么联系和区别？
- 神经机器翻译如何解决未登录词的翻译问题？
- 如何对文本中词的位置信息进行编码？
- 语言模型的任务形势是什么？语言模型如何帮助提升其他自然语言处理任务的效果？
- 训练神经机器翻译模型时有哪些解决双语语料不足的方法？
- 在给文本段落编码时如何结合问题信息？这样做有什么好处？
- 如何使用卷积神经网络和循环神经网络解决问答系统中的长距离语境依赖问题？Transformer相比以上方法有何改进？
- 对话系统中哪些问题可以使用强化学习来解决？

## 推荐系统

- 一个典型的推荐系统算法通常包括哪些部分？每个部分的作用是什么？有哪些常用算法？
- 推荐系统中为什么要有召回？在召回和排序中使用的深度学习算法有什么异同？
- 如何从神经网络的角度理解矩阵分解算法？
- 最近邻问题在推荐系统中的应用场景是什么？具体算法有哪些？
- 评价点击率预估模型时为什么选择AUC作为评价指标？
- 如何使用深度学习方法设计一个根据用户行为数据计算物品相似度的模型？
- 如何用深度学习的方法设计一个基于会话的推荐系统？
- 评价点击率预估模型时，线下AUC的提高一定可以保证线上点击率的提高吗？
- 二阶因子分解机中稀疏特征的嵌入向量的内积是否可以表达任意的特征交叉系数？引入深度神经网络的因子分解机是否提高了因子分解机的表达能力？

## 计算广告

- 在实时竞价场景中，制定广告的出价策略是一个什么问题？
- 简述CTR预估中的因子分解机模型（如FM、FFM、DeepFM等）。
- 如何对CTR预估问题中用户兴趣的多样性进行建模？
- 多臂老虎机算法是如何解决CTR预估中的冷启动问题的？
- 设计一个深度强化学习模型来完成竞价策略。
- 简述一个可以提高搜索广告召回效果的深度学习模型。
- 设计一个基于强化学习的算法来解决广告主的竞价策略问题。

## 视频处理

- 图像质量评价方法有哪些分类？举例一个常见的图像质量评估指标。
- 设计一个深度学习网络来实现帧内检测。
- 如何利用深度学习良好的图像特征提取能力来更好地解决NRIQA问题？
- 超分辨率重建方法可以分为哪几类？其评价指标是什么？
- 如何使用深度学习训练一个基本的图像超分辨率重建模型？
- 设计一个深度学习网络来实现环路滤波模块。
- 如何在较高的监控视频压缩比的情况下，提升人脸验证的准确率？
- 在基于深度学习的超分辨率重建方法中，怎样提高模型的重建速度和重建效果？
- 如何用深度学习模型预测网络中的某个节点在未来一段时间内的带宽情况？
- 怎样将图像的超分辨率重建方法移植到视频的超分辨率重建任务中？
- 如何利用深度学习完成自适应码率控制？

## 计算机听觉

- 音频事件识别领域常用的数据集有哪些？
- 简述音频信号特征提取中经常用到的梅尔频率倒谱系数的计算过程。
- 简单介绍一些常见的音频事件识别算法。
- 分别介绍一下传统的语音识别算法和当前主流的语音识别算法。

## 自动驾驶

- 一个自动驾驶系统在算法层面上可以分为哪几个模块？
- 如何设计一个基于深度神经网络的端到端自动驾驶模型？
- 如何将强化学习用于自动驾驶的决策系统？
