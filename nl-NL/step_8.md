--- challenge ---

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

    @keyframes fade {
      0%  
      50% 
      66% 
      100%  
    }
    

De boot gebruikt een negatieve startpositie, zodat je het voor een deel van de animatie niet kunt zien:

     @keyframes left-right {
      0%   
      100% 
    }
    

--- /challenge ---

***
Dit project werd vertaald door vrijwilligers:

**Cor Groot**

**Henny van Ham**

Dankzij vrijwilligers kunnen we mensen over de hele wereld de kans geven om in hun eigen taal te leren. Jij kunt ons helpen meer mensen te bereiken door vrijwillig te starten met vertalen - meer informatie op [rpf.io/translate](https://rpf.io/translate).