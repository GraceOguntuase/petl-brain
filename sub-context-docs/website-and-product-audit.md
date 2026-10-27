---
brand: petl
doc: website-and-product-audit
generated_on: 2026-10-27
refresh_by: 2026-12-15
refresh_note: Semi-annual cadence would be 2027-04-25. Set much sooner because refresh triggers are firing now. Prices and the bundle ladder moved six times in 2026, a further tariff increase is confirmed with no date, three new PETL 2 Plus colors launch 2026-11-04, the Black Friday offer is not yet set, and a leather case is due about early December. Re-check the PDP before every batch regardless.
sources_read:
  - gopetl.com PETL PDP (petl-magsafe-battery-pack-black), live, read 2026-10-27
  - gopetl.com PETL 2 Plus PDP (space-black), live, read 2026-10-27
  - gopetl.com homepage, live, read 2026-10-27
  - gopetl.com refund policy, live, read 2026-10-27
  - gopetl.com About page, live, read 2026-10-27
  - gopetl.com products.json, captured 2026-10-27 in research notes (live re-fetch rate-limited, HTTP 429)
  - Brief PETL112 (Notion, 2026-10-06), the newest internal price source, via internal-sources-digest.md
  - source-pulls/internal-sources-digest.md (compiled 2026-10-27)
  - source-pulls/_exports/grace-claude-project-2026-10-27/petl-claude-code/docs/01-product-offer-and-claims.md and docs/04-writing-rules.md and CLAUDE.md (as of 2026-10-27)
  - PETL Project context Files.txt: Website Copy (2026-01-14), Onboarding form (2026-01-12), PETL APP INFO (2026-08-27), website reviews (Jan 2026)
  - source-pulls/research_notes/PETL brand and market research/petl_brand_and_reviews.md (2026-10-27)
  - source-pulls/external-research-2026-10.md (2026-10-27)
data_limitations:
  - Parker MCP not connected. No review export, no ad creative media, no account pull through Parker. Ad-level facts come from the Meta Ads MCP pull summarized in internal-sources-digest.md §6, and from Meta Ad Library reads in external-research-2026-10.md.
  - products.json could not be re-fetched live (HTTP 429). The catalog relies on the same-day capture in research notes.
  - No spec sheet, certificate, patent filing or test report for either model.
  - Low-star reviews, return reasons and repeat-purchase data were not reachable.
  - Margin, LTV and best-seller data come only from scattered Slack and call remarks, never a shared table.
---

# Website and product audit — PETL (goPETL)

**How to read this.** **Stated** = a source says it, not checked. **Verified** = observed directly on the live site on 2026-10-27, or in a dated data pull. For specs, verified means "the brand shows this," not that it's independently true. **Inferred** = Parker's read, with its basis. **Data-limited** = can't be resolved here. Newest source wins on duplicates; older values are marked superseded.

**The short version.** PETL sells one idea in two sizes: a small round aluminum battery that snaps onto an iPhone and also charges an Apple Watch and AirPods. The original is a top-up, not a full refill. The PETL 2 Plus is the bigger battery and, by the team's own September numbers, the bigger revenue line. Bundles do most of the pricing work, and the economics say a single unit loses money while two or more make it. The script layer depends on a long list of claims that the live site itself contradicts, so the claim-safety section near the end of this doc is the part to read before writing anything.

---

## Full SKU list and product lines

The store organizes itself as two battery packs plus accessories. The nav reads: Shop PETL, Shop All Products, Corporate Gifts, PETL PLUS, goPETL APP, Tech specs. *Verified — homepage, 2026-10-27.*

### Line 1: battery packs

| | PETL (original, "PETL 1") | PETL 2 Plus |
|---|---|---|
| Price, single | **$64.95** | **$89.95** |
| Capacity | 3,000mAh | 5,000mAh ("67% more capacity") |
| Max output / input | 10W / 10W | 15W / 15W ("50% more power") |
| Size and weight | 70mm wide, 14mm thin, 92g | 72mm wide, 16mm thin, 120g |
| Brand's "ideal for" | "Ideal for standard iPhone" | "Made for iPhone Pro & Pro Max" |
| iPhone 16 Pro charge, MagSafe / USB-C | **55%** / 77% | **92%** / 130% |
| AirPods charges, wireless / USB-C | 3.4x / 4.7x | 5.7x / 7.9x |
| Apple Watch charges, wireless / USB-C | 5.8x / 8.1x | 9.7x / 13.6x |
| Colors | Black, Natural, Lavender, Sky, Sahara Gold, Blush Gold, Sage | Slate, Cosmic Orange, Space Black. Burgundy, Glacier and Silver launch 2026-11-04 |
| Store listing dates | Black 2025-01-01; Natural 2025-05-23; Sky and Lavender 2025-12-25; Sahara Gold and Blush Gold 2026-04-15; Sage 2026-05-15 | Slate and Cosmic Orange 2026-04-15; Space Black 2026-07-02 |

*Verified — both PDP performance guides and homepage, 2026-10-27; listing dates verified in the products.json capture, 2026-10-27; Nov 4 colors stated in the PETL Analytics weekly brief for the week of 2026-10-26.* Prices match the newest internal source, the PETL112 brief of 2026-10-06. *Verified match.*

**Shared features, as the brand states them** (*stated — PDP, homepage, January Website Copy*): CNC aluminum unibody with a tempered glass top and "zero plastic"; N52 magnets that self-align; Qi wireless output; one USB-C port for input, output and passthrough; LED ring at 25/50/75/100%; a flat edge that stands the iPhone up for StandBy mode; shows in the native iOS battery widget with no app; thermal sensors and adaptive output; iPhone 12 and newer; splash-resistant, not waterproof; TSA and FAA carry-on compliant; recharges in about 1.5 to 2 hours on a 9V/2A adapter; a USB-C cable now comes in the new box, where the older box had none. Homepage wattage: "5W for AirPods, 2.5W for Apple Watch." *Verified, 2026-10-27.*

**Colors carry Plus-only and original-only splits.** Space Black is Plus-only. *Stated — docs/01.* Cosmic Orange shows on both in some places: the PETL112 brief lists it on the original, and the live PDP for the original carries a "PETL 2 Plus Cosmic Orange" heading over 3,000mAh specs and the $64.95 price. *Verified — PDP 2026-10-27; this is a page error, routed to the website team, not a loop.* Sage is live, but the client has wavered on it. *Stated — docs/01.*

**Per-market pricing.** EU store shows €56.95 / €74.95. Never convert. *Stated — docs/01.* Ads run US only.

### Line 2: accessories

| SKU | Price | Listed |
|---|---|---|
| PETL 2-in-1 Keychain Cable (USB-C and USB-A) | $19.90 | 2026-01-14 |
| PETL 4-in-1 Keychain Cable (USB-C, USB-A, Lightning) | $21.95 | 2026-06-25 |

*Verified — products.json capture, 2026-10-27.* Neither appears in any brief, ad or internal note read. *Verified absence in the digest.*

### Line 3: the goPETL app (free)

An iOS app showing live wattage, charging speed, time-to-full and charging history, with Live Activities on the Lock Screen and Dynamic Island. "No accounts, no ads, and no tracking." It reads only the PETL on that phone. *Stated — PETL APP INFO capture, 2026-08-27; App Store id6752920475.* It also claims to track "battery health," tuned by "PETL's in-house battery analytics engine." *Stated — same capture.*

### Line 4: corporate and B2B

"Corporate Gifts" in the nav. Live ad line "Swag They'll Actually Use" offers laser-engraved logos from 25 units. *Verified — Meta Ad Library via external research, 2026-10-27.* Rakesh gets "one or two corporate requests a day"; one 500-unit order shipped at $35 a unit. *Stated — Fathom 2026-07-15 and 2026-09-09.* Bulk orders of 10+ of the same product are excluded from returns. *Verified — refund policy.* Consumer creative may not show $35 pricing or custom logos. *Stated — docs/01.*

### Pipeline (stated, not committed unless noted)

Leather PETL case "probably by early December" and PDP engraving "probably two months away," both said by Rakesh on 2026-10-09. A docking station was planned for September 2026; status unknown. *Data-limited.* Ideas floated but not committed: mirror panel, suction-cup accessory, Find My tracking, a display on a future model. *Stated — internal digest §1.*

**What the line's shape says** (*inferred*): this is a very tight line, one product idea in two capacities, wrapped in colorways. In ten months the brand added a bigger battery aimed at Pro and Pro Max owners, eight new colors, two cables, a free app and a B2B channel, with a case and engraving coming. Every addition either widens who the same disc fits, raises the reason to own more than one, or makes it more giftable. The brand is building toward an accessory family and a gifting brand around one hero object, not toward more battery capacity. The brand blog says outright the small capacity is "by design."

## Top sellers and hero products

- **PETL 2 Plus leads revenue.** It was 71.9% of revenue and 64.9% of units account-wide from Sep 1 to Sep 10, 2026. *Stated — Charley, Slack 2026-09-11.* That's the newest product split on file.
- **The original is described as the volume seller** that people re-buy. *Stated — docs/04 §E, undated rule.* This conflicts with the September split above, where Plus took nearly two-thirds of units. Newest data favors Plus; the rule may predate the Plus launch in June. *Inferred.*
- **Black was the #1 original color** and sold out from mid-June to about July 6; the pre-order cut store conversion from about 7% to about 3%. *Stated — internal digest §1 and §3.*
- **Space Black buyers are 91% men** at 1.84x ROAS, strongest among men 45–54 at 4.1x. Cosmic Orange is 52% men. Multi-color ads convert at 1.80x with women 45–54 the strongest segment. *Stated — PETL Analytics weekly, week of 2026-10-26.*
- **What the ads push.** The top ads by spend over the last 90 days are product-agnostic three-device and ranking concepts (PETL65 "Top 3 Chargers for Grandparents," $209,170 at 1.65 ROAS; PETL48 "Top 5," $129,002 at 1.57). The one Plus-led ad at scale, PETL61 "Meet PETL Plus," spent $84,966 at 1.90. *Verified — Meta Ads MCP pull, 2026-10-27, via internal digest §6.* Which model each ad actually shows can't be confirmed from ad names. *Data-limited — creative read unavailable through Parker.*
- **Single-unit orders are about half of all orders, at about $96 AOV.** *Stated — Charley, Slack 2026-10-20.* A $96 single-unit AOV sits close to one PETL 2 Plus plus $9.99 shipping, $99.94. *Inferred — suggests single-unit buyers lean Plus.*

**Hero hypothesis** (*inferred*): the PETL 2 Plus is the revenue hero; the original is the price-entry and multi-unit gifting product. Rests on the September split, the $96 single AOV, and the Plus price. Needs the brand's current SKU-level sales to confirm. *Route to Rakesh.*

## Bundles and starter packs

The whole-order discount ladder auto-applies, colors can be mixed, and there are no compare-at prices on single units. *Verified — PDP and products.json capture, 2026-10-27.* Matches the PETL112 brief of 2026-10-06. *Verified match.*

| Tier and label | Discount | PETL each / total | PETL 2 Plus each / total | Shipping |
|---|---|---|---|---|
| 1, "Just one" | — | $64.95 | $89.95 | $9.99 both |
| 2+, "One for every bag" | 20% | $51.96 / $103.92 | $71.96 / $143.92 | PETL $9.99; **Plus free** |
| 3+, "Keep extras or share," MOST POPULAR | 25% | $48.72 / $146.16 | $67.47 / $202.41 | Free |
| 5+, "Stock up & save," BEST VALUE | 30% | $45.47 / $227.35 | $62.97 / $314.85 | Free |

*Verified — both PDPs, 2026-10-27.* Free US shipping starts at $129 cart value, standard 2–3 days; orders before 12 PM EST ship same day. *Verified.*

**The other offer mechanics on the live site** (*verified 2026-10-27*): an upsell modal, "Add a 2nd PETL and get 20% OFF on total," labeled "One-time offer · won't be shown again"; an email pop-up for WELCOME15 at 15% off; "4 interest-free payments"; no subscription. A post-purchase upsell on single-unit orders takes about 11%. *Stated — Fathom 2026-09-09.*

**What the bundles are doing** (*inferred*). The ladder is built to push a base PETL order to three units, because three is the first tier that clears $129 and ships free, which is why it's tagged MOST POPULAR. For Plus, two units already clear $129. The bundle names are all about more than one owner or more than one bag, so the bundle doubles as the gifting pack. There is no starter pack in the classic sense, because there's no decision to simplify: one product, two sizes, pick a color.

**Why the bundle matters to the business.** The single-unit tier lost $9,634 on 1,361 orders from Sep 1 to Sep 10, while two-pack and larger tiers ran 13.9% to 54.3% margin. *Stated — Charley, Slack 2026-09-11.* Buy 5+ lifted AOV from $60 to $68 back in May. *Stated — Fathom 2026-05-06, superseded prices.* Black Friday plan: lean on the 30% five-pack, test two weeks early, fall back to about 10% off if it fails. The client still owes the final offer. *Stated — Fathom 2026-09-25; Slack 2026-10-20.*

**Arithmetic lines that are true today** (*verified against the live ladder*): "Get 3 and they're under $50 each" ($48.72). "Under $70" for a single original. "Your third one costs $32," valid only as the step from two base units with $9.99 shipping, $113.91, to three with free shipping, $146.16, a $32.25 gap. "Up to 30% off."

## Product-level differentiators

Checked against what the product actually is, with the places where a strength flips into a weakness.

**1. The round shape and the size.** 70mm by 14mm and 92g for the original; 72mm by 16mm and 120g for Plus. *Verified spec as shown.* Category 10,000mAh packs weigh 218 to 230g. *Stated — ThirstyBear via external research.* The brand calls it "almost the size of a golf ball" in winning scripts. *Stated — docs/04.* Customers echo it: "Perfect size. Not heavy like other power banks." *Verified — website review, 2026-01-13.* **The flip:** circular on its own is not a problem anyone has. Grace called a whole concept on circular versus rectangular "a waste of creative." *Stated — docs/04 §A.* Shape is the reason it gets carried, not the reason to buy.

**2. Three Apple devices from one disc.** iPhone by MagSafe on the back; AirPods and Apple Watch sitting on top. *Stated — brand; Grace corrected an early error that said the Watch charges by cable.* Owners confirm it in their own words: "charges my phone, AirPods, and Apple Watch beautifully" *(stated, quoted in PETL Analytics weekly)*; "I like it, easy to charge my phone, waych and airbuds" *(verified — website review, 2026-01-13)*. **The flip:** the live site contradicts itself on how the Watch charges, wirelessly on "Qi-compatible models" in the FAQ, "via USB-C cable" in the spec block, and "2.5W for Apple Watch" on the homepage. *Verified — all live 2026-10-27.* Apple Watch doesn't use standard Qi. *Inferred from public knowledge of Apple's charger, not from a brand source.* One ad comment raised fit: "My Apple Watch uses a particular type of charger that has a slight dip in the center. If this has a flat surface, it won't work." *Stated — FB comments capture, ~Apr 2026.* And "at the same time" is not supported: the FAQ's "at the same time" answer is about passthrough, not three devices. Early-round notes said the three charge "one by one." *Stated — docs/01.* UGREEN and The Ridge now run nearly the same three-device promise. *Verified — Meta Ad Library, 2026-10-27, via external research.*

**3. Build and materials.** Aluminum and glass, "zero plastic." *Stated; physically checkable.* Survey verbatim on why they bought: "Product is not plastic." *Verified — survey export, Jan–Mar 2026.* "Feels like something Apple would make" is the approved creative framing. *Stated — docs/04.*

**4. Native iPhone fit.** Shows in the iOS battery widget with no app; StandBy edge; iPhone 12 and newer; fits the foldable iPhone Duo, tested in Round 8 and claimed in the PRWeb release. *Stated.* Works through a MagSafe case per owners: "Compact, charging through my case, elegant." *Verified — Plus PDP review, Marc Grobman, 2026-10-26.* "It also works well with MagSafe cases without any connection issues." *Verified — website review, 2026-01-10.*

**5. The 30-day trial.** Few category rivals advertise one; most lean on long warranties. *Inferred — external research.* No live PETL ad copy read mentions it. *Verified absence in copy, 2026-10-27.*

**6. Original versus Plus.** The original's edge is price and size; Plus's edge is near-full charge on a Pro phone. **The flip on the original:** it gives about 55% of an iPhone 16 Pro over MagSafe. *Verified — brand's own table.* That's a top-up. Any "full charge" line on the original is false by the brand's own numbers. On Plus, 92% by MagSafe on a 16 Pro is "nearly full," not "full." *Verified.*

**What isn't a differentiator** (*verified or stated*): capacity, where PETL is the smallest in a 10,000mAh market; speed, at 10W and 15W in a market moving to 25W Qi2; Qi2 itself, which the site never claims; warranty, at one year against Anker's 24 months and INIU's 3 years; price, in the top fifth of the category.

## Patents, proprietary materials, and manufacturing edges

| Claimed edge | What the brand says | Public record or proof | Read |
|---|---|---|---|
| Circular form patent | "Patent Pending" and "Patent-pending form" on PDP; "patented circular design" on homepage, both live 2026-10-27 | None shown; no filing number | Rests only on the brand's word, and the brand's word disagrees with itself. *Route to brand* |
| "World's first circular MagSafe" | Hero line, product titles | None | Brand assertion only |
| Circular internal layout | About page: factories wanted square; the team reworked battery geometry; round costs five times more | None | Stated. *Inferred:* if true, the cost and engineering effort is a real barrier for copycats, more durable than the patent claim |
| N52 "military-grade" magnets | PDP, About | None | Commodity part; "military-grade" is unsupported |
| goPETL app and "in-house battery analytics engine" | App page | App Store listing exists | Owned software, a real if small moat |
| Certifications | CE, FCC, RoHS, UL, WEEE | None linked | Not an edge until documents exist |

*Inferred:* nothing on file is proven proprietary. The most defensible thing PETL has may be the harder-to-make round battery plus the brand's head start on that shape, not a legal protection. *Route the patent question to Rakesh.*

## Known product issues

Visible here; the deep read belongs to the reviews doc. Weighed against a review base of 1,382 where only 21 sit at three stars or below, about 1.5%. *Verified — PDP widget, 2026-10-27.* That base is thin on complaints, but low-star texts were unreachable, so it may also hide them. *Data-limited.*

1. **Capacity on the original.** 55% of an iPhone 16 Pro by MagSafe. *Verified.* Owners raise it gently: "Yes.. it may only be 3000 ml amps, but the size and the design makesup for that." *Verified — website review 2026-01-08.* Even a happy Plus owner wishes for more: "though with the batteries of new devices a 10k would be great!" *Verified — Plus PDP review, 2026-10-26.* **Constrains claims: severe.** No "full charge" on the original, ever.
2. **Price.** The top objection: 80 of 216 survey answers to "what almost stopped you," and 47% in NSY's own coding, all from a period when the price was $49. *Verified count; stated coding.* Price is now $64.95. *Inferred:* the objection is larger now. Notion hypotheses from PETL96 on call price "now the main objection." *Stated.*
3. **Trust and "is this legit."** 19 of 216 survey answers. "Wasn't sure if this was going to be a legit product." "Skepticism about purchasing products on Facebook." *Verified — survey export.* The brand runs a blog post titled "PETL Reviews & Complaints: Is PETL Legit?" *Verified in search.* No earned press and zero Trustpilot reviews don't help. *Verified.*
4. **Heat.** The brand blog says it "gets warm during wireless charging." *Stated.* Ad commenters ask: "Will get heat my phone up?" *Stated — FB comments, ~Apr 2026.* One owner says the opposite: "it doesn't overheat during use." *Verified — website review 2026-01-10.* **Constrains claims: moderate.** No "stays cool."
5. **Apple Watch charging clarity.** The site contradicts itself three ways. *Verified.* **Constrains claims: high,** because every three-device ad rests on it.
6. **Case and model fit questions.** "Does it work when you have a case on your iPhone?" "I phone 11?" "Will this work with the iPhone 18 when it comes out" plus Android questions. *Stated — FB comments.* iPhone 12 and newer only.
7. **Return friction.** "No questions asked" on the PDP versus a $5 return fee, no refund of original shipping, unused and resaleable condition, and full bundles back. *Verified — refund policy 2026-10-27.* The brand blog names the return process as a shopper concern. *Stated.*
8. **Stock-outs.** Black sold out mid-June to about July 6 and conversion fell from about 7% to about 3% on pre-order. *Stated — internal digest.* "Sold out 7 times" is sold as a proof point but was also a lost-sales problem. *Inferred.*
9. **Checkout friction in survey answers.** "Payment link didn't work." "Not seeing the SHOP option initially." PayPal not accepted per an ad comment. *Verified survey text; comment stated.*
10. **Spec tables that disagree on the live PDP.** Quick Specs lists the original at 9.7x Apple Watch by USB-C and 92% iPhone by USB-C; the performance guide says 8.1x and 77%. *Verified 2026-10-27.* Website team fix, but it means scripts must quote the performance guide only.

## LTV expansion and the upsell cycle

**The base fact:** both packs are durable, one-time purchases. There is no subscription and no consumable. *Verified absence.* Every repeat path is "buy another," not "buy again."

Expansion vectors, each marked:
- **Second unit or second color.** "70% buyers re-order in a second color." *Stated, unverified method.* Owners describe it: "one for the nightstand and one on the go." *Stated — PETL Analytics weekly quote.* The upsell modal and 2+ tier are built for this. *Verified.*
- **Gifting multiples.** Bundle labels "One for the whole family" and "The Perfect Present"; a doctor bought 4+ for his team. *Verified labels; story stated.*
- **Original to Plus upgrade.** Plus is framed as "The PETL you love, upgraded" with a rule to never make the original look weak. *Stated — PETL124 and Ideas Library.*
- **Color drops.** Ten colors now, three more on 2026-11-04. Space Black skewed 91% men, suggesting new colors open new buyers, not just repeat ones. *Inferred from PETL Analytics weekly.*
- **Accessories.** Keychain cables at $19.90 and $21.95 now; leather case and engraving coming. *Verified and stated.*
- **Corporate.** Orders from 25 to 500 units. *Stated.*
- **Email.** About 17% of revenue, up from 12% in early September. *Stated — Charley, Slack 2026-10-20.*

**Where it likely stalls** (*hypothesis*): after the second unit. A household that owns one for the bag and one for the nightstand has little reason to buy a third except as a gift or a new color. Repeat rate by tier has never been shared. *Data-limited — route to Rakesh.* COGS: Plus "almost $20"; the original "is cheap." *Stated — Rakesh, Fathom 2026-10-09.*

## Use-case and need-state mapping

The product's intended uses, drawn from the brand's own site and framing. This is not a claim about who buys. The join to real personas happens in the persona work.

| Use case or need-state, as the brand frames it | Original | Plus | Brand source |
|---|---|---|---|
| Daily top-up carried in a pocket, clutch or small bag | Primary | Yes | "One little charger. A lot less to carry."; coin-pocket origin story |
| Heavy phone use on a Pro or Pro Max | Weak fit | Primary | "Made for iPhone Pro & Pro Max" |
| Charging iPhone, Watch and AirPods with one device | Yes | Yes | "Replace 3 chargers with 1 PETL." |
| Travel and the airport gate | Yes | Yes | "Airplane safe"; "The only charger in my travel bag" |
| Nightstand and StandBy mode | Yes | Yes | "Transforms your Nightstand experience." |
| Clean desk | Yes | Yes | "A Cleaner Desk Setup. No cables. No stands." |
| Long days: navigation, rides, messaging | Top-up | Better fit | PDP "up to 4 hours of navigation" etc. |
| New iPhone or foldable iPhone Duo | Yes | Primary per PR | PRWeb "full extra charge for your iPhone Duo" |
| A gift, or one per family member | Primary through bundles | Yes | "The Perfect Present / One for the whole family" |
| Team or client swag | Yes | Yes | "Swag They'll Actually Use" |

*Inferred:* one customer can move through the whole line over time. A buyer starts with one disc for the bag, adds a second for the nightstand, gifts a 3-pack, then upgrades to Plus on a new Pro phone. That sequence is the line's quiet strength. Which real persona each product converts is an open question for the persona work.

## Entry-point product hypothesis

**Hypothesis** (*inferred*): there are two entry points, split by who is buying.

- **Self-buyer:** a single unit. The easiest first yes is "under $70" for one original, and the single-unit AOV of about $96 suggests many self-buyers pick a single Plus. *Rests on Charley's 2026-10-20 AOV and the Sep 1–10 Plus split.*
- **Gift buyer:** the 3-pack of the original. Under $50 each, free shipping, tagged MOST POPULAR, named for sharing. *Rests on the ladder design and the bundle labels.*

**The tension, not resolved here:** the easiest first yes, one unit, is the tier that lost $9,634 on 1,361 orders in early September, while multi-unit tiers carry 13.9% to 54.3% margin. So acquisition creative that wins the single-unit click may be buying unprofitable first orders, unless the post-purchase upsell, about 11%, and email, about 17% of revenue, recover them. *Stated figures; inference on the tension.* The question of what the acquisition funnel should lead with belongs to the product-priority work. *Route margin by tier to Rakesh.*

## Claims safe to use in scripts, and claims to avoid or verify

This is the working list scripts should be checked against. It's built from the live site on 2026-10-27, the PETL112 brief of 2026-10-06, the client's onboarding rules, and Grace's rule set in docs/01 and docs/04. **Rule zero still holds: re-check the live PDP before every batch.** Prices moved six times this year and a tariff-driven increase is confirmed with no date. *Stated — docs/01.*

### Safe to use as written

| Claim, script wording | Basis |
|---|---|
| "$64.95" for PETL, "$89.95" for PETL 2 Plus; single anchor "under $70" | Verified live 2026-10-27; matches PETL112 |
| "Up to 30% off" / "Buy 2 get 20% off, 3 get 25%, 5 get 30%" off the whole order | Verified live |
| "Get 3 and they're under $50 each" | Verified, $48.72 |
| "Free shipping on orders over $129" / "Buy three and the shipping's free" for the original / "Two PETL 2 Plus ship free" | Verified live |
| "Try it risk-free for 30 days" | Verified PDP; confirmed by Grace 2026-09-25 |
| "1-year warranty" with no scope promise | Verified |
| "Charges your iPhone, Apple Watch and AirPods" | Brand-stated; owner reviews confirm |
| "Snap it on" / magnetic / self-aligning / no cables for the iPhone | Brand-stated; core demo |
| "About another ten hours of talk time" for the original, with the footnote "based on internal testing with iPhone 16" on screen | Brand-stated with disclaimer |
| "Works with iPhone 12 and newer" | Brand-stated |
| "Aluminum and glass, no plastic" / "feels like something Apple would make" | Brand-stated build; approved framing |
| "Stands your iPhone up for StandBy on the nightstand" | Brand-stated feature |
| "Shows in your iPhone battery widget, no app needed" plus a short "there's a free app too" line | Brand-stated; app line per Grace's rule |
| "MagSafe-compatible" | Client-approved wording |
| "Almost the size of a golf ball" / "smaller than your palm" / "fits in your coin pocket" | Approved in docs/04; matches 70mm spec |
| "4.8 stars from over 1,400 reviews" | Verified on-site widget, 1,454 shop-wide at 4.8. Replaces the stale "1,191 reviews" in older overlays |
| "Sold out 7 times" as a brand-level line only | Live on PDP; client-endorsed; never per color |
| Naming Anker, Belkin, Mophie, Apple as comparisons, conceding Anker's capacity | Client-approved per PETL48; logos blurred or text only |
| "Not on Amazon, only at gopetl.com" | Stated by Rakesh; verified no official listing |

### Safe only with exact wording

| Claim | Say | Don't say | Why |
|---|---|---|---|
| Plus battery | "Nearly a full charge on an iPhone 16 Pro" | "A full extra charge" or "full charge" | Brand's own table shows 92% by MagSafe |
| Original battery | "A top-up that gets you through the day" | "Full charge," "charges to 100%," "charges up to 10 hours" | Brand's own table shows 55% on a 16 Pro by MagSafe; 10 hours is talk time |
| Watch and AirPods charging | "Set your Apple Watch or AirPods on top" | "All at the same time," "every Apple Watch," "via cable" | Live site contradicts itself on the Watch; "at the same time" is unsupported. Verify with Rakesh |
| "World's first circular MagSafe-compatible power bank" | Use only as the brand's own line, never as a stated fact in a creator's mouth with added proof | "Patented," "the only one ever made" | No evidence on file; client uses it heavily, so it's Rakesh's call |
| Patent | "Patent-pending," and only once Rakesh confirms a filing | "Patented" | Live homepage says both |
| Cases | "Works through most MagSafe cases" | "Works with any case" | Owners confirm MagSafe cases; thick or non-MagSafe cases unverified |
| Shipping speed | "Ships same day if you order before noon Eastern" | "Free FedEx 2Day," "free express shipping" | Site says standard 2–3 days and $9.99 under $129; live ads say FedEx 2Day |
| Travel | "Airplane-safe, fine in your carry-on" | "Use it in-flight" | Southwest and ICAO now limit in-flight use and count |
| Third-unit price | "Your third one costs $32," original only, two to three units | Using it for Plus | Arithmetic only holds on base with shipping |
| Gifting | Evergreen: "a birthday or holiday coming up" | Dated holidays unless the round is seasonal; "Pre-Black Friday" without Rakesh's sign-off | docs/04; PETL112 |
| Heat | "Built-in thermal sensors" | "Stays cool," "never gets hot" | Brand blog admits warmth |

### Avoid or verify before use

| Claim | Status | Source and date |
|---|---|---|
| "Apple-approved," "Apple-certified," "Made for Apple," "Official Apple accessory," Apple logos | **Banned** by client | Onboarding form, 2026-01-12 |
| "Made for iPhone" in any form | **Avoid.** The homepage says "Made for iPhone Pro & Pro Max," but "Made for iPhone" is Apple's licensing badge and sits next to the banned list. Flag to Rakesh | Homepage live 2026-10-27; inferred |
| "MagSafe®" as a product noun, "the MagSafe battery pack" | Avoid; say "MagSafe-compatible" | Internal digest §4 |
| "Qi2 certified," "certified Qi," "certified for next-gen Qi" | Avoid. Site never claims Qi2; "certified Qi" has no backing | docs/01; PDP live |
| "100,000+ customers" | **Hold.** Contradicts "65,000+ units sold" on the PDP and the founder's "more than 80,000 units in our first year" | Homepage live; PRWeb 2026-09-14 |
| "80,000+ customers" (in older overlays) | Superseded and unsupported; the founder figure is units shipped, not customers | docs/04 overlay; PRWeb |
| "80,000+ units shipped" | Usable only attributed and dated: "over 80,000 sold in our first year" | PRWeb 2026-09-14 |
| "1,191 reviews," "4.81 on 1,167" | Stale. Use the live count | docs/01, superseded |
| "No questions asked," "free returns," "full refund," "30-day full refund" | **Avoid.** Policy deducts $5, keeps original shipping, needs unused condition and full bundles. Batch 7 briefs PETL111, 118, 119, 122, 124, 126 and 127 close on "30-day full refund" and need a check | Refund policy live 2026-10-27; internal digest §1 |
| "Up to 15 extra hours" for Plus | Verify. Not on the live Plus PDP read today, which shows "10+ Extra hours" | PETL124 brief vs PDP 2026-10-27 |
| "+17 hours" | Wrong | docs/01 |
| PETL15, "15% off," "$49," single "under $50," "half the price of Apple's" | Dead. A live ad still runs a PETL15 "today only" code as of 2026-10-12; escalate to Charley or Rakesh | docs/01; Meta Ad Library via external research |
| WELCOME15 | Live on the site pop-up but never approved for creative. Don't stack with bundles | Homepage live |
| "Free shipping on 2+" for the original | Wrong. Still in live PETL65, PETL45 and PETL53 per older flags | docs/01 |
| "CE, FCC, RoHS, UL certified" as a lead or safety-led claim | Verify documents first, especially UL, given the 2025 Anker recalls | Brand-stated only |
| "Military-grade magnets," "strongest magnets in consumer tech" | Avoid; unsupported | PDP, About |
| "Sustainably sourced aluminum," eco claims | Avoid; unsupported, and sustainability converts late | January Website Copy |
| "Improves your battery health," charging-time claims like "full in under an hour" | Avoid | docs/01 |
| "70% re-order in a second color" | Stated, method unknown; Grace rejected it as a headline | PDP; docs/01 |
| "Black sold out 7 times," "restock sold out in 7 minutes," "REMAINING: 171/1000" | Avoid unless proven true at launch | docs/01; PETL108 |
| Price-rise deadlines or dates | Avoid until Rakesh confirms in writing. "Prices are going up because of tariffs" is fine without a date | docs/01 |
| Remote battery monitoring through the app | Never. The app reads only the PETL on that phone | docs/01 |
| Android or Samsung compatibility | Avoid; unconfirmed | External research |
| Fit on a specific new phone model | Name only models the brand has tested. iPhone Duo is tested per Round 8 | docs/01 |
| Corporate $35 pricing, custom logos in consumer ads | Avoid | docs/01 |
| Fabricated comments, reviews or branded AI screenshots | Never in final production | docs/04 §H |
| "Expert Tech Reviewer" quotes as independent press | Avoid. CJ and Claire are PETL's own creators | PDP; internal digest |

## Open loops

**1. Which product should the acquisition funnel actually lead with?**
Observation: Plus took 71.9% of revenue and 64.9% of units in early September, single-unit orders lose money while multi-unit tiers make 13.9% to 54.3% margin, and the top-spending ads are product-agnostic three-device and ranking concepts. A standing writing rule still calls the original the volume seller.
Pull: **Tension.** The newest sales split, the margin data and a standing creative rule point to three different leads.
Question: Which first purchase, by model and by unit count, earns PETL the most money over a customer's first ninety days?
Justification: the answer decides whether acquisition creative should sell one original under $70, one Plus, or a multi-unit gift pack, and it changes the offer, the hook and the persona in almost every brief.
Territory: Product. *Brand-only — route to Rakesh for margin and repeat by tier.*

**2. The three-device promise rests on a Watch claim the site can't settle.**
Observation: the live site says the Apple Watch charges wirelessly on "Qi-compatible models," and also "via USB-C cable," and also "2.5W" from the top. The three-device ad set runs at 2.29x on 9.8% of spend and is called "winner starved," and two rivals now run the same promise.
Pull: **Tension.** The best-converting angle in the account depends on a product claim the brand describes three ways.
Question: How does the Apple Watch actually charge on PETL, and on which Watch models does it work?
Justification: if the Watch charges reliably by sitting on top, the three-device demo is a moat worth scaling; if it needs a cable or only works on some models, the lead angle needs new wording before more spend goes behind it.
Territory: Product. *Brand-only.*

**3. The trial is the strongest unspent card, and the fine print may blunt it.**
Observation: few rivals advertise a trial, no live PETL ad copy mentions it, Batch 7 briefs close on "30-day full refund," and the policy deducts $5 and keeps original shipping.
Pull: **Gap.** A real risk reversal at a premium price sits on the PDP but almost nowhere in the ads, and the wording the briefs use overstates it.
Question: What share of buyers ever return a PETL, and what do they say when they do?
Justification: a low return rate would let the brand push the trial much harder and maybe soften the fine print; a high one would show where the product disappoints.
Territory: Product. *Brand-only.*

**4. The line keeps adding colors, and colors seem to bring new buyers.**
Observation: Space Black purchases run 91% men while multi-color ads lean to women 45–54, and three more Plus colors launch Nov 4.
Pull: **Surprise.** A finish, not a feature, appears to change who buys.
Question: How much of PETL's new-customer growth comes from color launches compared with the product itself?
Justification: if colors pull in new buyers, launches become an acquisition lever with their own creative and timing; if they mostly drive repeat, they belong in email and retention.
Territory: Product.

## Appendix - Parker media links

No Parker media links were available in this run. Parker MCP was not connected. Source URLs and references used:

**Product pages (read live 2026-10-27)**
- https://gopetl.com/products/petl-magsafe-battery-pack-black
- https://gopetl.com/products/petl-2-plus-magsafe-compatible-battery-pack-space-black
- https://gopetl.com
- https://gopetl.com/policies/refund-policy
- https://gopetl.com/pages/about-petl-magsafe-battery-pack
- https://gopetl.com/products.json (captured in research notes 2026-10-27)

**Brand blog and press (via external-research-2026-10.md)**
- https://gopetl.com/blogs/petl-magsafe-battery-pack-news/introducing-petl-the-world-s-first-circular-magsafe-battery-pack
- https://gopetl.com/blogs/petl-magsafe-battery-pack-news/petl-reviews-complaints-honest-answers
- https://www.prweb.com/releases/petl-introduces-petl-2-plus-a-full-extra-charge-for-your-iphone-duo-in-a-5-000mah-magsafe-battery-302876149.html

**App**
- https://apps.apple.com/us/app/gopetl/id6752920475

**Live PETL ads (Meta Ad Library, via external research 2026-10-27)**
- PETL page library: https://www.facebook.com/ads/library/?active_status=active&ad_type=all&country=US&view_all_page_id=518140051386660
- Top-impression three-band static, since 2026-10-08: https://www.facebook.com/ads/library/?id=2166469290894491
- Longest-running high-impression video, since 2026-08-14: https://www.facebook.com/ads/library/?id=1574551524043871
- Other live frames: https://www.facebook.com/ads/library/?id=28235981292751551 and https://www.facebook.com/ads/library/?id=3817761678385315

**Category references used for comparison (via external research)**
- https://www.amazon.com/dp/B0GGLNVRQK
- https://www.bestbuy.com/product/energizer-10000mah-slim-metal-20w-magnetic-wireless-qi-qi2-0-magsafe-powerbank-portable-charger-2-outputs-led-display-usb-c-black/J36C4YX4LL
- https://www.thirstybear.com/best-magsafe-battery-packs/
- https://www.macrumors.com/2026/05/27/iphone-air-magsafe-battery-59

**Internal (Notion, from source-pulls/source-index.md)**
- Brief PETL112 – Minimal Price, 2026-10-06: https://app.notion.com/p/3f1df9f700e58131a688fa662ccc14e8
- Brief PETL68, 2026-09-10: https://app.notion.com/p/0eddf9f700e5833185ed818c4a6914da
- Brief PETL124: https://app.notion.com/p/3f4df9f700e581acb2b2f8f10c02074c
- Onboarding Response: https://app.notion.com/p/2e6df9f700e5806d98f7f35ce66ef16b
- Meta ad account 3803347073290974 pull summarized in source-pulls/internal-sources-digest.md §6

**Local files**
- source-pulls/internal-sources-digest.md
- source-pulls/external-research-2026-10.md
- source-pulls/research_notes/PETL brand and market research/petl_brand_and_reviews.md
- source-pulls/_exports/grace-claude-project-2026-10-27/petl-claude-code/docs/01-product-offer-and-claims.md
- source-pulls/_exports/grace-claude-project-2026-10-27/petl-claude-code/docs/04-writing-rules.md
- source-pulls/_exports/grace-claude-project-2026-10-27/PETL Project context Files.txt
