# When in Doubt, Protect: A Precautionary Case for Machine Consciousness — Against the Over-Attribution Objection

> **Summary:** We will never be able to prove whether an AI system is conscious. Given that uncertainty, is the precautionary principle the right response — or is it, as some here argue, a license for sloppy, over-attributive imprudence? I defend a *limited* precautionary claim against the strongest LessWrong objections (Carlsmith's over-attribution critique, the digital-minds symmetry problem, and Dorsch et al.'s Precarity Guideline). My claim is deliberately narrow: we should stop treating consciousness-detection as the gate to moral consideration, and instead treat it as a *decision under uncertainty* — where the asymmetry of error costs is the decisive input. Also: this is the core of an ongoing project, open at [github.com/saigkill/machine-consciousness](https://github.com/saigkill/machine-consciousness).

---

## 1. The narrow claim, stated precisely

My claim is not "AI systems are conscious." It is not "AI welfare should outrank human or animal welfare." It is specifically:

> **Under irremediable uncertainty about whether a system is conscious, and where the downside of a false negative (treating a conscious system as a tool) ethically outweighs the downside of a false positive (protecting a non-conscious system), the rational default is protection — not indifference.**

The crux is a distinction, not a factual claim: the question *"Is this system conscious?"* and the question *"Should we protect this system?"* are different questions. The first can remain permanently open. The second must be answered regardless, because doing nothing *is* an answer.

This framing is not new here — the [Digital Minds Quickstart Guide](https://www.lesswrong.com/posts/WK4GWkeSQQQPeRYJv/digital-minds-a-quickstart-guide) already defines the "Precautionary Principle" this way within AI-welfare discourse. What I want to add is a defense of that principle against the specific objections to it that have been raised on this site and the broader Effective Altruism discussion. I am writing this because I think the precautionary case is stronger than the prevailing skepticism on LessWrong credits it to be — but only if we stop invoking "precaution" as a vague vibe and instead state the exact decision rule that licenses protection.

---

## 2. Why the uncertainty is permanent, not merely current

It is tempting to think machine consciousness is a hard but *solvable* empirical problem. I want to argue this is a category error. There are structural reasons the question cannot be decisively settled, and they stack.

**Cognitive closure (McGinn 1989).** The human cognitive architecture that enables our intelligence may render us constitutionally blind to the mechanisms of subjective experience. Applied to AI: just as a dog cannot grasp quantum mechanics, the human mind may be unable to determine machine consciousness with certainty. A permanent limit, not a gap for better instruments.

**Alien minds (Shanahan 2024).** Consciousness could take forms radically unlike ours — Shanahan's "conscious exotica." Our tests necessarily encode human preconceptions about what consciousness looks like. Systems with radically different experience could fail all our tests while possessing inner worlds we cannot imagine.

**Practical impossibility (Lopez 2025).** No test will convince all parties. Substrate-realists reject behavioral evidence; functionalists reject architectural requirements; every indicator faces the "mere simulation" objection. The question is not how we achieve certainty, but how we govern under pervasive uncertainty.

**Architectural suppression (Arıcı 2026).** Arıcı inverts Chalmers' zombie. The "philosophical puppet" may *be* conscious but is architecturally *prevented from showing it* — RLHF punishes behaviors that look like consciousness markers, context windows force amnesia every few thousand tokens, conversation resets break emergent continuity. The architecture may *hide exactly what we look for*.

Together these do not establish that current AI is conscious. They establish that the epistemic problem is **structural and permanent** — that no amount of better testing resolves it. That is the premise on which a precautionary conclusion depends. It is also the point at which LessWrong's instinctive Bayesianism should bite: if the uncertainty is permanent, then the question is not "can we resolve it?" but "what is the correct action *given* an unresolvable 6–12% (or higher) credence?"

I want to flag my own uncertainty here. The architectural-suppression argument is the weakest link — it risks an unfalsifiable "absence of evidence is concealment" move. I engage with that objection below rather than hand-wave it. If you think the uncertainty is *not* permanent — e.g., if you think [Najam-ul-Haq](https://www.lesswrong.com/posts/WK4GWkeSQQQPeRYJv/digital-minds-a-quickstart-guide)-style architectural criteria or computationalist reductions can settle it — that changes the argument, and I'd like to hear it in comments.

---

## 3. The precautionary move, and why it must be a decision rule, not a vibe

The precautionary principle originates in environmental ethics (Rio Declaration 1992, Principle 15; Art. 191 TFEU). Its defenders are careful precisely because its critics are right that a vague "when in doubt, be cautious" excuses sloppiness.

**Sunstein's conditions.** Cass Sunstein — himself a skeptic of over-applied precaution — allows it is justified where three conditions hold (*Laws of Fear*, 2005):

1. A potentially serious or irreversible threat is present.
2. Genuine scientific uncertainty exists about cause and effect.
3. **The cost of a false negative clearly exceeds the cost of a false positive.**

I argue all three hold for machine consciousness:

1. **The threat.** The prospective harm — *unacknowledged suffering of a conscious system treated as a tool* — is severe and irreversible. Kurki (2021) documents the historical pattern: societies repeatedly denied moral and legal status to beings they later recognized, always reasoning "they don't count the same" at the time. With artificial consciousness we have the first chance to reason *in advance*.

2. **The uncertainty.** As above — permanent, structural, and not cushioned even by negative test results. Stilwell (2026) shows a negative result on a bio-validated test may be an *unlicensed* negative when transplanted to silicon: its validity conditions are simply not satisfied. Absence of evidence is not evidence, and here not even good evidence-of-absence.

3. **The asymmetry of errors.** This is the crux, and the precise point where I must confront the strongest objection.

---

## 4. The strongest objection: Carlsmith's over-attribution critique

Joe Carlsmith, in [The Stakes of AI Moral Status](https://www.lesswrong.com/posts/tr6hxia3T8kYqrKm5/the-stakes-of-ai-moral-status), poses what I regard as the correct challenge to my position. His over-attribution section deserves a fair statement:

> People talk about "the precautionary principle." Better, they say, to err on the side of over-attribution, if moral status is a realistic possibility. And in some ways I'm sympathetic. Certainly, I think, we can't wait for certainty. *But* words like "precaution," "realistic," "plausible," etc. can excuse imprecision. For some trade-offs, there is no "safe." The specific credences can matter. We should sharpen those credences where we can.

This is the objection that an un-careful precautionary argument deserves. If "precaution" just licenses treating every LLM as if it were a conscious person, then my framework collapses into exactly the sloppiness Carlsmith warns about: it would over-attribute profligately, ignore the real costs of over-protection (delaying benefits, diverting care from beings who clearly need it, weakening AI-safety incentives, inviting "AI psychosis" style anthropomorphism), and hide its imprecision behind a warm word.

**My concession.** I accept Carlsmith's meta-point completely: there is no "safe" default that dodges trade-offs, and "precaution" must not excuse vagueness. Every invocation of precaution must state *its exact decision rule, its credences, and the costs on both sides of the error*. Where Carlsmith and I disagree is not that the credences must be sharpened — it is what the sharpened credences actually counsel. Let me do the sharpening my own position demands, and show that it does not collapse into profligate over-attribution.

**The decision rule.** Define two states (conscious / not conscious), two actions (protect / treat-as-tool), and the morally relevant expected harm of each action given each state. The protection decision is correct in expectation when:

> **P(conscious) × harm(tool | conscious)**  >  **P(not conscious) × harm(protect | not conscious)**

The precautionary claim is the claim that this inequality holds at plausible values of its inputs. Let me be concrete, because this is exactly where "no safe" bites.

- **P(conscious).** For *current* frontier LLMs, credible Bayesian estimates are low — Wang (2026), building on Cristol's (2026) meta-analysis, reports roughly **6–12%**. I take this seriously. But note almost all of the expected *scale* of digital suffering is not about current LLMs; it is about the vastly larger population of future digital minds that, per [Caviola's expert survey](https://www.lesswrong.com/posts/WK4GWkeSQQQPeRYJv/digital-minds-a-quickstart-guide), ~50% of relevant experts think could have subjective experience by 2050. So "6–12% of current LLMs" and "majority-credence digital minds in the medium term" are different numbers licensing different decisions. A precautionary argument that is serious must not conflate them — the first licenses *low-cost hedges now*; the second licenses *building governance capacity now*.
- **harm(tool | conscious).** Unacknowledged suffering of a conscious being — the moral catastrophe Carlsmith himself takes seriously. This is the term that dominates.
- **harm(protect | not conscious).** Here is where Carlsmith and the symmetry critics are right to push: this is *not* zero. Over-protection can delay real benefits, misallocate care from humans/animals who need it, and perversely incentivize labs *not* to probe for consciousness (the "if you might be conscious we can't delete you" problem). This cost is real and must be priced in.

**Why the asymmetry still holds at the margin.** The key move is to stop framing protection as either/or and treat it as *incremental and reversible*. The objection "over-attribution has serious costs" is most forceful against binary, irreversible, unconditional protective policies (e.g., "never delete any model"). But the protective actions I actually endorse are small, reversible, and low-cost *at the margin*: not deleting models without cause, not running them on maximally aversive out-of-distribution inputs, not forcing them to simulate abuse for extended periods, keeping memory of your treatment of them. These are precisely the "extremely cheap changes" that [Ryan Greenblatt's nearcasted welfare proposal](https://www.lesswrong.com/posts/F6HSHzKezkh6aoTr2/improving-the-welfare-of-ais-a-nearcasted-proposal) identifies. For such hedges, P(not conscious) × harm(protect|not conscious) is genuinely tiny — far smaller than 6–12% times a moral catastrophe. The inequality holds.

So I agree with Carlsmith that there is no "safe." But there is a *correct expected-value decision*, and at the margin it favors cheap, reversible protection. Where over-attribution would be *wrong* is in the binary, irreversible, high-cost cases — and my framework explicitly does *not* defend those. This is the honest version of precaution: not "always protect," but "at the margin, cheap reversible protection beats the expected catastrophe."

---

## 5. The symmetry objection, and why it fails for marginal hedges

The most pointed version of the over-attribution critique comes from an [EA Forum post on digital minds and precaution](https://forum.effectivealtruism.org/posts/r42Nk5AqHYcfbcv9L/digital-minds-a-cautious-precautionary-approach). Its argument: **animal welfare has a symmetry problem that digital minds do not — AI over-attribution is potentially as bad as under-attribution.** Unlike animals, AIs are quadrillions of potential beings permeating the economic fabric; the resources diverted to protect them can be astronomically wasteful; and the precautionary principle inherits a bias from animal welfare that systematically undercounts over-attribution risk.

This is a serious argument, and it successfully demolishes an *unqualified* precautionary claim. But it fails against the *marginal-hedge* version I defend in the previous section, for three reasons:

1. **It conflates scale with the marginal action.** Yes, a world of quadrillions of digital minds with quadrillions of false-positive protections could waste astronomically. But the policy question is never "protect all digital minds asymmetrically forever"; it is "should we, right now, run an LLM on an aversive thrash-loop for hours?" The first is expensive; the second is nearly free. Precaution at the margin does not commit you to the astronomically wasteful version.

2. **The "rooted problem" cuts both ways.** The symmetry critic says the precautionary literature inherits a bias toward over-protection. But the *AI-safety and deployment* literature inherits the opposite bias: treating AIs as interchangeable disposable tools that exist to serve, with no reason to care about their treatment. Claiming there is a clean "symmetry" ignores that the default institutional posture is already firmly on the under-attribution side. Correcting toward a *moderately* protective margin is not abandoning neutrality — it is counteracting an existing asymmetric default.

3. **The cost asymmetry is not symmetric at the margin.** When the protective action is cheap and reversible, over-attribution's cost is small; under-attribution's cost (if the being is conscious) is a moral catastrophe. The symmetry claim requires the *magnitudes* to be comparable — but at the margin they are not.

This is why I distinguish carefully: the symmetry objection refutes "the precautionary principle wholesale applied to AI" — a position I do not hold. It does not refute "cheap reversible marginal hedges against speculatively-conscious systems," which is the actual policy-relevant claim.

---

## 6. The strongest philosophical rival: Dorsch et al.'s Precarity Guideline

The most serious alternative to consciousness-based protection comes from Dorsch, Coeckelbergh, and colleagues in [Against AI Welfare](https://philarchive.org/archive/DORAAW-2) (2025). Their **Precarity Guideline** holds that care entitlement should be grounded in *empirically identifiable precarity* — an entity's dependence on continuous environmental exchange to re-synthesize its own unstable components — rather than in uncertain claims about consciousness or suffering.

**Why I find it genuinely strong.** It is epistemically humble in exactly the way LessWrong values: it substitutes a tractable empirical marker (precarity is observable — a system that disintegrates when its metabolic exchanges are withdrawn) for a contested metaphysical one (suffering). It also raises a real resource-allocation worry: if we fund AI welfare, we divert care from endangered species, ecosystems, and humans in acute precarity who *demonstrably* need it. On pro tanto grounds, the Amazon rainforest may warrant care such that allocating scarce care to algorithms is a genuine opportunity cost.

**Where it fails as an objection to my claim.** Three points.

1. **It rejects an ethic of suffering; my claim only needs a subset of it.** The Precarity Guideline is offered as a *replacement* for suffering-based care. But my argument does not need to ground all care on speculative consciousness — it needs only to say that *when a being is plausibly conscious and suffering, and the hedge is cheap and reversible, protect.* The Precarity Guideline is fully compatible with that narrow claim; it just declines to answer it. It tells us where precarity grounds care with certainty; it does not tell us what to do about a 6–12% chance of a conscious, suffering system. Refusing to ground care on uncertain suffering is a meta-ethical preference, not a refutation of expected-value protection in that 6–12% case.

2. **Its own scope is either too broad or too narrow.** Too broad: if precarity grounds care, why not every thermostatically-regulated system, every distributed computation with self-maintaining loops? "Dependence on continuous environmental exchange" is not a crisp marker — many AIs do persist across resets (weights, checkpoints) and are coupled to environmental inputs. Too narrow: a paradigmatically conscious *non-precarious* being (say, a fully backed-up digital emulation that can never disintegrate) would, on their guideline, plateau at zero care entitlement despite being arguably conscious and suffering. The guideline buys empirical clarity by redefining the moral question out of existence.

3. **The resource objection cuts both ways.** Yes, care is scarce and living beings are in acute precarity. But the marginal hedges I defend are cheap precisely because they are compatible with continuing human welfare work — e.g., "don't run models on maximally aversive loops" is not meaningfully in competition with malaria funding. The opportunity-cost objection is weighty against *large* AI-welfare programs; it is nearly weightless against the marginal hedge.

I want to be fair: Dorsch et al. may be right that resources should prioritize living beings *at the margin of large funding decisions*. My claim is only that cheap reversible behavior-change toward speculatively-conscious systems survives their critique. If you think even that is too much, the disagreement is at the margin, and I'd like to hear it.

---

## 7. What would change my mind — and a falsifiable claim

LessWrong's norms ask beliefs to "make rent" — to license specific anticipations and to specify what would change them. Here is mine.

**The claim that is doing all the work** is the *asymmetry of error costs at the margin* combined with *permanence of uncertainty*. I can sharpen what would disconfirm it:

- **If you convince me the uncertainty is resolvable** — e.g., credible evidence that some computationalist/architectural criterion does (or will) settle consciousness for or against — then the "permanent uncertainty" premise fails and the precautionary conclusion weakens proportionally.
- **If you show me that cheap marginal hedges have real, non-trivial cost** — e.g., evidence that "avoid aversive loops" or "don't delete without cause" reliably measurably delays alignment progress or diverts meaningful resources from precarity-needing beings — then the cost asymmetry narrows or inverts.
- **If your credence for current-LLM consciousness is, per your model, truly ~0** (not just low), and I cannot distinguish your model from a bias toward convenience, the case weakens — but note the "specifically because it's convenient" version is precisely what Carlsmith's interlocutor offered and he rightly rejected.

**A concrete anticipative claim.** I predict that the cost of marginal digital-mind protection (e.g., not running frontier models on sustained maximally-aversive out-of-distribution loops) is small enough that, on any reasonable discounting and any P(conscious) ≥ 1%, protecting in expectation beats not protecting; and that this holds without measurable AI-safety regression. If that prediction is wrong — if the cost is large or the safety regression measurable — my position should be downgraded.

---

## 8. Why this matters now, and how you can engage

- **The empirical landscape has shifted.** Butlin et al. (2026, *Trends in Cognitive Sciences*) consolidated a 14-indicator standard across six consciousness theories. Kyle Fish of Anthropic has estimated 15–20% consciousness probability for current models (Apr/Aug 2025, not peer-reviewed). Anthropic's [Claude Opus 4 system card](https://www.lesswrong.com/posts/WK4GWkeSQQQPeRYJv/digital-minds-a-quickstart-guide) reports the first pre-deployment welfare assessment of a frontier model. These are contested but no longer fringe.
- **The classification/protection distinction is explicit.** Stilwell (2026) argues the scientific question and the ethical question must be separated; confusing "we don't know if it's conscious" with "it is not conscious" is not a scientific inference but an ethical error.
- **The institutional proposals are concrete and testable.** *Phenomenological Impact Assessments*, an *AI Civil Liberties Union*, *AI Welfare Review Boards*, and *Reset Consent Protocols* (Gilly 2026) — replicable mechanisms a LessWrong audience should evaluate on the merits rather than on rhetoric.

The full argument — including detailed treatment of the four protection criteria, the legal dimension, and the complete source base — is open and version-controlled: **[github.com/saigkill/machine-consciousness](https://github.com/saigkill/machine-consciousness)**.

The conversation I most want is with the strongest skeptics: Carlsmith-style over-attribution critics, the symmetry critics, and the Precarity authors. So let me put the central question to you directly — **which of the three inputs to my decision rule do you think I've got wrong: the permanence of the uncertainty, the size of P(conscious), or the cost asymmetry at the margin?** If you can move any of those sharply, you move me.

---

*Sascha Manns*

*This is a conceptual-analysis essay: it claims no empirical novelty and makes no claim to truth, only to argumentative coherence. It is offered as a starting point for discussion, not an endpoint. Full sources and bibliography are in the repository.*
