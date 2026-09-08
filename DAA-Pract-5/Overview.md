# Knapsack using DP

* Creates a 2D grid to store the maximum values for all item and capacity combinations.
* Loops through each item and checks it against every capacity from 0 to the maximum limit.
* Compares two choices at each step: including the current item or leaving it behind.
* Selects the maximum value between these choices and saves it in the grid.
* Returns the final answer from the bottom-right corner of the table.
  
## Summary
* Time Complexity is O(n x W), which runs efficiently by avoiding repeated calculations.
* Space Complexity is O(n x W) to maintain the lookup table in memory.
* Sample Output yields a maximum value of 9 for the provided input items.

## Conclusion
* Highly efficient for solving the 0/1 Knapsack problem compared to slow brute-force guessing.
* Requires extra memory to store the grid, which scales with both the number of items and the total capacity.
