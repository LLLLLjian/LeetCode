
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0828. 独特字符串](https://leetcode-cn.com/problems/unique-letter-string/)
## 题目描述
<p>如果一个字符在字符串&nbsp;<code>S</code>&nbsp;中有且仅有出现一次，那么我们称其为独特字符。</p>

<p>例如，在字符串&nbsp;<code>S = &quot;LETTER&quot;</code>&nbsp;中，<code>&quot;L&quot;</code>&nbsp;和&nbsp;<code>&quot;R&quot;</code>&nbsp;可以被称为独特字符。</p>

<p>我们再定义&nbsp;<code>UNIQ(S)</code>&nbsp;作为字符串&nbsp;<code>S</code>&nbsp;中独特字符的个数。</p>

<p>那么，在&nbsp;<code>S = &quot;LETTER&quot;</code>&nbsp;中，&nbsp;<code>UNIQ(&quot;LETTER&quot;) =&nbsp; 2</code>。</p>

<p>对于给定字符串&nbsp;<code>S</code>，计算其所有非空子串的独特字符的个数（即&nbsp;<code>UNIQ(substring)</code>）之和。</p>

<p>如果在 <code>S</code>&nbsp;的不同位置上出现两个甚至多个相同的子串，那么我们认为这些子串是不同的。</p>

<p>考虑到答案可能会非常大，规定返回格式为：结果 mod&nbsp;<code>10 ^ 9 + 7</code>。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入: </strong>&quot;ABC&quot;
<strong>输出: </strong>10
<strong>解释:</strong> 所有可能的子串为：&quot;A&quot;,&quot;B&quot;,&quot;C&quot;,&quot;AB&quot;,&quot;BC&quot; 和 &quot;ABC&quot;。
     其中，每一个子串都由独特字符构成。
     所以其长度总和为：1 + 1 + 1 + 2 + 2 + 3 = 10
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入: </strong>&quot;ABA&quot;
<strong>输出: </strong>8
<strong>解释: </strong>除了子串 UNIQ(&#39;ABA&#39;) = 1，其余与示例1相同。
</pre>

<p>&nbsp;</p>

<p><strong>说明:</strong> <code>0 &lt;= S.length &lt;= 10000</code>。</p>

## 相关话题
- [双指针](https://leetcode-cn.com/tag/two-pointers)
## 相似题目

