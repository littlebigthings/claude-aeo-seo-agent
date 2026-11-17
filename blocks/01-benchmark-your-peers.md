---
name: 01-benchmark-your-peers
block: 1 of 9
lever: Research
cadence: Quarterly
reads: [context.md]
writes: data/peers.md
---

# 1. Benchmark your peers

**Lever:** Research. **Run:** quarterly. **Goal:** Find the companies buyers compare you with and sort them into segments.

Before you start, read: `context.md`. If a file you need is missing or empty, stop and say which block fills it.

## The 5 prompts, in order

### 1. /Peer list for [your site]

You get: 15 companies buyers compare you with.
Fill the brackets from: context.md (Website).

```text
You are a B2B market analyst. My company is [your site]. Use web search to find the 15 companies a buyer is most likely to compare us with: direct competitors, alternatives and the do-it-yourself option. For each, give the name, website, one line on what they sell, and why a buyer would shortlist them. Flag which ones you are unsure about.
```

### 2. /Segment peers [peer list]

You get: Grouped by who they sell to and how.
Fill the brackets from: context.md (Website); data/peers.md.

```text
Here is my list of peers: [peer list]. Sort them into 3 to 5 segments based on who they sell to (company size, industry, buyer role) and how they sell (self-serve, sales-led, services). Give each segment a plain name, list who sits in it, and say which segment my company [your site] belongs to and why.
```

### 3. /Position map [peer list]

You get: Where each one claims to win, and where nobody does.
Fill the brackets from: data/peers.md.

```text
For each company in [peer list], read their homepage and main product page and write the one claim they lead with. Then show where the claims overlap, which claims nobody makes, and one open position my company could own. Keep each claim in the company's own words.
```

### 4. /Peer site scan [peer URLs]

You get: Their key pages and what each one targets.
Fill the brackets from: data/peers.md (websites).

```text
Review these peer websites: [peer URLs]. For each, list their main pages (product, solutions, pricing, comparison, resources) and the buyer or question each page targets. End with a table of page types they have that we don't.
```

### 5. /Benchmark table [you + peers]

You get: Offer, pricing, proof and content depth in one table.
Fill the brackets from: context.md + data/peers.md.

```text
Build one comparison table for [you + peers] with these columns: core offer, who it is for, pricing model, proof shown (logos, numbers, case studies), and content depth (how many useful pages). Mark where we lead, match or trail each peer. Base it only on what is on their public sites.
```

## Save

- Write the combined result to `data/peers.md` (replace the old version, keep a dated copy in `outputs/01-benchmark-your-peers/YYYY-MM-DD.md`).
- Start the file with the date and the inputs you used.
- Mark anything you could not verify with [check]. Never invent numbers, companies or results.

## Next

Hand off to **Map the topics** when the master file says this cycle includes it.
