
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0546. 移除盒子](https://leetcode-cn.com/problems/remove-boxes/)
## 题目描述
<p>给出一些不同颜色的盒子，盒子的颜色由数字表示，即不同的数字表示不同的颜色。<br />
你将经过若干轮操作去去掉盒子，直到所有的盒子都去掉为止。每一轮你可以移除具有相同颜色的连续 k 个盒子（k&nbsp;&gt;= 1），这样一轮之后你将得到 <code>k*k</code> 个积分。<br />
当你将所有盒子都去掉之后，求你能获得的最大积分和。</p>

<p><strong>示例 1：</strong><br />
输入:</p>

<pre>
[1, 3, 2, 2, 2, 3, 4, 3, 1]
</pre>

<p>输出:</p>

<pre>
23
</pre>

<p>解释:</p>

<pre>
[1, 3, 2, 2, 2, 3, 4, 3, 1] 
----&gt; [1, 3, 3, 4, 3, 1] (3*3=9 分) 
----&gt; [1, 3, 3, 3, 1] (1*1=1 分) 
----&gt; [1, 1] (3*3=9 分) 
----&gt; [] (2*2=4 分)
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong>盒子的总数 <code>n</code> 不会超过 100。</p>

## 相关话题
- [深度优先搜索](https://leetcode-cn.com/tag/depth-first-search)
- [动态规划](https://leetcode-cn.com/tag/dynamic-programming)
## 相似题目
- [奇怪的打印机](../0664/README.md)
