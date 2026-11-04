# 7. Taste: making it look good, not generated

Most AI output looks the same because people accept the first draft. Taste is mostly knowing what to cut and saying exactly what's wrong.

## Words

AI writing has tells. Once you see them you can't unsee them. Cut these from anything you ship:

- "It's not X, it's Y." Just say Y.
- "Seamless," "powerful," "robust," "leverage," "empower," "transform your."
- Ending every paragraph on a little motivational line.
- Lists of three for no reason.
- Em dashes everywhere. Use a period or a comma.

The test I use: could this sentence be pasted onto a competitor's website unchanged? If yes, it's filler. Replace it with something true only about yours: a real name, a real time, a real place, a real number.

Prompt:

```text
Rewrite this so a first-time visitor reads it in 20 seconds. Cut every word
that could appear on anyone else's website. Keep our real names, times and places.
```

## Design

- **Look at three good ones first.** Before building a page, find three sites you think look great and tell Claude what you like about each. "Make it look good" gets you nothing. "Big type like Apple's product pages, lots of space, one color for buttons" gets you something.
- **Phone first.** Most people opening a link you send are on a phone. Check every page at 390px wide.
- **One accent color.** Use it on the thing you want people to tap. Nothing else.
- **Real photos over stock.** You already have photos of real people and real moments. Use them.
- **Motion that means something.** If an animation doesn't help someone understand, cut it.

Prompt:

```text
Look at this page like a picky designer seeing it for the first time on a phone.
List the five things that make it look generic or AI-made, worst first. Then fix them
one at a time and show me after each.
```

## Efficiency

- **Small asks finish faster than big ones.** Fifteen 5-minute asks beat one 2-hour ask that goes sideways.
- **Start a fresh session for a new task.** Long chats get confused. `/clear` in Claude Code starts over.
- **Put repeat instructions in CLAUDE.md** so you never type them twice.
- **Paste errors exactly.** "It broke" wastes a turn. The full red error text fixes it in one.
- **Make it check its own work.** "Run it and show me" catches most mistakes before you do.

## Honesty

Never let AI invent a number, a quote or a fact about a real person or your organization. If it doesn't have a source, it stays out. Trust takes years to build and one made-up number to lose.

Next: [Your work and operations](08-work-and-ops.md)
