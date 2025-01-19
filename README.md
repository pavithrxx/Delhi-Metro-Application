This is a C++ Delhi Metro application that takes the source station and destination station (name) as input from the user and displays the shortest metro route to reach the destination. It also includes a metro map for better navigation by commuters.

The idea is implemented using graph and heap data structures. The graph consists of nodes and edges. Nodes represent metro stations and contain information about the station, such as its name, metro corridor, and connecting lines. Edges, which represent the connections between two nodes, denote the distance between two stations. The cost of each edge corresponds to the distance between its connected stations (nodes).

Using algorithms like Dijkstra's and breadth-first search (BFS), the shortest path between the source and destination stations is determined. The most optimal route is calculated based on the shortest distance between the two stations. Finally, the metro route, along with details about intersection stations, is displayed.
