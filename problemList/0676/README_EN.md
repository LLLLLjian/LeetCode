
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0676. Implement Magic Dictionary](https://leetcode-cn.com/problems/implement-magic-dictionary/)
## Description
<p>
Implement a magic directory with <code>buildDict</code>, and <code>search</code> methods.
</p>

<p>
For the method <code>buildDict</code>, you'll be given a list of non-repetitive words to build a dictionary.
</p>

<p>
For the method <code>search</code>, you'll be given a word, and judge whether if you modify <b>exactly</b> one character into <b>another</b> character in this word, the modified word is in the dictionary you just built.
</p>

<p><b>Example 1:</b><br />
<pre>
Input: buildDict(["hello", "leetcode"]), Output: Null
Input: search("hello"), Output: False
Input: search("hhllo"), Output: True
Input: search("hell"), Output: False
Input: search("leetcoded"), Output: False
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li>You may assume that all the inputs are consist of lowercase letters <code>a-z</code>.</li>
<li>For contest purpose, the test data is rather small by now. You could think about highly efficient algorithm after the contest.</li>
<li>Please remember to <b>RESET</b> your class variables declared in class MagicDictionary, as static/class variables are <b>persisted across multiple test cases</b>. Please see <a href="https://leetcode.com/faq/#different-output">here</a> for more details.</li>
</ol>
</p>
## Related Topics
- [Trie](https://leetcode-cn.com/tag/trie)
- [Hash Table](https://leetcode-cn.com/tag/hash-table)
## Similar Questions
- [Implement Trie (Prefix Tree)](../0208/README_EN.md)
- [Longest Word in Dictionary](../0720/README_EN.md)
