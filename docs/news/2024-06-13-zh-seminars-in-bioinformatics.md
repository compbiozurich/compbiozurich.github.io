---
template: post.html
title: "On the identification of differentially-active transcription factors from ATAC-seq data<br/>Emanuel Sonder"
description: 'Zurich Seminars in Bioinformatics'
date: 2024-06-13
authors:
  - "@mbaudis"
links:
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** ATAC-seq has emerged as a rich epigenome profiling technique, and is commonly used to identify Transcription Factors (TFs) underlying given phenomena. A number of methods can be used to identify differentially-active TFs through the accessibility of their DNA-binding motif, however little is known on the best approaches for doing so. We benchmarked several such methods using a combination of curated datasets with various forms of short-term perturbations on known TFs, as well as semi-simulations. <!--more-->We included both methods specifically designed for this type of data as well as some that can be repurposed for it. We also investigated variations to these methods, and identify three particularly promising approaches (chromVAR-limma with critical adjustments, monaLisa and a combination of GC smooth quantile normalization and multi-variate modeling). We further investigated the specific use of nucleosome-free fragments, the combination of top methods, and the impact of technical variation. 
Our benchmark does provide insights and recommendations for identifying differentially-active TFs from ATAC-seq data.
