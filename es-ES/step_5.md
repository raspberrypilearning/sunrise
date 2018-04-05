## Animación infinita

Hagamos una animación que se repita parasiempre.

+ Si quieres que el sol salga y luego se ponga,  solo necesitas agregar mas keyframes a tu animación:

    ```
    @keyframes sunrise {
        0%   {top:90%; left:0;}
        33%  {top:0; left:40%; }
        66%  {top:0; left:40%; }
        100% {top:90%; left:80%; }
    }
    ```
	Esto significa que la animación empieza y termina con el sol al fondo del cielo, y se queda en la parte superior desde el 33% hasta el 66% de la animación.
  
+ Ahora solo tienes que agregar la palabra `infinito` a la animación para hacerla un ciclo parasiempre:

    ![screenshot](images/sunrise-infinite.png)
  
+ Prueba tu animación. El sol se mantiene saliendo y se poniéndose? 




