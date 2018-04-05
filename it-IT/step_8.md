--- challenge ---
## Sfida: Altre animazioni 

Riesci ad animare un'altra immagine? Puoi animare la posizione, il colore, la forma, le dimensioni, l'opacità (la possibilità di vedere attraverso) o qualsiasi altra cosa ti venga in mente. Puoi anche provare a cambiare la quantità di tempo in cui le animazioni vengono eseguite.

Per ciascun elemento che vuoi animare, dovrai:

+ Includerlo nell'HTML con un id
+ Aggiungere uno stile per l'id
+ Creare una regola @keyframes
+ Usare `animation:` nello stile per usare l'animazione definita con @keyframes

Fare clic sull'icona dell'immagine per vedere le immagini incluse nel progetto:

![screenshot](images/sunrise-images.png)

Puoi anche caricare una tua immagine, se vuoi.

Non dimenticare che puoi inserire elementi nel mare e nel cielo:

![screenshot](images/sunrise-boat.png)

Nell'esempio, l'arcobaleno impiega l'opacità per un effetto sfumato:

```
@keyframes fade {
  0%   {opacity: 0;}
  50%  {opacity: 100;}
  66%  {opacity: 0;}
  100%   {opacity: 0;}
}
```

La barca utilizza una posizione di partenza negativa in modo che tu non possa vederla per una parte dell'animazione:

```
 @keyframes left-right {
  0%    {left:-50%;}
  100%  {left:200%;}
}
```




--- /challenge ---