
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0208. 实现 Trie (前缀树)](https://leetcode-cn.com/problems/implement-trie-prefix-tree/)
## 题目描述
<p>实现一个 Trie (前缀树)，包含&nbsp;<code>insert</code>,&nbsp;<code>search</code>, 和&nbsp;<code>startsWith</code>&nbsp;这三个操作。</p>

<p><strong>示例:</strong></p>

<pre>Trie trie = new Trie();

trie.insert(&quot;apple&quot;);
trie.search(&quot;apple&quot;);   // 返回 true
trie.search(&quot;app&quot;);     // 返回 false
trie.startsWith(&quot;app&quot;); // 返回 true
trie.insert(&quot;app&quot;);   
trie.search(&quot;app&quot;);     // 返回 true</pre>

<p><strong>说明:</strong></p>

<ul>
	<li>你可以假设所有的输入都是由小写字母&nbsp;<code>a-z</code>&nbsp;构成的。</li>
	<li>保证所有输入均为非空字符串。</li>
</ul>

## 相关话题
- [设计](https://leetcode-cn.com/tag/design)
- [字典树](https://leetcode-cn.com/tag/trie)
## 相似题目
- [添加与搜索单词 - 数据结构设计](../0211/README.md)
- [设计搜索自动补全系统](../0642/README.md)
- [单词替换](../0648/README.md)
- [实现一个魔法字典](../0676/README.md)
