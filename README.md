# AAAI 2019
## A Combinatorial Framework for Focusing Topic Modeling Results
### Data

The Huffington Post RSS feeds (US version) from June the 20th until Sept. the 8th, 2016. Each article is considered a document in the corpus, which is challenging as there are articles ona wide variety of topics: i.e. sports, politics and even life style (i.e. cooking). We use the LDA model (Blei et al., 2003) using the MALLET tool (http://mallet.cs.umass.edu). Unless otherwise stated, we used k = 100 topics.

The Harry Potter Data Set we study is a set of 38,997 paragraphs extracted from the 7 book series Harry Potter, by J.K. Rowling.
This data were taken from previous work (Waumans et al. 2015) that studied the topology of social networks. Each paragraph is considered a document in the corpus. Little previous work has experimented topic labeling lwith a such complex material

As the right to release the data is restricted, we provide the output of the algorithm only. It is organized as follows :

- us-newsClean_default_distrib_docs : the distribution of topics on the document space : p(z|d)
- us-newsClean_default_topicwords : the distribution of the top n words on the topic space : p(w|z)

### Src

An example of a the knapsack formulation in section 2.1 is in knapSackSolve.mps.
An example of a the knapsack + set cover formulation in section 2.2 is in knapSackSolvePlusSetCover.mps.
An example of a the multiple knapsack formulation in section 2.3 is in multiKnapSackSolve.mps.

These problem instances were derived from the HuffingtonPost and can be run using any ILP solver than reads the IBM .mps standard file format.

The variables X1 ... X100 are Boolean variables that determine which topics are chosen
