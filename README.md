<div align="center">

<img src="assets/readme/hero.svg" width="100%" alt="QUANTUM TRADING / MT5 technical cover" />

**Quantum-inspired market-direction exploration using MT5 and Qiskit**

[Architecture](#architecture) · [Repository map](#repository-map) · [Run](#getting-started) · [Validation](#validation-and-evidence) · [Roadmap](#engineering-roadmap)

</div>

> **Evidence status: EXPERIMENTAL RESEARCH.** This README describes repository contents and boundaries, not verified production readiness or investment outcomes. Previous narrative is preserved in [legacy documentation](docs/README_LEGACY.md) for traceability, not as independent proof.

## Overview

Quantum-inspired market-direction exploration using MT5 and Qiskit. The purpose is to provide a research and engineering basis that can be inspected and improved without implying performance that has not been independently validated.

| Field | Details |
|:--|:--|
| Repository | [`quantum-trading_metatrader5`](https://github.com/Shtenco/quantum-trading_metatrader5) |
| Primary stack | Python, MetaTrader5, NumPy, Qiskit/Aer |
| Role | EXPERIMENTAL RESEARCH |
| Source of truth | Code on `main`; experiments require separate reproducible artifacts |
| Parent ecosystem | [SYNERGY SYSTEM](https://github.com/Shtenco/synergy_system) |

## Architecture

```mermaid
flowchart LR
 A[Inputs and configuration] --> B[Repository source]
 B --> C[Research or presentation outputs]
 C --> D[Independent verification gate]
 D --> E[Published evidence, if validated]
```

**Implementation scope:** Quantum-inspired market-direction exploration using MT5 and Qiskit. The diagram is a conceptual map and does not assert that the verification gate is implemented or automated.

## Repository map

| Path | Purpose |
|:--|:--|
| `main.py` | Primary executable and research logic |
| `requirements.txt` | Python package dependencies |
| `docs/README_LEGACY.md` | Preserved historical documentation; claims may be unverified |
| `assets/readme/hero.svg` | Vector cover, with no external image-host dependencies |

## Getting started

Check required Python modules, vendor platform services and API keys before execution. **Commands below identify the source entry point; they are not evidence of a successful run in this session.**

```bash
git clone https://github.com/Shtenco/quantum-trading_metatrader5.git
cd quantum-trading_metatrader5
python main.py
```

Use a configured local environment and a demo/data-only setup where applicable. Do not connect research prototypes to funded trading accounts without separate safety review.

## Validation and evidence

**Known limitation:** Market binary input is not encoded into the quantum state in the reviewed implementation; no demonstrated quantum predictive advantage.

| Layer | Evidence classification |
|:--|:--|
| Source files | Present in repository tree |
| Automated tests and CI | Not established by this documentation pass |
| Out-of-sample or independent evaluation | Not established by this documentation pass |
| Production readiness | Not established |
| Economic or predictive claims | Must be supported by dated, reproducible evidence |

The terms *prototype*, *simulation*, *backtest*, *live deployment* and *audited result* should never be conflated. Any quoted return, accuracy, latency or capability must be tied to a data provenance record, experiment conditions and a commit.

## Engineering roadmap

Market-conditioned encoding, classical baseline, strict walk-forward and reproducible seeds.

Recommended completion criteria: testable experiment configuration, pinned runtime dependencies, repeatable CI or equivalent checks, archived output manifests, and a documented failure/limitations section.

## Maintainer and attribution

Maintained in the [Shtenco GitHub portfolio](https://github.com/Shtenco). See `LICENSE` for applicable terms. Read the original repository source and [legacy README](docs/README_LEGACY.md) before treating earlier examples or statistics as verified evidence.
