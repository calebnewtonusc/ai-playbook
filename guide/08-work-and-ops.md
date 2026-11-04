# 8. Using AI for your work and operations

Operations is where AI saves the most hours, because so much of it is the same task every week. That's true whether you run a church, a small business, a film shoot, a club or a family calendar.

## Start with what repeats

Write down everything you do every week. The best first project is the one that's annoying, repetitive, and low risk if it goes wrong.

Prompt (in the Claude app, no code needed):

```text
I'm [your role] at [your organization, its size]. Here's everything I do
in a normal week: [list, or just talk it through]. Which three could AI or a
small tool take off my plate, ranked by hours saved and how risky it would be
if it made a mistake? For each, tell me the simplest version I could set up myself.
```

## Ideas, by how much setup they need

**No code at all (the Claude app):**

- Turn meeting or sermon notes into a discussion guide, a recap email, or a task list
- Draft the weekly announcement or update email from a bullet list
- Rewrite your "about" or "new here" page so a first-time visitor gets it in 20 seconds
- Turn a messy spreadsheet of people into a clean schedule
- With connectors on: a morning summary of what needs you today ([everyday level 4](../everyday/level-4-connect-your-stuff.md))

**Small builds with Claude Code:**

- A sign-up page for an event, deployed on Vercel ([guide step 3](03-first-project.md))
- A page that reads your volunteer or staff spreadsheet and shows each person their next shift
- A text-based intake for new people: one question per text, answers saved for whoever follows up
- A simple contact tracker that tells you who you haven't talked to in a while
- A weekly search for grants, scholarships or leads that match what you're looking for, written up as a list for you to review

**If your tool has an API** (Planning Center, Google Sheets, Airtable, most CRMs and email platforms do): Claude Code can read your data and build reports on it. Start read-only.

**If your site is on Squarespace or Wix:** Claude can't edit it directly, but it can write the copy and the layout plan, and you paste it in.

## Rules for anything touching people's info

- Nothing gets shared without the person's yes
- Hard or sensitive moments go to a real person, never the AI
- Test with fake names until you're sure it works
- Keep passwords and API keys out of your code and out of chats
- Check with whoever's responsible before anything new talks to your people, customers or members

The [case study app](06-case-study-app-in-a-day.md) was built on exactly these rules.
