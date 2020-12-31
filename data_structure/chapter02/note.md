# 第二章 线性表

## 线性表定义

线性表是具有相同数据类型的n(n>=0)个数据元素的有限序列,其中n为表长,当n=0时线性表是一个空表。若用L命名线性表,则其一般表示为：

L=(a1,a2,a3...ai,ai+1,...an)

**概念** 每个数据元素所占空间一样大。位序i；表头元素；表位元素；前驱；后驱

## 线性表基本操作

* InitList(&L):**初始化**操作。构造一个空的线性表L,分配内存空间。
* DestroyList(&):**销毁**操作。销毁线性表,并释放线性表L所占用的内存空间。
* ListInsert(&L,i,e):**插入**操作。在表L中的第i个位置上插入指定元素e
* ListDelete(&L,i,&e):**删除**操作。删除表L中第i个位置的元素,并用e返回删除元素的值。
* LocateElem(L,e):**按值査找**操作。在表L中査找具有给定关键字值的元素。
* GetElem(L,i):**按位查找**操作。获取表L中第i个位置的元素的值
  
其他常用操作:
* Length(L):**求表长**。返回线性表L的长度,即L中数据元素的个数。
* Prigtlist(L):**输出**操作。按前后顺序输出线性表L的所有元素值。
* Empty(L):**判空**操作。若L为空表,则返回tue,否则返回false。


## 顺序表
![线性表存储物理结构](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter02/images/线性表存储物理结构.png)











![](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter02/images/.png)