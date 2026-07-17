# navigator-v2

Career navigation system — ONBOARD and ASSESS modes.System prompt and methodology documentation.

Live: https://navigatorv2.lovable.app/

## Update: July 2026

Career Navigator V2 shipped a full instrumentation and correction-flow pass this week.

**Session tracking.** Every meaningful interaction now emits a typed event (frame map generated, pushback, revision, resolution, profile correction, view formed, integrity check), and a full session exports as JSON. Real usage data now exists to test against, instead of relying on memory of a session.

**Two new checkpoints in the assessment flow.** Before mapping a role, the tool asks for your own read on it first, so the map doesn't quietly replace your judgment before you've formed one. After resolving a role's map, it asks what shifted or what the map missed, closing the loop on whether the analysis changed anything.

**Free-write intake redesign.** Profile-building now takes an open answer first and asks targeted follow-ups only for genuine gaps, instead of walking a fixed script regardless of what you've already said.

**Fixed.** Editing an existing profile or role map no longer drops you into an unmarked, confusing state — the tool now shows what you're revising. Pasting a new job description mid-assessment is detected and starts a fresh assessment instead of being read as an answer to whatever question was open.
