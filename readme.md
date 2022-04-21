_(odpusťe mi prosím některé překlepy ve slovech :) )_

Zhruba 3 hodiny jsem strávil lámaním si hlavy nad tím co za aplikaci vytvořit. Co by bylo tak světoborného, že to ještě nikdy nikoho nenapadlo, a zároveň by to mohl vymyslet student 4. ročníku jako jsem já. Skrze pár nápadů jsem si uvědomil, jak moc komplikované některé aplikace vlastně jsou a že musím být realista. Rád bych vám tedy představil název mé, spíše než aplikace, hry.
# __ŠIBENICE__ #
Prověřte své znalosti! Máte všeobecný přehled? Vyzkoušejte zda otázkám dokážete čelit nebo vás takzvaně "_zabijou_".
## Pravidla hry ##
- Hra vám nabídne domovskou obrazovku, skrz kterou si lze vybrat typ obtížnosti (lehká, střední, těžka) dle typu obtížnosti se vám budou následně zobrazovat příslušné otázky.
- Po vybrání typu obtížnosti, se vám v horní části zobrazí otázka a pod ní příslušný počet políček pro doplnění písmen.
- Do políček lze doplňovat písmena.
- Při doplňování pouze správných písmen (v případě, že víme rovnou celé slovo) i slov, se výsledná tajenka zobrazí na zeleném pozadí a zobrazí se vám tlačítko "__DALŠÍ__", kterým se vám vygeneruje nová otázka.
- Při špatném doplnění písmene se však začne kreslit obrys oběšence. Nejprve __kopec__, poté __stožár__, poté __rameno__, poté __hák__, poté __smyčka__ a nakonec samotný __oběšenec__. Znamená to tedy, že máte 6 životů.
- V ten moment se na červeném pozadí zobrazí výsledná tajenka a stisknutím tlačítka "__NOVÝ__" se vám spustí nová otázka.
### Doplňující pravidla ###
- Pokud máte již nakreslený například __kopec__ a __rameno__ ale slovo následně uhádnete, tak se vám váš obrys nenuluje, ale přenáší se k další otázce.
## Funkce ##
- Menu - výběr obtížnosti.
- Ze hry se lze pomocí šipky vrátit do menu a změnit typ obtížnosti.
- Tlačítkem "__NOVÝ__" lze vynulovat postup a vygenerovat novou otázku.
- Otázky nelze přeskakovat.

## Vizuál hry ##
![GitHub Logo](uvodni.png)
- __Úvodní obrazovka__ - _vybereme typ obtížnosti: lehká_

### 1. možnost vývoje hry ###
![GitHub Logo](zacatek_hry.png)
- __Hrací pole__ - _hádáme jméno, typujeme různá písmena a už jsme se jednou mýlili, proto máme obrys __kopce__._

![GitHub Logo](/postup_hry.png)
- _stále hádáme tajenku a už jsme se 4x mýlili. Vidíme proto __kopec__, __stožár__, __rameno__ a __háček__._

![GitHub Logo](/prohra_hry.png)
- _vidíme __oběšence__, což značí, že jsme se již 6x mýlili_
- _zobrazuje se nám správná tajenka a hra pro nás končí_

### 2. možnost vývoje hry ###
![GitHub Logo](/hra_vyhra.png)
- _vidíme, že jsme se již 4x spletli ale najednou se nám podařilo tajenku správně uhádnout_
- _klikneme tedy na tlačítko další, abychom se posunuli na další otázku_

![GitHub Logo](/hra_vyhra_prohra.png)
- _jelikož se nám zachoval náš obrys, máme už jen 2 životy_
- _jelikož však neuhádneme tajenku, zobrazuje se nám po dalších 2 chybách __oběšenec__._

## Otázky ##
Jelikož jsou tři kategorie obtížnosti otázek, bude nutné udělat dostatečný počet otázek, aby nenastávalo jejich opakování.
Zde jsou 3 příklady od každé obtížnosti
### Obtížnost: Lehká ###
- Příjmení českého basketbalisty hrajícího v NBA za Chicago Bulls? - SATORANSKÝ
- Vyhrála 2 zlaté medaile ve dvou odlišných disciplínách na OH 2018. Doplňte její křestní jméno. - ESTER
- Přijmení držitele nejvíce ocenění "Český Slavík"  - GOTT

### Obtížnost: Střední ###
- Rok potopení Titaniku. - 1912
- Křestní jméno herce Agenta007 v letech 2006 - 2021 - DANIEL
- Hlavní město Albánie - TIRANA

### Obtížnost: Těžká ###
- Hlavní město Austrálie - CAMBORA
- Nejjižnější mys amerického kontinentu - HORN
- Přijmení Boženy Němcové za svobodna - PANKLOVÁ

## Logo hry ##
U hry je dle mého názoru důležitá její přehlednost a logika. Zárovň je dobré, aby ji lidé měli spojenou s nějakým zpamatovatelným symbolem. Já jsem pro hru __ŠIBENICE__ vymyslel toto logo.

![GitHub Logo](/logo.jpg)

## Kódovací proces ##
Samotné nakódování stránky bude vyžadovat i krom jazyku HTML a CSS i nějaký jiný, skrz který dokážeme nastavit věci jako generování otázek a systém vyhodnocování. (Na mysli mám např. Python, Javu nebo C / C ++.)
Důležité bude nakódování funkčního systému, který se možná bude co se týče náročnosti v průběhu tvorby trochu měnit.
Přidání obrysů oběšence bych řešil pomocí SVG objektů.
Tuto část bych již plně svěřil do rukou kódera, který má již dříve zmiňované vizuální podklady a teorii. Z pohledu designéra však můžu ke tvrobě přispět například výběrem barev.
- #B50000 (opacity 60%)
- #000000 (opacity 80%)
- #FFFFFF
- #707070
- #42B500 (opacity 60%)

## Slova na závěr ##
Aplikace bude potřebovat více a více nových otázek, takže největší starost vidím s jejich vymýšlením. Nicméně věřím, že funkčí aplikace by mohla leckoho zaujmout. Byla by ke stažení na Google Play i App Storu. 
