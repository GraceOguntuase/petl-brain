---
brand: petl
doc: winners-60d-and-scripts
generated_on: 2026-10-27
extends: audits/2026-10/2026-10-27-winners-for-iteration.md (7/14/30d pull, placement/demo split for CLD_1001, top-10 ranking). This doc does not repeat those numbers; it adds the 60-day weekly history, version history, share of account spend, creative/script detail and the Clair video.
window: 60 days, 2026-08-28 to 2026-10-26. Weeks run Mon-Sun so the last week (Oct 20-26) matches the 7d window in the prior doc. Aug 28-31 is a 4-day stub.
data_sources_read:
  - Meta Ads MCP, account 3803347073290974, pulled 2026-10-27, read only. Ad level by object ID, time_increment 7 (Sep 1-Oct 26) plus a stub (Aug 28-31); two 30-day windows (Aug 28-Sep 26, Sep 27-Oct 26) at ad and account level; account weekly; lifetime (maximum) for all PETL60/PETL61/CLD922/CLD_1001/Clair IDs; THREE DEVICES ad set ad list; creatives endpoint (17 creatives); video endpoint (12 videos).
  - Images and video thumbnails viewed directly from Meta CDN URLs, 2026-10-27 (CLD_1001 V1/V2, CLD922 V1/V2, thumbnails for PETL60 V1-V3, PETL61 V1-V4, Clair).
  - Notion (read only): "PETL60 - We're Sorry, Black Back In Stock (Video)" brief + its Brief table; "PETL61 - Meet PETL 2 Plus - Male Creator" brief + its Brief table; both Master Creative Database concept pages (hypothesis, ICP, status, edit dates).
labels: Verified = pulled from Meta or Notion today. Inferred = arithmetic or a read on pulled data. Stated = a doc or person says it; not checked against the asset. Data-limited = can't settle from what's available.
---

# PETL winners: 60-day weekly history, versions and scripts (2026-10-27)

## Short version

- **PETL60 V1 is steady-to-rising on spend for six weeks, flat on ROAS (1.6 to 1.9).** It moved IDs on Oct 9 (PRODUCT FOCUS copy stopped after Oct 12, TOP PERFORMERS copy took over). Combined weekly spend went $7.6K, $21.6K, $23.6K, $34.0K, $39.6K (Oct 6-12, both IDs), $35.2K, then $21.5K last week. Last week's drop is the CLD_1001 scale-up week. ROAS 1.89 last week is its best full week. It was 21% of account spend in the last 30 days (verified).
- **PETL61: only V4 ever spent.** V1/V2/V3 got $30, $207 and $4 lifetime in the PETL PLUS ad set before Meta starved them in the first days. V4 is Hook 4, "I regret buying my petl..." (split-screen), verified by thumbnail caption and brief. V4 had **zero spend Sep 8 to Oct 5**, then came back Oct 6. Since return: $14.1K at 1.79, then $9.3K at 2.18.
- **CLD922 V2 has been flat at $9K to $12K a week since launch** (Sep 22), ROAS 2.37 first week, sagged to 1.63 to 1.64 mid-Oct, back to 2.07 last week. **CLD922 V1** is starved ($0.7K to $3.3K a week) but its ROAS sits 1.97 to 2.57 after week one.
- **CLD_1001 V2 is new, not a 60-day story**: $127, $267, then $53.2K last week. **CLD_1001 V1** (a different design, see creatives) never got past $68 a week.
- **The Clair video is an old winner reused.** Same creative (1456415426034073, 39.7s video) ran as ad 120236845260040194 from Dec 1, 2025: **$67.8K lifetime at 2.11 ROAS, $29.32 CPA, 3.71% CTR**. A second copy (Apr 29) did $24.8K at 1.77. The THREE DEVICES copy (Oct 12) has $3.3K at 2.35, rising week to week ($144, $1,340, $1,718).

## Account context (verified)

| 30-day window | Account spend | Purchases | ROAS | CPM |
|---|---|---|---|---|
| Aug 28 - Sep 26 | $559,059 | 7,823 | 1.71 | $123.23 |
| Sep 27 - Oct 26 | $653,902 | 8,363 | 1.64 | $117.78 |

Account weekly spend: Sep 1-7 $126.6K (1.74), Sep 8-14 $131.6K (1.55), Sep 15-21 $128.2K (1.71), Sep 22-28 $138.9K (1.78), Sep 29-Oct 5 $146.3K (1.70), Oct 6-12 $155.7K (1.52), Oct 13-19 $154.3K (1.55), Oct 20-26 $158.3K (1.74).

## Share of account spend per 30-day window (verified spend, inferred share)

| Ad | Aug 28 - Sep 26 spend / share / ROAS | Sep 27 - Oct 26 spend / share / ROAS |
|---|---|---|
| PETL60 V1, PRODUCT FOCUS copy (120249723254010194) | $46,074 / 8.24% / 1.73 | $55,696 / 8.52% / 1.64 |
| PETL60 V1, TOP PERFORMERS copy (120250326901490194) | $0 | $81,544 / 12.47% / 1.72 |
| PETL60 V2 (120249761700890194) | $169 / 0.03% / 0.46 | $0 |
| PETL60 V3 (120249761704240194) | $1,904 / 0.34% / 1.24 | $0 |
| **PETL60 all IDs** | **$48,147 / 8.61%** | **$137,239 / 20.99%** |
| PETL61 V1 (120249382402570194) | $30 / 0.01% / no purchases | $0 |
| PETL61 V2 (120249382413100194) | $207 / 0.04% / 1.60 | $0 |
| PETL61 V3 (120249382419060194) | $4 / 0.00% | $0 |
| PETL61 V4 (120249382423130194) | $41,303 / 7.39% / 1.71 | $23,721 / 3.63% / 1.96 |
| CLD922 V1 (120250059233810194) | $1,613 / 0.29% / 1.54 | $7,122 / 1.09% / 2.19 |
| CLD922 V2 (120250059248960194) | $4,846 / 0.87% / 2.34 | $43,534 / 6.66% / 1.87 |
| CLD922 V3 (120250059258660194, paused) | $428 / 0.08% / 2.94 | $925 / 0.14% / 2.30 |
| CLD_1001 V1 (120250304393110194) | $0 | $183 / 0.03% / 2.55 |
| CLD_1001 V2 (120250304411110194) | $0 | $53,607 / 8.20% / 1.79 |
| Clair, THREE DEVICES copy (120250363639220194) | $0 | $3,201 / 0.49% / 2.39 |

## Weekly tables (verified; CPA and thruplays/impression inferred from pulled counts)

CTR = outbound (link) CTR, same field as the prior doc. Frequency is per week as Meta reports it. Blank weeks = $0 spend.

### PETL60 V1 (68.2s video, same creative 1849565459748043 on both IDs)

| Week | ID | Spend | Purch | ROAS | CPA | CPM | CTR | Freq | Thruplays/impr |
|---|---|---|---|---|---|---|---|---|---|
| Aug 28-31 | PF | $0 | | | | | | | |
| Sep 1-7 | PF | $234 | 10 | 4.42 | $23.42 | $142.90 | 2.56% | 1.18 | 8.0% |
| Sep 8-14 | PF | $7,571 | 115 | 1.82 | $65.83 | $262.43 | 3.49% | 1.17 | 12.4% |
| Sep 15-21 | PF | $21,599 | 313 | 1.79 | $69.01 | $413.16 | 4.57% | 1.10 | 20.1% |
| Sep 22-28 | PF | $23,583 | 321 | 1.63 | $73.47 | $464.97 | 5.63% | 1.04 | 22.6% |
| Sep 29-Oct 5 | PF | $33,997 | 433 | 1.58 | $78.52 | $303.16 | 4.40% | 1.19 | 18.3% |
| Oct 6-12 | PF | $14,784 | 181 | 1.70 | $81.68 | $367.69 | 3.83% | 1.11 | 16.6% |
| Oct 6-12 | TP | $24,862 | 322 | 1.73 | $77.21 | $351.95 | 3.67% | 1.12 | 16.9% |
| Oct 13-19 | TP | $35,221 | 420 | 1.62 | $83.86 | $461.60 | 4.47% | 1.11 | 19.4% |
| Oct 20-26 | TP | $21,460 | 284 | 1.89 | $75.56 | $413.23 | 4.06% | 1.07 | 17.7% |

**Trend (inferred):** spend ramped Sep 8 to Oct 12 (peak $39.6K combined), held at $35.2K, then fell 39% last week. ROAS has never been above 1.89 in a full week and never below 1.58. Thruplays/impression peaked at 22.6% (Sep 22-28) and has settled at 17-19%. CTR peaked at 5.63% the same week and is now 4.06%. CPA crept up from $66 to $84 as spend grew, then eased to $76. That reads like a concept that scales flat, not one that is decaying: frequency never passed 1.19. CPM is the account's highest every week ($263 to $465).

PETL60 V2 and V3 (PRODUCT FOCUS, created Sep 4) only spent Sep 1-14: V2 $169 at 0.46, V3 $1,904 at 1.24, CTR 2.00%, thruplays/impr 6.7%. Meta picked V1 in the first week.

### PETL61 V4 (77.7s video, creative 1029112713058520)

| Week | Spend | Purch | ROAS | CPA | CPM | CTR | Freq | Thruplays/impr |
|---|---|---|---|---|---|---|---|---|
| Aug 28-31 | $11,136 | 190 | 2.08 | $58.61 | $149.23 | 2.38% | 1.26 | 9.2% |
| Sep 1-7 | $30,166 | 372 | 1.58 | $81.09 | $163.77 | 2.26% | 1.25 | 10.0% |
| Sep 8 - Oct 5 | $0 (four weeks) | | | | | | | |
| Oct 6-12 | $350 | 7 | 2.91 | $50.07 | $126.76 | 2.57% | 1.13 | 10.8% |
| Oct 13-19 | $14,113 | 202 | 1.79 | $69.87 | $154.48 | 2.38% | 1.62 | 8.3% |
| Oct 20-26 | $9,257 | 150 | 2.18 | $61.72 | $137.99 | 2.24% | 1.46 | 7.7% |

**Trend (inferred):** two separate runs. Run 1 (Aug 14 to ~Sep 7): lifetime $85,520 minus the $65,024 in this 60-day window means about $20.5K went out Aug 14-27 (inferred). Aug 28-31 was strong (2.08), then Sep 1-7 scaled to $30K and ROAS fell to 1.58. Then nothing for four weeks. **Why it stopped is data-limited**: the pull shows $0, not who paused it or whether the ad set was off (activity log not pulled). Run 2 (Oct 6 on): smaller budget, better ROAS (1.79 then 2.18), but thruplays/impr is sliding (10.8% to 7.7%) and frequency is higher than run 1. Spend fell 34% last week while ROAS rose.

A fifth copy, "NSY | PETL61 | V4 | MEET PETL PLUS" in NSY | AWARENESS | CBO (120249799628500194, created Sep 7, video 1738260267320334, same length and thumbnail as V4), spent $1.64 lifetime. Ignore it.

### PETL61 V1, V2, V3 (verified)

| Version | Ad ID | Lifetime spend | 60-day spend | Video / length | Hook (thumbnail caption + brief) |
|---|---|---|---|---|---|
| V1 | 120249382402570194 | $33.58, no purchases | $30 (Aug 31-Sep 14) | 1047571364905044, 78.7s | Jared indoors to camera, no caption on thumbnail. Inferred to be the primary hook (row 01) |
| V2 | 120249382413100194 | $2,355 at 1.62 | $207, $203 of it Aug 28-31 (3 purchases) | 1592127768992596, 77.2s | Jared close-up indoors, no caption. Inferred to be Hook 2 |
| V3 | 120249382419060194 | $34.71 | $4 | 1037381365776306, 76.6s | Jared outdoors, caption "If you've ever wished" = Hook 3 (verified match) |
| V4 | 120249382423130194 | $85,520 at 1.89 | $65,024 | 2203285273646958, 77.7s | Split-screen, PETL box on top, Jared below, caption "I regret buying my PETL" = Hook 4 (verified match) |

All four launched Aug 14 in PETL PLUS, same copy, same body; only the hook differs (verified for V3/V4 by caption, inferred for V1/V2 from the brief's four-hook structure). V2 is the only other version that got a real test ($2.4K lifetime, mostly before Aug 28, at 1.62).

### CLD922 V1 / V2 / V3 (bundle statics, 1080x1080)

| Week | V1 spend / ROAS / CPA / CTR / freq | V2 spend / ROAS / CPA / CTR / freq / CPM | V3 spend / ROAS |
|---|---|---|---|
| Sep 22-28 | $1,613 / 1.54 / $80.64 / 2.03% / 1.53 | $7,336 / 2.37 / $54.34 / 2.55% / 2.05 / $88.59 | $626 / 3.40 |
| Sep 29-Oct 5 | $654 / 2.94 / $50.31 / 1.73% / 1.48 | $10,094 / 2.07 / $63.49 / 2.36% / 1.95 / $93.39 | $522 / 1.96 |
| Oct 6-12 | $3,322 / 1.97 / $57.28 / 1.95% / 1.71 | $12,379 / 1.63 / $80.39 / 2.45% / 1.83 / $105.46 | $206 / 1.18 |
| Oct 13-19 | $1,929 / 2.08 / $62.22 / 2.15% / 1.54 | $9,341 / 1.64 / $84.92 / 2.83% / 1.65 / $110.81 | $0 (paused) |
| Oct 20-26 | $1,217 / 2.57 / $48.67 / 2.12% / 1.49 | $9,229 / 2.07 / $59.93 / 2.71% / 1.78 / $111.17 | $0 |

**Trend (inferred):** V2 is steady on spend ($7.3K to $12.4K, now $9.2K) with a mid-October dip in ROAS that recovered. CPM has risen every week ($89 to $111), which is the one creeping cost. V1 is falling on spend from a $3.3K peak and rising on ROAS; it has never had a $4K week. V3 was cut Oct 12 after one bad week on $206.

### CLD_1001 V1 / V2 (THREE DEVICES)

| Week | V1 spend / purch / ROAS / CTR / CPM | V2 spend / purch / ROAS / CTR / CPM / freq |
|---|---|---|
| Oct 6-12 | $61 / 1 / 1.63 / 0.89% / $54.15 | $127 / 2 / 1.08 / 0.83% / $45.58 / 1.54 |
| Oct 13-19 | $54 / 3 / 6.76 / 0.47% / $42.23 | $267 / 12 / 5.08 / 1.03% / $43.19 / 2.05 |
| Oct 20-26 | $68 / 0 / none / 0.66% / $34.51 | $53,213 / 725 / 1.78 / 1.91% / $47.28 / 1.54 |

V1 has a link CTR under 0.9% every week; V2 doubled its CTR once Meta found a buying audience. Daily detail for V2 is in the prior doc.

### "Ad 1 | Clair All charger | 1st Dec | ASC" (all three IDs)

| ID | Campaign / ad set | Created | Status | Spend | Purch | Revenue | ROAS | CPA | CPM | CTR | Freq | Thruplays/impr | Avg watch |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 120236845260040194 | ASC - Scaling CBO, Catalogue Dec 1, $1500 / ASC Broad, Auto Placements | 2025-12-01 | Campaign paused | $67,839 | 2,314 | $143,252 | 2.11 | $29.32 | $57.93 | 3.71% | 1.88 | 11.9% | 7s |
| 120243716191210194 | April 29 VO-IA-ASC duplicate / ASC Broad | 2026-04-29 | Paused | $24,849 | 620 | $44,098 | 1.77 | $40.08 | $89.41 | 3.25% | 1.37 | 10.7% | 6s |
| 120250363639220194 | April 29 VO-IA-ASC duplicate / THREE DEVICES | 2026-10-12 | Active | $3,260 | 70 | $7,651 | 2.35 | $46.58 | $109.61 | 2.32% | 1.52 | 7.0% | 5s |

All lifetime, verified. The Dec and Oct copies use the **same creative** (1456415426034073, video 849433424222582, 39.7s, created 2026-03-20 per creative name). The Apr copy uses a re-upload of the same video (1333783535330593, also 39.7s, same thumbnail). None of the three spent Aug 28 to Oct 11.

THREE DEVICES copy weekly: Oct 6-12 $144 / 4 purch / 3.87 / CTR 1.75% / CPM $132.60 / 4.4% thruplays; Oct 13-19 $1,340 / 23 / 1.88 / 2.61% / $134.12 / 7.0%; Oct 20-26 $1,718 / 43 / 2.66 / 2.23% / $95.71 / 7.3%. **Rising on both spend and ROAS**, from a small base. Its CPA last week ($39.95) was the lowest of any ad in this doc.

**Creative (verified):** vertical video. Thumbnail is a woman in a kitchen holding a PETL disc up to camera, caption "MagSafe-compatible". Copy is unique in the account:
- Primary text: "Replace 3 chargers with 1 ✨ PETL's World's 1st circular MagSafe design charges iPhone + AirPods + Apple Watch in one sleek snap. Premium build. Pocket small. Apply PETL15 for 15% OFF—today only. 🛒 3 devices. 1 PETL."
- Headline: "🚨 3 devices. 1 PETL. Use PETL15 = 15% OFF"
- Description: "🔥Limited drop. Shop now. Use PETL15 = 15% OFF"
- CTA Shop Now. Meta video title is the headline text.

Whether PETL15 still works on site today is data-limited (not checked). The "Claire" name across older ads suggests this is the client's own creator (inferred from the "Clair/Claire" naming family, 2025 onward).

### Other video versions of the three-device idea (verified names, inferred mapping)

In the THREE DEVICES ad set, the only videos built from the Oct 8 "Three-device ecosystem" static batch are **INTL | Sean_1001_2 | V1 | Three-device ecosystem | TRIDEVFAM** (120250304344160194, active, video 1754540739085393, 31.6s, $164 lifetime at 2.28) and **V2** (120250304380360194, active, video 1641196044253523, 31.0s, $26, no purchases). They share the CLD_1001 launch date and ecosystem name, so they're the video counterparts (inferred); I didn't watch them. Other videos in THREE DEVICES are different concepts: INTL | SEAN915 V1-V5 (Sep 17, V4 $28.3K at 1.48, all paused) and NSY | PETL76 V1-V5 DECLUTTER TRANSFORMATION (Oct 2, V5 $7.9K at 1.35, all paused). The Feb "USP | Call Outs | Three-Devices A-D" ads are statics.

## Creatives

### CLD_1001 on-image text (verified, viewed)
- **V2** (hash 506326177..., the winner): three stacked bands. Orange: "iPhone." Sage: "Watch." Pink: "Airpods." then "Everything you rely on, powered by one pocket-sized charger." and a white pill "UP TO 30% OFF". No PETL logo wordmark outside the product.
- **V1** (hash d07a1c84...): a different layout, not a colour variant. Light-blue scene, PETL logo top left, headline "Phone. Watch. AirPods. All Charged.", subline "One compact PETL for all three. No separate chargers to buy.", five colour swatches (pink, green, lilac, grey, black), blue iPhone with a PETL on the back, AirPods and Watch each on their own PETL, "UP TO 30% OFF" bottom right.

### CLD922 on-image text (verified, viewed)
- **V1** (hash 0efea93c...): white-grey studio, four PETLs in a diagonal row (orange flat in front, then lilac, green, blue standing on edge), long shadows. "LAST CHANCE" in black, orange bar "UP TO 30% OFF", italic "Hurry before prices go up!", PETL logo bottom centre.
- **V2** (hash 901ca5a5...): lavender background, PETL logo top, "LAST CHANCE" in dark plum, plum bar "UP TO 30% OFF", six PETLs floating in an arc (lilac, blue, green, silver up top; gold and pink flat at the bottom), italic "Hurry before prices go up!" at the bottom.
- So V1 and V2 share the exact words; they differ in background, colour of the offer bar, product count and arrangement.

All three CLD922 and both CLD_1001 creatives carry the account's standard copy: primary text "One charger for your iPhone, Apple Watch, and AirPods. / Say goodbye to bulky cables & oversized battery packs.", headline "One Charger. Three Devices.", description "Ships FedEx 2Day.", CTA Shop Now (verified).

### PETL60: "We're Sorry, Black Back In Stock" (video)

**Meta (verified):** V1 video 1614641423629658, 68.2s; V2 1717986719499178, 69.1s; V3 2272595220158937, 66.6s. All created Sep 4 in PRODUCT FOCUS, standard copy, Meta video title "One Charger. Three Devices." on all three. Thumbnails: V1 = woman on camera holding a black PETL, caption "To the 1000 people"; V2 = 2x2 grid of four different people (woman, tattooed man with phone, young man with product, young woman with product), caption "To the 1000 of you"; V3 = hand holding a silver PETL on a desk next to AirPods and Watch, caption "One is 5% off." (a mid-video frame, so V3's hook isn't readable from it).

**Version mapping (inferred):** V1 "To the 1000 people" matches the primary hook; V2 "To the 1000 of you" matches Hook 2. V3's hook is data-limited.

**Conflict to check (verified both sides):** the brief and concept page say "Female VO over B-roll" and runtime 50-60s. The live V1 is 68s and its thumbnail frame shows a woman talking to camera, and V2's frame is a four-person grid. So either the cut added on-camera or AI-presenter footage, or the thumbnail frames are B-roll that looks like a presenter. Watch the asset (Frame.io link on the concept page: https://f.io/icasSWkj) before writing iterations that assume pure B-roll.

**Concept page (verified, Notion Master Creative Database, concept 60, Batch 5):** Status Approved / Ad Launched. Net New. Priority Urgent. Edit approved 2026-08-27, 3 internal revisions. ICP "Apple ecosystem buyer 45-65; previously interested, colour-blocked". Hypothesis (summarised): the Gyalbraids "we're sorry" winner works because a brand admitting fault breaks pattern and disarms resistance; PETL's Black really sold out (stated, Charley on Sync 5); the test is whether the apology carries demand proof without tipping into the scarcity register that failed on this account at 0.57x ROAS; female VO widens delivery beyond the male-creator ads.

**Script (verified, Notion brief table, verbatim):**

| Module | Script | Editor notes |
|---|---|---|
| 01 Hook | "To the 1,000 people who tried to buy a Black PETL last month - we're sorry." | Hand holding Black PETL, clean light-grey gradient. |
| 02 Body 1a | "It sold out. And honestly? We didn't see it coming." | Cut to sold-out state on site, Black swatch greyed. Beat of silence after the line. |
| 03 Body 1b | "So many of you picked Black over every other colour that it just went." | Fast cuts: colour lineup, Black pulled out of the row. |
| 04 Body 2a | "The good news is it's finally back." | Black snapping onto the phone. Land the magnet click in the audio. Music warms. "This is the turn." |
| 05 Body 2b | "If you've never seen one - it's a MagSafe-compatible battery that snaps onto the back of your iPhone. No cable, no outlet, nothing to plug in. It has 3000 mah, which charges just over 10 hours." | Snap-on demo, walking handheld. |
| 06 Body 2c | "And it doesn't just charge your phone. It charges your Apple Watch and your AirPods too. All three, off one tiny circle." | 3-device hero. "Core differentiator, give it room." |
| 07 Body 3a | "Machined aluminium, tempered glass. No plastic anywhere." | Macro, aluminium edge, glass top. |
| 08 Body 3b | "Small enough for a coin pocket. And it doubles as a stand, so everything charges on the nightstand while you sleep. It's the perfect travel companion. Use it on the plane, in your car while commuting, or even at home." | Coin pocket, then StandBy stand on nightstand. "Coin pocket outperforms regular pocket comparisons on this account." |
| 09 Body 4a | "And if Black isn't your thing - there are five other colours, including two new golds. Blush and Sahara. Makes the perfect gift for a friend or loved one." | Push in on golds; use client gold footage. |
| 10 Body 4b | "Over 50,000 people in the US have already bought one." | Text card. "Demand proof, not scarcity." |
| 11 Body 4c | "One is 5% off. Two is 20% - that's $42.40 each." | Ladder card, verified vs US store 16 July: 1 = $50.35, 2+ = $42.40, 3+ = $39.75, 5+ = $37.10. |
| 12 Body 4d | "And they have a 30-day garuntee and a one-year warranty. Something not to your liking? Simply send it back for a full refund" | Text card, risk reversal. |
| 13 CTA | "Black already sold out once. Don't miss it before it sells out again." | Black hero + gopetl.com. "The only scarcity beat in the whole ad." |
| Hook 2 | "To the 1,000 of you who watched our Viral Black PETL sell out - we owe you an apology." | Same visual as row 01. |
| Hook 3 | "If you went to buy the Viral Black PETL and it said sold out - we're sorry. Here's why." | Alt open. |
| Hook 4 | "If you've been waiting on our Black PETL that sold out last week - we owe you an apology. Here's why." | Alt open. |

**VO and editor notes (verified):** "female voiceover. Warm, natural, conversational. Slightly apologetic at the top, genuinely pleased on the reveal... Do not over-perform the apology." Switch shot every 2-3 seconds. Cut all four hooks as standalone openings. Scarcity confined to the CTA: no countdowns, timers or "last chance" cards anywhere else. Captions dynamic, bold, kinetic, sound-off; hook readable in 2s without audio; text cards for the 50,000 stat, the discount ladder and returns/warranty. Footage: existing PETL B-roll from Drive plus client-supplied gold footage (Claire unboxing + male ASMR). Music editor's choice. Reference: Gyalbraids "We're sorry" winner (Adnova link on the brief). The brief does not say the VO is AI; "AI VO" is stated in the task request only.

Note on the price line (inferred): the script's ladder ($42.40 at 2+) was checked on Jul 16. The account now runs "up to 30% off" on statics, so the spoken prices may be stale for an iteration. Check the live store before reusing them.

### PETL61: "Meet PETL 2 Plus - Male Creator" (Jared)

**Meta (verified):** see the V1-V4 table above. All carry the standard copy and Meta video title "One Charger. Three Devices." V4 thumbnail: split-screen, top half a hand holding the orange PETL 2 Plus box, bottom half Jared indoors, caption "I regret buying my PETL".

**Concept page (verified, concept 61, Batch 5):** Approved / Ad Launched. Net New. Urgent. Edit approved 2026-08-14, 1 internal revision. Creator Jared. ICP "Apple Ecosystem Buyer (35-65); existing PETL owners + prospects". Hypothesis (summarised): position Plus as more of a good thing, not a fix; fact-first, non-comparative script on the PETL48 structure (open on information, one thread, disarm-then-land honesty beat); spine is universal battery desire, big-iPhone fit mentioned once. Product: PETL 2 Plus (Cosmic Orange and Slate).

**Script (verified, Notion brief table, verbatim):**

| Module | Script | Editor notes |
|---|---|---|
| 01 Hook | "So most people don't even realize the PETL you keep seeing everywhere now comes in a bigger version. It's for when one charge just isn't enough." | Jared speaking while holding product, then snapping it to the phone. |
| 02 Body 1 | "Okay so here's the deal. The original PETL is 3,000mAh. It snaps onto your iPhone, tops you back up, and honestly it's great for everyday." | Cut to original-PETL B-roll. Don't undercut the original. |
| 03 Body 2 | "But say you're someone who kills your battery. Long days, loads of travel, or you've got one of the big phones like a Pro Max that just eats through it. That's why they made this one. The PETL 2 Plus." | Plus reveal, music lifts, snap-on B-roll. |
| 04 Body 3 | "It's 5,000mAh. That's 67% more, so you're looking at about 17 extra hours. I can be out all day and I'm not even thinking about finding a plug." | Text card 5,000mAh / 67% more / +17 HOURS. |
| 05 Body 4 | "It charges quicker too. So it's already topped up by the time I'm heading out the door." | Text card 15W / 50% MORE POWER (not spoken). |
| 06 Body 5 | "And everything you already love about PETL is still here. It snaps on, charges wirelessly, and it does all three at once. Your iPhone, your Watch, your AirPods." | 3-device hero. |
| 07 Body 6 | "It's proper aluminium and glass, no cheap plastic. It pops up in your iPhone battery widget on its own, no app or anything. It even flips into a little stand for your nightstand." | Macro, iOS battery widget, StandBy stand. |
| 08 Body 7 | "Now look, it's MagSafe compatible. I'm not gonna sit here and tell you it's an Apple product, because it's not. But it's the one I grab when I know it's gonna be a long day." | Compliance: keep wording exact. Trust beat. |
| 09 Body 8 | "You can get it in two colours. Cosmic Orange, or Slate." | Both colourways. |
| 10 CTA | "So yeah. If you just want more power in the same PETL you already love, go check out the PETL 2 Plus. Grab two and you get 20% off. Five gets you 30. Link's right here for you." | Ladder card 2+ = 20%, 5+ = 30%, free shipping on 2+. |
| Hook 2 | "You know the PETL everyone's got? It's got a bigger sibling now. More battery, same little circle." | Creator, then side-by-side size comparison. |
| Hook 3 | "If you've ever wished your PETL lasted even longer, well, they went and made a bigger, better version" | Creator, then Plus snapping to iPhone. (= live V3) |
| Hook 4 | "I regret buying my petl because they just released a 5,000mah version with a bigger, and better battery." | Split screen: Jared bottom, Plus B-roll top (unboxing, snaps). Hold up original, push out, bring Plus in. (= live V4) |

**Creator and editor notes (verified):** change location every 2-3 lines, indoor and outdoor ("the single most important instruction"); feature both colours; over-film Plus B-roll; generous unboxing; keep it conversational. Editor: cut on location changes, overlay B-roll on talking head, spec text cards, compliance ("MagSafe-compatible" only, never "Apple-approved"; "Apple Watch" not "iWatch"; no Apple logo). Captions and music match the Adnova reference ad linked on the brief.

**Inferred read for iteration:** the winning version is the only one whose hook is a negative-sounding twist ("I regret buying my PETL") with a split-screen visual. The three positive, information-first hooks got almost no delivery. That's the same "apparent negative" move PETL60 uses ("we're sorry"). Two cases is a pattern worth testing, not a rule.

## Data limits

- **Notion database row queries hit the workspace allowance** partway through; the two brief tables were read through their saved views instead, so they're complete. No other Notion tables were needed.
- **PETL61 V4's four-week gap (Sep 8 to Oct 5)** is verified as $0 spend; the reason (manual pause, ad set off, budget) is not pulled.
- **PETL60 VO type:** the brief says female VO over B-roll; thumbnails show on-camera people. The asset wasn't watched. AI VO is stated in the request, not in Notion.
- **PETL61 V1/V2 hook mapping** is inferred; their thumbnails carry no caption.
- **Sean_1001_2 videos** were not watched; calling them video versions of the three-device static rests on name and launch date.
- **Thruplays/impression** is the hold signal here, as in the prior doc; hook rate is still not available at ad level.
- **Attribution** is the main campaign's incrementality setting, same caveat as the prior doc.
- Meta CDN image/thumbnail URLs expire; re-pull by creative ID or image hash. Creative IDs: PETL60 V1 1849565459748043, V2 945396035282454, V3 1029722356784392; PETL61 V1 1086853440445161, V2 1693799995244609, V3 998474083154979, V4 1029112713058520; CLD922 V1 1839440423908216, V2 1047685714747727, V3 1631168155344714; CLD_1001 V1 1802956944278116, V2 1788651002086226; Clair 1456415426034073 (and 1622629338787776); Sean_1001_2 V1 2512694275807909, V2 1591744695826218.
