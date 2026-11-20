# Java Data Structures and Algorithms

This repository contains Java practice programs and problem solutions covering
core data structures, algorithms, and common coding-interview exercises.

## Topics

- **Arrays and windows:** arrays vs. `ArrayList`, minimum-size subarray sum,
  prefix sums, and sliding-window problems.
- **Searching and sorting:** linear and binary search, search in a rotated
  sorted array, first/last position, bubble sort, merge sort, quick sort, and
  selection sort.
- **Backtracking:** combinations and subset generation.
- **Linked lists:** singly, doubly, and circular linked lists, plus linked-list
  problems.
- **Graphs:** breadth-first and depth-first traversal, path existence, islands,
  provinces, flood fill, surrounded regions, and room/key traversal.
- **Hash maps:** grouping anagrams, frequency sorting, and four-sum counting.
- **Heaps and priority queues:** custom max heap, kth elements, top-k frequency,
  merging sorted lists, IPO, task scheduling, and related examples.
- **Queues and stacks:** queue/stack conversions, circular queues and deques,
  sliding-window maximum, and queue assessment exercises.
- **Trees:** traversals, tree construction, level order and zigzag traversal,
  height, node count, and structural validation.
- **Other exercises:** Pascal's triangle and array manipulation.

## Project layout

Problem-specific examples are grouped into topic folders such as `Graph`,
`HashMap`, `Heap`, `Queue`, and `Tree`. The `LL_*` folders contain linked-list
implementations, while folders such as `binary_search_hw` and
`Queue_Assessment` contain exercise sets. `GraphProblems.java` and
`TreeProblems.java` provide additional consolidated examples.

## Running an example

Install a JDK, then compile and run an individual example from the repository
root. For example:

```sh
javac GraphProblems.java
java GraphProblems
```

Most source files are intended to be compiled individually. Some examples use
supporting classes or have their own `main` method; check the selected source
file before compiling it.
