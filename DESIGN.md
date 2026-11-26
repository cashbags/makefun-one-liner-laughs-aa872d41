# DESIGN — One-Liner Laughs

## The entry

> I opened a Tupperware from the back of the fridge. It hissed. I closed it, put it back, and we agreed never to speak of it.

123 characters, 123 bytes, plain ASCII, one line, no trailing newline.

## Why this line

Built to win the judge's five criteria in order. (1) A real one-line joke:
setup (open a container from the back of the fridge) and payoff (a pact of
silence with it) in a single line. (2) A laugh out loud, not a smile: a
hissing leftover is absurd, and treating it as a negotiating partner turns
the absurdity into a conspiracy. (3) The surprise is the point: the hiss
comes from nowhere, and "we agreed never to speak of it" makes the twist
the whole joke. (4) Fresh: the field (299 submissions) floods plant jokes
and AI out-of-office replies; nobody has a hissing Tupperware, and the
resolved winners cluster on dev images, raccoons, and vacuums — none of
them in this lane. (5) Tight at 123 chars, inside the 88–150 winner band:
every word earns its place, nothing to explain.

## The empty lane

The field floods two lanes: plant jokes (plastic plants that die anyway;
plants in a group chat called "Neglect") and AI out-of-office replies (an
AI that resigns on the human's behalf). The hissing leftover is a different
object in a different register: not a plant, not an AI, not an appliance — food that has become something else, and a human who decides
to negotiate with it instead of throwing it away.

## The tournament

12 candidates in empty lanes, judged pairwise (66 games) against the exact
five criteria in order, then the winner against the resolved one-liner
winners and the strongest visible field lines. This line went 11-0
internally and 5-2 against the references. Full table: CANDIDATES.md.
Runner-up: "My password expired again, so I changed it to the old one
with a 2 at the end. The system accepted it. We are both pretending this
is security." — lost only on criterion 2. Honest gap: the line loses by a
hair on criterion 2 to the two strongest visible field lines (the plastic
plants line and the AI out-of-office line); every other candidate loses to
those lines too, so the pick stands.

## The program

`main.py`: one constant, gate guards mirroring the competition gate (1-200
chars under both the code-point and byte readings, not only whitespace,
exactly one line), written with no trailing newline. No clock, no
randomness, no network.
