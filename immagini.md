---
layout: page
title: Immagini
sidebar_link: true
lang: 'it_IT'
images:
  - name: risorse/immagini/donato-falco.jpeg
    title: Foto Profilo
  - name: risorse/immagini/anima-mundi.jpeg
    title: Pisa, Anima Mundi, 15 settembre 2016
  - name: risorse/immagini/anima-mundi-premiazione.jpeg
    title: Pisa, Anima Mundi 2016, Premiazione
  - name: risorse/immagini/anima-mundi-coro.jpeg
    title: Pisa, Anima Mundi 2016, Coro Costanzo Porta
---


<div class="container-grid">
{% for img in page.images %}
  <div class="card small">
    <div class="card-image">
      <img src="{{img.name}}" >
    </div>
    <div class="card-body">
      <div class="card-text">
      <h3>{{img.title}}</h3>
      <a href="{{img.name}}" target="_blank">Ottieni formato originale &raquo;</a>
      </div>
    </div>

  </div>
{% endfor %}
</div>
