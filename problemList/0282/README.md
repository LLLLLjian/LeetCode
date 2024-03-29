
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0282. 给表达式添加运算符](https://leetcode-cn.com/problems/expression-add-operators/)
## 题目描述
<p>给定一个仅包含数字&nbsp;<code>0-9</code>&nbsp;的字符串和一个目标值，在数字之间添加<strong>二元</strong>运算符（不是一元）<code>+</code>、<code>-</code>&nbsp;或&nbsp;<code>*</code>&nbsp;，返回所有能够得到目标值的表达式。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> <code><em>num</em> = </code>&quot;123&quot;, <em>target</em> = 6
<strong>输出: </strong>[&quot;1+2+3&quot;, &quot;1*2*3&quot;] 
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>输入:</strong> <code><em>num</em> = </code>&quot;232&quot;, <em>target</em> = 8
<strong>输出: </strong>[&quot;2*3+2&quot;, &quot;2+3*2&quot;]</pre>

<p><strong>示例 3:</strong></p>

<pre><strong>输入:</strong> <code><em>num</em> = </code>&quot;105&quot;, <em>target</em> = 5
<strong>输出: </strong>[&quot;1*0+5&quot;,&quot;10-5&quot;]</pre>

<p><strong>示例&nbsp;4:</strong></p>

<pre><strong>输入:</strong> <code><em>num</em> = </code>&quot;00&quot;, <em>target</em> = 0
<strong>输出: </strong>[&quot;0+0&quot;, &quot;0-0&quot;, &quot;0*0&quot;]
</pre>

<p><strong>示例 5:</strong></p>

<pre><strong>输入:</strong> <code><em>num</em> = </code>&quot;3456237490&quot;, <em>target</em> = 9191
<strong>输出: </strong>[]
</pre>

## 相关话题
- [分治算法](https://leetcode-cn.com/tag/divide-and-conquer)
## 相似题目
- [逆波兰表达式求值](../0150/README.md)
- [基本计算器](../0224/README.md)
- [基本计算器 II](../0227/README.md)
- [为运算表达式设计优先级](../0241/README.md)
- [目标和](../0494/README.md)
