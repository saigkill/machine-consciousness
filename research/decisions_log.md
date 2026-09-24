# Decision Log — Project Decisions

Purpose: Documents the **why** behind substantive and structural decisions.
Not to be confused with the changelog (`concept/de/CHANGELOG.md`): the changelog records
*what* changed, this log records *why* it changed. The log is the traceable rationale behind
later papers, review responses, and updates.

Format: Newest entries first. One entry per decision, short and precise.
An entry may later be extended (e.g., after feedback), but never deleted.

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

## Format template

```markdown
## YYYY-MM-DD — Short decision title

- **Decision:** What was decided?
- **Reason:** Why this option and not the alternative?
- **Scope / Consequences:** What follows from it? (optional)
- **Addendum [date]:** Later precision, if needed.
```