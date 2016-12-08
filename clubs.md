---
layout: default
title: Clubs
---
<!--{{site.data.clubs}}-->
  <main>
  {% for ligue in site.data.clubs %}
  <p>Name : {{ligue[0]}}</p>

    {% for club in ligue[1] %}
      {{club.key}}<br/>
    {% endfor %}

  {% endfor %}
  </main>
