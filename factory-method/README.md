<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:47
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Factory Method

定义用于创建对象的接口，但让子类决定实例化哪个类。
工厂方法允许类延迟实例化到子类。
该模式具有创建目的
并应用于通过继承处理关系的类。
他们是static-fixed
在编译时间。
与抽象工厂相比，工厂方法包含只产生一个方法的方法
类型的产品。

###何时使用

一个类不能预知它必须创建的对象的类
一个类希望它的子类指定它创建的对象
*类将责任委托给几个helper子类中的一个，而你想要本地化哪个helper子类是委托的知识