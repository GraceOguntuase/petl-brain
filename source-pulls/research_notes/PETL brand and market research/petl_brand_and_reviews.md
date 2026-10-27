# PETL: brand fact base and customer language

Pulled 2026-10-27. Labels: **[stated]** = the brand says it; **[verified]** = observed directly on the page or in the store's own data; **[inferred]** = reasoned from evidence; **[data-limited]** = could not resolve. Most product facts come from PETL's own site, so "verified" means "verified that the brand shows this," not that a claim is independently true.

Method note: gopetl.com rate-limited (HTTP 429) after a few fetches, and bulk review pulls from the Judge.me API were blocked by the session's permission rules, so I did not scrape the full review set. Parker MCP shows no accessible brands for this user (get_available_brands returned no organizations), so no Parker review export was used. The review section below rests on what the site displays plus the review distribution. A full export (Judge.me CSV from the brand, or Parker once connected) is the right next pull.

## Which brand is PETL?

### Takeaway
PETL is goPETL LLC (gopetl.com), a Florida-based DTC electronics brand founded in 2025 that sells a circular, MagSafe-compatible battery pack for iPhone, AirPods and Apple Watch. Its site has a 30-day return policy, which matches the NSY brief.

### Cited Findings
- The brand store is gopetl.com, operated by "goPETL LLC"; footer reads "PETL is not affiliated with or endorsed by Apple Inc." [verified] — [goPETL PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black)
- The refund policy says "you may return undamaged items within 30 days of delivery." [verified] — [Refund policy](https://gopetl.com/policies/refund-policy)
- PRWeb release (2026-09-14, Fort Lauderdale FL): PETL is a "Florida-based direct-to-consumer electronics brand, founded in 2025", sold exclusively at goPETL.com; CEO and co-founder Rakesh Guduru, Chairman and co-founder Muru Kannayan [stated] — [PRWeb](https://www.prweb.com/releases/petl-introduces-petl-2-plus-a-full-extra-charge-for-your-iphone-duo-in-a-5-000mah-magsafe-battery-302876149.html)
- A search summary placed goPETL LLC in Tamarac, Florida [stated, secondhand; I did not see the primary source] — [search result referencing gopetl.com](https://gopetl.com/pages/about-petl-magsafe-battery-pack)
- Other brands with similar names, not to be confused: Petzl (climbing gear, petzl.com), Petlas (Turkish tires), and a Multicomp Pro part code "PETL-20-BK100C" (cable sleeving) [verified in search results] — [Petzl](https://www.petzl.com/US/en/shop/policies), [element14](https://kr.element14.com/multicomp-pro/petl-20-bk100c/sleeving-braid-100m/dp/3223620)

### Inferences
- The brand is young (2025 founding) and moving fast: 10 colorways, a second-gen 5,000mAh model (Apr 2026) and a foldable-iPhone ("iPhone Duo") angle within about 18 months.

### Gaps
- Exact HQ city not confirmed from a primary source (the PRWeb dateline says Fort Lauderdale; the about page shows no address).

## Products, SKUs, prices, bundles, offers, guarantees, shipping

### Takeaway
Two battery packs (PETL 3,000mAh at $64.95, PETL 2 Plus 5,000mAh at $89.95) across 10 colors, plus two keychain cables. There are no struck-through list prices on single units; the discounting runs through quantity bundles (20/25/30% off), a 15% welcome code, and a post-add "second PETL" upsell.

### Cited Findings
Catalog from the store's public product feed, pulled 2026-10-27 [verified] — [products.json](https://gopetl.com/products.json); compare_at_price was empty on every variant:
- PETL MagSafe Compatible Battery Pack, 3000 mAh, $64.95: Black (listed 2025-01-01), Natural (2025-05-23), Sky and Lavender (2025-12-25), Sahara Gold and Blush Gold (2026-04-15), Sage (2026-05-15)
- PETL 2 Plus MagSafe Compatible Battery Pack, 5000 mAh, $89.95: Slate and Cosmic Orange (2026-04-15), Space Black (2026-07-02)
- PETL 2-in-1 Keychain Cable (USB-C & USB-A), $19.90 (2026-01-14)
- PETL 4-in-1 Keychain Cable (USB-C, USB-A, Lightning), $21.95 (2026-06-25)

Bundles on the PDP [verified] — [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black):
- 1 PETL "Just one": $64.95 + $9.99 shipping
- 2+ PETL "One for every bag": 20% off, $129.90 struck to $103.92 ($51.96/unit), "Save $25.98", + $9.99 shipping
- 3+ PETL "Keep extras or share", tagged MOST POPULAR: 25% off, $194.85 struck to $146.16 ($48.72/unit), free shipping
- 5+ PETL "Stock up & save", tagged BEST VALUE: 30% off, $324.75 struck to $227.35 ($45.47/unit), free shipping
- Mixed colors allowed; "Bundle discounts auto-apply"; section headline "MORE PETL. MORE POWER. MORE VALUE." with "The Perfect Present / One for every bag / One for the whole family"

Other offers [verified] — [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black), [homepage](https://gopetl.com):
- Upsell modal: "Add a 2nd PETL and get 20% OFF on total. Keep one for everyday use and one as a backup or gift, and save $25.98 - $35.98 on your order." Shown as "One-time offer · won't be shown again" / "Limited-time offer"; units shown at $51.96 (PETL) and $71.96 (2 Plus)
- Email pop-up: "Want 15% Off Your PETL?" code WELCOME15, decline button "No, I want to pay full price"
- Announcement bar: "Free US Shipping $129+", "Trusted by 100,000+ customers.", "Bundle & save up to 30%."
- "or 4 interest-free payments at checkout"
- Scarcity: "Sold out 7 times."; cart: "Items in your cart aren't reserved. PETL inventory sells out fast."
- Ship promise: "Ships same day. Order before 12 PM EST." with a delivery date estimate (showed "Oct 29 - 30" on 2026-10-27)
- No subscription offer found [verified absence on PDP]. Nav also lists "Corporate Gifts", "goPETL APP", and "Affiliates".

Guarantee, returns, warranty, shipping:
- PDP: "30-Day Risk Free Trial. Try it for 30-days, and if you don't like it for any reason at all send it back, no questions asked." Also "Hassle-free 30 day return." and cart line "30 days risk free trial • 1 year warranty" [verified] — [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black)
- Refund policy fine print: 30 days from delivery; item "in unused, resaleable condition with no visible signs of wear"; "Must include all original packaging, components, and accessories"; "Discounted or promotional bundles must be returned in full"; return shipping "$5.00 USD per return, deducted from the refund amount"; "Refunds exclude original shipping/insurance fees unless product is defective"; 0% restocking fee; Final Sale items excluded; bulk/corporate orders excluded [verified] — [Refund policy](https://gopetl.com/policies/refund-policy)
- Warranty: "1-Year Limited Warranty from the date of purchase" covering "defects in materials and workmanship under normal use"; replacements covered for the rest of the term or 90 days, whichever is longer [verified] — [Refund policy](https://gopetl.com/policies/refund-policy). The PDP FAQ says "12-month limited warranty covering manufacturing defects and normal wear and tear" [verified, wording differs from policy].
- Shipping: free on US orders over $129; standard 2-3 days; PO Box/APO/FPO via USPS 7-15 business days; sells in 30+ currencies (AU, CA, EU, UK, JP, IN, AE and more) [verified] — [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black)

### Inferences
- The "no questions asked" trial line and the fine print don't fully match: returns cost $5, exclude original shipping, require resaleable condition and full bundles. "Try it risk-free for 30 days" is accurate as a headline (matches Grace's 2026-09-25 confirmation), but "full refund, no questions asked" in a script would overstate it. Avoid promising free returns.
- With $64.95 under the $129 free-shipping line and a $9.99 fee, the 2-pack ($103.92) still pays shipping; the 3-pack is the first free-shipping tier. That's why 3+ is tagged MOST POPULAR. The bundle math is built to push AOV to 3 units.
- The "gift / one for every bag / one for the whole family" framing suggests gifting is a core use case, likely bigger in Q4.

### Gaps
- Whether struck-through pricing appears during sales events (BFCM) is unknown; none on 2026-10-27.
- Full shipping policy page not read (rate-limited).

## Claims, specs, certifications, proof points, founders, positioning, voice

### Takeaway
PETL sells design first: "World's First Circular MagSafe Compatible Battery Pack," coin-pocket size, aluminum and glass with "zero plastic," and "replace 3 chargers with 1." Proof leans on review volume, units/customers claims, certifications and three "tech expert" quotes; there are no press logos.

### Cited Findings
Headline claims [stated] — [homepage](https://gopetl.com), [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black):
- "World's First Circular MagSafe Compatible Battery Pack"; "Join over 100,000 PETL users"
- "Replace 3 chargers with 1 PETL." / "One PETL. iPhone, AirPods, Watch — charged."
- "One little charger. A lot less to carry."
- "Never see 1% again. 10+ hours, instantly." / "Never get caught at 1% again." (*"Based on internal testing with iPhone 16 under ideal network and ambient conditions."*)
- "PETL was built for the moments when your phone can't die—navigating, closing a deal, or capturing memories." / "This isn't just backup—it's peace of mind in your pocket."
- "Designed to Go. Built to Belong." / "Minimalism in motion." / "Made to match your Apple everything."
- "No apps. No setup. It just works." (shows in the iOS battery widget)
- "Most magsafe power banks add battery. PETL rethinks the whole charging experience."
- PETL 2 Plus: "The Most Powerful PETL Yet.", "A full extra charge on your phone", "Made for iPhone Pro & Pro Max", 67% more capacity and 50% more power (homepage)

Specs (Performance Guide, PDP) [stated]:
| | PETL (3000 mAh) | PETL 2 Plus (5000 mAh) |
|---|---|---|
| iPhone 16 Pro charge | 55% MagSafe / 77% USB-C | 92% MagSafe / 130% USB-C |
| AirPods | 3.4x / 4.7x | 5.7x / 7.9x |
| Apple Watch | 5.8x / 8.1x | 9.7x / 13.6x |
| Max output / input | 10W / 10W | 15W / 15W |
| Diameter / thickness / weight | 70mm / 14mm / 92g | 72mm / 16mm / 120g |
| Ideal for | Standard iPhone | iPhone Pro, Pro Max |
- Other stated features: N52 / "military-grade neodymium" magnets; CNC aluminum unibody + tempered glass, "Zero plastic"; passthrough charging over one USB-C port; LED ring 25/50/75/100%; StandBy/NightStand stand edge; thermal auto-throttle; patent-pending circular design; recharges in about 1.5-2 hours on 9V/2A; iPhone 12 and newer; "splash-resistant but not waterproof"; airline/TSA-compliant; new box packaging now includes a USB-C cable (older clamshell did not).
- Certifications: "CE • FCC • RoHS • UL Certified", plus WEEE on homepage [stated; certificates not verified]
- Comparison table vs "Others": circular design, coin-pocket size, multi-device, StandBy, native widget, aluminum vs "Cheap Plastic", thermal throttle vs none, N52 hold vs "Moderate hold" [stated]
- Proof stats: "Rated 4.81/5 · Over 1000+ reviews · Over 65,000+ units sold."; "Buyers come back. 70% buyers re-order in a second color."; "Loved by Tech experts. Compact, clean and a 'total game-changer.'" [stated]
- "Tech expert" quotes on PDP [verified as displayed]: Asher Mitilinakis, "Expert Tech Reviewer": "The smartest MagSafe battery I've ever used. One compact charger for my iPhone, Apple Watch, and AirPods—no extra cables, no extra clutter. It even works perfectly as a bedside charger." CJ, "Expert Tech Reviewer": "I stopped carrying three different chargers for three different devices. This tiny, sleek circular battery snaps on with MagSafe—no cables needed—and charges my iPhone, Apple Watch, and AirPods. It's fast, compact, and even doubles as a stand for StandBy mode at night. One clean little circle. Total game-changer." Claire Bacardi, "Tech Entrepreneur & Content Creator": "It's not just compact—it's thoughtfully designed. Circular, solid, and balanced, it stands on its own and feels great to use. One wireless charger for everything Apple."
- Homepage testimonial headlines [verified as displayed]: Nanette: "I don't carry bulky battery bricks anymore — I carry PETL." Nathan: "PETL - The only charger in my travel bag" CJ: "PETL charges all my Apple devices" Claire: "Low Battery Anxiety—Solved." Asher: "Best MagSafe Charger I've Ever Used." Sarah: "My Everyday MagSafe Battery." Marshel: "Premium Construction. Easy to Carry Anywhere." Anna: "Tiny and Super Portable. Ready to Go." Nate: "Easy to Carry Anywhere. PETL Is the Perfect Size." — [homepage](https://gopetl.com)
- Origin story (about page): the team saw that everyday carry already fills the main pockets (phone, keys, wallet, AirPods), leaving the coin pocket, and built a circular battery to fit it; factories called the round design impractical and pushed for square; the team reworked the internal layout and battery geometry until it worked. Founder "Rakesh G.": "People don't want more power. They want less friction in their pockets." Also: "PETL was never about easy. It was about earning its place." [stated] — [About](https://gopetl.com/pages/about-petl-magsafe-battery-pack)
- PRWeb (2026-09-14): PETL 2 Plus pitched as "engineered to deliver a full extra charge to the iPhone Duo," fits folded or unfolded, sits "without overhanging the hinge or edges"; Guduru: "We've shipped more than 80,000 units in our first year"; release also claims close to 100,000 units expected by end of 2026, August 2026 sales of $946,619, and about 30% month-over-month growth [stated, self-reported] — [PRWeb](https://www.prweb.com/releases/petl-introduces-petl-2-plus-a-full-extra-charge-for-your-iphone-duo-in-a-5-000mah-magsafe-battery-302876149.html)
- The brand blog runs heavy SEO content ("PETL Charger Reviews...", "Best MagSafe Power Bank 2026...", "PETL Reviews & Complaints: Is PETL Legit?") [verified in search results] — [blog example](https://gopetl.com/blogs/petl-magsafe-battery-pack-news/petl-reviews-complaints-honest-answers)
- A brand blog post admits the pack "is not the highest-capacity pack on the market, and that is by design" [stated, via search summary] — [blog](https://gopetl.com/blogs/petl-magsafe-battery-pack-news/introducing-petl-the-world-s-first-circular-magsafe-battery-pack)

### Inferences
- Positioning: a design object and everyday-carry upgrade for Apple people, not a max-capacity power bank. The competitive frame is "bulky plastic bricks" and "three chargers." Voice is clipped, confident fragments with an Apple-like cadence.
- The numbers conflict: "100,000+ customers" (site), "65,000+ units sold" (PDP), "80,000 units in first year" (PR). Customers can't exceed units sold unless the counts come from different dates. Safest claim for ads: "80,000+ units shipped" (founder, Sep 2026) or "1,400+ reviews at 4.8 stars." Flag "100,000+ customers" as unverified before using it.
- Homepage quote-givers CJ, Claire and Asher are the same people billed as "tech experts," so these read as creator/partner testimonials, not organic reviews.

### Gaps
- Certification documents and the patent-pending filing were not checked.
- No independent tech-press reviews surfaced; search results were almost all brand-owned pages.

## Social channels and press

### Takeaway
PETL links Facebook, X, Instagram and YouTube from its site; no TikTok link was found. Follower counts and top-performing content could not be pulled this session.

### Cited Findings
- Site social links: facebook.com/PETL.Official, x.com/gopetl, instagram.com/gopetl, youtube.com/@gopetl; hashtag "#goPETL" [verified] — [homepage](https://gopetl.com)
- Press: only the company-issued PRWeb release found; homepage shows no press logos [verified] — [PRWeb](https://www.prweb.com/releases/petl-introduces-petl-2-plus-a-full-extra-charge-for-your-iphone-duo-in-a-5-000mah-magsafe-battery-302876149.html)
- PDP has video modules ("Intro", "Unboxing", "3D", "Watch and see why customers love it") and "New premium packaging" [verified] — [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black)

### Inferences
- With no TikTok link on site, TikTok is likely run as paid-only (Spark/dark posts) through NSY, or under a handle not linked [inferred].

### Gaps
- Follower counts for IG/FB/YouTube/TikTok [data-limited: search returned nothing; the shared browser pane was in use by another task, and I did not open profiles].
- Influencer coverage beyond the three named "tech experts" [data-limited].

## What customers say

### Takeaway
On-site reviews are overwhelmingly positive (86% five-star, about 1% one-star) and talk about the size, the look, carrying one charger for all Apple devices, and charging through a case. The brand's own complaints article names the three objections: small capacity, warmth while charging, and the return process. Off-site review volume is near zero.

### Cited Findings
Review volume and ratings by platform [verified unless noted]:
- Judge.me (site widget): shop-wide 1,454 reviews, average 4.83 (from page data attributes, 2026-10-27); homepage copy "4.8/5 based on 1,454 reviews" and "1450+ Verified Reviews" — [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black), [homepage](https://gopetl.com)
- PETL product-group widget, "Based on 1382 reviews": 5★ 86% (1,188), 4★ 13% (173), 3★ 0% (6), 2★ 0% (5), 1★ 1% (10) — [PDP](https://gopetl.com/products/petl-magsafe-battery-pack-black)
- Trustpilot: claimed profile (Jun 2025), 0 reviews, "This company hasn't received any reviews yet." — [Trustpilot](https://www.trustpilot.com/review/gopetl.com)
- Amazon: no official listing found; PR says goPETL.com is the only channel. Newegg/Walmart listings appeared in search but weren't confirmed as PETL; one Newegg reseller listing says "please contact the Seller directly for warranty information" [data-limited] — [Newegg](https://www.newegg.com/p/0S9-024S-00009)
- Reddit, Google, TikTok/IG comments, YouTube comments: none retrieved [data-limited]. The brand blog says shoppers have "probably landed on a Reddit thread or AI summary highlighting three concerns" [stated] — [blog](https://gopetl.com/blogs/petl-magsafe-battery-pack-news/petl-reviews-complaints-honest-answers)

Verbatim reviews shown on the site (Judge.me, United States, all 5★; exact text including typos) [verified] — [PDP](https://gopetl.com/products/petl-2-plus-magsafe-compatible-battery-pack-space-black):
- Gregory Harrod, 2026-10-27, 5★: "Love the PETL 2 Plus MagSafe"
- A Burrell, 2026-10-26, 5★: "I am enjoying my new PETL 2 Plus for my iPhone 18 Max Pro .  It is always available to attach to the back of my phone when it needs charging.  Thank you again for the amazing battery pack!   A Burrell"
- Anonymous, 2026-10-26, 5★: "Device works as promised. Loved the 5000 mAmp capacity....though with the batteries of new devices a 10k would be great!"
- Dario Sanchez, 2026-10-26, 5★: "very sleek look and very convenient for for what it does. multiple chargers in one."
- Marc Grobman, 2026-10-26, 5★: "Compact, charging through my case, elegant."

Themes (from the quotes above, the homepage testimonials, and the brand's complaints article):
- **Reasons they bought / delight:** sleek, elegant look; compact; "multiple chargers in one"; works through a case; always there to snap on. Homepage lines carry the same: "I don't carry bulky battery bricks anymore — I carry PETL.", "The only charger in my travel bag", "Low Battery Anxiety—Solved."
- **Before-state pains (brand framing plus testimonials):** bulky battery bricks, carrying three chargers, tangled cables, hitting 1%, being tied to a wall outlet.
- **Results:** "Device works as promised"; always-available top-up; one device for iPhone, Watch and AirPods.
- **Complaints / objections:** capacity, from a happy 2 Plus buyer: "a 10k would be great!" Brand-acknowledged concerns: "the 3,000 mAh capacity feels small compared to traditional power banks," the pack "gets warm during wireless charging," and "concerns about the return process" [stated] — [blog](https://gopetl.com/blogs/petl-magsafe-battery-pack-news/petl-reviews-complaints-honest-answers)
- **Return reasons:** not observed [data-limited].

### Inferences
- The 3,000mAh pack gives about 55% of an iPhone 16 Pro by MagSafe (brand's own figure), so "a full charge" claims should go only on the 2 Plus (92% MagSafe on a 16 Pro). The capacity objection is real and should be handled head-on with "top-up, not a brick" framing.
- The 1,454 shop-wide vs 1,382 product-group counts are consistent (the group excludes cables or some SKUs) [inferred].
- Heavy 5★ skew and zero off-site reviews mean social proof in ads should lean on on-site rating and volume. There's no Trustpilot or Amazon proof to borrow.
- "Concerns about the return process" plus the $5 fee and condition rules point to a likely friction point; keep guarantee copy to "30-day risk-free trial."

### Gaps
- The roughly 21 one-to-three-star reviews and most of the 1,454 review texts were not read. Best fix: ask PETL or NSY for a Judge.me CSV export, or connect Parker reviews.
- No Reddit, TikTok, Instagram, YouTube or Google review language captured.
- Return reasons and rates not available publicly.
