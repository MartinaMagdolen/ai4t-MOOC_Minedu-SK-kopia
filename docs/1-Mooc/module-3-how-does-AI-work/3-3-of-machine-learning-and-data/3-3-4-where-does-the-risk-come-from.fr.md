---
názov: "3.3.4 Čo je zdrojom rizika?"
opis: Identifikujte rôzne typy rizík
---
??? info "Metadáta"
    - ID: EU.AI4T.O1.M3.3.3t
    - Názov: 3.3.3 Čo je zdrojom rizika?
    - Typ: text
    - Opis: Identifikujte rôzne typy rizík
    - Predmet: Umelá inteligencia pre učiteľov a od učiteľov
    - Autori:
        - AI4T 
    - Licencia: CC BY 4.0
    - Dátum: 2022-11-15


# Čo je zdrojom rizika?
Výskumná služba Európskeho parlamentu (EPRS) vo svojej štúdii o umelej inteligencii[^1] uviedla: *„Je dôležité poznamenať, že AI algoritmy nemôžu byť objektívne, pretože rovnako ako ľudia si počas svojho tréningu osvojujú spôsob, ako dávať zmysel videným veciam a tento svoj ‚svetonázor‘ využívajú na kategorizáciu nových situácií, s ktorými sa stretávajú.“*

Pozrime sa na to, aký má subjektivita umelej inteligencie zdroj a aké sú s ňou spojené riziká.

## Zaujatosť v dátach a algoritmoch

Tak ako pri každom digitálnom systéme, dáta používané na AI platformách pochádzajú z rôznych zdrojov a majú rôzne formáty. Aj preto môžu byť poznačené rôznymi typmi zaujatosti alebo skreslenia (z angl. _bias_).[^2] Zaujatosť dát sa prejavuje hlavne na štatistickej úrovni. Uveďme si niektoré z nich:

-   **Zaujatosť vzorky** _(sample bias)_ je zvyčajne prítomná v hodnotách dát. Príkladom môže byť náborový algoritmus trénovaný na databáze, v ktorej sú nadmerne zastúpení muži, čo následne vedie k vylúčeniu žien.

-   **Stereotypná zaujatosť** _(stereotype bias)_ je tendencia konať s odkazom na sociálnu skupinu, ku ktorej patríme. Istá štúdia napríklad ukázala, že ženy skôr zvyknú klikať na pracovné ponuky, ak ich vnímajú ako ľahšie dosiahnuteľné pre ženy.

-   **Zaujatosť spôsobená vynechaním premennej** _(omitted variable bias)_ vzniká v dôsledku problémov s reprezentáciou alebo zakódovaním určitého faktora v dátach. Môže napríklad vzniknúť v dôsledku toho, že je ťažké nájsť faktické kritériá na meranie emocionálnej inteligencie – tento rozmer v náborových algoritmoch chýba.

-   **Zaujatosť pri výbere** _(selection bias)_ je spôsobená vlastnosťami vzorky vybranej na vyvodenie záverov. Napríklad banka vypočítava úverové skóre pomocou interných údajov, pričom sa zameriava na ľudí, ktorí pôžičku získali alebo nezískali, ale ignoruje tých, ktorí si nikdy nepotrebovali požičať.

Algoritmická zaujatosť je hlavne vecou uvažovania. Tvorcovia umelej inteligencie vnášajú ju môžu do svojich výtvorov vnášať neúmyselne aj úmyselne.

Štúdia EPRS uvádza dva konkrétne príklady: *„Predstavte si symbolický AI algoritmus na posudzovanie žiadostí o prijatie do zamestnania. Mohol by kandidátov hodnotiť priraďovaním bodov len na základe ich vzdelania a skúseností. Ak však nezohľadní ďalšie faktory, ako je napríklad materská dovolenka, alebo neuzná vzdelanie získané v zahraniční rovnako úspešne ako ľudské výberové komisie, algoritmus by mohol diskriminovať ženy a zahraničných kandidátov.“*

*„Teraz si predstavte podobný AI nástroj v rámci paradigmy strojového učenia. Takéto algoritmy si nachádzajú vlastné spôsoby, ako v tréningových dátach identifikovať toho, aký typ kandidátov uspel. Na miestach s existujúcimi štrukturálnymi predsudkami vo výbere (napríklad ako dôsledok rasovej diskriminácie) si ich algoritmus môže osvojiť. Dokonca aj v prípade, že sa údaje o štátnej či etnickej príslušnosti z dát odstránia, strojové učenie dokáže šikovne nájsť zástupné ukazovatele v iných údajoch, ako je jazyk, poštové smerovacie číslo či škola – to všetko ktoré môže byť dobrým prediktorom etnicity.“*

## Tri hlavné riziká algoritmov

Rozlišujeme tri hlavné riziká algoritmov:[^3]

-   Prvým rizikom je **algoritmické uzavretie** (z angl. _confinement_), ktoré sa môže okrem iného týkať názorov, kultúrnych poznatkov či dokonca obchodných praktík. Algoritmy totiž napriek rešpektovaniu princípu spravodlivosti vystavujú používateľov internetu obsahu v závislosti od ich profilov a integrovaných parametrov. To platí najmä na stránkach s algoritmami na odporúčanie správ (napr. Facebook) alebo na stránkach s algoritmami na odporúčanie produktov (napr. Amazon).

-   Druhé riziko je, keď majú algoritmy **vplyv na všetky aspekty života jednotlivca**, od regulovania informácií pre investorov až po jeho stravovacie návyky, koníčky či dokonca zdravotný stav. Takéto sledovanie jednotlivcov môžeme považovať za formu dohľadu, ktorá je v konflike so samotnou podstatou individuálnej slobody.

-   Tretím rizikom je **potenciálne porušovanie základných práv**. Ide najmä o algoritmickú diskrimináciu v prípadoch, keď sa s ľuďmi v rovnakých alebo podobných situáciách zaobchádza horšie alebo inak než s inými osobami, a to na základe zreteľa, ktorý je vyslovene zakázaný zákonom. Týka sa to napríklad spravodlivosti algoritmov na hodnotenie kandidátov na zamestnanie, odporúčacích algoritmov či prediktívnych algoritmov strojového učenia. Problém diskriminačnej zaujatosti spôsobenej algoritmami sa týka viacerých oblastí, napríklad prijímania do zamestnania cez internet, súdnych rozhodnutí, rozhodnutí policajných hliadok či prijímania do škôl.

## Ako sa vysporiadať s rizikami dát a algoritmov?

Podľa R. Schwartza a kolektívu[^4] *„Zaujatosť nie je nič nové ani jedinečné pre umelú inteligenciu. V AI systéme nie je možné dosiahnuť nulové riziko zaujatosti.“* 
Ak uznáme, že pre AI agentov je istá miera subjektivity prirodzená, budeme schopní zabezpečiť, aby sa využívali len na úlohy, na ktoré sú dostatočne dobre vybavení.

Štúdia EPRS končí niekoľkými odporúčaniami k používaniu AI aplikácií:

-   Pochopte koncepty zaujatosti a subjektivity
-   Vyhýbajte sa využívaniu AI nad rámec jej schopností
-   Vyhýbajte sa aplikáciám s nežiaducimi dopadmi
-   Zachovajte si ľudskú autonómiu
-   Hľadajte riešenia k problémom, nie problémy k riešeniam
-   Zamyslite sa, čo od AI skutočne chcete

[^1]: [Artificial intelligence: How does it work, why does it matter, and what can we do about it?](https://www.europarl.europa.eu/thinktank/en/document/EPRS_STU(2020)641547) - Philip Boucher, Scientific Foresight Unit (STOA) - ISBN: 978-92-846-6770-3 - Union Européenne, 2020

[^2]: [Algorithms, Data and Bias: Public Policy Needed](https://www.institutmontaigne.org/en/analysis/algorithms-data-and-bias-public-policy-needed?_wrapper_format=html), Anne Bouverot, Thierry Delaporte, 2019

[^3]: [D'où vient le risque ? Des données et des algorithmes](https://www.lemonde.fr/blog/binaire/2020/02/05/les-plateformes-numeriques-un-foyer-pour-les-risques-donnees-et-algorithmes/) - Serge Abiteboul, Thierry Viéville, 2020

[^4]: [Towards a Standard for Identifying and Managing Bias in Artificial Intelligence]
