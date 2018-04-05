--- challenge ---
## Reto: Mas animación

Puedes animar otra imágen? Puedes animar su posición, color, forma, tamaño y opacidad(ver atravez de ella) o  cualquier otra cosa que se te ocurra, Prueba también cambiar la duración de tus animaciones.

Para cada elemento que quieras animar, necesitaras:

+ Incluirlo en tu HTML con un Id
+ Agregar un estilo (style) para ese ID
+ crear una regla @keyframes
+ Usar `animation:` en el stilo para usar la animaci que definiste con @keyframes 

Dar click en ícono para ver las imagenes que son incluidas en tu proyecto:

![screenshot](images/sunrise-images.png)

Puedes también subir tus propias imágenes si gustas.

No olvides que puedes poner elementos en el mar asi como en el cielo:

![screenshot](images/sunrise-boat.png)


En el ejemplo el arcoiris usa opacity(opacidad) para dar un efecto de desvanecimiento:

```
@keyframes fade {
  0%   {opacity: 0;}
  50%  {opacity: 100;}
  66%  {opacity: 0;}
  100%   {opacity: 0;}
}
```

El bote usa una posición de inicion negativa para que no lo puedas ver por una parate de la animación:

```
 @keyframes left-right {
  0%    {left:-50%;}
  100%  {left:200%;}
}
```



--- /challenge ---