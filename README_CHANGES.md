# Prompt Update Package — Retire Tier 1 §6, consolidate next-run vectors into Layer 1 §8
**Prepared:** 17 June 2026
**Lifecycle:** Stage 01 — InterpretationArtifacts (NOT_AUTHORIZED)

Drafts for review and commit. Nothing here is canonical until RJ's explicit AuthorizationAct.

---

## What changed and why

The Tier 1 brief's §8 item "Suggested searches for next run" and the Layer 1 §8 "Recommended search vectors for next Tier 1 run" were doing the same job from different vantage points. Layer 1 has the corpus-wide view (coverage gaps + weak-signal watch list across every brief in scope); Tier 1 had only a single run's view. Two sources producing the same artifact is a divergence risk. The change retires the weaker (Tier 1) source and makes Layer 1 §8 the single authoritative source.

---

## Package contents

| File | What it is | Status |
|---|---|---|
| `ABCF-v1_Monitoring_Prompt_v2.0.md` | Full Tier 1 prompt, edited | Complete file — built by surgical edit of your canonical v1.5 |
| `ABCF-v1_Corpus_Layer1_v1.1.md` | Full Layer 1 prompt, edited | Complete file |
| `README_CHANGES.md` | This file | — |

The Tier 1 v2.0 file was produced by copying your uploaded canonical v1.5 and applying only the edits below — every untouched section (including the §9.1–§9.9 publication concept lists) is byte-for-byte identical to your source.

---

## Exact edits applied to Tier 1 (v1.5 -> v2.0)

Seven hunks, verified by diff against your canonical source:

1. **Header** — version -> 2.0; last revised -> 17 June 2026; new change-from-v1.5 note.
2. **§8 item 6** — "Suggested searches for next run" **removed**.
3. **§8 items 7–10** — renumbered to **6–9**.
4. **§8 item 8** annotation — updated to "renumbered from §8 item 9 in v1.5".
5. **§8** — pointer blockquote added: next-run vectors come from Layer 1 §8.
6. **§10** — "(§8 items 1–10)" -> "(§8 items 1–9)".
7. **§10 brief-header template** — `Prompt version: 1.5` -> `2.0`; and end marker -> "version 2.0".

All `*(new in v1.5)*` provenance annotations were intentionally preserved — they record when a feature was added and should not change on a version bump.

## Exact edits applied to Layer 1 (v1.0 -> v1.1)

1. **Header** — version -> 1.1; change-from-v1.0 note.
2. **§8** — reframed as the sole authoritative source of next-Tier-1 vectors; per-query new-vs-refinement and P-ref/weak-signal tagging added; cadence note added.

> Diff both files against your canonical sources before committing — the one thing this package can't verify is whether your live source already drifted from what was uploaded.

---

## Version bumps (confirm or override)

- **Tier 1: v1.5 -> v2.0 (MAJOR).** Removing a brief output section is a structural change to output format. Override to v1.6 only if you judge the removal trivial.
- **Layer 1: v1.0 -> v1.1 (MINOR).** Addition/clarification; no framework change.

---

## Tradeoff you are accepting (named, for a conscious yes)

**Cadence coupling.** Tier 1 runs often; Layer 1 runs on demand. With the Tier 1 per-run suggestions gone, consecutive Tier 1 runs between Layer 1 passes rely only on the standing prompt vectors (§3 / §3a / §3b). That is by design — the standing vectors are the engine — but next-run guidance now refreshes on Layer 1's clock. The Layer 1 §8 cadence note states this.

---

## Open decision nodes (RJ + system)

- **D1** — Confirm MAJOR vs MINOR for the Tier 1 bump.
- **D2** — Confirm acceptance of the cadence-coupling tradeoff.
- **D3** — Repo hygiene: the highest-version Tier 1 prompt was uploaded as `ABCF-v1_governance_monitoring_brief_prompt-v1_5.md`, which diverges from the `prompts/ABCF-v1_Monitoring_Prompt_vX.X.md` convention used by v1.3 and assumed by PROJECT_INSTRUCTIONS and the "load highest version in prompts/" rule. This package names the v2.0 file `ABCF-v1_Monitoring_Prompt_v2.0.md` to restore the convention. Confirm the target path and reconcile the old filename so "load highest version" resolves unambiguously.

---

*Stage 01 InterpretationArtifacts. No action authorized without RJ's explicit AuthorizationAct.*
