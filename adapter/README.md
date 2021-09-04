<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:09
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Adapter

将类的接口转换为客户端期望的另一个接口。
适配器让类可以一起工作，否则无法
不兼容的接口,即。
允许使用一个不兼容的客户端
接口由适配器执行转换。
适配器具有结构用途
并且可以应用于类和对象。
类适配器使用多个
继承以使一个接口适应另一个接口，并且对象适配器使用对象
组合类和不同的接口。

###何时使用

你想使用一个已经存在的类，但它的接口与你需要的不匹配
*你想要创建一个可重用的类，它与那些不一定具有兼容接口的类协作
