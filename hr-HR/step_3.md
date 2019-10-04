## Animiranje izlaska sunca

Za animiranje izlaska sunca, trebaš odrediti kako se sunce kreće i koliko mu vremena treba da izađe.

Morat ćeš definirati listu **ključnih okvira (key frames)**. Svaki ključni okvir definira CSS svojstva elementa na određenoj poziciji u animaciji.

+ Najprije moraš upotrijebiti `@keyframes` za stvaranje nove animacije imena izlazak sunca.
    
    Dodaj ovaj CSS kôd na kraj svoje `style.css` datoteke:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Ovaj kôd govori suncu gdje se treba postaviti na početku (`0%`) i na kraju (`100%`) animacije.
    
    Pošto se sunce nalazi unutar `div` elementa neba (sky), `gornja (top)` i `lijeva (left` )

+ Sada kada je tvoja animacija `izlaska sunca (sunrise)` gotova, samo trebaš reći suncu da je upotrijebi!
    
    Dodaj označeni kôd u CSS kôd svog sunca:
    
    ![snimka zaslona](images/sunrise-sunrise.png)
    
    Ovaj kôd govori suncu da animira izlazak sunca 10 sekundi.

+ Za ponovno pokretanje animacije u Trinketu, samo klikni **Autorun**.