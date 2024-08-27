---
# layout: archive
permalink: /researchs/
title: "Researchs"
author_profile: true
---

## Data Mining
I have experience in logical rule mining on knowledge graphs through rule formulation and graph-theoretic algorithms, such as graph entity dependency (GED) and graph differential dependency (GDD), which contains a type of logical reasoning knowledge. It is expressed through a combination of graph patterns and dependency relationships based on graph patterns, and can be well applied to inference tasks in real world.

## Graph Representation Learning
The purpose of this work is to transform high-dimensional network structures into low dimensional embedded representations for application to downstream tasks. I have experience in the following different graph representation learning techniques:

### Random Walk-based
Random walk based methods will design a strategy for walking on the graph, starting from a node, randomly selecting a neighboring node and moving to that node, repeating this process to generate a node sequence. Subsequently, the generated node sequence will be input into a language model (e.g. CBOW, Skip-Gram, and BERT, etc.) for training to obtain the embedded representations of nodes. Early methods on homogeneous graps include Deepwalk, Node2vec, and Struc2vec, etc., and methods on heterogeneous graphs include Metapath2vec, HIN2vec, and GATNE, etc.

### Message Passing-based
Message passing based methods are a general framework for graph neural networks, which follows the "message passing paradigm", that is, nodes update their own feature vectors by exchanging information with their neighbors. This paradigm can include many variants of graph neural networks, such as methods for representing homogeneous graphs: GCN, GAE, GAT, and GraphSAGE, etc., and methods for representing heterogeneous graphs: RGCN, RGAT, HAN, HGT, and HetSANN, etc.

### Other Methods
I am also interested in other graph representation learning techniques such as auto-encoder, adversarial learning, and contrastive learning, etc.