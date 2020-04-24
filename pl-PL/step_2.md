## De zon creëren

Laten we beginnen met een afbeelding voor de zon toe te voegen en deze te positioneren met wat CSS.

+ Open deze trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    Het project zou er als volgt uit moeten zien:
    
    ![screenshot](images/sunrise-starter.png)

+ Kijk in de `body` van je `index.html` bestand en je zult de de `div` elementen voor de lucht en de zee vinden.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Een afbeelding voor de zon is al in je project opgenomen.
    
    Voeg de afbeelding in je zon toe `div` inclusief een id zodat je het kunt stylen:
    
    ![screenshot](images/sunrise-sun-image.png)

+ Whoa, het beeld is enorm. Ga naar `style.css` en voeg de CSS toe om de hoogte van de afbeelding in te stellen:
    
    ![screenshot](images/sunrise-sun-height.png)
    
    Merk op dat de breedte automatisch wordt bijgewerkt om de verhoudingen hetzelfde te houden.

+ Laten we tot slot een code toevoegen om de zon te positioneren:
    
    ![screenshot](images/sunrise-sun-position.png)