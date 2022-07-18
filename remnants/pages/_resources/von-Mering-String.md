---
title: "STRING - Gene Interactions"
layout: default
date: 2006-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://string-db.org'
www_link:
links:
image_file: 'logo_string_small.png'
category:
  - resources
tags: # please delete unneeded options
  - databases
  - tools
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 160px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## STRING - Search Tool for the Retrieval of Interacting Genes

STRING aims to collect and present all known and predicted protein-protein interactions, covering several hundred organisms. The interactions include direct (physical) and indirect (functional) associations.

<!--more-->

