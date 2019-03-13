---
title: "Andreas Wagner"
layout: default
date: 2006-01-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.ieu.uzh.ch/wagner/people.html'
www_link: # a simple web address related to the post, e.g. https://www.ga4gh.org
www_links_formatted:  # one or multiple complete links
#  - '<a href="https://www.biorxiv.org" target="_blank">[biorXiv]</a>'
image_file: 'Wagner.png'
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

* Professor and Chairman, Dept. of Evolutionary Biologyand Environmental Studies
* University of Zurich

<!--more-->





