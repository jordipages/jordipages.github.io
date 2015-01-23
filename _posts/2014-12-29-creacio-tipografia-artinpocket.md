---
layout: post
og: true
og-type: article
title: "Creació tipografia Artinpocket" 
share: true
class: artwork
categories:
  - portfoli
work: 2
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

El projecte Artinpocket Regular va néixer amb l’objectiu de desenvolupar, una tipografia pròpia i adequada per al món de les arts plàstiques i visuals. Sota una llicència de Creative Commons tota aquella persona i/o entitat la podrà utilitzar i compartir lliurement a les seves edicions, textos i webs.

El Juliol de 2014 es va presentar la nova tipografia: Artinpocket Regular. L’acte que va tenir lloc el dia 19 de juliol a l’espai La Cort deBanyoles hi varen assistir 32 persones. La presentació a càrrec del dissenyador Jaume Marco de Ió lab ens va explicarà com va ser procés de gestació d’aquesta nova tipografia per a les Arts.