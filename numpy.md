1.数组
-
属性
>```ndim``` 数组的维度<br></br>
>```shape``` 一个表示数组在各方向的长度的元组<br></br>
>```size``` shape元组内各个元素的乘积<br></br>
>```dtype``` numpy数据类型<br></br>
>```itemsize``` 数组内元素占用计算机内存的大小<br></br>
>```data``` 数组在内存中的地址<br></br>
生成
>```array(list)``` 生成一个numpy数组<br></br>
>```zeros(shape)/ones(shape)``` 生成一个元组其元素全为0/1<br></br>
>```empty(shape)``` 根据系统状态随机生成元素<br></br>
>```arange(start,end,step)``` 生成一个由start到end步长为step的数组<br></br>
>```rand(shape)``` 生成一个在区间[0,1)上均匀分布的数组<br></br>
>```zeros_like(array)/ones_like(array)``` 生成一个与array完全相同但元素全为0/1的数组<br></br>
>```linspace(start,end,len)``` 在区间[start,end)上生成均匀分布的一维数组，元素个数为len<br></br>
数据类型
>```astype(dtype)``` 转化数据类型<br></br>
基本操作
>```加减乘除```<br></br>
