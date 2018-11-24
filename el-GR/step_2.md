## Δημιουργία του ήλιου

Ας ξεκινήσουμε προσθέτοντας μια εικόνα για τον ήλιο και τοποθετώντας τη με χρήση κώδικα CSS.

+ Άνοιξε αυτό το trinket: <a href="http://jumpto.cc/web-sunrise" target="_blank">jumpto.cc/web-sunrise</a>.
    
    Το έργο πρέπει να μοιάζει έτσι:
    
    ![screenshot](images/sunrise-starter.png)

+ Δες μέσα στο `body` του αρχείου `index.html` και θα βρεις τις ετικέτες `div` για τον ουρανό και τη θάλασσα.
    
        <div id="sky">
        </div>
        
        <div id="sea">
        </div>
        

+ Στο έργο περιλαμβάνεται μια εικόνα για τον ήλιο.
    
    Πρόσθεσε την εικόνα ανάμεσα στην ετικέτα `div` για τον ήλιο συμπεριλαμβάνοντας και μια id ώστε να ρυθμίσεις το στυλ της:
    
    ![screenshot](images/sunrise-sun-image.png)

+ Whoa, the image is huge. Go to `style.css` and add the CSS to set the image height:
    
    ![screenshot](images/sunrise-sun-height.png)
    
    Note that the width is updated automatically to keep the proportions the same.

+ Finally, let's add some code to position the sun:
    
    ![screenshot](images/sunrise-sun-position.png)