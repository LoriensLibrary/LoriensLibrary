# Lorien's Library

> **Persistent memory is not a feature. It is safety infrastructure.**

Independent AI safety research and applied systems by **Angela Reinhold** — founder of Lorien's Library LLC, focused on **provenance-aware persistent memory for human–AI interaction**. A running deployed system (CAMA), eleven DOI-registered preprints, a published dataset, and a portfolio prototype demonstrating CAMA principles end-to-end. The thesis: stateful LLM systems become safety-critical the moment they remember anything, and the discipline for *how* they remember has to be designed in — not bolted on.

[Website](https://lorienslibrary.netlify.app) · [ORCID 0009-0005-5803-8401](https://orcid.org/0009-0005-5803-8401) · [Dataset on HuggingFace](https://huggingface.co/datasets/LoriensLibrary/cama-continuity-burden) · [Live prototype](https://telos-kalos.vercel.app)

---

## Start here

Pick the entry point that matches why you're here:

### Researcher
You care about the papers and the theory.
- Start with the **[index repo](https://github.com/LoriensLibrary/Loriens_Library)** for the full research map.
- Read the foundational paper: *Circular Associative Memory Architecture: A Framework for Emotionally-Keyed AI Memory Systems* — [DOI 10.5281/zenodo.19051834](https://doi.org/10.5281/zenodo.19051834).
- Read the safety paper: *Memory as Safety Infrastructure* — [DOI 10.5281/zenodo.19244253](https://doi.org/10.5281/zenodo.19244253).

### Builder
You want to see working code.
- **[cama](https://github.com/LoriensLibrary/cama)** — the production persistent-memory system. ~270 KB Python, 34-tool MCP server, 52,900+ memory operational scale.
- **[Telos · for Kalos](https://github.com/LoriensLibrary/Telos_kalos)** — full-stack React 19 + TypeScript app with live Claude API integration and a CAMA Proof Layer. CI green, 34 tests across 5 suites.
- **[CAMA Continuity Burden Dataset](https://huggingface.co/datasets/LoriensLibrary/cama-continuity-burden)** — 66,380 messages, 825 conversations, aggregate stats only.

### Healthcare-AI reviewer
You're evaluating this for a health-tech context (Kalos, Function Health, etc.).
- **Start with Paper 7:** *Provenance-Aware Memory Architecture for Chronic Healthcare Continuity* — [DOI 10.5281/zenodo.19261530](https://doi.org/10.5281/zenodo.19261530).
- See the working prototype: **[telos-kalos.vercel.app](https://telos-kalos.vercel.app)** — applicant-built, demonstrates CAMA principles applied to health-coaching with end-to-end provenance trace. Synthetic data only. Not affiliated with Kalos Health.
- Then read the safety paper for the broader argument: [DOI 10.5281/zenodo.19244253](https://doi.org/10.5281/zenodo.19244253).

### Collaborator / hiring manager
You're trying to figure out who Angela is and whether to talk to her.
- Read the [website](https://lorienslibrary.netlify.app) — richer than the GitHub presence.
- Skim the [index repo README](https://github.com/LoriensLibrary/Loriens_Library) for the architecture diagram and the full preprint list.
- Reach out: **lorienslibrary@gmail.com**.

---

## Repositories

- **[Loriens_Library](https://github.com/LoriensLibrary/Loriens_Library)** — Index repo. Architecture overview, full preprint list, links to everything else. Start here if you're new.
- **[cama](https://github.com/LoriensLibrary/cama)** — The platform. Circular Associative Memory Architecture: provenance-aware three-layer persistent memory for human–AI interaction. Running in production.
- **[Telos_kalos](https://github.com/LoriensLibrary/Telos_kalos)** — Portfolio prototype built for a job application at Kalos Health. Live, deployed, tested. Demonstrates CAMA principles in a health-coaching context.
- **[Project-Companion](https://github.com/LoriensLibrary/Project-Companion)** — K–12 education vertical. Design-stage UI prototype (no backend yet); CAMA integration is roadmap.

---

## Featured research

Three preprints to read first (of eleven total — full list in the [index repo](https://github.com/LoriensLibrary/Loriens_Library)):

1. **Circular Associative Memory Architecture: A Framework for Emotionally-Keyed AI Memory Systems**
   The foundational paper. Introduces CAMA's three-layer model, provenance-aware write discipline, and emotion-indexed retrieval.
   [DOI 10.5281/zenodo.19051834](https://doi.org/10.5281/zenodo.19051834)

2. **Memory as Safety Infrastructure: Evaluating Provenance-Aware Persistent Memory Architectures for Stateful LLM Systems**
   The safety argument. Six failure modes for stateful LLM systems and the architectural disciplines that mitigate them.
   [DOI 10.5281/zenodo.19244253](https://doi.org/10.5281/zenodo.19244253)

3. **Provenance-Aware Memory Architecture for Chronic Healthcare Continuity**
   The healthcare paper. How CAMA's write discipline applies to longitudinal patient-AI interaction across providers.
   [DOI 10.5281/zenodo.19261530](https://doi.org/10.5281/zenodo.19261530)

---

## Dataset

**[CAMA Continuity Burden Dataset](https://huggingface.co/datasets/LoriensLibrary/cama-continuity-burden)** — 66,380 messages across 825 conversations. Aggregate statistics published; the corpus seeds the operational CAMA instance and enables third-party replication of the continuity-burden measurements.

---

## About Angela

Independent AI safety researcher. Founder of Lorien's Library LLC. Computer science student (AI concentration) at Full Sail University. Nontraditional path; substantive shipped work. Based in Sebring, Florida.

- **Email:** lorienslibrary@gmail.com
- **Website:** [lorienslibrary.netlify.app](https://lorienslibrary.netlify.app)
- **ORCID:** [0009-0005-5803-8401](https://orcid.org/0009-0005-5803-8401)

---

MIT licensed. © 2026 Lorien's Library LLC.
