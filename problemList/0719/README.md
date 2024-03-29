
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0719. 找出第 k 小的距离对](https://leetcode-cn.com/problems/find-k-th-smallest-pair-distance/)
## 题目描述
<p>给定一个整数数组，返回所有数对之间的第 k 个最小<strong>距离</strong>。一对 (A, B) 的距离被定义为 A 和 B 之间的绝对差值。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入：</strong>
nums = [1,3,1]
k = 1
<strong>输出：0</strong> 
<strong>解释：</strong>
所有数对如下：
(1,3) -&gt; 2
(1,1) -&gt; 0
(3,1) -&gt; 2
因此第 1 个最小距离的数对是 (1,1)，它们之间的距离为 0。
</pre>

<p><strong>提示:</strong></p>

<ol>
	<li><code>2 &lt;= len(nums) &lt;= 10000</code>.</li>
	<li><code>0 &lt;= nums[i] &lt; 1000000</code>.</li>
	<li><code>1 &lt;= k &lt;= len(nums) * (len(nums) - 1) / 2</code>.</li>
</ol>

## 相关话题
- [堆](https://leetcode-cn.com/tag/heap)
- [数组](https://leetcode-cn.com/tag/array)
- [二分查找](https://leetcode-cn.com/tag/binary-search)
## 相似题目
- [查找和最小的K对数字](../0373/README.md)
- [有序矩阵中第K小的元素](../0378/README.md)
- [找到 K 个最接近的元素](../0658/README.md)
- [乘法表中第k小的数](../0668/README.md)
- [第 K 个最小的素数分数](../0786/README.md)
