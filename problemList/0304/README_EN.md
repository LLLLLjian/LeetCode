
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0304. Range Sum Query 2D - Immutable](https://leetcode-cn.com/problems/range-sum-query-2d-immutable/)
## Description
<p>Given a 2D matrix <i>matrix</i>, find the sum of the elements inside the rectangle defined by its upper left corner (<i>row</i>1, <i>col</i>1) and lower right corner (<i>row</i>2, <i>col</i>2).</p>

<p>
<img src="/static/images/courses/range_sum_query_2d.png" border="0" alt="Range Sum Query 2D" /><br />
<small>The above rectangle (with the red border) is defined by (row1, col1) = <b>(2, 1)</b> and (row2, col2) = <b>(4, 3)</b>, which contains sum = <b>8</b>.</small>
</p>

<p><b>Example:</b><br>
<pre>
Given matrix = [
  [3, 0, 1, 4, 2],
  [5, 6, 3, 2, 1],
  [1, 2, 0, 1, 5],
  [4, 1, 0, 1, 7],
  [1, 0, 3, 0, 5]
]

sumRegion(2, 1, 4, 3) -> 8
sumRegion(1, 1, 2, 2) -> 11
sumRegion(1, 2, 2, 4) -> 12
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li>You may assume that the matrix does not change.</li>
<li>There are many calls to <i>sumRegion</i> function.</li>
<li>You may assume that <i>row</i>1 &le; <i>row</i>2 and <i>col</i>1 &le; <i>col</i>2.</li>
</ol>
</p>
## Related Topics
- [Dynamic Programming](https://leetcode-cn.com/tag/dynamic-programming)
## Similar Questions
- [Range Sum Query - Immutable](../0303/README_EN.md)
- [Range Sum Query 2D - Mutable](../0308/README_EN.md)
