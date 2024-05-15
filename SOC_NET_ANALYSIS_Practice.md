**Social Network Analysis -- Practice Outline**

The Labs serve as practice for the theoretical concepts introduced in
the lecture. The practice focuses on using Python 3 Networkx 2. The
following functions cover the tasks during the practice activities and
might be useful for consultation.

1.  Basic Graph Theory

    1.  Intro: where & how to download the networks

    2.  Networkx functions to cover:

        1.  nx.Graph(), nx.DiGraph()

        2.  nx.read_edgelist()

            -   delimiter, create_using, comments

        3.  G.number_of_nodes(), G.number_of_edges(), G.nodes, G.edges

        4.  G.degree, G.in_degree, G.out_degree

        5.  nx.density()

        6.  G.add_edge(), G.add_edges_from()

        7.  G.add_node(), G.add_nodes_from()

        8.  nx.transitivity(), nx.density(), nx.average_clustering()

2.  Basic Graph Properties #2

    1.  Networkx functions to cover:

        1.  <https://networkx.github.io/documentation/stable/reference/algorithms/traversal.html>

        2.  <https://networkx.github.io/documentation/stable/reference/algorithms/shortest_paths.html>

        3.  nx.diameter()

        4.  <https://networkx.github.io/documentation/stable/reference/algorithms/centrality.html>

3.  Graphs as Matrices

    1.  Networkx functions to cover:

        1.  nx.to_numpy_matrix(), nx.to_scipy_sparse_matrix()

    2.  Numpy/Scipy functions to cover:

        1.  np.linalg.eig(), sp.sparse.linalg.eigs()

        2.  np.array.T

4.  Graph Models

    1.  Networkx functions to cover:

        1.  nx.generators.random_graphs.gnp_random_graph(),

        2.  Useful but not required:

            -   nx.generators.random_graphs.gnm_random_graph()

            -   nx.generators.random_graphs.watts_strogatz_graph(),

            -   nx.generators.random_graphs.newman_watts_strogatz_graph()

            -   nx.generators.random_graphs.barabasi_albert_graph()

            -   nx.generators.degree_seq.configuration_model(),

            -   nx.utils.random_sequence.powerlaw_sequence()

5.  Assortativity

    1.  Networkx functions to cover:

        1.  <https://networkx.github.io/documentation/stable/reference/algorithms/assortativity.html>
