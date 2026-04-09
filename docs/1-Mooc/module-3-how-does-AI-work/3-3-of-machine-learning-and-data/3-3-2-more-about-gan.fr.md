---
názov: "3.3.2 Generatívne adversariálne siete (GAN)"
popis: "Ďalšie informácie o sieťach GAN"
prispievateľ: "Mooc IAI"
---
??? info "Metadáta
    - Id: EU.AI4T.O1.M3.3.2t
    - Názov: 3.3.2 Generatívne adversariálne siete (GAN)
    - Typ: text
    - Opis: Ďalšie informácie o sieťach GAN
    - Predmet: Umelá inteligencia pre učiteľov a od učiteľov
    - Autori:
        - AI4T 
        - Mooc IAI
    - Licencia: CC BY 4.0
    - Dátum: 2022-11-15

# Generatívne adversariálne siete (GAN)
Generatívne adversariálne siete stoja na pomedzí učenia bez dohľadu a učenia s dohľadom (pri ktorom poskytujeme vstupné dáta so známym požadovaným výstupom, čo nám pomáha odhadnúť vzťah medzi vstupom aj mimo tréningových vzoriek).

Ak sú k dispozícii len vstupné dáta a cieľom je odhaliť v nich určité štruktúry (napríklad počet parametrov, ktoré ich charakterizujú), môžeme využívať množstvo ďalších paradigiem. Napríklad pri **učení s polovičným dohľadom** tieto dva prístupy kombinujeme: dáta so známym požadovaným výstupom miešame s inými dátami, pri ktorých požadovaný výstup nepoznáme.

Ďalšou paradigmou je **učenie so samostatným dohľadom**, pri ktorom sa pomocou vstupných dát hľadá externý mechanizmus na generovanie príslušných výstupov. Cieľom tohto prístupu je ušetriť veľké množstvo ľudského úsilia potrebné na zadávanie požadovaného výsledku pre každý vstup, napríklad pri ručnom označovaní obrázkov pixel po pixeli (ak napríklad chceme zistiť, kde sa na obrázku nachádza mačka). Ďalej sa dá využiť na naučenie umelej inteligencie automaticky vyfarbovať obrázky: začneme s farebnými obrázkami, prevedieme ich do čiernobielej podoby a následne mechanizmus trénujeme tým, že mu poskytneme požadované farebné obrázky. Tie sú v tomto prípade známe bez toho, aby sme museli každý čiernobiely obrázok prácne prevádzať späť do jeho farebnej verzie.
 
Tento postup funguje aj vtedy, keď chceme umelú inteligenciu naučiť relatívnu polohu prvkov na orezanom obrázku alebo jej chceme pomôcť pochopiť časovú nadväznosť vo videu. Nefunguje však na všetko. Dá sa použiť všade tam, kde nájdete spôsob, ako automaticky vygenerovať požadované vstupy a výstupy priamo z dostupných dát. **Ide v podstate o druh učenia bez dohľadu, ktoré automaticky generuje dáta pre paradigmu učenia s dohľadom.**
