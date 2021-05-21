# MOMDP

This work presents a novel greedy randomized adaptive search procedure approach for dealing with the maximum diversity problem from a multi-objective perspective. In particular, five of the most extended diversity metrics were considered, with the aim of maximizing all of them simultaneously. The metrics considered have been proven to be in conflict, i.e., it is not possible to optimize one metric without deteriorating another one. Therefore, this results in a multi-objective optimization problem where a set of efficient solutions that are diverse with respect to all the metrics at the same time must be obtained. A novel adaptation of the well-known greedy randomized adaptive search procedure, which has been traditionally used for single-objective optimization, was proposed. Two new constructive procedures are presented to generate a set of efficient solutions. Then, the improvement phase of the proposed algorithm consisted of a new efficient local search procedure based on an exchange neighborhood structure that follows a first improvement approach. An effective exploration of the exchange neighborhood structure is also presented, to firstly explore the most promising ones. This feature allowed the local search proposed to limit the size of the neighborhood explored, resulting in an efficient exploration of the solution space. The computational experiments showed the merit of the proposed algorithm, when comparing the obtained results with the best previous method in the literature. Additionally, new multi-objective evolutionary algorithms derived from the state-of-the-art were also included in the comparison, to prove the quality of the proposal. Furthermore, the differences found were supported by non-parametric statistical tests.

## Datasets

We downloaded the instances from the next website: https://grafo.etsii.urjc.es/optsicom/mdp/

We got the MDPLIB and used only the GKD set, which includes 145 instances.
