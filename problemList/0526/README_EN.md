
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0526. Beautiful Arrangement](https://leetcode-cn.com/problems/beautiful-arrangement/)
## Description
<p>Suppose you have <b>N</b> integers from 1 to N. We define a beautiful arrangement as an array that is constructed by these <b>N</b> numbers successfully if one of the following is true for the i<sub>th</sub> position (1 &lt;= i &lt;= N) in this array:</p>

<ol>
	<li>The number at the i<sub>th</sub> position is divisible by <b>i</b>.</li>
	<li><b>i</b> is divisible by the number at the i<sub>th</sub> position.</li>
</ol>

<p>&nbsp;</p>

<p>Now given N, how many beautiful arrangements can you construct?</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> 2
<b>Output:</b> 2
<b>Explanation:</b> 

The first beautiful arrangement is [1, 2]:

Number at the 1st position (i=1) is 1, and 1 is divisible by i (i=1).

Number at the 2nd position (i=2) is 2, and 2 is divisible by i (i=2).

The second beautiful arrangement is [2, 1]:

Number at the 1st position (i=1) is 2, and 2 is divisible by i (i=1).

Number at the 2nd position (i=2) is 1, and i (i=2) is divisible by 1.
</pre>

<p>&nbsp;</p>

<p><b>Note:</b></p>

<ol>
	<li><b>N</b> is a positive integer and will not exceed 15.</li>
</ol>

<p>&nbsp;</p>

## Related Topics
- [Backtracking](https://leetcode-cn.com/tag/backtracking)
## Similar Questions
- [Beautiful Arrangement II](../0667/README_EN.md)
