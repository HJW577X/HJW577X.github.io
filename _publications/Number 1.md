---
title: "<small>When GDD meets GNN: A Knowledge-driven Neural Connection for Effective Entity Resolution in Property Graphs</small>"
collection: publications
permalink: /publication/Number-1
excerpt: 'Major Revision (Submited), _EDBT_, 2025 '
# date: 2009-10-01
# venue: 'Journal 1'
codeurl: 'https://github.com/Zaiwen/Entity_Resolution_Junwei_HU'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**Author:** *Hu, Junwei et al.*

**Abstract:** This paper studies the entity resolution (ER) problem in property graphs. ER is the task of identifying and linking different records that refer to the same real-world entity. It is commonly used in data integration, data cleansing, fraud detection, and other applications where it is important to have accurate and consistent data. In general, two predominant approaches exist in the literature: a) rule-based methods, and b) learning-based methods. On the one hand, rule-based techniques are often desired due to their explainability and ability to encode domain knowledge. Learning-based methods, on the other hand, are preferred due to their effectiveness in spite of their black-box nature. In this work, we devise a hybrid ER solution, GraphER, that leverages the strengths of both systems for property graphs. In particular, we adopt graph differential dependency (GDD) for encoding the so-called record-matching rules, and employ them to guide a graph neural network (GNN) based representation learning for the task. We conduct extensive empirical evaluation of our proposal on benchmark ER datasets including 17 graph datasets and 7 relational datasets in comparison with 9 state-of-the-art (SOTA) techniques. The results show that our approach provides a significantly better solution to addressing ER in graph data, both quantitatively and qualitatively, while attaining highly competitive results on the benchmark relational datasets w.r.t. the SOTA solutions.