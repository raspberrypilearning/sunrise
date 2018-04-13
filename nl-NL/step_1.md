## Inleiding

In dit project leer je CSS te gebruiken om een ​​geanimeerde zonsopgang te creëren.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Aanvullende informatie voor clubleiders

Als je dit project wilt afdrukken, gebruik dan de [Printervriendelijke versie](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## titel: Clubleider notities

## Inleiding:

In dit project zullen kinderen leren hoe ze een eenvoudige scène kunnen animeren met behulp van CSS. Ze gebruiken de CSS @keyframes-regel om verschillende eigenschappen van afbeeldingen en divs te animeren.

## Online bronnen

We raden aan [trinket](https://trinket.io/) te gebruiken om HTML & CSS online te schrijven. Dit project bevat de volgende trinkets:

+ ['Zonsopkomst' startpunt](https://trinket.io/html/web-sunrise)

Kinderen kunnen ook gebruik maken van deze lege trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) om hun eigen HTML & CSS te schrijven, of ze kunnen deze sjabloontrinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template) gebruiken.

Er is ook een trinket met een voorbeeldoplossing voor de uitdagingen:

+ ['Zonsopkomst' klaar](https://trinket.io/html/abcc0284a3)

## Offline bronnen

Dit project kan indien gewenst [geheel offline ](../offline.html) voltooid worden. Je krijgt toegang tot de projectbronnen door op de koppeling 'Projectmaterialen downloaden' voor dit project te klikken. Deze koppeling bevat een map 'Projectresources' met bronnen die kinderen nodig hebben om dit project offline te voltooien. Zorg ervoor dat elk kind toegang heeft tot een kopie van deze bronnen. Deze map bevat de volgende bestanden:

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

Je kunt ook een voltooide versie van de uitdagingen van dit project vinden in de sectie 'Vrijwilligersbronnen', die bevat:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## leerdoelen

+ Styling en animatie met CSS: 
    + Introductie van `@keyframes` regel voor het definiëren van stappen in een animatie.
    + Versterking van het gebruik van eigenschappen om de grootte, vorm, positie en kleur van elementen op een webpagina te bepalen.

Dit project behandelt elementen uit de volgende onderdelen van het [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Ontwerp standaard 2D- en 3D-objecten](https://www.raspberrypi.org/curriculum/design/creator).

## Uitdagingen

+ "Diagonal animation" - bewerken van animatie `@keyframe` eigenschappen om left: te gebruiken;
+ "Verbeter de lucht" - voeg meer keyframes toe en stel achtergrond in :.
+ "Meer animatie" - animeer meer afbeeldingen of elementen met behulp van verschillende CSS-eigenschappen. 

## Veel Gestelde Vragen

+ Dit project maakt gebruik van de javascript `prefixfree.js` bibliotheek om animatiefunctionaliteit tussen browsers mogelijk te maken. Als deze bibliotheek niet wordt gebruikt, moeten kinderen die oudere browsers gebruiken in plaats daarvan een animatie voor hun browser declareren, bijvoorbeeld:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## titel: Projectmaterialen

## Project middelen

+ [.zip-bestand met alle projectbronnen](resources/sunrise-project-resources.zip)
+ [Online Trinket met alle projectbronnen van 'Sunrise'](http://jumpto.cc/web-sunrise)
+ [Online Trinket-sjabloon](http://jumpto.cc/trinket-template)
+ [Online lege Trinket](http://jumpto.cc/trinket-blank)
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

## Club leider middelen

+ [.zip-bestand met alle voltooide projectresources](resources/sunrise-volunteer-resources.zip)
+ [Online voltooid Trinket-project](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

\--- /collapse \---