## Animando el amanecer

Para animar el amanecer, necesitas definir como se mueve el sol y el tiempo que se necesita para levantarse.

Para hacer esto define una lista de __key frames__. Cada key frame define las propiedades CSS de un elemento en un punto particular de la animación. 

+ Primer, necesitas usar `@keyframes` para crear una animación llamada amanecer (sunrise). 

    Agregar este codigo CSS al final de tu archivo `style.css`:

    ```
    @keyframes sunrise {
        0% {top: 90%;}
        100% {top: 0;}
    }
    ```

	Este código le dice al sol donde posicionarse al inicio (`0%`) y al final (`100%`) de la animación.

	Proque el sol está dentro del `div` sky, las posiciones `top`(arriba) y `left`(izquierda) estan dentro del sky(cielo), con `top: 100%` siendo el fondo del cielo, no de la página.

+ Ahora que has creado una animación de amancer `sunrise`, solo necesitas decierle al solo que la use! 

    Agregar el código destacado al CSS de tu sol:

    ![screenshot](images/sunrise-sunrise.png)

    Esto le dice al sol que tarde 10 segundos en animar el amancer.
	
+ Para volver a correr de nuevo el Trinket, has click en **Autorun**. 


