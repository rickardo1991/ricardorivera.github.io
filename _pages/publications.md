layout: page
permalink: /publications/
title: Publicaciones / Publications
description: "Listado profesional de publicaciones académicas y técnicas. Filtra por autor, año o palabra clave."
nav: true
nav_order: 2
---


<!-- Buscador de publicaciones -->
<div style="margin-bottom:2em;">
	<h2 style="font-weight:600; color:#2c3e50;">Filtra tus publicaciones / Filter your publications</h2>
	{% include bib_search.liquid %}
</div>

<!-- Listado de publicaciones -->
<div class="publications" style="background:#f8f9fa; border-radius:8px; padding:2em; box-shadow:0 2px 8px rgba(0,0,0,0.05);">
	{% bibliography %}
</div>
