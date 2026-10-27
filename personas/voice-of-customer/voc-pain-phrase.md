---
brand: petl
doc: voc-pain-phrase
category: pain_phrase
generated_on: 2026-10-27
refresh_by: 2027-01-15
refresh_note: "VoC cadence ~180 days; set sooner because the survey predates the $64.95 price and a Q4 survey and full Judge.me export are the next pulls."
build: lean
personas_profile: personas/personas-profile.md
voc_corpus_profile: not built (lean build)
corpus_read:
  - "Post-purchase survey, 1,144 orders 2026-01-20 to 2026-03-26; 836 respondents; 778 free-text answers across Q2 (320), Q3 (236), Q4 (222). Source file: source-pulls/_exports/grace-claude-project-2026-10-27/PETL Project context Files.txt, section 'new survey responses & customer research' (export 2026-03-27)."
  - "Website reviews, 11 with text, 2026-01-08 to 2026-01-13, same file, 'Reviews from website'."
  - "Facebook ad comments, 28 customer comments, captured 2026-04-17, same file, 'FB Comments'."
  - "Judge.me PDP reviews, 5, 2026-10-26 to 2026-10-27, via research_notes/PETL brand and market research/petl_brand_and_reviews.md."
  - "Category reviews of competitor packs, via research_notes/PETL brand and market research/audience_and_market.md (contrast only)."
total_customer_records_read: 822
data_limitations:
  - "Survey answers are hopes and reasons at checkout, so most pain shows up indirectly, as the thing the buyer wants to stop. Few answers describe the before-state in full sentences."
  - "Only 19 of 1,454 Judge.me reviews read; no long reviews, no negative reviews. Before-state stories usually live in long reviews, so this pass is thin on scenes."
  - "No Reddit, TikTok, Instagram, support tickets, or interviews."
  - "No age or gender on any record; identity tags are inferred from content."
  - "Wrapped lines in the PDF export were rejoined with one space; otherwise verbatim."
  - "Ad-account copy was not pulled from Meta, so 'ad-account' source entries are drawn from the brand's winning-script files and flagged as brand echo, not customer language."
---

# VoC pain phrases — PETL

## How to read this

These are the buyer's own words for the problem before PETL. Each block is one distinct phrasing, copied exactly. Recurrence counts are against the 822 customer records read: 778 survey answers, 11 website reviews, 28 Facebook comments, and 5 Judge.me reviews. Cluster counts in the notes are my keyword classification read, not a structured field.

The shape of the pain in one line. PETL buyers describe a dull, daily problem, not a crisis: too many cords and chargers, bulky packs that are heavy to carry, a phone or Watch that won't last the day, and packs that let them down before. Wire, cord, and cable words appear in 44 of 778 survey answers. Dead or dying phone words appear in 4. The brand's panic framing, "1%," the dead phone at the gate, is mostly the brand's language. Those lines are logged at the bottom as brand echo.

Persona slugs come from `personas/personas-profile.md`: `no-fuss-family-keeper`, `apple-design-loyalist`, `team-provider`. Behavioral signal slugs come from the same doc.

## Pain phrases

### Cluster: too many cords and chargers

- snippet: "Simplicity. I travel constantly and hate all the wires. Hoping this will solve all that anxiety of carrying the right"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: travel-day
  source:
    type: post-purchase-survey
    platform: Shopify post-purchase survey, Q2
    review_id: "#GP7126"
    date: 2026-03-12
    url: null
  recurrence: 44
  source_diversity: [post-purchase-survey, ad-comment, review]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Recurrence 44 = survey answers using wire, cord, or cable words out of 778; the theme also appears in FB comments and January reviews. The answer is cut off in the source after 'the right'. Strongest single line because it names both 'hate' and 'anxiety', and the anxiety is about cords, not a dead phone."

- snippet: "Not having to deal with so many wires."
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: cable-clearout
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP4464", date: 2026-01-29, url: null}
  recurrence: 44
  source_diversity: [post-purchase-survey, ad-comment, review]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Same cluster as above; counted once for the cluster. Plain enough to lift as a hook line."

- snippet: "Freedom from Cords"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: cable-clearout
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP5207", date: 2026-02-12, url: null}
  recurrence: 44
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Half pain, half outcome. Kept here because the pain, cords, is the noun doing the work. The outcome pass may also claim it."

- snippet: "Reduce clutter and need for carrying around a clunky mobile charger with cords"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: cable-clearout
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP4289", date: 2026-01-25, url: null}
  recurrence: 44
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Names two pains in one breath: clutter and a clunky corded charger. 'Clutter' also appears in brand copy ('Cable-Free, Clutter-Free Charging', onboarding form 2026-01-12), so the word itself may be partly echo; the 'clunky mobile charger with cords' part is the customer's."

- snippet: "Convenience of having this in my bag for work and not have to lug a chord or wall plug."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP5352", date: 2026-02-15, url: null}
  recurrence: 44
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: mixed
  brand_self_echo: false
  notes: "'lug a chord or wall plug' is a vivid verb for the burden. 'chord' is the customer's spelling. Work-bag context, so possibly a working-age buyer; identity left null."

- snippet: "Having to bring less devices to charge stuff"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: travel-day
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP6866", date: 2026-03-08, url: null}
  recurrence: 44
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: mixed
  brand_self_echo: false
  notes: "The pain is the pile of chargers. Same buyer's Q4: 'Forgot my promo code'."

- snippet: "Less cables in tech bag"
  category: pain_phrase
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: travel-day
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP8041", date: 2026-03-22, url: null}
  recurrence: 6
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-20
  last_seen: 2026-03-22
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 6 = the 'less cables' or 'less cords' phrasing specifically: #GP8041, #GP7087 'Less cables', #GP5528 'Less cables', #GP6340 'Less cords', #GP6904 'Less hassle with charging' near paraphrase, #GP4123 'Good charging and no cables'. 'tech bag' hints at the Loyalist."

- snippet: "I have a few different power banks but these are still corded so I’m enjoying PETL."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: burned-by-another-pack
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Linda G.", date: 2026-02-20, url: null}
  recurrence: 1
  source_diversity: [ad-comment]
  first_seen: 2026-02-20
  last_seen: 2026-02-20
  confidence: thin
  brand_self_echo: false
  notes: "Date approximate: comment shown as 8w old in the 2026-04-17 capture. A buyer who owns several packs, all corded. Part of a longer positive comment."

### Cluster: bulky, heavy, brick on the phone

- snippet: "Comfort and the haul of a small and compact charger. No bulky feel!!!!"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP4684", date: 2026-02-01, url: null}
  recurrence: 9
  source_diversity: [post-purchase-survey, review]
  first_seen: 2026-01-13
  last_seen: 2026-03-15
  confidence: strong
  brand_self_echo: false
  notes: "Recurrence 9 = survey answers using bulk, bulky, heavy, clunky, brick, or cumbersome, out of 778, plus the January review below. Same buyer's Q4: 'Had to dig for comments and concerns.'"

- snippet: "Power to my phone without wires and/or bulky heavy feeling in using it"
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP5108", date: 2026-02-10, url: null}
  recurrence: 9
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-13
  last_seen: 2026-03-15
  confidence: strong
  brand_self_echo: false
  notes: "Joins the two biggest pains, wires and weight, in one line."

- snippet: "Not heavy like other power banks."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: burned-by-another-pack
  source: {type: review, platform: gopetl.com website review, Verified by Shop, review_id: null, date: 2026-01-13, url: null}
  recurrence: 9
  source_diversity: [review, post-purchase-survey]
  first_seen: 2026-01-13
  last_seen: 2026-03-15
  confidence: strong
  brand_self_echo: false
  notes: "From 'Perfect size. Not heavy like other power banks. Provided enough charge to get from 10-90%..while in use!' The pain is the contrast with other banks."

- snippet: "Light and less cumbersome than the current charger and love that I can charge my Apple Watch as well. Hope it works as good as its advertised."
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: burned-by-another-pack
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP4382", date: 2026-01-27, url: null}
  recurrence: 9
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-13
  last_seen: 2026-03-15
  confidence: mixed
  brand_self_echo: false
  notes: "The pain part is 'cumbersome' current charger. Full answer kept exact; the closing line belongs to the objection pass as guarded hope."

- snippet: "I’m hoping for a quality charger that is also not big and bulky. It’s difficult to find a good contact charger that charges my phone at a decent rate"
  category: pain_phrase
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: burned-by-another-pack
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP4942", date: 2026-02-07, url: null}
  recurrence: 9
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-13
  last_seen: 2026-03-15
  confidence: mixed
  brand_self_echo: false
  notes: "'It’s difficult to find' names a search that kept failing. Same buyer's Q4 is the 'damn chargers' price line in the objection doc, and they plan to buy 'several more for my kids and family' if it works."

- snippet: "Free up space in my purse"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP6878", date: 2026-03-09, url: null}
  recurrence: 8
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 8 = survey answers naming purse, bag, pocket, or clutch. The pain is a full purse. Same buyer's Q4: 'Already have another portable charger'."

### Cluster: the phone or Watch won't last the day

- snippet: "My phone be dead in the middle of the day"
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP4895", date: 2026-02-06, url: null}
  recurrence: 4
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-06
  last_seen: 2026-03-08
  confidence: thin
  brand_self_echo: false
  notes: "Recurrence 4 = dead, dies, or died words across all 778 answers. The one customer line in the corpus that matches the brand's dead-phone story. Spoken register, keep the grammar. Thin by count; do not let it carry the whole account's hook library."

- snippet: "Help my phone’s battery make it thru the day"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: aging-phone-battery
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP5663", date: 2026-02-21, url: null}
  recurrence: 22
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-26
  last_seen: 2026-03-19
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 22 of 320 Q2 hopes = more battery life, longer, lasting, extra charge, or 'make it thru the day' phrasings, a near paraphrase cluster; a few may mean the pack's own stamina rather than the phone's. Fits the PETL70 aging-battery idea. 'thru' is the customer's spelling."

- snippet: "Great charger on the go, no more dead batteries on my Apple Watch or iPhone"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP5110", date: 2026-02-10, url: null}
  recurrence: 4
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-06
  last_seen: 2026-03-08
  confidence: thin
  brand_self_echo: false
  notes: "Names the Apple Watch dying alongside the phone. The team states 'Apple Watch dying hooks have done well for older audiences' (02-audience doc). Same buyer's Q3: 'There are other brands of this same kind?' and Q4: 'The funds or lack there of'."

- snippet: "more battery time, especially in an emergency situation."
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP7702", date: 2026-03-18, url: null}
  recurrence: 13
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-21
  last_seen: 2026-03-22
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 13 = emergency, backup, security, worry, anxiety, or dead words in Q2 hopes. The fear is a future emergency, not a lived one."

- snippet: "Charging my devices on the go wherever I go without having to worry about finding an outlet."
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: travel-day
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP5729", date: 2026-02-22, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-22
  last_seen: 2026-02-22
  confidence: thin
  brand_self_echo: false
  notes: "The outlet hunt, said once by a customer and many times by the brand ('No hunting for outlets', winning ad scripts 2026-04-17). Same buyer's Q4: 'Nothing! I was going to purchase today because I put off long enough.'"

- snippet: "A viable charger for my wife’s Apple Watch when we travel!"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: gift-for-my-people
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP4104", date: 2026-01-21, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-21
  last_seen: 2026-01-21
  confidence: thin
  brand_self_echo: false
  notes: "'viable' implies earlier options were not. Same buyer, Q3: 'I tried another brand I found on Instagram but it didn’t work.' Q4: 'That prior failure…'. A husband buying for his wife's Watch; the keeper identity in a man."

### Cluster: other packs and chargers let me down

- snippet: "I have a different battery pack but it dies right away"
  category: pain_phrase
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: burned-by-another-pack
  source: {type: post-purchase-survey, platform: Shopify survey Q3, review_id: "#GP6875", date: 2026-03-08, url: null}
  recurrence: 5
  source_diversity: [post-purchase-survey, ad-comment]
  first_seen: 2026-01-21
  last_seen: 2026-03-19
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 5 = #GP6875, #GP7816, #GP4104, #GP7357 'I’ve tried a different brand and hopefully this will work more.', and FB Marie J. on heat. Out of 778 survey answers plus 28 comments. Small but the most charged language in the corpus."

- snippet: "I have other and they really don’t give me a full charge."
  category: pain_phrase
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: burned-by-another-pack
  source: {type: post-purchase-survey, platform: Shopify survey Q3, review_id: "#GP7816", date: 2026-03-19, url: null}
  recurrence: 5
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-21
  last_seen: 2026-03-19
  confidence: mixed
  brand_self_echo: false
  notes: "From 'Sounds like it will work. I have other and they really don’t give me a full charge. So let’s see on your product.' Claims governor: PETL original gives about 55% of an iPhone 16 Pro by MagSafe (stated, brand performance guide), so do not answer this pain with a full-charge promise on the original."

- snippet: "I tried another brand I found on Instagram but it didn’t work."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: burned-by-another-pack
  source: {type: post-purchase-survey, platform: Shopify survey Q3, review_id: "#GP4104", date: 2026-01-21, url: null}
  recurrence: 5
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-21
  last_seen: 2026-03-19
  confidence: mixed
  brand_self_echo: false
  notes: "Two pains: a product that failed and the feed it came from. This is the root of the trust objection in voc-objection."

- snippet: "I’d like to not use my charging case since the charging ports stink"
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: burned-by-another-pack
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP5106", date: 2026-02-10, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-10
  last_seen: 2026-02-10
  confidence: thin
  brand_self_echo: false
  notes: "Battery-case switcher. A switch-from state the account has not named."

- snippet: "I’ve used charger like this and it always heats my phone up."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: burned-by-another-pack
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Marie J.", date: 2026-04-10, url: null}
  recurrence: 3
  source_diversity: [ad-comment, post-purchase-survey]
  first_seen: 2026-03-01
  last_seen: 2026-04-14
  confidence: mixed
  brand_self_echo: false
  notes: "Date approximate, shown as 1w old in the 2026-04-17 capture. Lived pain from a prior product; the question that precedes it is an objection and is logged there. Recurrence 3 = heat mentions: this comment, FB Jennifer K. 'Does it heat up when it’s charging your phone?', survey #GP6223."

- snippet: "Been lookin at these damn chargers for a while but always hesitated at the price."
  category: pain_phrase
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4942", date: 2026-02-07, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-07
  last_seen: 2026-02-07
  confidence: thin
  brand_self_echo: false
  notes: "Mostly an objection, logged in full there. Kept here for 'damn chargers', the only frustrated swear in the corpus, which voices the fatigue of shopping a category of letdowns. Voice governor: off-voice as a brand line, usable as a quoted customer."

### Ease and age

- snippet: "Ease of use for an elderly woman"
  category: pain_phrase
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q2, review_id: "#GP7130", date: 2026-03-12, url: null}
  recurrence: 89
  source_diversity: [post-purchase-survey, review]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "The only answer that names the buyer's age. The pain beneath it, that tech is hard to use, is inferred. Recurrence 89 = Q2 hopes using ease, easy, easier, or convenience words out of 320; the January review 'Easy to use and easy to carry.' corroborates. Same buyer's Q4: 'Price'."

## Not customer language: brand echo log

These lines appear in the project files near customer quotes and in one case are listed as "Real customer language." They are the brand's own words. Do not use them as customer proof.

- snippet: "Tried to pull up my boarding pass at the gate and my phone was dead. I never want to go through that panic again."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: travel-day
  source: {type: ad-account, platform: "Winning ad scripts file, script 4", review_id: null, date: 2026-04-17, url: null}
  recurrence: 0
  source_diversity: [ad-account]
  first_seen: 2026-04-17
  last_seen: 2026-04-17
  confidence: thin
  brand_self_echo: true
  notes: "Script copy. No buyer in the corpus describes a gate moment. Kept as the brand's best panic line for contrast."

- snippet: "So no more rummaging through drawers looking for the right cable or having to pack a spare bag just for chargers."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: cable-clearout
  source: {type: ad-account, platform: "Winning ad scripts file, script 2", review_id: null, date: 2026-04-17, url: null}
  recurrence: 0
  source_diversity: [ad-account]
  first_seen: 2026-04-17
  last_seen: 2026-04-17
  confidence: thin
  brand_self_echo: true
  notes: "Listed as '65+ survey language' in petl-claude-code/docs/02-audience-and-customer-voice.md. It is a creator script line. The real customer version of this pain is 'Not having to deal with so many wires.' (#GP4464)."

- snippet: "Before PETL, my nightstand was a mess of cables and charging stands for my iPhone, Apple Watch, and AirPods."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: nightstand-routine
  source: {type: brand-reputation, platform: "gopetl.com 'Real life stories' testimonial, 'David L., Tech Professional'", review_id: null, date: 2026-01-14, url: null}
  recurrence: 0
  source_diversity: [brand-reputation]
  first_seen: 2026-01-14
  last_seen: 2026-01-14
  confidence: thin
  brand_self_echo: true
  notes: "Brand-curated testimonial on the website; same piece ends 'Pure minimalist genius.' Unverifiable as a real customer."

- snippet: "Never get caught at 1% again."
  category: pain_phrase
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: brand-reputation, platform: gopetl.com website copy, review_id: null, date: 2026-01-14, url: null}
  recurrence: 0
  source_diversity: [brand-reputation]
  first_seen: 2026-01-14
  last_seen: 2026-10-27
  confidence: thin
  brand_self_echo: true
  notes: "Site headline, still live per the 2026-10-27 research pass. Zero customer answers mention 1%."

## Relayed, not verbatim

- Rakesh relayed one customer's pain in Slack: "I was speaking to one of the 45 year old woman with two kids. She was saying her phone is always on low battery, because she hate to plug the phone and leave it away has she constantly needs her phone with her. At night time, she either forget to charge of she sleeps with the phone on her." (S-client, 2026-09-10, via internal-sources-digest.md). These are Rakesh's words describing her, so they are stated secondhand and cannot be quoted as hers. It is still the clearest before-state scene in the sources, and it became PETL93.

## Category contrast, competitor buyers

From audience_and_market.md, about other brands. Useful to see how category pain sounds when it is sharper. Not PETL customers.
- "It takes too long to charge, it doesn’t hold its charge" — Trustpilot, Oct 1 2026, about Clutch (verified by the research pass).
- "charges my phone very slowly and then dies before my phone even reaches 20%." — eBay, Apple MagSafe Battery Pack, undated, stated via search summary.
- "the negative side is the size and weight of this thing, relative to how little energy it stores" — eBay, Apple MagSafe Battery Pack, undated, stated via search summary.

## Open loops

1. **The before-state scenes are missing.** The corpus has short hopes, not stories. The long reviews that usually hold the "my phone died when..." moment were not read. *Pull: Gap — 1,435 Judge.me reviews sit unread and the survey only asks about hopes.* **Question:** What moments do PETL's long reviews describe from before the buyer owned one? *Justification:* Trigger-event hooks need real scenes, and right now the only scenes are the brand's own. Territory: messaging. Routes to the brand for a Judge.me export.

2. **Cords outrank dead phones.** Wire and cord pain shows up eleven times as often as dead-phone pain in buyer words, yet the account's proven hooks lean on rankings and dead batteries, and the "Cables" angle ran 1.37 ROAS in spring (stated, N-R3). *Pull: Tension.* **Question:** Why did the spring "Cables" angle underperform when cords are the pain buyers name most? *Justification:* If the execution was the problem rather than the pain, cord relief is an untapped lead message for the flagship persona. Territory: messaging.

3. **The switcher from other packs.** A small but intense group was burned by an Instagram brand, a dying pack, or a hot charger. *Pull: Resonance — the most charged lines in the corpus all come from people let down before.* **Question:** How many PETL buyers already owned another power bank before buying PETL? *Justification:* If it is most of them, "the one that finally works" is a bigger message than "you need a power bank." Territory: personas. Routes to the brand, as a survey question.
