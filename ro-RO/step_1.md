## Introducere

În acest proiect, vei învăța cum se utilizează limbajul CSS pentru a crea un răsărit de soare animat.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Informații suplimentare pentru liderii cluburilor

Dacă vrei să printezi acest proiect, folosește [Versiunea printabilă](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Note pentru conducătorul clubului

## Introducere:

În acest proiect, copiii vor învăța cum să creeze scene simple animate utilizând CSS. Ei vor folosi reguli CSS @keyframes pentru a anima diferite proprietăți ale imaginilor sau ale componentelor div.

## Resurse online

Recomandăm utilizarea [trinket](https://trinket.io/) pentru a scrie HTML & CSS online. Acest proiect conține următoarele Trinket-uri:

+ [Punctul de pornire pentru „Răsărit de soare”](http://jumpto.cc/web-sunrise)

Copiii pot, de asemenea, utiliza acest trinket gol [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) pentru a scrie propriul lor cod HTML & CSS, sau pot folosi acest șablon trinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

De asemenea, există un trinket care conține soluția finală a provocărilor:

+ [„Răsărit de soare” completat](https://trinket.io/html/abcc0284a3)

## Resurse offline

Acest proiect poate fi [completat offline](../offline.html) dacă dorești. Poți accesa resursele proiectului dând click pe link-ul „Materialele proiectului” pentru acest proiect. Acest link conține o secțiune „Resursele proiectului” care include resurse de care copiii vor avea nevoie pentru a completa acest proiect offline. Asigură-te că fiecare copil are acces la o copie a acestor resurse. Această secțiune include următoarele fișiere:

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

De asemenea, poți găsi o versiune completă a provocărilor din acest proiect în secțiunea „Resursele voluntarilor”, care conține:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Obiectivele exercitiului

+ Stilizarea și animarea cu CSS: 
    + Introducerea regulilor `@keyframes` pentru definirea pașilor într-o animație.
    + Consolidarea cunoștințelor în utilizarea proprietățile elementelor pentru a defini mărimea, forma, poziția sau culoarea acestora în cadrul unei pagini web.

Acest proiect acopera elemente din urmatoarele domenii [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Proiectează elemente grafice 2D și 3D de bază](https://www.raspberrypi.org/curriculum/design/creator).

## Provocări

+ „Animarea în diagonală” - editează proprietățile `@keyframe` ale animației pentru a utiliza left:;
+ „Perfecționează cerul” - adaugă mai multe proprietăți keyframe și setează background:.
+ „Mai multă animație” - animează mai multe imagini sau elemente utilizând o varietate de proprietăți CSS. 

## Întrebări frecvente

+ Acest proiect utilizează biblioteca javascript `prefixfree.js`, pentru a asigura compatibilitea între browser-e. Dacă această bibliotecă nu este utilizată, atunci copii care utilizează versiuni vechi de browser-e trebuie să utilizeze linia de cod care crează animația pentru browser-ul lor, de exemplu:

    animation: sky 10s infinite;            //pentru toate browser-ele noi
    -webkit-animation: sky 10s infinite;    // pentru browser-e Webkit (Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // pentru browser-e Mozilla
    -o-animation: sky 10s infinite;         // pentru browser-e Opera
    -ms-animation: sky 10s infinite;        // pentru browser-e Microsoft 
    

\--- /collapse \---

## \--- collapse \---

## title: Materialele proiectului

## Resursele proiectului

+ [fișier .zip care conține toate resursele proiectului](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Trinket online care conține toate resursele proiectului „Răsărit de soare”](http://jumpto.cc/web-sunrise)
+ [Șablon Trinket online](http://jumpto.cc/trinket-template)
+ [Trinket online gol](http://jumpto.cc/trinket-blank)
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

## Resurse pentru conducătorul clubului

+ [fișier .zip care conține toate resursele proiectului, completate](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Proiect Trinket online, completat](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---