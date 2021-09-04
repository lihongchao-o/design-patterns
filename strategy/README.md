<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:18:38
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Strategy

Strategy定义了一组算法，封装了每一种算法，并使之生效
可互换的。
它允许算法独立于使用它的客户端而变化。
该模式具有行为目的并适用于对象。

###何时使用

许多相关的类只在行为上有所不同
你需要不同的算法变体
一个算法使用客户不应该知道的数据