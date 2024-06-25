---
template: post.html
title: "Marker identification and cell annotation approaches for (spatial) transcriptomic data to unravel tissue cellular heterogeneity<br/>Jinjin Chen (WEHI)"
description: 'Zurich Seminars in Bioinformatics'
date: 2024-06-27
authors:
  - "@mbaudis"
links:
  - '[Jinjin @ WEHI](https://findaresearcher.wehi.edu.au/chen.j)'
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Advances in technology have produced an unprecedented volume and types of multi-omics and spatial datasets crucial for identifying markers in biological and medical research. My PhD focused on developing methods for marker and cell type identification in a range of data types, ranging from bulk-RNAseq, single cell RNAseq to single cell spatial transcriptomics. 

In this presentation, I’ll first briefly introduce mastR, a Bioconductor package for automatically identifying markers in bulk RNA sequencing data. mastR employs a rank-product based test by leveraging statistical results from edgeR and limma to identify markers with precision akin to expert curation. Next, I’ll describe an ensemble workflow that integrates various cell annotation methods <!--more-->commonly used for single cell analysis for single cell spatial transcriptomics, shedding light on the complex cell compositions and structures in tissues and to overcome the challenge of identifying cell types or proportions amongst the tissues. Noting an existing difficulty in identifying rare cell populations due to the bias in most methods towards dominant cell populations, I leveraged the power of a modified form of term frequency-inverse document frequency (TF-IDF) and expectation maximization (EM) algorithm to develop a gene-set scoring and marker identification package smartid to identifiy markers for rare populations. 

Overall, I’ll present tools that I’ve developed to improve marker and cell type identification in the different omics and spatial datasets. The work aims to advance the understanding of tissue heterogeneity and provide biological insights to untangle the transcriptomic complexity of cancer and diseases.