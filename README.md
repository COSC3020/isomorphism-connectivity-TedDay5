# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

To prove that graphs can be isomorphic while not being completely connected, here's two example graphs.

Graph $G_1$: has vertices {1, 2, 3} has edges {(1, 2),(1, 3)}

Graph $G_2$: has vertices {A, B, C} has edges {(A, B),(A, C)}

These graphs shouldn't be completely connected since there is no edge from 2 to 3 in $G_1$ and no edge from B to C in $G_2$.
Mapping these graphs together would make f(1) = A, f(2) = B, and f(3) = C.
This creates a bijection between the vertex of sets of $G_1$ and $G_2$, which satisfies the condition for isomorphism.
While mapping these graphs together, the edges don't change, as (1, 2) maps to (A, B) and (1, 3) maps to (A, C) which means it maintains the same correspondence between edges.

This means graphs $G_1$ and $G_2$ are isomorphic while not being completely connected.
