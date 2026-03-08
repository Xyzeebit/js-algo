# Test Cases for LeetCode‑Style JavaScript Problems

Below are test cases for each of the 30 problems. Inputs and expected outputs are shown. For linked list and tree problems, inputs are given in the standard LeetCode serialization format (level order for trees, array representation for lists).

---

## 1. Two Sum
| Input | Expected Output |
|-------|-----------------|
| `nums = [2,7,11,15], target = 9` | `[0,1]` |
| `nums = [3,2,4], target = 6` | `[1,2]` |
| `nums = [3,3], target = 6` | `[0,1]` |
| `nums = [1,2,3,4], target = 7` | `[2,3]` |

---

## 2. Palindrome Number
| Input | Expected Output |
|-------|-----------------|
| `x = 121` | `true` |
| `x = -121` | `false` |
| `x = 10` | `false` |
| `x = 0` | `true` |
| `x = 12321` | `true` |

---

## 3. Roman to Integer
| Input | Expected Output |
|-------|-----------------|
| `"III"` | `3` |
| `"LVIII"` | `58` |
| `"MCMXCIV"` | `1994` |
| `"IV"` | `4` |
| `"IX"` | `9` |
| `"XL"` | `40` |

---

## 4. Longest Common Prefix
| Input | Expected Output |
|-------|-----------------|
| `["flower","flow","flight"]` | `"fl"` |
| `["dog","racecar","car"]` | `""` |
| `["interspecies","interstellar","interstate"]` | `"inters"` |
| `["a"]` | `"a"` |
| `[""]` | `""` |
| `[]` | `""` |

---

## 5. Valid Parentheses
| Input | Expected Output |
|-------|-----------------|
| `"()"` | `true` |
| `"()[]{}"` | `true` |
| `"(]"` | `false` |
| `"([)]"` | `false` |
| `"{[]}"` | `true` |
| `""` | `true` |
| `"["` | `false` |

---

## 6. Merge Two Sorted Lists
(Input lists are given as arrays; implementation should use linked list nodes.)
| Input `l1` | Input `l2` | Expected Output |
|------------|------------|-----------------|
| `[1,2,4]` | `[1,3,4]` | `[1,1,2,3,4,4]` |
| `[]` | `[]` | `[]` |
| `[]` | `[0]` | `[0]` |
| `[1,3,5]` | `[2,4,6]` | `[1,2,3,4,5,6]` |

---

## 7. Remove Duplicates from Sorted Array
| Input `nums` | Expected length | First `k` elements of `nums` (order preserved) |
|--------------|-----------------|-------------------------------------------------|
| `[1,1,2]` | `2` | `[1,2]` |
| `[0,0,1,1,1,2,2,3,3,4]` | `5` | `[0,1,2,3,4]` |
| `[]` | `0` | `[]` |
| `[1]` | `1` | `[1]` |
| `[1,1,1]` | `1` | `[1]` |

---

## 8. Implement strStr()
| `haystack` | `needle` | Expected Output |
|------------|----------|-----------------|
| `"hello"` | `"ll"` | `2` |
| `"aaaaa"` | `"bba"` | `-1` |
| `""` | `""` | `0` |
| `"abc"` | `""` | `0` |
| `"aaa"` | `"a"` | `0` |
| `"mississippi"` | `"issip"` | `4` |

---

## 9. Search Insert Position
| `nums` | `target` | Expected Output |
|--------|----------|-----------------|
| `[1,3,5,6]` | `5` | `2` |
| `[1,3,5,6]` | `2` | `1` |
| `[1,3,5,6]` | `7` | `4` |
| `[1,3,5,6]` | `0` | `0` |
| `[1]` | `0` | `0` |
| `[1]` | `1` | `0` |

---

## 10. Maximum Subarray
| `nums` | Expected Output |
|--------|-----------------|
| `[-2,1,-3,4,-1,2,1,-5,4]` | `6` |
| `[1]` | `1` |
| `[5,4,-1,7,8]` | `23` |
| `[-1,-2]` | `-1` |
| `[-5,-2,-3]` | `-2` |

---

## 11. Length of Last Word
| `s` | Expected Output |
|-----|-----------------|
| `"Hello World"` | `5` |
| `"   fly me   to   the moon  "` | `4` |
| `"luffy is still joyboy"` | `6` |
| `""` | `0` |
| `"a"` | `1` |
| `"a "` | `1` |

---

## 12. Plus One
| `digits` | Expected Output |
|----------|-----------------|
| `[1,2,3]` | `[1,2,4]` |
| `[4,3,2,1]` | `[4,3,2,2]` |
| `[9]` | `[1,0]` |
| `[9,9,9]` | `[1,0,0,0]` |
| `[0]` | `[1]` |

---

## 13. Add Binary
| `a` | `b` | Expected Output |
|-----|-----|-----------------|
| `"11"` | `"1"` | `"100"` |
| `"1010"` | `"1011"` | `"10101"` |
| `"0"` | `"0"` | `"0"` |
| `"1111"` | `"1111"` | `"11110"` |
| `"1"` | `"111"` | `"1000"` |

---

## 14. Sqrt(x)
| `x` | Expected Output |
|-----|-----------------|
| `4` | `2` |
| `8` | `2` |
| `0` | `0` |
| `1` | `1` |
| `2147395600` | `46340` |

---

## 15. Climbing Stairs
| `n` | Expected Output |
|-----|-----------------|
| `2` | `2` |
| `3` | `3` |
| `4` | `5` |
| `1` | `1` |
| `5` | `8` |

---

## 16. Remove Duplicates from Sorted List
| Input `head` | Expected Output |
|--------------|-----------------|
| `[1,1,2]` | `[1,2]` |
| `[1,1,2,3,3]` | `[1,2,3]` |
| `[]` | `[]` |
| `[1,1,1]` | `[1]` |
| `[1,2,2,3]` | `[1,2,3]` |

---

## 17. Merge Sorted Array
| `nums1` (initial) | `m` | `nums2` | `n` | Expected `nums1` after merge |
|-------------------|-----|---------|-----|------------------------------|
| `[1,2,3,0,0,0]` | `3` | `[2,5,6]` | `3` | `[1,2,2,3,5,6]` |
| `[1]` | `1` | `[]` | `0` | `[1]` |
| `[0]` | `0` | `[1]` | `1` | `[1]` |
| `[4,5,6,0,0,0]` | `3` | `[1,2,3]` | `3` | `[1,2,3,4,5,6]` |

---

## 18. Binary Tree Inorder Traversal
(Trees are given in level‑order; `null` indicates absence of node.)

| Input `root` | Expected Output |
|--------------|-----------------|
| `[1,null,2,3]` | `[1,3,2]` |
| `[]` | `[]` |
| `[1]` | `[1]` |
| `[1,2,3,4,5]` | `[4,2,5,1,3]` |

---

## 19. Same Tree
| Tree `p` | Tree `q` | Expected Output |
|----------|----------|-----------------|
| `[1,2,3]` | `[1,2,3]` | `true` |
| `[1,2]` | `[1,null,2]` | `false` |
| `[1,2,1]` | `[1,1,2]` | `false` |
| `[]` | `[]` | `true` |
| `[1]` | `[1,null,2]` | `false` |

---

## 20. Symmetric Tree
| Input `root` | Expected Output |
|--------------|-----------------|
| `[1,2,2,3,4,4,3]` | `true` |
| `[1,2,2,null,3,null,3]` | `false` |
| `[1]` | `true` |
| `[]` | `true` |

---

## 21. Maximum Depth of Binary Tree
| Input `root` | Expected Output |
|--------------|-----------------|
| `[3,9,20,null,null,15,7]` | `3` |
| `[1,null,2]` | `2` |
| `[]` | `0` |
| `[0]` | `1` |

---

## 22. Convert Sorted Array to BST
| Input `nums` | Expected Output (any height‑balanced BST) |
|--------------|-------------------------------------------|
| `[-10,-3,0,5,9]` | Inorder traversal must be `[-10,-3,0,5,9]`; tree height difference ≤1 |
| `[1,3]` | Either `[3,1]` or `[1,null,3]` – both balanced |
| `[1]` | `[1]` |
| `[]` | `[]` |

---

## 23. Balanced Binary Tree
| Input `root` | Expected Output |
|--------------|-----------------|
| `[3,9,20,null,null,15,7]` | `true` |
| `[1,2,2,3,3,null,null,4,4]` | `false` |
| `[]` | `true` |
| `[1]` | `true` |
| `[1,2,2,3,null,null,3,4,null,null,4]` | `false` |

---

## 24. Minimum Depth of Binary Tree
| Input `root` | Expected Output |
|--------------|-----------------|
| `[3,9,20,null,null,15,7]` | `2` |
| `[2,null,3,null,4,null,5,null,6]` | `5` |
| `[]` | `0` |
| `[1]` | `1` |
| `[1,2]` | `2` (leaf at 2) |

---

## 25. Path Sum
| Input `root` | `targetSum` | Expected Output |
|--------------|-------------|-----------------|
| `[5,4,8,11,null,13,4,7,2,null,null,null,1]` | `22` | `true` |
| `[1,2,3]` | `5` | `false` |
| `[]` | `0` | `false` |
| `[1,2]` | `1` | `false` |
| `[1]` | `1` | `true` |

---

## 26. Pascal's Triangle
| `numRows` | Expected Output |
|-----------|-----------------|
| `5` | `[[1],[1,1],[1,2,1],[1,3,3,1],[1,4,6,4,1]]` |
| `1` | `[[1]]` |
| `3` | `[[1],[1,1],[1,2,1]]` |
| `0` | `[]` (if allowed; otherwise 1 ≤ numRows) |

---

## 27. Best Time to Buy and Sell Stock
| `prices` | Expected Output |
|----------|-----------------|
| `[7,1,5,3,6,4]` | `5` |
| `[7,6,4,3,1]` | `0` |
| `[2,4,1]` | `2` |
| `[1]` | `0` |
| `[3,2,6,5,0,3]` | `4` (buy at 2, sell at 6) |

---

## 28. Valid Palindrome
| `s` | Expected Output |
|-----|-----------------|
| `"A man, a plan, a canal: Panama"` | `true` |
| `"race a car"` | `false` |
| `" "` | `true` |
| `"0P"` | `false` |
| `"a."` | `true` |

---

## 29. Single Number
| `nums` | Expected Output |
|--------|-----------------|
| `[2,2,1]` | `1` |
| `[4,1,2,1,2]` | `4` |
| `[1]` | `1` |
| `[-1,-1,2]` | `2` |
| `[1,0,1]` | `0` |

---

## 30. Linked List Cycle
(`pos` indicates the index (0‑based) of the node that the tail connects to; `-1` means no cycle.)

| `head` | `pos` | Expected Output |
|--------|-------|-----------------|
| `[3,2,0,-4]` | `1` | `true` |
| `[1,2]` | `0` | `true` |
| `[1]` | `-1` | `false` |
| `[]` | `-1` | `false` |
| `[1,2,3,4]` | `2` | `true` |