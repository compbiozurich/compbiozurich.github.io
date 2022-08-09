---
template: blog_post.html
title: 'What is Bioinformatics? Introduction and Resources'
date: 2021-09-21
authors:
  - "@mbaudis"
pdf_file_name: 
links:
  - '<a href="2021-09-21___Michael_Baudis__What_is_Bioinformatics__UZH-BIO390-day-01.pdf">[2021 lecture slides]</a> (PDF)'
---

#### Michael Baudis

The first day of the "Introduction to Bioinformatics" lecture series starts with a general introduction into the field and a description of the lecture topics, timeline and procedures.

<!--more-->

Topics covered in the lecture are e.g.:

* a term definition for _bioinformatics_
* the relation of hypothesis driven and data driven science, with respect to bioinformatics
* categories of bioinformatics tools and data
* research areas and topics
* the varying emphasis on "bio" and "informatics"
* databases (primary vs. derived) and data curation
* data collection & curation
* file Formats, ontologies & APIs ass areas/topics (w/o details)
* "not-bioinformatics"

At the end of the lecture, a - very - brief introduction into the relevance of different aspects of bioinformatics for human genome variation is being given.

### Q & A[^1]

##### What is meant with prose in bioinformatics?

Prose refers to written text, e.g. the body of scientific publications or descriptions
of experimental procedures, which may contain much information that can be converted
into categorical data, relationships and so forth. As example, a study may refer to
its topic as genomic analysis of "tumor samples from pre-menopausal women with
estrogen receptor positive stage II breast cancer". This information may not appear
in any structured data provided through deposition repositories and may have to
be associated with e.g. genomic profiling data through text mining & data curation.

##### What is the difference between local and connected databases?

Connected databases are open for networked queries or provide parts for complex data
schemas - e.g. annotation data in one resource can be linked with molecular data
in another using shared identifiers. Local ones are, well, local - e.g. storing
data for experimental runs or sensitive clinical data in a protected environment.

##### What does the slide with the arrayMap data Pipeline exactly show?

It Depicts a "typical" bioinformatic data curation process - scripting, review, integration.

##### For a binary file to get created is a program needed that will transform my data into such a file?

Binary files are software specific, so one needs original software (think[^2] - Microsoft Word) or compatible implementations - think Apple Pages - to create and interpret the data. Text based data formats - FASTA, HTML, XML, JSON, tabular text like .csv or .tsv - can be "read by humans".

##### A computer cannot open any file of any format, what kind of software does the computer need? an API?

See above. An API would be an internal part of the software, but has a broader
meaning (e.g. it can also serve to read or write text based data in/from a
structured format - e.g. put data from a JSON data stream into the right columns
into a table).

##### In the file formats BED and VCF genomic regions are stored. Does the whole sequence get stored as it is or is it somehow encoded?

Both formats are not used to store contiguous sequences but rather "features" related
to genomic coordinates (e.g. an allelic variant). Sequences are stored in FASTA, BAM, CRAM ...

##### is an API just a piece of code written in perl, python or R?

... or any other programming language, to allow digital - digital interactions between
different systems or parts of the same.

##### What exactly is the difference between systems biology and bioinformatics?

"Exactly" is tricky; generally it is "transformation, visualization and interpretation of data"
in bioinformatics versus more data modeling and prediction (where prediction also
needs data, but the with a stronger theoretical component; think prediction of
protein structure or the behaviour of ecosystems).


[^1]: Thanks to Katja W. in HS21 for starting some questions!

[^2]: One shouldn't write in MS Word, IMO. Use LaTex, Markdown, OpenOffice ...
