## Animiranje izlaska sunca

Da biste animirali izlazak sunca, trebate odrediti kako se kreće sunce i koliko je vremena potrebno za uspon.

Da biste to učinili, definirate popis **ključnih okvira**. Svaki ključni okvir definira CSS svojstva elementa na određenoj točki u animaciji.

+ Najprije morate upotrijebiti `@keyframes` da biste stvorili novu animaciju zvanu izlazak sunca.
    
    Dodajte ovaj CSS kôd do kraja `style.css` datoteke:
    
        @keyframes sunrise {0% 100%}
        
    
    Ovaj kôd govori suncu gdje se treba postaviti na početku (`0%`) i kraj (`100%`) animacije.
    
    Because the sun is inside the sky `div`, the `top` and `left` positions you give are within to the sky, with `top: 100%` being the bottom of the sky, and not the bottom of the webpage.

+ Sada kada ste stvorili animaciju `izlaska sunca` , samo trebate reći suncu da je upotrebljava!
    
    Dodajte označeni kôd na svoj Sunčev CSS:
    
    ![screenshot](images/sunrise-sunrise.png)
    
    Ovo govori suncu da provede 10 sekundi animiranje izlaska sunca.

+ Da biste ponovno pokrenuli animaciju u Trinketu, samo kliknite **Autorun**.