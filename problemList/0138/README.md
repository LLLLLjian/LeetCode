
| [English](README_EN.md) | 简体中文 | [问题相关](QUESTION.md) |
# [0138. 复制带随机指针的链表](https://leetcode-cn.com/problems/copy-list-with-random-pointer/)
## 题目描述
<p>给定一个链表，每个节点包含一个额外增加的随机指针，该指针可以指向链表中的任何节点或空节点。</p>

<p>要求返回这个链表的<strong><a href="https://baike.baidu.com/item/深拷贝/22785317?fr=aladdin" target="_blank">深拷贝</a></strong>。&nbsp;</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/02/23/1470150906153-2yxeznm.png"></strong></p>

<pre><strong>输入：
</strong>{&quot;$id&quot;:&quot;1&quot;,&quot;next&quot;:{&quot;$id&quot;:&quot;2&quot;,&quot;next&quot;:null,&quot;random&quot;:{&quot;$ref&quot;:&quot;2&quot;},&quot;val&quot;:2},&quot;random&quot;:{&quot;$ref&quot;:&quot;2&quot;},&quot;val&quot;:1}

<strong>解释：
</strong>节点 1 的值是 1，它的下一个指针和随机指针都指向节点 2 。
节点 2 的值是 2，它的下一个指针指向 null，随机指针指向它自己。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>你必须返回<strong>给定头的拷贝</strong>作为对克隆列表的引用。</li>
</ol>

## 相关话题
- [哈希表](https://leetcode-cn.com/tag/hash-table)
- [链表](https://leetcode-cn.com/tag/linked-list)
## 相似题目
- [克隆图](../0133/README.md)
