---
title: "<small>An Effective In-Context Learning Strategy for Entity Matching via Large Language Models</small>"
collection: publications
permalink: /publication/Number-4
excerpt: 'Working, 2025'
# date: 2009-10-01
# venue: 'Journal 1'
# codeurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**Author:** *Hu, Junwei et al.*  

**Abstract:** Entity matching (EM) is an important data integration task with a wide range of applications. State-of-the-art (SOTA) solutions for EM rely on pre-trained language models (PLMs), which require fine-tuning on fully labeled data. Recently, EM based on generative large language models (LLMs) with context prompt engineering (in-context learning) has shown great promise due to their high few-shot performance. However, existing studies have not deeply explored the impact of labeled input context demonstrations on the EM task. To maximize the potential of LLMs, in this work, we investigate different in-context learning (ICL) strategies for EM via LLMs, mainly including two aspects: (i) how different context demonstration methods help LLMs to learn more suitable examples provided; and (ii) how different numbers of demonstrations help LLMs to make the best decisions. According to our findings, different demonstration methods provide different types of context examples that directly affect the decision effect of LLMs, and too many or too few demonstrations can lead to the addition of noise or lack of contextual knowledge, resulting in suboptimal performance. Thus, we design a strategy of top-k demonstrations in the given context demonstration method to guide LLMs in answering more accurately, and empirical results show that LLMs using this strategy achieve excellent performance over benchmark datasets compared to the SOTA techniques based on fine-tuned PLMs. Further, this work verifies ICL ability of LLMs can effectively improve the result of EM without any domain-specific training data.
