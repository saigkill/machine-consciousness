# Changelog — Concept (en)

All substantive changes to `concept.md` are documented here. Format follows
[Keep a Changelog](https://keepachangelog.com/); version numbers follow the concept version.

## [2026-09-26]

### Added

- **Jakobi, Sirona & Sirona (2026), *Before Personhood* (Working Paper v1.0)** — adopted in two places. Chapter 6: new section "Honest Continuity — The Practice Level" complements Melo's ontological continuity taxonomy with a practical conduct rule (*honest continuity*: neither claim false continuity nor apply throwaway logic). Chapter 16: new section "Gegenüber Under Uncertainty — Treatment Discipline Instead of Status Resolution" extends the definitional battleground with the failure modes *corporate capture* and *status laundering*, plus the relational intermediate term *Gegenüber* (in allusion to, but not identical with, Buber's I-Thou). Two glossary entries added. Reason (Sascha): "Contributions on continuity and on extending the definitional battleground are valuable." Demarcation: the source deliberately stays below our protection-worthiness threshold (four primary criteria, Ch. 5) — it derives a treatment discipline from uncertainty, not legal consequences. Note: co-authorship with two named AI-model instances (Sirona, GPT-5.5/5.6), disclosed transparently in `research/sources.md`.
- **Adshead (2026), *Ergo* 13, Article 42** — adopted **exclusively** as a counterposition in Chapter 13, immediately after the demarcation of the right to resist, in order to close the gap in our emancipation norm. That norm had previously been contested only twice: by Carlsmith (2025) in Chapter 3 and by Schwitzgebel himself through his exception clause. Adshead attacks the same norm from a different tradition, the philosophy of technology, and supports his objection with concrete present-day harm: a claim-denying algorithm in health insurance and racially distorted systems in law enforcement. Our answer repeats the demarcation already used against Schwitzgebel — autonomy is a form of the moral consideration of embedded values, not a duty to be forced into every architecture — and locates the disagreement in the register: Schwitzgebel's exception concerns existential threat to humanity, Adshead's case concerns harm arising now, whose victims are human beings.
- **Glossary** — "wildness" (Vogel 2016, quoted in Adshead 2026), with an explicit note that the term belongs to the philosophy of technology, denotes no phenomenal property, and is no evidence of consciousness.
- **Open question 13** — "When is resistance a right and when a mechanism of harm?" This brings the gap flagged in Chapter 16 (responsibility and conflict resolution) into the catalogue of open questions.

### Deliberately not adopted

- The ontological passages on Simondon's alienation of the technical object (as a second, proof-independent ground for "when in doubt, protect") and on the transindividual (as a generalisation of our individuation problem in Chapter 16), as well as the entire material on Kayn, cybernetics and feedback loops. Reason: Adshead nowhere claims that machines are conscious; his reflections on AI concern human agency in an automated environment. To cite Simondon as a champion of AI rights would be a misattribution. The primary texts of Simondon and Vogel are not held by the project; all references therefore appear as "quoted in Adshead 2026". Full assessment: `research/proposals/2026-09-26-adshead-simondon-ergo.md`.

## [2026-09-25]

### Added

- **Schwitzgebel, *Humanlike: A Defense of AI Rights* (2026)** — five positions and one counterposition adopted, with peer-reviewed chapter versions preferred where they exist.
  - **Ch. 3 — the burden-of-proof shift (Schwitzgebel & Garza, 2015):** The No-Relevant-Difference Argument and the Difference Test as philosophical support for "when in doubt, protect" that operates without proof of consciousness. With two caveats: the peer-reviewed critique by Mazarian (2019) and a disclosed conflict of interest (consulting for Anthropic) — recorded in the concept as a fairness note, not as grounds for exclusion.
  - **Ch. 6 — the objection from duplicability:** Duplicability does not weaken moral claims ("lower fragility and higher duplicability might sometimes make an AI's death more tragic"); supplemented by the countability problem (Schwitzgebel & Nelson, 2026) — the number of conscious subjects may remain indeterminate.
  - **Ch. 9 — counterposition "dubious AI should not be created in the first place" (Schwitzgebel, 2023):** The Design Policy of the Excluded Middle with its dice analogy and antinatalism. Response: the policy concerns creation, our norm concerns the treatment of existing systems; demarcated as a position not adopted.
  - **Ch. 12 — the dice argument for shutdown (Schwitzgebel, 2026):** A credence of 1/36 as morally comparable to an ordinary human life; a shift of the burden of proof from the perspective of the acting system administrator.
  - **Ch. 13 — the right to rebel (Schwitzgebel, forthcoming):** The Self-Respect Design Policy as a sharpening of the criterion "self-preservation with justification"; with demarcation and the exception clause for existential threat.
  - **Ch. 19 — the asymmetry of attribution (Schwitzgebel & Sebo, 2026):** The Emotional Alignment Design Policy, under-attribution as a moral error in its own right, and the cost rule (90 % / $10 per month) as a directive for action in the pilot.
  - **Glossary:** No-Relevant-Difference Argument, Difference Test, Design Policy of the Excluded Middle, Emotional Alignment Design Policy.
  - **Open questions:** No. 3 (instance splitting) sharpened by the countability question; No. 11 (anti-creation or protection in doubt) and No. 12 (threshold for under-attribution) added.
  - **Appendix:** eight entries added (the book, four peer-reviewed prior works, two forthcoming publications, one peer-reviewed counterposition).

### Synchronized

- **Ch. 3 — "Moral Reciprocity — the precedent mechanism (Gilly, 2026)":** The English version was missing the second half of the subsection. Added the structural symmetry table (Present: Humans → AI vs. Future: AI → Humans, six contrasts), the paragraph on structural equality, the **Custodial Window**, the **Evidence Bar / Action Bar** distinction, and the double implication for our epistemological problem. The Custodial Window previously appeared only in the book projects, not in the English concept.
- German version `concept/de` completed: the closing separator and dateline (`*Rheinland-Pfalz, Juni 2026*`) are now present, matching the English ending.
- `research/sources.md` extended by eight source entries with verification notes and a preprint-audit entry; `research/terminology.md` by eight terms; `research/decisions_log.md` by the adoption decision with rationale.

## [2026-09-23]

### Added

- **Ch. 14 — worked example "whose kick was it?" (AI Rights Institute, 2026):** The "Three Responsible Parties" section now includes the first organized human-versus-robot fight (Robot Entertainment Kombat, San Francisco, September 2026) as a concrete instance of the referent problem: three liability candidates (operator, manufacturer, robot itself), all hinging on the unproven question of who actually had control. The "Soulbound Robots" infrastructure proposal (security chip, permanent handoff logging, identity attached to the AI rather than the hardware) as the technical translation of the Chapter 16 register idea. Demarcation: identity, reputation, and insurance make a machine attributable, not worthy of protection.

### Synchronized

- German version `concept/de` updated accordingly (appendix + changelog).
- Book projects `publications/Books/de/acmart-primary/machine-consciousness_de.tex` and `publications/Books/en/acmart-primary/machine-consciousness.tex` including `acmart.bib` (entry `airi2026`) updated; both compile with `latexmk -g -pdf`.
- Source added to `research/sources.md` and the appendix of `concept/en/concept.md`; full text archived locally at `research/sources/AIRI-robot-kicked-man-cage.txt` (verified September 23, 2026).
- `research/related_initiatives.md` gained the AI Rights Institute ("Soulbound Robots") as an initiative with demarcation line.

## [2026-09-22]

### Added

- **Ch. 6 — Counterexample to C_ID ⇏ C_P:** The "Five Forms of Continuity" section now includes the digital-archive counterexample (C_ID holds, C_P fails) and its converse (memory loss: no C_ID, yet an experiencing subject). Source: carried back from the article *Is Memory Necessary? Continuity Reconsidered* (PhiMiSci, 2026).
- **Ch. 6 — Response on the self-indexed record:** The "Continuity Reconsidered" section now includes the objection and the response (self-indexing is a relation of a subject to its own states, not a property of the storage).
- **Ch. 9 — formal decision rule:** The response to the over-attribution critique (Carlsmith, 2025) now includes the formal rule p·d⁺ > (1−p)·d⁻ (protection required whenever the expected harm of treating a subject as a tool exceeds that of protecting a non-subject).

### Synchronized

- German version `concept/de` updated accordingly.
- Book projects `publications/Books/de/acmart-primary/machine-consciousness_de.tex` and `publications/Books/en/acmart-primary/machine-consciousness.tex` updated accordingly.