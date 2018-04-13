## Stvaranje sunca

Počnimo s dodavanjem slike za sunce i pozicioniranjem nekim CSS-om.

+ Otvori ovaj trik: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    Projekt bi trebao izgledati ovako:
    
    ![zaslona](images/sunrise-starter.png)

+ Pogledajte unutar `tijela` vaše `index.html` datoteke i pronaći ćete elemente `div` za nebo i more.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Slika za sunce već je uključena u vaš projekt.
    
    Dodajte sliku unutar vašeg sunca `div` uključujući ID kako biste ga mogli oblikovati:
    
    ![zaslona](images/sunrise-sun-image.png)

+ Whoa, slika je ogromna. Idite na `style.css` i dodajte CSS da biste postavili visinu slike:
    
    ![zaslona](images/sunrise-sun-height.png)
    
    Imajte na umu da se širina automatski ažurira kako bi proporcije bile iste.

+ Naposljetku, dodajmo neki kôd za postavljanje sunca:
    
    ![zaslona](images/sunrise-sun-position.png)