---
title: Fotos do Hotel
layout: defaultnovo 
description: Aqui você encontra fotos do Hotel dos Nobres. Confira todas as nossas fotos.
image: https://hoteldosnobres.com.br/imagens/banner.jpg
---
{% assign fotos = site.data.fotos.fotos %}
<div id="main" style="height: 100vh;">
  <div style="background-image: url('{{ fotos[0].imagem }}'); background-size: cover; background-position: center; padding: 20px; height: 100%; display: flex; justify-content: center; align-items: center;"> 
    <div style="text-align: center; border: 2px solid #000; padding: 20px; background-color: rgba(255, 255, 255, 0.7); border-radius: 10px;">
      <p>O Hotel dos Nobres estará passando por um período de atualização do site. Em breve, teremos um novo site, melhor e com mais novidades para você!!!</p>
    </div>
  </div>
</div>