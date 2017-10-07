---
title: page d'accueil
description: ma déscription
---

# Titre de ma page

texte de ma page
{{ site.title }} 

{% for page in site.pages %}
  <ul>
    <li>{{ page.contact }}</li>
    <li>{{ page.autrepage }}</li>
  </ul>
{% endfor %}