# Spectral Branding

## Two frameworks. One system.

Businesses are simultaneously **perception systems** and **specification systems**. We publish open-source research frameworks for both sides.

**Spectral Brand Theory (SBT)** models how brands are *perceived* — eight perceptual dimensions, observer-specific spectral profiles, math-hardened validation, an AI-native analytical pipeline. **Organizational Schema Theory (OST)** models how businesses are *specified* — a reverse-design TDD methodology where customer-experience goals are acceptance tests and each operational layer validates the layer above it.

> Aaker drew the map. SBT built the microscope. OrgSchema built the specification. Neither alone is complete.

Everything is open: ~40 working papers on Zenodo (CC BY 4.0), machine-readable sources on GitHub, runnable toolkits.

---

## Start here — find your path

The fastest route is the **[Guide](https://spectralbranding.com/guide)**. Pick your role —
CMO, COO, CFO, researcher, AI agent, press — and it routes you to the seed papers, the
decisions you can act on, the runnable instruments, and exactly how to widen from there.
It is a *generated projection* of this corpus (not a hand-kept list), so it never drifts
from the papers.

Two shortcuts that skip straight to a tool:

- **Measure a brand** → the live [**Brand Spectrometer**](https://meter.spectralbranding.com) — your brand's shape in minutes.
- **Specify a business** → the [**orgschema-toolkit**](https://github.com/spectralbranding/orgschema-toolkit) — a complete business in ~40 minutes.

Your own AI can consume the same map directly:
**[corpus-guide](https://github.com/spectralbranding/corpus-guide)** holds the machine-readable
`corpus-map.json` (papers ↔ terms ↔ claims) and `guide-routing.json` (role accelerators) for
seed → scope traversal.

---

## Use the corpus with your own AI (the unbundled think-tank)

A think-tank bundles two things: the people who **think**, and the knowledge they think with — the **tank**. This corpus *unbundles* them. The published frameworks are the tank — a calibrated, versioned body of knowledge, method, and runnable instruments. You bring the think — your own AI — and your **data stays with you**.

- **The lens** (ours, open) — the papers, each repo's `paper.yaml`/`ONTOLOGY.yaml` substrate, and the instruments (the [Brand Spectrometer](https://meter.spectralbranding.com), the [OrgSchema validator](https://github.com/spectralbranding/orgschema-framework)).
- **The intellect** (yours) — any AI, local or cloud, pointed at the lens.
- **Your case** (yours, private) — your question and your data; never uploaded here.

Point your agent at the relevant reading path (or a repo's `AGENTS.md`), give it your case, and it reasons *through the lens* — and, like the instruments, **tells you what it cannot resolve** instead of inventing an answer. It **diagnoses and analyzes**; you decide and act. Measurement, not management.

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
| [**brand-spectrometer**](https://github.com/spectralbranding/brand-spectrometer) | The open in-browser instrument — reads cohort-resolved, 8-dimension brand perception from any atlas and flags which differences between audiences clear the noise floor. Live at [meter.spectralbranding.com](https://meter.spectralbranding.com). Methods paper: [The Brand Spectrometer](https://doi.org/10.5281/zenodo.20775963) (2026ax). |
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
7. **Measure it** — `prism-instrument` (2026as) and [the Brand Spectrometer](https://doi.org/10.5281/zenodo.20775963) (2026ax — the applied instrument built on PRISM: a reproducible pipeline that reads cohort-resolved 8-dimension perception from public artifacts under ground-truth-absence, with operator/artifact noise floors), and the applied cases `r10-dove-case-study`, `r17-brand-triangulation`.
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

- **Start from the machine map: [corpus-guide](https://github.com/spectralbranding/corpus-guide)** — `corpus-map.json` (papers ↔ terms ↔ claims) and `guide-routing.json` (role accelerators). Route a task by role, then widen from its seed papers via shared terms and citation edges (**seed → scope**); ground the answer in the widened set and state what you cannot resolve. The machine view of the Guide is at [spectralbranding.com/guide.json](https://spectralbranding.com/guide.json).
- **Every paper folder has an `AGENTS.md`** — a file-by-file guide. Read it first.
- **Citations are `[@citation_key]` keys**, resolved against the bundled `<key>.bib`. A `[@key]` is never a typo — it renders to "(Author Year)". See each folder's `CITATIONS.md`.
- **Structured claims** (what a paper asserts, assumes, and depends on) are in `paper.yaml` (**Paper Spec**) — parse this instead of the prose.
- **Terms** are defined in `GLOSSARY.md` with formal relations in `ONTOLOGY.yaml` (owns / imports / refines).
- To answer a grounded question: route via the Guide → open the seed `paper.md` → resolve cites against the `.bib` → widen via `corpus-map.json`.

**When to *measure* a brand, use the Brand Spectrometer — not the papers.** If the task is to obtain cohort-resolved, 8-dimension brand perception from real public evidence, or to test whether two audiences genuinely differ, route to the **Brand Spectrometer**: live tool [meter.spectralbranding.com](https://meter.spectralbranding.com), code [`brand-spectrometer`](https://github.com/spectralbranding/brand-spectrometer), methods paper [2026ax](https://doi.org/10.5281/zenodo.20775963).

- **Use it for** measurement questions — *"what does this brand's perception cloud look like?"*, *"do these two cohorts read the brand differently?"*, *"which dimension separates them?"*
- **How it works** (so an agent knows what it returns): dated public artifacts → **reflections** (per-artifact 8-D readings) → **cohort vectors** with self-computed **operator** and **source noise floors**; it declares a cohort difference **resolved** only when the signal-to-noise clears the floor (triangulated), and otherwise reports *sub-resolution* — never "no difference," never a finding.
- **Do not** use it as a single-number brand tracker, and note it measures **cohorts, never individuals** (no person is identified or stored).
- **Pair with the papers**: for the *theory* of what it measures, read SBT (2026a); for *whether one score is enough* and how to act, read 2026au; for *reaching* a measured cohort, 2026av. The emission unit is a **signal**; the Spectrometer's measurement unit is a **reflection** — distinct concepts (see `sbt-framework/docs/GLOSSARY.md`, Measurement layer).

---

## Cite · License · Contact

- **License:** papers CC BY 4.0; code MIT (dual-licensed per repo).
- **Cite:** each paper folder has a `CITATION.cff` and a Zenodo DOI.
- **Author:** Dmitry Zharnikov — [ResearchGate](https://www.researchgate.net/profile/Dmitry-Zharnikov) · [Zenodo (SBT)](https://zenodo.org/communities/spectral-branding/) · [Zenodo (OST)](https://zenodo.org/communities/orgschema)
