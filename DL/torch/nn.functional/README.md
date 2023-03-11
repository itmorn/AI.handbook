# torch.nn.functional和torch.nn的区别
torch.nn是PyTorch中的一个模块，它提供了一个面向对象的接口来定义神经网络模型，包括各种层、损失函数和优化器等。

而torch.nn.functional是PyTorch中的一个函数库，提供了一些常用的非线性函数、损失函数等。相比于torch.nn，torch.nn.functional更加灵活，因为它可以直接使用PyTorch的张量作为输入，而不需要事先定义模型结构。另外，torch.nn.functional中的函数是纯函数，不包含任何可学习的参数，因此可以在模型的前向传播过程中直接调用，而不需要像torch.nn一样需要定义层的实例。

因此，torch.nn主要用于定义模型的结构，而torch.nn.functional主要用于定义模型的前向传播过程中所需的一些操作。在实际使用中，可以根据需要选择使用torch.nn或torch.nn.functional。

# torch.nn底层调用的是torch.nn.functional
torch.nn中定义的大多数层和函数都是基于torch.nn.functional实现的。在torch.nn中，通常会定义一个类来表示某一层的结构和参数，并且该类的forward()方法会调用相应的torch.nn.functional函数来实现具体的计算过程。因此，torch.nn.functional可以被视为torch.nn的底层实现。

例如，torch.nn.Conv2d表示一个二维卷积层，它的forward()方法调用了torch.nn.functional.conv2d()函数来实现卷积运算。又如，torch.nn.ReLU表示一个ReLU激活函数，它的forward()方法调用了torch.nn.functional.relu()函数来实现ReLU操作。

虽然torch.nn.functional可以被直接使用，但是在实际开发中，使用torch.nn的模型定义更加方便，因为它提供了高层次的抽象，使得模型定义更加简单直观。

因此，该部分的内容其实已经在torch.nn中都讲过了，可以直接参考，这里就赘述了。