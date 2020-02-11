## Beskonačna animacija

Napravi da se animacija ponavlja beskonačno mnogo puta.

+ Ako želiš da sunce izlazi, a zatim zalazi, dodaj više ključnih okvira (keyframes) u svoju animaciju:
```    
        @keyframes sunrise {0% 33% 66% 100%}
```        
    
    To znači da će sunce biti na dnu neba na početku i na kraju animacije te na vrhu neba od 33% do 66% animacije.

+ Sada još samo trebate dodati riječ `infinite` na `#sun` animaciju kako bi napravili beskonačnu petlju:
    
    ![screenshot](images/sunrise-infinite.png)

+ Isprobaj svoju animaciju. Diže li se i postavlja sunce?