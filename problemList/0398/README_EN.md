
| English | [简体中文](README.md) | [问题相关](QUESTION.md) |
# [0398. Random Pick Index](https://leetcode-cn.com/problems/random-pick-index/)
## Description
<p>Given an array of integers with possible duplicates, randomly output the index of a given target number. You can assume that the given target number must exist in the array.</p>

<p><b>Note:</b><br />
The array size can be very large. Solution that uses too much extra space will not pass the judge.</p>

<p><b>Example:</b></p>

<pre>
int[] nums = new int[] {1,2,3,3,3};
Solution solution = new Solution(nums);

// pick(3) should return either index 2, 3, or 4 randomly. Each index should have equal probability of returning.
solution.pick(3);

// pick(1) should return 0. Since in the array only nums[0] is equal to 1.
solution.pick(1);
</pre>

## Related Topics
- [Reservoir Sampling](https://leetcode-cn.com/tag/reservoir-sampling)
## Similar Questions
- [Linked List Random Node](../0382/README_EN.md)
- [Random Pick with Blacklist](../0710/README_EN.md)
- [Random Pick with Weight](../0528/README_EN.md)
