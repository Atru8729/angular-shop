Angular komponentai (parduotuvė).

1. Sukurkite naują (Angular) projektą elektroninės komercijos produktui.
2. Sukurkite komponentą, kuris atvaizduoja produktą.
3. Produktas turi atvaizduoti pavadinimą, kainą ir paveikslėlį. Paveikslėlį pasirinkite savo nuožiūra.
4. Paryškinkite elementa fono spalva, jei produktas šiuo metu yra su nuolaida. Informacija apie nuolaida turėtų būti saugoma produkto modelyje.
5. Pridėkite mygtukus, kurie leidžia padidinti arba pamažinti produkto kiekį krepšelyje. Kiekis krepšelyje turėtų būti matomas. Jei pr odukto kiekis krepšelyje lygus nuliui - padarykite išėmimo mygtuką neaktyviu.

Eiga
Angular CLI diegimas npm install -g @angular/cli.
Projekto sukūrimas, terminale pasirenkame lokaciją (direktoriją) ir kviečiame komandą ng new projekto-pavadinimas.
Projekte būna pridėtas komponentas (app.component.[ts/scss/html]).
Produkto modelio (klasės) aprašymas. Klasė turėtų šiuos atributus: paveikslėlį (nuoroda, string), pavadinimas (string), kaina (number), nuolaida (boolean/number).
Komponento viduje apibrėžiamas (sukuriamas) produkto modelis (panaudojant klasę).
Komponento template viduje (html) atspausdinami modelio (prekės) duomenys.
Elementams priskiriamos direktyvos. Direktyvos nulemia komponento atvaizdavimo logiką, pvz.: NgClass direktyva leidžia nuimti/pridėti elementui klasę. [disabled] direktyva leidžia aktyvuoti/deaktyvuoti mygtuką.
