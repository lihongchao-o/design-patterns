<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:18:05
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Memento

在不违反封装的情况下，捕获并外部化对象的内部
状态，以便稍后可以将对象恢复到此状态。
这种模式具有行为性
目的和适用于对象。

###何时使用

*必须保存对象状态的快照，以便稍后可以恢复到该状态
*一个直接获取状态的接口会暴露实现细节并破坏对象的封装