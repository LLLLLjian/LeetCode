
| [English](README_EN.md) | 简体中文 |
# [0988. 从叶结点开始的最小字符串](https://leetcode-cn.com/problems/smallest-string-starting-from-leaf/)
## 题目描述
<p>给定一颗根结点为&nbsp;<code>root</code>&nbsp;的二叉树，书中的每个结点都有一个从&nbsp;<code>0</code> 到&nbsp;<code>25</code>&nbsp;的值，分别代表字母&nbsp;<code>&#39;a&#39;</code> 到&nbsp;<code>&#39;z&#39;</code>：值&nbsp;<code>0</code> 代表&nbsp;<code>&#39;a&#39;</code>，值&nbsp;<code>1</code>&nbsp;代表&nbsp;<code>&#39;b&#39;</code>，依此类推。</p>

<p>找出按字典序最小的字符串，该字符串从这棵树的一个叶结点开始，到根结点结束。</p>

<p><em>（小贴士：字符串中任何较短的前缀在字典序上都是较小的：例如，在字典序上&nbsp;<code>&quot;ab&quot;</code> 比&nbsp;<code>&quot;aba&quot;</code>&nbsp;要小。叶结点是指没有子结点的结点。）</em></p>

<p>&nbsp;</p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/02/02/tree1.png" style="height: 107px; width: 160px;"></strong></p>

<pre><strong>输入：</strong>[0,1,2,3,4,3,4]
<strong>输出：</strong>&quot;dba&quot;
</pre>

<p><strong>示例 2：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/02/02/tree2.png" style="height: 107px; width: 160px;"></strong></p>

<pre><strong>输入：</strong>[25,1,3,1,3,0,2]
<strong>输出：</strong>&quot;adz&quot;
</pre>

<p><strong>示例 3：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/02/02/tree3.png" style="height: 180px; width: 172px;"></strong></p>

<pre><strong>输入：</strong>[2,2,1,null,1,0,null,0]
<strong>输出：</strong>&quot;abc&quot;
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>给定树的结点数介于&nbsp;<code>1</code> 和&nbsp;<code>8500</code>&nbsp;之间。</li>
	<li>树中的每个结点都有一个介于&nbsp;<code>0</code>&nbsp;和&nbsp;<code>25</code>&nbsp;之间的值。</li>
</ol>

## 相关话题
- [树](https://leetcode-cn.com/tag/tree)
- [深度优先搜索](https://leetcode-cn.com/tag/depth-first-search)
## 相似题目
- [求根到叶子节点数字之和](../sum-root-to-leaf-numbers/README.md)
- [二叉树的所有路径](../binary-tree-paths/README.md)