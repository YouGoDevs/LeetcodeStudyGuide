# Leetcode Study Guide

This guide aims to *comprehensively* prepare you for Leetcode (algorithms/data structures) interviews. 

## Prerequisite Knowledge
- Learn these data structures: array, linked list, hash table, matrix, stack, heap, graph, tree.
  - For each of these, what happens conceptually when you add, remove, and select an item?
- Big-O notation
  - Know both time and space complexity
  - For example, a “for” loop takes O(n) time. An array takes O(n) space.
  - For each of the above data structures, learn the time complexity of adding, removing, and selecting an item 
- Sorting algorithms
  - Bubble sort, insertion sort, selection sort, merge sort, quick sort
  - Know and understand how they work, and the time and space complexity for each

## Study Guide
Taken from [Danny’s Discord group](https://discord.com/channels/739845668582981683/739845892579786822/942949178055733298) & modified.

**Consistency.** These problems are conceptually difficult and take time for our brains to digest. Doing 1 problem a day for a month is superior to doing 30 problems in 3 days. Also, focus on learning the problem-solving techniques, rather than memorizing specific problems.

**One step at a time.** Do the Easy problems first. It might take two hours to finish your first Easy problem, or you might just give up and look at the solution. That's okay. Once you can do Easy in about 5 minutes, start on Medium. Repeat. But don't worry about Hard, you probably won't ever need it.

**RTFM.** Read the docs/spec for your programming language of choice. Learn how common data structures are implemented. Learn how libraries are implemented. Learn default settings and how they might affect performance. The more expertise you have in your chosen language, the more impressed your interviewers will be. **Note: Most interviews today are done in Python, regardless of the language used on the job, because it is concise and easy to learn.**

**Draw it out.** It can help to use a pen and paper to draw diagrams. (For some data structures like linked lists, drawing out diagrams **really** helps.)

**Practice thinking out loud.** While you're doing coding problems, practice explaining your approach (out loud). Explain why you're making the choices you are and why you're not making other choices.

**Practice iterating on your solution.** Once you solve a problem, before you look at others' solutions, look at your own solution with a critical eye. How could it be made "better"? Could it be made more readable? More efficient? Shorter? Better organized? Better variable names? Lots of these work against each other, so play around with different paths and see what feels best to you. Practice justifying your choices out loud.

**Read others' solutions.** Once you submit your solution, most sites will show you other users' solutions. Don't just go to the next problem. Spend at least a few minutes reading others' solutions and understanding them. Think of whether their solution is better or worse than yours. Also, make sure that your solution has the best time and space complexity possible - sometimes this isn't obvious.

**Test your code without an IDE.** Stay away from the "run my code" button when solving problems if you can. One way to be confident your code will work is to run through a test case or two (again, out loud). Pick test data that's short enough to get through in <5 minutes, but still exercises each branch of your code. Use multiple simple cases when needed. Finally, briefly discuss edge cases and how your code will handle them. For example, if the input is an array of integers, what happens if the array is empty? Or only contains one single element? What about all positives, all negatives, all 0s, max and min integers?

**Analyze the runtime of your solution.** Determine the Big-O complexity of your code, for both time and space.

**Time yourself and pace yourself.** Once you've done a few problems, simulate the time pressure in an interview. Most interviews will require you to completely finish the problem in about 30 minutes, but clarify this beforehand. Keep checking the clock to make sure you're pacing yourself properly. Here's how you can utilize the 30 minutes:
- Spend the first 5 minutes clarifying the problem and how it should handle edge cases.
- Then spend up to 15 minutes on the algorithm, discussing the approach with your interviewer.
- Only once you're certain of what to write, spend 5 minutes coding the solution.
- Spend the last 5 minutes on test cases and fixing bugs.


## Practice Problems
Source: https://us.teamblind.com/s/OaM1orEU. Remember, do the Easy ones first.

### Array

- Two Sum - https://leetcode.com/problems/two-sum/
- Best Time to Buy and Sell Stock - https://leetcode.com/problems/best-time-to-buy-and-sell-stock/
- Contains Duplicate - https://leetcode.com/problems/contains-duplicate/
- Product of Array Except Self - https://leetcode.com/problems/product-of-array-except-self/
- Maximum Subarray - https://leetcode.com/problems/maximum-subarray/
- Maximum Product Subarray - https://leetcode.com/problems/maximum-product-subarray/
- Find Minimum in Rotated Sorted Array - https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/
- Search in Rotated Sorted Array - https://leetcode.com/problems/search-in-rotated-sorted-array/
- 3Sum - https://leetcode.com/problems/3sum/
- Container With Most Water - https://leetcode.com/problems/container-with-most-water/

### Tree

- Maximum Depth of Binary Tree - https://leetcode.com/problems/maximum-depth-of-binary-tree/
- Same Tree - https://leetcode.com/problems/same-tree/
- Invert/Flip Binary Tree - https://leetcode.com/problems/invert-binary-tree/
- Binary Tree Maximum Path Sum - https://leetcode.com/problems/binary-tree-maximum-path-sum/
- Binary Tree Level Order Traversal - https://leetcode.com/problems/binary-tree-level-order-traversal/
- Serialize and Deserialize Binary Tree - https://leetcode.com/problems/serialize-and-deserialize-binary-tree/
- Subtree of Another Tree - https://leetcode.com/problems/subtree-of-another-tree/
- Construct Binary Tree from Preorder and Inorder Traversal - https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/
- Validate Binary Search Tree - https://leetcode.com/problems/validate-binary-search-tree/
- Kth Smallest Element in a BST - https://leetcode.com/problems/kth-smallest-element-in-a-bst/
- Lowest Common Ancestor of BST - https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/
- Implement Trie (Prefix Tree) - https://leetcode.com/problems/implement-trie-prefix-tree/
- Add and Search Word - https://leetcode.com/problems/add-and-search-word-data-structure-design/
- Word Search II - https://leetcode.com/problems/word-search-ii/

### Binary

- Sum of Two Integers - https://leetcode.com/problems/sum-of-two-integers/
- Number of 1 Bits - https://leetcode.com/problems/number-of-1-bits/
- Counting Bits - https://leetcode.com/problems/counting-bits/
- Missing Number - https://leetcode.com/problems/missing-number/
- Reverse Bits - https://leetcode.com/problems/reverse-bits/

### Graph

- Clone Graph - https://leetcode.com/problems/clone-graph/
- Course Schedule - https://leetcode.com/problems/course-schedule/
- Pacific Atlantic Water Flow - https://leetcode.com/problems/pacific-atlantic-water-flow/
- Number of Islands - https://leetcode.com/problems/number-of-islands/
- Longest Consecutive Sequence - https://leetcode.com/problems/longest-consecutive-sequence/
- Alien Dictionary (Leetcode Premium) - https://leetcode.com/problems/alien-dictionary/
- Graph Valid Tree (Leetcode Premium) - https://leetcode.com/problems/graph-valid-tree/
- Number of Connected Components in an Undirected Graph (Leetcode Premium) - https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/

### Interval

- Insert Interval - https://leetcode.com/problems/insert-interval/
- Merge Intervals - https://leetcode.com/problems/merge-intervals/
- Non-overlapping Intervals - https://leetcode.com/problems/non-overlapping-intervals/
- Meeting Rooms (Leetcode Premium) - https://leetcode.com/problems/meeting-rooms/
- Meeting Rooms II (Leetcode Premium) - https://leetcode.com/problems/meeting-rooms-ii/

### Linked List

- Reverse a Linked List - https://leetcode.com/problems/reverse-linked-list/
- Detect Cycle in a Linked List - https://leetcode.com/problems/linked-list-cycle/
- Merge Two Sorted Lists - https://leetcode.com/problems/merge-two-sorted-lists/
- Merge K Sorted Lists - https://leetcode.com/problems/merge-k-sorted-lists/
- Remove Nth Node From End Of List - https://leetcode.com/problems/remove-nth-node-from-end-of-list/
- Reorder List - https://leetcode.com/problems/reorder-list/

### Matrix

- Set Matrix Zeroes - https://leetcode.com/problems/set-matrix-zeroes/
- Spiral Matrix - https://leetcode.com/problems/spiral-matrix/
- Rotate Image - https://leetcode.com/problems/rotate-image/
- Word Search - https://leetcode.com/problems/word-search/

### String

- Longest Substring Without Repeating Characters - https://leetcode.com/problems/longest-substring-without-repeating-characters/
- Longest Repeating Character Replacement - https://leetcode.com/problems/longest-repeating-character-replacement/
- Minimum Window Substring - https://leetcode.com/problems/minimum-window-substring/
- Valid Anagram - https://leetcode.com/problems/valid-anagram/
- Group Anagrams - https://leetcode.com/problems/group-anagrams/
- Valid Parentheses - https://leetcode.com/problems/valid-parentheses/
- Valid Palindrome - https://leetcode.com/problems/valid-palindrome/
- Longest Palindromic Substring - https://leetcode.com/problems/longest-palindromic-substring/
- Palindromic Substrings - https://leetcode.com/problems/palindromic-substrings/
- Encode and Decode Strings (Leetcode Premium) - https://leetcode.com/problems/encode-and-decode-strings/

### Heap

- Merge K Sorted Lists - https://leetcode.com/problems/merge-k-sorted-lists/
- Top K Frequent Elements - https://leetcode.com/problems/top-k-frequent-elements/
- Find Median from Data Stream - https://leetcode.com/problems/find-median-from-data-stream/

### Dynamic Programming

Do these last. Many companies don't ask them anymore.

- Climbing Stairs - https://leetcode.com/problems/climbing-stairs/
- Coin Change - https://leetcode.com/problems/coin-change/
- Longest Increasing Subsequence - https://leetcode.com/problems/longest-increasing-subsequence/
- Longest Common Subsequence - 
- Word Break Problem - https://leetcode.com/problems/word-break/
- Combination Sum - https://leetcode.com/problems/combination-sum-iv/
- House Robber - https://leetcode.com/problems/house-robber/
- House Robber II - https://leetcode.com/problems/house-robber-ii/
- Decode Ways - https://leetcode.com/problems/decode-ways/
- Unique Paths - https://leetcode.com/problems/unique-paths/
- Jump Game - https://leetcode.com/problems/jump-game/
