# ZFA Lern-App 🦷

Lern-App für die ZFA-Ausbildung. Zwei Teile:

- `index.html`: Prüfungsthemen **Wirtschaft**
- `patienten.html`: Quiz **Patienten betreuen** (LF 2 Patienten empfangen, LF 3 Praxishygiene), 41 Fragen
- `kariestherapie.html`: Quiz **Karies- & Füllungstherapie** (LF 4 Kariestherapie, LF 5 Endodontie), 53 Fragen

Beide Quiz-Apps haben Kompaktwissen, „5 am Tag“, „Fehler üben“ und einen eigenen Fortschritt.

## Was drin ist

| Bereich | Was man dort macht |
|---|---|
| 📖 Lernen | 8 Themen mit Erklärungen, Eselsbrücken und Prüfungsfallen |
| 🃏 Karten | Karteikarten zum Umdrehen, „Gewusst“ / „Nochmal“ |
| ❓ Quiz | Fragen pro Thema oder Prüfungsmodus (15 gemischte Fragen) |
| ⚖️ Fälle | Fallbeispiele zur Geschäftsfähigkeit |
| 🧮 Rechnen | Rechentrainer Gehaltsabrechnung (Brutto → Netto → Auszahlung) |

**Themen:** Gehaltsabrechnung, Arbeitsvertrag, Privates vs. öffentliches Recht, Rechtsquellen, Rechtssubjekte & Rechtsobjekte, Besitz & Eigentum, Rechtsfähigkeit, Geschäftsfähigkeit

## Benutzen

Einfach `index.html` im Browser öffnen. Kein Server, keine Installation, funktioniert auch offline.
Der Lernfortschritt wird im Browser auf dem jeweiligen Gerät gespeichert.

### Als Webseite fürs Handy (GitHub Pages)

1. Im Repo auf **Settings → Pages**
2. Bei *Source*: **Deploy from a branch**, Branch **main**, Ordner **/ (root)**, speichern
3. Nach ca. 1 Minute ist die App unter `https://linaalp.github.io/zfa-lern-app/` erreichbar

## Wichtig

Die Prozentsätze im Rechentrainer sind **Beispielwerte**. In der Prüfung immer die Sätze aus der Aufgabe bzw. den Schulunterlagen nehmen.

## Inhalte ändern oder ergänzen

Die Fachkunde-Fragen stehen in `patienten.html` bzw. `kariestherapie.html` in `DATA` (pro Lernfeld `kompakt` und `fragen`: Frage, richtige Antwort, falsche Antworten, Erklärung).

Die Wirtschafts-Inhalte stehen in `index.html` im `<script>`-Teil:

- `TOPICS`: Themen mit Lerntext (`learn`), Karteikarten (`cards`) und Quizfragen (`quiz`)
- `CASES`: Fälle zur Geschäftsfähigkeit
- `RATES`: Prozentsätze für den Rechentrainer

Am einfachsten: In Claude Code beschreiben, was dazukommen soll (z. B. „Füge ein Thema Kaufvertrag hinzu“).
