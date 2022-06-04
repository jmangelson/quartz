---
title: "Factor Graph"
enableToc: true # do not show a table of contents on this page
---

# Definition: Factor Graph
A *factor graph* is a [[public/Bipartite Graph]] with "factor nodes", "variable nodes", and edges that encodes the factorization of a function.

Given the factorization of the function $g(x_1, x_2, \cdots, x_n)$:

$$ g(x_1, x_2, \cdots, x_n) = \prod_{j=1}^m f_j(S_j),$$
where $S_j \subseteq \{x_1, x_2, \cdots, x_n\}$, the corresponding factor graph $G = (X, F, E)$ consists of variable vertices $X = \{x_1, x_2, \cdots, x_n\}$, factor vertices $F = \{f_1, f_2, \cdots, f_m\}$, and edges $E$, such that the edges depend on the factorization as follows: there is an undirected edge between factor vertex $f_j$ and variable vertex $x_k$ if $x_k \in S_j$.

# Factor Graph Example
Assume a function $f(x_1, x_2, x_3, x_4, x_5)$ can be factorized as: 
$$ f(x_1, x_2, x_3, x_4, x_5) = f_1(x_1, x_2, x_4) f_2(x_2, x_3, x4) f_3(x_4, x_5)$$ Then the corresponding factor graph would look like?

## References
1. [Wikipedia - Factor Graph](https://en.wikipedia.org/wiki/Factor_graph)
