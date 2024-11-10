---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

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
    {% if post.title == '<small>GIG: Graph Data Imputation With Graph Differential Dependencies</small>' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
