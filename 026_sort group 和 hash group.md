##  sort group 和 hash group

sort group 和 hash group 是数据库中的两种分组算法：

- sort group：前者需要对数据进行全局排序，然后遍历每一条记录时，若与上一条记录不同，就划分为一个新组。
- hash group：后者则是直接对分组列计算 hash 值，相同的值会被分为一组