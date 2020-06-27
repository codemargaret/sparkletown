---
layout: home
---

This will chronicle my journey into Bridgetown and Bulmatown, with a short stop for some shopping.

----
{: .my-6}

# Latest Articles
{: .mb-5 .title .has-text-centered}

{% assign posts = site.posts | slice: 0, 6 %}
{% render "bulmatown/collection", collection: posts, metadata: site.metadata %}

{% if site.posts.size > 6 %}
  <a href="/posts/" class="button is-primary is-outlined is-small"><span>Previous Articles</span> <span class="icon"><i class="fa fa-arrow-right"></i></span></a>
  {: .mt-6 .has-text-centered}
{% endif %}
