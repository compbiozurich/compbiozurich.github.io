---
template: post.html
title: "Benchmarking Cell Segmentation Approaches for High-Resolution Spatial Transcriptomic<br/>Raphael De Gottardi (CBB M.Sc. Student, FGCZ)"
description: 'Zurich Seminars in Bioinformatics'
date: 2025-08-28
authors:
  - "@mbaudis"
links:
#  - '[]()'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** High-resolution Spatial Transcriptomics technologies have transformed our ability to study gene expression within tissues while preserving spatial context. With the release of Visium HD by 10X Genomics, transcript counts can now be captured in 2 µm × 2 µm squares, opening the possibility of single-cell-like analysis. Translating these squares into meaningful cell-level data requires accurate cell segmentation. This process, known as bin-to-cell mapping, is the focus of this thesis.

I systematically benchmarked bin-to-cell methods against the standard 8 µm × 8 µm binning approach.<!--more--> The study compared two published methods (Bin2Cell and ENACT, both based on nucleus segmentation and circular expansion) as well as a custom strategy that integrates detailed Xenium-based cell segmentation. To support this evaluation, I developed a benchmarking pipeline covering quality control, segmentation metrics, cell type annotation, and coexpression-based metrics.

The results show that bin-to-cell methods outperform naive binning, but their performance varies depending on tissue type, parameter choices, and downstream analysis methods. Method selection must consider computational constraints, tissue characteristics, and research objective. By setting evaluation standards and highlighting trade-offs, it aims to guide researchers toward informed use of Spatial Transcriptomics and enable evaluation of future bin-to-cell strategies.