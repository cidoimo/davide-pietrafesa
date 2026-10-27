---
layout: page
title: cene con delitto
permalink: /cene-con-delitto/
description: Gialli da giocare a tavola, scritti da me e pronti da stampare.
nav: true
nav_order: 3
horizontal: false
---

Una cena con delitto è una serata in cui gli invitati non sono solo ospiti: ognuno riceve un personaggio, con la sua storia, i suoi segreti e qualcosa da nascondere. Tra una portata e l'altra escono indizi, prove e rivelazioni, e prima del dolce bisogna capire chi è l'assassino.

Scrivo queste storie per giocarle con i miei amici, e ora le preparo in kit completi da stampare a casa. Li trovi sul mio [negozio Etsy](https://www.etsy.com/it/people/ym0bru7jydreew7f).

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
