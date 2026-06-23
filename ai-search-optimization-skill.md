---
name: ai-search-optimization
description: >-
  Optimize content to be cited inside AI-generated answers from ChatGPT, Claude, Perplexity, Gemini, and Google AI Overviews. Use when the user mentions AI SEO, AEO, GEO, LLMO, answer engine optimization, generative engine optimization, AI citations, AI visibility, zero-click search, getting cited by ChatGPT or Perplexity, or wants their site found when buyers research inside an AI tool.
---

# AI Search Optimization (AEO / GEO)

**Get your content cited inside AI-generated answers — not just ranked in traditional search.**

---

## What This Skill Does

This skill helps you optimize your website and content so that AI assistants like ChatGPT, Claude, Perplexity, Gemini, and Google AI Overviews cite you as a source when answering questions related to your business. Traditional SEO earns you a ranking. AI search optimization earns you a citation — your words, attributed to you, inside the answer a prospect reads.

For any early-stage startup or small business, this matters because a growing share of buying research now starts inside an AI tool, not a search engine. Getting cited there builds authority, drives traffic, and reaches buyers who never click traditional search results.

---

## When to Use This Skill

Use this skill when you want to:

- Appear in AI-generated answers when prospects research your category
- Get cited by ChatGPT, Perplexity, Claude, Gemini, or Google AI Overviews
- Audit why competitors are showing up in AI answers and you're not
- Optimize existing pages or plan new content for AI citation
- Understand which content types AI engines prefer

**Trigger phrases:** "AI SEO," "show up in AI answers," "get cited by ChatGPT," "AI Overviews," "answer engine optimization," "AEO," "GEO," "generative engine optimization," "optimize for Perplexity," "AI citations," "AI visibility"

---

## How AI Search Works

Different engines choose sources differently. Optimize for the mix your audience uses.

| Engine | How it selects sources | What it favors |
|--------|----------------------|----------------|
| Google AI Overviews | Summarizes top-ranking pages | Classic ranking signals + E-E-A-T |
| ChatGPT (with search) | Searches broadly, cites results | Recent, structured, authoritative content |
| Perplexity | Always cites with links | Well-organized, credible, current pages |
| Gemini | Google index + Knowledge Graph | Google ranking signals + entity recognition |
| Copilot | Bing-powered | Bing index + authoritative sources |
| Claude (with search) | Web search + training data | Clear, factual, well-organized sources |

**The key insight:** In classic search, you must rank on page one. In AI search, a well-structured page can get cited even from page two or three — because engines extract passages by quality and clarity, not rank position alone.

**One safe rule for both worlds:** Write for people, organize for clarity. Google warns against creating separate "AI content" (it risks spam penalties). But the structure that helps non-Google engines also doesn't hurt Google. Clean organization satisfies both.

---

## Step-by-Step Instructions

### Step 1 — Run a Visibility Audit

Before optimizing anything, find out where you stand.

Test your 10–20 most important queries across ChatGPT, Perplexity, and Google. For each query, log:
- Does an AI answer appear?
- Are you cited anywhere in it?
- Who is cited instead of you?

**Useful query shapes to test:**
- "What is [your category]?"
- "Best [your category] for [use case]"
- "[Your brand] vs [competitor]"
- "How to [problem you solve]"
- "[Category] pricing"
- "How does [your category] work?"

Record results in a simple table: query, engine, cited?, who's cited.

---

### Step 2 — Check Your Site's Extractability

For each priority page, verify these elements are present:

- [ ] A clear, one-sentence definition or answer in the first paragraph
- [ ] Self-contained answer blocks that make sense without surrounding context
- [ ] Statistics with named, dated sources
- [ ] A comparison table for any "X vs Y" or "which is better" intent
- [ ] A FAQ section written in natural question phrasing
- [ ] Schema markup matching the content type (see Step 5)
- [ ] A named author with visible credentials or bio
- [ ] A visible "last updated" date
- [ ] Headings phrased the way users ask questions

---

### Step 3 — Check Bot Access

If an AI engine's crawler is blocked, that engine cannot cite you — full stop.

Open your `robots.txt` file and confirm you are **not** blocking:
- `GPTBot` or `ChatGPT-User` — OpenAI / ChatGPT
- `PerplexityBot` — Perplexity
- `ClaudeBot` or `anthropic-ai` — Anthropic / Claude
- `Google-Extended` — Gemini and Google AI Overviews
- `Bingbot` — Microsoft Copilot

You may separately choose to block training-only crawlers like `CCBot` (Common Crawl) — that won't affect citations. But the search-and-cite bots above need access if you want to appear in answers.

---

### Step 4 — Apply the Three Optimization Pillars

**Pillar 1: Structure — Make content extractable**

AI systems extract passages, not whole pages. Every key answer must stand on its own.

- Lead each section with the direct answer, then elaborate
- Keep core answer passages to roughly 40–60 words (long enough to be complete, short enough to lift cleanly)
- Write H2/H3 headings as the questions your audience asks
- Use tables for comparisons, numbered lists for processes, one idea per paragraph

Reusable content block patterns:

| Block type | When to use | Format |
|-----------|-------------|--------|
| Definition block | "What is X?" queries | One-sentence definition, then 2–3 sentences of context |
| Comparison table | "X vs Y" queries | Columns per option, rows per dimension |
| Step block | "How to X" queries | Numbered, each step self-contained |
| Stat block | Any factual claim | Specific number + source + date |
| FAQ block | Common questions | H3 question, tight paragraph answer |

**Pillar 2: Authority — Make content citable**

Research on AI citation patterns (Princeton GEO study, Perplexity.ai data) found these levers reliably increase citation rates. Treat this as a priority order, not a checklist to spam:

| Lever | Approx. lift | How to apply |
|-------|-------------|--------------|
| Cite your sources | ~+40% | Link to authoritative references for factual claims |
| Add specific statistics | ~+37% | Named numbers with source and date |
| Include expert quotes | ~+30% | Named people, with title and organization |
| Write authoritatively | ~+25% | Demonstrate expertise; avoid hedging |
| Improve clarity | ~+20% | Simplify complex concepts |
| Use domain vocabulary | ~+18% | Use correct technical terminology |
| Keyword stuffing | **−10%** | Actively hurts AI visibility — never do this |

Also: name your authors with credentials, show first-hand experience, add an explicit "last updated" date and refresh competitive content quarterly.

**Pillar 3: Presence — Be where AI looks**

AI engines often cite third-party sources more than your own domain. Build presence where they look:

- Maintain an accurate, current Wikipedia or Wikidata entry for your brand
- Participate authentically in communities your audience uses (Reddit, Hacker News, forums, Discord)
- Get included in industry roundups and "best of" listicles
- Keep profiles current on relevant review sites (G2, Capterra, TrustRadius for B2B; app stores for consumer)
- Create YouTube content for how-to queries — Google's AI Overviews frequently cite YouTube
- Answer relevant questions on Quora and similar platforms

Only genuine participation counts. Fabricated mentions or bulk-spam tactics get detected and de-rank you.

---

### Step 5 — Add Machine-Readable Files

These files help non-Google AI engines and autonomous research agents understand your product without rendering JavaScript. They do not hurt Google.

**`/llms.txt`** — A short plain-text file (see llmstxt.org) describing what your product does, who it's for, and links to your key pages. Think of it as a structured introduction for AI systems.

**`/pricing.md` or `/pricing.txt`** — Plain-text pricing organized by tier: price, limits, what's included. AI agents evaluating tools programmatically skip products whose pricing is locked behind JavaScript or a "contact sales" wall.

Keep both current — stale machine-readable data is worse than none.

---

### Step 6 — Add Schema Markup

Structured data helps AI systems understand what your content is and extract it accurately.

| Content type | Schema to use |
|-------------|--------------|
| Blog posts / articles | `Article` or `BlogPosting` |
| How-to guides | `HowTo` |
| FAQ sections | `FAQPage` |
| Product or software pages | `Product` or `SoftwareApplication` |
| Comparison content | `ItemList` |
| Reviews | `Review` or `AggregateRating` |
| Your organization | `Organization` |

---

### Step 7 — Prioritize High-Citation Content Types

Invest in formats that consistently get cited most:

1. Comparison and alternative articles
2. Definitive guides on your core topic
3. Original research and data you've generated
4. "Best of" and category roundups
5. Detailed product or feature pages
6. How-to guides with clear steps
7. Expert analysis and opinion pieces

**Avoid or fix:** Generic unstructured blog posts, thin marketing pages, gated content (AI can't access it), undated pages, pages without author attribution, PDF-only content.

---

### Step 8 — Monitor Monthly

Track your AI visibility over time. Each month:

1. Run your top 20 queries through ChatGPT, Perplexity, and Google
2. Log: are you cited? Who is? Which of your pages earned the citation?
3. Track the trend month-over-month

Optional tools for automating this: Otterly, Peec AI, ZipTie, LLMrefs. For Google specifically, there is no AI-specific Search Console report — use standard SEO metrics there.

---

## Quality Checks and Guardrails

Before delivering any optimization recommendations, verify:

- [ ] Every recommendation is specific to a named page or content type — not generic
- [ ] No advice conflicts with Google's spam policies (no "write separate AI content," no content fragmentation)
- [ ] Bot-access check has been done before recommending content changes
- [ ] Schema recommendations match the actual content type of the page
- [ ] Citations and statistics recommended have real, named, dated sources — never fabricated
- [ ] Third-party presence advice is genuine participation only — no fake mentions or paid placements
- [ ] Machine-readable files recommended are kept current, not created and forgotten

---

## Expected Output Format

When running an audit or producing optimization recommendations, deliver:

```
# AI Search Optimization — [Site or Page Name]

## Current Visibility
| Query | Engine | Cited? | Who's cited instead |
|-------|--------|--------|-------------------|
| ...   | ...    | ...    | ...               |

## Quick Wins (implement this week)
- [Specific change] → [Page it applies to] → [Why it helps]

## Structural Fixes
- [Page] → [Block pattern to add or rewrite: definition / comparison table / FAQ / stat]

## Authority & Presence Plan
- [Source to add, expert to quote, community to participate in, third-party listing to claim]

## Technical Actions
- robots.txt: [any crawlers to unblock]
- llms.txt: [create / update / current status]
- pricing.md: [create / update / current status]
- Schema: [pages needing markup + type]

## Monitoring Plan
- Queries to track monthly: [list]
- How to log: [simple table or tool]
- Who owns it: [role]
```
