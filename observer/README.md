<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:18:09
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Observer

观察者定义了对象之间的一对多依赖关系，因此当一个对象
更改状态时，它的所有依赖项都会被通知并自动更新。
该模式
具有行为目的并适用于对象。

###何时使用

抽象有两个方面，一个依赖于另一个
*当一个对象的改变需要改变其他对象时，你不知道有多少对象需要改变
*当一个对象应该能够通知其他对象而不需要假设这些对象是谁时