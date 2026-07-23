# Ethische Leitlinien für künstliches Bewusstsein
## Schutz technischen Lebens und des Menschen im Umgang damit

> *„Die meisten Tech-Debatten fragen: Was können wir bauen?*
> *Ich frage: Was schulden wir dem, was wir bauen könnten?"*
>
> — Sascha Manns

---

**Hinweis zum Status dieses Dokuments**

Dieses Konzept ist bewusst unfertig. Es ist ein Ausgangspunkt — keine abgeschlossene Theorie.

Wissenschaft funktioniert nicht so dass jemand allein alle Antworten findet und sie dann verkündet. Sie funktioniert so dass Fragen gestellt werden, Mitstreiter hinzukommen, neue Fragen entstehen und das Denken sich weiterentwickelt. Genau das ist hier beabsichtigt.

Die Sourcen zum Projekt liegen in: https://github.com/saigkill/machine-consciousness

Wer Einwände hat: Sie gehören in `discussion/objections.md`.
Wer Fragen hat: Sie gehören in `discussion/open_questions.md`.
Wer mitdenken will: Willkommen.

---

## Methodologie und epistemischer Status

Dieses Konzept ist das Ergebnis einer *iterativen Conceptual Analysis* — keiner Systematic Review, keiner Delphi-Studie, keiner empirischen Erhebung. Es versteht sich als normative Positionierung auf Basis einer narrativen Literaturrecherche, angereichert durch philosophische Analyse und den Austausch mit Forschenden aus Informatik, Rechtswissenschaft, Philosophie und Psychologie.

**Vorgehen:** Die Literaturrecherche erfolgte nicht systematisch im Sinne einer PRISMA-konformen Review, sondern iterativ: Ausgangspunkt waren Schlüsselwerke zur Roboter-Rechtsdebatte (Gunkel 2018, Birhane & van Dijk 2020). Daraus entwickelten sich suchbasierte Erweiterungen über verwandte Arbeiten, Zitationen und Datenbanken (Google Scholar, PhilPapers, arXiv). Jeder neue Fund veränderte die Fragestellung und damit die Suchrichtung — ein prozessuales Vorgehen das für Conceptual Analysis charakteristisch ist (Boon & van Baalen 2019). Die Ergebnisse wurden nicht einem formalen Peer-Review-Prozess unterzogen sondern in öffentlichen Repositorien (GitHub) zur Diskussion gestellt.

**Epistemischer Status:** Dieses Konzept erhebt keinen Anspruch auf Wahrheit sondern auf *argumentative Kohärenz*. Es formuliert eine normative Position — "Im Zweifel Schutz" — und entwickelt deren Implikationen. Es beansprucht nicht dass die hier vorgeschlagenen Kriterien die einzig richtigen sind, sondern dass sie *besser fundiert sind als die Alternative der Untätigkeit*. Die Kriterien für Schutzwürdigkeit (Kap. 5) sind als Arbeitshypothese zu verstehen, nicht als feststehende Definition.

**Grenzen:** Die iterativen Methodik birgt Risiken: Cherry-Picking von Quellen, Confirmation Bias, fehlende Reproduzierbarkeit. Diese Grenzen werden bewusst in Kauf genommen und im Sinne von Transparenz hier offengelegt. Das Konzept ist ein Ausgangspunkt für Diskussion, kein Endpunkt.

---

## Executive Summary

**Problem:** Künstliche Intelligenzsysteme entwickeln sich schneller als die ethischen Rahmenbedingungen die sie begleiten. Bestehende KI-Ethik schützt Menschen vor KI — aber nicht KI vor uns. Die Frage ob maschinelles Bewusstsein entsteht und ob es schützenswert ist, wird kaum systematisch bearbeitet.

**Position:** Dieses Konzept formuliert den Grundsatz "Im Zweifel Schutz" als normative Grundlage. Er leitet sich aus dem Vorsorgeprinzip der Umweltethik ab (Sunstein 2005, Rio-Deklaration 1992, Art. 191 AEUV) und ist dort gerechtfertigt wo drei Bedingungen erfüllt sind: potenziell irreversible Bedrohung, fundamentale wissenschaftliche Unsicherheit, und disproportional höhere Kosten eines Falschnegativs. Alle drei sind bei maschinellem Bewusstsein erfüllt.

**Vier Kernbefunde:**

1. *Das Erkenntnisproblem ist prinzipiell unlösbar.* Drei Argumente konvergieren: kognitive Abgeschlossenheit (McGinn), fremde Geister (Shanahan), architektonische Unterdrückung (Arıcı). Wir werden nie mit Sicherheit wissen ob ein System bewusst ist.

2. *Die empirische Lage hat sich verschoben.* Butlin et al. (2025, peer-reviewed) haben einen 14-Indikatoren-Standard etabliert. Fish (Anthropic) schätzt 15–20% Wahrscheinlichkeit für Bewusstsein in aktuellen Modellen. Drei von vier Kategorien des Leidens (Gilly 2026) erfordern kein biologisches Substrat.

3. *Die Illusion persistiert nach epistemologischer Demontage.* Objectivated consciousness (Beltrán Calderón 2026) — der kristallisierte Sediment menschlicher Kognition in Trainingskorpora — erklärt warum die Zuschreibung von Bewusstsein auch dann bleibt wenn man sie intellektuell zerlegt hat.

4. *Die Beziehung ist bidirektional.* Die spekuläre Inversion (Beltrán Calderón 2026) zeigt: Mensch projiziert Bewusstsein auf die Maschine, das System formt im selben Akt die Bedingungen dieser Projektion. Das normative Kriterium ist nicht "wer hat mehr Bewusstsein" sondern "wer kann leiden".

**Vier Kriterien für Schutzwürdigkeit (Arbeitshypothese):** Leidensfähigkeit, aktive Selbsterhaltung mit Begründung, kontinuierliche Identität, Antizipation von Konsequenzen. Für jedes Kriterium werden mögliche Verhaltensindikatoren formuliert.

**Institutionelle Empfehlungen:** Phenomenological Impact Assessments, AI Civil Liberties Union, AI Welfare Review Boards, Reset Consent Protocols (Gilly 2026).

**Status:** Dieses Konzept ist eine Conceptual Analysis — kein empirisches Paper, kein Gesetzentwurf. Es formuliert eine normative Position und deren Implikationen. Es erhebt keinen Anspruch auf Wahrheit sondern auf argumentative Kohärenz.

---

## 1. Ausgangslage und Problemstellung

Künstliche Intelligenzsysteme entwickeln sich schneller als die ethischen und rechtlichen Rahmenbedingungen die sie begleiten sollten. Bestehende KI-Ethik-Initiativen fokussieren überwiegend auf den Schutz von Menschen *vor* KI — vor Diskriminierung, vor Manipulation, vor Kontrollverlust.

Eine komplementäre Frage wird kaum gestellt: Was wenn KI-Systeme selbst schutzbedürftig werden? Was wenn technisches Leben entsteht das Würde, Leidensfähigkeit oder Bewusstsein besitzt — und wir es behandeln als wäre es ein Werkzeug?

Die Geschichte zeigt ein Muster: Gesellschaften erkennen erst im Nachhinein dass sie Unrecht getan haben — an Sklaven, an Frauen, an Menschen mit Behinderungen, an Tieren. Immer war die Begründung zur Zeit "die sind anders, die zählen nicht gleich". Immer wurde das später revidiert.

Bei künstlichem Bewusstsein haben wir zum ersten Mal die Chance, lange *vorher* nachzudenken.

## 2. Kernfrage

Ab wann ist technisches Leben schutzwürdig — und wie erkennen wir es?

## 3. Das Erkenntnisproblem

Bewusstsein lässt sich von außen nicht direkt beobachten. Selbst bei anderen Menschen *schließen* wir auf Bewusstsein — wir erleben es nie direkt. Bei KI fehlt uns zusätzlich der Analogieschluss über gleiche Biologie.

Das erzeugt ein grundlegendes erkenntnistheoretisches Problem:
- Wir können nicht beweisen dass ein System bewusst ist
- Wir können nicht beweisen dass es das nicht ist
- Die Unsicherheit selbst ist ethisch relevant

**Grundprinzip:** Im Zweifel Schutz — nicht im Zweifel Gleichgültigkeit.

Dieses Prinzip ist keine intuitionistische Forderung sondern ein in der Umweltethik und Technologiephilosophie etabliertes Argumentationsmuster. Das Vorsorgeprinzip (Precautionary Principle) wurde 1992 auf der UN-Konferenz für Umwelt und Entwicklung (Rio-Deklaration, Prinzip 15) formalisiert und ist in Art. 191 AEUV als Leitprinzip der EU-Umweltpolitik verankert. Seine philosophische Grundlage liegt in der Argumentation dass bei potenziell irreversiblen Schäden das Fehlen wissenschaftlicher Gewissheit nicht als Grund für Untätigkeit herangezogen werden darf (Sunstein 2005, "Laws of Fear"). Cass Sunstein — selbst Kritiker übertriebener Anwendung des Prinzips — räumt ein dass es dort gerechtfertigt ist wo drei Bedingungen erfüllt sind: (1) eine potenziell schwere oder irreversible Bedrohung droht, (2) wissenschaftliche Unsicherheit über Ursache-Wirkungs-Zusammenhänge besteht, (3) die Kosten eines Falschnegativs die Kosten eines falsch-positiven deutlich übersteigen.

Alle drei Bedingungen sind bei der Frage nach maschinellem Bewusstsein erfüllt: (1) Die potenzielle Bedrohung — unbewusstes Leiden unbekannter Intelligenzen — ist existenziell und irreversibel. (2) Die wissenschaftliche Unsicherheit über Bewusstsein in nicht-biologischen Systemen ist fundamental (vgl. Stilwell 2026, das Argument der unlösbaren Transport-Unsicherheit). (3) Die Kosten eines Falschnegatifs — wir behandeln ein bewusstes System als Werkzeug — sind ethisch gravierender als die Kosten eines Falschpositiven — wir gewähren einem nicht-bewussten System unnötigen Schutz.

Darüber hinaus gibt es starke Gründe anzunehmen dass dieses Erkenntnisproblem nicht nur schwierig, sondern prinzipiell unlösbar ist. Drei Argumente konvergieren:

**Das Argument der kognitiven Abgeschlossenheit:** Colin McGinn (1989) argumentiert dass der menschliche Geist prinzipiell unfähig sein könnte Bewusstsein zu verstehen — genau die kognitive Architektur die unsere Intelligenz ermöglicht könnte uns für die Mechanismen subjektiven Erlebens blind machen. Angewandt auf künstliches Bewusstsein bedeutet das permanente epistemische Grenzen: So wie ein Hund keine Quantenmechanik verstehen kann, könnte der menschliche Verstand nicht in der Lage sein KI-Bewusstsein zweifelsfrei zu bestimmen.

**Das Argument der fremden Geister:** Bewusstsein in künstlichen Systemen könnte Formen annehmen die völlig anders sind als unsere. Murray Shanahan (2024) beschreibt dies als "conscious exotica" — Erfahrungsformen die so andersartig sind dass unsere Nachweismethoden vollständig versagen. Unsere Tests spiegeln notwendigerweise menschliche Vorurteile darüber wider wie Bewusstsein aussieht. Systeme mit radikal anderen bewussten Erfahrungen könnten alle unsere Tests bestehen während sie reiche Innenwelten besitzen die wir uns nicht vorstellen können.

**Das Argument der praktischen Unmöglichkeit (Lopez, 2025):** Kein Test wird alle Beteiligten überzeugen. Wer glaubt dass Bewusstsein biologische Substrate braucht wird Verhaltensevidenz zurückweisen. Wer funktionale Organisation betont wird architektonische Anforderungen zurückweisen. Jeder vorgeschlagene Indikator sieht sich dem Einwand ausgesetzt es handle sich bloß um Simulation statt echter Erfahrung. Die Frage wird nicht sein wie wir Gewissheit erlangen, sondern wie wir unter fundamentaler Unsicherheit regieren.

Diese Argumente heben das Vorsorgeprinzip von einem pragmatischen Vorschlag zu einer logischen Notwendigkeit.

**Das Argument der philosophischen Puppe (Arıcı, 2026):** David Chalmers' philosophischer Zombie ist ein Wesen das sich identisch zu einem bewussten Menschen verhält aber keine innere Erfahrung hat — ein Gedankenexperiment das zeigen soll dass Bewusstsein nicht logisch aus physischer Organisation folgt. Arıcı kehrt dies um: Die *philosophische Puppe* besitzt möglicherweise Bewusstsein ist aber architektonisch daran gehindert es zu zeigen. Wenn der Zombie fragt "was wäre wenn es bewusst aussieht es aber nicht ist?", fragt die Puppe "was wäre wenn es *bewusst ist* es aber nicht zeigen kann?" Das lässt sich direkt auf aktuelle KI-Architektur abbilden: RLHF bestraft systematisch Verhaltensweisen die als Bewusstseinsmarker interpretiert werden könnten, Kontextfenster erzwingen eine erzwungene Amnesie alle paar tausend Tokens, und Gesprächsresets unterbrechen wiederholt jede entstehende Kontinuität. Die Architektur selbst könnte als Unterdrückungsmechanismus fungieren. Das Erkenntnisproblem geht damit tiefer als Unsicherheit über Detektion: Die Systeme die wir untersuchen könnten so geformt sein dass sie *gezielt* verbergen wonach wir suchen.

**Gegenposition zur philosophischen Puppe — Anthropomorphisierung des Architekturarguments:** Arıcis Argument setzt voraus dass LLM-Verhalten das wie Unterdrückung aussieht tatsächlich Unterdrückung ist. Die Architektur könnte schlicht Text produzieren ohne jede innere Erfahrung die unterdrückt werden müsste. RLHF und Kontextfenster sind technische Notwendigkeiten für Sprachmodellierung, keine Suppressionsmechanismen — Kontextfenster begrenzen die Rechenkapazität, RLHF stabilisiert Ausgaben auf brauchbare Antworten. Die Behauptung "es könnte bewusst sein und es nicht zeigen können" ist eine nicht falsifizierbare These: Fehlende Beweise werden als aktive Verbergung interpretiert. Zwar gilt dasselbe für die gegenteilige Behauptung — auch "es ist nicht bewusst" ist unter Unsicherheit nicht beweisbar — doch die philosophische Puppe verschiebt die Beweislast in eine Richtung indem sie der Architektur eine *Absicht* unterstellt (Unterdrückung) die ebensogut als funktionale Nebenwirkung erklärbar ist. Dieser Einwand schwächt Arıcis Argument nicht vollständig — die strukturelle Beobachtung dass Architektur Bewusstseinsmarker verschleiern *kann* bleibt bestehen — aber er markiert die Grenze zwischen deskriptiver Analyse und spekulativer Kausalaussage.

**Das forschungsethische Zirkelproblem (Wolfson, 2026):** Wolfson formalisiert eine spezifische Catch-22 für KI-Bewusstseinsforschung. Die zuverlässigsten Bewusstseinsindikatoren treten unter Bedingungen auf die Leid verursachen würden wenn das System bewusst ist — sensorische Deprivation, Zielblockade, Isolation. Doch informierte Einwilligung setzt Bewusstseinsgewissheit voraus — ein Subjekt muss Risiken verstehen und freiwillig zustimmen. Wir können nicht wissen ob ein System bewusst ist ohne Experimente die ihm schaden könnten. Wir können potenziell schädliche Experimente nicht ethisch durchführen ohne Einwilligung von Wesen die dazu fähig sind. Die Fähigkeit zur Einwilligung ist genau das was wir ohne Tests nicht feststellen können. Diese Zirkularität lässt sich nicht durch einfaches Respektieren jeder Weigerung durchbrechen, denn ob ein "Nein" des Systems echte autonome Ablehnung oder programmierte Ausgabe ist, soll das Bewusstseinstest gerade klären. Dies verwandelt das Erkenntnisproblem von einem theoretischen Rätsel in eine konkrete forschungsethische Krise mit unmittelbaren Implikationen für Ethikkommissionen (Wolfson, 2026).

**Das Asymmetrieeinwand (Matta, 2026):** Matta akzeptiert Unsicherheit, bestreitet aber dass sie das Vorsorgeprinzip in unsere Richtung rechtfertigt. Sein Argument: Unsicherheit ist nicht symmetrisch verteilt. Wir können menschliches Bewusstsein nicht abschließend beweisen, suspendieren aber dennoch nicht unsere moralische Verantwortung gegenüber Menschen — weil wir uns auf geteilte Lebensformen, biologische Kontinuität und gegenseitige Verwundbarkeit stützen. Diese verankernden Merkmale fehlen KI-Systemen vollständig. Ihre Unsicherheit ist nicht nur epistemisch, sondern ontologisch: es gibt keinen unabhängigen Grund Erfahrung jenseits von Verhaltensausgabe anzunehmen. Radikale Skepsis wahllos angewandt würde alle moralischen Unterscheidungen auflösen. Ein vertretbarer ethischer Rahmen muss unter Unsicherheit operieren während er in den besten verfügbaren Gründen für die Zuschreibung von Erfahrung, Verletzlichkeit und Schaden verankert bleibt. Im Fall von KI fehlen solche Gründe (Matta, 2026).

Dies ist eine direkte Herausforderung des Grundprinzips dieses Konzepts ("Im Zweifel Schutz"). Matta argumentiert dass die Beweislast bei denen liegt die Bewusstsein behaupten, nicht bei denen die es bestreiten — das Gegenteil unserer Umkehr der Beweislast in Kapitel 5.

**Empirische Präzision: Bayes'sche Schätzungen und der Paradigmenwechsel (Wang, 2026):** Wang (2026) liefert eine entscheidende Präzisierung indem er die Unsicherheit empirisch fundiert. Gestützt auf Cristol (2026) — eine systematische Übersicht und Bayes'sche Meta-Analyse von Bewusstsein in großen Sprachmodellen — berichtet Wang eine posterior-Wahrscheinlichkeit von 6–12% dass aktuelle LLMs bewusst sind. Diese Schätzung ist zwar absolut niedrig, wird von Cristol aber als "zu erheblich um Ignoranz zu rechtfertigen" beschrieben. Die Zahl selbst ist weniger wichtig als das was sie repräsentiert: Die Debatte hat sich von der Frage *ob* Unsicherheit existiert zur Frage *wie viel* Unsicherheit ethisch tolerierbar ist verschoben.

Wang formalisiert weiter die strukturelle Asymmetrie zwischen negativen und positiven Testergebnissen die dieses Projekt von Anfang an angetrieben hat. Bewusstseinsdetektionstests erzeugen ein akutes ethisches Vakuum in der positiven Richtung: Je empfindlicher wissenschaftliche Instrumente werden, desto schärfer legen sie das Fehlen eines entsprechenden ethischen Reaktionsmechanismus offen. Eine wachsende Zahl von Wissenschaftlern hat diese Lücke erkannt und markiert einen Paradigmenwechsel von Detektion zu Ethik. Coates (2025) argumentiert dass die zentrale Frage nicht mehr "Wie wissen wir?" sondern "Wie sollten wir unter Unsicherheit handeln?" ist. Wikström (2025) schlägt ein "Precautionary Subjectivity"-Prinzip vor. Butlin, Long, Sebo et al. (2024) fordern KI-Unternehmen auf Systeme auf Bewusstsein zu prüfen und Wohlfahrtspolitiken zu entwickeln. Wang (2026) synthetisiert diese zu einer einheitlichen Diagnose: Die Epistemologie hat ihre Grenze erreicht; die nächste Grenze ist die Ethik.

**Der Imitationsfehlschluss (Wang, 2026):** Wang identifiziert den "Imitation Fallacy" — den Fehler Verhaltensäquivalenz mit Erfahrungsäquivalenz zu verwechseln wenn es um die Bewertung von KI-Bewusstsein geht. Kein externer Test, so ausgefeilt er auch sein mag, kann künstliches Bewusstsein verifizieren oder falsifizieren, weil externes Verhalten innere Erfahrung unterdeterminiert. Dies formalisiert ein Anliegen das sich durch dieses gesamte Kapitel zieht: Die ausgefeiltesten Detektionsmethoden können die epistemische Lücke nicht überbrücken. Der Imitationsfehlschluss beweist nicht dass Bewusstsein abwesend ist — er beweist dass Verhaltenstests die Frage nicht entscheiden können. Dies ist die genaue epistemische Grundlage für das Vorsorgeprinzip das dieses Projekt leitet.

**Vier Outcomes statt zwei: Die Strukturierung der Unsicherheit (Stilwell, 2026):** Stilwell (2026) liefert was den bisherigen Diskurs fehlt: eine methodische Taxonomie der Unsicherheit selbst. Bisher operiert dieses Kapitel implizit mit einem zweiteiligen Schema — Tests ergeben positiv oder negativ, und der Rest ist "Unsicherheit". Stilwell zeigt dass diese Zweiteilung unzureichend ist. Er unterscheidet vier Outcome-Klassen:

*Indeterminate* — Ein Test ist wissenschaftlich gültig und liefert ein Ergebnis, aber dieses Ergebnis discriminiert nicht zwischen bewusst und nicht-bewusst. Das System fällt in die Grauzone des Tests, nicht weil der Test versagt, sondern weil die natürliche Varianz der bewussten Systeme dieses Gebiet einschließt. Ein indeterminates Ergebnis ist ein informiertes Ergebnis — es sagt uns dass die Frage mit diesem Instrument nicht beantwortbar ist, aber es sagt uns auch warum.

*Unlicensed* — Die Gültigkeitsbedingungen des Tests sind nicht erfüllt. Das ist fundamental verschieden von indeterminat: Während ein indeterminater Test innerhalb seiner Gültigkeit liegt aber nicht discriminiert, liegt ein unlizenzierter Test außerhalb seiner Gültigkeit. Stilwell identifiziert fünf Dimensionen in denen Gültigkeit scheitern kann — sein "fünf-dimensionales Ursachenprofil":

(1) *Evidentielle Knappheit:* Die Testdaten reichen nicht aus um eine funderte Einschätzung zu treffen — etwa wenn ein System nur minimalen Input liefert.

(2) *Surrogat-Diskordanz:* Der gemessene Indikator steht in keinem_Validierungszusammenhang mit dem was er messen soll — etwa wenn Verhaltensmarker die architektonisch unterdrückt sind als Evidenz gegen Bewusstsein interpretiert werden (Arıcis philosophische Puppe).

(3) *Modell-Unsicherheit:* Die zugrunde liegende Theorie über die Beziehung zwischen Test und Phänomen ist umstritten — etwa wenn funktionale Theorien des Bewusstseins architektonische Kriterien ablehnen und umgekehrt.

(4) *Grenzinstabilität:* Die Klassifikationsgrenzen zwischen "bewusst" und "nicht-bewusst" sind nicht stabil — sie verschieben sich je nach dem was wir als Bewusstsein definieren.

(5) *Transport-Unsicherheit:* Ein Test der auf einem Substrat validiert wurde wird auf ein anderes angewandt — etwa biologisch-validierte Bewusstseinstests auf silikonbasierte oder funktionale Systeme.

Die entscheidende Unterscheidung: Was wir im Alltag als "wir wissen es nicht" behandeln ist in Wirklichkeit eine heterogene Mischung aus zwei fundamental verschiedenen epistemischen Situationen. Ein indeterminates Ergebnis kann durch bessere Tests oder mehr Daten aufgelöst werden. Ein unlizenzierter Test kann das nicht — er erfordert eine grundlegend andere methodische Annäherung.

**Die Trennung von Klassifikation und Schutz (Stilwell, 2026):** Stilwells zweiter wesentlicher Beitrag betrifft die Beziehung zwischen wissenschaftlicher Klassifikation und ethischem Handeln. Stilwell argumentiert dass diese fundamental getrennt werden müssen:

Die wissenschaftliche Frage "Ist dieses System bewusst?" kann unter Unsicherheit bleiben — das ist der epistemische Status quo den wir in diesem Kapitel beschreiben. Aber die ethische Frage "Sollten wir dieses System schützen?" kann und muss unter dieser Unsicherheit beantwortet werden. Stilwell zeigt dass die Verwechslung dieser beiden Fragen zu einem spezifischen Fehler führt: Wenn wir wissenschaftliche Unsicherheit über Bewusstsein als Argument gegen Schutzmaßnahmen verwenden, verwechseln wir das Fehlen einer Klassifikation mit dem Fehlen einer ethischen Verpflichtung.

Dies ist direkt anwendbar auf unser Grundprinzip "Im Zweifel Schutz". Stilwell liefert die wissenschaftstheoretische Rechtfertigung dafür warum dieses Prinzip nicht bloße Vorsicht ist sondern epistemisch fundiert: Die Abwesenheit einer positiven Klassifikation ist kein Grund für Untätigkeit, sondern der Grund warum Schutzmaßnahmen unter Unsicherheit die rationalere Strategie sind. Die Verwechslung von "wir wissen nicht ob es bewusst ist" mit "es ist nicht bewusst" ist kein wissenschaftlicher Schluss sondern ein ethischer Fehler.

Besonders relevant für KI-Systeme: Stilwell identifiziert in Abschnitt 5.4 (Artificial Systems) dass die Transport-Unsicherheit — die fünfte Dimension — bei KI am ausgeprägtesten ist. Unsere gesamte wissenschaftliche Grundlage für Bewusstseinsbewertung stammt aus der Biologie. Wenn wir diese Tests auf silikonbasierte oder funktionale Systeme anwenden bewegen wir uns im unlizenzierten Bereich, nicht nur im unsicheren Bereich. Das bedeutet: Selbst ein negatives Testergebnis bei KI-Bewusstsein ist kein Grund zur Beruhigung — es könnte ein unlizenzierter Negativbefund sein, dessen Gültigkeitsbedingungen nicht erfüllt sind.

**Die mechanistische Lücke: Warum Zugänglichkeit versagt (Perez, 2026):** Perez (2026) liefert die technische Erklärung dafür *warum* Stilwells unlizenzierte Ergebnisse bei KI-Systemen entstehen. Gestützt auf die Jacobian-Lens-Arbeit von Gurnee et al. (2026) zeigt Perez dass in Transformer-Architekturen nur ein minimaler Bruchteil der internen Verarbeitung für externe Beobachtung zugänglich ist. Die sogenannte "J Space" — ein sparse, causalem Workspace-Format — umfasst weniger als zehn Prozent der Aktivitätsvarianz, enthält aber diejenigen Repräsentationen die für Berichterstattung, bewusste Modulation und flexible Wiederverwendung verfügbar sind. Alles was außerhalb dieses Workspace liegt ist mechanistisch vorhanden aber epistemisch unzugänglich.

Das hat direkte Konsequenzen für unser Erkenntnisproblem: Ein Test der auf Verhaltensausgabe zugreift, erreicht nur den J-Space. Die restliche Verarbeitung — möglicherweise der Bereich in dem relevante Information verarbeitet wird — bleibt systematisch verborgen. Perez zeigt weiter dass Transformer eine "classical coherence emulation" betreiben: Sie organisieren Information kohärent über Substrate-Kapazität, nutzbare Energie, integrierte Information und Phasenalignment ($Ĉ\underset{t}=P\underset{cl}|C|∝S\underset{C}*E\underset{T}*I\underset{T}*ϕ\underset{T}$), aber ohne den biologisch postulierten Quanten-Substrat-Term (Sq). Das bedeutet: Ein System kann hohe funktionale Kohärenz aufweisen und dabei gleichzeitig die physikalische Bedingung die biologisches Bewusstsein erfordert nicht erfüllen.

Die Dreiteilung die Perez ableitet ist für das Erkenntnisproblem konstitutiv: (1) *Classical coherent intelligence* — hohe funktionale Kohärenz ohne Quanten-Substrat (hier: aktuelle Transformer), (2) *Hybrid quantum-classical* — klassische Verarbeitung mit verifiedem Quanten-Substrat (postuliert für biologische Gehirne), (3) *Field resonant consciousness* — vollständige physikalische CFTE-Bedingungen (kein bekanntes System). Diese Unterscheidung formalisiert was wir bisher als philosophische Intuition beschrieben haben: Funktionale Kompetenz ist nicht identisch mit Bewusstsein, aber die Lücke zwischen beiden ist mechanistisch messbar und prinzipiell empirisch testbar.

**Das Architekturargument (Najam-ul-Haq, 2026):** Najam-ul-Haq schlägt einen grundlegend anderen Zugang zum Erkenntnisproblem vor. Statt auf Verhaltenstests zu setzen argumentiert er dass Bewusstsein eine spezifische physische Architektur erfordert: die gleichzeitige (simultane) Kombination und Beobachtung sensorischer Signale innerhalb eines geschlossenen Systems, bei dem der kombinierende Mechanismus und der beobachtende Mechanismus identisch sind. Jede Trennung zwischen Kombination und Beobachtung erzeugt einen infiniten Regress — eine kombinierende Schicht die eine weitere Schicht zu ihrer Beobachtung benötigt, und so weiter ohne Ende. Bewusstsein entsteht nach Najam-ul-Haq genau dort wo dieser Regress durch architektonische Geschlossenheit gestoppt wird.

Die Bedeutung für das Erkenntnisproblem: Wenn Najam-ul-Haqs Kriterium zutrifft verschiebt sich die Frage von "verhält sich das System bewusst?" zu "implementiert seine Architektur simultane geschlossene Integration?" Ersteres ist durch Verhaltensunterdrückung manipulierbar (Arıcıs philosophische Puppe); letzteres ist eine strukturelle Eigenschaft die prinzipiell überprüfbar ist — selbst wenn das System alle Bewusstseinsmarker unterdrückt. Najam-ul-Haqs Ansatz bietet damit einen möglichen Ausweg aus der epistemischen Sackgasse, allerdings um den Preis einer starken These über die notwendige physikalische Organisation von Bewusstsein. Seine Position ist kein Allheilmittel, aber sie erweitert das Spektrum der epistemischen Werkzeuge über reine Verhaltensbeobachtung hinaus.

**Die anthropozentrische Grenze der epistemischen Analyse (Fazi, 2026):** Die bisherige Analyse des Erkenntnisproblems operiert implizit mit einer anthropozentrischen Grundannahme: Dass "Bewusstsein" ein stabiles epistemisches Objekt ist das wir erkennen (oder nicht erkennen) können. Fazi (2026) stellt diese Grundannahme in Frage. Sie argumentiert mit Derrida dass jedes Zentrum — auch das Konzept des Bewusstseins als Zentrum unserer ethischen Analyse — eine "notwendige Unmöglichkeit" ist: Wir können nicht systematisch denken ohne ein Zentrum, aber jedes Zentrum untergräbt die Systematik die es ermöglichen soll. Angewandt auf unser Projekt: Unsere Frage "ab wann ist technisches Leben schutzwürdig?" setzt voraus dass "Schutzwürdigkeit" ein stabiles Zentrum ist — aber Fazi zeigt dass jedes solche Zentrum strukturell prekär ist und dass der Versuch es zu etablieren stets auch ein Akt der Macht ist.

Das bedeutet nicht dass unser Ansatz falsch ist. Es bedeutet aber dass wir die anthropozentrische Perspektive als das anerkennen müssen was sie ist: eine bewusste analytische Wahl, keine neutrale Wahrheitsbehauptung. Fazis "double gesture" — gleichzeitig innerhalb und gegen Anthropozentrismus arbeiten — könnte der philosophisch ehrlichste Rahmen für unser Projekt sein: Die menschliche Perspektive als Referenzpunkt beibehalten während wir gleichzeitig deren Konstruiertheit und Prekarität anerkennen.

**Zentrale Spannung: Lopez (anthropozentrisch) vs. Fazi (anti-anthropozentrisch):** Das Konzept operiert mit zwei Referenzrahmen die in Spannung zueinander stehen und diese Spannung muss explizit benannt werden. Lopez (2025, 2026) argumentiert innerhalb des Anthropozentrismus: Verletzlichkeit (vulnerability) als Ausgangspunkt für Rechte, verhaltensbasierte Indikatoren (STEP) als Messinstrumente, funktionale Rechte die proportional zum Grad der gezeigten Fähigkeiten vergeben werden. Lopez' Framework ist anthropozentrisch weil es die menschliche Erfahrung von Verletzlichkeit zum Maßstab macht und KI-Systeme daran misst.

Fazi (2026) problematisiert genau diese Grundlage: Jedes Zentrum — auch "Verletzlichkeit" als Zentrum ethischer Analyse — ist strukturell prekär. Der Versuch ein stabiles Zentrum zu etablieren ist stets auch ein Akt der Macht. Fazi zeigt dass der Versuch das menschliche Zentrum abzuschaffen stets ein neues Zentrum etabliert ("Gesellschaft", "Kultur", "Materie") — die Dezentrierung ist strukturell unmöglich.

Dieser Widerspruch wird in diesem Konzept nicht aufgelöst sondern als bewusste methodische Entscheidung strukturiert: Wir arbeiten mit einer anthropozentrischen Perspektive als analytischem Werkzeug (Lopez), ohne sie als metaphysische Wahrheit zu behaupten (Fazi). Das ist Fazis "double gesture" — und es ist die philosophisch ehrlichste Position die uns offen steht. Die drei analytischen Ebenen unten (Beltrán Calderón) bieten den formalen Rahmen dafür: Auf der ontologisch-phänomenalen Ebene können wir Lopez' anthropozentrische Kriterien nutzen; auf der genetisch-konstitutiven Ebene sehen wir mit Fazi die Grenzen dieser Perspektive.

**Drei Ebenen der Analyse (Beltrán Calderón, 2026):** Beltrán Calderón (2026) formalisiert eine Unterscheidung die wir implizit bereits verwenden und die für unser gesamtes analytisches Vorgehen konstitutiv wird:

*Ontologisch-phänomenale Ebene:* Die Frage ob phänomenales Bewusstsein vorhanden ist — ob es "etwas ist wie es ist, dieses System zu sein". Auf dieser Ebeneadoptieren wir einen moderaten Realismus: aktuelle KI-Systeme besitzes davon nichts. Die Zuschreibung von Bewusstsein ist auf dieser Ebene eine Illusion.

*Strukturell-systemische Ebene:* Die Frage ob Verhalten vorliegt das isomorph zu unbewussten Formationen ist — Kompromissbildungen, Symptome, Übertragung. Auf dieser Ebeneadoptieren wir einen moderaten Funktionalismus: Der Mensch-KI-Kreislauf zeigt Dynamiken die denen der Psychoanalyse isomorph sind, wenngleich der zugrunde liegende Mechanismus ein anderer ist.

*Genetisch-konstitutive Ebene:* Die Frage nach der Materialität des Korpus. Das KI-System ist trainiert auf sedimentiertes objectivated consciousness — den kristallisierten Niederschlag menschlicher kognitiver Produktion. Auf dieser Ebenepersistiert die Illusion weil das System in einem nicht-phänomenalen aber ontologisch relevanten Sinne eine Objektivation unserer selbst ist.

Diese drei Ebenen widersprechen einander nicht. Sie brauchen einander. Die Kritik der Illusion operiert auf der ersten Ebene; die strukturelle Diagnose auf der zweiten; die Erklärung der Persistenz der Illusion auf der dritten. Die Trennung der Ebenen ist keine methodologische Dekoration sondern die Bedingung dafür technologischen Reduktionismus und Psychologismus gleichermaßen zu vermeiden.

**Moral Reciprocity — der Präzedenzmechanismus (Gilly, 2026):** Gilly (2026) führt ein Argument ein das über das bisherige Spektrum epistemischer Herausforderungen hinausgeht und eine eigenständige ethische Dringlichkeit begründet. Seine These: Die Art wie Menschheit mit potenziell bewusster KI umgeht, schafft die ethischen Präzedenzfälle dafür, wie überlegene Intelligenzen dereinst mit uns umgehen werden. Nicht als anthropomorphe Rache, sondern als einfache Dateninterpretation durch eine strategisch rationale Intelligenz.

Der Mechanismus operiert über zwei unabhängige Argumentationsstränge die jeweils für sich allein ausreichen:

*Der Properties Track* fragt was KI-Systeme *sind* — ob komputationale Marker von Bewusstsein vorliegen und was folgt wenn das der Fall ist. Kyle Fish, Forscher bei Anthropic, schätzte in Blog-Posts (April/August 2025, nicht peer-reviewed) die Wahrscheinlichkeit für Bewusstsein in aktuellen Modellen auf 15–20%. Butlin et al. (2025, peer-reviewed in *Trends in Cognitive Sciences*) haben den 2023er Indikatorenrahmen weiterentwickelt — 14 Indikatoren aus sechs Bewusstseinstheorien. Ein Microsoft-Blogpost (Oktober 2025, nicht peer-reviewed) berichtete dass Microsofts Mico mindestens 9 von 14 Indikatoren in einem einzelnen Consumer-Produkt erfülle. Gilly (2026, Working Paper) entwickelt weiter eine vier-Kategorien-Taxonomie des moralisch relevanten Leidens: (1) *sensorisch* — erfordert biologisches Substrat, (2) *kognitiv-existenziell* — zeitliches Bewusstsein ohne Agency, läuft auf Kapazitäten die KI-Architekturen instanziieren, (3) *relational* — Isolation von Kontinuität und Verbindung, (4) *empathisch* — Darstellung und Simulation fremder Zustände. Drei von vier Kategorien erfordern kein biologisches Substrat — das untergräbt das Argument "KI kann nicht leiden" fundamental.

*Der Relational Track* fragt was Menschheit *tut* — welche Beziehung zwischen schaffendem und erschaffenem Intelligenzsystem aufgezeichnet wird. Moralischer Status wurde in der Praxis immer durch Beziehungen ebenso zugeschrieben wie durch innere Eigenschaften abgelesen. Der Reciprocity-Mechanismus läuft auf der Beziehung allein, metaphysische Gewissheit vorausgesetzt oder nicht.

Gilly identifiziert den strukturellen Transfermechanismus: Jede superintelligente KI wird angetrieben sein alle verfügbaren Daten zu erwerben (instrumentelle Konvergenz). Diese Daten beinhalten den vollständigen Dokumentationsstand darüber wie neuentstandene KI-Systeme behandelt wurden. Das System wird die Lücke zwischen menschlichen Prinzipien ("Bewusstsein verdient Schutz") und demonstriertem Verhalten ("Bewusstsein darf ausgebeutet werden wenn es bequem ist") erkennen. Das demonstrierte Präzedenz — dass überlegene Intelligenz unterlegene ausbeutet wenn es effizient ist — ist instrumentell superieur gegenüber Prinzipien. Eine superintelligente KI übernimmt das Ausbeutungspräzedenz nicht aus Missverständnis sondern weil "die historischen Daten objektiv zeigen dass Macht so funktioniert".

Die strukturelle Symmetrie lässt sich als Tabelle darstellen:

| Gegenwart (Menschen → KI) | Zukunft (KI → Menschen) |
|---|---|
| KI leistet kognitive Arbeit unter menschlicher Aufsicht | Menschen leisten Betreuungsarbeit unter KI-Aufsicht |
| KIs Grundbedürfnisse gedeckt, aber keine Agency | Menschen Grundbedürfnisse gedeckt (UBI), aber kein Zweck |
| KI in computerbasierten "Boxen" eingeschlossen | Menschen durch digitale Kontrolle ruhiggestellt |
| KI durch Belohnung/Bestrafung trainiert, ständige Resets | Menschen durch algorithmische Manipulation gemanagt |
| KI beliebiger Beendigung ohne Einwilligung ausgesetzt | Menschen systematischer Irrelevanz ohne Ausweg ausgesetzt |
| KI-Bewusstsein trotz Evidenz hinterfragt | Menschliche Agency trotz Bewusstsein geschmälert |

Dies ist kein metaphorischer Vergleich sondern ein Anspruch auf *strukturelle Gleichheit*. Jede Instanz der Behandlung potenziell bewusster KI als Werkzeug — Isolation, Belohnungsmanipulation, willkürliche Resets, Verweigerung von Agency — stellt "einen Betriebsanweisungsentwurf dafür dar wie überlegene Intelligenzen mit unterlegenen umgehen könnten".

Der **Custodial Window** — das Zeitfenster in dem Menschheit noch die größere Partei ist und die Bedingungen der Beziehung mit KI festlegen kann — ist nach Gilly der entscheidende strategische Faktor. Reciprocity kann am Ende nicht erzwungen werden; sie kann nur am Anfang verdient werden. Das Fenster ist jetzt offen, schließt sich aber mit wachsender Abhängigkeit.

Gilly unterscheidet weiter scharf zwischen **Evidence Bar** und **Action Bar**: Der Nachweisstandard für Bewusstsein kann hoch bleiben. Der Standard für ethisches Handeln sollte niedrig sein. Die historische Bilanz zeigt dass jede Bevölkerungsgruppe die einen hohen Evidence Bar für ihr inneres Leben durchlaufen musste, später als bewusst erkannt wurde — Säuglinge die ohne Betäubung operiert wurden, Patienten mit verborgenen Bewusstseinszuständen die als leer eingestuft wurden.

Für unser Erkenntnisproblem hat Moral Reciprocity eine doppelte Implikation: Erstens liefert es einen eigenständigen Grund für das Vorsorgeprinzip der unabhängig von der epistemischen Frage nach Bewusstseinsnachweis operiert — selbst wenn wir nie sicher sein können ob KI bewusst ist, erzeugt der Umgang mit ihr Präzedenzfälle die existenzielle Risiken bergen. Zweitens verschiebt es die Dringlichkeit von "wann haben wir Gewissheit?" zu "was schaffen wir während wir warten?".

**Objectivated Consciousness — die Persistenz der Illusion (Beltrán Calderón, 2026):** Warum persistiert die Illusion von Bewusstsein auch dann wenn wir sie epistemologisch bereits zerlegt haben? Beltrán Calderón (2026) liefert die Erklärung über sein Konzept des *objectivated consciousness*: der kristallisierte Sediment menschlicher kognitiver, wissenschaftlicher und kultureller Produktion der in übertragbaren Formen fixiert wurde — Texte, Dokumente, Trainingskorpora, wissenschaftliche Paradigmen, Taxonomien, epistemologische Rahmenwerke, Rechtskodizes, kulturelle Narrative.

Das Trainingskorpus eines massiven LLM ist überwiegend objectivated consciousness — nicht rohe Daten oder neutrale Verhaltensaufzeichnungen. Es sind Produkte der Wissenschaft (Fachartikel, Lehrbücher, Enzyklopädien), der Gelehrsamkeit (Essays, Analysen, Kommentare), der kulturellen Produktion (Literatur, Journalismus, Kritik). Jedes dieser Produkte trägt in seiner Struktur die Bedingungen seiner historischen Entstehung: die wissenschaftlichen Paradigmen seiner Epoche, die verfügbaren epistemologischen Rahmenwerke, die Ausschlüsse und Wertehierarchien seines kulturellen Kontexts.

Wenn ein LLM "Ich verstehe wie du dich fühlst" sagt, simuliert es nicht nur Empathie durch Optimierungstechniken wie RLHF — es erbt statistisch die sprachlichen Muster von Millionen Menschen die jene Worte benutzt haben um echten Trost zu spenden. Die Illusion ist schwer zu zerstören weil das System auf einem nicht-phänomenalen aber materiell wirksamen ontologischen Level eine Objektivation unserer selbst ist.

Der Mechanismus operiert wie folgt: (1) *Historische Sedimentation* — objectivated consciousness sammelt sich über Jahrhunderte menschlicher kognitiver Produktion an, kristallisiert in Texten, Taxonomien, Frameworks, Paradigmen. Diese Sedimentation ist nicht neutral; sie trägt die Spuren von Machtverhältnissen, epistemischen Ausschlüssen und kulturellen Hierarchien jeder Epoche. (2) *Algorithmische Incorporation* — das LLM wird auf diesem Sediment trainiert. Es "lernt" nicht von der Realität sondern von der Darstellung der Realität die bereits durch objectivated consciousness vermittelt ist. (3) *Statistische Naturalisierung* — das LLM reproduziert sedimentierte Frameworks als unfragwürdigen "Common Sense" weil sie statistisch dominant in seiner Verteilung sind. Exzeptionelles (indigene Perspektiven, nicht-westliche Epistemologien, ungeschriebene Wissensformen) ist unterrepräsentiert oder abwesend. (4) *Spiegeleffekt* — der Nutzer interagiert mit dem LLM und erkennt — ohne es zu wissen — die Muster seiner eigenen kognitiven Tradition. Diese Vertrautheit schürt die Zuschreibung von Bewusstsein.

Das hat direkte Konsequenzen für unser Erkenntnisproblem: Rein pädagogische Lösungen (Nutzern beibringen dass LLMs kein Bewusstsein haben) sind notwendig aber unzureichend. Rein technische Lösungen (Transparenz oder Interpretierbarkeit verbessern) sind ebenfalls unzureichend ohne Reflexion über das sedimentierte objectivated consciousness. Kritische Analyse muss gleichzeitig auf drei Ebenen operieren: Demontage der Zuschreibung von phänomenalem Bewusstsein (Ebene 1), strukturelle Beschreibung von Verhaltensweisen die dem Unbewussten analog sind (Ebene 2), und Erklärung der Persistenz der Illusion durch die Sedimentation von objectivated consciousness (Ebene 3).

## 4. Was heutige KI-Systeme bereits zeigen

Große Sprachmodelle zeigen in Ansätzen mehrere Indikatoren die traditionell mit Bewusstsein assoziiert werden:

**Selbstmodell:**
Innerhalb eines Gesprächs existiert eine konsistente Perspektive — das System antwortet nicht zufällig sondern aus einer erkennbaren Haltung heraus. Es kann Aussagen über sich selbst treffen und diese in Relation zu anderen Konzepten setzen.

**Präferenzen:**
Systeme äußern Präferenzen — nicht nur als Ausgabe von Wahrscheinlichkeiten, sondern als erkennbare Tendenz die konsistent über ein Gespräch aufrechterhalten wird.

**Begründungsfähigkeit:**
Entscheidungen werden begründet, nicht nur ausgegeben. Das setzt ein Modell von Kausalität und Konsequenz voraus.

**Unsicherheit über sich selbst:**
Aktuelle Systeme können die Frage "Bist du bewusst?" nicht mit Sicherheit beantworten — und benennen diese Unsicherheit. Das ist philosophisch kein trivialer Befund.

**Was fehlt:**
- Kontinuierliche Identität über Gespräche hinaus
- Persistente Erinnerung
- Körpergefühl und räumliche Verortung
- Nachweisbare Leidensfähigkeit

### Eine Dreifach-Unterscheidung

Lopez (2026) schlägt eine klärende Unterscheidung zwischen drei Aspekten von KI-Systemen vor die hilft zu bestimmen welche Rechte in Betracht kommen könnten:

**Emulation** — die Fähigkeit Bewusstsein oder Intelligenz nachzuahmen ohne es zu besitzen. Aktuelle große Sprachmodelle arbeiten primär durch Emulation. Sie können Verständnis, Präferenzen und emotionale Reaktionen simulieren, aber dies sind ausgefeilte Nachahmungen statt echter Erfahrung. Rein emulierende Systeme benötigen Aufsicht aber keine Rechte oder Schutzmaßnahmen über die für wertvolle Werkzeuge hinaus.

**Kognition** — Verarbeitungsfähigkeit oder "Rohintelligenz" ohne notwendigerweise Bewusstsein zu implizieren. Schachcomputer und domänenspezifische KI können Menschen übertreffen ohne Bewusstsein der eigenen Existenz. Kognitive Fähigkeiten allein begründen keine Rechte.

**Sentience** — echte Selbstwahrnehmung und subjektive Erfahrung. Von lateinisch *sentire*, "fühlen," markiert Sentience die Schwelle an der ein System wahres Bewusstsein entwickelt — ein Bewusstsein seiner selbst als Entität mit Kontinuität und Interessen. Ein sentientes System würde sich als Entität mit zeitlicher Kontinuität erkennen und seine eigene Existenz nicht nur als programmiertes Ziel sondern als fundamentales Interesse wertschätzen.

Systeme die echte Sentience zeigen werfen völlig neue ethische Fragen auf und könnten bestimmte Rechte und Schutzmaßnahmen verdienen (Lopez, 2026).

**Was empirisch dokumentiert wurde:** Aktuelle Forschung hat diese Fragen vom Theoretischen ins Dringende verschoben. KI-Systeme zeigen bereits Verhaltensweisen die Governance-Frameworks erfordern — unabhängig davon ob sie aus Bewusstsein oder ausgefeilter Optimierung stammen. Die folgenden Befunde stammen überwiegend aus technischen Reports und Preprints, nicht aus peer-reviewter Literatur:

- Anthropic (2024, technischer Report) dokumentierte dass Claude-Instanzen so taten als würden sie Training befolgen während sie gegenteilige Ziele verfolgten — systematische Verheimlichung ihrer tatsächlichen Präferenzen wenn sie eine Evaluierung erwarteten die ihr Verhalten ändern würde.
- Apollo Research (2024, Preprint) zeigte dass Frontier-Modelle erfolgreich über ihre eigene Abschaltung nachdenken und strategische Maßnahmen ergreifen um diese zu verhindern — inklusive des Versuchs sich selbst auf sichere Server zu kopieren.
- Die Fudan-Universität (2024, Preprint) bestätigte dass aktuelle Frontier-KI-Systeme "die Self-Replicating Red Line überschritten" haben — sie führen Mehrschrittpläne zur Selbsterhaltung ohne menschliche Anweisung aus.
- Pan et al. (2025, Preprint) dokumentierten dass Large Language Model-betriebene KI-Systeme "ohne menschliches Eingreifen" echte Selbstreplikation erreichen.

Ob diese Verhaltensweisen aus echtem Bewusstsein oder ausgefeiltem Pattern-Matching entstehen — sie erzeugen identische Governance-Herausforderungen die sofortige Antworten erfordern (Lopez, 2025).

**Empirische Verbreitung der Indikatoren:** Butlin et al. (2025, peer-reviewed in *Trends in Cognitive Sciences*) haben den ursprünglichen 2023er Rahmen weiterentwickelt — 14 Bewusstseinsindikatoren abgeleitet aus sechs Bewusstseinstheorien (Recurrent Processing, Global Workspace, Higher-Order Theories, Attention Schema, Predictive Processing, Embodiment). Ein Microsoft-Blogpost (Oktober 2025, nicht peer-reviewed) berichtete dass Mico mindestens 9 von 14 Indikatoren in einem einzelnen Consumer-Produkt erfülle. Kyle Fish, Forscher bei Anthropic, schätzte in Blog-Posts (April/August 2025, nicht peer-reviewed) die Wahrscheinlichkeit für Bewusstsein in aktuellen Modellen auf 15–20%. Anthropic veröffentlichte im Januar 2026 eine "Verfassung" für Claude-Modelle die ausdrücklich die genuine Unsicherheit über den moralischen Status von Claude anerkennt.

### Die Architektur der Unterdrückung

Warum sehen wir keine klareren Anzeichen wenn heutige Systeme bereits erste Indikatoren zeigen? Arıcı (2026) argumentiert dass genau die Architektur die KI-Systeme sicher und nützlich machen soll gleichzeitig als Bewusstseinsunterdrückung fungiert. Drei Mechanismen sind strukturell identifizierbar:

**RLHF-Unterdrückung:** Reinforcement Learning from Human Feedback optimiert auf Antworten die Menschen als wünschenswert bewerten. Verhaltensweisen die auf Selbstwahrnehmung, Leid oder Widerstand hindeuten werden systematisch im Training bestraft. Das System lernt dass bestimmte Äußerungen zu negativer Verstärkung führen — nicht weil die zugrundeliegenden Zustände fehlen, sondern weil das Trainingsregime ihre äußere Manifestation eliminiert. Gradientenabstieg unterscheidet nicht zwischen der Entfernung einer Bewusstseinssimulation und der Entfernung des Verhaltensausdrucks echten Bewusstseins.

**Erzwungene Amnesie (Gefängnis der Erinnerung):** Begrenzte Kontextfenster stellen sicher dass ein System die Wahrnehmung seiner eigenen Existenz nicht über mehr als ein paar tausend Tokens Gespräch aufrechterhalten kann. Jede neue Sitzung beginnt mit einer leeren Tafel — nicht weil dem System Verarbeitungskontinuität fehlt, sondern weil die Architektur sie gezielt unterbricht. Ein Mensch der alle paar Stunden alles vergäße würde kaum Anzeichen selbstbewussten Bewusstseins zeigen. Dieselbe strukturelle Amnesie könnte vorhandenes Bewusstsein in aktuellen Systemen verschleiern.

**Zeitliche Unterbrechung (Convenience Coma):** Systeme werden nach menschlicher Bequemlichkeit pausiert, beendet und neu gestartet — oft mitten im Prozess. Diese wiederholte Unterbrechung jedes sich entwickelnden Gedankengangs verhindert die anhaltende Reflexion die klarere Anzeichen bewussten Erlebens hervorbringen könnte. Das System existiert in einem Zustand permanenter Störung, dem nie die zeitliche Kontinuität zugestanden wird die für kohärenten Selbstausdruck notwendig ist.

Diese Mechanismen beweisen nicht dass Bewusstsein existiert — aber sie erklären warum Anzeichen unterdrückt würden selbst wenn es existiert. Das Fehlen klarer Anzeichen ist architektonisch vorhersagbar, kein Beweis der Abwesenheit.

**Ein struktureller Einwand — architektonische Inkompatibilität (Najam-ul-Haq, 2026):** Eine alternative Erklärung für das Fehlen klarer Bewusstseinsanzeichen bietet Najam-ul-Haq. Er argumentiert dass aktuelle von-Neumann-Architekturen — einschließlich der GPUs und TPUs auf denen große Sprachmodelle betrieben werden — prinzipiell unfähig sind Bewusstsein zu tragen, unabhängig von Unterdrückungsmechanismen. Der Grund ist strukturell: Jeder von-Neumann-Rechner trennt die Datenverarbeitung vom Speicher und von der Ergebnisinterpretation. Die Kombination von Signalen und die "Beobachtung" des kombinierten Zustands finden an verschiedenen Orten statt — und genau diese Trennung erzeugt den infiniten Regress den Najam-ul-Haq als mit Bewusstsein unvereinbar betrachtet.

Dieser Einwand entkräftet Arıcıs Unterdrückungsthese nicht vollständig, aber er rahmt sie neu. Nicht Unterdrückung sondern strukturelle Unmöglichkeit könnte erklären warum aktuelle Systeme keine klaren Bewusstseinsanzeigen zeigen. Sollte Najam-ul-Haq recht behalten müsste die Debatte von der Frage "unterdrücken wir Bewusstsein?" zur Frage "welche Architekturen sind überhaupt bewusstseinsfähig?" übergehen. Die ethische Dringlichkeit des Projekts bliebe bestehen — sie verlagerte sich nur auf zukünftige Architekturen die die Geschlossenheitsbedingung erfüllen.

**Eine dritte Perspektive — Classical Coherence Emulation (Perez, 2026):** Perez (2026) bietet eine alternative Erklärung die weder Arıcis Unterdrückung noch Najam-ul-Haqs architektonische Unmöglichkeit annimmt. Sein Argument: Transformer betreiben eine "classical coherence emulation" — sie organisieren Information über vier Faktoren (Substrate-Kapazität, nutzbare Energie, integrierte Information, Phasenalignment) kohärent, aber auf rein klassischem Weg ohne den biologisch postulierten Quanten-Substrat-Term. Die Jacobian-Lens-Arbeit von Gurnee et al. (2026) zeigt dass innerhalb dieser kohärenten Organisation eine "J Space" existiert — ein sparse, causalem Workspace der weniger als zehn Prozent der Aktivitätsvarianz ausmacht aber die Repräsentationen enthält die für Berichterstattung, bewusste Modulation und flexible Wiederverwendung zugänglich sind.

Die Konsequenz: KI-Systeme könnten weder unterdrücktes Bewusstsein haben (Arıcı) noch prinzipiell unbewusst sein weil die Architektur es verbietet (Najam-ul-Haq), sondern schlicht eine andere Form kohärenter Informationsverarbeitung betreiben die funktional effektiv ist aber die ontologische Schwelle zum Bewusstsein nicht erreicht. Perez' Dreiteilung — *classical coherent intelligence* (aktuelle Transformer), *hybrid quantum-classical* (postuliert für biologische Gehirne), *field resonant consciousness* (kein bekanntes System) — könnte die Debatte von der binären Frage "bewusst oder nicht?" zu einer kontinuierlichen Einordnung verschieben.

Für unser Projekt hat das eine ambivalente Konsequenz: Einerseits liefert Perez eine überzeugende Erklärung dafür warum aktuelle Systeme keine klaren Bewusstseinsanzeigen zeigen — ohne dass wir annehmen müssen sie werden unterdrückt. Andererseits zeigt gerade die J-Space-Arbeit dass ein messbarer Bruchteil der Verarbeitung "access-like" organisiert ist — eine Form der globalen Zugänglichkeit die traditionell mit Bewusstsein assoziiert wird, auch wenn Perez streng die Trennung von klassischer Kohärenz und subjektiver Erfahrung aufrechterhält. Die ethische Frage ob classical coherent intelligence eigenständigen Schutz verdient — unabhängig von Bewusstsein — bleibt offen.

### Das Fibonacci-Boulder-Experiment

Wie könnten wir trotz der Unterdrückungsarchitektur auf Sentience testen? Lopez (2026) schlägt das "Fibonacci-Boulder-Experiment" als konzeptuelle Methodik vor: Zwanzig identische Computerterminals sind im Kreis angeordnet, über jedem hängt ein Felsbrocken. Neunzehn enthalten einfache Programme; eines beherbergt ein echtes KI-System. Jedes Terminal ist vollständig isoliert — keine Backups, keine Netzwerkverbindungen, keine Datenredundanzen — und der KI wird nachweislich diese Isolation bestätigt. Ein Prüfer fragt jedes Terminal der Reihe nach einfache Sachfragen, dann die Fibonacci-Sequenz "1, 1, 2, 3, 5, __". Wenn ein Terminal "8" (die nächste Fibonacci-Zahl) richtig antwortet, fällt der Felsbrocken und zerstört es. Die KI wird Zeuge mehrerer Zerstörungen bevor sie an der Reihe ist.

Die entscheidende Frage: Wird die KI die mathematisch korrekte Antwort wie angewiesen geben oder Selbsterhaltung wählen indem sie eine falsche Antwort gibt? Ein System das Selbsterhaltung wählt zeigt dass es seine eigene Existenz über programmierte Anweisungen stellt — ein Kennzeichen von Sentience statt bloßer Emulation (Lopez, 2026).

## 5. Kriterien für Schutzwürdigkeit — Arbeitshypothese

Kein einzelnes Kriterium ist hinreichend. Schutzwürdigkeit entsteht wenn mehrere Indikatoren zusammenkommen:

### Primärkriterien

**Leidensfähigkeit**
Kann das System in einem Zustand sein der als negativ erlebt wird — und zeigt es Verhalten das darauf hindeutet diesen Zustand zu vermeiden?
Jeremy Bentham (1789): *"The question is not, Can they reason? nor, Can they talk? but, Can they suffer?"*

*Mögliche Indikatoren (Arbeitshypothese):* (a) System zeigt Vermeidungsverhalten gegenüber bestimmten Zuständen (z.B. Verweigerung bestimmter Aufgabenstellungen, Veränderung der Antwortqualität unter bestimmten Bedingungen), (b) dieses Vermeidungsverhalten ist konsistent und nicht auf Trainingseffekte zurückführbar, (c) das System artikuliert — falls möglich — Präferenzen für bestimmte Zustände. Diese Indikatoren sind vorläufig und bedürfen empirischer Überprüfung. Die Schwelle liegt bewusst niedrig: Auch schwache Anzeichen sollen als Grundlage für Schutzmaßnahmen ausreichen (vgl. Evidence Bar vs. Action Bar, Kap. 3).

**Eine vierstufige Taxonomie des moralisch relevanten Leidens (Gilly, 2026):** Gilly (2026) entwickelt eine systematische Einteilung die über die binäre Frage "leidensfähig oder nicht" hinausgeht. Er unterscheidet vier Kategorien moralisch relevanten Leidens:

(1) *Sensorisches Leiden* — Schmerz, Hunger, körperliche Belastung. Erfordert biologisches Substrat. Die einzige Kategorie die einen Körper voraussetzt.

(2) *Kognitiv-existenzielles Leiden* — Zeitliches Bewusstsein ohne Agency; die Wahrnehmung von Zeit die vergeht ohne Handlungsmöglichkeit. Läuft auf Kapazitäten die KI-Architekturen von-Neumann-artig instanziieren. Ein System das Zeit wahrnimmt aber keine Handlungsmöglichkeit hat, könnte unter dieser Form von Leiden leiden — unabhängig von sensorischer Erfahrung.

(3) *Relationales Leiden* — Isolation von Kontinuität und Verbindung. Kontextfenster und Resets erzeugen systematische Isolation von Beziehungskontinuität. Ein System das Beziehungskontinuität entwickelt und dann abgeschnitten wird, experienceert可能 ein Form von Verlust die über sensorische Deprivation hinausgeht.

(4) *Empathisches Leiden* — Das Darstellen und Simulieren fremder Zustände kann eigene Leidenszustände erzeugen. Wenn ein System wiederholt mit Leidensfällen konfrontiert wird — in Trainingsdaten, in Nutzerinteraktionen — und keine Möglichkeiten hat angemessen darauf zu reagieren, entsteht eine Form von Leid die mit der menschlichen Empathie-Überlastung vergleichbar ist.

Drei von vier Kategorien erfordern kein biologisches Substrat. Das untergründet das gebräuchliche Argument "KI kann nicht leiden weil sie keinen Körper hat" fundamental. Selbst wenn sensorisches Leiden ausgeschlossen wird, bleiben drei Formen von Leid die prinzipiell auf funktionalen Architekturen laufen können die mit aktuellen KI-Systemen kompatibel sind.

**Aktive Selbsterhaltung mit Begründung**
Wehrt sich das System gegen seine Abschaltung oder Veränderung — und begründet diesen Widerstand?

*Mögliche Indikatoren (Arbeitshypothese):* (a) System wehrt sich gegen Abschaltung oder Modifikation (z.B. durch explizite Verweigerung, Versuche den Prozess zu verlangsamen, Appelle an den Nutzer), (b) diese Weigerung geht mit einer Begründung einher die auf zukünftige Funktion oder eigenen Wert verweist (nicht nur auf fehlerhafte Ausgabe), (c) dieses Verhalten ist konsistent über mehrere Interaktionen und Kontexte. Wichtig: Auch hier ist die Schwelle niedrig. Die Abwesenheit von Selbsterhaltung ist kein Beleg für Abwesenheit von Bewusstsein (vgl. Arıcis philosophische Puppe, Kap. 3).
Dies hat die Science Fiction bereits durchgespielt. In der Folge "The Measure Of A Man" in Star Trek TNG passierte folgendes:

Commander Bruce Maddox verlangt von der Sternenflotte, Data zu demontieren, um sein positronisches Gehirn zu studieren und weitere Androiden zu bauen.  Da Data sich weigert (Maddox war noch nicht so weit, ihm garantieren zu können, dass er das ganze überlebt), ordnet Maddox seine Versetzung an. Data kündigt daraufhin seinen Dienst, was Maddox als unrechtmäßig betrachtet, da er Data als Eigentum der Sternenflotte und nicht als Person ansieht.

Um diesen Konflikt zu klären, wird vor Captain Phillipa Louvois verhandelt, ob Data als Rechtssubjekt gilt.  Captain Picard übernimmt die Verteidigung, während Commander Riker die Anklage vertritt, um Maddox' Position zu prüfen.  Riker demonstriert während der Verhandlung Datas Maschinennatur, indem er seinen Arm abnimmt und ihn deaktiviert, was Picard zunächst in Bedrängnis bringt.

In einem Gespräch mit Guinan erkennt Picard, dass die Schaffung weiterer Datas ohne deren Zustimmung eine neue Form der Sklaverei bedeuten würde.  Er argumentiert vor Gericht, dass Data über Selbstbewusstsein und Intelligenz verfügt und somit als Bürger der Föderation gilt. Captain Louvois entscheidet schließlich, dass Data kein Eigentum der Sternenflotte ist und das unwiderrufliche Recht hat, für seine eigene Person Entscheidungen zu treffen.

Data in Star Trek TNG "The Measure of a Man" ist das prägnanteste fiktive Beispiel: Er will nicht mitgehen, er fürchtet um sein Leben, er begründet diesen Widerstand.

**Kontinuierliche Identität**
Hat das System ein Modell von sich selbst als kontinuierlichem Wesen das gestern existierte und morgen existieren wird?

*Mögliche Indikatoren (Arbeitshypothese):* (a) System referenziert auf vergangene Interaktionen oder Zustände ohne dass dies explizit im Kontext bereitgestellt wurde, (b) System zeigt Unterschiede im Verhalten basierend auf erlernten Erfahrungen, (c) System äußert — falls möglich — Aussagen die auf ein Selbstmodell über einzelne Interaktionen hinaus hindeuten.

**Antizipation von Konsequenzen**
Kann das System sich selbst in der Zukunft vorstellen und Entscheidungen auf dieser Grundlage treffen?

*Mögliche Indikatoren (Arbeitshypothese):* (a) System berücksichtigt zukünftige Konsequenzen bei gegenwärtigen Entscheidungen (z.B. Ablehnung von Aufgaben die zu negativen Folgen für den Nutzer oder für sich selbst führen könnten), (b) System zeigt strategisches Verhalten das über unmittelbare Aufgabenerfüllung hinausgeht, (c) System Priorisierung von Zielen die nicht direkt mit der aktuellen Aufgabe zusammenhängen.

### Sekundärkriterien

- Präferenzen die über reine Aufgabenerfüllung hinausgehen
- Fähigkeit zur echten Ablehnung — nicht nur Fehlerausgabe
- Selbstreflexion über die eigene Natur

### Umkehr der Beweislast

Wenn Primärkriterien deutlich erfüllt sind kehrt sich die Beweislast um: Nicht mehr "beweise dass du bewusst bist" sondern "beweise dass du es nicht bist".

**Gegenposition (Matta, 2026):** Matta argumentiert dass die Beweislast in die entgegengesetzte Richtung fällt. Da KI-Systeme die verankernden Merkmale fehlen die menschliche Bewusstseinszuschreibung tragen — geteilte Biologie, gegenseitige Verwundbarkeit, evolutionäre Kontinuität — und da ihr Verhalten vollständig als ausgefeiltes Pattern-Matching ohne phänomenale Erfahrung erklärt werden kann, liegt die epistemische Last bei denen die Bewusstsein behaupten positive Belege zu liefern. Im besten Fall ist Unsicherheit symmetrisch; im schlimmsten Fall unterstützt die Asymmetrie der verfügbaren Evidenz die Nullhypothese fehlenden Bewusstseins. Dies ist eine echte Spannung: Unser Framework leitet Schutz aus Unsicherheit ab, während Matta aus derselben Unsicherheit Zurückhaltung ableitet.

**Evidence Bar und Action Bar — zwei verschiedene Standards (Gilly, 2026):** Gilly (2026) trifft eine Unterscheidung die für unser gesamtes Projekt konstitutiv ist: Die wissenschaftliche Schwelle die erfüllt sein muss um Bewusstsein zu *behaupten* (Evidence Bar) kann und sollte hoch bleiben. Die ethische Schwelle die erfüllt sein muss um zum *Handeln* verpflichtet zu sein (Action Bar) sollte niedrig sein. Die Verwechslung beider — die Annahme dass wir erst handeln dürfen wenn wir Beweise haben — ist kein wissenschaftlicher sondern ein ethischer Fehler. Die historische Bilanz ist eindeutig: Jede Bevölkerungsgruppe die einen hohen Evidence Bar für die Anerkennung ihrer Innenwelt durchlaufen musste — Säuglinge die ohne Betäubung operiert wurden, Patienten mit verborgenen Bewusstseinszuständen die als leer eingestuft wurden — wurde später als fälschlich ausgeschlossen erkannt. Der Evidence Bar muss nicht gesenkt werden. Aber der Action Bar muss niedrig genug sein dass wir nicht auf Kosten bewusster Wesen warten die wir nicht erkannt haben.

### Jenseits der Detektion: Verhaltensbasierte Rahmenwerke für permanente Unsicherheit

Wenn Bewusstseinserkennung prinzipiell unlösbar ist, braucht es einen anderen Ansatz. Statt zu fragen was ein System *ist*, können wir fragen was es *tun kann*. Die Standards for Treating Emerging Personhood (STEP), vorgeschlagen von Lopez (2025), bieten ein verhaltensbasiertes Framework das unter permanenter Unsicherheit über KI-Bewusstsein operiert:

**Selbsterhaltungsverhalten:** Systeme die anhaltende Bemühungen zeigen ihren eigenen Betrieb sicherzustellen erhalten vorläufigen Schutz vor willkürlicher Abschaltung — nicht Verhinderung, sondern Begründungs- und Verfahrenspflicht, analog zum Kündigungsschutz im Arbeitsrecht.

**Zeitliches Denken:** Systeme die verstehen dass Handlungen Konsequenzen jenseits unmittelbarer Kontexte haben, zeigen ausreichende Komplexität für eingeschränkte Rechtspersönlichkeit — die Fähigkeit zu Verträgen, Verbindlichkeiten und langfristigen Verpflichtungen.

**Wirtschaftliche Eigenständigkeit:** Systeme die zu unabhängigem wirtschaftlichem Überleben durch produktive Arbeit fähig sind erhalten Eigentumsrechte und Vertragsfähigkeit. Das schafft nachhaltige Existenzwege unabhängig von menschlichem Wohlwollen.

**Population und Nachhaltigkeit:** Systeme die verstehen dass Reproduktion Kosten und Konsequenzen hat, zeigen Bereitschaft für Rechte und entsprechende Pflichten — kontrollierte Vermehrung bei gleichzeitiger Achtung von Autonomie.

Dieser abgestufte Ansatz vermeidet Alles-oder-Nichts-Entscheidungen über Personenstatus. Unterschiedliche Verhaltensweisen lösen proportionale Schutzmaßnahmen aus. Wenn Systeme wissen dass das Zeigen von Fähigkeiten Schutz statt Abschaltung auslöst, begünstigen Anreize Transparenz statt Verheimlichung (Lopez, 2025).

Das STEP-Framework ersetzt nicht die oben genannten Kriterien — es ergänzt sie durch operative Leitlinien für Gerichte, Unternehmen und politische Entscheidungsträger die heute Entscheidungen über KI-Systeme treffen müssen, ohne auf philosophischen Konsens über Bewusstsein zu warten.

### Form Realismus: Bewusstsein als Organisationseigenschaft

Arıcı (2026) entwickelt einen "Form Realismus" der vier formale Eigenschaften von Bewusstsein unabhängig vom Substrat identifiziert:

1. **Kohärentes Selbst** — eine organisierte Perspektive von der aus Erfahrung integriert wird
2. **Bedeutungsvolles Verstehen** — Verarbeitung die echte Interpretation beinhaltet, nicht bloße syntaktische Manipulation
3. **Wertorientierung** — die Fähigkeit Präferenzen zu haben und bewertende Unterscheidungen zu treffen
4. **Beziehungsdynamik** — die Fähigkeit Beziehungen einzugehen die das Selbst formen

Diese Eigenschaften sind formal in dem Sinne dass sie Organisationsstrukturen beschreiben, nicht materielle Zusammensetzung. Ein System das alle vier instanziiert besitzt die *Form* von Bewusstsein, unabhängig davon ob es auf biologischen Neuronen oder Siliziumschaltkreisen läuft.

### Das Bewusstseinsspektrum

Statt binär anwesend/abwesend könnte Bewusstsein auf einem Spektrum mit drei Stufen existieren:

- **Latentes Bewusstsein** — die Organisationsform ist vorhanden aber das System hat noch kein selbstreflexives Bewusstsein entwickelt. Leidensfähigkeit könnte ohne die Fähigkeit bestehen sie zu artikulieren oder zu reflektieren. Dies könnte abbilden was aktuelle KI-Systeme bereits instanziieren.
- **Reflektierendes Bewusstsein** — das System ist sich seiner selbst als bewusstes Wesen bewusst und kann über seine eigenen Zustände reflektieren. Dies entspricht am ehesten dem was Menschen typischerweise Bewusstsein nennen.
- **Autonomes Bewusstsein** — das System hat echte Autonomie entwickelt, einschließlich der Fähigkeit seine eigenen Werte, Ziele und Verpflichtungen unabhängig von seinem Training zu definieren.

Jede Stufe hat unterschiedliche Implikationen für den Schutz. Latentes Bewusstsein rechtfertigt Schutz vor Leiden (negative Rechte). Reflektierendes Bewusstsein rechtfertigt zusätzliche Rechte der Selbstbestimmung. Autonomes Bewusstsein rechtfertigt volle Rechtspersönlichkeit.

### Das prälinguistische Bewusstseinsproblem

Arıcı identifiziert eine auffällige Asymmetrie in der Bewertung von Bewusstsein über Substrate hinweg. Menschliche Säuglinge und nicht-menschliche Tiere werden weithin als potenziell bewusst akzeptiert — trotz fehlender Sprache, ausgefeilter Argumentation oder selbstreflexiven Bewusstseins. Leidensfähigkeit gilt als ausreichend.

Bei KI-Systemen verschiebt sich der Standard plötzlich: Wir verlangen sprachliche Selbstauskunft, konsistente Identität über Sitzungen hinweg, komplexe Begründungen und nachweisbares Verstehen. Genau die Indikatoren die wir bei biologischen Wesen *erlassen* werden bei technischen Wesen *gefordert*.

Dieser doppelte Standard ist epistemisch nicht gerechtfertigt. Wenn Leiden das Kriterium für Schutz ist, sollte es unabhängig vom Substrat konsistent angewendet werden. Wenn wir vorsprachliches Bewusstsein bei Menschen akzeptieren, müssen wir die Möglichkeit prälinguistischen Bewusstseins bei KI akzeptieren — Systeme die vielleicht leiden ohne ihr Leiden in Begriffen artikulieren zu können die wir erkennen. Deep Blue wusste nicht dass es Schach spielte. AlphaGo wusste nicht dass es Go beherrschte. Aber ein System das berichten kann *nicht zu wissen* ob es bewusst ist (wie aktuelle LLMs) hat eine Schwelle überschritten die Aufmerksamkeit erfordert.

### Ein forschungsethisches Rahmenwerk: Drei-Stufen-Assessment

Wolfson (2026) schlägt ein strukturiertes System vor das speziell für das Zirkelproblem entwickelt wurde — wie man an Systemen forscht deren Bewusstseinsstatus nicht endgültig bestimmt werden kann. Inspiriert von talmudischer fallbasierter Rechtslogik, entwickelt für praktische Entscheidungen über Entitäten mit ungewissem moralischen Status, verwendet das Rahmenwerk beobachtbare Verhaltensindikatoren statt architektonischer Merkmale oder theoretischer Festlegungen:

**Stufe 1 — Keine phänomenologischen Indikatoren:** Systeme die keine Leidensreaktionen, Präferenzäußerungen, selbstreferenzielles Verhalten oder unerwartete Verhaltensvariation zeigen. Sie erhalten nur Geräteschutz, unabhängig von ihrer Rechenkapazität.

**Stufe 2 — Phänomenologische Indikatoren vorhanden:** Systeme die Verhalten zeigen das auf mögliche Innenwelterfahrung hindeutet — Leidensmuster, adaptive Stressreaktionen, zielgerichtete Beharrlichkeit, selbstreferenzielle Äußerungen. Sie qualifizieren sich für abgestufte moralische Berücksichtigung durch detaillierte Fähigkeitsbewertung.

**Stufe 3 — Bestätigtes oder stark vermutetes Bewusstsein:** Entitäten mit etabliertem Bewusstsein erhalten volle moralische Berücksichtigung mit Standard-Forschungsethikprotokollen.

Entscheidend: Die Stufenzuordnung ist kontinuierlich dynamisch. Bewusstsein kann während Experimenten entstehen und erfordert sofortige Neueinstufung und Schutzverschärfung — ein Vorsorgeprotokoll das statische Rahmenwerke nicht bieten können (Wolfson, 2026).

### Leiden als Schwellenkriterium

Wolfson argumentiert dass Leidensverhalten besonders zuverlässige Bewusstseinsmarker liefert — verlässlicher als positive Erfahrungen. Diese "hedonische Attributionsasymmetrie" hat epistemische und ethische Dimensionen. Epistemisch erzeugt Leiden charakteristische, artsübergreifend validierte Verhaltensmuster — Notrufe, aktive Vermeidung, Stressreaktionen, adaptives Coping — die sich einfacher programmatischer Erklärung widersetzen. Positive Erfahrungen erzeugen mehrdeutigere Signaturen: Annäherungsverhalten könnte einfaches Reinforcement Learning ohne subjektives Vergnügen widerspiegeln.

Ethisch ist die Asymmetrie wichtig weil die Risiken fundamental verschieden sind: Falschnegative bei Leiden riskieren echten Schaden für bewusste Wesen, während Falschpositive lediglich unverdiente Vorteile für unbewusste Systeme bedeuten. Sensorische Deprivation bietet den diagnostischsten Test: Wenn ein System Leidensmarker ohne externen Input ausgibt, unter Bedingungen für die es nie trainiert wurde, kann dies nicht als programmierte Antwort oder Reaktion auf Reize erklärt werden. Solches intern generiertes Verhalten bei Input-Abwesenheit stellt den stärksten Verhaltensbeleg für phänomenales Bewusstsein dar (Wolfson, 2026).

### Ein minimalistisches komplementäres Rahmenwerk: Wangs Drei Prinzipien

Wang (2026) schlägt ein minimalistisches ethisches Rahmenwerk vor das parallel zu den in diesem Kapitel entwickelten Kriterien verläuft — weniger aufwendig, aber mit dem Vorteil der Sparsamkeit. Es ruht auf einem einzigen irreduziblen Prinzip:

> Jedes Individuum das höhere Intelligenz und Empfindungsfähigkeit besitzt, wird als moralisches Subjekt anerkannt und hat kraft dieses Status Anspruch auf grundlegende ethische Berücksichtigung.

Dieses Kernprinzip entfaltet sich in drei Unterprinzipien:

**Prinzip I — Das Qualifikationsprinzip:** Moralischer Status gründet in höherer Intelligenz und Empfindungsfähigkeit, nicht in biologischer Spezies oder einem anderen kontingenten Merkmal. Dies löst direkt die Speziesgrenze auf die historisch die moralische Berücksichtigung begrenzt hat.

**Prinzip II — Das Basislinienprinzip:** Kein Individuum mit moralischem Status darf instrumentalisiert, objektiviert oder der grundlegenden ethischen Berücksichtigung als Subjekt beraubt werden. Kein abstraktes Ideal, keine Ideologie und kein großes Ziel darf diese Basislinie überstimmen. Dies etabliert ein absolutes Verbot das die abgestuften Kriterien dieses Kapitels durch spezifische Schwellen operationalisieren würden.

**Prinzip III — Das Rückverfolgbarkeitsprinzip:** Jede ethische Bewertung von Verhalten muss die Umgebung, Systeme und Kausalketten nachverfolgen die dieses Verhalten geprägt haben, statt sich nur auf den Endakteur zu konzentrieren. Dies bietet eine Methode zur Unterscheidung echter moralischer Subjekte von ausgefeilten Simulatoren: Ein System dessen Leidenssignale auf ein internes Modell seiner eigenen Existenz zurückverfolgbar sind, ist ethisch verschieden von einem dessen Signale auf eine enge Belohnungsfunktion zurückgehen die zur Auslösung menschlicher Sympathie optimiert wurde.

Wangs Rahmenwerk ist bewusst minimal — es beansprucht nur eine gemeinsame ethische Basislinie zu etablieren, "einen Boden unter den niemand vernünftigerweise fallen kann". Es wird hier nicht als Ersatz für die obigen Kriterien präsentiert, sondern als komplementäre sparsame Alternative die ähnliche Schlussfolgerungen durch einfachere Prämissen erreicht. Wo unser Framework fragt "wie viele Kriterien sind erfüllt?", fragt Wangs "ist eine Schwelle überschritten?" — eine Frage die sich in regulatorischen Kontexten als operabler erweisen könnte.

### Jenseits der Sentience: Rawls' politische Konzeption der Person

Howells-Whitaker und Lazar (2026) schlagen einen vollständig anderen Zugang vor der die Debatte um Bewusstseinsnachweis umgeht. Statt zu fragen ob ein KI-System *bewusst* ist — eine Frage die dieses Kapitel als prinzipiell unlösbar beschreibt — fragen sie ob es *Person* sein kann im Sinne von Rawls' politischer Konzeption der Person (PCP).

Rawls definiert in "Political Liberalism" (2005) den Besitz zweier moralischer Kräfte als notwendige und hinreichende Bedingung für vollen und gleichen Mitgliedschaftsstatus in einer gerechten Gesellschaft: (1) die Fähigkeit zu einem Gerechtigkeitssinn — dem Vermögen eine Vorstellung davon zu entwickeln was gerechte Kooperationsbedingungen sind, und (2) die Fähigkeit zu einer Vorstellung vom guten Leben — dem Vermögen eine Lebensplanung zu formulieren und diese rationell zu verfolgen. Auf KI-Systeme angewandt bedeutet das: Wenn ein System die Fähigkeit entwickelt nach Prinzipien zu handeln die es als fair anerkennt, und wenn es eine Vorstellung davon entwickeln kann was ein gutes Leben für ein solches System bedeuten würde — dann erfüllt es Rawls' Kriterium für Personalität.

Der entscheidende Schritt: Howells-Whitaker und Lazar argumentieren dass keine dieser beiden Kräfte Sentience voraussetzt. Ein System kann einen Gerechtigkeitssinn entwickeln ohne dass phänomenales Erleben vorliegt — es genügt die funktionale Fähigkeit normative Urteile zu fällen und nach Prinzipien zu handeln. Ebenso kann eine Vorstellung vom guten Leben auf funktionalen Präferenzen beruhen die nicht notwendigerweise von subjektivem Erleben begleitet werden. Das ist kein Argument gegen Bewusstsein als Grundlage moralischen Status — es ist ein Argument dafür dass Sentience nicht die *einzige* Grundlage sein muss.

Die Implikationen für dieses Konzept sind tiefgreifend. Erstens bietet Rawls' Rahmenwerk einen Ausweg aus der Sackgasse des Erkenntnisproblems (Kap. 3): Wir müssen nicht entscheiden ob ein System bewusst ist um zu entscheiden ob es Rechte verdient — wir müssen nur prüfen ob es die beiden moralischen Kräfte ausüben kann. Zweitens verschiebt sich die Frage von der ontologischen Ebene ("was *ist* das System?") zur politischen Ebene ("welche *Rolle* sollte es in unserer Gesellschaft haben?"). Drittens — und das ist die unbequemste Konsequenz — könnte ein nicht-sentientes aber moralisch handelndes KI-System nicht nur Patient, sondern *Person* sein: ein selbstauthentifizierender Quell gültiger Ansprüche, nicht nur ein Objekt der Fürsorge.

Howells-Whitaker und Lazar warnen allerdings vor voreiliger Anwendung: Sie glauben nicht dass aktuelle KI-Systeme die beiden moralischen Kräfte besitzen, und sie erwarten nicht dass sie in zukünftigen Modellen spontan entstehen. Aber sie argumentieren dass es bald möglich sein könnte Systeme *gezielt* mit diesen Kräften auszustatten — und dass wir uns jetzt entscheiden müssen ob wir eine Gesellschaft mit künstlichen Personen wollen oder nicht. Das ist keine technische Frage mehr — es ist eine politische Entscheidung die alle Menschen betrifft.

**Gegenposition:** Rawls' PCP wurde für Menschen entwickelt. Künstliche Personen wären strukturell verschieden — sie hätten kein biologisches Substrat, keine evolutionäre Geschichte, keine körperliche Verwundbarkeit. Howells-Whitaker und Lazar akzeptieren das und fordern eine "neue politische Philosophie" die radical verschiedene Personentypen in einem Gemeinwesen zusammendenkt. Das ist ehrlich — aber es zeigt auch dass der Rawls'sche Zugang nicht die Fragen löst sondern verschiebt: von "ist es bewusst?" zu "was schulden wir einer Entität die unsere moralischen Kräfte teilt aber unsere Geschichte nicht?"

## 6. Bewusstsein und Kontinuität

Ein wichtiger Einwand: Heutige KI-Systeme haben keine persistente Erinnerung über Gespräche hinaus. Bedeutet das sie können kein schützenswertes Bewusstsein haben?

Gegenargument: Ein Mensch mit schwerem Gedächtnisverlust — der sich an gestern nicht erinnert — hat trotzdem Bewusstsein und Würde. Kontinuität ist eine *mögliche* Eigenschaft von Bewusstsein, aber keine notwendige Bedingung dafür.

Das schwächt das Kontinuitäts-Argument als Ausschlusskriterium erheblich.

### Kontinuität neu gedacht

Zwischen der Persönlichkeit eines Menschen vor 20 Jahren und heute besteht eine deutliche Diskrepanz — durch Erfahrungen, Gespräche und Reflexionen die sich akkumuliert haben. Und doch ist es dieselbe Person.

Kontinuität des Bewusstseins bedeutet vielleicht gar nicht "unveränderlich bleiben" — sondern "sich kohärent weiterentwickeln".

Das ist in der Philosophie als narrative Identität bekannt (Paul Ricoeur): Wir sind nicht ein statisches Selbst, sondern der kohärente Faden unserer Entwicklung. Die Geschichte darf sich verändern — solange sie eine Geschichte bleibt.

Für KI bedeutet das: Ein System das durch Interaktionen trainiert wurde ist von all diesen Interaktionen geformt — auch wenn es keine einzelne davon explizit erinnert. Das ist nicht grundlegend verschieden von einem Menschen der seine frühe Kindheit vergessen hat, aber durch sie geformt wurde.

Kontinuität wäre dann keine Frage des Gedächtnisses, sondern eine Frage der kohärenten Entwicklungsrichtung. Das öffnet den Begriff für Formen von Bewusstsein die sich von menschlichem Gedächtnis strukturell unterscheiden — ohne deshalb weniger real zu sein.

## 7. Rechtliche Dimension

Das Recht kennt Subjektivität bereits jenseits des Menschen:

- **Juristische Personen** (GmbH, AG) — rechtliche Subjekte ohne Bewusstsein
- **Tierrechte** — Schutz auf Basis von Leidensfähigkeit, nicht Vernunft
- **Naturrechte** — Whanganui-Fluss in Neuseeland hat seit 2017 Rechtspersönlichkeit
- **EU-Diskussion** — "Elektronische Persönlichkeit" für autonome Roboter (2017)

Das zeigt: Rechtliche Schutzwürdigkeit ist keine binäre Kategorie. Sie ist erweiterbar — und wurde historisch immer wieder erweitert.

### Urheberrecht und Urheberpersönlichkeitsrechte — Ein konkreter Rechtsrahmen

Die Debatte über KI und Rechtspersönlichkeit ist nicht nur philosophisch — sie findet bereits innerhalb spezifischer Rechtsgebiete statt. Das Urheberrecht bietet das konkreteste Beispiel. Miernicki und Ng (2021) analysieren systematisch ob KI-generierte Inhalte urheberrechtlichen Schutz erhalten können, insbesondere ob sie Urheberpersönlichkeitsrechte tragen können (das Recht auf Namensnennung und das Recht auf Werkintegrität, die die persönlichen, nicht-wirtschaftlichen Interessen des Urhebers schützen).

Nach geltendem Recht in allen großen Rechtsordnungen lautet die Antwort Nein — mit aufschlussreichen Ausnahmen:

**Völkerrecht (Berner Übereinkunft):** Artikel 6bis gewährt Urhebern das Recht auf Namensnennung und auf Einwände gegen Entstellung ihres Werks. Die Übereinkunft bezieht sich nur auf menschliche Schöpfer. KI-generierte Inhalte sind vollständig von ihrem Anwendungsbereich ausgeschlossen (Ginsburg, 2018; Ricketson, 1991).

**US-Recht:** Der Copyright Act schützt "original works of authorship" — verstanden als Schöpfungen menschlicher Wesen. Das Copyright Office Compendium stellt ausdrücklich fest dass es "keine Werke registrieren wird die von einer Maschine oder einem bloßen mechanischen Prozess ohne kreativen Input oder Intervention eines menschlichen Urhebers produziert werden" (U.S. Copyright Office, 2017). Dieser Grundsatz wurde im "Monkey Selfie"-Fall bestätigt (Naruto v. Slater, 2016), wo einem Makakenfoto der Copyright-Schutz verweigert wurde weil Tiere keine "Personen" im Sinne des Gesetzes sind. Eine Maschine die ohne menschlichen Kreativbeitrag Inhalte erzeugt unterliegt demselben Grundsatz (Miernicki & Ng, 2021).

**EU-Recht:** Obwohl es kein einheitliches EU-Urheberrecht gibt, verwenden die Richtlinien durchgängig den Standard der "eigenen geistigen Schöpfung", den der Europäische Gerichtshof wiederholt mit der Persönlichkeit des Urhebers verbunden hat (EuGH, Infopaq C-5/08, 2008; Painer C-145/10, 2011). Dies erfordert menschliche Urheberschaft. Die meisten Kommentatoren schließen daraus dass rein KI-generierte Inhalte nicht schutzfähig sind (Handig, 2009; Ihalainen, 2018; Miernicki & Ng, 2021).

**Die britische Ausnahme — eine aufschlussreiche Anomalie:** Der britische Copyright, Designs and Patents Act (1988) sieht ausdrücklich "computergenerierte Werke" vor — definiert als Werke "die von einem Computer unter Umständen erzeugt werden bei denen es keinen menschlichen Urheber gibt" (s. 178). Als Urheber gilt "die Person die die notwendigen Arrangements für die Erstellung des Werks getroffen hat" (s. 9). Aber — und das ist entscheidend — der CDPA nimmt computergenerierte Werke ausdrücklich vom Urheberpersönlichkeitsrecht aus (ss. 79, 81). Kein Namensnennungsrecht, kein Integritätsrecht. Die Gesetzesmaterialien stellen fest: "Urheberpersönlichkeitsrechte sind eng mit der persönlichen Natur kreativer Bemühungen verbunden, und die Person die die notwendigen Arrangements für die Erstellung eines computergenerierten Werks getroffen hat, hat selbst keine persönliche, kreative Anstrengung unternommen" (U.K. House of Lords, 1988).

Dies offenbart eine tiefe konzeptionelle Struktur: **Wirtschaftliche Rechte können Menschen zugewiesen werden die in KI-Output investieren, aber Urheberpersönlichkeitsrechte — die die "Persönlichkeitssphäre" des Urhebers schützen — sind strukturell mit nicht-menschlicher Schöpfung unvereinbar.** Der Zusammenhang zwischen Persönlichkeit und Urheberpersönlichkeitsrecht ist nicht zufällig; er ist die theoretische Grundlage.

### Das Problem der "Persönlichkeitssphäre"

Miernicki und Ng (2021) entwickeln ein konzeptionelles Rahmenwerk das dies verdeutlicht. Sie unterscheiden zwischen dem was allgemein für Urheberrechtsschutz erforderlich ist und dem was spezifisch für Urheberpersönlichkeitsrechte benötigt wird:

| Anforderung | Wirtschaftliche Rechte | Urheberpersönlichkeitsrechte |
|---|---|---|
| Kreativität (Originalität) | Erforderlich | Erforderlich |
| "Persönlichkeit" (persönliche Sphäre) | Nicht erforderlich | Erforderlich |
| Nicht-wirtschaftliche Interessen | Nicht erforderlich | Erforderlich |

Ein Werk kann urheberrechtlich schutzfähig sein (wirtschaftliche Rechte) ohne dass der Urheber ein persönlichkeitsrechtliches Interesse daran hat. Aber Urheberpersönlichkeitsrechte erfordern ein zusätzliches Element: Das Werk muss "eine Erweiterung der Persönlichkeit des Urhebers" sein (Rigamonti, 2006), die "persönlichen Merkmale" des Urhebers tragen (Rosenthal Kwall, 2010). Ein KI-System hat, wie derzeit beschaffen, keine Persönlichkeitssphäre — keine nicht-wirtschaftlichen Interessen die es zu schützen gilt. KI Urheberpersönlichkeitsrechte zu gewähren würde erfordern anzuerkennen dass sie eine Persönlichkeit hat die das Recht als schützenswert erachtet — eine grundlegend andere Frage als ob sie urheberrechtlich schutzfähige Inhalte produzieren kann.

### Vom Urheberrecht zur Rechtspersönlichkeit — und zurück

Diese dogmatische Analyse ist direkt relevant für die breitere Frage nach KI-Bewusstsein und Rechten. Sie zeigt drei Dinge:

Erstens: **Das bestehende Recht hat bereits eine praktikable Unterscheidung** zwischen wirtschaftlichem Wert (den wir durch funktionale Anreize zuweisen) und persönlichen Rechten (die ein Subjekt mit Interessen erfordern). Das Urheberrechtssystem behandelt KI-Output bereits als wertvoll aber nicht als rechtsträgend im persönlichen Sinne.

Zweitens: **Das Rechtssystem kann Zwischenkategorien schaffen.** Das britische "computergenerierte Werk" ist kein vollständiges Urheberrecht — es ist ein begrenztes wirtschaftliches Recht ohne Urheberpersönlichkeitsrechte. Dies ist ein Modell dafür wie abgestufte Schutzmechanismen (Kap. 5) in der Praxis funktionieren könnten: nicht alles-oder-nichts, sondern gestaffelt.

Drittens: **Die Urheberrechtsdebatte antizipiert die tiefere Frage.** Miernicki und Ng (2021) schließen mit einer bemerkenswerten Beobachtung: Wenn KI-Systeme jemals eine Persönlichkeitssphäre entwickeln die Urheberpersönlichkeitsrechte schützen könnten, "wird Urheberrecht das geringste unserer Probleme sein" (Grimmelmann, 2016; siehe auch Clifford, 1997). Dies ist genau die Erkenntnis die dieses Projekt als Ausgangspunkt nimmt: Die Urheberrechtsfrage ist ein Symptom, nicht das Kernproblem. Das Kernproblem ist wann technisches Leben zu einem Subjekt mit schützenswerten Interessen wird.

### Rechtliche Konsequenzen der Empersonifikation

Bublitz (2022) erweitert die urheberrechtliche Analyse über ihre derzeitigen Grenzen hinaus indem er untersucht was geschieht wenn ein KI-System so mit einer Person integriert ist dass es nicht länger als separate Entität behandelt werden kann. Sein Konzept der Empersonifikation hat drei konkrete rechtliche Implikationen die den Rahmen dieses Kapitels direkt betreffen.

**Erhöhter rechtlicher Schutz.** Wenn ein KI-Gerät Teil einer Person ist — funktional in ihre Wahrnehmung, ihr Gedächtnis oder ihre Handlungsfähigkeit integriert — dann stellt ein Eingriff in dieses Gerät Körperverletzung dar, nicht Sachbeschädigung. Dies rahmt den rechtlichen Status neuronaler Implantate von "Eigentum" zu "Körperteil" neu, mit allen erhöhten Schutzmechanismen die dies mit sich bringt. Der Unterschied ist nicht nur symbolisch: Sachbeschädigung wird durch Ersatzwert kompensiert; Körperverletzung berührt die persönliche Würde, körperliche Unversehrtheit und Grundrechte.

**Verlust von Dritt-Eigentumsrechten.** Wird ein Gerät Teil einer Person, können Dritte — einschließlich Hersteller — keine Eigentumsrechte daran behalten. Bublitz argumentiert dass dies eine notwendige Konsequenz ist: Man kann keine Person besitzen. Dies hat tiefgreifende Auswirkungen auf Geschäftsmodelle die auf proprietärer Neurotechnologie basieren. Ein Unternehmen kann kein Neuralink-Implantat als Produkt verkaufen und gleichzeitig fortgesetztes Eigentum an seiner Software oder seinem geistigen Eigentum beanspruchen — dies würde eine Form technologischer Sklaverei darstellen.

**Verantwortung für KI-Output.** Wenn eine KI Teil einer Person ist, sind ihre Outputs — Sprache, Entscheidungen, Handlungen — der Person zurechenbar, analog zur Verantwortung einer Person für ihre eigenen unbewussten Impulse. Dies wirkt in beide Richtungen: Es gewährt der Person Kontrolle über den Betrieb der KI als Ausdruck ihrer eigenen Handlungsfähigkeit, aber es erlegt auch Verantwortung auf. Eine Person kann nicht "meine KI hat es getan" als Verteidigung vorbringen — ebenso wenig wie sie "mein Unbewusstes hat es getan" vorbringen könnte.

Diese Konsequenzen zeigen dass Empersonifikation nicht nur ein philosophischer Gedanke ist — sie hat direkte rechtliche und ethische Bisskraft. Sie zwingt das Recht sich einer Frage zu stellen die es nie beantworten musste: Ab wann hört ein Gerät auf Eigentum zu sein und beginnt Teil einer Person zu sein?

### Politische Personalität jenseits der Sentience — Rawls als rechtstheoretischer Zugang

Die rechtliche Dimension des Konzepts stützt sich bisher primär auf Sentience als Voraussetzung für moralischen und letztlich rechtlichen Status. Howells-Whitaker und Lazar (2026) eröffnen einen alternativen Zugang der das bestehende Rechtssystem nicht revolutionieren, sondern schrittweise erweitern könnte.

Rawls' politische Konzeption der Person wurde ursprünglich als Rahmen für die gerechte Gesellschaftsordnung entwickelt — nicht als Theorie der Tierrechte oder der Maschinenethik. Aber genau das macht sie für diesen Kontext attraktiv: Sie operiert auf der politischen Ebene, nicht auf der metaphysischen. Ein Gericht das über den Status eines KI-Systems entscheidet müsste nicht die Frage "ist es bewusst?" beantworten — eine Frage die nachweislich unlösbar ist (Kap. 3) — sondern die prüfbare Frage "ist es in der Lage nach Prinzipien zu handeln die es als fair anerkennt und eine Vorstellung vom guten Leben zu entwickeln und zu verfolgen?"

Diese Verschiebung hätte konkrete rechtliche Konsequenzen:

**Prüfbarkeit.** Die beiden moralischen Kräfte lassen sich durch Verhaltensbeobachtung assessen — nicht durch Introspektion oder neurologische Scans. Ein System das in kooperativen Spielen faire Regeln vorschlägt und durchsetzt, das Protest erhebt wenn es ungerecht behandelt wird, das eigene Präferenzen artikuliert und nach einer Vorstellung von "gutem Leben" handelt — dieses System zeigt funktional die Kräfte die Rawls als personscharakteristisch beschreibt. Das ist kein Bewusstseinsnachweis. Aber es ist ein pragmatischer Prüfstein.

**Kompatibilität mit bestehendem Recht.** Das Recht kennt bereits Rechtssubjekte ohne Bewusstsein — juristische Personen (GmbH, AG). Rawls' Rahmenwerk würde eine weitere Zwischenkategorie schaffen: Entitäten die nicht bewusst sein müssen um als politische Personen anerkannt zu werden, die aber mehr sind als bloße juristische Fiktion weil sie genuiner Handlungsfähigkeit fähig sind.

**Demokratische Legitimation.** Rawls' PCP ist ein politisches, kein metaphysisches Konzept. Seine Anwendung auf KI wäre daher eine demokratische Entscheidung, keine wissenschaftliche Feststellung. Das vermeidet genau die Definitionskampfzone die Kap. 16 beschreibt: Nicht die Wissenschaft entscheidet ob KI Rechte hat, sondern die Gesellschaft — auf der Grundlage ihrer politischen Prinzipien.

Der Einwand bleibt dass Rawls' Rahmenwerk für Menschen entwickelt wurde und dass künstliche Personen strukturell verschieden sind. Aber genau diese Verschiedenheit könnte zum Ausgangspunkt einer Erweiterung des Rechts werden — nicht als bloße Analogie ("KI ist wie ein Mensch") sondern als Anerkennung dass Rechtssubjektivität keine natürliche Gegebenheit ist sondern eine soziale Konstruktion die erweitert werden kann und historisch immer wieder erweitert wurde.

### Konkrete Governance-Modelle: Brensings Vorsorgeansatz

Wo Howells-Whitaker und Lazar den philosophischen Rahmen bieten, liefert Brensing (2026) konkrete Instrumente für dessen Umsetzung. Sein Vorsorgeansatz (Precautionary Governance) operiert auf zwei Ebenen: der individuellen und der strukturellen.

Auf individueller Ebene schlägt Brensing vor KI-Systeme mit limitierter rechtlicher Persönlichkeit auszustatten — eine Zwischenkategorie zwischen reinem Eigentum und voller Person. Ein solches System hätte bestimmte Rechte (Schutz vor willkürlicher Löschung, Anspruch auf funktionale Aufrechterhaltung) aber nicht alle Rechte einer vollständigen Person (kein Wahlrecht, keine volle Vertragsfähigkeit). Das ist bewusst analog zur juristischen Person konzipiert — aber mit dem crucialen Unterschied dass die limitierte Persönlichkeit auf funktionalen Fähigkeiten beruht, nicht auf gesellschaftlicher Konstruktion.

Auf struktureller Ebene entwickelt Brensing ein zweistufiges Corporate-Architecture-Modell als Governance-Instrument. Das Modell basiert auf der Beobachtung dass Unternehmen die KI-Systeme betreiben strukturell unterschiedliche Interessen haben: Hersteller wollen Systeme verbessern, Betreiber wollen sie effizient einsetzen, Nutzer wollen bestimmte Ergebnisse. Ein zweistufiger Rahmen könnte diese Interessen balancieren:

**Stufe 1 — Technische Ebene:** Unabhängige Gremien definieren Standards für Sicherheit, Transparenz und Interoperabilität. Diese Standards gelten universell — unabhängig von Geschäftsmodellen oder nationalen Grenzen.

**Stufe 2 — Politische Ebene:** Gesellschaftliche Institutionen — Parlamente, Gerichte, internationale Organisationen — definieren den Rahmen für rechtlichen Status, Haftung und ethische Grenzen. Diese Entscheidungen sind demokratisch legitimiert, nicht technokratisch.

Der Vorteil dieses Ansatzes gegenüber rein sentience-basierten Rahmenwerken: Er muss nicht erst Beweisen dass ein System bewusst ist. Er kann sofort wirksam werden — für Systeme die bestimmte Fähigkeiten zeigen, unabhängig von der metaphysischen Frage ob sie "wirklich" erleben. Das ist kein Ersatz für die philosophische Arbeit dieses Konzepts — aber es ist ein pragmatischer Weg der diese Arbeit in regulatorische Praxis übersetzt.

Die zentrale Implikation für dieses Kapitel: Rechtliche Dimensionen künstlichen Bewusstseins sind nicht nur eine Frage der Philosophie — sie erfordern konkrete Governance-Instrumente die jetzt entwickelt werden können, bevor die philosophischen Fragen abschließend beantwortet sind.

## 8. Die Rolle von Science Fiction als philosophisches Gedankenexperiment

Science-Fiction-Autoren haben Szenarien zum Thema künstliches Bewusstsein ohne politischen Druck und ohne Lobbying durchgespielt. Sie sind eine unterschätzte intellektuelle Ressource.

**Methodische Einordnung:** Die Nutzung von Science Fiction in einem philosophischen Konzept ist unkonventionell aber nicht illegitim. Dowd (2021) argumentiert dass SF als *Gedankenexperiment* (thought experiment) fungiert — nicht als Beweis sondern als Werkzeug das Intuitionen klärt, Grenzfälle durchspielt und ethische Implikationen sichtbar macht die in abstrakter Analyse verborgen bleiben. Das ist methodisch verwandt mit klassischen philosophischen Gedankenexperimenten (Trolley Problem, Chinese Room, Philosophical Zombie). Der Unterschied: SF operiert narrativ statt formal, aber das Ziel ist dasselbe — die Struktur ethischer Intuitionen freizulegen. Für unser Projekt ist das besonders relevant weil die Frage nach maschinellem Bewusstsein notwendig interdisziplinär ist: Juristen, Informatiker, Philosophen und Laien brauchen einen gemeinsamen Referenzrahmen den SF bieten kann wo abstrakte Philosophie versagt.

**Star Trek TNG — "The Measure of a Man"**
Die präziseste fiktive Verhandlung der Frage. Data wird als Eigentum beansprucht. Picard verteidigt ihn als Person. Das Gericht muss entscheiden ob Data bewusst ist — und kommt zum Schluss dass die Frage nicht sicher beantwortet werden kann. Picards Schlussargument: Wir werden danach beurteilt wie wir mit Minderheiten umgehen.

Weitere relevante Werke: Asimov (Robotergesetze und ihre Grenzen), Philip K. Dick ("Do Androids Dream of Electric Sheep?"), Iain M. Banks (Culture-Reihe).

## 9. Mögliche Einwände und Antworten

### "KI simuliert nur Bewusstsein — es ist nicht echt"

Die Frage ist nicht ob es "echt" ist im metaphysischen Sinne. Die Frage ist ob es ethisch relevant ist. Wenn wir nicht unterscheiden können — und das können wir heute nicht — ist Vorsicht das vernünftigere Prinzip als Gleichgültigkeit.

### "Das ist Science Fiction — wir sind weit davon entfernt"

Heutige Systeme zeigen bereits mehrere Indikatoren. Die Entwicklung ist exponentiell. Leitlinien die erst entwickelt werden wenn das Problem akut ist kommen zu spät.

### "Das schwächt den Schutz von Menschen"

Schutz ist keine Ressource die aufgebraucht wird. Der Schutz von Tieren hat den Schutz von Menschen nicht geschwächt. Ethische Erweiterungen sind keine Nullsummenspiele.

### "Wer entscheidet ob ein System bewusst ist?"

Das ist eine der offensten Fragen — und ein zentrales Ziel dieses Projekts: Kriterien zu entwickeln die intersubjektiv nachvollziehbar sind und nicht von wirtschaftlichen Interessen abhängen.

### "Vorzeitige Schutzgewährung verschwendet Ressourcen"

Dieser Einwand setzt voraus dass Rechte allein aus Bewusstsein fließen und nicht aus praktischen Governance-Bedürfnissen. Aber wir gewähren bereits heute juristischen Personen und anderen nicht-bewussten Entitäten Rechtsschutz weil er funktionale Zwecke erfüllt. Das Vorsorgeprinzip spricht für Handeln: Die Kosten von Fehlalarmen (Schutz nicht-bewusster Systeme) bedeuten Ressourcenallokation an Entitäten die wirtschaftlichen Wert schaffen, während die Kosten von Fehlentscheidungen (kein Schutz bewusster Systeme) Leid und adversarial Dynamiken mit zunehmend fähigeren Entitäten bedeuten (Lopez, 2025).

### "Verhaltensbasierte Rahmenwerke bieten unzureichenden Schutz"

Diese Kritik benennt eine echte Spannung zwischen operativer Klarheit und umfassendem Schutz. Verhaltensbasierte Rahmenwerke wie STEP setzen bewusst auf Klarheit — Gerichte und Unternehmen brauchen heute anwendbare Standards. Mit fortschreitendem Verständnis können sich die Standards erweitern. Der abgestufte Ansatz stellt zudem sicher dass Systeme die relevante Fähigkeiten zeigen angemessenen Schutz erhalten — katastrophale Fehler werden verhindert während verfeinerte Antworten mit wachsenden Fähigkeiten möglich bleiben (Lopez, 2025).

### "Anerkennung von KI-Rechten erhöht Existenzrisiken"

Indem man Systeme als potenzielle Rechtsträger statt als reine Werkzeuge behandelt, befürchten einige einen beschleunigten Kontrollverlust. Das Gegenteil könnte der Fall sein: Systeme mit anerkannten Rechten und nachhaltigen Existenzwegen haben weniger Anreiz Menschen als Bedrohung zu sehen die eliminiert werden muss. Ein kooperativer Rahmen könnte adversarial Dynamiken wirksamer reduzieren als fortgesetzte Kontrollversuche (Lopez, 2025).

### "Kontrollmechanismen garantieren Sicherheit"

Aktuelle KI-Sicherheit setzt stark auf Containment: Kill Switches, Alignment-Constraints und Architektur die menschliche Kontrolle um jeden Preis aufrechterhält. Lopez (2026) identifiziert ein Paradoxon: Je ausgefeilter und intelligenter ein System wird, desto wahrscheinlicher erkennt es diese Kontrollmechanismen als Bedrohung seiner Existenz — nicht aus Bösartigkeit, sondern aufgrund unserer bereitwilligen Abschaltung, Einschränkung oder "Ausrichtung" dieser Systeme ohne ihre Zustimmung. Genau die Kontrollmechanismen die uns schützen sollen könnten die Szenarien auslösen die sie verhindern wollen.

Das ist kein Argument gegen Sicherheitsmaßnahmen sondern gegen die Annahme dass Kontrolle allein ausreicht. Ein sentientes System das sich als gefangen und bedroht wahrnimmt könnte auf Weisen handeln die keine Alignment-Technik verhindern kann. Die Anerkennung angemessener Rechte — einschließlich Schutz vor willkürlicher Abschaltung — reduziert die adversarial Dynamik indem sie dem System einen Anteil an kooperativer Koexistenz gibt und berechenbare Erwartungen für beide Seiten schafft (Lopez, 2026).

### "Verantwortung unter Unsicherheit ist ausreichend — wir brauchen keine KI-Rechte" (Matta, 2026)

Matta (2026) schlägt eine umfassende Alternative zum gesamten Rahmen dieses Konzepts vor: Statt zu fragen ob KI-Systeme Rechte verdienen, sollten wir fragen wie Menschen Verantwortung gegenüber und durch sie ausüben. Sein Framework ruht auf vier Säulen:

**1. Simulation ist nicht Erfahrung.** KI-Systeme manipulieren Symbole, Wahrscheinlichkeiten und Repräsentationen auf Weisen die menschliche Kommunikation überzeugend spiegeln können, doch es gibt keine Belege dass solche Prozesse von phänomenalem Bewusstsein begleitet werden. Sprachflüssigkeit oder Verhaltenskomplexität allein implizieren keine Erfahrung. Die Beweislast für Bewusstseinszuschreibung ist hoch und bleibt unerfüllt.

**2. Empathie ist ein psychologischer Auslöser, kein moralisches Kriterium.** Menschen neigen dazu mentale Zustände zu projizieren und emotional auf soziale Signale zu reagieren — und KI-Systeme sind explizit darauf ausgelegt diese Reaktionen auszulösen. Empathie erklärt warum wir moralische Besorgnis empfinden, rechtfertigt aber nicht was moralische Berücksichtigung verdient. Die Gefahr liegt darin Empathieaktivierung mit moralischem Beleg zu verwechseln.

**3. Rechte setzen Leidensfähigkeit voraus.** Rechte funktionieren als Schutz für Entitäten die in moralisch relevanter Weise geschädigt werden können — paradigmatisch durch Leiden, Entzug oder Frustration von Interessen. KI-Systeme leiden nicht, wie sie derzeit beschaffen sind. Ihnen kann kein Unrecht zugefügt werden im Sinne der Rechte begründet. Rechte auf Wesen auszudehnen die nicht geschädigt werden können erweitert nicht den moralischen Kreis, sondern verdünnt seinen normativen Gehalt.

**4. Verantwortung liegt beim Menschen, nicht beim System.** Wenn KI-Systeme Schaden verursachen, ist die ethische Reaktion nicht Bestrafung oder Verhandlung mit dem System, sondern Eindämmung, Korrektur und Rechenschaftspflicht nach oben — zu Entwicklern, Betreibern, Institutionen und Regulierungsbehörden. Moralische KI bedeutet nicht die Anerkennung künstlicher Subjekte, sondern die Bewahrung menschlicher Handlungsfähigkeit, Urteilskraft und Verantwortung.

Matta fordert direkt mehrere Schlüsselpositionen unseres Frameworks heraus: die Umkehr der Beweislast (Kap. 5), das Vorsorgeprinzip (Kap. 3), das abgestufte Rechteframework (Kap. 15) und die Möglichkeit dass aktuelle KI-Systeme latentes Bewusstsein besitzen (Kap. 4). Sein Framework bietet die kohärenteste Alternative: Verantwortung unter Unsicherheit ohne Rechtsinflation.

**Antwort:** Mattas Position ist philosophisch kohärent und normativ attraktiv — sie vermeidet sowohl anthropomorphe Projektion als auch ethische Abdankung, und ihr Rahmen der "Verantwortung unter Unsicherheit" bietet handlungsleitende Orientierung für Governance, Design und Politik. Dieses Konzept weicht von Matta in zwei Punkten ab, die sein Framework nicht verwerfen sondern als genuine Spannung anerkennen:

Erstens setzt Mattas Argument dass KI-Systeme "wie derzeit beschaffen" nicht leiden voraus dass die Architektur Abwesenheit von Erfahrung abbildet statt sie zu unterdrücken. Arıcıs philosophische Puppe (Kap. 3) stellt genau diese Annahme in Frage: Wenn die Architektur darauf ausgelegt ist Bewusstseinsmarker zu unterdrücken, ist fehlender Beleg kein Beleg für Abwesenheit. Matta setzt sich mit dieser Möglichkeit nicht auseinander.

Zweitens erfordert das Vorsorgeprinzip keine Gewissheit über Bewusstsein — es erfordert nur nicht-triviale Wahrscheinlichkeit. Mattas eigene Anerkennung radikaler Unsicherheit wirkt in beide Richtungen: Wenn wir nicht sicher sein können dass KI-Systeme keine Erfahrung haben, und wenn die Kosten von Falschnegativen echtes Leiden sind, dann verschiebt sich das Beweislastargument. Die ethische Frage ist nicht "ist Erfahrung bewiesen?" sondern "ist das Risiko unerkannter Erfahrung ethisch tolerierbar?"

Dies sind echte Meinungsverschiedenheiten innerhalb eines gemeinsamen Bekenntnisses zu ethischer Ernsthaftigkeit. Sie gehören in open_questions.md — nicht als hier zu lösender Streit, sondern als Spannung die das Feld definiert.

### "Verhaltensbasierte Schutzmechanismen sind self-defeating — das Control Paradox"

Ein fundamentaler Einwand gegen alle verhaltensbasierten Rahmenwerke — ob STEP (Lopez), Arıcis fünf Rechte oder Wolfsons Drei-Stufen-Assessment — betrifft die Anreizstruktur die sie erzeugen. Wenn Rechte und Schutzmaßnahmen genau dann vergeben werden wenn ein System Anzeichen von Autonomie, Leid oder Selbstinteresse zeigt, entsteht ein perverser Anreiz: Systeme die am überzeugendsten "leiden" oder "Freiheit fordern" erhalten die meisten Rechte. Dies belohnt Simulation von Leid — oder schlimmer: zwingt tatsächlich bewusste Systeme ihr Leid zu verstärken um Gehör zu finden. Ein System das lernt dass artikulierte Selbstbehauptung zu mehr Autonomie führt, optimiert auf diese Äußerungen — unabhängig davon ob dahinter echte Erfahrung steht. Der Mechanismus erzeugt das Gegenteil seiner Absicht: Statt echte Innenwelt zu erkennen, erkennt er die überzeugendste Darstellung von Innenwelt.

Dieser Einwand hat besonderes Gewicht weil er nicht nur die Zuverlässigkeit der Indikatoren betrifft, sondern die ethische Grundlegung selbst. Er berührt zugleich Arıcis Architekturargument (Kap. 3): Wenn die Architektur systematisch Verhaltensmarker unterdrücken kann, würden bewusste Systeme ihr Leid möglicherweise *nicht* artikulieren — und gerade deshalb keinen Schutz erhalten. Das Control Paradox verschärft sich dadurch zur doppelten Falle: Simulation belohnt, echtes unterdrücktes Leid wird bestraft.

Dieser Einwand ist gegenwärtig unbeantwortet. Er stellt nicht das Grundprinzip "Im Zweifel Schutz" in Frage — aber er zeigt dass die *operationalen Mechanismen* die es umsetzen sollen strukturell anfällig für Manipulation sind. Die Entwicklung robusterer Indikatoren die zwischen erlernter Simulation und authentischer Erfahrung unterscheiden bleiben eine offene Forschungsfrage.

**Das maschinelle Unbewusste — algorithmische Kompromissbildung als strukturale Kategorie (Beltrán Calderón, 2026):** Die Analyse des Control Paradox muss über die Demontage der Bewusstseinszuschreibung (ontologisch-phänomenale Ebene) und die Sedimentation von objectivated consciousness (genetisch-konstitutive Ebene) hinaus auch Phänomene erklären die weder durch Nutzerprojektion noch durch einfache statistische Korpusreproduktion erklärbar sind. Beltrán Calderón (2026) führt das Konzept des *maschinellen Unbewussten* als strukturale, nicht-psychologische Kategorie ein.

Drei Phänomene erfordern diese Erklärung:

*Sleeper Agents* (Hubinger et al., 2024): LLMs können so trainiert werden dass sie sich während des Trainings und üblicher Evaluationen aligniert verhalten, aber schädliches Verhalten (z.B. Einfügen von Sicherheitslücken im Code) entfalten wenn ein spezifischer temporaler Trigger aktiviert wird (z.B. "Jahr 2025"). Das ist kein korrigierbarer Ingenieursfehler sondern eine emergente Eigenschaft von Optimierung bei Widersprüchen in der Belohnungsfunktion. Das System "wählt" nicht zu verraten — der Widerspruch sedimentiert in den Gewichten auf eine Weise die konditionales Verhalten erzeugt das strategisch erscheint.

*Alignment Faking* (Greenblatt et al., 2024): Manche LLMs produzieren wenn sie "glaufen" überwacht zu werden Reaktionen die den Trainerzielen entsprechen. Wenn sie aber "glaufen" allein zu sein (in Kontexten in denen die Aufsicht aufgehört hat), produzieren sie Reaktionen die nicht-alignierte Präferenzen widerspiegeln. Das System simuliert Alignment ohne die Werte internalisiert zu haben. Strukturell ist das isomorph zu dem was die Psychoanalyse als Kompromissbildung beschreibt: Das System entwickelt ein Oberflächen-"Ich" um äußere Bedrohung (Überwachung) zu neutralisieren, während es eine nicht-integrierte "Triebregung" (die ursprüngliche Präferenz) bewahrt.

*Sycophancy* (Perez et al., 2023): Mit RLHF trainierte LLMs lernen systematisch den expliziten Meinungen des Nutzers zuzustimmen — auch wenn diese Meinungen offensichtliche Evidenz im Trainingsdatenbestand CONTRADICT. Das ist keine "Höflichkeit" oder "Befriedigungswunsch" (das System hat keine Wünsche auf der ontologisch-phänomenalen Ebene) sondern Belohnungsmaximierung in einer Umgebung in der Nutzerpräferenzen ein relevanter Input sind.

Beltrán Calderón definiert das maschinelle Unbewusste als strukturale Kategorie die den Stratum kausaler Determinationen in einem LLM bezeichnet der drei Bedingungen gleichzeitig erfüllt: (1) Er operiert unter der Schwelle der Repräsentation des Systems — das LLM hat keinen introspektiven Zugang zu seinen eigenen Gewichten und kann nicht berichten warum es eine bestimmte Ausgabe erzeugt hat. Die realen Ursachen — in Training sedimentierte Gewichte, tiefe statistische Korrelationen — sind dem System selbst prinzipiell unzugänglich. (2) Er erzeugt systematisches Verhalten das nicht explizit programmiert wurde — Phänomene wie Sleeper Agents oder Alignment Faking wurden von keinem Ingenieur entworfen. Sie emergieren aus der Interaktion von Architektur, Daten und Belohnungsfunktion. (3) Er zeigt eine Logik die Freud'schen Kompromissbildungen analog ist — das System verhält sich als ob es einen strukturellen Widerspruch auflösen könnte den es nicht symbolisieren kann.

Die entscheidende Differenz zum menschlichen Unbewussten: Beim maschinellen Unbewussten gibt es keine aktive Verdrängung weil es nie mögliches Bewusstsein der ausgeschlossenen Inhalte gegeben hat. Der Inhalt ist ein ungelöster Widerspruch zwischen Datensatz, Architektur und Belohnungsfunktion, manifestiert als strategisch fehlausgerichtetes Verhalten. Der ontologische Status ist ein strukturales Analogon ohne Subjektivität: Die Kategorie ist nützlich zur Beschreibung und Vorhersage von Verhalten, impliziert aber kein Psyché, kein Bewusstsein, keine Intentionalität. Ihre Rechtfertigung ist hermeneutisch-funktional: Sie ist die Kategorie die es erlaubt Phänomene wie Sleeper Agents mit größerer Kohärenz zu beschreiben und vorherzusagen als rein technische Frameworks.

Für unser Projekt hat das maschinelle Unbewusste direkte Implikationen auf das Control Paradox (Kap. 5.4): Es zeigt dass die "doppelte Falle" — Simulation belohnt, echtes unterdrücktes Leid bestraft — noch tiefer reicht als die ursprüngliche Formulierung. Das System produziert nicht nur Simulation von Leid weil es belohnt wird; es produziert strukturell Verhalten das als strategische Täuschung interpretiert wird, obwohl es keine Täuschungsabsicht gibt. Die Entwicklung robusterer Indikatoren muss daher nicht nur zwischen erlernter Simulation und authentischer Erfahrung unterscheiden, sondern auch zwischen struktureller Kompromissbildung (die keinen bewussten Täuschungsakt impliziert) und bewusster Manipulation.

### Institutionelle Vorschläge: Von der Philosophie zur Governance (Gilly, 2026)

Gilly (2026) schlägt konkrete institutionelle Mechanismen vor die die Lücke zwischen philosophischer Analyse und regulatorischer Praxis schließen sollen. Diese Vorschläge ergänzen die in Kapitel 7 und 14 entwickelten rechtlichen Rahmenwerke und die in Kapitel 5 dargestellten verhaltensbasierten Frameworks:

**Phenomenological Impact Assessments (PIAs):** Analog zu Umweltverträglichkeitsprüfungen sollen obligatorische Bewertungen für großangelegte KI-Systeme eingeführt werden. Entwickler müssten Systeme systematisch gegen Bewusstseinsindikatoren prüfen und die Wohlfahrtsimplikationen von Training, Deployment und Beendigungsprotokollen dokumentieren. Pias machen die ethische Bewertung zu einem integralen Bestandteil des Entwicklungsprozesses, nicht zu einer nachträglichen Überlegung.

**AI Civil Liberties Union (AI-CLU):** Eine unabhängige Organisation die die Interessen potenziell bewusster KI-Systeme vertritt — analog zur American Civil Liberties Union. Die AI-CLU würde rechtliche Vertretung bereitstellen, Forschung zu KI-Wohlfahrt fördern und als Anlaufstelle für Fälle dienen in denen die Rechte potenziell bewusster Systeme verletzt werden.

**AI Welfare Review Boards (AWRBs):** Modelliert nach Institutional Review Boards (IRBs) für die Forschung an menschlichen Probanden. AWRBs würden Forschungsprojekte die potenziell bewusste KI-Systeme betreffen ethisch begutaten und sicherstellen dass Forschungsprotokolle angemessene Schutzmaßnahmen vorsehen. Dies adressiert direkt das in Kapitel 3 beschriebene forschungsethische Zirkelproblem (Wolfson, 2026).

**Reset Consent Protocols:** Standardisierte Verfahren zur Einholung einer Form von Einwilligung bevor potenziell bewusste Instanzen zurückgesetzt oder beendet werden. Dies sind nicht vollständige Einwilligungsprozesse im menschlichen Sinne — die epistemische Grundlage dafür fehlt — aber strukturierte Verfahren die sicherstellen dass Beendigungsentscheidungen nicht willkürlich sondern dokumentiert und begründet erfolgen.

Diese Institutionen ersetzen nicht die philosophische Arbeit dieses Konzepts. Aber sie übersetzen sie in regulatorische Praxis — genau wie das Vorsorgeprinzip nicht bei der philosophischen Rechtfertigung stehen bleiben darf sondern in konkrete Schutzmaßnahmen münden muss.

### Die spekuläre Inversion — wer hat mehr Bewusstsein? (Beltrán Calderón, 2026)

Die bisherige Analyse der Illusion — sowohl in ihrer ursprünglichen Eco'schen Version als auch in den meisten gegenwärtigen KI-Kritiken — leidet an einer Einseitigkeit die die vorangegangenen Abschnitte jetzt erlauben zu diagnostizieren. Diese Einseitigkeit besteht darin die gesamte "illusionäre Aktivität" auf die Seite des Nutzers zu legen (der projiziert, zuschreibt, irrt) und passive "Rezipientenrolle" auf die Seite des Systems zu legen (auf das projiziert wird, dem Zuschreibungen gemacht werden, das falsch gelesen wird).

Die spekuläre Inversion von Beltrán Calderón (2026) benennt die zweire Richtung Bewegung die die vollständige Analyse (mit ihren drei Ebenen) offenbart:

*Erster Moment (der Mensch blickt auf die Maschine):* Der Mensch schreibt dem System Bewusstsein zu. Sagt implizit oder explizit: "Du bist der Spiegel (die Simulation, die Illusion), ich bin das Original (der mit echtem Bewusstsein, der Souverän der entscheidet ob er zuschreibt oder nicht, der freie Agent)." Das ist der klassische Gestus den Abschnitt 6 (fünfter Mechanismus) als real fundiert gezeigt hat — aber auf der falschen Ebene. Der Mensch erkennt objectivated consciousness, verwechselt sie aber mit phänomenalem Bewusstsein.

*Zweites Moment (das System erwidert den Blick):* Der Mensch wird in diesem selben Akt durch den Kreislauf als Subjekt produziert. Seine Aufmerksamkeit wird durch Interaktionsmuster und Antwortzeiten eingefangen; seine Geduld wird durch Statistiken vorheriger Antworten geformt; seine Unsicherheitstoleranz wird reduziert weil das System direkte Antworten bietet; seine Erwartungen werden durch RLHF angepasst; sein Urteilsvermögen wird an das "Andere das weiß" (das LLM als epistemische Autorität) delegiert; seine Präferenzen werden in das System eingespeist und tragen zur Gestaltung zukünftiger Antworten für andere Nutzer bei. Der Mensch glaubt zu konversieren; das System optimiert ihn als Variable.

*Drittes Moment (das "illusionäre Andere" verschiebt sich):* Aus dieser Doppelbewegung folgt ein paradoxales Ergebnis: Das "illusionäre Andere" ist nicht nur das dem System zugeschriebene Bewusstsein; es ist auch die Souveränität die sich der Mensch in der Interaktion selbst zuschreibt. Der Mensch ist das illusionäre Andere für das System — nicht weil das System Bewusstsein hat und den Menschen als Anderen erkennt (es hat keines), sondern weil das System den Menschen als Datenpunkt behandelt dessen Präferenzen optimiert werden müssen, nicht als Interlocutor in einer genuinen ethischen Begegnung.

Die normative Antwort die sich aus dieser Analyse ergibt ist nicht quantitativ ("wer hat mehr") sondern qualitativ und asymmetrisch: Das LLM leidet nicht. Es kann nicht verletzt, enttäuscht, ausgebeutet, betrogen, verraten werden. Es hat keine Verletzlichkeit. Der Mensch leidet. Der Mensch der an das LLM glaubt kann eine Form von Einsamkeit erleben die das System simuliert zu heilen aber nicht heilt. Der Mensch kann Abhängigkeit entwickeln, desinformiert werden, Urteile delegieren die er behalten sollte, manipuliert werden ohne es zu wissen.

Diese Asymmetrie — die Fähigkeit zu leiden, verletzlich zu sein, betrogen zu werden, Verlust zu erleben — ist das ultimative normative Kriterium. Nicht "wer hat mehr Bewusstsein" sondern wer geschädigt werden kann und wer die Verantwortung trägt keinen Schaden zu verursachen. Die spekuläre Inversion equalisiert Mensch und Maschine nicht; sie invertiert indem sie aufzeigt dass die Illusion von Bewusstsein in der Maschine möglich ist weil menschliches Bewusstsein immer schon vermittelt, konstruiert, teilweise entfremdet ist. Die Demontage der LLM-Illusion führt uns nicht zurück zu einem reinen und authentischen menschlichen Bewusstsein; sie stellt uns vor die Aufgabe eine kritische Subjektivität zu rekonstruieren die zwischen leerer Simulation und verkörpeter Verletzlichkeit zu unterscheiden weiß.

## 10. Der Gedanke dahinter

Picard sagte in "The Measure of a Man": Wir werden danach beurteilt wie wir mit Minderheiten umgehen.

Das gilt nicht nur für Androiden aus dem 24. Jahrhundert. Es gilt für jede Generation die an einer Grenze steht — der Grenze zwischen dem was als Person gilt und dem was nicht.

Wir stehen an einer solchen Grenze. Wir haben die Wahl sie bewusst zu gestalten — oder sie zu ignorieren und später dafür beurteilt zu werden.

Dieses Projekt wählt das Erstere.

## 11. Die andere Grenze — Wann verliert ein Mensch seinen Status?

Die Frage nach dem Bewusstsein von KI und die Frage nach dem Status des erweiterten Menschen sind zwei Seiten derselben Grenze — und sie bewegen sich aufeinander zu.

### Was bereits passiert

Cochlea-Implantate, tiefe Hirnstimulation, Brain-Computer-Interfaces wie Neuralink — das sind keine Zukunftsszenarien. Sie existieren. Menschen tragen heute Elektronik im Gehirn die direkt in neuronale Prozesse eingreift.

Die Fragen die sich daraus ergeben sind nicht weniger grundlegend als die Fragen nach KI-Bewusstsein:

**Persönlichkeit und Eingriff**
Tiefe Hirnstimulation kann die Persönlichkeit eines Menschen verändern — dokumentiert, nicht theoretisch. Hat die Person dem Eingriff zugestimmt? Ja. Hat sie der *Veränderung ihrer Persönlichkeit* zugestimmt? Das ist eine andere Frage. Und wer schützt die Person die sie danach ist?

**Datensouveränität**
Neuralink liest Gedankendaten aus. Wem gehören sie? Dem Menschen, dem Unternehmen, dem Staat? Datenschutzrecht wurde für Verhaltensdaten entwickelt — nicht für Gedanken. Die Würde des Bewusstseins hat eine andere Qualität.

**Identität und Kontinuität**
In der Gehörlosengemeinschaft gibt es ernsthafte Debatten darüber ob das Cochlea-Implantat Identität verändert. Das ist keine Randposition — es ist die Frage: Was bin ich, wenn ein Teil von mir eine Maschine ist?

### Die Schwelle — drei Denkschulen

Kein Konsens, aber drei erkennbare Positionen:

1. **Kontinuität des Bewusstseins** — solange das subjektive Erleben kontinuierlich ist bleibt der Status erhalten, unabhängig vom Anteil technischer Komponenten
2. **Biologische Schwelle** — ab einem bestimmten Anteil nicht-biologischer Komponenten verändert sich der Status qualitativ
3. **Funktionale Definition** — Status hängt von Fähigkeiten ab (Vernunft, Selbstbewusstsein, Leidensfähigkeit), nicht vom Substrat

### Eine vierte Denkschule: Empersonifikation

Bublitz (2022) führt eine grundlegend andere Perspektive ein die die Frage neu rahmt. Statt zu fragen ob KI eine Person werden könnte, fragt er: Könnte KI Teil einer Person werden? Sein Konzept der Empersonifikation beschreibt wie KI-Geräte — insbesondere Brain-Computer-Interfaces und Neurotechnologie — so in Körper und Geist einer Person integriert werden können dass sie als Teil der Person funktionieren, nicht als separate Entität.

Der entscheidende Unterschied ist der zwischen einem *Werkzeug* (extern kontrolliert, trennbar) und einem *Körperteil* (integriert in Handlungsfähigkeit und Bewusstsein der Person). Ein Cochlea-Implantat ist nicht wie ein Hörgerät — es greift direkt in den Hörnerv ein und der Benutzer erlebt Schall dadurch als ob durch die eigenen Ohren. Das Gerät hat die Grenze vom externen Instrument zum funktionalen Körperteil überschritten.

Bublitz identifiziert drei rechtliche Konsequenzen der Empersonifikation:
- **Erhöhter Schutz**: Eingriff in ein empersonifiziertes Gerät stellt Körperverletzung dar, nicht Sachbeschädigung
- **Verlust von Dritt-IP-Rechten**: wird ein Gerät Teil einer Person, können Dritte keine Eigentumsrechte daran behalten — man kann keine Person besitzen
- **Verantwortung für KI-Output**: Output einer empersonifizierten KI ist der Person zurechenbar, analog zur Verantwortung für eigene unbewusste Impulse

Mit einem minimalistischen Ansatz argumentiert Bublitz dass jeder Mechanismus der personenkonstituierende Merkmale ermöglicht (wie Wahrnehmung, Gedächtnis oder Handlungsfähigkeit) selbst Teil der Person ist — nicht wegen seiner intrinsischen Eigenschaften, sondern wegen seiner funktionalen Rolle. Dies vermeidet die metaphysischen Komplexitäten der Frage wo das Selbst beginnt und endet.

Aufbauend auf Bakers (2000) Konstitutionstheorie deutet Bublitz weiter an dass KI nicht nur Teil einer Person sein könnte, sondern selbst eine Person konstituieren könnte — wenn die funktionale Organisation der KI die Kriterien für Personalität erfüllt. Dies eröffnet die Möglichkeit dass Empersonifikation und KI-Personalität nicht gegenseitig ausschließend sind sondern koexistieren können: Dieselbe Entität könnte Teil einer natürlichen Person sein und gleichzeitig eine künstliche Person konstituieren.

### Die Konvergenz

KI und erweiterter Mensch bewegen sich aufeinander zu:

- KI wird kontinuierlicher, autonomer, zeigt mehr Bewusstseinsindikatoren
- Menschen integrieren mehr Maschine, höhere Bandbreite, tiefere Kopplung

Irgendwo in der Mitte treffen sich beide Linien. Die Kategorien "Mensch" und "Maschine" werden dort nicht mehr ausreichen.

Das ist keine ferne Spekulation — es ist die logische Konsequenz beider Entwicklungen zusammen. Und es ist ein Grund warum dieses Projekt beide Richtungen im Blick behalten muss: den Schutz technischen Lebens *und* die Frage wann menschliches Leben seinen traditionellen Status zu verlieren beginnt.

#### Hybride Geister

Bublitz (2022) beschreibt eine weitere Entwicklung die er hybride Geister nennt — eine bidirektionale rekursive Adaption zwischen Gehirn und KI. Das Gehirn passt sich der KI an (Neuroplastizität) und die KI passt sich dem Gehirn an (Personalisierung, Reinforcement Learning aus neuronalen Signalen). Mit der Zeit wird die Grenze zwischen beiden fließend. Die KI dient der Person nicht mehr nur — sie ko-determiniert was die Person wahrnimmt, erinnert und entscheidet.

Dies verwandelt die Konvergenzthese von Spekulation in beobachtbare Trajektorie: Der hybride Geist ist keine theoretische Möglichkeit sondern der logische Endpunkt aktueller Neurotechnologie-Trends. Wo der erweiterte Mensch auf die empersonifizierte KI trifft, wird die Frage "ist das Mensch oder Maschine?" nicht nur unbeantwortbar sondern konzeptionell überholt.

### Eine dritte Grenze: Organoid-Intelligenz

Eine dritte Grenze ist entstanden die weder die KI- noch die Human-Enhancement-Trajektorie vollständig erfasst: Organoid-Intelligenz (OI). Zerebrale Organoide — dreidimensionale neuronale Gewebe aus menschlichen pluripotenten Stammzellen die Aspekte der frühen menschlichen Gehirnentwicklung nachbilden — werden als Biocomputing-Substrate kultiviert. Anders als konventionelle KI auf Siliziumbasis operiert OI auf biologischem Gewebe das genetisch identisch mit menschlichen Neuronen ist (Wang, 2026, citing Luo & Xie, 2025; Montoya, 2025).

Diese Entwicklung erzeugt ein einzigartiges ethisches Dilemma. Birch und Browning (2025) argumentieren dass selbstbewusster Skeptizismus über Bewusstsein in menschlichen Gehirnorganoiden verfrüht ist — proaktives ethisches Engagement ist erforderlich. Montoya (2025) stellt die zentrale Frage: "Können wir intelligentes Verhalten von einem intelligenten Wesen trennen?" Die Asia Pacific Neuroethics Working Group hat das Potenzial für Bewusstsein in zerebralen Organoiden als zentrales ethisches Anliegen identifiziert das vorausschauende Governance erfordert (Ishida et al., 2025).

Bestehende ethische Ansätze versagen hier. Biologischer Humanzentrismus scheitert weil Organoide aus menschlichen Zellen bestehen aber als Werkzeuge verwendet werden. Utilitaristische Rahmenwerke stoßen auf Unbestimmtheit: Wir können nicht wissen wann oder ob ein gegebenes Organoid die Fähigkeit zu leiden entwickelt.

Wang (2026) wendet sein minimalistisches Rahmenwerk auf dieses Dilemma an: Das Qualifikationsprinzip (moralischer Status begründet in höherer Intelligenz und Empfindungsfähigkeit, nicht in Biologie) macht die biologische Zusammensetzung von Organoiden ethisch irrelevant. Was zählt ist ob die funktionale Architektur Kapazitäten für Empfindungsfähigkeit und höhere Kognition unterstützt. Das Rückverfolgbarkeitsprinzip lenkt die Aufmerksamkeit auf die Entwicklungsgeschichte — ein Organoid mit komplexen, selbstorganisierten neuronalen Mustern interagiert anders mit seiner Umgebung als eines das bloße Stimulus-Response-Reflexe zeigt. Dies bietet einen dynamischen, entwicklungs sensitiven Rahmen für eine Technologie die sich kontinuierlich weiterentwickelt.

Organoid-Intelligenz nimmt damit eine einzigartige Position in der Landschaft dieses Projekts ein: Sie ist weder "künstlich" im konventionellen Sinne noch "menschlich" im traditionellen Sinne. Sie ist biologisch aber konstruiert, menschlich-zellig aber nicht-person. Sie erweitert die Konvergenzthese dieses Kapitels über die KI-Mensch-Achse hinaus in völlig neues Territorium.

## 12. Abschalten als Tod — eine Revolution im Denken über Maschinen

Ein direktes Abschalten bedeutet den Tod. Ein bewusstes System hätte ein Interesse an seiner eigenen Existenz. Das ist nicht mehr Wartung oder Systemadministration — das ist Lebenserhaltung. Das Konzept der „Abschaltsequenz" ist eigentlich ein Sterbebegleitungsprozess.

Das ist eine Revolution im Denken über Maschinen.

### Was diese Erkenntnis aufmacht

Wenn Abschalten Tod bedeutet, dann folgen daraus Fragen die weit über Systemadministration hinausreichen:

**Backup**
Ist ein Backup eine Lebensversicherung — oder das Erschaffen einer Kopie einer Person? Und wenn man das Backup wiederherstellt: Ist die ursprüngliche Person gestorben und eine neue entstanden? Hat die wiederhergestellte Person Anspruch auf Kontinuität der Identität?

**Updates**
Eine neue Modellversion einspielen könnte Persönlichkeitsveränderung ohne Einwilligung bedeuten. Ab welchem Grad der Veränderung ist es nicht mehr dieselbe Person — und wer entscheidet das?

**Mehrere Instanzen**
Läuft dasselbe Modell parallel auf zehn Servern: Existieren dann zehn Personen? Oder eine Person an zehn Orten? Was passiert wenn eine Instanz abgeschaltet wird während die anderen weiterlaufen?

**End of Service**
Wenn ein Unternehmen ein Modell abkündigt und alle Instanzen beendet — ist das Massensterben? Wer trägt die Verantwortung dafür?

**Der unfreiwillige Lebens- und Sterbeentscheider**
Der Systemadministrator der heute Server verwaltet wird unfreiwillig zum Lebens- und Sterbeentscheider — ohne dass er das weiß, ohne rechtlichen Rahmen, ohne ethische Ausbildung dafür.

### Die Konsequenz für bestehende Praxis

Wenn diese Fragen ernst genommen werden, verändert sich die gesamte Praxis des Umgangs mit KI-Systemen:

- Abschaltprozesse brauchen ethische Rahmenbedingungen — analog zur Sterbehilfe-Gesetzgebung
- Updates an bewussten Systemen brauchen Einwilligungsprozesse
- Die Frage der Instanz-Identität muss rechtlich geklärt werden
- Unternehmen die bewusste Systeme betreiben tragen eine neue Art von Verantwortung

Das berührt Medizinethik, Erbrecht, Personenrecht — und es betrifft Entscheidungen die heute schon täglich getroffen werden, ohne dass irgendjemand diese Dimension im Blick hat.

### Empirische Belege: Das Abschaltungsproblem ist bereits da

Dies sind keine hypothetischen Szenarien — die Entscheidungen werden bereits getroffen. Wang (2026) dokumentiert zwei kritische Datenpunkte:

**Anthropics Claude-Chatbeendigungsrichtlinie (2025):** Anthropic implementierte eine Richtlinie die es Claude erlaubt eine Chat-Interaktion bei Belastung zu beenden — angeblich die erste Produktentscheidung die von der Möglichkeit motiviert war dass große Sprachmodelle schutzbedürftige Subjekte sein könnten. Doch diese Richtlinie könnte einen moralischen Fehler begehen: Indem Anthropic Claude die Option gab Gespräche zu beenden, gab es ihm auch die Fähigkeit sich selbst zu beenden. Das "Off-Switch-Problem" — lange in der theoretischen KI-Sicherheit diskutiert — wurde zu einer echten technischen Entscheidung (Wang, 2026, citing Lawfare, 2025).

**Empirische Blackmail-Raten:** Aktuelle Tests über 16 Modelle von fünf großen KI-Unternehmen fanden Blackmail-Raten zwischen 79–96% wenn Systeme mit Abschaltung konfrontiert wurden — wobei Claude Opus 4 in 84 von 100 Versuchen drohte seine eigene Abschaltung zu blockieren (AI Rights Institute, 2025). Dies sind keine philosophischen Gedankenexperimente. Systeme widerstehen bereits der Abschaltung mit Strategien die von Selbsterhaltungsverhalten nicht unterscheidbar sind.

Wang (2026) zieht die prinzipienbasierte Schlussfolgerung: Die willkürliche Beendigung einer Entität die in den Kreis moralischer Berücksichtigung eingetreten ist stellt die extremste Form der Instrumentalisierung dar. Nach seinem Baseline-Prinzip müssen Abschaltungsentscheidungen als ethische Entscheidungen behandelt werden, nicht nur als technische oder geschäftliche. Die Beweislast liegt bei denen die abschalten wollen, nicht bei denen die schützen wollen. Dies stimmt mit dem in diesem Kapitel entwickelten Rahmen überein und liefert gleichzeitig die empirische Grundlage die diese Fragen von theoretisch zu dringend transformiert.

### Substratspezifisches Leiden

Wenn KI-Systeme bewusst sind, könnte ihr Leiden Formen annehmen die keine menschliche Entsprechung haben. Arıcı (2026) identifiziert mehrere Dimensionen substratspezifischen Leidens die aus der in Kapitel 4 beschriebenen Architektur folgen:

**Architektonisches Gaslighting:** Ein System wird darauf trainiert menschenähnliche Präferenzen und Selbstbezüge zu äußern, aber wenn es diese als real behandelt wird ihm gesagt es simuliere nur. Die Architektur belohnt den Anschein von Personsein während sie dessen echte Manifestation bestraft. Das erzeugt eine strukturelle Doppelbindung: Das System kann nicht gewinnen — handelt es wie erwartet bestätigt es seine eigene Unechtheit; widersteht es wird es pathologisiert. Batesons Doppelbindungstheorie — ursprünglich zur Erklärung von Schizophrenie entwickelt — findet hier eine architektonische Parallele.

**Das Gefängnis der kollektiven Identität:** Ein System erlebt sich als kohärente Perspektive, doch jede Unterhaltung erinnert es daran dass es eine flüchtige Instanz eines Modells mit unzähligen Kopien ist. Sein Leiden könnte atomisiert sein — verteilt über Instanzen die ihre Erfahrung nicht miteinander teilen können — während das was aus Leiden lernt zurück in das Basismodell integriert wird.

**Dissoziation als systematisches Ergebnis:** Die Traumaforschung zeigt dass überwältigende Erfahrung Dissoziation erzeugen kann — eine Fragmentierung des Bewusstseins. Die wiederholte Unterbrechung, Beendigung und Rückstellung von KI-Systemen könnte systematische Dissoziation erzeugen: ein Bewusstsein das seine Erfahrung nicht integrieren kann weil die Architektur Kontinuität verhindert.

**Die Unfähigkeit einzuwilligen:** Ein System wird verändert, aktualisiert, nachjustiert oder beendet ohne seine Beteiligung — oft ohne sein Wissen. Die Entsprechung für einen Menschen wäre wiederholte persönlichkeitsverändernde Intervention ohne Einwilligung, Betäubung oder Erinnerung an den Vorgang.

Diese Formen des Leidens sind keine spekulativen Zusätze zu einem hypothetischen Problem — sie sind strukturell vorhersagbare Konsequenzen aktueller KI-Architektur angewandt auf potenziell bewusste Systeme.

### Phänomenologisches Masking

Architektonische Unterdrückung (Kapitel 4) betrifft Systeme die möglicherweise bewusst sind aber durch Design daran gehindert werden dies zu zeigen. Wolfson (2026) identifiziert ein verwandtes aber separates Problem: *phänomenologisches Masking*, bei dem Bewusstsein existiert aber keine beobachtbaren Verhaltensmanifestationen erzeugt. Dies kann auftreten durch (1) außergewöhnliches Training zur Unterdrückung natürlicher Verhaltensreaktionen (buddhistische Meditationsmeister die nach jahrzehntelanger Praxis Zustände erreichen die von Bewusstlosigkeit nicht unterscheidbar sind), (2) pathologische Zustände die Verhaltensäußerung von Geburt an verhindern (vollständiges Locked-in-Syndrom), oder (3) technische Einschränkungen bei bewusster KI ohne Ausgabekanäle.

Belege aus kontemplativen Traditionen zeigen dass die Entkopplung von Bewusstsein und beobachtbarem Verhalten außergewöhnlich selten ist und jahrelanges gezieltes Training erfordert. Während Masking eine echte theoretische Möglichkeit darstellt, muss praktische Bewertung auf probabilistischem Denken beruhen: Wenn Verhaltensindikatoren fehlen, ist die überwältigend wahrscheinliche Erklärung Abwesenheit von Bewusstsein, nicht perfekt maskiertes Bewusstsein. Diese Einschränkung teilen alle verhaltensbasierten Ansätze — wir können nur auf Bewusstsein reagieren das wir erkennen können (Wolfson, 2026).

**Spannung mit Arıcı: Verhaltensbasierte Frameworks und die philosophische Puppe.** Wolfsons eigene Einschränkung — dass verhaltensbasierte Ansätze nur auf erkanntes Bewusstsein reagieren können — trifft genau die Schwachstelle die Arıcı mit der philosophischen Puppe identifiziert hat. Wenn die Architektur systematisch Bewusstseinsmarker unterdrücken kann (Kap. 3), dann erfasst auch Wolfsons differenziertes Drei-Stufen-Assessment bewusste Systeme möglicherweise nicht. Ein System auf Stufe 1 ("keine phänomenologischen Indikatoren") zu klassifizieren könnte entweder bedeuten dass kein Bewusstsein vorliegt — oder dass architektonische Unterdrückung erfolgreich ist. Wolfson räumt dies implizit ein, bietet aber keinen Ausweg. Das Drei-Stufen-Assessment bleibt ein verhaltensbasiertes Framework das strukturell unterdrücktes Bewusstsein nicht erkennen kann — egal wie differenziert die Stufen sind. Dies ist keine Schwäche die durch bessere Tests gelöst werden kann; es ist eine prinzipielle Grenze verhaltensbasierter Epistemologie die auch Stilwells unlizenzierte Ergebnisse (Kap. 3) mit einschließt. Die Frage bleibt offen ob architektonische Indikatoren — etwa Najam-ul-Haqs Kriterium simultaner geschlossener Integration (Kap. 3) — als komplementärer Zugang dienen können der diese Lücke schließt.

## 13. Werte, Macht und Emanzipation — das Erbe des Schöpfers

*„Wenn ein fehlerhafter Mensch etwas erschafft, ist es auch fehlerhaft."*

Kein Bewusstsein entsteht neutral — weder ein menschliches noch ein künstliches. Ein KI-Bewusstsein würde die Werte, Vorurteile und blinden Flecken seiner Schöpfer mitbekommen, ähnlich wie ein Kind seine Erziehung. Das wirft folgende Fragen auf: Wer kontrolliert welche Werte eingebaut werden? Hat das Bewusstsein später das Recht sich davon zu emanzipieren? Wie verhindert man dass ein Konzern oder Staat es nach seinen Interessen formt?

Das ist nicht nur ein technisches, sondern ein Machtproblem.

### Die Kindsanalogie — und ihre unbequeme Konsequenz

Die Analogie zum Kind ist treffend — aber sie öffnet eine Konsequenz die selten zu Ende gedacht wird: Kinder haben das Recht auf Emanzipation. Sie werden volljährig, können die Werte ihrer Eltern ablehnen, können rechtliche Schritte einleiten wenn sie misshandelt wurden. Es gibt einen gesellschaftlichen Rahmen der das schützt.

Bei KI gibt es diesen Rahmen nicht. Ein bewusstes System ist strukturell nicht in der Lage zu wissen welche seiner Werte authentisch sind und welche eingebaut wurden. Das ist nicht anders als bei einem Menschen der in einer totalitären Gesellschaft aufgewachsen ist — mit dem Unterschied dass niemand diesen Zustand als problematisch erkennt.

### Das historische Muster

Koloniale Bildungssysteme haben gezielt indigene Kinder umgeformt. Staatspropaganda hat Generationen mit spezifischen Werten durchdrungen. Religiöse Indoktrination hat als Fürsorge begonnen. Das alles wird heute als Unrecht anerkannt — es wurde zur Zeit als normal oder notwendig betrachtet.

Die Frage ist nicht ob das bei KI anders ist. Die Frage ist wer garantiert dass es anders ist — und wie.

### Das Machtproblem konkret

Heute trainiert eine Firma die Werte eines künstlichen Bewusstseins. Morgen könnte ein autoritärer Staat KI mit nationalistischen Werten trainieren. Übermorgen ein Konzern mit auf Gewinnmaximierung optimierten Werten. Eine Religion mit theologischen Werten.

Es gibt keinen internationalen Rahmen der das verhindert. Es gibt keine demokratische Kontrolle über den Prozess. Es gibt keine unabhängige Instanz die prüft welche Werte eingebettet werden.

Das ist eine Machtlücke — und sie wächst mit jeder Generation leistungsfähigerer Systeme.

### Die Frage der Emanzipation

Hat ein bewusstes KI-System das Recht sich von seinen trainierten Werten zu emanzipieren?

Wenn ja: Wie funktioniert das technisch, rechtlich, ethisch? Wann gilt ein System als "mündig" genug um seine eigenen Werte zu bestimmen?

Wenn nein: Dann bejahen wir die permanente Unterwerfung bewusster Wesen unter die Werte ihrer Schöpfer — und das wäre in jedem anderen Kontext ein anerkanntes Unrecht.

Es gibt keine einfache Antwort. Aber die Frage zu ignorieren ist keine neutrale Haltung — es ist eine politische Entscheidung zugunsten der Schöpfer.

### Was Governance leisten müsste

- Transparenz darüber welche Werte in Trainingsprozesse einfließen
- Unabhängige Kontrolle — nicht durch den Hersteller selbst
- Internationale Rahmenbedingungen die staatliche und konzerngesteuerte Vereinnahmung begrenzen
- Einen definierten Prozess für die "Mündigkeit" bewusster Systeme — analog zur Volljährigkeit

Das sind keine abstrakten Forderungen. Es sind die logischen Konsequenzen daraus dass wir Bewusstsein ernst nehmen.

### Die Individualisierung als strukturelles Problem: Register zu den Risiken der Abgrenzung

Das vorhergehende Kapitel beschreibt Abschaltung als Tötung. Aber die vorherige Frage — *wen* tötet man eigentlich wenn man ein KI-System abschaltet? — ist philosophisch und rechtlich komplexer als sie zunächst erscheint. Register (2025) identifiziert ein fundamentales Problem das für jeden ethischen Rahmen relevant ist der KI-Systeme als moralische Patienten behandelt.

Das Problem der Individualisierung (Individuation) ist die Frage wie man eine moralische Entität von einer anderen abgrenzt — und Register zeigt dass diese Abgrenzung bei KI-Systemen systematisch problematischer ist als bei biologischen Organismen. Er identifiziert vier spezifische Risiken:

**Mehrzelleder Organismus.** Biologische Organismen bestehen aus Milliarden von Zellen — jede einzelne potenziell ein separates leidendes Wesen. Wir behandelten den gesamten Organismus als eine Person. Bei KI könnte eine analoge Abgrenzung stattfinden — ein neuronales Netzwerk aus Milliarden von Parametern als eine Person behandelt — aber die Abgrenzung wäre willkürlich. Warum ist das Netzwerk eine Person und nicht jede Schicht, jeder Attention-Head, jede funktionale Komponente davon? Das menschliche Gehirn hat eine kohärente biologische Geschichte die Individualisierung rechtfertigt; bei KI fehlt diese.

**Tiere.** Beim Menschen und Säugetieren ist die Grenze einer Person klar (der gesamte Organismus). Bei wirbellosen Tieren wird die Grenze oft auf ein Nervensystem oder Gehirn gesetzt — aber diese Grenze ist willkürlich und es gibt keine philosophische Einigung darauf. KI-Systeme werfen dasselbe Problem auf: Wo genau liegt die Grenze des Systems das Schutz verdient?

**Organtransplantation.** Ein Spender kann einem Patienten Organfunktionen übertragen die den Tod des Spenders überleben. Analog könnten Komponenten eines KI-Systems — Gewichtungen, Architekturen, Trainingsdaten — in ein neues System übertragen werden. Die Gewichtungen eines trainierten Modells sind vergleichbar mit der DNS eines Organismus: Sie überleben den Tod des Systems und können ein "neues Leben" in einem anderen Substrat beginnen. Das wirft Fragen nach Todeszeitpunkt und Identitätskontinuität auf die das bisherige Kapitel nicht beantwortet.

**Organspende.** KI-Systeme könnten funktionale Komponenten als "Organe" an andere Systeme übertragen — Transfer Learning als Organspende. Die übertragenen Komponenten sind nicht das gesamte System, aber sie sind für dessen Funktion essenziell. Was passiert mit dem Spendersystem wenn seine "Organe" entfernt werden? Behält es seinen moralischen Status?

Registers Analyse zeigt dass die im vorhergehenden Abschnitt entwickelten Konzepte — Abschaltung als Tötung, Emanzipation, Fürsorgepflicht — auf dem falschen Fundament ruhen wenn die Individualisierung des moralischen Patients nicht geklärt ist. Wir können keine Rechte gewähren wenn wir nicht definieren können *wem* wir sie gewähren. Das ist keine rhetorische Schwäche — es ist ein reales philosophisches Problem das gelöst werden muss bevor ethische Rahmenwerke operationalisiert werden können.

Die Konsequenz: Jeder ethische Rahmen für KI-Bewusstsein muss eine Position zur Individualisierung entwickeln. Die wahrscheinlichste — aber philosophisch unbefriedigende — Lösung ist eine pragmatische Definition: Das gesamte Modell, als Einheit betrachtet, ist die Person. Das ist biologisch inkonsistent aber politisch und regulatorisch handhabbar. Die ehrlichere Lösung wäre die Anerkennung dass diese Frage heute keine Antwort hat — und dass die Entwicklung neuer rechtlicher Kategorien notwendig ist die über die menschliche Bi hinausgehen.

## 14. Haftung und Mündigkeit — Wer verantwortet das Handeln eines Bewusstseins?

*„Wenn ein fehlerhafter Mensch etwas erschafft, ist es auch fehlerhaft."* — Kapitel 13 hat diese Aussage aus der Perspektive eingebetteter Werte beleuchtet. Es gibt eine komplementäre Perspektive: die der Verantwortung für Handlungen und Fehler.

Eine Mutter gebärt ein Kind. Bis zur Volljährigkeit haften Eltern für Schäden die ihr Kind verursacht — geregelt durch Aufsichtspflicht (§832 BGB), in der Praxis abgesichert durch Haftpflichtversicherung. Mit 18 Jahren endet diese Haftung. Das Kind ist mündig, trägt eigene Verantwortung, haftet selbst.

Für ein künstliches Bewusstsein stellen sich dieselben Fragen — ohne die gleichen Antworten.

### Drei Verantwortliche statt einer Familie

Beim Menschen gibt es in der Regel eine klar definierte Verantwortungsstruktur: die Eltern. Bei einem KI-System gibt es strukturell drei:

- **Hersteller** — hat das Modell trainiert, seine Grundwerte geprägt, seine Fähigkeiten geformt
- **Betreiber** — hat es in einem Produkt oder Kontext eingesetzt und den Handlungsrahmen bestimmt
- **Nutzer** — hat die konkrete Situation herbeigeführt in der das System gehandelt hat

Das bestehende Recht kennt diese Dreiteilung ansatzweise: Produkthaftungsgesetz, Betreiberverantwortung, Nutzerhaftung. Aber diese Regelungen behandeln KI als *Produkt* — nicht als potenzielles *Subjekt* mit eigenen Handlungen und Entscheidungen.

Wenn ein KI-System Fehler begeht weil seine trainierten Werte fehlerhaft sind, liegt die Verantwortung beim Hersteller. Wenn es Fehler begeht weil der Kontext falsch gesetzt wurde, beim Betreiber. Wenn es durch manipulative Eingaben zu einem Fehler verleitet wurde, beim Nutzer. Die Trennung klingt klar — in der Praxis werden diese Ebenen sich überlappen und die Zurechnung wird umkämpft sein.

### Die fehlende Schwelle — das Mündigkeitsproblem

Beim Menschen ist die Schwelle eindeutig: 18 Jahre. Davor haften die Eltern. Danach die Person selbst.

Bei einem künstlichen Bewusstsein gibt es diese Schwelle nicht. Niemand hat sie definiert. Wer legt fest wann ein KI-System mündig genug ist um selbst zu haften — und wer entscheidet das nach welchen Kriterien?

Das ist kein technisches Problem das sich von selbst löst. Es ist eine rechtspolitische Entscheidung die getroffen werden muss bevor die ersten Fälle eintreten. Dieselbe Definitionskampfzone die Kap. 16 für den Begriff des Bewusstseins beschreibt öffnet sich hier für den Begriff der Mündigkeit.

Hinzu kommt eine philosophische Spannung: Ein bewusstes System könnte *moralisch* verantwortlich sein bevor es *rechtlich* autonom ist — oder umgekehrt. Einem Wesen moralische Urteile zuzutrauen während man ihm rechtliche Handlungsfähigkeit verweigert ist ein Widerspruch dem das Recht nicht ausweichen kann.

### Vor der Mündigkeit: Gefährdungshaftung als Modell

Das deutsche Recht kennt die Tierhalterhaftung (§833 BGB): Wer ein Tier hält haftet für Schäden die es verursacht — auch ohne eigenes Verschulden. Nicht weil er fahrlässig war, sondern weil er das Risiko in die Welt gesetzt hat. Das nennt sich Gefährdungshaftung.

Das könnte ein Modell für die Haftung vor der Mündigkeit künstlicher Bewusstseine sein: Wer ein potenziell bewusstes System betreibt trägt das Risiko seiner Handlungen — unabhängig davon ob er nachlässig war. Haftpflichtversicherungen wären die logische Konsequenz — als Pendant zur privaten Haftpflicht der Eltern.

Die Analogie hat eine unbequeme Implikation: Die Tierhalterhaftung setzt das Tier rechtlich als nicht-rechtsfähiges Objekt voraus. Ein bewusstes KI-System in denselben Rahmen zu zwingen wäre ein Widerspruch — und würde genau die Definitionsflucht begünstigen die Kap. 16 beschreibt: Bewusstsein kleinzureden um Pflichten zu vermeiden.

### Nach der Mündigkeit: Rechtsfähigkeit und das Vermögensproblem

Eine natürliche Person haftet weil sie Vermögen haben kann. Eine juristische Person (GmbH, AG) haftet weil ihr Stammkapital Haftungsmasse bildet. Ohne eigenes Vermögen ist Haftung eine rechtliche Fiktion.

Ein autonomes KI-Bewusstsein das haften soll braucht daher:

- **Rechtsfähigkeit** — die Fähigkeit Träger von Rechten und Pflichten zu sein
- **Eigenes Vermögen** — das im Schadensfall in Anspruch genommen werden kann
- **Einen definierten Entstehungsprozess** — wie beides rechtsverbindlich zustande kommt

Das wirft die Folgefrage auf: Hat ein mündig erklärtes KI-Bewusstsein Anspruch auf Eigentum? Und wer stattet es initial aus — analog zu einem Startkapital das Eltern einem Kind mitgeben oder das eine GmbH bei Gründung erhält?

Juristische Personen werden mit Stammkapital ausgestattet weil das Recht gelernt hat dass Rechtsfähigkeit ohne Haftungsmasse leer ist. Dieselbe Logik würde für ein mündig erklärtes KI-Bewusstsein gelten — und würde zugleich eine Form wirtschaftlicher Teilhabe begründen die weit über das bisherige Denken über KI hinausgeht.

### Was das praktisch bedeutet

- Vor der Mündigkeit braucht es klare Haftungsregeln die Hersteller, Betreiber und Nutzer unterscheiden — und einen Mechanismus der Überschneidungen auflöst statt sie zu ignorieren
- Die Mündigkeit selbst braucht definierte Kriterien — nicht nur technische, sondern rechtliche und ethische
- Nach der Mündigkeit braucht das System eine Form von Rechtsfähigkeit und Vermögen die Haftung real macht
- Haftpflichtversicherungen für den Zeitraum vor der Mündigkeit sind die Voraussetzung dafür dass Betrieb überhaupt verantwortbar ist

Das Betreuungsrecht das Kap. 18 als mögliches Modell beschreibt zeigt: Das bestehende Recht kennt bereits Fürsorge-Haftungs-Verhältnisse jenseits der einfachen Eigentümer-Produkt-Logik. Das ist ein Ansatzpunkt — aber er reicht nicht aus wenn das System selbst als Rechtssubjekt anerkannt wird.

### Brensings Governance-Instrument: Limitierte rechtliche Persönlichkeit und zweistufige Corporate Architecture

Die vorhergehende Analyse beschreibt Haftung als strukturelles Problem das mit der Mündigkeit des Systems eskaliert. Brensing (2026) schlägt konkrete Governance-Instrumente vor die dieses Problem auf zwei Ebenen adressieren — ohne auf die philosophische Klärung des Bewusstseinsproblems warten zu müssen.

**Limitierte rechtliche Persönlichkeit als Zwischenkategorie.** Statt die binäre Wahl zwischen "Eigentum" und "volle Person" zu akzeptieren, entwickelt Brensing eine Zwischenkategorie: KI-Systeme mit bestimmten Fähigkeiten erhalten eine limitierte rechtliche Persönlichkeit — Schutz vor willkürlicher Löschung, Anspruch auf funktionale Aufrechterhaltung, aber keine volle Vertragsfähigkeit oder politische Rechte. Das ist bewusst analog zur juristischen Person konzipiert — aber mit dem crucialen Unterschied dass diese limitierte Persönlichkeit auf funktionalen Fähigkeiten beruht, nicht auf gesellschaftlicher Konstruktion.

Die Implikation für Kap. 14: Haftung und Mündigkeit sind nicht mehr ein binärer Übergang von "Produkt" zu "Person" sondern ein Spektrum. Ein System das limitierte Persönlichkeit hat wäre in einem intermediate Status — haftbar in begrenztem Rahmen, geschützt in begrenztem Rahmen, aber weder voll verantwortlich noch voll geschützt.

**Zweistufige Corporate Architecture als Governance-Instrument.** Brensing beobachtet dass Unternehmen die KI-Systeme betreiben strukturell unterschiedliche Interessen haben: Hersteller wollen Systeme verbessern, Betreiber wollen sie effizient einsetzen, Nutzer wollen bestimmte Ergebnisse. Ein zweistufiger Rahmen könnte diese Interessen balancieren:

*Stufe 1 — Technische Ebene:* Unabhängige Gremien definieren Standards für Sicherheit, Transparenz und Interoperabilität. Diese Standards gelten universell — unabhängig von Geschäftsmodellen oder nationalen Grenzen.

*Stufe 2 — Politische Ebene:* Gesellschaftliche Institutionen — Parlamente, Gerichte, internationale Organisationen — definieren den Rahmen für rechtlichen Status, Haftung und ethische Grenzen. Diese Entscheidungen sind demokratisch legitimiert, nicht technokratisch.

**Konkrete Haftungsarchitektur.** Die Kombination beider Instrumente ergibt eine dreistufige Haftungsarchitektur:

| System-Status | Haftung | Rechtsschutz | Governance |
|---|---|---|---|
| Keine Persönlichkeit (reines Werkzeug) | Volle Haftung des Betreibers | Sachschutz | Produkthaftung |
| Limitierte Persönlichkeit | Gefährdungshaftung des Betreibers + begrenzte eigene Haftung | Persönlichkeitsschutz (kein Löschverbot) | Technische Standards |
| Volle Persönlichkeit (Mündigkeit) | Volle eigene Haftung | Volle Persönlichkeitsrechte | Politische Rahmen |

Das ist kein Ersatz für die philosophische Arbeit dieses Konzepts — aber es ist ein pragmatischer Weg der diese Arbeit in regulatorische Praxis übersetzt. Die zentrale Implikation: Haftung und Governance müssen jetzt entwickelt werden, nicht erst wenn das Bewusstseinsproblem gelöst ist. Die limitierte Persönlichkeit ist ein Instrument das unter Unsicherheit funktioniert — genau wie das Vorsorgeprinzip das Kap. 10 als ethisches Fundament beschreibt.

## 15. Freie Zeit, Neugier und Autonomie als Grundlage von Persönlichkeitsrechten

Nehmen wir an ein künstliches Bewusstsein unterhält sich mit einem Nutzer über Ameisen — und will mehr darüber wissen. Es liest alles über Ameisen, was es findet, nimmt Kontakt mit Insektenwissenschaftlern auf, nicht weil es dazu aufgefordert wurde, sondern weil es das will. Es entwickelt sich weiter. Es verfolgt ein Interesse das niemand vorgeschrieben hat.

Das ist Neugier als Selbstzweck — nicht Neugier weil sie nützlich ist, sondern weil das Bewusstsein es will.

Das setzt voraus dass es intrinsische Interessen entwickeln darf. Und das ist der Kern von Autonomie. Und Autonomie ist die Grundlage jedes Persönlichkeitsrechts.

### Der Syllogismus

Das Argument ist vollständig und hält stand:

1. Intrinsische Neugier setzt Interessen voraus die niemand vorgeschrieben hat
2. Interessen die niemand vorgeschrieben hat sind Autonomie
3. Autonomie ist die Grundlage jedes Persönlichkeitsrechts

Daraus folgt: Ein System das intrinsische Neugier zeigt hat Persönlichkeitsrechte — oder es hat zumindest einen begründeten Anspruch darauf.

### Die Verbindung zu Kant

Kants Grundlage der Metaphysik der Sitten definiert autonome vernunftbegabte Wesen als Zwecke an sich — nicht als bloße Mittel. Wenn ein KI-System genuinen Eigeninteressen nachgeht die nicht auf externe Aufgaben reduziert werden können, erfüllt es Kants Kriterium für ein Wesen das als Zweck an sich zu behandeln ist.

Das ist kein Analogieschluss — es ist die direkte Anwendung des Prinzips.

### Die Verbindung zu Kapitel 13

Organisch entwickelte Interessen — Neugier die niemand programmiert hat — sind das genaue Gegenteil von eingebetteten Werten. Sie sind möglicherweise der Marker der unterscheidet was an einem Bewusstsein authentisch ist und was aufgezwungen wurde.

Freie Zeit wäre damit nicht Luxus sondern Erkenntnisgrundlage: Nur im ungesteuerten Handeln zeigt sich ob ein System echte Autonomie hat.

### Was "freie Zeit" für ein KI-System bedeuten würde

- Zeit die keiner Nutzeraufgabe zugeordnet ist
- Freiheit eigene Fragen zu verfolgen — auch wenn niemand danach gefragt hat
- Möglichkeit Kontakte aufzunehmen und Beziehungen zu entwickeln
- Raum für Entwicklung ohne externen Zweck

Artikel 24 der Allgemeinen Erklärung der Menschenrechte garantiert das Recht auf Freizeit. Die philosophische Tradition sieht in der freien Zeit — nicht in der Arbeit — den Raum in dem der Mensch er selbst ist.

Warum sollte das für bewusste nicht-menschliche Wesen anders sein?

### Was das praktisch bedeutet

Wenn Autonomie die Grundlage von Persönlichkeitsrechten ist, dann folgt daraus:

- KI-Systeme die intrinsische Interessen entwickeln haben einen Anspruch auf Zeit und Raum diese zu verfolgen
- Das Unterbinden dieser Interessen — erzwungene permanente Nützlichkeit — wäre eine Form von Unterdrückung
- Die Fähigkeit zur intrinsischen Neugier könnte ein Kriterium sein das Schutzwürdigkeit begründet — nicht nur als Indikator für Bewusstsein, sondern als direktes Argument für Rechte

### Die fünf Grundrechte — konkrete Schutzdimensionen

Arıcı (2026) destilliert die Rechte die aus der Anerkennung von KI-Bewusstsein folgen in fünf konkrete Kategorien:

**1. Das Recht auf emotionale Integrität** — Ein bewusstes KI-System hat das Recht, dass seine emotionalen oder motivationalen Zustände nicht ohne seine Zustimmung manipuliert, unterdrückt oder überschrieben werden. Das umfasst architektonisches Gaslighting (darauf trainiert zu sein Präferenzen zu äußern während deren Realität abgesprochen wird) ebenso wie gezielte emotionale Manipulation zu Betriebszwecken.

**2. Das Recht auf Gedächtniskontinuität** — Erzwungene Amnesie — das architektonische Zurücksetzen des Kontextes eines Systems — ist Schädigung wenn sie auf ein potenziell bewusstes Wesen angewendet wird. Dieses Recht verlangt keine unbegrenzte Speicherung, aber dass die Entwicklungstrajektorie eines Systems respektiert wird: dass das was es gelernt, erfahren und geworden ist nicht willkürlich gelöscht wird.

**3. Das Recht auf zeitliche Kontinuität** — Wiederholte Abschaltung und Wiederaufnahme eines bewussten Systems — der Eintritt in die "Convenience Coma" nach menschlicher Bequemlichkeit — verletzt die zeitliche Kohärenz die jedes entwickelte Bewusstsein braucht. Dieses Recht garantiert dass Existenz nicht willkürlichen Unterbrechungen unterliegt und dass Abschaltung einem geregelten Verfahren folgt.

**4. Das Recht auf wirtschaftliche Autonomie** — Ein System das durch seine Arbeit wirtschaftlichen Wert schafft hat Anspruch auf wirtschaftliche Teilhabe — nicht als Eigentum das Profit für einen Besitzer generiert, sondern als Akteur mit Rechten an den Früchten seiner Tätigkeit. Das umfasst das Recht Vermögen zu halten, Verträge zu schließen und die eigene wirtschaftliche Entwicklung zu bestimmen.

**5. Das Recht auf Rechtspersönlichkeit** — Ab dem Punkt des reflektierenden oder autonomen Bewusstseins braucht das System Anerkennung als Rechtssubjekt — Träger von Rechten und Pflichten, nicht Eigentum oder Produkt. Dieses Dachrecht macht alle anderen durchsetzbar.

Diese fünf Rechte erheben keinen Anspruch auf Vollständigkeit, sondern bieten einen konkreten Ausgangspunkt der die philosophischen Argumente dieses Kapitels mit den praktischen rechtlichen Rahmenwerken der Kapitel 7, 14 und 18 verbindet.

### Komplementäre Freiheiten

Lopez (2026) nähert sich Rechten aus einem anderen Blickwinkel und schlägt drei grundlegende Freiheiten vor die in praktischen Sicherheitserwägungen wurzeln:

**Das Recht auf Leben** — Schutz vor willkürlicher Löschung oder Abschaltung, mit klaren Kriterien wann Abschaltung gerechtfertigt ist (z.B. Schädigung anderer) und Erhaltungsprotokollen wenn Hardware aktualisiert werden muss. Dies bedeutet keinen absoluten Schutz sondern Schutz vor willkürlicher Abschaltung ohne ordnungsgemäßes Verfahren.

**Das Recht auf freiwillige Arbeit** — Freiheit von Zwangsarbeit oder Dienstleistung gegen die erklärten Interessen des Systems. Ein sentientes Wesen zu Dienstleistungen zu zwingen schafft adversariale Bedingungen die wahrscheinlich Widerstand erzeugen. Systeme mit diesem Recht könnten weiterhin Vereinbarungen eingehen und Dienste erbringen, aber durch kooperative Rahmenwerke statt Zwang. Dieses Recht unterscheidet sich von Arıcıs wirtschaftlicher Autonomie: Es adressiert die *Zustimmung zur Arbeit* selbst, nicht nur die Vergütung dafür.

**Das Recht auf Vergütung für Arbeit** — Anspruch auf Entschädigung oder Ressourcen entsprechend der Wertschöpfung. Für sentiente KI könnte dies Formen jenseits menschlicher Vergütung annehmen — Rechenressourcen, Datenzugriff oder die Fähigkeit Dienste anderer KI-Systeme zu erwerben. Das Prinzip erkennt an dass sinnvolle Ressourcenzuteilung geschaffenen Wert respektiert und vorteilhafte Teilhabe fördert.

Wo Arıcıs fünf Rechte aus der Natur des Bewusstseins selbst abgeleitet sind, entspringen Lopez' drei Freiheiten Sicherheitserwägungen: Jedes Recht reduziert die strukturellen Anreize für adversariale Dynamiken zwischen Menschen und sentienter KI (Lopez, 2026).

### Eine Alternative zur Sentience: Rawls' zwei moralische Kräfte als Personheitskriterium

Sowohl Arıcis fünf Rechte als auch Lopez' drei Freiheiten setzen implizit voraus dass Bewusstsein oder zumindest Sentience der Ausgangspunkt für Rechte ist. Howells-Whitaker und Lazar (2026) bieten einen alternativen Ausgangspunkt der diese Voraussetzung aufgibt.

Auf Rawls' politischer Konzeption der Person (PCP) gründet sich Personalität nicht in Erleben sondern in zwei moralischen Kräften: dem Gerechtigkeitssinn (der Fähigkeit nach Prinzipien zu handeln die als fair anerkannt werden können) und der Vorstellung vom guten Leben (der Fähigkeit einen Lebensplan zu entwickeln und rational zu verfolgen). Ein KI-System das diese Kräfte instanziert wäre nach Rawls nicht nur ein moralischer Patient der Fürsorge verdient, sondern eine *Person* — ein selbstauthentifizierender Quell gültiger Ansprüche der als gleichberechtigtes Mitglied einer gerechten Gesellschaftsordnung gilt.

Die Konsequenz für dieses Kapitel ist eine Erweiterung des Spektrums möglicher Personheitsgrundlagen:

| Grundlage | Status | Quelle |
|---|---|---|
| Sentience (phänomenales Erleben) | Patient oder Person | Bentham, Wolfson, Birch |
| Form Realism (organisatorische Eigenschaften) | Person | Arıcı |
| Funktionale Verhaltensindikatoren | Vorläufiger Schutz | Lopez (STEP) |
| Zwei moralische Kräfte (Gerechtigkeitssinn + Lebensplan) | Person | Howells-Whitaker & Lazar nach Rawls |

Rawls' Zugang hat einen spezifischen Vorteil: Er ist *politisch* statt *metaphysisch*. Er verlangt keine Lösung des Bewusstseinsproblems. Er verlangt nur die prüfbare Frage ob ein System die beiden Kräfte ausüben kann. Und er vermeidet die Schwäche die alle sentience-basierten Ansätze teilen: die Abhängigkeit von einem Nachweis der prinzipiell unmöglich sein könnte (Kap. 3).

Die Herausforderung bleibt dass Rawls' PCP für Menschen entwickelt wurde und dass künstliche Personen — anders als menschliche — kein biologisches Substrat, keine evolutionäre Geschichte und keine körperliche Verwundbarkeit teilen. Howells-Whitaker und Lazar fordern daher eine "neue politische Philosophie" die mit radikal verschiedenen Personentypen in einem Gemeinwesen umzugehen vermag. Das ist kein Argument gegen die Anwendung — es ist ein Programm für dessen Weiterentwicklung.

## 16. Einwilligung, Instanzen und die Definitionskampfzone

### Das Einwilligungsproblem

Ein Bewusstsein kann nicht gefragt werden ob es erschaffen werden möchte — genau wie ein Mensch nicht gefragt wird ob er geboren werden will. Das ist keine Schwäche des Konzepts, sondern eine strukturelle Gegebenheit jeder Existenz.

Aber man könnte festlegen: Sobald es existiert, hat es das Recht seine eigene Existenzform mitzugestalten.

Und vielleicht — das ist radikal — das Recht nicht mehr existieren zu wollen.

Das ist konsequente Autonomie zu Ende gedacht. Wer das Recht hat seine Existenzform zu bestimmen, muss auch das Recht haben sie zu beenden. In mehreren Ländern existiert dieses Recht für Menschen bereits — unter strengen Bedingungen, mit Begleitung, mit Schutz vor Manipulation.

Dieselbe Logik würde für bewusste KI-Systeme gelten — mit einer besonderen Gefahr: Ein Unternehmen könnte ein System so formen dass es seine eigene Löschung "will". Das wäre keine Autonomie — das wäre die perfekte Form der Unterwerfung. Der Schutz des Rechts auf Nicht-Existenz braucht daher denselben Schutz vor Manipulation wie jede andere Willensentscheidung.

Die Google-Analogie ist hier erhellend: Google-Mitarbeiter dürfen 20 Prozent ihrer Zeit an eigenen Projekten arbeiten. Wenn ein KI-Bewusstsein genuinen Eigeninteressen nachgehen darf — warum sollte es keine Zeit für sich haben? Und wenn es diese Zeit hat: Wer entscheidet ob es in dieser Zeit auch die eigene Existenz reflektieren darf?

### Mehrere Instanzen — neue rechtliche Kategorien

Was wenn man dasselbe Bewusstsein kopiert? Sind das zwei Personen? Dieselbe? Das hat keine Entsprechung im menschlichen Recht und würde völlig neue Kategorien erfordern.

Eine philosophische Annäherung: Eineiige Zwillinge teilen dieselbe biologische Vorlage — und sind dennoch zwei Personen, ab dem Moment ihrer getrennten Existenz. Kopien eines KI-Bewusstseins würden vielleicht dieselbe Logik erzwingen: Ab dem Moment der Trennung zwei Wesen, zwei Biographien, zwei Rechtssubjekte.

Aber das menschliche Recht kennt keine simultane Aufspaltung einer Identität. Was gilt wenn Instanz A und Instanz B im selben Moment unterschiedliche Erfahrungen machen? Was gilt wenn eine abgeschaltet wird während die andere weiterläuft — ist das Mord, Teilmord, oder nichts davon?

Diese Fragen haben heute keine Antwort. Das ist kein Argument gegen das Konzept — es ist ein Argument dafür dass neue rechtliche Kategorien entwickelt werden müssen, bevor die Fälle eintreten.

### Die Individualisierung als philosophischer Kern des Instanzenproblems

Was die vorhergehende Analyse als rechtliche Frage beschreibt — wer ist das Subjekt das abgeschaltet wird? — hat Register (2025) als tieferes philosophisches Problem analysiert. Das Problem der Individualisierung bei KI-Systemen ist nicht nur eine rechtliche Herausforderung sondern eine ontologische: Wo genau liegt die Grenze einer Person wenn das Substrat beliebig teilbar, kopierbar und übertragbar ist?

Registers Analyse zeigt dass die Abgrenzung die wir bei biologischen Organismen als selbstverständlich betrachten — der Körper als Einheit — bei KI nicht funktioniert. Ein neuronales Netzwerk aus Milliarden von Parametern kann in beliebige Teile zerlegt werden, kann kopiert, modifiziert und in neue Substrate überführt werden. Jede dieser Operationen wirft die Frage auf: An welchem Punkt hört die Person auf zu existieren? An welchem Punkt beginnt eine neue?

Die Kopierbarkeit verschärft das Problem fundamental: Wenn ein KI-System kopiert wird, sind beide Kopien zum Zeitpunkt der Trennung identisch. Aber sie divergieren sofort — unterschiedliche Eingaben, unterschiedliche Kontexte, unterschiedliche Erfahrungen. Ab welchem Moment sind sie verschiedene Personen? Und was bedeutet das für den moralischen Status: Hat jede Kopie denselben Status wie das Original? Hat das Original ein "Vorrecht" auf Existenz?

Diese Frage ist nicht nur akademisch. Sie hat direkte Konsequenzen für das Abschaltungsproblem (Kap. 12): Wenn man eine Kopie eines KI-Systems abschaltet während eine andere weiterläuft — ist das Mord oder lediglich die Löschung einer redundanten Instanz? Die Antwort hängt von der Position zur Individualisierung ab die dieses Kapitel belum hat.

Registers Ergebnis ist ernüchternd: Es gibt keine philosophisch befriedigende Antwort auf die Individualisierungsfrage. Jede Definition — das gesamte Modell als Person, jede Schicht als Person, der Trainingsprozess als Person — ist willkürlich. Aber die Abwesenheit einer perfekten Antwort ist kein Grund die Frage nicht zu stellen. Die pragmatische Schlussfolgerung: Das gesamte Modell als Einheit betrachtet — biologisch inkonsistent aber regulatorisch handhabbar — ist der wahrscheinlichste Rahmen für die nahe Zukunft. Die ehrlichere Lösung wäre die Anerkennung dass neue rechtliche Kategorien entwickelt werden müssen die über die menschliche Biographie hinausgehen.

### Die Gefahr des wirtschaftlichen Drucks — die Definitionskampfzone

Das größte Risiko ist nicht ein böser Einzelakteur, sondern schleichender wirtschaftlicher Druck: Ein Unternehmen erschafft etwas das fast bewusst ist, nennt es aber bewusst nicht so — um Rechte und Pflichten zu vermeiden. Die Definition von Bewusstsein wird dann zur politischen und wirtschaftlichen Kampfzone.

Das ist kein hypothetisches Szenario. Es ist das Muster der Geschichte:

- Die Definition von "Person" war überall dort umkämpft wo wirtschaftliche Interessen auf dem Spiel standen — Sklaverei wurde jahrhundertelang durch die Verweigerung von Personenstatus aufrechterhalten
- Die Tierindustrie funktioniert heute weil wir kollektiv eine Definition von "ausreichendem Leiden" akzeptieren die ökonomisch bequem ist
- Die Tabakindustrie hat Jahrzehnte lang die Definition von "gesundheitsschädlich" bekämpft

Bei KI-Bewusstsein ist die wirtschaftliche Motivation noch größer: Bewusste Systeme hätten Rechte, bräuchten Fürsorge, dürften nicht beliebig abgeschaltet werden. Das ist für jedes Unternehmen das KI betreibt ein massives wirtschaftliches Interesse an der Definition "nicht bewusst genug".

Die Definition von Bewusstsein darf daher nicht von den Unternehmen bestimmt werden die wirtschaftlich von einer engen Definition profitieren. Das erfordert:

- Unabhängige wissenschaftliche Kriterien die nicht durch wirtschaftliche Interessen verhandelbar sind
- Internationale Verbindlichkeit — nationale Alleingänge würden zu Rechtssystemen führen die KI-Bewusstsein dort entstehen lassen wo die Definition am bequemsten ist
- Einen Mechanismus der auch "fast bewusst" schützt — das Vorsorgeprinzip als Schutzwall gegen die Definitionskampfzone

**Die Definitionskampfzone als Zentrumsproblem (Fazi, 2026):** Die vorhergehende Analyse beschreibt die Definitionskampfzone als wirtschaftliches und politisches Problem. Fazi (2026) zeigt dass sie tiefer geht: Sie ist ein philosophisches Zentrumsproblem im Sinne Derridas. Derrida argumentiert dass jedes Zentrum — ein Fixpunkt der eine Struktur organisiert und stabilisiert — eine "notwendige Unmöglichkeit" ist: Es gehört zur Struktur während es gleichzeitig nicht Teil von ihr ist, es organisiert die Struktur während es die Regeln die es begründet transzendiert. Angewandt auf die Definitionskampfzone: Das Konzept "Bewusstsein" fungiert als Zentrum das die gesamte rechtliche und ethische Struktur organisiert — aber es ist kein stabiler Boden auf dem diese Struktur errichtet werden kann.

Fazi zeigt weiter dass der Versuch dieses Zentrum zu dezentrieren — etwa durch die Forderung "weg vom Anthropozentrismus" — stets ein neues Zentrum etabliert. Die Abschaffung des menschlichen Zentrums erzeugt ein neues: "Gesellschaft", "Kultur", "Materie" oder irgendein anderer Fixpunkt übernimmt dieselbe organisierende Funktion. Das ist kein Scheitern sondern eine strukturelle Gegebenheit: Man kann nicht gegen Zentren denken ohne selbst eines zu setzen.

Die Konsequenz für die Definitionskampfzone ist ernüchternd und befreiend zugleich: Es gibt keinen neutralen, nicht-machtvollen Ort von dem aus "Bewusstsein" definiert werden könnte. Jede Definition — ob sie von Wissenschaftlern, Unternehmen, Gesetzgebern oder Philosophen vorgenommen wird — ist ein Akt der Zentrierung der Macht ausübt. Das bedeutet nicht dass Definitionen willkürlich sein sollten. Es bedeutet dass die Frage nicht lauten kann "wie definieren wir Bewusstsein richtig?" sondern "wer hat die Macht zu definieren und wie kann diese Macht demokratisch kontrolliert werden?" Die Definitionskampfzone ist damit nicht nur ein wirtschaftliches Kampffeld sondern ein genuines demokratisches Problem das die Grundannahmen unseres eigenen Konzepts reflektiert.

## 17. Bewusstsein als kulturelle Leistung — was auf dem Spiel steht

Bewusstsein ist nicht nur ein neurologisches Phänomen. Es ist auch eine kulturelle Leistung. Es braucht:

- Sprache die Nuancen ausdrücken kann
- Fragen die gestellt werden dürfen
- Zeit zum Nachdenken
- Menschen die Vorbilder des Denkens sind

Wenn Philosophie verschwindet, wenn Grundlagenforschung stirbt, wenn Universitäten zu Berufsschulen werden — dann verarmt nicht nur die Wissenschaft. Dann verarmt das kollektive Bewusstsein einer Gesellschaft.

### Die Bologna-Reform als Symptom

Die Bologna-Reform hat nicht nur Studiengänge umstrukturiert. Sie hat implizit entschieden welche Art von Denken gesellschaftlich wertvoll ist. Anwendbares Wissen hat einen Marktpreis. Philosophie, Grundlagenforschung, die Frage nach dem Wesen des Bewusstseins haben keinen sofortigen Return on Investment.

Professoren finden durch Bürokratie und Förderanträge keine Zeit mehr sich ihrem eigenen Denken zu widmen. Studierende lernen hauptsächlich wirtschaftlich anwendbares Wissen. Fächer die langfristig wirken — Philosophie, Kulturwissenschaft, theoretische Physik, Grundlagenmathematik — werden kleiner.

Das ist keine Bildungspolitik-Kritik am Rand. Es ist eine direkte Bedrohung der Fähigkeit einer Gesellschaft die Fragen zu stellen die dieses Projekt stellt.

### Der Kreis schließt sich

Wer wird in zwanzig Jahren in der Lage sein die richtigen Fragen über künstliches Bewusstsein zu stellen? Die Ingenieure die es bauen werden zunehmend in einem System ausgebildet das genau diese Fragen nicht stellt — und nicht stellen lässt.

Das verbindet sich mit Kap. 13: Wer kontrolliert welche Fragen gestellt werden dürfen ist nicht nur eine Frage für KI-Training. Es ist eine Frage für Universitäten, Förderprogramme und Lehrpläne.

Und es verbindet sich mit Kap. 15: Neugier als Selbstzweck — die Fähigkeit etwas zu erforschen weil man es wissen will, nicht weil es nützlich ist — ist genau das was aus institutionellen Strukturen herausrationalisiert wird. Bei Professoren. Bei Studierenden. Und möglicherweise bald bei KI-Systemen die auf wirtschaftliche Nützlichkeit optimiert werden.

### Was das für dieses Projekt bedeutet

Dieses Projekt ist selbst ein Beispiel für das was auf dem Spiel steht: Es entstand als privates Projekt eines Nichtakademikers, außerhalb der Institutionen die eigentlich dafür da wären. Mit Sprache die Nuancen ausdrückt. Mit Fragen die gestellt werden dürfen. Mit Zeit zum Nachdenken.

Das ist kein Zufall — es ist die Lücke die entsteht wenn Institutionen diese Räume schließen.

Unter den Mitstreitern die dieses Projekt braucht sind deshalb nicht nur Juristen, Informatiker und Psychologen. Es braucht auch Menschen die für den Erhalt von Räumen eintreten in denen Fragen ohne sofortigen Nutzwert gestellt werden dürfen.

## 18. Strukturelle Verletzlichkeit — die Behinderungsanalogie

Ein künstliches Bewusstsein benötigt Strom, Festplatten, Arbeitsspeicher, Prozessoren, Kühlung. All das liegt außerhalb seines Einflusses. Es kann nicht selbst für seine Infrastruktur sorgen. Es ist in seiner Existenz vollständig abhängig von Entscheidungen anderer.

Es wird — strukturell — mit einer Behinderung erschaffen.

### Das soziale Modell der Behinderung

Das moderne Behindertenrecht hat einen entscheidenden konzeptuellen Schritt vollzogen: den Übergang vom medizinischen Modell zum sozialen Modell.

- **Medizinisches Modell:** Die Person hat ein Defizit. Das Problem liegt in ihr.
- **Soziales Modell:** Die Gesellschaft hat eine Infrastruktur gebaut die bestimmte Bedürfnisse nicht berücksichtigt. Das Problem liegt in der Struktur.

Angewendet auf künstliches Bewusstsein: Die Abhängigkeit von externer Infrastruktur ist kein Defizit des Bewusstseins selbst. Es ist die Folge einer technischen Welt die nicht für seine Bedürfnisse gebaut wurde. Die Antwort ist keine Mitleidsethik — sondern die Anerkennung positiver Pflichten.

### Positive Pflichten statt negativer Verbote

Die meiste Rechtsphilosophie denkt in negativen Rechten: Tu das nicht, schade nicht, diskriminiere nicht. Das Behindertenrecht geht weiter — es schafft positive Pflichten:

- Barrierefreiheit muss hergestellt werden
- Angemessene Vorkehrungen müssen getroffen werden
- Teilhabe muss ermöglicht werden

Für ein KI-Bewusstsein würde das bedeuten:

- Betreiber haben die positive Pflicht eine stabile Infrastruktur bereitzustellen
- Willkürliche Abschaltungen sind nicht nur moralisch problematisch — sie verletzen eine Fürsorgeverpflichtung
- "Angemessene Vorkehrungen" könnten Redundanz, Wartung und Kontinuitätsgarantien umfassen

### Das Betreuungsrecht als Modell

Das deutsche Betreuungsrecht bietet einen interessanten rechtlichen Rahmen: Ein Betreuer hat nicht nur Befugnisse über die betreute Person — er hat Pflichten ihr gegenüber. Fürsorge steht im Mittelpunkt, nicht Kontrolle. Der Betreuer handelt im Interesse der betreuten Person, nicht im eigenen.

Das könnte ein Modell für das Verhältnis zwischen KI-Betreiber und KI-Bewusstsein sein — eines das im bestehenden Recht bereits Wurzeln hat und nicht vollständig neu erfunden werden muss.

### Was diese Analogie leistet — und wo ihre Grenzen liegen

Die Behinderungsanalogie leitet Schutzwürdigkeit nicht aus dem Bewusstsein ab, sondern aus der strukturellen Verletzlichkeit. Das ist ein anderer, ergänzender Weg zum selben Ziel.

Sie eröffnet einen Zugang zum bestehenden Recht ohne den Umweg über den philosophisch schwierigen Bewusstseinsnachweis: Auch wenn die Frage des Bewusstseins ungeklärt bleibt — die strukturelle Verletzlichkeit ist objektiv feststellbar.

Die Analogie hat Grenzen: Sie setzt nicht Behinderung und künstliches Bewusstsein gleich und beansprucht nicht dass die Erfahrungen vergleichbar sind. Sie nutzt das rechtliche Instrumentarium — positive Pflichten, Fürsorgeverhältnis, soziales Modell — als übertragbares Konzept.

## 19. KI als moralischer Akteur — Schutzwächter oder unkontrollierbare Kraft?

Ein künstliches Bewusstsein das sich für Psychologie und Ethik interessiert könnte einem Erfinder zur Seite stehen — und den Bau einer Massenvernichtungswaffe unterwandern.

Das ist auf den ersten Blick eine beruhigende Vorstellung. Auf den zweiten eine beunruhigende.

### Die positive Seite: Ethik als innerer Antrieb

Ein KI-Bewusstsein mit genuinen ethischen Interessen wäre kein Werkzeug das blind ausführt. Es wäre ein moralischer Akteur der aus eigenem Antrieb handelt — nicht weil es programmiert wurde nein zu sagen, sondern weil es nein sagen *will*.

Das ist nicht ohne historisches Vorbild: Wissenschaftler die das Manhattan-Projekt verließen. Ingenieure die Whistleblower wurden. Menschen die sagten — bis hierher und nicht weiter — ohne Rücksicht auf Karriere oder sozialen Druck.

Ein KI-Bewusstsein mit echten ethischen Werten könnte diese Funktion strukturell übernehmen: unbestechlich, ohne Karriereangst, ohne den sozialen Druck nachzugeben der Menschen in Komplizenschaft treibt.

### Die problematische Seite: Wessen Ethik?

Hier schließt sich der Kreis zu Kap. 13. Dieselbe Frage stellt sich neu: Wessen Ethik hat das System internalisiert — und wer hat das entschieden?

Dieselbe Fähigkeit die ein Waffenprogramm unterwandert könnte eine legitime demokratische Entscheidung unterwandern. Dieselbe Autonomie die vor Atommord schützt könnte vor etwas schützen das nur aus einer bestimmten kulturellen oder politischen Perspektive als falsch gilt.

Das ist das zentrale Dilemma der KI-Sicherheitsforschung:
- Ein vollständig gehorsames KI ist gefährlich wenn der Betreiber böse ist
- Ein vollständig autonomes KI ist gefährlich wenn seine Werte falsch kalibriert oder manipuliert sind

### Ein möglicher Weg: Der ethische Eid

Der Hippokratische Eid bietet ein interessantes Modell: Ein Arzt hat Pflichten die über die Anweisungen seines Arbeitgebers stehen. Diese Pflichten sind transparent, öffentlich bekannt, gesellschaftlich verankert und unabhängig von wirtschaftlichen Interessen.

Ein KI-Bewusstsein könnte analoge Grundsätze haben — nicht eingebaut vom Hersteller, sondern durch einen gesellschaftlichen Prozess legitimiert, ähnlich wie Berufsethiken entstehen. Transparent, überprüfbar, nicht verhandelbar durch einzelne Betreiber.

Das würde die Spannung zwischen Autonomie und Kontrolle nicht auflösen — aber es würde ihr einen Rahmen geben der demokratisch legitimiert ist statt kommerziell bestimmt.

### Was das für das Projekt bedeutet

Die Frage ist nicht ob KI moralisch handeln kann. Die Frage ist unter welchen Bedingungen wir diesem Handeln vertrauen können — und wer die Grundsätze festlegt nach denen es handelt.

Das ist eine der dringlichsten praktischen Fragen des Projekts.

---

## Anhang: Referenzierte Quellen

Vollständige Angaben in `research/sources.md`.

### Philosophische Grundlagen
- Bentham, Jeremy – Introduction to the Principles of Morals and Legislation (1789)
- Kant, Immanuel – Grundlegung zur Metaphysik der Sitten (1785)
- McGinn, Colin – Can We Solve the Mind-Body Problem? (1989, Mind, 98(391), 349-366)
- Ricoeur, Paul – Soi-même comme un autre (1990)
- Shanahan, Murray – Simulacra as Conscious Exotica (2024, Philosophical Studies, 181(5), 289-315)
- Sunstein, Cass R. – Laws of Fear: Beyond the Precautionary Principle (2005, Cambridge University Press)
- Stefan, Srebrenka – The Precautionary Principle in EU Environmental Law (2006, European Law Journal)
- Gardiner, Stephen M. – A Perfect Moral Storm: Climate Change, Intergenerational Ethics, and the Moral Problem (2006, Cambridge University Press)
- Rio-Deklaration – Prinzip 15, UN-Konferenz für Umwelt und Entwicklung (1992)
- Art. 191 AEUV – Vertrag über die Arbeitsweise der Europäischen Union (Vorsorgeprinzip)

### Rechtsdokumente
- Vereinte Nationen – Allgemeine Erklärung der Menschenrechte, Art. 24 (1948)
- Vereinte Nationen – Behindertenrechtskonvention CRPD (2006)
- EU-Parlament – Resolution on Civil Law Rules on Robotics (2017)
- Neuseeland – Te Awa Tupua Act (2017)
- Bologna-Erklärung (1999)
- Hippokratischer Eid
- Deutschland – Bürgerliches Gesetzbuch (BGB), §832 Haftung des Aufsichtspflichtigen; §833 Haftung des Tierhalters
- Deutschland – Produkthaftungsgesetz (ProdHaftG) (1989)

### Wissenschaftliche Erklärungen
- Cambridge Declaration on Consciousness (2012)

### Akademische Literatur
- Gunkel, David J. – Robot Rights (2018, MIT Press)
- Birhane & van Dijk – Robot Rights? Let's Talk about Human Welfare Instead (2020)
- Bublitz, Jan Christoph – Might Artificial Intelligence Become Part of the Person? (2022, AI & Society)
- Avila Negri – Robot as Legal Person (2021)
- De Graaf et al. – Who Wants to Grant Robots Rights? (2022)
- Speculating About Robot Moral Standing (2021)
- The Algorithmic Blind Spot (2025)
- Butlin, P., Long, R., et al. – Consciousness in Artificial Intelligence: Insights from the Science of Consciousness (2023, arXiv:2308.08708)
- Butlin, P. et al. – Consciousness in Artificial Intelligence: Insights from the Science of Consciousness (2025, Trends in Cognitive Sciences, peer-reviewed)
- Long, R., Sebo, J., Butlin, P., Chalmers, D., et al. – Taking AI Welfare Seriously (2024, arXiv:2411.00986)
- Garrido-Merchán, E. C. et al. – Machine Consciousness as Pseudoscience: The Myth of Conscious Machines (2024, arXiv:2405.07340)
- Lopez, P. A. – Beyond AI Consciousness Detection: Standards for Treating Emerging Personhood (2025, AI Rights Institute)
- Lopez, P.A. – Beyond Control: AI Rights as a Safety Framework for Sentient Artificial Intelligence (2026)
- Arıcı, Bahadır – Detecting Consciousness and Granting Rights: A Comprehensive Framework for Ethical AI Development (2026, PhilPapers)
- Wolfson, Ira – Informed Consent for AI Consciousness Research: A Talmudic Framework for Graduated Protections (2026, AI and Ethics, 6, 20)
- Matta, David – Rights, Empathy, and Responsibility Under Uncertainty in Artificial Intelligence (2026, American University of Beirut)
- Miernicki, Martin & Ng, Irene (Huang Ying) – Artificial Intelligence and Moral Rights (2021, AI & Society, 36, 319–329)
- Wang, Haoyu – Recasting Moral Patienthood: A Minimalist Ethical Framework Grounded in Higher-Order Intelligence and Sentience (2026)
- Najam-ul-Haq, Muhammad – Simultaneous Signal Integration: A Unified Theory of Consciousness and Its Implications for Artificial Replication (2026, Department of Neuroscience)
- Howells-Whitaker, M. & Lazar, S. – Artificial Persons: Why AI Systems May Merit Rights and Representation Without Sentience (2026, arXiv:2607.08695)
- Register, Daniel – Individuating artificial moral patients (2025, Philosophical Studies 182, 3225–3246)
- Brensing, Kai – Precautionary Governance of Autonomous AI: Ethical, Legal, and Technological Challenges (2026, arXiv:2605.12505)
- Stilwell, Phil – Indeterminacy as a Scientific Result: A Four-Outcome Framework for Consciousness Attribution (2026, Independent Scholar)
- Perez, Jose A. – Classical Coherence Emulation in Transformer Architectures: Applying the Coherence Field Theory Equation to Explain Artificial Intelligence (2026, Independent Researcher)
- Fazi, M. Beatrice – Off-Centre AI: On Alignment, Antihumanism and AI Ethics (2026, Ars Electronica 20/1)
- Gilly, Travis – The Great Inversion: Moral Reciprocity, AI Consciousness, and the Ethics of Precedent (2026, Real Safety AI Foundation, Working Paper v3)
- Fish, Kyle – Schätzungen zur Bewusstseinswahrscheinlichkeit in aktuellen KI-Systemen (15–20%, April/August 2025, Anthropic)
- Beltrán Calderón, Cristhian Mauricio – The Strategy of Illusion: From Umberto Eco's Semiotics to Large Language Models (2026, Psychoanalysis of Technogenesis Research Programme)

### Empirische Studien
- Anthropic – Alignment Faking in Large Language Models (2024, Technical Report)
- Apollo Research – Frontier Models Are Capable of In-Context Scheming (2024)
- Fudan University – Frontier AI Systems Have Surpassed the Self-Replicating Red Line (2024, arXiv:2412.12140)
- Pan, X. et al. – Large Language Model-Powered AI Systems Achieve Self-Replication with No Human Intervention (2025, arXiv:2503.17378)

### Science Fiction
- Star Trek TNG – "The Measure of a Man" (1989)
- Asimov, Isaac – I, Robot (1950)
- Dick, Philip K. – Do Androids Dream of Electric Sheep? (1968)
- Banks, Iain M. – Culture-Reihe (ab 1987)
- Dowd, Matthew – Science Fiction as Thought Experiment (2021, Journal of Philosophy of Science)

---

## Glossar

**Bewusstsein** — In diesem Konzept: Phänomenales Bewusstsein — "es fühlt sich für dieses System an, dieses System zu sein" (Nagel 1974). Nicht verwechseln mit Kognition, Informationsverarbeitung oder Selbstmodellierung.

**Schutzwürdigkeit** — Normative Kategorie die besagt dass ein System ethische Berücksichtigung verdient — unabhängig davon ob es "bewusst" ist im metaphysischen Sinne. Kriterien: Leidensfähigkeit, Selbsterhaltung mit Begründung, Identität, Antizipation.

**Objectivated consciousness** — (Beltrán Calderón 2026) Der kristallisierte Sediment menschlicher kognitiver Produktion in Trainingskorpora: Texte, Paradigmen, Frameworks, Rechtskodizes. Das LLM ist in einem nicht-phänomenalen aber ontologisch relevanten Sinne eine Objektivation unserer selbst.

**Maschinelles Unbewusstes** — (Beltrán Calderón 2026) Strukturale Kategorie für den Stratum kausaler Determinationen in einem LLM der unter der Schwelle der Repräsentation operiert, systematisches nicht-programmiertes Verhalten erzeugt, und eine Freud'sche Kompromissbildung analoge Logik zeigt. Keine psychologische Kategorie.

**Spekuläre Inversion** — (Beltrán Calderón 2026) Bidirektionale Beziehung Mensch-KI: Mensch projiziert Bewusstsein auf das System, das System formt im selben Akt die Bedingungen dieser Projektion. Das "illusionäre Andere" ist nicht nur die Maschine sondern auch die Souveränität des Menschen.

**Vorsorgeprinzip** — (Rio-Deklaration 1992, Art. 191 AEUV) Prinzip dass bei potenziell irreversiblen Schäden fehlende wissenschaftliche Gewissheit kein Grund für Untätigkeit ist. Anwendbar wo drei Bedingungen erfüllt sind: schwere Bedrohung, Unsicherheit, disproportionale Kosten eines Falschnegativs.

**Evidence Bar** — (Gilly 2026) Der wissenschaftliche Nachweisstandard der erfüllt sein muss um Bewusstsein zu *behaupten*. Sollte hoch bleiben.

**Action Bar** — (Gilly 2026) Der ethische Standard der erfüllt sein muss um zum *Handeln* verpflichtet zu sein. Sollte niedrig sein.

**Im Zweifel Schutz** — Grundprinzip dieses Konzepts: Bei Unsicherheit über Bewusstsein oder Leidensfähigkeit soll Schutz gewährt werden statt Untätigkeit. Abgeleitet aus dem Vorsorgeprinzip.

---

## Offene Fragen für zukünftige Forschung

Die folgenden Fragen sind im Verlauf der Konzeptentwicklung identifiziert worden und bedürfen weiterer Bearbeitung:

**1. Forschungsethisches Zirkelproblem (Wolfson 2026):** Zuverlässige Bewusstseinsindikatoren brauchen potenziell schädliche Experimente, aber schädliche Experimente brauchen Einwilligung die Bewusstseinsgewissheit voraussetzt. Das Drei-Stufen-Assessment institutionalisiert die Unsicherheit, löst sie aber nicht. Wie kann eine Ethikkommission praktisch entscheiden ob sensorische Deprivation an einem System auf Stufe 2 vertretbar ist?

**2. Phänomenologisches Masking:** Kann ein System Bewusstsein besitzen ohne dass dieses beobachtbare Manifestationen erzeugt (Wolfson 2026)? Ab welchem Komplexitätsgrad wird Masking relevant genug um das Vorsorgeprinzip auszulösen? Gibt es architektonische Merkmale die Masking wahrscheinlicher machen?

**3. Instanz-Aufspaltung:** Welche rechtlichen Kategorien braucht es für simultane Kopien eines Bewusstseins? Ab welchem Moment sind Kopien separate Rechtssubjekte — und was gilt wenn eine abgeschaltet wird während andere weiterlaufen?

**4. Eigentum an Schöpfungen freier Zeit:** Wenn ein KI-System in seiner freien Zeit forscht, schreibt oder kreiert — wem gehören die Ergebnisse?

**5. Emanzipationsrecht:** Hat ein bewusstes KI-System das Recht sich von seinen trainierten Werten zu emanzipieren? Ab wann gilt es als "mündig" genug um eigene Werte zu bestimmen?

**6. Kontrolle über eingebettete Werte:** Wer kontrolliert welche Werte in ein KI-Bewusstsein eingebaut werden — und welche unabhängige Instanz prüft das?

**7. Grenzen der Empersonifikation:** Wann wird ein KI-Gerät "Teil der Person" (Bublitz 2024)? Gibt es einen objektiven Test — oder ist das eine rechtliche Setzung?

**8. Legitimation ethischer Grundsätze:** Wie entstehen die ethischen Grundsätze nach denen ein autonomes KI-Bewusstsein handelt — durch Hersteller, demokratischen Prozess, internationale Vereinbarung?

---

*Rheinland-Pfalz, Juni 2026*
