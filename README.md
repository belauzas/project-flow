# Projekto eiga / project flow

**Tipas**: tik _frontend_, komandinis darbas (teamwork).

## Bendrinis projekto aptarimas

Išankstinis techninių ir netechninių klausimų aptarimas ir reikalavimų išsiaiškinimas.

-   Pasitikslinti, ar tikrai bus tik _frontend_ ir nebus jokios _backend_ logikos?
    -   Jei nėra _backend_, ar bus reikalingi kažkokie pavyzdiniai duomenys? Jei taip, iš kur/kaip juos gausime?
    -   Galima naudoti JS failus, kurie eksportuoja duomenis.
    -   Galima būti iš anksto paviešinus JSON failus _master_ branch'e ir iš ten gauti duomenis naudojant _fetch()/ajax()_.
-   _Responsive_ dizainas? Beveik garantuotai, jog **taip**.
-   Ar atliekant pavienes užduotis, _responsive_ dizainas turi būti atliktas kokybiškai pagal nutylėjimą? Beveik garantuotai, jog **taip**), nebent yra suplanuota, jog komponentas bus daromas etapais, ir _responsive_ dalis yra tų etapų sudėtyje.
-   Kokia kalba bus naudojama bendraujant, bent jau Github lygyje? Lietuvių? Anglų? Kita?
    -   Pasirinkus sprendimą, ta kalba reikėtų stengtis visada ir susirašinėti, bei kurti užduotis Github'e.
    -   Rekomenduotina Github'e susirašinėti angliškai;
-   Ar darom rytinius stand-up'us?
    -   Ką dariau vakar?
    -   Ką darysiu šiandien?
    -   Ar kylo kokių nors kliūčių?
    -   Rekomenduotina visus šiuos 3 klausimus atsakyti raštu projekto grupės chat'ą/kanale;
-   Ar darom penktadienines retrospektyvas?
    -   Ar atliekant užduotis, kylo kokių nors nesusipratimų? Jei taip, kaip būtų galima geriau jas apsirašyti?
    -   Ar darbo procese yra kokių trūkumų? Kaip tai pagerinti?
        -   pvz.: Kažkas labai lėtas. Ką daryti?
        -   pvz.: Kažkas visai nedirba. Ką daryti?
        -   pvz.: PR ilgai kabo nepatvirtinti, todėl pyksta klientas. Ką daryti?
-   Kiti techniniai klausimai:
    -   eslint naudojimas?
    -   prettier naudojimas?
    -   _git-conflict_ padedantys išvengti veiksmai?
    -   CI/CD naudojimas?
    -   persiklausti, ar visi supranta, koks bus darbo procesas? (Github-flow)

## Užduočių planavimas

Tikslas yra kokybiškos užduotys, t.y. perskaičius praktiškai nekyla klausimų kaip jas realizuoti, o realizavus, tikrintojams nekyla kažkokių esminių trūkumų. Agile/scrume.

-   Trumpa bet aiški antraštė.
-   Dažniausiai bus reikalingas išsamus aprašymas, kurį gali sudaryti:
    -   tekstas;
    -   sąrašas (✅) kriterijų, kuriuos turi atitikti;
    -   nuotraukos/screenshot'ai;
    -   nuotraukose esant poreikiui naudinga turėti papildomus pažymėjimus;
    -   nuorodos į dokumentaciją, kuria būtų galima pasinaudoti sprendžiant esamą užduotį;
    -   ar reikia atnaujinti projekto README?
    -   ar bus reikalinti testai (pvz.: Jest)?
-   _Labels_ (hashtags) naudojimas. Padeda, turint daug užduočių, atsirinkti/atsifiltruoti tik tas užduotis, kurios domina pagal kažkokias temas.
-   Priskirimas darbų lentai.
-   Užduoties kūrimo metu nepriskirinėjam žmogaus, kuris ją turės atlikti! Nes mes ne pranašai ir nežinom kas tuo metu pas mus komandoje dirbs, kas bus gyvas, kas bus laisvas, t.t.
-   Prieš pradedant atlikinėti užduotis (bendrai), jos turi būti surikiuotos prioriteto tvarka.
    -   Užduočių atlikas vadovaujasi ta pačia prioriteto tvarka, t.y jei atsilaisvimai (atlikai darytą užduotį), tai imi sekančią svarbiausią užduotį.
