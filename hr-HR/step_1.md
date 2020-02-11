## Uvod

U ovom ćeš projektu naučiti kako koristiti CSS za stvaranje animiranog izlaska sunca.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Dodatne informacije za voditelje kluba

Ako želite ispisati ovaj projekt, molimo Vas da koristite [verziju koja je prilagođena za ispis](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Bilješke za voditelje kluba

## Uvod:

U ovom projektu djeca će naučiti kako animirati jednostavnu scenu pomoću CSS-a. Koristit će CSS-ovo @keyframes pravilo za animiranje različitih svojstava slika i div elemente.

## Online izvori

Preporučamo korištenje [trinketa](https://trinket.io/) za pisanje HTML-a i CSS-a online. Ovaj projekt sadrži sljedeće trinkete:

+ [Početni materijal projekta „Izlazak sunca”](http://jumpto.cc/web-sunrise)

Djeca također mogu koristiti ovaj prazni trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) za pisanje vlastitog HTML i CSS kôda ili mogu koristiti ovaj trinket predložak [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Također je uključen i trinket koji sadrži prijedlog rješenja izazova:

+ [Dovršeni projekt „Izlazak sunca”](https://trinket.io/html/abcc0284a3)

## Offline izvori

Ako želite, na ovom projektu možete [raditi i offline](../offline.html). Resursima projekta možete pristupiti klikom na poveznicu „Preuzimanje materijala projekta”. Na ovoj poveznici nalazi se mapa „Resursi projekta” koja uključuje resurse potrebne da bi djeca mogla raditi na ovom projektu izvanmrežno. Pobrinite se da svako dijete ima pristup kopiji ovih materijala. Ova mapa sadrži sljedeće datoteke:

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

Dovršenu verziju izazova projekta možete pronaći i u odjeljku „Resursi za volontere” koji sadrži:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Ishodi učenja

+ Postavljanje stila i animacija s CSS-om: 
    + Upoznavanje s `@ keyframes` pravilom za definiranje koraka u animaciji.
    + Poticanje upotrebe svojstava za određivanje veličine, oblika, položaja i boje elemenata na web stranici.

Ovaj projekt pokriva elemente iz sljedećih dijelova plana i programa [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Dizajniranje osnovnih 2D i 3D svojstava](https://www.raspberrypi.org/curriculum/design/creator).

## Izazovi

+ „Dijagonalna animacija” - uređivanje `@keyframe` svojstva animacije za upotrebu lijevo;
+ „Poboljšaj nebo” - dodavanje više keyframes svojstava i postavljanje pozadine;
+ „Više animacija” - animiranje više slika ili elemenata pomoću različitih CSS svojstava. 

## Često postavljana pitanja

+ Ovaj projekt koristi javascript biblioteku `prefixfree.js` kako bi se omogućila kompatibilnost animacija između preglednika. Ako se ta biblioteka ne koristi, djeca koja koriste starije preglednike morat će umjesto toga deklarirati animaciju za svoj preglednik. Na primjer:

    animation: sky 10s infinite;            // za sve novije preglednike
    -webkit-animation: sky 10s infinite;    // za Webkit preglednike (Chrome, Safari,...)
    -moz-animation: sky 10s infinite;       // za Mozilla preglednike
    -o-animation: sky 10s infinite;         // za Opera preglednike
    -ms-animation: sky 10s infinite;        // za Microsoft preglednike 
    

\--- /collapse \---

## \--- collapse \---

## title: Materijali projekta

## Resursi projekta

+ [.zip datoteku koja sadrži sve resurse projekta](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Online Trinket koji sadrži sve resurse projekta „Izlazak sunca”](http://jumpto.cc/web-sunrise)
+ [Online Trinket predložak](http://jumpto.cc/trinket-template)
+ [Prazan online Trinket](http://jumpto.cc/trinket-blank)
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

## Materijali za voditelje kluba

+ [.zip datoteku koja sadrži sve dovršene materijale projekta](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Dovršeni online Trinket projekt](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---