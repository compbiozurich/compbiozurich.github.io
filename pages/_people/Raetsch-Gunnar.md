---
title: "Gunnar R&auml;tsch"
layout: default
date: 2016-05-01
excerpt_separator: <!--more-->
excerpt_link: 'https://bmi.inf.ethz.ch/people/person/gunnar-raetsch/'
www_link: # a simple web address related to the post, e.g. https://www.ga4gh.org
www_links_formatted:  # one or multiple complete links
#  - '<a href="https://www.biorxiv.org" target="_blank">[biorXiv]</a>'
image_file: 'Raetsch.png'
category:
  - people
tags: # please delete unneeded options
  - ETHZ
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 80px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor of Biomedical Informatics 
* ETH Zurich 
* Department of Computer Science 

<!--more-->





