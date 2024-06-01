# Welcome to Week 1 of Competitive Programming SOC 2k24

In this repository, you can find assignment for Week 1.

**Deadline for submission of this assignment: June 2, 2024, 11.59 p.m. IST**
<br><br><br><br>
# Disclaimer
All submissions will be subjected to plagiarism checks. Any instances of copying will result in immediate disqualification, and you will not receive a certificate for this Summer of Code (SOC) program. <br> **It is important that you fully understand the material you are submitting**.

Failure to comply with these guidelines will have serious consequences.

**And don't worry — if you focus on your own work and avoid looking at others' code, you won't be flagged for plagiarism. Each person has their own unique coding style.**<br>
**You can discuss among yourselves, but make sure that you don't share code among yourselves. That's it.**
<br><br><br><br>
# Week-1 Assignment
<br>
This assignment consists of 10 easy questions. Each student should submit their code in the format specified in the submission area.

**This is a standard assignment. Do not copy under any circumstances. If you try your best, you will be able to solve the problems. If you have any doubts, please do not hesitate to reach out to us.**

<br>

### 1. Think of an Optimal Solution
Given an integer array nums and an integer k, output the length of the shortest non-empty subarray whose sum is at least k. If there is no such subarray, output -1. <br>
*Subarray*: A subarray is a contiguous segment of an array. It is defined by selecting a starting index and an ending index within the original array and including all the elements between these two indices. <br>
**Expected Complexity**:<br>
O(n) solution is expected<br>
**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case contains two integers n and k. Where n is the size of the array.<br>
Second line contains n integers of the array<br>
**Output format**:<br>
For each testcase output a single integer as mentioned in the question in a new line<br>

**Input1**: nums = [1], n = 1, k = 1 <br>
**Output1**: 1 <br>
**Input2**: nums = [1, 2], n = 2, k = 4 <br>
**Output2**: -1 <br>
**Input3**: nums = [2, -1, 2], n = 3, k = 3<br>
**Output3**: 3 <br>
<br>

### 2. Valid Strings
Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.<br>
A string is valid if :<br>
1. Open brackets must be closed by the same type of brackets.
2. Open brackets must be closed in the correct order.
3. Every close bracket has a corresponding open bracket of the same type.

**Expected Complexity**:<br>
O(n) solution is expected<br>

**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
The only line of each test case contains a string s as described in the question.<br>
**Output format**:<br>
For each testcase output true if the string is valid else false in a new line<br>

**Input1:** s = "()"<br>
**Output1:** true<br>
**Input2:** s = "()[]{}"<br>
**Output2:** true<br>
**Input3:** s = "(]"<br>
**Output3:** false<br>
<br>

### 3. Arrays..
Given a 1-indexed array of integers numbers that is already sorted in **non-decreasing** order, find two numbers such that they add up to a specific target number. Let these two numbers be numbers[index1] and numbers[index2] where 1 <= index1 < index2 <= numbers.length.<br>
Output the indices of the two numbers, index1 and index2, added by one as an integer array [index1, index2] of length 2.<br>
The tests are generated such that there is exactly one solution. You may not use the same element twice.<br>
**Expected Complexity**:<br>
O(n) solution is expected<br>
**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case contains two integers n and target. Where n is the size of the array<br>
Second line of each test case contains n integers of the array.<br>
**Output format**:<br>
For each test case, output two integers separated by a space on a new line. Ensure each test case is output on a separate line.<br>

**Input:** numbers = [2,7,11,15], target = 9 <br>
**Output:** 1 2<br>
**Input:** numbers = [2,3,4], target = 6<br>
**Output:** 1 3<br>
**Input:** numbers = [-1,0], target = -1 <br>
**Output:** 1 2 <br>
<br>

### 4. Largest Sum - Kadane’s Algorithm
Given an array arr[] of size N. The task is to print the sum of the contiguous subarray within a arr[] with the largest sum. 
**Expected Complexity**:<br>
O(n) solution is expected<br>
**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case contains an integer n.<br>
Second line has n integers of the array.<br>
**Output format**:<br>
For each testcase output a single integer as mentioned above in a new line<br>


**Input:** N = 8, arr = {-2,-3,4,-1,-2,1,5,-3} <br>
**Output:** 7<br>
**Input:** N = 1, arr = {2}<br>
**Output:** 2<br>
<br>

### 5. More on Arrayss
Print indices of the two numbers of the array nums such that their sum is equal to the target. Otherwise print {-1, -1}.
**Expected Complexity**:<br>
O(nlogn) solution is expected<br>
**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case contains two integers n and target. Where n is the size of the array<br>
Second line of each test case contains n integers of the array.<br>
**Output format**:<br>
For each test case, output two integers separated by a space on a new line. Ensure each test case is output on a separate line.<br>

**Input:** $nums = [2,7,11,15], n = 4, target = 9$<br>
**Output:** 0 1 <br>
**Input:** nums = [3, 2, 4], n = 3, target = 6 <br>
**Output:** 1 2 <br>
**Input:** nums = [2, 10], n = 3, target = 60 <br>
**Output:** -1 -1 <br>
<br>

### 6. Rotationn
Given a sorted array (may be distinct or may contain duplicates) of size N that is rotated at some unknown point, the task is to print the minimum element in it.
**Expected Complexity**:<br>
O(logn) solution is expected<br>
**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case an integer n. Where n is the size of the array<br>
Second line contains n integers of the array.<br>
**Output format**:<br>
For each testcase output an integer as mentioned above in a new line<br>

**Input:** n = 6, arr[] = {5, 6, 1, 2, 3, 4} <br>
**Output:** 1<br>
**Input:** n = 4, arr[] = {1, 2, 3, 4}<br>
**Output:** 1<br>
<br>

### 7. Thala For A Reason
*Please read concept for basic bit manipulations before solving this question* <br>
Given an integer n, print number of integers ‘x’ such that:
1. $0<= x <= n.$
2. $n + x = n\  XOR\  x$
**Expected Complexity**:<br>
O(logn) solution is expected.Hint is no. of bits in n is O(logn) <br>

**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
The only line of each test case an integer n.<br>
**Output format**:<br>
For each testcase output an integer as mentioned above in a new line<br>


**Input**: $n=4$<br>
**Output**:4<br>
**Explination**:<br>
Following values of x satisfy the equation <br>
$4 \ XOR \ 0 = 4 \ + \ 0 = 4$ <br>
$4\  XOR\  1 = 4 \ + \ 1 = 5$ <br>
$4 \ XOR \ 2 = 4\  + \ 2 = 6$ <br>
$4 \ XOR \ 3 = 4\  + \ 3 = 7$ <br>
<br>
### 8. XOR XOR XOR XOR
Given an array of integers $arr$ and an integer $m$. Print the total number of subarrays having bitwise $XOR$ of all elements equal to $m$.

**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case contains two integers n and m. Where n is the size of the array<br>
Second line contains n integers of the array.<br>
**Output format**:<br>
For each testcase output an integer as mentioned above in a new line<br>

**Input:** $arr[] = {4, 2, 2, 6, 4}, m = 6 $<br>
**Output:** $4$ <br>
**Explanation:** The subarrays having XOR of their elements as $6$ are {4, 2}, {4, 2, 2, 6, 4}, {2, 2, 6} and {6}<br>
<br>

### 9. String.. String.. where are your substrings
Given a string of lowercase alphabets, print all possible substrings (not necessarily distinct) that have exactly k distinct characters.

**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case contains an integer k.<br>
Second line contains a string s.<br>
**Output format**:<br>
For each testcase output an integer as mentioned above in a new line<br>

**Input:** abc, k = 2 <br>
**Output:** 2<br>
Possible substrings are {“ab”, “bc”}<br>
<br>

### 10. You reached end orzz - Sliding window
You are given an array of integers, there is a **sliding window** of size $k$ which is moving from the very left of the array to the very right. You can only see the $k$ numbers in the window. Each time the sliding window moves right by one position. **Print an array containing maximum values in each window**

**Input Format**:<br>
Each test contains multiple test cases. The first line of input contains a single integer $t$ $1≤t≤100$ — the number of test cases. The description of the test cases follows.<br>
First line of each test case contains two integers n and k. Where n is the size of the array.<br>
Second line contains n integers of the array.<br>
**Output format**:<br>
For each test case, output the specified array elements separated by spaces, each on a new line. <br>

**Input:** arr[] = {1, 2, 3, 1, 4, 5, 2, 3, 6}, K = 3  <br>
**Output:** 3 3 4 5 5 5 6 <br>
**Explanation:**<br>
Maximum of 1, 2, 3 is 3 <br>
Maximum of 2, 3, 1 is 3<br>
Maximum of 3, 1, 4 is 4<br>
Maximum of 1, 4, 5 is 5<br>
Maximum of 4, 5, 2 is 5 <br>
Maximum of 5, 2, 3 is 5<br>
Maximum of 2, 3, 6 is 6<br>
<br><br>
# Submission format
A google form will be floated soon where you need to submit a **zip-file** with name **roll-number.zip** containing the files <br>*q1.cpp, q2.cpp, q3.cpp, q4.cpp, q5.cpp, q6.cpp, q7.cpp, q8.cpp, q9.cpp and q10.cpp* your solutions for the above 10 questions respectively.<br>
