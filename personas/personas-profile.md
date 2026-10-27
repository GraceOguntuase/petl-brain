---
brand: petl
generated_on: 2026-10-27
refresh_by: 2027-01-15
refresh_note: "Cadence for personas is ~180 days, set sooner because two refresh triggers have already fired: the survey corpus predates the price move to $64.95 (Aug 2026), and Q4 gifting season will reshape the behavioral signals. Re-run after BFCM with a fresh post-purchase survey export."
build: lean
sources_synced:
  - customer-reviews: 2026-01-14 (website review export, 14 entries, Jan 8-13 2026) and 2026-10-27 (5 Judge.me reviews shown on PDP, Oct 26-27 2026, via research note)
  - ad-account: 2026-10-27 (Meta Ads MCP, account 3803347073290974, last_90d age x gender pull, live, read-only; plus META top-30 ads table in internal-sources-digest.md)
  - ad-comments: 2026-04-17 (Grace's "FB Comments" capture from top videos, 28 customer comments)
  - post-purchase-surveys: 2026-03-27 (Shopify survey export, 1,144 orders 2026-01-20 to 2026-03-26; 836 with any answer)
  - brand-reputation: 2026-10-27 (research note petl_brand_and_reviews.md: Judge.me 1,454 reviews at 4.83, Trustpilot 0 reviews, brand complaints blog)
  - reddit: unavailable (blocked to research tools on 2026-10-27)
  - other-reviews: 2026-10-27 (competitor and category reviews in audience_and_market.md; no PETL reviews exist off-site)
  - voc-corpus-profile: not built (lean build)
persona_count: 3
flagship_persona: no-fuss-family-keeper
companion_docs:
  - persona-voice-library: personas/persona-voice-library.md
  - voc-pain-phrase: personas/voice-of-customer/voc-pain-phrase.md
  - voc-objection: personas/voice-of-customer/voc-objection.md
  - lifecycle-journey-maps: not built (lean build)
data_limitations:
  - "Parker MCP not connected. No full review corpus: only 14 Jan-2026 website reviews and 5 Oct-2026 Judge.me reviews were read out of 1,454. The 21 one-to-three-star reviews were never read."
  - "The post-purchase survey has no age, gender, or recipient field. Linking survey language to the older buyer is inferred, not verified."
  - "Survey window is Jan 20 to Mar 26 2026, when the single unit was $49. The price is now $64.95. Price and value reads from it are dated."
  - "Meta age and gender is the age of the account that clicked and bought, not the person who uses the PETL. A gift buyer and a self buyer look the same."
  - "Creative read unavailable. No ad media, transcripts, or primary text were pulled. Served-audience claims rest on Notion brief descriptions (who was cast, what the script says) and Meta spend, not on watching the ads."
  - "Reddit, TikTok comments, Instagram comments, and Facebook page comments beyond the 28 in Grace's capture were not available."
  - "Survey keyword coding is my own classification read with overlapping regex buckets, not a field the customer filled in."
---

# Personas — PETL (goPETL)

## How to read this doc

This is who actually buys PETL, built from the sources listed above. Three personas: one flagship, one secondary, one emerging. Each persona is a durable identity, the kind of person someone still is in five years. The situations that come and go, like a trip, a holiday gift hunt, or a new iPhone, are kept separate as behavioral signals that sit on top of the identity.

Every claim is marked. **Verified** means I saw it directly in a data pull or source file. **Stated** means a source says it and I did not check it. **Inferred** means it is my reasoning, and I say what it rests on. **Data-limited** means the sources cannot settle it. Ages are verified only at the account level from Meta. Any age or trait attached to a single customer quote is inferred.

Exact customer language lives in the companion docs. This doc names the voice and points there. Slugs defined here are the canonical names the companion docs reuse.

The research trail in one paragraph. I parsed the full post-purchase survey export into 1,144 order rows. 836 answered at least one question: 836 answered where they heard about PETL, 320 answered what they hoped to get, 236 answered why PETL over another brand, and 222 answered what almost stopped them. I read every one of those 778 free-text answers. I read the 28 customer comments in Grace's April Facebook capture, the 14 website reviews from January, and the 5 recent Judge.me reviews the research pass copied off the PDP. I pulled a live Meta age by gender breakdown for the last 90 days, about 2026-07-29 to 2026-10-26: $1,644,395 in spend and 23,841 purchases with a known age. I read the team's stated audience notes in the digest and the Claude-project audience doc, the onboarding form, four bi-weekly call transcripts, and the market research notes. Then I matched who the ads serve against who buys.

## Cross-persona bias notes

**The brand's picture of its customer is not the customer.** The onboarding form describes PETL buyers as "design-conscious, convenience-driven consumers who value simplicity, minimalism, and thoughtful functionality ... They gravitate toward premium, understated brands" (stated, N-OB onboarding form, 2026-01-12). The January Gemini analysis of the top two ads read them as aimed at "the design-conscious, tech-savvy male" with "tattoos, rings, minimalist desk setup" and "the organized, aesthetic-driven, on-the-go female" (stated, Gemini analysis file, 2026-01-14). The Dojo playbook calls PETL "a younger tech audience" (stated, via 02-audience doc, Oct 2026). The external market research proposed "Apple-ecosystem stylist" as the core segment and guessed the demographic core as "US iPhone owners from teens to 40s+" (inferred by that research pass, audience_and_market.md, 2026-10-27). The live account says something else. In the last 90 days, 75.9% of purchases with a known age came from people 55 and older, 92.5% from people 45 and older, and 1.5% from people under 35 (verified, Meta pull 2026-10-27, 18,097 of 23,841 purchases are 55+). This is the central collision of the whole persona read, and it sits on top of everything below.

**A second assumption also does not hold up: the young gift-giver buying up for grandparents.** The team's working story includes adult children and grandkids buying PETL for parents and grandparents. PETL73 "Best Gift for Grandparents" was built for "Adult Children & Grandchildren Buying Gifts (25-45)" (stated, N-MCD PETL73). People 25 to 44 made 1,758 of 23,841 purchases in the last 90 days, 7.4% (verified, Meta pull). PETL73 ran $10,146 at a $89.00 CPA against a $69.15 account CPA (verified, META table in digest). The biggest spender in the account, PETL65 "Top 3 Chargers for Grandparents," was cast with a senior woman talking peer to peer to other grandparents about their own charging (stated, N-MCD PETL65 brief), and it took $209,170 at 2,954 purchases (verified, META). The read that fits all of this: the grandparent is mostly buying for herself and her own household, not being bought for (inferred from the age split, the PETL65 vs PETL73 gap, and the brief casting; the survey has no recipient field, so this is not verified).

**Delivery follows casting, so the age skew is partly self-made.** The team states Meta "delivery skews female when female creators are in the ad — male when male creators are in the ad" (stated, N-R3, 2026-04-22). The account has spent heavily on senior creators since August. So part of the 55+ skew is the algorithm finding who the creative courts. It is not all echo, though. The survey window ran January to March, before the senior casting scaled, and the team already stated in April that the "highest-converting demo is 45-65 with disposable income" (stated, N-R3). When the account does reach younger people it buys poorly: 25 to 34 women converted at a $98.96 CPA and 1.13 ROAS, men 25 to 34 at $97.16 and 1.26 ROAS (verified, Meta pull, but on only 1.9% of spend, so thin). Rakesh's own read: "I just found from ads, it's just older demographics work better" (stated, F-2026-10-09).

**Brand self-echo in the "customer language" files.** Several lines the Claude-project audience doc lists as "Real customer language" are not customer language. "Pure minimalist genius" is the website's own "Real life stories" testimonial credited to "David L., Tech Professional" (verified, Website Copy section of the project export). "It's a lifesaver," "It lives in my bag," and "no more rummaging through drawers looking for the right cable" are lines from the brand's winning ad scripts (verified, Winning ad scripts file, 2026-04-17). The homepage testimonial headlines "Low Battery Anxiety—Solved." and "PETL charges all my Apple devices" are credited to Claire and CJ, who are paid creators billed as tech experts (stated, petl_brand_and_reviews.md). None of these count as customer evidence in this doc.

**The panic the ads sell is not the problem buyers name.** The brand copy leans on the dead phone: "Never get caught at 1% again," boarding-pass panic scripts, "Low Battery Anxiety" (verified, Website Copy and Winning ad scripts files). In 778 survey answers, words for a dead or dying phone appear 4 times. Words for wires, cords, and cables appear 44 times. Convenience and ease words appear in 89 of 320 "hoping to get" answers (classification read, my keyword coding). The team's own "Low Battery Anxiety" angle ran 1.29 ROAS and was judged to have stakes that "felt too vague" (stated, N-R3). Here the gap between what is said and what drives the buy sits on the brand side, not the customer side.

**Vocal minority risk.** The Facebook comments are loud about cases, heat, and Android. Four of 28 comments ask whether PETL works through a phone case. In the survey only 1 of 222 objection answers mentions a case. The comment section is a pre-purchase question box, mostly from people who did not buy yet, so it over-represents doubts relative to buyers (inferred).

**Sources that disagree.** On capacity, a few buyers flag "3000 mHa seemed a little low" while the January reviews call the size worth the trade (see the objection doc). On the man versus woman split, the account is 65.5% female by purchases (verified), but Space Black PETL 2 Plus purchases "run 91% men" (stated, PA-weekly, week of 2026-10-26). Both are true. They describe different personas, which is part of why there are two.

## Served-versus-actual diagnosis

**Served audience.** Creative read unavailable, so this rests on brief descriptions and spend. The top of the 90-day spend table is the "Top 3 Chargers for Grandparents" ranking idea, NSY's PETL65 plus the in-house Sean_911 reshoot, at about $405K of $1.66M, roughly 24% (verified spend, META). PETL65 was briefed as a senior woman ranking chargers for grandparents (stated, N-MCD). Next is PETL48 "Top 5 MagSafe Power Banks Ranked" at $129,002, built on tech-expert authority from Jared, the top male creator (stated, N-MCD and digest). Then PETL60 at $183K across two ad sets, content data-limited, and PETL61 "Meet PETL Plus" at $84,966. Gifting ad sets get about 6% of spend, the Three Devices ad set gets 9.8% at 2.29x and was called "winner starved, needs more ads" (stated, Grace's brief for week of 2026-10-26). Creator criteria require "younger 20s–30s and older 40s–60s+, both genders" and every creator shoots family gifting B-roll (stated, S-int 2026-09-29).

**Actual buyer.** Purchases in the last 90 days, verified from the Meta pull:

| Age | Women: share of purchases, CPA | Men: share of purchases, CPA |
|---|---|---|
| 65+ | 30.8%, $63.21 | 13.3%, $57.74 |
| 55-64 | 21.0%, $72.84 | 10.8%, $66.38 |
| 45-54 | 9.7%, $81.21 | 6.9%, $71.88 |
| 35-44 | 3.2%, $81.79 | 2.8%, $84.42 |
| 25-34 | 0.7%, $98.96 | 0.7%, $97.16 |
| 18-24 | 0.1% | 0.0% |

Women are 65.5% of purchases. On the customer side, the survey says how they arrived and why. 733 of 836 respondents first heard of PETL from a Facebook or Instagram ad, 16 from a friend or family member, 18 from TikTok, 9 from Google (verified, survey count). What they hoped for: ease and convenience dominate, then travel, then charging all their Apple things, then fewer cables. Why PETL: the look and shape in 64 of 236 answers, the size in 48 (classification read).

**The gap.** On age, served and actual mostly line up: 72% of spend goes to 55+, and 55+ makes 75.9% of purchases (verified). So the classic "you are serving the wrong person" gap is not the story here. The gaps are three narrower ones.

1. **Men 65+ are the cheapest buyer and get less than their share.** They make 13.3% of purchases on 11.2% of spend, at a $57.74 CPA, the best in the account (verified). Rakesh's own 5 Oct readout calls Male 65+ "best efficiency, underweighted" (stated, 02-audience doc). The client playbook also says "default older-audience scripts to grandma/women" (stated, 02-audience doc). That rule is right on volume and leaves the most efficient pocket thin.
2. **The message gap.** The ads that soak spend run on ranking authority, Apple-discontinued comparison, and dead-battery stakes. Buyers describe ease, fewer cables, small size, and the look. The ease and simplicity story for an older buyer has one proven carrier, PETL65, and the account keeps reshooting it with new faces rather than new messages.
3. **The trust gap.** About one in ten objection answers is "is this real" (23 of 222, classification read): "Not seeing this on Amazon has me a little concerned about authenticity and quality." The account has almost no creative whose job is to settle that doubt for a first-time older buyer who found PETL in her Facebook feed.

**Diagnosis, two sentences.** PETL's buyer is already the 55+ Apple household, mostly women, buying for herself and her people, but the creative sells her a younger buyer's panic and a tech reviewer's ranking instead of the plain ease and the "is this legit" reassurance she actually asks for. The next quarter should go deeper on her, in her own words about fewer cords and easy charging for all her Apple things, add the 65+ man she lives with as a real lane, and stop spending shots on younger buyers gifting up.

What this disqualifies: net-new concepts aimed at 18 to 34, younger-buyer gifting-up stories as a lead lane, AI formats pitched as "younger tech" tests, and panic hooks that open on danger.

## Framework architecture

- **Identities:** `no-fuss-family-keeper` (flagship), `apple-design-loyalist` (secondary), `team-provider` (emerging).
- **Behavioral signals** are defined inside each persona and collected in the Behavioral overlays section. The ones that recur across personas: `gift-for-my-people`, `travel-day`, `new-iphone-refresh`, `burned-by-another-pack`, `cable-clearout`, `bundle-stock-up`, `first-time-trust-check`, `nightstand-routine`, `aging-phone-battery`.
- **Awareness:** most buyers enter product-unaware or solution-aware from a cold Facebook ad. The category is crowded at stage four to five sophistication (stated, audience_and_market.md), but this buyer is not living in that spec race. The persona reads below explain why.

## Persona reference matrix

| | No-Fuss Family Keeper | Apple Design Loyalist | Team Provider |
|---|---|---|---|
| Status | Flagship | Secondary | Emerging |
| Core drive | Make charging one less thing to manage, for me and my people | Own the best-made, best-looking thing for my Apple setup | Give my people something useful they will actually use |
| Age and gender | 55+, mostly women; verified at account level | 45-64 leaning male; inferred | 45+; stated by anecdote |
| Volume | Majority of purchases; inferred share 60% or more | Meaningful minority; data-limited | Small in orders, large in units |
| Emotional intensity | Medium, warm; relief and pride in being prepared | Medium; delight in the object | Low to medium; pride in the gift |
| Strongest message | One for everything, easy, fewer cords | Not plastic, circular, ranked best, Apple successor | The gift nobody leaves in a drawer |
| Confidence | Mixed | Mixed | Thin |

The volume and intensity rankings differ. The Family Keeper wins on volume. The most intense language in the corpus comes from people burned by a cheap pack or a sketchy Instagram brand, which is a signal that sits on both of the top two personas.

## Persona 1: The No-Fuss Family Keeper — flagship

Slug: `no-fuss-family-keeper`

### Identity

**Who she is.** An older Apple owner, most often a woman in her late 50s to 70s, who runs the household's stuff: her own iPhone, Apple Watch, and AirPods, and often her husband's, her kids', and her grandkids'. She is capable and practical. She does not think of herself as a tech person and does not want to become one. She wants things that work the first time and do not need managing. Being the one who is prepared, and the one who sorts things out for the family, is part of how she sees herself.

The age and gender part is verified at the account level: women 55+ are 51.8% of all purchases, and women 65+ alone are 30.8% with a $63.21 CPA (Meta pull). That any single survey answer below comes from her is inferred, because the survey carries no age.

**Core identities.**
- *The one who keeps everyone's devices going.* Evidence: Rakesh states "Older buyers buy in bulk for the household" (stated, 02-audience doc). The PDP bundles are named "One for every bag" and "One for the whole family," and 3-packs are tagged MOST POPULAR (verified, PDP via research note). Survey answers name the household: "Portable charger for me & family" (#GP5994, 2026-02-26), "It looked like something I would want my husband and myself to have" (#GP6999, 2026-03-10), "If I like it then I will be buying several more for my kids and family" (#GP4942, 2026-02-07). Corroborated across account data, client statement, PDP, and survey. Near verified on direction, data-limited on size.
- *Not a tech person, and fine with that.* Evidence: the team states the older buyer is "not tech-savvy, and many don't know the word "MagSafe"" (stated, 02-audience doc). Survey: "Ease of use for an elderly woman" (#GP7130, 2026-03-12), "What is pronouncing?" (#GP5178, 2026-02-12), "Looks easy to use" (#GP5415, 2026-02-17). 89 of 320 hopes answers use ease or convenience words (classification read). Inferred, resting on survey plus team observation.
- *Hates the clutter of cords and the hunt for the right one.* Evidence: wire, cord, and cable words in 44 of 778 survey answers (classification read). "Not having to deal with so many wires." (#GP4464), "Freedom from Cords" (#GP5207). The team says relief for 65+ "is about reduction (fewer cables, one place), not power" (stated, 02-audience doc).

**Contextual identities.** She becomes *the traveler* when she flies to see family. PETL75 was built on a woman "who flies to see her grandchildren every month" (stated brief), and 38 of 320 hopes answers name travel. She becomes *the gift-giver* at Christmas, birthdays, and Father's Day, when the same keeper instinct points at her husband or kids.

**Outward versus real.** Outwardly she is the "design-conscious" buyer the brand describes, and she does say the look sold her. But her stated hopes are about ease, not style. The clearest concrete gap is gender of user versus buyer: "My husband coming into the room just before I submitted my order." (#GP7459, 2026-03-15) shows a woman buying a gift in secret, logged in Meta as a female 55+ purchase for a man who will use it. Inferred.

### Behavioral signals (currently observed)

- `gift-for-my-people` — She is buying for a spouse, kids, or grandkids, not only for herself. Share: about 1% of survey respondents name a gift or family recipient, 9 of 836 (classification read, Jan to Mar, no holiday in the window). Team-stated far higher in Q4 and on 5-packs. Implication: multi-unit offers and "one for each of us" framing; Q4 gifting creative should show her giving, not receiving.
- `travel-day` — An upcoming trip, often to see family. Share: 38 of 320 hopes answers, 12% (classification read). Implication: airport and destination days, airline-safe proof; "Cost and timing before trip" (#GP6532) shows the trip also sets a deadline.
- `cable-clearout` — She is tired of the drawer of cords and pucks. Share: 30 of 320 hopes answers name cables, cords, or wires (classification read). Implication: show three chargers becoming one, slowly, at a pace she can follow.
- `first-time-trust-check` — She found PETL in her feed and is checking it is real before she pays. Share: 23 of 222 objection answers (classification read). Implication: reviews count, real owners, the 30-day risk-free trial, and "here is how to know we are real" creative.
- `bundle-stock-up` — She locks in savings in one go. Share: data-limited; half of orders are single-unit at about $96 AOV (stated, Charley, S-client 2026-10-20). Implication: bundle math at bottom of funnel only, per the brand's "30% off in creatives for BOF (not TOF)" rule (stated, N-R3).

### Voice signature

Plain, short, practical. She writes three to seven words: "Easy charging," "Less cables," "Portable charger for me & family." She names the devices one by one: "my phone, watch, and AirPods." She uses hope words at the moment of purchase: "Hopefully it works," "Hoping the reviews are right." No jargon; she spells MagSafe wrong ("Mag saga charger," #GP4738) and asks how to say the name. Emotional engine: quiet relief and being prepared for her people. Load `persona-voice-library.md` emotions 1, 2, and 4, and the cable, everyday, and trust clusters in the two VoC docs.

### Day-in-the-life

Inferred, built from the survey, the team's call notes, and the creative tests that worked. She keeps her iPhone, Watch, and AirPods on separate chargers on the kitchen counter or nightstand, and the Watch puck is the one that goes missing. Her husband's phone is always low. When she travels to see the grandkids she packs a pouch of cords and still forgets one. She sees a PETL ad on Facebook in the evening, likes how small it looks and that it charges all three, checks the reviews on the site because she has never heard of the company, and buys two or three so her husband gets one. Rakesh relayed a similar busy-mother story from a 45-year-old customer whose phone "is always on low battery, because she hate to plug the phone and leave it away" (stated, Rakesh relaying a conversation, S-client 2026-09-10; his words, not hers).

### What activates purchase

**Revealed trigger pattern.** She buys from a demonstration in the feed. 733 of 836 heard about PETL from a Facebook or Instagram ad. In "why us" answers, the ad or video itself is the reason in 17 of 236: "Because of the good demonstrations on Facebook," "The videos helped," "The ad convinced me" (classification read). Seeing it snap on and charge three devices is the moment, more than any dead-phone crisis.

**Stated versus revealed.** Stated: she wants convenience. Revealed: she bought because it looked easy and looked well made, and she bought after checking that the company was real. The trust check is load-bearing for the close; the ease is load-bearing for the stop. Inferred.

**Friction at the close.** Price first: 89 of 222 objection answers, 40%, and the survey ran at $49 (classification read; N-R3 stated 47% on its own coding). Trust second: 23 of 222. Then colour choice inside bundles: "Was going to purchase the 2 pack, but didn’t see an option to choose the colors" (#GP5087). Then checkout: "Payment link didn’t work" (#GP7386), and a Facebook commenter saying no PayPal stopped her buying "multiple times."

### What we believe vs what we observed

- **High confidence, three or more source types.** Older buyers dominate (Meta pull, N-R3, client dashboard, Rakesh calls). Ease and fewer cords are what they want (survey, team call notes, PETL65 results). Charging all three Apple devices is a reason to buy (survey 34 of 320 hopes, January reviews, FB comments asking about Watch).
- **Single source, needs corroboration.** That the older buyer buys in bulk for the household rests mainly on Rakesh's statement plus the PDP bundle naming; there is no order-level split by age. That she is buying for a husband rests on team observation ("Most women in their 40s–50s are buying for husbands, not dads," stated, 02-audience doc) and two survey answers.
- **Team assumptions the data does not support.** That this buyer is a "design-conscious" minimalist who prizes premium brands: half true, the look matters, but she never uses the words minimalist or premium; one buyer did, "Simple form factor with no frills. Minimalist." (#GP7868). That grandkids buying for her is a major lane: 25 to 44 make 7.4% of purchases. That low-battery panic is her driver: 4 of 778 survey answers use dead or dying words.

### Awareness and market sophistication

Mostly product-unaware or solution-aware when the ad hits. She knows phones die and cords are annoying; she did not know a round magnetic pack that charges her Watch existed. "First product I’ve seen that charges both items." (#GP6077), "I didn’t see another brand" (#GP7906), "There are other brands of this same kind?" (#GP5110). The category is sophisticated, but she is not shopping it, so for her the market is still early. Simple demonstration still carries. Inferred, resting on the 11 "no other brand" answers out of 236.

### Message signals, frequency-ranked

From survey hopes and reasons, classification read, overlapping buckets:
1. `msg-easy-no-fuss` — ease and convenience, 89 of 320 hopes.
2. `msg-looks-and-feels-right` — look, shape, design, 64 of 236 reasons.
3. `msg-small-fits-anywhere` — size and compactness, 48 of 236 reasons.
4. `msg-travel-ready` — 38 of 320 hopes.
5. `msg-one-for-everything` — iPhone, Watch, AirPods from one, 34 of 320 hopes.
6. `msg-fewer-cords` — 30 of 320 hopes.
7. `msg-proof-it-works` — reviews or the ad demo as the reason, 34 of 236 reasons combined.
8. `msg-more-in-the-day` — more battery life through the day, 22 of 320 hopes, said calmly ("Longer battery life").
9. `msg-never-caught-dead` — dead phone or emergency, 13 of 320 hopes. The brand leans on this one harder than she does.

### T-E-E-P content angle map

- **Trigger.** Her real moment is small and domestic: the Watch puck is missing again, her husband's phone is at 9%, the cord pouch for a trip. Mirror that state back plainly. Low intensity, positive, no danger.
- **Exploration.** She is building a picture of what this thing is. Show it on a real kitchen counter and in a real purse, at a slow pace, with a peer her age. PETL65's peer-to-peer ranking is the proven form.
- **Evaluation.** Her one objection is "is this legit, and is it worth $64.95." Name it. Real owner testimonials, review count, 30-day risk-free trial. Do not pile on specs.
- **Purchase.** Subtract. Show the bundle math and the "one for him too" logic, and let her pick colours. Fix the checkout frictions she named.

### Attribution

- **Contributed:** Meta age by gender pull, 2026-10-27, verified. Post-purchase survey, 1,144 orders, Jan 20 to Mar 26 2026. Team-stated audience notes: N-R3 2026-04-22, client dashboard ~2026-07-15, Rakesh 5 Oct readout, bi-weekly calls 2026-07-16, 2026-08-25, 2026-10-09. Notion briefs PETL65, PETL73, PETL74, PETL75. Website reviews Jan 2026. FB comments captured 2026-04-17. PDP bundle naming via research note 2026-10-27.
- **Available but unused or empty:** Judge.me full corpus, not accessible. Reddit, blocked. Trustpilot, zero reviews. No age-tagged review text exists.
- **Confidence: mixed.** The who is verified at the account level. The why rests on a survey with no demographics, so the link between this person and that language is inferred. A fresh survey with an age and "who is it for" question would move this to strong.

## Persona 2: The Apple Design Loyalist — secondary

Slug: `apple-design-loyalist`

### Identity

**Who he is.** An Apple-ecosystem owner who cares how his gear is made and how it looks next to his iPhone. He knows the specs, compares brands, remembers Apple's own discontinued battery pack, and wants the best-built option rather than the cheapest. More often a man, more often 45 to 64, though plenty of women share the identity. This is the buyer the brand thinks it has. He is real, just older and smaller than the brand pictures.

Gender and age here are inferred. The grounds: Space Black PETL 2 Plus purchases "run 91% men at 1.84x (strongest men 45-54 at 4.1x)" (stated, PA-weekly, week of 2026-10-26); M45-54 is described as "value-conscious, Apple-loyal" on the client dashboard (stated, ~2026-07-15); men 55-64 and 65+ convert at the account's best CPAs (verified, Meta pull); and Grace notes "Tech reviews and comparisons work better for men" and middle-aged men "care about "the best charger with the most battery"" (stated, 02-audience doc).

**Core identities.**
- *An Apple person, through and through.* Evidence: "Well integrated with iPhone" (#GP8420), "Because your product is designed and made for Apple Products." (#GP5795), "Liked the look and the fact that it could do the whole Apple ecosystem and work as a stand" (#GP4917). The team states "Apple ecosystem buyers with iPhone + Apple Watch + AirPods are the sweet spot" (stated, N-R3). And "Mentioning Apple in hooks increases attention" while direct Apple attack fails "because of loyalty" (stated, 02-audience doc and N-MCD PETL77 hypothesis).
- *Judges by build quality and materials.* Evidence: "Product is not plastic" (#GP7471), "Reviews and quality materials used to build it." (#GP7439), "Design and engineering" (#GP4274), "Looked very solid" (#GP7844); website review "very strong sturdy looking" (Jan 10 2026).
- *Compares before he commits.* Evidence: "comparing your product to Anker's options" (#GP4815), "It’s cheaper than the torras, and it looks sleeker." (#GP6145), "3000 mHa seemed a little low as there are other chargers that are 10,000 mHa" (#GP6287), "Give me Qi2 charging and I’m in 🙂" (FB, Lee M.).

**Contextual identities.** *The early adopter* when a new iPhone lands: "Just bought a 17 pro max iphone Saw your add and read your reviews" (#GP7729). *The desk and nightstand setup person* when the stand and StandBy mode come up.

**Outward versus real.** Outwardly he is a spec man. In practice he accepts a smaller battery for the form: "Yes.. it may only be 3000 ml amps, but the size and the design makesup for that." (website review, 2026-01-08). Inferred from that review plus the design and size reasons dominating survey answers.

### Behavioral signals (currently observed)

- `new-iphone-refresh` — Just upgraded, refreshing accessories. Share: data-limited; 1 survey answer names a new phone (#GP7729); Notion PETL105 "New iPhone?" ran $13,629 at $95.31 CPA (verified, META). Implication: fit reassurance for new models, which FB comments ask about ("Will this work with the iPhone 18").
- `burned-by-another-pack` — A previous power bank disappointed him. Share: 4 of 236 reasons answers plus related objections (classification read). Implication: comparison and stress-test creative; this is the most emotionally charged language in the corpus.
- `nightstand-routine` — Uses it as a stand at night or at a desk. Share: stand, kickstand, or cradle named in 8 survey answers (classification read). Implication: StandBy mode as a second job.
- `gift-for-my-people` — Shared with persona 1, expressed as buying the same good thing for his wife or kids. Share: data-limited.

### Voice signature

Slightly longer, more specific, comparison words: "cheaper than," "other chargers that are," "build quality," "ease of connection." He names specs, sometimes wrongly ("3000 mHa," "3000 ml amps"). Emotional engine: satisfaction in the well-made object and the small pride of picking the better one. Load `persona-voice-library.md` emotions 3 and 5.

### Day-in-the-life

Inferred. iPhone Pro, Apple Watch, AirPods Pro. Owned a rectangular Anker or the Apple pack at some point and found it heavy or slow. Sees a ranked comparison or an "Apple discontinued theirs" ad, recognises the problem, checks the specs and the materials, and picks a colour. Space Black for himself.

### What activates purchase

**Revealed trigger.** Authority and comparison content. PETL48 Top 5 Ranked took $129,002 at the account's best large-scale CPA, $58.21 (verified, META); the "Apple discontinued theirs" franchise was "the account's single biggest engine" in spring (stated, PETL39 hypothesis). **Stated versus revealed:** he says capacity and speed matter; he buys on form and build. **Friction at the close:** capacity doubt and comparison to cheaper packs.

### What we believe vs what we observed

- **High confidence:** Apple-ecosystem framing and the look and build drive purchase (survey, reviews, team notes, account results for ranking and Apple-successor ads).
- **Single source:** the male skew rests on PA-weekly's Space Black figure and Grace's observation. The Meta pull shows men are 34.5% of purchases and convert cheaper than women at every age from 45 up, which fits but does not prove the persona split.
- **Unsupported assumption:** that this buyer is young. The tattooed desk-setup tech male of the January Gemini read does not show up in the purchase data.

### Awareness and market sophistication

Solution-aware to product-aware. He knows MagSafe packs exist and has likely owned one. For him the market is at stage four to five sophistication: many brands claim slim, fast, and world-first (stated, audience_and_market.md). Receipts beat claims: the circle, the aluminum, the 3-device demo, a fair side-by-side.

### Message signals, frequency-ranked

1. `msg-looks-and-feels-right`, especially "not plastic" and build. 2. `msg-one-for-everything`. 3. `msg-ranked-best`. 4. `msg-apple-successor`. 5. `msg-small-fits-anywhere`. Ranking is my judgment across the survey reasons and account results; there is no survey split by persona.

### T-E-E-P content angle map

- **Trigger:** his old pack is heavy, or a new iPhone needs accessories. Name the "brick on the back."
- **Exploration:** ranked comparisons, the Apple-successor story, materials close-ups.
- **Evaluation:** answer capacity honestly, as a top-up not a brick; compare fairly. Do not hide the 3,000mAh number from a man who already knows it.
- **Purchase:** colour, PETL 2 Plus as the upgrade path, bundle for the household.

### Attribution

- **Contributed:** survey reasons and objections; January website reviews; FB comments; META spend table; PA-weekly colour split; client dashboard; Grace's stated observations.
- **Unused or empty:** no review or survey data split by gender; no creative media.
- **Confidence: mixed.** The identity is well evidenced in language. Its size and gender skew are inferred.

## Persona 3: The Team Provider — emerging

Slug: `team-provider`

### Identity

Someone responsible for a group, a doctor's practice, a team lead, a coach, a small business owner, who buys PETL in numbers to give to the people they look after. The durable identity is "the boss who takes care of the team," and it outlasts any one order.

**Evidence, all thin.** A 65+ doctor with 4+ orders appeared to be buying "for his team" (stated, S-client 2026-07-27; F-2026-08-25 transcript: "Who is age? 65 plus."). Rakesh states he gets "one or two corporate requests a day," two unprompted 50-unit orders, and a 500-unit order at $35 a unit (stated, F-2026-07-15, F-2026-09-09). One survey answer: "I am coach so I need something slim and easy" (#GP6155), which is a self-purchase but shows the role. PETL72, team gifting with AI VO, ran $28,660 at a $122.48 CPA (verified, META), so the consumer ad route has not worked for this person.

**Behavioral signals:** `team-gift-season` (year-end and holiday staff gifts), `bundle-stock-up`, `logo-and-engraving` (data-limited; the corporate page with logo mockups and engraving were in progress per F-2026-09-09 and F-2026-10-09).

**Voice signature:** data-limited. No verbatim from a team buyer exists in the sources.

**What activates purchase:** a gifting deadline plus a need to avoid giving junk. Rakesh's framing, "don't gift something nobody uses" (stated, F-2026-08-25), is the brand's, not the buyer's.

**Awareness:** product-aware once they have used one themselves (inferred).

**T-E-E-P:** this persona likely needs a sales motion, not an ad lane: a corporate page, a quote form, a lead-gen campaign. Rakesh requested one 2026-10-15 and tracking was blocked until a thank-you URL exists (stated, S-client).

**What would move this persona up:** ten or more confirmed multi-unit orders of 10+ units tied to a role in one quarter, any verbatim from such a buyer, or a corporate lead form result.

**Attribution and confidence:** Slack and Fathom anecdotes plus one META row. **Confidence: hypothesis.** Do not let it drive flagship strategy.

## Entry-door trigger library

- `trig-saw-it-demonstrated` — A feed ad showed it snap on and charge three devices. The dominant door: 733 of 836 heard of PETL from a FB or IG ad.
- `trig-trip-coming` — A trip is on the calendar. 38 of 320 hopes.
- `trig-cord-mess` — The drawer or bag of cables finally annoys enough. 30 of 320 hopes.
- `trig-prior-pack-failed` — The last pack died fast, did not work, or was junk from Instagram. "I have a different battery pack but it dies right away" (#GP6875).
- `trig-new-iphone` — A new phone needs new accessories.
- `trig-gift-occasion` — Christmas, Father's Day, a birthday. Father's Day ads drove a 148% MoM surge that sold out Black (stated, digest timeline).
- `trig-friend-showed-me` — Word of mouth, 16 of 836. "My friend gave me yours and I loved it" (#GP7674).
- `trig-phone-dies-mid-day` — Present but small in buyer language: 4 of 778 answers.

## Behavioral overlays

`gift-for-my-people`, `travel-day`, `cable-clearout`, `first-time-trust-check`, `bundle-stock-up`, `new-iphone-refresh`, `burned-by-another-pack`, `nightstand-routine`, `aging-phone-battery`, `team-gift-season`. Gifting and bundles are overlays, never personas: they cut across all three identities. Deal-seeking in particular is a sale-ad artifact here, since bundle and offer ad sets have the best ROAS (AR717 V1 2.33x, verified META) and would make "the deal buyer" look like a person if the sale creative were not stripped out.

`aging-phone-battery` — An old iPhone that no longer lasts the day. Evidence: PETL70 hypothesis and "Help my phone’s battery make it thru the day" (#GP5663). Thin.

## Identity overlays

- **Grandparent.** Sits on the Family Keeper. A life stage, not a persona: being a grandparent changes the stories (photos of grandkids, flights to visit) but not the purchase behavior.
- **Apple-ecosystem owner.** Sits on both top personas. Not a persona on its own, because nearly every buyer has it; the iOS-only product makes it a floor.
- **Professional with a role** — doctor, nurse, coach, police detective son of a gifting mum (stated, PA-weekly review mention). Can sit on any persona.
- **Spouse.** The man using a PETL his wife bought. He is often the user, not the buyer, which is why he is under-counted.

## Voices that speak for the brand

- **Peer senior creator.** The PETL65 senior woman ranking chargers for other grandparents. Proven at scale.
- **Tech reviewer or ranker.** Jared on PETL48; CJ and Asher on the PDP. Works for the Design Loyalist.
- **Real owner testimonial.** PETL74 cast "a genuine PETL owner rather than a hired creator" (stated); PETL84 long-copy ran 2.04 to 2.15x (verified META). Rakesh insists testimonial angles use "real UGC not AI" (stated, S-client 2026-09-10).
- **The spouse.** "My wife told me I had to get this" was a proven hook (stated, 02-audience doc). Note this is an ad hook, not a customer quote.
- **The reviews themselves.** 1,454 Judge.me reviews at 4.83 (verified on page, research note). The trust check makes this voice load-bearing.

## Messaging signals library

`msg-easy-no-fuss`, `msg-looks-and-feels-right`, `msg-small-fits-anywhere`, `msg-travel-ready`, `msg-one-for-everything`, `msg-fewer-cords`, `msg-more-in-the-day`, `msg-proof-it-works`, `msg-ranked-best`, `msg-apple-successor`, `msg-bundle-value`, `msg-never-caught-dead`, `msg-risk-free-trial`, `msg-gift-that-gets-used`.

## Companion-doc routing

- Emotional engines and liftable phrases: `personas/persona-voice-library.md`.
- Before-state problem language: `personas/voice-of-customer/voc-pain-phrase.md`.
- Pre-purchase doubts: `personas/voice-of-customer/voc-objection.md`.
- Not built in this lean pass: outcome, metaphor, aspirational, trigger, delight, jargon, and anti-language extractions; lifecycle journey maps; VoC corpus profile.

## What we're watching

- **New signal:** PETL 2 Plus buyers on big new phones ("my iPhone 18 Max Pro," Judge.me 2026-10-26) asking for more capacity ("a 10k would be great!"). Could pull the Design Loyalist toward the 2 Plus.
- **New signal:** Space Black as "his" colour. If colour splits by gender this cleanly, colour becomes a persona lever.
- **Forming cluster:** the busy 35 to 54 mother whose phone is "always on low battery" (Rakesh relay, PETL93). Women 35 to 54 are 12.9% of purchases at $81 CPA. Watch for real verbatims.
- **Forming cluster:** the iPhone Duo or foldable owner (PRWeb, PETL94). No buyer evidence yet.
- **Suspected bias artifact:** the young design-minimalist tech user. No purchase data supports it as a lead persona. Keep it out unless a younger test cell beats the account CPA.
- **Suspected bias artifact:** the grandchild gifting up to a grandparent. Keep as a Q4 overlay test, not a lane, unless 25 to 44 purchase share rises in December.

## Open loops

1. **Who the 65+ woman is buying for.** Women 65+ make 30.8% of purchases, but no source records whether the PETL is for her, her husband, or someone else. *Pull: Gap — the biggest buyer group has no recipient data at all.* **Question:** Who ends up using the PETLs that women 65 and older buy? *Justification:* If most go to husbands, the 65+ man is the real user and the creative should show him; if most are hers, the gifting story is a sideshow. Territory: personas. Routes to the brand, who can add the question to the post-purchase survey.

2. **Why men 65+ are the cheapest buyer.** Men 65+ convert at $57.74, the best CPA in the account, on 11.2% of spend, while the playbook tells writers to default to grandma. *Pull: Surprise — the most efficient buyer is the one the rules tell us to write for least.* **Question:** What is bringing men 65 and older to buy at a lower cost than anyone else? *Justification:* It decides whether the next round adds a 65+ man lane or keeps the female default. Territory: personas.

3. **The panic gap.** The brand's copy leads on dead phones and 1% panic, but buyers almost never use that language. *Pull: Tension — brand self-image against buyer words.* **Question:** How much of the account's spend runs on dead-battery panic hooks, and how do those ads convert next to ease and fewer-cords hooks? *Justification:* If panic hooks underperform for this older buyer, the hook library should shift to plain ease. Territory: messaging.

4. **The trust check after the price rise.** One in ten objections in Jan to Mar was "is this legit," at $49. *Pull: Pattern — the same doubt shows up across survey, FB comments, and the brand's own complaints blog.* **Question:** What share of shoppers who reach the PDP now leave because they are not sure PETL is real? *Justification:* If trust is a bigger leak at $64.95, proof and reassurance creative may beat new hooks. Territory: messaging. Routes to the brand for checkout and survey data.

5. **The team buyer.** Corporate and team orders arrive unprompted, and the consumer team-gift ad failed. *Pull: Curiosity — a buyer type that keeps showing up without being marketed to.* **Question:** How many of PETL's multi-unit orders come from someone buying for a team or a business? *Justification:* It decides whether the Team Provider gets a sales motion and its own page. Territory: personas. Routes to the brand.
