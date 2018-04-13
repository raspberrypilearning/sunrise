## Uvod

U ovom ćete projektu saznati kako koristiti CSS za stvaranje animiranog izlaska sunca.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Dodatne informacije za voditelje kluba

Ako trebate ispisati ovaj projekt, molimo koristite [Verzija za ispis](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- kolaps \---

## naslov: Bilješke voditelja kluba

## Uvod:

U ovom projektu djeca će naučiti kako animirati jednostavnu scenu pomoću CSS-a. Oni će koristiti pravilo CSS @keyframes za animiranje različitih svojstava slika i divova.

## Online resursi

Preporučujemo upotrebu [triketa](https://trinket.io/) za pisanje HTML & CSS-a na mreži. Ovaj projekt sadrži sljedeće trikove:

+ [Polazna točka "Sunrise"](https://trinket.io/html/web-sunrise)

Djeca također mogu koristiti ovu praznu nakit [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) da napišu vlastiti HTML & CSS ili alternativno mogu koristiti ovaj predložak nakita [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Tu je i trikota s rješenjem uzorka izazovima:

+ ['Sunrise' Završeno](https://trinket.io/html/abcc0284a3)

## Offline resursi

Ovaj projekt može biti [završen offline](../offline.html) ako je željena. Možete pristupiti resursima projekta klikom na vezu "Preuzimanje projektnih materijala" za ovaj projekt. Ova veza sadrži mapu "Project Resources", koja uključuje resurse koje će djeca morati dovršiti ovaj projekt izvan mreže. Pazite da svako dijete ima pristup kopiji tih resursa. Ova mapa sadrži sljedeće datoteke:

+ predložak / index.html
+ predložak / prefix.js
+ predložak / style.css
+ izlazak / index.html
+ izlazak / style.css
+ izlazak / prefixfree.js
+ izlazak / boat.png
+ izlazak / cloud.png
+ izlazak / helicopter.png
+ izlazak / rainbow.png
+ izlazak / sun.png

Također možete naći dovršenu verziju izazova ovog projekta u odjeljku "Volonterski resursi", koji sadrži:

+ izlazak dovršenim / index.html
+ izlazak dovršenim / style.css
+ izlaska dovršenim / prefixfree.js
+ izlazak dovršenim / boat.png
+ izlazak dovršenim / sun.png
+ izlazak dovršenim / rainbow.png

## ciljevi učenja

+ Stiliranje i animacija s CSS-om: 
    + Predstavljamo pravilo `@ keyframes` za definiranje koraka u animaciji.
    + Pojačavanje upotrebe svojstava za određivanje veličine, oblika, položaja i boje elemenata na web stranici.

Ovaj projekt pokriva elemente iz sljedećih niza [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Oblikujte osnovne 2D i 3D snimke](https://www.raspberrypi.org/curriculum/design/creator).

## Izazovi

+ "Dijagonalna animacija" - uređivanje animacije `@keyframe` svojstva za upotrebu lijevo :;
+ "Poboljšajte nebo" - dodajte više ključnih okvira i postavljanje pozadine :.
+ "Više animacija" - animirati više slika ili elemenata pomoću različitih CSS svojstava. 

## Često postavljana pitanja

+ Ovaj projekt koristi biblioteku javascript `prefixfree.js` , kako bi se omogućila kompatibilnost animacija između preglednika. Ako se ta biblioteka ne koristi, djeca koja koriste starije preglednike umjesto toga trebaju objaviti animaciju za svoj preglednik, na primjer:

    animacija: nebo 10s beskonačno; // za sve novije preglednike -webkit-animacija: nebo 10s beskonačno; // Za web preglednike (Chrome, Safari ...) -moz-animacija: nebo 10s beskonačno; // Za Mozilla preglednike -o-animacija: nebo 10s beskonačno; // Za Opera preglednike -ms-animacija: nebo 10s beskonačno; // Za Microsoftove preglednike 
    

\--- /kolaps \---

## \--- kolaps \---

## Naslov: Projektni materijali

## Resursi projekta

+ [.zip datoteku koja sadrži sve resurse projekta](resources/sunrise-project-resources.zip)
+ [Online Trinket koji sadrži sve resurse projekta 'Sunrise'](http://jumpto.cc/web-sunrise)
+ [Predložak Online Trinket](http://jumpto.cc/trinket-template)
+ [Online prazno trinket](http://jumpto.cc/trinket-blank)
+ [predložak / index.html](resources/template-index.html)
+ [predložak / style.css](resources/template-style.css)
+ [Uvod / index.html](resources/intro-index.html)
+ [Uvod / style.css](resources/intro-style.css)
+ [izlazak / index.html](resources/sunrise-index.html)
+ [izlazak / style.css](resources/sunrise-style.css)
+ [izlazak / prefixfree.js](resources/sunrise-prefixfree.js)
+ [izlazak / sun.png](resources/sunrise-sun.png)
+ [izlazak / rainbow.png](resources/sunrise-rainbow.png)
+ [izlazak / cloud.png](resources/sunrise-cloud.png)
+ [izlazak / boat.png](resources/sunrise-boat.png)
+ [izlazak / helicopter.png](resources/sunrise-helicopter.png)

## Resursi za vođe kluba

+ [.zip datoteku koja sadrži sve dovršene resurse projekta](resources/sunrise-volunteer-resources.zip)
+ [Online završio projekt Trinket](https://trinket.io/html/abcc0284a3)
+ [izlazak dovršenim / index.html](resources/sunrise-finished-index.html)
+ [izlazak dovršenim / style.css](resources/sunrise-finished-style.css)
+ [izlaska dovršenim / prefixfree.js](resources/sunrise-finished-prefixfree.js)
+ [izlazak dovršenim / sun.png](resources/sunrise-finished-sun.png)
+ [izlazak dovršenim / boat.png](resources/sunrise-finished-boat.png)
+ [izlazak dovršenim / rainbow.png](resources/sunrise-finished-rainbow.png)

\--- /kolaps \---