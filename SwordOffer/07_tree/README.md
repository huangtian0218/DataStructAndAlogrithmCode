### 07_tree

1. construct_binary_tree.c

   ```
   // 面试题7：重建二叉树
   // 题目：输入某二叉树的前序遍历和中序遍历的结果，请重建出该二叉树。假设输入的前序遍历和中序遍历的结果中都不含重复的数字。
   //例如输入前序遍历序列{1, 2, 4, 7, 3, 5, 6, 8}和中序遍历序列{4, 7, 2, 1, 5, 3, 8, 6}，则重建出二叉树并输出它的头结点。
   ```

2. static_array_binary_tree.c

   ```
   // 题目：静态数组实现二叉搜索树，能实现节点的插入，搜索，前序遍历
   ```

3. link_binary_search_tree.c

   ```
   // 题目： 通过链式 构建二叉搜索树
   // C 和指针上面的内容
   ```

4. next_binary_tree_node.c

   ```
   // 面试题8：二叉树的下一个结点
   // 题目：给定一棵二叉树和其中的一个结点，如何找出中序遍历顺序的下一个结点？
   // 树中的结点除了有两个分别指向左右子结点的指针以外，还有一个指向父结点的指针。
   ```

5. Substructure_inTree.c

   ```
   // 面试题26：树的子结构
   // 题目：输入两棵二叉树A和B，判断B是不是A的子结构。
   ```

6. mirror_recursively_binatyTree.c

   ```
   // 面试题27：二叉树的镜像
   // 题目：请完成一个函数，输入一个二叉树，该函数输出它的镜像。
   ```

7. is_Symmetrical.c

   ```
   // 面试题28：对称的二叉树
   // 题目：请实现一个函数，用来判断一棵二叉树是不是对称的。如果一棵二叉树和它的镜像一样，那么它是对称的。
   // 不是二叉搜索树
   ```

8. verify_sequenceOfBST.c

   ```
   // 面试题33：二叉搜索树的后序遍历序列
   // 题目：输入一个整数数组，判断该数组是不是某二叉搜索树的后序遍历的结果。如果是则返回true，否则返回false。假设输入的数组的任意两个数字都互不相同。
   // 题目扩展：思路一：判断一棵树是不是二叉树？（1）先得到它的后序遍历；（2）递归后续便利是否满足；
       // 思路二： 直接递归检查，左边不为空的时候，小于其父节点
   ```

 9. kNode_BinTree.c

   ```
   // 面试题54：二叉搜索树的第k个结点
    // 题目：给定一棵二叉搜索树，请找出其中的第k大的结点。
   ```

  10. depth_tree.c

   ```
   // 面试题55（一）：二叉树的深度
    // 题目：输入一棵二叉树的根结点，求该树的深度。从根结点到叶结点依次经过的
    // 结点（含根、叶结点）形成树的一条路径，最长路径的长度为树的深度。
   ```    

11. kNode_BinTree.c

   ```
   // 面试题54 (一)：二叉搜索树的第k个结点
    // 题目：给定一棵二叉搜索树，请找出其中的第k大的结点。
   ```

12. balance_tree.c

   ```
  // 面试题55（二）：平衡二叉树
    // 题目：输入一棵二叉树的根结点，判断该树是不是平衡二叉树。如果某二叉树中
    // 任意结点的左右子树的深度相差不超过1，那么它就是一棵平衡二叉树。
   ```