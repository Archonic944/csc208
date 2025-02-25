# 1.4 Notes

## Learning goals

* Direct proofs
* Proof by contrapositive
* Proof by cotradiction
* Identify flaws in an incorrect proof and determine whether they are flaws in logic or mathematical concepts.
* Apply definitions to prove statements using basic proof styles.

## Try it 1.4.1 (sudoku)

You cannot break the rule provided. No two adjacent squares can be the same,
and in the middle, every square is adjacent.

## Types of proofs

### Direct proof
  * Systematic explanation of what everything means. Carefully defining every element.
  * Assume P. Explain explain explain... therefore Q.
  * Example: *For each digit, since it appears exactly once in four different rows, it appears exactly four times. This completes the proof.*
#### Example 1.4.5
* My answer: A two in the top left square means that there must be a 4 in the top right square.
* A 4 in the top right square means there must be a 2 in the bottom right square.

### Proof by Contrapositive

* Directly proves $\neg Q \rightarrow \neg P$
* Example: Prove that if a mini sudoku puzzle is solvable, then it is valid.
  * Assume a puzzle is not valid, then prove that it is not solvable.
 
### Proof by contradiction

* Assume P is false. Make a direct proof from $\neg P$ to a false conclusion, thereby proving that P is true.
* $\neg P \rightarrow \text{contradiction}$

### Example 1.4.13

First, assume some solution S does not contain a 3 in the top right corner.
Then, prove that S is not valid. There must be a 3 somewhere else in the top row, but no other spot works.
Therefore, there exists no solution S that does not contain a 3 in the top right corner.

## Summary
<img width="629" alt="image" src="https://github.com/user-attachments/assets/4a7ef20d-cd3c-4357-b96e-a2beff3b6a88" />

