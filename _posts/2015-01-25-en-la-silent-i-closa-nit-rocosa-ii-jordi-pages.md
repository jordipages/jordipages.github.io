---
layout: post
og: true
og-type: product
title: "En la silent i closa nit rocosa II. Jordi Pagès" 
share: true
class: artwork
categories:
  - vinyoli
published: true
work: 3966
---

{% assign work_data = site.data.obres.vinyoliobrajordipages | where:"id", page.work %}
{% assign work = work_data | first %}
<figure>
  <div class="padding-artwork-container">
    <div class="embed-container embed-container_{{ work.aspect_ratio }}">
      <core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image> 
    </div>
  </div>
  <figcaption>
    <p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensions: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
    <p><a href="{{ work.permalink }}" class="btn btn-default btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
  </figcaption>
</figure>
<!--more-->
{{ work.description }}