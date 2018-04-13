## Beskonačna animacija

Učinimo da se animacija ponavlja zauvijek.

+ Ako želite da se sunce diže, a zatim postavite, dodajte više ključnih okvira u svoju animaciju:
    
        @keyframes sunrise {0% 33% 66% 100%}
        
    
    To znači da se animacija počinje i završava suncem na dnu neba i ostaje na vrhu od 33% do 66% animacije.

+ Now you just need to add the word `infinite` to the `#sun` animation to make it loop forever:
    
    ![zaslona](images/sunrise-infinite.png)

+ Isprobajte svoju animaciju. Sunce se diže i postavlja?