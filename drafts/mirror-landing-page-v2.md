# The Mirror — Facebook Test: Landing Page + Ad Copy — v2

Draft v2 — Sloan, 2026-09-12
Status: DRAFT. Copy only. Responds to Ed's first compliance pass on v1. NOT yet
re-reviewed by Ed. NOT approved for publication or spend. Send this back to Ed before
it goes anywhere near Justin.

v1 is preserved in full at the bottom of this file (APPENDIX) for the record — nothing
in v1 was deleted, only superseded where Ed flagged it.

---

## v2.1 — entity/registration correction, 2026-09-12
Justin corrected a factual error running through every disclosure block drafted so
far: Trulip Retirement Planning is **not** an SEC-registered investment adviser.
Justin is an investment adviser representative (IAR) of **Portfolio Medics, LLC**,
the actual SEC-registered adviser; Trulip is the insurance/planning entity. This
pass corrects the top disclosure notice (Section 1), the v2 change-note describing
it below, and applies Justin's resolved placeholder facts: "Justin [Last Name]" →
**Justin McGuffey**; no license numbers, NPN, or CRD printed (Justin's decision);
Trulip Retirement Planning, LLC confirmed as the FMO (no separate agency entity;
resolved 2026-09-16 — the FMO is "Trulip Planning," marketed as "Trulip Retirement
Planning," printed line kept as on his client-facing footer). The ad-unit entity naming question (Section
"THE AD" below) is addressed explicitly — see that section. Nothing about the
five questions, scoring key, CTA mechanics, or targeting/metric plan changed. See
Ed's report to Isla/Justin (2026-09-12) for the full geofence analysis this
correction triggered — it bears directly on this piece, since it's the one paid,
targeted piece reviewed so far.

## CHANGELOG — v1 → v2 (Ed's first-pass compliance notes)

**1. All three ad variants — same fixes, applied to each:**

- **(a) Bucket-specific language stripped.** "Money that can't lose value" and "a plan
  for the downside" are the exact phrases tied to claims-paying-ability and
  design-vs-outcome qualifiers that live in the disclosure block — a 30-word ad can't
  carry those qualifiers, so the ad now describes the concept generically ("three
  basic kinds of retirement money") without naming what the three are. The naming and
  the qualifiers both move to the landing page, which is built to carry that load.
  Variant A needed the most rework, B the second most, C (already generic) got a
  lighter touch.
- **(b) Every "most people..." line cut.** "Most people we talk with have two of the
  three," "most people who answer them realize" — both gone, no replacement
  statistic substituted. Also caught on my own read, not explicitly flagged by Ed but
  the same construction: Variant A's original headline, **"Most Retirement Plans Are
  Missing One Piece,"** made an unsubstantiated general-population claim about
  retirement plans, not just people — same problem, different noun. Rewrote as a
  question instead of an assertion. Flagging this explicitly so Ed can confirm the fix
  reads right to him rather than assuming it's fine because it wasn't the line he
  named.
- **(c) Entity named in every ad unit.** All three variants now name Edify Retirement
  Education / Trulip Retirement Planning directly in the ad copy. Producer-ID-travels-
  with-the-ad question is still with counsel — naming the entity is the conservative
  default in the meantime, per Ed's call.
- Fear/outcome/urgency/"your advisor" language — unchanged, already clean.

**2. Two new disclosure notices added, per Ed's placement call:**

- **Top notice** — new, directly beneath the Section 1 hook, before the five
  questions: dual registration (Portfolio Medics, LLC as the SEC-registered
  investment adviser; Justin as its IAR and as a licensed insurance producer in
  OH/KY; Trulip Retirement Planning as the insurance/planning entity — corrected in
  v2.1, see above), "educational only, not individualized advice," and a pointer
  down to the full disclosure block. **Note on length (v2.1):** naming two entities
  correctly instead of one takes more than the original two sentences. Flagging
  this as a real design tradeoff, not a copy nicety — Sloan/Justin should confirm
  the notice still reads as "small, quiet type" beneath the hook rather than a
  second block competing with it, once built.
- **Button notice** — new, inside Section 4 immediately below the CTA button:
  action-oriented ("this books a free educational conversation, not a solicitation")
  plus the same pointer to full disclosures. Placed at the exact moment the reader
  decides to act, same logic as a card-reader checking boxes.
- **Section 6 (bottom disclosure block)** — unchanged in content, but now explicitly
  marked **"always rendered — no accordion, no click-to-expand."** Ed ruled out a
  collapsible section; adding the marker so whoever builds this in Squarespace doesn't
  default to one.

**Untouched, per scope:** the five questions, the scoring key, Justin's close. Cleared
by Ed in the first pass, not re-opened here.

---

## THE LANDING PAGE (v2)

One page. One job: a booked meeting. Nothing on this page should compete with that.

### Section 1 — Hook (reused from card FRONT panel, verbatim — unchanged)

> **Two Minutes. Five Questions. Your Own Money, In Your Own Words.**
>
> You don't need to know anything about investing to answer these. You just need to
> know your own accounts. There's no right answer to any of them — just yours.
>
> Answer yes or no.

**[NEW — top disclosure notice, directly beneath the hook, before the five questions
— corrected in v2.1]**

> *Investment advisory services are offered through Portfolio Medics, LLC, an
> SEC-Registered Investment Adviser. Insurance and planning products are offered
> through Trulip Retirement Planning, LLC. Justin McGuffey is an investment
> adviser representative of Portfolio Medics and a licensed insurance producer in
> Ohio and Kentucky. This page is educational only and isn't individualized
> advice — full disclosures are below.*

Small, quiet type — a notice, not a second headline. It sits between the hook and the
five questions so a reader who never scrolls to Section 6 still saw it, but it isn't
sized or weighted to compete with "Two Minutes. Five Questions."

### Section 2 — The five questions (verbatim from card, required reuse — unchanged)

1. Do you have money in a savings account, a CD, or an annuity that's set up so the
   original amount you put in can't go down?
   Yes / No

2. Could you get to some of that money within a few days if you needed it — without
   a penalty, and without asking anyone's permission?
   Yes / No

3. Do you have a 401(k), 403(b), or an IRA left over from a job you don't work at
   anymore?
   Yes / No

4. The last time the market dropped sharply — 2022, 2020, 2008, whichever you
   remember — did any of your account balances drop right along with it, with
   nothing in place to limit how far they fell?
   Yes / No

5. Right now, could you name one part of your retirement savings that's invested
   for growth but has a specific plan in place designed to limit how much it could
   lose in a bad year?
   Yes / No

**Interaction spec (unchanged):** if Squarespace's form/quiz block supports simple
tappable yes/no toggles with no submission, no email field, and no computed output,
use that. If that requires a plugin, a third-party embed, or anything that captures
answers server-side, don't use it — present the five questions as clean, readable
static text instead. **Hard constraint either way: no tallying, no running score, no
"you answered 3 yes" counter anywhere on this page.**

### Section 3 — Scoring key (verbatim from card BACK panel — unchanged)

> **Here's What People Usually Find**
>
> For each question you answered "yes," check the matching box below.
>
> - Yes on Q1 or Q2 → **Money that can't lose value**
> - Yes on Q3 or Q4 → **Money from an old job, moving on its own**
> - Yes on Q5 → **Money that's managed with a plan for the downside**
>
> There's no wrong picture here — just yours.

No score. No verdict. No adjectives applied to the reader's situation. The reader
does the matching, on their own, same as on paper.

### Section 4 — The one CTA

**[ADAPTED — flagged for Ed, unchanged from v1]** The card's CTA paragraph assumes the
reader is holding the physical card. Adapted for a page serving both ad-clickers and
QR-code mail recipients; everything else in this paragraph is unchanged from the card:

> If you'd like to talk through what you found — all three boxes, two, or just one —
> here's how. It's a free conversation, about twenty minutes, no obligation, and no
> pitch. Bring your answers — on this screen, on a printed card, or just in your head.

**[ ⬤ Book the Free 20-Minute Conversation ]** → links directly to Justin's booking
calendar. [CALENDAR URL — PLACEHOLDER, needs Justin's real link]

**Booking page — Calendly build spec (Isla, 2026-09-16).** Justin uses Calendly.
It clears Ed's five conditions on a paid tier, configured as follows; the free tier
does not clear the first one.
1. **Records the firm can pull.** Paid tier (Standard or above) with booking export
   enabled; export bookings to Trulip's 204-2 file on a schedule, don't rely on
   Calendly's retention.
2. **State of residence.** A required custom question on the booking form: "What
   state do you live in?" (short answer, required). Justin screens anyone outside
   Ohio or Kentucky before the meeting — Meta's location targeting leaks.
3. **Pointer line.** Event description reads: "A free, educational, twenty-minute
   conversation — no pitch, no obligation. For Ohio and Kentucky residents. Full
   disclosures on the page you came from."
4. **Transactional confirmations only.** Confirmation and reminder emails/texts
   carry date, time, location/link, and how to reschedule. Nothing else — no
   content, no links to other pages. Turn off any marketing-style follow-up.
5. **Attribution.** Two event links (or one link with UTM parameters passed
   through): one for the FB landing page button, one for the mailed card's QR code,
   so bookings can be told apart by source.
Ed's rule from the box still applies: the booking page is its own advertisement
and gets its own log entry when it goes live.

**[NEW — button notice, immediately below the CTA button]**

> *Booking this call schedules a free educational conversation — it isn't a
> solicitation or an offer of specific advice. Full disclosures below.*

Small type, directly under the button — the equivalent of the moment a card reader
decides to check a box. Not a barrier to clicking, just present at the decision point.

That is the only button on the page. No secondary link, no "or watch this video
first," no "download the guide," no email field anywhere above or below the button.

### Section 5 — Justin's close

**[ONE WORD ADAPTED — flagged for Ed, unchanged from v1]**

> I built this because most people don't get shown a clear picture of their own
> retirement money until they're already sitting across the table from an advisor.
> This page is that picture, without needing the meeting first.
>
> — Justin McGuffey
> Trulip Retirement Planning / Edify Retirement Education

*(Note: this line, "most people don't get shown a clear picture...," is Justin's own
voiced opinion in his signed close, not a factual population claim presented as
Edify's — different register from the ad copy's "most people" lines Ed flagged.
Leaving it as-is since it wasn't in scope this round, but flagging for Ed to weigh in
explicitly given the standing rule, rather than assuming the distinction holds without
his sign-off.)*

### Section 6 — Disclosure slot

**[DISCLOSURE BLOCK — ALWAYS RENDERED. Per Ed's placement call: full block, unabridged,
visible at all times. No accordion, no "important information" expandable section, no
click-to-expand of any kind. Whoever builds this in Squarespace should treat this as a
hard requirement, not a design default to override.]**

Base text is the disclosure block already drafted in `drafts/mirror-card-v2.md`
(the "Disclosures" section — **corrected in that file's v2.1 pass, 2026-09-12: the
Portfolio Medics/Trulip two-line advisory-and-insurance structure, insurance
license lines without a printed license number per Justin's decision, the
principal-protection/carrier-guarantee paragraph, and the split advisory/insurance
"not an offer or solicitation" line**). Of the original six placeholder facts,
five are now resolved (name, license numbers/NPN/CRD omitted by Justin's decision,
FMO entity confirmed as Trulip itself); the sixth resolved 2026-09-16 (see change
log). Justin also confirmed Edify is correctly described as Trulip's educational arm. This block now sits alongside the two new short-form notices above
(Sections 1 and 4) as a three-layer disclosure structure: short notice at the
hook, short notice at the CTA, full block always visible at the bottom. Ed
confirms the three still work together as intended with the corrected entity
names — nothing in the two short notices contradicts or duplicates the full block
awkwardly.

---

## THE AD (v2)

Job of the ad is narrow: earn a click from someone who isn't expecting to be sold
anything. Not the booking, not the explanation — just the click. The landing page
carries the rest, including all bucket-specific language and the full disclosure load.

**Entity name in the ad unit — Ed's call, v2.1:** all three variants below still
name "Edify Retirement Education / Trulip Retirement Planning," not Portfolio
Medics. That's deliberate, and it stays that way. Two reasons: (1) this precedent
was already set for the mailed card — Portfolio Medics was kept off the mailer on
purpose because naming the RIA program pulls in performance-disclosure machinery
disproportionate to a short piece; the same logic applies more strongly to a
30-word ad, which has even less room to carry what naming an SEC-registered
adviser by name typically requires alongside it. (2) Edify/Trulip are the
consumer-facing brand identifiers used everywhere else in this piece (the mailed
card, the correction email) — naming Portfolio Medics only in the ad unit, and
nowhere else, would be inconsistent without a reason to be. The substantive
registration disclosure (Portfolio Medics as the SEC-registered adviser, Trulip as
the insurance/planning entity) lives where it belongs: the landing page's top
notice and full disclosure block, which are built to carry that load. The
producer-ID-travels-with-the-ad question is still with counsel per the standing
open item below — this call doesn't resolve that, it just keeps the conservative
default in place.

**Facebook button:** unchanged — "Learn More," not a commitment verb.

### Variant A — plain naming of the gap

**Headline:** Three Kinds of Retirement Money — Do You Have All Three?

**Primary text:**
There are three basic kinds of retirement money. Five short questions about your own
accounts — nothing else — show you which ones you have, and which you might not.
Takes about two minutes. No email required.
*Edify Retirement Education / Trulip Retirement Planning*

*(Was: "Most Retirement Plans Are Missing One Piece" headline + named buckets +
"most people we talk with have two of the three." Rebuilt as a question, generic
concept only, entity named.)*

### Variant B — question-led

**Headline:** Which of the Three Do You Have?

**Primary text:**
Retirement savings usually falls into three basic categories. Five quick yes/no
questions about your own accounts show you which of the three you're sitting on, and
which one you may have never gotten around to. Two minutes, no score, nothing to sign
up for.
*Edify Retirement Education / Trulip Retirement Planning*

*(Named buckets removed, "usually falls into three basic categories" kept generic,
entity named. Headline was already a question — no claim to fix.)*

### Variant C — quiet, low-key register

**Headline:** Five Questions About Your Own Retirement Money

**Primary text:**
No pitch, no score, nothing to download — just five short questions about your own
accounts, built around three basic pieces of a retirement plan. Takes about two
minutes, and it's yours to keep either way.
*Edify Retirement Education / Trulip Retirement Planning*

*(This variant was already closest to generic — only fix needed was cutting "most
people who answer them realize" and adding the entity name.)*

All three stay inside the same register on purpose: no fear language, no "protect
your retirement," no claim about outcomes, no urgency device, no unsubstantiated
population claim of any kind — general-noun or "most people" construction alike.

---

## TARGETING (v2.1 — rebuilt for Meta Special Ad Category, 2026-09-12)

**Why this section is being rebuilt, not tweaked:** Justin has confirmed from direct
experience that Meta requires Special Ad Category declaration for financial-services
ads, and that it strips the exact targeting v1 asked for (age band, income floor, zip
codes). The v1 targeting plan below in the APPENDIX is not achievable on this platform
as written — this replaces it rather than annotating it.

**Sourcing note, stated plainly:** Meta's own primary pages (transparency.meta.com,
facebook.com/business/help) were unreachable from here — both domains are blocked by
the network egress proxy I have access through. Everything below is cross-corroborated
across several independent secondary sources rather than read off Meta's own text
directly: Data Axle, *"The 2025 Meta Special Ad Categories Rules You Need to Know"*;
WOLF Financial, *"Meta Ads Financial Services Restrictions and Strategic Targeting
Workarounds"*; benly.ai, *"Meta Ads for Finance & Insurance: Compliant Strategy Guide
2026"*; and several ad-tech/agency posts on the enforced minimum radius and 2025
customer-list restrictions (all consulted 2026-09-12). Multiple independent sources
agree on every point below, which is why I'm treating it as reliable — but it is
secondary-source information, not a citation of Meta's own policy text, and whoever
builds the ad account should confirm each item against what Ads Manager actually shows
at campaign-creation time before spending a dollar. Where I couldn't get corroboration
(e.g., the exact current minimum radius figure had one outlier source saying
state-only, versus several more specific sources citing a 15-mile/25km floor around a
pin), I've flagged it rather than picked the more convenient number.

**In scope, confirmed:** Meta expanded its "Financial Products and Services" Special Ad
Category in 2025 to cover banking, savings, insurance, and investment services, not
just credit/loans — mandatory for US advertisers running these campaigns. An ad from
an IAR of an SEC-registered adviser (Portfolio Medics, LLC) who is also an OH/KY
insurance producer, promoting a conversation about retirement accounts, is squarely
inside this. Not a gray area, and consistent with Justin's own experience.

**What's removed:**
- Age targeting narrower than a broad 18–65+ bucket. No 55–70 band — the DRA list's
  actual age criterion is not settable here.
- Gender targeting — must run to all genders.
- Zip-code and neighborhood-level location — disallowed outright, no exceptions.
- Location exclusions of any kind — you cannot carve an area back out of a selected
  region once it's in.
- Household income and most detailed/interest-based demographic targeting — there is
  no way to set a $250K+ household income floor on this platform for this category.
- Lookalike Audiences and Meta Advantage+ targeting expansion built on Meta's own
  behavioral data.
- As of a January 2025 policy tightening: customer-list audiences shared in from
  another business portfolio, and customer lists sourced from a data broker/consumer-
  reporting provider — not relevant here since we'd do neither.

**What remains:**
- Location by city, address, or dropped pin, at an enforced minimum radius —
  reported consistently (though not primary-sourced, see above) as 15 miles (25 km) in
  the US. State- and metro/DMA-level targeting also remain as broader alternatives.
- A reduced set of broad interest/topic categories — expect most finance-adjacent
  interests to be grayed out; confirm what's actually selectable in-account rather
  than assuming any particular one survives.
- Custom Audiences — **not part of this plan (2026-09-16).** Sources reported them
  as still permitted from a directly uploaded first-party list, but Justin's own
  experience with this account under the category is that they aren't available.
  The test is built without them; if one turns out to be available later, uploading
  his client list to Facebook is still his explicit, separate call.

**Verification and disclosure — operational, needs an owner, not copy:**
- Advertiser/business identity verification is required, including demonstrating
  authorization by the relevant regulator — in our case Justin's OH/KY insurance
  producer license, since the advertiser is Edify (see below). Sources recommend starting this two-plus weeks
  before intended launch; it can involve a mailed verification code and, in some
  reports, notarization. This is a real launch-timeline item independent of copy
  readiness — flagging so it starts now if it hasn't. **Decided 2026-09-16 (Justin):** the
  advertiser on Meta is Edify, on the existing Edify page and ad account; Portfolio
  Medics is not involved in the Meta account. Separate question, still on Justin's
  list: whether Portfolio Medics must pre-approve the landing page copy itself, since
  it names them in the disclosure.
- Meta now requires a "Paid for by" disclaimer on financial-services ads, naming the
  verified payer/beneficiary, shown in the ad's "Ad info" and in the public Ad
  Library. This is a platform-generated label from verification data, not ad copy —
  separate from Ed's disclosure block on the landing page, but worth surfacing as a
  distinct to-do for whoever sets the ad account up.

**Geography — built for OH/KY, Cincinnati/NKY metro** (per Isla's working assumption;
Ed separately reconciling the exact geofence against Justin's IAR status, insurance
side staying OH/KY regardless):

With zip-level precision gone, the closest legal proxy for "Cincinnati/NKY" is one or
two city/address pins at the enforced minimum radius — e.g., a pin on downtown
Cincinnati and a second on Covington/Florence, KY, so the radius reaches NKY's inner
counties rather than one circle stretched thin. This is wider than the DRA list's zip
footprint, not narrower, and there's no way to tighten it back down.

One specific thing worth flagging rather than assuming away: a 15-mile radius from
downtown Cincinnati likely reaches into southeastern Indiana (Dearborn County /
Lawrenceburg) — Meta doesn't allow excluding it back out once it's in the circle.
Justin's insurance license is OH/KY only. Whether a handful of stray Indiana
impressions on an ad that only books an educational conversation (no product named, no
state-specific insurance solicitation in the ad copy itself) is immaterial or a real
compliance flag is Ed's call — surfacing it now rather than after the campaign is live.

**If the advisory-side footprint ends up wider than OH/KY** once Ed's geofence
reconciliation lands: the mechanic here doesn't change, only the pin count — add more
city-center pins (Columbus, Louisville, wherever) each carrying the same minimum-
radius floor. Additive, not a rebuild.

**Creative-as-targeting — since the platform won't filter by age or income, the copy
has to do some of that work:**

The only lever left to approximate "55–70, $250K+ household" is the ad content itself
doing the self-selecting, Godin/Miller-style: someone outside the intended reader
doesn't recognize themselves in the questions and scrolls past, rather than the
platform declining to show them the ad in the first place. The current three variants
already do some of this by accident — "an old 401(k) or IRA from a job you don't work
at anymore," a market drop "in 2022, 2020, 2008, whichever you remember," and "a plan
in place to limit how much it could lose" are account-type and memory cues someone
decades from retirement, or without meaningful retirement savings, doesn't have a
foothold in. That's the honest proxy for the income floor too — topic specificity
about holding multiple account types, not a dollar figure we couldn't defensibly claim
in ad copy regardless of what Meta allowed.

Where I'd add one more cue: none of the three headlines signal life stage at all right
now — they'd read the same to a 30-year-old as a 62-year-old. I'd add a short
life-stage qualifier to the *primary text* (not the headline) of all three variants —
something naming life stage, not a number. This matters as a real distinction, not a
style preference: Meta's ad review actively looks for copy that tries to route around
a Special Ad Category's removed targeting (an explicit "55 to 70" or a dollar figure
in the ad text reads exactly like that attempted workaround, and can get an ad
rejected or throttled) — a life-stage phrase doesn't have that problem, a number does.

**Concrete proposed edits below — draft only, needs Ed's pass; any copy change
re-opens his review, full stop:**

- **Variant A**, end of primary text: append "— worth five minutes if retirement is a
  handful of years away, not decades" before "Takes about two minutes."
- **Variant B**, end of primary text: append "— most useful if retirement's closer
  than it used to be" before "Two minutes, no score, nothing to sign up for."
- **Variant C**, end of primary text: append "— aimed at anyone within a few years of
  retirement, not just curious about the topic" before "Takes about two minutes."

I'm not confident these are the final phrasing — they're a first pass at the
mechanic, not a finished set, and Ed should scrutinize them exactly as hard as any
other new line (do they read as a claim? as urgency? as a workaround attempt in
themselves?) rather than waving them through because the rest of the variant already
cleared.

## METRIC (v2.1 — updated for Special Ad Category audience)

Ad performance (CTR, CPC) and page performance (visit-to-booking rate) still get
tracked separately — that split doesn't change, and neither do the page-level
thresholds below. What changes is how to read the ad-level numbers, now that the
TARGETING rebuild above means a much broader, less-qualified audience than v1
assumed:

- **CTR/CPC now sit against a much wider pool than v1 planned for.** v1 assumed a
  list-matched population (age band + income floor + zip). What's actually buyable is
  "everyone 18–65+ within a 15-mile-plus radius of a couple of Cincinnati/NKY pins" —
  a large share of impressions will go to people who were never going to be the
  reader, regardless of how good the ad is. Expect CPC to move (likely down — the
  auction is bidding against a bigger, cheaper, less-targeted pool) and CTR to move
  too (likely down — more of the audience has no reason to click). Neither shift is a
  verdict on the ad copy by itself; a meaningful part of it is the removed targeting,
  not the words.
- **Raise the impressions floor before reading CTR/CPC as signal.** v1's "at least a
  few hundred impressions per variant" threshold assumed most of those impressions
  were on-target. With Special Ad Category delivery, a much larger share are off-target
  by default, so treat a few hundred as a bare minimum, not a comfortable read —
  a thousand-plus per variant is a safer bar before drawing a CTR comparison between
  variants.
- **Visit-to-booking rate stays the number that matters, and its thresholds don't
  move.** Whoever actually lands on the page and reads it has already self-selected
  past the platform's missing filters — that's the whole point of the creative-as-
  targeting approach in TARGETING above. The 50–100-visit floor from v1 before reading
  that rate as signal still holds; this is the number to trust more than the ad-level
  metrics under the broader targeting.

## HONEST READ — WHAT WOULD MAKE THIS TEST FAIL FOR REASONS UNRELATED TO THE MIRROR
(v2.1 — items 1–7 unchanged from v1, see APPENDIX for full text; one new item added
below, specific to the targeting rebuild)

8. **Special Ad Category targeting dilutes the audience enough to blur what a bad
   number means.** With no age band, no income floor, and no zip precision — only a
   broad 18–65+ bucket and a 15-mile-plus radius around a couple of pins — a real
   share of clicks and landing-page visits will come from people well outside "a few
   years from retirement, real savings," through no fault of the copy or the page. A
   weak CTR or a weak visit-to-booking rate could just as easily be audience mismatch
   (the wrong person saw a well-built page and correctly ignored it) as a mirror-
   concept problem. This is a real limitation the test can't fully engineer around
   given what's actually buyable on the platform right now — the creative-as-
   targeting approach in TARGETING above is the honest mitigation, not a fix. Unlike
   items 1–7, this one can't be "ruled out" with an operational checklist before
   launch — it's a structural ceiling on how cleanly this test can isolate the mirror
   concept from audience mismatch, and worth reading any result with that ceiling in
   view rather than treating this as a clean read either way, good or bad.

---

## Notes for the record (v2)

1. This v2 only touches the ad copy (all three variants) and adds the two new
   disclosure notices plus the "always rendered" marker on Section 6. The five
   questions, scoring key, CTA paragraph, and Justin's close are untouched — cleared
   already, not re-opened.
2. One item flagged above that wasn't explicitly in Ed's note but follows the same
   logic he applied: Variant A's original headline made a "most retirement plans"
   population claim, structurally identical to the "most people" lines he did flag.
   Fixed it now rather than waiting for a second round to catch it.
3. Justin's close still contains "most people don't get shown a clear picture..." —
   left alone since it's outside this round's scope and reads differently to me
   (Justin's own stated opinion in a signed quote, not an Edify factual claim), but
   flagged explicitly for Ed to make the call rather than assuming the distinction
   holds on my own authority.
4. Still not for launch. Same open items from v1 remain open: calendar URL, Justin's
   last name and the six placeholder disclosure facts, Special Ad Category
   confirmation, and the popup/tracking/mobile checks in the Honest Read section.
5. This goes back to Ed next — not to Justin.

---
---

# APPENDIX — v1 (original, pre-Ed's-first-pass), preserved verbatim for the record

# The Mirror — Facebook Test: Landing Page + Ad Copy
Draft v1 — Sloan, 2026-09-12
Status: DRAFT. Copy only. NOT reviewed by Ed. NOT approved for publication or spend.
This is a copy + layout spec for whoever builds the actual Squarespace page and Facebook
ad — not a live page, not a live ad.

Source of record for the questions, scoring key, CTA framing, and close: `drafts/mirror-card-v2.md`
(post-Ed's-copy-review version). Everything marked "verbatim" below is copied unchanged from
that file on purpose — same discipline as the correction piece. Two small adaptations were
necessary because this is a screen serving two audiences (ad-clickers with no physical card,
and mail recipients scanning a QR code with the card in hand) — both are flagged explicitly
below, not buried, so Ed can look at exactly those two spots and nowhere else.

## What's still open before this goes anywhere
- Ed's web-specific compliance pass — he's defining this in parallel per Isla/Justin.
  Nothing below has that review yet.
- Justin's calendar booking link — placeholder below, needs the real URL.
- Justin's last name and the six placeholder facts from the card's disclosure block —
  same open items as `mirror-card-v2.md`, not re-litigated here.
- Confirm with Justin: does his practice's Facebook ad account need Special Ad Category
  tagging (financial products/services) before this can run? That's a platform-policy
  question, not a copy question, and it can block delivery entirely if missed — flagging
  it now so it isn't discovered after copy is finished and spend is scheduled.
- Whoever builds this in Squarespace should disable any default site-wide popup
  (newsletter signup, exit-intent offer, cookie banner beyond what's legally required).
  A default Squarespace popup asking for an email would silently reintroduce the exact
  email-gate mechanic this test is designed to remove.

---

## THE LANDING PAGE

One page. One job: a booked meeting. Nothing on this page should compete with that.

### Section 1 — Hook (reused from card FRONT panel, verbatim)

> **Two Minutes. Five Questions. Your Own Money, In Your Own Words.**
>
> You don't need to know anything about investing to answer these. You just need to
> know your own accounts. There's no right answer to any of them — just yours.
>
> Answer yes or no.

*Reused rather than rewritten on purpose: it already cleared Ed's review once, and every
word reused is one less word that needs re-clearing for the web.*

### Section 2 — The five questions (verbatim from card, required reuse)

1. Do you have money in a savings account, a CD, or an annuity that's set up so the
   original amount you put in can't go down?
   Yes / No

2. Could you get to some of that money within a few days if you needed it — without
   a penalty, and without asking anyone's permission?
   Yes / No

3. Do you have a 401(k), 403(b), or an IRA left over from a job you don't work at
   anymore?
   Yes / No

4. The last time the market dropped sharply — 2022, 2020, 2008, whichever you
   remember — did any of your account balances drop right along with it, with
   nothing in place to limit how far they fell?
   Yes / No

5. Right now, could you name one part of your retirement savings that's invested
   for growth but has a specific plan in place designed to limit how much it could
   lose in a bad year?
   Yes / No

**Interaction spec:** if Squarespace's form/quiz block supports simple tappable
yes/no toggles with no submission, no email field, and no computed output, use that —
it makes the two minutes feel like two minutes. If that requires a plugin, a third-party
embed, or anything that captures the answers server-side, don't use it — just present
the five questions as clean, readable static text with visual yes/no rows the reader
answers in their head, exactly like the printed card. **Hard constraint either way: no
tallying, no running score, no "you answered 3 yes" counter anywhere on this page,**
even if the interactive version makes that technically easy to add. That mechanism is
exactly what the old Squarespace quiz did wrong.

### Section 3 — Scoring key (verbatim from card BACK panel)

> **Here's What People Usually Find**
>
> For each question you answered "yes," check the matching box below.
>
> - Yes on Q1 or Q2 → **Money that can't lose value**
> - Yes on Q3 or Q4 → **Money from an old job, moving on its own**
> - Yes on Q5 → **Money that's managed with a plan for the downside**
>
> There's no wrong picture here — just yours.

No score. No verdict. No "Financial House Snapshot." No adjectives applied to the
reader's situation ("Strong," "At Risk," anything else that sounds like a diagnosis).
The reader does the matching, on their own, same as on paper. This is the single most
important thing this page has to get right relative to the old quiz.

### Section 4 — The one CTA

**[ADAPTED — flagged for Ed]** The card's CTA paragraph assumes the reader is holding
the physical card ("You bring the card; we'll look at it together"). This page serves
two audiences — ad-clickers with nothing physical in hand, and mail recipients who
scanned a QR code and do have the card — so that one clause is adapted to work for both.
Everything else in this paragraph is unchanged from the card:

> If you'd like to talk through what you found — all three boxes, two, or just one —
> here's how. It's a free conversation, about twenty minutes, no obligation, and no
> pitch. Bring your answers — on this screen, on a printed card, or just in your head.

**[ ⬤ Book the Free 20-Minute Conversation ]** → links directly to Justin's booking
calendar. [CALENDAR URL — PLACEHOLDER, needs Justin's real link]

That is the only button on the page. No secondary link, no "or watch this video
first," no "download the guide," no email field anywhere above or below the button.
If someone leaves this page without booking, they leave — that's the point of the
test.

### Section 5 — Justin's close

**[ONE WORD ADAPTED — flagged for Ed]** v2's close says "This card is that picture."
On a screen, "card" is inaccurate — adapted to "page." No other change.

> I built this because most people don't get shown a clear picture of their own
> retirement money until they're already sitting across the table from an advisor.
> This page is that picture, without needing the meeting first.
>
> — Justin [Last Name]
> Trulip Retirement Planning / Edify Retirement Education

### Section 6 — Disclosure slot

**[DISCLOSURE BLOCK — PLACEMENT AND FINAL WEB COPY PENDING ED'S REVIEW. DO NOT DELETE
OR SHRINK THIS SECTION WHEN BUILDING THE PAGE.]**

Base text is the disclosure block already drafted in `drafts/mirror-card-v2.md`
(the "Disclosures" section, RIA registration line, insurance license lines, the
principal-protection/carrier-guarantee paragraph, and the "not an offer or
solicitation" line) — same six placeholder facts still outstanding there. Ed will
tell us: whether it sits as a persistent footer, an always-visible block at the
bottom of the page, or an expandable "important information" section; and whether
web placement needs anything the printed card didn't (e.g., something the card's
paper format couldn't do but a webpage can, like a permanently visible line rather
than something the reader has to unfold to reach). Not guessing at that here.

---

## THE AD

Job of the ad is narrow: earn a click from someone who isn't expecting to be sold
anything. Not the booking, not the explanation — just the click. The landing page
carries the rest.

**Facebook button:** recommend the standard "Learn More" button rather than
anything that reads like a commitment ("Sign Up," "Get Offer," "Book Now"). "Learn
More" against a landing page that turns out to be two minutes of honest self-check
is a promise the click actually keeps — that's the whole Godin logic of earning
attention instead of demanding it. Putting a stronger verb on the ad than the page
delivers on would be the interruption-marketing instinct we're deliberately avoiding.

### Variant A — plain naming of the gap

**Headline:** Most Retirement Plans Are Missing One Piece

**Primary text:**
There are three basic kinds of retirement money: money that can't lose value, money
sitting in an old 401(k) or IRA, and money that's invested for growth but has a plan
for the downside built in. Most people we talk with have two of the three. Five short
questions — about your own accounts, nothing else — show you which one you might not
have. Takes about two minutes. No email required.

### Variant B — question-led

**Headline:** Which of the Three Do You Have?

**Primary text:**
Retirement savings usually falls into three categories — money that can't lose value,
money left over from an old job, and money that's managed with a specific plan for
the downside. Five quick yes/no questions about your own accounts show you which of
the three you're sitting on, and which one you may have never gotten around to.
Two minutes, no score, nothing to sign up for.

### Variant C — quiet, low-key register

**Headline:** Five Questions About Your Own Retirement Money

**Primary text:**
No pitch, no score, nothing to download — just five short questions about your own
accounts. Most people who answer them realize they're missing one of three basic
pieces of a retirement plan. Takes about two minutes, and it's yours to keep either
way.

All three stay inside the same register on purpose: no fear language, no "protect
your retirement," no claim about outcomes, no urgency device (no countdown, no
"before the next drop," no scarcity). If Ed wants a fourth variant testing headline
length or a different entry point into the three-buckets idea, that's a five-minute
addition once the first three clear.

---

## TARGETING (flag for Justin, not copy)

Recommend matching Facebook's targeting as closely as the platform allows to the
same population Justin's DRA mail list targets — age band, household income floor,
and Cincinnati/NKY zip codes — so this test reads as a floor for the mail version
rather than a read on a different audience answering a different ad. Concretely:

- Age band: match the DRA list's band exactly (need the actual figures from Justin/
  Isla — don't have them here, and guessing at "55-65" without confirming against the
  real list defeats the point of matching it).
- Geography: same Cincinnati/NKY zip list the mail run uses, not a broader metro
  radius — a wider net dilutes the population match and makes the comparison to the
  mail results meaningless.
- Household income: Facebook's ability to target household income directly has
  narrowed substantially since the platform's 2018+ privacy changes on sensitive
  categories, especially for anything that could read as a financial-services ad.
  Don't assume income targeting is available the way it might have been years ago —
  confirm what's actually selectable in the ad account before treating it as a given,
  and if it isn't available, zip code + age band is doing most of the demographic
  matching work anyway.
- Do not build a custom audience from Justin's client list for this test. That would
  mean uploading client contact data to Facebook's ad platform, which is a separate
  data-handling decision Justin needs to make explicitly and deliberately, not
  something that happens as a targeting convenience on a first test. Flagging, not
  deciding.

---

## METRIC

**What's actually being measured, and why it has to be split in two:** "meetings
booked per dollar spent" is the number Justin ultimately cares about, but it
conflates two different jobs — the ad's job (get a click) and the page's job (get a
booking). Track both separately from day one:

- **Ad performance:** click-through rate, cost per click. This tells you whether the
  ad copy and targeting are working — a problem here is an ad/targeting problem, not
  a verdict on the mirror.
- **Page performance:** landing-page-visit-to-booked-meeting rate. This is the actual
  test of the mirror mechanism — whether five honest questions with no score and one
  clean CTA converts better than the old quiz's zero.

**What counts as signal versus noise at small spend:** with a modest test budget
(low hundreds of dollars), don't call the result off the first few days or the first
handful of clicks. A single booked meeting out of 40 clicks and zero out of the next
40 are both within normal small-sample noise — neither proves anything alone.
Rough thresholds before treating a number as a real signal rather than noise:
- Don't read the ad-level numbers (CTR, CPC) until you've got at least a few hundred
  impressions per variant — anything less and you're reading random variation, not
  ad quality.
- Don't read the page-level conversion number (visits-to-bookings) until you've got
  at least 50-100 landing page visits total. Below that, one extra booking or one
  fewer swings the rate by several points on its own.
- The one number worth acting on early, even at low volume: a repeat of the old
  pattern — real traffic arriving at the page, and zero bookings, after a hundred-plus
  visits. That specific shape (traffic exists, conversion is flat zero) is the same
  failure signature as the original quiz, and if it shows up again despite a
  completely rebuilt page, that's worth pausing to check the "ruled out" list below
  before concluding anything about the mirror concept itself.
- A positive early signal worth genuinely noticing, even from a small number: any
  booked meetings at all in the first week. Given the old test's actual result was
  zero, even three or four real bookings from a small spend is already a different
  outcome than what's being compared against, and worth treating as real rather than
  waiting for a large-sample confirmation to feel allowed to be encouraged by it.

---

## HONEST READ — WHAT WOULD MAKE THIS TEST FAIL FOR REASONS THAT HAVE NOTHING TO DO
## WITH THE MIRROR

Rule these out before reading a bad result as a verdict on the concept:

1. **Mobile layout and load time.** This audience skews 55+, largely on phones. Five
   questions, a scoring key, a CTA, a close, and a disclosure block is real length —
   if the page is slow to load, if the CTA button isn't visible without excessive
   scrolling, or if text renders too small to read comfortably (the card's own format
   note said 8pt minimum, larger preferred — the same logic applies on a phone
   screen), people will bounce before ever engaging with the questions at all. Check
   this on an actual phone, not just a desktop preview.

2. **Calendar booking friction.** The whole test's cleanliness depends on "click the
   button, book the meeting" being close to frictionless. If Justin's calendar tool
   requires an account, asks for a long list of fields before showing available
   times, shows no open slots for days, or looks unpolished/untrusted at the exact
   moment someone was willing to commit twenty minutes — that's a booking-tool
   failure, not a mirror failure, and it would suppress the one number this whole
   test is built to read.

3. **No tracking, no way to attribute.** If there's no UTM tagging or distinct
   tracking per ad variant, and no way to tell a mail-driven booking from an
   ad-driven one once this page also serves as the mailed card's QR destination,
   "meetings booked per dollar" can't actually be calculated — it'll look like the
   test failed when really it was never instrumented to produce an answer. This
   needs to be set up before the first dollar spends, not reconstructed afterward.

4. **A default Squarespace popup reintroducing the email gate.** Already flagged
   above — worth repeating here because it's the single easiest way to accidentally
   recreate the old quiz's worst mechanic without anyone intending to.

5. **Ad account restrictions specific to financial services.** Facebook applies
   extra scrutiny and sometimes delivery restrictions to ads it classifies as
   financial products/services — this can silently limit reach or reject ads outright
   for reasons that have nothing to do with copy quality. Confirm the ad account is
   set up correctly for whatever category Facebook assigns this to before treating
   low delivery as an audience-disinterest signal.

6. **Ad fatigue or audience overlap with the future mail run.** If this test runs
   long enough against the same zip codes the mail piece will eventually target, and
   frequency climbs too high, later mail recipients may already have seen (and
   ignored) the online version before the postcard ever arrives — worth capping
   spend/duration with that in mind rather than treating this as a channel Justin
   runs indefinitely.

7. **Short test window catching an unrepresentative few days.** A test that runs for
   only two or three days can catch a fluke — a slow weekend, a news cycle
   dominating attention, a platform-wide delivery hiccup. Give it enough days to
   average out before reading the number as settled.

If the result comes back flat and none of the above turned out to be true — page
loaded fast, looked clean on mobile, booking took under a minute, tracking worked,
the ad account wasn't restricted, the window was long enough — then it's a real
read on the mirror mechanism itself, and worth taking seriously as one. Until those
are ruled out, a bad number is at least as likely to be a plumbing problem as a
concept problem.

---

## Notes for the record (not for print)

1. Two verbatim-required blocks (questions, scoring key) are unchanged from
   `mirror-card-v2.md`. Two adaptations were made and flagged individually above
   (the CTA paragraph's "bring the card" clause, and "card" → "page" in Justin's
   close) — both are the minimum edit needed for a screen serving two audiences,
   not creative rewrites, but Ed should still confirm they don't change anything
   substantively.
2. This page deliberately does not mention "the ad" anywhere, per the brief — it has
   to read the same way for someone arriving from a mailed card's QR code as for
   someone arriving from a Facebook click.
3. A note on scope, for Justin/Isla: this test runs paid Facebook spend, which sits
   outside what I'd normally call Sloan's lane — the mandate here is education and
   community reach, not paid media. Justin's already made the call to test this way
   before the mail run, so I've drafted to that decision rather than re-litigating
   it. Worth being explicit that this is a one-off test of a specific mechanism
   (the mirror), not a signal that paid Facebook acquisition is becoming a standing
   part of Edify's growth engine — that would be a bigger conversation on its own.
</content>
