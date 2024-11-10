---
permalink: /
title: "Hu Junwei"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# [About Me](http://HJW577X.github.io/about_me)
I am a master student at the College of Informatics, Huazhong Agricultural University, and will obtain my master degree in June 2025.

My supervisors are [Prof. Zaiwen Feng](https://coi.hzau.edu.cn/info/1122/6168.htm) from the College of Informatics at Huazhong Agricultural University, [Prof. Michael Bewong](https://bjbs.csu.edu.au/schools/computing-mathematics-engineering/staff/profiles/senior-lecturers/michael-bewong) from the School of Computing, Mathematics & Engineering at Charles Sturt University, and [Prof. Selasi Kwashie](https://researchoutput.csu.edu.au/en/persons/selasi-kwashie) from the AI & Cyber Futures Institute at Charles Sturt University.

I'm working on data mining、representation learning on graph-structured data and applying them to downstream tasks e.g., link prediction and entity resolution. I'm also working on in-context learning for large language models.

# [Researchs](http://HJW577X.github.io/researchs)
## Data Mining
I have experience in logical rule mining on knowledge graphs through rule formulation and graph-theoretic algorithms, such as graph entity dependency (GED) and graph differential dependency (GDD), which contains a type of logical reasoning knowledge. It is expressed through a combination of graph patterns and dependency relationships based on graph patterns, and can be well applied to inference tasks in real world.

## Graph Representation Learning
The purpose of this work is to transform high-dimensional network structures into low-dimensional embedded representations for application to downstream tasks. I have experience in the following different graph representation learning techniques:

### Random Walk-based
Random walk-based methods will design a strategy for walking on the graph, starting from a node, randomly selecting a neighboring node and moving to that node, repeating this process to generate a node sequence. Subsequently, the generated node sequence will be input into a language model (e.g. CBOW, Skip-Gram, and BERT, etc.) for training to obtain the embedded representations of nodes. Early methods on homogeneous graphs include Deepwalk, Node2vec, and Struc2vec, etc., and methods on heterogeneous graphs include Metapath2vec, HIN2vec, and GATNE, etc.

### Message Passing-based
Message passing-based methods are a general framework for graph neural networks, which follows the "message passing paradigm", that is, nodes update their own feature vectors by exchanging information with their neighbors. This paradigm can include many variants of graph neural networks, such as methods for representing homogeneous graphs: GCN, GAE, GAT, and GraphSAGE, etc., and methods for representing heterogeneous graphs: RGCN, RGAT, HAN, HGT, and HetSANN, etc.

### Other Methods
I am also interested in other graph representation learning techniques such as auto-encoder, adversarial learning, and contrastive learning, etc.

## In-Context Learning
It refers to the capability of large language models to learn from a few demonstrations in the input context without any parameters updating.


# [Publications](http://HJW577X.github.io/publications)
## My major work (first author):

{% include base_path %}

{% for post in site.publications %}
  {% if post.title == '<small>When GDD meets GNN: A Knowledge-driven Neural Connection for Effective Entity Resolution in Property Graphs</small>' %}
    {% include archive-single.html %}
  {% endif %}
  {% if post.title == '<small>Heterogeneous Graph Neural Networks for Link Prediction in Biomedical Networks</small>' %}
    {% include archive-single.html %}
  {% endif %}
  {% if post.title == '<small>A Heterogeneous Network-based Contrastive Learning Approach for Predicting Drug-Target Interaction</small>' %}
    {% include archive-single.html %}
  {% endif %}
  {% if post.title == '<small>An Effective In-Context Learning Strategy for Entity Matching via Large Language Models</small>' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## My involved work:

{% include base_path %}

{% for post in site.publications %}
  {% if post.title == '<small>An Efficient Approach for Discovering Graph Entity Dependencies (GEDs)</small>' %}
    {% include archive-single.html %}
  {% endif %}
  {% if post.title == '<small>FastAGEDs: Fast Approximate Graph Entity Dependency Discovery</small>' %}
    {% include archive-single.html %}
  {% endif %}
  {% if post.title == '<small>Discovering Graph Differential Dependencies</small>' %}
    {% include archive-single.html %}
  {% endif %}
    {% if post.title == '<small>FastAGEDs+: Fast Approximate Graph Entity Dependency Discovery</small>' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
