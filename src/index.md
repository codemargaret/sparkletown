---
layout: home
---

My journey into Bridgetown and Bulmatown, with a short stop for some shopping.

----
{: .my-6}

# Products
{: .mb-5 .title .has-text-centered}

### 100% Real Diamond

This genuine diamond is a steal at $9.95! But definitely not stolen haha!

<img src="/images/diamond.jpg" alt="diamond" width="550" height="600">

<button class="buy-button snipcart-add-item"
  data-item-id="1"
  data-item-price="9.95"
  data-item-url="/"
  data-item-description="This genuine diamond is a steal at $9.95!"
  data-item-image="/images/diamond.jpg"
  data-item-name="100% Real Diamond">
  Find happiness through commerce
</button>

# Latest Articles
{: .mb-5 .title .has-text-centered}

{% assign posts = site.posts | slice: 0, 6 %}
{% render "bulmatown/collection", collection: posts, metadata: site.metadata %}

{% if site.posts.size > 6 %}
  <a href="/posts/" class="button is-primary is-outlined is-small"><span>Previous Articles</span> <span class="icon"><i class="fa fa-arrow-right"></i></span></a>
  {: .mt-6 .has-text-centered}
{% endif %}
