
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0783. 二叉搜索树结点最小距离](https://leetcode-cn.com/problems/minimum-distance-between-bst-nodes/)
## 题目描述
<p>给定一个二叉搜索树的根结点&nbsp;<code>root</code>, 返回树中任意两节点的差的最小值。</p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入:</strong> root = [4,2,6,1,3,null,null]
<strong>输出:</strong> 1
<strong>解释:</strong>
注意，root是树结点对象(TreeNode object)，而不是数组。

给定的树 [4,2,6,1,3,null,null] 可表示为下图:

          4
        /   \
      2      6
     / \    
    1   3  

最小的差值是 1, 它是节点1和节点2的差值, 也是节点3和节点2的差值。</pre>

<p><strong>注意：</strong></p>

<ol>
	<li>二叉树的大小范围在 <code>2</code> 到&nbsp;<code>100</code>。</li>
	<li>二叉树总是有效的，每个节点的值都是整数，且不重复。</li>
</ol>

## 相关话题
- [树](https://leetcode-cn.com/tag/tree)
- [递归](https://leetcode-cn.com/tag/recursion)
## 相似题目
- [二叉树的中序遍历](../0094/README.md)
