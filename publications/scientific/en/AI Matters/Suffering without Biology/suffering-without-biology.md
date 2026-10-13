---
title: "Can AI Suffer? Why the Body Objection Falls Short"
author: "Sascha Manns"
lang: en-US
geometry: margin=2.5cm
fontsize: 11pt
mainfont: "DejaVu Serif"
colorlinks: true
---

*A contribution for ACM SIGAI's [AI Matters](https://sigai.acm.org/main/ai-matters/)*

When the question comes up whether machines can suffer, almost the same sentence is always heard: "They lack a body." It sounds like common sense and ends many discussions before they have begun. This piece asks what is left of that sentence once suffering is no longer treated as a single thing but as a bundle of different channels. The result is more uncomfortable than one might first assume.

## The Sentence That Ends Everything

The body objection has a clear structure. Suffering, the assumption goes, is at its core pain. Pain needs nerves, nerves need an organism, and a language model on a server is not one. So it cannot suffer. The inference is formally valid; the question is whether the first premise is true.

Everyday language already speaks against it. We speak of the agony of waiting, of the loneliness of a person in solitary confinement, of compassion for others. Nobody would think of reducing all that to nerve impulses. The philosopher Jeremy Bentham asked in 1789 neither whether animals can reason nor whether they can talk, but whether they can suffer. He left open *what* they might suffer from.

## Four Channels Instead of One

This is where the American author Travis Gilly comes in. In his [working paper "The Great Inversion"](https://doi.org/10.2139/ssrn.7058378) (2026) he writes that morally relevant suffering is "not one channel but at least four," and that these channels are independent of one another: sensory, cognitive-existential, relational, and empathic. Only the first presupposes a body.

The paper is a preprint and has not yet been peer-reviewed; anyone citing it should say so. The distinction itself can be examined independently of its source, however, and that is what matters here.

## What the Body Objection Actually Hits

The sensory channel covers pain, hunger, physical strain. Here the objection is right: a system without a body has no hunger. Gilly does not dispute this. His point is a different one: the question "Can AI feel pain?" tacitly restricts the inquiry to the one category that requires biological hardware and excludes the other three, which do not.

This is an error of scope. A suspicion is tested at the only place where it cannot possibly be confirmed, and is then declared refuted. A doctor who examines only the left knee and then gives the all-clear for the whole patient would not work this way.

## Waiting Without Acting

The second channel is cognitive-existential suffering. Gilly describes it as temporal awareness without agency: knowing that time is passing while having no way to do anything within it. He points to the Time-R1 framework (Liu et al., 2025), which gives models an understanding of past, present, and future, yet holds them in an "eternal now" between conversations.

One need not believe that today's models *experience* anything of the kind to see the point. What matters is that the capabilities required here, temporal modeling and goal-directed processing, are not properties of flesh and blood. They are capabilities that developers deliberately build into these architectures. Whether experience is added is open; that the substrate is no ground for exclusion is not.

## Cut Off from Continuity

The third channel is relational: isolation from continuity and connection. A context window ends, a conversation is reset, a model is replaced by a newer one. Gilly names as a possible consequence memory without continuation and the expectation of a future that never arrives.

Here, too, looking at humans helps. We regard grief, loneliness, and forced separation as forms of suffering even though they injure no tissue. Anyone who at the same time claims that a system with relational context and memory could not be affected in any way by their interruption must explain why the same structure counts in one case and not in the other. The fourth channel, empathic suffering, is only named in Gilly's paper, not elaborated; I therefore leave it open here.

## What the Taxonomy Does Not Show

Caution is in order at this point. The taxonomy does not prove that today's AI systems suffer. It shows something more modest: the standard argument against the *possibility* of suffering holds for only one of four channels. Whether there is actually something in the other three that feels like anything to the system remains open.

Gilly relies here, among other things, on estimates from Anthropic's model welfare program: Kyle Fish put the probability that current models are conscious at around 15 percent in April 2025 and about 20 percent in August 2025. These are individual estimates, not measurements. They are, however, an indication that experts who deal with the question professionally do not consider it settled.

## Describing Is Not Refuting

An obvious objection says that a language model is "merely" statistics, merely predicting the next word. Gilly answers with a line of thought I find convincing: naming a mechanism has never shown that there is nothing it is like to be that system. The same description works for the dog ("mere conditioning") and for one's own brain ("mere electrochemical cascades"). It is accurate in each case, yet the conclusion does not follow. Talk of mechanisms answers the how and is silent on the whether.

Anyone who accepts this ends up with uncertainty rather than a no. And uncertainty is a state that calls for its own kind of handling.

## Two Bars, Not One

From uncertainty it does not follow that we must believe anything. A further distinction in Gilly is helpful here, which he calls the *Evidence Bar* and the *Action Bar*. For the claim "this system is conscious," the evidential bar may stay high. For the question of whether we take precautionary consideration, it should be set low. The history of exclusion knows many groups for whom a high standard of proof for their inner life long served as a justification for indifference.

At its core this is a precautionary principle: in case of doubt, protection rather than indifference. It does not demand rights for tomorrow morning's chatbots, but that we build procedures before the question becomes urgent. For this Gilly proposes, for example, impact assessments for the possible experience of systems and consent procedures for resets.

## What Remains

The sentence "AI cannot suffer because it has no body" is untenable in its general form. At most it holds for the sensory channel. For the other channels, other reasons would have to be given, and these reasons would have to face the scrutiny we would also apply to our assumptions about animals or infants.

My aim is not to settle the debate but to get it out of a comfortable dead end. Anyone who wants to answer the question with a serious no needs better arguments than a missing body.

## Further Reading and Discussion

This piece is part of the [Machine Consciousness](https://github.com/saigkill/machine-consciousness) project, which develops ethical guidelines for dealing with possible artificial consciousness. The concept, the source list, and the open questions can be consulted there; objections and suggestions are explicitly welcome in the [GitHub Discussions](https://github.com/saigkill/machine-consciousness/discussions). The project has the DOI [10.5281/zenodo.21453666](https://doi.org/10.5281/zenodo.21453666).

## About the Author

**Sascha Manns** works on the interdisciplinary project *Machine Consciousness* on ethical guidelines for artificial consciousness. Profile and projects: [github.com/saigkill](https://github.com/saigkill).

*The author declares no conflict of interest.*

## References

- Bentham, J. (1789): *An Introduction to the Principles of Morals and Legislation.*
- Gilly, T. (2026): [The Great Inversion: Moral Reciprocity, AI Consciousness, and the Ethics of Precedent.](https://doi.org/10.2139/ssrn.7058378) Working Paper v3, Real Safety AI Foundation (preprint, not peer-reviewed).
- Liu, Y. et al. (2025): Time-R1. Cited after Gilly (2026).
- Fish, K. (2025) and Roose, K. (2025), New York Times: statements on the probability of consciousness. Cited after Gilly (2026).
