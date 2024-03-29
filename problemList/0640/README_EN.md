
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0640. Solve the Equation](https://leetcode-cn.com/problems/solve-the-equation/)
## Description
<p>
Solve a given equation and return the value of <code>x</code> in the form of string "x=#value". The equation contains only '+', '-' operation, the variable <code>x</code> and its coefficient.
</p>

<p>
If there is no solution for the equation, return "No solution".
</p>
<p>
If there are infinite solutions for the equation, return "Infinite solutions".
</p>
<p>
If there is exactly one solution for the equation, we ensure that the value of <code>x</code> is an integer.
</p>

<p><b>Example 1:</b><br/>
<pre>
<b>Input:</b> "x+5-3+x=6+x-2"
<b>Output:</b> "x=2"
</pre>
</p>

<p><b>Example 2:</b><br/>
<pre>
<b>Input:</b> "x=x"
<b>Output:</b> "Infinite solutions"
</pre>
</p>

<p><b>Example 3:</b><br/>
<pre>
<b>Input:</b> "2x=x"
<b>Output:</b> "x=0"
</pre>
</p>

<p><b>Example 4:</b><br/>
<pre>
<b>Input:</b> "2x+3x-6x=x+2"
<b>Output:</b> "x=-1"
</pre>
</p>

<p><b>Example 5:</b><br/>
<pre>
<b>Input:</b> "x=x+2"
<b>Output:</b> "No solution"
</pre>
</p>
## Related Topics
- [Math](https://leetcode-cn.com/tag/math)
## Similar Questions
- [Fraction Addition and Subtraction](../0592/README_EN.md)
