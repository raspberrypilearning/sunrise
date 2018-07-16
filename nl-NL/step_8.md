\--- challenge \---

## Uitdaging: meer animatie

Kun je een andere afbeelding animeren? Je kunt de positie, kleur, vorm, grootte, dekking (doorzichtigheid) of iets anders dat je maar kunt bedenken animeren. Probeer ook de hoeveelheid tijd te wijzigen die je animaties lopen.

Voor elk item dat je wilt animeren, moet je:

+ het in je HTML opnemen met een ID
+ een stijl toevoegen voor de ID
+ een @keyframes-regel maken
+ `animation:` gebruiken met de stijl die je hebt gedefinieerd met @keyframes 

Klik op het afbeeldingspictogram om de afbeeldingen te bekijken die in het project zijn opgenomen:

![screenshot](images/sunrise-images.png)

Je kunt ook je eigen afbeeldingen uploaden als je wilt.

Vergeet niet dat je voorwerpen zowel in de zee als in de lucht kunt plaatsen:

![screenshot](images/sunrise-boat.png)

In het voorbeeld gebruikt de regenboog opacity (doorzichtigheid) voor het vervaageffect:

    @keyframes vervagen {
      0%  
      50% 
      66% 
      100%  
    }
    

De boot gebruikt een negatieve startpositie, zodat je het voor een deel van de animatie niet kunt zien:

     @keyframes links-rechts {
      0%   
      100% 
    }
    

\--- /challenge \---