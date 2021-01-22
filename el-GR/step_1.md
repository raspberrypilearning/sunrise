## Εισαγωγή

Σε αυτό το έργο, θα μάθεις να χρησιμοποιείς CSS για να δημιουργήσεις μια απεικόνιση της ανατολής του ήλιου.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Πρόσθετες πληροφορίες για τους συντονιστές των ομάδων

Αν χρειαστεί να εκτυπώσεις αυτό το έργο, χρησιμοποίησε την [εκτυπώσιμη έκδοση](https://projects.raspberrypi.org/en/projects/sunrise/print).

## \--- collapse \---

## title: Σημειώσεις συντονιστή ομάδας

## Εισαγωγή:

Σε αυτό το έργο, τα παιδιά θα μάθουν να απεικονίζουν μια απλή κινούμενη σκηνή χρησιμοποιώντας κώδικα CSS. Θα χρησιμοποιήσουν τον CSS @keyframes για να μεταβάλλουν διάφορες ιδιότητες των εικόνων και ενοτήτων (divs).

## Online Πόροι

Συνιστούμε να χρησιμοποιήσετε την εφαρμογή [trinket](https://trinket.io/) για να γράψετε HTML & CSS online. Το έργο αυτό περιλαμβάνει τα ακόλουθα Trinkets:

+ ['Ανατολή του ήλιου' αρχικό](http://jumpto.cc/web-sunrise)

Τα παιδιά μπορούν επίσης να χρησιμοποιήσουν το κενό trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) για να γράψουν δικό τους κώδικα HTML & CSS, ή να βασιστούν σε αυτό το πρότυπο trinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

Υπάρχει επίσης ένα trinket που περιέχει μια υποδειγματική λύση για τις προκλήσεις:

+ ['Ανατολή του ήλιου' ολοκληρωμένο](https://trinket.io/html/abcc0284a3)

## Offline Πόροι

This project can be [completed offline](https://rpf.io/html-offline) if preferred. Μπορείς να αποκτήσεις πρόσβαση στους πόρους του έργου κάνοντας κλικ στο σύνδεσμο «Υλικό έργου» για αυτό το έργο. Αυτός ο σύνδεσμος περιέχει μια ενότητα "Πόροι έργου", η οποία περιλαμβάνει υλικό που τα παιδιά θα χρειαστούν για να ολοκληρώσουν αυτό το έργο εκτός σύνδεσης. Βεβαιώσου ότι κάθε παιδί έχει πρόσβαση σε ένα αντίγραφο αυτών των πόρων. Αυτή η ενότητα περιλαμβάνει τα ακόλουθα αρχεία:

+ template/index.html
+ template/prefix.js
+ template/style.css
+ sunrise/index.html
+ sunrise/style.css
+ sunrise/prefixfree.js
+ sunrise/boat.png
+ sunrise/cloud.png
+ sunrise/helicopter.png
+ sunrise/rainbow.png
+ sunrise/sun.png

Μπορείς επίσης να βρεις μια ολοκληρωμένη έκδοση των προκλήσεων αυτού του έργου στην ενότητα 'Πόροι εθελοντών', η οποία περιέχει:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Στόχοι μάθησης

+ Δημιουργία στυλ και κίνησης με CSS: 
    + Εισαγωγή του κανόνα `@keyframes` για τον ορισμό βημάτων σε μια μεταβαλλομενη απεικόνιση.
    + Εμπέδωση της χρήσης ιδιοτήτων για τον ορισμό του μεγέθους, σχήματος, θέσης και χρώματος των στοιχείων σε μια ιστοσελίδα.

Αυτό το έργο καλύπτει στοιχεία από τις ακόλουθες πτυχές του [Προγράμματος Μαθημάτων Ψηφιακής Δημιουργίας του Raspberry Pi](http://rpf.io/curriculum):

+ [Σχεδιασμός βασικών στοιχείων 2D και 3D](https://www.raspberrypi.org/curriculum/design/creator).

## Προκλήσεις

+ "Διαγώνια κίνηση" - επεξεργασία των ιδιοτήτων `@keyframe` της μεταβολής για τη χρήση του left:
+ "Βελτίωση του ουρανού" - προσθήκη περισσότερων keyframes και ορισμός του φόντου:
+ "Περισσότερες κινούμενες εικόνες" - μεταβολή περισσότερων εικόνων ή άλλων στοιχείων χρησιμοποιώντας μια ποικιλία CSS ιδιοτήτων. 

## Συχνές Ερωτήσεις

+ Αυτό το έργο κάνει χρήση της βιβλιοθήκης `prefixfree.js` της javascript, για την επίτευξη συμβατότητας μεταξύ διαφορετικών προγραμμάτων περιήγησης (browsers). Αν δε χρησιμοποιηθεί αυτή η βιβλιοθήκη, τα παιδιά που χρησιμοποιούν παλαιότερους browsers πρέπει να δηλώσουν μια μεταβολή για τον browser τους, για παράδειγμα:

    animation: sky 10s infinite;            //για όλους τους νεότερους browsers
    -webkit-animation: sky 10s infinite;    //για Webkit browsers (Chrome, Safari...)
    -moz-animation: sky 10s infinite;       //για Mozilla browsers
    -o-animation: sky 10s infinite;         //για Opera browsers
    -ms-animation: sky 10s infinite;        //για Microsoft browsers 
    

\--- /collapse \---

## \--- collapse \---

## title: Υλικό έργου

## Πόροι έργου

+ [αρχείο .zip που περιέχει όλους τους πόρους του έργου](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
+ [Online Trinket που περιέχει όλους τους πόρους του έργου 'Ανατολή του ήλιου'](http://jumpto.cc/web-sunrise)
+ [Online πρότυπο Trinket](http://jumpto.cc/trinket-template)
+ [Online κενό Trinket](http://jumpto.cc/trinket-blank)
+ [template/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-index.html)
+ [template/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-style.css)
+ [intro/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-index.html)
+ [intro/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-style.css)
+ [sunrise/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-index.html)
+ [sunrise/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-style.css)
+ [sunrise/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-prefixfree.js)
+ [sunrise/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-sun.png)
+ [sunrise/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-rainbow.png)
+ [sunrise/cloud.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-cloud.png)
+ [sunrise/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-boat.png)
+ [sunrise/helicopter.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-helicopter.png)

## Πόροι συντονιστή ομάδας

+ [Αρχείο .zip που περιέχει όλους τους ολοκληρωμένους πόρους του έργου](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
+ [Online ολοκληρωμένο έργο Trinket](https://trinket.io/html/abcc0284a3)
+ [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
+ [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
+ [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
+ [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
+ [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
+ [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

\--- /collapse \---