---
template: post.html
title: "PIBLO: A Comprehensive Approach to Pixel-Level Spatial Analytics for Multiplexed Imaging<br/>Tony Xu (PhD student, Australian National University)"
description: 'Zurich Seminars in Bioinformatics'
date: 2025-10-02
authors:
  - "@mbaudis"
links:
#  - '[]()'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** The volume and complexity of multiplexed tissue images are growing rapidly with newer acquisition platforms, while statistical methods for extracting biologically meaningful spatial information have not kept pace. This creates an opportunity to move beyond current techniques by delivering more comprehensive spatial analytics that capture complex spatial structure, incorporate non-cellular and sub-cellular features, and operate at larger scale and higher speed.

We present PIBLO, a comprehensive image-analysis package, engineered end-to-end for distributed GPU operations for enhanced performance and throughput. <!--more-->PIBLO eschews image segmentation, instead deploys a batch-SOM implementation for pixel clustering, alongside a novel SOM training method designed to further reduce quantization error while maintaining topological fidelity. Per-image SOMs are then harmonised, preserving consistent cluster semantics and enabling parallel per-image SOM training across datasets. 

To conduct spatial analytics, PIBLO transforms each image’s cluster outputs into probability-distribution representations. This allows for efficient compute of association, exclusion, and many other spatial metrics. PIBLO supports not only analysis of pixel clusters, but also regional tissue types, and direct image features, and any mixture thereof. Finally, PIBLO deploys a graph-based network analysis to identify salient structures and key features. The resulting per-image spatial feature vectors and interaction graphs integrate with traditional statistical tools, enabling cohort-level imaging analysis.

