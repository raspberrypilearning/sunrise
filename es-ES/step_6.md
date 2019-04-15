## Animando el Cielo

La animación no es solo para movimiento. Animemos el cielo para que se oscurezca por la noche.

+ Añade una animación llamada `sky` a tu CSS:
    
        @keyframes sky {
            0%
            100%
        }
        
    
    Date cuenta de que esta vez estás animando el color del cielo y no la posición.

+ Añade código a tu cielo para decirle que use tu nueva animación:
    
        animation: sky 10s;
        
    
    ![captura de pantalla](images/sunrise-sky.png)

+ Haz clic en **Autorun** para probar tu animación.