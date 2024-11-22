# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer 
Direct Proof:
- If we have two graphs $A$ and $B$ that are bothe complete and have the same number of vertices.
  - $A$ has 3 vertices $(a, b, c)$ and three edge $(a, b), (b, c), (c, a)$.
  - $B$ has 3 vertices $(1, 2, 3)$ and three edge $(1, 2), (2, 3), (3, 1)$.
- If there is a one-to-one and onto funtion $f: V_{A} \rightarrow V_{B}$ that maps .
- 
- This violates the bijection requirement.
  - There are more vertices in $B$ than in $A$. This makes it impossible for every vertex in $B$ to be mapped to by a vertex in $A$.
  - This breaks the onto condition of bijection.
- If the funtion is onto you would need to at least map one vertex from $A$ to multiple vertex in $B$.
  - This would cause a violation of the one-to-one condition of bijecton condition.
-  This shows that two graphs that do not have the same number of nodes cannot be isomorphic.
