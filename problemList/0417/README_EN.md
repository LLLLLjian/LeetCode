
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0417. Pacific Atlantic Water Flow](https://leetcode-cn.com/problems/pacific-atlantic-water-flow/)
## Description
<p>Given an <code>m x n</code> matrix of non-negative integers representing the height of each unit cell in a continent, the "Pacific ocean" touches the left and top edges of the matrix and the "Atlantic ocean" touches the right and bottom edges.</p>

<p>Water can only flow in four directions (up, down, left, or right) from a cell to another one with height equal or lower.</p>

<p>Find the list of grid coordinates where water can flow to both the Pacific and Atlantic ocean.</p>

<p><b>Note:</b><br />
<ol>
<li>The order of returned grid coordinates does not matter.</li>
<li>Both <i>m</i> and <i>n</i> are less than 150.</li>
</ol>
</p>
<p><b>Example:</b>
<pre>
Given the following 5x5 matrix:

  Pacific ~   ~   ~   ~   ~ 
       ~  1   2   2   3  (5) *
       ~  3   2   3  (4) (4) *
       ~  2   4  (5)  3   1  *
       ~ (6) (7)  1   4   5  *
       ~ (5)  1   1   2   4  *
          *   *   *   *   * Atlantic

Return:

[[0, 4], [1, 3], [1, 4], [2, 2], [3, 0], [3, 1], [4, 0]] (positions with parentheses in above matrix).
</pre>
</p>
## Related Topics
- [Depth-first Search](https://leetcode-cn.com/tag/depth-first-search)
- [Breadth-first Search](https://leetcode-cn.com/tag/breadth-first-search)
## Similar Questions

