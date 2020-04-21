--- challenge ---

## Herausforderung: Noch mehr Animation

Kannst du ein weiteres Bild animieren? Du kannst die Position, Farbe, Form, Größe, Deckkraft (Transparenz) oder alles andere animieren, was du dir vorstellen kannst. Versuche auch die Dauer zu ändern, wie lange deine Animationen ausgeführt werden.

Für jedes Element, das du animieren möchtest, musst du:

+ Es mit einer ID in dein HTML einfügen
+ Einen Style für diese ID hinzufügen
+ Eine @keyframe-Regel erstellen
+ `animation:` im Style verwenden, um die Animation, die du mit @keyframes definiert hast, zu nutzen 

Klicke auf das Bildsymbol, um die Bilder angezeigt zu bekommen, die im Projekt enthalten sind:

![Bildschirmfoto](images/sunrise-images.png)

Wenn du willst, kannst du auch deine eigenen Bilder hochladen.

Vergiss nicht, du kannst Gegenstände sowohl ins Meer tun, als auch in den Himmel:

![Bildschirmfoto](images/sunrise-boat.png)

Im Beispiel verwendet der Regenbogen opacity (also Deckkraft) für einen Überblendeffekt:
```
    @keyframes fade {
      0%  
      50% 
      66% 
      100%  
    }
```    

Das Boot verwendet eine negative Start-Position, so dass man es am Anfang der Animation nicht sehen kann:
```
     @keyframes left-right {
      0%   
      100% 
    }
```    

--- /challenge ---


***
Dieses Projekt wurde von freiwilligen Helfern übersetzt:

Holger Wittmann

Tassilo Scherrer

Dank freiwilliger Helfer können wir Menschen auf der ganzen Welt die Möglichkeit geben, in ihrer eigenen Sprache zu lernen. Du kannst uns helfen, mehr Menschen zu erreichen, indem Du dich freiwillig zum Übersetzen meldest - weitere Informationen unter [rpf.io/translate](https://rpf.io/translate).