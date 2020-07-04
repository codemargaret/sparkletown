---
layout: page
title: Products
---

{% for product in site.products %}
  <h2><a class="is-decorationless" href="{{ product.id }}">{{ product.name }}</a> | ${{ product.price }}</h2>
  <img src="{{ product.image }}" alt="{{ product.alt }}" width="550" height="600">
  <p>{{ product.description }}</p>
  <p>{{ product.content | markdownify }}</p>
  <button class="buy-button snipcart-add-item"
    data-item-id="{{ product.data_item_id }}"
    data-item-price="{{ product.price }}"
    data-item-url="/products"
    data-item-description="{{ product.description }}"
    data-item-image="{{ product.image }}"
    data-item-name="{{ product.name }}">
    Add to Cart
  </button>

{% endfor %}