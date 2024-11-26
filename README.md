# NetworkAnalysis
Community Structures in Network Analysis:

Algorithms for identifying Community Structure:

1- Lovuain Method: 
                  - This is a modularity optimization technique.
                  - It's a greedy algorithm that starts with each node in its community and iteratively merges them to maximize modularity gain.

2- Newman Girvan Method: 
                        - It is based on the concept of "betweenness centrality.
                        - The algorithm removes the edge with the highest betweenness iteratively until the most relevant communities are separated.
                        
3- Spectral Clustering:
                       - Uses the eigenvectors of the Laplacian matrix of a network.
                       - It finds a low-dimensional embedding of nodes and then applies traditional clustering methods like K-means in the embedded space.
                       
4- Label Propagation Algorithm (LPA):
                                     - Each node is initialized with a unique label.
                                     - At every step, nodes update their labels to the one that the maximum of their neighbors have.
                                     - The algorithm converges when each node has the label that the majority of their neighbors have.

5- Infomap:
           - It uses the concept of random walks.
           - The idea is that a random walker should stay in the same community for a long time if the community structure is strong.
           

Types of Graphical Structures Studied Using Community Structures:

1- Modular Structures: modules represent natural groupings of nodes that share common characteristics, functions, or interactions. 

2- Modularity: a measure that quantifies the strength of division of a network into modules.

3- Core-Periphery Structures: Identify the core and periphery nodes within each community.

4- Hierarchical Structures: show nested or layered communities within the network.

5- Overlap Structures: allow nodes to belong to multiple communities simultaneously.

6- Network Robustness: assess how the removal of key nodes or edges affects the structure and connectivity of the network.


