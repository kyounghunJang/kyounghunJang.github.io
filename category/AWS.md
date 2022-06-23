---
layout: category
title: AWS
---
{% assign posts = site.category.AWS %}
{% for post in posts %} {% include archive-single2.html type=site.entries_layout%} {% endfor %}