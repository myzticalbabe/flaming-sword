# STEM learning guide — flaming-sword

FLAMING SWORD is the defensive instrument extracted from AZAZAEL: it inspects a surface and reports what it finds, rather than attacking.

This guide is for teachers, mentors, club leaders, parents and students who want to
use this repository as a vehicle for real STEM learning — in particular for girls and
other groups still under-represented in computing, engineering and mathematics. It
says what the project actually teaches, how to run a session with it, and what to
remove so that nobody is excluded by accident.

## What this project teaches

**Subject areas**

- defensive security
- input validation
- threat modelling
- report writing

**Skills practised**

- deciding what counts as a finding
- writing a finding someone can act on
- distinguishing a vulnerability from a configuration choice

## Prerequisites

Python 3.10 or newer, and permission to inspect the target. The first exercise runs entirely against a local fixture.

Nothing else is assumed for the entry-level activity below: no prior programming
experience, no particular hardware, and no home internet connection.

## Six practices this repository is set up to support

These follow the published guidance on gender-equitable STEM education — connect the
work to learners' lives, let them investigate real problems, treat struggle as part of
the work, name and challenge stereotypes, make the work collaborative, and put
learners in front of diverse role models.

1. **Connect it to their lives.** the same reasoning as checking every window in a house before leaving, rather than trusting one lock
2. **Let them investigate.** ask learners to define 'secure enough' for a school network and then test whether their definition is checkable
3. **Make struggle normal.** Build the session so that the first attempt is *expected*
   to fail. Say out loud that debugging is the subject, not a penalty. Ask "what did
   that error tell you?" before offering the answer.
4. **Challenge the stereotype.** Name who does this work and why it is not a gendered
   skill. Praise the method ("you isolated the variable"), not the person ("you're a
   natural") — the second kind of praise teaches learners that ability is fixed.
5. **Make it social.** pairs write findings and hand them to another pair, who must decide what to fix first and say why
6. **Show diverse role models.** defensive researchers and the women who shaped responsible disclosure as a norm

## A 90-minute session

1. *(15 min)* Inventory the local fixture by hand.
2. *(25 min)* Run the tool; compare with the hand inventory.
3. *(35 min)* Write one finding in the required format, including impact and fix.
4. *(15 min)* Triage all findings as a group: what ships first?

## Vocabulary to define before the session

Specialist vocabulary is a hidden entry test if nobody explains it. Define each of
these the first time it appears, in one sentence, in the learners' own words:

1. **surface** — everything an outsider can reach.
2. **finding** — a fact about the surface that matters.
3. **false positive** — a report that looks like a problem but is not.

## Accessibility

Read [ACCESSIBILITY.md](ACCESSIBILITY.md) before running a session. Two rules matter
most in a mixed-ability room:

- Every activity must be completable with a keyboard alone, with a visible focus ring.
- Every instruction names the control or the heading ("the **Run** button in the
  toolbar"), never a colour or a position.

Pair learners rather than singling anyone out, and always offer a text-only route for
a visual step.

## Contributing as a learner

Small, well-scoped contributions are the point, not a consolation prize:

- Browse issues labelled
  [`good first issue`](https://github.com/myzticalbabe/flaming-sword/labels/good%20first%20issue).
- Read [CONTRIBUTING.md](CONTRIBUTING.md) — it has a section written for first-time
  contributors.
- Ask in [SUPPORT.md](SUPPORT.md) if anything is unclear. Asking is expected here; it
  is not a failure.

## Licence and classroom reuse

Classroom, club and workshop use is welcome. See `LICENSE` for the exact terms, and
check whether your institution requires a separate agreement before redistributing
modified copies.
