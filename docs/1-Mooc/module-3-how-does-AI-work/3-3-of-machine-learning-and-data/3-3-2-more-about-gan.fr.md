---
názov: "3.3.2 Generatívne antagonistické siete (GAN)" (vo francúzštine)
popis: Ďalšie informácie o sieťach GAN
prispievateľ: Mooc IAI
---
??? info "Metadáta
    - Id: EU.AI4T.O1.M3.3.2t
    - Názov: 3.3.2 Generatívne antagonistické siete (GAN)
    - Typ: text
    - Opis: Získajte viac informácií o GAN
    - Predmet: Umelá inteligencia pre učiteľov a pre učiteľov
    - Autori: Mgr:
        - AI4T 
        - Mooc IAI
    - Licencia: CC BY 4.0
    - Dátum: 2022-11-15

# Generatívne adverzné siete (GAN)
Generatívne adverzné siete ležia medzi učením pod dohľadom založeným na poskytovaní vstupných údajov, ktorých zodpovedajúci požadovaný výstup je známy, aby bolo možné odhadnúť vzťah medzi vstupom a výstupom nad rámec vzoriek poskytnutých na trénovanie, a učením bez dohľadu.

Ak sú k dispozícii len vstupné údaje s cieľom odhaliť určité štruktúry v údajoch (napríklad počet parametrov, ktoré ich charakterizujú), existuje mnoho ďalších paradigiem, napríklad **polovičný dohľad**, kde miešame údaje, pri ktorých poznáme požadovaný výstup, a iné údaje, pri ktorých ho nepoznáme, s cieľom zmiešať tieto dva prístupy.

Ďalšia paradigma, známa ako **samokontrolovaná**, spočíva v použití vstupných údajov na nájdenie externého mechanizmu na generovanie príslušného výstupu. Cieľom je vyhnúť sa obrovskému ľudskému úsiliu spojenému so zadávaním požadovaného výsledku pre každý vstup, napríklad ručným označovaním obrázkov, v prípade potreby pixel po pixeli (ak chceme zistiť, kde sa na obrázku nachádza mačka). Ďalším možným využitím by bolo naučiť sa automaticky vyfarbovať obrázky, pričom by sa začalo s farebnými obrázkami, zredukovalo by sa to na čiernobiele obrázky a potom by sa mechanizmus vycvičil tým, že by sa mu poskytli požadované farebné obrázky, v tomto prípade známe bez toho, aby sa museli rekonštruovať pre každý čiernobiely obrázok.
 
Tento postup funguje aj pri učení sa relatívnej polohy prvkov v obraze, ktorý bol vystrihnutý, alebo časovej nadväznosti vo videu. Nefunguje to však na všetko a zakaždým bude potrebné nájsť riešenie na automatické generovanie požadovaných vstupov a výstupov z údajov. **Jedná sa o druh učenia bez dohľadu, ktoré automaticky generuje údaje pre paradigmu učenia s dohľadom.
