## Kreiranje sunca

Počnimo tako što ćemo dodati sliku sunca i pozicionirati je pomoću CSS-a.

+ Otvori sljedeći trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    Projekat treba da izgleda ovako:
    
    ![screenshot](images/sunrise-starter.png)

+ U svojoj datoteci `index.html`, unutar `body`, naći ćeš `div` elemente za nebo i more.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Tvoj projekat već sadrži sliku sunca.
    
    Dodaj sliku unutar svog `div` za nebo. Dodaj i id, kako bi mogao/mogla da stilizuješ sunce:
    
    ![screenshot](images/sunrise-sun-image.png)

+ Hej, slika je ogromna. Pređi na `style.css` i dodaj CSS za podešavanje visine slike:
    
    ![screenshot](images/sunrise-sun-height.png)
    
    Imaj u vidu da se širina automatski ažurira, kako bi proporcije slike ostale iste.

+ Na kraju, dodajmo kôd za pozicioniranje sunca:
    
    ![screenshot](images/sunrise-sun-position.png)