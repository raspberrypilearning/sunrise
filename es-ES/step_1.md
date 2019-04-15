## Introducción

En este proyecto, aprenderás cómo usar CSS para crear un amanecer animado.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Información adicional para los líderes de los clubes

Si necesitas imprimir este proyecto, usa la [versión para imprimir](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Notas del líder del club

## Introducción:

En este proyecto, los niños aprenderán cómo animar una escena simple usando CSS. Usarán las reglas @keyframes de CSS para animar varias propiedades de imágenes y divs.

## Recursos en línea

Recomendamos usar [trinket](https://trinket.io/) para escribir HTML & CSS en línea. Este proyecto contiene los trinkets siguientes:

+ ['Sunrise' punto de partida](https://trinket.io/html/web-sunrise)

Los niños también pueden hacer uso de este trinket en blanco [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) para escribir su propio HTML & CSS, o alternativamente pueden usar este trinket plantilla [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

También hay un trinket que contiene una solución de muestra para los desafíos:

+ ['Sunrise' terminado](https://trinket.io/html/abcc0284a3)

## Recursos sin conexión

Este proyecto se puede [completar sin conexión](../offline.html) si se prefiere. Se puede acceder a los recursos del proyecto haciendo clic en el enlace 'Descargar materiales del proyecto' para este proyecto. Este enlace contiene una carpeta de 'Recursos del proyecto', que incluye los recursos que los niños necesitarán para completar este proyecto sin conexión. Asegúrate de que cada niño tenga acceso a una copia de estos recursos. Esta carpeta incluye los siguientes archivos:

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

También puedes encontrar una versión completa de los desafíos de este proyecto en la sección 'Recursos para voluntarios', que contiene:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Objetivos de aprendizaje

+ Estilo y animación con CSS: 
    + Presentar las reglas `@keyframes` para definir los pasos en una animación.
    + Reforzar el uso de propiedades para definir el tamaño, forma, posición y color de los elementos de una página web.

Este proyecto incluye elementos de los siguientes aspectos del [currículo de digitalización de Raspberry Pi](http://rpf.io/curriculum):

+ [Diseño de elementos básicos en 2D y 3D](https://www.raspberrypi.org/curriculum/design/creator).

## Retos

+ "Animación diagonal" - editar las propiedades `@keyframe` de una animación que quedan por usar:;
+ "Mejorar el cielo" - añadir más keyframes y fondo de escena:.
+ "Más animación" - animar más imágenes o elementos usando una variedad de propiedades CSS. 

## Preguntas frecuentes

+ Este proyecto usa la librería de javascript `prefixfree.js`, para permitir la compatibilidad de las animaciones entre navegadores. Si esta librería no se usa, entonces niños usando navegadores antiguos necesitarán declarar la animación para su navegador, por ejemplo:

    animation: sky 10s infinite;            //for all newer browsers
    -webkit-animation: sky 10s infinite;    // For Webkit browsers(Chrome, Safari...)
    -moz-animation: sky 10s infinite;       // For Mozilla browsers
    -o-animation: sky 10s infinite;         // For Opera browsers
    -ms-animation: sky 10s infinite;        // For Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title: materiales del proyecto

## Recursos del proyecto

+ [archivo .zip que contiene todos los recursos del proyecto](resources/sunrise-project-resources.zip)
+ [Trinket en línea que contiene todos los recursos del proyecto 'Sunrise'](http://jumpto.cc/web-sunrise)
+ [Trinket plantilla en línea](http://jumpto.cc/trinket-template)
+ [Trinket en blanco en línea](http://jumpto.cc/trinket-blank)
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

## Recursos para el líder del club

+ [archivo .zip que contiene todos los recursos del proyecto](resources/sunrise-volunteer-resources.zip)
+ [Proyecto Trinket completado en línea](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](resources/sunrise-finished-rainbow.png)

\--- /collapse \---