# Matrix Chain Multiplication (Dynamic Programming)  

* Uses dynamic programming with nested loops to calculate optimal matrix parenthesization.
* Fills a 2D table (dp) with minimum scalar multiplication costs across chain lengths.

## Summary
* Dynamic Programming Method takes O(n^3) time across best, average, and worst cases.
* Uses O(n^2) auxiliary space to store subproblem solutions.

## Conclusion
* Dynamic Programming Method prevents exponential recalculations of matrix chain combinations.
* Computes the lowest multiplication cost before running expensive matrix multiplications.
