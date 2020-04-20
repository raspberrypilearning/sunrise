## Introduction

Dans ce projet, tu apprendras à utiliser CSS pour créer un lever de soleil animé.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Informations complémentaires pour les responsables de club

Pour imprimer ce projet, merci d'utiliser la [version imprimable](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Notes pour le responsable de club

## Introduction :

Dans ce projet, les enfants apprendront à animer une scène simple à l'aide de CSS. Ils utiliseront la règle CSS @keyframes pour animer diverses propriétés d’images et de div.

## Ressources en ligne

Nous vous recommandons d'utiliser [trinket](https://trinket.io/) pour écrire le code HTML et CSS en ligne. Ce projet contient les Trinkets suivants :

+ [Point de départ du « Lever de soleil »](http://jumpto.cc/web-sunrise)

Les enfants peuvent également utiliser ce trinket vide [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) pour écrire leur propre code HTML & CSS, ou utiliser ce trinket modèle [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Il y a aussi un Trinket contenant un exemple de solution pour les défis :

+ [« Lever de soleil » terminé](https://trinket.io/html/abcc0284a3)

## Ressources hors-ligne

Ce projet peut être [terminé hors-ligne](../offline.html) si désiré. Vous pouvez accéder aux ressources du projet en cliquant sur le lien « Télécharger les matériaux du projet » pour ce projet. Ce lien contient un dossier « Ressources du projet », qui inclut les ressources dont les enfants auront besoin pour mener à bien ce projet hors-ligne. Assurez-vous que les enfants ont accès à une copie de ces ressources. Ce dossier comprend les fichiers suivants :

+ template/index.html
+ template/prefix.js
+ template/style.css
+ sunrise / index.html
+ sunrise / style.css
+ sunrise / prefixfree.js
+ sunrise / boat.png
+ sunrise / cloud.png
+ sunrise / helicopter.png
+ sunrise / rainbow.png
+ sunrise / sun.png

Vous pouvez aussi trouver une version terminée du projet dans la section « Ressources du bénévole » qui contient :

+ sunrise-finish / index.html
+ sunrise-finish / style.css
+ sunrise-finish / prefixfree.js
+ sunrise-finish / boat.png
+ sunrise-finish / sun.png
+ sunrise-finish / rainbow.png

## Objectifs d'apprentissage

+ Style et animation avec CSS : 
    + Introduction à la règle `@keyframes` pour définir les étapes d'une animation.
    + Renforcer l'utilisation des propriétés pour définir la taille, la forme, la position et la couleur des éléments d'une page Web.

Ce projet traite les éléments suivants du [Programme Raspberry Pi de Création Numérique](http://rpf.io/curriculum) :

+ [Concevoir des éléments de base en 2D et 3D](https://www.raspberrypi.org/curriculum/design/creator).

## Défis

+ « Animation diagonale » - édition des propriétés de l'animation `@keyframe` pour utiliser left.
+ « Améliorer le ciel » - ajouter plus de keyframes et fixer le fond d'écran.
+ « Plus d'animation » - animer plus d'images ou d'éléments en utilisant diverses propriétés CSS. 

## Foire aux questions

+ Ce projet utilise la bibliothèque javascript `prefixfree.js` pour permettre la compatibilité des animations entre les navigateurs. Si cette bibliothèque n'est pas utilisée, les enfants utilisant des navigateurs plus anciens devront plutôt déclarer une animation pour leur navigateur, par exemple :

    animation: sky 10s infini; // pour tous les nouveaux navigateurs
    -webkit-animation: sky 10s infinite; // Pour les navigateurs Webkit (Chrome, Safari ...)
    -moz-animation: sky 10s infinite; // Pour les navigateurs Mozilla
    -o-animation: sky 10s infinite; // Pour les navigateurs Opera,
    -ms-animation: sky 10s infinite; // Pour les navigateurs Microsoft 
    

\--- /collapse \---

## \--- collapse \---

## title: Matériaux pour le projet

## Ressources du projet

+ [Fichier .zip contenant toutes les ressources du projet](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Trinket en ligne contenant toutes les ressources du projet « Lever de soleil »](http://jumpto.cc/web-sunrise)
+ [Modèle de Trinket en ligne](http://jumpto.cc/trinket-template)
+ [Trinket en ligne vide](http://jumpto.cc/trinket-blank)
+ [template/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-index.html)
+ [template/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-style.css)
+ [intro/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-index.html)
+ [intro/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-style.css)
+ [sunrise / index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-index.html)
+ [sunrise / style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-style.css)
+ [sunrise / prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-prefixfree.js)
+ [sunrise / sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-sun.png)
+ [sunrise / rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-rainbow.png)
+ [sunrise / cloud.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-cloud.png)
+ [sunrise / boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-boat.png)
+ [sunrise / helicopter.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-helicopter.png)

## Ressources pour le responsable de club

+ [Fichier .zip contenant toutes les ressources du projet terminé](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Projet Trinket en ligne terminé](https://trinket.io/html/abcc0284a3)
+ [sunrise-finish / index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finish / style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finish / prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finish / sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finish / boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finish / rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---