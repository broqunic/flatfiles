---
layout: products
title: Produits
---
<h2>Baguettes Harry Potter</h2>
{% for product in site.products %}
  {% include products.html %}
{% endfor %}
<div class="clearfix"></div>
