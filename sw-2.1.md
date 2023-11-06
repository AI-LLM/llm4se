# Software 2.1

![a](./ANN%20model.jpeg)

①首先神经网络作为一种有别于图灵机的基本计算模型和越来越多的软硬件实现，将解决很多图灵机（冯诺依曼计算机）遇到瓶颈的问题，比如NLP、复杂的软件工程等。ChatGPT实际上正在构筑一个已有软件之上的LLM层来形成新的软件架构样板。餐巾纸画图直接生成app和网页的实验也展示了未来软件开发的一种雏形：将设计和实现作为一个神经网络黑盒来训练出来，人类只关心需求（意图）和结果。这可能解决传统软件工程中产出物全部是人脑思想的不完全表达而造成人际合作的障碍。在这个过程中有可能不再需要产生新的冯诺依曼体系的传统代码，数据和训练成为新的“编程”方式，模型权重和结构是产出物“程序”。基于这种新的范式，传统基于文档、代码和人类间沟通的软件开发流程可以继承和借鉴，但至少极限编程XP等关注代码的部分会发生很大变化，也必然会产生新的方法。

Andrej Karpathy在2017年就阐述了这个[Software 2.0](https://karpathy.medium.com/software-2-0-a64152b37c35)的概念。CPU的单任务性能提高已经很难、多处理器并行难度不减、命令式编程（Imperative programming）在复杂任务下非常难，而硬件上GPU的的并行计算能力被发掘出来。当时人们已经讨论神经网络相当于一种函数式编程（Functional programming），可能解决确定性图灵机的效率问题。
后来发生一个大的变化我现在都知道了，就是GPT不再是用神经网络来解决NLP、视觉识别等图灵机模型效率低的单个或多个问题，而是用一个超大的模型和数据集直接[逼近AGI](https://www.youtube.com/watch?v=Ft0gTO2K85A)（或者我认为是逼近人类的知识学习和运用过程）。

此时Andrej Karpathy把LLM看作[新的操作系统(Operating System)的核心进程(kernel process)，一种新的计算范式(computing paradigm)](https://twitter.com/karpathy/status/1707437820045062561)。是否“神经网络”已经可以更具体的用LLM就解决全部问题？
神经网络的难题是需要大量的训练数据和高昂的训练成本，LLM“涌现”出的ICL等Prompting能力能像高级语言替代汇编和机器语言一样成为新计算范式的主要“编程”方式吗？类比“图灵完备”，Prompting会是“神经网络完备”的吗？

②对于已有的软件遗产和适合冯诺依曼计算机处理的功能，神经网络可以学习使用。所以前者如何更好的提供接口，两者如何更好的交互，会是一个重要课题。

对于冯诺依曼软件组件本身，复杂的开发工程问题参考第①点。③产出物代码的生成问题相当于一个NLP问题，LLM可以是一个新的工具一定程度上提高生产率。值得注意的是，如果通过①得到软件的一部分适合使用图灵机实现，因此要产生传统编程语言代码，这时并不一定需要生成人类自然语言再翻译成代码。