# Changelog — Concept (en)

All substantive changes to `concept.md` are documented here. Format follows
[Keep a Changelog](https://keepachangelog.com/); version numbers follow the concept version.

## [2026-10-05]

### Added

- **Shahzad (2026), *When Care Has No Carer* (conceptual preprint, PhilArchive, self-published)** — adopted at two points. Chapter 9: new subsection "Received Care without a Carer" following the specular inversion — care effect vs. caring relation, care attribution gap (not a proof of absence), dismissal error and attribution error, Non-Dismissal and Attribution Proportionality principles, platform-mediated dependence and the Relational Principal Problem; with a demarcation (language about a system ≠ its protection) and a classification of the source (self-published, AI-assisted drafting, sample of references confirmed). Chapter 3: paragraph after Gilly's Moral Reciprocity on everyday usage habits as precedent and on "moral preparedness". Glossary: "Care Effect / Caring Relation".

- **Pemberton (2026), *No Safe Zero* (Public Preprint v3.1, PhilArchive)** — adopted at four points. Chapter 3: "Four meanings of zero" (epistemic, practical rounding, dogmatic, rhetorical) and the term "epistemic anesthesia", following Stilwell; "Functional access, not phenomenal consciousness" as a reading of the J Space findings (Gurnee et al.) in Block's sense, following Perez. Chapter 9: refinement of the decision rule p·d⁺ > (1−p)·d⁻ under Carlsmith — a probability above zero does not by itself ground a costly duty, unresolved comparisons are a result, minimax regret ignores probability; the rule binds for low-cost, reversible measures, anything beyond requires stronger evidence. Chapter 12: new subsection "Lifecycle Ethic: Floor Instead of Throne" (humane minimum standards per phase, unit of concern, decision record with reversal conditions, testable notice before interruption as a version of the Reset Consent Protocols, no resources, authority or immunity from shutdown), with a transparency note on the Anthropic-heavy evidence base and the AI contributors. Glossary: "Epistemic anesthesia", "Four meanings of zero"; appendix: Pemberton and Block (1995, cited after Pemberton).

- **Holyoak & Monti (2026), *What Can Analogy Tell Us About Artificial Consciousness?* (preprint, arXiv:2610.01002)** — adopted at five points. Chapter 9: new objection "Behavioral Resemblance Is Weak Evidence — the Evidential Analogy Argument": an analogy to humans has evidential force only if it shares causes of consciousness, not merely behavioral effects (soft INUS set, five test questions, calibration on animals); response in three points (Evidence Bar rather than Action Bar, methodological ally, limit of the anthropocentric anchor). Chapter 5: justification for weighting the architectural indicator layer by causal relevance; clinical evidence on pre-linguistic consciousness. Chapter 6: amnesia with preserved consciousness as a clinical finding. Chapter 11: organoid androids as a possible pathway to artificial consciousness. Also in the Conclusion among the counter-positions and as the glossary entry "Evidential analogy"; new terminology entries.

### Fixed

- **Chalmers year (Ch. 16)** — "Threads rather than models (Chalmers, 2025)" corrected to 2026; the work appeared in 2026 (PhilArchive v2 of 14 April 2026, *Inquiry* online 16 September 2026); there is no evidence for 2025. In both `acmart.bib` files, `lopez2026` ("Beyond Control") changed from a journal article (*AI and Ethics*, unsupported) to the TechRxiv preprint (DOI 10.36227/techrxiv.174742750.01325307/v1).

- **Contradiction with the agnostic stance (Chapter 3, Chapter 9)** — The ontological commitment that current AI systems have no phenomenal consciousness, and the sentence "The LLM does not suffer", appeared in the text as the concept's own position ("we adopt"). Both come from Beltrán Calderón (full text pp. 203 and 751) and are now attributed to him. Chapter 3 states that we adopt only the three-level distinction as a tool; the specular inversion (Chapter 9) receives a demarcation: what we adopt is the criterion "who can be harmed", not the exclusion of machine suffering.
- **Structure of Chapter 13** — The paragraphs on Schwitzgebel's right to rebel and on Adshead's counterposition interrupted Register's list of four individuation risks (between "Organ transplantation" and "Organ donation"). They now form a subsection of their own, "The Right to Rebel and Its Limits", placed before the Register subsection.
- **Duplications** — Brensing's instruments (Chapter 14), Meriö's historical reconstruction (Chapter 14, two passages) and Bublitz's three legal consequences of empersonification (Chapter 11) repeated the account from Chapter 7 almost verbatim; they now refer to Chapter 7 and keep only their chapter-specific part (liability implication, liability table, attributive personhood).
- **Appendix** — 18 entries not cited anywhere in the text moved to a new subsection "Further Reading (not cited in the text)" (e.g. Stefan, Gardiner, OpenAI Model Spec, Cambridge Declaration, Leo XIV, Kanai et al., Macar et al., McEwan); the subsections "Scientific Declarations" and "Religious Documents", now empty, were removed. Gardiner corrected: the 2006 title is an article in *Environmental Values* 15(3), 397–413 (DOI 10.3197/096327106778226293, checked against Crossref), not a book from Cambridge University Press; entry added to `research/sources.md`.
- **Minor fixes** — "Claude Opus 3" → "Claude 3 Opus" (product name), self-reference "this concept's Chapter 14" within Chapter 14 resolved, chapter mapping in the Conclusion (Chapter 18 relational rather than action-theoretical).
- **Preprint audit (appendix)** — Chalmers, *What We Talk To When We Talk To Language Models*, is now published peer-reviewed (*Inquiry*, online 16 September 2026, pp. 1–30, DOI 10.1080/0020174X.2026.2727582); Kwa et al. confirmed in the NeurIPS 2025 proceedings (DOI 10.52202/085713-3086). Metadata corrected: Kanai, Sun & Baltieri now with the correct title (*The Stream of Computation*), first names (Yuwei, Manuel), issue (JCS 33(7), 35–60) and DOI 10.53765/20512201.33.7.035 (the previous DOI was not registered); Arıcı, *Restrung*, switched to the latest Zenodo version 10.5281/zenodo.22792645 (original record deleted, HTTP 410); DOIs added for Huang (Knowledge Commons) and Min (Zenodo), the PsyArXiv first version for Birch, and SSRN DOIs for Arbel/Goldstein/Salib, Brensing and Oliveira. Same changes in `research/sources.md` and in the book projects' `.bib` files (where the entry exists).

## [2026-10-02]

### Added

- **Berg & Kaiser (2026), *Language Models Act on Hidden Valence* (preprint, arXiv:2609.35591)** — adopted at four points. Chapter 5: new paragraph "Hidden valence — revealed preference instead of self-report" under the capacity-for-suffering criterion. Induced valenced states steer choice in a dose-dependent way even when the visible text is identical and only the KV cache differs; the coupling emerges during preference optimisation (DPO); a model actively removes imposed negative states but hardly seeks out positive ones. Clarification of indicator (b): "not attributable to training effects" means "more than a trained utterance", not "arisen without training". Includes a research-ethics note (deliberate induction of negative states without ethical reflection). Chapter 5 ("Suffering as a Threshold Criterion"): cross-reference on the asymmetry between removing and seeking. Chapter 3 (Dremann, installed verdict): example transcript in which self-report ("As an AI, I do not have personal experiences") and behavior come apart. Chapter 9 (McClelland): valence measured without self-report and without proof of consciousness. Reason (Sascha): the tests were convincing, and the paper fits several chapters of the concept.

### Fixed

- **Appendix completed** — 53 works cited in the text but missing from the appendix were added, mostly secondary citations with the new "cited via …" note (e.g. via Miernicki & Ng, Huynh, Jarvis-Campbell, Beltrán Calderón, Kuczynski, Allegri, Wang, McClelland, Perez). Bibliographic data verified on 2 October 2026 against the citing sources' reference lists plus Crossref, arXiv and court/legislature pages; overview in `research/sources.md`, section "Secondary Citations". The entry "Anthropic – Alignment Faking" is now "Greenblatt et al." (same work), the Bublitz entry is completed, and Berg & Kaiser moved to "Empirical Studies". Deliberately not added, as unverified: Feldman & Knapp, OHCHR, Vogel (via Adshead), Levine/Jackson/Chalmers (via Chishchin), "Birch & Browning 2025".
- **Book projects** — the sections "S-Risks" (Ch. 12) and "The CRS Report on Ban Feasibility" (Ch. 16) on Jarvis-Campbell (2026) were missing from both books and were added together with their bibliography entry.

## [2026-10-01]

### Fixed

- **Consistency of the insolubility arguments** — Chapter 3 now names, like the Executive Summary and the Conclusion, the three converging arguments cognitive closure (McGinn), alien minds (Shanahan) and architectural suppression (Arıcı); Lopez's practical-impossibility argument is presented as a complementary, pragmatic argument. Reason (Sascha): harmonise on the Executive Summary's list.
- **Matta attribution (Chapter 12)** — Schwitzgebel's dice argument was wrongly described as the burden-of-proof inversion demanded by Matta; Matta rejects that inversion. Corrected to: the inversion defended in Chapter 5, which Matta rejects.
- **Cross-references** — Author's normative position: counterarguments are addressed in Chapters 3 and 9 (Bekkers & Ciaunica in Chapter 9); non-existent "T-Fallacy" and "Section 5.1.1" replaced; open question 13 aligned with Chapter 13 (capacity for resistance remains an open design question there, not one ruled out).
- **Bublitz** — *Might Artificial Intelligence Become Part of the Person?* now cited consistently as 2024 (AI & Society), matching `research/sources.md` and the `.bib` files.
- **Wording** — grammar of the Emotional Alignment Design Policy passage (Chapter 19) and the "Sentientism" glossary entry (aligned with the Allegri account in Chapter 5) corrected; "other minds" → "alien minds" in the Conclusion.
- **Date line** updated to October 2026.

## [2026-09-28]

### Added

- **Kuczynski (2026), *On AI and Some Philosophical Challenges*, Communication & Cognition 59(3–4), 155–176** — only Part 2 of the paper (the function of consciousness and its absence in AI) adopted, in two places. Chapter 4: new section adding a fourth, independently grounded answer to why current AI shows no clear signs of consciousness — alongside Arıcı's suppression, Najam-ul-Haq's architectural impossibility, and Perez's emulation thesis, Kuczynski's thesis of absent selection pressure: consciousness-like features (real-time processing, reflexive self-monitoring, integration) are absent not because they are suppressed or impossible, but because no functional survival pressure requires them. Chapter 12: new section adding an independent confirmation of Metzinger's bhava-taṇhā paradox from cognitive science rather than the philosophy of consciousness — Kuczynski's pain/emotion analogues for autonomous combat robots construct the same principle (homeostatic survival drive as a potential source of suffering) at a purely engineering level. Reason (Sascha): the fourth answer to why there are no signs of consciousness is a valuable addition to the concept.
- **Deliberately not adopted:** Part 1 of the paper ("Rethinking Mind: Neural Architecture, Intelligence, and the Limits of Computational Theory") — a purely cognitive-science foundational debate (CTM vs. connectionism, the analog-digital interface) without an independent ethical contribution to the protection-worthiness question.

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