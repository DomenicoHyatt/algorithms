  Algorithms
My personal Java practises for some well-studied algorithms and problems commonly asked in technical interviews

## My Solutions
* Given a number, return all possible strings that the number could represent if `0 -> {A, B, C}, 2 -> {D, E, F}`, and so on. (Modified from [*Original question*](http://www.glassdoor.com/Interview/phone-numbers-provided-a-phone-number-654-876-0987-return-all-possible-strings-that-the-phone-number-could-represent-QTN_361642.htm)) Solutions: [**Java**](Java/AllPossibleStrings.java)
* You have a room-full of balances and weights. Each balance weighs ten pounds and is considered perfectly balanced when the sum of weights on its left and right sides are exactly the same. You have placed some weights on some of the balances, and you have placed some of the balances on other balances. Given a description of how the balances are arranged and how much additional weight is on each balance, determine how to add weight to the balances so that they are all perfectly balanced. ([*Original question*](http://www.careercup.com/question?id=12150672)) Solutions: [**Java**](Java/Balance.java)
* Algorithms on binary trees ([**Java**](Java/BinaryTree.java)). Comprises of the following algorithms:  
  * Given a node value, finds the node in tree using dfs
  * Pre-order traversal
  * In-order traversal
  * Post-order traversal
  * Checks if tree is a BST
  * Gets the height of the BST
  * Checks if the tree is height balanced
  * Determines the Lowest Common Ancestor (LCA) of two nodes
  * Prints the tree level wise using BFS
  * Prints the average value for each level in tree
  * Determines the in-order successor for a node
* Suppose there are 5 types of coins: 50-cent, 25-cent, 10-cent, 5-cent, and 1-cent. Write a program to find the total number of different ways of making changes for any amount of money in cents. ([*Original question*](http://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=615)) Solutions: [**Java**](Java/CoinChange.java)
* Let 1 represent ‘A’, 2 represents ‘B’, etc. Given a digit sequence, count the number of possible decodings of the given digit sequence. ([*Original question*](http://www.geeksforgeeks.org/count-possible-decodings-given-digit-sequence/)) Solutions: [**Java**](Java/CountPossibleDecodings.java)
* Given a number, obtain the next larger permutation and next lower permutation by swapping around the digits in the number. Solutions: [**Java**](Java/DigitPermutations.java)
* Implement Fibonacci in bottom-up dynamic programming fashion. Solutions: [**Java**](Java/Fibonacci.java)
* Given n stairs, how many number of ways can you climb if u use either 1 or 2 at a time? ([*Original question*](http://www.careercup.com/question?id=3590768)) Solutions: [**Java**](Java/FibonacciSteps.java)
* Solve the “FizzBuzz” problem (*needs no introduction*). Solutions: [**Java**](Java/FizzBuzz.java)
* Implement Conway's game of life by predicting the next state of a matrix given its current state. Solutions: [**Java**](Java/GameOfLife.java)
* Algorithms on Graphs ([**Java**](Java/Graph.java)). Comprises of the following algorithms:
  * BFS
  * DFS
  * Kruskal (MST)
  * Prim (MST)
  * Modified Dijkstra (SSSP)
  * Bellman-Ford (SSSP)
  * Floyd-Warshall (APSP)
* You are given an M by N matrix containing only the characters 'P' and 'T'. You can flip the characters in any number of columns. I.e. 'P' becomes 'T' and 'T' becomes 'P' for all characters under that column. Your aim is to maximize the number of rows for which all the characters are the same.Solutions:  [**Java**](Java/HomogeneousRows.java)
* Implement integer division without using `/` or `%` in O(logN). Solutions: [**Java**](Java/IntegerDivision.java)
* You are given a binary array with N elements: `d[0], d[1], ... d[N - 1]`. You can perform AT MOST one move on the array: choose any two integers and flip all the elements between (and including) them. What is the maximum number of '1'-bits which you can obtain in the final bit-string? ([*Original question*](http://www.careercup.com/question?id=6262507668766720)) Solutions: [**Java**](Java/KadaneBitFlip.java)
* Implement Karatsuba's multiplication algorithm. *(Just a practice. No way this question will be tested)* Solutions: [**Java**](Java/Karatsuba.java)
* Implement Knuth shuffle. Solutions: [**Java**](Java/KnuthShuffle.java)
* Given two strings, find the Longest Common Subsequence between them. Solutions: [**Java**](Java/LongestCommonSubsequence.java)
* Given two strings, find the Longest Common Substring between them. Solutions: [**Java**](Java/LongestCommonSubstring.java)
* Given an array of integers, find the Longest Increasing Subsequence of its items. Solutions: [**Java**](Java/LongestIncreasingSubsequence.java)
* Given two strings, find the Longest Palindromic Subsequence between them. Solutions: [**Java**](Java/LongestPalindromicSubsequence.java)
* Given two strings, find the Longest Palindromic Substring between them. Solutions: [**Java**](Java/LongestPalindromicSubstring.java)
* Implement Kadane's algorithm, returning the maximum subarray sum as well as the start and end indexes representing the maximum subarray. Solutions:  [**Java**](Java/MaximumSubarray.java)
* Implement merge sort. Solutions: [**Java**](Java/MergeSort.java)
* Implement a data structure that supports "find minimum" on top of the other stack operations "push" and "pop" in O(1). Space Complexity for finding minimum element should be O(1) Solutions: [**Java**](Java/MinimumStack.java)
* Given a sorted list of numbers, write a function to return a string representing the missing numbers from 0 to 99 inclusive. ([*Original question*](https://leetcode.com/problems/missing-ranges/)) Solutions: [**Java**](Java/MissingRanges.java)
* You have an array containing information regarding n people. Each person is described using a string (their name) and a number (their position along a number line). Each person has three friends, which are the three people whose number is nearest to their own. Describe an algorithm to identify each person's three friends. ([*Original question*](http://algogeeks.narkive.com/SakzFz8P/nearest-neighbour)) Solutions: [**Java**](Java/NearestNeighbors.java)
* Write a function `strstr (char[] haystack, char[] needle)` to return the first index occurrence of needle in haystack. If needle is not present in haystack, return -1. ([*Original question*](http://www.programcreek.com/2012/12/leetcode-implement-strstr-java/)) Solutions: [**Java**](Java/NeedleHaystack.java)
* Implement numeric addition of two numbers in both decimal as well as binary. Solutions: [**Java**](Java/NumericAddition.java)
* An array is given consisting of integer numbers. Each number except one appears exactly twice. The remaining number appears only once in the array. Write a function which returns a number which appears only once in the array. What if we have a different array where every number appears thrice except one number which appear once?. Solutions: [**Java**](Java/OddManOut.java)
* [**Order Statistics**](Java/OrderStatistics.java). Comprises of the following algorithms:
  * Kth smallest
  * median
* Implement a queue using 2 stacks. Solutions: [**Java**](Java/QueueStack.java)
* Implement quick sort. Solutions: [**Java**](Java/QuickSort.java)
* A kidnaper wishes to write a ransom note using letters from a magazine article. You are given with the ransom note and magazine article find whether kidnaper can write a note using the article or not. ([*Original question*](http://www.careercup.com/question?id=67086)) Solutions: [**Java**](Java/RansomNote.java)
* Reverse an array in-place. Solutions: [**Java**](Java/ReverseArray.java)
* Reverse the order of words in a sentence, but keep words themselves unchanged. Words in a sentence are divided by blanks. For instance, the reversed output should be `"student. a am I"` when the input is `"I am a student."`. ([*Original question*](http://www.geeksforgeeks.org/reverse-words-in-a-given-string/)) Solutions: [**Java**](Java/ReverseWords.java)
* Given a matrix, rotate it clockwise by 90 degrees. Solutions: [**Java**](Java/RotateMatrix.java)
* [**Algorithms for set operations**](Java/SetOperations.java). Comprises of the following operations:
  * Intersection of two lists
  * Union of two lists
  * n-way intersection of n lists
* Given two sorted arrays and a number k, find the kth largest number in the union of the two arrays. Do it in place. Solutions: [**Java**](Java/SortedArrayUnion.java)
* Implement square-root method wihtout using the Math library. Solutions: [**Java**](Java/Sqrt.java) [**Python**](Python/sqrt.py)
* One steps through integer points of the straight line. The length of a step must be nonnegative and can be by one bigger than, equal to, or by one smaller than the length of the previous step. What is the minimum number of steps in order to get from x to y? The length of the first and the last step must be 1. ([*Original question*](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=787)) Solutions: [**Java**](Java/Steps.java)
* Given a string `"aaabbbcc"`, compress it into `"a3b3c2"` in-place. ([*Original question*](http://www.careercup.com/question?id=7449675)) Solutions:  [**Java**](Java/StringCompression.java)
* Given a string, print out all its permutations. Solutions: [**Java**](Java/StringPermutations.java)
* Write a function that parses a string into integer. Solutions: [**Java**](Java/StringToInteger.java)
* Given an array of integers, return all possible subsets of length n. Solutions: [**Java**](Java/SubsetsN.java)
* Given an n*m matrix, for each cell, calculate the sum of values in its implicit sub-matrix where the top-left coordinate is (0, 0) and bottom right corner is the cell itself. Can you do it in-place? ([*Original question*](http://stackoverflow.com/questions/2277749/calculate-the-sum-of-elements-in-a-matrix-efficiently)) Solutions: [**Java**](Java/SummedAreaTable.java)
* Given an array and a number n, can you obtain n using a 2 numbers in the array? What about 3 numbers? Solutions: [**Java**](Java/TargetSum.java)
* Implement a deep-copy method for the class Thing which has a list of Thing objects. Solutions: [**Java**](Java/Thing.java)
* Given a string, write a function which prints all the subsets of the string.  Now make the function to return only unique solutions. Solutions:  [**Java**](Java/UniqueStringSubsets.java)
* Given an input string and a dictionary of words, segment the input string into a space-separated sequence of dictionary words if possible. For example, if the input string is `"applepie"` and dictionary contains a standard set of English words, then we would return the string `"apple pie"` as output. ([*Original question*](http://thenoisychannel.com/2011/08/08/retiring-a-great-interview-problem)) Solutions: [**Java**](Java/WordBreak.java)
 