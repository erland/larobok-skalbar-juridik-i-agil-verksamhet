# Exportguide

## Grundregel
Export ska utgå från `docs/export-metadata.yaml` och kapitelordningen där.

## EPUB
- Använd metadata för titel, undertitel, författare, språk och identifierare.
- Inkludera inte innehållsförteckning som eget textkapitel.
- Använd luftig CSS med tydliga rubriker, styckeavstånd och läsbara kod-/tabellblock.

## PDF
- PDF ska ha innehållsförteckning i början, före inledningen.
- Innehållsförteckningen ska genereras från rubrikstrukturen.
- Markdown ska renderas som riktig formatering.

## DOCX
- Rubriker, listor, tabeller, kursiv/fet stil och citat ska renderas som riktig formatering.
- Kapitelordningen ska följa metadatafilen.

## Bilder
- Omslag planeras i `assets/image-prompts/COVER.md`.
- Omslagsbild ska placeras i `assets/cover/cover.png`.
- Inga inre illustrationer används i första versionen.
