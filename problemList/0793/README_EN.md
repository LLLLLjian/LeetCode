
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0793. Preimage Size of Factorial Zeroes Function](https://leetcode-cn.com/problems/preimage-size-of-factorial-zeroes-function/)
## Description
<p>Let <code>f(x)</code> be the number of zeroes at the end of <code>x!</code>. (Recall that <code>x! = 1 * 2 * 3 * ... * x</code>, and by convention, <code>0! = 1</code>.)</p>

<p>For example, <code>f(3) = 0</code> because 3! = 6 has no zeroes at the end, while <code>f(11) = 2</code> because 11! = 39916800 has 2 zeroes at the end. Given <code>K</code>, find how many non-negative integers <code>x</code> have the property that <code>f(x) = K</code>.</p>

<pre>
<strong>Example 1:</strong>
<strong>Input:</strong> K = 0
<strong>Output:</strong> 5
<strong>Explanation:</strong> 0!, 1!, 2!, 3!, and 4! end with K = 0 zeroes.

<strong>Example 2:</strong>
<strong>Input:</strong> K = 5
<strong>Output:</strong> 0
<strong>Explanation:</strong> There is no x such that x! ends in K = 5 zeroes.
</pre>

<p><strong>Note:</strong></p>

<ul>
	<li><code>K</code> will be an integer in the range <code>[0, 10^9]</code>.</li>
</ul>

## Related Topics
- [Binary Search](https://leetcode-cn.com/tag/binary-search)
## Similar Questions
- [Factorial Trailing Zeroes](../0172/README_EN.md)
