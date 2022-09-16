# Studentų galutinio balo skaičiuoklė #
Programa skirta apskaičiuoti kiekvieno studento galutinį balą panaudojant vidukį/medianą.

- - - 
## Veikimo principas ##
Pagal aprašytus užduoties reikalavimus realizuokite programą, kuri nuskaito vartotojų įvedamus reikiamus duomenis (patogiausiai naudoti struktūrą):
studento vardą ir pavardę;
namų darbų ir egzamino rezultatą;
Baigus duomenų įvedimą, suskaičiuoja galutinį balą ir juos pateikia į ekraną tokiu ar panašiu pavidalu (kur galutinis apskaičiuotas balas pateikiamas dviejų skaičių po kablelio tikslumu):
 ```
Pavardė    Vardas     Galutinis
--------------------------------
Pavardė1   Vardas1    x.xx
Pavardė2   Vardas2    y.yy
Pavardė3   Vardas3    z.zz
 ```

- - - 
## Įvedimo instrukcija ##
Vartotojas po kiekvieno pažymio įvedimo turi paspausti *Enter*, jei nori užbaigti pažymio įvedimą turi paspausti *s* ir *enter*.
Kai vartotojo prašoma pasirinkti, jis turi įvesti vieną iš nurodytų simbolių *taip/ne*.
Programa išmeta klaidą ir prašo pakartoti įvedimą šiais atvejais:
* Jei studento varde/pavardėje aptinka ne raidę, o neleistiną simbolį;
* Jei namų darbų pažymys/egzamino balas yra:
  * raidė;
  * simbolis;
  * ne intervale [1 - 10].
* Jei vietoje 'taip' arba 'ne' aptinka kitą simbolį. 
- - - 

## Apie programą ##

Programa yra realizuota dviem būdais: su C tipo masyvais ir su vektoriais. Programa su C tipo masyvais saugoma **c-masyvas.cpp**, o su vektoriais - **vektorius.cpp**.

Programa yra realizuota dviem būdais: naudojant ```C``` tipo masyvą - **c-masyvas.cpp** ir ```<vector>``` tipo konteinerį - **vektorius.cpp**.

### Versijos ###
*  - pirminė programos versija.
