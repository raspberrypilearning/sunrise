## Unendliche Animation

Lass es uns so einstellen, dass sich die Animation unendlich wiederholt.

+ Wenn du willst, dass die Sonne auf- und wieder untergeht, brauchst du einfach nur weitere „Keyframes“ zu deiner Animation hinzuzufügen:

    ```
    @keyframes Sonnenaufgang {
        0%   {oben:90%; links:0;}
        33%  {oben:0; links:40%; }
        66%  {oben:0; links:40%; }
        100% {oben:90%; links:80%; }
    }
    ```

    Das bedeutet, dass die Animation mit der Sonne im unteren Teil des Himmels beginnt und dort auch endet und von 33% bis 66% der Animation oben bleibt.

+ Jetzt musst du nur noch das Wort `infinite` (unendlich) zur `#sun` (Sonne) Animation hinzufügen, damit sie für immer in einer Schleife ist:

    ![screenshot](images/sunrise-infinite.png)

+ Teste deine Animation. Geht die Sonne immer wieder erneut auf und unter? 




