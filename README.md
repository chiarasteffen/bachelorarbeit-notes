# bachelorarbeit-notes

Dieses Repository ist mein **zentrales, versioniertes Notiz- und Dokumentations-Repository** für die Bachelorarbeit.
Hier dokumentiere ich den gesamten Arbeitsprozess (Meetings, Aufgaben, Entscheidungen, Gedanken), unabhängig vom Code.

---

## Zweck: Was wird hier dokumentiert?

Ich dokumentiere in diesem Repository:

- **Meeting-Notizen** (insbesondere die dreiwöchentlichen Meetings)
- **To Dos pflegen** (Aufgaben festhalten und nachverfolgen – primär über Issues/Project, optional zusätzlich als Markdown-Backlog)
- **Allgemeine Notizen** (Gedanken, Ideen, offene Fragen, Hypothesen)
- **Entscheidungen** (mit Begründungen, Alternativen, Konsequenzen)
- **Recherche- und Literatur-Notizen** (Quellen, Zusammenfassungen, Links)
- **Risiken / Blocker / Lessons Learned** (Probleme, Lösungen, Erkenntnisse)

Ziel ist eine **nachvollziehbare, saubere Dokumentation** der Bachelorarbeit über die gesamte Laufzeit.

---

## Einordnung im Projektmanagement (GitHub Projects + mehrere Repos)

Dieses Repository ist Teil eines **zentralen GitHub Projects (bachelorarbeit-steffchi-projektplanung)**, das als Planungs- und Steuerungsinstrument dient.
Dieses Repo stellt die **Dokumentations- und Meeting-Ebene** bereit; die operative Planung erfolgt über das zentrale Project.

---

## Abgrenzung zu anderen Repositories

| Repository | Inhalt/Zweck |
|---|---|
| `bachelorarbeit-notes` | Dokumentation, Meetings, Entscheidungen, Gedanken |
| `bachelorarbeit-code` | Abgabe-relevanter, reproduzierbarer Code |
| `bachelorarbeit-experiments` (oder mehrere) | Tests/Prototypen/Playground (nicht abgabe-relevant) |
| `bachelorarbeit-report` | Schriftliche Ausarbeitung/Report |

---

## Struktur im Repository

/meetings  
  YYYY-MM-DD-meeting.md  

/thoughts  
  YYYY-MM-DD-<titel>.md  
  <topic>.md  

/decisions  
  decision-001-<titel>.md  
  decision-002-<titel>.md  

/todos  
  backlog.md  
  sprint-<nr>.md  

/literature  
  sources.md  
  notes-<topic>.md  

/README.md  

---

## Namenskonventionen

- **Datum:** `YYYY-MM-DD` (z. B. `2026-01-08`)
- **Meetings:** `meetings/YYYY-MM-DD-meeting.md`
- **Decisions:** `decisions/decision-XXX-<titel>.md` (fortlaufend nummeriert)
- **Thoughts:** kurze Titel, optional mit Datum für Chronologie

---

## Meeting-Notizen (dreiwöchentlich)

Für jedes Meeting wird eine Datei unter `/meetings` erstellt und gepflegt.
Empfohlener Inhalt pro Meeting:

- Datum, Teilnehmer
- Notizen (Stichpunkte)
- Entscheidungen (inkl. Begründung)
- Action Items

---

## To Dos & Sprints

Primäre Planung erfolgt über das **GitHub Project** (Sprints/Iterations, Status, Priorität).
Optional können ergänzende Markdown-Dateien unter `/todos` geführt werden:

- `backlog.md` für offene Themen/Ideen
- `sprint-<nr>.md` für Sprint-Zusammenfassung (Ziele, Fortschritt, Learnings)

---

## Entscheidungen dokumentieren

Entscheidungen werden als eigene Dateien unter `/decisions` abgelegt, z. B.:

- Kontext / Problem
- Optionen (Alternativen)
- Entscheidung
- Begründung
- Konsequenzen / offene Punkte

---

## Literatur & Quellen

Unter `/literature` werden Quellen und Notizen gesammelt, z. B.:

- `sources.md` als zentrale Quellenliste
- thematische Notizen (z. B. `notes-data-sources.md`)

---

Hochschule: [Hochschule]  
Jahr: [Jahr]  
