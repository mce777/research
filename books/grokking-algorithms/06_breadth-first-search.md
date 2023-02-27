## Chapter 6: Breadth-first-search

- a `graph` is a set of connections
  - each `graph` is made up of `nodes` and `edges`
    - a `node` can be directly connectd to many other nodes, which are its `neighbors`  

- within a graph, the algorithm to solve the shortest-path problem is `breadth-first-search`
  - the way breadth first search works, the search radiates out from the starting point
  - `breadth-first-search` not only finds a path from a to b, it also finds the shortest path
    - `queue`: first-in-first-out (in contrast to a stack, LIFO)
      - used with `breadth-first-search`
  - `tree` no edges ever point back up (a directed graph)
    - in an undirected graph the relationship goes both ways         
