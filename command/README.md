<!--
 * @Author: lihongchao
 * @Date: 2021-08-19 16:26:34
 * @LastEditTime: 2021-08-21 21:17:31
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \design-patterns-cpp-master\abstract-factory\README.md
-->
# #Command

命令模式将请求封装为对象，从而允许参数化
客户端有不同的请求，排队或日志请求，并支持可撤销
操作。
该模式具有行为目的，并处理对象之间的关系。

###何时使用

想要通过执行的动作参数化对象
*希望在不同的时间指定、排队和执行请求
*支持撤销
*支持日志更改，以便在系统崩溃时可以重新应用
围绕建立在原语操作上的高级操作构建一个系统