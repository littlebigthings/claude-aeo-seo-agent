---
name: 08-brief-the-new-pages
block: 8 of 9
lever: Recommend
cadence: Weekly
reads: [data/plan.md, data/winning-pages.md, data/prompt-set.md]
writes: briefs/YYYY-MM-DD-<page>.md
---

# 8. Brief the new pages

**Lever:** Recommend. **Run:** weekly. **Goal:** Write briefs that match what wins in AI answers and add what's missing.

Before you start, read: `data/plan.md`, `data/winning-pages.md`, `data/prompt-set.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Page brief for [prompt]

You get: An outline built on what wins, plus what's missing.
Fill the brackets from: each prompt in data/prompt-set.md, or the one the plan names.

```text
Write a page brief to win AI answers for this buyer question: [prompt]. Base the structure on the pages AI cites today, then add what they miss. Include the title, the direct answer in 2 sentences, section headings, proof to include, and FAQs.
```

### 2. /First 100 words [brief]

You get: The direct answer AI can quote.
Fill the brackets from: the brief written by /Page brief for.

```text
Using this brief: [brief], write the first 100 words of the page. Answer the question directly in the first sentence, name our brand once in a factual claim, and make every sentence quotable on its own.
```

### 3. /Proof points for [topic]

You get: Data, quotes and examples to include.
Fill the brackets from: each priority topic in data/topic-map.md, one at a time.

```text
For a page about [topic], list the proof that would make it credible: our own data we could share, outside studies with sources, expert quotes we could get, and examples. Mark which ones we likely have and which we need to create.
```

### 4. /Follow-ups from [prompt set]

You get: The next questions the page must answer.
Fill the brackets from: data/prompt-set.md.

```text
For this question set: [prompt set], list the follow-up questions a buyer would ask next in the same AI conversation. The page should answer these too, so group them under the section where each belongs.
```

### 5. /Brand in the claim [draft]

You get: Puts your name in each stat so AI credits you.
Fill the brackets from: a draft in drafts/ (only when one exists).

```text
Edit this draft: [draft] so every statistic, finding and claim names our brand or study in the same sentence (for example "[Brand]'s 2026 survey found..." instead of "Studies show..."). Change nothing else.
```

## Save

- Write the combined result to `briefs/YYYY-MM-DD-<page>.md` (replace the old version, keep a dated copy in `outputs/08-brief-the-new-pages/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Track and report** when the master file says this cycle includes it.
