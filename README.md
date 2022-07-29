# Textbook - Mining Complex Networks

Published early 2022, see: https://www.torontomu.ca/mining-complex-networks/ and https://github.com/ftheberge/GraphMiningNotebooks

Slides for 3-hour short course from this book: https://github.com/ftheberge/Graph_and_Hypergraph_References/blob/main/CMS_2021.pdf

# Mini-course

FIELDS summer school, 2019: https://video-archive.fields.utoronto.ca/list/event/1790 slides and notebooks: https://github.com/ftheberge/ComplexNetworks2019

CMS 2021 mini-course: https://summer21.cms.math.ca/index.php/mini-courses/ (slides available on demand)

# Ensemble Clustering for Graphs (ECG)

ECG is a consensus clustering algorithm for vertex partitioning, based on the famous Louvain algorithm. Several studies show that is is less affected by the resolution limit, and that it yields good, stable communities.


* (2019) Valérie Poulin and François Théberge, Ensemble Clustering for Graphs. in: Aiello L., Cherifi C., Cherifi H., Lambiotte R., Lió P., Rocha L. (eds) Complex Networks and Their Applications VII. COMPLEX NETWORKS 2018. Studies in Computational Intelligence, vol 812. Springer (2019), https://doi.org/10.1007/978-3-030-05411-3_19 or https://link.springer.com/chapter/10.1007/978-3-030-05411-3_19 

* (2018) Pre-print: https://arxiv.org/abs/1809.05578

* (2019) V. Poulin and F. Théberge, Ensemble clustering for graphs: comparisons and applications, Network Science (2019) 4:51 https://doi.org/10.1007/s41109-019-0162-z or https://rdcu.be/bLn9i

* (2019) Pre-print: https://arxiv.org/abs/1903.08012

### Code: 

* PyPI (igraph): https://pypi.org/project/partition-igraph/
* PyPI (networkx): https://pypi.org/project/partition-networkx/
* GitHub: https://github.com/ftheberge/graph-partition-and-measures
* Codeocean: https://codeocean.com/capsule/3898939/tree/v1
* NVIDIA cuGraph: https://docs.rapids.ai/api/cugraph/stable/api.html#module-cugraph.community.ecg

# Graph-aware measure for comparing graph partitions

* (2021) V. Poulin and F. Theberge, "Comparing Graph Clusterings: Set partition measures vs. Graph-aware measures," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol.43(6). https://doi.org/10.1109/TPAMI.2020.3009862 and https://ieeexplore.ieee.org/document/9142444

* (2018) Pre-print: https://arxiv.org/abs/1806.11494

### Code:

* PyPI (igraph): https://pypi.org/project/partition-igraph/
* PyPI (networkx): https://pypi.org/project/partition-networkx/
* GitHub: https://github.com/ftheberge/graph-partition-and-measures (all measures)
* codeocean: https://codeocean.com/capsule/0712485/tree/v1 (Adjusted graph-aware Rand Index)

# Framework for comparing graph embeddings

* (2019) B. Kaminski, P. Pralat and F. Théberge, An unsupervised framework for comparing graph embeddings,
Journal of Complex Networks, Volume 8, Issue 5, 1 October 2020, https://doi.org/10.1093/comnet/cnz043, Published: 28 November 2019.

* (2019) Pre-print: https://arxiv.org/abs/1906.04562

* (2020) Kamiński B., Prałat P., Théberge F., A Scalable Unsupervised Framework for Comparing Graph Embeddings. In: Kamiński B., Prałat P., Szufel P. (eds) Algorithms and Models for the Web Graph. WAW 2020. Lecture Notes in Computer Science, vol 12091. Springer, Cham. https://doi.org/10.1007/978-3-030-48478-1_4

* (2020) SIAM Network Science Conference: https://ns20.cs.cornell.edu/abstracts/SIAMNS_2020_paper_31.pdf

* (2021) JMM 2021 talks and slides: https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3486 and https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3674

* (2021) Arash Dehghan-Kooshkghazi, Bogumił Kamiński, Łukasz Kraiński, Paweł Prałat, François Théberge, Evaluating Node Embeddings of Complex Networks, pre-print, https://arxiv.org/abs/2102.08275 and to appear, Journal of Complex Networks, Oxford University Press (2022).


### Code:

* Initial version in C: https://github.com/ftheberge/Comparing_Graph_Embeddings
* Scalable Julia Landmark-based version: https://github.com/KrainskiL/CGE.jl

# ABCD graphs -- Artificial Benchmark for Community Detection

* (2020) Pre-print: https://arxiv.org/abs/2002.00843

* (2020) SIAM Network Science Conference: https://ns20.cs.cornell.edu/abstracts/SIAMNS_2020_paper_33.pdf

* (2021) B. Kaminski, P. Pralat and F. Théberge, "Sequential and parallel generation of Artificial Benchmark for Community Detection (ABCD) graphs", to appead in the Book of Abstracts, Complex Networks Conference, 2020. Link to conference: https://easychair.org/smart-program/COMPLEXNETWORKS2020/2020-12-03.html#talk:162237

* (2021) B. Kaminski, P. Pralat and F. Théberge, "Artificial Benchmark for Community Detection (ABCD) - Fast random graph model with community structure", Network Science Journal (2021), pp. 1-26, https://doi.org/10.1017/nws.2020.45

* (2021) JMM 2021 talk and slides: https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3486

* (2021) B. Kaminski, P. Pralat, F. Théberge and T. Olczak, "Artificial Benchmark for Community Detection algorithm for simulation of social networks", Social Simulation Conference 2021, https://ssc2021.uek.krakow.pl/wp-content/uploads/2021/09/SSC_book_of_abstracts.pdf

* (2022) B. Kaminski, P. Pralat, F. Théberge, Asymptotic Properties of the ABCD Graph Benchmark with Community Structure, NetSci22 talk and slides: https://github.com/ftheberge/Slides/NetSci_Slides_2022.pdf

### Code:

* Julia code on GitHub: https://github.com/bkamins/ABCDGraphGenerator.jl
* Multithreaded code ABCDe: https://github.com/tolcz/ABCDeGraphGenerator.jl
* Notebooks to test the speed and properties of ABCD, ABCDe and LFR: https://github.com/bartoszpankratz/ABCDe_Experiments

# Hypergraph modularity and clustering

* (2018) Pre-print: https://arxiv.org/abs/1810.04816

* (2019) Bogumił Kamiński, Valérie Poulin, Paweł Prałat , Przemysław Szufel, François Théberge, "Clustering via hypergraph modularity", PLOS ONE, November 6, 2019, https://doi.org/10.1371/journal.pone.0224307

* (2021) Kamiński B., Prałat P., Théberge F. (2021) Community Detection Algorithm Using Hypergraph Modularity. In: Benito R.M., Cherifi C., Cherifi H., Moro E., Rocha L.M., Sales-Pardo M. (eds) Complex Networks & Their Applications IX. COMPLEX NETWORKS 2020 2020. Studies in Computational Intelligence, vol 943. Springer, Cham. https://doi.org/10.1007/978-3-030-65347-7_13 Link to conference: https://easychair.org/smart-program/COMPLEXNETWORKS2020/2020-12-03.html#talk:162304

* (2021) JMM 2021 talk and slides: https://meetings.ams.org/math/jmm2021/meetingapp.cgi/Paper/3482

### Code:

* H-modularity https://pnnl.github.io/HyperNetX/build/modularity.html is now part of HyperNetX: https://github.com/pnnl/HyperNetX

# AGC - Area under Gain Curves

A useful tool to compare binary classifiers's top scoring points.

### Code:

* PyPI: https://pypi.org/project/agc/
* GitHub (including example notebook): https://github.com/ftheberge/agc




