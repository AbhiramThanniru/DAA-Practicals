# Making Change Problem using DP

* Change-Making Problem using Dynamic Programming to find the minimum number of coins required to make a given amount.
* It breaks the problem into subproblems and builds up an optimal solution bottom-up using a lookup table to avoid redundant calculations.
  
## Summary
* The solution uses an array dp where each index i stores the minimum coins needed to produce amount i.
* It keeps track of the absolute minimum number of coins needed for every smaller amount along the way.

## Conclusion
* Dynamic Programming efficiently solves the coin change problem in O(amount * len(coins)) time complexity.
* It swaps extra memory for speed, making it both practical and foolproof for real-world change-making.
