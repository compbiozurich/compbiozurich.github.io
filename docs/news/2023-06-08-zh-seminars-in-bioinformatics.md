---
template: blog_post.html
title: Modeling the Tumor Microenvironment with Graph Concept Learning 
description: 'Zurich Seminars in Bioinformatics - Santiago Castro Dau'
date: 2023-06-08
authors:
  - "@mbaudis"
links:
  - '[www](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Heterogeneity is an emergent property of tumors, linked to cancer resistance and poor treatment outcomes [^1]. Geometric deep learning using graph representations has emerged as a promising approach to investigate tumor heterogeneity. Still, these approaches suffer from interpretability and transferability limitations [^2]. In this work, we propose a geometric deep-learning model with an interpretability framework to predict metadata from spatial datasets.<!--more--> Our approach draws inspiration from concept learning in computer vision, introducing concept graphs as a way of redefining the input space in terms of high-level premises that are relevant to the task at hand [3]. Concept graphs are cell graphs, which are graphical representations of a tissue, typically extracted from an image, where nodes represent cells and edges between nodes denote adjacency between cells. However, concept graphs are constructed only on a subset of all cells, where the filtering that induces a subset is defined by a premise. For example, well-established cancer hallmarks (e.g., tumor-promoting inflammation) can be used as premises to construct concept graphs where only cells that participate in the relevant interactions (e.g., tumor-immune cells) are included. By mixing and matching different premises, our approach offers a novel way of modeling the tumor microenvironment.

In summary, our approach decomposes each tumor sample into concept graphs, computes embeddings for each one of them using a concept-specific graph neural network, and finally, integrates all embeddings in a downstream prediction engine with an attention mechanism [^4]. This mechanism highlights the relevance of each premise for a given prediction, providing an avenue for interpretation. The novelty of our approach lies in disentangling complex tumor graphs into interpretable concept graphs, allowing us to explore the relevance of inputs in terms of high-level premises instead of low-level features such as pixels or nodes in a graph. We applied our framework to a publicly available breast cancer imaging mass cytometry dataset [^5], achieving highly accurate and interpretable predictions. With spatial omics and multiplexed imaging data becoming increasingly popular, we hope that our approach will offer an interpretable and transferable framework that can assist in identifying cancer-related mechanisms and their relevance for clinical predictions. 

[^1]:  Andriy Marusyk, Vanessa Almendro, and Kornelia Polyak. “Intra-tumor heterogeneity: a looking glass for cancer?” In: Nature Reviews Cancer 12.5 (May 2012). Number: 5 Publisher: Nature Publishing Group, pp. 323–334. issn: 1474-1768. doi: 10.1038/nrc3261.

[^2]:  Cynthia Rudin. “Stop explaining black-box machine learning models for high-stakes decisions and use interpretable models instead”. In: Nature Machine Intelligence 1.5 (May 2019). Number: 5 Publisher: Nature Publishing Group, pp. 206–215. issn: 2522-5839. doi: 10.1038/s42256-019-0048-x. 

[^3]:  Kaidi Cao, Maria Brbic, and Jure Leskovec. Concept Learners for Few- Shot Learning. Mar. 20, 2021. arXiv: 2007.07375[cs,stat].

[^4]:  Ashish Vaswani et al. Attention Is All You Need. Dec. 5, 2017. doi: 10.48550/arXiv.1706.03762. arXiv: 1706.03762[cs].

[^5]:  Hartland W. Jackson et al. “The single-cell pathology landscape of breast cancer”. In: Nature 578.7796 (Feb. 2020). Number: 7796 Publisher: Nature Publishing Group, pp. 615–620. issn: 1476-4687. doi: 10.1038/s41586-019-1876-x. 