<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:18:46
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Visitor

访问者表示要对对象的元素执行的操作
结构。
它允许您在不改变类的情况下定义一个新的操作
它所作用的元素。
该模式具有行为目的并可应用
的对象。

###何时使用

一个对象结构包含许多具有不同接口的对象类，
你想在这些对象上执行依赖于它们的具体类的操作
*许多不同的和不相关的操作需要在对象结构中的对象上执行，
您希望避免使用这些操作“污染”它们的类
定义对象结构的类很少改变，但你经常想要
定义结构上的新操作