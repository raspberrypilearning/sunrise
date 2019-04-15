## Einleitung

In this project, you'll learn how to use CSS to create an animated sunrise.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Zusätzliche Information für Clubleiter

Falls du dieses Projekt ausdrucken musst, verwende bitte die [druckfreundliche Version](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Anmerkungen für Clubleiter

## Einleitung:

In this project, children will to learn how to animate a simple scene using CSS. They will use the CSS @keyframes rule to animate various properties of images and divs.

## Online-Ressourcen

We recommend using [trinket](https://trinket.io/) to write HTML & CSS online. This project contains the following trinkets:

+ ['Sunrise' starting point](https://trinket.io/html/web-sunrise)

Die Kinder können auch dieses leere Trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) verwenden um ihr eigenes HTML & CSS zu schreiben, oder sie können als Alternative dazu dieses Trinket als Vorlage verwenden [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Es gibt auch ein Trinket mit einem Lösungsbeispiel für die Herausforderungen:

+ ['Sunrise' Finished](https://trinket.io/html/abcc0284a3)

## Offline-Ressourcen

Dieses Projekt kann, falls gewünscht, auch [offline bearbeitet](../offline.html) werden. You can access the project resources by clicking the 'Download Project Materials' link for this project. This link contains a 'Project Resources' folder, which includes resources that children will need to complete this project offline. Stellen sie sicher, dass jedes Kind Zugriff auf eine Kopie dieser Ressourcen hat. This folder includes the following files:

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

Eine vollständige Version dieses Projekts mit den Herausforderungen finden Sie auch im Abschnitt "Ressourcen für Freiwillige Mitarbeiter" mit diesem Inhalt:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Lernziele

+ Styling and animation with CSS: 
    + Introducing `@keyframes` rule for defining steps in an animation.
    + Reinforcing the use of properties to define the size, shape, position and colour of elements on a webpage.

Dieses Projekt umfasst Elemente aus den folgenden Strängen des [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Entwurf von grundlegenden 2D- and 3D-Konstruktionen](https://www.raspberrypi.org/curriculum/design/creator).

## Herausforderungen

+ "Diagonal animation" - editing animation `@keyframe` properties to use left:;
+ "Improve the sky" - add more keyframes and setting background:.
+ "More animation" - animate more images or elements using a variety of CSS properties. 

## Häufig Gestellte Fragen

+ This project makes use of the javascript `prefixfree.js` library, to allow animation compatibility between browsers. If this library isn't used, then children using older browsers will instead need to declare an animation for their browser, for example:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title: Projektmaterial

## Projektressourcen

+ [.zip-Datei, die alle Projektressourcen enthält](resources/sunrise-project-resources.zip)
+ [Online Trinket containing all 'Sunrise' project resources](http://jumpto.cc/web-sunrise)
+ [Online Trinket-Vorlage](http://jumpto.cc/trinket-template)
+ [Leeres online-Trinket](http://jumpto.cc/trinket-blank)
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

## Ressourcen für Clubleiter

+ [.zip-Datei, die alle fertig gestellten Projektressourcen enthält](resources/sunrise-volunteer-resources.zip)
+ [Vollständiges Trinket-Projekt (online)](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

\--- /collapse \---