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
- Datum: 2026-07-30; stav: ACTIVE.
- Rozhodnutí: úvod má zvát ke čtení; první kapitola má nést prožitek noci. Neopakovat stejný mechanismus v obou.
- Důvod: autor upozornil na opakování.
- Zdroj: E02; úplný pozdější přepis první kapitoly nebyl obnoven.

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
- Důsledky: dosavadních šest souborů přesunuto ze source/manuscript/ do texts/; texts/README.md je pouze navigace. Obsah kapitol se tím nemění. Upřesňuje úložnou cestu D008.
- Zdroj: explicitní zadání autora v konverzaci 2026-10-11.
