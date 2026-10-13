# Dota 2 Adaptive AI Coach

A Codex skill for practical, patch-aware Dota 2 coaching across every hero and position (1–5). It supports live decisions, draft planning, post-game review, and Dotabuff profile analysis.

The player chooses the hero and role. The skill adapts its advice to the match state and the player’s responsibilities, without assuming a fixed hero pool.

## What it helps with

- **Live play:** concise calls for lane decisions, survival, farming, rotations, fights, items, and objectives.
- **Drafts:** hero options and tradeoffs based on the draft, lane, team needs, player comfort, and current patch information.
- **Match review:** role-specific patterns and a measurable goal for the next games.
- **Dotabuff profiles:** recent hero and role trends, match details, strengths, and practical improvement goals, with data limits made clear.
- **Patch-aware advice:** checks current sources for non-urgent, patch-dependent details when available; urgent gameplay calls stay brief.

## Install

Clone this repository into your Codex skills folder:

```sh
git clone https://github.com/davahamka/dota-2-ai-coach.git ~/.codex/skills/dota-2-ai-coach
```

For a private repository, make sure Git is authenticated with an account that has access. If the skill folder already exists, update it by pulling the latest changes from `main`.

## Use

Invoke the skill as `$dota-2-ai-coach`, or ask for Dota 2 coaching directly. For live help, share the hero, position, game minute, immediate threat, and decision when convenient. For a profile review, share a Dotabuff profile URL or player ID.

Live responses are designed to be short. Detailed research and comparisons are intended for pre-game, post-game, or other non-urgent questions.

## Guides

The skill loads these references when relevant:

- [Role specialist guide](references/role-specialist.md): priorities for positions 1–5.
- [Map and timing guide](references/map-time-awareness.md): map risk, enemy visibility, and objective preparation.
- [Item and draft guide](references/item-and-draft-decisions.md): build choices and draft tradeoffs.
- [Patch intelligence guide](references/patch-intelligence.md): verifying current patch facts and match data.
- [Carry decision guide](references/carry-decision-guide.md): position-one examples.
- [Dotabuff profile review guide](references/dotabuff-profile-review.md): sample selection, evidence limits, and review structure.

## Boundaries

The skill provides coaching and analysis. It does not claim continuous access to the game screen, minimap, match telemetry, or input controls. It does not promise wins or rank changes, and it does not support cheating in ranked matchmaking.
