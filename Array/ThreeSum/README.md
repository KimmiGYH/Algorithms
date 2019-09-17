# Three Sum （三数之和）

**LeetCode 15**

* [英文版](https://leetcode.com/problems/3sum/)

* [中文版](https://leetcode-cn.com/problems/3sum/)

## 题目

给定一个包含 n 个整数的数组 nums，判断 nums 中是否存在三个元素 a，b，c ，使得 a + b + c = 0 ？找出所有满足条件且不重复的三元组。

注意：答案中不可以包含重复的三元组。

例如, 给定数组 nums = [-1, 0, 1, 2, -1, -4]，

满足要求的三元组集合为：
[
  [-1, 0, 1],
  [-1, -1, 2]
]

## 思路

1. 先对原数组排序
2. 从小到大遍历排序的数组
3. 在当前遍历下标的后面剩余数组中使用两边夹逼的方式查找两个数
4. 如果这两个数与当前下标的数之和等于 0，则存入结果数组
5. 否则继续夹逼查找

## 代码实现

| C++ | Java | Python | JavaScript | Go |
| :--: | :--: | :--: | :--: | :---: | :---: | :---: |
| [😀](ThreeSum.cpp) | [😀](ThreeSum.java) | [😀](ThreeSum.py) | [😀](./ThreeSum.js) | [😀](three_sum.go) |