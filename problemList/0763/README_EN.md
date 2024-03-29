
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0763. Partition Labels](https://leetcode-cn.com/problems/partition-labels/)
## Description
<p>
A string <code>S</code> of lowercase letters is given.  We want to partition this string into as many parts as possible so that each letter appears in at most one part, and return a list of integers representing the size of these parts.
</p><p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b> S = "ababcbacadefegdehijhklij"
<b>Output:</b> [9,7,8]
<b>Explanation:</b>
The partition is "ababcbaca", "defegde", "hijhklij".
This is a partition so that each letter appears in at most one part.
A partition like "ababcbacadefegde", "hijhklij" is incorrect, because it splits S into less parts.
</pre>
</p>

<p><b>Note:</b><br><ol>
<li><code>S</code> will have length in range <code>[1, 500]</code>.</li>
<li><code>S</code> will consist of lowercase letters (<code>'a'</code> to <code>'z'</code>) only.</li>
</ol></p>
## Related Topics
- [Greedy](https://leetcode-cn.com/tag/greedy)
- [Two Pointers](https://leetcode-cn.com/tag/two-pointers)
## Similar Questions
- [Merge Intervals](../0056/README_EN.md)
