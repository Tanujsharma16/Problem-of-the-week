# Problem-of-the-week
 Problem of the Week – Week 1

Welcome to Week 1 of the **Problem of the Week** challenge!  
This week's problems are focused on core **DSA skills** and **interview-style thinking**. Below you'll find detailed solutions and explanations for each problem.

---

 1. Find Minimum in Rotated Sorted Array
 Problem Statement
Given a rotated sorted array without duplicates, find the minimum element.

 Approaches

 Approach 1: Brute Force
- Scan all elements and track the smallest.
- **Time Complexity**: O(n)  
- **Space Complexity**: O(1)

Approach 2: Binary Search
- Use mid and check direction using comparison with `nums[right]`.
- Efficient for large arrays.
- **Time Complexity**: O(log n)  
- **Space Complexity**: O(1)

---

 2. Subarray Sum Equals K
 Problem Statement
Find total number of continuous subarrays that sum up to a given integer `k`.

Approaches

Approach 1: Prefix Sum + HashMap
- Track running sum and count occurrences of `sum - k`.
- Best performance overall.
- **Time Complexity**: O(n)  
- **Space Complexity**: O(n)

 Approach 2: Brute Force
- Check all possible subarrays using nested loops.
- **Time Complexity**: O(n²)  
- **Space Complexity**: O(1)

Approach 3: Sliding Window (Positives Only)
- Use two pointers only if array contains positive numbers.
- **Time Complexity**: O(n)  
- **Space Complexity**: O(1)


- Each problem includes multiple approaches for better insight.
- Code is commented and structured for clarity.
- Sample inputs can be tested via the `main` method in relevant files.

Consistency > Intensity  


