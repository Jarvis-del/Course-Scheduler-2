# Course-Scheduler-2
A Java implementation of Course Schedule II using BFS (Kahn’s Algorithm) to determine a valid order of course completion based on prerequisites.


# Course Scheduler II (LeetCode 210)

A clean and efficient Java solution to the Course Schedule II problem using **Topological Sorting (BFS / Kahn’s Algorithm)**.

## 🚀 Features

* Detects valid course order
* Handles cycle detection
* Uses BFS with in-degree approach
* Optimized time complexity

## 🧠 Approach

* Build graph using adjacency list
* Calculate in-degree of each node
* Push nodes with in-degree = 0 into queue
* Perform BFS and generate course order
* If all courses are processed → valid order
* Else → cycle exists (return empty)

## ⏱️ Complexity

* Time: O(V + E)
* Space: O(V + E)

## 🛠️ Tech Stack

* Java
* Data Structures (Graph, Queue)

## 📌 Problem Link

[![LeetCode](https://img.shields.io/badge/LeetCode-Problem-orange)](https://leetcode.com/problems/course-schedule-ii/)

## 📷 Example

Input:
numCourses = 2
prerequisites = [[1,0]]

Output:
[0,1]

## 📄 License

This project is for educational purposes.
