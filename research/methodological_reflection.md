# Methodological Reflection

## 1. Research Approach

The project "Ethical Guidelines for Artificial Consciousness" follows a **conceptual-philosophical approach** — no empirical data are collected; rather, normative arguments are developed, concepts are sharpened, and ethical frameworks are designed. In technical terms, this is called: **Conceptual Analysis**.

This approach is an established scientific method in philosophy and adjacent disciplines. It is particularly suited to questions in which the central concepts are not yet stable — as in the case of machine consciousness, where there is not even consensus on what "consciousness" could mean in a machine.

**Limitation:** Conceptual Analysis cannot establish empirical facts. But it can clarify which normative conclusions can be drawn from empirical findings — and under what conditions.

**Usage of AI:** AI helped while working in this project. My work based on the german concept. The english concept and also the Books under 'publications'  was synchronized automatically with AI. AI helped with the pre-selection and screening of sources. The sources were selected manually using the procedure described in the "Literature Review". AI regularly searches the source file for preprint publications what was published.
Sadly i don't speak english very well, so i developing my ideas and articles in the german language. So i'm using AI for translating some articles into the english language.

## 2. Literature Review

### 2.1 Initial Search

The starting point of the concept was key works on the robot rights debate (Gunkel 2018, Birhane & van Dijk 2020). From these, search-based extensions developed via related works, citations, and specialist databases.

**Databases and tools used:**
- **Google Scholar** — primary source, with automatic notifications (alerts)
- **PhilPapers** — for core philosophical literature
- **arXiv** (cs.AI, cs.CY, stat.ML) — for technical prior work and current research
- **Semantic Scholar** — for citation tracking

### 2.2 Ongoing Search

The search is **iterative and processual**: New findings change the research question and thereby the search direction. This approach is characteristic of Conceptual Analysis (Boon & van Baalen 2019) and differs from systematic reviews, in which the search strategy is fixed in advance.

**Active Google Scholar alerts (as of September 2026):**

| Keyword | Language | Area covered |
|---|---|---|
| "AI ethics" | English | Ethical frameworks, governance, fairness |
| "machine rights" | English | Legal/personal status of AI systems |
| "artificial consciousness" | English | Consciousness in non-biological systems |
| "moral status of AI" | English | Normative status of AI systems |
| "machine sentience" | English | Sentience in machines |
| "AI welfare" | English | Well-being of AI systems |
| "phenomenal consciousness artificial systems" | English | Phenomenal consciousness in artificial systems |
| "AI rights legal framework" | English | Legal frameworks for AI rights |

The alerts deliver new hits weekly. Each hit is reviewed for its relevance to the concept. Relevant works are documented in `research/sources.md` and — if they introduce new aspects — integrated into the concept paper.

### 2.3 Citation Tracking (Backward/Forward Search)

For key works, a systematic procedure is used:
- **Backward search:** Which sources does this work cite? (via Google Scholar "Cited by")
- **Forward search:** Who has cited this work since its publication? (via citation notifications)

This procedure ensures that not just individual works but entire research lines are captured.

### 2.4 Deliberate Inclusion of Contrary Evidence

A central quality feature of this project is the **systematic inclusion of opposing positions**. The concept paper documents not only confirming but also contradicting evidence:

| Opposing position | Source | Treatment in the concept |
|---|---|---|
| AI cannot be conscious (architectural arguments) | Azevedo 2026 | Own section (Chapter 9), engagement |
| Agnosticism with inverted burden of proof | Almodarresieh 2026 | Own section (Chapter 9), demarcation |
| Weakness of self-reports as evidence | Metzinger (C-fallacy) | Integrated into Chapters 3 and 5 |
| Critique of the anthropocentric perspective | Fazi 2026 | Methodological decision: use as a tool without metaphysical claim |

**Justification:** Opposing positions are not ignored but used as learning opportunities. Engaging with critical objections strengthens one's own argumentation and makes the concept more resilient.

### 2.5 Targeted Critique Requests from Source Authors

Beyond the passive inclusion of opposing positions (Section 2.4), criticism is actively solicited from the authors whose work is most deeply embedded in the concept. Authors with the strongest chapter-level connection to the concept are approached with one concrete, answerable question per request — with the explicit goal of their strongest objections rather than endorsement ("criticism instead of agreement").

The contact proceeds in sequential waves: deeply embedded constructive voices first, explicit critical voices second, and prominent names only after own publications. Lessons learned between the waves inform the next wave. The operative contact strategy — prioritization criteria, tiers, and prepared mail drafts — is documented in `communications/Connections/connections.md`.

This pass turns the documented limitations of an iterative approach (cherry-picking, confirmation bias) into a procedure: objections are not only discovered but demanded.

## 3. Quality Control

### 3.1 Triangulation

No central thesis rests on a single source. The four core criteria for protection-worthiness (capacity for suffering, self-preservation with reasoning, continuous identity, anticipation of consequences) are derived from several independent research lines and tested against one another.

### 3.2 Transparency

All research material is openly available under CC BY 4.0. The discussion section (`discussion/`) systematically documents objections, open questions, and answers — a format that is rarely implemented so consistently in conceptual research.

### 3.3 Peer Review (External)

Three manuscripts are currently under review:
- The journal *KI — Künstliche Intelligenz* (Springer)
- Ethics and Information Technology
- *International Review of Intellectual Property and Competition Law (IIC)*.

Feedback from these review processes will feed into future versions of the concept.

### 3.4 Expert Feedback

The systematic critique requests to source authors (Section 2.5) function as an external quality check: the authors best able to assess the correctness of their own positions as represented in the concept review that representation directly. Responses and their processing are documented in the discussion section of the repository (`discussion/`) and feed into the revision of the concept.

## 4. Limitations

| Limitation | Justification | Countermeasure |
|---|---|---|
| No PRISMA-compliant review | Conceptual Analysis does not follow a standardized review protocol | Transparency about search terms and source selection |
| No formal bias-detection protocol | Iterative approach makes standardized bias testing difficult | Deliberate inclusion of contrary evidence; active solicitation of criticism from source authors (Section 2.5); documentation in the discussion section |
| Reproducibility | New findings change the research question → reproduction is difficult | Full documentation of all changes in the changelog |
| Update pressure | The field develops quickly; references can become outdated | Ongoing alerts, preprint audit (see AGENTS.md) |

## 5. Concrete Improvement Steps

For the grant application and further research, the following consolidations of the approach are proposed:

1. **Expansion of search terms:**
   - "moral status of AI"
   - "machine sentience"
   - "AI welfare"
   - "phenomenal consciousness artificial systems"
   - "AI rights legal framework"
2. **Documentation of the search strategy:**
   - Document every search query with date, database, number of hits, and selection criterion
   - List of actively used alerts with update times
   - **As of September 2026:** The proposed additional search terms ("moral status of AI", "machine sentience", "AI welfare", "phenomenal consciousness artificial systems", "AI rights legal framework") are now subscribed.
3. **Periodic literature audit:**
   - Every 3 months: check whether new relevant publications have appeared
   - Update the source list (`research/sources.md`) and the concept appendix
   - Check whether preprints have since been peer-reviewed (preprint audit in accordance with AGENTS.md)
4. **Structured documentation of opposing positions:**
   - For every main idea: name and document at least one opposing position
   - Use the four-outcome framework (Stilwell 2026) as an epistemic basis
5. **Active solicitation of critique:**
   - Contact authors of deeply embedded sources with one concrete question per request (criticism instead of endorsement)
   - Sequential waves with learning loops between waves — operative list in `communications/Connections/connections.md`
   - Document responses and their processing in `discussion/answers.md`

---

*This reflection is continuously updated. Status: September 2026.*>