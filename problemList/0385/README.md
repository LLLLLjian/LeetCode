
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0385. 迷你语法分析器](https://leetcode-cn.com/problems/mini-parser/)
## 题目描述
<p>给定一个用字符串表示的整数的嵌套列表，实现一个解析它的语法分析器。</p>

<p>列表中的每个元素只可能是整数或整数嵌套列表</p>

<p><strong>提示：</strong>你可以假定这些字符串都是格式良好的：</p>

<ul>
	<li>字符串非空</li>
	<li>字符串不包含空格</li>
	<li>字符串只包含数字<code>0-9</code>, <code>[</code>, <code>-</code> <code>,</code>, <code>]</code></li>
</ul>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
给定 s = &quot;324&quot;,

你应该返回一个 NestedInteger 对象，其中只包含整数值 324。
</pre>

<p>&nbsp;</p>

<p><strong>示例 2：</strong></p>

<pre>
给定 s = &quot;[123,[456,[789]]]&quot;,

返回一个 NestedInteger 对象包含一个有两个元素的嵌套列表：

1. 一个 integer 包含值 123
2. 一个包含两个元素的嵌套列表：
    i.  一个 integer 包含值 456
    ii. 一个包含一个元素的嵌套列表
         a. 一个 integer 包含值 789
</pre>

<p>&nbsp;</p>

## 相关话题
- [栈](https://leetcode-cn.com/tag/stack)
- [字符串](https://leetcode-cn.com/tag/string)
## 相似题目
- [扁平化嵌套列表迭代器](../0341/README.md)
- [三元表达式解析器](../0439/README.md)
- [删除注释](../0722/README.md)
