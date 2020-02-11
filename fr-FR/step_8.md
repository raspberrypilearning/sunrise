--- challenge ---

## Défi : D'autres animations

Peux-tu animer une autre image? Tu peux animer la position, la couleur, la forme, la taille, l'opacité (la transparence) ou toute autre chose à laquelle tu peux penser. Essaye également de modifier la durée d'exécution de tes animations.

Pour chaque élément que tu souhaites animer, il faut:

+ L'inclure dans votre ton HTML avec un identifiant
+ Ajouter un style pour l'identifiant
+ Créer une règle @keyframes
+ Utiliser `animation:` dans le style pour employer l'animation définie avec @keyframes 

Clique sur l'icône de l'image pour voir les images incluses dans le projet:

![capture d'écran](images/sunrise-images.png)

Tu peux également télécharger tes propres images si tu le souhaites.

N'oublie pas que tu peux ajouter des objets dans la mer et dans le ciel:

![capture d'écran](images/sunrise-boat.png)

Dans l'exemple, l'arc-en-ciel utilise l'opacité pour un effet de fondu:

    @keyframes fade {
      0%  
      50% 
      66% 
      100%  
    }
    

Le bateau utilise une position de départ négative afin que tu ne puisses pas le voir pendant une partie de l'animation:

     @keyframes left-right {
      0%   
      100% 
    }
    

--- /challenge ---

***

Ce projet a été traduit par des bénévoles:

Fabrice Debart

Michel Arnols

Grâce aux bénévoles, nous pouvons donner aux gens du monde entier la chance d'apprendre dans leur propre langue. Vous pouvez nous aider à atteindre plus de personnes en vous portant volontaire pour la traduction - plus d'informations sur [rpf.io/translate](https://rpf.io/translate).