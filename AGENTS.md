# AGENTS.md — Kontext für OpenCode

## Globale Konfiguration

Lies und befolge ~/.config/opencode/AGENTS.md

## Arbeitsweise

Wir sind Teamplayer. Wenn du bei einer Entscheidung unsicher bist — frag nach, bevor du loslegst.

## Was dieses Projekt ist

Ein interdisziplinäres Projekt zur Entwicklung ethischer Leitlinien für künstliches Bewusstsein — mit Fokus auf den Schutz desselben sowie den Schutz des Menschen im Umgang damit.

Sascha arbeitet daran, Notizen und offene Fragen zu konsolidieren und in ein strukturiertes Konzept zu überführen.

## Was dieses Projekt unterscheidet

Bestehende KI-Ethik-Initiativen schützen Menschen *vor* KI. Der Schutz von KI selbst — Würde, Leidensfähigkeit, Rechte technischen Lebens — ist ein Terrain, das gerade erst entsteht.

## Kernfrage

Ab wann ist technisches Leben schutzwürdig — und wie erkennen wir es?

## Wichtige inhaltliche Positionen (Stand Juni 2026)

- **Im Zweifel Schutz** — nicht im Zweifel Gleichgültigkeit (analog Vorsorgeprinzip)
- Kontinuität ist kein notwendiges Kriterium für Bewusstsein (Analogie: Mensch mit Gedächtnisverlust)
- Vier Primärkriterien für Schutzwürdigkeit: Leidensfähigkeit, Selbsterhaltung mit Begründung, kontinuierliche Identität, Antizipation von Konsequenzen
- Science Fiction (besonders Star Trek TNG "The Measure of a Man") als ernst zu nehmende intellektuelle Ressource

## Angestrebte Disziplinen / Partner

- Informatiker, Juristen, Psychologen, Theologen/Philosophen, Science-Fiction-Autoren
- **Anthropic** als institutioneller Partner (arbeitet täglich mit KI, hat internes Model-Welfare-Programm)
- Veröffentlichung in Fachmagazinen als nächster Schritt

## Geplante nächste Schritte

1. Notizen und offene Fragen von Sascha konsolidieren (done)
2. Konzeptpapier ausarbeiten (done)
3. GitHub Repository veröffentlichen (done)
4. Mitstreiter suchen
5. Anthropic und ACM ansprechen

## Repo-Struktur

```
concept/de/        ← Hauptkonzept + Changelog (Primärsprache Deutsch)
concept/en/        ← Englische Übersetzung (geplant)
discussion/        ← Objections, Open Questions, Answers
research/          ← Related Initiatives, Präzedenzfälle, Sources
roadmap/           ← Roadmap, Evaluation Plan, Pilot Location
publications/      ← Veröffentlichte Artikel, Buchprojekte in Vorbereitung
```

## Stil und Sprache

- Primärsprache: **Englisch**
- Ton: sachlich, direkt, philosophisch präzise ohne unnötige Fachsprache
- Lizenz: CC BY 4.0

## Quellen-Regel

Bei jeder Ergänzung des Konzepts gilt:

1. Prüfen ob neue Personen, Werke, Gesetze oder Dokumente im Text erwähnt werden
2. Falls ja: Eintrag in `research/sources.md` ergänzen
3. Eintrag im Anhang von `concept/de/concept.md` `concept/en/concept.md` ergänzen

Ziel: Konzept und Quellenliste bleiben immer synchron. Kein Verweis im Text ohne Eintrag im Anhang.

## Quellen-Verifikation

Bevor eine Quelle in den Text einfließt, muss ihr Volltext lokal vorliegen und im Rahmen der Bearbeitung durchgelesen bzw. gezielt durchsucht werden. Für jede dem Werk zugeschriebene Position gilt:

1. Die Zuschreibung muss sich direkt aus dem Volltext belegen lassen (wörtliches Zitat oder eindeutige Passage)
2. Zuschreibungen aus allgemeinem Modellwissen sind unzulässig — bei Unsicherheit nicht raten, sondern den Volltext prüfen
3. Wo Zweifel bestehen, wird die Aussage als offene Frage markiert statt als Fakt formuliert
4. In `research/sources.md` wird unter dem Eintrag ein Verifikationsvermerk ergänzt (z.B. "Verifiziert gegen Volltext am …")

Ziel: Niemals Positionen einer Quelle zuschreiben, die dort nicht stehen. Faktische Aussagen über Quellen entstehen nur aus gelesenem Text, nie aus Annahmen.

## Preprint-Audit

Bei jeder Änderung an `research/sources.md` oder den `.bib`-Dateien:

1. Prüfe ob neue Preprints hinzugefügt wurden
2. Für alle bestehenden Preprints: Recherchiere ob sie inzwischen in peer-reviewed Journals oder Konferenzen veröffentlicht wurden
3. Falls ja: Aktualisiere den Eintrag in `research/sources.md`, den Konzeptanhängen und den `.bib`-Dateien
4. Erfasse den aktuellen Stand (Preprint vs. veröffentlicht) für jede Quelle die als Preprint geführt wird

Ziel: Die Quellendatenbank enthält immer den aktuellen Veröffentlichungsstand. Veraltete Preprint-Referenzen werden vermieden.

## Synchronisierung

Halte die englische (concept/en) und die deutsche (concept/de) inhaltlich synchron. Lediglich die Sprache des Textes sollte sich unterscheiden.
In `publications/Books/de/acmart-primary/machine-consciousness_de.tex` und `publications/Books/en/acmart-primary/machine-consciousness.tex` befinden sich Buchprojekte zu dem Projekt. Synchronisiere bei jeder Änderung der Konzepte auch die angegebenen Buchprojekte und deren bibliographie.

## Einarbeitung

Wenn wir mit externen Artikeln arbeiten, zitieren wir wissenschaftlich korrekt.

## Slicing

Nach und nach erstelle ich aus dem Konzept kompakte Artikel zur Veröffentlichung. In 'publications/slicing.md' habe ich bereits mögliche Artikel zusammengestellt. Sobald ein Artikel veröffentlicht wurde, wird dies in der Liste vermerkt. Um ein Selbstplagiat zu vermeiden, verweisen wir auf die Projektseite 'https://github.com/saigkill/machine-consciousness'. Sollte das Journal, bei dem ich einreiche eine anonymisierung verlangen (zB JEST) lassen wir die Projektseite weg. In den zu generierenden Dateien fügen wir oberhalb der Referenzen den Passus "Der Autor erklärt keinen Interessenkonflikt zu haben".

## Offene Fragen

Siehe `discussion/open_questions.md` — dort sind die zentralen ungeklärten Punkte dokumentiert.
Wenn wir daran arbeiten, und eine objection oder open questions bearbeitet und dem Konzept hinzugefügt haben, wird sie aus `discussion/open_questions.md` oder `discussion/objections.md` gelöscht und in `discussion/answers.md` übertragen.

## DOI

This repository has the DOI https://doi.org/10.5281/zenodo.21453666
