# gameInBinaryTree
外星星进攻地球的一个小游戏， javascript实现二叉树的创建，遍历，添加，查找最大值最小值和指定值的寻找及删除功能——递归的多次运用

 树是计算机科学中经常用到的一种数据结构。树是一种非线性的数据结构，以分成的方式存储数据，树被用来存储具有层级关系的数据，比如文件系统的文件，树还被用来存储有序列表。我们要研究的是二叉树，在二叉树上查找元素非常快，为二叉树添加元素或者删除元素，也是非常快的。我们现在最主要的是要来学习二叉树，二叉树是一种特殊的树，它的特征是 子节点个数不超过2个。如下图就是二叉树的基本结构示意图如下：

左子节点的值 < 父节点的值 <= 右节点的值
  二叉树是由节点组成的，所以我们需要定义一个对象node，可以保存数据，也可以保存其他节点的链接(left 和 right)，show()方法用来显示保存在节点中的数据。
下面对于顺序二叉树的的创建，遍历，添加，查找最大值最小值和指定值的寻找及删除功能，提供源码，仅供参考
