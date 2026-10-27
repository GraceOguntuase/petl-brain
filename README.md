# PETL — Parker brand brain

PETL's (goPETL, gopetl.com) creative-strategy brain, built by NSY Digital on 2026-10-27. It holds what's true about PETL's ad account, customers, competitors, and rules, and Parker thinks with it.

## Start here

1. `sub-context-docs/brand-profile-narrative.md` — the one-page PETL summary. Parker reads it first on every question.
2. `brand-lens.md` — PETL's rules: Apple wording, charge claims, return wording, price and offers, what has worked and failed.
3. `sub-context-docs/website-and-product-audit.md` — the product, offers, and the claims that are safe, need exact wording, or must be avoided in scripts.
4. `personas/` — who actually buys (75.9% aged 55+, 65.5% women, last 90 days) and the exact words they use.
5. `audits/2026-10/2026-10-monthly-performance-report.md` — the account's present tense.
6. `sub-context-docs/competitive-landscape.md` — The Ridge, Kuxiu, Anker, Apple, Ugreen and the rest.
7. `production/` — the creator filming guide and the B-roll tracker.
8. `running-notes/` — the team, the rules, what PETL hasn't told us yet (`missing-context.md`), and when each doc is due for a refresh (`refresh-schedule.md`).
9. `source-pulls/` — the raw material: the internal digest (Notion, Slack, Fathom, Meta), the outside research report, and Grace's Claude project export.

Built on purpose as a small working brain: the core docs now, more on request. `running-notes/refresh-schedule.md` lists every doc that isn't built yet with the prompt that builds it. Ask Parker "build the [doc]" when you need one.

## Data surfaces

- **Pulled:** the Meta ads account (3803347073290974) through the Meta ads MCP, competitor ads through AdWhispr and the Meta Ad Library, NSY's Notion, Slack, Fathom, Gmail and Drive, Grace's Claude project export (survey of 1,144 orders, FB comments, syncs, website copy), gopetl.com, and public web research.
- **Dark:** Parker MCP (trial ended), the full Judge.me review set (19 of 1,454 read), Shopify order and margin data, Reddit, US TikTok ads, video hook and hold rates.

## How it's put together

- **Skills** live in `.claude/skills/` (scriptwriting, hooks, headlines, iterations, ad-account analysis, AI ad generation, the routines, and more). They load when this folder is opened in Claude Code.
- **The method** is mounted read-only at `parker-system/`, a pinned release (v22) of the public `parker-brain` repo, including the exact prompts that built every doc.
- **Saving:** this folder is backed up to Grace's private GitHub repo (`GraceOguntuase/petl-brain`). Save with `git -c credential.helper= -c credential.helper=osxkeychain push grace main`.
