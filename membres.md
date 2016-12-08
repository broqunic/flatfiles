---
layout: membres
title: Membres
---

  <main>
  {% for membre in site.membres %}
  <h2>{{membres.nom}}</h2>
  <img src="membres.avatar" alt="membres.nom"/>
<p>{{membre.hobbies}}</p><br/>
<p>{{membre.cursus}}</p><br/>
<p>{{membre.motivation}}</p><br/>
<p>{{membre.amis}}</p><br/>


  {% endfor %}
  </main>
