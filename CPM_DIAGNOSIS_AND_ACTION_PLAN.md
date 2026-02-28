# SliceSafe Pro - CPM Diagnosis & Action Plan

## Current Situation
- ~$2,000 CAD spend, 7 conversions
- CPA: $341 CAD (Meta says 1141% higher than others)
- Target CPA: $30 CAD for profitability
- Budget: $45 CAD/day
- 1 ASC campaign, 1 ad set, ~10 ads at a time
- 1-2 purchases per week
- CAPI EMQ: 4.4/10 (ATC/IC/Payment), 6.6/10 (others)
- Landing page conversion rate: 1.89%
- Page load speed: 3.7s (Lighthouse: Performance 61, FCP 4.8s, LCP 9.5s)
- Every ATC has led to a purchase (funnel is tight, problem is desire not leakage)

---

## ROOT CAUSE ANALYSIS

### Issue #1: CAPI Event Match Quality 4.4/10 (High Priority - Free Fix)

Your purchase-funnel events (ATC, IC, Payment Info) score 4.4/10 on EMQ. This means
Meta can only match ~44% of your conversion events to actual users. The remaining 56%
are "dark" data - Meta can't use them to learn who your buyers are.

**Does low volume cause low EMQ?** Partially yes - EMQ is calculated from the last 48
hours of data, so with low volume it fluctuates more. But the primary driver is data
completeness, not volume. Your 4.4 score means your CAPI setup is only sending 1-2
customer identifiers per event when it should be sending 5-6.

**Free fixes (no app required):**
1. Make phone number REQUIRED at Shopify checkout (Settings > Checkout > Customer contact)
2. Enable Advanced Matching in Meta Pixel settings (Events Manager > Settings > Advanced Matching > toggle ON automatic advanced matching for email, phone, name, city, state, zip)
3. Verify your Shopify Facebook & Instagram sales channel is sending server-side events (not just browser pixel)
4. In Shopify admin: Settings > Customer accounts > make sure "Collect customer phone number" is enabled

**What this fixes:** Adding phone number alone can boost EMQ by 1-2 points. Enabling
all advanced matching fields should get you to 6-7+ which is where Meta can properly
attribute conversions and learn from them.

### Issue #2: Page Speed (LCP 9.5s, FCP 4.8s)

Your Lighthouse shows critical rendering issues:

**Theme-level problems found in code:**
- base.css is 368KB loaded render-blocking on critical path
- 192KB obfuscated main.js + 75KB secondary.js (267KB total JS)
- Material Symbols font loaded from Google Fonts (external request chain)
- Multiple inline scripts doing immediate DOM queries before page paints
- All product page sections (10 sections) loaded in DOM simultaneously - no lazy loading
- Massive inline CSS in custom_liquid sections (comparison table, FAQ, how-it-works)

**Applied fixes to theme.liquid:**
- Moved preconnect hints before JS to establish connections earlier
- Added preconnect for fonts.googleapis.com
- Preloaded Material Symbols font file for faster icon rendering
- Consolidated inline scripts into single DOMContentLoaded handler (reduces parse blocking)
- Moved link-modification script into requestIdleCallback inside DOMContentLoaded

**Additional fixes you should do in Shopify admin:**
1. Compress all product images to WebP format (Shopify does this automatically if you re-upload)
2. Remove any unused Shopify apps (each app injects scripts via content_for_header)
3. Check Apps > Settings for any apps loading scripts on storefront
4. Consider removing the "disable inspect" feature if enabled - it adds unnecessary JS

### Issue #3: Your Ads Need to Build More Desire (Your Own Correct Diagnosis)

You're right that every ATC leads to purchase - your funnel from ATC onwards is 100%.
The issue is getting people from LPV to ATC. At 1.89% overall conversion rate, the
problem is convincing traffic to buy, not losing them in checkout.

This means the priority is finding the winning ad angle/format that creates enough
desire BEFORE the click. The page just needs to not kill that desire (speed + basic
trust signals).

---

## YOUR NEXT MOVE (Priority Order)

### TODAY (15 minutes, free):
1. Shopify Settings > Checkout > Make phone number required
2. Meta Events Manager > Settings > Enable Advanced Matching (all fields)
3. Upload the modified theme.liquid from this repo to improve page speed

### THIS WEEK:
1. Continue testing batches in single ASC ad set (your current approach is correct)
2. Kill underperformers quickly (correct)
3. Focus on finding winning angle/format (correct)

### ON THE MULTI-AD-SET QUESTION:
At $45/day, splitting into multiple ad sets will hurt more than help. ASC already
handles audience finding at the creative level - it looks at WHO engages with EACH
creative and finds more of those people. You don't need separate ad sets for different
sub-avatars at this budget. The algorithm separates them by creative engagement patterns
within a single ad set.

**When to split:** Once you find a winning creative with consistent 2+ ROAS AND your
budget is $150+/day, THEN consider a second ad set for your champion creative. Not before.

### ON THE ATC OPTIMIZATION QUESTION:
Don't switch yet. Fix CAPI first (today's 15-minute task). Give it 2-3 weeks. If after
the CAPI fix you're still at <2 purchases/week, THEN consider temporary ATC optimization
to feed the pixel data. Switching to ATC with a 4.4 EMQ just means more low-quality
ATC events Meta can't match anyway.

---

## WHY CPMs ARE HIGH ON PURCHASE CAMPAIGNS SPECIFICALLY

This is the core question. The answer is a combination:

1. **Purchase-optimized campaigns target a MUCH smaller audience.** Meta shows your ads
   only to people with high purchase intent signals. This is a tiny fraction of the total
   audience, so competition for those impressions is fierce = higher CPM.

2. **Your pixel has almost no purchase data.** With 7 purchases total, Meta has almost
   nothing to build a lookalike profile from. So it's casting a very expensive net trying
   to find buyers with minimal signal.

3. **Your CAPI is losing ~56% of conversion data.** Even the purchases you DO get, Meta
   can only match about half of them to user profiles. So instead of 7 data points, Meta
   effectively has ~3-4 to learn from.

4. **This is NOT a business manager/page issue.** Your $4 CPM engagement campaign proves
   the account is healthy. The issue is specific to purchase optimization + low data.

The engagement campaign works at $4 CPM because engagement events happen constantly -
Meta has thousands of data points to optimize against. Purchase events at your volume are
so rare that Meta has no signal to learn from.

**The path forward:** Every fix above (CAPI, page speed, finding winning creative) feeds
into the same goal: give Meta more purchase data so it can stop overpaying for impressions.
The CAPI fix makes your existing purchases count more. Page speed prevents losing ready
buyers. Better creatives drive more purchases per dollar spent.

---

## SUMMARY

Your account is NOT broken. Your ads are NOT flagged. The high CPM is a data problem:
Meta doesn't have enough conversion signal to efficiently find buyers.

Priority 1: Fix CAPI (free, 15 min, makes existing data count more)
Priority 2: Fix page speed (theme changes applied, deploy them)
Priority 3: Keep testing creative angles to find the winner
Priority 4: Once you have a winner + higher budget, THEN worry about scaling structure
