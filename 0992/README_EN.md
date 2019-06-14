
| English | [简体中文](README.md) |
# [0992. Subarrays with K Different Integers](https://leetcode-cn.com/problems/subarrays-with-k-different-integers/)
## Description
<p>Given an array <code>A</code> of positive integers, call a (contiguous, not necessarily distinct) subarray of <code>A</code> <em>good</em> if the number of different integers in that subarray is exactly <code>K</code>.</p>

<p>(For example, <code>[1,2,3,1,2]</code> has <code>3</code> different integers: <code>1</code>, <code>2</code>, and <code>3</code>.)</p>

<p>Return the number of good subarrays of <code>A</code>.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong>A = <span id="example-input-1-1">[1,2,1,2,3]</span>, K = <span id="example-input-1-2">2</span>
<strong>Output: </strong><span id="example-output-1">7</span>
<strong>Explanation: </strong>Subarrays formed with exactly 2 different integers: [1,2], [2,1], [1,2], [2,3], [1,2,1], [2,1,2], [1,2,1,2].
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong>A = <span id="example-input-2-1">[1,2,1,3,4]</span>, K = <span id="example-input-2-2">3</span>
<strong>Output: </strong><span id="example-output-2">3</span>
<strong>Explanation: </strong>Subarrays formed with exactly 3 different integers: [1,2,1,3], [2,1,3], [1,3,4].
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 20000</code></li>
	<li><code>1 &lt;= A[i] &lt;= A.length</code></li>
	<li><code>1 &lt;= K &lt;= A.length</code></li>
</ol>
## Related Topics
- [Hash Table](https://leetcode-cn.com/tag/hash-table)
- [Two Pointers](https://leetcode-cn.com/tag/two-pointers)
- [Sliding Window](https://leetcode-cn.com/tag/sliding-window)
## Similar Questions
- [Longest Substring Without Repeating Characters](../longest-substring-without-repeating-characters/README_EN.md)
- [Longest Substring with At Most Two Distinct Characters](../longest-substring-with-at-most-two-distinct-characters/README_EN.md)
- [Longest Substring with At Most K Distinct Characters](../longest-substring-with-at-most-k-distinct-characters/README_EN.md)
