# EMNLP2018
## A Combinatorial Framework for Focusing Topic Modeling Results
### Data

- us-newsClean_default_distrib_docs : distribution of topics on the document space : p(z|d)
- us-newsClean_default_topicwords : distribution of the top n words on the topic space : p(w|z)

### Set

An example of a the knapsack formulation in section 2.1 is in knapSackSolve.mps.
An example of a the knapsack + set cover formulation in section 2.2 is in knapSackSolvePlusSetCover.mps.
An example of a the multiple knapsack formulation in section 2.3 is in multiKnapSackSolve.mps.

These problem instances were derived from the HuffingtonPost These can be run using any ILP solver than reads the IBM .mps standard file format.

The variables X1 ... X100 are Boolean variables that determine which topics are chosen
