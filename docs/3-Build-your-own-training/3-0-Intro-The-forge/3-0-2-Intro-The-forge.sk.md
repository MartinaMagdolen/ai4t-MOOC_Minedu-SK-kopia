---
názov: "3.0.2 Forge a viacjazyčnosť
popis: Predstavenie AI4T forge a jeho podpory viacjazyčnosti - Online nástroj na spoluprácu na vzdelávacom obsahu.
prispievateľ: Marie, Collin - Inria
              Bénédicte, Cardon - Inria
              Laurence, Farhi - Inria
              Benoit, Rospars - Inria
---

## Čo je to kováčska dielňa?

"Software forge" [^forgedef] je pôvodne online nástroj na spoluprácu na softvérových projektoch. Môže sa používať aj širšie na spoločné úpravy a publikovanie digitálnych zdrojov (webových stránok, databáz, dokumentov kurzov atď.).

Forge ponúka :

- online úložisko súborov, ktoré možno synchronizovať s vlastným počítačom, aby boli údaje vždy k dispozícii;

- nástroje na správu verzií na sledovanie zmien;

- nástroje na spoluprácu na opravu chýb a navrhovanie nových nápadov;

- nástroje na vytváranie webových stránok, publikovanie softvéru online alebo transformáciu textových súborov na komplexné dokumenty (prezentácie, diagramy atď.).

Hoci forky využívajú najmä vývojári softvéru, komunita v oblasti vzdelávania a odbornej prípravy môže z tohto typu platforiem tiež výrazne profitovať. Forge [Digital Education Commons](https://forge.aeif.fr/framaka/que-la-forge-soit-avec-toi#quest-ce-quune-forge-){:target="_blank"} vytvorený Alexisom Kauffmannom teraz podporuje [francúzske ministerstvo školstva](https://www.education.gouv.fr){:target="_blank"}.

## Riešenie, ktoré podporuje a uľahčuje viacjazyčnosť

Na spoluvytváranie a distribúciu otvorených vzdelávacích zdrojov sa vo vzdelávacom laboratóriu Inria pravidelne používajú knižnice Git. Mali sme možnosť využiť toto riešenie na vytvorenie dvojjazyčných zdrojov pre Mooc [Environmental impact of digital technologies](https://learninglab.gitlabpages.inria.fr/mooc-impacts-num/mooc-impacts-num-ressources/en/index.html){:target="_blank"}.

Pre projekt AI4T sme potom prispôsobili našu metodiku na vytvorenie **viacjazyčného systému**. Mooc je teraz k dispozícii v 5 jazykoch.

## **Ako vytvoriť vlastný školiaci kurz, postup v 3 krokoch**

- Krok 1 - Rozdvojenie Mooc: Vytvorte si vlastný repozitár AI4T na GitHub.

- Krok 2 - Preklad zdrojov Mooc: Jednoduchá metodika prekladu textov a obsahu a kontrola výsledku.

- Krok 3 - Zobrazenie a zdieľanie: Zobrazenie vašich zdrojov na statickej webovej stránke a aktualizácia viacjazyčnej navigácie.

Teraz si môžete vytvoriť vlastný kurz!

**Upozorňujeme**, že hoci sme sa snažili čo najpresnejšie predstaviť jednotlivé fázy spojené s generovaním stránok Mooc v novom jazyku, odporúčame, aby sa na technickej časti (fork úložiska, generovanie textu v novom jazyku) podieľal vývojár alebo niekto, kto má skúsenosti s IT.
generovanie textu v cieľovom jazyku, aktualizácia súborov .py alebo .yml, generovanie statických webových stránok).

[^forgedef]: Opis Alexisa Kauffmanna vo francúzskej kovárni [La Forge des Communs Numériques Éducatifs](https://forge.aeif.fr/framaka/que-la-forge-soit-avec-toi#quest-ce-quune-forge-){:target="_blank"}
