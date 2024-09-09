---
template: post.html
title: "Bias Correction and Differential Motif Activity in ATAC-seq Data<br/>Jiayi Wang"
description: 'Zurich Seminars in Bioinformatics'
date: 2024-07-18
authors:
  - "@mbaudis"
links:
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** The Assay for Transposase-Accessible Chromatin using sequencing (ATAC-seq) has become widely adopted for assessing chromatin accessibility due to its efficiency in time and input material. However, technical biases in ATAC-seq data can complicate the downstream analysis tasks, and here we focus on identifying differentially-active transcription factors (TFs).<!--more-->

A recent benchmarking study identified a variation of chromVAR as the preferred method for this task, but we observed that it suffers from an incomplete and computationally intensive bias correction strategy and overlooks the footprint characteristics of TF binding. To address these limitations, we developed two alternative approaches: the weight and insertion models. These models offer enhanced statistical performance, with the weight model effectively correcting various technical biases.

