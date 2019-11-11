\--- challenge \---

## Reto: Más animación

¿Puedes animar otra imagen? Puedes animar la posición, color, forma, tamaño, opacidad o cualquier otra cosa en la que puedas pensar. También intenta cambiar el tiempo que duran tus animaciones.

Para cada objeto que quieras animar, necesitarás:

+ Incluirlo en tu HTML con un id
+ Añade un estilo para el id
+ Crea una regla @keyframes
+ Usa `animation:` en el estilo para usar la animación que definiste con @keyframes 

Haz clic en el icono de la imagen para ver las imágenes que están incluidas en el proyecto:

![screenshot](images/sunrise-images.png)

También puedes subir tus propias imágenes si así lo prefieres.

No olvides que puedes poner objetos tanto en el mar como en el cielo:

![screenshot](images/sunrise-boat.png)

En el ejemplo el arco iris usa la opacidad para un efecto de desvanecimiento:

    @keyframes fade {
      0%  
      50% 
      66% 
      100%  
    }
    

El barco usa un punto de partida negativo de manera que puedas verlo durante una parte de la animación:

     @keyframes left-right {
      0%   
      100% 
    }
    

\--- /challenge \---