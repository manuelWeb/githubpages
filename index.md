---
title: page d'accueil
description: ma déscription
---

# Titre de ma page

texte de ma page
{{ site.title }} 

{% for page in site.pages %}
  <ul>
    <li>
      <a href="{{ page.contact }} ">{{ page.contact }}</a>
    </li>
    <li>{{ page.autrepage.md }}</li>
  </ul>
{% endfor %}