# 第一章 序论

![知识结构](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter01/images/知识结构.png)

## 基本概念

![数据结构绪论](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter01/images/数据结构绪论.png)

### 数据结构的三要素：

逻辑结构，物理结构，数据运算

### 数据结构的逻辑结构：

    集合，线性结构，树形结构，图形结构

1. 集合：各个元素同属一个结构，没有其他关系
2. 线性结构：数据元素之间是一对一的关系。 除了第一个元素,所有元素都有唯一**前驱**，除了最后一个元素,所有元素都有唯一**后继**
![线性结构](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter01/images/线性结构.png)
3. 树形结构：数据元素之间是一对多的关系。
![树形结构](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter01/images/树形结构.png)
4. 图结构：数据元素之间是多对多的关系
![图结构](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter01/images/图结构.png)

### 数据结构的物理结构

    顺序存储，链式存储，索引存储，散列存储

1. 顺序存储：把逻辑上相邻的元素存储在物理位置上也相邻的存储单元当中，**元素之间的关系**由**存储单元的邻接关系**来体现。一片连续的存储空间！

2. 链式存储：逻辑上相邻的元素在物理位置上可以不相邻，借助指示元素存储地址的指针来表示元素之间的逻辑关系。“指针指向下一个元素的存储地址”

3. 索引存储：在存储信息的同时，还建立一张**索引表**，索引表中的每个项称为索引项，索引项的一般形式是 关键字，地址

4. 散列存储：根据元素的关键字直接计算出该元素的存储地址，又称哈希存储。

后三种也可统称为非顺序存储。数据的存储结构会影响存储空间分配的方便程度。

### 数据的元素

如：队列结构：队头元素出队、新元素入队、输出队列长度......

### 数据类型，抽象数据类型

**数据类型：** 一个值的集合和定义在这个集合上的一组操作的总称

1. 原子类型：其值不可再分的数据类型bool,int等
2. 结构类型：其值还可以再分解成若干成分的数据类型

**抽象数据类型ADT：** abstract data type，抽象数据组织以及**与之相关的操作**。定义一个ADT后，就是定义了数据的逻辑结构、数据的运算。即**定义了一个数据结构**。

### 总结

在探讨一种数据结构时:
1. 定义逻辑结构(数据元素之间的关系)
2. 定义数据的运算(针对现实需求应该对这种逻辑结构进行什么样的**运算**)
3. 确定某种存储结构,实现数据结构,并实现一些对数据结构的基本运算
   
## 算法的基本概念

### 什么是算法

程序 = 数据结构 + 算法

算法来解决某些实际问题

### 算法的特性

**有穷性** 一个算法必须在执行有穷步后结束，算法必须是有穷的，程序可以是无穷的

**确定性** 必须有确切的含义，相同输入必须只能得出相同的输出

**可行性** 算法中描述的操作都可以通过已经实现的基本运算执行有限次来实现。

**输入和输出**

### 什么是“好”算法

正确性，可读性，健壮性，高效率，低存储量的需求

## 算法效率的度量

时间复杂度，空间复杂度


### **时间复杂度** 

时间开销T与问题规模n的关系T(n)。

1. 只考虑阶数高的部分，
2. 加法规则：多项相加，只保留最高阶的项，系数变为1
3. 乘法规则：多项相乘，都保留
4. 只需要考虑最深层循环的循环次数与n的关系。

![算法时间复杂度](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter01/images/算法时间复杂度.png)

三种时间复杂度：

**最坏时间复杂度:** 最坏情况下算法的时间复杂度

**平均时间复杂度:** 所有输入示例等概率出现的情况下,算法的期望运行时间

最好时间复杂度: 最好情况下算法的时间复杂度

### 空间复杂度：

程序运行时的内存需求：S(n) = O(1)




![](https://github.com/nilshao/cpp-notebook/raw/master/data_structure/chapter01/images/.png)