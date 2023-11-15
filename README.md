# Accelerating Actor-based Distributed Triangle Counting

***Code will be made public shortly!***

## About

Triangle counting is a cornerstone operation in large graph analytics. It has been a challenging problem historically, owing to the irregular and dynamic nature of the algorithm. This inhibits compile-time optimizations and also requires runtime optimizations such as message aggregation and load-imbalance mitigation. Popular triangle counting algorithms are either inherently slow, fail to take advantage of advanced hardware in modern processors, or involve sparse matrix operations.

With its support for fine-grained asynchronous messages, the Partitioned Global Address Space (PGAS) with the Actor model has been identified to be efficient for irregular applications [HCLIB ACTOR](https://hclib-actor.com/). However, few triangle counting implementations have been optimally implemented on top of PGAS Actor runtimes.

To address the above-mentioned challenges, we propose a set-intersection-based implementation of a distributed triangle counting algorithm atop the PGAS actor runtime. Evaluation of our approach on the PACE Phoenix cluster and the Perlmutter supercomputer showed encouraging results.

## Contact Us

Aniruddha Mysore (animysore@gatech.edu)

Kaushik Ravichandran (kravicja3@gatech.edu)

Poster presentation at Supercomputing'23 - [Link](https://sc23.conference-program.com/presentation/?id=rpost187&sess=sess291)

