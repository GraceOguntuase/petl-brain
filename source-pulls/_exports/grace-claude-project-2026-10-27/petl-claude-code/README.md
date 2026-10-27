# PETL knowledge base for Claude Code

## Setup (5 minutes)
1. Make a folder on your computer, e.g. `~/NSY/PETL/`, and copy this whole folder's contents into it, keeping the structure:
   ```
   PETL/
   ├── CLAUDE.md          ← Claude Code loads this automatically every session
   ├── README.md
   ├── docs/              ← the 8 knowledge docs (CLAUDE.md tells Claude when to read each)
   └── context/           ← put your raw project files here
   ```
2. Copy your claude.ai project files into `context/` as you go through them. Keep the names readable (e.g. `bi-weekly-sync-6.md`, `survey-responses.csv`, `website-reviews.md`, `470-high-impact-hooks.md`). Markdown, txt, csv and pdf all work.
3. Open Claude Code in the `PETL/` folder. CLAUDE.md loads on its own; Claude pulls `docs/` and `context/` files when it needs them.
4. Make sure your Notion connector and the NSY skills (nsy-brief-builder, nsy-creative-strategy, etc.) are available in Claude Code, so briefs can still be pushed.

## Keeping it current
- **Pricing changes:** update the table at the top of `docs/01` and the price lines in CLAUDE.md. Move the old row into the pricing history.
- **New round:** add a section to `docs/06` and update "Where things stand" in CLAUDE.md.
- **New rule from you:** tell Claude "add this to CLAUDE.md" (always-on rules) or "add this to docs/04" (writing rules).
- **New performance data:** add it to the top of `docs/03`.
- Keep CLAUDE.md short. Detail belongs in `docs/`.

## What's in here
Built from every PETL chat in the claude.ai project (Month 1 → Round 6, Jan–Sept 2026), the project memory (which covers Rounds 6–8 through early Oct), the ad account export, and the Dojo playbook. Rounds 7–8 weren't worked in these chats, so their detail comes from memory and the Round 8 Concept Plan. Check Notion for anything after early October.
