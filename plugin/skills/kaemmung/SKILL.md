---
name: kaemmung
description: Systematic grooming of an overgrown work carrier (backlog, queue, ledger segment) — diagnoses WHY it grows before pruning, because each growth disease has its own cure and a generic tidy-up regrows. Use for "backlog aufräumen", "das nimmt kein Ende", "cull/merge/batch", a carrier outgrown its own purpose, "Kämmung", or a session-start banner printing "retirement pass owed" / "exit pass owed". Not for booking or grading single items (the carrier's own rules), reviewing a system for defects (begehung), designing a change (statiker), or code cleanup.
---

# Kämmung

A carrier that keeps growing is not untidy — it is diseased in one
of a few nameable ways, and pruning without the diagnosis regrows
the pile. Consumer: a top-tier session model for the diagnosis;
the pass itself is brief-shaped by construction and defaults to a
dispatch. Evidence register throughout.

## Measure before touching

The numbers are the intake — no cure before them, and the same
numbers re-run are the closing:

- lines now vs at the last pass (or file birth);
- closure markers sitting outside the carrier's closure home;
- booked vs closed-plus-dropped over the most recent growth stretch;
- entries graded dispatchable vs what actually gets scheduled.

Where a session-start banner computes these, its line is the intake;
where not, compute by hand — an unread number fires nothing, which
is how every founding incident stayed invisible until an operator
asked.

## The four diseases

Each carries its marker and its cure; a carrier can have several at
once. Cure order in practice: exit first (cheap, mechanical), then
retirement, then boundaries, then grades — re-measure after each.

1. **Blocked exit** — closures never leave the live sections
   (struck through, graded in place); the carrier grows without
   bound while formally compliant, since "never delete silently" is
   satisfied by a recorded MOVE. Marker: closure markers outside
   the closure home. Cure: move each closed body with its evidence
   to the declared closure home, and amend the carrier's own care
   rule to name the exit — the rule that forbade leaving is the
   defect, never the entries. The carrier's mechanical guards learn
   the exit in the same pass: a presence predicate fires on the
   move itself (first trial: 44 false fires on the legitimate
   move); the repaired form asks whether a missing id's absence is
   EVIDENCED in the closure home — which also catches silent
   deletion and copied-not-moved.
2. **Capture-dominance** — bookings outrun closures plus drops;
   every investigation spawns findings while closing one. Marker:
   booked ~3× closed over a +30%-line stretch. Cure: the
   retirement pass — re-check stale-risk entries against the world
   by executed check, never memory; drop the overtaken with a
   recorded one-line drop; merge duplicates.
3. **Grade inflation** — the dispatchable grade asserts a schedule
   nobody holds; past that point its head is indistinguishable from
   its tail and readers stop believing it. Marker: graded entries
   far beyond what the venue ever schedules. Cure: a third grade —
   the dispatchable grade reserved for a derived, capped head; the
   rest keeps its body and verifier as record.
4. **Unresolved boundaries** — entries name what is wrong but not
   where the fix lands, so merging and batching need a judgment
   pass that grows with the queue and binds the strongest reader
   available. Marker: dispatchable entries without a named landing
   artifact. Cure: resolve each to its realizing artifact, then
   bundle by shared write boundary — a mechanical join over data —
   and close with the bundles BOOKED as dispatchable units in the
   venue's own carrier, or started: a bundling table nobody
   schedules is decoration, and the drainage step otherwise
   survives only in the conversation (first trial: it did, until
   the operator asked where it lived).

## The closing is an accounting, never a feeling

- **Reconciliation**: before-count = moved + kept + dropped
  (+ named gaps), per section, written into the carrier's own
  tally. A sum that fails to add up is itself the finding.
- **Negative grep** for closure markers in the live sections, the
  pattern shown live on a known positive before the move — a
  zero-hit pattern that never matched anything proves nothing.
- Every removal is a move-with-evidence or a recorded one-line
  drop; nothing leaves silently. "Culled" is a cleanness claim and
  inherits the absence probe.
- No "tidy now" claim — the re-measured numbers replace it, and
  the pass books its own date so the next measurement has a
  baseline.

## Composition

- A loaded operator corpus's evidence and carrier rules govern;
  this skill cites them, never restates them.
- The pass defaults to a dispatch: the measures and the four cures
  are the brief skeleton; judgment and reconciliation stay with the
  dispatcher.
- A finding that opens design work routes to statiker; a defect in
  the surrounding system (not the carrier) routes to begehung's
  map.

## Maintenance

Observations from use are written to `dev-notes/OBSERVATIONS.md` in
the source repo — a write target, never a load. Rules in this file
are fire-born: no addition without a real incident as provenance;
the founding incidents are logged there.
