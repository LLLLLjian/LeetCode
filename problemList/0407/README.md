
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0407. 接雨水 II](https://leetcode-cn.com/problems/trapping-rain-water-ii/)
## 题目描述
<p>给定一个 <code>m x n</code>&nbsp;的矩阵，其中的值均为正整数，代表二维高度图每个单元的高度，请计算图中形状最多能接多少体积的雨水。</p>

<p>&nbsp;</p>

<p><strong>说明:</strong></p>

<p><em>m&nbsp;</em>和 <em>n&nbsp;</em>都是小于110的整数。每一个单位的高度都大于0 且小于 20000。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre>给出如下 3x6 的高度图:
[
  [1,4,3,1,3,2],
  [3,2,1,3,2,4],
  [2,3,3,2,3,1]
]

返回 4。
</pre>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/10/12/rainwater_empty.png" style="width: 100%; max-width: 500px;"></p>

<p>如上图所示，这是下雨前的高度图<code>[[1,4,3,1,3,2],[3,2,1,3,2,4],[2,3,3,2,3,1]]</code> 的状态。</p>

<p>&nbsp;</p>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/10/12/rainwater_fill.png" style="width: 100%; max-width: 500px;"></p>

<p>下雨后，雨水将会被存储在这些方块中。总的接雨水量是4。</p>
## 相关话题
- [堆](https://leetcode-cn.com/tag/heap)
- [广度优先搜索](https://leetcode-cn.com/tag/breadth-first-search)
## 相似题目
- [接雨水](../0042/README.md)
