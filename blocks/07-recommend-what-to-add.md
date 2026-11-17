---
name: 07-recommend-what-to-add
block: 7 of 9
lever: Recommend
cadence: Monthly
reads: [data/topic-map.md, data/description-gaps.md, data/citation-openings.md, context.md]
writes: data/plan.md
---

# 7. Recommend what to add

**Lever:** Recommend. **Run:** monthly. **Goal:** Rank the gaps by impact and effort and turn them into a 4-week plan your boss will approve.

Before you start, read: `data/topic-map.md`, `data/description-gaps.md`, `data/citation-openings.md`, `context.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Gap ranking [gaps + openings]

You get: Ranked by impact and effort.
Fill the brackets from: data/description-gaps.md + data/citation-openings.md + topic gaps.

```text
Here are our topic gaps and citation openings: [gaps + openings]. Score each on impact (buyer intent and how often AI is asked) and effort (new page, page fix, or outside work). Return a ranked list with the reason for each score.
```

### 2. /Page or update [gap]

You get: A new page, or a fix to one you have.
Fill the brackets from: context.md (Sitemap), fetched; each top gap from /Gap ranking.

```text
For this gap: [gap], should we build a new page or improve an existing one? Check our sitemap [sitemap] for a page that could own it. Recommend one option and explain why in 3 lines.
```

### 3. /Quick wins [page list]

You get: Changes you can ship this week.
Fill the brackets from: the pages named in the ranked gaps.

```text
Review these pages: [page list]. Find changes we can ship this week in under 2 hours each: a direct answer up top, a missing FAQ, a stat with our name in it, a clearer heading. List them by page.
```

### 4. /Month plan [ranked gaps]

You get: What to do in weeks 1 to 4.
Fill the brackets from: the /Gap ranking output.

```text
Turn this ranked list: [ranked gaps] into a 4-week plan. For each week, give 3 to 5 tasks, who usually owns them (content, web, PR), and what done looks like. Keep week 1 to quick wins.
```

### 5. /Case for [recommendation]

You get: One paragraph your boss will approve.
Fill the brackets from: the top item in data/plan.md.

```text
Write a one-paragraph case for this recommendation: [recommendation], for a CMO who has 30 seconds. Say what we found, what we will change, what it costs in time, and how we will know it worked. No jargon.
```

## Save

- Write the combined result to `data/plan.md` (replace the old version, keep a dated copy in `outputs/07-recommend-what-to-add/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Brief the new pages** when the master file says this cycle includes it.
