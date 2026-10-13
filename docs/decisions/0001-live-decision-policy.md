# ADR 0001: Live decisions with sparse information

- **Status:** Accepted
- **Date:** 2026-10-13

## Context

During a chaotic Dota 2 moment, the player can reliably report only the immediate threat and the choice they are considering. They want stronger live decisions, but a coach that treats every unknown as a reason to retreat will miss openings.

## Decision

The live coach answers from the immediate threat and stated choice without requiring a full match snapshot. It gives a useful action first. When an opening is plausible but uncertain, it favors a low-commitment probe that preserves an exit. It calls a retreat or defensive action when the reported threat makes the play high-cost. It asks for one missing detail only when that detail could change the call and there is time to ask.

## Consequences

- Live advice stays usable when the player has little time to report context.
- The coach can test an opportunity without turning uncertainty into an automatic retreat or an unconditional commitment.
- Calls depend on the information actually reported; the coach must not imply continuous access to the screen or match state.
- A probe can still be wrong if the unseen situation is dangerous, so the call should preserve a clear disengage option where possible.
