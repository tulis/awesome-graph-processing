# Awesome - Graph Processing
A collection of awesome papers about graph processing.

## Categories
### Single & Memory
- **GraphLab** - `GraphLab: A New Framework For Parallel Machine Learning` (UAI'10). [[paper]](https://dslpitt.org/papers/10/p340-low.pdf)
- **Galois** - `A Lightweight Infrastructure for Graph Analytics` (SOSP'13). [[paper]](http://sigops.org/sosp/sosp13/papers/p456-nguyen.pdf)
- **GRACE** - `Asynchronous Large-Scale Graph Processing Made Easy` (CIDR'13). [[paper]](http://www.cs.cornell.edu/~guoz/Guozhang%20Wang%20publications/grace_cidr2013.pdf)
- **Ligra** - `Ligra: A Lightweight Graph Processing Framework for Shared Memory` (PPoPP'13). [[paper]](https://www.cs.cmu.edu/~jshun/ligra.pdf), [[code]](https://github.com/jshun/ligra)
- **Polymer** - `NUMA-Aware Graph-Structured Analytics` (PPoPP'15). [[paper]](https://people.csail.mit.edu/jshun/6886-s18/papers/Polymer.pdf), [[code]](https://github.com/realstolz/polymer)
- **GraphMat** - `GraphMat: High performance graph analytics made productive` (VLDB'15). [[paper]](https://pdfs.semanticscholar.org/b513/711621e81d0abd042e0877ca751581a993f5.pdf), [[code]](https://github.com/narayanan2004/GraphMat)

### Distributed & Memory
- **Pregel** - `Pregel: A System for Large-Scale Graph Processing` (SIGMOD'10). [[paper]](https://kowshik.github.io/JPregel/pregel_paper.pdf)
- **Distributed GraphLab** - `Distributed GraphLab: A Framework for Machine Learning and Data Mining in the Cloud` (VLDB'12). [[paper]](http://vldb.org/pvldb/vol5/p716_yuchenglow_vldb2012.pdf)
- **PowerGraph** - `PowerGraph: Distributed Graph-Parallel Computation on Natural Graphs` (OSDI'12). [[paper]](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-167.pdf), [[code]](https://github.com/jegonzal/PowerGraph)
- **GPS** - `GPS: A Graph Processing System` (SSDBM'13). [[paper]](http://ilpubs.stanford.edu:8090/1039/7/gps_ssdbm.pdf)
- **Mizan** - `Mizan: A System for Dynamic Load Balancing in Large-scale Graph Processing` (EuroSys'13). [[paper]](http://www.cs.cornell.edu/~djwill/pubs/mizan.pdf), [[code]](https://github.com/khayyatzy/Mizan)
- **Blogel** - `Blogel: A Block-Centric Framework for Distributed Computation on Real-World Graphs` (VLDB'14). [[paper]](http://people.csail.mit.edu/yilu/papers/p1981-yan.pdf), [[code]](http://www.cse.cuhk.edu.hk/blogel/)
- **Giraph++** - `From "Think Like a Vertex" to "Think Like a Graph"` (VLDB'14). [[paper]](https://researcher.watson.ibm.com/researcher/files/us-ytian/giraph++.pdf)
- **GraphX** - `GraphX: Graph Processing in a Distributed Dataflow Framework` (OSDI'14). [[paper]](https://www.usenix.org/node/186217), [[code]](https://spark.apache.org/graphx/)
- **PowerLyra** - `PowerLyra: Differentiated Graph Computation and Partitioning on Skewed Graphs` (EuroSys'15). [[paper]](https://ipads.se.sjtu.edu.cn/lib/exe/fetch.php?media=publications:powerlyra-eurosys15.pdf), [[code]](https://github.com/realstolz/powerlyra)
- **PowerSwith** - `SYNC or ASYNC: Time to Fuse for Distributed Graph-Parallel Computation` (PPoPP'15). [[paper]](https://ipads.se.sjtu.edu.cn/_media/publications/powerswitch-ppopp15.pdf)
- **Gemini** - `Gemini: A Computation-Centric Distributed Graph Processing System` (OSDI'16). [[paper]](https://www.usenix.org/system/files/conference/osdi16/osdi16-zhu.pdf), [[code]](https://github.com/thu-pacman/GeminiGraph)
- **GRAPE** - `Parallelizing Sequential Graph Computations` (SIGMOD'17). [[paper]](http://homepages.inf.ed.ac.uk/wenfei/papers/sigmod17-GRAPE.pdf)

### Single & Storage
- **GraphChi** - `GraphChi: Large-Scale Graph Computation on Just a PC` (OSDI'12). [[paper]](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-126.pdf), [[code]](https://github.com/GraphChi/graphchi-cpp)
- **X-Stream** - `X-Stream: Edge-centric Graph Processing using Streaming Partitions` (SOSP'13). [[paper]](https://infoscience.epfl.ch/record/188535/files/paper.pdf), [[code]](https://github.com/epfl-labos/x-stream)
- **TurboGraph** - `TurboGraph: A Fast Parallel Graph Engine Handling Billion-scale Graphs in a Single PC` (KDD'13). [[paper]](http://www.eiti.uottawa.ca/~nat/Courses/csi5387_Winter2014/paper1.pdf)
- **PathGraph** - `Fast Iterative Graph Computation: A Path Centric Approach` (SC'14). [[paper]](https://people.csail.mit.edu/jshun/6886-s18/papers/PathGraph.pdf), [[code]](https://github.com/CGCL-codes/PathGraph)
- **GridGraph** - `GridGraph: Large-Scale Graph Processing on a Single Machine Using 2-Level Hierarchical Partitioning` (USENIX ATC'15). [[paper]](https://www.usenix.org/system/files/conference/atc15/atc15-paper-zhu.pdf), [[code]](https://github.com/thu-pacman/GridGraph)
- **VENUS** - `VENUS: Vertex-Centric Streamlined Graph Computation on a Single PC` (ICDE'15). [[paper]](https://www.cse.cuhk.edu.hk/~cslui/PUBLICATION/ICDE15_Venus.pdf)
- **FlashGraph** - `FlashGraph: Processing Billion-Node Graphs on an Array of Commodity SSDs` (FAST'15). [[paper]](https://www.usenix.org/system/files/conference/fast15/fast15-paper-zheng.pdf), [[code]](https://github.com/Smerity/FlashGraph)
- **Lumos** - [[`LUMOS: Dependency-Driven Disk-based Graph Processing`]](]](https://www.usenix.org/conference/atc19/presentation/vora)) (USENIX ATC'19). [[paper]](https://www.usenix.org/system/files/atc19-vora.pdf), [[code]](https://github.com/pdclab/lumos), [[video1]](https://youtu.be/1tuAl7l-FBM), [[video2]](https://youtu.be/v-WwRhGKZ2o), [[slide1]](https://www.usenix.org/sites/default/files/conference/protected-files/atc19_slides_lt_vora_rev.pdf), [[slide2]](https://www.usenix.org/sites/default/files/conference/protected-files/atc19_slides_vora.pdf)

### Distributed & Storage
- **Chaos** - `Chaos: Scale-out Graph Processing from Secondary Storage` (SOSP'15). [[paper]](https://www.cl.cam.ac.uk/~ey204/teaching/ACS/R244_2017_2018/papers/roy_sosp_2015.pdf), [[code]](https://github.com/epfl-labos/chaos)
- **Pregelix** - `Pregelix: Big(ger) Graph Analytics on A Dataflow Engine` (VLDB'15). [[paper]](http://www.vldb.org/pvldb/vol8/p161-bu.pdf), [[code]](https://github.com/pregelix/pregelix)
- **TurboGraph++** - `TurboGraph++: A Scalable and Fast Graph Analytics System` (SIGMOD'18). [[paper]]()

## References
1. [Papers on Graph Aanlytics](https://people.csail.mit.edu/jshun/graph.shtml)


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
