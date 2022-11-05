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
    -   Rekomenduotina į visus šiuos 3 klausimus atsakyti raštu projekto grupės chat'e/kanale;
-   Ar darom penktadienines retrospektyvas?
    -   Ar atliekant užduotis, kilo kokių nors nesusipratimų? Jei taip, kaip būtų galima geriau jas apsirašyti?
    -   Ar darbo procese yra kokių trūkumų? Kaip tai pagerinti?
        -   pvz.: Kažkas labai lėtas. Ką daryti?
        -   pvz.: Kažkas visai nedirba. Ką daryti?
        -   pvz.: PR ilgai kabo nepatvirtinti, todėl pyksta klientas. Ką daryti?
-   Kiti techniniai klausimai:
    -   kintamųjų, funkcijų, failų, folderių ir kt. pavadinimų rašymo standartai?
    -   eslint naudojimas?
    -   prettier naudojimas?
    -   _git-conflict_ padedantys išvengti veiksmai?
    -   CI/CD naudojimas?
    -   perklausti, ar visi supranta, koks bus darbo procesas? (Github-flow)

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
    -   Užduočių atlikėjas vadovaujasi ta pačia prioriteto tvarka, t.y jei atsilaisvinai (atlikai darytą užduotį), tai imi sekančią svarbiausią užduotį.

## Užduoties atlikimas

Į ką atsižvelgti atlikinėjant užduotį.

-   Nuo ko pradėti?
    -   Perskaityti užduotį ir įsitikinti, jog supranti ką reikia padaryti;
    -   Jei kyla papildomų klausimų - rašom komentarus prie tos pačios užduoties (Github'e) ir laukiam patikslinimų iš komandos narių ir/arba kliento;
    -   Užduotyje prisiskiriam save kaip _Assignee_;
    -   Susikuriam _feature-branch_ Github'e (online) ir dirbam;
    -   Jei projekte yra naudojami/rašomi testai (pvz.: Jest), tai reikia atskirame terminale pasileisti testų script'ą;
    -   reikalingi resursai (nuotraukos, šriftai, video, audio) turi būti įtraukiami su kiekviena individualia užduoti, o ne sukelta prieš pradedant dirbti bendrai prie projekto;
-   Jei atliekant savą užduotį kažkuris komandos narys spėjo "sumerdžinti" (PR merge) savo branch'ą į _develop_ branch'ą?
    -   Pasidarom PR iš _develop_ į savo _feature-branch_;
    -   Jei sugriūna dizainas ir/arba logika (JS), tai prisiimam sau kaltę ir taip ištaisome savo kodą, jog veiktų ir kodas esantis _develop_ branch'e ir pas tave;
-   Ką daryti kai stringi ties užduotimi?
    -   Pats ieškai sprendimo ~30min;
    -   Klausiam savo komandos narių, tam skiriam max ~1-2val;
    -   Klausiam grupės narių, tam skiriam max ~1-2val;
    -   Klausiam kitų besimokančių, tam skiriam max ~1-2val;
    -   Klausiam mentorių;
-   Jei atliekant užduotį paaiškėja, jog dalies funkcionalumo nepavyks įgyvendinti?
    -   atliekam tiek užduoties kiek galim;
    -   atliekam visą procesą susijusį su pagalbos iš kitų gavimu;
    -   neišspręstą funkcionalumo dalį išsikeliame kaip naują atskirą užduotį;
-   Testavimas/tikrinimas, tiek atlikinėjant užduotį, tiek ją baigus:
    -   jei kalba eina apie struktūrą (HTML):
        -   kritiškai pažiūrime, ar kartais nėra perteklinių HTML tag'ų;
        -   sužiūrėti, ar galima panaudoti semantiškai tinkamesnį HTML tag'ą;
    -   jei kalba eina apie dizainą (CSS):
        -   pasitikriname kaip viskas atrodo keičiant ekrano dydį (_responsive design_ momentas);
        -   ar nėra naudojami #ID selektoriai, jei yra - ar tam turima svari priežastis;
        -   ar nėra naudojami "!important", jei yra - ar tam turima svari priežastis;
        -   ar selector'iai yra rašomi elementų atsiradimo eiliškumu?
        -   ar selector'iai neviršija 3-jų lygių (specificity)?
    -   jei kalba eina apie logiką (JS):
        -   ar pagal nutylėjimą naudojamos _const_?
        -   naršyklės console turi būti švari; jokių išspausdintų reikšmių; jokių klaidos pranešimų;
        -   jei užduotyje buvo numatyti naudoti tikrus testus (pvz.: Jest), tai ar jie aprašyti? Būtų labai gerai, jei kokybiškų testų būtų kuo daugiau.
-   Baigus užduotį:
    -   pasidaryti dar vieną papildomą PR iš _develop_ branch'o;
    -   jei kilo _git conflict'as_ - ištaisom, jog jo neliktų;
    -   jei sugriūvo dizainas ir/arba logika - ištaisom, jog viskas veiktų taip kaip reikia;
    -   ir tik tada galim susikurti savo PR iš _feature-branch_ į _develop_ branch'ą;

## Kodo peržiūra/patikra (Code review)

Procesas kodo kokybei palaikyti ir gal net pagerinti.

-   visų pirma atsisiunčiame PR pas save lokaliai;
-   persijungiame brach'ą į PR branch'ą;
-   pasileisti `npm i` komandą;
-   jei naudojami testai, tai pasileisti _test_ komandą `npm run test`;
    -   jei randamos klaidos - Github PR komentaruose taip ir parašom; kol neištaisys, tolimesnis tikrinimas nebus daromas;
-   pasileisti _dev_ serverį su `npm run dev` komanda;
    -   naršyklėje atsidaryti nuorodą;
    -   sužiūrėti _responsive design_;
    -   patikrinti, ar _console_ švari?
    -   sužiūrėti, ar laikomasi HTML, CSS ir JS rašymo reikalavimų (žr. Užduoties atlikimas)
    -   ar visi resursai užsikrauna (failai)?
    -   sužiūrėti, jog PR turi viską ko reikalavo užduotis (darbų lenta), jei kažko nėra - žymim kaip klaidą, nebent buvo susitarta tą dalį iškelti kaip atskirą užduotį;
    -   jei randamos klaidos ir žinomos tikslios vietos kode kur jos kyla, tai reikia _Github PR -> Files changed_ dalyje pažymėti tas vietas ir parašyti konkrečius komentarus kas ten yra galima negerai ir/arba ką gali tobulinti;
    -   jei randama klaida, bet tikrintojui nepavyksta nustatyti priežasties, tai tokį komentarą reikia parašyti prie "Review changes" formos;
    -   jei rasta kritinių klaidų, tai privaloma "Review changes" formoje spausti "Request changes" parinkti;
    -   "Review changes" formoje spausti "Approve" parinktį galima tik jei tikrai nerandi jokių priekaištų peržiūrėtam kodui, o kaip komentarą galima pvz palikti "LGTM";
-   kai buvo atlikta reikiamas kiekis kodo patikrinimų, tai pirmas pamatęs galimybę "sumerdžinti" kodą - tą ir padaro;
-   nebereikalingus branch'us išsitrina asmenys, kurie su juo dirbo (savininkas, tiek _online_, tiek _local_);

## Rezultato viešinimas

Periodiškumas. Užduočių grupavimas, nes kartais neprasminga paleisti neišbaigto funkcionalumo komplekto.

-   Į _master_ branch'ą atnaujinimai turėtų sueiti bent kas antrą dieną;
-   Į _develop_ branch'ą atnaujinimai turėtų sueiti iš karto po užduoties atlikimo;
-   vieša projekto nuoroda (Github pages) privalo veikti visą laiką;
