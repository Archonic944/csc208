# Graph propositions + definitions

**Proposition 1.5.17** In any graph, the number of vertices with odd degree must be even.

**Handshake lemma** Sum of degrees is twice the number of edges.

**Isomorphism** Two graphs G and H are isomorphic if there is a bijection $f : V(G) \rightarrow V(H)$ such that $\{u,v\} \in E(G)$ if and only if $\{f(u), f(v)\} \in E(H)$.

**Subgraphs** We say that $G' = (V', E')$ is a **subgraph** of $G = (V, E)$, and write $G' \subseteq G$, provided $V' \subseteq V$ and $E' \subseteq E$.

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

