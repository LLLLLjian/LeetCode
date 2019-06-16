
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0341. 扁平化嵌套列表迭代器](https://leetcode-cn.com/problems/flatten-nested-list-iterator/)
## 题目描述
<p>给定一个嵌套的整型列表。设计一个迭代器，使其能够遍历这个整型列表中的所有整数。</p>

<p>列表中的项或者为一个整数，或者是另一个列表。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入: </strong>[[1,1],2,[1,1]]
<strong>输出: </strong>[1,1,2,1,1]
<strong>解释: </strong>通过重复调用&nbsp;<em>next </em>直到&nbsp;<em>hasNex</em>t 返回false，<em>next&nbsp;</em>返回的元素的顺序应该是: <code>[1,1,2,1,1]</code>。</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入: </strong>[1,[4,[6]]]
<strong>输出: </strong>[1,4,6]
<strong>解释: </strong>通过重复调用&nbsp;<em>next&nbsp;</em>直到&nbsp;<em>hasNex</em>t 返回false，<em>next&nbsp;</em>返回的元素的顺序应该是: <code>[1,4,6]</code>。
</pre>

## 相关话题
- [栈](https://leetcode-cn.com/tag/stack)
- [设计](https://leetcode-cn.com/tag/design)
## 相似题目
- [展开二维向量](../0251/README.md)
- [锯齿迭代器](../0281/README.md)
- [迷你语法分析器](../0385/README.md)
- [数组嵌套](../0565/README.md)
