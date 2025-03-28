### Graph Propositions + Definitions

**Proposition 1.5.17**: In any graph, the number of vertices with odd degree must be even.

**Handshake Lemma**: The sum of degrees is twice the number of edges.

**Isomorphism**: Two graphs G and H are isomorphic if there is a bijection f : V(G) → V(H) such that {u,v} ∈ E(G) if and only if {f(u), f(v)} ∈ E(H).

**Subgraphs**: We say that G' = (V', E') is a **subgraph** of G = (V, E), and write G' ⊆ G, provided V' ⊆ V and E' ⊆ E.

We say that G' = (V', E') is an **induced subgraph** of G = (V, E) provided V' ⊆ V and every edge in E whose vertices are still in V' is also an edge in E'.

---

### Tree Propositions

**Unique Path Proposition**: A graph T is a tree if and only if between every pair of distinct vertices of T there is a unique path.

**Unique Path Corollary**: A graph F is a forest if and only if between any pair of vertices in F there is at most one path.

**At Least Two Leaves Proposition**: Any tree with at least two vertices has at least two vertices of degree one.

**One More Vertex Than Edges Proposition**: Let T be a tree with v vertices and e edges. Then e = v - 1.

**Euler's Formula**: For any connected planar graph with v vertices, e edges, and f faces, we have v - e + f = 2.

**Theorem 2.3.1**: K5 is not planar.

**Theorem 2.3.2**: K3,3 is not planar.

**Where g is girth**: When gf ≤ 2e disagrees with Euler's formula, a graph is not planar.

### Circuits & Trails

* Euler Circuit ↔︎ the degree of every vertex is even
* Euler Trail ↔︎ there are ≤2 odd degree vertices

### Coloring

**Theorem 2.5.2**: The Four Color Theorem

If G is a planar graph, then the chromatic number is ≤4.

**Theorem 2.5.4**: The chromatic number of graph $G$ is at least the clique number.

**Theorem 2.5.5: Brooks' Theorem**:
Chromatic number is ≤ highest vertex degree unless the graph is complete or an odd cycle


