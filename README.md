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
- If we have two graphs $A$ and $B$ that are both completely connected and have the same number of nodes.
  - $A$ has 3 vertices $(a, b, c)$ and three edges $(a, b), (b, c), (c, a)$.
  - $B$ has 3 vertices $(1, 2, 3)$ and three edges $(1, 2), (2, 3), (3, 1)$.
  - $|V_{A}| = m$ and $|V_{B}| = n$ where $m = n$.
- If there is a one-to-one and onto funtion $f: V_{A} \rightarrow V_{B}$.
  - There are same number of vertices in $B$ and $A$. This makes it possible for every vertex in $B$ to be mapped to a vertex in $A$.
  - This passes the onto condition of bijection.
- If the funtion is onto you would only need to map one unique vertex from $A$ to one unique vertex in $B$.
  - This would fufill the requirments for the one-to-one condition of bijecton.
-  This shows that two graphs $A$ and $B$ have the same number of nodes and are completely connected, they must be isomorphic.

This answer was adapted from my answer of the previous assignment. https://github.com/COSC3020/isomorphism-nodes-swilso59-2

“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”
