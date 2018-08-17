1.python的内建函数
-
>```print()``` 输出值<br></br>
>```len(x)``` 返回字符串/数组/列表/集合/字典的长度<br></br>
>```abs(x)``` 返回数字的绝对值<br></br>
>```divmod(a,b)``` 返回(a//b,a%b)<br></br>
>```input()``` 输入值<br></br>
>```open(path,mod='r')``` 打开一个文件<br></br>
>```str()/int()/float()/long()/list()/dict()/set()``` 转化数据类型<br></br>
>```ord()/chr()``` 把字符转化为ASCII码/把ASCII转化为字符<br></br>
>```dir()``` 查看所有方法<br></br>
>```next（）``` 生成器生成下一个值<br></br>
内建函数太多了就先写这么几个有时间再补充<br></br>

2.生成器
-
直接写例子吧<br></br>
>```a = (i for i in range(10))<br></br>```
```
def func():
    for i in range(10):
        yield i
'''

方法
1.```close()```关闭生成器 

3.装饰器
-
在不修改原函数的情况下增加函数的功能<br></br>
例子:
```
import time
def timer(func):
    def new_func(*args,**kws):
        old = time.clock()
        func(*args,**kws)
        print(time.clock()-old)
@timer
def a(n):
c = 1
    for i in range(n):
        c+=1
```
