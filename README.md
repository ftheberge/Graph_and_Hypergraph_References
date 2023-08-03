# Textbook - Mining Complex Networks (2022)
<img src="https://github.com/ftheberge/Graph_and_Hypergraph_References/assets/42616140/8ec477e4-c2a6-44f8-bd3a-1b8b0322841b" width="100">

* Authors: Bogumił Kamiński, Paweł Prałat, and François Théberge.
* ISBN-13: 978-1032112039
* ISBN-10: 1032112034
* Link: https://www.torontomu.ca/mining-complex-networks/
* Jupyter notebooks can be found here: https://github.com/ftheberge/GraphMiningNotebooks

# Mini-courses

* (2023) CMS 2023 mini-course: https://www.summer23.cms.math.ca/mini-courses slides: https://github.com/ftheberge/CMS2023_MiniCourse
* (2022) Mining Complex Networks - Practical Methods for Mining Graphs using Python-igraph: https://github.com/ftheberge/mining_graphs
* (2021) CMS 2021 mini-course: https://summer21.cms.math.ca/index.php/mini-courses/
slides: https://github.com/ftheberge/Graph_and_Hypergraph_References/blob/main/CMS_2021.pdf
* (2019) FIELDS summer school, 2019: https://video-archive.fields.utoronto.ca/list/event/1790
slides and notebooks: https://github.com/ftheberge/ComplexNetworks2019

# Ensemble Clustering for Graphs (ECG)

ECG is a consensus clustering algorithm for vertex partitioning, based on the famous Louvain and Leiden algorithms. Several studies show that is is less affected by the resolution limit, and that it yields good, stable communities.

* (2018) Valérie Poulin and François Théberge, Ensemble Clustering for Graphs. in: Aiello L., Cherifi C., Cherifi H., Lambiotte R., Lió P., Rocha L. (eds) Complex Networks and Their Applications VII. COMPLEX NETWORKS 2018. Studies in Computational Intelligence, vol 812. Springer, https://doi.org/10.1007/978-3-030-05411-3_19 or https://link.springer.com/chapter/10.1007/978-3-030-05411-3_19. Pre-print: https://arxiv.org/abs/1809.05578

* (2019) V. Poulin and F. Théberge, Ensemble clustering for graphs: comparisons and applications, Network Science (2019) 4:51 https://doi.org/10.1007/s41109-019-0162-z or https://rdcu.be/bLn9i. Pre-print: https://arxiv.org/abs/1903.08012

### Code: 

* PyPI (igraph): https://pypi.org/project/partition-igraph/
* PyPI (networkx): https://pypi.org/project/partition-networkx/
* GitHub: https://github.com/ftheberge/graph-partition-and-measures
* NVIDIA cuGraph: https://docs.rapids.ai/api/cugraph/stable/api.html#module-cugraph.community.ecg

# Graph-aware measure for comparing graph partitions

We propose variations of commonly used measures to compare node partitions that consider the fact that the nodes are linked by edges; we also show complementarity of graph-aware and graph-agnostic measures.

* (2021) V. Poulin and F. Theberge, "Comparing Graph Clusterings: Set partition measures vs. Graph-aware measures," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol.43(6). https://doi.org/10.1109/TPAMI.2020.3009862 and https://ieeexplore.ieee.org/document/9142444. Pre-print (2018): https://arxiv.org/abs/1806.11494

### Code:

* PyPI (igraph): https://pypi.org/project/partition-igraph/
* PyPI (networkx): https://pypi.org/project/partition-networkx/
* GitHub: https://github.com/ftheberge/graph-partition-and-measures (all measures)

# Framework for comparing graph embeddings

We propose a framework to compare graph embeddings (embedding of nodes) in an unsupervised way.

### Original framework

* (2019) B. Kaminski, P. Pralat and F. Théberge, An unsupervised framework for comparing graph embeddings,
Journal of Complex Networks, Volume 8, Issue 5, 1 October 2020, https://doi.org/10.1093/comnet/cnz043, Published: 28 November 2019. 
* pre-print: https://arxiv.org/abs/1906.04562

### Scalable version

* (2020) Kamiński B., Prałat P., Théberge F., A Scalable Unsupervised Framework for Comparing Graph Embeddings. In: Kamiński B., Prałat P., Szufel P. (eds) Algorithms and Models for the Web Graph. WAW 2020. Lecture Notes in Computer Science, vol 12091. Springer, Cham. https://doi.org/10.1007/978-3-030-48478-1_4. 

* (2020) SIAM Network Science Conference: https://ns20.cs.cornell.edu/abstracts/SIAMNS_2020_paper_31.pdf

* (2021) JMM 2021 talks and slides: https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3486 and https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3674

### Studies using the framework

* (2021) Arash Dehghan-Kooshkghazi, Bogumił Kamiński, Łukasz Kraiński, Paweł Prałat, François Théberge, Evaluating Node Embeddings of Complex Networks, Journal of Complex Networks, Volume 10, Issue 4, August 2022, cnac030, https://doi.org/10.1093/comnet/cnac030. 
* pre-print: https://arxiv.org/abs/2102.08275

* (2022) UCL thesis: http://hdl.handle.net/2078.1/thesis:35567

### Multi-purpose and scalable version

* (2022) Bogumił Kamiński, Łukasz Kraiński, Paweł Prałat, François Théberge A Multi-purposed Unsupervised Framework for Comparing Embeddings of Undirected and Directed Graphs, Network Science , First View , pp. 1 - 24, https://doi.org/10.1017/nws.2022.27. 
* pre-print: https://arxiv.org/abs/2112.00075

### Code:

* Initial version in C: https://github.com/ftheberge/Comparing_Graph_Embeddings
* Scalable Julia Landmark-based version: https://github.com/KrainskiL/CGE.jl

# Artificial Benchmark for Community Detection (ABCD graphs)

We have developed a family of benchmark graphs with communities, with a few objectives in mind:
* scalability
* similarity to well-known models like LFR
* simplicity, so theoretical analysis is possible

### Base ABCD graph benchmark

* (2020) B. Kaminski, P. Pralat and F. Théberge, Artificial Benchmark for Community Detection (ABCD): Fast Random Graph Model with Community Structure, 
pre-print: https://arxiv.org/abs/2002.00843

* (2020) SIAM Network Science Conference: https://ns20.cs.cornell.edu/abstracts/SIAMNS_2020_paper_33.pdf

* (2021) B. Kaminski, P. Pralat and F. Théberge, "Sequential and parallel generation of Artificial Benchmark for Community Detection (ABCD) graphs", Book of Abstracts, Complex Networks Conference, 2020. Link to conference: https://easychair.org/smart-program/COMPLEXNETWORKS2020/2020-12-03.html#talk:162237

### Faster implementations

* (2021) B. Kaminski, P. Pralat and F. Théberge, "Artificial Benchmark for Community Detection (ABCD) - Fast random graph model with community structure", Network Science Journal (2021), pp. 1-26, https://doi.org/10.1017/nws.2020.45

* (2021) JMM 2021 talk and slides: https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3486

* (2021) B. Kaminski, P. Pralat, F. Théberge and T. Olczak, "Artificial Benchmark for Community Detection algorithm for simulation of social networks", Social Simulation Conference 2021, https://ssc2021.uek.krakow.pl/wp-content/uploads/2021/09/SSC_book_of_abstracts.pdf

* (2022) B. Kaminski, T. Olczak, B. Pankratz, P. Pralat, F. Théberge, "Properties and Performance of the ABCDe Random Graph Model with Community Structure", Big Data Research Journal, https://doi.org/10.1016/j.bdr.2022.100348

### Theoretical analysis and performance studies

* (2022) Bogumił Kamiński, Bartosz Pankratz, Paweł Prałat, François Théberge, Modularity of the ABCD Random Graph Model with Community Structure, Journal of Complex Networks, 2022, https://doi.org/10.1093/comnet/cnac050; pre-print: https://arxiv.org/abs/2203.01480.

* (2022) Also a conference talk (with proceedings) at Complex Networks 2022: https://easychair.org/smart-program/COMPLEXNETWORKS2022/2022-11-10.html#talk:204663

* (2022) B. Kaminski, P. Pralat, F. Théberge and T. Olczak, Properties and Performance of the ABCDe Random Graph Model with Community Structure, Big Data Research, 100348, ISSN 2214-5796, https://doi.org/10.1016/j.bdr.2022.100348 (https://www.sciencedirect.com/science/article/pii/S2214579622000429) and pre-print: https://arxiv.org/abs/2203.14899

* (2022) B. Kaminski, P. Pralat, F. Théberge, Asymptotic Properties of the ABCD Graph Benchmark with Community Structure, NetSci22 talk: https://easychair.org/smart-program/NetSci2022/2022-07-25.html#talk:196041 and slides: https://github.com/ftheberge/Slides/NetSci_Slides_2022.pdf

### Model with outiliers

* (2022) Bogumił Kamiński, Paweł Prałat, François Théberge, and Sebastian Zając, A Definition of Graph Modularity with Outliers, SIAM Workshop on Network Science (NS22): http://dyn.phys.northwestern.edu/ns22_abstracts/NS22_paper_9793.pdf

* (2022) Also a conference talk (with proceedings) at Complex Networks 2022: https://easychair.org/smart-program/COMPLEXNETWORKS2022/2022-11-09.html#talk:204647

### Code:

* Julia code on GitHub: https://github.com/bkamins/ABCDGraphGenerator.jl
* Multithreaded code ABCDe: https://github.com/tolcz/ABCDeGraphGenerator.jl
* Notebooks to test the speed and properties of ABCD, ABCDe and LFR: https://github.com/bartoszpankratz/ABCDe_Experiments

# Hypergraph Benchmark (h-ABCD)

* (2023) Bogumił Kamiński, Paweł Prałat, François Théberge, "Hypergraph Artificial Benchmark for Community Detection (h-ABCD)", to appear in: Journal of Complex Networks 2023, pre-print: https://arxiv.org/abs/2210.15009

### Code:

* https://github.com/bkamins/ABCDHypergraphGenerator.jl

# Hypergraph modularity and clustering

We are looking at algorithms for unsupervised learning with hypergraphs; as a first step, we generalized the concept of modularity, often used in graph clustering algorithms, to hypergraphs.

* (2019) Bogumił Kamiński, Valérie Poulin, Paweł Prałat , Przemysław Szufel, François Théberge, "Clustering via hypergraph modularity", PLOS ONE, November 6, 2019, https://doi.org/10.1371/journal.pone.0224307. Pre-print (2018): https://arxiv.org/abs/1810.04816

* (2021) Kamiński B., Prałat P., Théberge F. "Community Detection Algorithm Using Hypergraph Modularity". In: Benito R.M., Cherifi C., Cherifi H., Moro E., Rocha L.M., Sales-Pardo M. (eds) Complex Networks & Their Applications IX. COMPLEX NETWORKS 2020 2020. Studies in Computational Intelligence, vol 943. Springer, Cham. https://doi.org/10.1007/978-3-030-65347-7_13 Link to conference: https://easychair.org/smart-program/COMPLEXNETWORKS2020/2020-12-03.html#talk:162304

* (2021) JMM 2021 talk and slides: https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3482

### Code:

* H-modularity https://pnnl.github.io/HyperNetX/build/modularity.html is now part of HyperNetX: https://github.com/pnnl/HyperNetX

# AGC - Area under Gain Curves

A useful tool to compare binary classifiers's top scoring points.

### Code:

* PyPI: https://pypi.org/project/agc/
* GitHub (including example notebook): https://github.com/ftheberge/agc

# Social Network Analysis
<img src="https://github.com/ftheberge/Graph_and_Hypergraph_References/assets/42616140/ff179ebe-3b00-47d9-8eea-49f96a67b187" width="100">

* (2023) Stan Matwin, Aristides Milios, Paweł Prałat, Amilcar Soares and François Théberge, "Generative Methods for Social Media Analysis", SpringerBriefs in Computer Science, 2023. https://link.springer.com/book/10.1007/978-3-031-33617-1 pre-print: https://arxiv.org/abs/2112.07041

# TGM - Temporal Graph Motifs

A tool to find actors with correlated temporal activity in various networks.
* Note: https://github.com/ftheberge/tgm/blob/main/Temporal_Graph_Motifs.pdf

### Code:

* PyPI: https://pypi.org/project/tgm/
* GitHub (including example notebook): https://github.com/ftheberge/tgm

# Conference organization
<img src="https://github.com/ftheberge/Graph_and_Hypergraph_References/assets/42616140/a8309659-d569-444e-bc1b-a7c5d7efd0bc" width="100">

* Co-organizer, WAW 2023, FIELDS(Toronto): https://math.ryerson.ca/waw2023/  proceedings: https://link.springer.com/book/10.1007/978-3-031-32296-9
* Co-organizer, Workshop on Modelling and Mining Complex Networks as Hypergraphs, TMU (Toronto), 2023. https://math.ryerson.ca/waw2023/schedule.html
* Co-organizer, WAW 2024: https://math.torontomu.ca/waw2024/
  



