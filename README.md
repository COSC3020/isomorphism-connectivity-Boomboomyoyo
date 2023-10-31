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
Consider two graphs, $G_A$ and $G_B$, each composed of a pair of unconnected nodes, with nodes $N_{1A}$ and $N_{2A}$ in $G_A$, as well as $N_{1B}$ and $N_{2B}$ in $G_B$. Note that these graphs are not completely connected because there is edge between the two nodes in either graph.

Now, consider the function f, which maps node $N_{1A}$ to node $N_{1B}$ and $N_{2A}$ to node $N_{2B}$. This function is bijective, as it maps each node in $G_A$ to a single node in $G_B$, and all nodes in both graphs are mapped to or from. Then these two graphs are by definition isomorphic. So, two isomorphic graphs do not have to be completely connected.