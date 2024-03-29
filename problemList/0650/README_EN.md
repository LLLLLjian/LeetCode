
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0650. 2 Keys Keyboard](https://leetcode-cn.com/problems/2-keys-keyboard/)
## Description
<p>Initially on a notepad only one character &#39;A&#39; is present. You can perform two operations on this notepad for each step:</p>

<ol>
	<li><code>Copy All</code>: You can copy all the characters present on the notepad (partial copy is not allowed).</li>
	<li><code>Paste</code>: You can paste the characters which are copied <b>last time</b>.</li>
</ol>

<p>&nbsp;</p>

<p>Given a number <code>n</code>. You have to get <b>exactly</b> <code>n</code> &#39;A&#39; on the notepad by performing the minimum number of steps permitted. Output the minimum number of steps to get <code>n</code> &#39;A&#39;.</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> 3
<b>Output:</b> 3
<b>Explanation:</b>
Intitally, we have one character &#39;A&#39;.
In step 1, we use <b>Copy All</b> operation.
In step 2, we use <b>Paste</b> operation to get &#39;AA&#39;.
In step 3, we use <b>Paste</b> operation to get &#39;AAA&#39;.
</pre>

<p>&nbsp;</p>

<p><b>Note:</b></p>

<ol>
	<li>The <code>n</code> will be in the range [1, 1000].</li>
</ol>

<p>&nbsp;</p>

## Related Topics
- [Dynamic Programming](https://leetcode-cn.com/tag/dynamic-programming)
## Similar Questions
- [4 Keys Keyboard](../0651/README_EN.md)
- [Broken Calculator](../0991/README_EN.md)
