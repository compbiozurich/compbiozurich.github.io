---
title: 'ZH Seminars Bioinformatics - Reto Gerber'
layout: default
author: '@mbaudis'
excerpt_separator: <!--more-->
www_link:
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
### Censored predictors in single cell regression models

* Thursday, {{page.date | date: "%Y-%m-%d" }}
* 12:15 (Skype Call)

<!--more-->

__Abstract__ Flow and mass cytometry enable the classification of a large number of cells into cell populations. Furthermore, the abundance of cell populations can have an association with a covariate that has additional information about the sample, such as treatment group, age, sex, survival time, etc. In differential abundance analysis, the goal is then to find cell populations whose abundance changes according to a covariate. One approach is to fit linear models to find those relationships. A problem occurs if a covariate is not always completely observed, but instead for some samples only a minimum value is known. This type of missing data mechanism is known as censoring and occurs frequently in the analysis of survival times.

The simplest way to deal with censored covariates is to discard all samples containing incomplete data. But for small sample sizes or high censoring rates, this method becomes highly inefficient and might even introduce a bias. Better is therefore to directly take into account the censored nature of a covariate, which can be achieved with a similar setup as when a covariate is missing: multiple imputation. The main difference to classical multiple imputation is the imputation step which uses a censoring specific method.

A comprehensive simulation study was performed by testing six different methods under various conditions. One method in particular, called Kaplan-Meier imputation, showed a good performance in terms of detection rates and error control. It detects much more reliably differentially abundant cell populations for small samples sizes with high censoring rates than the case where incomplete samples are discarded.
