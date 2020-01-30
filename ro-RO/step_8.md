--- challenge ---

## Provocare: Mai multă animație

Poți anima altă imagine? Poți anima poziția, culoarea, forma, dimensiunea, nivelul de opacitate (să poți vedea prin acea imagine) sau orice altceva la care te poți gândi. De asemenea, încearcă să modifici timpul de rulare al animațiilor.

Pentru fiecare obiect pe care vrei să îl faci animat, trebuie să:

+ Îl incluzi în HTML cu un id
+ Adaugi un stil pentru fiecare id
+ Creezi reguli @keyframes
+ Utilizezi `animation:` în stilul elementului pentru a-i atribui animația definită cu @keyframes 

Apasă pe iconița imaginilor pentru a vedea ce imagini au fost incluse in proiect:

![captură de ecran](images/sunrise-images.png)

De asemenea, poți încărca propriile tale imagini dacă dorești.

Nu uita că poți să adaugi obiecte pe mare, la fel cum ai făcut și pe cer:

![captură de ecran](images/sunrise-boat.png)

În exemplu, curcubeul folosește opacitatea pentru un efect de apariție treptată:

    @keyframes fade {
      0%  
      50% 
      66% 
      100%  
    }
    

Barca utilizează o valoare negativă de pornire pentru a intra în animație mai târziu:

     @keyframes left-right {
      0%   
      100% 
    }
    

--- /challenge ---

***
Acest proiect a fost tradus de voluntarii:

**Cristian Iacob**

**Gelu Ungur**

Datorită voluntarilor, putem oferi oamenilor din întreaga lume șansa de a învăța în propria lor limbă. Ne poți ajuta să ajungem la mai multe persoane, ajutând la traducere ca și voluntar - mai multe informații la [rpf.io/translate](https://rpf.io/translate).