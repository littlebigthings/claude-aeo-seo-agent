---
name: 04-check-how-ai-describes-you
block: 4 of 9
lever: Analyse
cadence: Monthly
reads: [context.md, data/peers.md]
writes: data/description-gaps.md
---

# 4. Check how AI describes you

**Lever:** Analyse. **Run:** monthly. **Goal:** See what AI says about you and your peers today, and list the fixes that make it tell your story right.

Before you start, read: `context.md`, `data/peers.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /How AI sees [brand]

You get: What AI says you do, for whom, and how well.
Fill the brackets from: context.md (Brand).

```text
Describe [brand] as you would to a B2B buyer who asked about it. Then answer: what do they do, who is it for, what are they best at, what are the drawbacks, and who are the main alternatives? Say where your information comes from and how confident you are.
```

### 2. /Description gap [homepage + AI answer]

You get: Where AI's version differs from yours.
Fill the brackets from: fetch the homepage from context.md (Website); the answer saved by /How AI sees.

```text
Here is our homepage copy: [homepage] and here is how an AI assistant described us: [AI answer]. List where the two differ: wrong category, wrong audience, missing strengths, outdated facts, or weaker wording. Rank the gaps by how much they would hurt a sale.
```

### 3. /Wrong facts in [AI answer]

You get: Claims that are outdated or false.
Fill the brackets from: the answer saved by /How AI sees.

```text
Check this AI answer about our company: [AI answer]. List every claim that is wrong, outdated or unsupported, next to the correct fact. For each, suggest which page on our site should state the right fact clearly so AI can pick it up.
```

### 4. /Peer descriptions [peers]

You get: How AI describes each competitor, side by side.
Fill the brackets from: data/peers.md.

```text
Describe each of these companies the way you would to a buyer: [peers]. Use the same format for each: what they do, who it's for, best at, drawbacks. Put them side by side in a table so I can see how we are positioned against them.
```

### 5. /Fix list for [gaps]

You get: The pages to change so AI tells it right.
Fill the brackets from: data/description-gaps.md.

```text
Here are the gaps between how we describe ourselves and how AI describes us: [gaps]. For each, name the page to change, the exact line to add or rewrite, and any outside source (review site, directory, article) that should say the same thing.
```

## Save

- Write the combined result to `data/description-gaps.md` (replace the old version, keep a dated copy in `outputs/04-check-how-ai-describes-you/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Find citation openings** when the master file says this cycle includes it.
