---
template: post.html
title: "Daniel Incicau - Evaluation of cell type annotation methods in multiplexed imaging"
description: 'Zurich Seminars in Bioinformatics'
date: 2023-12-08
authors:
  - "@mbaudis"
links:
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** In the field of biomedical imaging, multiplexed imaging technologies have become indispensable for complex tissue analysis, enabling unprecedented depth of cellular and molecular understanding. This technology allows the spatial profiling of molecular markers within tissues at a single-cell resolution. However, the novelty of the technology requires specialised computational tools to extract biologically meaningful information. In recent years, numerous methods have emerged for each data analysis step in multiplexed imaging. Yet, it is still unclear which method is best and under what circumstances.

In this work, we focus on the cell type annotation step of data analysis, where we evaluate a selection of state-of-the-art supervised and unsupervised approaches. The aim is to establish a quantitative performance framework for these methods with corresponding guidelines. Furthermore, we examine the effects of different data normalisation and integration strategies in single-cell data derived from images. We also assess how lateral spillover compensation methods, such as REDSEA, influence downstream phenotyping. We found out that STELLAR is the best-performing supervised method leveraging spatially-resolved data. While unsupervised methods generally show comparable performance, PIXIE was able to classify all cell types and stands out due to its ease of use.

Although this evaluation only focuses on proteomics profiling using Imaging Mass Cytometry (IMC) data, its applicability extends to other highly multiplexed imaging technologies. Most importantly, we provide an extensible evaluation framework that can easily incorporate new methods and datasets in the future.