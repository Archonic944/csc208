# Definitions

## Subsets, proper subsets, supersets, intersections
$A \subseteq B$ means that every element of A is an element of B. B is sometimes called the superset of A.

$A \subset B$ means that every element of A is an element of B, and that **A and B are not equal.**

$A \cap B$ is the intersection of sets A and B.

## Injective functions

A function $f : A \rightarrow B$ is injective if there is a **unique** output B for every input A.

## Cardinality of a set

$|a|$ represents the length of a set.

## Relations

A relation from a set $A$ is a set of ordered pairs where every number inside comes from $A$.

### Transitive relations

A relation R of set A is transitive if for all $x,y,z \in A$, if $xRy$ and $yRz$ then $xRz$.

## Graphs

A set of V vertices and a set of E edges. Each E is a 2-element subset of V.

### Degree of a vertex

$d(v)$ is the degree of a vertex, equivalent to the amount of edges containing that vertex. ($\text{"incident to v"}$)

# Set Theorems

## Unionized subset equivalence
For a set $A$ and $B$ where $A \subset B$, $A \cup B = B$

## Function-set mapping

For any function $f : \mathbb{N} \rightarrow \mathbb{N}$ we can write the image of f under A as $f(A) = {f(x) : x \in A}$

## Proposition 1.5.11

For a function $f$, and for sets a and b where $a \subseteq b$, then: 

$$f(a) \subseteq f(b)$$

## Subset Transience Theorem

$$(a \subseteq b) \land (b \subseteq c) \rightarrow a \subseteq c$$

Example proof for a fact about numbers:

> Every multiple of 9100 is also a multiple of 13. We could factor 9100, but here is an easier way. The set of multiples of 9100 is a subset of the set of multiples of 91. And the set of multiples of 91 is a subset of the set of multiples of 13. Now apply the proposition above.

# Function theorems

![image](https://github.com/user-attachments/assets/7125818f-ffe4-48e9-a4b4-20931e209f67)

## Codomain-image relation theorem

For any codomain, the image of the function (all potential outputs) are a subset of the codomain.

# Graph theorems

## Proposition 1.5.17

In any graph, the number of vertices with odd degree must be even.


