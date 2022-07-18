---
template: blog_post.html
title: 'From Biomolecular Networks to Pathways: Tools for the Interpretation of Genome-Wide Experiments'
description: 'Zurich Seminars in Bioinformatics - Annika Gable'
date: 2021-01-21
authors:
  - '@mbaudis'
---


* 12:15 om  ZOOM Call


Functional enrichment analysis (also called gene set enrichment analysis or pathway analysis) is a widely-used method to interpret genome-wide experiments, especially in transcriptomics and proteomics. The method relies on previously annotated gene sets, such as pathways, cellular locations, protein families, disease genes, or other annotation terms.<!--more-->
 These terms are typically obtained via manual curation of the scientific literature, and are stored in structured databases such as the Gene Ontology. Although this provides pathways and functional terms of high quality, manual curation is a time-consuming process that cannot keep pace with the amount of research output produced. Furthermore, curation is influenced by study biases. Thus, some genes and pathways are heavily annotated, while others are lacking any annotations.

In this talk, I will present two annotation systems which are automatically derived from data already aggregated in the STRING protein–protein association network and database. I compare these two annotation systems to nine other, mostly curated, functional gene annotation systems, with a focus on their performance in enrichment analysis. The benchmark dataset is a diverse collection of nearly 2000 unique, genome-scale datasets provided by STRING users.

I will show how our two novel annotation systems complement the existing, manually curated pathway databases, and how they discover potentially underexplored pathways in well-studied genomes, as well as providing a more complete coverage of understudied species.
