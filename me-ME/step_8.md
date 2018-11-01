\--- challenge \---

## Izazov: Više animacije

Da li možeš da animiraš neku drugu sliku? Možeš da animiraš njenu poziciju, boju, oblik, veličinu, neprozirnost (providnost) ili bilo šta drugo čega možeš se sjetiš. Takođe probaj da mijenjaš vrijeme trajanja svojih animacija.

Za svaki elemenat koji želiš da animiraš biće potrebno da:

+ Dodaš elemenat sa identifikatorom (id) u svoj HTML
+ Dodaš stil za id
+ Kreiraš @keyframes pravilo
+ Upotrijebiš `animation:` u stilu za korišćenje animacije koju si definisao/definisala sa @keyframes 

Klikni na ikonu za slike da pregledaš slike koje sadrži projekat:

![screenshot](images/sunrise-images.png)

Ako želiš, možeš takođe da preneseš svoje slike.

Ne zaboravi da elemente možeš da postaviš na more, kao i na nebo:

![screenshot](images/sunrise-boat.png)

U primjeru se za dugu koristi opacity (providnost) kako bi se postigao efekat postepenog nestajanja (fade effect):

    @keyframes fade {
      0%  
      50% 
      66% 
      100%  
    }
    

Za brod se koristi negativna početna pozicija, tako da se brod ne vidi u jednom dijelu animacije:

     @keyframes left-right {
      0%   
      100% 
    }
    

\--- /challenge \---