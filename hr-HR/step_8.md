\--- challenge \---

## Izazov: Više animacije

Možete li animirati još jednu sliku? Možete animirati položaj, boju, oblik, veličinu, neprozirnost (vidljivost) ili bilo što drugo na što se možete sjetiti. Također pokušajte mijenjati količinu vremena koja je potrebna za vaše animacije.

Za svaku stavku koju želite animirati morat ćete:

+ Uključite ga u svoj HTML kȏd s ID-om
+ Dodajte stil za ID
+ Napravite pravilo @keyframes
+ Upotrijebite `animaciju:` u stilu da biste upotrijebili animaciju koju ste definirali s @keyframesom 

Kliknite ikonu slike da biste vidjeli slike koje su uključene u projekt:

![screenshot](images/sunrise-images.png)

Također možete prenijeti vlastite slike ako želite.

Nemojte zaboraviti da možete staviti predmete u more kao i u nebo:

![screenshot](images/sunrise-boat.png)

U primjeru duga koristi neprozirnost za efekt izblijeđivanja:

    @ keyframes izblijedi {0% 50% 66% 100%}
    

Brod koristi negativnu polaznu poziciju tako da ga ne možete vidjeti za dio animacije:

     @keyframes left-right {
      0%   
      100% 
    }
    

\--- /challenge \---