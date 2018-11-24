## Απεικόνιση της ανατολής του ήλιου

Για να απεικονίσεις την ανατολή του ηλίου, πρέπει να καθορίσεις πως κινείται ο ήλιος και πόσο χρόνο χρειάζεται για να ανατείλει.

Για αυτό πρέπει να ορίσεις μια λίστα από **key frames**. Κάθε key frame ορίζει τις CSS ιδιότητες ενός στοιχείου σε ένα συγκεκριμένο σημείο της απεικόνισης.

+ Πρώτα, πρέπει να χρησιμοποιήσεις το `@keyframes` για να δημιουργήσεις μια νέα απεικόνιση με όνομα sunrise.
    
    Πρόσθεσε αυτόν τον κώδικα CSS στο τέλος του αρχείου `style.css`:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    Αυτός ο κώδικας ορίζει σε ποια θέση θα εμφανιστεί ο ήλιος στην αρχή (`0%`) και στο τέλος (`100%`) της απεικόνισης.
    
    Because the sun is inside the sky `div`, the `top` and `left` positions you give are within to the sky, with `top: 100%` being the bottom of the sky, and not the bottom of the webpage.

+ Now that you have created a `sunrise` animation, you just need to tell your sun to use it!
    
    Add the highlighted code to your sun's CSS:
    
    ![screenshot](images/sunrise-sunrise.png)
    
    This tells the sun to spend 10 seconds animating a sunrise.

+ To run the animation again in Trinket, just click **Autorun**.