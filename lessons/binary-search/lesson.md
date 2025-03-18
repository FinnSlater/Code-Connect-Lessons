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
![](./assets/binary_search.png)
