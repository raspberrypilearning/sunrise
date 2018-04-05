## Créer le soleil

Commençons en ajoutant une image pour le soleil et en le positionnant avec un peu de CSS.

+ Ouvrez ce trinket : <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>. 

    Le projet doit ressembler à ça :

	![screenshot](images/sunrise-starter.png)

+ Regardez à l'intérieur du `body` de votre fichier `index.html` et vous trouverez les éléments de `div` pour le ciel et la mer.

    ```
    <div id="sky">
    </div>
    
    <div id="sea">
    </div>
    ```

+ Une image pour le soleil est déjà incluse dans votre projet. 

    Ajoutez l'image à l'intérieur de la `div` soleil en incluant un id pour pouvoir y appliquer un style :

    ![screenshot](images/sunrise-sun-image.png)

+ Whoa, l'image est grande. Allez dans `style.css` et ajoutez le CSS pour régler la hauteur de l'image :

    ![screenshot](images/sunrise-sun-height.png)

    Notez que la largeur est mise à jour automatiquement pour garder les mêmes proportions. 

+ Enfin, ajoutons un peu de code pour positionner le soleil :

    ![screenshot](images/sunrise-sun-position.png)



