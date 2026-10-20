

\# Java DSA Journey 🚀



\*\*Building problem-solving skills, one problem at a time.\*\*



A beginner's journey into Data Structures and Algorithms using Java, with consistent practice, clear explanations, and honest progress tracking.



!\[Java](https://img.shields.io/badge/Language-Java-orange)

!\[DSA](https://img.shields.io/badge/Focus-Data%20Structures%20%26%20Algorithms-blue)

!\[LeetCode](https://img.shields.io/badge/Practice-LeetCode-yellow)

!\[Status](https://img.shields.io/badge/Status-Learning%20in%20Progress-brightgreen)



\## Contents



\- \[About](#about)

\- \[Repository Structure](#repository-structure)

\- \[Progress Tracker](#progress-tracker)

\- \[Day 1: Running Sum](#day-1-running-sum-of-1d-array)

\- \[Concepts Learned](#concepts-learned)

\- \[Learning Roadmap](#learning-roadmap)

\- \[How to Run](#how-to-run)

\- \[Goals](#goals)



\## About



I'm learning Java and Data Structures and Algorithms from the beginning. This repository documents my practice, solutions, mistakes, and improvements as I develop my programming and problem-solving skills.



The goal is to understand the logic behind each solution instead of simply copying code.



\## Repository Structure



```text

java-dsa-journey/

├── README.md

└── Day01/

&#x20;   └── RunningSum.java

```



\## Progress Tracker



| Day | Problem | Topics | Status |

|---|---|---|---|

| 1 | \[LeetCode 1480: Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | Arrays, loops, indexing, running totals | Accepted |



\## Day 1: Running Sum of 1d Array



\*\*Problem:\*\* Given an array, return an array where each position contains the sum of all elements up to that position.



Example:



```text

Input:  \[2, 5, 1]

Output: \[2, 7, 8]

```



\### How it works



1\. Start with a running total of `0`.

2\. Visit each element from left to right.

3\. Add the current element to the running total.

4\. Store that total in the corresponding position of the result array.

5\. Return the result.



\### Complexity



\- \*\*Time:\*\* `O(n)` — each element is visited once.

\- \*\*Auxiliary space:\*\* `O(n)` — a separate result array stores the running sums.



\*\*Solution file:\*\* `Day01/RunningSum.java`



\## Concepts Learned



\- Java variables and arithmetic

\- `if` statements and loops

\- Array indexing

\- Total sum versus running sum

\- Building an array of cumulative sums

\- Understanding time and space complexity



\## Learning Roadmap



\- \[x] Java basics practice

\- \[x] Solve and submit LeetCode 1480

\- \[ ] Practise more array problems

\- \[ ] Learn strings and common string operations

\- \[ ] Study searching and sorting

\- \[ ] Learn basic recursion

\- \[ ] Explore linked lists, stacks, and queues

\- \[ ] Progress to trees and other data structures



Items above reflect my learning checklist, not a claim that every topic has been mastered.



\## How to Run



Requirements: a Java JDK installed and available in your terminal.



From the repository root, compile the solution:



```bash

javac Day01/RunningSum.java

```



Run it using the class name declared in the Java file. If the file defines a LeetCode-style `Solution` class without a `main` method, it must first be used through a test harness or a separate driver program.



\## Goals



\- Practise consistently and understand each solution.

\- Write readable Java code.

\- Track completed problems honestly.

\- Learn from incorrect attempts and improve over time.

\- Keep this repository organised as the journey grows.



\## Feedback



Suggestions, corrections, and beginner-friendly explanations are welcome. This repository is a work in progress, and every solved problem is another step forward.



