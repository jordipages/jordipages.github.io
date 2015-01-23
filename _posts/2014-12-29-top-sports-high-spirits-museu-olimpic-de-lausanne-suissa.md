---
layout: post
og: true
og-type: article
title: "Top Sports High Spirits Museu Olímpic de Lausanne (Suïssa)" 
share: true
class: artwork
categories:
  - portfoli
work: 3
---

{% assign work_data = site.data.portfoli | where:"id", page.work %}
{% assign work = work_data | first %}
<figure>
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_4-3">
			<core-image sizing="cover" class="core-image-size" preload fade src="/images/{{ work.featured-img }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p>{% if work.external-url %}<a href="{{ work.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ work.name }}</strong></small></a>{% else if %}<small><strong>{{ work.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->

Projecte encarregat per The World Games Association, al Museu Olímpic de Lausanne per a promocionar Els World Games del 2009 a la ciutat de Kaohsiung (Taipei).

Amb l’eslògan “Top Sports High Spirits” com a tema principal, es va dissenyar una exposició eminentment visual aprofitant l’impacte dels diferents esports que participen en aquesta competició que es realitza cada quatre anys a una seu diferent d’arreu del món.