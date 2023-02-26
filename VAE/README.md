在这个项目中，我实现了一个简单的 VAE 并在 MNIST 上对其进行了训练。

该项目部分采用了 CNN-Cifar10 项目和 GRU 项目遵循的项目流程标准。 这里没有封装过渡阶段。

但我尝试了一个新技巧，它允许它在训练期间保存参数配置，一旦模型在测试集上达到最佳性能，它的参数配置将保存在字典中。

训练后，我们可以加载具有最佳参数配置的模型，并使用它生成一些图片并绘图以查看模型在视觉上的表现如何。


In this project , I implemented a simple VAE and trained it on MNIST.

This project partially adapat the project procedure standard which was followed in Project CNN-Cifar10 and GRU. the tranning phase wasn't encapsulized here. 

But I tried a new trick , which allow it to save the  parameter configuration during the training, once the model reachs a best performance on test set, its para config will be saved in dictionary.

after training ,we can load model with the best para config and generate some pictures with it and plot to see how well the model performs visually.

