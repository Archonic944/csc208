# Chapter 1.1

## Investigate: Knaves and Knights

- p: Troll 1 is a knave.
- q: There are exactly two knights.
- r: Troll 1 is lying.
- s: All 3 Trolls are knaves.

<table>
<thead>
<tr><th style="text-align: center;"> p </th><th style="text-align: center;"> q </th><th style="text-align: center;"> r </th><th style="text-align: center;"> s </th><th style="text-align: center;"> p =&gt; q </th><th style="text-align: center;"> s =&gt; r </th><th style="text-align: center;"> r =&gt; p </th><th style="text-align: center;"> s =&gt; p </th><th style="text-align: center;"> p =&gt; r </th><th style="text-align: center;"> q =&gt; ~s </th></tr>
</thead>
<tbody>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    0    </td></tr>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">    0    </td></tr>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    0    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    0    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 1 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   0    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
<tr><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;"> 0 </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">   1    </td><td style="text-align: center;">    1    </td></tr>
</tbody>
</table>

The only valid scenarios (where every proposition is 1):

- p, q, r, ~s: Troll 1 is a knave, there are two knights, and troll 1 is lying
- ~p, q, ~r, ~s: Troll 1 is a knight, there is 1 other knave.
- ~p, ~q, ~r, ~s: Troll 1 is a knight.  There is 1 or three knights.

Question: what would it mean if troll 1 was lying?

## Vocab

- premise
    - The beginning statements of an argument
- conclusion
    - The end of an argument
- argument
    - A sequence of statements; some premises followed by a conclusion
- theorem
    - a mathematical fact that must be proved
- proposition
    - e.g. p,q,r,s
- proof
- statement
    - A declarative sentence that is either true or false
- quantifier
- predicate
- logical connective
    - A way to combine two statements and create a molecular statement
        - Upwards hat is and (conjunction)
        - Downwards hat is or (disjunction)
        - Conditional/implication: $\rightarrow$
        - Biconditional: Double arrow
        - $\neg P$ = not P
- binary connective
    - For example: and, or
- unary connective
    - A modifier that applies to one statement
- truth value
    - true or false
- propositional variables
    - A variable that can be true or false
- conjunction
    - and
- disjunction
    - or
- implication
    - if .. then ..
- conditional
    - same as implication
- biconditional
    - if and only if - values must match
- negation
    - not
- truth conditions
    - descriptions of a particular logical connective

## Quantifiers & Predicates

A predicate is a statement with a free variable.

$O(X)$ means x is odd.

$E(X)$ means x is even

$\forall x (E(x) \vee O(x))$

...means all numbers are even or odd.

The predicate is the statement, the quantifier quantifies the free variables in that statement.

Usually our domain of discourse = all natural numbers (0,1,2,3...)