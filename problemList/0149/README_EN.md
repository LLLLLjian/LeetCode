
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0149. Max Points on a Line](https://leetcode-cn.com/problems/max-points-on-a-line/)
## Description
<p>Given <em>n</em> points on a 2D plane, find the maximum number of points that lie on the same straight line.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> [[1,1],[2,2],[3,3]]
<strong>Output:</strong> 3
<strong>Explanation:</strong>
^
|
| &nbsp; &nbsp; &nbsp; &nbsp;o
| &nbsp; &nbsp; o
| &nbsp;o &nbsp;
+-------------&gt;
0 &nbsp;1 &nbsp;2 &nbsp;3  4
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> [[1,1],[3,2],[5,3],[4,1],[2,3],[1,4]]
<strong>Output:</strong> 4
<strong>Explanation:</strong>
^
|
|  o
| &nbsp;&nbsp;&nbsp;&nbsp;o&nbsp;&nbsp;      o
| &nbsp;&nbsp;&nbsp;&nbsp;   o
| &nbsp;o &nbsp;      o
+-------------------&gt;
0 &nbsp;1 &nbsp;2 &nbsp;3 &nbsp;4 &nbsp;5 &nbsp;6
</pre>

<p><strong>NOTE:</strong>&nbsp;input types have been changed on April 15, 2019. Please reset to default code definition to get new method signature.</p>

## Related Topics
- [Hash Table](https://leetcode-cn.com/tag/hash-table)
- [Math](https://leetcode-cn.com/tag/math)
## Similar Questions
- [Line Reflection](../0356/README_EN.md)
