---
title: page d'accueil
description: ma déscription
contact: contact
autrepage: autrepage
---

# Titre de ma page

texte de ma page
{{ site.title }} 

{% for page in site.pages %}
  <ul>
    <li>
      <a href="{{ page.contact }} ">{{ page.contact }}</a>
    </li>
    <li>
      <a href="{{ page.autrepage }}">{{ page.autrepage }}</a>
    </li>
  </ul>
{% endfor %}