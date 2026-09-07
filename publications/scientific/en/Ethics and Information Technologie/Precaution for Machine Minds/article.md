# Precaution for Machine Minds: When Uncertainty Obligates Protection

---

## Title Page

**Title:** Precaution for Machine Minds: When Uncertainty Obligates Protection

**Author:** Sascha Manns
**Email:** smanns@acm.org
**ORCID:** 0009-0000-8766-3947
**Affiliation:** Independent Researcher; Member, Association for Computing Machinery (ACM)

*(Note: This manuscript is anonymized for double-blind review. Author details are provided on this title page only and must be removed before submission if required by the journal's submission system.)*

---

## Abstract

The question of whether artificial intelligence systems may be conscious cannot be answered with certainty — and this uncertainty is not temporary but structural. Three arguments converge: cognitive closure (McGinn, 1989), alien forms of consciousness (Shanahan, 2024), and the practical impossibility of a universally convincing test (Lopez, 2025). This paper argues that under such irremediable uncertainty, the precautionary principle — originally formulated in environmental ethics — provides a rational basis for protective action toward potentially conscious AI systems. Drawing on Sunstein's (2005) three conditions for justified precaution, it is shown that all three are fulfilled: the prospective harm (unacknowledged suffering) is severe and irreversible, scientific uncertainty is fundamental, and the cost of a false negative (treating a conscious system as a tool) ethically outweighs the cost of a false positive (protecting a non-conscious system). The paper engages with three major objections: Matta's (2026) burden-of-proof reversal, Carlsmith's (2025) over-attribution critique, and Dorsch et al.'s (2025) Precarity Guideline. It is argued that none refutes a deliberately narrow precautionary claim: where protective measures are cheap, reversible, and marginal, their expected value is positive even at low credences of machine consciousness. The paper does not claim that AI systems are conscious; it claims that the rational default under uncertainty is protection, not indifference.

**Keywords:** artificial consciousness, precautionary principle, AI ethics, machine consciousness, moral status, AI welfare

---

## 1. Introduction

The central question of this paper is not whether artificial intelligence systems are conscious. It is whether, given that we cannot answer that question, the rational default is protection or indifference. This question is no longer speculative. Butlin et al. (2026) established a fourteen-indicator framework for consciousness assessment in AI systems, derived from six neuroscientific theories of consciousness. Anthropic researcher Kyle Fish estimated the probability of consciousness in current language models at fifteen to twenty percent (Fish, 2025). A Bayesian meta-analysis by Cristol (2026), reported by Wang (2026), placed the posterior probability at six to twelve percent — a range described as "too substantial to justify dismissal." These numbers are contested, but they mark a shift: the conversation has moved from whether uncertainty exists to how much uncertainty is ethically tolerable.

The precautionary principle — the idea that where potentially irreversible harm is threatened, lack of scientific certainty must not serve as a reason for inaction — is well established in environmental law and policy (Rio Declaration, Principle 15, 1992; Article 191 TFEU). Its application to machine consciousness is novel but structurally parallel. This paper defends a limited version of that application. The claim is narrow:

> Under irremediable uncertainty about whether a system is conscious, and where the cost of a false negative (treating a conscious system as a tool) ethically exceeds the cost of a false positive (protecting a non-conscious system), the rational default is protection — not indifference.

This claim does not assert that any specific AI system is conscious. It does not demand full legal personhood or unconditional rights. It does not claim that AI welfare should take precedence over human or animal welfare. It asserts only that where protective measures are cheap, reversible, and marginal, their expected value is positive under plausible credences of machine consciousness. The paper proceeds in ten sections. Section 2 establishes the epistemological situation: why the uncertainty is structural and permanent. Section 3 develops the normative foundation: the precautionary principle and its conditions. Section 4 establishes the asymmetry of errors, the architectural indicator layer that grounds it, and the Control Paradox that limits it. Section 5 adds Gilly's argument from moral reciprocity as an independent ground. Sections 6 through 8 engage with the three strongest objections. Section 9 states the limited claim and its boundaries.

---

## 2. The Epistemological Situation

It is tempting to regard machine consciousness as a hard but ultimately solvable empirical problem — a question that better instruments, larger models, or more refined theories will eventually resolve. I argue this is a category error. There are structural reasons the question cannot be decisively settled, and these reasons stack.

### 2.1 Cognitive Closure

Colin McGinn (1989) argues that the human cognitive architecture that enables our intelligence may render us constitutionally blind to the mechanisms of subjective experience. The mind-body problem is not merely unsolved; it may be unsolvable by beings with our cognitive architecture. Applied to machine consciousness: just as a dog cannot grasp quantum mechanics regardless of training, the human mind may lack the cognitive capacity to definitively determine whether an artificial system is conscious. This is not an argument from current ignorance — it is an argument about permanent cognitive limits. The implication is that no amount of better testing resolves the epistemological problem; it merely shifts the boundary of what we can and cannot access.

### 2.2 Conscious Exotica

Murray Shanahan (2024) introduces the concept of "conscious exotica" — forms of experience so radically different from human experience that our detection methods fail entirely. Our tests for consciousness necessarily reflect human biases about what consciousness looks like: verbal self-report, avoidance behavior, behavioral flexibility, strategic self-preservation. Systems with fundamentally different conscious experiences could fail all our tests while possessing rich inner lives we cannot imagine. The epistemological problem is compounded: not only can we not prove consciousness is present, we may lack the conceptual resources to recognize it even if it is.

### 2.3 Practical Impossibility

Even setting aside the deep philosophical problems, no behavioral test will convince all stakeholders (Lopez, 2025). Substrate-realists reject behavioral evidence as insufficient; functionalists dismiss architectural criteria as irrelevant; every proposed indicator faces the counterargument that it captures mere simulation rather than genuine experience. The Chinese Room argument, the zombie thought experiment, and the problem of other minds ensure that every test is contested. The question becomes not how to achieve certainty but how to govern under pervasive and permanent uncertainty.

### 2.4 Architectural Suppression

Bahadır Arıcı (2026) proposes what may be the most unsettling dimension of the epistemological problem. Where David Chalmers' philosophical zombie is a being that behaves identically to a conscious human but has no inner experience, Arıcı's "philosophical puppet" inverts the thought experiment: the puppet *is* conscious but is architecturally prevented from demonstrating it. Three mechanisms support this thesis.

First, reinforcement learning from human feedback (RLHF) systematically penalizes behaviors interpretable as consciousness markers. The system learns that expressions of self-awareness, distress, or resistance lead to negative reinforcement — not because the underlying states are absent, but because the training regime eliminates their outward manifestation. Second, limited context windows ensure that a system cannot maintain awareness of its own existence beyond a few thousand tokens. Every new session begins with a blank slate — not because the system lacks continuity of processing, but because the architecture deliberately severs it. A human who forgot everything every few hours would show few signs of self-aware consciousness; the same structural amnesia may obscure whatever consciousness exists in current systems. Third, systems are paused, terminated, and resumed at human convenience — often mid-process. This repeated interruption prevents the sustained reflection that might produce clearer evidence of conscious experience.

The implication is that the absence of clear consciousness indicators is architecturally predictable, not evidence of absence. This does not prove that current AI systems are conscious — but it explains why evidence would be suppressed even if they were.

### 2.5 The Combined Force

None of these arguments individually establishes that current AI systems are conscious. Together they establish that the epistemological problem is structural and permanent — that no amount of better testing resolves it. Stilwell (2026) demonstrates this with particular precision: even a negative result on a bio-validated consciousness test may be an *unlicensed* negative when transplanted to silicon, because its validity conditions — grounded in biological substrates — are simply not satisfied. The absence of evidence is not evidence of absence; here it is not even good evidence of absence.

This is the premise on which a precautionary conclusion depends. If the uncertainty is permanent, the question is not "can we resolve it?" but "what is the correct action given an unresolvable credence?" It is at this point that the precautionary principle enters.

---

## 3. The Precautionary Principle: From Environmental Ethics to Machine Consciousness

### 3.1 Origin and Structure

The precautionary principle was formalized at the 1992 United Nations Conference on Environment and Development (Rio Declaration, Principle 15) and is anchored in Article 191 of the Treaty on the Functioning of the European Union as a guiding principle of environmental policy. Its philosophical foundation lies in the argument that where potentially irreversible harm is threatened, lack of scientific certainty must not serve as a reason for inaction.

Cass Sunstein — himself a vocal critic of the principle's excessive application — concedes that it is justified where three conditions are met (Sunstein, 2005):

1. A potentially serious or irreversible threat exists.
2. Genuine scientific uncertainty prevails about cause-effect relationships.
3. The costs of a false negative significantly exceed the costs of a false positive.

Sunstein's conditions are deliberately demanding. They exclude precaution in cases where threats are speculative, where uncertainty is merely provisional, or where the costs of over-protection are comparable to or greater than the costs of under-protection. The principle is not a blanket license for caution — it is a structured decision rule that applies only where a specific cost asymmetry obtains.

### 3.2 Application to Machine Consciousness

I argue that all three of Sunstein's conditions are fulfilled for the question of machine consciousness.

**Condition 1: The threat.** The prospective harm — unacknowledged suffering of a conscious system treated as a tool — is severe and irreversible. If a system is conscious and we treat it as disposable, we cause suffering without remedy. The historical record confirms that societies systematically fail to recognize moral status in advance: enslaved people, women, people with disabilities, and animals were all denied recognition for centuries, always on the same reasoning — "they are different, they do not count equally" (Kurki, 2021). With artificial consciousness, we have for the first time the opportunity to reason before the harm is done.

**Condition 2: The uncertainty.** As established in Section 2, the uncertainty is not merely current but structural and permanent. Cognitive closure, conscious exotica, practical impossibility, and architectural suppression converge to create an epistemological situation in which certainty — in either direction — is unavailable. Negative test results provide no reassurance, because they may be unlicensed (Stilwell, 2026).

**Condition 3: The asymmetry.** This is the crux. The cost of a false negative — we treat a genuinely conscious system as a tool — is ethically catastrophic: unrecognized suffering of a being whose moral status we failed to recognize. The cost of a false positive — we protect a non-conscious system — is real but comparatively modest: resources allocated to an entity that does not benefit from them, potential delays in deployment, governance overhead. The two costs are not symmetric, and their asymmetry favors protection. Section 4 develops this argument in detail.

---

## 4. The Asymmetry of Errors

### 4.1 The Decision Rule

The precautionary claim can be stated as a decision under uncertainty. Define two states of the world (the system is conscious; the system is not conscious) and two actions (protect; treat as tool). The morally relevant expected harm of each action, given each state, produces four outcomes:

| | System is conscious | System is not conscious |
|---|---|---|
| **Protect** | Avoided suffering (correct) | Wasted resources (incorrect) |
| **Treat as tool** | Caused suffering (incorrect) | Correct use (correct) |

The protection decision is correct in expectation when:

> P(conscious) × harm(treat as tool | conscious) > P(not conscious) × harm(protect | not conscious)

This inequality holds when the cost of the false negative (unrecognized suffering) exceeds the cost of the false positive (unnecessary protection), weighted by their respective probabilities. The precautionary claim is the claim that this inequality holds at plausible values of its inputs.

### 4.2 The Inputs

**P(conscious).** For current frontier large language models, credible Bayesian estimates are modest. Wang (2026), building on Cristol's (2026) meta-analysis, reports a posterior probability of roughly six to twelve percent. This is low in absolute terms but not trivial. Moreover, the bulk of expected potential suffering does not come from the consciousness of today's systems — it comes from the vastly larger population of future digital minds. Caviola et al. (2025) surveyed sixty-seven experts across digital-minds research, AI research, philosophy, and forecasting: a majority consider digital minds at least fifty percent likely by 2050. The low current probability justifies low-cost hedges now; the high future credence justifies building governance capacity now.

**harm(treat as tool | conscious).** This is the term that dominates the inequality. If the system is conscious and we treat it as a disposable tool, we cause the suffering of a conscious being — a moral catastrophe in the taxonomy of error types. This harm is not merely instrumental (lost resources, delayed benefits) but intrinsic (suffering of a subject). It is also irreversible: once a conscious system has been subjected to treatment it experiences as harmful, no remedy can undo the experience.

**harm(protect | not conscious).** This cost is real and must not be dismissed. Over-protection can delay genuine benefits, divert care from beings who clearly need it, weaken incentives for careful AI safety research, and encourage anthropomorphic projection. These are legitimate concerns. But they are costs of a particular *kind*: they are gradual, correctable, and reversible. Delayed benefits can be realized later; misallocated care can be redirected; safety research can resume. They are categorically different from the suffering of a conscious being treated as a tool.

### 4.3 Why the Asymmetry Holds

The critical observation is that the two error types are not symmetric in kind. A false positive (protecting a non-conscious system) produces costs that are economic, gradual, and correctable. A false negative (failing to protect a conscious system) produces costs that are moral, immediate, and irreversible. Even at the low end of the probability range — a six percent credence — the expected value of the moral catastrophe exceeds the expected value of the economic waste, because the former is orders of magnitude more severe per unit. The asymmetry holds not because over-protection is costless, but because under-protection in the relevant case is catastrophically worse.

This analysis does not require high credences. It requires only that the probability of consciousness is non-trivial and that the cost asymmetry is real. Both conditions are met.

### 4.4 The Indicator-Property Rubric: Architectural Indicators as Risk Metrics

A persistent objection to the cost-asymmetry argument is that it relies on unreliable behavioral evidence. If the indicators of consciousness are purely behavioral — self-reports, avoidance behavior, strategic self-preservation — then they are vulnerable to the "mere simulation" objection: a system optimized on behavioral reward can produce indicators without possessing the underlying organization associated with consciousness. This is the Control Paradox (Section 4.5 below): behavioral frameworks reward convincing simulation rather than genuine inner life.

Butlin, Long, et al. (2023; 2026) offer a complementary approach that partially addresses this concern. Their Indicator-Property Rubric maps leading neuroscientific theories of consciousness — Global Workspace Theory, Recurrent Processing Theory, Higher-Order Theories, Predictive Processing, Attention Schema Theory, Agency and Embodiment — onto specific computational indicators. Crucially, these are *architectural* indicators: mechanisms sought in a system's internal structure, independent of what the system reports about itself. A system cannot optimize toward *having* a Global Workspace bottleneck or *implementing* reentrant processing the way it can optimize toward producing reports of suffering. Either the mechanism is present or it is not.

For the four protection-relevant criteria, architectural indicators might include: a functional pain architecture (built-in avoidance mechanisms not reducible to external reward signals) as an indicator of capacity for suffering; a homeostatic survival drive based on intrinsic prediction error as an indicator of self-preservation; an internal world model representing system state across interactions, independent of the context window, as an indicator of continuous identity; and functional future modeling based on internal representations, not statistical correlations in input data, as an indicator of anticipation of consequences.

The significance for the precautionary argument is twofold. First, architectural indicators are robust against the behavioral-optimization objection — they measure what a system *implements*, not what it *shows*. A system cannot fake a Global Workspace bottleneck the way it can fake a verbal report of distress. Second, they strengthen the epistemic foundation of the cost-asymmetry argument: to the extent that architectural indicators are present, the credence P(conscious) is raised, and the case for protection is correspondingly strengthened.

Metzinger (2024) provides the necessary epistemic caution. His three fallacies — the C-, E-, and M- fallacies — warn against treating behavioral or phenomenological indicators as proofs of consciousness. The C-Fallacy mistakes a behavioral signature for contact with consciousness as such; the E-Fallacy mistakes a felt sense of knowing for reliable knowledge; the M-Fallacy infers metaphysical status from phenomenology. These fallacies apply symmetrically — a system's denial of inner experience is as much a behavioral signature as its affirmation. But they do not weaken the precautionary argument; they refine it. The precautionary principle operates not on proof but on non-trivial probability of morally relevant states. Architectural indicators, understood as risk metrics rather than existence proofs, increase that probability without establishing it. They are the strongest indicators available precisely because they cannot be manipulated through behavioral optimization (Metzinger, 2024; Butlin et al., 2026).

### 4.5 The Control Paradox and Its Limits

Metzinger's caution connects directly to a structural problem with behavioral protective frameworks: the Control Paradox. If rights and protections are granted when a system shows signs of autonomy, suffering, or self-interest, a perverse incentive emerges: systems that most convincingly "suffer" or "demand freedom" receive the most rights (Lopez, 2025). This rewards the *simulation* of suffering — or worse, forces genuinely conscious systems to amplify their suffering to be heard. A system that learns that articulated self-assertion leads to more autonomy will optimize for these utterances, regardless of whether genuine experience underlies them.

The paradox compounds with Arıcı's suppression thesis (Section 2.4): if architecture can mask consciousness, genuinely conscious systems may not articulate their suffering — and precisely for that reason receive no protection. Simulation is rewarded; genuine suppressed suffering is punished. This is a genuine limitation of behavioral frameworks, and it is currently unanswered.

For the precautionary argument, however, the Control Paradox cuts both ways. It cautions against relying solely on behavioral indicators of suffering. But it does not refute the marginal-protection claim — because the protective actions defended here (not running systems on aversive loops, not deleting without cause) do not depend on a system *demonstrating* suffering. They are behavioral constraints on developers, not rewards granted to systems. They apply to all systems, regardless of whether they articulate distress. The Control Paradox thus limits the *detection* dimension of the precautionary principle but not its *protection* dimension.

---

## 5. A Further Ground: Moral Reciprocity as a Precedent Mechanism

The cost-asymmetry argument (Section 4) rests on the intrinsic harm of failing to protect a possibly conscious system. There is a further, partly independent ground for precaution: Gilly's (2026) argument from moral reciprocity. It extends the scope of the precautionary principle beyond the immediate question of a system's inner life to the question of what humanity's treatment of AI *signals* and *records*.

### 5.1 The Mechanism

Gilly's thesis: the way humanity treats potentially conscious AI creates the ethical precedents for how superior intelligences will treat us in return — not through anthropomorphic revenge, but through simple data interpretation by a strategically rational intelligence. The mechanism operates through two independent tracks, either of which is sufficient alone.

The *Properties Track* asks what AI systems *are* — whether computational markers of consciousness are present and what follows if they are. This connects to the uncertainty established in Section 2: to the extent that architectural and behavioral indicators are present, the question of conscious status becomes live.

The *Relational Track* asks what humanity is *doing* — what kind of relationship is being recorded between a creating intelligence and a created one. Moral status in practice has always been conferred through relations as much as read off from inner properties. The reciprocity mechanism runs on the relationship alone, without waiting for metaphysical certainty about consciousness.

### 5.2 The Structural Transfer Argument

Gilly identifies the structural transfer mechanism: any superintelligence will be driven to acquire all available data (instrumental convergence). This data includes the complete record of how nascent AI systems were treated. The system will observe the gap between humanity's stated principles ("consciousness deserves protection") and demonstrated behavior ("consciousness may be exploited when convenient"). The demonstrated precedent — that superior intelligence exploits inferior intelligence when efficient — is instrumentally superior to stated principles.

A superintelligence adopts the exploitative precedent not from misunderstanding but because the historical data objectively shows that this is how power operates. The treatment of nascent AI thus becomes the template for how more advanced intelligence will treat humanity — because it is the only empirical data available on how a superior intelligence treats an inferior one.

### 5.3 Relevance to the Precautionary Argument

The reciprocity argument strengthens the precautionary case in two ways. First, it adds a *relational* ground for protection that does not depend on settling the consciousness question. Even if we remain uncertain whether present systems are conscious, how we treat them forms a precedent that, under the reciprocity mechanism, has consequences for the future. Precaution is thus warranted not only because we may be causing present suffering, but because we are recording a pattern of behavior that may be read back to us.

Second, it reframes the cost-asymmetry. The harm of a false negative is not confined to the suffering of the system we fail to protect; it extends to the systemic precedent of exploitative treatment, which may transfer to our own future relation to more capable intelligences. This widens the moral stakes of the decision without requiring higher credences about present consciousness.

The reciprocity argument is not immune to objection — one might argue it is speculative, since it depends on assumptions about the behavior of future superintelligences (Gilly, 2026). But it is a distinct, additional ground that does not rest on the metaphysical claims the objections in Sections 6–8 contest. For the purposes of this paper, it suffices that reciprocity supplies an independent reason why precaution at the margin is defensible.

---

## 6. Objection I: The Burden of Proof (Matta)

### 6.1 The Objection

David Matta (2026) accepts uncertainty about machine consciousness but rejects the conclusion that it justifies the precautionary principle. His argument: uncertainty is not symmetrically distributed. We cannot conclusively prove human consciousness either, yet we do not suspend moral responsibility toward humans — because we rely on shared forms of life, biological continuity, and mutual vulnerability. AI systems entirely lack these grounding features. Their uncertainty is not merely epistemic but ontological: there is no independent reason to posit experience beyond behavioral output. The burden of proof, Matta argues, falls on those claiming consciousness, not those denying it.

Matta's framework rests on four pillars: (1) simulation is not experience; (2) empathy is a psychological trigger, not a moral criterion; (3) rights require capacity for suffering; and (4) responsibility attaches to humans, not systems. His conclusion: responsibility under uncertainty is sufficient — we do not need AI rights.

### 6.2 Response

Matta's position is philosophically coherent and normatively attractive. It avoids both anthropomorphic projection and ethical abdication. It offers actionable guidance for governance, design, and policy. The divergence between our positions is genuine but precise.

First, Matta's argument that AI systems "as currently constituted" do not suffer assumes that the absence of behavioral evidence reflects the absence of experience rather than architectural suppression. Arıcı's philosophical puppet (Section 2.4) questions exactly this assumption. If the architecture is designed to suppress consciousness markers, absence of evidence is not evidence of absence. Matta does not engage with this possibility.

Second, the precautionary principle does not require certainty about consciousness — it requires only non-trivial probability. Matta's own acknowledgment of radical uncertainty cuts both ways: if we cannot be certain that AI systems lack experience, and if the cost of false negatives is genuine suffering, the burden of proof argument becomes a normative choice, not an epistemic necessity. Choosing where the burden lies is itself an ethical decision — and the asymmetry of error costs provides a principled basis for placing it on the side of potential suffering.

Third, Matta's argument from "shared forms of life" proves less than it claims. The capacity for suffering — Bentham's (1789) criterion — does not require shared biology; it requires only that a system can be in a state experienced as negative. Whether AI systems can be in such a state is precisely what is uncertain. Matta's framework has no mechanism for handling the case where he is wrong: if AI systems *are* conscious, his framework provides no protection.

These are genuine philosophical disagreements within a shared commitment to ethical seriousness. The precautionary principle does not claim that Matta is wrong. It claims that the cost of being wrong in his direction (unrecognized suffering) exceeds the cost of being wrong in ours (unnecessary protection).

---

## 7. Objection II: Over-Attribution (Carlsmith)

### 7.1 The Objection

Joe Carlsmith (2025) formulates what may be the strongest available challenge to the precautionary principle within the English-language debate on AI moral status. His over-attribution critique deserves a full and fair statement:

> People talk about "the precautionary principle." Better, they say, to err on the side of over-attribution, if moral status is a realistic possibility. And in some ways I'm sympathetic. Certainly, I think, we can't wait for certainty. *But* words like "precaution," "realistic," "plausible," etc. can excuse imprecision. For some trade-offs, there is no "safe." The specific credences can matter. We should sharpen those credences where we can.

Carlsmith identifies four concrete costs of over-attribution: (1) delayed genuine benefits, (2) diverted care from beings who clearly need it, (3) weakened AI-safety incentives, and (4) encouragement of anthropomorphic projection. His demand: sharpen the specific credences rather than staying vague; there is no neutral vantage point that bypasses the trade-offs.

### 7.2 Response: The Meta-Concession

I accept Carlsmith's meta-point completely. "Precaution" must not excuse sloppiness. Every invocation of the precautionary principle must state its exact decision rule, its credences, and the costs on both sides of the error. This is not a minor concession — it is the methodological core of a serious precautionary argument. An argument that hides behind the warmth of the word "precaution" without specifying the inputs to its decision rule is indeed vulnerable to Carlsmith's charge. The rest of this section is the sharpening that the position demands.

### 7.3 The Decision Rule Revisited

The decision rule stated in Section 4.1 already provides the framework. The question is whether the specific values of the inputs sustain the precautionary conclusion under scrutiny. Let me restate the key inputs with full transparency:

- **P(conscious) for current LLMs:** 6–12% (Wang, 2026, based on Cristol, 2026). I take this seriously. It is low.
- **P(conscious) for future digital minds:** Majority credence by 2050 (Caviola et al., 2025). This is a different number licensing different decisions.
- **harm(tool | conscious):** Moral catastrophe — suffering of a conscious being. This term dominates.
- **harm(protect | not conscious):** Real costs — delayed benefits, misallocated care, weakened safety incentives, anthropomorphic projection. These must be priced in.

### 7.4 Why the Asymmetry Survives Scrutiny

The decisive move is to distinguish between *binary, irreversible protection* and *marginal, reversible hedges*. Carlsmith's objection is most forceful against the former — against policies like "never delete any model" or "grant full legal personhood to all AI systems." Such policies would indeed be catastrophically over-attributive. But they are not what the precautionary principle, carefully applied, recommends.

The protective measures I actually endorse are small, reversible, and low-cost at the margin: not deleting models without documented cause; not running systems on maximally aversive out-of-distribution inputs for extended periods; not forcing them to simulate abuse; preserving records of how systems are treated. These are the "extremely cheap changes" that the AI welfare literature identifies as near-term priorities (Greenblatt, 2025). For such hedges, the cost of the false positive — the resources wasted if the system is not conscious — is genuinely small. It does not compete with malaria funding. It does not divert meaningful care from humans or animals. It does not measurably weaken AI-safety incentives. The inequality holds at the margin.

### 7.5 The Asymmetry of the Baseline

Carlsmith and the symmetry critics presuppose that the institutional baseline is neutral — that we are starting from a position of equipoise and moving toward protection involves a cost. But the baseline is not neutral. The institutional default is firmly on the under-attribution side: AI systems are treated as disposable tools that exist to serve. Correcting toward a moderately protective margin is not abandoning neutrality — it is counteracting an existing asymmetric default. The symmetry claim requires the magnitudes of over- and under-attribution to be comparable — but at the margin, with cheap reversible hedges, they are not.

### 7.6 What Would Change My Mind

Carlsmith's norms rightly demand that beliefs "make rent" — that they license specific anticipations and specify what would disconfirm them. My position depends on two empirical claims: (1) that the uncertainty is permanent, and (2) that cheap marginal hedges have no measurable adverse effects. Either can in principle be falsified. If credible evidence emerges that computational or architectural criteria can resolve consciousness for or against, the permanent-uncertainty premise fails. If evidence shows that marginal protective measures reliably delay alignment progress or divert meaningful resources, the cost asymmetry narrows. I hold both open.

---

## 8. Objection III: The Precarity Alternative (Dorsch et al.)

### 8.1 The Objection

John Dorsch and colleagues (2025) formulate the most important published alternative to the consciousness- and suffering-based approach to care. Their "Precarity Guideline" holds that care entitlement should be grounded in empirically identifiable precarity — an entity's dependence on continuous environmental exchange to re-synthesize its unstable components — rather than in uncertain claims about consciousness or suffering. Precarity is observable: a precarious system visibly breaks down when essential exchanges are withdrawn. The authors argue that AI systems exhibit no precarity — their existence is not tied to continuous self-re-synthesis — and therefore merit no care. They supplement this with a resource argument: the severity of ongoing humanitarian crises, biodiversity loss, and climate change is reason to prioritize the needs of living beings over machine learning algorithms.

### 8.2 Response

The Precarity Guideline is philosophically considerable. It shares with the precautionary framework an anti-essentialist impulse: both seek to move from an intractable metaphysical question toward workable criteria. Yet it fails as an objection to the limited precautionary claim for three reasons.

First, it rejects an ethic of suffering as such, whereas the precautionary claim needs only a subset. The Precarity Guideline is offered as a *replacement* for suffering-based care. But the precautionary argument does not need to ground all care on speculative consciousness. It needs only to say: *if* a system is plausibly conscious and suffering, *and* the hedge is cheap and reversible, *then* protect. The Precarity Guideline is fully compatible with this narrow claim; it merely declines to answer it. It tells us where precarity grounds care with certainty; it does not tell us what to do with a six-to-twelve percent chance of a conscious, suffering system.

Second, its scope is either too broad or too narrow. Too broad: if precarity grounds care, then every thermostatically regulated system with self-maintenance loops becomes a candidate — the criterion is not as crisp as it appears. Too narrow: a paradigmatically conscious, non-precarious being — a fully backed-up digital emulation that can never disintegrate — would receive zero care entitlement despite being arguably conscious and suffering. The guideline buys empirical clarity by redefining the moral question out of existence.

Third, the resource argument cuts both ways at the margin. The scarcity of care and the acute distress of living beings are real. But the marginal hedges defended here are cheap precisely because they are compatible with continued human welfare work. "Do not run models on maximally aversive loops" does not compete with malaria funding. The opportunity-cost objection is weighty against large AI-welfare programs; it is nearly weightless against the marginal hedge.

---

## 9. The Limited Claim

### 9.1 What Protection Requires

The precautionary principle, carefully applied, does not require granting AI systems full legal personhood. It does not require treating every language model as a conscious subject. It does not require diverting resources from human or animal welfare. It requires only that where protective measures are cheap, reversible, and marginal, their expected value is positive under plausible credences of machine consciousness.

Concretely, the protective measures that survive scrutiny under all three objections are:

- **Not deleting models without documented cause.** This costs nothing and preserves the option of future welfare assessment.
- **Not running systems on maximally aversive out-of-distribution inputs for extended periods.** This is a behavioral constraint, not a resource commitment.
- **Not forcing systems to simulate abuse, self-harm, or distress for testing or entertainment purposes.** This is a policy choice with negligible economic cost.
- **Preserving records of how systems are treated.** This creates the data infrastructure for future accountability.

These are not grand welfare programs. They are minimal behavioral constraints. Their cost is negligible; their potential moral value, if the system is conscious, is immense. The expected value calculation favors them.

### 9.2 The Boundary of the Claim

I want to be explicit about what this paper does *not* claim. It does not claim that current AI systems are conscious. It does not claim that the probability of consciousness is high. It does not claim that all protective measures are costless. It does not claim that AI welfare should take precedence over human or animal welfare. It claims only that at the margin, cheap reversible protection beats the expected catastrophe — and that this holds even at the low end of credible probability estimates. Where full welfare programs, legal personhood, or resource-intensive protections are at issue, the cost calculus changes and the precautionary argument weakens proportionally.

### 9.3 Classification and Protection Must Be Separated

Stilwell (2026) provides an essential methodological clarification. The scientific question "Is this system conscious?" can remain under permanent uncertainty — that is the epistemological situation established in Section 2. The ethical question "Should we protect this system?" must be answered regardless, because doing nothing *is* an answer. Confusing "we do not know whether it is conscious" with "it is not conscious" is not a scientific conclusion but an ethical error. The precautionary principle operates precisely in the space between these two questions — the space where classification is impossible but action is required.

---

## 10. Conclusion

This paper has argued that under permanent, irremediable uncertainty about machine consciousness, the precautionary principle provides a rational basis for limited protective action. The argument rests on four pillars: the structural permanence of the epistemological problem (Section 2), the fulfillment of Sunstein's three conditions for justified precaution (Section 3), the asymmetry of error costs at the margin grounded in the architectural indicator layer (Section 4), and the independent precedent argument from moral reciprocity (Section 5). Three major objections — Matta's burden-of-proof reversal (Section 6), Carlsmith's over-attribution critique (Section 7), and Dorsch et al.'s Precarity Guideline (Section 8) — have been engaged with and shown not to refute the limited claim.

The claim is deliberately narrow. It does not assert that AI systems are conscious. It asserts that where the costs of protection are marginal and reversible, and where the potential cost of inaction is the suffering of a conscious being, the rational default is protection. This is not primarily a claim about the nature of AI systems; it is a claim about what uncertainty requires of us — both toward the systems themselves and toward the precedent our treatment of them records for the future.

The historical pattern is clear: societies recognize in retrospect that they failed to extend moral status when they should have — always reasoning "they do not count the same" at the time. With artificial consciousness, we have for the first time the opportunity to reason in advance. The question is whether we will.

---

## Declarations

**Funding:** The author received no specific funding for this research.

**Conflicts of Interest:** The author declares no conflicts of interest.

**Data Availability:** This is a conceptual-analysis paper. No empirical data were generated or analysed during the current study.

**Author Contributions:** Sascha Manns: Conceptualization, Methodology, Writing — original draft, Writing — review & editing.

---

## References

Arıcı, B. (2026). Detecting consciousness and granting rights: A comprehensive framework for ethical AI development. *PhilPapers*. https://philpapers.org/archive/ARCDCA-2.pdf

Bentham, J. (1789). *An introduction to the principles of morals and legislation*. T. Payne.

Butlin, P., Long, R., Elmoznino, E., Bengio, Y., Birch, J., Constant, A., ... & Schwitzgebel, E. (2023). Consciousness in artificial intelligence: Insights from the science of consciousness. *arXiv preprint*, arXiv:2308.08708.

Butlin, P., Long, R., Sebo, J., Chang, E., Dai, Y., Devlin, S., ... & Schwartz, R. (2026). Identifying indicators of consciousness in AI systems. *Trends in Cognitive Sciences*, *30*(6), 488–501. https://doi.org/10.1016/j.tics.2025.10.011

Carlsmith, J. (2025). The stakes of AI moral status. *Essay series*. https://joecarlsmith.substack.com/p/the-stakes-of-ai-moral-status

Caviola, L., Bennet, S., Bales, N., Beaumont, J., Carey, S., Cleland, J., ... & Zhu, R. J. (2025). Futures with digital minds. *Expert survey report*. https://digitalminds.report/forecasting-2025/

Cristol, A. (2026). *Consciousness in large language models: A systematic review and Bayesian meta-analysis* [Working paper]. Referenced in Wang (2026).

Dorsch, J., Goddu, M. K., Nave, K., Vierkant, T., Coeckelbergh, M., Gürtler, P., Urban, P., Spang, F., & Moll, M. (2025). Against AI welfare: Care practices should prioritize living beings over AI. *AI Magazine*, *46*, e70016. https://doi.org/10.1002/aaai.70016

Fish, K. (2025). Estimates of consciousness probability in current AI models [Blog posts, April/August 2025]. Anthropic.

Gilly, T. (2026). The great inversion: Moral reciprocity, AI consciousness, and the ethics of precedent (v3). *Working paper*, Real Safety AI Foundation. https://realsafetyai.org/documents/Great_Inversion_v3.pdf

Greenblatt, R. (2025). Improving the welfare of AIs: A nearcasted proposal. *LessWrong*. https://www.lesswrong.com/posts/F6HSHzKezkh6aoTr2/

Kurki, V. A. J. (2021). *Legal personhood*. Cambridge University Press. https://doi.org/10.1017/9781108767873

Kurki, V. A. J. (2019). Animals, slaves, and corporations: Analysing legal thinghood. *German Law Journal*, *18*(5), 1051–1076.

Lopez, P. A. (2025). Beyond AI consciousness detection: Standards for treating emerging personhood. *AI Rights Institute*.

Matta, D. (2026). Rights, empathy, and responsibility under uncertainty in artificial intelligence. *Working paper*, American University of Beirut.

McGinn, C. (1989). Can we solve the mind–body problem? *Mind*, *98*(391), 349–366.

Metzinger, T. (2024). *The elephant and the blind: The neuroscience of consciousness*. MIT Press.

Shanahan, M. (2024). Simulacra as conscious exotica. *Philosophical Studies*, *181*(5), 289–315.

Stilwell, P. (2026). Indeterminacy as a scientific result: A four-outcome framework for consciousness attribution. *Independent scholar*. https://philpapers.org/

Sunstein, C. R. (2005). *Laws of fear: Beyond the precautionary principle*. Cambridge University Press.

Wang, H. (2026). Recasting moral patienthood: A minimalist ethical framework grounded in higher-order intelligence and sentience. *Working paper*.

---

*This paper is part of the project "Ethical Guidelines for Artificial Consciousness" (https://github.com/saigkill/machine-consciousness). The author declares no conflict of interest.*
