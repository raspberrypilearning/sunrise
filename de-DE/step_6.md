## Den Himmel animieren

Animation ist nicht nur für Bewegung. Lass uns den Himmel animieren, damit er nachts dunkel wird.

+ Füge eine Animation mit dem Namen `sky` zu deinem CSS hinzu:
    ```
        @keyframes sky {
            0%
            100%
        }
    ```    
    
    Beachte, dass du diesmal die Farbe des Himmels animierst und nicht die Position.

+ Füge Code zu deinem Himmel hinzu, um ihm zu sagen dass er die neue Animation verwenden soll:
    ```
        animation: sky 10s;
    ```    
    
    ![Bildschirmfoto](images/sunrise-sky.png)

+ Klicke **Autorun**, um die Animation zu testen.