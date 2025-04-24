---
tags:
  - type/zettel
  - topic/dsa
aliases: 
created: 2025-04-22 23:00:00
---
# What Are the Common Time Complexities

Time complexity refers to the time taken by an algorithm based on input. We refer to the worst-case scenario as Big O notation. It has several complexities; among them, the following are the most common:

- **O(1):** or *constant time*. This is the most efficient algorithm, as the execution time is constant and doesn't change. For example: *accessing an array by index*, *finding the median from a sorted array*.

- **O(log n):** or *logarithmic time* comes in second place in terms of efficiency after *O(1)*. The execution time increases with the input size as *log n*. For example: *binary search*.

- **O(n):** or *linear time*. The time taken by the algorithm increases linearly with the input size. For example: *linear search*, *Kadane's algorithm*.

- **O(n²):** or *quadratic time*. The execution time of this algorithm increases quadratically. For example: *bubble sort*, *insertion sort*.

## References

- [[What is time-complexity]]
- [[What is Kadane's algorithm]]