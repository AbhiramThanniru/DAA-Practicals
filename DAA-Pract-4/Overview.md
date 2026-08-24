# Factorial (Iterative)

* Uses a for or while loop to multiply numbers sequentially.
* Starts from 1 and multiplies up to the target number.

# Factorial (Recursive)

* Uses a function that calls itself with a smaller value.
* Base case returns 1 when the number reaches 0 or 1.

## Summary
* **Iterative Method** takes O(n) time to compute.
* Uses O(1) space because it only updates one variable.
* **Recursive Method** takes O(n) time to compute.
* Uses O(n) space due to the call stack frames.

## Conclusion
* **Iterative Method** best for general use and large input numbers.
* Safe from memory errors like stack overflow.
* **Recursive Method** code is clean and matches the mathematical definition.
* Risks a RecursionError if the input number is too large.
