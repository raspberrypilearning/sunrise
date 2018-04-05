## Animazione infinita

Facciamo in modo che l'animazione si ripeta all'infinito.

+ Se vuoi che il sole sorga e poi tramonti, aggiungiamo altri key frame alla tua animazione:


    ```
    @keyframes sunrise {
        0%   {top:90%; left:0;}
        33%  {top:0; left:40%; }
        66%  {top:0; left:40%; }
        100% {top:90%; left:80%; }
    }
    ```

    Ciò significa che l'animazione inizia e finisce con il sole in fondo al cielo, e rimane nella parte superiore dal 33% al 66% dell'animazione.

+ Ora devi solo aggiungere la parola `infinite` (infinito) all'animazione `#sun` per fare in modo che si ripeta sempre:

    ![screenshot](images/sunrise-infinite.png)

+ Fai un test della tua animazione. Il sole continua a sorgere e tramontare?



