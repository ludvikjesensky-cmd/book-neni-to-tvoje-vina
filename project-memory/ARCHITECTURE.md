# Architecture

## Současné uspořádání
Jeden knižní projekt = jeden repozitář. PROJECT.md směruje k project-memory/ a source/manuscript/. Kanonická paměť popisuje projekt; editovatelné texty jsou samostatný content master.

## Tok práce
Historické podklady → ověřený import s proveniencí → autorská editace textových zdrojů → schválený rukopis → sazba → vydané artefakty.
První dvě fáze jsou zahájeny. Produkční nástroj, místo produkčních souborů a exportní workflow nejsou určeny.

## Textová struktura
V source/manuscript/ jsou stabilně pojmenované soubory podle témat. Jejich názvy ani historická čísla v katalogu neurčují finální pořadí.
Každý nynější text má hlavičku s původem a označením pracovního importu. Finální lineární obsah dosud neexistuje.
Koncepční opory: noční sebeodsuzování, sdílenost, rozlišení chyby a identity, hodná holčička/hodná žena, bolest obrácená proti sobě a závěrečné svolení k něze. Jejich finální členění zůstává otevřené.

## Kontrakty
- Textové opravy se dělají v content masteru a verzují Gitem; žádné FINAL2.
- Při opravě obsahu v sazbě přenést změnu zpět do content masteru.
- Návrh osnovy není schválený text a export konverzace není hotová kniha.
- PDF import nezaručuje původní typografii; řádkové zlomy jsou ponechány z extrakce.
- docs/SOURCE_CATALOG.md drží původ a identitu podkladů. CURRENT_STATE drží současný stav.
- Externí zdroj je historická evidence; nová práce už nemá záviset na opětovném hledání chatu.

## Externí a produkční systémy
Historický PDF export je v ChatGPT, identifikován v katalogu. Databáze, server ani webová aplikace nejsou součástí aktuální architektury. Sazba, archiv release a nezávislý backup TBD.
