外观模式

开家庭party,我们需要打开音响，准备食物，调按灯光等。

我们可以新建一个类，有一个类似与turnOn的的动作，他负责将这些事情执行一遍，我们只需要执行turnOn操作。这就是外观模式。

将一些操作统一起来，但是并不封装，这样，上层既可以使用这些包装的方法，也可以调用更底层的方法实现高级功能。