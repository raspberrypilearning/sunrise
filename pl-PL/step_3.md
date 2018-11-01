## Animacja wschodzącego słońca

Aby stworzyć animację słońca, musisz najpierw określić, jak słońce porusza się po niebie i ile czasu zajmuje jego wschód.

Żeby to zrobić, musisz zdefiniować listę **key frames**. Każda klatka definiuje właściwości CSS danego elementu w konkretnym momencie animacji.

+ Na początku musisz użyć `@keyframes`, by zdefiniować nową animację nazwaną “sunrise” (ang. wschód słońca).
    
    Dodaj ten kod CSS na końcu swojego pliku `style.css`:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Ten kod mówi słońcu, w którym miejscu ma się znajdować na początku (`0%`) i przy końcu (`100%`) animacji.
    
    Ponieważ słońce jest wewnątrz `div` nieba, pozycje, które nadajesz (`top` i `left`) znajdują się w zakresie nieba, gdzie `top: 100%` to spód nieba, a nie strony internetowej.

+ Teraz, skoro twoja animacja `sunrise` jest gotowa, musisz powiedzieć swojemu słońcu, aby z niej skorzystało!
    
    Dodaj podkreślony fragment kodu do kodu CSS słońca:
    
    ![zrzut ekranu](images/sunrise-sunrise.png)
    
    Dzięki temu słońce wie, że animacja wschodu powinna trwać 10 sekund.

+ Aby uruchomić animację po raz kolejny w edytorze, kliknij **Autorun**.