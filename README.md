# Phylogenetics in R

Collection of scripts, functions, methods for building and analysing tree diagrams in R.


* UPGMA
* NJ
* Ultrametric and binary tests
* Tree shape metrics 





Tips and Notes:

If a tree is hard to read, transform the edge lengths by sqrt (this keeps relative lengths whilst making nodes easier to see)
tree$edge.length <- sqrt(tree$edge.length)
