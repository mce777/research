## Dijkstra's Algorithm

- breath-first search will find you the path with the fewest segments
- Dijkstra's algorithm will find you the ***fastest*** path (on a weighted graph)
  - in this algorithm you assign weights to each segment
  - then the algorithm finds the path with the smallest total weight
  - at the core of this algorithm: look at the cheapest node on your graph
  - you can't use Dijkstra's algorithm if you have negative-weight edges
- an undirected graph means that both nodes point to each other (that's a cycle)  
