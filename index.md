---
title: page d'accueil
description: ma déscription
---

# Titre de ma page

texte de ma page
{{ site.title }} 

{% for page in site.pages %}
  <ul>
    <li>{{ page.title }}</li>
  </ul>
{% endfor %}