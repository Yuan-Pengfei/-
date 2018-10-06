快速排序就是将待排数组的第一个数作为索引，第一次排序将比索引小的数放到索引左边，将比索引大的数放到索引右边，然后将左右两边分别进行递归操作直到待排数组元素个数为1。

最好情况时间复杂度O(nlogn)，最坏情况为O(n^2)，当数组元素基本有序的时候会降低快排效率，此时可以使用random()函数随机选择索引进行快排操作；此外当数组中重复元素较多时会降低快排效率，此时可以使用三轴快排方法，将值一样的元素放到一起作为一个区间。
