---
layout: members
title: Membres
---

  <main>
    {% for member in site.data.members %}
      <h2>{{member.nom}}</h2>
      <img src="{{member.avatar}}" alt="{{member.nom}}" width="150px"/>
      <p>Hobbies : {{member.hobbies}}</p>
      <p>Cursus : {{member.cursus}}</p>
      <p>Motivation : {{member.motivation}}</p>
      <p>Equipe de foot : {{member.footballteam}}</p><br/>
    {% endfor %}

    {% for ligue in site.data.clubs %}
      {% assign footballteam = {{member.footballteam}} %}
      {% assign clubs = ligue[1] | where : key, footballteam %}
      {% for club in clubs %}
        {{club.name}}
      {% endfor %}
    {% endfor %}

  </main>
