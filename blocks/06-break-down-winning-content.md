---
name: 06-break-down-winning-content
block: 6 of 9
lever: Analyse
cadence: Weekly
reads: [data/citation-openings.md, context.md]
writes: data/winning-pages.md
---

# 6. Break down winning content

**Lever:** Analyse. **Run:** weekly. **Goal:** Study the pages AI keeps citing: their structure, their rhythm and what they all skip.

Before you start, read: `data/citation-openings.md`, `context.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Page anatomy [cited URL]

You get: Its sections, order and length.
Fill the brackets from: the most-cited page for a target prompt (data/citation-openings.md).

```text
Analyse this page that AI keeps citing: [cited URL]. List its sections in order with the word count of each, the headings used, where the direct answer appears, and any tables, lists, FAQs or data. Keep it factual.
```

### 2. /Beat map [cited URL]

You get: The rhythm: claim, proof, example, answer.
Fill the brackets from: the most-cited page for a target prompt (data/citation-openings.md).

```text
Read [cited URL] and map its rhythm, paragraph by paragraph: claim, proof, example, answer, or transition. Show the pattern as a short sequence and note where it earns trust (a number, a source, a named expert).
```

### 3. /What's missing [3 cited URLs]

You get: What every winning page skips.
Fill the brackets from: the 3 most-cited pages for one target prompt.

```text
Here are 3 pages AI cites for the same question: [3 cited URLs]. List what all three cover, what only one covers, and what none of them cover that a buyer would still want to know. The last list is our opening.
```

### 4. /Answer-first check [your page]

You get: Does it answer in the first 100 words?.
Fill the brackets from: your page for that prompt.

```text
Read the opening of [your page]. Does it answer the main question directly in the first 100 words, in a sentence AI could quote on its own? If not, rewrite the opening so it does, without losing the brand voice.
```

### 5. /Compare pages [yours + winner]

You get: Side by side, section by section.
Fill the brackets from: context.md.

```text
Compare our page [yours] with the page AI cites instead [winner], section by section: structure, depth, proof, freshness and clarity. End with the 5 changes most likely to make AI cite ours.
```

## Save

- Write the combined result to `data/winning-pages.md` (replace the old version, keep a dated copy in `outputs/06-break-down-winning-content/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Brief the new pages** when the master file says this cycle includes it.
