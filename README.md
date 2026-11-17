# 45 Claude prompts for AEO and SEO, as an agent

45 prompts that run an AI search program for a B2B company, split into 9 blocks across three levers: **Research** (know the field), **Analyse** (read what AI sees) and **Recommend** (decide what to add). One master file, `AGENT.md`, runs them in the right order, weekly, monthly and quarterly.

By Veer Manhas, founder of [Lil Big Things](https://lilbigthings.com), a B2B agency for AI search visibility and websites.

## What's inside

```text
AGENT.md          the master file: cycles, run order, where every input comes from, rules
CLAUDE.md         points Claude Code at AGENT.md
context.md        your company's details (fill in once)
blocks/           the 9 blocks, 5 prompts each, full text
data/             working lists the blocks pass to each other
inputs/           what you add: tracking answers, call notes
outputs/ briefs/ reports/   what the agent produces
.claude/commands/ /setup, /weekly, /monthly, /quarterly, /block for Claude Code
```

## Set it up as an agent

### Option 1: Claude Code (runs end to end, saves files)

1. Download or clone this folder.
2. Fill in `context.md`.
3. Open the folder in Claude Code. It reads `CLAUDE.md`, which points it to `AGENT.md`.
4. Type `/setup` for the first run. After that: `/weekly` every week, `/monthly` at the start of each month, `/quarterly` every 3 months. `/block 5` runs one block.
5. Let it use web search and web fetch when it asks; the Research and Analyse blocks read live pages.
6. Each week, drop your AI answers or tracking export into `inputs/tracking/` before `/weekly`, and add what you shipped to `data/fixes-log.md`.

### Option 2: a Claude Project (no install)

1. Create a Project in Claude.
2. Paste the contents of `AGENT.md` into the project instructions.
3. Upload `context.md` (filled in) and the 9 files in `blocks/` to the project knowledge.
4. Turn on web search.
5. Start a chat: "Run the setup cycle." Then "Run the weekly cycle" each week, pasting your tracking answers into the chat.
6. A Project can't save files between chats, so ask Claude to give you each block's output as a file, and upload the updated `data/` files back to the project knowledge.

### Option 3: one prompt at a time

Open any file in `blocks/`, copy a prompt, fill in the brackets and paste it into Claude. No setup.

### Running it on a schedule

If your Claude setup supports scheduled tasks, schedule the weekly run with the prompt "Read AGENT.md and run the weekly cycle." Check its output before acting on it: the agent recommends, you decide.

## Before you rely on it

- Claude can only answer as Claude. For ChatGPT, Gemini, Perplexity and Google AI Overviews, bring the answers in from your AI visibility tool or copy them by hand into `inputs/tracking/`.
- Turn on web search, or the Research and Analyse blocks will guess.
- The agent marks anything it couldn't verify with [check]. Check those before they reach a report.
- It never publishes, sends outreach or edits your site. It drafts; you ship.

## The 45 prompts

**1. Benchmark your peers** (quarterly)

- `/Peer list for` [your site]: 15 companies buyers compare you with
- `/Segment peers` [peer list]: Grouped by who they sell to and how
- `/Position map` [peer list]: Where each one claims to win, and where nobody does
- `/Peer site scan` [peer URLs]: Their key pages and what each one targets
- `/Benchmark table` [you + peers]: Offer, pricing, proof and content depth in one table

**2. Map the topics** (quarterly)

- `/Topic map for` [category]: Every topic a buyer researches, grouped by stage
- `/Subtopics of` [topic]: The questions that sit under one topic
- `/Topic gaps` [your sitemap]: Topics you have no page for yet
- `/Topic owners` [topic]: Which peer owns each topic today
- `/Priority topics` [topic map]: Ranked by buyer intent and your expertise

**3. Build your prompt set** (quarterly)

- `/Buyer prompts for` [topic]: 20 questions buyers would ask AI
- `/Prompt mix` [prompt list]: Split into awareness, comparison and decision
- `/Call questions from` [call notes]: Prompts in your buyers' own words
- `/Unbranded check` [prompt list]: Takes your brand out so the test is fair
- `/Tracking set` [prompt list]: The 50 prompts worth tracking every month

**4. Check how AI describes you** (monthly)

- `/How AI sees` [brand]: What AI says you do, for whom, and how well
- `/Description gap` [homepage + AI answer]: Where AI's version differs from yours
- `/Wrong facts in` [AI answer]: Claims that are outdated or false
- `/Peer descriptions` [peers]: How AI describes each competitor, side by side
- `/Fix list for` [gaps]: The pages to change so AI tells it right

**5. Find citation openings** (monthly)

- `/Cited sources for` [prompt]: The sites AI quotes for this question
- `/Source types` [source list]: Reviews, lists, forums, media or docs
- `/Open doors` [source list]: Sites that cite your peers but not you
- `/Pitch angle for` [site]: Why this site would include you
- `/Outreach plan` [openings]: Who to contact first, ranked by impact

**6. Break down winning content** (weekly)

- `/Page anatomy` [cited URL]: Its sections, order and length
- `/Beat map` [cited URL]: The rhythm: claim, proof, example, answer
- `/What's missing` [3 cited URLs]: What every winning page skips
- `/Answer-first check` [your page]: Does it answer in the first 100 words?
- `/Compare pages` [yours + winner]: Side by side, section by section

**7. Recommend what to add** (monthly)

- `/Gap ranking` [gaps + openings]: Ranked by impact and effort
- `/Page or update` [gap]: A new page, or a fix to one you have
- `/Quick wins` [page list]: Changes you can ship this week
- `/Month plan` [ranked gaps]: What to do in weeks 1 to 4
- `/Case for` [recommendation]: One paragraph your boss will approve

**8. Brief the new pages** (weekly)

- `/Page brief for` [prompt]: An outline built on what wins, plus what's missing
- `/First 100 words` [brief]: The direct answer AI can quote
- `/Proof points for` [topic]: Data, quotes and examples to include
- `/Follow-ups from` [prompt set]: The next questions the page must answer
- `/Brand in the claim` [draft]: Puts your name in each stat so AI credits you

**9. Track and report** (weekly)

- `/Weekly changes` [this week's answers]: What moved, up or down, and why
- `/Share of answer` [tracking data]: Your share against each peer
- `/Win log` [fixes + results]: Which fixes moved which prompts
- `/Leadership summary` [month's data]: Five lines a CMO reads in a minute
- `/Next week` [results]: What to double down on, and what to drop

## Feedback

Tried it? Tell me what worked and what didn't on LinkedIn, or open an issue here. I'd love to make it better.

More on AI search for B2B: [lilbigthings.com](https://lilbigthings.com)
