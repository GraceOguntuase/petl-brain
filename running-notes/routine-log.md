# Routine log

Newest first.

## 2026-11-10 — refresh-context (scheduled)

**Checked:** `refresh_by` frontmatter on all 9 dated docs against today, plus the trigger list in `refresh-schedule.md`.

**Due:** nothing overdue. Nothing due within two weeks (by 2026-11-24). Next up, both due 2026-11-26 (16 days out): `audits/2026-10/2026-10-monthly-performance-report.md` and `sub-context-docs/brand-profile-narrative.md`. Next week's run will catch them as due soon.

**Re-ran:** nothing.

**Trigger check:**
- gopetl.com homepage loaded this time (HTTP 200). No mention of Burgundy, Glacier or Silver, and no Black Friday offer. Offer line reads "Bundle & save up to 30%" and "Free FedEx Premium Shipping $99+", which matches `brand-lens.md` (verified 2026-10-27). No contradiction to flag. *(verified · gopetl.com homepage, 2026-11-10)*
- The Nov 4 PETL 2 Plus color launch still isn't visible on the homepage. Homepage only, not the PDP, so this is data-limited. If it went live, `website-and-product-audit.md` is due now.
- Slack and Notion tools weren't available in this session, so no team-side trigger check.

**Skipped and why:** nothing was due, so nothing to skip.

## 2026-11-04 — refresh-context (scheduled)

**Checked:** every built doc's `refresh_by` against today, plus the trigger list in `refresh-schedule.md`.

**Due:** nothing overdue. Nothing due within two weeks (by 2026-11-18). Next up: `audits/2026-10/2026-10-monthly-performance-report.md` and `sub-context-docs/brand-profile-narrative.md`, both due 2026-11-26.

**Re-ran:** nothing.

**Skipped and why:**
- Trigger check, PETL 2 Plus Burgundy, Glacier and Silver launch (scheduled 2026-11-04): could not confirm it went live. Slack search since 2026-10-28 found no mention, and gopetl.com returned HTTP 429. If it is live, `website-and-product-audit.md` is due now (needs data: a clean PDP read). Left for next run or Grace.
- No Black Friday offer seen yet, so no price or offer contradiction to flag.

**Fixed:** `refresh-schedule.md` listed `brand-profile-narrative.md` under "not built yet", but the doc exists (built 2026-10-27, refresh_by 2026-11-26). Moved its line into the built section to match its frontmatter. No doc content changed.

## 2026-10-27 — routine armed

Weekly refresh set up as a local scheduled task on Grace's Mac (`petl-weekly-refresh`, Tuesdays 07:00, Auto mode). Re-runs up to two overdue docs per run; never builds "not built yet" docs; read-only on every tool. No other routines armed.
