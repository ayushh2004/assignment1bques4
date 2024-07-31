# Dijkstra's Algorithm Implementation Documentation

## minDistance Function
- **Purpose**: Finds the vertex with the minimum distance value from the set of vertices not yet included in the shortest path tree.
- **Parameters**:
  - `int dist[]`: Array holding the shortest distance from the source to each vertex.
  - `bool sptSet[]`: Array indicating whether a vertex is included in the shortest path tree.
- **Returns**: Index of the vertex with the minimum distance.

## printSolution Function
- **Purpose**: Prints the distance array, showing the shortest distance from the source to each vertex.
- **Parameters**:
  - `int dist[]`: Array holding the shortest distance from the source to each vertex.
- **Returns**: Void.

## dijkstra Function
- **Purpose**: Implements Dijkstra's single source shortest path algorithm.
- **Parameters**:
  - `int graph[V][V]`: 2D array representing the adjacency matrix of the graph.
  - `int src`: The source vertex.
- **Returns**: Void.
