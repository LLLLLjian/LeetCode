
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0402. Remove K Digits](https://leetcode-cn.com/problems/remove-k-digits/)
## Description
<p>Given a non-negative integer <i>num</i> represented as a string, remove <i>k</i> digits from the number so that the new number is the smallest possible.
</p>

<p><b>Note:</b><br />
<ul>
<li>The length of <i>num</i> is less than 10002 and will be &ge; <i>k</i>.</li>
<li>The given <i>num</i> does not contain any leading zero.</li>
</ul>
</b>
</p>

<p><b>Example 1:</b>
<pre>
Input: num = "1432219", k = 3
Output: "1219"
Explanation: Remove the three digits 4, 3, and 2 to form the new number 1219 which is the smallest.
</pre>
</p>

<p><b>Example 2:</b>
<pre>
Input: num = "10200", k = 1
Output: "200"
Explanation: Remove the leading 1 and the number is 200. Note that the output must not contain leading zeroes.
</pre>
</p>

<p><b>Example 3:</b>
<pre>
Input: num = "10", k = 2
Output: "0"
Explanation: Remove all the digits from the number and it is left with nothing which is 0.
</pre>
</p>
## Related Topics
- [Stack](https://leetcode-cn.com/tag/stack)
- [Greedy](https://leetcode-cn.com/tag/greedy)
## Similar Questions
- [Create Maximum Number](../0321/README_EN.md)
- [Monotone Increasing Digits](../0738/README_EN.md)
