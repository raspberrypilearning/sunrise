## Die Sonne herstellen

Beginnen wir damit, ein Bild für die Sonne hinzuzufügen und es mit etwas CSS zu positionieren.

+ Öffne diesen Trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    Das Projekt sollte so aussehen:
    
    ![Screenshot](images/sunrise-starter.png)

+ Schauen Sie in die `body` Ihrer `index.html` Datei und Sie finden die `div` -Elemente für den Himmel und das Meer.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Ein Bild für die Sonne ist bereits in Ihrem Projekt enthalten.
    
    Fügen Sie das Bild in Ihre Sonne `div` einschließlich einer ID, damit Sie es stylen können:
    
    ![Screenshot](images/sunrise-sun-image.png)

+ Whoa, das Bild ist riesig. Gehen Sie zu `style.css` und fügen Sie das CSS hinzu, um die Bildhöhe festzulegen:
    
    ![screenshot](images/sunrise-sun-height.png)
    
    Beachten Sie, dass die Breite automatisch aktualisiert wird, um die Proportionen gleich zu halten.

+ Zuletzt fügen wir einen Code hinzu, um die Sonne zu positionieren:
    
    ![screenshot](images/sunrise-sun-position.png)