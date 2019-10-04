## Beskonačna animacija

Napravi da se animacija ponavlja beskonačno mnogo puta.

+ Ako želiš da sunce izlazi, a zatim zalazi, dodaj više ključnih okvira (keyframes) u svoju animaciju:
    
        @keyframes sunrise {0% 33% 66% 100%}
        
    
    To znači da će sunce biti na dnu neba na početku i na kraju animacije te na vrhu neba od 33% do 66% animacije.

+ Now you just need to add the word `infinite` to the `#sun` animation to make it loop forever:
    
    ![screenshot](images/sunrise-infinite.png)

+ Isprobaj svoju animaciju. Sunce se diže i postavlja?