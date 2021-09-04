<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:58
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Iterator

迭代器模式具有行为目的并适用于对象。
该模式提供了
一种顺序访问聚合对象的元素而不公开的方法
它的底层表示。

###何时使用

*访问聚合对象的内容而不暴露其内部表示
*支持聚合对象的多次遍历
*为遍历不同的聚合结构提供统一的界面
(支持多态迭代)