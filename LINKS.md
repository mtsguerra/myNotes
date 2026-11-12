<h1>Some interesting videos all around</h1>

<div class="topics" id="data-structures">
<h2>Stacks&Queues</h2>
<ol>
    <li id="monotonic-stack">
        <strong>Monotonic Stack</strong>
        <p>Monotonic stacks are used to maintain a stack of elements in a specific order, either increasing or decreasing. They are useful for problems that require finding the next greater or smaller element efficiently.
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=Dq_ObZwTY_Q&t=190s" target="_blank"> Monotonic Stack Data Structure Explained </a></li>
        </ul>
    </li>
</ol>
</div>

<div class="topics" id="trees">
<h2>Trees:</h2>
<ol>
    <li id="heaps">
        <strong>Heaps</strong>
        <p>Heaps are specialized binary trees used as the foundation for Priority queues, where it always follows a condition, for example max heap always has the child node smaller than the parent.
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=WsNQuCa_-PU&t=136s" target="_blank">Heap - Build Max Heap</a></li>
          <li><a href="https://www.youtube.com/watch?v=5iBUTMWGtIQ&t=217s" target="_blank">Heap - Max Heapify</a></li>
          <li><a href="https://www.youtube.com/watch?v=t0Cq6tVNRBA&t=241s" target="_blank">Data Structures: Heaps</a></li>
          <li><a href="https://www.youtube.com/watch?v=cuL8gXCSA58&t=784s" target="_blank">Heapify Algorithm | Max Heapify | Min Heapify</a></li>
        </ul>
    </li>
    <br>
    <li id="Trie">
        <strong>Trie</strong>
        <p>Trie is a tree-like data structure used for storing strings, where each node represents a character. It allows for efficient prefix searching and is commonly used in autocomplete systems and spell checkers.
        </p>
        <ul>
            <li><a href="https://www.youtube.com/watch?v=zIjfhVPRZCg" target="_blank">Data Structures: Tries </a></li>
            <li><a href="https://www.youtube.com/watch?v=oobqoCJlHA0&t=927s" target="_blank">Implement Trie (Prefix Tree) - Leetcode 208 </a></li>
            <li><a href="https://www.youtube.com/watch?v=c1lX6ntrj64&t=103s" target="_blank">How to implement Trie in Java ? | Implementation </a></li>
        </ul>
    </li>
    <br>
</ol>
</div>

<div class="topics" id="graphs">
<h2>Graphs:</h2>
<ol>
    <li id="dijkstra">
        <strong>Dijkstra's Algorithm</strong>
        <p>Dijkstra’s algorithm finds the shortest distance from a starting node to all other nodes in a graph. It maintains a priority queue of nodes, always expanding the node with the smallest known distance. It works well with non-negative edge weights and it's a greedy type ig. <br><b>Time complexity: O(|E| + |V| log |V|).</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=_lHSawdgXpI" target="_blank">Dijkstra's Algorithm in 3</a></li>
          <li><a href="https://www.youtube.com/watch?v=bZkzH5x0SKU" target="_blank">Dijkstras Shortest Path Algorithm Explained | With Example | Graph Theory</a></li>
        </ul>
    </li>
    <br>
    <li id="kosaraju">
        <strong>Kosaraju's Algorithm</strong>
        <p>Kosaraju’s algorithm finds strongly connected components (SCCs) in a directed graph. It first performs a DFS to fill a stack with vertices in post-order, then reverses all edges and performs DFS again in stack order, finding the SCCs. <br><b>Time complexity: O(V + E).</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=QlGuaHT1lzA&t=126s" target="_blank">Kosaraju's Algorithm | Strongly Connected Components</a></li>
        </ul>
    </li>
    <br>
    <li id="prim">
        <strong>Prim's Algorithm</strong>
        <p>Prim’s algorithm builds a minimum spanning tree by starting at any node, then repeatedly adding the smallest edge between all the edges that are connected to the visited nodes without creating cycles.<br><b> Time complexity: O(V log V + E log V).</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=Uj47dxYPow8&t=89s" target="_blank">Prim's Algorithm: Minimum Spanning Tree (MST)</a></li>
          <li><a href="https://www.youtube.com/watch?v=cplfcGZmX7I" target="_blank">Prim's Algorithm in 2</a></li>
        </ul>
    </li>
    <br>
    <li id="kruskal">
        <strong>Kruskal's Algorithm</strong>
        <p>Kruskal’s algorithm builds a minimum spanning tree by sorting all edges by weight and connecting the smallest ones first, without forming a cycle. A union-find structure is typically used.<br><b>Time complexity: O(E log E).</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=71UQH7Pr9kU" target="_blank">Kruskal's Algorithm in 2</a></li>
        </ul>
    </li>
    <br>
    <li id="floyd-warshall">
        <strong>Floyd-Warshall's Algorithm</strong>
        <p>Floyd-Warshall starts with creating a matrix and filling it with all the connected edges and its weights, after that iterates through it with <code>for k in range (nNodes) { for i in range (nNodes) { for j in range (nNodes) }} comparing dist[i][j] > dist[i][k] + dist[k][j], if its true then alter dist[i][j]</code>. Allowing negative edges.<br><b> Time complexity: O(V³).</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=4OQeCuLYj-4&t=18s&pp=0gcJCa0JAYcqIYzv" target="_blank">Floyd-Warshall's Algorithm in 4</a></li>
        </ul>
    </li>
    <br>
    <li id="bellman-ford">
        <strong>Bellman-Ford's Algorithm</strong>
        <p>Bellman-Ford finds the shortest path from a starting node to all others. It relaxes all edges (V - 1) times and supports graphs with negative edge weights (but not negative cycles).<br><b> Time complexity: O(V × E).</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=9PHkk0UavIM" target="_blank">Bellman-Ford in 4 — Theory</a></li>
          <li><a href="https://www.youtube.com/watch?v=obWXjtg0L64" target="_blank">Bellman-Ford in 5 — Step by step</a></li>
        </ul>
    </li>
    <br>
    <li id="ford-fulkerson">
        <strong>Ford-Fulkerson's Algorithm</strong>
        <p>Ford-Fulkerson find the max flow from a source node to a sink node, the paths can be random or not for efficiency, as the paths are being chosen it creates a residual graph that consists in the capacity edge from a node to another and a reverse edge that will represent the current flow in the nodes (can be undone), the ford-fulkerson iterates through out the possible paths until there's no more path between the source and sink, finding then the max flow.<br><b>Time complexity:O(E × f), f being the max flow.</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=LdOnanfc5TM&t=9s" target="_blank">Max Flow Ford Fulkerson | Network Flow | Graph Theory</a></li>
          <li><a href="https://www.youtube.com/watch?v=Xu8jjJnwvxE&t=642s" target="_blank">Max Flow Ford Fulkerson | Source Code</a></li>
          <li><a href="https://www.youtube.com/watch?v=Tl90tNtKvxs&t=38s" target="_blank">Ford Fullkerson in 5</a></li>
          <li><a href="https://www.youtube.com/watch?v=sT9dpVRKrQY&t=371s" target="_blank">Max Flow | Ford-Fulkerson Algorithm Explained and Implemented in Java | Graph Theory | Geekific</a></li>
          <li><a href="https://www.youtube.com/watch?v=GOwt6cISaG4" target="_blank">The Ford-Fulkerson Algorithm</a></li>
        </ul>
    </li>
    <br>
    <li id="edmonds-karp">
        <strong>Edmonds-Karp's Algorithm</strong>
        <p>
          Edmonds-Karp is an implementation of Ford-Fulkerson that uses BFS instead of DFS to find the shortest augmenting path (by edge count). <br><b> Time complexity: O(V × E²).</b>
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=RppuJYwlcI8" target="_blank">Edmonds Karp Algorithm | Network Flow | Graph Theory</a></li>
          <li><a href="https://www.youtube.com/watch?v=GiN3jRdgxU4&t=983s" target="_blank">Ford Fulkerson Algorithm Edmonds Karp Algorithm For Max Flow</a></li>
        </ul>
    </li>
    <br>
    <li id="critical-path">
        <strong>Critical Path and Tasks</strong>
        <p>
          To find the critical path, first calculate the earliest start (ES) and earliest finish (EF) for each task by using <code>max(previous node's EF + edge weight)</code> in forward traversal. Then, perform a backward traversal to find the latest start (LS) and latest finish (LF) using <code>min(next node's LS - edge weight)</code>. Once both values are known, subtract <code>LS - ES (or LF - EF)</code> to compute task slack. Tasks with zero slack lie on the critical path.
    Note: This assumes task durations are modeled in the edges, not the nodes.
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=qEhBgNn6pYk" target="_blank">Earliest start, finish and latest start, finish time</a></li>
          <li><a href="https://www.youtube.com/watch?v=SLYW4nVejXM&t=796s" target="_blank">Total float | free float| independent float|interference float| network analysis|| pert and cpm</a></li>
        </ul>
    </li>
    <br>
    <li id="stable-marriage">
        <strong>Stable Marriage</strong>
        <p>
          The Gale-Shapley algorithm solves the Stable Marriage Problem by repeatedly proposing and matching candidates based on preferences, ensuring a stable matching where no two individuals would rather be with each other than with their assigned partners.
        </p>
        <ul>
          <li><a href="https://www.youtube.com/watch?v=fudb8DuzQlM&t=303s" target="_blank">Residency Match (Stable Marriage Problem, Gale-Shapley Algorithm)</a></li>
        </ul>
    </li>
</ol>
</div>


//

<a href="https://www.youtube.com/watch?v=NUWAXbSlsws" target="_blank">Kadane algorithm</a>

<a href="https://www.youtube.com/watch?v=CWDQJGaN1gY" target="_blank">Fenwick tree</a>


