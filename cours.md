---
layout: cours
title: Cours
---

  <main>
  {% for cours in site.cours %}
  <h2>{{cours.nom}}</h2>
<p>{{cours.content}}</p><br/>
  {% endfor %}
  </main>
