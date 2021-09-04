<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:16:34
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Singleton

确保一个类只有一个实例，并提供对它的全局访问点。
模式具有创建目的，并处理动态的对象关系。

###何时使用

必须有一个类的实例，并且它必须能被客户端从一个众所周知的访问点访问
*当唯一的实例应该通过子类化来扩展，并且客户端应该能够使用扩展的实例而不修改他们的代码