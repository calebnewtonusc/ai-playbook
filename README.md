# The AI playbook

A start-from-zero guide to working with AI, for people who want to get sharper from it, not more dependent on it.

I'm Caleb. I build most of what I make with Claude Code, and people keep asking me how. This repo is my answer, written so you can come back to it, copy the prompts straight out of it, and point your own AI at it so it can coach you.

It's built on one belief. Being resourceful, efficient, iterative and creative with AI can be learned. By default people use AI to make slop and slowly hand over their own thinking. Everything here is built to do the opposite: every level pairs what the AI does with what you keep doing yourself.

You don't need to know how to code. Text me if you get stuck.

## Pick your path

| You want to                                                | Start here                                              | Then                                                    |
| ---------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| Use AI to run your work and life, no code                  | [Start without code](guide/00-start-without-code.md)    | The [everyday track](everyday/README.md), levels 0 to 5 |
| Build websites, tools and apps with AI, even if you're new | [The tools](guide/01-tools.md), then guide steps 1 to 8 | The [builder track](track/README.md), levels 0 to 5     |

Both tracks share level 0, [stay the thinker](track/00-stay-the-engineer.md). Read it first whichever way you go.

Plenty of people start on the everyday path and move over once they want something built. That's the whole point of the second path: Claude Code does the building, you make the calls.

## Written for someone specific?

If I sent you this repo, there may be a page with your name on it that says where to start:

- [Ryan](for/ryan.md)
- [Joel](for/joel.md)

Want one for someone you're teaching? See [for/README.md](for/README.md).

## The guide

| Step | Read this                                                                    | Time       | You'll have                                       |
| ---- | ---------------------------------------------------------------------------- | ---------- | ------------------------------------------------- |
| 0    | [Start without code](guide/00-start-without-code.md)                         | 20 min     | Claude set up to know you, and a voice habit      |
| 1    | [The tools, and what to learn first](guide/01-tools.md)                      | 10 min     | A map of every tool and why it exists             |
| 2    | [Set up your computer](guide/02-setup.md)                                    | 45 min     | Claude Code running on your machine               |
| 3    | [Your first project, start to live link](guide/03-first-project.md)          | 1 to 2 hrs | A real site on the internet with your name on it  |
| 4    | [The loop: how to work with AI without building blind](guide/04-the-loop.md) | 15 min     | The habit that makes everything else work         |
| 5    | [Case study: a pitch site in an hour](guide/05-case-study-pitch-site.md)     | 15 min     | How a polished presentation really gets made      |
| 6    | [Case study: an app in one day](guide/06-case-study-app-in-a-day.md)         | 20 min     | How a team ships fast without breaking things     |
| 7    | [Taste: making it look good, not generated](guide/07-taste.md)               | 15 min     | The checklist I run before I show anyone anything |
| 8    | [Using AI for your work and operations](guide/08-work-and-ops.md)            | 15 min     | Your first three things to hand off               |

## The two tracks

The [everyday track](everyday/README.md) is for using AI well without writing code: a Claude that knows you, talking instead of typing, checking what it tells you, connecting your email and calendar, and handing it jobs that repeat.

The [builder track](track/README.md) is the AI-native engineer path: ship a small thing, read and catch the AI being wrong, give it context, build your own setup, then run several agents at once.

Every level ends with a checkpoint you do without help.

## Keep these open while you work

- [prompts/](prompts/): copy-paste prompts for planning, building, fixing, reviewing and writing
- [templates/CLAUDE.md](templates/CLAUDE.md): drop this in every new project so Claude knows your rules
- [skills/coach-me](skills/coach-me/SKILL.md): a skill that turns Claude into a coach for this playbook
- [kit/](kit/): a starter version of my own Claude Code setup (rules, hooks, skills, subagents), installed piece by piece at builder level 4

## Let Claude teach you this repo

Once Claude Code is installed (guide step 2):

```bash
git clone https://github.com/calebnewtonusc/ai-playbook.git
cd ai-playbook
claude
```

Then type: `Read CLAUDE.md and coach me through this playbook, starting where I am.`

No Claude Code yet? In the Claude app, make a Project, paste this repo's link into it, and ask the same thing.

## The short version

If you only remember three things:

1. **Plan before you build.** Ask the AI for a 5 bullet plan and read it before it does anything.
2. **One small slice at a time.** Something you can see working in under 15 minutes.
3. **Make it show you.** It isn't done until you've seen it with your own eyes.

All glory to God! ✝️❤️
