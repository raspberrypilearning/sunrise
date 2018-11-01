## Tworzenie animacji nieba

Animacja nie polega jedynie na ruchu. Stwórzmy animację nieba, tak, aby robiło się ciemniejsze w nocy.

+ Dodaj animację o nazwie `sky` do swojego kodu CSS:
    
        @keyframes sky {
            0%
            100%
        }
        
    
    Zauważ, że tym razem tworzysz animację koloru nieba, a nie jego pozycji.

+ Dodaj poniższy kod do nieba, aby zaczęło używać nowej animacji:
    
        animation: sky 10s;
        
    
    ![zrzut ekranu](images/sunrise-sky.png)

+ Kliknij **Run** (Uruchom), aby zobaczyć, jak działa.