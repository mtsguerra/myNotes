<h1>Some interesting videos all around</h1>

<h2>Data Structures:</h2>
<ol>
  <li>
    Heaps
    <p>Heaps are specialized binary trees used as the foundation for Priority queues, where it always follows a condition, for example max heap always has the child node smaller than the parent.
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=WsNQuCa_-PU&t=136s">Heap - Build Max Heap</a></li>
      <li><a href="https://www.youtube.com/watch?v=5iBUTMWGtIQ&t=217s">Heap - Max Heapify</a></li>
      <li><a href="https://www.youtube.com/watch?v=t0Cq6tVNRBA&t=241s">Data Structures: Heaps</a></li>
      <li><a href="https://www.youtube.com/watch?v=cuL8gXCSA58&t=784s">Heapify Algorithm | Max Heapify | Min Heapify</a></li>
    </ul>
  </li>
</ol>

<h2>Graphs:</h2>

<ol>
  
  <li>
    Dijkstra's Algorithm
    <p>Dijkstra’s algorithm finds the shortest distance from a starting node to all other nodes in a graph. It maintains a priority queue of nodes, always expanding the node with the smallest known distance. It works well with non-negative edge weights and it's a greedy type ig. <br><b>Time complexity: O(|E| + |V| log |V|).</b>
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=_lHSawdgXpI">Dijkstra's Algorithm in 3</a></li>
      <li><a href="https://www.youtube.com/watch?v=bZkzH5x0SKU">Dijkstras Shortest Path Algorithm Explained | With Example | Graph Theory</a></li>
    </ul>
  </li>
  
  <li>
    Kosaraju's Algorithm
    <p>Kosaraju’s algorithm finds strongly connected components (SCCs) in a directed graph. It first performs a DFS to fill a stack with vertices in post-order, then reverses all edges and performs DFS again in stack order, finding the SCCs. <br><b>Time complexity: O(V + E).</b>
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=QlGuaHT1lzA&t=126s">Kosaraju's Algorithm | Strongly Connected Components</a></li>
    </ul>
  </li>
  
  <li>
    Prim's Algorithm
    <p>Prim’s algorithm builds a minimum spanning tree by starting at any node, then repeatedly adding the smallest edge between all the edges that are connected to the visited nodes without creating cycles.<br><b> Time complexity: O(V log V + E log V).</b>
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=Uj47dxYPow8&t=89s">Prim's Algorithm: Minimum Spanning Tree (MST)</a></li>
      <li><a href="https://www.youtube.com/watch?v=cplfcGZmX7I">Prim's Algorithm in 2</a></li>
    </ul>
  </li>
  
  <li>
    Kruskal's Algorithm
    <p>Kruskal’s algorithm builds a minimum spanning tree by sorting all edges by weight and connecting the smallest ones first, without forming a cycle. A union-find structure is typically used.<br><b>Time complexity: O(E log E).</b>
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=71UQH7Pr9kU">Kruskal's Algorithm in 2</a></li>
    </ul>
  </li>
  
  <li>
    Floyd-Warshall's Algorithm
    <p>Floyd-Warshal starts with creating a matrix and filling it with all the connected edges and its weights, after that iterates through it with for k in range (nNodes) { for i in range (nNodes) { for j in range (nNodes) }} comparing dist[i][j] > dist[i][k] + dist[k][j], if its true then alter dist[i][j]. Allowing negative edges.<br><b> Time complexity: O(V³).</b>
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=4OQeCuLYj-4&t=18s&pp=0gcJCa0JAYcqIYzv">Floyd-Warshall's Algorithm in 4</a></li>
    </ul>
  </li>
  
  <li>
    Bellman-Ford's Algorithm
    <p>Bellman-Ford finds the shortest path from a starting node to all others. It relaxes all edges (V - 1) times and supports graphs with negative edge weights (but not negative cycles).<br><b> Time complexity: O(V × E).</b>
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=9PHkk0UavIM">Bellman-Ford in 4 — Theory</a></li>
      <li><a href="https://www.youtube.com/watch?v=obWXjtg0L64">Bellman-Ford in 5 — Step by step</a></li>
    </ul>
  </li>
  
  <li>
    Ford-Fulkerson's Algorithm
    <p>Ford-Fulkerson find the max flow from a source node to a sink node, the paths can be random or not for efficiency, as the paths are being chosen it creates a residual graph that consists in the capacity edge from a node to another and a reverse edge that will represent the current flow in the nodes (can be undone), the ford-fulkerson iterates through out the possible paths until there's no more path between the source and sink, finding then the max flow.<br><b>Time complexity:O(E × f), f being the max flow.</b>
</p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=LdOnanfc5TM&t=9s">Max Flow Ford Fulkerson | Network Flow | Graph Theory</a></li>
      <li><a href="https://www.youtube.com/watch?v=Xu8jjJnwvxE&t=642s">Max Flow Ford Fulkerson | Source Code</a></li>
      <li><a href="https://www.youtube.com/watch?v=Tl90tNtKvxs&t=38s">Ford Fullkerson in 5</a></li>
      <li><a href="https://www.youtube.com/watch?v=sT9dpVRKrQY&t=371s">Max Flow | Ford-Fulkerson Algorithm Explained and Implemented in Java | Graph Theory | Geekific</a></li>
      <li><a href="https://www.youtube.com/watch?v=GOwt6cISaG4">The Ford-Fulkerson Algorithm</a></li>
    </ul>
  </li>
  
  <li>
    Edmonds-Karp's Algorithm
    <p>
      Edmonds-Karp is an implementation of Ford-Fulkerson that uses BFS instead of DFS to find the shortest augmenting path (by edge count). <br><b> Time complexity: O(V × E²).</b>
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=RppuJYwlcI8">Edmonds Karp Algorithm | Network Flow | Graph Theory</a></li>
      <li><a href="https://www.youtube.com/watch?v=GiN3jRdgxU4&t=983s">Ford Fulkerson Algorithm Edmonds Karp Algorithm For Max Flow</a></li>
    </ul>
  </li>
  
  <li>
    Critical Path and Tasks
    <p>
      To find the critical path, first calculate the earliest start (ES) and earliest finish (EF) for each task by using max(previous node's EF + edge weight) in forward traversal. Then, perform a backward traversal to find the latest start (LS) and latest finish (LF) using min(next node's LS - edge weight). Once both values are known, subtract LS - ES (or LF - EF) to compute task slack. Tasks with zero slack lie on the critical path.
Note: This assumes task durations are modeled in the edges, not the nodes.
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=qEhBgNn6pYk">Earliest start, finish and latest start, finish time</a></li>
      <li><a href="https://www.youtube.com/watch?v=SLYW4nVejXM&t=796s">Total float | free float| independent float|interference float| network analysis|| pert and cpm</a></li>
    </ul>
  </li>
  
  <li>
    Stable Marriage
    <p>
      The Gale-Shapley algorithm solves the Stable Marriage Problem by repeatedly proposing and matching candidates based on preferences, ensuring a stable matching where no two individuals would rather be with each other than with their assigned partners.
    </p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=fudb8DuzQlM&t=303s">Residency Match (Stable Marriage Problem, Gale-Shapley Algorithm)</a></li>
    </ul>
  </li>
</ol>





