# Contributing to the Reveries enrichment schema

Thank you for your interest. This schema is a living document — it improves through use, critique, and the accumulated experience of people who work seriously with dreams.

## Three ways to contribute

### 1. Propose a new symbol

The current symbol vocabulary has 16 slugs. If you encounter dreams that don't map cleanly to any of them, open a GitHub Issue with:
- The proposed symbol name and slug
- 3–5 example dreams where it would apply
- Why existing slugs don't cover it
- Any relevant Jungian amplification material

These are discussed in the Schema Room (inside the Reveries app) before becoming formal proposals.

### 2. Propose a field refinement

If an existing field is ambiguous, inconsistently applied, or would be more useful in a different form, open a GitHub Issue with:
- The field name and current definition
- The proposed change
- The schema impact: does this require a migration? A backfill? Does it break existing data?
- A confidence tier assessment: does the change affect which tier the field belongs to?

### 3. Report a classification error

If you find a dream in the corpus where the enrichment is clearly wrong — a field that misidentified an archetype, a confidence tier that seems miscalibrated — open an Issue with the dream ID and your analysis.

## What happens after you open an issue

Issues are reviewed by the maintainer. Some will be discussed in the Schema Room. Those that reach informal consensus become formal PRs. The maintainer makes the final decision on what merges.

This is not a democracy. It is a transparent process with a clear decision-maker. The maintainer's responsibility is to hold the philosophical integrity of the schema — to ensure that changes serve depth, not convenience.

## What will not be merged

- Changes that flatten Tier 3 fields into Tier 1 certainty
- Symbol additions that are culturally specific without cross-cultural amplification support
- Structural changes proposed without schema impact analysis
- Any change that removes the epistemic tier from a field

## Schema versioning

The schema follows semantic versioning. Breaking changes increment the major version. Additive changes increment the minor version. The version travels with any data export.

Current version: 1.0
