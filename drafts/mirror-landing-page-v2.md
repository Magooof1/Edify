# The Mirror — Facebook Test: Landing Page + Ad Copy — v2

Draft v2 — Sloan, 2026-09-12
Status: DRAFT. Copy only. Responds to Ed's first compliance pass on v1. NOT yet
re-reviewed by Ed. NOT approved for publication or spend. Send this back to Ed before
it goes anywhere near Justin.

v1 is preserved in full at the bottom of this file (APPENDIX) for the record — nothing
in v1 was deleted, only superseded where Ed flagged it.

---

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
  questions: dual registration (Trulip Retirement Planning as SEC-registered
  investment adviser; Justin as a licensed insurance producer in OH/KY), "educational
  only, not individualized advice," and a pointer down to the full disclosure block.
  Two sentences, sized not to bury the hook.
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

**[NEW — top disclosure notice, directly beneath the hook, before the five questions]**

> *Trulip Retirement Planning is an SEC-registered investment adviser. Justin
> [Last Name] is also a licensed insurance producer in Ohio and Kentucky. This page is
> educational only and isn't individualized advice — full disclosures are below.*

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
> — Justin [Last Name]
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
(the "Disclosures" section, RIA registration line, insurance license lines, the
principal-protection/carrier-guarantee paragraph, and the "not an offer or
solicitation" line) — same six placeholder facts still outstanding there. This block
now sits alongside the two new short-form notices above (Sections 1 and 4) as a
three-layer disclosure structure: short notice at the hook, short notice at the CTA,
full block always visible at the bottom. Ed to confirm the three work together as
intended and that nothing in the two new short notices contradicts or duplicates the
full block awkwardly.

---

## THE AD (v2)

Job of the ad is narrow: earn a click from someone who isn't expecting to be sold
anything. Not the booking, not the explanation — just the click. The landing page
carries the rest, including all bucket-specific language and the full disclosure load.

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

## TARGETING (unchanged from v1 — flag for Justin, not copy)

Recommend matching Facebook's targeting as closely as the platform allows to the same
population Justin's DRA mail list targets — age band, household income floor, and
Cincinnati/NKY zip codes. See APPENDIX for full detail; nothing here changed in v2.

## METRIC (unchanged from v1)

Track ad performance (CTR, CPC) and page performance (visit-to-booking rate)
separately. See APPENDIX for full detail and signal/noise thresholds; nothing here
changed in v2.

## HONEST READ — WHAT WOULD MAKE THIS TEST FAIL FOR REASONS UNRELATED TO THE MIRROR
(unchanged from v1 — see APPENDIX for the full seven-item list)

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
