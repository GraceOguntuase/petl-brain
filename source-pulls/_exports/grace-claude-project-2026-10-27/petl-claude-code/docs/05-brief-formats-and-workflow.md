# 05 — Brief Formats & Workflow

## The workflow, every time

1. **Settle the concept with Grace.** Format (creator UGC / editor-only AI VO + B-roll / static), avatar, creator demographic, reference ad. **Ask whether it's a creator brief or editor-only; don't assume.**
2. **Write the script or static copy in chat.** Iterate until she explicitly OKs it. Show the *whole* script before pushing ("give me the rest of the script first, and then we can push it").
3. **Push with the `nsy-brief-builder` skill** into the Official NSY Brief Template. Two-layer structure, exactly as below. Never improvise a layout.
4. **Add the Time Log row** on the concept page: Action "Brief Done" · Person = Grace · Notes = "Brief completed, ready for creator to film. ASSIGN TO: [exact creator demographic, e.g. female 65+, real PETL owner; or real husband and wife couple]".
5. Report back briefly with the concept and brief links.

Strategist-supplied fields: **Caption Direction, Footage To Use and Music come from Grace** (often via the reference video). If she hasn't given them, mark them STRATEGIST TO CONFIRM rather than inventing them.

---

## Notion map

| Thing | ID / link |
|---|---|
| Master Creative Database (data source) | `collection://1d5df9f7-00e5-81a2-9e34-000be92d1412` |
| PETL brand page (Brand relation) | https://app.notion.com/p/2e6df9f700e580298955d961b8fcfa38 |
| Video Concept template (concept page; gives Strategy section, inline "Concept Brief Templates" DB, Time Log) | `1d5df9f7-00e5-8153-9e78-f3f7d6dfdf3b` |
| Static Concept template | `208df9f7-00e5-805c-9c8c-ef7a32525a32` (some rounds applied the video concept template to statics too; check what recent statics used) |
| Official NSY Brief Template (brief page) | `31ddf9f7-00e5-8020-841a-f3b4dc0f670d` |
| Ideas Library (shared across clients; filter Brand = PETL) | `collection://1d5df9f7-00e5-81f9-b9ce-000b6e13094e` |
| Team Projects DB (PETL deliverables; often stale) | `collection://1d5df9f7-00e5-812a-86f4-000b4eaef08d` |
| Meeting Notes DB | `2e6df9f7-00e5-8064-ad49-000b2a89cf19` |
| PETL Context Library | `2e6df9f7-00e5-809a-80c7-e80f8f16b93c` (Brand DNA for image gen, static prompts) |
| Grace's Notion user | `25ed872b-594c-81f7-aa2f-0002671f4375` |

### Concept page properties
- **Name:** "PETL## - Title"
- **Concept No.**
- **Batch:** Round 8 numbering continues from the Master DB; check the latest batch label on recent concepts
- **Concept Type:** Video Concept / Static Concept
- **Type:** Net New / Iteration
- **Product:** "Magsafe" ("PETL" fails)
- **Status:** In progress · **Status Type:** Strategy
- **Creator Needed?:** `__YES__` / `__NO__`
- **Priority**
- **Brand:** relation to the PETL brand page
- **Description:** one sentence, general to the concept, not to Hook 1. Keep it word-identical to the three Concept cells in the brief.
- **Hypothesis**
- **ICP - Target Avatar:** e.g. "Female Apple Ecosystem Owners 65+"
- **Brief Link:** plain URL

### Two-layer build
1. Create the concept page in the Master DB with the template. **Templates apply asynchronously: wait ~12–15s, then fetch** to get the inline "Concept Brief Templates" DB.
2. Create the brief page *inside* that inline DB from the Official NSY Brief Template. Its title property is **"Title"**, not "Name". Wait, then fetch again to get its inline "The Brief" (script) and "Shot List" DB IDs. These are unique per brief.
3. Fill everything, then set the concept's Brief Link.
- **Check the concept number** by querying the Master DB with the PETL brand filter before creating. Numbers have collided before (two PETL63s; PETL76/77).
- Statics are two-layer too ("remember to create a page for the brief").

### Brief page contents (video)
- **🚨 For the Creator ONLY (green toggle):**
  - Loom, "How to Read" callout, training callout
  - Table: Brand Name · Website · Product Link (https://gopetl.com/products/petl-magsafe-battery-pack-black) · Google Drive (creator raw footage upload: https://drive.google.com/drive/folders/127YX8UUS5iWudKTdf8OctTrNO5tjvvYy) · Concept · Target Audience · Reference
  - Shooting Instructions with a "✅ Location" line
  - Other Creator Notes
  - **All content must be nested inside the toggle**, or it renders outside it.
- **🚨 For the Editor ONLY (yellow toggle):**
  - Table: Concept · Reference · Caption Direction · Footage To Use · Music · Target Audience
  - Other Editor Notes (strategy, compliance, why-notes live here)
- **The Brief** (inline DB), with columns **Module | Script (What Creator Needs to Say) | Visual Guidance (What Creator Needs to Do) | Editor Notes (Creator Ignore This Column)**
  - Module names: zero-padded "01 - Hook", "02 - Agitate 1", "03 - Agitate 2"... "NN - CTA", then a blank separator row "NN -", then "Hook 2", "Hook 3", "Hook 4" as standalone takes.
  - Hooks are separate variations that each run into the same body. They're never stitched together.
  - **Overlays go in the Editor Notes column**, beside Visual Guidance. Editors ignore Visual Guidance. ("No, add it to the editor notes. It's beside the visual guidance in the actual script, like hello.")
  - Editor-only briefs: Visual Guidance is left empty and everything goes in Editor Notes.
  - Use plain URLs in table cells, never markdown links. Split long body sections into sub-rows.
- **Shot List** (inline DB): Shot | Visual (What You Do). Shots are numbered "Shot 01 - ...".

### Standard shooting instructions (creator)
- The read should NOT sound like an ad.
- The first 1–3 seconds are crucial.
- Film vertically, at least 1080×1920. Lapel or headphone mic.
- Submit RAW, with no text overlay or filters.
- No branded or graphic clothing.
- Encourage extra shots: "Please feel free to film any extra shots you can think of. Get creative."

### Standard compliance block (paste into every brief's Other Editor Notes)
- MagSafe Compatible only. Never Apple-approved / certified / Made for Apple. No Apple logos or marks on screen.
- Do not claim Qi2 certification.
- "Sold out 7 times" is brand-level only.
- Battery = up to 10 extra hours talk time (base) / up to 15 (Plus). No +17.
- Free shipping only at $129+ cart (3+ base, 2+ Plus). Never "free shipping on 2+".
- No $49, no PETL15, no "half the price".
- Blur competitor logos.
- Always "PETL 2 Plus". Space Black on Plus only.

---

## Shot lists

- **Shot list = extra B-roll only.** Never repeat footage the creator already films for the hooks or body. Get creative with new B-roll the library doesn't have yet.
- **Creators film lifestyle and situational, creator-in-frame shots.** No product macros, demos, rotations or unboxings; the library has plenty ("we have a ton of those"). Grace also thinks the product unboxing footage "isn't that good".
- **The exception: new product.** When creators receive something new (golds, Plus), load the list with that B-roll. "We really are lacking a lot of PETL 2 Plus B-roll." The original-vs-Plus size comparison is the money shot.
- Ask every Round 8+ creator for **gifting B-roll with family members** (mom → husband; younger creators → parents/grandparents; older men → family).
- Also ask for 2–3 shots of the creator using PETL, for the library.
- Typical counts:
  - 5–8 for a narrow concept
  - 15–20 for a new creator or a broad concept
  - none for editor-only (add a red callout explaining why)
  - When one creator films two briefs, put the shot list on the first brief only.
- **Keep product needs minimal.** Product goes out in bulk to ~15 creators per round. Never brief anything needing multiple units (e.g. a 5-PETL stack).
- No airport shots unless the creator is confirmed flying (it limits who can film).
- Matched before/after pairs (same location, angle, light) get called out in the shot list, creator notes and editor notes.
- Keep niche references (golf) minimal.

## Footage sources (for "Footage To Use")
- **Client brand assets / product library:** https://drive.google.com/drive/folders/1YbFkLZRUUuqjRwLlFwaocAmPIWtxy1RW
- **NSY B-roll library:** https://nsydigital.vercel.app/guide
- **Client raw footage. Include for ANY video featuring Sahara/Blush Gold or PETL 2 Plus** (Claire unboxing, male ASMR):
  - https://drive.google.com/open?id=1qMciL7GI34NAorPYSHG7KCWBZp198BUc
  - https://drive.google.com/open?id=14hF99x97utIy9001m9HiCJK2QqBH0G-L
  - https://drive.google.com/open?id=1T9aqikVeMUoRQnrUN-9vGLntNWYdgLIG
  - Re-paste these rather than copying from old briefs (one copy had mismatched IDs).
- Split Footage To Use into two buckets: **"Pull from the NSY B-roll library"** vs **"Source from the internet"** (e.g. Apple pack footage from MKBHD / Unbox Therapy, competitor product shots).
- B-Roll Creator Playbook: https://www.notion.so/B-Roll-Creator-Playbook-11d2c6af419f809c9316cd08a3c6a6f4

## Reference ads (AdNova)
- Account path: `https://app.adnova.ai/app/analytics/01KEH98B4EPA7SCDEHVDQGE1TK/account/01KEH98X0EK9NESGXXHVH5KJNY/creative/<id>`
- PETL65 Grandparents: creative `06772b34ffdc83e48c0898ee03da9c30`
- PETL48 / PETL25 Jared: `587f19f667755d6a612ed4bf4c93cd0e`
- Ranking reference used for PETL63/65/77: `b0db4a9e0709cce93f0f8c3dafd83290`
- Female Plus/gold unboxing: `a90abebbe58719a404e0766b06d83a93`
- Claire All Charger: `6f2f4e87c470ca15b70ff2bb010f9070`
- AdNova links are login-walled, so Claude can't watch them. Ask Grace for a beat breakdown, or have her paste a Gemini analysis.
- Static references: Grace describes the reference in the static brief and adds the image herself.

---

## Static brief template — "Static Concept - Existing Asset"

```
Reference: [what it is + what to take from it. Tell the designer: use it for layout/structure
            only; never copy its style, fonts, colors or look. Stay on PETL brand: PETL fonts,
            clean, premium, tech.]
Assets:    [Drive link + which product shots / colourways; what the designer must source or create]
Instruction: [ratio(s), layout, hierarchy, rules; keep it short; "read it once and get it"]
Copy (Variation A): headline / sub / callouts / offer / CTA, in full
Variations: table, B / C / D rows with "Select" + "Change" (only what changes)
Compliance
```

- **Four variations. Every one must look visually different** (a different scene, setup or subject, e.g. a person holding PETL up, a man charging his phone in a car) **and** carry different copy. Not just a colour or word swap. This is Meta's Andromeda update; Charley needs the visual variety for delivery.
- Ratios: 4:5 default. Long-copy and BOFU urgency statics need both 9:16 and 4:5 (4:5 = text on the right, product large on the left).
- Colourways:
  - **Universal by default:** a hero plus a six-colour lineup strip, since the range keeps growing
  - Solo colour matched to background where deliberate
  - Black/Natural for masculine
  - Sky blue/Lavender for female acquisition
  - All colours for BOFU family bundles
- Proven background: sky blue #C7E0F4. Use gradients, frosted white pills and an Apple-keynote look, not DTC clutter. No white "Amazon" backgrounds for premium statics.
- Environmental backdrops work when subtle: flower fields for Blush Gold, Sahara dunes for Sahara Gold ("cute but demure"). Backgrounds can be AI or stock; **product renders must be real assets** (AI gets the logo, port and LEDs wrong).
- Legibility for 55+: high contrast, minimum readable label size, comment bubbles ≤12 words.
- Graphic designer: Chona Tapeles.
- AI statics (Nano Banana / Higgsfield) were tried in Round 3 and fell below the client's design standard. Statics go to the designer.

---

## Batch shape (Round 8, Oct 2026 into Black Friday)
- **20 videos + 15 statics per round** (Rakesh upgraded the account). This supersedes 10 UGC + 4 misc + 10 statics.
- About 5 UGC creators × 2 briefs each, plus misc videos (AI VO + B-roll, tech edits, yapper, comment-reply).
- Statics: usually BOFU offer-led, sometimes TOF. About 2 corporate angles per round.
- Prioritise proven angles and formats first (Top 3 Grandparents, Top 5 Ranked, competitor comparisons). Low-hanging fruit before organic-style tests like "what's in my bag".
- No Christmas creative until the client says so. Black Friday angles were due at the October client call.

## Tooling gotchas (from Notion work so far)
- Notion writes can silently fail with "No approval received" when permissions haven't cleared. Reconnect the connector; don't loop retries.
- `replace_content` on a concept page **wipes the inline DBs** (Concept Brief, Time Log). Don't use it on concept pages. Use targeted updates with an exact `old_str` (re-fetch first; tabs and auto-linked URLs change after saving).
- The API can't hard-delete DB rows. Rename leftovers "[DELETE] ..." for Grace to bulk-delete.
- Template hydration is async (wait ~12–15s). Query rate limits: wait ~40s.
- Toggles hide edits when collapsed. When auditing, check every column, the toggles, and the concept-page Description/Hypothesis.
- Duplicated brief pages keep old IDs (PETL56 → 58 → 68). Confirm which page Grace is looking at.
- "$" can get escaped in titles.
- Ideas Library views can't be edited by API. Create pages one at a time to keep order.
- Image uploads to Notion: references attach manually (or auto-attach on some uploads). Don't promise.
- If the Notion connector isn't connected in Claude Code, draft the brief in markdown in the same structure and tell Grace.

## Related NSY skills
`nsy-brief-builder` (push briefs) · `nsy-creative-strategy` (scripts/hooks; reference files: script-examples, structures-and-hooks, principles-and-prohibitions, persona-architecture, static-ad-strategy with 7 headline formulas) · `nsy-creative-research` · `nsy-static-ad-generator` · `nsy-call-debrief` (sync transcripts → action bullets) · `ai-video-scene-generator` · `de-ai-ify`.
