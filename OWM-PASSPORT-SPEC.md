# OWM Model Passport v0.2

Open Weight Models treats the **exact deployment claim** as the core unit of information.

## Evidence labels

- **Source verified** — OWM reviewed the cited primary source.
- **Publisher stated** — a statement made by the model publisher.
- **OWM estimate** — a transparent calculation or engineering estimate; not a deployment guarantee.
- **Third-party measured** — an external benchmark with a traceable source. OWM has not reproduced it.
- **OWM runtime tested** — reserved only for a configuration physically reproduced by Open Weight Models.
- **Unknown** — no sufficiently reliable evidence has been recorded yet.

This distinction matters. A signed community benchmark or independent lab benchmark is useful evidence, but it is not an OWM test.

## v0.2 scope

The Passport set contains 20 exact model/checkpoint records spanning general-purpose, reasoning, coding, multimodal and research models.

Four runtime-evidence records are included:
- gpt-oss-20b — signed llm-speed community run
- Qwen3-32B — signed llm-speed community run
- Gemma 3 27B — signed llm-speed community run
- DeepSeek-R1 — SemiAnalysis InferenceX lab measurement

## Change history

History starts on 2026-09-27. Future automation should watch:
- model cards
- license files
- checkpoint metadata
- runtime support
- quantizations
- provider availability

## Legal note

License summaries are informational and are not legal advice. Always verify the exact checkpoint license, policies and applicable law before production use.
