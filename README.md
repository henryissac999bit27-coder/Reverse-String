# [344. Reverse String](https://leetcode.com)

## Problem Description
Write a function that reverses a string. The input string is given as an array of characters `s`.
You must do this by modifying the input array **in-place** with **O(1)** extra memory.

## My Approach: Two-Pointer Technique
To reverse the array in-place, I used two pointers:
1.  **Left pointer (`i`)**: Starts at the beginning (index 0).
2.  **Right pointer (`j`)**: Starts at the end (index `s.length - 1`).

I swap the characters at these positions and move the pointers toward each other until they meet in the middle.

### Complexity
- **Time Complexity**: $O(N)$, where $N$ is the length of the array. Each element is swapped at most once.
- **Space Complexity**: $O(1)$, as we only use a single temporary variable for swapping.
