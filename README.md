# msus-zadanie1

Náplňou semestrálneho projektu je vytvoriť procesnú aplikáciu pomocou modelovacieho jazyka Petriflow v poskytnutom aplikačnom servery (https://engine.petriflow.com).

Proces
Cieľom projektu je namodelovať/implementovať procesne riadenú aplikáciu pozostávajúcu z jedného procesu. Aplikácia musí spĺňať tému, ktorú ste si zvolili (viď tabuľku: https://uim.fei.stuba.sk/predmet/i-msus/).
Aby bol proces uznaný ako vypracovanie témy musí spĺňať všetky nasledovné podmienky:
Proces musí obsahovať aspoň 1 TaskRef data field (postačuje "statický", t.j. má nastavenú iniciálnu hodnotu a jeho hodnota sa počas behu procesu nemusí meniť).
Proces musí obsahovať aspoň jeden data field typu enumeration, alebo emuration_map, alebo multichoice, alebo multichoice_map.
Proces sa musí začínať práve jedným miestom s práve jedným tokenom (pre uľahčenie modelovania aj testovania).
Proces musí obsahovať minimálne 10 taskov (spustiteľných prechodov, t.j. minimálne 10 prechodov živosti L1).
Proces musí obsahovať aspoň jedno "rozhodnutie" (t.j. aspoň jeden XOR split, .t.j konštrukt kedy sú spustiteľné dve a viac prechod v jeden moment a systém/user musí rozhodnúť ktorý spustiť).
Spustenie rozhodnutia (t.j. spustenie jedného prechodu v rozhodnutí) musí byť automatizované pomocou akcií (viď. builder -> action edit -> functions -> async run with execution of task).
Proces musí obsahovať akcie, ktorými je menené:
    - zmena správania dátovej referencie (napríklad skrytie, alebo odkrytie, či zmena na editovateľný input vo formuláry)
    - nastavenie hodnoty (napríklad výpočet hodnoty, skladanie textu a ďalšie)
    - nastavenie možností (nastavenie možností pre enumeration/enumeration_map, alebo mutlichoice/multichoice_map data field) 

Sprievodné video
Spolu s procesmi vypracované v jazyku Petriflow, ktoré sú aj nasadené na poskytnutom aplikačnom servery (engine) je potrebné odovzdať aj .
Sprievodné video má pozostávať z dvoch častí:
predstavenie siete, ukázanie jej fungovania (odsimulovanie), ukážka niektorých dôležitých častí procesu (nastavenie rolí, akcie apod.)
ukážka nasadeného procesu na servery a prejdenie aspoň jedného prípadu použitia, na ktorom je demonštrovaná funkčnosť procesnej aplikácie
Video musí mať maximálne dĺžku 6 minút. Video musí byť odovzdané vo formáte mp4.


Odovzdanie
V rámci projektu treba odovzdať tri súbory:
XML súbor zdrojového kódu implementovaného procesu
SVG obrázok procesu (je možné exportovať rovno z builder aplikácie)
MP4 6min video vysvetlenia a preklikania procesu (podľa inštrukcií vyššie)
V prípade otázok pokojne píšte na Discord.
