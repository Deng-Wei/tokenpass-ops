---
name: tokenpass-ops
description: Use when planning, building, verifying, or operating TokenPass, including model and price catalog work, bilingual site changes, alerts, router features, or product documentation.
---

# TokenPass Operations

Use this skill to work on TokenPass consistently across product planning, website implementation, catalog maintenance, and release checks.

## Start with the current state

1. Locate the active TokenPass checkout and read its `AGENTS.md` and relevant project instructions before editing.
2. Inspect `git status` and preserve all existing user changes. Do not use the public Skill repository as a substitute for the website source repository.
3. Classify each relevant claim as **implemented**, **planned**, **proposed**, or **unverified**. Product plans describe intent; they do not prove a feature is live.
4. For live behavior, inspect the current source, production API, or deployed page as appropriate. Record what was actually checked and when.

## Work by request type

- **Product or roadmap work:** Read [product-map.md](references/product-map.md). Preserve the difference between personal and team use cases, and date roadmap assumptions.
- **Model catalog or pricing work:** Use current provider documentation and the project's canonical catalog/update scripts. Read [catalog-and-release.md](references/catalog-and-release.md) before changing data or publishing.
- **Website or backend changes:** Follow the active repository's own instructions. Avoid editing generated model comparison pages by hand; find and update their canonical source or generator.
- **Marketing or public product copy:** State only verified capabilities as available. Label plans as planned, avoid unsupported savings claims, and keep Chinese and English pages aligned.
- **Release or deployment:** Follow the active project instructions and required checks. A local change, commit, deployment, production readback, and user acceptance are separate states. Do not deploy production without the authorization required by the project instructions.

## Data, privacy, and reliability

- Treat exact model IDs, availability, input/output prices, modalities, limits, and effective dates as separate facts. Verify each from a current source; do not infer one from another.
- Keep source URL, checked date, and confidence/provenance alongside price decisions when the project supports those fields. Flag conflicts or stale data for review instead of silently choosing a value.
- Never put API keys, member data, unpublished financial assumptions, or private business notes in public files, logs, screenshots, or commits.
- Do not send prompts, customer data, or credentials to an external classifier or provider unless the user has authorized that data flow and the implementation is clear about it.
- Prefer conservative recommendations when model suitability is uncertain. Preserve user control over model switching and disclose material tradeoffs.

## References

- Read [product-map.md](references/product-map.md) for a sanitized overview of documented product areas and roadmap status cautions.
- Read [catalog-and-release.md](references/catalog-and-release.md) for catalog verification, bilingual consistency, and release evidence.
