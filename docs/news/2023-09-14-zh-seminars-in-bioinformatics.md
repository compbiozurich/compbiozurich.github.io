---
template: post.html
title: "SuperCellCyto: enabling efficient analysis of large scale cytometry datasets"
description: 'Zurich Seminars in Bioinformatics - Givanna Putri (WEHI)'
date: 2023-09-14
authors:
  - "@mbaudis"
links:
  - '[Github](https://github.com/phipsonlab/SuperCellCyto)'
  - '[Project Page](https://phipsonlab.github.io/SuperCellCyto-analysis/)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** The rapid advancements in cytometry technologies have enabled the quantification of up to 50 proteins across millions of cells at the single-cell resolution. The analysis of cytometry data necessitates the use of computational tools for tasks such as data integration, clustering, and dimensionality reduction. While numerous computational methods exist in the cytometry and single-cell RNA sequencing (scRNAseq) fields, many are hindered by extensive run times when processing large cytometry data containing millions of cells. Existing solutions, such as random subsampling, often prove inadequate as they risk excluding small, rare cell subsets.
 
To address this, we propose a practical strategy that builds on the SuperCell framework from the scRNAseq field. The supercell concept involves grouping single cells with highly similar transcriptomic profiles, and has been shown to be an effective unit of analysis for scRNAseq data.
 
We show that for cytometry datasets, there is no loss of information by grouping cells into supercells. Further, we demonstrate the effectiveness of our approach by conducting a series of downstream analyses on six publicly available cytometry datasets at the supercell level, and successfully replicating previous findings performed at the single cell level. We present a computationally efficient solution for transferring cell type labels from single-cell multiomics data which combines RNA with protein measurements, to a cytometry dataset, allowing for more precise cell type annotations.
 
Our SuperCellCyto R package and the associated analysis workflows are available on our GitHub repositories (https://github.com/phipsonlab/SuperCellCyto and https://phipsonlab.github.io/SuperCellCyto-analysis/).