---
title: "Project Euler 0001"
published: true
---

Problem Description:
If we list all the natural numbers below 10 that multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Find the sum of all the multiples of 3 or 5 below 1000. 

Solution: 

This is a simple application of inclusion-exclusion principle. Suppose $A$ is the set of all the multiples of 3 below 1000 and $B$ is the set of that of 5 below 1000. Then the sum of multiples of 3 or 5 below 1000 is 

$$\sum_{x\in A\cup B}x = \sum_{a\in A}a + \sum_{b\in B}b - \sum_{c\in A\cap B}c.$$

These three terms are all sums of arithmetic sequences. So the final answer is 

$$\sum_{x\in A\cup B} = \sum_{i = 1}^{333}3i + \sum_{j = 1}^{199} 5j - \sum_{k = 1}^{66}15k = 233168.$$