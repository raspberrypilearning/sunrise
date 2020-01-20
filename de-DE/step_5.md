## Unendliche Animation

Lassen Sie uns die Animation für immer wiederholen.

+ Wenn Sie möchten, dass die Sonne aufgeht und dann untergeht, fügen Sie Ihrer Animation einfach weitere Keyframes hinzu:
    
        @keyframes sunrise {
            0%  
            33% 
            66% 
            100%
        }
        
    
    Dies bedeutet, dass die Animation mit der Sonne am unteren Rand des Himmels beginnt und endet und von 33% bis 66% der Animation am oberen Rand bleibt.

+ Jetzt müssen Sie der Animation `#sun` nur noch das Wort `infinite` hinzufügen, damit sie für immer wiederholt wird:
    
    ![screenshot](images/sunrise-infinite.png)

+ Testen Sie Ihre Animation. Geht die Sonne immer wieder auf und unter?