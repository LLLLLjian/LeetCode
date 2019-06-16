
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0424. Longest Repeating Character Replacement](https://leetcode-cn.com/problems/longest-repeating-character-replacement/)
## Description
<p>Given a string that consists of only uppercase English letters, you can replace any letter in the string with another letter at most <i>k</i> times. Find the length of a longest substring containing all repeating letters you can get after performing the above operations.</p>

<p><b>Note:</b><br />
Both the string's length and <i>k</i> will not exceed 10<sup>4</sup>.
</p>

<p>
<b>Example 1:</b>
<pre>
<b>Input:</b>
s = "ABAB", k = 2

<b>Output:</b>
4

<b>Explanation:</b>
Replace the two 'A's with two 'B's or vice versa.
</pre>
</p>

<p>
<b>Example 2:</b>
<pre>
<b>Input:</b>
s = "AABABBA", k = 1

<b>Output:</b>
4

<b>Explanation:</b>
Replace the one 'A' in the middle with 'B' and form "AABBBBA".
The substring "BBBB" has the longest repeating letters, which is 4.
</pre>
</p>
## Related Topics
- [Two Pointers](https://leetcode-cn.com/tag/two-pointers)
- [Sliding Window](https://leetcode-cn.com/tag/sliding-window)
## Similar Questions
- [Longest Substring with At Most K Distinct Characters](../0340/README_EN.md)
- [Max Consecutive Ones III](../1004/README_EN.md)
