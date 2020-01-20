## Den Sonnenaufgang animieren

Um Ihren Sonnenaufgang zu animieren, müssen Sie definieren, wie sich die Sonne bewegt und wie lange es dauert, bis sie aufgeht.

Dazu definieren Sie eine Liste von **Keyframes**. Jeder Keyframe definiert die CSS-Eigenschaften eines Elements an einem bestimmten Punkt in einer Animation.

+ Zuerst müssen Sie `@keyframes` , um eine neue Animation namens sunrise zu erstellen.
    
    Fügen Sie diesen CSS-Code am Ende Ihrer Datei `style.css`:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Dieser Code teilt der Sonne mit, wo sie sich am Anfang (`0%`) und am Ende (`100%`) der Animation positionieren soll.
    
    Da sich die Sonne innerhalb des Himmels befindet `div`, befinden sich die `oberen` und `linken` Positionen innerhalb des Himmels, wobei `oben: 100%` die Unterseite des Himmels und nicht die Unterseite der Webseite ist.

+ Nachdem Sie eine `sunrise` Animation erstellt haben, müssen Sie Ihrer Sonne nur noch mitteilen, dass sie diese verwenden soll!
    
    Fügen Sie den markierten Code in das CSS Ihrer Sonne ein:
    
    ![Screenshot](images/sunrise-sunrise.png)
    
    Dies weist die Sonne an, 10 Sekunden damit zu verbringen, einen Sonnenaufgang zu animieren.

+ Um die Animation in Trinket erneut auszuführen, klicken Sie einfach auf **Autorun**.