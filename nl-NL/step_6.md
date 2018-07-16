## De lucht animeren

Animatie is niet alleen voor beweging. Laten we de lucht animeren zodat deze 's nachts donker wordt.

+ Voeg een animatie met de naam `lucht` toe aan je CSS:
    
        @keyframes lucht {
            0%
            100%
        }
        
    
    Merk op dat je deze keer de kleur van de lucht animeert, en niet de positie.

+ Voeg code toe aan je lucht, om het te vertellen om je nieuwe animatie te gebruiken:
    
        animation: lucht 10s;
        
    
    ![screenshot](images/sunrise-sky.png)

+ Klik op **Autorun** om je animatie te testen.