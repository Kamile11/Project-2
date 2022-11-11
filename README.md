# Studentų galutinio balo skaičiuoklė v0.1 #
Programa skirta apskaičiuoti kiekvieno studento galutinį balą panaudojant vidukį/medianą.

- - - 
## Veikimo principas ##
1. Vartotojas įvedą studento vardą ir pavardę. Studentų kiekis nėra ribojamas. Suvedus reikiamus duomenis apie studentą, vartotojas gauna užkalausą: "Ar norite ivesti dar vieno studento duomenis: [y/n]";
2. Vartotojas turi pasirinkimą namų darbų pažymius ir egzamino rezultatą suvesti rankiniu būdų arba sugeneruoti atsitiktinai. Užklausa:  "Ar norite atsitiktinai generuoti pazymius? [y/n]";
  2.2 Jei pazymius vartotojas veda pats. Vartotojas įvedą egzamino pažymį ir taip pat iki 10 namų darbų pažymių;
3. Galutinis pažymys yra apsakičiaujamas tiek su pažymių vidurkiu, tiek ir su mediana;

Programa išvedą studentų vardus ir pavardes bei studentų galutinius pažymius suskaičiuotus su pažymiu vidurkiu ir mediana.

# Antroji užduotis v0.2 #
Šioje versijoje yra apskaičiuojamas studento ar studentų galutinis įvertinimas.

- - - 
## Veikimo principas ##
1. v0.1 buvo papildyta, tuo kad dabar galima duomenis ne tik įvesti bet ir nuskaityti iš failo. Vartotojui suteikiamas pasirinkimas.
2. Studentai yra surūšiuojami pagal vardus.
3. Funkcijos, nauji duomenų tipai buvo perkelti į antraštinius (header) failus, bei sukurti trys nauji .cpp failai.
4. Minimaliai panaudotas išimčių valdymas.

# Trečioji užduotis v0.3 #
Šioje versijoje yra apskaičiuojamas studento ar studentų galutinis įvertinimas;

- - - 
## Veikimo principas ##
1. Atsirado nauja funkcija Failų generacija. Vartotojas pasirenka kiek studentų ir kiek studentų pažymių bus.
2. Studentai yra surušiuojami į dvi grupes; vargšiukai ( x>5 ) ir gudročiai ( x<5 ).
3. Studentai atspausdinami į du skirtingus failus.

# Ketvirtoji užduotis v0.4 #

- - - 
## Veikimo principas ##
Šioje versijoje yra apskaičiuojamas studento ar studentų galutinis įvertinimas;
1. Buvo sukurtos dvi atskiros programos su dviejais skirtingais konteineriais: vector, list.
2. Buvo atlikti laiko matavymai šių dvieju konteinerių spartumo.
Analizė: 
Greičiausias uskirstymas studentu į skirtingus konteinerius - vector;
Greičiausias failo nuskaitymas ir suskaičiavimas - List;

# Penktoji užduotis v1.0 #

- - - 
## Veikimo principas ##
Šioje versijoje yra apskaičiuojamas studento ar studentų galutinis įvertinimas;
1. Buvo ištestuotos 2 strategijos - vector, list konteineriams
Analizė:
1 strategija greitesnė - Vector konteineriu;
2 strategija greitesnė - List konteineriu;
2. Pritaikyti algoritmai studentų dalijimo procedūrai paspartinti (vector - konteinerio) - pritaikytas remove_if algoritmas
<img width="388" alt="image" src="https://user-images.githubusercontent.com/99173750/163716564-6bca804b-2c73-4843-b267-342249a44af4.png">
II strategija tris kartus pagreitėjo ir optimizavosi panaudojus remove_if algoritmą.

### Versijos ###
*[v0.1](https://github.com/Kamile11/Project-1.git) - pirminė programos versija.
*[v0.2] -jhg
*[v0.3]
*[v0.4]
*[v1.0]

