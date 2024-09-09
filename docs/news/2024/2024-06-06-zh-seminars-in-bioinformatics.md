---
template: post.html
title: "Benchmarking current spatial transcriptomics domain identification methods<br/>Jieran Sun"
description: 'Zurich Seminars in Bioinformatics'
date: 2024-06-06
authors:
  - "@mbaudis"
links:
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 ZOOM Call only!

**Abstract** Spatial transcriptomics (ST) preserves transcriptomic information within a spatial context, enabling an unprecedented understanding of tissue architecture and cellular heterogeneity. Since 2020, over 50 methods have been developed to identify spatial domains in ST datasets. Existing benchmarking efforts are limited by imbalances in dataset and technology inclusion, hindering a comprehensive overview of current methods. This study is a pilot demonstration of SpaceHack, a collaborative and community-driven benchmarking framework initiated by more than 40 researchers from across the world. <!--more-->

With a selected scope, this project uses SpaceHack implementation to evaluate 14 different methods across six commonly used ST datasets. Method performance is assessed in terms of accuracy, spatial continuity, scalability, and usability. and we also identify variability in method performance at different levels. Employing common metrics from benchmarking studies, we underscore the challenges in method usability, particularly in constructing precise software environments. Additionally, we question the notion of ground truth annotations, which may suffer from technical errors and subjective biases. In some instances, ground truth represents only one of several anatomically viable domain classification, potentially penalizing methods that adopt alternative, yet equally valid, classification.