--- challenge ---
## Challenge: Plus d'animations

Pouvez-vous animer une autre image ? Vous pouvez animer la position, la couleur, la forme, la taille, l'opacité (seethroughness) ou tout ce à quoi vous pouvez penser. Essayez également de changer la durée de vos animations. 

Pour chaque objet que vous souhaitez animer, il vous faudra :

+ L'inclure dans votre HTML avec un id
+ Ajouter un style pour l'id
+ Créer une règle @keyframes
+ Utiliser `animation:` dans le style pour utiliser l'animation que vous avez définie avec @keyframes 

Cliquez sur l'icône image pour voir les images qui sont incluses dans le projet :

![screenshot](images/sunrise-images.png)

Vous pouvez aussi mettre en ligne vos propres images si vous le souhaitez. 

N'oubliez pas de placer les objets dans la mer ainsi que dans le ciel :

![screenshot](images/sunrise-boat.png)

Dans l'exemple, l'arc-en-ciel utilise l'opacité pour obtenir un effet d'atténuation :

```
@keyframes fade {
  0%   {opacity: 0;}
  50%  {opacity: 100;}
  66%  {opacity: 0;}
  100%   {opacity: 0;}
}
```

Le bateau utilise une position de départ négative pour que vous ne puissiez pas le voir pendant une partie de l'animation :

```
 @keyframes left-right {
  0%    {left:-50%;}
  100%  {left:200%;}
}
```




--- /challenge ---