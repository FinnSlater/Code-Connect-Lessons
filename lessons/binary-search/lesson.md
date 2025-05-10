# Binary Search

## Introduction

:::introduction
Binary search is an efficient algorithm for locating a target value within a **sorted array**.  
It works by repeatedly dividing the search interval in half—if the value at the midpoint is equal to the target, the search is over.  
If the target is less than the midpoint, the search continues on the lower half; if greater, on the upper half.
:::

## Tutorial

Let’s walk through the binary search process step-by-step.  
Start with the entire sorted array -> Compare the target value to the middle element -> If they match, return the middle index -> If the target is smaller, repeat the process on the left half; if larger, on the right half -> Continue until the target is found or the search interval is empty

Below is a diagram illustrating the binary search process:
![](./assets/binary_search.svg)

The time complexity of the binary search algorithm is O(log(n)); this is because the array is split in half each time. For an array of size n, the first iteration divides the array into n/2 sized subarrays, then n/4, n/8, ..., n/2^l.

The binary search algorithm is amongst the most efficient search algorithms, but requires the array to be sorted - if it needs to be sorted this then introduces a large overhead of O(nlog(n)).
