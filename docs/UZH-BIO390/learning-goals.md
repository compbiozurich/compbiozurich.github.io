---
title: "UZH BIO390 - Learning Goals"
date: 2022-08-10
authors:
  - "@mbaudis"
---

This page indicates some of the learning goals, as emphasised by the different lecturers. Some points will have been discussed in different lectures; accordingly, exam questions may not refer to information of one specific presentation.

!!! warning "Learning goals have a general scope"

    Please be aware that some of the "Learning Goals" may reflect aspects not necessarily
    captured by the lectures in the current semester - The ones reelevant for the
    current semester's exam are related to the given lectures. Also, updates may
    occurr at any time.

!!! note "Consider individual pages"

    Please consider individual course pages and documents linked from there. Those
    might be updated later on, so it is a good idea to check back before the end
    of the course.

## Bioinformatics: Definition & Concepts

* definition of "Bioinformatics" (cf. Anna Tramontano)
* categories of informatics tools used in bioinformatics
* hypothesis versus data driven science
* areas of bioinformatics/bioinformaticians, (in contrast to "pure" modelling, statistics etc.)
* 3 main categories of biological data, and example resources
* definition of API
* common sequence related file formats
* hierarchies and relationships as 2 main principles of ontologies
* areas of "not-bioinformatics", and why
* bioinformatics tools (programming languages, libraries, online resources) and their specific use cases


## Sequence Analysis

* basics of DNA and Protein sequences
* substitution matrices
* BLAST
    - parameters
    - terms
    - scores


## Statistical Bioinformatics & Machine Learning

* usage of gene expression profiling
* multiple testing correction
* parameters for hierarchical clustering
* statistical evidence for a change in the mean
* dimensionality reduction
* central limit theorem
* hierarchical clustering
* clustering coefficient
* unsupervised machine learning tasks/components
* ML model types


## Bioinformatics tools & resources

* common programming/analysis languages/environments in bioinformatics and their preferred use
    - e.g. R, Perl, Python, JavaScript ... but also environments & packages like
      Mkdocs, ReadTheDocs, Bioconductor ...
* components of bioinformatics online resources
    - Databases, middleware, APIs, frontends ...

### Some Q & A (thanks to the providers of these questions)

* _Progenetix use case_: In comparative genomic hybridization, in the case of an high
copy number segment of DNA, more tumor DNA will hybridize to the metaphase chromosomes
just because of higher likelihood?
    - in essence, yes; it is a mix of higherlikelihood and therefore higher binding
      probability (it is actually hard for a given fragment to encounter the right
      place on the chromosome or array) w/ or w/o competition effects (latter when using normal
      reference DNA)
* _CURIEs_: ...hierarchical coding systems where individual codes are represented as
  CURIEs - aren't they a type of URI rather then a "code"?
    - CURIEs are universal identifiers (URIs) consisting of a public and a local
      part
    - they are universal (like UUIDs) but unlike UUIDs (which can be anonymous)
      they are resolvable (_i.e._ the public part can be resolved to a URL where
      then the local part can be used to retrieve the resource)
    - the "hierarchical coding systems" usually _don't_ use the CURIE _internally_
      but only the private part; but using the complete CURIE _externally_
      makes it unambiguous
* _Progenetix use case_: In Progenetix one can *either* use the GA4GH-Beacon API to
  query (i.e., do information retrieval) *OR* use the _pgxRpi_ API to load the data
  into an analysis environment (i.e., for eventual knowledge extraction)?
    - Not really. The _bycon_ software stack implements database access / middleware /
      Beacon API instance. This (outward facing) API (compatible to the Beacon specification)
      can be accessed by various clients for data retrieval (e.g. the `beaconplus-web`
      or `progenetix-web` JavaScript front ends, manual http requests, Beacon aggregator
      services...).
    - The `pgxRpi` itself is an API for the R environment, _i.e._ another client
      accessing the Beacon API. So here one gets
      `(DATA - Progenetix' Beacon API - pgxRpi API - R analysis environment`.


## Regulatory Genomics and Epigenomics

* secondary/tertiary human genome structure
* functional genome content
* transcription factors & genome interaction
* chemical genome modifications, their effectors and results
* Chip-Seq
* read mapping
* peak calling
* sequence compression algorithms


## Metagenomics

* concept of taxonomic diversity
* concept microbial community dissimilarity
* how are sequences used to derive an adopted species concept for prokaryotes
* principle steps for 16S rRNA-based taxonomic composition analysis
* essential steps of short sequencing read assembly into contigs and scaffolds
* basic steps of metagenomic analysis: from raw reads to the reconstruction of
  genomic scaffolds


## Proteomics

* principles of proteome organization in the cell
* key experimental and computational concepts for the collection and analysis of
  high confidence protein-protein interaction data
* peptide fragmentation
* target-decoy approach
* protein quantification
* MassSpec similarity queries


## Biological Networks

* Protein interaction and metabolic networks
* databases and online resources for different types of pathway and interaction
  data
* detection of protein complexes
* graphs, nodes, edges, paths
* geodesics, graph diameter
* common types of degree distributions
* adjacency matrix
* shortest path matrix
* assortative and disassortative graphs
* community (module) detection
* cliques
* motifs, graph representations of metabolic networks


## Text Mining

* text mining pipelines & (current) common programs/applications
* article/literature repositories (with focus on accessibility)
* processing steps in text mining
    - stemming etc.
* common problems in text mining
* search engine precision metrics
* benchmarking


## Semantic web, RDF, Ontologies

* semantic web
    - elements
    - benefits
* components of ontologies
* stack of standards in semantic web and their functions
* RDF for modeling data
* OWL/OBO for modeling a biomedical domain
* querying knowledge graphs for answering biomedical questions


## Clinical Bioinformatics & Personalized Medicine

* genomic variants (types, numbers)
* reference genome(s)
* main bottlenecks of molecular diagnostics in the clinical setting
* goals of many personalized health initiatives
* currently favoured _clinical_ NGS technology
* clinical trial participation


## Genomic data & privacy

* reasons for needing _many_ genomes
* genomic privacy and re-identification (concepts)
* principle of re-identification attacks over the Beacon protocol
* long range familial searches
* opinions about risk vs. opportunities
* direct-to-consumer genetic testing -> what, how
* technical and regulatory solutions against privacy breaches & data abuse
* genotype-phenotype (G2P) (ab-)use

