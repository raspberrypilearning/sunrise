## Animer le lever de soleil

Pour animer ton lever de soleil, il faut définir comment le soleil se déplace et combien de temps il lui faut pour se lever.

Dans ce but, tu définis une liste d' **images clés**. Chaque image clé définit les propriétés CSS d'un élément à un point particulier d'une animation.

+ Tout d'abord, tu dois utiliser `@keyframes` pour créer une nouvelle animation appelée leverdesoleil.
    
    Ajoutez ce code CSS à la fin de votre fichier `style.css`:
    
        @keyframes leverdesoleil {
            0%
            100%
        }
        
    
    Ce code indique la position du soleil au début (`0%`) et à la fin (`100%`) de l'animation.
    
    Parce que le soleil est dans le `div` ciel, les positions `top` et `left` sont par rapport au ciel, `top: 100%` étant le bas du ciel et non le bas de la page Web.

+ Maintenant que tu as créé une animation `leverdesoleil` , il suffit de dire à ton soleil de l'utiliser!
    
    Ajoute le code en surbrillance au CSS de ton soleil:
    
    ![capture d'écran](images/sunrise-sunrise.png)
    
    Cela indique au soleil de passer 10 secondes à animer un lever de soleil.

+ Pour relancer l'animation dans Trinket, clique simplement sur **Autorun**.