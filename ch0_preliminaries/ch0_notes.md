# What is discrete math?
- Math that deals with "stuff" that is individual and distinct
  - For example: $\\{0,1,2,3,4\\}$ instead of $0 < x < 4$
- The study of discrete sets of data as opposed to continuous ranges
- Satisfying a set of discrete conditions, such as a logic puzzle
- Provides a way to model "real-world" problems

# What are the four main topics that Professor Levin says will be presented in the book?
- Combinatorics; think permutations
- Sequences
- Symbolic Logic
- Graph Theory

# What are discrete structures? 
Discrete structures are the mathematical objects that represent the different elements of our problem.

## Set

An unordered collection of elements. They can be described in words (e.g. the set of all natural numbers less than 10), or by listing the elements.

For two sets to be the same, every number in each set must occur at least once in the other set.
At least, that is my interperetation.

For example, these sets are the same:

$\\{1,2,3\\}$ 

$\\{3,2,1\\}$ 

$\\{1,1+1,3\\}$

## Function

A rule that assigns each input to exactly one output. The output is the "image" of the input.

- Domain: The set of all inputs
- Codomain: The set of all allowable outputs

A function can be defined with a closed formula or a recursive definition. In a recursive definition, the output can be defined based on
other outputs of the function.

### Notation

$f : X \rightarrow Y$

$f : \\{1,2,3\\}\rightarrow\\{2,4,6\\}$

## Sequences

Like a set, but considering the order of the elements. A finite sequence has a finite length, whereas an infinite sequence
could have any length n.

### Notation

$(1,2,3)$

$a_0, a_1, a_2$

$(a_n)_{n≥0}$

## Relations

- Includes less than, greater than, equal to
- Relating multiple elements, for example 2 (binary relation)
- Numbers that satisfy a relation are considered to belong to the set associated with taht relation

### Notation

*"Consider the set of all ordered pairs such that $a < b$"*

### Properties

- Irreflexive: Cannot be applied to itself
- Antisymmetric: Cannot be flipped around
- Transitive: $a < b$, $b < c$ $\therefore$ $a < c$

Some relations can give us a graph.

## Graphs

A graph is a type of symmetric and irreflexive relation. It points out which numbers in a set are connected via
a certain relation.

We think of them as a set of **vertices** and **edges** where each edge is a 2 element subsection of the vertices.

