## Path_Finding_Algorithms

### A* algorithm
A* is a variant of Dijkstra's algorithm,A* assigns a weight to each open node equal to the weight of the edge to that node plus the approximate distance between that node and the finish. This approximate distance is found by the heuristic, and represents a minimum possible distance between that node and the end. This allows it to eliminate longer paths once an initial path is found.
