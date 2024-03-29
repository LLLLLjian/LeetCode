
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0211. 添加与搜索单词 - 数据结构设计](https://leetcode-cn.com/problems/add-and-search-word-data-structure-design/)
## 题目描述
<p>设计一个支持以下两种操作的数据结构：</p>

<pre>void addWord(word)
bool search(word)
</pre>

<p>search(word)&nbsp;可以搜索文字或正则表达式字符串，字符串只包含字母&nbsp;<code>.</code>&nbsp;或&nbsp;<code>a-z</code>&nbsp;。&nbsp;<code>.</code> 可以表示任何一个字母。</p>

<p><strong>示例:</strong></p>

<pre>addWord(&quot;bad&quot;)
addWord(&quot;dad&quot;)
addWord(&quot;mad&quot;)
search(&quot;pad&quot;) -&gt; false
search(&quot;bad&quot;) -&gt; true
search(&quot;.ad&quot;) -&gt; true
search(&quot;b..&quot;) -&gt; true
</pre>

<p><strong>说明:</strong></p>

<p>你可以假设所有单词都是由小写字母 <code>a-z</code>&nbsp;组成的。</p>

## 相关话题
- [设计](https://leetcode-cn.com/tag/design)
- [字典树](https://leetcode-cn.com/tag/trie)
- [回溯算法](https://leetcode-cn.com/tag/backtracking)
## 相似题目
- [实现 Trie (前缀树)](../0208/README.md)
- [前缀和后缀搜索](../0745/README.md)
