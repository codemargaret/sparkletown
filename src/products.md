---
layout: page
title: Products
exclude_from_search: true
pagination:
  enabled: true
---

{% assign products = paginator.documents %}
{% render "bulmatown/collection", collection: products, metadata: site.metadata %}

{% render "bulmatown/pagination", paginator: paginator %}