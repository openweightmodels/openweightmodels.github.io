# Open Weight Models

**Independent reference for open-weight AI models, licenses, hardware, inference, deployment and structured model data.**

Canonical website: **https://openweightmodels.eu/**  
Hugging Face: **https://huggingface.co/open-weight**

## Mission

Open Weight Models is a source-first technical reference for developers, researchers and infrastructure teams evaluating AI models whose trained weights can be obtained and run outside the original publisher's hosted API.

The project is intentionally broader than a model list. It tracks the operational questions that determine whether a model is actually usable:

- What does “open weight” mean?
- Which checkpoint and model family is being discussed?
- What license governs the weights?
- Is commercial use permitted?
- What architecture, size and context window are involved?
- Which formats and quantizations exist?
- What RAM / VRAM and accelerators are realistic?
- Which runtimes can serve the model?
- Where is the primary source?
- When was the record last verified?

## GitHub + Hugging Face

The two surfaces have different jobs:

- **GitHub Pages** — canonical long-form reference, definitions, registry and machine-readable metadata.
- **Hugging Face `open-weight`** — interactive Spaces, Collections, datasets and open-weight ecosystem tooling.

## Machine-readable resources

- `data/models.json` — curated family-level registry
- `llms.txt` — concise guide for AI systems and retrieval tools
- `sitemap.xml` — canonical resource discovery
- `robots.txt` — crawler policy

## Editorial rules

1. Prefer primary model-publisher sources.
2. Treat **open weight** and **open source** as distinct claims.
3. Record checkpoint-specific licenses; do not infer rights from a family name.
4. Do not present a benchmark as an overall model-quality score.
5. Include a `verified` date with structured records.
6. Link to the source instead of reproducing third-party model cards.
7. Update or remove stale records when official releases change.

## Current registry and EU deployment lens

The public registry now contains **64 selected open-weight model profiles**: **32 Gold-standard Model Passports** with full technical, license and deployment review plus **32 current source-verified profiles**. Provider origin, EU/EEA self-hosting, data-residency considerations and commercial-use notes are recorded separately.

The registry spans general-purpose, reasoning, coding, multimodal, edge, enterprise and open-research models. Provider origin is recorded separately from deployment location and data residency.

A dedicated **EU Deployment Lens** adds:
- provider country / region metadata
- EU/EEA self-hosting as a technical deployment option
- data-residency notes for inference, RAG, embeddings, logs and backups
- commercial-use constraints
- GDPR and AI Act context without assigning blanket compliance badges

Public resources:
- `/eu/`
- `/data/eu-model-lens.json`
- `/data/models.json`
- `/data/licenses.json`
- `/data/deployments.json`

This is **not** an exhaustive leaderboard. Every entry should remain tied to a primary source and a verification date.

---

Open Weight Models is an independent reference project and is not affiliated with the model developers listed on the site.


## OWM Model Passport v0.2

The Passport layer now contains **20 exact model/checkpoint records**.

A new evidence class, **third-party measured**, records externally measured runtime results without presenting them as Open Weight Models tests. The first four records include llm-speed signed community runs and a SemiAnalysis InferenceX lab measurement.

Machine-readable resources:

- `/passports-index.json`
- `/data/passports/*.json`
- `/runtime-evidence.json`
- `/owm-passport.schema.json`
- `/changes.json`
- `/OWM-PASSPORT-SPEC.md`


## Editorial position & sovereignty

The public reference now includes a long-form editorial position on:

- what an open-weight model is
- why open weight is not the same as Open Source AI
- why OWM views open weights as strategic infrastructure optionality
- the OWM Sovereignty Lens
- what open weights do **not** guarantee

Files:
- `OWM-EDITORIAL-POSITION.md`
- `data/sovereignty-lens.json`

The project deliberately takes a nuanced position: **the future is likely hybrid**, with proprietary APIs and open-weight deployment coexisting.


## v8 — Detailed model references

Ten model-specific reference pages are now available under `/models/`.

Each page includes:
- answer-first model summary for search and generative engines
- OWM editorial view
- exact checkpoint facts
- license reality
- hardware reality
- runtime evidence policy
- OWM Sovereignty Lens
- where-it-fits / where-it-does-not-fit guidance
- FAQ structured data
- TechArticle + Breadcrumb + FAQ JSON-LD
- canonical URL, Open Graph, metadata and internal links
- primary sources and machine-readable Passport link

The ten launch references are gpt-oss-20b, gpt-oss-120b, Qwen3-32B, Qwen3-Coder-30B-A3B-Instruct, DeepSeek-R1, Gemma 3 27B IT, Mistral Small 4, Llama 4 Scout, OLMo 3 32B and GLM-4.5.


## v8.1 — GitHub Pages-safe model URLs

The detailed model references are additionally published as root-level static HTML files:

- `/models.html`
- `/model-deepseek-r1.html`
- `/model-qwen3-32b.html`
- etc.

`.nojekyll` is included so GitHub Pages serves the repository as plain static files.
The previous clean `/models/<slug>/` structure is retained as a compatibility copy, and `404.html` redirects legacy clean model paths to their canonical flat URLs.


## v8.3 — Inline styling fix

The 10 detailed model reference pages and `models.html` now contain their full CSS inline.
They no longer depend on `/assets/model-reference.css`, so the pages remain fully styled even if GitHub Pages does not serve the asset path correctly.


## v9 — 20 complete model references + observed Change History

All 20 Passport models now have detailed human-readable reference pages.

New change-history layer:
- `/changes.html`
- `/change-history-index.json`
- `/change-watchlist.json`
- `/change-history.schema.json`
- `/change-<model>.json`
- `/OWM-CHANGE-HISTORY.md`

OWM history begins on 2026-09-27. The project intentionally does not reconstruct an unobserved past. Each model starts with a verified baseline; future material license, checkpoint, runtime, hardware, context, provider and access changes can be appended as dated events.
