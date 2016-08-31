# validater

提供了jquery-validation之外的一种表单验证方法

* 使用angular原生$dirty/$ invalid属性和$parsers方法
* 支持实时校验
* angular自动维护表单的校验状态

主要指令包括：inputError/ validateAll

1.使用<ng-form>指令，必须有name attribute
2.设置被观察指令 <... ng-required="true" input-error></...>
3.设置触发按钮 <... validate-all></...>　验证成功后才会调用ngClick

![test](1.png)
