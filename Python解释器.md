1. Python3和Python2中print的区别：
Python2中使用print，而Python3中使用print()。<br>
print 可以同时输出多个表达式，中间用逗号隔开：<br>
>>> i = 123<br>
>>> print('The value of i is', i)<br>
The value of i is 123<br>
用一个逗号结尾就可以禁止输出换行:<br>
>>> a, b = 0, 1<br>
>>> while b < 100:<br>
...  print(b, end= ',')<br>
...  a, b = b, a+b<br>
... <br>
1,1,2,3,5,8,13,21,34,55,89,<br>
2. 执行Python脚本，在脚本文件中添加一行指令，制定文件和模式:<br>
`#! /usr/bin/env python`<br>
3. 源程序编码：<br>
Python的源文件可以通过编码使用ASCII之外的字符集。通常做法是在#!行后面用一个特殊的注释行来定义字符集。<br>
`# -*- coding: iso-8859-1 -*-`<br>
4. 交互式环境的启动文件**（不太明白）**<br>
