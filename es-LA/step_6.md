## Animando el cielo

La animación no es solo para movimiento. Vamos a animar el cielo para que se oscurezca por la noche.

+ Añade una animación llamada `cielo` a tu CSS:
    
        @keyframes cielo {
            0%
            100%
        }
        
    
    Ten en cuenta que esta vez estás animando el color del cielo y no la posición.

+ Añade código a tu cielo para decirle que use tu nueva animación:
    
        animation: cielo 10s;
        
    
    ![captura de pantalla](images/sunrise-sky.png)

+ Haz clic en **Autorun** para probar tu animación.