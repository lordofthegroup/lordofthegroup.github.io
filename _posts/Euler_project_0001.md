---
layout: post
title: "Project Euler 0001"
---

Problem Description:
If we list all the natural numbers below 10 that multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Find the sum of all the multiples of 3 or 5 below 1000. 

Solution: 

This is a simple application of inclusion-exclusion principle. Suppose $A$ is the set of all the multiples of 3 below 1000 and $B$ is the set of that of 5 below 1000. Then the sum of multiples of 3 or 5 below 1000 is 

$$\sum_{x\in \{A\cup B\}}x$$