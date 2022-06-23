---
layout: category
title: AWS
---
{% assign posts = site.category.#AWS %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout%} {% endfor %}