









对于查找，添加等操作很快，仅需一次寻址即可；

**如果定位到的数组包含链表，对于添加操作，其时间复杂度依然为O(1)，因为最新的Entry会插入链表头部，急需要简单改变引用链即可**。

而对于查找操作来讲，此时就需要遍历链表，然后通过key对象的equals方法逐一比对查找。