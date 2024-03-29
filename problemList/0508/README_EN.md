
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0508. Most Frequent Subtree Sum](https://leetcode-cn.com/problems/most-frequent-subtree-sum/)
## Description
<p>
Given the root of a tree, you are asked to find the most frequent subtree sum. The subtree sum of a node is defined as the sum of all the node values formed by the subtree rooted at that node (including the node itself). So what is the most frequent subtree sum value? If there is a tie, return all the values with the highest frequency in any order.
</p>

<p><b>Examples 1</b><br>
Input:
<pre>
  5
 /  \
2   -3
</pre>
return [2, -3, 4], since all the values happen only once, return all of them in any order.
</p>

<p><b>Examples 2</b><br>
Input:
<pre>
  5
 /  \
2   -5
</pre>
return [2], since 2 happens twice, however -5 only occur once.
</p>

<p><b>Note:</b>
You may assume the sum of values in any subtree is in the range of 32-bit signed integer.
</p>
## Related Topics
- [Tree](https://leetcode-cn.com/tag/tree)
- [Hash Table](https://leetcode-cn.com/tag/hash-table)
## Similar Questions
- [Subtree of Another Tree](../0572/README_EN.md)
