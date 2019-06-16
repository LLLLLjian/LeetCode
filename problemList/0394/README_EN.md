
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0394. Decode String](https://leetcode-cn.com/problems/decode-string/)
## Description
<p>
Given an encoded string, return it's decoded string.
</p>
<p>
The encoding rule is: <code>k[encoded_string]</code>, where the <i>encoded_string</i> inside the square brackets is being repeated exactly <i>k</i> times. Note that <i>k</i> is guaranteed to be a positive integer.</p>

<p>
You may assume that the input string is always valid; No extra white spaces, square brackets are well-formed, etc.</p>

<p>Furthermore, you may assume that the original data does not contain any digits and that digits are only for those repeat numbers, <i>k</i>. For example, there won't be input like <code>3a</code> or <code>2[4]</code>.
</p>

<p><b>Examples:</b>
<pre>
s = "3[a]2[bc]", return "aaabcbc".
s = "3[a2[c]]", return "accaccacc".
s = "2[abc]3[cd]ef", return "abcabccdcdcdef".
</pre>
</p>
## Related Topics
- [Stack](https://leetcode-cn.com/tag/stack)
- [Depth-first Search](https://leetcode-cn.com/tag/depth-first-search)
## Similar Questions
- [Encode String with Shortest Length](../0471/README_EN.md)
- [Number of Atoms](../0726/README_EN.md)
- [Permutation of Letters](../None/README_EN.md)
