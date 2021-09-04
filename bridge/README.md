<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:14
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Bridge
将抽象与其实现解耦，这样两者就可以独立地变化。
桥模式具有结构化目的，适用于对象，因此它处理对象的组合。
###何时使用
你想要避免一个抽象和它的实现之间的永久绑定
抽象及其实现都应该通过子类化来扩展
抽象实现中的变化应该对客户端没有影响
*你想对客户完全隐藏一个抽象的实现