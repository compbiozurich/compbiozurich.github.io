---
title: "Christian von Mering"
layout: default
date: 2006-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.imls.uzh.ch/en/research/vonmering/people/christian-von-mering.html'
www_link: # a simple web address related to the post, e.g. https://www.ga4gh.org
www_links_formatted:  # one or multiple complete links
#  - '<a href="https://www.biorxiv.org" target="_blank">[biorXiv]</a>'
image_file: 'Mering.png'
category:
  - people
tags: # please delete unneeded options
  - UZH
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 100px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor of Bioinformatics
* Institute of Molecular Life Sciences 
* University of Zurich

<!--more-->





