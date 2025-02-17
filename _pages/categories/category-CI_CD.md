---
title: "CD/CD"
layout: archive
permalink: /categories/CD%/CD
author_profile: true
sidebar:
    nav: "docs"
---

{% assign posts =site.categories["CI/CD"] %}
{% for post in posts %} 
    {% include archive-single.html type=page.entries_layout %} 
{% endfor %}