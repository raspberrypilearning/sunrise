## Animation sans fin

Faisons en sorte que l'animation se répète indéfiniment.

+ Si tu souhaites que le soleil se lève puis se couche, ajoute simplement des images clés à ton animation:
    
        @keyframes leverdesoleil {
            0%  
            33% 
            66% 
            100%
        }
        
    
    Cela signifie que l'animation commence et se termine avec le soleil au bas du ciel et reste au sommet pendant 33% à 66% de l'animation.

+ Maintenant, il te suffit d’ajouter le mot `infinite` à l’animation `#sun` pour le mettre en boucle pour toujours:
    
    ![captures d'écran](images/sunrise-infinite.png)

+ Teste ton animation. Est-ce que le soleil se lève et se couche sans arrêt?