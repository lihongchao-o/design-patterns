<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:18:01
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Mediator

中介模式具有行为目的并应用于对象。
该模式定义了一个对象，该对象封装了一组对象如何交互。
它通过保持对象不引用每个对象来促进松耦合
其他显式的，它允许您独立地改变它们的交互。

###何时使用

一组对象以定义明确但复杂的方式进行交流
*重用一个对象是困难的，因为它涉及许多其他对象并与之通信
一个分布在几个类之间的行为应该是可定制的，而不需要大量的子类化