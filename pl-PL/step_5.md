## Niekończąca się animacja

Sprawmy, aby animacja powtarzała się bez końca.

+ Jeśli chcesz, żeby słońce wschodziło, a następnie zachodziło, dodaj więcej klatek kluczowych do swojej animacji:
    
        @keyframes sunrise {
            0%  
            33% 
            66% 
            100%
        }
        
    
    To oznacza, że na początku i na końcu animacji słońce znajduje się u dołu nieba, a na górze pomiędzy 33% a 66% czasu trwania animacji.

+ Teraz musisz jedynie dodać słowo `infinite` do animacji słońca, aby animacja powtarzała się w kółko:
    
    ![zrzut ekranu](images/sunrise-infinite.png)

+ Przetestuj swoją animację. Czy słońce wznosi się i opada?