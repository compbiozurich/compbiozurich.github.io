---
template: blog_post.html
title: Investigation of the potential of Covariates for Multiphenotype Studies (CMS) to improve genetic risk prediction
description: 'Zurich Seminars in Bioinformatics - Anja Estermann'
date: 2023-09-28
authors:
  - "@mbaudis"
links:
  - '[Robinson lab @ UZH](https://robinsonlabuzh.github.io)'
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** Polygenic risk scores (PRSs) estimate the genetic risk of an individual to develop a certain disease or trait and find application in disease prevention and personalized medicine. These scores are calculated based on summary statistics results of genome-wide association studies (GWAS). Covariates for multiphenotype studies (CMS) is an algorithm that has been developed to increase the detection of associated genetic variants in GWAS by leveraging covariates measured on behalf of a primary outcome.<!--more-->


In the scope of my master thesis, we investigated whether the output of CMS can also be used to improve risk prediction. The analysis of simulated and real data (UK Biobank) revealed that CMS can produce modest improvements in risk prediction in a majority of scenarios. The results on the UK Biobank varied between 7 % decrease and 36 % increase in predictive power of CMS compared to the linear model. Different parameters influencing the effectiveness of CMS were investigated. Results varied strongly across different setups and outcomes. Largest improvements are expected if the covariates explain large proportions of the variance of the outcome. However, the variance explained by the covariates was much lower (9 %) than the theoretical maximum (61-100 %). This reduces the potential gain in predictive power of CMS significantly. To further investigate CMS for risk prediction, other data sets or phenotypes with larger variance explained should be analyzed.