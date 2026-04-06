# Discrete Mathematics & Graph Theory

## 1. Tree Edge Property (Formal Proof)

### Statement
Every tree with n vertices has exactly n − 1 edges.

### Proof (Strong Induction)

**Base Case (n = 1):**
A single vertex has 0 edges → 1 − 1 = 0 ✔

**Inductive Hypothesis:**
Assume true for all trees with k vertices.

**Step to k+1:**
Adding a new vertex to a tree requires exactly one edge to maintain connectivity without forming a cycle.

Thus:
Edges = (k − 1) + 1 = k

So for k+1 vertices → edges = (k+1) − 1 ✔

### Conclusion
True for all n ≥ 1.

---

## 2. Handshaking Lemma

In any undirected graph:

∑ deg(v) = 2E

### Reasoning
Each edge contributes exactly two degree counts (one per endpoint).

---

## 3. Combinatorics Problem

### Problem
How many subsets exist for a set with n elements?

### Solution
Each element has 2 choices (include/exclude):

Total subsets = 2^n

---

## 4. Recurrence Relation Example

T(n) = T(n−1) + n, T(1) = 1

### Solution
Expanding:

T(n) = 1 + 2 + 3 + ... + n  
T(n) = n(n+1)/2
