# Head First设计模式 - 学习笔记

## OO基础

-   抽象
-   封装
-   多态
-   继承

## OO原则

-   封装变化 - 找出应用中可能需要变化之处，把它们独立出来，不要和那些不需要变化的代码混在一起。
-   针对接口编程,不针对实现编程。
-   组合/聚合复用原则 - 多用组合,少用继承。
-   为交互对象之间的松耦合设计而努力。
-   开闭原则 - 类应该对扩展开放,对修改关闭。
-   依赖倒置原则 - 要依抽象,不要依赖具体类。
-   最少知识原则 - 只和你的密友谈话。
-   好莱坞原则 - 别调用(打电话给)我们，我们会调用(打电话给)你。
-   单一责任 - 一个类应该只有一个引起变化的原因。

## OO模式

### 创建型模式(Creational Pattern)

-   [简单工厂模式(Simple Factory Pattern)](./source/_chapter/oo_patterns/04_simple_factory_pattern.md)
-   [工厂方法模式(Factory Method Pattern)](./source/_chapter/oo_patterns/05_factory_method_pattern.md)
-   [抽象工厂模式(Abstract Factory Pattern)](./source/_chapter/oo_patterns/06_abstract_factory_pattern.md)
-   [建造者模式(Builder Pattern)](./source/_chapter/oo_patterns/07_builder_pattern.md)
-   [单件模式(Singleton Pattern)](./source/_chapter/oo_patterns/08_singleton_pattern.md)
-   [原型模式(Prototype Pattern)](./source/_chapter/oo_patterns/23_prototype_pattern.md)

### 结构型模式(Structural Pattern)

-   [装饰者模式(Decorator Pattern)](./source/_chapter/oo_patterns/03_decorator_pattern.md)
-   [适配器模式(Adapter Pattern)](./source/_chapter/oo_patterns/10_adapter_pattern.md)
-   [外观模式(Facade Pattern)](./source/_chapter/oo_patterns/11_facade_pattern.md)
-   [组合模式(Composite Pattern)](./source/_chapter/oo_patterns/14_composite_pattern.md)
-   [代理模式(Proxy Pattern)](./source/_chapter/oo_patterns/16_proxy_pattern.md)
-   [桥接模式(Bridge Pattern)](./source/_chapter/oo_patterns/17_bridge_pattern.md)
-   [享元模式(Flyweight Pattern)](./source/_chapter/oo_patterns/19_flyweight_pattern.md)

### 行为型模式(Behavioral Pattern)

-   [策略模式(Strategy Pattern)](./source/_chapter/oo_patterns/01_strategy_pattern.md)
-   [观察者模式(Observer Pattern)](./source/_chapter/oo_patterns/02_observer_pattern.md)
-   [命令模式(Command Pattern)](./source/_chapter/oo_patterns/09_command_pattern.md)
-   [模板方法模式(Template Method Pattern)](./source/_chapter/oo_patterns/12_template_method_pattern.md)
-   [迭代器模式(Iterator Pattern)](./source/_chapter/oo_patterns/13_iterator_pattern.md)
-   [状态模式(State Pattern)](./source/_chapter/oo_patterns/15_state_pattern.md)
-   [责任链模式(Chain of Responsibility Pattern)](./source/_chapter/oo_patterns/18_chain_of_responsibility_pattern.md)
-   [解释器模式(Interpreter Pattern)](./source/_chapter/oo_patterns/20_interpreter_pattern.md)
-   [中介者模式(Mediator Pattern)](./source/_chapter/oo_patterns/21_mediator_pattern.md)
-   [备忘录模式(Memento Pattern)](./source/_chapter/oo_patterns/22_memento_pattern.md)
-   [访问者模式(Visitor Pattern)](./source/_chapter/oo_patterns/24_visitor_pattern.md)

## 谨记

-   为实际需要的扩展使用模式。不要只是为了假象的需要而使用模式。
-   简单才是王道。如果你不用模式就能够设计出更简单的方案，那就去干吧。
-   模式是工具而不是规则，需要被适当地调整以符合你的需求。
