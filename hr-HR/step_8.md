--- challenge ---

## Izazov: više animacije

Možeš li animirati još jednu sliku? Možeš animirati položaj, boju, oblik, veličinu, neprozirnost (vidljivost) ili bilo što drugo. Također pokušaj mijenjati vrijeme trajanja animacija.

Za svaku stavku koju želiš animirati morat ćeš:

+ Uključiti ju u svoj HTML kȏd s ID-om
+ Dodati stil za ID
+ Napravite @keyframes pravilo
+ Koristiti `animation:` u stilu da upotrijebiš animaciju koju ćeš definirati koristeći @keyframeso

Klikni na ikonu slike da vidiš slike koje su uključene u projekt:

![screenshot](images/sunrise-images.png)

Također možeš dodati vlastite slike ako želiš.

Nemoj zaboraviti da možeš dodati stvari u more kao i u nebo:

![screenshot](images/sunrise-boat.png)

U primjeru duga koristi neprozirnost za efekt izblijeđivanja:
```
    @ keyframes izblijedi {0% 50% 66% 100%}
```    

Brod koristi negativnu polaznu poziciju tako da ga u jednom dijelu animacije ne možeš vidjeti:
```
     @keyframes left-right {
      0%   
      100% 
    }
```    

--- /challenge ---


***
Ovaj su projekt preveli volonteri:

Marin Vitaljić

Erik Braun

Zahvaljujući volonterima, možemo pružiti ljudima širom svijeta priliku da uče na svom jeziku. Možete nam pomoći da dođemo do većeg broja ljudi tako da postanete volonter prevoditelj. Više informacija možete pronaći na [rpf.io/translate](https://rpf.io/translate).
