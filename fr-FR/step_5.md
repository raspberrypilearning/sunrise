## Animation infinie

Faisons en sorte que l'animation se répète à l'infini.

+ Si vous voulez que le soleil se lève puis se couche, ajoutez plus d'images clés à votre animation :

    ```
    @keyframes sunrise {
        0%   {top:90%; left:0;}
        33%  {top:0; left:40%; }
        66%  {top:0; left:40%; }
        100% {top:90%; left:80%; }
    }
    ```

    Cela signifie que l'animation commence et se termine avec le soleil au bas du ciel, et qu'il reste au sommet de 33 % à 66 % de l'animation.

+ Maintenant, vous devez simplement ajouter le mot `infinite` à l'animation `#sun` pour qu'elle tourne en boucle à l'infini :

    ![screenshot](images/sunrise-infinite.png)

+ Testez votre animation. Le soleil se lève-t-il et se couche-t-il en boucle ? 




