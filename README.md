
This is the legacy code (published in [1]) of the first prototypical version of the Contract Automata Toolkit Library (CATLib), part of the 
Contract Automata Toolkit (CAT) (https://github.com/ContractAutomataProject).  
Initially, CAT only contained CATLib, thus CATLib was referred as CAT in [1].
This repository contains a nucleus of the old version of CATLib, prior to its extension to variability [2], abstract synthesis [3], and its refactoring [4] . 
This repository contains other original functionalities that are not in the intersection with CATLib (e.g., AMPL models of weak agreement, 
branching condition, mixed choice checking). 

References:

[1] Basile, D., Degano, P., Ferrari, G.L. and Tuosto, E., 2016, June. Playing with our CAT and communication-centric applications. In International Conference on Formal Techniques for Distributed Objects, Components, and Systems (pp. 62-73). Springer, Cham.
https://link.springer.com/content/pdf/10.1007%2F978-3-319-39570-8_5.pdf

```tex
@inproceedings{DBLP:conf/forte/BasileDFT16,
  author    = {Davide Basile and
               Pierpaolo Degano and
               Gian Luigi Ferrari and
               Emilio Tuosto},
  editor    = {Elvira Albert and
               Ivan Lanese},
  title     = {Playing with Our {CAT} and Communication-Centric Applications},
  booktitle = {Formal Techniques for Distributed Objects, Components, and Systems
               - 36th {IFIP} {WG} 6.1 International Conference, {FORTE} 2016, Held
               as Part of the 11th International Federated Conference on Distributed
               Computing Techniques, DisCoTec 2016, Heraklion, Crete, Greece, June
               6-9, 2016, Proceedings},
  series    = {Lecture Notes in Computer Science},
  volume    = {9688},
  pages     = {62--73},
  publisher = {Springer},
  year      = {2016},
  url       = {https://doi.org/10.1007/978-3-319-39570-8\_5},
  doi       = {10.1007/978-3-319-39570-8\_5},
  timestamp = {Tue, 14 May 2019 10:00:50 +0200},
  biburl    = {https://dblp.org/rec/conf/forte/BasileDFT16.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

[2] Basile, D., ter Beek, M.H., Degano, P., Legay, A., Ferrari, G.L., Gnesi, S. and Di Giandomenico, F., 2020. Controller synthesis of service contracts with variability. Science of Computer Programming, 187, p.102344. 
https://www.sciencedirect.com/science/article/pii/S0167642318302260

[3] Pugliese, R., Ter Beek, M.H. and Basile, D., 2020. Synthesis of orchestrations and choreographies: bridging the gap between supervisory control and coordination of services. Logical Methods in Computer Science, 16.
https://lmcs.episciences.org/6527

[4] Basile, D. and Beek, M.H.T., 2021, June. A clean and efficient implementation of choreography synthesis for behavioural contracts. In International Conference on Coordination Languages and Models (pp. 225-238). Springer, Cham.
https://link.springer.com/chapter/10.1007/978-3-030-78142-2_14

----------------------------------------------------------------------------


The directory JaMaTa contains the java tool, see JaMaTa/README.

The folder ampl contains a tool implemented in AMPL for deciding if a CA is weakly safe and admits weak agreement,
see README inside ampl.

Developed with JDK 7 and Eclipse.
A file Readme is located in the workspace with some useful comments. 

