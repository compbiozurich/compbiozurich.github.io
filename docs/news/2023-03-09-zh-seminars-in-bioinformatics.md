---
template: post.html
title: Detecting Single Cell Blasts in Acute Myeloid Leukaemia using an Auto-Encoder
description: 'Zurich Seminars in Bioinformatics - Alice Driessen'
date: 2023-03-09
authors:
  - "@mbaudis"
links:
  - '[www](https://researcher.watson.ibm.com/researcher/view.php?person=zurich-ADR)'
---

* 12:15 UZH Irchel **Y13-K-05** and ZOOM Call

**Abstract** Acute myeloid leukaemia (AML) is a haematological cancer in the bone marrow, with accumulation and expansion of immature cells of the myeloid lineage. Unfortunately, almost half of paediatric AML patients relapse after standard treatment with chemotherapy or stem cell transplantation. Personalised medicine including immunotherapies have the potential to target chemotherapy resistant cells and achieve long-term remission. However, identifying suitable targets for AML therapy is hampered by high patient heterogeneity, complex disease evolution and challenging discrimination between aberrant and developing cells. Therefore, we aimed to build a single-cell cytometry AML map to identify malignant cells and place them along the developmental trajectory using data from 20 patients and three time points over the course of the disease.<!--more-->

We trained an auto-encoder on healthy cells, to map different patients onto a common latent space, and used the reconstruction error to identify malignant cells. The latent space of the auto-encoder captures the developmental trajectory of the healthy bone marrow cells, which we used to identify the developmental stage of AML cells and samples. Our classification achieved an accuracy of 0.96 on an annotated subset on the single cell level. We showed that our developmental stage assignment is consistent with the World Health Organisation classification of the samples. Additionally, we analysed the phenotypes of the predicted malignant cells to identify relevant markers for immunotherapy.
