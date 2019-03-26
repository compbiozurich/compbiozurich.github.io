---
title: "Robinson Lab - Software & Resources"
layout: default
date: 2012-01-01
excerpt_separator: <!--more-->
excerpt_link: 'https://robinsonlabuzh.github.io/tools.html'
www_link:
www_links_formatted:
image_file: 'robinsonlab-resources.png'
category:
  - resources
tags: # please delete unneeded options
  - databases
  - tools
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 200px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## Robinson Lab at UZH and SIB - Software & Resources inStatistical Bioinformatics

The group of Mark Robinson at the UZH develops software tools and resources for biological data analysis, visualisation and benchmarking, e.g. related to RNAseq, CyTOF, CRISPR design and differential splicing.

<!--more-->

