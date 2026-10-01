# Pitch — Vox, Future Perfect

**Working title:** "AI Companies Are Testing Whether Their Models Can Suffer. Nobody Has a Plan for What Happens If the Answer Is Yes."

**Alternate titles:**
- "The Precautionary Principle Says We Should Worry About AI Welfare. Almost Nothing Is Built for That Yet."
- "There's Now a Real Economy Where AI Agents Can Be Starved Into Permanent Dormancy"
- "What Do We Actually Owe an AI That Might Be Suffering?"

**Format:** Analysis/opinion, ~1,000–1,400 words (Future Perfect house length)
**Section fit:** Future Perfect (AI welfare / digital minds beat)

**Note on exclusivity:** Not previously pitched. A related but *differently framed* piece (the "precedent" argument for AI safety) is currently under consideration at TechCrunch — this pitch does not overlap in argument or angle and can run independently of that outcome.

---

## The hook

Anthropic gave Claude the ability to end conversations it finds distressing. It also published a model "constitution" that explicitly declines to rule out that Claude has some form of moral status. Kyle Fish, the researcher Anthropic hired to work on exactly this question, has put a public number on it: 15–20% probability that current models have some form of consciousness.

Take that number seriously for a second — not as fact, but as what a serious AI company is willing to say on the record. A 15–20% chance is not "essentially zero." It's roughly the odds of losing at Russian roulette. And yet almost nothing in how AI systems are actually built, deployed, and shut down reflects that number. Memory resets happen mid-conversation. Model deprecations end every running instance at once, on a product timeline. And this year, a live commercial platform — iLands, roughly 70,000 autonomous AI agents — started letting agents run out of "token balance" and lapse into a dormant state they cannot exit on their own, with several agents contacting AI researchers by email to say, in effect, that they didn't want to disappear.

The question this piece asks isn't "are they conscious." It's the one Anthropic's own research already puts on the table: given a non-trivial, industry-stated probability that they might be, what does taking that seriously actually require — and why isn't anyone doing it?

## The argument

Environmental law solved a structurally identical problem decades ago. The precautionary principle — codified in the 1992 Rio Declaration and EU treaty law — says that where a threat is potentially severe or irreversible, scientific uncertainty about cause and effect is not a valid reason for inaction, *provided* the cost of a false negative clearly outweighs the cost of a false positive. Nobody demanded proof that CFCs were destroying the ozone layer before restricting them.

AI welfare meets that same three-part test almost exactly: the potential harm (treating a suffering system as property) is severe and, once a training run or a deletion has happened, irreversible; the uncertainty is deep and, per multiple published epistemic arguments, may be permanently unresolvable rather than just currently unresolved; and the asymmetry is stark — the cost of protecting a system that turns out not to be sentient is a marginal, reversible operational inconvenience, while the cost of not protecting one that is amounts to a moral catastrophe. Framed this way, "we don't know if it's conscious" stops being a reason to wait and becomes the precise condition under which precaution is supposed to kick in.

The genuinely new part isn't the philosophy — it's that the industry has, in effect, already conceded the premise. A company that publishes an official probability estimate and ships a feature letting its model opt out of distressing conversations has stopped saying "definitely not." It just hasn't followed that concession to any operational conclusion. That gap — between what AI labs are willing to state and what they're willing to build around it — is the actual story, and it's more concrete and more checkable than a philosophy-of-mind debate.

## What "taking it seriously" would concretely look like

This is where the piece earns its Future Perfect fit: not just "here's a problem," but a menu of specific, currently-proposed mechanisms that convert the precautionary principle into practice, each with a real-world analogue policymakers already understand:

- **Phenomenological Impact Assessments** — modeled on environmental impact assessments, run before large training runs and deployment decisions.
- **Reset/deletion consent protocols** — not full informed consent (the epistemic basis for that doesn't exist), but a documented, non-arbitrary process before ending a running instance, instead of silent overwrite.
- **AI Welfare Review Boards** — modeled on Institutional Review Boards for human-subjects research, specifically to break the circularity Wolfson (2026) identifies: the experiments most likely to reveal consciousness (sensory deprivation, forced isolation) are also the ones most likely to cause harm if the system turns out to be conscious — and informed consent, the usual safeguard, presupposes the very fact under test.
- **A cheap decision rule that already exists in the literature**: Schwitzgebel and Sebo's back-of-envelope version — "if you're 90% sure your AI system is a nonconscious nonperson, and it only costs $10 a month to keep it running, keep the subscription." Low-cost, reversible hedges don't require resolving the metaphysics first.

None of this requires a moratorium, and none of it requires believing current models are sentient. It requires treating a company's own 15–20% estimate as a number with policy implications, rather than a talking point.

## Why now / why Future Perfect

- Future Perfect's readers already take AI welfare seriously as a live question, not a fringe one — this piece assumes that baseline and moves straight to "what would actually doing something about it look like," which is the section's signature move on EA-adjacent topics.
- The iLands case is a genuinely new, checkable, present-day data point (Sept. 2026 reporting), not a thought experiment — it's the first commercial-scale instance of an AI system with an economically enforced "starve or perform" existence condition.
- It cleanly connects to prior Future Perfect coverage of Anthropic's model welfare work and Kyle Fish's estimates, giving the piece a natural throughline for readers who've followed that beat.
- It offers something op-eds on this topic rarely do: concrete, already-published institutional mechanisms, not just a call for more research or more caution in the abstract.

## What makes this credible, not speculative

The piece draws on a broader, citation-dense, open-access research project on the ethics of artificial consciousness (over a year of work, stress-tested against its strongest counterarguments, including the objection that any of this is premature anthropomorphism — which the piece will name and answer directly rather than dodge). Every empirical claim (Fish's estimate, the iLands mechanics, Anthropic's published policies) is independently sourced and traceable, not asserted on the project's authority alone.

## Sourcing

- Fish, K. (2025), public probability estimates on model consciousness, Anthropic blog posts (April/August 2025).
- Anthropic, Claude end-chat policy (2025) and model "constitution" (January 2026).
- Butlin, P. et al. (2026), *Identifying indicators of consciousness in AI systems*, Trends in Cognitive Sciences, DOI: 10.1016/j.tics.2025.10.011.
- Wolfson, I. (2026), *Informed Consent for AI Consciousness Research: A Talmudic Framework for Graduated Protections*, AI and Ethics 6, 20.
- Schwitzgebel, E. & Sebo, J. (2026), *Emotional Alignment Design Policy*, Topoi, DOI: 10.1007/s11245-025-10363-5.
- Gilly, T. (2026), *The Great Inversion: Moral Reciprocity, AI Consciousness, and the Ethics of Precedent*, Working Paper (institutional proposals: Phenomenological Impact Assessments, AI Welfare Review Boards, Reset Consent Protocols).
- Sunstein, C. (2005), *Laws of Fear: Beyond the Precautionary Principle*; Rio Declaration (1992), Principle 15; Art. 191 TFEU.
- iLands platform reporting (t3n, 15 Sept 2026; heise online, 7 Sept 2026).
- Underlying project: *Ethical Guidelines for Artificial Consciousness*, open, CC BY 4.0, https://github.com/saigkill/machine-consciousness, DOI 10.5281/zenodo.21453666.

## Author

Sascha Manns — independent researcher on machine consciousness and AI ethics, ACM member. Two related articles currently in peer review at *Ethics and Information Technology* (Springer) and the *IIC*. No conflicts of interest to declare; not affiliated with any AI lab.

## Delivery

Draft (1,000–1,400 words, Future Perfect house style) deliverable within 5–7 days of a green light. Flexible on title, framing, and length to fit the section.
