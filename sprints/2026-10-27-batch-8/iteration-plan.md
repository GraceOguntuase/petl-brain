---
doc: iteration-plan
brand: PETL
batch: 8
generated_on: 2026-10-27
version: 2 (rebuilt after grounding review)
status: checkpoint, awaiting Grace (picks and split)
sources: audits/2026-10/2026-10-27-winners-for-iteration.md and 2026-10-27-winners-60d-and-scripts.md (Meta pulls 2026-10-27, verified); production/creator-roster.md; sprints/2026-10-27-batch-8/sprint-plan.md; personas/; brand-lens.md
method: selecting-ads-to-iterate-on.md, iterations.md, killer-performance-ads.md, ad-account-analysis.md (frequency 1.2 or lower, hold 12%+), andromeda-v2.md (entity IDs), ad-formats/, processes/format-swap, frankenstein-stitch, creator-reshoot-same-script, static-headline-iteration
---

# Batch 8 iteration plan (checkpoint, v2)

`strategy/` and `idea-bank/` are empty for PETL, so no committed roadmap frames these picks. The account data is the guide.

## Account read

PETL spent $559K in Aug 28 to Sep 26 and $654K in Sep 27 to Oct 26, at 1.64 ROAS for the latest window (verified). Spend is concentrated: PETL60's apology video took 21.0% of the last 30 days and the Sean_911/PETL65 family about 19%. Two new things showed up: CLD_1001's three-band static scaled from $267 to $53.2K in one week, and an old three-device UGC video (Clair) came back strong. Most of the remaining top 10 are "LAST CHANCE / UP TO 30% OFF" bundle statics. Hook rate can't be read through this connection; hold is read as thruplays per impression.

## Selected ads, ranked

1. **CLD_1001 V2, three-band static (`Product Collection`, in-house).** A high-riser: $127, then $267, then $53.2K at 1.78 last week (8.2% of 30-day spend). Facebook feed takes 66% of spend at a $43 CPM and 1.90 ROAS, the cheapest reach in the account. On-image text: "iPhone." / "Watch." / "Airpods." / "Everything you rely on, powered by one pocket-sized charger." / "UP TO 30% OFF." Two cautions. Its 7-day frequency of 1.54 is already above the 1.2 floor, so it's eating its audience fast. And it carries a discount badge. PETL's bundle ladder has been live through 2026, but it moved several times, so treating it as standing pricing is an inference. That's why the badge-out test comes first. Grace named this ad.
2. **PETL60 V1, the apology (`B-roll mashup + Voiceover`, NSY, 68s).** A slow-burner and the top spender. Weekly spend climbed $7.6K, $21.6K, $23.6K, $34.0K, $39.6K, held at $35.2K, then fell to $21.5K last week, while ROAS posted its best full week at 1.89. Frequency never went above 1.19, and hold is 17.7% (above the 12% floor). Last week's spend drop reads as the breakdown effect, Meta moving budget to CLD_1001 at a tenth of the CPM, not fatigue (inferred). Its CPM ($413) is the account's most expensive. Main hook: "To the 1,000 people who tried to buy a Black PETL last month - we're sorry." **Watch it before briefing.** The live cut's thumbnails show people on camera, so it may not be pure B-roll (Frame.io https://f.io/icasSWkj). Its spoken prices were set on Jul 16, so check them too.
3. **Clair "All charger" (`UGC Single` / `Demo`, 39.7s, in-house, first live Dec 1 2025).** A past winner coming back: $67.8K lifetime at 2.11 ROAS and a $29.32 CPA (when that spend landed isn't in the pull, so "evergreen" is inferred). **Promo caveat:** its copy runs a 15%-off "today only" code, the spike-then-die case the method warns about, so the lifetime number may be promo-driven. The Oct 12 copy in THREE DEVICES is rising, at $144, $1,340 and $1,718 a week, with a $39.95 CPA last week, the lowest of any ad pulled. It's small spend so far, about 1.1% of the account's roughly $158K a week. **Urgent fix first:** its copy still says "Use PETL15 = 15% OFF," and PETL15 is dead. Relaunch it with the code swapped out, and treat that relaunch as the first read on whether Clair works without the promo. **Nobody has watched it or pulled its script yet,** so the Clair iterations below wait until Grace watches it. If the spoken lines carry the code or "today only," the script has to change before any reshoot. And with a 3.71% lifetime CTR, Clair herself may be the working element, in which case a creator swap shouldn't be the first test.
4. **PETL61 V4, watch slot only (`UGC Single`, Jared, 78s).** Not a slow-burner. Its spend went $11.1K, $30.2K, $0 for four weeks, then $14.1K and $9.3K, and its share fell from 7.4% to 3.6%. Rising ROAS on falling spend is what the method warns about. Two things are still worth carrying forward. Its winning hook beat three others in the same test: V4's "I regret buying my petl because they just released a 5,000mah version..." took $85.5K at 1.89, while V2 took $2.4K. And its hold is 7.7%, below the 12% floor, which points to a short cut.

## Not selected

- **Sean_911 H4 / PETL65 family:** $126.5K at 1.58 and tiring. It needs a bigger swing, a format change, which is the ranked static below.
- **CLD922 V2** ($43.5K, steady $7–12K a week, 6.7% share) **and V1:** both images say "LAST CHANCE / UP TO 30% OFF / Hurry before prices go up!", a pure promo creative the method says not to iterate on.
- **AR717 V1/V3:** bundle-discount statics. V1 shows early fatigue and V3 is paused.
- **PETL84 V2/V3:** fatigued (2.04 to 1.56) or paused.
- **PETL125:** $31.6K at 1.32 over 30 days, and $13.5K at 1.45 last week as a top-3 spender, but it gets clicks without sales, and Charley is already moving budget off it.

## The pattern to protect

PETL's two biggest proven hooks both open on an apparent negative that flips into desire: "we're sorry" (PETL60) and "I regret buying my petl" (PETL61 V4, which beat three other hooks). In `killer-performance-ads.md` terms, both run on "to be superior, winning, keeping up with others": PETL60 says so many people wanted one that it sold out, and PETL61 says there's a better version now. CLD_1001 runs on a different one, "comfortable living conditions" (one charger for everything, shown plainly), which fits the persona's ease and fewer-cords language. Iterations on the two videos keep the apparent-negative open; iterations on CLD_1001 keep the plain three-device show (golden rule 10, show the product a lot). Each changes something else. (Inferred, from the hook lines in the 60-day audit.)

## Iterations (one variable each)

Andromeda groups near-identical images under one entity ID, and CLD_1001 is already above the frequency floor. So only visually distinct versions of it are kept: no same-layout headline or color swaps, per the monthly report's call for statics "spread across visibly different people and settings."

### Video iterations (9)
1. **CLD_1001 to `Motion Videos` (format swap).** The three bands animate, and each band becomes a 2–3 second clip of real hands with its own device: the PETL snapping onto an iPhone in a case, then an Apple Watch set on top, then AirPods set on top. One device per beat. It keeps the same on-image lines and a click-only sound, 4:5, about 12 seconds. **Check first:** INTL Sean_1001_2 V1/V2 ("Three-device ecosystem | TRIDEVFAM," about 31s, launched Oct 8 alongside CLD_1001) may already be this. They've spent only $190, which isn't a real test. If they are, re-launch them in their own ad set instead of remaking them.
2. **PETL60 whisper VO.** Same script and footage, with the female voiceover re-read as a whisper (stated · Grace, 2026-10-27, from the Dojo call). This applies only to the VO sections if the cut turns out to have people talking on camera.
3. **PETL60 event swap for the Nov 4 colors.** Same apology structure, new true event: "To everyone who waited for Burgundy… we're sorry." Only if Burgundy really sold out or had a waitlist. (Replaces net-new PETL145.)
4. **PETL60 Spanish VO.** Same footage (VO sections only, if the cut has people talking on camera), a Spanish voiceover reviewed by Nativ's wife, run to Spanish-speaking audiences (Rakesh, Oct 9: "take our number one ad ever"). Cheaper than a new creator. PETL141's Spanish-creator slot stays net new if Grace wants both.
5. **Clair, same script, new creator: a woman 60+ (after Grace watches it, and after the code-swapped relaunch reads).** It's normally the highest-confidence iteration: a proven script with a face from the core buyer. First pick Kelsea Lopez's mother (confirm her age), backup a sourced 60+ woman.
6. **Clair, same script, new creator: a man 54+ (same conditions).** Men 65+ are the cheapest buyers. First pick Rod Kynaston, backup Bo Richardson.
7. **Clair, hook headline banner.** Add CLD_1001's own line, "Everything you rely on, powered by one pocket-sized charger.", as a bold banner over the first 3 seconds. Very low effort.
8. **PETL61 short cut (`edit pacing`).** 78s down to about 30s: Hook 4, the 5,000mAh reveal, and the offer. Hold is 7.7% against a 12% floor, so most viewers never reach the close.
9. **PETL61 Hook 4 script, new creator.** The R8 brief already asked for "a new face (not Jared)." First pick Matt Ulman (a fresh older face), backup Bo Richardson.

### Static iterations (7)
1. **CLD_1001 badge out.** Same image, no "UP TO 30% OFF." This isolates whether the bands or the badge carry it, and it's the evergreen version for after Black Friday.
2. **CLD_1001 message, Space Black for men, new composition.** Same three-device message and on-image lines, rebuilt as a lifestyle scene, not bands: a man's hand on a dark desk with an iPhone, an Apple Watch and AirPods, each with a Space Black PETL. The same band layout in dark colors would share CLD_1001's entity ID, so the composition has to change. Men are 36.6% of CLD_1001's spend at 1.70, and Space Black buyers run 91% men (stated, PETL Analytics). This merges with net-new PETL162.
3. **CLD_1001 to `Carousel` (format swap).** One card per device (iPhone, Watch, AirPods), then a card for the bundle. A different format, so a different entity.
4. **PETL61 Hook 4 to `Headline Only` static (format swap).** The proven regret hook as the headline over a PETL 2 Plus product shot, always with the 5,000mAh turn in the same headline, so it reads as an upgrade and never knocks the original PETL (brand-lens.md). It's the account's one tested-against-three-others winning line.
5. **Clair to `Native` static (format swap, after Grace watches it).** A frame from the Clair video with one line it actually says, styled as an organic post. No code, no "today only."
6. **PETL65 / Sean_911 to a ranked static (format swap, the bigger swing the tiring family needs).** "Top 3 chargers for grandparents" as a ranked list image (the PETL81 style). Replaces net-new PETL160.
7. **PETL60 apology static for the Nov 4 colors.** The static version of video iteration 3, same condition. This is PETL157, reclassified as an iteration.

## Proposed batch split

Counting honestly: **16 iterations, 9 video and 7 static, plus 19 net new, 11 video and 8 static. That's 46%.** (Static 2 absorbs PETL162, so the net-new statics free one slot for a ninth idea.) That's the strong set the account supports today. Three iterable winners and one watch slot can't carry 28 iterations (80%) without repeating themselves, and CLD_1001 is already saturating. The clean way to go higher is more creator reshoots of the Clair and PETL60 scripts. Each new face counts as a real, separate test, and that adds about 4 to 6 more iterations if Grace wants to lean harder.

Net new keeps: PETL128–131, 132, 133, 135, 138, 140, 142, and one of PETL143 (call-in) or PETL144 (store grading) for video. For statics: PETL148 (5-pack, Urgent), 149, 151 (BF price, needs offer), 153 (BF letter), 154, 155, 158, plus one open slot.

## Creator picks, first and backup

- PETL128 "Over 65" demo: Kelsea Lopez filming her mother if she's 60+, otherwise a sourced 60+ woman.
- PETL129 "Grandma always has a charger": Kelsea Lopez with her mother and kids; backup Rod Kynaston's family.
- PETL130 "Is PETL legit?": Kelsea's mother (same age check); backup Jenni Bowman (46).
- PETL131 Grandma's First Snap: Abraham Gardner with his grandparent; backup Kelsea's mother.
- PETL132 "This charger is so weird" / 3 Things: Matt Ulman; backup Rod Kynaston.
- PETL133 car unboxing: Rod Kynaston (has a car); backup Amy Griffin (has a car).
- PETL135 Christmas 5-pack haul: Jenni Bowman; backup Nicole Brown.
- PETL138 travel gear: Bo Richardson with his wife; backup Rodger Harris. Ask both about trips.
- PETL140 man-pays purse trend: Brian Bickerton with his girlfriend; backup Allison Nelson with her husband.
- PETL142 real customer: no pick. PETL has to source the buyer.
- Iteration reshoots: Clair 60+ woman (Kelsea's mother, or sourced), Clair man (Rod, backup Bo), PETL61 Hook 4 (Matt Ulman, backup Bo).
- Kelsea's household carries 4 first picks (PETL128, 129, 130 and the Clair 60+ reshoot) plus a backup on PETL131. That makes her mother the single biggest dependency, so confirm her age and willingness first, and source a second 60+ woman so it isn't all on one family. Rod has 2 first picks (PETL133 and the Clair man reshoot) and 2 backups.
- Free capacity left: Rodger Harris (backup only), Rachel Ramos, Hannah Kim, Alexis Robb, Nicole Brown (backup only), Anthony Lemoine. Matthew Smith is held pending the blacklist check.

## Brand Context Applied
- **What I used:** the Oct 27 Meta pulls (60-day weekly spend, frequency, hold, placement and age splits), the winning hook lines from the Notion briefs, the personas (55+, women 65+, men 65+ cheapest), the claim rules, and the creator roster.
- **What I avoided:** "at the same time" (the motion video is one device per beat), stale "sold out" and price claims (the PETL60 iterations are conditional and need a price check), the dead PETL15 code (flagged on Clair), and same-layout clones that would share an entity ID.
- **Why this fits:** CPMs roughly doubled since May. CLD_1001 and the Clair video are buying the cheapest results in the account, and PETL60 is still the biggest proven engine, so most iterations build on those three. Black Friday on Nov 27 favors the fast ones: badge-out, the Clair banner, the whisper VO, the motion cut.

This is based on everything I know about choosing which ads to iterate on.

## Review gates
- Grounding review: grounded on round 3 (bounced twice: missing doctrine loads and 60-day pull, PETL61 mislabeled slow-burner, a stitch and mashup that failed pre-checks, same-layout clones, then the Clair promo caveat, the Space Black entity issue, and two miscounts).
- Voice review: not run yet. No final copy written; it runs when the briefs are drafted.
