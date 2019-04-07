---
title: "Decription du moteur good clean read"
toc: true
description: "Un modèle Jekyll pour publier des sites Web et des articles d'une seule page qui sont très lisibles et responsive"
date: 2019-04-07
last_modified_at: 2019-04-07
---

### Nice, clean, reading!

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed <code>index.md</code> do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum <code>index.md</code>.

> "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Notes de bas de page

Lorem ipsum dolor sit amet, consectetur adipiscing elit.[^1] Ut enim ad minim veniam.[^2]

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Boutons de partage social

Ajoutez simplement la ligne suivante n'importe où dans votre markdown:

<pre><code>{% raw  %}
{% include sharing.html %}
{% endraw %}
</code></pre>

et obtenez un ruban de partage.

{% include sharing.html %}

Ajoutez-le en bas et au plus de la page, entre les paragraphes, ...

N'oubliez pas de personnaliser les boutons pour qu'ils correspondent à votre url dans le fichier `_includes/sharing.html`.  Ces boutons sont disponibles et personnalisables chez kni-labs. Consultez la documentation sur [https://github.com/kni-labs/rrssb](https://github.com/kni-labs/rrssb) pour plus d'informations.

### Font awesome inclus

<i class="fa fa-quote-left fa-3x fa-pull-left fa-border"></i> Maintenant vous pouvez utiliser toutes les icônes cool que vous voulez ! [Font Awesome](http://fontawesome.io) est en effet génial. Si vous n'avez pas besoin de cette facilité, vous pouvez la désactiver dans le fichier `config.yml`.

```html
<i class="fa fa-quote-left fa-3x fa-pull-left fa-border"></i> Maintenant vous pouvez utiliser toutes les icônes cool que vous voulez ! [Font Awesome](http://fontawesome.io) est en effet génial. Si vous n'avez pas besoin de cette facilité, vous pouvez la désactiver dans le fichier `config.yml`.
```

<ul class="fa-ul">
  <li><i class="fa-li fa fa-check-square"></i>On peut faire des listes</li>
  <li><i class="fa-li fa fa-check-square-o"></i>avec des icônes comme celle-ci</li>
  <li><i class="fa-li fa fa-spinner fa-spin"></i>et même une icône animée</li>
</ul>

```html
<ul class="fa-ul">
  <li><i class="fa-li fa fa-check-square"></i>On peut faire des listes</li>
  <li><i class="fa-li fa fa-check-square-o"></i>avec des icônes comme celle-ci</li>
  <li><i class="fa-li fa fa-spinner fa-spin"></i>et même une icône animée</li>
</ul>
```

Si vous en avez besoin, vous pouvez coller n'importe laquelle de ces [1513 icônes gratuites](https://fontawesome.com/icons?d=gallery&m=free) n'importe où, avec la taille que vous voulez. ([Voyez la documentation](https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use))

<i class="fa fa-building"></i>&nbsp;&nbsp;<i class="fa fa-bus fa-lg"></i>&nbsp;&nbsp;<i class="fa fa-cube fa-2x"></i>&nbsp;&nbsp;<i class="fa fa-paper-plane fa-3x"></i>&nbsp;&nbsp;<i class="fa fa-camera-retro fa-4x">

```html
<i class="fa fa-building"></i>&nbsp;&nbsp;
<i class="fa fa-bus fa-lg"></i>&nbsp;&nbsp;
<i class="fa fa-cube fa-2x"></i>&nbsp;&nbsp;
<i class="fa fa-paper-plane fa-3x"></i>&nbsp;&nbsp;
<i class="fa fa-camera-retro fa-4x">
```

### Ajoutez des images

Images play nicely with this template as well. Add diagrams or charts to make your point, and the template will fit them in appropriately.

![Hello]({{site.baseurl}}/images/hello.svg)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Contributions

* [Adam Dueck](https://github.com/adueck) avec [good-clean-read](https://github.com/adueck/good-clean-read).
* [Shu Uesengi](https://github.com/chibicode) avec [solo](https://github.com/chibicode).

---

**Notes de bas de page**

[^1]: Ceci est une note de bas de page. Cliquez sur le retour.

[^2]: Here is another.
