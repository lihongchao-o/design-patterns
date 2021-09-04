<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:16:34
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Builder

构建器模式具有创建目的，分离了复杂对象的构造
从它的表示法，使相同的构造过程可以创建不同的
表示。
它是对象模式，即。
关系可以在运行时更改
而且更有活力。
常用于构造复合结构但构造
对象需要比使用Factory更多的客户端领域知识。

###何时使用

*创建对象的算法应该独立于部件和它们的组装方式
*构造过程必须允许被构造对象的不同表示