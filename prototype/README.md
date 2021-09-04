<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:18:12
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Prototype

使用原型实例指定要创建的对象类型，然后创建
通过复制这个原型来创建新的对象。
模式有创造的目的和交易
对象关系更动态。
这种模式隐藏了复杂性
从客户端创建新实例。

###何时使用

*当在运行时指定要实例化的类时
*避免建立一个类似于产品类层次结构的工厂类层次结构
当一个类的实例只有几种不同的状态组合之一时