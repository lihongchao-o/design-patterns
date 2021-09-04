<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:18:42
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Template Method

模板方法在操作中定义算法的框架，延迟一些操作
步骤子类。
它允许子类重新定义算法的某些步骤
而不改变算法的结构。
这种模式具有行为目的
适用于类。

###何时使用

*一次实现算法的不变部分，并将其留给子类来实现可以变化的行为
当子类中的公共行为应该被分解和本地化在一个公共类中，以避免代码重复
*来控制子类扩展