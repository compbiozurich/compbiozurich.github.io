---
template: post.html
title: "Spatial Domain Detection in Spatial Transcriptomics: A Consensus Clustering Approach<br/>Sarusan Kathirchelvan"
description: 'Zurich Seminars in Bioinformatics'
date: 2024-12-12
authors:
  - "@mbaudis"
links:
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Spatial transcriptomics maps gene expression within the spatial context of tissues, offering deep insights into tissue architecture and function. A key challenge in this field is identifying spatial domains: regions where cells share similar transcriptomic profiles. Often, these domains are defined using manual anatomical annotations, which may not fully capture the complexity of gene expression patterns and might introduce biases based on existing knowledge of tissue organization. This talk examines the notion of "ground truth" in spatial domain detection, questioning the reliance on manual annotations as the definitive reference.<!--more--> The primary objective is to develop a consensus clustering workflow that proposes an alternative, data-driven ground truth. By integrating clustering results from multiple spatial clustering methods, this workflow generates a unified clustering solution that reflects the intrinsic transcriptomic profile of the data. We demonstrate that consensus clustering can serve as a powerful tool to propose alternative ground truths in spatial transcriptomics.