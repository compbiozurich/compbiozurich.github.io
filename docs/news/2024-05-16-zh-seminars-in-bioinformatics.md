---
template: post.html
title: "Systematic comparison of sequencing-based spatial transcriptomic methods with cadasSTre and SpatialBench<br/>Prof Matthew Ritchie, Epigenetics and Development Division (WEHI)"
description: 'Zurich Seminars in Bioinformatics'
date: 2024-05-16
authors:
  - "@mbaudis"
links:
  - '[Ritchie Lab WEHI](https://www.wehi.edu.au/laboratory/ritchie-lab/)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Sequencing-based Spatial Transcriptomics (sST) allows gene expression to be measured within complex tissue contexts. Although a wide array of sST technologies are currently available to researchers, efforts to comprehensively benchmark different platforms are currently lacking. The inherent variability across technologies and datasets poses challenges in formulating standardized evaluation metrics.

To address this, we established a collection of reference tissues and regions characterized by well-defined histological architecture and other biological ground truth and used them to generate the cadasSTre and SpatialBench datasets that compare 11 sST methods. We highlight molecular diffusion as a variable parameter across different methods and tissues, significantly impacting the effective resolution. Furthermore, we observed that spatial transcriptomic data demonstrate unique attributes beyond merely adding a spatial axis to single-cell data, including an enhanced ability to capture patterned rare cell states along with specific markers, albeit being influenced by multiple factors including sequencing depth and resolution. For the 10X Visium platform, we benchmarked the performance of different sample handling approaches after preprocessing, explored spatially variable gene detection and the ability of clustering and cell deconvolution to identify expected cell types and tissue regions. Multi-sample differential expression analysis was able to recover known gene signatures related to biological sex or gene knockout. Our datasets and analyses serve as a practical guide for sST users and will be useful in future benchmarking studies.