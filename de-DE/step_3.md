## Den Sonnenaufgang animieren

Um den Sonnenaufgang zu animieren, musst du definieren, wie sich die Sonne bewegt und wie lange es dauert, bis sie aufgeht.

Um das zu erreichen, definierst du eine Liste von **keyframes**. Jeder keyframe definiert die CSS-Eigenschaften eines Elements an einem bestimmten Punkt in einer Animation.

+ Zuerst musst du `@keyframes` nutzen, um eine neue Animation namens sunrise zu erstellen.
    
    Füge diesen CSS-Code am Ende deiner Datei `style.css` hinzu:
    ```
        @keyframes sunrise {
            0%
            100%
        }
    ```    
    
    Dieser Code teilt der Sonne mit, wo sie sich am Anfang (`0%`) und am Ende (`100%`) der Animation positionieren soll.
    
    Da sich die Sonne innerhalb des Himmel ("sky") `div` Tags befindet, sind die `top` und `left` Positionen innerhalb des Himmels gesetzt, wobei `top: 100%` das untere Ende des Himmels und nicht der untere Rand der Webseite ist.

+ Nachdem du eine `sunrise` Animation erstellt hast, musst du deiner Sonne nur noch mitteilen, dass sie diese verwenden soll!
    
    Füge den markierten Code in das CSS deiner Sonne ein:
    
    ![Bildschirmfoto](images/sunrise-sunrise.png)
    
    Dies weist die Sonne an, 10 Sekunden für die Sonnenaufgang Animation zu verwenden.

+ Um die Animation in Trinket erneut auszuführen, klick einfach auf **Autorun**.