---
title: "Progenetix - Cancer Genome Data Resource"
layout: default
date: 2001-01-01
excerpt_separator: <!--more-->
excerpt_link: 'https://progenetix.org'
www_link:
www_links_formatted:
image_file: 'progenetix_160.png'
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

## {{page.title}}

The Progenetix database is the largest repository for annotated copy number profiling data in cancer. The website also tracks & analyses cancer genome profiling publications for provenance & content.

```
Domain Name: progenetix.net
Creation Date: 2000-11-29T18:17:38.000Z
```

<!--more-->

