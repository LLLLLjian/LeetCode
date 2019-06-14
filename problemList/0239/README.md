
| [English](README_EN.md) | 简体中文 |
# [0239. 滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum/)
## 题目描述
<p>给定一个数组 <em>nums</em>，有一个大小为&nbsp;<em>k&nbsp;</em>的滑动窗口从数组的最左侧移动到数组的最右侧。你只可以看到在滑动窗口 <em>k</em> 内的数字。滑动窗口每次只向右移动一位。</p>

<p>返回滑动窗口最大值。</p>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> <em>nums</em> = <code>[1,3,-1,-3,5,3,6,7]</code>, 和 <em>k</em> = 3
<strong>输出: </strong><code>[3,3,5,5,6,7] 
<strong>解释: 
</strong></code>
  滑动窗口的位置                最大值
---------------               -----
[1  3  -1] -3  5  3  6  7       3
 1 [3  -1  -3] 5  3  6  7       3
 1  3 [-1  -3  5] 3  6  7       5
 1  3  -1 [-3  5  3] 6  7       5
 1  3  -1  -3 [5  3  6] 7       6
 1  3  -1  -3  5 [3  6  7]      7</pre>

<p><strong>注意：</strong></p>

<p>你可以假设 <em>k </em>总是有效的，1 &le; k &le;&nbsp;输入数组的大小，且输入数组不为空。</p>

<p><strong>进阶：</strong></p>

<p>你能在线性时间复杂度内解决此题吗？</p>

## 相关话题
- [堆](https://leetcode-cn.com/tag/heap)
- [None](https://leetcode-cn.com/tag/sliding-window)
## 相似题目
- [最小覆盖子串](../minimum-window-substring/README.md)
- [最小栈](../min-stack/README.md)
- [至多包含两个不同字符的最长子串](../longest-substring-with-at-most-two-distinct-characters/README.md)
- [粉刷房子 II](../paint-house-ii/README.md)
