---
name: 03-build-your-prompt-set
block: 3 of 9
lever: Research
cadence: Quarterly
reads: [context.md, data/topic-map.md, inputs/call-notes/ (optional)]
writes: data/prompt-set.md
---

# 3. Build your prompt set

**Lever:** Research. **Run:** quarterly. **Goal:** Turn each priority topic into the questions buyers ask AI, then pick the set you track every month.

Before you start, read: `context.md`, `data/topic-map.md`, `inputs/call-notes/ (optional)`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Buyer prompts for [topic]

You get: 20 questions buyers would ask AI.
Fill the brackets from: each priority topic in data/topic-map.md, one at a time.

```text
Write 20 questions a B2B buyer would type into an AI assistant while researching [topic]. Make them long and specific, the way people actually ask AI (25 words is normal). Mix job titles, company sizes and situations. Do not include any brand names.
```

### 2. /Prompt mix [prompt list]

You get: Split into awareness, comparison and decision.
Fill the brackets from: data/prompt-set.md (draft list).

```text
Here is my prompt list: [prompt list]. Label each prompt as awareness (learning the problem), comparison (weighing options) or decision (ready to choose). Tell me if the mix is lopsided and write 5 prompts to fill the thinnest group.
```

### 3. /Call questions from [call notes]

You get: Prompts in your buyers' own words.
Fill the brackets from: inputs/call-notes/.

```text
Here are notes or transcripts from sales and customer calls: [call notes]. Pull out every question the buyer asked, in their own words. Rewrite each as a prompt they might ask an AI assistant before the call. Group them by topic.
```

### 4. /Unbranded check [prompt list]

You get: Takes your brand out so the test is fair.
Fill the brackets from: data/prompt-set.md (draft list).

```text
Review this prompt list: [prompt list]. Remove or rewrite any prompt that names our brand, product or a competitor, so it tests whether AI recommends us without being asked about us. Show the before and after for each change.
```

### 5. /Tracking set [prompt list]

You get: The 50 prompts worth tracking every month.
Fill the brackets from: data/prompt-set.md (draft list).

```text
From this prompt list: [prompt list], choose the 50 prompts most worth tracking every month. Favour prompts with buying intent, cover every priority topic, and keep a mix of awareness, comparison and decision. Explain any topic left out.
```

## Save

- Write the combined result to `data/prompt-set.md` (replace the old version, keep a dated copy in `outputs/03-build-your-prompt-set/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Check how AI describes you** when the master file says this cycle includes it.
