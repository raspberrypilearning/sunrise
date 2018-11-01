## Neprekidna animacija

Napravimo da se animacija neprestano ponavlja.

+ Ako želiš da sunce izađe, a zatim zađe, treba samo da dodaš još ključnih kadrova (keyframes) u svoju animaciju:
    
        @keyframes sunrise {
            0%  
            33% 
            66% 
            100%
        }
        
    
    To znači da animacija počinje i završava se sa suncem na dnu neba, a da sunce ostaje na vrhu neba od 33% do 66% animacije.

+ Sada samo treba da animaciji `#sun` dodaš riječ `infinite` kako bi se neprestano ponavljala:
    
    ![screenshot](images/sunrise-infinite.png)

+ Isprobaj svoju animaciju. Da li sunce neprestano izlazi i zalazi?