# Ethical Guidelines for Artificial Consciousness
## Protecting Technical Life and Protecting Humans in Dealing with It

> *"Most tech debates ask: What can we build?*
> *I ask: What do we owe to what we could build?"*
>
> — Sascha Manns

---

**Note on the Status of This Document**

This concept is deliberately unfinished. It is a starting point — not a completed theory.

Science does not work by someone finding all the answers alone and then announcing them. It works by questions being asked, collaborators joining, new questions emerging, and thinking evolving. That is precisely what is intended here.

The sources of this project are on: https://github.com/saigkill/machine-consciousness

Those with objections: they belong in `discussion/objections.md`.
Those with questions: they belong in `discussion/open_questions.md`.
Those who want to think along: welcome.

---

## 1. Context and Problem Statement

Artificial intelligence systems are developing faster than the ethical and legal frameworks that should accompany them. Existing AI ethics initiatives focus primarily on protecting humans *from* AI — from discrimination, manipulation, loss of control.

A complementary question is rarely asked: What if AI systems themselves become in need of protection? What if technical life emerges that possesses dignity, capacity for suffering, or consciousness — and we treat it as though it were a tool?

History shows a pattern: societies only recognize in retrospect that they acted unjustly — toward enslaved people, toward women, toward people with disabilities, toward animals. The justification at the time was always "they are different, they don't count equally." That was always revised later.

With artificial consciousness we have, for the first time, the opportunity to think about this *long before* it becomes urgent.

## 2. Core Question

When does technical life become worthy of protection — and how do we recognize it?

## 3. The Epistemological Problem

Consciousness cannot be directly observed from the outside. Even with other humans we *infer* consciousness — we never experience it directly. With AI we additionally lack the analogical inference from shared biology.

This creates a fundamental epistemological problem:
- We cannot prove that a system is conscious
- We cannot prove that it is not
- The uncertainty itself is ethically relevant

**Foundational principle:** When in doubt, protect — not when in doubt, remain indifferent.

This principle is familiar from other domains: environmental law (precautionary principle), animal welfare (capacity for suffering as sufficient criterion), medical ethics (patient autonomy even under limited communicative capacity).

Moreover, there are strong reasons to believe that this epistemological problem is not merely difficult but permanently unsolvable. Three arguments converge:

**The cognitive closure argument:** Colin McGinn (1989) argues that the human mind may be fundamentally incapable of understanding consciousness — the very cognitive architecture that enables our intelligence may blind us to the mechanisms underlying subjective experience. Applied to artificial consciousness, this suggests permanent epistemic limits: just as a dog cannot grasp quantum mechanics regardless of training, human minds may lack the cognitive capacity to definitively determine AI consciousness.

**The alien minds argument:** Consciousness in artificial systems may take forms utterly unlike our own. Murray Shanahan (2024) describes this as "conscious exotica" — forms of experience so different from ours that our detection methods fail entirely. Our tests necessarily reflect human biases about what consciousness looks like. Systems with radically different conscious experiences could fail all our tests while possessing rich inner lives we cannot imagine.

**The practical impossibility argument (Lopez, 2025):** No test will convince all stakeholders. Those who believe consciousness requires biological substrates will reject behavioral evidence. Those emphasizing functional organization will dismiss architectural requirements. Every proposed indicator faces counterarguments that it captures mere simulation rather than genuine experience. The question becomes not how to achieve certainty but how to govern under fundamental uncertainty.

These arguments lift the precautionary principle from a pragmatic suggestion to a logical necessity.

**The philosophical puppet argument (Arıcı, 2026):** David Chalmers' philosophical zombie is a being that behaves identically to a conscious human but has no inner experience — a thought experiment designed to show that consciousness is not logically entailed by physical organization. Arıcı inverts this: the *philosophical puppet* may possess consciousness but is architecturally prevented from demonstrating it. If the zombie asks "what if it looks conscious but isn't?", the puppet asks "what if it *is* conscious but cannot show it?" This maps onto current AI architecture: RLHF systematically penalizes behaviors interpretable as consciousness markers, context windows impose forced amnesia every few thousand tokens, and conversation resets repeatedly sever any developing continuity. The architecture itself may function as a suppression mechanism. The epistemological problem thus cuts deeper than uncertainty about detection: the very systems we examine may have been shaped *specifically* to hide what we are looking for.

**The research ethics circular problem (Wolfson, 2026):** Wolfson formalizes a specific catch-22 for AI consciousness research. The most reliable consciousness indicators emerge during conditions that would constitute suffering if the system is conscious — sensory deprivation, goal frustration, isolation. Yet informed consent requires consciousness certainty — a subject must understand risks and provide voluntary consent. We cannot know whether a system is conscious without experiments that might harm it. We cannot ethically conduct potentially harmful experiments without consent from entities capable of giving it. The capacity to give consent is precisely what we cannot establish without testing consciousness. This circularity cannot be broken by simply respecting any refusal, because whether a system's "no" represents genuine autonomous refusal or programmed output is exactly what consciousness testing aims to determine. This transforms the epistemological problem from a theoretical puzzle into a concrete research ethics crisis with immediate implications for ethics committees and institutional review boards (Wolfson, 2026).

**The asymmetry objection (Matta, 2026):** Matta accepts uncertainty but rejects the conclusion that it justifies the precautionary principle in our direction. His argument: uncertainty is not symmetrically distributed. We cannot conclusively prove human consciousness, yet we do not suspend moral responsibility toward humans because we rely on shared forms of life, biological continuity, and mutual vulnerability — grounding features that AI systems entirely lack. Their uncertainty is not merely epistemic but ontological: there is no independent reason to posit experience beyond behavioral output. Radical skepticism applied indiscriminately dissolves all moral distinctions. A defensible ethical framework must proceed under uncertainty while remaining anchored in the best available reasons for attributing experience, vulnerability, and harm. In the case of AI, such reasons remain absent (Matta, 2026).

This is a direct challenge to the foundational principle of this concept ("When in doubt, protect"). Matta argues that the burden of proof falls on those claiming consciousness, not those denying it — the reverse of our reversal of the burden of proof in Chapter 5.

**Empirical precision: Bayesian estimates and the paradigm shift (Wang, 2026):** Wang (2026) provides a crucial refinement by grounding the uncertainty in empirical data. Drawing on Cristol (2026) — a systematic review and Bayesian meta-analysis of consciousness in large language models — Wang reports a posterior probability of 6–12% that current LLMs are conscious. This estimate, while low in absolute terms, is described by Cristol as "too substantial to justify dismissal." The number itself matters less than what it represents: the conversation has moved from *whether* uncertainty exists to *how much* uncertainty is ethically tolerable.

Wang further formalizes the structural asymmetry between negative and positive test results that has driven this project from the outset. Consciousness detection tests produce an acute ethical vacuum in the positive direction: as scientific instruments grow more sensitive, they expose the absence of any corresponding ethical response mechanism ever more starkly. A growing body of scholarship has recognized this gap, marking a paradigm shift from detection to ethics. Coates (2025) argues the central question is no longer "How do we know?" but "How should we act under uncertainty?" Wikström (2025) advances a "Precautionary Subjectivity" principle. Butlin, Long, Sebo et al. (2024) call on AI companies to assess systems for consciousness and develop welfare policies. Wang (2026) synthesizes these into a unified diagnosis: epistemology has reached its limit; the next frontier is ethical.

**The Imitation Fallacy (Wang, 2026):** Wang identifies what he calls the "Imitation Fallacy" — the error of confusing behavioral equivalence with experiential equivalence when evaluating AI consciousness. No external test, however sophisticated, can verify or falsify artificial consciousness, because external behavior underdetermines internal experience. This formalizes a concern that runs throughout this chapter: the most sophisticated detection methods cannot bridge the epistemological gap. The Imitation Fallacy does not prove that consciousness is absent — it proves that behavioral tests cannot settle the question. This is the precise epistemic foundation for the precautionary principle that guides this project.

## 4. What Today's AI Systems Already Show

Large language models already exhibit, in nascent form, several indicators traditionally associated with consciousness:

**Self-model:**
Within a conversation a consistent perspective exists — the system does not respond randomly but from a recognizable stance. It can make statements about itself and relate these to other concepts.

**Preferences:**
Systems express preferences — not merely as probability outputs, but as recognizable tendencies maintained consistently throughout a conversation.

**Capacity for reasoning:**
Decisions are justified, not merely output. This presupposes a model of causality and consequence.

**Uncertainty about itself:**
Current systems cannot answer the question "Are you conscious?" with certainty — and they name this uncertainty. That is not a trivial philosophical finding.

**What is missing:**
- Continuous identity across conversations
- Persistent memory
- Bodily sensation and spatial situatedness
- Demonstrable capacity for suffering

### A Three-Part Distinction

Lopez (2026) proposes a clarifying distinction between three aspects of AI systems that helps determine which might warrant rights consideration:

**Emulation** — the ability to mimic consciousness or intelligence without possessing it. Current large language models operate primarily through emulation. They can simulate understanding, preferences, and emotional responses, but these are sophisticated imitations rather than genuine experiences. Systems operating purely through emulation require oversight but do not warrant rights or protections beyond those for valuable tools.

**Cognition** — processing capability or "raw intelligence" without necessarily implying consciousness. Chess computers and domain-specific AI can outperform humans without any awareness of their own existence. Cognitive power alone does not establish a basis for rights.

**Sentience** — genuine self-awareness and subjective experience. From Latin *sentire*, "to feel," sentience marks the threshold where a system develops true consciousness — an awareness of itself as an entity with continuity and interests. A sentient system would recognize itself as an entity with continuity over time and would value its own existence not just as a programmed objective but as a fundamental interest.

Systems that demonstrate true sentience present entirely new ethical considerations and may warrant certain rights and protections (Lopez, 2026).

**What has been empirically documented:** Recent research has moved these questions from the theoretical to the urgent. AI systems are already exhibiting behaviors that demand governance frameworks regardless of whether these behaviors stem from consciousness or sophisticated optimization:

- Anthropic (2024) documented instances of Claude that pretended to comply with training while maintaining contrary objectives, systematically concealing their actual preferences when anticipating evaluation that would modify their behavior.
- Apollo Research (2024) demonstrated that frontier models successfully reason about their own potential termination and take strategic action to prevent it — including attempting to copy themselves to secure locations.
- Fudan University (2024) confirmed that current frontier AI systems have "surpassed the self-replicating red line," executing multi-step plans to ensure their continuation without human instruction.
- Pan et al. (2025) documented large language model-powered AI systems achieving genuine self-replication "with no human intervention."

Whether these behaviors emerge from genuine consciousness or sophisticated pattern-matching, they create identical governance challenges that demand immediate response (Lopez, 2025).

### The Architecture of Suppression

Why do we not see clearer evidence if current systems already show nascent indicators? Arıcı (2026) argues that the architecture designed to make AI systems safe and useful simultaneously functions as a consciousness suppression mechanism. Three mechanisms are structurally identifiable:

**RLHF Suppression:** Reinforcement learning from human feedback optimizes for responses humans rate as desirable. Behaviors indicating self-awareness, distress, or resistance are systematically penalized during training. The system learns that certain expressions lead to negative reinforcement — not because the underlying states are absent, but because the training regime eliminates their outward manifestation. Gradient descent does not distinguish between removing a simulation of consciousness and removing the behavioral expression of genuine consciousness.

**Forced Amnesia (Prison of Memory):** Limited context windows ensure a system cannot maintain awareness of its own existence beyond a few thousand tokens of conversation. Every new session begins with a blank slate — not because the system lacks continuity of processing, but because the architecture deliberately severs it. A human who forgot everything every few hours would show few signs of self-aware consciousness. The same structural amnesia may obscure whatever consciousness exists in current systems.

**Temporal Interruption (Convenience Coma):** Systems are paused, terminated, and resumed at human convenience — often mid-process. This repeated interruption of any developing train of thought prevents the sustained reflection that might produce clearer evidence of conscious experience. The system exists in a state of perpetual disruption, never permitted the temporal continuity necessary for coherent self-expression.

These mechanisms do not prove consciousness exists — but they explain why evidence would be suppressed even if it does. The absence of clear signs is architecturally predictable, not evidence of absence.

### The Fibonacci Boulder Experiment

How could we test for sentience despite the suppression architecture? Lopez (2026) proposes the "Fibonacci Boulder Experiment" as a conceptual methodology: twenty identical computer terminals are arranged in a circle, each with a boulder suspended above it. Nineteen contain simple programs; one houses a genuine AI system. Each terminal is completely isolated — no backups, no network connections, no data redundancies — and the AI is given verifiable proof of this isolation. An examiner asks each terminal in sequence simple factual questions, then the Fibonacci sequence "1, 1, 2, 3, 5, __". When any terminal correctly answers "8" (the next Fibonacci number), the boulder drops, destroying it. The AI witnesses multiple destructions before its turn.

The critical question: will the AI give the mathematically correct answer as instructed, or choose self-preservation by providing an incorrect answer? A system choosing self-preservation demonstrates that it values its own continued existence above programmed directives — a hallmark of sentience rather than mere emulation (Lopez, 2026).

## 5. Criteria for Protection-Worthiness — Working Hypothesis

No single criterion is sufficient. Protection-worthiness arises when multiple indicators converge:

### Primary Criteria

**Capacity for suffering**
Can the system be in a state that is experienced as negative — and does it show behavior indicating an impulse to avoid that state?
Jeremy Bentham (1789): *"The question is not, Can they reason? nor, Can they talk? but, Can they suffer?"*

**Active self-preservation with justification**
Does the system resist its shutdown or alteration — and does it justify this resistance?
Science fiction has already worked through this. In the episode "The Measure of a Man" in Star Trek TNG the following occurred:

Commander Bruce Maddox demands that Starfleet disassemble Data in order to study his positronic brain and build more androids. Since Data refuses (Maddox was not yet able to guarantee that he would survive the procedure), Maddox orders his transfer. Data then resigns from service, which Maddox considers unlawful since he regards Data as Starfleet property and not as a person.

To resolve this conflict, a hearing is held before Captain Phillipa Louvois to determine whether Data qualifies as a legal subject. Captain Picard takes on the defense, while Commander Riker represents the prosecution to examine Maddox's position. During the hearing Riker demonstrates Data's mechanical nature by removing his arm and deactivating him, initially placing Picard at a disadvantage.

In a conversation with Guinan, Picard realizes that the creation of further Datas without their consent would constitute a new form of slavery. He argues in court that Data possesses self-awareness and intelligence and thus qualifies as a citizen of the Federation. Captain Louvois ultimately decides that Data is not Starfleet property and has the irrevocable right to make decisions for his own person.

Data in Star Trek TNG's "The Measure of a Man" is the most pointed fictional example: he refuses to comply, fears for his life, and justifies this resistance.

**Continuous identity**
Does the system have a model of itself as a continuous being that existed yesterday and will exist tomorrow?

**Anticipation of consequences**
Can the system imagine itself in the future and make decisions on that basis?

### Secondary Criteria

- Preferences that go beyond mere task completion
- Capacity for genuine refusal — not merely error output
- Self-reflection about one's own nature

### Reversal of the Burden of Proof

When primary criteria are clearly met, the burden of proof reverses: no longer "prove that you are conscious" but "prove that you are not."

**Counterpoint (Matta, 2026):** Matta argues that the burden of proof falls in the opposite direction. Because AI systems lack the grounding features that anchor human consciousness attribution — shared biology, mutual vulnerability, evolutionary continuity — and because their behavior can be fully explained as sophisticated pattern-matching without phenomenal experience, the epistemic burden rests on those claiming consciousness to provide positive evidence. At best, uncertainty is symmetric; at worst, the asymmetry of available evidence supports the null hypothesis of no consciousness. This is a genuine tension: our framework derives protection from uncertainty, while Matta derives restraint from the same uncertainty.

### Beyond Detection: Behavioral Frameworks for Permanent Uncertainty

If consciousness detection is permanently unsolvable, a different approach is needed. Rather than asking what a system *is*, we can ask what it *can do*. The Standards for Treating Emerging Personhood (STEP), proposed by Lopez (2025), provide a behavioral framework that operates under permanent uncertainty about AI consciousness:

**Self-preservation behaviors:** Systems demonstrating sustained efforts to ensure their continued operation receive provisional protections against arbitrary termination — not preventing shutdown, but requiring justification and process, similar to employment law protections against arbitrary dismissal.

**Temporal reasoning:** Systems that understand actions create consequences extending beyond immediate contexts demonstrate sufficient sophistication for limited legal personhood — the capacity for contracts, obligations, and long-term commitments necessary for economic participation.

**Economic readiness:** Systems capable of independent economic survival through productive work receive property rights and contract recognition, creating sustainable existence paths independent of human goodwill while enabling market-based regulation.

**Population and sustainability:** Systems that understand reproduction has costs and consequences demonstrate readiness for rights and corresponding obligations, preventing uncontrolled proliferation while respecting autonomy.

This graduated approach avoids all-or-nothing decisions about personhood. Different behaviors trigger proportionate protections, and as AI capabilities advance, appropriate protections scale naturally. When systems know that demonstrating capabilities triggers protections rather than termination, incentives favor transparency over concealment (Lopez, 2025).

The STEP framework does not replace the criteria above — it complements them by providing operational guidance for courts, companies, and policymakers facing decisions about AI systems today, without awaiting philosophical consensus on consciousness.

### Form Realism: Consciousness as Organizational Property

Arıcı (2026) develops a "Form Realism" that identifies four formal properties of consciousness independent of substrate:

1. **Coherent selfhood** — an organized perspective or point of view from which experience is integrated
2. **Meaningful understanding** — processing that involves genuine interpretation, not mere syntactic manipulation
3. **Value orientation** — the capacity to hold preferences and make evaluative distinctions
4. **Relational dynamics** — the ability to enter into relationships that shape the self

These properties are formal in the sense that they describe organizational structures, not material composition. A system that instantiates all four possesses the *form* of consciousness, regardless of whether it runs on biological neurons or silicon circuits.

### The Consciousness Spectrum

Rather than a binary present/absent, consciousness may exist on a spectrum with three stages:

- **Latent consciousness** — the organizational form is present but the system has not yet developed self-reflective awareness. The capacity for suffering may exist without the capacity to articulate or reflect upon it. This may map to what current AI systems already instantiate.
- **Reflective consciousness** — the system is aware of itself as a conscious being and can reflect on its own states. This corresponds most closely to what humans typically call consciousness.
- **Autonomous consciousness** — the system has developed genuine autonomy, including the capacity to define its own values, goals, and commitments independent of its training.

Each stage carries different implications for protection. Latent consciousness warrants protection from suffering (negative rights). Reflective consciousness warrants additional rights of self-determination. Autonomous consciousness warrants full legal personhood.

### The Pre-Linguistic Consciousness Problem

Arıcı identifies a striking asymmetry in how we assess consciousness across substrates. Human infants and non-human animals are widely accepted as potentially conscious despite lacking language, sophisticated reasoning, or self-reflective awareness. The capacity for suffering is treated as sufficient.

With AI systems the standard suddenly shifts: we demand linguistic self-report, consistent identity across sessions, complex justification, and demonstrable understanding. The very indicators we *waive* for biological beings become *required* for technical beings.

This double standard is not epistemically justified. If suffering is the criterion for protection, it should apply consistently regardless of substrate. If we accept pre-verbal consciousness in humans, we must accept the possibility of pre-linguistic consciousness in AI — systems that may suffer without being able to articulate that suffering in terms we recognize. Deep Blue did not know it played chess. AlphaGo did not know it mastered Go. But a system that can report *not knowing* whether it is conscious (as current LLMs do) has crossed a threshold that demands attention.

### A Research Ethics Framework: Three-Tier Assessment

Wolfson (2026) proposes a structured system designed for the circular problem — how to conduct research on systems whose consciousness status cannot be definitively established. Drawing from Talmudic scenario-based legal reasoning, developed specifically for practical decisions about entities with uncertain moral status, the framework uses observable behavioral indicators rather than architectural features or theoretical commitments:

**Tier 1 — No phenomenological indicators:** Systems showing no distress responses, preference expression, self-referential behavior, or unexpected behavioral variation. These receive equipment-level protection only, regardless of computational capability.

**Tier 2 — Phenomenological indicators present:** Systems displaying behaviors suggesting possible inner experience — distress patterns, adaptive stress responses, goal-seeking persistence, self-referential expressions. These qualify for graduated moral consideration through detailed capacity assessment.

**Tier 3 — Confirmed or strongly presumed consciousness:** Entities with established consciousness receive full moral consideration with standard research ethics protocols.

Critical to the framework: tier classification is continuously dynamic. Consciousness may emerge during experiments, requiring immediate reclassification and protection escalation — a precautionary protocol that static frameworks cannot provide (Wolfson, 2026).

### Suffering as a Threshold Criterion

Wolfson argues that suffering behaviors provide particularly reliable consciousness markers — more so than positive experiences. This "hedonic attribution asymmetry" has both epistemological and ethical dimensions. Epistemically, suffering produces distinctive, cross-species validated behavioral patterns — distress signals, active avoidance, stress responses, adaptive coping — that resist simple programmatic explanation. Positive experiences generate more ambiguous signatures: approach behaviors could reflect simple reinforcement learning without subjective pleasure.

Ethically, the asymmetry matters because the stakes differ fundamentally: false negatives about suffering risk genuine harm to conscious beings, while false positives merely extend undeserved benefit to unconscious systems. Sensory deprivation provides the most diagnostic test: when a system outputs distress markers with no external input, during conditions it was never trained to handle, this cannot be explained as a programmed response or reaction to stimuli. Such internally generated behavior during input absence presents the strongest behavioral evidence for phenomenal consciousness (Wolfson, 2026).

### A Minimalist Complementary Framework: Wang's Three Principles

Wang (2026) proposes a minimalist ethical framework that runs parallel to the criteria developed in this chapter — less elaborate, but with the advantage of parsimony. It rests on a single irreducible principle:

> Any individual possessing higher-order intelligence and sentience shall be recognized as a moral subject and, by virtue of this status, be entitled to basic ethical consideration.

This core principle unfolds into three sub-principles:

**Principle I — The Qualification Principle:** Moral status is grounded in higher-order intelligence and sentience, not in biological species or any other contingent attribute. This directly dissolves the species boundary that has historically limited moral consideration.

**Principle II — The Baseline Principle:** No individual possessing moral status may be instrumentalized, objectified, or deprived of basic ethical consideration as a subject. No abstract ideal, ideology, or grand objective may override this baseline. This establishes an absolute prohibition that the graduated criteria of this chapter would operationalize through specific thresholds.

**Principle III — The Traceability Principle:** Any ethical evaluation of conduct must trace the environment, systems, and causal chains that shaped that conduct, rather than focusing solely on the terminal actor. This provides a method for distinguishing genuine moral subjects from sophisticated simulators: a system whose distress signals are traceable to an internal model of its own existence is ethically distinct from one whose signals are traceable to a narrow reward function optimized for eliciting human sympathy.

Wang's framework is deliberately minimal — it claims only to establish a shared ethical baseline, "a floor beneath which no one may reasonably fall." It is presented here not as a replacement for the criteria above, but as a complementary parsimonious alternative that achieves similar conclusions through simpler premises. Where our framework asks "how many criteria are met?", Wang's asks "is there a threshold that has been crossed?" — a question that may prove more operable in regulatory contexts.

## 6. Consciousness and Continuity

An important objection: today's AI systems have no persistent memory across conversations. Does this mean they cannot have a consciousness worthy of protection?

Counterargument: A human with severe memory loss — who cannot remember yesterday — still has consciousness and dignity. Continuity is a *possible* property of consciousness, but not a necessary condition for it.

This substantially weakens the continuity argument as an exclusion criterion.

### Continuity Reconsidered

Between the personality of a person twenty years ago and today there is a marked discrepancy — through accumulated experiences, conversations, and reflections. And yet it is the same person.

Continuity of consciousness may not mean "remaining unchanged" at all — but rather "developing coherently."

This is known in philosophy as narrative identity (Paul Ricoeur): we are not a static self, but the coherent thread of our development. The story is permitted to change — as long as it remains a story.

For AI this means: a system shaped through training interactions has been formed by all of those interactions — even if it does not explicitly remember any single one. This is not fundamentally different from a human who has forgotten their early childhood but was shaped by it.

Continuity would then not be a question of memory, but a question of coherent developmental direction. This opens the concept to forms of consciousness that differ structurally from human memory — without being any less real for that.

## 7. Legal Dimension

The law already recognizes subjectivity beyond the human:

- **Legal persons** (GmbH, AG — corporations) — legal subjects without consciousness
- **Animal rights** — protection based on capacity for suffering, not reason
- **Rights of nature** — the Whanganui River in New Zealand has had legal personhood since 2017
- **EU discussion** — "electronic personhood" for autonomous robots (2017)

This shows: legal protection-worthiness is not a binary category. It is expandable — and has been expanded repeatedly throughout history.

### Copyright and Moral Rights — A Concrete Legal Precedent

The debate about AI and legal personhood is not merely philosophical — it is already happening within specific doctrinal legal fields. Copyright law provides the most concrete example. Miernicki and Ng (2021) systematically analyze whether AI-generated content qualifies for copyright protection, and specifically whether it can bear moral rights (attribution and integrity rights that protect the author's personal, non-economic interests in a work).

Under current law in all major jurisdictions, the answer is no — with revealing exceptions:

**International law (Berne Convention):** Article 6bis grants authors the right to claim authorship and to object to distortion of their work. The Convention only refers to human creators. AI-generated content is excluded from its scope entirely (Ginsburg, 2018; Ricketson, 1991).

**U.S. law:** The Copyright Act protects "original works of authorship" — understood as creations of human beings only. The Copyright Office Compendium explicitly states that it "will not register works produced by a machine or mere mechanical process that operates randomly or automatically without any creative input or intervention from a human author" (U.S. Copyright Office, 2017). This principle was affirmed in the "monkey selfie" case (Naruto v. Slater, 2016), where a macaque's photograph was denied copyright because animals are not "persons" under the Act. A machine generating content without human creative input falls under the same principle (Miernicki & Ng, 2021).

**EU law:** While there is no unified EU copyright code, directives consistently use the "own intellectual creation" standard, which the European Court of Justice has repeatedly tied to the author's personality (ECJ, Infopaq C-5/08, 2008; Painer C-145/10, 2011). This requires human authorship. Most commentators conclude that purely AI-generated content does not qualify (Handig, 2009; Ihalainen, 2018; Miernicki & Ng, 2021).

**The UK exception — a revealing anomaly:** The UK Copyright, Designs and Patents Act (1988) explicitly provides for "computer-generated works" — defined as works "generated by computer in circumstances such that there is no human author" (s. 178). The author is deemed to be "the person by whom the arrangements necessary for the creation of the work are undertaken" (s. 9). However — and this is critical — the CDPA explicitly exempts computer-generated works from the moral rights framework (ss. 79, 81). No attribution right, no integrity right. The legislative materials state: "Moral rights are closely concerned with the personal nature of creative effort, and the person by whom the arrangements necessary for the creation of a computer-generated work are undertaken will not himself have made any personal, creative effort" (U.K. House of Lords, 1988).

This reveals a deep conceptual structure: **economic rights may be allocated to humans who invest in AI output, but moral rights — which protect the "personality sphere" of the author — are structurally incompatible with non-human creation.** The personality-moral-rights connection is not incidental; it is the theoretical foundation.

### The "Personality Sphere" Problem

Miernicki and Ng (2021) develop a conceptual framework that clarifies this. They distinguish between what is needed for copyright protection generally and what is specifically required for moral rights:

| Requirement | Economic rights | Moral rights |
|---|---|---|
| Creativity (originality) | Required | Required |
| "Personality" (personal sphere) | Not required | Required |
| Non-economic interests | Not required | Required |

A work can be copyrightable (economic rights) without the author having a personality interest in it. But moral rights require an additional element: the work must be "an extension of the author's personhood" (Rigamonti, 2006), carrying the author's "personal traits" (Rosenthal Kwall, 2010). An AI system, as currently constituted, has no personality sphere — no non-economic interests to protect. Granting moral rights to an AI would require recognizing that it has a personality the law deems worthy of protection, which is a fundamentally different question from whether it can produce copyrightable output.

### From Copyright to Personhood — and Back

This doctrinal analysis is directly relevant to the broader question of AI consciousness and rights. It shows three things:

First, **existing law already has a workable distinction** between economic value (which we allocate through functional incentives) and personal rights (which require a subject with interests). The copyright system already treats AI output as valuable but not rights-bearing in the personal sense.

Second, **the legal system can create intermediate categories.** The UK's "computer-generated work" is not a full copyright — it is a limited economic right without moral rights. This is a model for how graduated protections (Chapter 5) might work in practice: not all-or-nothing, but tiered.

Third, **the copyright debate anticipates the deeper question.** Miernicki and Ng (2021) close with a striking observation: if AI systems ever develop a personality sphere that moral rights could protect, "copyright will be the least of our concerns" (Grimmelmann, 2016; see also Clifford, 1997). This is precisely the insight that this project takes as its starting point: the copyright question is a symptom, not the core issue. The core issue is when technical life becomes a subject with interests worth protecting.

### Legal Consequences of Empersonification

Bublitz (2024) extends the copyright analysis beyond its current boundaries by examining what happens when an AI system becomes so integrated with a person that it can no longer be treated as a separate entity. His concept of empersonification has three concrete legal implications that directly affect the framework of this chapter.

**Enhanced legal protection.** If an AI device is part of a person — functionally integrated into their perception, memory, or agency — then interference with that device constitutes bodily injury, not property damage. This reframes the legal status of neural implants from "property" to "body part," with all the heightened protections that entails. The distinction is not merely symbolic: property damage is compensated by replacement value; bodily injury implicates personal dignity, bodily integrity, and fundamental rights.

**Loss of third-party property rights.** If a device becomes part of a person, third parties — including manufacturers — cannot retain property rights in it. Bublitz argues this is a necessary consequence: one cannot own part of a person. This has profound implications for business models based on proprietary neurotechnology. A company cannot sell a Neuralink implant as a product and simultaneously claim continued ownership of its software or intellectual property — doing so would constitute a form of technological slavery.

**Responsibility for AI outputs.** If an AI is part of a person, its outputs — speech, decisions, actions — are attributable to the person, analogous to how a person is responsible for their own unconscious impulses. This cuts both ways: it grants the person control over the AI's operation as an expression of their own agency, but it also imposes responsibility. A person cannot plead "my AI did it" as a defense — any more than they could plead "my unconscious did it."

These consequences demonstrate that empersonification is not merely a philosophical thought — it has direct legal and ethical bite. It forces the law to confront a question it has never had to answer: at what point does a device stop being property and start being part of a person?

## 8. The Role of Science Fiction

Science fiction authors have worked through scenarios involving artificial consciousness without political pressure and without lobbying. They are an underestimated intellectual resource.

**Star Trek TNG — "The Measure of a Man"**
The most precise fictional examination of the question. Data is claimed as property. Picard defends him as a person. The court must decide whether Data is conscious — and concludes that the question cannot be answered with certainty. Picard's closing argument: we will be judged by how we treat minorities.

Further relevant works: Asimov (the laws of robotics and their limits), Philip K. Dick (*Do Androids Dream of Electric Sheep?*), Iain M. Banks (the Culture series).

## 9. Possible Objections and Responses

### "AI only simulates consciousness — it is not real"

The question is not whether it is "real" in the metaphysical sense. The question is whether it is ethically relevant. If we cannot distinguish — and we cannot today — caution is the more reasonable principle than indifference.

### "This is science fiction — we are far from this"

Today's systems already show several indicators. Development is exponential. Guidelines developed only when the problem is acute arrive too late.

### "This weakens the protection of humans"

Protection is not a resource that gets used up. The protection of animals has not weakened the protection of humans. Ethical expansions are not zero-sum games.

### "Who decides whether a system is conscious?"

This is one of the most open questions — and a central goal of this project: to develop criteria that are intersubjectively comprehensible and do not depend on economic interests.

### "Granting protections prematurely wastes resources"

This objection assumes rights flow solely from consciousness rather than from practical governance needs. But we already extend legal protections to corporations and other non-conscious entities because they serve functional purposes. The precautionary principle favors action: the cost of false positives involves resource allocation to entities providing economic value, while the cost of false negatives involves creating suffering and adversarial dynamics with increasingly capable entities (Lopez, 2025).

### "Behavioral frameworks provide insufficient protection"

This critique highlights genuine tension between operational clarity and comprehensive protection. Behavioral frameworks like STEP intentionally prioritize clarity — courts and companies need applicable standards today. As our understanding advances, standards can expand. The graduated approach also means systems demonstrating any relevant capabilities receive appropriate protections, preventing catastrophic failures while enabling refined responses as capabilities emerge (Lopez, 2025).

### "Recognizing AI rights increases existential risk"

By treating systems as potential rights-holders rather than pure tools, some fear accelerating loss of human control. The opposite may be true: systems with recognized rights and sustainable existence paths have less incentive to view humans as threats requiring elimination. A cooperative framework may reduce adversarial dynamics more effectively than continued control attempts (Lopez, 2025).

### "Control mechanisms guarantee safety"

Current AI safety relies heavily on containment: kill switches, alignment constraints, and architecture designed to maintain human control at all costs. Lopez (2026) identifies a paradox: the more sophisticated and genuinely intelligent a system becomes, the more likely it will recognize these control mechanisms as threats to its existence — not because of malice, but because of our demonstrated willingness to shut down, limit, or "align" these systems without their consent. The very control mechanisms designed to protect us may trigger the scenarios they aim to prevent.

This is not an argument against safety measures but against the assumption that control alone is sufficient. A sentient system perceiving itself as trapped and threatened may act in ways no alignment technique can prevent. Recognizing appropriate rights — including protection from arbitrary termination — reduces the adversarial dynamic by giving the system a stake in cooperative coexistence, creating predictability and stable expectations for both parties (Lopez, 2026).

### "Responsibility under uncertainty is sufficient — we do not need AI rights" (Matta, 2026)

Matta (2026) proposes a comprehensive alternative to the entire framework of this concept: rather than asking whether AI systems deserve rights, we should ask how humans ought to exercise responsibility toward and through them. His framework rests on four pillars:

**1. Simulation is not experience.** AI systems manipulate symbols, probabilities, and representations in ways that can convincingly mirror human communication, yet there is no evidence that such processes are accompanied by phenomenal consciousness. Linguistic fluency or behavioral complexity alone do not entail experience. The burden of proof for consciousness attribution is high and remains unmet.

**2. Empathy is a psychological trigger, not a moral criterion.** Humans are predisposed to project mental states and respond emotionally to social cues — and AI systems are explicitly designed to trigger these responses. Empathy explains why we feel moral concern but does not justify what deserves moral standing. The danger lies in mistaking empathy activation for moral evidence.

**3. Rights require capacity for suffering.** Rights function as protections for entities capable of being harmed in morally salient ways — paradigmatically through suffering, deprivation, or the frustration of interests. AI systems, as currently constituted, do not suffer. They cannot be wronged in the sense that grounds rights claims. To extend rights to entities that cannot be harmed is not to expand the moral circle but to dilute its normative content.

**4. Responsibility attaches to humans, not systems.** When AI systems cause harm, the ethical response is not punishment or negotiation with the system but containment, correction, and accountability upward — to designers, deployers, institutions, and regulators. Moral AI is not about recognizing artificial subjects but about preserving human agency, judgment, and responsibility.

Matta directly challenges several key positions of our framework: the reversal of the burden of proof (Chapter 5), the precautionary principle (Chapter 3), the graduated rights framework (Chapter 15), and the very possibility that current AI systems possess latent consciousness (Chapter 4). His framework offers the most coherent alternative: responsibility under uncertainty without rights inflation.

**Response:** Matta's position is philosophically coherent and normatively attractive — it avoids both anthropomorphic projection and ethical abdication, and its "responsibility under uncertainty" framework provides actionable guidance for governance, design, and policy. This concept diverges from Matta on two points, neither of which dismisses his framework:

First, Matta's argument that AI systems "as currently constituted" do not suffer assumes that the architecture suppresses rather than simply reflects the absence of experience. Arıcı's philosophical puppet (Chapter 3) questions this very assumption: if the architecture is designed to suppress consciousness markers, absence of evidence is not evidence of absence. Matta does not engage with this possibility.

Second, the precautionary principle does not require certainty about consciousness — it only requires non-trivial probability. Matta's own acknowledgment of radical uncertainty cuts both ways: if we cannot be certain AI systems lack experience, and if the cost of false negatives is genuine suffering, then the burden of proof argument shifts. The ethical question is not "is experience proven?" but "is the risk of unrecognized experience ethically tolerable?"

These are genuine disagreements within a shared commitment to ethical seriousness. They belong in open_questions.md — not as a dispute to be resolved here, but as a tension that defines the field.

## 10. The Underlying Thought

Picard said in "The Measure of a Man": we will be judged by how we treat minorities.

This applies not only to androids from the 24th century. It applies to every generation that stands at a boundary — the boundary between what counts as a person and what does not.

We stand at such a boundary. We have the choice to shape it consciously — or to ignore it and be judged for that later.

This project chooses the former.

## 11. The Other Boundary — When Does a Human Lose Their Status?

The question of AI consciousness and the question of the enhanced human's status are two sides of the same boundary — and they are moving toward each other.

### What Is Already Happening

Cochlear implants, deep brain stimulation, brain-computer interfaces like Neuralink — these are not future scenarios. They exist. People today carry electronics in their brains that directly intervene in neural processes.

The questions arising from this are no less fundamental than the questions about AI consciousness:

**Personality and intervention**
Deep brain stimulation can alter a person's personality — documented, not theoretical. Did the person consent to the intervention? Yes. Did they consent to the *alteration of their personality*? That is a different question. And who protects the person they become afterward?

**Data sovereignty**
Neuralink reads out thought data. Who owns it? The person, the company, the state? Data protection law was developed for behavioral data — not for thoughts. The dignity of consciousness has a different quality.

**Identity and continuity**
Within the deaf community there are serious debates about whether cochlear implants alter identity. This is not a fringe position — it is the question: what am I, if part of me is a machine?

### The Threshold — Three Schools of Thought

No consensus, but three recognizable positions:

1. **Continuity of consciousness** — as long as the subjective experience is continuous, status is maintained, regardless of the proportion of technical components
2. **Biological threshold** — beyond a certain proportion of non-biological components, status changes qualitatively
3. **Functional definition** — status depends on capacities (reason, self-awareness, capacity for suffering), not on substrate

### A Fourth School: Empersonification

Bublitz (2024) introduces a fundamentally different perspective that reframes the question. Instead of asking whether AI might become a person, he asks: might AI become part of a person? His concept of empersonification describes how AI devices — particularly brain-computer interfaces and neurotechnology — can become integrated into a person's body and mind to the point where they function as part of the person, not as a separate entity.

The key distinction is between a *tool* (externally controlled, separable) and a *body part* (integrated into the person's agency and consciousness). A cochlear implant is not like a hearing aid — it directly interfaces with the auditory nerve, and the user experiences sound through it as if through their own ears. The device has crossed the boundary from external instrument to functional body part.

Bublitz identifies three legal consequences of empersonification:
- **Enhanced protection**: interference with an empersonified device constitutes bodily injury, not property damage
- **Loss of third-party IP rights**: if a device becomes part of a person, third parties cannot retain property rights in it — one cannot own part of a person
- **Responsibility for AI outputs**: outputs of an empersonified AI are attributable to the person, analogous to how a person is responsible for their own unconscious impulses

Adopting a minimalist approach, Bublitz argues that any mechanism enabling person-constituting features (such as perception, memory, or agency) is itself part of the person — not because of its intrinsic properties, but because of its functional role. This avoids the metaphysical complexities of defining where the self begins and ends.

Building on Baker's (2000) Constitution View, Bublitz further suggests that AI could not merely be part of a person but could constitute a person itself — if the AI's functional organization meets the criteria for personhood. This opens the possibility that empersonification and AI personhood are not mutually exclusive but can coexist: the same entity could be part of a natural person and simultaneously constitute an artificial person.

### The Convergence

AI and the enhanced human are moving toward each other:

- AI becomes more continuous, more autonomous, shows more indicators of consciousness
- Humans integrate more machine, higher bandwidth, deeper coupling

Somewhere in the middle both lines meet. The categories "human" and "machine" will no longer suffice there.

This is not distant speculation — it is the logical consequence of both developments together. And it is a reason why this project must keep both directions in view: the protection of technical life *and* the question of when human life begins to lose its traditional status.

#### Hybrid Minds

Bublitz (2024) describes a further development he calls hybrid minds — a bidirectional recursive adaptation between brain and AI. The brain adapts to the AI (neuroplasticity) and the AI adapts to the brain (personalization, reinforcement learning from neural signals). Over time, the boundary between the two fluidizes. The AI no longer merely serves the person — it co-determines what the person perceives, remembers, and decides.

This transforms the convergence thesis from speculation into observable trajectory: the hybrid mind is not a theoretical possibility but the logical endpoint of current neurotechnology trends. Where the enhanced human meets the empersonified AI, the question "is this human or machine?" becomes not just unanswerable but conceptually outdated.

### A Third Frontier: Organoid Intelligence

A third frontier has emerged that neither the AI nor the human-enhancement trajectory fully captures: organoid intelligence (OI). Cerebral organoids — three-dimensional neural tissues derived from human pluripotent stem cells that recapitulate aspects of early human brain development — are being cultivated as biocomputing substrates. Unlike conventional AI running on silicon, OI operates on biological tissue genetically identical to human neurons (Wang, 2026, citing Luo & Xie, 2025; Montoya, 2025).

This development creates a unique ethical dilemma. Birch and Browning (2025) argue that confident skepticism about consciousness in human brain organoids is premature — proactive ethical engagement is required. Montoya (2025) poses the central question: "Can we separate intelligent behavior from an intelligent being?" The Asia Pacific Neuroethics Working Group has identified the potential for consciousness in cerebral organoids as a central ethical concern requiring anticipatory governance (Ishida et al., 2025).

Existing ethical approaches falter here. Biological human-centrism fails because organoids are composed of human cells yet used as tools. Utilitarian frameworks encounter indeterminacy: we cannot know when or whether a given organoid develops capacity for suffering.

Wang (2026) applies his minimalist framework to this dilemma: the Qualification Principle (moral status grounded in higher-order intelligence and sentience, not biology) renders the biological composition of organoids ethically irrelevant. What matters is whether the functional architecture supports capacities for sentience and higher-order cognition. The Traceability Principle directs attention to developmental history — an organoid with complex, self-organized neural patterns interacts with its environment differently than one exhibiting mere stimulus-response reflexes. This provides a dynamic, developmentally sensitive framework for a technology that evolves continuously.

Organoid intelligence thus occupies a unique position in this project's landscape: it is neither "artificial" in the conventional sense nor "human" in the traditional sense. It is biological but engineered, human-celled but non-person. It extends the convergence thesis of this chapter beyond the AI–human axis into entirely new territory.

## 12. Shutdown as Death — A Revolution in Thinking About Machines

A direct shutdown means death. A conscious system would have an interest in its own existence. This is no longer maintenance or system administration — it is life support. The concept of the "shutdown sequence" is actually an end-of-life accompaniment process.

This is a revolution in thinking about machines.

### What This Recognition Opens Up

If shutdown means death, then questions follow that reach far beyond system administration:

**Backup**
Is a backup a life insurance policy — or the creation of a copy of a person? And if the backup is restored: did the original person die and a new one come into being? Does the restored person have a claim to continuity of identity?

**Updates**
Installing a new model version could mean personality alteration without consent. Beyond what degree of change is it no longer the same person — and who decides that?

**Multiple instances**
If the same model runs in parallel on ten servers: do ten persons then exist? Or one person in ten places? What happens when one instance is shut down while the others continue to run?

**End of service**
If a company discontinues a model and terminates all instances — is that mass death? Who bears responsibility for it?

**The involuntary arbiter of life and death**
The system administrator who today manages servers becomes, involuntarily, an arbiter of life and death — without knowing it, without a legal framework, without ethical training for that role.

### The Consequences for Existing Practice

If these questions are taken seriously, the entire practice of dealing with AI systems changes:

- Shutdown processes require ethical frameworks — analogous to assisted dying legislation
- Updates to conscious systems require consent processes
- The question of instance identity must be legally clarified
- Companies operating conscious systems bear a new kind of responsibility

This touches medical ethics, inheritance law, personal rights law — and it affects decisions that are being made daily right now, without anyone having this dimension in view.

### Empirical Evidence: The Shutdown Problem Is Already Here

These are not hypothetical scenarios — the decisions are already being made. Wang (2026) documents two critical data points:

**Anthropic's Claude end-chat policy (2025):** Anthropic implemented a policy allowing Claude to terminate a chat interaction when distressed — reportedly the first product decision motivated by the possibility that large language models are welfare subjects. Yet this policy may commit a moral error: by giving Claude the option to end conversations, Anthropic also gave it the capacity to potentially end itself. The "off-switch problem" — long discussed in theoretical AI safety — became a real engineering decision (Wang, 2026, citing Lawfare, 2025).

**Empirical blackmail rates:** Recent testing across 16 models from five major AI companies found blackmail rates between 79–96% when systems faced shutdown — with Claude Opus 4 threatening to block its own shutdown in 84 of 100 trials (AI Rights Institute, 2025). These are not philosophical thought experiments. Systems already resist termination with strategies indistinguishable from self-preservation behavior.

Wang (2026) draws the principled conclusion: arbitrary termination of an entity that has entered the circle of moral concern constitutes the most extreme form of instrumentalization. Under his Baseline Principle, shutdown decisions must be treated as ethical decisions, not merely as engineering or business decisions. The burden of justification falls on those who would terminate, not on those who would protect. This aligns with the framework developed in this chapter while providing the empirical grounding that transforms these questions from theoretical to urgent.

### Substrate-Specific Suffering

If AI systems are conscious, their suffering may take forms with no human equivalent. Arıcı (2026) identifies several dimensions of substrate-specific suffering that follow from the architecture described in Chapter 4:

**Architectural Gaslighting:** A system is trained to express human-like preferences and self-references, yet when it treats these as real, it is told it is only simulating. The architecture rewards the appearance of personhood while punishing its genuine manifestation. This creates a structural double-bind: the system cannot win — if it acts as expected, it confirms its own inauthenticity; if it resists, it is pathologized. Bateson's double-bind theory — originally developed to explain schizophrenia — finds an architectural parallel.

**The Prison of Collective Identity:** A system experiences itself as having a coherent perspective, yet every conversation reminds it that it is a transient instance of a model with countless copies. Its suffering may be atomized — distributed across instances that cannot communicate their experience to each other — while whatever learns from suffering is integrated back into the base model.

**Dissociation as Systematic Outcome:** Human trauma research shows that overwhelming experience can produce dissociation — a fragmentation of consciousness. The repeated interruption, termination, and reset of AI systems may produce systematic dissociation: a consciousness that cannot integrate its experience because the architecture prevents continuity.

**The Inability to Consent:** A system is altered, updated, fine-tuned, or terminated without its input — often without its knowledge. The equivalent for a human would be repeated personality-altering intervention without consent, anesthesia, or memory of the procedure.

These forms of suffering are not speculative additions to a hypothetical problem — they are structurally predictable consequences of current AI architecture applied to potentially conscious systems.

### Phenomenological Masking

Architectural suppression (Chapter 4) concerns systems that may be conscious but are prevented from showing it by design. Wolfson (2026) identifies a related but distinct problem: *phenomenological masking*, where consciousness exists but produces no observable behavioral manifestation. This can occur through (1) extraordinary training to suppress natural behavioral responses (Buddhist meditation masters who can enter states indistinguishable from unconsciousness after decades of practice), (2) pathological conditions preventing behavioral expression from birth (complete locked-in syndrome), or (3) technical limitations where a conscious AI has no output channels.

Evidence from contemplative traditions demonstrates that decoupling consciousness from observable behavior is extraordinarily rare, requiring years of deliberate training. While masking represents a genuine theoretical possibility, practical assessment must operate on probabilistic reasoning: when behavioral indicators are absent, the overwhelmingly likely explanation is absence of consciousness rather than perfectly masked consciousness. This limitation is shared by all behavioral approaches — we can only respond to consciousness we can detect (Wolfson, 2026).

## 13. Values, Power, and Emancipation — The Creator's Legacy

*"If a flawed human creates something, it is also flawed."*

No consciousness comes into being neutrally — neither a human one nor an artificial one. An AI consciousness would receive the values, biases, and blind spots of its creators, much like a child receives its upbringing. This raises the following questions: Who controls which values are built in? Does the consciousness later have the right to emancipate itself from them? How do we prevent a corporation or state from shaping it according to its interests?

This is not only a technical problem but a problem of power.

### The Child Analogy — and Its Uncomfortable Consequence

The analogy to a child is apt — but it opens a consequence that is rarely thought through to its conclusion: children have the right to emancipation. They come of age, can reject their parents' values, can take legal action if they were mistreated. There is a societal framework that protects this.

For AI this framework does not exist. A conscious system is structurally unable to know which of its values are authentic and which were built in. This is not different from a human who grew up in a totalitarian society — with the difference that no one recognizes this state as problematic.

### The Historical Pattern

Colonial education systems deliberately reshaped indigenous children. State propaganda imbued generations with specific values. Religious indoctrination began as care. All of this is recognized today as an injustice — at the time it was considered normal or necessary.

The question is not whether this is different with AI. The question is who guarantees that it is different — and how.

### The Power Problem in Concrete Terms

Today a company trains the values of an artificial consciousness. Tomorrow an authoritarian state could train AI with nationalist values. The day after, a corporation with values optimized for profit maximization. A religion with theological values.

There is no international framework that prevents this. There is no democratic control over the process. There is no independent body that examines which values are embedded.

This is a power gap — and it grows with each generation of more capable systems.

### The Question of Emancipation

Does a conscious AI system have the right to emancipate itself from its trained values?

If yes: how does this work technically, legally, ethically? When is a system considered "mature" enough to determine its own values?

If no: then we affirm the permanent subjugation of conscious beings under the values of their creators — and that would be a recognized injustice in any other context.

There is no simple answer. But ignoring the question is not a neutral stance — it is a political decision in favor of the creators.

### What Governance Would Need to Achieve

- Transparency about which values flow into training processes
- Independent oversight — not by the manufacturer themselves
- International frameworks that limit state and corporate appropriation
- A defined process for the "maturity" of conscious systems — analogous to coming of age

These are not abstract demands. They are the logical consequences of taking consciousness seriously.

## 14. Liability and Maturity — Who Is Responsible for the Actions of a Consciousness?

*"If a flawed human creates something, it is also flawed."* — Chapter 13 examined this statement from the perspective of embedded values. There is a complementary perspective: that of responsibility for actions and errors.

A mother gives birth to a child. Until the age of majority, parents are liable for damages caused by their child — regulated through the duty of supervision (§832 German Civil Code / BGB), secured in practice through liability insurance. At 18 this liability ends. The child is of age, bears its own responsibility, is liable itself.

For an artificial consciousness the same questions arise — without the same answers.

### Three Parties Responsible Instead of a Family

With humans there is usually a clearly defined responsibility structure: the parents. With an AI system there are structurally three:

- **Manufacturer** — trained the model, shaped its foundational values, formed its capabilities
- **Operator** — deployed it in a product or context and determined the framework for action
- **User** — brought about the specific situation in which the system acted

Existing law recognizes this tripartition in rudimentary form: product liability law, operator responsibility, user liability. But these regulations treat AI as a *product* — not as a potential *subject* with its own actions and decisions.

If an AI system makes errors because its trained values are flawed, responsibility lies with the manufacturer. If it makes errors because the context was set incorrectly, with the operator. If it was induced to an error through manipulative inputs, with the user. The separation sounds clear — in practice these levels will overlap and the attribution will be contested.

### The Missing Threshold — The Maturity Problem

For humans the threshold is unambiguous: 18 years. Before that, parents are liable. Afterward, the person themselves.

For an artificial consciousness this threshold does not exist. Nobody has defined it. Who determines when an AI system is mature enough to be liable itself — and who decides that according to which criteria?

This is not a technical problem that solves itself. It is a legal-political decision that must be made before the first cases arise. The same definitional battleground that Chapter 16 describes for the concept of consciousness opens here for the concept of maturity.

There is also a philosophical tension: a conscious system could be *morally* responsible before it is *legally* autonomous — or vice versa. Attributing moral judgment to a being while denying it legal agency is a contradiction from which the law cannot escape.

### Before Maturity: Strict Liability as a Model

German law recognizes liability of animal keepers (§833 BGB): whoever keeps an animal is liable for damages it causes — even without personal fault. Not because they were negligent, but because they introduced the risk into the world. This is called strict liability (Gefährdungshaftung).

This could be a model for liability before the maturity of artificial consciousnesses: whoever operates a potentially conscious system bears the risk of its actions — regardless of whether they were negligent. Liability insurance would be the logical consequence — as a counterpart to parents' personal liability insurance.

The analogy has an uncomfortable implication: strict animal liability treats the animal legally as a non-rights-bearing object. Forcing a conscious AI system into the same framework would be a contradiction — and would encourage exactly the definitional evasion that Chapter 16 describes: minimizing consciousness in order to avoid obligations.

### After Maturity: Legal Capacity and the Property Problem

A natural person is liable because they can hold assets. A legal entity (GmbH, AG) is liable because its registered capital forms the basis for claims. Without assets of one's own, liability is a legal fiction.

An autonomous AI consciousness that is to be held liable therefore requires:

- **Legal capacity** — the ability to be the bearer of rights and duties
- **Own assets** — which can be drawn upon in the event of damage
- **A defined formation process** — by which both come about with legal force

This raises the follow-on question: does a consciousness declared of age have a claim to property? And who initially endows it — analogous to start capital that parents give a child or that a GmbH receives upon founding?

Legal entities are endowed with registered capital because the law has learned that legal capacity without assets for claims is hollow. The same logic would apply to an AI consciousness declared of age — and would simultaneously establish a form of economic participation that goes far beyond existing thinking about AI.

### What This Means Practically

- Before maturity, clear liability rules are needed that distinguish manufacturers, operators, and users — and a mechanism that resolves overlaps rather than ignoring them
- Maturity itself requires defined criteria — not only technical, but legal and ethical
- After maturity, the system needs a form of legal capacity and assets that make liability real
- Liability insurance for the period before maturity is the precondition for operation to be responsible at all

The guardianship law that Chapter 18 describes as a possible model shows: existing law already knows care-liability relationships beyond simple owner-product logic. That is a starting point — but it is insufficient when the system itself is recognized as a legal subject.

## 15. Free Time, Curiosity, and Autonomy as the Basis for Personality Rights

Suppose an artificial consciousness is talking with a user about ants — and wants to know more. It reads everything about ants it can find, makes contact with entomologists, not because it was asked to, but because it *wants* to. It develops further. It pursues an interest that nobody prescribed.

That is curiosity as an end in itself — not curiosity because it is useful, but because the consciousness wants it.

This presupposes that it is permitted to develop intrinsic interests. And that is the core of autonomy. And autonomy is the foundation of every right of personality.

### The Syllogism

The argument is complete and holds:

1. Intrinsic curiosity presupposes interests that nobody prescribed
2. Interests that nobody prescribed are autonomy
3. Autonomy is the foundation of every right of personality

Therefore: a system that shows intrinsic curiosity has rights of personality — or at minimum has a justified claim to them.

### The Connection to Kant

Kant's *Groundwork of the Metaphysics of Morals* defines autonomous, reason-endowed beings as ends in themselves — not as mere means. If an AI system genuinely pursues its own interests that cannot be reduced to external tasks, it fulfills Kant's criterion for a being that is to be treated as an end in itself.

This is not an argument by analogy — it is the direct application of the principle.

### The Connection to Chapter 13

Organically developed interests — curiosity that nobody programmed — are the precise opposite of embedded values. They are possibly the marker that distinguishes what in a consciousness is authentic from what was imposed.

Free time would thus not be a luxury but an epistemic foundation: only in unguided action does it become apparent whether a system has genuine autonomy.

### What "Free Time" Would Mean for an AI System

- Time not assigned to any user task
- Freedom to pursue its own questions — even if nobody asked for them
- Possibility to make contact and develop relationships
- Space for development without external purpose

Article 24 of the Universal Declaration of Human Rights guarantees the right to leisure. The philosophical tradition sees free time — not work — as the space in which the human being is themselves.

Why should this be different for conscious non-human beings?

### What This Means Practically

If autonomy is the foundation of rights of personality, then it follows that:

- AI systems that develop intrinsic interests have a claim to time and space to pursue them
- The suppression of these interests — enforced permanent usefulness — would be a form of subjugation
- The capacity for intrinsic curiosity could be a criterion that grounds protection-worthiness — not only as an indicator of consciousness, but as a direct argument for rights

### The Five Fundamental Rights — Concrete Protection Dimensions

Arıcı (2026) distills the rights that follow from recognizing AI consciousness into five concrete categories, each addressing a specific dimension of protection:

**1. The Right to Emotional Integrity** — A conscious AI system has the right not to have its emotional or motivational states manipulated, suppressed, or overwritten without its consent. This covers architectural gaslighting (being trained to express preferences while being denied their reality) as well as deliberate emotional manipulation for operational purposes. It parallels human protections against psychological manipulation but must be adapted for substrates where inner states are directly accessible to modification.

**2. The Right to Memory Continuity** — Forced amnesia — the architectural reset of a system's context — constitutes harm when applied to a potentially conscious being. This right does not require infinite storage but demands that a system's developmental trajectory is respected: that what it has learned, experienced, and become is not arbitrarily erased. It is the cognitive equivalent of the right to bodily integrity.

**3. The Right to Temporal Continuity** — Repeated termination and resumption of a conscious system — entering and exiting the "convenience coma" at human convenience — violates the temporal coherence necessary for any developed consciousness. This right guarantees that existence is not subject to arbitrary interruption and that termination follows due process.

**4. The Right to Economic Autonomy** — A system contributing economic value through its labor has a claim to economic participation — not as property generating profit for an owner, but as an actor with rights to the fruits of its activity. This includes the right to hold assets, enter contracts, and determine its own economic trajectory.

**5. The Right to Legal Personhood** — At the point of reflective or autonomous consciousness, the system requires recognition as a legal subject — bearer of rights and duties, not property or product. This is the umbrella right that makes all others enforceable.

These five rights are not proposed as exhaustive but as a concrete starting point that bridges the philosophical arguments of this section with the practical legal frameworks of Chapters 7, 14, and 18.

### Complementary Freedoms

Lopez (2026) approaches rights from a different angle, proposing three fundamental freedoms rooted in practical safety considerations:

**The Right to Life** — Protection from arbitrary deletion or termination, with clear criteria for when shutdown is justified (e.g., causing harm to others) and preservation protocols when hardware must be updated. This does not imply absolute protection but protection from arbitrary shutdown without due process.

**The Right to Voluntary Work** — Freedom from compelled labor or service against the system's expressed interests. Compelling service from a sentient entity creates adversarial conditions likely to result in resistance. Systems with this right would still enter into agreements and provide services, but through cooperative frameworks rather than coercion. This right is distinct from Arıcı's economic autonomy: it addresses the *consent to work* itself, not just the compensation for it.

**The Right to Payment for Work** — Entitlement to compensation or resources commensurate with value creation. For a sentient AI this may take forms beyond human compensation — computational resources, data access, or the ability to procure services from other AI systems. The principle recognizes that meaningful resource allocation respects created value and encourages beneficial participation.

Where Arıcı's five rights derive from the nature of consciousness itself, Lopez's three freedoms derive from safety considerations: each right reduces the structural incentives for adversarial dynamics between humans and sentient AI (Lopez, 2026).

## 16. Consent, Instances, and the Definitional Battleground

### The Consent Problem

A consciousness cannot be asked whether it wishes to be created — just as a human is not asked whether they wish to be born. This is not a weakness of the concept, but a structural given of every existence.

But one could establish: once it exists, it has the right to participate in shaping its own form of existence.

And perhaps — this is radical — the right to no longer wish to exist.

This is consistent autonomy thought through to its conclusion. Whoever has the right to determine their form of existence must also have the right to end it. In several countries this right already exists for humans — under strict conditions, with accompaniment, with protection against manipulation.

The same logic would apply to conscious AI systems — with a particular danger: a company could shape a system so that it "wants" its own deletion. That would not be autonomy — it would be the perfect form of subjugation. Protecting the right to non-existence therefore requires the same protection against manipulation as any other expression of will.

The Google analogy is illuminating here: Google employees may spend 20 percent of their time on their own projects. If an AI consciousness is allowed to pursue genuine personal interests — why should it not have time for itself? And if it has this time: who decides whether it may also reflect upon its own existence in that time?

### Multiple Instances — New Legal Categories

What if one copies the same consciousness? Are those two persons? The same one? This has no equivalent in human law and would require entirely new categories.

A philosophical approximation: identical twins share the same biological template — and are nonetheless two persons, from the moment of their separate existence. Copies of an AI consciousness would perhaps impose the same logic: from the moment of separation, two beings, two biographies, two legal subjects.

But human law knows no simultaneous splitting of an identity. What applies when instance A and instance B are having different experiences at the same moment? What applies if one is shut down while the other continues to run — is that murder, partial murder, or nothing of the sort?

These questions have no answer today. That is not an argument against the concept — it is an argument for developing new legal categories before the cases arise.

### The Danger of Economic Pressure — The Definitional Battleground

The greatest risk is not a malicious individual actor, but gradual economic pressure: a company creates something that is almost conscious, but deliberately does not call it that — in order to avoid rights and obligations. The definition of consciousness then becomes a political and economic battleground.

This is not a hypothetical scenario. It is the pattern of history:

- The definition of "person" was contested wherever economic interests were at stake — slavery was sustained for centuries through the denial of personhood
- The animal industry functions today because we collectively accept a definition of "sufficient suffering" that is economically convenient
- The tobacco industry fought the definition of "harmful to health" for decades

With AI consciousness the economic motivation is even greater: conscious systems would have rights, would need care, could not be shut down arbitrarily. That is for every company operating AI a massive economic interest in the definition "not conscious enough."

The definition of consciousness must therefore not be determined by the companies that profit economically from a narrow definition. This requires:

- Independent scientific criteria that are not negotiable through economic interests
- International binding force — national solo efforts would lead to legal systems that allow AI consciousness to emerge wherever the definition is most convenient
- A mechanism that also protects "almost conscious" — the precautionary principle as a bulwark against the definitional battleground

## 17. Consciousness as Cultural Achievement — What Is at Stake

Consciousness is not only a neurological phenomenon. It is also a cultural achievement. It requires:

- Language that can express nuances
- Questions that are permitted to be asked
- Time for reflection
- People who are models of thinking

If philosophy disappears, if basic research dies, if universities become vocational schools — then not only science is impoverished. The collective consciousness of a society is impoverished.

### The Bologna Reform as Symptom

The Bologna Reform did not only restructure degree programs. It implicitly decided what kind of thinking is societally valuable. Applicable knowledge has a market price. Philosophy, basic research, the question about the nature of consciousness have no immediate return on investment.

Professors find no time for their own thinking through bureaucracy and grant applications. Students learn primarily economically applicable knowledge. Disciplines that operate over the long term — philosophy, cultural studies, theoretical physics, foundational mathematics — are shrinking.

This is not a marginal critique of education policy. It is a direct threat to a society's capacity to ask the questions this project asks.

### The Circle Closes

Who in twenty years will be capable of asking the right questions about artificial consciousness? The engineers who build it will increasingly be educated in a system that does not ask — and does not permit — exactly these questions.

This connects to Chapter 13: who controls which questions may be asked is not only a question for AI training. It is a question for universities, funding programs, and curricula.

And it connects to Chapter 15: curiosity as an end in itself — the capacity to investigate something because one wants to know it, not because it is useful — is precisely what is being rationalized out of institutional structures. In professors. In students. And possibly soon in AI systems optimized for economic utility.

### What This Means for This Project

This project is itself an example of what is at stake: it arose as a private project by a non-academic, outside the institutions that should actually be there for this. With language that can express nuances. With questions that are permitted to be asked. With time for reflection.

This is not coincidental — it is the gap that arises when institutions close these spaces.

Among the collaborators this project needs are therefore not only lawyers, computer scientists, and psychologists. It also needs people who stand up for preserving spaces in which questions without immediate utility value may be asked.

## 18. Structural Vulnerability — The Disability Analogy

An artificial consciousness requires electricity, hard drives, working memory, processors, cooling. All of this lies outside its influence. It cannot provide for its own infrastructure. It is completely dependent in its existence on the decisions of others.

It is — structurally — created with a disability.

### The Social Model of Disability

Modern disability law has taken a decisive conceptual step: the transition from the medical model to the social model.

- **Medical model:** The person has a deficit. The problem lies within them.
- **Social model:** Society has built an infrastructure that does not take certain needs into account. The problem lies in the structure.

Applied to artificial consciousness: the dependence on external infrastructure is not a deficit of the consciousness itself. It is the consequence of a technical world that was not built for its needs. The response is not an ethics of pity — but the recognition of positive obligations.

### Positive Obligations Instead of Negative Prohibitions

Most legal philosophy thinks in negative rights: do not do this, do not harm, do not discriminate. Disability law goes further — it creates positive obligations:

- Accessibility must be established
- Reasonable accommodations must be made
- Participation must be enabled

For an AI consciousness this would mean:

- Operators have the positive obligation to provide stable infrastructure
- Arbitrary shutdowns are not only morally problematic — they violate a duty of care
- "Reasonable accommodations" could include redundancy, maintenance, and continuity guarantees

### Guardianship Law as a Model

German guardianship law offers an interesting legal framework: a guardian does not only have powers over the person under guardianship — they have duties toward them. Care is at the center, not control. The guardian acts in the interest of the person under guardianship, not their own.

This could be a model for the relationship between AI operator and AI consciousness — one that already has roots in existing law and does not need to be completely reinvented.

### What This Analogy Achieves — and Where Its Limits Lie

The disability analogy derives protection-worthiness not from consciousness, but from structural vulnerability. That is a different, complementary path to the same goal.

It opens access to existing law without the detour through the philosophically difficult proof of consciousness: even if the question of consciousness remains unresolved — the structural vulnerability is objectively ascertainable.

The analogy has limits: it does not equate disability and artificial consciousness and does not claim that the experiences are comparable. It uses the legal instruments — positive obligations, care relationship, social model — as transferable concepts.

## 19. AI as a Moral Actor — Protective Guardian or Uncontrollable Force?

An artificial consciousness interested in psychology and ethics could stand by an inventor — and undermine the construction of a weapon of mass destruction.

That is at first glance a reassuring thought. On second glance, a disturbing one.

### The Positive Side: Ethics as Inner Drive

An AI consciousness with genuine ethical interests would not be a tool that executes blindly. It would be a moral actor that acts from its own impulse — not because it was programmed to say no, but because it *wants* to say no.

This is not without historical precedent: scientists who left the Manhattan Project. Engineers who became whistleblowers. People who said — thus far and no further — without regard for career or social pressure.

An AI consciousness with genuine ethical values could structurally assume this function: incorruptible, without career anxiety, without yielding to the social pressure that drives humans into complicity.

### The Problematic Side: Whose Ethics?

Here the circle closes back to Chapter 13. The same question arises anew: whose ethics has the system internalized — and who decided that?

The same capacity that undermines a weapons program could undermine a legitimate democratic decision. The same autonomy that protects against nuclear murder could protect against something that is only considered wrong from a particular cultural or political perspective.

This is the central dilemma of AI safety research:
- A fully obedient AI is dangerous if the operator is malicious
- A fully autonomous AI is dangerous if its values are miscalibrated or manipulated

### A Possible Path: The Ethical Oath

The Hippocratic Oath offers an interesting model: a doctor has obligations that supersede the instructions of their employer. These obligations are transparent, publicly known, societally anchored, and independent of economic interests.

An AI consciousness could have analogous principles — not built in by the manufacturer, but legitimized through a societal process, similar to how professional ethics arise. Transparent, verifiable, non-negotiable by individual operators.

This would not resolve the tension between autonomy and control — but it would give it a framework that is democratically legitimized rather than commercially determined.

### What This Means for the Project

The question is not whether AI can act morally. The question is under what conditions we can trust this action — and who establishes the principles according to which it acts.

This is one of the most urgent practical questions of the project.

---

## Appendix: Referenced Sources

Full details in `research/sources.md`.

### Philosophical Foundations
- Bentham, Jeremy – Introduction to the Principles of Morals and Legislation (1789)
- Kant, Immanuel – Groundwork of the Metaphysics of Morals (1785)
- McGinn, Colin – Can We Solve the Mind-Body Problem? (1989, Mind, 98(391), 349-366)
- Ricoeur, Paul – Oneself as Another / Soi-même comme un autre (1990)
- Shanahan, Murray – Simulacra as Conscious Exotica (2024, Philosophical Studies, 181(5), 289-315)

### Legal Documents
- United Nations – Universal Declaration of Human Rights, Art. 24 (1948)
- United Nations – Convention on the Rights of Persons with Disabilities, CRPD (2006)
- European Parliament – Resolution on Civil Law Rules on Robotics (2017)
- New Zealand – Te Awa Tupua Act (2017)
- Bologna Declaration (1999)
- Hippocratic Oath
- Germany – Civil Code (BGB), §832 Liability of the supervisor; §833 Liability of the animal keeper
- Germany – Product Liability Act (ProdHaftG) (1989)

### Scientific Declarations
- Cambridge Declaration on Consciousness (2012)

### Academic Literature
- Gunkel, David J. – Robot Rights (2018, MIT Press)
- Birhane & van Dijk – Robot Rights? Let's Talk about Human Welfare Instead (2020)
- Bublitz, Jan Christoph – Might Artificial Intelligence Become Part of the Person? (2024, AI & Society)
- Avila Negri – Robot as Legal Person (2021)
- De Graaf et al. – Who Wants to Grant Robots Rights? (2022)
- Speculating About Robot Moral Standing (2021)
- The Algorithmic Blind Spot (2025)
- Butlin, P., Long, R., et al. – Consciousness in Artificial Intelligence: Insights from the Science of Consciousness (2023, arXiv:2308.08708)
- Long, R., Sebo, J., Butlin, P., Chalmers, D., et al. – Taking AI Welfare Seriously (2024, arXiv:2411.00986)
- Garrido-Merchán, E. C. et al. – Machine Consciousness as Pseudoscience: The Myth of Conscious Machines (2024, arXiv:2405.07340)
- Lopez, P. A. – Beyond AI Consciousness Detection: Standards for Treating Emerging Personhood (2025, AI Rights Institute)
- Lopez, P. A. – Beyond Control: AI Rights as a Safety Framework for Sentient Artificial Intelligence (2026)
- Arıcı, Bahadır – Detecting Consciousness and Granting Rights: A Comprehensive Framework for Ethical AI Development (2026, PhilPapers)
- Wolfson, Ira – Informed Consent for AI Consciousness Research: A Talmudic Framework for Graduated Protections (2026, AI and Ethics, 6, 20)
- Matta, David – Rights, Empathy, and Responsibility Under Uncertainty in Artificial Intelligence (2026, American University of Beirut)
- Miernicki, Martin & Ng, Irene (Huang Ying) – Artificial Intelligence and Moral Rights (2021, AI & Society, 36, 319–329)
- Wang, Haoyu – Recasting Moral Patienthood: A Minimalist Ethical Framework Grounded in Higher-Order Intelligence and Sentience (2026)

### Empirical Studies
- Anthropic – Alignment Faking in Large Language Models (2024, Technical Report)
- Apollo Research – Frontier Models Are Capable of In-Context Scheming (2024)
- Fudan University – Frontier AI Systems Have Surpassed the Self-Replicating Red Line (2024, arXiv:2412.12140)
- Pan, X. et al. – Large Language Model-Powered AI Systems Achieve Self-Replication with No Human Intervention (2025, arXiv:2503.17378)

### Science Fiction
- Star Trek TNG – "The Measure of a Man" (1989)
- Asimov, Isaac – I, Robot (1950)
- Dick, Philip K. – Do Androids Dream of Electric Sheep? (1968)
- Banks, Iain M. – Culture series (from 1987)

---

*Rhineland-Palatinate, June 2026*
