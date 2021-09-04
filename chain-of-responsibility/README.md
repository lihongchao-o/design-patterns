<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:26
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
##Chain of Responsibility

责任链模式避免了请求发送方与接收方的耦合
通过给多个对象处理请求的机会。
连锁模式
接收对象并沿着链传递请求，直到有对象处理它。
它具有行为目的并处理对象之间的关系。

###何时使用

多个对象可以处理一个请求，处理程序应该自动确定
您希望向多个对象之一发出请求，而不明确指定接收者
可以处理请求的对象集合应该动态指定