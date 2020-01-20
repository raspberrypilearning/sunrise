\--- challenge \---

## Aufgabe: Noch mehr Animationen

Können Sie ein anderes Bild animieren? Sie können die Position, Farbe, Form, Größe, Deckkraft (Durchsichtigkeit) oder alles andere animieren, was Sie sich vorstellen können. Ändern Sie auch die Dauer, für die Ihre Animationen ausgeführt werden.

Für jedes Element, das Sie animieren möchten, müssen Sie:

+ Fügen Sie es mit einer ID in Ihren HTML-Code ein
+ Fügen Sie einen Stil für die ID hinzu
+ Erstellen Sie eine @ keyframes-Regel
+ Verwenden Sie im Stil `Animation:` , um die Animation zu verwenden, die Sie mit @keyframes definiert haben 

Klicken Sie auf das Bildsymbol, um die im Projekt enthaltenen Bilder anzuzeigen:

![Screenshot](images/sunrise-images.png)

Sie können auch Ihre eigenen Bilder hochladen, wenn Sie möchten.

Vergessen Sie nicht, dass Sie sowohl Gegenstände ins Meer als auch in den Himmel werfen können:

![Screenshot](images/sunrise-boat.png)

Im Beispiel verwendet der Regenbogen die Deckkraft für einen Überblendungseffekt:

    @keyframes verblassen {
      0%  
      50% 
      66% 
      100%  
    }
    

Das Boot verwendet eine negative Startposition, sodass Sie diese für einen Teil der Animation nicht sehen können:

     @keyframes left-right {
      0%   
      100% 
    }
    

Und ergänze den CSS-Code in <0>style.css</0>, um das Bild zu positionieren.