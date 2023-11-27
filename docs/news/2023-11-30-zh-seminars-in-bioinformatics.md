---
template: post.html
title: "Siyuan Luo - Benchmarking computational methods for single-cell chromatin data analysis"
description: 'Zurich Seminars in Bioinformatics'
date: 2023-11-30
authors:
  - "@mbaudis"
links:
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Single-cell chromatin accessibility assays, such as scATAC-seq, are increasingly employed in individual and joint multi-omic profiling of single cells. As the accumulation of scATAC-seq and multi-omics datasets continue, challenges in analyzing such sparse, noisy, and high-dimensional data become pressing. Specifically, one challenge relates to optimizing the processing of chromatin-level measurements and efficiently extracting information to discern cellular heterogeneity. This is of critical importance, since the identification of cell types is a fundamental step in current single-cell data analysis practices.

We benchmarked 8 feature engineering pipelines derived from 5 recent methods to assess their ability to discover and discriminate cell types. By using 10 metrics calculated at the cell embedding, shared nearest neighbor graph, or partition levels, we evaluated the performance of each method at different data processing stages. This comprehensive approach allowed us to thoroughly understand the strengths and weaknesses of each method and the influence of parameter selection.

Our analysis provides guidelines for choosing analysis methods for different datasets. Overall, feature aggregation, SnapATAC, and SnapATAC2 outperform latent semantic indexing-based methods. For datasets with complex cell-type structures, SnapATAC and SnapATAC2 are preferred. With large datasets, SnapATAC2 and ArchR are most scalable.