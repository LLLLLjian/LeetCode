
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0947. 移除最多的同行或同列石头](https://leetcode-cn.com/problems/most-stones-removed-with-same-row-or-column/)
## 题目描述
<p>在二维平面上，我们将石头放置在一些整数坐标点上。每个坐标点上最多只能有一块石头。<br>
<br>
现在，<em>move</em> 操作将会移除与网格上的某一块石头共享一列或一行的一块石头。<br>
<br>
我们最多能执行多少次 <em>move</em> 操作？</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>stones = [[0,0],[0,1],[1,0],[1,2],[2,1],[2,2]]
<strong>输出：</strong>5
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>stones = [[0,0],[0,2],[1,1],[2,0],[2,2]]
<strong>输出：</strong>3
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>stones = [[0,0]]
<strong>输出：</strong>0
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= stones.length &lt;= 1000</code></li>
	<li><code>0 &lt;= stones[i][j] &lt; 10000</code></li>
</ol>

## 相关话题
- [深度优先搜索](https://leetcode-cn.com/tag/depth-first-search)
- [并查集](https://leetcode-cn.com/tag/union-find)
## 相似题目

