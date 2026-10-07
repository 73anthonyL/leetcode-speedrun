# leetcode-speedrun

My LeetCode solutions in Python 3, grouped by difficulty.

<!-- TODO: one line on what "speedrun" means for you (timed solves? a target pace? a topic order?) -->

## Structure

```
leetcode-speedrun/
├── easy/       # 21 Easy solutions, one file per problem
└── README.md
```

Each file is named after the problem title in PascalCase and uses LeetCode's `Solution` class format. Medium and hard folders will be added as I get to them.

## Solutions

### Easy

| # | Problem | Topic |
|---|---------|-------|
| 1 | [Two Sum](easy/TwoSum.py) | Array, Hash Table |
| 9 | [Palindrome Number](easy/PalindromeNumber.py) | Math |
| 13 | [Roman to Integer](easy/RomanToInteger.py) | Hash Table, String |
| 14 | [Longest Common Prefix](easy/LongestCommonPrefix.py) | String |
| 20 | [Valid Parentheses](easy/ValidParentheses.py) | Stack, String |
| 21 | [Merge Two Sorted Lists](easy/MergeTwoSortedLists.py) | Linked List |
| 26 | [Remove Duplicates from Sorted Array](easy/RemoveDuplicatesFromSortedArray.py) | Two Pointers |
| 27 | [Remove Element](easy/RemoveElement.py) | Two Pointers |
| 35 | [Search Insert Position](easy/SearchInsertPosition.py) | Binary Search |
| 67 | [Add Binary](easy/AddBinary.py) | Math, String |
| 69 | [Sqrt(x)](easy/SqrtX.py) | Binary Search, Math |
| 70 | [Climbing Stairs](easy/ClimbingStairs.py) | Dynamic Programming |
| 83 | [Remove Duplicates from Sorted List](easy/RemoveDuplicatesFromSortedList.py) | Linked List |
| 88 | [Merge Sorted Array](easy/MergedSortedArray.py) | Two Pointers |
| 94 | [Binary Tree Inorder Traversal](easy/BinaryTreeInorderTraversal.py) | Tree, DFS |
| 100 | [Same Tree](easy/SameTree.py) | Tree, DFS |
| 101 | [Symmetric Tree](easy/SymmetricTree.py) | Tree, DFS/BFS |
| 104 | [Maximum Depth of Binary Tree](easy/MaximumDepthOfBinaryTree.py) | Tree, DFS |
| 108 | [Convert Sorted Array to Binary Search Tree](easy/ConvertSortedArrayToBinarySearchTree.py) | Tree, Divide and Conquer |
| 110 | [Balanced Binary Tree](easy/BalancedBinaryTree.py) | Tree, DFS |
| 111 | [Minimum Depth of Binary Tree](easy/MinimumDepthOfBinaryTree.py) | Tree, DFS/BFS |

## Running a solution

Solutions are written in LeetCode's format (a `Solution` class with the problem's method), so to test one locally you'll need to define `TreeNode` or `ListNode` where the problem uses them, or paste the code into LeetCode.
