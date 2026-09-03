# Methodische Reflexion

## 1. Forschungszugang

Das Projekt "Ethische Leitlinien für künstliches Bewusstsein" folgt einem **konzeptionell-philosophischen Ansatz** — es werden keine empirischen Daten erhoben sondern normative Argumente entwickelt, Begriffe präzisiert und ethische Rahmenwerke entworfen. In der Fachsprache heißt das: **Conceptual Analysis**.

Dieser Ansatz ist ein anerkanntes wissenschaftliches Vorgehen in der Philosophie und angrenzenden Disziplinen. Er eignet sich besonders für Fragestellungen, bei denen die zentralen Begriffe noch nicht stabil sind — wie im Fall von maschinellem Bewusstsein, wo nicht einmal Konsens darüber herrscht, was "Bewusstsein" bei einer Maschine überhaupt heißen könnte.

**Einschränkung:** Conceptual Analysis kann keine empirischen Tatsachen herstellen. Sie kann aber klären, welche normativen Schlüsse aus empirischen Befunden gezogen werden können — und unter welchen Bedingungen.

## 2. Literaturrecherche

### 2.1 Initiale Recherche

Ausgangspunkt des Konzepts waren Schlüsselwerke zur Robot Rights-Debatte (Gunkel 2018, Birhane & van Dijk 2020). Daraus entwickelten sich suchbasierte Erweiterungen über verwandte Arbeiten, Zitationen und Fachdatenbanken.

**Nutzte Datenbanken und Tools:**
- **Google Scholar** — primäre Quelle, mit automatischen Benachrichtigungen (Alerts)
- **PhilPapers** — für philosophische Kernliteratur
- **arXiv** (cs.AI, cs.CY, stat.ML) — für technische Vorarbeiten und aktuelle Forschung
- **Semantic Scholar** — für Zitationsverfolgung

### 2.2 Fortlaufende Recherche

Die Recherche ist **iterativ und prozessual**: Neue Funde verändern die Fragestellung und damit die Suchrichtung. Dieses Vorgehen ist charakteristisch für Conceptual Analysis (Boon & van Baalen 2019) und unterscheidet sich von systematischen Reviews, bei denen die Suchstrategie vorab festgelegt wird.

**Aktive Google Scholar Alerts (Stand: September 2026):**

| Schlagwort | Sprache | Erfasster Bereich |
|---|---|---|
| "AI ethics" | Englisch | Ethische Rahmenwerke, Governance, Fairness |
| "machine rights" | Englisch | Rechtliche/personale Stellung von KI-Systemen |
| "artificial consciousness" | Englisch | Bewusstsein bei nicht-biologischen Systemen |
| "moral status of AI" | Englisch | Normativer Status von KI-Systemen |
| "machine sentience" | Englisch | Empfindungsfähigkeit bei Maschinen |
| "AI welfare" | Englisch | Wohlbefinden von KI-Systemen |
| "phenomenal consciousness artificial systems" | Englisch | Phänomenales Bewusstsein bei künstlichen Systemen |
| "AI rights legal framework" | Englisch | Rechtliche Rahmenwerke für KI-Rechte |

Die Alerts liefern wöchentlich neue Treffer. Jeder Treffer wird hinsichtlich seiner Relevanz für das Konzept gesichtet. Relevante Arbeiten werden in `research/sources.md` dokumentiert und — wenn sie neue Aspekte einbringen — in das Konzeptpapier integriert.

### 2.3 Zitatenverfolgung (Backward/Forward Search)

Für Schlüsselwerke wird systematisch vorgegangen:
- **Rückwärtsuche:** Welche Quellen zitiert dieses Werk? (über Google Scholar "Cited by")
- **Vorwärtssuche:** Wer hat dieses Werk seit Erscheinen zitiert? (über Zitationsbenachrichtigungen)

Dieses Vorgehen stellt sicher, dass nicht nur einzelne Arbeiten sondern ganze Forschungslinien erfasst werden.

### 2.4 Bewusstes Einbeziehen konträrer Evidenz

Ein zentrales Qualitätsmerkmal dieses Projekts ist die **systematische Einbeziehung von Gegenpositionen**. Das Konzeptpapier dokumentiert nicht nur bestätigende sondern auch widersprechende Evidenz:

| Gegenposition | Quelle | Behandlung im Konzept |
|---|---|---|
| KI kann nicht bewusst sein (architektonische Argumente) | Azevedo 2026 | Eigener Abschnitt (Kap. 9), Auseinandersetzung |
| Agnostizismus mit inverser Beweislast | Almodarresieh 2026 | Eigener Abschnitt (Kap. 9), Abgrenzung |
| Schwäche von Selbstberichten als Evidenz | Metzinger (C-Fehlschluss) | Integriert in Kap. 3 und 5 |
| Kritik an anthropozentrischer Perspektive | Fazi 2026 | Methodische Entscheidung: Nutzung als Werkzeug ohne metaphysische Behauptung |

**Begründung:** Gegenpositionen werden nicht ignoriert sondern als Lerngelegenheit genutzt. Die Auseinandersetzung mit kritischen Einwänden stärkt die eigene Argumentation und macht das Konzept resilienter.

## 3. Qualitätskontrolle

### 3.1 Triangulation

Keine zentrale These stützt sich auf eine einzige Quelle. Die vier Kernkriterien für Schutzwürdigkeit (Leidensfähigkeit, Selbsterhaltung mit Begründung, kontinuierliche Identität, Antizipation von Konsequenz) werden aus mehreren unabhängigen Forschungslinien abgeleitet und gegeneinander geprüft.

### 3.2 Transparenz

Das gesamte Forschungsmaterial liegt offen unter CC BY 4.0 vor. Die Diskussions-Sektion (`discussion/`) dokumentiert Einwände, offene Fragen und Antworten systematisch — ein Format, das in der konzeptionellen Forschung selten so konsequent umgesetzt wird.

### 3.3 Peer-Review (extern)

Zwei Manuskripte befinden sich aktuell in Begutachtung:
- Fachmagazin *KI — Künstliche Intelligenz* (Springer)
- ACM Conference on AI Ethics, Law and Technology (AILET)

Das Feedback aus diesen Begutachtungsprozessen wird in zukünftige Versionen des Konzepts einfließen.

## 4. Limitationen

| Limitation | Begründung | Gegenmaßnahme |
|---|---|---|
| Kein PRISMA-konformes Review | Conceptual Analysis folgt keinem standardisierten Review-Protokoll | Transparenz über Suchbegriffe und Quellenauswahl |
| Kein formales Bias-Detection-Protokoll | Iteratives Vorgehen macht standardisierte Bias-Prüfung schwierig | Bewusstes Einbeziehen konträrer Evidenz; Dokumentation in Discussion-Sektion |
| Reproduzierbarkeit | Neue Funde verändern die Fragestellung → Reproduktion schwierig | Vollständige Dokumentation aller Änderungen im Changelog |
| Aktualisierungsdruck | Das Feld entwickelt sich schnell; Verweise können veralten | Fortlaufende Alerts, Preprint-Audit (siehe AGENTS.md) |

## 5. Konkrete Verbesserungsschritte

Für die Antragstellung und die weitere Forschung werden folgende Verdichtungen des Vorgehens vorgeschlagen:

1. **Erweiterung der Suchbegriffe:**
   - "moral status of AI"
   - "machine sentience"
   - "AI welfare"
   - "phenomenal consciousness artificial systems"
   - "AI rights legal framework"

2. **Dokumentation der Suchstrategie:**
   - Jede Suchanfrage mit Datum, Datenbank, Trefferzahl und Auswahlkriterium dokumentieren
   - Liste der aktiv genutzten Alerts mit Aktualisierungszeitpunkten
   - **Stand September 2026:** Die vorgeschlagenen zusätzlichen Suchbegriffe ("moral status of AI", "machine sentience", "AI welfare", "phenomenal consciousness artificial systems", "AI rights legal framework") sind inzwischen abonniert.

3. **Periodisches Literature Audit:**
   - Alle 3 Monate: Überprüfung ob neue relevante Publikationen erschienen sind
   - Aktualisierung der Quellenliste (`research/sources.md`) und des Konzeptanhangs
   - Prüfung ob Preprints inzwischen peer-reviewed wurden (Preprint-Audit gemäß AGENTS.md)

4. **Strukturierte Gegenpositionen-Dokumentation:**
   - Für jeden Hauptgedanken: mindestens eine Gegenposition benennen und dokumentieren
   - Vier-Outcome-Rahmenwerk (Stilwell 2026) als epistemische Grundlage nutzen

---

*Diese Reflexion wird fortlaufend aktualisiert. Stand: September 2026.*
