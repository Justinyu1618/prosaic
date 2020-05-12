---
layout: default
title: Categories
permalink: /categories/
---
{% for category in site.categories %}
  - [{{category | first}}]({{page.url}}{{category | first}})
{% endfor %}
