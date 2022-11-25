# Pirmoji užduotis v1.1 #
Šioje versijoje yra apskaičiuojamas studento ar studentų galutinis įvertinimas;

1. Programos realizaciją (versiją v1.0) pakeista taip, kad vietoje sukurtos data structūros jos pagrindu sukurta class'ę data.
2. Struct ir Class realizacijos sparta (palyginimas):

| TIPAS  | KIEKIS   | F! NUSKAITYMAS IR SKAIČIAVIMAS | SUSKIRSTYMAS/RŪŠIAVIMAS Į VEKTORIUS | IŠVEDIMAS  |
|--------|----------|--------------------------------|-------------------------------------|------------|
| struct | 100000   | 0.051365 s                     | 0.0172147 s                         | 0.534344 s |
|        | 1000000  | 1.17018 s                      | 0.540851 s                          | 1.1299 s   |
|        | 10000000 | 32.5802 s                      | 15.0002 s                           | 19.21 s    |
|        |          |                                |                                     |            |
| class  | 100000   | 0.0855839 s                    | 0.0148084 s                         | 0.29665 s  |
|        | 1000000  | 1.0516 s                       | 0.496612 s                          | 2.37164 s  |
|        | 10000000 | 35.3514 s                      | 7.4089 s                            | 29.1266 s  |

3. Atlikta eksperimentinė analizė priklausomai nuo kompiliatoriaus optimizavimo lygio (palyginimas):

| FLAG'AS | KIEKIS   | NUSKAITYMAS | IŠSKIRSTYMAS | IŠVEDIMAS  |
|---------|----------|-------------|--------------|------------|
| 01      | 100000   | 0.279883 s  | 0.0328482 s  | 0.20165 s  |
|         | 1000000  | 3.5737 s    | 0.39092 s    | 2.94953 s  |
|         | 10000000 | 27.6266 s   | 9.56357 s    | 21.6099 s  |
|         |          |             |              |            |
| 02      | 100000   | 0.317432 s  | 0.038894 s   | 0.253594 s |
|         | 1000000  | 3.45165 s   | 0.372269 s   | 2.62386 s  |
|         | 10000000 | 31.2177 s   | 7.4315 s     | 22.4425 s  |
|         |          |             |              |            |
| 03      | 100000   | 0.370935 s  | 0.0354623 s  | 0.26057 s  |
|         | 1000000  | 3.45865 s   | 0.371608 s   | 2.7613 s   |
|         | 10000000 | 28.6496 s   | 8.76929 s    | 25.9495 s  |
