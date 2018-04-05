## Animando el Cielo

La animación no solo es acerca del movimiento. Vamos a animar el cielo para que se oscurezca en la noche.

+ Agregar una animación llamada `sky` a tu CSS:

    ```
    @keyframes sky {
        0% {background: black}
        100% {background: lightblue}
    }
    ```
	Nota que esta vez estás animando el color del cielo, y no la posición.

+ Agregar el código a tu cielo, para decirle que use la nueva animación:

    ```
    animation: sky 10s;
    ```

    ![screenshot](images/sunrise-sky.png)

+ Dar Click en **Autorun** para probar tu animación. 


