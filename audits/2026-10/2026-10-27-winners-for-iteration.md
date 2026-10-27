---
brand: petl
doc: winners-for-iteration
generated_on: 2026-10-27
windows: last 7 days 2026-10-20 to 10-26; last 14 days 2026-10-13 to 10-26; last 30 days 2026-09-27 to 10-26. "Prior week" = Oct 13 to 19, derived as 14d minus 7d.
purpose: numbers-only read of what's working, so Grace can plan single-variable iterations on winners
updates: audits/2026-10/2026-10-monthly-performance-report.md (Oct 27). Read alongside it; this doc does not repeat its narrative. Corrections to it are flagged inline.
data_sources_read:
  - Meta Ads MCP, account 3803347073290974, pulled 2026-10-27, read only. Ad level for all three windows (sorted by spend), ad level by object ID for the top 12, daily (Oct 13 to 26) for four ads, placement and age/gender breakdowns for CLD_1001 (7d), ad set level (7d) with optimization goal and attribution setting, creatives endpoint for 12 creatives, image and video lookups.
  - CLD_1001, CLD922 V2 and AR929 images viewed directly from the Meta CDN image URLs, 2026-10-27.
labels: Verified = pulled from Meta today. Inferred = arithmetic or a read on pulled numbers. Stated = from another doc or person.
---

# PETL winners for iteration — 2026-10-27

**Short version.** The three-band static Grace means is confirmed: it's **INTL | CLD_1001 | V2 | Three-device ecosystem** (ad 120250304411110194). It was created Oct 8, but it barely ran until Oct 20. Then Meta scaled it from $382 a day to $9K to $14K a day. Last 7 days: $53,211, 725 purchases, 1.78 ROAS, $73.39 CPA, $47 CPM (verified). That's 34% of the account's spend in its main campaign this week, at a CPM about a third of the account. On scale days (Oct 24 to 26) it held 1.60 to 1.68 ROAS. Its best day was the first big one, Oct 23, at 2.41 (verified, daily). So it's the account's volume and cheap-reach winner, not its efficiency winner. The efficiency winners are the bundle statics (CLD922 V1/V2, AR717 V1) and PETL61, all at 1.9 to 2.6 this week on much less money.

## How the top 10 is ranked

**Rule (inferred, stated here so it can be argued with):** an ad needs at least **$5,000 spend in the 30-day window** to count. Duplicate ad IDs carrying the same creative are merged into one row (PETL60 V1 has two IDs, Sean_911 H4 has two). Then score = **30-day ROAS × log10(30-day spend)**. The log means doubling spend is worth about +0.3 of score, so a $5K ad at 2.2 can beat a $100K ad at 1.6, but a $200 ad at 4x can't qualify at all. Account 30-day ROAS for reference is 1.64 (stated, monthly report).

Origin: NSY = name starts "NSY |". In-house = INTL, CLD, AR, Sean, ROG. Sean_911 H4 is the in-house re-shoot of NSY's PETL65 "Top 3 Chargers for Grandparents" (stated, monthly report and digest).

## Top 10 with trend and fatigue

Prior week = Oct 13 to 19. CTR is link (outbound) CTR. All numbers verified unless marked.

| # | Ad (status) | Origin / concept | Format | 30d spend / ROAS | Prior wk spend / ROAS | Last 7d spend / ROAS / CPA | 7d trend | Score |
|---|---|---|---|---|---|---|---|---|
| 1 | INTL \| CLD922 \| V2 (active) | In-house CLD, bundle static | Static 1080x1080 | $43,534 / 1.87 | $9,341 / 1.64 | $9,228 / 2.07 / $59.92 | Up | 8.68 |
| 2 | NSY \| PETL60 \| V1, two IDs (TOP PERFORMERS active, PRODUCT FOCUS paused) | NSY PETL60 | Video 68s | $137,239 / 1.69 | $35,221 / 1.62 | $21,460 / 1.89 / $75.56 | Up on ROAS, spend cut 39% | 8.68 |
| 3 | NSY \| PETL61 \| V4 \| MEET PETL PLUS (active) | NSY PETL61 | Video 78s | $23,721 / 1.96 | $14,113 / 1.79 | $9,257 / 2.18 / $61.71 | Up on ROAS, spend cut 34% | 8.58 |
| 4 | INTL \| CLD_1001 \| V2 \| Three-device ecosystem (active) | In-house CLD | Static 1080x1080 | $53,605 / 1.79 | $267 / 5.08 (tiny) | $53,211 / 1.78 / $73.39 | New at scale | 8.49 |
| 5 | INTL \| CLD922 \| V1 (active) | In-house CLD, bundle static | Static | $7,122 / 2.19 | $1,929 / 2.08 | $1,217 / 2.57 / $48.67 | Up, starved of spend | 8.45 |
| 6 | INTL \| Sean_911 \| H4 \| TOP 3 CHARGERS FOR GRANDPARENTS, two IDs (TOP PERFORMERS active, PRODUCT FOCUS paused) | In-house re-shoot of NSY PETL65 | Video 84s | $126,511 / 1.58 | $6,258 / 1.65 | $8,368 / 1.62 / $76.77 | Flat | 8.06 |
| 7 | INTL \| AR717 \| V1 \| BUNDLE DISCOUNT (active) | In-house AR | Catalog static (template creative) | $8,198 / 1.98 | $1,483 / 2.36 | $2,976 / 1.89 / $66.12 | Down on doubled spend | 7.75 |
| 8 | NSY \| PETL84 \| V3 (active) | NSY PETL84 | Long-copy static 4x5 | $8,562 / 1.96 | $1,338 / 2.04 | $1,364 / 1.56 / $85.27 | Down | 7.71 |
| 9 | INTL \| AR717 \| V3 \| GIFTING (paused) | In-house AR | Catalog static | $11,132 / 1.79 | $3,031 / 1.37 | $104 / 0.86 | Down, now paused | 7.25 |
| 10 | NSY \| PETL84 \| V2 (paused) | NSY PETL84 | Long-copy static 4x5 | $5,976 / 1.92 | $2,800 / 2.04 | $690 / 1.52 | Down, now paused | 7.24 |

Split: 3 NSY rows (PETL60, PETL61, PETL84 x2 = 4 ads), 6 in-house rows, of which one (Sean_911 H4) is an NSY concept re-shot in-house. Six of the ten are statics.

Just under the floor, worth watching (verified, 30d): **INTL | Sean_1016 | Product Focus | URGENTOFFER** $3,909 at 2.27, $55.84 CPA, video. **Ad 1 | Clair All charger | 1st Dec | ASC** (THREE DEVICES) $3,201 at 2.39, $45.73 CPA, 40s video, and the only top ad with different copy (PETL15 15% off code). **NSY | PETL84 | V1** $4,259 at 2.06. **NSY | PETL108 | PRICE ANNOUNCEMENT** $1,732 at 1.89. **INTL | CLD_1015 | CLEANBLACK** $628 at 2.50.

### Fatigue read per winner

Frequency below is per window as Meta reports it.

1. **CLD922 V2.** CPM flat ($111 prior week, $111 this week; $104 over 30d). CTR 2.56% (30d), 2.77% (14d), 2.71% (7d). Frequency 2.43 over 30d, the highest of the top 10, but 1.78 this week. Daily ROAS Oct 20 to 26 ran 1.36 to 2.81. **No fatigue.** It's improving at a steady ~$1.3K a day. Meta is not scaling it.
2. **PETL60 V1 (TOP PERFORMERS copy).** CPM fell from $462 to $413. CTR slipped from 4.30% (14d) to 4.06% (7d). Hold rate steady: thruplays per impression 18.7% (14d), 17.7% (7d). Frequency 1.07 this week. Meta moved $13.8K a week off it as CLD_1001 scaled (inferred from the timing). **Mild CTR softening, no ROAS fatigue.** Still the account's most expensive impressions by far.
3. **PETL61 V4.** CPM fell from $154 to $138. CTR 2.32% to 2.24%. Thruplays per impression 8.1% to 7.7%. Frequency 1.46. ROAS 1.79 to 2.18, with Oct 24 to 26 at 2.67 to 2.87. **No fatigue.** Spend is being cut while ROAS rises, which reads like budget pressure from CLD_1001, not decay (inferred).
4. **CLD_1001.** Only 7 days of real delivery, so fatigue can't show yet. Daily: Oct 20 $382 at 1.97, Oct 21 $1,389 at 1.42, Oct 22 $2,042 at 2.15, Oct 23 $9,057 at 2.41, Oct 24 $14,341 at 1.62, Oct 25 $13,270 at 1.60, Oct 26 $12,729 at 1.68. CPM $43 to $53 every day, CTR 1.73% to 2.00%, daily frequency 1.10 to 1.26. **No fatigue; ROAS stepped down when spend went up 5x.** Watch the 7-day frequency (1.54 now) and CTR under 1.8%.
5. **CLD922 V1.** CPM $92 to $81, ROAS 2.08 to 2.57. Too little spend to show fatigue. **Not fatigued, under-funded.**
6. **Sean_911 H4.** The PRODUCT FOCUS copy ($107,801 at 1.59) took no spend after Oct 12. The TOP PERFORMERS copy: CPM $193 to $180, ROAS 1.65 to 1.62, CTR 3.83% (old copy, 30d) down to 3.43% (7d). **Family-level fatigue** (stated in the monthly report, numbers consistent).
7. **AR717 V1.** Running since Jul 17. Spend doubled week on week and ROAS fell 2.36 to 1.89. CTR 1.91% (30d) to 1.70% (7d). Frequency 2.10 (30d). **Early fatigue signs.**
8. **PETL84 V3.** ROAS 2.04 to 1.56, CTR 2.14% (14d) to 1.97% (7d), frequency 2.34 (30d). **Fatigue showing.** Matches the PETL Analytics flag that all PETL84 variants were declining (stated, monthly report).
9. **AR717 V3 Gifting.** 1.79 over 30d but 1.37 the prior week, then paused. **Spent.**
10. **PETL84 V2.** 2.04 prior week, 1.52 on $690 this week, paused. **Spent.**

## The three-band static: CLD_1001

**Identity (verified).** Ad ID 120250304411110194, creative 1788651002086226, image hash 506326177ed3d770f053b5c7a12e6e17, image file name `INTL_CLD_1001_2_1080.png`, 1080x1080. Campaign "April 29 | VO-IA-ASC - Scaling CBO | Sales| Catalogue Dec 1 | duplicate", ad set THREE DEVICES. Status active. Created 2026-10-08. CTA Shop Now. Facebook post ID 518140051386660_122174119370713050.

**What the image shows (verified, viewed).** Three full-width horizontal bands stacked top to bottom. Top band burnt orange: an orange iPhone with an orange PETL disc on its back, big white word "iPhone." Middle band sage green: an Apple Watch with a sage band sitting on a sage PETL disc, "Watch." Bottom band dusty pink: white AirPods case on a pink PETL disc, "Airpods.", then the line "Everything you rely on, powered by one pocket-sized charger." and a white pill reading "UP TO 30% OFF". So it's three bands, not a 2x2 quadrant. Each band pairs one device with a PETL in a matching colour. The ad copy around it is the account's standard copy.

**Copy (verified).**
- Primary text: "One charger for your iPhone, Apple Watch, and AirPods. Say goodbye to bulky cables & oversized battery packs."
- Headline: "One Charger. Three Devices."
- Description: "Ships FedEx 2Day."

**Image URL (verified; Meta CDN links expire, re-pull by hash if dead):**
https://scontent-ord5-2.xx.fbcdn.net/v/t45.1600-4/836197943_122224389164379579_3537857742447770827_n.png?stp=dst-jpg_tt6&_nc_cat=105&ccb=1-7&_nc_sid=cbc22b&_nc_ohc=rq4WXm-_6-4Q7kNvwHx2uH-&_nc_oc=AdrCzLDceWJJZsl4ZntqSl7tH_3sLEmHVjeBoQW0Na1KXd3pDegmK-sQkuaFUiCuYB8&_nc_zt=1&_nc_ht=scontent-ord5-2.xx&edm=AEZPnVgEAAAA&_nc_gid=UNhaO_AWpLIMj4bj9zGmZw&_nc_tpa=Q5bMBQLQc-H51WBcR2okkXngrmxlgRIvNv6EfY6B0fCJMxFbjYvOiPzr8BSaGrkKlRDrzhjg7tMcLGLwkQ&oh=00_AQMnyRiDQ4Dr8mb7SRQdT-DGi_oZ4K_TRuocQMtbyKJkOQ&oe=6AE6811B

**Per window (verified).**

| Window | Spend | Purchases | Revenue | ROAS | CPA | Link CTR | CPM | Impressions | Reach | Frequency |
|---|---|---|---|---|---|---|---|---|---|---|
| 7d (Oct 20–26) | $53,211 | 725 | $94,724 | 1.78 | $73.39 | 1.91% | $47.27 | 1,125,560 | 730,580 | 1.54 |
| 14d (Oct 13–26) | $53,478 | 737 | $96,081 | 1.80 | $72.56 | 1.90% | $47.25 | 1,131,749 | 731,098 | 1.55 |
| 30d (Sep 27–Oct 26) | $53,605 | 739 | $96,219 | 1.79 | $72.54 | 1.90% | $47.25 | 1,134,532 | 731,163 | 1.55 |

99.3% of its lifetime spend landed in the last 7 days, so the three windows are nearly the same ad (inferred). Its ad set, THREE DEVICES, spent $55,366 at 1.81 this week; CLD_1001 is 96% of that ad set (verified, ad set level).

**Placement split, last 7 days (verified).**

| Placement | Spend | Share | ROAS | CPA | CPM | Link CTR |
|---|---|---|---|---|---|---|
| Facebook feed | $35,257 | 66.3% | 1.90 | $71.23 | $42.88 | 1.79% |
| Instagram feed | $12,174 | 22.9% | 1.71 | $70.78 | $68.62 | 1.99% |
| Instagram stories | $2,175 | 4.1% | 0.99 | $120.83 | $81.81 | 3.12% |
| Facebook reels | $1,087 | 2.0% | 1.99 | $60.37 | $46.45 | 2.91% |
| Threads feed | $721 | 1.4% | 0.91 | $144.23 | $21.65 | 2.14% |
| Instagram reels | $658 | 1.2% | 1.16 | $109.60 | $46.32 | 3.46% |
| Facebook stories | $610 | 1.1% | 1.10 | $101.73 | $94.95 | 4.08% |
| Other (profile feed, marketplace, right column, AN, unknown) | ~$528 | 1.0% | mixed | | | |

Feed carries it. In Instagram stories, Instagram reels, Facebook stories and Threads, the square image gets more clicks but buys poorly: $4,164 combined at about 1.0 ROAS (inferred sum). Facebook reels is the exception, 1.99 on $1,087.

**Age and gender, last 7 days (verified).**

| Age | Spend | Share | ROAS | CPA |
|---|---|---|---|---|
| 18–24 | $312 | 0.6% | 1.99 | $51.95 |
| 25–34 | $3,552 | 6.7% | 1.84 | $68.31 |
| 35–44 | $13,068 | 24.6% | 1.70 | $77.33 |
| 45–54 | $17,254 | 32.4% | 1.73 | $77.03 |
| 55–64 | $12,485 | 23.5% | 1.80 | $73.44 |
| 65+ | $6,540 | 12.3% | 1.97 | $62.88 |

| Gender | Spend | Share | ROAS | CPA | CPM |
|---|---|---|---|---|---|
| Female | $33,368 | 62.7% | 1.83 | $73.01 | $37–73 by age |
| Male | $19,464 | 36.6% | 1.70 | $74.01 | $18–42 by age |

Best cells with real money: women 65+ $4,164 at 2.01, women 25–34 $2,074 at 2.01, women 35–44 $8,145 at 1.90, men 65+ $2,305 at 1.84, men 45–54 $6,287 at 1.82, men 55–64 $4,436 at 1.82. Weakest: men 35–44 $4,842 at 1.40. Men cost half as much to reach as women at every age (men 45–54 CPM $37 vs women $65).

**Correction to the monthly report (verified today):** men took 36.6% of this ad's spend, not "about 45%." The 35–54 share ($30,322, 57%) and the men 45–64 ROAS (1.82) roughly match what it said.

**Related statics people may be mixing up (verified, viewed).** CLD922 V2 is a lavender "LAST CHANCE / UP TO 30% OFF" static with six floating PETL discs in different colours and "Hurry before prices go up!" It's the bundle winner, not the three-device one. INTL | AR929 | 2 | V1 (THREE DEVICES, $312 this week at 2.22) is a sage-background static, "10 Hrs Messaging. One Puck.", with an orange PETL in the middle, Watch, AirPods and orange iPhone around it, charge-count callouts, and a "30% OFF" badge.

## Tables per window

All ads with at least $1,000 spend in the window, sorted by spend (verified). Format marked (i) is inferred from video play counts, not from the creative pull. "Status" is today's.

### Last 7 days (Oct 20–26)

| Ad | Ad ID | Ad set | Status | Created | Format | Spend | Purch | Revenue | ROAS | CPA | Link CTR | CPM | Freq | Thruplays | Avg watch |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| INTL \| CLD_1001 \| V2 \| Three-device ecosystem | 120250304411110194 | THREE DEVICES | Active | Oct 8 | Static | $53,211 | 725 | $94,724 | 1.78 | $73.39 | 1.91% | $47.27 | 1.54 | n/a | n/a |
| NSY \| PETL60 \| V1 | 120250326901490194 | TOP PERFORMERS | Active | Oct 9 | Video 68s | $21,460 | 284 | $40,570 | 1.89 | $75.56 | 4.06% | $413.23 | 1.07 | 9,179 | 11s |
| NSY \| PETL125 \| 60 YEARS OF PHONES | 120250430855620194 | PRODUCT FOCUS | Active | Oct 16 | Video (i) | $13,544 | 144 | $19,582 | 1.45 | $94.06 | 3.69% | $197.32 | 1.16 | 16,326 | 30s |
| NSY \| PETL61 \| V4 \| MEET PETL PLUS | 120249382423130194 | PETL PLUS | Active | Aug 14 | Video 78s | $9,257 | 150 | $20,190 | 2.18 | $61.71 | 2.24% | $137.99 | 1.46 | 5,186 | 6s |
| INTL \| CLD922 \| V2 | 120250059248960194 | BUNDLES DISCOUNTS | Active | Sep 22 | Static | $9,228 | 154 | $19,063 | 2.07 | $59.92 | 2.71% | $111.16 | 1.78 | n/a | n/a |
| INTL \| Sean_911 \| H4 \| TOP 3 CHARGERS FOR GRANDPARENTS | 120250326901480194 | TOP PERFORMERS | Active | Oct 9 | Video 84s | $8,368 | 109 | $13,549 | 1.62 | $76.77 | 3.43% | $180.09 | 1.08 | 8,409 | 12s |
| NSY \| PETL73 \| BEST GIFT FOR GRANDPARENTS | 120250430795880194 | GIFTING | Active | Oct 16 | Video (i) | $6,025 | 61 | $8,705 | 1.44 | $98.76 | 3.98% | $267.33 | 1.23 | 4,736 | 16s |
| NSY \| PETL105 \| NEW IPHONE? | 120250431464930194 | PRODUCT FOCUS | Paused | Oct 16 | Static (i) | $4,995 | 45 | $5,526 | 1.11 | $111.00 | 2.36% | $72.07 | 1.41 | null | 2s |
| NSY \| PETL116 \| COMPETITOR COMPARISON | 120250431200800194 | Testimonial | Active | Oct 16 | Static (i) | $3,875 | 48 | $5,579 | 1.44 | $80.72 | 1.41% | $59.18 | 1.71 | 13 | 15s |
| INTL \| AR717 \| V1 \| BUNDLE DISCOUNT | 120248687379620194 | BUNDLES DISCOUNTS | Active | Jul 17 | Catalog static | $2,976 | 45 | $5,614 | 1.89 | $66.12 | 1.70% | $60.34 | 1.87 | null | 1s |
| INTL \| Sean_1016 \| Product Focus \| URGENTOFFER | 120250448483960194 | PRODUCT FOCUS | Active | Oct 17 | Video (i) | $2,897 | 50 | $6,537 | 2.26 | $57.94 | 1.93% | $89.14 | 1.90 | 1,157 | 3s |
| INTL \| Sean_1014 \| Product Focus \| GRANDLEGACY | 120250417377100194 | PRODUCT FOCUS | Active | Oct 15 | Video (i) | $2,797 | 26 | $4,316 | 1.54 | $107.56 | 2.01% | $178.90 | 1.28 | 881 | 4s |
| NSY \| PETL25 \| H3 | 120250363679740194 | PRODUCT FOCUS | Paused | Oct 12 | Video (i) | $2,608 | 21 | $2,748 | 1.05 | $124.20 | 1.81% | $149.35 | 1.17 | 1,834 | 9s |
| Ad 1 \| Clair All charger \| 1st Dec \| ASC | 120250363639220194 | THREE DEVICES | Active | Oct 12 | Video 40s | $1,718 | 43 | $4,574 | 2.66 | $39.94 | 2.23% | $95.76 | 1.39 | 1,302 | 5s |
| NSY \| PETL84 \| V1 | 120249850321890194 | Testimonial | Paused | Sep 10 | Static (i) | $1,503 | 16 | $1,935 | 1.29 | $93.94 | 1.61% | $105.47 | 1.43 | 1 | 21s |
| NSY \| PETL108 \| PRICE ANNOUNCEMENT | 120250431834240194 | BUNDLES DISCOUNTS | Active | Oct 16 | Static (i) | $1,411 | 25 | $2,873 | 2.04 | $56.44 | 1.75% | $76.90 | 2.23 | 1 | 5s |
| NSY \| PETL84 \| V3 | 120249850381760194 | Testimonial | Active | Sep 10 | Static 4x5 | $1,364 | 16 | $2,123 | 1.56 | $85.27 | 1.97% | $140.85 | 1.66 | n/a | n/a |
| NSY \| PETL115 \| PSA FOR GRANDPARENTS | 120250431707990194 | PRODUCT FOCUS | Paused | Oct 16 | Static (i) | $1,233 | 9 | $1,527 | 1.24 | $136.97 | 1.75% | $99.23 | 1.50 | 1 | 3s |
| INTL \| CLD922 \| V1 | 120250059233810194 | BUNDLES DISCOUNTS | Active | Sep 22 | Static | $1,217 | 25 | $3,131 | 2.57 | $48.67 | 2.12% | $80.53 | 1.49 | n/a | n/a |
| NSY \| PETL112 \| MINIMAL PRICE CROSSED OUT | 120250431878560194 | BUNDLES DISCOUNTS | Paused | Oct 16 | Static (i) | $1,185 | 12 | $1,598 | 1.35 | $98.77 | 1.72% | $82.11 | 1.87 | null | null |

### Last 14 days (Oct 13–26)

| Ad | Ad ID | Ad set | Status | Format | Spend | Purch | ROAS | CPA | Link CTR | CPM | Freq | Thruplays / impr | Avg watch |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| NSY \| PETL60 \| V1 | 120250326901490194 | TOP PERFORMERS | Active | Video | $56,681 | 704 | 1.72 | $80.51 | 4.30% | $442.01 | 1.16 | 18.7% | 11s |
| INTL \| CLD_1001 \| V2 \| Three-device ecosystem | 120250304411110194 | THREE DEVICES | Active | Static | $53,478 | 737 | 1.80 | $72.56 | 1.90% | $47.25 | 1.55 | n/a | n/a |
| NSY \| PETL125 \| 60 YEARS OF PHONES | 120250430855620194 | PRODUCT FOCUS | Active | Video | $31,609 | 317 | 1.32 | $99.71 | 3.57% | $186.13 | 1.35 | 24.4% | 30s |
| NSY \| PETL61 \| V4 \| MEET PETL PLUS | 120249382423130194 | PETL PLUS | Active | Video | $23,370 | 352 | 1.95 | $66.39 | 2.32% | $147.50 | 1.74 | 8.1% | 6s |
| INTL \| CLD922 \| V2 | 120250059248960194 | BUNDLES DISCOUNTS | Active | Static | $18,569 | 264 | 1.85 | $70.34 | 2.77% | $110.98 | 1.86 | n/a | n/a |
| INTL \| Sean_911 \| H4 \| TOP 3 CHARGERS (TP copy) | 120250326901480194 | TOP PERFORMERS | Active | Video | $14,625 | 198 | 1.63 | $73.87 | 3.60% | $185.59 | 1.18 | 18.2% | 13s |
| NSY \| PETL105 \| NEW IPHONE? | 120250431464930194 | PRODUCT FOCUS | Paused | Static (i) | $13,629 | 143 | 1.33 | $95.31 | 2.43% | $66.42 | 1.95 | n/a | |
| NSY \| PETL73 \| BEST GIFT FOR GRANDPARENTS | 120250430795880194 | GIFTING | Active | Video | $10,146 | 114 | 1.57 | $89.00 | 3.99% | $255.50 | 1.29 | 20.5% | 16s |
| May 1 \| PETL 32 AR \| V4 \| 30 P | 120243876106910194 | May 1 \| BOFU | Paused | Video (i) | $8,581 | 98 | 1.37 | $87.56 | 2.04% | $118.75 | 1.62 | 8.5% | 8s |
| NSY \| PETL25 \| H3 | 120250363679740194 | PRODUCT FOCUS | Paused | Video | $7,627 | 81 | 1.57 | $94.16 | 2.07% | $147.33 | 1.37 | 10.7% | 9s |
| NSY \| PETL65 \| V4 \| TOP 3 CHARGERS | 120249297609490194 | PRODUCT FOCUS | Paused | Video | $7,420 | 78 | 1.34 | $95.13 | 3.63% | $249.68 | 1.11 | 16.8% | 14s |
| NSY \| PETL48 \| V2 \| TOP 5 MAGSAFE POWER BANKS RANKED | 120250363523450194 | US VS THEM | Paused | Video | $5,397 | 56 | 1.24 | $96.37 | 2.48% | $123.49 | 1.08 | 12.3% | 14s |
| NSY \| PETL116 \| COMPETITOR COMPARISON | 120250431200800194 | Testimonial | Active | Static (i) | $5,178 | 67 | 1.55 | $77.28 | 1.42% | $58.17 | 2.03 | n/a | |
| INTL \| AR717 \| V1 \| BUNDLE DISCOUNT | 120248687379620194 | BUNDLES DISCOUNTS | Active | Catalog static | $4,459 | 77 | 2.04 | $57.90 | 1.71% | $61.48 | 2.07 | n/a | |
| NSY \| PETL112 \| MINIMAL PRICE CROSSED OUT | 120250431878560194 | BUNDLES DISCOUNTS | Paused | Static (i) | $3,991 | 44 | 1.43 | $90.71 | 1.79% | $77.39 | 2.97 | n/a | |
| INTL \| Sean_1016 \| Product Focus \| URGENTOFFER | 120250448483960194 | PRODUCT FOCUS | Active | Video | $3,909 | 70 | 2.27 | $55.84 | 1.87% | $87.15 | 2.16 | 3.5% | 3s |
| INTL \| Sean_1014 \| Product Focus \| GRANDLEGACY | 120250417377100194 | PRODUCT FOCUS | Active | Video | $3,838 | 43 | 1.97 | $89.27 | 2.07% | $168.94 | 1.39 | 5.3% | 4s |
| NSY \| PETL84 \| V2 | 120249850349830194 | Testimonial | Paused | Static 4x5 | $3,490 | 55 | 1.93 | $63.46 | 1.90% | $118.09 | 2.03 | n/a | |
| INTL \| CLD922 \| V1 | 120250059233810194 | BUNDLES DISCOUNTS | Active | Static | $3,146 | 56 | 2.27 | $56.17 | 2.14% | $87.43 | 1.65 | n/a | |
| INTL \| AR717 \| V3 \| GIFTING | 120248687456590194 | GIFTING | Paused | Catalog static | $3,135 | 38 | 1.35 | $82.49 | 2.09% | $112.63 | 1.67 | n/a | |
| Ad 1 \| Clair All charger \| 1st Dec \| ASC | 120250363639220194 | THREE DEVICES | Active | Video | $3,057 | 66 | 2.32 | $46.32 | 2.37% | $109.49 | 1.52 | 7.2% | 5s |
| NSY \| PETL84 \| V1 | 120249850321890194 | Testimonial | Paused | Static (i) | $2,768 | 31 | 1.48 | $89.30 | 1.62% | $103.84 | 1.62 | n/a | |
| NSY \| PETL84 \| V3 | 120249850381760194 | Testimonial | Active | Static 4x5 | $2,703 | 32 | 1.80 | $84.46 | 2.14% | $146.53 | 1.89 | n/a | |
| NSY \| PETL108 \| PRICE ANNOUNCEMENT | 120250431834240194 | BUNDLES DISCOUNTS | Active | Static (i) | $1,732 | 29 | 1.89 | $59.73 | 1.78% | $79.45 | 2.40 | n/a | |
| NSY \| PETL115 \| PSA FOR GRANDPARENTS | 120250431707990194 | PRODUCT FOCUS | Paused | Static (i) | $1,723 | 17 | 1.43 | $101.37 | 1.83% | $96.20 | 1.69 | n/a | |
| NSY \| PETL72 \| V3 \| THE GIFT THAT DOESN'T END UP IN A DRAWER | 120249849441420194 | GIFTING | Paused | Video | $1,170 | 2 | 1.15 | $584.91 | 4.95% | $573.72 | 1.13 | 25.5% | 20s |
| INTL \| CLD_1002 \| V2 \| Bundle Discounts \| BUNDLEFIX | 120250327067430194 | BUNDLES DISCOUNTS | Paused | Static (i) | $1,074 | 12 | 1.26 | $89.50 | 1.36% | $71.39 | 1.54 | n/a | |
| INTL \| CLD929 \| 2 \| V4 | 120250166158160194 | GIFTING | Paused | Static (i) | $1,011 | 7 | 1.04 | $144.39 | 2.75% | $109.67 | 1.44 | n/a | |

### Last 30 days (Sep 27–Oct 26)

Top 35 ads by spend (the pull stopped at $1,994, so ads between $1,000 and $1,993 are not listed).

| Ad | Ad ID | Ad set | Status | Created | Format | Spend | Purch | Revenue | ROAS | CPA | Link CTR | CPM | Freq | Thruplays / impr | Avg watch |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| INTL \| Sean_911 \| H4 \| TOP 3 CHARGERS (PF copy) | 120249880169740194 | PRODUCT FOCUS | Paused | Sep 11 | Video 84s | $107,801 | 1,408 | $170,956 | 1.59 | $76.56 | 3.83% | $170.81 | 1.44 | 19.8% | 13s |
| NSY \| PETL60 \| V1 (TP copy) | 120250326901490194 | TOP PERFORMERS | Active | Oct 9 | Video 68s | $81,544 | 1,025 | $140,610 | 1.72 | $79.55 | 4.08% | $410.02 | 1.19 | 18.1% | 11s |
| NSY \| PETL60 \| V1 (PF copy) | 120249723254010194 | PRODUCT FOCUS | Paused | Sep 4 | Video 68s | $55,696 | 712 | $91,132 | 1.64 | $78.22 | 4.40% | $332.58 | 1.21 | 18.2% | 11s |
| INTL \| CLD_1001 \| V2 \| Three-device ecosystem | 120250304411110194 | THREE DEVICES | Active | Oct 8 | Static | $53,605 | 739 | $96,219 | 1.79 | $72.54 | 1.90% | $47.25 | 1.55 | n/a | n/a |
| INTL \| CLD922 \| V2 | 120250059248960194 | BUNDLES DISCOUNTS | Active | Sep 22 | Static | $43,534 | 625 | $81,470 | 1.87 | $69.65 | 2.56% | $103.89 | 2.43 | n/a | n/a |
| NSY \| PETL125 \| 60 YEARS OF PHONES | 120250430855620194 | PRODUCT FOCUS | Active | Oct 16 | Video | $31,609 | 317 | $41,674 | 1.32 | $99.71 | 3.57% | $186.13 | 1.35 | 24.4% | 30s |
| NSY \| PETL61 \| V4 \| MEET PETL PLUS | 120249382423130194 | PETL PLUS | Active | Aug 14 | Video 78s | $23,721 | 359 | $46,492 | 1.96 | $66.07 | 2.32% | $147.14 | 1.77 | 8.1% | 7s |
| NSY \| PETL64 \| V1 \| PETL PLUS UNBOXING | 120249382432270194 | PETL PLUS | Paused | Aug 14 | Video | $19,394 | 199 | $26,147 | 1.35 | $97.46 | 2.19% | $140.26 | 1.21 | 14.9% | 10s |
| INTL \| Sean_911 \| H4 \| TOP 3 CHARGERS (TP copy) | 120250326901480194 | TOP PERFORMERS | Active | Oct 9 | Video 84s | $18,711 | 245 | $28,977 | 1.55 | $76.37 | 3.61% | $185.55 | 1.20 | 17.7% | 12s |
| NSY \| PETL105 \| NEW IPHONE? | 120250431464930194 | PRODUCT FOCUS | Paused | Oct 16 | Static (i) | $13,629 | 143 | $18,167 | 1.33 | $95.31 | 2.43% | $66.42 | 1.95 | n/a | |
| INTL \| ROG813 \| V4 | 120249497639110194 | US VS THEM | Paused | Aug 19 | Video (i) | $12,966 | 166 | $20,375 | 1.57 | $78.11 | 2.60% | $145.39 | 1.48 | 12.8% | 16s |
| INTL \| AR717 \| V3 \| GIFTING | 120248687456590194 | GIFTING | Paused | Jul 17 | Catalog static | $11,132 | 163 | $19,943 | 1.79 | $68.29 | 2.20% | $102.41 | 2.19 | n/a | |
| NSY \| PETL73 \| BEST GIFT FOR GRANDPARENTS | 120250430795880194 | GIFTING | Active | Oct 16 | Video | $10,146 | 114 | $15,901 | 1.57 | $89.00 | 3.99% | $255.50 | 1.29 | 20.5% | 16s |
| May 1 \| PETL 32 AR \| V4 \| 30 P | 120243876106910194 | May 1 \| BOFU | Paused | May 1 | Video (i) | $9,808 | 117 | $14,116 | 1.44 | $83.83 | 1.95% | $110.75 | 1.77 | 7.8% | 8s |
| NSY \| PETL65 \| V4 \| TOP 3 CHARGERS | 120249297609490194 | PRODUCT FOCUS | Paused | Aug 11 | Video | $8,653 | 92 | $11,645 | 1.35 | $94.06 | 3.56% | $234.68 | 1.12 | 16.4% | 14s |
| NSY \| PETL84 \| V3 | 120249850381760194 | Testimonial | Active | Sep 10 | Static 4x5 | $8,562 | 116 | $16,782 | 1.96 | $73.81 | 1.98% | $129.90 | 2.34 | n/a | |
| NSY \| PETL48 \| V2 \| TOP 5 MAGSAFE POWER BANKS RANKED | 120250363523450194 | US VS THEM | Paused | Oct 12 | Video | $8,203 | 85 | $9,760 | 1.19 | $96.51 | 2.44% | $115.57 | 1.16 | 12.2% | 13s |
| INTL \| AR717 \| V1 \| BUNDLE DISCOUNT | 120248687379620194 | BUNDLES DISCOUNTS | Active | Jul 17 | Catalog static | $8,198 | 148 | $16,233 | 1.98 | $55.40 | 1.91% | $67.70 | 2.10 | n/a | |
| NSY \| PETL76 \| V5 \| DECLUTTER TRANSFORMATION | 120250214239870194 | THREE DEVICES | Paused | Oct 2 | Video | $7,887 | 83 | $10,686 | 1.35 | $95.02 | 3.24% | $207.82 | 1.25 | 16.2% | 15s |
| NSY \| PETL25 \| H3 | 120250363679740194 | PRODUCT FOCUS | Paused | Oct 12 | Video | $7,646 | 81 | $12,006 | 1.57 | $94.40 | 2.07% | $147.22 | 1.38 | 10.7% | 9s |
| NSY \| PETL72 \| V3 \| THE GIFT THAT DOESN'T END UP IN A DRAWER | 120249849441420194 | GIFTING | Paused | Sep 10 | Video | $7,356 | 61 | $11,750 | 1.60 | $120.58 | 4.40% | $369.91 | 1.37 | 22.6% | 16s |
| INTL \| CLD922 \| V1 | 120250059233810194 | BUNDLES DISCOUNTS | Active | Sep 22 | Static | $7,122 | 127 | $15,621 | 2.19 | $56.08 | 2.00% | $83.51 | 1.98 | n/a | |
| NSY \| PETL84 \| V2 | 120249850349830194 | Testimonial | Paused | Sep 10 | Static 4x5 | $5,976 | 89 | $11,464 | 1.92 | $67.15 | 1.75% | $103.35 | 2.34 | n/a | |
| NSY \| PETL116 \| COMPETITOR COMPARISON | 120250431200800194 | Testimonial | Active | Oct 16 | Static (i) | $5,178 | 67 | $8,040 | 1.55 | $77.28 | 1.42% | $58.17 | 2.03 | n/a | |
| NSY \| PETL84 \| V1 | 120249850321890194 | Testimonial | Paused | Sep 10 | Static (i) | $4,259 | 63 | $8,782 | 2.06 | $67.60 | 1.55% | $102.14 | 1.83 | n/a | |
| NSY \| PETL112 \| MINIMAL PRICE CROSSED OUT | 120250431878560194 | BUNDLES DISCOUNTS | Paused | Oct 16 | Static (i) | $3,991 | 44 | $5,706 | 1.43 | $90.71 | 1.79% | $77.39 | 2.97 | n/a | |
| INTL \| Sean_1016 \| Product Focus \| URGENTOFFER | 120250448483960194 | PRODUCT FOCUS | Active | Oct 17 | Video | $3,909 | 70 | $8,873 | 2.27 | $55.84 | 1.87% | $87.15 | 2.16 | 3.5% | 3s |
| INTL \| Sean_1014 \| Product Focus \| GRANDLEGACY | 120250417377100194 | PRODUCT FOCUS | Active | Oct 15 | Video | $3,838 | 43 | $7,575 | 1.97 | $89.27 | 2.07% | $168.94 | 1.39 | 5.3% | 4s |
| INTL \| CLD830 \| V10 | 120249813928820194 | PRODUCT FOCUS | Paused | Sep 8 | Static (i) | $3,811 | 55 | $6,399 | 1.68 | $69.29 | 1.99% | $45.78 | 1.56 | n/a | |
| Ad 1 \| Clair All charger \| 1st Dec \| ASC | 120250363639220194 | THREE DEVICES | Active | Oct 12 | Video 40s | $3,201 | 70 | $7,651 | 2.39 | $45.73 | 2.34% | $110.36 | 1.52 | 7.1% | 5s |
| NSY \| PETL91 \| V1 | 120249938507300194 | BUNDLES DISCOUNTS | Paused | Sep 15 | Static (i) | $3,176 | 47 | $5,702 | 1.80 | $67.57 | 1.90% | $114.29 | 1.90 | n/a | |
| INTL \| CLD929 \| 2 \| V4 | 120250166158160194 | GIFTING | Paused | Sep 29 | Static (i) | $3,090 | 37 | $4,460 | 1.44 | $83.52 | 2.48% | $99.19 | 1.77 | n/a | |
| INTL \| SEAN924 \| 2 \| V3 | 120250103698270194 | PRODUCT FOCUS | Paused | Sep 25 | Video (i) | $2,616 | 47 | $4,448 | 1.70 | $55.67 | 2.30% | $124.91 | 1.47 | 11.2% | 7s |
| NSY \| PETL69 \| V1 | 120249849142410194 | PETL PLUS | Paused | Sep 10 | Video (i) | $2,177 | 33 | $5,013 | 2.30 | $65.97 | 2.29% | $135.50 | 1.56 | 10.6% | 8s |
| INTL \| AR827 \| V4 | 120249651493190194 | PRODUCT FOCUS | Paused | Aug 28 | Static (i) | $1,994 | 33 | $3,661 | 1.84 | $60.41 | 1.61% | $61.00 | 1.62 | n/a | |

## Creative details for the top 10 (verified)

All but two top-10 creatives carry the same copy: primary text "One charger for your iPhone, Apple Watch, and AirPods. Say goodbye to bulky cables & oversized battery packs.", headline "One Charger. Three Devices.", description "Ships FedEx 2Day.", CTA Shop Now. The exceptions: AR717 V1 and V3 are catalog template creatives (name "{{product.name}}") with no primary text or headline stored on the creative. Outside the top 10, "Ad 1 | Clair All charger" is the one ad with its own copy: headline "🚨 3 devices. 1 PETL. Use PETL15 = 15% OFF", primary text opening "Replace 3 chargers with 1 ✨ PETL's World's 1st circular MagSafe design charges iPhone + AirPods + Apple Watch in one sleek snap."

| Ad | Creative ID | Type | Asset / length | Asset name text |
|---|---|---|---|---|
| CLD922 V2 | 1047685714747727 | Image | hash 901ca5a5…, 1080x1080 | INTL_CLD_922_2_1080.png. On-image: "LAST CHANCE / UP TO 30% OFF / Hurry before prices go up!" (viewed) |
| PETL60 V1 | 1849565459748043 | Video | video 1614641423629658, 68.2s | Video title "One Charger. Three Devices." (no concept text) |
| PETL61 V4 | 1029112713058520 | Video | video 2203285273646958, 77.7s | Same generic title |
| CLD_1001 V2 | 1788651002086226 | Image | hash 506326177…, 1080x1080 | INTL_CLD_1001_2_1080.png |
| CLD922 V1 | 1839440423908216 | Image | hash 0efea93c…, 1080x1080 | INTL_CLD_922_1_1080.png (not viewed) |
| Sean_911 H4 | 2551127825408338 | Video | video 1716290722786467, 84.4s | Same generic title |
| AR717 V1 | 1890185725274895 | Catalog share | thumbnail only | {{product.name}} template |
| PETL84 V3 | 1954093501929094 | Image | hash 1fbf56b0…, 1638x2048 (4x5) | "NSY_PETL84 - It's Official, We're Ending It - Price Announcement (Long-Copy Static) - 4 x 5" |
| AR717 V3 | 1431850888964691 | Catalog share | thumbnail only | {{product.name}} template |
| PETL84 V2 | 1387252220242072 | Image | hash 90123f95…, 1638x2048 (4x5) | Same PETL84 file name as V3 (a different upload) |

Image and thumbnail URLs are long, signed Meta CDN links that expire. Re-pull them with the creative IDs or image hashes above through `ads_get_creatives` or `ads_get_ad_images` when needed. The CLD_1001 URL is written out in full above.

## Structure the winners sit in (verified, ad set level, last 7 days)

Nearly everything runs in one campaign: **"April 29 | VO-IA-ASC - Scaling CBO | Sales| Catalogue Dec 1 | duplicate"**, a budget-optimized sales campaign. All seven of its live ad sets optimize for **purchase value** (optimization goal VALUE), use the **incrementality** attribution setting, and are not dynamic creative.

| Ad set | Created | 7d spend | 7d ROAS | 7d CPA | 7d CPM | 7d freq | Top-10 ads inside |
|---|---|---|---|---|---|---|---|
| THREE DEVICES | Sep 17 | $55,366 | 1.81 | $71.44 | $48.04 | 1.57 | CLD_1001 (96% of the ad set) |
| TOP PERFORMERS | Oct 9 | $29,828 | 1.81 | $75.90 | $303.14 | 1.14 | PETL60 V1, Sean_911 H4 (duplicates of PRODUCT FOCUS ads) |
| PRODUCT FOCUS | Jul 21 | $28,719 | 1.42 | $95.09 | $128.45 | 1.68 | Original PETL60 and Sean_911 copies (both paused) |
| BUNDLES DISCOUNTS | Jul 17 | $16,766 | 2.03 | $61.41 | $88.35 | 2.61 | CLD922 V2, CLD922 V1, AR717 V1 |
| PETL PLUS | Jul 27 | $9,451 | 2.16 | $62.18 | $138.74 | 1.48 | PETL61 V4 |
| Testimonial | May 2 | $7,922 | 1.36 | $88.02 | $78.05 | 2.27 | PETL84 V2, V3 |
| GIFTING | Jul 17 | $6,934 | 1.46 | $97.66 | $229.39 | 1.38 | AR717 V3 (paused) |

The small NSY campaigns sit outside it: NSY | RETARGETING | CBO ($591 this week, 2.71), NSY | POST PURCHASE | CBO ($386, 8.37, frequency 5.09, attribution 1-day view / 7-day click), NSY | CORPORATE GIFTING | CBO ($366, no tracked purchases). Insta Followers Traffic | ABO still runs five ad sets at $30 a day each, optimizing for profile visits.

What that means for iteration (inferred): the two most efficient ad sets this week, PETL PLUS (2.16) and BUNDLES DISCOUNTS (2.03), are the ones Meta is funding least. BUNDLES DISCOUNTS also carries the highest frequency (2.61), so its audience is the narrowest or the most repeated. Because the campaign budget is shared, a new ad dropped into THREE DEVICES will compete with CLD_1001 directly for that ad set's share.

## Data limits

- **Hook rate can't be computed.** The 3-second video plays field is not supported at ad level in this connection, and 2-second continuous plays came back null before (stated, monthly report). The video plays field that does return runs 92% to 96% of impressions on every video, so it's counting autoplay starts, not hooks. Thruplays per impression and average watch time are the usable hold signals and are in the tables.
- **Average watch time is in whole seconds** and rounds hard (PETL61 shows 6 to 7s on a 78s video).
- **CLD_1001 has one week of real delivery.** Its 14- and 30-day numbers are basically its 7-day numbers. There's no way to read its fatigue yet.
- **Attribution is Meta's "incrementality" setting** on the main campaign. These ROAS figures aren't directly comparable to a 7-day click / 1-day view read, or to Shopify. Meta has run roughly 0.3 to 0.4 under blended (stated, Charley, via monthly report).
- **30-day table stops at the top 35 ads** (lowest $1,994). Ads with $1,000 to $1,993 in that window aren't listed.
- **Format marked (i)** is inferred from video play counts, not from the creative pull. Only the top 10 plus a few others were pulled at creative level.
- **Two top-10 ads are paused** (AR717 V3, PETL84 V2). They rank on their 30-day record, not on current delivery.
- **Placement and demographic splits were pulled for CLD_1001 only**, last 7 days. They weren't pulled for the other nine.
- **Spoken hooks, on-screen text for videos and first frames weren't pulled.** The video titles in the account are all "One Charger. Three Devices.", so the asset names don't identify the concept. Only CLD_1001, CLD922 V2 and AR929 were viewed directly.
- **Concept mapping** relies on the naming rule (stated, digest). "May 1 | PETL 32 AR" and "NSY | SEAN 914" break the rule, so their origin is ambiguous.
- **Account-level 7-day totals weren't re-pulled.** The weekly account figures are in the monthly report.
