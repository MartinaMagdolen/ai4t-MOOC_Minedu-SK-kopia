---
názov: "3.3.4 Odkiaľ pochádza riziko?
opis: Identifikujte rôzne typy rizika
---
??? info "Metadáta
    - Id: EU.AI4T.O1.M3.3.3t
    - Názov: "3.3.3: 
    - Typ: text
    - Opis: Predmet: Umelá inteligencia pre učiteľov a pre učiteľov 
    - Predmet: Umelá inteligencia pre učiteľov a pre učiteľov
    - Autori: Mgr:
        - AI4T 
    - Licencia: CC BY 4.0
    - Dátum: 2022-11-15


# Odkiaľ pochádza riziko?
Vo svojej štúdii o umelej inteligencii [^1] vedecká prognostická jednotka Európskeho parlamentu (STOA) uviedla: "*Dôležité je poznamenať, že algoritmy umelej inteligencie nemôžu byť objektívne, pretože rovnako ako ľudia si v priebehu svojho výcviku vytvoria spôsob, ako dať zmysel tomu, čo už videli, a tento "pohľad na svet" používajú na kategorizáciu nových situácií, ktoré sú im predložené.*"

Pozrime sa na to, odkiaľ pochádza subjektivita umelej inteligencie a aké sú s ňou spojené riziká.

## Predsudky v údajoch a algoritmoch

Tak ako pri každom digitálnom systéme, aj údaje používané v platformách založených na AI pochádzajú z rôznych zdrojov a majú viacero formátov. Nesú so sebou rôzne typy zaujatosti[^2]. Predpojatosti údajov majú prevažne štatistický charakter. Uvádzame niekoľko príkladov.

- Skreslenie údajov** je vo všeobecnosti prítomné v hodnotách údajov. Napríklad náborový algoritmus vycvičený na databáze, v ktorej sú nadmerne zastúpení muži, vylúči ženy.

- Stereotypné skreslenie** je tendencia konať s ohľadom na sociálnu skupinu, do ktorej človek patrí. Napríklad jedna štúdia ukazuje, že ženy majú tendenciu klikať na pracovné ponuky, o ktorých si myslia, že ich ako ženy ľahšie získajú.

- Predpojatosť vynechanej premennej** (modelovanie alebo kódovanie) je predpojatosť spôsobená ťažkosťami pri reprezentácii alebo kódovaní faktora v údajoch. Napríklad, keďže je ťažké nájsť faktické kritériá na meranie emocionálnej inteligencie, tento rozmer v náborových algoritmoch chýba.

- Skreslenie výberu** je spôsobené charakteristikami vzorky vybranej na vyvodenie záverov. Napríklad banka použije interné údaje na stanovenie úverového skóre, pričom sa zameria na ľudí, ktorí získali alebo nezískali úver, ale ignoruje tých, ktorí si nikdy nepotrebovali požičať, atď. Výberové skreslenie je spôsobené charakteristikami vzorky vybranej na vyvodenie záverov.

Algoritmické skreslenie je predovšetkým otázkou argumentácie. Toto skreslenie zavádzajú inžinieri umelej inteligencie, či už úmyselne, alebo inak.

V už spomínanej štúdii Výskumnej služby Európskeho parlamentu sa uvádzajú dva konkrétne príklady: "*Uvažujte o symbolickom algoritme AI na skúmanie žiadostí o zamestnanie. Mohol by hodnotiť uchádzačov tak, že by im prideľoval známky výlučne na základe ich vzdelania a skúseností. Ak však nezohľadní faktory, ako je materská dovolenka, alebo primerane neuzná štúdium na zahraničných inštitúciách, ako by to urobili ľudské výberové komisie, algoritmus by mohol diskriminovať ženy a zahraničných uchádzačov.*"

"*Uvažujme teraz o podobnom nástroji umelej inteligencie v rámci paradigmy ML (Machine Learning). Tieto algoritmy nachádzajú vlastné spôsoby identifikácie typov uchádzačov vybraných v ich trénujúcich údajoch. Ak v minulosti existovali štrukturálne predsudky v týchto výberoch - napríklad rasová diskriminácia - algoritmus sa ich môže naučiť. Dokonca aj keď sa z údajov odstráni národnosť alebo etnická príslušnosť, ML dokáže nájsť náhrady za základné vzory v iných údajoch, ako sú jazyky, poštové smerovacie čísla alebo školy, ktoré môžu byť dobrými prediktormi etnickej príslušnosti.*"

## Tri aspekty algoritmického rizika

Algoritmické riziko možno charakterizovať tromi spôsobmi[^3].

- Po prvé, ide o **algoritmické uzamknutie**, ktoré môže ovplyvniť aj názory, kultúrne znalosti alebo dokonca obchodné postupy. V skutočnosti algoritmy konfrontujú používateľov internetu s rovnakým obsahom v závislosti od ich profilu a integrovaných parametrov, a to napriek dodržiavaniu zásady spravodlivosti. To je prípad stránok s odporúčaním správ niektorých sociálnych sietí alebo stránok s odporúčaním produktov, ktoré používajú napríklad online predajcovia.

- Druhý aspekt algoritmického rizika súvisí s **kontrolou všetkých aspektov života jednotlivca**, od regulácie informácií pre investorov až po ich stravovacie návyky, záľuby alebo zdravotný stav. Toto sledovanie jednotlivca naznačuje formu dohľadu, ktorá je v rozpore so samotnou podstatou slobody jednotlivca.

- Tretí sa týka **potenciálneho porušenia základných práv**. Konkrétne ide o algoritmickú diskrimináciu definovanú ako nepriaznivé alebo nerovnaké zaobchádzanie v porovnaní s inými osobami alebo inými rovnakými alebo podobnými situáciami na základe dôvodu výslovne zakázaného zákonom. Patrí sem štúdia spravodlivosti algoritmov hodnotenia (triedenie ľudí hľadajúcich prácu online), odporúčacích algoritmov a algoritmov prediktívneho učenia. Problém diskriminačnej zaujatosti vyvolanej algoritmami sa týka viacerých oblastí, napríklad náboru zamestnancov online, súdnych rozhodnutí, rozhodnutí policajných hliadok a prijímania na školy.

### Ako môžeme riadiť riziká spojené s údajmi a algoritmami?

Podľa R. Schwartz a kol[^4], "*Predpojatosť nie je pre umelú inteligenciu ani nová, ani jedinečná a nie je možné dosiahnuť nulové riziko zaujatosti v systéme umelej inteligencie*".  
Zatiaľ je uznanie skutočnosti, že agenti UI sú vo svojej podstate subjektívni, kľúčovým predpokladom na zabezpečenie toho, aby sa používali len na úlohy, na ktoré sú vhodní.

V závere štúdie EPRS sa uvádza niekoľko odporúčaní pri používaní aplikácií založených na UI:

- Pochopiť zaujatosť a subjektivitu

- Vyhýbajte sa aplikáciám, ktoré presahujú možnosti umelej inteligencie

- Vyhýbanie sa aplikáciám s nežiaducimi účinkami

- Zachovanie autonómie človeka

- Hľadanie riešení problémov, nie problémov riešení

- Premýšľajte o tom, čo od umelej inteligencie skutočne chceme

[^1]: Štúdia v angličtine: [Artificial intelligence: How does it work, why does it matter, and what can we do about it?](https://www.europarl.europa.eu/thinktank/en/document/EPRS_STU(2020)641547) - Philip Boucher, Scientific Foresight Unit (STOA) - ISBN: 978-92-846-6770-3 - Európska únia, 2020

[^2]: [Algoritmy, údaje a zaujatosť: aké verejné politiky?](https://www.institutmontaigne.org/analyses/algorithmes-donnees-et-biais-quelles-politiques-publiques?_wrapper_format=html), Anne Bouverot, Thierry Delaporte, 2019

[^3]: [Odkiaľ pochádza riziko? údaje a algoritmy](https://www.lemonde.fr/blog/binaire/2020/02/05/les-plateformes-numeriques-un-foyer-pour-les-risques-donnees-et-algorithmes) - Serge Abiteboul, Thierry Viéville, 2020

[^4]: Článok v angličtine: ["Towards a Standard for Identifying and Managing Bias in Artificial Intelligence"](https://doi.org/10.6028/NIST.SP.1270) - Reva Schwartz, Apostol Vassilev, Kristen Greene, Lori Perine, Andrew Burt, NIST Special Publication 1270 , 2022
