[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12577688&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Informally, a completely connected graph is one where all nodes are connected to all other nodes. It can be simply shown that a pair of isomorphic graphs which are not completely connected are still isomorphic. 

Formally:
Assume that if two graphs $A$ and $B$ are isomorphic, and they are not completely connected. In this case, this means that they hold to the definition of isomorphism where for $G_A=(V_1 , E_1)$ and $G_B = (V_2, E_2)$ and there exists a bijection $f: V_1 \rightarrow V_2$ such that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$.

Now, since graphs $A$ and $B$ are not completely connected, there exists a pair of nodes in both graph $A$ and $B$ for which there is no edge between them, but for all other nodes and edges there is a bijection such that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$. This does not violate the definition of isomorphism, so two arbitrary graphs $A$ and $B$ can be isomorphic without being completely connected.