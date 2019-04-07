---
layout: default
description: "Un modèle Jekyll pour publier des sites Web et des articles d'une seule page qui sont très lisibles et responsive"
---

### Liste des articles

{% for post in site.posts %}
<a href="{{post.url | prepend:site.baseurl}}">{{post.title}}</a>
{% endfor %}

### Auteur

Robert Schuman

@rob
