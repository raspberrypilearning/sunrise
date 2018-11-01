## Animacija izlaska sunca

Za animaciju izlaska sunca potrebno je da odrediš kako se sunce kreće i koliko vremena je potrebno da izađe.

Da bismo to uradili, potrebno je da definišemo **key frames** listu (listu ključnih kadrova). Svaki key frame (ključni kadar) definiše CSS svojstva pojedinog elementa u određenom trenutku animacije.

+ Prvo treba da upotrijebiš `@keyframes` za kreiranje nove animacije pod nazivom 'sunrise' (izlazak sunca).
    
    Dodaj sljedeći CSS kôd na kraju svoje `style.css` datoteke:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Ovaj kôd određuje poziciju sunca na početku (`0%`) i na kraju (`100%`) animacije.
    
    Pošto se sunce nalazi unutar `div` za nebo (sky), pozicije `top` (gore) i `left` (lijevo) koje zadaješ su unutar neba, što znači da je `top: 100%` dno neba, a ne dno veb-stranice. 

+ Sada kada smo kreirali animaciju `sunrise` (izlazak sunca), potrebno je samo da kažeš suncu da je koristi!
    
    Dodaj označeni kôd CSS-u za sunce:
    
    ![screenshot](images/sunrise-sunrise.png)
    
    Ovaj kôd govori suncu da animira svoj izlazak u trajanju od 10 sekundi.

+ Da ponovo pokreneš animaciju u Trinketu, samo klikni na **Autorun**.