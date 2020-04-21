## Einleitung

In diesem Projekt wirst du lernen, wie man mit CSS einen animierten Sonnenaufgang erstellt.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Zusätzliche Information für Clubleiter

Falls du dieses Projekt ausdrucken musst, verwende bitte die [druckfreundliche Version](https://projects.raspberrypi.org/de-DE/projects/sunrise/print).

--- collapse ---
---
title: Anmerkungen für Clubleiter
---

## Einleitung:

In diesem Projekt lernen die Kinder, wie sie mit CSS eine einfache Szene animieren. Sie werden die CSS @keyframes Regel verwenden, um verschiedene Eigenschaften von Bildern und Divs zu animieren.

## Online-Ressourcen

Wir empfehlen, [trinket](https://trinket.io/) zu verwenden um HTML & CSS online zu schreiben. Dieses Projekt enthält die folgenden trinkets:

+ [Ausgangspunkt 'Sunrise'](http://jumpto.cc/web-sunrise)

Die Kinder können auch dieses leere Trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) verwenden um ihr eigenes HTML & CSS zu schreiben, oder sie können als Alternative dazu dieses Trinket als Vorlage verwenden [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Es gibt auch ein Trinket mit einem Lösungsbeispiel für die Herausforderungen:

+ ['Sunrise' fertig](https://trinket.io/html/abcc0284a3)

## Offline-Ressourcen

Dieses Projekt kann, falls gewünscht, auch [offline bearbeitet](../offline.html) werden. Sie können auf die Projektressourcen zugreifen, indem Sie auf den Link "Projektmaterialien herunterladen" für dieses Projekt klicken. Dieser Link enthält einen Ordner "Projektressourcen", der Ressourcen enthält, die Kinder benötigen, um dieses Projekt offline abzuschließen. Stellen sie sicher, dass jedes Kind Zugriff auf eine Kopie dieser Ressourcen hat. Dieser Ordner enthält die folgenden Dateien:

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

+ Styling und Animation mit CSS: 
    + Einführung der `@keyframes` Regel zum Definieren von Schritten in einer Animation.
    + Verstärkte Verwendung von Eigenschaften zum Definieren der Größe, Form, Position und Farbe von Elementen auf einer Webseite.

Dieses Projekt umfasst Elemente aus den folgenden Strängen des [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Entwurf von grundlegenden 2D- and 3D-Konstruktionen](https://www.raspberrypi.org/curriculum/design/creator).

## Herausforderungen

+ "Diagonale Animation" - `@keyframe` Eigenschaften einer Animation bearbeiten um "left:;" zu verwenden;
+ "Verbessere den Himmel" - füge weitere Keyframes hinzu und setze einen Hintergrund (background:).
+ "Mehr Animationen" - animiere mehr Bilder oder Elemente mit einer Vielzahl von CSS-Eigenschaften. 

## Häufig Gestellte Fragen

+ In diesem Projekt wird die JavaScript-Bibliothek `prefixfree.js` verwendet, um die Animationskompatibilität zwischen Browsern zu ermöglichen. Wenn diese Bibliothek nicht verwendet wird, müssen Kinder, die ältere Browser verwenden, stattdessen eine Animation für ihren Browser deklarieren. Zum Beispiel:

    animation: sky 10s infinite; // für alle neueren browser
    -webkit-animation: sky 10s infinite; // Für Webkit-Browser (Chrome, Safari...)
    -moz-animation: sky 10s infinite; // Für Mozilla-Browser
    -o-animation: sky 10s infinite; // Für Opera-Browser
    -ms-Animation: sky 10s infinite; // Für Microsoft Browser 
    

--- /collapse ---

--- collapse ---
---
title: Projektmaterial
---

## Projektressourcen

+ [.zip-Datei, die alle Projektressourcen enthält](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-project-resources.zip)
+ [Online-Trinket mit allen Projektressourcen von 'Sonnenaufgang'](http://jumpto.cc/web-sunrise)
+ [Online Trinket-Vorlage](http://jumpto.cc/trinket-template)
+ [Leeres Online-Trinket](http://jumpto.cc/trinket-blank)
+ [template/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/template-index.html)
+ [template/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/template-style.css)
+ [intro/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/intro-index.html)
+ [intro/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/intro-style.css)
+ [sunrise/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-index.html)
+ [sunrise/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-style.css)
+ [sunrise/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-prefixfree.js)
+ [sunrise/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-sun.png)
+ [sunrise/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-rainbow.png)
+ [sunrise/cloud.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-cloud.png)
+ [sunrise/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-boat.png)
+ [sunrise/helicopter.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-helicopter.png)

## Ressourcen für Clubleiter

+ [.zip-Datei, die alle fertig gestellten Projektressourcen enthält](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-volunteer-resources.zip)
+ [Vollständiges Trinket-Projekt (online)](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/de-DE/resources/sunrise-finished-rainbow.png)

--- /collapse ---