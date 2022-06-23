---
layout: category
title: Python
---
{% assign posts = site.category.Python %}
{% for post in posts %} {% include archive-single2.html type=site.entries_layout%} {% endfor %}