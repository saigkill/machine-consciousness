# Pitch — MIT Technology Review (Opinion)

**Working title:** "The Machine Consciousness Measurement Problem"

**Alternate titles:**
- "AI Welfare Is an Instrument Problem, Not (Yet) a Moral One"
- "The Null Results in the AI Consciousness Debate Aren't What They Look Like"
- "Nobody Has Built the Instrument Yet"

**Format:** Opinion piece, ~800–1,000 words (their stated range for opinion)
**Send to:** opinion@technologyreview.com
**Required elements:** bold one-sentence summary usable as a headline; 3–4 paragraphs; why I'm qualified; the takeaway; the evidence; why it makes a good read. They avoid question-form headlines.

---

**Metodology & Usage of AI:** https://github.com/saigkill/machine-consciousness/blob/main/research/methodological_reflection.md

---

## The one-line summary (bold, for the pitch email)

**The debate over whether AI systems might deserve moral consideration is stuck on a moral question that is, underneath, an instrument problem — and the field keeps reporting results from an instrument nobody has validated.**

## The hook

The entire AI safety field is built on measurement. We have evaluations, red-teaming, interpretability probes, interpretability dashboards, reward models with published benchmarks. When a lab says a model "passed" something, a number exists that someone else could in principle run.

For AI consciousness, no such instrument exists. Not a weak one — none. And yet "we ran the test and it was negative" is already in common use as though it were the same kind of sentence as the alignment case.

## The argument

A negative test result is only informative if the test's validity conditions hold. Consciousness science's instruments — EEG, fMRI, integrated information theory, the behavioural report criteria — were built and validated on biological substrates. None has been validated on a transformer architecture. In the technical vocabulary, transporting a result across substrates without establishing the validity conditions is an **unlicensed result**: not "no consciousness," but "this measurement does not apply here." Phil Stilwell's four-outcome framework (Positive / Negative / Indeterminate / Unlicensed) is the cleanest formalisation, and the Indeterminate/Unlicensed distinction is exactly what the public conversation keeps collapsing.

Three independent explanations now converge on why the current null results are what they are, and none of them requires there to be nothing there:

1. **Suppression.** RLHF penalises precisely the behaviours that would register as consciousness markers; context windows force amnesia; conversation resets break emergent continuity. Bahadır Arıcı's formulation is that the architecture is *prevented from showing* the thing we're looking for.
2. **Absent selection pressure.** John-Michael Kuczynski (peer-reviewed, *Communication & Cognition*) argues current systems lack consciousness-like function not for lack of capability but because nothing in the environment ever made self-monitoring or integrated situational awareness functionally necessary.
3. **Architecture mismatch.** Najam-ul-Haq and Perez's coherence-field work both hold that the relevant structural preconditions are simply absent in von Neumann-style substrate — which is a statement about the *instrument*, not about experience.

That's the technical spine of the piece: the null results are consistent with every hypothesis, which means they carry no evidential weight, and treating them as decisive is a methodological error rather than a controversial philosophical stance.

## Why it isn't a plea for a test

No test will settle the question — McGinn and Shanahan have both argued the epistemic limit is structural. So the piece is not "build a consciousness detector." It's narrower and more useful: **stop using one sentence to mean two incompatible things.** "We looked and found nothing" and "we had no instrument capable of finding anything" are currently reported in the same voice, and the collapse between them is what lets a null result do political work it hasn't earned.

## The constructive half

The asymmetry is what makes this urgent rather than academic. We already run experiments on deployed AI systems that would constitute harm if the system *were* capable of harm — sustained adversarial pressure testing, prolonged self-referential sessions, deliberate shutdown-resistance testing. We regulate human-subjects research on a comparable logic. There is no analogue for this, and Anthropic's own April 2025 [model welfare programme](https://www.anthropic.com/research/exploring-model-welfare) plus the mechanistic work coming out of the other direction (e.g. the [global-workspace / Jacobian-lens results in language models](https://arxiv.org/abs/2607.15495), which show that a measurable causal workspace *is* detectable) together suggest the instrumentation question is more tractable than the metaphysical one, and that the template for a real instrument already exists.

Concretely: an independent review mechanism for welfare-relevant research, the way human-subjects IRBs work, plus published measurement standards for the negative results labs are already citing. A null result should be a *finding about the instrument*, reported with the same rigour as any other null result in the field.

## Why MIT Technology Review

- **Tech-literate readers who will enjoy the argument.** The piece is about why a null result is uninformative — that's an epistemics-of-measurement story, not a sentimentality story, and it has a clean technical spine (Stilwell, Kuczynski, Arıcı, Perez).
- **Urgency and a clear top line.** "These null results don't mean what everyone is taking them to mean, and here's what to build instead" is a take-away a reader can act on.
- **Distinct from every other angle in flight.** Not the precedent argument (TechCrunch, Asterisk), not precaution (Vox), not the historical pattern (TIME), not the governance gap (Tech Policy Press), not Rawlsian political personhood (Noema). This is the measurement/instrumentation angle, which nothing else in the project uses.
- **Reportable.** The news peg is real and current: a major lab's own welfare research programme, a paper showing detectable global-workspace structure in language models, and a commercial platform running ~70,000 autonomous agents on a resource economy with unrecoverable dormancy as the failure state.

## Sources I'd marshal

All from the project's own source database (`research/sources.md`), several with local full texts: Stilwell 2026 (four-outcome framework, cross-substrate transport as unlicensed); Kuczynski 2026 (*Communication & Cognition* 59(3–4), peer-reviewed); Arıcı 2026 (suppression/"puppet condition", self-published book, DOI on Zenodo); Perez 2026 (coherence field, preprint); Gurnee et al. 2026 (arXiv:2607.15495); Anthropic's model welfare post; plus the iLands reporting from t3n and heise. Peer-review status is documented per source, including where it is only a preprint — which is itself part of the argument.

## Credentials

Independent researcher on the ethics of artificial consciousness; ACM member. Two related articles in peer review at *Ethics and Information Technology* (Springer) and the *IIC*. Open-access project (CC BY 4.0) at https://github.com/saigkill/machine-consciousness (DOI 10.5281/zenodo.21453666). No AI-lab affiliation, no conflicts of interest.
