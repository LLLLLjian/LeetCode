
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0546. Remove Boxes](https://leetcode-cn.com/problems/remove-boxes/)
## Description
<p>Given several boxes with different colors represented by different positive numbers. <br />
You may experience several rounds to remove boxes until there is no box left. Each time you can choose some continuous boxes with the same color (composed of k boxes, k >= 1), remove them and get <code>k*k</code> points.<br />
Find the maximum points you can get.
</p>

<p><b>Example 1:</b><br>
Input: 
<pre>
[1, 3, 2, 2, 2, 3, 4, 3, 1]
</pre>
Output:
<pre>
23
</pre>
Explanation: 
<pre>
[1, 3, 2, 2, 2, 3, 4, 3, 1] 
----> [1, 3, 3, 4, 3, 1] (3*3=9 points) 
----> [1, 3, 3, 3, 1] (1*1=1 points) 
----> [1, 1] (3*3=9 points) 
----> [] (2*2=4 points)
</pre>
</p>

<p><b>Note:</b>
The number of boxes <code>n</code> would not exceed 100.
</p>

## Related Topics
- [Depth-first Search](https://leetcode-cn.com/tag/depth-first-search)
- [Dynamic Programming](https://leetcode-cn.com/tag/dynamic-programming)
## Similar Questions
- [Strange Printer](../0664/README_EN.md)
