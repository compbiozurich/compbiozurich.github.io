---
template: blog_post.html
title: Variational Autoencoders Supporting Conditioning in Single Cell Transcriptomics and Their Consistency
description: 'Zurich Seminars in Bioinformatics - Eljas Röllin'
date: 2023-04-13
authors:
  - "@mbaudis"
links:
  - '[www](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Prediction of cell response to perturbation is a key goal in computational biology. To this end, different Variational Autencoder (VAE) based models have been suggested in the past. We are interested in such models and their ability to recognize their own output. We argue that this is a desirable model property, and phrase it in the context of cycle consistency.<!--more--> We suggest metrics to capture a model's cycle consistency, and evaluate the cycle consistency of different VAE based models for single-cell RNA sequencing data. A cycle consistency regularization term is suggested. The proposed cycle consistency regularization term is generally applicable to VAE based models, also when other regularization penalties are used simultaneously. In contrast to many other penalties, however, this cycle consistency regularization term provides its regularization effect not via an additional enforcement on the latent space or similar, but rather by naturally incentivizing the model to recognize its generated output during training. We find that this regularization term does improve cycle consistency for the different VAE based models considered here.  We consider how this affects the models, and show that its impact differs between different VAE based models.


