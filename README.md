# Lorien's Library

> **Persistent memory is not a feature. It is safety infrastructure.**

<sub>*This is the GitHub profile README — a 30-second front door. For the full research map, see the [Loriens_Library](https://github.com/LoriensLibrary/Loriens_Library) index repo.*</sub>

Independent AI safety research and applied systems by **Angela Reinhold** — founder of Lorien's Library LLC, focused on **provenance-aware persistent memory for human–AI interaction**. One operational research deployment (CAMA, single-participant), eleven DOI-registered preprints, a published aggregate-statistics dataset, and a portfolio prototype demonstrating the architecture end-to-end. The thesis: stateful LLM systems become safety-critical the moment they remember anything, and the discipline for *how* they remember has to be designed in — not bolted on.

[Website](https://lorienslibrary.netlify.app) · [ORCID 0009-0005-5803-8401](https://orcid.org/0009-0005-5803-8401) · [Dataset on HuggingFace](https://huggingface.co/datasets/LoriensLibrary/cama-continuity-burden) · [Live prototype](https://telos-kalos.vercel.app)

> **Hiring manager? Start with [Telos_kalos](https://github.com/LoriensLibrary/Telos_kalos)** — a deployed React 19 + TypeScript app with a Hono + Neon Postgres backend, live Claude API integration, and 42 tests in CI. [Live demo →](https://telos-kalos.vercel.app)
>
> **Currently seeking software engineering / applied AI / AI safety roles** — full-time, remote-first, with healthcare AI as the explicit target. Email **lorienslibrary@gmail.com**.

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
- **[Telos · for Kalos](https://github.com/LoriensLibrary/Telos_kalos)** — full-stack React 19 + TypeScript + Vite app with a Hono + Drizzle + Neon Postgres backend, live Claude API integration, and a CAMA Proof Layer demonstrating end-to-end provenance trace. 42 tests across 6 suites in CI. [Live demo](https://telos-kalos.vercel.app).
- **[cama](https://github.com/LoriensLibrary/cama)** — Python MCP server implementing the memory architecture. 34 core tools plus 9 optional subsystems on the single-participant side; eight-layer multi-tenant generalization (dyad / hive / persona / agent / quad / surface / consult / resources) with 187 tests in CI. Single-participant operational deployment (~53,000 memories on the author's instance). `v0.1.0` tagged.
- **[CAMA Continuity Burden Dataset](https://huggingface.co/datasets/LoriensLibrary/cama-continuity-burden)** — 66,380 messages, 825 conversations, aggregate stats only (raw corpus not released).

### Healthcare-AI reviewer
You're evaluating this for a health-tech context (Kalos, Function Health, etc.).
- **Start with Paper 7:** *Provenance-Aware Memory Architecture for Chronic Healthcare Continuity* — [DOI 10.5281/zenodo.19261530](https://doi.org/10.5281/zenodo.19261530).
- See the working prototype: **[telos-kalos.vercel.app](https://telos-kalos.vercel.app)** — applicant-built, demonstrates CAMA principles applied to health-coaching with end-to-end provenance trace. Synthetic data only. Not affiliated with Kalos Health.
- Then read the safety paper for the broader argument: [DOI 10.5281/zenodo.19244253](https://doi.org/10.5281/zenodo.19244253).

### Collaborator / hiring manager
Fastest path to evaluate the work:
1. **[Telos_kalos](https://github.com/LoriensLibrary/Telos_kalos)** — deployed React 19 + TypeScript + Vite app with Hono + Neon Postgres backend and live Claude API integration. 42 tests in CI. [Live demo](https://telos-kalos.vercel.app).
2. **[cama](https://github.com/LoriensLibrary/cama)** — Python MCP server + eight-layer multi-tenant architecture. Schema enforces provenance discipline. 187 tests in CI. `v0.1.0` tagged.
3. **[Project-Companion](https://github.com/LoriensLibrary/Project-Companion)** — design prototype showing CAMA architecture applied to K-12 (UI only; backend integration is roadmap).
4. *Optional context:* the [website](https://lorienslibrary.netlify.app), the [index repo](https://github.com/LoriensLibrary/Loriens_Library), or Paper 1 / Paper 7 from the [research map](https://github.com/LoriensLibrary/Loriens_Library).

**Stack across the portfolio:** TypeScript · React 19 · Vite · Vercel · Hono · Drizzle · Neon Postgres · Python 3.10+ · MCP · SQLite · Anthropic SDK · pytest · Vitest · Tailwind · GitHub Actions CI.

Contact: **lorienslibrary@gmail.com**.

---

## What's real

| Artifact | Evidence | Status |
|---|---|---|
| **CAMA** | Eight-layer multi-tenant architecture · 187 tests in CI · 27-subtest safety benchmark (100% pass) · Docker quickstart · [DATA_HANDLING.md](https://github.com/LoriensLibrary/cama/blob/main/DATA_HANDLING.md) · [SECURITY.md](https://github.com/LoriensLibrary/cama/blob/main/SECURITY.md) · [`v0.1.0`](https://github.com/LoriensLibrary/cama/releases/tag/v0.1.0) tagged | Operational research deployment (single-participant); multi-tenant code shipped |
| **Telos · for Kalos** | [Live Vercel demo](https://telos-kalos.vercel.app) · React 19 + TS + Vite + Vercel · `@anthropic-ai/sdk` + `hono` + `drizzle-orm` + `@neondatabase/serverless` in `package.json` · `api/draft-message.ts` calls Claude Haiku 4.5 · 42 tests across 6 suites · [`v0.1.0`](https://github.com/LoriensLibrary/Telos_kalos/releases/tag/v0.1.0) tagged | Working applicant prototype |
| **Project-Companion** | UI prototype (student / teacher / parent dashboards) · MVP CAMA read tile via `useCamaMemory` · MOCK TUTOR MODE default (no live AI calls without explicit developer opt-in) | Design prototype; backend proxy + COPPA consent + CAMA write integration are explicit roadmap |
| **Continuity Burden Dataset** | [HuggingFace dataset](https://huggingface.co/datasets/LoriensLibrary/cama-continuity-burden) · 66,380 messages · 825 conversations · aggregate statistics only | Published; raw corpus intentionally not released |
| **Preprints** | [11 DOI-registered papers](https://orcid.org/0009-0005-5803-8401) on Zenodo · ORCID 0009-0005-5803-8401 | Published Mar–Apr 2026 |

---

## Repositories

- **[Loriens_Library](https://github.com/LoriensLibrary/Loriens_Library)** — Index repo. Architecture overview, full preprint list, links to everything else. Start here if you're new.
- **[cama](https://github.com/LoriensLibrary/cama)** — The platform. Circular Associative Memory Architecture: provenance-aware three-layer persistent memory for human–AI interaction. Single-participant operational research deployment (~53,000 memories on the author's instance).
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

<sub>*Repos live under this **LoriensLibrary** account (the public face of Lorien's Library LLC); individual commits are authored by **CyberDaVincii**, my developer identity on the same email — same person, different hat.*</sub>

---

MIT licensed. © 2026 Lorien's Library LLC.
