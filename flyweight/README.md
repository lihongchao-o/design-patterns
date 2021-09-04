<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:52
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Flyweight

Flyweight模式具有结构化目的，适用于对象并使用共享来支持
有效地处理大量细粒度对象。
这种模式可以用来减少
当您需要创建大量类似对象时的内存使用情况。

###何时使用

当一个类的一个实例可以用来提供许多“虚拟实例”时
当下列各项都正确时
应用程序使用大量的对象
*存储成本高是因为对象的绝对数量
*大多数对象状态都是外在的
*一旦外部状态被移除，许多组对象可能会被相对较少的共享对象所取代
应用程序不依赖于对象标识