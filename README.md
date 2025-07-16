# Max Number of K-Sum Pairs

## Problem Description

You are given an integer array `nums` and an integer `k`.

In one operation, you can pick **two numbers** from the array whose **sum equals `k`** and **remove them** from the array.

Return the **maximum number of operations** you can perform on the array.

## Examples

### Example 1:
**Input:**  
`nums = [1,2,3,4]`  
`k = 5`  
**Output:**  
`2`  

**Explanation:**  
Starting with `nums = [1,2,3,4]`:
- Remove numbers `1` and `4`, then `nums = [2,3]`
- Remove numbers `2` and `3`, then `nums = []`  
Total operations = 2

---

### Example 2:
**Input:**  
`nums = [3,1,3,4,3]`  
`k = 6`  
**Output:**  
`1`  

**Explanation:**  
- Remove a pair of `3`s (3 + 3 = 6), then `nums = [1,4,3]`  
No more valid pairs left  
Total operations = 1

---

## Constraints
- `1 <= nums.length <= 10⁵`
- `1 <= nums[i] <= 10⁹`
- `1 <= k <= 10⁹`
