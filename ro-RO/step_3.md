## Animează răsăritul de soare

Pentru a anima răsăritul de soare, trebuie sa îți definești cum să se miște soarele și cât timp să îi ia până răsare.

Pentru a face acest lucru trebuie să definești o listă de **key frames**. Fiecare key frame definește proprietățile CSS ale unui element la un anumit moment dintr-o animație.

+ Mai întâi, trebuie să utilizezi `@keyframes` pentru a crea o nouă animație numită sunrise.
    
    Adaugă acest cod CSS la finalul fișierului `style.css`:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Acest cod ii spune soarelui unde să se poziționeze la începutul (`0%`) și la sfârșitul (`100%`) animației.
    
    Deoarece soarele este în inclus în elementul `div` al cerului, pozițiile `top` și `left` pe care le atribuim fac referire la dimensiunile cerului, adică `top: 100%` reprezintă partea inferioară a cerului, nu partea inferioară a paginii Web.

+ Acum că ai creat o animație `sunrise`, trebuie doar să îi spui soarelui să o utilizeze!
    
    Adaugă codul evidențiat la codul CSS al soarelui:
    
    ![captură de ecran](images/sunrise-sunrise.png)
    
    Acesta ii spune soarelui să fie animat timp de 10 secunde.

+ Pentru a rula din noua animația în Trinket, apasă **Autorun**.