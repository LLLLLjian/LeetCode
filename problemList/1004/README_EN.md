
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [1004. Max Consecutive Ones III](https://leetcode-cn.com/problems/max-consecutive-ones-iii/)
## Description
<p>Given an array <code>A</code>&nbsp;of 0s and 1s, we may change up to <code>K</code>&nbsp;values from 0 to 1.</p>

<p>Return the length of the longest (contiguous) subarray that contains only 1s.&nbsp;</p>

<p>&nbsp;</p>

<div>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong>A = <span id="example-input-1-1">[1,1,1,0,0,0,1,1,1,1,0]</span>, K = <span id="example-input-1-2">2</span>
<strong>Output: </strong><span id="example-output-1">6</span>
<strong>Explanation: </strong>
[1,1,1,0,0,<u><strong>1</strong>,1,1,1,1,<strong>1</strong></u>]
Bolded numbers were flipped from 0 to 1.  The longest subarray is underlined.</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong>A = <span id="example-input-2-1">[0,0,1,1,0,0,1,1,1,0,1,1,0,0,0,1,1,1,1]</span>, K = <span id="example-input-2-2">3</span>
<strong>Output: </strong><span id="example-output-2">10</span>
<strong>Explanation: </strong>
[0,0,<u>1,1,<b>1</b>,<strong>1</strong>,1,1,1,<strong>1</strong>,1,1</u>,0,0,0,1,1,1,1]
Bolded numbers were flipped from 0 to 1.  The longest subarray is underlined.
</pre>

<p>&nbsp;</p>

<p><strong><span>Note:</span></strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 20000</code></li>
	<li><code>0 &lt;= K &lt;= A.length</code></li>
	<li><code>A[i]</code> is <code>0</code> or <code>1</code>&nbsp;</li>
</ol>
</div>
</div>

## Related Topics
- [Two Pointers](https://leetcode-cn.com/tag/two-pointers)
- [Sliding Window](https://leetcode-cn.com/tag/sliding-window)
## Similar Questions
- [Longest Substring with At Most K Distinct Characters](../0340/README_EN.md)
- [Longest Repeating Character Replacement](../0424/README_EN.md)
- [Max Consecutive Ones](../0485/README_EN.md)
- [Max Consecutive Ones II](../0487/README_EN.md)
