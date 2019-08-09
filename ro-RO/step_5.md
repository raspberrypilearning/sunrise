## Animație infinită

Hai să facem această animație să se repete la infinit.

+ Dacă vrei ca soarele să răsară și apoi să apună, trebuie să adaugi mai multe keyframe la animația ta:
    
        @keyframes sunrise {
            0%  
            33% 
            66% 
            100%
        }
        
    
    Asta înseamnă că animația începe și se termină cu soarele în partea inferioară a cerului, și rămâne în partea de sus a cerului de la 33% până 66% din timpul de execuție al animației.

+ Acum doar trebuie să adaugi cuvântul `infinite` la animația `#sun` pentru a o face să ruleze continuu:
    
    ![captură de ecran](images/sunrise-infinite.png)

+ Testează animația. Soarele tău răsare și apune?