## Animer le ciel

L'animation ne concerne pas seulement le mouvement. Animons le ciel pour qu'il s'assombrisse la nuit.

+ Ajoute une animation appelée `ciel` à ton CSS :
    
        @keyframes ciel {
            0%
            100%
        }
        
    
    Note que cette fois, tu animes la couleur du ciel et non sa position.

+ Ajoute du code à ton ciel, pour lui dire d’utiliser ta nouvelle animation :
    
        animation: ciel 10s;
        
    
    ![captures d'écran](images/sunrise-sky.png)

+ Clique sur **Autorun** pour tester ton animation.