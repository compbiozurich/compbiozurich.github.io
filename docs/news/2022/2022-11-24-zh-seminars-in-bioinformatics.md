---
template: blog_post.html
title: "Searching in nucleotide archives at Petabase scale with MetaGraph"
description: 'Zurich Seminars in Bioinformatics - Mikhail Karasikov'
date: 2022-11-24
authors:
  - "@mbaudis"
links:
  - "[Mikhail's homepage](https://karasikov.com)"
---

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

**Abstract** High-throughput sequencing data is continuously accumulating in massive archives such as the NCBI Sequence Read Archive (SRA), which currently contains over 50 Petabytes of sequences. However, despite recent advances, even such a basic operation as sequence search effectively remains intractable due to the lack of cost-efficient solutions. To address this problem and enable aggregated data analysis at Petabase scale, we developed MetaGraph, a tool for indexing very large collections of sequences in de Bruijn graphs.<!--more--> MetaGraph supports arbitrary alphabets, including amino acid sequences, and enables various queries, including large-scale search by sequence and alignment to the underlying annotated graphs or even to individual sequences encoded in it, as well as reference-free comparison of samples using the novel concept of differential assembly.

We have indexed an expansive set of sequence collections with MetaGraph, ranging from reference sequences, to whole genome and metagenomics sequencing data sets. Applying only moderate filtration of the input, our indexes require orders-of-magnitude less storage than the original gzip-compressed inputs: 4742× for GTEx, 77–2595× for SRA, 27× for MetaSUB, as well as 7.6×, 1.6×, and 1.1× for the UHGG, Tara Oceans MAGs, and RefSeq assembled sequences, respectively. Our recently developed approach RowDiff for lossless annotation sparsification has led to a 5.2× improvement in compression over our previous results. Moreover, we recently developed a framework of Counting de Bruijn graphs for losslessly indexing k-mer abundances and entire sequences, which represent all sequences from the RefSeq collection using 4.6× less storage than MegaBLAST and index all GTEx expression counts using 378× less space than the original gzip-compressed inputs.

In my talk, I will briefly describe the data structures employed in MetaGraph and highlight our indexing efforts to create a community resource. In particular, our SRA graphs open new opportunities to perform sequence search against this trove of data with sensitivity ranging from exact k-mer matching to per-base-pair alignment, leveraging the joint graph structure. Our exact k-mer matching searches at ~400kbp/s on a database of microbial samples, which is almost 4× faster than the current state-of-the-art, while our more sensitive per-base-pair alignment achieves ~7kbp/s. We have recently diversified the arsenal of search algorithms provided by the MetaGraph framework, developing alignment modes tailored towards searching against collections of reference genomes (TCG-Aligner) and low-coverage raw sequencing data (MetaGraph-MLA).
