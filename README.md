# VM Quiz

Dette er en enkel, statisk quiz-app (HTML/JS/CSS) med fokus på VM i fodbold.

Fordeler:
- Hierarkisk kategoriutforsker på forsiden
- Oversikt over quiztyper (Pubquiz, Sport, Tenable osv.)
- Søg over kategorier og alle spørgsmål
- Forskellige spiltilstande: blandet quiz, liste-quiz, tenable, lineup, trup-quiz

Kør projektet:
1. Åbn `index.html` i en browser (ingen server nødvendig).

Hvordan tilføje spørgsmål:
- Spørgsmål ligger i `index.html` i `quizData`-objektet. Hver kategori er en array af objekter.
- Et spørgsmål skal som minimum have `q` (spørgsmålstekst) og `a` (array af acceptable svar).
- Brug `roundBreak: true` for at indsætte rundeopdelere i fx quizforliv.
- For multi-svar (flere rigtige) brug `multiPoint: true` og `maxPoints`.

Søg og navigation:
- Brug søgefeltet øverst på forsiden til at finde kategorier eller specifikke spørgsmål.
- Klik på en kategori i oversigten for at bore ned og starte "blandet" eller "alle" fra den node.

Fremtidige forbedringer (idéer):
- Leaderboard (localStorage eller backend)
- Filtrering på tags / sværhedsgrad
- Eksport/import af spørgsmål JSON
- Commitment og versionskontrol (git)

Kontakt:
- Denne kode blev ændret af digg (via Copilot-assistent) — rediger frit.
