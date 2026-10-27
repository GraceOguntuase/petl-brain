# NOBL — Parker brand brain

NOBL Travel's creative-strategy brain, built by NSY Digital with Parker, 2026-09-17 to 2026-09-21. It holds what's true about NOBL's ad account, customers, competitors, and rules, and Parker thinks with it.

## Where to start

**Open this folder in Claude Code and run `/get-started`.** It walks you through what's here and what to do first, and anyone on the team can run it any time.

Then, if you want to read:

1. `sub-context-docs/brand-profile-narrative.md` — the one-page NOBL summary. Parker reads it first on every question.
2. `brand-lens.md` — NOBL's rules: the $279 price, never naming competitors, the TSA rules, claims to avoid.
3. `audits/INDEX.md` — the account audits, newest first.
4. `personas/personas-profile.md` and `personas/persona-voice-library.md` — who buys and the exact words they use.
5. `sub-context-docs/competitive-landscape.md` — the field: Away, Monos, July, LEVEL8, Béis, and Rimowa as the unnamed anchor.
6. `running-notes/` — the team, the rules, what NOBL hasn't told us yet (`missing-context.md`), and when each doc is due for a refresh (`refresh-schedule.md`).

## This is a lean build

Built on purpose as a small working brain, following the Alex Cooper and Jimmy course method: the core docs now, more on request. `running-notes/refresh-schedule.md` lists every doc that isn't built yet with the prompt that builds it. Ask Parker "build the [doc]" when you need one.

## Data surfaces

- **Pulled:** Meta ads account NT1 and ad comments (Parker MCP), the TikTok inspiration library, the tracked competitor ad libraries (Monos, Away, July, Béis, LEVEL8), Grace's Trustpilot and Okendo review export (2026-08-18, 5-star only), public review sites and press, and NSY's Notion, Slack, and strategy files.
- **Dark:** post-purchase surveys, full-star-range reviews in Parker, Northbeam, order and LTV data, direct Reddit and TikTok reads.

## How it's put together

- **Skills** live in `.claude/skills/` (scriptwriting, hooks, headlines, iterations, ad-account analysis, AI ad generation, the routines, and more). They load when this folder is opened in Claude Code.
- **The method** is mounted read-only at `parker-system/`, a pinned release (v22) of the public `parker-brain` repo, including the exact prompts that built every doc. `/update-brain` offers newer releases; nothing changes without a yes.
- **Saving:** this folder is backed up to a private GitHub repo Parker manages (`parker-brain/grace-s-org-nobl`). `/save-brain` has the procedure.
