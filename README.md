# Bi-objective Spanning Tree - BiST

Find the _Minimum Spanning Tree_ that minimizes the _total cost_, while maximizing the _total profit_.<br />

We are given a connected, undirected graph _G(V, E)_, where _|V| = n_ is the total number of vertices and _|E| = m_ is the total number of edges.<br />
The graph is weighted. Each edge _e_ has a cost _c(e)_, as well as a profit _p(e)_.<br />
What we want to do is to find the minimum spanning tree _T_ of _G_ that minimizes the total cost, while maximizing the total profit.<br />

![graph](https://github.com/KyriakiAvgerinou/bi-objective_spanning_tree_BiST/assets/99874332/6ca8d665-a360-470f-9af0-714e8c63e54f)

<br />

<table align="center">
  <tr>
    <th align="left">Input Format:</th>
    <th align="left">Output Format:</th>
  </tr>
  <tr>
    <td>
      <i>"n m<br />
      fep(e<sub>1</sub>) sep(e<sub>1</sub>) p(e<sub>1</sub>) c(e<sub>1</sub>)<br />
      fep(e<sub>2</sub>) sep(e<sub>2</sub>) p(e<sub>2</sub>) c(e<sub>2</sub>)<br />
      ...<br />
      fep(e<sub>m</sub>) sep(e<sub>m</sub>) p(e<sub>m</sub>) c(e<sub>m</sub>)"</i><br />
    </td>
    <td><i>"p(T) c(T)"</i></td>
  </tr>
  <tr>
    <td>where:</td>
    <td>where:</td>
  </tr>
    <tr>
    <td>
      <i>n</i>: the total number of vertices of <i>G</i><br />
      <i>m</i>: the total number of edges of <i>G</i><br />
      <i>fep(e<sub>m</sub>)</i>: the first endpoint of edge <i>e<sub>m</sub></i><br />
      <i>sep(e<sub>m</sub>)</i>: the second endpoint of edge <i>e<sub>m</sub></i><br />
      <i>p(e<sub>m</sub>)</i>: the profit that edge <i>e<sub>m</sub></i> holds<br />
      <i>c(e<sub>m</sub>)</i>: the cost that edge <i>e<sub>m</sub></i> holds<br />
    </td>
    <td>
      <i>p(T)</i>: the total profit of <i>T</i><br />
      <i>c(T)</i>: the total cost of <i>T</i><br />
    </td>
  </tr>
</table>

**Restrictions:**
* _2 ≤ n ≤ 50.000_<br />
* _1 ≤ m ≤ 200.000_<br />
* _1 ≤ fep(e), sep(e) ≤ n, fep(e) ≠ sep(e)_<br />
* _1 ≤ p(e), c(e) ≤ 200_
