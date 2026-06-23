# XRPL Community Ideas

A repository of ideas for the XRPL builder community.

[Hackathon Ideas](hackathon/index.md)
A list of projects with a small enough scope to be done over a hackathon.

[Platform Ideas](platform/index.md)
A list of more ambitious projects, categorized by domain.

[Make Waves](make-waves/index.md)
74 market opportunities — gaps the ecosystem needs filled — sourced from the XRPL Builder Opportunities registry.

---

## How to use this guide

**Manually.** Browse the three lists above. Pick the section that matches your
ambition — [Hackathon](hackathon/index.md) for a weekend build, [Platform](platform/index.md)
for a venture, [Make Waves](make-waves/index.md) for an open market gap — then use the
selection checklist at the bottom of each page to scope what you pick.

**With an AI agent.** This repo is built to be read by an agent that interviews you and
recommends ideas that fit. [`ideas.json`](ideas.json) is a machine-readable index of every
idea across all sections, and [`SCHEMA.md`](SCHEMA.md) documents its fields plus how an agent
should use them. Paste the prompt below into your agent (Claude Code, Cursor, ChatGPT, etc.):

```
You are helping me decide what to build on the XRP Ledger.

First, read these two files from the XRPL Community Ideas repo:
- https://raw.githubusercontent.com/XRPL-Commons/community-ideas/main/ideas.json
- https://raw.githubusercontent.com/XRPL-Commons/community-ideas/main/SCHEMA.md

Then interview me ONE question at a time to understand:
1. Time & scope — a weekend hackathon, or a multi-month venture?
2. Audience — am I building for end users (type "app") or for other builders (type "tool")?
3. Skills & interest — which XRPL features or themes excite me
   (e.g. Escrow, AMM, DEX, NFTs, RLUSD, payments, DeFi, AI agents, impact)?
4. Ambition — a focused niche, or a high-tier ecosystem bet?

After my answers, recommend the 3 ideas from ideas.json that fit me best. For each:
- its id, title, and source section;
- why it fits what I told you;
- a concrete MVP I could ship first;
- the exact XRPL transactions it would use (from xrpl_features);
- any related ideas via overlaps_with that I should look at before committing.

Then help me refine the one I choose into a buildable spec.
```

Edit this site on [github](https://github.com/XRPL-Commons/community-ideas)
