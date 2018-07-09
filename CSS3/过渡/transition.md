# `transition`属性

## `transition-property`属性

- 检索或设置对象中的参与过渡的属性

语法：`transition-property:none|all|property`

参数说明：

- `none` 没有属性该表
- `all` 所有属性都会改变，默认值
- `property` 元素属性名称

## `transition-duration`属性

- 检索或设置对象过渡的持续时间

语法：`transtition-duration:time;`

参数说明：

- 规定完成过渡效果需要花费的时间（以秒或毫秒计算）
- 默认值是0

## `transition-timing-function`属性

- 检索或设置对象中过渡的动画类型

语法：`transition-timing-function:ease|linear|ease-in|ease-out|ease-in-out|step-start|steps(<integer>[,[start|end]]?)|cubic-bezier(<number>,<number>,<number>,<number>);`

## `transition-delay`属性

- 检索或设置对象延迟过渡的时间

语法：`transition-delay:time;`

参数说明：

- 指定秒或毫秒之前要等待的切换效果开始
- 默认值0