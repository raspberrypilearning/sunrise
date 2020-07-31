--- challenge ---

## Desafío: Más animación

¿Puedes animar otra imagen? Puedes animar la posición, color, forma, tamaño, opacidad o cualquier otra cosa en la que puedas pensar. Intenta también cambiar la duración de tus animaciones.

Para cada objeto que quieras animar, necesitarás:

+ Incluirlo en tu HTML con un id
+ Añadir un estilo para el id
+ Crear una regla @keyframes
+ Usar `animation:` en el estilo para utilizar la animación que definiste con @keyframes 

Haz clic en el icono de la imagen para ver las imágenes que están incluidas en el proyecto:

![captura de pantalla](images/sunrise-images.png)

También puedes subir tus propias imágenes si así lo prefieres.

No olvides que puedes poner objetos tanto en el mar como en el cielo:

![captura de pantalla](images/sunrise-boat.png)

En el ejemplo el arco iris usa la opacidad para darle efecto de desvanecer:
```
    @keyframes fade {
      0%  
      50% 
      66% 
      100%  
    }
```    

El barco usa un punto de partida negativo de manera que puedas verlo durante una parte de la animación:
```
     @keyframes left-right {
      0%   
      100% 
    }
```    

--- /challenge ---


***
Este proyecto fue traducido por voluntarios:

Maria Pechenina

Angela Patricia Quiñones Pingo

Gracias a los voluntarios, podemos dar a las personas de todo el mundo la oportunidad de aprender en su propio idioma. Puedes ayudarnos a llegar a más personas ofreciéndote como voluntario para traducir. Más información en [rpf.io/translate](https://rpf.io/translate).