---
name: ai-search-optimization-skill
description: >
  Get cited by ChatGPT, Perplexity, Claude, Gemini, Google AI Overviews, and AI assistants.
  8 disciplines for AI citation optimization: GEO (generative engine optimization), LLMO
  (large language model optimization), AIVO (AI visibility optimization),
  CSO (conversational search optimization), AAIO (agentic AI optimization), AI Shopping
  (ChatGPT Checkout, Google AI Shopping), Reddit optimization for AI citations, and multimodal
  search. Use this skill whenever the user wants to appear in AI answers, get cited by AI,
  improve AI visibility, audit brand accuracy in ChatGPT or Perplexity, optimize for AI
  shopping agents, build citation hooks, run Golden Prompt audits, track Share of Model,
  fix AI hallucinations about their brand, optimize Reddit presence for AI training data,
  or prepare for autonomous AI agents. Also trigger on: AI citations, AI search, generative
  engine, LLM optimization, AI answers, "why doesn't ChatGPT mention us", AI brand accuracy,
  AI shopping, agentic commerce. For traditional SEO (Google rankings, backlinks, technical
  SEO, local maps), use the companion ai-seo-skill instead.
---

# AI Search Optimization (8 Disciplines)

Get your brand cited, recommended, and transacted through by AI models.

## Why This Matters

AI models are becoming a primary discovery channel. But they work differently from search engines. Google ranks pages. AI models cite sources, synthesize answers, and increasingly take actions (book, buy, reserve) on behalf of users. Optimizing for AI requires different tactics than traditional SEO.

Key numbers:
- 40.1% of AI citations come from Reddit (Profound, 2025)
- 33 to 48% of AI responses contain factual errors about brands (PersonQA, 2024)
- 1,300% increase in agentic AI traffic, Jan to Aug 2025 (BrightEdge)
- 44% of ChatGPT citations come from the first third of content (SE Ranking, 2025)

## Scope

**This skill:** ChatGPT, Perplexity, Claude, Gemini, Copilot, Google AI Overviews, AI shopping agents, autonomous AI agents.

**Companion skill:** `ai-seo-skill` handles traditional search (Google rankings, technical SEO, local maps, YouTube, app stores). Strong traditional SEO is a prerequisite for AI visibility: 87% of ChatGPT citations match Bing's top 10 organic results.

## Reference Files

Load only the 1 to 2 files from `references/` most relevant to the user's specific question. Do not load all files. This keeps responses focused and avoids unnecessary token usage.

| Need | Load |
|------|------|
| Citation hooks, original data tactics, author authority | `references/geo-llmo.md` |
| Brand accuracy audits, Golden Prompts, hallucination detection | `references/aivo.md` |
| Multi-turn dialogue, fanout prompts, conversation flow | `references/cso.md` |
| AI shopping feeds, Google AI Shopping, ChatGPT Checkout | `references/ai-shopping.md` |
| Agentic AI, autonomous agents, ReserveAction schema | `references/aaio-overviews.md` |
| Cross-modal content, image+text, video analysis | `references/multimodal.md` |
| Reddit optimization, subreddit strategy, karma building | `references/social-video-visual.md` |
| Statistics with sources (for audits and reports) | `references/statistics.md` |
| Report templates, audit formats, schema examples | `references/output-templates.md` |
| SEvO meta-framework (full audit only) | `references/sevo.md` |

Only load `statistics.md` when producing audits, reports, or client-facing content that needs sourced data. Only load `output-templates.md` when the user explicitly requests a deliverable format.

## The 8 Disciplines

### Core: Getting Cited

**1. GEO (Generative Engine Optimization)**
The strategic framework for AI citation. How to get your content extracted, synthesized, and attributed by AI models. Five types of citation hooks: statistic with source, clear definition, named framework, direct comparison, and authority signal. Write 40 to 60 word paragraphs that AI can quote. Place key claims in the first third of content. Publish original data that gives AI something unique to cite.

**2. LLMO (Large Language Model Optimization)**
The technical execution layer (~80% overlap with GEO). Clean semantic HTML so AI crawlers can parse your content. Entity-attribute-value relationships stated explicitly ("X is Y", "X does Y"). Cross-platform brand mention consistency. No content hidden behind JavaScript rendering. LLMO handles the machine-readable side; GEO handles the strategic side.

**3. AIVO (AI Visibility Optimization)**
Brand accuracy monitoring across all AI platforms. Run Golden Prompt audits: test 15 to 20 brand-specific queries monthly across ChatGPT, Perplexity, Gemini, and Claude. Log hallucinations, factual errors, and competitor misattributions. Track Share of Model (how often your brand appears vs competitors for category queries). 33 to 48% of AI responses contain errors. 58% of consumers lose trust after AI misrepresents a brand.

**4. CSO (Conversational Search Optimization)**
AI conversations are multi-turn. Users ask follow-ups. Optimize for the full conversation, not just the first query. Map fanout prompts (the questions users ask after the initial answer). Structure content as question-answer pairs. Cover follow-up intent explicitly. 44% of citations come from the first third of content, so front-load your strongest material.

### Commerce: AI Agents and Shopping

**5. AAIO (Agentic AI Optimization)**
Autonomous AI agents are starting to browse, compare, book, and buy on behalf of users. Agentic traffic increased 1,300% in the first 8 months of 2025. To be agent-ready: machine-readable pricing (not trapped in images or PDFs), ReserveAction/BuyAction schema, semantic HTML, clean product/service feeds, server-rendered content.

**6. AI Shopping Optimization**
Product visibility in AI-powered shopping experiences: Google AI Mode Shopping, ChatGPT Instant Checkout, Perplexity Buy With Pro. Requirements: complete Product schema with UPC/GTIN, structured product feeds via Google Merchant Center, real-time inventory and pricing, high-quality product images with descriptive alt text.

### Channels: Where AI Gets Its Data

**7. Reddit Optimization**
Reddit is the #1 source for AI citations at 40.1% of all references. 80M weekly searches happen on Reddit. The platform's text-heavy, discussion format is uniquely valuable for LLM training data. Tactics: build subreddit authority through authentic participation, accumulate comment karma, provide genuinely helpful answers, run strategic AMAs. Do not astroturf. Reddit communities detect and punish inauthentic behavior.

**8. Multimodal Search**
AI platforms increasingly process multiple inputs simultaneously: photo + text, voice + image, video frame analysis. Content with multi-modal elements sees +317% AI citation boost. Tactics: pair images with descriptive alt text that reinforces the text content, embed video with full transcripts, create visual content that adds information (not decorative stock photos).

## Prioritization by Business Type

Before recommending disciplines, determine the client's business type, current AI visibility, and content maturity. Then use this matrix.

| Business Type | Critical (now) | High (60 days) | Medium (later) |
|---------------|---------------|----------------|---------------|
| SaaS / B2B | GEO, LLMO | AIVO, CSO, Reddit | AAIO, Multimodal |
| E-Commerce | AI Shopping, AAIO | GEO, AIVO, LLMO | CSO, Multimodal, Reddit |
| Local Services | AIVO, CSO | GEO, Multimodal | LLMO, AAIO, Reddit |
| Professional Services | GEO, AIVO | LLMO, CSO | Reddit, Multimodal, AAIO |
| Healthcare | AIVO, GEO | CSO, LLMO, Multimodal | Reddit, AAIO |
| Media / Publishing | GEO, LLMO, Reddit | CSO, Multimodal | AIVO, AAIO |

## Quick-Start (4 Weeks)

### Week 1: Audit
- Golden Prompt audit: 15 to 20 brand queries across ChatGPT, Perplexity, Gemini, Claude
- Document current Share of Model vs competitors
- Log all hallucinations and factual errors
- Audit top 10 pages for citation hooks

### Week 2: Citation Infrastructure
- Add/fix Organization and Person schema with E-E-A-T signals
- Restructure top 10 pages: 40 to 60 word quotable paragraphs
- Add 2+ citation hooks per page (stat, definition, framework, comparison, or authority)
- Clean up HTML: semantic tags, no JS-only content, proper heading hierarchy

### Week 3: Content and Channels
- Publish 2 to 3 original data pieces (surveys, benchmarks, case studies)
- Begin authentic Reddit participation in relevant subreddits
- Add multi-modal elements to top content (descriptive images, video with transcripts)
- Create conversational Q&A content for top 5 customer questions

### Week 4: Commerce and Measurement
- E-commerce: verify product feeds, add Product schema with UPC/GTIN
- Services: add ReserveAction schema, machine-readable pricing
- Set up monthly Golden Prompt re-audit schedule
- Establish Share of Model tracking
- Document baselines for 30/60/90 comparison

## Citation Optimization Checklist

Run against any page being optimized:

**Content:**
- [ ] 2+ citation hooks (statistic with source, definition, framework, comparison, authority)
- [ ] 40 to 60 word quotable paragraphs
- [ ] Key claims in first third of content
- [ ] Explicit entity-attribute-value statements
- [ ] Original data or proprietary research
- [ ] Question-answer pairs for conversational patterns

**Technical:**
- [ ] Clean semantic HTML, proper heading hierarchy
- [ ] Content accessible without JavaScript rendering
- [ ] Organization schema with complete properties
- [ ] Author page with Person schema and E-E-A-T credentials
- [ ] Consistent brand facts across all web properties

**Multi-Modal:**
- [ ] Images with genuinely descriptive alt text
- [ ] Video with embedded transcripts
- [ ] Visual content reinforces text claims

**Brand Accuracy:**
- [ ] Brand name spelled consistently everywhere
- [ ] Key facts stated explicitly (founding, location, offerings)
- [ ] No contradictory info across pages/platforms
- [ ] Wikipedia/Wikidata entry accurate if applicable

**Commerce (if applicable):**
- [ ] Product schema with UPC/GTIN, price, availability
- [ ] Machine-readable pricing
- [ ] ReserveAction or BuyAction schema
- [ ] Product feed submitted to Google Merchant Center

## Output Formats

| Output | When |
|--------|------|
| AIVO Audit Report | Monthly brand accuracy across AI platforms |
| Citation Gap Analysis | Client vs competitor citation rates |
| Golden Prompt Results | AI response accuracy for brand queries |
| Schema Implementation Guide | Structured data recommendations |
| Content Optimization Brief | Page-level citation hook placement |
| Share of Model Dashboard | Brand mention frequency over time |
| Reddit Strategy Plan | Subreddit targeting and participation cadence |
| 4-Week Quick-Start Plan | Customized roadmap by business type |

Load `output-templates.md` for full templates. Always include statistics from `statistics.md` with source attribution.
