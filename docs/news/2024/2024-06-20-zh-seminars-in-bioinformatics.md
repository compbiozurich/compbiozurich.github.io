---
template: post.html
title: "Robust data-driven gene expression state inference for RNA-seq using curated intergenic regions<br/>Alessandro Brandulas Cammarata (UniL)"
description: 'Zurich Seminars in Bioinformatics'
date: 2024-06-20
authors:
  - "@mbaudis"
links:
  - '[Alessandro Brandulas Cammarata @ UniL](https://www.unil.ch/dee/en/home/menuguid/people/graduate-students/alessandro-brandulas-cammarata.html)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Bulk and single-cell RNA-Seq are powerful and widely used techniques that provide quantitative information on gene expression. While the primary focus of many applications is to estimate gene expression levels, a crucial first step in assessing gene activity is to distinguish technical or biological transcriptional noise from actively expressed genes. Typically, this is accomplished by setting an arbitrary abundance threshold (e.g., TPM>2) for calling a gene expressed. However, because of the substantial variation in technical and biological noise levels across RNA-Seq experiments the usage of such a fixed threshold can lead to either a loss of information if it is set too high or to an increase in false positives if set too low.  

To overcome these limitations, we propose an updated dynamic approach. <!--more-->First, we infer the amount of noise in a library by selecting reads mapped to intergenic regions. Using those intergenic regions, we can define a gene as expressed if its abundance is significantly higher than the distribution of this background “noise”. The accuracy of this approach outperforms other existing methods in determining the true state of genes, based on our evaluation compared to  epigenetic markers and ribo-seq data, in three distinct species.