---
title: "Mark Robinson"
layout: default
date: 2011-09-01
excerpt_separator: <!--more-->
excerpt_link: 'https://robinsonlabuzh.github.io'
www_link:
www_links_formatted:
image_file: 'Robinson.png'
category:
  - people
tags: # please delete unneeded options
  - UZH
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Associate Professor of Statistical Genomics
* Institute of Molecular Life Sciences
* University of Zurich

<!--more-->





