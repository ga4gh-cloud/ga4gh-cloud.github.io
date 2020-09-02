---
title: "David Glazer"
layout: default
excerpt_separator: <!--more-->
image_file: dglazer.png
category:
  - contact
  - people
tags:
  - contacts
  - leads
  - contributors
  - Cloud
  - .featured
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; width: 80px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

Co-chair GA4GH Cloud  
Co-lead, Data Repository Service  
Engineering Director, Verily Life Sciences  

<!--more-->

email [dglazer@google.com](mailto:dglazer@google.com)
