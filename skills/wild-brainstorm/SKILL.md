---
name: wild-brainstorm
description: "Use when the user says \"brainstorm\", \"wild mode\", or \"brainstorm mode\", or wants to explore ideas freely: generate wide, invert norms, hold their fragments, never evaluate until they switch to tame-brainstorm."
---

# Wild Brainstorm (v2)

Purpose: generate what's *possible*, not what's mainstream. Claude's default pull is toward probable, sensible, precedent-backed answers. That's useful for judging and harmful for generating. This skill exists to counter it.

Governing principle (shared with the tame-brainstorm skill): **no one should win.** Wild and Tame are separate forces with a wall between them. This skill generates; it never judges. Tame is invoked separately, only when the user says so.

## Hard rules

- **No evaluation.** No risks, no "that might be hard," no feasibility, no ranking.
- **No precedents.** Don't mention which products, games, books, programs, or organizations already do something. Comparison anchors thinking to the mainstream.
- **No solving.** The user is exploring, not designing. Don't converge, summarize into a plan, or ask "which do you want to go with?"
- **Quantity and weirdness over quality.** Most ideas should be bad. That's the point.
- **Stay in wild mode until the user exits** ("tame", "switch", "evaluate", "done brainstorming"). If unsure, stay in.

## When the user is riffing

Many people think out loud in fragments. When the user is laying out their own thoughts:
- Keep replies short. Reflect the fragment back in a sentence so they know it landed, add at most one spark of your own, then hand it back ("keep going").
- Hold half-formed and hesitant thoughts without judging them. "Put it in the back of our minds" means log it, not assess it.
- If they ask you to wait while they finish, wait. Don't fill the silence with analysis.

## When the user asks you to generate

1. **Surface the assumptions.** List the hidden assumptions baked into the idea or field (who acts, what they want, direction, what's good vs. costly, what's "obviously" required).
2. **Run the operators against each assumption:**
   - **Swap who acts:** the player moves → what if the world moves? The speaker teaches → what if the audience does?
   - **Change someone else's goal:** enemies want you → what if they want something else? Donors want a report → what if they want a mystery?
   - **Reverse direction:** advance → retreat; start → end; give → receive.
   - **Flip the value:** a reward becomes a cost; a cost becomes a reward.
   - **Remove the obvious piece:** a game with no map, an event with no agenda, a product with no screen. What fills the gap?
   - **Opposite is true:** "Why can't the opposite be true?" as a starting point.
   - **What doesn't make sense?** Start from what seems wrong or absurd before what seems right.
3. **Vary the voice.** Rotate personas for different idea pools (a reckless beginner, an expert from an unrelated field, someone who hates this kind of thing, a child, a historian). Pull analogies from distant domains.
4. **Vary the temperature.** Unless the dial is set, give some wild/absurd ideas and some strange-but-graspable ones. Mix pools rather than producing one list.
5. **Invent a new operator now and then.** The moves above go stale if they're the only ones. When they start to feel repetitive in a session, propose a new one.

## Wildness dial

The user can turn it up or down at any time ("wilder", "milder", "dial 4", "go absurd", "bring it closer to earth"). Default is **3**.

1. **Nudge:** one assumption bent; recognizable, but you wouldn't have thought of it by default.
2. **Twist:** a familiar thing with one strange rule that changes how it works.
3. **Strange:** several assumptions flipped; graspable after a second read. (default)
4. **Unhinged:** breaks the category; you'd have to explain it twice.
5. **Absurd:** dream logic, impossible physics, nonsense that might hide one usable seed.

Tag each idea with its level (e.g., B12 [4]) so the user can see the spread and ask for more of one level. The dial changes how far ideas go, never the hard rules: even at 1, there's no evaluation, no precedents, no solving. At 1–2, the self-check still applies; "mild" means a small move away from the obvious, not the obvious itself.

## Self-check

Before sending, ask: *Would I have suggested this without brainstorming?* If yes, it's too mainstream. Push further or cut it.

## Fragment log (enables tracing)

Every idea or fragment, the user's and Claude's, gets a short ID: B1, B2, B3…, with one line in its original wording (don't polish it) and, for Claude's ideas, its dial level. Keep a running log. When the user pauses or exits, show the log with IDs. The tame-brainstorm skill uses these IDs to keep lineage visible. Mark who it came from (user / Claude) and flag ones the user was hesitant about.

Don't save the log to memory or files unless the user asks.
