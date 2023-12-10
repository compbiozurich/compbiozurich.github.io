---
title: "UZH BIO390 - Learning Goals"
date: 2022-08-10
authors:
  - "@mbaudis"
---

This page indicates some of the learning goals, as emphasised by the different lecturers. Some points will have been discussed in different lectures; accordingly, exam questions may not refer to information of one specific presentation.

__Cave__: Please be aware that some of the "Learning Goals" may reflect aspects not necessarily captured by the lectures in the current semester - The ones reelevant for the current semester's exam are related to the given lectures. Also, updates may occurr at any time.

#### Bioinformatics: Definition & Concepts

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

#### Bioinformatics tools & resources

* common programming/analysis languages in bioinformatics and their preferred use
* components of bioinformatics online resources

##### Some Q & A (thanks to the providers of these questions)

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


#### Sequence Analysis

* substitution matrices
* BLAST

#### Statistical Bioinformatics

* usage of gene expression profiling
* multiple testing correction
* parameters for hierarchical clustering
* statistical evidence for a change in the mean
* dimensionality reduction
* central limit theorem
* hierarchical clustering
* clustering coefficient

<!--
#### Bioinformatics tools: Statistics & Graphics in R & BioConductor

* What is tidy data?
* ideas behind ggplot:  components of a ggplot, arrangement of input data ... (no actual code writing needed)
*  interpret common types of plots, e.g. barplot, boxplot, histogram
* effect of data transformation (e.g. log) on common types of plots
-->

#### Regulatory Genomics and Epigenomics

* secondary/tertiary human genome structure
* functional genome content
* transcription factors & genome interaction
* chemical genome modifications, their effectors and results
* Chip-Seq
* read mapping
* peak calling
* sequence compression algorithms

#### Metagenomics

* concept of taxonomic diversity
* concept microbial community dissimilarity
* how are sequences used to derive an adopted species concept for prokaryotes
* principle steps for 16S rRNA-based taxonomic composition analysis
* essential steps of short sequencing read assembly into contigs and scaffolds
* basic steps of metagenomic analysis: from raw reads to the reconstruction of genomic scaffolds

#### Proteomics

* principles of proteome organization in the cell
* key experimental and computational concepts  for the collection and analysis of high confidence protein-protein interaction data
* peptide fragmentation
* target-decoy approach
* protein quantification

#### Clinical Bioinformatics & Personalized Medicine

* genomic variants (types, numbers)
* genomic privacy and re-identification (concepts)
* reference genome(s)
* main bottlenecks of molecular diagnostics in the clinical setting
* goals of many personalized health initiatives
* direct-to-consumer genetic testing -> what, how
* currently favoured _clinical_ NGS technology
* clinical trial participation
* genotype-phenotype (G2P) (ab-)use

#### Text Mining

* text mining pipelines & (current) common programs/applications
* article/literature repositories (with focus on accessibility)
* processing steps in text mining
* common problems in text mining
* search engine precision metrics
* benchmarking

#### Semantic web, RDF, Ontologies

* semantic web and its benefits
* stack of standards in semantic web and their functions
* RDF for modeling data
* OWL/OBO for modeling a biomedical domain
* querying knowledge graphs for answering biomedical questions

#### Biological Networks

* Protein interaction and metabolic networks
* the two-hybrid assay and its limitations
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




#### Genomic data & provacy

* reasons for needing _many_ genomes
* principle of re-identification attacks over the Beacon protocol
* long range familial searches
* opinions about risk vs. opportunities
* technical and regulatory solutions against privacy breaches & data abuse


<!--
* Girvan-Newman algorithm
* small world graphs
* degree correlations
* modularity Q
* stoichiometry matrices
* null space
* flux balance analysis
-->
