---
brand: petl
doc: voc-objection
category: objection
generated_on: 2026-10-27
refresh_by: 2027-01-15
refresh_note: "VoC cadence ~180 days; set sooner because every survey objection below was voiced at the $49 price, before the Aug 2026 move to $64.95, and BFCM will shift the price and trust objections."
build: lean
personas_profile: personas/personas-profile.md
voc_corpus_profile: not built (lean build)
corpus_read:
  - "Post-purchase survey Q4 'What almost stopped you from buying today?', 222 answers, 2026-01-20 to 2026-03-26, plus doubts voiced in Q2 and Q3. Source: source-pulls/_exports/grace-claude-project-2026-10-27/PETL Project context Files.txt, 'new survey responses & customer research' (export 2026-03-27)."
  - "Facebook ad comments, 28 customer comments from top videos, captured 2026-04-17, same file, 'FB Comments'."
  - "Website reviews, 11 with text, 2026-01-08 to 2026-01-13; Judge.me PDP reviews, 5, 2026-10-26 to 2026-10-27, via research note."
  - "Brand complaints blog 'PETL Reviews & Complaints: Is PETL Legit?' as summarized in research_notes/PETL brand and market research/petl_brand_and_reviews.md (stated)."
q4_denominator: 222
q4_breakdown_classification_read:
  price_or_money: 89
  nothing_or_na: 65
  trust_or_legitimacy: 23
  does_it_work_or_quality: 11
  colour: 8
  shipping: 5
  already_have_or_need: 5
  capacity: 4
  checkout_or_payment: 4
  other_single: remainder
data_limitations:
  - "Survey respondents are people who bought, so these are objections that were overcome. The objections that won are invisible here; the FB comments are the only window on non-buyers."
  - "All survey objections date from the $49 era. The price objection is likely larger now (inferred, resting on the Notion hypotheses from PETL96 onward that call price 'now the main objection')."
  - "FB comment dates are approximate, computed from the relative age shown in the 2026-04-17 capture."
  - "No age, gender, or recipient on any record; identity tags inferred."
  - "Theme counts are my keyword classification read with overlapping buckets, not structured fields. N-R3 (2026-04-22) coded the same survey as price 47% and skepticism or 'not on Amazon' 10% (stated)."
  - "Wrapped lines in the PDF export were rejoined with one space; otherwise verbatim."
---

# VoC objection phrases — PETL

## How to read this

These are the doubts buyers had before they bought, in their words. Survey answers come from people who pushed through the doubt and bought anyway, so they show which barriers are survivable and how people talked themselves past them. Facebook comments come mostly from people still deciding, so they show the questions an ad has to answer before someone buys.

Of 222 answers to "What almost stopped you from buying today?", 89 are about price or money, 65 say nothing stopped them, and 23 doubt that PETL is legit (classification read). Price is the biggest barrier by a wide margin. Trust is second and is the one the creative answers least. The Facebook comments add a third barrier the survey barely shows: will it work with my phone, my case, my Watch.

Persona slugs from `personas/personas-profile.md`: `no-fuss-family-keeper`, `apple-design-loyalist`, `team-provider`.

## Objection phrases

### Cluster: price and money

- snippet: "$$$"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP8405", date: 2026-03-26, url: null}
  recurrence: 89
  source_diversity: [post-purchase-survey, ad-comment]
  first_seen: 2026-01-20
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Recurrence 89 of 222 Q4 answers name price, cost, money, funds, spending, or discount; about 40% of all answers and about 57% of the 157 that named any barrier. Most say only 'Price' or 'Cost'. FB adds 'How much?' (Thomas W.). At $49. The brand later raised prices on 2026-08-03 and the single unit is now $64.95 (stated, digest)."

- snippet: "I don’t really have money to spend"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP8389", date: 2026-03-26, url: null}
  recurrence: 6
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-10
  last_seen: 2026-03-26
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 6 = answers about the buyer's own budget, not PETL's value: this one, #GP7602 'Low on funds', #GP5110 'The funds or lack there of', #GP6188 'Nothing really just making sure I’m had enough money', #GP7848 'Money', #GP6058 'Spending $ lol'. Underlying concern, inferred: real budget strain, often older buyers on fixed incomes. Do not answer with guilt or scarcity; the team states older buyers 'read pure scarcity as manipulative' (02-audience doc)."

- snippet: "Been lookin at these damn chargers for a while but always hesitated at the price. If it’s a decent charger then the price isn’t bad but if it’s basic and doesn’t do its job very well then it’s too expensive. Looking forward to finding out. If I like it then I will be buying several more for my kids and family"
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: gift-for-my-people
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4942", date: 2026-02-07, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-07
  last_seen: 2026-02-07
  confidence: thin
  brand_self_echo: false
  notes: "The richest objection in the corpus. Underlying concern, inferred: price is only too high if it fails, so the real objection is 'will it do its job'. Also shows the household multiplier: a first unit as a trial before buying for the family. Whole-review concept candidate for a long-copy static."

- snippet: "Price vs only one full charge if my phone is almost dead."
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7439", date: 2026-03-15, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-03-15
  last_seen: 2026-03-15
  confidence: thin
  brand_self_echo: false
  notes: "Price measured against capacity. Joins the capacity cluster below. Claims governor: on an iPhone 16 Pro the original gives about 55% by MagSafe (stated, brand performance guide), so even 'one full charge' overstates the original."

- snippet: "The price is high for a recharging pack, there isn’t a clear understanding online about what other devices it can charge it does say Apple Watch and air pods but you can’t find a list of which ones are compatible."
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7075", date: 2026-03-11, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-03-11
  last_seen: 2026-03-11
  confidence: thin
  brand_self_echo: false
  notes: "Price plus a compatibility doubt. Matches the open Apple Watch claim issue in the digest (the website contradicts itself on wireless versus cable Watch charging)."

- snippet: "Less expensive (but less attractive) charger on Amazon. Chose this because it’s a bit different from the rest and can charge my AirPods and watch."
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP5155", date: 2026-02-11, url: null}
  recurrence: 2
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-04
  last_seen: 2026-02-11
  confidence: thin
  brand_self_echo: false
  notes: "Shows the objection and its resolution in one answer: cheaper Amazon option, overcome by looks and three-device charging. Recurrence 2 with #GP4815 'comparing your product to Anker's options'."

- snippet: "Price for one was almost too much compared to buying in bulk"
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: bundle-stock-up
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP6638", date: 2026-03-05, url: null}
  recurrence: 2
  source_diversity: [post-purchase-survey]
  first_seen: 2026-03-05
  last_seen: 2026-03-13
  confidence: thin
  brand_self_echo: false
  notes: "The bundle ladder makes the single unit look expensive. Recurrence 2 with #GP7259 'Cost initially but proceeded with buying 2 with discount', a doubt resolved by the bundle."

- snippet: "The cost, but realized I can do payments on the purchase, so I went through with it."
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP5352", date: 2026-02-15, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-15
  last_seen: 2026-02-15
  confidence: thin
  brand_self_echo: false
  notes: "Resolved by pay-in-four, which the PDP offers ('or 4 interest-free payments at checkout', verified on PDP by research pass 2026-10-27). The account has no creative that mentions it (data-limited; ad copy not pulled)."

- snippet: "He price with not enough discounts."
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4581", date: 2026-01-31, url: null}
  recurrence: 6
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-29
  last_seen: 2026-03-24
  confidence: mixed
  brand_self_echo: false
  notes: "Discount-seeking. Recurrence 6 = #GP4581, #GP4474 'Lack of a discount', #GP5889 'No discount.', #GP5191 'Discount', #GP7427 'Not being able to stack discounts', #GP6145 'The “discount “.' Deal hunting is a behavior, not a persona; see personas-profile."

- snippet: "Petl15 code I could not use. Don’t offer this code if you can’t use it."
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP8199", date: 2026-03-24, url: null}
  recurrence: 2
  source_diversity: [post-purchase-survey]
  first_seen: 2026-03-08
  last_seen: 2026-03-24
  confidence: thin
  brand_self_echo: false
  notes: "Offer friction. PETL15 has since been retired (stated, N-MCD PETL68, 2026-09-08). Recurrence 2 with #GP6866 'Forgot my promo code'."

### Cluster: is this real

- snippet: "Wasn’t sure if this was going to be a legit product."
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP6117", date: 2026-02-27, url: null}
  recurrence: 23
  source_diversity: [post-purchase-survey, brand-reputation]
  first_seen: 2026-01-25
  last_seen: 2026-03-24
  confidence: strong
  brand_self_echo: false
  notes: "Recurrence 23 of 222 Q4 answers doubt legitimacy, the brand, the website, or buying from social. The brand's own blog is titled 'PETL Reviews & Complaints: Is PETL Legit?' and says shoppers 'probably landed on a Reddit thread or AI summary' (stated, research note). Trustpilot has 0 reviews and there is no Amazon listing (verified by research pass), so off-site proof does not exist. Underlying concern, inferred: fear of losing money to a fake brand seen in a feed."

- snippet: "That I could only find it on Facebook. Facebook purchases are sketchy 50% of the time. Not seeing this on Amazon has me a little concerned about authenticity and quality."
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7121", date: 2026-03-12, url: null}
  recurrence: 23
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-25
  last_seen: 2026-03-24
  confidence: strong
  brand_self_echo: false
  notes: "The fullest version of the trust doubt. Note 'sketchy 50% of the time' is a customer's own number, not a stat. Same buyer's Q3: 'Looked like what I was wanting'."

- snippet: "Because it was on Facebook and not on Amazon, where I know the shipping will be quick"
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7401", date: 2026-03-15, url: null}
  recurrence: 4
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-06
  last_seen: 2026-03-15
  confidence: mixed
  brand_self_echo: false
  notes: "Amazon as the safe place. Recurrence 4 = #GP7401, #GP7121, #GP5074 'Wasn’t on amazon', #GP4917 'Would prefer to have bought this through Amazon.' Underlying concern, inferred: shipping and returns feel safer through Amazon. PETL's '2 day' shipping answered it for some: #GP4438 'How long to get it, 2 day is great!!'."

- snippet: "The price and not seeing this other than on Instagram; wasn't sure if the product was legit. Would prefer to have bought this through Amazon."
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4917", date: 2026-02-06, url: null}
  recurrence: 23
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-25
  last_seen: 2026-03-24
  confidence: strong
  brand_self_echo: false
  notes: "Price and trust together, the two biggest barriers in one line. Same buyer's Q3: 'Liked the look and the fact that it could do the whole Apple ecosystem and work as a stand'."

- snippet: "Skepticism about purchasing products on Facebook"
  category: objection
  identity_tag: null
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP8084", date: 2026-03-22, url: null}
  recurrence: 5
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-01
  last_seen: 2026-03-22
  confidence: mixed
  brand_self_echo: false
  notes: "Distrust of the channel, not the brand. Recurrence 5 = #GP8084, #GP7114 'Buying from a Facebook ad, in general I don’t trust Facebook', #GP4668 'Don’t trust instagram ads', #GP7121, #GP4917. Ironic since 733 of 836 found PETL through FB or IG ads."

- snippet: "Hopefully, it’s not a scam"
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7675", date: 2026-03-17, url: null}
  recurrence: 4
  source_diversity: [post-purchase-survey]
  first_seen: 2026-03-03
  last_seen: 2026-03-17
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 4 = #GP7675, #GP7419 'Not sure the website is real', #GP6365 'may be a trick', #GP4594 'You never know what you are getting sometimes'. Same buyer's Q3: 'The ad convinced me'."

- snippet: "Unsure of the quality. Have never heard of this brand before a week or two ago"
  category: objection
  identity_tag: null
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4289", date: 2026-01-25, url: null}
  recurrence: 6
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-25
  last_seen: 2026-03-24
  confidence: mixed
  brand_self_echo: false
  notes: "Unknown brand. Recurrence 6 = #GP4289, #GP7829 'Unknown brand', #GP8196 'unknown product', #GP5914 'never heard of it. build quality.', #GP4276 'First time hearing about Petl', #GP6374. 'a week or two ago' shows the buy cycle from first ad to purchase can be short."

- snippet: "Never heard of this company before but the reviews look good and the website looks ok."
  category: objection
  identity_tag: null
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP6374", date: 2026-03-03, url: null}
  recurrence: 6
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-25
  last_seen: 2026-03-24
  confidence: mixed
  brand_self_echo: false
  notes: "Resolution in the same breath: reviews and a decent-looking website. Peer resolution exists: #GP6660 'Checking reviews from other customers before purchasing', #GP6510 'Just looked at the Petl page for reviews.', #GP7674 'I was interested in your demonstration and buyers comments'. Reviews are the trust answer; 17 of 236 Q3 reasons name them."

- snippet: "Not enough people speaking of it"
  category: objection
  identity_tag: null
  behavioral_signal_tag: first-time-trust-check
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP6999", date: 2026-03-10, url: null}
  recurrence: 2
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-01
  last_seen: 2026-03-10
  confidence: thin
  brand_self_echo: false
  notes: "Wants social proof volume. With #GP4684 'Had to dig for comments and concerns.' Same buyer's Q3: 'Because of the good demonstrations on Facebook It looked like something I would want my husband and myself to have'."

### Cluster: will it actually work

- snippet: "Not being sure that it actually works the way I expect."
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP8172", date: 2026-03-23, url: null}
  recurrence: 26
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-27
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Recurrence 26 = 11 Q4 doubts about whether it works or its quality, plus 15 Q2 hopes that it simply works as advertised ('Hopefully it works', 'That it works as described.', 'What the add says it will do'). Underlying concern, inferred: fear the ad oversells; prior failed packs feed it."

- snippet: "Not enough market study to know if this product actually works the way it’s advertised."
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP8047", date: 2026-03-22, url: null}
  recurrence: 26
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-27
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Same cluster. 'market study' signals a researcher. Same buyer's Q3: 'I’m hoping that it lives up to the advertising.'"

- snippet: "Hopefully it lives up to its reviews and advertisement"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4844", date: 2026-02-05, url: null}
  recurrence: 26
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-27
  last_seen: 2026-03-26
  confidence: strong
  brand_self_echo: false
  notes: "Same cluster. Pairs with #GP6207 'Whether vital will actually work as advertised' (customer's typo)."

- snippet: "That prior failure…"
  category: objection
  identity_tag: null
  behavioral_signal_tag: burned-by-another-pack
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4104", date: 2026-01-21, url: null}
  recurrence: 5
  source_diversity: [post-purchase-survey, ad-comment]
  first_seen: 2026-01-21
  last_seen: 2026-04-10
  confidence: mixed
  brand_self_echo: false
  notes: "The surface is three words; the context is in the same order's Q3, 'I tried another brand I found on Instagram but it didn’t work.' Underlying concern, inferred: being fooled twice. Recurrence 5 = burned-before records, see voc-pain-phrase."

### Cluster: capacity

- snippet: "3000 mHa seemed a little low as there are other chargers that are 10,000 mHa"
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP6287", date: 2026-03-02, url: null}
  recurrence: 8
  source_diversity: [post-purchase-survey, review, ad-comment, brand-reputation]
  first_seen: 2026-01-08
  last_seen: 2026-10-26
  confidence: strong
  brand_self_echo: false
  notes: "Recurrence 8 = survey #GP6287, #GP5795, #GP4066, #GP7439; website review 2026-01-08 'it may only be 3000 ml amps'; FB 'How many charges can it do?' (Cathy S.C.); Judge.me 2026-10-26 'a 10k would be great!'; the brand blog names 'the 3,000 mAh capacity feels small compared to traditional power banks' as a top concern (stated). Four source types. Resolution exists: the January review goes on 'but the size and the design makesup for that.'"

- snippet: "The PETL product only offers a 3,000 mAH MagSafe compatible Battery pack."
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP5795", date: 2026-02-23, url: null}
  recurrence: 8
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-08
  last_seen: 2026-10-26
  confidence: strong
  brand_self_echo: false
  notes: "Same cluster. Pre-dates PETL 2 Plus (5,000mAh, launched for pre-order ~2026-06-19). Same buyer's Q3: 'Because your product is designed and made for Apple Products.' Claims governor: 'made for Apple' is banned in PETL copy (stated, onboarding form)."

- snippet: "35% charging for 15 Pro Max"
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP4066", date: 2026-01-21, url: null}
  recurrence: 8
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-08
  last_seen: 2026-10-26
  confidence: strong
  brand_self_echo: false
  notes: "Big-phone owner who did the math. PETL 2 Plus is pitched 'Made for iPhone Pro & Pro Max' (stated, homepage), which is the answer."

- snippet: "Device works as promised. Loved the 5000 mAmp capacity....though with the batteries of new devices a 10k would be great!"
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: new-iphone-refresh
  source: {type: review, platform: Judge.me on gopetl.com PETL 2 Plus PDP, 5 stars, review_id: "Anonymous", date: 2026-10-26, url: "https://gopetl.com/products/petl-2-plus-magsafe-compatible-battery-pack-space-black"}
  recurrence: 8
  source_diversity: [review]
  first_seen: 2026-01-08
  last_seen: 2026-10-26
  confidence: strong
  brand_self_echo: false
  notes: "Post-purchase, so strictly a wish, not a pre-purchase doubt; logged because it shows the capacity doubt living on into the 2 Plus era. Newest capacity record."

### Cluster: will it work with my phone, case, or Watch

- snippet: "Does it work when you have a case on your iPhone?"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Kathy W.", date: 2026-04-03, url: null}
  recurrence: 6
  source_diversity: [ad-comment, post-purchase-survey]
  first_seen: 2026-03-18
  last_seen: 2026-04-10
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 6 = 4 of 28 FB comments ask about cases (Marla R.G. 'Does it work if your phone has a case on it?', Teesie L. 'Can it attach through a phone case?', Cindy H., Kathy W.), Robert P. on scratching, and survey #GP7729 'If I could use this charger with a case'. Only 1 of 222 buyers raised it, so it mostly stops people before they buy. Resolution exists: Judge.me 2026-10-26 'charging through my case', and the script line 'And no, you don’t need to take off the case for it to work.' Claims governor: works through MagSafe-compatible cases only."

- snippet: "Great idea except most phones are in a case!!!!"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Cindy H.", date: 2026-04-03, url: null}
  recurrence: 6
  source_diversity: [ad-comment]
  first_seen: 2026-03-18
  last_seen: 2026-04-10
  confidence: mixed
  brand_self_echo: false
  notes: "The case doubt as a flat dismissal. The strongest comment-bubble static candidate in the capture, answered by a visual of PETL on a cased phone."

- snippet: "Doesn’t it have a soft back so it doesn’t scratch the phone or case?"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Robert P.", date: 2026-04-10, url: null}
  recurrence: 1
  source_diversity: [ad-comment]
  first_seen: 2026-04-10
  last_seen: 2026-04-10
  confidence: thin
  brand_self_echo: false
  notes: "Scratch worry from an aluminum back. Data-limited whether PETL has a soft pad."

- snippet: "My Apple Watch uses a particular type of charger that has a slight dip in the center. If this has a flat surface, it won’t work. I have the Apple 8"
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: null
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Kim G.", date: 2026-04-10, url: null}
  recurrence: 4
  source_diversity: [ad-comment, post-purchase-survey]
  first_seen: 2026-03-11
  last_seen: 2026-04-11
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 4 = this, Brian S. 'Now make it work for Apple Watch', Shannon M. 'It charged apple watches too?!', survey #GP7075 'you can’t find a list of which ones are compatible.' Claims governor: gated. The website contradicts itself on whether the Watch charges wirelessly or by USB-C cable, and the brand's own FB reply said 'wirelessly' (digest open question 4). Do not answer this in copy until Rakesh confirms the mechanism."

- snippet: "Does this work with an android phone too as well cause I’m gonna get my husband one"
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: gift-for-my-people
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Jessica S.", date: 2026-03-27, url: null}
  recurrence: 2
  source_diversity: [ad-comment]
  first_seen: 2026-03-27
  last_seen: 2026-04-15
  confidence: thin
  brand_self_echo: false
  notes: "A wife shopping for her husband, blocked by his phone. Recurrence 2 with Cathy B. 'Does it work on Samsung razor phone'. PETL is iPhone 12 and newer only (stated, PDP FAQ). Gifting doubt the brand can only answer with a no."

- snippet: "I have a question. Will this work with the iPhone 18 when it comes out cause I have the iPhone 16 Pro Max now and if I get it, it would be a waste of money if it doesn’t work with the iPhone 18 it will be. Waste of money"
  category: objection
  identity_tag: apple-design-loyalist
  behavioral_signal_tag: new-iphone-refresh
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Jessica S.", date: 2026-03-27, url: null}
  recurrence: 5
  source_diversity: [ad-comment]
  first_seen: 2026-03-27
  last_seen: 2026-04-15
  confidence: mixed
  brand_self_echo: false
  notes: "Fear of buying something that goes obsolete. Recurrence 5 = phone-model fit questions: this, Kellie G. 'Does work with any kind of iPhone basically my iPhone is 14', Cathy S.C. 'I phone 11? How many charges can it do?', Alice W. 'Any apple phone mines an 11', plus the Android pair counted separately. The iPhone 11 and older are not MagSafe; answer plainly. A Judge.me buyer now uses it on 'my iPhone 18 Max Pro' (2026-10-26), which resolves this one."

### Cluster: do I need another one

- snippet: "Do I need another charger?"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP6674", date: 2026-03-06, url: null}
  recurrence: 5
  source_diversity: [post-purchase-survey]
  first_seen: 2026-01-29
  last_seen: 2026-03-15
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 5 = #GP6674, #GP6878 'Already have another portable charger', #GP4507 'The fact that I have a portable charger already.', #GP7433 'Just wasn’t sure if I needed it yet', #GP7150 'Hesitation of another battery pack for my college kid.' Same buyer as #GP6674, Q3: 'The videos helped'. Underlying concern, inferred: one more gadget in a drawer of gadgets; the three-chargers-to-one message answers it."

### Cluster: colour and bundle choice

- snippet: "Was going to purchase the 2 pack, but didn’t see an option to choose the colors"
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: bundle-stock-up
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP5087", date: 2026-02-10, url: null}
  recurrence: 8
  source_diversity: [post-purchase-survey]
  first_seen: 2026-02-04
  last_seen: 2026-03-26
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 8 = Q4 colour answers, incl. #GP7325 'Ability to get different colors when ordering 2 for the discount.', #GP5707 'More color choices would be nice. I bought your two neutral colors. Would love to see orange and green options.', #GP8420 'Cost, limited colors'. Largely resolved since: mixed colours in bundles are now allowed and Cosmic Orange and Sage exist (verified on PDP and product feed by research pass)."

### Cluster: shipping and checkout

- snippet: "Payment link didn’t work"
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7386", date: 2026-03-15, url: null}
  recurrence: 4
  source_diversity: [post-purchase-survey, ad-comment]
  first_seen: 2026-01-21
  last_seen: 2026-03-15
  confidence: mixed
  brand_self_echo: false
  notes: "Checkout friction, not a creative problem. Recurrence 4 = #GP7386, #GP4951 'Payment method.', #GP4106 'Not seeing the SHOP option initially.', and FB Anna E. below."

- snippet: "Why do you not accept PayPal as it means of payment I would’ve bought these multiple times but the process is cumbersome and I have to put in a lot of information"
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: null
  source: {type: ad-comment, platform: Facebook ad comments, review_id: "Anna E.", date: 2026-03-06, url: null}
  recurrence: 4
  source_diversity: [ad-comment]
  first_seen: 2026-01-21
  last_seen: 2026-03-15
  confidence: mixed
  brand_self_echo: false
  notes: "Date approximate, 6w before capture. A would-be repeat buyer lost to checkout. Whether PayPal is now offered is data-limited. Routes to the brand."

- snippet: "If shipping had been too much, but $5 for two day shipping was reasonable."
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7868", date: 2026-03-20, url: null}
  recurrence: 5
  source_diversity: [post-purchase-survey]
  first_seen: 2026-03-04
  last_seen: 2026-03-25
  confidence: mixed
  brand_self_echo: false
  notes: "Recurrence 5 = shipping answers: #GP8282 'Shipping cost', #GP8259 'Shipping delay', #GP7375 'Shipping to Hawaii', #GP6532 'Cost and timing before trip', #GP7868. Shipping is now $9.99 on 1 or 2 units, free at $129 (verified on PDP by research pass), so this objection has likely grown."

### Cluster: size and the gift secret

- snippet: "At first glance, the PETL disc looks a little big, but I got past that."
  category: objection
  identity_tag: null
  behavioral_signal_tag: null
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP5330", date: 2026-02-15, url: null}
  recurrence: 3
  source_diversity: [post-purchase-survey, review]
  first_seen: 2026-01-13
  last_seen: 2026-03-11
  confidence: thin
  brand_self_echo: false
  notes: "Recurrence 3 = this, #GP7067 'I want a something light', website review 2026-01-13 'I would like it to be thinner and less weight like my other wireless power bank.' Same buyer's Q3: 'Tom's Guide gave PETL good ratings for ease-of-use when charging.' (stated, not checked)."

- snippet: "My husband coming into the room just before I submitted my order."
  category: objection
  identity_tag: no-fuss-family-keeper
  behavioral_signal_tag: gift-for-my-people
  source: {type: post-purchase-survey, platform: Shopify survey Q4, review_id: "#GP7459", date: 2026-03-15, url: null}
  recurrence: 1
  source_diversity: [post-purchase-survey]
  first_seen: 2026-03-15
  last_seen: 2026-03-15
  confidence: thin
  brand_self_echo: false
  notes: "Not a doubt about the product; the only thing that nearly stopped her was being caught buying a surprise gift. Same buyer's Q2: 'A convenient charger to charge my phone, watch, and AirPods.' and Q3: 'Didn’t shop a different brand.' Inferred: a woman buying for her husband in secret. A one-off, but a ready-made gifting scene."

## What the brand already answers, and what it does not

Inferred, from the concept list in internal-sources-digest.md, since ad copy was not pulled.
- **Price:** answered often, through bundle ladders, competitor price stacks, and "Yes It's Pricey" style concepts.
- **Capacity:** answered by PETL 2 Plus framing and Apple-pack comparisons.
- **Case:** answered inside some scripts ("no, you don’t need to take off the case") but no concept leads with it.
- **Trust and legitimacy:** almost no concept is briefed to answer it. The best-ROAS testimonial ad, PETL84 long copy at 2.04 to 2.15x (verified, META), is the closest.
- **Apple Watch fit:** cannot be answered cleanly until the claim is confirmed.

## Open loops

1. **Trust goes unanswered.** One in ten buyers nearly walked because they were not sure PETL was real, and the brand has no off-site proof. *Pull: Gap — a recurring barrier with no creative aimed at it.* **Question:** What would a first-time Facebook shopper need to see to believe PETL is a real company? *Justification:* If proof creative closes this gap, it may lift conversion more than another hook test. Territory: messaging.

2. **Price at $64.95.** Every price objection here was voiced at $49. *Pull: Tension — the survey says price is the top barrier, and the price has since gone up a third.* **Question:** How has the share of shoppers stopped by price changed since the August price rise? *Justification:* It decides how hard the creative should lean on bundle math versus value. Territory: product. Routes to the brand for a newer survey export.

3. **The case question stops non-buyers.** Four of 28 commenters asked about cases, but only one of 222 buyers did. *Pull: Surprise — the doubt is loud before purchase and nearly absent after.* **Question:** How many people leave PETL ads without buying because they think it won't work with a case? *Justification:* If many, a case-led demo is a cheap fix at the top of the funnel. Territory: messaging.

4. **The gift-giver's compatibility wall.** A wife asked whether PETL works on her husband's Android before buying him one. *Pull: Curiosity.* **Question:** How often do gift buyers find out the person they are buying for cannot use a PETL? *Justification:* In Q4 gifting, the iPhone-only fit is a hidden barrier that a simple "works with iPhone 12 and newer" line could clear. Territory: product.
