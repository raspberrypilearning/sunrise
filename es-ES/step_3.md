## Animando el amanecer

Para animar tu amanecer, necesitas definir cómo se mueve el sol y cuánto tarda en subir.

Para hacer esto tienes que definir una lista de **key frames**. Cada key frame define las propiedades CSS de un elemento en un punto particular de la animación.

+ Primero, necesitas usar `@keyframes` para crear una nueva animación llamada amanecer.
    
    Añade este código CSS al final de tu archivo `style.css`:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Este código le dice al sol dónde colocarse al comienzo (`0%`) y al final (`100%`) de la animación.
    
    Como el sol está dentro del `div` del cielo, las posiciones `top` y `left` que le das son relativas al cielo, con `top: 100%` siendo el final del cielo y no de la página web.

+ Ahora que has creado una animación de un `amanecer`, ¡solo necesitas decirle a tu sol que la use!
    
    Añade el código resaltado al CSS de tu sol:
    
    ![captura de pantalla](images/sunrise-sunrise.png)
    
    Esto le dice al sol que pase 10 segundos animando un amanecer.

+ Para volver a ejecutar la animación en Trinket, solo tienes que hacer clic en **Autorun**.