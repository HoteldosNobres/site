---
title:
layout: defaultnovo 
description: Aqui você encontra fotos do Hotel dos Nobres. Confira todas as nossas fotos.
image: https://hoteldosnobres.com.br/imagens/banner.jpg
---
{% assign fotos = site.data.fotos.fotos %}
{% if page.language == "en" %}
{% assign empresa = site.data.dataen.empresa %}
{% else %}
{% assign empresa = site.data.data.empresa %}
{% endif %}
<div id="main" style="height: 100vh;">
  <div style="background-image: url('{{ fotos[0].imagem }}'); background-size: cover; background-position: center; padding: 20px; height: 100%; display: flex; justify-content: center; align-items: center;"> 
    <div style="text-align: center; border: 2px solid #000; padding: 20px; background-color: rgba(255, 255, 255, 0.7); border-radius: 10px;">
      <section > 
       <p>O Hotel dos Nobres estará passando por um período de atualização do site 👨‍💻 . Em breve, teremos um novo site, melhor e com mais novidades para você! Fique ligado! 🚀</p>
          <h2 style="color: red;">{{ empresa.redesociais }}</h2>
          <ul style="color: red;" class="icons"> 
            <li><a href="{{ empresa.instagram }}"><span style="color: red;" class="label"><i class="fab fa-instagram"></i> Instagram</span></a></li> 
            <li><a href="{{ empresa.whatsapp }}" ><span style="color: red;" class="label"><i class="fab fa-whatsapp"></i>Whatsapp</span></a></li> 
          </ul>  
      </section>
    </div>
  </div>
</div>