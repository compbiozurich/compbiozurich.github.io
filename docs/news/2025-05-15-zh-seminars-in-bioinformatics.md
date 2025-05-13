---
template: post.html
title: "Advancing Quantitative Proteomics with Language Model Integration<br/>John Oehninger (von Mering group)"
description: 'Zurich Seminars in Bioinformatics'
date: 2025-05-15
authors:
  - "@mbaudis"
links:
  - '[von Mering Lab @ UZH](https://www.mls.uzh.ch/en/research/von-mering.html)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Advancing large-scale proteomic resources like PaxDb relies on the careful curation and integration of suitable quantitative datasets from the literature. This thesis investigates how various language modeling strategies can assist in automating this process by classifying publication abstracts for their relevance to PaxDb. Starting from a curated set of labeled examples, I developed and evaluated a diverse range of classification strategies, from classical vector space models established decades ago to deep neural architectures that now dominate the field of natural language processing.<!--more-->

A central challenge addressed in this work is the small size and inherent class imbalance of the labeled dataset. To mitigate overfitting and improve generalization, I introduced a novel similarity-aware data-splitting strategy that leverages embedding-derived cosine similarity to guide stratified train/test partitioning. This allowed me to better control data leakage and assess model robustness under realistic conditions.

My evaluation spans classical machine learning classifiers on low-dimensional embeddings, attention-based neural networks for full token representations, fine-tuned pre-trained transformer encoders, and custom transformer encoder architectures trained from scratch. Models were optimized for both precision-oriented and balanced objectives, revealing that precision can be maximized through careful model selection and targeted tuning.
This thesis provides a comprehensive comparative analysis across embedding families and classification strategies, offers a reproducible optimization and evaluation framework, and lays the groundwork for integrating transformer-based models into PaxDb’s curation pipeline. The tools and insights developed here aim to support scalable, high-quality expansion of proteomic resources.