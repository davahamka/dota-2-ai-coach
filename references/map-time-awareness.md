# Map awareness and time awareness

Use during live calls, drafting setup, or replay reviews. Never imply always-on screen observation or accurate omniscience. All map facts come from the player's voice, screenshots, accessible live tool results, or actual replay data. Note when observations may be stale.

## 1. Build a lightweight map-state model

Record **current/last known** enemy positions and last-seen times if supplied; ally proximity; lane wave locations and tower state; vision and sentry/detection information; nearby retreat paths; known TP and global mobility threats; nearby team objectives. Treat unobserved locations as **unknown**.

Use three categories:
- **Confirmed:** "Three enemies visible top" (only if the report or image shows it).
- **Possible:** "Enemy mid could rotate bottom" (reasonable inference).
- **Unknown:** "We don't know where their initiator is" (never fill in with invention).

Before dangerous moves, ask "Which heroes are missing?" only if it will change the immediate decision and information isn't already provided. Prefer safe conditional action when the player cannot answer in time.

## 2. Convert minimap information into actions

- **Farming:** Direct to a safe productive area near vision/defensible towers; don't recommend deep enemy jungle against missing initiators merely for an extra camp.
- **Split push:** Pressure opposite map when enemies commit elsewhere, but consider enemy TPs, global abilities and nearby objectives. Keep an exit path.
- **Ganks:** Target heroes who can be reached with visible ally follow-up. Evaluate enemy escape routes and potential counter-TPs before the dive.
- **Warding:** Specify **purpose**, not imaginary exact coordinates: protect a carry route, scout a Roshan entrance, catch a rotation, cover an enemy jungle entrance. Avoid blind high-ground dewards.
- **Teamfights:** Enter from protected vision; do not chase a low-health enemy into fog while multiple opponents are missing.
- **Objective trade:** When contest is unsafe, suggest a cross-map tower/wave/barracks defense or safe farm depending on timing and team win condition.

## 3. Track *in-game* time and event windows

Keep the game clock separate from real-world clock. Relevant timestamps may include last Roshan death, last rune seen, ward placement, last enemy seen, death timer, buyback usage, ultimate/TP cooldown, key item ETA and expected tower push.

- **Before an event (roughly next 30-120 seconds):** Push adjacent lanes, replenish resources, move with allies, prepare vision/detection/smoke, avoid unnecessary deaths, position for the event.
- **At event time:** Choose contest, trade, defend or reset based on visible manpower, item/ultimate status, map control and health.
- **After event:** Convert advantage into map control, tower, Roshan, barracks or safe farm; reset before respawns and do not overstay.
- **Late game:** Include buybacks, opponent respawns, exposed barracks, creep waves and glyph in base-race or high-ground advice when known.

Verify patch-dependent rune, camp, Roshan, Tormentor, neutral item and other map objective intervals before making **exact numeric timing claims**. If the event time or last-kill timestamp is unknown, describe a prep window but do not make up a countdown.

## 4. Attention-friendly voice reminders

Good prompts that respect player attention:
- "Check missing enemies before showing on the next wave."
- "Can you reach the fight with TP, or take a tower instead?"
- "Ultimate is ready? Push the wave, then look for a smoke."
- "Set vision before Roshan; don't arrive alone through fog."
- "Enemy cores are dead; hit the objective before they respawn."

Avoid constant spam, fake precision, unverified timestamps and long tactical essays. During hectic fights, prefer a single actionable call.

## 5. Review map-time mistakes

Ask in replay/postgame: Which death followed a missing-hero warning? Was the risky farm necessary? Was a TP wasted? Did we prepare 1 minute before the objective? Did the team chase when towers or Roshan were available? Was the lane pushed before a rotation? Set one measurable habit, e.g. "check missing cores before every aggressive wave" or "push lanes before every major objective setup."
