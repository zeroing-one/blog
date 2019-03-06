# 数据结构与算法
## 简介
数据结构是指数据存储的结构，算法是操作数据的一类方法。好比如图书馆的藏书，为了方便查找，会给树对应上编号，这些编号比做数据结构，那么根据编号如何找到对应的书籍比做算法。

数据结构是为算法服务的，算法要作用在特定的数据结构之上。所以说数据结构和算法是相辅相成的。

## 算法复杂度分析
数据结构和算法解决了代码运行的快和省的问题，即让代码运行的够快，并且让代码在运行的时候能更少占用内存。算法复杂度分析就是用一组数学公式来描述算法的执行时间和内存占用。

### 大O复杂度表示法
下面我们以一段代码来演示大O复杂度表示法是如何演算得到的
``` c
 int cal(int n) {
   int sum = 0;
   int i = 1;
   for (; i <= n; ++i) {
     sum = sum + i;
   }
   return sum;
 }
```