# Open Weight Models

**Independent reference for open-weight AI models, licenses, hardware, inference, deployment and structured model data.**

Website: **https://openweightmodels.github.io/**  
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

## Current registry

The first expanded registry includes selected families from OpenAI, Meta, Qwen/Alibaba, Mistral AI, DeepSeek, Moonshot AI, Z.ai, Microsoft, IBM, Google DeepMind, MiniMax and NVIDIA.

This is **not** an exhaustive leaderboard.

---

Open Weight Models is an independent reference project and is not affiliated with the model developers listed on the site.
