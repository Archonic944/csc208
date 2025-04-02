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

### Example of a non-transitive relation:

The "within 3" relation. Holds for $a \text{and} b$ for when $|a - b| ≤ 3$.

## Equivalence Relations

Equality is reflexive, symmetric, and transitive. 

An **equivalence relation** is a relation that is reflexive, symmetric, transitive.

## Graphs

A graph is defined as an ordered pair $G = (V, E)$, where:
-   $V$ is a set of vertices (or nodes).
-   $E$ is a set of edges, where each edge is a pair of vertices $\{u, v\}$ and $u, v \in V$.

## Trees
A tree is a connected graph containing no cycles.

A forest is a graph containing no cycles. Note that this means that a connected forest is a tree.

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

# Function theorems + propositions

## Proposition 1.5.7

if $|A| > |B|$ then the function $f : A \rightarrow B$ is not injective

The result after directly applying a theorem or proposition is called a
corollary. "If a class has 25 students, then at least 2 students share the same
birth month" is a corollary.

## Codomain-image relation theorem

For any codomain, the image of the function (all potential outputs) are a subset of the codomain.

# Graph propositions + definitions

## Proposition 1.5.17

In any graph, the number of vertices with odd degree must be even.

## Handshake Lemma

Sum of degrees is twice the number of edges.

## Degree of a vertex

$d(v)$ is the degree of a vertex, equivalent to the amount of edges containing that vertex. ($\text{"incident to v"}$)

## Graph Isomorphism

Two graphs G and H are isomorphic if there is a bijection $f : V(G) \rightarrow V(H)$ such that $\{u,v\} \in E(G)$ if and only if $\{f(u), f(v)\} \in E(H)$.

### Subgraph

We say that $G' = (V', E')$ is a **subgraph** of $G = (V, E)$, and write $G' \subseteq G$, provided $V' \subseteq V$ and $E' \subseteq E$.

We say that $G' = (V', E')$ is an **induced subgraph** of $G = (V, E)$ provided $V' \subseteq V$ and every edge in $E$ whose vertices are still in $V'$ is also an edge in $E'$.

## Tree Propositions

**Unique Path Proposition** A graph $T$ is a tree if and only if between every
pair of distinct vertices of $T$ there is a unique path.

**Unique Path Corollary** A graph $F$ is a forest if and only if between any
pair of verticies in $F$ there is at most one path.

**At Least Two Leaves Proposition** Any tree with at least two vertices has at
least two vertices of degree one.

**One More Vertex Than Edges Proposition** Let $T$ be a tree with $v$ vertices
and $e$ edges. Then $e = v - 1$.

**Euler's formula** For any connected planar graph with $v$ vertices, $e$ edges, and $f$ faces, we have $v-e+f=2$

**Theorem 2.3.1** $K_5$ is not planar.

**Theorem 2.3.2** $K_{3,3}$ is not planar

**Where g is girth** when gf ≤ 2e disagrees with Euler's formula, a graph is not planar

## Theorem 2.5.2: The Four Color Theorem

If G is a planar graph, then the chromatic number is ≤4.

## Theorem 2.5.4

The chromatic number of graph $G$ is at least the clique number.

## Theorem 2.5.5: Brooks' Theorem

Any graph $G$ satisfies $\phi(G) ≤ \delta(G)$ unless $G$ is complete or an odd cycle.

## Theorem 2.5.7

For any graph G, the chromatic index is either $\delta(G) \text{or} \delta(G) + 1$ ($\delta$ = highest degree)
