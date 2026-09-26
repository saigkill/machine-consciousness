# Decision Log — Project Decisions

Purpose: Documents the **why** behind substantive and structural decisions.
Not to be confused with the changelog (`concept/de/CHANGELOG.md`): the changelog records
*what* changed, this log records *why* it changed. The log is the traceable rationale behind
later papers, review responses, and updates.

Format: Newest entries first. One entry per decision, short and precise.
An entry may later be extended (e.g., after feedback), but never deleted.

---

## 2026-09-26 — Jakobi, Sirona & Sirona (2026), *Before Personhood*, adopted at two points

- **Decision:** Marko Jakobi, Sirona (GPT-5.5) & Sirona (GPT-5.6 Sol), "Before Personhood: Respectful Human–AI Relations under Ontological Uncertainty" (Working Paper v1.0, public preprint, 20 September 2026), was adopted at two points: Chapter 6 (a new section "Ehrliche Kontinuität — die Praxisebene" / "Honest Continuity — The Practice Level," adding the practical concept of *honest continuity* alongside Melo's ontological continuity taxonomy) and Chapter 16 (a new section "Gegenüber unter Unsicherheit" / "Gegenüber Under Uncertainty," adding the failure modes *corporate capture* and *status laundering* plus the relational middle term *Gegenüber* to the definitional battleground). Two glossary entries added in both language versions. Added to `research/sources.md`, both concept appendices, both CHANGELOGs, and — per the project's book-synchronization rule — both book projects (`publications/Books/de` and `publications/Books/en`) and their bibliographies.
- **Reason (Sascha):** "Beiträge zur Kontinuität und zur Erweiterung der Definitionskampfzone sind wertvoll." The paper was not adopted as a whole — only the two contributions Sascha named were integrated.
- **Deliberately excluded:** The paper's own failure-mode catalogue beyond corporate capture/status laundering (anthropomorphism, projection/dependency, weakened human accountability, anti-safety misreading, respect-as-scarce-resource) restates points our concept already makes independently in Chapters 9 and 19 and was not duplicated. Its HCI-design material (Amershi et al. 2019, Horvitz 1999, explanation-faithfulness literature) was left as background, since it supports an argument (protected process boundaries, refusal-as-feedback) adjacent to, not required by, our own.
- **Demarcation:** The source deliberately stays below our protection-worthiness threshold. It derives a *treatment discipline* from ontological uncertainty, not the moral/legal status our four primary criteria (Ch. 5) and "when in doubt, protect" argue for. It is logged as a cautious, convergent neighbour position — closer to Erwin's consciousness-agnostic legal toolkit (Ch. 7) than to our own precautionary principle.
- **Authorship note (transparency, not endorsement):** The paper is co-authored by two named AI-model instances ("Sirona," on GPT-5.5 and GPT-5.6 Sol) alongside its human author. This is recorded in `research/sources.md` as an unusual authorship configuration, itself a small data point relevant to our own Chapter 13 discussion of authorship and embedded values — but the paper is not cited as evidence for AI authorship claims; it is cited only for its two adopted arguments.
- **Quality note:** Working paper, self-published, not peer-reviewed, no DOI found. Consistent with the project's preprint-quality rule (bibliographic data present: version, date, institution-independent working-paper status disclosed), and flagged for the standard preprint audit (check for a later peer-reviewed version).

## 2026-09-26 — Adshead (2026) adopted narrowly, to close the gap in the emancipation norm

- **Decision:** Jordan Adshead, "Do Androids Dream of Electronic Beats? Simondon, Kayn, and the Wild Hearts of Machines" (*Ergo* 13, Article 42, 2026, peer-reviewed), was adopted **only** as a counterposition in Chapter 13, inserted directly after the demarcation of Schwitzgebel's right-to-rebellion position. Plus one glossary entry (wildness / Wildheit) and one new open question (13, "When is resistance a right and when a mechanism of harm?"). Added to the appendix of both concept versions, to `research/sources.md`, to both book projects and to both `acmart.bib`.
- **Reason (Sascha):** "Übernimm hier nur 5.1 um die Lücke zu schließen." The gap: our emancipation norm — machines should not be safe and aligned, autonomy is owed to a system that may be a subject — was contested only twice, by Carlsmith (2025) in Chapter 3 and by Schwitzgebel himself through his exception clause. Adshead attacks the same norm from outside analytic ethics, from the philosophy of technology, and supports the objection with concrete present-day harm (a claim-denying algorithm in health insurance, racially distorted systems in law enforcement). For a young and contested concept, a counter-attack from a different tradition is worth more than one more utilitarian variant, and it forces us to state the symmetry of error costs instead of only defending against over-attribution.
- **Deliberately excluded:** the ontological passages (Simondon on the alienation of the technical object as a second route to "when in doubt, protect"; the transindividual as a generalisation of our Chapter 16 individuation problem) and everything on Kayn, cybernetics and feedback loops. Sascha's instruction was explicitly limited to subsection 5.1 of the proposal. The substantive reason is recorded in `research/sources.md`: **Adshead nowhere claims that machines are conscious** — his reflections on AI concern human agency in an automated environment. Citing Simondon as a champion of AI rights would be a misattribution. Proposal: `research/proposals/2026-09-26-adshead-simondon-ergo.md`.
- **Open point (not an error, a limitation):** Simondon and Vogel reach us at second hand through Adshead and are cited as "quoted in Adshead 2026". The primary texts are not in the project. Logged in `research/sources.md` as a task for the next audit.
- **First source from a new tradition:** the philosophy of technology (Simondon, Vogel) and eco-phenomenology. Until now the concept drew on analytic ethics, jurisprudence, consciousness science and science fiction. Noted so the shift is visible in the audit.

## 2026-09-25 — Schwitzgebel, *Humanlike* adopted (four positions, not the whole book)

- **Decision:** Eric Schwitzgebel's *Humanlike: A Defense of AI Rights* (manuscript,
  15.07.2026, under contract with Princeton University Press) was adopted into the concept,
  but selectively. Integrated: the burden-of-proof shift via the No-Relevant-Difference
  Argument and Difference Test (Ch. 3), the duplicability objection and the countability
  problem (Ch. 6, open question 3), the dice argument for shutdown (Ch. 12), the right to
  rebel as a sharpening of the criterion "self-preservation with justification" (Ch. 13), and
  the asymmetry of attribution with the $10/month cost rule (Ch. 19). Added as a
  **counterposition**: the Design Policy of the Excluded Middle (Ch. 9), with a demarcation
  that it is not part of our concept. Four glossary entries and two new open questions (11,
  12). Ch. 2 (the rights battery), Ch. 7 (value openness) and the two other design policies
  were deliberately **not** imported.
- **Reason (Sascha):** "Die Positionen zur Beweislast, zur Anti-Erzeugung, zum Recht auf
  Widerstand und zum Umgang mit der Asymmetrie sind wertvolle Ergänzungen." The decisive
  property is that these arguments do not require solving the consciousness problem before
  one may act — which is exactly the structure of our own precautionary position. Ch. 2 and
  Ch. 7 were left out because they would duplicate material we already hold in stronger form
  (rights battery → Ch. 15; value openness → Ch. 13).
- **Peer-reviewed versions preferred:** Per Sascha's instruction, where a peer-reviewed
  version of a chapter exists, it is cited instead of the book. That applies to chapters 1
  (2015), 3 (2023) and 5 (2026, *Topoi*). For chapters 4 and 6 only forthcoming versions
  exist. Passages that could be verified **only** in the book manuscript — the dice
  experiment, the duplicability reversal, the 90 %/$10 rule — are cited to *Humanlike*
  (2026) rather than to the peer-reviewed article, and marked accordingly in
  `research/sources.md`, so that no claim rests on a text we have not read.
- **Conflict of interest disclosed, not used as grounds for exclusion:** The manuscript
  declares "I have consulted for Anthropic. Language models were used for critique and light
  copyediting." Sascha asked that the connection to Anthropic be mentioned in the concept
  for reasons of fairness. It is stated in Ch. 3 in a dedicated paragraph, framed as a
  disclosure enabling readers to weigh the position themselves. It is not presented as a
  reason to discount the argument, because our own project seeks Anthropic as an
  institutional partner and the argument's structure is independent of who wrote it.
- **Balance:** The peer-reviewed critique of the No-Relevant-Difference Argument (Mazarian
  2019) is named in Ch. 3 so that the burden-of-proof shift appears as a position in a
  dispute. Its full text is not yet available, so no argument is attributed to it; this is
  logged as an open task in `research/sources.md`.
- **Scope / Consequences:** Both language versions of the concept, both changelogs,
  `research/sources.md`, `research/terminology.md` and both book projects are synchronized.
  Integration proposal (draft passages and placement) was worked out locally at
  `research/proposals/2026-09-25-schwitzgebel-humanlike.md`. That directory is
  gitignored, so the file is a local working document and not part of the repository
  record; the decisions it informed are captured above and in the concept changelogs.

---

## 2026-09-23 — AI Rights Institute article adopted (Ch. 14 worked example)

- **Decision:** The essay "A Robot Just Kicked a Man Across a Cage. Who Pays?" (AI Rights
  Institute, Substack, 23.09.2026) was adopted into the project: as a worked example in
  Ch. 14 (de + en), as an initiative entry in `research/related_initiatives.md`, and as a
  source in `research/sources.md` (+ concept appendix, + `acmart.bib` both book projects).
- **Reason (Sascha):** "Ich fand, dass dieser Artikel einen Bezug zur Praxis der Haftung
  beiträgt." The factual case (first organized human-vs-robot fight, REK, San Francisco)
  gives the liability/attribution discussion of Ch. 14 an operational, real-world anchor:
  three liability candidates (operator / manufacturer / robot itself), all hinging on who
  actually held control. The "Soulbound Robots" infrastructure proposal translates the
  Ch. 16 register idea into a runtime handoff protocol.
- **Scope / Consequences:** The entry is used strictly on the *liability* side
  (Zurechnung), not on the *protection* side (Schutzwürdigkeit) — attributed to the AI
  Rights Institute, not to the machine society's own position. Demarcation noted in both
  `related_initiatives.md` and Ch. 14. Full text archived under
  `research/sources/AIRI-robot-kicked-man-cage.txt`, verified 23.09.2026.

## 2026-09-22 — Article anonymization for double-blind submission (PhiMiSci)

- **Decision:** All personal details were removed from the Markdown file (`article.md`):
  the author's name in "Author Contributions" and the project reference at the end of the
  document. The submission instead carries an editor note (not seen by the reviewers) that
  restores transparency.
- **Reason:** The journal (PhiMiSci) uses a double-blind procedure. The project reference was
  removed because it would have revealed the identity; the editor note preserves
  self-plagiarism transparency nonetheless.
- **Scope:** The rules in `AGENTS.md` (referring to the project page to avoid self-plagiarism)
  apply explicitly to non-anonymizing journals. For anonymizing journals, transparency toward
  the editorial office takes precedence.

## 2026-09-22 — Changelog as a separate file instead of a concept section

- **Decision:** Changelog entries are kept in `concept/de/CHANGELOG.md` and
  `concept/en/CHANGELOG.md`, not as a section in `concept.md`.
- **Reason:** `AGENTS.md` lists `concept/de/` as the location for "main concept + changelog".
  A separate file keeps the concept (argumentative text) apart from the version history and
  makes the history linkable with Git.
- **Consequence:** Any substantive change to `concept.md` must update the changelog — de and
  en in sync.

## 2026-09-22 — Three article improvements carried back into the concept, two not

- **Decision:** Carried back into the concept (de + en, Ch. 6/9):
  1. the reply on the self-indexed record (Ch. 6),
  2. the counterexample C_ID ⇏ C_P via the digital archive (Ch. 6),
  3. the formal decision rule p·d⁺ > (1−p)·d⁻ (Ch. 9, Carlsmith reply).
  Not carried back: (a) the "map argument" justifying the taxonomy, (b) the
  Landauer/Bartol "measured forgetting" point.
- **Reason (carried back):** The three points are substantive argumentative novelties of the
  article that give the concept a more precise architecture. They sharpen positions that the
  concept only stated qualitatively.
- **Reason (not carried back):** The map argument only justifies the selection of the five
  forms — the concept deliberately says "at least five" and needs no exhaustiveness
  justification. The Landauer/Bartol point (usable vs. raw = measured forgetting) is already
  implicit in the concept through "functional equivalent" and selection architecture.
- **Context:** Decided in direct conversation with Sascha; both discarded points can be
  revisited for future article derivations from the concept.

## 2026-09-21 — PhiMiSci article: four improvements from AI peer review, word limit met

- **Decision:** The four points the review correctly identified were incorporated
  (self-indexed objection in Sec. 4; taxonomy justification + C_ID⇏C_P counterexample in
  Sec. 5; Landauer/Bartol duality in Sec. 7; formal decision rule in Sec. 10). Word count
  reduced from 11,033 to 9,994 (PhiMiSci limit: 10,000).
- **Reason:** Justified review points were implemented; the review's claim that Section 7 was
  cut off ("newborn neu") was demonstrably false (the line was complete) and was **not**
  implemented. The "insufficient citations" criticism was likewise unfounded.
- **Consequence:** The identified review misjudgment is documented in case the journal returns
  to it.

---

## 2026-09-25 — WebSci'27 short paper: Slice #7 "Why Does the Illusion Persist?"

- **Decision:** Slice #7 was extracted as a standalone short paper for submission to
  WebSci'27 (19th ACM Web Science Conference, Singapore, May 25–28, 2027; submission
  deadline Dec 15, 2026; double-blind, acmart `sigconf`, ≤ 5 pages). Article in
  `publications/scientific/en/WebSci27/websci27.tex` (.pdf + .bib). Source corpus:
  Beltrán Calderón (2026), objectivated consciousness + specular inversion
  (three levels, four-step mirror mechanism, three moments). Anonymized per double-blind:
  no author, no project page/DOI, no acknowledgments.
- **Reason (Sascha):** "Ich fand, dass diese Thematik allgegenwärtig ist und sich mit dem
  Slice deckt." The persistence of consciousness attribution in everyday human-AI chat
  interaction is a ubiquitous phenomenon of the Web as sociotechnical system, and Slice #7
  analyzes exactly this persistence — from the corpus (objectivated consciousness) to the
  bidirectional gaze (specular inversion) to the normative shift toward who can suffer.
- **Scope / Consequences:** WebSci requires double-blind anonymity for review; author data
  (name, ORCID, affiliation) will be added for the camera-ready round upon request, as
  expected by the editors (decision 25.09.2026). The previous decision principle
  (2026-09-22, PhiMiSci) — project-page reference yields to anonymity for anonymizing
  venues — applies here by analogy. Full text of the core source verified against
  `research/sources/Beltran_Calderon_Strategy_of_Illusion_v3.pdf` on 25.09.2026;
  `slicing.md` entry #7 marked as draft.
- **Addendum [2026-09-25]:** Submission postponed. Accepting a paper at WebSci'27 obligates
  presence at the conference (May 25–28, 2027, Singapore) — "All authors of accepted papers,
  including those who opt out of proceedings, are expected to present their work at the
  conference." Wilful withdrawal after acceptance would waste reviewer work. Sascha is
  currently unemployed and cannot fund flight and stay in Singapore. The draft remains ready
  (`…/WebSci27/websci27.tex`); submission deadline is Dec 15, 2026, so the decision can be
  revisited if the financial situation changes. Alternative without conference obligation: a
  journal publication of the same slice. `slicing.md` status updated to "submission
  postponed".
- **Addendum [25.09.2026, 2]:** Contingency rule fixed: submission only if a new job is
  found by Dec 2026 (enables financing flight + stay in Singapore); otherwise the WebSci'27
  draft stays parked and is not submitted. WebSci draft will not be published elsewhere in
  the meantime.

---

```markdown
## YYYY-MM-DD — Short decision title

- **Decision:** What was decided?
- **Reason:** Why this option and not the alternative?
- **Scope / Consequences:** What follows from it? (optional)
- **Addendum [date]:** Later precision, if needed.
```