
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0526. 优美的排列](https://leetcode-cn.com/problems/beautiful-arrangement/)
## 题目描述
<p>假设有从 1 到 N 的&nbsp;<strong>N&nbsp;</strong>个整数，如果从这&nbsp;<strong>N&nbsp;</strong>个数字中成功构造出一个数组，使得数组的第 <strong>i</strong>&nbsp;位 (1 &lt;= i &lt;= N) 满足如下两个条件中的一个，我们就称这个数组为一个优美的排列。条件：</p>

<ol>
	<li>第&nbsp;<strong>i&nbsp;</strong>位的数字能被&nbsp;<strong>i&nbsp;</strong>整除</li>
	<li><strong>i</strong> 能被第 <strong>i</strong> 位上的数字整除</li>
</ol>

<p>现在给定一个整数 N，请问可以构造多少个优美的排列？</p>

<p><strong>示例1:</strong></p>

<pre>
<strong>输入:</strong> 2
<strong>输出:</strong> 2
<strong>解释:</strong> 

第 1 个优美的排列是 [1, 2]:
  第 1 个位置（i=1）上的数字是1，1能被 i（i=1）整除
  第 2 个位置（i=2）上的数字是2，2能被 i（i=2）整除

第 2 个优美的排列是 [2, 1]:
  第 1 个位置（i=1）上的数字是2，2能被 i（i=1）整除
  第 2 个位置（i=2）上的数字是1，i（i=2）能被 1 整除
</pre>

<p><strong>说明:</strong></p>

<ol>
	<li><strong>N</strong> 是一个正整数，并且不会超过15。</li>
</ol>

## 相关话题
- [回溯算法](https://leetcode-cn.com/tag/backtracking)
## 相似题目
- [优美的排列 II](../0667/README.md)
