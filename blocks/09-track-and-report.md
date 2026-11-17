---
name: 09-track-and-report
block: 9 of 9
lever: Recommend
cadence: Weekly
reads: [inputs/tracking/ (this week's AI answers), data/fixes-log.md, data/prompt-set.md]
writes: reports/YYYY-MM-DD-weekly.md
---

# 9. Track and report

**Lever:** Recommend. **Run:** weekly. **Goal:** Prove the changes moved your AI visibility, and decide what to do next week.

Before you start, read: `inputs/tracking/ (this week's AI answers)`, `data/fixes-log.md`, `data/prompt-set.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Weekly changes [this week's answers]

You get: What moved, up or down, and why.
Fill the brackets from: inputs/tracking/ (this week and last week).

```text
Here are this week's AI answers for our tracked prompts, with last week's for comparison: [this week's answers]. List what changed: prompts where we appeared or dropped, new competitors named, and new sources cited. Suggest a likely reason for each change.
```

### 2. /Share of answer [tracking data]

You get: Your share against each peer.
Fill the brackets from: inputs/tracking/.

```text
From this tracking data: [tracking data], calculate how often we are mentioned compared with each competitor, overall and by topic. Show it as a simple table and point out the biggest shift since last time.
```

### 3. /Win log [fixes + results]

You get: Which fixes moved which prompts.
Fill the brackets from: data/fixes-log.md + inputs/tracking/.

```text
Here are the fixes we shipped and our tracking results: [fixes + results]. Match each fix to the prompts that moved after it, with dates. Flag fixes with no visible effect yet, so we know what to wait on and what to drop.
```

### 4. /Leadership summary [month's data]

You get: Five lines a CMO reads in a minute.
Fill the brackets from: the last 4 weekly reports.

```text
Summarise this month's AI search data: [month's data] in 5 lines a CMO can read in a minute: where we stand, what moved, why, what we are doing next, and one number to watch. No jargon.
```

### 5. /Next week [results]

You get: What to double down on, and what to drop.
Fill the brackets from: this week's report.

```text
Based on these results: [results], tell me what to double down on, what to stop, and the one test to run next week. Keep it to 6 bullets.
```

## Save

- Write the combined result to `reports/YYYY-MM-DD-weekly.md` (replace the old version, keep a dated copy in `outputs/09-track-and-report/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Break down winning content** when the master file says this cycle includes it.
