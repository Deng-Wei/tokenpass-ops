# TokenPass Ops Skill

A Codex skill for working on TokenPass product planning, model and price catalogs, bilingual site changes, and release verification.

## Install for Codex

Copy this folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R tokenpass-ops ~/.codex/skills/tokenpass-ops
```

Then restart or refresh Codex's skill discovery if needed. You can invoke it explicitly as `$tokenpass-ops`; automatic selection is enabled by default.

## Contents

- `SKILL.md` — when and how to apply the workflow
- `references/product-map.md` — sanitized product map with roadmap status boundaries
- `references/catalog-and-release.md` — verification and release workflow
- `agents/openai.yaml` — display metadata

The product map was distilled from TokenPass planning documents. It does not certify current production capabilities. Always verify live claims against the current source and production behavior.
