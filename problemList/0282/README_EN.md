
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0282. Expression Add Operators](https://leetcode-cn.com/problems/expression-add-operators/)
## Description
<p>Given a string that contains only digits <code>0-9</code> and a target value, return all possibilities to add <b>binary</b> operators (not unary) <code>+</code>, <code>-</code>, or <code>*</code> between the digits so they evaluate to the target value.</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> <code><em>num</em> = </code>&quot;123&quot;, <em>target</em> = 6
<b>Output: </b>[&quot;1+2+3&quot;, &quot;1*2*3&quot;] 
</pre>

<p><b>Example 2:</b></p>

<pre>
<b>Input:</b> <code><em>num</em> = </code>&quot;232&quot;, <em>target</em> = 8
<b>Output: </b>[&quot;2*3+2&quot;, &quot;2+3*2&quot;]</pre>

<p><b>Example 3:</b></p>

<pre>
<b>Input:</b> <code><em>num</em> = </code>&quot;105&quot;, <em>target</em> = 5
<b>Output: </b>[&quot;1*0+5&quot;,&quot;10-5&quot;]</pre>

<p><b>Example 4:</b></p>

<pre>
<b>Input:</b> <code><em>num</em> = </code>&quot;00&quot;, <em>target</em> = 0
<b>Output: </b>[&quot;0+0&quot;, &quot;0-0&quot;, &quot;0*0&quot;]
</pre>

<p><b>Example 5:</b></p>

<pre>
<b>Input:</b> <code><em>num</em> = </code>&quot;3456237490&quot;, <em>target</em> = 9191
<b>Output: </b>[]
</pre>

## Related Topics
- [Divide and Conquer](https://leetcode-cn.com/tag/divide-and-conquer)
## Similar Questions
- [Evaluate Reverse Polish Notation](../0150/README_EN.md)
- [Basic Calculator](../0224/README_EN.md)
- [Basic Calculator II](../0227/README_EN.md)
- [Different Ways to Add Parentheses](../0241/README_EN.md)
- [Target Sum](../0494/README_EN.md)
