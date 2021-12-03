---
title: 'ZH Sem Bioinfo - Mirjam Zünd'
layout: default
author: '@mbaudis'
excerpt_separator: <!--more-->
www_link: https://micro.biol.ethz.ch/people/person-detail.html?persid=232713
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

### TBD

* Thursday, {{page.date | date: "%Y-%m-%d" }}
* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** An estimated 40 - 50% of mammalian gut bacteria carry a prophage in their genome. Prophages can be induced upon stress and produce phage particles to infect and kill bacterial populations and thereby directly modulate the composition of the gut microbiota. Despite advances in studying prophages using whole-genome sequencing, challenges in identifying and locating inducible prophages within their host have limited our understanding of phage-bacterial interactions. 

<!--more-->

We established and experimentally validated methods based on DNA sequencing data to locate inducible prophages in bacterial genomes. This method, implemented as a bioinformatic tool named mVIRs, identifies prophages by analysing the orientation and apparent insert size of paired-end reads aligned to a reference genome and locates the exact genomic coordinates by partially aligned reads. The output of mVIRs builds the foundation to quantify phage-to-host ratios as relative prophage activity levels. Applying mVIRs in four murine model strains, we detected and located six inducible prophages. We also show that mVIRs is applicable to gut microbial community samples, using either publicly available or de novo assembled genomes as reference for the alignment of sequencing reads. Comparing experimentally validated prophage locations to the results from several computational detection tools revealed that phage predictions were both variable and inconsistent across such tools, with only one out of 46 predictions agreeing with the experimentally validated coordinates. The ability to identify prophages de novo and to generate quantitative information of their activity will provide a more comprehensive picture of how phage-bacteria interactions affect our gut microbiota and health. 

mVIRs is freely available at [github.com/SushiLab/mVIRs](https://github.com/SushiLab/mVIRs).
