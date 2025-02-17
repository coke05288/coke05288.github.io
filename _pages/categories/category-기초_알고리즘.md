---
title: "기초 알고리즘"
layout: archive
permalink: /categories/기초%20알고리즘
author_profile: true
sidebar:
    nav: "docs"
---

{% assign posts =site.categories["기초 알고리즘"] %}
{% for post in posts %} 
    {% include archive-single.html type=page.entries_layout %} 
{% endfor %}