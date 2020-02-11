## Créer le soleil

Commençons par ajouter une image pour le soleil et la positionner avec du CSS.

+ Ouvre ce trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    Le projet devrait ressembler à ceci:
    
    ![capture d'écran](images/sunrise-starter.png)

+ Regarde à l'intérieur du `corps` de ton fichier `index.html` et tu trouveras les éléments `div` pour le ciel et la mer.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Une image pour le soleil est déjà incluse dans ton projet.
    
    Ajoute l'image à l'intérieur de ton `div` soleil avec un identifiant pour pouvoir lui affecter un style:
    
    ![capture d'écran](images/sunrise-sun-image.png)

+ Whoa, l'image est énorme. Va à `style.css` et ajoute le CSS pour définir la hauteur de l'image:
    
    ![capture d'écran](images/sunrise-sun-height.png)
    
    Note que la largeur est mise à jour automatiquement pour conserver les mêmes proportions.

+ Enfin, ajoutons du code pour positionner le soleil:
    
    ![capture d'écran](images/sunrise-sun-position.png)