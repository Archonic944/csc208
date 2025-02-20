# Chapter 1.3 Notes

## Try it 1.3.1

First we should make variables
p = purple shirt
q = green vest
r = tweed vest
s = bow tie
t = red shoes

s = true

q | t

(p & q) => ~s

q => p | t

p => t

Let's make a truth table

Must be q, s, t

## Implications + Tautologies

$p \rightarrow q \vee q \rightarrow p$

...is a tautology.

## De Morgan's Laws

$\neg (P \lor Q) = \neg P \land \neg Q$

$\neg (P \land Q) = \neg P \lor \neg Q$

## Implications as disjunctions

$P \rightarrow Q = \neg P \lor Q$

## Implication Negations

![The negation of an implication is a conjunction.](image.png)

## Deductions

Written like this:

![alt text](image-1.png)

# Practice Problems

These were completed in the actual textbook.

# Additional exercises: my answers

1. No
2. Skipped

3a. (P or Q) => Q

3b. Same as implication truth table

3c. Can't conclude anything if we know there's cake

3d. It isn't my birthday

4. p or s, s => q, (p or q) => r. We don't yet know if geoff is a liar or truth teller

5. The statement is correct because you said it was correct. Having the variable on the right side of the implication be false while the one on the left side is true is the only way for an implication to be false.

6a. P and Q

6b:

$(\neg P \lor \neg Q) \rightarrow \neg (\neg Q \land R)$

$\neg (\neg P \lor \neg Q) \lor \neg (\neg Q \land R)$

$(P \land Q) \lor \neg (\neg Q \land R)$

$(P \land Q) \lor (Q \lor \neg R)$

6c:

$\neg (P \rightarrow \neg Q) \lor (R \land \neg R)$

This statement is always true considering the ~(R and ~R) but ignoring that:

$\neg (P \rightarrow \neg Q)$

And continue to simplify:

$\neg (\neg P \lor \neg Q)$

$P \land Q$

6d:
P = sam is a man
Q = chris is a woman

$\neg ((\neg P \rightarrow Q) \land \neg Q)$

$\neg (\neg P \rightarrow Q) \lor Q$

Negating an implication turns it into a conjunction

$(\neg P \land \neg Q) \lor Q$

7a:

$\neg ((\neg P \land Q) \lor \neg (R \lor \neg S))$

$\neg (\neg P \land Q) \land (R \lor \neg S)$

$(P \lor \neg Q) \land (R \lor \neg S)$

7b:

$\neg ((\neg P \rightarrow \neg Q) \land (\neg Q \rightarrow R))$

$\neg (\neg P \rightarrow \neg Q) \lor \neg(\neg Q \rightarrow R)$

$(\neg P \land Q) \lor (\neg Q \land \neg R)$

8. Consider the statement, “If a number is triangular or square, then it is not prime”

a. Counterexample - We would need any of these: 
1. a number that is triangular, square, and prime
2. a number that is triangular and prime
3. a number that is square and prime

$(T \lor S) \rightarrow \neg P$

9. Tommy Flanagan was telling you what he ate yesterday afternoon. He tells you, “I had either popcorn or raisins. Also, if I had cucumber sandwiches, then I had soda. But I didn’t drink soda or tea.” Of course, you know that Tommy is the world’s worst liar, and everything he says is false. What did Tommy eat?

Original propositions:
- P or R
- Q => S
- ~(S or T)

Negated propositions:
- ~P and ~ R
- ~(Q => S)
- S or T

True case is Q T
But it says he can only drink 1 thing so let's say it's Q,S

10. Can you chain implications together? That is, if P => Q and Q => R, does that mean P => R? Prove that the following is a valid deduction rule:

There is no scenario where P is true and R is false.
If P is true, then Q has to be true, which means that R has to be true. Therefore, P => R.

11. Suppose P and Q are (possibly molecular) propositional statements. Prove that P and Q are logically equivalent if and only if $P \leftrightarrow Q$ is a tautology.

For P and Q to be logically equivalent, P and Q must be the same in all cases. $P \leftrightarrow Q$ means that p and q are the same, and that being a tautology means they are the same in all cases.