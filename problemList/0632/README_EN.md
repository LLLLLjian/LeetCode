
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0632. Smallest Range](https://leetcode-cn.com/problems/smallest-range/)
## Description
<p>You have <code>k</code> lists of sorted integers in ascending order. Find the <b>smallest</b> range that includes at least one number from each of the <code>k</code> lists. </p>

<p>We define the range [a,b] is smaller than range [c,d] if <code>b-a < d-c</code> or <code>a < c</code> if <code>b-a == d-c</code>.</p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b>[[4,10,15,24,26], [0,9,12,20], [5,18,22,30]]
<b>Output:</b> [20,24]
<b>Explanation:</b> 
List 1: [4, 10, 15, 24,26], 24 is in range [20,24].
List 2: [0, 9, 12, 20], 20 is in range [20,24].
List 3: [5, 18, 22, 30], 22 is in range [20,24].
</pre>
</p>

<p>
<b>Note:</b><br/>
<ol>
<li>The given list may contain duplicates, so ascending order means >= here.</li>
<li>1 <= <code>k</code> <= 3500</li>
<li> -10<sup>5</sup> <= <code>value of elements</code> <= 10<sup>5</sup>.</li>
<li><b>For Java users, please note that the input type has been changed to List&lt;List&lt;Integer&gt;&gt;. And after you reset the code template, you'll see this point.</b></li>
</ol>
<br/>
</p>
## Related Topics
- [Hash Table](https://leetcode-cn.com/tag/hash-table)
- [Two Pointers](https://leetcode-cn.com/tag/two-pointers)
- [String](https://leetcode-cn.com/tag/string)
## Similar Questions
- [Minimum Window Substring](../0076/README_EN.md)
