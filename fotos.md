---
title: Fotos do Hotel
layout: defaultnovo 
description: Aqui você encontra fotos do Hotel dos Nobres. Confira todas as nossas fotos.
image: https://hoteldosnobres.com.br/imagens/logo.png
---
 
{% assign fotos = site.data.fotos.fotos %} 
<div id="main">
{% for foto in fotos %}
  <article class="thumb">
      <a href="{{ foto.imagem }}" class="image"><img src="{{ foto.imagem }}" alt="" /></a>
      <h2>{{ foto.title }}</h2>
      <p>{{ foto.subtitle }}</p>
  </article>
  {% endfor %}   
</div>
