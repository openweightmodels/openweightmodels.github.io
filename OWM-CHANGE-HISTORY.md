# OWM Change History Methodology

Open Weight Models starts observed history on **2026-09-27**.

## Principle

We record what changed **after OWM began observing the model**. We do not manufacture a retroactive timeline from incomplete memories or current pages.

## Watched fields

- model card
- license / usage terms
- checkpoint files
- quantizations
- runtime support
- context claims
- hardware guidance
- provider availability
- access / gating status

## Event classes

- `initial-snapshot` — first OWM baseline
- `license-change`
- `model-card-change`
- `checkpoint-added`
- `checkpoint-removed`
- `runtime-added`
- `runtime-removed`
- `context-change`
- `hardware-guidance-change`
- `provider-change`
- `access-change`
- `owm-runtime-test-added`
- `correction`

Each event should contain a date, evidence class, concise summary, detail and source.

## Editorial rule

A repository edit is not automatically important. OWM should record a change when it can affect a user's understanding of access, rights, deployment, compatibility, performance evidence or model identity.
