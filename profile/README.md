# Spectral Branding

## Two frameworks. One system.

Businesses are simultaneously **perception systems** and **specification systems**. We publish open-source research frameworks for both sides.

**Spectral Brand Theory (SBT)** models how brands are *perceived* — eight perceptual dimensions, observer-specific spectral profiles, math-hardened validation, an AI-native analytical pipeline. **Organizational Schema Theory (OST)** models how businesses are *specified* — a reverse-design TDD methodology where customer-experience goals are acceptance tests and each operational layer validates the layer above it.

> Aaker drew the map. SBT built the microscope. OrgSchema built the specification. Neither alone is complete.

Everything is open: ~40 working papers on Zenodo (CC BY 4.0), machine-readable sources on GitHub, runnable toolkits.

---

## Start here — find your path

Pick the row that fits you. Each path names the exact repo/paper to open first.

| You are… | You want to… | Start here |
| :------- | :----------- | :--------- |
| **Researcher / student** | Understand the *theory* and build on it | SBT: [`sbt-papers/spectral-brand-theory`](https://github.com/spectralbranding/sbt-papers/tree/main/spectral-brand-theory) · OST: [`orgschema-papers/six-tier-ontology`](https://github.com/spectralbranding/orgschema-papers/tree/main/six-tier-ontology). Full reading paths ↓ |
| **CMO / brand lead** | Diagnose a brand, find perception gaps | The live [**Brand Spectrometer**](https://meter.spectralbranding.com) (see your brand's shape in minutes) + [`sbt-framework`](https://github.com/spectralbranding/sbt-framework) (run a spectral audit) + the 8-dimension model ↓ |
| **CMO / brand lead** | Decide *how to act*: is one brand score enough, and how do you reach a cohort with no address? | [`brand-correspondence-principle`](https://github.com/spectralbranding/sbt-papers/tree/main/brand-correspondence-principle) (2026au — when a single score suffices, and the cost when it doesn't) → [`reaching-a-perception`](https://github.com/spectralbranding/sbt-papers/tree/main/reaching-a-perception) (2026av — three bridges to reach a perceptual cohort; only one needs an address) |
| **CEO / COO** | Specify or stress-test an operating model | [`orgschema-toolkit`](https://github.com/spectralbranding/orgschema-toolkit) (specify a business in ~40 min) + [`orgschema-demo`](https://github.com/spectralbranding/orgschema-demo) |
| **CFO / strategy** | Decide where to invest, evaluate an M&A or new project | Tier-allocation & tier-rotation papers ↓ ("Evaluate a business case") |
| **AI agent** | Consume the corpus correctly | Every repo's `AGENTS.md` + the citation/metadata model ↓ |
| **Curious / press** | Get the idea in one sentence | *A brand, like colour, does not exist in the object — it is completed in the observer.* → [spectralbranding.com](https://spectralbranding.com) |

---

## The core ideas (concept map)

**Spectral Brand Theory.** A brand emits signals across **eight independent perceptual dimensions** — *Semiotic, Narrative, Ideological, Experiential, Social, Economic, Cultural, Temporal*. Each observer filters those signals through a personal **spectral profile** (a weight vector) and constructs a **perception cloud** — a probability distribution over possible convictions, *not* a single "brand image." Observers group into **cohorts** (perceptual, not demographic). Two different emission profiles can produce the same perception for a cohort — **metamerism**. Measurement, not management: SBT measures the perception you do **not** control.

**Organizational Schema Theory.** A business is a **specification cascade** across **six tiers**: customer-experience goals at the top are *acceptance tests*; each lower layer (positioning → capabilities → processes → roles → sourcing) must validate the layer above. **Verification is an operator** that projects the sprawling implementation back onto the specified subspace. Distinct configurations that yield equivalent outputs are **organizational metamerism**. Specification, not improvisation: OST makes the business you *do* control explicit and testable.

**The bridge.** Both are instances of the **rendering problem**: a compact *specification* (genome / org-schema / brand guidelines) is rendered into a vast *implementation* (organism / operations / signals), from which an *emergent* layer arises (phenotype / culture / perception). The **meaningfulness** program generalizes this to any knowledge artifact: a small **substrate** (the claims) renders into much larger **prose**.

```
            SPECIFICATION  ──render──▶  IMPLEMENTATION  ──emerge──▶  EMERGENT LAYER
  biology    genome                     organism                     phenotype
  business   org-schema (OST)           operations                   culture
  brand      guidelines                 emitted signals              perception cloud (SBT)
  research   substrate / spine          prose                        meaningfulness
```

Per-term definitions and their formal relations live in each paper's `ONTOLOGY.yaml` + `GLOSSARY.md`.

---

## The repositories

### Spectral Brand Theory

| Repo | What it is |
| :--- | :--------- |
| [**sbt-framework**](https://github.com/spectralbranding/sbt-framework) | 7-module AI-native prompt kit with YAML templates + 7 math validators. Run a spectral brand audit on any brand. |
| [**brand-spectrometer**](https://github.com/spectralbranding/brand-spectrometer) | The open in-browser instrument — reads cohort-resolved, 8-dimension brand perception from any atlas and flags which differences between audiences clear the noise floor. Live at [meter.spectralbranding.com](https://meter.spectralbranding.com). |
| [**sbt-papers**](https://github.com/spectralbranding/sbt-papers) | Research papers — framework spec, epistemological pipeline, mathematical foundations (R0–R22), AI-era studies, and the measurement instrument. 30+ papers on [Zenodo](https://zenodo.org/communities/spectral-branding/). |
| [**brand-functions**](https://github.com/spectralbranding/brand-functions) | Brand Function Registry — machine-readable brand specs (JSON) for 26 brands across the 8 dimensions. The schema.org of brand identity. |
| [**brand-code**](https://github.com/spectralbranding/brand-code) | Executable brand identity. The visual identity is a function, not a file. |

[spectralbranding.com](https://spectralbranding.com) · [Substack](https://spectralbranding.substack.com) · [Zenodo](https://zenodo.org/communities/spectral-branding/)

### Organizational Schema Theory

| Repo | What it is |
| :--- | :--------- |
| [**orgschema-framework**](https://github.com/spectralbranding/orgschema-framework) | Python validator + JSON Schema for the 6-level TDD cascade format. |
| [**orgschema-demo**](https://github.com/spectralbranding/orgschema-demo) | Spectra Coffee — a complete business specified as organizational schema. 25 YAML files + CI/CD. |
| [**orgschema-toolkit**](https://github.com/spectralbranding/orgschema-toolkit) | 8-module AI prompt pipeline. Specify a complete business in ~40 minutes. |
| [**orgschema-papers**](https://github.com/spectralbranding/orgschema-papers) | Research papers — six-tier ontology, projection cascade, tier-rotation, tier-allocation, verification-as-operator, specification-readiness, the rendering problem, and the OST audit. |

[orgschema.com](https://orgschema.com) · [Substack](https://orgschema.substack.com) · [Zenodo](https://zenodo.org/communities/orgschema)

### Meaningfulness & Meaning

Meta-corpus on knowledge work in the post-AI era — the substrate↔rendering distinction operationalized for any propositional artifact (paper, memo, brand spec, decision log).

| Repo | What it is |
| :--- | :--------- |
| [**meaningfulness-papers**](https://github.com/spectralbranding/meaningfulness-papers) | [Spec-Based Research in the Post-AI Era](https://doi.org/10.5281/zenodo.20409683) (theory) + [Same Meaning, Different Prose](https://doi.org/10.5281/zenodo.20409701) (empirical). |

### Applied specifications

| Repo | What it is |
| :--- | :--------- |
| [**paper-spec**](https://github.com/spectralbranding/paper-spec) | Paper Spec v0.1.0 — machine-readable YAML standard for scientific claims. *What a paper claims.* |
| [**paper-repo**](https://github.com/spectralbranding/paper-repo) | Paper Repo v0.1.0 — Git-native protocol for scientific publishing. *How a paper is managed.* |
| [**activity-spec**](https://github.com/spectralbranding/activity-spec) | YAML schema + LLM prompts for machine-readable professional profiles. |
| [**negotiation-spec-experiment**](https://github.com/spectralbranding/negotiation-spec-experiment) | Empirical study — specify an LLM negotiator's objective, or style it? 7 arms, 4,920 dyads. [Zenodo](https://doi.org/10.5281/zenodo.20595996). |

---

## Reading paths (researchers & students)

**Understand SBT (brand perception):**
1. **The framework** — `spectral-brand-theory` (2026a): the 8 dimensions, emission profiles, perception clouds, cohorts.
2. **Where it sits** — `r0-literature-survey` (2026c): SBT vs Aaker / Keller / Kapferer / MDS. And `spectral-identity` (2026n): formalizing Aaker's identity model.
3. **Why eight** — `r11-dimension-justification` (2026r).
4. **Mathematical spine** — `r1-formal-metric` (geometry) → `r2-spectral-metamerism` (projection bounds) → `r3-cohort-boundaries` (concentration of measure) → `r4-sphere-packing` (market capacity) → `r5-specification-impossibility`.
5. **Dynamics** — `r6-diffusion-dynamics`, `r9-nonergodic-perception`, `r12-coherence-resilience`, `r18-spectral-dynamics`, `r22-spectral-gap-restoration`.
6. **AI era** — `r15-ai-search-metamerism`, `r16-ai-native-brand-identity`, `r21-spectral-immunity`, `r19-rate-distortion`.
7. **Measure it** — `prism-instrument` (2026as), and the applied cases `r10-dove-case-study`, `r17-brand-triangulation`.
8. **When the score suffices** — `brand-correspondence-principle` (2026au): the regime where an aggregate brand score is sufficient for a decision, and the measurable cost when it is not.
9. **Reach a perceptual cohort** — `reaching-a-perception` (2026av): a perceptual cohort has no native media address and does not need one — three measurable bridges from perception to delivery (broadcast a dimension and let self-selection route it, follow atom provenance, or quantify the proxy-join loss), and why the address-free route is the post-cookie tailwind.

**Understand OST (how businesses are specified):**
1. **Six tiers** — `six-tier-ontology` (2026ag) + the OST main paper.
2. **The rendering problem** — the cross-domain bridge (biology / org / brand).
3. **Mechanics** — `verification-as-operator` (2026ae), `projection-paper` (2026m), `org-as-metadata` (2026af, organizational metamerism).
4. **Where to invest** — `tier-allocation` (2026aj), `tier-rotation` (2026ai), `brand-as-modular-layer` (2026ah), `capability-as-projection` (2026al).
5. **Readiness** — `specification-readiness` (2026am) + its empirical companion (2026an); diagnose with `orgschema-audit` (2026ar).

**Understand the meta-program (research after AI):**
`meaning-meaningfulness` (2026ao/2026ap) · `r14-paper-as-repository` (2026u) · `canon-as-repository` (2026w) · `paper-spec` · `paper-repo`.

---

## Evaluate a business case (executives)

A concrete four-step recipe, using both frameworks:

1. **Place your business on the six tiers** (OST) — use [`orgschema-toolkit`](https://github.com/spectralbranding/orgschema-toolkit); see [`orgschema-demo`](https://github.com/spectralbranding/orgschema-demo) for a worked example. Output: an explicit, testable spec with the acceptance tests that define "working."
2. **Measure your brand's 8-dimension emission profile** and the cohorts that matter (SBT) — run [`sbt-framework`](https://github.com/spectralbranding/sbt-framework); compare against the 26 specs in [`brand-functions`](https://github.com/spectralbranding/brand-functions).
3. **Find the two gaps** — the **specification gap** (operations exceed or miss the spec → OST `verification-as-operator`, `orgschema-audit`) and the **perception gap** (the cohorts' perception clouds diverge from intent → SBT `r10-dove-case-study`, `r12-coherence-resilience`).
4. **Decide where capital/attention creates the most value** — `tier-allocation` (2026aj, "where to invest within the firm"), `tier-rotation` (2026ai), and the AI-substrate-dependence lens for new bets. For brand-portfolio moves: `r8` → `r21-spectral-immunity` (when portfolio interference does and does not hold), `brand-as-modular-layer` (2026ah).

CMO-first? Skip to steps 2–3. CFO-first? Steps 1 and 4. The point: you can only manage the specification you control once you can *measure* the perception you don't.

---

## For AI agents

- **Every paper folder has an `AGENTS.md`** — a file-by-file guide. Read it first.
- **Citations are `[@citation_key]` keys**, resolved against the bundled `<key>.bib`. A `[@key]` is never a typo — it renders to "(Author Year)". See each folder's `CITATIONS.md`.
- **Structured claims** (what a paper asserts, assumes, and depends on) are in `paper.yaml` (**Paper Spec**) — parse this instead of the prose.
- **Terms** are defined in `GLOSSARY.md` with formal relations in `ONTOLOGY.yaml` (owns / imports / refines).
- To answer a grounded question: find the paper in the reading paths above → open `paper.md` → resolve cites against the `.bib`.

---

## Cite · License · Contact

- **License:** papers CC BY 4.0; code MIT (dual-licensed per repo).
- **Cite:** each paper folder has a `CITATION.cff` and a Zenodo DOI.
- **Author:** Dmitry Zharnikov — [ResearchGate](https://www.researchgate.net/profile/Dmitry-Zharnikov) · [Zenodo (SBT)](https://zenodo.org/communities/spectral-branding/) · [Zenodo (OST)](https://zenodo.org/communities/orgschema)
