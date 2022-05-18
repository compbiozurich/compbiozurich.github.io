---
title: 'ZH Sem Bioinfo - Elyas Heidari'
layout: default
author: '@mbaudis'
excerpt_separator: <!--more-->
www_link:
www_links_formatted:
pdf_file_name:
category:
  - events
tags:
  - seminars
  - BIO612
  - news
---

## {{ page.title }}
### Supervised spatial inference of dissociated single-cell data with _SageNet_

* Thursday, {{page.date | date: "%Y-%m-%d" }}
* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Spatially-resolved transcriptomics uncovers patterns of gene expression at supercellular, cellular, or subcellular resolution, providing insights into spatially variable cellular functions, diffusible morphogens, and cell-cell interactions. However, for practical reasons, multiplexed single cell RNA-sequencing remains the most widely used technology for profiling transcriptomes of single cells, especially in the context of large-scale anatomical atlassing.<!--more-->
Devising techniques to accurately predict the latent physical positions as well as the latent cell-cell proximities of such dissociated cells, represents an exciting and new challenge. Most of the current approaches rely on an ‘autocorrelation’ assumption, i.e., cells with similar transcriptomic profiles are located close to each other in physical space and vice versa. However, this is not always the case in native biological contexts due to complex morphological and functional patterning. To address this challenge, we developed SageNet, a graph neural network approach that spatially reconstructs dissociated single cell data using one or more spatial references. SageNet first estimates a gene-gene interaction network from a reference spatial dataset. This informs the structure of the graph on which the graph neural network is trained to predict the region of dissociated cells. Finally, SageNet produces a low-dimensional embedding of the query dataset, corresponding to the reconstructed spatial coordinates of the dissociated tissue. Furthermore, SageNet reveals spatially informative genes by extracting the most important features from the neural network model. We demonstrate the utility and robust performance of SageNet using molecule-resolved seqFISH and spot-based Spatial Transcriptomics reference datasets as well as dissociated single-cell data, across multiple biological contexts. SageNet is provided as an open-source python software package at <https://github.com/MarioniLab/SageNet>. Preprint available at <https://www.biorxiv.org/content/10.1101/2022.04.14.488419v1>
