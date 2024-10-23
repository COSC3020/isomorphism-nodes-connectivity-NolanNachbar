# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

- Direct Proof

Consider two graphs $A$ and $B$ that are completely connected and have both have $V$ vertices. 

Let $[ 1, 2, 3, \dots, V ]$ represent the vertices of $A$ and $[ a, b, c, \dots ]$ represent the vertices of $B$. Because both graphs are completely connected, any arbitrary one-to-one mapping will preserve the required edge connectivity and thus satisfy the requirements of $f$ in the formal definition. For example, $f: V_1 \rightarrow V_2$ could take 

$$
1 \to a 
$$

$$
2 \to b 
$$

$$
3 \to c 
$$

$$
\vdots
$$

Thus, $A$ and $B$ are isomorphic. 

I certify that I have listed all sources used to complete this exercise, including the use of any large language models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice. 

I did this all independently. 
