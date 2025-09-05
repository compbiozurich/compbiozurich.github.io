---
template: post.html
title: "Associating cancer-specific variants with methylation changes using nanopore genome dat<br/>Halimat Atanda (PhD student, University of Queensland)"
description: 'Zurich Seminars in Bioinformatics'
date: 2025-09-11
authors:
  - "@mbaudis"
links:
#  - '[]()'
---

* 10:30 UZH Irchel Y17-H-05

**Abstract** Advancement in high throughput sequencing technologies has eased the extraction of the whole genome from biological samples and the identification of genomic variants that define molecular phenotypes. This has resulted in a relative abundance of genomic data, especially variants, with limited understanding of their functional or regulatory impacts.<!--more--> The presence of genomic variation and base modification on sequence reads generated from nanopore technology offers an opportunity to link a somatic or disease-specific variant to changes in methylation profile and offer insights into genetic-epigenetic regulation mechanisms in diseases. 

I will present an ongoing approach to develop an image-based classification model using convolutional neural networks, with an overall goal to predict genetic variants associated with methylation pattern changes in cancer genomes. I trained the model using individual phased sequence reads, single nucleotide variants, per-base methylation probability, and differentially methylated regions from DSS (Dispersion Shrinkage for Sequencing data) tool. The sequence reads were obtained from nanopore sequence data of MCF7 breast cancer cell lines. Oversampling of the positive class was applied to account for class imbalance and the following hyperparameters were varied during the initial training process: model depth, learning rate, and batch size. I use MCC (Mathews Correlation Coefficient) and F1 score as performance metrics to ensure the limited positive class is accounted for. The intended output of the tool would be a ranked table containing variant positions, predicted association with methylation difference (positive, negative, or ambiguous), and the direction of methylation change (increase or decrease) with p-values.

