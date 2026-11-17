---
name: 05-find-citation-openings
block: 5 of 9
lever: Analyse
cadence: Monthly
reads: [data/prompt-set.md, data/peers.md]
writes: data/citation-openings.md
---

# 5. Find citation openings

**Lever:** Analyse. **Run:** monthly. **Goal:** Find the sites AI cites for your prompts, and the ones that name your peers but not you.

Before you start, read: `data/prompt-set.md`, `data/peers.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Cited sources for [prompt]

You get: The sites AI quotes for this question.
Fill the brackets from: each prompt in data/prompt-set.md, or the one the plan names.

```text
Answer this buyer question as an AI assistant would: [prompt]. Then list every source you would rely on: the site, the page, and what it contributed. Group them into our site, competitor sites, and third-party sites.
```

### 2. /Source types [source list]

You get: Reviews, lists, forums, media or docs.
Fill the brackets from: the sources saved by /Cited sources for.

```text
Here is a list of sources AI cites in our category: [source list]. Sort them into reviews, best-of lists, forums and communities, media and analysts, vendor docs, and other. Tell me which type shows up most and what that says about where to focus.
```

### 3. /Open doors [source list]

You get: Sites that cite your peers but not you.
Fill the brackets from: the sources saved by /Cited sources for.

```text
From this source list: [source list], find the sites that mention our competitors but not us. For each, note the page, which competitors it names, and whether it looks open to adding vendors (a list, a directory, a review site, a guest-post section).
```

### 4. /Pitch angle for [site]

You get: Why this site would include you.
Fill the brackets from: each open door in data/citation-openings.md.

```text
Read this site: [site]. Write the angle that would make them include us: what their readers care about, what we can offer that their page lacks (data, an expert quote, a tool), and a 3-sentence pitch to the editor.
```

### 5. /Outreach plan [openings]

You get: Who to contact first, ranked by impact.
Fill the brackets from: data/citation-openings.md.

```text
Here are our citation openings: [openings]. Rank them by impact (how often AI cites the site, how relevant the audience is) and effort (how easy it is to get in). Give me a 4-week outreach order with the first action for each.
```

## Save

- Write the combined result to `data/citation-openings.md` (replace the old version, keep a dated copy in `outputs/05-find-citation-openings/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Recommend what to add** when the master file says this cycle includes it.
