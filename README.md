# Multiple-fuzzy-Sugeno-lambda-measures-in-networks.-An-application. Appendix
In this repository we set some information related to the paper entitled "Multiple fuzzy Sugeno lambda-measures in networks. An application".
We detail the characterization and simulation process needed to generate several benchmark graphs which are considered in the corresponding "Computational results" section of the mentioned paper.
Each benchmark model represents a multi-dimensional extended vector fuzzy graph, so we distinguis two components in the generation process.
  1. The adjacency matrix. It is 256-matrix. In the Section 1 of the main document we detail the generation process, summarized in the algorithm "Generate Adjacency", as well        as the parameters considered.
  2. The additional information matrix. It is a 256-matrix, built from a family of r vectors, for whose generation we consider trapezoidal fuzzy number. We distinguis between        low and high fuzzy numbers.
  (a) Low fuzzy numbers. These are generated to represent, in each vector, the components related to the elements with a low value in the corresponding characteristic.
      The generation process is detailed in the Section 2,  summarized in the algorithm "Low Fuzzy Number".
  (b) High fuzzy numbers. These are generated to represent, in each vector, the components related to the elements with a high value in the corresponding characteristic.
      The generation process is detailed in the Section 3, summarized in the algorithm "High Fuzzy Number".
      
   As we consider a multi-dimensional context, then we explain the process to generate multiple vectors. The process is summarized in the algorithm "Generate Multiple Vectors", Section 4.
   Finally, in the "Matrix From Multiple Vectors" algorithm, Section 5, we detail how to build a synergies matrix from a family of vectors.
