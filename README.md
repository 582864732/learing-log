这将记录我所有学习的情况
<br>尽管在我写下这篇 readme 时 我已经学了一两个月了</br>
那就先来复习吧。
<br>第一行代码：</br>
```
print('hello world')
```

一、字符串
-
1.用`'(")` 或 `'''(""")`括起来的字段
<br></br>

2.字符串中的转义字符
>\a 响铃
<br></br>
>\n 换行
<br></br>
>\t 横向制表
<br></br>
>\v 纵向制表
<br></br>
>\b 退格

3.str()
>将各种数据类型转化为字符串

4.方法
>```split()```将语句拆分成列表
<br></br>
>```replace(a,b,[max])```将字符串中的所a替换为b，次数为max
<br></br>
>```upper/lower()```字母大/小写
<br></br>
>```title()```首字母大写
<br></br>
>```count(a)```a在字符串中出现的次数

二、数字
-
这好像没啥说的，想到再写

三、列表
-
1.下标从零开始数
<br></br>
2.方法
>```append()```在列表最后添加元素
<br></br>
>```insert(a,b)```在列表的第a索引中插入元素b
<br></br>
>```count(a)```元素a在列表中出现的次数
<br></br>
>```clear()```清空列表
<br></br>
>```copy()```复制
<br></br>
>```index(a,beg = 0,end = len(list))```
<br></br>
>>```beg```：开始索引
<br></br>
>>```end```：结束索引
<br></br>
>>元素a在列表中的索引
<br></br>
>```pop(index = -1)```弹出第index索引的值
<br></br>
>```remove(a)```弹出a（一个值）
<br></br>
>```reverse()```把列表倒过来
<br></br>
>```sort()```排序，不能对数字和字符串混合的列表

四、元组
-
1.不可修改
<br></br>
2.方法
>```count(a)```和```index(a)```和列表一样

五、字典
-
1.每一个键对应一个值
<br></br>
2.方法
>```items()```返回由（键，值）组成的列表
<br></br>
>```keys/values()```
