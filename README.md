# iOS-DesignPatterns

### MementoPattern

> 备忘录设计模式的完整实现

![demo.gif](http://images2015.cnblogs.com/blog/607542/201509/607542-20150911211147387-467686442.gif)

* 在不破坏封装的情况下，捕获一个对象的内部状态，并在该对象之外保存这个状态，这样以后就可以将该对象恢复到原先保存的状态
* 本人已经将创建状态与恢复状态的逻辑抽象成了协议，并配合备忘录中心一起使用


### SingletonPattern

> [严格单例模式的完整实现](http://www.cnblogs.com/YouXianMing/p/4709209.html)

![demo.png](http://images0.cnblogs.com/blog2015/607542/201508/062107342681020.png)

* 单例模式人人用过,严格的单例模式很少有人用过
* 严格的单例模式指的是无法通过常规的 alloc init 方法来生成对象,派生出来的子类也不能产生出对象,而只能通过单例的方法获取到对象


### FlyweightPattern

> 享元设计模式的完整实现

![demo.png](http://images2015.cnblogs.com/blog/607542/201510/607542-20151027172216122-262635664.png)

* 享元模式使用共享物件，用来尽可能减少内存使用量以及分享资讯给尽可能多的相似物件；它适合用于只是因重复而导致使用无法令人接受的大量内存的大量物件。通常物件中的部分状态是可以分享。常见做法是把它们放在外部数据结构，当需要使用时再将它们传递给享元。


### ChainOfResponsibilityPattern

> 责任链设计模式的完整实现

![demo.png](http://images2015.cnblogs.com/blog/607542/201510/607542-20151027145216575-700989924.png)

* 在责任链模式里，很多对象由每一个对象对其下家的引用而连接起来形成一条链。请求在这个链上传递，直到链上的某一个对象决定处理此请求。发出这个请求的客户端并不知道链上的哪一个对象最终处理这个请求，这使得系统可以在不影响客户端的情况下动态地重新组织和分配责任。


### VisitorPattern

> 访问者设计模式的完整实现

![demo.png](http://images2015.cnblogs.com/blog/607542/201510/607542-20151027105704513-2073306262.png)

* 表示一个作用于某对象结构中的各元素的操作，它使你可以在不改变各元素类的前提下定义作用于这些元素的新操作。
