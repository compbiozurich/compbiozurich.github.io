---
title:  "Michael Baudis"
permalink: /people/Michael-Baudis.html
excerpt_link: 'http://info.baudisgroup.org/group/Michael_Baudis/'
excerpt_separator: <!--more-->
layout: default
date:   2007-08-01
image_file: 'Baudis.png'
category:
 - people
tags:
  - UZH
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}


## {{ page.title }}

- Professor of Bioinformatics
- Institute of Molecular Life Sciences
- University of Zurich & Swiss Institute of Bioinformatics **SIB**

<!--more-->
