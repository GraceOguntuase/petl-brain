# Refresh schedule — PETL

This is the one place that tracks when every standing doc was last run and when it is due to be re-run. Each doc's own `generated_on` and `refresh_by` frontmatter is the source of truth; this file aggregates them so the brain's freshness reads at a glance. The cadence policy, and the real-world triggers that override the calendar, live in `parker-system/system/refresh-cadence.md`.

## How Parker uses this

- When you load this brain or consult a standing doc, compare each due date to today. Past due is overdue; within about two weeks is due soon. Say so plainly and offer to re-run the generating prompt by name. Don't silently keep using a stale doc, and don't re-run without saying so first.
- A refresh is a re-run of the generating prompt in `parker-system/prompts/`. It takes the prior version as context, carries forward what's still true, and re-stamps `generated_on` and `refresh_by`. Update the line here after.
- Triggers outrank the calendar. For PETL the live ones are: a price or ladder move (six in 2026, and a tariff increase is confirmed with no date), the Black Friday offer landing, the PETL 2 Plus Burgundy, Glacier and Silver launch on 2026-11-04, the leather case (about early December), a new competitor push (Kuxiu entered 2026-10-15), and Rakesh answering any claim question in `missing-context.md`. When one fires, mark the affected doc due now and note why.
- When two or more foundation docs have been re-run, `sub-context-docs/brand-profile-narrative.md` is due regardless of date (not built yet, see below).
- **Re-check the live PDP before every batch** no matter what this schedule says. *(stated · Grace, docs/01)*

## Built — the lean PETL brain (2026-10-27)

All built on 2026-10-27, method pinned at parker-brain v22. Due dates come from each doc's `refresh_by`; where a doc carries none, the line says so and gives the cadence it follows.

### Brand foundation
- `sub-context-docs/website-and-product-audit.md` — last run 2026-10-27 — **due 2026-12-15** (set early: prices, BF offer, Nov 4 colors and the leather case are all moving; re-check the PDP every batch)
- `sub-context-docs/competitive-landscape.md` — last run 2026-10-27 — **due 2027-01-15** (watch-closely check of the emerging set, Kuxiu included, around 2026-12-08 after Cyber Monday)
- `sub-context-docs/brand-identity-analysis.md` — last run 2026-10-27 — **due 2027-04-27** (set six months early because the claim set is unsettled; re-run sooner if the PDP is rewritten, a patent lands, or a brand guide ships)

### Personas and customer language
- `personas/personas-profile.md` — last run 2026-10-27 — **due 2027-01-15** (re-run after BFCM with a fresh post-purchase survey export)
- `personas/persona-voice-library.md` — last run 2026-10-27 — **due 2027-01-15**
- `personas/voice-of-customer/voc-pain-phrase.md` — last run 2026-10-27 — **due 2027-01-15**
- `personas/voice-of-customer/voc-objection.md` — last run 2026-10-27 — **due 2027-01-15**

### Account audits
- `audits/2026-10/2026-10-monthly-performance-report.md` — last run 2026-10-27 — **due 2026-11-26** (+30d; the November report)

### Production
- `production/creator-filming-guide.md` — last updated 2026-10-27 — no `refresh_by` in frontmatter. Update when the writing rules, specs or claims move, and check it against `brand-lens.md` each round.
- `production/broll-tracker.md` — last updated 2026-10-27 — no `refresh_by` in frontmatter. Its own note says update it every round; next due with the Black Friday round.

### Running notes (maintained, not regenerated)
- `brand-lens.md`, `running-notes/brand-notes-from-org.md`, `brand-rules.md`, `success-definition.md`, `missing-context.md`, `standard-sync.md` — all last updated 2026-10-27. Updated in the memory pass whenever the team teaches Parker something; no calendar date.

### Source pulls (raw material, dated captures)
- `source-pulls/internal-sources-digest.md` — compiled 2026-10-27 — no `refresh_by`. Re-pull before the next quarterly audit, or sooner when the BF offer lands; the Meta section dates fastest.
- `source-pulls/external-research-2026-10.md` (and its copy at `source-pulls/reports/PETL brand and market research.md`) — 2026-10-27 — no `refresh_by`. Re-pull with the competitive-landscape refresh.
- `source-pulls/research_notes/PETL brand and market research/` (audience_and_market, category_ads_and_whitespace, petl_brand_and_reviews) — 2026-10-27 — no `refresh_by`. Same cadence as the external research.
- `source-pulls/source-index.md` — 2026-10-27 — update whenever a pull is added.
- `source-pulls/_exports/grace-claude-project-2026-10-27/` — Grace's export, frozen as of 2026-10-27. Not refreshed; a newer export replaces it as a new dated folder.

## Not built yet — build on request

The lean build skipped these. Each has its generating prompt ready in `parker-system/prompts/`. Say "build the [doc]" and Parker runs it, or a routine picks it up. Most useful first.

### Most useful next
- `audits/2026-Q4/90-day-performance-audit.md`, `90-day-creative-strategy-audit.md`, `90-day-diversity-audit.md`, `customer-review-audit.md`, `quarterly-whitespace-analysis.md` — prompts in `audits-quarterly/` (the diversity audit maps straight onto Rakesh's Andromeda grading; the review audit needs the Judge.me export)
- `audits/2026-10/2026-10-monthly-hook-audit.md` — prompt `audits-monthly/monthly-hook-audit.md` (needs hook-level creative pulls)
- `sub-context-docs/performance-targets-and-metrics.md` — prompt `brand-profile/performance-targets-and-metrics.md` (targets are stated; see `brand-rules.md`)
- `sub-context-docs/ad-account-evaluation.md` — prompt `brand-profile/ad-account-evaluation.md`
- `sub-context-docs/marketing-calendar-and-campaigns.md` — prompt `brand-profile/marketing-calendar-and-campaigns.md` (urgent value with BF, CM and the Nov 4 launch)
- `sub-context-docs/visual-vocabulary.md` — prompt `brand-profile/visual-vocabulary.md`
- `sub-context-docs/brand-profile-narrative.md` — prompt `brand-profile/brand-profile-narrative.md`
- `open-loops/[date]-consolidated-roll-up.md` — prompt `open-loops/open-loops-roll-up.md` (the `/research-loops` routine runs it)
- `strategy/product-priority.md`, `persona-strategy-input.md`, `messaging-strategy-input.md`, `creator-talent-strategy-input.md`, then `strategy/strategic-roadmap.md` — prompts in `strategic-roadmap/`
- Competitor deep-dives for Apple, Anker, The Ridge and the commodity marketplace bank (the deep-audit set in `competitive-landscape.md`) — prompts in `competitor-profile/`: `competitor-snapshot`, `competitor-ad-account-evaluation`, `competitor-brand-identity-analysis`, `competitor-website-and-product-audit`, `competitor-reviews-and-customer-language`, `competitor-customer-and-persona-discovery`, `competitor-reputation-analysis`, `competitor-community-and-forums`, `competitor-organic-channels-audit`, `running-notes-on-competitor`, `working-thesis-synthesis`

### Later
- **Brand profile:** `category-and-market-research`, `customer-journey-and-persona-discovery`, `reputation-analysis`, `community-and-forums`, `operations-and-team`, `organic-channels-inventory` — prompts in `brand-profile/`
- **Personas companions:** `lifecycle-journey-maps`, `cross-persona-bias-notes`, and the persona source pulls `ad-account`, `ad-comments`, `customer-reviews`, `other-reviews`, `post-purchase-surveys`, `reddit`, `brand-reputation`, `brand-self-echo-detection` — prompts in `personas/`
- **Voice of customer:** `voc-corpus-profile`, `voc-outcome-phrase`, `voc-trigger-moment`, `voc-surprise-delight`, `voc-aspirational`, `voc-metaphor`, `voc-category-jargon`, `voc-anti-language`, then `voice-of-customer-assembly` — prompts in `voice-of-customer/`
- **Audits:** `monthly-organic-tiktok-audit`, `monthly-tiktok-mining` (`audits-monthly/`), `biweekly-iterations-report` (`audits-biweekly/`), `weekly-performance-snapshot` (`audits-weekly/`), the external cuts `monthly-creative-landscape`, `monthly-top-impressions-report` (`audits-monthly-external/`) and `90-day-creative-strategy-audit-external`, `90-day-diversity-audit-external`, `90-day-performance-audit-external`, `single-competitor-ad-analysis` (`audits-quarterly-external/`)
- **Synthesis:** `audits/[YYYY-Q]/gaps-opportunities-inspo.md` — prompt `market-synthesis/gaps-opportunities-inspo.md`
- **Ideas and briefs:** `brand-idea-bank`, `idea-evaluation`, `sprint-plan`, `brief-creation` — prompts in `ideas-and-briefs/` (the `/harvest-ideas` routine fills the bank; PETL briefs still go through Grace's `nsy-brief-builder` into Notion)

### Exempt — self-cadenced or always-on
- The idea bank is captured continuously; briefs are per-campaign artifacts, not refreshed.
