## Introducción

En este proyecto, aprenderás a usar CSS para crear un amanecer animado.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Información adicional para los líderes del club

Si necesitas imprimir este proyecto, usa la [versión para imprimir](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Notas para el líder del club

## Introducción:

En este proyecto, los niños y niñas aprenderán como animar una escena simple usando CSS. Usarán las reglas @keyframes de CSS para animar varias propiedades de imágenes y divs.

## Recursos en línea

Recomendamos usar [trinket](https://trinket.io/) para programar en HTML y CSS en línea. Este proyecto contiene los siguientes trinkets:

+ ["Amanecer" punto de partida](http://jumpto.cc/web-sunrise)

También pueden hacer uso de este trinket en blanco [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) para escribir su propio HTML & CSS o alternativamente pueden usar esta plantilla de trinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Además, hay un trinket que contiene una solución de muestra para los retos:

+ ["Amanecer" terminado](https://trinket.io/html/abcc0284a3)

## Recursos sin conexión

Si prefieres, este proyecto se puede [completar offline](../offline.html). Se puede acceder a los recursos del proyecto haciendo clic en el enlace "Descargar materiales del proyecto". Este enlace contiene una carpeta de "Recursos del proyecto", que incluye los recursos que los niños necesitarán para completar el proyecto sin conexión. Asegúrate de que cada niño tenga acceso a una copia de estos recursos. Esta carpeta incluye los siguientes archivos:

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

También puedes encontrar una versión completa de los desafíos de este proyecto en la sección "Recursos para voluntarios", que contiene:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Objetivos del aprendizaje

+ Estilo y animación con CSS: 
    + Introducir las reglas `@keyframes` para definir los pasos en una animación.
    + Reforzar el uso de propiedades para definir el tamaño, forma, posición y color de los elementos de una página web.

Este proyecto incluye elementos de los siguientes aspectos del [Currículo de creación digital de Raspberry Pi](http://rpf.io/curriculum):

+ [Diseño de elementos básicos en 2D y 3D](https://www.raspberrypi.org/curriculum/design/creator).

## Desafíos

+ "Animación diagonal" - editar las propiedades de animación `@keyframe` para usar la propiedad left:;
+ "Mejorar el cielo" - añadir más keyframes y ajustar background:.
+ "Más animación" - añadir mayor animación a imágenes o elementos usando una variedad de propiedades CSS. 

## Preguntas frecuentes

+ Este proyecto usa la librería de javascript `prefixfree.js`, para permitir la compatibilidad de las animaciones entre navegadores web. Si esta librería no se usa, entonces los niños y niñas que usen navegadores antiguos necesitarán declarar la animación para su navegador, por ejemplo:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title: Materiales del proyecto

## Recursos del proyecto

+ [Archivo .zip que contiene todos los recursos del proyecto](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Trinket en línea que contiene todos los recursos del proyecto "Amanecer"](http://jumpto.cc/web-sunrise)
+ [Plantilla de Trinket en línea](http://jumpto.cc/trinket-template)
+ [Trinket en blanco en línea](http://jumpto.cc/trinket-blank)
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

## Recursos del líder del club

+ [Archivo .zip que contiene todos los recursos del proyecto](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Proyecto Trinket completado en línea](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---