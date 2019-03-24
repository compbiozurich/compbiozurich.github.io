---
title: "Constance Ciaudo"
layout: default
date: 2013-04-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.mhs.biol.ethz.ch/research/ciaudo.html'
www_link:
www_links_formatted:
image_file: 'Ciaudo.png'
category:
  - people
tags: # please delete unneeded options
  - ETHZ
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Institute for Molecular Health Sciences
* ETHZ

<!--more-->
