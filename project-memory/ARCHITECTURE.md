# Architecture

## Současné uspořádání

Jeden knižní projekt = jeden repozitář. PROJECT.md je bootstrap. project-memory/ drží kanonickou znalost projektu; docs/ podrobnou provenienci a redakční rozbory.

Texty mají dvě oddělené vrstvy podle D015:
- **texts/** — zachované historické zdroje, pracovní výběr, varianty, fragmenty a zadání.
- **manuscript/** — místo pro nově skládanou a redigovanou podobu knihy; nyní README bez kapitol.

## Tok práce

Historický zdroj → import s proveniencí do texts/ → redakční porovnání v docs/ → autorská domluva o výběru → skládání a editace v manuscript/ → schválený rukopis → sazba → vydané artefakty.

Produkční nástroj, místo produkčních souborů a exportní workflow nejsou určeny.

## Textová struktura

Šest kořenových textů v texts/ je historický pracovní výběr, nikoli přednostně schválený rukopis. texts/podklady/<téma>/ obsahuje varianty, rozpracování a úryvky. Tematické README a texts/README.md jsou navigace. Názvy souborů ani historická čísla kapitol neurčují budoucí pořadí.

Osnovy jsou v texts/podklady/osnovy/, doprovodné texty v texts/podklady/propagace/. E15 zůstává příbuznou tvorbou mimo knihu. Drobné zásobníky mají stabilní ID Mxxx pro úseky E01 a Vxxx pro neúplné výňatky E02; texts/DROBNE_TEXTY.md je rejstřík.

[Redakční průchod](../docs/EDITORIAL_REVIEW.md) porovnává celý dostupný soubor. Jeho doporučení nejsou schválením variant ani osnovy. manuscript/ bude držet jednu aktuální textovou podobu; přesná struktura souborů se určí až při výběru.

## Kontrakty

- Při skládání rukopisu nepřesouvat ani literárně nepřepisovat archivní předlohy v texts/.
- Literární úpravy vybraných textů provádět v manuscript/ a verzovat Gitem, bez FINAL2.
- U složeného textu vést v docs/ odkazy na použité předlohy a odlišit nově dopsané pasáže. Nevydávat novou syntézu za obnovený historický text.
- Případnou opravu v sazbě vrátit do manuscript/ jako textového content masteru.
- Import není schválení; úplná zpráva nemusí být celou kapitolou. Dva soubory mohou mít shodné literární tělo.
- PDF import nezaručuje původní typografii. Zlomy a překlepy archivu neopravovat v rámci literární redakce rukopisu.
- docs/SOURCE_CATALOG.md drží původ, docs/EDITORIAL_REVIEW.md redakční zjištění, CURRENT_STATE současný stav.

## Externí a produkční systémy

Historické exporty jsou identifikované v katalogu. Nová práce nemá záviset na opětovném hledání chatu. Databáze, server ani webová aplikace nejsou součástí architektury. Sazba, archiv vydání a nezávislý backup TBD.
