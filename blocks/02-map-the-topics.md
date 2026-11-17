---
name: 02-map-the-topics
block: 2 of 9
lever: Research
cadence: Quarterly
reads: [context.md, data/peers.md]
writes: data/topic-map.md
---

# 2. Map the topics

**Lever:** Research. **Run:** quarterly. **Goal:** Break your category into the topics buyers research, and find the ones you have no page for.

Before you start, read: `context.md`, `data/peers.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Topic map for [category]

You get: Every topic a buyer researches, grouped by stage.
Fill the brackets from: context.md (Category).

```text
I sell [category] to B2B buyers. List every topic a buyer researches before they buy, grouped by stage: understanding the problem, comparing options, and deciding. Give 8 to 12 topics per stage, written the way a buyer would say them, not as keywords.
```

### 2. /Subtopics of [topic]

You get: The questions that sit under one topic.
Fill the brackets from: each priority topic in data/topic-map.md, one at a time.

```text
Break down [topic] into the 10 to 15 specific questions a B2B buyer asks about it. Order them from first question to last. For each, note the job title most likely to ask it.
```

### 3. /Topic gaps [your sitemap]

You get: Topics you have no page for yet.
Fill the brackets from: context.md (Sitemap), fetched; data/topic-map.md.

```text
Here is my sitemap or page list: [your sitemap]. Compare it to this topic map: [topic map]. List the topics we have no page for, the topics we cover thinly (one page for a big topic), and the pages that cover no buyer topic at all.
```

### 4. /Topic owners [topic]

You get: Which peer owns each topic today.
Fill the brackets from: each priority topic in data/topic-map.md, one at a time.

```text
For [topic], search the web and the answers AI assistants give, and tell me which company is seen as the authority today. Name the pages, studies or tools that earn them that spot, and what it would take to compete.
```

### 5. /Priority topics [topic map]

You get: Ranked by buyer intent and your expertise.
Fill the brackets from: data/topic-map.md.

```text
Here is my topic map: [topic map]. Score each topic from 1 to 5 on buyer intent (how close it is to a purchase) and on our expertise (how credibly we can speak to it). Rank the top 10 and say why each made the list.
```

## Save

- Write the combined result to `data/topic-map.md` (replace the old version, keep a dated copy in `outputs/02-map-the-topics/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Build your prompt set** when the master file says this cycle includes it.
