# Decisions

Datace historických rozhodnutí pochází z vyhledávání rozhovorů; primární textové doklady tam, kde dostupné, odkazují na E01 v docs/SOURCE_CATALOG.md. Návrhy bez doloženého přijetí nejsou ACTIVE decisions.

## D001 — Název
- Datum: 2026-03-30; stav: ACTIVE.
- Rozhodnutí: „Není to tvoje vina“, běžná velikost písmen, nikoli verzálky.
- Důvod: autor potvrdil původní podobu.
- Zdroj: E02. Podtitul tím není rozhodnut.

## D002 — Slova, cesta a opakované čtení
- Datum: 2026-06-06; stav: ACTIVE.
- Rozhodnutí: literární cesta od bolesti k naději; slova místo předepsané formy dopisů; možnost číst jednu větu či stránku jako „lékárničku“.
- Důvod: kniha má podržet i ve chvíli, kdy čtenářka nemá sílu číst souvisle.
- Důsledky: samostatně použitelné pasáže, prostor, krátké části; žádný katalog všech vin.
- Zdroj: E01 s. 111–119.

## D003 — Pořadí prvních prožitků
- Datum: 2026-06 až 07; přesný den v PDF není doložen; stav: ACTIVE.
- Rozhodnutí: nejprve noční rozpoznání, potom úleva „nejsi sama“, následně vlídné pochopení.
- Důvod: autor tento postup výslovně přijal.
- Důsledky: princip návaznosti, nikoli fixace všech čísel kapitol.
- Zdroj: E01 s. 129–130.

## D004 — Každodenní i vztahové sebeodsuzování
- Datum: 2026-07-24; stav: ACTIVE.
- Rozhodnutí: zahrnout chybu v práci, zapomenutí, připálenou večeři, křik na dítě i vztahové bolesti.
- Důvod: autor upozornil, že běžná chyba se mění v „Já jsem úplně blbá / špatná“.
- Důsledky: starší texty revidovat; žádné omezení na ženy po rozchodu.
- Zdroj: E01 s. 181–185, 212–215.

## D005 — Dva mechanismy, ne univerzální vysvětlení
- Datum: 2026-07-24; stav: ACTIVE.
- Rozhodnutí: odlišit „udělala jsem chybu → já jsem špatná“ a „někdo mi ublížil → obrátím bolest proti sobě“.
- Důvod: metafora odložené bolesti nevysvětluje každou každodenní výčitku.
- Důsledky: odpovědnost se nepopírá; chyba není identita.
- Zdroj: E01 s. 185–189.

## D006 — Závěrečné svolení
- Datum: 2026-07-26; stav: ACTIVE.
- Rozhodnutí: závěr „Už nad sebou nemusíš vynášet rozsudek“ má nabídnout východisko bez rad a návodů, motiv „Dovol si…“ a něhu k sobě.
- Důvod: pouhé pojmenování bolesti nestačí, ale další úkol by šel proti účelu knihy.
- Důsledky: konkrétní počet závěrečných zastavení zůstává návrhem.
- Zdroj: E01 s. 203–212.

## D007 — Odlišit úvod a první kapitolu
- Datum: 2026-07-30; upřesněno 2026-10-11; stav: ACTIVE.
- Rozhodnutí: úvod má zvát k nepravidelnému čtení a používání knihy jako opory; první kapitola má nést noční prožitek. Neopakovat v obou výčet výčitek + titulní větu + „nemusíš tomu zatím věřit“.
- Důvod: autor upozornil, že tento mechanismus se opakuje a oslabuje účinek.
- Důsledky: úvod nemá začínat léčbou ani vysvětlováním. První kapitola má být primárně obrazná literatura bez výkladu mechanismu; titulní „Není to tvoje vina.“ může zaznít až na konci. Vysvětlení bolesti/viny patří do následujících kapitol. Titulní větu v celé knize používat střídmě jako refrén, ne jako slogan.
- Zdroj: E02; upřesnění a explicitní souhlas autora E09, texts/podklady/osnovy/e09-oddeleni-uvodu-a-prvni-kapitoly.md.

## D008 — GitHub jako domov projektu
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: book-neni-to-tvoje-vina drží textové zdroje, rozsah a stav; použít centrální GUIDANCE/CREATE_PROJECT.
- Důvod: autor požaduje systematickou práci a obnovitelný kontext.
- Důsledky: jeden PROJECT.md, jedna Project Memory; registrace v project-memory/projects.yaml; zdrojové texty oddělené od znalosti.
- Zdroj: explicitní zadání v této konverzaci. Technická realizace: Markdown content master, tematické názvy, provenience importů.

## Historické návrhy bez statusu rozhodnutí
Šest kapitol (2025), 14 mikrokapitol, sedmidílná/26kapitolová struktura, 34 kapitol i následných 12–15 kapitol byly pracovní varianty v různých fázích. Žádnou z nich tato inicializace nepovyšuje na finální obsah. Viz HISTORY a OPEN_QUESTIONS.

## D009 — Samostatná složka texts
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: všechny texty knihy ukládat v kořenové složce texts/, odděleně od projektové dokumentace.
- Důvod: autor požaduje přehledné oddělení projektu a kapitol.
- Důsledky: dosavadních šest souborů přesunuto ze source/manuscript/ do texts/; texts/README.md je pouze navigace. Obsah kapitol se tím nemění. Upřesňuje úložnou cestu D008. Pro další práci je rozdělení archivu a redigovaného rukopisu upřesněno D015.
- Zdroj: explicitní zadání autora v konverzaci 2026-10-11.

## D010 — Vytěžit i neschválené texty
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: obnovit maximum předchozího psaní včetně rozpracovaných a neschválených variant a přiřadit je k příslušným kapitolám/tématům.
- Důvod: autor chce maximálně využít předešlou práci.
- Důsledky: základní pracovní výběr zůstává; podklady obsahují odlišné zdrojové varianty, rozpracování a výňatky s proveniencí. Mezery se nevymýšlejí. Import není schválení literární ani faktické správnosti.
- Zdroj: explicitní zadání autora v této konverzaci.


## D011 — Kniha jako pohlazení a objetí, ne výčet bolestí
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: kniha jako celek nemá být jen výčtem bolestí. Má fungovat jako pohlazení a objetí; před konkrétními tématy má být prostor, který ženu nejprve drží, ujišťuje a odebírá část nesené viny.
- Důvod: autor to v této konverzaci výslovně formuloval: „Nechtěl bych, aby ta kniha byla jen výčtem bolestí. Proto tam chci tu úvodní část. Chci aby kniha byla pohlazením, objetím“.
- Důsledky: návrhy 37, 14 ani jiného počtu mikrokapitol nejsou samy o sobě kostrou knihy. Před další fixací osnovy je třeba posoudit celek a chybějící opěrné vrstvy.
- Zdroj: E06, texts/podklady/uvod/e06-autorske-zadani-a-uvodni-texty.md.

## D012 — Úvodní blok před konkrétními tématy
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: před konkrétními mikrokapitolami má být krátký blok, který 1) ukáže prožívání viny na obrazu ženy, 2) ujistí ji, že v tom není sama a že tento způsob sebeobviňování má širší naučený kontext, 3) připomene, že ne všechno, co nese, je její a ne každá bolest je její vina.
- Důvod: explicitní autorův návrh a následné potvrzení potřeby úvodní části.
- Důsledky: konkrétní znění tří textů E06 je pouze pracovní návrh asistenta. Rozhodnutí se týká funkce bloku, nikoli jeho definitivního textu, počtu stránek nebo přesného pořadí.
- Zdroj: E06, texts/podklady/uvod/e06-autorske-zadani-a-uvodni-texty.md.


## D013 — První noční kapitola má primárně rozpoznat, ne vysvětlit
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: při další redakci první noční kapitoly preferovat jednoduchost a prožitek původní verze; nevkládat do ní celý výklad mechanismu vnitřního soudu. Širší každodenní rovinu může nést úvod a následující kapitoly.
- Důvod: po přepracování na širší každodenní osu autor uvedl, že nová verze je „mnohem složitější než byla ta původní“ a začal váhat ve prospěch původní verze.
- Důsledky: E07 se nepřepisuje novější variantou; případné změny první kapitoly mají být chirurgické, nikoli úplná koncepční přestavba. Návrh sedmi kapitol první části v E08 zůstává pouze pracovní strukturou.
- Zdroj: E08, texts/podklady/osnovy/e08-prvni-cast-a-redakcni-rozhodovani.md.

## D014 — „Když láska bolí“ je příbuzná tvorba, ne automaticky rukopis knihy
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: konkrétní vztahová témata a texty rozvíjené pro kanál „Když láska bolí“ nejsou automaticky textem knihy „Není to tvoje vina“. Autor v této konverzaci výslovně uvedl: „Není to na knihu.“
- Důvod: autor hledá pro tuto větev spíše YouTube, podcast/audio a placenou vrstvu; současně chce mluvit především k ženám, se kterými jeho způsob psaní souzní.
- Důsledky: příbuzné texty lze archivovat jako zdroj hlasu, obrazů a distribučního kontextu, ale nesmějí být bez dalšího autorského rozhodnutí zařazeny do rukopisu nebo použity k fixaci osnovy. Výběr platformy Herohero vs. YouTube subscription není tímto rozhodnut.
- Zdroj: E15, `texts/podklady/propagace/e15-kdyz-laska-boli-souvisejici-autorsky-text.md` a `e15-publikum-forma-osobni-vazba.md`.

## D015 — Podklady zachovat, výsledný rukopis skládat v manuscript/
- Datum: 2026-10-11; stav: ACTIVE.
- Rozhodnutí: všechny dosavadní podklady nechat na místě; vytvořit manuscript/ pro výslednou podobu textu. Nejprve provést detailní redakční průchod, potom se s autorem dohodnout na dalších krocích.
- Důvod: autor chce bezpečně oddělit zachráněný materiál od skládané knihy.
- Důsledky: texts/ zůstává archivem, manuscript/ bude content master redigovaného rukopisu. Nyní obsahuje pouze README. Redakční posouzení v docs/EDITORIAL_REVIEW.md neuzavírá osnovu, výběr variant ani schválení textů. Literární editace předloh se do archivu nepromítají.
- Zdroj: explicitní zadání autora v této konverzaci: „Necháme všechny podklady na místě. Vytvoříme nový adresář manuscript/ … Udělej nejdřív detailní redakční průchod a pak se dohodneme na dalších krocích.“

## D016 — Nejprve struktura, potom skládání textů
- Datum: 2026-10-12; stav: ACTIVE.
- Rozhodnutí: nejdříve zafixovat strukturu knihy; následně do ní dosazovat zachráněné texty, myšlenky, metafory a vytvářet jednotlivé kapitoly podle jejich funkce.
- Důvod: autor chce soudržnou konstrukci před další prací na jednotlivých textech.
- Důsledky: docs/BOOK_STRUCTURE.md předkládá konkrétní návrh úvodu a patnácti kapitol v pěti částech. Jeho počet, pořadí a rozpočet zatím nejsou schválené; Q001/Q002 zůstávají otevřené. D016 schvaluje postup, nikoli automaticky tento nový návrh.
- Zdroj: přímé zadání autora v této konverzaci: „V prvním kroku bychom měli zafixovat strukturu knihy a pak do ní postupně dosazovat texty, myšlenky, metafory…“
