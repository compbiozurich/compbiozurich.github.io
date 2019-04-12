---
title: 'ZH Seminars Bioinformatics - Bo Gao'
date: 2019-04-10
layout: default
author: '@KyleGao'
excerpt_separator: <!--more-->
www_link:
www_links_formatted:
pdf_file_name:
category:
  - events
tags:
  - seminars
---

## {{ page.title }}
### Minimum Error Normalization for Copy Number Analysis

* Wednesday, 2019-04-17
* 12:15 in Y-55L-12, UZH Irchel campus

<!--more-->

*Abstract* Copy number aberrations (CNAs) are abnormal changes of DNA copies in segments on chromosomes. They exhibit diverse and intriguing patterns in a wide range of cancers and are closely associated with tumorigenesis. Currently, the CNA profile of a tumor sample is usually generated using micro-array or high-throughput sequencing. Regardless of the technology, CNAs data is derived from relative measurement of signal intensity and the data generation processes are prone to noise contamination from several sources. Therefore, the copy number values in a CNA profile usually deviate from the their corresponding DNA levels, and the extent of deviation differs between profiles. This inconsistency poses a great challenge for data integration and comparison in large scale genome analysis. In this study, we present a novel method named Minimum Error Normalization of Copy Numbers (MENCN). For each CNA profile, MENCN first reduces the noise level, then calculate values representing the normal DNA copies (baseline) and the change of one copy (level distance), and finally normalize all values uniformly. Experiments of MENCN on simulated data showed an overall accuracy of 93% and 91% in determining baseline and level distance, respectively. Comparison of baseline and level distance estimation with ABSOLUTE and karyotyping on tumor cell lines NCI-60 produced results of high coherency. Lastly, we applied GISTIC on both the original and normalized CNA data from the Caner Genome Atlas (TCGA). The normalized data showed prominent improvement of both sensitivity and specificity in detecting focal regions. In general, MENCN is useful for CNA data normalization in research involving data of high volume and diverse quality. Supported with its informative output and visualization, it can also be used for quick analysis of single CNA profile.
