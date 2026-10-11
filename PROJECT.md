# Není to tvoje vina

**ID:** book-neni-to-tvoje-vina · **Vlastník:** Ludvík · **Typ:** knižní projekt  
**Generace:** první kniha; redakční verze zatím neurčena.

Literární opora pro ženy, které z vlastní chyby nebo prožité bolesti dělají rozsudek nad sebou. Cesta od bolesti k naději, ke které se lze vracet po jednotlivých větách.

## Source of Truth a vstup
Tento repozitář: https://github.com/ludvikjesensky-cmd/book-neni-to-tvoje-vina  
Tento soubor je jediný bootstrap. Aktuální stav: [CURRENT_STATE](project-memory/CURRENT_STATE.md).

## Co číst
- Vždy: [SCOPE](project-memory/SCOPE.md), [CURRENT_STATE](project-memory/CURRENT_STATE.md).
- Před psaním/editací: [ARCHITECTURE](project-memory/ARCHITECTURE.md), [DECISIONS](project-memory/DECISIONS.md), [evidence textů](docs/SOURCE_CATALOG.md).
- Před změnou koncepce: navíc [FAILURES](project-memory/FAILURES.md), [OPEN_QUESTIONS](project-memory/OPEN_QUESTIONS.md).
- Pro vývoj: [HISTORY](project-memory/HISTORY.md), [LESSONS](project-memory/LESSONS.md).

## Mapa úložišť
| Vrstva | Autoritativní umístění |
| --- | --- |
| KNOWLEDGE | PROJECT.md, project-memory/; detailní provenience v docs/SOURCE_CATALOG.md |
| SOURCE | texts/ — textový content master; nyní importované pracovní texty, nikoli schválená kompletní kniha |
| PRODUCTION | TBD; sazba ani její nástroj nejsou určeny |
| ARTIFACTS | Žádné vydání; umístění finálního PDF/EPUB TBD |
| EXTERNAL | Historický PDF export NTTV – Část 1 v ChatGPT; přesná identifikace v katalogu zdrojů |
| OPERATIONAL | Není provozní služba ani databáze; stav redakční práce v CURRENT_STATE, změny textu v Gitu |
| BACKUP | Nezávislá záloha TBD; GitHub není prohlášen za nezávislý backup |

## Kritická pravidla
- Rozlišovat ověřený text, uživatelovo rozhodnutí, historický návrh a otevřenou otázku.
- Nepovažovat osnovu 34 ani 15 kapitol za definitivně schválenou.
- Import textu není jeho redakční schválení. Starší vztahově zaměřené pasáže potřebují revizi.
- Nepřidávat další STATUS/HANDOFF. Současnost patří pouze do CURRENT_STATE.
- Text není návod ani univerzální zbavení odpovědnosti. Chyba není identita; odpovědnost není sebetrýznění.
- Neupravovat při importu formulace a nevymýšlet chybějící rukopis.
- Po významné práci konsolidovat správné soubory; zdrojové texty verzovat Gitem.

Centrální pravidla: [GUIDANCE](https://github.com/ludvikjesensky-cmd/project-memory/blob/main/GUIDANCE.md), [PROJECT_STANDARD](https://github.com/ludvikjesensky-cmd/project-memory/blob/main/PROJECT_STANDARD.md).
