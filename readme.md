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


![GitHub Logo](uvodni.png)
- __Úvodní obrazovka__ - _vybereme typ obtížnosti: lehká_

## 1. možnost vývoje hry ##
![GitHub Logo](zacatek_hry.png)
- __Hrací pole__ - _hádáme jméno, typujeme různá písmena a už jsme se jednou mýlili, proto máme obrys (__kopce__)_

![GitHub Logo](/postup_hry.png)
- _stále hádáme tajenku a už jsme se 4x mýlili. Vidíme proto (__kopec__, __stožár__, __rameno__ a __háček__)_

![GitHub Logo](/prohra_hry.png)
- _vidíme __oběšence__, což značí, že jsme se již 6x mýlili_
- _zobrazuje se nám správná tajenka a hra pro nás končí_

## 2. možnost vývoje hry ##
![GitHub Logo](/hra_vyhra.png)
- _vidíme, že jsme se již 2x spletli ale najednou se nám podařilo tajenku správně uhádnout_
- _klikneme tedy na tlačítko další, abychom se posunuli na další otázku_

![GitHub Logo](/hra_vyhra_prohra.png)
- _jelikož se nám zachoval náš obrys, máme už jen 4 životy_
- _jelikož však neuhádneme tajenku, zobrazuje se nám po dalších 4 chybách (__oběšenec__)_
