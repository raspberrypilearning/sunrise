## Tworzenie animacji Słońca

Zacznijmy od dodania obrazka ze Słońcem i ustawienia go w odpowiednim miejscu z pomocą CSS.

+ Otwórz edytor: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    Projekt powinien wyglądać następująco:
    
    ![zrzut ekranu](images/sunrise-starter.png)

+ W znaczniku `body` jest plik `index. html`, w którym znajdziesz dwa elementy `div`, które będą ci potrzebne: niebo (ang. sky) oraz morze (ang. sea).
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Obrazek Słońca jest już dodany do projektu.
    
    Dodaj do elementu `div` nazwanego <0>sun</0> kod, który wyświetli obrazek. Nadaj mu identyfikator, aby za chwilę móc go stylizować:
    
    ![zrzut ekranu](images/sunrise-sun-image.png)

+ Oho, twój obrazek jest ogromny. Zajrzyj do pliku `style. css` i dodaj kod CSS, aby ustawić wysokość obrazka:
    
    ![screenshot](images/sunrise-sun-height.png)
    
    Zauważ, że szerokość obrazka jest ustawiana automatycznie, aby proporcje zostały zachowane.

+ Na koniec dodajmy kod, aby określić położenie Słońca:
    
    ![screenshot](images/sunrise-sun-position.png)