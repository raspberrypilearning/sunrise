## Den Sonnenaufgang animieren

Um den Sonnenaufgang  zu animieren, musst du definieren, wie sich die Sonne bewegt und wie lange es dauern soll, bis sie aufgeht.

Damit du dies tun kannst, musst du eine Liste von sog. __Keyframes__, bzw. Schlüsselbildern definieren. Jeder „Keyframe“ definiert die CSS-Eigenschaften eines Elements zu einem bestimmten Zeitpunkt der Animation. 

+ Als erstes musst du `@keyframes` (Schlüsselbilder) benutzen, um eine neue Animation namens Sonnenaufgang zu erstellen. 

    Füge diesen CSS-Code zum Ende deiner `style.css` Datei hinzu:

    ```
    @keyframes Sonnenaufgang {
        0% {oben: 90%;}
        100% {oben: 0;}
    }
    ```

    Dieser Code teilt der Sonne mit, wo sie zu Beginn (`0%`) und zum Ende (`100%`) der Animation positioniert ist.

    Da die Sonne sich im Himmel `div` befindet, sind die `top` (oben) und `left` (links) Positionen, die du gibst, innerhalb „zum Himmel“, wobei `top: 100%` (oben 100%) die Unterseite des Himmels bedeutet und nicht die Unterseite deiner Webseite.


+ Jetzt, wo du eine `sunrise` (Sonnenaufgang) Animation erstellt hast, musst du nur noch der Sonne mitteilen, diese zu benutzen! 

    Füge den markierten Code zum CSS deiner Sonne hinzu:

    ![screenshot](images/sunrise-sunrise.png)

    Dies teilt der Sonne mit, 10 Sekunden damit zu verbringen, einen Sonnenaufgang zu animieren.

+ Um diese Animation erneut laufen zu lassen, brauchst du im Trinket einfach nur auf **Autorun** (automatisch laufen lassen) zu klicken. 

