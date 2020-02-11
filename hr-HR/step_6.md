## Animiranje neba

Animacija nije samo za kretanje. Animirajmo nebo da noću bude mračno.

+ Dodaj animaciju `sky (nebo)` u svoj CSS:
```    
        @keyframes sky {0% 100%}
```        
    
    Primijeti da ovaj put animiraš boju neba, a ne položaj.

+ Dodaj kôd svome nebu kojim ćeš mu reći da upotrijebi tvoju novu animaciju:
```    
        animation: sky 10s;
```        
    
    ![screenshot](images/sunrise-sky.png)

+ Klikni **Autorun** da biste testiraš svoju animaciju.