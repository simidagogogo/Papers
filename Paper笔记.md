# Paper



We ablate the 𝑁𝑎𝑡𝑖𝑣𝑒𝐸𝑥𝑝𝑒𝑟𝑡𝐿𝐹 module to validate the importance of AdaTT’s residual design which incorporates separate modules to fuse different experts.

我们消除了 𝑁𝑎𝑡𝑖𝑣𝑒𝐸𝑥𝑝𝑒𝑟𝑡𝐿𝐹 模块来验证 AdaTT 残差设计的重要性，该设计包含单独的模块来融合不同的专家。



First, at the lower level of fusion (level 0), our model is able to discern relationships between tasks. 

首先，在较低的融合级别（级别 0），我们的模型能够**辨别任务之间的关系**。



There is a clear distinction between the consumption and engagement task groups. Additionally, there is an asymmetric sharing pattern among the two consumption tasks: the classification consumption task mostly uses expert 2 and the classification regression task roughly uses expert 1 and 2 equally.

消费任务组和参与任务组之间有明显的区别。 此外，两个消费任务之间存在不对称的共享模式：分类消费任务主要使用专家2，分类回归任务大致平等地使用专家1和2。