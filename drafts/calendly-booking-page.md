# Calendly Booking Page — copy spec, mailer-v2 funnel

Jayme, 2026-09-22. Draft. NOT cleared by Ed. NOT approved by Justin. Nothing here
configures or goes live until both sign off.

**Status: end of the mailer funnel, not the FB/mirror funnel.** This is the booking
step behind `drafts/mailer-v2-from-the-class.md`'s CTA — the hour-long, in-person
**visit** at the Crestview Hills office. It is not the 20-minute phone conversation
spec'd for the Facebook mirror test in `drafts/mirror-landing-page-v2.md` Section 4.
Different offer, different duration, different location — worth flagging because the
two could get merged by accident if someone builds this off the wrong reference.

Per Ed's standing ruling (`.claude/memory/compliance-precedents.md`, 2026-09-12 web
box): **the booking page is its own advertisement.** It gets its own compliance
clearance and its own Rule 204-2 log entry before it goes live — not covered by
whatever cleared the mailer or the landing page upstream of it.

---

## 1. The event title

**"A Visit — About an Hour"**

Not "meeting," "appointment," or "consultation" — Justin's own word, and the one word
the class-script capture (`reference/class/script-part-1.md`, THE CLOSE) flags as the
single most transferable thing in his live material. Putting the duration in the title
itself, not buried in the description, kills "how long is this going to take" before
anyone has to read a sentence to find out — same job "about an hour" does on Panel 3 of
the mailer.

**Considered and rejected:**
- *"Free Consultation"* — "consultation" is banned; "Free" alone as a title undersells
  what's actually being offered and reads like every other financial-services booking
  page in the category.
- *"Schedule Your Visit"* — "Your" is premature. The reader hasn't agreed to anything
  yet; a command verb plus a possessive pronoun is the sales-page register this whole
  project exists to avoid.
- *"Book a Time to Talk"* — vague, no duration, no register connection to the piece
  that got them here.

## 2. The event description (the body copy)

> Not a class. Not a sales pitch. A visit — about an hour, one-on-one, at our office
> in Crestview Hills, right behind Thomas More University.
>
> *Investment advisory services are offered through Portfolio Medics, LLC, an
> SEC-Registered Investment Adviser. Insurance business is conducted through Trulip
> Investment Management, LLC. This is a free educational visit — not a solicitation,
> and not individualized advice. Full disclosures: [LINK].*
>
> We'll sit down and look at what you've already got — no products, nothing to sign,
> nothing to buy. Bring whatever's most comfortable for you — statements, questions,
> or nothing at all. The more you bring, the more precise we can be.
>
> It's free. If it makes sense to keep talking afterward, we'll set up a second visit.
> If it doesn't, you'll still leave knowing more about your own money than you did
> walking in.
>
> Questions before you book? Call [TRACKED PHONE NUMBER] and just ask for a visit.

**Why this and not a shorter version.** Every word here is doing reassurance work, not
selling — this is Jayme's own rule about sequence: the mailer's job was to get someone
curious enough to click; this page's only job is to not lose them at the very last
step, the way a receptionist's tone can undo an hour of good advertising. It pulls
directly from the mailer's own Panel 3 language ("Not a class. Not a sales meeting. A
visit...") and from README's Step 2 form logic (no cost, no product, no commitment
beyond showing up) so the funnel reads as one voice, not two — the continuity the brief
asked for.

**What I left out on purpose.** No bucket language (green/blue/red), no BrokerCheck
device, no restatement of "coordination." Those did their job upstream. By the time
someone is looking at a calendar, the persuasion is over — the only job left is
logistics and reassurance, same as the Step 2 form's own design (checkboxes and dates,
not another argument).

## 3. The required question: "What state do you live in?"

Kept as the literal question text Ed's spec already requires
(`.claude/memory/compliance-precedents.md`, 2026-09-12: "a required custom question on
the booking form... Justin screens anyone outside Ohio or Kentucky before the
meeting"). It's a plain factual short-answer field, which is already about as
low-friction as a required question gets — the risk isn't the question, it's that it
can *land* as a gate if it sits there bare, with no reason attached.

**Subtext line beneath it, if Calendly's custom-question field supports helper text:**

> *No wrong answer — we just want to make sure the right person on our team can help
> you.*

That borrows the "no wrong answer" refrain already established on the mirror card and
landing page ("There's no wrong picture here — just yours") rather than inventing a new
reassurance device. If Calendly's field type doesn't support a separate helper-text
line, fold it into the question itself: **"What state do you live in? (No wrong
answer — just want to make sure the right person can help you.)"** — longer, but still
one field, not two.

## 4. Other questions considered — argued individually

- **Phone number: optional, not required.** Justin's own close removes the callback
  requirement entirely — "he sends the confirming email... completion requires no
  interaction with anyone" is the fourteenth and most important friction removal in
  README's count of his live close. Requiring a phone number on a cold booking page
  reintroduces exactly the expectation he's built his warm process to avoid. Leave it
  as Calendly's optional field, don't make it mandatory.
- **Email: required, but not really a choice.** Calendly needs it to send the
  confirmation, and the confirmation email *is* the mechanism that replaces the
  callback. Structural, not a design decision.
- **"What would you like to talk about?" — argued against.** This is the Step 2 form's
  concern checklist (Foundation/Income/Legacy/Health & Care), and it works warm because
  the room has already spent two hours together. Cold, off a mailer, the same question
  reads as building a file on someone before they've met anyone — the opposite of "no
  products, nothing to sign." Skip it. If Justin wants to know what's on someone's mind
  before the visit, that's a live question he can ask in the first five minutes on the
  couch, where it's a conversation instead of a form field.
- **"How did you hear about us?" — argued against as a visible field.** This is the
  literal source-attribution question the test needs an answer to, and it's exactly the
  kind of field the brief flagged as avoidable friction. See Section 5 — there's a
  cleaner way to get the same answer.
- **"Have you attended one of Justin's classes before?" — not applicable, skip.**
  Nobody arriving from a cold mailer has. Including it would be a confusing non
  sequitur on this specific funnel, even if it might make sense on a different booking
  page fed by warm traffic.

**Net: two fields beyond Calendly's own defaults (name, email) — state (required,
reassured) and phone (optional).** Everything else stays off the page.

## 5. The source-field problem — clean solution exists, no visible question needed

**Recommendation: a dedicated Calendly event link for this drop, not a form field.**
This isn't a new mechanism — `drafts/mirror-landing-page-v2.md`'s own build spec
already established it for the Facebook test ("Two event links... one for the FB
landing page button, one for the mailed card's QR code, so bookings can be told apart
by source"). The same logic extends cleanly here: this mailer gets its own Calendly
event type/link, used nowhere else — not on the FB landing page, not on any other
future drop — so every booking through it is unambiguously attributable at the link
level, with zero fields added to the form a person actually fills out.

**One layer finer, if Justin wants it, still no visible question:** Calendly's paid
tiers can pass UTM parameters through a booking link's query string
(`?utm_source=mailer-v2&utm_campaign=nky-drop-1`, etc.), captured in Calendly's own
reporting/export without ever being shown to the invitee. **I'm flagging this as
likely rather than confirmed** — I haven't verified which Calendly plan tier actually
supports UTM pass-through versus just a static link, and per the standing rule against
asserting unconfirmed facts about tools/vendors, this needs a five-minute check against
the actual account before anyone relies on it. If it doesn't work, the dedicated-link
approach above still solves the problem on its own — UTM pass-through would only add
finer-grained detail (e.g., distinguishing a QR scan from a typed URL within the same
drop), not solve the core attribution question.

**So: the source-field problem has a clean solution, and it doesn't require a visible
question.** One dedicated link, confirmed working today; UTM pass-through as a
possible refinement, unconfirmed. Recommend building on the link alone and treating UTM
as a nice-to-have, not a dependency.

## 6. The confirmation copy

Per Ed's standing rule (`.claude/memory/compliance-precedents.md`, 2026-09-12 web box):
"Transactional confirmations only... Nothing else — no content, no links to other
pages. Turn off any marketing-style follow-up." The compliance pointer line is the one
permitted exception — restating no-pitch/service-area briefly at the booking stage was
explicitly ruled pointer-style-acceptable, not an added marketing element.

> **Subject: You're booked — [Day], [Date] at [Time]**
>
> You're set for [Day, Date] at [Time], at our office in Crestview Hills —
> [ADDRESS], right behind Thomas More University. [Directions link]
>
> It's just you and Justin, about an hour, on the couch. Bring whatever's most
> comfortable for you — the more you bring, the more precise we can be.
>
> Need to change the time? [Reschedule link] · [Cancel link]
>
> *This is a free educational conversation — not a solicitation, and not
> individualized advice. Full disclosures: [LINK].*
>
> — Justin McGuffey

No content beyond the logistics, the reschedule/cancel links Calendly itself needs to
function, and the one compliance line. Nothing else gets added later without going
back through Ed — that's the rule, not a suggestion.

## 7. Compliance — flagged for Ed, not decided here

- **The pointer line in both the description and the confirmation is a first draft of
  the idea, not final wording.** Conceptually modeled on the button-notice register
  already established in `drafts/disclosure-blocks-v1.md` (Variant B) — "Booking this
  call schedules a free educational conversation — it isn't a solicitation or an offer
  of specific advice" — adapted for an in-person visit rather than a call. Ed's call on
  exact wording, same as everywhere else.
- **Entity question resolved 2026-09-22 — this item is closed.** Insurance business is
  conducted through **Trulip Investment Management, LLC**. Disclosure wording pulls
  from **Block A** in `drafts/disclosure-blocks-v1.md`, not the superseded variants
  below it. The "[LINK]" placeholders for full disclosures point at wherever the
  resolved block ends up living (presumably the mailer's landing page, since that's
  upstream of this page in the funnel).
- **Edge case worth flagging, not resolving:** the funnel as designed always routes a
  digital visitor through the landing page (which carries the full, always-rendered
  disclosure block) before they reach this Calendly page. But if this link is ever
  forwarded, bookmarked, or reached directly — bypassing the landing page — the only
  disclosure a visitor sees is this page's short pointer line. Worth Ed confirming
  whether that's sufficient on its own or whether this page needs a heavier-weight
  disclosure presence given that possibility.
- **Recordkeeping is operational, not copy, but sits here because Ed's rule ties it to
  this page specifically:** export enabled, retention-capable tier (already spec'd in
  `drafts/mirror-landing-page-v2.md`), and its own dated log entry in Trulip's Rule
  204-2 file once live — not something this draft can satisfy on its own.

## 8. What this measures

Not a new metric — this page is Stage 6 ("Meeting booked") in
`drafts/mirror-mail-test-plan.md`'s instrumentation table, feeding the same primary
metric (booked meetings per 1,000 pieces mailed) that decides whether the mailer test
reads as viable. The dedicated event link in Section 5 is what makes this number
attributable to this specific drop rather than guessed at. Nothing about this page
needs its own separate success threshold — it exists to not lose people between "I
clicked" and "I'm on the calendar," and the honest way to check that is watching
Stage 5→6 dropoff (mirror completed → meeting booked) once real traffic runs, same as
already planned.

---

## Open before this goes anywhere

- Justin's actual Calendly account/tier — needs confirming against the plan
  requirements Ed already specified (export-capable, custom required question support,
  helper-text support on custom questions, UTM pass-through if wanted).
- The dedicated event link itself — needs building, and needs to be genuinely distinct
  from any link used on the FB/mirror funnel or any future drop.
- Final disclosure wording — pull from **Block A** in `drafts/disclosure-blocks-v1.md`
  (approved, entity-corrected 2026-09-22). No longer blocked.
- Address and directions link for the confirmation email.
- Tracked phone number for the "questions before you book" line, shared with the
  mailer's own phone instrumentation.
