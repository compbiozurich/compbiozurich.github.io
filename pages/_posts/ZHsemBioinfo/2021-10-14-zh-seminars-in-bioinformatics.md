---
title: 'ZH Sem Bioinfo - David Wissel'
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

### Supervised Hierarchical Autoencoders for Multi-Omics Integration in Cancer Survival Models

* Thursday, {{page.date | date: "%Y-%m-%d" }}
* 12:00 UZH Irchel Y55-l-06/08 and ZOOM Call (12:15)

**Abstract** With the increasing amount of high-throughput sequencing data becoming available, the proper integration of differently sized and heterogeneous molecular and clinical groups of variables has become crucial in cancer survival models. 

<!--more-->

Due to the difficulty of multi-omics integration, the Cox Proportional-Hazards (Cox PH) model using clinical data has remained one of the best-performing methods [Herrmann et al., 2021]. This motivates the need for new models which can successfully perform multi-omics integration in survival models and outperform the Cox PH model. Furthermore, there is a strong need to make multi-omics models more sparse and interpretable to encourage their usage in clinical settings.

We developed a novel neural architecture, termed Supervised Hierarchical Autoencoder (SHAE), based on supervised autoencoders and Sparse-Group-Lasso regularization. Our new method performed competitively with the best performing statistical models used for multi-omics survival analysis. Moreover, it outperformed the Cox PH model using clinical data. We further showed that surrogate linear models for SHAE trained on a subset of multi-omics groups achieved competitive performance at consistently high sparsity levels, enabling usage within clinics. Alternatively, surrogate models can act as a feature selection step, permitting improved performance in arbitrary downstream survival models. 
