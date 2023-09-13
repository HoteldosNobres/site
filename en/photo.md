---
language: en
title: Photos
layout: defaultnovo
---

{% assign fotos = site.data.fotosen.fotos %} 
<div id="main">
{% for foto in fotos %}
  <article class="thumb">
      <a href="{{ foto.imagem }}" class="image"><img src="{{ foto.imagem }}" alt="" /></a>
      <h2>{{ foto.title }}</h2>
      <p>{{ foto.subtitle }}</p>
  </article>
  {% endfor %}   
</div>
