## Animare il sorgere del sole

Per animare il sorgere del sole, è necessario definire come si sposta e il tempo impiegato.

per farlo, è necessario definire un elenco di __key frames__. Ogni key frame (fotogramma chiave) definisce le proprietà CSS di un elemento in un punto particolare dell'animazione.

+ Anzitutto è necessario usare `@keyframes` per creare una nuova animazione denominata sorgere del sole.

    Aggiungi questo codice CSS al termine del file `style.css`:

    ```
    @keyframes sunrise {
        0% {top: 90%;}
        100% {top: 0;}
    }
    ```

    Questo codice dice al sole dove posizionarsi all'inizio (`0%`) e alla fine (`100%`) dell'animazione.

    Dal momento che il sole è nel cielo`div`, le posizioni `top` (alto) e `left` (sinistra) date da te si trovano nel cielo, in cui `top: 100%` indica il fondo del cielo, e non della pagina web.


+Ora che hai creato l'animazione `sunrise` non ti rimane che dire al sole di usarla!

   Aggiungi il codice evidenziato al CSS del tuo sole:

   ![screenshot](images/sunrise-sunrise.png)

   In questo modo dici al sole di impiegare 10 secondi per l'animazione.

+ Per eseguire nuovamente l'animazione nel Trinket, fai clic su **Autorun**.



