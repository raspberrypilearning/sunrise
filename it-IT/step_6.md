## Anima il cielo

L'animazione non riguarda solo il movimento. Facciamo in modo che il cielo diventi scuro la notte.

+ Aggiungi un'animazione chiamata `sky` (cielo) al CSS:

    ```
    @keyframes sky {
        0% {background: black}
        100% {background: lightblue}
    }
    ```

    Nota: questa volta stai animando il colore del cielo, e non la posizione.

+ Aggiungi codice al cielo, per dirgli di usare la nuova animazione:

    ```
    animation: sky 10s;
    ```

    ![screenshot](images/sunrise-sky.png)

+ Fai clic su **Autorun** per provare l'animazione.



