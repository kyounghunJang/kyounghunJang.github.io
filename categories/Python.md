---
layout: category
title: Python
---
{% assign posts = site.category.#Python %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout%} {% endfor %}