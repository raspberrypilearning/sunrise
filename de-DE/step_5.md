## Endlose Animation

Lass uns die Animation so machen dass sie sich für immer wiederholt.

+ Wenn du willst, dass die Sonne aufgeht und anschließend untergeht, füge deiner Animation einfach weitere Keyframes hinzu:
    
        @keyframes sunrise {
            0%  
            33% 
            66% 
            100%
        }
        
    
    Das bedeutet, dass die Animation mit der Sonne am unteren Rand des Himmels beginnt und endet und von 33% bis 66% der Animation am oberen Rand stehen bleibt.

+ Jetzt musst du der Animation `#sun` nur noch das Wort `infinite` hinzufügen, damit sie für immer wiederholt wird:
    
    ![Bildschirmfoto](images/sunrise-infinite.png)

+ Teste deine Animation. Geht die Sonne immer wieder auf und unter?