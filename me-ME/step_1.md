## Uvod

U ovom projektu naučićeš kako da koristiš CSS za kreiranje animiranog izlaska sunca.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Dodatne informacije za vođe kluba

Ukoliko je potrebno da odštampate ovaj projekat, koristite [Verziju za štampu](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Bilješke za vođe kluba

## Uvod:

U ovom projektu djeca će naučiti kako da animiraju jednostavnu scenu koristeći CSS. Koristiće CSS @keyframes pravilo da animiraju različita svojstva slika i elemenata div.

## Online izvori

Za pisanje HTML-a i CSS-a online preporučujemo da koristite [trinket](https://trinket.io/). Ovaj projekat sadrži sljedeće trinkete:

+ [Početak projekta 'Izlazak sunca'](https://trinket.io/html/web-sunrise)

Za pisanje sopstvenog HTML-a i CSS-a, djeca takođe mogu da koriste ovaj prazan trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) ili da koriste ovaj trinket šablon [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Takođe postoji trinket koji sadrži primjer rješenja izazova:

+ [Završen projekat 'Izlazak sunca'](https://trinket.io/html/abcc0284a3)

## Offline izvori

Ako želite, ovaj projekat može biti [izrađen offline](../offline.html). Izvorima projekta možete pristupiti klikom na link projekta 'Projektni materijali'. Navedeni link sadrži odjeljak 'Izvori projekta' u kojem se nalaze izvori koji će djeci biti potrebni kako bi izradila ovaj projekat offline. Obezbijedite da svako dijete ima pristup kopiji ovih izvora. Odjeljak sadrži sljedeće datoteke:

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

Takođe, završenu verziju izazova ovoga projekta možete naći u odjeljku 'Izvori za volontere' koji sadrži:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Ciljevi učenja

+ Stilizovanje i animacija sa CSS-om: 
    + Upoznavanje sa ` @keyframes` pravilom za definisanje koraka u animaciji.
    + Utvrđivanje znanja o upotrebi svojstava za određivanje veličine, oblika, pozicije i boje elemenata na veb-stranici.

Ovim projektom obuhvaćeni su elementi iz sljedećih dijelova [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Dizajniranje osnovnih 2D i 3D elemenata](https://www.raspberrypi.org/curriculum/design/creator).

## Izazovi

+ ''Dijagonalna animacija'' - uređivanje `@keyframe` svojstava animacije za korišćenje left:;
+ ''Poboljšaj nebo'' - dodavanje više ključnih kadrova (keyframes) i postavljanje pozadine (background:).
+ ''Više animacije'' - animacija više slika ili elemenata koristeći različita CSS svojstva. 

## Često postavljana pitanja

+ Ovaj projekat koristi javascript biblioteku `prefixfree.js`, kako bi bila omogućena kompatibilnost animacija između pregledača. Ako se ova biblioteka ne koristi, djeca koja koriste starije pregledače treba da deklarišu animaciju za svoj pregledač, na primjer:

    animation: sky 10s infinite;            // Za sve novije pregledače
    -webkit-animation: sky 10s infinite;    // Za Webkit pregledače (Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // Za Mozilla pregledače
    -o-animation: sky 10s infinite;         // Za Opera pregledače
    -ms-animation: sky 10s infinite;        // Za Microsoft pregledače 
    

\--- /collapse \---

## \--- collapse \---

## title: Projektni materijali

## Izvori projekta

+ [.zip datoteka koja sadrži sve izvore projekta](resources/sunrise-project-resources.zip)
+ [Online Trinket koji sadrži sve izvore projekta 'Izlazak sunca'](http://jumpto.cc/web-sunrise)
+ [Online Trinket šablon](http://jumpto.cc/trinket-template)
+ [Online prazan Trinket](http://jumpto.cc/trinket-blank)
+ [template/index.html](resources/template-index.html)
+ [template/style.css](resources/template-style.css)
+ [intro/index.html](resources/intro-index.html)
+ [intro/style.css](resources/intro-style.css)
+ [sunrise/index.html](resources/sunrise-index.html)
+ [sunrise/style.css](resources/sunrise-style.css)
+ [sunrise/prefixfree.js](resources/sunrise-prefixfree.js)
+ [sunrise/sun.png](resources/sunrise-sun.png)
+ [sunrise/rainbow.png](resources/sunrise-rainbow.png)
+ [sunrise/cloud.png](resources/sunrise-cloud.png)
+ [sunrise/boat.png](resources/sunrise-boat.png)
+ [sunrise/helicopter.png](resources/sunrise-helicopter.png)

## Izvori za vođe kluba

+ [.zip datoteka koja sadrži sve završene izvore projekta](resources/sunrise-volunteer-resources.zip)
+ [Završen Trinket projekat online](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

\--- /collapse \---