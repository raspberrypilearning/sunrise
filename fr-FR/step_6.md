## Animer le ciel

L'animation n'est pas que pour les mouvements. Animons le ciel pour qu'il soit sombre la nuit.

+ Ajoutez une animation appelée  `sky` à votre CSS :

    ```
    @keyframes sky {
        0% {background: black}
        100% {background: lightblue}
    }
    ```

    Remarquez que cette fois vous animez la couleur du ciel, et non pas une position.

+ Ajoutez du code à votre ciel pour lui dire d'utiliser votre nouvelle animation :

    ```
    animation: sky 10s;
    ```

    ![screenshot](images/sunrise-sky.png)

+ Cliquez sur **Autorun** pour tester votre animation. 


