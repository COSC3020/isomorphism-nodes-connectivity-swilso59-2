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
  - $A$ has a set of vertices $V_{A}$ and a set of edges $E_{A}$.
  - $B$ has a set of vertices $V_{B}$ and a set of edges $E_{B}$.
  - $|V_{A}| = m$ and $|V_{B}| = n$ where $m = n$.
  
- Since $|V_{A}| = |V_{B}|$ the two graphs have the same cardinality (the same number of elements). According to theorem 2 of the pigeonhole principle "If X and Y have the same number of elements and f is one-to-one, then f is onto". This means there exists a bijection function
- $f: V_{A} \rightarrow V_{B}$.
  - Since $|V_{A}| = |V_{B}|$. This makes it possible for each vertex in $B$ to be mapped to by a vertex in $A$.
  - This passes the onto condition of bijection.
- If the function is onto and the graph is fully connected. The function would only need to map one unique vertex from $A$ to one unique vertex in $B$.
  - The graph's edge structure of $A$ is preserved under $f$.
  - Fulfilling the requirements for the one-to-one condition of bijection.
-  This shows that if two graphs $A$ and $B$ have the same number of nodes and are completely connected, they must be isomorphic.

This answer was adapted from my answer of the previous assignment. https://github.com/COSC3020/isomorphism-nodes-swilso59-2
https://www.geeksforgeeks.org/discrete-mathematics-the-pigeonhole-principle/#pigeonhole-principle-theorem

“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”
