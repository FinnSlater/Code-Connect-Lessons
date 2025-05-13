# Linear Search

## Introduction

:::introduction
A linear search is a simple search algorithm that sequentially checks each element in a list until the desired value is found or the end of the list is reached. It's efficient for smaller lists, 
but its performance degrades significantly for larger datasets as it needs to check every item in the worst-case scenario. 
:::

## Tutorial

Key Steps of a Linear Search:
1. Start at the beginning: Begin searching from the first element of the list.
2. Iterate through each element: Compare the current element with the target value.
3. Check for a match: If the current element matches the target, the search is successful, and the element's index is returned.
4. Move to the next element: If the current element doesn't match, move to the next element in the list.
5. Continue until found or the end is reached: Repeat steps 2-4 until either the target is found or the end of the list is reached.
6. Handle not found: If the end of the list is reached and the target is not found, return an indication that the target is not present. 

When to Use Linear Search:
- Small Lists: For small lists, linear search is a straightforward and efficient option.
- Unordered Lists: It can be used on lists that are not sorted.
- Singly Linked Lists: It's a suitable choice for searching through singly linked lists where direct access to elements is not possible. 

Example:
Imagine you have a list of names: ["Alice", "Bob", "Charlie", "David"] and you are looking for "Charlie". 
The algorithm starts at "Alice" and compares it with "Charlie" (no match).
It moves to "Bob" and compares it with "Charlie" (no match).
It moves to "Charlie" and compares it with "Charlie" (match found).
The algorithm stops and returns the index of "Charlie" (which is 2).

Time Complexity:
- Best Case: O(1) - When the target is found at the first element. 
- Average Case: O(n) - When the target is found roughly in the middle of the list. 
- Worst Case: O(n) - When the target is not found or is the last element. 
