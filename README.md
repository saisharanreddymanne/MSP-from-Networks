<h1>  Building Minimum Spanning Tree from Networks </h1>

 **Abstract** — This review constitutes a comprehensive review of
 Minimum Spanning Trees (MSTs) and their practical appli
cations across various domains. MSTs hold a pivotal role in
 Routing Algorithms, Network Design, Circuit Design, Resource
 Allocation, and Data Centre Design, motivated by their potential
 for significant cost reductions in intricate network scenarios. The
 primary objective of this review is to compare and analyze MST
 algorithms using Kruskal’s Algorithm. Additionally, we explore the practical
 implementations of these algorithms in real-world scenarios
 like Metro Railway networks and Uber Networks, where they
 offer optimal cost paths for network coverage. An essential
 aspect of this review is the assessment of algorithm performance
 relative to specific network complexities, addressing the chal
lenge of determining the most suitable algorithm for a given
 network. Furthermore, the review emphasizes the importance
 of redundancy and reliability within MSTs, ensuring seamless
 connectivity during link or node failures and minimizing network
 downtime.

 ![image](https://github.com/saisharanreddymanne/MSP-from-Networks/assets/148990776/cb0e253e-0217-484a-af7f-1e97cbda9fec)

 
 <h2>  I. INTRODUCTION </h2>
 In the realm of network theory and graph theory, the
 concept of Minimum Spanning Trees (MSTs) holds a
 paramount position. MSTs are fundamental in various
 applications, ranging from designing efficient communication
 networks to optimizing transportation routes. These trees
 most cost-effective way to connect a set of nodes in a graph.
 In this project, we delve into the fascinating world of MSTs
 and embark on a comprehensive exploration of different
 algorithms used to construct them.
 An MST is a subset of edges in a connected, undirected
 graph that connects all vertices together while minimizing the
 total edge weight. It represents the backbone of a network,
 ensuring that every node is reachable with the least possible
 overall cost. The significance of MSTs extends across multiple
 domains, including computer networking, urban planning,
 biology, and even image segmentation. As such, understanding
 the various algorithms that generate MSTs is essential for
 problem-solving and optimization in diverse fields.
 
 <h2>  II. MOTIVATION </h2>
 The motivation for tackling the Minimum Spanning Tree
 (MST) problem is underpinned by its pivotal role in a multi
tude of practical applications spanning diverse fields. From
 optimizing routing algorithms and network design in the
 realm of computer science to facilitating cost-effective circuit
 designs in electrical engineering, constructing MSTs holds the
 potential to revolutionize various domains. Moreover, MSTs
 find relevance in resource allocation, data center design, urban
 planning, and environmental conservation. In these contexts,
 generating an MST within a network or system can lead
 to substantial cost reductions, improved system efficiency,
 offer an elegant solution to a classic problem: finding the
 and enhanced resource allocation. MSTs, by identifying the
most efficient connections or paths, offer the promise of
 their relevance to spanning tree identification. Furthermore,
 streamlining processes, conserving resources, and promoting
 sustainability. Additionally, in fields such as healthcare, MSTs
 have been used to optimize patient treatment plans and reduce
 medical costs, further underscoring their wide-reaching impact
 on practical problem-solving. This project aims to explore
 and harness the power of MST algorithms to address these
 multifaceted challenges, unlocking innovative solutions and
 benefiting a wide range of industries and fields.
 
 <h2> III. PROBLEM STATEMENT </h2>
 In the domain of graph theory and network optimization,
 we are presented with a compelling problem centered on
 an undirected and connected graph G = (V, E). Within this
 graph, the set V represents a collection of vertices, while
 the set E contains edges, each assigned a non-negative
 weight represented as w(e). These weights signify the cost
 or distance associated with traversing each edge within the
 graph. Our primary objective within this project is to discover
 a spanning tree, denoted as T, residing within this graph. A
 spanning tree is characterized by its ability to connect all
 vertices in V, forming a tree structure devoid of any cycles.
 The central challenge we face is to identify such a spanning
 tree T while minimizing the collective weight or cost of the
 edges incorporated into T. In order to achieve the project’s objectives, we explored
 a diverse set of well-established algorithms and techniques
 for constructing minimum spanning trees (MSTs). Our in
vestigation encompassed the utilization of Prim’s Algorithm,
 Boruvka’s Algorithm, and Kruskal’s Algorithm, renowned for
 their distinct approaches to solving the MST problem. We also
 delved into the adaptability of Breadth-First Search (BFS) and
 Depth-First Search (DFS) as potential methods for MST con
Some innovative approaches like by using sets and disjoint sets
 union data structures, providing an alternative perspective on
 addressing the MST challenge. These explorations equipped
 us with a comprehensive toolkit to delve into the intricacies
 of constructing MSTs, assess their performance, and gain
 valuable insights into the practical applications of minimum
 spanning tree algorithms.
 
 <h2> IV. OBJECTIVES AND GOALS </h2>
 • Comparison of Algorithms: Despite the fact that all
 the algorithms we are implementing yield a Minimum
 Spanning Tree (MST), the choice of algorithm can make
 a difference in terms of performance, particularly in
 response to the network’s complexity.
 • Future Directions: These algorithms have practical use
 cases in networks such as Metro Railway and Uber, as
 they provide cost-efficient paths that cover the entire
 network. They play a crucial role in route optimization,
 cost reduction, and overall efficiency improvement, serv
ing as indispensable tools for the smooth functioning of
 transportation networks like Metro Rail and Uber.
 • Finding optimal Algorithm for a Particular Network:
 Determining the most suitable algorithm for a specific
 network can be a challenge because the effectiveness
 of each algorithm varies depending on the network’s
 characteristics. To identify the optimal algorithm, it’s
 necessary to run all available algorithms, making the
 selection process potentially laborious and complex.

 <h2> V. Kruskal’s Algorithm </h2>
 Kruskal's Algorithm is another widely used algorithm for finding the Minimum Spanning Tree (MST) of a connected, undirected, weighted graph.
 Sort all of the edges and express the vertices and their connections with weights using an adjacency matrix or list.
Use the union-find data structure to determine whether the related vertices are part of the same component.
If not, incorporate the edge into the MST and use the union-find data structure to combine the parts.
For the given graph, the least weight spanning tree will be represented by the set of edges in the MST.

<h2> Output Graph </h2>
From the above graph, by using Kruskal's Algorithm the MST(Minimum Spanning Tree) for the graph is: 

![image](https://github.com/saisharanreddymanne/MSP-from-Networks/assets/148990776/39b77c59-db83-42b3-a02a-736dbe227260)

 
 <h2> VI. SIGNIFICANCE </h2>
 • Optimal Network Connectivity: MSTs play a crucial
 role in ensuring optimal connectivity within networks
 by connecting all nodes while minimizing the total
 edge weight or cost, which is essential in applications
 like transportation, telecommunications, and infrastruc
ture planning.
 • Resource Allocation: MSTs play a crucial role in opti
mizing resource allocation in various industries, including
 logistics, supply chain management, and manufacturing.
 Efficient resource allocation reduces waste and enhances
 productivity.
 • Cost Savings: MSTs help minimize resource usage
 and cost, making them significant in scenarios where
 contributing to efficient resource management.
 • Efficient Routing: MSTs provide a foundation for rout
ing algorithms, enabling the determination of the shortest
 paths between nodes in networks, which improves naviga
tion, reduces travel times, and enhances overall network
 efficiency.
 
 <h2> REFERENCES </h2>
 [1] M. Held and R. M. Karp, “The traveling-salesman problem and
 minimum spanning trees,” Operations Research, vol. 18, no. 6, pp.
 1138–1162, 1970.
 [2] K. Bharath-Kumar and J. Jaffe, “Routing to multiple destinations in
 computer networks,” IEEE Transactions on communications, vol. 31,
 no. 3, pp. 343–351, 1983.
 [3] L.An,Q.-S.Xiang,andS.Chavez,“Afastimplementationofthemini-
 mum
 spanning tree method for phase unwrapping,” IEEE transactions on
 medical imaging, vol. 19, no. 8, pp. 805–808, 2000.
 [4] N.AkpanandI.Iwok,“Aminimumspanningtreeapproachofsolving a trans
portation problem,” International Journal of Mathematics and Statistics
 Invention, vol. 5, no. 3, pp. 09–18, 2017.
 [5] V. Osipov, P. Sanders, and J. Singler, “The filter-kruskal minimum
 spanning tree algorithm,” in 2009 Proceedings of the Eleventh Work
shop on Algorithm Engineering and Experiments (ALENEX). SIAM,
 2009, pp. 52–61.
 [6] R.C.Prim,“Shortestconnectionnetworksandsomegeneralizations,”
 Labs Technical Journal, vol. 36, no. 6, pp. 1389–1401, 1957.
 Bell
 [7] J. B. Kruskal, “On the shortest spanning subtree of a graph and the
 traveling salesman problem,” Proceedings of the American Mathemat
ical society, vol. 7, no. 1, pp. 48–50, 1956
