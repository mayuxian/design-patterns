
# 建造者模式

场景:
1. 建造者分别建造产品部件,组合起来就是一个完整产品
2. 每个建造建造一个产品,组合起来是一个大的工程项目或系统
两种关系一样,只是对象实体有些许差别

设计模式方法论:  

1. 分析事物中的角色:
   指挥者,建造者,产品
   

2. 分析各角色的行为(即具备什么属性,方法)
   指挥者:指挥多个建造者生产一个产品? 每次只指挥一个建造者生产一个产品? 若建造者生产必须按照顺序, 则需要使用职责链模式
   建造者:每个建造者的行为都不一致. (父元素不关心,则统一构建行为.若需要父元素调度,则建造者行为不一致可供组合)

   
3. 分析角色间的关系[关联,依赖,继承(泛化),实现,组合,聚合]
