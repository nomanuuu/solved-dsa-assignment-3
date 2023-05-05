Download Link: https://assignmentchef.com/product/solved-dsa-assignment-3
<br>
<strong><u>PROBLEM 1: </u>Implementation of suffix array</strong>

<strong>AIM: </strong>Implement a Suffix Array that is capable of performing following operations on Strings in a most efficient way.

<ol>

 <li>Given a string S print its minimum lexicographic rotation. <strong>O(nlogn)</strong></li>

 <li>Given an integer K, print the length of the longest substring that appears in the text at least K times.If no such substring exist, print -1. <strong>O(nlogn)</strong></li>

 <li>Given a strings S determine its longest substring that is also a palindrome. In the case of multiple solutions, print the lexicographically smallest palindrome. <strong>O(nlogn)</strong></li>

</ol>

<strong>EXAMPLE: </strong>

<strong>Input String: S = “dcabca” </strong>

<ol>

 <li>All possible rotation are “dcabca” , “cabcad” , “abcadc” , “bcadca” , “cadcab” , “adcabc”.</li>

</ol>

Among all lexicographically minimum is “abcadc” .

<ol start="2">

 <li>If K=2 than since “ca” is a substring that appears twice and its length is 2, so the answer is 2</li>

 <li>Since only length 1 substring are palindromic, and among them “a” is lexicographically smallest, hence answer is “a”.</li>

</ol>

<strong>INPUT FORMAT:  You will be given a large string S (length &lt;= 10 ^5 ). Print the corresponding output for each case Q1a, Q1b and Q1c. </strong>

<strong>Constraints: </strong>

<ul>

 <li>1 &lt;= String length &lt;= 10^5</li>

 <li>String consist of either Lower/Upper Case Alphabet and Numeric digits.</li>

</ul>

<strong>Submission Format:</strong> <strong>For each subpart implement a different code. Submit it as rollnumber_Q1a.cpp, rollnumber_Q1b.cpp, rollnumber_Q1c.cpp. We will run each file separately.</strong>

<strong><u>PROBLEM 2:</u> Trie Implementation</strong>

<strong>AIM: </strong>Given an array A of N numbers, you will be given q queries. Each query will contain a single integer x. You have to find then maximum xor of x from any number in A.

<strong>Constraints:</strong>

<ul>

 <li>1 &lt;= N, q &lt;= 10 ^ 5</li>

 <li>1 &lt;= A[i] &lt;= 10 ^ 12</li>

</ul>

<strong>INPUT: </strong>

First Line contains N and q

Second line contains N space separated intergers. Next q lines contain q queries of single integer

<strong>Example:</strong>

<strong>3 2</strong>

<strong>1 2 3</strong>

<strong>4</strong>

<strong>5</strong>

A = {1, 2, 3}

Case 1: x = 4 Maximum xor of x is with 3, therefore answer is 4 xor 3 = 7

Case 2: x = 5 Maximum xor of x is with 2, therefore answer is 5 xor 2 = 7

<strong>Submission Format: Submit it as rollnumber_Q2.cpp</strong>

<strong><u>PROBLEM 3: </u>External Sorting </strong>

<strong>AIM:</strong> External Sorting is a class of algorithms used to deal with massive amounts of data that do not fit in memory.

The question aims at implementing one such type: K-Way merge sort algorithm to sort a very large array. This algorithm is a perfect example of the use of divide and conquer where with limited resources large problems are tackled by breaking the problem space into small computable subspaces and then operations are done on them.

<strong>Input Constraints:</strong>

<ol>

 <li>A file containing a large unsorted list of integers (Will not fit in your usual Laptop</li>

</ol>

RAM).

2.Do not use any in-built data structures.

<strong>Output:</strong> A file containing non-Descending sorted list of the given integers

<strong>Evaluation parameters : </strong>

<ol>

 <li>Time and Space Complexity of the algorithm</li>

 <li>Efficient use of Data-Structures</li>

</ol>

<strong>Input Format:</strong> Your code should take two arguments.

<ul>

 <li>First is the name of input file.</li>

 <li>Second is name of output file.</li>

 <li>Example Format: If your input file is at ./data/input.txt And if you need your output file at ./data/ named output.txt</li>

</ul>

For c++, code should be of format rollnumber_Q3.cpp <strong>compiled file should accept two arguments ./a.out “./data/input.txt” “./data/output.txt”</strong>

<strong>Generation of unsorted file: </strong>

<strong>To generate the unsorted file, python script is uploaded along with this pdf. It contains all the instructions required to run it.</strong>

<strong>Submission format: Submit it as rollnumber_Q3.cpp</strong>