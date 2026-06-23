# Repo Schema & Agent Guide

This repo holds XRPL build ideas in two layers:

1. **Human source of truth** — the prose Markdown lists:
   - [`hackathon/index.md`](hackathon/index.md) — scoped, demoable builds (24–72h)
   - [`platform/index.md`](platform/index.md) — longer-term, VMT-driven products
   - [`make-waves/index.md`](make-waves/index.md) — 74 market opportunities (gaps to fill)
2. **Machine-readable index** — [`ideas.json`](ideas.json), one normalized record per idea
   across **all** sections. This is what an agent reads.

When the Markdown changes, `ideas.json` must be regenerated to match.

---

## `ideas.json` record schema

Each entry in the top-level `ideas` array:

| Field | Type | Notes |
|---|---|---|
| `id` | string | Stable id. `hack-NN`, `plat-NN`, or the source `OPP-NNN` for Make Waves. |
| `title` | string | Display name. |
| `description` | string | One-line summary. |
| `source` | enum | `hackathon` \| `platform` \| `make-waves`. |
| `theme` | string | Section/category within the source (e.g. `DeFi`, `Impact & Social Good`). |
| `type` | enum\|null | `app` (for users) \| `tool` (for builders) \| `null` (not classified). |
| `tier` | enum\|null | `high` \| `medium` \| `low` \| `null`. Impact/priority, from Make Waves only. |
| `xrpl_features` | string[] | XRPL primitives the idea uses (e.g. `Escrow`, `AMM`, `RLUSD`). |
| `tags` | string[] | Free-form topic tags. |
| `status` | enum | `idea` (default) \| `in-progress` \| `built` \| `deprecated`. |
| `overlaps_with` | string[] | Ids of near-duplicate ideas in other sections. Dedup is deferred. |

The top level also carries `meta` (counts, enum vocab, source URL) for quick orientation.

---

## How an agent should use this repo

When helping a builder **refine or choose** an idea:

1. **Load `ideas.json`**, not the Markdown — it has the structured fields.
2. **Narrow by the builder's constraints:**
   - Time/scope → prefer `source: "hackathon"` for short builds, `platform`/`make-waves` for ventures.
   - Audience → `type: "app"` (end users) vs `type: "tool"` (other builders).
   - Ambition/impact → `tier: "high"` for ecosystem-multiplier bets.
   - Skills/interest → match `xrpl_features` and `tags` (e.g. only `AMM` + `DeFi`).
3. **Check `overlaps_with`** before recommending — surface related ideas across sections so
   the builder sees the fuller design space and prior framing, and can pick the richest version.
4. **Refine, don't just list:** propose a concrete MVP, name the exact XRPL transactions involved
   (from `xrpl_features`), and apply the source's own selection tests — for hackathon ideas, the
   "can you demo a working transaction in 24h / does usage generate on-chain txns" checklist at the
   bottom of `hackathon/index.md`; for platform ideas, the VMT/MVP/sustainability checklist in
   `platform/index.md`.
5. **Respect provenance:** Make Waves entries are market gaps sourced from the
   [XRPL Builder Opportunities registry](https://xrpl-builder.vercel.app/en/opportunities); cite
   their `OPP-NNN` id and `tier` when recommending.

To **add** an idea: append the prose entry to the right Markdown file, then add a matching
record to `ideas.json` (set `status: "idea"`, fill `overlaps_with` if it echoes an existing one).
