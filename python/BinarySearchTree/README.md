### BinarySearchTree
#### 特点
+ 动态数据结构
+ 每个节点的值都大于其左子树的所有节点的值
+ 每个节点的值都小于其右子树的所有节点的值
+ 每一颗子树也是二分搜索树
+ 存储的元素必须有可比较性, Java中的话就要求二分搜索树保存的数据类型要实现Comparable接口, 或者使用额外的比较器实现
+ 一般二分搜索树不包含重复元素, 当然也可以定义包含重复元素的二分搜索树

#### 时间复杂度
+ 因为二分查找每次排除掉一半的不适合值，所以对于n个元素的情况为:
    + O(logN)
    
#### 前中后序遍历
`想要理解算法 必要 画出入栈出栈的顺序`
+ 1、使用递归
+ 2、使用辅助栈（list即可）
