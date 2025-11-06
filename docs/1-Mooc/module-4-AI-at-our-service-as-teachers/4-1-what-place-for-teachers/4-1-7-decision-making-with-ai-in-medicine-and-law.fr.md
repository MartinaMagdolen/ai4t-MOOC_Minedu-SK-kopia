---
názov: 4.1.7 Rozhodovanie pomocou umelej inteligencie v medicíne a súdnictve
opis: Objavte oblasti mimo vzdelávania, v ktorých systémy umelej inteligencie už zásadne zmenili spôsob rozhodovania.
---
??? info "Metadáta
    - Id: EU.AI4T.O1.M4.1.7t
    - Názov: 
    - Typ: text
    - Opis: Predmet: Umelá inteligencia pre učiteľov a pre učiteľov 
    - Predmet: Umelá inteligencia pre učiteľov a pre učiteľov
    - Autori: Mgr:
        - AI4T 
    - Licencia: CC BY 4.0
    - Dátum: 2022-11-15

# Rozhodovanie s umelou inteligenciou v medicíne a justícii

Pokiaľ ide o podporu rozhodovania, dve oblasti už majú za sebou históriu využívania umelej inteligencie: medicína a právo.  
Vzhľadom na dôležitosť rozhodnutí prijímaných v týchto oblastiach sú to zaujímavé príklady na štúdium.

## AI a medicína

"Umelá inteligencia je srdcom medicíny budúcnosti, s asistovanými operáciami, diaľkovým monitorovaním pacientov, inteligentnými protézami a personalizovanou liečbou založenou na veľkých objemoch údajov"[^1].

Približne pred päťdesiatimi rokmi bol v oblasti diagnostiky vyvinutý jeden z najznámejších expertných systémov: MYCIN.  
"Bol to jeden z prvých expertných systémov, ktorý využíval umelú inteligenciu na identifikáciu baktérií zodpovedných za závažné infekcie, ako je bakteriémia a meningitída, a na odporúčanie antibiotík, ktorých dávka sa upravovala podľa telesnej hmotnosti pacienta"[^2].

Systém MYCIN vyvíjaný od roku 1972 dokázal o 6 rokov neskôr prekonať lekárov v presnej diagnostike. V rámci celoplošného testu mali MYCIN a 9 lekárov, stážistov a akademikov, stanoviť diagnózu a predpísať lieky 80 pacientom trpiacim meningitídou. Diagnózy a predpisy potom naslepo vyhodnotilo 8 špecialistov na meningitídu a ...... MYCIN dosiahol lepšie výsledky ako ľudskí odborníci.

V súčasnosti je dôležitou oblasťou využitia strojového učenia na lekárske účely analýza obrazu na lekárske diagnózy [^3]. Pozrime sa v krátkosti na to, ako to funguje, ako to vysvetlil Gaël Varoquaux, výskumník spoločnosti Inria AI:

"Strojové učenie je jedným z odvetví umelej inteligencie (AI). Vo francúzštine znamená automatické učenie. Stručne povedané, táto technika zahŕňa podávanie tisícov príkladov softvéru, aby sa naučil vykonávať klasifikačné úlohy. Napríklad vyhľadávanie psov alebo mačiek na obrázkoch. Znamienka alebo zhubné melanómy. Teoreticky sa tak otvára celý nový svet medicínskych aplikácií. Napríklad röntgenové snímky tisícov pacientov trpiacich rovnakým ochorením sú zhromaždené v tzv. kohorte. Na základe týchto tréningových údajov potom počítač rozpozná rovnaké vizuálne charakteristiky na nových snímkach zhotovených počas vyšetrenia iných ľudí. Toto sú cieľové údaje*"[^4].

## Umelá inteligencia a spravodlivosť

V oblasti spravodlivosti boli identifikované dve hlavné použitia systémov umelej inteligencie.

Prvým sú nástroje na podporu rozhodovania. Systém AI môže pomôcť sudcovi pri vyšetrovaní prípadu, napríklad tým, že ho informuje o všetkých rozsudkoch, ktoré vyniesli príslušné súdy v podobných prípadoch. V tomto prípade AI zlepšuje vyhľadávanie informácií, ale rozhodnutie prijíma sudca sám[^5].

Potom existujú nástroje schopné predvídať rozhodnutia. V tomto prípade AI navrhuje právne rozhodnutie priamo sudcovi[^6]. Softvér analyzuje veľké množstvo príkladov súdnych rozhodnutí a "automaticky" z nich odvodzuje pravidlá rozhodovania. Vznik prediktívnej justície vyvoláva mnohé obavy.

Hoci "uplatňovanie umelej inteligencie v oblasti justície môže prispieť k zvýšeniu jej účinnosti a kvality" [musí] "byť vykonávané zodpovedne a v súlade so základnými právami"[^7]. Na európskej úrovni bola v roku 2018 prijatá Etická charta o používaní umelej inteligencie v justičných systémoch a ich prostredí.

Je usporiadaná okolo 5 zásad a uznáva sa v nej dôležitosť nediskriminácie, dodržiavania základných práv, kvality, bezpečnosti, transparentnosti, nestrannosti a spravodlivosti.

Napokon sa v nej zdôrazňuje zásada "kontroly používateľa": "vylúčenie normatívneho prístupu a zabezpečenie toho, aby používatelia boli informovaní a mali kontrolu nad svojimi rozhodnutiami" [^7].

V oblasti práva, rovnako ako vo vzdelávaní alebo medicíne, môže podpora pri rozhodovaní, ktorú poskytuje systém umelej inteligencie, zlepšiť prijaté rozhodnutie. Vzhľadom na možné dôsledky tých istých rozhodnutí je zachovanie ľudskej kontroly dôležitou otázkou pre vývoj systémov UI v nasledujúcich rokoch.

Všetci používatelia musia byť schopní kriticky využívať rozhodnutia navrhované systémami UI. Napríklad pri odhaľovaní niektorých druhov rakoviny sú systémy tak dobre vycvičené na určité vizuálne charakteristiky, že pri týchto prejavoch stanovujú vynikajúcu diagnózu, ale ostatné už nie sú schopné rozpoznať. Stále potrebujete oko lekára, aby ste videli to, čo dobre vycvičená AI prehliadla.

[^1]: Výňatok z francúzskeho článku [Intelligence artificielle et santé : Des algorithmes au service de la médecine] (https://www.inserm.fr/dossier/intelligence-artificielle-et-sante/) - stránka francúzskeho Národného inštitútu pre zdravie a lekársky výskum (konzultované 23. 8. 2022).

[^2]: [Mycin](https://en.wikipedia.org/wiki/Mycin), článok na Wikipédii (konzultované 23/08/2022).

[^3]: Varoquaux, G., Cheplygina, V. - článok v angličtine ["Machine learning for medical imaging: methodological failures and recommendations for the future"](https://doi.org/10.1038/s41746-022-00592-y). *npj Digit. Med.* 5, 48 (2022).

[^4]: Varoquaux, G. - [Imagerie médicale: l'intelligence artificielle peut-elle tenir ses promesses?](https://www.inria.fr/fr/imagerie-medicale-intelligence-artificielle-apprentissage-automatique) - rozhovor na webovej stránke spoločnosti Inria (konzultované 23. 8. 2022).

[^5]: V tomto prípade ide o "rozšírenie rozhodovania" alebo "podporu rozhodovania", ako sa uvádza v predchádzajúcej časti o "rozhodovaní pomocou AI".

[^6]: V tomto prípade ide o "automatizáciu rozhodovania", ako sa uvádza v predchádzajúcej časti o "rozhodovaní s AI".

[^7]: Výňatok z [Európskej etickej charty pre používanie umelej inteligencie v súdnych systémoch](https://www.coe.int/fr/web/cepej/cepej-european-ethical-charter-on-the-use-of-artificial-intelligence-ai-in-judicial-systems-and-their-environment)- webová stránka Európskej komisie pre efektívnosť justície (prístup 29.8.2022).
