---
template: blog_post.html
title: Leveraging single-cell RNA-seq with CITE-seq data
description: 'Zurich Seminars in Bioinformatics - Anthony Sonrel'
date: 2021-03-04
authors:
  - '@mbaudis'
  - '@ansonrel'
---

* 12:15 om  ZOOM Call


Recently, the ability to profile gene expression at the single-cell level has been expanded to include the measure of both RNA and protein levels from the same cells ([Stoeckius et al., 2017](https://www.nature.com/articles/nmeth.4380)). While RNA-based data has broadly proven sufficient for cell type detection and classification, its usage for determining drug target is still limiting: we still often rely on the assumption that RNA expression levels are representative of protein expression levels.<!--more-->
 In this presentation I will summarize the results of a six-months internship at Roche that aimed to bridge the gap between the RNA and the protein worlds.

In the first part of the presentation, I will briefly present Besca ([Maedler et al., 2020](https://www.biorxiv.org/content/10.1101/2020.08.11.245795v2)), a single-cell analysis workflow based on scanpy that allows to process raw single-cell RNA-seq data to annotated clusters. Besca was recently extended to CITE-seq analysis to provide a simple multimodal analysis workflow for this type of data. 

In the second part of the presentation, I will present a novel neural network, cTP-net ([Zhou et al., 2020](https://www.nature.com/articles/s41467-020-14391-0)), for the prediction of protein expression from raw single-cell RNA-seq data. cTP-net is able to learn the relation between RNA and protein levels and provides accurate predictions in different settings. I will present the network architecture, the enhancements that we brought to it and example applications. 

