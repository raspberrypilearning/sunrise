## Creando el Sol

Empecemos agregando una imagen del sol y posicionándolo con CSS.

+ Arbir este trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>. Si estas viendo esto online, también puedes usar la version incrustada de este trinket de abajo.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/5085f92143" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

+ Ver dentro del `body` de tu archivo `index.html` y encontrarás los elementos `div` para el cielo y el mar.

    ```
    <div id="sky">
    </div>
    
    <div id="sea">
    </div>
    ```
+ Se ha incluido una imagen del sol en este proyecto.. 

	Agregar la imagen del sol dentro del `div` incluyendo un id para que puedas aplicarle estilo.:

    ![screenshot](images/sunrise-sun-image.png)

+ Huy, la imagen es enorme. Ve a `style.css` y agrega el CSS para aplicarle altura a la imagen:

    ![screenshot](images/sunrise-sun-height.png)

	Nota que el ancho es actualizado automáticament para mantener las proporciones iguales.

+ Finalmente, agreguemos algo de codigo para posicionar el sol:

    ![screenshot](images/sunrise-sun-position.png)



