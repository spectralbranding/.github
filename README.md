[![MIT License](https://img.shields.io/badge/Code-MIT-blue.svg)](LICENSE)
[![CC-BY 4.0](https://img.shields.io/badge/Data-CC--BY_4.0-lightgrey.svg)](LICENSE-data)
![Last Updated](https://img.shields.io/badge/updated-2026--06--09-success)

# Spectral Branding — Organisation Profile Repository

> GitHub org profile, default community files, and shared configuration for the `spectralbranding/` organisation.

This repository is the GitHub special `.github` repo for the `spectralbranding` organisation. Its primary purpose is to host the org-profile README rendered at <https://github.com/spectralbranding> and to provide default community files inherited by org repositories that do not define their own.

---

## 1 | Getting Started

This repository contains no source code or computational pipeline. To read the rendered org profile, visit <https://github.com/spectralbranding>. To clone this repo:

```bash
git clone https://github.com/spectralbranding/.github.git
cd .github
```

The project anchor is the `.here` file at the repository root.

---

## 2 | Project Layout

```
.
├── profile/                # Org-profile README rendered at github.com/spectralbranding
│   └── README.md           # Profile content (separate from this README)
├── .github/                # Default community files inherited by org repos
├── LICENSE                 # MIT (code, configs, scripts)
├── LICENSE-data            # CC BY 4.0 (text, content, rendered artifacts)
├── CITATION.cff            # Machine-readable citation
├── reproduce.sh            # Reproducibility stub (no pipeline)
├── output/                 # Standard-mandated structure (empty here)
│   ├── figures/
│   ├── tables/
│   └── logs/
├── .here                   # Project anchor
├── .gitignore              # Secrets + environment exclusions
└── README.md               # This file
```

---

## 3 | Quick Start

There is no computational pipeline to reproduce in this repo. The `reproduce.sh` stub at the root is present only to satisfy `PUBLIC_MIRROR_STANDARD.md` v1.0.0 and prints a pointer to per-mirror reproduction scripts.

---

## 4 | Dependencies

None. The org profile is rendered server-side by GitHub from `profile/README.md`.

---

## 5 | Script Map

Not applicable. No scripts ship in this repository.

---

## 6 | Citation

If you cite the spectralbranding organisation as a publishing entity, see [`CITATION.cff`](CITATION.cff). For the underlying research, cite the respective paper mirrors (each ships its own `CITATION.cff`).

---

## 7 | Licence

- **Code** — © Dmitry Zharnikov, 2026. [MIT Licence](LICENSE).
- **Content** — © Dmitry Zharnikov, 2026. [CC BY 4.0](LICENSE-data).

---

## Public mirrors

Primary public mirrors under the `spectralbranding` organisation:

- **sbt-papers** — Spectral Brand Theory paper corpus: <https://github.com/spectralbranding/sbt-papers>
- **orgschema-papers** — Organisational Schema Theory paper corpus: <https://github.com/spectralbranding/orgschema-papers>
- **meaningfulness-papers** — Meaningfulness paper corpus: <https://github.com/spectralbranding/meaningfulness-papers>
- **sbt-framework** — Shared framework code and references: <https://github.com/spectralbranding/sbt-framework>
- **negotiation-spec-experiment** — Standalone empirical note (specification vs style in LLM negotiation; value headroom as moderator): <https://github.com/spectralbranding/negotiation-spec-experiment>

Per-paper-slug mirrors (28+) live under the same organisation; see the parent corpus mirrors above for the full index.

---

*Last updated: 2026-06-09*
