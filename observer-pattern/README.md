# 观察者设计模式

## 说明:与发布订阅模式原理本质相似,可以理解成同一个.
## 观察者模式和发布订阅模式,区别在于:
1. 发布订阅模式中存在第三方作为发布,订阅的服务商(符合迪米特原则),而观察者模式是直接操作观察实体
2. 发布订阅模式对消息的传递和接收都是由外部订阅对象接收和处理,而观察者模式是观察者可能会组装消息再给观察实体
