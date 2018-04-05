## Animer le lever de soleil

Pour animer votre lever de soleil, vous devez définir comment le soleil bouge et combien il met de temps à se lever.

Pour ce faire, vous devez définir une liste __images clés__. Chaque image clé définit les propriétés CSS d'un élément à un point spécifique de l'animation. 

+ D'abord, vous devez utiliser `@keyframes` pour créer une nouvelle animation appelée lever de soleil. 

    Ajoutez ce code CSS à la fin de votre fichier `style.css` :

    ```
    @keyframes sunrise {
        0% {top: 90%;}
        100% {top: 0;}
    }
    ```

    Ce code indique au soleil où se positionner au début (`0%`) et à la fin (`100%`)de l'animation.

    Puisque le soleil est à l'intérieur de la `div` ciel, les positions `top` et `left` que vous donnez sont comprises dans le ciel, avec `top : 100%` étant le bas du ciel, et non le bas de la page Web.


+ Maintenant que vous avez créé une animation `sunrise`, vous devez simplement dire à votre soleil de l'utiliser ! 

    Ajoutez le code en surbrillance au CSS de votre soleil :

    ![screenshot](images/sunrise-sunrise.png)

    Il indique à votre soleil de passer 10 secondes à animer un lever de soleil.

+ Pour lancer l'animation à nouveau dans Trinket, cliquez simplement sur **Autorun**. 

