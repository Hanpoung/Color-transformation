# ColorTransformation
实现对HTML元素的自定义的颜色
页面变幻背景

[页面展示](https://hanpoung.github.io/ColorTransformation/colofulTest.html)

输入参数包括:

1.element
接受一个变色的元素，
数据类型： {  HTMLElement  } 

2.array
用于存放每个时刻的颜色的数组,变色依赖的关键颜色.按rgb传入，如:[[255,255,0],[0,220,220],[220,0,220]]
数据类型： {  Array  } 

3.msec
完成一个变色阶段的时间（毫秒）,即从array[i]变色到array[i+1]的时间。
数据类型： {Number}

4.attr 
其余属性。如果要变色的是css的其他属性，传入属性的名字，如'color'
数据类型：{string}
