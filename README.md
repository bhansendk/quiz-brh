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
 - Spørgsmål kan også have et internt `tags`-felt (array af strings). Tags bruges til at knytte et spørgsmål til flere kategorier (fx "vm", "fodbold", "sport", "faktamix"). Tags vises ikke i UI, men bruges af kategorinavigatoren.

Søg og navigation:
- Brug søgefeltet øverst på forsiden til at finde kategorier eller specifikke spørgsmål.
- Klik på en kategori i oversigten for at bore ned og starte "blandet" eller "alle" fra den node.
 - Bemærk: navnet `blandet` er erstattet af `FaktaMix` internt som `faktamix`.
 
Opdateringer i denne version:
- Forbedret forside med hero-sektion, CTA-knapper og statistikker.
- Automatisk annotering af spørgsmål (`tags`) udføres ved sideindlæsning.
- Flere eksempels spørgsmål er importeret automatisk for at gøre kategorierne mere fyldige.

Hvis du vil tilpasse: åbn `index.html` og rediger `addMoreQuestions()` eller spørg mig om at importere fra en CSV/JSON.

Fremtidige forbedringer (idéer):
- Leaderboard (localStorage eller backend)
- Filtrering på tags / sværhedsgrad
- Eksport/import af spørgsmål JSON
- Commitment og versionskontrol (git)

Kontakt:
- Denne kode blev ændret af digg (via Copilot-assistent) — rediger frit.
