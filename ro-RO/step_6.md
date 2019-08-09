## Animează cerul

O animație nu se referă doar la mișcare. Hai să animăm și cerul pe care se întunecă pe timpul nopții.

+ Adaugă o animație numită `sky` în codul CSS:
    
        @keyframes sky {
            0%
            100%
        }
        
    
    Ține minte faptul că acum animăm culoarea cerului, nu poziția acestuia.

+ Adaugă cod cerului, pentru a-i spune să utilizeze animația:
    
        animation: sky 10s;
        
    
    ![captură de ecran](images/sunrise-sky.png)

+ Apasă **Autorun** pentru a testa animația.