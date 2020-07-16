# 哈希表
##  **定义**：根据关键码值 key value 而直接访问的数据结构， 通过把关键码值映射到表中的一个位置来访问记录，以加快查找速度。这个映射函数叫做散列函数 Hash Function , 存放记录的数组叫做哈希表。

## 哈希碰撞 Hash collisions : 多个元素映射之后的值相同。

## 在实际工程中， 经常使用的不是hash map本身， 而是抽象出来的Map和set.  

### std::set
1. storing unique elements
2. sorted order
3. great O(logn) insertion and look-up

### std::map
用key和value配对来存放查找


### [What is the best way to use a HashMap in C++?](https://stackoverflow.com/questions/3578083/what-is-the-best-way-to-use-a-hashmap-in-c)
The standard library includes the ordered and the unordered map (std::map and std::unordered_map) containers. In an ordered map the elements are sorted by the key, insert and access is in O(log n). Usually the standard library internally uses red black trees for ordered maps. But this is just an implementation detail. In an unordered map insert and access is in O(1). It is just another name for a hashtable.

# 参考资料
## std::map 和 std::set
[C++ Standard Library: Associative Containers](https://app.pluralsight.com/library/courses/c-plus-plus-standard-library-associative-containers/table-of-contents)

# 二叉搜索树 binary search tree
同义词: 二叉搜索树/二叉排序树/有序二叉树/排序二叉树
性质：
1. 左子树上所有结点的均值小于它的根节点的值;
2. 右子树上所有结点的均值大于它的根节点的值;

常见操作:
1. 查询 O(logn) 
2. 插入新结点  O(logn)
3. 删除 O(logn)






