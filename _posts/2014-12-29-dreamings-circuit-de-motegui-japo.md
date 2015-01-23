---
layout: post
og: true
og-type: article
title: "DREAMINGS Circuit de Motegui (Japó)" 
share: true
class: artwork
categories:
  - portfoli
work: 4
---

{% assign work_data = site.data.portfoli | where:"id", page.work %}
{% assign work = work_data | first %}
<figure>
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_16-9">
			<core-image sizing="cover" class="core-image-size" preload fade src="/images/{{ work.featured-img }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p>{% if work.external-url %}<a href="{{ work.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ work.name }}</strong></small></a>{% else if %}<small><strong>{{ work.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->

Projecte encarregat per Haute-Voltige per a complementar en les pantalles gegants del circuit de Motegui (Japó) l'espectacle aeri “Dreamings”. L'encàrrec consistia en il·lustrar una serie d'escenes basades en l'argument del músical, que es podia seguir simultàniament, tan a l'aire on un equip d'avions acrobàtics desenvolupava l'acció com a les pantalles gegants del circuit.