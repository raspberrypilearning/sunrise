## Animacija neba

Animacija ne služi samo za kretanje. Animirajmo nebo tako da noću potamni.

+ Svom CSS-u dodaj animaciju pod nazivom `sky` (nebo):
    
        @keyframes sky {
            0%
            100%
        }
        
    
    Imaj u vidu da ovaj put animiraš boju neba, a ne njegovu poziciju.

+ Svom nebu dodaj kôd, kako bi moglo da koristi tvoju novu animaciju:
    
        animation: sky 10s;
        
    
    ![screenshot](images/sunrise-sky.png)

+ Klikni na **Autorun** da isprobaš svoju animaciju.