# Welcome to Week 1 of Competitive Programming SOC 2k24

In this repository, you can find assignments for Week 1.

**Deadline for submission of this assignment: June 1, 2024, 11.59 p.m. IST **
<br><br><br><br>
# Disclaimer
All submissions will be subjected to plagiarism checks. Any instances of copying will result in immediate disqualification, and you will not receive a certificate for this Summer of Code (SOC) program. <br> **It is important that you fully understand the material you are submitting**.

Failure to comply with these guidelines will have serious consequences.

**And don't worry — if you focus on your own work and avoid looking at others' code, you won't be flagged for plagiarism. Each person has their own unique coding style. **<br>
**You can discuss among yourselves, but make sure that you don't share code among yourselves. That's it.
<br><br><br><br>
# Week-1 Assignment
<br>
This assignment consists of 10 easy questions. Each student should submit their code in the format specified in the submission area. <br>
**This is a standard assignment. Do not copy under any circumstances. If you try your best, you will be able to solve the problems. If you have any doubts, please do not hesitate to reach out to us. **

<br>

### 1. Think of an Optimal Solution
Given an integer array and an integer k, return the length of the shortest non-empty subarray whose sum is at least k. If there is no such subarray, return -1. <br>
*Subarray*: A subarray is a contiguous segment of an array. It is defined by selecting a starting index and an ending index within the original array and including all the elements between these two indices. <br>

**Input1**: nums = [1], k = 1 <br>
**Output1**: 1 <br>
**Input2**: nums = [1, 2], k = 4 <br>
**Output2**: -1 <br>
**Input3**: nums = [2, -1, 2], k = 3<br>
**Output3**: 3 <br>
<br>
### 2. Valid Strings
Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.<br>
A string is valid if :<br>
1. Open brackets must be closed by the same type of brackets.
2. Open brackets must be closed in the correct order.
3. Every close bracket has a corresponding open bracket of the same type.


**Input1:** s = "()"<br>
**Output1:** true<br>
**Input2:** s = "()[]{}"<br>
**Output2:** true<br>
**Input3:** s = "(]"<br>
**Output3:** false<br>
<br>
### 3. Arrays..
Given a 1-indexed array of integers numbers that is already sorted in non-decreasing order, find two numbers such that they add up to a specific target number. Let these two numbers be numbers[index1] and numbers[index2] where 1 <= index1 < index2 <= numbers.length.<br>
Return the indices of the two numbers, index1 and index2, added by one as an integer array [index1, index2] of length 2.<br>
The tests are generated such that there is exactly one solution. You may not use the same element twice.<br>

**Input:** numbers = [2,7,11,15], target = 9 <br>
**Output:** [1,2]<br>
**Input:** numbers = [2,3,4], target = 6<br>
**Output:** [1,3]<br>
**Input:** numbers = [-1,0], target = -1 <br>
**Output:** [1,2] <br>
<br>
### 4. Largest Sum - Kadane’s Algorithm
Given an integer array, find the contiguous subarray (containing at least one number) which has the largest sum return its sum and prints the subarray.

**Input:** arr = {-2,-3,4,-1,-2,1,5,-3} <br>
**Output:** 7<br>
**Input:** arr = {2}<br>
**Output:** 2<br>
<br>
### 5. More on Arrayss
Return indices of the two numbers such that their sum is equal to the target. Otherwise, we will return {-1, -1}.

**Input:** $nums = [2,7,11,15], target = 9$<br>
**Output:** [0,1] <br>
**Input:** nums = [3, 2, 4], target = 6 <br>
**Output:** [1,2] <br>
<br>
### 6. Rotationn
Given an integer array of size N, sorted in ascending order (with distinct values). Now the array is rotated between 1 to N times which is unknown. Find the minimum element in the array

**Input:** arr[] = {5, 6, 1, 2, 3, 4} <br>
**Output:** 1<br>
**Input:** arr[] = {1, 2, 3, 4}<br>
**Output:** 1<br>
<br>
### 7. Thala For A Reason
*Please read concept for basic bit manipulations before solving this question* <br>
Given an integer n, find number of integers ‘x’ such that:
1. $0<= x <= n.$
2. $n + x = n\  XOR\  x$

**Input**: $n=5$<br>
**Output**:4<br>
Following values of x satisfy the equation <br>
$5 \ XOR \ 0 = 5 \ – \ 0 = 5$ <br>
$5\  XOR\  1 = 5 \ – \ 1 = 4$ <br>
$5 \ XOR \ 4 = 5\  – \ 4 = 1$ <br>
$5 \ XOR \ 5 = 5\  – \ 5 = 0$ <br>
<br>
### 8. XOR XOR XOR XOR
Given an array of integers $A$ and an integer $B$. Find the total number of subarrays having bitwise $XOR$ of all elements equal to $k$.

**Input:** $arr[] = {4, 2, 2, 6, 4}, m = 6 $<br>
**Output:** $4$ <br>
**Explanation:** The subarrays having XOR of their elements as $6$ are {4, 2}, {4, 2, 2, 6, 4}, {2, 2, 6} and {6}<br>
<br>
### 9. String.. String.. where are your substrings
Given a string of lowercase alphabets, count all possible substrings (not necessarily distinct) that have exactly k distinct characters.

**Input:** abc, k = 2 <br>
**Output:** 2<br>
Possible substrings are {“ab”, “bc”}<br>
<br>
### 10. You reached end orzz - Sliding window
You are given an array of integers, there is a **sliding window** of size $k$ which is moving from the very left of the array to the very right. You can only see the $k$ numbers in the window. Each time the sliding window moves right by one position. **Return an array containing maximum values in each window**

**Input:** arr[] = {1, 2, 3, 1, 4, 5, 2, 3, 6}, K = 3  <br>
**Output:** 3 3 4 5 5 5 6 <br>
**Explanation:** Maximum of 1, 2, 3 is 3 <br>
                Maximum of 2, 3, 1 is 3<br>
                Maximum of 3, 1, 4 is 4<br>
                       Maximum of 1, 4, 5 is 5<br>
                       Maximum of 4, 5, 2 is 5 <br>
                       Maximum of 5, 2, 3 is 5<br>
                       Maximum of 2, 3, 6 is 6<br>
<br><br>
# Submission format
A google form will be floated soon where you need to submit a **zip-file** with name **roll-number.zip** containing the files <br>*q1.cpp, q2.cpp, q3.cpp, q4.cpp, q5.cpp, q6.cpp, q7.cpp, q8.cpp, q9.cpp and q10.cpp* your solutions for the above 10 questions respectively.<br>