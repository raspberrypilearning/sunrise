## Wprowadzenie

Wykonując ten projekt dowiesz się, jak z pomocą CSS stworzyć animację wschodu Słońca.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Dodatkowe informacje dla prowadzących klub

Jeśli chcesz wydrukować ten projekt, użyj [wersji do druku](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Notatki dla liderów klubów

## Wprowadzenie:

Wykonując ten projekt, dzieci nauczą się animować prostą scenkę przy użyciu CSS. Będą wykorzystywały regułę @keyframes, aby animować obrazy oraz elementy div.

## Zasoby Online

Do pisania kodu HTML i CSS online rekomendujemy użytkowanie edytora [trinket](https://trinket.io/). Ten projekt zawiera następujące szablony:

+ [Punkt początkowy wschodu Słońca](http://jumpto.cc/web-sunrise)

Dzieci mogą również skorzystać z tego pustego wzorca [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank), aby napisać własny kod HTML i CSS, lub mogą skorzystać z wcześniej przygotowanego wzorca [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Dostępny jest także projekt zawierający przykładowe rozwiązania wyzwań:

+ [Ukończony wschód Słońca](https://trinket.io/html/abcc0284a3)

## Zasoby Offline

Ten projekt można także [wykonać offline](../offline.html). Materiały potrzebne do wykonania projektu dostępne są po kliknięciu linku "Materiały do projektu". Można znaleźć tam sekcję "Źródła", która zawiera zasoby potrzebne dzieciom do wykonania projektu w wersji offline. Upewnij się, że każde dziecko ma dostęp do własnej kopii zasobów. Ta sekcja zawiera następujące pliki:

+ template/index.html
+ template/prefix.js
+ template/style.css
+ sunrise/index.html
+ sunrise/style.css
+ sunrise/prefixfree.js
+ sunrise/boat.png
+ sunrise/cloud.png
+ sunrise/helicopter.png
+ sunrise/rainbow.png
+ sunrise/sun.png

Pełną wersję tego projektu można również znaleźć w sekcji "Zasoby dla wolontariuszy", która zawiera:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Cele dydaktyczne

+ Stylizacja i animacja w CSS: 
    + Wprowadzenie reguły `@keyframes` do definiowania kroków w animacji.
    + Wzmocnienie wykorzystania właściwości do określenia rozmiaru, kształtu, położenia i koloru elementów na stronie internetowej.

Projekt ten obejmuje następujące elementy [Cyfrowego programu nauczania Raspberry Pi](http://rpf.io/curriculum):

+ [ Projektuj podstawowe zasoby 2D i 3D](https://www.raspberrypi.org/curriculum/design/creator).

## Wyzwania

+ "Animacja po przekątnej" - edycja pozostałych właściwości animacji `@keyframes`:;
+ "Popraw niebo" - dodaj więcej klatek kluczowych i ustaw tło:.
+ "Więcej animacji" - animuj więcej obrazów lub elementów przy użyciu różnych właściwości CSS. 

## Najczęściej Zadawane Pytania

+ Ten projekt korzysta z biblioteki javascript `prefixfree.js`, aby umożliwić kompatybilność animacji między przeglądarkami. Jeśli ta biblioteka nie jest używana, wówczas dzieci korzystające ze starszych przeglądarek będą musiały zadeklarować animację dla swojej przeglądarki, na przykład:

    animacja: niebo 10s nieskończone; // dla wszystkich nowszych przeglądarek
    -webkit-animacja: niebo 10s nieskończone; // Dla przeglądarek Webkit (Chrome, Safari...)
    -moz-animacja: niebo 10s nieskończone; // Dla przeglądarek Mozilli
    -o-animacja: niebo 10s nieskończone; // Dla przeglądarek Opera
    -ms-animation: niebo 10s nieskończone; // Dla przeglądarek Microsoft 
    

\--- /collapse \---

## \--- collapse \---

## title: Materiały do projektu

## Zasoby

+ [Plik .zip zawierający wszystkie zasoby potrzebne do wykonania projektu](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Szablon startowy zawierający wszystkie zasoby potrzebne do realizacji projektu "Wschód Słońca"](http://jumpto.cc/web-sunrise)
+ [Pusty szablon Trinket](http://jumpto.cc/trinket-template)
+ [Pusty Trinket](http://jumpto.cc/trinket-blank)
+ [template/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-index.html)
+ [template/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-style.css)
+ [intro/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-index.html)
+ [intro/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-style.css)
+ [sunrise/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-index.html)
+ [sunrise/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-style.css)
+ [sunrise/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-prefixfree.js)
+ [sunrise/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-sun.png)
+ [sunrise/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-rainbow.png)
+ [sunrise/cloud.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-cloud.png)
+ [sunrise/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-boat.png)
+ [sunrise/helicopter.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-helicopter.png)

## Zasoby dla lidera klubu

+ [Plik .zip zawierający zasoby z ukończonym projektem](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Ukończony projekt "Wschód Słońca"](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---