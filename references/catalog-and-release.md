# Catalog, Site, and Release Workflow

Use this reference for changes to model listings, prices, comparison pages, bilingual UI, or production releases. The active TokenPass checkout's `AGENTS.md` and current scripts remain authoritative; re-read them because project rules can change.

## Model and price updates

1. Identify the canonical catalog source and the generator/update script for the affected data. Avoid editing generated comparison pages directly.
2. Verify the exact model identifier and relevant features from current provider documentation. Check lifecycle status and whether the model can actually be called through the listed route when that distinction matters.
3. Verify input and output prices, units, currency, cache/audio/image pricing where applicable, context limits, and effective date separately. Save source and checked date.
4. Compare independent evidence where the project's policy requires it. If sources conflict, mark the record for review rather than inventing a reconciliation.
5. Run the project's scoped validation for the affected catalog and generated pages. Review the result and report exactly which checks ran.
6. Check model selector results and relevant Chinese and English pages after generation. Confirm that labels, price units, links, and availability agree.
7. Keep discovery separate from production: a candidate found in a provider announcement is not yet a verified catalog entry or a deployed page.

## Website changes

- Read repository-local instructions and inspect the current working tree before editing.
- Preserve existing user changes; keep the change limited to the request.
- For bilingual changes, verify both languages and avoid untranslated text except proper names and model IDs.
- For user-visible prices or model status, verify a production readback after deployment when authorized. A successful build or deploy command alone does not prove that production serves the intended result.

## Release evidence

Report distinct states instead of collapsing them into “done”:

- source changed;
- structural or scoped checks completed;
- rendered or locally exercised;
- committed;
- deployed;
- production behavior read back;
- user accepted.

Do not claim a later state based on evidence for an earlier one. Before a production deployment, follow the current project-specific authorization requirement. Never use destructive Git operations to clean up user changes.
