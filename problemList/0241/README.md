
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0241. 为运算表达式设计优先级](https://leetcode-cn.com/problems/different-ways-to-add-parentheses/)
## 题目描述
<p>给定一个含有数字和运算符的字符串，为表达式添加括号，改变其运算优先级以求出不同的结果。你需要给出所有可能的组合的结果。有效的运算符号包含 <code>+</code>,&nbsp;<code>-</code>&nbsp;以及&nbsp;<code>*</code>&nbsp;。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre><strong>输入:</strong> <code>&quot;2-1-1&quot;</code>
<strong>输出:</strong> <code>[0, 2]</code>
<strong>解释: </strong>
((2-1)-1) = 0 
(2-(1-1)) = 2</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>输入: </strong><code>&quot;2*3-4*5&quot;</code>
<strong>输出:</strong> <code>[-34, -14, -10, -10, 10]</code>
<strong>解释: 
</strong>(2*(3-(4*5))) = -34 
((2*3)-(4*5)) = -14 
((2*(3-4))*5) = -10 
(2*((3-4)*5)) = -10 
(((2*3)-4)*5) = 10</pre>

## 相关话题
- [分治算法](https://leetcode-cn.com/tag/divide-and-conquer)
## 相似题目
- [不同的二叉搜索树 II](../0095/README.md)
- [基本计算器](../0224/README.md)
- [给表达式添加运算符](../0282/README.md)
