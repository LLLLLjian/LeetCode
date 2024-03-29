
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0207. Course Schedule](https://leetcode-cn.com/problems/course-schedule/)
## Description
<p>There are a total of <i>n</i> courses you have to take, labeled from <code>0</code> to <code>n-1</code>.</p>

<p>Some courses may have prerequisites, for example to take course 0 you have to first take course 1, which is expressed as a pair: <code>[0,1]</code></p>

<p>Given the total number of courses and a list of prerequisite <b>pairs</b>, is it possible for you to finish all courses?</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> 2, [[1,0]] 
<strong>Output: </strong>true
<strong>Explanation:</strong>&nbsp;There are a total of 2 courses to take. 
&nbsp;            To take course 1 you should have finished course 0. So it is possible.</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> 2, [[1,0],[0,1]]
<strong>Output: </strong>false
<strong>Explanation:</strong>&nbsp;There are a total of 2 courses to take. 
&nbsp;            To take course 1 you should have finished course 0, and to take course 0 you should
&nbsp;            also have finished course 1. So it is impossible.
</pre>

<p><b>Note:</b></p>

<ol>
	<li>The input prerequisites is a graph represented by <b>a list of edges</b>, not adjacency matrices. Read more about <a href="https://www.khanacademy.org/computing/computer-science/algorithms/graph-representation/a/representing-graphs" target="_blank">how a graph is represented</a>.</li>
	<li>You may assume that there are no duplicate edges in the input prerequisites.</li>
</ol>

## Related Topics
- [Depth-first Search](https://leetcode-cn.com/tag/depth-first-search)
- [Breadth-first Search](https://leetcode-cn.com/tag/breadth-first-search)
- [Graph](https://leetcode-cn.com/tag/graph)
- [Topological Sort](https://leetcode-cn.com/tag/topological-sort)
## Similar Questions
- [Course Schedule II](../0210/README_EN.md)
- [Graph Valid Tree](../0261/README_EN.md)
- [Minimum Height Trees](../0310/README_EN.md)
- [Course Schedule III](../0630/README_EN.md)
