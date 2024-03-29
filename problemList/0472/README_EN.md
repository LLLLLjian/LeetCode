
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0472. Concatenated Words](https://leetcode-cn.com/problems/concatenated-words/)
## Description
Given a list of words (<b>without duplicates</b>), please write a program that returns all concatenated words in the given list of words.
<p>A concatenated word is defined as a string that is comprised entirely of at least two shorter words in the given array.</p>

<p><b>Example:</b><br />
<pre>
<b>Input:</b> ["cat","cats","catsdogcats","dog","dogcatsdog","hippopotamuses","rat","ratcatdogcat"]

<b>Output:</b> ["catsdogcats","dogcatsdog","ratcatdogcat"]

<b>Explanation:</b> "catsdogcats" can be concatenated by "cats", "dog" and "cats"; <br> "dogcatsdog" can be concatenated by "dog", "cats" and "dog"; <br>"ratcatdogcat" can be concatenated by "rat", "cat", "dog" and "cat".
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li>The number of elements of the given array will not exceed <code>10,000 </code>
<li>The length sum of elements in the given array will not exceed <code>600,000</code>. </li>
<li>All the input string will only include lower case letters.</li>
<li>The returned elements order does not matter. </li>
</ol>
</p>
## Related Topics
- [Depth-first Search](https://leetcode-cn.com/tag/depth-first-search)
- [Trie](https://leetcode-cn.com/tag/trie)
- [Dynamic Programming](https://leetcode-cn.com/tag/dynamic-programming)
## Similar Questions
- [Word Break II](../0140/README_EN.md)
