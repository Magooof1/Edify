# Mirror Mail Test — success metrics and funnel instrumentation

Isla, 2026-09-19. Written at Justin's request: what number makes this viable, and how
we see *where* it broke if it breaks.

Status: plan, not approved to mail. Gated on Calendly (Justin), the question-five fix
(Sloan), and Ed's re-clearance.

---

## What is actually being tested

**Whether the offer was the constraint.** Two drops of roughly $10k each — different
lists, different markets, different venues — returned 3 buying units and 4 attendees.
The one variable never changed across either is the ask: a free three-and-a-half-hour
Saturday class. The mirror replaces that ask with a two-minute self-diagnostic and a
booked meeting.

This is not a creative test. It is not a list test. Both of those have been run and
failed. If the mirror performs like the class invite did, the offer was not the problem
and mail is finished as a channel for this practice.

## The shape

2,000–3,000 pieces into the tired core Northern Kentucky ZIPs — deliberately the *worn*
list, because using a fresh one would reintroduce the variable the Ohio drop already
controlled for. At roughly $1.00–1.50 all-in per piece on a short run (the DRA list is
already owned), that's about **$2,500–3,750**, leaving room inside the $7k for a second
cell or a follow-up drop.

**Worth considering before committing: run a control cell.** Splitting the budget into
~2,500 mirror pieces and ~2,500 old-style class invites into matched ZIPs would isolate
the offer cleanly. Without a control, a good mirror result is confounded with
seasonality and the annual list refresh. The cost is that both cells get small enough
that only a large difference is readable. Justin's call; flagged, not decided.

---

## The primary metric

**Booked meetings per 1,000 pieces mailed.**

Not response rate, not scans, not impressions. A booked meeting is the first point where
someone has done the thing the old funnel needed a Saturday for.

**Bands recalibrated 2026-09-22**, after Justin confirmed Harrison also cost ~$10k and
after his real meeting-to-client rate replaced a guess. The earlier version of this
table was one notch too harsh — it set the viable bar at 4 per 1,000 on instinct, and
the economics don't require that.

| Result | Reading | What follows |
|---|---|---|
| **< 1 per 1,000** | The offer was not the constraint either. | Mail is done. Stop spending on it and put everything behind the other two doors. |
| **1–2 per 1,000** | Ambiguous — roughly break-even against today's cost per client. | A second test, not a rollout. |
| **2+ per 1,000** | The offer *was* the constraint. | Scale it. |
| **4+ per 1,000** | Strong. | Scale hard, and reopen whether the class should exist in its current form. |

**Why 2 per 1,000 is the line.** At 2,500 pieces that's 5 booked meetings. Harrison
converted 2 meetings into 1 client, and while that's a single data point it's
consistent with a practice that closes unusually well — call it roughly half. Five
meetings therefore implies 2–3 clients against a test cost near $3,000, or about
**$1,200 per client.** Compare: his recent drops run ~$3,333 per buying unit and his
historical good years ran $500–1,000. So 2 per 1,000 is where this channel stops losing
money, and 4 per 1,000 is where it returns to being the best acquisition he has ever
had.

**Baseline to beat:** the three most recent drops each cost about $10,000 and produced
3–4 people. That is 0.3–0.4 per 1,000 at the *attendance* stage. The bar above asks for
roughly five times that at the *booking* stage — a lower-threshold ask, which is the
entire hypothesis.

**The prior this is running against, stated plainly so nobody reads the test
optimistically.** Three drops, roughly $30,000, across two states, two venues and two
list sources, produced on the order of one to two actual clients. That is $15,000–30,000
per client against a historical $500–1,000. Whatever is broken is not geography, not
venue, and not list.

### The business metric behind it

**Cost per new client.** Historical good years ran $500–1,000. The recent drop ran
$3,333. **Viability means beating $3,333 and ideally landing under $2,000.**

This arrives months after the booking number does, so it confirms the decision rather
than driving it.

### A limit to state before anyone reads too much into the result

At 2,500 pieces the counts are small. Ten meetings against six is not a meaningful
difference — it's noise. **This test can detect "the offer was the problem," which
should show up as a large effect. It cannot optimize anything.** If the result lands in
the ambiguous band, the honest response is another test, not a theory about why.

---

## Where it broke — the instrumentation

Every stage gets its own number, because "it didn't work" is useless and each failure
point implies a different fix.

| # | Stage | How it's measured | If this is where it stops |
|---|---|---|---|
| 1 | Pieces mailed | Mail house count | — |
| 2 | Piece opened and read | **Not measurable.** A black box. | Inferred from stage 3 being near zero |
| 3 | **Landing page reached** | Unique visits to a URL used by nothing else | **The piece failed.** Nobody cared enough to act. Creative or offer-at-the-mailbox problem. |
| 4 | Mirror started | Page analytics — began question one | People arrived and bounced. The page isn't delivering on what the piece promised. |
| 5 | Mirror completed | Analytics — reached the result | **The instrument failed.** Too long, too confusing, or the questions don't land. |
| 6 | Meeting booked | Calendly | **The ask failed.** They engaged with the diagnostic and still won't meet — meaning the realization doesn't convert without the room. |
| 7 | Meeting held | Calendly / Justin's calendar | Show-rate or qualification problem. |
| 8 | Became a client | Justin's records | New, and serious — closing is his strength. |

**Stage 3 is the most important number in the test.** It separates *the mailbox is dead*
from *the mailbox works and the offer doesn't* — the question that has been
unanswerable all day. Everything upstream of it is unmeasurable; everything downstream
is diagnosable.

### What the piece has to carry for any of this to work

- **A URL used by nowhere else.** Short, typable, and unique to this drop, so traffic is
  attributable. Vanity URL, not a query string nobody will type.
- **A QR code *and* a printed URL.** Not QR alone. A meaningful share of 50–65-year-olds
  won't scan, and QR-only would measure scanning behavior rather than interest.
- **A phone path, tracked separately.** The 2021 control led with a phone number and it
  produced $6M. Dropping it because digital is tidier would remove a route the audience
  has actually used. A tracking number, or at minimum a required "how did you hear about
  us" field.
- **A source field on the Calendly booking**, so meetings are attributed rather than
  guessed at.

If the piece ships without stage-3 attribution, the test produces a verdict with no
diagnosis — which is most of the value gone.

---

## Timing

- **Drop → first read: 2–3 weeks.** Stages 3–6 are visible by then. This is the go/no-go.
- **Drop → confirmation: 3–6 months.** Stages 7–8, cost per client.

Justin should not wait for the second window to decide the first question.
