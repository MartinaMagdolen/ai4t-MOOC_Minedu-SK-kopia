---
názov: "3.3.4 Odkiaľ pochádza riziko?"
opis: Identifikujte rôzne typy rizík
---
??? info "Metadáta"
    - ID: EU.AI4T.O1.M3.3.3t
    - Názov: 3.3.3 Odkiaľ pochádza riziko?
    - Typ: text
    - Opis: Identifikujte rôzne typy rizík
    - Predmet: Umelá inteligencia pre učiteľov a od učiteľov
    - Autori:
        - AI4T 
    - Licencia: CC BY 4.0
    - Dátum: 2022-11-15


# Odkiaľ pochádza riziko?
Výskumná služba Európskeho parlamentu (EPRS) vo svojej štúdii o umelej inteligencii[^1] uviedla: *„Je dôležité poznamenať, že AI algoritmy nemôžu byť objektívne, pretože rovnako ako ľudia si počas svojho tréningu osvojujú spôsob, ako dávať zmysel videným veciam a tento svoj ‚svetonázor‘ využívajú na kategorizáciu nových situácií, s ktorými sa stretávajú.“*

Pozrime sa na to, aký má subjektivita umelej inteligencie zdroj a aké sú s ňou spojené riziká.

## Zaujatosť v dátach a algoritmoch

Tak ako pri každom digitálnom systéme, dáta používané na AI platformách pochádzajú z rôznych zdrojov a majú rôzne formáty. Aj preto môžu byť poznačené rôznymi typmi zaujatosti alebo skreslenia (z angl. _bias_).[^2] Zaujatosť dát sa prejavuje hlavne na štatistickej úrovni. Uveďme si niektoré z nich:

-   **Výberová zaujatosť** je zvyčajne prítomná v hodnotách dát. Príkladom môže byť náborový algoritmus trénovaný na databáze, v ktorej sú nadmerne zastúpení muži, čo povedie k vylúčeniu žien.

-   **Stereotypná zaujatosť (Stereotype bias)** je tendencia konať s odkazom na sociálnu skupinu, ku ktorej patríme. Jedna štúdia napríklad ukazuje, že ženy majú tendenciu klikať na pracovné ponuky, o ktorých si myslia, že ich ako ženy ľahšie získajú.

-   **Zaujatosť vynechanou premennou (Omitted variable bias)** (zaujatosť pri modelovaní alebo kódovaní) je zaujatosť spôsobená ťažkosťami pri reprezentácii alebo kódovaní určitého faktora v údajoch. Napríklad preto, že je ťažké nájsť faktické kritériá na meranie emočnej inteligencie, tento rozmer v náborových algoritmoch chýba.

-   **Zaujatosť pri výbere (Selection bias)** je zasa spôsobená charakteristikami vzorky vybranej na vyvodenie záverov. Napríklad banka použije interné údaje na odvodenie úverového skóre, pričom sa zameria na tých, ktorí pôžičku získali alebo nezískali, ale ignoruje tých, ktorí si nikdy nepotrebovali požičať atď.

Algoritmická zaujatosť je hlavne záležitosťou uvažovania. Takúto zaujatosť zavádzajú inžinieri AI úmyselne alebo neúmyselne.

Štúdia EPRS uvádza dva konkrétne príklady: „*Predstavte si symbolický algoritmus AI na posudzovanie žiadostí o zamestnanie. Mohol by hodnotiť kandidátov priraďovaním bodov len na základe ich vzdelania a skúseností. Ak však nezohľadní faktory, ako je materská dovolenka, alebo primerane neuzná vzdelanie v zahraničných inštitúciách spôsobom, akým by to urobili ľudské výberové komisie, algoritmus by mohol diskriminovať ženy a zahraničných kandidátov.*“

„*Teraz si predstavte podobný nástroj AI v rámci paradigmy ML (strojového učenia). Takéto algoritmy si nachádzajú vlastné spôsoby identifikácie toho, aký druh kandidátov bol vybraný v ich tréningových údajoch. Tam, kde existuje história štrukturálnych predsudkov v týchto výberoch – napríklad rasová diskriminácia – algoritmus sa ich môže naučiť. Dokonca aj tam, kde sú údaje o štátnej príslušnosti alebo etnickej príslušnosti z údajov odstránené, je ML zručné v hľadaní zástupných ukazovateľov (proxies) pre základné vzorce v iných údajoch, ako sú jazyky, poštové smerovacie čísla alebo školy, ktoré môžu byť dobrými prediktormi etnicity.*“

## Tri aspekty algoritmického rizika

Algoritmické riziko možno charakterizovať tromi spôsobmi[^3].

-   Po prvé, existuje **algoritmické uzavretie (confinement)**, ktoré sa môže týkať aj názorov, kultúrnych znalostí alebo dokonca obchodných praktík. Algoritmy totiž konfrontujú používateľa internetu s rovnakým obsahom v závislosti od jeho profilu a integrovaných parametrov, napriek rešpektovaniu princípu spravodlivosti. To je prípad stránok s odporúčaním správ, ako je Facebook, alebo stránok s odporúčaním produktov, ako je Amazon.

-   Druhý aspekt algoritmického rizika súvisí s **kontrolou všetkých aspektov života jednotlivca**, od regulácie informácií pre investorov až po jeho stravovacie návyky, koníčky alebo dokonca zdravotný stav. Toto sledovanie jednotlivca naznačuje formu dohľadu, ktorá odporuje samotnej podstate individuálnej slobody.

-   Tretí aspekt súvisí s **potenciálnym porušením základných práv**. Ide najmä o algoritmickú diskrimináciu definovanú ako nepriaznivé alebo nerovnaké zaobchádzanie v porovnaní s inými osobami alebo inými rovnakými či podobnými situáciami na základe dôvodu výslovne zakázaného zákonom. To zahŕňa štúdium spravodlivosti (*fairness*) algoritmov na zaraďovanie (triedenie ľudí hľadajúcich prácu online), odporúčanie a učenie sa predpovedí. Problém diskriminačnej zaujatosti vyvolanej algoritmami sa týka viacerých oblastí, ako je prijímanie do zamestnania online, súdne rozhodnutia, rozhodnutia policajných hliadok alebo prijímanie do škôl.

## Ako sa vysporiadať s rizikami údajov a algoritmov?

Podľa článku *Towards a Standard for Identifying and Managing Bias in Artificial Intelligence*[^4]: „*Zaujatosť nie je nová ani jedinečná pre AI a nie je možné dosiahnuť nulové riziko zaujatosti v systéme AI*“. 
Zároveň uznanie toho, že agenti AI sú prirodzene subjektívni, je kľúčovým predpokladom na zabezpečenie toho, aby sa používali len na úlohy, na ktoré sú dobre vybavení.

Štúdia EPRS končí niekoľkými odporúčaniami pri používaní aplikácií založených na AI:

-   Pochopiť zaujatosť a subjektivitu
-   Vyhýbať sa aplikáciám nad rámec schopností AI
-   Vyhýbať sa aplikáciám s nežiaducimi dopadmi
-   Zachovať autonómiu človeka
-   Hľadať riešenia problémov, nie problémy pre riešenia
-   Zvážiť, čo od AI skutočne chceme

[^1]: [Artificial intelligence: How does it work, why does it matter, and what can we do about it?](https://www.europarl.europa.eu/thinktank/en/document/EPRS_STU(2020)641547) - Philip Boucher, Scientific Foresight Unit (STOA) - ISBN: 978-92-846-6770-3 - Union Européenne, 2020

[^2]: [Algorithms, Data and Bias: Public Policy Needed](https://www.institutmontaigne.org/en/analysis/algorithms-data-and-bias-public-policy-needed?_wrapper_format=html), Anne Bouverot, Thierry Delaporte, 2019

[^3]: Článok vo francúzštine: [D'où vient le risque ? Des données et des algorithmes](https://www.lemonde.fr/blog/binaire/2020/02/05/les-plateformes-numeriques-un-foyer-pour-les-risques-donnees-et-algorithmes/) - Serge Abiteboul, Thierry Viéville, 2020

[^4]: [Towards a Standard for Identifying and Managing Bias in Artificial Intelligence]
