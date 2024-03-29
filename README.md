简单工厂模式

所有的东西都在一个工厂里创建，随着新的需求出现，客户端的依赖会越来越臃肿，从代码的角度不易于扩展。

![ad](https://github.com/memoryEffect/gupao-work-2019-3-6/blob/master/src/uml/simpleFactory.png)

工厂方法模式

根据单一原则我们将职能进行拆分，专人干专事，对工厂本身进行抽象，这种方法易拓展，符合开闭原则，只是跟据产品种类的增加，会有越来越来的类。

![as](https://github.com/memoryEffect/gupao-work-2019-3-6/blob/master/src/uml/FactoryMethod.png)

抽象工厂模式

定义产品族非常完美的描述这层关系，但是我们继续扩展产品等级，那我们从代码到抽象工厂，到具体工厂都要调整，显然不符合开闭原则。

![ad](https://github.com/memoryEffect/gupao-work-2019-3-6/blob/master/src/uml/abstractFactory.png)

产品族
![ad](https://github.com/memoryEffect/gupao-work-2019-3-6/blob/master/src/uml/product.png)
