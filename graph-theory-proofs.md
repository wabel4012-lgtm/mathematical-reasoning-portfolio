# Graph Theory & Proofs

## 1. Proof: A Tree with n Nodes Has n−1 Edges

### Statement
Every connected acyclic graph (tree) with n nodes has exactly n−1 edges.

### Proof (Induction)

**Base Case:**
For n = 1, a single node has 0 edges → 1 - 1 = 0 ✔

**Inductive Step:**
Assume true for n = k.

A tree with k+1 nodes can be formed by adding one node and connecting it with one edge to an existing node.

Thus:
Edges = (k - 1) + 1 = k

So for k+1 nodes, edges = (k+1) - 1 ✔

### Conclusion
True for all n ≥ 1.

---

## 2. Handshaking Lemma

### Statement
Sum of degrees of all vertices = 2 × number of edges.

### Reasoning
Each edge contributes exactly 2 to total degree count.

Thus:
∑deg(v) = 2E ✔
