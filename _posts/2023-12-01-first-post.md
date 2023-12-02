---
layout: post
title: Premier post
subtitle: Il y beaucoup à voir!
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
author: Silvan De La Rosa
---

{: .box-success}
Ceci est un post de demonstration pour vous montrer comment écrire des posts avec du markdown. Je vous encourage vivement à [prendre 5 minutes pour apprendre comment écrire en markdown](https://markdowntutorial.com/) - Cela va vous apprendre comment transformer du texte normal en gras/italique/tableaux/etc.<br/> Je vous encourage également à regarder [cette vidéo](https://www.youtube.com/channel/UC5DNocSirFo2o0bonM9FrPw) pour apprendre quelque chose d'important.

**Ceci est du texte en gras**

## Ceci est un sous-titre

Ceci est un tableau:

| Nombre | Nombre suivant | Nombre précédent |
| :------ |:--- | :--- |
| Cinq | Six | Quatre |
| Dix | Onze | Neuf |
| Sept | Huit | Six |
| Deux | Trois | Un |

Que dirais-tu d'une délicieuse crêpe ?

![Crêpe](https://beautifuljekyll.com/assets/img/crepe.jpg)

Elle peut aussi être centrée!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Ceci est du code:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Et voici le même code mais avec de joli couleur:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

Et ceci est encore le même code mais avec le numéro des lignes:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boîtes
Tu peux ajouter des boîtes de notifications, d'alertes et d'erreurs comme ceci:

### Notification

{: .box-note}
**Note:** Ceci est une boites de notifications.

### Alerte

{: .box-warning}
**Alerte:** Ceci est une boîte d'alerte.

### Erreur

{: .box-error}
**Erreur:** Ceci est une boîte d'erreur.
