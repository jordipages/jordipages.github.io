---
layout: post
og: true
og-type: article
title: "Mostra d’Art digital" 
share: true
class: artwork
categories:
  - portfoli
work: 1
---

{% assign work_data = site.data.portfoli | where:"id", page.work %}
{% assign work = work_data | first %}
<figure>
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_9-16">
			<core-image sizing="cover" class="core-image-size" preload fade src="/images/{{ work.featured-img }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p>{% if work.external-url %}<a href="{{ work.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ work.name }}</strong></small></a>{% else if %}<small><strong>{{ work.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->

La Iª Mostra simultània d’art digital de Barcelona es presenta com una exposició simultània en diferents espais i edificis de referència de la ciutat. L’objectiu d’aquesta mostra es oferir al públic la possibilitat de descobrir i gaudir de l’art digital fora dels circuits expositius tradicionals. Oci, cultura i patrimoni es fusionen per oferir una experiència entorn l’Art Digital.

La finalitat d’aquesta mostra es divulgar la disciplina artística digital alhora que projectar i promocionar el treball de diferents artistes. Per aquesta finalitat s’han escollit nous espais i formats expositius. Artinpocket conjuntament amb el Convent de Sant Agustí i amb la col·laboració de IDODI i Blanz, han reunit més de 20 creadors d’art digital per realitzar aquesta primera exhibició.