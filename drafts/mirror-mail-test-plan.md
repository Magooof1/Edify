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

| Result | Reading | What follows |
|---|---|---|
| **< 1 per 1,000** | The offer was not the constraint. | Mail is done. Stop spending on it and put everything behind the other two doors. |
| **1–3 per 1,000** | Better than the class, not enough to scale. | A second test, not a rollout. Change one thing and re-run. |
| **4+ per 1,000** | The offer *was* the constraint. | Scale it. This is roughly ten times the Ohio drop's attendance rate. |
| **8+ per 1,000** | Strong. | Scale hard and re-examine whether the class should exist in its current form at all. |

**Baseline to beat:** the April 2025 Ohio drop produced 4 attendees from ~10,000 pieces
— 0.4 per 1,000. The bar above asks for ten times that at the booking stage.

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
