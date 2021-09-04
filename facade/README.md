<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:42
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
##Facade
为子系统中的一组接口提供统一的接口。
外观
定义使子系统更易于使用的高级接口。
该模式具有结构化目的，并适用于对象。

###何时使用

你想为一个复杂的子系统提供一个简单的接口
客户端和抽象的实现类之间有很多依赖关系
*你想要对子系统分层，使用facade来定义每个子系统级别的入口点