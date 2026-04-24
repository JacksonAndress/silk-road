---
title: Objects
layout: base
header-title: Objects
---

# Venetian-made objects using Silk Roads techniques

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'objects/'" %}

{% include nav/card-grid.html cards=cards %}
