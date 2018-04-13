\--- challenge \---

## Uitdaging: Meer animaties

Kun je een andere afbeelding animeren? Je kunt de positie, kleur, vorm, grootte, dekking (doorkijk) of iets anders dat je maar kunt bedenken animeren. Probeer ook de hoeveelheid tijd die je animaties lopen te wijzigen.

Voor elk item dat je wilt animeren, moet je:

+ Neem het in je HTML op met een ID
+ Voeg een stijl toe voor de ID
+ Maak een @keyframes-regel
+ Gebruik `animation:` in de stijl om de animatie te gebruiken die je hebt gedefinieerd met @keyframes 

Klik op het afbeeldingspictogram om de afbeeldingen te bekijken die in het project zijn opgenomen:

![screenshot](images/sunrise-images.png)

Je kunt ook je eigen afbeeldingen uploaden als je wilt.

Vergeet niet dat je voorwerpen zowel in de zee als in de lucht kunt plaatsen:

![screenshot](images/sunrise-boat.png)

In het voorbeeld gebruikt de regenboog voor een vervagingseffect fade:

    @keyframes vervagen {0% 50% 66% 100%}
    

De boot gebruikt een negatieve startpositie, zodat je het voor een deel van de animatie niet kunt zien:

     @keyframes left-right {
      0%   
      100% 
    }
    

\--- /challenge \---