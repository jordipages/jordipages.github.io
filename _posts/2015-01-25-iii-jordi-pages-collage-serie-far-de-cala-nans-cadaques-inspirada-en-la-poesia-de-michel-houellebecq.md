---
layout: post
og: true
og-type: product
title: "3. JORDI PAGÈS Collage(s) sèrie Far de Cala Nans Cadaqués inspirada en la poesia de Michel Houellebecq" 
share: true
class: artwork
categories:
  - farcalanans
published: true
work: 3
---

{% assign work_data = site.data.obres.farcalanansobrajordipages | where:"id", page.work %}
{% assign work = work_data | first %}
<figure>
  <div class="padding-artwork-container">
    <div class="embed-container embed-container_{{ work.aspect_ratio }}">
      <core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image> 
    </div>
  </div>
  <figcaption>
    <p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensions: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
  </figcaption>
</figure>
<!--more-->
{{ work.description }}