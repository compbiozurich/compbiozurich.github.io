---
title: "Petros Koumoutsakos"
layout: default
date: 2000-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.cse-lab.ethz.ch/member/petros-koumoutsakos/'
www_link:
www_links_formatted:
image_file: 'Koumoutsakos.jpg'
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

* Chair for Computational Science
* ETHZ

<!--more-->
