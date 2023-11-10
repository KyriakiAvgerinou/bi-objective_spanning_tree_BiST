# Bi-objective Spanning Tree - BiST

Find the Minimum Spanning Tree that minimizes the total cost, while maximizing the total profit.

We are given a connected, undirected graph _G(V, E)_, where _|V| = n_ is the total number of vertices and _|E| = m_ is the total number of edges.
The graph is weighted. Each edge _e_ has a cost _c(e)_, as well as a profit _p(e)_.
What we want to do is to find the Minimum Spanning Tree _T_ of _G_ that minimizes the total cost, while maximizing the total profit.

### Input Format:
_n m_
_fep(e<sub>1</sub>) sep(e<sub>1</sub>) p(e<sub>1</sub>) c(e<sub>1</sub>)_
_fep(e<sub>2</sub>) sep(e<sub>2</sub>) p(e<sub>2</sub>) c(e<sub>2</sub>)_
_..._
_fep(e<sub>m</sub>) sep(e<sub>m</sub>) p(e<sub>m</sub>) c(e<sub>m</sub>)_

where:
-_n_: the total number of vertices of _G_
-_m_: the total number of edges of _G_
-_fep(e<sub>m</sub>)_: the first endpoint of edge _e<sub>m</sub>_
-_sep(e<sub>m</sub>)_: the second endpoint of edge _e<sub>m</sub>_
-_p(e<sub>m</sub>)_: the profit that edge _e<sub>m</sub>_ holds
-_c(e<sub>m</sub>)_: the cost that edge _e<sub>m</sub>_ holds

### Output Format:
_tp tc_

where:
-_tp_: the total profit of _T_
-_tc_: the total cost of _T_

### Restrictions:
-_2 <= n <= 50.000_
-_1 <= m <= 200.000_
-_1 <= fep(e), sep(e) <= n, fep(e) !== sep(e)_
-_1 <= p(e), c(e) <= 200_
