# Wild & Tame Brainstorm — two Claude skills

A pair of skills for brainstorming with Claude without letting it drift back to the safe, obvious answer.

AI models are good at producing the *probable* answer. That helps when you're judging ideas and hurts when you're generating them. These skills split the work into two modes with a wall between them:

| | **wild-brainstorm** | **tame-brainstorm** |
|---|---|---|
| Job | Generate what's possible | Make chosen ideas buildable |
| Never | Evaluates, ranks, cites precedents, or solves | Sands an idea down until it's safe |
| Start it | "brainstorm", "wild mode" | "tame", "tame mode" |

The shared principle is **no one should win**. If taming wins, you end up with what you'd have had without brainstorming. If wild wins, you're left with something you can't build. The value is in the friction between the two.

## What makes them different

- **You control the switch.** Wild mode doesn't evaluate anything until you say "tame."
- **Wildness dial (1–5).** Say "wilder," "milder," or "dial 4" at any time. Claude tags each idea with its level so you can see the spread.
- **Riffing mode.** If you're thinking out loud, Claude keeps its replies short, logs your half-formed fragments, and waits when you ask it to. It doesn't interview you.
- **Fragment log with IDs.** Every idea gets an ID (B1, B2…) in its original wording, with who said it and whether you were hesitant about it.
- **Visible lineage.** Each tamed idea shows what it was *born from*, its *spark*, *what changed*, and a *DNA check* against the original.
- **Two alarms.** Claude tells you plainly when "taming won" or "wild won."
- **Alternating passes.** Tame switches between feasibility and originality passes instead of doing all the feasibility work first. This follows Baruah, Paulus & Kohn (2021), *Journal of Creative Behavior* 55(4), who found that a simultaneous focus on originality and feasibility produced more original ideas.

## Install

**Claude apps (web, desktop, mobile):** zip a skill folder (for example `skills/wild-brainstorm/`), then upload it as a custom skill in Claude's settings. Install both skills; they're designed to work together.

**Claude Code:** copy the folders into your skills directory:

```bash
git clone https://github.com/wimerek/claude-skills
cp -r claude-skills/skills/* ~/.claude/skills/
```

## A typical session

1. "Brainstorm: a fundraiser nobody has seen before." Claude starts generating, mostly at dial 3.
2. "Wilder." Claude moves to level 4 and 5 ideas. You riff, and it logs your fragments.
3. "Tame B4 and B11." Claude names each one's spark, alternates feasibility and originality passes, and shows lineage for two or three variants.

## License

MIT. See [LICENSE](LICENSE).
